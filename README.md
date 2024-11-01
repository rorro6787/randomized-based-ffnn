# Randomized-Based Feedforward Neural Network
Welcome to the Advanced Neural Network for Multi-Class Classification repository! This project implements a PyTorch-based neural network following the novel approach outlined in "A Multi-Class Classification Model with Parameterized Target Outputs for Randomized-Based Feedforward Neural Networks" (Applied Soft Computing, 2023). Our goal is to bring the advanced theoretical framework of parameterized target outputs into a practical, high-performance model that simplifies multi-class classification with enhanced separability and generalization. Through this implementation, we aim to bridge theory and practice, providing a resource for learning and experimentation with PyTorch.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Requirements

- Python 3.X.X

## Installation

1. Clone the repository:
   
    ```sh
    git clone https://github.com/rorro6787/randomized-based-feedforward-neural-network.git
    ```
3. Navigate to the project directory:
   
    ```sh
    cd randomized-based-feedforward-neural-network/src
    ```
5. (Optional) Create a virtual environment:
   
    ```sh
    python3 -m venv venv
    .\venv\Scripts\activate  # On macOS/Linux use 'python -m venv venv
                                                   source venv/bin/activate'
    ```
7. Install the required packages:
   
    ```sh
    pip install -r requirements.txt
    ```
5. Select venv as your python interpreter (in VSC):
   
    ```sh
    > Python: Select Interpreter
    .\venv\Scripts\python.exe # On macOS/Linux use './venv/bin/python'
    ```

## Usage

Run the following script to train and test the neural network described in the article:

```sh
python feedforward_network.py
```

## Contributors

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/rorro6787) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emilio-rodrigo-carreira-villalta-2a62aa250/) **Emilio Rodrigo Carreira Villalta**

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request

## Acknowledgements
Inspired by various tutorials and resources on neural networks and my teacher's Francisco Fernández Navarro's article: "A multi-class classification model with parametrized target outputs for randomized-based feedforward neural networks:" [Read the Article](https://www.sciencedirect.com/science/article/pii/S1568494622009632?ref=pdf_download&fr=RR-9&rr=8dbe252cc92fcfce).

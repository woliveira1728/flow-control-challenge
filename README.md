# Flow Control Challenge

## Description

This project is a flow control challenge in Java. The goal is to implement a count between two integers provided by the user. If the second number is less than or equal to the first, a custom exception is thrown.

## Project Structure

The project contains the following main files:

- `Contador.java`: Main class that prompts the user for two parameters and calls the counting method.
- `ParametrosInvalidosException.java`: Custom exception thrown when the provided parameters are invalid.

## How to Use

### Prerequisites

- Java Development Kit (JDK) installed (version 8 or higher).

### Running the Program

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/username/flow-control-challenge.git
    ```

2. Navigate to the project directory:

    ```bash
    cd flow-control-challenge
    ```

3. Compile the Java files:

    ```bash
    javac Contador.java ParametrosInvalidosException.java
    ```

4. Run the program:

    ```bash
    java Contador
    ```

5. Enter the requested values:

    - First parameter: An integer.
    - Second parameter: An integer greater than the first.

### Execution Example

    - Digite o primeiro parâmetro
    - 5
    - Digite o segundo parâmetro
    - 10
    - Imprimindo o número 1
    - Imprimindo o número 2
    - Imprimindo o número 3
    - Imprimindo o número 4
    - Imprimindo o número 5


#### Invalid Input

    - Digite o primeiro parâmetro
    - 10
    - Digite o segundo parâmetro
    - 5
    - O segundo parâmetro deve ser maior que o primeiro

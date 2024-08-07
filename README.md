# OPA Policy Engine Integration

## Description

This project is a simple sample of integrating the OPA policy engine with a simple account application. 

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/HsuehYangYu/OPA_Policy_Engine.git
    ```

2. Navigate to the project directory:

    ```sh
    cd OPA_Policy_Engine
    ```

3. Build the project using Maven:

    ```sh
    mvn clean install
    ```

## Integration Tests

1. Start the OPA server pointing to the folder containinf the authorization policy file.


    ```sh
    opa run -w -s src/test/rego
    ```

2. Run the integration tests

    ```sh
    mvn test
    ```


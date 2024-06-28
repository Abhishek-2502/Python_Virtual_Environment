# Python Virtual Environment Setup

This guide provides step-by-step instructions to create and activate a Python virtual environment using `virtualenv`.

## Prerequisites

- Ensure Python 3 is installed on your system. You can download it from the [official Python website](https://www.python.org/downloads/).
- Ensure `pip` is installed. `pip` typically comes with Python, but you can install it separately if needed.

## Steps to Create a Virtual Environment

1. **Install `virtualenv`**:
    ```bash
    pip install virtualenv
    ```

2. **Create a Virtual Environment**:
    ```bash
    virtualenv -p python3 env
    ```
    This command creates a virtual environment named `env` using Python 3.

3. **Activate the Virtual Environment**:

    - **For Linux/MacOS**:
        ```bash
        source env/bin/activate
        ```
    - **For Windows**:
        ```bash
        env\Scripts\activate
        ```

## Deactivating the Virtual Environment

To deactivate the virtual environment, simply run:
```bash
deactivate
```

## Additional Information

- **Installing Packages**: Once the virtual environment is activated, you can install packages using `pip` as usual, e.g., 

    ```bash
    pip install package_name
    ```
- **Freezing Requirements**: To freeze the installed packages into a `requirements.txt` file, use:
    ```bash
    pip freeze > requirements.txt
    ```
- **Installing from `requirements.txt`**: To install packages from a `requirements.txt` file, use:
    ```bash
    pip install -r requirements.txt
    ```

## Author

Abhishek Rajput<br>
Palak Rajput

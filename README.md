# Simple Flask Project

A simple Python Flask project with basic testing and CI/CD using GitHub Actions.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Running the Application](#running-the-application)
- [Running Tests](#running-tests)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

To run this project, you need the following installed on your system:

- Python 3
- pip (Python package manager)

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/ixtimesix/gh-actions-flask.git
   ```

2. Change into the project directory:
   ```bash
   cd gh-actions-flask
   ```
   
3. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use venv\Scripts\activate
   ```
   
4. Install project dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application

To run the Flask application, execute the following command:

```bash
python app.py
```

The application will start on http://localhost:5000. Open a web browser and navigate to this address to view the "Hello, World!" message.

### Running Tests

You can run tests using the built-in unittest framework. Execute the following command to run the tests:

```bash
python -m unittest discover
```

This will run the test suite and report the results.

### Contributing

We welcome contributions! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: git checkout -b feature/your-feature-name.
3. Make your changes and commit them: git commit -m "Add your feature".
4. Push to your fork: git push origin feature/your-feature-name.
5. Create a pull request in the original repository.

### License

This project is licensed under the MIT License - see the LICENSE file for details.

# Credit Risk Score Generator

This project is a startup that uses Python in the stack to generate credit risk scores using AI and an unusual source of data. The project has an awesome interface and an API with documentation.

## Project Structure

- `app/`: This directory contains the main application code.
  - `__init__.py`: Initializes the Flask application.
  - `main.py`: Runs the Flask application.
  - `api.py`: Defines the API endpoints.
  - `models.py`: Defines the data models.
  - `utils.py`: Contains utility functions.
- `tests/`: This directory contains the test code.
  - `__init__.py`: Initializes the test suite.
  - `test_api.py`: Tests the API endpoints.
  - `test_models.py`: Tests the data models.
  - `test_utils.py`: Tests the utility functions.
- `Dockerfile`: Defines the Docker image for the application.
- `docker-compose.yml`: Defines the Docker Compose configuration.
- `.github/workflows/main.yml`: Defines the GitHub Actions workflow.
- `.pre-commit-config.yaml`: Defines the pre-commit hooks.

## Installation

To install the project dependencies, run:

```
pip install -r requirements.txt
```

## Usage

To run the application, run:

```
python app/main.py
```

The API documentation can be found at `http://localhost:5000/docs`.

## Testing

To run the tests, run:

```
pytest
```

## Contributing

Contributions are welcome! Please see the [contributing guidelines](CONTRIBUTING.md) for more information.

## License

This project is licensed under the [MIT License](LICENSE).
# Instructions and Guidelines

## Notes
```
No need to test email. Email accounts not active
```

## Creating a local virtual environment
py -3 -m venv venv

## Pip installs
```
pip install -r requirements.txt
pip install -e src/
```

## Running the tests
```
pytest tests/unit
pytest tests/integration
pytest tests/e2e
```
# Machine Learning and Techniques Lab Manual Program

## Setup Instructions

### 1. Create a Virtual Environment

```bash
# Using venv
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate

# On macOS/Linux:
source venv/bin/activate
```

```bash
# If activation fails, run:
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

### 2. Install Dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 3. Project Structure

```
.
├── data/
├── src/
├── requirements.txt
└── README.md
```

### 4. Deactivate Virtual Environment

```bash
deactivate
```

## Requirements

- Python 3.8 or higher
- pip package manager

## Notes

- Keep `requirements.txt` updated: `pip freeze > requirements.txt`
- Never commit the `venv/` directory to version control

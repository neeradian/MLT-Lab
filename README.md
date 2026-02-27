# Machine Learning and Techniques Lab Manual Program

## Setup Instructions

### 1. Create a Virtual Environment



```bash
# Using venv
python -m venv venv
```
### 2. Activate virtual environment

####  On Windows:
```bash
venv\Scripts\activate
```

##### On macOS/Linux:
```bash
source venv/bin/activate
```

```bash
# If activation fails, run:
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

### 3. Install Dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Project Structure

```
.
├── data/
├── src/
├── requirements.txt
└── README.md
```

### 5. Deactivate Virtual Environment

```bash
deactivate
```

## Requirements

- Python 3.8 or higher
- pip package manager

## Notes

- Keep `requirements.txt` updated 
```bash 
pip freeze > requirements.txt
```
- Never commit the `.venv/` directory to version control

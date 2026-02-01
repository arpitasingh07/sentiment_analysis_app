## Quick Start

### Group ID: 61

### Group Members:

1. Arpita Singh (2024AA05027)
2. Rahul Sharma (2024AA05893)
3. Sachit Pandey (2024AA05023)
4. Avishek Ghatak (2024AA05895)
5. Anoushka Guleria (2023AA05527)

---

### Prerequisites

- Python 3.10+
- 100MB free space
- Modern web browser
- Internet connection

### Setup & Run

**macOS/Linux:**

```bash
cd submission/app
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python3 app.py
```

**Windows:**

```bash
cd submission\app
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

**Then open:** http://localhost:5001

---

## Troubleshooting

| Issue                 | Solution                                                                                           |
| --------------------- | -------------------------------------------------------------------------------------------------- |
| Port 5001 in use      | Change port in app.py or kill process: `lsof -i :5001 \| awk '{print $2}' \| xargs kill -9`        |
| Module not found      | Activate venv first: `source venv/bin/activate` (macOS/Linux) or `venv\Scripts\activate` (Windows) |
| Python not found      | Install Python from python.org or use `python` instead of `python3`                                |
| SSL certificate error | Already handled in code. Restart the app if needed.                                                |

---

## Using the Application

**Three tabs available:**

1. **Text Input** - Paste text and analyze (up to 5000 chars)
2. **File Upload** - Upload .txt files for line-by-line analysis
3. **Batch Analysis** - Multiple texts at once (one per line, max 50)

---

## Stopping the App

Press `CTRL+C` in the terminal to stop the application.

---

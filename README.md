Climate Challenge Week 0

This repository is a starter structure for Python-based climate challenge work.

Project Structure

- src: source code
- scripts: helper scripts for running tasks
- tests: automated tests
- notebooks: exploratory notebooks

Prerequisites

- Git
- Python 3.11 or newer

Clone The Repository

1. Open a terminal.
2. Clone the repository:

```bash
git clone <your-repo-url>
```

3. Move into the project folder:

```bash
cd climate-challenge-week0
```

Set Up A Local Python Environment

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it:

Windows PowerShell:

```powershell
.\\.venv\\Scripts\\Activate.ps1
```

Windows Command Prompt:

```bat
.venv\\Scripts\\activate.bat
```

macOS/Linux:

```bash
source .venv/bin/activate
```

If PowerShell blocks activation, run this once in PowerShell and then reactivate:

```powershell
Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
```

Install Dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

Run The Project Locally

This starter repo does not yet include a single app entrypoint. Use one of these patterns as you add code:

- Run a module from src:

```bash
python -m src.<module_name>
```

- Run a script from scripts:

```bash
python scripts/<script_name>.py
```

Run Tests

Install pytest if needed:

```bash
pip install pytest
```

Run all tests:

```bash
python -m pytest
```

Notes

- The CI workflow is in .github/workflows/unittests.yml.
- CI triggers on pushes to main and on pull requests.

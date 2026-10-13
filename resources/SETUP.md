# Setup on Windows
1. Open the repository folder in VS Code.
2. In a terminal, run `py --version`.
3. Create and activate a virtual environment:
   ```powershell
   py -m venv .venv
   .venv\Scripts\activate
   python -m pip install --upgrade pip
   pip install -r requirements.txt
   jupyter lab
   ```
4. Install the Python and Jupyter extensions in VS Code if using VS Code notebooks.
5. Run notebooks from top to bottom and do not commit private data, credentials, or unauthorized datasets.

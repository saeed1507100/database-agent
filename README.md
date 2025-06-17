# database-agent
An AI agent to interact with your database.

## Setup Instructions

### 1. Create and activate a Python virtual environment (Python 3.11)

```bash
python3.11 -m venv .venv
source .venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 2. Install project dependencies

```bash
pip install -r requirements.txt
```

### 3. Create a Jupyter kernel for the virtual environment

```bash
python -m ipykernel install --user --name=venv --display-name "Python 3.11 (database-agent)"
```

### 4. Add your Google API key

- Create a `.env` file in the project root directory
- Add the following line, replacing with your actual API key:

```env
GOOGLE_API_KEY=your_google_api_key_here
```

### 5. Launch Jupyter Notebook and select the correct kernel

```bash
jupyter notebook
```

- Open the notebook located at `notebooks/dev.ipynb`
- Select the kernel named **Python 3.11 (database-agent)**

---

## Usage

- Use the Jupyter notebook to develop and test the AI agent’s capabilities for interacting with tabular data and databases.
- Modify, run, and iterate on the notebook cells as needed.

---

## Future Enhancements

- Expand AI agent functionality to handle complex database queries.
- Support integration with multiple data sources.
- Develop interactive user interfaces.

---

## License

This project is licensed under the MIT License.

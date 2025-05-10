# Data Wrangling - Assignment 3

[Code on GitHub](https://github.com/RobinfRoth/dawr-ass3)

## Load Persisted Data

You can download the persisted data from [GitHub](https://github.com/RobinfRoth/dawr-ass3/releases/download/Raw_Data/raw_data.zip).
For the notebook to work correctly place the ZIP file's content directly in `./raw_data/`.

Example how this can be done in bash on Linux:

```bash
cd ./raw_data/
wget https://github.com/RobinfRoth/dawr-ass3/releases/download/Raw_Data/raw_data.zip
unzip raw_data.zip
```

## Installation

It is recommended to setup a Python virtualenv (venv) to install the dependencies into before running the notebook.

Follow these steps to install a venv:

1. Ensure Python 3.10 or newer is installed.

2. Create a venv for this project by running these commands in the root folder of this project:

MacOS / Linux:
```bash
python3 -m venv .venv
```

Windows:
```powershell
python -m venv .venv
```

3. Then, activate the venv in the project folder by running:

MacOS / Linux:
```bash
source .venv/bin/activate
```

Windows:
```powershell
.venv\Scripts\activate
```

4. Next, install all required dependencies into the venv:

MacOS / Linux:
```bash
pip3 install -r requirements.txt
```

Windows:
```powershell
pip install -r requirements.txt
```

5. Finally, configure the `ipython`-kernel to use the venv, by running:

    MacOS / Linux:
    ```bash
    python3 -m ipykernel install --user --name=.venv
    ```

    Windows:
    ```powershell
    python -m ipykernel install --user --name=.venv
    ```

6. You can now run the Jupyter notebook. Make sure you select the `.venv` kernel to use the venv in the notebook.

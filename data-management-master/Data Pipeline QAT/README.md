# Data pipeline QAT

A brief description of what this project does and who it's for

## Configurations

Create a file name config.json. Paste the following content into config.json

```json
{
  "mysql": {
    "host": "localhost",
    "user": "root",
    "password": "",
    "port": "3307"
  },
  "postgres": {
    "database": "master",
    "user": "postgres",
    "password": "wGMCAE6zFHcyrBmXtus97JPanxvkY4fb",
    "host": "127.0.0.1",
    "port": "5432"
  }
}
```

You may update the contents of config.json to match your environment.

## Python packages

Open QAT.ipynb and run the following:

```bash
pip install mysql-connector-python
pip install psycopg2-binary
pip install python-docx
```
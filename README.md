### Running Notes

Each folder has a `requirements.txt` file. To build an 
environment you should use `uv` 

```sh
pip install uv
```

Then make a cirual environemnt 

```sh
uv venv $(PATH)/.venv
source $(PATH)/.venv/bin/activate  
```

Then install requirements

```sh
uv pip install -r $(PATH)/.venv/requirements.txt
```
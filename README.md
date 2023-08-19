# duckdb-huggingface

This repo uses the Hugging Face dataset hub to explore remote data using DuckDB.
See https://huggingface.co/blog/hub-duckdb.



# Installing environment using mamba:

## If not already installed, install mamba:
```bash
brew install micromamba
```

Update mamba
```bash
micromamba self-update
```

Create the mamba environment using this file by running the following command in your terminal:
```bash
mamba env create -f environment.yaml
```

This will create a new mamba environment with Python 3.10, pip, pandas, and Faker, and more installed. You can activate the environment with the command:
```bash
mamba activate duckdb_huggingface
```

To update a mamba environment based on an updated environment.yaml file, you can use the following command:
```bash
mamba env update --file environment.yaml --prune
```

To list all installed packages in the current environment:
```bash
mamba list
```


# Installing environment using conda:

You can use the same commands as above, but replace mamba with conda.
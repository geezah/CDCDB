# CDCDB
To create a new version
1. [Install `uv`](https://docs.astral.sh/uv/getting-started/installation/)
2. Enter your AACT credentials into `input_data/aact_credentials.json`
3. Run `uv sync --frozen` in the top-level directory of this repository
5. Create a new CDCDB dump by running the provided script 
  > ./create_version.sh
  
Note, there are plenty of caches used in this system, therefore the first run would be longer.

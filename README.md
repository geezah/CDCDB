# CDCDB
To create a new version
1. [Install `uv`](https://docs.astral.sh/uv/getting-started/installation/)
2. Enter your AACT credentials into `input_data/aact_credentials.json`
3. Execute the command `uv sync --frozen` from the root directory of the repository.
5. Generate the new CDCDB dump by executing the command `bash ./create_version.sh` form the root directory of the repository: `
  
Note, there are plenty of caches used in this system, therefore the first run would be longer.

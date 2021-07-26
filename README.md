# AIRFLOW SETUP - Manual vs DOCKER

This repository contains Both CLI and Docker commands needed to setup a basic environment for Airflow to run.
Using the the Docker approach is highly recommedned and less stessful. However , if you want a step by step approach, you can use the manual approach.

# Dependencies

If you are using the docker approach , kindly ensure that you already have Docker installed . If not , use the command below :

- Docker
```bash
brew install Docker
```

# File structure
.
├── LICENSE
├── README.md
└── airflow-setup
    ├── Dockerfile
    ├── constraints-3.8.txt
    ├── docs
    │   └── cli_commands.txt
    └── entrypoint.sh
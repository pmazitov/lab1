# PostgreSQL & Jupyter Lab

## Installation  

```
git clone https://github.com/pmazitov/lab1.git

cd lab1/init_database

sudo docker-compose --project-name="habr-pg-14" up -d
```
    
## Log in Jupyter Lab instance
Go to http://localhost:8888/
Login credentials can be found in [docker-compose.yml](./init_database/docker-compose.yml)


## Repo structure

    ├── lab1                <- main folder
        |
        ├── init_database   <- folder with docker-compose
        |        
        lab1.ipynb          <- jupyter-notebook with source code


## Usage

You can see example of usage in [lab1.ipynb](./lab1.ipynb)
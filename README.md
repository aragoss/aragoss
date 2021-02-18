A docker based local environment

## Setup

Clone repo with the submodules:

```bash
git clone --recursive git@github.com:argosp/argos.git
```

Go inside folder

```bash
cd argos
```

Copy configuration template and edit if needed

```bash
cp .env.example .env
```

Build the docker images

```bash
docker-compose build
```

Run the project

```bash
docker-compose up -d
```
Dev enviroment:  
https://argos.new-aks-stage.linnovate.net/

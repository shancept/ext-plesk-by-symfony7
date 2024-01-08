# Demo extension based on symfony 7

## Install by cookiecutter

```bash
docker run -it -v $(pwd):/app{project_slug} cookiecutter-ext shancept/ext-plesk-symfony7
```

**Note: {project_slug} is the name of your project, you must replace it with your project name**

## Project build

```bash
composer install
```
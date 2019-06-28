# jupyter-test

## make environment

  ```bash
  # create docker image
  docker-compose build

  # start jupyter notebook
  docker-compose up -d
  ```

## connect jupyter notebook

  ```bash
  # show docker logs
  docker logs -f < your docker container id >
  ```

   execute as log messages
  ```
    To access the notebook, open this file in a browser:
        file:///home/jovyan/.local/share/jupyter/runtime/nbserver-7-open.html
    Or copy and paste one of these URLs:
        http://(< your docker container id > or 127.0.0.1):8888/?token=< your token >
  ```

## play jupyter notebook

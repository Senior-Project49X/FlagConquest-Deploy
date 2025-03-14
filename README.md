# FlagConquest-Deploy
This readme will show instruction how to deploy Flagconquest website with docker
## Please do the following steps
  1. Copy `env.template` to `.env` file.
     
  2.Edit the following variables in the .env file accordingly. (On this part please contact professor to get these value)
    `CLIENT ID`
    `CLIENT SECRET`
    `CMU_ENTRAID_REDIRECT_URL`
  
  3.run command below to start server
    ```bash
    docker compose up
    ```
When all docker container is running the sever should be in:
  Frontend: [http://localhost:3003](http://localhost:3003)
  Backend: [http://localhost:5003](http://localhost:5003)

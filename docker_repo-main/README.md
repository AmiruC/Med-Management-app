## Build and run instructions

## Git related instructions
### How to clone the repository correctly
Run the following command to clone this repository and all submodules within it:
```
git clone --recurse-submodules -j 4 https://github.com/team1sept/docker_repo.git
cd docker_repo
git submodule foreach git pull origin master
```

### How to correctly pull and update this repository and all submodules within it:
Run the following commands
```
git pull
git submodule foreach git pull origin master
```

### How to use
1. Ensure that your local docker service is running.
2. Run `docker compose build` to build all the containers.
2. Run `docker compose up -d` to run all the services.
3. Run `docker compose down` to stop all the services.

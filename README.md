# MasterClass

This is master class learning manegement system.

## Cloning
- `git clone --recurse-submodules https://github.com/MuhammeedAlaa/MasterClass`
## Requierments

- you must have the .env file in the MasterClassBackEnd directory.

## Example for .env
```
     JWT_SECRET=secret
     JWT_EXP_DATE=10000
     MAIL_SERVICE=smtp.gmail.com
     MAIL_PORT=587
     EMAIL=example@gmail.com
     PASSWORD=password
     AUTHENTICATION=plain
```

- You must have the master.key file in the MasterClassBackEnd/config directory

- You must have Docker and docker-compose installed.

## Install instructions
- Run `docker-compose up -d` on this directory
- Head your request to `localhost:8080`

# ft_transcendence project from 42
This is the root of the project, it includes git submodules to frontend and backend, a docker-compose file and some other stuff.

## Technologies / Stack
- Vue.js 3 (Frontend framework)
- Socket.io (Sockets)
- P5.js (Graphics)
- NestJS (Backend framework)
- TypeORM (Database ORM)

## How do I run the project?
It runs using docker, all you have to do to start the project is:
- Copy .env.example to .env and configure the variables
- Configure the backend local address in the front: front/src/utils/const.ts
- Run `docker compose up --build` and it should run, have fun! 🕺💃

## Ressources
Please refer to the ressources section in frontend and backend's READMEs

## Get computer local ip address
- MacOS: `ipconfig getifaddr en0`
- Linux: `ip a | grep inet`

## The team
- mdesoeuvre
- tjolivea
- mrozniec

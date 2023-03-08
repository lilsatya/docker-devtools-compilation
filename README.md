# Docker Development Tools Compilation

## What is this?

Compilation of docker-compose files for local development. Including:

- elastic stack
- mysql
- postgres
- rabbitmq
- redis

## Why did you make this?

Having so many supporting tools was a hassle for me, and I don't want to slow down my PC using native client. In this case I can just turn on all of the docker container everytime I'm working and turn off whenever I'm done.

## How do I use this?

It's fairly simple!

You just need to ```cd``` to specific folder and run ```docker-compose up -d```

For example:

```bash
  cd monitoring && docker-compose up -d
```

As for myself, I like to keep the container exist in docker, so that i may turn it off and on anytime I wanted to.

## Requirement

Just Docker! Better if you use docker desktop for easier switch.


## Contributing

You can contribute by creating PR if you want new tools added, might help some people

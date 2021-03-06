
# Readme #

This is the readme for this project.  It will include any useful links and commands to run.

## Install Visual Studio Code ##

```https://code.visualstudio.com/Download```

## Install Git ##

1. get a github account at github.com

2. install git locally

```https://github.com/git-guides/install-git```

## Install NodeJs ##

Install following the instructions at the following web page:

```https://nodejs.org/en/download/```



## Validation Steps ##

How to tell you have git installed:

```$git version```

How to tell you have node installed:

```$node -v```

## Dependencies and NPM ##

We want to use large chunks of code that others have written to interact with Ethereum, like the web3 package.  Do this, we need to set up the Node Package Manager (npm).

From inside your folder, to create your own package.json:

```$npm init```


## update .env file with details ##
INFURA_TOKEN
CONTRACT_ADDRESS
OWNER_ADDRESS
SUPER_SECRET_PRIVATE_KEY

## Distributing tokens to the given addresses ##

To execute a javascript file using node.js, run the following command:

```$node distribute.js```


## CURL accessing of handlers"

To POST to a route, execute the following CURL command:

```curl -XPOST http://localhost:8080/transfer -H 'content-type: application/json' -d '{"account_to": "0x4d60E7f9d4901816981a0E4c6D95F394159C6371", "amount": "123000"}'```


## Docker ##

### View running docker containers ###

```docker ps```

### build a docker container ###

```docker build -t nci/lab2021 .```

### run the image ###

```docker run -p 8090:8080 --name nci -d nci/lab2021```

### kill a running container ###
```docker kill [name]```

### start/stop a container ###
```docker start/stop [name]```

### view logs ###
```docker logs [name]```

### view logs inside a container ###
```docker logs -f [name]```
#   b l o c k c h a i n _ 2 0 1 8 6 1 6 9 _ j a n i t 
 
 
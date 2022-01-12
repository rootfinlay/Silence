# Silence

Silence - a P2P private messaging service

cli: work in progress

desktop version: work in progress

server: work in progress

  

## Setting Up a Server
### Initial Setup

```console

# clone repo

$ git clone https://github.com/rootfinlay/Silence

  

# cd into directory

$ cd Silence/server

  

# start mysql service

$ apt-get install mysql # if not already installed

$ sudo service mysql start

  

# edit configuration of setup.go

$ nano setup.go

# CHANGE THIS to your desired database

  

const (

username = "root" # Local user to make database

password = "rootpassword" # Password for local user

hostname = "127.0.0.1:3306" # Host for database to be created

dbname = "silenceserver" # Name you want for the database

)

  

# run the script

$ go run setup.go

```

### Running the server (server.go still a work in progress)

```console

# ( Optional ) Build the server

$ go build server.go

# Run the serevr

$ go run server.go

```

## Command Line Interface Version
### Work in progress

## Desktop Version
### Work in progress

## Web Version
### Work in progress

## Mobile Version
### Work in progress
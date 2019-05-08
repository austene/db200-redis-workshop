# db200-redis-workshop

## Purpose of Program
Tests the following commands to a Redis:
- GET
- SET
- INCR
- DEL
- EXPIRE
- TTL
- RPUSH
- LPUSH
- LRANGE
- LLEN
- LPOP
- RPOP
- SADD
- SREM
- SISMEMBER
- SMEMBERS
- SUNION

## Setup

### Clone
Clone Respository
### Install
1. Dependencies
```
$ npm install
```
2. Install 
#### Installing on Windows

- [Redis-x64-3.0.504.msi](https://github.com/MicrosoftArchive/redis/releases/download/win-3.0.504/Redis-x64-3.0.504.msi)
- [medis-latest.exe](https://s3-us-west-1.amazonaws.com/oca-start-now/Medis/win/medis-latest.exe)
- Redis should start running on it's own.
- Open Medis, click connect
- Click Terminal tab (top right)
- Type `INFO` and hit return
- This should output general information about the running instance

#### Installing on OSX

- [Homebrew](https://brew.sh/) package manager
- Run `brew install redis`
- Download, unzip, and add the Medis app to your Applications folder: [medis-latest.zip](https://s3-us-west-1.amazonaws.com/oca-start-now/Medis/osx/medis-latest.zip)
- Use the `redis-server` command in a terminal to start Redis
    - Note that this creates a Redis database file in the directory you're in
- Open Medis, click connect
- Open Medis, click connect
- Click Terminal tab (top right)
- Type `INFO` and hit return
- This should output general information about the running instance

## Testing
```
$ npm test
```
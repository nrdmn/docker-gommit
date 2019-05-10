# Gommit
Gommit analyze commits messages to ensure they follow defined pattern. See https://github.com/antham/gommit for more information.

## Tags
- [`2.2.0`, `latest` _(2.2.0/Dockerfile)_](https://github.com/nrdmn/docker-gommit/blob/master/2.2.0/Dockerfile)
- [`2.1.3` _(2.1.3/Dockerfile)_](https://github.com/nrdmn/docker-gommit/blob/master/2.1.3/Dockerfile)
- [`2.1.1` _(2.1.1/Dockerfile)_](https://github.com/nrdmn/docker-gommit/blob/master/2.1.1/Dockerfile)

## Usage
Mount the directory you want to check to /app.  
`docker run --rm -ti -v /path/to/repo:/app nrdmn/gommit check range HEAD~5 HEAD`

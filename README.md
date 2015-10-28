# Guacamole command line interface

A command line interface for https://github.com/amessinger/guacamole

Tested with Python 2.7 and 3.4

## Install

```
$ pip install https://github.com/pabluk/guacamole-cli/archive/master.zip
```

## Usage

### Uploading a file
To upload a file you need to specify your Guacamole server URL and a filename, for example:
```
$ guacamole --endpoint http://guacamole-server/files/ screenshot.jpg
http://guacamole-server/files/TRPm/0lkq/6egk/yHgg/OeDg/fVHr/screenshot.jpg
```

### Command options
Use `--help` to show the command options:
```
$ guacamole --help
usage: guacamole [-h] [-e ENDPOINT] filename

positional arguments:
  filename              file to upload

  optional arguments:
    -h, --help            show this help message and exit
      -e ENDPOINT, --endpoint ENDPOINT
                              Guacamole endpoint URL
```
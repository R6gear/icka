# icka

irccloud keep-alive

## usage

```sh
# build and install
$ make
$ make install

# execute with command line arguments
$ icka -email <email> -password <password>

# provide credentials from environment
$ ICKA_EMAIL=<email> ICKA_PASSWORD=<password> icka

# run once every hour, without exiting
$ icka -email <email> -password <password> -forever

$ icka -user-agent Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/133.0.0.0 Safari/537.36 -email <email> -password <password> -forever
```

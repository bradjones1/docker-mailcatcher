Docker: Mailcatcher
===================

Simple image to run [Mailcatcher](http://mailcatcher.me/)

Usage
-----

```sh
# Run a daemon container with mailcatcher started
sudo docker run \
    -d \ # Daemon mode
    --name mailcatcher \ # Give a name to your container, so you can start/stop or link it later
    bradjones1/docker-mailcatcher
```

Now you can access to the mailcatcher smtp throught the `1025` port and the web interface via `http://localhost:1080`
Feel free to map ports differently.

Credits
-------

Forked from [zolweb/docker-mailcatcher](https://github.com/zolweb/docker-mailcatcher)

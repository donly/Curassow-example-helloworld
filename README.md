# Hello World

This is a simple Swift Hello World website using the
[Currasow](https://github.com/kylef/Currasow) Swift pre-forking worker webserver.

## Usage

```shell
$ swift build --configuration release
$ ./.build/release/HelloWorld
Listening on 0.0.0.0:8000
```

### Deployment

This example can be deployed to Heroku using the
[heroku-buildpack-swift](https://github.com/kylef/heroku-buildpack-swift).

Click the button below to automatically set up this example to run on your own Heroku account.

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/kylef/Currasow-example-helloworld)

### Options

```shell
$ ./.build/release/HelloWorld --help
Usage:

    $ ./.build/release/HelloWorld

Options:
    --address
    --port
```

```shell
$ ./.build/release/HelloWorld --port 8080
```

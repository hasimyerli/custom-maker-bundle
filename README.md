# custom-maker-bundle
**Symfony version:** 4.2.2

**[Symfony maker-bundle](https://github.com/symfony/maker-bundle)** The MakerBundle is the fastest way to generate the most common code you'll need in a Symfony app: commands, controllers, form classes, event subscribers and more!

**[custom-maker-bundle](https://github.com/hasimyerli/custom-maker-bundle):** It works like ***make:controller***. Inherited from the 'maker-bundle'. Creates a folder named service and creates a class with the name you specify. 

## Getting Started
### Usage

***Review the directory 'src/Maker'.***

`make:service`
```bash
$ php bin/console make:service Hello
created: src/Service/Hello.php
Service class created.
```
`make:service --help`
```console
$ php bin/console make:service --help
Description:
  Creates a new service class.

Usage:
  make:service [<service-class>]

Arguments:
  service-class         Choose a name for your service class (e.g. Hello)

Options:
  -h, --help            Display this help message
  -q, --quiet           Do not output any message
  -V, --version         Display this application version
      --ansi            Force ANSI output
      --no-ansi         Disable ANSI output
  -n, --no-interaction  Do not ask any interactive question
  -e, --env=ENV         The Environment name. [default: "dev"]
      --no-debug        Switches off debug mode.
  -v|vv|vvv, --verbose  Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug

Help:
  The make:service command generates a new service class.

  php bin/console make:service Hello

```
Like this example, you can produce different solutions.

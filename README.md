# Docker image alpine nginx php


 Package Included
- nginx (1.8.0)
- php-fpm (7.1.17)
- composer

## Build

```
docker build -t becopay/alpine-nginx-php .
```

## RUN

```
docker run -d --name nginx-php -p 80:80 becopay/alpine-nginx-php
```

## Becopay Support:

* [GitHub Issues](https://github.com/becopay/alpine-nginx-php/issues)
  * Open an issue if you are having issues with this plugin
* [Support](https://becopay.com/en/support/#contact-us)
  * Becopay support

## Contribute

Would you like to help with this project?  Great!  You don't have to be a developer, either.  If you've found a bug or have an idea for an improvement, please open an [issue](https://github.com/becopay/alpine-nginx-php/issues) and tell us about it.

If you *are* a developer wanting contribute an enhancement, bug fix or other patch to this project, please fork this repository and submit a pull request detailing your changes. We review all PRs!

This open source project is released under the [Apache 2.0 license](https://opensource.org/licenses/Apache-2.0) which means if you would like to use this project's code in your own project you are free to do so.  Speaking of, if you have used our code in a cool new project we would like to hear about it!  [Please send us an email](mailto:io@becopay.com).

## License

Please refer to the [LICENSE](https://opensource.org/licenses/Apache-2.0) file that came with this project.

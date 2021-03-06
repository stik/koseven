## [Download](https://github.com/koseven/koseven/archive/master.zip)

### [Join the Telegram group] (https://telegram.me/koseven)

# Koseven PHP Framework

Koseven is a PHP framework based on [Kohana](http://kohanaframework.org/) 3.3.X . Fully compatible with Kohana and updated to work with PHP7

Koseven is an elegant, open source, and object oriented HMVC framework built using PHP7, by a team of volunteers. It aims to be swift, secure, and small.

Released under a [BSD license](LICENSE.md), Koseven can be used legally for any open source, commercial, or personal project.

## Why a Kohana alternative?

I use Kohana 3.3.x in many live projects and migration will be really complex into any new PHP framework. Keeping the project alive and updated is a priority. Kohana team (which I belong too) will not release any new version. [Kohana is DEAD] (http://discourse.kohanaframework.org/t/search-for-collaborators/56)

I will keep updated tihs repo with any other new issues or features on Kohana.

## Will work as dropin of Kohana?

If you were using 3.3.x version normally yes. Normally? theres 2 breaking changes that may affect you be aware. We have removed MySQL (you need to use MySQLi) and exception.php is now compatible with PHP7.

We have also added the pagination module.

## What changes have you made?

So far is exactly as last stable version of KO 3.3.6 released on Jul 25, 2016. But compatible with PHP 7 / PHP 7.1. I personally would like only to add fixes, bug fixes, speed improvements and the rest leave it for the modules.

## Are modules of Kohana compatible?

Yes they are, just be sure are compatible with KO 3.3.X. 

## Why all modules in 1 repo?

This is a personal choice for me to keep the project as simple and easier to manage, modules are not enabled by default, just do not enable those you will not use.

## I Need help!

Feel free to [open an issue on github](https://github.com/koseven/koseven/issues/new). Please be as specific as possible if you want to get help. You can also [Join the Telegram group] (https://telegram.me/koseven) 

## Documentation

We are working to improve currents Kohana's documentation but in the meantime fill free to use the one provided by KO.

Kohana's documentation can be found at <http://kohanaframework.org/documentation> which also contains an API browser.

The `userguide` module included in all Kohana releases also allows you to view the documentation locally. Once the `userguide` module is enabled in the bootstrap, it is accessible from your site via `/index.php/guide` (or just `/guide` if you are rewriting your URLs).

## Reporting bugs
If you've stumbled across a bug, please help us out by [reporting the bug](https://github.com/koseven/koseven/issues/new) you have found. Simply log in or register and submit a new issue, leaving as much information about the bug as possible, e.g.

* Steps to reproduce
* Expected result
* Actual result

This will help us to fix the bug as quickly as possible, and if you'd like to fix it yourself feel free to [fork us on GitHub](https://github.com/koseven) and submit a pull request!

## Contributing

Any help is more than welcome! please see [Contributing](CONTRIBUTING.md)

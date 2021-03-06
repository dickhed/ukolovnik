# Ukolovnik

[![Build Status](https://travis-ci.org/nijel/ukolovnik.svg?branch=master)](https://travis-ci.org/nijel/ukolovnik)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/nijel/ukolovnik/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/nijel/ukolovnik/?branch=master)
[![Translation status](https://hosted.weblate.org/widgets/ukolovnik/-/svg-badge.svg)](https://hosted.weblate.org/engage/ukolovnik/?utm_source=widget)

Simple task manager written in PHP and using MySQL as backend. 

It requires browser with decent CSS support (Internet Explorer 7 or
newer or almost any version of Firefox, Safari or Opera).


## Homepage

http://cihar.com/software/ukolovnik/


## License

Ukolovnik is provided under GNU GPL version 3 or later.

Some icons were taken from phpMyAdmin (GNU GPL) and GNOME (GNU LGPL).


## Installation

Edit config.php to fit your setup and create needed tables by provided
SQL script (use sql/ukolovnik.sql for current MySQL which supports
charsets or sql/ukolovnik-no-charsets.sql for older versions 3.x which
do not support it).

If you are running git version, you need to generate locales data if you
want to use localized versions. To do so, install gettext and run
./admin/locales-generate script.

Ukolovnik does not provide any authentication and user management. If
you don't want to make it publicly available, please configure
authentication in your web server.

## Bug reporting

Please report found bugs to issue tracker on [GitHub][1].


## Developing

Development goes on in [Git][2], you can use [web based browser][3] to
browse it.

You can also update translations [online using Weblate][4].

[1]: https://github.com/nijel/ukolovnik/issues
[2]: git://github.com/nijel/ukolovnik.git
[3]: https://github.com/nijel/ukolovnik
[4]: https://hosted.weblate.org/projects/ukolovnik/

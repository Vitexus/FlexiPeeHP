# FlexiPeeHP
PHP Based Library for easy interaction with Czech accounting system Flexibee.

To test basic functionality please try to run testing/demo.php

PHP Knihovna pro snadnou práci s českým ekonomickým systémem [FlexiBee](https://www.flexibee.eu/)

[![Source Code](http://img.shields.io/badge/source-Spoje-NET/FlexiPeeHP-blue.svg?style=flat-square)](https://github.com/Spoje-NET/FlexiPeeHP)
[![Latest Version](https://img.shields.io/github/release/Spoje-NET/FlexiPeeHP.svg?style=flat-square)](https://github.com/Spoje-NET/FlexiPeeHP/releases)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](https://github.com/Spoje-NET/FlexiPeeHP/blob/master/LICENSE)
[![Build Status](https://img.shields.io/travis/Spoje-NET/FlexiPeeHP/master.svg?style=flat-square)](https://travis-ci.org/Spoje-NET/FlexiPeeHP)
[![Total Downloads](https://img.shields.io/packagist/dt/vitexsoftware/ease-framework.svg?style=flat-square)](https://packagist.org/packages/spoje.net/flexipeehp)


#Poděkování
Vznik této knihovny by nebyl možný bez laskavé podpory společnosti [Spoje.Net](http://www.spoje.net), 
která hradila vývoj řešení pro propojení LMS / FlexiBee a importu skladu.

U společnosti Spoje.Net, je možné si objednat komerční podporu pro integraci
knihovny do vašich projektů. 

![Spoje.Net](https://github.com/Spoje-NET/FlexiPeeHP/raw/master/spoje-net_logo.gif "Spoje.Net")

Installation
------------

    composer require spoje.net/flexipeehp


Mandatory configuration Directives
----------------------------------


    /*
    * URL Flexibee API
    */
    define('FLEXIBEE_URL', 'https://flexibee-dev.spoje.net:5434');
    /*
    * Uživatel FlexiBee API
    */
    define('FLEXIBEE_LOGIN', 'test');
    /*
    * Heslo FlexiBee API
    */
    define('FLEXIBEE_PASSWORD', 'testing');
    /*
     * Společnost v FlexiBee
    */
    define('FLEXIBEE_COMPANY', 'test');


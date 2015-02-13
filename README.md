
This is the sample config of .ebextensions to setup an Elastic Beanstalk PHP 5.5 container using Nginx and PHP-FPM


Using the non-legacy containers allows you to use Nginx (or any other services that you would like to) without the need of building a customised AMI.

Tested on ami-f7ce97c7, PHP 5.5 default.


Many thanks to https://github.com/carboncoders/elasticbeanstalk-nginx-php for the base config of Nginx and PHP-FPM






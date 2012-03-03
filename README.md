[![Kunena](http://www.kunena.org/images/kunena.png)](http://www.kunena.org)



## ABOUT

*Kunena* is a native Joomla forum and communications component written in PHP. *Kunena* enables forums, bulletin board, support forums, discussions and comments for a Jooomla base website.


## REQUIREMENTS

*Kunena* 1.7.2 requirements:

    Joomla! 1.5: version 1.5.20 or greater (>= 1.5.25 recommended)
    Joomla! 1.7: version 1.7.0 or greater (>= 1.7.4 recommended)
    Joomla! 2.5: version 2.5.0 or greater (>= 2.5.0 recommended)
    PHP: version 5.2.3 or greater (>= 5.3.6 recommended)
    MySQL: version 4.1.19 or greater (>= 5.0 recommended)

Our installer will check for minimal version requirements and will abort the install if they are not met.

In addition we recommend the following PHP settings:

    max_execution_time     >= 30
    memory_limit           >= 16M  (>= 64M recommended) - depends on other Joomla extensions used
    safe_mode               = off
    upload_max_filesize    >= 2M
    GD, DOM, JSON support installed

*Kunena* requires the following Joomla settings:

    * Site template compatible with Mootools 1.2 or better
    * Upgraded to latest versions all extensions that claim to integrate with Kunena 1.6
    * No plugins or modules that were developed for previous versions of Kunena or Fireboard

Version-specific information
============================

Please go to http://docs.kunena.org/index.php/Category:Kunena_Read_Me and select the specific article corresponding to this release.


## EXAMPLES

If you are looking for examples on how *Kunena* works or can be installed, we recommend you checkout our team site at http://www.kunena.org

We have setup a Playground for users and developers to try out various features of Kunena: http://www.kunena.org/playground

Most of our modules and Kunena extensions are installed at: http://www.kunena.org/showcase


## INSTALLATION

*Kunena* is installed via the Joomla component/extension installer. You may download our builds/packages from joomlacode.org via: http://joomlacode.org/gf/project/kunena/frs/ or from our downloads manager at: http://www.kunena.org/download

The Joomla installers allows you to directly install *Kunena* via package URL or from a local download of yours.

As long as the minimum requirements are met, the Kunena install should take only a few moments. We have spent a great amount of time to automate the entire installation process.

Upgrades are performed just like new installs. There is no need to uninstall Kunena to perform an upgrade. We STRONGLY recommend that you perform a backup before and new software install or upgrade. The upgrade procedure is identical to a new install and is performed via the Joomla extension installer. *Kunena* will detect all prior version of Kunena and will perform the necessary upgrade tasks fully automatic. 


## COMMUNITY

*Kunena* is a community built and maintained project. There is no commercial entity behind *Kunena*. We provide all our work for free and donate generous amounts of our time into the project.

As such *Kunena* itself does not offer commercial or paid for support. We provide our community with a support forum and in general you will find what you need on there. You can find the community support forums here: http://www.kunena.org/forum

If you are interested in commercial grade support we encourage you to check the Joomla Resource Directory at: http://resources.joomla.org/

The *Kunena* projects thrives on contributions from the community. Our dedicated volunteers spend countless hours every week to help the community.


## CONTRIBUTE

1. [Create an account on kunena.org](http://www.kunena.org/component/community/register)
2. [Create a topic (unless there already is one)](http://www.kunena.org/forum/newtopic)
3. [Checkout our GIT repository on github](https://github.com/Kunena)
4. [Read our documentation](http://docs.kunena.org)
5. [Read our developer wiki](https://github.com/Kunena/Kunena-2.0/wiki)
6. Send us a pull request


## LICENSE

[GNU General Public License v2](http://opensource.org/licenses/gpl-2.0.php)
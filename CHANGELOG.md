# Changelog

Change history for mcollective-package.

## 4.4.0

* Add zypper provider for SLES (MCOP-224)
* Add a version option to the install action (PR#1, PR#14)
* Add a yum provider for RedHat variants (PR#3, PR#15)

## 4.3.1

Released 2014-06-18

* Test more carefully for the windows provider to avoid breaking
  chocolatey (MCOP-18)
* Updated packaging metadata to build for RHEL7 and Ubuntu Trusty (MCOP-69)
* Handle empty response sets more gracefully (MCOP-55)


## 4.3.0

Released 2014-03-10

* Fix uninstall action on Windows systems (MCOP-14)


## 4.2.2

Released 2014-01-28

* Allow uninstall action to work with Puppet 3.4 and newer (MCOP-2)


## 4.2.1

Released 2014-01-02

* Allow agent to work with Puppet 3.4 (MCO-144)



## 4.2.0

Released 2013-03-04

* Remove Package agent data plugin (19563)


## 4.1.0

Released 2013-02-21

* Allow application parameters to be passed as either `action package` or `package action` (19371)


## 4.0.0

Released 2013-02-14

* Rewrite and publish package agent (18772)

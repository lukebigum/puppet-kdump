## treydock-kdump changelog

Release notes for the treydock-kdump module.

------------------------------------------

#### 0.1.1 - 2019-04-02

* Fix Puppet support to add Puppet 6 back

#### 0.1.0 - 2019-03-19

* Update to work with puppet 4.10 and later
* Add strong types and remove calls to
  depricated validate functions.
* Updated tests and Gemfile to  work with
  latest beaker.
* Drop support for EL5
* Add kernel_arguments fact
* Issue a notification when a reboot is required to enable/disable kdump

#### 0.0.1 - 2015-07-31

* Initial release

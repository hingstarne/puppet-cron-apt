puppet-cron-apt
===============

This is a Puppet module to install and configure cron-apt.
it has an additional upgrade step.

Usage
_____

include cron-apt

or

class {
  cron-apt:
    upgrade => true;
}

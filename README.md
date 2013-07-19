puppet-cron-apt
===============

This is a Puppet module to install and configure cron-apt.
it has an additional upgrade step.

Usage
-----
<pre>

include cron-apt

</pre>

or

<pre>

class {
  cron-apt:
    upgrade => true;
}

</pre>

[![Build Status](https://travis-ci.org/hingstarne/puppet-cron-apt.png)](https://travis-ci.org/hingstarne/puppet-cron-apt)

sublimetext-syslog
==================

![Twilight Theme](http://i.imgur.com/jlszoHg.png)

Sublime Text Syslog Syntax Highlighting

Still pretty rough at this point, but usable.

Example code for adding this module through Boxen:

```puppet
repository { 'sublimetext-syslog':
  source => 'gregschoen/sublimetext-syslog',
  path   => "${home}/Library/Application Support/Sublime Text 2/Packages/Syslog",
  require => Package['SublimeText2'],
}
```

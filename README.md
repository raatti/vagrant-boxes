# vagrant-boxes

Build fast vagrant-base-boxes (CentOS) for further usage.
Default EN/US language and Finnish keyboard

(!) Enforcing SELinux by default (!)
- like it is supposed to be.

## Requirements

* [virtualbox](https://www.virtualbox.org/)
* [vagrant](https://www.vagrantup.com/)
* [veewee](https://github.com/jedi4ever/veewee)

## Build
```
$ veewee vbox build centos-5.11-x86_64
$ veewee vbox build centos-6.8-x86_64
$ veewee vbox build centos-7.2-x86_64
```

## Export
```
$ veewee vbox export centos-5.11-x86_64
$ veewee vbox export centos-6.8-x86_64
$ veewee vbox export centos-7.2-x86_64

```


## Credits

Based on [puppet-vagrant-boxes](https://github.com/tommy-muehle/puppet-vagrant-boxes)

# code challenger to deploying Nginx

This example has not been tested (sorry i write it at home on my netbook ). It should install nginx using this design pattern [ http://www.craigdunn.org/2012/05/239/ ] 

## Prerequesites
We need a working Puppet setup

## Dependencies
We will be using some 3rd party modules:

* [jfryman-nginx](https://forge.puppetlabs.com/jfryman/nginx)

```
$ sudo puppet module install jfryman-nginx --modulepath /etc/puppet/modules
```


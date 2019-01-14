# modular-repoquery

This is a workaround.

An easy way to do RPM repoquery accross all modules in a repository. Read my [Modularity content discovery blog post](https://blog.samalik.com/fedora/2019/01/09/thinking-about-modularity-content-discovery.html) to find out why we need it.

```
$ ./modular-repoquery --whatprovides /usr/bin/npm
Last metadata expiration check: 1:05:14 ago on Mon 14 Jan 2019 01:24:41 PM UTC.
npm-1:5.6.0-1.8.11.4.1.module_2030+42747d40.x86_64 (nodejs:8:20180816123422:6c81f848:x86_64)
npm-1:6.4.1-1.10.11.0.1.fc29.x86_64 
npm-1:6.4.1-1.10.11.0.1.module_2200+adbac02b.x86_64 (nodejs:10:20180920144631:6c81f848:x86_64)
npm-1:6.4.1-1.10.13.0.1.module_2362+1451e041.x86_64 (nodejs:10:20181101171344:6c81f848:x86_64)
npm-1:6.4.1-1.10.15.0.1.fc29.x86_64 
npm-1:6.4.1-1.11.1.0.1.module_2379+8d497405.x86_64 (nodejs:11:20181102165620:6c81f848:x86_64)
```

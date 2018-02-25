# Beanstalkd
Beanstalkd is a simple, fast work queue.
# Usage
```sh
$ docker run -d -p 11300:11300 dtannock/beanstalkd
```
To change the maximum job size:
```sh
$ docker run -d -p 11300:11300 dtannock/beanstalkd -z 1024
```
To enable the binary log:
```sh
$ docker volume create beanstalkd_binlog
$ docker run -d -p 11300:11300 -v beanstalkd_binlog:/var/lib/beanstalkd dtannock/beanstalkd -b /var/lib/beanstalkd
```

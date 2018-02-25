# Beanstalkd

Beanstalkd is a simple, fast work queue.

## Usage

```sh
$ docker run -d -p 11300:11300 dtannock/beanstalkd
$ docker run -d -p 11301:11300 dtannock/beanstalkd -z 1024
```


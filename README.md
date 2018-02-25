# Beanstalkd

[Beanstalkd](http://kr.github.io/beanstalkd/) is a simple, fast work queue. Its interface is generic, but was originally designed for reducing the latency of page views in high-volume web applications by running time-consuming tasks asynchronously.

## Usage

```sh
$ docker run -d -p 11300:11300 dtannock/beanstalkd
$ docker run -d -p 11301:11300 dtannock/beanstalkd -z 1024
```


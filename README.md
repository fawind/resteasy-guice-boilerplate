# RESTEasy-Guice-Boilerplate [![Build Status](https://travis-ci.com/fawind/resteasy-guice-boilerplate.svg?token=RTEhNHKreGSnaC3U1jh2&branch=master)](https://travis-ci.com/fawind/resteasy-guice-boilerplate)

Boilerplate project for setting up RESTEasy webservices.

# Provided Libraries

* [RESTeasy](http://resteasy.jboss.org/) as REST framework.
* [Guice](https://github.com/google/guice) for bindings.
* [Guava](https://github.com/google/guava) for utilities.
* [SLF4j](https://www.slf4j.org/) and [Logback](https://logback.qos.ch/) for logging.
* [AssertJ](http://joel-costigliola.github.io/assertj/), [Mockito](http://site.mockito.org/), and [Jukito](https://github.com/ArcBees/Jukito) for tests.

# Setup

* Setup gradle: `gradle wrapper --gradle-version 3.3`
* For development: Run the [`JettyRunner`](https://github.com/fawind/resteasy-guice-boilerplate/blob/master/src/main/java/JettyRunner.java)
* Sample routes: `/index.html` and `/api/ping`


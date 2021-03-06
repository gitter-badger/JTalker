<h1 align="center"
  <br>
  <a href="http://www.github.com/coswald/JTalker"><img src="https://github.com/coswald/JTalker/blob/master/docs/img/JTalker.png" alt="JTalker" width="200"></a>
  <br>
  JTalker
  <br>
  <img src="https://forthebadge.com/images/badges/made-with-java.svg" alt=""> 
  <img src="https://forthebadge.com/images/badges/built-with-love.svg" alt="">
  <img src="https://forthebadge.com/images/badges/no-ragrets.svg" alt="">
  <br>
</h1>

<h4 align="center">An implementation of a server/client application in Java.</h4>

<p align = "center">
  <a href="https://www.gnu.org/licenses/gpl-3.0"><img src="https://img.shields.io/badge/License-GPL%20v3-blue.svg" alt="GNU GPL v3.0"></a>
  <a href="https://github.com/coswald/JTalker/blob/master/CONTRIBUTING.md"><img src="https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg" alt="Contributor Covenant v1.4"></a>
  <!-- <a href="https://www.codacy.com?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=coswald/JTalker&amp;utm_campaign=Badge_Grade"><img src="https://api.codacy.com/project/badge/Grade/0ed8150dc0d44ac2a0aeb2e09010c3be" alt="Codacy"></a> -->
  <!-- TODO: Add Travis Badges -->
  <a href="https://coswald.github.io/JTalker"><img src="https://img.shields.io/readthedocs/pip.svg" alt="Docs"></a>
  <!-- TODO: Add Twitter Badge -->
  <!-- <a href="https://gitter.im/JTalkerJava/"><img src="https://badges.gitter.im/coswald/JTalker.png" alt="Gitter"></a> -->
  <a href="https://saythanks.io/to/coswald%40uni.edu"><img src="https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg" alt="Say Thanks!"></a>
</p>

<p align="center">
  <a href="#jtalker">Description</a> •
  <a href="#tests">Testing</a> •
  <a href="#deployment">Deployment</a> •
  <a href="#built-with">Built With</a> •
  <a href="#versioning">Versioning</a> •
  <a href="#authors">Authors</a> •
  <a href="#license">License</a> •
  <a href="#acknowledgments">Acknowledgments</a>
</p>

## JTalker
An implementation of a server/client application in Java. This started as an example application for a networking class. However, I wanted to expand on it and test a couple things out. The only real use for JTalker is as an example of a server/client text sender, and to be used concurrently with a packet sniffer such as <a href="http://wireshark.org">Wireshark</a>. 

## Getting Started
See `Installing` to install JTalker for use or testing purposes. See `Deployment` for notes on how to deploy the project on a live system.

### Prerequisites
You need the [Java&trade; Runtime Environment](https://www.oracle.com/technetwork/java/javase/downloads/jre9-downloads-3848532.html) version 9 to use JTalker. However, to build JTalker, you need the [Java&trade; Development Kit](http://www.oracle.com/technetwork/java/javase/downloads/index.html) version 9 in order to use the *javac* command.

### Installing
We will give you an entire rundown on how to install JTalker. *TODO:* Have a live system set up on my website. If you wish to build the system by hand, here are the steps you will take. The first step is cloning the repository:

```
git clone https://github.com/coswald/JTalker
```

Once you have done that, move into the JTalker directory and `make` the project.

```
cd JTalker
make all
```

The `all` is optional. *TODO:* Generate a test to test the system works.

## Tests
*TODO:* We are going to use [Travis CI](https://travis-ci.org/) for tests and testing hooks, look again in the future for more details.

### Example tests
*TODO:* Generate JTalker tests.

### And coding style tests
*TODO:* Generate tests that allow for testing of our coding style.

## Deployment
*TODO:* Add additional notes about how to deploy this on a live system

## Built With
* [javac](https://www.java.com/) - The java compiler

## Contributing
Please read [CONTRIBUTING.md](https://github.com/coswald/JTalker/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning
We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/coswald/JTalker/tags). 

## Authors
* **Coved William Oswald** - *Lead Programmer* - [coswald](https://github.com/coswald)

See also the list of [contributors](https://github.com/coswald/JTalker/contributors) who participated in this project.

## License
This project is licensed under the GNU GPL v3.0 License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
* Thank you to [Dheryta Jaisinghani](https://www.dheryta.co.in) for the inspiration to start this project, as well as her guidance during this process. 
* Thank you to [PurpleBooth](https://github.com/PurpleBooth), for letting us use their README style!

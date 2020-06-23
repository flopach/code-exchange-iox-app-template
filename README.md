# IOx App: < Name >

< App-description >

## Quickstart: Build & Install

< Choose 1.a or 1.b or both >

### 1.a Create the Docker Container

```
docker build <URL-to-your-repo> -t ioxapp
docker save ioxapp > ioxapp.tar
```
The [Docker Runtime](https://www.docker.com/products/docker-desktop) needs to be installed on your computer.

### 1.b Create the IOx Package File

```
git clone <URL-to-your-repo>
docker build -t ioxapp .
ioxclient docker package ioxapp .
```
The [Docker Runtime](https://www.docker.com/products/docker-desktop) and [ioxclient](https://developer.cisco.com/docs/iox/#!iox-resource-downloads/downloads) need to be installed on your computer. You can download the files via [Git](https://git-scm.com/downloads) or as ZIP (Clone or download > Download ZIP).

### 2. Installation, App-Settings & Outcome

1. Install the application on your IOx device.
2. < what settings in the app can be modified? >
3. < what is the expected behaviour of the IOx app? How do I access it?>

**Tested Hardware**

< on which IOx hardware did you test this IOx app? >

* < HW > / < Firmware >
* < HW > / < Firmware >
* ...

## Deep-Dive: Configure the IOx App

< More Information on how to configure the IOx App >

## Versioning

**1.0** - < description >

## Authors & Contributors

* **< name >** - *< title / work >* - [< github page >](https://github.com/user)

## License

< choose a license of your choice. Example: >

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## More Information about IOx

* Documentation: [Installation guides, app network settings & more](https://developer.cisco.com/docs/iox/)
* Learning Labs: [Step by step learning guides](https://developer.cisco.com/learning/labs/tags/IOx/page/1)
* Find more IOx Apps: [DevNet CodeExchange: IOx Apps](https://developer.cisco.com/codeexchange/platforms/iox)
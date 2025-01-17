
# Train Ticket：A Benchmark Microservice System

The project is a train ticket booking system based on microservice architecture which contains 41 microservices. The programming languages and frameworks it used are as below.
- Java - Spring Boot, Spring Cloud
- Node.js - Express
- Python - Django
- Go - Webgo
- DB - Mongo、MySQL

You can get more details at [Wiki Pages](https://github.com/FudanSELab/train-ticket/wiki).

## Quick Start
The easiest way to get start with the Train Ticket application is by using [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/).

> If you don't have Docker and Docker Compose installed, you can refer to [the Docker website](https://www.docker.com/) to install them.

### Presequisite
* Docker
* Docker Compose

### 1. Clone the Repository
```
git clone https://github.com/FudanSELab/train-ticket.git
cd train-ticket/
```

### 2. Start the Application
```
docker-compose -f deployment/quickstart-docker-compose-v0.0.2/quickstart-docker-compose.yml up
```
Once the application starts, you can visit the Train Ticket web page at [http://localhost:8080](http://localhost:8080).

## Screenshot
![screenshot](./image/main_interface.png)
In order to know how to use the application, you can refer to [the User Guide](https://github.com/FudanSELab/train-ticket/wiki/User-Guide).

## Communication

* [FAQ](https://github.com/FudanSELab/train-ticket/wiki/FAQ)
* [Submit an issue](https://github.com/FudanSELab/train-ticket/issues)
* [Open a pull request](https://github.com/FudanSELab/train-ticket/pulls)

## Information

* [Release Note](https://github.com/FudanSELab/train-ticket/wiki/Release-Note)

## Paper Reference


Xiang Zhou, Xin Peng, Tao Xie, Jun Sun, Chao Ji, Dewei Liu, Qilin Xiang, and Chuan He. <br/>
**Latent Error Prediction and Fault Localization for Microservice Applications by Learning from System Trace Logs.**<br/>
In Proceedings of the 27th ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering ([ESEC/FSE 2019](https://esec-fse19.ut.ee/)) , Tallinn, Estonia, August 2019. <br/>
Download: [[PDF](https://cspengxin.github.io/publications/fse19-zhou-microservice.pdf)] [[BibTeX](https://dblp.uni-trier.de/rec/bibtex/conf/sigsoft/Zhou0X0JLXH19)] 

<br/>

Xiang Zhou, Xin Peng, Tao Xie, Jun Sun, Chao Ji, Wenhai Li, and Dan Ding. <br/>
**Fault Analysis and Debugging of Microservice Systems: Industrial Survey, Benchmark System, and Empirical Study.** <br/>
[IEEE Transactions on Software Engineering](https://www.computer.org/web/tse) , To appear. <img src="image/cup.png" height="20px"/> <img src="image/tse-best-paper-award.png" height="28px"> <br/> 
Download: [[PDF](https://cspengxin.github.io/publications/tse19-msdebugging.pdf)] 

<br/>

Xiang Zhou, Xin Peng, Tao Xie, Jun Sun, Wenhai Li, Chao Ji, and Dan Ding. <br/>
**Delta Debugging Microservice Systems.** <br/>
In Proceedings of 33rd IEEE/ACM International Conference on Automated Software Engineering ([ASE 2018](http://ase2018.com/)) , Short Paper, Montpellier, France, September 2018. <br/>
Download: [[PDF](https://cspengxin.github.io/publications/ase18-debugmicroservice.pdf)] [[BibTeX](https://dblp.uni-trier.de/rec/bibtex/conf/kbse/ZhouPX0LJD18)] <br/>
An extended version to appear in IEEE Transactions on Services Computing. 

<br/>

Xiang Zhou, Xin Peng, Tao Xie, Jun Sun, Chenjie Xu, Chao Ji, and Wenyun Zhao. <br/>
**Poster: Benchmarking Microservice Systems for Software Engineering Research.** <br/>
In Proceedings of the 40th International Conference on Software Engineering ([ICSE 2018](https://www.icse2018.org/)) , Posters, Gothenburg, Sweden, May 2018. <br/>
Download: [[PDF](https://cspengxin.github.io/publications/icse18poster-microservices.pdf)] [[BibTeX](https://dblp.uni-trier.de/rec/bibtex/conf/icse/ZhouPX0XJZ18)] 


## Architecture Graph
![architecture](./image/2.png)

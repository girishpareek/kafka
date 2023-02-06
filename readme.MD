# kafka training-feb-2023


### System Requirement 
- System with 8 GB 
- Hypervisor Support to test with docker 
- abount 50 GB free space 
- Operating System Mac / Windows / Linux
- Open internet access 


### Step 1 
> Download and install jdk 11 for your respective OS(Mac/Win/Linux) - https://www.oracle.com/in/java/technologies/javase/jdk11-archive-downloads.html

### Step 2 
>  Download Kafka from - https://downloads.apache.org/kafka/3.2.3/kafka_2.12-3.2.3.tgz and keep in windows desktop with shortest path possible example - 
>  :\Users\030841744\Desktop\kafka (Do not keep long path) 
>  Extract with softwares like 7 zip / win zip etc  
>    

* Note Windows Users: install wsl2 first -  https://docs.microsoft.com/en-us/windows/wsl/install
* For this you must Turn the windows system features ON (A) Windows subsystem for linux (B) Virtual Machine Platform (C) Hybper V. Also set system path as C:\Windows\Sysnative
* 
### Step 3 
> Add Kafka to system path - kafka_2.13-3.1.0/bin 

### Additional Softwares 
> Docker - https://www.docker.com/products/docker-desktop/
> Eclipse JEE - https://www.eclipse.org/downloads/  --> go and download enterprise version of eclipse https://www.eclipse.org/downloads/packages/

### Additional Kafka information:
https://kafka.apache.org/uses
https://zookeeper.apache.org/  == To know what zooker does?

Commands: 
First you need to keep the command into Kafka Folder: 
**To start zeekeeper server:** .\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties ===> for Windows
For Linux ./bin/kafka-server-start.sh ./config/server.properties

.\bin\server.properties


    tar -xvf <fileName.tgz>

    2000's - Login, stock, customer details, shipping, order, tracking etc - Vertical Scaling

    Producer - Consumer

    Publisher - Subscriber

    Array, ArrayList, Set - Values are sent

    Map - Key Value are sent

    workings (windows users please refer inside windows folder)

    Staring Zookeeper

    ./bin/zookeeper-server-start.sh ./config/zookeeper.properties
    
    For Windows: .\bin\windows\zookeeper-server-start.sh .\config\zookeeper.properties

    Starting Kafka

    ./bin/kafka-server-start.sh ./config/server.properties
    
     For Windows: .\bin\windows\kafka-server-start.sh .\confi\server.properties

    list all the topics

    bin/kafka-topics.sh --bootstrap-server localhost:9092 --list
    For Windows: bin\windows\kafka-topics.sh --bootstrap-server localhost:9092 --list

    create topic

    bin/kafka-topics.sh --bootstrap-server localhost:9092 --create --topic first_topic

For windows: bin\windows\kafka-topics.sh --bootstrap-server localhost:9092 --create --<topic_name>


Publishier: C:\Users\030841744\Desktop\kafka\bin\windows>kafka-console-producer.bat --bootstrap-server localhost:9092 --topic first_topic
Type messages as: 
>Hi
>How
>are
>you?

Consumer: C:\Users\030841744\Desktop\kafka\bin\windows>kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic first_topic
Consumer will get only latest messages after it got started and sent by publisher after starting consumer. Once consumed then Consumer can't use it again. 





https://www.ibm.com/docs/en/cloud-paks/cp-biz-automation/19.0.x?topic=emitter-enabling-kafka-broker-trace


.\bin\windows\kafka-topics.bat --bootstrap-server --list



 
 



## Introduction 

- 






# ASSIGNMENT-5 Master salve configuration

## Jenkins Master is the primary Jenkins server and is responsible for the following tasks:
```
    It distributes the builds among the numerous slaves for execution.

    It organises the build projects.

    It keeps an eye on the slaves at all times.

    Master can also run build jobs directly if necessary.

    It keeps track of the build outcomes and shows them.

```

## Jenkins Slave runs on a remote machine. A slave is responsible for the following tasks:
```
    Slaves can be operated on a number of different operating systems.

    It responds to the Jenkins Master's demands.

    Apart from the fact that Jenkins executes the build task on the next available save, 

    we can always arrange the project to run on a certain sort of slave computer.

    It also completes construction operations that the Master has dispatched.
```

## Steps -

1. Install Java on master node

2. Install Jenkins on master node

3. Install java on slave node

4. Create a user and ssh keys on slave node

5. Copy keys on master node

6. Join slave node to master

7. Test the setup


## Join slave node to master

To join the Jenkins slave node to Jenkins Master, perform below steps -

```
Select Build Executor Status > New Node > Type - Permanent 

Select below values -

Name - jenkins-slave1

Description - jenkins-slave1

Number of executors - 1 

Remote root directory - /home/prayag

Labels - jenkins-slave1

Usage - Use this mode as much as possible

Launch method - Launch agents via SSH

Host - 192.168.0.103

Credentials - use ssh username / private key options

Host Key Verification Strategy - Know hosts key strategy

Save and check that new slave node is added and is in sync

When prompted give node name 

```


<img src=./snaps/1.png>

<img src=./snaps/2.png>

<img src=./snaps/3.png>

<img src=./snaps/4.png>

<img src=./snaps/5.png>

<img src=./snaps/6.png>

<img src=./snaps/7.png>

<img src=./snaps/8.png>

<img src=./snaps/9.png>

<img src=./snaps/10.png>





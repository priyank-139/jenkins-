# ASSIGNMENT-4 Authentication and Authorization 

## Prerequisites
```
 java 11 

 jenkins 
```


## steps for assignment 4
```

1- create 9 freestyle jobs

2- go to Dashboard | New Items | job name> select> freestyle jobs > ok

3- Build Enviroment > Build Steps > add build steps > execute shell

echo $JOB_NAME  
echo "$JOB_NAME"

4- apply | save

5- Build Now

6-console Output

```

<img src=./snaps/4.png>






### Create 3 views devoloper | devops | testing
select list view > select type list view > filter jobs to be added for particular views 

<img src=./snaps/1.png>

<img src=./snaps/2.png>

<img src=./snaps/3.png>


### Authorization
```
1-create 3 users  |  manage jenkins > manage users > create users

2- go to configure global security 

```





## google-login configuration

A Jenkins plugin which lets you login to Jenkins with your Google account. Also allows you to restrict access to accounts in a given Google Apps domain.

To use this plugin, you must obtain OAuth 2.0 credentials from the Google Developers Console. These don't need to belong to a special account, or even one associated with the domain you want to restrict logins to.

Instructions to create the Client ID and Secret:

'''
   1 Login to the Google Developers Console

   2 Create a new project

   3 Under APIs & Services -> Credentials, Create credentials, OAuth client ID

   4 The application type should be "Web Application"

   5 The authorized redirect URLs should contain ${JENKINS_ROOT_URL}/securityRealm/finishLogin

   6 Enter the created Client ID and secret in the Security Realm Configuration
'''



<img src=./snaps/5.png>

<img src=./snaps/6.png>


<img src=./snaps/7.png>

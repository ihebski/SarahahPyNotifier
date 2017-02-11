#About Saraha Notifier

This is a dirty script that helps you to get notifications alerts about the new messages recieved on Saraha.com website.

![home_page](http://i.imgur.com/2fSFAjA.png)

#The main idea of the script

When you check around the web site ,the notification bar not indicate the new msg (onely email notification),but ,the /Message page gives you some information about the sum of the recieved messages.The script fetch the number field and compare it to an old one ,then save the new updates.

#How it works ?!
if new updates appears in the web site ,the script push a notification on the Desktop. 

![notification](http://i.imgur.com/AR4tnI5.png)

else "no update" nothing happen :p !,The script parse the new msg ,every 1 min left 

![](http://i.imgur.com/4PLElEK.png)

#Run the script

You need to include your cookies to run the code .
exemple of cookies and sessions
`cmdCurl='curl --cookie "csrftoken=BLABLABLA; sessionid=BLABLABLA" http://www.pwnerrank.com/categories/ | grep "<small>" >>pwnerrank.com'
`

RUN : 
```
$ git clone https://github.com/ihebBenSalem/pwnerrank_Notifier.git
$ cd pwnerrank_Notifier
$ python notifier.py
```
#Recommendation
You can use `Worker` to run the script every 1 h and get the new updates . 
#Say thank you
Big thanks to Mr .Fahmi ben Khlifa CEO of Tunisian white hat security who have inspired me to write this code 

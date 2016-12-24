# Email-Net-Over-Time_4
Email Net Over Time - 4

**Authors**: Weichen Xu, Zhengxin Cai, Hanqiao Qiu
![Screenshot](https://github.com/WeichenXu/Email-Net-Over-Time-4/blob/master/screen_shot.png "Screenshot")
## Description
We try to visualize the social network created by an email data set over time. We focus especially on visualizing the change in the communications within the network over time or during a specified time span. Besides, we generate the distribution of hot keys and display the content of emails between users in a interactive way.
This project offers functions:
* User status overview: What are the current status of the user?
	* Did user send/receive any e-mails in the current period?
	* Did user status change compared with last period?

* Email networking graph:
	* Whether there is a link/What are the content (of emails) between different users?
	* What's the volumn of the link?
	* What's the sum of emails a single user processed in current time span?
	* How the networking evolve during the time in coordinance with variable time unit?

* Content of the emails:
	* What's the distribution of the hot keys in current period?

**Video**:https://drive.google.com/file/d/0B3G56SR7Nof8NS1SODREbFFjNE0/view

**Real-time work url**:https://caicai-poly.github.io/Email-Net-Over-Time-4/index.html

**Final Document**:https://docs.google.com/document/d/1ViPR-H7xkU5Vk-5talFFACYs2arVnq5oo-pD56Hm-14/edit?ts=585cb30d

###Running
If you want to run the repo locally,
	```sh
		$ git clone https://github.com/NYU-CS6313-Fall16/Email-Net-Over-Time-4
	```
Start a local server for http request, use Python for more convenience
For Python 2.*
	```sh
		$ python -m SimpleHTTPServer
	```
For Python 3.*
	```sh
		$ python -m http.server
	```

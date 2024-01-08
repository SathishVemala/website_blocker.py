# website_blocker.py
Website Blocker Using Python [Working Model]

- [ ] Without python if i want to block websites in windows/linux or mac how to do that. I will tell you that first.
- [ ] If you want to do that manually right. So in your windows. For example you take windows you have to go this particular directory c://windows/system32/drivers/etc where you will be seeing a folder called “hosts” you have to open that file. We need to keep in mind that we must have to open that file as an administrator means that run as like open with administrator otherwise you will get an error.
- [ ] If you want to block some website you have to do like this 127.0.0.1 website.com (website you want to block) this website will be blocked. If you want to unblock just remove that and save the file. This is how you have to do for blocking and unblocking the websites. 
- [ ] So now I am gonna do the same thing with python.
- [ ] If you want to block “facebook.com”. I am giving two kind of options like www.facebook.com , https://www.facebook.com. Because there is a different domain combinations. Even fb.com goes to facebook.com. So whatever the possibilities of domain names are there you have to give everything in the list. If i give in the box I am getting the label ‘blocked’.
- [ ] Let me show you the host file, so it is asking for the refresh. The reason is we have written something in the host file. So it is asking for refresh.
- [ ] You can see here it got added to my host file. Now it is ok. If you see here if i give www.facebook.com it says like it is almost blocked right. If i want to unblock this go back to the host file I will just remove this and then save the file and back here now if you refresh it. It is working. 
- [ ] Even if you want to add unblock option to your code you can add it. But I am just showing you here manually by removing it from the host file.

Concepts I have learnt:

python  file handling
Scheduling tasks for automation
Hosts file working(DNS AND IP)

How do we access the web?

When you type a url and search for it, before it gets converted to IP address it actually checks in the host file first.
It first checks in the host file that already something present over there. If the domain is already present then it will choose that IP address only. 
(If domain is already present in the host file it will choose that IP address).

What we will do?

We will map the domain for example Facebook.com to our own IP address that is local machine IP address. 
At that time what happens means the entered url will not send IP address to server and then request was not go. 
It will check from the host file only. From host file it will check and get the IP address(i.e,  your own machine local host). 
Server was not respond. Facebook won’t load. That website won’t load and you are already blocked it.

Note: Instead of DNS request going to the server it redirects to our local Host. 

In Local Host the domain of whatever website you want to block will map to an ip address which is our own local machine ip address. 
In this way server won’t respond.

Output:

Go to browser and search for Instagram.com the page won’t load. Search Facebook.com the page won’t load. 
Hence Our project is executed successfully.

To watch Demo: [click Here](https://drive.google.com/file/d/1S4fNNU1DojRN2rrnQXkhfWTATIwwBy2e/view?usp=sharing)


               

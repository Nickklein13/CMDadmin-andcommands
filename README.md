![image](https://github.com/Nickklein13/CMDadmin-andcommands/assets/150096883/9281ccd9-4910-4e6a-8d2c-1a85045609fe)


<h1>Setting CMD as admin by default, and examples of some commands in CMD.</h1>

In this project, we will open command prompt, and give it permissions to open as admin everytime the program is ever opened. Then it'll be re-opened  to confirm it worked. Once open, we'll run a few commands in cmd. 

The reason behind us wanting to run CMD in admin by default,  is to automatically bypass denying commands that may modify system settings, or affect other users on the same computer, and it'll help us to not have to right click it everytime it's opened to manually select admin, it'll just happen.
. <br />



<h2>Environments and Technologies Used</h2>

- Command Prompt
- Administrative Privleges
- Notepad


<h2>Operating Systems Used </h2>


- Windows 10 

<h2>Deployment and Configuration Steps</h2>


<p>
1.) 1.) First we'll want to navigate to the start menu, search "cmd" or "command prompt", and right click it. Then click "open file location".  

NOTE: Yes you'll see "Run as admin" here, for the purpose of this project we will be setting it so that it always opens this way, and so you can skip that step going forward.

</p>
<br />

![image](https://github.com/Nickklein13/CMDadmin-andcommands/assets/150096883/7a081b7b-1688-464e-a04e-25f9592c46aa)


<p>
2.) Once we're in file locations, right click again, and select properties. Then once that window is up, we'll want to click on the "Advanced" command.  It'll pop up a new window, and we'll want to select "Run as administrator". Hit "OK", "Apply", "OK".
</p>
<br />

![image](https://github.com/Nickklein13/CMDadmin-andcommands/assets/150096883/8dd8c2f8-a08b-4bce-a969-40923533eb4a)

![image](https://github.com/Nickklein13/CMDadmin-andcommands/assets/150096883/20f9a6d6-20df-4e26-85ff-06fa797605f0)




<p>
3.) Now we will go re-open command prompt similar to how we did in step 1,  left click it, and if done correctly it'll ask if you want to give it permissions with a pop-up window. Say yes, and now you're in CMD with admin privleges.

You can also check the actual title of the window where it'll state it's administrator.



<br />



<p>
4.) We will run a few commands in CMD, just to get an idea what cmd prompt is capabe of.  Now that it is in admin mode, you shouldn't receive any restrictions to anything commands you enter, and it'll automatically bypass denying commands that may modify system settings, or affect other users on the same computer.

For this project we won't be diving in that deep into commands.


First we will run the command ipconfig /dissplaydns | clip
- NOTE: The " | " key is found above the right side SHIFT key, this is not a normal key to press to those not familiar with it.

Running this command will allow you to display dns settings, and automatically have it copied over into a notepad or word document. 

</p>
<br />

![image](https://github.com/Nickklein13/CMDadmin-andcommands/assets/150096883/f11ceaab-c549-427f-9876-fc455f0ff6c4)


It will not show any line-item results in cmd, however if you open a notepad and go to paste the results:

![image](https://github.com/Nickklein13/CMDadmin-andcommands/assets/150096883/369cb8f4-7ed8-4975-a3fc-515b324f1465)



<p>
Curious how I got the cmd line with weather in the beginning? Next we will use CMD to tell us the weather!

 I've personally made the move from Houston --> Philladelphia within the past week. So, in the middle of this project I've become curious what the weather I left behind is like currently. Instead of clicking on my taskbar, I'd like to see what cmd says about the weather in houston

So next, to check that, we'll type in 

curl wttr.in/Houston    (or change Houston to where you want)
</p>
<br />

![image](https://github.com/Nickklein13/CMDadmin-andcommands/assets/150096883/cf485b7b-6871-464c-8110-088fe404dbef)

<p>
And as you can see, we now havven't even need to leave CMD to get a 3 day forecast, or current weather conditions of Harris County in Houston, Tx.
</p>
<br />



<p>
And finally, we're gonna use CMD to create a QR code for a website. 

The line command we'll use for this is;

curl qrenco.de/https://espn.com

Which creates a QR code, that I scanned with my phone and can verify is working (and you can too)</p>
<br />

![image](https://github.com/Nickklein13/CMDadmin-andcommands/assets/150096883/45a1d9e8-700a-4c1f-bf04-e2b155dca784)




<p>
Not able to communicate with it, however Google is working?
</p>
<br />


<p>
There are thousands of different commands you can do CMD prompt, these were just a few to demonstrate the basic background of this project. After reading this, you should now be able to open CMD in admin, set it to permanently open in admn, and hopefully learned a few new fun commands in command prompt you didn't know bwfore.

</p>
<br />


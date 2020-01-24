# E-chat&Chatib Auto-Pm 


 Simple automation(bot) without any need for node.js, python etc....
View below how to install and setup for e-chat and chatib.

# E-chat

Before installing the Auto-pm. [Download](https://chrome.google.com/webstore/detail/katalon-recorder-selenium/ljdobmomdgdljniojadhoplhkpialdid "Download") this Google chrome Extension:  Katalon Recorder 

How to install:

```
 1. Download the zip file below and than extract it   
 2. Edit the .html files. See down below how to.
 3.  Log out of e-chat if your already logged in. Open new window from google chrome
 4. Login into e-chat with registered account or guest account**¹
 5. Click on katalon recorder extension. Set speed to 2nd highest as seen in (img1) below
 6. Open testsuit than select the .html file you want to use**²
 7. Press play and now should work as seen in (img3)   
```
 [Download zip](https://srv-file5.gofile.io/download/lO2EQe/auto-pm-files.zip "Download")

**Important** **¹ Make sure username of the account you login with has ~ in front of it or with any other character that puts your username at very bottom of username list   

**Important1** **² Use 20userlist if the room your using auto-pm on has 22 or more users in it. Use 30userlist if room has 32 or more users in it. Use 40userlist if room has 42 or more users in it. Use 50userlist if room has 52 or more users in it. Use 60userlist if room has 62 or more users in it. Use 70userlist if room has 72 or more users in it.  Use 80userlist if room has 82 or more users in it. Use 102userlist if room has 104 or more users in it.

**Note**: Downward userlists pms users going down from top to bottom. Upward userlists pms users from bottom to top. As seen in (img0)

(img0)
<img src="https://i.ibb.co/FB0M2HS/Userdown-up.png" alt="img0" width="600" height="300">





 (img1)
<img src="https://i.ibb.co/vqvDN2t/setspeed1.png" alt="img1" width="400" height="400">




(img2)
<a href="https://imgflip.com/gif/3n0gwi"><img src="https://i.imgflip.com/3n0gwi.gif" title="img2"/></a>





## How to Edit .html

```
 1. Select which ever .html file from 20,30,40,50,60,70,80,102 userlist.html
 2. Open any text editor(Recommend atom text editor) go to the 17th line where it says: Delete this text and Than Enter room url e.g http://e-chat.co/room/1
 3. Replace that text with any room link. For example: http://e-chat.co/room/1
 4. copy the whole code from the file.
 5. Go to site named pintools. link down below.
 6. Paste the copied code into "ORIGINAL TEXT" box on the site
 7. In the "Search for" box on the site enter this: Delete this text Than Enter your message here
 8. In the "Replace with" box enter any message
 9. Click Replace button on site and than copy the code from "TEXT WITH REPLACED OCCURRENCES" box
 10. Go back to text editor Delete all of the orginal code and Paste the new copied code in text editor and save. Make sure its saved as .html          
```
[Pinetools](https://pinetools.com/find-and-replace)

##  Loop script

 Load one of .html script in Katalon recorder extension. Click on plus sign four times. Four rectangle box will appear at bottom. Fill them out as follow:
 rectangle box1
 ```
 Command: store
 Target: 1
 Value: ii
 ```
<img src="https://i.ibb.co/Y305bDy/Store.png" alt="img3" width="400" height="100">

rectangle box2
 ```
 Command: while
 Target: ii<5
 Value: 
 ```
 Note: Script will loop 5 times. You can change 5 to any number greater than 1.
 
 <img src="https://i.ibb.co/N66N2B0/while.png" alt="img4" width="400" height="100">
 
 rectangle box3
 ```
 Command: storeEval
 Target: ${ii}+1
 Value: ii
 ```
 <img src="https://i.ibb.co/3CHfD9N/Storeeval.png" alt="img5" width="400" height="100">
 
 rectangle box4
 ```
 Command: endWhile
 Target: 
 Value: 
 ```
 <img src="https://i.ibb.co/443dYcz/endwhile.png" alt="img6" width="400" height="100">
 
 
 Move store to the very top and while to second.
 
 
  <img src="https://i.ibb.co/yqstm74/whilelooptop.png" alt="img7" width="500" height="200">
  
  Endwhile should be at very bottom and storeEval above it
  
  <img src="https://i.ibb.co/HtRt8zb/whileloopbtttom.png" alt="img8" width="500" height="200">
  
## 
For best results use 2 browsers or [person/profile](https://support.google.com/chrome/answer/2364824?co=GENIE.Platform%3DDesktop&hl=en-GB) on chrome one running Downward other upward script. If you have 2 windows or tab open. Both logged in on e-chat with same user. Close one of the window and tab.    

**When its running dont touch the browser window its running in. Let it run in background**

##  
##  



## Chatib

This is more simpler than e-chat auto-pm. Since Chatib has no limt on how many people you can pm in a certain time period and javascript responds faster on this site. You can do any speed on here slow-medium-fast.

Before installing the Auto-pm. [Download](https://chrome.google.com/webstore/detail/uivision-rpa/gcbalfbdmfieckjlnblleoemohcganoc) this Google chrome Extension: UI.Vision RPA

This Extension runs faster for Maximum speed

How to install:

```
 1. Download file. Download link below
 2. Edit the .json See down below how to.
 3. Open new window on chrome Go to chatib.us and login with account or Chat Without Registration login
 4. Click play! you can also loop by clicking the down chevron button. Set number of max value to the amount you want to replay. Default is 3

```
Its set to pm 1500 users 
[Download zip](https://srv-file5.gofile.io/download/kEp8Gy/Chatbi-auto-pm.json.zip)


## Editing .Json

```
1. Open any text editor(Recommend atom text editor)
2. Copy all the code in file
3. Go to https://pinetools.com/find-and-replace
4. paste code in "ORIGINAL TEXT" box
5. In "Search for" box type: Enter your text here
6. In "Replace with" box Enter any text
7. Click replace and copy code from "TEXT WITH REPLACED OCCURRENCES" box
8. Open text editor Delete orginal code and paste new code

```




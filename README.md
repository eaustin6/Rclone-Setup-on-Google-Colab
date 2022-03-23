# Rclone on Google Colab (Advanced!) 🔥
<p><b>Setup and Start using Rclone on Google Colab and Create/Edit/View and delete your Rclone config file and keep them always with you using this! No matters which device you are on! Use Anywhere and Anytime and perform all Rclone task and immediately save it!</b></p>
<h2><b>🆕What's New!🆕</b></h2>
<p><b><i>v2.2.3<i><b></p>
<h4><b>1.Rclone will now auto-fetch the saved progress including Rclone config file (If Any) from your Google Drive (My Drive).🔥</b></h4>
<h4><b>2.Now you can use your own Rclone Config File! Just upload it to your My Drive and fetch it</b>🙃</h4>
<h4><b>3.File will be shifted to Google Drive at place of starting download to your Device!</b></h4>
<p><b><i>v2.2.1</i></b></p>
<h4><b>1.Create/Delete/Edit Rclone config file/remote!🤩</b></h4>
<h4><b>2.Download Rclone config file!😀</b></h4>
<h4><b>3.Support all Rclone Commands!😎</b></h4>
<h4><b>4.Store your Rclone progress on Cloud and access it from anywhere!😉</b></h4>
<h2><b>⛔ NOTICE</b></h2>
<h4><b>1.In Latest Rclone Version v1.58.0, they made some changes in Auto-Config. Don't worry I am aware of that and till that you can either follow the New Steps or if you are making config file for Google Drive then you can provide your CLIENT ID and CLIENT SECRET to Work around that situation! I will update you in my Update Channel ,once I find some alternative to help you out in that Step.</b></h4>
<h4><b>2.For auto-config always choose No(n) because we are going to run the Rclone not on our own local device! Otherwise login will not work.</b></h4>
<h2><b>📝 Introduction</b></h2>
<h4><b>This Project makes it easy and possible to Perform every Rclone Task on Google Colaborately and Store your progress on the cloud and continue it where you left it anytime and anywhere! This Project comes with In-Build support to perform basic task like Creating/Editing/Viewing and Deleteing and also Downloading your Rclone Config file which is needed by almost all Rclone User to perform task! To execute any rclone command you just need to type "!rclone" (After installing Required Setup Files) before any command like "!rclone config" where config is the Command name!</b></h4>
<!--- Step Area Begin --->
<h2><b>🔌Before you Start!</b></h2>
<h4><b>Please Connect your Google Account, So that Rclone can easily save its progress automatically.</b></h4>
<img src="Img/rq-1.png">
<h4><b>If you want to use your own Rclone config file or the progress saved in your Google Drive in My Drive! Then run the following Code as shown in the image</b></h4>
<img src="Img/rq-2.png">
<h2><b>⚙️ How to use?</b></h2>
<h4><b>1.First Open the Code on Google Colab: <a href="https://colab.research.google.com/github/TheCaduceus/Rclone-Setup-on-Google-Colab/blob/main/Rclone.ipynb" alt="Open Code">Open Code</a></b></h4>
<h4><b>2.Now,Before performing anything Run the Code as shown in the Image to download Setup and configure Rclone!</b></h4>
<img src="Img/1.png" alt="1">
<h4><b>3.To Create/Edit/Delete/View comfig file/remote just run the code as shown in the Image.</b></h4>
<img src="Img/2.png" alt="2">
<h4><b>4.After Running the Code! Checkout the available options (shown in image) and choose a type alphabet and hit Enter key to continue, but if input filed is not visible then just click on the blinking line.</b></h4>
<img src="Img/3.png" alt="3">
<h4><b>5.Type n and hit Enter to create a new Config file or Remote and give name, So that you can identify it in future</b></h4>
<img src="Img/4.png" alt="4">
<h4><b>6.Now after Entering the name! You have to choose the cloud for which you have to make config file or remote (by typing its list number), like if you need to make config file or remote of Google Drive then type number "17" and hit Enter</b></h4>
<img src="Img/5.png" alt="5">
<h4><b>7.If you don't know about Client ID and Client Secret then just hit Enter without entering anything! Otherwise this can be used to bypass login into your Google Account</b></h4>
<img src="Img/6.png" alt="6">
<h4><b>8.After that, It will ask you to grant which level of access to your Rclone config file, to choose it just type and hit enter the list number! I recommend to use number '1' which is for full access.</b></h4>
<img src="Img/7.png" alt="7">
<h4><b>9.If you want to use "Computers" folder than you can provide its root_folder_id otherwise just hit Enter to ignore</b></h4>
<img src="Img/8.png" alt="8">
<h4><b>10.Again! If you want to use Service Accounts then you can fill the shown field otherwise leave it and hit Enter!</b></h4>
<img src="Img/9.png" alt="9">
<h4><b>11.Also, for doing advanced configuration you can type y or just hit Enter to ignore it.</b></h4>
<img src="Img/10.png" alt="10">
<h4><b>12.This is a important step! For Auto-Config write 'n' and hit Enter because here we are using a Remote Machine which is not our Device! So always choose 'n' otherwise login will not work.
<img src="Img/11.png" alt="11">
<h4><b>13.After above step! Rclone will give you an URL, You have to copy that URL and paste and open it on new tab and log in with your Google Account. After login, you will get a code just copy and paste it here as shown in the Image</b></h4>
<img src="Img/12.png" alt="12">
<img src="Img/13.png" alt="13">
<h4><b>14.Now, it will ask you if you want to use Shared Drive or not ? y for Yes and n for No.</b></h4>
<h4><b>15.If you want to use Shared Drive then it will ask you to choose the list number of Shared Drive from the list shown (of available Shared Drive in your Account.)</b></h4>
<img src="Img/14.png" alt="14">
<h4><b>16.Finally! After above steps, it will show you the final code of rclone config file, you can copy paste it in any Text Editor and after that type 'y' and hit Enter to confirm and then type 'q' tp quite the configuration of file.</b></h4>
<img src="Img/15.png" alt="15">
<img src="Img/16.png" alt="16">
<h4><b>17.After Typing q and hitting Enter! The Download of rclone config file will automatically starts and save it in your Device.</b></h4>
<img src="Img/17.png" alt="17">
<h4><b>18.You can execute or run any Rclone command in this project! Just click on the Drop-down arrow of "Advanced Task" and that sit! Enjoy</b></h4>
<img src="Img/18.png" alt="18">
<!--- Step Area Ended --->
<h2><b>📑Creating Config File for More Clouds</b></h2>
<p><b>You can learn creating config file for all Cloud Services: <a href="https://rclone.org/docs/">Learn Here</a></b></p>
<h2><b>🎯Points to be Remembere</b></h2>
<h4><b>1.Always choose No (n) for Auto-Config because we are not going to use Rclone on our Local Device/Machine otherwise login will not work!</b></h4>
<h4><b>2.Don't forget to type '!' before executing any custom Rclone Command.</b></h4>
<h4><b>3.For Safety! Rclone will always save progress in your My Drive! Not in any of your Shared Drive.</b></h4>
<h2><b>Supported Command List</b></h2>
<h4><b><a href="https://github.com/TheCaduceus/Rclone-Setup-on-Google-Colab/blob/main/Cmds.md">Show List</a></b></h4>
<h2> 🔐 Safe or Not? ✅</h2>
<h4><b> 1.Don't Worry! No data will be shared with anyone, if you use the <a href="https://github.com/TheCaduceus/Rclone-Setup-on-Google-Colab">Original code</a>.🔒</b></h4>
<h4><b> 2.This code do not share even a single piece of data to any third party source and not create any log of that!🔑</b></h4>
<h4><b> 3.Do not trust any other copy of this Code.📚</b></h4>
<h2>⛑Contact Us!</h2>
<h4><b>Join our Update Channel at Telegram:<a href="https://telegram.me/TheCaduceusUPDATE"> Join Now!</a></b></h4>
<h4><b>Directly Contact the Developer using Telegram <a href="https://telegram.me/HelpAutomatted_Bot">@HelpAutomatted_Bot</a></b></h4>
<h2>❤️Credits & Thanks</h2>
<p><b><a href="https://github.com/TheCaduceus">Dr.Caduceus</a>: For making this Project and Guide.</b></p>
<p><b><a href="https://rclone.org/">Rclone</a>: The Backbone of this Powerful Project.</b></p>

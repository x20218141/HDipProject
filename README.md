# **Car Location App**

##### **Please note in order to use this App you need an Android phone (called "Phone 1"). "Phone 1" should have a sim card with credit to allow it to send a text and Location sensor turned on. You also need to have another Phone that is able to text "Phone 1". You will also need a gmail account to sign in to MIT App Inventor to allow you to edit the app.** <br /> <br />

## *To set up this project on your own Android Phone, along with testing it and altering it you need to follow the below instructions;* <br /><br />

## *Upload the Project to MIT App Inventor;*

1. Download the ProjectUploadForGit.aia file found in the "Code" section on github. You can download it as a zip by clicking on code, then "Download zip".

2. Extract the downloaded zip folder by right clicking on the file and selecting "Extract all". 

3. Then, go to the MIT App Inventors home page found [here](https://appinventor.mit.edu/) and click on "Create Apps!". Then sign up/in using a gmail account. 

4. Click the "Projects", then click "Import project (.aia) from my computer", Choose the ProjectUploadForGit.aia file you just downloaded and then click "OK". <br /><br />

## *Changing the Phone Numbers to your Desired Number/Numbers;*

1. When in the Project that you just uploaded in MIT App Inventor, click on "Blocks" on the top right of the screen. You will then see all the blocks that make the App function in the middle of the screen. 

2. There are currently 5 Sentences / Phrases set up here. To add a mobile number for each phrase click on the pink box that is next to "Set TextMe.PhoneNumber to" (in green) then enter your mobile number in the following format "+3538512345678". Do this for all the Sentences / Phrases you want to use. Only one mobile number can be used per phrase. Each text function is in a block of "if"/"else if" and "then".
At the Bottom of the page you will see a message that is sent back if the phrase is wrong. Enter your own mobile number for this phrase as it will be used to test and ensure the app is working if the wrong phrase is sent. <br />

#### *Please note that you can have a different mobile number for each phrase, this can be used to have muilple mobile numbers that can text the app and recieve the devices location.* <br /> <br />

## *Deleting / Changing the Sentences / Pharses*

1. To change the Sentences / Phrases that trigger the text, click the pink box beside "get messageText =" and enter the Sentence / Phrase there. Enter the exact same Sentence / Phrase in the pink box beside "set messageText to" (directly below). Do this for each Sentence / Phrase you want to change.

#### *Please note that this is case sensitive, if the text sent has a missing capital letter, comma or a space at the end it will not function correctly* <br />

2. To delete 1 or more of the text functions, Click on the blue cog wheel that is between "do" & "if" at the top of the blocks. Then for example, if removing the last text function drag the bottom "else if" out of the "if" block. The block related to that bottom will be left detached from the remaining blocks. Just drag the desired blocks over to the trash icon on the right to remove them. <br /> <br />

## *Testing the App*

1. Firstly you will need to download the non "Play Store" version of the MIT AI2 Companion app. You can do this by clicking [here](http://ai2.appinventor.mit.edu/companions/MITAI2Companion.apk) on the device you want to install the app for testing ("Phone 1"). When signed-in to the MIT App Inventor page you can also click on the Help dropdown, then Companion Information and Scan the QR code provided there and install it from there.

2. Once the MIT AI2 Comanion app is installed, open it. Then go to the Connect dropdown found once signed in to the MIT App Inventor page, *Please note you should have the project opened in there at this point.* Click on Connect, then AI Companion, then either type the code shown there in to the MIT AI2 Compnaion app or scan the QR with the same app that is shown.

3. Once step 2 is done the app should be displayed on your device, you can then test the fuctionality.

4. To test the device, text "Phone 1" the sentence / phrase you have defined and it should text back the current latitude, longitude and address of where the device is. <br /> <br />

## *Installing the App on the your Device*

1. Once you have the app tested and working as desired you can then install the app on "Phone 1". When in the project on MIT App Inventor, click on the Build dropdown and then Android App (.apk).

2. Once it has finished Compling and Building the app it will show you two options. You can scan a QR code, this will bring you to the download and you can then install it on the phone. <br /> 

*Please note you may need to allow installs from unknown sources on the Android device* or you can download the .apk file and then put it on the device and then install it.

## Using the App

1. "Phone 1's" lock settings need to be changed to "never lock". 

2. "Phone 1" needs be hidden somewhere in your car that is not easy to find.

3. "Phone 1" needs to be connected to power continuously to ensure the device is always on.

4. "Phone 1" also needs to have a sim card with credit so it can send a text when required.

5. "Phone 1" needs to have Location Sensor turned on.
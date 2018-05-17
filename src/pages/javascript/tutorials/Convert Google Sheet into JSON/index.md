---
How to convert a Google Sheet into JSON with 5 easy steps.
---

### Step 1

If you haven't done so already please [sign up at Google](https://accounts.google.com/signup/v2/webcreateaccount?hl=en-GB&flowName=GlifWebSignIn&flowEntry=SignUp) for a Gmail account. 

### Step 2 

Go to your Google Drive and open one of your google sheets or create a new one if you haven't done so already. Now that you have it open I want to mention the first row in your google sheet will act as keys for your properties. Below I have the examples of some keys highlighted. 

![Google Sheet 1](https://github.com/Dminch1/myblog/blob/My-Blog/assets/Googlesheet1.jpg?raw=true)

### Step 3

In the upper right-hand corner of your Google sheet should be a share button. Once you click it, a popup window should appear, and you will need to click on the Advanced button at the bottom right corner of the window. You will need to change the “who has access” to Public. Another thing to keep in mind while making your sheet public to the internet is the fact anyone can now see it so keep that in mind.

![Google Sheet 2](https://github.com/Dminch1/myblog/blob/My-Blog/assets/Googlesheet2.JPG?raw=true)

### Step 4

Next, you will want to get the shareable link by clicking the share button in the top left corner of your sheet. Inside your link you will have a Sheet ID. You will need to take note of the Sheet ID and Sheet name. Examples are highlighted below.

![Google Sheet 3](https://github.com/Dminch1/myblog/blob/My-Blog/assets/Googlesheet3.JPG?raw=true)

### Step 5

Take your ID and sheet name and paste into this script. ``` https://script.google.com/macros/s/AKfycbygukdW3tt8sCPcFDlkMnMuNu9bH5fpt7bKV50p2bM/exec?id={YOUR-SHEET-ID-GOES-HERE}&sheet={YOUR-SHEET-NAME-GOES-HERE} ```  If you've followed these steps correctly you should now have a fully functional  [JSON link like this.](https://script.googleusercontent.com/macros/echo?user_content_key=k8VNgosoZ34yex_9sHbIFLNsgglwyDa8k3XHpMJS2px_Z05t8XpPwkPSoffI_2kYz6RzPvYyZ4K5bNJEpLkjkVCIvHwf4ESvOJmA1Yb3SEsKFZqtv3DaNYcMrmhZHmUMWojr9NvTBuBLhyHCd5hHa1ZsYSbt7G4nMhEEDL32U4DxjO7V7yvmJPXJTBuCiTGh3rUPjpYM_V0PJJG7TIaKp9JZm8S1OE6prygjhE2hY9EaNnmFYDBMTAu84oeSx9sgtz1w1ikeeNwH5kyRS5p7ZMKiW3k6MDkf31SIMZH6H4k&lib=MbpKbbfePtAVndrs259dhPT7ROjQYJ8yx) 


Check out [General Bitcorn Tech Blog](https://generalbitcorn.netlify.com/) for more guides in the future.
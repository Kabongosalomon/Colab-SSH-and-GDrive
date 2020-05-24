# Colab-SSH-and-GDrive
A convenient way to utilize Colab GPUs and save the progress from your local Terminal. SSH into Colab notebook with access to your google drive. 


## Steps
1. Create your free account at [ngrok](https://ngrok.com), this will be usefull in next steps.
2. Get the public key of your local machine. <br>
`$ ssh-keygen`<br>
`$ cat .ssh/id_rsa.pub`

3. Go to this notebook and follow instruictions.

<!-- 4. Execute the colab notebook. Mount your Google Drive. When prompted, enter the authtoken obtained in Step1. Lastly, it will ask the public key of your local machine obtained in Step2.
5. Now you should get output something like `ssh root@0.tcp.ngrok.io -p 12**6`. The port will be different for your case. Go to your local machine and run this ssh command. **Done!** -->

<br>By default, you will be inside a temporary space and its content will be deleted once your Colab session ends. If you want to save your work, you should explicitly save your changes in the mounted google drive.
<br>Your Google Drive files will be present in `/content/gdrive/My Drive/` <br>

![Screenshot](https://github.com/vdivakar/Colab-SSH-and-GDrive/blob/master/Images/Terminal_img.png)
<br>

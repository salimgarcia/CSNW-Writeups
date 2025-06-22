●	Create a new VM using the Windows Server template
●	Add the server you your domain
●	Open Server Manager and click Manage and select Add Roles and Features
●	In Server Roles, select the Web Server (IIS) role
●	Click next until you have the option to install, then click Install
●	Open Internet Explorer and type localhost into the address bar. If IIS is working properly you should see a webpage
●	Go back to Server Manager, click Tools, and open IIS Manager
●	Navigate to Default Website and select Default Document
●	Delete everything except index.html, then close IIS Manager
●	Open File Explorer and navigate to C:\inetpub\wwwroot and delete iisstart.htm and iisstart.png
●	Create a text document in wwwroot and create the hello world page with html
●	Save the text doc as index.html
●	Open internet explorer and type localhost in the address bar again and you should see your hello world html page displayed

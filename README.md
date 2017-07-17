# Oracle Service Cloud - Chrome App

<p align="center"><img src ="https://github.com/eferreira07/OSvC-Chrome-App/blob/master/img/osvc_chrome.png"/></p>

This repository / tutorial walks you through creating your first Oracle Service Cloud Chrome App.

**Why Chrome App?**

Chrome App provides an alternative to organize and access your apps and web page. With that said, Chrome App might be an alternative provide access to your Oracle Service Cloud Browser Interface.

# How it works?
Go ahead and open your Chrome. Find and click in "Show Apps" icon as presented below.

<p align="center"><img src ="https://github.com/eferreira07/OSvC-Chrome-App/blob/master/img/step-1.png"/></p>

Your apps is showing up as the follow image. In this example, I already have added my OSvC extension and you can see Oracle Service Cloud as an app.

<p align="center"><img src ="https://github.com/eferreira07/OSvC-Chrome-App/blob/master/img/step-2.png"/></p>

Alternatively, you can create a shortcut using your right-click on OSvC icon, then click in "Create Shortcuts...". The following options will be available to proceed with Shortcut creation.

<p align="center"><img src ="https://github.com/eferreira07/OSvC-Chrome-App/blob/master/img/step-3.png"/></p>

# Creating your first Oracle Service Cloud - Chrome App

[Download](https://github.com/eferreira07/OSvC-Chrome-App/raw/master/osvc_chrome_app.zip) the sample code from here and edit the   manifest.json as below:

```json
{
	"name": "OSvC App",
	"version": "0.1",
	"manifest_version": 2,
	"description": "OSvC App",
	"app": {
        	"urls": ["INSERT YOUR OSVC BUI URL > https://[sitename].custhelp.com/AgentWeb/"],
        	"launch": {
            		"web_url": "INSERT YOUR OSVC BUI URL > https://[sitename].custhelp.com/AgentWeb/"
        	}
    	},
	"icons": {
		"128": "icon.png"
	}
}

```

** Packaging your extension **
For more detailed information I'd recommend to access this [article](https://developer.chrome.com/extensions/packaging) and follow the steps provided.

** For more insights **
[Chrome Extension Web Page](https://developer.chrome.com/extensions/samples)

# Content Workflow

## Creating your new app

1. Install the app 'minimum-boilerplate-theme' by running `vtex install vtex.minimumtheme@0.x`
-  Update content to allow changes to be made in the *Site Editor*
     - Update banner text
     - Create an image block with a dummy image in *home.jsonc*
     	```
     	"image#placeholder": {
			"props": {
				"src": "https://dummyimage.com/720X400/000111/fff"
			}
	}
	```
	
	
     - Update the app name and version in your *manifest.json* file
           ```
	   {
               "vendor": "appliancetheme",
               "name": "trainingweek-fabiana",
               ...
           } 
	   ```

3. Save your content in the current repository

-----

## Publishing and installing your app
1. Run the command `vtex publish`
- Create a new **production** workspace by running `vtex use {workspace} --production`
- Install your new app by running `vtex install vtex.{new-app}@n.x`

-----

## Update blocks in the Site Editor tool

1. Navigate to Store *Setup > CMS > Site Editor* in your **production** workspace

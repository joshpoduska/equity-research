
## Tips and tricks for equity researchers in Domino

![image](raw/latest/equity.jpg?inline=true)

#### Code of interest is in the Deliver and Devlop directories.

#### Example Tearsheet:

![image](raw/latest/figures/tearsheet.png)

Demo topics in order:
    
    - Search
    - Files
    - git integration
    - Settings
    - Workspaces
    - Runs
    - Schedulers
    - Apps
    - Lauchers
    - API


Search and tagging
	
	- Asset management specific tags but also using comments
	- find pyfolio and show the files
	    - want more than one project to show up, ideally
	    
	- Add some run tags so we can find and look at old runs; speak to reproducibility

Files - 

	- File type agnostic
		- Need to have files in the home folder
		- Add R-files to the source
			- Doesn't matter what the script is
	- Render ipython notebooks inline like github
	    - Move an ipython notebook in the root folder
	- revisioning them through time
		- roleback and reproduce work

	
git integration
    
    - Mount a git repo - 
    	- use sci-kit learn or something random


Import a data project - 

	- this all happens on the `Files >> Other Projects` tab


WE get into model manager, and we don't have a way to show that it's real

	- light weight website
		- powered by domino end-point
		- 

Launchers? 

	- Simple.  What's there already works. 

API endpoints 
   


List of things to do: 

	1) Move some files out to the root folder
		- File page narrative is about file type agnostic
		- Show inline rendering of jupyter notbooks
			- jupyter notebook
			- python script
			- R file
			- CSV
			- Image file
	2) DONE Add a git repo
		- doesn't need to be real
			- something data scienc-y
	3) DONE Import a data project;
		- doesn't need to be real
			- adds depth to the details page
	4) NOT NEEDED Make an app in the same project; Preferably that uses the API end-point.
	5) CAN BE DONE - turned it off: Schedule the tearsheet python notebook
	6) Add a readme 
	    - try to define some of the more finance language
	        - Add some definitions for the non-finance folks giving this demo
	        - talk to DG about what he needs to role out...
	7) NOT NEEDED API question; not sure what the right API is for asset management
	8) Create an HTML email with the tearsheet embedded...

	Last) Add some better titles to the chart outputs

Git integration notes:

Any time you run a session, we are mounting the repo using a git-clone, and it creates a subdirectory
	- when you don't have a git-repo specified, the root directory is mnt
	- when you import another project
		- your root directory becomes [USER NAME]-[Current Project Name]
	- when you integrate a repo
		- the repo is mounted to a folder called "repo"
		- the "repo" folder is a git repository
			- you need to go to the terminal and git push in order to commit back to your repo
			- you would need to open a terminal, before you shutdown workspace
		- 




# nmc-api-postman
Postman Collection for the Nasuni NMC API

## Intro

This Postman collection can be used to get going quickly with the Nasuni NMC API. using it will allow you to get data from the NMC for manual use cases or to aid in script development.

## Usage

To use this postman collection you can either download or clone the repository to your local computer and import the folder or files or you can import directly from the GitHub Repo.

### Import Folder / Files

If you choose to import from folder or files you will need to first download a zip of the repo, or clone it to your local machine. Next, in Postman, click the "Import" button at the top of the screen. Select "File" or "Folder" at the top, and then browse to where you saved the repo files. Select them, and click Import. The collection should now appear on the left side of your screen under Collections.

### Import from Code Repository

In Postman, click "Import" at the top left. Then click "Code repository". Next you will need to connect Postman to your GitHub account. Once you have connected to your account, you will need to select which repository the collection is in. Note: If you have many repos it may not be listed, you can manually enter the name though.

Once you have the repo selected or manually entered, you will need to select the branch you want it to work from then click Continue. You will then be asked if you want to import the Collection and the Environment. 

If you want to fork this repo, and then backup your local environment to your fork, check out [this link.](https://blog.postman.com/backup-and-sync-your-postman-collections-on-github/)

## Getting Started with the Collection

Once you have the collection imported you should select the imported environment and edit some variables. Specifically there are 4 variables you need to edit:

* nmcserver
* nmcport
* nmcusername
* nmcpassword

Once you have those inplace you can run the "Login" request under the "Auth" folder, this will log you in to your NMC and store the auth token. You can then run other requests as needed. A great request to try first, to make sure you are logged in and everything is working is the "Get-Filers" request under the "Filers" folder. This should list all filers under NMC control.

## Contributing

If you find something missing or incorrect we welcome pull requests. If you aren't sure what the fix is then please submit an issue and let us know what problem you are experiencing so we can figure out the fix together.
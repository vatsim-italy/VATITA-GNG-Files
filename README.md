# VATITA-GNG-Files

You can connect one public github repository with the tree. With this you can include files into your packages without uploading them here.
You have to enter the following url at the NAV Settings page into the "Github_url" setting.
https://github.com/{YOUR GITHUB ACCOUNT}/{YOUR REPOSITORY}/zipball/{YOUR BRANCH}

https://github.com/Vatsim-ANA/ANA-Sectorfile/zipball/master
is the needed link for this example
https://github.com/Vatsim-ANA/ANA-Sectorfile

The files are not automatically synchronized when you upload them to Github. You have to use the "Update Github" button here in the GNG to get the latest repository.

Taken into account are following folders in the repository: ASR, ATIS, Plugins, Settings, Sounds and Other. These folders must be in the main repository folder like in the example above.
If they are not in the main repository folder, you can link to a subfolder of your repository where these folders exist.
You can use the "Github_path" in this case. If your Sound/Plugins/... folders are for example here in the subfolders NAV and then Files: NAV/Files/Sounds and NAV/Files/Plugins you have to enter "NAV/Files/" into the setting.

After changing the setting "Github_url" or "Github_path" you have to do a download to get the changes into effect.

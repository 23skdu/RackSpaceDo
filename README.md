# RackSpaceDo -- automated cloud provisioning for Rackspace API in Perl
Requires:  
Swiftly client via https://support.rackspace.com/how-to/install-the-swiftly-client-for-cloud-files/  
LWP::UserAgent  
JSON 

Can be used on the command line, in a shell for/loop, to both upload images,
and create virtual machines in the Rackspace cloud (currently, in IAD and DFW)
Can use multiple account/customer API keys and numbers, if you have a need
like i did, of managing images and machines in multiple accounts,sharing machine
images across accounts, etc.
Uses swiftly for file transfer. 

Implements the following functions via Rackspace API:  
AcceptImage ShowShare ShowBackup CancelBackup AddPublicIP BuildHost CheckImageTasks CreateGoldenImage  
DeleteImage DestroyHost DownloadFile ExportImage GetToken ImportImage  
SetBackup ListFlavors ListImages ShareImage ListPublicIP ListServers RemovePublicIP UploadFile      

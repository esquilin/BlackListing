# BlackListing
List of Domains and URL's to Block in your DNS or Pi-hole DNS Server.

## How To...

### How to block porn sites on Pi-hole using this BlackListing?
Login to your Pi-hole system and navigate to the settings screen by clicking on the settings button on the left menu panel.
Inside the settins screen click on the 'Blocklist' tab.
At the end of the screen you should see a text box the may say "Enter one URL per line to add new blocklists."

Copy the fallowing Lines:

```
https://raw.githubusercontent.com/esquilin/BlackListing/master/PornList/PornDomainsList-Part-01.txt
https://raw.githubusercontent.com/esquilin/BlackListing/master/PornList/PornDomainsList-Part-02.txt
https://raw.githubusercontent.com/esquilin/BlackListing/master/PornList/PornDomainsList-Part-03.txt
```

and paste it on the text box. 

#### Note: make sure there is one url per line when you paste the URL's in the text box.

Click on the 'Save and Update' button and wait for the system to process the files; this may take a few minutes depending on your Pi-Hole setup and Internet Connection. Your are all set!! 


### I accidently erase the original Url's list on my Pi-hole, how can I get it back??
When Those are not part of this project here is the easy way:

Copy the fallowing lines to the text box at the 'Blocklist' tab on Settings page: 

```
https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts	
https://mirror1.malwaredomains.com/files/justdomains	
http://sysctl.org/cameleon/hosts	
https://s3.amazonaws.com/lists.disconnect.me/simple_tracking.txt	
https://s3.amazonaws.com/lists.disconnect.me/simple_ad.txt	
https://hosts-file.net/ad_servers.txt
```

after been pasted, click the 'Save and Update' button and you will be all set.


### Are there is going to be other list here??
Yes, I will be working on more list but with the ones already posted here you will have a good start.


Good luck with your project!!

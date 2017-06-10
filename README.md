# Personal Site

This Repo is my personal website (http://dionajie.com) that can re-use by anyone. You can generate Linkedin Resume and Article from your Medium Publication automatically

# Features
  - Show your Linkedin Resume 
  - Show some post from your Medium Publication
 
# How to Start
### Add Linkedin Resume 
  - Link Instruction to download your Linkedin Archive and Export it to Json ([LinkedinToJson])
  - Save and Upload to your parent directory
  - Place your URL to Javascript at index.php 
```sh
var resume ='yourdomain.com/resume.json';
```
> Note : You need to actually run a webserver to get request to URI resume.json

### Add Medium Publication
  - Read more about Medium RSS Feed ([RssFeed])
  - Place your URL to Javascript at index.php 
```sh
var rss_medium = 'yourpublication.com/feed';
```

> Note : Personal Medium page (not a Medium Publication) will add not just your post (ex : response)

[LinkedinToJson]: <https://jmperezperez.com/linkedin-to-json-resume/>
[RssFeed]: <https://help.medium.com/hc/en-us/articles/214874118-RSS-feeds>


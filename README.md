### Last.fm Badges

This is a work in progress, soon to be a standalone version of the 'now-playing' endpoint on my website.   
I made this to embed on my GitHub profile, but the endpoint is open for any user.  
Support for themes, language filters, more/less information is planned.
  
### Now Playing
  
Displays the last song a user played on Last.FM  
No authentication required, simply update the 'user' parameter with your own username.  
If you set 'render' to '0' the response will be the JSON object used to generate the image.  

```
https://api.ksir.pw/v1/lastfm/now-playing?user=KainSir&render=1
```

Preview:  
![1](https://api.ksir.pw/v1/lastfm/now-playing?user=KainSir&render=1)  


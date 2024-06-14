# protonvpnbreakfix
These are files that as of 06/14/2024 , were loaded into protonVPN and broke my site on my computer completely.    
this is my site www.techsport.app , and after a long time of yelling at my hosting provider for no reason for months  , after them coaching me to test if it was still on ,
-  it was  
and this has been the cause of a redirect issue, causing my site online , to break on my local computer when / after developing with me for months, But I finally found it !  

- This is a tricky bug , as it occurs sometimes and does not occur other  times. 

When having proton vpn installed on my local , it works fine except for a little bit of caching issues, which cause a 404 page for certain sites. 
- Sometimes , when I have caching issues , it is on the browser side , and I have to go and delete files locally to get them 
to cache properly. I checked all of that , and even tried multiple browsers , so this time I thought then ,
the issue was  in my network layer somewhere , possibly DNS caching. 


------ 

=================================================================================================================================================
When Proton VPN is inatalled on widows , I would have these files occassionally generate from this path 
=
C:\Users\Vampeyer\AppData\Local\ProtonVPN
=
the folder - ProtonVPN_Url_cmnccr2xp2ofmvhglly0haihuyzzqh0i - with a user.config file inside. 
=
Startup.profile
=
--- After deleting these files , I was able to view my site via proton vpn successfully , EVEN on multiple browsers, 
it was at the OS cache / network level , so a bit tricky to spot and find.  
=
=
As well as these  ,
c:\users\vampeyer\appdata\local\protonvpn\logs   
=
app-logs.txt
=
app-logs.1.txt
===========================================================================================================================================


Recmmended fix 

= Delete files on startup. 





========================================================================================================



==========================================================
Note to self - come back in a week and write and push the code to fix it  
==========================================================


Note to the reader , if you found this valueable , let me know , either in thread or   via financial complements 
for an hour of professional time ($80.00 , here  - https://buy.stripe.com/9AQ9AH5KL9l24Xm006 )
here  - 

Thank you  








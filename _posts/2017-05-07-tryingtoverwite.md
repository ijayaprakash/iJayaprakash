---
layout: post
title: trying to overwrite library/mobilesubstrate/dynamiclibraries
tags: iOS
image_large: /images/dynamiclib.png 
image_small: /images/dynamiclib.png 
published: true
---

## trying to overwrite /library/mobilesubstrate/dynamiclibraries - IOS 10 Jailbreak

![]({{site.baseurl}}/images/dynamiclib.png)




### Noobs who have reseted/erased the phone after jailbreak !!!!:) :)



<!--more-->


### Step 1 using Terminal


  Type: su and password (if you closed Terminal before)
   
     Type : cd /Library/MobileSubstrate/DynamicLibraries 
    
     Type : ls -1 (fyi, you should see 2 files now: one of them should be 'DynamicLibraries')
    
     Type : rm DynamicLibraries
    

### Step 2 using ifile


	 Get into File Manager
  
     /Library/MobileSubstrate/DynamicLibraries
    
     Delete the Dynamiclibrary.lib file**
    


### step 3 :

	Create a new folder after deleting the dynamiclib.lib file
   
     new folder name !!!!DynamicLibraries

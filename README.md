### _XOOPS Documentation Series_
![logoXoops.jpg](assets/logoXoops.jpg)

# Module xLanguage
#### for XOOPS 2.5.7
      
![logoModule.png](assets/logoModule.png)
            
## User Manual

© 2015 XOOPS Project (www.xoops.org)    

## Module Purpose 

This module, **xLanguage** (eXtensible Multi-language content and character encoding Management plugin) handles displaying contents of different languages, like English, French and Chinese. Character encoding management also handles contents of different encoding sets for one language, like GB2312 (Chinese Simplified) and BIG5 (Chinese Traditional) for Chinese.  

### What xLanguage CAN do
1 displaying content of specified language based on user's dynamic choice 
2 converting content from one character encoding set to another

### What xLanguage can NOT do
1 xLanguage does NOT have the ability of translating content from one language to another one. You have to input contents of various languages by yourself 
2 xLanguage does NOT work without adding one line to XOOPS/include/common.php (see guide below) 
3 xLanguage does NOT have the ability of converting content from one character encoding to another if none of "iconv", "mb_string" or "xconv" is available. 

### Features
1 auto-detection of visitor's language on his first visitor 
2 memorizing users' language preferences
3 switching contents of different languages/encoding sets on-fly 
4 supporting M-S-M mode for character encoding handler

![image001.jpg](assets/image001.jpg)
*Figure 1: Main view of the xLanguage Module (Admin side)*

# Table of Content

* [Install/Uninstall](book/1install.md)
* [Administration Menu](book/2administration.md)
* [Preferences](book/3preferences.md)
* [Operating Instructions](book/4operations.md)
* [The User Side](book/5userside.md)
* [Blocks](book/6blocks.md)
* [Templates](book/7templates.md)
* [Other](book/8other.md) //delete, if not used
* [Module Credits](book/9credits.md)
* 

##License:

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />Unless specified, this content is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

All derivative works are to be attributed to XOOPS Project (www.xoops.org)

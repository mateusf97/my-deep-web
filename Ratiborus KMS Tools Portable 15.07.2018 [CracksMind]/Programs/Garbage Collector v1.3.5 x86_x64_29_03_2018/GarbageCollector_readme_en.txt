                           Garbage Collector by Ratiborus, 
                                     MSFree Inc. 

                                     Descripton: 
                           ————————————————————————————————— 
 	The program is designed to simplify and facilitate the search for different activation
keys in text form, located on different resources in the network. The principle of operation
of its simple: the program searches for activation keys for Windows, Office (and others!)
given it masks\searches\regular expressions, such popular services for sharing information, as
pastebin, textuploader, and other resources on the network.  In addition, you can add your own
links to pages of forums\sites, you prefer to look for the activation key for Windwos, Office,
etc. 
	In the case of the default settings, the program searches through special keys
search query to Google, on the service pastebin.com. The interface provides ten
custom buttons, which you can hang your favorite pages. Everything is customizable
through the program interface. 
	In addition, you can create up to 16 search queries that will be run when
pressing the Auto button, in the program built one, for example, nothing complicated. For
thin setup autosearch, you must click on the settings icon, add your own links... Then select
the search type (normal or anonymizer), and click "Apply and  Close". The anonymizer is needed
in some cases, to prevent checks from the robots.  
	From the resulting page, with search results, select links, and program searches keys
to these links. It's as simple as that simply have nowhere... 
	The size of the window can be changed. On 1st - 10th buttons you can assign your
favorite forum pages or sites. In the program, by clicking on the links on the page, the whole
the text is copied to the clipboard, then click "Select keys" can..... to choose from it keys.
	If you don't need specific search terms, or in your opinion, they processed quickly
enough, in settings sufficient to remove the check mark. And this search request will not be
processed. 
	Added the ability to interrupt the operation of garbage collection and selection keys.
Have the opportunity to ask his mask to search for text on the page. Now it's the M$ key
format, but you can customize the search for keys in other format. For example, even a format: 
XXX-XXXXXXXXX-XXXX-XXXXXXXXXXXX.XXXXXXX 
That is, for search personal data in certain format just change the parameter  regular
expression in the INI-file, now it is: 
[0-9a-zA-Z]{5}-[0-9a-zA-Z]{5}-[0-9a-zA-Z]{5}-[0-9a-zA-Z]{5}-[0-9a-zA-Z]{5}, 
where 5 - number of digits, 0-9a-zA-Z - values. 
In fact, the program is a universal generic parser for strings of any kind... 
	After the first search in the program folder will be created an array of keys: 
file Garbage Collector Base.txt. This file should not be removed. The file will be updated  
when subsequent runs. The keys can (should) be checked in PIDKey and save necessary keys. 
	For the second and subsequent runs, if found new keys, will be available buttons 
"Save keys" and "Copy", first opens the standard window to save text file, in which we will 
place the new keys that are absent in database program, second - copy them to the clipboard. 
Button "Copy" and works during the search keys.
	The program can be run with the command-line options, specifying the path to the INI 
file and folder with scenarios: 
/path My_Path or /PATH "D:\My Path" 
Base previously found keys remains in the same place, near the executable.


*** If during your search you will be prompted to enter a "captcha", stop the autosearch, 
enter the "captcha" and click the button on the page. If you press Enter, the page just 
reloads. So, Google checks, you're a robot or not....

            ———————————————————————————————————————————————————————————————— 
                                                            Ratiborus & "Co" 


Changes in versions: 
v1.3.4 (build 09.12.2016)
 -Added the ability to right-click to select 1-12 button, then click the new button, everything 
  is processed sequentially.

v1.3.3 (build 11/15/2016)
 -Добавлена возможность указать диапазон ссылок. 
  Конструкция "#1-11" создаст 11 ссылок, подставив в адрес числа от 1 до 11

v1.3.1 (build 05/31/2016)
 -Small changes to the interface.

v1.3.0 (build 04/21/2016)
 -Small changes to the interface.

v1.3.0 (build 11/18/2015)
 -Small changes to the interface.

v1.3.0 (build 11/14/2015)
 -Small changes to the interface.

v1.3.0 (build 10/17/2015)
 -Further development of the program.

v1.3.0 (build 06/30/2015)
 -Further development of the program.

v1.3.0 (build 06/04/2015)
 -Further development of the program.

v1.2.0 (build 31.05.2015) 
 - Automatically closed windows search not for the full coincidence of names, but by presence of the key phrases in it.

v1.2.0 (build 04/28/2015)
 -Added automatic closing dialog boxes.

v1.2.0 (build 04/21/2015)
 -Added search in social networks (facebook.com, vk.com).

v1.2.0 (build 04/15/2015)
 -Small changes in code to improve reliability. 
 -Added button "Run a program PIDKey"

v1.2.0 (build 04/08/2015) 
 -The parameter "AutoCopyScr = 1" is no longer relevant, in code now measures are 
  taken to extract the keys, separated by tags. Set it to "AutoCopyScr = 0", 
  this should improve program stability.

v1.2.0 (build 04/01/2015) 
 -Changed the algorithm of work Autosearch button. 
 -When searching in Google when prompted to enter a "captcha" search stops. 
 -Search in ask.com replaced by Yahoo.

v1.2.0 (build 03/28/2015) 
 -Further development of the program interface, improved compatibility with Windows XP. 
 -Added launch with a command line parameter, you can specify the path to the INI file.

v1.1.2 (build 03/26/2015) 
 -Further development of the program interface. 

v1.1.2 (build 24.03.2015) 
 -Further development of the program interface. 
 -In the INI-file added parameter AutoScroll.

v1.1.2 (build 23.03.2015)
 -As a search query, you can specify a file containing multiple search queries.

v1.1.2 (build 18.03.2015) 
 -Program works with standard user rights, administrative privileges are NOT required.

v1.1.2 (build 16.03.2015) 
 -When you run the program prompted for administrator privileges. 
 -Rewrote the function selection keys.

v1.1.2 (build 13.03.2015) 
 -Further development of the program interface. 
 -In the INI-file added parameter FEATURE_BROWSER_EMULATION.

v1.1.2 (build 03/11/2015) 
 -Further development of the program interface.
 -The program supports searching in yandex.ru in automatic mode.  

v1.1.1 (build 03/10/2015) 
 -The program supports searching in www.bing.com in automatic mode. 
 -You can block pages on the mask with the sign "*". Example: "wikipedia*". Will be blocked all 
  links containing "wikipedia".

v1.1.1 
 -Added Switch "Search for keys only for Windows 8-10, Server 2012 R2 and 
  Office 2013" 
 -Increased the size of the array for blocked addresses to 1000 pieces.

v1.1.0 
 -Database keys is optimized when you exit the program.. 
 -When you exit the program, it remembers the open page. 
 -The program supports searching on www.baidu.com in automatic mode. 
 -Autosearch links works on Windows XP.

v1.0.9 
 -Further development of the program interface. 
 -All defined keys immediately written to the database, in case of hangs program, already 
  found keys you will not lose.

v1.0.8 
 -Further development of the program interface. 
 -Pressing the Enter key starts loading the entered link. 
 -Status check "Save to file" is saved in the INI file. 
 -64-bit version of the program was renamed in "GarbageCollector_x64.exe" 
 -If occurred "crash" program, then the next time you start the program, 
  the link, when booting which the failure occurred, will be added to the list of blocked. 
 -From links found in Google removed the redirects from Google itself, left clean links.

v1.0.7 
 -Further development of the program interface. 
 -Added the ability to put a link to the blocked list.


v1.0.6 
 -Further development of the program interface. 
 -Added ability to stop the execution of collecting "garbage" and separated from him 
  keys.



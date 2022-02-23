LOL Offical Cheat Dict 

idea:
In the beginning, I just wanted to practise my skills while looking for a job as Data Analyst, then I realised that the game I have played for 8 years League of Legends is a wonderful dataset since it has 159 champions and a number of data. After I downloaded and went through the file, I saw those allytips and enemytips written by Roit, which reminds me of the past happy time when playing LOL with friends. Therefore, I decided to abstract those key information, build a website and display those tiny tips on it for benefiting more people.

technical steps：
1.Download the newest documents from the official Riot website. https://developer.riotgames.com/docs/lol
2.Change the document format from Json to txt in order to read easily.
3.Regular expression to abstract the keywords and sentences （id, title, name, allytips, enemytips）.
4.Use python to delete all the other pictures except the origin for every champion.
5.Find a good-looking website template
6.Use python to produce html code chunks
7.Modify the website contents and details
8.Upload to github and deploy website

problems:
1. I thought to keep the smallest pic for saving the space and it turned out the difference can be ignored, therefore, for best identification, I decided to keep the origins instead of the skill pics.
2.When programming with python,   \ should be paid attention. However, windows can recognise even there are 2\ in address.
3.The ?(greedy & ungreedy) in the regular expression wasted me 2 hours.😀
4.Some champs' allytips and enemytips are missing, I filled in "Waiting for update".

You may want to know:
1.When i was learning website programming, i used dreamweaver and visual studio. But neither of them is in my new pc so i just used notepad to edit the website file.
2.From having the idea and website finished, it took me a whole afternoon.
3.Hope Riot can work with font awesome to make a unique logo, could be either the fist or the map of LOL.

thanks to html5up for the free website template.
thank Alex The Analyst for showing me how to deploy a website on github for free.

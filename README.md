Room	     - 
OutsiderCool - Github
Projects     - folder. (modules)
	The-Optimistic
	C-Programs
	Opacity-Transpacency-Progects
	WebsitesThroughDiff samabove

	Artificial Intelligence
	     Chatbots
	Algorithms


	Arrangin-A-Party
	
Crap
	FutureAndroidApplication
	(bad because not immediately launch)
	(and tutorial -not real)

design-code
~goal: everythoughtrecordedandthenorganized


# WebsitesThroughADifferentLense
WebsitesThrough HTML to JavaParser creating TransparentJavaLense
Webpage to become java gui

I need it to look at the webpage 
recognize all relative formats
All HTML formating
translate the HTML formating into java gui formating.











I'd use a decent HTML parser like Jsoup. It's then as easy as:

String html = Jsoup.connect("http://stackoverflow.com").get().html();

It handles GZIP and chunked responses and character encoding fully transparently. It offers more advantages as well, like HTML traversing and manipulation by CSS selectors like as jQuery can do. You only have to grab it as Document, not as a String.

Document document = Jsoup.connect("http://google.com").get();

You really don't want to run basic String methods or even regex on HTML to process it.
See also:

    What are the pros and cons of leading HTML parsers in Java?

shareedit
	
edited May 16 '11 at 22:31

	
answered Dec 31 '10 at 17:57
BalusC
583k14819202227
	
1 	 
	
Good answer. A little late. ;) –  jjnguy Jan 1 '11 at 0:00
28 	 
	
Better than never. –  BalusC Jan 1 '11 at 0:42
   	 
https://github.com/romainguy/road-trip	
Fantastic library :) Thx for that. –  Jakub P. Oct 8 '12 at 23:52 

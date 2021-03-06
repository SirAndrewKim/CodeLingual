# TransLang: The Programming Language Translator
The purpose of this web application is to help individuals quickly learn the basics of new languages by translating standard and common functions from one language to another (so like Google Translate, but for code)!

<b>The basic idea:</b> A user would type in the name of a standard function in a language that they know, and the application would return the equivalent function in another language (the desired language). 

For example, if a user typed in toUpperCase() and selected Java as their source lang, the app would return upper() if Python was selected as their target lang. 

<b>How it would work:</b> The application would run on both manual translations done by real people, and by automatic translations done with webscraping. (Completing the webscraping part before the project due date wouldn't at all be a priority, though.) Users of the application will be able to add new translations if their results come up blank and they want to contribute, and there will be an option to report translations as well. 

In terms of <b>MERN</b> architecture: 1. The database would be used to store translations/metadata; 2. Express+Node would be used for back-end work, which will include inserting and retrieving info from the database and webscraping if we get to that part; and 3. React would be for the front-end interface. (IF any of you guys are interested in AI, there's a way we could incorporate that to produce more accurate translations as well.)

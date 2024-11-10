java cDDWT Assignment Two
Version Changes	Details
Version 1.0	Initial Release
Version 1.1	Updated Task 1 to reflect task is to cover all card types
 
Pokemon League
 
All work is to be done individually and must be your own work. You must not share your @razor code or SQL with anyone else.  You must only submit code you have personally written (with the exception of utilising bootstrap html template examples). If you use other resources, you must include direct links to those resources as HTML/@razor comments at the bottom of the relevant files.  You are also reminded that use of AI tools for assignments in this course is considered academic misconduct.
Your task is to complete several web pages to search, view and add data relating to the South Australian Pokemon League database.  Do not leave this to the last minute as it is not possible to finish the project without prior thought to the implementation.  Writing queries is one thing but implementing SQL with programming logic in @Razor and HTML combined with Bootstrap presentation does require serious thought to get the desired functionality and outcomes!
Task
A web application containing the necessary database and MVC Views has already been created for you.  This can be downloaded from the assessments tab on the course website.  Your task is to complete several pages:
1. Views/PokemonCards/Index.cshtml
2. Views/PokemonCards/Detail.cshtml
3. Views/PokemonDecks/Index.cshtml
4. Views/PokemonDecks/Details.cshtml
5. Views/Tournaments/Index.cshtml
6. Views/Tournaments/Detail.cshtml
with the necessary layout using the WebMatrix data library, HTML, bootstrap v5.x and @Razor code.  Start by working on the PokemonCards/Index page that allows a person to view all the Pokemon cards in the database.  You will need to determine the best layout to present the data to our users and ensure you implement HTML Validation to reduce errors. Once this is working, start implementing the other pages in the order above.
Task 1: Pokemon Cards [30%]
url: PokemonCards/Index
This page is intended to display a comprehensive list of all cards available in the database. The page should retrieve all cards and display their attributes such as name, type, HP, Trainer type, energy type and any other relevant statistics, depending on what type of card they are. Users should be able to view this information in a clear and organized manner.
• HTML/Bootstrap Layout:
o Use Bootstrap's table or card components to present each card in an organized fashion.
o Include a search bar at the top of the page to allow users to filter cards by name or element  (if relevant). Utilize Bootstrap's form controls and grid system to ensure responsiveness.
o Implement a dropdown menu to filter by card type (Pokemon, Trainer, Energy)
o Each card entry should include a button or link that directs the user to the detail page for that specific card (PokemonCards/Detail?cardID=xx).
 
 
 
url: PokemonCards/Detail?cardID=xx
The detail page provides in-depth information about a specific card. It should display all detailed attributes such as the card's image, name, type, HP, attacks, any special abilities, trainer text, energy type or descriptions, etc. The page should retrieve the details of the card based on the cardID passed via the query string.
• HTML/Bootstrap Layout:
o Present the card's information in a visually appealing layout.
o Display the card image prominently.
o Include a back button to return to the index page.
o Use Bootstrap's alert components to handle and display error messages if an invalid cardID is provided or if the card is not found.
 
 
Task 2: Pokemon Decks [30%]
url: /PokemonDecks/Index
This page displays a list of all Pokémon decks stored in the database. It should retrieve the decks and display information such as the deck name, creator, and the number of cards in each deck. Users should be able to sort or filter the list of decks.
• HTML/Bootstrap Layout:
o Use a card layout to present each deck's information.
o Provide sorting options for deck代 写program、 SQL
代做程序编程语言 name and player name.
o Each deck entry should include a link or button to view its details (PokemonDecks/Detail?deckID=xx).
 
url: /PokemonDecks/Detail?deckID=xx
The detail page shows comprehensive information about a selected Pokémon deck, including the list of Pokémon cards it contains. It should retrieve the deck details and associated cards using the deckID.
• HTML/Bootstrap Layout:
o Display the deck's name and creator prominantly.
o List the cards in the deck, using Bootstrap's list group or card deck components.
o Each card in the list should link to its respective detail page.
 
Task 3: Tournaments [30%]
url: /Tournaments/Index
This page lists all tournament results available in the database. It should display information such as tournament name, date, location, and status. Users should be able to browse through the list and view tournament results of interest.
• HTML/Bootstrap Layout:
o Use a table or card layout to present each tournament's information.
o Include filters or search functionality to help users find tournaments by name, date, or location.
o Each tournament entry should include a link or button to view more details about the tournament (Tournaments/Detail?tournamentID=xx).
 
url: /Tournaments/Detail?tournamentID=xx
The detail page provides comprehensive information about a specific tournament. It should display details such as the tournament name, date, location, participants, and match results.
• HTML/Bootstrap Layout:
o Display the tournament's information prominently at the top of the page.
o List the participants and match results, using bootstrap elements
o Include navigation buttons to return to the tournaments index page.
o Implement error handling using Bootstrap alerts if an invalid tournamentID is provided or if the tournament is not found.
 
Mark Breakdown
Pages [90%]
• Correct SQL statements
• Correctly structured HTML in pages
• P Grade: Basic bootstrap implementation, basic query implementation, very simplistic.  Basic HTML and HTML Forms understanding.
• C Grade: Good bootstrap implementation and some investigation of bootstrap documentation.  Basic usage of bootstrap utilities.  SQL queries acceptable, somewhat optimised.  Code quality basic including expected HTML Forms attributes etc.  Consistent layout and professional looking pages as expected when using bootstrap CSS correctly.
• D Grade: Excellent use of bootstrap documentation and classes demonstrating investigation and experimentation of what’s available to create excellent looking customised layouts.  SQL Queries are optimised, well crafted, page structure shows in-depth knowledge and thought of functionality.  HTML is optimised to reduce errors and improve user experience.  SQL demonstrates thought and includes aggregate and sub-queries to provide additional and useful information. All tables available used to obtain relevant information. Professional looking pages
• HD Grade: Extensive exploration of bootstrap documentation and classes to create a custom layout using the available classes.  Razor code demonstrates experimentation with conditional statements around HTML, managing various value conditions with suitable messages, well structured and thoughtful code to reduce errors.  SQL demonstrates thought and includes aggregate and sub-queries to provide additional and useful information that is efficiently combined with Razor Code. All tables available used to obtain relevant information. Professional looking pages.
HTML Validation [10%]
• Check that your final generated HTML is valid and does not contain any errors.  You will need to run your page, then right click on it in the web browser and select “View Source” to check the html.   Images should have custom alt text etc.  
 
Note: All code must be done using the style and approach utilised throughout the course – you must not utilise lambda/LINQ expressions and your code must demonstrate the basic concepts covered based on the WebMatrix library.
 
Domain Model Diagram

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

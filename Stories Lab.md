# Stories Lab
## Wed, 7-12-2022
---


### Ideas:

types of stories and points to include:
* your experience building a certain project
   * what the project is
   * what technology you used
   * why you chose that technology
   * something you learned from your time building the project
* an experience fixing a bug
   * what the bug was
   * how you found it
   * what you did to fix it
* an experience learning a new technology
   * what tech you were learning
   * why you chose that
   * how you’ve used it since
   

---


### My Stories:
________________


1 | Fixing A Bug
Dragons Keep was a SPA(single-page application) I created as a final project of sorts for the first half of my time at the DevMountain coding bootcamp. 
In that project I had a welcome display which took up the whole page upon loading into the app. It was just a simple div, with a logo. I had it set up so on click it would play a simple slide up and fade animation before becoming invisible and allowing the user to move on using the app.
Implementing it’s functionality was a mini challenge itself given  I had never made and animation before, but I got that. The bigger problem came after. 
When I had all the whole animation figured out I was testing it and found that if I scrolled down on the page before reloading it, when the page loaded back up it would be stuck wherever I had previously scrolled to. 
I tried a few ways of fixing this but after a couple hours of trying different things and looking at documentation I decided to do a combination of a few things. 
First I had the window scroll to the top before the page reloaded, cause I wanted to ensure that the page always opened at the top anyway. Then I also decided to hide the y-overflow to lock the scroll while on the welcome screen. 
This got rid of the ugly reloading glitch and made the reload work exactly as I wanted it to.
________________


2 | Experience building Dragons Keep
Dragons Keep was my first full-stack solo project, and at the start of it all, I was admittedly feeling a bit overwhelmed. 
Simply put, it was an digital compendium of characters from the game franchise, dragons age. It had a main view with character cards for all the characters. On click each card would open up into a more detailed view with that characters info like a desc, quote and basic stuff like class and race. There was a simple search bar that would pull up a character based on name and the user could both delete characters and add their own inquisitor, which for context is the play protagonist of the third game in the franchise which I was pulling all the characters from.
It was made with JS and the usual HTML and CSS. To store my data, I choose to use simple JSON files. I had three in total, 
one for characters and their associated information thats the one I would append or delete from depending on if the user added or removed characters, 
one for the class info that would be needed when creating a character 
and lastly one for the general info that would be needed for character creation (descriptions based on race, links for the images associated with a certain race and gender.
I decided to keep all these in separate files to keep it all organized and to make queries easier for me to handle.
Finally to handle those queries and the data exchanges I used axios and the node packages express and cors. 


So, like I said I was pretty overwhelmed when I first started the project, but I took it one step at a time and made sure to spend plenty of time in the planning phase with the idea that before I even started coding I needed to understand how things were going to work on and what functionality I would need. 
Looking back I’m actually really proud of the work I did during that planning period. I drew out ideas for the site, made low and hi-fi wireframes, worked out the data I would need to store, figured out I should probably just use JSON files to store said data and so on. 
By the time I got to actually setting up my directory and coding, I had a full game plan. I had a list of end-points and the associated processes, I had fully fleshed out wireframes that really helped my figure out the functionality, which I of course also listed out. I was fully prepared to code and felt confident jumping in.
I will say though, I still had to alter things later on. Prior to making Dragons keep I was still murky on how the queries associated with endpoints worked syntactically, but while coding I figured that out and appended my code to reflect that new knowledge.
Overall it was a wonderful learning process and fun project that really helped me to learn not only the basic process behind making a full-stack app, but also how to find/navigate the immense documentation you can find online.


________________
Step Three: Finalize
Choose your top 2 from the previous step and add some polish. Make sure you’ve included necessary details and that the story flows. Optionally, think of some questions that this story could answer and/or practice telling your stories to a classmate.
Step Four: Turn In
Create a repo on GitHub and upload your stories to it.
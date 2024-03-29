# Discovering Ecuador

In the Pacific coast of South America, just crossed by the Ecuadorian line, we can find one of the most amazing countries in the world.
Its beautiful coasts, its high mountains and volcanos, the wild Amazoninan Rainforest in the west side and those islands, which helped Dariwn
with that book that changed the way to look at the human being, attract thousands of tourists every years.
I am speaking about Ecuador, a little country with 4 different worlds inside it. Ecuador is the perfect destination if you are looking for
fun or relax or adventure and it is also perfect if you go alone or with your family.

## UX

As for the project's title, the main goal of this website is to inform about Ecuador and its geological structure. The website is
focused to that people who are looking for trvel destination ideas or just someone who needs a general overview on the country for a personal
project or school homworks.

In order to see some of this project mockups, please find them inside the Mockups folder.

## Features

The project is divided in 6 html files and one css file in order to style them all.

#### Home page

You can find the home page in the index.html file.
It has the same main structure (and background image) as the other pages and its divided as below:

- the header is composed by a navbar where we can find the Ecuadorian flag (that also works as an home link) and the two main links
    - the "home" link that always brings the user to the homepage and the "about" link for the About page

- then we can find the main and secondary titles (differents in each region) followed by a section with an introductory photo of the region
  and a little captive description in order to grab the users's attemption. The photos also work as link to the different regions pages.

- at the very bottom of the page you will find the social networks link (Instagram, LinkedIn and Twitter)

#### Regions pages

All the regions pages share the same structure

- a little descriptive introduction which gives some info about the topic

- a photo gallery with 6 or 4 photos depending on the screen size (each photo can be viewed full screen just clicking on it)

- a map (Google map) that should help the user in order to locate the region in the country.

#### About page

The "about" page is focused on who I am and why I chose Ecuador as main topic in the project.
It also provide a "fake" form in order to submit any question the user could have related to Ecuador

### Existing Features
- Form in the "About" page - would allow users to ask questions or give feedback directly to the website creator by filling the textarea element
and providing his/her name and email address (mandatory)

### Features Left to Implement
- Little forum or comment section where users can interact with each other with personal opinions or advises about the main topic

## Technologies Used

- [bootstrap](https://getbootstrap.com/docs/4.3/getting-started/download/)
- [fontawesome](https://fontawesome.com/icons?d=gallery)
- [JQuery](https://jquery.com)

## Testing

The first tests about the good website functionality have been done locally, using the Google Chrome tool. Using it I was able to test the project trough a big device variety
and in a responsive environment.
Once everyhting looked good in the Chrome environmnet, the project has been tested in the others browsers (Mozilla, IE and Edge)
The wesite has then been tested in phisical differet devices (iPad, iPhone 8 and Honor 9) and after the good feedback has been sent to multiple contacts in order to test it
in more devices as possible.
All of them has been given some specific tasks in order to test each one of the critical features of the project.
In particular they had to test the form located in the About page and check if after submitting a question whitout providing an email address or a name the form will respond
with an "error" message.
The other specific task they needed to test was the good functionality of the photo gallery. Once they clicked on one of the photos, it should have been displayed full screen
with the option to switch from one to the following/previous one.
Most of the feedbacks have been positive.

The only negative feedbacks came from iOS users, who faced a background image completely stretched (did not make any difference if was an iPhone or an Ipad, if they were using Safari or Chrome). As I could not find anything related to this
problem in internet, I asked for help to the Code Insitute's tutors who said that was probably due to the fact that GitHub was not loading the
image correctly in the iOS devices. So they give me a workaround changing the CSS background-attachment attribute from fixed to scroll for the screen up to 414px wide.


## Deployment

The project deployment has been done using GitHub pages.
The pubblic accessible web link of my project has been deployed by going to GitHub --> Ecuador repository --> Settings --> scrolling down until GitHub Pages and
changing the first option from None to Master Branch.

In order to run the code locally you need to click on the Clone or Download button. There you have 2 option, or download the zip directly or run the command "git clone https://github.com/TheTraveller95/Ecuador.git" in your machine's terminal after having navigated to the folder you want to save the code into.


## Credits

### Content
- The text for section Coast was copied from the [Ecuador.com article titled "TRAVEL THE PACIFIC COAST IN ECUADOR, CITIES, TRAVEL DESTINATIONS"](http://www.ecuador.com/regions/costa-coastline/)
- The text for section Andes was copied from the [Ecuador.com article titled "TRAVEL ECUADOR’S ANDES MOUNTAINS, TRAVEL DESTINATIONS"](http://www.ecuador.com/regions/sierra-andes/)
- The text for section Amazon was copied from the [Ecuador.com article titled "TRAVEL THE AMAZON IN ECUADOR, TRAVEL DESTINATIONS"](http://www.ecuador.com/regions/oriente-amazon/)
- The text for section Galapagos Islands was copied from the [Ecuador.com article titled "TRAVEL TO THE GALAPAGOS ISLANDS IN ECUADOR, TRAVEL DESTINATIONS"](http://www.ecuador.com/regions/galapagos-islands/)
and from the [Wikipedia article titled "Galápagos Islands"](https://en.wikipedia.org/wiki/Gal%C3%A1pagos_Islands)

### Media

- Some of the photos used in this site come from my personal gallery
- You will find the other ones vsiting the following pages
    - https://dissolve.com/stock-photo/Morpho-butterfly-displaying-leaf-Morpho-achilles-Amazonia-royalty-free-image/101-D1267-37-069
    - https://www.tes.com/lessons/e4TiG8B7SG8NQg/copy-of-save-the-rain-forest
    - https://www.firesideadventures.ca/amazonia-indigenous-roots-of-ecuador
    - https://www.ecuadortv.ec/noticias/actualidad/ampliara-zona-intangible-amazon%C3%ADa-ecuatoriana
    - https://www.selina.com/ecuador/amazon-tena/
    - https://es.wikipedia.org/wiki/Saguinus_tripartitus
    - https://www.newscientist.com/article/2197998-the-waters-of-the-galapagos-islands-are-being-invaded-by-alien-species/
    - https://www.kuoni.co.uk/ecuador-and-galapagos/the-galapagos-islands
    - https://aladdintravel.com/college-spring-break/galapagos-seal/
    - https://www.theglobetrottergp.com/the-galapagos-islands-wildlife-paradise-and-a-whole-lot-of-boobies-part-1-the-eastern-islands/
    - https://www.galapagosunbound.com/blog
    - https://www.voyagers.travel/wonders-3/

### Acknowledgements

- I received inspiration for this project from the experience and knowledge about the main topic I got living in Ecuador.
- About the coding related technical knowledge, the https://www.w3schools.com website really helped me a lot.
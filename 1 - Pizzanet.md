#PizzaNet: The Fulfillment of a Hacker Dream

It's the Summer of 1994, and the World Wide Web is barely 3 years old. The first lines of code for Internet Explorer 1.0 are being written by Microsoft engineers in Seattle and nearby, Jeff Bezos has recently incorporated Cadabra, the company that will later launch Amazon.com. Pierre Omidyar is still a year away from registering eBay.com.

Meanwhile, 1,700 miles away in Wichita, Kansas, an international food chain founded in 1958 is preparing to launch one of the first eCommerce sites in Internet history. On Monday, August 22nd 1994, Pizza Hut and the Santa Cruz Operation issued a joint press release announcing the launch of PizzaNet, “a pilot program that enables computer users, for the first time, to electronically order pizza delivery from their local Pizza Hut restaurant via the worldwide Internet.”

As Bill Higgins of Fermilab wrote to the Computer-Under Digest:

> “History has been made.  Ordering pizza from your computer.  It's the fulfillment of a hacker dream at least as old as computer networking.”


###Unusual innovators
It was a pivotal moment. For the first time a major corporation (Pizza Hut was owned by PepsiCo at the time) chose to use the web to sell directly to their customers. 

The project was conceived by Jon Payne (of Pizza Hut) and Doug Michels of the Santa Cruz Operation. SCO was arguably the first commercial UNIX software company and the makers of SCO Unix, which was used at the time to run Pizza Hut's ordering systems. 

That system was called PHOEBE - "The Pizza Hut Order Entry Back End." SCO employees Phil Neuman and Steph Marr took on the project of building an HTML form flow for ordering, but for truly automated ordering they needed to integrate the website with Pizza Hut's backend system. Steph Marr left Santa Cruz for Wichita: "I remember being stuck in a Tornado bunker in Wichita ... arguing with UUnet about IP addresses, domain registrations, and routing", he told me.  

The first pizza was ordered and delivered to Phil Neuman of SCO on Friday, August 12th, 1994. Ten days later, SCO and Pizza Hut went public, and the site was live on PizzaHut.com.

<p align="center"><img src="https://github.com/sinak/stripe-blog-posts/raw/master/1%20-%20images/pizza1.jpg" /></p>

Rob Doughty, the author of the original launch press release, and VP of Communications at Pizza Hut at the time of the launch, gave me a taste of Pizza Hut's side of the story: “We’d spent months in meetings trying to figure out this Internet thing,” he told me, “some bright spark realized that by taking orders online we could build a great customer database. We’d have their address, phone number, email address, and then marry that with pizza preferences.” All told, Pizza Hut estimated that they saved $1.17 per order ($0.17 for labor, $1.00 for not taking coupons via that mechanism) per transaction.


###The Designer Pizza
The launch was heralded by some great headlines: "'CYBERCHOW'-TO-GO ROLLS ONTO THE INFOBAHN" (Albany Times Union), "PIE A LA MODEM" (The Washington Post), "HACKERS PUNCH UP A PIZZA" (Post Tribune).

The LA Times' article, entitled [On-Line Pizza Is Clever but Only Half-Baked](http://articles.latimes.com/1994-08-25/business/fi-31168_1_pizza-hut), is a fun artefact fun to read. The author - Michael Schrage, at the time a research associate at MIT – doesn’t think much of of the idea though:

> Still, as computationally clever as on-line ordering may be, it misses the point of what this medium can do. Fundamentally, there's not much difference between ordering a pizza over the phone and ordering one on-line. The transaction is basically a commodity. The trick is to figure out new ways to create value for the customer.

> Instead of simply letting people order a pizza, why not let them design it as well? Instead of showing an ordinary menu with a list of toppings, show a picture of a pizza with the toppings clustered on the side. Let teen-agers and college students build their own pizzas on-screen. Present a palette of toppings and let people place their mushrooms and green peppers and pepperoni anywhere on the pizza they want. The real pizza is customized accordingly. In other words, computer-aided pizza engineering.

In fact, Domino's, Pizza Hut's main competitor, was working on a graphical UI for pizza ordering with a company called EON Corp. As far as I was able to tell, that effort never saw the light of day.

###11 days earlier: NetMarket
Pizza Hut and SCO were actually just a few days off from making Internet history. Eleven days before the PR blast, and 1 day before the first Pizza was delivered, a company called NetMarket made the first commercial eCommerce transaction. At around noon of August 11th 1994, Phil Brandenberger of Philadelphia ordered the Sting album “Ten Summoner’s Tales” from NetMarket.com for $12.48, marking the first eCommerce transaction in Internet history. 

That transaction required some determination. NetMarket, founded by Daniel Kohn and Guy Fernald, had ported a version of ViaCrypt PGP for their servers, and published their public Key. To make a purchase, Phil Brandenberger had to install PGP on his local Unix machine (Windows and Mac were not supported), compile X Mosaic using custom scripts that enabled PGP encryption, and then send his own public key to NetMarket.

NetMarket was born by Swathmore and LSE graduates working out of a house in New Hampshire, with the typical student-entrepreneur setup: bedrooms upstairs, and the broadband line and office downstairs. Dan Kohn remembers the time fondly, "Living in that house in New Hampshire is one of my fondest memories. BUt it's amazing how hard things were then, how complicated the tools were. We were leveraging UNIX and HTTPD and other early open source software. But when you look at what's available today, and how much easier it is, it's mind-boggling to me."

Dan Kohn claims that they had the earliest shopping-cart system on the web, and he dug out some never-since-seen screenhots of the original site for us to share here. It's amazing to see how little the shopping cart paradigm has changed since then:


<p align="center"><img src="https://github.com/sinak/stripe-blog-posts/raw/master/1%20-%20images/netmarket-1.gif" /></p>
<p align="center"><img src="https://github.com/sinak/stripe-blog-posts/raw/master/1%20-%20images/netmarket-2.gif" /></p>


About 6 months later, Netscape publicly released the first version of the SSL protocol, which despite having “a number of security flaws,” paved the way for online commerce as we know it.

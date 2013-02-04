#The PizzaNet

It's August of 1994, and the World Wide Web is barely 3 years old. Microsoft engineers have just begin writing the first lines of code for Internet Explorer 1.0. Jeff Bezos arrives in Seattle, fresh from his cross-country drive in an '88 Chevy Blazer. He's just started work on the company that'll become Amazon.com. Further south, in Silicon Valley, Pierre Omidyar is still a year away from registering eBay.com.

1,700 miles away in Wichita, Kansas, an networking and security architect is in a tornado bunker, arguing with one of the early tier 1 ISPs about IP addresses, domain registrations, and routing. Steph Marr is making final preparations for the launch of one the first eCommerce sites on the internet.

On Monday, August 22nd 1994, Pizza Hut and the Santa Cruz Operation issue a joint [press release](http://www.interesting-people.org/archives/interesting-people/199408/msg00057.html) announcing the launch of PizzaNet, “a pilot program that enables computer users, for the first time, to electronically order pizza delivery from their local Pizza Hut restaurant via the worldwide Internet.”

As Bill Higgins of Fermilab [writes](http://cu-digest.org/CUDS6/cud6.83) to the Computer Underground Digest, “History has been made.  Ordering pizza from your computer.  It's the fulfillment of a hacker dream at least as old as computer networking.” 


###Dough for cash
It was a pivotal moment in Internet history. For the first time a major corporation (Pizza Hut was owned by PepsiCo at the time) has launched a website  to sell directly to their customers.

The PizzaNet was conceived by Jon Payne of Pizza Hut and Doug Michels of the Santa Cruz Operation (SCO). SCO was arguably the first commercial UNIX software company and the maintainers of SCO Unix, which was used at the time to run Pizza Hut's ordering systems. 

That system was called PHOEBE - "The Pizza Hut Order Entry Back End." After the initial idea was discussed internally, SCO employees Phil Neuman and Steph Marr were assigned the task of building an HTML form flow for ordering. But for truly automated ordering they needed to integrate the PizzaNet website with PHOEBE. Once the ordering flow was complete, Steph Marr flew out to Wichita to coordinate the integration with Pizza Hut's Kurt Schmidt. 

According to an easter egg on the site, activated by clicking the Pizza Hut logo multiple times: "After a few false starts, a few hundred cups of coffee, and only a couple of weeks, the link was made, and the first pizza was ordered
and delivered (to Phil in Santa Cruz) on Friday, 12 August, 1994." Ten days later, SCO and Pizza Hut went public, and the site was launched on PizzaHut.com.

<p align="center"><img src="https://github.com/sinak/stripe-blog-posts/raw/master/1%20-%20images/pizza1.jpg" /></p>

[Rob Doughty](http://robdoughtycommunications.com/robdoughtycommunications.com/Welcome.html), the author of the original launch press release, and VP of Communications at Pizza Hut at the time of the launch, gave me Pizza Hut's side of the story. 

“We’d spent months in meetings trying to figure out this Internet thing,” he said. “Some bright spark realized that by taking orders online we could build a great customer database. We’d have their address, phone number, email address, and could then marry that with pizza preferences.”

Not only that, but the profit margins on Internet-ordered pizza turned out to be higher. Pizza Hut estimated that they saved $1.17 per order ($0.17 for labor, $1.00 for not taking coupons via that mechanism) per transaction.


###The Designer Pizza
The launch got both companies some great press, and reporters had fun with the headlines: "'CYBERCHOW'-TO-GO ROLLS ONTO THE INFOBAHN" (Albany Times Union), "PIE A LA MODEM" (The Washington Post), "HACKERS PUNCH UP A PIZZA" (Post Tribune).

The LA Times' article, entitled [On-Line Pizza Is Clever but Only Half-Baked](http://articles.latimes.com/1994-08-25/business/fi-31168_1_pizza-hut), is a fun artefact to read. The author - Michael Schrage, at the time a research associate at MIT – didn’t think much of the idea:

> Still, as computationally clever as on-line ordering may be, it misses the point of what this medium can do. Fundamentally, there's not much difference between ordering a pizza over the phone and ordering one on-line. The transaction is basically a commodity. The trick is to figure out new ways to create value for the customer.

> Instead of simply letting people order a pizza, why not let them design it as well? Instead of showing an ordinary menu with a list of toppings, show a picture of a pizza with the toppings clustered on the side. Let teen-agers and college students build their own pizzas on-screen. Present a palette of toppings and let people place their mushrooms and green peppers and pepperoni anywhere on the pizza they want. The real pizza is customized accordingly. In other words, computer-aided pizza engineering.

Amusingly, Domino's actually doing just that. Working with a company called EON Corp they were building a graphical UI for pizza ordering. As far as I was able to tell, that effort never saw the light of day.

###11 days earlier
Pizza Hut and SCO were very close to making eCommerce history. Eleven days before the PR blast and one day before the first Pizza was delivered, a company called NetMarket made the first recorded  eCommerce transaction. At around noon of August 11th 1994, Phil Brandenberger of Philadelphia ordered the Sting album “Ten Summoner’s Tales” from NetMarket.com for $12.48, marking the first eCommerce transaction in Internet history. 

That transaction required some determination. NetMarket, founded by Daniel Kohn and Guy Fernald, had ported a version of ViaCrypt PGP for their servers, and published their public key. To make a purchase, Phil Brandenberger had to install PGP on his local Unix machine (Windows and Mac were not supported), compile X Mosaic using custom scripts that enabled PGP encryption, and then send his own public key to NetMarket.

NetMarket was founded by Swathmore and LSE graduates working out of a house in New Hampshire, with the typical student-entrepreneur setup: bedrooms upstairs, and the broadband line and office downstairs. Kohn remembers those times affectionately. 

"Living in that house in New Hampshire is one of my fondest memories. But it's amazing how hard things were then, how complicated the tools were. We were leveraging UNIX and HTTPD and other early open source software ... but when you look at what's available today, and how much easier it is, it's mind-boggling to me."

Kohn claims that they had the earliest shopping-cart system on the web, and he dug out some never-since-seen screenhots of the original site for us to share. It's amazing to see how little the shopping cart paradigm has changed since then:

<p align="center"><img src="https://github.com/sinak/stripe-blog-posts/raw/master/1%20-%20images/netmarket-2.gif" /></p>
<p align="center"><img src="https://github.com/sinak/stripe-blog-posts/raw/master/1%20-%20images/netmarket-1.gif" /></p>

Kohn is now working on a new startup, [ShopMyLabel](http://shopmylabel.com), and when I called him to discuss NetMarket he happened to have the new [Stripe checkout](https://stripe.com/blog/stripe-checkout) open in a browser tab. He told me they're planning on using it for the next revision of ShopMyLabel. For one of the inventors of eCommerce and the first online shopping cart to be considering using our product is an honor to say the leasst.

###A developing story

Pioneers like NetMarket, SCO, and Pizza Hut are in our recent past; it's less than two decades since the first eCommerce transactions were being made. The barriers to selling online have shrunk considerably, but we're still in the early days of online commerce. Twenty years from now, it's likely that Stripe Checkout will look as dated as the original NetMarket and PizzaNet. We're excited to be a part of that narrative, and eager to see what the next 20 years of online commerce have in store.

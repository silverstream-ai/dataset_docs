# Task

**Exploring Integrations for Orderli**

As a restaurant owner,
I explore integration options with Orderli,
so that I can find the right tools to enhance my ordering system.

**Success definition:** Given I am on the Orderli website and can access the integrations section
When I click on the Integrations link, then on the Lightspeed K integration link, and finally the 'Try Orderli for Free' button
Then I should be navigated to the Lightspeed K-series integration page and see a form to fill out my details for the trial.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://orderli.com/en/

https://orderli.com/en/integrations

**Content (before/after):** 

```
RootWebArea QR Code Ordering for Restaurants, focused, url='https://orderli.com/en/'
	banner
		link Orderli logo, url='https://orderli.com/en/'
			[61] image Orderli logo, center=(440,35), url='https://orderli.com/images/Orderli-logo-oranje.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[95] button Orderli for, center=(575,36), expanded=False, hasPopup='menu'
			[130] link Integrations, center=(695,36), url='https://orderli.com/en/integrations.html'
			[131] link Pricing, center=(788,36), url='https://orderli.com/en/pricing.html'
			[132] link Demo, center=(858,36), url='https://orderli.com/en/demo.html'
			[133] link About us, center=(935,36), url='https://orderli.com/en/about.html'
			[134] link Contact, center=(1020,36), url='https://orderli.com/en/contact.html'
			[135] link Log in, center=(1370,36), url='https://admin.orderli.com/login'
		[140] link Try for free, center=(1470,34), url='https://orderli.com/en/#cta'
	image, url='https://orderli.com/images/iStock-1129572627-1-2-p-2000.jpeg'
	heading The best ordering solution for restaurants & bars
	paragraph
		StaticText Orderli is the best ordering solution for restaurants and bars according to guests.
	[165] link Start with 14 day trial, center=(960,520), url='https://orderli.com/en/#'
	heading Trusted by hundreds of businesses, including:
	image Brouwerij Troost logo, url='https://orderli.com/images/troost-logo---min.jpg'
	image Van der Valk logo, url='https://orderli.com/images/van-der-valk-logo---min.png'
	image Avocado show logo, url='https://orderli.com/images/The-Avocado-Show-Logo-Black.svg'
	image Schiphol logo, url='https://orderli.com/images/schiphol.svg'
	image Brasa Purmerend logo, url='https://orderli.com/images/brasa-black---min.png'
	image Bierfabriek logo, url='https://orderli.com/images/bierfabriek-simple.svg'
	paragraph
		StaticText No app needed
	heading Experience how easy it is
	image, url='https://orderli.com/images/icons8-qr_code-1.svg'
	heading Scan
	StaticText Guests scan the QR-code on their table with their phone and get taken to our website.
	image, url='https://orderli.com/images/icons8-topup_payment-1.svg'
	heading Order
	StaticText They're immediately in the menu and able to choose what they want to order.
	image, url='https://orderli.com/images/icons8-easy-1.svg'
	heading Done
	StaticText Once guests place their order we send it directly to your staff.
	image, url='https://orderli.com/images/arrow-with-loop-dotted.svg'
	link Start demo, url='https://orderli.com/en/#'
	StaticText Or try it with your own phone
	image QR Code leading to a demo, url='https://orderli.com/images/qr-path-orderli-demo.svg'
	StaticText 👆🏼Scan the QR-code with your camera
	paragraph
		StaticText FEATURES
	heading Suitable for any type of hospitality business.
	tablist, orientation='horizontal'
		tab Bars, selected=True
		tab Restaurants, selected=False
		tab Hotels, selected=False
		tab Festivals, selected=False
	tabpanel Bars
		link Advances upselling features Right arrow, url='https://orderli.com/en/bars.html'
			image, url='https://orderli.com/images/icons8-pint-90.png'
			image Right arrow, url='https://orderli.com/images/simple-arrow-right.svg'
		link Happy Hours integration Right arrow, url='https://orderli.com/en/bars.html'
			image, url='https://orderli.com/images/icons8-hourglass-1.svg'
			image Right arrow, url='https://orderli.com/images/simple-arrow-right.svg'
		link Pay bill afterwards Right arrow, url='https://orderli.com/en/bars.html'
			image, url='https://orderli.com/images/icons8-topup_payment-1.svg'
			image Right arrow, url='https://orderli.com/images/simple-arrow-right.svg'
		link Optimized for large drink menus Right arrow, url='https://orderli.com/en/bars.html'
			image, url='https://orderli.com/images/icons8-restaurant_menu-1.svg'
			image Right arrow, url='https://orderli.com/images/simple-arrow-right.svg'
	image Waitress servicing guests, url='https://orderli.com/images/service-foto-min.jpeg'
	heading Keep it personal.
	paragraph
		StaticText Orderli is an addition to your staff — not a replacement.
		StaticText ‍
		StaticText By using Orderli to take orders, staff will have more time to chat with guests and ensure guests are noticed and served more quickly.
	heading Seamless integration with your POS and other systems.
	paragraph
		StaticText Orders are entered into the POS automatically with our integration. Helping staff serve orders like they're used to.
	image Lightspeed L-series logo, url='https://orderli.com/images/lightspeed.svg'
	StaticText Lightspeed
	image Vectron logo, url='https://orderli.com/images/logo-vectron.png'
	StaticText Vectron
	image unTill logo, url='https://orderli.com/images/logo-untill.png'
	StaticText unTill
	image Index logo, url='https://orderli.com/images/index.svg'
	StaticText Index
	image Square logo, url='https://orderli.com/images/logo-square.png'
	StaticText Square
	image Toast logo, url='https://orderli.com/images/logo-toast.png'
	StaticText Toast
	image Micas logo, url='https://orderli.com/images/logo-micas.png'
	StaticText Micas
	image Mpluskassa logo, url='https://orderli.com/images/logo-mpluskassa.png'
	StaticText Mpluskassa
	image, url='https://orderli.com/images/epson.svg'
	StaticText Epson
	image Citizen logo, url='https://orderli.com/images/Group-47citizen.svg'
	StaticText Citizen
	image, url='https://orderli.com/images/star.svg'
	StaticText Star
	image CCV logo, url='https://orderli.com/images/ccv-logo-p-500.png'
	StaticText CCV
	image Mollie logo, url='https://orderli.com/images/Mollie-logo-dark.svg'
	StaticText Mollie
	image Adyen logo, url='https://orderli.com/images/1024px-Adyen_Corporate_Logo.svg.png'
	StaticText Adyen
	image Stripe logo, url='https://orderli.com/images/Stripe-wordmark---blurple.svg'
	StaticText Stripe
	image Sumup logo, url='https://orderli.com/images/Sumup_logo.svg'
	StaticText Sumup
	image Bitpay logo, url='https://orderli.com/images/bitpay.svg'
	StaticText Bitpay
	image Mailchimp logo, url='https://orderli.com/images/Mailchimp_Logo-Vertical_Black.png'
	StaticText Mailchimp
	image Google Analytics logo, url='https://orderli.com/images/google_analytics-official.svg'
	StaticText Google Analytics
	image Google logo, url='https://orderli.com/images/google_g_icon_download.png'
	StaticText Google Reviews
	image Facebook logo, url='https://orderli.com/images/f_logo_RGB-Grey_512-p-500.png'
	StaticText Facebook Pixel
	image Gify logo, url='https://orderli.com/images/logo-1.svg'
	StaticText Gifty
	image Lightspeed L-series logo, url='https://orderli.com/images/lightspeed.svg'
	StaticText Lightspeed
	image Vectron logo, url='https://orderli.com/images/logo-vectron.png'
	StaticText Vectron
	image unTill logo, url='https://orderli.com/images/logo-untill.png'
	StaticText unTill
	image Index logo, url='https://orderli.com/images/index.svg'
	StaticText Index
	image Square logo, url='https://orderli.com/images/logo-square.png'
	StaticText Square
	image Toast logo, url='https://orderli.com/images/logo-toast.png'
	StaticText Toast
	link More about integrations, url='https://orderli.com/en/integrations.html'
	heading Stay in control.
	paragraph
		StaticText With an (optional) small tablet next to your POS, staff can see what is being ordered and decide when to prepare.
		strong
			StaticText Is something temporarily out of stock?
		StaticText In 3 seconds your staff can turn a menu item off with our restaurant software, making it disappear immediately from the menu for guests.
	image Tablet showing orders for tables, url='https://orderli.com/images/Orderli-tablet-new-1.svg'
	heading Business owners love Orderli.
	region carousel
		group 2 of 6
			image Testimonial Image, url='https://orderli.com/images/Cocos-zaak-foto---min-p-500.jpeg'
			image Entree magazine logo, url='https://orderli.com/images/entree-min.png'
			image Coco's Outback logo, url='https://orderli.com/images/cocos.png'
			heading “Previously, an employee would sometimes sit at a table for twenty minutes to take orders from large groups of students. Thanks to Orderli, that is a thing of the past. Especially during peak times, it saves a lot of time and hassle that guests order themselves and pay online immediately.” - Joey Elzas
				strong
			link Read more on EntreeMagazine.nl, url='https://www.entreemagazine.nl/adv-orderli-meer-tijd-voor-gastvrijheid-bij-cocos-outback-door-orderli'
		StaticText Slide 2 of 6.
		button previous slide
			StaticText 
		button next slide
			StaticText 
	heading And guests agree.
	paragraph
		StaticText In their words.
	link Profile picture Jan Willem Foppen Filled star Filled star Filled star Filled star Filled star 8 months ago Ontzettend leuke gezellige relaxte sfeer met  lekker eten, goed geprijsd, mooie porties. Aardige attente bediening. Bestelling mbv n QR code. Meestal krijg je dan een of ander bestellingsformulier waar je van alles over jezelf moet invullen (naam, adres, etc), maar niet hier: scannen, bestellen, pats klaar. Simpel en snel. Heel goed!, url='https://goo.gl/maps/L9nPbPTK5ccvBQPK7'
		image Profile picture, url='https://orderli.com/images/photo-1_1photo-1.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture placeholder Ed Filled star Filled star Filled star Filled star Filled star 8 months ago Lekker bier en heerlijk geborreld. Tegenwoordig kan je ook door middel van een QR code bestellen waardoor er nog meer service is!, url='https://goo.gl/maps/rfZdF1NSonewfodr8'
		image Profile picture placeholder, url='https://orderli.com/images/photo-2_1photo-2.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture placeholder christianne Luijten Filled star Filled star Filled star Filled star Filled star 5 months ago Its really nice to sit near the window and look at people walking by. Nice beers too! I love how you can order drinks with your phone and they bring it really quick!  Love the employees as well!! And they are open untill late! :), url='https://goo.gl/maps/y3JmDAzF8AsU1Sr48'
		image Profile picture placeholder, url='https://orderli.com/images/photo-4_1photo-4.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture Izma R. Effendi Filled star Filled star Filled star Filled star Filled star 5 months ago A very nice bar in Delft. I love the atmosphere and the trendy look of the bar. You can even order from a qr code from your table.  A must go!, url='https://goo.gl/maps/8K7ydEYrrcH4a5SP7'
		image Profile picture, url='https://orderli.com/images/photo-5_1photo-5.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture Sietze Meijer Filled star Filled star Filled star Filled star Empty star 5 months ago Good food, much choice in drinks (including A cool non-alcoholic gin tonight which is pretty good considering),  great personnel. And do try their app to order your stuff!, url='https://goo.gl/maps/2x2L57GAoRGhRtEE7'
		image Profile picture, url='https://orderli.com/images/photo-6_1photo-6.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Empty star, url='https://orderli.com/images/google_star_empty_1google_star_empty.png'
		paragraph
		paragraph
		paragraph
	link Profile picture ana m Filled star Filled star Filled star Filled star Filled star 6 months ago Excellent breakfast, they have nice little qr code that opens an app for ordering your food, url='https://goo.gl/maps/kfRBQkBv5PenQPBPA'
		image Profile picture, url='https://orderli.com/images/photo-7_1photo-7.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture Jan Willem Foppen Filled star Filled star Filled star Filled star Filled star 8 months ago Ontzettend leuke gezellige relaxte sfeer met  lekker eten, goed geprijsd, mooie porties. Aardige attente bediening. Bestelling mbv n QR code. Meestal krijg je dan een of ander bestellingsformulier waar je van alles over jezelf moet invullen (naam, adres, etc), maar niet hier: scannen, bestellen, pats klaar. Simpel en snel. Heel goed!, url='https://goo.gl/maps/L9nPbPTK5ccvBQPK7'
		image Profile picture, url='https://orderli.com/images/photo-1_1photo-1.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture placeholder Ed Filled star Filled star Filled star Filled star Filled star 8 months ago Lekker bier en heerlijk geborreld. Tegenwoordig kan je ook door middel van een QR code bestellen waardoor er nog meer service is!, url='https://goo.gl/maps/rfZdF1NSonewfodr8'
		image Profile picture placeholder, url='https://orderli.com/images/photo-2_1photo-2.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture placeholder christianne Luijten Filled star Filled star Filled star Filled star Filled star 5 months ago Its really nice to sit near the window and look at people walking by. Nice beers too! I love how you can order drinks with your phone and they bring it really quick!  Love the employees as well!! And they are open untill late! :), url='https://goo.gl/maps/y3JmDAzF8AsU1Sr48'
		image Profile picture placeholder, url='https://orderli.com/images/photo-4_1photo-4.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture Izma R. Effendi Filled star Filled star Filled star Filled star Filled star 5 months ago A very nice bar in Delft. I love the atmosphere and the trendy look of the bar. You can even order from a qr code from your table.  A must go!, url='https://goo.gl/maps/8K7ydEYrrcH4a5SP7'
		image Profile picture, url='https://orderli.com/images/photo-5_1photo-5.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture Sietze Meijer Filled star Filled star Filled star Filled star Empty star 5 months ago Good food, much choice in drinks (including A cool non-alcoholic gin tonight which is pretty good considering),  great personnel. And do try their app to order your stuff!, url='https://goo.gl/maps/2x2L57GAoRGhRtEE7'
		image Profile picture, url='https://orderli.com/images/photo-6_1photo-6.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Empty star, url='https://orderli.com/images/google_star_empty_1google_star_empty.png'
		paragraph
		paragraph
		paragraph
	link Profile picture ana m Filled star Filled star Filled star Filled star Filled star 6 months ago Excellent breakfast, they have nice little qr code that opens an app for ordering your food, url='https://goo.gl/maps/kfRBQkBv5PenQPBPA'
		image Profile picture, url='https://orderli.com/images/photo-7_1photo-7.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture placeholder Veerle van der Stok Filled star Filled star Filled star Filled star Filled star 7 months ago ‘Verrassende’ manier van bestellen.  Lekkere cocktails!, url='https://goo.gl/maps/ANEkXPnoAXPupr6g6'
		image Profile picture placeholder, url='https://orderli.com/images/photo-14_1photo-14.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture placeholder André Schuurmans Filled star Filled star Filled star Filled star Filled star 2 months ago Nice beers and a neat way to order (through an app) that gets you lightning fast service and you don't have to worry about getting a bartender to notice you..., url='https://goo.gl/maps/pJY4j5oShr7LdNPJ6'
		image Profile picture placeholder, url='https://orderli.com/images/photo-16_1photo-16.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture Gernot Sümmermann Filled star Filled star Filled star Filled star Empty star 4 months ago Es ist ein nettes Lokal in der Mitte der Universitätsgebäude von Delft. Das Essen wird super schnell gebracht nachdem man per QR-Code / Webseite bestellen konnte.  Bezahlt wird aber weiterhin nach dem Essen. Trotzdem sehr bequemes System!, url='https://goo.gl/maps/5djZbo48iTsrhRjaA'
		image Profile picture, url='https://orderli.com/images/photo-17_1photo-17.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Empty star, url='https://orderli.com/images/google_star_empty_1google_star_empty.png'
		paragraph
		paragraph
		paragraph
	link Profile picture sjoukeschr Filled star Filled star Filled star Filled star Filled star 3 months ago leuke en hippe bar. Via de QR code konden we snel bestellen via onze smartphone.  We hebben niet lang moeten wachten op onze bestellingen, dit ging heel vlot. Er was heel wat keuze aan eten. Superhandig dus dat je meerdere dingen kon bestellen. Hier komen we zeker nog eens terug als we in de buurt zijn!, url='https://www.tripadvisor.nl/ShowUserReviews-g188626-d15211724-r742635278-De_Gist-Delft_South_Holland_Province.html?m=19905'
		image Profile picture, url='https://orderli.com/images/default-avatar-2020-37.jpg'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture 504pietv Filled star Filled star Filled star Filled star Filled star 4 months ago Met 7 personen onverwachts binnengelopen voor een borreltje. Deze bar heeft een aardige mogelijkheid je bestelling online te doen via het scannen van een code met je telefoon.  Bar is een beetje engels georiënteerd. Order, een paar glazen wijn en frisdrank en een bittergarnituur werd vlot na de elektronische bestelling, uitgeserveerd., url='https://www.tripadvisor.nl/ShowUserReviews-g188626-d15211724-r738618960-De_Gist-Delft_South_Holland_Province.html?m=19905'
		image Profile picture, url='https://orderli.com/images/default-avatar-2020-2.jpg'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture Els Huurman-Hogendoorn Filled star Filled star Filled star Filled star Filled star 6 months ago Gemakkelijk bestellen met QR code!  En de picanha is heerlijk! En het amandel ijs ook!, url='https://www.facebook.com/elsje.hogendoorn/posts/3134593039944662'
		image Profile picture, url='https://orderli.com/images/93679818_3626889247381703_5073042252788400128_n.jpg'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture placeholder Veerle van der Stok Filled star Filled star Filled star Filled star Filled star 7 months ago ‘Verrassende’ manier van bestellen.  Lekkere cocktails!, url='https://goo.gl/maps/ANEkXPnoAXPupr6g6'
		image Profile picture placeholder, url='https://orderli.com/images/photo-14_1photo-14.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture placeholder André Schuurmans Filled star Filled star Filled star Filled star Filled star 2 months ago Nice beers and a neat way to order (through an app) that gets you lightning fast service and you don't have to worry about getting a bartender to notice you..., url='https://goo.gl/maps/pJY4j5oShr7LdNPJ6'
		image Profile picture placeholder, url='https://orderli.com/images/photo-16_1photo-16.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture Gernot Sümmermann Filled star Filled star Filled star Filled star Empty star 4 months ago Es ist ein nettes Lokal in der Mitte der Universitätsgebäude von Delft. Das Essen wird super schnell gebracht nachdem man per QR-Code / Webseite bestellen konnte.  Bezahlt wird aber weiterhin nach dem Essen. Trotzdem sehr bequemes System!, url='https://goo.gl/maps/5djZbo48iTsrhRjaA'
		image Profile picture, url='https://orderli.com/images/photo-17_1photo-17.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Empty star, url='https://orderli.com/images/google_star_empty_1google_star_empty.png'
		paragraph
		paragraph
		paragraph
	link Profile picture sjoukeschr Filled star Filled star Filled star Filled star Filled star 3 months ago leuke en hippe bar. Via de QR code konden we snel bestellen via onze smartphone.  We hebben niet lang moeten wachten op onze bestellingen, dit ging heel vlot. Er was heel wat keuze aan eten. Superhandig dus dat je meerdere dingen kon bestellen. Hier komen we zeker nog eens terug als we in de buurt zijn!, url='https://www.tripadvisor.nl/ShowUserReviews-g188626-d15211724-r742635278-De_Gist-Delft_South_Holland_Province.html?m=19905'
		image Profile picture, url='https://orderli.com/images/default-avatar-2020-37.jpg'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture 504pietv Filled star Filled star Filled star Filled star Filled star 4 months ago Met 7 personen onverwachts binnengelopen voor een borreltje. Deze bar heeft een aardige mogelijkheid je bestelling online te doen via het scannen van een code met je telefoon.  Bar is een beetje engels georiënteerd. Order, een paar glazen wijn en frisdrank en een bittergarnituur werd vlot na de elektronische bestelling, uitgeserveerd., url='https://www.tripadvisor.nl/ShowUserReviews-g188626-d15211724-r738618960-De_Gist-Delft_South_Holland_Province.html?m=19905'
		image Profile picture, url='https://orderli.com/images/default-avatar-2020-2.jpg'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	link Profile picture Els Huurman-Hogendoorn Filled star Filled star Filled star Filled star Filled star 6 months ago Gemakkelijk bestellen met QR code!  En de picanha is heerlijk! En het amandel ijs ook!, url='https://www.facebook.com/elsje.hogendoorn/posts/3134593039944662'
		image Profile picture, url='https://orderli.com/images/93679818_3626889247381703_5073042252788400128_n.jpg'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		image Filled star, url='https://orderli.com/images/google_star_1google_star.png'
		paragraph
		paragraph
		paragraph
	heading Don't leave guests waiting.
	list
		listitem
			image Checkmark, url='https://orderli.com/images/checkmark.svg'
			StaticText No hidden costs.
		listitem
			image Checkmark, url='https://orderli.com/images/checkmark.svg'
			StaticText Easy installation.
		listitem
			image Checkmark, url='https://orderli.com/images/checkmark.svg'
			StaticText Can be cancelled monthly.
	Iframe Form 0
		RootWebArea, url='about:blank'
			LabelText
				StaticText Naam
				StaticText *
			[c15] textbox Naam*, center=(1065,5756), required
			LabelText
				StaticText Naam onderneming
				StaticText *
			[c22] textbox Naam onderneming*, center=(1065,5838), required
			LabelText
				StaticText E-mail
				StaticText *
			[c29] textbox E-mail*, center=(1065,5920), required
			LabelText
				StaticText Telefoonnummer
				StaticText *
			[c36] textbox Telefoonnummer*, center=(1065,6002), required
			[c46] button Verzenden, center=(968,6076)
			[ca] Iframe hubspot-forms-viral-iframe, center=(1065,6160)
				RootWebArea Virale links gebruikersinterface, url='https://app.hubspot.com/embedded-viral-link/forms?lang=nl&portalId=8545281&hubs_id=forms-branding-control&hubs_source=orderli.com&intent=marketingFreeForms'
					[ca36] link Creëer je eigen gratis formulieren om leads te genereren op je website., center=(1065,6160), url='https://app.hubspot.com/signup-hubspot/marketing?uuid=82ad1b71-2427-477f-a58c-74ed2cf31a7a&utm_medium=virality&utm_campaign=hubspot-forms-virality&intent=marketingFreeForms&hubs_id=forms-branding-control&hubs_source=orderli.com'
						strong
	StaticText Or schedule a demo call
	link Schedule call, url='https://orderli.com/en/#'
	image, url='https://orderli.com/images/icons8-shop-1.svg'
	StaticText Tell us about your business
	image, url='https://orderli.com/images/icons8-restaurant_menu-1.svg'
	StaticText Add your menu with our editor
	image, url='https://orderli.com/images/simple-arrow.svg'
	image, url='https://orderli.com/images/simple-arrow-under.svg'
	image, url='https://orderli.com/images/icons8-qr_code-1.svg'
	StaticText Link the QR codes to your tables
	image Orderli logo, url='https://orderli.com/images/Orderli-logo-oranje.svg'
	link +31 85 303 07 23, url='tel:+31853030723'
	button Globe icon English, expanded=False, hasPopup='menu'
		image Globe icon, url='https://orderli.com/images/svgexport-14.svg'
	heading For businesses
	link Integrations, url='https://orderli.com/en/integrations.html'
	link Pricing, url='https://orderli.com/en/pricing.html'
	link Demo, url='https://orderli.com/en/demo.html'
	heading Orderli for
	link Bars, url='https://orderli.com/en/bars.html'
	link Hotels, url='https://orderli.com/en/hotels.html'
	link Festivals, url='https://orderli.com/en/festivals.html'
	link Restaurants, url='https://orderli.com/en/restaurants.html'
	link Everyone, url='https://orderli.com/en/'
	heading Integrations
	link Lightspeed, url='https://orderli.com/en/integrations/lightspeed.html'
	link unTill, url='https://orderli.com/en/integrations/untill.html'
	link Vectron, url='https://orderli.com/en/integrations/vectron.html'
	link MplusKASSA, url='https://orderli.com/en/integrations/mpluskassa.html'
	link Index, url='https://orderli.com/en/integrations/index-pos.html'
	heading Legal
	link Privacy Policy, url='https://orderli.com/privacypolicy.pdf'
	link Terms of Service, url='https://orderli.com/algemene-voorwaarden.pdf'
	heading Company
	link Our story, url='https://orderli.com/en/about.html'
	link System status, url='https://status.orderli.com/'
	link Blog, url='http://blog.orderli.com/'
	link Careers 4, url='https://jobs.orderli.com/'
	link Contact, url='https://orderli.com/en/contact.html'
	link Voedselverspilling, url='https://orderli.com/foodwaste.html'
	StaticText Copyright © 2024 Orderli B.V.
	StaticText Made with 🎉 in Delft & Leeuwarden.
	link Instagram logo, url='https://www.instagram.com/orderli.nl/'
		image Instagram logo, url='https://orderli.com/images/icons8-instagram.svg'
	link Twitter logo, url='https://twitter.com/OrderliNL'
		image Twitter logo, url='https://orderli.com/images/icons8-twitter.svg'
	link Facebook logo, url='https://www.facebook.com/pages/category/Hospitality-Service/Orderli-102253861313384/'
		image Facebook logo, url='https://orderli.com/images/icons8-facebook.svg'
	link LinkedIn logo, url='https://www.linkedin.com/company/orderli'
		image LinkedIn logo, url='https://orderli.com/images/icons8-linkedin.svg'
	[g] Iframe trengo-widget-launcher, center=(1870,1030), title=trengo-widget-launcher
		RootWebArea, url='about:blank'
```
</details>



```
RootWebArea Integraties, focused, url='https://orderli.com/en/integrations'
	banner
		link Orderli logo, url='https://orderli.com/en/'
			[57] image Orderli logo, center=(440,32), url='https://orderli.com/images/Orderli-logo-oranje.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[91] button Orderli for, center=(575,33), expanded=False, hasPopup='menu'
			[126] link Integrations, center=(695,33), url='https://orderli.com/en/integrations.html'
			[127] link Pricing, center=(788,33), url='https://orderli.com/en/pricing.html'
			[128] link Demo, center=(858,33), url='https://orderli.com/en/demo.html'
			[129] link About us, center=(935,33), url='https://orderli.com/en/about.html'
			[130] link Contact, center=(1020,33), url='https://orderli.com/en/contact.html'
			[146] link Log in, center=(1370,33), url='https://admin.orderli.com/login'
		[151] link Try for free, center=(1470,32), url='https://orderli.com/en/integrations#'
	heading Integrate with your POS.
	paragraph
		StaticText We can push orders directly to the POS using our integration. This way your staff will receive a receipt that they are already used to working with.
	heading POS integrations
	[165] link Lightspeed K-series logo Lightspeed K NEW, center=(525,672), inner_text=Lightspeed K
NEW, url='https://orderli.com/en/integrations/lightspeed-k-series.html'
		image Lightspeed K-series logo, url='https://orderli.com/images/lightspeed-k.svg'
	[170] link Lightspeed L-series logo Lightspeed, center=(815,672), inner_text=Lightspeed, url='https://orderli.com/en/integrations/lightspeed.html'
		image Lightspeed L-series logo, url='https://orderli.com/images/lightspeed.svg'
	[175] link unTill logo unTill, center=(1105,672), inner_text=unTill, url='https://orderli.com/en/integrations/untill.html'
		image unTill logo, url='https://orderli.com/images/logo-untill.png'
	[180] link Vectron logo Vectron, center=(1395,672), inner_text=Vectron, url='https://orderli.com/en/integrations/vectron.html'
		image Vectron logo, url='https://orderli.com/images/logo-vectron.png'
	[185] link Mpluskassa logo MplusKASSA, center=(525,964), inner_text=MplusKASSA, url='https://orderli.com/en/integrations/mpluskassa.html'
		image Mpluskassa logo, url='https://orderli.com/images/logo-mpluskassa.png'
	[191] link Trivec logo Trivec NEW, center=(815,964), inner_text=Trivec
NEW, url='https://orderli.com/en/integrations/trivec.html'
		image Trivec logo, url='https://orderli.com/images/trivec-logo.svg'
	[197] link Square logo Matrix NEW, center=(1105,964), inner_text=Matrix
NEW, url='https://orderli.com/en/integrations#'
		image Square logo, url='https://orderli.com/images/logo-matrix.png'
	[203] link Toast logo Povis NEW, center=(1395,964), inner_text=Povis
NEW, url='https://orderli.com/en/integrations#'
		image Toast logo, url='https://orderli.com/images/logo-povis.png'
	link Micas logo Micas, url='https://orderli.com/en/integrations/micas.html'
		image Micas logo, url='https://orderli.com/images/logo-micas.png'
	link Orderli webclip logo Orderli Standalone, url='https://orderli.com/en/integrations#'
		image Orderli webclip logo, url='https://orderli.com/images/ios-webclip-black.png'
	link Webhook API, url='https://orderli.com/en/integrations#'
		image, url='https://orderli.com/images/settings-svgrepo-com.svg'
	heading Receipt printers
	link Epson, url='https://orderli.com/en/integrations#'
		image, url='https://orderli.com/images/epson.svg'
	link Citizen logo Citizen, url='https://orderli.com/en/integrations#'
		image Citizen logo, url='https://orderli.com/images/Citizen_logo.svg-p-500.png'
	link Star, url='https://orderli.com/en/integrations#'
		image, url='https://orderli.com/images/star.svg'
	heading Payments
	link CCV logo CCV, url='https://orderli.com/en/integrations#'
		image CCV logo, url='https://orderli.com/images/ccv-logo-p-500.png'
	link Mollie logo Mollie, url='https://orderli.com/en/integrations#'
		image Mollie logo, url='https://orderli.com/images/Mollie-logo-dark.svg'
	link Adyen logo Adyen, url='https://orderli.com/en/integrations#'
		image Adyen logo, url='https://orderli.com/images/1024px-Adyen_Corporate_Logo.svg.png'
	link Stripe logo Stripe, url='https://orderli.com/en/integrations#'
		image Stripe logo, url='https://orderli.com/images/Stripe-wordmark---blurple.svg'
	link Sumup logo SumUp, url='https://orderli.com/en/integrations#'
		image Sumup logo, url='https://orderli.com/images/Sumup_logo.svg'
	link Bitpay logo BitPay NEW, url='https://orderli.com/en/integrations#'
		image Bitpay logo, url='https://orderli.com/images/bitpay.svg'
	heading Other
	link Mailchimp logo Mailchimp, url='https://orderli.com/en/integrations#'
		image Mailchimp logo, url='https://orderli.com/images/Mailchimp_Logo-Vertical_Black.png'
	link Google Analytics logo Google Analytics, url='https://orderli.com/en/integrations#'
		image Google Analytics logo, url='https://orderli.com/images/google_analytics-official.svg'
	link Google logo Google Reviews NEW, url='https://orderli.com/en/integrations#'
		image Google logo, url='https://orderli.com/images/google_g_icon_download.png'
	link Facebook logo Facebook Pixel, url='https://orderli.com/en/integrations#'
		image Facebook logo, url='https://orderli.com/images/f_logo_RGB-Grey_512-p-500.png'
	link Gify logo Gifty NEW, url='https://orderli.com/en/integrations#'
		image Gify logo, url='https://orderli.com/images/logo-1.svg'
	link Untappd logo Untappd NEW, url='https://orderli.com/en/integrations#'
		image Untappd logo, url='https://orderli.com/images/logo-untappd.png'
	heading Frequently Asked Questions
	paragraph
		StaticText Didn't find an answer to your question? Please
		link contact, url='https://orderli.com/en/contact.html'
		StaticText us!
		strong
	heading Can I use Orderli if my POS system is not listed?
		strong
	image Plus icon, url='https://orderli.com/images/svgexport-10.svg'
	paragraph
		link Contact, url='https://orderli.com/en/contact.html'
		StaticText us and ask for the possibilities.
	heading Can I use Orderli if my POS doesn't support integrations?
		strong
	image Plus icon, url='https://orderli.com/images/svgexport-10.svg'
	paragraph
		StaticText No problem. We will provide a small tablet to hang next to your POS, which will show all incoming orders. Staff will need to manually input these into your POS — just like they are already doing now.
	heading How does the integration with CCV work?
		strong
	image Plus icon, url='https://orderli.com/images/svgexport-10.svg'
	paragraph
		StaticText You can request the link with CCV yourself. You will then receive a code from CCV, which you can enter to link it to Orderli.
	heading Don't leave guests waiting
	link Try Orderli for free, url='https://orderli.com/en/integrations#'
	list
		listitem
			image, url='https://uploads-ssl.webflow.com/5dfcb4c9305f514441dd2294/5e00004adcc8adb8cf6ef413_checkmark.svg'
			StaticText No hidden costs
		listitem
			image, url='https://uploads-ssl.webflow.com/5dfcb4c9305f514441dd2294/5e00004adcc8adb8cf6ef413_checkmark.svg'
			StaticText Can be cancelled monthly
		listitem
			image, url='https://uploads-ssl.webflow.com/5dfcb4c9305f514441dd2294/5e00004adcc8adb8cf6ef413_checkmark.svg'
			StaticText Easy installation
	image, url='https://orderli.com/images/icons8-shop-1.svg'
	StaticText Tell us about your business
	image, url='https://orderli.com/images/icons8-restaurant_menu-1.svg'
	StaticText Add your menu with our editor
	image, url='https://orderli.com/images/simple-arrow.svg'
	image, url='https://orderli.com/images/simple-arrow-under.svg'
	image, url='https://orderli.com/images/icons8-qr_code-1.svg'
	StaticText Link the QR codes to your tables
	image Orderli logo, url='https://orderli.com/images/Orderli-logo-oranje.svg'
	link +31 85 303 07 23, url='tel:+31853030723'
	button Globe icon English, expanded=False, hasPopup='menu'
		image Globe icon, url='https://orderli.com/images/svgexport-14.svg'
	heading For businesses
	link Integrations, url='https://orderli.com/en/integrations.html'
	link Pricing, url='https://orderli.com/en/pricing.html'
	link Demo, url='https://orderli.com/en/demo.html'
	heading Orderli for
	link Bars, url='https://orderli.com/en/bars.html'
	link Hotels, url='https://orderli.com/en/hotels.html'
	link Festivals, url='https://orderli.com/en/festivals.html'
	link Restaurants, url='https://orderli.com/en/restaurants.html'
	link Everyone, url='https://orderli.com/en/'
	heading Integrations
	link Lightspeed, url='https://orderli.com/en/integrations/lightspeed.html'
	link unTill, url='https://orderli.com/en/integrations/untill.html'
	link Vectron, url='https://orderli.com/en/integrations/vectron.html'
	link MplusKASSA, url='https://orderli.com/en/integrations/mpluskassa.html'
	link Index, url='https://orderli.com/en/integrations/index-pos.html'
	heading Legal
	link Privacy Policy, url='https://orderli.com/privacypolicy.pdf'
	link Terms of Service, url='https://orderli.com/algemene-voorwaarden.pdf'
	heading Company
	link Our story, url='https://orderli.com/en/about.html'
	link Blog, url='http://blog.orderli.com/'
	link Careers 4, url='https://jobs.orderli.com/'
	link Contact, url='https://orderli.com/en/contact.html'
	link Voedselverspilling, url='https://orderli.com/foodwaste.html'
	StaticText Copyright © 2024 Orderli B.V.
	StaticText Made with 🎉 in Delft & Leeuwarden.
	link Instagram logo, url='https://www.instagram.com/orderli.nl/'
		image Instagram logo, url='https://orderli.com/images/icons8-instagram.svg'
	link Twitter logo, url='https://twitter.com/OrderliNL'
		image Twitter logo, url='https://orderli.com/images/icons8-twitter.svg'
	link Facebook logo, url='https://www.facebook.com/pages/category/Hospitality-Service/Orderli-102253861313384/'
		image Facebook logo, url='https://orderli.com/images/icons8-facebook.svg'
	link LinkedIn logo, url='https://www.linkedin.com/company/orderli'
		image LinkedIn logo, url='https://orderli.com/images/icons8-linkedin.svg'
	[f] Iframe trengo-widget-launcher, center=(1870,1030), title=trengo-widget-launcher
		RootWebArea, url='about:blank'
```
</details>

**Reasoning for action:** Clicking on the Integrations link is a necessary first step toward fulfilling the user story. By doing this, I will access the correct section of the Orderli website where the available integrations are listed, including the specific integration the restaurant owner is interested in. This aligns with the user's goal of exploring integration options.

**Action:** click(130) # Click on the Integrations link to explore integration options.

**Change Description:** After clicking the 'Integrations' link, the browser navigated to a new page that provides information on various POS and payment system integrations available with Orderli, and the page title changed to 'Integraties' as reflected in the new URL 'https://orderli.com/en/integrations'. Additionally, the content now includes headings and links specific to different integration partners and features.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://orderli.com/en/integrations

https://orderli.com/en/integrations/lightspeed-k-series

**Content (before/after):** 

```
RootWebArea Integraties, focused, url='https://orderli.com/en/integrations'
	banner
		link Orderli logo, url='https://orderli.com/en/'
			[57] image Orderli logo, center=(440,32), url='https://orderli.com/images/Orderli-logo-oranje.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[91] button Orderli for, center=(575,33), expanded=False, hasPopup='menu'
			[126] link Integrations, center=(695,33), url='https://orderli.com/en/integrations.html'
			[127] link Pricing, center=(788,33), url='https://orderli.com/en/pricing.html'
			[128] link Demo, center=(858,33), url='https://orderli.com/en/demo.html'
			[129] link About us, center=(935,33), url='https://orderli.com/en/about.html'
			[130] link Contact, center=(1020,33), url='https://orderli.com/en/contact.html'
			[146] link Log in, center=(1370,33), url='https://admin.orderli.com/login'
		[151] link Try for free, center=(1470,32), url='https://orderli.com/en/integrations#'
	heading Integrate with your POS.
	paragraph
		StaticText We can push orders directly to the POS using our integration. This way your staff will receive a receipt that they are already used to working with.
	heading POS integrations
	[165] link Lightspeed K-series logo Lightspeed K NEW, center=(525,672), inner_text=Lightspeed K
NEW, url='https://orderli.com/en/integrations/lightspeed-k-series.html'
		image Lightspeed K-series logo, url='https://orderli.com/images/lightspeed-k.svg'
	[170] link Lightspeed L-series logo Lightspeed, center=(815,672), inner_text=Lightspeed, url='https://orderli.com/en/integrations/lightspeed.html'
		image Lightspeed L-series logo, url='https://orderli.com/images/lightspeed.svg'
	[175] link unTill logo unTill, center=(1105,672), inner_text=unTill, url='https://orderli.com/en/integrations/untill.html'
		image unTill logo, url='https://orderli.com/images/logo-untill.png'
	[180] link Vectron logo Vectron, center=(1395,672), inner_text=Vectron, url='https://orderli.com/en/integrations/vectron.html'
		image Vectron logo, url='https://orderli.com/images/logo-vectron.png'
	[185] link Mpluskassa logo MplusKASSA, center=(525,964), inner_text=MplusKASSA, url='https://orderli.com/en/integrations/mpluskassa.html'
		image Mpluskassa logo, url='https://orderli.com/images/logo-mpluskassa.png'
	[191] link Trivec logo Trivec NEW, center=(815,964), inner_text=Trivec
NEW, url='https://orderli.com/en/integrations/trivec.html'
		image Trivec logo, url='https://orderli.com/images/trivec-logo.svg'
	[197] link Square logo Matrix NEW, center=(1105,964), inner_text=Matrix
NEW, url='https://orderli.com/en/integrations#'
		image Square logo, url='https://orderli.com/images/logo-matrix.png'
	[203] link Toast logo Povis NEW, center=(1395,964), inner_text=Povis
NEW, url='https://orderli.com/en/integrations#'
		image Toast logo, url='https://orderli.com/images/logo-povis.png'
	link Micas logo Micas, url='https://orderli.com/en/integrations/micas.html'
		image Micas logo, url='https://orderli.com/images/logo-micas.png'
	link Orderli webclip logo Orderli Standalone, url='https://orderli.com/en/integrations#'
		image Orderli webclip logo, url='https://orderli.com/images/ios-webclip-black.png'
	link Webhook API, url='https://orderli.com/en/integrations#'
		image, url='https://orderli.com/images/settings-svgrepo-com.svg'
	heading Receipt printers
	link Epson, url='https://orderli.com/en/integrations#'
		image, url='https://orderli.com/images/epson.svg'
	link Citizen logo Citizen, url='https://orderli.com/en/integrations#'
		image Citizen logo, url='https://orderli.com/images/Citizen_logo.svg-p-500.png'
	link Star, url='https://orderli.com/en/integrations#'
		image, url='https://orderli.com/images/star.svg'
	heading Payments
	link CCV logo CCV, url='https://orderli.com/en/integrations#'
		image CCV logo, url='https://orderli.com/images/ccv-logo-p-500.png'
	link Mollie logo Mollie, url='https://orderli.com/en/integrations#'
		image Mollie logo, url='https://orderli.com/images/Mollie-logo-dark.svg'
	link Adyen logo Adyen, url='https://orderli.com/en/integrations#'
		image Adyen logo, url='https://orderli.com/images/1024px-Adyen_Corporate_Logo.svg.png'
	link Stripe logo Stripe, url='https://orderli.com/en/integrations#'
		image Stripe logo, url='https://orderli.com/images/Stripe-wordmark---blurple.svg'
	link Sumup logo SumUp, url='https://orderli.com/en/integrations#'
		image Sumup logo, url='https://orderli.com/images/Sumup_logo.svg'
	link Bitpay logo BitPay NEW, url='https://orderli.com/en/integrations#'
		image Bitpay logo, url='https://orderli.com/images/bitpay.svg'
	heading Other
	link Mailchimp logo Mailchimp, url='https://orderli.com/en/integrations#'
		image Mailchimp logo, url='https://orderli.com/images/Mailchimp_Logo-Vertical_Black.png'
	link Google Analytics logo Google Analytics, url='https://orderli.com/en/integrations#'
		image Google Analytics logo, url='https://orderli.com/images/google_analytics-official.svg'
	link Google logo Google Reviews NEW, url='https://orderli.com/en/integrations#'
		image Google logo, url='https://orderli.com/images/google_g_icon_download.png'
	link Facebook logo Facebook Pixel, url='https://orderli.com/en/integrations#'
		image Facebook logo, url='https://orderli.com/images/f_logo_RGB-Grey_512-p-500.png'
	link Gify logo Gifty NEW, url='https://orderli.com/en/integrations#'
		image Gify logo, url='https://orderli.com/images/logo-1.svg'
	link Untappd logo Untappd NEW, url='https://orderli.com/en/integrations#'
		image Untappd logo, url='https://orderli.com/images/logo-untappd.png'
	heading Frequently Asked Questions
	paragraph
		StaticText Didn't find an answer to your question? Please
		link contact, url='https://orderli.com/en/contact.html'
		StaticText us!
		strong
	heading Can I use Orderli if my POS system is not listed?
		strong
	image Plus icon, url='https://orderli.com/images/svgexport-10.svg'
	paragraph
		link Contact, url='https://orderli.com/en/contact.html'
		StaticText us and ask for the possibilities.
	heading Can I use Orderli if my POS doesn't support integrations?
		strong
	image Plus icon, url='https://orderli.com/images/svgexport-10.svg'
	paragraph
		StaticText No problem. We will provide a small tablet to hang next to your POS, which will show all incoming orders. Staff will need to manually input these into your POS — just like they are already doing now.
	heading How does the integration with CCV work?
		strong
	image Plus icon, url='https://orderli.com/images/svgexport-10.svg'
	paragraph
		StaticText You can request the link with CCV yourself. You will then receive a code from CCV, which you can enter to link it to Orderli.
	heading Don't leave guests waiting
	link Try Orderli for free, url='https://orderli.com/en/integrations#'
	list
		listitem
			image, url='https://uploads-ssl.webflow.com/5dfcb4c9305f514441dd2294/5e00004adcc8adb8cf6ef413_checkmark.svg'
			StaticText No hidden costs
		listitem
			image, url='https://uploads-ssl.webflow.com/5dfcb4c9305f514441dd2294/5e00004adcc8adb8cf6ef413_checkmark.svg'
			StaticText Can be cancelled monthly
		listitem
			image, url='https://uploads-ssl.webflow.com/5dfcb4c9305f514441dd2294/5e00004adcc8adb8cf6ef413_checkmark.svg'
			StaticText Easy installation
	image, url='https://orderli.com/images/icons8-shop-1.svg'
	StaticText Tell us about your business
	image, url='https://orderli.com/images/icons8-restaurant_menu-1.svg'
	StaticText Add your menu with our editor
	image, url='https://orderli.com/images/simple-arrow.svg'
	image, url='https://orderli.com/images/simple-arrow-under.svg'
	image, url='https://orderli.com/images/icons8-qr_code-1.svg'
	StaticText Link the QR codes to your tables
	image Orderli logo, url='https://orderli.com/images/Orderli-logo-oranje.svg'
	link +31 85 303 07 23, url='tel:+31853030723'
	button Globe icon English, expanded=False, hasPopup='menu'
		image Globe icon, url='https://orderli.com/images/svgexport-14.svg'
	heading For businesses
	link Integrations, url='https://orderli.com/en/integrations.html'
	link Pricing, url='https://orderli.com/en/pricing.html'
	link Demo, url='https://orderli.com/en/demo.html'
	heading Orderli for
	link Bars, url='https://orderli.com/en/bars.html'
	link Hotels, url='https://orderli.com/en/hotels.html'
	link Festivals, url='https://orderli.com/en/festivals.html'
	link Restaurants, url='https://orderli.com/en/restaurants.html'
	link Everyone, url='https://orderli.com/en/'
	heading Integrations
	link Lightspeed, url='https://orderli.com/en/integrations/lightspeed.html'
	link unTill, url='https://orderli.com/en/integrations/untill.html'
	link Vectron, url='https://orderli.com/en/integrations/vectron.html'
	link MplusKASSA, url='https://orderli.com/en/integrations/mpluskassa.html'
	link Index, url='https://orderli.com/en/integrations/index-pos.html'
	heading Legal
	link Privacy Policy, url='https://orderli.com/privacypolicy.pdf'
	link Terms of Service, url='https://orderli.com/algemene-voorwaarden.pdf'
	heading Company
	link Our story, url='https://orderli.com/en/about.html'
	link Blog, url='http://blog.orderli.com/'
	link Careers 4, url='https://jobs.orderli.com/'
	link Contact, url='https://orderli.com/en/contact.html'
	link Voedselverspilling, url='https://orderli.com/foodwaste.html'
	StaticText Copyright © 2024 Orderli B.V.
	StaticText Made with 🎉 in Delft & Leeuwarden.
	link Instagram logo, url='https://www.instagram.com/orderli.nl/'
		image Instagram logo, url='https://orderli.com/images/icons8-instagram.svg'
	link Twitter logo, url='https://twitter.com/OrderliNL'
		image Twitter logo, url='https://orderli.com/images/icons8-twitter.svg'
	link Facebook logo, url='https://www.facebook.com/pages/category/Hospitality-Service/Orderli-102253861313384/'
		image Facebook logo, url='https://orderli.com/images/icons8-facebook.svg'
	link LinkedIn logo, url='https://www.linkedin.com/company/orderli'
		image LinkedIn logo, url='https://orderli.com/images/icons8-linkedin.svg'
	[f] Iframe trengo-widget-launcher, center=(1870,1030), title=trengo-widget-launcher
		RootWebArea, url='about:blank'
```
</details>



```
RootWebArea Lightspeed K-series QR ordering - Mobile Ordering for Lightspeed, focused, url='https://orderli.com/en/integrations/lightspeed-k-series'
	banner
		link Orderli logo, url='https://orderli.com/en/'
			[56] image Orderli logo, center=(440,32), url='https://orderli.com/images/Orderli-logo-oranje.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[90] button Orderli for, center=(575,33), expanded=False, hasPopup='menu'
			[125] link Integrations, center=(695,33), url='https://orderli.com/en/integrations.html'
			[126] link Pricing, center=(788,33), url='https://orderli.com/en/pricing.html'
			[127] link Demo, center=(858,33), url='https://orderli.com/en/demo.html'
			[128] link About us, center=(935,33), url='https://orderli.com/en/about.html'
			[129] link Contact, center=(1020,33), url='https://orderli.com/en/contact.html'
			[145] link Log in, center=(1370,33), url='https://admin.orderli.com/login'
		[150] link Try for free, center=(1470,32), url='https://orderli.com/en/integrations/lightspeed-k-series#'
	image Lightspeed K-series logo, url='https://orderli.com/images/lightspeed-k.svg'
	heading QR ordering for Lightspeed K.
	paragraph
		StaticText Connect Orderli QR ordering directly with Lightspeed K-Series. All orders are sent to the POS. Within
		strong
			StaticText one minute connected
		StaticText to Lightspeed!
	[163] link Try Orderli for Free, center=(960,586), url='https://orderli.com/en/integrations/lightspeed-k-series#'
	heading Trusted by hundreds of businesses, including:
	image Brouwerij Troost logo, url='https://orderli.com/images/troost-logo---min.jpg'
	image Van der Valk logo, url='https://orderli.com/images/van-der-valk-logo---min.png'
	image Avocado show logo, url='https://orderli.com/images/The-Avocado-Show-Logo-Black.svg'
	image Schiphol logo, url='https://orderli.com/images/schiphol.svg'
	image Brasa Purmerend logo, url='https://orderli.com/images/brasa-black---min.png'
	image Bierfabriek logo, url='https://orderli.com/images/bierfabriek-simple.svg'
	heading The capabilities of Orderli + Lightspeed K.
	image Green checkmark, url='https://orderli.com/images/5cd24ca168db6560f9e01747_check.svg'
	heading Pay afterwards
	image Green checkmark, url='https://orderli.com/images/5cd24ca168db6560f9e01747_check.svg'
	heading Stock management integration
	image Green checkmark, url='https://orderli.com/images/5cd24ca168db6560f9e01747_check.svg'
	heading Automatically integrate options
	image Green checkmark, url='https://orderli.com/images/5cd24ca168db6560f9e01747_check.svg'
	heading Integrate deals
	heading Don't leave guests waiting
	link Try Orderli for Free, url='https://orderli.com/en/integrations/lightspeed-k-series#'
	list
		listitem
			image, url='https://uploads-ssl.webflow.com/5dfcb4c9305f514441dd2294/5e00004adcc8adb8cf6ef413_checkmark.svg'
			StaticText No hidden costs
		listitem
			image, url='https://uploads-ssl.webflow.com/5dfcb4c9305f514441dd2294/5e00004adcc8adb8cf6ef413_checkmark.svg'
			StaticText Can be cancelled monthly
		listitem
			image, url='https://uploads-ssl.webflow.com/5dfcb4c9305f514441dd2294/5e00004adcc8adb8cf6ef413_checkmark.svg'
			StaticText Easy installation
	image, url='https://orderli.com/images/icons8-shop-1.svg'
	StaticText Tell us about your business
	image, url='https://orderli.com/images/icons8-restaurant_menu-1.svg'
	StaticText Add your menu in our editor
	image, url='https://orderli.com/images/simple-arrow.svg'
	image, url='https://orderli.com/images/simple-arrow-under.svg'
	image, url='https://orderli.com/images/icons8-qr_code-1.svg'
	StaticText Link the QR codes to your tables
	image Orderli logo, url='https://orderli.com/images/Orderli-logo-oranje.svg'
	link +31 85 303 07 23, url='tel:+31853030723'
	button Globe icon English, expanded=False, hasPopup='menu'
		image Globe icon, url='https://orderli.com/images/svgexport-14.svg'
	heading For businesses
	link Integrations, url='https://orderli.com/en/integrations.html'
	link Pricing, url='https://orderli.com/en/pricing.html'
	link Demo, url='https://orderli.com/en/demo.html'
	heading Orderli for
	link Bars, url='https://orderli.com/en/bars.html'
	link Hotels, url='https://orderli.com/en/hotels.html'
	link Festivals, url='https://orderli.com/en/festivals.html'
	link Restaurants, url='https://orderli.com/en/restaurants.html'
	link Everyone, url='https://orderli.com/en/'
	heading Integrations
	link Lightspeed, url='https://orderli.com/en/integrations/lightspeed.html'
	link unTill, url='https://orderli.com/en/integrations/untill.html'
	link Vectron, url='https://orderli.com/en/integrations/vectron.html'
	link MplusKASSA, url='https://orderli.com/en/integrations/mpluskassa.html'
	link Index, url='https://orderli.com/en/integrations/index-pos.html'
	heading Legal
	link Privacy Policy, url='https://orderli.com/privacypolicy.pdf'
	link Terms of Service, url='https://orderli.com/algemene-voorwaarden.pdf'
	heading Company
	link Our story, url='https://orderli.com/en/about.html'
	link Blog, url='http://blog.orderli.com/'
	link Careers 4, url='https://jobs.orderli.com/'
	link Contact, url='https://orderli.com/en/contact.html'
	link Voedselverspilling, url='https://orderli.com/foodwaste.html'
	StaticText Copyright © 2024 Orderli B.V.
	StaticText Made with 🎉 in Delft & Leeuwarden.
	link Instagram logo, url='https://www.instagram.com/orderli.nl/'
		image Instagram logo, url='https://orderli.com/images/icons8-instagram.svg'
	link Twitter logo, url='https://twitter.com/OrderliNL'
		image Twitter logo, url='https://orderli.com/images/icons8-twitter.svg'
	link Facebook logo, url='https://www.facebook.com/pages/category/Hospitality-Service/Orderli-102253861313384/'
		image Facebook logo, url='https://orderli.com/images/icons8-facebook.svg'
	link LinkedIn logo, url='https://www.linkedin.com/company/orderli'
		image LinkedIn logo, url='https://orderli.com/images/icons8-linkedin.svg'
	[d] Iframe trengo-widget-launcher, center=(1870,1030), title=trengo-widget-launcher
		RootWebArea, url='about:blank'
```
</details>

**Reasoning for action:** I identified the link for the Lightspeed K integration as it is a specific option within the integrations section that the user story instructed me to explore. By clicking this link, I will be directed to a dedicated page that likely contains comprehensive information about how Lightspeed K can enhance the ordering system, thereby helping the restaurant owner achieve their goal of finding the right tools.

**Action:** click(165) # Click on the Lightspeed K integration link to explore its details.

**Change Description:** The browser navigated to the Lightspeed K-series integration page, changing the URL to 'https://orderli.com/en/integrations/lightspeed-k-series' and updating the content to display information about QR ordering for Lightspeed K, including specific features and trusted businesses associated with it.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://orderli.com/en/integrations/lightspeed-k-series

https://orderli.com/en/integrations/lightspeed-k-series

**Content (before/after):** 

```
RootWebArea Lightspeed K-series QR ordering - Mobile Ordering for Lightspeed, focused, url='https://orderli.com/en/integrations/lightspeed-k-series'
	banner
		link Orderli logo, url='https://orderli.com/en/'
			[56] image Orderli logo, center=(440,32), url='https://orderli.com/images/Orderli-logo-oranje.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[90] button Orderli for, center=(575,33), expanded=False, hasPopup='menu'
			[125] link Integrations, center=(695,33), url='https://orderli.com/en/integrations.html'
			[126] link Pricing, center=(788,33), url='https://orderli.com/en/pricing.html'
			[127] link Demo, center=(858,33), url='https://orderli.com/en/demo.html'
			[128] link About us, center=(935,33), url='https://orderli.com/en/about.html'
			[129] link Contact, center=(1020,33), url='https://orderli.com/en/contact.html'
			[145] link Log in, center=(1370,33), url='https://admin.orderli.com/login'
		[150] link Try for free, center=(1470,32), url='https://orderli.com/en/integrations/lightspeed-k-series#'
	image Lightspeed K-series logo, url='https://orderli.com/images/lightspeed-k.svg'
	heading QR ordering for Lightspeed K.
	paragraph
		StaticText Connect Orderli QR ordering directly with Lightspeed K-Series. All orders are sent to the POS. Within
		strong
			StaticText one minute connected
		StaticText to Lightspeed!
	[163] link Try Orderli for Free, center=(960,586), url='https://orderli.com/en/integrations/lightspeed-k-series#'
	heading Trusted by hundreds of businesses, including:
	image Brouwerij Troost logo, url='https://orderli.com/images/troost-logo---min.jpg'
	image Van der Valk logo, url='https://orderli.com/images/van-der-valk-logo---min.png'
	image Avocado show logo, url='https://orderli.com/images/The-Avocado-Show-Logo-Black.svg'
	image Schiphol logo, url='https://orderli.com/images/schiphol.svg'
	image Brasa Purmerend logo, url='https://orderli.com/images/brasa-black---min.png'
	image Bierfabriek logo, url='https://orderli.com/images/bierfabriek-simple.svg'
	heading The capabilities of Orderli + Lightspeed K.
	image Green checkmark, url='https://orderli.com/images/5cd24ca168db6560f9e01747_check.svg'
	heading Pay afterwards
	image Green checkmark, url='https://orderli.com/images/5cd24ca168db6560f9e01747_check.svg'
	heading Stock management integration
	image Green checkmark, url='https://orderli.com/images/5cd24ca168db6560f9e01747_check.svg'
	heading Automatically integrate options
	image Green checkmark, url='https://orderli.com/images/5cd24ca168db6560f9e01747_check.svg'
	heading Integrate deals
	heading Don't leave guests waiting
	link Try Orderli for Free, url='https://orderli.com/en/integrations/lightspeed-k-series#'
	list
		listitem
			image, url='https://uploads-ssl.webflow.com/5dfcb4c9305f514441dd2294/5e00004adcc8adb8cf6ef413_checkmark.svg'
			StaticText No hidden costs
		listitem
			image, url='https://uploads-ssl.webflow.com/5dfcb4c9305f514441dd2294/5e00004adcc8adb8cf6ef413_checkmark.svg'
			StaticText Can be cancelled monthly
		listitem
			image, url='https://uploads-ssl.webflow.com/5dfcb4c9305f514441dd2294/5e00004adcc8adb8cf6ef413_checkmark.svg'
			StaticText Easy installation
	image, url='https://orderli.com/images/icons8-shop-1.svg'
	StaticText Tell us about your business
	image, url='https://orderli.com/images/icons8-restaurant_menu-1.svg'
	StaticText Add your menu in our editor
	image, url='https://orderli.com/images/simple-arrow.svg'
	image, url='https://orderli.com/images/simple-arrow-under.svg'
	image, url='https://orderli.com/images/icons8-qr_code-1.svg'
	StaticText Link the QR codes to your tables
	image Orderli logo, url='https://orderli.com/images/Orderli-logo-oranje.svg'
	link +31 85 303 07 23, url='tel:+31853030723'
	button Globe icon English, expanded=False, hasPopup='menu'
		image Globe icon, url='https://orderli.com/images/svgexport-14.svg'
	heading For businesses
	link Integrations, url='https://orderli.com/en/integrations.html'
	link Pricing, url='https://orderli.com/en/pricing.html'
	link Demo, url='https://orderli.com/en/demo.html'
	heading Orderli for
	link Bars, url='https://orderli.com/en/bars.html'
	link Hotels, url='https://orderli.com/en/hotels.html'
	link Festivals, url='https://orderli.com/en/festivals.html'
	link Restaurants, url='https://orderli.com/en/restaurants.html'
	link Everyone, url='https://orderli.com/en/'
	heading Integrations
	link Lightspeed, url='https://orderli.com/en/integrations/lightspeed.html'
	link unTill, url='https://orderli.com/en/integrations/untill.html'
	link Vectron, url='https://orderli.com/en/integrations/vectron.html'
	link MplusKASSA, url='https://orderli.com/en/integrations/mpluskassa.html'
	link Index, url='https://orderli.com/en/integrations/index-pos.html'
	heading Legal
	link Privacy Policy, url='https://orderli.com/privacypolicy.pdf'
	link Terms of Service, url='https://orderli.com/algemene-voorwaarden.pdf'
	heading Company
	link Our story, url='https://orderli.com/en/about.html'
	link Blog, url='http://blog.orderli.com/'
	link Careers 4, url='https://jobs.orderli.com/'
	link Contact, url='https://orderli.com/en/contact.html'
	link Voedselverspilling, url='https://orderli.com/foodwaste.html'
	StaticText Copyright © 2024 Orderli B.V.
	StaticText Made with 🎉 in Delft & Leeuwarden.
	link Instagram logo, url='https://www.instagram.com/orderli.nl/'
		image Instagram logo, url='https://orderli.com/images/icons8-instagram.svg'
	link Twitter logo, url='https://twitter.com/OrderliNL'
		image Twitter logo, url='https://orderli.com/images/icons8-twitter.svg'
	link Facebook logo, url='https://www.facebook.com/pages/category/Hospitality-Service/Orderli-102253861313384/'
		image Facebook logo, url='https://orderli.com/images/icons8-facebook.svg'
	link LinkedIn logo, url='https://www.linkedin.com/company/orderli'
		image LinkedIn logo, url='https://orderli.com/images/icons8-linkedin.svg'
	[d] Iframe trengo-widget-launcher, center=(1870,1030), title=trengo-widget-launcher
		RootWebArea, url='about:blank'
```
</details>



```
RootWebArea Lightspeed K-series QR ordering - Mobile Ordering for Lightspeed, focused, url='https://orderli.com/en/integrations/lightspeed-k-series'
	banner
		link Orderli logo, url='https://orderli.com/en/'
			image Orderli logo, url='https://orderli.com/images/Orderli-logo-oranje.svg'
		navigation
```
<details><summary>Show more</summary>

```
			button Orderli for, expanded=False, hasPopup='menu'
			link Integrations, url='https://orderli.com/en/integrations.html'
			link Pricing, url='https://orderli.com/en/pricing.html'
			link Demo, url='https://orderli.com/en/demo.html'
			link About us, url='https://orderli.com/en/about.html'
			link Contact, url='https://orderli.com/en/contact.html'
			link Log in, url='https://admin.orderli.com/login'
		link Try for free, url='https://orderli.com/en/integrations/lightspeed-k-series#'
	image Lightspeed K-series logo, url='https://orderli.com/images/lightspeed-k.svg'
	heading QR ordering for Lightspeed K.
	paragraph
		StaticText Connect Orderli QR ordering directly with Lightspeed K-Series. All orders are sent to the POS. Within
		strong
			StaticText one minute connected
		StaticText to Lightspeed!
	link Try Orderli for Free, focused, url='https://orderli.com/en/integrations/lightspeed-k-series#'
	heading Trusted by hundreds of businesses, including:
	image Brouwerij Troost logo, url='https://orderli.com/images/troost-logo---min.jpg'
	image Van der Valk logo, url='https://orderli.com/images/van-der-valk-logo---min.png'
	image Avocado show logo, url='https://orderli.com/images/The-Avocado-Show-Logo-Black.svg'
	image Schiphol logo, url='https://orderli.com/images/schiphol.svg'
	image Brasa Purmerend logo, url='https://orderli.com/images/brasa-black---min.png'
	image Bierfabriek logo, url='https://orderli.com/images/bierfabriek-simple.svg'
	heading The capabilities of Orderli + Lightspeed K.
	image Green checkmark, url='https://orderli.com/images/5cd24ca168db6560f9e01747_check.svg'
	heading Pay afterwards
	image Green checkmark, url='https://orderli.com/images/5cd24ca168db6560f9e01747_check.svg'
	heading Stock management integration
	image Green checkmark, url='https://orderli.com/images/5cd24ca168db6560f9e01747_check.svg'
	heading Automatically integrate options
	image Green checkmark, url='https://orderli.com/images/5cd24ca168db6560f9e01747_check.svg'
	heading Integrate deals
	heading Don't leave guests waiting
	link Try Orderli for Free, url='https://orderli.com/en/integrations/lightspeed-k-series#'
	list
		listitem
			image, url='https://uploads-ssl.webflow.com/5dfcb4c9305f514441dd2294/5e00004adcc8adb8cf6ef413_checkmark.svg'
			StaticText No hidden costs
		listitem
			image, url='https://uploads-ssl.webflow.com/5dfcb4c9305f514441dd2294/5e00004adcc8adb8cf6ef413_checkmark.svg'
			StaticText Can be cancelled monthly
		listitem
			image, url='https://uploads-ssl.webflow.com/5dfcb4c9305f514441dd2294/5e00004adcc8adb8cf6ef413_checkmark.svg'
			StaticText Easy installation
	image, url='https://orderli.com/images/icons8-shop-1.svg'
	StaticText Tell us about your business
	image, url='https://orderli.com/images/icons8-restaurant_menu-1.svg'
	StaticText Add your menu in our editor
	image, url='https://orderli.com/images/simple-arrow.svg'
	image, url='https://orderli.com/images/simple-arrow-under.svg'
	image, url='https://orderli.com/images/icons8-qr_code-1.svg'
	StaticText Link the QR codes to your tables
	image Orderli logo, url='https://orderli.com/images/Orderli-logo-oranje.svg'
	link +31 85 303 07 23, url='tel:+31853030723'
	button Globe icon English, expanded=False, hasPopup='menu'
		image Globe icon, url='https://orderli.com/images/svgexport-14.svg'
	heading For businesses
	link Integrations, url='https://orderli.com/en/integrations.html'
	link Pricing, url='https://orderli.com/en/pricing.html'
	link Demo, url='https://orderli.com/en/demo.html'
	heading Orderli for
	link Bars, url='https://orderli.com/en/bars.html'
	link Hotels, url='https://orderli.com/en/hotels.html'
	link Festivals, url='https://orderli.com/en/festivals.html'
	link Restaurants, url='https://orderli.com/en/restaurants.html'
	link Everyone, url='https://orderli.com/en/'
	heading Integrations
	link Lightspeed, url='https://orderli.com/en/integrations/lightspeed.html'
	link unTill, url='https://orderli.com/en/integrations/untill.html'
	link Vectron, url='https://orderli.com/en/integrations/vectron.html'
	link MplusKASSA, url='https://orderli.com/en/integrations/mpluskassa.html'
	link Index, url='https://orderli.com/en/integrations/index-pos.html'
	heading Legal
	link Privacy Policy, url='https://orderli.com/privacypolicy.pdf'
	link Terms of Service, url='https://orderli.com/algemene-voorwaarden.pdf'
	heading Company
	link Our story, url='https://orderli.com/en/about.html'
	link Blog, url='http://blog.orderli.com/'
	link Careers 4, url='https://jobs.orderli.com/'
	link Contact, url='https://orderli.com/en/contact.html'
	link Voedselverspilling, url='https://orderli.com/foodwaste.html'
	StaticText Copyright © 2024 Orderli B.V.
	StaticText Made with 🎉 in Delft & Leeuwarden.
	link Instagram logo, url='https://www.instagram.com/orderli.nl/'
		image Instagram logo, url='https://orderli.com/images/icons8-instagram.svg'
	link Twitter logo, url='https://twitter.com/OrderliNL'
		image Twitter logo, url='https://orderli.com/images/icons8-twitter.svg'
	link Facebook logo, url='https://www.facebook.com/pages/category/Hospitality-Service/Orderli-102253861313384/'
		image Facebook logo, url='https://orderli.com/images/icons8-facebook.svg'
	link LinkedIn logo, url='https://www.linkedin.com/company/orderli'
		image LinkedIn logo, url='https://orderli.com/images/icons8-linkedin.svg'
	[325] image Times icon, center=(1232,192), url='https://orderli.com/images/times.svg'
	heading Try Orderli for free.
	StaticText The first two weeks are free, from the moment you process your first order. Leave your details and we will get in touch with you as soon as possible.
	[329] link Or plan a demo now., center=(960,376), url='https://orderli.com/en/integrations/lightspeed-k-series#'
	[a] Iframe Form 0, center=(960,657), title=Form 0
		RootWebArea, url='about:blank'
			LabelText
				StaticText Naam
				StaticText *
			[a15] textbox Naam*, center=(960,462), required
			LabelText
				StaticText Naam onderneming
				StaticText *
			[a22] textbox Naam onderneming*, center=(960,544), required
			LabelText
				StaticText E-mail
				StaticText *
			[a29] textbox E-mail*, center=(960,626), required
			LabelText
				StaticText Telefoonnummer
				StaticText *
			[a36] textbox Telefoonnummer*, center=(960,708), required
			[a46] button Verzenden, center=(770,782)
			[aa] Iframe hubspot-forms-viral-iframe, center=(960,866)
				RootWebArea Virale links gebruikersinterface, url='https://app.hubspot.com/embedded-viral-link/forms?lang=nl&portalId=8545281&hubs_id=forms-branding-control&hubs_source=orderli.com&intent=marketingFreeForms'
					[aa36] link Creëer je eigen gratis formulieren om leads te genereren op je website., center=(960,866), url='https://app.hubspot.com/signup-hubspot/marketing?uuid=b18c7b8c-0c08-426b-87b2-547bebb04882&utm_medium=virality&utm_campaign=hubspot-forms-virality&intent=marketingFreeForms&hubs_id=forms-branding-control&hubs_source=orderli.com'
						strong
	[d] Iframe trengo-widget-launcher, center=(1870,1030), title=trengo-widget-launcher
		RootWebArea, url='about:blank'
```
</details>

**Reasoning for action:** Clicking on the 'Try Orderli for Free' button is a crucial step to advance the task. It directly links me to the form that allows the user to initiate the trial process for the Lightspeed K-series integration. This action ensures that I will be able to access the necessary information to explore the integration features and ultimately enhance the restaurant's ordering system.

**Action:** click(163) # Click on the 'Try Orderli for Free' button to explore the sign-up or demo options.

**Change Description:** After clicking the 'Try Orderli for Free' button, a form interface appeared where users can input their personal and business details, indicating a shift from the main information page to a focused sign-up or demo form.

**Screenshot before:****Screenshot after:**---


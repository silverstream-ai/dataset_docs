# Task

**Find Restaurants in Ibadan**

As a food lover,
I search for restaurants in Ibadan,
so that I can discover dining options available for delivery in my area.

**Success definition:** Given I am on the Heyfood homepage and I have access to the delivery address textbox
When I enter 'Ibadan' into the delivery address textbox and click on the 'Find restaurants' button
Then I should see a message indicating 'No result' for the specified delivery address 'Ibadan' and a prompt to 'Search for your location and select from the suggestions'.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://heyfood.africa/

https://heyfood.africa/

**Content (before/after):** 

```
RootWebArea Heyfood, focused, url='https://heyfood.africa/'
	[77] link heyfood-logo-long, center=(154,41), url='https://heyfood.africa/'
		image heyfood-logo-long, url='https://heyfood.africa/icons/new/logo-long.svg'
	[80] button Sign In, center=(1654,41), type=button
	[83] button Sign Up, center=(1779,41), type=button
```
<details><summary>Show more</summary>

```
	heading Your food delivered within minutes.
	image location-pin, url='https://heyfood.africa/icons/new/location-pin.svg'
	[96] textbox Enter delivery address, center=(353,492), contenteditable=True, type=text
	[98] button Find restaurants, center=(713,492), type=button
	image hero-image, url='https://heyfood.africa/images/new/hero-side.svg'
	[105] link apple-logo App Store, center=(1476,724), inner_text=App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	[111] link google-play-logo Play Store, center=(1663,724), inner_text=Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	image Try The App, url='https://heyfood.africa/images/new/first-sales-1.svg'
	heading Try The App
	paragraph
		StaticText Discover the best restaurants and vendors near you all in one place
	link Get Started, url='https://heyfood.africa/download'
	image Become A Merchant, url='https://heyfood.africa/images/new/first-sales-2.svg'
	heading Become A Merchant
	paragraph
		StaticText Grow your business and increase profit by creating an online ordering page
	link Get Started, url='https://heyfood.africa/merchant'
	image Become A Rider, url='https://heyfood.africa/images/new/first-sales-3.svg'
	heading Become A Rider
	paragraph
		StaticText Drive, deliver and earn. Make more money when you become a rider on Heyfood
	link Get Started, url='https://heyfood.africa/driver'
	heading A Variety of Stores to choose from
	paragraph
		StaticText Order food from the best restaurants, local favorites, and online vendors using the app or web.
	link Start Ordering, url='https://heyfood.africa/download'
		button Start Ordering
	image A Variety of Stores to choose from, url='https://heyfood.africa/images/new/second-sales-1.png'
	heading Grow With Heyfood
	paragraph
		StaticText Expand your business and make money with features that make managing and processing orders easier.
	image Order Management, url='https://heyfood.africa/images/new/second-sales-sub-1.svg'
	heading Order Management
	paragraph
		StaticText Receive and manage orders directly from your dashboard.
	image Automatic Payout, url='https://heyfood.africa/images/new/second-sales-sub-2.svg'
	heading Automatic Payout
	paragraph
		StaticText Get paid automatically to your bank account.
	image Dine-In Orders, url='https://heyfood.africa/images/new/second-sales-sub-3.svg'
	heading Dine-In Orders
	paragraph
		StaticText Better in-store dining service with QR Codes
	link Sign up your store, url='https://dashboard.heyfood.africa/signup'
		button Sign up your store
	image Grow With Heyfood, url='https://heyfood.africa/images/new/second-sales-2.png'
	heading Experience the app today!
	link apple-logo App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	link google-play-logo Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	image heyfood-app-demo, url='https://heyfood.africa/images/new/download-app-phone.png'
	heading Cities near me
	link Ibadan, url='https://heyfood.africa/places/ibadan'
	StaticText Top Areas
	list
		listitem
			link Agbowo, url='https://heyfood.africa/places/agbowo'
		listitem
			link Akobo, url='https://heyfood.africa/places/akobo'
		listitem
			link Ashi, url='https://heyfood.africa/places/ashi'
		listitem
			link Basorun, url='https://heyfood.africa/places/basorun'
		listitem
			link Bodija, url='https://heyfood.africa/places/bodija'
		listitem
			link Mokola, url='https://heyfood.africa/places/mokola'
		listitem
			link Ojoo, url='https://heyfood.africa/places/ojoo'
		listitem
			link Orogun, url='https://heyfood.africa/places/orogun'
		listitem
			link Barika, url='https://heyfood.africa/places/barika'
		listitem
			link Samonda, url='https://heyfood.africa/places/samonda'
		listitem
			link Sango, url='https://heyfood.africa/places/sango'
		listitem
			link Eleyele, url='https://heyfood.africa/places/eleyele'
		listitem
			link Ologuneru, url='https://heyfood.africa/places/ologuneru'
		listitem
			link Moniya, url='https://heyfood.africa/places/moniya'
		listitem
			link Agodi, url='https://heyfood.africa/places/agodi'
		listitem
			link Agodi-gate, url='https://heyfood.africa/places/agodi-gate'
		listitem
			link University of Ibadan, url='https://heyfood.africa/places/university-of-ibadan'
		listitem
			link UCH, url='https://heyfood.africa/places/uch'
		listitem
			link Dugbe, url='https://heyfood.africa/places/dugbe'
		listitem
			link Onireke, url='https://heyfood.africa/places/onireke'
	StaticText Best Restaurants In
	StaticText Ibadan
	list
		listitem
			link Restaurants in Agbowo, url='https://heyfood.africa/places/best-restaurants-in-agbowo'
		listitem
			link Restaurants in Akobo, url='https://heyfood.africa/places/best-restaurants-in-akobo'
		listitem
			link Restaurants in Ashi, url='https://heyfood.africa/places/best-restaurants-in-ashi'
		listitem
			link Restaurants in Basorun, url='https://heyfood.africa/places/best-restaurants-in-basorun'
		listitem
			link Restaurants in Bodija, url='https://heyfood.africa/places/best-restaurants-in-bodija'
		listitem
			link Restaurants in Mokola, url='https://heyfood.africa/places/best-restaurants-in-mokola'
		listitem
			link Restaurants in Ojoo, url='https://heyfood.africa/places/best-restaurants-in-ojoo'
		listitem
			link Restaurants in Orogun, url='https://heyfood.africa/places/best-restaurants-in-orogun'
		listitem
			link Restaurants in Barika, url='https://heyfood.africa/places/best-restaurants-in-barika'
		listitem
			link Restaurants in Samonda, url='https://heyfood.africa/places/best-restaurants-in-samonda'
		listitem
			link Restaurants in Sango, url='https://heyfood.africa/places/best-restaurants-in-sango'
		listitem
			link Restaurants in Eleyele, url='https://heyfood.africa/places/best-restaurants-in-eleyele'
		listitem
			link Restaurants in Ologuneru, url='https://heyfood.africa/places/best-restaurants-in-ologuneru'
		listitem
			link Restaurants in Moniya, url='https://heyfood.africa/places/best-restaurants-in-moniya'
		listitem
			link Restaurants in Agodi, url='https://heyfood.africa/places/best-restaurants-in-agodi'
		listitem
			link Restaurants in Agodi-gate, url='https://heyfood.africa/places/best-restaurants-in-agodi-gate'
		listitem
			link Restaurants in University of Ibadan, url='https://heyfood.africa/places/best-restaurants-in-university-of-ibadan'
		listitem
			link Restaurants in UCH, url='https://heyfood.africa/places/best-restaurants-in-uch'
		listitem
			link Restaurants in Dugbe, url='https://heyfood.africa/places/best-restaurants-in-dugbe'
		listitem
			link Restaurants in Onireke, url='https://heyfood.africa/places/best-restaurants-in-onireke'
	link Abuja, url='https://heyfood.africa/places/abuja'
	StaticText Top Areas
	list
		listitem
			link Wuse, url='https://heyfood.africa/places/wuse'
		listitem
			link Adetokunbo, url='https://heyfood.africa/places/adetokunbo'
		listitem
			link Aminu Kano Crescent, url='https://heyfood.africa/places/aminu-kano-crescent'
		listitem
			link Garki, url='https://heyfood.africa/places/garki'
		listitem
			link Gwarinpa, url='https://heyfood.africa/places/gwarinpa'
		listitem
			link Wuye, url='https://heyfood.africa/places/wuye'
		listitem
			link Utako, url='https://heyfood.africa/places/utako'
		listitem
			link Area 11, url='https://heyfood.africa/places/area-11'
	StaticText Best Restaurants In
	StaticText Abuja
	list
		listitem
			link Restaurants in Wuse, url='https://heyfood.africa/places/best-restaurants-in-wuse'
		listitem
			link Restaurants in Adetokunbo, url='https://heyfood.africa/places/best-restaurants-in-adetokunbo'
		listitem
			link Restaurants in Aminu Kano Crescent, url='https://heyfood.africa/places/best-restaurants-in-aminu-kano-crescent'
		listitem
			link Restaurants in Garki, url='https://heyfood.africa/places/best-restaurants-in-garki'
		listitem
			link Restaurants in Gwarinpa, url='https://heyfood.africa/places/best-restaurants-in-gwarinpa'
		listitem
			link Restaurants in Wuye, url='https://heyfood.africa/places/best-restaurants-in-wuye'
		listitem
			link Restaurants in Utako, url='https://heyfood.africa/places/best-restaurants-in-utako'
		listitem
			link Restaurants in Area 11, url='https://heyfood.africa/places/best-restaurants-in-area-11'
	link Lagos, url='https://heyfood.africa/places/lagos'
	StaticText Top Areas
	list
		listitem
			link Lekki, url='https://heyfood.africa/places/lekki'
		listitem
			link Ikeja, url='https://heyfood.africa/places/ikeja'
		listitem
			link Victoria Island, url='https://heyfood.africa/places/victoria-island'
		listitem
			link Ikoyi, url='https://heyfood.africa/places/ikoyi'
		listitem
			link Oniru, url='https://heyfood.africa/places/oniru'
	StaticText Best Restaurants In
	StaticText Lagos
	list
		listitem
			link Restaurants in Lekki, url='https://heyfood.africa/places/best-restaurants-in-lekki'
		listitem
			link Restaurants in Ikeja, url='https://heyfood.africa/places/best-restaurants-in-ikeja'
		listitem
			link Restaurants in Victoria Island, url='https://heyfood.africa/places/best-restaurants-in-victoria-island'
		listitem
			link Restaurants in Ikoyi, url='https://heyfood.africa/places/best-restaurants-in-ikoyi'
		listitem
			link Restaurants in Oniru, url='https://heyfood.africa/places/best-restaurants-in-oniru'
	heading Cuisines near me
	list
		listitem
			link Rice near me, url='https://heyfood.africa/places/ibadan/rice-near-me'
		listitem
			link Ice Cream near me, url='https://heyfood.africa/places/ibadan/ice-cream-near-me'
		listitem
			link Grocery near me, url='https://heyfood.africa/places/ibadan/grocery-near-me'
		listitem
			link Chicken near me, url='https://heyfood.africa/places/ibadan/chicken-near-me'
		listitem
			link Shawarma near me, url='https://heyfood.africa/places/ibadan/shawarma-near-me'
		listitem
			link Spaghetti near me, url='https://heyfood.africa/places/ibadan/spaghetti-near-me'
		listitem
			link Small Chops near me, url='https://heyfood.africa/places/ibadan/small-chops-near-me'
		listitem
			link Chinese near me, url='https://heyfood.africa/places/ibadan/chinese-near-me'
		listitem
			link Pizza near me, url='https://heyfood.africa/places/ibadan/pizza-near-me'
		listitem
			link Soup bowl near me, url='https://heyfood.africa/places/ibadan/soup-bowl-near-me'
		listitem
			link Grills near me, url='https://heyfood.africa/places/ibadan/grills-near-me'
		listitem
			link Fastfood near me, url='https://heyfood.africa/places/ibadan/fastfood-near-me'
	image heyfood-logo, url='https://heyfood.africa/icons/new/logo-long.svg'
	paragraph
		StaticText Your food delivered within minutes.
	link apple-logo App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	link google-play-logo Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	heading Get To Know Us
	link About Us, url='https://heyfood.medium.com/introducing-heyfood-7037d5a5f8c7?source=user_profile---------6----------------------------'
	link LinkedIn, url='https://www.linkedin.com/company/heyfood'
	link Blog, url='https://heyfood.medium.com/'
	heading Let Us Help You
	link Support, url='mailto:%20heypayapp@gmail.com'
	link FAQs, url='https://heyfood.africa/'
	link Restaurants Near Me, url='https://heyfood.africa/stores'
	heading Doing Business
	link Become a driver, url='https://heyfood.africa/driver'
	link Become a partner restaurant, url='https://heyfood.africa/merchant'
	image qr-code, url='https://heyfood.africa/images/new/download-qr.svg'
	link https://facebook.com/heyfoodNg, url='https://facebook.com/heyfoodNg'
		image https://facebook.com/heyfoodNg, url='https://heyfood.africa/icons/new/facebook.svg'
	link https://twitter.com/HeyfoodAfrica, url='https://twitter.com/HeyfoodAfrica'
		image https://twitter.com/HeyfoodAfrica, url='https://heyfood.africa/icons/new/twitter.svg'
	link https://www.instagram.com/heyfood.africa, url='https://www.instagram.com/heyfood.africa'
		image https://www.instagram.com/heyfood.africa, url='https://heyfood.africa/icons/new/instagram.svg'
	link https://www.linkedin.com/company/heyfood/, url='https://www.linkedin.com/company/heyfood/'
		image https://www.linkedin.com/company/heyfood/, url='https://heyfood.africa/icons/new/linkedin.svg'
	link Terms Of Service, url='https://heyfood.africa/terms'
	link Privacy Policy, url='https://heyfood.africa/privacy'
	StaticText © 2025 Hey Technologies Limited. All rights reserved
	alert, atomic
	[471] button Open Intercom Messenger, center=(44,1036)
		image
		image
```
</details>



```
RootWebArea Heyfood, focused, url='https://heyfood.africa/'
	[77] link heyfood-logo-long, center=(154,41), url='https://heyfood.africa/'
		image heyfood-logo-long, url='https://heyfood.africa/icons/new/logo-long.svg'
	[80] button Sign In, center=(1654,41), type=button
	[83] button Sign Up, center=(1779,41), type=button
```
<details><summary>Show more</summary>

```
	heading Your food delivered within minutes.
	image location-pin, url='https://heyfood.africa/icons/new/location-pin.svg'
	[96] textbox Enter delivery address, center=(353,492), contenteditable=True, focused, type=text
	StaticText *Search for your location and select from the suggestions
	StaticText No result
	[98] button Find restaurants, center=(713,492), type=button
	image hero-image, url='https://heyfood.africa/images/new/hero-side.svg'
	[105] link apple-logo App Store, center=(1476,724), inner_text=App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	[111] link google-play-logo Play Store, center=(1663,724), inner_text=Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	image Try The App, url='https://heyfood.africa/images/new/first-sales-1.svg'
	heading Try The App
	paragraph
		StaticText Discover the best restaurants and vendors near you all in one place
	link Get Started, url='https://heyfood.africa/download'
	image Become A Merchant, url='https://heyfood.africa/images/new/first-sales-2.svg'
	heading Become A Merchant
	paragraph
		StaticText Grow your business and increase profit by creating an online ordering page
	link Get Started, url='https://heyfood.africa/merchant'
	image Become A Rider, url='https://heyfood.africa/images/new/first-sales-3.svg'
	heading Become A Rider
	paragraph
		StaticText Drive, deliver and earn. Make more money when you become a rider on Heyfood
	link Get Started, url='https://heyfood.africa/driver'
	heading A Variety of Stores to choose from
	paragraph
		StaticText Order food from the best restaurants, local favorites, and online vendors using the app or web.
	link Start Ordering, url='https://heyfood.africa/download'
		button Start Ordering
	image A Variety of Stores to choose from, url='https://heyfood.africa/images/new/second-sales-1.png'
	heading Grow With Heyfood
	paragraph
		StaticText Expand your business and make money with features that make managing and processing orders easier.
	image Order Management, url='https://heyfood.africa/images/new/second-sales-sub-1.svg'
	heading Order Management
	paragraph
		StaticText Receive and manage orders directly from your dashboard.
	image Automatic Payout, url='https://heyfood.africa/images/new/second-sales-sub-2.svg'
	heading Automatic Payout
	paragraph
		StaticText Get paid automatically to your bank account.
	image Dine-In Orders, url='https://heyfood.africa/images/new/second-sales-sub-3.svg'
	heading Dine-In Orders
	paragraph
		StaticText Better in-store dining service with QR Codes
	link Sign up your store, url='https://dashboard.heyfood.africa/signup'
		button Sign up your store
	image Grow With Heyfood, url='https://heyfood.africa/images/new/second-sales-2.png'
	heading Experience the app today!
	link apple-logo App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	link google-play-logo Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	image heyfood-app-demo, url='https://heyfood.africa/images/new/download-app-phone.png'
	heading Cities near me
	link Ibadan, url='https://heyfood.africa/places/ibadan'
	StaticText Top Areas
	list
		listitem
			link Agbowo, url='https://heyfood.africa/places/agbowo'
		listitem
			link Akobo, url='https://heyfood.africa/places/akobo'
		listitem
			link Ashi, url='https://heyfood.africa/places/ashi'
		listitem
			link Basorun, url='https://heyfood.africa/places/basorun'
		listitem
			link Bodija, url='https://heyfood.africa/places/bodija'
		listitem
			link Mokola, url='https://heyfood.africa/places/mokola'
		listitem
			link Ojoo, url='https://heyfood.africa/places/ojoo'
		listitem
			link Orogun, url='https://heyfood.africa/places/orogun'
		listitem
			link Barika, url='https://heyfood.africa/places/barika'
		listitem
			link Samonda, url='https://heyfood.africa/places/samonda'
		listitem
			link Sango, url='https://heyfood.africa/places/sango'
		listitem
			link Eleyele, url='https://heyfood.africa/places/eleyele'
		listitem
			link Ologuneru, url='https://heyfood.africa/places/ologuneru'
		listitem
			link Moniya, url='https://heyfood.africa/places/moniya'
		listitem
			link Agodi, url='https://heyfood.africa/places/agodi'
		listitem
			link Agodi-gate, url='https://heyfood.africa/places/agodi-gate'
		listitem
			link University of Ibadan, url='https://heyfood.africa/places/university-of-ibadan'
		listitem
			link UCH, url='https://heyfood.africa/places/uch'
		listitem
			link Dugbe, url='https://heyfood.africa/places/dugbe'
		listitem
			link Onireke, url='https://heyfood.africa/places/onireke'
	StaticText Best Restaurants In
	StaticText Ibadan
	list
		listitem
			link Restaurants in Agbowo, url='https://heyfood.africa/places/best-restaurants-in-agbowo'
		listitem
			link Restaurants in Akobo, url='https://heyfood.africa/places/best-restaurants-in-akobo'
		listitem
			link Restaurants in Ashi, url='https://heyfood.africa/places/best-restaurants-in-ashi'
		listitem
			link Restaurants in Basorun, url='https://heyfood.africa/places/best-restaurants-in-basorun'
		listitem
			link Restaurants in Bodija, url='https://heyfood.africa/places/best-restaurants-in-bodija'
		listitem
			link Restaurants in Mokola, url='https://heyfood.africa/places/best-restaurants-in-mokola'
		listitem
			link Restaurants in Ojoo, url='https://heyfood.africa/places/best-restaurants-in-ojoo'
		listitem
			link Restaurants in Orogun, url='https://heyfood.africa/places/best-restaurants-in-orogun'
		listitem
			link Restaurants in Barika, url='https://heyfood.africa/places/best-restaurants-in-barika'
		listitem
			link Restaurants in Samonda, url='https://heyfood.africa/places/best-restaurants-in-samonda'
		listitem
			link Restaurants in Sango, url='https://heyfood.africa/places/best-restaurants-in-sango'
		listitem
			link Restaurants in Eleyele, url='https://heyfood.africa/places/best-restaurants-in-eleyele'
		listitem
			link Restaurants in Ologuneru, url='https://heyfood.africa/places/best-restaurants-in-ologuneru'
		listitem
			link Restaurants in Moniya, url='https://heyfood.africa/places/best-restaurants-in-moniya'
		listitem
			link Restaurants in Agodi, url='https://heyfood.africa/places/best-restaurants-in-agodi'
		listitem
			link Restaurants in Agodi-gate, url='https://heyfood.africa/places/best-restaurants-in-agodi-gate'
		listitem
			link Restaurants in University of Ibadan, url='https://heyfood.africa/places/best-restaurants-in-university-of-ibadan'
		listitem
			link Restaurants in UCH, url='https://heyfood.africa/places/best-restaurants-in-uch'
		listitem
			link Restaurants in Dugbe, url='https://heyfood.africa/places/best-restaurants-in-dugbe'
		listitem
			link Restaurants in Onireke, url='https://heyfood.africa/places/best-restaurants-in-onireke'
	link Abuja, url='https://heyfood.africa/places/abuja'
	StaticText Top Areas
	list
		listitem
			link Wuse, url='https://heyfood.africa/places/wuse'
		listitem
			link Adetokunbo, url='https://heyfood.africa/places/adetokunbo'
		listitem
			link Aminu Kano Crescent, url='https://heyfood.africa/places/aminu-kano-crescent'
		listitem
			link Garki, url='https://heyfood.africa/places/garki'
		listitem
			link Gwarinpa, url='https://heyfood.africa/places/gwarinpa'
		listitem
			link Wuye, url='https://heyfood.africa/places/wuye'
		listitem
			link Utako, url='https://heyfood.africa/places/utako'
		listitem
			link Area 11, url='https://heyfood.africa/places/area-11'
	StaticText Best Restaurants In
	StaticText Abuja
	list
		listitem
			link Restaurants in Wuse, url='https://heyfood.africa/places/best-restaurants-in-wuse'
		listitem
			link Restaurants in Adetokunbo, url='https://heyfood.africa/places/best-restaurants-in-adetokunbo'
		listitem
			link Restaurants in Aminu Kano Crescent, url='https://heyfood.africa/places/best-restaurants-in-aminu-kano-crescent'
		listitem
			link Restaurants in Garki, url='https://heyfood.africa/places/best-restaurants-in-garki'
		listitem
			link Restaurants in Gwarinpa, url='https://heyfood.africa/places/best-restaurants-in-gwarinpa'
		listitem
			link Restaurants in Wuye, url='https://heyfood.africa/places/best-restaurants-in-wuye'
		listitem
			link Restaurants in Utako, url='https://heyfood.africa/places/best-restaurants-in-utako'
		listitem
			link Restaurants in Area 11, url='https://heyfood.africa/places/best-restaurants-in-area-11'
	link Lagos, url='https://heyfood.africa/places/lagos'
	StaticText Top Areas
	list
		listitem
			link Lekki, url='https://heyfood.africa/places/lekki'
		listitem
			link Ikeja, url='https://heyfood.africa/places/ikeja'
		listitem
			link Victoria Island, url='https://heyfood.africa/places/victoria-island'
		listitem
			link Ikoyi, url='https://heyfood.africa/places/ikoyi'
		listitem
			link Oniru, url='https://heyfood.africa/places/oniru'
	StaticText Best Restaurants In
	StaticText Lagos
	list
		listitem
			link Restaurants in Lekki, url='https://heyfood.africa/places/best-restaurants-in-lekki'
		listitem
			link Restaurants in Ikeja, url='https://heyfood.africa/places/best-restaurants-in-ikeja'
		listitem
			link Restaurants in Victoria Island, url='https://heyfood.africa/places/best-restaurants-in-victoria-island'
		listitem
			link Restaurants in Ikoyi, url='https://heyfood.africa/places/best-restaurants-in-ikoyi'
		listitem
			link Restaurants in Oniru, url='https://heyfood.africa/places/best-restaurants-in-oniru'
	heading Cuisines near me
	list
		listitem
			link Rice near me, url='https://heyfood.africa/places/ibadan/rice-near-me'
		listitem
			link Ice Cream near me, url='https://heyfood.africa/places/ibadan/ice-cream-near-me'
		listitem
			link Grocery near me, url='https://heyfood.africa/places/ibadan/grocery-near-me'
		listitem
			link Chicken near me, url='https://heyfood.africa/places/ibadan/chicken-near-me'
		listitem
			link Shawarma near me, url='https://heyfood.africa/places/ibadan/shawarma-near-me'
		listitem
			link Spaghetti near me, url='https://heyfood.africa/places/ibadan/spaghetti-near-me'
		listitem
			link Small Chops near me, url='https://heyfood.africa/places/ibadan/small-chops-near-me'
		listitem
			link Chinese near me, url='https://heyfood.africa/places/ibadan/chinese-near-me'
		listitem
			link Pizza near me, url='https://heyfood.africa/places/ibadan/pizza-near-me'
		listitem
			link Soup bowl near me, url='https://heyfood.africa/places/ibadan/soup-bowl-near-me'
		listitem
			link Grills near me, url='https://heyfood.africa/places/ibadan/grills-near-me'
		listitem
			link Fastfood near me, url='https://heyfood.africa/places/ibadan/fastfood-near-me'
	image heyfood-logo, url='https://heyfood.africa/icons/new/logo-long.svg'
	paragraph
		StaticText Your food delivered within minutes.
	link apple-logo App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	link google-play-logo Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	heading Get To Know Us
	link About Us, url='https://heyfood.medium.com/introducing-heyfood-7037d5a5f8c7?source=user_profile---------6----------------------------'
	link LinkedIn, url='https://www.linkedin.com/company/heyfood'
	link Blog, url='https://heyfood.medium.com/'
	heading Let Us Help You
	link Support, url='mailto:%20heypayapp@gmail.com'
	link FAQs, url='https://heyfood.africa/'
	link Restaurants Near Me, url='https://heyfood.africa/stores'
	heading Doing Business
	link Become a driver, url='https://heyfood.africa/driver'
	link Become a partner restaurant, url='https://heyfood.africa/merchant'
	image qr-code, url='https://heyfood.africa/images/new/download-qr.svg'
	link https://facebook.com/heyfoodNg, url='https://facebook.com/heyfoodNg'
		image https://facebook.com/heyfoodNg, url='https://heyfood.africa/icons/new/facebook.svg'
	link https://twitter.com/HeyfoodAfrica, url='https://twitter.com/HeyfoodAfrica'
		image https://twitter.com/HeyfoodAfrica, url='https://heyfood.africa/icons/new/twitter.svg'
	link https://www.instagram.com/heyfood.africa, url='https://www.instagram.com/heyfood.africa'
		image https://www.instagram.com/heyfood.africa, url='https://heyfood.africa/icons/new/instagram.svg'
	link https://www.linkedin.com/company/heyfood/, url='https://www.linkedin.com/company/heyfood/'
		image https://www.linkedin.com/company/heyfood/, url='https://heyfood.africa/icons/new/linkedin.svg'
	link Terms Of Service, url='https://heyfood.africa/terms'
	link Privacy Policy, url='https://heyfood.africa/privacy'
	StaticText © 2025 Hey Technologies Limited. All rights reserved
	alert, atomic
	generic
		[b] dialog Intercom live chat, center=(44,1036), modal=False, title=Intercom live chat
```
</details>

**Reasoning for action:** I clicked the 'Find restaurants' button because it is the action required to submit the delivery address that was entered in the textbox. This action triggers the search for restaurants in Ibadan, which is the main goal of the user's request. By performing this click action, I am expecting the system to process the input and return either the results of available restaurants or the 'No result' message that the user needs to see.

**Action:** click(98) # Click on the 'Find restaurants' button to explore available restaurants.

**Change Description:** After clicking the 'Find restaurants' button, the textbox now displays a message prompting the user to search for their location and select from suggestions, alongside a notification indicating 'No result'. The focus remains on the textbox.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://heyfood.africa/

https://heyfood.africa/

**Content (before/after):** 

```
RootWebArea Heyfood, focused, url='https://heyfood.africa/'
	[77] link heyfood-logo-long, center=(154,41), url='https://heyfood.africa/'
		image heyfood-logo-long, url='https://heyfood.africa/icons/new/logo-long.svg'
	[80] button Sign In, center=(1654,41), type=button
	[83] button Sign Up, center=(1779,41), type=button
```
<details><summary>Show more</summary>

```
	heading Your food delivered within minutes.
	image location-pin, url='https://heyfood.africa/icons/new/location-pin.svg'
	[96] textbox Enter delivery address, center=(353,492), contenteditable=True, focused, type=text
	StaticText *Search for your location and select from the suggestions
	StaticText No result
	[98] button Find restaurants, center=(713,492), type=button
	image hero-image, url='https://heyfood.africa/images/new/hero-side.svg'
	[105] link apple-logo App Store, center=(1476,724), inner_text=App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	[111] link google-play-logo Play Store, center=(1663,724), inner_text=Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	image Try The App, url='https://heyfood.africa/images/new/first-sales-1.svg'
	heading Try The App
	paragraph
		StaticText Discover the best restaurants and vendors near you all in one place
	link Get Started, url='https://heyfood.africa/download'
	image Become A Merchant, url='https://heyfood.africa/images/new/first-sales-2.svg'
	heading Become A Merchant
	paragraph
		StaticText Grow your business and increase profit by creating an online ordering page
	link Get Started, url='https://heyfood.africa/merchant'
	image Become A Rider, url='https://heyfood.africa/images/new/first-sales-3.svg'
	heading Become A Rider
	paragraph
		StaticText Drive, deliver and earn. Make more money when you become a rider on Heyfood
	link Get Started, url='https://heyfood.africa/driver'
	heading A Variety of Stores to choose from
	paragraph
		StaticText Order food from the best restaurants, local favorites, and online vendors using the app or web.
	link Start Ordering, url='https://heyfood.africa/download'
		button Start Ordering
	image A Variety of Stores to choose from, url='https://heyfood.africa/images/new/second-sales-1.png'
	heading Grow With Heyfood
	paragraph
		StaticText Expand your business and make money with features that make managing and processing orders easier.
	image Order Management, url='https://heyfood.africa/images/new/second-sales-sub-1.svg'
	heading Order Management
	paragraph
		StaticText Receive and manage orders directly from your dashboard.
	image Automatic Payout, url='https://heyfood.africa/images/new/second-sales-sub-2.svg'
	heading Automatic Payout
	paragraph
		StaticText Get paid automatically to your bank account.
	image Dine-In Orders, url='https://heyfood.africa/images/new/second-sales-sub-3.svg'
	heading Dine-In Orders
	paragraph
		StaticText Better in-store dining service with QR Codes
	link Sign up your store, url='https://dashboard.heyfood.africa/signup'
		button Sign up your store
	image Grow With Heyfood, url='https://heyfood.africa/images/new/second-sales-2.png'
	heading Experience the app today!
	link apple-logo App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	link google-play-logo Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	image heyfood-app-demo, url='https://heyfood.africa/images/new/download-app-phone.png'
	heading Cities near me
	link Ibadan, url='https://heyfood.africa/places/ibadan'
	StaticText Top Areas
	list
		listitem
			link Agbowo, url='https://heyfood.africa/places/agbowo'
		listitem
			link Akobo, url='https://heyfood.africa/places/akobo'
		listitem
			link Ashi, url='https://heyfood.africa/places/ashi'
		listitem
			link Basorun, url='https://heyfood.africa/places/basorun'
		listitem
			link Bodija, url='https://heyfood.africa/places/bodija'
		listitem
			link Mokola, url='https://heyfood.africa/places/mokola'
		listitem
			link Ojoo, url='https://heyfood.africa/places/ojoo'
		listitem
			link Orogun, url='https://heyfood.africa/places/orogun'
		listitem
			link Barika, url='https://heyfood.africa/places/barika'
		listitem
			link Samonda, url='https://heyfood.africa/places/samonda'
		listitem
			link Sango, url='https://heyfood.africa/places/sango'
		listitem
			link Eleyele, url='https://heyfood.africa/places/eleyele'
		listitem
			link Ologuneru, url='https://heyfood.africa/places/ologuneru'
		listitem
			link Moniya, url='https://heyfood.africa/places/moniya'
		listitem
			link Agodi, url='https://heyfood.africa/places/agodi'
		listitem
			link Agodi-gate, url='https://heyfood.africa/places/agodi-gate'
		listitem
			link University of Ibadan, url='https://heyfood.africa/places/university-of-ibadan'
		listitem
			link UCH, url='https://heyfood.africa/places/uch'
		listitem
			link Dugbe, url='https://heyfood.africa/places/dugbe'
		listitem
			link Onireke, url='https://heyfood.africa/places/onireke'
	StaticText Best Restaurants In
	StaticText Ibadan
	list
		listitem
			link Restaurants in Agbowo, url='https://heyfood.africa/places/best-restaurants-in-agbowo'
		listitem
			link Restaurants in Akobo, url='https://heyfood.africa/places/best-restaurants-in-akobo'
		listitem
			link Restaurants in Ashi, url='https://heyfood.africa/places/best-restaurants-in-ashi'
		listitem
			link Restaurants in Basorun, url='https://heyfood.africa/places/best-restaurants-in-basorun'
		listitem
			link Restaurants in Bodija, url='https://heyfood.africa/places/best-restaurants-in-bodija'
		listitem
			link Restaurants in Mokola, url='https://heyfood.africa/places/best-restaurants-in-mokola'
		listitem
			link Restaurants in Ojoo, url='https://heyfood.africa/places/best-restaurants-in-ojoo'
		listitem
			link Restaurants in Orogun, url='https://heyfood.africa/places/best-restaurants-in-orogun'
		listitem
			link Restaurants in Barika, url='https://heyfood.africa/places/best-restaurants-in-barika'
		listitem
			link Restaurants in Samonda, url='https://heyfood.africa/places/best-restaurants-in-samonda'
		listitem
			link Restaurants in Sango, url='https://heyfood.africa/places/best-restaurants-in-sango'
		listitem
			link Restaurants in Eleyele, url='https://heyfood.africa/places/best-restaurants-in-eleyele'
		listitem
			link Restaurants in Ologuneru, url='https://heyfood.africa/places/best-restaurants-in-ologuneru'
		listitem
			link Restaurants in Moniya, url='https://heyfood.africa/places/best-restaurants-in-moniya'
		listitem
			link Restaurants in Agodi, url='https://heyfood.africa/places/best-restaurants-in-agodi'
		listitem
			link Restaurants in Agodi-gate, url='https://heyfood.africa/places/best-restaurants-in-agodi-gate'
		listitem
			link Restaurants in University of Ibadan, url='https://heyfood.africa/places/best-restaurants-in-university-of-ibadan'
		listitem
			link Restaurants in UCH, url='https://heyfood.africa/places/best-restaurants-in-uch'
		listitem
			link Restaurants in Dugbe, url='https://heyfood.africa/places/best-restaurants-in-dugbe'
		listitem
			link Restaurants in Onireke, url='https://heyfood.africa/places/best-restaurants-in-onireke'
	link Abuja, url='https://heyfood.africa/places/abuja'
	StaticText Top Areas
	list
		listitem
			link Wuse, url='https://heyfood.africa/places/wuse'
		listitem
			link Adetokunbo, url='https://heyfood.africa/places/adetokunbo'
		listitem
			link Aminu Kano Crescent, url='https://heyfood.africa/places/aminu-kano-crescent'
		listitem
			link Garki, url='https://heyfood.africa/places/garki'
		listitem
			link Gwarinpa, url='https://heyfood.africa/places/gwarinpa'
		listitem
			link Wuye, url='https://heyfood.africa/places/wuye'
		listitem
			link Utako, url='https://heyfood.africa/places/utako'
		listitem
			link Area 11, url='https://heyfood.africa/places/area-11'
	StaticText Best Restaurants In
	StaticText Abuja
	list
		listitem
			link Restaurants in Wuse, url='https://heyfood.africa/places/best-restaurants-in-wuse'
		listitem
			link Restaurants in Adetokunbo, url='https://heyfood.africa/places/best-restaurants-in-adetokunbo'
		listitem
			link Restaurants in Aminu Kano Crescent, url='https://heyfood.africa/places/best-restaurants-in-aminu-kano-crescent'
		listitem
			link Restaurants in Garki, url='https://heyfood.africa/places/best-restaurants-in-garki'
		listitem
			link Restaurants in Gwarinpa, url='https://heyfood.africa/places/best-restaurants-in-gwarinpa'
		listitem
			link Restaurants in Wuye, url='https://heyfood.africa/places/best-restaurants-in-wuye'
		listitem
			link Restaurants in Utako, url='https://heyfood.africa/places/best-restaurants-in-utako'
		listitem
			link Restaurants in Area 11, url='https://heyfood.africa/places/best-restaurants-in-area-11'
	link Lagos, url='https://heyfood.africa/places/lagos'
	StaticText Top Areas
	list
		listitem
			link Lekki, url='https://heyfood.africa/places/lekki'
		listitem
			link Ikeja, url='https://heyfood.africa/places/ikeja'
		listitem
			link Victoria Island, url='https://heyfood.africa/places/victoria-island'
		listitem
			link Ikoyi, url='https://heyfood.africa/places/ikoyi'
		listitem
			link Oniru, url='https://heyfood.africa/places/oniru'
	StaticText Best Restaurants In
	StaticText Lagos
	list
		listitem
			link Restaurants in Lekki, url='https://heyfood.africa/places/best-restaurants-in-lekki'
		listitem
			link Restaurants in Ikeja, url='https://heyfood.africa/places/best-restaurants-in-ikeja'
		listitem
			link Restaurants in Victoria Island, url='https://heyfood.africa/places/best-restaurants-in-victoria-island'
		listitem
			link Restaurants in Ikoyi, url='https://heyfood.africa/places/best-restaurants-in-ikoyi'
		listitem
			link Restaurants in Oniru, url='https://heyfood.africa/places/best-restaurants-in-oniru'
	heading Cuisines near me
	list
		listitem
			link Rice near me, url='https://heyfood.africa/places/ibadan/rice-near-me'
		listitem
			link Ice Cream near me, url='https://heyfood.africa/places/ibadan/ice-cream-near-me'
		listitem
			link Grocery near me, url='https://heyfood.africa/places/ibadan/grocery-near-me'
		listitem
			link Chicken near me, url='https://heyfood.africa/places/ibadan/chicken-near-me'
		listitem
			link Shawarma near me, url='https://heyfood.africa/places/ibadan/shawarma-near-me'
		listitem
			link Spaghetti near me, url='https://heyfood.africa/places/ibadan/spaghetti-near-me'
		listitem
			link Small Chops near me, url='https://heyfood.africa/places/ibadan/small-chops-near-me'
		listitem
			link Chinese near me, url='https://heyfood.africa/places/ibadan/chinese-near-me'
		listitem
			link Pizza near me, url='https://heyfood.africa/places/ibadan/pizza-near-me'
		listitem
			link Soup bowl near me, url='https://heyfood.africa/places/ibadan/soup-bowl-near-me'
		listitem
			link Grills near me, url='https://heyfood.africa/places/ibadan/grills-near-me'
		listitem
			link Fastfood near me, url='https://heyfood.africa/places/ibadan/fastfood-near-me'
	image heyfood-logo, url='https://heyfood.africa/icons/new/logo-long.svg'
	paragraph
		StaticText Your food delivered within minutes.
	link apple-logo App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	link google-play-logo Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	heading Get To Know Us
	link About Us, url='https://heyfood.medium.com/introducing-heyfood-7037d5a5f8c7?source=user_profile---------6----------------------------'
	link LinkedIn, url='https://www.linkedin.com/company/heyfood'
	link Blog, url='https://heyfood.medium.com/'
	heading Let Us Help You
	link Support, url='mailto:%20heypayapp@gmail.com'
	link FAQs, url='https://heyfood.africa/'
	link Restaurants Near Me, url='https://heyfood.africa/stores'
	heading Doing Business
	link Become a driver, url='https://heyfood.africa/driver'
	link Become a partner restaurant, url='https://heyfood.africa/merchant'
	image qr-code, url='https://heyfood.africa/images/new/download-qr.svg'
	link https://facebook.com/heyfoodNg, url='https://facebook.com/heyfoodNg'
		image https://facebook.com/heyfoodNg, url='https://heyfood.africa/icons/new/facebook.svg'
	link https://twitter.com/HeyfoodAfrica, url='https://twitter.com/HeyfoodAfrica'
		image https://twitter.com/HeyfoodAfrica, url='https://heyfood.africa/icons/new/twitter.svg'
	link https://www.instagram.com/heyfood.africa, url='https://www.instagram.com/heyfood.africa'
		image https://www.instagram.com/heyfood.africa, url='https://heyfood.africa/icons/new/instagram.svg'
	link https://www.linkedin.com/company/heyfood/, url='https://www.linkedin.com/company/heyfood/'
		image https://www.linkedin.com/company/heyfood/, url='https://heyfood.africa/icons/new/linkedin.svg'
	link Terms Of Service, url='https://heyfood.africa/terms'
	link Privacy Policy, url='https://heyfood.africa/privacy'
	StaticText © 2025 Hey Technologies Limited. All rights reserved
	alert, atomic
	generic
		[b] dialog Intercom live chat, center=(44,1036), modal=False, title=Intercom live chat
```
</details>



```
RootWebArea Heyfood, focused, url='https://heyfood.africa/'
	[77] link heyfood-logo-long, center=(154,41), url='https://heyfood.africa/'
		image heyfood-logo-long, url='https://heyfood.africa/icons/new/logo-long.svg'
	[80] button Sign In, center=(1654,41), type=button
	[83] button Sign Up, center=(1779,41), type=button
```
<details><summary>Show more</summary>

```
	heading Your food delivered within minutes.
	image location-pin, url='https://heyfood.africa/icons/new/location-pin.svg'
	[96] textbox Enter delivery address value='Ibadan', center=(353,492), contenteditable=True, focused, type=text
	list
		[501] button Ibadan Nigeria, center=(254,567), inner_text=Ibadan

Nigeria
			paragraph
		[507] button Ibadan Airport Ibadan, Nigeria, center=(254,639), inner_text=Ibadan Airport

Ibadan, Nigeria
			paragraph
		[513] button Ibadan - Iwo Road Iwo, Nigeria, center=(254,711), inner_text=Ibadan - Iwo Road

Iwo, Nigeria
			paragraph
		[519] button Ibadan Expressway Lagos - Ibadan Expressway, Ibafo, Nigeria, center=(254,783), inner_text=Ibadan Expressway

Lagos - Ibadan Expressway, Ibafo, Nigeria
			paragraph
		[525] button Ibadan North Nigeria, center=(254,855), inner_text=Ibadan North

Nigeria
			paragraph
		image google-icon, url='https://heyfood.africa/icons/new/google_on_white.png'
	[98] button Find restaurants, center=(713,492), type=button
	image hero-image, url='https://heyfood.africa/images/new/hero-side.svg'
	[105] link apple-logo App Store, center=(1476,724), inner_text=App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	[111] link google-play-logo Play Store, center=(1663,724), inner_text=Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	image Try The App, url='https://heyfood.africa/images/new/first-sales-1.svg'
	heading Try The App
	paragraph
		StaticText Discover the best restaurants and vendors near you all in one place
	link Get Started, url='https://heyfood.africa/download'
	image Become A Merchant, url='https://heyfood.africa/images/new/first-sales-2.svg'
	heading Become A Merchant
	paragraph
		StaticText Grow your business and increase profit by creating an online ordering page
	link Get Started, url='https://heyfood.africa/merchant'
	image Become A Rider, url='https://heyfood.africa/images/new/first-sales-3.svg'
	heading Become A Rider
	paragraph
		StaticText Drive, deliver and earn. Make more money when you become a rider on Heyfood
	link Get Started, url='https://heyfood.africa/driver'
	heading A Variety of Stores to choose from
	paragraph
		StaticText Order food from the best restaurants, local favorites, and online vendors using the app or web.
	link Start Ordering, url='https://heyfood.africa/download'
		button Start Ordering
	image A Variety of Stores to choose from, url='https://heyfood.africa/images/new/second-sales-1.png'
	heading Grow With Heyfood
	paragraph
		StaticText Expand your business and make money with features that make managing and processing orders easier.
	image Order Management, url='https://heyfood.africa/images/new/second-sales-sub-1.svg'
	heading Order Management
	paragraph
		StaticText Receive and manage orders directly from your dashboard.
	image Automatic Payout, url='https://heyfood.africa/images/new/second-sales-sub-2.svg'
	heading Automatic Payout
	paragraph
		StaticText Get paid automatically to your bank account.
	image Dine-In Orders, url='https://heyfood.africa/images/new/second-sales-sub-3.svg'
	heading Dine-In Orders
	paragraph
		StaticText Better in-store dining service with QR Codes
	link Sign up your store, url='https://dashboard.heyfood.africa/signup'
		button Sign up your store
	image Grow With Heyfood, url='https://heyfood.africa/images/new/second-sales-2.png'
	heading Experience the app today!
	link apple-logo App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	link google-play-logo Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	image heyfood-app-demo, url='https://heyfood.africa/images/new/download-app-phone.png'
	heading Cities near me
	link Ibadan, url='https://heyfood.africa/places/ibadan'
	StaticText Top Areas
	list
		listitem
			link Agbowo, url='https://heyfood.africa/places/agbowo'
		listitem
			link Akobo, url='https://heyfood.africa/places/akobo'
		listitem
			link Ashi, url='https://heyfood.africa/places/ashi'
		listitem
			link Basorun, url='https://heyfood.africa/places/basorun'
		listitem
			link Bodija, url='https://heyfood.africa/places/bodija'
		listitem
			link Mokola, url='https://heyfood.africa/places/mokola'
		listitem
			link Ojoo, url='https://heyfood.africa/places/ojoo'
		listitem
			link Orogun, url='https://heyfood.africa/places/orogun'
		listitem
			link Barika, url='https://heyfood.africa/places/barika'
		listitem
			link Samonda, url='https://heyfood.africa/places/samonda'
		listitem
			link Sango, url='https://heyfood.africa/places/sango'
		listitem
			link Eleyele, url='https://heyfood.africa/places/eleyele'
		listitem
			link Ologuneru, url='https://heyfood.africa/places/ologuneru'
		listitem
			link Moniya, url='https://heyfood.africa/places/moniya'
		listitem
			link Agodi, url='https://heyfood.africa/places/agodi'
		listitem
			link Agodi-gate, url='https://heyfood.africa/places/agodi-gate'
		listitem
			link University of Ibadan, url='https://heyfood.africa/places/university-of-ibadan'
		listitem
			link UCH, url='https://heyfood.africa/places/uch'
		listitem
			link Dugbe, url='https://heyfood.africa/places/dugbe'
		listitem
			link Onireke, url='https://heyfood.africa/places/onireke'
	StaticText Best Restaurants In
	StaticText Ibadan
	list
		listitem
			link Restaurants in Agbowo, url='https://heyfood.africa/places/best-restaurants-in-agbowo'
		listitem
			link Restaurants in Akobo, url='https://heyfood.africa/places/best-restaurants-in-akobo'
		listitem
			link Restaurants in Ashi, url='https://heyfood.africa/places/best-restaurants-in-ashi'
		listitem
			link Restaurants in Basorun, url='https://heyfood.africa/places/best-restaurants-in-basorun'
		listitem
			link Restaurants in Bodija, url='https://heyfood.africa/places/best-restaurants-in-bodija'
		listitem
			link Restaurants in Mokola, url='https://heyfood.africa/places/best-restaurants-in-mokola'
		listitem
			link Restaurants in Ojoo, url='https://heyfood.africa/places/best-restaurants-in-ojoo'
		listitem
			link Restaurants in Orogun, url='https://heyfood.africa/places/best-restaurants-in-orogun'
		listitem
			link Restaurants in Barika, url='https://heyfood.africa/places/best-restaurants-in-barika'
		listitem
			link Restaurants in Samonda, url='https://heyfood.africa/places/best-restaurants-in-samonda'
		listitem
			link Restaurants in Sango, url='https://heyfood.africa/places/best-restaurants-in-sango'
		listitem
			link Restaurants in Eleyele, url='https://heyfood.africa/places/best-restaurants-in-eleyele'
		listitem
			link Restaurants in Ologuneru, url='https://heyfood.africa/places/best-restaurants-in-ologuneru'
		listitem
			link Restaurants in Moniya, url='https://heyfood.africa/places/best-restaurants-in-moniya'
		listitem
			link Restaurants in Agodi, url='https://heyfood.africa/places/best-restaurants-in-agodi'
		listitem
			link Restaurants in Agodi-gate, url='https://heyfood.africa/places/best-restaurants-in-agodi-gate'
		listitem
			link Restaurants in University of Ibadan, url='https://heyfood.africa/places/best-restaurants-in-university-of-ibadan'
		listitem
			link Restaurants in UCH, url='https://heyfood.africa/places/best-restaurants-in-uch'
		listitem
			link Restaurants in Dugbe, url='https://heyfood.africa/places/best-restaurants-in-dugbe'
		listitem
			link Restaurants in Onireke, url='https://heyfood.africa/places/best-restaurants-in-onireke'
	link Abuja, url='https://heyfood.africa/places/abuja'
	StaticText Top Areas
	list
		listitem
			link Wuse, url='https://heyfood.africa/places/wuse'
		listitem
			link Adetokunbo, url='https://heyfood.africa/places/adetokunbo'
		listitem
			link Aminu Kano Crescent, url='https://heyfood.africa/places/aminu-kano-crescent'
		listitem
			link Garki, url='https://heyfood.africa/places/garki'
		listitem
			link Gwarinpa, url='https://heyfood.africa/places/gwarinpa'
		listitem
			link Wuye, url='https://heyfood.africa/places/wuye'
		listitem
			link Utako, url='https://heyfood.africa/places/utako'
		listitem
			link Area 11, url='https://heyfood.africa/places/area-11'
	StaticText Best Restaurants In
	StaticText Abuja
	list
		listitem
			link Restaurants in Wuse, url='https://heyfood.africa/places/best-restaurants-in-wuse'
		listitem
			link Restaurants in Adetokunbo, url='https://heyfood.africa/places/best-restaurants-in-adetokunbo'
		listitem
			link Restaurants in Aminu Kano Crescent, url='https://heyfood.africa/places/best-restaurants-in-aminu-kano-crescent'
		listitem
			link Restaurants in Garki, url='https://heyfood.africa/places/best-restaurants-in-garki'
		listitem
			link Restaurants in Gwarinpa, url='https://heyfood.africa/places/best-restaurants-in-gwarinpa'
		listitem
			link Restaurants in Wuye, url='https://heyfood.africa/places/best-restaurants-in-wuye'
		listitem
			link Restaurants in Utako, url='https://heyfood.africa/places/best-restaurants-in-utako'
		listitem
			link Restaurants in Area 11, url='https://heyfood.africa/places/best-restaurants-in-area-11'
	link Lagos, url='https://heyfood.africa/places/lagos'
	StaticText Top Areas
	list
		listitem
			link Lekki, url='https://heyfood.africa/places/lekki'
		listitem
			link Ikeja, url='https://heyfood.africa/places/ikeja'
		listitem
			link Victoria Island, url='https://heyfood.africa/places/victoria-island'
		listitem
			link Ikoyi, url='https://heyfood.africa/places/ikoyi'
		listitem
			link Oniru, url='https://heyfood.africa/places/oniru'
	StaticText Best Restaurants In
	StaticText Lagos
	list
		listitem
			link Restaurants in Lekki, url='https://heyfood.africa/places/best-restaurants-in-lekki'
		listitem
			link Restaurants in Ikeja, url='https://heyfood.africa/places/best-restaurants-in-ikeja'
		listitem
			link Restaurants in Victoria Island, url='https://heyfood.africa/places/best-restaurants-in-victoria-island'
		listitem
			link Restaurants in Ikoyi, url='https://heyfood.africa/places/best-restaurants-in-ikoyi'
		listitem
			link Restaurants in Oniru, url='https://heyfood.africa/places/best-restaurants-in-oniru'
	heading Cuisines near me
	list
		listitem
			link Rice near me, url='https://heyfood.africa/places/ibadan/rice-near-me'
		listitem
			link Ice Cream near me, url='https://heyfood.africa/places/ibadan/ice-cream-near-me'
		listitem
			link Grocery near me, url='https://heyfood.africa/places/ibadan/grocery-near-me'
		listitem
			link Chicken near me, url='https://heyfood.africa/places/ibadan/chicken-near-me'
		listitem
			link Shawarma near me, url='https://heyfood.africa/places/ibadan/shawarma-near-me'
		listitem
			link Spaghetti near me, url='https://heyfood.africa/places/ibadan/spaghetti-near-me'
		listitem
			link Small Chops near me, url='https://heyfood.africa/places/ibadan/small-chops-near-me'
		listitem
			link Chinese near me, url='https://heyfood.africa/places/ibadan/chinese-near-me'
		listitem
			link Pizza near me, url='https://heyfood.africa/places/ibadan/pizza-near-me'
		listitem
			link Soup bowl near me, url='https://heyfood.africa/places/ibadan/soup-bowl-near-me'
		listitem
			link Grills near me, url='https://heyfood.africa/places/ibadan/grills-near-me'
		listitem
			link Fastfood near me, url='https://heyfood.africa/places/ibadan/fastfood-near-me'
	image heyfood-logo, url='https://heyfood.africa/icons/new/logo-long.svg'
	paragraph
		StaticText Your food delivered within minutes.
	link apple-logo App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	link google-play-logo Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	heading Get To Know Us
	link About Us, url='https://heyfood.medium.com/introducing-heyfood-7037d5a5f8c7?source=user_profile---------6----------------------------'
	link LinkedIn, url='https://www.linkedin.com/company/heyfood'
	link Blog, url='https://heyfood.medium.com/'
	heading Let Us Help You
	link Support, url='mailto:%20heypayapp@gmail.com'
	link FAQs, url='https://heyfood.africa/'
	link Restaurants Near Me, url='https://heyfood.africa/stores'
	heading Doing Business
	link Become a driver, url='https://heyfood.africa/driver'
	link Become a partner restaurant, url='https://heyfood.africa/merchant'
	image qr-code, url='https://heyfood.africa/images/new/download-qr.svg'
	link https://facebook.com/heyfoodNg, url='https://facebook.com/heyfoodNg'
		image https://facebook.com/heyfoodNg, url='https://heyfood.africa/icons/new/facebook.svg'
	link https://twitter.com/HeyfoodAfrica, url='https://twitter.com/HeyfoodAfrica'
		image https://twitter.com/HeyfoodAfrica, url='https://heyfood.africa/icons/new/twitter.svg'
	link https://www.instagram.com/heyfood.africa, url='https://www.instagram.com/heyfood.africa'
		image https://www.instagram.com/heyfood.africa, url='https://heyfood.africa/icons/new/instagram.svg'
	link https://www.linkedin.com/company/heyfood/, url='https://www.linkedin.com/company/heyfood/'
		image https://www.linkedin.com/company/heyfood/, url='https://heyfood.africa/icons/new/linkedin.svg'
	link Terms Of Service, url='https://heyfood.africa/terms'
	link Privacy Policy, url='https://heyfood.africa/privacy'
	StaticText © 2025 Hey Technologies Limited. All rights reserved
	alert, atomic
	generic
		[b] dialog Intercom live chat, center=(44,1036), modal=False, title=Intercom live chat
```
</details>

**Reasoning for action:** I chose to fill the delivery address textbox with 'Ibadan' because the user is looking for dining options available for delivery in that specific area. By inputting 'Ibadan', I ensure the subsequent search for restaurants is relevant to the user's needs. This action directly sets up the request for restaurants that can be found in Ibadan, aligning with the user story to discover dining options.

**Action:** fill(96, 'Ibadan') # Fill in the delivery address textbox with 'Ibadan' to search for restaurants.

**Change Description:** The delivery address textbox was updated with the value 'Ibadan', enabling a search for restaurants in that area, and several buttons related to delivery suggestions were made available below the textbox.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://heyfood.africa/

https://heyfood.africa/

**Content (before/after):** 

```
RootWebArea Heyfood, focused, url='https://heyfood.africa/'
	[77] link heyfood-logo-long, center=(154,41), url='https://heyfood.africa/'
		image heyfood-logo-long, url='https://heyfood.africa/icons/new/logo-long.svg'
	[80] button Sign In, center=(1654,41), type=button
	[83] button Sign Up, center=(1779,41), type=button
```
<details><summary>Show more</summary>

```
	heading Your food delivered within minutes.
	image location-pin, url='https://heyfood.africa/icons/new/location-pin.svg'
	[96] textbox Enter delivery address value='Ibadan', center=(353,492), contenteditable=True, focused, type=text
	list
		[501] button Ibadan Nigeria, center=(254,567), inner_text=Ibadan

Nigeria
			paragraph
		[507] button Ibadan Airport Ibadan, Nigeria, center=(254,639), inner_text=Ibadan Airport

Ibadan, Nigeria
			paragraph
		[513] button Ibadan - Iwo Road Iwo, Nigeria, center=(254,711), inner_text=Ibadan - Iwo Road

Iwo, Nigeria
			paragraph
		[519] button Ibadan Expressway Lagos - Ibadan Expressway, Ibafo, Nigeria, center=(254,783), inner_text=Ibadan Expressway

Lagos - Ibadan Expressway, Ibafo, Nigeria
			paragraph
		[525] button Ibadan North Nigeria, center=(254,855), inner_text=Ibadan North

Nigeria
			paragraph
		image google-icon, url='https://heyfood.africa/icons/new/google_on_white.png'
	[98] button Find restaurants, center=(713,492), type=button
	image hero-image, url='https://heyfood.africa/images/new/hero-side.svg'
	[105] link apple-logo App Store, center=(1476,724), inner_text=App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	[111] link google-play-logo Play Store, center=(1663,724), inner_text=Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	image Try The App, url='https://heyfood.africa/images/new/first-sales-1.svg'
	heading Try The App
	paragraph
		StaticText Discover the best restaurants and vendors near you all in one place
	link Get Started, url='https://heyfood.africa/download'
	image Become A Merchant, url='https://heyfood.africa/images/new/first-sales-2.svg'
	heading Become A Merchant
	paragraph
		StaticText Grow your business and increase profit by creating an online ordering page
	link Get Started, url='https://heyfood.africa/merchant'
	image Become A Rider, url='https://heyfood.africa/images/new/first-sales-3.svg'
	heading Become A Rider
	paragraph
		StaticText Drive, deliver and earn. Make more money when you become a rider on Heyfood
	link Get Started, url='https://heyfood.africa/driver'
	heading A Variety of Stores to choose from
	paragraph
		StaticText Order food from the best restaurants, local favorites, and online vendors using the app or web.
	link Start Ordering, url='https://heyfood.africa/download'
		button Start Ordering
	image A Variety of Stores to choose from, url='https://heyfood.africa/images/new/second-sales-1.png'
	heading Grow With Heyfood
	paragraph
		StaticText Expand your business and make money with features that make managing and processing orders easier.
	image Order Management, url='https://heyfood.africa/images/new/second-sales-sub-1.svg'
	heading Order Management
	paragraph
		StaticText Receive and manage orders directly from your dashboard.
	image Automatic Payout, url='https://heyfood.africa/images/new/second-sales-sub-2.svg'
	heading Automatic Payout
	paragraph
		StaticText Get paid automatically to your bank account.
	image Dine-In Orders, url='https://heyfood.africa/images/new/second-sales-sub-3.svg'
	heading Dine-In Orders
	paragraph
		StaticText Better in-store dining service with QR Codes
	link Sign up your store, url='https://dashboard.heyfood.africa/signup'
		button Sign up your store
	image Grow With Heyfood, url='https://heyfood.africa/images/new/second-sales-2.png'
	heading Experience the app today!
	link apple-logo App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	link google-play-logo Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	image heyfood-app-demo, url='https://heyfood.africa/images/new/download-app-phone.png'
	heading Cities near me
	link Ibadan, url='https://heyfood.africa/places/ibadan'
	StaticText Top Areas
	list
		listitem
			link Agbowo, url='https://heyfood.africa/places/agbowo'
		listitem
			link Akobo, url='https://heyfood.africa/places/akobo'
		listitem
			link Ashi, url='https://heyfood.africa/places/ashi'
		listitem
			link Basorun, url='https://heyfood.africa/places/basorun'
		listitem
			link Bodija, url='https://heyfood.africa/places/bodija'
		listitem
			link Mokola, url='https://heyfood.africa/places/mokola'
		listitem
			link Ojoo, url='https://heyfood.africa/places/ojoo'
		listitem
			link Orogun, url='https://heyfood.africa/places/orogun'
		listitem
			link Barika, url='https://heyfood.africa/places/barika'
		listitem
			link Samonda, url='https://heyfood.africa/places/samonda'
		listitem
			link Sango, url='https://heyfood.africa/places/sango'
		listitem
			link Eleyele, url='https://heyfood.africa/places/eleyele'
		listitem
			link Ologuneru, url='https://heyfood.africa/places/ologuneru'
		listitem
			link Moniya, url='https://heyfood.africa/places/moniya'
		listitem
			link Agodi, url='https://heyfood.africa/places/agodi'
		listitem
			link Agodi-gate, url='https://heyfood.africa/places/agodi-gate'
		listitem
			link University of Ibadan, url='https://heyfood.africa/places/university-of-ibadan'
		listitem
			link UCH, url='https://heyfood.africa/places/uch'
		listitem
			link Dugbe, url='https://heyfood.africa/places/dugbe'
		listitem
			link Onireke, url='https://heyfood.africa/places/onireke'
	StaticText Best Restaurants In
	StaticText Ibadan
	list
		listitem
			link Restaurants in Agbowo, url='https://heyfood.africa/places/best-restaurants-in-agbowo'
		listitem
			link Restaurants in Akobo, url='https://heyfood.africa/places/best-restaurants-in-akobo'
		listitem
			link Restaurants in Ashi, url='https://heyfood.africa/places/best-restaurants-in-ashi'
		listitem
			link Restaurants in Basorun, url='https://heyfood.africa/places/best-restaurants-in-basorun'
		listitem
			link Restaurants in Bodija, url='https://heyfood.africa/places/best-restaurants-in-bodija'
		listitem
			link Restaurants in Mokola, url='https://heyfood.africa/places/best-restaurants-in-mokola'
		listitem
			link Restaurants in Ojoo, url='https://heyfood.africa/places/best-restaurants-in-ojoo'
		listitem
			link Restaurants in Orogun, url='https://heyfood.africa/places/best-restaurants-in-orogun'
		listitem
			link Restaurants in Barika, url='https://heyfood.africa/places/best-restaurants-in-barika'
		listitem
			link Restaurants in Samonda, url='https://heyfood.africa/places/best-restaurants-in-samonda'
		listitem
			link Restaurants in Sango, url='https://heyfood.africa/places/best-restaurants-in-sango'
		listitem
			link Restaurants in Eleyele, url='https://heyfood.africa/places/best-restaurants-in-eleyele'
		listitem
			link Restaurants in Ologuneru, url='https://heyfood.africa/places/best-restaurants-in-ologuneru'
		listitem
			link Restaurants in Moniya, url='https://heyfood.africa/places/best-restaurants-in-moniya'
		listitem
			link Restaurants in Agodi, url='https://heyfood.africa/places/best-restaurants-in-agodi'
		listitem
			link Restaurants in Agodi-gate, url='https://heyfood.africa/places/best-restaurants-in-agodi-gate'
		listitem
			link Restaurants in University of Ibadan, url='https://heyfood.africa/places/best-restaurants-in-university-of-ibadan'
		listitem
			link Restaurants in UCH, url='https://heyfood.africa/places/best-restaurants-in-uch'
		listitem
			link Restaurants in Dugbe, url='https://heyfood.africa/places/best-restaurants-in-dugbe'
		listitem
			link Restaurants in Onireke, url='https://heyfood.africa/places/best-restaurants-in-onireke'
	link Abuja, url='https://heyfood.africa/places/abuja'
	StaticText Top Areas
	list
		listitem
			link Wuse, url='https://heyfood.africa/places/wuse'
		listitem
			link Adetokunbo, url='https://heyfood.africa/places/adetokunbo'
		listitem
			link Aminu Kano Crescent, url='https://heyfood.africa/places/aminu-kano-crescent'
		listitem
			link Garki, url='https://heyfood.africa/places/garki'
		listitem
			link Gwarinpa, url='https://heyfood.africa/places/gwarinpa'
		listitem
			link Wuye, url='https://heyfood.africa/places/wuye'
		listitem
			link Utako, url='https://heyfood.africa/places/utako'
		listitem
			link Area 11, url='https://heyfood.africa/places/area-11'
	StaticText Best Restaurants In
	StaticText Abuja
	list
		listitem
			link Restaurants in Wuse, url='https://heyfood.africa/places/best-restaurants-in-wuse'
		listitem
			link Restaurants in Adetokunbo, url='https://heyfood.africa/places/best-restaurants-in-adetokunbo'
		listitem
			link Restaurants in Aminu Kano Crescent, url='https://heyfood.africa/places/best-restaurants-in-aminu-kano-crescent'
		listitem
			link Restaurants in Garki, url='https://heyfood.africa/places/best-restaurants-in-garki'
		listitem
			link Restaurants in Gwarinpa, url='https://heyfood.africa/places/best-restaurants-in-gwarinpa'
		listitem
			link Restaurants in Wuye, url='https://heyfood.africa/places/best-restaurants-in-wuye'
		listitem
			link Restaurants in Utako, url='https://heyfood.africa/places/best-restaurants-in-utako'
		listitem
			link Restaurants in Area 11, url='https://heyfood.africa/places/best-restaurants-in-area-11'
	link Lagos, url='https://heyfood.africa/places/lagos'
	StaticText Top Areas
	list
		listitem
			link Lekki, url='https://heyfood.africa/places/lekki'
		listitem
			link Ikeja, url='https://heyfood.africa/places/ikeja'
		listitem
			link Victoria Island, url='https://heyfood.africa/places/victoria-island'
		listitem
			link Ikoyi, url='https://heyfood.africa/places/ikoyi'
		listitem
			link Oniru, url='https://heyfood.africa/places/oniru'
	StaticText Best Restaurants In
	StaticText Lagos
	list
		listitem
			link Restaurants in Lekki, url='https://heyfood.africa/places/best-restaurants-in-lekki'
		listitem
			link Restaurants in Ikeja, url='https://heyfood.africa/places/best-restaurants-in-ikeja'
		listitem
			link Restaurants in Victoria Island, url='https://heyfood.africa/places/best-restaurants-in-victoria-island'
		listitem
			link Restaurants in Ikoyi, url='https://heyfood.africa/places/best-restaurants-in-ikoyi'
		listitem
			link Restaurants in Oniru, url='https://heyfood.africa/places/best-restaurants-in-oniru'
	heading Cuisines near me
	list
		listitem
			link Rice near me, url='https://heyfood.africa/places/ibadan/rice-near-me'
		listitem
			link Ice Cream near me, url='https://heyfood.africa/places/ibadan/ice-cream-near-me'
		listitem
			link Grocery near me, url='https://heyfood.africa/places/ibadan/grocery-near-me'
		listitem
			link Chicken near me, url='https://heyfood.africa/places/ibadan/chicken-near-me'
		listitem
			link Shawarma near me, url='https://heyfood.africa/places/ibadan/shawarma-near-me'
		listitem
			link Spaghetti near me, url='https://heyfood.africa/places/ibadan/spaghetti-near-me'
		listitem
			link Small Chops near me, url='https://heyfood.africa/places/ibadan/small-chops-near-me'
		listitem
			link Chinese near me, url='https://heyfood.africa/places/ibadan/chinese-near-me'
		listitem
			link Pizza near me, url='https://heyfood.africa/places/ibadan/pizza-near-me'
		listitem
			link Soup bowl near me, url='https://heyfood.africa/places/ibadan/soup-bowl-near-me'
		listitem
			link Grills near me, url='https://heyfood.africa/places/ibadan/grills-near-me'
		listitem
			link Fastfood near me, url='https://heyfood.africa/places/ibadan/fastfood-near-me'
	image heyfood-logo, url='https://heyfood.africa/icons/new/logo-long.svg'
	paragraph
		StaticText Your food delivered within minutes.
	link apple-logo App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	link google-play-logo Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	heading Get To Know Us
	link About Us, url='https://heyfood.medium.com/introducing-heyfood-7037d5a5f8c7?source=user_profile---------6----------------------------'
	link LinkedIn, url='https://www.linkedin.com/company/heyfood'
	link Blog, url='https://heyfood.medium.com/'
	heading Let Us Help You
	link Support, url='mailto:%20heypayapp@gmail.com'
	link FAQs, url='https://heyfood.africa/'
	link Restaurants Near Me, url='https://heyfood.africa/stores'
	heading Doing Business
	link Become a driver, url='https://heyfood.africa/driver'
	link Become a partner restaurant, url='https://heyfood.africa/merchant'
	image qr-code, url='https://heyfood.africa/images/new/download-qr.svg'
	link https://facebook.com/heyfoodNg, url='https://facebook.com/heyfoodNg'
		image https://facebook.com/heyfoodNg, url='https://heyfood.africa/icons/new/facebook.svg'
	link https://twitter.com/HeyfoodAfrica, url='https://twitter.com/HeyfoodAfrica'
		image https://twitter.com/HeyfoodAfrica, url='https://heyfood.africa/icons/new/twitter.svg'
	link https://www.instagram.com/heyfood.africa, url='https://www.instagram.com/heyfood.africa'
		image https://www.instagram.com/heyfood.africa, url='https://heyfood.africa/icons/new/instagram.svg'
	link https://www.linkedin.com/company/heyfood/, url='https://www.linkedin.com/company/heyfood/'
		image https://www.linkedin.com/company/heyfood/, url='https://heyfood.africa/icons/new/linkedin.svg'
	link Terms Of Service, url='https://heyfood.africa/terms'
	link Privacy Policy, url='https://heyfood.africa/privacy'
	StaticText © 2025 Hey Technologies Limited. All rights reserved
	alert, atomic
	generic
		[b] dialog Intercom live chat, center=(44,1036), modal=False, title=Intercom live chat
```
</details>



```
RootWebArea Heyfood, focused, url='https://heyfood.africa/'
	[77] link heyfood-logo-long, center=(154,41), url='https://heyfood.africa/'
		image heyfood-logo-long, url='https://heyfood.africa/icons/new/logo-long.svg'
	[80] button Sign In, center=(1654,41), type=button
	[83] button Sign Up, center=(1779,41), type=button
```
<details><summary>Show more</summary>

```
	heading Your food delivered within minutes.
	image location-pin, url='https://heyfood.africa/icons/new/location-pin.svg'
	[96] textbox Enter delivery address value='Ibadan', center=(353,492), contenteditable=True, focused, type=text
	StaticText *Search for your location and select from the suggestions
	StaticText No result
	[98] button Find restaurants, center=(713,492), type=button
	image hero-image, url='https://heyfood.africa/images/new/hero-side.svg'
	[105] link apple-logo App Store, center=(1476,724), inner_text=App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	[111] link google-play-logo Play Store, center=(1663,724), inner_text=Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	image Try The App, url='https://heyfood.africa/images/new/first-sales-1.svg'
	heading Try The App
	paragraph
		StaticText Discover the best restaurants and vendors near you all in one place
	link Get Started, url='https://heyfood.africa/download'
	image Become A Merchant, url='https://heyfood.africa/images/new/first-sales-2.svg'
	heading Become A Merchant
	paragraph
		StaticText Grow your business and increase profit by creating an online ordering page
	link Get Started, url='https://heyfood.africa/merchant'
	image Become A Rider, url='https://heyfood.africa/images/new/first-sales-3.svg'
	heading Become A Rider
	paragraph
		StaticText Drive, deliver and earn. Make more money when you become a rider on Heyfood
	link Get Started, url='https://heyfood.africa/driver'
	heading A Variety of Stores to choose from
	paragraph
		StaticText Order food from the best restaurants, local favorites, and online vendors using the app or web.
	link Start Ordering, url='https://heyfood.africa/download'
		button Start Ordering
	image A Variety of Stores to choose from, url='https://heyfood.africa/images/new/second-sales-1.png'
	heading Grow With Heyfood
	paragraph
		StaticText Expand your business and make money with features that make managing and processing orders easier.
	image Order Management, url='https://heyfood.africa/images/new/second-sales-sub-1.svg'
	heading Order Management
	paragraph
		StaticText Receive and manage orders directly from your dashboard.
	image Automatic Payout, url='https://heyfood.africa/images/new/second-sales-sub-2.svg'
	heading Automatic Payout
	paragraph
		StaticText Get paid automatically to your bank account.
	image Dine-In Orders, url='https://heyfood.africa/images/new/second-sales-sub-3.svg'
	heading Dine-In Orders
	paragraph
		StaticText Better in-store dining service with QR Codes
	link Sign up your store, url='https://dashboard.heyfood.africa/signup'
		button Sign up your store
	image Grow With Heyfood, url='https://heyfood.africa/images/new/second-sales-2.png'
	heading Experience the app today!
	link apple-logo App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	link google-play-logo Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	image heyfood-app-demo, url='https://heyfood.africa/images/new/download-app-phone.png'
	heading Cities near me
	link Ibadan, url='https://heyfood.africa/places/ibadan'
	StaticText Top Areas
	list
		listitem
			link Agbowo, url='https://heyfood.africa/places/agbowo'
		listitem
			link Akobo, url='https://heyfood.africa/places/akobo'
		listitem
			link Ashi, url='https://heyfood.africa/places/ashi'
		listitem
			link Basorun, url='https://heyfood.africa/places/basorun'
		listitem
			link Bodija, url='https://heyfood.africa/places/bodija'
		listitem
			link Mokola, url='https://heyfood.africa/places/mokola'
		listitem
			link Ojoo, url='https://heyfood.africa/places/ojoo'
		listitem
			link Orogun, url='https://heyfood.africa/places/orogun'
		listitem
			link Barika, url='https://heyfood.africa/places/barika'
		listitem
			link Samonda, url='https://heyfood.africa/places/samonda'
		listitem
			link Sango, url='https://heyfood.africa/places/sango'
		listitem
			link Eleyele, url='https://heyfood.africa/places/eleyele'
		listitem
			link Ologuneru, url='https://heyfood.africa/places/ologuneru'
		listitem
			link Moniya, url='https://heyfood.africa/places/moniya'
		listitem
			link Agodi, url='https://heyfood.africa/places/agodi'
		listitem
			link Agodi-gate, url='https://heyfood.africa/places/agodi-gate'
		listitem
			link University of Ibadan, url='https://heyfood.africa/places/university-of-ibadan'
		listitem
			link UCH, url='https://heyfood.africa/places/uch'
		listitem
			link Dugbe, url='https://heyfood.africa/places/dugbe'
		listitem
			link Onireke, url='https://heyfood.africa/places/onireke'
	StaticText Best Restaurants In
	StaticText Ibadan
	list
		listitem
			link Restaurants in Agbowo, url='https://heyfood.africa/places/best-restaurants-in-agbowo'
		listitem
			link Restaurants in Akobo, url='https://heyfood.africa/places/best-restaurants-in-akobo'
		listitem
			link Restaurants in Ashi, url='https://heyfood.africa/places/best-restaurants-in-ashi'
		listitem
			link Restaurants in Basorun, url='https://heyfood.africa/places/best-restaurants-in-basorun'
		listitem
			link Restaurants in Bodija, url='https://heyfood.africa/places/best-restaurants-in-bodija'
		listitem
			link Restaurants in Mokola, url='https://heyfood.africa/places/best-restaurants-in-mokola'
		listitem
			link Restaurants in Ojoo, url='https://heyfood.africa/places/best-restaurants-in-ojoo'
		listitem
			link Restaurants in Orogun, url='https://heyfood.africa/places/best-restaurants-in-orogun'
		listitem
			link Restaurants in Barika, url='https://heyfood.africa/places/best-restaurants-in-barika'
		listitem
			link Restaurants in Samonda, url='https://heyfood.africa/places/best-restaurants-in-samonda'
		listitem
			link Restaurants in Sango, url='https://heyfood.africa/places/best-restaurants-in-sango'
		listitem
			link Restaurants in Eleyele, url='https://heyfood.africa/places/best-restaurants-in-eleyele'
		listitem
			link Restaurants in Ologuneru, url='https://heyfood.africa/places/best-restaurants-in-ologuneru'
		listitem
			link Restaurants in Moniya, url='https://heyfood.africa/places/best-restaurants-in-moniya'
		listitem
			link Restaurants in Agodi, url='https://heyfood.africa/places/best-restaurants-in-agodi'
		listitem
			link Restaurants in Agodi-gate, url='https://heyfood.africa/places/best-restaurants-in-agodi-gate'
		listitem
			link Restaurants in University of Ibadan, url='https://heyfood.africa/places/best-restaurants-in-university-of-ibadan'
		listitem
			link Restaurants in UCH, url='https://heyfood.africa/places/best-restaurants-in-uch'
		listitem
			link Restaurants in Dugbe, url='https://heyfood.africa/places/best-restaurants-in-dugbe'
		listitem
			link Restaurants in Onireke, url='https://heyfood.africa/places/best-restaurants-in-onireke'
	link Abuja, url='https://heyfood.africa/places/abuja'
	StaticText Top Areas
	list
		listitem
			link Wuse, url='https://heyfood.africa/places/wuse'
		listitem
			link Adetokunbo, url='https://heyfood.africa/places/adetokunbo'
		listitem
			link Aminu Kano Crescent, url='https://heyfood.africa/places/aminu-kano-crescent'
		listitem
			link Garki, url='https://heyfood.africa/places/garki'
		listitem
			link Gwarinpa, url='https://heyfood.africa/places/gwarinpa'
		listitem
			link Wuye, url='https://heyfood.africa/places/wuye'
		listitem
			link Utako, url='https://heyfood.africa/places/utako'
		listitem
			link Area 11, url='https://heyfood.africa/places/area-11'
	StaticText Best Restaurants In
	StaticText Abuja
	list
		listitem
			link Restaurants in Wuse, url='https://heyfood.africa/places/best-restaurants-in-wuse'
		listitem
			link Restaurants in Adetokunbo, url='https://heyfood.africa/places/best-restaurants-in-adetokunbo'
		listitem
			link Restaurants in Aminu Kano Crescent, url='https://heyfood.africa/places/best-restaurants-in-aminu-kano-crescent'
		listitem
			link Restaurants in Garki, url='https://heyfood.africa/places/best-restaurants-in-garki'
		listitem
			link Restaurants in Gwarinpa, url='https://heyfood.africa/places/best-restaurants-in-gwarinpa'
		listitem
			link Restaurants in Wuye, url='https://heyfood.africa/places/best-restaurants-in-wuye'
		listitem
			link Restaurants in Utako, url='https://heyfood.africa/places/best-restaurants-in-utako'
		listitem
			link Restaurants in Area 11, url='https://heyfood.africa/places/best-restaurants-in-area-11'
	link Lagos, url='https://heyfood.africa/places/lagos'
	StaticText Top Areas
	list
		listitem
			link Lekki, url='https://heyfood.africa/places/lekki'
		listitem
			link Ikeja, url='https://heyfood.africa/places/ikeja'
		listitem
			link Victoria Island, url='https://heyfood.africa/places/victoria-island'
		listitem
			link Ikoyi, url='https://heyfood.africa/places/ikoyi'
		listitem
			link Oniru, url='https://heyfood.africa/places/oniru'
	StaticText Best Restaurants In
	StaticText Lagos
	list
		listitem
			link Restaurants in Lekki, url='https://heyfood.africa/places/best-restaurants-in-lekki'
		listitem
			link Restaurants in Ikeja, url='https://heyfood.africa/places/best-restaurants-in-ikeja'
		listitem
			link Restaurants in Victoria Island, url='https://heyfood.africa/places/best-restaurants-in-victoria-island'
		listitem
			link Restaurants in Ikoyi, url='https://heyfood.africa/places/best-restaurants-in-ikoyi'
		listitem
			link Restaurants in Oniru, url='https://heyfood.africa/places/best-restaurants-in-oniru'
	heading Cuisines near me
	list
		listitem
			link Rice near me, url='https://heyfood.africa/places/ibadan/rice-near-me'
		listitem
			link Ice Cream near me, url='https://heyfood.africa/places/ibadan/ice-cream-near-me'
		listitem
			link Grocery near me, url='https://heyfood.africa/places/ibadan/grocery-near-me'
		listitem
			link Chicken near me, url='https://heyfood.africa/places/ibadan/chicken-near-me'
		listitem
			link Shawarma near me, url='https://heyfood.africa/places/ibadan/shawarma-near-me'
		listitem
			link Spaghetti near me, url='https://heyfood.africa/places/ibadan/spaghetti-near-me'
		listitem
			link Small Chops near me, url='https://heyfood.africa/places/ibadan/small-chops-near-me'
		listitem
			link Chinese near me, url='https://heyfood.africa/places/ibadan/chinese-near-me'
		listitem
			link Pizza near me, url='https://heyfood.africa/places/ibadan/pizza-near-me'
		listitem
			link Soup bowl near me, url='https://heyfood.africa/places/ibadan/soup-bowl-near-me'
		listitem
			link Grills near me, url='https://heyfood.africa/places/ibadan/grills-near-me'
		listitem
			link Fastfood near me, url='https://heyfood.africa/places/ibadan/fastfood-near-me'
	image heyfood-logo, url='https://heyfood.africa/icons/new/logo-long.svg'
	paragraph
		StaticText Your food delivered within minutes.
	link apple-logo App Store, url='https://apps.apple.com/ng/app/heyfood-food-delivery/id1572221178'
		button apple-logo App Store
			image apple-logo, url='https://heyfood.africa/icons/new/apple-logo.svg'
	link google-play-logo Play Store, url='https://play.google.com/store/apps/details?id=xyz.heypay.heyfood'
		button google-play-logo Play Store
			image google-play-logo, url='https://heyfood.africa/icons/new/google-play-logo.svg'
	heading Get To Know Us
	link About Us, url='https://heyfood.medium.com/introducing-heyfood-7037d5a5f8c7?source=user_profile---------6----------------------------'
	link LinkedIn, url='https://www.linkedin.com/company/heyfood'
	link Blog, url='https://heyfood.medium.com/'
	heading Let Us Help You
	link Support, url='mailto:%20heypayapp@gmail.com'
	link FAQs, url='https://heyfood.africa/'
	link Restaurants Near Me, url='https://heyfood.africa/stores'
	heading Doing Business
	link Become a driver, url='https://heyfood.africa/driver'
	link Become a partner restaurant, url='https://heyfood.africa/merchant'
	image qr-code, url='https://heyfood.africa/images/new/download-qr.svg'
	link https://facebook.com/heyfoodNg, url='https://facebook.com/heyfoodNg'
		image https://facebook.com/heyfoodNg, url='https://heyfood.africa/icons/new/facebook.svg'
	link https://twitter.com/HeyfoodAfrica, url='https://twitter.com/HeyfoodAfrica'
		image https://twitter.com/HeyfoodAfrica, url='https://heyfood.africa/icons/new/twitter.svg'
	link https://www.instagram.com/heyfood.africa, url='https://www.instagram.com/heyfood.africa'
		image https://www.instagram.com/heyfood.africa, url='https://heyfood.africa/icons/new/instagram.svg'
	link https://www.linkedin.com/company/heyfood/, url='https://www.linkedin.com/company/heyfood/'
		image https://www.linkedin.com/company/heyfood/, url='https://heyfood.africa/icons/new/linkedin.svg'
	link Terms Of Service, url='https://heyfood.africa/terms'
	link Privacy Policy, url='https://heyfood.africa/privacy'
	StaticText © 2025 Hey Technologies Limited. All rights reserved
	alert, atomic
	generic
		[b] dialog Intercom live chat, center=(44,1036), modal=False, title=Intercom live chat
```
</details>

**Reasoning for action:** By clicking on the 'Find restaurants' button, I am sending a query to the Heyfood system to search for restaurants that deliver to the specified location, Ibadan. This action is essential in advancing the user's task of discovering dining options available for delivery in their area.

**Action:** click(98) # Click on the 'Find restaurants' button to search for available restaurants in Ibadan.

**Change Description:** After clicking the 'Find restaurants' button, the search results indicate 'No result' for the specified delivery address 'Ibadan', and a new static text prompt appears stating, 'Search for your location and select from the suggestions'.

**Screenshot before:****Screenshot after:**---


# Task

**Explore Olympian Motors Vehicle Models**

As a potential car buyer,
I learn about different electric vehicle models offered by Olympian Motors,
so that I can make an informed decision about which vehicle to consider for purchase.

**Success definition:** Given I am on the Olympian Motors website
When I click on the Company link to learn more about Olympian Motors vehicles and then explore the Model 01 and Model 84
Then I should see detailed information, features, and images related to both the Model 01 and Model 84.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://olympianmotors.com/

https://olympianmotors.com/company

**Content (before/after):** 

```
RootWebArea Olympian Motors | Experience-First Electric Vehicles, focused, url='https://olympianmotors.com/'
	navigation
		list
			[81] link Olympian Motors Logo, center=(132,32), url='https://olympianmotors.com/'
				image Olympian Motors Logo, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Folympian-logo.42e47ff7.png&w=256&q=75'
```
<details><summary>Show more</summary>

```
		list
			list
				[86] link Company, center=(802,32), url='https://olympianmotors.com/company'
				[88] link Model 01, center=(902,32), url='https://olympianmotors.com/model-01'
				[90] link Model 84, center=(1002,32), url='https://olympianmotors.com/model-84'
				[92] link Olympus OS, center=(1116,32), url='https://olympianmotors.com/olympus-os'
		list
			[95] link Test Drive, center=(1641,32), inner_text=Order, url='https://olympianmotors.com/order'
				button Test Drive
					StaticText Order
			[99] link Test Drive, center=(1712,32), url='https://olympianmotors.com/test-drive'
				button Test Drive
			listitem
				[104] link Invest, center=(1818,32), url='https://olympianmotors.com/invest'
					button Invest
	main
		heading Electric. Aesthetic. Modular.
			paragraph
			paragraph
			paragraph
		list
			listitem
				StaticText Olympian Motors introduces next-gen electric vehicles for the 21st century.
			listitem
				StaticText Our timeless and bold designs are built with an open, modular electric vehicle architecture.
			listitem
				StaticText Olympian is creating an efficient, sustainable, and aesthetic future for all. With our novel modular vehicles, we are pioneering changes in the American automotive industry.
		[121] video, center=(1205,620)
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fhome%2Fo-zero.jpg&w=1920&q=75'
		image Aesthetics Bridge, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fbridge.jpg&w=1920&q=50'
		heading Our Priorities
		list
			listitem
				ListMarker •
				paragraph
					StaticText Experience
					StaticText over cliché.
			listitem
				ListMarker •
				paragraph
					StaticText Aesthetics
					StaticText over mundane designs.
			listitem
				ListMarker •
				paragraph
					StaticText Simplicity
					StaticText over invasive display screens.
			listitem
				ListMarker •
				paragraph
					StaticText Steel and wood
					StaticText over plastic and chemicals.
			listitem
				ListMarker •
				paragraph
					StaticText Silence
					StaticText over noise.
		image Olympian Model 01 and Model 84, url='https://olympianmotors.com/images/both-model-grad.png'
		paragraph
			StaticText Timeless cars,
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Ffeatures%2FModel-01-sea.jpg&w=1920&q=75'
		paragraph
			StaticText Endless journeys.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Ffeatures%2Foceanside_white_m84.jpg&w=1920&q=75'
		paragraph
			StaticText Away from distractions,
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Ffeatures%2Finterior.png&w=1920&q=75'
		paragraph
			StaticText Experience and feel more with Olympian.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Ffeatures%2Fmodel_01_white_sunset.png&w=1920&q=75'
		paragraph
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Ffeatures%2Fsf_model84.jpg&w=1920&q=75'
		paragraph
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Ffeatures%2Fevent_truck.jpg&w=1920&q=75'
		heading In The News
		link, url='https://olympianmotors.com/press'
			image, url='https://olympianmotors.com/images/invest/in_the_news/bloomberg.svg'
		link, url='https://olympianmotors.com/press'
			image, url='https://olympianmotors.com/images/invest/in_the_news/lat.svg'
		link, url='https://olympianmotors.com/press'
			image, url='https://olympianmotors.com/images/invest/in_the_news/yc.svg'
		link, url='https://olympianmotors.com/press'
			image, url='https://olympianmotors.com/images/invest/in_the_news/ft.svg'
		link, url='https://olympianmotors.com/press'
			image, url='https://olympianmotors.com/images/invest/in_the_news/yf.svg'
		link, url='https://olympianmotors.com/press'
			image, url='https://olympianmotors.com/images/invest/in_the_news/matlab.svg'
		link, url='https://olympianmotors.com/press'
			image, url='https://olympianmotors.com/images/invest/in_the_news/tbt.svg'
		link, url='https://olympianmotors.com/press'
			image, url='https://olympianmotors.com/images/invest/in_the_news/ae.svg'
		image Olympian Model 84, url='https://olympianmotors.com/images/version/model84_blue.png'
		heading Model 84
		heading The Founder Edition 2025
		list
			listitem
				ListMarker •
				StaticText Base Price: $80K
			listitem
				ListMarker •
				StaticText Segment: SUV
			listitem
				ListMarker •
				StaticText *Range: 205-335 miles
			listitem
				ListMarker •
				StaticText System: Olympus OS x Android
			listitem
				ListMarker •
				StaticText Available for purchase: CA, NY, FL, TX
		link Order Now, url='https://olympianmotors.com/model-84/preorder'
			button Order Now
		link Discover, url='https://olympianmotors.com/model-84'
			button Discover
		image Model O1 (The Founder Edition 2025), url='https://olympianmotors.com/images/version/model01_new.png'
		heading Model O1
		heading The Founder Edition 2025
		list
			listitem
				ListMarker •
				StaticText Base Price: $80K
			listitem
				ListMarker •
				StaticText Segment: Sedan
			listitem
				ListMarker •
				StaticText *Range: 210-305 miles
			listitem
				ListMarker •
				StaticText System: Olympus x Android
			listitem
				ListMarker •
				StaticText Available for purchase: CA, NY, FL, TX
		link Reserve Now, url='https://olympianmotors.com/model-01/preorder'
			button Reserve Now
		link Discover, url='https://olympianmotors.com/model-01'
			button Discover
		image Olympian Motors EV Platform, url='https://olympianmotors.com/images/homepage-versions/olympus-ev-platform.jpg'
		heading Olympian EV Platform
		heading
		list
			listitem
				ListMarker •
				StaticText Base Price: $50K
			listitem
				ListMarker •
				StaticText Segment: Open, Modular EV Platform
			listitem
				ListMarker •
				StaticText *Range: 205-335 miles
			listitem
				ListMarker •
				StaticText System: Olympus OS x Android
			listitem
				ListMarker •
				StaticText Available for purchase: All 50 U.S. states and Canada
		link Order Now, url='https://olympianmotors.com/ev-platform/preorder'
			button Order Now
		link Discover, url='https://olympianmotors.com/olympus-os'
			button Discover
		paragraph
			StaticText For any further questions or local partnership, distribution/dealer questions, please contact us at
			link sales@olympianmotors.com, url='mailto:sales@olympianmotors.com'
			StaticText .
		paragraph
			StaticText For inquiries about local partnerships, distributors/dealers, or service centers, please contact
			link jv@olympianmotors.com, url='mailto:JV@olympianmotors.com'
			StaticText .
		paragraph
			StaticText Olympian MVDS:
		paragraph
			StaticText Modular Vehicle Drivetrain System
		heading Open, modular EV configuration.
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodular%2Fmodel-84%2Fmodel84_seq_0.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodular%2Fmodel-84%2Fmodel84_seq_1.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodular%2Fmodel-84%2Fmodel84_seq_2.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodular%2Fmodel-84%2Fmodel84_seq_3.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodular%2Fmodel-84%2Fmodel84_seq_4.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodular%2Fmodel-84%2Fmodel84_seq_5.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodular%2Fmodel-84%2Fmodel84_seq_5.png&w=1920&q=75'
		heading Modular Vehicle Architecture
		paragraph
			StaticText Bringing simplicity to vehicle, hardware and software architecture.
		heading Open Vehicle Platform and Operating System
		paragraph
			StaticText Olympian provides an open, standardized. unified vehicle protocol with our tech partners.
		heading Decentralized Production
		paragraph
			StaticText Our modular approach enables a decentralized network of manufacturing hubs across the U.S.
		heading Configurable In-Vehicle Setup
		paragraph
			StaticText Flexible cockpit, interior and seating arrangements for different applications and use cases.
		heading Reduced Tooling & Machinery Costs
		paragraph
			StaticText Olympian's modular body topology changes the conventional car manufacturing process.
		heading Model 84
		paragraph
			StaticText Simple, modular and beautiful. Available to purchase in California and New York.
		heading
		paragraph
		heading Olympus Consortium
		paragraph
			StaticText We are growing our consortium with new partners, suppliers, joint ventures and distributors around the world.
		image Olympus OS, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Folympus-os-models.586f10ea.png&w=640&q=75'
		heading Olympus Developer Program
		image, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FOlympus-Developer-Program.bf62f0a0.jpg&w=640&q=75'
		paragraph
			StaticText Tier-1/Tier-2 suppliers, tech & data partners
		heading Olympus Joint Venture Program
		image, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FOlympus-Joint-Venture-Program.b8d0afdf.jpg&w=640&q=75'
		paragraph
			StaticText Regional joint ventures, partners & distributors
		heading Inspired by nature.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fhome%2Fmodel-01-black.jpg&w=1920&q=75'
		heading Frequently Asked Questions
		heading Is it electric?
			button Is it electric?, expanded=False
		separator, orientation='horizontal'
		heading How can I charge my Olympian vehicle?
			button How can I charge my Olympian vehicle?, expanded=False
		separator, orientation='horizontal'
		heading So, can I charge an Olympian at a Tesla charging station?
			button So, can I charge an Olympian at a Tesla charging station?, expanded=False
		separator, orientation='horizontal'
		heading How can I purchase?
			button How can I purchase?, expanded=False
		separator, orientation='horizontal'
		heading Can I purchase Olympian cars in my area?
			button Can I purchase Olympian cars in my area?, expanded=False
		separator, orientation='horizontal'
		heading When is the first planned delivery?
			button When is the first planned delivery?, expanded=False
		separator, orientation='horizontal'
		heading Do you accept new investors?
			button Do you accept new investors?, expanded=False
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fsubscribe%2Fmodel01-dark.png&w=1920&q=75'
		heading Subscribe To Olympian Motors Newsletter
		paragraph
			StaticText To receive strategic company updates, upcoming
			StaticText launch dates,
			StaticText test-drive and Olympian Demo Day events.
		textbox Enter your email, required
		button Subscribe
		paragraph
			StaticText Your email is safe with us, we don't spam.
		image Logo Olympian Motors, url='https://olympianmotors.com/_next/static/media/logo.1fb8db2a.svg'
		paragraph
			StaticText Follow us
		link, url='https://twitter.com/olympianmotors'
			image
		link, url='https://www.instagram.com/olympianmotors/'
			image
		link, url='https://www.tiktok.com/@olympianmotors'
			image
		link, url='https://www.linkedin.com/company/olympian-motors/'
			image
		link Company, url='https://olympianmotors.com/company'
		link Careers, url='https://olympianmotors.com/careers'
		link Order, url='https://olympianmotors.com/order'
		link Contact, url='https://olympianmotors.com/contact'
		link Press, url='https://olympianmotors.com/press'
		paragraph
			StaticText OLYMPIAN MOTORS ©
			StaticText 2025
	alert, atomic
```
</details>



```
RootWebArea Our Company - Olympian Motors, focused, url='https://olympianmotors.com/company'
	navigation
		list
			[81] link Olympian Motors Logo, center=(132,32), url='https://olympianmotors.com/'
				image Olympian Motors Logo, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Folympian-logo.42e47ff7.png&w=256&q=75'
```
<details><summary>Show more</summary>

```
		list
			list
				[86] link Company, center=(802,32), focused, url='https://olympianmotors.com/company'
				[88] link Model 01, center=(902,32), url='https://olympianmotors.com/model-01'
				[90] link Model 84, center=(1002,32), url='https://olympianmotors.com/model-84'
				[92] link Olympus OS, center=(1116,32), url='https://olympianmotors.com/olympus-os'
		list
			[95] link Test Drive, center=(1641,32), inner_text=Order, url='https://olympianmotors.com/order'
				button Test Drive
					StaticText Order
			[99] link Test Drive, center=(1712,32), url='https://olympianmotors.com/test-drive'
				button Test Drive
			listitem
				[104] link Invest, center=(1818,32), url='https://olympianmotors.com/invest'
					button Invest
	main
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2Fhero-image.jpg&w=1920&q=90'
		heading The Olympian Journey
		paragraph
			StaticText Olympian Motors is an American automotive and technology company. Olympian was founded in 2021 as New York’s first electric vehicle manufacturer.
		paragraph
			StaticText We build timeless electric vehicles that change the rules of the automotive industry.
		paragraph
			StaticText Olympian vehicles are dedicated to entrepreneurs, scientists, artists, and great minds.
		paragraph
			StaticText As of today, we are operating across our Brooklyn Navy Yard, NY, Malibu, CA, and Detroit, MI locations.
		image Aesthetics Bridge, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fbridge.jpg&w=1920&q=50'
		heading Our Priorities
		list
			listitem
				ListMarker •
				paragraph
					StaticText Experience
					StaticText over cliché.
			listitem
				ListMarker •
				paragraph
					StaticText Aesthetics
					StaticText over mundane designs.
			listitem
				ListMarker •
				paragraph
					StaticText Simplicity
					StaticText over invasive display screens.
			listitem
				ListMarker •
				paragraph
					StaticText Steel and wood
					StaticText over plastic and chemicals.
			listitem
				ListMarker •
				paragraph
					StaticText Silence
					StaticText over noise.
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2Fexperience.jpg&w=1920&q=75'
		heading Experience-first electric cars
		paragraph
			StaticText We bring aesthetics, color and lifestyle back.
		paragraph
			StaticText Olympian blends timeless design, minimalism and nature.
		paragraph
			StaticText Experience Olympian: Drive steel, touch wood, and protect nature.
		heading Our Vehicles
		image Olympian Model 84, url='https://olympianmotors.com/images/version/model84_blue.png'
		heading Model 84
		heading The Founder Edition 2025
		list
			listitem
				ListMarker •
				StaticText Base Price: $80K
			listitem
				ListMarker •
				StaticText Segment: SUV
			listitem
				ListMarker •
				StaticText *Range: 205-335 miles
			listitem
				ListMarker •
				StaticText System: Olympus OS x Android
			listitem
				ListMarker •
				StaticText Available for purchase: CA, NY, FL, TX
		link Order Now, url='https://olympianmotors.com/model-84/preorder'
			button Order Now
		link Discover, url='https://olympianmotors.com/model-84'
			button Discover
		image Model O1 (The Founder Edition 2025), url='https://olympianmotors.com/images/version/model01_new.png'
		heading Model O1
		heading The Founder Edition 2025
		list
			listitem
				ListMarker •
				StaticText Base Price: $80K
			listitem
				ListMarker •
				StaticText Segment: Sedan
			listitem
				ListMarker •
				StaticText *Range: 210-305 miles
			listitem
				ListMarker •
				StaticText System: Olympus x Android
			listitem
				ListMarker •
				StaticText Available for purchase: CA, NY, FL, TX
		link Reserve Now, url='https://olympianmotors.com/model-01/preorder'
			button Reserve Now
		link Discover, url='https://olympianmotors.com/model-01'
			button Discover
		image Olympian Motors EV Platform, url='https://olympianmotors.com/images/version/olympus-ev-platform.png'
		heading Olympian EV Platform
		heading
		list
			listitem
				ListMarker •
				StaticText Base Price: $50K
			listitem
				ListMarker •
				StaticText Segment: Open, Modular EV Platform
			listitem
				ListMarker •
				StaticText *Range: 205-335 miles
			listitem
				ListMarker •
				StaticText System: Olympus OS x Android
			listitem
				ListMarker •
				StaticText Available for purchase: All 50 U.S. states and Canada
		link Order Now, url='https://olympianmotors.com/ev-platform/preorder'
			button Order Now
		link Discover, url='https://olympianmotors.com/olympus-os'
			button Discover
		image Centaru VAN, url='https://olympianmotors.com/images/version/centaur.png'
		heading Centaur
		heading
		list
			listitem
				ListMarker •
				StaticText Base Price: $70K
			listitem
				ListMarker •
				StaticText Segment: VAN
			listitem
				ListMarker •
				StaticText *Range: 205-335 miles
			listitem
				ListMarker •
				StaticText System: Olympus OS x Android
			listitem
				ListMarker •
				StaticText Available for purchase: In 2025
		link Reserve Now, url='https://olympianmotors.com/centaur/preorder'
			button Reserve Now
		heading Powered by 'Olympus' Operating System
		paragraph
			StaticText Model O1 and Model 84 share the same modular vehicle platform, powered by Olympus Operating System.
			StaticText Olympus OS enables a fully-modular vehicle architecture and provides a standardized integration protocol for our modular manufacturing and supply-chain partners.
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2FMVDS%2FMVDS_3.jpeg&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2FMVDS%2FMVDS_1.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2FMVDS%2FMVDS_2.png&w=1920&q=75'
		heading Model 84 Powered by Olympus OS.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2Fnvidia-inception.png&w=1920&q=75'
		heading Sustainability
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2Fsustainability.png&w=1920&q=75'
		paragraph
			StaticText Olympian Motors is dedicated to creating the most environmentally responsible vehicles of the 21st century.
		paragraph
			StaticText SUSTAINABLE MATERIALS: We prioritize using post-industrial recycled (PIR) materials, carbon-sequestered polyketone, bio-based polyurethane in Olympian vehicles.
		paragraph
			StaticText SUPERIOR BATTERY EFFICIENCY: Our commitment to sustainability is reflected in our highly efficient battery consumption rates in urban areas. Olympian O1 prototypes have achieved superior miles/kwh battery efficiency compared to existing electric vehicles such as the Tesla Model 3 (2022) and Rivian Model R1T (2022).
		paragraph
			StaticText We are leading the industry towards a cleaner, greener, sustainable future.
		heading Nature and Minimalism
		paragraph
			StaticText Inspired by the traditional Japanese philosophy of wabi-sabi, we diligently combine nature with minimalism in Olympian electric cars.
		paragraph
		paragraph
			StaticText Our company collaborates with exclusive suppliers and uses cutting-edge material technology to provide a unique driving and in-vehicle experience.
		paragraph
			StaticText We let Olympian drivers and passengers feel a sense of serenity in today's fast-paced world. Because less is more.
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2Fnatureminimilism.jpg&w=1920&q=75'
		heading Our Bases
		paragraph
			StaticText Brooklyn Navy Yard, New York
		image Brooklyn Navy Yard, New York, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2FBrooklyn.png&w=1920&q=75'
		paragraph
			StaticText Los Angeles, California
		image Michigan Central, Detroit (Q4/2023), url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2FCalifornia.png&w=1920&q=75'
		paragraph
			StaticText Detroit, Michigan
		image Michigan Central, Detroit (Q4/2023), url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2FDetroit_new.png&w=1920&q=75'
		heading Our Team
		StaticText We are a team of engineers, builders and makers.
		image Eren, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fteams%2Feren.png&w=1920&q=75'
		paragraph
			StaticText Eren
		paragraph
			StaticText CEO & Chief Engineer
		image Eren, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fteams%2Fjohn.jpg&w=1920&q=75'
		paragraph
			StaticText John
		paragraph
			StaticText Head of Olympus OS
		image Adam, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fteams%2Fjasmine.jpg&w=1920&q=75'
		paragraph
			StaticText Jasmine
		paragraph
			StaticText Ops & Strategy
		image Zhaolong, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fteams%2FZhaolong.jpg&w=1920&q=75'
		paragraph
			StaticText Zhaolong
		paragraph
			StaticText Cockpit & Infotainment
		image Adam, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fteams%2FAdam.jpg&w=1920&q=75'
		paragraph
			StaticText Adam
		paragraph
			StaticText Head of Vehicle Engineering
		image Bikash, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fteams%2Fbikash.jpg&w=1920&q=75'
		paragraph
			StaticText Bikash
		paragraph
			StaticText Cloud & Data
		image Bryan, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fteams%2Fbryan.jpg&w=1920&q=75'
		paragraph
			StaticText Bryan
		paragraph
			StaticText Ops & Marketing
		image Henry, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fteams%2Fhenry.jpg&w=1920&q=75'
		paragraph
			StaticText Henry
		paragraph
			StaticText Technical Advisor
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2FgallaryImages%2Fcrowd.jpg&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2FgallaryImages%2Fnvidia-inception.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2FgallaryImages%2Finvest-gallary-2.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2FgallaryImages%2Finvest-gallery-3-new.jpg&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2FgallaryImages%2Finvest-gallary-4.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2FgallaryImages%2Finvest-gallary-5.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2FgallaryImages%2Finvest-gallary-6.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2FgallaryImages%2Finvest-gallary-7.png&w=1920&q=75'
		heading Featured in Media
		link Nvidia's Advanced AI Tech Powers Olympian Motors' New Electric Vehicle Platform December 24, 2024, url='https://finance.yahoo.com/news/nvidias-advanced-ai-tech-powers-115401009.html'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Fyfnvidia.jpeg&w=640&q=75'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Flogo%2FYahoo.png&w=640&q=75'
			paragraph
			paragraph
		link Olympian Motors and NVIDIA Pioneer the First AI-Powered EV Platforms December 23, 2024, url='https://www.globenewswire.com/news-release/2024/12/24/3001535/0/en/Olympian-Motors-and-NVIDIA-Pioneer-the-First-AI-Powered-EV-Platforms.html'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Fgn.jpeg&w=640&q=75'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Flogo%2Fglobenewswire.jpeg&w=640&q=75'
			paragraph
			paragraph
		link Olympian Motors Is Making Minimalist EVs for Drivers Sick of Screens March 2, 2024, url='https://www.bloomberg.com/news/articles/2024-03-02/olympian-motors-is-making-evs-for-drivers-sick-of-screens?embedded-checkout=true'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2FBloomberg.jpg&w=640&q=75'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Flogo%2Fbloomberg.png&w=640&q=75'
			paragraph
			paragraph
		link Manufacturing modular electric vehicles with style Jan 21, 2023, url='https://www.ycombinator.com/companies/olympian-motors'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Fyc.jpg&w=640&q=75'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Flogo%2Fyc.png&w=640&q=75'
			paragraph
			paragraph
		link electric SUV olympian model 84 projects its augmented reality display on windshield Jan 25, 2024, url='https://www.designboom.com/technology/olympian-motors-model-84-electric-suv-augmented-reality-ar-display-01-25-2024/'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Fdesignboom.jpg&w=640&q=75'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Flogo%2Fdesign_boom.png&w=640&q=75'
			paragraph
			paragraph
		link OLYMPIAN MOTORS’ ELECTRIC SUV SLATED FOR Q2 2024 RELEASE, TEASES CYBERTRUCK WITH AR WINDSHIELD AND A RETRO-FUTURISTIC DESIGN Jan 01, 2024, url='https://www.yankodesign.com/2024/01/30/olympian-motors-electric-suv-slated-for-q2-2024-release-teases-cybertruck-with-ar-windshield-and-a-retro-futuristic-design/'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Fyankodesign.jpg&w=640&q=75'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Flogo%2Fyankodesign.png&w=640&q=75'
			paragraph
			paragraph
		button Show more
		image Logo Olympian Motors, url='https://olympianmotors.com/_next/static/media/logo.1fb8db2a.svg'
		paragraph
			StaticText Follow us
		link, url='https://twitter.com/olympianmotors'
			image
		link, url='https://www.instagram.com/olympianmotors/'
			image
		link, url='https://www.tiktok.com/@olympianmotors'
			image
		link, url='https://www.linkedin.com/company/olympian-motors/'
			image
		link Company, url='https://olympianmotors.com/company'
		link Careers, url='https://olympianmotors.com/careers'
		link Order, url='https://olympianmotors.com/order'
		link Contact, url='https://olympianmotors.com/contact'
		link Press, url='https://olympianmotors.com/press'
		paragraph
			StaticText OLYMPIAN MOTORS ©
			StaticText 2025
	alert, atomic
		StaticText Our Company - Olympian Motors
```
</details>

**Reasoning for action:** By clicking on the Company link, I effectively access detailed information about Olympian Motors and their offerings. This step is integral to gathering the necessary information about electric vehicle models, which directly aligns with the user's goal of making an informed decision regarding potential purchases.

**Action:** click(86) # Click on the Company link to learn more about Olympian Motors.

**Change Description:** Upon clicking the 'Company' link, the browser navigated to the 'Our Company' page of Olympian Motors, updating the main content to display detailed information about the company, including its history, priorities, team, and locations, replacing the previous content with a header indicating the current page.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://olympianmotors.com/company

https://olympianmotors.com/model-01

**Content (before/after):** 

```
RootWebArea Our Company - Olympian Motors, focused, url='https://olympianmotors.com/company'
	navigation
		list
			[81] link Olympian Motors Logo, center=(132,32), url='https://olympianmotors.com/'
				image Olympian Motors Logo, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Folympian-logo.42e47ff7.png&w=256&q=75'
```
<details><summary>Show more</summary>

```
		list
			list
				[86] link Company, center=(802,32), focused, url='https://olympianmotors.com/company'
				[88] link Model 01, center=(902,32), url='https://olympianmotors.com/model-01'
				[90] link Model 84, center=(1002,32), url='https://olympianmotors.com/model-84'
				[92] link Olympus OS, center=(1116,32), url='https://olympianmotors.com/olympus-os'
		list
			[95] link Test Drive, center=(1641,32), inner_text=Order, url='https://olympianmotors.com/order'
				button Test Drive
					StaticText Order
			[99] link Test Drive, center=(1712,32), url='https://olympianmotors.com/test-drive'
				button Test Drive
			listitem
				[104] link Invest, center=(1818,32), url='https://olympianmotors.com/invest'
					button Invest
	main
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2Fhero-image.jpg&w=1920&q=90'
		heading The Olympian Journey
		paragraph
			StaticText Olympian Motors is an American automotive and technology company. Olympian was founded in 2021 as New York’s first electric vehicle manufacturer.
		paragraph
			StaticText We build timeless electric vehicles that change the rules of the automotive industry.
		paragraph
			StaticText Olympian vehicles are dedicated to entrepreneurs, scientists, artists, and great minds.
		paragraph
			StaticText As of today, we are operating across our Brooklyn Navy Yard, NY, Malibu, CA, and Detroit, MI locations.
		image Aesthetics Bridge, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fbridge.jpg&w=1920&q=50'
		heading Our Priorities
		list
			listitem
				ListMarker •
				paragraph
					StaticText Experience
					StaticText over cliché.
			listitem
				ListMarker •
				paragraph
					StaticText Aesthetics
					StaticText over mundane designs.
			listitem
				ListMarker •
				paragraph
					StaticText Simplicity
					StaticText over invasive display screens.
			listitem
				ListMarker •
				paragraph
					StaticText Steel and wood
					StaticText over plastic and chemicals.
			listitem
				ListMarker •
				paragraph
					StaticText Silence
					StaticText over noise.
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2Fexperience.jpg&w=1920&q=75'
		heading Experience-first electric cars
		paragraph
			StaticText We bring aesthetics, color and lifestyle back.
		paragraph
			StaticText Olympian blends timeless design, minimalism and nature.
		paragraph
			StaticText Experience Olympian: Drive steel, touch wood, and protect nature.
		heading Our Vehicles
		image Olympian Model 84, url='https://olympianmotors.com/images/version/model84_blue.png'
		heading Model 84
		heading The Founder Edition 2025
		list
			listitem
				ListMarker •
				StaticText Base Price: $80K
			listitem
				ListMarker •
				StaticText Segment: SUV
			listitem
				ListMarker •
				StaticText *Range: 205-335 miles
			listitem
				ListMarker •
				StaticText System: Olympus OS x Android
			listitem
				ListMarker •
				StaticText Available for purchase: CA, NY, FL, TX
		link Order Now, url='https://olympianmotors.com/model-84/preorder'
			button Order Now
		link Discover, url='https://olympianmotors.com/model-84'
			button Discover
		image Model O1 (The Founder Edition 2025), url='https://olympianmotors.com/images/version/model01_new.png'
		heading Model O1
		heading The Founder Edition 2025
		list
			listitem
				ListMarker •
				StaticText Base Price: $80K
			listitem
				ListMarker •
				StaticText Segment: Sedan
			listitem
				ListMarker •
				StaticText *Range: 210-305 miles
			listitem
				ListMarker •
				StaticText System: Olympus x Android
			listitem
				ListMarker •
				StaticText Available for purchase: CA, NY, FL, TX
		link Reserve Now, url='https://olympianmotors.com/model-01/preorder'
			button Reserve Now
		link Discover, url='https://olympianmotors.com/model-01'
			button Discover
		image Olympian Motors EV Platform, url='https://olympianmotors.com/images/version/olympus-ev-platform.png'
		heading Olympian EV Platform
		heading
		list
			listitem
				ListMarker •
				StaticText Base Price: $50K
			listitem
				ListMarker •
				StaticText Segment: Open, Modular EV Platform
			listitem
				ListMarker •
				StaticText *Range: 205-335 miles
			listitem
				ListMarker •
				StaticText System: Olympus OS x Android
			listitem
				ListMarker •
				StaticText Available for purchase: All 50 U.S. states and Canada
		link Order Now, url='https://olympianmotors.com/ev-platform/preorder'
			button Order Now
		link Discover, url='https://olympianmotors.com/olympus-os'
			button Discover
		image Centaru VAN, url='https://olympianmotors.com/images/version/centaur.png'
		heading Centaur
		heading
		list
			listitem
				ListMarker •
				StaticText Base Price: $70K
			listitem
				ListMarker •
				StaticText Segment: VAN
			listitem
				ListMarker •
				StaticText *Range: 205-335 miles
			listitem
				ListMarker •
				StaticText System: Olympus OS x Android
			listitem
				ListMarker •
				StaticText Available for purchase: In 2025
		link Reserve Now, url='https://olympianmotors.com/centaur/preorder'
			button Reserve Now
		heading Powered by 'Olympus' Operating System
		paragraph
			StaticText Model O1 and Model 84 share the same modular vehicle platform, powered by Olympus Operating System.
			StaticText Olympus OS enables a fully-modular vehicle architecture and provides a standardized integration protocol for our modular manufacturing and supply-chain partners.
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2FMVDS%2FMVDS_3.jpeg&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2FMVDS%2FMVDS_1.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2FMVDS%2FMVDS_2.png&w=1920&q=75'
		heading Model 84 Powered by Olympus OS.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2Fnvidia-inception.png&w=1920&q=75'
		heading Sustainability
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2Fsustainability.png&w=1920&q=75'
		paragraph
			StaticText Olympian Motors is dedicated to creating the most environmentally responsible vehicles of the 21st century.
		paragraph
			StaticText SUSTAINABLE MATERIALS: We prioritize using post-industrial recycled (PIR) materials, carbon-sequestered polyketone, bio-based polyurethane in Olympian vehicles.
		paragraph
			StaticText SUPERIOR BATTERY EFFICIENCY: Our commitment to sustainability is reflected in our highly efficient battery consumption rates in urban areas. Olympian O1 prototypes have achieved superior miles/kwh battery efficiency compared to existing electric vehicles such as the Tesla Model 3 (2022) and Rivian Model R1T (2022).
		paragraph
			StaticText We are leading the industry towards a cleaner, greener, sustainable future.
		heading Nature and Minimalism
		paragraph
			StaticText Inspired by the traditional Japanese philosophy of wabi-sabi, we diligently combine nature with minimalism in Olympian electric cars.
		paragraph
		paragraph
			StaticText Our company collaborates with exclusive suppliers and uses cutting-edge material technology to provide a unique driving and in-vehicle experience.
		paragraph
			StaticText We let Olympian drivers and passengers feel a sense of serenity in today's fast-paced world. Because less is more.
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2Fnatureminimilism.jpg&w=1920&q=75'
		heading Our Bases
		paragraph
			StaticText Brooklyn Navy Yard, New York
		image Brooklyn Navy Yard, New York, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2FBrooklyn.png&w=1920&q=75'
		paragraph
			StaticText Los Angeles, California
		image Michigan Central, Detroit (Q4/2023), url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2FCalifornia.png&w=1920&q=75'
		paragraph
			StaticText Detroit, Michigan
		image Michigan Central, Detroit (Q4/2023), url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fcompany%2FDetroit_new.png&w=1920&q=75'
		heading Our Team
		StaticText We are a team of engineers, builders and makers.
		image Eren, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fteams%2Feren.png&w=1920&q=75'
		paragraph
			StaticText Eren
		paragraph
			StaticText CEO & Chief Engineer
		image Eren, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fteams%2Fjohn.jpg&w=1920&q=75'
		paragraph
			StaticText John
		paragraph
			StaticText Head of Olympus OS
		image Adam, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fteams%2Fjasmine.jpg&w=1920&q=75'
		paragraph
			StaticText Jasmine
		paragraph
			StaticText Ops & Strategy
		image Zhaolong, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fteams%2FZhaolong.jpg&w=1920&q=75'
		paragraph
			StaticText Zhaolong
		paragraph
			StaticText Cockpit & Infotainment
		image Adam, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fteams%2FAdam.jpg&w=1920&q=75'
		paragraph
			StaticText Adam
		paragraph
			StaticText Head of Vehicle Engineering
		image Bikash, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fteams%2Fbikash.jpg&w=1920&q=75'
		paragraph
			StaticText Bikash
		paragraph
			StaticText Cloud & Data
		image Bryan, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fteams%2Fbryan.jpg&w=1920&q=75'
		paragraph
			StaticText Bryan
		paragraph
			StaticText Ops & Marketing
		image Henry, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fteams%2Fhenry.jpg&w=1920&q=75'
		paragraph
			StaticText Henry
		paragraph
			StaticText Technical Advisor
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2FgallaryImages%2Fcrowd.jpg&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2FgallaryImages%2Fnvidia-inception.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2FgallaryImages%2Finvest-gallary-2.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2FgallaryImages%2Finvest-gallery-3-new.jpg&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2FgallaryImages%2Finvest-gallary-4.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2FgallaryImages%2Finvest-gallary-5.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2FgallaryImages%2Finvest-gallary-6.png&w=1920&q=75'
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2FgallaryImages%2Finvest-gallary-7.png&w=1920&q=75'
		heading Featured in Media
		link Nvidia's Advanced AI Tech Powers Olympian Motors' New Electric Vehicle Platform December 24, 2024, url='https://finance.yahoo.com/news/nvidias-advanced-ai-tech-powers-115401009.html'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Fyfnvidia.jpeg&w=640&q=75'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Flogo%2FYahoo.png&w=640&q=75'
			paragraph
			paragraph
		link Olympian Motors and NVIDIA Pioneer the First AI-Powered EV Platforms December 23, 2024, url='https://www.globenewswire.com/news-release/2024/12/24/3001535/0/en/Olympian-Motors-and-NVIDIA-Pioneer-the-First-AI-Powered-EV-Platforms.html'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Fgn.jpeg&w=640&q=75'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Flogo%2Fglobenewswire.jpeg&w=640&q=75'
			paragraph
			paragraph
		link Olympian Motors Is Making Minimalist EVs for Drivers Sick of Screens March 2, 2024, url='https://www.bloomberg.com/news/articles/2024-03-02/olympian-motors-is-making-evs-for-drivers-sick-of-screens?embedded-checkout=true'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2FBloomberg.jpg&w=640&q=75'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Flogo%2Fbloomberg.png&w=640&q=75'
			paragraph
			paragraph
		link Manufacturing modular electric vehicles with style Jan 21, 2023, url='https://www.ycombinator.com/companies/olympian-motors'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Fyc.jpg&w=640&q=75'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Flogo%2Fyc.png&w=640&q=75'
			paragraph
			paragraph
		link electric SUV olympian model 84 projects its augmented reality display on windshield Jan 25, 2024, url='https://www.designboom.com/technology/olympian-motors-model-84-electric-suv-augmented-reality-ar-display-01-25-2024/'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Fdesignboom.jpg&w=640&q=75'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Flogo%2Fdesign_boom.png&w=640&q=75'
			paragraph
			paragraph
		link OLYMPIAN MOTORS’ ELECTRIC SUV SLATED FOR Q2 2024 RELEASE, TEASES CYBERTRUCK WITH AR WINDSHIELD AND A RETRO-FUTURISTIC DESIGN Jan 01, 2024, url='https://www.yankodesign.com/2024/01/30/olympian-motors-electric-suv-slated-for-q2-2024-release-teases-cybertruck-with-ar-windshield-and-a-retro-futuristic-design/'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Fyankodesign.jpg&w=640&q=75'
			image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fpress%2Fmedia-image%2Flogo%2Fyankodesign.png&w=640&q=75'
			paragraph
			paragraph
		button Show more
		image Logo Olympian Motors, url='https://olympianmotors.com/_next/static/media/logo.1fb8db2a.svg'
		paragraph
			StaticText Follow us
		link, url='https://twitter.com/olympianmotors'
			image
		link, url='https://www.instagram.com/olympianmotors/'
			image
		link, url='https://www.tiktok.com/@olympianmotors'
			image
		link, url='https://www.linkedin.com/company/olympian-motors/'
			image
		link Company, url='https://olympianmotors.com/company'
		link Careers, url='https://olympianmotors.com/careers'
		link Order, url='https://olympianmotors.com/order'
		link Contact, url='https://olympianmotors.com/contact'
		link Press, url='https://olympianmotors.com/press'
		paragraph
			StaticText OLYMPIAN MOTORS ©
			StaticText 2025
	alert, atomic
		StaticText Our Company - Olympian Motors
```
</details>



```
RootWebArea Olympian O1 - Olympian Motors, focused, url='https://olympianmotors.com/model-01'
	navigation
		list
			[81] link Olympian Motors Logo, center=(132,32), url='https://olympianmotors.com/'
				image Olympian Motors Logo, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Folympian-logo.42e47ff7.png&w=256&q=75'
```
<details><summary>Show more</summary>

```
		list
			list
				[86] link Company, center=(802,32), url='https://olympianmotors.com/company'
				[88] link Model 01, center=(902,32), focused, url='https://olympianmotors.com/model-01'
				[90] link Model 84, center=(1002,32), url='https://olympianmotors.com/model-84'
				[92] link Olympus OS, center=(1116,32), url='https://olympianmotors.com/olympus-os'
		list
			[95] link Test Drive, center=(1641,32), inner_text=Order, url='https://olympianmotors.com/order'
				button Test Drive
					StaticText Order
			[99] link Test Drive, center=(1712,32), url='https://olympianmotors.com/test-drive'
				button Test Drive
			listitem
				[104] link Invest, center=(1818,32), url='https://olympianmotors.com/invest'
					button Invest
	main
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FOlympian-01-Hero.76655e58.jpg&w=3840&q=50'
		heading Olympian Model 01
		paragraph
			StaticText It's time to drive exquisite and elegant cars.
		paragraph
			StaticText Not boring, mainstream, so called 'futuristic' cars that legacy automakers have pushed for decades.
		paragraph
			StaticText Olympian cars provide higher aesthetic standards and elevated quality.
		paragraph
			StaticText The Olympian Operating System provides full data privacy, data ownership, and data security.
		paragraph
			StaticText …
		paragraph
			StaticText Olympian O1, our flagship vehicle, is dedicated to great entrepreneurs, artists and scientists.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2Fm-01.png&w=1920&q=30'
		link Invest, url='https://olympianmotors.com/model-01/preorder'
			button Invest
				StaticText Reserve Now
		heading Exterior
		paragraph
			StaticText Olympian O1 sets the perfect balance of nature, minimalism, aesthetics.
		paragraph
			StaticText It's designed so you can enjoy, relax, breathe and find comfort in today's fast-paced world.
		paragraph
			StaticText Feel the Olympian experience. It's more than just a car.
		Iframe Olympain Model Video
			RootWebArea Model O1 by Olympian Motors | Experience-first electric vehicles. - YouTube, url='https://www.youtube.com/embed/zOK1BF1mVuA?controls=0&fs=0&modestbranding=1&playsinline=1&rel=0&showinfo=0'
				[d28] link Photo image of Olympian Motors, center=(452,3230)
				[d36] link Model O1 by Olympian Motors | Experience-first electric vehicles., center=(951,3231), url='https://www.youtube.com/watch?v=zOK1BF1mVuA'
				[d53] button Share, center=(1454,3228), hasPopup='menu'
					image
				[d89] button Play, center=(960,3630)
					image
				generic, atomic
				[d299] link Watch on www.youtube.com, center=(1429,4033), url='https://www.youtube.com/watch?v=zOK1BF1mVuA'
					image
		heading Features
		paragraph
			StaticText The perfect balance of nature, minimalism, and aesthetics.
		paragraph
			StaticText Find comfort. Have your space. Relax. Decompress.
		paragraph
			StaticText Exclusive. High-end. Aesthetic. Minimalist.
		paragraph
			StaticText Feel the Olympian experience. It's more than just a car.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2Fmodel-01-feature.jpg&w=1920&q=75'
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2FExterior-feature-1.jpg&w=1920&q=75'
		heading Interior
		paragraph
			StaticText Olympian vehicles achieve a luxurious minimalist interior that only adds to their allure. Today's interior automotive design requires a connection to the outside world, and we believe that 2D display screens and excessive buttons and switches are unnecessary. Instead, we combine advanced technology with natural elements to achieve a relaxing environment.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2Finterior.png&w=1920&q=75'
		heading Features
		paragraph
			StaticText Olympian vehicles achieve seamless functionality and simplicity.
		paragraph
			StaticText We solve the problem of today's over-complicated and crowded cockpits. Olympian provides a simple, natural, and intuitive UX.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2FInterior-2.jpg&w=1920&q=75'
		heading No Display Screens
		list
			listitem
				StaticText We are surrounded by screens all day long, from our phones to tablets, to laptops. Do we need to stare at yet another screen? Instead, we use augmented reality HUD.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2FInterior-4.jpg&w=1920&q=75'
		heading Quality Materials
		list
			listitem
				StaticText Olympian features the finest sustainably and responsibly sourced materials including exotic woods, steel, cashmere and silk. We avoid cheap plastics, veneer and toxic chemicals.
		heading Specifications
		paragraph
			StaticText Olympian O1 provides strong performance and
			StaticText battery capabilities.
		heading 0
		paragraph
			StaticText sec
		paragraph
			StaticText 0 - 60 mph
		heading 0
		paragraph
			StaticText mph
		paragraph
			StaticText *Top Speed
		heading 0
		paragraph
			StaticText miles
		paragraph
			StaticText *Max Range
		heading 0
		paragraph
			StaticText kWh
		paragraph
			StaticText *Max Battery
		image Olympian O1 in dim light, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2Finterior-specification.jpg&w=1920&q=75'
		heading Olympian O1 Details
		heading Key Specs
			button Key Specs, expanded=False
		separator, orientation='horizontal'
		heading Performance
			button Performance, expanded=False
		separator, orientation='horizontal'
		heading Drive & Battery
			button Drive & Battery, expanded=False
		separator, orientation='horizontal'
		heading Size
			button Size, expanded=False
		separator, orientation='horizontal'
		heading Minimalist Driver Cockpit
			button Minimalist Driver Cockpit, expanded=False
		separator, orientation='horizontal'
		heading Pricing
			button Pricing, expanded=False
		separator, orientation='horizontal'
		heading Exclusive Beauty
			button Exclusive Beauty, expanded=False
		separator, orientation='horizontal'
		heading Range: 300+ Miles per Charge
			button Range: 300+ Miles per Charge, expanded=False
		separator, orientation='horizontal'
		heading Find comfort. Have your space. Relax. Decompress.
			button Find comfort. Have your space. Relax. Decompress., expanded=False
		separator, orientation='horizontal'
		heading Safety
			button Safety, expanded=False
		separator, orientation='horizontal'
		heading Protection
			button Protection, expanded=False
		heading Lifestyle
		paragraph
			StaticText Olympian caters to those who appreciate the finer things in life and celebrate beauty in all forms with style, independence, and taste.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2FNewlab-10.jpeg&w=1920&q=75'
		heading Independence
		list
			listitem
				StaticText Olympian vehicles are for individuals who create their own paths. We created a brand for individual-thinkers, not conformists. For those who invent, not imitate.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2FLifestyle-1.jpg&w=1920&q=75'
		heading Adventure
		list
			listitem
				StaticText Olympian customers seek pleasurable experiences to nourish their souls. They feel free on the road away from the distractions of daily life. When they encounter something novel, something unknown and unexpected, they achieve an increased sense of creativity and self-awareness.
		image Olympian Model O1, url='https://olympianmotors.com/images/company/Bottom.jpg'
		heading Frequently Asked Questions
		heading Is it electric?
			button Is it electric?, expanded=False
		separator, orientation='horizontal'
		heading How can I charge my Olympian vehicle?
			button How can I charge my Olympian vehicle?, expanded=False
		separator, orientation='horizontal'
		heading So, can I charge an Olympian at a Tesla charging station?
			button So, can I charge an Olympian at a Tesla charging station?, expanded=False
		separator, orientation='horizontal'
		heading How can I purchase?
			button How can I purchase?, expanded=False
		separator, orientation='horizontal'
		heading Can I purchase Olympian cars in my area?
			button Can I purchase Olympian cars in my area?, expanded=False
		separator, orientation='horizontal'
		heading When is the first planned delivery?
			button When is the first planned delivery?, expanded=False
		separator, orientation='horizontal'
		heading Do you accept new investors?
			button Do you accept new investors?, expanded=False
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fsubscribe%2Fmodel01-dark.png&w=1920&q=75'
		heading Subscribe To Olympian Motors Newsletter
		paragraph
			StaticText To receive strategic company updates, upcoming
			StaticText launch dates,
			StaticText test-drive and Olympian Demo Day events.
		textbox Enter your email, required
		button Subscribe
		paragraph
			StaticText Your email is safe with us, we don't spam.
		image Logo Olympian Motors, url='https://olympianmotors.com/_next/static/media/logo.1fb8db2a.svg'
		paragraph
			StaticText Follow us
		link, url='https://twitter.com/olympianmotors'
			image
		link, url='https://www.instagram.com/olympianmotors/'
			image
		link, url='https://www.tiktok.com/@olympianmotors'
			image
		link, url='https://www.linkedin.com/company/olympian-motors/'
			image
		link Company, url='https://olympianmotors.com/company'
		link Careers, url='https://olympianmotors.com/careers'
		link Order, url='https://olympianmotors.com/order'
		link Contact, url='https://olympianmotors.com/contact'
		link Press, url='https://olympianmotors.com/press'
		paragraph
			StaticText OLYMPIAN MOTORS ©
			StaticText 2025
	alert, atomic
		StaticText Olympian O1 - Olympian Motors
```
</details>

**Reasoning for action:** I clicked on the Model 01 link because the user story defined a requirement to learn about different electric vehicle models offered by Olympian Motors. By clicking Model 01, I am accessing its specific details which will contribute towards meeting the user's goal of making an informed decision about their potential car purchase.

**Action:** click(88) # Click on Model 01 to learn more about this specific vehicle.

**Change Description:** After clicking on the Model 01 link, the browser navigated to the dedicated page for the Olympian Model O1, displaying updated content including a new main heading, descriptive paragraphs, features, and high-quality images specifically related to the Model O1, as well as a video iframe showcasing the vehicle.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://olympianmotors.com/model-01

https://olympianmotors.com/model-84

**Content (before/after):** 

```
RootWebArea Olympian O1 - Olympian Motors, focused, url='https://olympianmotors.com/model-01'
	navigation
		list
			[81] link Olympian Motors Logo, center=(132,32), url='https://olympianmotors.com/'
				image Olympian Motors Logo, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Folympian-logo.42e47ff7.png&w=256&q=75'
```
<details><summary>Show more</summary>

```
		list
			list
				[86] link Company, center=(802,32), url='https://olympianmotors.com/company'
				[88] link Model 01, center=(902,32), focused, url='https://olympianmotors.com/model-01'
				[90] link Model 84, center=(1002,32), url='https://olympianmotors.com/model-84'
				[92] link Olympus OS, center=(1116,32), url='https://olympianmotors.com/olympus-os'
		list
			[95] link Test Drive, center=(1641,32), inner_text=Order, url='https://olympianmotors.com/order'
				button Test Drive
					StaticText Order
			[99] link Test Drive, center=(1712,32), url='https://olympianmotors.com/test-drive'
				button Test Drive
			listitem
				[104] link Invest, center=(1818,32), url='https://olympianmotors.com/invest'
					button Invest
	main
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FOlympian-01-Hero.76655e58.jpg&w=3840&q=50'
		heading Olympian Model 01
		paragraph
			StaticText It's time to drive exquisite and elegant cars.
		paragraph
			StaticText Not boring, mainstream, so called 'futuristic' cars that legacy automakers have pushed for decades.
		paragraph
			StaticText Olympian cars provide higher aesthetic standards and elevated quality.
		paragraph
			StaticText The Olympian Operating System provides full data privacy, data ownership, and data security.
		paragraph
			StaticText …
		paragraph
			StaticText Olympian O1, our flagship vehicle, is dedicated to great entrepreneurs, artists and scientists.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2Fm-01.png&w=1920&q=30'
		link Invest, url='https://olympianmotors.com/model-01/preorder'
			button Invest
				StaticText Reserve Now
		heading Exterior
		paragraph
			StaticText Olympian O1 sets the perfect balance of nature, minimalism, aesthetics.
		paragraph
			StaticText It's designed so you can enjoy, relax, breathe and find comfort in today's fast-paced world.
		paragraph
			StaticText Feel the Olympian experience. It's more than just a car.
		Iframe Olympain Model Video
			RootWebArea Model O1 by Olympian Motors | Experience-first electric vehicles. - YouTube, url='https://www.youtube.com/embed/zOK1BF1mVuA?controls=0&fs=0&modestbranding=1&playsinline=1&rel=0&showinfo=0'
				[d28] link Photo image of Olympian Motors, center=(452,3230)
				[d36] link Model O1 by Olympian Motors | Experience-first electric vehicles., center=(951,3231), url='https://www.youtube.com/watch?v=zOK1BF1mVuA'
				[d53] button Share, center=(1454,3228), hasPopup='menu'
					image
				[d89] button Play, center=(960,3630)
					image
				generic, atomic
				[d299] link Watch on www.youtube.com, center=(1429,4033), url='https://www.youtube.com/watch?v=zOK1BF1mVuA'
					image
		heading Features
		paragraph
			StaticText The perfect balance of nature, minimalism, and aesthetics.
		paragraph
			StaticText Find comfort. Have your space. Relax. Decompress.
		paragraph
			StaticText Exclusive. High-end. Aesthetic. Minimalist.
		paragraph
			StaticText Feel the Olympian experience. It's more than just a car.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2Fmodel-01-feature.jpg&w=1920&q=75'
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2FExterior-feature-1.jpg&w=1920&q=75'
		heading Interior
		paragraph
			StaticText Olympian vehicles achieve a luxurious minimalist interior that only adds to their allure. Today's interior automotive design requires a connection to the outside world, and we believe that 2D display screens and excessive buttons and switches are unnecessary. Instead, we combine advanced technology with natural elements to achieve a relaxing environment.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2Finterior.png&w=1920&q=75'
		heading Features
		paragraph
			StaticText Olympian vehicles achieve seamless functionality and simplicity.
		paragraph
			StaticText We solve the problem of today's over-complicated and crowded cockpits. Olympian provides a simple, natural, and intuitive UX.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2FInterior-2.jpg&w=1920&q=75'
		heading No Display Screens
		list
			listitem
				StaticText We are surrounded by screens all day long, from our phones to tablets, to laptops. Do we need to stare at yet another screen? Instead, we use augmented reality HUD.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2FInterior-4.jpg&w=1920&q=75'
		heading Quality Materials
		list
			listitem
				StaticText Olympian features the finest sustainably and responsibly sourced materials including exotic woods, steel, cashmere and silk. We avoid cheap plastics, veneer and toxic chemicals.
		heading Specifications
		paragraph
			StaticText Olympian O1 provides strong performance and
			StaticText battery capabilities.
		heading 0
		paragraph
			StaticText sec
		paragraph
			StaticText 0 - 60 mph
		heading 0
		paragraph
			StaticText mph
		paragraph
			StaticText *Top Speed
		heading 0
		paragraph
			StaticText miles
		paragraph
			StaticText *Max Range
		heading 0
		paragraph
			StaticText kWh
		paragraph
			StaticText *Max Battery
		image Olympian O1 in dim light, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2Finterior-specification.jpg&w=1920&q=75'
		heading Olympian O1 Details
		heading Key Specs
			button Key Specs, expanded=False
		separator, orientation='horizontal'
		heading Performance
			button Performance, expanded=False
		separator, orientation='horizontal'
		heading Drive & Battery
			button Drive & Battery, expanded=False
		separator, orientation='horizontal'
		heading Size
			button Size, expanded=False
		separator, orientation='horizontal'
		heading Minimalist Driver Cockpit
			button Minimalist Driver Cockpit, expanded=False
		separator, orientation='horizontal'
		heading Pricing
			button Pricing, expanded=False
		separator, orientation='horizontal'
		heading Exclusive Beauty
			button Exclusive Beauty, expanded=False
		separator, orientation='horizontal'
		heading Range: 300+ Miles per Charge
			button Range: 300+ Miles per Charge, expanded=False
		separator, orientation='horizontal'
		heading Find comfort. Have your space. Relax. Decompress.
			button Find comfort. Have your space. Relax. Decompress., expanded=False
		separator, orientation='horizontal'
		heading Safety
			button Safety, expanded=False
		separator, orientation='horizontal'
		heading Protection
			button Protection, expanded=False
		heading Lifestyle
		paragraph
			StaticText Olympian caters to those who appreciate the finer things in life and celebrate beauty in all forms with style, independence, and taste.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2FNewlab-10.jpeg&w=1920&q=75'
		heading Independence
		list
			listitem
				StaticText Olympian vehicles are for individuals who create their own paths. We created a brand for individual-thinkers, not conformists. For those who invent, not imitate.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2FLifestyle-1.jpg&w=1920&q=75'
		heading Adventure
		list
			listitem
				StaticText Olympian customers seek pleasurable experiences to nourish their souls. They feel free on the road away from the distractions of daily life. When they encounter something novel, something unknown and unexpected, they achieve an increased sense of creativity and self-awareness.
		image Olympian Model O1, url='https://olympianmotors.com/images/company/Bottom.jpg'
		heading Frequently Asked Questions
		heading Is it electric?
			button Is it electric?, expanded=False
		separator, orientation='horizontal'
		heading How can I charge my Olympian vehicle?
			button How can I charge my Olympian vehicle?, expanded=False
		separator, orientation='horizontal'
		heading So, can I charge an Olympian at a Tesla charging station?
			button So, can I charge an Olympian at a Tesla charging station?, expanded=False
		separator, orientation='horizontal'
		heading How can I purchase?
			button How can I purchase?, expanded=False
		separator, orientation='horizontal'
		heading Can I purchase Olympian cars in my area?
			button Can I purchase Olympian cars in my area?, expanded=False
		separator, orientation='horizontal'
		heading When is the first planned delivery?
			button When is the first planned delivery?, expanded=False
		separator, orientation='horizontal'
		heading Do you accept new investors?
			button Do you accept new investors?, expanded=False
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fsubscribe%2Fmodel01-dark.png&w=1920&q=75'
		heading Subscribe To Olympian Motors Newsletter
		paragraph
			StaticText To receive strategic company updates, upcoming
			StaticText launch dates,
			StaticText test-drive and Olympian Demo Day events.
		textbox Enter your email, required
		button Subscribe
		paragraph
			StaticText Your email is safe with us, we don't spam.
		image Logo Olympian Motors, url='https://olympianmotors.com/_next/static/media/logo.1fb8db2a.svg'
		paragraph
			StaticText Follow us
		link, url='https://twitter.com/olympianmotors'
			image
		link, url='https://www.instagram.com/olympianmotors/'
			image
		link, url='https://www.tiktok.com/@olympianmotors'
			image
		link, url='https://www.linkedin.com/company/olympian-motors/'
			image
		link Company, url='https://olympianmotors.com/company'
		link Careers, url='https://olympianmotors.com/careers'
		link Order, url='https://olympianmotors.com/order'
		link Contact, url='https://olympianmotors.com/contact'
		link Press, url='https://olympianmotors.com/press'
		paragraph
			StaticText OLYMPIAN MOTORS ©
			StaticText 2025
	alert, atomic
		StaticText Olympian O1 - Olympian Motors
```
</details>



```
RootWebArea Model 84 - Olympian Motors, focused, url='https://olympianmotors.com/model-84'
	navigation
		list
			[81] link Olympian Motors Logo, center=(132,32), url='https://olympianmotors.com/'
				image Olympian Motors Logo, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Folympian-logo.42e47ff7.png&w=256&q=75'
```
<details><summary>Show more</summary>

```
		list
			list
				[86] link Company, center=(801,32), url='https://olympianmotors.com/company'
				[88] link Model 01, center=(902,32), url='https://olympianmotors.com/model-01'
				[90] link Model 84, center=(1002,32), focused, url='https://olympianmotors.com/model-84'
				[92] link Olympus OS, center=(1116,32), url='https://olympianmotors.com/olympus-os'
		list
			[95] link Test Drive, center=(1641,32), inner_text=Order, url='https://olympianmotors.com/order'
				button Test Drive
					StaticText Order
			[99] link Test Drive, center=(1712,32), url='https://olympianmotors.com/test-drive'
				button Test Drive
			listitem
				[104] link Invest, center=(1818,32), url='https://olympianmotors.com/invest'
					button Invest
	main
		image Olympian Model 84, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fmodel-84-hero-background.5e865e60.jpg&w=2048&q=40'
		heading Model 84
		paragraph
			StaticText Model 84 is carefully designed to take you on a mind-breaking journey on every single drive.
		paragraph
			StaticText Maybe you're a sultry detective in LA or an aspiring novelist in NY.
		paragraph
			StaticText Enjoy a serene driving experience.
		paragraph
			StaticText The first electric convertible SUV in the United States.
		image Olympian 84 Night, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-84%2Fmodel-84-nightshot.jpg&w=1920&q=70'
		heading Model 84 Limited Edition
		list
			listitem
				ListMarker •
				StaticText Limited Edition: Only
				StaticText 247
				StaticText units to be delivered in 2024.
			listitem
				ListMarker •
				StaticText Only available for
				StaticText NY and CA residents.
			listitem
				ListMarker •
				StaticText The first customer delivery: Q4/2024
			listitem
				ListMarker •
				StaticText Test-drives have started in Brooklyn, New York. (We will also offer test-drives during Olympian Demo Days in SF, LA and Miami throughout 2024.)
		link Invest, url='https://olympianmotors.com/model-84/preorder'
			button Invest
				StaticText Order Now
		Iframe Olympian Model 84 Video
			RootWebArea Less is more, less is freedom. Model 84 by Olympian Motors. Only available in CA & NY. #electriccars - YouTube, url='https://www.youtube.com/embed/Au5g2GY4Ju4'
				[e30] link Photo image of Olympian Motors, center=(452,3482)
				[e38] link Less is more, less is freedom. Model 84 by Olympian Motors. Only available in CA & NY. #electriccars, center=(951,3482), url='https://www.youtube.com/watch?v=Au5g2GY4Ju4'
				[e55] button Share, center=(1454,3480), hasPopup='menu'
					image
				[e91] button Play, center=(960,3882)
					image
				generic, atomic
				[e321] link Watch on YouTube, center=(506,4285), url='https://www.youtube.com/watch?v=Au5g2GY4Ju4&embeds_referring_euri=https%3A%2F%2Folympianmotors.com%2F'
		heading Model 84 Exterior
		paragraph
			StaticText Whether you are cruising down the city streets or exploring the wilderness, the Olympian Model 84 is the perfect companion for the adventurous spirit.
		image Olympian Model 84, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FOlympian_WallScene_BLACK.13cf030a.jpg&w=3840&q=75'
		heading Elegant
		paragraph
			StaticText The perfect balance of nature, minimalism, aesthetics, Find comfort. Have your space. Relax. Decompress. Exclusive, High-end, Aesthetic, Minimalistic. Feel the Olympian experience. It’s more than just a car.
		image Olympian Model 84 Red, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fmodel-84-blue-elegent.926e45e8.jpg&w=3840&q=75'
		image Olympian Model 84 Red, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FOlympian_WallScene_Red_Cam.b57f8a5f.jpg&w=1920&q=75'
		heading 84 Interior
		paragraph
			StaticText Olympian vehicles achieve a luxurious minimalist interior that only adds to their allure. Automotive design requires a connection to the outside world, and we believe that 2D display screens and excessive buttons and switches are unnecessary. Instead, we combine advanced technology with natural elements to achieve a relaxing, integrated environment.
		image Olympian Model 84, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fmodel-84-interior.b3501d11.jpg&w=1080&q=75'
		heading Features
		paragraph
			StaticText Olympian vehicles achieve seamless functionality and simplicity. We solve the problem of today’s over-complicated and crowded cockpits. Olympian provides a simple, natural, and intuitive UX.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2FInterior-3.jpg&w=1920&q=75'
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2FInterior-2.jpg&w=1920&q=75'
		heading No Display Screens
		list
			listitem
				StaticText We are surrounded by screens all day long, from our phones to tablets, to laptops. Do we need to stare at yet another screen? Instead, we use augmented reality HUD.
		paragraph
			StaticText Olympian MVDS:
		paragraph
			StaticText Modular Vehicle Drivetrain System
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fmodel-01%2FInterior-4.jpg&w=1920&q=75'
		heading Quality Materials
		list
			listitem
				StaticText Olympian features the finest sustainably and responsibly sourced materials including exotic woods, steel, cashmere and silk. We reject cheap plastics, veneer and toxic chemicals.
		heading Specifications
		paragraph
			StaticText Olympian 84 provides strong
			StaticText performance and battery capabilities.
		heading 0
		paragraph
			StaticText s
		paragraph
			StaticText 0 - 60 mph
		heading 0
		paragraph
			StaticText mph
		paragraph
			StaticText *Top Speed
		heading 0
		paragraph
			StaticText miles
		paragraph
			StaticText *Max Range
		heading 0
		paragraph
			StaticText kWh
		paragraph
			StaticText *Max Battery
		image Olympian O1 in dim light, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FOlympian_WallScen.b60d685a.jpg&w=1920&q=100'
		heading Olympian 84 Details
		heading Key Specs
			button Key Specs, expanded=False
		separator, orientation='horizontal'
		heading Performance
			button Performance, expanded=False
		separator, orientation='horizontal'
		heading Drive & Battery
			button Drive & Battery, expanded=False
		separator, orientation='horizontal'
		heading Size
			button Size, expanded=False
		separator, orientation='horizontal'
		heading Minimalistic Driver Cockpit
			button Minimalistic Driver Cockpit, expanded=False
		separator, orientation='horizontal'
		heading Pricing
			button Pricing, expanded=False
		separator, orientation='horizontal'
		heading Range: 300+ Miles per Charge
			button Range: 300+ Miles per Charge, expanded=False
		separator, orientation='horizontal'
		heading Find comfort. Have your space. Relax. Decompress.
			button Find comfort. Have your space. Relax. Decompress., expanded=False
		separator, orientation='horizontal'
		heading Safety
			button Safety, expanded=False
		separator, orientation='horizontal'
		heading Protection
			button Protection, expanded=False
		heading Lifestyle
		paragraph
			StaticText Olympian caters to those who appreciate the finer things in life and celebrate beauty in all forms
		image Olympian Model 84, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Foceanside-1.6a6969da.jpg&w=1920&q=75'
		heading Independence
		list
			listitem
				StaticText Olympian vehicles are for individuals who create their own paths. We created a brand for individual-thinkers, not conformists. For those who invent, not imitate.
		image Olympian Model O1, url='https://olympianmotors.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FCalifornia-Sun.7abd49d4.jpg&w=1920&q=75'
		heading Adventure
		list
			listitem
				StaticText Olympian customers seek pleasurable experiences to nourish their souls. They feel free on the road away from the distractions of daily life. When they encounter something novel, something unknown and unexpected, they achieve an increased sense of creativity and self-awareness.
		heading Frequently Asked Questions
		heading Is it electric?
			button Is it electric?, expanded=False
		separator, orientation='horizontal'
		heading How can I charge my Olympian vehicle?
			button How can I charge my Olympian vehicle?, expanded=False
		separator, orientation='horizontal'
		heading So, can I charge an Olympian at a Tesla charging station?
			button So, can I charge an Olympian at a Tesla charging station?, expanded=False
		separator, orientation='horizontal'
		heading How can I purchase?
			button How can I purchase?, expanded=False
		separator, orientation='horizontal'
		heading Can I purchase Olympian cars in my area?
			button Can I purchase Olympian cars in my area?, expanded=False
		separator, orientation='horizontal'
		heading When is the first planned delivery?
			button When is the first planned delivery?, expanded=False
		separator, orientation='horizontal'
		heading Do you accept new investors?
			button Do you accept new investors?, expanded=False
		image, url='https://olympianmotors.com/_next/image?url=%2Fimages%2Fsubscribe%2Fmodel01-dark.png&w=1920&q=75'
		heading Subscribe To Olympian Motors Newsletter
		paragraph
			StaticText To receive strategic company updates, upcoming
			StaticText launch dates,
			StaticText test-drive and Olympian Demo Day events.
		textbox Enter your email, required
		button Subscribe
		paragraph
			StaticText Your email is safe with us, we don't spam.
		image Logo Olympian Motors, url='https://olympianmotors.com/_next/static/media/logo.1fb8db2a.svg'
		paragraph
			StaticText Follow us
		link, url='https://twitter.com/olympianmotors'
			image
		link, url='https://www.instagram.com/olympianmotors/'
			image
		link, url='https://www.tiktok.com/@olympianmotors'
			image
		link, url='https://www.linkedin.com/company/olympian-motors/'
			image
		link Company, url='https://olympianmotors.com/company'
		link Careers, url='https://olympianmotors.com/careers'
		link Order, url='https://olympianmotors.com/order'
		link Contact, url='https://olympianmotors.com/contact'
		link Press, url='https://olympianmotors.com/press'
		paragraph
			StaticText OLYMPIAN MOTORS ©
			StaticText 2025
	alert, atomic
		StaticText Model 84 - Olympian Motors
```
</details>

**Reasoning for action:** I need to gather information on the Model 84 as requested in the user story. By clicking the link for Model 84, I will transition to that specific model's webpage, which is necessary for obtaining detailed information, features, and images relevant to the Model 84. This action is an essential step towards fulfilling the user's goal of learning about different electric vehicle models offered by Olympian Motors.

**Action:** click(90) # Click on the Model 84 link to explore another vehicle model.

**Change Description:** The browser navigated from the Olympian Model 01 page to the Model 84 page, changing the focused link in the navigation to 'Model 84' and displaying new content specifically for the Model 84 vehicle, including updated images, headings, and descriptive paragraphs relevant to the new model.

**Screenshot before:****Screenshot after:**---


# Task

**Search and View Event Details for ISOxo**

As a music enthusiast,
I search for specific events by artist names,
so that I can find and purchase tickets for my favorite events easily.

**Success definition:** Given I am on the CrowdVolt homepage
When I search for 'ISOxo' in the search textbox and click on the ISOxo Friday event link
Then I should see the event details page for ISOxo Friday at Brooklyn Steel, including ticket purchase options and event information.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.crowdvolt.com/

https://www.crowdvolt.com/

**Content (before/after):** 

```
RootWebArea CrowdVolt, focused, url='https://www.crowdvolt.com/'
	navigation
		[80] link CrowdVolt Logo, center=(93,32), url='https://www.crowdvolt.com/'
			image CrowdVolt Logo, url='https://www.crowdvolt.com/_next/image?url=%2Ffull_logo.png&w=256&q=75'
		[86] textbox Search by event, center=(478,32), contenteditable=True
```
<details><summary>Show more</summary>

```
		image
		[91] link Events, center=(1584,32), url='https://www.crowdvolt.com/'
		[92] link About, center=(1680,32), url='https://www.crowdvolt.com/about'
		[93] link Help, center=(1767,32), url='https://www.crowdvolt.com/help'
		[97] button Log In, center=(1850,32)
	heading Buy or Sell
	heading Rave & EDM Tickets
	heading Easy, secure, and hassle-free transactions
	heading powered by community-generated reviews and ratings.
	[360] link Join the party, center=(338,334), url='https://www.crowdvolt.com/signup'
		button Join the party
			image
	group
		link Background, url='https://soundcloud.com/crowdvoltradio/volt-radio-v08-simmi?si=dee864ba6f794b399d5a62a700cb1fd4&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing'
			image Background, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2F8e7eb9fe-1b3_d1487c61-144d-43f1-af0c-bc437022edff.png&w=1920&q=75'
			paragraph
		link Background, url='https://soundcloud.com/crowdvoltradio/volt-radio-v07-dopastat?si=b3d1b4509b4542cdb78b3ec5f3db40f7&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing'
			image Background, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2Fbeeaeed6-3be_c6dbc2fe-c5bd-44f4-bbcf-46a86a576163.png&w=1920&q=75'
			paragraph
		[379] link Background, center=(1328,230), url='https://www.instagram.com/crowdvolt'
			image Background, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2F31918f14-d89_455d4d3b-15f0-48a9-9673-80b62d5a73bf.png&w=1920&q=75'
			paragraph
		image Bolt, url='https://www.crowdvolt.com/_next/image?url=%2Fbolt.png&w=32&q=75'
		StaticText @
		StaticText crowdvolt
		paragraph
			StaticText Follow us on Instagram to stay in the loop with exclusive events and promotions!
	button
	button
	button
	button
	heading Trending Events
	link ISOxo (Friday) ISOxo (Friday) Fri, January 10 • 9PM Brooklyn Steel From $109, url='https://www.crowdvolt.com/app/event/isoxofri1'
		image ISOxo (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fdab10e1f-6068-4a2e-bff7-ee6a8fe63226.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Friday)
		StaticText Fri, January 10 • 9PM
		StaticText Brooklyn Steel
		StaticText From $109
	link Spring Festival: Illenium Spring Festival: Illenium Thu, January 30 • 10PM Great Hall From $131, url='https://www.crowdvolt.com/app/event/springfestivalillenium'
		image Spring Festival: Illenium, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F286eeebe-a543-4ca6-8e7e-4566a350f1ed.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Spring Festival: Illenium
		StaticText Thu, January 30 • 10PM
		StaticText Great Hall
		StaticText From $131
	[566] link Knock2 (Friday) Knock2 (Friday) Fri, March 7 • 7PM Terminal 5 From $79, center=(439,660), inner_text=Knock2 (Friday)
Fri, March 7 • 7PM
Terminal 5
From $79, url='https://www.crowdvolt.com/app/event/knock2friterm5'
		image Knock2 (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fbbe08c4b-3579-478d-b6eb-a543934b0ac5.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Knock2 (Friday)
		StaticText Fri, March 7 • 7PM
		StaticText Terminal 5
		StaticText From $79
	[581] link Dom Dolla (Saturday) Dom Dolla (Saturday) Sat, March 8 • 8PM Madison Square Garden From $99, center=(903,660), inner_text=Dom Dolla (Saturday)
Sat, March 8 • 8PM
Madison Square Garden
From $99, url='https://www.crowdvolt.com/app/event/domdollamsgsaturday'
		image Dom Dolla (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F587f0cd7-fc50-455e-901c-8b8548320729.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Dom Dolla (Saturday)
		StaticText Sat, March 8 • 8PM
		StaticText Madison Square Garden
		StaticText From $99
	[599] link ISOxo (Friday) ISOxo (Friday) Fri, January 10 • 9PM Brooklyn Steel From $109, center=(1367,660), inner_text=ISOxo (Friday)
Fri, January 10 • 9PM
Brooklyn Steel
From $109, url='https://www.crowdvolt.com/app/event/isoxofri1'
		image ISOxo (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fdab10e1f-6068-4a2e-bff7-ee6a8fe63226.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Friday)
		StaticText Fri, January 10 • 9PM
		StaticText Brooklyn Steel
		StaticText From $109
	link Spring Festival: Illenium Spring Festival: Illenium Thu, January 30 • 10PM Great Hall From $131, url='https://www.crowdvolt.com/app/event/springfestivalillenium'
		image Spring Festival: Illenium, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F286eeebe-a543-4ca6-8e7e-4566a350f1ed.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Spring Festival: Illenium
		StaticText Thu, January 30 • 10PM
		StaticText Great Hall
		StaticText From $131
	link Knock2 (Friday) Knock2 (Friday) Fri, March 7 • 7PM Terminal 5 From $79, url='https://www.crowdvolt.com/app/event/knock2friterm5'
		image Knock2 (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fbbe08c4b-3579-478d-b6eb-a543934b0ac5.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Knock2 (Friday)
		StaticText Fri, March 7 • 7PM
		StaticText Terminal 5
		StaticText From $79
	link Dom Dolla (Saturday) Dom Dolla (Saturday) Sat, March 8 • 8PM Madison Square Garden From $99, url='https://www.crowdvolt.com/app/event/domdollamsgsaturday'
		image Dom Dolla (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F587f0cd7-fc50-455e-901c-8b8548320729.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Dom Dolla (Saturday)
		StaticText Sat, March 8 • 8PM
		StaticText Madison Square Garden
		StaticText From $99
	heading Browse Events in New York or Miami
		[665] button New York, center=(562,903)
		[667] button Miami, center=(716,903)
	[669] button Date, center=(289,957)
	[672] button Venue, center=(398,957)
	[675] button Popular, center=(520,957)
	[678] button Sort By, center=(648,957)
	link Jamie XX (Friday) Jamie XX (Friday) Fri, January 10 • 7PM Park Avenue Armory Last Sale $130, url='https://www.crowdvolt.com/app/event/jamiexxfriarmory'
		image Jamie XX (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F9038d60a-a043-4969-b76e-3f0ee291b641.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Jamie XX (Friday)
		paragraph
			StaticText Fri, January 10 • 7PM
		paragraph
			StaticText Park Avenue Armory
		paragraph
			StaticText Last Sale $130
	link ISOxo (Friday) ISOxo (Friday) Fri, January 10 • 9PM Brooklyn Steel From $109, url='https://www.crowdvolt.com/app/event/isoxofri1'
		image ISOxo (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fdab10e1f-6068-4a2e-bff7-ee6a8fe63226.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Friday)
		paragraph
			StaticText Fri, January 10 • 9PM
		paragraph
			StaticText Brooklyn Steel
		paragraph
			StaticText From $109
	link Slushii Slushii Fri, January 10 • 11PM Webster Hall Be the first to sell, url='https://www.crowdvolt.com/app/event/slushii'
		image Slushii, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F1f8974a0-0808-4d26-a0ed-629106a79851.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Slushii
		paragraph
			StaticText Fri, January 10 • 11PM
		paragraph
			StaticText Webster Hall
		paragraph
			StaticText Be the first to sell
	link Jamie XX (Saturday) Jamie XX (Saturday) Sat, January 11 • 7PM Park Avenue Armory From $170, url='https://www.crowdvolt.com/app/event/jamiexxsatarmory'
		image Jamie XX (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F9038d60a-a043-4969-b76e-3f0ee291b641.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Jamie XX (Saturday)
		paragraph
			StaticText Sat, January 11 • 7PM
		paragraph
			StaticText Park Avenue Armory
		paragraph
			StaticText From $170
	link ISOxo (Saturday) ISOxo (Saturday) Sat, January 11 • 9PM Brooklyn Steel From $95, url='https://www.crowdvolt.com/app/event/isoxosat1'
		image ISOxo (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fc17aab61-b732-4532-8775-6d26f5102012.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Saturday)
		paragraph
			StaticText Sat, January 11 • 9PM
		paragraph
			StaticText Brooklyn Steel
		paragraph
			StaticText From $95
	link HESH HESH Sat, January 11 • 10PM Kings Hall - Avant Gardner From $14, url='https://www.crowdvolt.com/app/event/heshnyc'
		image HESH, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F76e55167-884c-4159-ba87-da0a2b606b13.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText HESH
		paragraph
			StaticText Sat, January 11 • 10PM
		paragraph
			StaticText Kings Hall - Avant Gardner
		paragraph
			StaticText From $14
	link Markus Schulz Markus Schulz Sat, January 11 • 10PM SILO Be the first to sell, url='https://www.crowdvolt.com/app/event/markusschulzsilo'
		image Markus Schulz, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F41119665-5594-46a9-a4b8-9ba0de41b423.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Markus Schulz
		paragraph
			StaticText Sat, January 11 • 10PM
		paragraph
			StaticText SILO
		paragraph
			StaticText Be the first to sell
	link Gene Farris Gene Farris Sun, January 12 • 2PM Superior Ingredients From $18, url='https://www.crowdvolt.com/app/event/genefarrisgrayarea'
		image Gene Farris, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F762d7003-f3c3-405b-991c-41ff66b92351.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Gene Farris
		paragraph
			StaticText Sun, January 12 • 2PM
		paragraph
			StaticText Superior Ingredients
		paragraph
			StaticText From $18
	heading Company
	link Careers, url='https://forms.gle/XWQzReTD1pafSZac9'
		heading Careers
	link About, url='https://www.crowdvolt.com/about'
		heading About
	link FAQ, url='https://www.crowdvolt.com/faq'
		heading FAQ
	heading Connect
	link Instagram, url='https://www.instagram.com/crowdvolt/'
		heading Instagram
	link LinkedIn, url='https://www.linkedin.com/company/crowdvolt'
		heading LinkedIn
	link Help, url='https://www.crowdvolt.com/faq'
		heading Help
	heading Resources
	heading Request an Event
	link Privacy Policy, url='https://www.crowdvolt.com/privacy'
		heading Privacy Policy
	link Terms and Conditions, url='https://www.crowdvolt.com/terms_of_service'
		heading Terms and Conditions
	image Y-Combinator, url='https://www.crowdvolt.com/ycom.png'
	heading Backed by Y Combinator
	heading © CrowdVolt 2024
	region Notifications (F8)
		list
	alert, atomic
```
</details>



```
RootWebArea CrowdVolt, focused, url='https://www.crowdvolt.com/'
	navigation
		link CrowdVolt Logo, url='https://www.crowdvolt.com/'
			image CrowdVolt Logo, url='https://www.crowdvolt.com/_next/image?url=%2Ffull_logo.png&w=256&q=75'
		[86] textbox Search by event, center=(478,32), contenteditable=True, focused
```
<details><summary>Show more</summary>

```
		image
		[91] link Events, center=(1584,32), url='https://www.crowdvolt.com/'
		[92] link About, center=(1680,32), url='https://www.crowdvolt.com/about'
		[93] link Help, center=(1767,32), url='https://www.crowdvolt.com/help'
		[97] button Log In, center=(1850,32)
	heading Buy or Sell
	heading Rave & EDM Tickets
	heading Easy, secure, and hassle-free transactions
	heading powered by community-generated reviews and ratings.
	link Join the party, url='https://www.crowdvolt.com/signup'
		button Join the party
			image
	group
		link Background, url='https://soundcloud.com/crowdvoltradio/volt-radio-v08-simmi?si=dee864ba6f794b399d5a62a700cb1fd4&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing'
			image Background, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2F8e7eb9fe-1b3_d1487c61-144d-43f1-af0c-bc437022edff.png&w=1920&q=75'
			paragraph
		link Background, url='https://soundcloud.com/crowdvoltradio/volt-radio-v07-dopastat?si=b3d1b4509b4542cdb78b3ec5f3db40f7&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing'
			image Background, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2Fbeeaeed6-3be_c6dbc2fe-c5bd-44f4-bbcf-46a86a576163.png&w=1920&q=75'
			paragraph
		link Background, url='https://www.instagram.com/crowdvolt'
			image Background, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2F31918f14-d89_455d4d3b-15f0-48a9-9673-80b62d5a73bf.png&w=1920&q=75'
			paragraph
		image Bolt, url='https://www.crowdvolt.com/_next/image?url=%2Fbolt.png&w=32&q=75'
		StaticText @
		StaticText crowdvolt
		paragraph
			StaticText Follow us on Instagram to stay in the loop with exclusive events and promotions!
	button
	button
	button
	button
	heading Trending Events
	link ISOxo (Friday) ISOxo (Friday) Fri, January 10 • 9PM Brooklyn Steel From $109, url='https://www.crowdvolt.com/app/event/isoxofri1'
		image ISOxo (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fdab10e1f-6068-4a2e-bff7-ee6a8fe63226.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Friday)
		StaticText Fri, January 10 • 9PM
		StaticText Brooklyn Steel
		StaticText From $109
	link Spring Festival: Illenium Spring Festival: Illenium Thu, January 30 • 10PM Great Hall From $131, url='https://www.crowdvolt.com/app/event/springfestivalillenium'
		image Spring Festival: Illenium, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F286eeebe-a543-4ca6-8e7e-4566a350f1ed.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Spring Festival: Illenium
		StaticText Thu, January 30 • 10PM
		StaticText Great Hall
		StaticText From $131
	link Knock2 (Friday) Knock2 (Friday) Fri, March 7 • 7PM Terminal 5 From $79, url='https://www.crowdvolt.com/app/event/knock2friterm5'
		image Knock2 (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fbbe08c4b-3579-478d-b6eb-a543934b0ac5.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Knock2 (Friday)
		StaticText Fri, March 7 • 7PM
		StaticText Terminal 5
		StaticText From $79
	link Dom Dolla (Saturday) Dom Dolla (Saturday) Sat, March 8 • 8PM Madison Square Garden From $99, url='https://www.crowdvolt.com/app/event/domdollamsgsaturday'
		image Dom Dolla (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F587f0cd7-fc50-455e-901c-8b8548320729.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Dom Dolla (Saturday)
		StaticText Sat, March 8 • 8PM
		StaticText Madison Square Garden
		StaticText From $99
	link ISOxo (Friday) ISOxo (Friday) Fri, January 10 • 9PM Brooklyn Steel From $109, url='https://www.crowdvolt.com/app/event/isoxofri1'
		image ISOxo (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fdab10e1f-6068-4a2e-bff7-ee6a8fe63226.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Friday)
		StaticText Fri, January 10 • 9PM
		StaticText Brooklyn Steel
		StaticText From $109
	link Spring Festival: Illenium Spring Festival: Illenium Thu, January 30 • 10PM Great Hall From $131, url='https://www.crowdvolt.com/app/event/springfestivalillenium'
		image Spring Festival: Illenium, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F286eeebe-a543-4ca6-8e7e-4566a350f1ed.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Spring Festival: Illenium
		StaticText Thu, January 30 • 10PM
		StaticText Great Hall
		StaticText From $131
	link Knock2 (Friday) Knock2 (Friday) Fri, March 7 • 7PM Terminal 5 From $79, url='https://www.crowdvolt.com/app/event/knock2friterm5'
		image Knock2 (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fbbe08c4b-3579-478d-b6eb-a543934b0ac5.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Knock2 (Friday)
		StaticText Fri, March 7 • 7PM
		StaticText Terminal 5
		StaticText From $79
	link Dom Dolla (Saturday) Dom Dolla (Saturday) Sat, March 8 • 8PM Madison Square Garden From $99, url='https://www.crowdvolt.com/app/event/domdollamsgsaturday'
		image Dom Dolla (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F587f0cd7-fc50-455e-901c-8b8548320729.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Dom Dolla (Saturday)
		StaticText Sat, March 8 • 8PM
		StaticText Madison Square Garden
		StaticText From $99
	heading Browse Events in New York or Miami
		button New York
		button Miami
	button Date
	button Venue
	button Popular
	button Sort By
	link Jamie XX (Friday) Jamie XX (Friday) Fri, January 10 • 7PM Park Avenue Armory Last Sale $130, url='https://www.crowdvolt.com/app/event/jamiexxfriarmory'
		image Jamie XX (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F9038d60a-a043-4969-b76e-3f0ee291b641.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Jamie XX (Friday)
		paragraph
			StaticText Fri, January 10 • 7PM
		paragraph
			StaticText Park Avenue Armory
		paragraph
			StaticText Last Sale $130
	link ISOxo (Friday) ISOxo (Friday) Fri, January 10 • 9PM Brooklyn Steel From $109, url='https://www.crowdvolt.com/app/event/isoxofri1'
		image ISOxo (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fdab10e1f-6068-4a2e-bff7-ee6a8fe63226.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Friday)
		paragraph
			StaticText Fri, January 10 • 9PM
		paragraph
			StaticText Brooklyn Steel
		paragraph
			StaticText From $109
	link Slushii Slushii Fri, January 10 • 11PM Webster Hall Be the first to sell, url='https://www.crowdvolt.com/app/event/slushii'
		image Slushii, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F1f8974a0-0808-4d26-a0ed-629106a79851.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Slushii
		paragraph
			StaticText Fri, January 10 • 11PM
		paragraph
			StaticText Webster Hall
		paragraph
			StaticText Be the first to sell
	link Jamie XX (Saturday) Jamie XX (Saturday) Sat, January 11 • 7PM Park Avenue Armory From $170, url='https://www.crowdvolt.com/app/event/jamiexxsatarmory'
		image Jamie XX (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F9038d60a-a043-4969-b76e-3f0ee291b641.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Jamie XX (Saturday)
		paragraph
			StaticText Sat, January 11 • 7PM
		paragraph
			StaticText Park Avenue Armory
		paragraph
			StaticText From $170
	link ISOxo (Saturday) ISOxo (Saturday) Sat, January 11 • 9PM Brooklyn Steel From $95, url='https://www.crowdvolt.com/app/event/isoxosat1'
		image ISOxo (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fc17aab61-b732-4532-8775-6d26f5102012.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Saturday)
		paragraph
			StaticText Sat, January 11 • 9PM
		paragraph
			StaticText Brooklyn Steel
		paragraph
			StaticText From $95
	link HESH HESH Sat, January 11 • 10PM Kings Hall - Avant Gardner From $14, url='https://www.crowdvolt.com/app/event/heshnyc'
		image HESH, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F76e55167-884c-4159-ba87-da0a2b606b13.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText HESH
		paragraph
			StaticText Sat, January 11 • 10PM
		paragraph
			StaticText Kings Hall - Avant Gardner
		paragraph
			StaticText From $14
	link Markus Schulz Markus Schulz Sat, January 11 • 10PM SILO Be the first to sell, url='https://www.crowdvolt.com/app/event/markusschulzsilo'
		image Markus Schulz, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F41119665-5594-46a9-a4b8-9ba0de41b423.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Markus Schulz
		paragraph
			StaticText Sat, January 11 • 10PM
		paragraph
			StaticText SILO
		paragraph
			StaticText Be the first to sell
	link Gene Farris Gene Farris Sun, January 12 • 2PM Superior Ingredients From $18, url='https://www.crowdvolt.com/app/event/genefarrisgrayarea'
		image Gene Farris, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F762d7003-f3c3-405b-991c-41ff66b92351.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Gene Farris
		paragraph
			StaticText Sun, January 12 • 2PM
		paragraph
			StaticText Superior Ingredients
		paragraph
			StaticText From $18
	heading Company
	link Careers, url='https://forms.gle/XWQzReTD1pafSZac9'
		heading Careers
	link About, url='https://www.crowdvolt.com/about'
		heading About
	link FAQ, url='https://www.crowdvolt.com/faq'
		heading FAQ
	heading Connect
	link Instagram, url='https://www.instagram.com/crowdvolt/'
		heading Instagram
	link LinkedIn, url='https://www.linkedin.com/company/crowdvolt'
		heading LinkedIn
	link Help, url='https://www.crowdvolt.com/faq'
		heading Help
	heading Resources
	heading Request an Event
	link Privacy Policy, url='https://www.crowdvolt.com/privacy'
		heading Privacy Policy
	link Terms and Conditions, url='https://www.crowdvolt.com/terms_of_service'
		heading Terms and Conditions
	image Y-Combinator, url='https://www.crowdvolt.com/ycom.png'
	heading Backed by Y Combinator
	heading © CrowdVolt 2024
	region Notifications (F8)
		list
	alert, atomic
```
</details>

**Reasoning for action:** By clicking on the search textbox, I am preparing to enter the search term 'ISOxo'. This step is crucial to initiate the search process for the specific event related to the artist. Once the textbox is active, I will be able to type in the artist's name, which directly aligns with the user's task of finding events by artist names.

**Action:** click(86) # Click on the search textbox to explore the search functionality.

**Change Description:** After clicking on the search textbox, it became focused, allowing the user to input text for searching events or information, thereby enhancing the functionality of the site for user interaction.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.crowdvolt.com/

https://www.crowdvolt.com/

**Content (before/after):** 

```
RootWebArea CrowdVolt, focused, url='https://www.crowdvolt.com/'
	navigation
		link CrowdVolt Logo, url='https://www.crowdvolt.com/'
			image CrowdVolt Logo, url='https://www.crowdvolt.com/_next/image?url=%2Ffull_logo.png&w=256&q=75'
		[86] textbox Search by event, center=(478,32), contenteditable=True, focused
```
<details><summary>Show more</summary>

```
		image
		[91] link Events, center=(1584,32), url='https://www.crowdvolt.com/'
		[92] link About, center=(1680,32), url='https://www.crowdvolt.com/about'
		[93] link Help, center=(1767,32), url='https://www.crowdvolt.com/help'
		[97] button Log In, center=(1850,32)
	heading Buy or Sell
	heading Rave & EDM Tickets
	heading Easy, secure, and hassle-free transactions
	heading powered by community-generated reviews and ratings.
	link Join the party, url='https://www.crowdvolt.com/signup'
		button Join the party
			image
	group
		link Background, url='https://soundcloud.com/crowdvoltradio/volt-radio-v08-simmi?si=dee864ba6f794b399d5a62a700cb1fd4&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing'
			image Background, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2F8e7eb9fe-1b3_d1487c61-144d-43f1-af0c-bc437022edff.png&w=1920&q=75'
			paragraph
		link Background, url='https://soundcloud.com/crowdvoltradio/volt-radio-v07-dopastat?si=b3d1b4509b4542cdb78b3ec5f3db40f7&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing'
			image Background, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2Fbeeaeed6-3be_c6dbc2fe-c5bd-44f4-bbcf-46a86a576163.png&w=1920&q=75'
			paragraph
		link Background, url='https://www.instagram.com/crowdvolt'
			image Background, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2F31918f14-d89_455d4d3b-15f0-48a9-9673-80b62d5a73bf.png&w=1920&q=75'
			paragraph
		image Bolt, url='https://www.crowdvolt.com/_next/image?url=%2Fbolt.png&w=32&q=75'
		StaticText @
		StaticText crowdvolt
		paragraph
			StaticText Follow us on Instagram to stay in the loop with exclusive events and promotions!
	button
	button
	button
	button
	heading Trending Events
	link ISOxo (Friday) ISOxo (Friday) Fri, January 10 • 9PM Brooklyn Steel From $109, url='https://www.crowdvolt.com/app/event/isoxofri1'
		image ISOxo (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fdab10e1f-6068-4a2e-bff7-ee6a8fe63226.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Friday)
		StaticText Fri, January 10 • 9PM
		StaticText Brooklyn Steel
		StaticText From $109
	link Spring Festival: Illenium Spring Festival: Illenium Thu, January 30 • 10PM Great Hall From $131, url='https://www.crowdvolt.com/app/event/springfestivalillenium'
		image Spring Festival: Illenium, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F286eeebe-a543-4ca6-8e7e-4566a350f1ed.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Spring Festival: Illenium
		StaticText Thu, January 30 • 10PM
		StaticText Great Hall
		StaticText From $131
	link Knock2 (Friday) Knock2 (Friday) Fri, March 7 • 7PM Terminal 5 From $79, url='https://www.crowdvolt.com/app/event/knock2friterm5'
		image Knock2 (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fbbe08c4b-3579-478d-b6eb-a543934b0ac5.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Knock2 (Friday)
		StaticText Fri, March 7 • 7PM
		StaticText Terminal 5
		StaticText From $79
	link Dom Dolla (Saturday) Dom Dolla (Saturday) Sat, March 8 • 8PM Madison Square Garden From $99, url='https://www.crowdvolt.com/app/event/domdollamsgsaturday'
		image Dom Dolla (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F587f0cd7-fc50-455e-901c-8b8548320729.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Dom Dolla (Saturday)
		StaticText Sat, March 8 • 8PM
		StaticText Madison Square Garden
		StaticText From $99
	link ISOxo (Friday) ISOxo (Friday) Fri, January 10 • 9PM Brooklyn Steel From $109, url='https://www.crowdvolt.com/app/event/isoxofri1'
		image ISOxo (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fdab10e1f-6068-4a2e-bff7-ee6a8fe63226.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Friday)
		StaticText Fri, January 10 • 9PM
		StaticText Brooklyn Steel
		StaticText From $109
	link Spring Festival: Illenium Spring Festival: Illenium Thu, January 30 • 10PM Great Hall From $131, url='https://www.crowdvolt.com/app/event/springfestivalillenium'
		image Spring Festival: Illenium, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F286eeebe-a543-4ca6-8e7e-4566a350f1ed.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Spring Festival: Illenium
		StaticText Thu, January 30 • 10PM
		StaticText Great Hall
		StaticText From $131
	link Knock2 (Friday) Knock2 (Friday) Fri, March 7 • 7PM Terminal 5 From $79, url='https://www.crowdvolt.com/app/event/knock2friterm5'
		image Knock2 (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fbbe08c4b-3579-478d-b6eb-a543934b0ac5.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Knock2 (Friday)
		StaticText Fri, March 7 • 7PM
		StaticText Terminal 5
		StaticText From $79
	link Dom Dolla (Saturday) Dom Dolla (Saturday) Sat, March 8 • 8PM Madison Square Garden From $99, url='https://www.crowdvolt.com/app/event/domdollamsgsaturday'
		image Dom Dolla (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F587f0cd7-fc50-455e-901c-8b8548320729.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Dom Dolla (Saturday)
		StaticText Sat, March 8 • 8PM
		StaticText Madison Square Garden
		StaticText From $99
	heading Browse Events in New York or Miami
		button New York
		button Miami
	button Date
	button Venue
	button Popular
	button Sort By
	link Jamie XX (Friday) Jamie XX (Friday) Fri, January 10 • 7PM Park Avenue Armory Last Sale $130, url='https://www.crowdvolt.com/app/event/jamiexxfriarmory'
		image Jamie XX (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F9038d60a-a043-4969-b76e-3f0ee291b641.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Jamie XX (Friday)
		paragraph
			StaticText Fri, January 10 • 7PM
		paragraph
			StaticText Park Avenue Armory
		paragraph
			StaticText Last Sale $130
	link ISOxo (Friday) ISOxo (Friday) Fri, January 10 • 9PM Brooklyn Steel From $109, url='https://www.crowdvolt.com/app/event/isoxofri1'
		image ISOxo (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fdab10e1f-6068-4a2e-bff7-ee6a8fe63226.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Friday)
		paragraph
			StaticText Fri, January 10 • 9PM
		paragraph
			StaticText Brooklyn Steel
		paragraph
			StaticText From $109
	link Slushii Slushii Fri, January 10 • 11PM Webster Hall Be the first to sell, url='https://www.crowdvolt.com/app/event/slushii'
		image Slushii, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F1f8974a0-0808-4d26-a0ed-629106a79851.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Slushii
		paragraph
			StaticText Fri, January 10 • 11PM
		paragraph
			StaticText Webster Hall
		paragraph
			StaticText Be the first to sell
	link Jamie XX (Saturday) Jamie XX (Saturday) Sat, January 11 • 7PM Park Avenue Armory From $170, url='https://www.crowdvolt.com/app/event/jamiexxsatarmory'
		image Jamie XX (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F9038d60a-a043-4969-b76e-3f0ee291b641.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Jamie XX (Saturday)
		paragraph
			StaticText Sat, January 11 • 7PM
		paragraph
			StaticText Park Avenue Armory
		paragraph
			StaticText From $170
	link ISOxo (Saturday) ISOxo (Saturday) Sat, January 11 • 9PM Brooklyn Steel From $95, url='https://www.crowdvolt.com/app/event/isoxosat1'
		image ISOxo (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fc17aab61-b732-4532-8775-6d26f5102012.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Saturday)
		paragraph
			StaticText Sat, January 11 • 9PM
		paragraph
			StaticText Brooklyn Steel
		paragraph
			StaticText From $95
	link HESH HESH Sat, January 11 • 10PM Kings Hall - Avant Gardner From $14, url='https://www.crowdvolt.com/app/event/heshnyc'
		image HESH, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F76e55167-884c-4159-ba87-da0a2b606b13.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText HESH
		paragraph
			StaticText Sat, January 11 • 10PM
		paragraph
			StaticText Kings Hall - Avant Gardner
		paragraph
			StaticText From $14
	link Markus Schulz Markus Schulz Sat, January 11 • 10PM SILO Be the first to sell, url='https://www.crowdvolt.com/app/event/markusschulzsilo'
		image Markus Schulz, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F41119665-5594-46a9-a4b8-9ba0de41b423.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Markus Schulz
		paragraph
			StaticText Sat, January 11 • 10PM
		paragraph
			StaticText SILO
		paragraph
			StaticText Be the first to sell
	link Gene Farris Gene Farris Sun, January 12 • 2PM Superior Ingredients From $18, url='https://www.crowdvolt.com/app/event/genefarrisgrayarea'
		image Gene Farris, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F762d7003-f3c3-405b-991c-41ff66b92351.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Gene Farris
		paragraph
			StaticText Sun, January 12 • 2PM
		paragraph
			StaticText Superior Ingredients
		paragraph
			StaticText From $18
	heading Company
	link Careers, url='https://forms.gle/XWQzReTD1pafSZac9'
		heading Careers
	link About, url='https://www.crowdvolt.com/about'
		heading About
	link FAQ, url='https://www.crowdvolt.com/faq'
		heading FAQ
	heading Connect
	link Instagram, url='https://www.instagram.com/crowdvolt/'
		heading Instagram
	link LinkedIn, url='https://www.linkedin.com/company/crowdvolt'
		heading LinkedIn
	link Help, url='https://www.crowdvolt.com/faq'
		heading Help
	heading Resources
	heading Request an Event
	link Privacy Policy, url='https://www.crowdvolt.com/privacy'
		heading Privacy Policy
	link Terms and Conditions, url='https://www.crowdvolt.com/terms_of_service'
		heading Terms and Conditions
	image Y-Combinator, url='https://www.crowdvolt.com/ycom.png'
	heading Backed by Y Combinator
	heading © CrowdVolt 2024
	region Notifications (F8)
		list
	alert, atomic
```
</details>



```
RootWebArea CrowdVolt, focused, url='https://www.crowdvolt.com/'
	navigation
		link CrowdVolt Logo, url='https://www.crowdvolt.com/'
			image CrowdVolt Logo, url='https://www.crowdvolt.com/_next/image?url=%2Ffull_logo.png&w=256&q=75'
		[86] textbox Search by event value='ISOxo', center=(478,32), contenteditable=True, focused
```
<details><summary>Show more</summary>

```
		image
		[911] link ISOxo (Friday) image ISOxo (Friday) Jan 10 Brooklyn Steel, center=(296,109), inner_text=ISOxo (Friday)
Jan 10
Brooklyn Steel, url='https://www.crowdvolt.com/event/isoxofri1'
			image ISOxo (Friday) image, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2Fd61161dd-1454-4963-85b7-d78e09dd9066.png&w=1920&q=75'
			heading ISOxo (Friday)
			heading Jan 10
			heading Brooklyn Steel
		[922] link ISOxo (Saturday) image ISOxo (Saturday) Jan 11 Brooklyn Steel, center=(306,189), inner_text=ISOxo (Saturday)
Jan 11
Brooklyn Steel, url='https://www.crowdvolt.com/event/isoxosat1'
			image ISOxo (Saturday) image, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2F36cf73e7-f59c-40c3-9ba0-bf2f3b1a674c.png&w=1920&q=75'
			heading ISOxo (Saturday)
			heading Jan 11
			heading Brooklyn Steel
		[91] link Events, center=(1584,32), url='https://www.crowdvolt.com/'
		[92] link About, center=(1680,32), url='https://www.crowdvolt.com/about'
		[93] link Help, center=(1767,32), url='https://www.crowdvolt.com/help'
		[97] button Log In, center=(1850,32)
	heading Buy or Sell
	heading Rave & EDM Tickets
	heading Easy, secure, and hassle-free transactions
	heading powered by community-generated reviews and ratings.
	link Join the party, url='https://www.crowdvolt.com/signup'
		button Join the party
			image
	group
		link Background, url='https://soundcloud.com/crowdvoltradio/volt-radio-v08-simmi?si=dee864ba6f794b399d5a62a700cb1fd4&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing'
			image Background, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2F8e7eb9fe-1b3_d1487c61-144d-43f1-af0c-bc437022edff.png&w=1920&q=75'
			paragraph
		link Background, url='https://soundcloud.com/crowdvoltradio/volt-radio-v07-dopastat?si=b3d1b4509b4542cdb78b3ec5f3db40f7&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing'
			image Background, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2Fbeeaeed6-3be_c6dbc2fe-c5bd-44f4-bbcf-46a86a576163.png&w=1920&q=75'
			paragraph
		link Background, url='https://www.instagram.com/crowdvolt'
			image Background, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2F31918f14-d89_455d4d3b-15f0-48a9-9673-80b62d5a73bf.png&w=1920&q=75'
			paragraph
		image Bolt, url='https://www.crowdvolt.com/_next/image?url=%2Fbolt.png&w=32&q=75'
		StaticText @
		StaticText crowdvolt
		paragraph
			StaticText Follow us on Instagram to stay in the loop with exclusive events and promotions!
	button
	button
	button
	button
	heading Trending Events
	link ISOxo (Friday) ISOxo (Friday) Fri, January 10 • 9PM Brooklyn Steel From $109, url='https://www.crowdvolt.com/app/event/isoxofri1'
		image ISOxo (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fdab10e1f-6068-4a2e-bff7-ee6a8fe63226.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Friday)
		StaticText Fri, January 10 • 9PM
		StaticText Brooklyn Steel
		StaticText From $109
	link Spring Festival: Illenium Spring Festival: Illenium Thu, January 30 • 10PM Great Hall From $131, url='https://www.crowdvolt.com/app/event/springfestivalillenium'
		image Spring Festival: Illenium, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F286eeebe-a543-4ca6-8e7e-4566a350f1ed.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Spring Festival: Illenium
		StaticText Thu, January 30 • 10PM
		StaticText Great Hall
		StaticText From $131
	link Knock2 (Friday) Knock2 (Friday) Fri, March 7 • 7PM Terminal 5 From $79, url='https://www.crowdvolt.com/app/event/knock2friterm5'
		image Knock2 (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fbbe08c4b-3579-478d-b6eb-a543934b0ac5.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Knock2 (Friday)
		StaticText Fri, March 7 • 7PM
		StaticText Terminal 5
		StaticText From $79
	link Dom Dolla (Saturday) Dom Dolla (Saturday) Sat, March 8 • 8PM Madison Square Garden From $99, url='https://www.crowdvolt.com/app/event/domdollamsgsaturday'
		image Dom Dolla (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F587f0cd7-fc50-455e-901c-8b8548320729.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Dom Dolla (Saturday)
		StaticText Sat, March 8 • 8PM
		StaticText Madison Square Garden
		StaticText From $99
	link ISOxo (Friday) ISOxo (Friday) Fri, January 10 • 9PM Brooklyn Steel From $109, url='https://www.crowdvolt.com/app/event/isoxofri1'
		image ISOxo (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fdab10e1f-6068-4a2e-bff7-ee6a8fe63226.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Friday)
		StaticText Fri, January 10 • 9PM
		StaticText Brooklyn Steel
		StaticText From $109
	link Spring Festival: Illenium Spring Festival: Illenium Thu, January 30 • 10PM Great Hall From $131, url='https://www.crowdvolt.com/app/event/springfestivalillenium'
		image Spring Festival: Illenium, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F286eeebe-a543-4ca6-8e7e-4566a350f1ed.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Spring Festival: Illenium
		StaticText Thu, January 30 • 10PM
		StaticText Great Hall
		StaticText From $131
	link Knock2 (Friday) Knock2 (Friday) Fri, March 7 • 7PM Terminal 5 From $79, url='https://www.crowdvolt.com/app/event/knock2friterm5'
		image Knock2 (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fbbe08c4b-3579-478d-b6eb-a543934b0ac5.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Knock2 (Friday)
		StaticText Fri, March 7 • 7PM
		StaticText Terminal 5
		StaticText From $79
	link Dom Dolla (Saturday) Dom Dolla (Saturday) Sat, March 8 • 8PM Madison Square Garden From $99, url='https://www.crowdvolt.com/app/event/domdollamsgsaturday'
		image Dom Dolla (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F587f0cd7-fc50-455e-901c-8b8548320729.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Dom Dolla (Saturday)
		StaticText Sat, March 8 • 8PM
		StaticText Madison Square Garden
		StaticText From $99
	heading Browse Events in New York or Miami
		button New York
		button Miami
	button Date
	button Venue
	button Popular
	button Sort By
	link Jamie XX (Friday) Jamie XX (Friday) Fri, January 10 • 7PM Park Avenue Armory Last Sale $130, url='https://www.crowdvolt.com/app/event/jamiexxfriarmory'
		image Jamie XX (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F9038d60a-a043-4969-b76e-3f0ee291b641.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Jamie XX (Friday)
		paragraph
			StaticText Fri, January 10 • 7PM
		paragraph
			StaticText Park Avenue Armory
		paragraph
			StaticText Last Sale $130
	link ISOxo (Friday) ISOxo (Friday) Fri, January 10 • 9PM Brooklyn Steel From $109, url='https://www.crowdvolt.com/app/event/isoxofri1'
		image ISOxo (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fdab10e1f-6068-4a2e-bff7-ee6a8fe63226.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Friday)
		paragraph
			StaticText Fri, January 10 • 9PM
		paragraph
			StaticText Brooklyn Steel
		paragraph
			StaticText From $109
	link Slushii Slushii Fri, January 10 • 11PM Webster Hall Be the first to sell, url='https://www.crowdvolt.com/app/event/slushii'
		image Slushii, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F1f8974a0-0808-4d26-a0ed-629106a79851.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Slushii
		paragraph
			StaticText Fri, January 10 • 11PM
		paragraph
			StaticText Webster Hall
		paragraph
			StaticText Be the first to sell
	link Jamie XX (Saturday) Jamie XX (Saturday) Sat, January 11 • 7PM Park Avenue Armory From $170, url='https://www.crowdvolt.com/app/event/jamiexxsatarmory'
		image Jamie XX (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F9038d60a-a043-4969-b76e-3f0ee291b641.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Jamie XX (Saturday)
		paragraph
			StaticText Sat, January 11 • 7PM
		paragraph
			StaticText Park Avenue Armory
		paragraph
			StaticText From $170
	link ISOxo (Saturday) ISOxo (Saturday) Sat, January 11 • 9PM Brooklyn Steel From $95, url='https://www.crowdvolt.com/app/event/isoxosat1'
		image ISOxo (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fc17aab61-b732-4532-8775-6d26f5102012.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Saturday)
		paragraph
			StaticText Sat, January 11 • 9PM
		paragraph
			StaticText Brooklyn Steel
		paragraph
			StaticText From $95
	link HESH HESH Sat, January 11 • 10PM Kings Hall - Avant Gardner From $14, url='https://www.crowdvolt.com/app/event/heshnyc'
		image HESH, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F76e55167-884c-4159-ba87-da0a2b606b13.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText HESH
		paragraph
			StaticText Sat, January 11 • 10PM
		paragraph
			StaticText Kings Hall - Avant Gardner
		paragraph
			StaticText From $14
	link Markus Schulz Markus Schulz Sat, January 11 • 10PM SILO Be the first to sell, url='https://www.crowdvolt.com/app/event/markusschulzsilo'
		image Markus Schulz, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F41119665-5594-46a9-a4b8-9ba0de41b423.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Markus Schulz
		paragraph
			StaticText Sat, January 11 • 10PM
		paragraph
			StaticText SILO
		paragraph
			StaticText Be the first to sell
	link Gene Farris Gene Farris Sun, January 12 • 2PM Superior Ingredients From $18, url='https://www.crowdvolt.com/app/event/genefarrisgrayarea'
		image Gene Farris, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F762d7003-f3c3-405b-991c-41ff66b92351.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Gene Farris
		paragraph
			StaticText Sun, January 12 • 2PM
		paragraph
			StaticText Superior Ingredients
		paragraph
			StaticText From $18
	heading Company
	link Careers, url='https://forms.gle/XWQzReTD1pafSZac9'
		heading Careers
	link About, url='https://www.crowdvolt.com/about'
		heading About
	link FAQ, url='https://www.crowdvolt.com/faq'
		heading FAQ
	heading Connect
	link Instagram, url='https://www.instagram.com/crowdvolt/'
		heading Instagram
	link LinkedIn, url='https://www.linkedin.com/company/crowdvolt'
		heading LinkedIn
	link Help, url='https://www.crowdvolt.com/faq'
		heading Help
	heading Resources
	heading Request an Event
	link Privacy Policy, url='https://www.crowdvolt.com/privacy'
		heading Privacy Policy
	link Terms and Conditions, url='https://www.crowdvolt.com/terms_of_service'
		heading Terms and Conditions
	image Y-Combinator, url='https://www.crowdvolt.com/ycom.png'
	heading Backed by Y Combinator
	heading © CrowdVolt 2024
	region Notifications (F8)
		list
	alert, atomic
```
</details>

**Reasoning for action:** I decided to input the artist's name 'ISOxo' into the search textbox because the user story explicitly states that the user wants to find events by searching for specific artist names. By doing this, I am ensuring that the system can retrieve and display events pertinent to ISOxo, which is crucial for the user to find and purchase tickets for their favorite events.

**Action:** keyboard_insert_text('ISOxo') # Type 'ISOxo' in the search textbox to see if any events related to it appear.

**Change Description:** The search textbox now displays the value 'ISOxo', indicating that the term has been successfully inserted. Additionally, two relevant event links for 'ISOxo' were made visible: one for 'ISOxo (Friday)' and another for 'ISOxo (Saturday)', which provide details on the upcoming events.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.crowdvolt.com/

https://www.crowdvolt.com/event/isoxofri1

**Content (before/after):** 

```
RootWebArea CrowdVolt, focused, url='https://www.crowdvolt.com/'
	navigation
		link CrowdVolt Logo, url='https://www.crowdvolt.com/'
			image CrowdVolt Logo, url='https://www.crowdvolt.com/_next/image?url=%2Ffull_logo.png&w=256&q=75'
		[86] textbox Search by event value='ISOxo', center=(478,32), contenteditable=True, focused
```
<details><summary>Show more</summary>

```
		image
		[911] link ISOxo (Friday) image ISOxo (Friday) Jan 10 Brooklyn Steel, center=(296,109), inner_text=ISOxo (Friday)
Jan 10
Brooklyn Steel, url='https://www.crowdvolt.com/event/isoxofri1'
			image ISOxo (Friday) image, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2Fd61161dd-1454-4963-85b7-d78e09dd9066.png&w=1920&q=75'
			heading ISOxo (Friday)
			heading Jan 10
			heading Brooklyn Steel
		[922] link ISOxo (Saturday) image ISOxo (Saturday) Jan 11 Brooklyn Steel, center=(306,189), inner_text=ISOxo (Saturday)
Jan 11
Brooklyn Steel, url='https://www.crowdvolt.com/event/isoxosat1'
			image ISOxo (Saturday) image, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2F36cf73e7-f59c-40c3-9ba0-bf2f3b1a674c.png&w=1920&q=75'
			heading ISOxo (Saturday)
			heading Jan 11
			heading Brooklyn Steel
		[91] link Events, center=(1584,32), url='https://www.crowdvolt.com/'
		[92] link About, center=(1680,32), url='https://www.crowdvolt.com/about'
		[93] link Help, center=(1767,32), url='https://www.crowdvolt.com/help'
		[97] button Log In, center=(1850,32)
	heading Buy or Sell
	heading Rave & EDM Tickets
	heading Easy, secure, and hassle-free transactions
	heading powered by community-generated reviews and ratings.
	link Join the party, url='https://www.crowdvolt.com/signup'
		button Join the party
			image
	group
		link Background, url='https://soundcloud.com/crowdvoltradio/volt-radio-v08-simmi?si=dee864ba6f794b399d5a62a700cb1fd4&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing'
			image Background, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2F8e7eb9fe-1b3_d1487c61-144d-43f1-af0c-bc437022edff.png&w=1920&q=75'
			paragraph
		link Background, url='https://soundcloud.com/crowdvoltradio/volt-radio-v07-dopastat?si=b3d1b4509b4542cdb78b3ec5f3db40f7&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing'
			image Background, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2Fbeeaeed6-3be_c6dbc2fe-c5bd-44f4-bbcf-46a86a576163.png&w=1920&q=75'
			paragraph
		link Background, url='https://www.instagram.com/crowdvolt'
			image Background, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2F31918f14-d89_455d4d3b-15f0-48a9-9673-80b62d5a73bf.png&w=1920&q=75'
			paragraph
		image Bolt, url='https://www.crowdvolt.com/_next/image?url=%2Fbolt.png&w=32&q=75'
		StaticText @
		StaticText crowdvolt
		paragraph
			StaticText Follow us on Instagram to stay in the loop with exclusive events and promotions!
	button
	button
	button
	button
	heading Trending Events
	link ISOxo (Friday) ISOxo (Friday) Fri, January 10 • 9PM Brooklyn Steel From $109, url='https://www.crowdvolt.com/app/event/isoxofri1'
		image ISOxo (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fdab10e1f-6068-4a2e-bff7-ee6a8fe63226.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Friday)
		StaticText Fri, January 10 • 9PM
		StaticText Brooklyn Steel
		StaticText From $109
	link Spring Festival: Illenium Spring Festival: Illenium Thu, January 30 • 10PM Great Hall From $131, url='https://www.crowdvolt.com/app/event/springfestivalillenium'
		image Spring Festival: Illenium, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F286eeebe-a543-4ca6-8e7e-4566a350f1ed.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Spring Festival: Illenium
		StaticText Thu, January 30 • 10PM
		StaticText Great Hall
		StaticText From $131
	link Knock2 (Friday) Knock2 (Friday) Fri, March 7 • 7PM Terminal 5 From $79, url='https://www.crowdvolt.com/app/event/knock2friterm5'
		image Knock2 (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fbbe08c4b-3579-478d-b6eb-a543934b0ac5.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Knock2 (Friday)
		StaticText Fri, March 7 • 7PM
		StaticText Terminal 5
		StaticText From $79
	link Dom Dolla (Saturday) Dom Dolla (Saturday) Sat, March 8 • 8PM Madison Square Garden From $99, url='https://www.crowdvolt.com/app/event/domdollamsgsaturday'
		image Dom Dolla (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F587f0cd7-fc50-455e-901c-8b8548320729.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Dom Dolla (Saturday)
		StaticText Sat, March 8 • 8PM
		StaticText Madison Square Garden
		StaticText From $99
	link ISOxo (Friday) ISOxo (Friday) Fri, January 10 • 9PM Brooklyn Steel From $109, url='https://www.crowdvolt.com/app/event/isoxofri1'
		image ISOxo (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fdab10e1f-6068-4a2e-bff7-ee6a8fe63226.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Friday)
		StaticText Fri, January 10 • 9PM
		StaticText Brooklyn Steel
		StaticText From $109
	link Spring Festival: Illenium Spring Festival: Illenium Thu, January 30 • 10PM Great Hall From $131, url='https://www.crowdvolt.com/app/event/springfestivalillenium'
		image Spring Festival: Illenium, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F286eeebe-a543-4ca6-8e7e-4566a350f1ed.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Spring Festival: Illenium
		StaticText Thu, January 30 • 10PM
		StaticText Great Hall
		StaticText From $131
	link Knock2 (Friday) Knock2 (Friday) Fri, March 7 • 7PM Terminal 5 From $79, url='https://www.crowdvolt.com/app/event/knock2friterm5'
		image Knock2 (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fbbe08c4b-3579-478d-b6eb-a543934b0ac5.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Knock2 (Friday)
		StaticText Fri, March 7 • 7PM
		StaticText Terminal 5
		StaticText From $79
	link Dom Dolla (Saturday) Dom Dolla (Saturday) Sat, March 8 • 8PM Madison Square Garden From $99, url='https://www.crowdvolt.com/app/event/domdollamsgsaturday'
		image Dom Dolla (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F587f0cd7-fc50-455e-901c-8b8548320729.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Dom Dolla (Saturday)
		StaticText Sat, March 8 • 8PM
		StaticText Madison Square Garden
		StaticText From $99
	heading Browse Events in New York or Miami
		button New York
		button Miami
	button Date
	button Venue
	button Popular
	button Sort By
	link Jamie XX (Friday) Jamie XX (Friday) Fri, January 10 • 7PM Park Avenue Armory Last Sale $130, url='https://www.crowdvolt.com/app/event/jamiexxfriarmory'
		image Jamie XX (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F9038d60a-a043-4969-b76e-3f0ee291b641.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Jamie XX (Friday)
		paragraph
			StaticText Fri, January 10 • 7PM
		paragraph
			StaticText Park Avenue Armory
		paragraph
			StaticText Last Sale $130
	link ISOxo (Friday) ISOxo (Friday) Fri, January 10 • 9PM Brooklyn Steel From $109, url='https://www.crowdvolt.com/app/event/isoxofri1'
		image ISOxo (Friday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fdab10e1f-6068-4a2e-bff7-ee6a8fe63226.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Friday)
		paragraph
			StaticText Fri, January 10 • 9PM
		paragraph
			StaticText Brooklyn Steel
		paragraph
			StaticText From $109
	link Slushii Slushii Fri, January 10 • 11PM Webster Hall Be the first to sell, url='https://www.crowdvolt.com/app/event/slushii'
		image Slushii, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F1f8974a0-0808-4d26-a0ed-629106a79851.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Slushii
		paragraph
			StaticText Fri, January 10 • 11PM
		paragraph
			StaticText Webster Hall
		paragraph
			StaticText Be the first to sell
	link Jamie XX (Saturday) Jamie XX (Saturday) Sat, January 11 • 7PM Park Avenue Armory From $170, url='https://www.crowdvolt.com/app/event/jamiexxsatarmory'
		image Jamie XX (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F9038d60a-a043-4969-b76e-3f0ee291b641.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Jamie XX (Saturday)
		paragraph
			StaticText Sat, January 11 • 7PM
		paragraph
			StaticText Park Avenue Armory
		paragraph
			StaticText From $170
	link ISOxo (Saturday) ISOxo (Saturday) Sat, January 11 • 9PM Brooklyn Steel From $95, url='https://www.crowdvolt.com/app/event/isoxosat1'
		image ISOxo (Saturday), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fc17aab61-b732-4532-8775-6d26f5102012.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText ISOxo (Saturday)
		paragraph
			StaticText Sat, January 11 • 9PM
		paragraph
			StaticText Brooklyn Steel
		paragraph
			StaticText From $95
	link HESH HESH Sat, January 11 • 10PM Kings Hall - Avant Gardner From $14, url='https://www.crowdvolt.com/app/event/heshnyc'
		image HESH, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F76e55167-884c-4159-ba87-da0a2b606b13.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText HESH
		paragraph
			StaticText Sat, January 11 • 10PM
		paragraph
			StaticText Kings Hall - Avant Gardner
		paragraph
			StaticText From $14
	link Markus Schulz Markus Schulz Sat, January 11 • 10PM SILO Be the first to sell, url='https://www.crowdvolt.com/app/event/markusschulzsilo'
		image Markus Schulz, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F41119665-5594-46a9-a4b8-9ba0de41b423.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Markus Schulz
		paragraph
			StaticText Sat, January 11 • 10PM
		paragraph
			StaticText SILO
		paragraph
			StaticText Be the first to sell
	link Gene Farris Gene Farris Sun, January 12 • 2PM Superior Ingredients From $18, url='https://www.crowdvolt.com/app/event/genefarrisgrayarea'
		image Gene Farris, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F762d7003-f3c3-405b-991c-41ff66b92351.png%3Fauto%3Dcompress%26h%3D500&w=1920&q=75'
		button
		StaticText Gene Farris
		paragraph
			StaticText Sun, January 12 • 2PM
		paragraph
			StaticText Superior Ingredients
		paragraph
			StaticText From $18
	heading Company
	link Careers, url='https://forms.gle/XWQzReTD1pafSZac9'
		heading Careers
	link About, url='https://www.crowdvolt.com/about'
		heading About
	link FAQ, url='https://www.crowdvolt.com/faq'
		heading FAQ
	heading Connect
	link Instagram, url='https://www.instagram.com/crowdvolt/'
		heading Instagram
	link LinkedIn, url='https://www.linkedin.com/company/crowdvolt'
		heading LinkedIn
	link Help, url='https://www.crowdvolt.com/faq'
		heading Help
	heading Resources
	heading Request an Event
	link Privacy Policy, url='https://www.crowdvolt.com/privacy'
		heading Privacy Policy
	link Terms and Conditions, url='https://www.crowdvolt.com/terms_of_service'
		heading Terms and Conditions
	image Y-Combinator, url='https://www.crowdvolt.com/ycom.png'
	heading Backed by Y Combinator
	heading © CrowdVolt 2024
	region Notifications (F8)
		list
	alert, atomic
```
</details>



```
RootWebArea ISOxo (Friday) Brooklyn tickets - Brooklyn Steel - Fri, January 10 | CrowdVolt, focused, url='https://www.crowdvolt.com/event/isoxofri1'
	navigation
		[80] link CrowdVolt Logo, center=(93,32), url='https://www.crowdvolt.com/'
			image CrowdVolt Logo, url='https://www.crowdvolt.com/_next/image?url=%2Ffull_logo.png&w=256&q=75'
		[86] textbox Search by event, center=(478,32), contenteditable=True, focused
```
<details><summary>Show more</summary>

```
		image
		[91] link Events, center=(1584,32), url='https://www.crowdvolt.com/'
		[92] link About, center=(1680,32), url='https://www.crowdvolt.com/about'
		[93] link Help, center=(1767,32), url='https://www.crowdvolt.com/help'
		[97] button Log In, center=(1850,32)
	image Concert, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2Fd61161dd-1454-4963-85b7-d78e09dd9066.png&w=1920&q=75'
	image Concert, url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fmiragematch.s3.us-east-2.amazonaws.com%2Fd61161dd-1454-4963-85b7-d78e09dd9066.png&w=1920&q=75'
	image
	heading Brooklyn Steel
	heading Brooklyn, NY 11222
	[1138] button OPEN IN MAP, center=(415,768)
	image
	heading Top Tracks
	[1148] link how2fly ISOxo 4:01, center=(617,885), inner_text=how2fly
ISOxo
4:01, url='https://open.spotify.com/track/2fga4JgHuq91W9HiTfo9GC'
		image
		image, url='https://i.scdn.co/image/ab67616d0000b2737afc6c28166fe03f9c84d973'
		StaticText how2fly
		StaticText ISOxo
		StaticText 4:01
	[1160] link Aarena (Knock2 Remix) ISOxo, Knock2 3:27, center=(617,951), inner_text=Aarena (Knock2 Remix)
ISOxo, Knock2
3:27, url='https://open.spotify.com/track/3QdNlDA5ZYzg99r1eafrO8'
		image
		image, url='https://i.scdn.co/image/ab67616d0000b273ea76f3462b6acc7a97614333'
		StaticText Aarena (Knock2 Remix)
		StaticText ISOxo, Knock2
		StaticText 3:27
	[1172] link dontstopme! ISOxo 3:41, center=(617,1017), inner_text=dontstopme!
ISOxo
3:41, url='https://open.spotify.com/track/60tToQgGBi2ZxHLMqkcy5h'
		image
		image, url='https://i.scdn.co/image/ab67616d0000b273fa1210f6e72342dd9efbd990'
		StaticText dontstopme!
		StaticText ISOxo
		StaticText 3:41
	link inhuman ISOxo 3:18, url='https://open.spotify.com/track/72sLsJ5XELHGuV1J6ntJoZ'
		[1188] image, center=(374,1078)
		[1189] image, center=(422,1078), url='https://i.scdn.co/image/ab67616d0000b2739f4da0ea6299dea63e5f5e1d'
		StaticText inhuman
		StaticText ISOxo
		StaticText 3:18
	link kidsgonemad! ISOxo 2:04, url='https://open.spotify.com/track/19X1yhvMTLxwnLF4Onr2bG'
		image
		image, url='https://i.scdn.co/image/ab67616d0000b273fa1210f6e72342dd9efbd990'
		StaticText kidsgonemad!
		StaticText ISOxo
		StaticText 2:04
	[1194] div, center=(854,1074), inner_text=3:18
	[1191] div, center=(480,1070), inner_text=inhuman
	link Angels Landing ISOxo, FrostTop 3:53, url='https://open.spotify.com/track/7z8zdcW66DyZ931P6BjnX7'
		image
		image, url='https://i.scdn.co/image/ab67616d0000b2737be36906998b411e4c524369'
		StaticText Angels Landing
		StaticText ISOxo, FrostTop
		StaticText 3:53
	link murdah (ISOxo Remix) Knock2, ISOxo 2:52, url='https://open.spotify.com/track/1wecjDqjR28ENc6G4oGIBh'
		image
		image, url='https://i.scdn.co/image/ab67616d0000b273ea76f3462b6acc7a97614333'
		StaticText murdah (ISOxo Remix)
		StaticText Knock2, ISOxo
		StaticText 2:52
	link SHYPOP ISOxo, Ninajirachi 3:28, url='https://open.spotify.com/track/7fBzVMo0aAD3GIqhq6zv3s'
		image
		image, url='https://i.scdn.co/image/ab67616d0000b273fa1210f6e72342dd9efbd990'
		StaticText SHYPOP
		StaticText ISOxo, Ninajirachi
		StaticText 3:28
	link Beam (Knock2 Remix) ISOxo, Knock2 4:53, url='https://open.spotify.com/track/0WdxhkZSlDS4HLA3Ly2oQ8'
		image
		image, url='https://i.scdn.co/image/ab67616d0000b273ea76f3462b6acc7a97614333'
		StaticText Beam (Knock2 Remix)
		StaticText ISOxo, Knock2
		StaticText 4:53
	link Jewel RL Grime, ISOxo 4:06, url='https://open.spotify.com/track/7If4RHoV0MLOGkM6smqYFp'
		image
		image, url='https://i.scdn.co/image/ab67616d0000b27357f37328dc33f1fb8f3a3d59'
		StaticText Jewel
		StaticText RL Grime, ISOxo
		StaticText 4:06
	StaticText ISOxo (Friday)
	heading Fri, January 10 • 9PM • Brooklyn Steel
	image
	StaticText Brooklyn
	StaticText ,
	StaticText NY
	[1277] button Buy $109, center=(1108,255), inner_text=Buy
$109
	[1282] button Sell $65, center=(1450,255), inner_text=Sell
$65
	tablist, orientation='horizontal'
		[1294] tab Tickets Available, center=(1112,322), selected=True, type=button
		[1295] tab Interested Buyers, center=(1446,322), selected=False, type=button
	table simple table
		rowgroup
		rowgroup
			row
				cell Profile Picture 1 Ticket Danny
					[1306] image Profile Picture, center=(966,379), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F22e3ba10-58a_user-live-d39f53a0-cca2-432a-8bdd-b0093933e35b.jpg%3Fauto%3Dcompress%26h%3D100&w=1920&q=75'
					StaticText 1 Ticket
					StaticText Danny
				cell $109 ea
					[1313] button $109 ea, center=(1572,379), inner_text=$109
ea
			row
				cell Profile Picture 1 Ticket Linh
					[1323] image Profile Picture, center=(966,454), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F63881be5-c7f_3932b23c-4a45-481c-bc1f-91ddb1741005.jpg%3Fauto%3Dcompress%26h%3D100&w=1920&q=75'
					StaticText 1 Ticket
					StaticText Linh
				cell $120 ea
					[1330] button $120 ea, center=(1572,454), inner_text=$120
ea
			row
				cell Profile Picture 1-2 Tickets Venkat
					[1340] image Profile Picture, center=(966,529), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2Fd4c69317-42f_user-live-f178d81b-ab3b-4b4e-88de-fdae789d25ae.jpg%3Fauto%3Dcompress%26h%3D100&w=1920&q=75'
					StaticText 1-
					StaticText 2
					StaticText Tickets
					StaticText Venkat
				cell $131 ea
					[1347] button $131 ea, center=(1572,529), inner_text=$131
ea
			row
				cell Profile Picture 1-2 Tickets Erjun
					[1357] image Profile Picture, center=(966,604), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F2c9de399-0f5_user-live-370ff31e-4b1e-48af-9e1e-31efc07a8d63.jpg%3Fauto%3Dcompress%26h%3D100&w=1920&q=75'
					StaticText 1-
					StaticText 2
					StaticText Tickets
					StaticText Erjun
				cell $138 ea
					[1364] button $138 ea, center=(1572,604), inner_text=$138
ea
			row
				cell Profile Picture 1-2 Tickets Gus
					[1374] image Profile Picture, center=(966,679), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F5efb8b65-789c-4927-8e9e-5bc3c24344bf.jpg%3Fauto%3Dcompress%26h%3D100&w=1920&q=75'
					StaticText 1-
					StaticText 2
					StaticText Tickets
					StaticText Gus
				cell $139 ea
					[1381] button $139 ea, center=(1572,679), inner_text=$139
ea
			row
				cell Profile Picture 1 Ticket William
					[1391] image Profile Picture, center=(966,754), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F8ceca337-786_223d4bf3-5c6d-491e-be4b-77340ada31bd.jpg%3Fauto%3Dcompress%26h%3D100&w=1920&q=75'
					StaticText 1 Ticket
					StaticText William
				cell $148 ea
					[1398] button $148 ea, center=(1572,754), inner_text=$148
ea
			row
				cell Profile Picture 1-6 Tickets William
					[1408] image Profile Picture, center=(966,829), url='https://www.crowdvolt.com/_next/image?url=https%3A%2F%2Fcrowdvolt-894150087.imgix.net%2F8ceca337-786_223d4bf3-5c6d-491e-be4b-77340ada31bd.jpg%3Fauto%3Dcompress%26h%3D100&w=1920&q=75'
					StaticText 1-
					StaticText 6
					StaticText Tickets
					StaticText William
				cell $180 ea
					[1415] button $180 ea, center=(1572,829), inner_text=$180
ea
	heading Company
	link Careers, url='https://forms.gle/XWQzReTD1pafSZac9'
		heading Careers
	link About, url='https://www.crowdvolt.com/about'
		heading About
	link FAQ, url='https://www.crowdvolt.com/faq'
		heading FAQ
	heading Connect
	link Instagram, url='https://www.instagram.com/crowdvolt/'
		heading Instagram
	link LinkedIn, url='https://www.linkedin.com/company/crowdvolt'
		heading LinkedIn
	link Help, url='https://www.crowdvolt.com/faq'
		heading Help
	heading Resources
	heading Request an Event
	link Privacy Policy, url='https://www.crowdvolt.com/privacy'
		heading Privacy Policy
	link Terms and Conditions, url='https://www.crowdvolt.com/terms_of_service'
		heading Terms and Conditions
	image Y-Combinator, url='https://www.crowdvolt.com/ycom.png'
	heading Backed by Y Combinator
	heading © CrowdVolt 2024
	region Notifications (F8)
		list
	alert, atomic
		StaticText ISOxo (Friday) Brooklyn tickets - Brooklyn Steel - Fri, January 10 | CrowdVolt
```
</details>

**Reasoning for action:** The link identified by 911 is the correct entry for the event I am searching for ('ISOxo Friday'). By clicking on this link, I will be taken to the dedicated event details page, which is crucial for meeting the user's goal of finding ticket purchase options and relevant event information.

**Action:** click(911) # Click on the link for ISOxo (Friday) to view more details about the event.

**Change Description:** After clicking the link for ISOxo (Friday), the browser navigated to a new page displaying the event details for ISOxo at Brooklyn Steel on January 10, including ticket purchase and sale options, as well as top tracks associated with the artist.

**Screenshot before:****Screenshot after:**---


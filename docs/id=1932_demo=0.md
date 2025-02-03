# Task

**Booking a Demo with Time Zone and Cookie Preferences**

As a potential customer,
I explore the demo booking process,
so that I can schedule a demo and manage my time zone and cookie preferences effectively.

**Success definition:** Given I am on the Moving Parts demo booking page after clicking 'Book a demo' link.
When I select my preferred time zone from the options provided and review the cookie consent preferences.
Then I should see my selected time zone displayed on the booking page and have clear options to manage my cookie preferences.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://movingparts.io/

https://calendly.com/moving-parts/demo?month=2025-01

**Content (before/after):** 

```
RootWebArea Moving Parts, focused, url='https://movingparts.io/'
	navigation
		heading Moving Parts
			image
		[29] link Pow, center=(298,84), url='https://movingparts.io/pow/'
```
<details><summary>Show more</summary>

```
		[30] link Articles, center=(408,84), url='https://movingparts.io/articles/'
	banner
		heading Supercharge your mobile team
		paragraph
			StaticText Moving Parts is a library of world-class SwiftUI components that help you ship your app faster.
		[34] link Book a demo, center=(960,577), url='https://calendly.com/moving-parts/demo'
			image
	StaticText MovingParts.
	main
		heading Import engineering excellence
		paragraph
			StaticText We provide you with a great baseline for designing and building for mobile. By taking care of common use-cases, Moving Parts allows you to move fast, maintain less, and prioritize features that actually matter.
		link Book a demo, url='https://calendly.com/moving-parts/demo'
			image
		switch With Moving Parts, checked='false'
		heading Styles easily
		paragraph
			StaticText While our components look great out of the box, they easily adapt to fit your brand’s design language to a tee. Pick and choose from our selection of styles and themes, customize them, or build your own without having to reinvent the wheel.
		heading Localized & Accessible
		paragraph
			StaticText Our components are pre-localized in all iOS-supported languages, support right-to-left layout, and follow all best practices around barrier-free interaction. With Moving Parts, your app remains compliant and new markets are easy to conquer.
		heading Performance matters
		paragraph
			StaticText Every bit of performance and quality matters to get to the best possible conversion rate. We focus relentlessly on responsiveness and performance to deliver an optimal experience, even on older devices or slower network connections.
		heading Compose anything mobile
		paragraph
			StaticText Break apart, piece together, style, iterate, and build experiences that best represent your products and your customers.
		link Book a demo, url='https://calendly.com/moving-parts/demo'
			image
		image
		image
		image
		StaticText AggregateRating
		image
		StaticText CurrencyLabel
		StaticText Offer
		image
		StaticText SingleChoice
		image
		image
		StaticText AsyncMedia
		image
		StaticText ImagePager
		image
		StaticText Markdown
		image Bicycle product detail screen
			image
			image
			StaticText ★ 4.46
			StaticText (416)
			StaticText Helsinki
			StaticText Outback
			StaticText $950
			superscript
				StaticText 00
			StaticText $1250
			superscript
				StaticText 00
			figure
			figure
			figure
			figure
			StaticText DESCRIPTION
			StaticText A longer distance adventure bicycle, optimized for gravel paths and trekking. The geometry is designed to provide a nimble steering, even when riding fast with all your camping gear on the bike.
			StaticText SELECT FRAME SIZE
			StaticText 13 to 15 inches
			StaticText 150 to 160cm
			StaticText 15 to 16 inches
			StaticText 160 to 170cm
			StaticText 16 to 17 inches
			StaticText 170 to 180cm
		heading Fully native, 100% SwiftUI
		paragraph
			StaticText By fully leveraging the SwiftUI framework, Moving Parts blends in seamlessly with the rest of your application. There's no new language to learn, no platform to connect to, and no custom build step.
		heading Standard lockups for common layouts
		paragraph
			StaticText Moving Parts offers turn-key solutions for the most common UX problems. From credit card details to health data, our components achieve high-level goals and never bog you down in details.
		heading Built-in escape hatches
		paragraph
			StaticText Fully adapting to your brand's design language is extremely important to us. Our components are built with complete customizability in mind to never lock you into an aesthetic.
		heading Make it your own
		paragraph
			StaticText Use our components as is or configure them to whatever context you see fit. We make styling easy by allowing you to extend all our components with custom styling or just use one of our included themes.
		link Book a demo, url='https://calendly.com/moving-parts/demo'
			image
		figure
			blockquote
				paragraph
					StaticText “SwiftUI is the future of interface programming on Apple Platforms, and Moving Parts has one of the best teams to help your company make the most of SwiftUI. Their components provide a stunning amount of detail that is typically only found in products with very large teams. By working with Moving Parts you can use these well-crafted parts in your app today.”
			Figcaption
				image Chris Eidhof, url='https://movingparts.io/frontpage/testimonial-1.png'
				StaticText CHRIS EIDHOF
				StaticText FOUNDER,
				link OBJC.IO, url='https://www.objc.io/'
		figure
			blockquote
				paragraph
					StaticText “Moving Parts acts as a force multiplier for our team, allowing development of world class commerce experiences at an unprecedented pace. The components are simply a delight to use and bring a level of quality that would have previously been out of reach.”
			Figcaption
				image Tom Hutchinson, url='https://movingparts.io/frontpage/testimonial-2.png'
				StaticText TOM HUTCHINSON
				StaticText HEAD OF MOBILE,
				link RAPHA RACING, url='https://www.rapha.cc/'
		figure
			blockquote
				paragraph
					StaticText “Custom UI is expensive. It takes time to polish essential interactions to the level our customers expect, and it takes even more time down the road to maintain that polish as major OS versions change things under our feet. Moving Parts fills essential gaps in SwiftUI, using an API design your team will find familiar, leaving more time, energy, and budget to finish the things only your app can do.”
			Figcaption
				image Danilo Campos, url='https://movingparts.io/frontpage/testimonial-3.png'
				StaticText DANILO CAMPOS
				StaticText FORMER HEAD OF MOBILE PRODUCT & ENGINEERING,
				link SEDNA SYSTEMS, url='https://sedna.com/'
		figure
			blockquote
				paragraph
					StaticText “Everything Moving Parts builds and writes is so top-notch.”
			Figcaption
				image Paul Stamatiou, url='https://movingparts.io/frontpage/testimonial-4.png'
				StaticText PAUL STAMATIOU
				StaticText PRINCIPAL DESIGNER,
				link KRAKEN EXCHANGE, url='https://www.kraken.com/'
		heading SUPPORTED BY
		image Y Combinator
		image Haystack
		image Notion
		heading Ready to level up your mobile team?
		link Book a demo, url='https://calendly.com/moving-parts/demo'
			image
		heading Articles
		link, url='https://movingparts.io/gradient-meshes'
			figure
				Figcaption
					StaticText ROBB
					StaticText •
					StaticText MAY 20, 2021
				heading Gradient Meshes in SceneKit
				paragraph
					StaticText How to build two-dimensional gradient meshes with SceneKit.
		link, url='https://movingparts.io/variadic-views-in-swiftui'
			figure
				Figcaption
					StaticText ROBB
					StaticText •
					StaticText FEB 24, 2022
				heading SwiftUI under the Hood: Variadic Views
				paragraph
					StaticText After some spelunking in SwiftUI internals, we discover how to write better container views.
		link, url='https://movingparts.io/styling-components-in-swiftui'
			figure
				Figcaption
					StaticText KASPER
					StaticText •
					StaticText JAN 31, 2023
				heading Styling Components in SwiftUI.
				paragraph
					StaticText We'll look at how we can style custom views in the same way as native SwiftUI views.
		link View all articles, url='https://movingparts.io/articles/'
			image
		heading Join our mailing list
		textbox Your mail address
		button Sign Up
		paragraph
			StaticText We promise we’ll only send you emails that are actually worthwhile.
			StaticText Not feeling like more email? Follow us on
			link Mastodon, url='https://mastodon.social/@movingparts'
			StaticText or
			link Twitter, url='https://twitter.com/movingpartsio'
			StaticText .
		image
		navigation Social
			heading SOCIAL
			link MASTODON, url='https://mastodon.social/@movingparts'
			link TWITTER, url='https://twitter.com/movingpartsio'
			link INSTAGRAM, url='https://www.instagram.com/movingparts.io/'
```
</details>



```
RootWebArea Select a Date & Time - Calendly, focused, url='https://calendly.com/moving-parts/demo?month=2025-01'
	[53] link POWERED BY Calendly, center=(1312,114), inner_text=POWERED BY
Calendly, url='https://calendly.com/?utm_campaign=sign_up&utm_medium=badge&utm_source=invitee'
	image Company logo, url='https://d3v0px0pttie1i.cloudfront.net/uploads/user/logo/12271368/555ddb3d.png'
	image Moving Parts, url='https://d3v0px0pttie1i.cloudfront.net/uploads/user/avatar/12271368/21b5036c.png'
```
<details><summary>Show more</summary>

```
	StaticText Moving Parts
	heading Moving Parts Demo
	StaticText 30 min
	StaticText Web conferencing details provided upon confirmation.
	[92] button Cookie settings, center=(646,728), type=button
	[95] link Report abuse, center=(887,728), url='https://calendly.com/abuse_reports/new?source=RW9BOyg-vtR7sHTKbWRToB0FfTq83AIJGHAtmJaooU5w0TulNDTw7UPQNrBmQSmxHBZxQ-wWx5EeRtGr8T7d5eSkyz6gpywLUTB2tWz5'
	heading Select a Date & Time
	button Go to previous month, disabled=True
	StaticText January 2025
	button Go to next month, disabled=True
	status, atomic
		StaticText January is now displayed
	table Select a Day
		rowgroup
			row
				columnheader SUN
				columnheader MON
				columnheader TUE
				columnheader WED
				columnheader THU
				columnheader FRI
				columnheader SAT
		rowgroup
			row
				gridcell
				gridcell
				gridcell
				gridcell Wednesday, January 1 - No times available
					button Wednesday, January 1 - No times available, disabled=True
				gridcell Thursday, January 2 - No times available
					button Thursday, January 2 - No times available, disabled=True
				gridcell Friday, January 3 - No times available
					button Friday, January 3 - No times available, disabled=True
				gridcell Saturday, January 4 - No times available
					button Saturday, January 4 - No times available, disabled=True
			row
				gridcell Sunday, January 5 - No times available
					button Sunday, January 5 - No times available, disabled=True
				gridcell Monday, January 6 - No times available
					button Monday, January 6 - No times available, disabled=True
				gridcell Tuesday, January 7 - No times available
					button Tuesday, January 7 - No times available, disabled=True
				gridcell Wednesday, January 8 - No times available
					button Wednesday, January 8 - No times available, disabled=True
				gridcell Thursday, January 9 - No times available
					button Thursday, January 9 - No times available, disabled=True
				gridcell Friday, January 10 - No times available
					button Friday, January 10 - No times available, disabled=True
				gridcell Saturday, January 11 - No times available
					button Saturday, January 11 - No times available, disabled=True
			row
				gridcell Sunday, January 12 - No times available
					button Sunday, January 12 - No times available, disabled=True
				gridcell Monday, January 13 - No times available
					button Monday, January 13 - No times available, disabled=True
				gridcell Tuesday, January 14 - No times available
					button Tuesday, January 14 - No times available, disabled=True
				gridcell Wednesday, January 15 - No times available
					button Wednesday, January 15 - No times available, disabled=True
				gridcell Thursday, January 16 - No times available
					button Thursday, January 16 - No times available, disabled=True
				gridcell Friday, January 17 - No times available
					button Friday, January 17 - No times available, disabled=True
				gridcell Saturday, January 18 - No times available
					button Saturday, January 18 - No times available, disabled=True
			row
				gridcell Sunday, January 19 - No times available
					button Sunday, January 19 - No times available, disabled=True
				gridcell Monday, January 20 - No times available
					button Monday, January 20 - No times available, disabled=True
				gridcell Tuesday, January 21 - No times available
					button Tuesday, January 21 - No times available, disabled=True
				gridcell Wednesday, January 22 - No times available
					button Wednesday, January 22 - No times available, disabled=True
				gridcell Thursday, January 23 - No times available
					button Thursday, January 23 - No times available, disabled=True
				gridcell Friday, January 24 - No times available
					button Friday, January 24 - No times available, disabled=True
				gridcell Saturday, January 25 - No times available
					button Saturday, January 25 - No times available, disabled=True
			row
				gridcell Sunday, January 26 - No times available
					button Sunday, January 26 - No times available, disabled=True
				gridcell Monday, January 27 - No times available
					button Monday, January 27 - No times available, disabled=True
				gridcell Tuesday, January 28 - No times available
					button Tuesday, January 28 - No times available, disabled=True
				gridcell Wednesday, January 29 - No times available
					button Wednesday, January 29 - No times available, disabled=True
				gridcell Thursday, January 30 - No times available
					button Thursday, January 30 - No times available, disabled=True
				gridcell Friday, January 31 - No times available
					button Friday, January 31 - No times available, disabled=True
				gridcell
	StaticText No times in January
	status, atomic
	paragraph
		StaticText Time zone
	[245] button Time zone  UTC Time (2:11pm) , center=(1075,556), expanded=False, inner_text=UTC Time
(2:11pm), type=button
	region Cookie banner
		alertdialog We respect your personal privacy, modal=False
			StaticText We respect your personal privacy
			StaticText We and our partners use cookies, pixels, and similar tracking technology (all called “cookies” here), including necessary cookies to provide our websites and optional cookies to collect information from you (including your clicks, cursor movements, and screen recordings on our websites) for site functionality and personalization, usage analytics, and marketing. You consent to our use of all cookies by choosing “l understand” or continuing to use this website. You may decline optional cookies by choosing "Do not allow cookies". We honor opt-out preference signals.
			[268] link Click here, center=(514,933), url='https://calendly.com/privacy'
			StaticText to read about how we use your personal data.
			[272] button Do not allow cookies, center=(372,1003)
			[273] button I understand, center=(510,1003)
			[274] button Cookie settings, center=(99,1003)
			[277] button Close, center=(560,764)
```
</details>

**Reasoning for action:** I chose to click on the 'Book a demo' link (index 34) because it's the primary call to action for users wanting to schedule a demo. By navigating to this specific page, I can now proceed with selecting a time zone from the options provided and reviewing the cookie consent preferences, thereby moving closer to fulfilling the user's objective of exploring the demo booking process.

**Action:** click(34) # Click on the 'Book a demo' link to explore the demo booking process.

**Change Description:** After clicking the 'Book a demo' link, the browser transitioned to a new page displaying the 'Select a Date & Time' interface for scheduling a demo with Moving Parts, eliminating the previous content about the Moving Parts library and replacing it with a calendar and related options.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://calendly.com/moving-parts/demo?month=2025-01

https://calendly.com/moving-parts/demo?month=2025-01

**Content (before/after):** 

```
RootWebArea Select a Date & Time - Calendly, focused, url='https://calendly.com/moving-parts/demo?month=2025-01'
	[53] link POWERED BY Calendly, center=(1312,114), inner_text=POWERED BY
Calendly, url='https://calendly.com/?utm_campaign=sign_up&utm_medium=badge&utm_source=invitee'
	image Company logo, url='https://d3v0px0pttie1i.cloudfront.net/uploads/user/logo/12271368/555ddb3d.png'
	image Moving Parts, url='https://d3v0px0pttie1i.cloudfront.net/uploads/user/avatar/12271368/21b5036c.png'
```
<details><summary>Show more</summary>

```
	StaticText Moving Parts
	heading Moving Parts Demo
	StaticText 30 min
	StaticText Web conferencing details provided upon confirmation.
	[92] button Cookie settings, center=(646,728), type=button
	[95] link Report abuse, center=(887,728), url='https://calendly.com/abuse_reports/new?source=RW9BOyg-vtR7sHTKbWRToB0FfTq83AIJGHAtmJaooU5w0TulNDTw7UPQNrBmQSmxHBZxQ-wWx5EeRtGr8T7d5eSkyz6gpywLUTB2tWz5'
	heading Select a Date & Time
	button Go to previous month, disabled=True
	StaticText January 2025
	button Go to next month, disabled=True
	status, atomic
		StaticText January is now displayed
	table Select a Day
		rowgroup
			row
				columnheader SUN
				columnheader MON
				columnheader TUE
				columnheader WED
				columnheader THU
				columnheader FRI
				columnheader SAT
		rowgroup
			row
				gridcell
				gridcell
				gridcell
				gridcell Wednesday, January 1 - No times available
					button Wednesday, January 1 - No times available, disabled=True
				gridcell Thursday, January 2 - No times available
					button Thursday, January 2 - No times available, disabled=True
				gridcell Friday, January 3 - No times available
					button Friday, January 3 - No times available, disabled=True
				gridcell Saturday, January 4 - No times available
					button Saturday, January 4 - No times available, disabled=True
			row
				gridcell Sunday, January 5 - No times available
					button Sunday, January 5 - No times available, disabled=True
				gridcell Monday, January 6 - No times available
					button Monday, January 6 - No times available, disabled=True
				gridcell Tuesday, January 7 - No times available
					button Tuesday, January 7 - No times available, disabled=True
				gridcell Wednesday, January 8 - No times available
					button Wednesday, January 8 - No times available, disabled=True
				gridcell Thursday, January 9 - No times available
					button Thursday, January 9 - No times available, disabled=True
				gridcell Friday, January 10 - No times available
					button Friday, January 10 - No times available, disabled=True
				gridcell Saturday, January 11 - No times available
					button Saturday, January 11 - No times available, disabled=True
			row
				gridcell Sunday, January 12 - No times available
					button Sunday, January 12 - No times available, disabled=True
				gridcell Monday, January 13 - No times available
					button Monday, January 13 - No times available, disabled=True
				gridcell Tuesday, January 14 - No times available
					button Tuesday, January 14 - No times available, disabled=True
				gridcell Wednesday, January 15 - No times available
					button Wednesday, January 15 - No times available, disabled=True
				gridcell Thursday, January 16 - No times available
					button Thursday, January 16 - No times available, disabled=True
				gridcell Friday, January 17 - No times available
					button Friday, January 17 - No times available, disabled=True
				gridcell Saturday, January 18 - No times available
					button Saturday, January 18 - No times available, disabled=True
			row
				gridcell Sunday, January 19 - No times available
					button Sunday, January 19 - No times available, disabled=True
				gridcell Monday, January 20 - No times available
					button Monday, January 20 - No times available, disabled=True
				gridcell Tuesday, January 21 - No times available
					button Tuesday, January 21 - No times available, disabled=True
				gridcell Wednesday, January 22 - No times available
					button Wednesday, January 22 - No times available, disabled=True
				gridcell Thursday, January 23 - No times available
					button Thursday, January 23 - No times available, disabled=True
				gridcell Friday, January 24 - No times available
					button Friday, January 24 - No times available, disabled=True
				gridcell Saturday, January 25 - No times available
					button Saturday, January 25 - No times available, disabled=True
			row
				gridcell Sunday, January 26 - No times available
					button Sunday, January 26 - No times available, disabled=True
				gridcell Monday, January 27 - No times available
					button Monday, January 27 - No times available, disabled=True
				gridcell Tuesday, January 28 - No times available
					button Tuesday, January 28 - No times available, disabled=True
				gridcell Wednesday, January 29 - No times available
					button Wednesday, January 29 - No times available, disabled=True
				gridcell Thursday, January 30 - No times available
					button Thursday, January 30 - No times available, disabled=True
				gridcell Friday, January 31 - No times available
					button Friday, January 31 - No times available, disabled=True
				gridcell
	StaticText No times in January
	status, atomic
	paragraph
		StaticText Time zone
	[245] button Time zone  UTC Time (2:11pm) , center=(1075,556), expanded=False, inner_text=UTC Time
(2:11pm), type=button
	region Cookie banner
		alertdialog We respect your personal privacy, modal=False
			StaticText We respect your personal privacy
			StaticText We and our partners use cookies, pixels, and similar tracking technology (all called “cookies” here), including necessary cookies to provide our websites and optional cookies to collect information from you (including your clicks, cursor movements, and screen recordings on our websites) for site functionality and personalization, usage analytics, and marketing. You consent to our use of all cookies by choosing “l understand” or continuing to use this website. You may decline optional cookies by choosing "Do not allow cookies". We honor opt-out preference signals.
			[268] link Click here, center=(514,933), url='https://calendly.com/privacy'
			StaticText to read about how we use your personal data.
			[272] button Do not allow cookies, center=(372,1003)
			[273] button I understand, center=(510,1003)
			[274] button Cookie settings, center=(99,1003)
			[277] button Close, center=(560,764)
```
</details>



```
RootWebArea Select a Date & Time - Calendly, focused, url='https://calendly.com/moving-parts/demo?month=2025-01'
	[53] link POWERED BY Calendly, center=(1312,114), inner_text=POWERED BY
Calendly, url='https://calendly.com/?utm_campaign=sign_up&utm_medium=badge&utm_source=invitee'
	image Company logo, url='https://d3v0px0pttie1i.cloudfront.net/uploads/user/logo/12271368/555ddb3d.png'
	image Moving Parts, url='https://d3v0px0pttie1i.cloudfront.net/uploads/user/avatar/12271368/21b5036c.png'
```
<details><summary>Show more</summary>

```
	StaticText Moving Parts
	heading Moving Parts Demo
	StaticText 30 min
	StaticText Web conferencing details provided upon confirmation.
	[92] button Cookie settings, center=(646,728), type=button
	[95] link Report abuse, center=(887,728), url='https://calendly.com/abuse_reports/new?source=RW9BOyg-vtR7sHTKbWRToB0FfTq83AIJGHAtmJaooU5w0TulNDTw7UPQNrBmQSmxHBZxQ-wWx5EeRtGr8T7d5eSkyz6gpywLUTB2tWz5'
	heading Select a Date & Time
	button Go to previous month, disabled=True
	StaticText January 2025
	button Go to next month, disabled=True
	status, atomic
		StaticText January is now displayed
	table Select a Day
		rowgroup
			row
				columnheader SUN
				columnheader MON
				columnheader TUE
				columnheader WED
				columnheader THU
				columnheader FRI
				columnheader SAT
		rowgroup
			row
				gridcell
				gridcell
				gridcell
				gridcell Wednesday, January 1 - No times available
					button Wednesday, January 1 - No times available, disabled=True
				gridcell Thursday, January 2 - No times available
					button Thursday, January 2 - No times available, disabled=True
				gridcell Friday, January 3 - No times available
					button Friday, January 3 - No times available, disabled=True
				gridcell Saturday, January 4 - No times available
					button Saturday, January 4 - No times available, disabled=True
			row
				gridcell Sunday, January 5 - No times available
					button Sunday, January 5 - No times available, disabled=True
				gridcell Monday, January 6 - No times available
					button Monday, January 6 - No times available, disabled=True
				gridcell Tuesday, January 7 - No times available
					button Tuesday, January 7 - No times available, disabled=True
				gridcell Wednesday, January 8 - No times available
					button Wednesday, January 8 - No times available, disabled=True
				gridcell Thursday, January 9 - No times available
					button Thursday, January 9 - No times available, disabled=True
				gridcell Friday, January 10 - No times available
					button Friday, January 10 - No times available, disabled=True
				gridcell Saturday, January 11 - No times available
					button Saturday, January 11 - No times available, disabled=True
			row
				gridcell Sunday, January 12 - No times available
					button Sunday, January 12 - No times available, disabled=True
				gridcell Monday, January 13 - No times available
					button Monday, January 13 - No times available, disabled=True
				gridcell Tuesday, January 14 - No times available
					button Tuesday, January 14 - No times available, disabled=True
				gridcell Wednesday, January 15 - No times available
					button Wednesday, January 15 - No times available, disabled=True
				gridcell Thursday, January 16 - No times available
					button Thursday, January 16 - No times available, disabled=True
				gridcell Friday, January 17 - No times available
					button Friday, January 17 - No times available, disabled=True
				gridcell Saturday, January 18 - No times available
					button Saturday, January 18 - No times available, disabled=True
			row
				gridcell Sunday, January 19 - No times available
					button Sunday, January 19 - No times available, disabled=True
				gridcell Monday, January 20 - No times available
					button Monday, January 20 - No times available, disabled=True
				gridcell Tuesday, January 21 - No times available
					button Tuesday, January 21 - No times available, disabled=True
				gridcell Wednesday, January 22 - No times available
					button Wednesday, January 22 - No times available, disabled=True
				gridcell Thursday, January 23 - No times available
					button Thursday, January 23 - No times available, disabled=True
				gridcell Friday, January 24 - No times available
					button Friday, January 24 - No times available, disabled=True
				gridcell Saturday, January 25 - No times available
					button Saturday, January 25 - No times available, disabled=True
			row
				gridcell Sunday, January 26 - No times available
					button Sunday, January 26 - No times available, disabled=True
				gridcell Monday, January 27 - No times available
					button Monday, January 27 - No times available, disabled=True
				gridcell Tuesday, January 28 - No times available
					button Tuesday, January 28 - No times available, disabled=True
				gridcell Wednesday, January 29 - No times available
					button Wednesday, January 29 - No times available, disabled=True
				gridcell Thursday, January 30 - No times available
					button Thursday, January 30 - No times available, disabled=True
				gridcell Friday, January 31 - No times available
					button Friday, January 31 - No times available, disabled=True
				gridcell
	StaticText No times in January
	status, atomic
	paragraph
		StaticText Time zone
	[245] button Time zone  UTC Time (2:11pm) , center=(1075,556), expanded=True, inner_text=UTC Time
(2:11pm), type=button
	[424] textbox Search..., center=(1160,261), contenteditable=True, focused, type=text
	StaticText TIME ZONE
	group Time format
		LabelText
			radio am/pm, checked='true'
		LabelText
			radio 24h, checked='false'
	listbox Time zone, orientation='vertical'
		group US/CANADA
			option Pacific Time - US & Canada 6:11am, selected=False
			option Mountain Time - US & Canada 7:11am, selected=False
			option Central Time - US & Canada 8:11am, selected=False
			option Eastern Time - US & Canada 9:11am, selected=False
			option Alaska Time 5:11am, selected=False
			option Arizona, Yukon Time 7:11am, selected=False
			option Newfoundland Time 10:41am, selected=False
			option Hawaii Time 4:11am, selected=False
		group AMERICA
			option America/Adak 4:11am, selected=False
			option Buenos Aires Time 11:11am, selected=False
			option Asuncion Time 11:11am, selected=False
			option Bogota, Jamaica, Lima Time 9:11am, selected=False
			option America/Campo Grande 10:11am, selected=False
			option Caracas Time 10:11am, selected=False
			option America/Godthab 12:11pm, selected=False
			option Atlantic Time 10:11am, selected=False
			option Saskatchewan, Guatemala, Costa Rica Time 8:11am, selected=False
			option America/Havana 9:11am, selected=False
			option America/Mazatlan 7:11am, selected=False
			option Mexico City Time 8:11am, selected=False
			option Montevideo Time 11:11am, selected=False
			option America/Miquelon 11:11am, selected=False
			option America/Noronha 12:11pm, selected=False
			option Santiago Time 11:11am, selected=False
			option America/Santa Isabel 6:11am, selected=False
			option Atlantic Standard Time 10:11am, selected=False
			option Brasilia Time 11:11am, selected=False
		group AFRICA
			option Africa/Cairo 4:11pm, selected=False
			option Central Africa Time 4:11pm, selected=False
			option West Africa Time 3:11pm, selected=False
			option Africa/Windhoek 4:11pm, selected=False
		group ASIA
			option Jordan Time 5:11pm, selected=False
			option Baghdad, East Africa Time 5:11pm, selected=False
			option Asia/Baku 6:11pm, selected=False
			option Lebanon Time 4:11pm, selected=False
			option Syria Time 5:11pm, selected=False
			option Asia/Dhaka 8:11pm, selected=False
			option Dubai Time 6:11pm, selected=False
			option Asia/Gaza 4:11pm, selected=False
			option Asia/Irkutsk 10:11pm, selected=False
			option Indochina Time 9:11pm, selected=False
			option Israel Time 4:11pm, selected=False
			option Kabul Time 6:41pm, selected=False
			option Pacific/Majuro 2:11am, selected=False
			option Pakistan, Maldives Time 7:11pm, selected=False
			option Kathmandu Time 7:56pm, selected=False
			option India, Sri Lanka Time 7:41pm, selected=False
			option Krasnoyarsk Time 9:11pm, selected=False
			option Asia/Omsk 8:11pm, selected=False
			option Asia/Rangoon 8:41pm, selected=False
			option China, Singapore, Perth 10:11pm, selected=False
			option Tehran Time 5:41pm, selected=False
			option Japan, Korea Time 11:11pm, selected=False
			option Asia/Vladivostok 12:11am, selected=False
			option Asia/Yakutsk 11:11pm, selected=False
			option Yekaterinburg Time 7:11pm, selected=False
			option Asia/Yerevan 6:11pm, selected=False
		group ATLANTIC
			option Azores Time 1:11pm, selected=False
			option Cape Verde Time 1:11pm, selected=False
		group AUSTRALIA
			option Adelaide Time 12:41am, selected=False
			option Brisbane Time 12:11am, selected=False
			option Australia/Darwin 11:41pm, selected=False
			option Australia/Eucla 10:56pm, selected=False
			option Australia/Lord Howe 1:11am, selected=False
			option Australia/Perth 10:11pm, selected=False
			[706] option Sydney, Melbourne Time 1:11am, center=(1160,360), inner_text=Sydney, Melbourne Time
1:11am, selected=False, type=button
		group UTC
			[712] option UTC Time 2:11pm, center=(1160,432), inner_text=UTC Time
2:11pm, selected=True, type=button
		group EUROPE
			[718] option Central European Time 3:11pm, center=(1160,504), inner_text=Central European Time
3:11pm, selected=False, type=button
			option Eastern European Time 4:11pm, selected=False
			option UK, Ireland, Lisbon Time 2:11pm, selected=False
			option Minsk Time 5:11pm, selected=False
			option Moscow Time 5:11pm, selected=False
			option Turkey Time 5:11pm, selected=False
		group PACIFIC
			option Pacific/Apia 3:11am, selected=False
			option Auckland Time 3:11am, selected=False
			option Pacific/Chatham 3:56am, selected=False
			option Pacific/Easter 9:11am, selected=False
			option Pacific/Fiji 2:11am, selected=False
			option Pacific/Gambier 5:11am, selected=False
			option Pacific/Kiritimati 4:11am, selected=False
			option Pacific/Majuro 2:11am, selected=False
			option Pacific/Marquesas 4:41am, selected=False
			option Pacific/Norfolk 2:11am, selected=False
			option Pacific/Noumea 1:11am, selected=False
			option Pacific/Pago Pago 3:11am, selected=False
			option Pacific/Pitcairn 6:11am, selected=False
			option Pacific/Tarawa 2:11am, selected=False
			option Pacific/Tongatapu 3:11am, selected=False
```
</details>

**Reasoning for action:** By clicking on the 'Time zone' button, I am enabling the user to select their preferred time zone from a dropdown or selection menu that will appear. This step is essential in ensuring that the user can manage their time zone preferences effectively, which is part of the overall goal of completing the demo booking process.

**Action:** click(245) # Click on the 'Time zone' button to explore time zone options.

**Change Description:** The 'Time zone' button was clicked to expand its options, revealing the time zone selection interface which now includes a list of time zones categorized by regions, allowing the user to select their preferred time zone. Additionally, the 'Time zone' button now displays as expanded, indicating active user interaction.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://calendly.com/moving-parts/demo?month=2025-01

https://calendly.com/moving-parts/demo?month=2025-01

**Content (before/after):** 

```
RootWebArea Select a Date & Time - Calendly, focused, url='https://calendly.com/moving-parts/demo?month=2025-01'
	[53] link POWERED BY Calendly, center=(1312,114), inner_text=POWERED BY
Calendly, url='https://calendly.com/?utm_campaign=sign_up&utm_medium=badge&utm_source=invitee'
	image Company logo, url='https://d3v0px0pttie1i.cloudfront.net/uploads/user/logo/12271368/555ddb3d.png'
	image Moving Parts, url='https://d3v0px0pttie1i.cloudfront.net/uploads/user/avatar/12271368/21b5036c.png'
```
<details><summary>Show more</summary>

```
	StaticText Moving Parts
	heading Moving Parts Demo
	StaticText 30 min
	StaticText Web conferencing details provided upon confirmation.
	[92] button Cookie settings, center=(646,728), type=button
	[95] link Report abuse, center=(887,728), url='https://calendly.com/abuse_reports/new?source=RW9BOyg-vtR7sHTKbWRToB0FfTq83AIJGHAtmJaooU5w0TulNDTw7UPQNrBmQSmxHBZxQ-wWx5EeRtGr8T7d5eSkyz6gpywLUTB2tWz5'
	heading Select a Date & Time
	button Go to previous month, disabled=True
	StaticText January 2025
	button Go to next month, disabled=True
	status, atomic
		StaticText January is now displayed
	table Select a Day
		rowgroup
			row
				columnheader SUN
				columnheader MON
				columnheader TUE
				columnheader WED
				columnheader THU
				columnheader FRI
				columnheader SAT
		rowgroup
			row
				gridcell
				gridcell
				gridcell
				gridcell Wednesday, January 1 - No times available
					button Wednesday, January 1 - No times available, disabled=True
				gridcell Thursday, January 2 - No times available
					button Thursday, January 2 - No times available, disabled=True
				gridcell Friday, January 3 - No times available
					button Friday, January 3 - No times available, disabled=True
				gridcell Saturday, January 4 - No times available
					button Saturday, January 4 - No times available, disabled=True
			row
				gridcell Sunday, January 5 - No times available
					button Sunday, January 5 - No times available, disabled=True
				gridcell Monday, January 6 - No times available
					button Monday, January 6 - No times available, disabled=True
				gridcell Tuesday, January 7 - No times available
					button Tuesday, January 7 - No times available, disabled=True
				gridcell Wednesday, January 8 - No times available
					button Wednesday, January 8 - No times available, disabled=True
				gridcell Thursday, January 9 - No times available
					button Thursday, January 9 - No times available, disabled=True
				gridcell Friday, January 10 - No times available
					button Friday, January 10 - No times available, disabled=True
				gridcell Saturday, January 11 - No times available
					button Saturday, January 11 - No times available, disabled=True
			row
				gridcell Sunday, January 12 - No times available
					button Sunday, January 12 - No times available, disabled=True
				gridcell Monday, January 13 - No times available
					button Monday, January 13 - No times available, disabled=True
				gridcell Tuesday, January 14 - No times available
					button Tuesday, January 14 - No times available, disabled=True
				gridcell Wednesday, January 15 - No times available
					button Wednesday, January 15 - No times available, disabled=True
				gridcell Thursday, January 16 - No times available
					button Thursday, January 16 - No times available, disabled=True
				gridcell Friday, January 17 - No times available
					button Friday, January 17 - No times available, disabled=True
				gridcell Saturday, January 18 - No times available
					button Saturday, January 18 - No times available, disabled=True
			row
				gridcell Sunday, January 19 - No times available
					button Sunday, January 19 - No times available, disabled=True
				gridcell Monday, January 20 - No times available
					button Monday, January 20 - No times available, disabled=True
				gridcell Tuesday, January 21 - No times available
					button Tuesday, January 21 - No times available, disabled=True
				gridcell Wednesday, January 22 - No times available
					button Wednesday, January 22 - No times available, disabled=True
				gridcell Thursday, January 23 - No times available
					button Thursday, January 23 - No times available, disabled=True
				gridcell Friday, January 24 - No times available
					button Friday, January 24 - No times available, disabled=True
				gridcell Saturday, January 25 - No times available
					button Saturday, January 25 - No times available, disabled=True
			row
				gridcell Sunday, January 26 - No times available
					button Sunday, January 26 - No times available, disabled=True
				gridcell Monday, January 27 - No times available
					button Monday, January 27 - No times available, disabled=True
				gridcell Tuesday, January 28 - No times available
					button Tuesday, January 28 - No times available, disabled=True
				gridcell Wednesday, January 29 - No times available
					button Wednesday, January 29 - No times available, disabled=True
				gridcell Thursday, January 30 - No times available
					button Thursday, January 30 - No times available, disabled=True
				gridcell Friday, January 31 - No times available
					button Friday, January 31 - No times available, disabled=True
				gridcell
	StaticText No times in January
	status, atomic
	paragraph
		StaticText Time zone
	[245] button Time zone  UTC Time (2:11pm) , center=(1075,556), expanded=True, inner_text=UTC Time
(2:11pm), type=button
	[424] textbox Search..., center=(1160,261), contenteditable=True, focused, type=text
	StaticText TIME ZONE
	group Time format
		LabelText
			radio am/pm, checked='true'
		LabelText
			radio 24h, checked='false'
	listbox Time zone, orientation='vertical'
		group US/CANADA
			option Pacific Time - US & Canada 6:11am, selected=False
			option Mountain Time - US & Canada 7:11am, selected=False
			option Central Time - US & Canada 8:11am, selected=False
			option Eastern Time - US & Canada 9:11am, selected=False
			option Alaska Time 5:11am, selected=False
			option Arizona, Yukon Time 7:11am, selected=False
			option Newfoundland Time 10:41am, selected=False
			option Hawaii Time 4:11am, selected=False
		group AMERICA
			option America/Adak 4:11am, selected=False
			option Buenos Aires Time 11:11am, selected=False
			option Asuncion Time 11:11am, selected=False
			option Bogota, Jamaica, Lima Time 9:11am, selected=False
			option America/Campo Grande 10:11am, selected=False
			option Caracas Time 10:11am, selected=False
			option America/Godthab 12:11pm, selected=False
			option Atlantic Time 10:11am, selected=False
			option Saskatchewan, Guatemala, Costa Rica Time 8:11am, selected=False
			option America/Havana 9:11am, selected=False
			option America/Mazatlan 7:11am, selected=False
			option Mexico City Time 8:11am, selected=False
			option Montevideo Time 11:11am, selected=False
			option America/Miquelon 11:11am, selected=False
			option America/Noronha 12:11pm, selected=False
			option Santiago Time 11:11am, selected=False
			option America/Santa Isabel 6:11am, selected=False
			option Atlantic Standard Time 10:11am, selected=False
			option Brasilia Time 11:11am, selected=False
		group AFRICA
			option Africa/Cairo 4:11pm, selected=False
			option Central Africa Time 4:11pm, selected=False
			option West Africa Time 3:11pm, selected=False
			option Africa/Windhoek 4:11pm, selected=False
		group ASIA
			option Jordan Time 5:11pm, selected=False
			option Baghdad, East Africa Time 5:11pm, selected=False
			option Asia/Baku 6:11pm, selected=False
			option Lebanon Time 4:11pm, selected=False
			option Syria Time 5:11pm, selected=False
			option Asia/Dhaka 8:11pm, selected=False
			option Dubai Time 6:11pm, selected=False
			option Asia/Gaza 4:11pm, selected=False
			option Asia/Irkutsk 10:11pm, selected=False
			option Indochina Time 9:11pm, selected=False
			option Israel Time 4:11pm, selected=False
			option Kabul Time 6:41pm, selected=False
			option Pacific/Majuro 2:11am, selected=False
			option Pakistan, Maldives Time 7:11pm, selected=False
			option Kathmandu Time 7:56pm, selected=False
			option India, Sri Lanka Time 7:41pm, selected=False
			option Krasnoyarsk Time 9:11pm, selected=False
			option Asia/Omsk 8:11pm, selected=False
			option Asia/Rangoon 8:41pm, selected=False
			option China, Singapore, Perth 10:11pm, selected=False
			option Tehran Time 5:41pm, selected=False
			option Japan, Korea Time 11:11pm, selected=False
			option Asia/Vladivostok 12:11am, selected=False
			option Asia/Yakutsk 11:11pm, selected=False
			option Yekaterinburg Time 7:11pm, selected=False
			option Asia/Yerevan 6:11pm, selected=False
		group ATLANTIC
			option Azores Time 1:11pm, selected=False
			option Cape Verde Time 1:11pm, selected=False
		group AUSTRALIA
			option Adelaide Time 12:41am, selected=False
			option Brisbane Time 12:11am, selected=False
			option Australia/Darwin 11:41pm, selected=False
			option Australia/Eucla 10:56pm, selected=False
			option Australia/Lord Howe 1:11am, selected=False
			option Australia/Perth 10:11pm, selected=False
			[706] option Sydney, Melbourne Time 1:11am, center=(1160,360), inner_text=Sydney, Melbourne Time
1:11am, selected=False, type=button
		group UTC
			[712] option UTC Time 2:11pm, center=(1160,432), inner_text=UTC Time
2:11pm, selected=True, type=button
		group EUROPE
			[718] option Central European Time 3:11pm, center=(1160,504), inner_text=Central European Time
3:11pm, selected=False, type=button
			option Eastern European Time 4:11pm, selected=False
			option UK, Ireland, Lisbon Time 2:11pm, selected=False
			option Minsk Time 5:11pm, selected=False
			option Moscow Time 5:11pm, selected=False
			option Turkey Time 5:11pm, selected=False
		group PACIFIC
			option Pacific/Apia 3:11am, selected=False
			option Auckland Time 3:11am, selected=False
			option Pacific/Chatham 3:56am, selected=False
			option Pacific/Easter 9:11am, selected=False
			option Pacific/Fiji 2:11am, selected=False
			option Pacific/Gambier 5:11am, selected=False
			option Pacific/Kiritimati 4:11am, selected=False
			option Pacific/Majuro 2:11am, selected=False
			option Pacific/Marquesas 4:41am, selected=False
			option Pacific/Norfolk 2:11am, selected=False
			option Pacific/Noumea 1:11am, selected=False
			option Pacific/Pago Pago 3:11am, selected=False
			option Pacific/Pitcairn 6:11am, selected=False
			option Pacific/Tarawa 2:11am, selected=False
			option Pacific/Tongatapu 3:11am, selected=False
```
</details>



```
RootWebArea Select a Date & Time - Calendly, focused, url='https://calendly.com/moving-parts/demo?month=2025-01'
	link POWERED BY Calendly, url='https://calendly.com/?utm_campaign=sign_up&utm_medium=badge&utm_source=invitee'
	image Company logo, url='https://d3v0px0pttie1i.cloudfront.net/uploads/user/logo/12271368/555ddb3d.png'
	image Moving Parts, url='https://d3v0px0pttie1i.cloudfront.net/uploads/user/avatar/12271368/21b5036c.png'
	StaticText Moving Parts
```
<details><summary>Show more</summary>

```
	heading Moving Parts Demo
	StaticText 30 min
	StaticText Web conferencing details provided upon confirmation.
	button Cookie settings
	link Report abuse, url='https://calendly.com/abuse_reports/new?source=RW9BOyg-vtR7sHTKbWRToB0FfTq83AIJGHAtmJaooU5w0TulNDTw7UPQNrBmQSmxHBZxQ-wWx5EeRtGr8T7d5eSkyz6gpywLUTB2tWz5'
	heading Select a Date & Time
	button Go to previous month, disabled=True
	StaticText January 2025
	button Go to next month, disabled=True
	status, atomic
		StaticText January is now displayed
	table Select a Day
		rowgroup
			row
				columnheader SUN
				columnheader MON
				columnheader TUE
				columnheader WED
				columnheader THU
				columnheader FRI
				columnheader SAT
		rowgroup
			row
				gridcell
				gridcell
				gridcell
				gridcell Wednesday, January 1 - No times available
					button Wednesday, January 1 - No times available, disabled=True
				gridcell Thursday, January 2 - No times available
					button Thursday, January 2 - No times available, disabled=True
				gridcell Friday, January 3 - No times available
					button Friday, January 3 - No times available, disabled=True
				gridcell Saturday, January 4 - No times available
					button Saturday, January 4 - No times available, disabled=True
			row
				gridcell Sunday, January 5 - No times available
					button Sunday, January 5 - No times available, disabled=True
				gridcell Monday, January 6 - No times available
					button Monday, January 6 - No times available, disabled=True
				gridcell Tuesday, January 7 - No times available
					button Tuesday, January 7 - No times available, disabled=True
				gridcell Wednesday, January 8 - No times available
					button Wednesday, January 8 - No times available, disabled=True
				gridcell Thursday, January 9 - No times available
					button Thursday, January 9 - No times available, disabled=True
				gridcell Friday, January 10 - No times available
					button Friday, January 10 - No times available, disabled=True
				gridcell Saturday, January 11 - No times available
					button Saturday, January 11 - No times available, disabled=True
			row
				gridcell Sunday, January 12 - No times available
					button Sunday, January 12 - No times available, disabled=True
				gridcell Monday, January 13 - No times available
					button Monday, January 13 - No times available, disabled=True
				gridcell Tuesday, January 14 - No times available
					button Tuesday, January 14 - No times available, disabled=True
				gridcell Wednesday, January 15 - No times available
					button Wednesday, January 15 - No times available, disabled=True
				gridcell Thursday, January 16 - No times available
					button Thursday, January 16 - No times available, disabled=True
				gridcell Friday, January 17 - No times available
					button Friday, January 17 - No times available, disabled=True
				gridcell Saturday, January 18 - No times available
					button Saturday, January 18 - No times available, disabled=True
			row
				gridcell Sunday, January 19 - No times available
					button Sunday, January 19 - No times available, disabled=True
				gridcell Monday, January 20 - No times available
					button Monday, January 20 - No times available, disabled=True
				gridcell Tuesday, January 21 - No times available
					button Tuesday, January 21 - No times available, disabled=True
				gridcell Wednesday, January 22 - No times available
					button Wednesday, January 22 - No times available, disabled=True
				gridcell Thursday, January 23 - No times available
					button Thursday, January 23 - No times available, disabled=True
				gridcell Friday, January 24 - No times available
					button Friday, January 24 - No times available, disabled=True
				gridcell Saturday, January 25 - No times available
					button Saturday, January 25 - No times available, disabled=True
			row
				gridcell Sunday, January 26 - No times available
					button Sunday, January 26 - No times available, disabled=True
				gridcell Monday, January 27 - No times available
					button Monday, January 27 - No times available, disabled=True
				gridcell Tuesday, January 28 - No times available
					button Tuesday, January 28 - No times available, disabled=True
				gridcell Wednesday, January 29 - No times available
					button Wednesday, January 29 - No times available, disabled=True
				gridcell Thursday, January 30 - No times available
					button Thursday, January 30 - No times available, disabled=True
				gridcell Friday, January 31 - No times available
					button Friday, January 31 - No times available, disabled=True
				gridcell
	StaticText No times in January
	status, atomic
	paragraph
		StaticText Time zone
	button Time zone  UTC Time (2:12pm) , expanded=False
	region Privacy Preference Center
		alertdialog Privacy Preference Center, modal=True
			image Company Logo
				image Company Logo, url='https://cdn.cookielaw.org/logos/122ecfc3-4694-42f1-863f-2db42d1b1e68/0bcbbcf4-9b83-4684-ba59-bc913c0d5905/c21bea90-f4f1-43d1-8118-8938bbb27a9d/logo.png'
			[283] button Close, center=(458,32)
			StaticText When you visit any website, it may store or retrieve information on your browser, mostly in the form of cookies. This information might be about you, your preferences or your device and is mostly used to make the site work as you expect it to. The information does not usually directly identify you, but it can give you a more personalized web experience. Because we respect your right to privacy, you can choose not to allow some types of cookies. Click on the different category headings to find out more and change our default settings. However, blocking some types of cookies may impact your experience of the site and the services we are able to offer.
			StaticText Manage Consent Preferences
			[295] button Strictly Necessary Cookies Always Active, center=(244,368), expanded=False
			StaticText Strictly Necessary Cookies
			StaticText Always Active
			[307] button Functional Cookies, center=(244,419), expanded=False
			StaticText Functional Cookies
			switch Functional Cookies, checked='true', focused
			LabelText
				[316] switch Functional Cookies, center=(432,416), checked='true'
			[323] button Performance Cookies, center=(244,473), expanded=False
			StaticText Performance Cookies
			switch Performance Cookies, checked='true'
			LabelText
				[332] switch Performance Cookies, center=(432,470), checked='true'
			[339] button Targeting Cookies, center=(244,528), expanded=False
			StaticText Targeting Cookies
			switch Targeting Cookies, checked='true'
			LabelText
				[348] switch Targeting Cookies, center=(432,525), checked='true'
			[413] button Confirm My Choices, center=(130,1015)
			[415] link Powered by OneTrust Opens in a new Tab, center=(394,1068), url='https://www.onetrust.com/products/cookie-consent/'
				image Powered by Onetrust, url='https://cdn.cookielaw.org/logos/static/powered_by_logo.svg'
			generic, atomic
```
</details>

**Reasoning for action:** I need to access the cookie settings to fulfill the user story requirements related to managing cookie preferences. By clicking on the 'Cookie settings' button (with the identifier 92), I can explore available options to manage cookies, which is necessary for the user to effectively control their preferences as mentioned in the acceptance test.

**Action:** click(92) # Click on the 'Cookie settings' button to explore cookie options.

**Change Description:** After clicking the 'Cookie settings' button, a Privacy Preference Center modal appeared, providing information about cookies and options to manage consent preferences, including 'Strictly Necessary', 'Functional', 'Performance', and 'Targeting' cookies.

**Screenshot before:****Screenshot after:**---


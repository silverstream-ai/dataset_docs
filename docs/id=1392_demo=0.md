# Task

**User Submission for Inquiry**

As a potential customer,
I submit my inquiry through the 'Talk to us' feature,
so that I can receive personalized assistance and learn more about Verdn's offerings.

**Success definition:** Given I am a potential customer on the Verdn homepage
When I click on the 'Talk to us' button and fill out my name
Then I should see a form transition that allows me to input my work email, indicating I can continue my inquiry.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://verdn.com/

https://verdn.com/

**Content (before/after):** 

```
RootWebArea Verdn, focused, url='https://verdn.com/'
	main
		[38] link, center=(355,31), url='https://verdn.com/'
			image
		navigation Main
```
<details><summary>Show more</summary>

```
			list
				listitem
					[44] link For nonprofits, center=(503,36), url='https://verdn.com/product/for-nonprofits'
				listitem
					[46] link Case studies, center=(632,36), url='https://verdn.com/resources/case-studies'
		[49] link Log in, center=(1560,36), url='https://verdn.com/app/log-in'
			button Log in
				image
		image hero-bg-gradient, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fbg-mesh-1.png&w=1200&q=75'
		heading Make donations a revenue center
		paragraph
			StaticText Verdn's best-in-class tool set provides you the power to give back with any action, tell the full impact story, and prove it moves the metrics you care most about.
		[67] button Talk to us, center=(383,537), type=button
			image
		figure
			StaticText ACME Ϫ FASHIONS
			image
			StaticText Women
			StaticText >
			StaticText Bags
			StaticText >
			StaticText Handbags
			image test-clutch, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fclutch.png&w=640&q=75'
			StaticText Orford clutch
			image
			StaticText $299
			image
			StaticText Plants 5 trees
			StaticText Track impact post-purchase
			StaticText BUY NOW
			StaticText Description
			StaticText This classic purse has been handcrafted from the finest Venetian vegan leather.
			StaticText ecomm. order
			image
			StaticText Acme fashions
			image
			StaticText 1337
			image
			StaticText paula.stike@example.com
			StaticText Pledge for
			StaticText 5 trees
			StaticText created
			StaticText $2.78
			StaticText sent to impact partner
			image
			StaticText Impact email sent
			image test-paula, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fpaula.png&w=128&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		[198] link Ren Skincare, center=(379,770), url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		[201] link Shady Rays, center=(555,770), url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		[204] link Alo Yoga, center=(731,770), url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		[207] link Ohh Deer, center=(907,770), url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		[210] link Cariuma, center=(1083,770), url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		[214] link Ren Skincare, center=(1259,770), url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		[217] link Shady Rays, center=(1435,770), url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		StaticText USE CASES
		heading The platform for giving back
		heading For companies
		paragraph
			StaticText Give back effortlessly with any action, tell your complete impact story, and prove that it moves the metrics you care most about.
		image
		StaticText Integrate your give back into any aspect of your business in a few clicks.
		image
		StaticText Drive engagement by leveraging impact storytelling from your nonprofit partner.
		image
		StaticText Measure how donations drive the KPIs that matter to your business.
		code
			StaticText import
			StaticText axios
			StaticText from
			StaticText "axios"
			StaticText ;
			StaticText const
			StaticText makePledge
			StaticText =
			StaticText async
			StaticText ({
			StaticText customer
			StaticText })
			StaticText =>
			StaticText {
			StaticText const
			StaticText response
			StaticText =
			StaticText await
			StaticText axios.
			StaticText post
			StaticText (
			StaticText "https://verdn.com/api/impact"
			StaticText ,
			StaticText {
			StaticText amount:
			StaticText 1
			StaticText ,
			StaticText unit:
			StaticText "kg"
			StaticText ,
			StaticText impactOffering:
			StaticText "OceanPlastic"
			StaticText }
			StaticText );
			StaticText if
			StaticText (response.status
			StaticText ===
			StaticText 200
			StaticText ) {
			StaticText await
			StaticText sendEmail
			StaticText (customer.email);
			StaticText }
			StaticText }
			StaticText // ...
			StaticText const
			StaticText processOrder
			StaticText =
			StaticText async
			StaticText ({
			StaticText customer
			StaticText })
			StaticText =>
			StaticText {
			StaticText // ...After order has completed
			StaticText await
			StaticText makePledge
			StaticText (customer);
			StaticText }
		heading For nonprofits
		paragraph
			StaticText Meet corporations where they are with Verdn's seamless tech. Empower them to get set up in minutes, and track positive KPI outcomes.
		link Discover Verdn for nonprofits, url='https://verdn.com/product/for-nonprofits'
			button Discover Verdn for nonprofits
				image
		StaticText PROVEN VALUE
		heading Drive KPIs across your business
		StaticText CONVERT
		heading Sell more by donating with every product or order
		image
		StaticText Leverage rules to give back on your terms.
		image
		StaticText Display widgets across your site to tell your visitors.
		image
		StaticText Track how pledging increases your conversion rate.
		figure
			StaticText ACME Ϫ FASHIONS
			image
			StaticText Women
			StaticText >
			StaticText Bags
			StaticText >
			StaticText Handbags
			image test-clutch, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fclutch.png&w=640&q=75'
			StaticText Orford clutch
			image
			StaticText $299
			image
			StaticText Plants 5 trees
			StaticText Track impact post-purchase
			StaticText BUY NOW
			StaticText Description
			StaticText This classic purse has been handcrafted from the finest Venetian vegan leather. We recommend pairing this piece with something from our
			StaticText Autumnal Look-book
			StaticText to get the true Acme take.
			StaticText 1.8
			StaticText %
			image
			StaticText CVR
			StaticText CONVERSION RATE
		StaticText INFORM
		heading Drive user interaction with incentives and rewards
		image
		StaticText Attach a donation pledge to any user action.
		image
		StaticText Promote loyalty by letting users accumulate impact.
		image
		StaticText Save money vs gift cards with cost-efficient projects.
		figure
			image
			StaticText Inbox (27)
			StaticText Help us improve ou...
			image
			image
			StaticText COLLISON BANK
			paragraph
				StaticText Dear Alice,
			paragraph
				StaticText Thank you for banking with us. To help us improve our service, please take this short survey. As a thank you,
				StaticText we'll make a donation
				StaticText to our nonprofit partner. Your impact gets added to your existing total.
			StaticText Take our survey
			image
			image
			StaticText Recover 200cm² coral reef
			StaticText 1,337
			image
			StaticText Responses
		StaticText ENGAGE
		heading Boost user engagement with unique impact storytelling
		image
		StaticText Deepen your customer and user relationships.
		image
		StaticText Let customers track the impact of your donations.
		image
		StaticText Integrate impact data to email, SMS, and most other notification channels.
		figure
			image Mary for timeline, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fmary.png&w=256&q=75'
			StaticText Mary's impact
			StaticText 5 trees planted
			heading Impact timeline
			image
			StaticText 7th January, 4:32 am
			StaticText Trees planted
			image
			StaticText Great news! Your trees have now been planted.
			StaticText Check out the project update below.
			image Eden update, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Feden-update-2.webp&w=1200&q=75'
			StaticText 500%
			image
			StaticText Email clicks
		StaticText RETAIN
		heading Increase customer LTV with green marketing and rewards
		image
		StaticText Stay top-of-mind with timely impact updates.
		image
		StaticText Deploy a toolkit of incentives to nudge behavior.
		image
		StaticText Avoid promotion-fatigue, or bland reminders.
		figure
			StaticText LIMITED TIME OFFER
			image
			paragraph
				StaticText We haven't seen you in a while so we'd love to
				StaticText offer you
				strong
					StaticText twice
				StaticText the impact
				StaticText when you book your next session. Click below to redeem.
			StaticText Book a
			StaticText double-impact
			StaticText session
			paragraph
				StaticText You have currently recovered 850 bottles' worth of ocean-bound plastic.
				StaticText Track updates to your impact here.
			StaticText 15%
			image
			StaticText Retention MoM
		StaticText EASY INTEGRATION
		heading Seamless setup
		paragraph
			StaticText Whatever your stack, Verdn integrates cleanly and doesn't get in the way. It takes usually just 10 minutes to get fully set up and starting to donate.
		heading No code
		paragraph
			StaticText Automate your giveback in 5 minutes, and start reaping a measurable ROI with our award-winning Shopify app.
		image
		heading 5.0
		image
		image
		image
		image
		image
		paragraph
			StaticText 50
			StaticText Reviews
		link Install Shopify app, url='https://apps.shopify.com/verdn-sell-with-impact'
			button Install Shopify app
				image
		heading Low code
		paragraph
			StaticText Start unleashing the power of your nonprofit partnership with a single
			StaticText POST
			StaticText –call triggered by any
			StaticText action
			StaticText taken by a user or customer.
		button Join our API program
			image
		StaticText CASE STUDIES
		heading Don't take it from us
		StaticText Revitalize
		StaticText loyalty
		StaticText Use Verdn as part of your loyalty and customer rewards programs to grow redemptions.
		StaticText Boost
		StaticText your ROI
		StaticText Our A/B testing pipeline allows you to see the results of your give-back on your bottom line.
		StaticText Bespoke
		StaticText impact providers
		StaticText Bring your own charity or NGO partner to Verdn with our white-glove provider integration.
		image alo-yoga background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Falo-test-bg.jpg&w=1200&q=75'
		StaticText Customer success
		StaticText "This partnership was a no-brainer. Our loyalty program is environmentally conscious and aligns to our values with Verdn."
		StaticText Cher Fuller
		StaticText |
		StaticText Head of Growth, Alo Yoga
		image alo-yoga logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		image alo-yoga logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		image shady-rays background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fsr-test-bg.webp&w=1200&q=75'
		StaticText Customer success
		StaticText "Verdn has been a game-changer for us. It's boosted our customer engagement and generates a positive ROI for our give back program."
		StaticText Jenny Howard
		StaticText |
		StaticText Strategic Comms. Director, Shady Rays
		image shady-rays logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		image shady-rays logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		image cariuma background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fcariuma-test-bg.jpg&w=1200&q=75'
		StaticText Customer success
		StaticText "We'd been looking for a better way to engage our customers about our impact, and Verdn's platform was the perfect solution for us."
		StaticText Felipe Arujao
		StaticText |
		StaticText Head of Growth, Cariuma
		image cariuma logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		image cariuma logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		heading Truly global and transparent impact
		paragraph
			StaticText By working with a hand-picked roster of vetted charities, NGOs, and impact organizations, Verdn is able to offer unparalleled on-the-ground reporting.
		StaticText Our flagship partners
		link eden-logo, url='https://eden-plus.org/'
			image eden-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Feden-logo.png&w=640&q=75'
		link empower-logo, url='https://empower.eco/'
			image empower-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fempower-logo.png&w=640&q=75'
		link coralive-logo, url='https://coralive.org/'
			image coralive-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fcoralive-logo.png&w=640&q=75'
		link, url='https://verdn.com/'
			image
		link, url='https://www.bcorporation.net/find-a-b-corp/company/verdn/'
			image
		link Backed by, url='https://ycombinator.com/companies/verdn'
			image
		heading RESOURCES
		link For nonprofits, url='https://verdn.com/product/for-nonprofits'
		link For AI, url='https://verdn.com/product/for-ai'
		link Case studies, url='https://verdn.com/resources/case-studies'
		heading COMPANY
		link About us, url='https://www.ycombinator.com/companies/verdn'
		link Work at Verdn, url='https://www.workatastartup.com/companies/verdn'
		StaticText Contact us
		link Privacy policy, url='https://verdn.com/legal/privacy-policy'
		link Cookie policy, url='https://verdn.com/legal/cookie-policy'
		StaticText ©
		StaticText 2025
		StaticText Verdn Ltd. All rights reserved.
		StaticText Made around the 🌍
		link, url='https://linkedin.com/company/verdn'
			image
		link, url='https://instagram.com/verdn.impact'
			image
	region Notifications (F8)
		list
	alert, atomic
```
</details>



```
RootWebArea Verdn, url='https://verdn.com/'
	main
		link, url='https://verdn.com/'
			image
		navigation Main
```
<details><summary>Show more</summary>

```
			list
				listitem
					link For nonprofits, url='https://verdn.com/product/for-nonprofits'
				listitem
					link Case studies, url='https://verdn.com/resources/case-studies'
		link Log in, url='https://verdn.com/app/log-in'
			button Log in
				image
		image hero-bg-gradient, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fbg-mesh-1.png&w=1200&q=75'
		heading Make donations a revenue center
		paragraph
			StaticText Verdn's best-in-class tool set provides you the power to give back with any action, tell the full impact story, and prove it moves the metrics you care most about.
		button Talk to us
			image
		figure
			StaticText ACME Ϫ FASHIONS
			image
			StaticText Women
			StaticText >
			StaticText Bags
			StaticText >
			StaticText Handbags
			image test-clutch, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fclutch.png&w=640&q=75'
			StaticText Orford clutch
			image
			StaticText $299
			image
			StaticText Plants 5 trees
			StaticText Track impact post-purchase
			StaticText BUY NOW
			StaticText Description
			StaticText This classic purse has been handcrafted from the finest Venetian vegan leather.
			StaticText ecomm. order
			image
			StaticText Acme fashions
			image
			StaticText 1337
			image
			StaticText paula.stike@example.com
			StaticText Pledge for
			StaticText 5 trees
			StaticText created
			StaticText $2.78
			StaticText sent to impact partner
			image
			StaticText Impact email sent
			image test-paula, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fpaula.png&w=128&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		StaticText USE CASES
		heading The platform for giving back
		heading For companies
		paragraph
			StaticText Give back effortlessly with any action, tell your complete impact story, and prove that it moves the metrics you care most about.
		image
		StaticText Integrate your give back into any aspect of your business in a few clicks.
		image
		StaticText Drive engagement by leveraging impact storytelling from your nonprofit partner.
		image
		StaticText Measure how donations drive the KPIs that matter to your business.
		code
			StaticText import
			StaticText axios
			StaticText from
			StaticText "axios"
			StaticText ;
			StaticText const
			StaticText makePledge
			StaticText =
			StaticText async
			StaticText ({
			StaticText customer
			StaticText })
			StaticText =>
			StaticText {
			StaticText const
			StaticText response
			StaticText =
			StaticText await
			StaticText axios.
			StaticText post
			StaticText (
			StaticText "https://verdn.com/api/impact"
			StaticText ,
			StaticText {
			StaticText amount:
			StaticText 1
			StaticText ,
			StaticText unit:
			StaticText "kg"
			StaticText ,
			StaticText impactOffering:
			StaticText "OceanPlastic"
			StaticText }
			StaticText );
			StaticText if
			StaticText (response.status
			StaticText ===
			StaticText 200
			StaticText ) {
			StaticText await
			StaticText sendEmail
			StaticText (customer.email);
			StaticText }
			StaticText }
			StaticText // ...
			StaticText const
			StaticText processOrder
			StaticText =
			StaticText async
			StaticText ({
			StaticText customer
			StaticText })
			StaticText =>
			StaticText {
			StaticText // ...After order has completed
			StaticText await
			StaticText makePledge
			StaticText (customer);
			StaticText }
		heading For nonprofits
		paragraph
			StaticText Meet corporations where they are with Verdn's seamless tech. Empower them to get set up in minutes, and track positive KPI outcomes.
		link Discover Verdn for nonprofits, url='https://verdn.com/product/for-nonprofits'
			button Discover Verdn for nonprofits
				image
		StaticText PROVEN VALUE
		heading Drive KPIs across your business
		StaticText CONVERT
		heading Sell more by donating with every product or order
		image
		StaticText Leverage rules to give back on your terms.
		image
		StaticText Display widgets across your site to tell your visitors.
		image
		StaticText Track how pledging increases your conversion rate.
		figure
			StaticText ACME Ϫ FASHIONS
			image
			StaticText Women
			StaticText >
			StaticText Bags
			StaticText >
			StaticText Handbags
			image test-clutch, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fclutch.png&w=640&q=75'
			StaticText Orford clutch
			image
			StaticText $299
			image
			StaticText Plants 5 trees
			StaticText Track impact post-purchase
			StaticText BUY NOW
			StaticText Description
			StaticText This classic purse has been handcrafted from the finest Venetian vegan leather. We recommend pairing this piece with something from our
			StaticText Autumnal Look-book
			StaticText to get the true Acme take.
			StaticText 1.8
			StaticText %
			image
			StaticText CVR
			StaticText CONVERSION RATE
		StaticText INFORM
		heading Drive user interaction with incentives and rewards
		image
		StaticText Attach a donation pledge to any user action.
		image
		StaticText Promote loyalty by letting users accumulate impact.
		image
		StaticText Save money vs gift cards with cost-efficient projects.
		figure
			image
			StaticText Inbox (27)
			StaticText Help us improve ou...
			image
			image
			StaticText COLLISON BANK
			paragraph
				StaticText Dear Alice,
			paragraph
				StaticText Thank you for banking with us. To help us improve our service, please take this short survey. As a thank you,
				StaticText we'll make a donation
				StaticText to our nonprofit partner. Your impact gets added to your existing total.
			StaticText Take our survey
			image
			image
			StaticText Recover 200cm² coral reef
			StaticText 1,337
			image
			StaticText Responses
		StaticText ENGAGE
		heading Boost user engagement with unique impact storytelling
		image
		StaticText Deepen your customer and user relationships.
		image
		StaticText Let customers track the impact of your donations.
		image
		StaticText Integrate impact data to email, SMS, and most other notification channels.
		figure
			image Mary for timeline, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fmary.png&w=256&q=75'
			StaticText Mary's impact
			StaticText 5 trees planted
			heading Impact timeline
			image
			StaticText 7th January, 4:32 am
			StaticText Trees planted
			image
			StaticText Great news! Your trees have now been planted.
			StaticText Check out the project update below.
			image Eden update, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Feden-update-2.webp&w=1200&q=75'
			StaticText 500%
			image
			StaticText Email clicks
		StaticText RETAIN
		heading Increase customer LTV with green marketing and rewards
		image
		StaticText Stay top-of-mind with timely impact updates.
		image
		StaticText Deploy a toolkit of incentives to nudge behavior.
		image
		StaticText Avoid promotion-fatigue, or bland reminders.
		figure
			StaticText LIMITED TIME OFFER
			image
			paragraph
				StaticText We haven't seen you in a while so we'd love to
				StaticText offer you
				strong
					StaticText twice
				StaticText the impact
				StaticText when you book your next session. Click below to redeem.
			StaticText Book a
			StaticText double-impact
			StaticText session
			paragraph
				StaticText You have currently recovered 850 bottles' worth of ocean-bound plastic.
				StaticText Track updates to your impact here.
			StaticText 15%
			image
			StaticText Retention MoM
		StaticText EASY INTEGRATION
		heading Seamless setup
		paragraph
			StaticText Whatever your stack, Verdn integrates cleanly and doesn't get in the way. It takes usually just 10 minutes to get fully set up and starting to donate.
		heading No code
		paragraph
			StaticText Automate your giveback in 5 minutes, and start reaping a measurable ROI with our award-winning Shopify app.
		image
		heading 5.0
		image
		image
		image
		image
		image
		paragraph
			StaticText 50
			StaticText Reviews
		link Install Shopify app, url='https://apps.shopify.com/verdn-sell-with-impact'
			button Install Shopify app
				image
		heading Low code
		paragraph
			StaticText Start unleashing the power of your nonprofit partnership with a single
			StaticText POST
			StaticText –call triggered by any
			StaticText action
			StaticText taken by a user or customer.
		button Join our API program
			image
		StaticText CASE STUDIES
		heading Don't take it from us
		StaticText Revitalize
		StaticText loyalty
		StaticText Use Verdn as part of your loyalty and customer rewards programs to grow redemptions.
		StaticText Boost
		StaticText your ROI
		StaticText Our A/B testing pipeline allows you to see the results of your give-back on your bottom line.
		StaticText Bespoke
		StaticText impact providers
		StaticText Bring your own charity or NGO partner to Verdn with our white-glove provider integration.
		image alo-yoga background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Falo-test-bg.jpg&w=1200&q=75'
		StaticText Customer success
		StaticText "This partnership was a no-brainer. Our loyalty program is environmentally conscious and aligns to our values with Verdn."
		StaticText Cher Fuller
		StaticText |
		StaticText Head of Growth, Alo Yoga
		image alo-yoga logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		image alo-yoga logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		image shady-rays background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fsr-test-bg.webp&w=1200&q=75'
		StaticText Customer success
		StaticText "Verdn has been a game-changer for us. It's boosted our customer engagement and generates a positive ROI for our give back program."
		StaticText Jenny Howard
		StaticText |
		StaticText Strategic Comms. Director, Shady Rays
		image shady-rays logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		image shady-rays logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		image cariuma background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fcariuma-test-bg.jpg&w=1200&q=75'
		StaticText Customer success
		StaticText "We'd been looking for a better way to engage our customers about our impact, and Verdn's platform was the perfect solution for us."
		StaticText Felipe Arujao
		StaticText |
		StaticText Head of Growth, Cariuma
		image cariuma logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		image cariuma logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		heading Truly global and transparent impact
		paragraph
			StaticText By working with a hand-picked roster of vetted charities, NGOs, and impact organizations, Verdn is able to offer unparalleled on-the-ground reporting.
		StaticText Our flagship partners
		link eden-logo, url='https://eden-plus.org/'
			image eden-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Feden-logo.png&w=640&q=75'
		link empower-logo, url='https://empower.eco/'
			image empower-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fempower-logo.png&w=640&q=75'
		link coralive-logo, url='https://coralive.org/'
			image coralive-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fcoralive-logo.png&w=640&q=75'
		link, url='https://verdn.com/'
			image
		link, url='https://www.bcorporation.net/find-a-b-corp/company/verdn/'
			image
		link Backed by, url='https://ycombinator.com/companies/verdn'
			image
		heading RESOURCES
		link For nonprofits, url='https://verdn.com/product/for-nonprofits'
		link For AI, url='https://verdn.com/product/for-ai'
		link Case studies, url='https://verdn.com/resources/case-studies'
		heading COMPANY
		link About us, url='https://www.ycombinator.com/companies/verdn'
		link Work at Verdn, url='https://www.workatastartup.com/companies/verdn'
		StaticText Contact us
		link Privacy policy, url='https://verdn.com/legal/privacy-policy'
		link Cookie policy, url='https://verdn.com/legal/cookie-policy'
		StaticText ©
		StaticText 2025
		StaticText Verdn Ltd. All rights reserved.
		StaticText Made around the 🌍
		link, url='https://linkedin.com/company/verdn'
			image
		link, url='https://instagram.com/verdn.impact'
			image
	region Notifications (F8)
		list
	alert, atomic
	[a] Iframe, center=(960,540)
		RootWebArea Landing General (2024), focused, url='https://form.typeform.com/to/VsQntgWS?typeform-embed-id=6184888407998836&typeform-embed=popup-blank&typeform-source=verdn.com&typeform-medium=embed-sdk&typeform-medium-version=next&typeform-embed-handles-redirect=1&typeform-embed-no-heading=true'
			banner
				image, url='https://images.typeform.com/images/ZVxG8jgxEWW3'
			main
				progressbar Form progress value='0'
				StaticText Question 1
				LabelText
					StaticText What is your
					strong
						StaticText name?
					StaticText This question is required.
				paragraph
				[a116] textbox What is your name? This question is required., center=(960,512), focused
				[a123] button OK, center=(630,570)
					StaticText OK
				navigation
					[a192] button Navigate to next question, center=(1655,992)
						image
					button Navigate to previous question, disabled=True
						image
				[a209] link Powered by Typeform, center=(1765,992), url='https://www.typeform.com/explore/?utm_campaign=VsQntgWS&utm_source=typeform.com-01EM1WHFEBS2JC51892DK9V11Y-basic&utm_medium=typeform&utm_content=typeform-footer&utm_term=EN'
					StaticText Powered by
					strong
						StaticText Typeform
	[809] button Close, center=(1868,18), inner_text=×
		StaticText ×
```
</details>

**Reasoning for action:** Clicking on the 'Talk to us' button is the first step in fulfilling the user story. This action is necessary to access the inquiry form where the user can begin to submit their details, which is pivotal for receiving personalized assistance. By clicking this button, I move closer to generating the form that will eventually allow the user to learn more about Verdn's offerings.

**Action:** click('67') # Click on the 'Talk to us' button to explore further options.

**Change Description:** The user clicked the 'Talk to us' button, which prompted a Typeform popup to appear, allowing for user input on their name, indicating a transition to an interactive form for further engagement.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://verdn.com/

https://verdn.com/

**Content (before/after):** 

```
RootWebArea Verdn, url='https://verdn.com/'
	main
		link, url='https://verdn.com/'
			image
		navigation Main
```
<details><summary>Show more</summary>

```
			list
				listitem
					link For nonprofits, url='https://verdn.com/product/for-nonprofits'
				listitem
					link Case studies, url='https://verdn.com/resources/case-studies'
		link Log in, url='https://verdn.com/app/log-in'
			button Log in
				image
		image hero-bg-gradient, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fbg-mesh-1.png&w=1200&q=75'
		heading Make donations a revenue center
		paragraph
			StaticText Verdn's best-in-class tool set provides you the power to give back with any action, tell the full impact story, and prove it moves the metrics you care most about.
		button Talk to us
			image
		figure
			StaticText ACME Ϫ FASHIONS
			image
			StaticText Women
			StaticText >
			StaticText Bags
			StaticText >
			StaticText Handbags
			image test-clutch, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fclutch.png&w=640&q=75'
			StaticText Orford clutch
			image
			StaticText $299
			image
			StaticText Plants 5 trees
			StaticText Track impact post-purchase
			StaticText BUY NOW
			StaticText Description
			StaticText This classic purse has been handcrafted from the finest Venetian vegan leather.
			StaticText ecomm. order
			image
			StaticText Acme fashions
			image
			StaticText 1337
			image
			StaticText paula.stike@example.com
			StaticText Pledge for
			StaticText 5 trees
			StaticText created
			StaticText $2.78
			StaticText sent to impact partner
			image
			StaticText Impact email sent
			image test-paula, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fpaula.png&w=128&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		StaticText USE CASES
		heading The platform for giving back
		heading For companies
		paragraph
			StaticText Give back effortlessly with any action, tell your complete impact story, and prove that it moves the metrics you care most about.
		image
		StaticText Integrate your give back into any aspect of your business in a few clicks.
		image
		StaticText Drive engagement by leveraging impact storytelling from your nonprofit partner.
		image
		StaticText Measure how donations drive the KPIs that matter to your business.
		code
			StaticText import
			StaticText axios
			StaticText from
			StaticText "axios"
			StaticText ;
			StaticText const
			StaticText makePledge
			StaticText =
			StaticText async
			StaticText ({
			StaticText customer
			StaticText })
			StaticText =>
			StaticText {
			StaticText const
			StaticText response
			StaticText =
			StaticText await
			StaticText axios.
			StaticText post
			StaticText (
			StaticText "https://verdn.com/api/impact"
			StaticText ,
			StaticText {
			StaticText amount:
			StaticText 1
			StaticText ,
			StaticText unit:
			StaticText "kg"
			StaticText ,
			StaticText impactOffering:
			StaticText "OceanPlastic"
			StaticText }
			StaticText );
			StaticText if
			StaticText (response.status
			StaticText ===
			StaticText 200
			StaticText ) {
			StaticText await
			StaticText sendEmail
			StaticText (customer.email);
			StaticText }
			StaticText }
			StaticText // ...
			StaticText const
			StaticText processOrder
			StaticText =
			StaticText async
			StaticText ({
			StaticText customer
			StaticText })
			StaticText =>
			StaticText {
			StaticText // ...After order has completed
			StaticText await
			StaticText makePledge
			StaticText (customer);
			StaticText }
		heading For nonprofits
		paragraph
			StaticText Meet corporations where they are with Verdn's seamless tech. Empower them to get set up in minutes, and track positive KPI outcomes.
		link Discover Verdn for nonprofits, url='https://verdn.com/product/for-nonprofits'
			button Discover Verdn for nonprofits
				image
		StaticText PROVEN VALUE
		heading Drive KPIs across your business
		StaticText CONVERT
		heading Sell more by donating with every product or order
		image
		StaticText Leverage rules to give back on your terms.
		image
		StaticText Display widgets across your site to tell your visitors.
		image
		StaticText Track how pledging increases your conversion rate.
		figure
			StaticText ACME Ϫ FASHIONS
			image
			StaticText Women
			StaticText >
			StaticText Bags
			StaticText >
			StaticText Handbags
			image test-clutch, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fclutch.png&w=640&q=75'
			StaticText Orford clutch
			image
			StaticText $299
			image
			StaticText Plants 5 trees
			StaticText Track impact post-purchase
			StaticText BUY NOW
			StaticText Description
			StaticText This classic purse has been handcrafted from the finest Venetian vegan leather. We recommend pairing this piece with something from our
			StaticText Autumnal Look-book
			StaticText to get the true Acme take.
			StaticText 1.8
			StaticText %
			image
			StaticText CVR
			StaticText CONVERSION RATE
		StaticText INFORM
		heading Drive user interaction with incentives and rewards
		image
		StaticText Attach a donation pledge to any user action.
		image
		StaticText Promote loyalty by letting users accumulate impact.
		image
		StaticText Save money vs gift cards with cost-efficient projects.
		figure
			image
			StaticText Inbox (27)
			StaticText Help us improve ou...
			image
			image
			StaticText COLLISON BANK
			paragraph
				StaticText Dear Alice,
			paragraph
				StaticText Thank you for banking with us. To help us improve our service, please take this short survey. As a thank you,
				StaticText we'll make a donation
				StaticText to our nonprofit partner. Your impact gets added to your existing total.
			StaticText Take our survey
			image
			image
			StaticText Recover 200cm² coral reef
			StaticText 1,337
			image
			StaticText Responses
		StaticText ENGAGE
		heading Boost user engagement with unique impact storytelling
		image
		StaticText Deepen your customer and user relationships.
		image
		StaticText Let customers track the impact of your donations.
		image
		StaticText Integrate impact data to email, SMS, and most other notification channels.
		figure
			image Mary for timeline, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fmary.png&w=256&q=75'
			StaticText Mary's impact
			StaticText 5 trees planted
			heading Impact timeline
			image
			StaticText 7th January, 4:32 am
			StaticText Trees planted
			image
			StaticText Great news! Your trees have now been planted.
			StaticText Check out the project update below.
			image Eden update, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Feden-update-2.webp&w=1200&q=75'
			StaticText 500%
			image
			StaticText Email clicks
		StaticText RETAIN
		heading Increase customer LTV with green marketing and rewards
		image
		StaticText Stay top-of-mind with timely impact updates.
		image
		StaticText Deploy a toolkit of incentives to nudge behavior.
		image
		StaticText Avoid promotion-fatigue, or bland reminders.
		figure
			StaticText LIMITED TIME OFFER
			image
			paragraph
				StaticText We haven't seen you in a while so we'd love to
				StaticText offer you
				strong
					StaticText twice
				StaticText the impact
				StaticText when you book your next session. Click below to redeem.
			StaticText Book a
			StaticText double-impact
			StaticText session
			paragraph
				StaticText You have currently recovered 850 bottles' worth of ocean-bound plastic.
				StaticText Track updates to your impact here.
			StaticText 15%
			image
			StaticText Retention MoM
		StaticText EASY INTEGRATION
		heading Seamless setup
		paragraph
			StaticText Whatever your stack, Verdn integrates cleanly and doesn't get in the way. It takes usually just 10 minutes to get fully set up and starting to donate.
		heading No code
		paragraph
			StaticText Automate your giveback in 5 minutes, and start reaping a measurable ROI with our award-winning Shopify app.
		image
		heading 5.0
		image
		image
		image
		image
		image
		paragraph
			StaticText 50
			StaticText Reviews
		link Install Shopify app, url='https://apps.shopify.com/verdn-sell-with-impact'
			button Install Shopify app
				image
		heading Low code
		paragraph
			StaticText Start unleashing the power of your nonprofit partnership with a single
			StaticText POST
			StaticText –call triggered by any
			StaticText action
			StaticText taken by a user or customer.
		button Join our API program
			image
		StaticText CASE STUDIES
		heading Don't take it from us
		StaticText Revitalize
		StaticText loyalty
		StaticText Use Verdn as part of your loyalty and customer rewards programs to grow redemptions.
		StaticText Boost
		StaticText your ROI
		StaticText Our A/B testing pipeline allows you to see the results of your give-back on your bottom line.
		StaticText Bespoke
		StaticText impact providers
		StaticText Bring your own charity or NGO partner to Verdn with our white-glove provider integration.
		image alo-yoga background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Falo-test-bg.jpg&w=1200&q=75'
		StaticText Customer success
		StaticText "This partnership was a no-brainer. Our loyalty program is environmentally conscious and aligns to our values with Verdn."
		StaticText Cher Fuller
		StaticText |
		StaticText Head of Growth, Alo Yoga
		image alo-yoga logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		image alo-yoga logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		image shady-rays background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fsr-test-bg.webp&w=1200&q=75'
		StaticText Customer success
		StaticText "Verdn has been a game-changer for us. It's boosted our customer engagement and generates a positive ROI for our give back program."
		StaticText Jenny Howard
		StaticText |
		StaticText Strategic Comms. Director, Shady Rays
		image shady-rays logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		image shady-rays logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		image cariuma background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fcariuma-test-bg.jpg&w=1200&q=75'
		StaticText Customer success
		StaticText "We'd been looking for a better way to engage our customers about our impact, and Verdn's platform was the perfect solution for us."
		StaticText Felipe Arujao
		StaticText |
		StaticText Head of Growth, Cariuma
		image cariuma logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		image cariuma logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		heading Truly global and transparent impact
		paragraph
			StaticText By working with a hand-picked roster of vetted charities, NGOs, and impact organizations, Verdn is able to offer unparalleled on-the-ground reporting.
		StaticText Our flagship partners
		link eden-logo, url='https://eden-plus.org/'
			image eden-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Feden-logo.png&w=640&q=75'
		link empower-logo, url='https://empower.eco/'
			image empower-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fempower-logo.png&w=640&q=75'
		link coralive-logo, url='https://coralive.org/'
			image coralive-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fcoralive-logo.png&w=640&q=75'
		link, url='https://verdn.com/'
			image
		link, url='https://www.bcorporation.net/find-a-b-corp/company/verdn/'
			image
		link Backed by, url='https://ycombinator.com/companies/verdn'
			image
		heading RESOURCES
		link For nonprofits, url='https://verdn.com/product/for-nonprofits'
		link For AI, url='https://verdn.com/product/for-ai'
		link Case studies, url='https://verdn.com/resources/case-studies'
		heading COMPANY
		link About us, url='https://www.ycombinator.com/companies/verdn'
		link Work at Verdn, url='https://www.workatastartup.com/companies/verdn'
		StaticText Contact us
		link Privacy policy, url='https://verdn.com/legal/privacy-policy'
		link Cookie policy, url='https://verdn.com/legal/cookie-policy'
		StaticText ©
		StaticText 2025
		StaticText Verdn Ltd. All rights reserved.
		StaticText Made around the 🌍
		link, url='https://linkedin.com/company/verdn'
			image
		link, url='https://instagram.com/verdn.impact'
			image
	region Notifications (F8)
		list
	alert, atomic
	[a] Iframe, center=(960,540)
		RootWebArea Landing General (2024), focused, url='https://form.typeform.com/to/VsQntgWS?typeform-embed-id=6184888407998836&typeform-embed=popup-blank&typeform-source=verdn.com&typeform-medium=embed-sdk&typeform-medium-version=next&typeform-embed-handles-redirect=1&typeform-embed-no-heading=true'
			banner
				image, url='https://images.typeform.com/images/ZVxG8jgxEWW3'
			main
				progressbar Form progress value='0'
				StaticText Question 1
				LabelText
					StaticText What is your
					strong
						StaticText name?
					StaticText This question is required.
				paragraph
				[a116] textbox What is your name? This question is required., center=(960,512), focused
				[a123] button OK, center=(630,570)
					StaticText OK
				navigation
					[a192] button Navigate to next question, center=(1655,992)
						image
					button Navigate to previous question, disabled=True
						image
				[a209] link Powered by Typeform, center=(1765,992), url='https://www.typeform.com/explore/?utm_campaign=VsQntgWS&utm_source=typeform.com-01EM1WHFEBS2JC51892DK9V11Y-basic&utm_medium=typeform&utm_content=typeform-footer&utm_term=EN'
					StaticText Powered by
					strong
						StaticText Typeform
	[809] button Close, center=(1868,18), inner_text=×
		StaticText ×
```
</details>



```
RootWebArea Verdn, url='https://verdn.com/'
	main
		link, url='https://verdn.com/'
			image
		navigation Main
```
<details><summary>Show more</summary>

```
			list
				listitem
					link For nonprofits, url='https://verdn.com/product/for-nonprofits'
				listitem
					link Case studies, url='https://verdn.com/resources/case-studies'
		link Log in, url='https://verdn.com/app/log-in'
			button Log in
				image
		image hero-bg-gradient, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fbg-mesh-1.png&w=1200&q=75'
		heading Make donations a revenue center
		paragraph
			StaticText Verdn's best-in-class tool set provides you the power to give back with any action, tell the full impact story, and prove it moves the metrics you care most about.
		button Talk to us
			image
		figure
			StaticText ACME Ϫ FASHIONS
			image
			StaticText Women
			StaticText >
			StaticText Bags
			StaticText >
			StaticText Handbags
			image test-clutch, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fclutch.png&w=640&q=75'
			StaticText Orford clutch
			image
			StaticText $299
			image
			StaticText Plants 5 trees
			StaticText Track impact post-purchase
			StaticText BUY NOW
			StaticText Description
			StaticText This classic purse has been handcrafted from the finest Venetian vegan leather.
			StaticText ecomm. order
			image
			StaticText Acme fashions
			image
			StaticText 1337
			image
			StaticText paula.stike@example.com
			StaticText Pledge for
			StaticText 5 trees
			StaticText created
			StaticText $2.78
			StaticText sent to impact partner
			image
			StaticText Impact email sent
			image test-paula, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fpaula.png&w=128&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		StaticText USE CASES
		heading The platform for giving back
		heading For companies
		paragraph
			StaticText Give back effortlessly with any action, tell your complete impact story, and prove that it moves the metrics you care most about.
		image
		StaticText Integrate your give back into any aspect of your business in a few clicks.
		image
		StaticText Drive engagement by leveraging impact storytelling from your nonprofit partner.
		image
		StaticText Measure how donations drive the KPIs that matter to your business.
		code
			StaticText import
			StaticText axios
			StaticText from
			StaticText "axios"
			StaticText ;
			StaticText const
			StaticText makePledge
			StaticText =
			StaticText async
			StaticText ({
			StaticText customer
			StaticText })
			StaticText =>
			StaticText {
			StaticText const
			StaticText response
			StaticText =
			StaticText await
			StaticText axios.
			StaticText post
			StaticText (
			StaticText "https://verdn.com/api/impact"
			StaticText ,
			StaticText {
			StaticText amount:
			StaticText 1
			StaticText ,
			StaticText unit:
			StaticText "kg"
			StaticText ,
			StaticText impactOffering:
			StaticText "OceanPlastic"
			StaticText }
			StaticText );
			StaticText if
			StaticText (response.status
			StaticText ===
			StaticText 200
			StaticText ) {
			StaticText await
			StaticText sendEmail
			StaticText (customer.email);
			StaticText }
			StaticText }
			StaticText // ...
			StaticText const
			StaticText processOrder
			StaticText =
			StaticText async
			StaticText ({
			StaticText customer
			StaticText })
			StaticText =>
			StaticText {
			StaticText // ...After order has completed
			StaticText await
			StaticText makePledge
			StaticText (customer);
			StaticText }
		heading For nonprofits
		paragraph
			StaticText Meet corporations where they are with Verdn's seamless tech. Empower them to get set up in minutes, and track positive KPI outcomes.
		link Discover Verdn for nonprofits, url='https://verdn.com/product/for-nonprofits'
			button Discover Verdn for nonprofits
				image
		StaticText PROVEN VALUE
		heading Drive KPIs across your business
		StaticText CONVERT
		heading Sell more by donating with every product or order
		image
		StaticText Leverage rules to give back on your terms.
		image
		StaticText Display widgets across your site to tell your visitors.
		image
		StaticText Track how pledging increases your conversion rate.
		figure
			StaticText ACME Ϫ FASHIONS
			image
			StaticText Women
			StaticText >
			StaticText Bags
			StaticText >
			StaticText Handbags
			image test-clutch, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fclutch.png&w=640&q=75'
			StaticText Orford clutch
			image
			StaticText $299
			image
			StaticText Plants 5 trees
			StaticText Track impact post-purchase
			StaticText BUY NOW
			StaticText Description
			StaticText This classic purse has been handcrafted from the finest Venetian vegan leather. We recommend pairing this piece with something from our
			StaticText Autumnal Look-book
			StaticText to get the true Acme take.
			StaticText 1.8
			StaticText %
			image
			StaticText CVR
			StaticText CONVERSION RATE
		StaticText INFORM
		heading Drive user interaction with incentives and rewards
		image
		StaticText Attach a donation pledge to any user action.
		image
		StaticText Promote loyalty by letting users accumulate impact.
		image
		StaticText Save money vs gift cards with cost-efficient projects.
		figure
			image
			StaticText Inbox (27)
			StaticText Help us improve ou...
			image
			image
			StaticText COLLISON BANK
			paragraph
				StaticText Dear Alice,
			paragraph
				StaticText Thank you for banking with us. To help us improve our service, please take this short survey. As a thank you,
				StaticText we'll make a donation
				StaticText to our nonprofit partner. Your impact gets added to your existing total.
			StaticText Take our survey
			image
			image
			StaticText Recover 200cm² coral reef
			StaticText 1,337
			image
			StaticText Responses
		StaticText ENGAGE
		heading Boost user engagement with unique impact storytelling
		image
		StaticText Deepen your customer and user relationships.
		image
		StaticText Let customers track the impact of your donations.
		image
		StaticText Integrate impact data to email, SMS, and most other notification channels.
		figure
			image Mary for timeline, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fmary.png&w=256&q=75'
			StaticText Mary's impact
			StaticText 5 trees planted
			heading Impact timeline
			image
			StaticText 7th January, 4:32 am
			StaticText Trees planted
			image
			StaticText Great news! Your trees have now been planted.
			StaticText Check out the project update below.
			image Eden update, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Feden-update-2.webp&w=1200&q=75'
			StaticText 500%
			image
			StaticText Email clicks
		StaticText RETAIN
		heading Increase customer LTV with green marketing and rewards
		image
		StaticText Stay top-of-mind with timely impact updates.
		image
		StaticText Deploy a toolkit of incentives to nudge behavior.
		image
		StaticText Avoid promotion-fatigue, or bland reminders.
		figure
			StaticText LIMITED TIME OFFER
			image
			paragraph
				StaticText We haven't seen you in a while so we'd love to
				StaticText offer you
				strong
					StaticText twice
				StaticText the impact
				StaticText when you book your next session. Click below to redeem.
			StaticText Book a
			StaticText double-impact
			StaticText session
			paragraph
				StaticText You have currently recovered 850 bottles' worth of ocean-bound plastic.
				StaticText Track updates to your impact here.
			StaticText 15%
			image
			StaticText Retention MoM
		StaticText EASY INTEGRATION
		heading Seamless setup
		paragraph
			StaticText Whatever your stack, Verdn integrates cleanly and doesn't get in the way. It takes usually just 10 minutes to get fully set up and starting to donate.
		heading No code
		paragraph
			StaticText Automate your giveback in 5 minutes, and start reaping a measurable ROI with our award-winning Shopify app.
		image
		heading 5.0
		image
		image
		image
		image
		image
		paragraph
			StaticText 50
			StaticText Reviews
		link Install Shopify app, url='https://apps.shopify.com/verdn-sell-with-impact'
			button Install Shopify app
				image
		heading Low code
		paragraph
			StaticText Start unleashing the power of your nonprofit partnership with a single
			StaticText POST
			StaticText –call triggered by any
			StaticText action
			StaticText taken by a user or customer.
		button Join our API program
			image
		StaticText CASE STUDIES
		heading Don't take it from us
		StaticText Revitalize
		StaticText loyalty
		StaticText Use Verdn as part of your loyalty and customer rewards programs to grow redemptions.
		StaticText Boost
		StaticText your ROI
		StaticText Our A/B testing pipeline allows you to see the results of your give-back on your bottom line.
		StaticText Bespoke
		StaticText impact providers
		StaticText Bring your own charity or NGO partner to Verdn with our white-glove provider integration.
		image alo-yoga background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Falo-test-bg.jpg&w=1200&q=75'
		StaticText Customer success
		StaticText "This partnership was a no-brainer. Our loyalty program is environmentally conscious and aligns to our values with Verdn."
		StaticText Cher Fuller
		StaticText |
		StaticText Head of Growth, Alo Yoga
		image alo-yoga logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		image alo-yoga logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		image shady-rays background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fsr-test-bg.webp&w=1200&q=75'
		StaticText Customer success
		StaticText "Verdn has been a game-changer for us. It's boosted our customer engagement and generates a positive ROI for our give back program."
		StaticText Jenny Howard
		StaticText |
		StaticText Strategic Comms. Director, Shady Rays
		image shady-rays logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		image shady-rays logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		image cariuma background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fcariuma-test-bg.jpg&w=1200&q=75'
		StaticText Customer success
		StaticText "We'd been looking for a better way to engage our customers about our impact, and Verdn's platform was the perfect solution for us."
		StaticText Felipe Arujao
		StaticText |
		StaticText Head of Growth, Cariuma
		image cariuma logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		image cariuma logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		heading Truly global and transparent impact
		paragraph
			StaticText By working with a hand-picked roster of vetted charities, NGOs, and impact organizations, Verdn is able to offer unparalleled on-the-ground reporting.
		StaticText Our flagship partners
		link eden-logo, url='https://eden-plus.org/'
			image eden-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Feden-logo.png&w=640&q=75'
		link empower-logo, url='https://empower.eco/'
			image empower-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fempower-logo.png&w=640&q=75'
		link coralive-logo, url='https://coralive.org/'
			image coralive-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fcoralive-logo.png&w=640&q=75'
		link, url='https://verdn.com/'
			image
		link, url='https://www.bcorporation.net/find-a-b-corp/company/verdn/'
			image
		link Backed by, url='https://ycombinator.com/companies/verdn'
			image
		heading RESOURCES
		link For nonprofits, url='https://verdn.com/product/for-nonprofits'
		link For AI, url='https://verdn.com/product/for-ai'
		link Case studies, url='https://verdn.com/resources/case-studies'
		heading COMPANY
		link About us, url='https://www.ycombinator.com/companies/verdn'
		link Work at Verdn, url='https://www.workatastartup.com/companies/verdn'
		StaticText Contact us
		link Privacy policy, url='https://verdn.com/legal/privacy-policy'
		link Cookie policy, url='https://verdn.com/legal/cookie-policy'
		StaticText ©
		StaticText 2025
		StaticText Verdn Ltd. All rights reserved.
		StaticText Made around the 🌍
		link, url='https://linkedin.com/company/verdn'
			image
		link, url='https://instagram.com/verdn.impact'
			image
	region Notifications (F8)
		list
	alert, atomic
	[a] Iframe, center=(960,540)
		RootWebArea Landing General (2024), focused, url='https://form.typeform.com/to/VsQntgWS?typeform-embed-id=6184888407998836&typeform-embed=popup-blank&typeform-source=verdn.com&typeform-medium=embed-sdk&typeform-medium-version=next&typeform-embed-handles-redirect=1&typeform-embed-no-heading=true'
			banner
				image, url='https://images.typeform.com/images/ZVxG8jgxEWW3'
			main
				progressbar Form progress value='25'
				StaticText Question 1
				LabelText
					StaticText What is your
					strong
						StaticText name?
					StaticText This question is required.
				paragraph
				[a116] textbox What is your name? This question is required. value='John Doe', center=(960,512), focused
				[a123] button OK, center=(630,570)
					StaticText OK
				navigation
					[a192] button Navigate to next question, center=(1655,992)
						image
					button Navigate to previous question, disabled=True
						image
				[a209] link Powered by Typeform, center=(1765,992), url='https://www.typeform.com/explore/?utm_campaign=VsQntgWS&utm_source=typeform.com-01EM1WHFEBS2JC51892DK9V11Y-basic&utm_medium=typeform&utm_content=typeform-footer&utm_term=EN'
					StaticText Powered by
					strong
						StaticText Typeform
	[809] button Close, center=(1868,18), inner_text=×
		StaticText ×
```
</details>

**Reasoning for action:** I chose to fill the name input field with 'John Doe' because it's a required field necessary for progressing to the next step in the inquiry process. By completing this step, I ensure that the form can transition to allow for the input of my work email, fulfilling the user's goal of receiving personalized assistance.

**Action:** fill('a116', 'John Doe') # Fill in the name input field with 'John Doe'.

**Change Description:** The name input field in the form now contains the value 'John Doe', indicating that the user filled out the name field, and the progress of the form increased to 25%.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://verdn.com/

https://verdn.com/

**Content (before/after):** 

```
RootWebArea Verdn, url='https://verdn.com/'
	main
		link, url='https://verdn.com/'
			image
		navigation Main
```
<details><summary>Show more</summary>

```
			list
				listitem
					link For nonprofits, url='https://verdn.com/product/for-nonprofits'
				listitem
					link Case studies, url='https://verdn.com/resources/case-studies'
		link Log in, url='https://verdn.com/app/log-in'
			button Log in
				image
		image hero-bg-gradient, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fbg-mesh-1.png&w=1200&q=75'
		heading Make donations a revenue center
		paragraph
			StaticText Verdn's best-in-class tool set provides you the power to give back with any action, tell the full impact story, and prove it moves the metrics you care most about.
		button Talk to us
			image
		figure
			StaticText ACME Ϫ FASHIONS
			image
			StaticText Women
			StaticText >
			StaticText Bags
			StaticText >
			StaticText Handbags
			image test-clutch, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fclutch.png&w=640&q=75'
			StaticText Orford clutch
			image
			StaticText $299
			image
			StaticText Plants 5 trees
			StaticText Track impact post-purchase
			StaticText BUY NOW
			StaticText Description
			StaticText This classic purse has been handcrafted from the finest Venetian vegan leather.
			StaticText ecomm. order
			image
			StaticText Acme fashions
			image
			StaticText 1337
			image
			StaticText paula.stike@example.com
			StaticText Pledge for
			StaticText 5 trees
			StaticText created
			StaticText $2.78
			StaticText sent to impact partner
			image
			StaticText Impact email sent
			image test-paula, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fpaula.png&w=128&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		StaticText USE CASES
		heading The platform for giving back
		heading For companies
		paragraph
			StaticText Give back effortlessly with any action, tell your complete impact story, and prove that it moves the metrics you care most about.
		image
		StaticText Integrate your give back into any aspect of your business in a few clicks.
		image
		StaticText Drive engagement by leveraging impact storytelling from your nonprofit partner.
		image
		StaticText Measure how donations drive the KPIs that matter to your business.
		code
			StaticText import
			StaticText axios
			StaticText from
			StaticText "axios"
			StaticText ;
			StaticText const
			StaticText makePledge
			StaticText =
			StaticText async
			StaticText ({
			StaticText customer
			StaticText })
			StaticText =>
			StaticText {
			StaticText const
			StaticText response
			StaticText =
			StaticText await
			StaticText axios.
			StaticText post
			StaticText (
			StaticText "https://verdn.com/api/impact"
			StaticText ,
			StaticText {
			StaticText amount:
			StaticText 1
			StaticText ,
			StaticText unit:
			StaticText "kg"
			StaticText ,
			StaticText impactOffering:
			StaticText "OceanPlastic"
			StaticText }
			StaticText );
			StaticText if
			StaticText (response.status
			StaticText ===
			StaticText 200
			StaticText ) {
			StaticText await
			StaticText sendEmail
			StaticText (customer.email);
			StaticText }
			StaticText }
			StaticText // ...
			StaticText const
			StaticText processOrder
			StaticText =
			StaticText async
			StaticText ({
			StaticText customer
			StaticText })
			StaticText =>
			StaticText {
			StaticText // ...After order has completed
			StaticText await
			StaticText makePledge
			StaticText (customer);
			StaticText }
		heading For nonprofits
		paragraph
			StaticText Meet corporations where they are with Verdn's seamless tech. Empower them to get set up in minutes, and track positive KPI outcomes.
		link Discover Verdn for nonprofits, url='https://verdn.com/product/for-nonprofits'
			button Discover Verdn for nonprofits
				image
		StaticText PROVEN VALUE
		heading Drive KPIs across your business
		StaticText CONVERT
		heading Sell more by donating with every product or order
		image
		StaticText Leverage rules to give back on your terms.
		image
		StaticText Display widgets across your site to tell your visitors.
		image
		StaticText Track how pledging increases your conversion rate.
		figure
			StaticText ACME Ϫ FASHIONS
			image
			StaticText Women
			StaticText >
			StaticText Bags
			StaticText >
			StaticText Handbags
			image test-clutch, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fclutch.png&w=640&q=75'
			StaticText Orford clutch
			image
			StaticText $299
			image
			StaticText Plants 5 trees
			StaticText Track impact post-purchase
			StaticText BUY NOW
			StaticText Description
			StaticText This classic purse has been handcrafted from the finest Venetian vegan leather. We recommend pairing this piece with something from our
			StaticText Autumnal Look-book
			StaticText to get the true Acme take.
			StaticText 1.8
			StaticText %
			image
			StaticText CVR
			StaticText CONVERSION RATE
		StaticText INFORM
		heading Drive user interaction with incentives and rewards
		image
		StaticText Attach a donation pledge to any user action.
		image
		StaticText Promote loyalty by letting users accumulate impact.
		image
		StaticText Save money vs gift cards with cost-efficient projects.
		figure
			image
			StaticText Inbox (27)
			StaticText Help us improve ou...
			image
			image
			StaticText COLLISON BANK
			paragraph
				StaticText Dear Alice,
			paragraph
				StaticText Thank you for banking with us. To help us improve our service, please take this short survey. As a thank you,
				StaticText we'll make a donation
				StaticText to our nonprofit partner. Your impact gets added to your existing total.
			StaticText Take our survey
			image
			image
			StaticText Recover 200cm² coral reef
			StaticText 1,337
			image
			StaticText Responses
		StaticText ENGAGE
		heading Boost user engagement with unique impact storytelling
		image
		StaticText Deepen your customer and user relationships.
		image
		StaticText Let customers track the impact of your donations.
		image
		StaticText Integrate impact data to email, SMS, and most other notification channels.
		figure
			image Mary for timeline, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fmary.png&w=256&q=75'
			StaticText Mary's impact
			StaticText 5 trees planted
			heading Impact timeline
			image
			StaticText 7th January, 4:32 am
			StaticText Trees planted
			image
			StaticText Great news! Your trees have now been planted.
			StaticText Check out the project update below.
			image Eden update, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Feden-update-2.webp&w=1200&q=75'
			StaticText 500%
			image
			StaticText Email clicks
		StaticText RETAIN
		heading Increase customer LTV with green marketing and rewards
		image
		StaticText Stay top-of-mind with timely impact updates.
		image
		StaticText Deploy a toolkit of incentives to nudge behavior.
		image
		StaticText Avoid promotion-fatigue, or bland reminders.
		figure
			StaticText LIMITED TIME OFFER
			image
			paragraph
				StaticText We haven't seen you in a while so we'd love to
				StaticText offer you
				strong
					StaticText twice
				StaticText the impact
				StaticText when you book your next session. Click below to redeem.
			StaticText Book a
			StaticText double-impact
			StaticText session
			paragraph
				StaticText You have currently recovered 850 bottles' worth of ocean-bound plastic.
				StaticText Track updates to your impact here.
			StaticText 15%
			image
			StaticText Retention MoM
		StaticText EASY INTEGRATION
		heading Seamless setup
		paragraph
			StaticText Whatever your stack, Verdn integrates cleanly and doesn't get in the way. It takes usually just 10 minutes to get fully set up and starting to donate.
		heading No code
		paragraph
			StaticText Automate your giveback in 5 minutes, and start reaping a measurable ROI with our award-winning Shopify app.
		image
		heading 5.0
		image
		image
		image
		image
		image
		paragraph
			StaticText 50
			StaticText Reviews
		link Install Shopify app, url='https://apps.shopify.com/verdn-sell-with-impact'
			button Install Shopify app
				image
		heading Low code
		paragraph
			StaticText Start unleashing the power of your nonprofit partnership with a single
			StaticText POST
			StaticText –call triggered by any
			StaticText action
			StaticText taken by a user or customer.
		button Join our API program
			image
		StaticText CASE STUDIES
		heading Don't take it from us
		StaticText Revitalize
		StaticText loyalty
		StaticText Use Verdn as part of your loyalty and customer rewards programs to grow redemptions.
		StaticText Boost
		StaticText your ROI
		StaticText Our A/B testing pipeline allows you to see the results of your give-back on your bottom line.
		StaticText Bespoke
		StaticText impact providers
		StaticText Bring your own charity or NGO partner to Verdn with our white-glove provider integration.
		image alo-yoga background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Falo-test-bg.jpg&w=1200&q=75'
		StaticText Customer success
		StaticText "This partnership was a no-brainer. Our loyalty program is environmentally conscious and aligns to our values with Verdn."
		StaticText Cher Fuller
		StaticText |
		StaticText Head of Growth, Alo Yoga
		image alo-yoga logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		image alo-yoga logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		image shady-rays background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fsr-test-bg.webp&w=1200&q=75'
		StaticText Customer success
		StaticText "Verdn has been a game-changer for us. It's boosted our customer engagement and generates a positive ROI for our give back program."
		StaticText Jenny Howard
		StaticText |
		StaticText Strategic Comms. Director, Shady Rays
		image shady-rays logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		image shady-rays logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		image cariuma background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fcariuma-test-bg.jpg&w=1200&q=75'
		StaticText Customer success
		StaticText "We'd been looking for a better way to engage our customers about our impact, and Verdn's platform was the perfect solution for us."
		StaticText Felipe Arujao
		StaticText |
		StaticText Head of Growth, Cariuma
		image cariuma logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		image cariuma logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		heading Truly global and transparent impact
		paragraph
			StaticText By working with a hand-picked roster of vetted charities, NGOs, and impact organizations, Verdn is able to offer unparalleled on-the-ground reporting.
		StaticText Our flagship partners
		link eden-logo, url='https://eden-plus.org/'
			image eden-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Feden-logo.png&w=640&q=75'
		link empower-logo, url='https://empower.eco/'
			image empower-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fempower-logo.png&w=640&q=75'
		link coralive-logo, url='https://coralive.org/'
			image coralive-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fcoralive-logo.png&w=640&q=75'
		link, url='https://verdn.com/'
			image
		link, url='https://www.bcorporation.net/find-a-b-corp/company/verdn/'
			image
		link Backed by, url='https://ycombinator.com/companies/verdn'
			image
		heading RESOURCES
		link For nonprofits, url='https://verdn.com/product/for-nonprofits'
		link For AI, url='https://verdn.com/product/for-ai'
		link Case studies, url='https://verdn.com/resources/case-studies'
		heading COMPANY
		link About us, url='https://www.ycombinator.com/companies/verdn'
		link Work at Verdn, url='https://www.workatastartup.com/companies/verdn'
		StaticText Contact us
		link Privacy policy, url='https://verdn.com/legal/privacy-policy'
		link Cookie policy, url='https://verdn.com/legal/cookie-policy'
		StaticText ©
		StaticText 2025
		StaticText Verdn Ltd. All rights reserved.
		StaticText Made around the 🌍
		link, url='https://linkedin.com/company/verdn'
			image
		link, url='https://instagram.com/verdn.impact'
			image
	region Notifications (F8)
		list
	alert, atomic
	[a] Iframe, center=(960,540)
		RootWebArea Landing General (2024), focused, url='https://form.typeform.com/to/VsQntgWS?typeform-embed-id=6184888407998836&typeform-embed=popup-blank&typeform-source=verdn.com&typeform-medium=embed-sdk&typeform-medium-version=next&typeform-embed-handles-redirect=1&typeform-embed-no-heading=true'
			banner
				image, url='https://images.typeform.com/images/ZVxG8jgxEWW3'
			main
				progressbar Form progress value='25'
				StaticText Question 1
				LabelText
					StaticText What is your
					strong
						StaticText name?
					StaticText This question is required.
				paragraph
				[a116] textbox What is your name? This question is required. value='John Doe', center=(960,512), focused
				[a123] button OK, center=(630,570)
					StaticText OK
				navigation
					[a192] button Navigate to next question, center=(1655,992)
						image
					button Navigate to previous question, disabled=True
						image
				[a209] link Powered by Typeform, center=(1765,992), url='https://www.typeform.com/explore/?utm_campaign=VsQntgWS&utm_source=typeform.com-01EM1WHFEBS2JC51892DK9V11Y-basic&utm_medium=typeform&utm_content=typeform-footer&utm_term=EN'
					StaticText Powered by
					strong
						StaticText Typeform
	[809] button Close, center=(1868,18), inner_text=×
		StaticText ×
```
</details>



```
RootWebArea Verdn, url='https://verdn.com/'
	main
		link, url='https://verdn.com/'
			image
		navigation Main
```
<details><summary>Show more</summary>

```
			list
				listitem
					link For nonprofits, url='https://verdn.com/product/for-nonprofits'
				listitem
					link Case studies, url='https://verdn.com/resources/case-studies'
		link Log in, url='https://verdn.com/app/log-in'
			button Log in
				image
		image hero-bg-gradient, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fbg-mesh-1.png&w=1200&q=75'
		heading Make donations a revenue center
		paragraph
			StaticText Verdn's best-in-class tool set provides you the power to give back with any action, tell the full impact story, and prove it moves the metrics you care most about.
		button Talk to us
			image
		figure
			StaticText ACME Ϫ FASHIONS
			image
			StaticText Women
			StaticText >
			StaticText Bags
			StaticText >
			StaticText Handbags
			image test-clutch, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fclutch.png&w=640&q=75'
			StaticText Orford clutch
			image
			StaticText $299
			image
			StaticText Plants 5 trees
			StaticText Track impact post-purchase
			StaticText BUY NOW
			StaticText Description
			StaticText This classic purse has been handcrafted from the finest Venetian vegan leather.
			StaticText ecomm. order
			image
			StaticText Acme fashions
			image
			StaticText 1337
			image
			StaticText paula.stike@example.com
			StaticText Pledge for
			StaticText 5 trees
			StaticText created
			StaticText $2.78
			StaticText sent to impact partner
			image
			StaticText Impact email sent
			image test-paula, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fpaula.png&w=128&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		link Ren Skincare, url='https://renskincare.com/'
			image Ren Skincare, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fren.png&w=640&q=75'
		link Shady Rays, url='https://shadyrays.com/'
			image Shady Rays, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		link Alo Yoga, url='https://aloyoga.com/'
			image Alo Yoga, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		link Ohh Deer, url='https://ohhdeer.com/'
			image Ohh Deer, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fohh-deer.png&w=640&q=75'
		link Cariuma, url='https://cariuma.com/'
			image Cariuma, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		StaticText USE CASES
		heading The platform for giving back
		heading For companies
		paragraph
			StaticText Give back effortlessly with any action, tell your complete impact story, and prove that it moves the metrics you care most about.
		image
		StaticText Integrate your give back into any aspect of your business in a few clicks.
		image
		StaticText Drive engagement by leveraging impact storytelling from your nonprofit partner.
		image
		StaticText Measure how donations drive the KPIs that matter to your business.
		code
			StaticText import
			StaticText axios
			StaticText from
			StaticText "axios"
			StaticText ;
			StaticText const
			StaticText makePledge
			StaticText =
			StaticText async
			StaticText ({
			StaticText customer
			StaticText })
			StaticText =>
			StaticText {
			StaticText const
			StaticText response
			StaticText =
			StaticText await
			StaticText axios.
			StaticText post
			StaticText (
			StaticText "https://verdn.com/api/impact"
			StaticText ,
			StaticText {
			StaticText amount:
			StaticText 1
			StaticText ,
			StaticText unit:
			StaticText "kg"
			StaticText ,
			StaticText impactOffering:
			StaticText "OceanPlastic"
			StaticText }
			StaticText );
			StaticText if
			StaticText (response.status
			StaticText ===
			StaticText 200
			StaticText ) {
			StaticText await
			StaticText sendEmail
			StaticText (customer.email);
			StaticText }
			StaticText }
			StaticText // ...
			StaticText const
			StaticText processOrder
			StaticText =
			StaticText async
			StaticText ({
			StaticText customer
			StaticText })
			StaticText =>
			StaticText {
			StaticText // ...After order has completed
			StaticText await
			StaticText makePledge
			StaticText (customer);
			StaticText }
		heading For nonprofits
		paragraph
			StaticText Meet corporations where they are with Verdn's seamless tech. Empower them to get set up in minutes, and track positive KPI outcomes.
		link Discover Verdn for nonprofits, url='https://verdn.com/product/for-nonprofits'
			button Discover Verdn for nonprofits
				image
		StaticText PROVEN VALUE
		heading Drive KPIs across your business
		StaticText CONVERT
		heading Sell more by donating with every product or order
		image
		StaticText Leverage rules to give back on your terms.
		image
		StaticText Display widgets across your site to tell your visitors.
		image
		StaticText Track how pledging increases your conversion rate.
		figure
			StaticText ACME Ϫ FASHIONS
			image
			StaticText Women
			StaticText >
			StaticText Bags
			StaticText >
			StaticText Handbags
			image test-clutch, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fclutch.png&w=640&q=75'
			StaticText Orford clutch
			image
			StaticText $299
			image
			StaticText Plants 5 trees
			StaticText Track impact post-purchase
			StaticText BUY NOW
			StaticText Description
			StaticText This classic purse has been handcrafted from the finest Venetian vegan leather. We recommend pairing this piece with something from our
			StaticText Autumnal Look-book
			StaticText to get the true Acme take.
			StaticText 1.8
			StaticText %
			image
			StaticText CVR
			StaticText CONVERSION RATE
		StaticText INFORM
		heading Drive user interaction with incentives and rewards
		image
		StaticText Attach a donation pledge to any user action.
		image
		StaticText Promote loyalty by letting users accumulate impact.
		image
		StaticText Save money vs gift cards with cost-efficient projects.
		figure
			image
			StaticText Inbox (27)
			StaticText Help us improve ou...
			image
			image
			StaticText COLLISON BANK
			paragraph
				StaticText Dear Alice,
			paragraph
				StaticText Thank you for banking with us. To help us improve our service, please take this short survey. As a thank you,
				StaticText we'll make a donation
				StaticText to our nonprofit partner. Your impact gets added to your existing total.
			StaticText Take our survey
			image
			image
			StaticText Recover 200cm² coral reef
			StaticText 1,337
			image
			StaticText Responses
		StaticText ENGAGE
		heading Boost user engagement with unique impact storytelling
		image
		StaticText Deepen your customer and user relationships.
		image
		StaticText Let customers track the impact of your donations.
		image
		StaticText Integrate impact data to email, SMS, and most other notification channels.
		figure
			image Mary for timeline, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fmary.png&w=256&q=75'
			StaticText Mary's impact
			StaticText 5 trees planted
			heading Impact timeline
			image
			StaticText 7th January, 4:32 am
			StaticText Trees planted
			image
			StaticText Great news! Your trees have now been planted.
			StaticText Check out the project update below.
			image Eden update, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Feden-update-2.webp&w=1200&q=75'
			StaticText 500%
			image
			StaticText Email clicks
		StaticText RETAIN
		heading Increase customer LTV with green marketing and rewards
		image
		StaticText Stay top-of-mind with timely impact updates.
		image
		StaticText Deploy a toolkit of incentives to nudge behavior.
		image
		StaticText Avoid promotion-fatigue, or bland reminders.
		figure
			StaticText LIMITED TIME OFFER
			image
			paragraph
				StaticText We haven't seen you in a while so we'd love to
				StaticText offer you
				strong
					StaticText twice
				StaticText the impact
				StaticText when you book your next session. Click below to redeem.
			StaticText Book a
			StaticText double-impact
			StaticText session
			paragraph
				StaticText You have currently recovered 850 bottles' worth of ocean-bound plastic.
				StaticText Track updates to your impact here.
			StaticText 15%
			image
			StaticText Retention MoM
		StaticText EASY INTEGRATION
		heading Seamless setup
		paragraph
			StaticText Whatever your stack, Verdn integrates cleanly and doesn't get in the way. It takes usually just 10 minutes to get fully set up and starting to donate.
		heading No code
		paragraph
			StaticText Automate your giveback in 5 minutes, and start reaping a measurable ROI with our award-winning Shopify app.
		image
		heading 5.0
		image
		image
		image
		image
		image
		paragraph
			StaticText 50
			StaticText Reviews
		link Install Shopify app, url='https://apps.shopify.com/verdn-sell-with-impact'
			button Install Shopify app
				image
		heading Low code
		paragraph
			StaticText Start unleashing the power of your nonprofit partnership with a single
			StaticText POST
			StaticText –call triggered by any
			StaticText action
			StaticText taken by a user or customer.
		button Join our API program
			image
		StaticText CASE STUDIES
		heading Don't take it from us
		StaticText Revitalize
		StaticText loyalty
		StaticText Use Verdn as part of your loyalty and customer rewards programs to grow redemptions.
		StaticText Boost
		StaticText your ROI
		StaticText Our A/B testing pipeline allows you to see the results of your give-back on your bottom line.
		StaticText Bespoke
		StaticText impact providers
		StaticText Bring your own charity or NGO partner to Verdn with our white-glove provider integration.
		image alo-yoga background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Falo-test-bg.jpg&w=1200&q=75'
		StaticText Customer success
		StaticText "This partnership was a no-brainer. Our loyalty program is environmentally conscious and aligns to our values with Verdn."
		StaticText Cher Fuller
		StaticText |
		StaticText Head of Growth, Alo Yoga
		image alo-yoga logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		image alo-yoga logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Falo.png&w=640&q=75'
		image shady-rays background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fsr-test-bg.webp&w=1200&q=75'
		StaticText Customer success
		StaticText "Verdn has been a game-changer for us. It's boosted our customer engagement and generates a positive ROI for our give back program."
		StaticText Jenny Howard
		StaticText |
		StaticText Strategic Comms. Director, Shady Rays
		image shady-rays logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		image shady-rays logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fshady-rays.png&w=640&q=75'
		image cariuma background, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fcariuma-test-bg.jpg&w=1200&q=75'
		StaticText Customer success
		StaticText "We'd been looking for a better way to engage our customers about our impact, and Verdn's platform was the perfect solution for us."
		StaticText Felipe Arujao
		StaticText |
		StaticText Head of Growth, Cariuma
		image cariuma logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		image cariuma logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Flogos%2Fclients%2Fcariuma.png&w=640&q=75'
		heading Truly global and transparent impact
		paragraph
			StaticText By working with a hand-picked roster of vetted charities, NGOs, and impact organizations, Verdn is able to offer unparalleled on-the-ground reporting.
		StaticText Our flagship partners
		link eden-logo, url='https://eden-plus.org/'
			image eden-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Feden-logo.png&w=640&q=75'
		link empower-logo, url='https://empower.eco/'
			image empower-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fempower-logo.png&w=640&q=75'
		link coralive-logo, url='https://coralive.org/'
			image coralive-logo, url='https://verdn.com/_next/image?url=%2Fpublic%2Flanding%2Fscratch%2Fcoralive-logo.png&w=640&q=75'
		link, url='https://verdn.com/'
			image
		link, url='https://www.bcorporation.net/find-a-b-corp/company/verdn/'
			image
		link Backed by, url='https://ycombinator.com/companies/verdn'
			image
		heading RESOURCES
		link For nonprofits, url='https://verdn.com/product/for-nonprofits'
		link For AI, url='https://verdn.com/product/for-ai'
		link Case studies, url='https://verdn.com/resources/case-studies'
		heading COMPANY
		link About us, url='https://www.ycombinator.com/companies/verdn'
		link Work at Verdn, url='https://www.workatastartup.com/companies/verdn'
		StaticText Contact us
		link Privacy policy, url='https://verdn.com/legal/privacy-policy'
		link Cookie policy, url='https://verdn.com/legal/cookie-policy'
		StaticText ©
		StaticText 2025
		StaticText Verdn Ltd. All rights reserved.
		StaticText Made around the 🌍
		link, url='https://linkedin.com/company/verdn'
			image
		link, url='https://instagram.com/verdn.impact'
			image
	region Notifications (F8)
		list
	alert, atomic
	[a] Iframe, center=(960,540)
		RootWebArea Landing General (2024), focused, url='https://form.typeform.com/to/VsQntgWS?typeform-embed-id=6184888407998836&typeform-embed=popup-blank&typeform-source=verdn.com&typeform-medium=embed-sdk&typeform-medium-version=next&typeform-embed-handles-redirect=1&typeform-embed-no-heading=true'
			banner
				image, url='https://images.typeform.com/images/ZVxG8jgxEWW3'
			main
				progressbar Form progress value='25'
				StaticText Question 2
				LabelText
					StaticText What is your
					strong
						StaticText work email address?
					StaticText This question is required.
				paragraph
				[a166] textbox What is your work email address? This question is required., center=(960,512), focused
				[a173] button OK, center=(630,570)
					StaticText OK
				navigation
					[a192] button Navigate to next question, center=(1655,992)
						image
					[a201] button Navigate to previous question, center=(1618,992)
						image
				[a209] link Powered by Typeform, center=(1765,992), url='https://www.typeform.com/explore/?utm_campaign=VsQntgWS&utm_source=typeform.com-01EM1WHFEBS2JC51892DK9V11Y-basic&utm_medium=typeform&utm_content=typeform-footer&utm_term=EN'
					StaticText Powered by
					strong
						StaticText Typeform
	[809] button Close, center=(1868,18), inner_text=×
		StaticText ×
```
</details>

**Reasoning for action:** My reasoning for this action is to fulfill the first part of the user's request, which is to enter their name in the inquiry form. By clicking the 'OK' button, I am submitting the name input, which will trigger the form to transition to the next question. This is necessary to advance in the inquiry submission process, aligning with the user story's success criteria.

**Action:** click('a123') # Click on the 'OK' button to submit the name and proceed to the next question.

**Change Description:** After clicking the 'OK' button to submit the name, the form transitioned to the second question, which now asks for the user's work email address, indicating progress in the form submission process.

**Screenshot before:****Screenshot after:**---


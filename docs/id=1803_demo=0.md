# Task

**Explore HEO's Offerings**

As a potential client or partner,
I explore HEO's technology and partnership opportunities,
so that I can understand how HEO's products and collaborations can benefit my organization.

**Success definition:** Given I am on the HEO Robotics website
When I navigate through the Product, Technology, and Partnerships pages
Then I should see detailed information about HEO's product offerings, technology advancements, and partnership opportunities.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.heospace.com/

https://www.heospace.com/product

**Content (before/after):** 

```
RootWebArea HEO | Non-Earth Imaging, focused, url='https://www.heospace.com/'
	StaticText HEO's NEI camera launches to space
	[43] link Read more, center=(1108,30), url='https://www.heospace.com/blog-posts/heos-nei-camera-aboard-sidus-spaces-lizziesat-tm--2-launches-to-space-expanding-coverage-for-in-orbit-insights'
	[44] image X icon, center=(1539,30), url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/6763a54dfead5f1afb2ffe84_white-close-icon-top-notification-bar-webflow-cloneable-template-brix-templates.svg'
	banner
```
<details><summary>Show more</summary>

```
		[48] link home, center=(171,95), url='https://www.heospace.com/'
			image HEO Logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/64eea8c2afb4f279139664d1_HEO%20Logo%20White.webp'
		navigation
			[51] link Product, center=(1220,95), url='https://www.heospace.com/product'
			[52] link Technology, center=(1324,95), url='https://www.heospace.com/technology'
			[53] link Partnerships, center=(1443,95), url='https://www.heospace.com/partnerships'
			[55] button Resources, center=(1565,95), expanded=False, hasPopup='menu'
			[82] link About, center=(1658,95), url='https://www.heospace.com/about-us'
			[84] link Contact, center=(1771,95), url='mailto:info@heospace.com'
	heading Make Space Transparent
	heading Make Space Transparent
	Video
	StaticText OUR MISSION
	heading Image Anything In The Solar System On-Demand
	paragraph
		StaticText HEO is creating technologies and solutions that ensure a sustainable and secure space environment.
	StaticText ABOUT HEO
	heading The Solution For In-Orbit Insights
	paragraph
		StaticText HEO harnesses the world’s largest commercially available NEI dataset and sensor network to visually monitor your satellites. We deliver high frequency, actionable insights that empower informed and decisive space operations.
	link learn more about HEO, url='https://www.heospace.com/about-us'
		StaticText Learn more
	heading What Is Non-Earth Imaging (NEI)?
	paragraph
		StaticText Non-Earth Imaging (NEI), also referred to as Satellite-to-Satellite imaging (Sat Squared) or Space-to-Space imaging (S2S), involves using space-based sensors to capture resolved imagery of Resident Space Objects (RSOs). This includes other satellites, space debris, space stations, the moon, or asteroids.
	StaticText PRODUCT
	heading Non-Earth Imaging And Insights Services At Scale
	paragraph
		StaticText Our NEI data, archives, and insights provide customers with an unparalleled perspective on spacecraft, enabling early operations support, anomaly detection, identification and capability assessment, pattern-of-life analysis, and beyond.
	link Learn more about HEO's product, url='https://www.heospace.com/product'
		StaticText Learn More
	StaticText TECHNOLOGY
	heading Highly Autonomous Software Meets Sophisticated Hardware
	paragraph
		StaticText Our proprietary software enables fully automated NEI at scale, providing trusted information so you can supercharge your space operations. Our NEI cameras, Holmes and Adler, help us to expand our coverage beyond LEO.
	link Learn about HEO's technology, url='https://www.heospace.com/technology'
		StaticText Learn More
	main
		region carousel
			group 1 of 4
				list
					listitem
						paragraph
							StaticText "With the support of HEO and their resolved imagery we are able to work towards making space more sustainable for future generations."
						StaticText MEKHI DHESI
						StaticText ASTROSCALE UK
			StaticText Slide 1 of 4.
			button Show slide 1 of 4
			button Show slide 2 of 4
			button Show slide 3 of 4
			button Show slide 4 of 4
	StaticText NEI SENSOR NETWORK
	heading Make The Most Out Of Your Time In Orbit
	paragraph
		StaticText HEO is building out a network of NEI sensors. We expand our coverage by partnering with Earth Observation companies and spacecraft owners who can host our NEI cameras.
	link find out about HEO's partnerships, url='https://www.heospace.com/partnerships'
		StaticText Find Out How
	heading Subscribe To Our Newsletter
	paragraph
		StaticText We're dropping product updates, new imagery, and in-orbit insights so you can unlock the power of non-Earth imaging.
	form General Form
		textbox FIRST
		textbox LAST
		textbox EMAIL, required
		button Sign Up
	heading Latest News
	link Read more HEO news, url='https://www.heospace.com/stories'
		StaticText Read More
	list
		listitem
			link main blog image, url='https://www.heospace.com/blog-posts/heos-nei-camera-aboard-sidus-spaces-lizziesat-tm--2-launches-to-space-expanding-coverage-for-in-orbit-insights'
				image, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf5c/67673fd3fb8af106ec464b08_Holmes-004%20Launch-p-800.jpg'
			link author name, url='https://www.heospace.com/#'
				StaticText HEO
			link read the blog, url='https://www.heospace.com/blog-posts/heos-nei-camera-aboard-sidus-spaces-lizziesat-tm--2-launches-to-space-expanding-coverage-for-in-orbit-insights'
				heading HEO’s NEI Camera aboard Sidus Space’s LizzieSat™-2 Launches to Space, Expanding Coverage for In-Orbit Insights
		listitem
			link main blog image, url='https://www.heospace.com/blog-posts/blacksky-awarded-space-domain-awareness-contract-with-heo'
				image, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf5c/66ecb0b703cd934fc8bfaa7c_GX0VpyiXoAArIFL.png'
			link author name, url='https://www.heospace.com/#'
				StaticText HEO
			link read the blog, url='https://www.heospace.com/blog-posts/blacksky-awarded-space-domain-awareness-contract-with-heo'
				heading BlackSky Awarded Space Domain Awareness Contract with HEO and Unlocks Additional Constellation Value by Revolutionizing Non-Earth Imaging Missions
		listitem
			link main blog image, url='https://www.heospace.com/blog-posts/highlights-from-heos-t-minus-3-0'
				image, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf5c/66f4d445a59de41cc62eb631_Webflow%20Blog%20Images.jpg'
			link author name, url='https://www.heospace.com/#'
				StaticText HEO
			link read the blog, url='https://www.heospace.com/blog-posts/highlights-from-heos-t-minus-3-0'
				heading Highlights from HEO's T-Minus 3.0
	contentinfo
		link HEO logo, url='https://www.heospace.com/'
			image HEO logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65c19e62b2de772eb4027354_HEO%20Logo%20Blue-p-500.png'
		link HEO, url='https://www.heospace.com/#Contact-Us'
		StaticText 477 Pitt Street, Haymarket, NSW, 2000. ABN: 52613142448
		StaticText HEO Robotics (UK)
		StaticText SPACES, Covent Garden, 60 St Martin's Ln, London WC2N 4JS. Company number: 13772543
		StaticText HEO USA
		StaticText 3033 Wilson Blvd #700, Arlington, VA 22201
		StaticText Contact
		link info@heospace.com, url='mailto:info@heospace.com'
		link X logo, url='http://twitter.com/heospace'
			image X logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4ea9b4cf361dc52d1d40_sl_z_072523_61700_01-p-500.jpg'
		link LinkedIn logo, url='https://www.linkedin.com/company/high-earth-orbit-robotics/'
			image LinkedIn logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4cfdeab57aaa39104c52_LinkedIn.svg'
		link YouTube logo, url='https://www.youtube.com/channel/UCeNTo1I7PY8m1AANgzlm-xw'
			image YouTube logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4cf25f1595ba0519536c_YouTube.svg'
		link About, url='https://www.heospace.com/about-us'
		link Product, url='https://www.heospace.com/product'
		link Technology, url='https://www.heospace.com/technology'
		link Partnerships, url='https://www.heospace.com/partnerships'
		link Careers, url='https://www.heospace.com/careers'
		link White Papers, url='https://www.heospace.com/white-papers'
		link Stories, url='https://www.heospace.com/stories'
		link Site Status, url='https://stats.uptimerobot.com/OjOB3H5w66'
		StaticText © 2024 High Earth Orbit Robotics Pty Ltd. All right reserved.
		link Privacy Policy, url='https://www.heospace.com/policy-html'
		link Terms & Conditions, url='https://www.heospace.com/terms-conditions'
		link Responsible Disclosure Policy, url='https://www.heospace.com/responsible-disclosure-policy'
	alert, atomic
		alert, atomic
			[417] button Close, center=(1898,956), inner_text=×
				StaticText ×
			StaticText This website uses cookies
			StaticText This website uses cookies to improve user experience. By using our website you consent to all cookies in accordance with our Cookie Policy.
			[423] link Read The Full Cookie Policy, opens a new window, center=(922,995), inner_text=Read The Full Cookie Policy, url='https://www.heospace.com/policy-html'
			[427] checkbox PERFORMANCE, center=(59,1026), checked='false', contenteditable=True, type=checkbox
			image
			LabelText
				StaticText PERFORMANCE
			[432] button SHOW DETAILS, center=(526,1056), inner_text= SHOW DETAILS
				image
			[431] span, center=(130,1026), inner_text=PERFORMANCE
			[440] button ACCEPT ALL, center=(1411,1007)
			[441] button DECLINE ALL, center=(1709,1007)
```
</details>



```
RootWebArea Product | HEO, focused, url='https://www.heospace.com/product'
	banner
		[36] link home, center=(171,36), url='https://www.heospace.com/'
			image HEO Logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/64eea8c2afb4f279139664d1_HEO%20Logo%20White.webp'
		navigation
```
<details><summary>Show more</summary>

```
			[39] link Product, center=(1220,36), url='https://www.heospace.com/product'
			[40] link Technology, center=(1324,36), url='https://www.heospace.com/technology'
			[41] link Partnerships, center=(1443,36), url='https://www.heospace.com/partnerships'
			[43] button Resources, center=(1565,36), expanded=False, hasPopup='menu'
			[70] link About, center=(1658,36), url='https://www.heospace.com/about-us'
			[72] link Contact, center=(1771,36), url='mailto:info@heospace.com'
	heading PRODUCT
	paragraph
		StaticText NEI DATA AND INSIGHTS SERVICES AT SCALE
	heading
	paragraph
		StaticText With over 2500 successful NEI missions, we have helped both government and commercial customers in the US, UK, Australia and Japan make decisions in space with confidence.
	heading Our Services
	tablist, orientation='horizontal'
		tab Early Operations Support, selected=True
		tab In-Orbit Servicing Support, selected=False
		tab Anomaly Attribution, selected=False
		tab De-Risking Re-Entry, selected=False
	tabpanel Early Operations Support
		StaticText Verify the deployment status, attitude, and identity of your spacecraft soon after launch.
	heading How To Access Our Services
	image Laptop icon, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66d7ddb7d0c2c732a9b0b54b_2.svg'
	image Network icon, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66d7ddb7c7d670e908f169fa_1.svg'
	image Paper icon, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66e11936bef92096cd0db831_7.svg'
	image aperature icon, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66e1193523b555eee8512089_6.svg'
	heading Web App & API
	heading Integrations
	heading NEI Reports
	heading NEI Hardware
	paragraph
		StaticText HEO Inspect 3.0 web app and API act as your gateway to HEO’s NEI and insight services.
	paragraph
		StaticText Access our data through systems like the Unified Data Library to provide comprehensive resource for informed decision-making.
	paragraph
		StaticText Receive NEI reports containing foundational and tactical intelligence on space objects via your preferred method of delivery.
	paragraph
		StaticText Host one of HEO's NEI sensors and use our tasking software to convert your spacecraft to an NEI capable platform.
	heading HEO Inspect 3.0
	link Create your free account today, url='https://inspect.heospace.com/sign-up'
	tablist, orientation='horizontal'
		tab Explore, selected=True
		tab Task, selected=False
		tab Analyse, selected=False
	tabpanel Explore
		StaticText Explore HEO’s past non-Earth imagery and insights, sensor coverage, and upcoming imaging opportunities. Decide when to collect new data to support your mission.
	heading Supercharge Your In-Orbit Insights With Our NEI Accelerator Pack
	paragraph
		StaticText HEO's NEI Accelerator Pack enables your organisation to rapidly evaluate the type of NEI data, insights and tools available, and make an informed decision on how to seamlessly integrate this critical type of data to your space domain awareness or intelligence workflows. Fill out the form if you are interested in the pack and we'll be in touch.
	form NEI Accelerator Form
		textbox FIRST
		textbox LAST
		textbox COMPANY
		textbox EMAIL, required
		button Request the NEI Accelerator Pack
	contentinfo
		link HEO logo, url='https://www.heospace.com/'
			image HEO logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65c19e62b2de772eb4027354_HEO%20Logo%20Blue-p-500.png'
		link HEO, url='https://www.heospace.com/product#Contact-Us'
		StaticText 477 Pitt Street, Haymarket, NSW, 2000. ABN: 52613142448
		StaticText HEO Robotics (UK)
		StaticText SPACES, Covent Garden, 60 St Martin's Ln, London WC2N 4JS. Company number: 13772543
		StaticText HEO USA
		StaticText 3033 Wilson Blvd #700, Arlington, VA 22201
		StaticText Contact
		link info@heospace.com, url='mailto:info@heospace.com'
		link X logo, url='http://twitter.com/heospace'
			image X logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4ea9b4cf361dc52d1d40_sl_z_072523_61700_01-p-500.jpg'
		link LinkedIn logo, url='https://www.linkedin.com/company/high-earth-orbit-robotics/'
			image LinkedIn logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4cfdeab57aaa39104c52_LinkedIn.svg'
		link YouTube logo, url='https://www.youtube.com/channel/UCeNTo1I7PY8m1AANgzlm-xw'
			image YouTube logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4cf25f1595ba0519536c_YouTube.svg'
		link About, url='https://www.heospace.com/about-us'
		link Product, url='https://www.heospace.com/product'
		link Technology, url='https://www.heospace.com/technology'
		link Partnerships, url='https://www.heospace.com/partnerships'
		link Careers, url='https://www.heospace.com/careers'
		link White Papers, url='https://www.heospace.com/white-papers'
		link Stories, url='https://www.heospace.com/stories'
		link Site Status, url='https://stats.uptimerobot.com/OjOB3H5w66'
		StaticText © 2024 High Earth Orbit Robotics Pty Ltd. All right reserved.
		link Privacy Policy, url='https://www.heospace.com/policy-html'
		link Terms & Conditions, url='https://www.heospace.com/terms-conditions'
		link Responsible Disclosure Policy, url='https://www.heospace.com/responsible-disclosure-policy'
	alert, atomic
		alert, atomic
			[355] button Close, center=(1898,956), inner_text=×
				StaticText ×
			StaticText This website uses cookies
			StaticText This website uses cookies to improve user experience. By using our website you consent to all cookies in accordance with our Cookie Policy.
			[361] link Read The Full Cookie Policy, opens a new window, center=(922,995), inner_text=Read The Full Cookie Policy, url='https://www.heospace.com/policy-html'
			[365] checkbox PERFORMANCE, center=(59,1026), checked='false', contenteditable=True, type=checkbox
			image
			LabelText
				StaticText PERFORMANCE
			[370] button SHOW DETAILS, center=(526,1056), inner_text= SHOW DETAILS
				image
			[369] span, center=(130,1026), inner_text=PERFORMANCE
			[378] button ACCEPT ALL, center=(1411,1007)
			[379] button DECLINE ALL, center=(1709,1007)
```
</details>

**Reasoning for action:** By clicking on the Product link, I am accessing a section that provides comprehensive details on HEO's product offerings. This is crucial for the user story because understanding the products is the first step toward exploring how these offerings can benefit the user's organization.

**Action:** click(51) # Click on the Product link to explore HEO's products.

**Change Description:** After clicking the Product link, the browser state changed to display the Product page for HEO, highlighting NEI data and insights services along with details about their offerings and how to access them, rather than the initial homepage content.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.heospace.com/product

https://www.heospace.com/technology

**Content (before/after):** 

```
RootWebArea Product | HEO, focused, url='https://www.heospace.com/product'
	banner
		[36] link home, center=(171,36), url='https://www.heospace.com/'
			image HEO Logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/64eea8c2afb4f279139664d1_HEO%20Logo%20White.webp'
		navigation
```
<details><summary>Show more</summary>

```
			[39] link Product, center=(1220,36), url='https://www.heospace.com/product'
			[40] link Technology, center=(1324,36), url='https://www.heospace.com/technology'
			[41] link Partnerships, center=(1443,36), url='https://www.heospace.com/partnerships'
			[43] button Resources, center=(1565,36), expanded=False, hasPopup='menu'
			[70] link About, center=(1658,36), url='https://www.heospace.com/about-us'
			[72] link Contact, center=(1771,36), url='mailto:info@heospace.com'
	heading PRODUCT
	paragraph
		StaticText NEI DATA AND INSIGHTS SERVICES AT SCALE
	heading
	paragraph
		StaticText With over 2500 successful NEI missions, we have helped both government and commercial customers in the US, UK, Australia and Japan make decisions in space with confidence.
	heading Our Services
	tablist, orientation='horizontal'
		tab Early Operations Support, selected=True
		tab In-Orbit Servicing Support, selected=False
		tab Anomaly Attribution, selected=False
		tab De-Risking Re-Entry, selected=False
	tabpanel Early Operations Support
		StaticText Verify the deployment status, attitude, and identity of your spacecraft soon after launch.
	heading How To Access Our Services
	image Laptop icon, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66d7ddb7d0c2c732a9b0b54b_2.svg'
	image Network icon, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66d7ddb7c7d670e908f169fa_1.svg'
	image Paper icon, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66e11936bef92096cd0db831_7.svg'
	image aperature icon, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66e1193523b555eee8512089_6.svg'
	heading Web App & API
	heading Integrations
	heading NEI Reports
	heading NEI Hardware
	paragraph
		StaticText HEO Inspect 3.0 web app and API act as your gateway to HEO’s NEI and insight services.
	paragraph
		StaticText Access our data through systems like the Unified Data Library to provide comprehensive resource for informed decision-making.
	paragraph
		StaticText Receive NEI reports containing foundational and tactical intelligence on space objects via your preferred method of delivery.
	paragraph
		StaticText Host one of HEO's NEI sensors and use our tasking software to convert your spacecraft to an NEI capable platform.
	heading HEO Inspect 3.0
	link Create your free account today, url='https://inspect.heospace.com/sign-up'
	tablist, orientation='horizontal'
		tab Explore, selected=True
		tab Task, selected=False
		tab Analyse, selected=False
	tabpanel Explore
		StaticText Explore HEO’s past non-Earth imagery and insights, sensor coverage, and upcoming imaging opportunities. Decide when to collect new data to support your mission.
	heading Supercharge Your In-Orbit Insights With Our NEI Accelerator Pack
	paragraph
		StaticText HEO's NEI Accelerator Pack enables your organisation to rapidly evaluate the type of NEI data, insights and tools available, and make an informed decision on how to seamlessly integrate this critical type of data to your space domain awareness or intelligence workflows. Fill out the form if you are interested in the pack and we'll be in touch.
	form NEI Accelerator Form
		textbox FIRST
		textbox LAST
		textbox COMPANY
		textbox EMAIL, required
		button Request the NEI Accelerator Pack
	contentinfo
		link HEO logo, url='https://www.heospace.com/'
			image HEO logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65c19e62b2de772eb4027354_HEO%20Logo%20Blue-p-500.png'
		link HEO, url='https://www.heospace.com/product#Contact-Us'
		StaticText 477 Pitt Street, Haymarket, NSW, 2000. ABN: 52613142448
		StaticText HEO Robotics (UK)
		StaticText SPACES, Covent Garden, 60 St Martin's Ln, London WC2N 4JS. Company number: 13772543
		StaticText HEO USA
		StaticText 3033 Wilson Blvd #700, Arlington, VA 22201
		StaticText Contact
		link info@heospace.com, url='mailto:info@heospace.com'
		link X logo, url='http://twitter.com/heospace'
			image X logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4ea9b4cf361dc52d1d40_sl_z_072523_61700_01-p-500.jpg'
		link LinkedIn logo, url='https://www.linkedin.com/company/high-earth-orbit-robotics/'
			image LinkedIn logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4cfdeab57aaa39104c52_LinkedIn.svg'
		link YouTube logo, url='https://www.youtube.com/channel/UCeNTo1I7PY8m1AANgzlm-xw'
			image YouTube logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4cf25f1595ba0519536c_YouTube.svg'
		link About, url='https://www.heospace.com/about-us'
		link Product, url='https://www.heospace.com/product'
		link Technology, url='https://www.heospace.com/technology'
		link Partnerships, url='https://www.heospace.com/partnerships'
		link Careers, url='https://www.heospace.com/careers'
		link White Papers, url='https://www.heospace.com/white-papers'
		link Stories, url='https://www.heospace.com/stories'
		link Site Status, url='https://stats.uptimerobot.com/OjOB3H5w66'
		StaticText © 2024 High Earth Orbit Robotics Pty Ltd. All right reserved.
		link Privacy Policy, url='https://www.heospace.com/policy-html'
		link Terms & Conditions, url='https://www.heospace.com/terms-conditions'
		link Responsible Disclosure Policy, url='https://www.heospace.com/responsible-disclosure-policy'
	alert, atomic
		alert, atomic
			[355] button Close, center=(1898,956), inner_text=×
				StaticText ×
			StaticText This website uses cookies
			StaticText This website uses cookies to improve user experience. By using our website you consent to all cookies in accordance with our Cookie Policy.
			[361] link Read The Full Cookie Policy, opens a new window, center=(922,995), inner_text=Read The Full Cookie Policy, url='https://www.heospace.com/policy-html'
			[365] checkbox PERFORMANCE, center=(59,1026), checked='false', contenteditable=True, type=checkbox
			image
			LabelText
				StaticText PERFORMANCE
			[370] button SHOW DETAILS, center=(526,1056), inner_text= SHOW DETAILS
				image
			[369] span, center=(130,1026), inner_text=PERFORMANCE
			[378] button ACCEPT ALL, center=(1411,1007)
			[379] button DECLINE ALL, center=(1709,1007)
```
</details>



```
RootWebArea Technology | HEO, focused, url='https://www.heospace.com/technology'
	banner
		[37] link home, center=(171,36), url='https://www.heospace.com/'
			image HEO Logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/64eea8c2afb4f279139664d1_HEO%20Logo%20White.webp'
		navigation
```
<details><summary>Show more</summary>

```
			[40] link Product, center=(1220,36), url='https://www.heospace.com/product'
			[41] link Technology, center=(1324,36), url='https://www.heospace.com/technology'
			[42] link Partnerships, center=(1443,36), url='https://www.heospace.com/partnerships'
			[44] button Resources, center=(1565,36), expanded=False, hasPopup='menu'
			[71] link About, center=(1658,36), url='https://www.heospace.com/about-us'
			[73] link Contact, center=(1771,36), url='mailto:info@heospace.com'
	heading TECHNOLOGY
	paragraph
		StaticText HIGHLY AUTONOMOUS SOFTWARE MEETS SOPHISTICATED HARDWARE
	heading Software
	paragraph
		StaticText Our resilient space infrastructure offers the highest frequency NEI data available, transforming the way we monitor satellites. Our data, archive, and analytics offer a 360 degree view of spacecraft to ensure the resiliency and security of space assets, and bolster space domain awareness.
	heading Capabilities
	paragraph
		StaticText A suite of custom-built tools delivering continuous awareness and security for satellite constellations.
	tablist, orientation='horizontal'
		tab NEI At Scale, selected=True
		tab Insight Generation, selected=False
		tab 3D Modelling & Simulation, selected=False
	tabpanel NEI At Scale
		paragraph
			StaticText Our advanced software can support hundreds of sensors and expand to meet growing customer demands. We offer both panchromatic and multispectral imaging, capturing individual snapshots or short video sequences.
	heading Hardware
	paragraph
		StaticText Supporting our commitment to make space transparent and sustainable, we leverage third party sensors already in space or host our proprietary Holmes or Adler Imagers on multi-use space vehicles to extend orbital coverage.  Our innovative technology turns single capability satellites into multi-use capability satellites to make the most of their time in orbit without compromising core mission objectives.
	heading HEO NEI Cameras
	tablist, orientation='horizontal'
		tab Holmes, selected=True
		tab Adler, selected=False
	tabpanel Holmes
		paragraph
			StaticText Holmes Imager is the smallest payload currently offered by HEO, developed for in-orbit NEI applications. It achieved TRL 9 on its initial launch in June 2023. Operating as a hosted payload, Holmes captures resolved imagery of space objects as they fly past the host spacecraft.
			StaticText ‍
		StaticText Aperture Size
		StaticText 94 mm
		StaticText Size
		StaticText 274 (L) x 115 (W) x 125 (H) mm
		StaticText Resolution (GSD)
		StaticText 1.7 m at 500km
		image Holmes Imager, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66ebb21aded3a7d1e1679cec_Webflow%20Photos.png'
	contentinfo
		link HEO logo, url='https://www.heospace.com/'
			image HEO logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65c19e62b2de772eb4027354_HEO%20Logo%20Blue-p-500.png'
		link HEO, url='https://www.heospace.com/technology#Contact-Us'
		StaticText 477 Pitt Street, Haymarket, NSW, 2000. ABN: 52613142448
		StaticText HEO Robotics (UK)
		StaticText SPACES, Covent Garden, 60 St Martin's Ln, London WC2N 4JS. Company number: 13772543
		StaticText HEO USA
		StaticText 3033 Wilson Blvd #700, Arlington, VA 22201
		StaticText Contact
		link info@heospace.com, url='mailto:info@heospace.com'
		link X logo, url='http://twitter.com/heospace'
			image X logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4ea9b4cf361dc52d1d40_sl_z_072523_61700_01-p-500.jpg'
		link LinkedIn logo, url='https://www.linkedin.com/company/high-earth-orbit-robotics/'
			image LinkedIn logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4cfdeab57aaa39104c52_LinkedIn.svg'
		link YouTube logo, url='https://www.youtube.com/channel/UCeNTo1I7PY8m1AANgzlm-xw'
			image YouTube logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4cf25f1595ba0519536c_YouTube.svg'
		link About, url='https://www.heospace.com/about-us'
		link Product, url='https://www.heospace.com/product'
		link Technology, url='https://www.heospace.com/technology'
		link Partnerships, url='https://www.heospace.com/partnerships'
		link Careers, url='https://www.heospace.com/careers'
		link White Papers, url='https://www.heospace.com/white-papers'
		link Stories, url='https://www.heospace.com/stories'
		link Site Status, url='https://stats.uptimerobot.com/OjOB3H5w66'
		StaticText © 2024 High Earth Orbit Robotics Pty Ltd. All right reserved.
		link Privacy Policy, url='https://www.heospace.com/policy-html'
		link Terms & Conditions, url='https://www.heospace.com/terms-conditions'
		link Responsible Disclosure Policy, url='https://www.heospace.com/responsible-disclosure-policy'
	alert, atomic
		alert, atomic
			[301] button Close, center=(1898,956), inner_text=×
				StaticText ×
			StaticText This website uses cookies
			StaticText This website uses cookies to improve user experience. By using our website you consent to all cookies in accordance with our Cookie Policy.
			[307] link Read The Full Cookie Policy, opens a new window, center=(922,995), inner_text=Read The Full Cookie Policy, url='https://www.heospace.com/policy-html'
			[311] checkbox PERFORMANCE, center=(59,1026), checked='false', contenteditable=True, type=checkbox
			image
			LabelText
				StaticText PERFORMANCE
			[316] button SHOW DETAILS, center=(526,1056), inner_text= SHOW DETAILS
				image
			[315] span, center=(130,1026), inner_text=PERFORMANCE
			[324] button ACCEPT ALL, center=(1411,1007)
			[325] button DECLINE ALL, center=(1709,1007)
```
</details>

**Reasoning for action:** By clicking on the Technology link, I am changing the current webpage context from the Product page to the Technology page. This is a necessary step to fulfill the user's goal of exploring HEO's technology advancements, which is crucial for understanding how these offerings can benefit their organization.

**Action:** click(40) # Click on the Technology link to explore HEO's technology offerings.

**Change Description:** The browser navigated from the Product page to the Technology page, indicated by a change in the URL to 'https://www.heospace.com/technology' and an update in the heading from 'PRODUCT' to 'TECHNOLOGY', along with new content about HEO's technology offerings.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.heospace.com/technology

https://www.heospace.com/partnerships

**Content (before/after):** 

```
RootWebArea Technology | HEO, focused, url='https://www.heospace.com/technology'
	banner
		[37] link home, center=(171,36), url='https://www.heospace.com/'
			image HEO Logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/64eea8c2afb4f279139664d1_HEO%20Logo%20White.webp'
		navigation
```
<details><summary>Show more</summary>

```
			[40] link Product, center=(1220,36), url='https://www.heospace.com/product'
			[41] link Technology, center=(1324,36), url='https://www.heospace.com/technology'
			[42] link Partnerships, center=(1443,36), url='https://www.heospace.com/partnerships'
			[44] button Resources, center=(1565,36), expanded=False, hasPopup='menu'
			[71] link About, center=(1658,36), url='https://www.heospace.com/about-us'
			[73] link Contact, center=(1771,36), url='mailto:info@heospace.com'
	heading TECHNOLOGY
	paragraph
		StaticText HIGHLY AUTONOMOUS SOFTWARE MEETS SOPHISTICATED HARDWARE
	heading Software
	paragraph
		StaticText Our resilient space infrastructure offers the highest frequency NEI data available, transforming the way we monitor satellites. Our data, archive, and analytics offer a 360 degree view of spacecraft to ensure the resiliency and security of space assets, and bolster space domain awareness.
	heading Capabilities
	paragraph
		StaticText A suite of custom-built tools delivering continuous awareness and security for satellite constellations.
	tablist, orientation='horizontal'
		tab NEI At Scale, selected=True
		tab Insight Generation, selected=False
		tab 3D Modelling & Simulation, selected=False
	tabpanel NEI At Scale
		paragraph
			StaticText Our advanced software can support hundreds of sensors and expand to meet growing customer demands. We offer both panchromatic and multispectral imaging, capturing individual snapshots or short video sequences.
	heading Hardware
	paragraph
		StaticText Supporting our commitment to make space transparent and sustainable, we leverage third party sensors already in space or host our proprietary Holmes or Adler Imagers on multi-use space vehicles to extend orbital coverage.  Our innovative technology turns single capability satellites into multi-use capability satellites to make the most of their time in orbit without compromising core mission objectives.
	heading HEO NEI Cameras
	tablist, orientation='horizontal'
		tab Holmes, selected=True
		tab Adler, selected=False
	tabpanel Holmes
		paragraph
			StaticText Holmes Imager is the smallest payload currently offered by HEO, developed for in-orbit NEI applications. It achieved TRL 9 on its initial launch in June 2023. Operating as a hosted payload, Holmes captures resolved imagery of space objects as they fly past the host spacecraft.
			StaticText ‍
		StaticText Aperture Size
		StaticText 94 mm
		StaticText Size
		StaticText 274 (L) x 115 (W) x 125 (H) mm
		StaticText Resolution (GSD)
		StaticText 1.7 m at 500km
		image Holmes Imager, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66ebb21aded3a7d1e1679cec_Webflow%20Photos.png'
	contentinfo
		link HEO logo, url='https://www.heospace.com/'
			image HEO logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65c19e62b2de772eb4027354_HEO%20Logo%20Blue-p-500.png'
		link HEO, url='https://www.heospace.com/technology#Contact-Us'
		StaticText 477 Pitt Street, Haymarket, NSW, 2000. ABN: 52613142448
		StaticText HEO Robotics (UK)
		StaticText SPACES, Covent Garden, 60 St Martin's Ln, London WC2N 4JS. Company number: 13772543
		StaticText HEO USA
		StaticText 3033 Wilson Blvd #700, Arlington, VA 22201
		StaticText Contact
		link info@heospace.com, url='mailto:info@heospace.com'
		link X logo, url='http://twitter.com/heospace'
			image X logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4ea9b4cf361dc52d1d40_sl_z_072523_61700_01-p-500.jpg'
		link LinkedIn logo, url='https://www.linkedin.com/company/high-earth-orbit-robotics/'
			image LinkedIn logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4cfdeab57aaa39104c52_LinkedIn.svg'
		link YouTube logo, url='https://www.youtube.com/channel/UCeNTo1I7PY8m1AANgzlm-xw'
			image YouTube logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4cf25f1595ba0519536c_YouTube.svg'
		link About, url='https://www.heospace.com/about-us'
		link Product, url='https://www.heospace.com/product'
		link Technology, url='https://www.heospace.com/technology'
		link Partnerships, url='https://www.heospace.com/partnerships'
		link Careers, url='https://www.heospace.com/careers'
		link White Papers, url='https://www.heospace.com/white-papers'
		link Stories, url='https://www.heospace.com/stories'
		link Site Status, url='https://stats.uptimerobot.com/OjOB3H5w66'
		StaticText © 2024 High Earth Orbit Robotics Pty Ltd. All right reserved.
		link Privacy Policy, url='https://www.heospace.com/policy-html'
		link Terms & Conditions, url='https://www.heospace.com/terms-conditions'
		link Responsible Disclosure Policy, url='https://www.heospace.com/responsible-disclosure-policy'
	alert, atomic
		alert, atomic
			[301] button Close, center=(1898,956), inner_text=×
				StaticText ×
			StaticText This website uses cookies
			StaticText This website uses cookies to improve user experience. By using our website you consent to all cookies in accordance with our Cookie Policy.
			[307] link Read The Full Cookie Policy, opens a new window, center=(922,995), inner_text=Read The Full Cookie Policy, url='https://www.heospace.com/policy-html'
			[311] checkbox PERFORMANCE, center=(59,1026), checked='false', contenteditable=True, type=checkbox
			image
			LabelText
				StaticText PERFORMANCE
			[316] button SHOW DETAILS, center=(526,1056), inner_text= SHOW DETAILS
				image
			[315] span, center=(130,1026), inner_text=PERFORMANCE
			[324] button ACCEPT ALL, center=(1411,1007)
			[325] button DECLINE ALL, center=(1709,1007)
```
</details>



```
RootWebArea Partnerships | HEO, focused, url='https://www.heospace.com/partnerships'
	banner
		[37] link home, center=(171,36), url='https://www.heospace.com/'
			image HEO Logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/64eea8c2afb4f279139664d1_HEO%20Logo%20White.webp'
		navigation
```
<details><summary>Show more</summary>

```
			[40] link Product, center=(1220,36), url='https://www.heospace.com/product'
			[41] link Technology, center=(1324,36), url='https://www.heospace.com/technology'
			[42] link Partnerships, center=(1443,36), url='https://www.heospace.com/partnerships'
			[44] button Resources, center=(1565,36), expanded=False, hasPopup='menu'
			[71] link About, center=(1658,36), url='https://www.heospace.com/about-us'
			[73] link Contact, center=(1771,36), url='mailto:info@heospace.com'
	heading BECOME A PARTNER
	paragraph
		StaticText MAKE THE MOST OUT OF YOUR TIME IN ORBIT BY JOINING HEO'S NEI NETWORK
	paragraph
		StaticText Supporting our commitment to space sustainability, we leverage third party sensors in space to extend orbital coverage. With proven success on Earth observation, space logistics and in-space servicing applications, we turn single capability satellites into multi-use capability satellites without compromising core mission objectives. We'll use your sensor during downtime and take care of the entire imaging process.
	image Space machines logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66dfd962e614e00013f17a23_2.svg'
	image Axelspace logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66dfd9620606c81ce481aaa8_6.svg'
	image Satellogic logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66dfd9623570897227bf3999_4.svg'
	image TURION SPACE logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66dfd9627eaf34225c8be4a3_3.svg'
	image Sidus Space logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66dfd962c2c3ab57f32ffec6_5.svg'
	image Impulse Space Propulsion logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66dfd96226377f826a8595d4_1.svg'
	image BlackSky logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66eb6889caa37375fede7050_Web%20logos%20(5).webp'
	heading Current Coverage
	paragraph
		StaticText HEO employs over 40 sensors to provide coverage on objects up to 700 kilometre altitude. We plan to grow our ecosystem to over 1000 sensors across all orbital regimes by 2027, with GEO coverage expected in 2025.
	image Space photo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66ea65956866dabdf7a62139_5.webp'
	heading Fast Track Your Entry Into NEI
	image Satellite icon, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/6594efba6065064afaea2a8a_8.jpg'
	heading Enter NEI Market
	paragraph
		StaticText Fast track your entry into the NEI market and realise additional revenue during satellite downtime.
	image Earth Icon, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/6594efbb96e25a8251920e50_7.jpg'
	heading Space Sustainability
	paragraph
		StaticText Support space sustainability by working with HEO to improve satellite efficiency and effectiveness.
	image Satellite icon, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/6594efba056bb1e5a5e58999_6.jpg'
	heading Focus On Your Mission
	paragraph
		StaticText Our technology integrates with your existing systems without compromising core mission objectives.
	heading Designed To Match Your ConOps
	paragraph
		StaticText HEO can bring standard Earth observation practices into non-Earth imaging (NEI) without any additional engineering. Similar to how Earth observation requests include event-based imaging to image an area at a specific time, we can provide a location on Earth and a set time for NEI. Using your typical pointing and concept of operations, HEO conducts all calculations so that a satellite will be in the frame of the camera at the imaging time.
	image Rocket body over Earth, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66ea6595a94cf8aac69ec000_4.webp'
	image Adler Imager above a photo of the Earth and Moon, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/66ea659570f8e3beacd0a832_6.webp'
	heading Host HEO's NEI Camera
	paragraph
		StaticText HEO is extending our coverage beyond LEO by launching NEI cameras as hosted payloads on third-party spacecraft. Our Holmes Mk2 Imager is the smallest payload currently offered by HEO, developed for in-orbit NEI applications. Adler is HEOs larger payload engineered for exceptional image quality and is the largest commercial camera dedicated to non-Earth imaging. Operating as a hosted payload, our cameras capture resolved imagery of space objects as they fly past your spacecraft.
	heading Let's Talk
	paragraph
		StaticText Consider applying to join our partnerships program if your sensors meet the minimum specifications. Have a spacecraft going to space and need a sensor? Reach out!
	StaticText Pointing Error
	StaticText < 10% of the FOV of the Sensor
	StaticText Imaging Type
	StaticText Snapshot Preferable
	StaticText Telemetry Data
	StaticText Onboard GPS & Sensor Attitude
	StaticText Image Resolution (GSD)
	StaticText <10m/pixel @ 500km
	StaticText Timing Error
	StaticText < 5ms
	StaticText Sensor Tasking
	StaticText Secure API (Optional)
	heading The Most Common Questions
	button Why are partners important? , expanded=False, hasPopup='menu'
		heading Why are partners important?
	navigation Why are partners important? 
		paragraph
			StaticText Part of HEO’s mission is to keep space sustainable. Rather than launching our own assets, we foster collaboration opportunities with companies to access existing space-based sensors when they are not in use, as well as building our own imaging systems which will be integrated onto host spacecraft already going to space to improve HEO’s coverage in LEO and beyond.
	button Why should I partner with HEO? , expanded=False, hasPopup='menu'
		heading Why should I partner with HEO?
	navigation Why should I partner with HEO? 
		paragraph
			StaticText Our partnerships program offers a new revenue stream for our partners by bringing in business when their cameras are not in use. A single company’s imaging system often does not have enough satellites for timely access to data and to maintain a high revisit rate. We add this additional capability to satellites allowing for them to focus on their primary missions while maximising its utilisation.
	button How quickly can HEO onboard an active sensor? , expanded=False, hasPopup='menu'
		heading How quickly can HEO onboard an active sensor?
	navigation How quickly can HEO onboard an active sensor? 
		paragraph
			StaticText If the sensor is commissioned and API ready for tasking, HEO can begin tasking straight away with revenue realised within one to two months.
	button Does my satellite have to point 'up' to complete NEI? , expanded=False, hasPopup='menu'
		heading Does my satellite have to point 'up' to complete NEI?
	navigation Does my satellite have to point 'up' to complete NEI? 
		paragraph
			StaticText We work within the off-nadir restrictions of the satellite. However, increasing the off-nadir angle sees increased revenue potential for the partner.
	contentinfo
		link HEO logo, url='https://www.heospace.com/'
			image HEO logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65c19e62b2de772eb4027354_HEO%20Logo%20Blue-p-500.png'
		link HEO, url='https://www.heospace.com/partnerships#Contact-Us'
		StaticText 477 Pitt Street, Haymarket, NSW, 2000. ABN: 52613142448
		StaticText HEO Robotics (UK)
		StaticText SPACES, Covent Garden, 60 St Martin's Ln, London WC2N 4JS. Company number: 13772543
		StaticText HEO USA
		StaticText 3033 Wilson Blvd #700, Arlington, VA 22201
		StaticText Contact
		link info@heospace.com, url='mailto:info@heospace.com'
		link X logo, url='http://twitter.com/heospace'
			image X logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4ea9b4cf361dc52d1d40_sl_z_072523_61700_01-p-500.jpg'
		link LinkedIn logo, url='https://www.linkedin.com/company/high-earth-orbit-robotics/'
			image LinkedIn logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4cfdeab57aaa39104c52_LinkedIn.svg'
		link YouTube logo, url='https://www.youtube.com/channel/UCeNTo1I7PY8m1AANgzlm-xw'
			image YouTube logo, url='https://cdn.prod.website-files.com/64d991920c82dd47a29baf56/65af4cf25f1595ba0519536c_YouTube.svg'
		link About, url='https://www.heospace.com/about-us'
		link Product, url='https://www.heospace.com/product'
		link Technology, url='https://www.heospace.com/technology'
		link Partnerships, url='https://www.heospace.com/partnerships'
		link Careers, url='https://www.heospace.com/careers'
		link White Papers, url='https://www.heospace.com/white-papers'
		link Stories, url='https://www.heospace.com/stories'
		link Site Status, url='https://stats.uptimerobot.com/OjOB3H5w66'
		StaticText © 2024 High Earth Orbit Robotics Pty Ltd. All right reserved.
		link Privacy Policy, url='https://www.heospace.com/policy-html'
		link Terms & Conditions, url='https://www.heospace.com/terms-conditions'
		link Responsible Disclosure Policy, url='https://www.heospace.com/responsible-disclosure-policy'
	alert, atomic
		alert, atomic
			[370] button Close, center=(1898,956), inner_text=×
				StaticText ×
			StaticText This website uses cookies
			StaticText This website uses cookies to improve user experience. By using our website you consent to all cookies in accordance with our Cookie Policy.
			[376] link Read The Full Cookie Policy, opens a new window, center=(922,995), inner_text=Read The Full Cookie Policy, url='https://www.heospace.com/policy-html'
			[380] checkbox PERFORMANCE, center=(59,1026), checked='false', contenteditable=True, type=checkbox
			image
			LabelText
				StaticText PERFORMANCE
			[385] button SHOW DETAILS, center=(526,1056), inner_text= SHOW DETAILS
				image
			[384] span, center=(130,1026), inner_text=PERFORMANCE
			[393] button ACCEPT ALL, center=(1411,1007)
			[394] button DECLINE ALL, center=(1709,1007)
```
</details>

**Reasoning for action:** Clicking the Partnerships link (element 42) is essential because it directly addresses the user's goal of exploring HEO's partnership opportunities. This action will take me to the relevant page where I can find detailed information about how HEO collaborates with other organizations, which is part of understanding the benefits of HEO's products and collaborations for the user's organization.

**Action:** click(42) # Click on the Partnerships link to explore HEO's partnerships.

**Change Description:** The browser navigated from the 'Technology' page to the 'Partnerships' page, changing the main heading from 'TECHNOLOGY' to 'BECOME A PARTNER' and displaying new content related to HEO's partnerships, including company logos and information about their collaboration program.

**Screenshot before:****Screenshot after:**---


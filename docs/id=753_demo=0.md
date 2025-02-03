# Task

**User Story for Browsing Botox Services**

As a potential patient interested in cosmetic treatments,
I explore Botox providers in New York City,
so that I can compare prices and availability conveniently.

**Success definition:** Given I am on the Certainly Health homepage
When I click on the 'Botox' link and then the 'Search' button for providers in Midtown Manhattan
Then I should see a list of Botox providers along with their pricing and availability options.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://certainlyhealth.com/

https://certainlyhealth.com/

**Content (before/after):** 

```
RootWebArea Book New York City Providers Online with Upfront Prices | Certainly Health, focused, url='https://certainlyhealth.com/'
	navigation
		[70] link Certainly Health logo, center=(105,61), url='https://certainlyhealth.com/'
			image Certainly Health logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/forest-green-certainly.e8f32e088fe6.svg'
		[77] button Browse Down arrow to expand list item, center=(1368,61), inner_text=Browse
```
<details><summary>Show more</summary>

```
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[118] button For Providers Down arrow to expand list item, center=(1510,61), inner_text=For Providers
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[127] button About Down arrow to expand list item, center=(1645,61), inner_text=About
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[155] button Sign Up or Log In, center=(1790,61), inner_text=Sign Up
or
Log In
	heading Book doctors with price transparency
	StaticText Compare providers by guaranteed cost, reviews, and more. No more surprise bills.
	combobox Submit, expanded=False, hasPopup='listbox'
		search
			LabelText Submit
				[423] button Submit, center=(316,463), title=Submit, type=submit
					image
			[428] searchbox Submit, center=(622,463), autocomplete=off, contenteditable=True, type=search
	[439] textbox Neighborhood, city, state, or zip value='New York City', center=(599,519), autocomplete=off, contenteditable=True, type=text
	[441] combobox value='Blue Cross/Blue Shield (any - including Anthem, Empire, etc.)', center=(598,575), contenteditable=True, expanded=False, hasPopup='menu', inner_text=Blue Cross/Blue Shield (any - including Anthem, Empire, etc.)
Aetna (any - including Meritain)
Cigna
United Healthcare (any - including Oxford)
		option Blue Cross/Blue Shield (any - including Anthem, Empire, etc.), selected=True
		option Aetna (any - including Meritain), selected=False
		option Cigna, selected=False
		option United Healthcare (any - including Oxford), selected=False
	[447] button Search, center=(599,631), type=button
	image Hero Image, url='https://damh1px1p5h25.cloudfront.net/hero-img/medical-index-hero-img-lg.f5e6ff2b4bb2.svg'
	image Y Combinator Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/y_combinator.c111b91c6277.svg'
	image Forbes Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/forbes.bdd5d178ecdd.svg'
	image Fierce Healthcare Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/fierce_healthcare.da3ac887118f.svg'
	image Women's Wear Daily Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/WWD.3048e7b2f2b0.svg'
	image Fortune Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/fortune.f12a6c899392.svg'
	image Yahoo News Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/yahoo_news.6d5a33a3a136.svg'
	heading Popular Services
	heading Medical
	[471] link Icon for OBGYN OBGYN, center=(787,1009), inner_text=OBGYN, url='https://certainlyhealth.com/obgyn/nyc-ny/new-york?sort_by=Recommended'
		image Icon for OBGYN, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/OBGYN.fcaa1c495827.svg'
	[477] link Icon for Dermatologist Dermatologist, center=(960,1009), inner_text=Dermatologist, url='https://certainlyhealth.com/dermatologist/nyc-ny/new-york?sort_by=Recommended'
		image Icon for Dermatologist, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/dermatologist.05605b29064d.svg'
	[483] link Icon for Physical Therapist Physical Therapist, center=(1133,1009), inner_text=Physical Therapist, url='https://certainlyhealth.com/physical-therapist/nyc-ny/new-york?sort_by=Recommended'
		image Icon for Physical Therapist, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/physical-therapy.eb1ff30f87b2.svg'
	heading Cosmetic
	link Icon for Botox Botox, url='https://certainlyhealth.com/#'
		image Icon for Botox, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/botox.3aca9a3c8fa9.svg'
	link Icon for Microneedling Microneedling, url='https://certainlyhealth.com/treatment/microneedling/nyc-ny/new-york?sort_by=Recommended'
		image Icon for Microneedling, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/microneedling.ea1403b6309a.svg'
	link Icon for Filler Filler, url='https://certainlyhealth.com/#'
		image Icon for Filler, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/filler.4ed87cea816b.svg'
	heading How it works
	heading 1.
	StaticText Compare upfront prices
	StaticText Medical
	StaticText We use your specific insurance information to generate guaranteed out-of-pocket costs across all providers.
	StaticText Cosmetic
	StaticText No need to call around and ask about pricing. We've done the work for New Yorkers.
	image, url='https://damh1px1p5h25.cloudfront.net/index-doctor-pfp/parvina-ibragimova-pfp.3a8b7cd5fc78.png'
	StaticText Parvina Ibragimova, NP
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/white-star-filled.ce4bfa16648e.svg'
	StaticText 5.00
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/location-pin-hollow.15d688013842.svg'
	StaticText 0.2 mi
	StaticText Often up to
	StaticText $180
	image, url='https://damh1px1p5h25.cloudfront.net/index-doctor-pfp/hector-rodriguez-pfp.8655d202dbe7.png'
	StaticText Dr. Hector Rodriguez Navarro
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/white-star-filled.ce4bfa16648e.svg'
	StaticText 4.81
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/location-pin-hollow.15d688013842.svg'
	StaticText 1.5 mi
	StaticText Often up to
	StaticText $210
	image, url='https://damh1px1p5h25.cloudfront.net/index-doctor-pfp/philip-roux-lough-pfp.e8053cf090d3.png'
	StaticText Dr. Philip Roux-Lough
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/white-star-filled.ce4bfa16648e.svg'
	StaticText 4.54
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/location-pin-hollow.15d688013842.svg'
	StaticText 2.3 mi
	StaticText Often up to
	StaticText $250
	image Booking Example, url='https://damh1px1p5h25.cloudfront.net/dr-philip-book-example-card.3583ebeca9a1.png'
	heading 2.
	StaticText Book with Certainly
	StaticText Medical
	StaticText We ensure you never pay more than the prices listed for medical services in the
	link Certainly Price Protection, url='https://certainlyhealth.com/faq#faq_question_what-is-certainly-price-protection'
	StaticText package.
	StaticText Cosmetic
	StaticText No need to call around and ask about pricing. We've done the work for New Yorkers.
	image stars, url='https://damh1px1p5h25.cloudfront.net/stars.e79ba85f890d.svg'
	StaticText "I couldnt find a dermatologist with pricing and availability anywhere but Certainly had it all one in one place. Thank you for bringing price transparency to healthcare!"
	StaticText Elsie Alvarez
	list
		listitem
		listitem
		listitem
	image Medical provider, url='https://damh1px1p5h25.cloudfront.net/medical_provider_at_keyboard.3ee2c209e47f.png'
	StaticText Are you a provider interested in partnering with Certainly?
	StaticText Get new patients who always pay 100% of their deductible and coinsurance without any hassle!
	button Learn more
	heading Search by NYC boroughs
	button New York Down arrow to expand faq question, expanded=False
		heading New York
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Westchester Down arrow to expand faq question, expanded=False
		heading Westchester
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Queens Down arrow to expand faq question, expanded=False
		heading Queens
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Staten Island Down arrow to expand faq question, expanded=False
		heading Staten Island
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Brooklyn Down arrow to expand faq question, expanded=False
		heading Brooklyn
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Bronx Down arrow to expand faq question, expanded=False
		heading Bronx
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	link About, url='https://certainlyhealth.com/about'
	link Blog, url='https://certainlyhealth.com/blog'
	link FAQ, url='https://certainlyhealth.com/faq'
	link Privacy Policy, url='https://certainlyhealth.com/privacy'
	link Terms of Service, url='https://certainlyhealth.com/tos'
	link Sitemap, url='https://certainlyhealth.com/sitemap'
	StaticText support@certainlyhealth.com
	StaticText (646) 820-8619
	StaticText 169 Madison Ave #2665, New York, NY 10016
	link certainly facebook, url='https://www.facebook.com/certainlyhealth/'
		image certainly facebook, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c3067d18a79e4686f01fd_Facebook%20-%20White.png'
	link certainly instagram, url='https://www.instagram.com/certainlyhealth'
		image certainly instagram, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c34b38a1050afefe1df88_Instagram%20-%20White.png'
	link certainly linkedin, url='https://www.linkedin.com/company/certainly-health/'
		image certainly linkedin, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c30a456c2d7406b9922b9_LinkedIn%20-%20White.png'
	link certainly twitter, url='https://twitter.com/CertainlyHealth'
		image certainly twitter, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c30af1425c399828fbba0_Twitter%20-%20White.png'
	link certainly tiktok, url='https://www.tiktok.com/@certainlyhealth'
		image certainly tiktok, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c31a5ffb8755668db6a94_TikTok%20-%20White.png'
	image Certainly Health, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/64d48ca5ae1dd707569ffef9_forest-green-certainly.svg'
	StaticText Certainly Health, Inc.
```
</details>



```
RootWebArea Book New York City Providers Online with Upfront Prices | Certainly Health, focused, url='https://certainlyhealth.com/'
	navigation
		[70] link Certainly Health logo, center=(105,61), url='https://certainlyhealth.com/'
			image Certainly Health logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/forest-green-certainly.e8f32e088fe6.svg'
		[77] button Browse Down arrow to expand list item, center=(1368,61), inner_text=Browse
```
<details><summary>Show more</summary>

```
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[83] link Cosmetic, center=(1362,123), url='https://certainlyhealth.com/#'
		[84] link Medical, center=(1449,123), url='https://certainlyhealth.com/#'
		[88] link Botox, center=(1391,168), url='https://certainlyhealth.com/treatment/botox/nyc-ny/new-york'
		[89] link Masseter Botox, center=(1391,206), url='https://certainlyhealth.com/treatment/masseter-botox/nyc-ny/new-york'
		[90] link Botox for Sweating (Hyperhidrosis), center=(1391,256), url='https://certainlyhealth.com/treatment/botox-sweating/nyc-ny/new-york'
		[91] link Fillers, center=(1391,305), url='https://certainlyhealth.com/treatment/fillers/nyc-ny/new-york'
		[92] link Microneedling, center=(1391,344), url='https://certainlyhealth.com/treatment/microneedling/nyc-ny/new-york'
		[93] link Medspas, center=(1391,382), url='https://certainlyhealth.com/medspa/nyc-ny/new-york'
		[118] button For Providers Down arrow to expand list item, center=(1510,61), inner_text=For Providers
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[127] button About Down arrow to expand list item, center=(1645,61), inner_text=About
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[155] button Sign Up or Log In, center=(1790,61), inner_text=Sign Up
or
Log In
	heading Book doctors with price transparency
	StaticText Compare providers by guaranteed cost, reviews, and more. No more surprise bills.
	combobox Submit, expanded=False, hasPopup='listbox'
		search
			LabelText Submit
				[423] button Submit, center=(316,463), title=Submit, type=submit
					image
			[428] searchbox Submit, center=(622,463), autocomplete=off, contenteditable=True, type=search
	[439] textbox Neighborhood, city, state, or zip value='New York City', center=(599,519), autocomplete=off, contenteditable=True, type=text
	[441] combobox value='Blue Cross/Blue Shield (any - including Anthem, Empire, etc.)', center=(598,575), contenteditable=True, expanded=False, hasPopup='menu', inner_text=Blue Cross/Blue Shield (any - including Anthem, Empire, etc.)
Aetna (any - including Meritain)
Cigna
United Healthcare (any - including Oxford)
		option Blue Cross/Blue Shield (any - including Anthem, Empire, etc.), selected=True
		option Aetna (any - including Meritain), selected=False
		option Cigna, selected=False
		option United Healthcare (any - including Oxford), selected=False
	[447] button Search, center=(599,631), type=button
	image Hero Image, url='https://damh1px1p5h25.cloudfront.net/hero-img/medical-index-hero-img-lg.f5e6ff2b4bb2.svg'
	image Y Combinator Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/y_combinator.c111b91c6277.svg'
	image Forbes Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/forbes.bdd5d178ecdd.svg'
	image Fierce Healthcare Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/fierce_healthcare.da3ac887118f.svg'
	image Women's Wear Daily Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/WWD.3048e7b2f2b0.svg'
	image Fortune Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/fortune.f12a6c899392.svg'
	image Yahoo News Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/yahoo_news.6d5a33a3a136.svg'
	heading Popular Services
	heading Medical
	[471] link Icon for OBGYN OBGYN, center=(787,1009), inner_text=OBGYN, url='https://certainlyhealth.com/obgyn/nyc-ny/new-york?sort_by=Recommended'
		image Icon for OBGYN, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/OBGYN.fcaa1c495827.svg'
	[477] link Icon for Dermatologist Dermatologist, center=(960,1009), inner_text=Dermatologist, url='https://certainlyhealth.com/dermatologist/nyc-ny/new-york?sort_by=Recommended'
		image Icon for Dermatologist, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/dermatologist.05605b29064d.svg'
	[483] link Icon for Physical Therapist Physical Therapist, center=(1133,1009), inner_text=Physical Therapist, url='https://certainlyhealth.com/physical-therapist/nyc-ny/new-york?sort_by=Recommended'
		image Icon for Physical Therapist, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/physical-therapy.eb1ff30f87b2.svg'
	heading Cosmetic
	link Icon for Botox Botox, url='https://certainlyhealth.com/#'
		image Icon for Botox, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/botox.3aca9a3c8fa9.svg'
	link Icon for Microneedling Microneedling, url='https://certainlyhealth.com/treatment/microneedling/nyc-ny/new-york?sort_by=Recommended'
		image Icon for Microneedling, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/microneedling.ea1403b6309a.svg'
	link Icon for Filler Filler, url='https://certainlyhealth.com/#'
		image Icon for Filler, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/filler.4ed87cea816b.svg'
	heading How it works
	heading 1.
	StaticText Compare upfront prices
	StaticText Medical
	StaticText We use your specific insurance information to generate guaranteed out-of-pocket costs across all providers.
	StaticText Cosmetic
	StaticText No need to call around and ask about pricing. We've done the work for New Yorkers.
	image, url='https://damh1px1p5h25.cloudfront.net/index-doctor-pfp/parvina-ibragimova-pfp.3a8b7cd5fc78.png'
	StaticText Parvina Ibragimova, NP
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/white-star-filled.ce4bfa16648e.svg'
	StaticText 5.00
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/location-pin-hollow.15d688013842.svg'
	StaticText 0.2 mi
	StaticText Often up to
	StaticText $180
	image, url='https://damh1px1p5h25.cloudfront.net/index-doctor-pfp/hector-rodriguez-pfp.8655d202dbe7.png'
	StaticText Dr. Hector Rodriguez Navarro
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/white-star-filled.ce4bfa16648e.svg'
	StaticText 4.81
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/location-pin-hollow.15d688013842.svg'
	StaticText 1.5 mi
	StaticText Often up to
	StaticText $210
	image, url='https://damh1px1p5h25.cloudfront.net/index-doctor-pfp/philip-roux-lough-pfp.e8053cf090d3.png'
	StaticText Dr. Philip Roux-Lough
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/white-star-filled.ce4bfa16648e.svg'
	StaticText 4.54
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/location-pin-hollow.15d688013842.svg'
	StaticText 2.3 mi
	StaticText Often up to
	StaticText $250
	image Booking Example, url='https://damh1px1p5h25.cloudfront.net/dr-philip-book-example-card.3583ebeca9a1.png'
	heading 2.
	StaticText Book with Certainly
	StaticText Medical
	StaticText We ensure you never pay more than the prices listed for medical services in the
	link Certainly Price Protection, url='https://certainlyhealth.com/faq#faq_question_what-is-certainly-price-protection'
	StaticText package.
	StaticText Cosmetic
	StaticText No need to call around and ask about pricing. We've done the work for New Yorkers.
	image stars, url='https://damh1px1p5h25.cloudfront.net/stars.e79ba85f890d.svg'
	StaticText "I couldnt find a dermatologist with pricing and availability anywhere but Certainly had it all one in one place. Thank you for bringing price transparency to healthcare!"
	StaticText Elsie Alvarez
	list
		listitem
		listitem
		listitem
	image Medical provider, url='https://damh1px1p5h25.cloudfront.net/medical_provider_at_keyboard.3ee2c209e47f.png'
	StaticText Are you a provider interested in partnering with Certainly?
	StaticText Get new patients who always pay 100% of their deductible and coinsurance without any hassle!
	button Learn more
	heading Search by NYC boroughs
	button New York Down arrow to expand faq question, expanded=False
		heading New York
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Westchester Down arrow to expand faq question, expanded=False
		heading Westchester
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Queens Down arrow to expand faq question, expanded=False
		heading Queens
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Staten Island Down arrow to expand faq question, expanded=False
		heading Staten Island
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Brooklyn Down arrow to expand faq question, expanded=False
		heading Brooklyn
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Bronx Down arrow to expand faq question, expanded=False
		heading Bronx
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	link About, url='https://certainlyhealth.com/about'
	link Blog, url='https://certainlyhealth.com/blog'
	link FAQ, url='https://certainlyhealth.com/faq'
	link Privacy Policy, url='https://certainlyhealth.com/privacy'
	link Terms of Service, url='https://certainlyhealth.com/tos'
	link Sitemap, url='https://certainlyhealth.com/sitemap'
	StaticText support@certainlyhealth.com
	StaticText (646) 820-8619
	StaticText 169 Madison Ave #2665, New York, NY 10016
	link certainly facebook, url='https://www.facebook.com/certainlyhealth/'
		image certainly facebook, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c3067d18a79e4686f01fd_Facebook%20-%20White.png'
	link certainly instagram, url='https://www.instagram.com/certainlyhealth'
		image certainly instagram, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c34b38a1050afefe1df88_Instagram%20-%20White.png'
	link certainly linkedin, url='https://www.linkedin.com/company/certainly-health/'
		image certainly linkedin, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c30a456c2d7406b9922b9_LinkedIn%20-%20White.png'
	link certainly twitter, url='https://twitter.com/CertainlyHealth'
		image certainly twitter, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c30af1425c399828fbba0_Twitter%20-%20White.png'
	link certainly tiktok, url='https://www.tiktok.com/@certainlyhealth'
		image certainly tiktok, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c31a5ffb8755668db6a94_TikTok%20-%20White.png'
	image Certainly Health, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/64d48ca5ae1dd707569ffef9_forest-green-certainly.svg'
	StaticText Certainly Health, Inc.
```
</details>

**Reasoning for action:** By clicking on the 'Browse' button, I unlock the menu that likely contains categories for different medical services, including 'Botox'. This will lead me closer to finding the specific link for Botox providers in New York City, fulfilling the user's intention to compare prices and availability.

**Action:** click(77) # Click on the 'Browse' button to explore available services.

**Change Description:** After clicking the 'Browse' button, a new expanded list of service categories appeared, including links to Cosmetic treatments like Botox, Fillers, and Microneedling, along with Medical services, enhancing the navigation options available to the user.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://certainlyhealth.com/

https://certainlyhealth.com/treatment/botox/nyc-ny/new-york

**Content (before/after):** 

```
RootWebArea Book New York City Providers Online with Upfront Prices | Certainly Health, focused, url='https://certainlyhealth.com/'
	navigation
		[70] link Certainly Health logo, center=(105,61), url='https://certainlyhealth.com/'
			image Certainly Health logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/forest-green-certainly.e8f32e088fe6.svg'
		[77] button Browse Down arrow to expand list item, center=(1368,61), inner_text=Browse
```
<details><summary>Show more</summary>

```
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[83] link Cosmetic, center=(1362,123), url='https://certainlyhealth.com/#'
		[84] link Medical, center=(1449,123), url='https://certainlyhealth.com/#'
		[88] link Botox, center=(1391,168), url='https://certainlyhealth.com/treatment/botox/nyc-ny/new-york'
		[89] link Masseter Botox, center=(1391,206), url='https://certainlyhealth.com/treatment/masseter-botox/nyc-ny/new-york'
		[90] link Botox for Sweating (Hyperhidrosis), center=(1391,256), url='https://certainlyhealth.com/treatment/botox-sweating/nyc-ny/new-york'
		[91] link Fillers, center=(1391,305), url='https://certainlyhealth.com/treatment/fillers/nyc-ny/new-york'
		[92] link Microneedling, center=(1391,344), url='https://certainlyhealth.com/treatment/microneedling/nyc-ny/new-york'
		[93] link Medspas, center=(1391,382), url='https://certainlyhealth.com/medspa/nyc-ny/new-york'
		[118] button For Providers Down arrow to expand list item, center=(1510,61), inner_text=For Providers
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[127] button About Down arrow to expand list item, center=(1645,61), inner_text=About
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[155] button Sign Up or Log In, center=(1790,61), inner_text=Sign Up
or
Log In
	heading Book doctors with price transparency
	StaticText Compare providers by guaranteed cost, reviews, and more. No more surprise bills.
	combobox Submit, expanded=False, hasPopup='listbox'
		search
			LabelText Submit
				[423] button Submit, center=(316,463), title=Submit, type=submit
					image
			[428] searchbox Submit, center=(622,463), autocomplete=off, contenteditable=True, type=search
	[439] textbox Neighborhood, city, state, or zip value='New York City', center=(599,519), autocomplete=off, contenteditable=True, type=text
	[441] combobox value='Blue Cross/Blue Shield (any - including Anthem, Empire, etc.)', center=(598,575), contenteditable=True, expanded=False, hasPopup='menu', inner_text=Blue Cross/Blue Shield (any - including Anthem, Empire, etc.)
Aetna (any - including Meritain)
Cigna
United Healthcare (any - including Oxford)
		option Blue Cross/Blue Shield (any - including Anthem, Empire, etc.), selected=True
		option Aetna (any - including Meritain), selected=False
		option Cigna, selected=False
		option United Healthcare (any - including Oxford), selected=False
	[447] button Search, center=(599,631), type=button
	image Hero Image, url='https://damh1px1p5h25.cloudfront.net/hero-img/medical-index-hero-img-lg.f5e6ff2b4bb2.svg'
	image Y Combinator Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/y_combinator.c111b91c6277.svg'
	image Forbes Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/forbes.bdd5d178ecdd.svg'
	image Fierce Healthcare Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/fierce_healthcare.da3ac887118f.svg'
	image Women's Wear Daily Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/WWD.3048e7b2f2b0.svg'
	image Fortune Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/fortune.f12a6c899392.svg'
	image Yahoo News Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/yahoo_news.6d5a33a3a136.svg'
	heading Popular Services
	heading Medical
	[471] link Icon for OBGYN OBGYN, center=(787,1009), inner_text=OBGYN, url='https://certainlyhealth.com/obgyn/nyc-ny/new-york?sort_by=Recommended'
		image Icon for OBGYN, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/OBGYN.fcaa1c495827.svg'
	[477] link Icon for Dermatologist Dermatologist, center=(960,1009), inner_text=Dermatologist, url='https://certainlyhealth.com/dermatologist/nyc-ny/new-york?sort_by=Recommended'
		image Icon for Dermatologist, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/dermatologist.05605b29064d.svg'
	[483] link Icon for Physical Therapist Physical Therapist, center=(1133,1009), inner_text=Physical Therapist, url='https://certainlyhealth.com/physical-therapist/nyc-ny/new-york?sort_by=Recommended'
		image Icon for Physical Therapist, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/physical-therapy.eb1ff30f87b2.svg'
	heading Cosmetic
	link Icon for Botox Botox, url='https://certainlyhealth.com/#'
		image Icon for Botox, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/botox.3aca9a3c8fa9.svg'
	link Icon for Microneedling Microneedling, url='https://certainlyhealth.com/treatment/microneedling/nyc-ny/new-york?sort_by=Recommended'
		image Icon for Microneedling, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/microneedling.ea1403b6309a.svg'
	link Icon for Filler Filler, url='https://certainlyhealth.com/#'
		image Icon for Filler, url='https://damh1px1p5h25.cloudfront.net/svg-icons/popular-services-icons/filler.4ed87cea816b.svg'
	heading How it works
	heading 1.
	StaticText Compare upfront prices
	StaticText Medical
	StaticText We use your specific insurance information to generate guaranteed out-of-pocket costs across all providers.
	StaticText Cosmetic
	StaticText No need to call around and ask about pricing. We've done the work for New Yorkers.
	image, url='https://damh1px1p5h25.cloudfront.net/index-doctor-pfp/parvina-ibragimova-pfp.3a8b7cd5fc78.png'
	StaticText Parvina Ibragimova, NP
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/white-star-filled.ce4bfa16648e.svg'
	StaticText 5.00
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/location-pin-hollow.15d688013842.svg'
	StaticText 0.2 mi
	StaticText Often up to
	StaticText $180
	image, url='https://damh1px1p5h25.cloudfront.net/index-doctor-pfp/hector-rodriguez-pfp.8655d202dbe7.png'
	StaticText Dr. Hector Rodriguez Navarro
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/white-star-filled.ce4bfa16648e.svg'
	StaticText 4.81
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/location-pin-hollow.15d688013842.svg'
	StaticText 1.5 mi
	StaticText Often up to
	StaticText $210
	image, url='https://damh1px1p5h25.cloudfront.net/index-doctor-pfp/philip-roux-lough-pfp.e8053cf090d3.png'
	StaticText Dr. Philip Roux-Lough
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/white-star-filled.ce4bfa16648e.svg'
	StaticText 4.54
	image, url='https://damh1px1p5h25.cloudfront.net/svg-icons/location-pin-hollow.15d688013842.svg'
	StaticText 2.3 mi
	StaticText Often up to
	StaticText $250
	image Booking Example, url='https://damh1px1p5h25.cloudfront.net/dr-philip-book-example-card.3583ebeca9a1.png'
	heading 2.
	StaticText Book with Certainly
	StaticText Medical
	StaticText We ensure you never pay more than the prices listed for medical services in the
	link Certainly Price Protection, url='https://certainlyhealth.com/faq#faq_question_what-is-certainly-price-protection'
	StaticText package.
	StaticText Cosmetic
	StaticText No need to call around and ask about pricing. We've done the work for New Yorkers.
	image stars, url='https://damh1px1p5h25.cloudfront.net/stars.e79ba85f890d.svg'
	StaticText "I couldnt find a dermatologist with pricing and availability anywhere but Certainly had it all one in one place. Thank you for bringing price transparency to healthcare!"
	StaticText Elsie Alvarez
	list
		listitem
		listitem
		listitem
	image Medical provider, url='https://damh1px1p5h25.cloudfront.net/medical_provider_at_keyboard.3ee2c209e47f.png'
	StaticText Are you a provider interested in partnering with Certainly?
	StaticText Get new patients who always pay 100% of their deductible and coinsurance without any hassle!
	button Learn more
	heading Search by NYC boroughs
	button New York Down arrow to expand faq question, expanded=False
		heading New York
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Westchester Down arrow to expand faq question, expanded=False
		heading Westchester
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Queens Down arrow to expand faq question, expanded=False
		heading Queens
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Staten Island Down arrow to expand faq question, expanded=False
		heading Staten Island
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Brooklyn Down arrow to expand faq question, expanded=False
		heading Brooklyn
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Bronx Down arrow to expand faq question, expanded=False
		heading Bronx
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	link About, url='https://certainlyhealth.com/about'
	link Blog, url='https://certainlyhealth.com/blog'
	link FAQ, url='https://certainlyhealth.com/faq'
	link Privacy Policy, url='https://certainlyhealth.com/privacy'
	link Terms of Service, url='https://certainlyhealth.com/tos'
	link Sitemap, url='https://certainlyhealth.com/sitemap'
	StaticText support@certainlyhealth.com
	StaticText (646) 820-8619
	StaticText 169 Madison Ave #2665, New York, NY 10016
	link certainly facebook, url='https://www.facebook.com/certainlyhealth/'
		image certainly facebook, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c3067d18a79e4686f01fd_Facebook%20-%20White.png'
	link certainly instagram, url='https://www.instagram.com/certainlyhealth'
		image certainly instagram, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c34b38a1050afefe1df88_Instagram%20-%20White.png'
	link certainly linkedin, url='https://www.linkedin.com/company/certainly-health/'
		image certainly linkedin, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c30a456c2d7406b9922b9_LinkedIn%20-%20White.png'
	link certainly twitter, url='https://twitter.com/CertainlyHealth'
		image certainly twitter, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c30af1425c399828fbba0_Twitter%20-%20White.png'
	link certainly tiktok, url='https://www.tiktok.com/@certainlyhealth'
		image certainly tiktok, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c31a5ffb8755668db6a94_TikTok%20-%20White.png'
	image Certainly Health, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/64d48ca5ae1dd707569ffef9_forest-green-certainly.svg'
	StaticText Certainly Health, Inc.
```
</details>



```
RootWebArea Botox NYC | Best Botox Near Me | Certainly Health, focused, url='https://certainlyhealth.com/treatment/botox/nyc-ny/new-york'
	navigation
		[75] link Certainly Health logo, center=(105,61), url='https://certainlyhealth.com/cosmetic'
			image Certainly Health logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/forest-green-certainly.e8f32e088fe6.svg'
		[82] button Browse Down arrow to expand list item, center=(1368,61), inner_text=Browse
```
<details><summary>Show more</summary>

```
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[128] button For Providers Down arrow to expand list item, center=(1510,61), inner_text=For Providers
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[137] button About Down arrow to expand list item, center=(1645,61), inner_text=About
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[165] button Sign Up or Log In, center=(1790,61), inner_text=Sign Up
or
Log In
	banner
		heading Botox in NYC. Book an appointment for the best Botox treatment in New York City
		StaticText Compare prices and reviews for Botox across doctors all in one place
		image Provider search engine results, url='https://damh1px1p5h25.cloudfront.net/cosmetic-header.3fabfa021d47.webp'
		combobox Submit, expanded=False, hasPopup='listbox'
			search
				LabelText Submit
					[432] button Submit, center=(316,587), title=Submit, type=submit
						image
				[437] searchbox Submit value='Botox', center=(612,587), autocomplete=off, contenteditable=True, type=search
				[439] button Clear, center=(907,587), title=Clear, type=reset
					image
		[449] textbox Neighborhood, city, state, or zip value='Midtown Manhattan, NY', center=(611,643), autocomplete=off, contenteditable=True, type=text
		[451] button Search, center=(611,699), type=button
	image Y Combinator Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/y_combinator.c111b91c6277.svg'
	image Forbes Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/forbes.bdd5d178ecdd.svg'
	image Fierce Healthcare Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/fierce_healthcare.da3ac887118f.svg'
	image Women's Wear Daily Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/WWD.3048e7b2f2b0.svg'
	image Fortune Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/fortune.f12a6c899392.svg'
	image Yahoo News Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/yahoo_news.6d5a33a3a136.svg'
	image Makeup artist, url='https://damh1px1p5h25.cloudfront.net/injection-2.8998156d2ede.svg'
	heading How Certainly works
	heading 1. Compare upfront prices for Botox in NYC
	paragraph
		StaticText No need to call around and ask about pricing. We display all pricing, including any free consultations and discounts.
	heading 2. See ratings and reviews for Botox treatment in New York City
	paragraph
		StaticText Read verified reviews for specific treatment areas, across all platforms. In NYC, the average rating for a Botox Treatment is 4.74/5.0.
	heading 3. Book with Certainly for Botox in NYC
	paragraph
		StaticText Choose the best provider for you and book your appointment online. In the last week, 20 patients booked Botox in NYC on Certainly. They paid between $216.00 and $850.00 for care.
	heading Other Botox treatments in NYC
	StaticText Book your
	link Botox for Sweating (Hyperhidrosis) appointment with the best in New York City, url='https://certainlyhealth.com/treatment/botox-sweating/nyc-ny/new-york'
	StaticText Book your
	link Masseter Botox appointment with the best in New York City, url='https://certainlyhealth.com/treatment/masseter-botox/nyc-ny/new-york'
	heading Frequently Asked Questions
	button Why use Certainly Health to book Botox in NYC? Down arrow to expand faq question, expanded=False
		heading Why use Certainly Health to book Botox in NYC?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button What is the average cost for Botox in NYC? Down arrow to expand faq question, expanded=False
		heading What is the average cost for Botox in NYC?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button What kinds of providers offer Botox in NYC? Down arrow to expand faq question, expanded=False
		heading What kinds of providers offer Botox in NYC?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button How does the pricing for Botox in New York City vary by provider type? Down arrow to expand faq question, expanded=False
		heading How does the pricing for Botox in New York City vary by provider type?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button How can I make a same-day appointment with a Botox practitioner in NYC or Manhattan? Down arrow to expand faq question, expanded=False
		heading How can I make a same-day appointment with a Botox practitioner in NYC or Manhattan?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button What neighborhoods in NYC do you serve? Down arrow to expand faq question, expanded=False
		heading What neighborhoods in NYC do you serve?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Getting treatment in NYC Down arrow to expand faq question, expanded=False
		heading Getting treatment in NYC
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Save money on Botox treatments with Upfront, Guaranteed Prices Down arrow to expand faq question, expanded=False
		heading Save money on Botox treatments with Upfront, Guaranteed Prices
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	StaticText Botox reviews for providers in New York, NY
	image Google logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/google_logo_small.9877a71d0ac5.svg'
	StaticText Google review for Dr. Adam Nabatian
	StaticText 5.0
	StaticText (161)
	StaticText Mar 14, 2024
	StaticText •
	StaticText Kerrie Mohr
	StaticText I recently had a Fraxel treatment on my face and chest at Dr. Adam Nabatian's office, and I am beyond thrilled with the results. My skin hasn't looked this good in years! Following the treatment, I experienced a few days of downtime, with my skin being very red and puffy for the first two days. However, it quickly subsided by the third day, leaving me with only minor redness for a week. Impressively, the treatment greatly reduced some scarring I had from injection sites from previous procedures done elsewhere. Dr. Nabatian, along with his medical assistant and office management team, were exceptionally warm and professional throughout the entire process. I tend to get very anxious before undergoing laser procedures, but their wonderful attention and bedside manner eased my anxiety greatly. They made sure I felt comfortable and well-informed at every step. I highly recommend Dr. Nabatian for anyone considering dermatological treatments. The quality of care, combined with the visible results of the treatment, makes this experience truly five-star. Thank you, Dr. Nabatian and team, for such a positive and transformative experience!
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Google logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/google_logo_small.9877a71d0ac5.svg'
	StaticText Google review for Dr. Robin Blum
	StaticText 4.9
	StaticText (120)
	StaticText Dec 27, 2022
	StaticText •
	StaticText Elana Wolloch
	StaticText I always have a positive experience! Melissa and Robin are very helpful, hear my concerns and find a solution. Easy to make appointments and receive refills on prescriptions. 100% worth being an out of network patient for the service and treatment I receive. THANKS!
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Google logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/google_logo_small.9877a71d0ac5.svg'
	StaticText Google review for Andouah Assebian, NP
	StaticText 5.0
	StaticText (64)
	StaticText Apr 24, 2024
	StaticText •
	StaticText Carolina Quinones
	StaticText The second I walked into Derm Artisan I felt a sense of trust and a welcoming energy, Andi was so informative and gentle through out the whole process I hardly felt a thing! My service included Botox focusing a lot on my problem area ( masseter muscle ) helped relax my tense jaw and reduce my teeth grinding while I sleep. With the amazing plus of the facial slimming effect caused by the Botox shrinking the masseter. Love my results! Simply can’t wait for my next visit, will certainly be visiting Derm Artisian for all my filler/tox/treatment needs.
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	list
		listitem
			link How much does Botox cost in NYC in 2024?, url='https://certainlyhealth.com/blog/botox-cost'
				image How much does Botox cost in NYC in 2024?, url='https://assets-global.website-files.com/64e41b9a52e032b704ab4a04/653815675659ddfa98c72727_Untitled%20design%20(12).png'
	list
		listitem
			link January 16, 2024 How much does Botox cost in NYC in 2024? Kevin Chiu Kevin Chiu Co-Founder of Certainly New Yorkers are familiar with needing to pay more for everything, including housing, food, etc. Botox is no different and generally costs more in NYC than other US cities... Read More arrow right, url='https://certainlyhealth.com/blog/botox-cost'
				image Kevin Chiu, url='https://assets-global.website-files.com/64e41b9a52e032b704ab4a04/652738bb0510e4ad4334c27b_kevin.jpeg'
				StaticText Kevin Chiu
				StaticText Co-Founder of Certainly
				StaticText Read More
				image arrow right, url='https://assets-global.website-files.com/64d3cfd2651e615791e4e43c/652740cdf1b45faa9dc34562_arrow-right.png'
	heading Search by NYC boroughs
	button New York Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Westchester Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Manhattan Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Queens Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Staten Island Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Brooklyn Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Bronx Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	navigation breadcrumb
		list
			listitem
				link Certainly Health, url='https://certainlyhealth.com/'
			listitem
				StaticText ›
				link New York, NY Botox, url='https://certainlyhealth.com/treatment/botox/nyc-ny/new-york'
			listitem
				StaticText ›
				StaticText New York
	link About, url='https://certainlyhealth.com/about'
	link Blog, url='https://certainlyhealth.com/blog'
	link FAQ, url='https://certainlyhealth.com/faq'
	link Privacy Policy, url='https://certainlyhealth.com/privacy'
	link Terms of Service, url='https://certainlyhealth.com/tos'
	link Sitemap, url='https://certainlyhealth.com/sitemap'
	StaticText support@certainlyhealth.com
	StaticText (646) 820-8619
	StaticText 169 Madison Ave #2665, New York, NY 10016
	link certainly facebook, url='https://www.facebook.com/certainlyhealth/'
		image certainly facebook, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c3067d18a79e4686f01fd_Facebook%20-%20White.png'
	link certainly instagram, url='https://www.instagram.com/certainlyhealth'
		image certainly instagram, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c34b38a1050afefe1df88_Instagram%20-%20White.png'
	link certainly linkedin, url='https://www.linkedin.com/company/certainly-health/'
		image certainly linkedin, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c30a456c2d7406b9922b9_LinkedIn%20-%20White.png'
	link certainly twitter, url='https://twitter.com/CertainlyHealth'
		image certainly twitter, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c30af1425c399828fbba0_Twitter%20-%20White.png'
	link certainly tiktok, url='https://www.tiktok.com/@certainlyhealth'
		image certainly tiktok, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c31a5ffb8755668db6a94_TikTok%20-%20White.png'
	image Certainly Health, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/64d48ca5ae1dd707569ffef9_forest-green-certainly.svg'
	StaticText Certainly Health, Inc.
```
</details>

**Reasoning for action:** I clicked on the 'Botox' link to take the user to the specific section for Botox treatments. This is an essential first step in fulfilling the user's goal of comparing providers in New York City, as it allows me to access relevant information about Botox services and later search providers in Midtown Manhattan.

**Action:** click(88) # Click on the 'Botox' link to learn more about this treatment.

**Change Description:** The browser navigated from the main Certainly Health site to a specific page dedicated to Botox treatments in New York City, which updated the heading to 'Botox NYC | Best Botox Near Me' and displayed additional information about comparing prices, reviews, and booking options for Botox services.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://certainlyhealth.com/treatment/botox/nyc-ny/new-york

https://certainlyhealth.com/treatment/botox/nyc-ny/new-york

**Content (before/after):** 

```
RootWebArea Botox NYC | Best Botox Near Me | Certainly Health, focused, url='https://certainlyhealth.com/treatment/botox/nyc-ny/new-york'
	navigation
		[75] link Certainly Health logo, center=(105,61), url='https://certainlyhealth.com/cosmetic'
			image Certainly Health logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/forest-green-certainly.e8f32e088fe6.svg'
		[82] button Browse Down arrow to expand list item, center=(1368,61), inner_text=Browse
```
<details><summary>Show more</summary>

```
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[128] button For Providers Down arrow to expand list item, center=(1510,61), inner_text=For Providers
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[137] button About Down arrow to expand list item, center=(1645,61), inner_text=About
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[165] button Sign Up or Log In, center=(1790,61), inner_text=Sign Up
or
Log In
	banner
		heading Botox in NYC. Book an appointment for the best Botox treatment in New York City
		StaticText Compare prices and reviews for Botox across doctors all in one place
		image Provider search engine results, url='https://damh1px1p5h25.cloudfront.net/cosmetic-header.3fabfa021d47.webp'
		combobox Submit, expanded=False, hasPopup='listbox'
			search
				LabelText Submit
					[432] button Submit, center=(316,587), title=Submit, type=submit
						image
				[437] searchbox Submit value='Botox', center=(612,587), autocomplete=off, contenteditable=True, type=search
				[439] button Clear, center=(907,587), title=Clear, type=reset
					image
		[449] textbox Neighborhood, city, state, or zip value='Midtown Manhattan, NY', center=(611,643), autocomplete=off, contenteditable=True, type=text
		[451] button Search, center=(611,699), type=button
	image Y Combinator Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/y_combinator.c111b91c6277.svg'
	image Forbes Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/forbes.bdd5d178ecdd.svg'
	image Fierce Healthcare Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/fierce_healthcare.da3ac887118f.svg'
	image Women's Wear Daily Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/WWD.3048e7b2f2b0.svg'
	image Fortune Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/fortune.f12a6c899392.svg'
	image Yahoo News Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/yahoo_news.6d5a33a3a136.svg'
	image Makeup artist, url='https://damh1px1p5h25.cloudfront.net/injection-2.8998156d2ede.svg'
	heading How Certainly works
	heading 1. Compare upfront prices for Botox in NYC
	paragraph
		StaticText No need to call around and ask about pricing. We display all pricing, including any free consultations and discounts.
	heading 2. See ratings and reviews for Botox treatment in New York City
	paragraph
		StaticText Read verified reviews for specific treatment areas, across all platforms. In NYC, the average rating for a Botox Treatment is 4.74/5.0.
	heading 3. Book with Certainly for Botox in NYC
	paragraph
		StaticText Choose the best provider for you and book your appointment online. In the last week, 20 patients booked Botox in NYC on Certainly. They paid between $216.00 and $850.00 for care.
	heading Other Botox treatments in NYC
	StaticText Book your
	link Botox for Sweating (Hyperhidrosis) appointment with the best in New York City, url='https://certainlyhealth.com/treatment/botox-sweating/nyc-ny/new-york'
	StaticText Book your
	link Masseter Botox appointment with the best in New York City, url='https://certainlyhealth.com/treatment/masseter-botox/nyc-ny/new-york'
	heading Frequently Asked Questions
	button Why use Certainly Health to book Botox in NYC? Down arrow to expand faq question, expanded=False
		heading Why use Certainly Health to book Botox in NYC?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button What is the average cost for Botox in NYC? Down arrow to expand faq question, expanded=False
		heading What is the average cost for Botox in NYC?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button What kinds of providers offer Botox in NYC? Down arrow to expand faq question, expanded=False
		heading What kinds of providers offer Botox in NYC?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button How does the pricing for Botox in New York City vary by provider type? Down arrow to expand faq question, expanded=False
		heading How does the pricing for Botox in New York City vary by provider type?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button How can I make a same-day appointment with a Botox practitioner in NYC or Manhattan? Down arrow to expand faq question, expanded=False
		heading How can I make a same-day appointment with a Botox practitioner in NYC or Manhattan?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button What neighborhoods in NYC do you serve? Down arrow to expand faq question, expanded=False
		heading What neighborhoods in NYC do you serve?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Getting treatment in NYC Down arrow to expand faq question, expanded=False
		heading Getting treatment in NYC
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Save money on Botox treatments with Upfront, Guaranteed Prices Down arrow to expand faq question, expanded=False
		heading Save money on Botox treatments with Upfront, Guaranteed Prices
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	StaticText Botox reviews for providers in New York, NY
	image Google logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/google_logo_small.9877a71d0ac5.svg'
	StaticText Google review for Dr. Adam Nabatian
	StaticText 5.0
	StaticText (161)
	StaticText Mar 14, 2024
	StaticText •
	StaticText Kerrie Mohr
	StaticText I recently had a Fraxel treatment on my face and chest at Dr. Adam Nabatian's office, and I am beyond thrilled with the results. My skin hasn't looked this good in years! Following the treatment, I experienced a few days of downtime, with my skin being very red and puffy for the first two days. However, it quickly subsided by the third day, leaving me with only minor redness for a week. Impressively, the treatment greatly reduced some scarring I had from injection sites from previous procedures done elsewhere. Dr. Nabatian, along with his medical assistant and office management team, were exceptionally warm and professional throughout the entire process. I tend to get very anxious before undergoing laser procedures, but their wonderful attention and bedside manner eased my anxiety greatly. They made sure I felt comfortable and well-informed at every step. I highly recommend Dr. Nabatian for anyone considering dermatological treatments. The quality of care, combined with the visible results of the treatment, makes this experience truly five-star. Thank you, Dr. Nabatian and team, for such a positive and transformative experience!
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Google logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/google_logo_small.9877a71d0ac5.svg'
	StaticText Google review for Dr. Robin Blum
	StaticText 4.9
	StaticText (120)
	StaticText Dec 27, 2022
	StaticText •
	StaticText Elana Wolloch
	StaticText I always have a positive experience! Melissa and Robin are very helpful, hear my concerns and find a solution. Easy to make appointments and receive refills on prescriptions. 100% worth being an out of network patient for the service and treatment I receive. THANKS!
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Google logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/google_logo_small.9877a71d0ac5.svg'
	StaticText Google review for Andouah Assebian, NP
	StaticText 5.0
	StaticText (64)
	StaticText Apr 24, 2024
	StaticText •
	StaticText Carolina Quinones
	StaticText The second I walked into Derm Artisan I felt a sense of trust and a welcoming energy, Andi was so informative and gentle through out the whole process I hardly felt a thing! My service included Botox focusing a lot on my problem area ( masseter muscle ) helped relax my tense jaw and reduce my teeth grinding while I sleep. With the amazing plus of the facial slimming effect caused by the Botox shrinking the masseter. Love my results! Simply can’t wait for my next visit, will certainly be visiting Derm Artisian for all my filler/tox/treatment needs.
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	list
		listitem
			link How much does Botox cost in NYC in 2024?, url='https://certainlyhealth.com/blog/botox-cost'
				image How much does Botox cost in NYC in 2024?, url='https://assets-global.website-files.com/64e41b9a52e032b704ab4a04/653815675659ddfa98c72727_Untitled%20design%20(12).png'
	list
		listitem
			link January 16, 2024 How much does Botox cost in NYC in 2024? Kevin Chiu Kevin Chiu Co-Founder of Certainly New Yorkers are familiar with needing to pay more for everything, including housing, food, etc. Botox is no different and generally costs more in NYC than other US cities... Read More arrow right, url='https://certainlyhealth.com/blog/botox-cost'
				image Kevin Chiu, url='https://assets-global.website-files.com/64e41b9a52e032b704ab4a04/652738bb0510e4ad4334c27b_kevin.jpeg'
				StaticText Kevin Chiu
				StaticText Co-Founder of Certainly
				StaticText Read More
				image arrow right, url='https://assets-global.website-files.com/64d3cfd2651e615791e4e43c/652740cdf1b45faa9dc34562_arrow-right.png'
	heading Search by NYC boroughs
	button New York Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Westchester Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Manhattan Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Queens Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Staten Island Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Brooklyn Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Bronx Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	navigation breadcrumb
		list
			listitem
				link Certainly Health, url='https://certainlyhealth.com/'
			listitem
				StaticText ›
				link New York, NY Botox, url='https://certainlyhealth.com/treatment/botox/nyc-ny/new-york'
			listitem
				StaticText ›
				StaticText New York
	link About, url='https://certainlyhealth.com/about'
	link Blog, url='https://certainlyhealth.com/blog'
	link FAQ, url='https://certainlyhealth.com/faq'
	link Privacy Policy, url='https://certainlyhealth.com/privacy'
	link Terms of Service, url='https://certainlyhealth.com/tos'
	link Sitemap, url='https://certainlyhealth.com/sitemap'
	StaticText support@certainlyhealth.com
	StaticText (646) 820-8619
	StaticText 169 Madison Ave #2665, New York, NY 10016
	link certainly facebook, url='https://www.facebook.com/certainlyhealth/'
		image certainly facebook, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c3067d18a79e4686f01fd_Facebook%20-%20White.png'
	link certainly instagram, url='https://www.instagram.com/certainlyhealth'
		image certainly instagram, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c34b38a1050afefe1df88_Instagram%20-%20White.png'
	link certainly linkedin, url='https://www.linkedin.com/company/certainly-health/'
		image certainly linkedin, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c30a456c2d7406b9922b9_LinkedIn%20-%20White.png'
	link certainly twitter, url='https://twitter.com/CertainlyHealth'
		image certainly twitter, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c30af1425c399828fbba0_Twitter%20-%20White.png'
	link certainly tiktok, url='https://www.tiktok.com/@certainlyhealth'
		image certainly tiktok, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c31a5ffb8755668db6a94_TikTok%20-%20White.png'
	image Certainly Health, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/64d48ca5ae1dd707569ffef9_forest-green-certainly.svg'
	StaticText Certainly Health, Inc.
```
</details>



```
RootWebArea Botox NYC | Best Botox Near Me | Certainly Health, focused, url='https://certainlyhealth.com/treatment/botox/nyc-ny/new-york'
	navigation
		[75] link Certainly Health logo, center=(105,61), url='https://certainlyhealth.com/cosmetic'
			image Certainly Health logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/forest-green-certainly.e8f32e088fe6.svg'
		[82] button Browse Down arrow to expand list item, center=(1368,61), inner_text=Browse
```
<details><summary>Show more</summary>

```
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[128] button For Providers Down arrow to expand list item, center=(1510,61), inner_text=For Providers
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[137] button About Down arrow to expand list item, center=(1645,61), inner_text=About
			image Down arrow to expand list item, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
		[165] button Sign Up or Log In, center=(1790,61), inner_text=Sign Up
or
Log In
	banner
		heading Botox in NYC. Book an appointment for the best Botox treatment in New York City
		StaticText Compare prices and reviews for Botox across doctors all in one place
		image Provider search engine results, url='https://damh1px1p5h25.cloudfront.net/cosmetic-header.3fabfa021d47.webp'
		combobox Submit, expanded=False, hasPopup='listbox'
			search
				LabelText Submit
					[432] button Submit, center=(316,587), title=Submit, type=submit
						image
				[437] searchbox Submit value='Botox', center=(612,587), autocomplete=off, contenteditable=True, type=search
				[439] button Clear, center=(907,587), title=Clear, type=reset
					image
		[449] textbox Neighborhood, city, state, or zip value='Midtown Manhattan, NY', center=(611,643), autocomplete=off, contenteditable=True, focused, type=text
		button Search
	image Y Combinator Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/y_combinator.c111b91c6277.svg'
	image Forbes Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/forbes.bdd5d178ecdd.svg'
	image Fierce Healthcare Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/fierce_healthcare.da3ac887118f.svg'
	image Women's Wear Daily Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/WWD.3048e7b2f2b0.svg'
	image Fortune Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/fortune.f12a6c899392.svg'
	image Yahoo News Logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/as_seen_in/yahoo_news.6d5a33a3a136.svg'
	image Makeup artist, url='https://damh1px1p5h25.cloudfront.net/injection-2.8998156d2ede.svg'
	heading How Certainly works
	heading 1. Compare upfront prices for Botox in NYC
	paragraph
		StaticText No need to call around and ask about pricing. We display all pricing, including any free consultations and discounts.
	heading 2. See ratings and reviews for Botox treatment in New York City
	paragraph
		StaticText Read verified reviews for specific treatment areas, across all platforms. In NYC, the average rating for a Botox Treatment is 4.74/5.0.
	heading 3. Book with Certainly for Botox in NYC
	paragraph
		StaticText Choose the best provider for you and book your appointment online. In the last week, 20 patients booked Botox in NYC on Certainly. They paid between $216.00 and $850.00 for care.
	heading Other Botox treatments in NYC
	StaticText Book your
	link Botox for Sweating (Hyperhidrosis) appointment with the best in New York City, url='https://certainlyhealth.com/treatment/botox-sweating/nyc-ny/new-york'
	StaticText Book your
	link Masseter Botox appointment with the best in New York City, url='https://certainlyhealth.com/treatment/masseter-botox/nyc-ny/new-york'
	heading Frequently Asked Questions
	button Why use Certainly Health to book Botox in NYC? Down arrow to expand faq question, expanded=False
		heading Why use Certainly Health to book Botox in NYC?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button What is the average cost for Botox in NYC? Down arrow to expand faq question, expanded=False
		heading What is the average cost for Botox in NYC?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button What kinds of providers offer Botox in NYC? Down arrow to expand faq question, expanded=False
		heading What kinds of providers offer Botox in NYC?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button How does the pricing for Botox in New York City vary by provider type? Down arrow to expand faq question, expanded=False
		heading How does the pricing for Botox in New York City vary by provider type?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button How can I make a same-day appointment with a Botox practitioner in NYC or Manhattan? Down arrow to expand faq question, expanded=False
		heading How can I make a same-day appointment with a Botox practitioner in NYC or Manhattan?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button What neighborhoods in NYC do you serve? Down arrow to expand faq question, expanded=False
		heading What neighborhoods in NYC do you serve?
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Getting treatment in NYC Down arrow to expand faq question, expanded=False
		heading Getting treatment in NYC
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Save money on Botox treatments with Upfront, Guaranteed Prices Down arrow to expand faq question, expanded=False
		heading Save money on Botox treatments with Upfront, Guaranteed Prices
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	StaticText Botox reviews for providers in New York, NY
	image Google logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/google_logo_small.9877a71d0ac5.svg'
	StaticText Google review for Dr. Adam Nabatian
	StaticText 5.0
	StaticText (161)
	StaticText Mar 14, 2024
	StaticText •
	StaticText Kerrie Mohr
	StaticText I recently had a Fraxel treatment on my face and chest at Dr. Adam Nabatian's office, and I am beyond thrilled with the results. My skin hasn't looked this good in years! Following the treatment, I experienced a few days of downtime, with my skin being very red and puffy for the first two days. However, it quickly subsided by the third day, leaving me with only minor redness for a week. Impressively, the treatment greatly reduced some scarring I had from injection sites from previous procedures done elsewhere. Dr. Nabatian, along with his medical assistant and office management team, were exceptionally warm and professional throughout the entire process. I tend to get very anxious before undergoing laser procedures, but their wonderful attention and bedside manner eased my anxiety greatly. They made sure I felt comfortable and well-informed at every step. I highly recommend Dr. Nabatian for anyone considering dermatological treatments. The quality of care, combined with the visible results of the treatment, makes this experience truly five-star. Thank you, Dr. Nabatian and team, for such a positive and transformative experience!
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Google logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/google_logo_small.9877a71d0ac5.svg'
	StaticText Google review for Dr. Robin Blum
	StaticText 4.9
	StaticText (120)
	StaticText Dec 27, 2022
	StaticText •
	StaticText Elana Wolloch
	StaticText I always have a positive experience! Melissa and Robin are very helpful, hear my concerns and find a solution. Easy to make appointments and receive refills on prescriptions. 100% worth being an out of network patient for the service and treatment I receive. THANKS!
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Google logo, url='https://damh1px1p5h25.cloudfront.net/svg-logos/google_logo_small.9877a71d0ac5.svg'
	StaticText Google review for Andouah Assebian, NP
	StaticText 5.0
	StaticText (64)
	StaticText Apr 24, 2024
	StaticText •
	StaticText Carolina Quinones
	StaticText The second I walked into Derm Artisan I felt a sense of trust and a welcoming energy, Andi was so informative and gentle through out the whole process I hardly felt a thing! My service included Botox focusing a lot on my problem area ( masseter muscle ) helped relax my tense jaw and reduce my teeth grinding while I sleep. With the amazing plus of the facial slimming effect caused by the Botox shrinking the masseter. Love my results! Simply can’t wait for my next visit, will certainly be visiting Derm Artisian for all my filler/tox/treatment needs.
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	image Active Star, url='https://damh1px1p5h25.cloudfront.net/svg-icons/green-star-filled.35c2f4a72332.svg'
	list
		listitem
			link How much does Botox cost in NYC in 2024?, url='https://certainlyhealth.com/blog/botox-cost'
				image How much does Botox cost in NYC in 2024?, url='https://assets-global.website-files.com/64e41b9a52e032b704ab4a04/653815675659ddfa98c72727_Untitled%20design%20(12).png'
	list
		listitem
			link January 16, 2024 How much does Botox cost in NYC in 2024? Kevin Chiu Kevin Chiu Co-Founder of Certainly New Yorkers are familiar with needing to pay more for everything, including housing, food, etc. Botox is no different and generally costs more in NYC than other US cities... Read More arrow right, url='https://certainlyhealth.com/blog/botox-cost'
				image Kevin Chiu, url='https://assets-global.website-files.com/64e41b9a52e032b704ab4a04/652738bb0510e4ad4334c27b_kevin.jpeg'
				StaticText Kevin Chiu
				StaticText Co-Founder of Certainly
				StaticText Read More
				image arrow right, url='https://assets-global.website-files.com/64d3cfd2651e615791e4e43c/652740cdf1b45faa9dc34562_arrow-right.png'
	heading Search by NYC boroughs
	button New York Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Westchester Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Manhattan Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Queens Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Staten Island Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Brooklyn Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	button Bronx Down arrow to expand faq question, expanded=False
		image Down arrow to expand faq question, url='https://damh1px1p5h25.cloudfront.net/faq-down-arrow.af4a53c132f0.svg'
	navigation breadcrumb
		list
			listitem
				link Certainly Health, url='https://certainlyhealth.com/'
			listitem
				StaticText ›
				link New York, NY Botox, url='https://certainlyhealth.com/treatment/botox/nyc-ny/new-york'
			listitem
				StaticText ›
				StaticText New York
	link About, url='https://certainlyhealth.com/about'
	link Blog, url='https://certainlyhealth.com/blog'
	link FAQ, url='https://certainlyhealth.com/faq'
	link Privacy Policy, url='https://certainlyhealth.com/privacy'
	link Terms of Service, url='https://certainlyhealth.com/tos'
	link Sitemap, url='https://certainlyhealth.com/sitemap'
	StaticText support@certainlyhealth.com
	StaticText (646) 820-8619
	StaticText 169 Madison Ave #2665, New York, NY 10016
	link certainly facebook, url='https://www.facebook.com/certainlyhealth/'
		image certainly facebook, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c3067d18a79e4686f01fd_Facebook%20-%20White.png'
	link certainly instagram, url='https://www.instagram.com/certainlyhealth'
		image certainly instagram, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c34b38a1050afefe1df88_Instagram%20-%20White.png'
	link certainly linkedin, url='https://www.linkedin.com/company/certainly-health/'
		image certainly linkedin, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c30a456c2d7406b9922b9_LinkedIn%20-%20White.png'
	link certainly twitter, url='https://twitter.com/CertainlyHealth'
		image certainly twitter, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c30af1425c399828fbba0_Twitter%20-%20White.png'
	link certainly tiktok, url='https://www.tiktok.com/@certainlyhealth'
		image certainly tiktok, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/654c31a5ffb8755668db6a94_TikTok%20-%20White.png'
	image Certainly Health, url='https://cdn.prod.website-files.com/64d3cfd2651e615791e4e43c/64d48ca5ae1dd707569ffef9_forest-green-certainly.svg'
	StaticText Certainly Health, Inc.
	StaticText Midtown Manhattan
	StaticText Manhattan, New York,
	StaticText NY
	StaticText , USA
	StaticText NY
	StaticText PL
	StaticText 3rd Avenue,
	StaticText Manhattan
	StaticText , New York, NY, USA
	StaticText NY
	StaticText U Langone Health
	StaticText 1st Avenue,
	StaticText Manhattan
	StaticText , New York, NY, USA
	StaticText NY
	StaticText C Health + Hospitals / Bellevue.
	StaticText 1st Avenue,
	StaticText Manhattan
	StaticText , New York, NY, USA
	StaticText NY
	StaticText U College of Dentistry
	StaticText East 24th Street,
	StaticText Manhattan
	StaticText , New York, NY, USA
```
</details>

**Reasoning for action:** I clicked on the 'Search' button (identified as (449)) because this is the necessary action to retrieve information about available Botox providers in the specified area of Midtown Manhattan. By doing this, I am effectively progressing towards the user's goal of comparing Botox providers based on their pricing and availability.

**Action:** click(449) # Click on the 'Search' button to find Botox providers in Midtown Manhattan.

**Change Description:** After clicking the 'Search' button, the browser updated to display results for Botox providers specifically located in Midtown Manhattan, NY, indicating a focus on that area for potential treatments.

**Screenshot before:****Screenshot after:**---


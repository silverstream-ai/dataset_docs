# Task

**Explore Karbon's Remittance Solutions and Begin Registration Process**

As a potential customer interested in international payments,
I explore remittance solutions offered by Karbon,
so that I can understand my options and start the registration process for a service that meets my business needs.

**Success definition:** Given I am on the Karbon Business website
When I click on the 'Inward Remittances' link, then on 'Outward Remittances', and finally on the 'Sign Up' link
Then I should see the 'Outward Remittances' page displayed with a focus on competitive rates, and the registration form for Karbon FX should be visible allowing me to enter my work email address.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.karbonbusiness.com/

https://www.karbonbusiness.com/accept-international-payments-india

**Content (before/after):** 

```
RootWebArea Karbon Business, focused, url='https://www.karbonbusiness.com/'
	banner
		[30] link home, center=(175,36), url='https://www.karbonbusiness.com/'
			image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab120e0cd7cc8ed12069_636e120a891dc54ee1e0a891_cropped-Untitled-design-removebg-preview-p-500%201%20(1).png'
		navigation
```
<details><summary>Show more</summary>

```
			[34] link Inward Remittances, center=(694,36), url='https://www.karbonbusiness.com/accept-international-payments-india'
			[35] link Outward Remittances, center=(902,36), url='https://www.karbonbusiness.com/outward-remittance-india'
			[36] link Corporate Card, center=(1092,36), url='https://www.karbonbusiness.com/corporate-prepaid-card-by-karbon'
			[37] link Career, center=(1218,36), url='https://www.karbonbusiness.com/about'
		navigation
			[44] link Login, center=(1640,36), url='http://karbonfx.com/login'
			[45] link Sign Up, center=(1752,36), url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	region carousel
		group 2 of 3
			heading Low-Cost Payment For Importers & Exporters
			paragraph
				StaticText Lowest rate, superior customer service, process 15CB for free
			[68] link Sign Up, center=(896,311), url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
			[69] link Login, center=(1031,311), url='http://karbonfx.com/login'
			image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/67173af49242a150cd959119_c9d41cf0d64511c35a05c128ead4a3f7%201.png'
			image Karbon Forex provides secure transactions, low costs, and responsive services for importers and exporters., url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/6740591826d4df1262f3af8a_Frame%201000001215%20(1).png'
		StaticText Slide 2 of 3.
		[84] button previous slide, center=(40,540)
			image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6827b3e301759d417f_arrow-left-5-svgrepo-com.svg'
		[86] button next slide, center=(1880,540)
			image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6827b3e301759d41a4_right-arrow-svgrepo-com.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb00b_Img_margin-4.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb051_Img_margin-2.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb02b_Img_margin-1.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab707593bf76f89fb082_Img_margin-7.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb048_Img_margin-3.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb044_Img_margin.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fafe9_Img_margin-6.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb04c_Img_margin-5.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab707593bf76f89fb05f_Img_margin-8.svg'
	heading Why Is Karbon The Right Business Payment Solution?
	image Easy Onboarding Process, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab75020e2e650585d77a_insurance-p-500.png'
	StaticText Easy Onboarding
	image Fast Account Opening, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab75020e2e650585d71f_stopwatch-p-500.png'
	StaticText Fast Account Opening
	image Low Fees, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab75020e2e650585d787_price-down-p-500.png'
	StaticText Low Fees
	image Customer Support, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab75020e2e650585d79b_customer-support-p-500.png'
	StaticText Superior Service
	heading Who Is Karbon Built For?
		strong
	tablist, orientation='horizontal'
		tab Freelancers, selected=False
		tab Exporters, selected=False
		tab Importers, selected=False
		tab Startups, selected=True
	tabpanel Startups
		image Startups, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/674441fbfa67d21c2b22e4af_startup%202%20(1)-p-500.png'
		heading Strategic Spending, Serious Savings
		StaticText • High cashback
		StaticText • Card, expense & analytics consolidated
		StaticText • Employee card
		StaticText • Real-time spend monitoring
	Iframe
		RootWebArea Karbon forex, url='https://app.dev.karbonfx.com/onlycalci'
			[a37] article, center=(703,2422)
				StaticText Your Client Pays
			[a44] spinbutton value='100', center=(633,2459)
			combobox, autocomplete='list', hasPopup='listbox'
			[a56] image usd, center=(774,2459), url='https://app.dev.karbonfx.com/assets/usd-D7YqEwsK.svg'
			StaticText USD
			heading ₹85.86
			heading Live FOREX Rate
			heading ₹8,586.00
			[a72] heading Converted Amount, center=(777,2549)
			heading ₹85.86
			heading Our Fees (1%)
			heading ₹0
			[a83] heading Hidden Charges, center=(777,2605)
			[a85] article, center=(703,2672)
				StaticText You’ll receive
			[a87] heading ₹8,500.14, center=(633,2710)
			[a90] image, center=(784,2710), url="data:image/svg+xml,%3csvg%20xmlns:xlink='http://www.w3.org/1999/xlink'%20xmlns='http://www.w3.org/2000/svg'%20width='24'%20height='19'%20viewBox='0%200%2024%2019'%20fill='none'%3e%3crect%20x='0.348267'%20y='0.971069'%20width='23.5391'%20height='17.1193'%20fill='white'/%3e%3cpath%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M0.348267%206.67752H23.8874V0.971069H0.348267V6.67752Z'%20fill='%23FFA44A'/%3e%3cpath%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M0.348267%2018.0904H23.8874V12.384H0.348267V18.0904Z'%20fill='%231A9F0B'/%3e%3cpath%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.1177%2011.2427C13.0463%2011.2427%2013.7991%2010.4762%2013.7991%209.53075C13.7991%208.58528%2013.0463%207.81882%2012.1177%207.81882C11.1891%207.81882%2010.4363%208.58528%2010.4363%209.53075C10.4363%2010.4762%2011.1891%2011.2427%2012.1177%2011.2427Z'%20fill='%23181A93'%20fill-opacity='0.15'/%3e%3cpath%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M14.3597%209.53074C14.3597%2010.7914%2013.356%2011.8133%2012.1179%2011.8133C10.8797%2011.8133%209.87604%2010.7914%209.87604%209.53074C9.87604%208.27011%2010.8797%207.24816%2012.1179%207.24816C13.356%207.24816%2014.3597%208.27011%2014.3597%209.53074ZM13.7992%209.53074C13.7992%2010.4762%2013.0464%2011.2427%2012.1179%2011.2427C11.1893%2011.2427%2010.4365%2010.4762%2010.4365%209.53074C10.4365%208.58527%2011.1893%207.81881%2012.1179%207.81881C13.0464%207.81881%2013.7992%208.58527%2013.7992%209.53074Z'%20fill='%23181A93'/%3e%3cpath%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.1177%2010.1014C12.4272%2010.1014%2012.6781%209.84589%2012.6781%209.53074C12.6781%209.21558%2012.4272%208.96009%2012.1177%208.96009C11.8081%208.96009%2011.5572%209.21558%2011.5572%209.53074C11.5572%209.84589%2011.8081%2010.1014%2012.1177%2010.1014Z'%20fill='%23181A93'/%3e%3c/svg%3e"
			StaticText INR
	heading Karbon FX
	StaticText Cheaper, quicker and easier foreign remittance tool built for Indian businesses
	link Sign Up, url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	link Learn More, url='https://www.karbonbusiness.com/accept-international-payments-india'
	image Karbon Card, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/6718c354bd407f973c927920_Frame%202245.png'
	heading Corporate Card
	StaticText Enjoy substantial cashback, turning everyday purchases into strategic financial moves.
	link Sign Up, url='https://app.karboncard.com/sign-up?_gl=1*1qe4fd*_ga*MTU0OTQyNDQ4NC4xNzMxNTY3MzYy*_ga_36TTY46M1C*MTczMTk5NjczNy4yLjEuMTczMTk5NjczOC41OS4wLjA.'
	link Learn More, url='https://www.karbonbusiness.com/corporate-prepaid-card-by-karbon'
	heading Why Do Users Trust Us?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabacb2b498a901965702_873.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Arun Ramanathan
		strong
	StaticText Karbon has been a great partner for our business. Their platform is user-friendly and we appreciate the transparency they provide throughout the remittance process. We can count on them to deliver our payments on time and with no hidden fees.
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabacb2b498a90196573f_666c158ae76bcbecf52d86a0_Karbon-business-p-130x130q80.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Shankar R
		strong
	StaticText Karbon has been a game changer for our business. We needed a reliable and efficient way to make international payments and Karbon has delivered. Their customer support team is always available to help and we've had no issues with the remittance process. Highly recommended!
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabadb2b498a901965871_121sad.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Aishwarya Nair
		strong
	StaticText Karbon has made our foreign outward remittance process so much simpler. Their platform is easy to use and we can track our transactions in real-time. Plus, their rates are very competitive. We're very happy with their service.
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabadb2b498a90196587a_Untitled-1.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Nidhi Menon
		strong
	StaticText We were looking for a trustworthy foreign outward remittance service and Karbon has exceeded our expectations. Their team is professional and responsive, and they've helped us navigate complex compliance requirements. We now use Karbon for all our international transactions
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196598c_image%2520(7)-p-500.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading YAP
		strong
	StaticText They increased our credit limit within 24 hours. Extremely positive, and I recommend Karbon to all of my friends starting/running companies. Plus, they keep adding new features every few months
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a9019659e2_Frame-12%2520(1)-p-500.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Jupiter
		strong
	StaticText Karbon Payout works best for a startup like ours. Our manual work was reduced drastically with Payout which helped us to focus on core business activities. Kudos to the team for providing an excellent vendor payment service!
	heading Explore All Things Financial, Business And Banking
	link See All Blog Posts, url='https://www.karbonbusiness.com/blog'
	list
		listitem
			link Devendra Mali BUSINESS Comprehensive Guide to External Commercial Borrowings (ECBs) for Indian Businesses, url='https://www.karbonbusiness.com/blog/external-commercial-borrowings'
				image, url='https://cdn.prod.website-files.com/6732ede3c32a0faadbd4a3e8/6752da9aba0a3f5936395e50_external-commercial-borrowings-p-800.png'
				image, url='https://cdn.prod.website-files.com/6732ede3c32a0faadbd4a3e8/67513a178d3e8a35b18db976_facestudio_20s_south_asian_male_3374592678-p-500.jpeg'
				heading Devendra Mali
				StaticText BUSINESS
				heading Comprehensive Guide to External Commercial Borrowings (ECBs) for Indian Businesses
	list
		listitem
			link Devendra Mali BUSINESS Comprehensive Guide to External Commercial Borrowings (ECBs) for Indian Businesses, url='https://www.karbonbusiness.com/blog/external-commercial-borrowings'
				image, url='https://cdn.prod.website-files.com/6732ede3c32a0faadbd4a3e8/6752da9aba0a3f5936395e50_external-commercial-borrowings-p-800.png'
				image, url='https://cdn.prod.website-files.com/6732ede3c32a0faadbd4a3e8/67513a178d3e8a35b18db976_facestudio_20s_south_asian_male_3374592678-p-500.jpeg'
				heading Devendra Mali
				StaticText BUSINESS
				heading Comprehensive Guide to External Commercial Borrowings (ECBs) for Indian Businesses
		listitem
			link Ramitha Ramesh BUSINESS A Guide to Bank Comfort Letters: What Indian Businesses Need to Know, url='https://www.karbonbusiness.com/blog/guide-to-bank-comfort-letter'
				image, url='https://cdn.prod.website-files.com/6732ede3c32a0faadbd4a3e8/67503284fd020365a12597b6_guide-to-bank-comfort-letter-p-800.png'
				image, url='https://cdn.prod.website-files.com/6732ede3c32a0faadbd4a3e8/67347d9018083acda93c7761_63bd31eb12055b5040d65345_20230110-150730-p-500.jpg'
				heading Ramitha Ramesh
				StaticText BUSINESS
				heading A Guide to Bank Comfort Letters: What Indian Businesses Need to Know
		listitem
			link Ramitha Ramesh BUSINESS Understanding Cross-Border Mergers in India: Regulations, Examples, and Key Insights, url='https://www.karbonbusiness.com/blog/cross-border-mergers-in-india-regulations-examples'
				image, url='https://cdn.prod.website-files.com/6732ede3c32a0faadbd4a3e8/67498e0482588c205e1a72cc_cross-border-mergers-in-india-regulations-examples-p-800.png'
				image, url='https://cdn.prod.website-files.com/6732ede3c32a0faadbd4a3e8/67347d9018083acda93c7761_63bd31eb12055b5040d65345_20230110-150730-p-500.jpg'
				heading Ramitha Ramesh
				StaticText BUSINESS
				heading Understanding Cross-Border Mergers in India: Regulations, Examples, and Key Insights
	heading Frequently Asked Questions
	StaticText What do we do here at Karbon Business?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText How does Karbon Card help with B2B finance management?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Who can benefit from using Karbon’s services?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText How do I apply for a prepaid card?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Is there a fee for using Karbon Forex services?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	heading Simplify Your Business Payments
	StaticText Reach out to us today!
	form Email Form
		link Get Started, url='https://www.karbonbusiness.com/contact'
	link Ground Floor, Karbon Business, 1st Stage Rd, Binnamangala, Hoysala Nagar, Indiranagar, Bengaluru, Karnataka 560038, url='https://www.karbonbusiness.com/#'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd3a219e41ad2476906_Karbon%20Business%20white%20logo.png'
	link Contact Us, url='https://www.karbonbusiness.com/#'
		strong
	link support@karboncard.com, url='https://www.karbonbusiness.com/#'
	link Connect on Whatsapp, url='https://www.karbonbusiness.com/#'
	link Schedule a demo, url='https://www.karboncard.com/contact'
	link 1-800-309-8470, url='https://www.karbonbusiness.com/#'
	link Company, url='https://www.karbonbusiness.com/#'
		strong
	link Inward, url='https://www.karbonbusiness.com/accept-international-payments-india'
		strong
	link Outward, url='https://www.karbonbusiness.com/outward-remittance-india'
		strong
	link Card, url='https://www.karbonbusiness.com/corporate-prepaid-card-by-karbon'
		strong
	link Career, url='https://www.karbonbusiness.com/about'
		strong
	link Blogs, url='https://www.karbonbusiness.com/blog'
		strong
	link Legal, url='https://www.karbonbusiness.com/#'
		strong
	link User Agreement, url='https://www.karbonbusiness.com/karbon-user-agreement'
		strong
	link Terms and Conditions, url='https://www.karbonbusiness.com/karbon-terms-conditions'
		strong
	link T&C - LIvQuik, url='https://cdn.prod.website-files.com/636cbe89ca23fd1c5fe8e188/67330b70f8b770d9e6c4b5f2_LivQuik%20%20Karbon%20T%26C%20for%20Prepaid%20Cards%20051124%20(1).pdf'
		strong
	StaticText © All rights reserved.
	link, url='https://www.facebook.com/people/Karbon-Card/100064030717569/'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd3a219e41ad24768d3_Group%2025.svg'
	link, url='https://x.com/KarbonIndia'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd2a219e41ad2476861_Vector.svg'
	link, url='https://www.youtube.com/watch?v=vND9ieTBT-g'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd3a219e41ad24768ed_Group%2026.svg'
	link, url='https://in.linkedin.com/company/karbonbusiness'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd2a219e41ad2476839_Group%2027.svg'
```
</details>



```
RootWebArea Accept International Payments to India - Karbon Forex, focused, url='https://www.karbonbusiness.com/accept-international-payments-india'
	banner
		[36] link home, center=(175,36), url='https://www.karbonbusiness.com/'
			image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab120e0cd7cc8ed12069_636e120a891dc54ee1e0a891_cropped-Untitled-design-removebg-preview-p-500%201%20(1).png'
		navigation
```
<details><summary>Show more</summary>

```
			[40] link Inward Remittances, center=(694,36), url='https://www.karbonbusiness.com/accept-international-payments-india'
			[41] link Outward Remittances, center=(903,36), url='https://www.karbonbusiness.com/outward-remittance-india'
			[42] link Corporate Card, center=(1093,36), url='https://www.karbonbusiness.com/corporate-prepaid-card-by-karbon'
			[43] link Career, center=(1219,36), url='https://www.karbonbusiness.com/about'
		navigation
			[50] link Login, center=(1640,36), url='http://karbonfx.com/login'
			[51] link Sign Up, center=(1752,36), url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	heading Accept USD Payment With 1% Flat Fee
	paragraph
		StaticText Inward remittances made quicker, more affordable, and effortless
	[61] link Sign Up, center=(896,331), url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	[62] link Login, center=(1031,331), url='http://karbonfx.com/login'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/67173af49242a150cd959119_c9d41cf0d64511c35a05c128ead4a3f7%201.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb00b_Img_margin-4.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb051_Img_margin-2.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb02b_Img_margin-1.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab707593bf76f89fb082_Img_margin-7.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb048_Img_margin-3.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb044_Img_margin.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fafe9_Img_margin-6.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb04c_Img_margin-5.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab707593bf76f89fb05f_Img_margin-8.svg'
	region carousel
		group 1 of 4
			heading Fast
			image Fast Settlement, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac58d6eb7977a93b0e18_Frame%201000000979.png'
			StaticText Fast Settlement
			StaticText Receive inward remittance between 24 to 48 hours
			image Fast onboarding, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac57d6eb7977a93b0dc1_Frame%201000000979%20(1).png'
			StaticText Fast Onboarding
			StaticText Submit your first invoice in 10 minutes
		button previous slide
			StaticText 
		button next slide
			StaticText 
	heading Receive Payment in 30+ Currencies
	paragraph
		StaticText Karbon Supports almost all currencies across the world
	link Start accepting payments, url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	Iframe
		RootWebArea Karbon forex, url='https://app.dev.karbonfx.com/onlycalci'
			[a37] article, center=(703,1922)
				StaticText Your Client Pays
			[a44] spinbutton value='100', center=(633,1959)
			combobox, autocomplete='list', hasPopup='listbox'
			[a56] image usd, center=(774,1959), url='https://app.dev.karbonfx.com/assets/usd-D7YqEwsK.svg'
			StaticText USD
			heading ₹85.86
			heading Live FOREX Rate
			heading ₹8,586.00
			[a72] heading Converted Amount, center=(777,2050)
			heading ₹85.86
			heading Our Fees (1%)
			heading ₹0
			[a83] heading Hidden Charges, center=(777,2106)
			[a85] article, center=(703,2173)
				StaticText You’ll receive
			[a87] heading ₹8,500.14, center=(633,2210)
			[a90] image, center=(784,2210), url="data:image/svg+xml,%3csvg%20xmlns:xlink='http://www.w3.org/1999/xlink'%20xmlns='http://www.w3.org/2000/svg'%20width='24'%20height='19'%20viewBox='0%200%2024%2019'%20fill='none'%3e%3crect%20x='0.348267'%20y='0.971069'%20width='23.5391'%20height='17.1193'%20fill='white'/%3e%3cpath%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M0.348267%206.67752H23.8874V0.971069H0.348267V6.67752Z'%20fill='%23FFA44A'/%3e%3cpath%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M0.348267%2018.0904H23.8874V12.384H0.348267V18.0904Z'%20fill='%231A9F0B'/%3e%3cpath%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.1177%2011.2427C13.0463%2011.2427%2013.7991%2010.4762%2013.7991%209.53075C13.7991%208.58528%2013.0463%207.81882%2012.1177%207.81882C11.1891%207.81882%2010.4363%208.58528%2010.4363%209.53075C10.4363%2010.4762%2011.1891%2011.2427%2012.1177%2011.2427Z'%20fill='%23181A93'%20fill-opacity='0.15'/%3e%3cpath%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M14.3597%209.53074C14.3597%2010.7914%2013.356%2011.8133%2012.1179%2011.8133C10.8797%2011.8133%209.87604%2010.7914%209.87604%209.53074C9.87604%208.27011%2010.8797%207.24816%2012.1179%207.24816C13.356%207.24816%2014.3597%208.27011%2014.3597%209.53074ZM13.7992%209.53074C13.7992%2010.4762%2013.0464%2011.2427%2012.1179%2011.2427C11.1893%2011.2427%2010.4365%2010.4762%2010.4365%209.53074C10.4365%208.58527%2011.1893%207.81881%2012.1179%207.81881C13.0464%207.81881%2013.7992%208.58527%2013.7992%209.53074Z'%20fill='%23181A93'/%3e%3cpath%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.1177%2010.1014C12.4272%2010.1014%2012.6781%209.84589%2012.6781%209.53074C12.6781%209.21558%2012.4272%208.96009%2012.1177%208.96009C11.8081%208.96009%2011.5572%209.21558%2011.5572%209.53074C11.5572%209.84589%2011.8081%2010.1014%2012.1177%2010.1014Z'%20fill='%23181A93'/%3e%3c/svg%3e"
			StaticText INR
	heading Karbon FX
	StaticText Cheaper, quicker and easier foreign remittance tool built for Indian businesses
	link Sign Up, url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	heading How Does Karbon FX work?
	image Create Account, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac6747be08e9427294a2_Frame.svg'
	StaticText Create an Account
	image Upload Invoice, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac6747be08e9427294b1_Frame%20(1).svg'
	StaticText Upload Invoice
	image Done!, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac6747be08e9427294e6_Frame%20(2).svg'
	StaticText You are all set!
	heading Why Karbon FX?
	link Sign Up, url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	image Karbon Logo, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd3a219e41ad2476906_Karbon%2520Business%2520white%2520logo-p-500.png'
	paragraph
		StaticText ▪ Transaction fee: 1%
		StaticText ▪ 0% Forex markup
		StaticText ▪ 24hrs customer support
		StaticText ▪ No Chargeback/Disputes
		StaticText ▪ No Funds block
	image Paypal Logo, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/675a854bf76b5bde42e484d9_Frame%201000001218.png'
	paragraph
		StaticText ▪ Transaction fee: 4.4% + $0.3
		StaticText ▪ Minimum 3% Forex markup
		StaticText ▪ 24hrs customer support
		StaticText ▪ Chargeback/Disputes
		StaticText ▪ Funds block
	heading Why Do Users Trust Us?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabacb2b498a901965702_873.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Arun Ramanathan
		strong
	StaticText Karbon has been a great partner for our business. Their platform is user-friendly and we appreciate the transparency they provide throughout the remittance process. We can count on them to deliver our payments on time and with no hidden fees.
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabacb2b498a90196573f_666c158ae76bcbecf52d86a0_Karbon-business-p-130x130q80.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Shankar R
		strong
	StaticText Karbon has been a game changer for our business. We needed a reliable and efficient way to make international payments and Karbon has delivered. Their customer support team is always available to help and we've had no issues with the remittance process. Highly recommended!
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabadb2b498a901965871_121sad.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Aishwarya Nair
		strong
	StaticText Karbon has made our foreign outward remittance process so much simpler. Their platform is easy to use and we can track our transactions in real-time. Plus, their rates are very competitive. We're very happy with their service.
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabadb2b498a90196587a_Untitled-1.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Nidhi Menon
		strong
	StaticText We were looking for a trustworthy foreign outward remittance service and Karbon has exceeded our expectations. Their team is professional and responsive, and they've helped us navigate complex compliance requirements. We now use Karbon for all our international transactions
	heading Frequently Asked Questions
	StaticText Is Karbon Forex a payment gateway? Or does it specialize in SWIFT Wire Transfers to accept international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText What are the charges under Karbon Forex to accept international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Is the forex fee inclusive of GST?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText What are the documents required to accept international payments in India with Karbon Forex?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText What is the transaction time involved in accepting international payments in India through Karbon Forex?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Is a shop establishment certificate needed to accept international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Does Karbon Forex have a multi-currency account apart from USD?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Is providing an invoice mandatory to accept international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Is the Karbon Forex fee a one-time or recurring charge?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Which bank is Karbon Forex tied up with to accept international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText What are the currencies Karbon can process to accept international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Who issues FIRC?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Can Karbon Forex enable the onboarding of sole proprietors for accepting international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Is a GST certificate needed for inward remittance?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Which account will the money come into?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Is a GST certificate required for proprietorships that want to accept international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Are there any charges for holding the funds in the virtual account for 60 days?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	heading Simplify Your Business Payments
	StaticText Reach out to us today!
	form Email Form
		link Get Started, url='https://www.karbonbusiness.com/contact'
	link Ground Floor, Karbon Business, 1st Stage Rd, Binnamangala, Hoysala Nagar, Indiranagar, Bengaluru, Karnataka 560038, url='https://www.karbonbusiness.com/accept-international-payments-india#'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd3a219e41ad2476906_Karbon%20Business%20white%20logo.png'
	link Contact Us, url='https://www.karbonbusiness.com/accept-international-payments-india#'
		strong
	link support@karboncard.com, url='https://www.karbonbusiness.com/accept-international-payments-india#'
	link Connect on Whatsapp, url='https://www.karbonbusiness.com/accept-international-payments-india#'
	link Schedule a demo, url='https://www.karboncard.com/contact'
	link 1-800-309-8470, url='https://www.karbonbusiness.com/accept-international-payments-india#'
	link Company, url='https://www.karbonbusiness.com/accept-international-payments-india#'
		strong
	link Inward, url='https://www.karbonbusiness.com/accept-international-payments-india'
		strong
	link Outward, url='https://www.karbonbusiness.com/outward-remittance-india'
		strong
	link Card, url='https://www.karbonbusiness.com/corporate-prepaid-card-by-karbon'
		strong
	link Career, url='https://www.karbonbusiness.com/about'
		strong
	link Blogs, url='https://www.karbonbusiness.com/blog'
		strong
	link Legal, url='https://www.karbonbusiness.com/accept-international-payments-india#'
		strong
	link User Agreement, url='https://www.karbonbusiness.com/karbon-user-agreement'
		strong
	link Terms and Conditions, url='https://www.karbonbusiness.com/karbon-terms-conditions'
		strong
	link T&C - LIvQuik, url='https://cdn.prod.website-files.com/636cbe89ca23fd1c5fe8e188/67330b70f8b770d9e6c4b5f2_LivQuik%20%20Karbon%20T%26C%20for%20Prepaid%20Cards%20051124%20(1).pdf'
		strong
	StaticText © All rights reserved.
	link, url='https://www.facebook.com/people/Karbon-Card/100064030717569/'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd3a219e41ad24768d3_Group%2025.svg'
	link, url='https://x.com/KarbonIndia'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd2a219e41ad2476861_Vector.svg'
	link, url='https://www.youtube.com/watch?v=vND9ieTBT-g'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd3a219e41ad24768ed_Group%2026.svg'
	link, url='https://in.linkedin.com/company/karbonbusiness'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd2a219e41ad2476839_Group%2027.svg'
```
</details>

**Reasoning for action:** I clicked on the 'Inward Remittances' link because this is the first step in the user story. The user wants to explore remittance solutions offered by Karbon. By accessing this section, I can begin to gather information about the services provided. This will help in determining options that may suit the user's business needs.

**Action:** click(34) # Click on the 'Inward Remittances' link to explore that section.

**Change Description:** After clicking on the 'Inward Remittances' link, the browser state changed to the 'Accept International Payments to India - Karbon Forex' page. The URL updated to reflect the new section, and the header and content transitioned to focus on the services related to inbound remittances, while retaining navigational links and features from the previous page.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.karbonbusiness.com/accept-international-payments-india

https://www.karbonbusiness.com/outward-remittance-india

**Content (before/after):** 

```
RootWebArea Accept International Payments to India - Karbon Forex, focused, url='https://www.karbonbusiness.com/accept-international-payments-india'
	banner
		[36] link home, center=(175,36), url='https://www.karbonbusiness.com/'
			image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab120e0cd7cc8ed12069_636e120a891dc54ee1e0a891_cropped-Untitled-design-removebg-preview-p-500%201%20(1).png'
		navigation
```
<details><summary>Show more</summary>

```
			[40] link Inward Remittances, center=(694,36), url='https://www.karbonbusiness.com/accept-international-payments-india'
			[41] link Outward Remittances, center=(903,36), url='https://www.karbonbusiness.com/outward-remittance-india'
			[42] link Corporate Card, center=(1093,36), url='https://www.karbonbusiness.com/corporate-prepaid-card-by-karbon'
			[43] link Career, center=(1219,36), url='https://www.karbonbusiness.com/about'
		navigation
			[50] link Login, center=(1640,36), url='http://karbonfx.com/login'
			[51] link Sign Up, center=(1752,36), url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	heading Accept USD Payment With 1% Flat Fee
	paragraph
		StaticText Inward remittances made quicker, more affordable, and effortless
	[61] link Sign Up, center=(896,331), url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	[62] link Login, center=(1031,331), url='http://karbonfx.com/login'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/67173af49242a150cd959119_c9d41cf0d64511c35a05c128ead4a3f7%201.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb00b_Img_margin-4.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb051_Img_margin-2.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb02b_Img_margin-1.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab707593bf76f89fb082_Img_margin-7.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb048_Img_margin-3.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb044_Img_margin.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fafe9_Img_margin-6.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb04c_Img_margin-5.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab707593bf76f89fb05f_Img_margin-8.svg'
	region carousel
		group 1 of 4
			heading Fast
			image Fast Settlement, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac58d6eb7977a93b0e18_Frame%201000000979.png'
			StaticText Fast Settlement
			StaticText Receive inward remittance between 24 to 48 hours
			image Fast onboarding, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac57d6eb7977a93b0dc1_Frame%201000000979%20(1).png'
			StaticText Fast Onboarding
			StaticText Submit your first invoice in 10 minutes
		button previous slide
			StaticText 
		button next slide
			StaticText 
	heading Receive Payment in 30+ Currencies
	paragraph
		StaticText Karbon Supports almost all currencies across the world
	link Start accepting payments, url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	Iframe
		RootWebArea Karbon forex, url='https://app.dev.karbonfx.com/onlycalci'
			[a37] article, center=(703,1922)
				StaticText Your Client Pays
			[a44] spinbutton value='100', center=(633,1959)
			combobox, autocomplete='list', hasPopup='listbox'
			[a56] image usd, center=(774,1959), url='https://app.dev.karbonfx.com/assets/usd-D7YqEwsK.svg'
			StaticText USD
			heading ₹85.86
			heading Live FOREX Rate
			heading ₹8,586.00
			[a72] heading Converted Amount, center=(777,2050)
			heading ₹85.86
			heading Our Fees (1%)
			heading ₹0
			[a83] heading Hidden Charges, center=(777,2106)
			[a85] article, center=(703,2173)
				StaticText You’ll receive
			[a87] heading ₹8,500.14, center=(633,2210)
			[a90] image, center=(784,2210), url="data:image/svg+xml,%3csvg%20xmlns:xlink='http://www.w3.org/1999/xlink'%20xmlns='http://www.w3.org/2000/svg'%20width='24'%20height='19'%20viewBox='0%200%2024%2019'%20fill='none'%3e%3crect%20x='0.348267'%20y='0.971069'%20width='23.5391'%20height='17.1193'%20fill='white'/%3e%3cpath%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M0.348267%206.67752H23.8874V0.971069H0.348267V6.67752Z'%20fill='%23FFA44A'/%3e%3cpath%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M0.348267%2018.0904H23.8874V12.384H0.348267V18.0904Z'%20fill='%231A9F0B'/%3e%3cpath%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.1177%2011.2427C13.0463%2011.2427%2013.7991%2010.4762%2013.7991%209.53075C13.7991%208.58528%2013.0463%207.81882%2012.1177%207.81882C11.1891%207.81882%2010.4363%208.58528%2010.4363%209.53075C10.4363%2010.4762%2011.1891%2011.2427%2012.1177%2011.2427Z'%20fill='%23181A93'%20fill-opacity='0.15'/%3e%3cpath%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M14.3597%209.53074C14.3597%2010.7914%2013.356%2011.8133%2012.1179%2011.8133C10.8797%2011.8133%209.87604%2010.7914%209.87604%209.53074C9.87604%208.27011%2010.8797%207.24816%2012.1179%207.24816C13.356%207.24816%2014.3597%208.27011%2014.3597%209.53074ZM13.7992%209.53074C13.7992%2010.4762%2013.0464%2011.2427%2012.1179%2011.2427C11.1893%2011.2427%2010.4365%2010.4762%2010.4365%209.53074C10.4365%208.58527%2011.1893%207.81881%2012.1179%207.81881C13.0464%207.81881%2013.7992%208.58527%2013.7992%209.53074Z'%20fill='%23181A93'/%3e%3cpath%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.1177%2010.1014C12.4272%2010.1014%2012.6781%209.84589%2012.6781%209.53074C12.6781%209.21558%2012.4272%208.96009%2012.1177%208.96009C11.8081%208.96009%2011.5572%209.21558%2011.5572%209.53074C11.5572%209.84589%2011.8081%2010.1014%2012.1177%2010.1014Z'%20fill='%23181A93'/%3e%3c/svg%3e"
			StaticText INR
	heading Karbon FX
	StaticText Cheaper, quicker and easier foreign remittance tool built for Indian businesses
	link Sign Up, url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	heading How Does Karbon FX work?
	image Create Account, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac6747be08e9427294a2_Frame.svg'
	StaticText Create an Account
	image Upload Invoice, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac6747be08e9427294b1_Frame%20(1).svg'
	StaticText Upload Invoice
	image Done!, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac6747be08e9427294e6_Frame%20(2).svg'
	StaticText You are all set!
	heading Why Karbon FX?
	link Sign Up, url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	image Karbon Logo, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd3a219e41ad2476906_Karbon%2520Business%2520white%2520logo-p-500.png'
	paragraph
		StaticText ▪ Transaction fee: 1%
		StaticText ▪ 0% Forex markup
		StaticText ▪ 24hrs customer support
		StaticText ▪ No Chargeback/Disputes
		StaticText ▪ No Funds block
	image Paypal Logo, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/675a854bf76b5bde42e484d9_Frame%201000001218.png'
	paragraph
		StaticText ▪ Transaction fee: 4.4% + $0.3
		StaticText ▪ Minimum 3% Forex markup
		StaticText ▪ 24hrs customer support
		StaticText ▪ Chargeback/Disputes
		StaticText ▪ Funds block
	heading Why Do Users Trust Us?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabacb2b498a901965702_873.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Arun Ramanathan
		strong
	StaticText Karbon has been a great partner for our business. Their platform is user-friendly and we appreciate the transparency they provide throughout the remittance process. We can count on them to deliver our payments on time and with no hidden fees.
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabacb2b498a90196573f_666c158ae76bcbecf52d86a0_Karbon-business-p-130x130q80.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Shankar R
		strong
	StaticText Karbon has been a game changer for our business. We needed a reliable and efficient way to make international payments and Karbon has delivered. Their customer support team is always available to help and we've had no issues with the remittance process. Highly recommended!
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabadb2b498a901965871_121sad.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Aishwarya Nair
		strong
	StaticText Karbon has made our foreign outward remittance process so much simpler. Their platform is easy to use and we can track our transactions in real-time. Plus, their rates are very competitive. We're very happy with their service.
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabadb2b498a90196587a_Untitled-1.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Nidhi Menon
		strong
	StaticText We were looking for a trustworthy foreign outward remittance service and Karbon has exceeded our expectations. Their team is professional and responsive, and they've helped us navigate complex compliance requirements. We now use Karbon for all our international transactions
	heading Frequently Asked Questions
	StaticText Is Karbon Forex a payment gateway? Or does it specialize in SWIFT Wire Transfers to accept international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText What are the charges under Karbon Forex to accept international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Is the forex fee inclusive of GST?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText What are the documents required to accept international payments in India with Karbon Forex?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText What is the transaction time involved in accepting international payments in India through Karbon Forex?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Is a shop establishment certificate needed to accept international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Does Karbon Forex have a multi-currency account apart from USD?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Is providing an invoice mandatory to accept international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Is the Karbon Forex fee a one-time or recurring charge?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Which bank is Karbon Forex tied up with to accept international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText What are the currencies Karbon can process to accept international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Who issues FIRC?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Can Karbon Forex enable the onboarding of sole proprietors for accepting international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Is a GST certificate needed for inward remittance?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Which account will the money come into?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Is a GST certificate required for proprietorships that want to accept international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	StaticText Are there any charges for holding the funds in the virtual account for 60 days?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	heading Simplify Your Business Payments
	StaticText Reach out to us today!
	form Email Form
		link Get Started, url='https://www.karbonbusiness.com/contact'
	link Ground Floor, Karbon Business, 1st Stage Rd, Binnamangala, Hoysala Nagar, Indiranagar, Bengaluru, Karnataka 560038, url='https://www.karbonbusiness.com/accept-international-payments-india#'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd3a219e41ad2476906_Karbon%20Business%20white%20logo.png'
	link Contact Us, url='https://www.karbonbusiness.com/accept-international-payments-india#'
		strong
	link support@karboncard.com, url='https://www.karbonbusiness.com/accept-international-payments-india#'
	link Connect on Whatsapp, url='https://www.karbonbusiness.com/accept-international-payments-india#'
	link Schedule a demo, url='https://www.karboncard.com/contact'
	link 1-800-309-8470, url='https://www.karbonbusiness.com/accept-international-payments-india#'
	link Company, url='https://www.karbonbusiness.com/accept-international-payments-india#'
		strong
	link Inward, url='https://www.karbonbusiness.com/accept-international-payments-india'
		strong
	link Outward, url='https://www.karbonbusiness.com/outward-remittance-india'
		strong
	link Card, url='https://www.karbonbusiness.com/corporate-prepaid-card-by-karbon'
		strong
	link Career, url='https://www.karbonbusiness.com/about'
		strong
	link Blogs, url='https://www.karbonbusiness.com/blog'
		strong
	link Legal, url='https://www.karbonbusiness.com/accept-international-payments-india#'
		strong
	link User Agreement, url='https://www.karbonbusiness.com/karbon-user-agreement'
		strong
	link Terms and Conditions, url='https://www.karbonbusiness.com/karbon-terms-conditions'
		strong
	link T&C - LIvQuik, url='https://cdn.prod.website-files.com/636cbe89ca23fd1c5fe8e188/67330b70f8b770d9e6c4b5f2_LivQuik%20%20Karbon%20T%26C%20for%20Prepaid%20Cards%20051124%20(1).pdf'
		strong
	StaticText © All rights reserved.
	link, url='https://www.facebook.com/people/Karbon-Card/100064030717569/'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd3a219e41ad24768d3_Group%2025.svg'
	link, url='https://x.com/KarbonIndia'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd2a219e41ad2476861_Vector.svg'
	link, url='https://www.youtube.com/watch?v=vND9ieTBT-g'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd3a219e41ad24768ed_Group%2026.svg'
	link, url='https://in.linkedin.com/company/karbonbusiness'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd2a219e41ad2476839_Group%2027.svg'
```
</details>



```
RootWebArea Karbon Forex: Fast and Affordable Vendor Payments Worldwide, focused, url='https://www.karbonbusiness.com/outward-remittance-india'
	banner
		[37] link home, center=(175,36), url='https://www.karbonbusiness.com/'
			image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab120e0cd7cc8ed12069_636e120a891dc54ee1e0a891_cropped-Untitled-design-removebg-preview-p-500%201%20(1).png'
		navigation
```
<details><summary>Show more</summary>

```
			[41] link Inward Remittances, center=(694,36), url='https://www.karbonbusiness.com/accept-international-payments-india'
			[42] link Outward Remittances, center=(902,36), url='https://www.karbonbusiness.com/outward-remittance-india'
			[43] link Corporate Card, center=(1092,36), url='https://www.karbonbusiness.com/corporate-prepaid-card-by-karbon'
			[44] link Career, center=(1218,36), url='https://www.karbonbusiness.com/about'
		navigation
			[51] link Login, center=(1640,36), url='http://karbonfx.com/login'
			[52] link Sign Up, center=(1752,36), url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	heading Customer - Centric Outward Remittance Solution
	paragraph
		StaticText Responsive support, assisted onboarding, minimal documentation, and the best rate, guaranteed
	[63] link Sign Up, center=(896,341), url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	[64] link Login, center=(1031,341), url='http://karbonfx.com/login'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/67173af49242a150cd959119_c9d41cf0d64511c35a05c128ead4a3f7%201.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb00b_Img_margin-4.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb051_Img_margin-2.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb02b_Img_margin-1.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab707593bf76f89fb082_Img_margin-7.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb048_Img_margin-3.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb044_Img_margin.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fafe9_Img_margin-6.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb04c_Img_margin-5.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab707593bf76f89fb05f_Img_margin-8.svg'
	region carousel
		group 1 of 4
			heading Low Cost
			image Competitive Rates, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/673c2a8878cef2489d58fcf5_Frame%201000000979.png'
			StaticText Competitive Rates
			StaticText Reduced costs for international transactions
			image Low Forex Markups, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac58d6eb7977a93b0e45_Frame%201000000979%20(3).png'
			StaticText Low Forex Markups
			StaticText Save more with minimal fees.
		button previous slide
			StaticText 
		button next slide
			StaticText 
	heading Send Payment in 30+ Currencies
	paragraph
		StaticText Karbon Supports almost all currencies across the world
	link Start sending payments, url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	heading How Does Karbon FX work?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac6747be08e9427294a2_Frame.svg'
	StaticText Create an Account
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac6747be08e9427294b1_Frame%20(1).svg'
	StaticText Upload Invoice
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac6747be08e9427294e6_Frame%20(2).svg'
	StaticText You are all set!
	heading Why Do Users Trust Us?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabacb2b498a901965702_873.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Arun Ramanathan
		strong
	StaticText Karbon has been a great partner for our business. Their platform is user-friendly and we appreciate the transparency they provide throughout the remittance process. We can count on them to deliver our payments on time and with no hidden fees.
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabacb2b498a90196573f_666c158ae76bcbecf52d86a0_Karbon-business-p-130x130q80.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Shankar R
		strong
	StaticText Karbon has been a game changer for our business. We needed a reliable and efficient way to make international payments and Karbon has delivered. Their customer support team is always available to help and we've had no issues with the remittance process. Highly recommended!
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabadb2b498a901965871_121sad.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Aishwarya Nair
		strong
	StaticText Karbon has made our foreign outward remittance process so much simpler. Their platform is easy to use and we can track our transactions in real-time. Plus, their rates are very competitive. We're very happy with their service.
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabadb2b498a90196587a_Untitled-1.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Nidhi Menon
		strong
	StaticText We were looking for a trustworthy foreign outward remittance service and Karbon has exceeded our expectations. Their team is professional and responsive, and they've helped us navigate complex compliance requirements. We now use Karbon for all our international transactions
	heading Frequently Asked Questions
	strong
		StaticText How does Karbon Forex help businesses send money abroad?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Is Karbon Forex a payment gateway?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText What are the fees for sending money overseas?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Is GST included in the fees?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText What documents do I need to make an outward remittance from India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Is a shop establishment certificate needed to accept international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText What currencies can I pay in?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Can I use Karbon Forex to pay contractors internationally?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Is there any holding fee for money maintained in a virtual account?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Which bank does Karbon Forex partner with for international payments to India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Is Karbon Forex's service available for sole proprietors?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Is providing an invoice required for outward remittance?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Is a GST certificate required for outward remittance?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText How to track my outward remittance? What notification will I get when funds are transferred?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Under what circumstances is a Chartered Accountant (CA) certificate needed for outward remittances?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText What types of transactions are restricted by the Foreign Exchange Management Act, 1999?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText What is the tax liability for outward remittance?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	heading Simplify Your Business Payments
	StaticText Reach out to us today!
	form Email Form
		link Get Started, url='https://www.karbonbusiness.com/contact'
	link Ground Floor, Karbon Business, 1st Stage Rd, Binnamangala, Hoysala Nagar, Indiranagar, Bengaluru, Karnataka 560038, url='https://www.karbonbusiness.com/outward-remittance-india#'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd3a219e41ad2476906_Karbon%20Business%20white%20logo.png'
	link Contact Us, url='https://www.karbonbusiness.com/outward-remittance-india#'
		strong
	link support@karboncard.com, url='https://www.karbonbusiness.com/outward-remittance-india#'
	link Connect on Whatsapp, url='https://www.karbonbusiness.com/outward-remittance-india#'
	link Schedule a demo, url='https://www.karboncard.com/contact'
	link 1-800-309-8470, url='https://www.karbonbusiness.com/outward-remittance-india#'
	link Company, url='https://www.karbonbusiness.com/outward-remittance-india#'
		strong
	link Inward, url='https://www.karbonbusiness.com/accept-international-payments-india'
		strong
	link Outward, url='https://www.karbonbusiness.com/outward-remittance-india'
		strong
	link Card, url='https://www.karbonbusiness.com/corporate-prepaid-card-by-karbon'
		strong
	link Career, url='https://www.karbonbusiness.com/about'
		strong
	link Blogs, url='https://www.karbonbusiness.com/blog'
		strong
	link Legal, url='https://www.karbonbusiness.com/outward-remittance-india#'
		strong
	link User Agreement, url='https://www.karbonbusiness.com/karbon-user-agreement'
		strong
	link Terms and Conditions, url='https://www.karbonbusiness.com/karbon-terms-conditions'
		strong
	link T&C - LIvQuik, url='https://cdn.prod.website-files.com/636cbe89ca23fd1c5fe8e188/67330b70f8b770d9e6c4b5f2_LivQuik%20%20Karbon%20T%26C%20for%20Prepaid%20Cards%20051124%20(1).pdf'
		strong
	StaticText © All rights reserved.
	link, url='https://www.facebook.com/people/Karbon-Card/100064030717569/'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd3a219e41ad24768d3_Group%2025.svg'
	link, url='https://x.com/KarbonIndia'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd2a219e41ad2476861_Vector.svg'
	link, url='https://www.youtube.com/watch?v=vND9ieTBT-g'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd3a219e41ad24768ed_Group%2026.svg'
	link, url='https://in.linkedin.com/company/karbonbusiness'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd2a219e41ad2476839_Group%2027.svg'
```
</details>

**Reasoning for action:** By clicking on the 'Outward Remittances' link, I advance toward exploring the remittance solutions that Karbon offers specifically for sending money internationally. This action is essential for understanding my options as a potential customer and helps me gather the information needed to assess whether this service meets my business needs. Following this link is a critical step toward completing the user's instruction.

**Action:** click(41) # Click on the 'Outward Remittances' link to explore that section.

**Change Description:** The browser navigated to the 'Outward Remittances' page, updating the URL to 'https://www.karbonbusiness.com/outward-remittance-india' and changing the main heading from 'Accept USD Payment With 1% Flat Fee' to 'Customer - Centric Outward Remittance Solution,' along with a new focus on competitive rates and responsive support features.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.karbonbusiness.com/outward-remittance-india

https://karbonfx.com/signup-v2-form?utm_source=karboncard&_gl=1*oblfw0*_ga*MTMwODAxNjc5LjE3MzY0MzAyMDI.*_ga_36TTY46M1C*MTczNjQzMDIwMS4xLjEuMTczNjQzMDMwMy41OS4wLjA.

**Content (before/after):** 

```
RootWebArea Karbon Forex: Fast and Affordable Vendor Payments Worldwide, focused, url='https://www.karbonbusiness.com/outward-remittance-india'
	banner
		[37] link home, center=(175,36), url='https://www.karbonbusiness.com/'
			image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab120e0cd7cc8ed12069_636e120a891dc54ee1e0a891_cropped-Untitled-design-removebg-preview-p-500%201%20(1).png'
		navigation
```
<details><summary>Show more</summary>

```
			[41] link Inward Remittances, center=(694,36), url='https://www.karbonbusiness.com/accept-international-payments-india'
			[42] link Outward Remittances, center=(902,36), url='https://www.karbonbusiness.com/outward-remittance-india'
			[43] link Corporate Card, center=(1092,36), url='https://www.karbonbusiness.com/corporate-prepaid-card-by-karbon'
			[44] link Career, center=(1218,36), url='https://www.karbonbusiness.com/about'
		navigation
			[51] link Login, center=(1640,36), url='http://karbonfx.com/login'
			[52] link Sign Up, center=(1752,36), url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	heading Customer - Centric Outward Remittance Solution
	paragraph
		StaticText Responsive support, assisted onboarding, minimal documentation, and the best rate, guaranteed
	[63] link Sign Up, center=(896,341), url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	[64] link Login, center=(1031,341), url='http://karbonfx.com/login'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/67173af49242a150cd959119_c9d41cf0d64511c35a05c128ead4a3f7%201.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb00b_Img_margin-4.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb051_Img_margin-2.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb02b_Img_margin-1.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab707593bf76f89fb082_Img_margin-7.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb048_Img_margin-3.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb044_Img_margin.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fafe9_Img_margin-6.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab6f7593bf76f89fb04c_Img_margin-5.svg'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fab707593bf76f89fb05f_Img_margin-8.svg'
	region carousel
		group 1 of 4
			heading Low Cost
			image Competitive Rates, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/673c2a8878cef2489d58fcf5_Frame%201000000979.png'
			StaticText Competitive Rates
			StaticText Reduced costs for international transactions
			image Low Forex Markups, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac58d6eb7977a93b0e45_Frame%201000000979%20(3).png'
			StaticText Low Forex Markups
			StaticText Save more with minimal fees.
		button previous slide
			StaticText 
		button next slide
			StaticText 
	heading Send Payment in 30+ Currencies
	paragraph
		StaticText Karbon Supports almost all currencies across the world
	link Start sending payments, url='https://karbonfx.com/signup-v2-form?utm_source=karboncard'
	heading How Does Karbon FX work?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac6747be08e9427294a2_Frame.svg'
	StaticText Create an Account
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac6747be08e9427294b1_Frame%20(1).svg'
	StaticText Upload Invoice
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fac6747be08e9427294e6_Frame%20(2).svg'
	StaticText You are all set!
	heading Why Do Users Trust Us?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabacb2b498a901965702_873.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Arun Ramanathan
		strong
	StaticText Karbon has been a great partner for our business. Their platform is user-friendly and we appreciate the transparency they provide throughout the remittance process. We can count on them to deliver our payments on time and with no hidden fees.
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabacb2b498a90196573f_666c158ae76bcbecf52d86a0_Karbon-business-p-130x130q80.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Shankar R
		strong
	StaticText Karbon has been a game changer for our business. We needed a reliable and efficient way to make international payments and Karbon has delivered. Their customer support team is always available to help and we've had no issues with the remittance process. Highly recommended!
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabadb2b498a901965871_121sad.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Aishwarya Nair
		strong
	StaticText Karbon has made our foreign outward remittance process so much simpler. Their platform is easy to use and we can track our transactions in real-time. Plus, their rates are very competitive. We're very happy with their service.
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabadb2b498a90196587a_Untitled-1.png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabaeb2b498a90196590a_unnamed%20(1).png'
	heading Nidhi Menon
		strong
	StaticText We were looking for a trustworthy foreign outward remittance service and Karbon has exceeded our expectations. Their team is professional and responsive, and they've helped us navigate complex compliance requirements. We now use Karbon for all our international transactions
	heading Frequently Asked Questions
	strong
		StaticText How does Karbon Forex help businesses send money abroad?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Is Karbon Forex a payment gateway?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText What are the fees for sending money overseas?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Is GST included in the fees?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText What documents do I need to make an outward remittance from India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Is a shop establishment certificate needed to accept international payments in India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText What currencies can I pay in?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Can I use Karbon Forex to pay contractors internationally?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Is there any holding fee for money maintained in a virtual account?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Which bank does Karbon Forex partner with for international payments to India?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Is Karbon Forex's service available for sole proprietors?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Is providing an invoice required for outward remittance?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Is a GST certificate required for outward remittance?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText How to track my outward remittance? What notification will I get when funds are transferred?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText Under what circumstances is a Chartered Accountant (CA) certificate needed for outward remittances?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText What types of transactions are restricted by the Foreign Exchange Management Act, 1999?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	strong
		StaticText What is the tax liability for outward remittance?
	image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabc30310693e26787fed_Cross%20icon.svg'
	heading Simplify Your Business Payments
	StaticText Reach out to us today!
	form Email Form
		link Get Started, url='https://www.karbonbusiness.com/contact'
	link Ground Floor, Karbon Business, 1st Stage Rd, Binnamangala, Hoysala Nagar, Indiranagar, Bengaluru, Karnataka 560038, url='https://www.karbonbusiness.com/outward-remittance-india#'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd3a219e41ad2476906_Karbon%20Business%20white%20logo.png'
	link Contact Us, url='https://www.karbonbusiness.com/outward-remittance-india#'
		strong
	link support@karboncard.com, url='https://www.karbonbusiness.com/outward-remittance-india#'
	link Connect on Whatsapp, url='https://www.karbonbusiness.com/outward-remittance-india#'
	link Schedule a demo, url='https://www.karboncard.com/contact'
	link 1-800-309-8470, url='https://www.karbonbusiness.com/outward-remittance-india#'
	link Company, url='https://www.karbonbusiness.com/outward-remittance-india#'
		strong
	link Inward, url='https://www.karbonbusiness.com/accept-international-payments-india'
		strong
	link Outward, url='https://www.karbonbusiness.com/outward-remittance-india'
		strong
	link Card, url='https://www.karbonbusiness.com/corporate-prepaid-card-by-karbon'
		strong
	link Career, url='https://www.karbonbusiness.com/about'
		strong
	link Blogs, url='https://www.karbonbusiness.com/blog'
		strong
	link Legal, url='https://www.karbonbusiness.com/outward-remittance-india#'
		strong
	link User Agreement, url='https://www.karbonbusiness.com/karbon-user-agreement'
		strong
	link Terms and Conditions, url='https://www.karbonbusiness.com/karbon-terms-conditions'
		strong
	link T&C - LIvQuik, url='https://cdn.prod.website-files.com/636cbe89ca23fd1c5fe8e188/67330b70f8b770d9e6c4b5f2_LivQuik%20%20Karbon%20T%26C%20for%20Prepaid%20Cards%20051124%20(1).pdf'
		strong
	StaticText © All rights reserved.
	link, url='https://www.facebook.com/people/Karbon-Card/100064030717569/'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd3a219e41ad24768d3_Group%2025.svg'
	link, url='https://x.com/KarbonIndia'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd2a219e41ad2476861_Vector.svg'
	link, url='https://www.youtube.com/watch?v=vND9ieTBT-g'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd3a219e41ad24768ed_Group%2026.svg'
	link, url='https://in.linkedin.com/company/karbonbusiness'
		image, url='https://cdn.prod.website-files.com/670ceff4b2fa1be44c3929a5/670fabd2a219e41ad2476839_Group%2027.svg'
```
</details>



```
RootWebArea Karbon forex, focused, url='https://karbonfx.com/signup-v2-form?utm_source=karboncard&_gl=1*oblfw0*_ga*MTMwODAxNjc5LjE3MzY0MzAyMDI.*_ga_36TTY46M1C*MTczNjQzMDIwMS4xLjEuMTczNjQzMDMwMy41OS4wLjA.'
	link Logo, url='https://www.karboncard.com/'
		image Logo, url='https://karbonfx.com/assets/logo-white-CAzwT4Zb.svg'
	StaticText ”
	StaticText Accepting international payments can be a complex and time-consuming task for businesses, given the extensive regulatory requirements involved. However, at Newton School, we have found a solution in Karbon Business
```
<details><summary>Show more</summary>

```
	image /assets/newtonschoolfounder-CDaH5i93.svg, url='https://karbonfx.com/assets/newtonschoolfounder-CDaH5i93.svg'
	heading Siddharth Maheshwari
	StaticText Founder at Newton School
	image /assets/star_review-Ccgcyb4l.svg, url='https://karbonfx.com/assets/star_review-Ccgcyb4l.svg'
	image /assets/star_review-Ccgcyb4l.svg, url='https://karbonfx.com/assets/star_review-Ccgcyb4l.svg'
	image /assets/star_review-Ccgcyb4l.svg, url='https://karbonfx.com/assets/star_review-Ccgcyb4l.svg'
	image /assets/star_review-Ccgcyb4l.svg, url='https://karbonfx.com/assets/star_review-Ccgcyb4l.svg'
	image /assets/star_review-Ccgcyb4l.svg, url='https://karbonfx.com/assets/star_review-Ccgcyb4l.svg'
	heading Enter your work email to get started
	StaticText We will send an OTP to validate your email address
	LabelText
		StaticText Enter your email address
		StaticText *
	textbox Enter your email address *, required
	image mail
	button Verify Email, disabled=True
	StaticText By registering, I agree to Karbon's
	link Terms & conditions, url='https://www.karbonfx.com/termsconditions'
	StaticText and
	link Privacy Policy, url='https://www.karbonfx.com/privacypolicy'
	StaticText Already registered?
	link Sign in, url='https://karbonfx.com/login'
```
</details>

**Reasoning for action:** My reasoning for this action is that clicking on the 'Sign Up' link is crucial for the user to begin exploring the registration process for the outward remittance services offered by Karbon. Since the user story indicates interest in understanding options and starting the registration process, this action will direct them to the relevant page or form where they can enter their information and learn more about the service they are interested in. It directly supports the user's goal of assessing their options and taking the next steps toward registration.

**Action:** click(63) # Click on the 'Sign Up' link to explore the registration process.

**Change Description:** After the user clicked the 'Sign Up' link, the browser navigated to the registration page for Karbon FX, displaying a form to enter their work email address for account setup, along with relevant branding, reviews, and links to Terms & Conditions and Privacy Policy.

**Screenshot before:****Screenshot after:**---


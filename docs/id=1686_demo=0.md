# Task

**Password Recovery Process**

As a user who forgot their password,
I recover my access to my account without frustration,
so that I can regain access to my account quickly and without needing to contact support.

**Success definition:** Given I am on the hotglue login page and have clicked the 'Forgot Password?' link
When I enter my email address and click the 'Reset Password' button
Then I should see a confirmation code field and a new password field to complete my password reset

## Trajectory

**Step 1:**

**Url (before/after):** 

https://hotglue.com/

https://hotglue.com/app

**Content (before/after):** 

```
RootWebArea Embedded iPaaS Platform to Simplify SaaS Integrations | hotglue, focused, url='https://hotglue.com/'
	alert, atomic
		StaticText 🔥 hotglue announces $4 million seed round led by 8VC!
		[163] link Read more, center=(1169,26), url='https://hotglue.com/blog/announcing-hotglues-4m-seed-round'
		[164] button Close, center=(1888,24), inner_text=×, type=button
```
<details><summary>Show more</summary>

```
	navigation
		[170] link logo, center=(442,81), url='https://hotglue.com/'
			image logo, url='https://hotglue.com/_next/static/image/src/assets/img/logos/logo-2024.15618d8bda9efbd04d4ccc15d3072279.svg'
		[173] link Log in, center=(1400,81), url='https://hotglue.com/app'
		[174] link Let's Chat, center=(1498,81), url='https://hotglue.com/demo'
		list
			listitem
				[185] button Features, center=(714,81), expanded=False, hasPopup='menu'
			listitem
				[273] button Solutions, center=(826,81), expanded=False, hasPopup='menu'
			listitem
				[311] button Resources, center=(944,81), expanded=False, hasPopup='menu'
			listitem
				[514] button Connectors, center=(1055,81)
			listitem
				[516] button Pricing, center=(1140,81)
			listitem
				[518] button Blog, center=(1203,81)
	heading Build the integrations your customers want
	paragraph
		StaticText Ship powerful integrations to your users. Avoid a lifetime of maintenance.
	[530] link Let's Chat, center=(842,456), url='https://hotglue.com/demo'
	[531] link Read the docs, center=(1058,456), url='https://docs.hotglue.com/'
	list
		listitem
			[536] link hotglue embed, center=(884,546)
				image
		listitem
			[542] link hotglue admin, center=(1039,546)
				image
	[553] link, center=(960,903), url='https://hotglue.com/#'
		image
	StaticText Watch the Demo
	image Hotglue embed screenshot, url='https://hotglue.imgix.net/landing/embed-hero-v2.png?auto=format&fit=max&w=1920'
	[556] span, center=(960,984), inner_text=Watch the Demo
	paragraph
		StaticText Trusted by leading product teams
	image
	image
	image
	image
	image
	image
	image
	image
	image
	image
	image
	image
	image
	image
	image
	image
	image
	image
	image
	image
	image
	image
	image
	image
	image
	image
	heading Build integrations for any use case
	paragraph
		StaticText Meet the code-first integration platform that gives you the flexibility you need to meet all your user requirements.
	image Dev Tools Hero, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
	heading Clean
	paragraph
		StaticText Give your users a 1-click experience. Sign-in and done.
	image Dev Tools Hero, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
	heading Open-Source
	paragraph
		StaticText All hotglue integrations are open-source. Dive deep into our connectors, write one yourself, or leverage what others have already built.
	heading Customizable
	paragraph
		StaticText Write custom transformations to adapt to any user requirements. Merge tables, filter out irrelevant data, run aggregations and more using Python libraries like pandas and gluestick natively within hotglue.
	link Read the docs, url='https://docs.hotglue.com/transformation/overview'
	image Always white labeled, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
	heading Conquer your integrations backlog
	paragraph
		StaticText From start-ups to publicly traded companies, product teams use hotglue to ship production-ready integrations at scale.
	heading Save valuable engineering bandwidth
	paragraph
		StaticText Chargebee RevRec couldn’t juggle product iteration with the constant need to maintain and update their data pipeline. With hotglue, they are able to support more integrations and dedicate more engineering resources to their core product.
	image
	heading Scale integrations at light speed
	paragraph
		StaticText Inventoro shipped 40+ integrations within their first 3 months of using hotglue.
	image
	heading Turn integrations into revenue
	paragraph
		StaticText SaaaSGrid onboarded hundreds of customers to their integrations in the course of weeks, accelerating their growth with key CRM, accounting, and billing integrations.
	image
	heading Let your integrations stack scale with you
	paragraph
		StaticText You don’t have to worry about things breaking when you close that next big deal.
	heading Highly Scalable
	paragraph
		StaticText hotglue’s ETL-based architecture makes dealing with large historical data syncs or writing in bulk dead simple. Let our infrastructure do the heavy lifting so you don’t have to.
	image Highly Scalable, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
	heading Clear Visibility
	paragraph
		StaticText Supporting mission critical integrations requires robust monitoring and tooling. Leverage webhooks, real-time logging, error notifications, and integrations with observability platforms like Datadog and Heap – all out of the box with hotglue.
	image Clear Visibility, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
	image Architecture Hero, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
	heading White Label
	paragraph
		StaticText Maintain complete control over the connection experience: use your own branding, your own workflows, even your own frontend components – your users will have a completely native experience.
	image Architecture Hero, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
	heading Enterprise Security
	paragraph
		StaticText Enterprise level security out of the box: SOC 2 Type II and GDPR compliant. Unlike our competitors, hotglue doesn’t need to store your customer data: we process the data and immediately pass it to you.
	image, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/irfan-revlock.802cb77ec42587036529e0e8003e0018.jpeg'
	paragraph
		StaticText “hotglue has made data integration a worry-free process. hotglue has cut the time it takes for us to roll out new customer integrations by 90%.”
	heading Irfan Zulfiqar
	paragraph
		StaticText Director, Product Engineering at Chargebee
	image
	heading Trusted by executives, developers, and product managers to always deliver
	image G2 Badges, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
	image Julian Rowlands Logo, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/cashboard-logo.527fdcf5022516ae99caed2024b83973.svg'
	paragraph
		StaticText hotglue continues to exceed my expectations. By using hotglue, I get to integrate with any constellation of systems that my customers care about.
	separator, orientation='horizontal'
	image Julian Rowlands, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/julian-cashboard.7108ed31a1bb566b6ac061b92f2e7a0b.png'
	paragraph
		StaticText Julian Rowlands
	paragraph
		StaticText Co-Founder
	image Michael Warshafsky Logo, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/goodkind-logo-new.109944bd2a96a6c886d9efdf8bd63626.png'
	paragraph
		StaticText For most companies, integrations tend to be a pain, but for us, it is actually an advantage now.
	separator, orientation='horizontal'
	image Michael Warshafsky, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/michael-goodkind.d4b446c11a9bce380a0d49d178f1d71e.jpeg'
	paragraph
		StaticText Michael Warshafsky
	paragraph
		StaticText CTO
	image Tomas Formanek Logo, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/inventoro-v2.c778dd0ec2c0c553aaa2911f07820bd9.svg'
	paragraph
		StaticText On average, a new integration would take us 6 months - with hotglue we have 40 different connections in 3 months. You can call hotglue a game changer.
	separator, orientation='horizontal'
	image Tomas Formanek, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/tomas-inventoro.6376a5f80553366adc5439d4bfddffbb.jpeg'
	paragraph
		StaticText Tomas Formanek
	paragraph
		StaticText CEO
	image Domingo Noriega Logo, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/bops-logo.ab7aa397a359f51508d4b296e4e8f8f7.png'
	paragraph
		StaticText hotglue has been a great catalyst in our integrations with multiple applications. I appreciate that the tool is easy to use and makes integrations seamless.
	separator, orientation='horizontal'
	image Domingo Noriega, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/domingo-bops.58cdab1163519b21adc728a38bd27278.png'
	paragraph
		StaticText Domingo Noriega
	paragraph
		StaticText Co-Founder
	image Irfan Zulfiqar Logo, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/chargebee-logo-v2.6aaa4502c6487f01ac92749f2d70cd3c.svg'
	paragraph
		StaticText Without hotglue, our team couldn't juggle product iteration with the constant need to maintain and upgrade our data pipeline.
	separator, orientation='horizontal'
	image Irfan Zulfiqar, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/irfan-revlock.802cb77ec42587036529e0e8003e0018.jpeg'
	paragraph
		StaticText Irfan Zulfiqar
	paragraph
		StaticText Director, Product Engineering
	image Julian Rowlands Logo, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/cashboard-logo.527fdcf5022516ae99caed2024b83973.svg'
	paragraph
		StaticText hotglue continues to exceed my expectations. By using hotglue, I get to integrate with any constellation of systems that my customers care about.
	separator, orientation='horizontal'
	image Julian Rowlands, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/julian-cashboard.7108ed31a1bb566b6ac061b92f2e7a0b.png'
	paragraph
		StaticText Julian Rowlands
	paragraph
		StaticText Co-Founder
	image Michael Warshafsky Logo, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/goodkind-logo-new.109944bd2a96a6c886d9efdf8bd63626.png'
	paragraph
		StaticText For most companies, integrations tend to be a pain, but for us, it is actually an advantage now.
	separator, orientation='horizontal'
	image Michael Warshafsky, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/michael-goodkind.d4b446c11a9bce380a0d49d178f1d71e.jpeg'
	paragraph
		StaticText Michael Warshafsky
	paragraph
		StaticText CTO
	image Tomas Formanek Logo, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/inventoro-v2.c778dd0ec2c0c553aaa2911f07820bd9.svg'
	paragraph
		StaticText On average, a new integration would take us 6 months - with hotglue we have 40 different connections in 3 months. You can call hotglue a game changer.
	separator, orientation='horizontal'
	image Tomas Formanek, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/tomas-inventoro.6376a5f80553366adc5439d4bfddffbb.jpeg'
	paragraph
		StaticText Tomas Formanek
	paragraph
		StaticText CEO
	image Domingo Noriega Logo, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/bops-logo.ab7aa397a359f51508d4b296e4e8f8f7.png'
	paragraph
		StaticText hotglue has been a great catalyst in our integrations with multiple applications. I appreciate that the tool is easy to use and makes integrations seamless.
	separator, orientation='horizontal'
	image Domingo Noriega, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/domingo-bops.58cdab1163519b21adc728a38bd27278.png'
	paragraph
		StaticText Domingo Noriega
	paragraph
		StaticText Co-Founder
	image Irfan Zulfiqar Logo, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/chargebee-logo-v2.6aaa4502c6487f01ac92749f2d70cd3c.svg'
	paragraph
		StaticText Without hotglue, our team couldn't juggle product iteration with the constant need to maintain and upgrade our data pipeline.
	separator, orientation='horizontal'
	image Irfan Zulfiqar, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/irfan-revlock.802cb77ec42587036529e0e8003e0018.jpeg'
	paragraph
		StaticText Irfan Zulfiqar
	paragraph
		StaticText Director, Product Engineering
	image Julian Rowlands Logo, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/cashboard-logo.527fdcf5022516ae99caed2024b83973.svg'
	paragraph
		StaticText hotglue continues to exceed my expectations. By using hotglue, I get to integrate with any constellation of systems that my customers care about.
	separator, orientation='horizontal'
	image Julian Rowlands, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/julian-cashboard.7108ed31a1bb566b6ac061b92f2e7a0b.png'
	paragraph
		StaticText Julian Rowlands
	paragraph
		StaticText Co-Founder
	image Michael Warshafsky Logo, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/goodkind-logo-new.109944bd2a96a6c886d9efdf8bd63626.png'
	paragraph
		StaticText For most companies, integrations tend to be a pain, but for us, it is actually an advantage now.
	separator, orientation='horizontal'
	image Michael Warshafsky, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/michael-goodkind.d4b446c11a9bce380a0d49d178f1d71e.jpeg'
	paragraph
		StaticText Michael Warshafsky
	paragraph
		StaticText CTO
	image Tomas Formanek Logo, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/inventoro-v2.c778dd0ec2c0c553aaa2911f07820bd9.svg'
	paragraph
		StaticText On average, a new integration would take us 6 months - with hotglue we have 40 different connections in 3 months. You can call hotglue a game changer.
	separator, orientation='horizontal'
	image Tomas Formanek, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/tomas-inventoro.6376a5f80553366adc5439d4bfddffbb.jpeg'
	paragraph
		StaticText Tomas Formanek
	paragraph
		StaticText CEO
	image Domingo Noriega Logo, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/bops-logo.ab7aa397a359f51508d4b296e4e8f8f7.png'
	paragraph
		StaticText hotglue has been a great catalyst in our integrations with multiple applications. I appreciate that the tool is easy to use and makes integrations seamless.
	separator, orientation='horizontal'
	image Domingo Noriega, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/domingo-bops.58cdab1163519b21adc728a38bd27278.png'
	paragraph
		StaticText Domingo Noriega
	paragraph
		StaticText Co-Founder
	image Irfan Zulfiqar Logo, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/chargebee-logo-v2.6aaa4502c6487f01ac92749f2d70cd3c.svg'
	paragraph
		StaticText Without hotglue, our team couldn't juggle product iteration with the constant need to maintain and upgrade our data pipeline.
	separator, orientation='horizontal'
	image Irfan Zulfiqar, url='https://hotglue.com/_next/static/image/src/assets/img/case-studies/irfan-revlock.802cb77ec42587036529e0e8003e0018.jpeg'
	paragraph
		StaticText Irfan Zulfiqar
	paragraph
		StaticText Director, Product Engineering
	heading hotglue: the embedded integration stack for high-performing B2B product teams.
	link Let's chat   →, url='https://hotglue.com/demo'
	link Read the docs, url='https://docs.hotglue.com/'
	contentinfo
		image logo, url='https://hotglue.com/_next/static/image/src/assets/img/logos/logo-white-2024.ff8f469c0f66ec72893f263f6c9f13b2.svg'
		list
			listitem
				link Home, url='https://hotglue.com/'
			listitem
				link Docs, url='https://docs.hotglue.com/'
			listitem
				link Connectors, url='https://hotglue.com/connectors'
			listitem
				link Pricing, url='https://hotglue.com/pricing'
		list
			listitem
				link Case Studies, url='https://hotglue.com/case-studies'
			listitem
				link Changelog, url='https://hotglue.com/changelog'
			listitem
				link Status, url='https://status.hotglue.xyz/'
			listitem
				link Blog, url='https://hotglue.com/blog'
		list
			listitem
				link Terms of Service, url='https://hotglue.com/terms'
			listitem
				link Privacy Policy, url='https://hotglue.com/privacy'
			listitem
				link Security, url='https://hotglue.com/security'
		list
			listitem
				link Book demo, url='https://hotglue.com/demo'
			listitem
				link Contact Us, url='mailto:hello@hotglue.xyz'
		image soc seal, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image
		paragraph
			StaticText Sales & CRM
		list
			listitem
				link Affinity, url='https://hotglue.com/connectors/affinity'
			listitem
				link Agile CRM, url='https://hotglue.com/connectors/agilecrm'
			listitem
				link Capsule, url='https://hotglue.com/connectors/capsulecrm'
			listitem
				link Close, url='https://hotglue.com/connectors/closeio'
			listitem
				link Copper, url='https://hotglue.com/connectors/copper'
			listitem
				link Follow Up Boss, url='https://hotglue.com/connectors/followupboss'
			listitem
				link Freshsales Classic, url='https://hotglue.com/connectors/freshsales'
			listitem
				link Freshsales Suite, url='https://hotglue.com/connectors/freshworks'
			listitem
				link GoHighLevel, url='https://hotglue.com/connectors/gohighlevel'
			listitem
				link HubSpot, url='https://hotglue.com/connectors/hubspot'
			listitem
				link Keap, url='https://hotglue.com/connectors/keap'
			listitem
				link Listrak, url='https://hotglue.com/connectors/listrak'
			listitem
				link Microsoft Dynamics 365, url='https://hotglue.com/connectors/dynamics'
			listitem
				link Microsoft Dynamics On-Premise, url='https://hotglue.com/connectors/dynamics-onprem'
			listitem
				link Outreach, url='https://hotglue.com/connectors/outreach'
			listitem
				link PersistIQ, url='https://hotglue.com/connectors/persistiq'
			listitem
				link Pipedrive, url='https://hotglue.com/connectors/pipedrive'
			listitem
				link Salesforce, url='https://hotglue.com/connectors/salesforce'
			listitem
				link Salesloft, url='https://hotglue.com/connectors/salesloft'
			listitem
				link Sellsy, url='https://hotglue.com/connectors/sellsy-v1'
			listitem
				link Zoho, url='https://hotglue.com/connectors/zoho'
		paragraph
			StaticText E-Commerce
		list
			listitem
				link Abicart, url='https://hotglue.com/connectors/abicart'
			listitem
				link Active Ants, url='https://hotglue.com/connectors/activeants'
			listitem
				link Amazon Seller, url='https://hotglue.com/connectors/amazon-seller'
			listitem
				link Amazon Vendor Central, url='https://hotglue.com/connectors/amazon-vendor-central'
			listitem
				link Bexio, url='https://hotglue.com/connectors/bexio'
			listitem
				link BigCommerce, url='https://hotglue.com/connectors/bigcommerce'
			listitem
				link Cin7, url='https://hotglue.com/connectors/cin7'
			listitem
				link DearSystems, url='https://hotglue.com/connectors/dearsystems'
			listitem
				link EasyEcom, url='https://hotglue.com/connectors/easyecom'
			listitem
				link Ecwid, url='https://hotglue.com/connectors/ecwid'
			listitem
				link Etsy, url='https://hotglue.com/connectors/etsy'
			listitem
				link Exact, url='https://hotglue.com/connectors/exact'
			listitem
				link Faire, url='https://hotglue.com/connectors/faire'
			listitem
				link Fishbowl Inventory, url='https://hotglue.com/connectors/fishbowl'
			listitem
				link Fortnox, url='https://hotglue.com/connectors/fortnox'
			listitem
				link Fulfil, url='https://hotglue.com/connectors/fulfil'
			listitem
				link Gambio, url='https://hotglue.com/connectors/gambio'
			listitem
				link Lightspeed (C-Series), url='https://hotglue.com/connectors/lightspeed'
			listitem
				link Linnworks, url='https://hotglue.com/connectors/linnworks'
			listitem
				link Magento 1, url='https://hotglue.com/connectors/magento-v1'
			listitem
				link Magento 2, url='https://hotglue.com/connectors/magento'
			listitem
				link Mailstep, url='https://hotglue.com/connectors/mailship'
			listitem
				link Medusa, url='https://hotglue.com/connectors/medusa'
			listitem
				link Montapacking, url='https://hotglue.com/connectors/montapacking'
			listitem
				link Netohq, url='https://hotglue.com/connectors/netohq'
			listitem
				link Odoo, url='https://hotglue.com/connectors/odoo'
			listitem
				link Ongoing WMS, url='https://hotglue.com/connectors/ongoing'
			listitem
				link Ordoro, url='https://hotglue.com/connectors/ordoro'
			listitem
				link PrestaShop, url='https://hotglue.com/connectors/prestashop'
			listitem
				link QLS, url='https://hotglue.com/connectors/qls'
			listitem
				link Quickbutik, url='https://hotglue.com/connectors/quickbutik'
			listitem
				link SHOPLAZZA, url='https://hotglue.com/connectors/shoplazza'
			listitem
				link Salesforce Commerce Cloud, url='https://hotglue.com/connectors/salesforce-commerce'
			listitem
				link Sellercloud, url='https://hotglue.com/connectors/sellercloud'
			listitem
				link ShipBob, url='https://hotglue.com/connectors/shipbob'
			listitem
				link ShipHero, url='https://hotglue.com/connectors/shiphero'
			listitem
				link Shopify, url='https://hotglue.com/connectors/shopify'
			listitem
				link Shoptet, url='https://hotglue.com/connectors/shoptet'
			listitem
				link SkuVault, url='https://hotglue.com/connectors/skuvault'
			listitem
				link Square, url='https://hotglue.com/connectors/square'
			listitem
				link Squarespace, url='https://hotglue.com/connectors/squarespace'
			listitem
				link StoreFeeder, url='https://hotglue.com/connectors/storefeeder'
			listitem
				link Unleashed, url='https://hotglue.com/connectors/unleashed'
			listitem
				link Vilkas, url='https://hotglue.com/connectors/vilkas'
			listitem
				link Wannafind, url='https://hotglue.com/connectors/wannafind'
			listitem
				link Wix, url='https://hotglue.com/connectors/wix'
			listitem
				link WooCommerce, url='https://hotglue.com/connectors/woocommerce'
			listitem
				link Bol.Com, url='https://hotglue.com/connectors/bol'
			listitem
				link Plentymarkets, url='https://hotglue.com/connectors/plentymarkets'
		paragraph
			StaticText Accounting
		list
			listitem
				link BQE, url='https://hotglue.com/connectors/bqe'
			listitem
				link FreshBooks, url='https://hotglue.com/connectors/freshbooks'
			listitem
				link Katana MRP, url='https://hotglue.com/connectors/katana'
			listitem
				link MYOB, url='https://hotglue.com/connectors/myob'
			listitem
				link Microsoft Dynamics 365 Finance, url='https://hotglue.com/connectors/dynamics-finance'
			listitem
				link Microsoft Dynamics Business Central, url='https://hotglue.com/connectors/dynamics-bc'
			listitem
				link NetSuite, url='https://hotglue.com/connectors/netsuite'
			listitem
				link Precoro, url='https://hotglue.com/connectors/precoro'
			listitem
				link QuickBooks, url='https://hotglue.com/connectors/quickbooks'
			listitem
				link QuickBooks Desktop, url='https://hotglue.com/connectors/quickbooks-desktop'
			listitem
				link Sage 50 UK, url='https://hotglue.com/connectors/sage-50'
			listitem
				link Sage Intacct, url='https://hotglue.com/connectors/intacct'
			listitem
				link Xero, url='https://hotglue.com/connectors/xero'
			listitem
				link Zoho Books, url='https://hotglue.com/connectors/zohobooks'
		paragraph
			StaticText Analytics
		list
			listitem
				link Amplitude, url='https://hotglue.com/connectors/amplitude'
			listitem
				link App Store Connect, url='https://hotglue.com/connectors/appstore'
			listitem
				link AppsFlyer, url='https://hotglue.com/connectors/appsflyer'
			listitem
				link Fullstory, url='https://hotglue.com/connectors/fullstory'
			listitem
				link Gong, url='https://hotglue.com/connectors/gong'
			listitem
				link Google Analytics 4, url='https://hotglue.com/connectors/google-analytics'
			listitem
				link Google Play, url='https://hotglue.com/connectors/google-play'
			listitem
				link Google Search Console, url='https://hotglue.com/connectors/google-search-console'
			listitem
				link Heap, url='https://hotglue.com/connectors/heap'
			listitem
				link Looker, url='https://hotglue.com/connectors/looker'
			listitem
				link Marketo, url='https://hotglue.com/connectors/marketo'
			listitem
				link Mixpanel, url='https://hotglue.com/connectors/mixpanel'
			listitem
				link Outreach, url='https://hotglue.com/connectors/outreach'
			listitem
				link PostHog, url='https://hotglue.com/connectors/posthog'
			listitem
				link PowerBI, url='https://hotglue.com/connectors/powerbi'
			listitem
				link Redash, url='https://hotglue.com/connectors/redash'
			listitem
				link Salesforce Marketing Cloud, url='https://hotglue.com/connectors/salesforce-marketing'
			listitem
				link ITunes, url='https://hotglue.com/connectors/itunes'
		paragraph
			StaticText Billing
		list
			listitem
				link Braintree, url='https://hotglue.com/connectors/braintree'
			listitem
				link Chargebee, url='https://hotglue.com/connectors/chargebee'
			listitem
				link Chargify, url='https://hotglue.com/connectors/chargify'
			listitem
				link GoCardless, url='https://hotglue.com/connectors/gocardless'
			listitem
				link Invoiced, url='https://hotglue.com/connectors/invoiced'
			listitem
				link Metronome, url='https://hotglue.com/connectors/metronome'
			listitem
				link Ordway, url='https://hotglue.com/connectors/ordway'
			listitem
				link PayPal, url='https://hotglue.com/connectors/paypal'
			listitem
				link ReCharge, url='https://hotglue.com/connectors/recharge'
			listitem
				link Recurly, url='https://hotglue.com/connectors/recurly'
			listitem
				link SaaSOptics, url='https://hotglue.com/connectors/saasoptics'
			listitem
				link Square, url='https://hotglue.com/connectors/square'
			listitem
				link Stripe, url='https://hotglue.com/connectors/stripe'
			listitem
				link Zuora, url='https://hotglue.com/connectors/zuora'
		paragraph
			StaticText Marketing
		list
			listitem
				link Campaign Monitor, url='https://hotglue.com/connectors/campaign-monitor'
			listitem
				link Contentful, url='https://hotglue.com/connectors/contentful'
			listitem
				link Delighted, url='https://hotglue.com/connectors/delighted'
			listitem
				link Iterable, url='https://hotglue.com/connectors/iterable'
			listitem
				link Judge.Me, url='https://hotglue.com/connectors/judgeme'
			listitem
				link Klaviyo, url='https://hotglue.com/connectors/klaviyo'
			listitem
				link Mailchimp, url='https://hotglue.com/connectors/mailchimp'
			listitem
				link Mailshake, url='https://hotglue.com/connectors/mailshake'
			listitem
				link Omnisend, url='https://hotglue.com/connectors/omnisend'
			listitem
				link Outreach, url='https://hotglue.com/connectors/outreach'
			listitem
				link Pardot, url='https://hotglue.com/connectors/pardot'
			listitem
				link Reviews.Io, url='https://hotglue.com/connectors/reviewsio'
			listitem
				link Stamped, url='https://hotglue.com/connectors/stamped'
			listitem
				link Trustpilot, url='https://hotglue.com/connectors/trustpilot'
			listitem
				link Yotpo, url='https://hotglue.com/connectors/yotpo'
		separator, orientation='horizontal'
		StaticText © 2024 hotglue
		list
			listitem
				link , url='https://github.com/hotgluexyz'
			listitem
				link , url='https://join.slack.com/t/hotglue-workspace/shared_invite/zt-rg910ue9-2Y~2jdpZz3Q2eSda2dl2Rw'
			listitem
				link, url='https://twitter.com/hotgluexyz'
			listitem
				link , url='https://www.linkedin.com/company/hotglue/'
	alert, atomic
	[1429] button Open chat window, center=(1868,1028), title=Open chat window
		image
```
</details>



```
RootWebArea hotglue - Admin Panel, focused, url='https://hotglue.com/app'
	main
		image logo, url='https://hotglue.com/_next/static/image/src/assets/img/logos/logo-primary-alt.f1281a1a9dc5c505d0f838226f27fe11.svg'
		heading Login to your Account
		paragraph
```
<details><summary>Show more</summary>

```
			StaticText Need an account?
			[1462] link Let's chat, center=(176,234), url='https://hotglue.com/demo'
		LabelText
			StaticText Email
		[1470] textbox, center=(388,309), autocomplete=username, contenteditable=True, focused, type=text
		LabelText
			StaticText Password
		[1476] textbox, center=(373,359), autocomplete=current-password, contenteditable=True, type=password
		[1478] button toggle password visibility, center=(599,359), type=button
		[1482] paragraph, center=(320,407), inner_text=Forgot Password?
			StaticText Forgot Password?
		[1483] button Log In, center=(320,467), type=submit
		paragraph
			[1487] link Home, center=(49,671), url='https://hotglue.xyz/'
			[1488] link Pricing, center=(106,671), url='https://hotglue.xyz/pricing'
			[1489] link Contact, center=(170,671), url='https://hotglue.xyz/demo'
			[1490] link Terms, center=(231,671), url='https://hotglue.xyz/terms'
			[1491] link Privacy, center=(290,671), url='https://hotglue.xyz/privacy'
		image logo, url='https://hotglue.com/_next/static/image/src/assets/img/illustrations/login-illustration.aa236d336a5ae028a600715025eaf9bb.svg'
		heading Build integrations your users will love
		paragraph
			StaticText Build scalable, native integrations with the data sources your customers use 10x faster.
	alert, atomic
		StaticText hotglue - Admin Panel
	[1429] button Open chat window, center=(1868,1028), title=Open chat window
		image
```
</details>

**Reasoning for action:** Since the user story requires recovering access to an account via the password reset process, the first step is to get to the relevant login page. By clicking the 'Log in' link, I am effectively heading to the login screen where the user can initiate the password recovery process by finding and clicking on the 'Forgot Password?' link.

**Action:** click(173) # Click on the 'Log in' link to explore the login functionality.

**Change Description:** After clicking the 'Log in' link, the browser state changed to the hotglue Admin Panel, shifting the focus from the main landing page to a login interface that prompts users for their email and password. The header now displays 'Login to your Account,' and additional interactive elements for account access and support have become available.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://hotglue.com/app

https://hotglue.com/app

**Content (before/after):** 

```
RootWebArea hotglue - Admin Panel, focused, url='https://hotglue.com/app'
	main
		image logo, url='https://hotglue.com/_next/static/image/src/assets/img/logos/logo-primary-alt.f1281a1a9dc5c505d0f838226f27fe11.svg'
		heading Login to your Account
		paragraph
```
<details><summary>Show more</summary>

```
			StaticText Need an account?
			[1462] link Let's chat, center=(176,234), url='https://hotglue.com/demo'
		LabelText
			StaticText Email
		[1470] textbox, center=(388,309), autocomplete=username, contenteditable=True, focused, type=text
		LabelText
			StaticText Password
		[1476] textbox, center=(373,359), autocomplete=current-password, contenteditable=True, type=password
		[1478] button toggle password visibility, center=(599,359), type=button
		[1482] paragraph, center=(320,407), inner_text=Forgot Password?
			StaticText Forgot Password?
		[1483] button Log In, center=(320,467), type=submit
		paragraph
			[1487] link Home, center=(49,671), url='https://hotglue.xyz/'
			[1488] link Pricing, center=(106,671), url='https://hotglue.xyz/pricing'
			[1489] link Contact, center=(170,671), url='https://hotglue.xyz/demo'
			[1490] link Terms, center=(231,671), url='https://hotglue.xyz/terms'
			[1491] link Privacy, center=(290,671), url='https://hotglue.xyz/privacy'
		image logo, url='https://hotglue.com/_next/static/image/src/assets/img/illustrations/login-illustration.aa236d336a5ae028a600715025eaf9bb.svg'
		heading Build integrations your users will love
		paragraph
			StaticText Build scalable, native integrations with the data sources your customers use 10x faster.
	alert, atomic
		StaticText hotglue - Admin Panel
	[1429] button Open chat window, center=(1868,1028), title=Open chat window
		image
```
</details>



```
RootWebArea hotglue - Admin Panel, focused, url='https://hotglue.com/app'
	main
		image logo, url='https://hotglue.com/_next/static/image/src/assets/img/logos/logo-primary-alt.f1281a1a9dc5c505d0f838226f27fe11.svg'
		paragraph
			[1505] link Back to Log In, center=(75,198)
```
<details><summary>Show more</summary>

```
		heading Forgot Password
		paragraph
			StaticText Enter the email address associated with your account, and we’ll email you a link to reset your password.
		LabelText
			StaticText Email
		[1515] textbox, center=(257,371), autocomplete=username, contenteditable=True, focused, type=text
		[1517] button Reset Password, center=(320,447), type=button
		paragraph
			[1521] link Home, center=(49,650), url='https://hotglue.xyz/'
			[1522] link Pricing, center=(106,650), url='https://hotglue.xyz/pricing'
			[1523] link Contact, center=(170,650), url='https://hotglue.xyz/demo'
			[1524] link Terms, center=(231,650), url='https://hotglue.xyz/terms'
			[1525] link Privacy, center=(290,650), url='https://hotglue.xyz/privacy'
		image logo, url='https://hotglue.com/_next/static/image/src/assets/img/illustrations/login-illustration.aa236d336a5ae028a600715025eaf9bb.svg'
		heading Build integrations your users will love
		paragraph
			StaticText Build scalable, native integrations with the data sources your customers use 10x faster.
	alert, atomic
		StaticText hotglue - Admin Panel
	[1429] button Open chat window, center=(1868,1028), title=Open chat window
		image
```
</details>

**Reasoning for action:** By clicking on the 'Forgot Password?' link, I am initiating the password recovery process. This step is crucial as it allows me to access the next part of the flow, where I will be able to enter my email address and request a password reset. This directly aligns with the user's goal of regaining access to their account without unnecessary difficulties.

**Action:** click(1482) # Click on the 'Forgot Password?' link to explore password recovery options.

**Change Description:** After clicking the 'Forgot Password?' link, the browser navigated to a password recovery page where the heading changed to 'Forgot Password', and a new paragraph was added prompting the user to enter their email for a password reset. Additionally, a reset password button was introduced, replacing the previous login form.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://hotglue.com/app

https://hotglue.com/app

**Content (before/after):** 

```
RootWebArea hotglue - Admin Panel, focused, url='https://hotglue.com/app'
	main
		image logo, url='https://hotglue.com/_next/static/image/src/assets/img/logos/logo-primary-alt.f1281a1a9dc5c505d0f838226f27fe11.svg'
		paragraph
			[1505] link Back to Log In, center=(75,198)
```
<details><summary>Show more</summary>

```
		heading Forgot Password
		paragraph
			StaticText Enter the email address associated with your account, and we’ll email you a link to reset your password.
		LabelText
			StaticText Email
		[1515] textbox, center=(257,371), autocomplete=username, contenteditable=True, focused, type=text
		[1517] button Reset Password, center=(320,447), type=button
		paragraph
			[1521] link Home, center=(49,650), url='https://hotglue.xyz/'
			[1522] link Pricing, center=(106,650), url='https://hotglue.xyz/pricing'
			[1523] link Contact, center=(170,650), url='https://hotglue.xyz/demo'
			[1524] link Terms, center=(231,650), url='https://hotglue.xyz/terms'
			[1525] link Privacy, center=(290,650), url='https://hotglue.xyz/privacy'
		image logo, url='https://hotglue.com/_next/static/image/src/assets/img/illustrations/login-illustration.aa236d336a5ae028a600715025eaf9bb.svg'
		heading Build integrations your users will love
		paragraph
			StaticText Build scalable, native integrations with the data sources your customers use 10x faster.
	alert, atomic
		StaticText hotglue - Admin Panel
	[1429] button Open chat window, center=(1868,1028), title=Open chat window
		image
```
</details>



```
RootWebArea hotglue - Admin Panel, focused, url='https://hotglue.com/app'
	main
		image logo, url='https://hotglue.com/_next/static/image/src/assets/img/logos/logo-primary-alt.f1281a1a9dc5c505d0f838226f27fe11.svg'
		paragraph
			[1505] link Back to Log In, center=(75,198)
```
<details><summary>Show more</summary>

```
		heading Forgot Password
		paragraph
			StaticText Enter the email address associated with your account, and we’ll email you a link to reset your password.
		LabelText
			StaticText Confirmation Code
		[1515] textbox, center=(388,371), autocomplete=off, contenteditable=True, type=text
		LabelText
			StaticText New Password
		[1536] textbox, center=(373,434), autocomplete=new-password, contenteditable=True, type=password
		[1538] button toggle password visibility, center=(599,434), type=button
		[1517] button Save New Password, center=(320,510), focused, type=button
		paragraph
			strong
				StaticText We just sent you a code.
			StaticText Once you get it go ahead and provide a new password for your account.
		paragraph
			[1521] link Home, center=(49,764), url='https://hotglue.xyz/'
			[1522] link Pricing, center=(106,764), url='https://hotglue.xyz/pricing'
			[1523] link Contact, center=(170,764), url='https://hotglue.xyz/demo'
			[1524] link Terms, center=(231,764), url='https://hotglue.xyz/terms'
			[1525] link Privacy, center=(290,764), url='https://hotglue.xyz/privacy'
		image logo, url='https://hotglue.com/_next/static/image/src/assets/img/illustrations/login-illustration.aa236d336a5ae028a600715025eaf9bb.svg'
		heading Build integrations your users will love
		paragraph
			StaticText Build scalable, native integrations with the data sources your customers use 10x faster.
	alert, atomic
		StaticText hotglue - Admin Panel
	[1429] button Open chat window, center=(1868,1028), title=Open chat window
		image
```
</details>

**Reasoning for action:** My reasoning for filling in the textbox with the email address is that it is the required input for triggering the password reset process. By doing this, I complete the first part of the user's interactions as defined in the acceptance criteria. Following that, clicking the 'Reset Password' button is necessary to submit the email address and initiate the next step in the password recovery process. This action is what leads to the anticipated output where I should see the confirmation code field and a new password field, thus progressing me closer to the goal of regaining account access.

**Action:** fill(1515, 'user@example.com') # Fill in a sample email address for password reset
click(1517) # Click on the 'Reset Password' button to initiate the password reset process.

**Change Description:** The email address field was filled with 'user@example.com', and after clicking the 'Reset Password' button, the interface changed to display a confirmation code field and a new password field, indicating that a password reset process has been initiated.

**Screenshot before:****Screenshot after:**---


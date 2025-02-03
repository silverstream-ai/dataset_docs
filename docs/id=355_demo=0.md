# Task

**Explore Heat Pump Products**

As a potential customer,
I explore the offerings related to heat pumps,
so that I can find a suitable product and easily book a demo.

**Success definition:** Given I am on the Autarc energy homepage and can see the Products button
When I click on the Products button and the products menu expands, then I select the 'Heat pump check' option
Then I should be taken to a detailed page about the Heat pump check that includes a booking form for a demo and information on various companies using the service.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.autarc.energy/en

https://www.autarc.energy/en

**Content (before/after):** 

```
RootWebArea autarc – Die Wärmepumpen-Software, focused, url='https://www.autarc.energy/en'
	dialog Diese Webseite verwendet Cookies, modal=True
		image Logo, url='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAC4AAAAuCAYAAABXuSs3AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAQBSURBVGhD7VpJKLZtFDYskKlkzpjMIUOGQoqIlIUFFmYZEskQkj1CGUNYUCKhLAylzAvCghA+Q1aGiJAI53edz/28ff/n3+npf+s5dfXe59znvs/1nPucs0HjU3594kbNAM4aD58gNQM48xd8t/l/BjgrxOWEQlxuKMTlhkJcbijE5YZCXG4oxOWGQpyRmJhIdXV1FBAQ8O3+D+JniQ8MDBAkLS3t2/0fxN/EY2JiaHx8nFZWVqi7u5t8fX3ZHhcXR0NDQxQbGyv5GhsbM9nm5mZqbGyks7MzJr6xsUGjo6NkYWFBJiYmVF9fz/dNTU1RTk4On9XS0qLOzk6O4e/vT/39/TQzM0OGhobk4uJCHR0dND8/T2NjY5SRkSHF/MKfxPPy8jjwy8sLbW9v8/r5+ZlcXV2psLCQ9aqqKukCa2trtl1fX9Pq6iq9vb2x/vr6So+PjxQfH0/7+/ts293dpZubG143NTWRpqYm3d/fs/7x8cG/7+/vVFpaKtkfHh74F9Lb2yvF/YSKuK6uLh0eHnIgAwMDdkhKSuJDbW1tlJyczOuSkhLpAisrKw52enrK5/v6+tgnPz+f9ZqaGrq7u6Pc3FzpzMnJCfs4OTnR3t4er4+Ojig4OJgzfXV1xbaCggLS09Mjd3d3Oj8/Z1tgYKC4R0VcW1ubjIyMKCoqiqqrq/mpt7a2+MDw8DClpqbyuqysTCIB4hAQh97S0sK6qHEdHR1yc3Oj9PR06unpodnZWc4mMuzn58evAEFM+Ht5ebG+vr4uxQBsbGwoJCSEzMzMhE1FHECGhCAby8vLvB4ZGWEyEDyl8EfWIMfHx6y3trayLurY29ub9yAop8XFRbq8vOSSAvGDgwP+CPQC/CMjI9l3cnJSivEfUBEX9XpxccENAlt0dDTbkPHs7Gxeo2mwB5SXl7MNJQa9vb2d9czMTNYHBwdZz8rKks7AF4KGxBr9YG5uznv29va8h14QNqC2tpYWFhYoNDRU2FTE8dUQNFVCQgKlpKTQ7e0t2yYmJvipIAiE5hJlAREZLyoqYh2NXVFRQUtLS6zjgzCtcI8Q1DTOIfumpqYSSUwZCHqtsrJS0p+enji5X34q4kBxcTFPESF4Msjc3BzvNzQ0SBMAgkvR+Wg4TAl9fX2anp7+2v3dpGtra1/a7zG5s7PD66CgIC4VxMPIFBzQF11dXewjZHNzk3x8fCSfT/xJHLCzs6Pw8HBydHRk3dPTkxwcHKR9jMaIiAiytbVlHc3n7OzMxIUPyiAsLIzXmNfILgDd0tKSPDw8eGKgR3Aeg0GcFUBM8PgXYYG/iasJFOJyQyEuNxTickMhLjcU4nJDIS43FOJyg4mr7Z/E1fCfEDR+/QN5VWLLOegHAwAAAABJRU5ErkJggg=='
		[71] link Logo - opens in a new window, center=(1249,304), url='https://www.cookiebot.com/de/was-steckt-hinter-powered-by-cookiebot/'
			image
```
<details><summary>Show more</summary>

```
		[73] button Banner schließen, center=(1380,304)
			image
		tablist, orientation='horizontal'
			[80] tab Zustimmung, center=(650,375), selected=True
			[82] tab Details, center=(930,375), selected=False
			[86] tab Über Cookies, center=(1210,375), selected=False
		tabpanel Zustimmung
			heading Diese Webseite verwendet Cookies
			group Consent Selection
				Legend
				LabelText
					strong
						StaticText Notwendig
				checkbox Notwendig, checked='true', disabled=True
				LabelText
					[113] strong, center=(847,639), inner_text=Präferenzen
						StaticText Präferenzen
				[115] checkbox Präferenzen, center=(847,679), checked=, contenteditable=True, type=checkbox
				LabelText
					[119] strong, center=(1072,639), inner_text=Statistiken
						StaticText Statistiken
				[121] checkbox Statistiken, center=(1072,679), checked=, contenteditable=True, type=checkbox
				LabelText
					[125] strong, center=(1298,639), inner_text=Marketing
						StaticText Marketing
				[127] checkbox Marketing, center=(1298,679), checked=, contenteditable=True, type=checkbox
		[999] button Ablehnen, center=(672,763)
		[1000] button Auswahl erlauben, center=(960,763)
		[1003] button Alle zulassen, center=(1248,763)
	banner
		[1012] link, center=(87,45), url='https://www.autarc.energy/en'
			image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/655bf2270fe58d910009ed6b_autrc-logo.png'
		navigation
			[1049] button Products, center=(197,45), expanded=False, hasPopup='menu'
			[1088] button Solutions, center=(291,45), expanded=False, hasPopup='menu'
			[1110] link Customers, center=(392,45), url='https://www.autarc.energy/en/kunden/kunden'
			[1112] button Knowledge, center=(499,45), expanded=False, hasPopup='menu'
			[1126] button About us, center=(600,45), expanded=False, hasPopup='menu'
			[1156] link Jobs, center=(678,45), url='https://www.autarc.energy/en/jobs'
			[1157] link Rates, center=(744,45), url='https://www.autarc.energy/en/preise'
			article
				[1160] link WhatsApp Chat, center=(1613,45), url='https://wa.me/4915792312671'
					image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6732237bf724025079599592_whatsapp-logo-grey.png'
				[1163] link Login, center=(1732,45), url='https://app.autarc.energy/login'
				[1164] link Book a demo, center=(1826,45), url='https://www.autarc.energy/en/demo-buchen'
	[1286] link künstliche Intelligenz bei autarc energy Autarc AI — app out, scan on, heat load in 15 minutes Pfeil nach rechts, center=(960,210), inner_text=Autarc AI — app out, scan on, heat load in 15 minutes, url='https://www.autarc.energy/en/produkte/lidar-scan'
		image künstliche Intelligenz bei autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65691ad146aa7fb03353521b_sparkle.svg'
		image Pfeil nach rechts, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65691afb341494ef5e90d89f_arrowRight.svg'
	heading autarc is a better way
	heading to plan heat pumps
	StaticText Discover the new standard for sales and planning of heat pumps. Heat load, hydraulic balancing (B) and funding application in just a few clicks.
	form Email Form Start
		textbox Business email address*, required
		button Book a demo
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
	StaticText 14-day free trial
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
	StaticText Set up in just 3 minutes
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
	StaticText Can be canceled at any time
	image autarc home screen, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b313d2e56f36107c33e_autarc-home-screen-1-min-p-1080.png'
	StaticText We are a member of
	image Bunderverband Wärmepumpe e.V. autarc energy Software Planung wärmepumpe hydraulischer abgleich, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/651191ce20e01ee0dab72cf7_Logo_BWP_gross.png'
	image DIN-logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65e9aa81ef1b78df023333d4_DIN-mitgliedslogo-blau-autarc%20energy-p-500.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/66c222175ebc6be23eb42a83_EE_EnergieeffizienzExperten_Logo_M-removebg-p-500.webp'
	StaticText Software for the best heating engineers.
	StaticText From the next generation to established businesses, 250+ customers already trust us.
	image Vinci Unternehmenslogo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6391e678268622418d2bfeb9_Vinci.png'
	image Daume Gruppe Unternehmenslogo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6391e67829871fbe96bc762b_Daume.png'
	image Theodor Bergmann Berlin, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b38e65330789e606fe27_Theodor%20Bergmann%20Berlin.svg'
	image Vattenfall, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b38fbf4bdd782aa5eac1_Vattenfall.svg'
	image mf mercedöl, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b48810e117cbe394c07b_mf%20mercedoil%20gmbh%20berlin.svg'
	image Koster, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b488fd4ac778e955fc38_koster%20gmbh%20berlin%20heizung.svg'
	image Hörmann Haustechnike, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646269795ed5193ea3b87531_hoermann-haustechnik%201.svg'
	image WagEnergie aus Duderstadt, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646269792dc26a20312e9008_logo_wagenergie_rgb-removebg-preview%201.svg'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/66cffa26a6addc029265bd2f_nuuEnergy_logo.png'
	image Klaus Klein Design Bad, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d54581270477c9dbd8_Klaus%20Klein%20Gmbh.svg'
	image Team Steffen, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d469b7a5456ecd20e9_Team%20Steffen.svg'
	image Thomas Mehner Haustechnik Unternehmenslogo Braunschweig, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/63c69c6f3159457dc6248ccd_Mehner.svg'
	image Berner Elektrotechnik, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646280cc96faa3e03621627f_Berner%20Elektrotechnik.svg'
	StaticText Benefits
	heading Why autarc?
	image Uhr Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699c018f5de07a866d2440_Group%20482166.svg'
	StaticText The fastest way to data
	StaticText With autarc, you can quickly access via
	StaticText 600 relevant house data
	StaticText thanks to artificial intelligence.
	StaticText In just 10 minutes
	StaticText enter all necessary information, supplemented with pictures at the customer's site. This step can also be taken over by inexperienced colleagues.
	image Sicherheit Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699c01f9738c8487d50db2_Group%20482167.svg'
	StaticText Higher offer quality
	StaticText Through the data
	StaticText Does quality increase
	StaticText your offers
	StaticText by 90%
	StaticText . With precise and comprehensive information, you can offer tailor-made solutions. For you, this means:
	StaticText more successful deals
	StaticText And a
	StaticText quick contract processing
	StaticText .
	image Schloss Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699c0166880e76db41fee8_Group%20482168.svg'
	StaticText No plant failures
	StaticText Wrongly dimensioned or timed heat pumps are a thing of the past. Our precise analysis enables a
	StaticText optimal system planning
	StaticText . The result is powerful, efficient heat pumps that are precisely tailored to the needs of your customers. For you, that means:
	StaticText fewer plant failures
	StaticText and therefore
	StaticText happier customers
	StaticText .
	StaticText Known from
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731bac75b8721c35ff4e_image%201183-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731b3d28cd7e20c5abab_image%201182-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731bc2a0f1867d6fceff_image%201181-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731b50ec48404304f555_image%201186-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731b08a0892e1a0b8b00_image%201187-min.png'
	StaticText Solution
	heading autarc has what you need.
	heading The most efficient planning and sales process.
	image Nummer 1, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699fb7f77c77287929fea5_Group%20482169.svg'
	StaticText Heat pump check and customer portal
	StaticText Quick aptitude test, modern communication
	StaticText In
	StaticText few minutes
	StaticText Does your customer find out whether a heat pump is suitable for their home. He then gets access to
	StaticText your customer portal
	StaticText , the hub for all communication. From the
	StaticText initial assessment
	StaticText up to the final installation
	StaticText keep your customers up to date.
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Quick aptitude test in just 3 minutes
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customizable interface
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Forecast for higher conversion
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Accessible 24/7 from all devices
	image Wärmepumpen check autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b3162da9b852b633038_autarc-home-screen-2-min.png'
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText 1 hour time saving
	StaticText Your customer provides you with important information for your calculations
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText +75%
	StaticText Higher conversion of requests
	image Nummer 2, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699fb6909cb9881fef548c_Group%20482170.svg'
	StaticText On-site visit
	StaticText Input and calculation in one step
	StaticText In just 15 minutes
	StaticText Do you get a result for
	StaticText Heat load, sound emissions, heating surface design
	StaticText and
	StaticText hydraulic balancing (B)
	StaticText . In addition, a suitable offer is generated. Means for you:
	StaticText less time for data recording
	StaticText , more time to sell the plant.
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Mobile availability on tablet/smartphone
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Room capture with 3D scanner
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Automatic radiator detection (beta)
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText All calculations in one pdf. Report
	image LiDAR Scan für Heizlast und hydraulischer abgleich von autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b3163cd25a8d73ccae9_autarc-home-screen-3-min.png'
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText 600+
	StaticText Data for the best offers and plant planning
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText >10 hours time saving
	StaticText For heat load, layout, sound testing, supply and hydraulic adjustment
	image Nummer 3, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699fb7415c82498e334224_Group%20482171.svg'
	StaticText Specialist partner portal
	StaticText One software for everything related to the heat pump
	StaticText Everything is managed centrally in the specialist partner portal. It allows the generation of
	StaticText Reports
	StaticText , processing of
	StaticText Funding
	StaticText , the creation of
	StaticText VDZ forms
	StaticText , the
	StaticText startup
	StaticText of plants and
	StaticText maintenancies
	StaticText .
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Collaborate with teammates
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Generating heat pump reports
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Planning of systems including heating surfaces
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Funding and VDZ forms
	image Screen von der Projektübersicht der autarc energy software, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b314ee49de84aad0baa_autarc-home-screen-4-min.png'
	Iframe Auf Trustpilot veröffentlichte Kundenbewertungen
		RootWebArea Trustpilot Custom Widget, url='https://widget.trustpilot.com/trustboxes/5419b6a8b0d04a076446a9ad/index.html?templateId=5419b6a8b0d04a076446a9ad&businessunitId=63ca54b68fcd1c82bbeabefb#locale=de-DE&styleHeight=50px&styleWidth=100%25&theme=light&minReviewCount=0&styleAlignment=center'
			link Sehen Sie unsere 38 Bewertungen auf Trustpilot, url='https://de.trustpilot.com/review/autarc.energy?utm_medium=trustbox&utm_source=MicroReviewCount'
				[a12] strong, center=(919,5736)
					StaticText 38
				[a16] image Trustpilot, center=(1084,5734)
	StaticText Work together
	StaticText 10x faster.
	StaticText autarc was developed so that you and your colleagues get the most out of sales and planning for heating installations.
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	image iPhone Screen autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a8667dd7fe207f4da02c_autarc-Screen-5.svg'
	image Angebotstool autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a8a36a1ea6c7b7f32d39_autarc-home-screen-5-p-800.png'
	image Wärmepumpen Report autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a8a305876884a29298b2_autarc-home-screen-5-1-p-800.png'
	StaticText Meets all requirements
	StaticText And more
	StaticText autarc has what you need and is therefore the leading provider of heat pump planning.
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	StaticText requests
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Overview of all inquiries
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText High conversion prediction
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Share projects with customers
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customizable interface
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Create customer file
	StaticText requests
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText All climate data
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heat load calculation
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heating surface design
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText sound emissions
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Indicative price offers
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Funding
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText manufacturer's instructions
	StaticText installation
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Auto Inspection of delivery measures
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customizable checklists
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Online orders
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Material extracts
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Foundation instructions
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Annual performance figure
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Safety distances
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Installation site with augmented reality
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText valve settings
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText pump delivery heights
	StaticText furtherance
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Review of available funding
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Interface to BAFA
	StaticText + more
	StaticText “Since we've been using autarc, we've been driving
	StaticText We no longer go directly to every customer
	StaticText . Through the
	StaticText Qualification
	StaticText During the heat pump check, we only deal with customers who are really interested in a heat pump.”
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569c64166880e76db5e38ca_Ellipse%20392.svg'
	StaticText Philip Walter
	StaticText Managing Director
	StaticText Thomas Mehner Haustechnik
	StaticText Our guide
	StaticText The ultimate guide to
	StaticText Heat pump house visits 2024 are here!
	link Learn more, url='https://www.autarc.energy/en/leitfaden'
	image autarc Leitfaden für Wärmepumpen Hausbesuche, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/657499757d7f5fa4e98b8022_Group%20482127.png'
	StaticText Leading manufacturers
	StaticText Works with all manufacturers and types
	StaticText of heat pumps
	link Learn more, url='https://www.autarc.energy/en/wissen'
	image Übersicht verfügbarer Hersteller in der autarc energy software, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569d79d08885f64dec7e0fa_Group%20482173.svg'
	StaticText Our software works with all manufacturers.
	StaticText You can find a small selection here.
	image Danfoss, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d582485650889931f1_Danfoss.svg'
	image IMI Heimeier, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d54eaafc68f6aa619c_IMI%20Heimeier.svg'
	image Oventrop, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d5fb6ee1d0f1b04b25_Oventrop.svg'
	image Resideo Honeywell, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64628132380e5ecaac062cd8_Resideo%20Honeywell.svg'
	image Viessmann, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b66ad7095943cebd8e6f_Viessmann.svg'
	image Vaillant Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65c8695df776be3aa90_Vaillant.svg'
	image Stiebel Eltron Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65c121acb6a85783b4a_Stiebel%20Eltron.svg'
	image Daikin Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65c4793c63f2747af30_Daikin.svg'
	image Buderus Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65cfc6d39159e072da0_Buderus.svg'
	image Samsung Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65cfc6d39159e072dac_Samsung.svg'
	image Bosch Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65d97eba92836ed04fc_Bosch.svg'
	StaticText Ready to start?
	StaticText Discover all our solutions or book a demo to test autarc free of charge.
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	image Sicherheit Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8318594f792728e68_disputeProtection.svg'
	StaticText 100% DIN compliant
	StaticText We comply with all standards in our calculations
	image Kalender Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8a072dc7ea8656caf_calendar.svg'
	StaticText 24/7 available
	StaticText Accessible from all devices throughout the year
	image Person Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8f538c85e3faedc85_person.svg'
	StaticText Personal contact
	StaticText We take time to answer your concerns, no question remains unanswered
	StaticText Testimonials
	heading What our customers say.
	heading How Daume plans 270 heat pumps per year using Autarc.
	Iframe Daume GmbH über Ihre Erfahrung mit der einfachsten Planungssoftware für Wärmepumpen | autarc
		RootWebArea Daume GmbH über Ihre Erfahrung mit der einfachsten Planungssoftware für Wärmepumpen | autarc - YouTube, url='https://www.youtube.com/embed/mEkOYnmscdw?rel=0&controls=1&autoplay=1&mute=1&start=0'
			[b26] Video, center=(960,12134)
			generic, atomic
			slider Seek slider value='0', orientation='horizontal'
			group
				slider Click or scroll the panel for the precise seeking. value='0', orientation='horizontal'
			[b409] button Pause (k), center=(395,12451)
				image
			[b414] button Unmute (m), center=(438,12451)
				image
			slider Volume value='100', orientation='horizontal'
				group
			StaticText 0:00
			StaticText /
			StaticText 3:30
			[b430] button Vorstellung Daume GmbH, center=(942,12451)
				generic Vorstellung Daume GmbH
			[b436] button Subtitles/closed captions unavailable, center=(1381,12451)
				image
			[b438] button Settings, center=(1421,12451), expanded=False, hasPopup='menu'
				image
			[b440] link Watch on YouTube, center=(1474,12451), url='https://www.youtube.com/watch?v=mEkOYnmscdw'
			[b447] button Full screen (f), center=(1528,12451)
				image
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText Premium license
	StaticText Everything you need to make your business efficient.
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText Products in use
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heat pump check
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customer portal
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText iOS app for iPad
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heat pump report
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText >270 heat pumps
	StaticText Install thumbs per year and plan them with self-tarc.
	StaticText Your potential
	heading Calculate your savings potential.
	heading With autarc, we make you even more efficient.
	link Available soon, url='https://www.autarc.energy/en#'
	StaticText “With autarc, we can implement method B in
	StaticText Create under 1 hour
	StaticText , much faster than our previous solutions. We can see that our customers are impressed that everything comes from a single source.”
	image Portrait Stefan Möllenhoff Vinci Energies, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569ff3c2615a40b667d1a1d_Group%20482130.svg'
	StaticText Stefan Möllenhoff
	StaticText Executive
	StaticText Vinci Energies
	StaticText Would you like to stay up to date?
	StaticText Sign up for our newsletter
	form Newsletter Form
		textbox First name *, required
		textbox Last name *, required
		textbox Business email address*, required
		button Subscribe
	StaticText Frequently asked questions
	StaticText We can help answer questions and resolve issues. Have a look at our frequently asked questions, send us a message or give us a call.
	link Learn more, url='https://hilfe.autarc.energy/de/'
	image Bunderverband Wärmepumpe e.V. autarc energy Software Planung wärmepumpe hydraulischer abgleich, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/651191ce20e01ee0dab72cf7_Logo_BWP_gross.png'
	image INVEST Förderung BAFA für autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65085835fa950284eb14fffa_INVEST_Logo_URL_rote_URL_RZ-p-500.png'
	image European Social Fund, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/63e298e1d376b73610c0daee_Google%20form%20cover%20-%20Accelerator%20team-p-500.png'
	link Autarc Logo, url='https://www.autarc.energy/en'
		image Autarc Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6339884edcb06d6ae77fe900_autarc%20logo_black.svg'
	link, url='https://wa.me/4915792312671'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6732224a26847515db644115_whatsapp.svg'
	link, url='https://apps.apple.com/app/autarc/id6464311183'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/656a05f75545a6a3e2b24fab_Group%20482167.svg'
	link, url='https://app.autarc.energy/login'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/656a05f7d8a01b8c1b94e2a4_Group%20482166.svg'
	button Language, expanded=False, hasPopup='menu'
	StaticText PRODUCTS
	link Heat pump check, url='https://www.autarc.energy/en/produkte/warmepumpen-check'
	link Customer portal, url='https://www.autarc.energy/en/produkte/kunden-portal'
	link Quotation tool, url='https://www.autarc.energy/en/produkte/angebotstool'
	link LiDAR scan, url='https://www.autarc.energy/en/produkte/lidar-scan'
	link Heat load calculation, url='https://www.autarc.energy/en/produkte/heizlastberechnung'
	link Hydraulic balancing, url='https://www.autarc.energy/en/produkte/hydraulischer-abgleich-b'
	link Heating surface design, url='https://www.autarc.energy/en/produkte/heizflachenauslegung'
	link Funding service, url='https://www.autarc.energy/en/produkte/foerderhilfe'
	StaticText INTEGRATIONS
	link Craftsman software, url='https://www.autarc.energy/en/produkte/handwerkersoftware'
	link CRM, url='https://www.autarc.energy/en/produkte/crm'
	StaticText SOCIAL MEDIA
	link Linkedin, url='https://www.linkedin.com/company/autarc-energy/'
	link facebook, url='https://www.facebook.com/autarcenergy'
	link instagram, url='https://www.instagram.com/autarcenergy/'
	link YouTube, url='https://www.youtube.com/@getautarc'
	StaticText PRODUCTS
	link For young companies, url='https://www.autarc.energy/en/loesungen/fuer-junge-firmen'
	link For established companies, url='https://www.autarc.energy/en/loesungen/fuer-etablierte-unternehmen'
	link For energy suppliers, url='https://www.autarc.energy/en/loesungen/fur-energieversorger-stadtwerke'
	link For energy consultants, url='https://www.autarc.energy/en/loesungen/fuer-energieberater-ingenieurbueros'
	link For solar engineers/electricians, url='https://www.autarc.energy/en/loesungen/fur-solarteure-elektriker'
	StaticText RESOURCES
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	link Customers, url='https://www.autarc.energy/en/kunden/kunden'
	link Support, url='https://www.autarc.energy/en/support'
	link Knowledge, url='https://www.autarc.energy/en/wissen'
	link Rates, url='https://www.autarc.energy/en/preise'
	link Imprint, url='https://www.autarc.energy/en/impressum'
	link Data protection, url='https://www.autarc.energy/en/datenschutz'
	link TERMS AND CONDITIONS, url='https://www.autarc.energy/en/agb'
	StaticText COMPANIES
	link About us, url='https://www.autarc.energy/en/uber-uns'
	link jobs, url='https://www.autarc.energy/en/jobs'
	link Press, url='https://www.autarc.energy/en/presse'
	link Events, url='https://www.autarc.energy/en/events'
	link Partner program, url='https://www.autarc.energy/en/partnerprogramm'
	StaticText autarc GmbH © 2024.
	StaticText All rights reserved
	[1914] button Open Intercom Messenger, center=(1876,1036)
		image
		image
```
</details>



```
RootWebArea autarc – Die Wärmepumpen-Software, focused, url='https://www.autarc.energy/en'
	dialog Diese Webseite verwendet Cookies, modal=True
		image Logo, url='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAC4AAAAuCAYAAABXuSs3AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAQBSURBVGhD7VpJKLZtFDYskKlkzpjMIUOGQoqIlIUFFmYZEskQkj1CGUNYUCKhLAylzAvCghA+Q1aGiJAI53edz/28ff/n3+npf+s5dfXe59znvs/1nPucs0HjU3594kbNAM4aD58gNQM48xd8t/l/BjgrxOWEQlxuKMTlhkJcbijE5YZCXG4oxOWGQpyRmJhIdXV1FBAQ8O3+D+JniQ8MDBAkLS3t2/0fxN/EY2JiaHx8nFZWVqi7u5t8fX3ZHhcXR0NDQxQbGyv5GhsbM9nm5mZqbGyks7MzJr6xsUGjo6NkYWFBJiYmVF9fz/dNTU1RTk4On9XS0qLOzk6O4e/vT/39/TQzM0OGhobk4uJCHR0dND8/T2NjY5SRkSHF/MKfxPPy8jjwy8sLbW9v8/r5+ZlcXV2psLCQ9aqqKukCa2trtl1fX9Pq6iq9vb2x/vr6So+PjxQfH0/7+/ts293dpZubG143NTWRpqYm3d/fs/7x8cG/7+/vVFpaKtkfHh74F9Lb2yvF/YSKuK6uLh0eHnIgAwMDdkhKSuJDbW1tlJyczOuSkhLpAisrKw52enrK5/v6+tgnPz+f9ZqaGrq7u6Pc3FzpzMnJCfs4OTnR3t4er4+Ojig4OJgzfXV1xbaCggLS09Mjd3d3Oj8/Z1tgYKC4R0VcW1ubjIyMKCoqiqqrq/mpt7a2+MDw8DClpqbyuqysTCIB4hAQh97S0sK6qHEdHR1yc3Oj9PR06unpodnZWc4mMuzn58evAEFM+Ht5ebG+vr4uxQBsbGwoJCSEzMzMhE1FHECGhCAby8vLvB4ZGWEyEDyl8EfWIMfHx6y3trayLurY29ub9yAop8XFRbq8vOSSAvGDgwP+CPQC/CMjI9l3cnJSivEfUBEX9XpxccENAlt0dDTbkPHs7Gxeo2mwB5SXl7MNJQa9vb2d9czMTNYHBwdZz8rKks7AF4KGxBr9YG5uznv29va8h14QNqC2tpYWFhYoNDRU2FTE8dUQNFVCQgKlpKTQ7e0t2yYmJvipIAiE5hJlAREZLyoqYh2NXVFRQUtLS6zjgzCtcI8Q1DTOIfumpqYSSUwZCHqtsrJS0p+enji5X34q4kBxcTFPESF4Msjc3BzvNzQ0SBMAgkvR+Wg4TAl9fX2anp7+2v3dpGtra1/a7zG5s7PD66CgIC4VxMPIFBzQF11dXewjZHNzk3x8fCSfT/xJHLCzs6Pw8HBydHRk3dPTkxwcHKR9jMaIiAiytbVlHc3n7OzMxIUPyiAsLIzXmNfILgDd0tKSPDw8eGKgR3Aeg0GcFUBM8PgXYYG/iasJFOJyQyEuNxTickMhLjcU4nJDIS43FOJyg4mr7Z/E1fCfEDR+/QN5VWLLOegHAwAAAABJRU5ErkJggg=='
		[71] link Logo - opens in a new window, center=(1249,304), url='https://www.cookiebot.com/de/was-steckt-hinter-powered-by-cookiebot/'
			image
```
<details><summary>Show more</summary>

```
		[73] button Banner schließen, center=(1380,304)
			image
		tablist, orientation='horizontal'
			[80] tab Zustimmung, center=(650,375), selected=True
			[82] tab Details, center=(930,375), selected=False
			[86] tab Über Cookies, center=(1210,375), selected=False
		tabpanel Zustimmung
			heading Diese Webseite verwendet Cookies
			group Consent Selection
				Legend
				LabelText
					strong
						StaticText Notwendig
				checkbox Notwendig, checked='true', disabled=True
				LabelText
					[113] strong, center=(847,639), inner_text=Präferenzen
						StaticText Präferenzen
				[115] checkbox Präferenzen, center=(847,679), checked=, contenteditable=True, type=checkbox
				LabelText
					[119] strong, center=(1072,639), inner_text=Statistiken
						StaticText Statistiken
				[121] checkbox Statistiken, center=(1072,679), checked=, contenteditable=True, type=checkbox
				LabelText
					[125] strong, center=(1298,639), inner_text=Marketing
						StaticText Marketing
				[127] checkbox Marketing, center=(1298,679), checked=, contenteditable=True, type=checkbox
		[999] button Ablehnen, center=(672,763)
		[1000] button Auswahl erlauben, center=(960,763)
		[1003] button Alle zulassen, center=(1248,763)
	banner
		[1012] link, center=(87,45), url='https://www.autarc.energy/en'
			image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/655bf2270fe58d910009ed6b_autrc-logo.png'
		navigation
			[1049] button Products, center=(197,45), expanded=False, focused, hasPopup='menu'
			[1088] button Solutions, center=(291,45), expanded=False, hasPopup='menu'
			[1110] link Customers, center=(392,45), url='https://www.autarc.energy/en/kunden/kunden'
			[1112] button Knowledge, center=(499,45), expanded=False, hasPopup='menu'
			[1126] button About us, center=(600,45), expanded=False, hasPopup='menu'
			[1156] link Jobs, center=(678,45), url='https://www.autarc.energy/en/jobs'
			[1157] link Rates, center=(744,45), url='https://www.autarc.energy/en/preise'
			article
				[1160] link WhatsApp Chat, center=(1613,45), url='https://wa.me/4915792312671'
					image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6732237bf724025079599592_whatsapp-logo-grey.png'
				[1163] link Login, center=(1732,45), url='https://app.autarc.energy/login'
				[1164] link Book a demo, center=(1826,45), url='https://www.autarc.energy/en/demo-buchen'
	[1286] link künstliche Intelligenz bei autarc energy Autarc AI — app out, scan on, heat load in 15 minutes Pfeil nach rechts, center=(960,210), inner_text=Autarc AI — app out, scan on, heat load in 15 minutes, url='https://www.autarc.energy/en/produkte/lidar-scan'
		image künstliche Intelligenz bei autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65691ad146aa7fb03353521b_sparkle.svg'
		image Pfeil nach rechts, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65691afb341494ef5e90d89f_arrowRight.svg'
	heading autarc is a better way
	heading to plan heat pumps
	StaticText Discover the new standard for sales and planning of heat pumps. Heat load, hydraulic balancing (B) and funding application in just a few clicks.
	form Email Form Start
		textbox Business email address*, required
		button Book a demo
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
	StaticText 14-day free trial
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
	StaticText Set up in just 3 minutes
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
	StaticText Can be canceled at any time
	image autarc home screen, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b313d2e56f36107c33e_autarc-home-screen-1-min-p-1080.png'
	StaticText We are a member of
	image Bunderverband Wärmepumpe e.V. autarc energy Software Planung wärmepumpe hydraulischer abgleich, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/651191ce20e01ee0dab72cf7_Logo_BWP_gross.png'
	image DIN-logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65e9aa81ef1b78df023333d4_DIN-mitgliedslogo-blau-autarc%20energy-p-500.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/66c222175ebc6be23eb42a83_EE_EnergieeffizienzExperten_Logo_M-removebg-p-500.webp'
	StaticText Software for the best heating engineers.
	StaticText From the next generation to established businesses, 250+ customers already trust us.
	image Vinci Unternehmenslogo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6391e678268622418d2bfeb9_Vinci.png'
	image Daume Gruppe Unternehmenslogo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6391e67829871fbe96bc762b_Daume.png'
	image Theodor Bergmann Berlin, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b38e65330789e606fe27_Theodor%20Bergmann%20Berlin.svg'
	image Vattenfall, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b38fbf4bdd782aa5eac1_Vattenfall.svg'
	image mf mercedöl, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b48810e117cbe394c07b_mf%20mercedoil%20gmbh%20berlin.svg'
	image Koster, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b488fd4ac778e955fc38_koster%20gmbh%20berlin%20heizung.svg'
	image Hörmann Haustechnike, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646269795ed5193ea3b87531_hoermann-haustechnik%201.svg'
	image WagEnergie aus Duderstadt, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646269792dc26a20312e9008_logo_wagenergie_rgb-removebg-preview%201.svg'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/66cffa26a6addc029265bd2f_nuuEnergy_logo.png'
	image Klaus Klein Design Bad, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d54581270477c9dbd8_Klaus%20Klein%20Gmbh.svg'
	image Team Steffen, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d469b7a5456ecd20e9_Team%20Steffen.svg'
	image Thomas Mehner Haustechnik Unternehmenslogo Braunschweig, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/63c69c6f3159457dc6248ccd_Mehner.svg'
	image Berner Elektrotechnik, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646280cc96faa3e03621627f_Berner%20Elektrotechnik.svg'
	StaticText Benefits
	heading Why autarc?
	image Uhr Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699c018f5de07a866d2440_Group%20482166.svg'
	StaticText The fastest way to data
	StaticText With autarc, you can quickly access via
	StaticText 600 relevant house data
	StaticText thanks to artificial intelligence.
	StaticText In just 10 minutes
	StaticText enter all necessary information, supplemented with pictures at the customer's site. This step can also be taken over by inexperienced colleagues.
	image Sicherheit Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699c01f9738c8487d50db2_Group%20482167.svg'
	StaticText Higher offer quality
	StaticText Through the data
	StaticText Does quality increase
	StaticText your offers
	StaticText by 90%
	StaticText . With precise and comprehensive information, you can offer tailor-made solutions. For you, this means:
	StaticText more successful deals
	StaticText And a
	StaticText quick contract processing
	StaticText .
	image Schloss Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699c0166880e76db41fee8_Group%20482168.svg'
	StaticText No plant failures
	StaticText Wrongly dimensioned or timed heat pumps are a thing of the past. Our precise analysis enables a
	StaticText optimal system planning
	StaticText . The result is powerful, efficient heat pumps that are precisely tailored to the needs of your customers. For you, that means:
	StaticText fewer plant failures
	StaticText and therefore
	StaticText happier customers
	StaticText .
	StaticText Known from
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731bac75b8721c35ff4e_image%201183-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731b3d28cd7e20c5abab_image%201182-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731bc2a0f1867d6fceff_image%201181-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731b50ec48404304f555_image%201186-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731b08a0892e1a0b8b00_image%201187-min.png'
	StaticText Solution
	heading autarc has what you need.
	heading The most efficient planning and sales process.
	image Nummer 1, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699fb7f77c77287929fea5_Group%20482169.svg'
	StaticText Heat pump check and customer portal
	StaticText Quick aptitude test, modern communication
	StaticText In
	StaticText few minutes
	StaticText Does your customer find out whether a heat pump is suitable for their home. He then gets access to
	StaticText your customer portal
	StaticText , the hub for all communication. From the
	StaticText initial assessment
	StaticText up to the final installation
	StaticText keep your customers up to date.
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Quick aptitude test in just 3 minutes
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customizable interface
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Forecast for higher conversion
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Accessible 24/7 from all devices
	image Wärmepumpen check autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b3162da9b852b633038_autarc-home-screen-2-min.png'
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText 1 hour time saving
	StaticText Your customer provides you with important information for your calculations
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText +75%
	StaticText Higher conversion of requests
	image Nummer 2, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699fb6909cb9881fef548c_Group%20482170.svg'
	StaticText On-site visit
	StaticText Input and calculation in one step
	StaticText In just 15 minutes
	StaticText Do you get a result for
	StaticText Heat load, sound emissions, heating surface design
	StaticText and
	StaticText hydraulic balancing (B)
	StaticText . In addition, a suitable offer is generated. Means for you:
	StaticText less time for data recording
	StaticText , more time to sell the plant.
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Mobile availability on tablet/smartphone
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Room capture with 3D scanner
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Automatic radiator detection (beta)
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText All calculations in one pdf. Report
	image LiDAR Scan für Heizlast und hydraulischer abgleich von autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b3163cd25a8d73ccae9_autarc-home-screen-3-min.png'
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText 600+
	StaticText Data for the best offers and plant planning
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText >10 hours time saving
	StaticText For heat load, layout, sound testing, supply and hydraulic adjustment
	image Nummer 3, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699fb7415c82498e334224_Group%20482171.svg'
	StaticText Specialist partner portal
	StaticText One software for everything related to the heat pump
	StaticText Everything is managed centrally in the specialist partner portal. It allows the generation of
	StaticText Reports
	StaticText , processing of
	StaticText Funding
	StaticText , the creation of
	StaticText VDZ forms
	StaticText , the
	StaticText startup
	StaticText of plants and
	StaticText maintenancies
	StaticText .
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Collaborate with teammates
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Generating heat pump reports
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Planning of systems including heating surfaces
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Funding and VDZ forms
	image Screen von der Projektübersicht der autarc energy software, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b314ee49de84aad0baa_autarc-home-screen-4-min.png'
	Iframe Auf Trustpilot veröffentlichte Kundenbewertungen
		RootWebArea Trustpilot Custom Widget, url='https://widget.trustpilot.com/trustboxes/5419b6a8b0d04a076446a9ad/index.html?templateId=5419b6a8b0d04a076446a9ad&businessunitId=63ca54b68fcd1c82bbeabefb#locale=de-DE&styleHeight=50px&styleWidth=100%25&theme=light&minReviewCount=0&styleAlignment=center'
			link Sehen Sie unsere 38 Bewertungen auf Trustpilot, url='https://de.trustpilot.com/review/autarc.energy?utm_medium=trustbox&utm_source=MicroReviewCount'
				[a12] strong, center=(919,5736)
					StaticText 38
				[a16] image Trustpilot, center=(1084,5734)
	StaticText Work together
	StaticText 10x faster.
	StaticText autarc was developed so that you and your colleagues get the most out of sales and planning for heating installations.
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	image iPhone Screen autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a8667dd7fe207f4da02c_autarc-Screen-5.svg'
	image Angebotstool autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a8a36a1ea6c7b7f32d39_autarc-home-screen-5-p-800.png'
	image Wärmepumpen Report autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a8a305876884a29298b2_autarc-home-screen-5-1-p-800.png'
	StaticText Meets all requirements
	StaticText And more
	StaticText autarc has what you need and is therefore the leading provider of heat pump planning.
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	StaticText requests
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Overview of all inquiries
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText High conversion prediction
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Share projects with customers
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customizable interface
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Create customer file
	StaticText requests
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText All climate data
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heat load calculation
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heating surface design
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText sound emissions
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Indicative price offers
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Funding
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText manufacturer's instructions
	StaticText installation
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Auto Inspection of delivery measures
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customizable checklists
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Online orders
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Material extracts
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Foundation instructions
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Annual performance figure
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Safety distances
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Installation site with augmented reality
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText valve settings
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText pump delivery heights
	StaticText furtherance
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Review of available funding
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Interface to BAFA
	StaticText + more
	StaticText “Since we've been using autarc, we've been driving
	StaticText We no longer go directly to every customer
	StaticText . Through the
	StaticText Qualification
	StaticText During the heat pump check, we only deal with customers who are really interested in a heat pump.”
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569c64166880e76db5e38ca_Ellipse%20392.svg'
	StaticText Philip Walter
	StaticText Managing Director
	StaticText Thomas Mehner Haustechnik
	StaticText Our guide
	StaticText The ultimate guide to
	StaticText Heat pump house visits 2024 are here!
	link Learn more, url='https://www.autarc.energy/en/leitfaden'
	image autarc Leitfaden für Wärmepumpen Hausbesuche, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/657499757d7f5fa4e98b8022_Group%20482127.png'
	StaticText Leading manufacturers
	StaticText Works with all manufacturers and types
	StaticText of heat pumps
	link Learn more, url='https://www.autarc.energy/en/wissen'
	image Übersicht verfügbarer Hersteller in der autarc energy software, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569d79d08885f64dec7e0fa_Group%20482173.svg'
	StaticText Our software works with all manufacturers.
	StaticText You can find a small selection here.
	image Danfoss, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d582485650889931f1_Danfoss.svg'
	image IMI Heimeier, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d54eaafc68f6aa619c_IMI%20Heimeier.svg'
	image Oventrop, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d5fb6ee1d0f1b04b25_Oventrop.svg'
	image Resideo Honeywell, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64628132380e5ecaac062cd8_Resideo%20Honeywell.svg'
	image Viessmann, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b66ad7095943cebd8e6f_Viessmann.svg'
	image Vaillant Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65c8695df776be3aa90_Vaillant.svg'
	image Stiebel Eltron Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65c121acb6a85783b4a_Stiebel%20Eltron.svg'
	image Daikin Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65c4793c63f2747af30_Daikin.svg'
	image Buderus Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65cfc6d39159e072da0_Buderus.svg'
	image Samsung Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65cfc6d39159e072dac_Samsung.svg'
	image Bosch Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65d97eba92836ed04fc_Bosch.svg'
	StaticText Ready to start?
	StaticText Discover all our solutions or book a demo to test autarc free of charge.
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	image Sicherheit Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8318594f792728e68_disputeProtection.svg'
	StaticText 100% DIN compliant
	StaticText We comply with all standards in our calculations
	image Kalender Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8a072dc7ea8656caf_calendar.svg'
	StaticText 24/7 available
	StaticText Accessible from all devices throughout the year
	image Person Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8f538c85e3faedc85_person.svg'
	StaticText Personal contact
	StaticText We take time to answer your concerns, no question remains unanswered
	StaticText Testimonials
	heading What our customers say.
	heading How Daume plans 270 heat pumps per year using Autarc.
	Iframe Daume GmbH über Ihre Erfahrung mit der einfachsten Planungssoftware für Wärmepumpen | autarc
		RootWebArea Daume GmbH über Ihre Erfahrung mit der einfachsten Planungssoftware für Wärmepumpen | autarc - YouTube, url='https://www.youtube.com/embed/mEkOYnmscdw?rel=0&controls=1&autoplay=1&mute=1&start=0'
			[b26] Video, center=(960,12134)
			generic, atomic
			slider Seek slider value='0', orientation='horizontal'
			group
				slider Click or scroll the panel for the precise seeking. value='0', orientation='horizontal'
			[b409] button Pause (k), center=(395,12451)
				image
			[b414] button Unmute (m), center=(438,12451)
				image
			slider Volume value='100', orientation='horizontal'
				group
			StaticText 0:00
			StaticText /
			StaticText 3:30
			[b430] button Vorstellung Daume GmbH, center=(942,12451)
				generic Vorstellung Daume GmbH
			[b436] button Subtitles/closed captions unavailable, center=(1381,12451)
				image
			[b438] button Settings, center=(1421,12451), expanded=False, hasPopup='menu'
				image
			[b440] link Watch on YouTube, center=(1474,12451), url='https://www.youtube.com/watch?v=mEkOYnmscdw'
			[b447] button Full screen (f), center=(1528,12451)
				image
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText Premium license
	StaticText Everything you need to make your business efficient.
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText Products in use
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heat pump check
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customer portal
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText iOS app for iPad
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heat pump report
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText >270 heat pumps
	StaticText Install thumbs per year and plan them with self-tarc.
	StaticText Your potential
	heading Calculate your savings potential.
	heading With autarc, we make you even more efficient.
	link Available soon, url='https://www.autarc.energy/en#'
	StaticText “With autarc, we can implement method B in
	StaticText Create under 1 hour
	StaticText , much faster than our previous solutions. We can see that our customers are impressed that everything comes from a single source.”
	image Portrait Stefan Möllenhoff Vinci Energies, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569ff3c2615a40b667d1a1d_Group%20482130.svg'
	StaticText Stefan Möllenhoff
	StaticText Executive
	StaticText Vinci Energies
	StaticText Would you like to stay up to date?
	StaticText Sign up for our newsletter
	form Newsletter Form
		textbox First name *, required
		textbox Last name *, required
		textbox Business email address*, required
		button Subscribe
	StaticText Frequently asked questions
	StaticText We can help answer questions and resolve issues. Have a look at our frequently asked questions, send us a message or give us a call.
	link Learn more, url='https://hilfe.autarc.energy/de/'
	image Bunderverband Wärmepumpe e.V. autarc energy Software Planung wärmepumpe hydraulischer abgleich, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/651191ce20e01ee0dab72cf7_Logo_BWP_gross.png'
	image INVEST Förderung BAFA für autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65085835fa950284eb14fffa_INVEST_Logo_URL_rote_URL_RZ-p-500.png'
	image European Social Fund, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/63e298e1d376b73610c0daee_Google%20form%20cover%20-%20Accelerator%20team-p-500.png'
	link Autarc Logo, url='https://www.autarc.energy/en'
		image Autarc Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6339884edcb06d6ae77fe900_autarc%20logo_black.svg'
	link, url='https://wa.me/4915792312671'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6732224a26847515db644115_whatsapp.svg'
	link, url='https://apps.apple.com/app/autarc/id6464311183'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/656a05f75545a6a3e2b24fab_Group%20482167.svg'
	link, url='https://app.autarc.energy/login'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/656a05f7d8a01b8c1b94e2a4_Group%20482166.svg'
	button Language, expanded=False, hasPopup='menu'
	StaticText PRODUCTS
	link Heat pump check, url='https://www.autarc.energy/en/produkte/warmepumpen-check'
	link Customer portal, url='https://www.autarc.energy/en/produkte/kunden-portal'
	link Quotation tool, url='https://www.autarc.energy/en/produkte/angebotstool'
	link LiDAR scan, url='https://www.autarc.energy/en/produkte/lidar-scan'
	link Heat load calculation, url='https://www.autarc.energy/en/produkte/heizlastberechnung'
	link Hydraulic balancing, url='https://www.autarc.energy/en/produkte/hydraulischer-abgleich-b'
	link Heating surface design, url='https://www.autarc.energy/en/produkte/heizflachenauslegung'
	link Funding service, url='https://www.autarc.energy/en/produkte/foerderhilfe'
	StaticText INTEGRATIONS
	link Craftsman software, url='https://www.autarc.energy/en/produkte/handwerkersoftware'
	link CRM, url='https://www.autarc.energy/en/produkte/crm'
	StaticText SOCIAL MEDIA
	link Linkedin, url='https://www.linkedin.com/company/autarc-energy/'
	link facebook, url='https://www.facebook.com/autarcenergy'
	link instagram, url='https://www.instagram.com/autarcenergy/'
	link YouTube, url='https://www.youtube.com/@getautarc'
	StaticText PRODUCTS
	link For young companies, url='https://www.autarc.energy/en/loesungen/fuer-junge-firmen'
	link For established companies, url='https://www.autarc.energy/en/loesungen/fuer-etablierte-unternehmen'
	link For energy suppliers, url='https://www.autarc.energy/en/loesungen/fur-energieversorger-stadtwerke'
	link For energy consultants, url='https://www.autarc.energy/en/loesungen/fuer-energieberater-ingenieurbueros'
	link For solar engineers/electricians, url='https://www.autarc.energy/en/loesungen/fur-solarteure-elektriker'
	StaticText RESOURCES
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	link Customers, url='https://www.autarc.energy/en/kunden/kunden'
	link Support, url='https://www.autarc.energy/en/support'
	link Knowledge, url='https://www.autarc.energy/en/wissen'
	link Rates, url='https://www.autarc.energy/en/preise'
	link Imprint, url='https://www.autarc.energy/en/impressum'
	link Data protection, url='https://www.autarc.energy/en/datenschutz'
	link TERMS AND CONDITIONS, url='https://www.autarc.energy/en/agb'
	StaticText COMPANIES
	link About us, url='https://www.autarc.energy/en/uber-uns'
	link jobs, url='https://www.autarc.energy/en/jobs'
	link Press, url='https://www.autarc.energy/en/presse'
	link Events, url='https://www.autarc.energy/en/events'
	link Partner program, url='https://www.autarc.energy/en/partnerprogramm'
	StaticText autarc GmbH © 2024.
	StaticText All rights reserved
	[1914] button Open Intercom Messenger, center=(1876,1036)
		image
		image
```
</details>

**Reasoning for action:** By clicking on the Products button, I am initiating the process to explore the offerings related to heat pumps. This step is essential to navigate through the webpage and access the relevant information. After this action, the next steps will focus on selecting the appropriate product, which in this case is the 'Heat pump check' option.

**Action:** click(1049) # Click on the Products button to explore the product offerings.

**Change Description:** The agent clicked the 'Products' button, which caused the button to become focused, indicating that the user is now able to explore the product offerings, but no new content has been loaded or changed in the displayed area.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.autarc.energy/en

https://www.autarc.energy/en

**Content (before/after):** 

```
RootWebArea autarc – Die Wärmepumpen-Software, focused, url='https://www.autarc.energy/en'
	dialog Diese Webseite verwendet Cookies, modal=True
		image Logo, url='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAC4AAAAuCAYAAABXuSs3AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAQBSURBVGhD7VpJKLZtFDYskKlkzpjMIUOGQoqIlIUFFmYZEskQkj1CGUNYUCKhLAylzAvCghA+Q1aGiJAI53edz/28ff/n3+npf+s5dfXe59znvs/1nPucs0HjU3594kbNAM4aD58gNQM48xd8t/l/BjgrxOWEQlxuKMTlhkJcbijE5YZCXG4oxOWGQpyRmJhIdXV1FBAQ8O3+D+JniQ8MDBAkLS3t2/0fxN/EY2JiaHx8nFZWVqi7u5t8fX3ZHhcXR0NDQxQbGyv5GhsbM9nm5mZqbGyks7MzJr6xsUGjo6NkYWFBJiYmVF9fz/dNTU1RTk4On9XS0qLOzk6O4e/vT/39/TQzM0OGhobk4uJCHR0dND8/T2NjY5SRkSHF/MKfxPPy8jjwy8sLbW9v8/r5+ZlcXV2psLCQ9aqqKukCa2trtl1fX9Pq6iq9vb2x/vr6So+PjxQfH0/7+/ts293dpZubG143NTWRpqYm3d/fs/7x8cG/7+/vVFpaKtkfHh74F9Lb2yvF/YSKuK6uLh0eHnIgAwMDdkhKSuJDbW1tlJyczOuSkhLpAisrKw52enrK5/v6+tgnPz+f9ZqaGrq7u6Pc3FzpzMnJCfs4OTnR3t4er4+Ojig4OJgzfXV1xbaCggLS09Mjd3d3Oj8/Z1tgYKC4R0VcW1ubjIyMKCoqiqqrq/mpt7a2+MDw8DClpqbyuqysTCIB4hAQh97S0sK6qHEdHR1yc3Oj9PR06unpodnZWc4mMuzn58evAEFM+Ht5ebG+vr4uxQBsbGwoJCSEzMzMhE1FHECGhCAby8vLvB4ZGWEyEDyl8EfWIMfHx6y3trayLurY29ub9yAop8XFRbq8vOSSAvGDgwP+CPQC/CMjI9l3cnJSivEfUBEX9XpxccENAlt0dDTbkPHs7Gxeo2mwB5SXl7MNJQa9vb2d9czMTNYHBwdZz8rKks7AF4KGxBr9YG5uznv29va8h14QNqC2tpYWFhYoNDRU2FTE8dUQNFVCQgKlpKTQ7e0t2yYmJvipIAiE5hJlAREZLyoqYh2NXVFRQUtLS6zjgzCtcI8Q1DTOIfumpqYSSUwZCHqtsrJS0p+enji5X34q4kBxcTFPESF4Msjc3BzvNzQ0SBMAgkvR+Wg4TAl9fX2anp7+2v3dpGtra1/a7zG5s7PD66CgIC4VxMPIFBzQF11dXewjZHNzk3x8fCSfT/xJHLCzs6Pw8HBydHRk3dPTkxwcHKR9jMaIiAiytbVlHc3n7OzMxIUPyiAsLIzXmNfILgDd0tKSPDw8eGKgR3Aeg0GcFUBM8PgXYYG/iasJFOJyQyEuNxTickMhLjcU4nJDIS43FOJyg4mr7Z/E1fCfEDR+/QN5VWLLOegHAwAAAABJRU5ErkJggg=='
		[71] link Logo - opens in a new window, center=(1249,304), url='https://www.cookiebot.com/de/was-steckt-hinter-powered-by-cookiebot/'
			image
```
<details><summary>Show more</summary>

```
		[73] button Banner schließen, center=(1380,304)
			image
		tablist, orientation='horizontal'
			[80] tab Zustimmung, center=(650,375), selected=True
			[82] tab Details, center=(930,375), selected=False
			[86] tab Über Cookies, center=(1210,375), selected=False
		tabpanel Zustimmung
			heading Diese Webseite verwendet Cookies
			group Consent Selection
				Legend
				LabelText
					strong
						StaticText Notwendig
				checkbox Notwendig, checked='true', disabled=True
				LabelText
					[113] strong, center=(847,639), inner_text=Präferenzen
						StaticText Präferenzen
				[115] checkbox Präferenzen, center=(847,679), checked=, contenteditable=True, type=checkbox
				LabelText
					[119] strong, center=(1072,639), inner_text=Statistiken
						StaticText Statistiken
				[121] checkbox Statistiken, center=(1072,679), checked=, contenteditable=True, type=checkbox
				LabelText
					[125] strong, center=(1298,639), inner_text=Marketing
						StaticText Marketing
				[127] checkbox Marketing, center=(1298,679), checked=, contenteditable=True, type=checkbox
		[999] button Ablehnen, center=(672,763)
		[1000] button Auswahl erlauben, center=(960,763)
		[1003] button Alle zulassen, center=(1248,763)
	banner
		[1012] link, center=(87,45), url='https://www.autarc.energy/en'
			image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/655bf2270fe58d910009ed6b_autrc-logo.png'
		navigation
			[1049] button Products, center=(197,45), expanded=False, focused, hasPopup='menu'
			[1088] button Solutions, center=(291,45), expanded=False, hasPopup='menu'
			[1110] link Customers, center=(392,45), url='https://www.autarc.energy/en/kunden/kunden'
			[1112] button Knowledge, center=(499,45), expanded=False, hasPopup='menu'
			[1126] button About us, center=(600,45), expanded=False, hasPopup='menu'
			[1156] link Jobs, center=(678,45), url='https://www.autarc.energy/en/jobs'
			[1157] link Rates, center=(744,45), url='https://www.autarc.energy/en/preise'
			article
				[1160] link WhatsApp Chat, center=(1613,45), url='https://wa.me/4915792312671'
					image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6732237bf724025079599592_whatsapp-logo-grey.png'
				[1163] link Login, center=(1732,45), url='https://app.autarc.energy/login'
				[1164] link Book a demo, center=(1826,45), url='https://www.autarc.energy/en/demo-buchen'
	[1286] link künstliche Intelligenz bei autarc energy Autarc AI — app out, scan on, heat load in 15 minutes Pfeil nach rechts, center=(960,210), inner_text=Autarc AI — app out, scan on, heat load in 15 minutes, url='https://www.autarc.energy/en/produkte/lidar-scan'
		image künstliche Intelligenz bei autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65691ad146aa7fb03353521b_sparkle.svg'
		image Pfeil nach rechts, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65691afb341494ef5e90d89f_arrowRight.svg'
	heading autarc is a better way
	heading to plan heat pumps
	StaticText Discover the new standard for sales and planning of heat pumps. Heat load, hydraulic balancing (B) and funding application in just a few clicks.
	form Email Form Start
		textbox Business email address*, required
		button Book a demo
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
	StaticText 14-day free trial
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
	StaticText Set up in just 3 minutes
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
	StaticText Can be canceled at any time
	image autarc home screen, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b313d2e56f36107c33e_autarc-home-screen-1-min-p-1080.png'
	StaticText We are a member of
	image Bunderverband Wärmepumpe e.V. autarc energy Software Planung wärmepumpe hydraulischer abgleich, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/651191ce20e01ee0dab72cf7_Logo_BWP_gross.png'
	image DIN-logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65e9aa81ef1b78df023333d4_DIN-mitgliedslogo-blau-autarc%20energy-p-500.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/66c222175ebc6be23eb42a83_EE_EnergieeffizienzExperten_Logo_M-removebg-p-500.webp'
	StaticText Software for the best heating engineers.
	StaticText From the next generation to established businesses, 250+ customers already trust us.
	image Vinci Unternehmenslogo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6391e678268622418d2bfeb9_Vinci.png'
	image Daume Gruppe Unternehmenslogo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6391e67829871fbe96bc762b_Daume.png'
	image Theodor Bergmann Berlin, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b38e65330789e606fe27_Theodor%20Bergmann%20Berlin.svg'
	image Vattenfall, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b38fbf4bdd782aa5eac1_Vattenfall.svg'
	image mf mercedöl, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b48810e117cbe394c07b_mf%20mercedoil%20gmbh%20berlin.svg'
	image Koster, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b488fd4ac778e955fc38_koster%20gmbh%20berlin%20heizung.svg'
	image Hörmann Haustechnike, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646269795ed5193ea3b87531_hoermann-haustechnik%201.svg'
	image WagEnergie aus Duderstadt, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646269792dc26a20312e9008_logo_wagenergie_rgb-removebg-preview%201.svg'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/66cffa26a6addc029265bd2f_nuuEnergy_logo.png'
	image Klaus Klein Design Bad, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d54581270477c9dbd8_Klaus%20Klein%20Gmbh.svg'
	image Team Steffen, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d469b7a5456ecd20e9_Team%20Steffen.svg'
	image Thomas Mehner Haustechnik Unternehmenslogo Braunschweig, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/63c69c6f3159457dc6248ccd_Mehner.svg'
	image Berner Elektrotechnik, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646280cc96faa3e03621627f_Berner%20Elektrotechnik.svg'
	StaticText Benefits
	heading Why autarc?
	image Uhr Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699c018f5de07a866d2440_Group%20482166.svg'
	StaticText The fastest way to data
	StaticText With autarc, you can quickly access via
	StaticText 600 relevant house data
	StaticText thanks to artificial intelligence.
	StaticText In just 10 minutes
	StaticText enter all necessary information, supplemented with pictures at the customer's site. This step can also be taken over by inexperienced colleagues.
	image Sicherheit Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699c01f9738c8487d50db2_Group%20482167.svg'
	StaticText Higher offer quality
	StaticText Through the data
	StaticText Does quality increase
	StaticText your offers
	StaticText by 90%
	StaticText . With precise and comprehensive information, you can offer tailor-made solutions. For you, this means:
	StaticText more successful deals
	StaticText And a
	StaticText quick contract processing
	StaticText .
	image Schloss Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699c0166880e76db41fee8_Group%20482168.svg'
	StaticText No plant failures
	StaticText Wrongly dimensioned or timed heat pumps are a thing of the past. Our precise analysis enables a
	StaticText optimal system planning
	StaticText . The result is powerful, efficient heat pumps that are precisely tailored to the needs of your customers. For you, that means:
	StaticText fewer plant failures
	StaticText and therefore
	StaticText happier customers
	StaticText .
	StaticText Known from
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731bac75b8721c35ff4e_image%201183-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731b3d28cd7e20c5abab_image%201182-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731bc2a0f1867d6fceff_image%201181-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731b50ec48404304f555_image%201186-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731b08a0892e1a0b8b00_image%201187-min.png'
	StaticText Solution
	heading autarc has what you need.
	heading The most efficient planning and sales process.
	image Nummer 1, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699fb7f77c77287929fea5_Group%20482169.svg'
	StaticText Heat pump check and customer portal
	StaticText Quick aptitude test, modern communication
	StaticText In
	StaticText few minutes
	StaticText Does your customer find out whether a heat pump is suitable for their home. He then gets access to
	StaticText your customer portal
	StaticText , the hub for all communication. From the
	StaticText initial assessment
	StaticText up to the final installation
	StaticText keep your customers up to date.
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Quick aptitude test in just 3 minutes
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customizable interface
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Forecast for higher conversion
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Accessible 24/7 from all devices
	image Wärmepumpen check autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b3162da9b852b633038_autarc-home-screen-2-min.png'
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText 1 hour time saving
	StaticText Your customer provides you with important information for your calculations
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText +75%
	StaticText Higher conversion of requests
	image Nummer 2, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699fb6909cb9881fef548c_Group%20482170.svg'
	StaticText On-site visit
	StaticText Input and calculation in one step
	StaticText In just 15 minutes
	StaticText Do you get a result for
	StaticText Heat load, sound emissions, heating surface design
	StaticText and
	StaticText hydraulic balancing (B)
	StaticText . In addition, a suitable offer is generated. Means for you:
	StaticText less time for data recording
	StaticText , more time to sell the plant.
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Mobile availability on tablet/smartphone
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Room capture with 3D scanner
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Automatic radiator detection (beta)
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText All calculations in one pdf. Report
	image LiDAR Scan für Heizlast und hydraulischer abgleich von autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b3163cd25a8d73ccae9_autarc-home-screen-3-min.png'
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText 600+
	StaticText Data for the best offers and plant planning
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText >10 hours time saving
	StaticText For heat load, layout, sound testing, supply and hydraulic adjustment
	image Nummer 3, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699fb7415c82498e334224_Group%20482171.svg'
	StaticText Specialist partner portal
	StaticText One software for everything related to the heat pump
	StaticText Everything is managed centrally in the specialist partner portal. It allows the generation of
	StaticText Reports
	StaticText , processing of
	StaticText Funding
	StaticText , the creation of
	StaticText VDZ forms
	StaticText , the
	StaticText startup
	StaticText of plants and
	StaticText maintenancies
	StaticText .
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Collaborate with teammates
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Generating heat pump reports
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Planning of systems including heating surfaces
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Funding and VDZ forms
	image Screen von der Projektübersicht der autarc energy software, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b314ee49de84aad0baa_autarc-home-screen-4-min.png'
	Iframe Auf Trustpilot veröffentlichte Kundenbewertungen
		RootWebArea Trustpilot Custom Widget, url='https://widget.trustpilot.com/trustboxes/5419b6a8b0d04a076446a9ad/index.html?templateId=5419b6a8b0d04a076446a9ad&businessunitId=63ca54b68fcd1c82bbeabefb#locale=de-DE&styleHeight=50px&styleWidth=100%25&theme=light&minReviewCount=0&styleAlignment=center'
			link Sehen Sie unsere 38 Bewertungen auf Trustpilot, url='https://de.trustpilot.com/review/autarc.energy?utm_medium=trustbox&utm_source=MicroReviewCount'
				[a12] strong, center=(919,5736)
					StaticText 38
				[a16] image Trustpilot, center=(1084,5734)
	StaticText Work together
	StaticText 10x faster.
	StaticText autarc was developed so that you and your colleagues get the most out of sales and planning for heating installations.
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	image iPhone Screen autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a8667dd7fe207f4da02c_autarc-Screen-5.svg'
	image Angebotstool autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a8a36a1ea6c7b7f32d39_autarc-home-screen-5-p-800.png'
	image Wärmepumpen Report autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a8a305876884a29298b2_autarc-home-screen-5-1-p-800.png'
	StaticText Meets all requirements
	StaticText And more
	StaticText autarc has what you need and is therefore the leading provider of heat pump planning.
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	StaticText requests
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Overview of all inquiries
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText High conversion prediction
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Share projects with customers
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customizable interface
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Create customer file
	StaticText requests
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText All climate data
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heat load calculation
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heating surface design
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText sound emissions
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Indicative price offers
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Funding
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText manufacturer's instructions
	StaticText installation
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Auto Inspection of delivery measures
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customizable checklists
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Online orders
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Material extracts
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Foundation instructions
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Annual performance figure
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Safety distances
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Installation site with augmented reality
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText valve settings
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText pump delivery heights
	StaticText furtherance
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Review of available funding
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Interface to BAFA
	StaticText + more
	StaticText “Since we've been using autarc, we've been driving
	StaticText We no longer go directly to every customer
	StaticText . Through the
	StaticText Qualification
	StaticText During the heat pump check, we only deal with customers who are really interested in a heat pump.”
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569c64166880e76db5e38ca_Ellipse%20392.svg'
	StaticText Philip Walter
	StaticText Managing Director
	StaticText Thomas Mehner Haustechnik
	StaticText Our guide
	StaticText The ultimate guide to
	StaticText Heat pump house visits 2024 are here!
	link Learn more, url='https://www.autarc.energy/en/leitfaden'
	image autarc Leitfaden für Wärmepumpen Hausbesuche, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/657499757d7f5fa4e98b8022_Group%20482127.png'
	StaticText Leading manufacturers
	StaticText Works with all manufacturers and types
	StaticText of heat pumps
	link Learn more, url='https://www.autarc.energy/en/wissen'
	image Übersicht verfügbarer Hersteller in der autarc energy software, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569d79d08885f64dec7e0fa_Group%20482173.svg'
	StaticText Our software works with all manufacturers.
	StaticText You can find a small selection here.
	image Danfoss, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d582485650889931f1_Danfoss.svg'
	image IMI Heimeier, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d54eaafc68f6aa619c_IMI%20Heimeier.svg'
	image Oventrop, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d5fb6ee1d0f1b04b25_Oventrop.svg'
	image Resideo Honeywell, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64628132380e5ecaac062cd8_Resideo%20Honeywell.svg'
	image Viessmann, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b66ad7095943cebd8e6f_Viessmann.svg'
	image Vaillant Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65c8695df776be3aa90_Vaillant.svg'
	image Stiebel Eltron Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65c121acb6a85783b4a_Stiebel%20Eltron.svg'
	image Daikin Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65c4793c63f2747af30_Daikin.svg'
	image Buderus Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65cfc6d39159e072da0_Buderus.svg'
	image Samsung Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65cfc6d39159e072dac_Samsung.svg'
	image Bosch Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65d97eba92836ed04fc_Bosch.svg'
	StaticText Ready to start?
	StaticText Discover all our solutions or book a demo to test autarc free of charge.
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	image Sicherheit Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8318594f792728e68_disputeProtection.svg'
	StaticText 100% DIN compliant
	StaticText We comply with all standards in our calculations
	image Kalender Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8a072dc7ea8656caf_calendar.svg'
	StaticText 24/7 available
	StaticText Accessible from all devices throughout the year
	image Person Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8f538c85e3faedc85_person.svg'
	StaticText Personal contact
	StaticText We take time to answer your concerns, no question remains unanswered
	StaticText Testimonials
	heading What our customers say.
	heading How Daume plans 270 heat pumps per year using Autarc.
	Iframe Daume GmbH über Ihre Erfahrung mit der einfachsten Planungssoftware für Wärmepumpen | autarc
		RootWebArea Daume GmbH über Ihre Erfahrung mit der einfachsten Planungssoftware für Wärmepumpen | autarc - YouTube, url='https://www.youtube.com/embed/mEkOYnmscdw?rel=0&controls=1&autoplay=1&mute=1&start=0'
			[b26] Video, center=(960,12134)
			generic, atomic
			slider Seek slider value='0', orientation='horizontal'
			group
				slider Click or scroll the panel for the precise seeking. value='0', orientation='horizontal'
			[b409] button Pause (k), center=(395,12451)
				image
			[b414] button Unmute (m), center=(438,12451)
				image
			slider Volume value='100', orientation='horizontal'
				group
			StaticText 0:00
			StaticText /
			StaticText 3:30
			[b430] button Vorstellung Daume GmbH, center=(942,12451)
				generic Vorstellung Daume GmbH
			[b436] button Subtitles/closed captions unavailable, center=(1381,12451)
				image
			[b438] button Settings, center=(1421,12451), expanded=False, hasPopup='menu'
				image
			[b440] link Watch on YouTube, center=(1474,12451), url='https://www.youtube.com/watch?v=mEkOYnmscdw'
			[b447] button Full screen (f), center=(1528,12451)
				image
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText Premium license
	StaticText Everything you need to make your business efficient.
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText Products in use
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heat pump check
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customer portal
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText iOS app for iPad
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heat pump report
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText >270 heat pumps
	StaticText Install thumbs per year and plan them with self-tarc.
	StaticText Your potential
	heading Calculate your savings potential.
	heading With autarc, we make you even more efficient.
	link Available soon, url='https://www.autarc.energy/en#'
	StaticText “With autarc, we can implement method B in
	StaticText Create under 1 hour
	StaticText , much faster than our previous solutions. We can see that our customers are impressed that everything comes from a single source.”
	image Portrait Stefan Möllenhoff Vinci Energies, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569ff3c2615a40b667d1a1d_Group%20482130.svg'
	StaticText Stefan Möllenhoff
	StaticText Executive
	StaticText Vinci Energies
	StaticText Would you like to stay up to date?
	StaticText Sign up for our newsletter
	form Newsletter Form
		textbox First name *, required
		textbox Last name *, required
		textbox Business email address*, required
		button Subscribe
	StaticText Frequently asked questions
	StaticText We can help answer questions and resolve issues. Have a look at our frequently asked questions, send us a message or give us a call.
	link Learn more, url='https://hilfe.autarc.energy/de/'
	image Bunderverband Wärmepumpe e.V. autarc energy Software Planung wärmepumpe hydraulischer abgleich, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/651191ce20e01ee0dab72cf7_Logo_BWP_gross.png'
	image INVEST Förderung BAFA für autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65085835fa950284eb14fffa_INVEST_Logo_URL_rote_URL_RZ-p-500.png'
	image European Social Fund, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/63e298e1d376b73610c0daee_Google%20form%20cover%20-%20Accelerator%20team-p-500.png'
	link Autarc Logo, url='https://www.autarc.energy/en'
		image Autarc Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6339884edcb06d6ae77fe900_autarc%20logo_black.svg'
	link, url='https://wa.me/4915792312671'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6732224a26847515db644115_whatsapp.svg'
	link, url='https://apps.apple.com/app/autarc/id6464311183'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/656a05f75545a6a3e2b24fab_Group%20482167.svg'
	link, url='https://app.autarc.energy/login'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/656a05f7d8a01b8c1b94e2a4_Group%20482166.svg'
	button Language, expanded=False, hasPopup='menu'
	StaticText PRODUCTS
	link Heat pump check, url='https://www.autarc.energy/en/produkte/warmepumpen-check'
	link Customer portal, url='https://www.autarc.energy/en/produkte/kunden-portal'
	link Quotation tool, url='https://www.autarc.energy/en/produkte/angebotstool'
	link LiDAR scan, url='https://www.autarc.energy/en/produkte/lidar-scan'
	link Heat load calculation, url='https://www.autarc.energy/en/produkte/heizlastberechnung'
	link Hydraulic balancing, url='https://www.autarc.energy/en/produkte/hydraulischer-abgleich-b'
	link Heating surface design, url='https://www.autarc.energy/en/produkte/heizflachenauslegung'
	link Funding service, url='https://www.autarc.energy/en/produkte/foerderhilfe'
	StaticText INTEGRATIONS
	link Craftsman software, url='https://www.autarc.energy/en/produkte/handwerkersoftware'
	link CRM, url='https://www.autarc.energy/en/produkte/crm'
	StaticText SOCIAL MEDIA
	link Linkedin, url='https://www.linkedin.com/company/autarc-energy/'
	link facebook, url='https://www.facebook.com/autarcenergy'
	link instagram, url='https://www.instagram.com/autarcenergy/'
	link YouTube, url='https://www.youtube.com/@getautarc'
	StaticText PRODUCTS
	link For young companies, url='https://www.autarc.energy/en/loesungen/fuer-junge-firmen'
	link For established companies, url='https://www.autarc.energy/en/loesungen/fuer-etablierte-unternehmen'
	link For energy suppliers, url='https://www.autarc.energy/en/loesungen/fur-energieversorger-stadtwerke'
	link For energy consultants, url='https://www.autarc.energy/en/loesungen/fuer-energieberater-ingenieurbueros'
	link For solar engineers/electricians, url='https://www.autarc.energy/en/loesungen/fur-solarteure-elektriker'
	StaticText RESOURCES
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	link Customers, url='https://www.autarc.energy/en/kunden/kunden'
	link Support, url='https://www.autarc.energy/en/support'
	link Knowledge, url='https://www.autarc.energy/en/wissen'
	link Rates, url='https://www.autarc.energy/en/preise'
	link Imprint, url='https://www.autarc.energy/en/impressum'
	link Data protection, url='https://www.autarc.energy/en/datenschutz'
	link TERMS AND CONDITIONS, url='https://www.autarc.energy/en/agb'
	StaticText COMPANIES
	link About us, url='https://www.autarc.energy/en/uber-uns'
	link jobs, url='https://www.autarc.energy/en/jobs'
	link Press, url='https://www.autarc.energy/en/presse'
	link Events, url='https://www.autarc.energy/en/events'
	link Partner program, url='https://www.autarc.energy/en/partnerprogramm'
	StaticText autarc GmbH © 2024.
	StaticText All rights reserved
	[1914] button Open Intercom Messenger, center=(1876,1036)
		image
		image
```
</details>



```
RootWebArea autarc – Die Wärmepumpen-Software, focused, url='https://www.autarc.energy/en'
	dialog Diese Webseite verwendet Cookies, modal=True
		image Logo, url='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAC4AAAAuCAYAAABXuSs3AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAQBSURBVGhD7VpJKLZtFDYskKlkzpjMIUOGQoqIlIUFFmYZEskQkj1CGUNYUCKhLAylzAvCghA+Q1aGiJAI53edz/28ff/n3+npf+s5dfXe59znvs/1nPucs0HjU3594kbNAM4aD58gNQM48xd8t/l/BjgrxOWEQlxuKMTlhkJcbijE5YZCXG4oxOWGQpyRmJhIdXV1FBAQ8O3+D+JniQ8MDBAkLS3t2/0fxN/EY2JiaHx8nFZWVqi7u5t8fX3ZHhcXR0NDQxQbGyv5GhsbM9nm5mZqbGyks7MzJr6xsUGjo6NkYWFBJiYmVF9fz/dNTU1RTk4On9XS0qLOzk6O4e/vT/39/TQzM0OGhobk4uJCHR0dND8/T2NjY5SRkSHF/MKfxPPy8jjwy8sLbW9v8/r5+ZlcXV2psLCQ9aqqKukCa2trtl1fX9Pq6iq9vb2x/vr6So+PjxQfH0/7+/ts293dpZubG143NTWRpqYm3d/fs/7x8cG/7+/vVFpaKtkfHh74F9Lb2yvF/YSKuK6uLh0eHnIgAwMDdkhKSuJDbW1tlJyczOuSkhLpAisrKw52enrK5/v6+tgnPz+f9ZqaGrq7u6Pc3FzpzMnJCfs4OTnR3t4er4+Ojig4OJgzfXV1xbaCggLS09Mjd3d3Oj8/Z1tgYKC4R0VcW1ubjIyMKCoqiqqrq/mpt7a2+MDw8DClpqbyuqysTCIB4hAQh97S0sK6qHEdHR1yc3Oj9PR06unpodnZWc4mMuzn58evAEFM+Ht5ebG+vr4uxQBsbGwoJCSEzMzMhE1FHECGhCAby8vLvB4ZGWEyEDyl8EfWIMfHx6y3trayLurY29ub9yAop8XFRbq8vOSSAvGDgwP+CPQC/CMjI9l3cnJSivEfUBEX9XpxccENAlt0dDTbkPHs7Gxeo2mwB5SXl7MNJQa9vb2d9czMTNYHBwdZz8rKks7AF4KGxBr9YG5uznv29va8h14QNqC2tpYWFhYoNDRU2FTE8dUQNFVCQgKlpKTQ7e0t2yYmJvipIAiE5hJlAREZLyoqYh2NXVFRQUtLS6zjgzCtcI8Q1DTOIfumpqYSSUwZCHqtsrJS0p+enji5X34q4kBxcTFPESF4Msjc3BzvNzQ0SBMAgkvR+Wg4TAl9fX2anp7+2v3dpGtra1/a7zG5s7PD66CgIC4VxMPIFBzQF11dXewjZHNzk3x8fCSfT/xJHLCzs6Pw8HBydHRk3dPTkxwcHKR9jMaIiAiytbVlHc3n7OzMxIUPyiAsLIzXmNfILgDd0tKSPDw8eGKgR3Aeg0GcFUBM8PgXYYG/iasJFOJyQyEuNxTickMhLjcU4nJDIS43FOJyg4mr7Z/E1fCfEDR+/QN5VWLLOegHAwAAAABJRU5ErkJggg=='
		link Logo - opens in a new window, url='https://www.cookiebot.com/de/was-steckt-hinter-powered-by-cookiebot/'
			image
```
<details><summary>Show more</summary>

```
		button Banner schließen
			image
		tablist, orientation='horizontal'
			tab Zustimmung, selected=True
			tab Details, selected=False
			tab Über Cookies, selected=False
		tabpanel Zustimmung
			heading Diese Webseite verwendet Cookies
			group Consent Selection
				Legend
				LabelText
					strong
						StaticText Notwendig
				checkbox Notwendig, checked='true', disabled=True
				LabelText
					[113] strong, center=(847,639), inner_text=Präferenzen
						StaticText Präferenzen
				[115] checkbox Präferenzen, center=(847,679), checked=, contenteditable=True, type=checkbox
				LabelText
					[119] strong, center=(1072,639), inner_text=Statistiken
						StaticText Statistiken
				[121] checkbox Statistiken, center=(1072,679), checked=, contenteditable=True, type=checkbox
				LabelText
					[125] strong, center=(1298,639), inner_text=Marketing
						StaticText Marketing
				[127] checkbox Marketing, center=(1298,679), checked=, contenteditable=True, type=checkbox
		[999] button Ablehnen, center=(672,763)
		[1000] button Auswahl erlauben, center=(960,763)
		[1003] button Alle zulassen, center=(1248,763)
	banner
		[1012] link, center=(87,45), url='https://www.autarc.energy/en'
			image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/655bf2270fe58d910009ed6b_autrc-logo.png'
		navigation
			[1049] button Products, center=(197,45), expanded=True, focused, hasPopup='menu'
			navigation Products
				StaticText products
				[1056] link Heat pump check Quick test for the suitability of a heat pump, center=(362,171), inner_text=Heat pump check
Quick test for the suitability of a heat pump, url='https://www.autarc.energy/en/produkte/warmepumpen-check'
					heading Heat pump check
				[1059] link Customer portal Modern customer communication, center=(362,223), inner_text=Customer portal
Modern customer communication, url='https://www.autarc.energy/en/produkte/kunden-portal'
					heading Customer portal
				[1062] link Quotation tool 90% better offers due to higher data quality, center=(362,275), inner_text=Quotation tool
90% better offers due to higher data quality, url='https://www.autarc.energy/en/produkte/angebotstool'
					heading Quotation tool
				[1065] link LiDAR scan with artificial intelligence Heat load and hydraulic balance in 10 minutes, center=(362,327), inner_text=LiDAR scan with artificial intelligence
Heat load and hydraulic balance in 10 minutes, url='https://www.autarc.energy/en/produkte/lidar-scan'
					heading LiDAR scan with artificial intelligence
				[1069] link Heat load calculation Roomwise heating load in accordance with DIN 12831, center=(678,172), inner_text=Heat load calculation
Roomwise heating load in accordance with DIN 12831, url='https://www.autarc.energy/en/produkte/heizlastberechnung'
					heading Heat load calculation
				[1072] link Hydraulic balancing According to VdZ procedures, center=(678,224), inner_text=Hydraulic balancing
According to VdZ procedures, url='https://www.autarc.energy/en/produkte/hydraulischer-abgleich-b'
					heading Hydraulic balancing
				[1075] link Heating surface design Optimize your customer's radiators, center=(678,276), inner_text=Heating surface design
Optimize your customer's radiators, url='https://www.autarc.energy/en/produkte/heizflachenauslegung'
					heading Heating surface design
				[1078] link Funding service Apply for funding for your customer, center=(678,328), inner_text=Funding service
Apply for funding for your customer, url='https://www.autarc.energy/en/produkte/foerderhilfe'
					heading Funding service
				StaticText integrations
				[1083] link Craftsman software, center=(994,163), url='https://www.autarc.energy/en/produkte/handwerkersoftware'
					heading Craftsman software
				[1085] link CRM systems, center=(994,199), url='https://www.autarc.energy/en/produkte/crm'
					heading CRM systems
			[1088] button Solutions, center=(291,45), expanded=False, hasPopup='menu'
			[1110] link Customers, center=(392,45), url='https://www.autarc.energy/en/kunden/kunden'
			[1112] button Knowledge, center=(499,45), expanded=False, hasPopup='menu'
			[1126] button About us, center=(600,45), expanded=False, hasPopup='menu'
			[1156] link Jobs, center=(678,45), url='https://www.autarc.energy/en/jobs'
			[1157] link Rates, center=(744,45), url='https://www.autarc.energy/en/preise'
			article
				[1160] link WhatsApp Chat, center=(1613,45), url='https://wa.me/4915792312671'
					image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6732237bf724025079599592_whatsapp-logo-grey.png'
				[1163] link Login, center=(1732,45), url='https://app.autarc.energy/login'
				[1164] link Book a demo, center=(1826,45), url='https://www.autarc.energy/en/demo-buchen'
	link künstliche Intelligenz bei autarc energy Autarc AI — app out, scan on, heat load in 15 minutes Pfeil nach rechts, url='https://www.autarc.energy/en/produkte/lidar-scan'
		image künstliche Intelligenz bei autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65691ad146aa7fb03353521b_sparkle.svg'
		image Pfeil nach rechts, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65691afb341494ef5e90d89f_arrowRight.svg'
	heading autarc is a better way
	heading to plan heat pumps
	StaticText Discover the new standard for sales and planning of heat pumps. Heat load, hydraulic balancing (B) and funding application in just a few clicks.
	form Email Form Start
		textbox Business email address*, required
		button Book a demo
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
	StaticText 14-day free trial
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
	StaticText Set up in just 3 minutes
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
	StaticText Can be canceled at any time
	image autarc home screen, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b313d2e56f36107c33e_autarc-home-screen-1-min-p-1080.png'
	StaticText We are a member of
	image Bunderverband Wärmepumpe e.V. autarc energy Software Planung wärmepumpe hydraulischer abgleich, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/651191ce20e01ee0dab72cf7_Logo_BWP_gross.png'
	image DIN-logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65e9aa81ef1b78df023333d4_DIN-mitgliedslogo-blau-autarc%20energy-p-500.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/66c222175ebc6be23eb42a83_EE_EnergieeffizienzExperten_Logo_M-removebg-p-500.webp'
	StaticText Software for the best heating engineers.
	StaticText From the next generation to established businesses, 250+ customers already trust us.
	image Vinci Unternehmenslogo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6391e678268622418d2bfeb9_Vinci.png'
	image Daume Gruppe Unternehmenslogo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6391e67829871fbe96bc762b_Daume.png'
	image Theodor Bergmann Berlin, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b38e65330789e606fe27_Theodor%20Bergmann%20Berlin.svg'
	image Vattenfall, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b38fbf4bdd782aa5eac1_Vattenfall.svg'
	image mf mercedöl, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b48810e117cbe394c07b_mf%20mercedoil%20gmbh%20berlin.svg'
	image Koster, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b488fd4ac778e955fc38_koster%20gmbh%20berlin%20heizung.svg'
	image Hörmann Haustechnike, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646269795ed5193ea3b87531_hoermann-haustechnik%201.svg'
	image WagEnergie aus Duderstadt, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646269792dc26a20312e9008_logo_wagenergie_rgb-removebg-preview%201.svg'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/66cffa26a6addc029265bd2f_nuuEnergy_logo.png'
	image Klaus Klein Design Bad, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d54581270477c9dbd8_Klaus%20Klein%20Gmbh.svg'
	image Team Steffen, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d469b7a5456ecd20e9_Team%20Steffen.svg'
	image Thomas Mehner Haustechnik Unternehmenslogo Braunschweig, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/63c69c6f3159457dc6248ccd_Mehner.svg'
	image Berner Elektrotechnik, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646280cc96faa3e03621627f_Berner%20Elektrotechnik.svg'
	StaticText Benefits
	heading Why autarc?
	image Uhr Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699c018f5de07a866d2440_Group%20482166.svg'
	StaticText The fastest way to data
	StaticText With autarc, you can quickly access via
	StaticText 600 relevant house data
	StaticText thanks to artificial intelligence.
	StaticText In just 10 minutes
	StaticText enter all necessary information, supplemented with pictures at the customer's site. This step can also be taken over by inexperienced colleagues.
	image Sicherheit Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699c01f9738c8487d50db2_Group%20482167.svg'
	StaticText Higher offer quality
	StaticText Through the data
	StaticText Does quality increase
	StaticText your offers
	StaticText by 90%
	StaticText . With precise and comprehensive information, you can offer tailor-made solutions. For you, this means:
	StaticText more successful deals
	StaticText And a
	StaticText quick contract processing
	StaticText .
	image Schloss Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699c0166880e76db41fee8_Group%20482168.svg'
	StaticText No plant failures
	StaticText Wrongly dimensioned or timed heat pumps are a thing of the past. Our precise analysis enables a
	StaticText optimal system planning
	StaticText . The result is powerful, efficient heat pumps that are precisely tailored to the needs of your customers. For you, that means:
	StaticText fewer plant failures
	StaticText and therefore
	StaticText happier customers
	StaticText .
	StaticText Known from
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731bac75b8721c35ff4e_image%201183-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731b3d28cd7e20c5abab_image%201182-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731bc2a0f1867d6fceff_image%201181-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731b50ec48404304f555_image%201186-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731b08a0892e1a0b8b00_image%201187-min.png'
	StaticText Solution
	heading autarc has what you need.
	heading The most efficient planning and sales process.
	image Nummer 1, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699fb7f77c77287929fea5_Group%20482169.svg'
	StaticText Heat pump check and customer portal
	StaticText Quick aptitude test, modern communication
	StaticText In
	StaticText few minutes
	StaticText Does your customer find out whether a heat pump is suitable for their home. He then gets access to
	StaticText your customer portal
	StaticText , the hub for all communication. From the
	StaticText initial assessment
	StaticText up to the final installation
	StaticText keep your customers up to date.
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Quick aptitude test in just 3 minutes
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customizable interface
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Forecast for higher conversion
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Accessible 24/7 from all devices
	image Wärmepumpen check autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b3162da9b852b633038_autarc-home-screen-2-min.png'
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText 1 hour time saving
	StaticText Your customer provides you with important information for your calculations
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText +75%
	StaticText Higher conversion of requests
	image Nummer 2, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699fb6909cb9881fef548c_Group%20482170.svg'
	StaticText On-site visit
	StaticText Input and calculation in one step
	StaticText In just 15 minutes
	StaticText Do you get a result for
	StaticText Heat load, sound emissions, heating surface design
	StaticText and
	StaticText hydraulic balancing (B)
	StaticText . In addition, a suitable offer is generated. Means for you:
	StaticText less time for data recording
	StaticText , more time to sell the plant.
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Mobile availability on tablet/smartphone
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Room capture with 3D scanner
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Automatic radiator detection (beta)
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText All calculations in one pdf. Report
	image LiDAR Scan für Heizlast und hydraulischer abgleich von autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b3163cd25a8d73ccae9_autarc-home-screen-3-min.png'
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText 600+
	StaticText Data for the best offers and plant planning
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText >10 hours time saving
	StaticText For heat load, layout, sound testing, supply and hydraulic adjustment
	image Nummer 3, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699fb7415c82498e334224_Group%20482171.svg'
	StaticText Specialist partner portal
	StaticText One software for everything related to the heat pump
	StaticText Everything is managed centrally in the specialist partner portal. It allows the generation of
	StaticText Reports
	StaticText , processing of
	StaticText Funding
	StaticText , the creation of
	StaticText VDZ forms
	StaticText , the
	StaticText startup
	StaticText of plants and
	StaticText maintenancies
	StaticText .
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Collaborate with teammates
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Generating heat pump reports
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Planning of systems including heating surfaces
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Funding and VDZ forms
	image Screen von der Projektübersicht der autarc energy software, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b314ee49de84aad0baa_autarc-home-screen-4-min.png'
	Iframe Auf Trustpilot veröffentlichte Kundenbewertungen
		RootWebArea Trustpilot Custom Widget, url='https://widget.trustpilot.com/trustboxes/5419b6a8b0d04a076446a9ad/index.html?templateId=5419b6a8b0d04a076446a9ad&businessunitId=63ca54b68fcd1c82bbeabefb#locale=de-DE&styleHeight=50px&styleWidth=100%25&theme=light&minReviewCount=0&styleAlignment=center'
			link Sehen Sie unsere 38 Bewertungen auf Trustpilot, url='https://de.trustpilot.com/review/autarc.energy?utm_medium=trustbox&utm_source=MicroReviewCount'
				[a12] strong, center=(919,5736)
					StaticText 38
				[a16] image Trustpilot, center=(1084,5734)
	StaticText Work together
	StaticText 10x faster.
	StaticText autarc was developed so that you and your colleagues get the most out of sales and planning for heating installations.
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	image iPhone Screen autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a8667dd7fe207f4da02c_autarc-Screen-5.svg'
	image Angebotstool autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a8a36a1ea6c7b7f32d39_autarc-home-screen-5-p-800.png'
	image Wärmepumpen Report autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a8a305876884a29298b2_autarc-home-screen-5-1-p-800.png'
	StaticText Meets all requirements
	StaticText And more
	StaticText autarc has what you need and is therefore the leading provider of heat pump planning.
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	StaticText requests
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Overview of all inquiries
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText High conversion prediction
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Share projects with customers
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customizable interface
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Create customer file
	StaticText requests
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText All climate data
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heat load calculation
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heating surface design
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText sound emissions
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Indicative price offers
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Funding
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText manufacturer's instructions
	StaticText installation
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Auto Inspection of delivery measures
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customizable checklists
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Online orders
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Material extracts
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Foundation instructions
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Annual performance figure
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Safety distances
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Installation site with augmented reality
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText valve settings
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText pump delivery heights
	StaticText furtherance
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Review of available funding
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Interface to BAFA
	StaticText + more
	StaticText “Since we've been using autarc, we've been driving
	StaticText We no longer go directly to every customer
	StaticText . Through the
	StaticText Qualification
	StaticText During the heat pump check, we only deal with customers who are really interested in a heat pump.”
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569c64166880e76db5e38ca_Ellipse%20392.svg'
	StaticText Philip Walter
	StaticText Managing Director
	StaticText Thomas Mehner Haustechnik
	StaticText Our guide
	StaticText The ultimate guide to
	StaticText Heat pump house visits 2024 are here!
	link Learn more, url='https://www.autarc.energy/en/leitfaden'
	image autarc Leitfaden für Wärmepumpen Hausbesuche, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/657499757d7f5fa4e98b8022_Group%20482127.png'
	StaticText Leading manufacturers
	StaticText Works with all manufacturers and types
	StaticText of heat pumps
	link Learn more, url='https://www.autarc.energy/en/wissen'
	image Übersicht verfügbarer Hersteller in der autarc energy software, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569d79d08885f64dec7e0fa_Group%20482173.svg'
	StaticText Our software works with all manufacturers.
	StaticText You can find a small selection here.
	image Danfoss, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d582485650889931f1_Danfoss.svg'
	image IMI Heimeier, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d54eaafc68f6aa619c_IMI%20Heimeier.svg'
	image Oventrop, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d5fb6ee1d0f1b04b25_Oventrop.svg'
	image Resideo Honeywell, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64628132380e5ecaac062cd8_Resideo%20Honeywell.svg'
	image Viessmann, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b66ad7095943cebd8e6f_Viessmann.svg'
	image Vaillant Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65c8695df776be3aa90_Vaillant.svg'
	image Stiebel Eltron Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65c121acb6a85783b4a_Stiebel%20Eltron.svg'
	image Daikin Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65c4793c63f2747af30_Daikin.svg'
	image Buderus Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65cfc6d39159e072da0_Buderus.svg'
	image Samsung Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65cfc6d39159e072dac_Samsung.svg'
	image Bosch Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65d97eba92836ed04fc_Bosch.svg'
	StaticText Ready to start?
	StaticText Discover all our solutions or book a demo to test autarc free of charge.
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	image Sicherheit Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8318594f792728e68_disputeProtection.svg'
	StaticText 100% DIN compliant
	StaticText We comply with all standards in our calculations
	image Kalender Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8a072dc7ea8656caf_calendar.svg'
	StaticText 24/7 available
	StaticText Accessible from all devices throughout the year
	image Person Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8f538c85e3faedc85_person.svg'
	StaticText Personal contact
	StaticText We take time to answer your concerns, no question remains unanswered
	StaticText Testimonials
	heading What our customers say.
	heading How Daume plans 270 heat pumps per year using Autarc.
	Iframe Daume GmbH über Ihre Erfahrung mit der einfachsten Planungssoftware für Wärmepumpen | autarc
		RootWebArea Daume GmbH über Ihre Erfahrung mit der einfachsten Planungssoftware für Wärmepumpen | autarc - YouTube, url='https://www.youtube.com/embed/mEkOYnmscdw?rel=0&controls=1&autoplay=1&mute=1&start=0'
			[b26] Video, center=(960,12134)
			generic, atomic
			slider Seek slider value='0', orientation='horizontal'
			group
				slider Click or scroll the panel for the precise seeking. value='0', orientation='horizontal'
			[b409] button Pause (k), center=(395,12451)
				image
			[b414] button Unmute (m), center=(438,12451)
				image
			slider Volume value='100', orientation='horizontal'
				group
			StaticText 0:00
			StaticText /
			StaticText 3:30
			[b430] button Warum autarc?, center=(942,12451)
				generic Warum autarc?
			[b436] button Subtitles/closed captions unavailable, center=(1381,12451)
				image
			[b438] button Settings, center=(1421,12451), expanded=False, hasPopup='menu'
				image
			[b440] link Watch on YouTube, center=(1474,12451), url='https://www.youtube.com/watch?v=mEkOYnmscdw'
			[b447] button Full screen (f), center=(1528,12451)
				image
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText Premium license
	StaticText Everything you need to make your business efficient.
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText Products in use
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heat pump check
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customer portal
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText iOS app for iPad
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heat pump report
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText >270 heat pumps
	StaticText Install thumbs per year and plan them with self-tarc.
	StaticText Your potential
	heading Calculate your savings potential.
	heading With autarc, we make you even more efficient.
	link Available soon, url='https://www.autarc.energy/en#'
	StaticText “With autarc, we can implement method B in
	StaticText Create under 1 hour
	StaticText , much faster than our previous solutions. We can see that our customers are impressed that everything comes from a single source.”
	image Portrait Stefan Möllenhoff Vinci Energies, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569ff3c2615a40b667d1a1d_Group%20482130.svg'
	StaticText Stefan Möllenhoff
	StaticText Executive
	StaticText Vinci Energies
	StaticText Would you like to stay up to date?
	StaticText Sign up for our newsletter
	form Newsletter Form
		textbox First name *, required
		textbox Last name *, required
		textbox Business email address*, required
		button Subscribe
	StaticText Frequently asked questions
	StaticText We can help answer questions and resolve issues. Have a look at our frequently asked questions, send us a message or give us a call.
	link Learn more, url='https://hilfe.autarc.energy/de/'
	image Bunderverband Wärmepumpe e.V. autarc energy Software Planung wärmepumpe hydraulischer abgleich, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/651191ce20e01ee0dab72cf7_Logo_BWP_gross.png'
	image INVEST Förderung BAFA für autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65085835fa950284eb14fffa_INVEST_Logo_URL_rote_URL_RZ-p-500.png'
	image European Social Fund, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/63e298e1d376b73610c0daee_Google%20form%20cover%20-%20Accelerator%20team-p-500.png'
	link Autarc Logo, url='https://www.autarc.energy/en'
		image Autarc Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6339884edcb06d6ae77fe900_autarc%20logo_black.svg'
	link, url='https://wa.me/4915792312671'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6732224a26847515db644115_whatsapp.svg'
	link, url='https://apps.apple.com/app/autarc/id6464311183'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/656a05f75545a6a3e2b24fab_Group%20482167.svg'
	link, url='https://app.autarc.energy/login'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/656a05f7d8a01b8c1b94e2a4_Group%20482166.svg'
	button Language, expanded=False, hasPopup='menu'
	StaticText PRODUCTS
	link Heat pump check, url='https://www.autarc.energy/en/produkte/warmepumpen-check'
	link Customer portal, url='https://www.autarc.energy/en/produkte/kunden-portal'
	link Quotation tool, url='https://www.autarc.energy/en/produkte/angebotstool'
	link LiDAR scan, url='https://www.autarc.energy/en/produkte/lidar-scan'
	link Heat load calculation, url='https://www.autarc.energy/en/produkte/heizlastberechnung'
	link Hydraulic balancing, url='https://www.autarc.energy/en/produkte/hydraulischer-abgleich-b'
	link Heating surface design, url='https://www.autarc.energy/en/produkte/heizflachenauslegung'
	link Funding service, url='https://www.autarc.energy/en/produkte/foerderhilfe'
	StaticText INTEGRATIONS
	link Craftsman software, url='https://www.autarc.energy/en/produkte/handwerkersoftware'
	link CRM, url='https://www.autarc.energy/en/produkte/crm'
	StaticText SOCIAL MEDIA
	link Linkedin, url='https://www.linkedin.com/company/autarc-energy/'
	link facebook, url='https://www.facebook.com/autarcenergy'
	link instagram, url='https://www.instagram.com/autarcenergy/'
	link YouTube, url='https://www.youtube.com/@getautarc'
	StaticText PRODUCTS
	link For young companies, url='https://www.autarc.energy/en/loesungen/fuer-junge-firmen'
	link For established companies, url='https://www.autarc.energy/en/loesungen/fuer-etablierte-unternehmen'
	link For energy suppliers, url='https://www.autarc.energy/en/loesungen/fur-energieversorger-stadtwerke'
	link For energy consultants, url='https://www.autarc.energy/en/loesungen/fuer-energieberater-ingenieurbueros'
	link For solar engineers/electricians, url='https://www.autarc.energy/en/loesungen/fur-solarteure-elektriker'
	StaticText RESOURCES
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	link Customers, url='https://www.autarc.energy/en/kunden/kunden'
	link Support, url='https://www.autarc.energy/en/support'
	link Knowledge, url='https://www.autarc.energy/en/wissen'
	link Rates, url='https://www.autarc.energy/en/preise'
	link Imprint, url='https://www.autarc.energy/en/impressum'
	link Data protection, url='https://www.autarc.energy/en/datenschutz'
	link TERMS AND CONDITIONS, url='https://www.autarc.energy/en/agb'
	StaticText COMPANIES
	link About us, url='https://www.autarc.energy/en/uber-uns'
	link jobs, url='https://www.autarc.energy/en/jobs'
	link Press, url='https://www.autarc.energy/en/presse'
	link Events, url='https://www.autarc.energy/en/events'
	link Partner program, url='https://www.autarc.energy/en/partnerprogramm'
	StaticText autarc GmbH © 2024.
	StaticText All rights reserved
	[1914] button Open Intercom Messenger, center=(1876,1036)
		image
		image
```
</details>

**Reasoning for action:** By clicking the Products button, I am initiating the process to access the product categories available on the website. This is a crucial first step because it directly leads me to the specific offerings related to heat pumps, as per the user's request to explore those offerings. My next goal is to select the 'Heat pump check' option from the expanded menu.

**Action:** click(1049) # Click on the Products button to explore the product offerings.

**Change Description:** After clicking the 'Products' button, the products menu was expanded to show various offerings such as 'Heat pump check', 'Customer portal', 'Quotation tool', and other services, providing quick access to detailed information about each product.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.autarc.energy/en

https://www.autarc.energy/en/produkte/warmepumpen-check

**Content (before/after):** 

```
RootWebArea autarc – Die Wärmepumpen-Software, focused, url='https://www.autarc.energy/en'
	dialog Diese Webseite verwendet Cookies, modal=True
		image Logo, url='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAC4AAAAuCAYAAABXuSs3AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAQBSURBVGhD7VpJKLZtFDYskKlkzpjMIUOGQoqIlIUFFmYZEskQkj1CGUNYUCKhLAylzAvCghA+Q1aGiJAI53edz/28ff/n3+npf+s5dfXe59znvs/1nPucs0HjU3594kbNAM4aD58gNQM48xd8t/l/BjgrxOWEQlxuKMTlhkJcbijE5YZCXG4oxOWGQpyRmJhIdXV1FBAQ8O3+D+JniQ8MDBAkLS3t2/0fxN/EY2JiaHx8nFZWVqi7u5t8fX3ZHhcXR0NDQxQbGyv5GhsbM9nm5mZqbGyks7MzJr6xsUGjo6NkYWFBJiYmVF9fz/dNTU1RTk4On9XS0qLOzk6O4e/vT/39/TQzM0OGhobk4uJCHR0dND8/T2NjY5SRkSHF/MKfxPPy8jjwy8sLbW9v8/r5+ZlcXV2psLCQ9aqqKukCa2trtl1fX9Pq6iq9vb2x/vr6So+PjxQfH0/7+/ts293dpZubG143NTWRpqYm3d/fs/7x8cG/7+/vVFpaKtkfHh74F9Lb2yvF/YSKuK6uLh0eHnIgAwMDdkhKSuJDbW1tlJyczOuSkhLpAisrKw52enrK5/v6+tgnPz+f9ZqaGrq7u6Pc3FzpzMnJCfs4OTnR3t4er4+Ojig4OJgzfXV1xbaCggLS09Mjd3d3Oj8/Z1tgYKC4R0VcW1ubjIyMKCoqiqqrq/mpt7a2+MDw8DClpqbyuqysTCIB4hAQh97S0sK6qHEdHR1yc3Oj9PR06unpodnZWc4mMuzn58evAEFM+Ht5ebG+vr4uxQBsbGwoJCSEzMzMhE1FHECGhCAby8vLvB4ZGWEyEDyl8EfWIMfHx6y3trayLurY29ub9yAop8XFRbq8vOSSAvGDgwP+CPQC/CMjI9l3cnJSivEfUBEX9XpxccENAlt0dDTbkPHs7Gxeo2mwB5SXl7MNJQa9vb2d9czMTNYHBwdZz8rKks7AF4KGxBr9YG5uznv29va8h14QNqC2tpYWFhYoNDRU2FTE8dUQNFVCQgKlpKTQ7e0t2yYmJvipIAiE5hJlAREZLyoqYh2NXVFRQUtLS6zjgzCtcI8Q1DTOIfumpqYSSUwZCHqtsrJS0p+enji5X34q4kBxcTFPESF4Msjc3BzvNzQ0SBMAgkvR+Wg4TAl9fX2anp7+2v3dpGtra1/a7zG5s7PD66CgIC4VxMPIFBzQF11dXewjZHNzk3x8fCSfT/xJHLCzs6Pw8HBydHRk3dPTkxwcHKR9jMaIiAiytbVlHc3n7OzMxIUPyiAsLIzXmNfILgDd0tKSPDw8eGKgR3Aeg0GcFUBM8PgXYYG/iasJFOJyQyEuNxTickMhLjcU4nJDIS43FOJyg4mr7Z/E1fCfEDR+/QN5VWLLOegHAwAAAABJRU5ErkJggg=='
		link Logo - opens in a new window, url='https://www.cookiebot.com/de/was-steckt-hinter-powered-by-cookiebot/'
			image
```
<details><summary>Show more</summary>

```
		button Banner schließen
			image
		tablist, orientation='horizontal'
			tab Zustimmung, selected=True
			tab Details, selected=False
			tab Über Cookies, selected=False
		tabpanel Zustimmung
			heading Diese Webseite verwendet Cookies
			group Consent Selection
				Legend
				LabelText
					strong
						StaticText Notwendig
				checkbox Notwendig, checked='true', disabled=True
				LabelText
					[113] strong, center=(847,639), inner_text=Präferenzen
						StaticText Präferenzen
				[115] checkbox Präferenzen, center=(847,679), checked=, contenteditable=True, type=checkbox
				LabelText
					[119] strong, center=(1072,639), inner_text=Statistiken
						StaticText Statistiken
				[121] checkbox Statistiken, center=(1072,679), checked=, contenteditable=True, type=checkbox
				LabelText
					[125] strong, center=(1298,639), inner_text=Marketing
						StaticText Marketing
				[127] checkbox Marketing, center=(1298,679), checked=, contenteditable=True, type=checkbox
		[999] button Ablehnen, center=(672,763)
		[1000] button Auswahl erlauben, center=(960,763)
		[1003] button Alle zulassen, center=(1248,763)
	banner
		[1012] link, center=(87,45), url='https://www.autarc.energy/en'
			image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/655bf2270fe58d910009ed6b_autrc-logo.png'
		navigation
			[1049] button Products, center=(197,45), expanded=True, focused, hasPopup='menu'
			navigation Products
				StaticText products
				[1056] link Heat pump check Quick test for the suitability of a heat pump, center=(362,171), inner_text=Heat pump check
Quick test for the suitability of a heat pump, url='https://www.autarc.energy/en/produkte/warmepumpen-check'
					heading Heat pump check
				[1059] link Customer portal Modern customer communication, center=(362,223), inner_text=Customer portal
Modern customer communication, url='https://www.autarc.energy/en/produkte/kunden-portal'
					heading Customer portal
				[1062] link Quotation tool 90% better offers due to higher data quality, center=(362,275), inner_text=Quotation tool
90% better offers due to higher data quality, url='https://www.autarc.energy/en/produkte/angebotstool'
					heading Quotation tool
				[1065] link LiDAR scan with artificial intelligence Heat load and hydraulic balance in 10 minutes, center=(362,327), inner_text=LiDAR scan with artificial intelligence
Heat load and hydraulic balance in 10 minutes, url='https://www.autarc.energy/en/produkte/lidar-scan'
					heading LiDAR scan with artificial intelligence
				[1069] link Heat load calculation Roomwise heating load in accordance with DIN 12831, center=(678,172), inner_text=Heat load calculation
Roomwise heating load in accordance with DIN 12831, url='https://www.autarc.energy/en/produkte/heizlastberechnung'
					heading Heat load calculation
				[1072] link Hydraulic balancing According to VdZ procedures, center=(678,224), inner_text=Hydraulic balancing
According to VdZ procedures, url='https://www.autarc.energy/en/produkte/hydraulischer-abgleich-b'
					heading Hydraulic balancing
				[1075] link Heating surface design Optimize your customer's radiators, center=(678,276), inner_text=Heating surface design
Optimize your customer's radiators, url='https://www.autarc.energy/en/produkte/heizflachenauslegung'
					heading Heating surface design
				[1078] link Funding service Apply for funding for your customer, center=(678,328), inner_text=Funding service
Apply for funding for your customer, url='https://www.autarc.energy/en/produkte/foerderhilfe'
					heading Funding service
				StaticText integrations
				[1083] link Craftsman software, center=(994,163), url='https://www.autarc.energy/en/produkte/handwerkersoftware'
					heading Craftsman software
				[1085] link CRM systems, center=(994,199), url='https://www.autarc.energy/en/produkte/crm'
					heading CRM systems
			[1088] button Solutions, center=(291,45), expanded=False, hasPopup='menu'
			[1110] link Customers, center=(392,45), url='https://www.autarc.energy/en/kunden/kunden'
			[1112] button Knowledge, center=(499,45), expanded=False, hasPopup='menu'
			[1126] button About us, center=(600,45), expanded=False, hasPopup='menu'
			[1156] link Jobs, center=(678,45), url='https://www.autarc.energy/en/jobs'
			[1157] link Rates, center=(744,45), url='https://www.autarc.energy/en/preise'
			article
				[1160] link WhatsApp Chat, center=(1613,45), url='https://wa.me/4915792312671'
					image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6732237bf724025079599592_whatsapp-logo-grey.png'
				[1163] link Login, center=(1732,45), url='https://app.autarc.energy/login'
				[1164] link Book a demo, center=(1826,45), url='https://www.autarc.energy/en/demo-buchen'
	link künstliche Intelligenz bei autarc energy Autarc AI — app out, scan on, heat load in 15 minutes Pfeil nach rechts, url='https://www.autarc.energy/en/produkte/lidar-scan'
		image künstliche Intelligenz bei autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65691ad146aa7fb03353521b_sparkle.svg'
		image Pfeil nach rechts, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65691afb341494ef5e90d89f_arrowRight.svg'
	heading autarc is a better way
	heading to plan heat pumps
	StaticText Discover the new standard for sales and planning of heat pumps. Heat load, hydraulic balancing (B) and funding application in just a few clicks.
	form Email Form Start
		textbox Business email address*, required
		button Book a demo
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
	StaticText 14-day free trial
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
	StaticText Set up in just 3 minutes
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
	StaticText Can be canceled at any time
	image autarc home screen, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b313d2e56f36107c33e_autarc-home-screen-1-min-p-1080.png'
	StaticText We are a member of
	image Bunderverband Wärmepumpe e.V. autarc energy Software Planung wärmepumpe hydraulischer abgleich, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/651191ce20e01ee0dab72cf7_Logo_BWP_gross.png'
	image DIN-logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65e9aa81ef1b78df023333d4_DIN-mitgliedslogo-blau-autarc%20energy-p-500.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/66c222175ebc6be23eb42a83_EE_EnergieeffizienzExperten_Logo_M-removebg-p-500.webp'
	StaticText Software for the best heating engineers.
	StaticText From the next generation to established businesses, 250+ customers already trust us.
	image Vinci Unternehmenslogo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6391e678268622418d2bfeb9_Vinci.png'
	image Daume Gruppe Unternehmenslogo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6391e67829871fbe96bc762b_Daume.png'
	image Theodor Bergmann Berlin, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b38e65330789e606fe27_Theodor%20Bergmann%20Berlin.svg'
	image Vattenfall, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b38fbf4bdd782aa5eac1_Vattenfall.svg'
	image mf mercedöl, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b48810e117cbe394c07b_mf%20mercedoil%20gmbh%20berlin.svg'
	image Koster, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b488fd4ac778e955fc38_koster%20gmbh%20berlin%20heizung.svg'
	image Hörmann Haustechnike, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646269795ed5193ea3b87531_hoermann-haustechnik%201.svg'
	image WagEnergie aus Duderstadt, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646269792dc26a20312e9008_logo_wagenergie_rgb-removebg-preview%201.svg'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/66cffa26a6addc029265bd2f_nuuEnergy_logo.png'
	image Klaus Klein Design Bad, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d54581270477c9dbd8_Klaus%20Klein%20Gmbh.svg'
	image Team Steffen, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d469b7a5456ecd20e9_Team%20Steffen.svg'
	image Thomas Mehner Haustechnik Unternehmenslogo Braunschweig, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/63c69c6f3159457dc6248ccd_Mehner.svg'
	image Berner Elektrotechnik, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646280cc96faa3e03621627f_Berner%20Elektrotechnik.svg'
	StaticText Benefits
	heading Why autarc?
	image Uhr Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699c018f5de07a866d2440_Group%20482166.svg'
	StaticText The fastest way to data
	StaticText With autarc, you can quickly access via
	StaticText 600 relevant house data
	StaticText thanks to artificial intelligence.
	StaticText In just 10 minutes
	StaticText enter all necessary information, supplemented with pictures at the customer's site. This step can also be taken over by inexperienced colleagues.
	image Sicherheit Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699c01f9738c8487d50db2_Group%20482167.svg'
	StaticText Higher offer quality
	StaticText Through the data
	StaticText Does quality increase
	StaticText your offers
	StaticText by 90%
	StaticText . With precise and comprehensive information, you can offer tailor-made solutions. For you, this means:
	StaticText more successful deals
	StaticText And a
	StaticText quick contract processing
	StaticText .
	image Schloss Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699c0166880e76db41fee8_Group%20482168.svg'
	StaticText No plant failures
	StaticText Wrongly dimensioned or timed heat pumps are a thing of the past. Our precise analysis enables a
	StaticText optimal system planning
	StaticText . The result is powerful, efficient heat pumps that are precisely tailored to the needs of your customers. For you, that means:
	StaticText fewer plant failures
	StaticText and therefore
	StaticText happier customers
	StaticText .
	StaticText Known from
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731bac75b8721c35ff4e_image%201183-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731b3d28cd7e20c5abab_image%201182-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731bc2a0f1867d6fceff_image%201181-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731b50ec48404304f555_image%201186-min.png'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6580731b08a0892e1a0b8b00_image%201187-min.png'
	StaticText Solution
	heading autarc has what you need.
	heading The most efficient planning and sales process.
	image Nummer 1, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699fb7f77c77287929fea5_Group%20482169.svg'
	StaticText Heat pump check and customer portal
	StaticText Quick aptitude test, modern communication
	StaticText In
	StaticText few minutes
	StaticText Does your customer find out whether a heat pump is suitable for their home. He then gets access to
	StaticText your customer portal
	StaticText , the hub for all communication. From the
	StaticText initial assessment
	StaticText up to the final installation
	StaticText keep your customers up to date.
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Quick aptitude test in just 3 minutes
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customizable interface
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Forecast for higher conversion
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Accessible 24/7 from all devices
	image Wärmepumpen check autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b3162da9b852b633038_autarc-home-screen-2-min.png'
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText 1 hour time saving
	StaticText Your customer provides you with important information for your calculations
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText +75%
	StaticText Higher conversion of requests
	image Nummer 2, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699fb6909cb9881fef548c_Group%20482170.svg'
	StaticText On-site visit
	StaticText Input and calculation in one step
	StaticText In just 15 minutes
	StaticText Do you get a result for
	StaticText Heat load, sound emissions, heating surface design
	StaticText and
	StaticText hydraulic balancing (B)
	StaticText . In addition, a suitable offer is generated. Means for you:
	StaticText less time for data recording
	StaticText , more time to sell the plant.
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Mobile availability on tablet/smartphone
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Room capture with 3D scanner
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Automatic radiator detection (beta)
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText All calculations in one pdf. Report
	image LiDAR Scan für Heizlast und hydraulischer abgleich von autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b3163cd25a8d73ccae9_autarc-home-screen-3-min.png'
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText 600+
	StaticText Data for the best offers and plant planning
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText >10 hours time saving
	StaticText For heat load, layout, sound testing, supply and hydraulic adjustment
	image Nummer 3, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65699fb7415c82498e334224_Group%20482171.svg'
	StaticText Specialist partner portal
	StaticText One software for everything related to the heat pump
	StaticText Everything is managed centrally in the specialist partner portal. It allows the generation of
	StaticText Reports
	StaticText , processing of
	StaticText Funding
	StaticText , the creation of
	StaticText VDZ forms
	StaticText , the
	StaticText startup
	StaticText of plants and
	StaticText maintenancies
	StaticText .
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Collaborate with teammates
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Generating heat pump reports
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Planning of systems including heating surfaces
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Funding and VDZ forms
	image Screen von der Projektübersicht der autarc energy software, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b314ee49de84aad0baa_autarc-home-screen-4-min.png'
	Iframe Auf Trustpilot veröffentlichte Kundenbewertungen
		RootWebArea Trustpilot Custom Widget, url='https://widget.trustpilot.com/trustboxes/5419b6a8b0d04a076446a9ad/index.html?templateId=5419b6a8b0d04a076446a9ad&businessunitId=63ca54b68fcd1c82bbeabefb#locale=de-DE&styleHeight=50px&styleWidth=100%25&theme=light&minReviewCount=0&styleAlignment=center'
			link Sehen Sie unsere 38 Bewertungen auf Trustpilot, url='https://de.trustpilot.com/review/autarc.energy?utm_medium=trustbox&utm_source=MicroReviewCount'
				[a12] strong, center=(919,5736)
					StaticText 38
				[a16] image Trustpilot, center=(1084,5734)
	StaticText Work together
	StaticText 10x faster.
	StaticText autarc was developed so that you and your colleagues get the most out of sales and planning for heating installations.
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	image iPhone Screen autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a8667dd7fe207f4da02c_autarc-Screen-5.svg'
	image Angebotstool autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a8a36a1ea6c7b7f32d39_autarc-home-screen-5-p-800.png'
	image Wärmepumpen Report autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a8a305876884a29298b2_autarc-home-screen-5-1-p-800.png'
	StaticText Meets all requirements
	StaticText And more
	StaticText autarc has what you need and is therefore the leading provider of heat pump planning.
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	StaticText requests
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Overview of all inquiries
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText High conversion prediction
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Share projects with customers
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customizable interface
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Create customer file
	StaticText requests
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText All climate data
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heat load calculation
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heating surface design
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText sound emissions
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Indicative price offers
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Funding
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText manufacturer's instructions
	StaticText installation
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Auto Inspection of delivery measures
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customizable checklists
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Online orders
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Material extracts
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Foundation instructions
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Annual performance figure
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Safety distances
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Installation site with augmented reality
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText valve settings
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText pump delivery heights
	StaticText furtherance
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Review of available funding
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Interface to BAFA
	StaticText + more
	StaticText “Since we've been using autarc, we've been driving
	StaticText We no longer go directly to every customer
	StaticText . Through the
	StaticText Qualification
	StaticText During the heat pump check, we only deal with customers who are really interested in a heat pump.”
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569c64166880e76db5e38ca_Ellipse%20392.svg'
	StaticText Philip Walter
	StaticText Managing Director
	StaticText Thomas Mehner Haustechnik
	StaticText Our guide
	StaticText The ultimate guide to
	StaticText Heat pump house visits 2024 are here!
	link Learn more, url='https://www.autarc.energy/en/leitfaden'
	image autarc Leitfaden für Wärmepumpen Hausbesuche, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/657499757d7f5fa4e98b8022_Group%20482127.png'
	StaticText Leading manufacturers
	StaticText Works with all manufacturers and types
	StaticText of heat pumps
	link Learn more, url='https://www.autarc.energy/en/wissen'
	image Übersicht verfügbarer Hersteller in der autarc energy software, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569d79d08885f64dec7e0fa_Group%20482173.svg'
	StaticText Our software works with all manufacturers.
	StaticText You can find a small selection here.
	image Danfoss, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d582485650889931f1_Danfoss.svg'
	image IMI Heimeier, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d54eaafc68f6aa619c_IMI%20Heimeier.svg'
	image Oventrop, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d5fb6ee1d0f1b04b25_Oventrop.svg'
	image Resideo Honeywell, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64628132380e5ecaac062cd8_Resideo%20Honeywell.svg'
	image Viessmann, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b66ad7095943cebd8e6f_Viessmann.svg'
	image Vaillant Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65c8695df776be3aa90_Vaillant.svg'
	image Stiebel Eltron Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65c121acb6a85783b4a_Stiebel%20Eltron.svg'
	image Daikin Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65c4793c63f2747af30_Daikin.svg'
	image Buderus Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65cfc6d39159e072da0_Buderus.svg'
	image Samsung Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65cfc6d39159e072dac_Samsung.svg'
	image Bosch Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b65d97eba92836ed04fc_Bosch.svg'
	StaticText Ready to start?
	StaticText Discover all our solutions or book a demo to test autarc free of charge.
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	image Sicherheit Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8318594f792728e68_disputeProtection.svg'
	StaticText 100% DIN compliant
	StaticText We comply with all standards in our calculations
	image Kalender Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8a072dc7ea8656caf_calendar.svg'
	StaticText 24/7 available
	StaticText Accessible from all devices throughout the year
	image Person Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8f538c85e3faedc85_person.svg'
	StaticText Personal contact
	StaticText We take time to answer your concerns, no question remains unanswered
	StaticText Testimonials
	heading What our customers say.
	heading How Daume plans 270 heat pumps per year using Autarc.
	Iframe Daume GmbH über Ihre Erfahrung mit der einfachsten Planungssoftware für Wärmepumpen | autarc
		RootWebArea Daume GmbH über Ihre Erfahrung mit der einfachsten Planungssoftware für Wärmepumpen | autarc - YouTube, url='https://www.youtube.com/embed/mEkOYnmscdw?rel=0&controls=1&autoplay=1&mute=1&start=0'
			[b26] Video, center=(960,12134)
			generic, atomic
			slider Seek slider value='0', orientation='horizontal'
			group
				slider Click or scroll the panel for the precise seeking. value='0', orientation='horizontal'
			[b409] button Pause (k), center=(395,12451)
				image
			[b414] button Unmute (m), center=(438,12451)
				image
			slider Volume value='100', orientation='horizontal'
				group
			StaticText 0:00
			StaticText /
			StaticText 3:30
			[b430] button Warum autarc?, center=(942,12451)
				generic Warum autarc?
			[b436] button Subtitles/closed captions unavailable, center=(1381,12451)
				image
			[b438] button Settings, center=(1421,12451), expanded=False, hasPopup='menu'
				image
			[b440] link Watch on YouTube, center=(1474,12451), url='https://www.youtube.com/watch?v=mEkOYnmscdw'
			[b447] button Full screen (f), center=(1528,12451)
				image
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText Premium license
	StaticText Everything you need to make your business efficient.
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText Products in use
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heat pump check
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Customer portal
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText iOS app for iPad
	image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a14cf04def588ca54038_Group%20482172.svg'
	StaticText Heat pump report
	image Linie in der Farbe lila, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569a2665722965dd00fbc87_Line%20178.svg'
	StaticText >270 heat pumps
	StaticText Install thumbs per year and plan them with self-tarc.
	StaticText Your potential
	heading Calculate your savings potential.
	heading With autarc, we make you even more efficient.
	link Available soon, url='https://www.autarc.energy/en#'
	StaticText “With autarc, we can implement method B in
	StaticText Create under 1 hour
	StaticText , much faster than our previous solutions. We can see that our customers are impressed that everything comes from a single source.”
	image Portrait Stefan Möllenhoff Vinci Energies, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569ff3c2615a40b667d1a1d_Group%20482130.svg'
	StaticText Stefan Möllenhoff
	StaticText Executive
	StaticText Vinci Energies
	StaticText Would you like to stay up to date?
	StaticText Sign up for our newsletter
	form Newsletter Form
		textbox First name *, required
		textbox Last name *, required
		textbox Business email address*, required
		button Subscribe
	StaticText Frequently asked questions
	StaticText We can help answer questions and resolve issues. Have a look at our frequently asked questions, send us a message or give us a call.
	link Learn more, url='https://hilfe.autarc.energy/de/'
	image Bunderverband Wärmepumpe e.V. autarc energy Software Planung wärmepumpe hydraulischer abgleich, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/651191ce20e01ee0dab72cf7_Logo_BWP_gross.png'
	image INVEST Förderung BAFA für autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65085835fa950284eb14fffa_INVEST_Logo_URL_rote_URL_RZ-p-500.png'
	image European Social Fund, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/63e298e1d376b73610c0daee_Google%20form%20cover%20-%20Accelerator%20team-p-500.png'
	link Autarc Logo, url='https://www.autarc.energy/en'
		image Autarc Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6339884edcb06d6ae77fe900_autarc%20logo_black.svg'
	link, url='https://wa.me/4915792312671'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6732224a26847515db644115_whatsapp.svg'
	link, url='https://apps.apple.com/app/autarc/id6464311183'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/656a05f75545a6a3e2b24fab_Group%20482167.svg'
	link, url='https://app.autarc.energy/login'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/656a05f7d8a01b8c1b94e2a4_Group%20482166.svg'
	button Language, expanded=False, hasPopup='menu'
	StaticText PRODUCTS
	link Heat pump check, url='https://www.autarc.energy/en/produkte/warmepumpen-check'
	link Customer portal, url='https://www.autarc.energy/en/produkte/kunden-portal'
	link Quotation tool, url='https://www.autarc.energy/en/produkte/angebotstool'
	link LiDAR scan, url='https://www.autarc.energy/en/produkte/lidar-scan'
	link Heat load calculation, url='https://www.autarc.energy/en/produkte/heizlastberechnung'
	link Hydraulic balancing, url='https://www.autarc.energy/en/produkte/hydraulischer-abgleich-b'
	link Heating surface design, url='https://www.autarc.energy/en/produkte/heizflachenauslegung'
	link Funding service, url='https://www.autarc.energy/en/produkte/foerderhilfe'
	StaticText INTEGRATIONS
	link Craftsman software, url='https://www.autarc.energy/en/produkte/handwerkersoftware'
	link CRM, url='https://www.autarc.energy/en/produkte/crm'
	StaticText SOCIAL MEDIA
	link Linkedin, url='https://www.linkedin.com/company/autarc-energy/'
	link facebook, url='https://www.facebook.com/autarcenergy'
	link instagram, url='https://www.instagram.com/autarcenergy/'
	link YouTube, url='https://www.youtube.com/@getautarc'
	StaticText PRODUCTS
	link For young companies, url='https://www.autarc.energy/en/loesungen/fuer-junge-firmen'
	link For established companies, url='https://www.autarc.energy/en/loesungen/fuer-etablierte-unternehmen'
	link For energy suppliers, url='https://www.autarc.energy/en/loesungen/fur-energieversorger-stadtwerke'
	link For energy consultants, url='https://www.autarc.energy/en/loesungen/fuer-energieberater-ingenieurbueros'
	link For solar engineers/electricians, url='https://www.autarc.energy/en/loesungen/fur-solarteure-elektriker'
	StaticText RESOURCES
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	link Customers, url='https://www.autarc.energy/en/kunden/kunden'
	link Support, url='https://www.autarc.energy/en/support'
	link Knowledge, url='https://www.autarc.energy/en/wissen'
	link Rates, url='https://www.autarc.energy/en/preise'
	link Imprint, url='https://www.autarc.energy/en/impressum'
	link Data protection, url='https://www.autarc.energy/en/datenschutz'
	link TERMS AND CONDITIONS, url='https://www.autarc.energy/en/agb'
	StaticText COMPANIES
	link About us, url='https://www.autarc.energy/en/uber-uns'
	link jobs, url='https://www.autarc.energy/en/jobs'
	link Press, url='https://www.autarc.energy/en/presse'
	link Events, url='https://www.autarc.energy/en/events'
	link Partner program, url='https://www.autarc.energy/en/partnerprogramm'
	StaticText autarc GmbH © 2024.
	StaticText All rights reserved
	[1914] button Open Intercom Messenger, center=(1876,1036)
		image
		image
```
</details>



```
RootWebArea Wärmepumpen-Check, focused, url='https://www.autarc.energy/en/produkte/warmepumpen-check'
	banner
		[71] link, center=(87,45), url='https://www.autarc.energy/en'
			image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/655bf2270fe58d910009ed6b_autrc-logo.png'
		navigation
```
<details><summary>Show more</summary>

```
			[108] button Products, center=(197,45), expanded=False, hasPopup='menu'
			[147] button Solutions, center=(291,45), expanded=False, hasPopup='menu'
			[169] link Customers, center=(392,45), url='https://www.autarc.energy/en/kunden/kunden'
			[171] button Knowledge, center=(499,45), expanded=False, hasPopup='menu'
			[185] button About us, center=(600,45), expanded=False, hasPopup='menu'
			[215] link Jobs, center=(678,45), url='https://www.autarc.energy/en/jobs'
			[216] link Rates, center=(744,45), url='https://www.autarc.energy/en/preise'
			article
				[219] link WhatsApp Chat, center=(1613,45), url='https://wa.me/4915792312671'
					image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6732237bf724025079599592_whatsapp-logo-grey.png'
				[222] link Login, center=(1732,45), url='https://app.autarc.energy/login'
				[223] link Book a demo, center=(1826,45), url='https://www.autarc.energy/en/demo-buchen'
	[346] link Products, center=(392,110), url='https://www.autarc.energy/en/produkte/warmepumpen-check#'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/656a0f21ea195dc1b9d7f0ed_chevronRight.svg'
	[348] link Heat pump check, center=(517,110), url='https://www.autarc.energy/en/produkte/warmepumpen-check#'
	heading Classification in minutes
	heading the suitability of the heat pump
	StaticText Discover the new standard for sales and planning of heat pumps.
	StaticText Save up to 12 hours
	StaticText per project!
	[357] link Book a demo, center=(430,527), url='https://www.autarc.energy/en/produkte/warmepumpen-check#email-form'
	image Wärmepumpen check autarc energy, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/65749b3162da9b852b633038_autarc-home-screen-2-min.png'
	StaticText You'll be in good company.
	StaticText An excerpt of the companies that work with autarc on a daily basis.
	image Vinci Unternehmenslogo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6391e678268622418d2bfeb9_Vinci.png'
	image Daume Gruppe Unternehmenslogo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6391e67829871fbe96bc762b_Daume.png'
	image Theodor Bergmann Berlin, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b38e65330789e606fe27_Theodor%20Bergmann%20Berlin.svg'
	image Vattenfall, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b38fbf4bdd782aa5eac1_Vattenfall.svg'
	image mf mercedöl, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b48810e117cbe394c07b_mf%20mercedoil%20gmbh%20berlin.svg'
	image Koster, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6491b488fd4ac778e955fc38_koster%20gmbh%20berlin%20heizung.svg'
	image Hörmann Haustechnike, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646269795ed5193ea3b87531_hoermann-haustechnik%201.svg'
	image WagEnergie aus Duderstadt, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646269792dc26a20312e9008_logo_wagenergie_rgb-removebg-preview%201.svg'
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/66cffa26a6addc029265bd2f_nuuEnergy_logo.png'
	image Klaus Klein Design Bad, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d54581270477c9dbd8_Klaus%20Klein%20Gmbh.svg'
	image Team Steffen, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/643a79d469b7a5456ecd20e9_Team%20Steffen.svg'
	image Thomas Mehner Haustechnik Unternehmenslogo Braunschweig, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/63c69c6f3159457dc6248ccd_Mehner.svg'
	image Berner Elektrotechnik, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/646280cc96faa3e03621627f_Berner%20Elektrotechnik.svg'
	StaticText Understandable questions for your customer
	StaticText In just
	StaticText few minutes
	StaticText Can your customer, the homeowner, fill out our heat pump check. For this,
	StaticText no specific expertise required
	StaticText . Simple questions about his building will allow you to make calculations faster and more reliably later.
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/666961680d167d24e7e2ee24_warmepumpen-check-1-p-500.png'
	StaticText Customizable user interface
	StaticText You have the option of carrying out your heat pump check
	StaticText individually configurable
	StaticText . Ob
	StaticText paints
	StaticText ,
	StaticText logos
	StaticText ,
	StaticText pictures
	StaticText or similar elements — you decide how you want to present yourself to your customer.
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/666961681b741d0e5f50a118_warmepumpen-check-2-p-500.png'
	StaticText Pre-qualification of customer inquiries
	StaticText Your customer's request can be significantly better with autarc
	StaticText prequalified
	StaticText become. For you, this means that you can decide whether a visit is worthwhile or not, what you
	StaticText saves valuable time
	StaticText . By querying contact information online, you can manage inquiries more efficiently.
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/666961687b3adc1a599ceca8_warmepumpen-check-3-p-500.png'
	form Email Form
		heading Book a free demo now
		image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
		StaticText 14-day free trial
		image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
		StaticText Set up in just 3 minutes
		image Checkmark, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/64a7c058e0cfaf4d34a060b3_check_small_2.svg'
		StaticText Can be canceled at any time
		StaticText Tell us a bit about yourself and your company
		StaticText We need the following information to best prepare for our joint appointment.
		LabelText
			StaticText First name *
		textbox First name *, required
		LabelText
			StaticText Last name *
		textbox Last name *, required
		LabelText
			StaticText Email address *
		textbox Email address *, required
		LabelText
			StaticText Phone number *
		textbox Phone number *, required
		textbox value='2', required
		textbox
		LabelText
			StaticText Company name *
		textbox Company name *, required
		LabelText
			StaticText Type *
		combobox Type * value='Heizungsbauer', expanded=False, hasPopup='menu'
			option Heizungsbauer, selected=True
			option Energieberater / Fachplaner, selected=False
			option Energieversorger / Stadtwerke, selected=False
			option Solarteur / Elektriker, selected=False
		LabelText
			checkbox By submitting this form, I confirm that I have the privacy policy I have read and agree to the processing of my personal data by autarc for the stated purposes. If I give my consent, I can withdraw my consent to this processing at any time., checked='true'
			StaticText By submitting this form, I confirm that I have the
			link privacy policy, url='https://www.autarc.energy/en/datenschutz'
			StaticText I have read and agree to the processing of my personal data by autarc for the stated purposes. If I give my consent, I can withdraw my consent to this processing at any time.
		link Demo buchen, url='https://www.autarc.energy/en/produkte/warmepumpen-check#'
	StaticText “Since we've been using autarc, we've been driving
	StaticText We no longer go directly to every customer
	StaticText . Through the
	StaticText Qualification
	StaticText During the heat pump check, we only deal with customers who are really interested in a heat pump.”
	image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569c64166880e76db5e38ca_Ellipse%20392.svg'
	StaticText Philip Walter
	StaticText Managing Director
	StaticText Thomas Mehner Haustechnik
	StaticText Ready to start?
	StaticText Discover all our solutions or book a demo to test autarc free of charge.
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	image Sicherheit Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8318594f792728e68_disputeProtection.svg'
	StaticText 100% DIN compliant
	StaticText We comply with all standards in our calculations
	image Kalender Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8a072dc7ea8656caf_calendar.svg'
	StaticText 24/7 available
	StaticText Accessible from all devices throughout the year
	image Person Symbol, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6569faa8f538c85e3faedc85_person.svg'
	StaticText Personal contact
	StaticText We take time to answer your concerns, no question remains unanswered
	link Autarc Logo, url='https://www.autarc.energy/en'
		image Autarc Logo, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6339884edcb06d6ae77fe900_autarc%20logo_black.svg'
	link, url='https://wa.me/4915792312671'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/6732224a26847515db644115_whatsapp.svg'
	link, url='https://apps.apple.com/app/autarc/id6464311183'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/656a05f75545a6a3e2b24fab_Group%20482167.svg'
	link, url='https://app.autarc.energy/login'
		image, url='https://cdn.prod.website-files.com/62ed3f380e99ef9567e1d072/656a05f7d8a01b8c1b94e2a4_Group%20482166.svg'
	button Language, expanded=False, hasPopup='menu'
	StaticText PRODUCTS
	link Heat pump check, url='https://www.autarc.energy/en/produkte/warmepumpen-check'
	link Customer portal, url='https://www.autarc.energy/en/produkte/kunden-portal'
	link Quotation tool, url='https://www.autarc.energy/en/produkte/angebotstool'
	link LiDAR scan, url='https://www.autarc.energy/en/produkte/lidar-scan'
	link Heat load calculation, url='https://www.autarc.energy/en/produkte/heizlastberechnung'
	link Hydraulic balancing, url='https://www.autarc.energy/en/produkte/hydraulischer-abgleich-b'
	link Heating surface design, url='https://www.autarc.energy/en/produkte/heizflachenauslegung'
	link Funding service, url='https://www.autarc.energy/en/produkte/foerderhilfe'
	StaticText INTEGRATIONS
	link Craftsman software, url='https://www.autarc.energy/en/produkte/handwerkersoftware'
	link CRM, url='https://www.autarc.energy/en/produkte/crm'
	StaticText SOCIAL MEDIA
	link Linkedin, url='https://www.linkedin.com/company/autarc-energy/'
	link facebook, url='https://www.facebook.com/autarcenergy'
	link instagram, url='https://www.instagram.com/autarcenergy/'
	link YouTube, url='https://www.youtube.com/@getautarc'
	StaticText PRODUCTS
	link For young companies, url='https://www.autarc.energy/en/loesungen/fuer-junge-firmen'
	link For established companies, url='https://www.autarc.energy/en/loesungen/fuer-etablierte-unternehmen'
	link For energy suppliers, url='https://www.autarc.energy/en/loesungen/fur-energieversorger-stadtwerke'
	link For energy consultants, url='https://www.autarc.energy/en/loesungen/fuer-energieberater-ingenieurbueros'
	link For solar engineers/electricians, url='https://www.autarc.energy/en/loesungen/fur-solarteure-elektriker'
	StaticText RESOURCES
	link Book a demo, url='https://www.autarc.energy/en/demo-buchen'
	link Customers, url='https://www.autarc.energy/en/kunden/kunden'
	link Support, url='https://www.autarc.energy/en/support'
	link Knowledge, url='https://www.autarc.energy/en/wissen'
	link Rates, url='https://www.autarc.energy/en/preise'
	link Imprint, url='https://www.autarc.energy/en/impressum'
	link Data protection, url='https://www.autarc.energy/en/datenschutz'
	link TERMS AND CONDITIONS, url='https://www.autarc.energy/en/agb'
	StaticText COMPANIES
	link About us, url='https://www.autarc.energy/en/uber-uns'
	link jobs, url='https://www.autarc.energy/en/jobs'
	link Press, url='https://www.autarc.energy/en/presse'
	link Events, url='https://www.autarc.energy/en/events'
	link Partner program, url='https://www.autarc.energy/en/partnerprogramm'
	StaticText autarc GmbH © 2024.
	StaticText All rights reserved
	[649] button Open Intercom Messenger, center=(1876,1036)
		image
		image
	[657] button Widget öffnen, center=(44,1036)
		image
```
</details>

**Reasoning for action:** By clicking on the link corresponding to 'Heat pump check', I fulfilled the user's requirement to explore the offerings related to heat pumps. This action takes me to the specific page that provides detailed information about the service, which is essential for the user to make an informed decision and to easily book a demo.

**Action:** click(1056) # Click on the Heat pump check link to explore its details.

**Change Description:** After clicking on the 'Heat pump check' link, the browser navigated to a new page titled 'Wärmepumpen-Check', displaying detailed information about the suitability of heat pumps, including a form for booking a demo and showing various companies using the service.

**Screenshot before:****Screenshot after:**---


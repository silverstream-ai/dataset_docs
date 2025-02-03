# Task

**Demo Request User Story**

As a potential customer interested in firmware security solutions,,
I schedule a demo to learn more about the product capabilities,,
so that I can evaluate how Metalware's offerings can meet my organization's security needs.

**Success definition:** Given I am on the product page of Metalware's website after navigating from the homepage.
When I click on the 'Book a Demo' link, fill in my company email and use case description, and submit the demo request form.
Then I should see a confirmation message indicating that my demo request has been successfully submitted.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.metalware.com/

https://www.metalware.com/product

**Content (before/after):** 

```
RootWebArea Metalware, focused, url='https://www.metalware.com/'
	banner
		banner
			[20] link home, center=(472,40), url='https://www.metalware.com/'
				image
```
<details><summary>Show more</summary>

```
			navigation
				[26] link Product, center=(660,40), url='https://www.metalware.com/product'
				[28] button Industries, center=(768,40), expanded=False, hasPopup='menu'
					image
				[38] link Company, center=(882,40), url='https://www.metalware.com/company'
			[41] link Log In, center=(1384,40), url='https://www.metalware.com/#'
			[42] link Book a demo, center=(1504,40), url='https://www.metalware.com/book-a-demo'
	main
		heading Fuzz testing for firmware
		paragraph
			StaticText Automatically detect vulnerabilities to ensure security and safety of embedded devices
		[60] link Book a demo, center=(418,536), url='https://www.metalware.com/book-a-demo'
		image chip, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/6668776d6f506180b9129fa1_chip-p-1080.png'
		image m, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/6668776c6f506180b9129f6c_m.webp'
		StaticText Built by engineers from
		image amazon, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/66687ed810f4a91d5db20e0b_Amazon_Robotics_logo.svg'
		image l3harris, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/66687ed9844aa21704d0c39b_L3Harris_Technologies_logo.svg'
		image space x, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/66687ed82afad9786ed389d5_SpaceX-Logo%201.svg'
		image illustration firmware, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/66688b71c1e6a191beeb1510_Content.webp'
		heading Benefits
			strong
		paragraph
			StaticText Metalware is a binary analysis tool for fuzzing ARM-based embedded software.
		heading
		heading Minimal Setup
		paragraph
			StaticText Metalware automates the complexity of firmware emulation. Simply upload a binary and specify the memory map of the target device. We are protocol-agnostic so you can fuzz any device without manual configuration.
		heading Low False Positives
		paragraph
			StaticText Vulnerabilities are directly relevant to deployed production binaries, eliminating false-positives from unused libraries and features in source code. Metalware automatically clusters related failures for higher signal-to-noise ratio.
		heading Remediation Reports
		paragraph
			StaticText We provide detailed, data-rich reports for efficient remediation including stack trace, program trace, input vectors, and vulnerability mapping to industry standards.
		heading Scalable
		paragraph
			StaticText Unlike existing tools which fuzz on-target, Metalware emulates your firmware and fuzzes off-target which is horizontally and vertically scalable.
		link Product Overview, url='https://www.metalware.com/product'
		image, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/66faf342d060964b8c3e97ed_sdlc.png'
		image, url='https://cdn.prod.website-files.com/placeholder.svg'
		heading Use Cases
			strong
		paragraph
			StaticText Metalware is flexible and scalable, enabling you to use it across any team. Detect defects earlier, saving your team valuable time and cost.
		heading
		heading Supply Chain
		paragraph
			StaticText Metalware doesn't require source code to run, enabling you to analyze third-party software and secure your supply chain.
		heading Development
		paragraph
			StaticText Easily integrate into any development workflow using our API, web interface, or data export. Run it in your CI/CD build pipeline or use it as a manual tool.
		heading Quality Assurance
		paragraph
			StaticText Improve software quality and improve edge cases in your code without compromising innovation, time-to-market, or operational costs.
		heading Product Security
		paragraph
			StaticText Black box testing is one of the top techniques used by hackers. Metalware uncovers zero-day and unknown vulnerabilities before they lead to damaging risks.
		link Product Overview, url='https://www.metalware.com/product'
		heading SECURITY AND COMPLIANCE
		image ITAR, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/6668931c4616a747ae2f0cb8_ITAR.webp'
		heading ITAR registered
		paragraph
			StaticText Supports critical hardware for aerospace & defense
		image AWS, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/6668931cfcfce2e9a8124302_AWS.webp'
		heading AWS GovCloud
		paragraph
			StaticText Approved for AWS GovCloud for highly sensitive government data.
		image soc II, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/6668931cc8f991fed3e069a5_soc%20II.webp'
		heading AICPA SOC Type 2
		paragraph
			StaticText Enterprise-ready compliance
			StaticText (certification in progress)
		heading Reduce risk from hardware threat vectors
		paragraph
			StaticText See how building with Metalware can help you ship your hardware product more securely.
		link Sign Up Now, url='https://www.metalware.com/book-a-demo'
		image, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/6668a5880f48cfe567b77a4f_logo%20decoration.webp'
		image, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/6668a58855ab49a9fad787f6_grid%20bg.webp'
	contentinfo
		link, url='https://www.metalware.com/'
			image
		StaticText Company
		link About, url='https://www.metalware.com/company'
		link Careers, url='https://www.ycombinator.com/companies/metalware/jobs'
		link Terms, url='https://www.metalware.com/terms'
		link Privacy, url='https://www.metalware.com/privacy-policy'
		StaticText Industries
		link Aerospace & Defense, url='https://www.metalware.com/aerospace'
		link Automotive, url='https://www.metalware.com/automotive'
		link Healthcare, url='https://www.metalware.com/healthcare'
		link Industrials, url='https://www.metalware.com/industrials'
		link Consumer Electronics, url='https://www.metalware.com/consumer'
		StaticText Resources
		link Book a demo, url='https://www.metalware.com/book-a-demo'
		link HDL Plugin for VS Code, url='https://hdlcopilot.com/'
		link PDF Reader for Datasheets, url='https://datasheetreader.com/'
		StaticText Contact
		link sales@metalware.com, url='mailto:sales@metalware.io'
		link support@metalware.com, url='mailto:support@metalware.io'
		link careers@metalware.com, url='mailto:careers@metalware.io'
		link press@metalware.com, url='mailto:press@metalware.io'
		link go to twitter, url='https://twitter.com/getmetalware'
			image
		link go to linkedin, url='https://linkedin.com/company/metalwareinc/'
			image
		link go to ycombinator, url='https://www.ycombinator.com/companies/metalware'
			image
		link go to github, url='https://github.com/metalware-inc'
			image
		StaticText © 2024 Metalware. All rights reserved.
```
</details>



```
RootWebArea Product, focused, url='https://www.metalware.com/product'
	banner
		banner
			[23] link home, center=(472,40), url='https://www.metalware.com/'
				image
```
<details><summary>Show more</summary>

```
			navigation
				[29] link Product, center=(660,40), url='https://www.metalware.com/product'
				[31] button Industries, center=(768,40), expanded=False, hasPopup='menu'
					image
				[41] link Company, center=(882,40), url='https://www.metalware.com/company'
			[44] link Log In, center=(1384,40), url='https://www.metalware.com/product#'
			[45] link Book a demo, center=(1504,40), url='https://www.metalware.com/book-a-demo'
	main
		heading Find vulnerabilities in your
		StaticText Reset Controller
		StaticText Sensors
		StaticText UART
		StaticText USB Device
		StaticText Video Device
		StaticText Serial Device
		StaticText ADC
		StaticText Auxiliary Display
		StaticText Audio
		StaticText Clock Control
		StaticText CAN Bus
		StaticText Chargers
		StaticText Coredump Device
		StaticText Counter
		StaticText DAC
		StaticText DMA
		StaticText Display Interface
		StaticText SPI Bus
		StaticText Flash
		StaticText Fuel Gauge
		StaticText GNSS
		StaticText GPIO
		StaticText I2C Device
		StaticText I3C Device
		StaticText IPC Bus
		StaticText LED
		StaticText MIPI Bus
		StaticText PCIe Device
		StaticText PS/2
		StaticText Real-Time Clock
		image, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/66694e3ef44f54cadd21a1a3_Blur-p-1600.png'
		heading How it works
		paragraph
			StaticText Metalware is a black box binary analysis tool for fuzzing embedded architectures like ARM Cortex. We use a hybrid strategy combining symbolic execution and coverage-guided fuzzing, resulting in state-of-the-art code coverage and efficiency compared to other fuzzing techniques.
			StaticText Metalware is protocol-agnostic, enabling you to test serial, bluetooth, wireless, proprietary, and industry-specific protocols without manual configuration.
		StaticText 1
		heading Upload
		paragraph
			StaticText Upload your firmware binary file (.elf or .bin) via API or web interface.
		StaticText 2
		heading Configure
		paragraph
			StaticText Specify the memory map of your target device.
		StaticText 3
		heading Run
		paragraph
			StaticText Metalware automatically performs failure injection and creates detailed vulnerability remediation reports.
		StaticText 4
		heading Analyze
		paragraph
			StaticText Use Metalware Replay Debugger to quickly reproduce and root-cause defects.
		heading Use Cases
		paragraph
			StaticText Discover how Metalware enhances firmware development.
		list
			listitem
				image, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/66695d8bf60dd4b9dde6205e_Graphic-p-500.png'
				heading Medical Devices
				paragraph
					StaticText For medical device developers and manufacturers
				StaticText View
				image Medical Devices, url='https://cdn.prod.website-files.com/66695b3d25c3e48049e70642/666974e5b72784a010a6b452_medical-p-500.png'
			listitem
				image, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/66695d8bf60dd4b9dde6205e_Graphic-p-500.png'
				heading Aerospace & Defense
				paragraph
					StaticText For government agencies, defense contractors, and aerospace companies
				StaticText View
				image Aerospace & Defense, url='https://cdn.prod.website-files.com/66695b3d25c3e48049e70642/66695bb180f9e055fc030a00_Frame%201321315271-2-p-500.jpg'
			listitem
				image, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/66695d8bf60dd4b9dde6205e_Graphic-p-500.png'
				heading Consumer Electronics
				paragraph
					StaticText For consumer electronics companies and suppliers
				StaticText View
				image Consumer Electronics, url='https://cdn.prod.website-files.com/66695b3d25c3e48049e70642/66695b836efc40d1f3adac5b_Frame%201321315271-p-500.jpg'
		heading Ready to Accelerate Your Firmware Development?
		link Book a Demo, url='https://www.metalware.com/book-a-demo'
	contentinfo
		link, url='https://www.metalware.com/'
			image
		StaticText Company
		link About, url='https://www.metalware.com/company'
		link Careers, url='https://www.ycombinator.com/companies/metalware/jobs'
		link Terms, url='https://www.metalware.com/terms'
		link Privacy, url='https://www.metalware.com/privacy-policy'
		StaticText Industries
		link Aerospace & Defense, url='https://www.metalware.com/aerospace'
		link Automotive, url='https://www.metalware.com/automotive'
		link Healthcare, url='https://www.metalware.com/healthcare'
		link Industrials, url='https://www.metalware.com/industrials'
		link Consumer Electronics, url='https://www.metalware.com/consumer'
		StaticText Resources
		link Book a demo, url='https://www.metalware.com/book-a-demo'
		link HDL Plugin for VS Code, url='https://hdlcopilot.com/'
		link PDF Reader for Datasheets, url='https://datasheetreader.com/'
		StaticText Contact
		link sales@metalware.com, url='mailto:sales@metalware.io'
		link support@metalware.com, url='mailto:support@metalware.io'
		link careers@metalware.com, url='mailto:careers@metalware.io'
		link press@metalware.com, url='mailto:press@metalware.io'
		link go to twitter, url='https://twitter.com/getmetalware'
			image
		link go to linkedin, url='https://linkedin.com/company/metalwareinc/'
			image
		link go to ycombinator, url='https://www.ycombinator.com/companies/metalware'
			image
		link go to github, url='https://github.com/metalware-inc'
			image
		StaticText © 2024 Metalware. All rights reserved.
```
</details>

**Reasoning for action:** I reasoned that by clicking the 'Product' link in the navigation bar, I would access detailed information about Metalware's offerings. This step is crucial because it allows me to familiarize myself with the specific capabilities and features of the product, which is a necessary context before scheduling a demo. After understanding the solutions provided, I can proceed to the demo scheduling process with a clear idea of what I wish to explore regarding Metalware's firmware security.

**Action:** click(26) # Click on the Product link in the navigation bar to explore product offerings.

**Change Description:** The browser navigated from the homepage to the 'Product' page of the Metalware website, updating the URL to 'https://www.metalware.com/product', and the main content now displays a section outlining various vulnerabilities and how the Metalware tool operates, replacing previous firmware testing information.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.metalware.com/product

https://www.metalware.com/book-a-demo

**Content (before/after):** 

```
RootWebArea Product, focused, url='https://www.metalware.com/product'
	banner
		banner
			[23] link home, center=(472,40), url='https://www.metalware.com/'
				image
```
<details><summary>Show more</summary>

```
			navigation
				[29] link Product, center=(660,40), url='https://www.metalware.com/product'
				[31] button Industries, center=(768,40), expanded=False, hasPopup='menu'
					image
				[41] link Company, center=(882,40), url='https://www.metalware.com/company'
			[44] link Log In, center=(1384,40), url='https://www.metalware.com/product#'
			[45] link Book a demo, center=(1504,40), url='https://www.metalware.com/book-a-demo'
	main
		heading Find vulnerabilities in your
		StaticText Reset Controller
		StaticText Sensors
		StaticText UART
		StaticText USB Device
		StaticText Video Device
		StaticText Serial Device
		StaticText ADC
		StaticText Auxiliary Display
		StaticText Audio
		StaticText Clock Control
		StaticText CAN Bus
		StaticText Chargers
		StaticText Coredump Device
		StaticText Counter
		StaticText DAC
		StaticText DMA
		StaticText Display Interface
		StaticText SPI Bus
		StaticText Flash
		StaticText Fuel Gauge
		StaticText GNSS
		StaticText GPIO
		StaticText I2C Device
		StaticText I3C Device
		StaticText IPC Bus
		StaticText LED
		StaticText MIPI Bus
		StaticText PCIe Device
		StaticText PS/2
		StaticText Real-Time Clock
		image, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/66694e3ef44f54cadd21a1a3_Blur-p-1600.png'
		heading How it works
		paragraph
			StaticText Metalware is a black box binary analysis tool for fuzzing embedded architectures like ARM Cortex. We use a hybrid strategy combining symbolic execution and coverage-guided fuzzing, resulting in state-of-the-art code coverage and efficiency compared to other fuzzing techniques.
			StaticText Metalware is protocol-agnostic, enabling you to test serial, bluetooth, wireless, proprietary, and industry-specific protocols without manual configuration.
		StaticText 1
		heading Upload
		paragraph
			StaticText Upload your firmware binary file (.elf or .bin) via API or web interface.
		StaticText 2
		heading Configure
		paragraph
			StaticText Specify the memory map of your target device.
		StaticText 3
		heading Run
		paragraph
			StaticText Metalware automatically performs failure injection and creates detailed vulnerability remediation reports.
		StaticText 4
		heading Analyze
		paragraph
			StaticText Use Metalware Replay Debugger to quickly reproduce and root-cause defects.
		heading Use Cases
		paragraph
			StaticText Discover how Metalware enhances firmware development.
		list
			listitem
				image, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/66695d8bf60dd4b9dde6205e_Graphic-p-500.png'
				heading Medical Devices
				paragraph
					StaticText For medical device developers and manufacturers
				StaticText View
				image Medical Devices, url='https://cdn.prod.website-files.com/66695b3d25c3e48049e70642/666974e5b72784a010a6b452_medical-p-500.png'
			listitem
				image, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/66695d8bf60dd4b9dde6205e_Graphic-p-500.png'
				heading Aerospace & Defense
				paragraph
					StaticText For government agencies, defense contractors, and aerospace companies
				StaticText View
				image Aerospace & Defense, url='https://cdn.prod.website-files.com/66695b3d25c3e48049e70642/66695bb180f9e055fc030a00_Frame%201321315271-2-p-500.jpg'
			listitem
				image, url='https://cdn.prod.website-files.com/666869d7c1a1c583c5f12690/66695d8bf60dd4b9dde6205e_Graphic-p-500.png'
				heading Consumer Electronics
				paragraph
					StaticText For consumer electronics companies and suppliers
				StaticText View
				image Consumer Electronics, url='https://cdn.prod.website-files.com/66695b3d25c3e48049e70642/66695b836efc40d1f3adac5b_Frame%201321315271-p-500.jpg'
		heading Ready to Accelerate Your Firmware Development?
		link Book a Demo, url='https://www.metalware.com/book-a-demo'
	contentinfo
		link, url='https://www.metalware.com/'
			image
		StaticText Company
		link About, url='https://www.metalware.com/company'
		link Careers, url='https://www.ycombinator.com/companies/metalware/jobs'
		link Terms, url='https://www.metalware.com/terms'
		link Privacy, url='https://www.metalware.com/privacy-policy'
		StaticText Industries
		link Aerospace & Defense, url='https://www.metalware.com/aerospace'
		link Automotive, url='https://www.metalware.com/automotive'
		link Healthcare, url='https://www.metalware.com/healthcare'
		link Industrials, url='https://www.metalware.com/industrials'
		link Consumer Electronics, url='https://www.metalware.com/consumer'
		StaticText Resources
		link Book a demo, url='https://www.metalware.com/book-a-demo'
		link HDL Plugin for VS Code, url='https://hdlcopilot.com/'
		link PDF Reader for Datasheets, url='https://datasheetreader.com/'
		StaticText Contact
		link sales@metalware.com, url='mailto:sales@metalware.io'
		link support@metalware.com, url='mailto:support@metalware.io'
		link careers@metalware.com, url='mailto:careers@metalware.io'
		link press@metalware.com, url='mailto:press@metalware.io'
		link go to twitter, url='https://twitter.com/getmetalware'
			image
		link go to linkedin, url='https://linkedin.com/company/metalwareinc/'
			image
		link go to ycombinator, url='https://www.ycombinator.com/companies/metalware'
			image
		link go to github, url='https://github.com/metalware-inc'
			image
		StaticText © 2024 Metalware. All rights reserved.
```
</details>



```
RootWebArea Book a Demo, focused, url='https://www.metalware.com/book-a-demo'
	banner
		banner
			[22] link home, center=(472,40), url='https://www.metalware.com/'
				image
```
<details><summary>Show more</summary>

```
			navigation
				[28] link Product, center=(660,40), url='https://www.metalware.com/product'
				[30] button Industries, center=(768,40), expanded=False, hasPopup='menu'
					image
				[40] link Company, center=(882,40), url='https://www.metalware.com/company'
			[43] link Log In, center=(1384,40), url='https://www.metalware.com/book-a-demo#'
			[44] link Book a demo, center=(1504,40), url='https://www.metalware.com/book-a-demo'
	main
		heading BOOK A DEMO
		paragraph
			StaticText See how Metalware can help you detect firmware bugs so you can develop more secure, reliable applications.
		heading What you can expect:
		image
		paragraph
			StaticText See firsthand how Metalware finds vulnerabilities in your firmware
		image
		paragraph
			StaticText Discuss your use case and hardware requirements in detail
		image
		paragraph
			StaticText Explore Metalware's full development platform, including crash replays and full trace
		heading READY TO SPEAK WITH AN EXPERT?
		form Book a demo
			LabelText
				StaticText Company email*
			[92] textbox Company email*, center=(1280,347), contenteditable=True, required, type=email
			LabelText
				StaticText Describe your use case*
			[95] textbox Describe your use case*, center=(1280,529), contenteditable=True, required
			[96] button Submit, center=(1046,673), contenteditable=True, type=submit
	contentinfo
		[107] link, center=(460,987), url='https://www.metalware.com/'
			image
		StaticText Company
		[113] link About, center=(342,1079), url='https://www.metalware.com/company'
		link Careers, url='https://www.ycombinator.com/companies/metalware/jobs'
		link Terms, url='https://www.metalware.com/terms'
		link Privacy, url='https://www.metalware.com/privacy-policy'
		StaticText Industries
		[119] link Aerospace & Defense, center=(727,1079), url='https://www.metalware.com/aerospace'
		link Automotive, url='https://www.metalware.com/automotive'
		link Healthcare, url='https://www.metalware.com/healthcare'
		link Industrials, url='https://www.metalware.com/industrials'
		link Consumer Electronics, url='https://www.metalware.com/consumer'
		StaticText Resources
		[126] link Book a demo, center=(1026,1079), url='https://www.metalware.com/book-a-demo'
		link HDL Plugin for VS Code, url='https://hdlcopilot.com/'
		link PDF Reader for Datasheets, url='https://datasheetreader.com/'
		StaticText Contact
		[131] link sales@metalware.com, center=(1390,1079), url='mailto:sales@metalware.io'
		link support@metalware.com, url='mailto:support@metalware.io'
		link careers@metalware.com, url='mailto:careers@metalware.io'
		link press@metalware.com, url='mailto:press@metalware.io'
		link go to twitter, url='https://twitter.com/getmetalware'
			image
		link go to linkedin, url='https://linkedin.com/company/metalwareinc/'
			image
		link go to ycombinator, url='https://www.ycombinator.com/companies/metalware'
			image
		link go to github, url='https://github.com/metalware-inc'
			image
		StaticText © 2024 Metalware. All rights reserved.
```
</details>

**Reasoning for action:** I clicked on the 'Book a Demo' link (element 45) because this is a crucial step in the user's journey to schedule a demo for Metalware's firmware security solutions. By following this link, I will be directed to the appropriate page that contains the demo request form, which is necessary for the user to provide their contact information and details about their use case. This action directly supports the user's goal of evaluating how Metalware's offerings can meet their organization's security needs.

**Action:** click(45) # Click on the 'Book a Demo' link to explore options for scheduling a demo.

**Change Description:** After clicking on the 'Book a Demo' link, the browser navigated to the 'Book a Demo' page, displaying a new heading, form fields for entering details, and updated content specific to scheduling a demo, replacing the previous product information.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.metalware.com/book-a-demo

https://www.metalware.com/book-a-demo

**Content (before/after):** 

```
RootWebArea Book a Demo, focused, url='https://www.metalware.com/book-a-demo'
	banner
		banner
			[22] link home, center=(472,40), url='https://www.metalware.com/'
				image
```
<details><summary>Show more</summary>

```
			navigation
				[28] link Product, center=(660,40), url='https://www.metalware.com/product'
				[30] button Industries, center=(768,40), expanded=False, hasPopup='menu'
					image
				[40] link Company, center=(882,40), url='https://www.metalware.com/company'
			[43] link Log In, center=(1384,40), url='https://www.metalware.com/book-a-demo#'
			[44] link Book a demo, center=(1504,40), url='https://www.metalware.com/book-a-demo'
	main
		heading BOOK A DEMO
		paragraph
			StaticText See how Metalware can help you detect firmware bugs so you can develop more secure, reliable applications.
		heading What you can expect:
		image
		paragraph
			StaticText See firsthand how Metalware finds vulnerabilities in your firmware
		image
		paragraph
			StaticText Discuss your use case and hardware requirements in detail
		image
		paragraph
			StaticText Explore Metalware's full development platform, including crash replays and full trace
		heading READY TO SPEAK WITH AN EXPERT?
		form Book a demo
			LabelText
				StaticText Company email*
			[92] textbox Company email*, center=(1280,347), contenteditable=True, required, type=email
			LabelText
				StaticText Describe your use case*
			[95] textbox Describe your use case*, center=(1280,529), contenteditable=True, required
			[96] button Submit, center=(1046,673), contenteditable=True, type=submit
	contentinfo
		[107] link, center=(460,987), url='https://www.metalware.com/'
			image
		StaticText Company
		[113] link About, center=(342,1079), url='https://www.metalware.com/company'
		link Careers, url='https://www.ycombinator.com/companies/metalware/jobs'
		link Terms, url='https://www.metalware.com/terms'
		link Privacy, url='https://www.metalware.com/privacy-policy'
		StaticText Industries
		[119] link Aerospace & Defense, center=(727,1079), url='https://www.metalware.com/aerospace'
		link Automotive, url='https://www.metalware.com/automotive'
		link Healthcare, url='https://www.metalware.com/healthcare'
		link Industrials, url='https://www.metalware.com/industrials'
		link Consumer Electronics, url='https://www.metalware.com/consumer'
		StaticText Resources
		[126] link Book a demo, center=(1026,1079), url='https://www.metalware.com/book-a-demo'
		link HDL Plugin for VS Code, url='https://hdlcopilot.com/'
		link PDF Reader for Datasheets, url='https://datasheetreader.com/'
		StaticText Contact
		[131] link sales@metalware.com, center=(1390,1079), url='mailto:sales@metalware.io'
		link support@metalware.com, url='mailto:support@metalware.io'
		link careers@metalware.com, url='mailto:careers@metalware.io'
		link press@metalware.com, url='mailto:press@metalware.io'
		link go to twitter, url='https://twitter.com/getmetalware'
			image
		link go to linkedin, url='https://linkedin.com/company/metalwareinc/'
			image
		link go to ycombinator, url='https://www.ycombinator.com/companies/metalware'
			image
		link go to github, url='https://github.com/metalware-inc'
			image
		StaticText © 2024 Metalware. All rights reserved.
```
</details>



```
RootWebArea Book a Demo, focused, url='https://www.metalware.com/book-a-demo'
	banner
		banner
			[22] link home, center=(472,40), url='https://www.metalware.com/'
				image
```
<details><summary>Show more</summary>

```
			navigation
				[28] link Product, center=(660,40), url='https://www.metalware.com/product'
				[30] button Industries, center=(768,40), expanded=False, hasPopup='menu'
					image
				[40] link Company, center=(882,40), url='https://www.metalware.com/company'
			[43] link Log In, center=(1384,40), url='https://www.metalware.com/book-a-demo#'
			[44] link Book a demo, center=(1504,40), url='https://www.metalware.com/book-a-demo'
	main
		heading BOOK A DEMO
		paragraph
			StaticText See how Metalware can help you detect firmware bugs so you can develop more secure, reliable applications.
		heading What you can expect:
		image
		paragraph
			StaticText See firsthand how Metalware finds vulnerabilities in your firmware
		image
		paragraph
			StaticText Discuss your use case and hardware requirements in detail
		image
		paragraph
			StaticText Explore Metalware's full development platform, including crash replays and full trace
		heading READY TO SPEAK WITH AN EXPERT?
		region Book a demo success, focused
			StaticText Thank you! Your submission has been received!
	contentinfo
		[107] link, center=(460,960), url='https://www.metalware.com/'
			image
		StaticText Company
		[113] link About, center=(342,1052), url='https://www.metalware.com/company'
		link Careers, url='https://www.ycombinator.com/companies/metalware/jobs'
		link Terms, url='https://www.metalware.com/terms'
		link Privacy, url='https://www.metalware.com/privacy-policy'
		StaticText Industries
		[119] link Aerospace & Defense, center=(727,1052), url='https://www.metalware.com/aerospace'
		link Automotive, url='https://www.metalware.com/automotive'
		link Healthcare, url='https://www.metalware.com/healthcare'
		link Industrials, url='https://www.metalware.com/industrials'
		link Consumer Electronics, url='https://www.metalware.com/consumer'
		StaticText Resources
		[126] link Book a demo, center=(1026,1052), url='https://www.metalware.com/book-a-demo'
		link HDL Plugin for VS Code, url='https://hdlcopilot.com/'
		link PDF Reader for Datasheets, url='https://datasheetreader.com/'
		StaticText Contact
		[131] link sales@metalware.com, center=(1390,1052), url='mailto:sales@metalware.io'
		link support@metalware.com, url='mailto:support@metalware.io'
		link careers@metalware.com, url='mailto:careers@metalware.io'
		link press@metalware.com, url='mailto:press@metalware.io'
		link go to twitter, url='https://twitter.com/getmetalware'
			image
		link go to linkedin, url='https://linkedin.com/company/metalwareinc/'
			image
		link go to ycombinator, url='https://www.ycombinator.com/companies/metalware'
			image
		link go to github, url='https://github.com/metalware-inc'
			image
		StaticText © 2024 Metalware. All rights reserved.
```
</details>

**Reasoning for action:** Filling in '92' with 'example@company.com' and '95' with 'I would like to discuss firmware security solutions.' directly addresses the required fields in the demo request form. Completing these fields makes the form ready for submission, which is essential for moving forward with scheduling the demo. Finally, clicking '96' submits the form, fulfilling the task of requesting a demo and progressing towards the confirmation message that indicates the successful submission of the request.

**Action:** fill('92', 'example@company.com') # Fill in the Company email field with a placeholder email
fill('95', 'I would like to discuss firmware security solutions.') # Fill in the Describe your use case field with a placeholder message
click(96) # Click on the Submit button to submit the demo request form.

**Change Description:** The Company email and Describe your use case fields were filled with placeholder information, and upon clicking the Submit button, a success message was displayed indicating that the demo request submission was received.

**Screenshot before:****Screenshot after:**---


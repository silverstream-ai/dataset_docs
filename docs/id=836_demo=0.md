# Task

**User Engagement on Sizeless Website**

As a potential customer interested in machine learning solutions,,
I explore contact options and learn about Sizeless services through a demonstration video,
so that I can determine if their offerings align with my needs for reproducible and safe AI implementations.

**Success definition:** Given I am on the Sizeless homepage
When I click on the 'Get in Touch' button and then click on the 'Watch the full video 3 min' button
Then I should be directed to the contact options section and a modal should open displaying the Sizeless demo video.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://sizeless.co/

https://sizeless.co/

**Content (before/after):** 

```
RootWebArea sizeless: Reproducible and Safe AI, focused, url='https://sizeless.co/'
	banner
		heading sizeless
			[29] link sizeless, center=(471,38), url='https://sizeless.co/'
		navigation
```
<details><summary>Show more</summary>

```
			list
				listitem
					[33] button Get in Touch, center=(1448,40)
		paragraph
			StaticText This website uses cookies We use cookies to personalise content and ads, to provide social media features and to analyse our traffic. We also share information about your use of our site with our social media, advertising and analytics partners who may combine it with other information that you’ve provided to them or that they’ve collected from your use of their services. See our
			[36] link cookie policy, center=(767,1044), url='https://sizeless.co/terms'
			StaticText .
		[38] button Accept all, center=(1757,1020), type=button
		[39] button Reject all, center=(1856,1020), type=button
	main
		heading We make Machine Learning Reproducible and Safe
		paragraph
			StaticText You choose a model and we take care of the rest:
			StaticText running at scale and benchmarking ML models.
		image Modal video thumbnail, url='https://sizeless.co/_next/static/media/thumbnail.be78c250.png'
		[56] button Watch the full video (3 min), center=(960,821)
			image
		LabelText
			StaticText Email address
		[69] textbox Email address, center=(881,881), autocomplete=email, contenteditable=True, required, type=email
		[70] button Join the waitlist!, center=(1113,881), type=submit
		paragraph
			StaticText Built for and trusted by ML engineers, researchers and academics.
		link Transistor, url='https://asl.ethz.ch/'
			image Transistor, url='https://sizeless.co/images/ETH_Zurich.png'
		link Reform, url='https://www.lbl.gov/'
			image Reform, url='https://sizeless.co/images/Lawrence_Berkeley_National_Laboratory_logo.svg.png'
		link Tuple, url='https://www.cam.ac.uk/'
			image Tuple, url='https://sizeless.co/images/cambridge.png'
		link SavvyCal, url='https://www.berkeley.edu/'
			image SavvyCal, url='https://sizeless.co/images/berkeley.png'
		paragraph
			StaticText Backed By
		link SavvyCal, url='https://www.ycombinator.com/'
			image SavvyCal, url='https://sizeless.co/images/YC_logo_orange.png'
		heading We accelerate your AI journey
		paragraph
			StaticText We are making a shortcut for ML teams everywhere.
			StaticText Speed up your development cycle: Run, test and improve your ML models with just a few clicks.
		heading Speed-up your development cycle
		link Run We automatically deploy your ML model efficiently to CPUs & GPUs., url='https://sizeless.co/#0'
			image
		link Test We train, test and validate your model and compare it to other codes., url='https://sizeless.co/#0'
			image
		link Improve We generate insights on how you can improve your models to reach your KPIs and metrics., url='https://sizeless.co/#0'
			image
		image Features bg, url='https://sizeless.co/_next/static/media/features-new.c91c3127.png'
		heading Focus on building ML models
		paragraph
			StaticText We accelerate the development cycle from prototyping to deployment by dealing with the hassle of running your models at scale and benchmarking them against other models and data sets.
		image
		heading AI safety
		paragraph
			StaticText Significantly improve model performance by uncovering and fixing model failures.
		image
		heading Transparency
		paragraph
			StaticText Know how well your models perform compared to other models & data sets.
		image
		heading Optimize Cloud Spend
		paragraph
			StaticText We efficiently deploy your models - only pay what you use.
		heading Evaluate across many fields
		paragraph
			StaticText Benchmarking is available for a selected group of categories for now.
		tablist, orientation='horizontal'
			tab Object Detection, selected=True
			tab Anomaly Detection, selected=False
			tab VIO - Visual Inertial Odometry, selected=False
			tab Submit your own, selected=False
		tabpanel Object Detection
			heading Object Detection
			table
				rowgroup
					row
						columnheader
						columnheader PASCAL VOC 2007 - [LINK]
							link LINK, url='http://host.robots.ox.ac.uk/pascal/VOC/voc2007/'
						columnheader COCO - [LINK]
							link LINK, url='https://cocodataset.org/#home'
						columnheader CROWDHUMAN - [LINK]
							link LINK, url='https://arxiv.org/abs/1805.00123'
				rowgroup
					row
						rowheader Cascade - [link]
							link link, url='https://arxiv.org/pdf/2012.07177v2.pdf'
						cell MAP: 89.3%
						cell MAP: 57.3%
						cell
							status, atomic
								StaticText Loading...
					row
						rowheader Yolo v2 - [link]
							link link, url='https://arxiv.org/pdf/1612.08242v1.pdf'
						cell MAP: 78.6%
						cell
						cell Close
							button Close
					row
						rowheader Faster RCNN - [link]
							link link, url='https://arxiv.org/pdf/1506.01497v3.pdf'
						cell MAP: 73.2%
						cell MAP 43.9%
						cell MAP 84.95%
		blockquote
			StaticText “ sizeless is a game changer for transparent and reproducible research. I can now easily run, test and compare my computer vision models to other models and data sets in a few clicks.“
		StaticText Cornelius
		StaticText PhD student
		link ETH Zurich, url='https://sizeless.co/#0'
	contentinfo
		list
			listitem
				link Github, url='https://github.com/sizeless-tech'
					image
		StaticText Copyright © 2023 sizeless Corporation. All rights reserved.
		link Terms and Conditions, url='https://sizeless.co/terms'
	alert, atomic
```
</details>



```
RootWebArea sizeless: Reproducible and Safe AI, focused, url='https://sizeless.co/'
	banner
		heading sizeless
			[29] link sizeless, center=(471,38), url='https://sizeless.co/'
		navigation
```
<details><summary>Show more</summary>

```
			list
				listitem
					[33] button Get in Touch, center=(1448,40), focused
		paragraph
			StaticText This website uses cookies We use cookies to personalise content and ads, to provide social media features and to analyse our traffic. We also share information about your use of our site with our social media, advertising and analytics partners who may combine it with other information that you’ve provided to them or that they’ve collected from your use of their services. See our
			[36] link cookie policy, center=(767,1044), url='https://sizeless.co/terms'
			StaticText .
		[38] button Accept all, center=(1757,1020), type=button
		[39] button Reject all, center=(1856,1020), type=button
	main
		heading We make Machine Learning Reproducible and Safe
		paragraph
			StaticText You choose a model and we take care of the rest:
			StaticText running at scale and benchmarking ML models.
		image Modal video thumbnail, url='https://sizeless.co/_next/static/media/thumbnail.be78c250.png'
		[56] button Watch the full video (3 min), center=(960,821)
			image
		LabelText
			StaticText Email address
		[69] textbox Email address, center=(881,881), autocomplete=email, contenteditable=True, required, type=email
		[70] button Join the waitlist!, center=(1113,881), type=submit
		paragraph
			StaticText Built for and trusted by ML engineers, researchers and academics.
		link Transistor, url='https://asl.ethz.ch/'
			image Transistor, url='https://sizeless.co/images/ETH_Zurich.png'
		link Reform, url='https://www.lbl.gov/'
			image Reform, url='https://sizeless.co/images/Lawrence_Berkeley_National_Laboratory_logo.svg.png'
		link Tuple, url='https://www.cam.ac.uk/'
			image Tuple, url='https://sizeless.co/images/cambridge.png'
		link SavvyCal, url='https://www.berkeley.edu/'
			image SavvyCal, url='https://sizeless.co/images/berkeley.png'
		paragraph
			StaticText Backed By
		link SavvyCal, url='https://www.ycombinator.com/'
			image SavvyCal, url='https://sizeless.co/images/YC_logo_orange.png'
		heading We accelerate your AI journey
		paragraph
			StaticText We are making a shortcut for ML teams everywhere.
			StaticText Speed up your development cycle: Run, test and improve your ML models with just a few clicks.
		heading Speed-up your development cycle
		link Run We automatically deploy your ML model efficiently to CPUs & GPUs., url='https://sizeless.co/#0'
			image
		link Test We train, test and validate your model and compare it to other codes., url='https://sizeless.co/#0'
			image
		link Improve We generate insights on how you can improve your models to reach your KPIs and metrics., url='https://sizeless.co/#0'
			image
		image Features bg, url='https://sizeless.co/_next/static/media/features-new.c91c3127.png'
		heading Focus on building ML models
		paragraph
			StaticText We accelerate the development cycle from prototyping to deployment by dealing with the hassle of running your models at scale and benchmarking them against other models and data sets.
		image
		heading AI safety
		paragraph
			StaticText Significantly improve model performance by uncovering and fixing model failures.
		image
		heading Transparency
		paragraph
			StaticText Know how well your models perform compared to other models & data sets.
		image
		heading Optimize Cloud Spend
		paragraph
			StaticText We efficiently deploy your models - only pay what you use.
		heading Evaluate across many fields
		paragraph
			StaticText Benchmarking is available for a selected group of categories for now.
		tablist, orientation='horizontal'
			tab Object Detection, selected=True
			tab Anomaly Detection, selected=False
			tab VIO - Visual Inertial Odometry, selected=False
			tab Submit your own, selected=False
		tabpanel Object Detection
			heading Object Detection
			table
				rowgroup
					row
						columnheader
						columnheader PASCAL VOC 2007 - [LINK]
							link LINK, url='http://host.robots.ox.ac.uk/pascal/VOC/voc2007/'
						columnheader COCO - [LINK]
							link LINK, url='https://cocodataset.org/#home'
						columnheader CROWDHUMAN - [LINK]
							link LINK, url='https://arxiv.org/abs/1805.00123'
				rowgroup
					row
						rowheader Cascade - [link]
							link link, url='https://arxiv.org/pdf/2012.07177v2.pdf'
						cell MAP: 89.3%
						cell MAP: 57.3%
						cell
							status, atomic
								StaticText Loading...
					row
						rowheader Yolo v2 - [link]
							link link, url='https://arxiv.org/pdf/1612.08242v1.pdf'
						cell MAP: 78.6%
						cell
						cell Close
							button Close
					row
						rowheader Faster RCNN - [link]
							link link, url='https://arxiv.org/pdf/1506.01497v3.pdf'
						cell MAP: 73.2%
						cell MAP 43.9%
						cell MAP 84.95%
		blockquote
			StaticText “ sizeless is a game changer for transparent and reproducible research. I can now easily run, test and compare my computer vision models to other models and data sets in a few clicks.“
		StaticText Cornelius
		StaticText PhD student
		link ETH Zurich, url='https://sizeless.co/#0'
	contentinfo
		list
			listitem
				link Github, url='https://github.com/sizeless-tech'
					image
		StaticText Copyright © 2023 sizeless Corporation. All rights reserved.
		link Terms and Conditions, url='https://sizeless.co/terms'
	alert, atomic
```
</details>

**Reasoning for action:** I clicked the 'Get in Touch' button (identified by index 33) to move towards the contact options as the user story mentions that I need to explore contact options. This action navigates me away from the homepage content towards the section where I am likely to find further engagement details or forms to connect with Sizeless, which aligns with the user's goal of learning about their services.

**Action:** click(33) # Click on the 'Get in Touch' button to explore contact options.

**Change Description:** After clicking the 'Get in Touch' button, the state of the navigation bar in the browser has changed to indicate that the button is now focused. This likely suggests that the user is being directed towards contact options, although no new content has been rendered in the accessibility tree.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://sizeless.co/

https://sizeless.co/

**Content (before/after):** 

```
RootWebArea sizeless: Reproducible and Safe AI, focused, url='https://sizeless.co/'
	banner
		heading sizeless
			[29] link sizeless, center=(471,38), url='https://sizeless.co/'
		navigation
```
<details><summary>Show more</summary>

```
			list
				listitem
					[33] button Get in Touch, center=(1448,40), focused
		paragraph
			StaticText This website uses cookies We use cookies to personalise content and ads, to provide social media features and to analyse our traffic. We also share information about your use of our site with our social media, advertising and analytics partners who may combine it with other information that you’ve provided to them or that they’ve collected from your use of their services. See our
			[36] link cookie policy, center=(767,1044), url='https://sizeless.co/terms'
			StaticText .
		[38] button Accept all, center=(1757,1020), type=button
		[39] button Reject all, center=(1856,1020), type=button
	main
		heading We make Machine Learning Reproducible and Safe
		paragraph
			StaticText You choose a model and we take care of the rest:
			StaticText running at scale and benchmarking ML models.
		image Modal video thumbnail, url='https://sizeless.co/_next/static/media/thumbnail.be78c250.png'
		[56] button Watch the full video (3 min), center=(960,821)
			image
		LabelText
			StaticText Email address
		[69] textbox Email address, center=(881,881), autocomplete=email, contenteditable=True, required, type=email
		[70] button Join the waitlist!, center=(1113,881), type=submit
		paragraph
			StaticText Built for and trusted by ML engineers, researchers and academics.
		link Transistor, url='https://asl.ethz.ch/'
			image Transistor, url='https://sizeless.co/images/ETH_Zurich.png'
		link Reform, url='https://www.lbl.gov/'
			image Reform, url='https://sizeless.co/images/Lawrence_Berkeley_National_Laboratory_logo.svg.png'
		link Tuple, url='https://www.cam.ac.uk/'
			image Tuple, url='https://sizeless.co/images/cambridge.png'
		link SavvyCal, url='https://www.berkeley.edu/'
			image SavvyCal, url='https://sizeless.co/images/berkeley.png'
		paragraph
			StaticText Backed By
		link SavvyCal, url='https://www.ycombinator.com/'
			image SavvyCal, url='https://sizeless.co/images/YC_logo_orange.png'
		heading We accelerate your AI journey
		paragraph
			StaticText We are making a shortcut for ML teams everywhere.
			StaticText Speed up your development cycle: Run, test and improve your ML models with just a few clicks.
		heading Speed-up your development cycle
		link Run We automatically deploy your ML model efficiently to CPUs & GPUs., url='https://sizeless.co/#0'
			image
		link Test We train, test and validate your model and compare it to other codes., url='https://sizeless.co/#0'
			image
		link Improve We generate insights on how you can improve your models to reach your KPIs and metrics., url='https://sizeless.co/#0'
			image
		image Features bg, url='https://sizeless.co/_next/static/media/features-new.c91c3127.png'
		heading Focus on building ML models
		paragraph
			StaticText We accelerate the development cycle from prototyping to deployment by dealing with the hassle of running your models at scale and benchmarking them against other models and data sets.
		image
		heading AI safety
		paragraph
			StaticText Significantly improve model performance by uncovering and fixing model failures.
		image
		heading Transparency
		paragraph
			StaticText Know how well your models perform compared to other models & data sets.
		image
		heading Optimize Cloud Spend
		paragraph
			StaticText We efficiently deploy your models - only pay what you use.
		heading Evaluate across many fields
		paragraph
			StaticText Benchmarking is available for a selected group of categories for now.
		tablist, orientation='horizontal'
			tab Object Detection, selected=True
			tab Anomaly Detection, selected=False
			tab VIO - Visual Inertial Odometry, selected=False
			tab Submit your own, selected=False
		tabpanel Object Detection
			heading Object Detection
			table
				rowgroup
					row
						columnheader
						columnheader PASCAL VOC 2007 - [LINK]
							link LINK, url='http://host.robots.ox.ac.uk/pascal/VOC/voc2007/'
						columnheader COCO - [LINK]
							link LINK, url='https://cocodataset.org/#home'
						columnheader CROWDHUMAN - [LINK]
							link LINK, url='https://arxiv.org/abs/1805.00123'
				rowgroup
					row
						rowheader Cascade - [link]
							link link, url='https://arxiv.org/pdf/2012.07177v2.pdf'
						cell MAP: 89.3%
						cell MAP: 57.3%
						cell
							status, atomic
								StaticText Loading...
					row
						rowheader Yolo v2 - [link]
							link link, url='https://arxiv.org/pdf/1612.08242v1.pdf'
						cell MAP: 78.6%
						cell
						cell Close
							button Close
					row
						rowheader Faster RCNN - [link]
							link link, url='https://arxiv.org/pdf/1506.01497v3.pdf'
						cell MAP: 73.2%
						cell MAP 43.9%
						cell MAP 84.95%
		blockquote
			StaticText “ sizeless is a game changer for transparent and reproducible research. I can now easily run, test and compare my computer vision models to other models and data sets in a few clicks.“
		StaticText Cornelius
		StaticText PhD student
		link ETH Zurich, url='https://sizeless.co/#0'
	contentinfo
		list
			listitem
				link Github, url='https://github.com/sizeless-tech'
					image
		StaticText Copyright © 2023 sizeless Corporation. All rights reserved.
		link Terms and Conditions, url='https://sizeless.co/terms'
	alert, atomic
```
</details>



```
RootWebArea sizeless: Reproducible and Safe AI, focused, url='https://sizeless.co/'
	banner
		heading sizeless
			[29] link sizeless, center=(471,38), url='https://sizeless.co/'
		navigation
```
<details><summary>Show more</summary>

```
			list
				listitem
					[33] button Get in Touch, center=(1448,40), focused
		paragraph
			StaticText This website uses cookies We use cookies to personalise content and ads, to provide social media features and to analyse our traffic. We also share information about your use of our site with our social media, advertising and analytics partners who may combine it with other information that you’ve provided to them or that they’ve collected from your use of their services. See our
			[36] link cookie policy, center=(767,1044), url='https://sizeless.co/terms'
			StaticText .
		[38] button Accept all, center=(1757,1020), type=button
		[39] button Reject all, center=(1856,1020), type=button
	main
		heading We make Machine Learning Reproducible and Safe
		paragraph
			StaticText You choose a model and we take care of the rest:
			StaticText running at scale and benchmarking ML models.
		image Modal video thumbnail, url='https://sizeless.co/_next/static/media/thumbnail.be78c250.png'
		[56] button Watch the full video (3 min), center=(960,821)
			image
		LabelText
			StaticText Email address
		[69] textbox Email address, center=(881,881), autocomplete=email, contenteditable=True, required, type=email
		[70] button Join the waitlist!, center=(1113,881), type=submit
		paragraph
			StaticText Built for and trusted by ML engineers, researchers and academics.
		link Transistor, url='https://asl.ethz.ch/'
			image Transistor, url='https://sizeless.co/images/ETH_Zurich.png'
		link Reform, url='https://www.lbl.gov/'
			image Reform, url='https://sizeless.co/images/Lawrence_Berkeley_National_Laboratory_logo.svg.png'
		link Tuple, url='https://www.cam.ac.uk/'
			image Tuple, url='https://sizeless.co/images/cambridge.png'
		link SavvyCal, url='https://www.berkeley.edu/'
			image SavvyCal, url='https://sizeless.co/images/berkeley.png'
		paragraph
			StaticText Backed By
		link SavvyCal, url='https://www.ycombinator.com/'
			image SavvyCal, url='https://sizeless.co/images/YC_logo_orange.png'
		heading We accelerate your AI journey
		paragraph
			StaticText We are making a shortcut for ML teams everywhere.
			StaticText Speed up your development cycle: Run, test and improve your ML models with just a few clicks.
		heading Speed-up your development cycle
		link Run We automatically deploy your ML model efficiently to CPUs & GPUs., url='https://sizeless.co/#0'
			image
		link Test We train, test and validate your model and compare it to other codes., url='https://sizeless.co/#0'
			image
		link Improve We generate insights on how you can improve your models to reach your KPIs and metrics., url='https://sizeless.co/#0'
			image
		image Features bg, url='https://sizeless.co/_next/static/media/features-new.c91c3127.png'
		heading Focus on building ML models
		paragraph
			StaticText We accelerate the development cycle from prototyping to deployment by dealing with the hassle of running your models at scale and benchmarking them against other models and data sets.
		image
		heading AI safety
		paragraph
			StaticText Significantly improve model performance by uncovering and fixing model failures.
		image
		heading Transparency
		paragraph
			StaticText Know how well your models perform compared to other models & data sets.
		image
		heading Optimize Cloud Spend
		paragraph
			StaticText We efficiently deploy your models - only pay what you use.
		heading Evaluate across many fields
		paragraph
			StaticText Benchmarking is available for a selected group of categories for now.
		tablist, orientation='horizontal'
			tab Object Detection, selected=True
			tab Anomaly Detection, selected=False
			tab VIO - Visual Inertial Odometry, selected=False
			tab Submit your own, selected=False
		tabpanel Object Detection
			heading Object Detection
			table
				rowgroup
					row
						columnheader
						columnheader PASCAL VOC 2007 - [LINK]
							link LINK, url='http://host.robots.ox.ac.uk/pascal/VOC/voc2007/'
						columnheader COCO - [LINK]
							link LINK, url='https://cocodataset.org/#home'
						columnheader CROWDHUMAN - [LINK]
							link LINK, url='https://arxiv.org/abs/1805.00123'
				rowgroup
					row
						rowheader Cascade - [link]
							link link, url='https://arxiv.org/pdf/2012.07177v2.pdf'
						cell MAP: 89.3%
						cell MAP: 57.3%
						cell
							status, atomic
								StaticText Loading...
					row
						rowheader Yolo v2 - [link]
							link link, url='https://arxiv.org/pdf/1612.08242v1.pdf'
						cell MAP: 78.6%
						cell
						cell Close
							button Close
					row
						rowheader Faster RCNN - [link]
							link link, url='https://arxiv.org/pdf/1506.01497v3.pdf'
						cell MAP: 73.2%
						cell MAP 43.9%
						cell MAP 84.95%
		blockquote
			StaticText “ sizeless is a game changer for transparent and reproducible research. I can now easily run, test and compare my computer vision models to other models and data sets in a few clicks.“
		StaticText Cornelius
		StaticText PhD student
		link ETH Zurich, url='https://sizeless.co/#0'
	contentinfo
		list
			listitem
				link Github, url='https://github.com/sizeless-tech'
					image
		StaticText Copyright © 2023 sizeless Corporation. All rights reserved.
		link Terms and Conditions, url='https://sizeless.co/terms'
	alert, atomic
```
</details>

**Reasoning for action:** Clicking on the 'Get in Touch' button is the first step in fulfilling the user story. By doing this, I will be taken to the contact options section, which is necessary for exploring how to inquire further about Sizeless services. This action brings me closer to the goal of understanding their offerings.

**Action:** click(33) # Click on the 'Get in Touch' button to explore contact options.

**Change Description:** After clicking the 'Get in Touch' button, the browser's focus shifted to the contact options or section related to getting in touch, though specific visible changes in the content or state of the page are not detailed in the given accessibility tree representation.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://sizeless.co/

https://sizeless.co/

**Content (before/after):** 

```
RootWebArea sizeless: Reproducible and Safe AI, focused, url='https://sizeless.co/'
	banner
		heading sizeless
			[29] link sizeless, center=(471,38), url='https://sizeless.co/'
		navigation
```
<details><summary>Show more</summary>

```
			list
				listitem
					[33] button Get in Touch, center=(1448,40), focused
		paragraph
			StaticText This website uses cookies We use cookies to personalise content and ads, to provide social media features and to analyse our traffic. We also share information about your use of our site with our social media, advertising and analytics partners who may combine it with other information that you’ve provided to them or that they’ve collected from your use of their services. See our
			[36] link cookie policy, center=(767,1044), url='https://sizeless.co/terms'
			StaticText .
		[38] button Accept all, center=(1757,1020), type=button
		[39] button Reject all, center=(1856,1020), type=button
	main
		heading We make Machine Learning Reproducible and Safe
		paragraph
			StaticText You choose a model and we take care of the rest:
			StaticText running at scale and benchmarking ML models.
		image Modal video thumbnail, url='https://sizeless.co/_next/static/media/thumbnail.be78c250.png'
		[56] button Watch the full video (3 min), center=(960,821)
			image
		LabelText
			StaticText Email address
		[69] textbox Email address, center=(881,881), autocomplete=email, contenteditable=True, required, type=email
		[70] button Join the waitlist!, center=(1113,881), type=submit
		paragraph
			StaticText Built for and trusted by ML engineers, researchers and academics.
		link Transistor, url='https://asl.ethz.ch/'
			image Transistor, url='https://sizeless.co/images/ETH_Zurich.png'
		link Reform, url='https://www.lbl.gov/'
			image Reform, url='https://sizeless.co/images/Lawrence_Berkeley_National_Laboratory_logo.svg.png'
		link Tuple, url='https://www.cam.ac.uk/'
			image Tuple, url='https://sizeless.co/images/cambridge.png'
		link SavvyCal, url='https://www.berkeley.edu/'
			image SavvyCal, url='https://sizeless.co/images/berkeley.png'
		paragraph
			StaticText Backed By
		link SavvyCal, url='https://www.ycombinator.com/'
			image SavvyCal, url='https://sizeless.co/images/YC_logo_orange.png'
		heading We accelerate your AI journey
		paragraph
			StaticText We are making a shortcut for ML teams everywhere.
			StaticText Speed up your development cycle: Run, test and improve your ML models with just a few clicks.
		heading Speed-up your development cycle
		link Run We automatically deploy your ML model efficiently to CPUs & GPUs., url='https://sizeless.co/#0'
			image
		link Test We train, test and validate your model and compare it to other codes., url='https://sizeless.co/#0'
			image
		link Improve We generate insights on how you can improve your models to reach your KPIs and metrics., url='https://sizeless.co/#0'
			image
		image Features bg, url='https://sizeless.co/_next/static/media/features-new.c91c3127.png'
		heading Focus on building ML models
		paragraph
			StaticText We accelerate the development cycle from prototyping to deployment by dealing with the hassle of running your models at scale and benchmarking them against other models and data sets.
		image
		heading AI safety
		paragraph
			StaticText Significantly improve model performance by uncovering and fixing model failures.
		image
		heading Transparency
		paragraph
			StaticText Know how well your models perform compared to other models & data sets.
		image
		heading Optimize Cloud Spend
		paragraph
			StaticText We efficiently deploy your models - only pay what you use.
		heading Evaluate across many fields
		paragraph
			StaticText Benchmarking is available for a selected group of categories for now.
		tablist, orientation='horizontal'
			tab Object Detection, selected=True
			tab Anomaly Detection, selected=False
			tab VIO - Visual Inertial Odometry, selected=False
			tab Submit your own, selected=False
		tabpanel Object Detection
			heading Object Detection
			table
				rowgroup
					row
						columnheader
						columnheader PASCAL VOC 2007 - [LINK]
							link LINK, url='http://host.robots.ox.ac.uk/pascal/VOC/voc2007/'
						columnheader COCO - [LINK]
							link LINK, url='https://cocodataset.org/#home'
						columnheader CROWDHUMAN - [LINK]
							link LINK, url='https://arxiv.org/abs/1805.00123'
				rowgroup
					row
						rowheader Cascade - [link]
							link link, url='https://arxiv.org/pdf/2012.07177v2.pdf'
						cell MAP: 89.3%
						cell MAP: 57.3%
						cell
							status, atomic
								StaticText Loading...
					row
						rowheader Yolo v2 - [link]
							link link, url='https://arxiv.org/pdf/1612.08242v1.pdf'
						cell MAP: 78.6%
						cell
						cell Close
							button Close
					row
						rowheader Faster RCNN - [link]
							link link, url='https://arxiv.org/pdf/1506.01497v3.pdf'
						cell MAP: 73.2%
						cell MAP 43.9%
						cell MAP 84.95%
		blockquote
			StaticText “ sizeless is a game changer for transparent and reproducible research. I can now easily run, test and compare my computer vision models to other models and data sets in a few clicks.“
		StaticText Cornelius
		StaticText PhD student
		link ETH Zurich, url='https://sizeless.co/#0'
	contentinfo
		list
			listitem
				link Github, url='https://github.com/sizeless-tech'
					image
		StaticText Copyright © 2023 sizeless Corporation. All rights reserved.
		link Terms and Conditions, url='https://sizeless.co/terms'
	alert, atomic
```
</details>



```
RootWebArea sizeless: Reproducible and Safe AI, url='https://sizeless.co/'
	alert, atomic
	dialog, modal=True
		[a] Iframe, center=(960,540), focused
			RootWebArea Sizeless Demo - YouTube, focused, url='https://www.youtube-nocookie.com/embed/EPNP8BXZp1Q'
```
<details><summary>Show more</summary>

```
				[a29] link Photo image of sizeless, center=(32,32)
				[a37] link Sizeless Demo, center=(946,33), url='https://www.youtube.com/watch?v=EPNP8BXZp1Q'
				[a58] button Copy link, center=(1869,30)
					image
				[a90] button Play, center=(960,540)
					image
				generic, atomic
				[a316] link Watch on YouTube, center=(86,1052), url='https://www.youtube.com/watch?v=EPNP8BXZp1Q&embeds_referring_euri=https%3A%2F%2Fsizeless.co%2F'
```
</details>

**Reasoning for action:** By clicking on the 'Watch the full video (3 min)' button, I am initiating the process to view a demonstration video that showcases Sizeless services. This is crucial as it allows me to become informed about their offerings and determines their alignment with my needs for reproducible and safe AI implementations. Opening this video modal is a direct step towards achieving the user's goal of exploring contact options and learning about Sizeless services.

**Action:** click(56) # Click on the 'Watch the full video (3 min)' button to explore more about the services offered.

**Change Description:** Upon clicking the 'Watch the full video (3 min)' button, a modal dialog appeared in the browser containing an embedded YouTube video titled 'Sizeless Demo'. The video interface includes options to play the video, copy the link, and watch on YouTube, while temporarily hiding the main webpage content.

**Screenshot before:****Screenshot after:**---


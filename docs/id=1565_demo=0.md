# Task

**Explore and Engage with FlowDeploy Documentation and Tutorials**

As a bioinformatician,
I explore the documentation and tutorials available on FlowDeploy,
so that I can learn how to effectively run and manage bioinformatics pipelines using the platform.

**Success definition:** Given I am on the FlowDeploy documentation website
When I click on the 'Docs' link and then select the 'Tutorials' link to view the available tutorials and click on the 'Run an open-source pipeline' tutorial
Then I should see the tutorial content for running an open-source pipeline displayed and the URL should reflect that I am viewing the 'Run an open-source pipeline' page.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://flowdeploy.com/

https://learn.flowdeploy.com/

**Content (before/after):** 

```
RootWebArea FlowDeploy, focused, url='https://flowdeploy.com/'
	banner
		[31] link Flowdeploy logo, center=(425,44), url='https://flowdeploy.com/#'
			image Flowdeploy logo, url='https://cdn.prod.website-files.com/65f85e244ab18bf8a70eec48/65f85eb69a3636df4d7dac83_Flowdeploy-Wordmark.svg'
		navigation
```
<details><summary>Show more</summary>

```
			list
				listitem
					[36] link Docs, center=(1248,42), url='https://learn.flowdeploy.com/'
				listitem
					[38] link Blog, center=(1310,42), url='https://learn.flowdeploy.com/blog'
				listitem
					[40] link Contact, center=(1381,42), url='mailto:hello@flowdeploy.com?subject=I%27m%20interested%20in%20FlowDeploy!!'
				listitem
					[42] link Get Started, center=(1501,42), url='https://app.flowdeploy.com/'
	StaticText Run bioinformatics pipelines in the cloud using Snakemake or Nextflow.
	StaticText Bioinformaticians use FlowDeploy to try, run and develop pipelines.
	[54] link Try running a pipeline for free, center=(896,534), url='https://app.flowdeploy.com/'
	[57] link Contact us, center=(1092,534), url='mailto:hello@flowdeploy.com?subject=I%27m%20interested%20in%20FlowDeploy!'
	StaticText Getting started
	StaticText Try, run, and develop bioinformatic pipelines with a bit of help from FlowDeploy.
	heading Try pipelines
	paragraph
		StaticText Connect pipelines through GitHub
	paragraph
		StaticText Import custom and public pipelines through GitHub. The git branches and releases are automatically imported and refreshed.
	paragraph
		StaticText Try pipeline templates
	paragraph
		StaticText To help you get started, FlowDeploy has a handful of tested templates to try and use. You can also help others get started by creating your own pipeline templates.
	link Text on image: "Connect through Github", url='https://app.flowdeploy.com/'
		image Text on image: "Connect through Github", url='https://cdn.prod.website-files.com/65f85e244ab18bf8a70eec48/65fa0b4341cdfa1a5834a4b3_Text.png'
	link Text on image: "Pipeline templates", url='https://app.flowdeploy.com/'
		image Text on image: "Pipeline templates", url='https://cdn.prod.website-files.com/65f85e244ab18bf8a70eec48/65fa0b432aac02604b84a729_Text-1.png'
	StaticText Shell
	StaticText flowdeploy run acme/rnaseq -v
	StaticText "1.1.0"
	StaticText Python
	StaticText flowdeploy
	StaticText .snakemake(
	StaticText pipeline=
	StaticText "acme/rnaseq"
	StaticText ,
	StaticText pipeline_version=
	StaticText "1.1.0"
	StaticText ,
	StaticText profiles=
	StaticText [
	StaticText "docker"
	StaticText ],
	StaticText use_git_release=
	StaticText True
	StaticText )
	heading Choose how you run pipelines
	paragraph
		StaticText Using our web app
	paragraph
		StaticText Start running custom or public pipelines right away on your browser, with no installation needed.
	paragraph
		StaticText Programmatically with the FlowDeploy API
	paragraph
		StaticText Build your own framework around FlowDeploy to run and manage your pipelines. After launch, monitor pipelines through the web app.
	heading Flexibly develop your pipelines
	paragraph
		StaticText On your own infrastructure
	paragraph
		StaticText Continue to develop pipelines on your laptop, server, or a cloud.
	paragraph
		StaticText With the help of FlowDeploy for more intensive steps
	paragraph
		StaticText Run individual steps with FlowDeploy while running the pipeline on your own infrastructure.
	StaticText Nextflow
	StaticText nextflow run hello.nf --profile flowdeploy
	StaticText Snakemake
	StaticText snakemake --rerun-incomplete --profile flowdeploy
	StaticText Reach milestones faster
	StaticText FlowDeploy works with you, so you can get your results quickly.
	link See what we're talking about, url='https://app.flowdeploy.com/'
	image Magnifying glass icon, url='https://cdn.prod.website-files.com/65f85e244ab18bf8a70eec48/65f9b6144a7f117a3445d369_BsSearch.svg'
	StaticText Monitor pipelines
	StaticText The web app has a live stream of the run logs, pipeline steps, and resource usage. You can also browse through files as they are created by the run.
	image Reload icon, url='https://cdn.prod.website-files.com/65f85e244ab18bf8a70eec48/65f9b614a837ed7e6e5b1a4b_BsArrowRepeat.svg'
	StaticText Avoid lengthy restarts
	StaticText Like a “checkpoint” in a video game, your run is cached intermittently so you don’t have to start the whole run over again.
	image Unlocked lock icon, url='https://cdn.prod.website-files.com/65f85e244ab18bf8a70eec48/65f9b614ad3a659115fc27d4_BsUnlock.svg'
	StaticText No vendor lock-in
	StaticText FlowDeploy uses an open source bioinformatics task execution protocol, managed by an independent non-profit.
	image Slack logo icon, url='https://cdn.prod.website-files.com/65f85e244ab18bf8a70eec48/65f9b855e9a86bb06d5f499d_FiSlack.svg'
	StaticText Live updates with Slack webhook
	StaticText Receive push notifications from Slack to track pipeline progress.
	image Verified check icon, url='https://cdn.prod.website-files.com/65f85e244ab18bf8a70eec48/65f9b61785a0e48ba8ffd767_MdOutlineVerified.svg'
	StaticText Reduce errors
	StaticText Stable infrastructure and tested pipelines reduce pipeline and operational errors.
	image Icon of a key, url='https://cdn.prod.website-files.com/65f85e244ab18bf8a70eec48/65f9b86892f93af34bda0709_BsKey.svg'
	StaticText Team based auth
	StaticText Securely manage your team through FlowDeploy, or integrate your existing user permissions with SSO.
	heading Resources
	region carousel
		group 1 of 4
			image Nextflow vs snakemake, url='https://cdn.prod.website-files.com/65f85e244ab18bf8a70eec48/65f9e6af125f44e919c0b083_120623_Airflow%20vs.%20Snakemake_BlogIcon-svgs-2.svg'
			heading Nextflow vs. Snakemake
			paragraph
				StaticText How do you choose between Nextflow and Snakemake when writing a bioinformatics pipeline?
			link Learn more, url='https://learn.flowdeploy.com/blog/nextflow-vs-snakemake'
				image
		group 2 of 4
			image Airflow vs Snakemake, url='https://cdn.prod.website-files.com/65f85e244ab18bf8a70eec48/65f9e6af550b4caefa0a4e6f_120623_Airflow%20vs.%20Snakemake_BlogIcon-svgs-3.svg'
			heading Airflow vs. Snakemake
			paragraph
				StaticText What are the pros and cons of these two python based workflow managers for bioinformatics?
			link Learn more, url='https://learn.flowdeploy.com/blog/airflow-vs-snakemake'
				image
		group 3 of 4
			image A purple rocketship, url='https://cdn.prod.website-files.com/65f85e244ab18bf8a70eec48/65fb2406bd2c0ee81cd2efb9_Start%20a%20Bioinformatics%20team.svg'
			heading Starting a bioinformatics team
			paragraph
				StaticText A guide for people with technical experience in bioinformatics, who have never built their own team.
			link Show me the guide, url='https://learn.flowdeploy.com/starting-a-bioinformatics-team'
				image
		button Show slide 1 of 2
		button Show slide 2 of 2
	StaticText Run a pipeline
	link Try Now, url='https://app.flowdeploy.com/'
	link Flowdeploy logo, url='https://flowdeploy.com/'
		image Flowdeploy logo, url='https://cdn.prod.website-files.com/65f85e244ab18bf8a70eec48/65f85eb69a3636df4d7dac83_Flowdeploy-Wordmark.svg'
	link, url='https://www.linkedin.com/company/flowdeploy-bio/'
		image, url='https://cdn.prod.website-files.com/65f85e244ab18bf8a70eec48/65f9ba98ad3a6591150071fa_BsLinkedin.svg'
	link, url='mailto:hello@flowdeploy.com?subject=I%27m%20interested%20in%20FlowDeploy!'
		image, url='https://cdn.prod.website-files.com/65f85e244ab18bf8a70eec48/65f9ba9897f3f58bff617979_mail.svg'
	link, url='https://github.com/trytoolchest'
		image, url='https://cdn.prod.website-files.com/65f85e244ab18bf8a70eec48/65f9ba98cfa206f4ca9d5761_Github.svg'
	link Docs, url='https://learn.flowdeploy.com/'
	link Blog, url='https://learn.flowdeploy.com/blog'
	link Contact us, url='mailto:hello@flowdeploy.com?subject=I%27m%20interested%20in%20FlowDeploy!'
	link Get started, url='https://app.flowdeploy.com/'
	StaticText © 2024 Toolchest, Inc.
	link Terms Of Use, url='https://www.trytoolchest.com/terms'
	link Privacy Policy, url='https://www.trytoolchest.com/privacy'
```
</details>



```
RootWebArea Introduction | FlowDeploy, focused, url='https://learn.flowdeploy.com/'
	region Skip to main content
		link Skip to main content, url='https://learn.flowdeploy.com/#__docusaurus_skipToContent_fallback'
	navigation Main
		[169] link FlowDeploy logo, center=(95,30), url='https://learn.flowdeploy.com/'
```
<details><summary>Show more</summary>

```
			image FlowDeploy logo, url='https://learn.flowdeploy.com/img/flowdeploy_logo.svg'
		[173] link Docs, center=(1627,30), url='https://learn.flowdeploy.com/'
		[174] link Blog, center=(1685,30), url='https://learn.flowdeploy.com/blog'
		[175] link Get started, center=(1766,30), url='https://app.flowdeploy.com/'
		[176] link Sign in, center=(1856,30), url='https://app.flowdeploy.com/'
	complementary
		link FlowDeploy logo, url='https://learn.flowdeploy.com/'
			image FlowDeploy logo, url='https://learn.flowdeploy.com/img/flowdeploy_logo.svg'
		navigation Docs sidebar
			list
				listitem
					[191] link Introduction, center=(149,84), url='https://learn.flowdeploy.com/'
				listitem
					[194] link Tutorials, center=(127,120), expanded=False, url='https://learn.flowdeploy.com/category/tutorials'
					[195] button Toggle the collapsible sidebar category 'Tutorials', center=(268,120), type=button
				listitem
					[198] link How-to Guides, center=(127,156), expanded=False, url='https://learn.flowdeploy.com/category/how-to-guides'
					[199] button Toggle the collapsible sidebar category 'How-to Guides', center=(268,156), type=button
				listitem
					[202] link Reference, center=(127,192), expanded=False, url='https://learn.flowdeploy.com/category/reference'
					[203] button Toggle the collapsible sidebar category 'Reference', center=(268,192), type=button
				listitem
					[206] link Knowledge base, center=(127,228), expanded=False, url='https://learn.flowdeploy.com/category/knowledge-base'
					[207] button Toggle the collapsible sidebar category 'Knowledge base', center=(268,228), type=button
		[208] button Collapse sidebar, center=(150,972), title=Collapse sidebar, type=button
	main
		article
			navigation Breadcrumbs
				list
					listitem
						[219] link Home page, center=(485,90), url='https://learn.flowdeploy.com/'
							image
					[221] listitem, center=(573,99), inner_text=Introduction
						StaticText Introduction
			heading Introduction
			heading Ready to get started? Direct link to Ready to get started?
				[229] link Direct link to Ready to get started?, center=(880,252), inner_text=​, title=Direct link to Ready to get started?, url='https://learn.flowdeploy.com/#ready-to-get-started'
					StaticText ​
			paragraph
				[232] link Get started with a "Hello world!" project!, center=(611,308), url='https://learn.flowdeploy.com/category/tutorials'
			heading Looking for something specific? Direct link to Looking for something specific?
				[234] link Direct link to Looking for something specific?, center=(1070,386), inner_text=​, title=Direct link to Looking for something specific?, url='https://learn.flowdeploy.com/#looking-for-something-specific'
					StaticText ​
			paragraph
				[237] link Go to the FlowDeploy reference, center=(582,442), url='https://learn.flowdeploy.com/category/reference'
		navigation Docs pages
			[239] link Next Tutorials », center=(1188,541), inner_text=Next
Tutorials, url='https://learn.flowdeploy.com/category/tutorials'
		list
			listitem
				[246] link Ready to get started?, center=(1610,102), url='https://learn.flowdeploy.com/#ready-to-get-started'
			listitem
				[248] link Looking for something specific?, center=(1610,129), url='https://learn.flowdeploy.com/#looking-for-something-specific'
	contentinfo
		StaticText Copyright © 2024 Toolchest, Inc.
	region
	region
	region
	region
	region
	region
```
</details>

**Reasoning for action:** By clicking on the 'Docs' link, I move to the section that contains all the documentation resources available on FlowDeploy. This is essential for the user story as it allows me to access the tutorials and further information needed to effectively utilize the platform for bioinformatics pipelines.

**Action:** click(36) # Click on the 'Docs' link to explore the documentation.

**Change Description:** After clicking the 'Docs' link, the browser navigated to the documentation page for FlowDeploy, indicated by a change in the URL to 'https://learn.flowdeploy.com/', and the main content now displays an introduction with various links to tutorials and guides, replacing the previous homepage content.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://learn.flowdeploy.com/

https://learn.flowdeploy.com/category/tutorials

**Content (before/after):** 

```
RootWebArea Introduction | FlowDeploy, focused, url='https://learn.flowdeploy.com/'
	region Skip to main content
		link Skip to main content, url='https://learn.flowdeploy.com/#__docusaurus_skipToContent_fallback'
	navigation Main
		[169] link FlowDeploy logo, center=(95,30), url='https://learn.flowdeploy.com/'
```
<details><summary>Show more</summary>

```
			image FlowDeploy logo, url='https://learn.flowdeploy.com/img/flowdeploy_logo.svg'
		[173] link Docs, center=(1627,30), url='https://learn.flowdeploy.com/'
		[174] link Blog, center=(1685,30), url='https://learn.flowdeploy.com/blog'
		[175] link Get started, center=(1766,30), url='https://app.flowdeploy.com/'
		[176] link Sign in, center=(1856,30), url='https://app.flowdeploy.com/'
	complementary
		link FlowDeploy logo, url='https://learn.flowdeploy.com/'
			image FlowDeploy logo, url='https://learn.flowdeploy.com/img/flowdeploy_logo.svg'
		navigation Docs sidebar
			list
				listitem
					[191] link Introduction, center=(149,84), url='https://learn.flowdeploy.com/'
				listitem
					[194] link Tutorials, center=(127,120), expanded=False, url='https://learn.flowdeploy.com/category/tutorials'
					[195] button Toggle the collapsible sidebar category 'Tutorials', center=(268,120), type=button
				listitem
					[198] link How-to Guides, center=(127,156), expanded=False, url='https://learn.flowdeploy.com/category/how-to-guides'
					[199] button Toggle the collapsible sidebar category 'How-to Guides', center=(268,156), type=button
				listitem
					[202] link Reference, center=(127,192), expanded=False, url='https://learn.flowdeploy.com/category/reference'
					[203] button Toggle the collapsible sidebar category 'Reference', center=(268,192), type=button
				listitem
					[206] link Knowledge base, center=(127,228), expanded=False, url='https://learn.flowdeploy.com/category/knowledge-base'
					[207] button Toggle the collapsible sidebar category 'Knowledge base', center=(268,228), type=button
		[208] button Collapse sidebar, center=(150,972), title=Collapse sidebar, type=button
	main
		article
			navigation Breadcrumbs
				list
					listitem
						[219] link Home page, center=(485,90), url='https://learn.flowdeploy.com/'
							image
					[221] listitem, center=(573,99), inner_text=Introduction
						StaticText Introduction
			heading Introduction
			heading Ready to get started? Direct link to Ready to get started?
				[229] link Direct link to Ready to get started?, center=(880,252), inner_text=​, title=Direct link to Ready to get started?, url='https://learn.flowdeploy.com/#ready-to-get-started'
					StaticText ​
			paragraph
				[232] link Get started with a "Hello world!" project!, center=(611,308), url='https://learn.flowdeploy.com/category/tutorials'
			heading Looking for something specific? Direct link to Looking for something specific?
				[234] link Direct link to Looking for something specific?, center=(1070,386), inner_text=​, title=Direct link to Looking for something specific?, url='https://learn.flowdeploy.com/#looking-for-something-specific'
					StaticText ​
			paragraph
				[237] link Go to the FlowDeploy reference, center=(582,442), url='https://learn.flowdeploy.com/category/reference'
		navigation Docs pages
			[239] link Next Tutorials », center=(1188,541), inner_text=Next
Tutorials, url='https://learn.flowdeploy.com/category/tutorials'
		list
			listitem
				[246] link Ready to get started?, center=(1610,102), url='https://learn.flowdeploy.com/#ready-to-get-started'
			listitem
				[248] link Looking for something specific?, center=(1610,129), url='https://learn.flowdeploy.com/#looking-for-something-specific'
	contentinfo
		StaticText Copyright © 2024 Toolchest, Inc.
	region
	region
	region
	region
	region
	region
```
</details>



```
RootWebArea Tutorials | FlowDeploy, focused, url='https://learn.flowdeploy.com/category/tutorials'
	region Skip to main content
		link Skip to main content, url='https://learn.flowdeploy.com/category/tutorials#__docusaurus_skipToContent_fallback'
	navigation Main
		[169] link FlowDeploy logo, center=(95,30), url='https://learn.flowdeploy.com/'
```
<details><summary>Show more</summary>

```
			image FlowDeploy logo, url='https://learn.flowdeploy.com/img/flowdeploy_logo.svg'
		[173] link Docs, center=(1627,30), url='https://learn.flowdeploy.com/'
		[174] link Blog, center=(1685,30), url='https://learn.flowdeploy.com/blog'
		[175] link Get started, center=(1766,30), url='https://app.flowdeploy.com/'
		[176] link Sign in, center=(1856,30), url='https://app.flowdeploy.com/'
	complementary
		link FlowDeploy logo, url='https://learn.flowdeploy.com/'
			image FlowDeploy logo, url='https://learn.flowdeploy.com/img/flowdeploy_logo.svg'
		navigation Docs sidebar
			list
				listitem
					[191] link Introduction, center=(146,84), url='https://learn.flowdeploy.com/'
				listitem
					[194] link Tutorials, center=(124,120), expanded=True, url='https://learn.flowdeploy.com/category/tutorials'
					[195] button Toggle the collapsible sidebar category 'Tutorials', center=(263,120), type=button
					list
						listitem
							[369] link Run an open-source pipeline, center=(152,156), url='https://learn.flowdeploy.com/tutorial-basics/run'
						listitem
							[371] link Develop a pipeline, center=(152,192), url='https://learn.flowdeploy.com/tutorial-basics/develop'
						listitem
							[373] link Deploy a pipeline, center=(152,228), url='https://learn.flowdeploy.com/tutorial-basics/deploy'
						listitem
							[375] link Congratulations!, center=(152,264), url='https://learn.flowdeploy.com/tutorial-basics/congratulations'
				listitem
					[198] link How-to Guides, center=(124,300), expanded=False, url='https://learn.flowdeploy.com/category/how-to-guides'
					[199] button Toggle the collapsible sidebar category 'How-to Guides', center=(263,300), type=button
				listitem
					[202] link Reference, center=(124,336), expanded=False, url='https://learn.flowdeploy.com/category/reference'
					[203] button Toggle the collapsible sidebar category 'Reference', center=(263,336), type=button
				listitem
					[206] link Knowledge base, center=(124,372), expanded=False, url='https://learn.flowdeploy.com/category/knowledge-base'
					[207] button Toggle the collapsible sidebar category 'Knowledge base', center=(263,372), type=button
		[208] button Collapse sidebar, center=(150,972), title=Collapse sidebar, type=button
	main
		navigation Breadcrumbs
			list
				listitem
					[380] link Home page, center=(485,90), url='https://learn.flowdeploy.com/'
						image
				[382] listitem, center=(562,99), inner_text=Tutorials
					StaticText Tutorials
		heading Tutorials
		article
			article
				[390] link 📄️ Run an open-source pipeline Running an open-source pipeline with FlowDeploy., center=(700,282), inner_text=📄️ Run an open-source pipeline

Running an open-source pipeline with FlowDeploy., url='https://learn.flowdeploy.com/tutorial-basics/run'
					heading 📄️ Run an open-source pipeline
					paragraph
			article
				[394] link 📄️ Develop a pipeline Using FlowDeploy to assist with local pipeline development., center=(1198,282), inner_text=📄️ Develop a pipeline

Using FlowDeploy to assist with local pipeline development., url='https://learn.flowdeploy.com/tutorial-basics/develop'
					heading 📄️ Develop a pipeline
					paragraph
			article
				[398] link 📄️ Deploy a pipeline Importing and deploying a custom versioned pipeline with GitHub., center=(700,439), inner_text=📄️ Deploy a pipeline

Importing and deploying a custom versioned pipeline with GitHub., url='https://learn.flowdeploy.com/tutorial-basics/deploy'
					heading 📄️ Deploy a pipeline
					paragraph
			article
				[402] link 📄️ Congratulations! You have conquered the basics of FlowDeploy!, center=(1198,439), inner_text=📄️ Congratulations!

You have conquered the basics of FlowDeploy!, url='https://learn.flowdeploy.com/tutorial-basics/congratulations'
					heading 📄️ Congratulations!
					paragraph
		navigation Docs pages
			[407] link Previous « Introduction, center=(704,587), inner_text=Previous
Introduction, url='https://learn.flowdeploy.com/'
			[410] link Next Run an open-source pipeline », center=(1194,587), inner_text=Next
Run an open-source pipeline, url='https://learn.flowdeploy.com/tutorial-basics/run'
	contentinfo
		StaticText Copyright © 2024 Toolchest, Inc.
	region
	region
	region
	region
	region
	region
```
</details>

**Reasoning for action:** By clicking on the 'Tutorials' link, I am accessing the section of the documentation that contains various tutorials. This is a crucial step towards fulfilling the user’s goal of exploring the available tutorials for learning how to manage bioinformatics pipelines. Once in the Tutorials section, I will be able to find specific tutorials including the one on running an open-source pipeline.

**Action:** click(194) # Click on the 'Tutorials' link to explore available tutorials.

**Change Description:** After clicking the 'Tutorials' link, the page changed to display the 'Tutorials' section of the FlowDeploy website, updating the main content area with tutorials available for users, including links to specific guides on running, developing, and deploying pipelines.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://learn.flowdeploy.com/category/tutorials

https://learn.flowdeploy.com/tutorial-basics/run

**Content (before/after):** 

```
RootWebArea Tutorials | FlowDeploy, focused, url='https://learn.flowdeploy.com/category/tutorials'
	region Skip to main content
		link Skip to main content, url='https://learn.flowdeploy.com/category/tutorials#__docusaurus_skipToContent_fallback'
	navigation Main
		[169] link FlowDeploy logo, center=(95,30), url='https://learn.flowdeploy.com/'
```
<details><summary>Show more</summary>

```
			image FlowDeploy logo, url='https://learn.flowdeploy.com/img/flowdeploy_logo.svg'
		[173] link Docs, center=(1627,30), url='https://learn.flowdeploy.com/'
		[174] link Blog, center=(1685,30), url='https://learn.flowdeploy.com/blog'
		[175] link Get started, center=(1766,30), url='https://app.flowdeploy.com/'
		[176] link Sign in, center=(1856,30), url='https://app.flowdeploy.com/'
	complementary
		link FlowDeploy logo, url='https://learn.flowdeploy.com/'
			image FlowDeploy logo, url='https://learn.flowdeploy.com/img/flowdeploy_logo.svg'
		navigation Docs sidebar
			list
				listitem
					[191] link Introduction, center=(146,84), url='https://learn.flowdeploy.com/'
				listitem
					[194] link Tutorials, center=(124,120), expanded=True, url='https://learn.flowdeploy.com/category/tutorials'
					[195] button Toggle the collapsible sidebar category 'Tutorials', center=(263,120), type=button
					list
						listitem
							[369] link Run an open-source pipeline, center=(152,156), url='https://learn.flowdeploy.com/tutorial-basics/run'
						listitem
							[371] link Develop a pipeline, center=(152,192), url='https://learn.flowdeploy.com/tutorial-basics/develop'
						listitem
							[373] link Deploy a pipeline, center=(152,228), url='https://learn.flowdeploy.com/tutorial-basics/deploy'
						listitem
							[375] link Congratulations!, center=(152,264), url='https://learn.flowdeploy.com/tutorial-basics/congratulations'
				listitem
					[198] link How-to Guides, center=(124,300), expanded=False, url='https://learn.flowdeploy.com/category/how-to-guides'
					[199] button Toggle the collapsible sidebar category 'How-to Guides', center=(263,300), type=button
				listitem
					[202] link Reference, center=(124,336), expanded=False, url='https://learn.flowdeploy.com/category/reference'
					[203] button Toggle the collapsible sidebar category 'Reference', center=(263,336), type=button
				listitem
					[206] link Knowledge base, center=(124,372), expanded=False, url='https://learn.flowdeploy.com/category/knowledge-base'
					[207] button Toggle the collapsible sidebar category 'Knowledge base', center=(263,372), type=button
		[208] button Collapse sidebar, center=(150,972), title=Collapse sidebar, type=button
	main
		navigation Breadcrumbs
			list
				listitem
					[380] link Home page, center=(485,90), url='https://learn.flowdeploy.com/'
						image
				[382] listitem, center=(562,99), inner_text=Tutorials
					StaticText Tutorials
		heading Tutorials
		article
			article
				[390] link 📄️ Run an open-source pipeline Running an open-source pipeline with FlowDeploy., center=(700,282), inner_text=📄️ Run an open-source pipeline

Running an open-source pipeline with FlowDeploy., url='https://learn.flowdeploy.com/tutorial-basics/run'
					heading 📄️ Run an open-source pipeline
					paragraph
			article
				[394] link 📄️ Develop a pipeline Using FlowDeploy to assist with local pipeline development., center=(1198,282), inner_text=📄️ Develop a pipeline

Using FlowDeploy to assist with local pipeline development., url='https://learn.flowdeploy.com/tutorial-basics/develop'
					heading 📄️ Develop a pipeline
					paragraph
			article
				[398] link 📄️ Deploy a pipeline Importing and deploying a custom versioned pipeline with GitHub., center=(700,439), inner_text=📄️ Deploy a pipeline

Importing and deploying a custom versioned pipeline with GitHub., url='https://learn.flowdeploy.com/tutorial-basics/deploy'
					heading 📄️ Deploy a pipeline
					paragraph
			article
				[402] link 📄️ Congratulations! You have conquered the basics of FlowDeploy!, center=(1198,439), inner_text=📄️ Congratulations!

You have conquered the basics of FlowDeploy!, url='https://learn.flowdeploy.com/tutorial-basics/congratulations'
					heading 📄️ Congratulations!
					paragraph
		navigation Docs pages
			[407] link Previous « Introduction, center=(704,587), inner_text=Previous
Introduction, url='https://learn.flowdeploy.com/'
			[410] link Next Run an open-source pipeline », center=(1194,587), inner_text=Next
Run an open-source pipeline, url='https://learn.flowdeploy.com/tutorial-basics/run'
	contentinfo
		StaticText Copyright © 2024 Toolchest, Inc.
	region
	region
	region
	region
	region
	region
```
</details>



```
RootWebArea Run an open-source pipeline | FlowDeploy, focused, url='https://learn.flowdeploy.com/tutorial-basics/run'
	region Skip to main content
		link Skip to main content, url='https://learn.flowdeploy.com/tutorial-basics/run#__docusaurus_skipToContent_fallback'
	navigation Main
		[169] link FlowDeploy logo, center=(95,30), url='https://learn.flowdeploy.com/'
```
<details><summary>Show more</summary>

```
			image FlowDeploy logo, url='https://learn.flowdeploy.com/img/flowdeploy_logo.svg'
		[173] link Docs, center=(1627,30), url='https://learn.flowdeploy.com/'
		[174] link Blog, center=(1685,30), url='https://learn.flowdeploy.com/blog'
		[175] link Get started, center=(1766,30), url='https://app.flowdeploy.com/'
		[176] link Sign in, center=(1856,30), url='https://app.flowdeploy.com/'
	complementary
		link FlowDeploy logo, url='https://learn.flowdeploy.com/'
			image FlowDeploy logo, url='https://learn.flowdeploy.com/img/flowdeploy_logo.svg'
		navigation Docs sidebar
			list
				listitem
					[191] link Introduction, center=(146,84), url='https://learn.flowdeploy.com/'
				listitem
					[194] link Tutorials, center=(124,120), expanded=True, url='https://learn.flowdeploy.com/category/tutorials'
					[195] button Toggle the collapsible sidebar category 'Tutorials', center=(263,120), type=button
					list
						listitem
							[369] link Run an open-source pipeline, center=(152,156), url='https://learn.flowdeploy.com/tutorial-basics/run'
						listitem
							[371] link Develop a pipeline, center=(152,192), url='https://learn.flowdeploy.com/tutorial-basics/develop'
						listitem
							[373] link Deploy a pipeline, center=(152,228), url='https://learn.flowdeploy.com/tutorial-basics/deploy'
						listitem
							[375] link Congratulations!, center=(152,264), url='https://learn.flowdeploy.com/tutorial-basics/congratulations'
				listitem
					[198] link How-to Guides, center=(124,300), expanded=False, url='https://learn.flowdeploy.com/category/how-to-guides'
					[199] button Toggle the collapsible sidebar category 'How-to Guides', center=(263,300), type=button
				listitem
					[202] link Reference, center=(124,336), expanded=False, url='https://learn.flowdeploy.com/category/reference'
					[203] button Toggle the collapsible sidebar category 'Reference', center=(263,336), type=button
				listitem
					[206] link Knowledge base, center=(124,372), expanded=False, url='https://learn.flowdeploy.com/category/knowledge-base'
					[207] button Toggle the collapsible sidebar category 'Knowledge base', center=(263,372), type=button
		[208] button Collapse sidebar, center=(150,1060), title=Collapse sidebar, type=button
	main
		article
			navigation Breadcrumbs
				list
					listitem
						[436] link Home page, center=(485,90), url='https://learn.flowdeploy.com/'
							image
					listitem
						[439] link Tutorials, center=(562,99), url='https://learn.flowdeploy.com/category/tutorials'
					[442] listitem, center=(712,99), inner_text=Run an open-source pipeline
						StaticText Run an open-source pipeline
			heading Run an open-source pipeline
			paragraph
				StaticText Running an open-source pipeline with FlowDeploy.
			paragraph
				StaticText Let's run the simple Nextflow pipeline to fetch NGS data,
				[452] link nf-core/fetchngs, center=(952,267), url='https://github.com/nf-core/fetchngs'
					code
				StaticText .
			heading In your browser Direct link to In your browser
				[455] link Direct link to In your browser, center=(768,345), inner_text=​, title=Direct link to In your browser, url='https://learn.flowdeploy.com/tutorial-basics/run#in-your-browser'
					StaticText ​
			paragraph
				StaticText Try the
				[458] link pre-populated nf-core/fetchngs example, center=(676,401), url='https://app.flowdeploy.com/pipelines/launch?selected=Fetch%20NGS%data'
					code
			heading In Python Direct link to In Python
				[461] link Direct link to In Python, center=(658,479), inner_text=​, title=Direct link to In Python, url='https://learn.flowdeploy.com/tutorial-basics/run#in-python'
					StaticText ​
			paragraph
				StaticText If you haven't already, make sure to:
			list
				[464] listitem, center=(961,580), inner_text=Install Python 3.9 or above
					ListMarker •
					StaticText Install Python 3.9 or above
				[465] listitem, center=(961,608), inner_text=Sign up for FlowDeploy, and create a new key
					ListMarker •
					StaticText Sign up for FlowDeploy, and create a new key
			list
				[467] listitem, center=(961,652), inner_text=Install the FlowDeploy Python package.
					ListMarker 0.
					StaticText Install the FlowDeploy Python package.
			code
				StaticText $ pip
				StaticText install
				StaticText flowdeploy
			[478] button Copy code to clipboard, center=(1400,704), title=Copy, type=button
			list
				[483] listitem, center=(961,765), inner_text=In Python, set your key and call flowdeploy.nextflow():
					ListMarker 0.
					StaticText In Python, set your key and call
					code
						StaticText flowdeploy.nextflow()
					StaticText :
			code
				StaticText import
				StaticText flowdeploy
				StaticText flowdeploy
				StaticText .
				StaticText set_key
				StaticText (
				StaticText "YOUR_KEY"
				StaticText )
				StaticText flowdeploy
				StaticText .
				StaticText nextflow
				StaticText (
				StaticText pipeline
				StaticText =
				StaticText "nf-core/fetchngs"
				StaticText ,
				StaticText pipeline_version
				StaticText =
				StaticText "1.10.0"
				StaticText ,
				StaticText outdir
				StaticText =
				StaticText "fd://YOUR_HOME/tutorial_one/"
				StaticText ,
				StaticText profiles
				StaticText =
				StaticText [
				StaticText "docker"
				StaticText ,
				StaticText "test"
				StaticText ]
				StaticText ,
				StaticText )
			[550] button Copy code to clipboard, center=(1400,817), title=Copy, type=button
			paragraph
				StaticText That's it! Execute your code, and the pipeline runs in FlowDeploy! 🎉
			paragraph
				StaticText You can follow the pipeline's execution in your browser.
			heading On the command line Direct link to On the command line
				link Direct link to On the command line, url='https://learn.flowdeploy.com/tutorial-basics/run#on-the-command-line'
					StaticText ​
			paragraph
				StaticText If you haven't already, make sure to:
			list
				listitem
					ListMarker •
					StaticText Install pip (or pipx)
				listitem
					ListMarker •
					StaticText Sign up for FlowDeploy, and create a new key
			list
				listitem
					ListMarker 0.
					StaticText Install the FlowDeploy CLI and Python package:
			code
				StaticText pip install flowdeploy
			button Copy code to clipboard
			list
				listitem
					ListMarker 0.
					StaticText Set your key and call
					code
						StaticText flowdeploy run
			code
				StaticText flowdeploy set-key YOUR_KEY
				StaticText flowdeploy run nextflow nf-core/fetchngs --version 1.10.0 --outdir fd://YOUR_HOME/tutorial_one --profile docker --profile test
			button Toggle word wrap
			button Copy code to clipboard
			paragraph
				StaticText That's it! Run the command, and the pipeline runs in FlowDeploy! 🎉
		navigation Docs pages
			link Previous « Tutorials, url='https://learn.flowdeploy.com/category/tutorials'
			link Next Develop a pipeline », url='https://learn.flowdeploy.com/tutorial-basics/develop'
		list
			listitem
				[608] link In your browser, center=(1610,102), url='https://learn.flowdeploy.com/tutorial-basics/run#in-your-browser'
			listitem
				[610] link In Python, center=(1610,129), url='https://learn.flowdeploy.com/tutorial-basics/run#in-python'
			listitem
				[612] link On the command line, center=(1610,156), url='https://learn.flowdeploy.com/tutorial-basics/run#on-the-command-line'
	contentinfo
		StaticText Copyright © 2024 Toolchest, Inc.
	region
	region
	region
	region
	region
	region
```
</details>

**Reasoning for action:** I chose to click on the 'Run an open-source pipeline' tutorial link because this is the specific tutorial that the user story indicates is of interest. By selecting this link, I will be able to access the detailed instructions and information pertaining to running the tutorial, thus fulfilling the user's goal of exploring the FlowDeploy documentation and learning how to effectively run a bioinformatics pipeline.

**Action:** click(369) # Click on the 'Run an open-source pipeline' tutorial to explore its content.

**Change Description:** The browser navigated to the 'Run an open-source pipeline' tutorial page, changing the URL to 'https://learn.flowdeploy.com/tutorial-basics/run' and updating the main content area to display the tutorial's details, header, and related paragraphs.

**Screenshot before:****Screenshot after:**---


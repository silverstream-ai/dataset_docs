# Task

**Explore Security Features and Articles**

As a prospective customer,
I explore the security features and gain insights on software capitalization,
so that I can make informed decisions about using Mogara's services to enhance my company's financial processes.

**Success definition:** Given I am on the Mogara homepage
When I click on 'Our Security Promise' and then the 'Blog' link, followed by the first blog post titled '3 approaches to software capitalization'
Then I should see the blog post content related to software capitalization, confirming that I have successfully navigated through the security information and found relevant articles.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.mogara.com/

https://www.mogara.com/security

**Content (before/after):** 

```
RootWebArea Mogara, focused, url='https://www.mogara.com/'
	banner
		[27] link home, center=(368,34), url='https://www.mogara.com/'
			image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/644981a3e9e76b2a67498320_NEWLOGO.png'
		navigation
```
<details><summary>Show more</summary>

```
			[31] link Our Security Promise, center=(572,32), url='https://www.mogara.com/security'
			[34] link Blog, center=(704,32), url='https://www.mogara.com/blog'
			[37] link Contact, center=(786,32), url='https://aziduahbl4o.typeform.com/to/C0CvsfXP'
	heading R&D Cost Capitalization, automated.
	paragraph
		StaticText Mogara captures and categorizes capitalizable work by plugging directly into the developer workflow.
	form Email Form
		[50] textbox Your Email, center=(314,502), contenteditable=True, required, type=email
		[51] button Request Demo, center=(464,502), contenteditable=True, type=submit
	StaticText Backed by
	image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/640a07898e74bb34037595fd_image-4.png'
	image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/6441681c0ba367d867f467bc_Project%20Dashboard-p-1080.png'
	heading Mogara helps you close your books faster
	image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/644ab29ad02eff3d0ad609ef_Graphic%201.png'
	heading Integrate with tools your teams already use
	paragraph
		StaticText We pull data from IDEs and code repositories, so you're not waiting for survey responses from the engineering team
	image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/645076dbb78954404d394c90_Frame%208833.png'
	heading Enable a fully automated process
	paragraph
		StaticText Mogara is a modular platform. We meet you where you are today in your capitalization journey, and help you work toward a fully-automated process over time
	image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/644ab293cde18e45c12c2069_Graphic%202).png'
	heading Consistently reinforce capitalization standards
	paragraph
		StaticText Configure the Mogara capitalization engine to auto-categorize capitalizable activity according to your specific accounting policies
	heading How we automate your workflows
	button Tie R&D resources to projects, expanded=False, hasPopup='menu'
	navigation Tie R&D resources to projects
		paragraph
			StaticText Mogara identifies which engineers committed code to each project automatically, so you don't need to build an internal tool to track resourcing or survey your engineering leaders.
	button Identify capitalizable projects, expanded=False, hasPopup='menu'
	navigation Identify capitalizable projects
		paragraph
			StaticText The platform automatically prompts engineering leaders to identify completed projects as capitalizable or leverage our engine to make a capitalization determination -- so you're not left chasing down data at the end of the quarter.
	button Identify time windows of active work, expanded=False, hasPopup='menu'
	navigation Identify time windows of active work
		paragraph
			StaticText Mogara pulls from existing sources to identify start and stop times of any given project as well as the total work time from any contributing team member.
	button Auto-categorize capitalizabile activity, expanded=False, hasPopup='menu'
	navigation Auto-categorize capitalizabile activity
		paragraph
			StaticText Every coding description can be analyzed by  Mogara as capitalizable, or not, with a workflow for a final review with the responsible engineering leader.
	button Sync to accounting systems, expanded=False, hasPopup='menu'
	navigation Sync to accounting systems
		paragraph
			StaticText Mogara syncs with enterprise-grade file sharing systems and ERPs to ensure that all data is audit-ready and month-end ready.
	heading Security & Privacy
	StaticText We follow industry-standard practices for data security.
	link Learn More, url='https://www.mogara.com/security'
	link, url='https://www.mogara.com/#'
		image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/644981a3e9e76b2a67498320_NEWLOGO.png'
	heading Mogara
	link Homepage, url='https://www.mogara.com/'
	link Our Security Promise, url='https://www.mogara.com/security'
	link Blog, url='https://www.mogara.com/blog'
	link Contact Us, url='https://aziduahbl4o.typeform.com/to/C0CvsfXP'
	StaticText Copyright © 2021 — 2023 Mogara. All rights reserved.
```
</details>



```
RootWebArea Mogara Security, focused, url='https://www.mogara.com/security'
	banner
		[22] link home, center=(368,34), url='https://www.mogara.com/'
			image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/644981a3e9e76b2a67498320_NEWLOGO.png'
		navigation
```
<details><summary>Show more</summary>

```
			[26] link Our Security Promise, center=(572,32), url='https://www.mogara.com/security'
			[29] link Blog, center=(704,32), url='https://www.mogara.com/blog'
			[32] link Contact, center=(786,32), url='https://aziduahbl4o.typeform.com/to/C0CvsfXP'
	heading Security at Mogara
	StaticText We follow industry-standard practices for data security.
	heading Our Security Measures
	paragraph
		StaticText Your security is our top priority. Mogara takes every step possible to ensure your data is protected and safe. We are SOC 2 Type 1 compliant. Please send questions or report issues to
		[44] link security@mogara.com, center=(1116,684), url='mailto:security@mogara.com'
		StaticText .
	list
		listitem
			StaticText Data security
			paragraph
				StaticText We encrypt data at rest and in transit. All connections to Mogara are encrypted using SSL, and any attempt to connect over HTTP is redirected to HTTPS. We maintain an
				[55] link A grade for Qualys/SSL labs, center=(1082,815), inner_text= A grade for Qualys/SSL labs, url='https://www.ssllabs.com/ssltest/analyze.html?d=mogara.app'
				StaticText . We rely on AWS infrastructure to securely maintain our cryptographic encryption keys. We use industry-standard AWS-managed storage systems.
			[51] div, center=(593,758), inner_text=Data security
		listitem
			StaticText Development and change management
			[63] paragraph, center=(960,1024), inner_text=Changes to the company’s code are tracked via GitHub and automated controls ensure each change is peer-reviewed and passes a series of tests before being deployed to production. Changes to infrastructure are made via infrastructure as code (Terraform) and are manually reviewed.

				StaticText Changes to the company’s code are tracked via GitHub and automated controls ensure each change is peer-reviewed and passes a series of tests before being deployed to production. Changes to infrastructure are made via infrastructure as code (Terraform) and are manually reviewed.
			[60] div, center=(716,967), inner_text=Development and change management
		listitem
			StaticText Secure infrastructure
			paragraph
				StaticText Mogara hosts all data and applications in Amazon Web Services (AWS) facilities in the USA. Amazon provides an extensive list of compliance and regulatory assurances, including SOC 1-3, and ISO 27001. See Amazon’s compliance documents for more information. All of Mogara’s servers are located within a dedicated virtual private cloud (VPC), protected by restricted security groups allowing only the minimal required communication to and between the servers.
		listitem
			StaticText Application security
			paragraph
				StaticText Web application architecture and implementation are built in Python and follow OWASP guidelines. We regularly run internal application penetration testing and plan to conduct third-party testing soon.
		listitem
			StaticText Third-party vendor security review process
			paragraph
				StaticText We ensure that all of our third-party apps and providers meet our security data protection standards before using them. We leverage third-party built-in permissioning for managing user access. Our vendor list can be found
				link here., url='https://docs.google.com/spreadsheets/d/1sDwszTxExWZL2n3iSSEQ0jdqWRQ7RPTxQb_Z_zO5ACk/edit?usp=sharing'
	image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/64af8858d931f01930591305_SOC%202%20Icon.png'
	link, url='https://www.mogara.com/security#'
		image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/644981a3e9e76b2a67498320_NEWLOGO.png'
	heading Mogara
	link Homepage, url='https://www.mogara.com/'
	link Our Security Promise, url='https://www.mogara.com/security'
	link Blog, url='https://www.mogara.com/blog'
	link Contact Us, url='https://aziduahbl4o.typeform.com/to/C0CvsfXP'
	StaticText Copyright © 2021 — 2023 Mogara. All rights reserved.
```
</details>

**Reasoning for action:** I clicked on 'Our Security Promise' to access detailed information about Mogara's security practices. This is the first step in fulfilling the user story, as it allows me to gather insights into how Mogara ensures the safety and security of its services, which is critical for making informed decisions.

**Action:** click(31) # Click on 'Our Security Promise' link to explore security features.

**Change Description:** The browser navigated from the main Mogara page to the 'Our Security Promise' page, updating the URL to 'https://www.mogara.com/security' and changing the heading to 'Security at Mogara' while providing detailed information on the company's security measures.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.mogara.com/security

https://www.mogara.com/blog

**Content (before/after):** 

```
RootWebArea Mogara Security, focused, url='https://www.mogara.com/security'
	banner
		[22] link home, center=(368,34), url='https://www.mogara.com/'
			image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/644981a3e9e76b2a67498320_NEWLOGO.png'
		navigation
```
<details><summary>Show more</summary>

```
			[26] link Our Security Promise, center=(572,32), url='https://www.mogara.com/security'
			[29] link Blog, center=(704,32), url='https://www.mogara.com/blog'
			[32] link Contact, center=(786,32), url='https://aziduahbl4o.typeform.com/to/C0CvsfXP'
	heading Security at Mogara
	StaticText We follow industry-standard practices for data security.
	heading Our Security Measures
	paragraph
		StaticText Your security is our top priority. Mogara takes every step possible to ensure your data is protected and safe. We are SOC 2 Type 1 compliant. Please send questions or report issues to
		[44] link security@mogara.com, center=(1116,684), url='mailto:security@mogara.com'
		StaticText .
	list
		listitem
			StaticText Data security
			paragraph
				StaticText We encrypt data at rest and in transit. All connections to Mogara are encrypted using SSL, and any attempt to connect over HTTP is redirected to HTTPS. We maintain an
				[55] link A grade for Qualys/SSL labs, center=(1082,815), inner_text= A grade for Qualys/SSL labs, url='https://www.ssllabs.com/ssltest/analyze.html?d=mogara.app'
				StaticText . We rely on AWS infrastructure to securely maintain our cryptographic encryption keys. We use industry-standard AWS-managed storage systems.
			[51] div, center=(593,758), inner_text=Data security
		listitem
			StaticText Development and change management
			[63] paragraph, center=(960,1024), inner_text=Changes to the company’s code are tracked via GitHub and automated controls ensure each change is peer-reviewed and passes a series of tests before being deployed to production. Changes to infrastructure are made via infrastructure as code (Terraform) and are manually reviewed.

				StaticText Changes to the company’s code are tracked via GitHub and automated controls ensure each change is peer-reviewed and passes a series of tests before being deployed to production. Changes to infrastructure are made via infrastructure as code (Terraform) and are manually reviewed.
			[60] div, center=(716,967), inner_text=Development and change management
		listitem
			StaticText Secure infrastructure
			paragraph
				StaticText Mogara hosts all data and applications in Amazon Web Services (AWS) facilities in the USA. Amazon provides an extensive list of compliance and regulatory assurances, including SOC 1-3, and ISO 27001. See Amazon’s compliance documents for more information. All of Mogara’s servers are located within a dedicated virtual private cloud (VPC), protected by restricted security groups allowing only the minimal required communication to and between the servers.
		listitem
			StaticText Application security
			paragraph
				StaticText Web application architecture and implementation are built in Python and follow OWASP guidelines. We regularly run internal application penetration testing and plan to conduct third-party testing soon.
		listitem
			StaticText Third-party vendor security review process
			paragraph
				StaticText We ensure that all of our third-party apps and providers meet our security data protection standards before using them. We leverage third-party built-in permissioning for managing user access. Our vendor list can be found
				link here., url='https://docs.google.com/spreadsheets/d/1sDwszTxExWZL2n3iSSEQ0jdqWRQ7RPTxQb_Z_zO5ACk/edit?usp=sharing'
	image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/64af8858d931f01930591305_SOC%202%20Icon.png'
	link, url='https://www.mogara.com/security#'
		image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/644981a3e9e76b2a67498320_NEWLOGO.png'
	heading Mogara
	link Homepage, url='https://www.mogara.com/'
	link Our Security Promise, url='https://www.mogara.com/security'
	link Blog, url='https://www.mogara.com/blog'
	link Contact Us, url='https://aziduahbl4o.typeform.com/to/C0CvsfXP'
	StaticText Copyright © 2021 — 2023 Mogara. All rights reserved.
```
</details>



```
RootWebArea Blog - Webflow Template, focused, url='https://www.mogara.com/blog'
	banner
		[27] link home, center=(368,34), url='https://www.mogara.com/'
			image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/644981a3e9e76b2a67498320_NEWLOGO.png'
		navigation
```
<details><summary>Show more</summary>

```
			[31] link Our Security Promise, center=(572,32), url='https://www.mogara.com/security'
			[34] link Blog, center=(704,32), url='https://www.mogara.com/blog'
			[37] link Contact, center=(786,32), url='https://aziduahbl4o.typeform.com/to/C0CvsfXP'
	heading Blog
	heading Mogara Blog Posts
	list
		listitem
			[50] link 3 approaches to software capitalization June 21, 2023 We’ve spoken to and learned from dozens of companies who capitalize software. Here are 3 approaches we’ve seen., center=(960,747), inner_text=3 approaches to software capitalization
June 21, 2023

We’ve spoken to and learned from dozens of companies who capitalize software. Here are 3 approaches we’ve seen., url='https://www.mogara.com/post/approaches-software-cap'
				heading 3 approaches to software capitalization
				paragraph
		listitem
			[56] link ACCOUNTING Software Capitalization 101 May 2, 2023 For the software-capitalization curious, we cover what software capitalization is, who does it & what it takes to execute on it., center=(960,1007), inner_text=ACCOUNTING
Software Capitalization 101
May 2, 2023

For the software-capitalization curious, we cover what software capitalization is, who does it & what it takes to execute on it., url='https://www.mogara.com/post/software-capitalization-101'
				heading ACCOUNTING
				heading Software Capitalization 101
				paragraph
	link, url='https://www.mogara.com/blog#'
		image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/644981a3e9e76b2a67498320_NEWLOGO.png'
	heading Mogara
	link Homepage, url='https://www.mogara.com/'
	link Our Security Promise, url='https://www.mogara.com/security'
	link Blog, url='https://www.mogara.com/blog'
	link Contact Us, url='https://aziduahbl4o.typeform.com/to/C0CvsfXP'
	StaticText Copyright © 2021 — 2023 Mogara. All rights reserved.
```
</details>

**Reasoning for action:** Since the user story requires me to explore articles on software capitalization after reviewing the security features, clicking on the 'Blog' link is essential. This action redirects me to the blog section of the Mogara website, thereby moving me closer to locating the relevant content that will help the user make informed decisions.

**Action:** click(29) # Click on the 'Blog' link to explore related articles.

**Change Description:** The browser changed to the 'Blog' page of Mogara, displaying a new heading and list of blog posts. The URL updated to 'https://www.mogara.com/blog', and the content now reflects articles about software capitalization instead of security measures.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.mogara.com/blog

https://www.mogara.com/post/approaches-software-cap

**Content (before/after):** 

```
RootWebArea Blog - Webflow Template, focused, url='https://www.mogara.com/blog'
	banner
		[27] link home, center=(368,34), url='https://www.mogara.com/'
			image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/644981a3e9e76b2a67498320_NEWLOGO.png'
		navigation
```
<details><summary>Show more</summary>

```
			[31] link Our Security Promise, center=(572,32), url='https://www.mogara.com/security'
			[34] link Blog, center=(704,32), url='https://www.mogara.com/blog'
			[37] link Contact, center=(786,32), url='https://aziduahbl4o.typeform.com/to/C0CvsfXP'
	heading Blog
	heading Mogara Blog Posts
	list
		listitem
			[50] link 3 approaches to software capitalization June 21, 2023 We’ve spoken to and learned from dozens of companies who capitalize software. Here are 3 approaches we’ve seen., center=(960,747), inner_text=3 approaches to software capitalization
June 21, 2023

We’ve spoken to and learned from dozens of companies who capitalize software. Here are 3 approaches we’ve seen., url='https://www.mogara.com/post/approaches-software-cap'
				heading 3 approaches to software capitalization
				paragraph
		listitem
			[56] link ACCOUNTING Software Capitalization 101 May 2, 2023 For the software-capitalization curious, we cover what software capitalization is, who does it & what it takes to execute on it., center=(960,1007), inner_text=ACCOUNTING
Software Capitalization 101
May 2, 2023

For the software-capitalization curious, we cover what software capitalization is, who does it & what it takes to execute on it., url='https://www.mogara.com/post/software-capitalization-101'
				heading ACCOUNTING
				heading Software Capitalization 101
				paragraph
	link, url='https://www.mogara.com/blog#'
		image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/644981a3e9e76b2a67498320_NEWLOGO.png'
	heading Mogara
	link Homepage, url='https://www.mogara.com/'
	link Our Security Promise, url='https://www.mogara.com/security'
	link Blog, url='https://www.mogara.com/blog'
	link Contact Us, url='https://aziduahbl4o.typeform.com/to/C0CvsfXP'
	StaticText Copyright © 2021 — 2023 Mogara. All rights reserved.
```
</details>



```
RootWebArea Mogara, focused, url='https://www.mogara.com/post/approaches-software-cap'
	banner
		[40] link home, center=(368,34), url='https://www.mogara.com/'
			image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/644981a3e9e76b2a67498320_NEWLOGO.png'
		navigation
```
<details><summary>Show more</summary>

```
			[44] link Our Security Promise, center=(572,32), url='https://www.mogara.com/security'
			[47] link Blog, center=(704,32), url='https://www.mogara.com/blog'
			[50] link Contact, center=(786,32), url='https://aziduahbl4o.typeform.com/to/C0CvsfXP'
	heading 3 approaches to software capitalization
	StaticText June 21, 2023
	paragraph
		StaticText ‍
	blockquote
		StaticText For accounting leaders looking to baseline their capitalization approach
	paragraph
		StaticText ‍
	paragraph
		StaticText We’ve spoken to and learned from dozens of companies who capitalize software. Here are 3 approaches we’ve seen:
	heading Approach #1: The “Reasonable Percentage”
	paragraph
		StaticText Accounting & engineering leaders review all the projects over a given quarter or year, identify which ones are capitalizable, who worked on them, and how long they were. This typically happens in a meeting with a few follow-up conversations to confirm all capitalizable projects are being tracked.
	paragraph
		StaticText Accounting pulls total compensation for each of the R&D resources and applies a reasonable capitalization percentage for the R&D resources for the length of the project. This “reasonable percentage” is usually developed through a review of projects to understand what a typical capitalizable percentage looks like. The sum of all capitalized compensation for R&D resources on a given project is the software capitalization balance to be reviewed for materiality to determine whether or not to book.
	paragraph
		emphasis
			StaticText ‍
	paragraph
		emphasis
			StaticText ‍
		strong
			emphasis
				StaticText Who we’ve seen doing this:
		StaticText Mid-stage companies who are preparing for or have gone through their first PCAOB audit and are not capitalizing a material amount
	paragraph
		StaticText ‍
	heading Approach #2: The “Time Sheet”
	paragraph
		strong
			StaticText ‍
		StaticText Once accounting has gathered the list of projects and engineers tied to each project, they survey engineers with a time sheet for the percentage of time they spent on capitalizable activity for each project they worked on. This requires educating engineers on what capitalizable activity is and sheer responsiveness to gather the data in a timely manner but it’s much more precise.
	paragraph
		StaticText Once this percentage data has been collected from every engineer (usually after a few follow-ups), an accounting leader can pull in total compensation and continue with the same process as above to calculate a capitalized software balance.
		strong
			StaticText ‍
	paragraph
		StaticText ‍
	paragraph
		strong
			emphasis
				StaticText Who we’ve seen doing this
			StaticText :
		StaticText Late-stage growth and public companies who have material capitalization amounts
	paragraph
		StaticText ‍
	heading Approach #3: The “Deep Dive”
	paragraph
		strong
			StaticText ‍
		StaticText Instead of asking engineers to fill out time estimates, a single accounting or engineering leader will deep dive into all issue tracking data (like Jira epics and tickets) in the time period to develop a capitalizable percentage per project. They’ll get an export of issues from the system, review time estimate fields and read descriptions of issues to understand what might be capitalizable activity. This review is meaningful — we heard from one engineering leader who reviews 400 Jira epics annually in this approach.
	paragraph
		StaticText ‍
	paragraph
		strong
			emphasis
				StaticText Who we’ve seen doing this
		StaticText : Late-stage growth and public companies who have material capitalization amounts
	paragraph
		StaticText ‍
	heading Mogara can automate each piece of these workflows.
	paragraph
		StaticText Mogara can identify which engineers worked on which projects, how long each project was and, most critically, can calculate the percentage of capitalizable activity for each individual project. We pull in total compensation data and can easily export data to accounting workpapers and your ERP system. Get in touch!
	paragraph
		StaticText ‍
	link, url='https://www.mogara.com/post/approaches-software-cap#'
		image, url='https://cdn.prod.website-files.com/63e2bc7a8e436a43a2c001a2/644981a3e9e76b2a67498320_NEWLOGO.png'
	heading Mogara
	link Homepage, url='https://www.mogara.com/'
	link Our Security Promise, url='https://www.mogara.com/security'
	link Blog, url='https://www.mogara.com/blog'
	link Contact Us, url='https://aziduahbl4o.typeform.com/to/C0CvsfXP'
	StaticText Copyright © 2021 — 2023 Mogara. All rights reserved.
```
</details>

**Reasoning for action:** In order to fulfill the user story, I needed to navigate to the blog post that specifically addresses software capitalization. Clicking on the link (50) for '3 approaches to software capitalization' advances me toward showing the user relevant content that will enable them to explore the information they need regarding Mogara's services and software capitalization. This step is crucial as it directly leads to the insights that the user is seeking.

**Action:** click(50) # Click on the first blog post '3 approaches to software capitalization' to read more.

**Change Description:** The browser navigated from the blog main page to the specific blog post titled '3 approaches to software capitalization', updating the URL to 'https://www.mogara.com/post/approaches-software-cap', and now displays the content of the selected blog post including headings, paragraphs, and specific details related to the topic.

**Screenshot before:****Screenshot after:**---


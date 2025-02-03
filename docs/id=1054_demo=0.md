# Task

**User Journey for Simple Scraper Exploration**

As a data analyst,
I explore the Simple Scraper feature to understand its capabilities,
so that I can efficiently extract data from websites for analysis.

**Success definition:** Given I am on the Simple Scraper page of the Indexical Playground
When I enter a sample URL into the URL textbox and click 'Extract'
Then I should see the scraping results displayed, showing the relevant extracted data from the entered URL.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://indexical.dev/

https://playground.indexical.dev/

**Content (before/after):** 

```
RootWebArea Indexical - Web Crawling and Scraping Powered by LLMs., focused, url='https://indexical.dev/'
	[23] link #Indexical, center=(277,47), url='https://indexical.dev/'
	[26] link Playground, center=(1272,47), url='https://playground.indexical.dev/'
	[27] link Blog, center=(1370,47), url='https://blog.indexical.dev/'
	[28] link Docs, center=(1438,47), url='https://docs.indexical.dev/'
```
<details><summary>Show more</summary>

```
	[29] link Console, center=(1522,47), url='https://console.indexical.dev/'
	[30] link Sign Up, center=(1651,47), url='https://auth.indexical.dev/en/signup'
	StaticText Get The Data
	StaticText You Need
	StaticText Write & run zero-maintenance web scraping pipelines with natural language steps
	[41] link Get Started   →, center=(341,696), url='https://auth.indexical.dev/en/signup'
	StaticText Backed by
	image
	StaticText Combinator
	code
		StaticText {
		StaticText "action"
		StaticText :
		StaticText "navigate"
		StaticText ,
		StaticText "goal"
		StaticText :
		StaticText "Find a link to the product specifications"
		StaticText },
		StaticText {
		StaticText "action"
		StaticText :
		StaticText "extract"
		StaticText ,
		StaticText "goal"
		StaticText :
		StaticText "Extract the product details"
		StaticText ,
		StaticText "schema"
		StaticText : {
		StaticText "product_number"
		StaticText : {
		StaticText "type"
		StaticText :
		StaticText "string"
		StaticText ,
		StaticText "description"
		StaticText :
		StaticText "This device's Product Number"
		StaticText },
		StaticText "price"
		StaticText : {
		StaticText "type"
		StaticText :
		StaticText "string"
		StaticText ,
		StaticText "description"
		StaticText :
		StaticText "The device's price"
		StaticText },
		StaticText "description"
		StaticText :
		StaticText "$mainContent"
		StaticText }
		StaticText }
	StaticText Powered by LLMs
	StaticText Indexical uses LLMs to intelligently navigate the web and extract data, so you don't have to worry about brittle selectors and complicated interaction scripts.
	StaticText Built for Devs
	StaticText Indexical scraping & crawling jobs are defined with well-documented, version-controllable JSON pipelines that give you fine-grain control without any boilerplate.
	StaticText Fault-tolerant & Robust
	StaticText Indexical's scrapers automatically handle proxying, retries, rate-limiting, and other best-practices to ensure you get the data you're looking for
	StaticText Fully Managed
	StaticText Indexical provides an easy-to-use API, a CLI, and a web UI to make creating, running, and monitoring your scraping jobs as smooth as possible
	heading Pricing for Every Need
	paragraph
		StaticText Choose the plan that fits your business best.
	heading Free
	StaticText $0
	StaticText /month
	StaticText No credit card required
	StaticText 1000 credits per month
	StaticText API and dashboard access
	link Get Started, url='https://auth.indexical.dev/en/signup'
	heading Hobby
	StaticText $30
	StaticText /month
	StaticText 3,000 credits per month
	StaticText API and Dashboard Access
	link Get Started, url='https://auth.indexical.dev/en/signup'
	heading Startup
	StaticText $100
	StaticText /month
	StaticText 20,000 credits per month
	StaticText API and dashboard access
	StaticText Priority support
	link Get Started, url='https://auth.indexical.dev/en/signup'
	heading Growth
	StaticText $500
	StaticText /month
	StaticText 150,000 credits per month
	StaticText API and dashboard access
	StaticText Priority support
	StaticText CEO's number
	link Get Started, url='https://auth.indexical.dev/en/signup'
	heading Need more credits or implementation help?
	link Chat with Us, url='https://cal.com/shanelle-indexical/intro'
	heading Understanding Credit Usage
	paragraph
		StaticText Scraping & crawling jobs in Indexical can use different amounts of credits depending on their complexity and resource-usage. See the table below to estimate which plan is appropriate for your intended usecase.
	table
		rowgroup
			row
				columnheader Action
				columnheader Cost
		rowgroup
			row
				cell Non-proxy page load
				cell 1 credit
			row
				cell Proxy page load
				cell 5 credits
			row
				cell LLM extraction
				cell 5 credits
			row
				cell Visual extraction
				cell 5 credits
			row
				cell Search API query
				cell 5 credits
	contentinfo
		heading Indexical
		paragraph
			StaticText AI-powered web scraping & data extraction engine
		link LinkedIn, url='https://www.linkedin.com/company/indexical-ai/'
		link Privacy Policy, url='https://indexical.dev/privacy.html'
		link Terms of Service, url='https://indexical.dev/terms.html'
		paragraph
			StaticText Made with ❤️ in San Francisco © 2024 Raio Technologies, Inc.
```
</details>



```
RootWebArea Indexical Playground, focused, url='https://playground.indexical.dev/'
	banner
		heading API Playground
		[22] link Sign Up, center=(1852,36), url='https://auth.indexical.dev/en/signup'
	heading Available Pipelines
```
<details><summary>Show more</summary>

```
	list
		listitem
			[28] heading Simple Scraper, center=(328,176)
			[29] paragraph, center=(328,198), inner_text=Scrape the content of the page
				StaticText Scrape the content of the page
		listitem
			[31] heading Simple Crawler, center=(328,244)
			[32] paragraph, center=(328,266), inner_text=Crawl through the first 2 pages of the website and scrape the main content.
				StaticText Crawl through the first 2 pages of the website and scrape the main content.
		listitem
			[34] heading Product Data Extractor, center=(328,312)
			[35] paragraph, center=(328,334), inner_text=Extract product information from an ecommerce details page.
				StaticText Extract product information from an ecommerce details page.
		listitem
			[37] heading News Article Extractor, center=(328,380)
			[38] paragraph, center=(328,402), inner_text=Extract the main text content from a news article.
				StaticText Extract the main text content from a news article.
	StaticText Please select a pipeline to get started.
	contentinfo
		heading Indexical
			link Indexical, url='https://indexical.dev/'
		paragraph
			StaticText AI-powered web scraping & data extraction engine
		link LinkedIn, url='https://www.linkedin.com/company/indexical-ai/'
		link Privacy Policy, url='https://indexical.dev/privacy'
		link Terms of Service, url='https://indexical.dev/terms'
		paragraph
			StaticText Made with ❤️ in San Francisco © 2024 Raio Technologies, Inc.
	alert, atomic
```
</details>

**Reasoning for action:** My reasoning for this action is that in order to explore the Simple Scraper feature, I first need to access the correct page where it is found. Clicking on the Playground link takes me to the desired area of the application where I can find the tools and options related to data scraping, thus taking me closer to completing the user story.

**Action:** click(26) # Click on the Playground link to explore its features.

**Change Description:** The browser navigated from the Indexical homepage to the Playground section, where the title changed to 'API Playground' and several available pipelines for web scraping were displayed, including options such as 'Simple Scraper' and 'Product Data Extractor'.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://playground.indexical.dev/

https://playground.indexical.dev/

**Content (before/after):** 

```
RootWebArea Indexical Playground, focused, url='https://playground.indexical.dev/'
	banner
		heading API Playground
		[22] link Sign Up, center=(1852,36), url='https://auth.indexical.dev/en/signup'
	heading Available Pipelines
```
<details><summary>Show more</summary>

```
	list
		listitem
			[28] heading Simple Scraper, center=(328,176)
			[29] paragraph, center=(328,198), inner_text=Scrape the content of the page
				StaticText Scrape the content of the page
		listitem
			[31] heading Simple Crawler, center=(328,244)
			[32] paragraph, center=(328,266), inner_text=Crawl through the first 2 pages of the website and scrape the main content.
				StaticText Crawl through the first 2 pages of the website and scrape the main content.
		listitem
			[34] heading Product Data Extractor, center=(328,312)
			[35] paragraph, center=(328,334), inner_text=Extract product information from an ecommerce details page.
				StaticText Extract product information from an ecommerce details page.
		listitem
			[37] heading News Article Extractor, center=(328,380)
			[38] paragraph, center=(328,402), inner_text=Extract the main text content from a news article.
				StaticText Extract the main text content from a news article.
	StaticText Please select a pipeline to get started.
	contentinfo
		heading Indexical
			link Indexical, url='https://indexical.dev/'
		paragraph
			StaticText AI-powered web scraping & data extraction engine
		link LinkedIn, url='https://www.linkedin.com/company/indexical-ai/'
		link Privacy Policy, url='https://indexical.dev/privacy'
		link Terms of Service, url='https://indexical.dev/terms'
		paragraph
			StaticText Made with ❤️ in San Francisco © 2024 Raio Technologies, Inc.
	alert, atomic
```
</details>



```
RootWebArea Indexical Playground, focused, url='https://playground.indexical.dev/'
	banner
		heading API Playground
		[22] link Sign Up, center=(1852,36), url='https://auth.indexical.dev/en/signup'
	heading Available Pipelines
```
<details><summary>Show more</summary>

```
	list
		listitem
			[28] heading Simple Scraper, center=(328,176)
			[29] paragraph, center=(328,198), inner_text=Scrape the content of the page
				StaticText Scrape the content of the page
		listitem
			[31] heading Simple Crawler, center=(328,244)
			[32] paragraph, center=(328,266), inner_text=Crawl through the first 2 pages of the website and scrape the main content.
				StaticText Crawl through the first 2 pages of the website and scrape the main content.
		listitem
			[34] heading Product Data Extractor, center=(328,312)
			[35] paragraph, center=(328,334), inner_text=Extract product information from an ecommerce details page.
				StaticText Extract product information from an ecommerce details page.
		listitem
			[37] heading News Article Extractor, center=(328,380)
			[38] paragraph, center=(328,402), inner_text=Extract the main text content from a news article.
				StaticText Extract the main text content from a news article.
	heading Simple Scraper
	paragraph
		StaticText Scrape the content of the page
	LabelText
		StaticText Enter a URL:
	[74] textbox Enter a URL:, center=(1232,240), contenteditable=True, type=text
	[75] button Extract, center=(1840,240)
	heading Pipeline Specification
	StaticText [
  {
    "goal": "extract the following information",
    "action": "extract",
    "schema": {
      "textContent": "$textContent",
      "htmlContentDownloaded": "$download",
      "screenshot": "$screenshot"
    }
  }
]
	contentinfo
		heading Indexical
			[45] link Indexical, center=(360,710), url='https://indexical.dev/'
		paragraph
			StaticText AI-powered web scraping & data extraction engine
		[48] link LinkedIn, center=(329,780), url='https://www.linkedin.com/company/indexical-ai/'
		[52] link Privacy Policy, center=(1397,706), url='https://indexical.dev/privacy'
		[53] link Terms of Service, center=(1397,734), url='https://indexical.dev/terms'
		paragraph
			StaticText Made with ❤️ in San Francisco © 2024 Raio Technologies, Inc.
	alert, atomic
```
</details>

**Reasoning for action:** I clicked on the Simple Scraper heading because it aligns with my task of understanding the capabilities of the Simple Scraper. By doing this, I can access detailed information about this feature, which is essential for extracting data from websites effectively.

**Action:** click(28) # Click on the Simple Scraper heading to learn more about it.

**Change Description:** After clicking on the Simple Scraper heading, additional details regarding the Simple Scraper pipeline were displayed, including a heading for Simple Scraper, a textbox to enter a URL, a button labeled 'Extract', and a specification of the pipeline's goal and action.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://playground.indexical.dev/

https://playground.indexical.dev/

**Content (before/after):** 

```
RootWebArea Indexical Playground, focused, url='https://playground.indexical.dev/'
	banner
		heading API Playground
		[22] link Sign Up, center=(1852,36), url='https://auth.indexical.dev/en/signup'
	heading Available Pipelines
```
<details><summary>Show more</summary>

```
	list
		listitem
			[28] heading Simple Scraper, center=(328,176)
			[29] paragraph, center=(328,198), inner_text=Scrape the content of the page
				StaticText Scrape the content of the page
		listitem
			[31] heading Simple Crawler, center=(328,244)
			[32] paragraph, center=(328,266), inner_text=Crawl through the first 2 pages of the website and scrape the main content.
				StaticText Crawl through the first 2 pages of the website and scrape the main content.
		listitem
			[34] heading Product Data Extractor, center=(328,312)
			[35] paragraph, center=(328,334), inner_text=Extract product information from an ecommerce details page.
				StaticText Extract product information from an ecommerce details page.
		listitem
			[37] heading News Article Extractor, center=(328,380)
			[38] paragraph, center=(328,402), inner_text=Extract the main text content from a news article.
				StaticText Extract the main text content from a news article.
	heading Simple Scraper
	paragraph
		StaticText Scrape the content of the page
	LabelText
		StaticText Enter a URL:
	[74] textbox Enter a URL:, center=(1232,240), contenteditable=True, type=text
	[75] button Extract, center=(1840,240)
	heading Pipeline Specification
	StaticText [
  {
    "goal": "extract the following information",
    "action": "extract",
    "schema": {
      "textContent": "$textContent",
      "htmlContentDownloaded": "$download",
      "screenshot": "$screenshot"
    }
  }
]
	contentinfo
		heading Indexical
			[45] link Indexical, center=(360,710), url='https://indexical.dev/'
		paragraph
			StaticText AI-powered web scraping & data extraction engine
		[48] link LinkedIn, center=(329,780), url='https://www.linkedin.com/company/indexical-ai/'
		[52] link Privacy Policy, center=(1397,706), url='https://indexical.dev/privacy'
		[53] link Terms of Service, center=(1397,734), url='https://indexical.dev/terms'
		paragraph
			StaticText Made with ❤️ in San Francisco © 2024 Raio Technologies, Inc.
	alert, atomic
```
</details>



```
RootWebArea Indexical Playground, focused, url='https://playground.indexical.dev/'
	banner
		heading API Playground
		[22] link Sign Up, center=(1852,36), url='https://auth.indexical.dev/en/signup'
	heading Available Pipelines
```
<details><summary>Show more</summary>

```
	list
		listitem
			[28] heading Simple Scraper, center=(328,176)
			[29] paragraph, center=(328,198), inner_text=Scrape the content of the page
				StaticText Scrape the content of the page
		listitem
			[31] heading Simple Crawler, center=(328,244)
			[32] paragraph, center=(328,266), inner_text=Crawl through the first 2 pages of the website and scrape the main content.
				StaticText Crawl through the first 2 pages of the website and scrape the main content.
		listitem
			[34] heading Product Data Extractor, center=(328,312)
			[35] paragraph, center=(328,334), inner_text=Extract product information from an ecommerce details page.
				StaticText Extract product information from an ecommerce details page.
		listitem
			[37] heading News Article Extractor, center=(328,380)
			[38] paragraph, center=(328,402), inner_text=Extract the main text content from a news article.
				StaticText Extract the main text content from a news article.
	heading Simple Scraper
	paragraph
		StaticText Scrape the content of the page
	LabelText
		StaticText Enter a URL:
	[74] textbox Enter a URL: value='https://example.com', center=(1232,240), contenteditable=True, focused, type=text
	[75] button Extract, center=(1840,240)
	heading Pipeline Specification
	StaticText [
  {
    "goal": "extract the following information",
    "action": "extract",
    "schema": {
      "textContent": "$textContent",
      "htmlContentDownloaded": "$download",
      "screenshot": "$screenshot"
    }
  }
]
	contentinfo
		heading Indexical
			[45] link Indexical, center=(360,710), url='https://indexical.dev/'
		paragraph
			StaticText AI-powered web scraping & data extraction engine
		[48] link LinkedIn, center=(329,780), url='https://www.linkedin.com/company/indexical-ai/'
		[52] link Privacy Policy, center=(1397,706), url='https://indexical.dev/privacy'
		[53] link Terms of Service, center=(1397,734), url='https://indexical.dev/terms'
		paragraph
			StaticText Made with ❤️ in San Francisco © 2024 Raio Technologies, Inc.
	alert, atomic
```
</details>

**Reasoning for action:** Entering a sample URL is essential because it provides the Simple Scraper feature with a target page from which it can retrieve data. By filling in the textbox with 'https://example.com', I am preparing to trigger the extraction process by providing valid input, thus moving closer to seeing the scraping results as defined in the user story.

**Action:** fill(74, 'https://example.com') # Fill the URL textbox with a sample URL.

**Change Description:** The URL textbox was filled with the value 'https://example.com', changing its state to have this new content while remaining focused and editable.

**Screenshot before:****Screenshot after:**---


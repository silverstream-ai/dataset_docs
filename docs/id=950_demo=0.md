# Task

**User Story for Early Access Signup**

As a potential user of Turntable services,
I gain access to early features and set up a demo,
so that I can evaluate Turntable's capabilities for my data projects.

**Success definition:** Given I am a user on the Turntable website looking to explore early access features
When I fill in my work email and submit the early access form
Then I should see a confirmation message stating 'You're on the list!' and be prompted to book a demo.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.turntable.so/

https://www.turntable.so/early-access

**Content (before/after):** 

```
RootWebArea Turntable, focused, url='https://www.turntable.so/'
	navigation
		[51] link Turntable, center=(352,34), url='https://www.turntable.so/'
			image
		navigation Main
```
<details><summary>Show more</summary>

```
			list
		[64] link Get early access, center=(1553,34), url='https://www.turntable.so/early-access'
	image
	image
	image
	[87] link Backed by Y Combinator, center=(960,213), url='https://www.ycombinator.com/companies/turntable'
		image
		image
	heading Where humans and AI build data pipelines
	paragraph
		StaticText Turntable is a collaborative workspace to develop, deploy, and monitor data products in half the time
	[98] button Get early access, center=(960,551)
	image
	image
	tabpanel
		image Feature 1 screenshot, url='https://www.turntable.so/_next/image?url=%2Fheader_tt_high_res.png&w=1920&q=100'
	heading TRUSTED BY HUNDREDS OF LEADING DATA TEAMS
	image Grab, url='https://www.turntable.so/grab.svg'
	image Spotify, url='https://www.turntable.so/spotify.svg'
	image Louis Vuitton, url='https://www.turntable.so/lv.svg'
	image The Atlantic, url='https://www.turntable.so/the_atlantic.svg'
	image gopuff, url='https://www.turntable.so/gopuff.svg'
	image Braze, url='https://www.turntable.so/braze.svg'
	image Wayfair, url='https://www.turntable.so/wayfair.svg'
	image Xero, url='https://www.turntable.so/xero_logo.svg'
	image Hubspot, url='https://www.turntable.so/hubspot.svg'
	image Pave, url='https://www.turntable.so/pave_logo.svg'
	heading A powerful data IDE
	heading Purpose built code editor
	paragraph
		StaticText Run queries, document tables, and transform data using dbt Core, SQLMesh, or plain SQL.
	heading Column-level lineage
	paragraph
		StaticText Trace columns from upstream sources, to transforms and downstream dashboards.
	heading Multiplayer projects
	paragraph
		StaticText Work on projects together and get teammates caught up to speed.
	StaticText SELECT 
  users.name, 
  orders.order_date, 
  SUM(order_items.quantity * products.price) AS total_amount
FROM 
  users
  JOIN orders ON users.id = orders.user_id
  JOIN order_items ON orders.id = order_items.order_id
  JOIN products ON order_items.product_id = products.id
WHERE 
  orders.order_date >= '2023-01-01'
GROUP BY 
  users.name, orders.order_date
ORDER BY 
  total_amount DESC
LIMIT 10;
	StaticText Alex
	StaticText Jen
	heading Automated catalog
	paragraph
		StaticText Sync sources, metrics and dashboards with up-to-date metadata and documentation.
	heading Virtual data branches
	paragraph
		StaticText Modify, preview, and deploy transform and BI changes instantly. Avoid data duplication.
	image
	image
	heading Models, metrics, and dashboards in minutes
	paragraph
		StaticText A native AI assistant helps you spend less time managing your DAG, building models, and changing downstream BI tools and reports.
	list
		listitem
			image
			StaticText Context across your data stack
		listitem
			image
			StaticText Auto EDA and profiling
		listitem
			image
			StaticText Auto-generate documentation
		listitem
			image
			StaticText Generate and edit models
		listitem
			image
			StaticText Leverage warehouse design
		listitem
			image
			StaticText Interpret data lineage
	image
	image
	StaticText stg_customers.sql
	StaticText current file
	StaticText x
	image
	StaticText 3
	StaticText models from lineage
	StaticText x
	image
	StaticText Data Profile
	StaticText 56.1k rows
	StaticText x
	image
	StaticText Compiled SQL
	StaticText stg_customers.sql
	StaticText x
	StaticText Generate documentation for this model
	image
	StaticText Claude-3.5-sonnet
	button Submit
		image
	heading Find problems before your stakeholders do
	paragraph
		StaticText Full end-to-end visibility into your data stack. Discover breaking changes and data quality issues in your pipelines and dashboards before they go to production.
	list
		listitem
			image
			StaticText Orchestrate transforms and jobs
		listitem
			image
			StaticText Detect breaking changes
		listitem
			image
			StaticText Set up alerts and monitoring
		listitem
			image
			StaticText Run data diffs across environments
	image dbt, url='https://www.turntable.so/_next/static/media/dbt.f00d6df4.svg'
	image looker, url='https://www.turntable.so/_next/static/media/looker.c44969d0.svg'
	image snowflake, url='https://www.turntable.so/_next/static/media/snowflake.a7deda5d.svg'
	image
	image sheets, url='https://www.turntable.so/_next/static/media/sheets.6bc82f3b.svg'
	image postgres, url='https://www.turntable.so/_next/static/media/postgres.68b66bab.svg'
	image power_bi, url='https://www.turntable.so/_next/static/media/power_bi.94baf198.svg'
	image
	image
	image
	image
	image
	image
	heading Workswithyourdatastack
		StaticText Works
		StaticText with
		StaticText your
		StaticText data
		StaticText stack
	paragraph
		StaticText Setup takes 5 minutes. Turntable supports all the tools you already love and use.
	image Snowflake Logo
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
	heading Getstartedforfree
		StaticText Get
		StaticText started
		StaticText for
		StaticText free
	paragraph
		StaticText 14 day trial. No credit card required.
	button Get early access
	StaticText Product
	link Features, url='https://www.turntable.so/#product'
	link VS Code Extension, url='https://www.turntable.so/extension'
	StaticText Resources
	link Support, url='https://www.turntable.so/support'
	link Terms, url='https://www.turntable.so/terms'
	link Privacy, url='https://www.turntable.so/privacy'
	StaticText Company
	link Contact Us, url='mailto:team@turntable.so'
	link Join the team, url='https://www.ycombinator.com/companies/turntable/jobs'
	link, url='https://join.slack.com/t/turntable-community/shared_invite/zt-25p0olvhz-Z~c5QWq1jv2YFHQ46mMFDA'
		image
	link, url='https://x.com/turntable'
		image
	link, url='https://www.linkedin.com/company/turntabledata/'
		image
	alert, atomic
```
</details>



```
RootWebArea Turntable, focused, url='https://www.turntable.so/early-access'
	navigation
		[51] link Turntable, center=(352,34), url='https://www.turntable.so/'
			image
		navigation Main
```
<details><summary>Show more</summary>

```
			list
		[64] link Get early access, center=(1553,34), focused, url='https://www.turntable.so/early-access'
	alert, atomic
	heading Get early access
	paragraph
		StaticText Setup takes 5 minutes. 14 day free trial. No credit card required.
	LabelText
		StaticText Work email
	[483] textbox Work email, center=(960,325), contenteditable=True
	[484] button Submit, center=(960,381)
```
</details>

**Reasoning for action:** I recognized that to fulfill the user story, I needed to access the early access features provided by Turntable. The element with ID '64' represents the 'Get early access' link, and clicking it would direct me to the relevant page or form. This step is essential because it leads closer to completing the task of submitting my work email and thereby initiating the process to gain early access.

**Action:** click('64') # Click on the 'Get early access' button to explore the early access page.

**Change Description:** The browser navigated to the 'Get early access' page at 'https://www.turntable.so/early-access', where a heading and additional information about the early access program were displayed, along with a textbox for entering a work email and a submit button.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.turntable.so/early-access

https://www.turntable.so/early-access

**Content (before/after):** 

```
RootWebArea Turntable, focused, url='https://www.turntable.so/early-access'
	navigation
		[51] link Turntable, center=(352,34), url='https://www.turntable.so/'
			image
		navigation Main
```
<details><summary>Show more</summary>

```
			list
		[64] link Get early access, center=(1553,34), focused, url='https://www.turntable.so/early-access'
	alert, atomic
	heading Get early access
	paragraph
		StaticText Setup takes 5 minutes. 14 day free trial. No credit card required.
	LabelText
		StaticText Work email
	[483] textbox Work email, center=(960,325), contenteditable=True
	[484] button Submit, center=(960,381)
```
</details>



```
RootWebArea Turntable, focused, url='https://www.turntable.so/early-access'
	navigation
		[51] link Turntable, center=(352,34), url='https://www.turntable.so/'
			image
		navigation Main
```
<details><summary>Show more</summary>

```
			list
		[64] link Get early access, center=(1553,34), url='https://www.turntable.so/early-access'
	alert, atomic
	heading Get early access
	paragraph
		StaticText Setup takes 5 minutes. 14 day free trial. No credit card required.
	LabelText
		StaticText Work email
	[483] textbox Work email value='user@example.com', center=(960,325), contenteditable=True, focused
	[484] button Submit, center=(960,381)
```
</details>

**Reasoning for action:** I reasoned that filling in the work email field is the first step towards submitting the early access form. By entering 'user@example.com' in the textbox (identified by the ID '483'), I am providing the required information to proceed further. This action is aligned with the user's goal of gaining access to Turntable's early features.

**Action:** fill('483', 'user@example.com') # Fill in the work email field with a sample email address.

**Change Description:** The work email textbox now contains the value 'user@example.com' filled in by the agent, while maintaining its focused state.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.turntable.so/early-access

https://www.turntable.so/early-access

**Content (before/after):** 

```
RootWebArea Turntable, focused, url='https://www.turntable.so/early-access'
	navigation
		[51] link Turntable, center=(352,34), url='https://www.turntable.so/'
			image
		navigation Main
```
<details><summary>Show more</summary>

```
			list
		[64] link Get early access, center=(1553,34), url='https://www.turntable.so/early-access'
	alert, atomic
	heading Get early access
	paragraph
		StaticText Setup takes 5 minutes. 14 day free trial. No credit card required.
	LabelText
		StaticText Work email
	[483] textbox Work email value='user@example.com', center=(960,325), contenteditable=True, focused
	[484] button Submit, center=(960,381)
```
</details>



```
RootWebArea Turntable, focused, url='https://www.turntable.so/early-access'
	navigation
		[51] link Turntable, center=(352,34), url='https://www.turntable.so/'
			image
		navigation Main
```
<details><summary>Show more</summary>

```
			list
		[64] link Get early access, center=(1553,34), url='https://www.turntable.so/early-access'
	alert, atomic
	heading Get early access
	heading You're on the list!
	paragraph
		StaticText Want to chat sooner? Book a demo using the Cal embed.
	[a] Iframe Book a call, center=(960,679), title=Book a call
		RootWebArea Turntable Demo | Ian Tracey | Cal.com, url='https://app.cal.com/turntable/demo/embed?embed=&layout=month_view&embedType=inline&ui.color-scheme=dark&date=2025-01-03&month=2025-01'
			image
			main
				list
					listitem
						[a92] link Ian Tracey, center=(477,431), url='https://cal.com/turntable?redirect=false'
							image Ian Tracey, url='https://lh3.googleusercontent.com/a/ACg8ocIe8fXzyAlWF7J53SzU0rQBA0LHygb9g3mLa2ZcGBwD93D2GPU=s96-c'
				paragraph
					StaticText Ian Tracey
				heading Turntable Demo
				StaticText 20m
				image Google Meet icon, url='https://app.cal.com/app-store/googlevideo/logo.webp'
				[a106] paragraph, center=(536,561)
					StaticText Google Meet
				generic
				StaticText Select...
				[a119] combobox Timezone Select, center=(491,597), autocomplete='list', expanded=False, hasPopup='menu'
				strong
					StaticText January
				StaticText 2025
				[a132] button View previous month, center=(1126,425), disabled=True
				[a134] button View next month, center=(1162,425)
				StaticText SUN
				StaticText MON
				StaticText TUE
				StaticText WED
				StaticText THU
				StaticText FRI
				StaticText SAT
				[a152] button 1, center=(960,525), disabled=True
				[a154] button 2, center=(1024,525), disabled=True
				[a156] button 3 today, center=(1087,525)
				[a160] button 4, center=(1150,525), disabled=True
				[a162] button 5, center=(771,588), disabled=True
				[a164] button 6, center=(834,588)
				[a166] button 7, center=(897,588)
				[a168] button 8, center=(960,588)
				[a170] button 9, center=(1024,588)
				[a172] button 10, center=(1087,588)
				[a174] button 11, center=(1150,588), disabled=True
				[a176] button 12, center=(771,651), disabled=True
				[a178] button 13, center=(834,651)
				[a180] button 14, center=(897,651)
				[a182] button 15, center=(960,651)
				[a184] button 16, center=(1024,651)
				[a186] button 17, center=(1087,651)
				[a188] button 18, center=(1150,651), disabled=True
				[a190] button 19, center=(771,715), disabled=True
				[a192] button 20, center=(834,715)
				[a194] button 21, center=(897,715)
				[a196] button 22, center=(960,715)
				[a198] button 23, center=(1024,715)
				[a200] button 24, center=(1087,715)
				[a202] button 25, center=(1150,715), disabled=True
				[a204] button 26, center=(771,778), disabled=True
				[a206] button 27, center=(834,778)
				[a208] button 28, center=(897,778)
				[a210] button 29, center=(960,778)
				[a212] button 30, center=(1024,778)
				[a214] button 31, center=(1087,778)
				StaticText Fri
				StaticText 03
				group
					[a223] radio 12h, center=(1377,425), checked='true'
					[a225] radio 24h, center=(1429,425), checked='false'
				[a232] button 11:00pm, center=(1340,474)
				[a235] button 11:20pm, center=(1340,520)
				[a238] button 11:40pm, center=(1340,566)
				[a242] link Cal.com Logo, center=(960,923), url='https://go.cal.com/booking'
					image Cal.com Logo, url='https://app.cal.com/api/logo'
			alert, atomic
```
</details>

**Reasoning for action:** I identified that the user is currently focused on the 'Submit' button, which is necessary to finalize the early access request. By clicking the 'Submit' button, I send the user's work email to Turntable, advancing the task of gaining access to the early features. This should prompt a confirmation message confirming that the user is on the list and allow them to book a demo, achieving the user's goal.

**Action:** click('484') # Click on the Submit button to submit the early access form.

**Change Description:** After clicking the Submit button, the heading changed to 'You're on the list!' and a new paragraph was added, prompting the user to book a demo. Additionally, an iframe displaying a booking calendar for scheduling a call appeared below.

**Screenshot before:****Screenshot after:**---


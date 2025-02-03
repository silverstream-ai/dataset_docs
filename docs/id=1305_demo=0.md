# Task

**User Journey on the Web**

As a web user,
I navigate between different websites to gather information,
so that I can explore various topics and learn more about example domains and related services.

**Success definition:** Given I am a web user on the homepage of Dealls and looking to explore further
When I attempt to navigate back after encountering a 404 error and then I go to a well-known example website
Then I should successfully reach the Example Domain page and then navigate to the IANA site for more information on example domains.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://dealls.com/

about:blank

**Content (before/after):** 

```
RootWebArea 404, focused, url='https://dealls.com/'
	StaticText 404 Not Found
```


```
RootWebArea, focused, url='about:blank'
```
**Reasoning for action:** My reasoning for taking this action was to navigate back from the current page displaying a '404 Not Found' message on the Dealls website. By using the go_back() function, I am attempting to return to a previous state in the browser where I might have encountered useful information or links that could further my exploration of related topics. This move is essential to recover from the error and find a valid path forward.

**Action:** go_back() # Attempt to navigate back to the previous page.

**Change Description:** The browser navigated back from the '404 Not Found' page of 'https://dealls.com/' to an 'about:blank' page, indicating a transition from a non-existent webpage to a blank state.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

about:blank

http://www.example.com/

**Content (before/after):** 

```
RootWebArea, focused, url='about:blank'
```


```
RootWebArea Example Domain, focused, url='http://www.example.com/'
	heading Example Domain
	paragraph
		StaticText This domain is for use in illustrative examples in documents. You may use this domain in literature without prior coordination or asking for permission.
	paragraph
```
<details><summary>Show more</summary>

```
		[12] link More information..., center=(736,275), url='https://www.iana.org/domains/example'
```
</details>

**Reasoning for action:** I initiated the action to navigate to 'http://www.example.com' because my goal is to reach the Example Domain page as specified in the user story. This step is crucial to proceed with the task of gathering information about example domains and related services. By successfully accessing the Example Domain, I can then plan the next action to navigate towards the IANA site for further information.

**Action:** goto('http://www.example.com') # Navigate to a known website.

**Change Description:** The browser navigated from a blank page to 'http://www.example.com/', displaying the page title 'Example Domain' and adding new elements including a heading and two paragraphs of static text, along with a link to 'More information...'.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

http://www.example.com/

https://www.iana.org/help/example-domains

**Content (before/after):** 

```
RootWebArea Example Domain, focused, url='http://www.example.com/'
	heading Example Domain
	paragraph
		StaticText This domain is for use in illustrative examples in documents. You may use this domain in literature without prior coordination or asking for permission.
	paragraph
```
<details><summary>Show more</summary>

```
		[12] link More information..., center=(736,275), url='https://www.iana.org/domains/example'
```
</details>



```
RootWebArea Example Domains, focused, url='https://www.iana.org/help/example-domains'
	banner
		[14] link Homepage, center=(527,91), url='https://www.iana.org/'
			image Homepage, url='https://www.iana.org/_img/2022/iana-logo-header.svg'
		list
```
<details><summary>Show more</summary>

```
			listitem
				[19] link Domains, center=(1236,52), url='https://www.iana.org/domains'
			listitem
				[21] link Protocols, center=(1321,52), url='https://www.iana.org/protocols'
			listitem
				[23] link Numbers, center=(1408,52), url='https://www.iana.org/numbers'
			listitem
				[25] link About, center=(1482,52), url='https://www.iana.org/about'
	article
		main
			heading Example Domains
			paragraph
				StaticText As described in
				[32] link RFC 2606, center=(562,247), url='https://www.iana.org/go/rfc2606'
				StaticText and
				[33] link RFC 6761, center=(666,247), url='https://www.iana.org/go/rfc6761'
				StaticText , a number of domains such as example.com and example.org are maintained for documentation purposes. These domains may be used as illustrative examples in documents without prior coordination with us. They are not available for registration or transfer.
			paragraph
				StaticText We provide a web service on the example domain hosts to provide basic information on the purpose of the domain. These web services are provided as best effort, but are not designed to support production applications. While incidental traffic for incorrectly configured applications is expected, please do not design applications that require the example domains to have operating HTTP service.
			heading Further Reading
			list
				listitem
					ListMarker ■
					[38] link IANA-managed Reserved Domains, center=(571,471), url='https://www.iana.org/domains/reserved'
			StaticText Last revised 2017-05-13.
		navigation
	contentinfo
		LayoutTable
			LayoutTableRow
				LayoutTableCell Domain Names
					[47] link Domain Names, center=(458,619), url='https://www.iana.org/domains'
				LayoutTableCell Root Zone Registry .INT Registry .ARPA Registry IDN Repository
					list
						listitem
							[51] link Root Zone Registry, center=(602,619), url='https://www.iana.org/domains/root'
						listitem
							[53] link .INT Registry, center=(704,619), url='https://www.iana.org/domains/int'
						listitem
							[55] link .ARPA Registry, center=(792,619), url='https://www.iana.org/domains/arpa'
						listitem
							[57] link IDN Repository, center=(888,619), url='https://www.iana.org/domains/idn-tables'
			LayoutTableRow
				LayoutTableCell Number Resources
					[60] link Number Resources, center=(471,646), url='https://www.iana.org/numbers'
				LayoutTableCell Abuse Information
					list
						listitem
							[64] link Abuse Information, center=(601,646), url='https://www.iana.org/abuse'
			LayoutTableRow
				LayoutTableCell Protocols
					[67] link Protocols, center=(442,673), url='https://www.iana.org/protocols'
				LayoutTableCell Protocol Registries Time Zone Database
					list
						listitem
							[71] link Protocol Registries, center=(602,673), url='https://www.iana.org/protocols'
						listitem
							[73] link Time Zone Database, center=(728,673), url='https://www.iana.org/time-zones'
			LayoutTableRow
				LayoutTableCell About Us
					[76] link About Us, center=(439,700), url='https://www.iana.org/about'
				LayoutTableCell Performance Reports Reviews Excellence Contact Us
					list
						listitem
							[80] link Performance, center=(584,700), url='https://www.iana.org/performance'
						listitem
							[82] link Reports, center=(654,700), url='https://www.iana.org/reports'
						listitem
							[84] link Reviews, center=(710,700), url='https://www.iana.org/reviews'
						listitem
							[86] link Excellence, center=(772,700), url='https://www.iana.org/about/excellence'
						listitem
							[88] link Contact Us, center=(842,700), url='https://www.iana.org/contact'
		paragraph
			StaticText The IANA functions coordinate the Internet’s globally unique identifiers, and are provided by
			[91] link Public Technical Identifiers, center=(1031,746), url='http://pti.icann.org/'
			StaticText , an affiliate of
			[92] link ICANN, center=(1224,746), url='http://www.icann.org/'
			StaticText .
		list
			listitem
				[96] link Privacy Policy, center=(454,788), url='https://www.icann.org/privacy/policy'
			listitem
				[98] link Terms of Service, center=(562,788), url='https://www.icann.org/privacy/tos'
```
</details>

**Reasoning for action:** I chose to click on the 'More information...' link because it is a crucial step in my exploration of example domains. By doing this, I will be redirected to the IANA site, which is a reputable source for further details on example domains. This action directly contributes to achieving my goal of gathering more information about the topic.

**Action:** click('12') # Click on the 'More information...' link to access further details.

**Change Description:** After clicking the 'More information...' link, the browser navigated from the example domain page to the IANA site, updating the URL to 'https://www.iana.org/help/example-domains' and displaying new content including headings, paragraphs, and various links related to example domains and IANA services.

**Screenshot before:****Screenshot after:**---


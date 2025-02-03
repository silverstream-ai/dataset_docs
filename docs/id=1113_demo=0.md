# Task

**User Navigation Flow to Find Information**

As a A curious internet user,
I navigate to relevant content to learn more about example domains,
so that I can understand the purpose of example domains and their applications.

**Success definition:** Given I am on the OpenSight homepage and encounter a 404 error
When I navigate to 'httpwww.example.com' and click 'More information...'
Then I should see detailed information about example domains on the IANA website

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.opensight.ai/

about:blank

**Content (before/after):** 

```
RootWebArea 404 - Page not found, focused, url='https://www.opensight.ai/'
	StaticText 404
	heading Page not found
	paragraph
		StaticText The page you are looking for doesn't exist or has been moved.
```


```
RootWebArea, focused, url='about:blank'
```
**Reasoning for action:** I encountered a 404 error on the OpenSight homepage, which means I couldn't access any useful content on that page. By using the go_back() function, I can return to the previous state before the error, giving me a chance to attempt a different navigation approach or possibly access functional links that might provide information about example domains.

**Action:** go_back() # Navigate back to the previous page in history.

**Change Description:** The browser navigated back to the previous page, resulting in a change from a '404 - Page not found' error page to a blank page (about:blank), effectively clearing the previous error message from the view.

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

**Reasoning for action:** I concluded that navigating to 'http://www.example.com' is essential because this site is specifically designated for example domains. By doing so, I am attempting to gather relevant information on the topic. This action directly progresses towards the user story of learning about example domains and their applications.

**Action:** goto('http://www.example.com') # Navigate to a specific homepage to find relevant content.

**Change Description:** The browser navigated from an empty page ('about:blank') to the 'http://www.example.com/' homepage, which now displays the 'Example Domain' heading and a paragraph of static text explaining the domain's purpose, along with a link to 'More information...' located at the specified coordinates.

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

**Reasoning for action:** I clicked on the 'More information...' link to access further details about example domains. This action is crucial because it directly aligns with the user story's goal of learning more about the purpose and applications of example domains. By navigating to the IANA website through this link, I will obtain comprehensive information, fulfilling the success criteria outlined in the task.

**Action:** click('12') # Click on the 'More information...' link to gather more details about the example domain.

**Change Description:** The browser navigated from the Example Domain page to the IANA Example Domains page, changing the URL from 'http://www.example.com/' to 'https://www.iana.org/help/example-domains', and the content displayed now includes new headings, paragraphs, and lists providing detailed information about example domains and their use.

**Screenshot before:****Screenshot after:**---


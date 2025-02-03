# Task

**User Navigation to Learn About Example Domains**

As an internet user,
I explore example domains for learning purposes,
so that I can understand more about how example domains function and their intended use.

**Success definition:** Given The user is on the TryLevel app
When the user navigates back from a non-existing page, then goes to the example domain and clicks on the additional information link
Then the user should be redirected to a page that provides details about example domains.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://trylevel.webflow.io/

about:blank

**Content (before/after):** 

```
RootWebArea 404 - Page not found, focused, url='https://trylevel.webflow.io/'
	StaticText 404
	heading Page not found
	paragraph
		StaticText The page you are looking for doesn't exist or has been moved.
```


```
RootWebArea, focused, url='about:blank'
```
**Reasoning for action:** I decided to perform the action of going back because the current state of the browser indicates that the user is on a 404 'Page not found' screen. This page does not provide any useful information for the user. By navigating back, I can return to the last functional page of the TryLevel app, which is necessary for the user to proceed to the example domain and follow the next steps for gathering information.

**Action:** go_back() # Navigate back to the previous page.

**Change Description:** The browser navigated back from the '404 - Page not found' error page to an empty 'about:blank' page, resulting in the loss of the previous content and a focus shift from the error message to a blank state.

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

**Reasoning for action:** I chose to navigate to 'http://www.example.com' because this URL is specifically designed as an example domain, which aligns directly with the user's goal of exploring example domains for learning. By accessing this page, I can gather information about its purpose and functionality, which will further the user's understanding of example domains.

**Action:** goto('http://www.example.com') # Navigate to a homepage or a specific URL.

**Change Description:** The browser navigated from an empty state to displaying the 'Example Domain' webpage at 'http://www.example.com/', where a heading and a descriptive paragraph about the domain are now focused, along with a link for more information.

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

**Reasoning for action:** I identified the link labeled 'More information...' as a means to access further details regarding example domains. By clicking this link, I am fulfilling the user's intent to learn more about how example domains function and their intended use. This action directly aligns with the success criteria by redirecting the user to the specific page desired.

**Action:** click(12) # Click on the 'More information...' link to learn more about the example domain.

**Change Description:** After clicking the 'More information...' link, the browser navigated from 'http://www.example.com/' to 'https://www.iana.org/help/example-domains', displaying a new page with updated content, including headings, paragraphs, and various links related to example domains.

**Screenshot before:****Screenshot after:**---


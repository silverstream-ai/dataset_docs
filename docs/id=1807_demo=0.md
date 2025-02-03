# Task

**Navigating Information About Example Domains**

As a user interested in learning about example domains,
I navigate from a broken link to informative resources,
so that I can understand the purpose and usage of example domains.

**Success definition:** Given I am on a webpage that shows a 404 error
When I decide to go to the homepage of Example Domain
Then I should see the content of the Example Domain homepage displayed with headings and paragraphs explaining example domains, along with a link for more information.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.veranohealth.org/

about:blank

**Content (before/after):** 

```
RootWebArea 404 - Page not found, focused, url='https://www.veranohealth.org/'
	StaticText 404
	heading Page not found
	paragraph
		StaticText The page you are looking for doesn't exist or has been moved.
```


```
RootWebArea, focused, url='about:blank'
```
**Reasoning for action:** The webpage I am currently on shows a 404 error, indicating that the desired content is unavailable. To progress towards the user story goal of accessing informative resources about example domains, going back will allow me to return to an earlier state in the browsing session, ideally to a page where I can find a link to the Example Domain homepage. This is a crucial step to ensure I can reach content that meets the user's needs.

**Action:** go_back() # Navigate back to the previous page in history.

**Change Description:** The browser navigated back to a previous page, resulting in a change from a '404 - Page not found' error page to a blank page ('about:blank'), with the focus shifting away from the error message.

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

**Reasoning for action:** Since the user is currently on a webpage that is causing a 404 error, my immediate goal is to redirect them to a relevant resource. The action of navigating to the home page of Example Domain allows the user to access informative content about example domains. This homepage is the next logical step to achieve the user's intent to learn more, as it is specifically designed to provide users with relevant information and examples.

**Action:** goto('http://www.example.com') # Navigate to the homepage of the website.

**Change Description:** The browser navigated from a blank page to 'http://www.example.com/', changing the URL and displaying the content of the Example Domain homepage, which includes a heading and two paragraphs with static text, along with a link to more information.

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

**Reasoning for action:** My reasoning for this action is based on the user's need to learn more about example domains. By clicking the 'More information...' link, I will be directed to a page that likely contains comprehensive resources and explanations about example domains. This directly supports the user story by ensuring that I have access to informative content, thus fulfilling the user's request for understanding.

**Action:** click(12) # Click on the 'More information...' link to learn more about the example domain.

**Change Description:** The browser navigated from the 'Example Domain' page to the 'Example Domains' page on a different site, updating the URL to 'https://www.iana.org/help/example-domains'. The content displayed significant new information including headings, paragraphs, and multiple links regarding the IANA-managed example domains, whereas the previous page contained only a brief overview of the example domain.

**Screenshot before:****Screenshot after:**---


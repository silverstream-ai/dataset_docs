# Task

**Explore IANA Managed Domains**

As a website explorer,
I understand the concept of IANA-managed domains,
so that I can gain insights into how different domains are reserved and managed.

**Success definition:** Given I am on the 'Example Domain' page
When I click on the 'More information...' link and subsequently on 'IANA-managed Reserved Domains'
Then I should be taken to the 'IANA-managed Reserved Domains' page and see detailed information and policies regarding reserved domains.

## Trajectory

**Step 1:**

**Url (before/after):** 

about:blank

https://www.example.com/

**Content (before/after):** 

```
RootWebArea, focused, url='about:blank'
```


```
RootWebArea Example Domain, focused, url='https://www.example.com/'
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

**Reasoning for action:** In order to complete the task of understanding IANA-managed domains, I must first access the correct webpage that contains the relevant links, specifically the 'More information...' link. Navigating to 'https://www.example.com' allows me to begin my exploration on the 'Example Domain' page, which is the starting point for finding the information about IANA-managed Reserved Domains.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its elements.

**Change Description:** The browser navigated from an empty state (about:blank) to displaying the 'Example Domain' webpage, which now includes a heading and static text explaining the purpose of the domain, as well as a link for more information.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.example.com/

https://www.iana.org/help/example-domains

**Content (before/after):** 

```
RootWebArea Example Domain, focused, url='https://www.example.com/'
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

**Reasoning for action:** By clicking on the 'More information...' link, I am following the specified user story to gather additional information about IANA-managed domains. This link leads to the IANA website's page on 'Example Domain', which is crucial for fulfilling the task of understanding how domains are reserved and managed. Therefore, this action brings me closer to the goal of gaining insights into the topic.

**Action:** click('12') # Click on the 'More information...' link to explore further details.

**Change Description:** The browser navigated from the 'Example Domain' page to the 'Example Domains' page on the IANA website, changing the URL from 'https://www.example.com/' to 'https://www.iana.org/help/example-domains'. The content displayed now includes new headings, paragraphs, and links related to IANA-managed domains, replacing the previous static text and information.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.iana.org/help/example-domains

https://www.iana.org/domains/reserved

**Content (before/after):** 

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



```
RootWebArea IANA-managed Reserved Domains, focused, url='https://www.iana.org/domains/reserved'
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
			heading IANA-managed Reserved Domains
			paragraph
				StaticText Certain domains are set aside, and nominally registered to “IANA”, for specific policy or technical purposes.
			heading Example domains
			paragraph
				StaticText As described in
				[33] link RFC 2606, center=(812,345), url='https://www.iana.org/go/rfc2606'
				StaticText and
				[34] link RFC 6761, center=(916,345), url='https://www.iana.org/go/rfc6761'
				StaticText , a number of domains such as
				StaticText example.com
				StaticText and
				StaticText example.org
				StaticText are maintained for documentation purposes. These domains may be used as illustrative examples in documents without prior coordination with us. They are not available for registration or transfer.
			heading Test IDN top-level domains
			paragraph
				StaticText These domains were temporarily delegated by IANA for the
				[39] link IDN Evaluation, center=(1170,488), url='http://www.icann.org/topics/idn/'
				StaticText being conducted by
				[40] link ICANN, center=(1406,488), url='http://www.icann.org/'
				StaticText .
			table
				rowgroup
					row
						columnheader DOMAIN
						columnheader DOMAIN (A-LABEL)
						columnheader LANGUAGE
						columnheader SCRIPT
				rowgroup
					row
						[51] cell إختبار, center=(726,558)
						cell XN--KGBECHTV
							[54] link XN--KGBECHTV, center=(855,560), url='https://www.iana.org/domains/root/db/xn--kgbechtv.html'
						[55] cell Arabic, center=(1141,558)
						[56] cell Arabic, center=(1381,558)
					row
						[58] cell آزمایشی, center=(726,592)
						cell XN--HGBK6AJ7F53BBA
							[61] link XN--HGBK6AJ7F53BBA, center=(885,594), url='https://www.iana.org/domains/root/db/xn--hgbk6aj7f53bba.html'
						[62] cell Persian, center=(1141,592)
						[63] cell Arabic, center=(1381,592)
					row
						[65] cell 测试, center=(726,626)
						cell XN--0ZWM56D
							[68] link XN--0ZWM56D, center=(850,628), url='https://www.iana.org/domains/root/db/xn--0zwm56d.html'
						[69] cell Chinese, center=(1141,626)
						[70] cell Han (Simplified variant), center=(1381,626)
					row
						[72] cell 測試, center=(726,661)
						cell XN--G6W251D
							[75] link XN--G6W251D, center=(850,663), url='https://www.iana.org/domains/root/db/xn--g6w251d.html'
						[76] cell Chinese, center=(1141,661)
						[77] cell Han (Traditional variant), center=(1381,661)
					row
						[79] cell испытание, center=(726,696)
						cell XN--80AKHBYKNJ4F
							[82] link XN--80AKHBYKNJ4F, center=(875,698), url='https://www.iana.org/domains/root/db/xn--80akhbyknj4f.html'
						[83] cell Russian, center=(1141,696)
						[84] cell Cyrillic, center=(1381,696)
					row
						[86] cell परीक्षा, center=(726,730)
						cell XN--11B5BS3A9AJ6G
							[89] link XN--11B5BS3A9AJ6G, center=(880,732), url='https://www.iana.org/domains/root/db/xn--11b5bs3a9aj6g.html'
						[90] cell Hindi, center=(1141,730)
						[91] cell Devanagari (Nagari), center=(1381,730)
					row
						[93] cell δοκιμή, center=(726,764)
						cell XN--JXALPDLP
							[96] link XN--JXALPDLP, center=(855,766), url='https://www.iana.org/domains/root/db/xn--jxalpdlp.html'
						[97] cell Greek, Modern (1453-), center=(1141,764)
						[98] cell Greek, center=(1381,764)
					row
						[100] cell 테스트, center=(726,798)
						cell XN--9T4B11YI5A
							[103] link XN--9T4B11YI5A, center=(865,800), url='https://www.iana.org/domains/root/db/xn--9t4b11yi5a.html'
						[104] cell Korean, center=(1141,798)
						[105] cell Hangul (Hangŭl, Hangeul), center=(1381,798)
					row
						[107] cell טעסט, center=(726,833)
						cell XN--DEBA0AD
							[110] link XN--DEBA0AD, center=(850,835), url='https://www.iana.org/domains/root/db/xn--deba0ad.html'
						[111] cell Yiddish, center=(1141,833)
						[112] cell Hebrew, center=(1381,833)
					row
						[114] cell テスト, center=(726,867)
						cell XN--ZCKZAH
							[117] link XN--ZCKZAH, center=(845,869), url='https://www.iana.org/domains/root/db/xn--zckzah.html'
						[118] cell Japanese, center=(1141,867)
						[119] cell Katakana, center=(1381,867)
					row
						[121] cell பரிட்சை, center=(726,902)
						cell XN--HLCJ6AYA9ESC7A
							[124] link XN--HLCJ6AYA9ESC7A, center=(885,904), url='https://www.iana.org/domains/root/db/xn--hlcj6aya9esc7a.html'
						[125] cell Tamil, center=(1141,902)
						[126] cell Tamil, center=(1381,902)
			heading Policy-reserved domains
			paragraph
				StaticText We act as both the registrant and registrar for a select number of domains which have been reserved under policy grounds. These exclusions are typically indicated in either technical standards (RFC documents), or
				[129] link contractual limitations, center=(746,1051), url='http://www.icann.org/en/registries/agreements.htm'
				StaticText .
			paragraph
				StaticText Domains which are described as registered to IANA or ICANN on policy grounds are not available for registration or transfer, with the exception of
				StaticText country-name
				StaticText .info
				StaticText domains. These domains are available for release by the ICANN Governmental Advisory Committee Secretariat.
			heading Other Special-Use Domains
			paragraph
				StaticText There is additionally a
				link Special-Use Domain Names, url='https://www.iana.org/assignments/special-use-domain-names'
				StaticText registry documenting special-use domains designated by technical standards. For further information, see
				link Special-Use Domain Names, url='https://www.iana.org/go/rfc6761'
				StaticText (RFC 6761).
		navigation
			heading Domain Names
			list
				listitem
					[142] link Overview, center=(450,279), url='https://www.iana.org/domains'
				listitem
					[144] link Root Zone Management, center=(494,301), url='https://www.iana.org/domains/root'
				listitem
					[159] link .INT Registry, center=(460,323), url='https://www.iana.org/domains/int'
				listitem
					[168] link .ARPA Registry, center=(465,345), url='https://www.iana.org/domains/arpa'
				listitem
					[170] link IDN Practices Repository, center=(496,367), url='https://www.iana.org/domains/idn-tables'
				listitem
					[177] link Root Key Signing Key (DNSSEC), center=(516,389), url='https://www.iana.org/dnssec'
				listitem
					[192] link Reserved Domains, center=(484,411), url='https://www.iana.org/domains/reserved'
	contentinfo
		LayoutTable
			LayoutTableRow
				LayoutTableCell Domain Names
					link Domain Names, url='https://www.iana.org/domains'
				LayoutTableCell Root Zone Registry .INT Registry .ARPA Registry IDN Repository
					list
						listitem
							link Root Zone Registry, url='https://www.iana.org/domains/root'
						listitem
							link .INT Registry, url='https://www.iana.org/domains/int'
						listitem
							link .ARPA Registry, url='https://www.iana.org/domains/arpa'
						listitem
							link IDN Repository, url='https://www.iana.org/domains/idn-tables'
			LayoutTableRow
				LayoutTableCell Number Resources
					link Number Resources, url='https://www.iana.org/numbers'
				LayoutTableCell Abuse Information
					list
						listitem
							link Abuse Information, url='https://www.iana.org/abuse'
			LayoutTableRow
				LayoutTableCell Protocols
					link Protocols, url='https://www.iana.org/protocols'
				LayoutTableCell Protocol Registries Time Zone Database
					list
						listitem
							link Protocol Registries, url='https://www.iana.org/protocols'
						listitem
							link Time Zone Database, url='https://www.iana.org/time-zones'
			LayoutTableRow
				LayoutTableCell About Us
					link About Us, url='https://www.iana.org/about'
				LayoutTableCell Performance Reports Reviews Excellence Contact Us
					list
						listitem
							link Performance, url='https://www.iana.org/performance'
						listitem
							link Reports, url='https://www.iana.org/reports'
						listitem
							link Reviews, url='https://www.iana.org/reviews'
						listitem
							link Excellence, url='https://www.iana.org/about/excellence'
						listitem
							link Contact Us, url='https://www.iana.org/contact'
		paragraph
			StaticText The IANA functions coordinate the Internet’s globally unique identifiers, and are provided by
			link Public Technical Identifiers, url='http://pti.icann.org/'
			StaticText , an affiliate of
			link ICANN, url='http://www.icann.org/'
			StaticText .
		list
			listitem
				link Privacy Policy, url='https://www.icann.org/privacy/policy'
			listitem
				link Terms of Service, url='https://www.icann.org/privacy/tos'
```
</details>

**Reasoning for action:** Before taking the action to click on the link, I checked the current webpage structure and confirmed that the link labeled 'IANA-managed Reserved Domains' (identified by the action index '38') is present in the 'Further Reading' section. This link is crucial for fulfilling the user's task of gaining insights into IANA-managed domains. By clicking on it, I will be directed to the page containing the detailed information that the user is seeking, thereby advancing towards the successful completion of the user story.

**Action:** click('38') # Click on the 'IANA-managed Reserved Domains' link to explore more details.

**Change Description:** The browser navigated to the 'IANA-managed Reserved Domains' page, updating the title and URL to 'https://www.iana.org/domains/reserved'. The content now includes headings and paragraphs detailing reserved domains, including examples and related policies, replacing the previous content about example domains.

**Screenshot before:****Screenshot after:**---


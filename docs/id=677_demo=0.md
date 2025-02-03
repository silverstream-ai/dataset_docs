# Task

**Job Application Process for Founding Engineer**

As a job seeker,
I explore job opportunities at Sweep AI,
so that I can apply for the Founding Engineer role and advance my career.

**Success definition:** Given I am on the Sweep AI About Us page and interested in job opportunities
When I click on the Open Positions button and then proceed to apply for the Founding Engineer position
Then I should see an application modal prompting me to input my personal information and upload my resume.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://sweep.dev/

https://sweep.dev/about-us

**Content (before/after):** 

```
RootWebArea Sweep: turn bugs and feature requests into code changes., focused, url='https://sweep.dev/'
	navigation
		[40] link logo Sweep AI, center=(440,40), inner_text=Sweep AI, url='https://sweep.dev/'
			image logo, url='https://sweep.dev/static/media/icon.0e4801c4058ae7cceb14.png'
		[43] link About Us, center=(791,40), url='https://sweep.dev/about-us'
```
<details><summary>Show more</summary>

```
		[44] link Blogs, center=(912,40), url='https://docs.sweep.dev/blogs'
		[45] link Security, center=(1027,40), url='https://docs.sweep.dev/blogs/soc2'
		[46] link Pricing, center=(1148,40), url='https://sweep.dev/pricing'
		[47] button Contact Sales, center=(1290,40), type=button
	heading Self-hosted coding assistant for JetBrains IDEs
	paragraph
		StaticText Accelerate your JetBrains developers with the latest in AI coding intelligence. No data ever leaves your VPC.
	[58] button Contact Sales, center=(630,483), type=button
	[59] button Get Started, center=(946,483), type=button
	paragraph
		StaticText Trusted by organizations including
	image Fundrise, url='https://sweep.dev/static/media/fundrise.f8216a75f9288447e6b39d7ddbe497d8.svg'
	image Company logo, url='data:image/png;base64,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'
	image Company logo, url='https://sweep.dev/static/media/hearth.edc2a79b46fa0456602c7b8326deb5d2.svg'
	image Company logo, url='https://sweep.dev/static/media/gradio.88403e69c46c357808187c8abb4528ed.svg'
	image LlamaIndex, url='https://sweep.dev/static/media/llamaindex.633d9bdd411fb5011e2b.png'
	image Sweep logo, url='https://sweep.dev/static/media/icon.0e4801c4058ae7cceb14.png'
	paragraph
		StaticText The latest AI features in the IDEs that you love
	paragraph
		StaticText Sweep brings the latest innovations in AI coding into JetBrains IDEs like IntelliJ, PyCharm, and more.
	paragraph
		StaticText ⚡
	paragraph
		StaticText Save hours writing the same code over and over
	paragraph
		StaticText Sweep understands your entire codebase to automate simple tasks like writing tests, fixing bugs, and more.
	paragraph
		StaticText 🚀
	paragraph
		StaticText Onboard new developers faster
	paragraph
		StaticText Sweep helps new hires quickly get up to speed with any codebase.
	paragraph
		StaticText Develop at ease, with Sweep
	button Get Started
	contentinfo
		link Privacy, url='https://sweep.dev/privacy.pdf'
		link Terms of Use, url='https://sweep.dev/tos.pdf'
		link Backed by Y Combinator, url='https://techcrunch.com/2023/11/02/sweep-aims-to-automate-basic-dev-tasks-using-large-language-models/'
			image Y Combinator, url='https://sweep.dev/static/media/yc.d98f8ddf8a0866173865.webp'
		paragraph
			StaticText ©
			StaticText 2025
			strong
				StaticText Sweep AI, Inc.
			StaticText All rights reserved.
	region
	region
	region
	region
	region
	region
	[118] button Open Intercom Messenger, center=(1876,1036)
		image
		image
```
</details>



```
RootWebArea Sweep: turn bugs and feature requests into code changes., focused, url='https://sweep.dev/about-us'
	navigation
		[40] link logo Sweep AI, center=(440,40), inner_text=Sweep AI, url='https://sweep.dev/'
			image logo, url='https://sweep.dev/static/media/icon.0e4801c4058ae7cceb14.png'
		[43] link About Us, center=(791,40), focused, url='https://sweep.dev/about-us'
```
<details><summary>Show more</summary>

```
		[44] link Blogs, center=(912,40), url='https://docs.sweep.dev/blogs'
		[45] link Security, center=(1027,40), url='https://docs.sweep.dev/blogs/soc2'
		[46] link Pricing, center=(1148,40), url='https://sweep.dev/pricing'
		[47] button Contact Sales, center=(1290,40), type=button
	paragraph
		StaticText Join the Team
	paragraph
		StaticText We're a YC-backed startup building the future of AI-powered development tools. Our team brings experience from Roblox, CMU, and cutting-edge ML research.
	[127] button Open Positions, center=(960,362), type=button
	paragraph
		StaticText Founders
	image William Zeng, url='https://sweep.dev/wz_pfp.png'
	paragraph
		StaticText William Zeng
	paragraph
		StaticText Previously led Search ML at Roblox as the youngest senior MLE, where he built vector search and ranking models serving 70M+ DAU.
	image Kevin Lu, url='https://sweep.dev/KEVIN.jpeg'
	paragraph
		StaticText Kevin Lu
	paragraph
		StaticText Previously worked on Avatar ML at Roblox, including the first ML-based skin weight generation model for UGC avatars.
	contentinfo
		[100] link Privacy, center=(662,1050), url='https://sweep.dev/privacy.pdf'
		[101] link Terms of Use, center=(742,1050), url='https://sweep.dev/tos.pdf'
		[102] link Backed by Y Combinator, center=(901,1050), inner_text=Backed by, url='https://techcrunch.com/2023/11/02/sweep-aims-to-automate-basic-dev-tasks-using-large-language-models/'
			image Y Combinator, url='https://sweep.dev/static/media/yc.d98f8ddf8a0866173865.webp'
		paragraph
			StaticText ©
			StaticText 2025
			strong
				StaticText Sweep AI, Inc.
			StaticText All rights reserved.
	region
	region
	region
	region
	region
	region
	generic
		[b] dialog Intercom live chat, center=(1876,1036), modal=False, title=Intercom live chat
```
</details>

**Reasoning for action:** Since the user is on the Sweep AI homepage and interested in exploring job opportunities, I first need to locate the About Us page to gather more information about the company and its culture. Clicking on the About Us link allows me to access the relevant content that may provide insights into job opportunities and the specifics of the company—the next step toward applying for the Founding Engineer role.

**Action:** click(43) # Click on the About Us link to explore more about the company.

**Change Description:** The browser navigated to the 'About Us' page of Sweep AI, updating the URL to 'https://sweep.dev/about-us', and displaying new content about the company, including information about its team and positions available, while the header links remain accessible with 'About Us' now focused.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://sweep.dev/about-us

https://www.ycombinator.com/companies/sweep/jobs/8dUn406-founding-engineer

**Content (before/after):** 

```
RootWebArea Sweep: turn bugs and feature requests into code changes., focused, url='https://sweep.dev/about-us'
	navigation
		[40] link logo Sweep AI, center=(440,40), inner_text=Sweep AI, url='https://sweep.dev/'
			image logo, url='https://sweep.dev/static/media/icon.0e4801c4058ae7cceb14.png'
		[43] link About Us, center=(791,40), focused, url='https://sweep.dev/about-us'
```
<details><summary>Show more</summary>

```
		[44] link Blogs, center=(912,40), url='https://docs.sweep.dev/blogs'
		[45] link Security, center=(1027,40), url='https://docs.sweep.dev/blogs/soc2'
		[46] link Pricing, center=(1148,40), url='https://sweep.dev/pricing'
		[47] button Contact Sales, center=(1290,40), type=button
	paragraph
		StaticText Join the Team
	paragraph
		StaticText We're a YC-backed startup building the future of AI-powered development tools. Our team brings experience from Roblox, CMU, and cutting-edge ML research.
	[127] button Open Positions, center=(960,362), type=button
	paragraph
		StaticText Founders
	image William Zeng, url='https://sweep.dev/wz_pfp.png'
	paragraph
		StaticText William Zeng
	paragraph
		StaticText Previously led Search ML at Roblox as the youngest senior MLE, where he built vector search and ranking models serving 70M+ DAU.
	image Kevin Lu, url='https://sweep.dev/KEVIN.jpeg'
	paragraph
		StaticText Kevin Lu
	paragraph
		StaticText Previously worked on Avatar ML at Roblox, including the first ML-based skin weight generation model for UGC avatars.
	contentinfo
		[100] link Privacy, center=(662,1050), url='https://sweep.dev/privacy.pdf'
		[101] link Terms of Use, center=(742,1050), url='https://sweep.dev/tos.pdf'
		[102] link Backed by Y Combinator, center=(901,1050), inner_text=Backed by, url='https://techcrunch.com/2023/11/02/sweep-aims-to-automate-basic-dev-tasks-using-large-language-models/'
			image Y Combinator, url='https://sweep.dev/static/media/yc.d98f8ddf8a0866173865.webp'
		paragraph
			StaticText ©
			StaticText 2025
			strong
				StaticText Sweep AI, Inc.
			StaticText All rights reserved.
	region
	region
	region
	region
	region
	region
	generic
		[b] dialog Intercom live chat, center=(1876,1036), modal=False, title=Intercom live chat
```
</details>



```
RootWebArea Founding Engineer at Sweep | Y Combinator, focused, url='https://www.ycombinator.com/companies/sweep/jobs/8dUn406-founding-engineer'
	banner
		navigation
			[306] link Y Combinator, center=(438,48), title=Y Combinator, url='https://www.ycombinator.com/'
				image Y Combinator, url='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAQEAAAEBCAMAAABPMuDPAAAAQlBMVEXyZSLyZSLyZSLyZSLyZSL6roH91br2ilD+6tr4nGn0eDf7wp3+9e3zbyz3k1z0gUP7uI/5pXX+38n8y6z////yZSKuMvVfAAAABXRSTlOAQMBgICelMzEAAAOgSURBVHhe5MABDQAAAIIw3eifmSB8vA3Zt5vcuGEgCsLeUBSpnxnb4f2vmn068xK5Z8FuFQ8gCB9q80Dw42Pc+3y8UQABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQACBR7GnuAF6MafNKnDsv+xx/+1mv3nOKjDKXwRWbwIWYJl4F6wigvclUCcWaCKCeRKwAtNFoBN4TC1wigjelMA2+S5YRATv+VyfXKC+NYIqEphVQEfgT2Dv0ws8VAT+BEqAXbCJCPwJHAEEuorAn0AAARGBO4H1CCFw7O+JoArIuQVGERH4EhgBBFQE/gQmF9ARnP4EljG5gB5Iiz+BGkBAreTqTyCAgIzAnUAogdMbwSIm0cQCeiAtvgR6MIEqInAkEEBARuBKIJzAwxOB5SsBb822n0dQxSoOJNBFBI4EAgmMp4jAkUAAATWQ6s8SaEFvz8vPIqhiWAYQcEQgEogqMD5FBBcS+BrBBPRAqtcTqIEF2vUIqsgmgIAjApFAaIF6NQKbwPcIKKAHUr2WQI8k4I+gilUcQMARgUggvEC/EkEzAM8E7wu2CxGsdhJFEvBH0MQqDiegV3J1JBBQ4NhFBDqBzyTvC4qIQCawjgwCOgKdQIstoFdydSQQRcD2rSNoVimRQPuPCFaLFF1AR7A5EggloK/BdAIZBPRVqE6ghxLwR7BaoBQCOgKdQDqBLiIQCSQSGJuIoNlJlEVAR3C8TKCkfHX7fLn+T5tASoFjf9X6YmlSCozyYvxVO4kSCegI1r8n0FIJ6IF0igQyCej9txiWZAI6gsfoViWxwPiy+2gzqzi1QLUR2ATSCeiBtBuSfAI6AjsWkguM738I9PQC3ZFADoGxKYC95xfQEZRxA4FRRALHLQSOXSSQXkBHsB75BXQEbWQV0APJruL8AmMVCaQW0BEsI5uAXsn21FsJVJFAZgH9juJmAsVOorsLlLsJIIAAAggggAACCCCAAAIIIIAAAggggAACCCCAAAIIIIAAAggggAACCCCAAAIIIIAAAggggAACCCCAAAIIIIAAAm3547QAAoGPFkAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBH6XAwc0AAAAAME2+ncWxOXNAI6Cs14i3Db7AAAAAElFTkSuQmCC'
```
<details><summary>Show more</summary>

```
			[310] link About, center=(514,48), url='https://www.ycombinator.com/about'
			[321] link Companies, center=(594,48), url='https://www.ycombinator.com/companies'
			[329] link Startup Jobs, center=(696,48), url='https://www.ycombinator.com/jobs'
			[343] link Find a Co-Founder, center=(824,48), url='https://www.ycombinator.com/cofounder-matching'
			[348] link Library, center=(932,48), url='https://www.ycombinator.com/library'
			[353] link SAFE, center=(990,48), url='https://www.ycombinator.com/documents'
			[358] link Resources, center=(1062,48), url='https://www.ycombinator.com/library'
			StaticText Apply for
			StaticText X2025
			StaticText batch.
			[375] link Apply, center=(1476,49), title=Apply for X2025 batch., url='https://www.ycombinator.com/apply'
	[382] link, center=(450,177), url='https://www.ycombinator.com/companies/sweep/jobs/8dUn406-founding-engineer'
		image, url='https://bookface-images.s3.amazonaws.com/small_logos/885d2be670d352a8d396403e926005fd75ce210b.png'
	heading Sweep
		[386] link Sweep, center=(546,162), url='https://www.ycombinator.com/companies/sweep'
	paragraph
		StaticText AI-powered Python junior developer for software teams
	heading Founding Engineer
	strong
		StaticText $130K - $170K
	StaticText /
	StaticText 0.50% - 2.00%
	strong
		StaticText Location
	StaticText San Francisco, CA, US
	strong
		StaticText Job Type
	StaticText Full-time
	strong
		StaticText Experience
	StaticText 1+ years
	StaticText Connect directly with founders of the best YC-funded startups.
	[411] link Apply to role ›, center=(514,526), url='https://account.ycombinator.com/authenticate?continue=https%3A%2F%2Fwww.workatastartup.com%2Fapplication%3Fsignup_job_id%3D65798&defaults%5BsignUpActive%5D=true&defaults%5Bwaas_company%5D=29013'
	image Kevin Lu, url='https://bookface-images.s3.us-west-2.amazonaws.com/avatars/d02bf268302d4c204515d4fc779599313b25875c.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIAQC4NIECAGN7TU2GI%2F20250105%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250105T200333Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEoaCXVzLXdlc3QtMiJIMEYCIQDxGWcNn8HwRnRQD5hbgsKrkPkjlfPVBGsGvQw%2Fp%2BlWxAIhANS6jtRQdPcj7ALnlZrgz7M%2FvvL9eaBwU6UXXKfS2yS5KuUDCDMQABoMMDA2MjAxODExMDcyIgwHOxl0tRm%2BexVO86oqwgO%2B258sMUwqWzYLz%2F8LI5M55%2B%2Fu1ZQEnMUaToa0HVLgTxycLfXoWbs6VF3i3c5mYltb0w6LrC22Nv2HWgTi3JTQYbbRBuCIfmB7AgxjUuMB0WHXASZRyB%2FqvWSyIkpOdr0tD%2BFdFDNRGjNwo%2BepJmHK1F8IYWgAcyFX3VCh1L%2B%2F5%2BgDlcZbqMc2x8uUdDMk8XVZq45pMOAueY%2BaynOhC5XEB8cApZnuGloXhaaiImf1%2BMKAgxmgEfoQ47pMt7Fgk%2BpOvEM5zndxor%2FMsOGW5ytQ%2Fexkwu5b9EVCifALACCehI22Q%2FPS4HW1TQgip73oErbjmacoos9mceWghW3lzxm2NOvNW7Ox7FW3LwiZfBO%2BWH61FppLLyzdfTdqbPFtuC8ZHD0lxe7tTJcjXZCH0ruxVUaabU5ns7jhgi3XGvoBZWmd3%2FYXkj7%2Bq8FtBkacHa0dyshUSG%2Fhc3WYI35JoVlHv7q%2B7VlnJ%2FNph5XI33IHPzozak8YXdp%2F0gMHWuSDbUmRIrswS%2BIhZkRysuK1zkLrM%2FCr3Vj73mVhoaLIAmJYYggilHxoBc66mnRwbR0NrB%2BRV22d%2BnFIHFsDlBLIyRVLF9ow0JHruwY6pAG6kcuj3tPZkxlQuj%2B8S2AWEJ6mUUwpqOL%2FIwCzV42BHg5s2aKJ4DWNJ6EHT2pRSbuqZHpzKyII6eAjPQiy3TJ7Nw%2B%2B3jaEt1tIHYfiyhG6yMOxMreunhMKizBP2FBrkE%2BtNtMOc7YppM9OGduDwqb77ijRQVVbPfqrPt8EGoVvQwV%2Bo%2FTefASZtBY1muTy0AEhzZ0wiXriBOXSqFCPVm66TFv05Q%3D%3D&X-Amz-SignedHeaders=host&X-Amz-Signature=5fa61483ce0935962a1056a1b2f922d9fb8ce17e97fa8093e1727fdfb5a5f47a'
	StaticText Kevin Lu
	StaticText Founder
	heading About the role
	paragraph
		StaticText Sweep is an AI developer that understands your codebase and practices.
		StaticText Sweep is founded by William Zeng, previously the youngest senior machine learning engineer at Roblox, and Kevin Lu, the top student in his class at Waterloo in Math/CS.
		StaticText We help companies like Pulley (Series B FinTech) save hours of engineering time.
		StaticText We're backed by investors like Goat Capital, Amjad Masad (Replit), and Y Combinator (S23).
		StaticText You’ll know:
	list
		[431] listitem, center=(807,971), inner_text=How to code/learn/research extremely quickly.
			ListMarker •
			StaticText How to code/learn/research extremely quickly.
	heading About Sweep
	paragraph
		StaticText Sweep is an AI assistant to automate your software chores like customer reported bug fixes. We take natural language descriptions of code changes and turn them into pull requests with code.
	paragraph
		StaticText We have large customers in production. We ship fast.
	image Sweep, url='https://bookface-images.s3.us-west-2.amazonaws.com/logos/9ef82faaeebb3ccab332969ef717850b83ffacae.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIAQC4NIECAGN7TU2GI%2F20250105%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250105T200333Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEoaCXVzLXdlc3QtMiJIMEYCIQDxGWcNn8HwRnRQD5hbgsKrkPkjlfPVBGsGvQw%2Fp%2BlWxAIhANS6jtRQdPcj7ALnlZrgz7M%2FvvL9eaBwU6UXXKfS2yS5KuUDCDMQABoMMDA2MjAxODExMDcyIgwHOxl0tRm%2BexVO86oqwgO%2B258sMUwqWzYLz%2F8LI5M55%2B%2Fu1ZQEnMUaToa0HVLgTxycLfXoWbs6VF3i3c5mYltb0w6LrC22Nv2HWgTi3JTQYbbRBuCIfmB7AgxjUuMB0WHXASZRyB%2FqvWSyIkpOdr0tD%2BFdFDNRGjNwo%2BepJmHK1F8IYWgAcyFX3VCh1L%2B%2F5%2BgDlcZbqMc2x8uUdDMk8XVZq45pMOAueY%2BaynOhC5XEB8cApZnuGloXhaaiImf1%2BMKAgxmgEfoQ47pMt7Fgk%2BpOvEM5zndxor%2FMsOGW5ytQ%2Fexkwu5b9EVCifALACCehI22Q%2FPS4HW1TQgip73oErbjmacoos9mceWghW3lzxm2NOvNW7Ox7FW3LwiZfBO%2BWH61FppLLyzdfTdqbPFtuC8ZHD0lxe7tTJcjXZCH0ruxVUaabU5ns7jhgi3XGvoBZWmd3%2FYXkj7%2Bq8FtBkacHa0dyshUSG%2Fhc3WYI35JoVlHv7q%2B7VlnJ%2FNph5XI33IHPzozak8YXdp%2F0gMHWuSDbUmRIrswS%2BIhZkRysuK1zkLrM%2FCr3Vj73mVhoaLIAmJYYggilHxoBc66mnRwbR0NrB%2BRV22d%2BnFIHFsDlBLIyRVLF9ow0JHruwY6pAG6kcuj3tPZkxlQuj%2B8S2AWEJ6mUUwpqOL%2FIwCzV42BHg5s2aKJ4DWNJ6EHT2pRSbuqZHpzKyII6eAjPQiy3TJ7Nw%2B%2B3jaEt1tIHYfiyhG6yMOxMreunhMKizBP2FBrkE%2BtNtMOc7YppM9OGduDwqb77ijRQVVbPfqrPt8EGoVvQwV%2Bo%2FTefASZtBY1muTy0AEhzZ0wiXriBOXSqFCPVm66TFv05Q%3D%3D&X-Amz-SignedHeaders=host&X-Amz-Signature=80ba1f69914fcaaeea09a4207781a2fc8f41157ecc189ea6f607104fca6c9a63'
	StaticText Sweep
	StaticText Founded:
	StaticText 2023
	StaticText Team Size:
	StaticText 3
	StaticText Location:
	[451] link LinkedIn profile, center=(1245,486), inner_text= , title=LinkedIn profile, url='https://www.linkedin.com/company/95674114/'
	[452] link Twitter account, center=(1273,486), inner_text= , title=Twitter account, url='https://twitter.com/sweep__ai'
	StaticText Founders
	image Kevin Lu, url='https://bookface-images.s3.us-west-2.amazonaws.com/avatars/d02bf268302d4c204515d4fc779599313b25875c.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIAQC4NIECAGN7TU2GI%2F20250105%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250105T200333Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEoaCXVzLXdlc3QtMiJIMEYCIQDxGWcNn8HwRnRQD5hbgsKrkPkjlfPVBGsGvQw%2Fp%2BlWxAIhANS6jtRQdPcj7ALnlZrgz7M%2FvvL9eaBwU6UXXKfS2yS5KuUDCDMQABoMMDA2MjAxODExMDcyIgwHOxl0tRm%2BexVO86oqwgO%2B258sMUwqWzYLz%2F8LI5M55%2B%2Fu1ZQEnMUaToa0HVLgTxycLfXoWbs6VF3i3c5mYltb0w6LrC22Nv2HWgTi3JTQYbbRBuCIfmB7AgxjUuMB0WHXASZRyB%2FqvWSyIkpOdr0tD%2BFdFDNRGjNwo%2BepJmHK1F8IYWgAcyFX3VCh1L%2B%2F5%2BgDlcZbqMc2x8uUdDMk8XVZq45pMOAueY%2BaynOhC5XEB8cApZnuGloXhaaiImf1%2BMKAgxmgEfoQ47pMt7Fgk%2BpOvEM5zndxor%2FMsOGW5ytQ%2Fexkwu5b9EVCifALACCehI22Q%2FPS4HW1TQgip73oErbjmacoos9mceWghW3lzxm2NOvNW7Ox7FW3LwiZfBO%2BWH61FppLLyzdfTdqbPFtuC8ZHD0lxe7tTJcjXZCH0ruxVUaabU5ns7jhgi3XGvoBZWmd3%2FYXkj7%2Bq8FtBkacHa0dyshUSG%2Fhc3WYI35JoVlHv7q%2B7VlnJ%2FNph5XI33IHPzozak8YXdp%2F0gMHWuSDbUmRIrswS%2BIhZkRysuK1zkLrM%2FCr3Vj73mVhoaLIAmJYYggilHxoBc66mnRwbR0NrB%2BRV22d%2BnFIHFsDlBLIyRVLF9ow0JHruwY6pAG6kcuj3tPZkxlQuj%2B8S2AWEJ6mUUwpqOL%2FIwCzV42BHg5s2aKJ4DWNJ6EHT2pRSbuqZHpzKyII6eAjPQiy3TJ7Nw%2B%2B3jaEt1tIHYfiyhG6yMOxMreunhMKizBP2FBrkE%2BtNtMOc7YppM9OGduDwqb77ijRQVVbPfqrPt8EGoVvQwV%2Bo%2FTefASZtBY1muTy0AEhzZ0wiXriBOXSqFCPVm66TFv05Q%3D%3D&X-Amz-SignedHeaders=host&X-Amz-Signature=5fa61483ce0935962a1056a1b2f922d9fb8ce17e97fa8093e1727fdfb5a5f47a'
	StaticText Kevin Lu
	StaticText Founder
	[462] link Twitter account, center=(1332,679), inner_text= , title=Twitter account, url='https://twitter.com/kevinlu1248'
	[463] link LinkedIn profile, center=(1360,679), inner_text= , title=LinkedIn profile, url='https://linkedin.com/in/kevinlu1248'
	image William Zeng, url='https://bookface-images.s3.us-west-2.amazonaws.com/avatars/6ea14a52703b3d5d1bc15d010a715f0a74723845.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIAQC4NIECAGN7TU2GI%2F20250105%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250105T200333Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEoaCXVzLXdlc3QtMiJIMEYCIQDxGWcNn8HwRnRQD5hbgsKrkPkjlfPVBGsGvQw%2Fp%2BlWxAIhANS6jtRQdPcj7ALnlZrgz7M%2FvvL9eaBwU6UXXKfS2yS5KuUDCDMQABoMMDA2MjAxODExMDcyIgwHOxl0tRm%2BexVO86oqwgO%2B258sMUwqWzYLz%2F8LI5M55%2B%2Fu1ZQEnMUaToa0HVLgTxycLfXoWbs6VF3i3c5mYltb0w6LrC22Nv2HWgTi3JTQYbbRBuCIfmB7AgxjUuMB0WHXASZRyB%2FqvWSyIkpOdr0tD%2BFdFDNRGjNwo%2BepJmHK1F8IYWgAcyFX3VCh1L%2B%2F5%2BgDlcZbqMc2x8uUdDMk8XVZq45pMOAueY%2BaynOhC5XEB8cApZnuGloXhaaiImf1%2BMKAgxmgEfoQ47pMt7Fgk%2BpOvEM5zndxor%2FMsOGW5ytQ%2Fexkwu5b9EVCifALACCehI22Q%2FPS4HW1TQgip73oErbjmacoos9mceWghW3lzxm2NOvNW7Ox7FW3LwiZfBO%2BWH61FppLLyzdfTdqbPFtuC8ZHD0lxe7tTJcjXZCH0ruxVUaabU5ns7jhgi3XGvoBZWmd3%2FYXkj7%2Bq8FtBkacHa0dyshUSG%2Fhc3WYI35JoVlHv7q%2B7VlnJ%2FNph5XI33IHPzozak8YXdp%2F0gMHWuSDbUmRIrswS%2BIhZkRysuK1zkLrM%2FCr3Vj73mVhoaLIAmJYYggilHxoBc66mnRwbR0NrB%2BRV22d%2BnFIHFsDlBLIyRVLF9ow0JHruwY6pAG6kcuj3tPZkxlQuj%2B8S2AWEJ6mUUwpqOL%2FIwCzV42BHg5s2aKJ4DWNJ6EHT2pRSbuqZHpzKyII6eAjPQiy3TJ7Nw%2B%2B3jaEt1tIHYfiyhG6yMOxMreunhMKizBP2FBrkE%2BtNtMOc7YppM9OGduDwqb77ijRQVVbPfqrPt8EGoVvQwV%2Bo%2FTefASZtBY1muTy0AEhzZ0wiXriBOXSqFCPVm66TFv05Q%3D%3D&X-Amz-SignedHeaders=host&X-Amz-Signature=c633adb5e95a7c15c0bd516ddcc3e1be77419aed44a773c3268de95b4f043f80'
	StaticText William Zeng
	StaticText Founder
	[471] link Twitter account, center=(1332,820), inner_text= , title=Twitter account, url='https://twitter.com/wwzeng1'
	[472] link LinkedIn profile, center=(1360,820), inner_text= , title=LinkedIn profile, url='https://linkedin.com/in/william-zeng'
	StaticText Similar Jobs
	image Hiro Systems, url='https://bookface-images.s3.amazonaws.com/small_logos/96d6585dd5c6970a5bdb324b4a4d6e71b977b149.png'
	[480] link Hiro Systems, center=(1334,985), url='https://www.ycombinator.com/companies/hiro-systems'
	[482] link Blockchain Engineer, center=(1356,1001), url='https://www.ycombinator.com/companies/hiro-systems/jobs/QXDWQ9l-blockchain-engineer'
	image Kombo, url='https://bookface-images.s3.amazonaws.com/small_logos/1ea96f644bc25cfeaa1198b5db442e95f63b56b4.png'
	[487] link Kombo, center=(1318,1037), url='https://www.ycombinator.com/companies/kombo'
	link Haven't found what you are looking for? Operations/Engineering/Product, url='https://www.ycombinator.com/companies/kombo/jobs/vyzsAci-haven-t-found-what-you-are-looking-for-operations-engineering-product'
	image Morphle Labs, url='https://bookface-images.s3.amazonaws.com/small_logos/c76097b716ca7b82f6b26beb694f3ab12e87aab6.png'
	link Morphle Labs, url='https://www.ycombinator.com/companies/morphle-labs'
	link Senior Software Engineer, url='https://www.ycombinator.com/companies/morphle-labs/jobs/N2I8gal-senior-software-engineer'
	image Dripos, url='https://bookface-images.s3.amazonaws.com/small_logos/ba1d88383fb670f4bece6ddacd19dd9b25e972cc.png'
	link Dripos, url='https://www.ycombinator.com/companies/dripos'
	link Software Engineer - Full Stack, url='https://www.ycombinator.com/companies/dripos/jobs/W4A72t9-software-engineer-full-stack'
	image FlutterFlow, url='https://bookface-images.s3.amazonaws.com/small_logos/3df7b6e09c2fda2538b0426203b84e4e92ca7471.png'
	link FlutterFlow, url='https://www.ycombinator.com/companies/flutterflow'
	link Software Engineer - AI (United States), url='https://www.ycombinator.com/companies/flutterflow/jobs/UnyHKVJ-software-engineer-ai-united-states'
	image Coba, url='https://bookface-images.s3.amazonaws.com/small_logos/064ab4995b234ee61187e6d755a27338f57c5c90.png'
	link Coba, url='https://www.ycombinator.com/companies/coba'
	link Coba.ai Hiring | Full-stack developers for US-MX cross-border fintech (remote US or MX), url='https://www.ycombinator.com/companies/coba/jobs/9wju4KE-coba-ai-hiring-full-stack-developers-for-us-mx-cross-border-fintech-remote-us-or-mx'
	image Converge, url='https://bookface-images.s3.amazonaws.com/small_logos/6ddaa5bebf2aae550b90599e16a46dc1f877c755.png'
	link Converge, url='https://www.ycombinator.com/companies/converge'
	link Founding Engineer (#2 at $1M+ ARR), url='https://www.ycombinator.com/companies/converge/jobs/GQWZ40Z-founding-engineer-2-at-1m-arr'
	image Latent, url='https://bookface-images.s3.amazonaws.com/small_logos/d464e72e759603ce78169d56b1ef679252bf2dae.png'
	link Latent, url='https://www.ycombinator.com/companies/latent'
	link Senior Software Engineer (Full Stack), url='https://www.ycombinator.com/companies/latent/jobs/KqOXaXA-senior-software-engineer-full-stack'
	image AviaryAI, url='https://bookface-images.s3.amazonaws.com/small_logos/c883569550177f7700c6efba769c869c5d530759.png'
	link AviaryAI, url='https://www.ycombinator.com/companies/aviaryai'
	link Full Stack Software Engineer, url='https://www.ycombinator.com/companies/aviaryai/jobs/dbF1b7S-full-stack-software-engineer'
	image HippoBuild, url='https://bookface-images.s3.amazonaws.com/small_logos/a5b7abe9b8dc9591204def8329e61e695322cd8e.png'
	link HippoBuild, url='https://www.ycombinator.com/companies/hippobuild'
	link FlutterFlow & Firebase Engineer, url='https://www.ycombinator.com/companies/hippobuild/jobs/LfFcPQy-flutterflow-firebase-engineer'
	image Codes Health, url='https://bookface-images.s3.amazonaws.com/small_logos/ae2e103cef868d10d11f8eda1c9371448e8a4640.png'
	link Codes Health, url='https://www.ycombinator.com/companies/codes-health'
	link Founding Engineer, url='https://www.ycombinator.com/companies/codes-health/jobs/RK8DNqG-founding-engineer'
	image InspectMind AI, url='https://bookface-images.s3.amazonaws.com/small_logos/380201f9cadb6a3d51cb0328080b2378d425269f.png'
	link InspectMind AI, url='https://www.ycombinator.com/companies/inspectmind-ai'
	link Software Engineer, url='https://www.ycombinator.com/companies/inspectmind-ai/jobs/rPuRKf1-software-engineer'
	image Mino Games, url='https://bookface-images.s3.amazonaws.com/small_logos/573373ab6401e76024bab0260b4ba1cd64b7a1fe.png'
	link Mino Games, url='https://www.ycombinator.com/companies/mino-games'
	link Game Developer, url='https://www.ycombinator.com/companies/mino-games/jobs/6Toj1IT1z-game-developer'
	image PermitFlow, url='https://bookface-images.s3.amazonaws.com/small_logos/7ded490920c3d66fa08b0a9da3269ee21d78daff.png'
	link PermitFlow, url='https://www.ycombinator.com/companies/permitflow'
	link Staff Software Engineer, url='https://www.ycombinator.com/companies/permitflow/jobs/sh5wkwG-staff-software-engineer'
	image Eight Sleep, url='https://bookface-images.s3.amazonaws.com/small_logos/b649c0ed7300661389c61da3478d9e510a6ef517.png'
	link Eight Sleep, url='https://www.ycombinator.com/companies/eight-sleep'
	link Full Stack Engineer - Web Focus, url='https://www.ycombinator.com/companies/eight-sleep/jobs/slZD7gD-full-stack-engineer-web-focus'
	image Numeral, url='https://bookface-images.s3.amazonaws.com/small_logos/c0f30c988fde8ec60cc14e8c5cf656b62cd6d35d.png'
	link Numeral, url='https://www.ycombinator.com/companies/numeral'
	link Software Engineer (Product), url='https://www.ycombinator.com/companies/numeral/jobs/HLVIyAP-software-engineer-product'
	image 222, url='https://bookface-images.s3.amazonaws.com/small_logos/2e693471ebf0087cdb9edcdba2657ef0066b1a88.png'
	link 222, url='https://www.ycombinator.com/companies/222'
	link Full-Stack Software Engineer, url='https://www.ycombinator.com/companies/222/jobs/QlmT2Pl-full-stack-software-engineer'
	image Artisan, url='https://bookface-images.s3.amazonaws.com/small_logos/3aa68965eefe42dc96e16073740dae2087ad188f.png'
	link Artisan, url='https://www.ycombinator.com/companies/artisan'
	link Full Stack Engineer, url='https://www.ycombinator.com/companies/artisan/jobs/BgWVElZ-full-stack-engineer'
	image Olympian Motors, url='https://bookface-images.s3.amazonaws.com/small_logos/295a828c811272d963b3ebd52d4f226bb1023827.png'
	link Olympian Motors, url='https://www.ycombinator.com/companies/olympian-motors'
	link Head of Vehicle Engineering (Full-Stack), url='https://www.ycombinator.com/companies/olympian-motors/jobs/cWz8Glx-head-of-vehicle-engineering-full-stack'
	image autarc, url='https://bookface-images.s3.amazonaws.com/small_logos/c6f422aa332e520cce9d631b8dfbcdfb14375c6e.png'
	link autarc, url='https://www.ycombinator.com/companies/autarc'
	link Senior Fullstack Engineer (React, Supabase), url='https://www.ycombinator.com/companies/autarc/jobs/bQKx2VT-senior-fullstack-engineer-react-supabase'
	contentinfo Footer
		heading Footer
		link Y Combinator Y Combinator, url='https://www.ycombinator.com/'
			image Y Combinator, url='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAQEAAAEBCAMAAABPMuDPAAAAQlBMVEXyZSLyZSLyZSLyZSLyZSL6roH91br2ilD+6tr4nGn0eDf7wp3+9e3zbyz3k1z0gUP7uI/5pXX+38n8y6z////yZSKuMvVfAAAABXRSTlOAQMBgICelMzEAAAOgSURBVHhe5MABDQAAAIIw3eifmSB8vA3Zt5vcuGEgCsLeUBSpnxnb4f2vmn068xK5Z8FuFQ8gCB9q80Dw42Pc+3y8UQABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQACBR7GnuAF6MafNKnDsv+xx/+1mv3nOKjDKXwRWbwIWYJl4F6wigvclUCcWaCKCeRKwAtNFoBN4TC1wigjelMA2+S5YRATv+VyfXKC+NYIqEphVQEfgT2Dv0ws8VAT+BEqAXbCJCPwJHAEEuorAn0AAARGBO4H1CCFw7O+JoArIuQVGERH4EhgBBFQE/gQmF9ARnP4EljG5gB5Iiz+BGkBAreTqTyCAgIzAnUAogdMbwSIm0cQCeiAtvgR6MIEqInAkEEBARuBKIJzAwxOB5SsBb822n0dQxSoOJNBFBI4EAgmMp4jAkUAAATWQ6s8SaEFvz8vPIqhiWAYQcEQgEogqMD5FBBcS+BrBBPRAqtcTqIEF2vUIqsgmgIAjApFAaIF6NQKbwPcIKKAHUr2WQI8k4I+gilUcQMARgUggvEC/EkEzAM8E7wu2CxGsdhJFEvBH0MQqDiegV3J1JBBQ4NhFBDqBzyTvC4qIQCawjgwCOgKdQIstoFdydSQQRcD2rSNoVimRQPuPCFaLFF1AR7A5EggloK/BdAIZBPRVqE6ghxLwR7BaoBQCOgKdQDqBLiIQCSQSGJuIoNlJlEVAR3C8TKCkfHX7fLn+T5tASoFjf9X6YmlSCozyYvxVO4kSCegI1r8n0FIJ6IF0igQyCej9txiWZAI6gsfoViWxwPiy+2gzqzi1QLUR2ATSCeiBtBuSfAI6AjsWkguM738I9PQC3ZFADoGxKYC95xfQEZRxA4FRRALHLQSOXSSQXkBHsB75BXQEbWQV0APJruL8AmMVCaQW0BEsI5uAXsn21FsJVJFAZgH9juJmAsVOorsLlLsJIIAAAggggAACCCCAAAIIIIAAAggggAACCCCAAAIIIIAAAggggAACCCCAAAIIIIAAAggggAACCCCAAAIIIIAAAm3547QAAoGPFkAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBH6XAwc0AAAAAME2+ncWxOXNAI6Cs14i3Db7AAAAAElFTkSuQmCC'
		heading Programs
		list
			listitem
				link YC Program, url='https://www.ycombinator.com/about'
			listitem
				link Startup School, url='https://startupschool.org/'
			listitem
				link Work at a Startup, url='https://www.ycombinator.com/jobs'
			listitem
				link Co-Founder Matching, url='https://www.ycombinator.com/cofounder-matching'
		heading Company
		list
			listitem
				link YC Blog, url='https://www.ycombinator.com/blog'
			listitem
				link Contact, url='https://www.ycombinator.com/contact'
			listitem
				link Press, url='https://www.ycombinator.com/press'
			listitem
				link People, url='https://www.ycombinator.com/people'
			listitem
				link Careers, url='https://www.ycombinator.com/careers'
			listitem
				link Privacy Policy, url='https://www.ycombinator.com/legal#privacy'
			listitem
				link Notice at Collection, url='https://www.ycombinator.com/legal#notice-at-collection'
			listitem
				link Security, url='https://www.ycombinator.com/security'
			listitem
				link Terms of Use, url='https://www.ycombinator.com/legal#tou'
		heading Resources
		list
			listitem
				link Startup Directory, url='https://www.ycombinator.com/companies'
			listitem
				link Startup Library, url='https://www.ycombinator.com/library'
			listitem
				link Investors, url='https://www.ycombinator.com/investors'
			listitem
				link SAFE, url='https://www.ycombinator.com/documents'
			listitem
				link Hacker News, url='https://news.ycombinator.com/'
			listitem
				link Launch YC, url='https://www.ycombinator.com/launches'
			listitem
				link YC Deals, url='https://deals.ycombinator.com/'
		heading Make something people want.
		link Apply, url='https://www.ycombinator.com/apply'
		link Twitter, url='https://twitter.com/ycombinator'
		link Facebook, url='https://www.facebook.com/YCombinator/'
		link Instagram, url='https://www.instagram.com/ycombinator'
		link LinkedIn, url='https://www.linkedin.com/school/y-combinator/'
		link Youtube, url='https://www.youtube.com/c/ycombinator'
		paragraph
			StaticText © 2024 Y Combinator
```
</details>

**Reasoning for action:** I clicked on the Open Positions button because it is essential for me to access the section of the website that lists job openings. This step is critical in fulfilling the user story of exploring job opportunities at Sweep AI, specifically to find the Founding Engineer role I want to apply for. By initiating this action, I am moving closer to my goal of applying for the job.

**Action:** click(127) # Click on the Open Positions button to explore job opportunities at Sweep AI.

**Change Description:** The browser navigated from the "About Us" page of Sweep AI to the "Founding Engineer at Sweep" job listing on the Y Combinator website, changing the URL and content displayed to focus on job opportunities available at Sweep AI.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.ycombinator.com/companies/sweep/jobs/8dUn406-founding-engineer

https://www.ycombinator.com/companies/sweep/jobs/8dUn406-founding-engineer

**Content (before/after):** 

```
RootWebArea Founding Engineer at Sweep | Y Combinator, focused, url='https://www.ycombinator.com/companies/sweep/jobs/8dUn406-founding-engineer'
	banner
		navigation
			[306] link Y Combinator, center=(438,48), title=Y Combinator, url='https://www.ycombinator.com/'
				image Y Combinator, url='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAQEAAAEBCAMAAABPMuDPAAAAQlBMVEXyZSLyZSLyZSLyZSLyZSL6roH91br2ilD+6tr4nGn0eDf7wp3+9e3zbyz3k1z0gUP7uI/5pXX+38n8y6z////yZSKuMvVfAAAABXRSTlOAQMBgICelMzEAAAOgSURBVHhe5MABDQAAAIIw3eifmSB8vA3Zt5vcuGEgCsLeUBSpnxnb4f2vmn068xK5Z8FuFQ8gCB9q80Dw42Pc+3y8UQABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQACBR7GnuAF6MafNKnDsv+xx/+1mv3nOKjDKXwRWbwIWYJl4F6wigvclUCcWaCKCeRKwAtNFoBN4TC1wigjelMA2+S5YRATv+VyfXKC+NYIqEphVQEfgT2Dv0ws8VAT+BEqAXbCJCPwJHAEEuorAn0AAARGBO4H1CCFw7O+JoArIuQVGERH4EhgBBFQE/gQmF9ARnP4EljG5gB5Iiz+BGkBAreTqTyCAgIzAnUAogdMbwSIm0cQCeiAtvgR6MIEqInAkEEBARuBKIJzAwxOB5SsBb822n0dQxSoOJNBFBI4EAgmMp4jAkUAAATWQ6s8SaEFvz8vPIqhiWAYQcEQgEogqMD5FBBcS+BrBBPRAqtcTqIEF2vUIqsgmgIAjApFAaIF6NQKbwPcIKKAHUr2WQI8k4I+gilUcQMARgUggvEC/EkEzAM8E7wu2CxGsdhJFEvBH0MQqDiegV3J1JBBQ4NhFBDqBzyTvC4qIQCawjgwCOgKdQIstoFdydSQQRcD2rSNoVimRQPuPCFaLFF1AR7A5EggloK/BdAIZBPRVqE6ghxLwR7BaoBQCOgKdQDqBLiIQCSQSGJuIoNlJlEVAR3C8TKCkfHX7fLn+T5tASoFjf9X6YmlSCozyYvxVO4kSCegI1r8n0FIJ6IF0igQyCej9txiWZAI6gsfoViWxwPiy+2gzqzi1QLUR2ATSCeiBtBuSfAI6AjsWkguM738I9PQC3ZFADoGxKYC95xfQEZRxA4FRRALHLQSOXSSQXkBHsB75BXQEbWQV0APJruL8AmMVCaQW0BEsI5uAXsn21FsJVJFAZgH9juJmAsVOorsLlLsJIIAAAggggAACCCCAAAIIIIAAAggggAACCCCAAAIIIIAAAggggAACCCCAAAIIIIAAAggggAACCCCAAAIIIIAAAm3547QAAoGPFkAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBH6XAwc0AAAAAME2+ncWxOXNAI6Cs14i3Db7AAAAAElFTkSuQmCC'
```
<details><summary>Show more</summary>

```
			[310] link About, center=(514,48), url='https://www.ycombinator.com/about'
			[321] link Companies, center=(594,48), url='https://www.ycombinator.com/companies'
			[329] link Startup Jobs, center=(696,48), url='https://www.ycombinator.com/jobs'
			[343] link Find a Co-Founder, center=(824,48), url='https://www.ycombinator.com/cofounder-matching'
			[348] link Library, center=(932,48), url='https://www.ycombinator.com/library'
			[353] link SAFE, center=(990,48), url='https://www.ycombinator.com/documents'
			[358] link Resources, center=(1062,48), url='https://www.ycombinator.com/library'
			StaticText Apply for
			StaticText X2025
			StaticText batch.
			[375] link Apply, center=(1476,49), title=Apply for X2025 batch., url='https://www.ycombinator.com/apply'
	[382] link, center=(450,177), url='https://www.ycombinator.com/companies/sweep/jobs/8dUn406-founding-engineer'
		image, url='https://bookface-images.s3.amazonaws.com/small_logos/885d2be670d352a8d396403e926005fd75ce210b.png'
	heading Sweep
		[386] link Sweep, center=(546,162), url='https://www.ycombinator.com/companies/sweep'
	paragraph
		StaticText AI-powered Python junior developer for software teams
	heading Founding Engineer
	strong
		StaticText $130K - $170K
	StaticText /
	StaticText 0.50% - 2.00%
	strong
		StaticText Location
	StaticText San Francisco, CA, US
	strong
		StaticText Job Type
	StaticText Full-time
	strong
		StaticText Experience
	StaticText 1+ years
	StaticText Connect directly with founders of the best YC-funded startups.
	[411] link Apply to role ›, center=(514,526), url='https://account.ycombinator.com/authenticate?continue=https%3A%2F%2Fwww.workatastartup.com%2Fapplication%3Fsignup_job_id%3D65798&defaults%5BsignUpActive%5D=true&defaults%5Bwaas_company%5D=29013'
	image Kevin Lu, url='https://bookface-images.s3.us-west-2.amazonaws.com/avatars/d02bf268302d4c204515d4fc779599313b25875c.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIAQC4NIECAGN7TU2GI%2F20250105%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250105T200333Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEoaCXVzLXdlc3QtMiJIMEYCIQDxGWcNn8HwRnRQD5hbgsKrkPkjlfPVBGsGvQw%2Fp%2BlWxAIhANS6jtRQdPcj7ALnlZrgz7M%2FvvL9eaBwU6UXXKfS2yS5KuUDCDMQABoMMDA2MjAxODExMDcyIgwHOxl0tRm%2BexVO86oqwgO%2B258sMUwqWzYLz%2F8LI5M55%2B%2Fu1ZQEnMUaToa0HVLgTxycLfXoWbs6VF3i3c5mYltb0w6LrC22Nv2HWgTi3JTQYbbRBuCIfmB7AgxjUuMB0WHXASZRyB%2FqvWSyIkpOdr0tD%2BFdFDNRGjNwo%2BepJmHK1F8IYWgAcyFX3VCh1L%2B%2F5%2BgDlcZbqMc2x8uUdDMk8XVZq45pMOAueY%2BaynOhC5XEB8cApZnuGloXhaaiImf1%2BMKAgxmgEfoQ47pMt7Fgk%2BpOvEM5zndxor%2FMsOGW5ytQ%2Fexkwu5b9EVCifALACCehI22Q%2FPS4HW1TQgip73oErbjmacoos9mceWghW3lzxm2NOvNW7Ox7FW3LwiZfBO%2BWH61FppLLyzdfTdqbPFtuC8ZHD0lxe7tTJcjXZCH0ruxVUaabU5ns7jhgi3XGvoBZWmd3%2FYXkj7%2Bq8FtBkacHa0dyshUSG%2Fhc3WYI35JoVlHv7q%2B7VlnJ%2FNph5XI33IHPzozak8YXdp%2F0gMHWuSDbUmRIrswS%2BIhZkRysuK1zkLrM%2FCr3Vj73mVhoaLIAmJYYggilHxoBc66mnRwbR0NrB%2BRV22d%2BnFIHFsDlBLIyRVLF9ow0JHruwY6pAG6kcuj3tPZkxlQuj%2B8S2AWEJ6mUUwpqOL%2FIwCzV42BHg5s2aKJ4DWNJ6EHT2pRSbuqZHpzKyII6eAjPQiy3TJ7Nw%2B%2B3jaEt1tIHYfiyhG6yMOxMreunhMKizBP2FBrkE%2BtNtMOc7YppM9OGduDwqb77ijRQVVbPfqrPt8EGoVvQwV%2Bo%2FTefASZtBY1muTy0AEhzZ0wiXriBOXSqFCPVm66TFv05Q%3D%3D&X-Amz-SignedHeaders=host&X-Amz-Signature=5fa61483ce0935962a1056a1b2f922d9fb8ce17e97fa8093e1727fdfb5a5f47a'
	StaticText Kevin Lu
	StaticText Founder
	heading About the role
	paragraph
		StaticText Sweep is an AI developer that understands your codebase and practices.
		StaticText Sweep is founded by William Zeng, previously the youngest senior machine learning engineer at Roblox, and Kevin Lu, the top student in his class at Waterloo in Math/CS.
		StaticText We help companies like Pulley (Series B FinTech) save hours of engineering time.
		StaticText We're backed by investors like Goat Capital, Amjad Masad (Replit), and Y Combinator (S23).
		StaticText You’ll know:
	list
		[431] listitem, center=(807,971), inner_text=How to code/learn/research extremely quickly.
			ListMarker •
			StaticText How to code/learn/research extremely quickly.
	heading About Sweep
	paragraph
		StaticText Sweep is an AI assistant to automate your software chores like customer reported bug fixes. We take natural language descriptions of code changes and turn them into pull requests with code.
	paragraph
		StaticText We have large customers in production. We ship fast.
	image Sweep, url='https://bookface-images.s3.us-west-2.amazonaws.com/logos/9ef82faaeebb3ccab332969ef717850b83ffacae.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIAQC4NIECAGN7TU2GI%2F20250105%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250105T200333Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEoaCXVzLXdlc3QtMiJIMEYCIQDxGWcNn8HwRnRQD5hbgsKrkPkjlfPVBGsGvQw%2Fp%2BlWxAIhANS6jtRQdPcj7ALnlZrgz7M%2FvvL9eaBwU6UXXKfS2yS5KuUDCDMQABoMMDA2MjAxODExMDcyIgwHOxl0tRm%2BexVO86oqwgO%2B258sMUwqWzYLz%2F8LI5M55%2B%2Fu1ZQEnMUaToa0HVLgTxycLfXoWbs6VF3i3c5mYltb0w6LrC22Nv2HWgTi3JTQYbbRBuCIfmB7AgxjUuMB0WHXASZRyB%2FqvWSyIkpOdr0tD%2BFdFDNRGjNwo%2BepJmHK1F8IYWgAcyFX3VCh1L%2B%2F5%2BgDlcZbqMc2x8uUdDMk8XVZq45pMOAueY%2BaynOhC5XEB8cApZnuGloXhaaiImf1%2BMKAgxmgEfoQ47pMt7Fgk%2BpOvEM5zndxor%2FMsOGW5ytQ%2Fexkwu5b9EVCifALACCehI22Q%2FPS4HW1TQgip73oErbjmacoos9mceWghW3lzxm2NOvNW7Ox7FW3LwiZfBO%2BWH61FppLLyzdfTdqbPFtuC8ZHD0lxe7tTJcjXZCH0ruxVUaabU5ns7jhgi3XGvoBZWmd3%2FYXkj7%2Bq8FtBkacHa0dyshUSG%2Fhc3WYI35JoVlHv7q%2B7VlnJ%2FNph5XI33IHPzozak8YXdp%2F0gMHWuSDbUmRIrswS%2BIhZkRysuK1zkLrM%2FCr3Vj73mVhoaLIAmJYYggilHxoBc66mnRwbR0NrB%2BRV22d%2BnFIHFsDlBLIyRVLF9ow0JHruwY6pAG6kcuj3tPZkxlQuj%2B8S2AWEJ6mUUwpqOL%2FIwCzV42BHg5s2aKJ4DWNJ6EHT2pRSbuqZHpzKyII6eAjPQiy3TJ7Nw%2B%2B3jaEt1tIHYfiyhG6yMOxMreunhMKizBP2FBrkE%2BtNtMOc7YppM9OGduDwqb77ijRQVVbPfqrPt8EGoVvQwV%2Bo%2FTefASZtBY1muTy0AEhzZ0wiXriBOXSqFCPVm66TFv05Q%3D%3D&X-Amz-SignedHeaders=host&X-Amz-Signature=80ba1f69914fcaaeea09a4207781a2fc8f41157ecc189ea6f607104fca6c9a63'
	StaticText Sweep
	StaticText Founded:
	StaticText 2023
	StaticText Team Size:
	StaticText 3
	StaticText Location:
	[451] link LinkedIn profile, center=(1245,486), inner_text= , title=LinkedIn profile, url='https://www.linkedin.com/company/95674114/'
	[452] link Twitter account, center=(1273,486), inner_text= , title=Twitter account, url='https://twitter.com/sweep__ai'
	StaticText Founders
	image Kevin Lu, url='https://bookface-images.s3.us-west-2.amazonaws.com/avatars/d02bf268302d4c204515d4fc779599313b25875c.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIAQC4NIECAGN7TU2GI%2F20250105%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250105T200333Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEoaCXVzLXdlc3QtMiJIMEYCIQDxGWcNn8HwRnRQD5hbgsKrkPkjlfPVBGsGvQw%2Fp%2BlWxAIhANS6jtRQdPcj7ALnlZrgz7M%2FvvL9eaBwU6UXXKfS2yS5KuUDCDMQABoMMDA2MjAxODExMDcyIgwHOxl0tRm%2BexVO86oqwgO%2B258sMUwqWzYLz%2F8LI5M55%2B%2Fu1ZQEnMUaToa0HVLgTxycLfXoWbs6VF3i3c5mYltb0w6LrC22Nv2HWgTi3JTQYbbRBuCIfmB7AgxjUuMB0WHXASZRyB%2FqvWSyIkpOdr0tD%2BFdFDNRGjNwo%2BepJmHK1F8IYWgAcyFX3VCh1L%2B%2F5%2BgDlcZbqMc2x8uUdDMk8XVZq45pMOAueY%2BaynOhC5XEB8cApZnuGloXhaaiImf1%2BMKAgxmgEfoQ47pMt7Fgk%2BpOvEM5zndxor%2FMsOGW5ytQ%2Fexkwu5b9EVCifALACCehI22Q%2FPS4HW1TQgip73oErbjmacoos9mceWghW3lzxm2NOvNW7Ox7FW3LwiZfBO%2BWH61FppLLyzdfTdqbPFtuC8ZHD0lxe7tTJcjXZCH0ruxVUaabU5ns7jhgi3XGvoBZWmd3%2FYXkj7%2Bq8FtBkacHa0dyshUSG%2Fhc3WYI35JoVlHv7q%2B7VlnJ%2FNph5XI33IHPzozak8YXdp%2F0gMHWuSDbUmRIrswS%2BIhZkRysuK1zkLrM%2FCr3Vj73mVhoaLIAmJYYggilHxoBc66mnRwbR0NrB%2BRV22d%2BnFIHFsDlBLIyRVLF9ow0JHruwY6pAG6kcuj3tPZkxlQuj%2B8S2AWEJ6mUUwpqOL%2FIwCzV42BHg5s2aKJ4DWNJ6EHT2pRSbuqZHpzKyII6eAjPQiy3TJ7Nw%2B%2B3jaEt1tIHYfiyhG6yMOxMreunhMKizBP2FBrkE%2BtNtMOc7YppM9OGduDwqb77ijRQVVbPfqrPt8EGoVvQwV%2Bo%2FTefASZtBY1muTy0AEhzZ0wiXriBOXSqFCPVm66TFv05Q%3D%3D&X-Amz-SignedHeaders=host&X-Amz-Signature=5fa61483ce0935962a1056a1b2f922d9fb8ce17e97fa8093e1727fdfb5a5f47a'
	StaticText Kevin Lu
	StaticText Founder
	[462] link Twitter account, center=(1332,679), inner_text= , title=Twitter account, url='https://twitter.com/kevinlu1248'
	[463] link LinkedIn profile, center=(1360,679), inner_text= , title=LinkedIn profile, url='https://linkedin.com/in/kevinlu1248'
	image William Zeng, url='https://bookface-images.s3.us-west-2.amazonaws.com/avatars/6ea14a52703b3d5d1bc15d010a715f0a74723845.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIAQC4NIECAGN7TU2GI%2F20250105%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250105T200333Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEoaCXVzLXdlc3QtMiJIMEYCIQDxGWcNn8HwRnRQD5hbgsKrkPkjlfPVBGsGvQw%2Fp%2BlWxAIhANS6jtRQdPcj7ALnlZrgz7M%2FvvL9eaBwU6UXXKfS2yS5KuUDCDMQABoMMDA2MjAxODExMDcyIgwHOxl0tRm%2BexVO86oqwgO%2B258sMUwqWzYLz%2F8LI5M55%2B%2Fu1ZQEnMUaToa0HVLgTxycLfXoWbs6VF3i3c5mYltb0w6LrC22Nv2HWgTi3JTQYbbRBuCIfmB7AgxjUuMB0WHXASZRyB%2FqvWSyIkpOdr0tD%2BFdFDNRGjNwo%2BepJmHK1F8IYWgAcyFX3VCh1L%2B%2F5%2BgDlcZbqMc2x8uUdDMk8XVZq45pMOAueY%2BaynOhC5XEB8cApZnuGloXhaaiImf1%2BMKAgxmgEfoQ47pMt7Fgk%2BpOvEM5zndxor%2FMsOGW5ytQ%2Fexkwu5b9EVCifALACCehI22Q%2FPS4HW1TQgip73oErbjmacoos9mceWghW3lzxm2NOvNW7Ox7FW3LwiZfBO%2BWH61FppLLyzdfTdqbPFtuC8ZHD0lxe7tTJcjXZCH0ruxVUaabU5ns7jhgi3XGvoBZWmd3%2FYXkj7%2Bq8FtBkacHa0dyshUSG%2Fhc3WYI35JoVlHv7q%2B7VlnJ%2FNph5XI33IHPzozak8YXdp%2F0gMHWuSDbUmRIrswS%2BIhZkRysuK1zkLrM%2FCr3Vj73mVhoaLIAmJYYggilHxoBc66mnRwbR0NrB%2BRV22d%2BnFIHFsDlBLIyRVLF9ow0JHruwY6pAG6kcuj3tPZkxlQuj%2B8S2AWEJ6mUUwpqOL%2FIwCzV42BHg5s2aKJ4DWNJ6EHT2pRSbuqZHpzKyII6eAjPQiy3TJ7Nw%2B%2B3jaEt1tIHYfiyhG6yMOxMreunhMKizBP2FBrkE%2BtNtMOc7YppM9OGduDwqb77ijRQVVbPfqrPt8EGoVvQwV%2Bo%2FTefASZtBY1muTy0AEhzZ0wiXriBOXSqFCPVm66TFv05Q%3D%3D&X-Amz-SignedHeaders=host&X-Amz-Signature=c633adb5e95a7c15c0bd516ddcc3e1be77419aed44a773c3268de95b4f043f80'
	StaticText William Zeng
	StaticText Founder
	[471] link Twitter account, center=(1332,820), inner_text= , title=Twitter account, url='https://twitter.com/wwzeng1'
	[472] link LinkedIn profile, center=(1360,820), inner_text= , title=LinkedIn profile, url='https://linkedin.com/in/william-zeng'
	StaticText Similar Jobs
	image Hiro Systems, url='https://bookface-images.s3.amazonaws.com/small_logos/96d6585dd5c6970a5bdb324b4a4d6e71b977b149.png'
	[480] link Hiro Systems, center=(1334,985), url='https://www.ycombinator.com/companies/hiro-systems'
	[482] link Blockchain Engineer, center=(1356,1001), url='https://www.ycombinator.com/companies/hiro-systems/jobs/QXDWQ9l-blockchain-engineer'
	image Kombo, url='https://bookface-images.s3.amazonaws.com/small_logos/1ea96f644bc25cfeaa1198b5db442e95f63b56b4.png'
	[487] link Kombo, center=(1318,1037), url='https://www.ycombinator.com/companies/kombo'
	link Haven't found what you are looking for? Operations/Engineering/Product, url='https://www.ycombinator.com/companies/kombo/jobs/vyzsAci-haven-t-found-what-you-are-looking-for-operations-engineering-product'
	image Morphle Labs, url='https://bookface-images.s3.amazonaws.com/small_logos/c76097b716ca7b82f6b26beb694f3ab12e87aab6.png'
	link Morphle Labs, url='https://www.ycombinator.com/companies/morphle-labs'
	link Senior Software Engineer, url='https://www.ycombinator.com/companies/morphle-labs/jobs/N2I8gal-senior-software-engineer'
	image Dripos, url='https://bookface-images.s3.amazonaws.com/small_logos/ba1d88383fb670f4bece6ddacd19dd9b25e972cc.png'
	link Dripos, url='https://www.ycombinator.com/companies/dripos'
	link Software Engineer - Full Stack, url='https://www.ycombinator.com/companies/dripos/jobs/W4A72t9-software-engineer-full-stack'
	image FlutterFlow, url='https://bookface-images.s3.amazonaws.com/small_logos/3df7b6e09c2fda2538b0426203b84e4e92ca7471.png'
	link FlutterFlow, url='https://www.ycombinator.com/companies/flutterflow'
	link Software Engineer - AI (United States), url='https://www.ycombinator.com/companies/flutterflow/jobs/UnyHKVJ-software-engineer-ai-united-states'
	image Coba, url='https://bookface-images.s3.amazonaws.com/small_logos/064ab4995b234ee61187e6d755a27338f57c5c90.png'
	link Coba, url='https://www.ycombinator.com/companies/coba'
	link Coba.ai Hiring | Full-stack developers for US-MX cross-border fintech (remote US or MX), url='https://www.ycombinator.com/companies/coba/jobs/9wju4KE-coba-ai-hiring-full-stack-developers-for-us-mx-cross-border-fintech-remote-us-or-mx'
	image Converge, url='https://bookface-images.s3.amazonaws.com/small_logos/6ddaa5bebf2aae550b90599e16a46dc1f877c755.png'
	link Converge, url='https://www.ycombinator.com/companies/converge'
	link Founding Engineer (#2 at $1M+ ARR), url='https://www.ycombinator.com/companies/converge/jobs/GQWZ40Z-founding-engineer-2-at-1m-arr'
	image Latent, url='https://bookface-images.s3.amazonaws.com/small_logos/d464e72e759603ce78169d56b1ef679252bf2dae.png'
	link Latent, url='https://www.ycombinator.com/companies/latent'
	link Senior Software Engineer (Full Stack), url='https://www.ycombinator.com/companies/latent/jobs/KqOXaXA-senior-software-engineer-full-stack'
	image AviaryAI, url='https://bookface-images.s3.amazonaws.com/small_logos/c883569550177f7700c6efba769c869c5d530759.png'
	link AviaryAI, url='https://www.ycombinator.com/companies/aviaryai'
	link Full Stack Software Engineer, url='https://www.ycombinator.com/companies/aviaryai/jobs/dbF1b7S-full-stack-software-engineer'
	image HippoBuild, url='https://bookface-images.s3.amazonaws.com/small_logos/a5b7abe9b8dc9591204def8329e61e695322cd8e.png'
	link HippoBuild, url='https://www.ycombinator.com/companies/hippobuild'
	link FlutterFlow & Firebase Engineer, url='https://www.ycombinator.com/companies/hippobuild/jobs/LfFcPQy-flutterflow-firebase-engineer'
	image Codes Health, url='https://bookface-images.s3.amazonaws.com/small_logos/ae2e103cef868d10d11f8eda1c9371448e8a4640.png'
	link Codes Health, url='https://www.ycombinator.com/companies/codes-health'
	link Founding Engineer, url='https://www.ycombinator.com/companies/codes-health/jobs/RK8DNqG-founding-engineer'
	image InspectMind AI, url='https://bookface-images.s3.amazonaws.com/small_logos/380201f9cadb6a3d51cb0328080b2378d425269f.png'
	link InspectMind AI, url='https://www.ycombinator.com/companies/inspectmind-ai'
	link Software Engineer, url='https://www.ycombinator.com/companies/inspectmind-ai/jobs/rPuRKf1-software-engineer'
	image Mino Games, url='https://bookface-images.s3.amazonaws.com/small_logos/573373ab6401e76024bab0260b4ba1cd64b7a1fe.png'
	link Mino Games, url='https://www.ycombinator.com/companies/mino-games'
	link Game Developer, url='https://www.ycombinator.com/companies/mino-games/jobs/6Toj1IT1z-game-developer'
	image PermitFlow, url='https://bookface-images.s3.amazonaws.com/small_logos/7ded490920c3d66fa08b0a9da3269ee21d78daff.png'
	link PermitFlow, url='https://www.ycombinator.com/companies/permitflow'
	link Staff Software Engineer, url='https://www.ycombinator.com/companies/permitflow/jobs/sh5wkwG-staff-software-engineer'
	image Eight Sleep, url='https://bookface-images.s3.amazonaws.com/small_logos/b649c0ed7300661389c61da3478d9e510a6ef517.png'
	link Eight Sleep, url='https://www.ycombinator.com/companies/eight-sleep'
	link Full Stack Engineer - Web Focus, url='https://www.ycombinator.com/companies/eight-sleep/jobs/slZD7gD-full-stack-engineer-web-focus'
	image Numeral, url='https://bookface-images.s3.amazonaws.com/small_logos/c0f30c988fde8ec60cc14e8c5cf656b62cd6d35d.png'
	link Numeral, url='https://www.ycombinator.com/companies/numeral'
	link Software Engineer (Product), url='https://www.ycombinator.com/companies/numeral/jobs/HLVIyAP-software-engineer-product'
	image 222, url='https://bookface-images.s3.amazonaws.com/small_logos/2e693471ebf0087cdb9edcdba2657ef0066b1a88.png'
	link 222, url='https://www.ycombinator.com/companies/222'
	link Full-Stack Software Engineer, url='https://www.ycombinator.com/companies/222/jobs/QlmT2Pl-full-stack-software-engineer'
	image Artisan, url='https://bookface-images.s3.amazonaws.com/small_logos/3aa68965eefe42dc96e16073740dae2087ad188f.png'
	link Artisan, url='https://www.ycombinator.com/companies/artisan'
	link Full Stack Engineer, url='https://www.ycombinator.com/companies/artisan/jobs/BgWVElZ-full-stack-engineer'
	image Olympian Motors, url='https://bookface-images.s3.amazonaws.com/small_logos/295a828c811272d963b3ebd52d4f226bb1023827.png'
	link Olympian Motors, url='https://www.ycombinator.com/companies/olympian-motors'
	link Head of Vehicle Engineering (Full-Stack), url='https://www.ycombinator.com/companies/olympian-motors/jobs/cWz8Glx-head-of-vehicle-engineering-full-stack'
	image autarc, url='https://bookface-images.s3.amazonaws.com/small_logos/c6f422aa332e520cce9d631b8dfbcdfb14375c6e.png'
	link autarc, url='https://www.ycombinator.com/companies/autarc'
	link Senior Fullstack Engineer (React, Supabase), url='https://www.ycombinator.com/companies/autarc/jobs/bQKx2VT-senior-fullstack-engineer-react-supabase'
	contentinfo Footer
		heading Footer
		link Y Combinator Y Combinator, url='https://www.ycombinator.com/'
			image Y Combinator, url='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAQEAAAEBCAMAAABPMuDPAAAAQlBMVEXyZSLyZSLyZSLyZSLyZSL6roH91br2ilD+6tr4nGn0eDf7wp3+9e3zbyz3k1z0gUP7uI/5pXX+38n8y6z////yZSKuMvVfAAAABXRSTlOAQMBgICelMzEAAAOgSURBVHhe5MABDQAAAIIw3eifmSB8vA3Zt5vcuGEgCsLeUBSpnxnb4f2vmn068xK5Z8FuFQ8gCB9q80Dw42Pc+3y8UQABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQACBR7GnuAF6MafNKnDsv+xx/+1mv3nOKjDKXwRWbwIWYJl4F6wigvclUCcWaCKCeRKwAtNFoBN4TC1wigjelMA2+S5YRATv+VyfXKC+NYIqEphVQEfgT2Dv0ws8VAT+BEqAXbCJCPwJHAEEuorAn0AAARGBO4H1CCFw7O+JoArIuQVGERH4EhgBBFQE/gQmF9ARnP4EljG5gB5Iiz+BGkBAreTqTyCAgIzAnUAogdMbwSIm0cQCeiAtvgR6MIEqInAkEEBARuBKIJzAwxOB5SsBb822n0dQxSoOJNBFBI4EAgmMp4jAkUAAATWQ6s8SaEFvz8vPIqhiWAYQcEQgEogqMD5FBBcS+BrBBPRAqtcTqIEF2vUIqsgmgIAjApFAaIF6NQKbwPcIKKAHUr2WQI8k4I+gilUcQMARgUggvEC/EkEzAM8E7wu2CxGsdhJFEvBH0MQqDiegV3J1JBBQ4NhFBDqBzyTvC4qIQCawjgwCOgKdQIstoFdydSQQRcD2rSNoVimRQPuPCFaLFF1AR7A5EggloK/BdAIZBPRVqE6ghxLwR7BaoBQCOgKdQDqBLiIQCSQSGJuIoNlJlEVAR3C8TKCkfHX7fLn+T5tASoFjf9X6YmlSCozyYvxVO4kSCegI1r8n0FIJ6IF0igQyCej9txiWZAI6gsfoViWxwPiy+2gzqzi1QLUR2ATSCeiBtBuSfAI6AjsWkguM738I9PQC3ZFADoGxKYC95xfQEZRxA4FRRALHLQSOXSSQXkBHsB75BXQEbWQV0APJruL8AmMVCaQW0BEsI5uAXsn21FsJVJFAZgH9juJmAsVOorsLlLsJIIAAAggggAACCCCAAAIIIIAAAggggAACCCCAAAIIIIAAAggggAACCCCAAAIIIIAAAggggAACCCCAAAIIIIAAAm3547QAAoGPFkAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBBBAAAEEEEAAAQQQQAABBH6XAwc0AAAAAME2+ncWxOXNAI6Cs14i3Db7AAAAAElFTkSuQmCC'
		heading Programs
		list
			listitem
				link YC Program, url='https://www.ycombinator.com/about'
			listitem
				link Startup School, url='https://startupschool.org/'
			listitem
				link Work at a Startup, url='https://www.ycombinator.com/jobs'
			listitem
				link Co-Founder Matching, url='https://www.ycombinator.com/cofounder-matching'
		heading Company
		list
			listitem
				link YC Blog, url='https://www.ycombinator.com/blog'
			listitem
				link Contact, url='https://www.ycombinator.com/contact'
			listitem
				link Press, url='https://www.ycombinator.com/press'
			listitem
				link People, url='https://www.ycombinator.com/people'
			listitem
				link Careers, url='https://www.ycombinator.com/careers'
			listitem
				link Privacy Policy, url='https://www.ycombinator.com/legal#privacy'
			listitem
				link Notice at Collection, url='https://www.ycombinator.com/legal#notice-at-collection'
			listitem
				link Security, url='https://www.ycombinator.com/security'
			listitem
				link Terms of Use, url='https://www.ycombinator.com/legal#tou'
		heading Resources
		list
			listitem
				link Startup Directory, url='https://www.ycombinator.com/companies'
			listitem
				link Startup Library, url='https://www.ycombinator.com/library'
			listitem
				link Investors, url='https://www.ycombinator.com/investors'
			listitem
				link SAFE, url='https://www.ycombinator.com/documents'
			listitem
				link Hacker News, url='https://news.ycombinator.com/'
			listitem
				link Launch YC, url='https://www.ycombinator.com/launches'
			listitem
				link YC Deals, url='https://deals.ycombinator.com/'
		heading Make something people want.
		link Apply, url='https://www.ycombinator.com/apply'
		link Twitter, url='https://twitter.com/ycombinator'
		link Facebook, url='https://www.facebook.com/YCombinator/'
		link Instagram, url='https://www.instagram.com/ycombinator'
		link LinkedIn, url='https://www.linkedin.com/school/y-combinator/'
		link Youtube, url='https://www.youtube.com/c/ycombinator'
		paragraph
			StaticText © 2024 Y Combinator
```
</details>



```
RootWebArea Founding Engineer at Sweep | Y Combinator, focused, url='https://www.ycombinator.com/companies/sweep/jobs/8dUn406-founding-engineer'
	dialog Apply to Sweep, modal=True
		image company logo, url='https://bookface-images.s3.us-west-2.amazonaws.com/logos/9ef82faaeebb3ccab332969ef717850b83ffacae.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIAQC4NIECAGN7TU2GI%2F20250105%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250105T200333Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEoaCXVzLXdlc3QtMiJIMEYCIQDxGWcNn8HwRnRQD5hbgsKrkPkjlfPVBGsGvQw%2Fp%2BlWxAIhANS6jtRQdPcj7ALnlZrgz7M%2FvvL9eaBwU6UXXKfS2yS5KuUDCDMQABoMMDA2MjAxODExMDcyIgwHOxl0tRm%2BexVO86oqwgO%2B258sMUwqWzYLz%2F8LI5M55%2B%2Fu1ZQEnMUaToa0HVLgTxycLfXoWbs6VF3i3c5mYltb0w6LrC22Nv2HWgTi3JTQYbbRBuCIfmB7AgxjUuMB0WHXASZRyB%2FqvWSyIkpOdr0tD%2BFdFDNRGjNwo%2BepJmHK1F8IYWgAcyFX3VCh1L%2B%2F5%2BgDlcZbqMc2x8uUdDMk8XVZq45pMOAueY%2BaynOhC5XEB8cApZnuGloXhaaiImf1%2BMKAgxmgEfoQ47pMt7Fgk%2BpOvEM5zndxor%2FMsOGW5ytQ%2Fexkwu5b9EVCifALACCehI22Q%2FPS4HW1TQgip73oErbjmacoos9mceWghW3lzxm2NOvNW7Ox7FW3LwiZfBO%2BWH61FppLLyzdfTdqbPFtuC8ZHD0lxe7tTJcjXZCH0ruxVUaabU5ns7jhgi3XGvoBZWmd3%2FYXkj7%2Bq8FtBkacHa0dyshUSG%2Fhc3WYI35JoVlHv7q%2B7VlnJ%2FNph5XI33IHPzozak8YXdp%2F0gMHWuSDbUmRIrswS%2BIhZkRysuK1zkLrM%2FCr3Vj73mVhoaLIAmJYYggilHxoBc66mnRwbR0NrB%2BRV22d%2BnFIHFsDlBLIyRVLF9ow0JHruwY6pAG6kcuj3tPZkxlQuj%2B8S2AWEJ6mUUwpqOL%2FIwCzV42BHg5s2aKJ4DWNJ6EHT2pRSbuqZHpzKyII6eAjPQiy3TJ7Nw%2B%2B3jaEt1tIHYfiyhG6yMOxMreunhMKizBP2FBrkE%2BtNtMOc7YppM9OGduDwqb77ijRQVVbPfqrPt8EGoVvQwV%2Bo%2FTefASZtBY1muTy0AEhzZ0wiXriBOXSqFCPVm66TFv05Q%3D%3D&X-Amz-SignedHeaders=host&X-Amz-Signature=80ba1f69914fcaaeea09a4207781a2fc8f41157ecc189ea6f607104fca6c9a63'
		paragraph
			StaticText AI-powered Python junior developer for software teams
```
<details><summary>Show more</summary>

```
		paragraph
			StaticText Founding Engineer
		paragraph
			StaticText $130K - $170K
			StaticText /
			StaticText 0.50% - 2.00%
		image, url='https://bookface-images.s3.us-west-2.amazonaws.com/avatars/d02bf268302d4c204515d4fc779599313b25875c.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIAQC4NIECAGN7TU2GI%2F20250105%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250105T200333Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEoaCXVzLXdlc3QtMiJIMEYCIQDxGWcNn8HwRnRQD5hbgsKrkPkjlfPVBGsGvQw%2Fp%2BlWxAIhANS6jtRQdPcj7ALnlZrgz7M%2FvvL9eaBwU6UXXKfS2yS5KuUDCDMQABoMMDA2MjAxODExMDcyIgwHOxl0tRm%2BexVO86oqwgO%2B258sMUwqWzYLz%2F8LI5M55%2B%2Fu1ZQEnMUaToa0HVLgTxycLfXoWbs6VF3i3c5mYltb0w6LrC22Nv2HWgTi3JTQYbbRBuCIfmB7AgxjUuMB0WHXASZRyB%2FqvWSyIkpOdr0tD%2BFdFDNRGjNwo%2BepJmHK1F8IYWgAcyFX3VCh1L%2B%2F5%2BgDlcZbqMc2x8uUdDMk8XVZq45pMOAueY%2BaynOhC5XEB8cApZnuGloXhaaiImf1%2BMKAgxmgEfoQ47pMt7Fgk%2BpOvEM5zndxor%2FMsOGW5ytQ%2Fexkwu5b9EVCifALACCehI22Q%2FPS4HW1TQgip73oErbjmacoos9mceWghW3lzxm2NOvNW7Ox7FW3LwiZfBO%2BWH61FppLLyzdfTdqbPFtuC8ZHD0lxe7tTJcjXZCH0ruxVUaabU5ns7jhgi3XGvoBZWmd3%2FYXkj7%2Bq8FtBkacHa0dyshUSG%2Fhc3WYI35JoVlHv7q%2B7VlnJ%2FNph5XI33IHPzozak8YXdp%2F0gMHWuSDbUmRIrswS%2BIhZkRysuK1zkLrM%2FCr3Vj73mVhoaLIAmJYYggilHxoBc66mnRwbR0NrB%2BRV22d%2BnFIHFsDlBLIyRVLF9ow0JHruwY6pAG6kcuj3tPZkxlQuj%2B8S2AWEJ6mUUwpqOL%2FIwCzV42BHg5s2aKJ4DWNJ6EHT2pRSbuqZHpzKyII6eAjPQiy3TJ7Nw%2B%2B3jaEt1tIHYfiyhG6yMOxMreunhMKizBP2FBrkE%2BtNtMOc7YppM9OGduDwqb77ijRQVVbPfqrPt8EGoVvQwV%2Bo%2FTefASZtBY1muTy0AEhzZ0wiXriBOXSqFCPVm66TFv05Q%3D%3D&X-Amz-SignedHeaders=host&X-Amz-Signature=5fa61483ce0935962a1056a1b2f922d9fb8ce17e97fa8093e1727fdfb5a5f47a'
		paragraph
			StaticText Kevin Lu
		paragraph
			StaticText Founder
		image, url='https://bookface-images.s3.us-west-2.amazonaws.com/avatars/6ea14a52703b3d5d1bc15d010a715f0a74723845.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIAQC4NIECAGN7TU2GI%2F20250105%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250105T200333Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEoaCXVzLXdlc3QtMiJIMEYCIQDxGWcNn8HwRnRQD5hbgsKrkPkjlfPVBGsGvQw%2Fp%2BlWxAIhANS6jtRQdPcj7ALnlZrgz7M%2FvvL9eaBwU6UXXKfS2yS5KuUDCDMQABoMMDA2MjAxODExMDcyIgwHOxl0tRm%2BexVO86oqwgO%2B258sMUwqWzYLz%2F8LI5M55%2B%2Fu1ZQEnMUaToa0HVLgTxycLfXoWbs6VF3i3c5mYltb0w6LrC22Nv2HWgTi3JTQYbbRBuCIfmB7AgxjUuMB0WHXASZRyB%2FqvWSyIkpOdr0tD%2BFdFDNRGjNwo%2BepJmHK1F8IYWgAcyFX3VCh1L%2B%2F5%2BgDlcZbqMc2x8uUdDMk8XVZq45pMOAueY%2BaynOhC5XEB8cApZnuGloXhaaiImf1%2BMKAgxmgEfoQ47pMt7Fgk%2BpOvEM5zndxor%2FMsOGW5ytQ%2Fexkwu5b9EVCifALACCehI22Q%2FPS4HW1TQgip73oErbjmacoos9mceWghW3lzxm2NOvNW7Ox7FW3LwiZfBO%2BWH61FppLLyzdfTdqbPFtuC8ZHD0lxe7tTJcjXZCH0ruxVUaabU5ns7jhgi3XGvoBZWmd3%2FYXkj7%2Bq8FtBkacHa0dyshUSG%2Fhc3WYI35JoVlHv7q%2B7VlnJ%2FNph5XI33IHPzozak8YXdp%2F0gMHWuSDbUmRIrswS%2BIhZkRysuK1zkLrM%2FCr3Vj73mVhoaLIAmJYYggilHxoBc66mnRwbR0NrB%2BRV22d%2BnFIHFsDlBLIyRVLF9ow0JHruwY6pAG6kcuj3tPZkxlQuj%2B8S2AWEJ6mUUwpqOL%2FIwCzV42BHg5s2aKJ4DWNJ6EHT2pRSbuqZHpzKyII6eAjPQiy3TJ7Nw%2B%2B3jaEt1tIHYfiyhG6yMOxMreunhMKizBP2FBrkE%2BtNtMOc7YppM9OGduDwqb77ijRQVVbPfqrPt8EGoVvQwV%2Bo%2FTefASZtBY1muTy0AEhzZ0wiXriBOXSqFCPVm66TFv05Q%3D%3D&X-Amz-SignedHeaders=host&X-Amz-Signature=c633adb5e95a7c15c0bd516ddcc3e1be77419aed44a773c3268de95b4f043f80'
		paragraph
			StaticText William Zeng
		paragraph
			StaticText Founder
		heading Apply to Sweep
		paragraph
			StaticText Get directly in touch with the team.
		[744] textbox First Name *, center=(1086,282), contenteditable=True, focused, type=text
		[746] textbox Last Name *, center=(1086,332), contenteditable=True, type=text
		[748] textbox Email Address *, center=(1086,382), contenteditable=True, type=email
		[750] textbox Linkedin URL *, center=(1086,432), contenteditable=True, type=text
		[753] combobox Current location*, center=(1086,482), autocomplete=off, contenteditable=True, expanded=False, hasPopup='listbox', type=text
		paragraph
			StaticText Are you legally authorized to work in the United States?
		group
			[757] radio Yes, center=(916,556), checked='false', contenteditable=True, type=radio
			LabelText
				StaticText Yes
			[759] radio No, center=(977,556), checked='false', contenteditable=True, type=radio
			LabelText
				StaticText No
		paragraph
			StaticText Do you or will you require sponsorship for a US employment visa?
		group
			[764] radio Yes, center=(916,644), checked='false', contenteditable=True, type=radio
			LabelText
				StaticText Yes
			[766] radio No, center=(977,644), checked='false', contenteditable=True, type=radio
			LabelText
				StaticText No
		LabelText
			StaticText Upload Resume
		[772] button Upload Resume value='No file chosen', center=(1145,688), contenteditable=True, type=file
		[774] textbox What interests you about Sweep?, center=(1086,780), contenteditable=True, type=text
		[776] button Send Message, center=(1200,884), type=submit
		[777] button Close, center=(1094,884), type=button
```
</details>

**Reasoning for action:** By clicking on the 'Apply to role' button, I am taken to the application modal where I can provide my personal information and upload my resume, which fulfills the user story requirement to apply for the Founding Engineer position. This action directly progresses towards the user's goal of exploring job opportunities and completing the application.

**Action:** click(411) # Click on the Apply to role button to start the application process for the Founding Engineer position.

**Change Description:** After clicking the 'Apply to role' button, a modal dialogue titled 'Apply to Sweep' appeared, prompting the user to input their personal information and upload their resume. This dialogue contains structured fields for the applicant's first name, last name, email address, LinkedIn profile URL, current location, and questions regarding work authorization, as well as a button to send the application.

**Screenshot before:****Screenshot after:**---


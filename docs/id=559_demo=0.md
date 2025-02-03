# Task

**User Story about Exploring Tusk AI**

As a prospective customer,
I explore the product offerings and understand how Tusk AI can improve my development workflow,
so that I can make an informed decision about using the service for enhancing our testing processes.

**Success definition:** Given I am on the main Tusk AI website
When I click on the Products button and navigate to the About Us section, then click on the Read docs link
Then I should see relevant information about the company and the automated tests overview document.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.usetusk.ai/

https://www.usetusk.ai/

**Content (before/after):** 

```
RootWebArea Tusk: AI unit tests to prevent bugs caused by edge cases - Tusk, focused, url='https://www.usetusk.ai/'
	banner
		[38] link home, center=(441,51), url='https://www.usetusk.ai/'
			image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673befa76c897580685a931a_tusk-full-logo.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[48] button Products , center=(696,50), expanded=False, hasPopup='menu', inner_text=Products

				paragraph
			[59] button About Us , center=(835,50), expanded=False, hasPopup='menu', inner_text=About Us

				paragraph
			[71] link Pricing, center=(953,51), url='https://www.usetusk.ai/pricing'
			[72] link Docs, center=(1045,51), url='https://docs.usetusk.ai/automated-tests/overview'
			[73] link Blog, center=(1128,51), url='https://blog.usetusk.ai/'
		[76] link Sign in, center=(1314,51), url='https://app.usetusk.ai/app'
		[77] link Talk to our founders, center=(1456,51), url='https://cal.com/marceltan/demo'
	image Badge saying "Backed by Y Combinator", url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d1730dfc7f674050c0f4b_Black.svg'
	image Badge for #1 SaaS Product the Week on Product Hunt, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d2c1d6ed417c53f792f51_product-hunt-badge-dark.svg'
	heading Increase feature coverage with high impact tests
	paragraph
		StaticText Generate unit and integration tests with codebase context to catch edge cases that your engineers are missing
	[101] link Get access , center=(450,687), inner_text=Get access
, url='https://tally.so/r/nP29pQ'
	[103] link Read docs , center=(611,687), inner_text=Read docs
, url='https://docs.usetusk.ai/automated-tests/overview'
	image Image Banner, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf1768e06d561b954f5f7_pr-check-hero-image-dark-p-1600.png'
	paragraph
		StaticText Trusted by engineers at fast-growing companies
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/678051f8d7910199189cf147_deeplearning-ai-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/678052eeec28faeccfc8e556_savvy-wealth-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bf9787bc5618d15217faf_wefunder-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c01af5f3addba8465aa7f_replo-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c036f04cb435e9b18f9bd_Dark%20Mode%3DYes.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c010e4e3b890efff73aa2_fondo-white-logo-p-500.png'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bf9c2da166a45cf21a696_prefix-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c0345da9d6db8c1c20df2_genie-logo-white.svg'
	image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bfded5f3addba8461b79e_tusk-t-logo.svg'
	heading Tusk runs on your PRs to generate happy path and edge case tests
	paragraph
		StaticText Our AI-powered tool reads your codebase and docs to suggest test cases, allowing you to ship faster but safer.
	heading Embedded into your workflow
	paragraph
		StaticText Tusk sits within GitHub and your CI/CD pipeline so that you don't have to change the way you work
	list
		listitem
			article
				image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b88b9/673be64804f5ed85a91b89da_65f8312a12341cfa0dfa2fff_bar%20chart.svg'
			link Push in one click, url='https://www.usetusk.ai/#'
			paragraph
				StaticText View individual test cases before clicking one button to add Tusk-generated tests to a PR's branch.
		listitem
			article
				image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b88b9/673be64804f5ed85a91b89fa_65f8312a12341cfa0dfa2fbd_time%20add.svg'
			link Mock services, url='https://www.usetusk.ai/#'
			paragraph
				StaticText Tusk takes in context from existing tests to mock services and data structures required to generate integration tests.
		listitem
			article
				image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b88b9/673be64804f5ed85a91b89fb_65f8312a12341cfa0dfa2fe8_pie%20chart.svg'
			link Non-blocking check, url='https://www.usetusk.ai/#'
			paragraph
				StaticText You decide whether to include Tusk's tests before merging a PR. We're a quiet helper in the background.
	heading Build a testing culture that goes beyond writing tests for the sake of coverage
	image Image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf2af8f43168ad20adca0_pr-add-to-branch-dark-squarelike-p-800.png'
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673be64804f5ed85a91b88a1_Frame%20(1).svg'
	StaticText PR #1682
	paragraph
		StaticText feat(subscription-charges): add logic to calculate monthly api usage
	StaticText Engineer
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf5903430cd2de7f74025_marcel_IMG_8787new_square-p-500.jpg'
	StaticText add logic to calculate monthly api usage
	paragraph
		StaticText Commented 2 hours ago
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf5903430cd2de7f74025_marcel_IMG_8787new_square-p-500.jpg'
	StaticText add unit tests for calculation
	paragraph
		StaticText Commented 2 hours ago
	StaticText Tusk
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf5903430cd2de7f74025_marcel_IMG_8787new_square-p-500.jpg'
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bfded5f3addba8461b79e_tusk-t-logo.svg'
	StaticText Add tests to monthlyApiUsage
	paragraph
		StaticText Commented 2 hours ago
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d026c1f857f85f4e11e26_github-success-icon.png'
	StaticText All checks have passed
	paragraph
		StaticText 5 successful checks
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673be64804f5ed85a91b88a4_Frame%2027.webp'
	heading Merge PRs 25% faster with peace of mind
	paragraph
		StaticText Unlike code review tools, Tusk runs its tests and determines if failures are caused by a bug in the code. This way we give you only targeted suggestions that prevent bugs before deployment.
	heading Ready to build a strong testing culture?
	link Get access , url='https://tally.so/r/nP29pQ'
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf1768e06d561b954f5f7_pr-check-hero-image-dark-p-1600.png'
	link, url='https://www.usetusk.ai/'
		image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673befa76c897580685a931a_tusk-full-logo.svg'
	StaticText Pages
	link Pricing, url='https://www.usetusk.ai/pricing'
	link Book a Demo, url='https://www.usetusk.ai/book-a-demo'
	link FAQ, url='https://www.usetusk.ai/faq'
	StaticText Resources
	link Docs, url='https://docs.usetusk.ai/automated-tests/overview'
	link Blog, url='https://blog.usetusk.ai/'
	link Privacy, url='https://www.usetusk.ai/privacy'
	link Terms, url='https://www.usetusk.ai/terms'
	heading Subscribe to newsletter
	StaticText Stay current with all things Tusk
	form Email Form
		textbox Email, required
		button 
	link, url='https://www.linkedin.com/company/usetusk'
		image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d1cd8d5b73a24148d6c46_linkedin-vector-icon-white.svg'
	link, url='https://twitter.com/usetusk'
		image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d1eb6b208d9b76fc45012_twitter-vector-icon-white.png'
	link, url='https://www.youtube.com/@MarcelTusk'
		image, url='https://cdn.prod.website-files.com/65f8312a12341cfa0dfa2f49/65f8312a12341cfa0dfa2fc7_youtube.svg'
	StaticText © 2025 Tusk AI, Inc.. All rights reserved.
```
</details>



```
RootWebArea Tusk: AI unit tests to prevent bugs caused by edge cases - Tusk, focused, url='https://www.usetusk.ai/'
	banner
		[38] link home, center=(441,51), url='https://www.usetusk.ai/'
			image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673befa76c897580685a931a_tusk-full-logo.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[48] button Products , center=(696,50), expanded=False, focused, hasPopup='menu', inner_text=Products

				paragraph
			[59] button About Us , center=(835,50), expanded=False, hasPopup='menu', inner_text=About Us

				paragraph
			[71] link Pricing, center=(953,51), url='https://www.usetusk.ai/pricing'
			[72] link Docs, center=(1045,51), url='https://docs.usetusk.ai/automated-tests/overview'
			[73] link Blog, center=(1128,51), url='https://blog.usetusk.ai/'
		[76] link Sign in, center=(1314,51), url='https://app.usetusk.ai/app'
		[77] link Talk to our founders, center=(1456,51), url='https://cal.com/marceltan/demo'
	image Badge saying "Backed by Y Combinator", url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d1730dfc7f674050c0f4b_Black.svg'
	image Badge for #1 SaaS Product the Week on Product Hunt, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d2c1d6ed417c53f792f51_product-hunt-badge-dark.svg'
	heading Increase feature coverage with high impact tests
	paragraph
		StaticText Generate unit and integration tests with codebase context to catch edge cases that your engineers are missing
	[101] link Get access , center=(450,687), inner_text=Get access
, url='https://tally.so/r/nP29pQ'
	[103] link Read docs , center=(611,687), inner_text=Read docs
, url='https://docs.usetusk.ai/automated-tests/overview'
	image Image Banner, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf1768e06d561b954f5f7_pr-check-hero-image-dark-p-1600.png'
	paragraph
		StaticText Trusted by engineers at fast-growing companies
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/678051f8d7910199189cf147_deeplearning-ai-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/678052eeec28faeccfc8e556_savvy-wealth-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bf9787bc5618d15217faf_wefunder-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c01af5f3addba8465aa7f_replo-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c036f04cb435e9b18f9bd_Dark%20Mode%3DYes.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c010e4e3b890efff73aa2_fondo-white-logo-p-500.png'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bf9c2da166a45cf21a696_prefix-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c0345da9d6db8c1c20df2_genie-logo-white.svg'
	image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bfded5f3addba8461b79e_tusk-t-logo.svg'
	heading Tusk runs on your PRs to generate happy path and edge case tests
	paragraph
		StaticText Our AI-powered tool reads your codebase and docs to suggest test cases, allowing you to ship faster but safer.
	heading Embedded into your workflow
	paragraph
		StaticText Tusk sits within GitHub and your CI/CD pipeline so that you don't have to change the way you work
	list
		listitem
			article
				image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b88b9/673be64804f5ed85a91b89da_65f8312a12341cfa0dfa2fff_bar%20chart.svg'
			link Push in one click, url='https://www.usetusk.ai/#'
			paragraph
				StaticText View individual test cases before clicking one button to add Tusk-generated tests to a PR's branch.
		listitem
			article
				image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b88b9/673be64804f5ed85a91b89fa_65f8312a12341cfa0dfa2fbd_time%20add.svg'
			link Mock services, url='https://www.usetusk.ai/#'
			paragraph
				StaticText Tusk takes in context from existing tests to mock services and data structures required to generate integration tests.
		listitem
			article
				image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b88b9/673be64804f5ed85a91b89fb_65f8312a12341cfa0dfa2fe8_pie%20chart.svg'
			link Non-blocking check, url='https://www.usetusk.ai/#'
			paragraph
				StaticText You decide whether to include Tusk's tests before merging a PR. We're a quiet helper in the background.
	heading Build a testing culture that goes beyond writing tests for the sake of coverage
	image Image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf2af8f43168ad20adca0_pr-add-to-branch-dark-squarelike-p-800.png'
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673be64804f5ed85a91b88a1_Frame%20(1).svg'
	StaticText PR #1682
	paragraph
		StaticText feat(subscription-charges): add logic to calculate monthly api usage
	StaticText Engineer
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf5903430cd2de7f74025_marcel_IMG_8787new_square-p-500.jpg'
	StaticText add logic to calculate monthly api usage
	paragraph
		StaticText Commented 2 hours ago
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf5903430cd2de7f74025_marcel_IMG_8787new_square-p-500.jpg'
	StaticText add unit tests for calculation
	paragraph
		StaticText Commented 2 hours ago
	StaticText Tusk
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf5903430cd2de7f74025_marcel_IMG_8787new_square-p-500.jpg'
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bfded5f3addba8461b79e_tusk-t-logo.svg'
	StaticText Add tests to monthlyApiUsage
	paragraph
		StaticText Commented 2 hours ago
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d026c1f857f85f4e11e26_github-success-icon.png'
	StaticText All checks have passed
	paragraph
		StaticText 5 successful checks
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673be64804f5ed85a91b88a4_Frame%2027.webp'
	heading Merge PRs 25% faster with peace of mind
	paragraph
		StaticText Unlike code review tools, Tusk runs its tests and determines if failures are caused by a bug in the code. This way we give you only targeted suggestions that prevent bugs before deployment.
	heading Ready to build a strong testing culture?
	link Get access , url='https://tally.so/r/nP29pQ'
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf1768e06d561b954f5f7_pr-check-hero-image-dark-p-1600.png'
	link, url='https://www.usetusk.ai/'
		image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673befa76c897580685a931a_tusk-full-logo.svg'
	StaticText Pages
	link Pricing, url='https://www.usetusk.ai/pricing'
	link Book a Demo, url='https://www.usetusk.ai/book-a-demo'
	link FAQ, url='https://www.usetusk.ai/faq'
	StaticText Resources
	link Docs, url='https://docs.usetusk.ai/automated-tests/overview'
	link Blog, url='https://blog.usetusk.ai/'
	link Privacy, url='https://www.usetusk.ai/privacy'
	link Terms, url='https://www.usetusk.ai/terms'
	heading Subscribe to newsletter
	StaticText Stay current with all things Tusk
	form Email Form
		textbox Email, required
		button 
	link, url='https://www.linkedin.com/company/usetusk'
		image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d1cd8d5b73a24148d6c46_linkedin-vector-icon-white.svg'
	link, url='https://twitter.com/usetusk'
		image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d1eb6b208d9b76fc45012_twitter-vector-icon-white.png'
	link, url='https://www.youtube.com/@MarcelTusk'
		image, url='https://cdn.prod.website-files.com/65f8312a12341cfa0dfa2f49/65f8312a12341cfa0dfa2fc7_youtube.svg'
	StaticText © 2025 Tusk AI, Inc.. All rights reserved.
```
</details>

**Reasoning for action:** By clicking on the Products button, I initiate the process of learning more about Tusk AI's offerings, which is essential for me to understand how it can improve my development workflow. This action directly aligns with the user's goal of exploring product offerings.

**Action:** click(48) # Click on the Products button to explore the product offerings.

**Change Description:** After clicking the 'Products' button, it became focused and maintained its collapsed state, indicating that the user is now exploring the product offerings while its dropdown menu is not yet expanded.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.usetusk.ai/

https://www.usetusk.ai/

**Content (before/after):** 

```
RootWebArea Tusk: AI unit tests to prevent bugs caused by edge cases - Tusk, focused, url='https://www.usetusk.ai/'
	banner
		[38] link home, center=(441,51), url='https://www.usetusk.ai/'
			image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673befa76c897580685a931a_tusk-full-logo.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[48] button Products , center=(696,50), expanded=False, focused, hasPopup='menu', inner_text=Products

				paragraph
			[59] button About Us , center=(835,50), expanded=False, hasPopup='menu', inner_text=About Us

				paragraph
			[71] link Pricing, center=(953,51), url='https://www.usetusk.ai/pricing'
			[72] link Docs, center=(1045,51), url='https://docs.usetusk.ai/automated-tests/overview'
			[73] link Blog, center=(1128,51), url='https://blog.usetusk.ai/'
		[76] link Sign in, center=(1314,51), url='https://app.usetusk.ai/app'
		[77] link Talk to our founders, center=(1456,51), url='https://cal.com/marceltan/demo'
	image Badge saying "Backed by Y Combinator", url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d1730dfc7f674050c0f4b_Black.svg'
	image Badge for #1 SaaS Product the Week on Product Hunt, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d2c1d6ed417c53f792f51_product-hunt-badge-dark.svg'
	heading Increase feature coverage with high impact tests
	paragraph
		StaticText Generate unit and integration tests with codebase context to catch edge cases that your engineers are missing
	[101] link Get access , center=(450,687), inner_text=Get access
, url='https://tally.so/r/nP29pQ'
	[103] link Read docs , center=(611,687), inner_text=Read docs
, url='https://docs.usetusk.ai/automated-tests/overview'
	image Image Banner, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf1768e06d561b954f5f7_pr-check-hero-image-dark-p-1600.png'
	paragraph
		StaticText Trusted by engineers at fast-growing companies
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/678051f8d7910199189cf147_deeplearning-ai-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/678052eeec28faeccfc8e556_savvy-wealth-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bf9787bc5618d15217faf_wefunder-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c01af5f3addba8465aa7f_replo-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c036f04cb435e9b18f9bd_Dark%20Mode%3DYes.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c010e4e3b890efff73aa2_fondo-white-logo-p-500.png'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bf9c2da166a45cf21a696_prefix-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c0345da9d6db8c1c20df2_genie-logo-white.svg'
	image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bfded5f3addba8461b79e_tusk-t-logo.svg'
	heading Tusk runs on your PRs to generate happy path and edge case tests
	paragraph
		StaticText Our AI-powered tool reads your codebase and docs to suggest test cases, allowing you to ship faster but safer.
	heading Embedded into your workflow
	paragraph
		StaticText Tusk sits within GitHub and your CI/CD pipeline so that you don't have to change the way you work
	list
		listitem
			article
				image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b88b9/673be64804f5ed85a91b89da_65f8312a12341cfa0dfa2fff_bar%20chart.svg'
			link Push in one click, url='https://www.usetusk.ai/#'
			paragraph
				StaticText View individual test cases before clicking one button to add Tusk-generated tests to a PR's branch.
		listitem
			article
				image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b88b9/673be64804f5ed85a91b89fa_65f8312a12341cfa0dfa2fbd_time%20add.svg'
			link Mock services, url='https://www.usetusk.ai/#'
			paragraph
				StaticText Tusk takes in context from existing tests to mock services and data structures required to generate integration tests.
		listitem
			article
				image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b88b9/673be64804f5ed85a91b89fb_65f8312a12341cfa0dfa2fe8_pie%20chart.svg'
			link Non-blocking check, url='https://www.usetusk.ai/#'
			paragraph
				StaticText You decide whether to include Tusk's tests before merging a PR. We're a quiet helper in the background.
	heading Build a testing culture that goes beyond writing tests for the sake of coverage
	image Image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf2af8f43168ad20adca0_pr-add-to-branch-dark-squarelike-p-800.png'
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673be64804f5ed85a91b88a1_Frame%20(1).svg'
	StaticText PR #1682
	paragraph
		StaticText feat(subscription-charges): add logic to calculate monthly api usage
	StaticText Engineer
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf5903430cd2de7f74025_marcel_IMG_8787new_square-p-500.jpg'
	StaticText add logic to calculate monthly api usage
	paragraph
		StaticText Commented 2 hours ago
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf5903430cd2de7f74025_marcel_IMG_8787new_square-p-500.jpg'
	StaticText add unit tests for calculation
	paragraph
		StaticText Commented 2 hours ago
	StaticText Tusk
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf5903430cd2de7f74025_marcel_IMG_8787new_square-p-500.jpg'
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bfded5f3addba8461b79e_tusk-t-logo.svg'
	StaticText Add tests to monthlyApiUsage
	paragraph
		StaticText Commented 2 hours ago
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d026c1f857f85f4e11e26_github-success-icon.png'
	StaticText All checks have passed
	paragraph
		StaticText 5 successful checks
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673be64804f5ed85a91b88a4_Frame%2027.webp'
	heading Merge PRs 25% faster with peace of mind
	paragraph
		StaticText Unlike code review tools, Tusk runs its tests and determines if failures are caused by a bug in the code. This way we give you only targeted suggestions that prevent bugs before deployment.
	heading Ready to build a strong testing culture?
	link Get access , url='https://tally.so/r/nP29pQ'
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf1768e06d561b954f5f7_pr-check-hero-image-dark-p-1600.png'
	link, url='https://www.usetusk.ai/'
		image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673befa76c897580685a931a_tusk-full-logo.svg'
	StaticText Pages
	link Pricing, url='https://www.usetusk.ai/pricing'
	link Book a Demo, url='https://www.usetusk.ai/book-a-demo'
	link FAQ, url='https://www.usetusk.ai/faq'
	StaticText Resources
	link Docs, url='https://docs.usetusk.ai/automated-tests/overview'
	link Blog, url='https://blog.usetusk.ai/'
	link Privacy, url='https://www.usetusk.ai/privacy'
	link Terms, url='https://www.usetusk.ai/terms'
	heading Subscribe to newsletter
	StaticText Stay current with all things Tusk
	form Email Form
		textbox Email, required
		button 
	link, url='https://www.linkedin.com/company/usetusk'
		image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d1cd8d5b73a24148d6c46_linkedin-vector-icon-white.svg'
	link, url='https://twitter.com/usetusk'
		image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d1eb6b208d9b76fc45012_twitter-vector-icon-white.png'
	link, url='https://www.youtube.com/@MarcelTusk'
		image, url='https://cdn.prod.website-files.com/65f8312a12341cfa0dfa2f49/65f8312a12341cfa0dfa2fc7_youtube.svg'
	StaticText © 2025 Tusk AI, Inc.. All rights reserved.
```
</details>



```
RootWebArea Tusk: AI unit tests to prevent bugs caused by edge cases - Tusk, focused, url='https://www.usetusk.ai/'
	banner
		[38] link home, center=(441,51), url='https://www.usetusk.ai/'
			image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673befa76c897580685a931a_tusk-full-logo.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[48] button Products , center=(696,50), expanded=False, hasPopup='menu', inner_text=Products

				paragraph
			[59] button About Us , center=(835,50), expanded=False, focused, hasPopup='menu', inner_text=About Us

				paragraph
			[71] link Pricing, center=(953,51), url='https://www.usetusk.ai/pricing'
			[72] link Docs, center=(1045,51), url='https://docs.usetusk.ai/automated-tests/overview'
			[73] link Blog, center=(1128,51), url='https://blog.usetusk.ai/'
		[76] link Sign in, center=(1314,51), url='https://app.usetusk.ai/app'
		[77] link Talk to our founders, center=(1456,51), url='https://cal.com/marceltan/demo'
	image Badge saying "Backed by Y Combinator", url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d1730dfc7f674050c0f4b_Black.svg'
	image Badge for #1 SaaS Product the Week on Product Hunt, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d2c1d6ed417c53f792f51_product-hunt-badge-dark.svg'
	heading Increase feature coverage with high impact tests
	paragraph
		StaticText Generate unit and integration tests with codebase context to catch edge cases that your engineers are missing
	[101] link Get access , center=(450,687), inner_text=Get access
, url='https://tally.so/r/nP29pQ'
	[103] link Read docs , center=(611,687), inner_text=Read docs
, url='https://docs.usetusk.ai/automated-tests/overview'
	image Image Banner, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf1768e06d561b954f5f7_pr-check-hero-image-dark-p-1600.png'
	paragraph
		StaticText Trusted by engineers at fast-growing companies
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/678051f8d7910199189cf147_deeplearning-ai-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/678052eeec28faeccfc8e556_savvy-wealth-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bf9787bc5618d15217faf_wefunder-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c01af5f3addba8465aa7f_replo-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c036f04cb435e9b18f9bd_Dark%20Mode%3DYes.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c010e4e3b890efff73aa2_fondo-white-logo-p-500.png'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bf9c2da166a45cf21a696_prefix-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c0345da9d6db8c1c20df2_genie-logo-white.svg'
	image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bfded5f3addba8461b79e_tusk-t-logo.svg'
	heading Tusk runs on your PRs to generate happy path and edge case tests
	paragraph
		StaticText Our AI-powered tool reads your codebase and docs to suggest test cases, allowing you to ship faster but safer.
	heading Embedded into your workflow
	paragraph
		StaticText Tusk sits within GitHub and your CI/CD pipeline so that you don't have to change the way you work
	list
		listitem
			article
				image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b88b9/673be64804f5ed85a91b89da_65f8312a12341cfa0dfa2fff_bar%20chart.svg'
			link Push in one click, url='https://www.usetusk.ai/#'
			paragraph
				StaticText View individual test cases before clicking one button to add Tusk-generated tests to a PR's branch.
		listitem
			article
				image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b88b9/673be64804f5ed85a91b89fa_65f8312a12341cfa0dfa2fbd_time%20add.svg'
			link Mock services, url='https://www.usetusk.ai/#'
			paragraph
				StaticText Tusk takes in context from existing tests to mock services and data structures required to generate integration tests.
		listitem
			article
				image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b88b9/673be64804f5ed85a91b89fb_65f8312a12341cfa0dfa2fe8_pie%20chart.svg'
			link Non-blocking check, url='https://www.usetusk.ai/#'
			paragraph
				StaticText You decide whether to include Tusk's tests before merging a PR. We're a quiet helper in the background.
	heading Build a testing culture that goes beyond writing tests for the sake of coverage
	image Image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf2af8f43168ad20adca0_pr-add-to-branch-dark-squarelike-p-800.png'
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673be64804f5ed85a91b88a1_Frame%20(1).svg'
	StaticText PR #1682
	paragraph
		StaticText feat(subscription-charges): add logic to calculate monthly api usage
	StaticText Engineer
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf5903430cd2de7f74025_marcel_IMG_8787new_square-p-500.jpg'
	StaticText add logic to calculate monthly api usage
	paragraph
		StaticText Commented 2 hours ago
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf5903430cd2de7f74025_marcel_IMG_8787new_square-p-500.jpg'
	StaticText add unit tests for calculation
	paragraph
		StaticText Commented 2 hours ago
	StaticText Tusk
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf5903430cd2de7f74025_marcel_IMG_8787new_square-p-500.jpg'
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bfded5f3addba8461b79e_tusk-t-logo.svg'
	StaticText Add tests to monthlyApiUsage
	paragraph
		StaticText Commented 2 hours ago
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d026c1f857f85f4e11e26_github-success-icon.png'
	StaticText All checks have passed
	paragraph
		StaticText 5 successful checks
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673be64804f5ed85a91b88a4_Frame%2027.webp'
	heading Merge PRs 25% faster with peace of mind
	paragraph
		StaticText Unlike code review tools, Tusk runs its tests and determines if failures are caused by a bug in the code. This way we give you only targeted suggestions that prevent bugs before deployment.
	heading Ready to build a strong testing culture?
	link Get access , url='https://tally.so/r/nP29pQ'
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf1768e06d561b954f5f7_pr-check-hero-image-dark-p-1600.png'
	link, url='https://www.usetusk.ai/'
		image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673befa76c897580685a931a_tusk-full-logo.svg'
	StaticText Pages
	link Pricing, url='https://www.usetusk.ai/pricing'
	link Book a Demo, url='https://www.usetusk.ai/book-a-demo'
	link FAQ, url='https://www.usetusk.ai/faq'
	StaticText Resources
	link Docs, url='https://docs.usetusk.ai/automated-tests/overview'
	link Blog, url='https://blog.usetusk.ai/'
	link Privacy, url='https://www.usetusk.ai/privacy'
	link Terms, url='https://www.usetusk.ai/terms'
	heading Subscribe to newsletter
	StaticText Stay current with all things Tusk
	form Email Form
		textbox Email, required
		button 
	link, url='https://www.linkedin.com/company/usetusk'
		image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d1cd8d5b73a24148d6c46_linkedin-vector-icon-white.svg'
	link, url='https://twitter.com/usetusk'
		image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d1eb6b208d9b76fc45012_twitter-vector-icon-white.png'
	link, url='https://www.youtube.com/@MarcelTusk'
		image, url='https://cdn.prod.website-files.com/65f8312a12341cfa0dfa2f49/65f8312a12341cfa0dfa2fc7_youtube.svg'
	StaticText © 2025 Tusk AI, Inc.. All rights reserved.
```
</details>

**Reasoning for action:** I clicked on the About Us button because it is essential to learn more about Tusk AI's mission, vision, and values, which will provide context about their product offerings. This step moves me forward in understanding how Tusk AI can enhance my development workflow, which aligns with the user story.

**Action:** click(59) # Click on the About Us button to learn more about the company.

**Change Description:** The About Us button, which was previously unfocused, became focused as a result of the click action, indicating that the user is now in a section related to company information.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.usetusk.ai/

https://docs.usetusk.ai/automated-tests/overview

**Content (before/after):** 

```
RootWebArea Tusk: AI unit tests to prevent bugs caused by edge cases - Tusk, focused, url='https://www.usetusk.ai/'
	banner
		[38] link home, center=(441,51), url='https://www.usetusk.ai/'
			image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673befa76c897580685a931a_tusk-full-logo.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[48] button Products , center=(696,50), expanded=False, hasPopup='menu', inner_text=Products

				paragraph
			[59] button About Us , center=(835,50), expanded=False, focused, hasPopup='menu', inner_text=About Us

				paragraph
			[71] link Pricing, center=(953,51), url='https://www.usetusk.ai/pricing'
			[72] link Docs, center=(1045,51), url='https://docs.usetusk.ai/automated-tests/overview'
			[73] link Blog, center=(1128,51), url='https://blog.usetusk.ai/'
		[76] link Sign in, center=(1314,51), url='https://app.usetusk.ai/app'
		[77] link Talk to our founders, center=(1456,51), url='https://cal.com/marceltan/demo'
	image Badge saying "Backed by Y Combinator", url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d1730dfc7f674050c0f4b_Black.svg'
	image Badge for #1 SaaS Product the Week on Product Hunt, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d2c1d6ed417c53f792f51_product-hunt-badge-dark.svg'
	heading Increase feature coverage with high impact tests
	paragraph
		StaticText Generate unit and integration tests with codebase context to catch edge cases that your engineers are missing
	[101] link Get access , center=(450,687), inner_text=Get access
, url='https://tally.so/r/nP29pQ'
	[103] link Read docs , center=(611,687), inner_text=Read docs
, url='https://docs.usetusk.ai/automated-tests/overview'
	image Image Banner, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf1768e06d561b954f5f7_pr-check-hero-image-dark-p-1600.png'
	paragraph
		StaticText Trusted by engineers at fast-growing companies
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/678051f8d7910199189cf147_deeplearning-ai-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/678052eeec28faeccfc8e556_savvy-wealth-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bf9787bc5618d15217faf_wefunder-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c01af5f3addba8465aa7f_replo-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c036f04cb435e9b18f9bd_Dark%20Mode%3DYes.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c010e4e3b890efff73aa2_fondo-white-logo-p-500.png'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bf9c2da166a45cf21a696_prefix-logo-white.svg'
	image Image Partners, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673c0345da9d6db8c1c20df2_genie-logo-white.svg'
	image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bfded5f3addba8461b79e_tusk-t-logo.svg'
	heading Tusk runs on your PRs to generate happy path and edge case tests
	paragraph
		StaticText Our AI-powered tool reads your codebase and docs to suggest test cases, allowing you to ship faster but safer.
	heading Embedded into your workflow
	paragraph
		StaticText Tusk sits within GitHub and your CI/CD pipeline so that you don't have to change the way you work
	list
		listitem
			article
				image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b88b9/673be64804f5ed85a91b89da_65f8312a12341cfa0dfa2fff_bar%20chart.svg'
			link Push in one click, url='https://www.usetusk.ai/#'
			paragraph
				StaticText View individual test cases before clicking one button to add Tusk-generated tests to a PR's branch.
		listitem
			article
				image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b88b9/673be64804f5ed85a91b89fa_65f8312a12341cfa0dfa2fbd_time%20add.svg'
			link Mock services, url='https://www.usetusk.ai/#'
			paragraph
				StaticText Tusk takes in context from existing tests to mock services and data structures required to generate integration tests.
		listitem
			article
				image Icon, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b88b9/673be64804f5ed85a91b89fb_65f8312a12341cfa0dfa2fe8_pie%20chart.svg'
			link Non-blocking check, url='https://www.usetusk.ai/#'
			paragraph
				StaticText You decide whether to include Tusk's tests before merging a PR. We're a quiet helper in the background.
	heading Build a testing culture that goes beyond writing tests for the sake of coverage
	image Image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf2af8f43168ad20adca0_pr-add-to-branch-dark-squarelike-p-800.png'
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673be64804f5ed85a91b88a1_Frame%20(1).svg'
	StaticText PR #1682
	paragraph
		StaticText feat(subscription-charges): add logic to calculate monthly api usage
	StaticText Engineer
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf5903430cd2de7f74025_marcel_IMG_8787new_square-p-500.jpg'
	StaticText add logic to calculate monthly api usage
	paragraph
		StaticText Commented 2 hours ago
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf5903430cd2de7f74025_marcel_IMG_8787new_square-p-500.jpg'
	StaticText add unit tests for calculation
	paragraph
		StaticText Commented 2 hours ago
	StaticText Tusk
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf5903430cd2de7f74025_marcel_IMG_8787new_square-p-500.jpg'
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673bfded5f3addba8461b79e_tusk-t-logo.svg'
	StaticText Add tests to monthlyApiUsage
	paragraph
		StaticText Commented 2 hours ago
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d026c1f857f85f4e11e26_github-success-icon.png'
	StaticText All checks have passed
	paragraph
		StaticText 5 successful checks
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673be64804f5ed85a91b88a4_Frame%2027.webp'
	heading Merge PRs 25% faster with peace of mind
	paragraph
		StaticText Unlike code review tools, Tusk runs its tests and determines if failures are caused by a bug in the code. This way we give you only targeted suggestions that prevent bugs before deployment.
	heading Ready to build a strong testing culture?
	link Get access , url='https://tally.so/r/nP29pQ'
	image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673cf1768e06d561b954f5f7_pr-check-hero-image-dark-p-1600.png'
	link, url='https://www.usetusk.ai/'
		image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673befa76c897580685a931a_tusk-full-logo.svg'
	StaticText Pages
	link Pricing, url='https://www.usetusk.ai/pricing'
	link Book a Demo, url='https://www.usetusk.ai/book-a-demo'
	link FAQ, url='https://www.usetusk.ai/faq'
	StaticText Resources
	link Docs, url='https://docs.usetusk.ai/automated-tests/overview'
	link Blog, url='https://blog.usetusk.ai/'
	link Privacy, url='https://www.usetusk.ai/privacy'
	link Terms, url='https://www.usetusk.ai/terms'
	heading Subscribe to newsletter
	StaticText Stay current with all things Tusk
	form Email Form
		textbox Email, required
		button 
	link, url='https://www.linkedin.com/company/usetusk'
		image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d1cd8d5b73a24148d6c46_linkedin-vector-icon-white.svg'
	link, url='https://twitter.com/usetusk'
		image, url='https://cdn.prod.website-files.com/673be64804f5ed85a91b883f/673d1eb6b208d9b76fc45012_twitter-vector-icon-white.png'
	link, url='https://www.youtube.com/@MarcelTusk'
		image, url='https://cdn.prod.website-files.com/65f8312a12341cfa0dfa2f49/65f8312a12341cfa0dfa2fc7_youtube.svg'
	StaticText © 2025 Tusk AI, Inc.. All rights reserved.
```
</details>



```
RootWebArea Overview - Tusk, focused, url='https://docs.usetusk.ai/automated-tests/overview'
	main
		[74] button Search or ask... Ctrl K, center=(840,32), inner_text=Search or ask...
Ctrl K, type=button
			image
```
<details><summary>Show more</summary>

```
		navigation
			list
				listitem
					[83] link Support, center=(1438,31), url='mailto:founders@usetusk.ai'
				listitem
					[87] link Dashboard, center=(1544,32), url='https://usetusk.ai/app'
		[93] button Toggle dark mode, center=(1632,32)
			image
		[113] link Automated Tests, center=(636,88), url='https://docs.usetusk.ai/automated-tests/introduction'
		[115] link UI/UX Fixes, center=(758,88), url='https://docs.usetusk.ai/ui-fixes/onboarding'
		[122] link Tusk home page dark logo, center=(310,34), inner_text=Tusk home page, url='https://usetusk.ai/'
			image dark logo, url='https://mintlify.s3.us-west-1.amazonaws.com/tusk/logo/tusk_full_logo.svg'
		heading Get Started
		list
			listitem
				[132] link Documentation, center=(376,140), url='https://docs.usetusk.ai/automated-tests/introduction'
			listitem
				[136] link Onboarding, center=(376,176), url='https://docs.usetusk.ai/automated-tests/onboarding'
		heading Platform
		list
			listitem
				[143] link Overview, center=(376,278), url='https://docs.usetusk.ai/automated-tests/overview'
			listitem
				[147] link Customization, center=(376,314), url='https://docs.usetusk.ai/automated-tests/customization'
			listitem
				[151] link Advantages, center=(376,350), url='https://docs.usetusk.ai/automated-tests/advantages'
			listitem
				[155] link Security Policy, center=(376,386), url='https://docs.usetusk.ai/automated-tests/security-policy'
		StaticText Platform
		heading Overview
		paragraph
			StaticText Generate unit and integration tests for your PRs
		image Tip
		paragraph
			StaticText This product is currently in private preview. Fill out
			[176] link this form, center=(1003,315), url='https://tally.so/r/nP29pQ'
			StaticText to get access.
		heading Navigate to header Test Generation
			[179] link Navigate to header, center=(567,406), inner_text=​, url='https://docs.usetusk.ai/automated-tests/overview#test-generation'
				StaticText ​
				image
		paragraph
			StaticText We’ve built a new Tusk agent that’s optimized for generating unit and integration tests for your code changes. Increase your code coverage with tests that actually
			strong
				StaticText check for edge cases
			StaticText .
		[182] span, center=(677,406), inner_text=Test Generation
		paragraph
			StaticText For engineering teams with a testing culture, this feature helps to cut down on the time spent writing good tests, which make up
			strong
				StaticText 25-50% of the time spent on a PR
			StaticText .
		[a] Iframe Loom video player, center=(947,792), title=Loom video player
			RootWebArea Demo of Tusk test check, url='https://www.loom.com/embed/4c9686b24d304bfc9ce0c2ac7b6e0dc8?sid=0e120cf6-f740-4e60-8083-8c0893d7411e?hideEmbedTopBar=true&hide_title=true&hide_owner=true'
				main
					image
					StaticText 2 min
					[a69] button Copy Link, center=(1227,624)
						image
					[a74] link Open video in Loom, center=(1267,622), url='https://www.loom.com/share/4c9686b24d304bfc9ce0c2ac7b6e0dc8'
						button Open video in Loom
							image
					[a79] button Play the video, center=(947,792)
						image
					image
					StaticText 0.8
					StaticText ×
					image
					StaticText 1
					StaticText ×
					[a99] image, center=(929,880)
					StaticText 1.2
					StaticText ×
					image
					StaticText 1.5
					StaticText ×
					image
					StaticText 1.7
					StaticText ×
					image
					StaticText 2
					StaticText ×
					image
					StaticText 2.5
					StaticText ×
					StaticText 2 min 11 sec
					StaticText ⚡️
					StaticText 2 min 43 sec
					StaticText 2 min 11 sec
					StaticText 1 min 49 sec
					StaticText 1 min 27 sec
					StaticText 1 min 17 sec
					StaticText 1 min 5 sec
					StaticText 52 sec
					image
					StaticText 2 min
					button Copy Link
						image
					link Open video in Loom, url='https://www.loom.com/share/4c9686b24d304bfc9ce0c2ac7b6e0dc8'
						button Open video in Loom
							image
					button Play the video
						image
					image
					StaticText 0.8
					StaticText ×
					image
					StaticText 1
					StaticText ×
					image
					StaticText 1.2
					StaticText ×
					image
					StaticText 1.5
					StaticText ×
					image
					StaticText 1.7
					StaticText ×
					image
					StaticText 2
					StaticText ×
					image
					StaticText 2.5
					StaticText ×
					StaticText 2 min 11 sec
					StaticText ⚡️
					StaticText 2 min 43 sec
					StaticText 2 min 11 sec
					StaticText 1 min 49 sec
					StaticText 1 min 27 sec
					StaticText 1 min 17 sec
					StaticText 1 min 5 sec
					StaticText 52 sec
				[192] span, center=(662,1059), inner_text=How It Works
		heading Navigate to header How It Works
			[189] link Navigate to header, center=(567,1059), inner_text=​, url='https://docs.usetusk.ai/automated-tests/overview#how-it-works'
				StaticText ​
				image
		list
			listitem
				ListMarker 0.
				paragraph
					StaticText When a commit is pushed to a PR, Tusk will look at the PR details, existing tests (if any), and codebase context to generate tests for the happy path and edge cases.
			listitem
				ListMarker 0.
				paragraph
					StaticText Tusk will run these new tests in an
					strong
						StaticText isolated sandbox
					StaticText .
			listitem
				ListMarker 0.
				paragraph
					StaticText If any tests fail and Tusk determines that the failure is due to an issue in the test, Tusk will auto-iterate on the test case.
			listitem
				ListMarker 0.
				paragraph
					StaticText Once the check is complete, Tusk will leave a
					strong
						StaticText PR comment
					StaticText with a summary of the tests generated as well as the check history.
		paragraph
			image Screenshot of Tusk's PR comment post-check, url='https://mintlify.s3.us-west-1.amazonaws.com/tusk/images/tusk-tester-pr-comment.jpeg'
			button Expand image: Screenshot of Tusk's PR comment post-check
		list
			listitem
				ListMarker 0.
				StaticText You can view the test cases created by clicking
				strong
					StaticText View tests
				StaticText or going to the check’s Details.
		paragraph
			image Screenshot of Tusk's automated tests, url='https://mintlify.s3.us-west-1.amazonaws.com/tusk/images/pr-check-hero-image-dark-new.png'
			button Expand image: Screenshot of Tusk's automated tests
		list
			listitem
				ListMarker 0.
				paragraph
					StaticText You can view the code for each test case, the reason why it was created, whether it passed or failed, and the test execution logs.
			listitem
				ListMarker 0.
				paragraph
					StaticText Click
					strong
						StaticText Incorporate tests
					StaticText to add the tests to the PR. If you’d like to add only a subset of the Tusk tests, hover over the code block, click to copy the test to your clipboard, and add it to the test file(s) in your IDE.
		image Screenshot of Tusk's 'Add to branch' button, url='https://mintlify.s3.us-west-1.amazonaws.com/tusk/images/pr-incorporate-tests-dark.png'
		button Expand image: Screenshot of Tusk's 'Add to branch' button
		list
			listitem
				ListMarker 0.
				StaticText You will see a new commit in the PR with the Tusk tests added. Good to go!
		paragraph
			image Screenshot of Tusk's new commit with tests, url='https://mintlify.s3.us-west-1.amazonaws.com/tusk/images/pr-new-commit-dark.jpg'
			button Expand image: Screenshot of Tusk's new commit with tests
		paragraph
			StaticText Questions? Reach out to
			link support@usetusk.ai, url='mailto:support@usetusk.ai'
			StaticText . We will respond as soon as possible.
		separator, orientation='horizontal'
		heading Navigate to header Coming Up
			link Navigate to header, url='https://docs.usetusk.ai/automated-tests/overview#coming-up'
				StaticText ​
				image
		list
			listitem
				paragraph
					StaticText UI to review and incorporate select test cases
			listitem
				paragraph
					StaticText E2E test generation with codebase context
			listitem
				paragraph
					StaticText GitLab support
		paragraph
			StaticText Was this page helpful?
		button Yes
			image
		button No
			image
		link Onboarding, url='https://docs.usetusk.ai/automated-tests/onboarding'
			image
		link Customization, url='https://docs.usetusk.ai/automated-tests/customization'
			image
		link x, url='https://x.com/usetusk'
			image
		link github, url='https://github.com/apps/use-tusk'
			image
		link linkedin, url='https://www.linkedin.com/company/usetusk'
			image
		link Powered by Mintlify, url='https://mintlify.com/preview-request?utm_campaign=poweredBy&utm_medium=docs&utm_source=docs.usetusk.ai'
		image
		StaticText On this page
		list
			listitem
				[299] link Test Generation, center=(1532,200), url='https://docs.usetusk.ai/automated-tests/overview#test-generation'
			listitem
				[301] link How It Works, center=(1532,232), url='https://docs.usetusk.ai/automated-tests/overview#how-it-works'
			listitem
				[303] link Coming Up, center=(1532,264), url='https://docs.usetusk.ai/automated-tests/overview#coming-up'
	alert, atomic
```
</details>

**Reasoning for action:** I clicked on the 'Read docs' link because it is crucial for the user to access detailed information about the product offerings of Tusk AI, specifically regarding automated tests. This step moves the user closer to understanding how Tusk AI can enhance their development workflow, fulfilling the user story's requirement to explore product offerings and make an informed decision.

**Action:** click(103) # Click on the Read docs link to learn more about how Tusk works.

**Change Description:** The browser navigated to the Tusk documentation page, specifically to the automated tests overview, which resulted in a change of URL to 'https://docs.usetusk.ai/automated-tests/overview' and the display of new content including headings, lists, and various links related to test generation and documentation resources.

**Screenshot before:****Screenshot after:**---


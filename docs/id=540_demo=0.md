# Task

**User Story - Exploring SSOReady Documentation**

As a developer exploring SSOReady,
I understand how to implement SAML SSO in my application,
so that I can quickly integrate single sign-on capabilities and enhance user authentication.

**Success definition:** Given I am on the SSOReady documentation homepage
When I click on the Documentation link and follow the links to Basic Concepts and Code Implementation
Then I should see detailed foundational information about SAML and its integration with SSOReady, and I should land on the Code Implementation section that outlines the steps for implementing SAML logins.

## Trajectory

**Step 1:**

**Url (before/after):** 

http://ssoready.com/

https://ssoready.com/docs/saml/saml-quickstart

**Content (before/after):** 

```
RootWebArea SSOReady | Open source developer tools for SAML single sign-on, focused, url='http://ssoready.com/'
	[60] link, center=(558,52), url='http://ssoready.com/'
		image, url='https://framerusercontent.com/images/e2JireuG3Rgs6XyK6Jl78kE19PE.png?scale-down-to=512'
	[65] link Documentation, center=(808,52), url='https://ssoready.com/docs/introduction/quickstart'
		paragraph
```
<details><summary>Show more</summary>

```
	[69] link Pricing, center=(928,52), url='http://ssoready.com/pricing'
		paragraph
	[73] link Company, center=(1027,52), url='http://ssoready.com/company'
		paragraph
	[77] link Blog, center=(1118,52), url='https://ssoready.com/blog/'
		paragraph
	[82] link Get SSOReady Get SSOReady, center=(1346,52), inner_text=Get SSOReady

Get SSOReady, url='https://app.ssoready.com/'
		paragraph
			StaticText Get SSOReady
		paragraph
			StaticText Get SSOReady
		image
		image
	banner
		[107] link Star us on Github!, center=(960,363), url='http://github.com/ssoready/ssoready'
			image, url='https://framerusercontent.com/images/VqBq7xt2nPCXSEuWwN2WMdsaUKA.png?scale-down-to=512'
			paragraph
		heading Ship enterprise single sign-on in less than a day
		paragraph
			StaticText Totally free — either cloud or self-hosted
		[126] link Add SAML SSO to your app Add SAML SSO to your app, center=(960,653), inner_text=Add SAML SSO to your app

Add SAML SSO to your app, url='https://app.ssoready.com/'
			paragraph
				StaticText Add SAML SSO to your app
			paragraph
				StaticText Add SAML SSO to your app
			image
			image
		paragraph
			StaticText Backed by
		image, url='https://framerusercontent.com/images/dGCKsNQGfjz43AbnGcXjSEB3bw.png?scale-down-to=512'
		image, url='https://framerusercontent.com/images/hxoTP82d3xDNedMIAQMIB6bHMAM.png'
		paragraph
			StaticText ffxfxfxf
	banner
		heading Support for all major identity providers
		paragraph
			StaticText SSOReady integrates with the services your customers use for single sign-on. Once you've set up SSOReady, you immediately get coverage for all major identity providers.
		link Get started for free Get started for free, url='https://app.ssoready.com/'
			paragraph
				StaticText Get started for free
			paragraph
				StaticText Get started for free
			image
			image
		image, url='https://framerusercontent.com/images/sCIWXgh5mocnJQApK0XojHwcO4.png'
		image, url='https://framerusercontent.com/images/dKX42Egpr61ZOcd11wJ9GVrPgTc.png?scale-down-to=512'
		image, url='https://framerusercontent.com/images/ZvG6DBQC42S9WKo1coEEVslxads.png?scale-down-to=512'
		image, url='https://framerusercontent.com/images/BY6FKJcHYrwvCDxRK53ekQY53g.png?scale-down-to=512'
		image, url='https://framerusercontent.com/images/eMtCAb687tcHxnki6sm6dsBNbA.png?scale-down-to=512'
		image, url='https://framerusercontent.com/images/o2M31bMMcej13MvNZh7oemzXGw.png?scale-down-to=512'
		image, url='https://framerusercontent.com/images/UfPBJPSrFJ7V3Z2WztrBSc0E.png?scale-down-to=512'
		image, url='https://framerusercontent.com/images/9VdHrdrGytDArzVqUQpCmSmFkqA.png?scale-down-to=512'
		image, url='https://framerusercontent.com/images/tBJXDj8nSRKVAaK6nKZVf48Ju8U.png?scale-down-to=512'
		image, url='https://framerusercontent.com/images/7oMvrsKYnYMHKnmILOQBGYvY3M.png?scale-down-to=512'
		image, url='https://framerusercontent.com/images/1GNeF8MjVrWgxYjUhb0v3TDCA6s.png?scale-down-to=512'
		image, url='https://framerusercontent.com/images/0LSl6nDpSCLaV7EFdzHG0Js5R7I.png?scale-down-to=512'
		image, url='https://framerusercontent.com/images/Yx3fd2kABB94bFOtQRZPQdqy56g.png?scale-down-to=512'
		image, url='https://framerusercontent.com/images/ixfgpK9tzOTG19kFt6COayfSM.png?scale-down-to=512'
		image, url='https://framerusercontent.com/images/LwG9fAgURZEmI3tJEpKRxB2d9vM.png?scale-down-to=512'
		heading Abstract away all of the SAML
		paragraph
			StaticText Get multi-tenant SSO support with just two API calls. Stick with the tech stack you already use.
		link Read the docs Read the docs, url='https://ssoready.com/docs/saml/saml-quickstart'
			paragraph
				StaticText Read the docs
			paragraph
				StaticText Read the docs
			image
			image
		paragraph
		paragraph
		paragraph
		code
			StaticText # Get a redirect URL
			StaticText curl
			StaticText https://api.ssoready.com/v1/saml/redirect \
			StaticText -H
			StaticText "Content-Type: application/json"
			StaticText \
			StaticText -H
			StaticText "Authorization: Bearer ssoready_sk_..."
			StaticText \
			StaticText -d
			StaticText '{ "organizationExternalId": "..." }'
			StaticText # Exchange access code for login details
			StaticText curl
			StaticText https://api.ssoready.com/v1/saml/redeem \
			StaticText -H
			StaticText "Content-Type: application/json"
			StaticText \
			StaticText -H
			StaticText "Authorization: Bearer ssoready_sk_..."
			StaticText \
			StaticText -d
			StaticText '{ "samlAccessCode": "saml_access_code_..." }'
		heading SCIM directory sync made simple
		paragraph
			StaticText Programmatically provision and deprovision users with a single unified API for your customers' identity providers.
		link Read the docs Read the docs, url='https://ssoready.com/docs/scim/scim-quickstart'
			paragraph
				StaticText Read the docs
			paragraph
				StaticText Read the docs
			image
			image
		paragraph
		paragraph
		paragraph
		code
			StaticText # List SCIM users
			StaticText curl
			StaticText -G
			StaticText https://api.ssoready.com/v1/scim/users \
			StaticText -H
			StaticText "Authorization: Bearer <apiKey>"
			StaticText \
			StaticText -d
			StaticText organizationExternalId
			StaticText =my_custom_external_id
			StaticText # List SCIM groups
			StaticText curl
			StaticText -G
			StaticText https://api.ssoready.com/v1/scim/groups \
			StaticText -H
			StaticText "Authorization: Bearer <apiKey>"
			StaticText \
			StaticText -d
			StaticText organizationExternalId
	banner
		heading Stay in touch
		paragraph
			StaticText If you're at all curious about what we're building, fill out this form to receive updates on our progress. Don't worry; we don't do spam emails! We write all outreach by hand.
		paragraph
		paragraph
			StaticText You can also use this form to request technical advice. We'd be happy to help out — no strings attached.
		LabelText
			paragraph
				StaticText Email (required)
			textbox Email (required), required
		LabelText
			paragraph
				StaticText Anything we should know?
			textbox Anything we should know?, required
		button Submit
			paragraph
	banner
		link, url='http://ssoready.com/'
			image, url='https://framerusercontent.com/images/e2JireuG3Rgs6XyK6Jl78kE19PE.png?scale-down-to=512'
		paragraph
			StaticText © Copyright 2024, All rights reserved by Codomain Data Corporation (d.b.a. SSOReady)
		paragraph
			link Privacy policy, url='http://ssoready.com/privacy'
		paragraph
			link Terms of use, url='http://ssoready.com/terms'
```
</details>



```
RootWebArea Getting started with SSOReady SAML — SSOReady Docs, focused, url='https://ssoready.com/docs/saml/saml-quickstart'
	banner
		navigation primary
			[84] link SSOReady Docs, center=(349,32), url='https://ssoready.com/'
				image SSOReady Docs, url='https://app.buildwithfern.com/_next/image?url=https%3A%2F%2Ffiles.buildwithfern.com%2Fssoready.docs.buildwithfern.com%2Fdocs%2F2025-01-02T23%3A05%3A17.602Z%2Fdocs%2Fassets%2Flogo.png&w=128&q=100&dpl=dpl_E3br8NqLCTPPhihEjcHncTi4MC6y'
```
<details><summary>Show more</summary>

```
			[89] button Search... /, center=(960,32), inner_text=Search...
/
				image
			[97] link Login, center=(1594,32), url='https://app.ssoready.com/'
				image
	navigation secondary
		list
			listitem
				list
					listitem
						[120] link Introduction, center=(402,106), url='https://ssoready.com/docs/introduction'
			listitem
				StaticText SAML (Enterprise SSO)
				list
					listitem
						[129] link SAML Quickstart, center=(402,206), url='https://ssoready.com/docs/saml/saml-quickstart'
					listitem
						[134] link SAML: A technical primer, center=(402,242), url='https://ssoready.com/docs/saml/saml-technical-primer'
					listitem
						[139] link Integrating SAML with your Login UI, center=(402,278), url='https://ssoready.com/docs/saml/integrating-saml-into-your-login-ui'
					listitem
						[144] link Handling SAML Logins + JIT Provisioning, center=(402,324), url='https://ssoready.com/docs/saml/handling-saml-logins-jit-provisioning'
			listitem
				StaticText SCIM (Enterprise Directory Sync)
				list
					listitem
						[153] link SCIM Quickstart, center=(402,434), url='https://ssoready.com/docs/scim/scim-quickstart'
			listitem
				StaticText SDKs
				list
					listitem
						[162] link TypeScript SDK, center=(402,534), url='https://github.com/ssoready/ssoready-typescript'
							image
					listitem
						[170] link Python SDK, center=(402,570), url='https://github.com/ssoready/ssoready-python'
							image
					listitem
						[178] link Go SDK, center=(402,606), url='https://github.com/ssoready/ssoready-go'
							image
					listitem
						[186] link Java SDK, center=(402,642), url='https://github.com/ssoready/ssoready-java'
							image
					listitem
						[194] link C# SDK, center=(402,678), url='https://github.com/ssoready/ssoready-csharp'
							image
					listitem
						[202] link Ruby SDK, center=(402,714), url='https://github.com/ssoready/ssoready-ruby'
							image
					listitem
						[210] link PHP SDK, center=(402,750), url='https://github.com/ssoready/ssoready-php'
							image
			listitem
				StaticText SAML-over-OAuth
				list
					listitem
						[222] link SAML over OAuth (SAML NextAuth.js integration), center=(402,860), url='https://ssoready.com/docs/saml-over-oauth-saml-nextauth-integration'
					listitem
						[227] link SAML for Firebase, center=(402,906), url='https://ssoready.com/docs/firebase'
			listitem
				StaticText IDP configuration
				list
					listitem
						[236] link Enabling self-service configuration for your customers, center=(402,1016), url='https://ssoready.com/docs/idp-configuration/enabling-self-service-configuration-for-your-customers'
					listitem
						[242] button Guides for common identity providers, center=(402,1072)
							image
			listitem
				StaticText SSOReady concepts
				list
					listitem
						link Overview, url='https://ssoready.com/docs/ssoready-concepts/overview'
					listitem
						link Environments, url='https://ssoready.com/docs/ssoready-concepts/environments'
					listitem
						link Organizations, url='https://ssoready.com/docs/ssoready-concepts/organizations'
					listitem
						link SAML Connections, url='https://ssoready.com/docs/ssoready-concepts/saml-connections'
					listitem
						link SAML Login Flows, url='https://ssoready.com/docs/ssoready-concepts/saml-login-flows'
					listitem
						link SCIM Directories, url='https://ssoready.com/docs/ssoready-concepts/scim-directories'
					listitem
						link SCIM Users, url='https://ssoready.com/docs/ssoready-concepts/scim-users'
					listitem
						link SCIM Groups, url='https://ssoready.com/docs/ssoready-concepts/scim-groups'
					listitem
						link SCIM Request Logs, url='https://ssoready.com/docs/ssoready-concepts/scim-request-logs'
			listitem
				StaticText Management API
				list
					listitem
						link Management API, url='https://ssoready.com/docs/management-api'
			listitem
				StaticText DummyIDP
				list
					listitem
						link Testing SAML/SCIM with DummyIDP, url='https://ssoready.com/docs/dummyidp'
			listitem
				StaticText Self-Hosting
				list
					listitem
						link Self-Hosting SSOReady, url='https://ssoready.com/docs/self-hosting-ssoready'
			listitem
				StaticText API Reference
				list
					listitem
						button SAML
							image
					listitem
						button SCIM
							image
					listitem
						button Management API
							image
	main
		complementary
			StaticText On this page
			list
				listitem
					[368] link Getting started with SSOReady SAML, center=(1519,148), url='https://ssoready.com/docs/saml/saml-quickstart#getting-started-with-ssoready-saml'
				listitem
					[370] link Basic concepts, center=(1519,186), url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
				listitem
					[372] link Code implementation, center=(1519,214), url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
				listitem
					[374] link Initiating SAML logins, center=(1519,242), url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				listitem
					[376] link Handling SAML logins, center=(1519,270), url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
				listitem
					[378] link Setting up SSOReady, center=(1519,298), url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				listitem
					[380] link Creating environments, center=(1519,326), url='https://ssoready.com/docs/saml/saml-quickstart#creating-environments'
				listitem
					[382] link Creating API keys, center=(1519,354), url='https://ssoready.com/docs/saml/saml-quickstart#creating-api-keys'
				listitem
					[384] link Creating organizations, center=(1519,382), url='https://ssoready.com/docs/saml/saml-quickstart#creating-organizations'
				listitem
					[386] link Creating SAML connections, center=(1519,410), url='https://ssoready.com/docs/saml/saml-quickstart#creating-saml-connections'
				listitem
					[388] link Onboarding customers, center=(1519,438), url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
		article
			[394] link SAML (Enterprise SSO), center=(686,108), url='https://ssoready.com/docs/saml/saml-quickstart'
			heading SAML Quickstart
				paragraph
			paragraph
				StaticText Start accepting SAML logins this afternoon
			[400] heading Getting started with SSOReady SAML, center=(960,257)
			paragraph
				StaticText Welcome to the SSOReady quickstart guide! This guide will take you through:
			list
				listitem
					ListMarker 0.
					[404] link Basic concepts., center=(701,370), url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
						strong
					StaticText How Enterprise SSO / SAML works at a high level, and how SSOReady will help you implement it.
				listitem
					ListMarker 0.
					[407] link Code implementation., center=(724,434), url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
						strong
					StaticText What you’ll need to build, and how to use SSOReady’s SDK.
				listitem
					ListMarker 0.
					[410] link Onboarding customers., center=(730,470), url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
						strong
					StaticText SAML requires both you and your customer to do setup. SSOReady automates your end of the equation, and this section describes what instructions you’ll give to your customers.
			paragraph
				StaticText SSOReady is just an authentication middleware layer. SSOReady doesn’t “own” your users, and it doesn’t require you to use any particular tech stack. That’s on purpose — it makes onboarding easier for you, and it forces us to keep earning your business in the long run, because churning is easier.
			[413] heading Basic concepts, center=(960,747)
			paragraph
				StaticText ”Enterprise SSO” is mostly a synonym for a protocol called
				[415] link SAML, center=(1057,812), url='https://en.wikipedia.org/wiki/Security_Assertion_Markup_Language'
					image
				StaticText . It’s a way for a company to easily let their employees log into all their software products, including your product.
			paragraph
				StaticText At smaller companies, employees use username+password or “Log in with Google” to sign into your product. At larger companies, employees instead expect to use services like Okta or Microsoft Entra (formerly “Azure AD”) to do sign-in. Those sign-ins happen using the SAML protocol. SSOReady makes it way easier to implement SAML.
			paragraph
				StaticText SAML logins have two steps:
			list
				listitem
					ListMarker 0.
					StaticText You
					[421] link initiate a SAML login, center=(750,1068), url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
						strong
					StaticText by redirecting your user to their corporate Okta/Google/Microsoft.
				listitem
					ListMarker 0.
					StaticText Their corporate Okta/Google/Microsoft redirects your user back to your app, and you
					link handle the SAML login, url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
						strong
					StaticText .
			paragraph
				StaticText Before this can happen, you and your customer need to exchange settings about each other. This process is done offline; you’ll give your customer some settings that SSOReady provides for you, and you’ll email your customer asking for some settings in return which you’ll input into SSOReady.
			paragraph
				StaticText We’ll cover how to do (1) and (2) in
				link Code implementation, url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
				StaticText . We’ll cover the setup work you’ll need to do inside SSOReady’s webapp in
				link Setting up SSOReady, url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				StaticText . We’ll cover the settings you’ll give and ask for in
				link Onboarding customers, url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
				StaticText .
			heading Code implementation
			paragraph
				StaticText As covered in
				link Basic concepts, url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
				StaticText , there are two steps involved in implementing SAML: initiating SAML logins, and handling SAML logins. Here’s how you do each.
			heading Initiating SAML logins
			paragraph
				image, url='https://app.buildwithfern.com/_next/image?url=https%3A%2F%2Ffiles.buildwithfern.com%2Fssoready.docs.buildwithfern.com%2Fdocs%2F2025-01-02T23%3A05%3A17.602Z%2Fpages%2Fquickstart-initiate.png&w=3840&q=75&dpl=dpl_E3br8NqLCTPPhihEjcHncTi4MC6y'
				button Expand image
			paragraph
				StaticText Under the hood, initiating SAML logins requires you to get your user’s browser to perform an HTTP POST against their corporate Okta/Google/Microsoft with a specific XML message. SSOReady abstracts all this work away into you just needing to redirect your user to a URL.
			paragraph
				StaticText SSOReady’s SDKs generate a URL for you, and then you simply forward your user to that URL using any mechanism that suits your tech stack.
			StaticText POST
			button /v1/saml/redirect
			button cURL, expanded=False, hasPopup='menu'
				image
			link, url='https://ssoready.com/docs/api-reference/saml/get-saml-redirect-url'
				image
			button
				image
			code
				table
					rowgroup
						row
							cell $
							cell curl -X POST https://api.ssoready.com/v1/saml/redirect \
						row
							cell >
							cell -H "Authorization: Bearer <apiKey>" \
						row
							cell >
							cell -H "Content-Type: application/json" \
						row
							cell >
							cell -d '{
						row
							cell >
							cell "organizationExternalId": "my_custom_external_id"
						row
							cell >
							cell }'
			StaticText Response
			button
				image
			code
				table
					rowgroup
						row
							cell 1
							cell {
						row
							cell 2
							cell "redirectUrl": "https://your.redirect.url"
						row
							cell 3
							cell }
			paragraph
				StaticText That code sample requires an API Key (
				code
					StaticText ssoready_sk_...
				StaticText ) and an
				code
					StaticText organizationExternalId
				StaticText . How you get those is covered in
				link Setting up SSOReady, url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				StaticText later on this page.
			image
			heading
			paragraph
				StaticText For recommendations on how to incorporate a “Log in with SAML” button into your login user experience, check out our docs on
				link Integrating SAML with your Login UI, url='https://ssoready.com/docs/saml/integrating-saml-into-your-login-ui'
				StaticText .
			heading Handling SAML logins
			paragraph
				image, url='https://app.buildwithfern.com/_next/image?url=https%3A%2F%2Ffiles.buildwithfern.com%2Fssoready.docs.buildwithfern.com%2Fdocs%2F2025-01-02T23%3A05%3A17.602Z%2Fpages%2Fquickstart-handle.png&w=3840&q=75&dpl=dpl_E3br8NqLCTPPhihEjcHncTi4MC6y'
				button Expand image
			paragraph
				StaticText Under the hood, SAML login details are sent to you in the form of your user’s web browser POST-ing you an XML message. You would then need to
				link authenticate that message, url='https://www.w3.org/TR/xmldsig-core1/'
					image
				StaticText before logging your user in.
			paragraph
				StaticText SSOReady abstracts this away; we handle authenticating the message, and instead forward your user to a callback page on your webapp with a “SAML access code”, which you can redeem in exchange for authenticated details about the user.
			paragraph
				StaticText So what you’ll need to do is create a new “SSOReady callback page” (typically something like
				code
					StaticText https://app.yourcompany.com/ssoready-callback
				StaticText ), where you’ll expect a
				code
					StaticText ?saml_access_code=saml_access_code_...
				StaticText query parameter in the URL. From your backend, you’ll exchange that access code for a user’s details:
			StaticText POST
			button /v1/saml/redeem
			button cURL, expanded=False, hasPopup='menu'
				image
			link, url='https://ssoready.com/docs/api-reference/saml/redeem-saml-access-code'
				image
			button
				image
			code
				table
					rowgroup
						row
							cell $
							cell curl -X POST https://api.ssoready.com/v1/saml/redeem \
						row
							cell >
							cell -H "Authorization: Bearer <apiKey>" \
						row
							cell >
							cell -H "Content-Type: application/json" \
						row
							cell >
							cell -d '{
						row
							cell >
							cell "samlAccessCode": "saml_access_code_..."
						row
							cell >
							cell }'
			StaticText Response
			button
				image
			code
				table
					rowgroup
						row
							cell 1
							cell {
						row
							cell 2
							cell "email": "john.doe@acme.com",
						row
							cell 3
							cell "organizationId": "org_7cu5hsy9vrbi5d2k1qvbh19lj",
						row
							cell 4
							cell "organizationExternalId": "my_custom_external_id"
						row
							cell 5
							cell }
			paragraph
				StaticText The response will include the user’s
				code
					StaticText email
				StaticText as well as the SSOReady
				code
					StaticText organizationId
				StaticText and
				code
					StaticText organizationExternalId
				StaticText they belong to. It’s your responsibility to then log the user in with that given email and organization using whatever mechanism your tech stack uses.
			paragraph
				StaticText How you tell us about your desired “SSOReady callback page”, as well as what
				code
					StaticText organizationId
				StaticText and
				code
					StaticText organizationExternalId
				StaticText mean, is covered in
				link Setting up SSOReady, url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				StaticText below.
			image
			heading
			paragraph
				StaticText For recommendations on how your SAML handling logic should work, check out our docs on
				link Handling SAML Logins and Just-in-Time Provisioning, url='https://ssoready.com/docs/saml/handling-saml-logins-jit-provisioning'
				StaticText .
			heading Setting up SSOReady
			paragraph
				StaticText In
				link Code implementation, url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
				StaticText , there were three missing pieces that you’d need to implement SSOReady:
			list
				listitem
					ListMarker 0.
					strong
						StaticText Where does the SSOReady callback page get configured?
					StaticText That information lives on
					link environments, url='https://ssoready.com/docs/saml/saml-quickstart#creating-environments'
					StaticText .
				listitem
					ListMarker 0.
					strong
						StaticText Where do I get an API key?
					StaticText You create
					link an API key, url='https://ssoready.com/docs/saml/saml-quickstart#creating-api-keys'
					StaticText scoped to an environment.
				listitem
					ListMarker 0.
					strong
						StaticText How do I get
						code
							StaticText organizationExternalId
						StaticText ?
					StaticText You create
					link an organization, url='https://ssoready.com/docs/saml/saml-quickstart#creating-organizations'
					StaticText in an environment, where you can choose an external ID convenient for you.
			paragraph
				StaticText This section will step you through how you’ll do all of this setup in SSOReady’s webapp. As a prerequisite step, you’ll need to
				link sign up for SSOReady, url='https://app.ssoready.com/login'
					image
				StaticText . It’s free and anyone can sign up, even with a personal email.
			heading Creating environments
			paragraph
				StaticText To create an environment, go
				link here, url='https://app.ssoready.com/environments/new'
					image
				StaticText . You’ll typically create one environment per deployment environment, e.g. one each for “production”, “staging”, and “local dev”. On an environment, you’ll assign a “Redirect URL”. That’s the URL your users get redirected to in
				link “Handling SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
				StaticText .
			heading Creating API keys
			paragraph
				StaticText API keys are scoped to an environment. When viewing an environment in the app, click “API Keys” on the left navbar. Then click “Create API Key”. A popup will show you your new API key’s secret (it starts with
				code
					StaticText ssoready_sk_...
				StaticText ). That’s the API key you’ll use in
				link “Initiating SAML Logins”, url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				StaticText and
				link “Handling SAML Logins”, url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
				StaticText .
			heading Creating organizations
			paragraph
				StaticText An organization corresponds to a corporate customer of yours. If you sold your product to Apple, Nvidia, and Amazon, you’d have three organizations in SSOReady: one each for Apple, Nvidia, and Amazon.
			paragraph
				StaticText Organizations belong to an environment. When viewing an environment in the app, the “Create organization” button creates a new organization. Organizations have two properties worth highlighting:
			list
				listitem
					ListMarker •
					StaticText An optional
					emphasis
						StaticText external ID
					StaticText , which you can assign. If you’re selling multi-tenant B2B software, you probably already have a concept that closely matches an SSOReady organization — usually, this is something named a “team”, “workspace”, “company”, or something similar. When creating an SSOReady organization, use your product’s counterpart to an organization ID as the external ID.
			paragraph
				StaticText You’ll provide the external ID as the
				code
					StaticText organizationExternalId
				StaticText in
				link “Initiating SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				StaticText . The external ID is returned to you when
				link “Redeeming SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#redeeming-saml-logins'
				StaticText .
			list
				listitem
					ListMarker •
					StaticText A set of
					emphasis
						StaticText domains
					StaticText . If you expect Apple’s employees will log in to your product from
					code
						StaticText @apple.com
					StaticText and
					code
						StaticText @shazam.com
					StaticText email addresses, then put
					code
						StaticText apple.com
					StaticText and
					code
						StaticText shazam.com
					StaticText here. SSOReady will enforce that users’ SAML logins come from these domains.
			heading Creating SAML connections
			paragraph
				StaticText A SAML connection holds onto SAML-related settings. In
				link “Onboarding customers”, url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
				StaticText , you’ll be providing and asking for settings. Those settings all live on an SSOReady SAML connection.
			paragraph
				StaticText SAML connections belong to an organization. When viewing an organization in the app, the “Create SAML connection” button creates a new SAML connection. Beyond the SAML-related settings covered in
				link “Onboarding customers”, url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
				StaticText , SAML connections have one setting of note: whether they are
				emphasis
					StaticText primary
				StaticText .
			paragraph
				StaticText Each organization has up to one primary SAML connection. In
				link “Initiating SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				StaticText , you provide an
				code
					StaticText organizationExternalId
				StaticText . SSOReady will use that organization’s primary SAML connection to initiate the login.
			heading Onboarding customers
			paragraph
				StaticText In
				link Basic concepts, url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
				StaticText , we mentioned that you and your customer need to exchange details about each other before you can do SAML logins. This process happens offline — there’s no coding involved.
			paragraph
				StaticText You have to go through this process each time a new company wants to set up SAML. It’s inherent to how SAML was designed.
			paragraph
				StaticText With SSOReady, you have two options for onboarding customers onto SAML — that is, exchanging SAML-related settings with them. You can:
			list
				listitem
					ListMarker 0.
					StaticText Use SSOReady’s
					link self-serve setup links, url='https://ssoready.com/docs/idp-configuration/enabling-self-service-configuration-for-your-customers'
					StaticText . You give your customers a link, where they can set up SAML on their own. It’s a slick experience for your customers, and they’ll get set up in minutes.
					strong
						StaticText We recommend this approach.
				listitem
					ListMarker 0.
					StaticText Give your customers instructions yourself, over email/slack/Zoom/etc.
			paragraph
				StaticText If you go with option (2), be advised that SAML identity providers (e.g. Okta, Microsoft Entra, Google Workspace, etc.) don’t use the same terminology for these identical details. To deal with that, we’ve prepared a separate set of documentation for you to follow depending on what identity provider your customer uses:
			list
				listitem
					ListMarker •
					link Okta, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/okta/saml-with-okta'
				listitem
					ListMarker •
					link Google Workspace, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/google/saml-with-google'
				listitem
					ListMarker •
					link Microsoft Entra, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/entra-formerly-azure-ad/saml-with-entra'
					StaticText (aka Microsoft Azure Active Directory, Microsoft Azure AD)
				listitem
					ListMarker •
					link JumpCloud, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/jumpcloud/saml-with-jumpcloud'
				listitem
					ListMarker •
					link Ping Identity, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/ping-identity/saml-with-ping-identity'
			paragraph
				StaticText In all cases, you’re ultimately going to:
			list
				listitem
					ListMarker 0.
					StaticText Give your customers an “SP Entity ID” and “SP ACS URL”. SSOReady’s webapp gives you both.
				listitem
					ListMarker 0.
					StaticText Ask your customers for an “IDP Entity ID”, “IDP Redirect URL”, and “IDP Certificate” which you input into SSOReady.
			paragraph
				StaticText Once you have all those details, you’ll be ready to accept SAML logins!
			StaticText Was this page helpful?
			button Yes, expanded=False, hasPopup='dialog'
				image
			button No, expanded=False, hasPopup='dialog'
				image
			link SAML: A technical primer Up Next, url='https://ssoready.com/docs/saml/saml-technical-primer'
				image
			link Built with, url='https://buildwithfern.com/?utm_campaign=buildWith&utm_medium=docs&utm_source=ssoready.com'
				image
	contentinfo
	alert, atomic
```
</details>

**Reasoning for action:** My reasoning for this action is that clicking on the Documentation link is a necessary step to move to the relevant section where detailed information regarding SAML SSO can be accessed. This directly aligns with the user story's requirement to explore documentation to understand how to implement SAML SSO in an application.

**Action:** click(65) # Click on the Documentation link to explore the documentation section.

**Change Description:** After clicking the Documentation link, the browser navigated to the SSOReady documentation page, updating the main content area to display documentation resources specifically for SAML single sign-on, including links to various quickstart guides and API references.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://ssoready.com/docs/saml/saml-quickstart

https://ssoready.com/docs/saml/saml-quickstart#basic-concepts

**Content (before/after):** 

```
RootWebArea Getting started with SSOReady SAML — SSOReady Docs, focused, url='https://ssoready.com/docs/saml/saml-quickstart'
	banner
		navigation primary
			[84] link SSOReady Docs, center=(349,32), url='https://ssoready.com/'
				image SSOReady Docs, url='https://app.buildwithfern.com/_next/image?url=https%3A%2F%2Ffiles.buildwithfern.com%2Fssoready.docs.buildwithfern.com%2Fdocs%2F2025-01-02T23%3A05%3A17.602Z%2Fdocs%2Fassets%2Flogo.png&w=128&q=100&dpl=dpl_E3br8NqLCTPPhihEjcHncTi4MC6y'
```
<details><summary>Show more</summary>

```
			[89] button Search... /, center=(960,32), inner_text=Search...
/
				image
			[97] link Login, center=(1594,32), url='https://app.ssoready.com/'
				image
	navigation secondary
		list
			listitem
				list
					listitem
						[120] link Introduction, center=(402,106), url='https://ssoready.com/docs/introduction'
			listitem
				StaticText SAML (Enterprise SSO)
				list
					listitem
						[129] link SAML Quickstart, center=(402,206), url='https://ssoready.com/docs/saml/saml-quickstart'
					listitem
						[134] link SAML: A technical primer, center=(402,242), url='https://ssoready.com/docs/saml/saml-technical-primer'
					listitem
						[139] link Integrating SAML with your Login UI, center=(402,278), url='https://ssoready.com/docs/saml/integrating-saml-into-your-login-ui'
					listitem
						[144] link Handling SAML Logins + JIT Provisioning, center=(402,324), url='https://ssoready.com/docs/saml/handling-saml-logins-jit-provisioning'
			listitem
				StaticText SCIM (Enterprise Directory Sync)
				list
					listitem
						[153] link SCIM Quickstart, center=(402,434), url='https://ssoready.com/docs/scim/scim-quickstart'
			listitem
				StaticText SDKs
				list
					listitem
						[162] link TypeScript SDK, center=(402,534), url='https://github.com/ssoready/ssoready-typescript'
							image
					listitem
						[170] link Python SDK, center=(402,570), url='https://github.com/ssoready/ssoready-python'
							image
					listitem
						[178] link Go SDK, center=(402,606), url='https://github.com/ssoready/ssoready-go'
							image
					listitem
						[186] link Java SDK, center=(402,642), url='https://github.com/ssoready/ssoready-java'
							image
					listitem
						[194] link C# SDK, center=(402,678), url='https://github.com/ssoready/ssoready-csharp'
							image
					listitem
						[202] link Ruby SDK, center=(402,714), url='https://github.com/ssoready/ssoready-ruby'
							image
					listitem
						[210] link PHP SDK, center=(402,750), url='https://github.com/ssoready/ssoready-php'
							image
			listitem
				StaticText SAML-over-OAuth
				list
					listitem
						[222] link SAML over OAuth (SAML NextAuth.js integration), center=(402,860), url='https://ssoready.com/docs/saml-over-oauth-saml-nextauth-integration'
					listitem
						[227] link SAML for Firebase, center=(402,906), url='https://ssoready.com/docs/firebase'
			listitem
				StaticText IDP configuration
				list
					listitem
						[236] link Enabling self-service configuration for your customers, center=(402,1016), url='https://ssoready.com/docs/idp-configuration/enabling-self-service-configuration-for-your-customers'
					listitem
						[242] button Guides for common identity providers, center=(402,1072)
							image
			listitem
				StaticText SSOReady concepts
				list
					listitem
						link Overview, url='https://ssoready.com/docs/ssoready-concepts/overview'
					listitem
						link Environments, url='https://ssoready.com/docs/ssoready-concepts/environments'
					listitem
						link Organizations, url='https://ssoready.com/docs/ssoready-concepts/organizations'
					listitem
						link SAML Connections, url='https://ssoready.com/docs/ssoready-concepts/saml-connections'
					listitem
						link SAML Login Flows, url='https://ssoready.com/docs/ssoready-concepts/saml-login-flows'
					listitem
						link SCIM Directories, url='https://ssoready.com/docs/ssoready-concepts/scim-directories'
					listitem
						link SCIM Users, url='https://ssoready.com/docs/ssoready-concepts/scim-users'
					listitem
						link SCIM Groups, url='https://ssoready.com/docs/ssoready-concepts/scim-groups'
					listitem
						link SCIM Request Logs, url='https://ssoready.com/docs/ssoready-concepts/scim-request-logs'
			listitem
				StaticText Management API
				list
					listitem
						link Management API, url='https://ssoready.com/docs/management-api'
			listitem
				StaticText DummyIDP
				list
					listitem
						link Testing SAML/SCIM with DummyIDP, url='https://ssoready.com/docs/dummyidp'
			listitem
				StaticText Self-Hosting
				list
					listitem
						link Self-Hosting SSOReady, url='https://ssoready.com/docs/self-hosting-ssoready'
			listitem
				StaticText API Reference
				list
					listitem
						button SAML
							image
					listitem
						button SCIM
							image
					listitem
						button Management API
							image
	main
		complementary
			StaticText On this page
			list
				listitem
					[368] link Getting started with SSOReady SAML, center=(1519,148), url='https://ssoready.com/docs/saml/saml-quickstart#getting-started-with-ssoready-saml'
				listitem
					[370] link Basic concepts, center=(1519,186), url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
				listitem
					[372] link Code implementation, center=(1519,214), url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
				listitem
					[374] link Initiating SAML logins, center=(1519,242), url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				listitem
					[376] link Handling SAML logins, center=(1519,270), url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
				listitem
					[378] link Setting up SSOReady, center=(1519,298), url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				listitem
					[380] link Creating environments, center=(1519,326), url='https://ssoready.com/docs/saml/saml-quickstart#creating-environments'
				listitem
					[382] link Creating API keys, center=(1519,354), url='https://ssoready.com/docs/saml/saml-quickstart#creating-api-keys'
				listitem
					[384] link Creating organizations, center=(1519,382), url='https://ssoready.com/docs/saml/saml-quickstart#creating-organizations'
				listitem
					[386] link Creating SAML connections, center=(1519,410), url='https://ssoready.com/docs/saml/saml-quickstart#creating-saml-connections'
				listitem
					[388] link Onboarding customers, center=(1519,438), url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
		article
			[394] link SAML (Enterprise SSO), center=(686,108), url='https://ssoready.com/docs/saml/saml-quickstart'
			heading SAML Quickstart
				paragraph
			paragraph
				StaticText Start accepting SAML logins this afternoon
			[400] heading Getting started with SSOReady SAML, center=(960,257)
			paragraph
				StaticText Welcome to the SSOReady quickstart guide! This guide will take you through:
			list
				listitem
					ListMarker 0.
					[404] link Basic concepts., center=(701,370), url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
						strong
					StaticText How Enterprise SSO / SAML works at a high level, and how SSOReady will help you implement it.
				listitem
					ListMarker 0.
					[407] link Code implementation., center=(724,434), url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
						strong
					StaticText What you’ll need to build, and how to use SSOReady’s SDK.
				listitem
					ListMarker 0.
					[410] link Onboarding customers., center=(730,470), url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
						strong
					StaticText SAML requires both you and your customer to do setup. SSOReady automates your end of the equation, and this section describes what instructions you’ll give to your customers.
			paragraph
				StaticText SSOReady is just an authentication middleware layer. SSOReady doesn’t “own” your users, and it doesn’t require you to use any particular tech stack. That’s on purpose — it makes onboarding easier for you, and it forces us to keep earning your business in the long run, because churning is easier.
			[413] heading Basic concepts, center=(960,747)
			paragraph
				StaticText ”Enterprise SSO” is mostly a synonym for a protocol called
				[415] link SAML, center=(1057,812), url='https://en.wikipedia.org/wiki/Security_Assertion_Markup_Language'
					image
				StaticText . It’s a way for a company to easily let their employees log into all their software products, including your product.
			paragraph
				StaticText At smaller companies, employees use username+password or “Log in with Google” to sign into your product. At larger companies, employees instead expect to use services like Okta or Microsoft Entra (formerly “Azure AD”) to do sign-in. Those sign-ins happen using the SAML protocol. SSOReady makes it way easier to implement SAML.
			paragraph
				StaticText SAML logins have two steps:
			list
				listitem
					ListMarker 0.
					StaticText You
					[421] link initiate a SAML login, center=(750,1068), url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
						strong
					StaticText by redirecting your user to their corporate Okta/Google/Microsoft.
				listitem
					ListMarker 0.
					StaticText Their corporate Okta/Google/Microsoft redirects your user back to your app, and you
					link handle the SAML login, url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
						strong
					StaticText .
			paragraph
				StaticText Before this can happen, you and your customer need to exchange settings about each other. This process is done offline; you’ll give your customer some settings that SSOReady provides for you, and you’ll email your customer asking for some settings in return which you’ll input into SSOReady.
			paragraph
				StaticText We’ll cover how to do (1) and (2) in
				link Code implementation, url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
				StaticText . We’ll cover the setup work you’ll need to do inside SSOReady’s webapp in
				link Setting up SSOReady, url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				StaticText . We’ll cover the settings you’ll give and ask for in
				link Onboarding customers, url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
				StaticText .
			heading Code implementation
			paragraph
				StaticText As covered in
				link Basic concepts, url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
				StaticText , there are two steps involved in implementing SAML: initiating SAML logins, and handling SAML logins. Here’s how you do each.
			heading Initiating SAML logins
			paragraph
				image, url='https://app.buildwithfern.com/_next/image?url=https%3A%2F%2Ffiles.buildwithfern.com%2Fssoready.docs.buildwithfern.com%2Fdocs%2F2025-01-02T23%3A05%3A17.602Z%2Fpages%2Fquickstart-initiate.png&w=3840&q=75&dpl=dpl_E3br8NqLCTPPhihEjcHncTi4MC6y'
				button Expand image
			paragraph
				StaticText Under the hood, initiating SAML logins requires you to get your user’s browser to perform an HTTP POST against their corporate Okta/Google/Microsoft with a specific XML message. SSOReady abstracts all this work away into you just needing to redirect your user to a URL.
			paragraph
				StaticText SSOReady’s SDKs generate a URL for you, and then you simply forward your user to that URL using any mechanism that suits your tech stack.
			StaticText POST
			button /v1/saml/redirect
			button cURL, expanded=False, hasPopup='menu'
				image
			link, url='https://ssoready.com/docs/api-reference/saml/get-saml-redirect-url'
				image
			button
				image
			code
				table
					rowgroup
						row
							cell $
							cell curl -X POST https://api.ssoready.com/v1/saml/redirect \
						row
							cell >
							cell -H "Authorization: Bearer <apiKey>" \
						row
							cell >
							cell -H "Content-Type: application/json" \
						row
							cell >
							cell -d '{
						row
							cell >
							cell "organizationExternalId": "my_custom_external_id"
						row
							cell >
							cell }'
			StaticText Response
			button
				image
			code
				table
					rowgroup
						row
							cell 1
							cell {
						row
							cell 2
							cell "redirectUrl": "https://your.redirect.url"
						row
							cell 3
							cell }
			paragraph
				StaticText That code sample requires an API Key (
				code
					StaticText ssoready_sk_...
				StaticText ) and an
				code
					StaticText organizationExternalId
				StaticText . How you get those is covered in
				link Setting up SSOReady, url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				StaticText later on this page.
			image
			heading
			paragraph
				StaticText For recommendations on how to incorporate a “Log in with SAML” button into your login user experience, check out our docs on
				link Integrating SAML with your Login UI, url='https://ssoready.com/docs/saml/integrating-saml-into-your-login-ui'
				StaticText .
			heading Handling SAML logins
			paragraph
				image, url='https://app.buildwithfern.com/_next/image?url=https%3A%2F%2Ffiles.buildwithfern.com%2Fssoready.docs.buildwithfern.com%2Fdocs%2F2025-01-02T23%3A05%3A17.602Z%2Fpages%2Fquickstart-handle.png&w=3840&q=75&dpl=dpl_E3br8NqLCTPPhihEjcHncTi4MC6y'
				button Expand image
			paragraph
				StaticText Under the hood, SAML login details are sent to you in the form of your user’s web browser POST-ing you an XML message. You would then need to
				link authenticate that message, url='https://www.w3.org/TR/xmldsig-core1/'
					image
				StaticText before logging your user in.
			paragraph
				StaticText SSOReady abstracts this away; we handle authenticating the message, and instead forward your user to a callback page on your webapp with a “SAML access code”, which you can redeem in exchange for authenticated details about the user.
			paragraph
				StaticText So what you’ll need to do is create a new “SSOReady callback page” (typically something like
				code
					StaticText https://app.yourcompany.com/ssoready-callback
				StaticText ), where you’ll expect a
				code
					StaticText ?saml_access_code=saml_access_code_...
				StaticText query parameter in the URL. From your backend, you’ll exchange that access code for a user’s details:
			StaticText POST
			button /v1/saml/redeem
			button cURL, expanded=False, hasPopup='menu'
				image
			link, url='https://ssoready.com/docs/api-reference/saml/redeem-saml-access-code'
				image
			button
				image
			code
				table
					rowgroup
						row
							cell $
							cell curl -X POST https://api.ssoready.com/v1/saml/redeem \
						row
							cell >
							cell -H "Authorization: Bearer <apiKey>" \
						row
							cell >
							cell -H "Content-Type: application/json" \
						row
							cell >
							cell -d '{
						row
							cell >
							cell "samlAccessCode": "saml_access_code_..."
						row
							cell >
							cell }'
			StaticText Response
			button
				image
			code
				table
					rowgroup
						row
							cell 1
							cell {
						row
							cell 2
							cell "email": "john.doe@acme.com",
						row
							cell 3
							cell "organizationId": "org_7cu5hsy9vrbi5d2k1qvbh19lj",
						row
							cell 4
							cell "organizationExternalId": "my_custom_external_id"
						row
							cell 5
							cell }
			paragraph
				StaticText The response will include the user’s
				code
					StaticText email
				StaticText as well as the SSOReady
				code
					StaticText organizationId
				StaticText and
				code
					StaticText organizationExternalId
				StaticText they belong to. It’s your responsibility to then log the user in with that given email and organization using whatever mechanism your tech stack uses.
			paragraph
				StaticText How you tell us about your desired “SSOReady callback page”, as well as what
				code
					StaticText organizationId
				StaticText and
				code
					StaticText organizationExternalId
				StaticText mean, is covered in
				link Setting up SSOReady, url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				StaticText below.
			image
			heading
			paragraph
				StaticText For recommendations on how your SAML handling logic should work, check out our docs on
				link Handling SAML Logins and Just-in-Time Provisioning, url='https://ssoready.com/docs/saml/handling-saml-logins-jit-provisioning'
				StaticText .
			heading Setting up SSOReady
			paragraph
				StaticText In
				link Code implementation, url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
				StaticText , there were three missing pieces that you’d need to implement SSOReady:
			list
				listitem
					ListMarker 0.
					strong
						StaticText Where does the SSOReady callback page get configured?
					StaticText That information lives on
					link environments, url='https://ssoready.com/docs/saml/saml-quickstart#creating-environments'
					StaticText .
				listitem
					ListMarker 0.
					strong
						StaticText Where do I get an API key?
					StaticText You create
					link an API key, url='https://ssoready.com/docs/saml/saml-quickstart#creating-api-keys'
					StaticText scoped to an environment.
				listitem
					ListMarker 0.
					strong
						StaticText How do I get
						code
							StaticText organizationExternalId
						StaticText ?
					StaticText You create
					link an organization, url='https://ssoready.com/docs/saml/saml-quickstart#creating-organizations'
					StaticText in an environment, where you can choose an external ID convenient for you.
			paragraph
				StaticText This section will step you through how you’ll do all of this setup in SSOReady’s webapp. As a prerequisite step, you’ll need to
				link sign up for SSOReady, url='https://app.ssoready.com/login'
					image
				StaticText . It’s free and anyone can sign up, even with a personal email.
			heading Creating environments
			paragraph
				StaticText To create an environment, go
				link here, url='https://app.ssoready.com/environments/new'
					image
				StaticText . You’ll typically create one environment per deployment environment, e.g. one each for “production”, “staging”, and “local dev”. On an environment, you’ll assign a “Redirect URL”. That’s the URL your users get redirected to in
				link “Handling SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
				StaticText .
			heading Creating API keys
			paragraph
				StaticText API keys are scoped to an environment. When viewing an environment in the app, click “API Keys” on the left navbar. Then click “Create API Key”. A popup will show you your new API key’s secret (it starts with
				code
					StaticText ssoready_sk_...
				StaticText ). That’s the API key you’ll use in
				link “Initiating SAML Logins”, url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				StaticText and
				link “Handling SAML Logins”, url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
				StaticText .
			heading Creating organizations
			paragraph
				StaticText An organization corresponds to a corporate customer of yours. If you sold your product to Apple, Nvidia, and Amazon, you’d have three organizations in SSOReady: one each for Apple, Nvidia, and Amazon.
			paragraph
				StaticText Organizations belong to an environment. When viewing an environment in the app, the “Create organization” button creates a new organization. Organizations have two properties worth highlighting:
			list
				listitem
					ListMarker •
					StaticText An optional
					emphasis
						StaticText external ID
					StaticText , which you can assign. If you’re selling multi-tenant B2B software, you probably already have a concept that closely matches an SSOReady organization — usually, this is something named a “team”, “workspace”, “company”, or something similar. When creating an SSOReady organization, use your product’s counterpart to an organization ID as the external ID.
			paragraph
				StaticText You’ll provide the external ID as the
				code
					StaticText organizationExternalId
				StaticText in
				link “Initiating SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				StaticText . The external ID is returned to you when
				link “Redeeming SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#redeeming-saml-logins'
				StaticText .
			list
				listitem
					ListMarker •
					StaticText A set of
					emphasis
						StaticText domains
					StaticText . If you expect Apple’s employees will log in to your product from
					code
						StaticText @apple.com
					StaticText and
					code
						StaticText @shazam.com
					StaticText email addresses, then put
					code
						StaticText apple.com
					StaticText and
					code
						StaticText shazam.com
					StaticText here. SSOReady will enforce that users’ SAML logins come from these domains.
			heading Creating SAML connections
			paragraph
				StaticText A SAML connection holds onto SAML-related settings. In
				link “Onboarding customers”, url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
				StaticText , you’ll be providing and asking for settings. Those settings all live on an SSOReady SAML connection.
			paragraph
				StaticText SAML connections belong to an organization. When viewing an organization in the app, the “Create SAML connection” button creates a new SAML connection. Beyond the SAML-related settings covered in
				link “Onboarding customers”, url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
				StaticText , SAML connections have one setting of note: whether they are
				emphasis
					StaticText primary
				StaticText .
			paragraph
				StaticText Each organization has up to one primary SAML connection. In
				link “Initiating SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				StaticText , you provide an
				code
					StaticText organizationExternalId
				StaticText . SSOReady will use that organization’s primary SAML connection to initiate the login.
			heading Onboarding customers
			paragraph
				StaticText In
				link Basic concepts, url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
				StaticText , we mentioned that you and your customer need to exchange details about each other before you can do SAML logins. This process happens offline — there’s no coding involved.
			paragraph
				StaticText You have to go through this process each time a new company wants to set up SAML. It’s inherent to how SAML was designed.
			paragraph
				StaticText With SSOReady, you have two options for onboarding customers onto SAML — that is, exchanging SAML-related settings with them. You can:
			list
				listitem
					ListMarker 0.
					StaticText Use SSOReady’s
					link self-serve setup links, url='https://ssoready.com/docs/idp-configuration/enabling-self-service-configuration-for-your-customers'
					StaticText . You give your customers a link, where they can set up SAML on their own. It’s a slick experience for your customers, and they’ll get set up in minutes.
					strong
						StaticText We recommend this approach.
				listitem
					ListMarker 0.
					StaticText Give your customers instructions yourself, over email/slack/Zoom/etc.
			paragraph
				StaticText If you go with option (2), be advised that SAML identity providers (e.g. Okta, Microsoft Entra, Google Workspace, etc.) don’t use the same terminology for these identical details. To deal with that, we’ve prepared a separate set of documentation for you to follow depending on what identity provider your customer uses:
			list
				listitem
					ListMarker •
					link Okta, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/okta/saml-with-okta'
				listitem
					ListMarker •
					link Google Workspace, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/google/saml-with-google'
				listitem
					ListMarker •
					link Microsoft Entra, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/entra-formerly-azure-ad/saml-with-entra'
					StaticText (aka Microsoft Azure Active Directory, Microsoft Azure AD)
				listitem
					ListMarker •
					link JumpCloud, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/jumpcloud/saml-with-jumpcloud'
				listitem
					ListMarker •
					link Ping Identity, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/ping-identity/saml-with-ping-identity'
			paragraph
				StaticText In all cases, you’re ultimately going to:
			list
				listitem
					ListMarker 0.
					StaticText Give your customers an “SP Entity ID” and “SP ACS URL”. SSOReady’s webapp gives you both.
				listitem
					ListMarker 0.
					StaticText Ask your customers for an “IDP Entity ID”, “IDP Redirect URL”, and “IDP Certificate” which you input into SSOReady.
			paragraph
				StaticText Once you have all those details, you’ll be ready to accept SAML logins!
			StaticText Was this page helpful?
			button Yes, expanded=False, hasPopup='dialog'
				image
			button No, expanded=False, hasPopup='dialog'
				image
			link SAML: A technical primer Up Next, url='https://ssoready.com/docs/saml/saml-technical-primer'
				image
			link Built with, url='https://buildwithfern.com/?utm_campaign=buildWith&utm_medium=docs&utm_source=ssoready.com'
				image
	contentinfo
	alert, atomic
```
</details>



```
RootWebArea Getting started with SSOReady SAML — SSOReady Docs, focused, url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
	banner
		navigation primary
			[84] link SSOReady Docs, center=(349,678), url='https://ssoready.com/'
				image SSOReady Docs, url='https://app.buildwithfern.com/_next/image?url=https%3A%2F%2Ffiles.buildwithfern.com%2Fssoready.docs.buildwithfern.com%2Fdocs%2F2025-01-02T23%3A05%3A17.602Z%2Fdocs%2Fassets%2Flogo.png&w=128&q=100&dpl=dpl_E3br8NqLCTPPhihEjcHncTi4MC6y'
```
<details><summary>Show more</summary>

```
			[89] button Search... /, center=(960,678), inner_text=Search...
/
				image
			[97] link Login, center=(1594,678), url='https://app.ssoready.com/'
				image
	navigation secondary
		list
			listitem
				list
					listitem
						[120] link Introduction, center=(402,752), url='https://ssoready.com/docs/introduction'
			listitem
				StaticText SAML (Enterprise SSO)
				list
					listitem
						[129] link SAML Quickstart, center=(402,852), url='https://ssoready.com/docs/saml/saml-quickstart'
					listitem
						[134] link SAML: A technical primer, center=(402,888), url='https://ssoready.com/docs/saml/saml-technical-primer'
					listitem
						[139] link Integrating SAML with your Login UI, center=(402,924), url='https://ssoready.com/docs/saml/integrating-saml-into-your-login-ui'
					listitem
						[144] link Handling SAML Logins + JIT Provisioning, center=(402,970), url='https://ssoready.com/docs/saml/handling-saml-logins-jit-provisioning'
			listitem
				StaticText SCIM (Enterprise Directory Sync)
				list
					listitem
						[153] link SCIM Quickstart, center=(402,1080), url='https://ssoready.com/docs/scim/scim-quickstart'
			listitem
				StaticText SDKs
				list
					listitem
						[162] link TypeScript SDK, center=(402,1180), url='https://github.com/ssoready/ssoready-typescript'
							image
					listitem
						[170] link Python SDK, center=(402,1216), url='https://github.com/ssoready/ssoready-python'
							image
					listitem
						[178] link Go SDK, center=(402,1252), url='https://github.com/ssoready/ssoready-go'
							image
					listitem
						[186] link Java SDK, center=(402,1288), url='https://github.com/ssoready/ssoready-java'
							image
					listitem
						[194] link C# SDK, center=(402,1324), url='https://github.com/ssoready/ssoready-csharp'
							image
					listitem
						[202] link Ruby SDK, center=(402,1360), url='https://github.com/ssoready/ssoready-ruby'
							image
					listitem
						[210] link PHP SDK, center=(402,1396), url='https://github.com/ssoready/ssoready-php'
							image
			listitem
				StaticText SAML-over-OAuth
				list
					listitem
						[222] link SAML over OAuth (SAML NextAuth.js integration), center=(402,1506), url='https://ssoready.com/docs/saml-over-oauth-saml-nextauth-integration'
					listitem
						[227] link SAML for Firebase, center=(402,1552), url='https://ssoready.com/docs/firebase'
			listitem
				StaticText IDP configuration
				list
					listitem
						[236] link Enabling self-service configuration for your customers, center=(402,1662), url='https://ssoready.com/docs/idp-configuration/enabling-self-service-configuration-for-your-customers'
					listitem
						[242] button Guides for common identity providers, center=(402,1718)
							image
			listitem
				StaticText SSOReady concepts
				list
					listitem
						link Overview, url='https://ssoready.com/docs/ssoready-concepts/overview'
					listitem
						link Environments, url='https://ssoready.com/docs/ssoready-concepts/environments'
					listitem
						link Organizations, url='https://ssoready.com/docs/ssoready-concepts/organizations'
					listitem
						link SAML Connections, url='https://ssoready.com/docs/ssoready-concepts/saml-connections'
					listitem
						link SAML Login Flows, url='https://ssoready.com/docs/ssoready-concepts/saml-login-flows'
					listitem
						link SCIM Directories, url='https://ssoready.com/docs/ssoready-concepts/scim-directories'
					listitem
						link SCIM Users, url='https://ssoready.com/docs/ssoready-concepts/scim-users'
					listitem
						link SCIM Groups, url='https://ssoready.com/docs/ssoready-concepts/scim-groups'
					listitem
						link SCIM Request Logs, url='https://ssoready.com/docs/ssoready-concepts/scim-request-logs'
			listitem
				StaticText Management API
				list
					listitem
						link Management API, url='https://ssoready.com/docs/management-api'
			listitem
				StaticText DummyIDP
				list
					listitem
						link Testing SAML/SCIM with DummyIDP, url='https://ssoready.com/docs/dummyidp'
			listitem
				StaticText Self-Hosting
				list
					listitem
						link Self-Hosting SSOReady, url='https://ssoready.com/docs/self-hosting-ssoready'
			listitem
				StaticText API Reference
				list
					listitem
						button SAML
							image
					listitem
						button SCIM
							image
					listitem
						button Management API
							image
	main
		complementary
			StaticText On this page
			list
				listitem
					[368] link Getting started with SSOReady SAML, center=(1519,794), url='https://ssoready.com/docs/saml/saml-quickstart#getting-started-with-ssoready-saml'
				listitem
					[370] link Basic concepts, center=(1519,832), url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
				listitem
					[372] link Code implementation, center=(1519,860), url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
				listitem
					[374] link Initiating SAML logins, center=(1519,888), url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				listitem
					[376] link Handling SAML logins, center=(1519,916), url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
				listitem
					[378] link Setting up SSOReady, center=(1519,944), url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				listitem
					[380] link Creating environments, center=(1519,972), url='https://ssoready.com/docs/saml/saml-quickstart#creating-environments'
				listitem
					[382] link Creating API keys, center=(1519,1000), url='https://ssoready.com/docs/saml/saml-quickstart#creating-api-keys'
				listitem
					[384] link Creating organizations, center=(1519,1028), url='https://ssoready.com/docs/saml/saml-quickstart#creating-organizations'
				listitem
					[386] link Creating SAML connections, center=(1519,1056), url='https://ssoready.com/docs/saml/saml-quickstart#creating-saml-connections'
				listitem
					[388] link Onboarding customers, center=(1519,1084), url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
		article
			link SAML (Enterprise SSO), url='https://ssoready.com/docs/saml/saml-quickstart'
			heading SAML Quickstart
				paragraph
			paragraph
				StaticText Start accepting SAML logins this afternoon
			heading Getting started with SSOReady SAML
			paragraph
				StaticText Welcome to the SSOReady quickstart guide! This guide will take you through:
			list
				listitem
					ListMarker 0.
					link Basic concepts., focused, url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
						strong
					StaticText How Enterprise SSO / SAML works at a high level, and how SSOReady will help you implement it.
				listitem
					ListMarker 0.
					link Code implementation., url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
						strong
					StaticText What you’ll need to build, and how to use SSOReady’s SDK.
				listitem
					ListMarker 0.
					link Onboarding customers., url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
						strong
					StaticText SAML requires both you and your customer to do setup. SSOReady automates your end of the equation, and this section describes what instructions you’ll give to your customers.
			paragraph
				StaticText SSOReady is just an authentication middleware layer. SSOReady doesn’t “own” your users, and it doesn’t require you to use any particular tech stack. That’s on purpose — it makes onboarding easier for you, and it forces us to keep earning your business in the long run, because churning is easier.
			[413] heading Basic concepts, center=(960,747)
			paragraph
				StaticText ”Enterprise SSO” is mostly a synonym for a protocol called
				[415] link SAML, center=(1057,812), url='https://en.wikipedia.org/wiki/Security_Assertion_Markup_Language'
					image
				StaticText . It’s a way for a company to easily let their employees log into all their software products, including your product.
			paragraph
				StaticText At smaller companies, employees use username+password or “Log in with Google” to sign into your product. At larger companies, employees instead expect to use services like Okta or Microsoft Entra (formerly “Azure AD”) to do sign-in. Those sign-ins happen using the SAML protocol. SSOReady makes it way easier to implement SAML.
			paragraph
				StaticText SAML logins have two steps:
			list
				listitem
					ListMarker 0.
					StaticText You
					[421] link initiate a SAML login, center=(750,1068), url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
						strong
					StaticText by redirecting your user to their corporate Okta/Google/Microsoft.
				[423] listitem, center=(973,1119), inner_text=Their corporate Okta/Google/Microsoft redirects your user back to your app, and you handle the SAML login.
					ListMarker 0.
					StaticText Their corporate Okta/Google/Microsoft redirects your user back to your app, and you
					link handle the SAML login, url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
						strong
					StaticText .
			paragraph
				StaticText Before this can happen, you and your customer need to exchange settings about each other. This process is done offline; you’ll give your customer some settings that SSOReady provides for you, and you’ll email your customer asking for some settings in return which you’ll input into SSOReady.
			paragraph
				StaticText We’ll cover how to do (1) and (2) in
				[428] link Code implementation, center=(942,1284), url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
				StaticText . We’ll cover the setup work you’ll need to do inside SSOReady’s webapp in
				[429] link Setting up SSOReady, center=(950,1312), url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				StaticText . We’ll cover the settings you’ll give and ask for in
				[430] link Onboarding customers, center=(765,1340), url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
				StaticText .
			[431] heading Code implementation, center=(960,1429)
			paragraph
				StaticText As covered in
				[433] link Basic concepts, center=(768,1494), url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
				StaticText , there are two steps involved in implementing SAML: initiating SAML logins, and handling SAML logins. Here’s how you do each.
			[434] heading Initiating SAML logins, center=(960,1601)
			paragraph
				image, url='https://app.buildwithfern.com/_next/image?url=https%3A%2F%2Ffiles.buildwithfern.com%2Fssoready.docs.buildwithfern.com%2Fdocs%2F2025-01-02T23%3A05%3A17.602Z%2Fpages%2Fquickstart-initiate.png&w=3840&q=75&dpl=dpl_E3br8NqLCTPPhihEjcHncTi4MC6y'
				button Expand image
			paragraph
				StaticText Under the hood, initiating SAML logins requires you to get your user’s browser to perform an HTTP POST against their corporate Okta/Google/Microsoft with a specific XML message. SSOReady abstracts all this work away into you just needing to redirect your user to a URL.
			paragraph
				StaticText SSOReady’s SDKs generate a URL for you, and then you simply forward your user to that URL using any mechanism that suits your tech stack.
			StaticText POST
			button /v1/saml/redirect
			button cURL, expanded=False, hasPopup='menu'
				image
			link, url='https://ssoready.com/docs/api-reference/saml/get-saml-redirect-url'
				image
			button
				image
			code
				table
					rowgroup
						row
							cell $
							cell curl -X POST https://api.ssoready.com/v1/saml/redirect \
						row
							cell >
							cell -H "Authorization: Bearer <apiKey>" \
						row
							cell >
							cell -H "Content-Type: application/json" \
						row
							cell >
							cell -d '{
						row
							cell >
							cell "organizationExternalId": "my_custom_external_id"
						row
							cell >
							cell }'
			StaticText Response
			button
				image
			code
				table
					rowgroup
						row
							cell 1
							cell {
						row
							cell 2
							cell "redirectUrl": "https://your.redirect.url"
						row
							cell 3
							cell }
			paragraph
				StaticText That code sample requires an API Key (
				code
					StaticText ssoready_sk_...
				StaticText ) and an
				code
					StaticText organizationExternalId
				StaticText . How you get those is covered in
				link Setting up SSOReady, url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				StaticText later on this page.
			image
			heading
			paragraph
				StaticText For recommendations on how to incorporate a “Log in with SAML” button into your login user experience, check out our docs on
				link Integrating SAML with your Login UI, url='https://ssoready.com/docs/saml/integrating-saml-into-your-login-ui'
				StaticText .
			heading Handling SAML logins
			paragraph
				image, url='https://app.buildwithfern.com/_next/image?url=https%3A%2F%2Ffiles.buildwithfern.com%2Fssoready.docs.buildwithfern.com%2Fdocs%2F2025-01-02T23%3A05%3A17.602Z%2Fpages%2Fquickstart-handle.png&w=3840&q=75&dpl=dpl_E3br8NqLCTPPhihEjcHncTi4MC6y'
				button Expand image
			paragraph
				StaticText Under the hood, SAML login details are sent to you in the form of your user’s web browser POST-ing you an XML message. You would then need to
				link authenticate that message, url='https://www.w3.org/TR/xmldsig-core1/'
					image
				StaticText before logging your user in.
			paragraph
				StaticText SSOReady abstracts this away; we handle authenticating the message, and instead forward your user to a callback page on your webapp with a “SAML access code”, which you can redeem in exchange for authenticated details about the user.
			paragraph
				StaticText So what you’ll need to do is create a new “SSOReady callback page” (typically something like
				code
					StaticText https://app.yourcompany.com/ssoready-callback
				StaticText ), where you’ll expect a
				code
					StaticText ?saml_access_code=saml_access_code_...
				StaticText query parameter in the URL. From your backend, you’ll exchange that access code for a user’s details:
			StaticText POST
			button /v1/saml/redeem
			button cURL, expanded=False, hasPopup='menu'
				image
			link, url='https://ssoready.com/docs/api-reference/saml/redeem-saml-access-code'
				image
			button
				image
			code
				table
					rowgroup
						row
							cell $
							cell curl -X POST https://api.ssoready.com/v1/saml/redeem \
						row
							cell >
							cell -H "Authorization: Bearer <apiKey>" \
						row
							cell >
							cell -H "Content-Type: application/json" \
						row
							cell >
							cell -d '{
						row
							cell >
							cell "samlAccessCode": "saml_access_code_..."
						row
							cell >
							cell }'
			StaticText Response
			button
				image
			code
				table
					rowgroup
						row
							cell 1
							cell {
						row
							cell 2
							cell "email": "john.doe@acme.com",
						row
							cell 3
							cell "organizationId": "org_7cu5hsy9vrbi5d2k1qvbh19lj",
						row
							cell 4
							cell "organizationExternalId": "my_custom_external_id"
						row
							cell 5
							cell }
			paragraph
				StaticText The response will include the user’s
				code
					StaticText email
				StaticText as well as the SSOReady
				code
					StaticText organizationId
				StaticText and
				code
					StaticText organizationExternalId
				StaticText they belong to. It’s your responsibility to then log the user in with that given email and organization using whatever mechanism your tech stack uses.
			paragraph
				StaticText How you tell us about your desired “SSOReady callback page”, as well as what
				code
					StaticText organizationId
				StaticText and
				code
					StaticText organizationExternalId
				StaticText mean, is covered in
				link Setting up SSOReady, url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				StaticText below.
			image
			heading
			paragraph
				StaticText For recommendations on how your SAML handling logic should work, check out our docs on
				link Handling SAML Logins and Just-in-Time Provisioning, url='https://ssoready.com/docs/saml/handling-saml-logins-jit-provisioning'
				StaticText .
			heading Setting up SSOReady
			paragraph
				StaticText In
				link Code implementation, url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
				StaticText , there were three missing pieces that you’d need to implement SSOReady:
			list
				listitem
					ListMarker 0.
					strong
						StaticText Where does the SSOReady callback page get configured?
					StaticText That information lives on
					link environments, url='https://ssoready.com/docs/saml/saml-quickstart#creating-environments'
					StaticText .
				listitem
					ListMarker 0.
					strong
						StaticText Where do I get an API key?
					StaticText You create
					link an API key, url='https://ssoready.com/docs/saml/saml-quickstart#creating-api-keys'
					StaticText scoped to an environment.
				listitem
					ListMarker 0.
					strong
						StaticText How do I get
						code
							StaticText organizationExternalId
						StaticText ?
					StaticText You create
					link an organization, url='https://ssoready.com/docs/saml/saml-quickstart#creating-organizations'
					StaticText in an environment, where you can choose an external ID convenient for you.
			paragraph
				StaticText This section will step you through how you’ll do all of this setup in SSOReady’s webapp. As a prerequisite step, you’ll need to
				link sign up for SSOReady, url='https://app.ssoready.com/login'
					image
				StaticText . It’s free and anyone can sign up, even with a personal email.
			heading Creating environments
			paragraph
				StaticText To create an environment, go
				link here, url='https://app.ssoready.com/environments/new'
					image
				StaticText . You’ll typically create one environment per deployment environment, e.g. one each for “production”, “staging”, and “local dev”. On an environment, you’ll assign a “Redirect URL”. That’s the URL your users get redirected to in
				link “Handling SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
				StaticText .
			heading Creating API keys
			paragraph
				StaticText API keys are scoped to an environment. When viewing an environment in the app, click “API Keys” on the left navbar. Then click “Create API Key”. A popup will show you your new API key’s secret (it starts with
				code
					StaticText ssoready_sk_...
				StaticText ). That’s the API key you’ll use in
				link “Initiating SAML Logins”, url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				StaticText and
				link “Handling SAML Logins”, url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
				StaticText .
			heading Creating organizations
			paragraph
				StaticText An organization corresponds to a corporate customer of yours. If you sold your product to Apple, Nvidia, and Amazon, you’d have three organizations in SSOReady: one each for Apple, Nvidia, and Amazon.
			paragraph
				StaticText Organizations belong to an environment. When viewing an environment in the app, the “Create organization” button creates a new organization. Organizations have two properties worth highlighting:
			list
				listitem
					ListMarker •
					StaticText An optional
					emphasis
						StaticText external ID
					StaticText , which you can assign. If you’re selling multi-tenant B2B software, you probably already have a concept that closely matches an SSOReady organization — usually, this is something named a “team”, “workspace”, “company”, or something similar. When creating an SSOReady organization, use your product’s counterpart to an organization ID as the external ID.
			paragraph
				StaticText You’ll provide the external ID as the
				code
					StaticText organizationExternalId
				StaticText in
				link “Initiating SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				StaticText . The external ID is returned to you when
				link “Redeeming SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#redeeming-saml-logins'
				StaticText .
			list
				listitem
					ListMarker •
					StaticText A set of
					emphasis
						StaticText domains
					StaticText . If you expect Apple’s employees will log in to your product from
					code
						StaticText @apple.com
					StaticText and
					code
						StaticText @shazam.com
					StaticText email addresses, then put
					code
						StaticText apple.com
					StaticText and
					code
						StaticText shazam.com
					StaticText here. SSOReady will enforce that users’ SAML logins come from these domains.
			heading Creating SAML connections
			paragraph
				StaticText A SAML connection holds onto SAML-related settings. In
				link “Onboarding customers”, url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
				StaticText , you’ll be providing and asking for settings. Those settings all live on an SSOReady SAML connection.
			paragraph
				StaticText SAML connections belong to an organization. When viewing an organization in the app, the “Create SAML connection” button creates a new SAML connection. Beyond the SAML-related settings covered in
				link “Onboarding customers”, url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
				StaticText , SAML connections have one setting of note: whether they are
				emphasis
					StaticText primary
				StaticText .
			paragraph
				StaticText Each organization has up to one primary SAML connection. In
				link “Initiating SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				StaticText , you provide an
				code
					StaticText organizationExternalId
				StaticText . SSOReady will use that organization’s primary SAML connection to initiate the login.
			heading Onboarding customers
			paragraph
				StaticText In
				link Basic concepts, url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
				StaticText , we mentioned that you and your customer need to exchange details about each other before you can do SAML logins. This process happens offline — there’s no coding involved.
			paragraph
				StaticText You have to go through this process each time a new company wants to set up SAML. It’s inherent to how SAML was designed.
			paragraph
				StaticText With SSOReady, you have two options for onboarding customers onto SAML — that is, exchanging SAML-related settings with them. You can:
			list
				listitem
					ListMarker 0.
					StaticText Use SSOReady’s
					link self-serve setup links, url='https://ssoready.com/docs/idp-configuration/enabling-self-service-configuration-for-your-customers'
					StaticText . You give your customers a link, where they can set up SAML on their own. It’s a slick experience for your customers, and they’ll get set up in minutes.
					strong
						StaticText We recommend this approach.
				listitem
					ListMarker 0.
					StaticText Give your customers instructions yourself, over email/slack/Zoom/etc.
			paragraph
				StaticText If you go with option (2), be advised that SAML identity providers (e.g. Okta, Microsoft Entra, Google Workspace, etc.) don’t use the same terminology for these identical details. To deal with that, we’ve prepared a separate set of documentation for you to follow depending on what identity provider your customer uses:
			list
				listitem
					ListMarker •
					link Okta, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/okta/saml-with-okta'
				listitem
					ListMarker •
					link Google Workspace, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/google/saml-with-google'
				listitem
					ListMarker •
					link Microsoft Entra, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/entra-formerly-azure-ad/saml-with-entra'
					StaticText (aka Microsoft Azure Active Directory, Microsoft Azure AD)
				listitem
					ListMarker •
					link JumpCloud, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/jumpcloud/saml-with-jumpcloud'
				listitem
					ListMarker •
					link Ping Identity, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/ping-identity/saml-with-ping-identity'
			paragraph
				StaticText In all cases, you’re ultimately going to:
			list
				listitem
					ListMarker 0.
					StaticText Give your customers an “SP Entity ID” and “SP ACS URL”. SSOReady’s webapp gives you both.
				listitem
					ListMarker 0.
					StaticText Ask your customers for an “IDP Entity ID”, “IDP Redirect URL”, and “IDP Certificate” which you input into SSOReady.
			paragraph
				StaticText Once you have all those details, you’ll be ready to accept SAML logins!
			StaticText Was this page helpful?
			button Yes, expanded=False, hasPopup='dialog'
				image
			button No, expanded=False, hasPopup='dialog'
				image
			link SAML: A technical primer Up Next, url='https://ssoready.com/docs/saml/saml-technical-primer'
				image
			link Built with, url='https://buildwithfern.com/?utm_campaign=buildWith&utm_medium=docs&utm_source=ssoready.com'
				image
	contentinfo
	alert, atomic
		StaticText Getting started with SSOReady SAML — SSOReady Docs
```
</details>

**Reasoning for action:** By clicking the Basic concepts link (with ID 404), I am accessing a section that details the foundational concepts necessary to understand how SAML works with SSOReady. This is crucial for the user as the task involves integrating SAML SSO, and having a solid understanding of these basic concepts will facilitate their implementation process. This step is necessary to fulfill the user story requirements.

**Action:** click(404) # Click on the Basic concepts link to explore the foundational information about SAML and how it works with SSOReady.

**Change Description:** After the agent clicked on the 'Basic concepts' link, the browser navigated to the corresponding section within the SSOReady documentation, updating the page to show foundational information on how Enterprise SSO and SAML operate, along with its integration into SSOReady.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://ssoready.com/docs/saml/saml-quickstart#basic-concepts

https://ssoready.com/docs/saml/saml-quickstart#code-implementation

**Content (before/after):** 

```
RootWebArea Getting started with SSOReady SAML — SSOReady Docs, focused, url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
	banner
		navigation primary
			[84] link SSOReady Docs, center=(349,678), url='https://ssoready.com/'
				image SSOReady Docs, url='https://app.buildwithfern.com/_next/image?url=https%3A%2F%2Ffiles.buildwithfern.com%2Fssoready.docs.buildwithfern.com%2Fdocs%2F2025-01-02T23%3A05%3A17.602Z%2Fdocs%2Fassets%2Flogo.png&w=128&q=100&dpl=dpl_E3br8NqLCTPPhihEjcHncTi4MC6y'
```
<details><summary>Show more</summary>

```
			[89] button Search... /, center=(960,678), inner_text=Search...
/
				image
			[97] link Login, center=(1594,678), url='https://app.ssoready.com/'
				image
	navigation secondary
		list
			listitem
				list
					listitem
						[120] link Introduction, center=(402,752), url='https://ssoready.com/docs/introduction'
			listitem
				StaticText SAML (Enterprise SSO)
				list
					listitem
						[129] link SAML Quickstart, center=(402,852), url='https://ssoready.com/docs/saml/saml-quickstart'
					listitem
						[134] link SAML: A technical primer, center=(402,888), url='https://ssoready.com/docs/saml/saml-technical-primer'
					listitem
						[139] link Integrating SAML with your Login UI, center=(402,924), url='https://ssoready.com/docs/saml/integrating-saml-into-your-login-ui'
					listitem
						[144] link Handling SAML Logins + JIT Provisioning, center=(402,970), url='https://ssoready.com/docs/saml/handling-saml-logins-jit-provisioning'
			listitem
				StaticText SCIM (Enterprise Directory Sync)
				list
					listitem
						[153] link SCIM Quickstart, center=(402,1080), url='https://ssoready.com/docs/scim/scim-quickstart'
			listitem
				StaticText SDKs
				list
					listitem
						[162] link TypeScript SDK, center=(402,1180), url='https://github.com/ssoready/ssoready-typescript'
							image
					listitem
						[170] link Python SDK, center=(402,1216), url='https://github.com/ssoready/ssoready-python'
							image
					listitem
						[178] link Go SDK, center=(402,1252), url='https://github.com/ssoready/ssoready-go'
							image
					listitem
						[186] link Java SDK, center=(402,1288), url='https://github.com/ssoready/ssoready-java'
							image
					listitem
						[194] link C# SDK, center=(402,1324), url='https://github.com/ssoready/ssoready-csharp'
							image
					listitem
						[202] link Ruby SDK, center=(402,1360), url='https://github.com/ssoready/ssoready-ruby'
							image
					listitem
						[210] link PHP SDK, center=(402,1396), url='https://github.com/ssoready/ssoready-php'
							image
			listitem
				StaticText SAML-over-OAuth
				list
					listitem
						[222] link SAML over OAuth (SAML NextAuth.js integration), center=(402,1506), url='https://ssoready.com/docs/saml-over-oauth-saml-nextauth-integration'
					listitem
						[227] link SAML for Firebase, center=(402,1552), url='https://ssoready.com/docs/firebase'
			listitem
				StaticText IDP configuration
				list
					listitem
						[236] link Enabling self-service configuration for your customers, center=(402,1662), url='https://ssoready.com/docs/idp-configuration/enabling-self-service-configuration-for-your-customers'
					listitem
						[242] button Guides for common identity providers, center=(402,1718)
							image
			listitem
				StaticText SSOReady concepts
				list
					listitem
						link Overview, url='https://ssoready.com/docs/ssoready-concepts/overview'
					listitem
						link Environments, url='https://ssoready.com/docs/ssoready-concepts/environments'
					listitem
						link Organizations, url='https://ssoready.com/docs/ssoready-concepts/organizations'
					listitem
						link SAML Connections, url='https://ssoready.com/docs/ssoready-concepts/saml-connections'
					listitem
						link SAML Login Flows, url='https://ssoready.com/docs/ssoready-concepts/saml-login-flows'
					listitem
						link SCIM Directories, url='https://ssoready.com/docs/ssoready-concepts/scim-directories'
					listitem
						link SCIM Users, url='https://ssoready.com/docs/ssoready-concepts/scim-users'
					listitem
						link SCIM Groups, url='https://ssoready.com/docs/ssoready-concepts/scim-groups'
					listitem
						link SCIM Request Logs, url='https://ssoready.com/docs/ssoready-concepts/scim-request-logs'
			listitem
				StaticText Management API
				list
					listitem
						link Management API, url='https://ssoready.com/docs/management-api'
			listitem
				StaticText DummyIDP
				list
					listitem
						link Testing SAML/SCIM with DummyIDP, url='https://ssoready.com/docs/dummyidp'
			listitem
				StaticText Self-Hosting
				list
					listitem
						link Self-Hosting SSOReady, url='https://ssoready.com/docs/self-hosting-ssoready'
			listitem
				StaticText API Reference
				list
					listitem
						button SAML
							image
					listitem
						button SCIM
							image
					listitem
						button Management API
							image
	main
		complementary
			StaticText On this page
			list
				listitem
					[368] link Getting started with SSOReady SAML, center=(1519,794), url='https://ssoready.com/docs/saml/saml-quickstart#getting-started-with-ssoready-saml'
				listitem
					[370] link Basic concepts, center=(1519,832), url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
				listitem
					[372] link Code implementation, center=(1519,860), url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
				listitem
					[374] link Initiating SAML logins, center=(1519,888), url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				listitem
					[376] link Handling SAML logins, center=(1519,916), url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
				listitem
					[378] link Setting up SSOReady, center=(1519,944), url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				listitem
					[380] link Creating environments, center=(1519,972), url='https://ssoready.com/docs/saml/saml-quickstart#creating-environments'
				listitem
					[382] link Creating API keys, center=(1519,1000), url='https://ssoready.com/docs/saml/saml-quickstart#creating-api-keys'
				listitem
					[384] link Creating organizations, center=(1519,1028), url='https://ssoready.com/docs/saml/saml-quickstart#creating-organizations'
				listitem
					[386] link Creating SAML connections, center=(1519,1056), url='https://ssoready.com/docs/saml/saml-quickstart#creating-saml-connections'
				listitem
					[388] link Onboarding customers, center=(1519,1084), url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
		article
			link SAML (Enterprise SSO), url='https://ssoready.com/docs/saml/saml-quickstart'
			heading SAML Quickstart
				paragraph
			paragraph
				StaticText Start accepting SAML logins this afternoon
			heading Getting started with SSOReady SAML
			paragraph
				StaticText Welcome to the SSOReady quickstart guide! This guide will take you through:
			list
				listitem
					ListMarker 0.
					link Basic concepts., focused, url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
						strong
					StaticText How Enterprise SSO / SAML works at a high level, and how SSOReady will help you implement it.
				listitem
					ListMarker 0.
					link Code implementation., url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
						strong
					StaticText What you’ll need to build, and how to use SSOReady’s SDK.
				listitem
					ListMarker 0.
					link Onboarding customers., url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
						strong
					StaticText SAML requires both you and your customer to do setup. SSOReady automates your end of the equation, and this section describes what instructions you’ll give to your customers.
			paragraph
				StaticText SSOReady is just an authentication middleware layer. SSOReady doesn’t “own” your users, and it doesn’t require you to use any particular tech stack. That’s on purpose — it makes onboarding easier for you, and it forces us to keep earning your business in the long run, because churning is easier.
			[413] heading Basic concepts, center=(960,747)
			paragraph
				StaticText ”Enterprise SSO” is mostly a synonym for a protocol called
				[415] link SAML, center=(1057,812), url='https://en.wikipedia.org/wiki/Security_Assertion_Markup_Language'
					image
				StaticText . It’s a way for a company to easily let their employees log into all their software products, including your product.
			paragraph
				StaticText At smaller companies, employees use username+password or “Log in with Google” to sign into your product. At larger companies, employees instead expect to use services like Okta or Microsoft Entra (formerly “Azure AD”) to do sign-in. Those sign-ins happen using the SAML protocol. SSOReady makes it way easier to implement SAML.
			paragraph
				StaticText SAML logins have two steps:
			list
				listitem
					ListMarker 0.
					StaticText You
					[421] link initiate a SAML login, center=(750,1068), url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
						strong
					StaticText by redirecting your user to their corporate Okta/Google/Microsoft.
				[423] listitem, center=(973,1119), inner_text=Their corporate Okta/Google/Microsoft redirects your user back to your app, and you handle the SAML login.
					ListMarker 0.
					StaticText Their corporate Okta/Google/Microsoft redirects your user back to your app, and you
					link handle the SAML login, url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
						strong
					StaticText .
			paragraph
				StaticText Before this can happen, you and your customer need to exchange settings about each other. This process is done offline; you’ll give your customer some settings that SSOReady provides for you, and you’ll email your customer asking for some settings in return which you’ll input into SSOReady.
			paragraph
				StaticText We’ll cover how to do (1) and (2) in
				[428] link Code implementation, center=(942,1284), url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
				StaticText . We’ll cover the setup work you’ll need to do inside SSOReady’s webapp in
				[429] link Setting up SSOReady, center=(950,1312), url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				StaticText . We’ll cover the settings you’ll give and ask for in
				[430] link Onboarding customers, center=(765,1340), url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
				StaticText .
			[431] heading Code implementation, center=(960,1429)
			paragraph
				StaticText As covered in
				[433] link Basic concepts, center=(768,1494), url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
				StaticText , there are two steps involved in implementing SAML: initiating SAML logins, and handling SAML logins. Here’s how you do each.
			[434] heading Initiating SAML logins, center=(960,1601)
			paragraph
				image, url='https://app.buildwithfern.com/_next/image?url=https%3A%2F%2Ffiles.buildwithfern.com%2Fssoready.docs.buildwithfern.com%2Fdocs%2F2025-01-02T23%3A05%3A17.602Z%2Fpages%2Fquickstart-initiate.png&w=3840&q=75&dpl=dpl_E3br8NqLCTPPhihEjcHncTi4MC6y'
				button Expand image
			paragraph
				StaticText Under the hood, initiating SAML logins requires you to get your user’s browser to perform an HTTP POST against their corporate Okta/Google/Microsoft with a specific XML message. SSOReady abstracts all this work away into you just needing to redirect your user to a URL.
			paragraph
				StaticText SSOReady’s SDKs generate a URL for you, and then you simply forward your user to that URL using any mechanism that suits your tech stack.
			StaticText POST
			button /v1/saml/redirect
			button cURL, expanded=False, hasPopup='menu'
				image
			link, url='https://ssoready.com/docs/api-reference/saml/get-saml-redirect-url'
				image
			button
				image
			code
				table
					rowgroup
						row
							cell $
							cell curl -X POST https://api.ssoready.com/v1/saml/redirect \
						row
							cell >
							cell -H "Authorization: Bearer <apiKey>" \
						row
							cell >
							cell -H "Content-Type: application/json" \
						row
							cell >
							cell -d '{
						row
							cell >
							cell "organizationExternalId": "my_custom_external_id"
						row
							cell >
							cell }'
			StaticText Response
			button
				image
			code
				table
					rowgroup
						row
							cell 1
							cell {
						row
							cell 2
							cell "redirectUrl": "https://your.redirect.url"
						row
							cell 3
							cell }
			paragraph
				StaticText That code sample requires an API Key (
				code
					StaticText ssoready_sk_...
				StaticText ) and an
				code
					StaticText organizationExternalId
				StaticText . How you get those is covered in
				link Setting up SSOReady, url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				StaticText later on this page.
			image
			heading
			paragraph
				StaticText For recommendations on how to incorporate a “Log in with SAML” button into your login user experience, check out our docs on
				link Integrating SAML with your Login UI, url='https://ssoready.com/docs/saml/integrating-saml-into-your-login-ui'
				StaticText .
			heading Handling SAML logins
			paragraph
				image, url='https://app.buildwithfern.com/_next/image?url=https%3A%2F%2Ffiles.buildwithfern.com%2Fssoready.docs.buildwithfern.com%2Fdocs%2F2025-01-02T23%3A05%3A17.602Z%2Fpages%2Fquickstart-handle.png&w=3840&q=75&dpl=dpl_E3br8NqLCTPPhihEjcHncTi4MC6y'
				button Expand image
			paragraph
				StaticText Under the hood, SAML login details are sent to you in the form of your user’s web browser POST-ing you an XML message. You would then need to
				link authenticate that message, url='https://www.w3.org/TR/xmldsig-core1/'
					image
				StaticText before logging your user in.
			paragraph
				StaticText SSOReady abstracts this away; we handle authenticating the message, and instead forward your user to a callback page on your webapp with a “SAML access code”, which you can redeem in exchange for authenticated details about the user.
			paragraph
				StaticText So what you’ll need to do is create a new “SSOReady callback page” (typically something like
				code
					StaticText https://app.yourcompany.com/ssoready-callback
				StaticText ), where you’ll expect a
				code
					StaticText ?saml_access_code=saml_access_code_...
				StaticText query parameter in the URL. From your backend, you’ll exchange that access code for a user’s details:
			StaticText POST
			button /v1/saml/redeem
			button cURL, expanded=False, hasPopup='menu'
				image
			link, url='https://ssoready.com/docs/api-reference/saml/redeem-saml-access-code'
				image
			button
				image
			code
				table
					rowgroup
						row
							cell $
							cell curl -X POST https://api.ssoready.com/v1/saml/redeem \
						row
							cell >
							cell -H "Authorization: Bearer <apiKey>" \
						row
							cell >
							cell -H "Content-Type: application/json" \
						row
							cell >
							cell -d '{
						row
							cell >
							cell "samlAccessCode": "saml_access_code_..."
						row
							cell >
							cell }'
			StaticText Response
			button
				image
			code
				table
					rowgroup
						row
							cell 1
							cell {
						row
							cell 2
							cell "email": "john.doe@acme.com",
						row
							cell 3
							cell "organizationId": "org_7cu5hsy9vrbi5d2k1qvbh19lj",
						row
							cell 4
							cell "organizationExternalId": "my_custom_external_id"
						row
							cell 5
							cell }
			paragraph
				StaticText The response will include the user’s
				code
					StaticText email
				StaticText as well as the SSOReady
				code
					StaticText organizationId
				StaticText and
				code
					StaticText organizationExternalId
				StaticText they belong to. It’s your responsibility to then log the user in with that given email and organization using whatever mechanism your tech stack uses.
			paragraph
				StaticText How you tell us about your desired “SSOReady callback page”, as well as what
				code
					StaticText organizationId
				StaticText and
				code
					StaticText organizationExternalId
				StaticText mean, is covered in
				link Setting up SSOReady, url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				StaticText below.
			image
			heading
			paragraph
				StaticText For recommendations on how your SAML handling logic should work, check out our docs on
				link Handling SAML Logins and Just-in-Time Provisioning, url='https://ssoready.com/docs/saml/handling-saml-logins-jit-provisioning'
				StaticText .
			heading Setting up SSOReady
			paragraph
				StaticText In
				link Code implementation, url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
				StaticText , there were three missing pieces that you’d need to implement SSOReady:
			list
				listitem
					ListMarker 0.
					strong
						StaticText Where does the SSOReady callback page get configured?
					StaticText That information lives on
					link environments, url='https://ssoready.com/docs/saml/saml-quickstart#creating-environments'
					StaticText .
				listitem
					ListMarker 0.
					strong
						StaticText Where do I get an API key?
					StaticText You create
					link an API key, url='https://ssoready.com/docs/saml/saml-quickstart#creating-api-keys'
					StaticText scoped to an environment.
				listitem
					ListMarker 0.
					strong
						StaticText How do I get
						code
							StaticText organizationExternalId
						StaticText ?
					StaticText You create
					link an organization, url='https://ssoready.com/docs/saml/saml-quickstart#creating-organizations'
					StaticText in an environment, where you can choose an external ID convenient for you.
			paragraph
				StaticText This section will step you through how you’ll do all of this setup in SSOReady’s webapp. As a prerequisite step, you’ll need to
				link sign up for SSOReady, url='https://app.ssoready.com/login'
					image
				StaticText . It’s free and anyone can sign up, even with a personal email.
			heading Creating environments
			paragraph
				StaticText To create an environment, go
				link here, url='https://app.ssoready.com/environments/new'
					image
				StaticText . You’ll typically create one environment per deployment environment, e.g. one each for “production”, “staging”, and “local dev”. On an environment, you’ll assign a “Redirect URL”. That’s the URL your users get redirected to in
				link “Handling SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
				StaticText .
			heading Creating API keys
			paragraph
				StaticText API keys are scoped to an environment. When viewing an environment in the app, click “API Keys” on the left navbar. Then click “Create API Key”. A popup will show you your new API key’s secret (it starts with
				code
					StaticText ssoready_sk_...
				StaticText ). That’s the API key you’ll use in
				link “Initiating SAML Logins”, url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				StaticText and
				link “Handling SAML Logins”, url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
				StaticText .
			heading Creating organizations
			paragraph
				StaticText An organization corresponds to a corporate customer of yours. If you sold your product to Apple, Nvidia, and Amazon, you’d have three organizations in SSOReady: one each for Apple, Nvidia, and Amazon.
			paragraph
				StaticText Organizations belong to an environment. When viewing an environment in the app, the “Create organization” button creates a new organization. Organizations have two properties worth highlighting:
			list
				listitem
					ListMarker •
					StaticText An optional
					emphasis
						StaticText external ID
					StaticText , which you can assign. If you’re selling multi-tenant B2B software, you probably already have a concept that closely matches an SSOReady organization — usually, this is something named a “team”, “workspace”, “company”, or something similar. When creating an SSOReady organization, use your product’s counterpart to an organization ID as the external ID.
			paragraph
				StaticText You’ll provide the external ID as the
				code
					StaticText organizationExternalId
				StaticText in
				link “Initiating SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				StaticText . The external ID is returned to you when
				link “Redeeming SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#redeeming-saml-logins'
				StaticText .
			list
				listitem
					ListMarker •
					StaticText A set of
					emphasis
						StaticText domains
					StaticText . If you expect Apple’s employees will log in to your product from
					code
						StaticText @apple.com
					StaticText and
					code
						StaticText @shazam.com
					StaticText email addresses, then put
					code
						StaticText apple.com
					StaticText and
					code
						StaticText shazam.com
					StaticText here. SSOReady will enforce that users’ SAML logins come from these domains.
			heading Creating SAML connections
			paragraph
				StaticText A SAML connection holds onto SAML-related settings. In
				link “Onboarding customers”, url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
				StaticText , you’ll be providing and asking for settings. Those settings all live on an SSOReady SAML connection.
			paragraph
				StaticText SAML connections belong to an organization. When viewing an organization in the app, the “Create SAML connection” button creates a new SAML connection. Beyond the SAML-related settings covered in
				link “Onboarding customers”, url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
				StaticText , SAML connections have one setting of note: whether they are
				emphasis
					StaticText primary
				StaticText .
			paragraph
				StaticText Each organization has up to one primary SAML connection. In
				link “Initiating SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				StaticText , you provide an
				code
					StaticText organizationExternalId
				StaticText . SSOReady will use that organization’s primary SAML connection to initiate the login.
			heading Onboarding customers
			paragraph
				StaticText In
				link Basic concepts, url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
				StaticText , we mentioned that you and your customer need to exchange details about each other before you can do SAML logins. This process happens offline — there’s no coding involved.
			paragraph
				StaticText You have to go through this process each time a new company wants to set up SAML. It’s inherent to how SAML was designed.
			paragraph
				StaticText With SSOReady, you have two options for onboarding customers onto SAML — that is, exchanging SAML-related settings with them. You can:
			list
				listitem
					ListMarker 0.
					StaticText Use SSOReady’s
					link self-serve setup links, url='https://ssoready.com/docs/idp-configuration/enabling-self-service-configuration-for-your-customers'
					StaticText . You give your customers a link, where they can set up SAML on their own. It’s a slick experience for your customers, and they’ll get set up in minutes.
					strong
						StaticText We recommend this approach.
				listitem
					ListMarker 0.
					StaticText Give your customers instructions yourself, over email/slack/Zoom/etc.
			paragraph
				StaticText If you go with option (2), be advised that SAML identity providers (e.g. Okta, Microsoft Entra, Google Workspace, etc.) don’t use the same terminology for these identical details. To deal with that, we’ve prepared a separate set of documentation for you to follow depending on what identity provider your customer uses:
			list
				listitem
					ListMarker •
					link Okta, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/okta/saml-with-okta'
				listitem
					ListMarker •
					link Google Workspace, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/google/saml-with-google'
				listitem
					ListMarker •
					link Microsoft Entra, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/entra-formerly-azure-ad/saml-with-entra'
					StaticText (aka Microsoft Azure Active Directory, Microsoft Azure AD)
				listitem
					ListMarker •
					link JumpCloud, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/jumpcloud/saml-with-jumpcloud'
				listitem
					ListMarker •
					link Ping Identity, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/ping-identity/saml-with-ping-identity'
			paragraph
				StaticText In all cases, you’re ultimately going to:
			list
				listitem
					ListMarker 0.
					StaticText Give your customers an “SP Entity ID” and “SP ACS URL”. SSOReady’s webapp gives you both.
				listitem
					ListMarker 0.
					StaticText Ask your customers for an “IDP Entity ID”, “IDP Redirect URL”, and “IDP Certificate” which you input into SSOReady.
			paragraph
				StaticText Once you have all those details, you’ll be ready to accept SAML logins!
			StaticText Was this page helpful?
			button Yes, expanded=False, hasPopup='dialog'
				image
			button No, expanded=False, hasPopup='dialog'
				image
			link SAML: A technical primer Up Next, url='https://ssoready.com/docs/saml/saml-technical-primer'
				image
			link Built with, url='https://buildwithfern.com/?utm_campaign=buildWith&utm_medium=docs&utm_source=ssoready.com'
				image
	contentinfo
	alert, atomic
		StaticText Getting started with SSOReady SAML — SSOReady Docs
```
</details>



```
RootWebArea Getting started with SSOReady SAML — SSOReady Docs, focused, url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
	banner
		navigation primary
			[84] link SSOReady Docs, center=(349,1360), url='https://ssoready.com/'
				image SSOReady Docs, url='https://app.buildwithfern.com/_next/image?url=https%3A%2F%2Ffiles.buildwithfern.com%2Fssoready.docs.buildwithfern.com%2Fdocs%2F2025-01-02T23%3A05%3A17.602Z%2Fdocs%2Fassets%2Flogo.png&w=128&q=100&dpl=dpl_E3br8NqLCTPPhihEjcHncTi4MC6y'
```
<details><summary>Show more</summary>

```
			[89] button Search... /, center=(960,1360), inner_text=Search...
/
				image
			[97] link Login, center=(1594,1360), url='https://app.ssoready.com/'
				image
	navigation secondary
		list
			listitem
				list
					listitem
						[120] link Introduction, center=(402,1434), url='https://ssoready.com/docs/introduction'
			listitem
				StaticText SAML (Enterprise SSO)
				list
					listitem
						[129] link SAML Quickstart, center=(402,1534), url='https://ssoready.com/docs/saml/saml-quickstart'
					listitem
						[134] link SAML: A technical primer, center=(402,1570), url='https://ssoready.com/docs/saml/saml-technical-primer'
					listitem
						[139] link Integrating SAML with your Login UI, center=(402,1606), url='https://ssoready.com/docs/saml/integrating-saml-into-your-login-ui'
					listitem
						[144] link Handling SAML Logins + JIT Provisioning, center=(402,1652), url='https://ssoready.com/docs/saml/handling-saml-logins-jit-provisioning'
			listitem
				StaticText SCIM (Enterprise Directory Sync)
				list
					listitem
						[153] link SCIM Quickstart, center=(402,1762), url='https://ssoready.com/docs/scim/scim-quickstart'
			listitem
				StaticText SDKs
				list
					listitem
						[162] link TypeScript SDK, center=(402,1862), url='https://github.com/ssoready/ssoready-typescript'
							image
					listitem
						[170] link Python SDK, center=(402,1898), url='https://github.com/ssoready/ssoready-python'
							image
					listitem
						[178] link Go SDK, center=(402,1934), url='https://github.com/ssoready/ssoready-go'
							image
					listitem
						[186] link Java SDK, center=(402,1970), url='https://github.com/ssoready/ssoready-java'
							image
					listitem
						[194] link C# SDK, center=(402,2006), url='https://github.com/ssoready/ssoready-csharp'
							image
					listitem
						[202] link Ruby SDK, center=(402,2042), url='https://github.com/ssoready/ssoready-ruby'
							image
					listitem
						[210] link PHP SDK, center=(402,2078), url='https://github.com/ssoready/ssoready-php'
							image
			listitem
				StaticText SAML-over-OAuth
				list
					listitem
						[222] link SAML over OAuth (SAML NextAuth.js integration), center=(402,2188), url='https://ssoready.com/docs/saml-over-oauth-saml-nextauth-integration'
					listitem
						[227] link SAML for Firebase, center=(402,2234), url='https://ssoready.com/docs/firebase'
			listitem
				StaticText IDP configuration
				list
					listitem
						[236] link Enabling self-service configuration for your customers, center=(402,2344), url='https://ssoready.com/docs/idp-configuration/enabling-self-service-configuration-for-your-customers'
					listitem
						[242] button Guides for common identity providers, center=(402,2400)
							image
			listitem
				StaticText SSOReady concepts
				list
					listitem
						link Overview, url='https://ssoready.com/docs/ssoready-concepts/overview'
					listitem
						link Environments, url='https://ssoready.com/docs/ssoready-concepts/environments'
					listitem
						link Organizations, url='https://ssoready.com/docs/ssoready-concepts/organizations'
					listitem
						link SAML Connections, url='https://ssoready.com/docs/ssoready-concepts/saml-connections'
					listitem
						link SAML Login Flows, url='https://ssoready.com/docs/ssoready-concepts/saml-login-flows'
					listitem
						link SCIM Directories, url='https://ssoready.com/docs/ssoready-concepts/scim-directories'
					listitem
						link SCIM Users, url='https://ssoready.com/docs/ssoready-concepts/scim-users'
					listitem
						link SCIM Groups, url='https://ssoready.com/docs/ssoready-concepts/scim-groups'
					listitem
						link SCIM Request Logs, url='https://ssoready.com/docs/ssoready-concepts/scim-request-logs'
			listitem
				StaticText Management API
				list
					listitem
						link Management API, url='https://ssoready.com/docs/management-api'
			listitem
				StaticText DummyIDP
				list
					listitem
						link Testing SAML/SCIM with DummyIDP, url='https://ssoready.com/docs/dummyidp'
			listitem
				StaticText Self-Hosting
				list
					listitem
						link Self-Hosting SSOReady, url='https://ssoready.com/docs/self-hosting-ssoready'
			listitem
				StaticText API Reference
				list
					listitem
						button SAML
							image
					listitem
						button SCIM
							image
					listitem
						button Management API
							image
	main
		complementary
			StaticText On this page
			list
				listitem
					[368] link Getting started with SSOReady SAML, center=(1519,1476), url='https://ssoready.com/docs/saml/saml-quickstart#getting-started-with-ssoready-saml'
				listitem
					[370] link Basic concepts, center=(1519,1514), url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
				listitem
					[372] link Code implementation, center=(1519,1542), focused, url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
				listitem
					[374] link Initiating SAML logins, center=(1519,1570), url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				listitem
					[376] link Handling SAML logins, center=(1519,1598), url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
				listitem
					[378] link Setting up SSOReady, center=(1519,1626), url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				listitem
					[380] link Creating environments, center=(1519,1654), url='https://ssoready.com/docs/saml/saml-quickstart#creating-environments'
				listitem
					[382] link Creating API keys, center=(1519,1682), url='https://ssoready.com/docs/saml/saml-quickstart#creating-api-keys'
				listitem
					[384] link Creating organizations, center=(1519,1710), url='https://ssoready.com/docs/saml/saml-quickstart#creating-organizations'
				listitem
					[386] link Creating SAML connections, center=(1519,1738), url='https://ssoready.com/docs/saml/saml-quickstart#creating-saml-connections'
				listitem
					[388] link Onboarding customers, center=(1519,1766), url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
		article
			link SAML (Enterprise SSO), url='https://ssoready.com/docs/saml/saml-quickstart'
			heading SAML Quickstart
				paragraph
			paragraph
				StaticText Start accepting SAML logins this afternoon
			heading Getting started with SSOReady SAML
			paragraph
				StaticText Welcome to the SSOReady quickstart guide! This guide will take you through:
			list
				listitem
					ListMarker 0.
					link Basic concepts., url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
						strong
					StaticText How Enterprise SSO / SAML works at a high level, and how SSOReady will help you implement it.
				listitem
					ListMarker 0.
					link Code implementation., url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
						strong
					StaticText What you’ll need to build, and how to use SSOReady’s SDK.
				listitem
					ListMarker 0.
					link Onboarding customers., url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
						strong
					StaticText SAML requires both you and your customer to do setup. SSOReady automates your end of the equation, and this section describes what instructions you’ll give to your customers.
			paragraph
				StaticText SSOReady is just an authentication middleware layer. SSOReady doesn’t “own” your users, and it doesn’t require you to use any particular tech stack. That’s on purpose — it makes onboarding easier for you, and it forces us to keep earning your business in the long run, because churning is easier.
			heading Basic concepts
			paragraph
				StaticText ”Enterprise SSO” is mostly a synonym for a protocol called
				link SAML, url='https://en.wikipedia.org/wiki/Security_Assertion_Markup_Language'
					image
				StaticText . It’s a way for a company to easily let their employees log into all their software products, including your product.
			paragraph
				StaticText At smaller companies, employees use username+password or “Log in with Google” to sign into your product. At larger companies, employees instead expect to use services like Okta or Microsoft Entra (formerly “Azure AD”) to do sign-in. Those sign-ins happen using the SAML protocol. SSOReady makes it way easier to implement SAML.
			paragraph
				StaticText SAML logins have two steps:
			list
				listitem
					ListMarker 0.
					StaticText You
					link initiate a SAML login, url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
						strong
					StaticText by redirecting your user to their corporate Okta/Google/Microsoft.
				listitem
					ListMarker 0.
					StaticText Their corporate Okta/Google/Microsoft redirects your user back to your app, and you
					link handle the SAML login, url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
						strong
					StaticText .
			paragraph
				StaticText Before this can happen, you and your customer need to exchange settings about each other. This process is done offline; you’ll give your customer some settings that SSOReady provides for you, and you’ll email your customer asking for some settings in return which you’ll input into SSOReady.
			paragraph
				StaticText We’ll cover how to do (1) and (2) in
				link Code implementation, url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
				StaticText . We’ll cover the setup work you’ll need to do inside SSOReady’s webapp in
				link Setting up SSOReady, url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				StaticText . We’ll cover the settings you’ll give and ask for in
				link Onboarding customers, url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
				StaticText .
			[431] heading Code implementation, center=(960,1429)
			paragraph
				StaticText As covered in
				[433] link Basic concepts, center=(768,1494), url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
				StaticText , there are two steps involved in implementing SAML: initiating SAML logins, and handling SAML logins. Here’s how you do each.
			[434] heading Initiating SAML logins, center=(960,1601)
			paragraph
				image, url='https://app.buildwithfern.com/_next/image?url=https%3A%2F%2Ffiles.buildwithfern.com%2Fssoready.docs.buildwithfern.com%2Fdocs%2F2025-01-02T23%3A05%3A17.602Z%2Fpages%2Fquickstart-initiate.png&w=3840&q=75&dpl=dpl_E3br8NqLCTPPhihEjcHncTi4MC6y'
				button Expand image
			paragraph
				StaticText Under the hood, initiating SAML logins requires you to get your user’s browser to perform an HTTP POST against their corporate Okta/Google/Microsoft with a specific XML message. SSOReady abstracts all this work away into you just needing to redirect your user to a URL.
			paragraph
				StaticText SSOReady’s SDKs generate a URL for you, and then you simply forward your user to that URL using any mechanism that suits your tech stack.
			StaticText POST
			[454] button /v1/saml/redirect, center=(731,2271)
			[464] button cURL, center=(1199,2271), expanded=False, hasPopup='menu', type=button
				image
			[469] link, center=(1259,2271), url='https://ssoready.com/docs/api-reference/saml/get-saml-redirect-url'
				image
			[472] button, center=(1291,2271)
				image
			code
				table
					rowgroup
						row
							[488] cell $, center=(618,2308)
							[490] cell curl -X POST https://api.ssoready.com/v1/saml/redirect \, center=(970,2308)
						row
							[498] cell >, center=(618,2328)
							[500] cell -H "Authorization: Bearer <apiKey>" \, center=(970,2328), inner_text=     -H "Authorization: Bearer <apiKey>" \
						row
							[508] cell >, center=(618,2347)
							[510] cell -H "Content-Type: application/json" \, center=(970,2347), inner_text=     -H "Content-Type: application/json" \
						row
							[518] cell >, center=(618,2367)
							[520] cell -d '{, center=(970,2367), inner_text=     -d '{
						row
							[526] cell >, center=(618,2386)
							[528] cell "organizationExternalId": "my_custom_external_id", center=(970,2386), inner_text=  "organizationExternalId": "my_custom_external_id"
						row
							[532] cell >, center=(618,2406)
							[534] cell }', center=(970,2406)
			StaticText Response
			button
				image
			code
				table
					rowgroup
						row
							cell 1
							cell {
						row
							cell 2
							cell "redirectUrl": "https://your.redirect.url"
						row
							cell 3
							cell }
			paragraph
				StaticText That code sample requires an API Key (
				code
					StaticText ssoready_sk_...
				StaticText ) and an
				code
					StaticText organizationExternalId
				StaticText . How you get those is covered in
				link Setting up SSOReady, url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				StaticText later on this page.
			image
			heading
			paragraph
				StaticText For recommendations on how to incorporate a “Log in with SAML” button into your login user experience, check out our docs on
				link Integrating SAML with your Login UI, url='https://ssoready.com/docs/saml/integrating-saml-into-your-login-ui'
				StaticText .
			heading Handling SAML logins
			paragraph
				image, url='https://app.buildwithfern.com/_next/image?url=https%3A%2F%2Ffiles.buildwithfern.com%2Fssoready.docs.buildwithfern.com%2Fdocs%2F2025-01-02T23%3A05%3A17.602Z%2Fpages%2Fquickstart-handle.png&w=3840&q=75&dpl=dpl_E3br8NqLCTPPhihEjcHncTi4MC6y'
				button Expand image
			paragraph
				StaticText Under the hood, SAML login details are sent to you in the form of your user’s web browser POST-ing you an XML message. You would then need to
				link authenticate that message, url='https://www.w3.org/TR/xmldsig-core1/'
					image
				StaticText before logging your user in.
			paragraph
				StaticText SSOReady abstracts this away; we handle authenticating the message, and instead forward your user to a callback page on your webapp with a “SAML access code”, which you can redeem in exchange for authenticated details about the user.
			paragraph
				StaticText So what you’ll need to do is create a new “SSOReady callback page” (typically something like
				code
					StaticText https://app.yourcompany.com/ssoready-callback
				StaticText ), where you’ll expect a
				code
					StaticText ?saml_access_code=saml_access_code_...
				StaticText query parameter in the URL. From your backend, you’ll exchange that access code for a user’s details:
			StaticText POST
			button /v1/saml/redeem
			button cURL, expanded=False, hasPopup='menu'
				image
			link, url='https://ssoready.com/docs/api-reference/saml/redeem-saml-access-code'
				image
			button
				image
			code
				table
					rowgroup
						row
							cell $
							cell curl -X POST https://api.ssoready.com/v1/saml/redeem \
						row
							cell >
							cell -H "Authorization: Bearer <apiKey>" \
						row
							cell >
							cell -H "Content-Type: application/json" \
						row
							cell >
							cell -d '{
						row
							cell >
							cell "samlAccessCode": "saml_access_code_..."
						row
							cell >
							cell }'
			StaticText Response
			button
				image
			code
				table
					rowgroup
						row
							cell 1
							cell {
						row
							cell 2
							cell "email": "john.doe@acme.com",
						row
							cell 3
							cell "organizationId": "org_7cu5hsy9vrbi5d2k1qvbh19lj",
						row
							cell 4
							cell "organizationExternalId": "my_custom_external_id"
						row
							cell 5
							cell }
			paragraph
				StaticText The response will include the user’s
				code
					StaticText email
				StaticText as well as the SSOReady
				code
					StaticText organizationId
				StaticText and
				code
					StaticText organizationExternalId
				StaticText they belong to. It’s your responsibility to then log the user in with that given email and organization using whatever mechanism your tech stack uses.
			paragraph
				StaticText How you tell us about your desired “SSOReady callback page”, as well as what
				code
					StaticText organizationId
				StaticText and
				code
					StaticText organizationExternalId
				StaticText mean, is covered in
				link Setting up SSOReady, url='https://ssoready.com/docs/saml/saml-quickstart#setting-up-ssoready'
				StaticText below.
			image
			heading
			paragraph
				StaticText For recommendations on how your SAML handling logic should work, check out our docs on
				link Handling SAML Logins and Just-in-Time Provisioning, url='https://ssoready.com/docs/saml/handling-saml-logins-jit-provisioning'
				StaticText .
			heading Setting up SSOReady
			paragraph
				StaticText In
				link Code implementation, url='https://ssoready.com/docs/saml/saml-quickstart#code-implementation'
				StaticText , there were three missing pieces that you’d need to implement SSOReady:
			list
				listitem
					ListMarker 0.
					strong
						StaticText Where does the SSOReady callback page get configured?
					StaticText That information lives on
					link environments, url='https://ssoready.com/docs/saml/saml-quickstart#creating-environments'
					StaticText .
				listitem
					ListMarker 0.
					strong
						StaticText Where do I get an API key?
					StaticText You create
					link an API key, url='https://ssoready.com/docs/saml/saml-quickstart#creating-api-keys'
					StaticText scoped to an environment.
				listitem
					ListMarker 0.
					strong
						StaticText How do I get
						code
							StaticText organizationExternalId
						StaticText ?
					StaticText You create
					link an organization, url='https://ssoready.com/docs/saml/saml-quickstart#creating-organizations'
					StaticText in an environment, where you can choose an external ID convenient for you.
			paragraph
				StaticText This section will step you through how you’ll do all of this setup in SSOReady’s webapp. As a prerequisite step, you’ll need to
				link sign up for SSOReady, url='https://app.ssoready.com/login'
					image
				StaticText . It’s free and anyone can sign up, even with a personal email.
			heading Creating environments
			paragraph
				StaticText To create an environment, go
				link here, url='https://app.ssoready.com/environments/new'
					image
				StaticText . You’ll typically create one environment per deployment environment, e.g. one each for “production”, “staging”, and “local dev”. On an environment, you’ll assign a “Redirect URL”. That’s the URL your users get redirected to in
				link “Handling SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
				StaticText .
			heading Creating API keys
			paragraph
				StaticText API keys are scoped to an environment. When viewing an environment in the app, click “API Keys” on the left navbar. Then click “Create API Key”. A popup will show you your new API key’s secret (it starts with
				code
					StaticText ssoready_sk_...
				StaticText ). That’s the API key you’ll use in
				link “Initiating SAML Logins”, url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				StaticText and
				link “Handling SAML Logins”, url='https://ssoready.com/docs/saml/saml-quickstart#handling-saml-logins'
				StaticText .
			heading Creating organizations
			paragraph
				StaticText An organization corresponds to a corporate customer of yours. If you sold your product to Apple, Nvidia, and Amazon, you’d have three organizations in SSOReady: one each for Apple, Nvidia, and Amazon.
			paragraph
				StaticText Organizations belong to an environment. When viewing an environment in the app, the “Create organization” button creates a new organization. Organizations have two properties worth highlighting:
			list
				listitem
					ListMarker •
					StaticText An optional
					emphasis
						StaticText external ID
					StaticText , which you can assign. If you’re selling multi-tenant B2B software, you probably already have a concept that closely matches an SSOReady organization — usually, this is something named a “team”, “workspace”, “company”, or something similar. When creating an SSOReady organization, use your product’s counterpart to an organization ID as the external ID.
			paragraph
				StaticText You’ll provide the external ID as the
				code
					StaticText organizationExternalId
				StaticText in
				link “Initiating SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				StaticText . The external ID is returned to you when
				link “Redeeming SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#redeeming-saml-logins'
				StaticText .
			list
				listitem
					ListMarker •
					StaticText A set of
					emphasis
						StaticText domains
					StaticText . If you expect Apple’s employees will log in to your product from
					code
						StaticText @apple.com
					StaticText and
					code
						StaticText @shazam.com
					StaticText email addresses, then put
					code
						StaticText apple.com
					StaticText and
					code
						StaticText shazam.com
					StaticText here. SSOReady will enforce that users’ SAML logins come from these domains.
			heading Creating SAML connections
			paragraph
				StaticText A SAML connection holds onto SAML-related settings. In
				link “Onboarding customers”, url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
				StaticText , you’ll be providing and asking for settings. Those settings all live on an SSOReady SAML connection.
			paragraph
				StaticText SAML connections belong to an organization. When viewing an organization in the app, the “Create SAML connection” button creates a new SAML connection. Beyond the SAML-related settings covered in
				link “Onboarding customers”, url='https://ssoready.com/docs/saml/saml-quickstart#onboarding-customers'
				StaticText , SAML connections have one setting of note: whether they are
				emphasis
					StaticText primary
				StaticText .
			paragraph
				StaticText Each organization has up to one primary SAML connection. In
				link “Initiating SAML logins”, url='https://ssoready.com/docs/saml/saml-quickstart#initiating-saml-logins'
				StaticText , you provide an
				code
					StaticText organizationExternalId
				StaticText . SSOReady will use that organization’s primary SAML connection to initiate the login.
			heading Onboarding customers
			paragraph
				StaticText In
				link Basic concepts, url='https://ssoready.com/docs/saml/saml-quickstart#basic-concepts'
				StaticText , we mentioned that you and your customer need to exchange details about each other before you can do SAML logins. This process happens offline — there’s no coding involved.
			paragraph
				StaticText You have to go through this process each time a new company wants to set up SAML. It’s inherent to how SAML was designed.
			paragraph
				StaticText With SSOReady, you have two options for onboarding customers onto SAML — that is, exchanging SAML-related settings with them. You can:
			list
				listitem
					ListMarker 0.
					StaticText Use SSOReady’s
					link self-serve setup links, url='https://ssoready.com/docs/idp-configuration/enabling-self-service-configuration-for-your-customers'
					StaticText . You give your customers a link, where they can set up SAML on their own. It’s a slick experience for your customers, and they’ll get set up in minutes.
					strong
						StaticText We recommend this approach.
				listitem
					ListMarker 0.
					StaticText Give your customers instructions yourself, over email/slack/Zoom/etc.
			paragraph
				StaticText If you go with option (2), be advised that SAML identity providers (e.g. Okta, Microsoft Entra, Google Workspace, etc.) don’t use the same terminology for these identical details. To deal with that, we’ve prepared a separate set of documentation for you to follow depending on what identity provider your customer uses:
			list
				listitem
					ListMarker •
					link Okta, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/okta/saml-with-okta'
				listitem
					ListMarker •
					link Google Workspace, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/google/saml-with-google'
				listitem
					ListMarker •
					link Microsoft Entra, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/entra-formerly-azure-ad/saml-with-entra'
					StaticText (aka Microsoft Azure Active Directory, Microsoft Azure AD)
				listitem
					ListMarker •
					link JumpCloud, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/jumpcloud/saml-with-jumpcloud'
				listitem
					ListMarker •
					link Ping Identity, url='https://ssoready.com/docs/idp-configuration/guides-for-common-identity-providers/ping-identity/saml-with-ping-identity'
			paragraph
				StaticText In all cases, you’re ultimately going to:
			list
				listitem
					ListMarker 0.
					StaticText Give your customers an “SP Entity ID” and “SP ACS URL”. SSOReady’s webapp gives you both.
				listitem
					ListMarker 0.
					StaticText Ask your customers for an “IDP Entity ID”, “IDP Redirect URL”, and “IDP Certificate” which you input into SSOReady.
			paragraph
				StaticText Once you have all those details, you’ll be ready to accept SAML logins!
			StaticText Was this page helpful?
			button Yes, expanded=False, hasPopup='dialog'
				image
			button No, expanded=False, hasPopup='dialog'
				image
			link SAML: A technical primer Up Next, url='https://ssoready.com/docs/saml/saml-technical-primer'
				image
			link Built with, url='https://buildwithfern.com/?utm_campaign=buildWith&utm_medium=docs&utm_source=ssoready.com'
				image
	contentinfo
	alert, atomic
		StaticText Getting started with SSOReady SAML — SSOReady Docs
```
</details>

**Reasoning for action:** This action is crucial as it directly addresses the user's requirement to learn how to implement SAML SSO in their application. By clicking on the 'Code implementation' link, I am navigating from the current information on basic concepts to the practical section that outlines the necessary steps for implementation, thus fulfilling part of the user story.

**Action:** click(372) # Click on the Code implementation link to explore how to implement SAML logins.

**Change Description:** After clicking the 'Code implementation' link, the browser navigated to the section detailing the steps involved in implementing SAML logins, moving the focus to the 'Code implementation' heading and updating the page URL to 'https://ssoready.com/docs/saml/saml-quickstart#code-implementation', while the overall content dynamically updated to reflect this specific implementation guidance.

**Screenshot before:****Screenshot after:**---


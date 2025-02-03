# Task

**Explore Polytomic's Offerings and Integrations**

As a potential customer researching data synchronization solutions,,
I explore the products, use cases, and integrations provided by Polytomic,,
so that I can understand how Polytomic can meet my organization's data needs effectively.

**Success definition:** Given I am on the Polytomic homepage
When I click on the Products button, followed by the Use Cases button, and finally the Integrations link
Then I should see content that presents various products offered by Polytomic, cases of how different teams utilize these products, and details on available integrations for syncing data with various platforms.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.polytomic.com/

https://www.polytomic.com/

**Content (before/after):** 

```
RootWebArea Polytomic, focused, url='https://www.polytomic.com/'
	banner
		[54] link, center=(559,40), url='https://www.polytomic.com/'
			image
		[60] button Products, center=(796,40), expanded=False, hasPopup='menu'
```
<details><summary>Show more</summary>

```
		[81] button Use Cases, center=(891,40), expanded=False, hasPopup='menu'
		[93] link Integrations, center=(997,40), url='https://www.polytomic.com/integrations'
		[96] link Customers, center=(1105,40), url='https://www.polytomic.com/customers'
		[100] button Resources, center=(1208,40), expanded=False, hasPopup='menu'
		[111] link Book demo, center=(1318,40), url='https://www.polytomic.com/book-demo'
		[112] link Log in, center=(1410,40), url='https://app.polytomic.com/'
	main
		heading Sync
		link, url='https://www.polytomic.com/integrations'
			image
		link, url='https://www.polytomic.com/integrations'
			image
		link, url='https://www.polytomic.com/integrations'
			image
		heading to
		link, url='https://www.polytomic.com/integrations'
			image
		link, url='https://www.polytomic.com/integrations'
			image
		link, url='https://www.polytomic.com/integrations'
			image
		heading Bidirectional ETL and data syncing
		[139] link Book demo, center=(867,368), url='https://www.polytomic.com/book-demo'
		StaticText or
		[142] link Start free trial, center=(1042,368), url='https://www.polytomic.com/start-free-trial'
		StaticText TRUSTED BY DATA AND OPS TEAMS
		image Brex, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae40b03e4a1bbb06f5_Brex-min.svg'
		image CloudTrucks, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037baf4c42b37e0fbac0a1_CloudTrucks-min.svg'
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f07d38b41f1d81718a9b8d_Retool.svg'
		image Vanta, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037baedd1159a0c1fc4709_Vanta-min.svg'
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66ebd7e824eaabe44e6322d1_Heygen.svg'
		image ID.me logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65ee85a9e4f132cab4914829_IDMe.svg'
		image Mercury, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae5786cce867364e28_Mercury-min.svg'
		image Vercel, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae8b1f86f497c26236_Vercel-min.svg'
		image Artsy, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bafb40e5c8a04b09b86_Artsy-min.svg'
		image Sourcegraph, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae3ad1dfdbb8f8f8b9_Sourcegraph-min.svg'
		image Telnyx, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae7434b46058dda760_Telnyx-min.svg'
		StaticText UNIFIED PLATFORM
		heading One platform for all syncs
		StaticText ETL, ELT, CDC streaming, Reverse ETL, and general data syncs in one platform.
		StaticText Move data between data warehouses, databases, cloud applications, general storage, spreadsheets, and HTTP APIs.
		[184] Video, center=(1247,1020)
		StaticText ENTERPRISE
		heading Enterprise-ready
		StaticText Polytomic is enterprise-ready out of the box.
		StaticText Self-hosted deployment option, RBAC permissions, audit log, no-code and code, and more.
		image Self hosted ETL solution., url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/630409f536fae0d423bba7ba_server%20icon.svg'
		StaticText Self-hosted option available
		StaticText Deploy Polytomic to your private cloud
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f2fc969ed78b266aff2c00_B.svg'
		StaticText Security and compliance
		StaticText SOC 2, GDPR, CCPA, and HIPAA compliant
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f2fc96061678aaa9cc2fba_C.svg'
		StaticText Enterprise permissions engine
		StaticText True RBAC fine-grained user permissions
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f2fc9612bdedb34bbcd9a6_D.svg'
		StaticText Infrastructure as code option
		StaticText Run Polytomic with Terraform or code
		StaticText INTEGRATIONS
		heading Integrations ready
		StaticText Two-way integrations available out of the box. Your integration requests built in days.
		image Snowflake logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fe62bac06e1f31f7e7_Integration%3DSnowflake.svg'
		StaticText Snowflake
		image Salesforce logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fe1b50c333f7272900_Integration%3DSalesforce.svg'
		StaticText Salesforce
		image BigQuery logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fec16b96f8e1d0bd1d_Integration%3DGoogleBigQuery.svg'
		StaticText BigQuery
		image Marketo logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fe36357a160e4f649d_Integration%3DMarketo.svg'
		StaticText Marketo
		image Stripe logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/662686d9be3408abe47038d4_stripe.svg'
		StaticText Stripe
		image Databricks logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6626874fe97f46d98bf616c2_databricks.svg'
		StaticText Databricks
		image NetSuite logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6626874242082482a88a829f_netsuite.svg'
		StaticText NetSuite
		image Google sheets logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba861b31a6dc8008c534e_Google%20Spreadsheets.svg'
		StaticText Google Sheets
		image Hubspot logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fed262c23c0cec31ea_Integration%3DHubspot.svg'
		StaticText HubSpot
		image Airtable logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7feb31a6d8cfc8c5065_Integration%3DAirtable.svg'
		StaticText Google Ads
		image S3 logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66268790afb50884fa08dc09_s3.svg'
		StaticText Amazon S3
		image Facebook logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66268762d1288a961e8db8ff_fbaudience.svg'
		StaticText Facebook Ads
		image AWS Athena logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/662686fac78979824347339c_awsathena.svg'
		StaticText Amazon Athena
		image LinkedIn logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/662684d1c789798243454499_LinkedinAds.svg'
		StaticText LinkedIn Ads
		image Airtable logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7feb31a6d8cfc8c5065_Integration%3DAirtable.svg'
		StaticText Airtable
		StaticText And many more...
		StaticText SUPPORT
		heading Fanatical customer support
		StaticText Replies to your messages in under a minute.
		image G2 support badge, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66267b7b427daadf85d022cb_best-support.svg'
		link Book demo, url='https://www.polytomic.com/book-demo'
		StaticText or
		link Start free trial, url='https://www.polytomic.com/start-free-trial'
		heading All the features you need, on the platform that does it all
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80eec4382052d8485ea_stack.svg'
		heading Replace multiple vendors
		StaticText Reduce costs and simplify workflows
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b9ded6e3bc292ef3ce2b_rotate.svg'
		heading One platform for all syncs
		StaticText ETL, Reverse ETL, CDC, iPaaS, APIs, and spreadsheets
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80e0008d2a556545a50_grid.svg'
		heading Sync only what’s changed
		StaticText Save on API limits and compute costs
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80e28226ec8287c7ac7_click.svg'
		heading Point and click
		StaticText Select and filter your data without writing code
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80e4aa24876fdb2cde7_terminal.svg'
		heading SQL query support
		StaticText Powerful transformations when you need them
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80eee57629e308fb9bf_orbit.svg'
		heading Pull from any API
		StaticText No more glue code for custom integrations
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80ef4d67f032153a0ba_server.svg'
		heading Self-hosting available
		StaticText Turnkey deployment to your private cloud
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622ba2450c42b5d99a1a404_shield.svg'
		heading Enterprise-ready
		StaticText SOC 2, GDPR, permissions, and audit logs
		heading Get started
		StaticText See a live demo or try free for 14 days.
		link Book demo, url='https://www.polytomic.com/book-demo'
		StaticText or
		link Start free trial, url='https://www.polytomic.com/start-free-trial'
		image
		StaticText Best Support
		StaticText Spring 2023
		image
		StaticText Best Meets Requirements
		StaticText Spring 2023
		image
		StaticText High Performer
		StaticText Spring 2023
	contentinfo
		StaticText Product
		link Overview, url='https://www.polytomic.com/overview'
		link Pricing, url='https://www.polytomic.com/pricing'
		link Integrations, url='https://www.polytomic.com/integrations'
		StaticText Use cases
		link Data Teams, url='https://www.polytomic.com/data-teams'
		link RevOps, url='https://www.polytomic.com/rev-ops'
		link Marketing, url='https://www.polytomic.com/marketing-teams'
		link Support, url='https://www.polytomic.com/support-teams'
		link API Endpoints, url='https://www.polytomic.com/api-sources'
		StaticText Resources
		link Documentation, url='https://docs.polytomic.com/'
		link Blog, url='https://www.polytomic.com/blog'
		link Ebooks, url='https://www.polytomic.com/ebooks'
		link Case studies, url='https://www.polytomic.com/customers'
		link Security, url='https://www.polytomic.com/security'
		StaticText Get in touch
		link Contact us, url='https://www.polytomic.com/contact'
		link, url='https://www.linkedin.com/company/polytomic/'
			image
		link, url='https://twitter.com/polytomic'
			image
		StaticText Copyright © 2024 Polytomic Inc. All rights reserved.
		StaticText ·
		link Terms of Service, url='https://www.polytomic.com/terms'
		StaticText ·
		link Privacy Policy, url='https://www.polytomic.com/privacy-policy'
		link, url='https://www.polytomic.com/'
			image
	generic
		[g] dialog Intercom live chat, center=(1876,1036), modal=False, title=Intercom live chat
```
</details>



```
RootWebArea Polytomic, focused, url='https://www.polytomic.com/'
	banner
		[54] link, center=(559,40), url='https://www.polytomic.com/'
			image
		[60] button Products, center=(796,40), expanded=False, focused, hasPopup='menu'
```
<details><summary>Show more</summary>

```
		[81] button Use Cases, center=(891,40), expanded=False, hasPopup='menu'
		[93] link Integrations, center=(997,40), url='https://www.polytomic.com/integrations'
		[96] link Customers, center=(1105,40), url='https://www.polytomic.com/customers'
		[100] button Resources, center=(1208,40), expanded=False, hasPopup='menu'
		[111] link Book demo, center=(1318,40), url='https://www.polytomic.com/book-demo'
		[112] link Log in, center=(1410,40), url='https://app.polytomic.com/'
	main
		heading Sync
		link, url='https://www.polytomic.com/integrations'
			image
		[449] link, center=(959,239), url='https://www.polytomic.com/integrations'
			image
		[451] link, center=(959,203), url='https://www.polytomic.com/integrations'
			image
		heading to
		link, url='https://www.polytomic.com/integrations'
			image
		link, url='https://www.polytomic.com/integrations'
			image
		[457] link, center=(1148,203), url='https://www.polytomic.com/integrations'
			image
		heading Bidirectional ETL and data syncing
		[139] link Book demo, center=(867,368), url='https://www.polytomic.com/book-demo'
		StaticText or
		[142] link Start free trial, center=(1042,368), url='https://www.polytomic.com/start-free-trial'
		StaticText TRUSTED BY DATA AND OPS TEAMS
		image Brex, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae40b03e4a1bbb06f5_Brex-min.svg'
		image CloudTrucks, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037baf4c42b37e0fbac0a1_CloudTrucks-min.svg'
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f07d38b41f1d81718a9b8d_Retool.svg'
		image Vanta, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037baedd1159a0c1fc4709_Vanta-min.svg'
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66ebd7e824eaabe44e6322d1_Heygen.svg'
		image ID.me logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65ee85a9e4f132cab4914829_IDMe.svg'
		image Mercury, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae5786cce867364e28_Mercury-min.svg'
		image Vercel, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae8b1f86f497c26236_Vercel-min.svg'
		image Artsy, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bafb40e5c8a04b09b86_Artsy-min.svg'
		image Sourcegraph, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae3ad1dfdbb8f8f8b9_Sourcegraph-min.svg'
		image Telnyx, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae7434b46058dda760_Telnyx-min.svg'
		StaticText UNIFIED PLATFORM
		heading One platform for all syncs
		StaticText ETL, ELT, CDC streaming, Reverse ETL, and general data syncs in one platform.
		StaticText Move data between data warehouses, databases, cloud applications, general storage, spreadsheets, and HTTP APIs.
		[184] Video, center=(1247,1020)
		StaticText ENTERPRISE
		heading Enterprise-ready
		StaticText Polytomic is enterprise-ready out of the box.
		StaticText Self-hosted deployment option, RBAC permissions, audit log, no-code and code, and more.
		image Self hosted ETL solution., url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/630409f536fae0d423bba7ba_server%20icon.svg'
		StaticText Self-hosted option available
		StaticText Deploy Polytomic to your private cloud
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f2fc969ed78b266aff2c00_B.svg'
		StaticText Security and compliance
		StaticText SOC 2, GDPR, CCPA, and HIPAA compliant
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f2fc96061678aaa9cc2fba_C.svg'
		StaticText Enterprise permissions engine
		StaticText True RBAC fine-grained user permissions
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f2fc9612bdedb34bbcd9a6_D.svg'
		StaticText Infrastructure as code option
		StaticText Run Polytomic with Terraform or code
		StaticText INTEGRATIONS
		heading Integrations ready
		StaticText Two-way integrations available out of the box. Your integration requests built in days.
		image Snowflake logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fe62bac06e1f31f7e7_Integration%3DSnowflake.svg'
		StaticText Snowflake
		image Salesforce logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fe1b50c333f7272900_Integration%3DSalesforce.svg'
		StaticText Salesforce
		image BigQuery logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fec16b96f8e1d0bd1d_Integration%3DGoogleBigQuery.svg'
		StaticText BigQuery
		image Marketo logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fe36357a160e4f649d_Integration%3DMarketo.svg'
		StaticText Marketo
		image Stripe logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/662686d9be3408abe47038d4_stripe.svg'
		StaticText Stripe
		image Databricks logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6626874fe97f46d98bf616c2_databricks.svg'
		StaticText Databricks
		image NetSuite logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6626874242082482a88a829f_netsuite.svg'
		StaticText NetSuite
		image Google sheets logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba861b31a6dc8008c534e_Google%20Spreadsheets.svg'
		StaticText Google Sheets
		image Hubspot logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fed262c23c0cec31ea_Integration%3DHubspot.svg'
		StaticText HubSpot
		image Airtable logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7feb31a6d8cfc8c5065_Integration%3DAirtable.svg'
		StaticText Google Ads
		image S3 logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66268790afb50884fa08dc09_s3.svg'
		StaticText Amazon S3
		image Facebook logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66268762d1288a961e8db8ff_fbaudience.svg'
		StaticText Facebook Ads
		image AWS Athena logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/662686fac78979824347339c_awsathena.svg'
		StaticText Amazon Athena
		image LinkedIn logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/662684d1c789798243454499_LinkedinAds.svg'
		StaticText LinkedIn Ads
		image Airtable logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7feb31a6d8cfc8c5065_Integration%3DAirtable.svg'
		StaticText Airtable
		StaticText And many more...
		StaticText SUPPORT
		heading Fanatical customer support
		StaticText Replies to your messages in under a minute.
		image G2 support badge, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66267b7b427daadf85d022cb_best-support.svg'
		link Book demo, url='https://www.polytomic.com/book-demo'
		StaticText or
		link Start free trial, url='https://www.polytomic.com/start-free-trial'
		heading All the features you need, on the platform that does it all
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80eec4382052d8485ea_stack.svg'
		heading Replace multiple vendors
		StaticText Reduce costs and simplify workflows
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b9ded6e3bc292ef3ce2b_rotate.svg'
		heading One platform for all syncs
		StaticText ETL, Reverse ETL, CDC, iPaaS, APIs, and spreadsheets
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80e0008d2a556545a50_grid.svg'
		heading Sync only what’s changed
		StaticText Save on API limits and compute costs
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80e28226ec8287c7ac7_click.svg'
		heading Point and click
		StaticText Select and filter your data without writing code
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80e4aa24876fdb2cde7_terminal.svg'
		heading SQL query support
		StaticText Powerful transformations when you need them
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80eee57629e308fb9bf_orbit.svg'
		heading Pull from any API
		StaticText No more glue code for custom integrations
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80ef4d67f032153a0ba_server.svg'
		heading Self-hosting available
		StaticText Turnkey deployment to your private cloud
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622ba2450c42b5d99a1a404_shield.svg'
		heading Enterprise-ready
		StaticText SOC 2, GDPR, permissions, and audit logs
		heading Get started
		StaticText See a live demo or try free for 14 days.
		link Book demo, url='https://www.polytomic.com/book-demo'
		StaticText or
		link Start free trial, url='https://www.polytomic.com/start-free-trial'
		image
		StaticText Best Support
		StaticText Spring 2023
		image
		StaticText Best Meets Requirements
		StaticText Spring 2023
		image
		StaticText High Performer
		StaticText Spring 2023
	contentinfo
		StaticText Product
		link Overview, url='https://www.polytomic.com/overview'
		link Pricing, url='https://www.polytomic.com/pricing'
		link Integrations, url='https://www.polytomic.com/integrations'
		StaticText Use cases
		link Data Teams, url='https://www.polytomic.com/data-teams'
		link RevOps, url='https://www.polytomic.com/rev-ops'
		link Marketing, url='https://www.polytomic.com/marketing-teams'
		link Support, url='https://www.polytomic.com/support-teams'
		link API Endpoints, url='https://www.polytomic.com/api-sources'
		StaticText Resources
		link Documentation, url='https://docs.polytomic.com/'
		link Blog, url='https://www.polytomic.com/blog'
		link Ebooks, url='https://www.polytomic.com/ebooks'
		link Case studies, url='https://www.polytomic.com/customers'
		link Security, url='https://www.polytomic.com/security'
		StaticText Get in touch
		link Contact us, url='https://www.polytomic.com/contact'
		link, url='https://www.linkedin.com/company/polytomic/'
			image
		link, url='https://twitter.com/polytomic'
			image
		StaticText Copyright © 2024 Polytomic Inc. All rights reserved.
		StaticText ·
		link Terms of Service, url='https://www.polytomic.com/terms'
		StaticText ·
		link Privacy Policy, url='https://www.polytomic.com/privacy-policy'
		link, url='https://www.polytomic.com/'
			image
	generic
		[g] dialog Intercom live chat, center=(1876,1036), modal=False, title=Intercom live chat
```
</details>

**Reasoning for action:** By clicking on the Products button, I'm initiating navigation towards the relevant section that provides information about various products. This step is crucial as it allows me to gather information about the solutions Polytomic offers, fulfilling the user's requirement to explore products in order to assess how they can meet their organization's data needs.

**Action:** click(60) # Click on the Products button to explore the products offered by Polytomic.

**Change Description:** The Products button in the banner became focused after the click action, with no change in its expansion state, indicating that the user was preparing to explore the product offerings of Polytomic, while the content remained unchanged.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.polytomic.com/

https://www.polytomic.com/

**Content (before/after):** 

```
RootWebArea Polytomic, focused, url='https://www.polytomic.com/'
	banner
		[54] link, center=(559,40), url='https://www.polytomic.com/'
			image
		[60] button Products, center=(796,40), expanded=False, focused, hasPopup='menu'
```
<details><summary>Show more</summary>

```
		[81] button Use Cases, center=(891,40), expanded=False, hasPopup='menu'
		[93] link Integrations, center=(997,40), url='https://www.polytomic.com/integrations'
		[96] link Customers, center=(1105,40), url='https://www.polytomic.com/customers'
		[100] button Resources, center=(1208,40), expanded=False, hasPopup='menu'
		[111] link Book demo, center=(1318,40), url='https://www.polytomic.com/book-demo'
		[112] link Log in, center=(1410,40), url='https://app.polytomic.com/'
	main
		heading Sync
		link, url='https://www.polytomic.com/integrations'
			image
		[449] link, center=(959,239), url='https://www.polytomic.com/integrations'
			image
		[451] link, center=(959,203), url='https://www.polytomic.com/integrations'
			image
		heading to
		link, url='https://www.polytomic.com/integrations'
			image
		link, url='https://www.polytomic.com/integrations'
			image
		[457] link, center=(1148,203), url='https://www.polytomic.com/integrations'
			image
		heading Bidirectional ETL and data syncing
		[139] link Book demo, center=(867,368), url='https://www.polytomic.com/book-demo'
		StaticText or
		[142] link Start free trial, center=(1042,368), url='https://www.polytomic.com/start-free-trial'
		StaticText TRUSTED BY DATA AND OPS TEAMS
		image Brex, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae40b03e4a1bbb06f5_Brex-min.svg'
		image CloudTrucks, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037baf4c42b37e0fbac0a1_CloudTrucks-min.svg'
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f07d38b41f1d81718a9b8d_Retool.svg'
		image Vanta, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037baedd1159a0c1fc4709_Vanta-min.svg'
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66ebd7e824eaabe44e6322d1_Heygen.svg'
		image ID.me logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65ee85a9e4f132cab4914829_IDMe.svg'
		image Mercury, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae5786cce867364e28_Mercury-min.svg'
		image Vercel, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae8b1f86f497c26236_Vercel-min.svg'
		image Artsy, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bafb40e5c8a04b09b86_Artsy-min.svg'
		image Sourcegraph, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae3ad1dfdbb8f8f8b9_Sourcegraph-min.svg'
		image Telnyx, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae7434b46058dda760_Telnyx-min.svg'
		StaticText UNIFIED PLATFORM
		heading One platform for all syncs
		StaticText ETL, ELT, CDC streaming, Reverse ETL, and general data syncs in one platform.
		StaticText Move data between data warehouses, databases, cloud applications, general storage, spreadsheets, and HTTP APIs.
		[184] Video, center=(1247,1020)
		StaticText ENTERPRISE
		heading Enterprise-ready
		StaticText Polytomic is enterprise-ready out of the box.
		StaticText Self-hosted deployment option, RBAC permissions, audit log, no-code and code, and more.
		image Self hosted ETL solution., url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/630409f536fae0d423bba7ba_server%20icon.svg'
		StaticText Self-hosted option available
		StaticText Deploy Polytomic to your private cloud
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f2fc969ed78b266aff2c00_B.svg'
		StaticText Security and compliance
		StaticText SOC 2, GDPR, CCPA, and HIPAA compliant
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f2fc96061678aaa9cc2fba_C.svg'
		StaticText Enterprise permissions engine
		StaticText True RBAC fine-grained user permissions
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f2fc9612bdedb34bbcd9a6_D.svg'
		StaticText Infrastructure as code option
		StaticText Run Polytomic with Terraform or code
		StaticText INTEGRATIONS
		heading Integrations ready
		StaticText Two-way integrations available out of the box. Your integration requests built in days.
		image Snowflake logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fe62bac06e1f31f7e7_Integration%3DSnowflake.svg'
		StaticText Snowflake
		image Salesforce logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fe1b50c333f7272900_Integration%3DSalesforce.svg'
		StaticText Salesforce
		image BigQuery logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fec16b96f8e1d0bd1d_Integration%3DGoogleBigQuery.svg'
		StaticText BigQuery
		image Marketo logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fe36357a160e4f649d_Integration%3DMarketo.svg'
		StaticText Marketo
		image Stripe logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/662686d9be3408abe47038d4_stripe.svg'
		StaticText Stripe
		image Databricks logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6626874fe97f46d98bf616c2_databricks.svg'
		StaticText Databricks
		image NetSuite logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6626874242082482a88a829f_netsuite.svg'
		StaticText NetSuite
		image Google sheets logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba861b31a6dc8008c534e_Google%20Spreadsheets.svg'
		StaticText Google Sheets
		image Hubspot logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fed262c23c0cec31ea_Integration%3DHubspot.svg'
		StaticText HubSpot
		image Airtable logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7feb31a6d8cfc8c5065_Integration%3DAirtable.svg'
		StaticText Google Ads
		image S3 logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66268790afb50884fa08dc09_s3.svg'
		StaticText Amazon S3
		image Facebook logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66268762d1288a961e8db8ff_fbaudience.svg'
		StaticText Facebook Ads
		image AWS Athena logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/662686fac78979824347339c_awsathena.svg'
		StaticText Amazon Athena
		image LinkedIn logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/662684d1c789798243454499_LinkedinAds.svg'
		StaticText LinkedIn Ads
		image Airtable logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7feb31a6d8cfc8c5065_Integration%3DAirtable.svg'
		StaticText Airtable
		StaticText And many more...
		StaticText SUPPORT
		heading Fanatical customer support
		StaticText Replies to your messages in under a minute.
		image G2 support badge, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66267b7b427daadf85d022cb_best-support.svg'
		link Book demo, url='https://www.polytomic.com/book-demo'
		StaticText or
		link Start free trial, url='https://www.polytomic.com/start-free-trial'
		heading All the features you need, on the platform that does it all
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80eec4382052d8485ea_stack.svg'
		heading Replace multiple vendors
		StaticText Reduce costs and simplify workflows
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b9ded6e3bc292ef3ce2b_rotate.svg'
		heading One platform for all syncs
		StaticText ETL, Reverse ETL, CDC, iPaaS, APIs, and spreadsheets
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80e0008d2a556545a50_grid.svg'
		heading Sync only what’s changed
		StaticText Save on API limits and compute costs
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80e28226ec8287c7ac7_click.svg'
		heading Point and click
		StaticText Select and filter your data without writing code
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80e4aa24876fdb2cde7_terminal.svg'
		heading SQL query support
		StaticText Powerful transformations when you need them
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80eee57629e308fb9bf_orbit.svg'
		heading Pull from any API
		StaticText No more glue code for custom integrations
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80ef4d67f032153a0ba_server.svg'
		heading Self-hosting available
		StaticText Turnkey deployment to your private cloud
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622ba2450c42b5d99a1a404_shield.svg'
		heading Enterprise-ready
		StaticText SOC 2, GDPR, permissions, and audit logs
		heading Get started
		StaticText See a live demo or try free for 14 days.
		link Book demo, url='https://www.polytomic.com/book-demo'
		StaticText or
		link Start free trial, url='https://www.polytomic.com/start-free-trial'
		image
		StaticText Best Support
		StaticText Spring 2023
		image
		StaticText Best Meets Requirements
		StaticText Spring 2023
		image
		StaticText High Performer
		StaticText Spring 2023
	contentinfo
		StaticText Product
		link Overview, url='https://www.polytomic.com/overview'
		link Pricing, url='https://www.polytomic.com/pricing'
		link Integrations, url='https://www.polytomic.com/integrations'
		StaticText Use cases
		link Data Teams, url='https://www.polytomic.com/data-teams'
		link RevOps, url='https://www.polytomic.com/rev-ops'
		link Marketing, url='https://www.polytomic.com/marketing-teams'
		link Support, url='https://www.polytomic.com/support-teams'
		link API Endpoints, url='https://www.polytomic.com/api-sources'
		StaticText Resources
		link Documentation, url='https://docs.polytomic.com/'
		link Blog, url='https://www.polytomic.com/blog'
		link Ebooks, url='https://www.polytomic.com/ebooks'
		link Case studies, url='https://www.polytomic.com/customers'
		link Security, url='https://www.polytomic.com/security'
		StaticText Get in touch
		link Contact us, url='https://www.polytomic.com/contact'
		link, url='https://www.linkedin.com/company/polytomic/'
			image
		link, url='https://twitter.com/polytomic'
			image
		StaticText Copyright © 2024 Polytomic Inc. All rights reserved.
		StaticText ·
		link Terms of Service, url='https://www.polytomic.com/terms'
		StaticText ·
		link Privacy Policy, url='https://www.polytomic.com/privacy-policy'
		link, url='https://www.polytomic.com/'
			image
	generic
		[g] dialog Intercom live chat, center=(1876,1036), modal=False, title=Intercom live chat
```
</details>



```
RootWebArea Polytomic, focused, url='https://www.polytomic.com/'
	banner
		[54] link, center=(559,40), url='https://www.polytomic.com/'
			image
		[60] button Products, center=(796,40), expanded=False, hasPopup='menu'
```
<details><summary>Show more</summary>

```
		[81] button Use Cases, center=(891,40), expanded=False, focused, hasPopup='menu'
		[93] link Integrations, center=(997,40), url='https://www.polytomic.com/integrations'
		[96] link Customers, center=(1105,40), url='https://www.polytomic.com/customers'
		[100] button Resources, center=(1208,40), expanded=False, hasPopup='menu'
		[111] link Book demo, center=(1318,40), url='https://www.polytomic.com/book-demo'
		[112] link Log in, center=(1410,40), url='https://app.polytomic.com/'
	main
		heading Sync
		link, url='https://www.polytomic.com/integrations'
			image
		[461] link, center=(959,239), url='https://www.polytomic.com/integrations'
			image
		[463] link, center=(959,203), url='https://www.polytomic.com/integrations'
			image
		heading to
		link, url='https://www.polytomic.com/integrations'
			image
		link, url='https://www.polytomic.com/integrations'
			image
		[469] link, center=(1148,203), url='https://www.polytomic.com/integrations'
			image
		heading Bidirectional ETL and data syncing
		[139] link Book demo, center=(867,368), url='https://www.polytomic.com/book-demo'
		StaticText or
		[142] link Start free trial, center=(1042,368), url='https://www.polytomic.com/start-free-trial'
		StaticText TRUSTED BY DATA AND OPS TEAMS
		image Brex, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae40b03e4a1bbb06f5_Brex-min.svg'
		image CloudTrucks, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037baf4c42b37e0fbac0a1_CloudTrucks-min.svg'
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f07d38b41f1d81718a9b8d_Retool.svg'
		image Vanta, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037baedd1159a0c1fc4709_Vanta-min.svg'
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66ebd7e824eaabe44e6322d1_Heygen.svg'
		image ID.me logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65ee85a9e4f132cab4914829_IDMe.svg'
		image Mercury, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae5786cce867364e28_Mercury-min.svg'
		image Vercel, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae8b1f86f497c26236_Vercel-min.svg'
		image Artsy, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bafb40e5c8a04b09b86_Artsy-min.svg'
		image Sourcegraph, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae3ad1dfdbb8f8f8b9_Sourcegraph-min.svg'
		image Telnyx, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae7434b46058dda760_Telnyx-min.svg'
		StaticText UNIFIED PLATFORM
		heading One platform for all syncs
		StaticText ETL, ELT, CDC streaming, Reverse ETL, and general data syncs in one platform.
		StaticText Move data between data warehouses, databases, cloud applications, general storage, spreadsheets, and HTTP APIs.
		[184] Video, center=(1247,1020)
		StaticText ENTERPRISE
		heading Enterprise-ready
		StaticText Polytomic is enterprise-ready out of the box.
		StaticText Self-hosted deployment option, RBAC permissions, audit log, no-code and code, and more.
		image Self hosted ETL solution., url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/630409f536fae0d423bba7ba_server%20icon.svg'
		StaticText Self-hosted option available
		StaticText Deploy Polytomic to your private cloud
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f2fc969ed78b266aff2c00_B.svg'
		StaticText Security and compliance
		StaticText SOC 2, GDPR, CCPA, and HIPAA compliant
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f2fc96061678aaa9cc2fba_C.svg'
		StaticText Enterprise permissions engine
		StaticText True RBAC fine-grained user permissions
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f2fc9612bdedb34bbcd9a6_D.svg'
		StaticText Infrastructure as code option
		StaticText Run Polytomic with Terraform or code
		StaticText INTEGRATIONS
		heading Integrations ready
		StaticText Two-way integrations available out of the box. Your integration requests built in days.
		image Snowflake logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fe62bac06e1f31f7e7_Integration%3DSnowflake.svg'
		StaticText Snowflake
		image Salesforce logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fe1b50c333f7272900_Integration%3DSalesforce.svg'
		StaticText Salesforce
		image BigQuery logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fec16b96f8e1d0bd1d_Integration%3DGoogleBigQuery.svg'
		StaticText BigQuery
		image Marketo logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fe36357a160e4f649d_Integration%3DMarketo.svg'
		StaticText Marketo
		image Stripe logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/662686d9be3408abe47038d4_stripe.svg'
		StaticText Stripe
		image Databricks logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6626874fe97f46d98bf616c2_databricks.svg'
		StaticText Databricks
		image NetSuite logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6626874242082482a88a829f_netsuite.svg'
		StaticText NetSuite
		image Google sheets logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba861b31a6dc8008c534e_Google%20Spreadsheets.svg'
		StaticText Google Sheets
		image Hubspot logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fed262c23c0cec31ea_Integration%3DHubspot.svg'
		StaticText HubSpot
		image Airtable logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7feb31a6d8cfc8c5065_Integration%3DAirtable.svg'
		StaticText Google Ads
		image S3 logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66268790afb50884fa08dc09_s3.svg'
		StaticText Amazon S3
		image Facebook logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66268762d1288a961e8db8ff_fbaudience.svg'
		StaticText Facebook Ads
		image AWS Athena logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/662686fac78979824347339c_awsathena.svg'
		StaticText Amazon Athena
		image LinkedIn logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/662684d1c789798243454499_LinkedinAds.svg'
		StaticText LinkedIn Ads
		image Airtable logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7feb31a6d8cfc8c5065_Integration%3DAirtable.svg'
		StaticText Airtable
		StaticText And many more...
		StaticText SUPPORT
		heading Fanatical customer support
		StaticText Replies to your messages in under a minute.
		image G2 support badge, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66267b7b427daadf85d022cb_best-support.svg'
		link Book demo, url='https://www.polytomic.com/book-demo'
		StaticText or
		link Start free trial, url='https://www.polytomic.com/start-free-trial'
		heading All the features you need, on the platform that does it all
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80eec4382052d8485ea_stack.svg'
		heading Replace multiple vendors
		StaticText Reduce costs and simplify workflows
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b9ded6e3bc292ef3ce2b_rotate.svg'
		heading One platform for all syncs
		StaticText ETL, Reverse ETL, CDC, iPaaS, APIs, and spreadsheets
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80e0008d2a556545a50_grid.svg'
		heading Sync only what’s changed
		StaticText Save on API limits and compute costs
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80e28226ec8287c7ac7_click.svg'
		heading Point and click
		StaticText Select and filter your data without writing code
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80e4aa24876fdb2cde7_terminal.svg'
		heading SQL query support
		StaticText Powerful transformations when you need them
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80eee57629e308fb9bf_orbit.svg'
		heading Pull from any API
		StaticText No more glue code for custom integrations
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80ef4d67f032153a0ba_server.svg'
		heading Self-hosting available
		StaticText Turnkey deployment to your private cloud
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622ba2450c42b5d99a1a404_shield.svg'
		heading Enterprise-ready
		StaticText SOC 2, GDPR, permissions, and audit logs
		heading Get started
		StaticText See a live demo or try free for 14 days.
		link Book demo, url='https://www.polytomic.com/book-demo'
		StaticText or
		link Start free trial, url='https://www.polytomic.com/start-free-trial'
		image
		StaticText Best Support
		StaticText Spring 2023
		image
		StaticText Best Meets Requirements
		StaticText Spring 2023
		image
		StaticText High Performer
		StaticText Spring 2023
	contentinfo
		StaticText Product
		link Overview, url='https://www.polytomic.com/overview'
		link Pricing, url='https://www.polytomic.com/pricing'
		link Integrations, url='https://www.polytomic.com/integrations'
		StaticText Use cases
		link Data Teams, url='https://www.polytomic.com/data-teams'
		link RevOps, url='https://www.polytomic.com/rev-ops'
		link Marketing, url='https://www.polytomic.com/marketing-teams'
		link Support, url='https://www.polytomic.com/support-teams'
		link API Endpoints, url='https://www.polytomic.com/api-sources'
		StaticText Resources
		link Documentation, url='https://docs.polytomic.com/'
		link Blog, url='https://www.polytomic.com/blog'
		link Ebooks, url='https://www.polytomic.com/ebooks'
		link Case studies, url='https://www.polytomic.com/customers'
		link Security, url='https://www.polytomic.com/security'
		StaticText Get in touch
		link Contact us, url='https://www.polytomic.com/contact'
		link, url='https://www.linkedin.com/company/polytomic/'
			image
		link, url='https://twitter.com/polytomic'
			image
		StaticText Copyright © 2024 Polytomic Inc. All rights reserved.
		StaticText ·
		link Terms of Service, url='https://www.polytomic.com/terms'
		StaticText ·
		link Privacy Policy, url='https://www.polytomic.com/privacy-policy'
		link, url='https://www.polytomic.com/'
			image
	generic
		[g] dialog Intercom live chat, center=(1876,1036), modal=False, title=Intercom live chat
```
</details>

**Reasoning for action:** By clicking on the Use Cases button, I proceed to explore specific examples of how Polytomic's products are utilized by various teams. This is directly related to the user story, as understanding these use cases is crucial for determining how Polytomic can effectively meet my organization's data needs.

**Action:** click(81) # Click on the Use Cases button to explore how different teams utilize Polytomic's products.

**Change Description:** The Use Cases button in the banner became focused after being clicked, indicating that the user has selected to explore how different teams utilize Polytomic's products, although no changes to the overall URL or content structure were detected.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.polytomic.com/

https://www.polytomic.com/integrations

**Content (before/after):** 

```
RootWebArea Polytomic, focused, url='https://www.polytomic.com/'
	banner
		[54] link, center=(559,40), url='https://www.polytomic.com/'
			image
		[60] button Products, center=(796,40), expanded=False, hasPopup='menu'
```
<details><summary>Show more</summary>

```
		[81] button Use Cases, center=(891,40), expanded=False, focused, hasPopup='menu'
		[93] link Integrations, center=(997,40), url='https://www.polytomic.com/integrations'
		[96] link Customers, center=(1105,40), url='https://www.polytomic.com/customers'
		[100] button Resources, center=(1208,40), expanded=False, hasPopup='menu'
		[111] link Book demo, center=(1318,40), url='https://www.polytomic.com/book-demo'
		[112] link Log in, center=(1410,40), url='https://app.polytomic.com/'
	main
		heading Sync
		link, url='https://www.polytomic.com/integrations'
			image
		[461] link, center=(959,239), url='https://www.polytomic.com/integrations'
			image
		[463] link, center=(959,203), url='https://www.polytomic.com/integrations'
			image
		heading to
		link, url='https://www.polytomic.com/integrations'
			image
		link, url='https://www.polytomic.com/integrations'
			image
		[469] link, center=(1148,203), url='https://www.polytomic.com/integrations'
			image
		heading Bidirectional ETL and data syncing
		[139] link Book demo, center=(867,368), url='https://www.polytomic.com/book-demo'
		StaticText or
		[142] link Start free trial, center=(1042,368), url='https://www.polytomic.com/start-free-trial'
		StaticText TRUSTED BY DATA AND OPS TEAMS
		image Brex, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae40b03e4a1bbb06f5_Brex-min.svg'
		image CloudTrucks, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037baf4c42b37e0fbac0a1_CloudTrucks-min.svg'
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f07d38b41f1d81718a9b8d_Retool.svg'
		image Vanta, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037baedd1159a0c1fc4709_Vanta-min.svg'
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66ebd7e824eaabe44e6322d1_Heygen.svg'
		image ID.me logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65ee85a9e4f132cab4914829_IDMe.svg'
		image Mercury, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae5786cce867364e28_Mercury-min.svg'
		image Vercel, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae8b1f86f497c26236_Vercel-min.svg'
		image Artsy, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bafb40e5c8a04b09b86_Artsy-min.svg'
		image Sourcegraph, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae3ad1dfdbb8f8f8b9_Sourcegraph-min.svg'
		image Telnyx, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/65037bae7434b46058dda760_Telnyx-min.svg'
		StaticText UNIFIED PLATFORM
		heading One platform for all syncs
		StaticText ETL, ELT, CDC streaming, Reverse ETL, and general data syncs in one platform.
		StaticText Move data between data warehouses, databases, cloud applications, general storage, spreadsheets, and HTTP APIs.
		[184] Video, center=(1247,1020)
		StaticText ENTERPRISE
		heading Enterprise-ready
		StaticText Polytomic is enterprise-ready out of the box.
		StaticText Self-hosted deployment option, RBAC permissions, audit log, no-code and code, and more.
		image Self hosted ETL solution., url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/630409f536fae0d423bba7ba_server%20icon.svg'
		StaticText Self-hosted option available
		StaticText Deploy Polytomic to your private cloud
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f2fc969ed78b266aff2c00_B.svg'
		StaticText Security and compliance
		StaticText SOC 2, GDPR, CCPA, and HIPAA compliant
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f2fc96061678aaa9cc2fba_C.svg'
		StaticText Enterprise permissions engine
		StaticText True RBAC fine-grained user permissions
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66f2fc9612bdedb34bbcd9a6_D.svg'
		StaticText Infrastructure as code option
		StaticText Run Polytomic with Terraform or code
		StaticText INTEGRATIONS
		heading Integrations ready
		StaticText Two-way integrations available out of the box. Your integration requests built in days.
		image Snowflake logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fe62bac06e1f31f7e7_Integration%3DSnowflake.svg'
		StaticText Snowflake
		image Salesforce logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fe1b50c333f7272900_Integration%3DSalesforce.svg'
		StaticText Salesforce
		image BigQuery logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fec16b96f8e1d0bd1d_Integration%3DGoogleBigQuery.svg'
		StaticText BigQuery
		image Marketo logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fe36357a160e4f649d_Integration%3DMarketo.svg'
		StaticText Marketo
		image Stripe logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/662686d9be3408abe47038d4_stripe.svg'
		StaticText Stripe
		image Databricks logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6626874fe97f46d98bf616c2_databricks.svg'
		StaticText Databricks
		image NetSuite logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6626874242082482a88a829f_netsuite.svg'
		StaticText NetSuite
		image Google sheets logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba861b31a6dc8008c534e_Google%20Spreadsheets.svg'
		StaticText Google Sheets
		image Hubspot logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7fed262c23c0cec31ea_Integration%3DHubspot.svg'
		StaticText HubSpot
		image Airtable logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7feb31a6d8cfc8c5065_Integration%3DAirtable.svg'
		StaticText Google Ads
		image S3 logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66268790afb50884fa08dc09_s3.svg'
		StaticText Amazon S3
		image Facebook logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66268762d1288a961e8db8ff_fbaudience.svg'
		StaticText Facebook Ads
		image AWS Athena logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/662686fac78979824347339c_awsathena.svg'
		StaticText Amazon Athena
		image LinkedIn logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/662684d1c789798243454499_LinkedinAds.svg'
		StaticText LinkedIn Ads
		image Airtable logo, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/62eba7feb31a6d8cfc8c5065_Integration%3DAirtable.svg'
		StaticText Airtable
		StaticText And many more...
		StaticText SUPPORT
		heading Fanatical customer support
		StaticText Replies to your messages in under a minute.
		image G2 support badge, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/66267b7b427daadf85d022cb_best-support.svg'
		link Book demo, url='https://www.polytomic.com/book-demo'
		StaticText or
		link Start free trial, url='https://www.polytomic.com/start-free-trial'
		heading All the features you need, on the platform that does it all
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80eec4382052d8485ea_stack.svg'
		heading Replace multiple vendors
		StaticText Reduce costs and simplify workflows
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b9ded6e3bc292ef3ce2b_rotate.svg'
		heading One platform for all syncs
		StaticText ETL, Reverse ETL, CDC, iPaaS, APIs, and spreadsheets
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80e0008d2a556545a50_grid.svg'
		heading Sync only what’s changed
		StaticText Save on API limits and compute costs
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80e28226ec8287c7ac7_click.svg'
		heading Point and click
		StaticText Select and filter your data without writing code
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80e4aa24876fdb2cde7_terminal.svg'
		heading SQL query support
		StaticText Powerful transformations when you need them
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80eee57629e308fb9bf_orbit.svg'
		heading Pull from any API
		StaticText No more glue code for custom integrations
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622b80ef4d67f032153a0ba_server.svg'
		heading Self-hosting available
		StaticText Turnkey deployment to your private cloud
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622ba2450c42b5d99a1a404_shield.svg'
		heading Enterprise-ready
		StaticText SOC 2, GDPR, permissions, and audit logs
		heading Get started
		StaticText See a live demo or try free for 14 days.
		link Book demo, url='https://www.polytomic.com/book-demo'
		StaticText or
		link Start free trial, url='https://www.polytomic.com/start-free-trial'
		image
		StaticText Best Support
		StaticText Spring 2023
		image
		StaticText Best Meets Requirements
		StaticText Spring 2023
		image
		StaticText High Performer
		StaticText Spring 2023
	contentinfo
		StaticText Product
		link Overview, url='https://www.polytomic.com/overview'
		link Pricing, url='https://www.polytomic.com/pricing'
		link Integrations, url='https://www.polytomic.com/integrations'
		StaticText Use cases
		link Data Teams, url='https://www.polytomic.com/data-teams'
		link RevOps, url='https://www.polytomic.com/rev-ops'
		link Marketing, url='https://www.polytomic.com/marketing-teams'
		link Support, url='https://www.polytomic.com/support-teams'
		link API Endpoints, url='https://www.polytomic.com/api-sources'
		StaticText Resources
		link Documentation, url='https://docs.polytomic.com/'
		link Blog, url='https://www.polytomic.com/blog'
		link Ebooks, url='https://www.polytomic.com/ebooks'
		link Case studies, url='https://www.polytomic.com/customers'
		link Security, url='https://www.polytomic.com/security'
		StaticText Get in touch
		link Contact us, url='https://www.polytomic.com/contact'
		link, url='https://www.linkedin.com/company/polytomic/'
			image
		link, url='https://twitter.com/polytomic'
			image
		StaticText Copyright © 2024 Polytomic Inc. All rights reserved.
		StaticText ·
		link Terms of Service, url='https://www.polytomic.com/terms'
		StaticText ·
		link Privacy Policy, url='https://www.polytomic.com/privacy-policy'
		link, url='https://www.polytomic.com/'
			image
	generic
		[g] dialog Intercom live chat, center=(1876,1036), modal=False, title=Intercom live chat
```
</details>



```
RootWebArea Polytomic | Integrations, focused, url='https://www.polytomic.com/integrations'
	banner
		[50] link, center=(559,40), url='https://www.polytomic.com/'
			image
		[56] button Products, center=(796,40), expanded=False, hasPopup='menu'
```
<details><summary>Show more</summary>

```
		[77] button Use Cases, center=(891,40), expanded=False, hasPopup='menu'
		[89] link Integrations, center=(997,40), url='https://www.polytomic.com/integrations'
		[92] link Customers, center=(1105,40), url='https://www.polytomic.com/customers'
		[96] button Resources, center=(1208,40), expanded=False, hasPopup='menu'
		[107] link Book demo, center=(1318,40), url='https://www.polytomic.com/book-demo'
		[108] link Log in, center=(1410,40), url='https://app.polytomic.com/'
	main
		heading Sync your data in all directions
		image, url='https://cdn.prod.website-files.com/62eb5e6ae107875bf1582276/6622919b29c26f98b9bde1c7_sparkle.png'
		StaticText New integrations built on request —
		[124] link Contact us here, center=(1144,310), url='https://www.polytomic.com/contact'
		list
			listitem
				[130] link Snowflake Snowflake Sync to Snowflake from your SaaS tools, database, cloud storage systems, spreadsheets, and APIs. Or go the other way: sync from Snowflake to any of your SaaS tools, databases, cloud storage systems, spreadsheets, or APIs., center=(632,490), inner_text=Snowflake
Sync to Snowflake from your SaaS tools, database, cloud storage systems, spreadsheets, and APIs. Or go the other way: sync from Snowflake to any of your SaaS tools, databases, cloud storage systems, spreadsheets, or APIs., url='https://www.polytomic.com/integrations/snowflake'
					StaticText Snowflake
					image Snowflake, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f11c3cae4a3ac047fd3_609cbc5238e9e1a82a566dc7_snowflake.svg'
			listitem
				[139] link Salesforce Salesforce Sync to Salesforce from your data warehouse, databases, SaaS tools, spreadsheets, and APIs. Or go the other way: sync from Salesforce to your data warehouse, databases, SaaS tools, spreadsheets, or custom APIs., center=(960,490), inner_text=Salesforce
Sync to Salesforce from your data warehouse, databases, SaaS tools, spreadsheets, and APIs. Or go the other way: sync from Salesforce to your data warehouse, databases, SaaS tools, spreadsheets, or custom APIs., url='https://www.polytomic.com/integrations/salesforce'
					StaticText Salesforce
					image Salesforce, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f11e9346d094c2ba41d_609cbc8998a5e184990fa694_salesforce.svg'
			listitem
				[148] link Marketo Marketo Sync to Marketo from your data warehouse, databases, SaaS tools, spreadsheets, or APIs. Or go the other way: sync from Marketo to your data warehouse or any other systems or SaaS tools., center=(1288,490), inner_text=Marketo
Sync to Marketo from your data warehouse, databases, SaaS tools, spreadsheets, or APIs. Or go the other way: sync from Marketo to your data warehouse or any other systems or SaaS tools., url='https://www.polytomic.com/integrations/marketo'
					StaticText Marketo
					image Marketo, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f101626a4288bf9b75c_609cbc9ee8d6fac604bcf118_marketo.svg'
			listitem
				[157] link HubSpot HubSpot Sync from your data warehouse, databases, SaaS tools, spreadsheets, or APIs to any HubSpot objects (including custom ones). Or go the other way: from HubSpot to your data warehouse, databases, SaaS tools, spreadsheets, and custom APIs., center=(632,783), inner_text=HubSpot
Sync from your data warehouse, databases, SaaS tools, spreadsheets, or APIs to any HubSpot objects (including custom ones). Or go the other way: from HubSpot to your data warehouse, databases, SaaS tools, spreadsheets, and custom APIs., url='https://www.polytomic.com/integrations/hubspot'
					StaticText HubSpot
					image HubSpot, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0f82b07875c0092b2d_609cbcb2b34a9c0635145fc1_hubspot.svg'
			listitem
				[166] link Google Sheets Google Sheets Sync any of your data to Google Sheets, or sync from Google Sheets to any of your business systems or APIs., center=(960,783), inner_text=Google Sheets
Sync any of your data to Google Sheets, or sync from Google Sheets to any of your business systems or APIs., url='https://www.polytomic.com/integrations/googlesheets'
					StaticText Google Sheets
					image Google Sheets, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f10a831a0520d7448c4_609cbcd40bef65375a65fe6a_gsheets.svg'
			listitem
				[175] link Airtable Airtable Sync any of your data to Airtable, or sync from Airtable to any of your business systems, spreadsheets, or APIs., center=(1288,783), inner_text=Airtable
Sync any of your data to Airtable, or sync from Airtable to any of your business systems, spreadsheets, or APIs., url='https://www.polytomic.com/integrations/airtable'
					StaticText Airtable
					image Airtable, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0dfdb6a3031db53189_609cbcea9903f4851903be57_airtable.svg'
			listitem
				link PostgreSQL PostgreSQL CDC stream and replicate your PostgreSQL database to your data warehouse and cloud storage systems. Or sync from PostgreSQL to your SaaS tools like Salesforce, spreadsheets, APIs, and other business systems. Or go the other way: write from any of the mentioned systems to your PostgreSQL database., url='https://www.polytomic.com/integrations/postgresql'
					StaticText PostgreSQL
					[188] image PostgreSQL, center=(746,985), url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f110dac045636cf859f_609cbcffb4db574d532895ee_postresql.svg'
					[187] div, center=(569,986), inner_text=PostgreSQL
			listitem
				link BigQuery BigQuery Sync to BigQuery from your SaaS tools, database, cloud storage systems, spreadsheets, and APIs. Or go the other way: sync from BigQuery to any of your SaaS tools, databases, cloud storage systems, spreadsheets, or APIs., url='https://www.polytomic.com/integrations/bigquery'
					StaticText BigQuery
					[197] image BigQuery, center=(1074,985), url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0e1626a43e1bf9b738_609cbd110bef65519b65fe9f_bigquery.svg'
					[196] div, center=(884,986), inner_text=BigQuery
			listitem
				link Redshift Redshift Sync to Redshift from your SaaS tools, database, cloud storage systems, spreadsheets, and APIs. Or go the other way: sync from Redshift to any of your SaaS tools, databases, cloud storage systems, spreadsheets, or APIs., url='https://www.polytomic.com/integrations/redshift'
					StaticText Redshift
					[206] image Redshift, center=(1402,985), url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f11671bc501c6c37a0b_609cbd22559d6554c1a88d23_redshift.svg'
					[205] div, center=(1206,986), inner_text=Redshift
			listitem
				link Pipedrive Pipedrive Enrich people, organizations, or any Pipedrive object with data from your databases, spreadsheets, or third-party APIs., url='https://www.polytomic.com/integrations/pipedrive'
					StaticText Pipedrive
					image Pipedrive, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f1155f1885f706144b0_609cbd350f427a607770c2dc_pipedrive.svg'
			listitem
				link Intercom Intercom Create and enrich users and companies from your databases, spreadsheets, or APIs., url='https://www.polytomic.com/integrations/intercom'
					StaticText Intercom
					image Intercom, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0f57251dae4f730cf2_609cbd4a8cdfb5041196a01c_intercom.svg'
			listitem
				link Front Front Sync all Front data to your data warehouse, or sync from anywhere to enrich your Front contacts and conversations., url='https://www.polytomic.com/integrations/front'
					StaticText Front
					image Front, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0fc1c769933c10637d_609cbd62b4db57561728961a_front.svg'
			listitem
				link MySQL MySQL CDC stream and replicate your MySQL database to your data warehouse and cloud storage systems. Or sync from MySQL to your SaaS tools like Salesforce, spreadsheets, APIs, and other business systems. Or go the other way: write from any of the mentioned systems to your MySQL database., url='https://www.polytomic.com/integrations/mysql'
					StaticText MySQL
					image MySQL, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f11c1c7697419106385_609cbd74e909679ff5179f83_mysql.svg'
			listitem
				link Azure SQL Azure SQL Automatically sync data from your Azure SQL instance to your data warehouses, business systems or spreadsheets. Or, go the other way and sync any data into your Azure SQL instance., url='https://www.polytomic.com/integrations/azuresql'
					StaticText Azure SQL
					image Azure SQL, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0eb7ae540cc1476dc5_609cbd8a3060e49ea97f79f0_azure.svg'
			listitem
				link Mongo DB Mongo DB Sync data from MongoDB to your data warehouses, databases, SaaS tools, spreadsheets, cloud storage systems, or webhooks. Or go the other way: sync to MongoDB from your data warehouses, databases, SaaS tools, spreadsheets, cloud storage systems, or arbitrary APIs., url='https://www.polytomic.com/integrations/mongo-db'
					StaticText Mongo DB
					image Mongo DB, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f1194e75001e541291b_609cbd9c01b2334b8e8cc96c_mongodb.svg'
			listitem
				link Stripe Stripe Enrich your Stripe objects with data from your databases, spreadsheets, and APIs. Or pipe Stripe data anywhere you want., url='https://www.polytomic.com/integrations/stripe'
					StaticText Stripe
					image Stripe, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f124a7679869816b3da_609cbdac96e6d958c12fd25e_stripe.svg'
			listitem
				link Facebook Ads Facebook Ads Sync your Facebook Ads data to your data warehouse and cloud storage systems. Or, sync audiences and conversion data to Facebook Ads from any of your data stores, apps, spreadsheets, or APIs., url='https://www.polytomic.com/integrations/facebook-ads'
					StaticText Facebook Ads
					image Facebook Ads, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0f9cf5df6ed50651a4_609cbdc275c3123d8a27c51c_fb.svg'
			listitem
				link Google Ads Google Ads Sync your Google Ads data to your data warehouse and cloud storage systems. Or, sync audiences and conversion data to Google Ads from any of your data stores, apps, spreadsheets, or APIs., url='https://www.polytomic.com/integrations/google-ads'
					StaticText Google Ads
					image Google Ads, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0ffdb6a31adeb531a1_609cbdd56a47eb18b0890227_adwords.svg'
			listitem
				link Affinity CRM Affinity CRM Sync your Affinity People, Organizations, and Lists to your data warehouses, databases, SaaS tools, spreadsheets, and cloud storage. Or go the other way and sync from any of your systems to Affinity People, Organizations, and Lists., url='https://www.polytomic.com/integrations/affinity-crm'
					StaticText Affinity CRM
					image Affinity CRM, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0d01516fbbc9e5c6c2_609cbde9e8d6fa4778bcf3b9_affinity%2520crm.svg'
			listitem
				link Customer.io Customer.io Sync to your Customer.io user profiles and custom objects from your databases, data warehouses, SaaS tools, spreadsheets, and APIs., url='https://www.polytomic.com/integrations/customer-io'
					StaticText Customer.io
					image Customer.io, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0e968e2ee69aaf8420_609cbdf9e871691bfbbd0ce7_customer.io.svg'
			listitem
				link Amplitude Amplitude Sync any of your user and event data to Amplitude without writing any code., url='https://www.polytomic.com/integrations/amplitude'
					StaticText Amplitude
					image Amplitude, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/63d1c86391ebd3cc0bb4842d_amplitude-logo-67DFD43C34-seeklogo.com.png'
			listitem
				link HTTP API HTTP API Sync from any REST API to your databases, data warehouses, business systems, spreadsheets, and webhooks., url='https://www.polytomic.com/integrations/http-api'
					StaticText HTTP API
					image HTTP API, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0f487435c4a1fc2416_60b8249f5a15302b8f95ea28_Screen%2520Shot%25202021-06-02%2520at%25204.01.29%2520PM.png'
			listitem
				link Iterable Iterable Enrich Iterable users, campaigns, or any other object with your own data for personalized campaigns., url='https://www.polytomic.com/integrations/iterable'
					StaticText Iterable
					image Iterable, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/63d1d3db942f2d0164ac61b7_Iterable-icon.png'
			listitem
				link Webhook Webhook Define your own webhooks and regularly sync data to them from any APIs, databases, or spreadsheets without writing code., url='https://www.polytomic.com/integrations/webhook'
					StaticText Webhook
					image Webhook, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f12a7b8423e8f98dfae_60b829e535092a6b3dd4ac60_webhooks%2520logo%2520copy.png'
			listitem
				link Zendesk Support Zendesk Support Enrich Zendesk tickets, users, and organizations with any of your app data, spreadsheets, or even third-party APIs. Or, sync your Zendesk data into your databases, business systems, or spreadsheets., url='https://www.polytomic.com/integrations/zendesk-support'
					StaticText Zendesk Support
					image Zendesk Support, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/63d1d35191ebd35f47b55e2d_zendesk-icon.svg'
			listitem
				link Pardot Pardot Sync from your databases, warehouses, SaaS apps, API, or spreadsheets to any Pardot objects. Or, sync all your Pardot data into your data warehouses and cloud storage systems., url='https://www.polytomic.com/integrations/pardot'
					StaticText Pardot
					image Pardot, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/63d1d42825f4c933adb80588_salesforce-pardot-1024x683-p-500.webp'
			listitem
				link Freshdesk Freshdesk Sync to and from Freshdesk tickets, contacts, and companies with your app data, data warehouse, spreadsheets, SaaS tools, or even third-party APIs., url='https://www.polytomic.com/integrations/freshdesk'
					StaticText Freshdesk
					image Freshdesk, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/63d1cc0930ce1badd3ae1f24_Freshdesk%20logo.png'
			listitem
				link Klaviyo Klaviyo Sync any of your user and event data to Klaviyo without writing any code., url='https://www.polytomic.com/integrations/klaviyo'
					StaticText Klaviyo
					image Klaviyo, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f10cdba4270414b8476_60f6fb704a31317441fc5d75_download.png'
			listitem
				link Segment Segment Send users, events, and properties to Segment from your databases, spreadsheets, and business applications without writing any code., url='https://www.polytomic.com/integrations/segment'
					StaticText Segment
					image Segment, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f119b113936bb73935f_6122c98d589f5f4ce4e78bf4_Segment%25E2%2580%2594Icon%25E2%2580%2594Green.svg'
			listitem
				link Azure Synapse Azure Synapse Automatically sync data from your Azure Synapse instance to your business systems, spreadsheets, or webhooks., url='https://www.polytomic.com/integrations/azure-synapse'
					StaticText Azure Synapse
					image Azure Synapse, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0e084ff0eacf0df38f_61234aa2de9b7ee8d6fe3819_synapse.svg'
			listitem
				link Chargebee Chargebee Sync customers and subscriptions to your databases, business systems, and spreadsheets., url='https://www.polytomic.com/integrations/chargebee'
					StaticText Chargebee
					image Chargebee, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0e57251dfb45730ceb_613fcc800e4b99b05ef64b10_chargebee.svg'
			listitem
				link AWS Athena AWS Athena Sync data from AWS Athena to your data warehouse, CRMs, business systems, spreadsheets, and webhooks., url='https://www.polytomic.com/integrations/aws-athena'
					StaticText AWS Athena
					image AWS Athena, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0d9100d864209f954d_613fccf1dac76e17a53f5d8f_awsathena.svg'
			listitem
				link Azure Cosmos DB Azure Cosmos DB Sync data from Cosmos DB to your data warehouse, business systems, spreadsheets, and webhooks., url='https://www.polytomic.com/integrations/azure-cosmos-db'
					StaticText Azure Cosmos DB
					image Azure Cosmos DB, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0e3e8563e644c89d7a_6148e43631e745fd5359e75a_cosmosdb.svg'
			listitem
				link Harmonic Harmonic Enrich people and companies in Affinity, Airtable, databases, data warehouses, or other business systems with data from Harmonic., url='https://www.polytomic.com/integrations/harmonic'
					StaticText Harmonic
					image Harmonic, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/635074cde0b26466b02a3082_harmonic.svg'
			listitem
				link Databricks Databricks Sync to Databricks from your SaaS tools, database, cloud storage systems, spreadsheets, and APIs. Or go the other way: sync from Databricks to any of your SaaS tools, databases, cloud storage systems, spreadsheets, or APIs., url='https://www.polytomic.com/integrations/databricks'
					StaticText Databricks
					image Databricks, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0e9a314b4e8cfbfde4_61772a212557f730136c1d75_Databricks-iconOnly.svg'
			listitem
				link Smartsheet Smartsheet Sync any data to Smartsheets from databases, CRMS, or other spreadsheets, or sync from Smartsheets to any of your databases, applications, or spreadsheets., url='https://www.polytomic.com/integrations/smartsheet'
					StaticText Smartsheet
					image Smartsheet, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f1187ee272c879c6c6a_6172479a373080b8a32d7f45_smartsheet.svg'
			listitem
				link Dialpad Dialpad Sync Dialpad contacts, call logs, and SMS logs to your databases, data warehouses, spreadsheets, and business systems. Or enrich Dialpad contacts from any source or API endpoint., url='https://www.polytomic.com/integrations/dialpad'
					StaticText Dialpad
					image Dialpad, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0f08141a49b9899155_61b2525c47904dc3792920de_dialpad.svg'
			listitem
				link MS SQL Server MS SQL Server Sync any data from Microsoft SQL Server to other databases, data warehouses, business apps, spreadsheets, or webhooks. Or, go the other way and sync any data into Microsoft SQL Server., url='https://www.polytomic.com/integrations/microsoft-sql-server'
					StaticText MS SQL Server
					image MS SQL Server, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f109cf5df8d4a0651b7_62686bf8717c31af93d3a58e_microsoft-sql-server-logo-vector.svg'
			listitem
				link Metabase Metabase Sync any of your Metabase data to business systems, spreadsheets, or databases., url='https://www.polytomic.com/integrations/metabase'
					StaticText Metabase
					image Metabase, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f10e9200a4c28b2dcd3_627d2fdae80f2121d18af218_metabase.svg'
			listitem
				link Looker Looker Sync any of your Looker data to business systems, spreadsheets, or other databases., url='https://www.polytomic.com/integrations/looker'
					StaticText Looker
					image Looker, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f108cf150e1c07ccf7f_627d312316c4e66abed6c17d_looker.svg'
			listitem
				link Amazon S3 Amazon S3 Sync data from your business apps, spreadsheets, APIs, data warehouses, and databases to Amazon S3., url='https://www.polytomic.com/integrations/amazon-s3'
					StaticText Amazon S3
					image Amazon S3, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0db8d28d69effb657e_629e86910a1e164360c54804_Amazon-S3-Logo.svg'
			listitem
				link Azure Blob Storage Azure Blob Storage Sync data from your business apps, spreadsheets, APIs, data warehouses, and databases to Azure Blob Storage., url='https://www.polytomic.com/integrations/azure-blob-storage'
					StaticText Azure Blob Storage
					image Azure Blob Storage, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f0d20e29ee46c76aaaa_62b0ce3b32d69747939fd4dc_azure-blog-storage.svg'
			listitem
				link Google Cloud Storage Google Cloud Storage Sync data from your business apps, spreadsheets, APIs, data warehouses, and databases to Google Cloud Storage., url='https://www.polytomic.com/integrations/google-cloud-storage'
					StaticText Google Cloud Storage
					image Google Cloud Storage, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/63d1d39c25f4c91fd7b7f9b7_Google_Storage-Logo.wine_NniLldt.svg'
			listitem
				link Kustomer Kustomer Sync into Customers and Companies from databases, data warehouses, spreadsheets, business systems, or even API endpoints. Or go in the other direction and sync your Kustomer data anywhere you want., url='https://www.polytomic.com/integrations/kustomer'
					StaticText Kustomer
					image Kustomer, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f101b125a1d502ad859_62b37a70cf211531f2e1e3ac_kustomer.svg'
			listitem
				link ShipBob ShipBob Sync your ShipBob data into databases, data warehouses, CRMs like Salesforce and Zendesk, or spreadsheets., url='https://www.polytomic.com/integrations/shipbob'
					StaticText ShipBob
					image ShipBob, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f119cf5dfdc9d0651bc_62ed7d618ef108be5f1a17fa_shipbob.svg'
			listitem
				link Jira Jira Sync your Jira issues, projects, and users to your data warehouse to run custom analysis and build custom dashboards., url='https://www.polytomic.com/integrations/jira'
					StaticText Jira
					image Jira, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/632a1f109cf5df371e0651b0_6318ebd8e1bc93ed5d9be441_jira.svg'
			listitem
				link NetSuite NetSuite Sync to Netsuite from your databases, spreadsheets, business systems, or APIs. Or, sync from Netsuite into your data warehouses or cloud storage systems like S3., url='https://www.polytomic.com/integrations/netsuite'
					StaticText NetSuite
					image NetSuite, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/64baefabc48ed652248af413_netsuite.svg'
			listitem
				link Microsoft Ads (Bing Ads) Microsoft Ads (Bing Ads) Sync campaign data from Microsoft Ads (formerly Bing Ads) to your data warehouse or cloud storage systems like S3., url='https://www.polytomic.com/integrations/microsoft-ads-bing-ads'
					StaticText Microsoft Ads (Bing Ads)
					image Microsoft Ads (Bing Ads), url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/633cb26735b4158f11cd86fd_6333fbdfcebc56721fa44e2b_Microsoft_logo.svg'
			listitem
				link FullStory FullStory Sync your FullStory events to your data warehouse or cloud storage buckets., url='https://www.polytomic.com/integrations/fullstory'
					StaticText FullStory
					image FullStory, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/633cb267d0684b3a411b642c_6337be40a918c20d541cff4c_fullstory.svg'
			listitem
				link Google Cloud SQL Google Cloud SQL Sync data from your Google Cloud SQL databases into your data warehouse, business applications, spreadsheets, or webhooks., url='https://www.polytomic.com/integrations/google-cloud-sql'
					StaticText Google Cloud SQL
					image Google Cloud SQL, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/6344573f3382a62e7d455bb7_google-cloud-sql.svg'
			listitem
				link Lob Lob Create postcards in Lob with data from your databases, spreadsheets, CRMs, or APIs., url='https://www.polytomic.com/integrations/lob'
					StaticText Lob
					image Lob, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/6365608a477f103470d71191_633cb1bd0191478039f88a45_lob-logo.svg'
			listitem
				link Slack Slack Sync channels, users, teams, and other data from your Slack workspace into your data warehouse or cloud storage buckets., url='https://www.polytomic.com/integrations/slack'
					StaticText Slack
					image Slack, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/63cad11f8cdf804c6e97e717_Slack_icon_2019.svg-p-500.webp'
			listitem
				link LinkedIn Ads LinkedIn Ads Sync campaign data to your data warehouse., url='https://www.polytomic.com/integrations/linkedin-ads'
					StaticText LinkedIn Ads
					image LinkedIn Ads, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/63db28210318291d25754042_LinkedIn%20Icon.png'
			listitem
				link Quickbooks Quickbooks Sync customer billing data and internal expense records to your CRM or data warehouse, or sync to Quickbooks from your databases, data warehouses, CRMs, and spreadsheets., url='https://www.polytomic.com/integrations/quickbooks'
					StaticText Quickbooks
					image Quickbooks, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/63db25093a20fd59bab4bb8b_quickbooks-2.svg'
			listitem
				link Salesloft Salesloft Sync to Salesloft accounts, people, and cadences from your data warehouse, databases, SaaS tools, spreadsheets, and APIs. Or go the other way: sync any data from Salesloft to your data warehouses, databases, SaaS tools, spreadsheets, and APIs., url='https://www.polytomic.com/integrations/salesloft'
					StaticText Salesloft
					image Salesloft, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/66a148001037ec6a19d45ae9_salesloft.svg'
			listitem
				link GitHub GitHub Sync GitHub activity to your data warehouse., url='https://www.polytomic.com/integrations/github'
					StaticText GitHub
					image GitHub, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/63db27b528204d84a50bd60d_GitHub%20Icon.png'
			listitem
				link AdRoll AdRoll Sync Adroll campaigns to your data warehouse., url='https://www.polytomic.com/integrations/adroll'
					StaticText AdRoll
					image AdRoll, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/63db26a162e0107d1f09a194_AdRoll%20Icon.png'
			listitem
				link Google Analytics Google Analytics Sync your Google Analytics events to your data warehouse., url='https://www.polytomic.com/integrations/google-analytics'
					StaticText Google Analytics
					image Google Analytics, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/63db26187b0547b9a1fba63c_Google%20Analytics%20Icon.svg'
			listitem
				link Outreach Outreach Sync any data from Outreach to your data warehouse, CRMs, or spreadsheets. Or go the other way: sync to Outreach from any of your systems., url='https://www.polytomic.com/integrations/outreach'
					StaticText Outreach
					image Outreach, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/63db259b3f1f229bf6913905_Outreach%20Icon.min.svg'
			listitem
				link Ascend Ascend Sync you carrier, program, payment, and organization data to your data warehouse and cloud storage systems., url='https://www.polytomic.com/integrations/ascend'
					StaticText Ascend
					image Ascend, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/642c721c5b0c0527a58a0da2_ascend.svg'
			listitem
				link Statsig Statsig Sync all data about your gates, segments, experiments, and users to your data warehouse and cloud storage systems., url='https://www.polytomic.com/integrations/statsig'
					StaticText Statsig
					image Statsig, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/642c799bb2c5179386c28fda_statsig.svg'
			listitem
				link Delighted Delighted Sync your survey data to your other tools, data warehouses, or cloud storage systems., url='https://www.polytomic.com/integrations/delighted'
					StaticText Delighted
					image Delighted, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/642c7abe83d8f15b094b1b17_delighted.svg'
			listitem
				link Linear Linear Sync your linear issue and project data to your data warehouse and cloud storage systems., url='https://www.polytomic.com/integrations/linear'
					StaticText Linear
					image Linear, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/642c7be83a4173a380e9f27b_linear.svg'
			listitem
				link Asana Asana Sync all data from your Asana workspace into your data warehouse and cloud storage systems., url='https://www.polytomic.com/integrations/asana'
					StaticText Asana
					image Asana, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/642c7cc5935f9816afae02f6_asana.svg'
			listitem
				link Shopify Shopify Sync your Shopify data to your data warehouse and cloud storage systems., url='https://www.polytomic.com/integrations/shopify'
					StaticText Shopify
					image Shopify, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/643422890a90559cf55007b5_shopify.svg'
			listitem
				link Reply Reply Sync contact data to and from Reply and your databases, data warehouses, business systems, spreadsheets, and APIs., url='https://www.polytomic.com/integrations/reply'
					StaticText Reply
					image Reply, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/6476c344b16fc306be6f37f5_reply.svg'
			listitem
				link DynamoDB DynamoDB Sync from DynamoDB to your data warehouse, business applications, spreadsheets, and webhooks., url='https://www.polytomic.com/integrations/dynamodb'
					StaticText DynamoDB
					image DynamoDB, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/64c9ca63ac0eced09152a9ce_dynamodb.svg'
			listitem
				link Dittofeed Dittofeed Sync users and events to Dittofeed from your databases, data warehouses, SaaS tools, spreadsheets, and APIs., url='https://www.polytomic.com/integrations/dittofeed'
					StaticText Dittofeed
					image Dittofeed, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/6520becdbd0adf9f1a9395b3_dittofeed.svg'
			listitem
				link AWS OpenSearch AWS OpenSearch Sync data from your OpenSearch indices into your data warehouses, databases, and cloud storage systems like S3., url='https://www.polytomic.com/integrations/aws-opensearch'
					StaticText AWS OpenSearch
					image AWS OpenSearch, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/655b84657e55a82029d7be94_aws-opensearch.svg'
			listitem
				link Unbounce Unbounce Sync your Unbound pages and leads data to your data warehouse, databases, and cloud storage systems., url='https://www.polytomic.com/integrations/unbounce'
					StaticText Unbounce
					image Unbounce, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/656a493eecfb394aeff53449_unbounce-icon-svgrepo-com.svg'
			listitem
				link Zendesk Chat Zendesk Chat Sync your chat data from Zendesk Chat to your data warehouses, databases, and cloud storage systems like S3., url='https://www.polytomic.com/integrations/zendesk-chat'
					StaticText Zendesk Chat
					image Zendesk Chat, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/65bacaa7c0335dce7f6ea608_zendeskchat.svg'
			listitem
				link Heap Heap Update user properties in Heap with data from your database, data warehouse, SaaS tools, APIs, and spreadsheets., url='https://www.polytomic.com/integrations/heap'
					StaticText Heap
					image Heap, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/65cf9b8ac8ecc3b02a126161_heap.svg'
			listitem
				link Ironclad Ironclad Sync workflow, record, and user data into your data warehouse and cloud storage systems., url='https://www.polytomic.com/integrations/ironclad'
					StaticText Ironclad
					image Ironclad, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/65d3bec9f5ee4e2034631aa4_ironclad.svg'
			listitem
				link Gong Gong Sync your Gong calls, scorecards, transcripts, workspaces, and more to your databases, data warehouses, and cloud storage systems like S3., url='https://www.polytomic.com/integrations/gong'
					StaticText Gong
					image Gong, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/65ee87100a440ab8f8f0e42f_gong.svg'
			listitem
				link Attio Attio Sync from your data warehouse, database, cloud apps, spreadsheets, or APIs into Attio's People, Companies, Deals, and all custom objects. Or sync in the other direction: from Attio to your data warehouse, databases, cloud apps, spreadsheets, and APIs., url='https://www.polytomic.com/integrations/attio'
					StaticText Attio
					image Attio, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/661edf82424fb51837fdb0e5_attio.svg'
			listitem
				link SFTP SFTP Sync CSV or JSON files from SFTP servers into your data warehouses, databases, cloud storage buckets, and spreadsheets., url='https://www.polytomic.com/integrations/sftp'
					StaticText SFTP
					image SFTP, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/663d500ea0425f0a957cb68a_sftp.svg'
			listitem
				link ZoomInfo ZoomInfo Enrich any people or companies in your data warehouses, databases, business systems, spreadsheets, and API sources with data from ZoomInfo., url='https://www.polytomic.com/integrations/zoominfo'
					StaticText ZoomInfo
					image ZoomInfo, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/663ff035a6fe9a26f9a2203e_zoominfo.svg'
			listitem
				link Scamalytics Scamalytics Enrich any IP addresses in your data warehouses, databases, business systems, spreadsheets, and API sources with fraud scores from Scamalytics., url='https://www.polytomic.com/integrations/scamalytics'
					StaticText Scamalytics
					image Scamalytics, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/663ff0e2dfc171fd5b3837ec_scamalytics.svg'
			listitem
				link Apollo.io Apollo.io Enrich any people or companies in your data warehouses, databases, business systems, spreadsheets, and API sources with data from Apollo.io. Also, add contacts from any of your data sources to Apollo sequences., url='https://www.polytomic.com/integrations/apollo-io'
					StaticText Apollo.io
					image Apollo.io, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/663fef69fc657deb1e2a96ee_apollo.svg'
			listitem
				link PredictLeads PredictLeads Enrich any people or companies in your data warehouses, databases, business systems, spreadsheets, and API sources with data from PredictLeads., url='https://www.polytomic.com/integrations/predictleads'
					StaticText PredictLeads
					image PredictLeads, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/663ff08585de55ee13c7c4ae_predictleads.svg'
			listitem
				link MailerCheck MailerCheck Enrich any email addresses in your data warehouses, databases, business systems, spreadsheets, and API sources with fraud scores from MailerCheck., url='https://www.polytomic.com/integrations/mailercheck'
					StaticText MailerCheck
					image MailerCheck, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/663ff174fc0777a7774edff3_mailercheck.svg'
			listitem
				link PostHog PostHog Sync PostHog events and people to your data warehouse, databases, and cloud storage buckets like S3., url='https://www.polytomic.com/integrations/posthog'
					StaticText PostHog
					image PostHog, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/6686014f48d875dbe8553452_posthog-logomark.svg'
			listitem
				link Parquet Parquet Sync from your data warehouses, SaaS applications, databases, spreadsheets, and APIs to Parquet files on Amazon S3, Google Cloud Storage, or Azure Blob Storage. Or go the other way: sync from your Parquet files to your SaaS applications, data warehouses, databases, spreadsheets, and webhooks., url='https://www.polytomic.com/integrations/parquet'
					StaticText Parquet
					image Parquet, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/6691b25f212a51279cb0441d_parquet.svg'
			listitem
				link Mixpanel Mixpanel Sync Mixpanel events to your data warehouse and cloud storage systems., url='https://www.polytomic.com/integrations/mixpanel'
					StaticText Mixpanel
					image Mixpanel, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/6691ace41d5a807ca72fb2ab_mixpanel.svg'
			listitem
				link Clari Copilot Clari Copilot Sync Clari Copilot call logs, transcripts, scorecards, and user data to your data warehouse, databases, SaaS applications, spreadsheets, and APIs., url='https://www.polytomic.com/integrations/clari-copilot'
					StaticText Clari Copilot
					image Clari Copilot, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/669829001e9d519a7c2a2b03_clari.svg'
			listitem
				link Heron Data Heron Data Sync end user data, bank statements, and profit and loss reports from Heron Data to your data warehouse, databases, cloud storage, SaaS applications like Salesforce, spreadsheets, and APIs., url='https://www.polytomic.com/integrations/heron-data'
					StaticText Heron Data
					image Heron Data, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/66a9701de50ac80899fba4c9_herondata.svg'
			listitem
				link Strackr Strackr Sync all financial and transactional reports from Stackr to your data warehouses, databases, SaaS tools, spreadsheets, and APIs., url='https://www.polytomic.com/integrations/strackr'
					StaticText Strackr
					image Strackr, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/66b15d4f6e37d1b7b6616046_strackr.svg'
			listitem
				link Intellimize Intellimize Sync conversion events to Intellimize from your data warehouse, databases, SaaS tools, spreadsheets, and APIs., url='https://www.polytomic.com/integrations/intellimize'
					StaticText Intellimize
					image Intellimize, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/66bd3f424557122fa697e107_intellimize.svg'
			listitem
				link Yotpo Yotpo Sync reviews, questions, and answers from Yotpo to your data warehouses, databases, SaaS tools, spreadsheets, webhooks, and cloud storage systems., url='https://www.polytomic.com/integrations/yotpo'
					StaticText Yotpo
					image Yotpo, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/66dcba8f8058bad06f61b48d_yotpo.svg'
			listitem
				link Smartlead.ai Smartlead.ai Sync your campaigns, leads, and message histories to your data warehouses, databases, SaaS tools, spreadsheets, and cloud storage like S3. Or go the other way and add leads from any of your systems to your Smartlead.ai campaigns., url='https://www.polytomic.com/integrations/smartlead-ai'
					StaticText Smartlead.ai
					image Smartlead.ai, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/67009ca4ff0f2f30351bdd0e_smartlead.svg'
			listitem
				link Dropbox Dropbox Sync from CSVs and JSON files on Dropbox to your databases, data warehouses, SaaS applications, spreadsheets, and webhooks., url='https://www.polytomic.com/integrations/dropbox'
					StaticText Dropbox
					image Dropbox, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/6732940497aa9621cba99eef_dropbox.svg'
			listitem
				link monday.com monday.com Sync data from your monday.com boards to your CRMs, data warehouses, databases, spreadsheets, and cloud storage like S3. Or, go the other way and sync from all these systems to your monday.com boards., url='https://www.polytomic.com/integrations/monday-com'
					StaticText monday.com
					image monday.com, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/6733adb8b3baab378586b152_monday.svg'
			listitem
				link Productboard Productboard Sync to Productboard users and companies from your data warehouses, databases, SaaS tools, spreadsheets, and APIs. Or, go the other way and sync from Productboard to your databases, data warehouses, SaaS tools, spreadsheets, and webhooks., url='https://www.polytomic.com/integrations/productboard'
					StaticText Productboard
					image Productboard, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/674de6d2fbc4bed5e8d11ae0_productboard.svg'
			listitem
				link App Store Connect App Store Connect Sync your App Store Connect analytics and sales reports to your data warehouses, databases, and cloud storage buckets like S3., url='https://www.polytomic.com/integrations/app-store-connect'
					StaticText App Store Connect
					image App Store Connect, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/675cb949ac550d9f7f02f0ae_appstoreconnect.svg'
			listitem
				link Towbook Towbook Sync your Towbook reports to your data warehouses, databases, and cloud storage buckets like S3., url='https://www.polytomic.com/integrations/towbook'
					StaticText Towbook
					image Towbook, url='https://cdn.prod.website-files.com/62eb5e6ae1078765d758227f/675cbae915861f50c5c96fd6_towbook.svg'
		heading Get started
		StaticText See a live demo.
		link Book demo, url='https://www.polytomic.com/book-demo'
		StaticText or
		link Start free trial, url='https://www.polytomic.com/start-free-trial'
	contentinfo
		StaticText Product
		link Overview, url='https://www.polytomic.com/overview'
		link Pricing, url='https://www.polytomic.com/pricing'
		link Integrations, url='https://www.polytomic.com/integrations'
		StaticText Use cases
		link Data Teams, url='https://www.polytomic.com/data-teams'
		link RevOps, url='https://www.polytomic.com/rev-ops'
		link Marketing, url='https://www.polytomic.com/marketing-teams'
		link Support, url='https://www.polytomic.com/support-teams'
		link API Endpoints, url='https://www.polytomic.com/api-sources'
		StaticText Resources
		link Documentation, url='https://docs.polytomic.com/'
		link Blog, url='https://www.polytomic.com/blog'
		link Ebooks, url='https://www.polytomic.com/ebooks'
		link Case studies, url='https://www.polytomic.com/customers'
		link Security, url='https://www.polytomic.com/security'
		StaticText Get in touch
		link Contact us, url='https://www.polytomic.com/contact'
		link, url='https://www.linkedin.com/company/polytomic/'
			image
		link, url='https://twitter.com/polytomic'
			image
		StaticText Copyright © 2024 Polytomic Inc. All rights reserved.
		StaticText ·
		link Terms of Service, url='https://www.polytomic.com/terms'
		StaticText ·
		link Privacy Policy, url='https://www.polytomic.com/privacy-policy'
		link, url='https://www.polytomic.com/'
			image
	[1063] button Open Intercom Messenger, center=(1876,1036)
		image
		image
```
</details>

**Reasoning for action:** I needed to explore the Integrations offered by Polytomic to fully understand how their solutions can address my organization's data needs. Clicking on the Integrations link is the final step in fulfilling the user's story, which specifies that I should view the content related to products, use cases, and integrations. By taking this action, it allows me to gather specific details about how Polytomic can help with data synchronization solutions.

**Action:** click(93) # Click on the Integrations link to explore the various integrations offered by Polytomic.

**Change Description:** After clicking the Integrations link, the browser changed to display the Integrations page of Polytomic, focusing on features for syncing data with various platforms, including a newly introduced heading, several integration links, and updated static text describing integration capabilities.

**Screenshot before:****Screenshot after:**---


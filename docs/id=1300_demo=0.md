# Task

**Explore IOMETE Pricing Options**

As a potential customer seeking a data lakehouse solution,
I explore IOMETE's pricing options and request a quote,
so that I can evaluate if their services fit within my budget and needs.

**Success definition:** Given I am on the IOMETE homepage
When I click on the Pricing link
Then I should see detailed pricing information for IOMETE services including on-premise, private, and public cloud models, and when I click on the Get a Quote link, I should be navigated to a scheduling interface on Calendly to select a date and time for a discovery call.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://iomete.com/

https://iomete.com/

**Content (before/after):** 

```
RootWebArea IOMETE | The Self-Hosted Data Lakehouse Platform, focused, url='https://iomete.com/'
	banner
		[39] link home, center=(436,34), url='https://iomete.com/'
			image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/625d83b137c1b3783d4c8baf_iomete-logo-white-no-padding.d0313f34.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[43] button Product, center=(596,34), expanded=False, hasPopup='menu'
			[61] link Pricing, center=(689,34), url='https://iomete.com/pricing'
			[63] button Use Cases, center=(793,34), expanded=False, hasPopup='menu'
			[96] button Resources, center=(920,34), expanded=False, hasPopup='menu'
			[120] button Company, center=(1044,34), expanded=False, hasPopup='menu'
		[142] link Book a demo, center=(1485,34), url='https://calendly.com/iomete/iomete-discovery-call'
	strong
		StaticText The smart alternative to Snowflake, Databricks and Cloudera.
	heading The Self-Hosted Data Lakehouse Platform
	StaticText Smart users worldwide are saying yes to IOMETE and no to data breaches and overpriced SAAS schemes designed to lock you in. Runs on premises and on public and private clouds.
	[153] link Book a Demo, center=(446,378), url='https://calendly.com/iomete/iomete-discovery-call'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/659ca9dc2db87ad28cc1151e_arrow-right-line.svg'
	[156] link Learn More, center=(596,378), url='https://iomete.com/#features-section'
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a29426aefd9be930bc5112_Lakehouses.svg'
	heading Connect to any source
	StaticText Wide variety connections and integrations.
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a289399132d6f677d6ed93_Redash%20Logo.svg'
	StaticText Redash
	StaticText Business Intelligence
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939d84d81bc48579f53_Airflow%20Logo.svg'
	StaticText Apache Airflow
	StaticText Automated Workflows
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a2893bdbd7f345933eab7c_Powerbi%20Logo.svg'
	StaticText Power BI
	StaticText Business Intelligence
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a289399132d6f677d6ed93_Redash%20Logo.svg'
	StaticText Redash
	StaticText Business Intelligence
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939d84d81bc48579f53_Airflow%20Logo.svg'
	StaticText Apache Airflow
	StaticText Automated Workflows
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a2893bdbd7f345933eab7c_Powerbi%20Logo.svg'
	StaticText Power BI
	StaticText Business Intelligence
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939a9e1bd3f0c45d7d9_Prefect%20Logo.svg'
	StaticText Prefect
	StaticText Orchestration platform
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939dc1efbe190070492_dbt%20Logo.svg'
	StaticText dbt
	StaticText Data transformations
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939322cb1690df915cf_Tableau%20Logo.svg'
	StaticText Tableau
	StaticText Business Intelligence
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939a9e1bd3f0c45d7d9_Prefect%20Logo.svg'
	StaticText Prefect
	StaticText Orchestration platform
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939dc1efbe190070492_dbt%20Logo.svg'
	StaticText dbt
	StaticText Data transformations
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939322cb1690df915cf_Tableau%20Logo.svg'
	StaticText Tableau
	StaticText Business Intelligence
	main
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/64824708f424f64d0de83c24_iceberg-55.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641c7734ecb40dcc40710d5f_spark.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641c8c41849aad152eed6215_Line-decoration.svg'
		StaticText A modern and open lakehouse
		paragraph
			StaticText IOMETE features the Apache Iceberg table format. Get access to ACID transactions, time travel, snapshots, schema evolution, data versioning, concurrency control, metadata management, and partitioning. Powered by the Apache Spark engine, IOMETE is fast, versatile, and scalable.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6477b9b1b8a5a55dc0773844_cloud_new.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6477b98ddf2631cdcd225391_azure.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6477b99b27cf7a136a4e8353_google%20cloud.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6477b9cfdf2631cdcd22adc2_priv_cloud.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6477c00bcda083d6ecc679d8_Group%20196.svg'
		StaticText Securely deployed where your data lives
		paragraph
			StaticText IOMETE can be deployed on-premises in your data centers, in the cloud or in a hybrid configuration. In all cases the data does not leave your trust perimeter, guaranteeing maximum data security and ownership.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641c7747dff483620728f011_graph_others.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641c774fdca2276632be2124_graph_iomete.svg'
		StaticText Disruptive, transparent pricing
		paragraph
			StaticText Cost matters. No surprise bills. No lock-ins.
		list
			listitem
			listitem
		link Book a demo, url='https://calendly.com/iomete/iomete-discovery-call'
		heading Sync. Prepare. Consume.
		StaticText Unified data for analytics, ML and AI made easy.
		StaticText SYNC
		heading Sync from a wide range of compatible data sources
		StaticText or use query federation to unify your data for analytical and ML/AI workloads.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/658da668fe1e07b8f6c549af_Sync%20image.png'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641d879f7ed9161ad7e62621_Icon_change.svg'
		StaticText Sync or ingest from a wide range of compatible data sources
		paragraph
			StaticText Use built-in serverless Spark jobs to sync data from your operational database and other data sources into a lakehouse or use a third party ELT tool to ingest your data.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641d879f16414006c18a61e3_Icon_braces.svg'
		StaticText Access your data with query federation
		paragraph
			StaticText IOMETE allows you to query disparate datasources in the same system with the same SQL. Federated queries can access your object storage, relational databases, No-SQL system, all in the same query.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641d879f7ed916ac8de62628_Icon_airplay.svg'
		StaticText Enjoy the benefits of near real-time streaming
		paragraph
			StaticText IOMETE's powerful Spark Job Cluster makes it easy to analyze realtime streaming data. With IOMETE, users can ingest and process large volumes of realtime data from a variety of sources - including IoT devices, social media feeds and financial transactions.
		StaticText PREPARE
		heading Transform, clean and organize your data with SQL, Spark and DBT.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a29426bd0b724104a9ab0e_SQL%20Editor.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da4159205bca769fe9cea_Icon-graph.svg'
		StaticText Transform your data at any scale
		paragraph
			StaticText Built-in Apache Spark can handle large datasets by dividing them into smaller partitions and processing them in parallel in clusters. This makes it highly scalable, fast and suitable for up to petabytes datasets. Apache Spark is flexible and handles SQL, Java, Scala, and Python. IOMETE offers a seamless integration with DBT.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da4152a7f8bcb2d403571_Icon-cube.svg'
		StaticText Run ad-hoc analysis with the SQL editor
		paragraph
			StaticText The built-in SQL editor provides a toolkit to make it easy to write SQL queries with features such as search, autocomplete and schema explorer.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a233e44621b6acf84f3d77_Data%20Security.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da415ed6184f4eb290772_Icon_db.svg'
		StaticText Organize your data with the built-in data catalog
		paragraph
			StaticText The IOMETE data catalog provides Google-like search, index and discovery for your data. It also allows you to document the data you own so you can stay organized.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da415ed61844c5e290773_Icon-shield.svg'
		StaticText Manage data access and become compliant with data regulations
		paragraph
			StaticText Leverage advanced data access controls to keep your data secure. IOMETE allows you to manage access on person or team level, as well as on table, row and column level. This makes it easy to become and stay compliant with regulations such as SOC2, HIPAA and GDPR.
		StaticText CONSUME
		heading Run blazing-fast analytics, ML and AI models
		StaticText and enjoy the benefits of having access to relevant, high-quality data for analysis and decision making by men and machines.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/658da68d61cdc35434cc14d2_Animation3-convert.png'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da4151bf6469ab4314d4f_Icon-chain.svg'
		StaticText Run blazing-fast analytics on quality data
		paragraph
			StaticText It’s very easy to connect IOMETE to your favorite BI tool - including Tableau, PowerBI, Metabase and Apache Superset - and enjoy the benefits of organized, high-quality data for analytical and dashboarding purposes.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da415cc916a2a345516a9_Icon-merge.svg'
		StaticText ML and AI made easy
		paragraph
			StaticText With features such as notebook service, training ML jobs on the Spark cluster and unlimited time-travel on the data lake, IOMETE makes it easy to run your ML and AI models whether it is on premise or in the cloud.
		heading Explore IOMETE use cases
		heading On premise and hybrid deployment options
		StaticText Explore how IOMETE can be securely deployed in your trust perimeter.
		generic
			group 1 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641ca6716dd0566e41f69dd3_home%201.svg'
				StaticText IOMETE on premise deployment
				StaticText Enjoy cloud-like performance with the benefits of on premise.
				link Learn More, url='https://iomete.com/cases/iomete-on-premise'
			group 2 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641ca6716dd0566e41f69dd3_home%201.svg'
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641ca668be2a98804e3fc1ae_cloud-lightning%201.svg'
				StaticText IOMETE hybrid deployment
				StaticText Learn how to combine on premise and cloud with one platform to rule them all.
				link Learn More, url='https://iomete.com/cases/iomete-hybrid-deployment'
			group 3 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641ca668be2a98804e3fc1ae_cloud-lightning%201.svg'
				StaticText IOMETE private cloud deployment
				StaticText Learn the benefits of running IOMETE in your private cloud.
				link Learn More, url='https://iomete.com/cases/iomete-on-private-cloud'
		generic, atomic
		heading Cloud-only deployment options
		StaticText You want to know a little secret? We started out as a cloud-only data lakehouse...
		generic
			group 1 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641ca4f77d47842d589d34b7_aws-2.svg'
				StaticText IOMETE on AWS
				StaticText Learn about the benefits of running IOMETE on AWS.
				link Learn More, url='https://iomete.com/cases/iomete-on-aws'
			group 2 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/650123c1a9a4e2bd02806040_Azure.svg'
				StaticText IOMETE on Azure
				StaticText Learn about the benefits of running IOMETE on Azure.
				link Learn More, url='https://iomete.com/cases/iomete-on-azure'
			group 3 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/650123ea7d1d81c84f3d2b96_google%20cloud%20logo.svg'
				StaticText IOMETE on Google Cloud
				StaticText Learn about the benefits of running IOMETE on Google Cloud.
				link Learn More, url='https://iomete.com/cases/iomete-on-google-cloud'
		generic, atomic
	heading Top-Tier Data Protection Standards
	StaticText We adhere to the highest standards of security and privacy.
	StaticText Proudly displaying our SOC 2, GDPR, and HIPAA certifications, we ensure that your information is handled in compliance with data regulations.
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a0850d7a98eaf45a8c5db9_soc2.svg'
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a085264ac47a65082eeba0_gdpr.svg'
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a0851bd018b401a02075ec_hipaa.svg'
	heading Ready? Try it today.
	StaticText Start with a Free Community version to see what IOMETE can do.
	StaticText Interested in Enterprise? Book a call with us!
	link Book a Demo, url='https://calendly.com/iomete/iomete-discovery-call'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/659eee191c3f7541469bc044_arrow-right-line-2.svg'
	link, url='https://iomete.com/'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/625d83b137c1b3783d4c8baf_iomete-logo-white-no-padding.d0313f34.svg'
	link IOMETE | Linkedin, url='https://www.linkedin.com/company/iomete'
		image IOMETE | Linkedin, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b1458f5642a3ba950f3bc1_linkedin-white.svg'
	link IOMETE | Github, url='https://github.com/iomete/'
		image IOMETE | Github, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b145d7b08fe6adee126913_github-white.svg'
	link IOMETE | Twitter, url='https://twitter.com/iometedata/'
		image IOMETE | Twitter, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b14595b6e174c604c778c6_twitter-white.svg'
	link IOMETE | Youtube, url='https://www.youtube.com/@iomete'
		image IOMETE | Youtube, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b1459fa105bd225de796b2_youtube-white.svg'
	StaticText 1049 El Monte Avenue
	StaticText Mountain View, CA 94040
	StaticText USA
	StaticText PRODUCT
	link Pricing, url='https://iomete.com/pricing'
	link Product Overview, url='https://iomete.com/#process'
	link Product Features, url='https://iomete.com/pricing#comparison'
	link Serverless Lakehouse, url='https://iomete.com/lakehouse'
	link SQL Editor, url='https://iomete.com/sql-editor'
	link Apache Iceberg, url='https://iomete.com/iceberg'
	StaticText SOLUTIONS
	link On Premise, url='https://iomete.com/cases/iomete-on-premise'
	link Hybrid Deployment, url='https://iomete.com/cases/iomete-hybrid-deployment'
	link Private Cloud, url='https://iomete.com/cases/iomete-on-private-cloud'
	link AWS, url='https://iomete.com/cases/iomete-on-aws'
	link Azure, url='https://iomete.com/cases/iomete-on-azure'
	link Google Cloud, url='https://iomete.com/cases/iomete-on-google-cloud'
	StaticText USE CASES
	link Financial Institutions, url='https://iomete.com/cases/iomete-for-financial-institutions'
	link Healthcare, url='https://iomete.com/cases/iomete-for-healthcare'
	link Public Sector, url='https://iomete.com/cases/iomete-for-public-sector'
	link Data Resellers, url='https://iomete.com/cases/iomete-for-data-resellers'
	StaticText RESOURCES
	link Documentation, url='https://iomete.com/resources'
	link Support, url='https://iomete.com/resources/getting-started/support'
	link Roadmap, url='https://github.com/orgs/iomete/projects/2'
	link Community, url='https://github.com/iomete'
	link Glossary, url='https://iomete.com/resources/glossary'
	link Blog, url='https://iomete.com/resources/blog'
	StaticText COMPANY
	link About Us, url='https://iomete.com/about'
	link The IOMETE Creed, url='https://iomete.com/about#creed'
	link Careers, url='https://iomete.com/about#careers'
	link Investors, url='https://iomete.com/about#investors'
	link Brand Wall, url='https://iomete.com/brand-wall'
	StaticText © 2024 IOMETE Inc. All Rights Reserved
	link Privacy Policy, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/673c9c12209584ad15a76161_IOMETE%20Privacy%20Statement%20-%20Updated%20November%202024.pdf'
	link Terms & Conditions, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/636fa7b771bc737954a0e648_IOMETE%20Terms%20of%20Service.pdf'
	link Cookies Policy, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/673c9c451e9a43448fd257fa_IOMETE%20Cookie%20Policy%20v1.1%20-%20Updated%20November%202024.pdf'
	dialog Cookie consent dialog, modal=False
		dialog Cookie consent dialog, modal=False
			[577] button Close, center=(1898,925), inner_text=×
				StaticText ×
			StaticText This website uses cookies
			StaticText We use essential cookies to make our site work. With your consent, we may also use non-essential cookies to improve user experience and analyze website traffic. For these reasons, we may share your site usage data with our analytics partners. By clicking “Accept,” you agree to our website's cookie use as described in our Cookie Policy.
			[583] link Read more, opens a new window, center=(829,983), inner_text=Read more, url='https://assets-global.website-files.com/625843c6d847c8dca08551d1/655cff76197826253dd715b5_IOMETE%20Cookie%20Policy%20v1.0%20-%20Updated%20November%202023.pdf'
			[587] checkbox PERFORMANCE, center=(62,1018), checked='false', contenteditable=True, type=checkbox
			image
			LabelText
				StaticText PERFORMANCE
			[594] checkbox MARKETING, center=(223,1018), checked='false', contenteditable=True, type=checkbox
			[591] span, center=(137,1018), inner_text=PERFORMANCE
			image
			LabelText
				StaticText MARKETING
			[601] checkbox FUNCTIONALITY, center=(359,1018), checked='false', contenteditable=True, type=checkbox
			[598] span, center=(285,1018), inner_text=MARKETING
			image
			LabelText
				StaticText FUNCTIONALITY
			[606] button SHOW DETAILS, center=(638,1053), inner_text= SHOW DETAILS
				image
			[605] span, center=(436,1018), inner_text=FUNCTIONALITY
			[614] button ACCEPT ALL, center=(1411,992)
			[615] button DECLINE ALL, center=(1709,992)
```
</details>



```
RootWebArea IOMETE | The Self-Hosted Data Lakehouse Platform, focused, url='https://iomete.com/'
	banner
		[39] link home, center=(436,34), url='https://iomete.com/'
			image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/625d83b137c1b3783d4c8baf_iomete-logo-white-no-padding.d0313f34.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[43] button Product, center=(596,34), expanded=False, focused, hasPopup='menu'
			[61] link Pricing, center=(689,34), url='https://iomete.com/pricing'
			[63] button Use Cases, center=(793,34), expanded=False, hasPopup='menu'
			[96] button Resources, center=(920,34), expanded=False, hasPopup='menu'
			[120] button Company, center=(1044,34), expanded=False, hasPopup='menu'
		[142] link Book a demo, center=(1485,34), url='https://calendly.com/iomete/iomete-discovery-call'
	strong
		StaticText The smart alternative to Snowflake, Databricks and Cloudera.
	heading The Self-Hosted Data Lakehouse Platform
	StaticText Smart users worldwide are saying yes to IOMETE and no to data breaches and overpriced SAAS schemes designed to lock you in. Runs on premises and on public and private clouds.
	[153] link Book a Demo, center=(446,378), url='https://calendly.com/iomete/iomete-discovery-call'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/659ca9dc2db87ad28cc1151e_arrow-right-line.svg'
	[156] link Learn More, center=(596,378), url='https://iomete.com/#features-section'
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a29426aefd9be930bc5112_Lakehouses.svg'
	heading Connect to any source
	StaticText Wide variety connections and integrations.
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a289399132d6f677d6ed93_Redash%20Logo.svg'
	StaticText Redash
	StaticText Business Intelligence
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939d84d81bc48579f53_Airflow%20Logo.svg'
	StaticText Apache Airflow
	StaticText Automated Workflows
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a2893bdbd7f345933eab7c_Powerbi%20Logo.svg'
	StaticText Power BI
	StaticText Business Intelligence
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a289399132d6f677d6ed93_Redash%20Logo.svg'
	StaticText Redash
	StaticText Business Intelligence
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939d84d81bc48579f53_Airflow%20Logo.svg'
	StaticText Apache Airflow
	StaticText Automated Workflows
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a2893bdbd7f345933eab7c_Powerbi%20Logo.svg'
	StaticText Power BI
	StaticText Business Intelligence
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939a9e1bd3f0c45d7d9_Prefect%20Logo.svg'
	StaticText Prefect
	StaticText Orchestration platform
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939dc1efbe190070492_dbt%20Logo.svg'
	StaticText dbt
	StaticText Data transformations
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939322cb1690df915cf_Tableau%20Logo.svg'
	StaticText Tableau
	StaticText Business Intelligence
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939a9e1bd3f0c45d7d9_Prefect%20Logo.svg'
	StaticText Prefect
	StaticText Orchestration platform
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939dc1efbe190070492_dbt%20Logo.svg'
	StaticText dbt
	StaticText Data transformations
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939322cb1690df915cf_Tableau%20Logo.svg'
	StaticText Tableau
	StaticText Business Intelligence
	main
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/64824708f424f64d0de83c24_iceberg-55.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641c7734ecb40dcc40710d5f_spark.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641c8c41849aad152eed6215_Line-decoration.svg'
		StaticText A modern and open lakehouse
		paragraph
			StaticText IOMETE features the Apache Iceberg table format. Get access to ACID transactions, time travel, snapshots, schema evolution, data versioning, concurrency control, metadata management, and partitioning. Powered by the Apache Spark engine, IOMETE is fast, versatile, and scalable.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6477b9b1b8a5a55dc0773844_cloud_new.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6477b98ddf2631cdcd225391_azure.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6477b99b27cf7a136a4e8353_google%20cloud.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6477b9cfdf2631cdcd22adc2_priv_cloud.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6477c00bcda083d6ecc679d8_Group%20196.svg'
		StaticText Securely deployed where your data lives
		paragraph
			StaticText IOMETE can be deployed on-premises in your data centers, in the cloud or in a hybrid configuration. In all cases the data does not leave your trust perimeter, guaranteeing maximum data security and ownership.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641c7747dff483620728f011_graph_others.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641c774fdca2276632be2124_graph_iomete.svg'
		StaticText Disruptive, transparent pricing
		paragraph
			StaticText Cost matters. No surprise bills. No lock-ins.
		list
			listitem
			listitem
		link Book a demo, url='https://calendly.com/iomete/iomete-discovery-call'
		heading Sync. Prepare. Consume.
		StaticText Unified data for analytics, ML and AI made easy.
		StaticText SYNC
		heading Sync from a wide range of compatible data sources
		StaticText or use query federation to unify your data for analytical and ML/AI workloads.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/658da668fe1e07b8f6c549af_Sync%20image.png'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641d879f7ed9161ad7e62621_Icon_change.svg'
		StaticText Sync or ingest from a wide range of compatible data sources
		paragraph
			StaticText Use built-in serverless Spark jobs to sync data from your operational database and other data sources into a lakehouse or use a third party ELT tool to ingest your data.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641d879f16414006c18a61e3_Icon_braces.svg'
		StaticText Access your data with query federation
		paragraph
			StaticText IOMETE allows you to query disparate datasources in the same system with the same SQL. Federated queries can access your object storage, relational databases, No-SQL system, all in the same query.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641d879f7ed916ac8de62628_Icon_airplay.svg'
		StaticText Enjoy the benefits of near real-time streaming
		paragraph
			StaticText IOMETE's powerful Spark Job Cluster makes it easy to analyze realtime streaming data. With IOMETE, users can ingest and process large volumes of realtime data from a variety of sources - including IoT devices, social media feeds and financial transactions.
		StaticText PREPARE
		heading Transform, clean and organize your data with SQL, Spark and DBT.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a29426bd0b724104a9ab0e_SQL%20Editor.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da4159205bca769fe9cea_Icon-graph.svg'
		StaticText Transform your data at any scale
		paragraph
			StaticText Built-in Apache Spark can handle large datasets by dividing them into smaller partitions and processing them in parallel in clusters. This makes it highly scalable, fast and suitable for up to petabytes datasets. Apache Spark is flexible and handles SQL, Java, Scala, and Python. IOMETE offers a seamless integration with DBT.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da4152a7f8bcb2d403571_Icon-cube.svg'
		StaticText Run ad-hoc analysis with the SQL editor
		paragraph
			StaticText The built-in SQL editor provides a toolkit to make it easy to write SQL queries with features such as search, autocomplete and schema explorer.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a233e44621b6acf84f3d77_Data%20Security.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da415ed6184f4eb290772_Icon_db.svg'
		StaticText Organize your data with the built-in data catalog
		paragraph
			StaticText The IOMETE data catalog provides Google-like search, index and discovery for your data. It also allows you to document the data you own so you can stay organized.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da415ed61844c5e290773_Icon-shield.svg'
		StaticText Manage data access and become compliant with data regulations
		paragraph
			StaticText Leverage advanced data access controls to keep your data secure. IOMETE allows you to manage access on person or team level, as well as on table, row and column level. This makes it easy to become and stay compliant with regulations such as SOC2, HIPAA and GDPR.
		StaticText CONSUME
		heading Run blazing-fast analytics, ML and AI models
		StaticText and enjoy the benefits of having access to relevant, high-quality data for analysis and decision making by men and machines.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/658da68d61cdc35434cc14d2_Animation3-convert.png'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da4151bf6469ab4314d4f_Icon-chain.svg'
		StaticText Run blazing-fast analytics on quality data
		paragraph
			StaticText It’s very easy to connect IOMETE to your favorite BI tool - including Tableau, PowerBI, Metabase and Apache Superset - and enjoy the benefits of organized, high-quality data for analytical and dashboarding purposes.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da415cc916a2a345516a9_Icon-merge.svg'
		StaticText ML and AI made easy
		paragraph
			StaticText With features such as notebook service, training ML jobs on the Spark cluster and unlimited time-travel on the data lake, IOMETE makes it easy to run your ML and AI models whether it is on premise or in the cloud.
		heading Explore IOMETE use cases
		heading On premise and hybrid deployment options
		StaticText Explore how IOMETE can be securely deployed in your trust perimeter.
		generic
			group 1 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641ca6716dd0566e41f69dd3_home%201.svg'
				StaticText IOMETE on premise deployment
				StaticText Enjoy cloud-like performance with the benefits of on premise.
				link Learn More, url='https://iomete.com/cases/iomete-on-premise'
			group 2 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641ca6716dd0566e41f69dd3_home%201.svg'
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641ca668be2a98804e3fc1ae_cloud-lightning%201.svg'
				StaticText IOMETE hybrid deployment
				StaticText Learn how to combine on premise and cloud with one platform to rule them all.
				link Learn More, url='https://iomete.com/cases/iomete-hybrid-deployment'
			group 3 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641ca668be2a98804e3fc1ae_cloud-lightning%201.svg'
				StaticText IOMETE private cloud deployment
				StaticText Learn the benefits of running IOMETE in your private cloud.
				link Learn More, url='https://iomete.com/cases/iomete-on-private-cloud'
		generic, atomic
		heading Cloud-only deployment options
		StaticText You want to know a little secret? We started out as a cloud-only data lakehouse...
		generic
			group 1 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641ca4f77d47842d589d34b7_aws-2.svg'
				StaticText IOMETE on AWS
				StaticText Learn about the benefits of running IOMETE on AWS.
				link Learn More, url='https://iomete.com/cases/iomete-on-aws'
			group 2 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/650123c1a9a4e2bd02806040_Azure.svg'
				StaticText IOMETE on Azure
				StaticText Learn about the benefits of running IOMETE on Azure.
				link Learn More, url='https://iomete.com/cases/iomete-on-azure'
			group 3 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/650123ea7d1d81c84f3d2b96_google%20cloud%20logo.svg'
				StaticText IOMETE on Google Cloud
				StaticText Learn about the benefits of running IOMETE on Google Cloud.
				link Learn More, url='https://iomete.com/cases/iomete-on-google-cloud'
		generic, atomic
	heading Top-Tier Data Protection Standards
	StaticText We adhere to the highest standards of security and privacy.
	StaticText Proudly displaying our SOC 2, GDPR, and HIPAA certifications, we ensure that your information is handled in compliance with data regulations.
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a0850d7a98eaf45a8c5db9_soc2.svg'
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a085264ac47a65082eeba0_gdpr.svg'
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a0851bd018b401a02075ec_hipaa.svg'
	heading Ready? Try it today.
	StaticText Start with a Free Community version to see what IOMETE can do.
	StaticText Interested in Enterprise? Book a call with us!
	link Book a Demo, url='https://calendly.com/iomete/iomete-discovery-call'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/659eee191c3f7541469bc044_arrow-right-line-2.svg'
	link, url='https://iomete.com/'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/625d83b137c1b3783d4c8baf_iomete-logo-white-no-padding.d0313f34.svg'
	link IOMETE | Linkedin, url='https://www.linkedin.com/company/iomete'
		image IOMETE | Linkedin, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b1458f5642a3ba950f3bc1_linkedin-white.svg'
	link IOMETE | Github, url='https://github.com/iomete/'
		image IOMETE | Github, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b145d7b08fe6adee126913_github-white.svg'
	link IOMETE | Twitter, url='https://twitter.com/iometedata/'
		image IOMETE | Twitter, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b14595b6e174c604c778c6_twitter-white.svg'
	link IOMETE | Youtube, url='https://www.youtube.com/@iomete'
		image IOMETE | Youtube, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b1459fa105bd225de796b2_youtube-white.svg'
	StaticText 1049 El Monte Avenue
	StaticText Mountain View, CA 94040
	StaticText USA
	StaticText PRODUCT
	link Pricing, url='https://iomete.com/pricing'
	link Product Overview, url='https://iomete.com/#process'
	link Product Features, url='https://iomete.com/pricing#comparison'
	link Serverless Lakehouse, url='https://iomete.com/lakehouse'
	link SQL Editor, url='https://iomete.com/sql-editor'
	link Apache Iceberg, url='https://iomete.com/iceberg'
	StaticText SOLUTIONS
	link On Premise, url='https://iomete.com/cases/iomete-on-premise'
	link Hybrid Deployment, url='https://iomete.com/cases/iomete-hybrid-deployment'
	link Private Cloud, url='https://iomete.com/cases/iomete-on-private-cloud'
	link AWS, url='https://iomete.com/cases/iomete-on-aws'
	link Azure, url='https://iomete.com/cases/iomete-on-azure'
	link Google Cloud, url='https://iomete.com/cases/iomete-on-google-cloud'
	StaticText USE CASES
	link Financial Institutions, url='https://iomete.com/cases/iomete-for-financial-institutions'
	link Healthcare, url='https://iomete.com/cases/iomete-for-healthcare'
	link Public Sector, url='https://iomete.com/cases/iomete-for-public-sector'
	link Data Resellers, url='https://iomete.com/cases/iomete-for-data-resellers'
	StaticText RESOURCES
	link Documentation, url='https://iomete.com/resources'
	link Support, url='https://iomete.com/resources/getting-started/support'
	link Roadmap, url='https://github.com/orgs/iomete/projects/2'
	link Community, url='https://github.com/iomete'
	link Glossary, url='https://iomete.com/resources/glossary'
	link Blog, url='https://iomete.com/resources/blog'
	StaticText COMPANY
	link About Us, url='https://iomete.com/about'
	link The IOMETE Creed, url='https://iomete.com/about#creed'
	link Careers, url='https://iomete.com/about#careers'
	link Investors, url='https://iomete.com/about#investors'
	link Brand Wall, url='https://iomete.com/brand-wall'
	StaticText © 2024 IOMETE Inc. All Rights Reserved
	link Privacy Policy, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/673c9c12209584ad15a76161_IOMETE%20Privacy%20Statement%20-%20Updated%20November%202024.pdf'
	link Terms & Conditions, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/636fa7b771bc737954a0e648_IOMETE%20Terms%20of%20Service.pdf'
	link Cookies Policy, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/673c9c451e9a43448fd257fa_IOMETE%20Cookie%20Policy%20v1.1%20-%20Updated%20November%202024.pdf'
	dialog Cookie consent dialog, modal=False
		dialog Cookie consent dialog, modal=False
			[577] button Close, center=(1898,925), inner_text=×
				StaticText ×
			StaticText This website uses cookies
			StaticText We use essential cookies to make our site work. With your consent, we may also use non-essential cookies to improve user experience and analyze website traffic. For these reasons, we may share your site usage data with our analytics partners. By clicking “Accept,” you agree to our website's cookie use as described in our Cookie Policy.
			[583] link Read more, opens a new window, center=(829,983), inner_text=Read more, url='https://assets-global.website-files.com/625843c6d847c8dca08551d1/655cff76197826253dd715b5_IOMETE%20Cookie%20Policy%20v1.0%20-%20Updated%20November%202023.pdf'
			[587] checkbox PERFORMANCE, center=(62,1018), checked='false', contenteditable=True, type=checkbox
			image
			LabelText
				StaticText PERFORMANCE
			[594] checkbox MARKETING, center=(223,1018), checked='false', contenteditable=True, type=checkbox
			[591] span, center=(137,1018), inner_text=PERFORMANCE
			image
			LabelText
				StaticText MARKETING
			[601] checkbox FUNCTIONALITY, center=(359,1018), checked='false', contenteditable=True, type=checkbox
			[598] span, center=(285,1018), inner_text=MARKETING
			image
			LabelText
				StaticText FUNCTIONALITY
			[606] button SHOW DETAILS, center=(638,1053), inner_text= SHOW DETAILS
				image
			[605] span, center=(436,1018), inner_text=FUNCTIONALITY
			[614] button ACCEPT ALL, center=(1411,992)
			[615] button DECLINE ALL, center=(1709,992)
```
</details>

**Reasoning for action:** Clicking the Product button is a strategic first step, as it will likely lead to more information about IOMETE's data lakehouse solutions. This will help me understand the details of their services before moving on to the pricing options. Since the user's goal includes evaluating if the services fit their needs, this exploration is necessary and may provide context for understanding prices later.

**Action:** click(43) # Click on the Product button in the navigation bar to explore product offerings.

**Change Description:** After clicking the Product button in the navigation bar, its state changed to 'focused', indicating that the dropdown menu for product offerings is likely now ready for interaction, although it remains 'expanded=False', suggesting that the menu has not yet opened. Other elements of the page and the overall layout remain unchanged.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://iomete.com/

https://iomete.com/pricing

**Content (before/after):** 

```
RootWebArea IOMETE | The Self-Hosted Data Lakehouse Platform, focused, url='https://iomete.com/'
	banner
		[39] link home, center=(436,34), url='https://iomete.com/'
			image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/625d83b137c1b3783d4c8baf_iomete-logo-white-no-padding.d0313f34.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[43] button Product, center=(596,34), expanded=False, focused, hasPopup='menu'
			[61] link Pricing, center=(689,34), url='https://iomete.com/pricing'
			[63] button Use Cases, center=(793,34), expanded=False, hasPopup='menu'
			[96] button Resources, center=(920,34), expanded=False, hasPopup='menu'
			[120] button Company, center=(1044,34), expanded=False, hasPopup='menu'
		[142] link Book a demo, center=(1485,34), url='https://calendly.com/iomete/iomete-discovery-call'
	strong
		StaticText The smart alternative to Snowflake, Databricks and Cloudera.
	heading The Self-Hosted Data Lakehouse Platform
	StaticText Smart users worldwide are saying yes to IOMETE and no to data breaches and overpriced SAAS schemes designed to lock you in. Runs on premises and on public and private clouds.
	[153] link Book a Demo, center=(446,378), url='https://calendly.com/iomete/iomete-discovery-call'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/659ca9dc2db87ad28cc1151e_arrow-right-line.svg'
	[156] link Learn More, center=(596,378), url='https://iomete.com/#features-section'
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a29426aefd9be930bc5112_Lakehouses.svg'
	heading Connect to any source
	StaticText Wide variety connections and integrations.
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a289399132d6f677d6ed93_Redash%20Logo.svg'
	StaticText Redash
	StaticText Business Intelligence
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939d84d81bc48579f53_Airflow%20Logo.svg'
	StaticText Apache Airflow
	StaticText Automated Workflows
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a2893bdbd7f345933eab7c_Powerbi%20Logo.svg'
	StaticText Power BI
	StaticText Business Intelligence
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a289399132d6f677d6ed93_Redash%20Logo.svg'
	StaticText Redash
	StaticText Business Intelligence
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939d84d81bc48579f53_Airflow%20Logo.svg'
	StaticText Apache Airflow
	StaticText Automated Workflows
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a2893bdbd7f345933eab7c_Powerbi%20Logo.svg'
	StaticText Power BI
	StaticText Business Intelligence
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939a9e1bd3f0c45d7d9_Prefect%20Logo.svg'
	StaticText Prefect
	StaticText Orchestration platform
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939dc1efbe190070492_dbt%20Logo.svg'
	StaticText dbt
	StaticText Data transformations
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939322cb1690df915cf_Tableau%20Logo.svg'
	StaticText Tableau
	StaticText Business Intelligence
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939a9e1bd3f0c45d7d9_Prefect%20Logo.svg'
	StaticText Prefect
	StaticText Orchestration platform
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939dc1efbe190070492_dbt%20Logo.svg'
	StaticText dbt
	StaticText Data transformations
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a28939322cb1690df915cf_Tableau%20Logo.svg'
	StaticText Tableau
	StaticText Business Intelligence
	main
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/64824708f424f64d0de83c24_iceberg-55.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641c7734ecb40dcc40710d5f_spark.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641c8c41849aad152eed6215_Line-decoration.svg'
		StaticText A modern and open lakehouse
		paragraph
			StaticText IOMETE features the Apache Iceberg table format. Get access to ACID transactions, time travel, snapshots, schema evolution, data versioning, concurrency control, metadata management, and partitioning. Powered by the Apache Spark engine, IOMETE is fast, versatile, and scalable.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6477b9b1b8a5a55dc0773844_cloud_new.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6477b98ddf2631cdcd225391_azure.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6477b99b27cf7a136a4e8353_google%20cloud.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6477b9cfdf2631cdcd22adc2_priv_cloud.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6477c00bcda083d6ecc679d8_Group%20196.svg'
		StaticText Securely deployed where your data lives
		paragraph
			StaticText IOMETE can be deployed on-premises in your data centers, in the cloud or in a hybrid configuration. In all cases the data does not leave your trust perimeter, guaranteeing maximum data security and ownership.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641c7747dff483620728f011_graph_others.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641c774fdca2276632be2124_graph_iomete.svg'
		StaticText Disruptive, transparent pricing
		paragraph
			StaticText Cost matters. No surprise bills. No lock-ins.
		list
			listitem
			listitem
		link Book a demo, url='https://calendly.com/iomete/iomete-discovery-call'
		heading Sync. Prepare. Consume.
		StaticText Unified data for analytics, ML and AI made easy.
		StaticText SYNC
		heading Sync from a wide range of compatible data sources
		StaticText or use query federation to unify your data for analytical and ML/AI workloads.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/658da668fe1e07b8f6c549af_Sync%20image.png'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641d879f7ed9161ad7e62621_Icon_change.svg'
		StaticText Sync or ingest from a wide range of compatible data sources
		paragraph
			StaticText Use built-in serverless Spark jobs to sync data from your operational database and other data sources into a lakehouse or use a third party ELT tool to ingest your data.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641d879f16414006c18a61e3_Icon_braces.svg'
		StaticText Access your data with query federation
		paragraph
			StaticText IOMETE allows you to query disparate datasources in the same system with the same SQL. Federated queries can access your object storage, relational databases, No-SQL system, all in the same query.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641d879f7ed916ac8de62628_Icon_airplay.svg'
		StaticText Enjoy the benefits of near real-time streaming
		paragraph
			StaticText IOMETE's powerful Spark Job Cluster makes it easy to analyze realtime streaming data. With IOMETE, users can ingest and process large volumes of realtime data from a variety of sources - including IoT devices, social media feeds and financial transactions.
		StaticText PREPARE
		heading Transform, clean and organize your data with SQL, Spark and DBT.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a29426bd0b724104a9ab0e_SQL%20Editor.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da4159205bca769fe9cea_Icon-graph.svg'
		StaticText Transform your data at any scale
		paragraph
			StaticText Built-in Apache Spark can handle large datasets by dividing them into smaller partitions and processing them in parallel in clusters. This makes it highly scalable, fast and suitable for up to petabytes datasets. Apache Spark is flexible and handles SQL, Java, Scala, and Python. IOMETE offers a seamless integration with DBT.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da4152a7f8bcb2d403571_Icon-cube.svg'
		StaticText Run ad-hoc analysis with the SQL editor
		paragraph
			StaticText The built-in SQL editor provides a toolkit to make it easy to write SQL queries with features such as search, autocomplete and schema explorer.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a233e44621b6acf84f3d77_Data%20Security.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da415ed6184f4eb290772_Icon_db.svg'
		StaticText Organize your data with the built-in data catalog
		paragraph
			StaticText The IOMETE data catalog provides Google-like search, index and discovery for your data. It also allows you to document the data you own so you can stay organized.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da415ed61844c5e290773_Icon-shield.svg'
		StaticText Manage data access and become compliant with data regulations
		paragraph
			StaticText Leverage advanced data access controls to keep your data secure. IOMETE allows you to manage access on person or team level, as well as on table, row and column level. This makes it easy to become and stay compliant with regulations such as SOC2, HIPAA and GDPR.
		StaticText CONSUME
		heading Run blazing-fast analytics, ML and AI models
		StaticText and enjoy the benefits of having access to relevant, high-quality data for analysis and decision making by men and machines.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/658da68d61cdc35434cc14d2_Animation3-convert.png'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da4151bf6469ab4314d4f_Icon-chain.svg'
		StaticText Run blazing-fast analytics on quality data
		paragraph
			StaticText It’s very easy to connect IOMETE to your favorite BI tool - including Tableau, PowerBI, Metabase and Apache Superset - and enjoy the benefits of organized, high-quality data for analytical and dashboarding purposes.
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da415cc916a2a345516a9_Icon-merge.svg'
		StaticText ML and AI made easy
		paragraph
			StaticText With features such as notebook service, training ML jobs on the Spark cluster and unlimited time-travel on the data lake, IOMETE makes it easy to run your ML and AI models whether it is on premise or in the cloud.
		heading Explore IOMETE use cases
		heading On premise and hybrid deployment options
		StaticText Explore how IOMETE can be securely deployed in your trust perimeter.
		generic
			group 1 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641ca6716dd0566e41f69dd3_home%201.svg'
				StaticText IOMETE on premise deployment
				StaticText Enjoy cloud-like performance with the benefits of on premise.
				link Learn More, url='https://iomete.com/cases/iomete-on-premise'
			group 2 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641ca6716dd0566e41f69dd3_home%201.svg'
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641ca668be2a98804e3fc1ae_cloud-lightning%201.svg'
				StaticText IOMETE hybrid deployment
				StaticText Learn how to combine on premise and cloud with one platform to rule them all.
				link Learn More, url='https://iomete.com/cases/iomete-hybrid-deployment'
			group 3 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641ca668be2a98804e3fc1ae_cloud-lightning%201.svg'
				StaticText IOMETE private cloud deployment
				StaticText Learn the benefits of running IOMETE in your private cloud.
				link Learn More, url='https://iomete.com/cases/iomete-on-private-cloud'
		generic, atomic
		heading Cloud-only deployment options
		StaticText You want to know a little secret? We started out as a cloud-only data lakehouse...
		generic
			group 1 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641ca4f77d47842d589d34b7_aws-2.svg'
				StaticText IOMETE on AWS
				StaticText Learn about the benefits of running IOMETE on AWS.
				link Learn More, url='https://iomete.com/cases/iomete-on-aws'
			group 2 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/650123c1a9a4e2bd02806040_Azure.svg'
				StaticText IOMETE on Azure
				StaticText Learn about the benefits of running IOMETE on Azure.
				link Learn More, url='https://iomete.com/cases/iomete-on-azure'
			group 3 / 3
				image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/650123ea7d1d81c84f3d2b96_google%20cloud%20logo.svg'
				StaticText IOMETE on Google Cloud
				StaticText Learn about the benefits of running IOMETE on Google Cloud.
				link Learn More, url='https://iomete.com/cases/iomete-on-google-cloud'
		generic, atomic
	heading Top-Tier Data Protection Standards
	StaticText We adhere to the highest standards of security and privacy.
	StaticText Proudly displaying our SOC 2, GDPR, and HIPAA certifications, we ensure that your information is handled in compliance with data regulations.
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a0850d7a98eaf45a8c5db9_soc2.svg'
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a085264ac47a65082eeba0_gdpr.svg'
	image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65a0851bd018b401a02075ec_hipaa.svg'
	heading Ready? Try it today.
	StaticText Start with a Free Community version to see what IOMETE can do.
	StaticText Interested in Enterprise? Book a call with us!
	link Book a Demo, url='https://calendly.com/iomete/iomete-discovery-call'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/659eee191c3f7541469bc044_arrow-right-line-2.svg'
	link, url='https://iomete.com/'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/625d83b137c1b3783d4c8baf_iomete-logo-white-no-padding.d0313f34.svg'
	link IOMETE | Linkedin, url='https://www.linkedin.com/company/iomete'
		image IOMETE | Linkedin, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b1458f5642a3ba950f3bc1_linkedin-white.svg'
	link IOMETE | Github, url='https://github.com/iomete/'
		image IOMETE | Github, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b145d7b08fe6adee126913_github-white.svg'
	link IOMETE | Twitter, url='https://twitter.com/iometedata/'
		image IOMETE | Twitter, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b14595b6e174c604c778c6_twitter-white.svg'
	link IOMETE | Youtube, url='https://www.youtube.com/@iomete'
		image IOMETE | Youtube, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b1459fa105bd225de796b2_youtube-white.svg'
	StaticText 1049 El Monte Avenue
	StaticText Mountain View, CA 94040
	StaticText USA
	StaticText PRODUCT
	link Pricing, url='https://iomete.com/pricing'
	link Product Overview, url='https://iomete.com/#process'
	link Product Features, url='https://iomete.com/pricing#comparison'
	link Serverless Lakehouse, url='https://iomete.com/lakehouse'
	link SQL Editor, url='https://iomete.com/sql-editor'
	link Apache Iceberg, url='https://iomete.com/iceberg'
	StaticText SOLUTIONS
	link On Premise, url='https://iomete.com/cases/iomete-on-premise'
	link Hybrid Deployment, url='https://iomete.com/cases/iomete-hybrid-deployment'
	link Private Cloud, url='https://iomete.com/cases/iomete-on-private-cloud'
	link AWS, url='https://iomete.com/cases/iomete-on-aws'
	link Azure, url='https://iomete.com/cases/iomete-on-azure'
	link Google Cloud, url='https://iomete.com/cases/iomete-on-google-cloud'
	StaticText USE CASES
	link Financial Institutions, url='https://iomete.com/cases/iomete-for-financial-institutions'
	link Healthcare, url='https://iomete.com/cases/iomete-for-healthcare'
	link Public Sector, url='https://iomete.com/cases/iomete-for-public-sector'
	link Data Resellers, url='https://iomete.com/cases/iomete-for-data-resellers'
	StaticText RESOURCES
	link Documentation, url='https://iomete.com/resources'
	link Support, url='https://iomete.com/resources/getting-started/support'
	link Roadmap, url='https://github.com/orgs/iomete/projects/2'
	link Community, url='https://github.com/iomete'
	link Glossary, url='https://iomete.com/resources/glossary'
	link Blog, url='https://iomete.com/resources/blog'
	StaticText COMPANY
	link About Us, url='https://iomete.com/about'
	link The IOMETE Creed, url='https://iomete.com/about#creed'
	link Careers, url='https://iomete.com/about#careers'
	link Investors, url='https://iomete.com/about#investors'
	link Brand Wall, url='https://iomete.com/brand-wall'
	StaticText © 2024 IOMETE Inc. All Rights Reserved
	link Privacy Policy, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/673c9c12209584ad15a76161_IOMETE%20Privacy%20Statement%20-%20Updated%20November%202024.pdf'
	link Terms & Conditions, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/636fa7b771bc737954a0e648_IOMETE%20Terms%20of%20Service.pdf'
	link Cookies Policy, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/673c9c451e9a43448fd257fa_IOMETE%20Cookie%20Policy%20v1.1%20-%20Updated%20November%202024.pdf'
	dialog Cookie consent dialog, modal=False
		dialog Cookie consent dialog, modal=False
			[577] button Close, center=(1898,925), inner_text=×
				StaticText ×
			StaticText This website uses cookies
			StaticText We use essential cookies to make our site work. With your consent, we may also use non-essential cookies to improve user experience and analyze website traffic. For these reasons, we may share your site usage data with our analytics partners. By clicking “Accept,” you agree to our website's cookie use as described in our Cookie Policy.
			[583] link Read more, opens a new window, center=(829,983), inner_text=Read more, url='https://assets-global.website-files.com/625843c6d847c8dca08551d1/655cff76197826253dd715b5_IOMETE%20Cookie%20Policy%20v1.0%20-%20Updated%20November%202023.pdf'
			[587] checkbox PERFORMANCE, center=(62,1018), checked='false', contenteditable=True, type=checkbox
			image
			LabelText
				StaticText PERFORMANCE
			[594] checkbox MARKETING, center=(223,1018), checked='false', contenteditable=True, type=checkbox
			[591] span, center=(137,1018), inner_text=PERFORMANCE
			image
			LabelText
				StaticText MARKETING
			[601] checkbox FUNCTIONALITY, center=(359,1018), checked='false', contenteditable=True, type=checkbox
			[598] span, center=(285,1018), inner_text=MARKETING
			image
			LabelText
				StaticText FUNCTIONALITY
			[606] button SHOW DETAILS, center=(638,1053), inner_text= SHOW DETAILS
				image
			[605] span, center=(436,1018), inner_text=FUNCTIONALITY
			[614] button ACCEPT ALL, center=(1411,992)
			[615] button DECLINE ALL, center=(1709,992)
```
</details>



```
RootWebArea IOMETE | Pricing, focused, url='https://iomete.com/pricing'
	banner
		[37] link home, center=(436,34), url='https://iomete.com/'
			image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/625d83c2849ef275d484d230_iomete-logo-black.4a335b2b.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[41] button Product, center=(596,34), expanded=False, hasPopup='menu'
			[59] link Pricing, center=(689,34), url='https://iomete.com/pricing'
			[61] button Use Cases, center=(793,34), expanded=False, hasPopup='menu'
			[94] button Resources, center=(920,34), expanded=False, hasPopup='menu'
			[115] button Company, center=(1044,34), expanded=False, hasPopup='menu'
		[136] link Book a demo, center=(1485,34), url='https://calendly.com/iomete/iomete-discovery-call'
	main
		heading IOMETE Pricing
		StaticText Self-host the IOMETE Data Lakehouse on premise, on private or on public cloud.
		StaticText On Premise or Private Cloud
		StaticText Pricing based on # CPU cores.
		StaticText Custom Pricing
		list
			[166] listitem, center=(720,618), inner_text=Tailored to your needs.
				StaticText Tailored to your needs.
			[168] listitem, center=(720,646), inner_text=Best-in-industry performance.
				StaticText Best-in-industry performance.
			[170] listitem, center=(720,676), inner_text=Works with all leading object storage.
				StaticText Works with all leading object storage.
			[172] listitem, center=(720,704), inner_text=Access to all data lakehouse features.
				StaticText Access to all data lakehouse features.
			[174] listitem, center=(720,734), inner_text=Charged annually upfront.
				StaticText Charged annually upfront.
			listitem
			listitem
		[179] link Get a Quote, center=(720,817), url='https://calendly.com/iomete/iomete-discovery-call'
		StaticText Public Cloud (AWS, Azure, GC)
		StaticText Pricing based on compute.
		StaticText $0.05
		StaticText / per vCPU per hour
		list
			[190] listitem, center=(1200,618), inner_text=Straightforward pricing. No surprises.
				StaticText Straightforward pricing. No surprises.
			[192] listitem, center=(1200,646), inner_text=No pre-paid compute credits or steep markups.
				StaticText No pre-paid compute credits or steep markups.
			[194] listitem, center=(1200,676), inner_text=Runs on any cloud.
				StaticText Runs on any cloud.
			[196] listitem, center=(1200,704), inner_text=Access to all data lakehouse features.
				StaticText Access to all data lakehouse features.
			[198] listitem, center=(1200,734), inner_text=Charged at the end of the month.
				StaticText Charged at the end of the month.
		[201] link Start Now, center=(1200,817), url='https://calendly.com/iomete/iomete-discovery-call'
		heading Data Lakehouse Features
		StaticText Platform
		complementary
			StaticText Infinitely scalable
			image
		StaticText No vendor lock-in
		image
		StaticText Built on open standards
		image
		StaticText Easy setup
		StaticText Unlimited compute
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Lakehouse
		StaticText Clusters
		image
		StaticText Cluster Size
		image
		StaticText Complete SQL Data Lakehouse
		image
		StaticText Decoupled Compute & Storage
		image
		StaticText Auto-Scaling
		image
		StaticText Unlimited Time Travel
		image
		StaticText Full ANSI SQL
		image
		StaticText User Defined Functions (UDFs)
		image
		StaticText Query History and Profile
		image
		StaticText Unlimited
		StaticText Unlimited
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Lakehouse - Query Federation
		StaticText Native support for structured and semi-structured file formats
		image
		StaticText Analyze data stored in RDBMS databases (e.g. MySQL, PostgreSQL)
		image
		StaticText Analyze data stored in NoSQL sources (e.g. MongoDB, Cassandra)
		image
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Lakehouse - Connectivity
		StaticText Connecting from Java, Python, Go, Node.js
		image
		StaticText DBT Integration (data build tool)
		image
		StaticText BI Integrations - Tableau, Power BI, Metabase etc.
		image
		StaticText Notebooks Integration
		image
		StaticText Rest API
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Spark Jobs
		StaticText Number of Executors
		image
		StaticText Spark Jobs
		StaticText Auto-Scaling
		StaticText Advanced Metrics & Logs
		StaticText Unlimited
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText SQL Editor
		StaticText SQL Worksheets
		image
		StaticText Query History
		image
		StaticText Autocomplete and Syntax Highlighter
		image
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Data Governance - Data Access Control
		StaticText Centralized Data ACL
		StaticText RBAC (Role Based Access Control)
		StaticText Data Masking
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Data Governance - Data Catalog
		StaticText Data Discovery
		image
		StaticText Data Monitoring & Observability
		StaticText Automatic PII/PCI Detection
		StaticText Lineage
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Notebook service
		StaticText Jupyter Notebook Service
		StaticText Pyspark Kernel
		StaticText Python Kernel with pre-installed Mongo libraries
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Security and Compliance
		StaticText SOC2
		StaticText GDPR, HIPAA ready
		StaticText Always-on Enterprise Grade Encryption (in transit and at rest)
		StaticText Encryption with Customer-Managed Keys (BYOK)
		StaticText Audit Log
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Deployment options
		StaticText On-Premise Deployment
		StaticText Hybrid Deployment
		StaticText Private Cloud Deployment
		StaticText AWS Deployment
		StaticText Azure Deployment
		StaticText Google Cloud Deployment
		StaticText Multi-Cloud Deployment
		StaticText Multi-RegionDeployment
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText SLA/Authentication
		StaticText SLA
		StaticText Federated Authentication & SSO
		image
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Support
		StaticText First Class Onboarding
		StaticText Migration Assistance
		StaticText Enterprise Level 24 x 7 Support
		StaticText Dedicated Communication Channel (e.g. Slack, MS Teams, Discord)
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da647282133ae237910b3_cta_decoration-1.svg'
		StaticText Want to learn more about our product or book a demo?
		link Book a call, url='https://calendly.com/iomete/iomete-discovery-call'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da647132461eb69e52cb1_cta_decoration-2.svg'
	link, url='https://iomete.com/'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/625d83b137c1b3783d4c8baf_iomete-logo-white-no-padding.d0313f34.svg'
	link IOMETE | Linkedin, url='https://www.linkedin.com/company/iomete'
		image IOMETE | Linkedin, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b1458f5642a3ba950f3bc1_linkedin-white.svg'
	link IOMETE | Github, url='https://github.com/iomete/'
		image IOMETE | Github, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b145d7b08fe6adee126913_github-white.svg'
	link IOMETE | Twitter, url='https://twitter.com/iometedata/'
		image IOMETE | Twitter, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b14595b6e174c604c778c6_twitter-white.svg'
	link IOMETE | Youtube, url='https://www.youtube.com/@iomete'
		image IOMETE | Youtube, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b1459fa105bd225de796b2_youtube-white.svg'
	StaticText 1049 El Monte Avenue
	StaticText Mountain View, CA 94040
	StaticText USA
	StaticText PRODUCT
	link Pricing, url='https://iomete.com/pricing'
	link Product Overview, url='https://iomete.com/#process'
	link Product Features, url='https://iomete.com/pricing#comparison'
	link Serverless Lakehouse, url='https://iomete.com/lakehouse'
	link SQL Editor, url='https://iomete.com/sql-editor'
	link Apache Iceberg, url='https://iomete.com/iceberg'
	StaticText SOLUTIONS
	link On Premise, url='https://iomete.com/cases/iomete-on-premise'
	link Hybrid Deployment, url='https://iomete.com/cases/iomete-hybrid-deployment'
	link Private Cloud, url='https://iomete.com/cases/iomete-on-private-cloud'
	link AWS, url='https://iomete.com/cases/iomete-on-aws'
	link Azure, url='https://iomete.com/cases/iomete-on-azure'
	link Google Cloud, url='https://iomete.com/cases/iomete-on-google-cloud'
	StaticText USE CASES
	link Financial Institutions, url='https://iomete.com/cases/iomete-for-financial-institutions'
	link Healthcare, url='https://iomete.com/cases/iomete-for-healthcare'
	link Public Sector, url='https://iomete.com/cases/iomete-for-public-sector'
	link Data Resellers, url='https://iomete.com/cases/iomete-for-data-resellers'
	StaticText RESOURCES
	link Documentation, url='https://iomete.com/resources'
	link Support, url='https://iomete.com/resources/getting-started/support'
	link Roadmap, url='https://github.com/orgs/iomete/projects/2'
	link Community, url='https://github.com/iomete'
	link Glossary, url='https://iomete.com/resources/glossary'
	link Blog, url='https://iomete.com/resources/blog'
	StaticText COMPANY
	link About Us, url='https://iomete.com/about'
	link The IOMETE Creed, url='https://iomete.com/about#creed'
	link Careers, url='https://iomete.com/about#careers'
	link Investors, url='https://iomete.com/about#investors'
	link Brand Wall, url='https://iomete.com/brand-wall'
	StaticText © 2024 IOMETE Inc. All Rights Reserved
	link Privacy Policy, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/673c9c12209584ad15a76161_IOMETE%20Privacy%20Statement%20-%20Updated%20November%202024.pdf'
	link Terms & Conditions, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/636fa7b771bc737954a0e648_IOMETE%20Terms%20of%20Service.pdf'
	link Cookies Policy, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/673c9c451e9a43448fd257fa_IOMETE%20Cookie%20Policy%20v1.1%20-%20Updated%20November%202024.pdf'
	dialog Cookie consent dialog, modal=False
		dialog Cookie consent dialog, modal=False
			[1273] button Close, center=(1898,925), inner_text=×
				StaticText ×
			StaticText This website uses cookies
			StaticText We use essential cookies to make our site work. With your consent, we may also use non-essential cookies to improve user experience and analyze website traffic. For these reasons, we may share your site usage data with our analytics partners. By clicking “Accept,” you agree to our website's cookie use as described in our Cookie Policy.
			[1279] link Read more, opens a new window, center=(829,983), inner_text=Read more, url='https://assets-global.website-files.com/625843c6d847c8dca08551d1/655cff76197826253dd715b5_IOMETE%20Cookie%20Policy%20v1.0%20-%20Updated%20November%202023.pdf'
			[1283] checkbox PERFORMANCE, center=(62,1018), checked='false', contenteditable=True, type=checkbox
			image
			LabelText
				StaticText PERFORMANCE
			[1290] checkbox MARKETING, center=(223,1018), checked='false', contenteditable=True, type=checkbox
			[1287] span, center=(137,1018), inner_text=PERFORMANCE
			image
			LabelText
				StaticText MARKETING
			[1297] checkbox FUNCTIONALITY, center=(359,1018), checked='false', contenteditable=True, type=checkbox
			[1294] span, center=(285,1018), inner_text=MARKETING
			image
			LabelText
				StaticText FUNCTIONALITY
			[1302] button SHOW DETAILS, center=(638,1053), inner_text= SHOW DETAILS
				image
			[1301] span, center=(436,1018), inner_text=FUNCTIONALITY
			[1310] button ACCEPT ALL, center=(1411,992)
			[1311] button DECLINE ALL, center=(1709,992)
```
</details>

**Reasoning for action:** By clicking on the Pricing link, I moved closer to accessing the information about IOMETE's pricing structures, which is essential for the user to evaluate whether their services fit their budget and needs. This directly meets the user's requirement to explore pricing options.

**Action:** click(61) # Click on the Pricing link to explore the pricing options for IOMETE.

**Change Description:** The browser navigated from the IOMETE homepage to the Pricing page, updating the displayed content from general platform information to specific pricing details for IOMETE's offerings, including on-premise, private, and public cloud pricing models.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://iomete.com/pricing

https://calendly.com/iomete/iomete-discovery-call?month=2025-01

**Content (before/after):** 

```
RootWebArea IOMETE | Pricing, focused, url='https://iomete.com/pricing'
	banner
		[37] link home, center=(436,34), url='https://iomete.com/'
			image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/625d83c2849ef275d484d230_iomete-logo-black.4a335b2b.svg'
		navigation
```
<details><summary>Show more</summary>

```
			[41] button Product, center=(596,34), expanded=False, hasPopup='menu'
			[59] link Pricing, center=(689,34), url='https://iomete.com/pricing'
			[61] button Use Cases, center=(793,34), expanded=False, hasPopup='menu'
			[94] button Resources, center=(920,34), expanded=False, hasPopup='menu'
			[115] button Company, center=(1044,34), expanded=False, hasPopup='menu'
		[136] link Book a demo, center=(1485,34), url='https://calendly.com/iomete/iomete-discovery-call'
	main
		heading IOMETE Pricing
		StaticText Self-host the IOMETE Data Lakehouse on premise, on private or on public cloud.
		StaticText On Premise or Private Cloud
		StaticText Pricing based on # CPU cores.
		StaticText Custom Pricing
		list
			[166] listitem, center=(720,618), inner_text=Tailored to your needs.
				StaticText Tailored to your needs.
			[168] listitem, center=(720,646), inner_text=Best-in-industry performance.
				StaticText Best-in-industry performance.
			[170] listitem, center=(720,676), inner_text=Works with all leading object storage.
				StaticText Works with all leading object storage.
			[172] listitem, center=(720,704), inner_text=Access to all data lakehouse features.
				StaticText Access to all data lakehouse features.
			[174] listitem, center=(720,734), inner_text=Charged annually upfront.
				StaticText Charged annually upfront.
			listitem
			listitem
		[179] link Get a Quote, center=(720,817), url='https://calendly.com/iomete/iomete-discovery-call'
		StaticText Public Cloud (AWS, Azure, GC)
		StaticText Pricing based on compute.
		StaticText $0.05
		StaticText / per vCPU per hour
		list
			[190] listitem, center=(1200,618), inner_text=Straightforward pricing. No surprises.
				StaticText Straightforward pricing. No surprises.
			[192] listitem, center=(1200,646), inner_text=No pre-paid compute credits or steep markups.
				StaticText No pre-paid compute credits or steep markups.
			[194] listitem, center=(1200,676), inner_text=Runs on any cloud.
				StaticText Runs on any cloud.
			[196] listitem, center=(1200,704), inner_text=Access to all data lakehouse features.
				StaticText Access to all data lakehouse features.
			[198] listitem, center=(1200,734), inner_text=Charged at the end of the month.
				StaticText Charged at the end of the month.
		[201] link Start Now, center=(1200,817), url='https://calendly.com/iomete/iomete-discovery-call'
		heading Data Lakehouse Features
		StaticText Platform
		complementary
			StaticText Infinitely scalable
			image
		StaticText No vendor lock-in
		image
		StaticText Built on open standards
		image
		StaticText Easy setup
		StaticText Unlimited compute
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Lakehouse
		StaticText Clusters
		image
		StaticText Cluster Size
		image
		StaticText Complete SQL Data Lakehouse
		image
		StaticText Decoupled Compute & Storage
		image
		StaticText Auto-Scaling
		image
		StaticText Unlimited Time Travel
		image
		StaticText Full ANSI SQL
		image
		StaticText User Defined Functions (UDFs)
		image
		StaticText Query History and Profile
		image
		StaticText Unlimited
		StaticText Unlimited
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Lakehouse - Query Federation
		StaticText Native support for structured and semi-structured file formats
		image
		StaticText Analyze data stored in RDBMS databases (e.g. MySQL, PostgreSQL)
		image
		StaticText Analyze data stored in NoSQL sources (e.g. MongoDB, Cassandra)
		image
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Lakehouse - Connectivity
		StaticText Connecting from Java, Python, Go, Node.js
		image
		StaticText DBT Integration (data build tool)
		image
		StaticText BI Integrations - Tableau, Power BI, Metabase etc.
		image
		StaticText Notebooks Integration
		image
		StaticText Rest API
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Spark Jobs
		StaticText Number of Executors
		image
		StaticText Spark Jobs
		StaticText Auto-Scaling
		StaticText Advanced Metrics & Logs
		StaticText Unlimited
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText SQL Editor
		StaticText SQL Worksheets
		image
		StaticText Query History
		image
		StaticText Autocomplete and Syntax Highlighter
		image
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Data Governance - Data Access Control
		StaticText Centralized Data ACL
		StaticText RBAC (Role Based Access Control)
		StaticText Data Masking
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Data Governance - Data Catalog
		StaticText Data Discovery
		image
		StaticText Data Monitoring & Observability
		StaticText Automatic PII/PCI Detection
		StaticText Lineage
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Notebook service
		StaticText Jupyter Notebook Service
		StaticText Pyspark Kernel
		StaticText Python Kernel with pre-installed Mongo libraries
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Security and Compliance
		StaticText SOC2
		StaticText GDPR, HIPAA ready
		StaticText Always-on Enterprise Grade Encryption (in transit and at rest)
		StaticText Encryption with Customer-Managed Keys (BYOK)
		StaticText Audit Log
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Deployment options
		StaticText On-Premise Deployment
		StaticText Hybrid Deployment
		StaticText Private Cloud Deployment
		StaticText AWS Deployment
		StaticText Azure Deployment
		StaticText Google Cloud Deployment
		StaticText Multi-Cloud Deployment
		StaticText Multi-RegionDeployment
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText SLA/Authentication
		StaticText SLA
		StaticText Federated Authentication & SSO
		image
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		StaticText Support
		StaticText First Class Onboarding
		StaticText Migration Assistance
		StaticText Enterprise Level 24 x 7 Support
		StaticText Dedicated Communication Channel (e.g. Slack, MS Teams, Discord)
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/6421b77204e8b3ed15764d27_Yes.svg'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da647282133ae237910b3_cta_decoration-1.svg'
		StaticText Want to learn more about our product or book a demo?
		link Book a call, url='https://calendly.com/iomete/iomete-discovery-call'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/641da647132461eb69e52cb1_cta_decoration-2.svg'
	link, url='https://iomete.com/'
		image, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/625d83b137c1b3783d4c8baf_iomete-logo-white-no-padding.d0313f34.svg'
	link IOMETE | Linkedin, url='https://www.linkedin.com/company/iomete'
		image IOMETE | Linkedin, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b1458f5642a3ba950f3bc1_linkedin-white.svg'
	link IOMETE | Github, url='https://github.com/iomete/'
		image IOMETE | Github, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b145d7b08fe6adee126913_github-white.svg'
	link IOMETE | Twitter, url='https://twitter.com/iometedata/'
		image IOMETE | Twitter, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b14595b6e174c604c778c6_twitter-white.svg'
	link IOMETE | Youtube, url='https://www.youtube.com/@iomete'
		image IOMETE | Youtube, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/65b1459fa105bd225de796b2_youtube-white.svg'
	StaticText 1049 El Monte Avenue
	StaticText Mountain View, CA 94040
	StaticText USA
	StaticText PRODUCT
	link Pricing, url='https://iomete.com/pricing'
	link Product Overview, url='https://iomete.com/#process'
	link Product Features, url='https://iomete.com/pricing#comparison'
	link Serverless Lakehouse, url='https://iomete.com/lakehouse'
	link SQL Editor, url='https://iomete.com/sql-editor'
	link Apache Iceberg, url='https://iomete.com/iceberg'
	StaticText SOLUTIONS
	link On Premise, url='https://iomete.com/cases/iomete-on-premise'
	link Hybrid Deployment, url='https://iomete.com/cases/iomete-hybrid-deployment'
	link Private Cloud, url='https://iomete.com/cases/iomete-on-private-cloud'
	link AWS, url='https://iomete.com/cases/iomete-on-aws'
	link Azure, url='https://iomete.com/cases/iomete-on-azure'
	link Google Cloud, url='https://iomete.com/cases/iomete-on-google-cloud'
	StaticText USE CASES
	link Financial Institutions, url='https://iomete.com/cases/iomete-for-financial-institutions'
	link Healthcare, url='https://iomete.com/cases/iomete-for-healthcare'
	link Public Sector, url='https://iomete.com/cases/iomete-for-public-sector'
	link Data Resellers, url='https://iomete.com/cases/iomete-for-data-resellers'
	StaticText RESOURCES
	link Documentation, url='https://iomete.com/resources'
	link Support, url='https://iomete.com/resources/getting-started/support'
	link Roadmap, url='https://github.com/orgs/iomete/projects/2'
	link Community, url='https://github.com/iomete'
	link Glossary, url='https://iomete.com/resources/glossary'
	link Blog, url='https://iomete.com/resources/blog'
	StaticText COMPANY
	link About Us, url='https://iomete.com/about'
	link The IOMETE Creed, url='https://iomete.com/about#creed'
	link Careers, url='https://iomete.com/about#careers'
	link Investors, url='https://iomete.com/about#investors'
	link Brand Wall, url='https://iomete.com/brand-wall'
	StaticText © 2024 IOMETE Inc. All Rights Reserved
	link Privacy Policy, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/673c9c12209584ad15a76161_IOMETE%20Privacy%20Statement%20-%20Updated%20November%202024.pdf'
	link Terms & Conditions, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/636fa7b771bc737954a0e648_IOMETE%20Terms%20of%20Service.pdf'
	link Cookies Policy, url='https://cdn.prod.website-files.com/625843c6d847c8dca08551d1/673c9c451e9a43448fd257fa_IOMETE%20Cookie%20Policy%20v1.1%20-%20Updated%20November%202024.pdf'
	dialog Cookie consent dialog, modal=False
		dialog Cookie consent dialog, modal=False
			[1273] button Close, center=(1898,925), inner_text=×
				StaticText ×
			StaticText This website uses cookies
			StaticText We use essential cookies to make our site work. With your consent, we may also use non-essential cookies to improve user experience and analyze website traffic. For these reasons, we may share your site usage data with our analytics partners. By clicking “Accept,” you agree to our website's cookie use as described in our Cookie Policy.
			[1279] link Read more, opens a new window, center=(829,983), inner_text=Read more, url='https://assets-global.website-files.com/625843c6d847c8dca08551d1/655cff76197826253dd715b5_IOMETE%20Cookie%20Policy%20v1.0%20-%20Updated%20November%202023.pdf'
			[1283] checkbox PERFORMANCE, center=(62,1018), checked='false', contenteditable=True, type=checkbox
			image
			LabelText
				StaticText PERFORMANCE
			[1290] checkbox MARKETING, center=(223,1018), checked='false', contenteditable=True, type=checkbox
			[1287] span, center=(137,1018), inner_text=PERFORMANCE
			image
			LabelText
				StaticText MARKETING
			[1297] checkbox FUNCTIONALITY, center=(359,1018), checked='false', contenteditable=True, type=checkbox
			[1294] span, center=(285,1018), inner_text=MARKETING
			image
			LabelText
				StaticText FUNCTIONALITY
			[1302] button SHOW DETAILS, center=(638,1053), inner_text= SHOW DETAILS
				image
			[1301] span, center=(436,1018), inner_text=FUNCTIONALITY
			[1310] button ACCEPT ALL, center=(1411,992)
			[1311] button DECLINE ALL, center=(1709,992)
```
</details>



```
RootWebArea Select a Date & Time - Calendly, focused, url='https://calendly.com/iomete/iomete-discovery-call?month=2025-01'
	image Company logo, url='https://d3v0px0pttie1i.cloudfront.net/uploads/branding/logo/8e7ab4c2-94fb-45d6-85a3-b95125433a56/f17709b2.png'
	image IOMETE, url='https://d3v0px0pttie1i.cloudfront.net/uploads/team/avatar/252372/ca2c5936.png'
	StaticText IOMETE
	heading IOMETE Discovery Call
```
<details><summary>Show more</summary>

```
	StaticText 20 min
	StaticText Web conferencing details provided upon confirmation.
	paragraph
		StaticText 20-min intro / discovery call
	[96] button Cookie settings, center=(646,728), type=button
	[99] link Report abuse, center=(887,728), url='https://calendly.com/abuse_reports/new?source=dqPpsK0JflI_GS-ouwnJBlzXy8Kht7uKiVpPhtOdb99BRxCmtOolS9sMd3my2RrOiDwCx7QXBx-Bkd5_rGISlvG45MAQ0xaaW_7RUMsd'
	heading Select a Date & Time
	button Go to previous month, disabled=True
	StaticText January 2025
	[114] button Go to next month, center=(1251,170), type=button
	status, atomic
		StaticText January is now displayed
	table Select a Day
		rowgroup
			row
				columnheader SUN
				columnheader MON
				columnheader TUE
				columnheader WED
				columnheader THU
				columnheader FRI
				columnheader SAT
		rowgroup
			row
				[131] gridcell, center=(1005,254)
				[134] gridcell, center=(1056,254)
				[137] gridcell, center=(1108,254)
				[140] gridcell Wednesday, January 1 - No times available, center=(1159,254), inner_text=1
					button Wednesday, January 1 - No times available, disabled=True
				[143] gridcell Thursday, January 2 - No times available, center=(1211,254), inner_text=2
					button Thursday, January 2 - No times available, disabled=True
				[146] gridcell Friday, January 3 - No times available, center=(1263,254), inner_text=3
					button Friday, January 3 - No times available, disabled=True
				[149] gridcell Saturday, January 4 - No times available, center=(1314,254), inner_text=4
					button Saturday, January 4 - No times available, disabled=True
			row
				[153] gridcell Sunday, January 5 - No times available, center=(1005,306), inner_text=5
					button Sunday, January 5 - No times available, disabled=True
				[156] gridcell Monday, January 6 - No times available, center=(1056,306), inner_text=6
					button Monday, January 6 - No times available, disabled=True
				gridcell Tuesday, January 7 - Times available, selected=False
					[160] button Tuesday, January 7 - Times available, center=(1108,306), inner_text=7, type=button
				gridcell Wednesday, January 8 - Times available, selected=False
					[164] button Wednesday, January 8 - Times available, center=(1159,306), inner_text=8, type=button
				gridcell Thursday, January 9 - Times available, selected=False
					[167] button Thursday, January 9 - Times available, center=(1211,306), inner_text=9, type=button
				gridcell Friday, January 10 - Times available, selected=False
					[170] button Friday, January 10 - Times available, center=(1263,306), inner_text=10, type=button
				gridcell Saturday, January 11 - Times available, selected=False
					[173] button Saturday, January 11 - Times available, center=(1314,306), inner_text=11, type=button
			row
				[176] gridcell Sunday, January 12 - No times available, center=(1005,358), inner_text=12
					button Sunday, January 12 - No times available, disabled=True
				gridcell Monday, January 13 - Times available, selected=False
					[180] button Monday, January 13 - Times available, center=(1056,358), inner_text=13, type=button
				gridcell Tuesday, January 14 - Times available, selected=False
					[183] button Tuesday, January 14 - Times available, center=(1108,358), inner_text=14, type=button
				gridcell Wednesday, January 15 - Times available, selected=False
					[186] button Wednesday, January 15 - Times available, center=(1159,358), inner_text=15, type=button
				gridcell Thursday, January 16 - Times available, selected=False
					[189] button Thursday, January 16 - Times available, center=(1211,358), inner_text=16, type=button
				gridcell Friday, January 17 - Times available, selected=False
					[192] button Friday, January 17 - Times available, center=(1263,358), inner_text=17, type=button
				gridcell Saturday, January 18 - Times available, selected=False
					[195] button Saturday, January 18 - Times available, center=(1314,358), inner_text=18, type=button
			row
				[198] gridcell Sunday, January 19 - No times available, center=(1005,410), inner_text=19
					button Sunday, January 19 - No times available, disabled=True
				gridcell Monday, January 20 - Times available, selected=False
					[202] button Monday, January 20 - Times available, center=(1056,410), inner_text=20, type=button
				gridcell Tuesday, January 21 - Times available, selected=False
					[205] button Tuesday, January 21 - Times available, center=(1108,410), inner_text=21, type=button
				gridcell Wednesday, January 22 - Times available, selected=False
					[208] button Wednesday, January 22 - Times available, center=(1159,410), inner_text=22, type=button
				gridcell Thursday, January 23 - Times available, selected=False
					[211] button Thursday, January 23 - Times available, center=(1211,410), inner_text=23, type=button
				gridcell Friday, January 24 - Times available, selected=False
					[214] button Friday, January 24 - Times available, center=(1263,410), inner_text=24, type=button
				gridcell Saturday, January 25 - Times available, selected=False
					[217] button Saturday, January 25 - Times available, center=(1314,410), inner_text=25, type=button
			row
				[220] gridcell Sunday, January 26 - No times available, center=(1005,462), inner_text=26
					button Sunday, January 26 - No times available, disabled=True
				gridcell Monday, January 27 - Times available, selected=False
					[224] button Monday, January 27 - Times available, center=(1056,462), inner_text=27, type=button
				gridcell Tuesday, January 28 - Times available, selected=False
					[227] button Tuesday, January 28 - Times available, center=(1108,462), inner_text=28, type=button
				gridcell Wednesday, January 29 - Times available, selected=False
					[230] button Wednesday, January 29 - Times available, center=(1159,462), inner_text=29, type=button
				gridcell Thursday, January 30 - Times available, selected=False
					[233] button Thursday, January 30 - Times available, center=(1211,462), inner_text=30, type=button
				gridcell Friday, January 31 - Times available, selected=False
					[236] button Friday, January 31 - Times available, center=(1263,462), inner_text=31, type=button
				[238] gridcell, center=(1314,462)
	status, atomic
	paragraph
		StaticText Time zone
	[246] button Time zone  UTC Time (12:21pm) , center=(1079,556), expanded=False, inner_text=UTC Time
(12:21pm), type=button
	region Cookie banner
		alertdialog We respect your personal privacy, modal=False
			StaticText We respect your personal privacy
			StaticText We and our partners use cookies, pixels, and similar tracking technology (all called “cookies” here), including necessary cookies to provide our websites and optional cookies to collect information from you (including your clicks, cursor movements, and screen recordings on our websites) for site functionality and personalization, usage analytics, and marketing. You consent to our use of all cookies by choosing “l understand” or continuing to use this website. You may decline optional cookies by choosing "Do not allow cookies". We honor opt-out preference signals.
			[269] link Click here, center=(514,933), url='https://calendly.com/privacy'
			StaticText to read about how we use your personal data.
			[273] button Do not allow cookies, center=(372,1003)
			[274] button I understand, center=(510,1003)
			[275] button Cookie settings, center=(99,1003)
			[278] button Close, center=(560,764)
```
</details>

**Reasoning for action:** By clicking on the 'Get a Quote' link (identified by its index 179), I advance the task of exploring IOMETE's pricing options, which is essential for fulfilling the user story. This action directly connects me to a platform where I can schedule a discovery call, thus enabling me to inquire about pricing details tailored to my needs. This step is crucial as it progressively enables me to gather the necessary information to assess whether IOMETE's services fit within my budget.

**Action:** click(179) # Click on the Get a Quote link to explore custom pricing details.

**Change Description:** After clicking the 'Get a Quote' link, the browser navigated to the Calendly scheduling page where the user can select a date and time for an IOMETE discovery call, replacing the previous pricing details with a scheduling interface.

**Screenshot before:****Screenshot after:**---


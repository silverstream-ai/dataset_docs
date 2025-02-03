# Task

**User Journey to Discover Artie's Compliance Features**

As a potential customer,
I explore Artie's features specifically related to HIPAA compliance,
so that I can understand how Artie's solutions align with my company's regulatory needs.

**Success definition:** Given I am on the Artie website and interested in data compliance features
When I navigate to the 'About' page and then go to the 'Blog' page to find the post about HIPAA compliance
Then I should see the HIPAA compliance blog post with details about the announcement and its implications for users.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.artie.com/

https://www.artie.com/about

**Content (before/after):** 

```
RootWebArea Artie | Real-time data replication platform, focused, url='https://www.artie.com/'
	banner
		[38] link home, center=(428,44), url='https://www.artie.com/'
			image Artie logo, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/6690586b63f787ded1c849af_artie-logo.png'
		navigation
```
<details><summary>Show more</summary>

```
			[42] link About, center=(517,46), url='https://www.artie.com/about'
			[43] link Blog, center=(607,46), url='https://www.artie.com/blogs'
			[44] link Customers, center=(713,46), url='https://www.artie.com/customer-stories'
			[45] link Docs, center=(820,46), url='https://www.artie.com/docs/start'
			[46] link Pricing, center=(915,46), url='https://www.artie.com/pricing'
		[48] link Get started, center=(1455,46), url='https://www.artie.com/contact'
		[49] link Login, center=(1544,46), url='https://app.artie.com/login'
	[58] link We're hiring!, center=(438,204), url='https://www.ycombinator.com/companies/artie/jobs'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0ce552abb4459f5b4c_chevron-right-small-white.svg'
	heading Real-time database replication
	paragraph
		StaticText 10x better pipelines to move your most important data.
	[65] link Get started, center=(442,512), url='https://www.artie.com/contact'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0be552abb4459f5aca_chevron-right-black.svg'
	[68] link Documentation, center=(616,512), url='https://artie.com/docs/start'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0be552abb4459f5b17_chevron-right-white.svg'
	StaticText Trusted by world-class data & engineering teams
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0de552abb4459f5c34_tango-logo.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0de552abb4459f5c92_papaya-pay-logo.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0de552abb4459f5c09_roundtable-logo.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0de552abb4459f5c39_apkudo-logo.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0de552abb4459f5c81_keep-logo.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0de552abb4459f5c43_indigov-logo.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66dfc8e013442304bb633beb_stitch-moneyl-logo.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0ce552abb4459f5b76_substack-logo.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0ae552abb4459f5a3a_image-1.png'
	heading Reliability & consistency is just the beginning
	StaticText Effortless replication that gives you a peace of mind at terabyte scale.
	link Talk to a founder, url='https://www.artie.com/contact'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0be552abb4459f5b17_chevron-right-white.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905b542d244fb0b68e6e83_database-icon.png'
	heading Pipelines that will blow you away
	StaticText Artie leverages change data capture to replicate only the data that has changed. Built-in analytics and monitors mean you’re on top of schema changes and pipeline anomalies.
	tablist, orientation='horizontal'
		tab Built-in analytics, selected=True
			image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905b562d244fb0b68e702c_analytics-icon.png'
		tab Monitors, selected=False
			image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905b562d244fb0b68e6fd2_code-icon.png'
		tab Schema change alerts, selected=False
			image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905b552d244fb0b68e6f04_schema-icon.png'
	tabpanel Built-in analytics
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905b582d244fb0b68e7108_built-in-analytics-screenshot-p-1600.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66dfbd1edd4d91a8c5458518_chevron-large-left.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66dfbd1edd4d91a8c5458514_chevron-large-right.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905b983a5cf8706d7fd969_substack-icon-circle.svg'
	paragraph
		StaticText Our A/B testing framework measures much faster and we have higher data integrity now. This means the whole company can move faster and make decisions quicker. Artie is business critical and our day to day would be significantly tougher without it.
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/65afa291bd9dd99b54e91141_mike-cohen.webp'
	StaticText Mike Cohen, Head of Data at Substack
	StaticText Sources
	StaticText DocumentDB
	image DocumentDB, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66e387f712e1a2185f8f071b_source-destination-icon.png'
	StaticText DynamoDB
	image DynamoDB, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66e387f6280a3c340972e3c2_source-destination-icon-1.png'
	StaticText MongoDB
	image MongoDB, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66e387f712e1a2185f8f0728_source-destination-icon-2.png'
	StaticText SQL Server
	image Microsoft SQL Server, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66e387f6b1331eb92c0312fe_source-destination-icon-3.png'
	StaticText MySQL
	image MySQL, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66e387f712e1a2185f8f0721_source-destination-icon-4.png'
	StaticText Postgres
	image Postgres, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66e387f6a07e40107a7de510_source-destination-icon-5.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66dfc0f513442304bb5a32f5_Vectors-Wrapper.svg'
	StaticText Destinations
	image Snowflake, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66e387f7bebc12bb366b8fbc_source-destination-icon-6.png'
	StaticText Snowflake
	image Databricks, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66e389be1404fefff513edd2_source-destination-icon-10.png'
	StaticText Databricks
	image BigQuery, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66e387f6f1dcd6d6446e6882_source-destination-icon-7.png'
	StaticText BigQuery
	image Redshift, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66e387f63c8f8eea6a01bc3d_source-destination-icon-8.png'
	StaticText Redshift
	image Microsoft SQL Server, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66e387f6b1331eb92c0312fe_source-destination-icon-3.png'
	StaticText SQL Server
	image Postgres, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66e387f6a07e40107a7de510_source-destination-icon-5.png'
	StaticText Postgres
	image S3, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66e387f712e1a2185f8f0715_source-destination-icon-9.png'
	StaticText S3
	StaticText Supported integrations.
	StaticText We have you covered
	StaticText Inbox
	StaticText 23 messages
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905bc8b65e13170c59e370_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905bc8b65e13170c59e39e_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905bc8b65e13170c59e394_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905bc9b65e13170c59e3b6_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905bc9b65e13170c59e3c9_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905bc9b65e13170c59e3d1_Vectors-Wrapper.svg'
	StaticText Artie
	StaticText The schema of your table
	StaticText customers
	StaticText has changed
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905bc8b65e13170c59e370_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905bc8b65e13170c59e39e_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905bc8b65e13170c59e394_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905bc9b65e13170c59e3cd_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905bc8b65e13170c59e370_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905bc8b65e13170c59e39e_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905bc8b65e13170c59e394_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905bc9b65e13170c59e3ee_Vectors-Wrapper.svg'
	StaticText Schema change alerts.
	StaticText We notify you before downstream operations break
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905bc9b65e13170c59e3f8_Vectors-Wrapper.svg'
	StaticText History mode.
	StaticText Replace daily snapshots with slowly changing dimension tables in one-click
	heading Sick of tools that barely work? There’s a better way
	link Fast, parallelized backfills Blazing fast backfills that do not require table locking and can be performed on read replicas, url='https://www.artie.com/#'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905ca8b65e13170c5a715f_backfill-icon.svg'
	link Eventual consistency guaranteed No more missing data. We hard fail and continuously retry on every data ingestion error to guarantee data consistency, url='https://www.artie.com/#'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905ca7b65e13170c5a7155_missing-data-icon.svg'
	link Schema evolution Automatic column detection, mapping and creation, url='https://www.artie.com/#'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905ca7b65e13170c5a7112_schema-evolution-icon.svg'
	link Soft or hard delete rows Choose how you want to handle deleted rows. Or skip processing deletes entirely, url='https://www.artie.com/#'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905ca7b65e13170c5a7100_soft-delete-icon.svg'
	link Datadog integration Send metrics directly to your Datadog and create custom monitors, url='https://www.artie.com/#'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905ca8b65e13170c5a7159_datadog-icon.svg'
	link Terraform Manage your deployments via API or Terraform, url='https://www.artie.com/#'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905ca7b65e13170c5a7147_terraform-icon.svg'
	heading What Artie users say
	StaticText Companies trust Artie with their most critical business data to power operations and customer facing data products. When was the last time you thought about your pipelines? Our customers never do.
	StaticText We went from doing multi-hour batched syncs to real time streaming with Artie - we now have live visibility into what’s happening in the business. We were impressed at how easy Artie was to set up at our scale!
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/65afa291bd9dd99b54e91141_mike-cohen.webp'
	StaticText Mike Cohen
	StaticText Head of AI and ML Engineering, Substack
	StaticText Discovering Artie has been a game-changer in our data management strategy. In an arena where real-time access to data can define market leadership, their tool bridges the gap between our database and data warehouse with seamless, zero-latency synchronization. It's not just about speed; the fidelity of our data remains uncompromised with no unnecessary data type
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/65afa3b8bd7a8c6ece8b28d9_jason.webp'
	strong
		StaticText Jason Hodson
	StaticText Director, Data & Analytics, Routable
	StaticText Artie is powering our most important tables today. The product and engineering teams at Tatango are able to provide near real-time sending and performance related analytics to our customers, enabling them to focus on what matters most; fundraise.
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/65afa4be12ec161d36357a8e_matthew.webp'
	strong
		StaticText Matt Powers
	StaticText CTO, Tatango
	StaticText Artie is a game changer in our data stack. It makes syncing your engineering team's database to your data warehouse seamless and pain free. In a world where out of the box solutions frequently get you 80% "there", Artie gets you 100% of what you need.In addition, Artie can scale with your business. No more trying to batch load your data before daily reports go out.
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/65afa4b71324ff28c89cf861_danielle.webp'
	StaticText Danielle Barringer
	StaticText Lead Data Engineer, Yaysay
	StaticText Artie's innovative eco-mode function have revolutionized our data transfer process. We can now adjust replication frequency to match demand, improving data freshness without escalating costs. What sets Artie apart is the collaboration with its passionate founders. They don't just listen but act quickly on our feedback.
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/65afa4ae5119ef83152f0e6f_chao-li-p-500.webp'
	StaticText Chao Li
	StaticText Senior Data Engineer, Sleeping Duck
	StaticText Artie Transfer was the missing piece from our ETL data pipeline that delivered data replication between PostgreSQL and Snowflake! It enables our Product Intelligence team and our BI tools to have real-time access to data straight from our data warehouse.
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/65af9cb7ec6612fa3e02e442_tamas-p-500.webp'
	StaticText Tamas Boros
	StaticText Engineering Director, FYLD AI
	StaticText Artie’s simple configuration and interoperability with popular developer tools makes it an easy choice for replacing batch data replication with streaming in our upcoming data resiliency efforts.
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/65afa4a79a6d740ace1916c6_ari.webp'
	StaticText Ari Falkner
	StaticText Software Engineer, OpenStore
	StaticText Artie has been a foundational component of building our data stack. As a data-driven fintech startup, we wanted all the benefits of fast and reliable database replication, without having to invest months of engineering time to build and maintain a robust pipeline. We now can focus on building products that our customers love.
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66a3fd35a06b7a8acbf94932_helson-taveras.jpg'
	StaticText Helson Taveras
	StaticText Co-founder & CTO
	StaticText We went from doing multi-hour batched syncs to real time streaming with Artie - we now have live visibility into what’s happening in the business. We were impressed at how easy Artie was to set up at our scale!
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/65afa291bd9dd99b54e91141_mike-cohen.webp'
	StaticText Mike Cohen
	StaticText Head of AI and ML Engineering, Substack
	StaticText Discovering Artie has been a game-changer in our data management strategy. In an arena where real-time access to data can define market leadership, their tool bridges the gap between our database and data warehouse with seamless, zero-latency synchronization. It's not just about speed; the fidelity of our data remains uncompromised with no unnecessary data type
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/65afa3b8bd7a8c6ece8b28d9_jason.webp'
	strong
		StaticText Jason Hodson
	StaticText Director, Data & Analytics, Routable
	StaticText Artie is powering our most important tables today. The product and engineering teams at Tatango are able to provide near real-time sending and performance related analytics to our customers, enabling them to focus on what matters most; fundraise.
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/65afa4be12ec161d36357a8e_matthew.webp'
	strong
		StaticText Matt Powers
	StaticText CTO, Tatango
	StaticText Artie is a game changer in our data stack. It makes syncing your engineering team's database to your data warehouse seamless and pain free. In a world where out of the box solutions frequently get you 80% "there", Artie gets you 100% of what you need.In addition, Artie can scale with your business. No more trying to batch load your data before daily reports go out.
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/65afa4b71324ff28c89cf861_danielle.webp'
	StaticText Danielle Barringer
	StaticText Lead Data Engineer, Yaysay
	StaticText Artie's innovative eco-mode function have revolutionized our data transfer process. We can now adjust replication frequency to match demand, improving data freshness without escalating costs. What sets Artie apart is the collaboration with its passionate founders. They don't just listen but act quickly on our feedback.
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/65afa4ae5119ef83152f0e6f_chao-li-p-500.webp'
	StaticText Chao Li
	StaticText Senior Data Engineer, Sleeping Duck
	StaticText Artie Transfer was the missing piece from our ETL data pipeline that delivered data replication between PostgreSQL and Snowflake! It enables our Product Intelligence team and our BI tools to have real-time access to data straight from our data warehouse.
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/65af9cb7ec6612fa3e02e442_tamas-p-500.webp'
	StaticText Tamas Boros
	StaticText Engineering Director, FYLD AI
	StaticText Artie’s simple configuration and interoperability with popular developer tools makes it an easy choice for replacing batch data replication with streaming in our upcoming data resiliency efforts.
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/65afa4a79a6d740ace1916c6_ari.webp'
	StaticText Ari Falkner
	StaticText Software Engineer, OpenStore
	StaticText Artie has been a foundational component of building our data stack. As a data-driven fintech startup, we wanted all the benefits of fast and reliable database replication, without having to invest months of engineering time to build and maintain a robust pipeline. We now can focus on building products that our customers love.
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66a3fd35a06b7a8acbf94932_helson-taveras.jpg'
	StaticText Helson Taveras
	StaticText Co-founder & CTO
	heading 10x better pipelines. This weekend.
	link Get started, url='https://www.artie.com/contact'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0be552abb4459f5aca_chevron-right-black.svg'
	link Talk to a founder, url='https://www.artie.com/contact'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0be552abb4459f5b17_chevron-right-white.svg'
	image, url='https://cdn.prod.website-files.com/66762bf6418642de486f1cc6/6687f9e4df3ac33cc807ef88_artie-logo.png'
	StaticText 220 Sansome Street, San Francisco, CA 94104
	link, url='https://x.com/artie_tech'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f2922d3_Vectors-Wrapper.svg'
	link, url='https://github.com/artie-labs/'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292342_Vectors-Wrapper.svg'
	link, url='https://artie.com/slack'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292314_Vectors-Wrapper.svg'
	link, url='https://www.linkedin.com/company/artie-technologies/'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292368_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292372_icon_soc-2.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/675211814eb5a7ea02c53dbe_HIPAA%20Compliant.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/673536fd56aafffebaa97a57_Technology_Partner_Select_Badge-p-500.png'
	StaticText Documentation
	link Getting started, url='https://artie.com/docs/start'
	link Tutorials, url='https://artie.com/docs/guides'
	link Trust report, url='https://trust.artie.com/'
	link Status page, url='https://artie.instatus.com/'
	StaticText Resources
	link Blog, url='https://www.artie.com/blogs'
	link Customers, url='https://www.artie.com/customer-stories'
	link Pricing, url='https://www.artie.com/pricing'
	link FAQ, url='https://www.artie.com/pricing#faq'
	StaticText Company
	link About, url='https://www.artie.com/about'
	link Contact, url='https://www.artie.com/contact'
	link GitHub, url='https://github.com/artie-labs/'
	StaticText Legal
	link Privacy policy, url='https://artie.com/docs/legal/privacy-policy'
	link Terms of service, url='https://artie.com/docs/legal/terms-of-service'
```
</details>



```
RootWebArea About, focused, url='https://www.artie.com/about'
	banner
		[29] link home, center=(428,44), url='https://www.artie.com/'
			image Artie logo, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/6690586b63f787ded1c849af_artie-logo.png'
		navigation
```
<details><summary>Show more</summary>

```
			[33] link About, center=(517,46), url='https://www.artie.com/about'
			[34] link Blog, center=(607,46), url='https://www.artie.com/blogs'
			[35] link Customers, center=(713,46), url='https://www.artie.com/customer-stories'
			[36] link Docs, center=(820,46), url='https://www.artie.com/docs/start'
			[37] link Pricing, center=(915,46), url='https://www.artie.com/pricing'
		[39] link Get started, center=(1455,46), url='https://www.artie.com/contact'
		[40] link Login, center=(1544,46), url='https://app.artie.com/login'
	heading We’re building the modern data ingestion platform
	StaticText They say data ingestion is complicated. We believe it doesn’t have to be.
	heading Our story
	StaticText 2016
	StaticText Hi, I’m Robin, co-founder and CTO of Artie. I was 22 when I built my first ingestion pipeline at scale. I was working in a startup in San Francisco where we handled enormous amounts of data (billions of events per day). As a startup, we had to keep the pipelines extremely efficient to save time and money.
	StaticText 2018
	StaticText The startup was acquired by Zendesk and I went on to build the foundations of Zendesk’s CRM offering. Change data capture (CDC) and Kafka was used heavily internally – it was such a big part of Zendesk that they developed and open sourced Maxwell, a CDC application that reads MySQL binlogs and writes data changes as JSON to Kafka, Kinesis, and other streaming platforms.
	StaticText 2021
	StaticText I eventually went to work at a real estate tech startup in San Francisco, where I felt firsthand how data ingestion lag and high number of data processing errors led to lower productivity of teams downstream of the warehouse. I saw it directly lead to higher operational costs and impact on our ability to build robust data products. It's hard to build a house when you have to constantly worry about its foundation.
	StaticText 2022
	StaticText Having used CDC in the past and knowing the benefits, I wanted to use it for data replication in order to minimize data latency. I tried a bunch of tools available in the market and was disappointed. So, I ended up architecting my own solution.
	StaticText 2022
	StaticText I had an MVP working and it felt like magic! But, the process was
	emphasis
		StaticText hard
	StaticText and there was still so much more to build. It quickly dawned on me that every company would need to address these concerns in order to build a robust streaming CDC pipeline.  How do I guarantee eventual consistency? How do I guarantee all data types are supported? How do I handle schema evolution? How do I handle stateful datasets? How should backfills be handled to ensure minimal load and no storage growth? What about telemetry?
	StaticText 2023
	StaticText I recruited my co-founder Jacqueline to help deal with everything else related to company building and go-to-market so I can focus on building the product. She got us into Y Combinator, got our first few dozen customers, and convinced world-class investors to join us on our journey.
	StaticText 2024
	StaticText We are even more excited in our mission to offer the fastest and most reliable database replication solution. As Joe Reis says, “The frequency of ingestion sets a ceiling on downstream frequency”. With Artie, our customers are now able to adopt all kinds of workloads that were previously unattainable, directly from their data warehouse.
	heading Founders
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66a3ff2f259cac29adbe740c_Robin-Jacqueline-p-800.png'
	heading Our culture
	button Sustainability > Growth, expanded=False, hasPopup='menu'
	navigation Sustainability > Growth
		StaticText Every decision we make should be geared towards improving long term durability, not short term growth. We should focus on building an excellent product that customers love to use, even 10+ years down the line.
		StaticText To build sustainability for customers, we should focus on making customers feel valued, even if it requires harder engineering work or comes at the expense of revenue. If it makes sense to help customers sync less data and close a smaller deal, we should do so without hesitation.
		StaticText Sustainability also applies to our team. Artie is only as good as its people. As we grow, we must maintain the quality of people by making sure that each new hire maintains or increases the average quality of the group. After a new hire joins for 3-6 months, we should ask ourselves if we would be devastated if they left – if we don’t, we should let them go.
	button Freedom & Ownership, expanded=False, hasPopup='menu'
	navigation Freedom & Ownership
		StaticText It’s important that people here create work that they’re proud of. If your work was made public, would you be happy with it? We are not a company that rewards people based on effort and hours worked. What matters is results and performance.
		StaticText We value freedom. This can come in many forms – one example is when people prefer to work. Some people are night owls and some are early birds. We want to allow people to perform when they’re at their best.
		StaticText We want high performers to work here, and high performers should feel strong ownership of their work and have the freedom to decide
		emphasis
			StaticText how
		StaticText they solve problems. No one should be micromanaged at Artie – great managers don’t enjoy micromanaging, and great people don’t enjoy being micromanaged. Micromanaging is a recipe for bad culture and low ownership.
	button Openness Without Ego, expanded=False, hasPopup='menu'
	navigation Openness Without Ego
		StaticText Even the best people have flaws or make mistakes. At Artie, everyone should feel comfortable giving feedback (to their peers and managers) or disagree with the path we’re going down. If an engineer is confused about our marketing direction, they should feel comfortable giving the marketing team feedback and explain why they disagree. The decision maker should listen to everyone’s opinion, but they have the final say. After the decision is made, they should explain why or why not feedback was incorporated.
		StaticText With that said, there will be disagreements. Not every decision will have 100% of the team on board. It’s important that we explain our thought process, learn to agree to disagree, and then fully commit to it as a team.
	button 1% Better Everyday, expanded=False, hasPopup='menu'
	navigation 1% Better Everyday
		StaticText Everyone should aim to get 1% better everyday, that’s a ~38x improvement over a year. It’s hard to fathom a 38x improvement over the course of a year, but it is very believable that we got 1% better everyday. If we focus on improving slightly every day, it will be shocking what we have achieved in a few years.
		StaticText Charlie Munger once said: “Spend each day trying to be a little wiser than you were when you woke up. Discharge your duties faithfully and well. Step by step you get ahead, but not necessarily in fast spurts. But you build discipline by preparing for fast spurts. Slug it out one inch at a time, day by day, and at the end of the day — if you live long enough — like most people, you will get out of life what you deserve.”
		StaticText Don’t be afraid to experiment and try new things. If it doesn’t work, you’re exactly where you would be otherwise. If it works, you’ve just made things infinitely better (or at a minimum 1% better).
	button Startup Mentality, expanded=False, hasPopup='menu'
	navigation Startup Mentality
		StaticText Don’t let perfect be the enemy of done. We move fast and have a strong bias towards action without compromising on quality. We are relentlessly resourceful and will do anything to get things done.
	button One Team, One Dream, expanded=False, hasPopup='menu'
	navigation One Team, One Dream
		StaticText The path to success is non-linear and things inevitably go wrong. When that happens, don’t assign blame and focus instead on how we can fix the issue as a team and prevent it in the future. We should operate under the assumption that people are making the best decisions based on information available at that time – sometimes the decision does not result in the outcome we expect, that’s ok. Additionally, while we have decision makers that make the final call to avoid decision paralysis, final decisions are ultimately a group effort because of our openness to feedback along the way.
		StaticText We value working in a collaborative environment where decisions are not made in silos. Make sure to be inclusive and aware that people have different backgrounds and experiences. The differences in perspective is critical to long term sustainable growth.
	StaticText Backed by world-class investors and operators
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66a3ff9916d2295543c782bf_yc-logo.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66a3ff9916d2295543c782c5_exponent-logo.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66a3ff9916d2295543c782e4_general-catalyst-logo.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66a3ff9916d2295543c782af_sancus-logo.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66a3ff9816d2295543c78293_banana-capital-logo.png'
	heading 10x better pipelines. This weekend.
	link Get started, url='https://www.artie.com/contact'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0be552abb4459f5aca_chevron-right-black.svg'
	link Talk to a founder, url='https://www.artie.com/contact'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0be552abb4459f5b17_chevron-right-white.svg'
	image, url='https://cdn.prod.website-files.com/66762bf6418642de486f1cc6/6687f9e4df3ac33cc807ef88_artie-logo.png'
	StaticText 220 Sansome Street, San Francisco, CA 94104
	link, url='https://x.com/artie_tech'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f2922d3_Vectors-Wrapper.svg'
	link, url='https://github.com/artie-labs/'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292342_Vectors-Wrapper.svg'
	link, url='https://artie.com/slack'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292314_Vectors-Wrapper.svg'
	link, url='https://www.linkedin.com/company/artie-technologies/'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292368_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292372_icon_soc-2.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/675211814eb5a7ea02c53dbe_HIPAA%20Compliant.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/673536fd56aafffebaa97a57_Technology_Partner_Select_Badge-p-500.png'
	StaticText Documentation
	link Getting started, url='https://artie.com/docs/start'
	link Tutorials, url='https://artie.com/docs/guides'
	link Trust report, url='https://trust.artie.com/'
	link Status page, url='https://artie.instatus.com/'
	StaticText Resources
	link Blog, url='https://www.artie.com/blogs'
	link Customers, url='https://www.artie.com/customer-stories'
	link Pricing, url='https://www.artie.com/pricing'
	link FAQ, url='https://www.artie.com/pricing#faq'
	StaticText Company
	link About, url='https://www.artie.com/about'
	link Contact, url='https://www.artie.com/contact'
	link GitHub, url='https://github.com/artie-labs/'
	StaticText Legal
	link Privacy policy, url='https://artie.com/docs/legal/privacy-policy'
	link Terms of service, url='https://artie.com/docs/legal/terms-of-service'
```
</details>

**Reasoning for action:** By clicking on the 'About' link, I initiate the process of exploring Artie's features and values as a company. This move is critical as the 'About' page typically provides insights into the company's mission, regulatory compliance, and standards, which are crucial for understanding how Artie's solutions may align with the user's needs regarding HIPAA compliance.

**Action:** click(42) # Click on the About link to learn more about the company.

**Change Description:** The browser navigated from the homepage of Artie to the 'About' page, displaying new headings and textual content about the company's story, culture, and values while retaining the navigation links and logo in the banner.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.artie.com/about

https://www.artie.com/blogs

**Content (before/after):** 

```
RootWebArea About, focused, url='https://www.artie.com/about'
	banner
		[29] link home, center=(428,44), url='https://www.artie.com/'
			image Artie logo, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/6690586b63f787ded1c849af_artie-logo.png'
		navigation
```
<details><summary>Show more</summary>

```
			[33] link About, center=(517,46), url='https://www.artie.com/about'
			[34] link Blog, center=(607,46), url='https://www.artie.com/blogs'
			[35] link Customers, center=(713,46), url='https://www.artie.com/customer-stories'
			[36] link Docs, center=(820,46), url='https://www.artie.com/docs/start'
			[37] link Pricing, center=(915,46), url='https://www.artie.com/pricing'
		[39] link Get started, center=(1455,46), url='https://www.artie.com/contact'
		[40] link Login, center=(1544,46), url='https://app.artie.com/login'
	heading We’re building the modern data ingestion platform
	StaticText They say data ingestion is complicated. We believe it doesn’t have to be.
	heading Our story
	StaticText 2016
	StaticText Hi, I’m Robin, co-founder and CTO of Artie. I was 22 when I built my first ingestion pipeline at scale. I was working in a startup in San Francisco where we handled enormous amounts of data (billions of events per day). As a startup, we had to keep the pipelines extremely efficient to save time and money.
	StaticText 2018
	StaticText The startup was acquired by Zendesk and I went on to build the foundations of Zendesk’s CRM offering. Change data capture (CDC) and Kafka was used heavily internally – it was such a big part of Zendesk that they developed and open sourced Maxwell, a CDC application that reads MySQL binlogs and writes data changes as JSON to Kafka, Kinesis, and other streaming platforms.
	StaticText 2021
	StaticText I eventually went to work at a real estate tech startup in San Francisco, where I felt firsthand how data ingestion lag and high number of data processing errors led to lower productivity of teams downstream of the warehouse. I saw it directly lead to higher operational costs and impact on our ability to build robust data products. It's hard to build a house when you have to constantly worry about its foundation.
	StaticText 2022
	StaticText Having used CDC in the past and knowing the benefits, I wanted to use it for data replication in order to minimize data latency. I tried a bunch of tools available in the market and was disappointed. So, I ended up architecting my own solution.
	StaticText 2022
	StaticText I had an MVP working and it felt like magic! But, the process was
	emphasis
		StaticText hard
	StaticText and there was still so much more to build. It quickly dawned on me that every company would need to address these concerns in order to build a robust streaming CDC pipeline.  How do I guarantee eventual consistency? How do I guarantee all data types are supported? How do I handle schema evolution? How do I handle stateful datasets? How should backfills be handled to ensure minimal load and no storage growth? What about telemetry?
	StaticText 2023
	StaticText I recruited my co-founder Jacqueline to help deal with everything else related to company building and go-to-market so I can focus on building the product. She got us into Y Combinator, got our first few dozen customers, and convinced world-class investors to join us on our journey.
	StaticText 2024
	StaticText We are even more excited in our mission to offer the fastest and most reliable database replication solution. As Joe Reis says, “The frequency of ingestion sets a ceiling on downstream frequency”. With Artie, our customers are now able to adopt all kinds of workloads that were previously unattainable, directly from their data warehouse.
	heading Founders
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66a3ff2f259cac29adbe740c_Robin-Jacqueline-p-800.png'
	heading Our culture
	button Sustainability > Growth, expanded=False, hasPopup='menu'
	navigation Sustainability > Growth
		StaticText Every decision we make should be geared towards improving long term durability, not short term growth. We should focus on building an excellent product that customers love to use, even 10+ years down the line.
		StaticText To build sustainability for customers, we should focus on making customers feel valued, even if it requires harder engineering work or comes at the expense of revenue. If it makes sense to help customers sync less data and close a smaller deal, we should do so without hesitation.
		StaticText Sustainability also applies to our team. Artie is only as good as its people. As we grow, we must maintain the quality of people by making sure that each new hire maintains or increases the average quality of the group. After a new hire joins for 3-6 months, we should ask ourselves if we would be devastated if they left – if we don’t, we should let them go.
	button Freedom & Ownership, expanded=False, hasPopup='menu'
	navigation Freedom & Ownership
		StaticText It’s important that people here create work that they’re proud of. If your work was made public, would you be happy with it? We are not a company that rewards people based on effort and hours worked. What matters is results and performance.
		StaticText We value freedom. This can come in many forms – one example is when people prefer to work. Some people are night owls and some are early birds. We want to allow people to perform when they’re at their best.
		StaticText We want high performers to work here, and high performers should feel strong ownership of their work and have the freedom to decide
		emphasis
			StaticText how
		StaticText they solve problems. No one should be micromanaged at Artie – great managers don’t enjoy micromanaging, and great people don’t enjoy being micromanaged. Micromanaging is a recipe for bad culture and low ownership.
	button Openness Without Ego, expanded=False, hasPopup='menu'
	navigation Openness Without Ego
		StaticText Even the best people have flaws or make mistakes. At Artie, everyone should feel comfortable giving feedback (to their peers and managers) or disagree with the path we’re going down. If an engineer is confused about our marketing direction, they should feel comfortable giving the marketing team feedback and explain why they disagree. The decision maker should listen to everyone’s opinion, but they have the final say. After the decision is made, they should explain why or why not feedback was incorporated.
		StaticText With that said, there will be disagreements. Not every decision will have 100% of the team on board. It’s important that we explain our thought process, learn to agree to disagree, and then fully commit to it as a team.
	button 1% Better Everyday, expanded=False, hasPopup='menu'
	navigation 1% Better Everyday
		StaticText Everyone should aim to get 1% better everyday, that’s a ~38x improvement over a year. It’s hard to fathom a 38x improvement over the course of a year, but it is very believable that we got 1% better everyday. If we focus on improving slightly every day, it will be shocking what we have achieved in a few years.
		StaticText Charlie Munger once said: “Spend each day trying to be a little wiser than you were when you woke up. Discharge your duties faithfully and well. Step by step you get ahead, but not necessarily in fast spurts. But you build discipline by preparing for fast spurts. Slug it out one inch at a time, day by day, and at the end of the day — if you live long enough — like most people, you will get out of life what you deserve.”
		StaticText Don’t be afraid to experiment and try new things. If it doesn’t work, you’re exactly where you would be otherwise. If it works, you’ve just made things infinitely better (or at a minimum 1% better).
	button Startup Mentality, expanded=False, hasPopup='menu'
	navigation Startup Mentality
		StaticText Don’t let perfect be the enemy of done. We move fast and have a strong bias towards action without compromising on quality. We are relentlessly resourceful and will do anything to get things done.
	button One Team, One Dream, expanded=False, hasPopup='menu'
	navigation One Team, One Dream
		StaticText The path to success is non-linear and things inevitably go wrong. When that happens, don’t assign blame and focus instead on how we can fix the issue as a team and prevent it in the future. We should operate under the assumption that people are making the best decisions based on information available at that time – sometimes the decision does not result in the outcome we expect, that’s ok. Additionally, while we have decision makers that make the final call to avoid decision paralysis, final decisions are ultimately a group effort because of our openness to feedback along the way.
		StaticText We value working in a collaborative environment where decisions are not made in silos. Make sure to be inclusive and aware that people have different backgrounds and experiences. The differences in perspective is critical to long term sustainable growth.
	StaticText Backed by world-class investors and operators
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66a3ff9916d2295543c782bf_yc-logo.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66a3ff9916d2295543c782c5_exponent-logo.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66a3ff9916d2295543c782e4_general-catalyst-logo.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66a3ff9916d2295543c782af_sancus-logo.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66a3ff9816d2295543c78293_banana-capital-logo.png'
	heading 10x better pipelines. This weekend.
	link Get started, url='https://www.artie.com/contact'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0be552abb4459f5aca_chevron-right-black.svg'
	link Talk to a founder, url='https://www.artie.com/contact'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0be552abb4459f5b17_chevron-right-white.svg'
	image, url='https://cdn.prod.website-files.com/66762bf6418642de486f1cc6/6687f9e4df3ac33cc807ef88_artie-logo.png'
	StaticText 220 Sansome Street, San Francisco, CA 94104
	link, url='https://x.com/artie_tech'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f2922d3_Vectors-Wrapper.svg'
	link, url='https://github.com/artie-labs/'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292342_Vectors-Wrapper.svg'
	link, url='https://artie.com/slack'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292314_Vectors-Wrapper.svg'
	link, url='https://www.linkedin.com/company/artie-technologies/'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292368_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292372_icon_soc-2.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/675211814eb5a7ea02c53dbe_HIPAA%20Compliant.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/673536fd56aafffebaa97a57_Technology_Partner_Select_Badge-p-500.png'
	StaticText Documentation
	link Getting started, url='https://artie.com/docs/start'
	link Tutorials, url='https://artie.com/docs/guides'
	link Trust report, url='https://trust.artie.com/'
	link Status page, url='https://artie.instatus.com/'
	StaticText Resources
	link Blog, url='https://www.artie.com/blogs'
	link Customers, url='https://www.artie.com/customer-stories'
	link Pricing, url='https://www.artie.com/pricing'
	link FAQ, url='https://www.artie.com/pricing#faq'
	StaticText Company
	link About, url='https://www.artie.com/about'
	link Contact, url='https://www.artie.com/contact'
	link GitHub, url='https://github.com/artie-labs/'
	StaticText Legal
	link Privacy policy, url='https://artie.com/docs/legal/privacy-policy'
	link Terms of service, url='https://artie.com/docs/legal/terms-of-service'
```
</details>



```
RootWebArea Artie Blog - latest product updates and data ideas, focused, url='https://www.artie.com/blogs'
	banner
		[36] link home, center=(428,44), url='https://www.artie.com/'
			image Artie logo, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/6690586b63f787ded1c849af_artie-logo.png'
		navigation
```
<details><summary>Show more</summary>

```
			[40] link About, center=(517,46), url='https://www.artie.com/about'
			[41] link Blog, center=(607,46), url='https://www.artie.com/blogs'
			[42] link Customers, center=(713,46), url='https://www.artie.com/customer-stories'
			[43] link Docs, center=(820,46), url='https://www.artie.com/docs/start'
			[44] link Pricing, center=(915,46), url='https://www.artie.com/pricing'
		[46] link Get started, center=(1455,46), url='https://www.artie.com/contact'
		[47] link Login, center=(1544,46), url='https://app.artie.com/login'
	main
		heading Blogs
	list
		listitem
			[69] link December 9, 2024 Artie Achieves HIPAA Compliance Artie achieves HIPAA compliance Jacqueline Cheong Co-founder & CEO, center=(960,460), inner_text=December 9, 2024
Artie Achieves HIPAA Compliance

Artie achieves HIPAA compliance

Jacqueline Cheong
Co-founder & CEO, url='https://www.artie.com/blogs/artie-achieves-hipaa-compliance'
				StaticText December 9, 2024
				heading Artie Achieves HIPAA Compliance
				paragraph
					StaticText Artie achieves HIPAA compliance
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			[87] link September 22, 2024 Postgres Write-Ahead Logs This is the second part of our deep-dive into Postgres logical replication. In this part, we will focus on Postgres Write-Ahead Logs (WAL). Madison Schott Guest contributor, center=(960,710), inner_text=September 22, 2024
Postgres Write-Ahead Logs

This is the second part of our deep-dive into Postgres logical replication. In this part, we will focus on Postgres Write-Ahead Logs (WAL).

Madison Schott
Guest contributor, url='https://www.artie.com/blogs/postgres-write-ahead-logs'
				StaticText September 22, 2024
				heading Postgres Write-Ahead Logs
				paragraph
					StaticText This is the second part of our deep-dive into Postgres logical replication. In this part, we will focus on Postgres Write-Ahead Logs (WAL).
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/66a67dbfda21c45e2c75c39d_madison-p-500.jpeg'
				StaticText Madison Schott
				StaticText Guest contributor
		listitem
			[105] link August 6, 2024 MySQL Cascading Changes and Why You Shouldn't Use Them Cascading changes is a feature within MySQL that makes it easy for related objects to be updated and deleted. In this blog, we'll talk about how it works and why you you shouldn't use them in a production environment. Robin Tang Co-founder & CTO, center=(960,988), inner_text=August 6, 2024
MySQL Cascading Changes and Why You Shouldn't Use Them

Cascading changes is a feature within MySQL that makes it easy for related objects to be updated and deleted. In this blog, we'll talk about how it works and why you you shouldn't use them in a production environment.

Robin Tang
Co-founder & CTO, url='https://www.artie.com/blogs/mysql-cascading-changes-and-why-you-shouldnt-use-them'
				StaticText August 6, 2024
				heading MySQL Cascading Changes and Why You Shouldn't Use Them
				paragraph
					StaticText Cascading changes is a feature within MySQL that makes it easy for related objects to be updated and deleted. In this blog, we'll talk about how it works and why you you shouldn't use them in a production environment.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65947b59a8896bc225e1eeb0_Robin%20Tang.webp'
				StaticText Robin Tang
				StaticText Co-founder & CTO
		listitem
			link July 29, 2024 How to choose a data warehouse Your data warehouse is the central location of all analytics processes, so it is important that you choose the right one. Whether you are building out your data stack from scratch, or looking to replace your current warehouse, we will walk you through the pros and cons of Snowflake vs Redshift vs BigQuery vs ClickHouse. Madison Schott Guest contributor, url='https://www.artie.com/blogs/how-to-choose-a-data-warehouse'
				StaticText July 29, 2024
				heading How to choose a data warehouse
				paragraph
					StaticText Your data warehouse is the central location of all analytics processes, so it is important that you choose the right one. Whether you are building out your data stack from scratch, or looking to replace your current warehouse, we will walk you through the pros and cons of Snowflake vs Redshift vs BigQuery vs ClickHouse.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/66a67dbfda21c45e2c75c39d_madison-p-500.jpeg'
				StaticText Madison Schott
				StaticText Guest contributor
		listitem
			link June 21, 2024 4 DMS Alternatives in 2024 AWS Data Migration Service (DMS) was launched in 2016 as a database migration solution to help companies move database and analytics workloads to the AWS environment. AWS DMS supports migration from database sources that are on-premise, in Amazon EC2, and in Amazon RDS using change data capture (CDC) replication. Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/4-dms-alternatives-in-2024'
				StaticText June 21, 2024
				heading 4 DMS Alternatives in 2024
				paragraph
					StaticText AWS Data Migration Service (DMS) was launched in 2016 as a database migration solution to help companies move database and analytics workloads to the AWS environment. AWS DMS supports migration from database sources that are on-premise, in Amazon EC2, and in Amazon RDS using change data capture (CDC) replication.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link June 10, 2024 Postgres Table Replica Identity This is a first part of our deep-dive into Postgres logical replication. In this part, we will focus on the REPLICA IDENTITY property of a table and how it affects logical replication. Robin Tang Co-founder & CTO, url='https://www.artie.com/blogs/postgres-table-replica-identity'
				StaticText June 10, 2024
				heading Postgres Table Replica Identity
				paragraph
					StaticText This is a first part of our deep-dive into Postgres logical replication. In this part, we will focus on the REPLICA IDENTITY property of a table and how it affects logical replication.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65947b59a8896bc225e1eeb0_Robin%20Tang.webp'
				StaticText Robin Tang
				StaticText Co-founder & CTO
		listitem
			link May 13, 2024 8 Best Fivetran Alternatives in 2024 Fivetran was founded in 2012 and is one of the most popular data integration solutions. In this article, we explore some of the top alternatives to Fivetran currently available in the market, providing options that cater to various needs and preferences. Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/fivetran-alternatives'
				StaticText May 13, 2024
				heading 8 Best Fivetran Alternatives in 2024
				paragraph
					StaticText Fivetran was founded in 2012 and is one of the most popular data integration solutions. In this article, we explore some of the top alternatives to Fivetran currently available in the market, providing options that cater to various needs and preferences.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link April 10, 2024 Not All CDC Pipelines Are Created Equal There are many ways to leverage change data capture (CDC) to perform data replication from databases to external destinations, like data warehouses, data lakes, and other databases. In this blog, we run through the design principles we followed when building Artie and reasoning behind our architectural decisions. Robin Tang Co-founder & CTO, url='https://www.artie.com/blogs/not-all-cdc-pipelines-are-created-equal'
				StaticText April 10, 2024
				heading Not All CDC Pipelines Are Created Equal
				paragraph
					StaticText There are many ways to leverage change data capture (CDC) to perform data replication from databases to external destinations, like data warehouses, data lakes, and other databases. In this blog, we run through the design principles we followed when building Artie and reasoning behind our architectural decisions.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65947b59a8896bc225e1eeb0_Robin%20Tang.webp'
				StaticText Robin Tang
				StaticText Co-founder & CTO
		listitem
			link February 28, 2024 Artie Achieves Select Tier Partner Status with Snowflake Artie today announced that it has achieved Select tier partner status from Snowflake, the Data Cloud company. As a Select partner, Artie will accelerate the digital transformation of its joint customers who can fully leverage the performance, flexibility, and near-infinite scalability of the Snowflake Data Cloud. Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/artie-achieves-select-tier-partner-status-with-snowflake'
				StaticText February 28, 2024
				heading Artie Achieves Select Tier Partner Status with Snowflake
				paragraph
					StaticText Artie today announced that it has achieved Select tier partner status from Snowflake, the Data Cloud company. As a Select partner, Artie will accelerate the digital transformation of its joint customers who can fully leverage the performance, flexibility, and near-infinite scalability of the Snowflake Data Cloud.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link February 14, 2024 Artie Raises $3.3M Seed Round from Exponent Founders Capital, General Catalyst, and Y Combinator to Revolutionize Database Replication We are excited to announce that we have raised a $3.3M Seed round led by Exponent Founders Capital with participation from General Catalyst, Y Combinator, and many angel investors including Benn Stancil, Lenny Rachitsky, and Arash Ferdowsi.  Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/artie-raises-3-3m-seed-round-from-exponent-founders-capital-general-catalyst-and-y-combinator-to-revolutionize-database-replication'
				StaticText February 14, 2024
				heading Artie Raises $3.3M Seed Round from Exponent Founders Capital, General Catalyst, and Y Combinator to Revolutionize Database Replication
				paragraph
					StaticText We are excited to announce that we have raised a $3.3M Seed round led by Exponent Founders Capital with participation from General Catalyst, Y Combinator, and many angel investors including Benn Stancil, Lenny Rachitsky, and Arash Ferdowsi.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link January 29, 2024 History Table Artie’s History Table feature creates a separate table that stores all historical states of the records. Every insert, update, and delete operation from the database’s CDC log is recorded with a timestamp and the type of operation that was performed. Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/history-table'
				StaticText January 29, 2024
				heading History Table
				paragraph
					StaticText Artie’s History Table feature creates a separate table that stores all historical states of the records. Every insert, update, and delete operation from the database’s CDC log is recorded with a timestamp and the type of operation that was performed.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link January 15, 2024 Introduction to Database Replication Database replication is a key component in data management, involving the creation of multiple copies of a database across different servers or locations. This process ensures data redundancy, reliability, and performance. Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/introduction-to-database-replication'
				StaticText January 15, 2024
				heading Introduction to Database Replication
				paragraph
					StaticText Database replication is a key component in data management, involving the creation of multiple copies of a database across different servers or locations. This process ensures data redundancy, reliability, and performance.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link November 27, 2023 Introducing Artie’s Analytics Portal Analytics Portal offers real-time observability into database pipelines and peripheral infrastructure, so companies can increase understanding of how systems impact one another, reduce downtime/debug issues faster, and generate proactive alerts to maintain robust infrastructure. Robin Tang Co-founder & CTO, url='https://www.artie.com/blogs/introducing-arties-analytics-portal'
				StaticText November 27, 2023
				heading Introducing Artie’s Analytics Portal
				paragraph
					StaticText Analytics Portal offers real-time observability into database pipelines and peripheral infrastructure, so companies can increase understanding of how systems impact one another, reduce downtime/debug issues faster, and generate proactive alerts to maintain robust infrastructure.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65947b59a8896bc225e1eeb0_Robin%20Tang.webp'
				StaticText Robin Tang
				StaticText Co-founder & CTO
		listitem
			link November 15, 2023 Best Practices on Running Redshift at Scale Configuring Redshift can be very confusing. There are hundreds of knobs that customers can tune within Redshift, which unfortunately means that teams are often stuck with low performing Redshift clusters because it wasn't configured correctly. Robin Tang Co-founder & CTO, url='https://www.artie.com/blogs/best-practices-on-running-redshift-at-scale'
				StaticText November 15, 2023
				heading Best Practices on Running Redshift at Scale
				paragraph
					StaticText Configuring Redshift can be very confusing. There are hundreds of knobs that customers can tune within Redshift, which unfortunately means that teams are often stuck with low performing Redshift clusters because it wasn't configured correctly.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65947b59a8896bc225e1eeb0_Robin%20Tang.webp'
				StaticText Robin Tang
				StaticText Co-founder & CTO
		listitem
			link November 13, 2023 Artie Is SOC 2 Type II Compliant SOC 2 or Service Organization Controls 2 is a framework that is governed by the American Institute of Certified Public Accountants (AICPA). Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/artie-is-soc-2-type-ii-compliant'
				StaticText November 13, 2023
				heading Artie Is SOC 2 Type II Compliant
				paragraph
					StaticText SOC 2 or Service Organization Controls 2 is a framework that is governed by the American Institute of Certified Public Accountants (AICPA).
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link September 12, 2023 Preventing WAL Growth on Postgres DB Running on AWS RDS For anyone using Postgres on AWS RDS, it’s possible you’ve run into the scenario of an idle or unused dev database suddenly running out of memory and causing replication slot overflow. This guide explains why replication slot overflow happens and how to prevent it. Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/preventing-wal-growth-on-postgres-db-running-on-aws-rds'
				StaticText September 12, 2023
				heading Preventing WAL Growth on Postgres DB Running on AWS RDS
				paragraph
					StaticText For anyone using Postgres on AWS RDS, it’s possible you’ve run into the scenario of an idle or unused dev database suddenly running out of memory and causing replication slot overflow. This guide explains why replication slot overflow happens and how to prevent it.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link July 26, 2023 Snowflake Eco Mode Eco Mode - minimize time and maximize resource utilization. Eco Mode is an advanced setting that allows customers to define peak and off-peak hours and configure various sync time intervals.  Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/snowflake-eco-mode'
				StaticText July 26, 2023
				heading Snowflake Eco Mode
				paragraph
					StaticText Eco Mode - minimize time and maximize resource utilization. Eco Mode is an advanced setting that allows customers to define peak and off-peak hours and configure various sync time intervals.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link April 11, 2023 The Inevitability and Power of Real-Time Data The ability to shorten the data feedback loop and act while data is still relevant is incredibly valuable. In order to lower response times to data insights, companies require a system that can alert in seconds or minutes rather than hours. Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/the-inevitability-and-power-of-realtime-data'
				StaticText April 11, 2023
				heading The Inevitability and Power of Real-Time Data
				paragraph
					StaticText The ability to shorten the data feedback loop and act while data is still relevant is incredibly valuable. In order to lower response times to data insights, companies require a system that can alert in seconds or minutes rather than hours.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link February 27, 2023 Why ELTs Are Here to Stay ELTs greatly simplify and streamline the data integration process. It helps free up your data engineering team to work on data pipeline improvements and unlock new data sources. Robin Tang Co-founder & CTO, url='https://www.artie.com/blogs/why-elts-are-here-to-stay'
				StaticText February 27, 2023
				heading Why ELTs Are Here to Stay
				paragraph
					StaticText ELTs greatly simplify and streamline the data integration process. It helps free up your data engineering team to work on data pipeline improvements and unlock new data sources.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65947b59a8896bc225e1eeb0_Robin%20Tang.webp'
				StaticText Robin Tang
				StaticText Co-founder & CTO
		listitem
			link January 30, 2023 What Are the Differences Between OLTP and OLAP Databases? When differentiating between databases, one key characteristic is whether the database is OLTP or OLAP. We will explore what they are, key differences, and go through some real-world examples in this blog post. Robin Tang Co-founder & CTO, url='https://www.artie.com/blogs/what-are-the-differences-between-oltp-and-olap-databases'
				StaticText January 30, 2023
				heading What Are the Differences Between OLTP and OLAP Databases?
				paragraph
					StaticText When differentiating between databases, one key characteristic is whether the database is OLTP or OLAP. We will explore what they are, key differences, and go through some real-world examples in this blog post.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65947b59a8896bc225e1eeb0_Robin%20Tang.webp'
				StaticText Robin Tang
				StaticText Co-founder & CTO
		listitem
			link January 17, 2023 Introducing Artie Transfer Artie leverages change data capture (CDC) and stream processing to sync databases and data warehouses in real-time, enabling sub-minute latency and reducing compute costs. Robin Tang Co-founder & CTO, url='https://www.artie.com/blogs/introducing-artie-transfer'
				StaticText January 17, 2023
				heading Introducing Artie Transfer
				paragraph
					StaticText Artie leverages change data capture (CDC) and stream processing to sync databases and data warehouses in real-time, enabling sub-minute latency and reducing compute costs.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65947b59a8896bc225e1eeb0_Robin%20Tang.webp'
				StaticText Robin Tang
				StaticText Co-founder & CTO
	image, url='https://cdn.prod.website-files.com/66762bf6418642de486f1cc6/6687f9e4df3ac33cc807ef88_artie-logo.png'
	StaticText 220 Sansome Street, San Francisco, CA 94104
	link, url='https://x.com/artie_tech'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f2922d3_Vectors-Wrapper.svg'
	link, url='https://github.com/artie-labs/'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292342_Vectors-Wrapper.svg'
	link, url='https://artie.com/slack'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292314_Vectors-Wrapper.svg'
	link, url='https://www.linkedin.com/company/artie-technologies/'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292368_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292372_icon_soc-2.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/675211814eb5a7ea02c53dbe_HIPAA%20Compliant.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/673536fd56aafffebaa97a57_Technology_Partner_Select_Badge-p-500.png'
	StaticText Documentation
	link Getting started, url='https://artie.com/docs/start'
	link Tutorials, url='https://artie.com/docs/guides'
	link Trust report, url='https://trust.artie.com/'
	link Status page, url='https://artie.instatus.com/'
	StaticText Resources
	link Blog, url='https://www.artie.com/blogs'
	link Customers, url='https://www.artie.com/customer-stories'
	link Pricing, url='https://www.artie.com/pricing'
	link FAQ, url='https://www.artie.com/pricing#faq'
	StaticText Company
	link About, url='https://www.artie.com/about'
	link Contact, url='https://www.artie.com/contact'
	link GitHub, url='https://github.com/artie-labs/'
	StaticText Legal
	link Privacy policy, url='https://artie.com/docs/legal/privacy-policy'
	link Terms of service, url='https://artie.com/docs/legal/terms-of-service'
```
</details>

**Reasoning for action:** I need to access the Blog page in order to locate the post that discusses HIPAA compliance features, which is essential for understanding how Artie's solutions align with regulatory needs. By clicking the Blog link, I am advancing towards finding the relevant content that addresses the user's inquiry.

**Action:** click(34) # Click on the Blog link to explore articles related to Artie.

**Change Description:** The browser changed from the 'About' page to the 'Blog' page of Artie, updating the title to 'Artie Blog - latest product updates and data ideas', and displaying a list of recent blog articles with their respective headings, dates, authors, and associated images.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.artie.com/blogs

https://www.artie.com/blogs/artie-achieves-hipaa-compliance

**Content (before/after):** 

```
RootWebArea Artie Blog - latest product updates and data ideas, focused, url='https://www.artie.com/blogs'
	banner
		[36] link home, center=(428,44), url='https://www.artie.com/'
			image Artie logo, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/6690586b63f787ded1c849af_artie-logo.png'
		navigation
```
<details><summary>Show more</summary>

```
			[40] link About, center=(517,46), url='https://www.artie.com/about'
			[41] link Blog, center=(607,46), url='https://www.artie.com/blogs'
			[42] link Customers, center=(713,46), url='https://www.artie.com/customer-stories'
			[43] link Docs, center=(820,46), url='https://www.artie.com/docs/start'
			[44] link Pricing, center=(915,46), url='https://www.artie.com/pricing'
		[46] link Get started, center=(1455,46), url='https://www.artie.com/contact'
		[47] link Login, center=(1544,46), url='https://app.artie.com/login'
	main
		heading Blogs
	list
		listitem
			[69] link December 9, 2024 Artie Achieves HIPAA Compliance Artie achieves HIPAA compliance Jacqueline Cheong Co-founder & CEO, center=(960,460), inner_text=December 9, 2024
Artie Achieves HIPAA Compliance

Artie achieves HIPAA compliance

Jacqueline Cheong
Co-founder & CEO, url='https://www.artie.com/blogs/artie-achieves-hipaa-compliance'
				StaticText December 9, 2024
				heading Artie Achieves HIPAA Compliance
				paragraph
					StaticText Artie achieves HIPAA compliance
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			[87] link September 22, 2024 Postgres Write-Ahead Logs This is the second part of our deep-dive into Postgres logical replication. In this part, we will focus on Postgres Write-Ahead Logs (WAL). Madison Schott Guest contributor, center=(960,710), inner_text=September 22, 2024
Postgres Write-Ahead Logs

This is the second part of our deep-dive into Postgres logical replication. In this part, we will focus on Postgres Write-Ahead Logs (WAL).

Madison Schott
Guest contributor, url='https://www.artie.com/blogs/postgres-write-ahead-logs'
				StaticText September 22, 2024
				heading Postgres Write-Ahead Logs
				paragraph
					StaticText This is the second part of our deep-dive into Postgres logical replication. In this part, we will focus on Postgres Write-Ahead Logs (WAL).
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/66a67dbfda21c45e2c75c39d_madison-p-500.jpeg'
				StaticText Madison Schott
				StaticText Guest contributor
		listitem
			[105] link August 6, 2024 MySQL Cascading Changes and Why You Shouldn't Use Them Cascading changes is a feature within MySQL that makes it easy for related objects to be updated and deleted. In this blog, we'll talk about how it works and why you you shouldn't use them in a production environment. Robin Tang Co-founder & CTO, center=(960,988), inner_text=August 6, 2024
MySQL Cascading Changes and Why You Shouldn't Use Them

Cascading changes is a feature within MySQL that makes it easy for related objects to be updated and deleted. In this blog, we'll talk about how it works and why you you shouldn't use them in a production environment.

Robin Tang
Co-founder & CTO, url='https://www.artie.com/blogs/mysql-cascading-changes-and-why-you-shouldnt-use-them'
				StaticText August 6, 2024
				heading MySQL Cascading Changes and Why You Shouldn't Use Them
				paragraph
					StaticText Cascading changes is a feature within MySQL that makes it easy for related objects to be updated and deleted. In this blog, we'll talk about how it works and why you you shouldn't use them in a production environment.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65947b59a8896bc225e1eeb0_Robin%20Tang.webp'
				StaticText Robin Tang
				StaticText Co-founder & CTO
		listitem
			link July 29, 2024 How to choose a data warehouse Your data warehouse is the central location of all analytics processes, so it is important that you choose the right one. Whether you are building out your data stack from scratch, or looking to replace your current warehouse, we will walk you through the pros and cons of Snowflake vs Redshift vs BigQuery vs ClickHouse. Madison Schott Guest contributor, url='https://www.artie.com/blogs/how-to-choose-a-data-warehouse'
				StaticText July 29, 2024
				heading How to choose a data warehouse
				paragraph
					StaticText Your data warehouse is the central location of all analytics processes, so it is important that you choose the right one. Whether you are building out your data stack from scratch, or looking to replace your current warehouse, we will walk you through the pros and cons of Snowflake vs Redshift vs BigQuery vs ClickHouse.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/66a67dbfda21c45e2c75c39d_madison-p-500.jpeg'
				StaticText Madison Schott
				StaticText Guest contributor
		listitem
			link June 21, 2024 4 DMS Alternatives in 2024 AWS Data Migration Service (DMS) was launched in 2016 as a database migration solution to help companies move database and analytics workloads to the AWS environment. AWS DMS supports migration from database sources that are on-premise, in Amazon EC2, and in Amazon RDS using change data capture (CDC) replication. Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/4-dms-alternatives-in-2024'
				StaticText June 21, 2024
				heading 4 DMS Alternatives in 2024
				paragraph
					StaticText AWS Data Migration Service (DMS) was launched in 2016 as a database migration solution to help companies move database and analytics workloads to the AWS environment. AWS DMS supports migration from database sources that are on-premise, in Amazon EC2, and in Amazon RDS using change data capture (CDC) replication.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link June 10, 2024 Postgres Table Replica Identity This is a first part of our deep-dive into Postgres logical replication. In this part, we will focus on the REPLICA IDENTITY property of a table and how it affects logical replication. Robin Tang Co-founder & CTO, url='https://www.artie.com/blogs/postgres-table-replica-identity'
				StaticText June 10, 2024
				heading Postgres Table Replica Identity
				paragraph
					StaticText This is a first part of our deep-dive into Postgres logical replication. In this part, we will focus on the REPLICA IDENTITY property of a table and how it affects logical replication.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65947b59a8896bc225e1eeb0_Robin%20Tang.webp'
				StaticText Robin Tang
				StaticText Co-founder & CTO
		listitem
			link May 13, 2024 8 Best Fivetran Alternatives in 2024 Fivetran was founded in 2012 and is one of the most popular data integration solutions. In this article, we explore some of the top alternatives to Fivetran currently available in the market, providing options that cater to various needs and preferences. Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/fivetran-alternatives'
				StaticText May 13, 2024
				heading 8 Best Fivetran Alternatives in 2024
				paragraph
					StaticText Fivetran was founded in 2012 and is one of the most popular data integration solutions. In this article, we explore some of the top alternatives to Fivetran currently available in the market, providing options that cater to various needs and preferences.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link April 10, 2024 Not All CDC Pipelines Are Created Equal There are many ways to leverage change data capture (CDC) to perform data replication from databases to external destinations, like data warehouses, data lakes, and other databases. In this blog, we run through the design principles we followed when building Artie and reasoning behind our architectural decisions. Robin Tang Co-founder & CTO, url='https://www.artie.com/blogs/not-all-cdc-pipelines-are-created-equal'
				StaticText April 10, 2024
				heading Not All CDC Pipelines Are Created Equal
				paragraph
					StaticText There are many ways to leverage change data capture (CDC) to perform data replication from databases to external destinations, like data warehouses, data lakes, and other databases. In this blog, we run through the design principles we followed when building Artie and reasoning behind our architectural decisions.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65947b59a8896bc225e1eeb0_Robin%20Tang.webp'
				StaticText Robin Tang
				StaticText Co-founder & CTO
		listitem
			link February 28, 2024 Artie Achieves Select Tier Partner Status with Snowflake Artie today announced that it has achieved Select tier partner status from Snowflake, the Data Cloud company. As a Select partner, Artie will accelerate the digital transformation of its joint customers who can fully leverage the performance, flexibility, and near-infinite scalability of the Snowflake Data Cloud. Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/artie-achieves-select-tier-partner-status-with-snowflake'
				StaticText February 28, 2024
				heading Artie Achieves Select Tier Partner Status with Snowflake
				paragraph
					StaticText Artie today announced that it has achieved Select tier partner status from Snowflake, the Data Cloud company. As a Select partner, Artie will accelerate the digital transformation of its joint customers who can fully leverage the performance, flexibility, and near-infinite scalability of the Snowflake Data Cloud.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link February 14, 2024 Artie Raises $3.3M Seed Round from Exponent Founders Capital, General Catalyst, and Y Combinator to Revolutionize Database Replication We are excited to announce that we have raised a $3.3M Seed round led by Exponent Founders Capital with participation from General Catalyst, Y Combinator, and many angel investors including Benn Stancil, Lenny Rachitsky, and Arash Ferdowsi.  Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/artie-raises-3-3m-seed-round-from-exponent-founders-capital-general-catalyst-and-y-combinator-to-revolutionize-database-replication'
				StaticText February 14, 2024
				heading Artie Raises $3.3M Seed Round from Exponent Founders Capital, General Catalyst, and Y Combinator to Revolutionize Database Replication
				paragraph
					StaticText We are excited to announce that we have raised a $3.3M Seed round led by Exponent Founders Capital with participation from General Catalyst, Y Combinator, and many angel investors including Benn Stancil, Lenny Rachitsky, and Arash Ferdowsi.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link January 29, 2024 History Table Artie’s History Table feature creates a separate table that stores all historical states of the records. Every insert, update, and delete operation from the database’s CDC log is recorded with a timestamp and the type of operation that was performed. Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/history-table'
				StaticText January 29, 2024
				heading History Table
				paragraph
					StaticText Artie’s History Table feature creates a separate table that stores all historical states of the records. Every insert, update, and delete operation from the database’s CDC log is recorded with a timestamp and the type of operation that was performed.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link January 15, 2024 Introduction to Database Replication Database replication is a key component in data management, involving the creation of multiple copies of a database across different servers or locations. This process ensures data redundancy, reliability, and performance. Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/introduction-to-database-replication'
				StaticText January 15, 2024
				heading Introduction to Database Replication
				paragraph
					StaticText Database replication is a key component in data management, involving the creation of multiple copies of a database across different servers or locations. This process ensures data redundancy, reliability, and performance.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link November 27, 2023 Introducing Artie’s Analytics Portal Analytics Portal offers real-time observability into database pipelines and peripheral infrastructure, so companies can increase understanding of how systems impact one another, reduce downtime/debug issues faster, and generate proactive alerts to maintain robust infrastructure. Robin Tang Co-founder & CTO, url='https://www.artie.com/blogs/introducing-arties-analytics-portal'
				StaticText November 27, 2023
				heading Introducing Artie’s Analytics Portal
				paragraph
					StaticText Analytics Portal offers real-time observability into database pipelines and peripheral infrastructure, so companies can increase understanding of how systems impact one another, reduce downtime/debug issues faster, and generate proactive alerts to maintain robust infrastructure.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65947b59a8896bc225e1eeb0_Robin%20Tang.webp'
				StaticText Robin Tang
				StaticText Co-founder & CTO
		listitem
			link November 15, 2023 Best Practices on Running Redshift at Scale Configuring Redshift can be very confusing. There are hundreds of knobs that customers can tune within Redshift, which unfortunately means that teams are often stuck with low performing Redshift clusters because it wasn't configured correctly. Robin Tang Co-founder & CTO, url='https://www.artie.com/blogs/best-practices-on-running-redshift-at-scale'
				StaticText November 15, 2023
				heading Best Practices on Running Redshift at Scale
				paragraph
					StaticText Configuring Redshift can be very confusing. There are hundreds of knobs that customers can tune within Redshift, which unfortunately means that teams are often stuck with low performing Redshift clusters because it wasn't configured correctly.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65947b59a8896bc225e1eeb0_Robin%20Tang.webp'
				StaticText Robin Tang
				StaticText Co-founder & CTO
		listitem
			link November 13, 2023 Artie Is SOC 2 Type II Compliant SOC 2 or Service Organization Controls 2 is a framework that is governed by the American Institute of Certified Public Accountants (AICPA). Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/artie-is-soc-2-type-ii-compliant'
				StaticText November 13, 2023
				heading Artie Is SOC 2 Type II Compliant
				paragraph
					StaticText SOC 2 or Service Organization Controls 2 is a framework that is governed by the American Institute of Certified Public Accountants (AICPA).
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link September 12, 2023 Preventing WAL Growth on Postgres DB Running on AWS RDS For anyone using Postgres on AWS RDS, it’s possible you’ve run into the scenario of an idle or unused dev database suddenly running out of memory and causing replication slot overflow. This guide explains why replication slot overflow happens and how to prevent it. Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/preventing-wal-growth-on-postgres-db-running-on-aws-rds'
				StaticText September 12, 2023
				heading Preventing WAL Growth on Postgres DB Running on AWS RDS
				paragraph
					StaticText For anyone using Postgres on AWS RDS, it’s possible you’ve run into the scenario of an idle or unused dev database suddenly running out of memory and causing replication slot overflow. This guide explains why replication slot overflow happens and how to prevent it.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link July 26, 2023 Snowflake Eco Mode Eco Mode - minimize time and maximize resource utilization. Eco Mode is an advanced setting that allows customers to define peak and off-peak hours and configure various sync time intervals.  Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/snowflake-eco-mode'
				StaticText July 26, 2023
				heading Snowflake Eco Mode
				paragraph
					StaticText Eco Mode - minimize time and maximize resource utilization. Eco Mode is an advanced setting that allows customers to define peak and off-peak hours and configure various sync time intervals.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link April 11, 2023 The Inevitability and Power of Real-Time Data The ability to shorten the data feedback loop and act while data is still relevant is incredibly valuable. In order to lower response times to data insights, companies require a system that can alert in seconds or minutes rather than hours. Jacqueline Cheong Co-founder & CEO, url='https://www.artie.com/blogs/the-inevitability-and-power-of-realtime-data'
				StaticText April 11, 2023
				heading The Inevitability and Power of Real-Time Data
				paragraph
					StaticText The ability to shorten the data feedback loop and act while data is still relevant is incredibly valuable. In order to lower response times to data insights, companies require a system that can alert in seconds or minutes rather than hours.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
				StaticText Jacqueline Cheong
				StaticText Co-founder & CEO
		listitem
			link February 27, 2023 Why ELTs Are Here to Stay ELTs greatly simplify and streamline the data integration process. It helps free up your data engineering team to work on data pipeline improvements and unlock new data sources. Robin Tang Co-founder & CTO, url='https://www.artie.com/blogs/why-elts-are-here-to-stay'
				StaticText February 27, 2023
				heading Why ELTs Are Here to Stay
				paragraph
					StaticText ELTs greatly simplify and streamline the data integration process. It helps free up your data engineering team to work on data pipeline improvements and unlock new data sources.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65947b59a8896bc225e1eeb0_Robin%20Tang.webp'
				StaticText Robin Tang
				StaticText Co-founder & CTO
		listitem
			link January 30, 2023 What Are the Differences Between OLTP and OLAP Databases? When differentiating between databases, one key characteristic is whether the database is OLTP or OLAP. We will explore what they are, key differences, and go through some real-world examples in this blog post. Robin Tang Co-founder & CTO, url='https://www.artie.com/blogs/what-are-the-differences-between-oltp-and-olap-databases'
				StaticText January 30, 2023
				heading What Are the Differences Between OLTP and OLAP Databases?
				paragraph
					StaticText When differentiating between databases, one key characteristic is whether the database is OLTP or OLAP. We will explore what they are, key differences, and go through some real-world examples in this blog post.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65947b59a8896bc225e1eeb0_Robin%20Tang.webp'
				StaticText Robin Tang
				StaticText Co-founder & CTO
		listitem
			link January 17, 2023 Introducing Artie Transfer Artie leverages change data capture (CDC) and stream processing to sync databases and data warehouses in real-time, enabling sub-minute latency and reducing compute costs. Robin Tang Co-founder & CTO, url='https://www.artie.com/blogs/introducing-artie-transfer'
				StaticText January 17, 2023
				heading Introducing Artie Transfer
				paragraph
					StaticText Artie leverages change data capture (CDC) and stream processing to sync databases and data warehouses in real-time, enabling sub-minute latency and reducing compute costs.
				image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65947b59a8896bc225e1eeb0_Robin%20Tang.webp'
				StaticText Robin Tang
				StaticText Co-founder & CTO
	image, url='https://cdn.prod.website-files.com/66762bf6418642de486f1cc6/6687f9e4df3ac33cc807ef88_artie-logo.png'
	StaticText 220 Sansome Street, San Francisco, CA 94104
	link, url='https://x.com/artie_tech'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f2922d3_Vectors-Wrapper.svg'
	link, url='https://github.com/artie-labs/'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292342_Vectors-Wrapper.svg'
	link, url='https://artie.com/slack'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292314_Vectors-Wrapper.svg'
	link, url='https://www.linkedin.com/company/artie-technologies/'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292368_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292372_icon_soc-2.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/675211814eb5a7ea02c53dbe_HIPAA%20Compliant.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/673536fd56aafffebaa97a57_Technology_Partner_Select_Badge-p-500.png'
	StaticText Documentation
	link Getting started, url='https://artie.com/docs/start'
	link Tutorials, url='https://artie.com/docs/guides'
	link Trust report, url='https://trust.artie.com/'
	link Status page, url='https://artie.instatus.com/'
	StaticText Resources
	link Blog, url='https://www.artie.com/blogs'
	link Customers, url='https://www.artie.com/customer-stories'
	link Pricing, url='https://www.artie.com/pricing'
	link FAQ, url='https://www.artie.com/pricing#faq'
	StaticText Company
	link About, url='https://www.artie.com/about'
	link Contact, url='https://www.artie.com/contact'
	link GitHub, url='https://github.com/artie-labs/'
	StaticText Legal
	link Privacy policy, url='https://artie.com/docs/legal/privacy-policy'
	link Terms of service, url='https://artie.com/docs/legal/terms-of-service'
```
</details>



```
RootWebArea Artie Achieves HIPAA Compliance, focused, url='https://www.artie.com/blogs/artie-achieves-hipaa-compliance'
	banner
		[43] link home, center=(428,44), url='https://www.artie.com/'
			image Artie logo, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/6690586b63f787ded1c849af_artie-logo.png'
		navigation
```
<details><summary>Show more</summary>

```
			[47] link About, center=(517,46), url='https://www.artie.com/about'
			[48] link Blog, center=(607,46), url='https://www.artie.com/blogs'
			[49] link Customers, center=(713,46), url='https://www.artie.com/customer-stories'
			[50] link Docs, center=(820,46), url='https://www.artie.com/docs/start'
			[51] link Pricing, center=(915,46), url='https://www.artie.com/pricing'
		[53] link Get started, center=(1455,46), url='https://www.artie.com/contact'
		[54] link Login, center=(1544,46), url='https://app.artie.com/login'
	banner
		[68] link All posts, center=(363,164), url='https://www.artie.com/blogs'
			image
		heading Artie Achieves HIPAA Compliance
		StaticText Updated on
		StaticText December 9, 2024
		paragraph
			StaticText We're excited to announce that Artie has achieved HIPAA compliance, reinforcing our commitment to secure and reliable data replication solutions. With HIPAA compliance, our healthcare customers can confidently use Artie, knowing their sensitive patient data is protected to the highest standards.
		paragraph
			StaticText This milestone enhances our real-time data replication services, ensuring they meet critical healthcare data privacy and security requirements.
		paragraph
			StaticText Thank you to our team and customers for your trust in Artie. We're dedicated to continuing our work in providing secure, compliant data solutions.
		paragraph
			StaticText Our policies, compliance report, and other details are available at our
			[90] link Trust Center, center=(944,644), url='https://trust.artie.com/'
			StaticText .
		paragraph
			StaticText If you would like to learn more about HIPAA, how to sign a business associate agreement (BAA), or hear more details on how Artie approaches data security, please reach out to
			[92] link hi@artie.com, center=(975,724), url='mailto:hi@artie.com'
			StaticText .
		paragraph
			image HIPAA Announcement, url='https://cdn.jsdelivr.net/gh/artie-labs/website_assets/blogs/hipaa/doctor_revised.webp'
		StaticText Author
		image, url='https://cdn.prod.website-files.com/6585783e20fedbf67af56edb/65857fd4d93b5382cc05206e_author-p-500.webp'
		StaticText Jacqueline Cheong
		StaticText Co-founder & CEO
	[121] link, center=(1848,1018), url='https://www.artie.com/blogs/artie-achieves-hipaa-compliance#Anchor'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/6595534f8f32d6d89b92d2bc_icons8-collapse-arrow-50.png'
	heading 10x better pipelines. This weekend.
	link Get started, url='https://www.artie.com/contact'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0be552abb4459f5aca_chevron-right-black.svg'
	link Talk to a founder, url='https://www.artie.com/contact'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905a0be552abb4459f5b17_chevron-right-white.svg'
	image, url='https://cdn.prod.website-files.com/66762bf6418642de486f1cc6/6687f9e4df3ac33cc807ef88_artie-logo.png'
	StaticText 220 Sansome Street, San Francisco, CA 94104
	link, url='https://x.com/artie_tech'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f2922d3_Vectors-Wrapper.svg'
	link, url='https://github.com/artie-labs/'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292342_Vectors-Wrapper.svg'
	link, url='https://artie.com/slack'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292314_Vectors-Wrapper.svg'
	link, url='https://www.linkedin.com/company/artie-technologies/'
		image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292368_Vectors-Wrapper.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/66905d266f02e1e29f292372_icon_soc-2.png'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/675211814eb5a7ea02c53dbe_HIPAA%20Compliant.svg'
	image, url='https://cdn.prod.website-files.com/658577cb7cec5829d065b1d3/673536fd56aafffebaa97a57_Technology_Partner_Select_Badge-p-500.png'
	StaticText Documentation
	link Getting started, url='https://artie.com/docs/start'
	link Tutorials, url='https://artie.com/docs/guides'
	link Trust report, url='https://trust.artie.com/'
	link Status page, url='https://artie.instatus.com/'
	StaticText Resources
	link Blog, url='https://www.artie.com/blogs'
	link Customers, url='https://www.artie.com/customer-stories'
	link Pricing, url='https://www.artie.com/pricing'
	link FAQ, url='https://www.artie.com/pricing#faq'
	StaticText Company
	link About, url='https://www.artie.com/about'
	link Contact, url='https://www.artie.com/contact'
	link GitHub, url='https://github.com/artie-labs/'
	StaticText Legal
	link Privacy policy, url='https://artie.com/docs/legal/privacy-policy'
	link Terms of service, url='https://artie.com/docs/legal/terms-of-service'
```
</details>

**Reasoning for action:** I chose to click on the blog post link labeled 'December 9, 2024 Artie Achieves HIPAA Compliance' because it directly relates to the user's interest in understanding Artie's solutions in relation to HIPAA compliance. This action takes me from a list of blog posts to the detailed content that describes the compliance announcement and its implications, ultimately helping the user achieve their goal of assessing Artie's alignment with their company's regulatory needs.

**Action:** click(69) # Click on the blog post about Artie achieving HIPAA compliance.

**Change Description:** After clicking on the link about Artie achieving HIPAA compliance, the browser's state transitioned to display the details of the blog post, including the heading, paragraphs explaining the compliance announcement, and additional information pertaining to the author. The URL changed to reflect the specific blog post about HIPAA compliance, and the previous main blog list was replaced with content relevant to the selected topic.

**Screenshot before:****Screenshot after:**---


# Task

**Explore Lantern Documentation**

As a developer looking to integrate AI functionalities,
I explore the documentation for using Lantern effectively,
so that I can understand how to generate embeddings and leverage its features in my applications.

**Success definition:** Given I have accessed the Lantern website
When I click on the Docs link and navigate through the documentation sections
Then I should successfully reach the 'Generate Embeddings' page to learn how to implement embedding generation.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://lantern.dev/

https://lantern.dev/docs

**Content (before/after):** 

```
RootWebArea Lantern, focused, url='https://lantern.dev/'
	navigation
		[57] link, center=(464,29), url='https://lantern.dev/'
			image
		[60] link Pricing, center=(786,29), url='https://lantern.dev/pricing'
```
<details><summary>Show more</summary>

```
		[61] link Docs, center=(859,29), url='https://lantern.dev/docs'
		[62] link Tutorials, center=(936,29), url='https://lantern.dev/tutorials'
		[63] link Blog, center=(1012,29), url='https://lantern.dev/blog'
		[64] link About, center=(1080,29), url='https://lantern.dev/about'
		[65] link, center=(1144,29), url='https://github.com/lanterndata/lanterndb'
			image
		[68] link Login, center=(1406,29), url='https://lantern.dev/auth/sign-in'
		[69] link Sign Up, center=(1506,29), url='https://lantern.dev/auth/sign-up'
	heading Build in AI with Postgres
		paragraph
		image AI, url='https://lantern.dev/images/home/AI.png'
		paragraph
	paragraph
		StaticText Lantern Cloud is an open-source Postgres vector database and toolkit for developers to build production-ready AI applications.
	[86] link Get started for free, center=(852,354), url='https://lantern.dev/auth/sign-up'
		paragraph
		image
	[89] link Explore the docs, center=(1094,354), url='https://lantern.dev/docs'
	paragraph
		StaticText Trusted by companies building for scale
	image Owen Colegrove, url='https://storage.googleapis.com/lantern-web/OwenColegrove.jpg'
	paragraph
		StaticText Owen Colegrove
	paragraph
		StaticText Founder,
		StaticText SciPhi
	image SciPhi logo, url='https://storage.googleapis.com/lantern-web/SciphiLogo.png'
	paragraph
		StaticText Lantern helped us scale our cloud database infrastructure to support thousands of developers building RAG applications.
	image
	image Daksh Gupta, url='https://storage.googleapis.com/lantern-web/DakshGupta.jpg'
	paragraph
		StaticText Daksh Gupta
	paragraph
		StaticText Founder,
		StaticText Greptile
	image Greptile logo, url='https://storage.googleapis.com/lantern-web/GreptileLogo.png'
	paragraph
		StaticText We love Lantern! They made it easy for us to do search over thousands of repositories and millions of lines of code.
	image
	image Kevin Tang, url='https://storage.googleapis.com/lantern-web/KevinTang.jpeg'
	paragraph
		StaticText Kevin Tang
	paragraph
		StaticText Founder,
		StaticText Firebender
	image Firebender logo, url='https://storage.googleapis.com/lantern-web/FirebenderLogo.png'
	paragraph
		StaticText Lantern is the real deal; They helped fixed our Postgres setup and we were able to scale to 10M+ vectors with <50ms query times.
	image
	heading Vector search and BM25 in Postgres
	paragraph
		StaticText Get advanced search functionality inside Postgres with extensions -- no separate vector database or search engine required.
	image
	heading Vector search with pgvector
	paragraph
		StaticText Search over sparse and dense vectors, with support for binary, scalar, and product compression. Scale seamlessly to millions and beyond with serverless indexing.
	StaticText BETA
	image
	heading Text search with BM25
	paragraph
		StaticText Use the BM25 ranking algorithm - the industry standard used in ElasticSearch - for more relevant text search results, surpassing the default full text search capabilities in Postgres.
	StaticText BETA
	image
	heading Hybrid search
	paragraph
		StaticText Combine vector search and BM25 text search using RRF or other reranking algorithms for better results.
	link Get started for free, url='https://lantern.dev/auth/sign-up'
		paragraph
		image
	heading Scale to millions with serverless indexing
	paragraph
		StaticText Scale effortlessly without compromising database performance by offloading vector index creation to a separate machine from your main database.
	image
	list
		listitem
			image
			paragraph
				StaticText Infinite scalability
			paragraph
				StaticText Use as many or as little resources as you'd like, depending on your needs
		listitem
			image
			paragraph
				StaticText Performance
			paragraph
				StaticText Build or update indexes without slowing down your database
		listitem
			image
			paragraph
				StaticText Seamless integration
			paragraph
				StaticText Simply add external=true to vector index creation
	link Get started for free, url='https://lantern.dev/auth/sign-up'
		paragraph
		image
	heading Embedding generation and LLM integrations
	paragraph
		StaticText Simplify AI workflows by generating embeddings and running LLMs directly within your database.
	list
		listitem
			image
			paragraph
				StaticText Generate vectors and run LLMs in Postgres
			paragraph
				StaticText Run simple SQL commands to generate vectors and run LLM models.
		listitem
			image
			paragraph
				StaticText Support for 20+ embedding models and LLMs
			paragraph
				StaticText Access Open AI, Cohere, Jina AI, and other open-source models.
		listitem
			image
			paragraph
				StaticText Automatically generate vector and LLM columns
			paragraph
				StaticText Create new vector or LLM columns based on your existing data.
	link Get started for free, url='https://lantern.dev/auth/sign-up'
		paragraph
		image
	StaticText Table: Products
	paragraph
		StaticText ID
	paragraph
		StaticText Name
	image
	paragraph
		StaticText Description
	image
	paragraph
		StaticText Vector
	StaticText 1
	StaticText Croissant
	StaticText Flaky, buttery, soft breakfast pastry.
	StaticText [0.2, 0.4, 0.7, 0.3, 0.8, 0.1, 0.5]
	StaticText 2
	StaticText Baguette
	StaticText Long, thin loaf of French bread.
	StaticText [0.1, 0.3, 0.6, 0.2, 0.7, 0.2, 0.4]
	StaticText 3
	StaticText Pain au chocolat
	StaticText Chocolate-filled pastry.
	StaticText Generating...
	StaticText 4
	StaticText Brioche
	StaticText Generating...
	StaticText Generating...
	StaticText 5
	StaticText Pretzel
	StaticText Generating...
	StaticText Generating...
	StaticText 6
	StaticText Sourdough
	StaticText Generating...
	StaticText Generating...
	image
	heading Easy to use — just use SQL or your favorite ORM
	paragraph
		StaticText No need to learn a new API or framework. Just use SQL or leverage our integrations with your favorite ORMs.
	StaticText SQL
	StaticText SQL
	StaticText JAVASCRIPT
	StaticText Sequelize
	StaticText Knex
	StaticText PYTHON
	StaticText Django
	link Docs, url='https://lantern.dev/docs/develop/get-started'
		button Docs
			image
	code
		StaticText 1
		StaticText -- Create a table with a vector column
		StaticText 2
		StaticText CREATE
		StaticText TABLE
		StaticText books
		StaticText (id
		StaticText SERIAL
		StaticText PRIMARY KEY
		StaticText , book_embedding
		StaticText REAL
		StaticText [3]);
		StaticText 3
		StaticText 4
		StaticText -- Insert some vectors
		StaticText 5
		StaticText INSERT INTO
		StaticText books (book_embedding)
		StaticText VALUES
		StaticText (
		StaticText '{0,1,0}'
		StaticText ), (
		StaticText '{3,2,4}'
		StaticText );
		StaticText 6
		StaticText 7
		StaticText -- Create an index for faster queries
		StaticText 8
		StaticText CREATE
		StaticText INDEX
		StaticText book_index
		StaticText ON
		StaticText books
		StaticText USING
		StaticText lantern_hnsw(book_embedding dist_l2sq_ops)
		StaticText 9
		StaticText WITH
		StaticText (M
		StaticText =
		StaticText 2
		StaticText , ef_construction
		StaticText =
		StaticText 10
		StaticText , ef
		StaticText =
		StaticText 4
		StaticText , dim
		StaticText =
		StaticText 3
		StaticText );
		StaticText 10
		StaticText 11
		StaticText -- Query the nearest vector
		StaticText 12
		StaticText SELECT
		StaticText id
		StaticText FROM
		StaticText books
		StaticText ORDER BY
		StaticText book_embedding
		StaticText <->
		StaticText '{0,0,0}'
		StaticText LIMIT
		StaticText 1
		StaticText ;
		StaticText 13
		StaticText 14
		StaticText -- Query the nearest vector to a text embedding
		StaticText 15
		StaticText SELECT
		StaticText id
		StaticText FROM
		StaticText books
		StaticText ORDER BY
		StaticText book_embedding
		StaticText <->
		StaticText text_embedding(
		StaticText 'BAAI/bge-base-en'
		StaticText ,
		StaticText 'My text input'
		StaticText )
		StaticText LIMIT
		StaticText 1
		StaticText ;
	link Get started for free, url='https://lantern.dev/auth/sign-up'
		paragraph
		image
	link Explore the docs, url='https://lantern.dev/docs'
	heading Lantern Cloud
	paragraph
		StaticText We're open-source, so you can self-host for full control, or use our managed service for easy setup and scaling.
	paragraph
		StaticText FREE FOREVER
	heading Free tier
	paragraph
		StaticText A multi-tenant setup allows us to set up a free tier that never pauses.
	paragraph
		StaticText $0.00
		StaticText /month
	paragraph
		StaticText All databases include
	list
		listitem
			image
			paragraph
				StaticText Vector search and indexing
		listitem
			image
			paragraph
				StaticText Vector and LLM generation
		listitem
			image
			paragraph
				StaticText Automatic upgrades
		listitem
			image
			paragraph
				StaticText Query insights
		listitem
			image
			paragraph
				StaticText Community support
	link Get started for free, url='https://lantern.dev/auth/sign-up'
	paragraph
		StaticText BEST CHOICE
	heading Production
	paragraph
		StaticText Designed for running high-performance production workloads
	paragraph
		StaticText STARTING AT
	paragraph
		StaticText $44.00
		StaticText /month
	paragraph
		StaticText Everything in free, plus
	list
		listitem
			image
			paragraph
				StaticText Increased compute and storage
		listitem
			image
			paragraph
				StaticText Automatic backups
		listitem
			image
			paragraph
				StaticText Point-in-time recovery
		listitem
			image
			paragraph
				StaticText Asynchronous tasks
		listitem
			image
			paragraph
				StaticText Priority support
	link Get started, url='https://lantern.dev/auth/sign-up'
	heading Start building
	link Get started for free, url='https://lantern.dev/auth/sign-up'
		paragraph
		image
	link Explore the docs, url='https://lantern.dev/docs'
	paragraph
		StaticText Developers
	link Documentation, url='https://lantern.dev/docs'
		paragraph
	link API Reference, url='https://lantern.dev/docs'
		paragraph
	link Tutorials, url='https://lantern.dev/Examples'
		paragraph
	link Blog, url='https://lantern.dev/blog'
		paragraph
	paragraph
		StaticText Company
	link About, url='https://lantern.dev/about'
		paragraph
	link Pricing, url='https://lantern.dev/pricing'
		paragraph
	link Privacy Policy, url='https://lantern.dev/privacy'
		paragraph
	link Terms & Conditions, url='https://lantern.dev/terms'
		paragraph
	paragraph
		StaticText Contact
	link Github, url='https://github.com/lanterndata/lantern'
		paragraph
	link Twitter, url='https://twitter.com/lanterndb'
		paragraph
	link LinkedIn, url='https://www.linkedin.com/company/98218505'
		paragraph
	link Email, url='mailto:support@lantern.dev'
		paragraph
	link, url='https://lantern.dev/'
		image
	paragraph
		StaticText © 2024 Lantern Systems, Inc.
	alert, atomic
```
</details>



```
RootWebArea Docs | Lantern, focused, url='https://lantern.dev/docs'
	alert, atomic
		StaticText Docs | Lantern
	navigation
		[567] link, center=(128,29), url='https://lantern.dev/'
```
<details><summary>Show more</summary>

```
			image
		[570] link Pricing, center=(786,29), url='https://lantern.dev/pricing'
		[571] link Docs, center=(859,29), url='https://lantern.dev/docs'
		[572] link Tutorials, center=(936,29), url='https://lantern.dev/tutorials'
		[573] link Blog, center=(1012,29), url='https://lantern.dev/blog'
		[574] link About, center=(1080,29), url='https://lantern.dev/about'
		[575] link, center=(1144,29), url='https://github.com/lanterndata/lanterndb'
			image
		[578] link Login, center=(1742,29), url='https://lantern.dev/auth/sign-in'
		[579] link Sign Up, center=(1842,29), url='https://lantern.dev/auth/sign-up'
	main
		navigation
			[590] button Search K, center=(144,89), inner_text=Search

K
				image
				paragraph
				image
			paragraph
				StaticText Develop
			[598] link Get Started, center=(148,192), url='https://lantern.dev/docs/develop/get-started'
			[600] link Store Embeddings, center=(148,224), url='https://lantern.dev/docs/develop/store'
			[602] link Generate Embeddings, center=(148,256), url='https://lantern.dev/docs/develop/generate'
			[604] link Automatic Embedding Generation, center=(148,298), url='https://lantern.dev/docs/develop/columns'
			[606] link Calculate Distance, center=(148,340), url='https://lantern.dev/docs/develop/distance'
			[608] link Query Embeddings, center=(148,372), url='https://lantern.dev/docs/develop/query'
			[610] link Create Index, center=(148,404), url='https://lantern.dev/docs/develop/indexing'
			[612] link Quantization, center=(148,436), url='https://lantern.dev/docs/develop/quantization'
			[614] link Asynchronous Tasks, center=(148,468), url='https://lantern.dev/docs/develop/async-tasks'
			[616] link Weighted Vector Search, center=(148,500), url='https://lantern.dev/docs/develop/weighted-vector-search'
			[618] link Troubleshooting, center=(148,532), url='https://lantern.dev/docs/develop/troubleshooting'
			[620] link Single Operator, center=(148,564), url='https://lantern.dev/docs/develop/operator'
			[622] link Postgres Notes, center=(148,596), url='https://lantern.dev/docs/develop/postgres'
			[624] link Security, center=(148,628), url='https://lantern.dev/docs/develop/security'
			paragraph
				StaticText Languages
			[628] link Javascript, center=(148,712), url='https://lantern.dev/docs/languages/javascript'
			[630] link Python, center=(148,744), url='https://lantern.dev/docs/languages/python'
			[632] link Ruby, center=(148,776), url='https://lantern.dev/docs/languages/ruby'
			[634] link Rust, center=(148,808), url='https://lantern.dev/docs/languages/rust'
			paragraph
				StaticText Migrate
			[638] link Migrate from Postgres to Lantern Cloud, center=(148,902), url='https://lantern.dev/docs/migrate/postgres-cloud'
			[640] link Migrate from pgvector to Lantern Cloud, center=(148,954), url='https://lantern.dev/docs/migrate/pgvector-cloud'
			[642] link Migrate from pgvector to self-hosted Lantern, center=(148,1006), url='https://lantern.dev/docs/migrate/pgvector-self'
			[644] link Migrate from Pinecone to Lantern Cloud, center=(148,1058), url='https://lantern.dev/docs/migrate/pinecone'
			paragraph
				StaticText Lantern HNSW
			link Installation, url='https://lantern.dev/docs/lantern-hnsw/install'
			paragraph
				StaticText Lantern Extras
			link Installation, url='https://lantern.dev/docs/lantern-extras/install'
			link Generate Embeddings, url='https://lantern.dev/docs/lantern-extras/embeddings'
			link Lantern Daemon, url='https://lantern.dev/docs/lantern-extras/daemon'
			paragraph
				StaticText Lantern CLI
			link Installation, url='https://lantern.dev/docs/lantern-cli/install'
			link Generate Embeddings, url='https://lantern.dev/docs/lantern-cli/embeddings'
			link Indexing Server, url='https://lantern.dev/docs/lantern-cli/indexing'
			link Daemon, url='https://lantern.dev/docs/lantern-cli/daemon'
			link Autotune Index, url='https://lantern.dev/docs/lantern-cli/autotune'
			link Product Quantization, url='https://lantern.dev/docs/lantern-cli/pq'
			paragraph
				StaticText Contributing
			link Dockerfile, url='https://lantern.dev/docs/contributing/docker'
			link Visual Studio Code, url='https://lantern.dev/docs/contributing/vscode'
		heading Build AI Applications with Postgres
		paragraph
			StaticText Lantern is the only database you need for your AI applications.
		list
			[683] listitem, center=(1104,204), inner_text=Built on top of Postgres- Add AI to your existing applications by just writing another SQL query. We support Postgres 11 - 16.
				ListMarker •
				StaticText Built on top of Postgres
				StaticText -
				StaticText Add AI to your existing applications by just writing another SQL query. We support Postgres 11 - 16.
			listitem
				ListMarker •
				StaticText Fast index creation that scales to billions of vectors
				StaticText -
				StaticText Create an HNSW index for your data in minutes (see our
				[689] link benchmarks, center=(1372,236), url='https://lantern.dev/blog/hnsw-index-creation'
				StaticText ).
			[690] listitem, center=(1104,280), inner_text=Create embeddings without worrying about infrastructure- Simply select the model you'd like to use to embed your data, and we'll handle the rest. No need to worry about finding the right library, switching languages, or handling API call failures.
				ListMarker •
				StaticText Create embeddings without worrying about infrastructure
				StaticText -
				StaticText Simply select the model you'd like to use to embed your data, and we'll handle the rest. No need to worry about finding the right library, switching languages, or handling API call failures.
			[693] listitem, center=(1104,336), inner_text=Index hyperparameter optimization- We'll automatically tune your index for you, so you don't have to worry about finding the right set of parameters, and changing them over time.
				ListMarker •
				StaticText Index hyperparameter optimization
				StaticText -
				StaticText We'll automatically tune your index for you, so you don't have to worry about finding the right set of parameters, and changing them over time.
		heading Getting Started
		paragraph
			StaticText The easiest way to get started with Lantern is with
			[698] link Lantern Cloud, center=(908,456), url='https://lantern.dev/'
			StaticText . Lantern Cloud is a fully managed database offering with support for embedding generation and management. We also provide
			[699] link guides, center=(744,480), url='https://lantern.dev/docs/develop/get-started'
			StaticText on self-hosting Lantern.
		[700] link Sign up for Lantern Cloud, center=(626,538), url='https://lantern.dev/auth/sign-up'
		heading Explore Documentation
		paragraph
			StaticText Check our
			[703] link development guide, center=(650,660), url='https://lantern.dev/docs/develop/store'
			StaticText to learn more about how to use Lantern. We support generating vectors with a a variety of embedding models out of the box. With a single operator, you can query your vectors using a range of distance functions, and filter these results using your existing data.
		[705] link Get Started, center=(800,746), url='https://lantern.dev/docs/develop/get-started'
			image
			paragraph
		[710] link Store Embeddings, center=(1408,746), url='https://lantern.dev/docs/develop/store'
			image
			paragraph
		[715] link Create Index, center=(800,824), url='https://lantern.dev/docs/develop/index'
			image
			paragraph
		[720] link Query Embeddings, center=(1408,824), url='https://lantern.dev/docs/develop/query'
			image
			paragraph
		heading Quickstart Tutorials
		paragraph
			StaticText Integrate Lantern and vector search into an existing application by following one of our quickstart tutorials.
		[728] link Python, center=(800,1014), url='https://lantern.dev/tutorials/python/quickstart'
			image
			paragraph
		[733] link Javascript, center=(1408,1014), url='https://lantern.dev/tutorials/javascript/quickstart'
			image
			paragraph
		link Java, url='https://lantern.dev/tutorials/java/quickstart'
			image
			paragraph
		link Ruby, url='https://lantern.dev/tutorials/ruby/quickstart'
			image
			paragraph
		heading Get Help
		paragraph
			StaticText If you need any help with using Lantern, reach out to our support team at
			link support@lantern.dev., url='mailto:support@lantern.dev'
```
</details>

**Reasoning for action:** By clicking on the Docs link, I successfully transition from the homepage to the documentation section, which is essential for further exploration of how to generate embeddings and leverage the features of the Lantern platform. This is the first necessary step towards reaching the specific 'Generate Embeddings' page outlined in the user story.

**Action:** click(61) # Click on the Docs link to explore the documentation section.

**Change Description:** The browser navigated from the homepage to the documentation section of the Lantern website, updating the URL to 'https://lantern.dev/docs' and changing the focused content to display the documentation links and information, while retaining the main navigation options at the top.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://lantern.dev/docs

https://lantern.dev/docs/develop/get-started

**Content (before/after):** 

```
RootWebArea Docs | Lantern, focused, url='https://lantern.dev/docs'
	alert, atomic
		StaticText Docs | Lantern
	navigation
		[567] link, center=(128,29), url='https://lantern.dev/'
```
<details><summary>Show more</summary>

```
			image
		[570] link Pricing, center=(786,29), url='https://lantern.dev/pricing'
		[571] link Docs, center=(859,29), url='https://lantern.dev/docs'
		[572] link Tutorials, center=(936,29), url='https://lantern.dev/tutorials'
		[573] link Blog, center=(1012,29), url='https://lantern.dev/blog'
		[574] link About, center=(1080,29), url='https://lantern.dev/about'
		[575] link, center=(1144,29), url='https://github.com/lanterndata/lanterndb'
			image
		[578] link Login, center=(1742,29), url='https://lantern.dev/auth/sign-in'
		[579] link Sign Up, center=(1842,29), url='https://lantern.dev/auth/sign-up'
	main
		navigation
			[590] button Search K, center=(144,89), inner_text=Search

K
				image
				paragraph
				image
			paragraph
				StaticText Develop
			[598] link Get Started, center=(148,192), url='https://lantern.dev/docs/develop/get-started'
			[600] link Store Embeddings, center=(148,224), url='https://lantern.dev/docs/develop/store'
			[602] link Generate Embeddings, center=(148,256), url='https://lantern.dev/docs/develop/generate'
			[604] link Automatic Embedding Generation, center=(148,298), url='https://lantern.dev/docs/develop/columns'
			[606] link Calculate Distance, center=(148,340), url='https://lantern.dev/docs/develop/distance'
			[608] link Query Embeddings, center=(148,372), url='https://lantern.dev/docs/develop/query'
			[610] link Create Index, center=(148,404), url='https://lantern.dev/docs/develop/indexing'
			[612] link Quantization, center=(148,436), url='https://lantern.dev/docs/develop/quantization'
			[614] link Asynchronous Tasks, center=(148,468), url='https://lantern.dev/docs/develop/async-tasks'
			[616] link Weighted Vector Search, center=(148,500), url='https://lantern.dev/docs/develop/weighted-vector-search'
			[618] link Troubleshooting, center=(148,532), url='https://lantern.dev/docs/develop/troubleshooting'
			[620] link Single Operator, center=(148,564), url='https://lantern.dev/docs/develop/operator'
			[622] link Postgres Notes, center=(148,596), url='https://lantern.dev/docs/develop/postgres'
			[624] link Security, center=(148,628), url='https://lantern.dev/docs/develop/security'
			paragraph
				StaticText Languages
			[628] link Javascript, center=(148,712), url='https://lantern.dev/docs/languages/javascript'
			[630] link Python, center=(148,744), url='https://lantern.dev/docs/languages/python'
			[632] link Ruby, center=(148,776), url='https://lantern.dev/docs/languages/ruby'
			[634] link Rust, center=(148,808), url='https://lantern.dev/docs/languages/rust'
			paragraph
				StaticText Migrate
			[638] link Migrate from Postgres to Lantern Cloud, center=(148,902), url='https://lantern.dev/docs/migrate/postgres-cloud'
			[640] link Migrate from pgvector to Lantern Cloud, center=(148,954), url='https://lantern.dev/docs/migrate/pgvector-cloud'
			[642] link Migrate from pgvector to self-hosted Lantern, center=(148,1006), url='https://lantern.dev/docs/migrate/pgvector-self'
			[644] link Migrate from Pinecone to Lantern Cloud, center=(148,1058), url='https://lantern.dev/docs/migrate/pinecone'
			paragraph
				StaticText Lantern HNSW
			link Installation, url='https://lantern.dev/docs/lantern-hnsw/install'
			paragraph
				StaticText Lantern Extras
			link Installation, url='https://lantern.dev/docs/lantern-extras/install'
			link Generate Embeddings, url='https://lantern.dev/docs/lantern-extras/embeddings'
			link Lantern Daemon, url='https://lantern.dev/docs/lantern-extras/daemon'
			paragraph
				StaticText Lantern CLI
			link Installation, url='https://lantern.dev/docs/lantern-cli/install'
			link Generate Embeddings, url='https://lantern.dev/docs/lantern-cli/embeddings'
			link Indexing Server, url='https://lantern.dev/docs/lantern-cli/indexing'
			link Daemon, url='https://lantern.dev/docs/lantern-cli/daemon'
			link Autotune Index, url='https://lantern.dev/docs/lantern-cli/autotune'
			link Product Quantization, url='https://lantern.dev/docs/lantern-cli/pq'
			paragraph
				StaticText Contributing
			link Dockerfile, url='https://lantern.dev/docs/contributing/docker'
			link Visual Studio Code, url='https://lantern.dev/docs/contributing/vscode'
		heading Build AI Applications with Postgres
		paragraph
			StaticText Lantern is the only database you need for your AI applications.
		list
			[683] listitem, center=(1104,204), inner_text=Built on top of Postgres- Add AI to your existing applications by just writing another SQL query. We support Postgres 11 - 16.
				ListMarker •
				StaticText Built on top of Postgres
				StaticText -
				StaticText Add AI to your existing applications by just writing another SQL query. We support Postgres 11 - 16.
			listitem
				ListMarker •
				StaticText Fast index creation that scales to billions of vectors
				StaticText -
				StaticText Create an HNSW index for your data in minutes (see our
				[689] link benchmarks, center=(1372,236), url='https://lantern.dev/blog/hnsw-index-creation'
				StaticText ).
			[690] listitem, center=(1104,280), inner_text=Create embeddings without worrying about infrastructure- Simply select the model you'd like to use to embed your data, and we'll handle the rest. No need to worry about finding the right library, switching languages, or handling API call failures.
				ListMarker •
				StaticText Create embeddings without worrying about infrastructure
				StaticText -
				StaticText Simply select the model you'd like to use to embed your data, and we'll handle the rest. No need to worry about finding the right library, switching languages, or handling API call failures.
			[693] listitem, center=(1104,336), inner_text=Index hyperparameter optimization- We'll automatically tune your index for you, so you don't have to worry about finding the right set of parameters, and changing them over time.
				ListMarker •
				StaticText Index hyperparameter optimization
				StaticText -
				StaticText We'll automatically tune your index for you, so you don't have to worry about finding the right set of parameters, and changing them over time.
		heading Getting Started
		paragraph
			StaticText The easiest way to get started with Lantern is with
			[698] link Lantern Cloud, center=(908,456), url='https://lantern.dev/'
			StaticText . Lantern Cloud is a fully managed database offering with support for embedding generation and management. We also provide
			[699] link guides, center=(744,480), url='https://lantern.dev/docs/develop/get-started'
			StaticText on self-hosting Lantern.
		[700] link Sign up for Lantern Cloud, center=(626,538), url='https://lantern.dev/auth/sign-up'
		heading Explore Documentation
		paragraph
			StaticText Check our
			[703] link development guide, center=(650,660), url='https://lantern.dev/docs/develop/store'
			StaticText to learn more about how to use Lantern. We support generating vectors with a a variety of embedding models out of the box. With a single operator, you can query your vectors using a range of distance functions, and filter these results using your existing data.
		[705] link Get Started, center=(800,746), url='https://lantern.dev/docs/develop/get-started'
			image
			paragraph
		[710] link Store Embeddings, center=(1408,746), url='https://lantern.dev/docs/develop/store'
			image
			paragraph
		[715] link Create Index, center=(800,824), url='https://lantern.dev/docs/develop/index'
			image
			paragraph
		[720] link Query Embeddings, center=(1408,824), url='https://lantern.dev/docs/develop/query'
			image
			paragraph
		heading Quickstart Tutorials
		paragraph
			StaticText Integrate Lantern and vector search into an existing application by following one of our quickstart tutorials.
		[728] link Python, center=(800,1014), url='https://lantern.dev/tutorials/python/quickstart'
			image
			paragraph
		[733] link Javascript, center=(1408,1014), url='https://lantern.dev/tutorials/javascript/quickstart'
			image
			paragraph
		link Java, url='https://lantern.dev/tutorials/java/quickstart'
			image
			paragraph
		link Ruby, url='https://lantern.dev/tutorials/ruby/quickstart'
			image
			paragraph
		heading Get Help
		paragraph
			StaticText If you need any help with using Lantern, reach out to our support team at
			link support@lantern.dev., url='mailto:support@lantern.dev'
```
</details>



```
RootWebArea Develop - Get Started | Lantern Docs, focused, url='https://lantern.dev/docs/develop/get-started'
	alert, atomic
		StaticText Develop - Get Started | Lantern Docs
	navigation
		[567] link, center=(128,29), url='https://lantern.dev/'
```
<details><summary>Show more</summary>

```
			image
		[570] link Pricing, center=(786,29), url='https://lantern.dev/pricing'
		[571] link Docs, center=(859,29), url='https://lantern.dev/docs'
		[572] link Tutorials, center=(936,29), url='https://lantern.dev/tutorials'
		[573] link Blog, center=(1012,29), url='https://lantern.dev/blog'
		[574] link About, center=(1080,29), url='https://lantern.dev/about'
		[575] link, center=(1144,29), url='https://github.com/lanterndata/lanterndb'
			image
		[578] link Login, center=(1742,29), url='https://lantern.dev/auth/sign-in'
		[579] link Sign Up, center=(1842,29), url='https://lantern.dev/auth/sign-up'
	main
		navigation
			[590] button Search K, center=(144,89), inner_text=Search

K
				image
				paragraph
				image
			paragraph
				StaticText Develop
			[598] link Get Started, center=(148,192), focused, url='https://lantern.dev/docs/develop/get-started'
			[600] link Store Embeddings, center=(148,224), url='https://lantern.dev/docs/develop/store'
			[602] link Generate Embeddings, center=(148,256), url='https://lantern.dev/docs/develop/generate'
			[604] link Automatic Embedding Generation, center=(148,298), url='https://lantern.dev/docs/develop/columns'
			[606] link Calculate Distance, center=(148,340), url='https://lantern.dev/docs/develop/distance'
			[608] link Query Embeddings, center=(148,372), url='https://lantern.dev/docs/develop/query'
			[610] link Create Index, center=(148,404), url='https://lantern.dev/docs/develop/indexing'
			[612] link Quantization, center=(148,436), url='https://lantern.dev/docs/develop/quantization'
			[614] link Asynchronous Tasks, center=(148,468), url='https://lantern.dev/docs/develop/async-tasks'
			[616] link Weighted Vector Search, center=(148,500), url='https://lantern.dev/docs/develop/weighted-vector-search'
			[618] link Troubleshooting, center=(148,532), url='https://lantern.dev/docs/develop/troubleshooting'
			[620] link Single Operator, center=(148,564), url='https://lantern.dev/docs/develop/operator'
			[622] link Postgres Notes, center=(148,596), url='https://lantern.dev/docs/develop/postgres'
			[624] link Security, center=(148,628), url='https://lantern.dev/docs/develop/security'
			paragraph
				StaticText Languages
			[628] link Javascript, center=(148,712), url='https://lantern.dev/docs/languages/javascript'
			[630] link Python, center=(148,744), url='https://lantern.dev/docs/languages/python'
			[632] link Ruby, center=(148,776), url='https://lantern.dev/docs/languages/ruby'
			[634] link Rust, center=(148,808), url='https://lantern.dev/docs/languages/rust'
			paragraph
				StaticText Migrate
			[638] link Migrate from Postgres to Lantern Cloud, center=(148,902), url='https://lantern.dev/docs/migrate/postgres-cloud'
			[640] link Migrate from pgvector to Lantern Cloud, center=(148,954), url='https://lantern.dev/docs/migrate/pgvector-cloud'
			[642] link Migrate from pgvector to self-hosted Lantern, center=(148,1006), url='https://lantern.dev/docs/migrate/pgvector-self'
			[644] link Migrate from Pinecone to Lantern Cloud, center=(148,1058), url='https://lantern.dev/docs/migrate/pinecone'
			paragraph
				StaticText Lantern HNSW
			link Installation, url='https://lantern.dev/docs/lantern-hnsw/install'
			paragraph
				StaticText Lantern Extras
			link Installation, url='https://lantern.dev/docs/lantern-extras/install'
			link Generate Embeddings, url='https://lantern.dev/docs/lantern-extras/embeddings'
			link Lantern Daemon, url='https://lantern.dev/docs/lantern-extras/daemon'
			paragraph
				StaticText Lantern CLI
			link Installation, url='https://lantern.dev/docs/lantern-cli/install'
			link Generate Embeddings, url='https://lantern.dev/docs/lantern-cli/embeddings'
			link Indexing Server, url='https://lantern.dev/docs/lantern-cli/indexing'
			link Daemon, url='https://lantern.dev/docs/lantern-cli/daemon'
			link Autotune Index, url='https://lantern.dev/docs/lantern-cli/autotune'
			link Product Quantization, url='https://lantern.dev/docs/lantern-cli/pq'
			paragraph
				StaticText Contributing
			link Dockerfile, url='https://lantern.dev/docs/contributing/docker'
			link Visual Studio Code, url='https://lantern.dev/docs/contributing/vscode'
		article
			paragraph
				StaticText Develop
			heading Get Started
			heading Lantern Cloud
			paragraph
				StaticText The easiest way to get started with all of our tools is with
				[779] link Lantern Cloud, center=(905,268), url='https://lantern.dev/'
				StaticText .
			paragraph
				StaticText In Lantern Cloud, you can create create a database with just a few clicks. Once you load your data into Lantern, you can
				link generate embeddings, url='https://lantern.dev/docs/develop/generate'
				StaticText with a single click from dozens of provided open source or proprietary embedding models. You can then
				[782] link create a vector index, center=(1364,336), url='https://lantern.dev/docs/develop/indexing'
				StaticText from your dashboard or run an index-tuning experiment to choose the best parameters for index creation.
			heading Ubicloud
			paragraph
				StaticText Lantern is also available as a managed offering on
				[785] link Ubicloud, center=(838,484), url='https://ubicloud.com/'
				StaticText . You'll still receive direct support from the Lantern team for instances on Ubicloud.
			paragraph
				StaticText Ubicloud is an open-source alternative to AWS. It offers cloud services like virtual machines, block storage, and managed Postgres at rates 2-10x lower than hyperscalers like AWS, Azure, and GCP.
			heading Self-Host
			paragraph
				StaticText Alternatively, you can also use our tools locally or self-host them. There are three tools that are provided out-of-the-box with Lantern Cloud.
			list
				listitem
					ListMarker •
					[791] link Lantern HNSW, center=(534,720), url='https://lantern.dev/docs/lantern-hnsw/install'
					StaticText , our core Postgres extension, provides vector search in Postgres.
				listitem
					ListMarker •
					[793] link Lantern Extras, center=(532,760), url='https://lantern.dev/docs/lantern-extras/install'
					StaticText , which further extends Postgres to support embedding generation.
				listitem
					ListMarker •
					[795] link Lantern CLI, center=(522,800), url='https://lantern.dev/docs/lantern-cli/install'
					StaticText provides routines for generating embeddings and indexes.
			paragraph
				StaticText You can install the tools individually by following the instructions linked.
			heading Overview
			paragraph
				StaticText Here is a non-comprehensive overview of what you can do with Lantern. The examples below use SQL, but we also provide examples for
				[799] link Python, center=(482,992), url='https://lantern.dev/docs/languages/python'
				StaticText ,
				[800] link JavaScript, center=(554,992), url='https://lantern.dev/docs/languages/javascript'
				StaticText ,
				[801] link Ruby, center=(620,992), url='https://lantern.dev/docs/languages/ruby'
				StaticText , and
				[802] link Rust, center=(693,992), url='https://lantern.dev/docs/languages/rust'
				StaticText .
			paragraph
				StaticText Create a table with an embedding column
			StaticText sql
			image
			StaticText Copy
			code
				StaticText 1
				StaticText CREATE
				StaticText TABLE
				StaticText books
				StaticText (id
				StaticText SERIAL
				StaticText PRIMARY KEY
				StaticText , book_embedding
				StaticText REAL
				StaticText [3]);
			paragraph
				StaticText Generate embeddings
			StaticText sql
			image
			StaticText Copy
			code
				StaticText 1
				StaticText SELECT
				StaticText text_embedding(
				StaticText 'BAAI/bge-base-en'
				StaticText ,
				StaticText 'My text input'
				StaticText );
				StaticText 2
				StaticText SELECT
				StaticText openai_embedding(
				StaticText 'openai/text-embedding-ada-002'
				StaticText ,
				StaticText 'My text input'
				StaticText );
			paragraph
				StaticText Insert embeddings
			StaticText sql
			image
			StaticText Copy
			code
				StaticText 1
				StaticText INSERT INTO
				StaticText books (book_embedding)
				StaticText VALUES
				StaticText (
				StaticText '{0,1,0}'
				StaticText ), (
				StaticText '{3,2,4}'
				StaticText );
			paragraph
				StaticText Calculate distance and select nearest rows
			StaticText sql
			image
			StaticText Copy
			code
				StaticText 1
				StaticText SELECT
				StaticText book_embedding
				StaticText <->
				StaticText '{0,0,0}'
				StaticText FROM
				StaticText books
				StaticText 2
				StaticText ORDER BY
				StaticText book_embedding
				StaticText <->
				StaticText '{0,0,0}'
				StaticText LIMIT
				StaticText 1
				StaticText ;
			paragraph
				StaticText Create an index to speed up nearest neighbor search
			StaticText sql
			image
			StaticText Copy
			code
				StaticText 1
				StaticText CREATE
				StaticText INDEX
				StaticText book_index
				StaticText ON
				StaticText books
				StaticText USING
				StaticText lantern_hnsw(book_embedding dist_l2sq_ops)
				StaticText 2
				StaticText WITH
				StaticText (M
				StaticText =
				StaticText 2
				StaticText , ef_construction
				StaticText =
				StaticText 10
				StaticText , ef
				StaticText =
				StaticText 4
				StaticText , dim
				StaticText =
				StaticText 3
				StaticText );
			link Edit this page, url='https://github.com/lanterndata/docs/blob/main/010-develop/000-get-started.md'
				paragraph
		paragraph
			StaticText ON THIS PAGE
		list
			[931] listitem, center=(1776,122), inner_text=Lantern Cloud
				StaticText Lantern Cloud
			[932] listitem, center=(1776,158), inner_text=Ubicloud
				StaticText Ubicloud
			[933] listitem, center=(1776,194), inner_text=Self-Host
				StaticText Self-Host
			[934] listitem, center=(1776,230), inner_text=Overview
				StaticText Overview
```
</details>

**Reasoning for action:** I initiated the action of clicking the 'Get Started' link because this page typically contains essential introductory content, tutorials, and details necessary for new users to effectively use Lantern. This step is important as it can provide context and lead me towards further links or sections including the 'Generate Embeddings' page, which is the ultimate goal of the user story.

**Action:** click(598) # Click on the 'Get Started' link to explore foundational information about using Lantern.

**Change Description:** The user clicked on the 'Get Started' link, resulting in a navigation change to the 'Develop - Get Started' page of the Lantern Docs, with the URL updated to 'https://lantern.dev/docs/develop/get-started', and the focus shifted to the content specific to getting started with Lantern.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://lantern.dev/docs/develop/get-started

https://lantern.dev/docs/develop/generate

**Content (before/after):** 

```
RootWebArea Develop - Get Started | Lantern Docs, focused, url='https://lantern.dev/docs/develop/get-started'
	alert, atomic
		StaticText Develop - Get Started | Lantern Docs
	navigation
		[567] link, center=(128,29), url='https://lantern.dev/'
```
<details><summary>Show more</summary>

```
			image
		[570] link Pricing, center=(786,29), url='https://lantern.dev/pricing'
		[571] link Docs, center=(859,29), url='https://lantern.dev/docs'
		[572] link Tutorials, center=(936,29), url='https://lantern.dev/tutorials'
		[573] link Blog, center=(1012,29), url='https://lantern.dev/blog'
		[574] link About, center=(1080,29), url='https://lantern.dev/about'
		[575] link, center=(1144,29), url='https://github.com/lanterndata/lanterndb'
			image
		[578] link Login, center=(1742,29), url='https://lantern.dev/auth/sign-in'
		[579] link Sign Up, center=(1842,29), url='https://lantern.dev/auth/sign-up'
	main
		navigation
			[590] button Search K, center=(144,89), inner_text=Search

K
				image
				paragraph
				image
			paragraph
				StaticText Develop
			[598] link Get Started, center=(148,192), focused, url='https://lantern.dev/docs/develop/get-started'
			[600] link Store Embeddings, center=(148,224), url='https://lantern.dev/docs/develop/store'
			[602] link Generate Embeddings, center=(148,256), url='https://lantern.dev/docs/develop/generate'
			[604] link Automatic Embedding Generation, center=(148,298), url='https://lantern.dev/docs/develop/columns'
			[606] link Calculate Distance, center=(148,340), url='https://lantern.dev/docs/develop/distance'
			[608] link Query Embeddings, center=(148,372), url='https://lantern.dev/docs/develop/query'
			[610] link Create Index, center=(148,404), url='https://lantern.dev/docs/develop/indexing'
			[612] link Quantization, center=(148,436), url='https://lantern.dev/docs/develop/quantization'
			[614] link Asynchronous Tasks, center=(148,468), url='https://lantern.dev/docs/develop/async-tasks'
			[616] link Weighted Vector Search, center=(148,500), url='https://lantern.dev/docs/develop/weighted-vector-search'
			[618] link Troubleshooting, center=(148,532), url='https://lantern.dev/docs/develop/troubleshooting'
			[620] link Single Operator, center=(148,564), url='https://lantern.dev/docs/develop/operator'
			[622] link Postgres Notes, center=(148,596), url='https://lantern.dev/docs/develop/postgres'
			[624] link Security, center=(148,628), url='https://lantern.dev/docs/develop/security'
			paragraph
				StaticText Languages
			[628] link Javascript, center=(148,712), url='https://lantern.dev/docs/languages/javascript'
			[630] link Python, center=(148,744), url='https://lantern.dev/docs/languages/python'
			[632] link Ruby, center=(148,776), url='https://lantern.dev/docs/languages/ruby'
			[634] link Rust, center=(148,808), url='https://lantern.dev/docs/languages/rust'
			paragraph
				StaticText Migrate
			[638] link Migrate from Postgres to Lantern Cloud, center=(148,902), url='https://lantern.dev/docs/migrate/postgres-cloud'
			[640] link Migrate from pgvector to Lantern Cloud, center=(148,954), url='https://lantern.dev/docs/migrate/pgvector-cloud'
			[642] link Migrate from pgvector to self-hosted Lantern, center=(148,1006), url='https://lantern.dev/docs/migrate/pgvector-self'
			[644] link Migrate from Pinecone to Lantern Cloud, center=(148,1058), url='https://lantern.dev/docs/migrate/pinecone'
			paragraph
				StaticText Lantern HNSW
			link Installation, url='https://lantern.dev/docs/lantern-hnsw/install'
			paragraph
				StaticText Lantern Extras
			link Installation, url='https://lantern.dev/docs/lantern-extras/install'
			link Generate Embeddings, url='https://lantern.dev/docs/lantern-extras/embeddings'
			link Lantern Daemon, url='https://lantern.dev/docs/lantern-extras/daemon'
			paragraph
				StaticText Lantern CLI
			link Installation, url='https://lantern.dev/docs/lantern-cli/install'
			link Generate Embeddings, url='https://lantern.dev/docs/lantern-cli/embeddings'
			link Indexing Server, url='https://lantern.dev/docs/lantern-cli/indexing'
			link Daemon, url='https://lantern.dev/docs/lantern-cli/daemon'
			link Autotune Index, url='https://lantern.dev/docs/lantern-cli/autotune'
			link Product Quantization, url='https://lantern.dev/docs/lantern-cli/pq'
			paragraph
				StaticText Contributing
			link Dockerfile, url='https://lantern.dev/docs/contributing/docker'
			link Visual Studio Code, url='https://lantern.dev/docs/contributing/vscode'
		article
			paragraph
				StaticText Develop
			heading Get Started
			heading Lantern Cloud
			paragraph
				StaticText The easiest way to get started with all of our tools is with
				[779] link Lantern Cloud, center=(905,268), url='https://lantern.dev/'
				StaticText .
			paragraph
				StaticText In Lantern Cloud, you can create create a database with just a few clicks. Once you load your data into Lantern, you can
				link generate embeddings, url='https://lantern.dev/docs/develop/generate'
				StaticText with a single click from dozens of provided open source or proprietary embedding models. You can then
				[782] link create a vector index, center=(1364,336), url='https://lantern.dev/docs/develop/indexing'
				StaticText from your dashboard or run an index-tuning experiment to choose the best parameters for index creation.
			heading Ubicloud
			paragraph
				StaticText Lantern is also available as a managed offering on
				[785] link Ubicloud, center=(838,484), url='https://ubicloud.com/'
				StaticText . You'll still receive direct support from the Lantern team for instances on Ubicloud.
			paragraph
				StaticText Ubicloud is an open-source alternative to AWS. It offers cloud services like virtual machines, block storage, and managed Postgres at rates 2-10x lower than hyperscalers like AWS, Azure, and GCP.
			heading Self-Host
			paragraph
				StaticText Alternatively, you can also use our tools locally or self-host them. There are three tools that are provided out-of-the-box with Lantern Cloud.
			list
				listitem
					ListMarker •
					[791] link Lantern HNSW, center=(534,720), url='https://lantern.dev/docs/lantern-hnsw/install'
					StaticText , our core Postgres extension, provides vector search in Postgres.
				listitem
					ListMarker •
					[793] link Lantern Extras, center=(532,760), url='https://lantern.dev/docs/lantern-extras/install'
					StaticText , which further extends Postgres to support embedding generation.
				listitem
					ListMarker •
					[795] link Lantern CLI, center=(522,800), url='https://lantern.dev/docs/lantern-cli/install'
					StaticText provides routines for generating embeddings and indexes.
			paragraph
				StaticText You can install the tools individually by following the instructions linked.
			heading Overview
			paragraph
				StaticText Here is a non-comprehensive overview of what you can do with Lantern. The examples below use SQL, but we also provide examples for
				[799] link Python, center=(482,992), url='https://lantern.dev/docs/languages/python'
				StaticText ,
				[800] link JavaScript, center=(554,992), url='https://lantern.dev/docs/languages/javascript'
				StaticText ,
				[801] link Ruby, center=(620,992), url='https://lantern.dev/docs/languages/ruby'
				StaticText , and
				[802] link Rust, center=(693,992), url='https://lantern.dev/docs/languages/rust'
				StaticText .
			paragraph
				StaticText Create a table with an embedding column
			StaticText sql
			image
			StaticText Copy
			code
				StaticText 1
				StaticText CREATE
				StaticText TABLE
				StaticText books
				StaticText (id
				StaticText SERIAL
				StaticText PRIMARY KEY
				StaticText , book_embedding
				StaticText REAL
				StaticText [3]);
			paragraph
				StaticText Generate embeddings
			StaticText sql
			image
			StaticText Copy
			code
				StaticText 1
				StaticText SELECT
				StaticText text_embedding(
				StaticText 'BAAI/bge-base-en'
				StaticText ,
				StaticText 'My text input'
				StaticText );
				StaticText 2
				StaticText SELECT
				StaticText openai_embedding(
				StaticText 'openai/text-embedding-ada-002'
				StaticText ,
				StaticText 'My text input'
				StaticText );
			paragraph
				StaticText Insert embeddings
			StaticText sql
			image
			StaticText Copy
			code
				StaticText 1
				StaticText INSERT INTO
				StaticText books (book_embedding)
				StaticText VALUES
				StaticText (
				StaticText '{0,1,0}'
				StaticText ), (
				StaticText '{3,2,4}'
				StaticText );
			paragraph
				StaticText Calculate distance and select nearest rows
			StaticText sql
			image
			StaticText Copy
			code
				StaticText 1
				StaticText SELECT
				StaticText book_embedding
				StaticText <->
				StaticText '{0,0,0}'
				StaticText FROM
				StaticText books
				StaticText 2
				StaticText ORDER BY
				StaticText book_embedding
				StaticText <->
				StaticText '{0,0,0}'
				StaticText LIMIT
				StaticText 1
				StaticText ;
			paragraph
				StaticText Create an index to speed up nearest neighbor search
			StaticText sql
			image
			StaticText Copy
			code
				StaticText 1
				StaticText CREATE
				StaticText INDEX
				StaticText book_index
				StaticText ON
				StaticText books
				StaticText USING
				StaticText lantern_hnsw(book_embedding dist_l2sq_ops)
				StaticText 2
				StaticText WITH
				StaticText (M
				StaticText =
				StaticText 2
				StaticText , ef_construction
				StaticText =
				StaticText 10
				StaticText , ef
				StaticText =
				StaticText 4
				StaticText , dim
				StaticText =
				StaticText 3
				StaticText );
			link Edit this page, url='https://github.com/lanterndata/docs/blob/main/010-develop/000-get-started.md'
				paragraph
		paragraph
			StaticText ON THIS PAGE
		list
			[931] listitem, center=(1776,122), inner_text=Lantern Cloud
				StaticText Lantern Cloud
			[932] listitem, center=(1776,158), inner_text=Ubicloud
				StaticText Ubicloud
			[933] listitem, center=(1776,194), inner_text=Self-Host
				StaticText Self-Host
			[934] listitem, center=(1776,230), inner_text=Overview
				StaticText Overview
```
</details>



```
RootWebArea Develop - Generate Embeddings | Lantern Docs, focused, url='https://lantern.dev/docs/develop/generate'
	alert, atomic
		StaticText Develop - Generate Embeddings | Lantern Docs
	navigation
		[567] link, center=(128,29), url='https://lantern.dev/'
```
<details><summary>Show more</summary>

```
			image
		[570] link Pricing, center=(786,29), url='https://lantern.dev/pricing'
		[571] link Docs, center=(859,29), url='https://lantern.dev/docs'
		[572] link Tutorials, center=(936,29), url='https://lantern.dev/tutorials'
		[573] link Blog, center=(1012,29), url='https://lantern.dev/blog'
		[574] link About, center=(1080,29), url='https://lantern.dev/about'
		[575] link, center=(1144,29), url='https://github.com/lanterndata/lanterndb'
			image
		[578] link Login, center=(1742,29), url='https://lantern.dev/auth/sign-in'
		[579] link Sign Up, center=(1842,29), url='https://lantern.dev/auth/sign-up'
	main
		navigation
			[590] button Search K, center=(144,89), inner_text=Search

K
				image
				paragraph
				image
			paragraph
				StaticText Develop
			[598] link Get Started, center=(148,192), url='https://lantern.dev/docs/develop/get-started'
			[600] link Store Embeddings, center=(148,224), url='https://lantern.dev/docs/develop/store'
			[602] link Generate Embeddings, center=(148,256), focused, url='https://lantern.dev/docs/develop/generate'
			[604] link Automatic Embedding Generation, center=(148,298), url='https://lantern.dev/docs/develop/columns'
			[606] link Calculate Distance, center=(148,340), url='https://lantern.dev/docs/develop/distance'
			[608] link Query Embeddings, center=(148,372), url='https://lantern.dev/docs/develop/query'
			[610] link Create Index, center=(148,404), url='https://lantern.dev/docs/develop/indexing'
			[612] link Quantization, center=(148,436), url='https://lantern.dev/docs/develop/quantization'
			[614] link Asynchronous Tasks, center=(148,468), url='https://lantern.dev/docs/develop/async-tasks'
			[616] link Weighted Vector Search, center=(148,500), url='https://lantern.dev/docs/develop/weighted-vector-search'
			[618] link Troubleshooting, center=(148,532), url='https://lantern.dev/docs/develop/troubleshooting'
			[620] link Single Operator, center=(148,564), url='https://lantern.dev/docs/develop/operator'
			[622] link Postgres Notes, center=(148,596), url='https://lantern.dev/docs/develop/postgres'
			[624] link Security, center=(148,628), url='https://lantern.dev/docs/develop/security'
			paragraph
				StaticText Languages
			[628] link Javascript, center=(148,712), url='https://lantern.dev/docs/languages/javascript'
			[630] link Python, center=(148,744), url='https://lantern.dev/docs/languages/python'
			[632] link Ruby, center=(148,776), url='https://lantern.dev/docs/languages/ruby'
			[634] link Rust, center=(148,808), url='https://lantern.dev/docs/languages/rust'
			paragraph
				StaticText Migrate
			[638] link Migrate from Postgres to Lantern Cloud, center=(148,902), url='https://lantern.dev/docs/migrate/postgres-cloud'
			[640] link Migrate from pgvector to Lantern Cloud, center=(148,954), url='https://lantern.dev/docs/migrate/pgvector-cloud'
			[642] link Migrate from pgvector to self-hosted Lantern, center=(148,1006), url='https://lantern.dev/docs/migrate/pgvector-self'
			[644] link Migrate from Pinecone to Lantern Cloud, center=(148,1058), url='https://lantern.dev/docs/migrate/pinecone'
			paragraph
				StaticText Lantern HNSW
			link Installation, url='https://lantern.dev/docs/lantern-hnsw/install'
			paragraph
				StaticText Lantern Extras
			link Installation, url='https://lantern.dev/docs/lantern-extras/install'
			link Generate Embeddings, url='https://lantern.dev/docs/lantern-extras/embeddings'
			link Lantern Daemon, url='https://lantern.dev/docs/lantern-extras/daemon'
			paragraph
				StaticText Lantern CLI
			link Installation, url='https://lantern.dev/docs/lantern-cli/install'
			link Generate Embeddings, url='https://lantern.dev/docs/lantern-cli/embeddings'
			link Indexing Server, url='https://lantern.dev/docs/lantern-cli/indexing'
			link Daemon, url='https://lantern.dev/docs/lantern-cli/daemon'
			link Autotune Index, url='https://lantern.dev/docs/lantern-cli/autotune'
			link Product Quantization, url='https://lantern.dev/docs/lantern-cli/pq'
			paragraph
				StaticText Contributing
			link Dockerfile, url='https://lantern.dev/docs/contributing/docker'
			link Visual Studio Code, url='https://lantern.dev/docs/contributing/vscode'
		article
			paragraph
				StaticText Develop
			heading Generate Embeddings
			paragraph
				StaticText Lantern supports generating text and image embeddings inside the database. Try it out on
				[962] link Lantern Cloud, center=(1136,216), url='https://lantern.dev/'
				StaticText .
			paragraph
				StaticText Note that generating embeddings is a compute-intensive task. For large scale embedding generation, such as generating embeddings over all of your data, Lantern provides a
				[964] link separate process, center=(728,284), url='https://lantern.dev/docs/develop/generate'
				StaticText .
			heading Open AI Text Embeddings
			paragraph
				StaticText Before using Open AI text embeddings, you need to have an Open AI API key. You can get one by signing up at
				[967] link Open AI, center=(1268,408), url='https://openai.com/'
				StaticText . Once you have an API key, set it as a parameter in Postgres.
			StaticText sql
			[972] image, center=(1409,478)
			StaticText Copy
			code
				StaticText 1
				StaticText ALTER
				StaticText ROLE
				StaticText [YOUR_USERNAME]
				StaticText SET
				StaticText lantern_extras
				StaticText .
				StaticText openai_token
				StaticText =
				StaticText '[YOUR_API_KEY]'
				StaticText ;
				StaticText 2
				StaticText SELECT
				StaticText pg_reload_conf();
			[973] span, center=(1436,478), inner_text=Copy
			paragraph
				StaticText Use the
				code
					StaticText openai_embedding
				StaticText function to generate text embeddings using the Open AI embedding models. This function accepts a model name and text input as arguments, and for the
				code
					StaticText text-embedding-3-small
				StaticText and
				code
					StaticText text-embedding-3-large
				StaticText models, an optional dimension argument.
			StaticText sql
			[999] image, center=(1409,686)
			StaticText Copy
			code
				StaticText 1
				StaticText SELECT
				StaticText openai_embedding(
				StaticText 'openai/text-embedding-ada-002'
				StaticText ,
				StaticText 'My text input'
				StaticText );
				StaticText 2
				StaticText SELECT
				StaticText openai_embedding(
				StaticText 'openai/text-embedding-3-large'
				StaticText ,
				StaticText 'My text input'
				StaticText );
				StaticText 3
				StaticText SELECT
				StaticText openai_embedding(
				StaticText 'openai/text-embedding-3-large'
				StaticText ,
				StaticText 'My text input'
				StaticText ,
				StaticText 256
				StaticText );
			[1000] span, center=(1436,686), inner_text=Copy
			paragraph
				StaticText The following embedding models are supported
			table
				rowgroup
					row
						columnheader Model Name
							paragraph
						columnheader Dimensions
							paragraph
						columnheader Max Tokens
							paragraph
				rowgroup
					row
						[1042] cell openai/text-embedding-ada-002, center=(734,911)
							paragraph
								code
									StaticText openai/text-embedding-ada-002
						[1046] cell 1536, center=(1124,911)
							paragraph
						[1049] cell 8192, center=(1350,911)
							paragraph
					row
						[1053] cell openai/text-embedding-3-small, center=(734,952)
							paragraph
								code
									StaticText openai/text-embedding-3-small
						[1057] cell 512 - 1536, center=(1124,952)
							paragraph
						[1060] cell 8192, center=(1350,952)
							paragraph
					row
						[1064] cell openai/text-embedding-3-large, center=(734,993)
							paragraph
								code
									StaticText openai/text-embedding-3-large
						[1068] cell 256 - 3072, center=(1124,993)
							paragraph
						[1071] cell 8192, center=(1350,993)
							paragraph
			heading Cohere Text Embeddings
			paragraph
				StaticText Before using Cohere text embeddings, you need to have a Cohere API key. You can get one by signing up at
				link Cohere, url='https://cohere.ai/'
				StaticText . Once you have an API key, set it as a parameter in Postgres.
			StaticText sql
			image
			StaticText Copy
			code
				StaticText 1
				StaticText ALTER
				StaticText ROLE
				StaticText [YOUR_USERNAME]
				StaticText SET
				StaticText lantern_extras
				StaticText .
				StaticText cohere_token
				StaticText =
				StaticText '[YOUR_API_KEY]'
				StaticText ;
				StaticText 2
				StaticText SELECT
				StaticText pg_reload_conf();
			paragraph
				StaticText Use the
				code
					StaticText cohere_embedding
				StaticText function to generate text embeddings using the Cohere embedding models. This function accepts a model name and text input as arguments, and an optional input type argument with values
				code
					StaticText search_document
				StaticText or
				code
					StaticText search_query
				StaticText (default is
				code
					StaticText search_query
				StaticText ).
			StaticText sql
			image
			StaticText Copy
			code
				StaticText 1
				StaticText SELECT
				StaticText cohere_embedding(
				StaticText 'cohere/embed-english-v3.0'
				StaticText ,
				StaticText 'My text input'
				StaticText );
				StaticText 2
				StaticText SELECT
				StaticText cohere_embedding(
				StaticText 'cohere/embed-english-v3.0'
				StaticText ,
				StaticText 'My text input'
				StaticText ,
				StaticText 'search_document'
				StaticText );
			paragraph
				StaticText The following embedding models are supported
			table
				rowgroup
					row
						columnheader Model Name
							paragraph
						columnheader Dimensions
							paragraph
						columnheader Max Tokens
							paragraph
				rowgroup
					row
						cell cohere/embed-english-v3.0
							paragraph
								code
									StaticText cohere/embed-english-v3.0
						cell 1024
							paragraph
						cell 512
							paragraph
					row
						cell cohere/embed-multilingual-v3.0
							paragraph
								code
									StaticText cohere/embed-multilingual-v3.0
						cell 1024
							paragraph
						cell 512
							paragraph
					row
						cell cohere/embed-english-v2.0
							paragraph
								code
									StaticText cohere/embed-english-v2.0
						cell 4096
							paragraph
						cell 512
							paragraph
					row
						cell cohere/embed-english-light-v2.0
							paragraph
								code
									StaticText cohere/embed-english-light-v2.0
						cell 1024
							paragraph
						cell 512
							paragraph
					row
						cell cohere/embed-multilingual-v2.0
							paragraph
								code
									StaticText cohere/embed-multilingual-v2.0
						cell 768
							paragraph
						cell 512
							paragraph
					row
						cell cohere/embed-english-light-v3.0
							paragraph
								code
									StaticText cohere/embed-english-light-v3.0
						cell 384
							paragraph
						cell 512
							paragraph
					row
						cell cohere/embed-multilingual-light-v3.0
							paragraph
								code
									StaticText cohere/embed-multilingual-light-v3.0
						cell 384
							paragraph
						cell 512
							paragraph
			heading Open-Source Text Embeddings
			paragraph
				StaticText For example, to generate an embedding for the text
				code
					StaticText My text input
				StaticText using the open-source embedding model
				code
					StaticText BAAI/bge-small-en
				StaticText in SQL, run
			StaticText sql
			image
			StaticText Copy
			code
				StaticText 1
				StaticText SELECT
				StaticText text_embedding(
				StaticText 'BAAI/bge-small-en'
				StaticText ,
				StaticText 'My text input'
				StaticText );
			paragraph
				StaticText The following embedding models are supported
			table
				rowgroup
					row
						columnheader Model Name
							paragraph
						columnheader Dimensions
							paragraph
						columnheader Max Tokens
							paragraph
				rowgroup
					row
						cell clip/ViT-B-32-textual
							paragraph
								code
									StaticText clip/ViT-B-32-textual
						cell 512
							paragraph
						cell 77
							paragraph
					row
						cell microsoft/all-mpnet-base-v2
							paragraph
								code
									StaticText microsoft/all-mpnet-base-v2
						cell 768
							paragraph
						cell 128
							paragraph
					row
						cell microsoft/all-MiniLM-L12-v2
							paragraph
								code
									StaticText microsoft/all-MiniLM-L12-v2
						cell 384
							paragraph
						cell 128
							paragraph
					row
						cell transformers/multi-qa-mpnet-base-dot-v1
							paragraph
								code
									StaticText transformers/multi-qa-mpnet-base-dot-v1
						cell 768
							paragraph
						cell 250
							paragraph
					row
						cell thenlper/gte-base
							paragraph
								code
									StaticText thenlper/gte-base
						cell 768
							paragraph
						cell 128
							paragraph
					row
						cell thenlper/gte-large
							paragraph
								code
									StaticText thenlper/gte-large
						cell 1024
							paragraph
						cell 128
							paragraph
					row
						cell llmrails/ember-v1
							paragraph
								code
									StaticText llmrails/ember-v1
						cell 1024
							paragraph
						cell 512
							paragraph
					row
						cell intfloat/e5-base-v2
							paragraph
								code
									StaticText intfloat/e5-base-v2
						cell 768
							paragraph
						cell 512
							paragraph
					row
						cell intfloat/e5-large-v2
							paragraph
								code
									StaticText intfloat/e5-large-v2
						cell 1024
							paragraph
						cell 512
							paragraph
					row
						cell BAAI/bge-small-en
							paragraph
								code
									StaticText BAAI/bge-small-en
						cell 384
							paragraph
						cell 512
							paragraph
					row
						cell BAAI/bge-base-en
							paragraph
								code
									StaticText BAAI/bge-base-en
						cell 768
							paragraph
						cell 512
							paragraph
					row
						cell BAAI/bge-large-en
							paragraph
								code
									StaticText BAAI/bge-large-en
						cell 1024
							paragraph
						cell 512
							paragraph
					row
						cell BAAI/bge-m3
							paragraph
								code
									StaticText BAAI/bge-m3
						cell 1024
							paragraph
						cell 8192
							paragraph
					row
						cell jinaai/jina-embeddings-v2-small-en
							paragraph
								code
									StaticText jinaai/jina-embeddings-v2-small-en
						cell 512
							paragraph
						cell 8192
							paragraph
					row
						cell jinaai/jina-embeddings-v2-base-en
							paragraph
								code
									StaticText jinaai/jina-embeddings-v2-base-en
						cell 768
							paragraph
						cell 8192
							paragraph
			heading Image Embeddings
			paragraph
				StaticText To generate image embeddings, use the
				code
					StaticText image_embedding
				StaticText function. This function accepts a model name and image URL as arguments.
			paragraph
				StaticText For example, to generate an embedding for the image
				code
					StaticText https://lantern.dev/images/home/footer.png
				StaticText using the embedding model
				code
					StaticText clip/ViT-B-32-visual
				StaticText , run
			StaticText sql
			image
			StaticText Copy
			code
				StaticText 1
				StaticText SELECT
				StaticText image_embedding(
				StaticText 'clip/ViT-B-32-visual'
				StaticText ,
				StaticText 'https://lantern.dev/images/home/footer.png'
				StaticText );
			paragraph
				StaticText The following embedding models are supported
			table
				rowgroup
					row
						columnheader Model Name
							paragraph
						columnheader Dimensions
							paragraph
						columnheader Max Tokens
							paragraph
				rowgroup
					row
						cell clip/ViT-B-32-visual
							paragraph
								code
									StaticText clip/ViT-B-32-visual
						cell 512
							paragraph
						cell 224
							paragraph
			heading Self-Hosting
			paragraph
				StaticText For people self-hosting, generating embeddings requires the Lantern Extras extension. Installation steps are found
				link here, url='https://lantern.dev/docs/lantern-extras/install'
				StaticText .
			paragraph
				StaticText Once the extension is installed, the above functions are available.
			link Edit this page, url='https://github.com/lanterndata/docs/blob/main/010-develop/020-generate.md'
				paragraph
		paragraph
			StaticText ON THIS PAGE
		list
			[1478] listitem, center=(1776,122), inner_text=Open AI Text Embeddings
				StaticText Open AI Text Embeddings
			[1479] listitem, center=(1776,158), inner_text=Cohere Text Embeddings
				StaticText Cohere Text Embeddings
			[1480] listitem, center=(1776,194), inner_text=Open-Source Text Embeddings
				StaticText Open-Source Text Embeddings
			[1481] listitem, center=(1776,230), inner_text=Image Embeddings
				StaticText Image Embeddings
			[1482] listitem, center=(1776,266), inner_text=Self-Hosting
				StaticText Self-Hosting
```
</details>

**Reasoning for action:** By clicking on the 'Generate Embeddings' link, I am directly accessing the documentation section that aligns with my goal of understanding how to implement embedding generation in Lantern. This action is a crucial step in the process as it brings me closer to the acceptance criteria of my user story, which is to learn how to generate embeddings effectively for integration into my applications.

**Action:** click(602) # Click on the 'Generate Embeddings' link to explore how to generate embeddings with Lantern.

**Change Description:** The browser navigated from the 'Get Started' page to the 'Generate Embeddings' page of the Lantern Docs, changing the focused content and the displayed URL to reflect the new section regarding how to generate embeddings with Lantern.

**Screenshot before:****Screenshot after:**---


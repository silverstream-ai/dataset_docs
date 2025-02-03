# Task

**Explore Cedana's Product Offerings**

As a potential customer,
I explore Cedana's product offerings in detail,
so that I can understand how Cedana's solutions can help optimize my compute resources and reduce costs.

**Success definition:** Given I am on the Cedana homepage at httpswww.cedana.com
When I click on the PRODUCT button and then select 'How It Works' from the submenu
Then I should see the 'How It Works' page displayed, with the URL updated to 'httpswww.cedana.comproducthow-it-works' and detailed information about the product functionality.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.cedana.com/

https://www.cedana.com/

**Content (before/after):** 

```
RootWebArea Cedana - Nov 2024 update, focused, url='https://www.cedana.com/'
	banner
		[25] link Home Page Link, center=(379,45), url='https://www.cedana.com/'
			image
		navigation
```
<details><summary>Show more</summary>

```
			[32] button PRODUCT, center=(1080,45), expanded=False, hasPopup='menu'
			[53] button COMPANY, center=(1222,45), expanded=False, hasPopup='menu'
			[69] link DOCS, center=(1336,45), url='https://docs.cedana.ai/'
			[70] link REQUEST API ACCESS, center=(1500,45), url='https://calendly.com/neel-cedana-ai/30-min-pst-clone'
	heading Snapshot and migrate your workloads across instances
	heading Command your compute_increase utilizati|
	[101] link VIEW DOCS, center=(380,427), url='https://docs.cedana.ai/'
	[102] link REQUEST API ACCESS, center=(550,427), url='https://www.cedana.com/connect'
	heading Why Cedana?
	heading Reduce compute costs up to
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda474a_illustarion-2.svg'
	paragraph
		StaticText Eliminate idle compute. Automatically suspend and resume your workloads based on activity. Automatically bin-packs containers freeing up resources.
	heading Automated stateful failover
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda474b_illustarion.svg'
	paragraph
		StaticText Upon hardware or OOM failure, automatically resume workload on a new instance without losing work.
	heading Reduce latency 2-10x
	paragraph
		StaticText Accelerate cold start and time to first token by resuming your CPU/GPU workload from its previous state. Eliminate boot time, initialization, and other steps.
	heading Use Cases
	tablist, orientation='horizontal'
		tab KUBERNETES, selected=False
		tab GPU ORCHESTRATION, selected=False
		tab AI INFERENCE, selected=False
		tab AI TRAINING, selected=False
		tab DATA WORKFLOWS, selected=False
		tab AI AGENTS, selected=False
		tab GAMING, selected=False
		tab HPC, selected=False
		tab DATABASES, selected=True
	tabpanel DATABASES
		heading Transform database deployment and operations with zero downtime migration
		list
			listitem
				StaticText Live migration of in-memory databases
			listitem
				StaticText Zero-downtime OS/HW upgrades
			listitem
				StaticText Dynamically resize workloads to optimal instances
		list
			listitem
				StaticText Eliminate over-provisioning
			listitem
				StaticText Automatically reduce idle compute
	region carousel
		group 1 of 1
			image, url='https://cdn.prod.website-files.com/62434fa732124a0fb112aab4/62434fa732124a91e612aae8_quote-mark.svg'
			StaticText "We reduced our cloud costs 50% by integrating Cedana's Save, Migrate, and Resume capability into our product. If an instance fails, workloads automatically continue without losing work."
			image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673be331e89725173738c320_673096fb7ef9f305b4d617ab_debo_photo.png'
			StaticText Debo Ray
			StaticText CEO, DevZero
	heading Easy Integration
	StaticText Use Cedana's REST API to checkpoint your application’s state, transfer it to a new instance, cloud or resource, and resume operations.
	StaticText No code modifications needed.
	StaticText Checkpoint
	link Copy to clipboard, url='https://www.cedana.com/#'
		image
	StaticText curl
	StaticText -X POST -H
	StaticText "Content-Type: application/json" -d '{
	StaticText "checkpoint_data": {
	StaticText "container_name": "
	StaticText $CHECKPOINT_CONTAINER
	StaticText ",
	StaticText "sandbox_name": "
	StaticText $CHECKPOINT_SANDBOX
	StaticText ",
	StaticText "namespace": "
	StaticText $NAMESPACE
	StaticText ",
	StaticText "checkpoint_path": "
	StaticText $CHECKPOINT_PATH
	StaticText ",
	StaticText "root": "
	StaticText $ROOT
	StaticText "
	StaticText }
	StaticText }'
	StaticText http://
	StaticText $CONTROLLER_URL
	StaticText :1324/checkpoint
	StaticText Restore
	link Copy to clipboard, url='https://www.cedana.com/#'
		image
	StaticText curl
	StaticText -X POST -H
	StaticText "Content-Type: application/json" -d '{
	StaticText "checkpoint_data": {
	StaticText "container_name": "
	StaticText $CHECKPOINT_CONTAINER
	StaticText ",
	StaticText "sandbox_name": "
	StaticText $CHECKPOINT_SANDBOX
	StaticText ",
	StaticText "namespace": "
	StaticText $NAMESPACE
	StaticText ",
	StaticText "checkpoint_path": "
	StaticText $CHECKPOINT_PATH
	StaticText ",
	StaticText "root": "
	StaticText $ROOT
	StaticText "
	StaticText }
	StaticText }'
	StaticText http://
	StaticText $CONTROLLER_URL
	StaticText :1324/restore
	heading Get started
	heading Play in the sandbox
	image
	paragraph
		StaticText We’ve deployed a test cluster for you to play with where you can interact and experiment with the system.
	link SANDBOX, url='https://docs.cedana.ai/sandbox-and-demo-environment'
	heading Get a demo
	image
	paragraph
		StaticText Learn more about how Cedana is transforming compute orchestration and how we can help your organization.
	link CONNECT, url='https://www.cedana.com/connect'
	heading API Reference & Guides
	image
	paragraph
		StaticText From deploying on your cluster, to market, to GPU Checkpointing, learn our system and get started quickly.
	link VIEW DOCS, url='https://docs.cedana.ai/'
	StaticText Backers / Partners
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4770_partners_logo.svg'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4772_partners_logo-1.svg'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4771_partners_logo-2.svg'
	heading command your compute_
	form Newsletter
		textbox Stay in the loop. Join our mailing list., required
		button →
		image
	StaticText Sitemap
	link Home, url='https://www.cedana.com/'
	link About, url='https://www.cedana.com/about'
	link Careers, url='https://www.greenhouse.com/'
	link Insights, url='https://www.cedana.com/blog-post'
	link Docs, url='https://docs.cedana.ai/'
	link Get Access, url='https://www.cedana.com/connect'
	link GitHub, url='https://github.com/cedana'
	StaticText Product
	link How It Works, url='https://www.cedana.com/product/how-it-works'
	link Performance, url='https://www.cedana.com/product/performance'
	link Orchestration, url='https://www.cedana.com/product/orchestration'
	link Reliability, url='https://www.cedana.com/product/reliability'
	StaticText Social
	link X, url='https://x.com/cedanacorp'
	link LinkedIn, url='https://www.linkedin.com/company/cedanacorp'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda47b4_cedana_logo_footer2.svg'
	StaticText © 2024 Cedana Systems Inc.
	link Privacy, url='https://www.cedana.com/privacy-policy'
```
</details>



```
RootWebArea Cedana - Nov 2024 update, focused, url='https://www.cedana.com/'
	banner
		[25] link Home Page Link, center=(379,45), url='https://www.cedana.com/'
			image
		navigation
```
<details><summary>Show more</summary>

```
			[32] button PRODUCT, center=(1080,45), expanded=False, focused, hasPopup='menu'
			[53] button COMPANY, center=(1222,45), expanded=False, hasPopup='menu'
			[69] link DOCS, center=(1336,45), url='https://docs.cedana.ai/'
			[70] link REQUEST API ACCESS, center=(1500,45), url='https://calendly.com/neel-cedana-ai/30-min-pst-clone'
	heading Snapshot and migrate your workloads across instances
	heading Command your compute_increase utilization|
	[101] link VIEW DOCS, center=(380,427), url='https://docs.cedana.ai/'
	[102] link REQUEST API ACCESS, center=(550,427), url='https://www.cedana.com/connect'
	heading Why Cedana?
	heading Reduce compute costs up to
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda474a_illustarion-2.svg'
	paragraph
		StaticText Eliminate idle compute. Automatically suspend and resume your workloads based on activity. Automatically bin-packs containers freeing up resources.
	heading Automated stateful failover
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda474b_illustarion.svg'
	paragraph
		StaticText Upon hardware or OOM failure, automatically resume workload on a new instance without losing work.
	heading Reduce latency 2-10x
	paragraph
		StaticText Accelerate cold start and time to first token by resuming your CPU/GPU workload from its previous state. Eliminate boot time, initialization, and other steps.
	heading Use Cases
	tablist, orientation='horizontal'
		tab KUBERNETES, selected=False
		tab GPU ORCHESTRATION, selected=False
		tab AI INFERENCE, selected=False
		tab AI TRAINING, selected=False
		tab DATA WORKFLOWS, selected=False
		tab AI AGENTS, selected=False
		tab GAMING, selected=False
		tab HPC, selected=False
		tab DATABASES, selected=True
	tabpanel DATABASES
		heading Transform database deployment and operations with zero downtime migration
		list
			listitem
				StaticText Live migration of in-memory databases
			listitem
				StaticText Zero-downtime OS/HW upgrades
			listitem
				StaticText Dynamically resize workloads to optimal instances
		list
			listitem
				StaticText Eliminate over-provisioning
			listitem
				StaticText Automatically reduce idle compute
	region carousel
		group 1 of 1
			image, url='https://cdn.prod.website-files.com/62434fa732124a0fb112aab4/62434fa732124a91e612aae8_quote-mark.svg'
			StaticText "We reduced our cloud costs 50% by integrating Cedana's Save, Migrate, and Resume capability into our product. If an instance fails, workloads automatically continue without losing work."
			image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673be331e89725173738c320_673096fb7ef9f305b4d617ab_debo_photo.png'
			StaticText Debo Ray
			StaticText CEO, DevZero
	heading Easy Integration
	StaticText Use Cedana's REST API to checkpoint your application’s state, transfer it to a new instance, cloud or resource, and resume operations.
	StaticText No code modifications needed.
	StaticText Checkpoint
	link Copy to clipboard, url='https://www.cedana.com/#'
		image
	StaticText curl
	StaticText -X POST -H
	StaticText "Content-Type: application/json" -d '{
	StaticText "checkpoint_data": {
	StaticText "container_name": "
	StaticText $CHECKPOINT_CONTAINER
	StaticText ",
	StaticText "sandbox_name": "
	StaticText $CHECKPOINT_SANDBOX
	StaticText ",
	StaticText "namespace": "
	StaticText $NAMESPACE
	StaticText ",
	StaticText "checkpoint_path": "
	StaticText $CHECKPOINT_PATH
	StaticText ",
	StaticText "root": "
	StaticText $ROOT
	StaticText "
	StaticText }
	StaticText }'
	StaticText http://
	StaticText $CONTROLLER_URL
	StaticText :1324/checkpoint
	StaticText Restore
	link Copy to clipboard, url='https://www.cedana.com/#'
		image
	StaticText curl
	StaticText -X POST -H
	StaticText "Content-Type: application/json" -d '{
	StaticText "checkpoint_data": {
	StaticText "container_name": "
	StaticText $CHECKPOINT_CONTAINER
	StaticText ",
	StaticText "sandbox_name": "
	StaticText $CHECKPOINT_SANDBOX
	StaticText ",
	StaticText "namespace": "
	StaticText $NAMESPACE
	StaticText ",
	StaticText "checkpoint_path": "
	StaticText $CHECKPOINT_PATH
	StaticText ",
	StaticText "root": "
	StaticText $ROOT
	StaticText "
	StaticText }
	StaticText }'
	StaticText http://
	StaticText $CONTROLLER_URL
	StaticText :1324/restore
	heading Get started
	heading Play in the sandbox
	image
	paragraph
		StaticText We’ve deployed a test cluster for you to play with where you can interact and experiment with the system.
	link SANDBOX, url='https://docs.cedana.ai/sandbox-and-demo-environment'
	heading Get a demo
	image
	paragraph
		StaticText Learn more about how Cedana is transforming compute orchestration and how we can help your organization.
	link CONNECT, url='https://www.cedana.com/connect'
	heading API Reference & Guides
	image
	paragraph
		StaticText From deploying on your cluster, to market, to GPU Checkpointing, learn our system and get started quickly.
	link VIEW DOCS, url='https://docs.cedana.ai/'
	StaticText Backers / Partners
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4770_partners_logo.svg'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4772_partners_logo-1.svg'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4771_partners_logo-2.svg'
	heading command your compute_
	form Newsletter
		textbox Stay in the loop. Join our mailing list., required
		button →
		image
	StaticText Sitemap
	link Home, url='https://www.cedana.com/'
	link About, url='https://www.cedana.com/about'
	link Careers, url='https://www.greenhouse.com/'
	link Insights, url='https://www.cedana.com/blog-post'
	link Docs, url='https://docs.cedana.ai/'
	link Get Access, url='https://www.cedana.com/connect'
	link GitHub, url='https://github.com/cedana'
	StaticText Product
	link How It Works, url='https://www.cedana.com/product/how-it-works'
	link Performance, url='https://www.cedana.com/product/performance'
	link Orchestration, url='https://www.cedana.com/product/orchestration'
	link Reliability, url='https://www.cedana.com/product/reliability'
	StaticText Social
	link X, url='https://x.com/cedanacorp'
	link LinkedIn, url='https://www.linkedin.com/company/cedanacorp'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda47b4_cedana_logo_footer2.svg'
	StaticText © 2024 Cedana Systems Inc.
	link Privacy, url='https://www.cedana.com/privacy-policy'
```
</details>

**Reasoning for action:** By clicking the PRODUCT button (identified by its index '32'), I initiate the opening of the products menu on the Cedana homepage. This step is crucial because the next step in the user story requires selecting the 'How It Works' submenu item. Expanding the menu presents the available options, which is necessary to navigate to the specific product details that the user wants to explore.

**Action:** click('32') # Click on the PRODUCT button to explore product offerings.

**Change Description:** After clicking the PRODUCT button, it became focused while other elements remained unchanged; this may indicate the display of a product offerings menu or further details related to products.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.cedana.com/

https://www.cedana.com/

**Content (before/after):** 

```
RootWebArea Cedana - Nov 2024 update, focused, url='https://www.cedana.com/'
	banner
		[25] link Home Page Link, center=(379,45), url='https://www.cedana.com/'
			image
		navigation
```
<details><summary>Show more</summary>

```
			[32] button PRODUCT, center=(1080,45), expanded=False, focused, hasPopup='menu'
			[53] button COMPANY, center=(1222,45), expanded=False, hasPopup='menu'
			[69] link DOCS, center=(1336,45), url='https://docs.cedana.ai/'
			[70] link REQUEST API ACCESS, center=(1500,45), url='https://calendly.com/neel-cedana-ai/30-min-pst-clone'
	heading Snapshot and migrate your workloads across instances
	heading Command your compute_increase utilization|
	[101] link VIEW DOCS, center=(380,427), url='https://docs.cedana.ai/'
	[102] link REQUEST API ACCESS, center=(550,427), url='https://www.cedana.com/connect'
	heading Why Cedana?
	heading Reduce compute costs up to
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda474a_illustarion-2.svg'
	paragraph
		StaticText Eliminate idle compute. Automatically suspend and resume your workloads based on activity. Automatically bin-packs containers freeing up resources.
	heading Automated stateful failover
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda474b_illustarion.svg'
	paragraph
		StaticText Upon hardware or OOM failure, automatically resume workload on a new instance without losing work.
	heading Reduce latency 2-10x
	paragraph
		StaticText Accelerate cold start and time to first token by resuming your CPU/GPU workload from its previous state. Eliminate boot time, initialization, and other steps.
	heading Use Cases
	tablist, orientation='horizontal'
		tab KUBERNETES, selected=False
		tab GPU ORCHESTRATION, selected=False
		tab AI INFERENCE, selected=False
		tab AI TRAINING, selected=False
		tab DATA WORKFLOWS, selected=False
		tab AI AGENTS, selected=False
		tab GAMING, selected=False
		tab HPC, selected=False
		tab DATABASES, selected=True
	tabpanel DATABASES
		heading Transform database deployment and operations with zero downtime migration
		list
			listitem
				StaticText Live migration of in-memory databases
			listitem
				StaticText Zero-downtime OS/HW upgrades
			listitem
				StaticText Dynamically resize workloads to optimal instances
		list
			listitem
				StaticText Eliminate over-provisioning
			listitem
				StaticText Automatically reduce idle compute
	region carousel
		group 1 of 1
			image, url='https://cdn.prod.website-files.com/62434fa732124a0fb112aab4/62434fa732124a91e612aae8_quote-mark.svg'
			StaticText "We reduced our cloud costs 50% by integrating Cedana's Save, Migrate, and Resume capability into our product. If an instance fails, workloads automatically continue without losing work."
			image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673be331e89725173738c320_673096fb7ef9f305b4d617ab_debo_photo.png'
			StaticText Debo Ray
			StaticText CEO, DevZero
	heading Easy Integration
	StaticText Use Cedana's REST API to checkpoint your application’s state, transfer it to a new instance, cloud or resource, and resume operations.
	StaticText No code modifications needed.
	StaticText Checkpoint
	link Copy to clipboard, url='https://www.cedana.com/#'
		image
	StaticText curl
	StaticText -X POST -H
	StaticText "Content-Type: application/json" -d '{
	StaticText "checkpoint_data": {
	StaticText "container_name": "
	StaticText $CHECKPOINT_CONTAINER
	StaticText ",
	StaticText "sandbox_name": "
	StaticText $CHECKPOINT_SANDBOX
	StaticText ",
	StaticText "namespace": "
	StaticText $NAMESPACE
	StaticText ",
	StaticText "checkpoint_path": "
	StaticText $CHECKPOINT_PATH
	StaticText ",
	StaticText "root": "
	StaticText $ROOT
	StaticText "
	StaticText }
	StaticText }'
	StaticText http://
	StaticText $CONTROLLER_URL
	StaticText :1324/checkpoint
	StaticText Restore
	link Copy to clipboard, url='https://www.cedana.com/#'
		image
	StaticText curl
	StaticText -X POST -H
	StaticText "Content-Type: application/json" -d '{
	StaticText "checkpoint_data": {
	StaticText "container_name": "
	StaticText $CHECKPOINT_CONTAINER
	StaticText ",
	StaticText "sandbox_name": "
	StaticText $CHECKPOINT_SANDBOX
	StaticText ",
	StaticText "namespace": "
	StaticText $NAMESPACE
	StaticText ",
	StaticText "checkpoint_path": "
	StaticText $CHECKPOINT_PATH
	StaticText ",
	StaticText "root": "
	StaticText $ROOT
	StaticText "
	StaticText }
	StaticText }'
	StaticText http://
	StaticText $CONTROLLER_URL
	StaticText :1324/restore
	heading Get started
	heading Play in the sandbox
	image
	paragraph
		StaticText We’ve deployed a test cluster for you to play with where you can interact and experiment with the system.
	link SANDBOX, url='https://docs.cedana.ai/sandbox-and-demo-environment'
	heading Get a demo
	image
	paragraph
		StaticText Learn more about how Cedana is transforming compute orchestration and how we can help your organization.
	link CONNECT, url='https://www.cedana.com/connect'
	heading API Reference & Guides
	image
	paragraph
		StaticText From deploying on your cluster, to market, to GPU Checkpointing, learn our system and get started quickly.
	link VIEW DOCS, url='https://docs.cedana.ai/'
	StaticText Backers / Partners
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4770_partners_logo.svg'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4772_partners_logo-1.svg'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4771_partners_logo-2.svg'
	heading command your compute_
	form Newsletter
		textbox Stay in the loop. Join our mailing list., required
		button →
		image
	StaticText Sitemap
	link Home, url='https://www.cedana.com/'
	link About, url='https://www.cedana.com/about'
	link Careers, url='https://www.greenhouse.com/'
	link Insights, url='https://www.cedana.com/blog-post'
	link Docs, url='https://docs.cedana.ai/'
	link Get Access, url='https://www.cedana.com/connect'
	link GitHub, url='https://github.com/cedana'
	StaticText Product
	link How It Works, url='https://www.cedana.com/product/how-it-works'
	link Performance, url='https://www.cedana.com/product/performance'
	link Orchestration, url='https://www.cedana.com/product/orchestration'
	link Reliability, url='https://www.cedana.com/product/reliability'
	StaticText Social
	link X, url='https://x.com/cedanacorp'
	link LinkedIn, url='https://www.linkedin.com/company/cedanacorp'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda47b4_cedana_logo_footer2.svg'
	StaticText © 2024 Cedana Systems Inc.
	link Privacy, url='https://www.cedana.com/privacy-policy'
```
</details>



```
RootWebArea Cedana - Nov 2024 update, focused, url='https://www.cedana.com/'
	banner
		[25] link Home Page Link, center=(379,45), url='https://www.cedana.com/'
			image
		navigation
```
<details><summary>Show more</summary>

```
			[32] button PRODUCT, center=(1080,45), expanded=True, focused, hasPopup='menu'
			navigation PRODUCT
				[36] link How It Works, center=(1127,100), url='https://www.cedana.com/product/how-it-works'
					image
				[40] link Performance, center=(1127,138), url='https://www.cedana.com/product/performance'
					image
				[44] link Orchestration, center=(1127,177), url='https://www.cedana.com/product/orchestration'
					image
				[48] link Reliability, center=(1127,215), url='https://www.cedana.com/product/reliability'
					image
			[53] button COMPANY, center=(1222,45), expanded=False, hasPopup='menu'
			[69] link DOCS, center=(1336,45), url='https://docs.cedana.ai/'
			[70] link REQUEST API ACCESS, center=(1500,45), url='https://calendly.com/neel-cedana-ai/30-min-pst-clone'
	heading Snapshot and migrate your workloads across instances
	heading Command your compute_|
	[101] link VIEW DOCS, center=(380,427), url='https://docs.cedana.ai/'
	[102] link REQUEST API ACCESS, center=(550,427), url='https://www.cedana.com/connect'
	heading Why Cedana?
	heading Reduce compute costs up to
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda474a_illustarion-2.svg'
	paragraph
		StaticText Eliminate idle compute. Automatically suspend and resume your workloads based on activity. Automatically bin-packs containers freeing up resources.
	heading Automated stateful failover
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda474b_illustarion.svg'
	paragraph
		StaticText Upon hardware or OOM failure, automatically resume workload on a new instance without losing work.
	heading Reduce latency 2-10x
	paragraph
		StaticText Accelerate cold start and time to first token by resuming your CPU/GPU workload from its previous state. Eliminate boot time, initialization, and other steps.
	heading Use Cases
	tablist, orientation='horizontal'
		tab KUBERNETES, selected=False
		tab GPU ORCHESTRATION, selected=False
		tab AI INFERENCE, selected=False
		tab AI TRAINING, selected=False
		tab DATA WORKFLOWS, selected=False
		tab AI AGENTS, selected=False
		tab GAMING, selected=False
		tab HPC, selected=False
		tab DATABASES, selected=True
	tabpanel DATABASES
		heading Transform database deployment and operations with zero downtime migration
		list
			listitem
				StaticText Live migration of in-memory databases
			listitem
				StaticText Zero-downtime OS/HW upgrades
			listitem
				StaticText Dynamically resize workloads to optimal instances
		list
			listitem
				StaticText Eliminate over-provisioning
			listitem
				StaticText Automatically reduce idle compute
	region carousel
		group 1 of 1
			image, url='https://cdn.prod.website-files.com/62434fa732124a0fb112aab4/62434fa732124a91e612aae8_quote-mark.svg'
			StaticText "We reduced our cloud costs 50% by integrating Cedana's Save, Migrate, and Resume capability into our product. If an instance fails, workloads automatically continue without losing work."
			image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673be331e89725173738c320_673096fb7ef9f305b4d617ab_debo_photo.png'
			StaticText Debo Ray
			StaticText CEO, DevZero
	heading Easy Integration
	StaticText Use Cedana's REST API to checkpoint your application’s state, transfer it to a new instance, cloud or resource, and resume operations.
	StaticText No code modifications needed.
	StaticText Checkpoint
	link Copy to clipboard, url='https://www.cedana.com/#'
		image
	StaticText curl
	StaticText -X POST -H
	StaticText "Content-Type: application/json" -d '{
	StaticText "checkpoint_data": {
	StaticText "container_name": "
	StaticText $CHECKPOINT_CONTAINER
	StaticText ",
	StaticText "sandbox_name": "
	StaticText $CHECKPOINT_SANDBOX
	StaticText ",
	StaticText "namespace": "
	StaticText $NAMESPACE
	StaticText ",
	StaticText "checkpoint_path": "
	StaticText $CHECKPOINT_PATH
	StaticText ",
	StaticText "root": "
	StaticText $ROOT
	StaticText "
	StaticText }
	StaticText }'
	StaticText http://
	StaticText $CONTROLLER_URL
	StaticText :1324/checkpoint
	StaticText Restore
	link Copy to clipboard, url='https://www.cedana.com/#'
		image
	StaticText curl
	StaticText -X POST -H
	StaticText "Content-Type: application/json" -d '{
	StaticText "checkpoint_data": {
	StaticText "container_name": "
	StaticText $CHECKPOINT_CONTAINER
	StaticText ",
	StaticText "sandbox_name": "
	StaticText $CHECKPOINT_SANDBOX
	StaticText ",
	StaticText "namespace": "
	StaticText $NAMESPACE
	StaticText ",
	StaticText "checkpoint_path": "
	StaticText $CHECKPOINT_PATH
	StaticText ",
	StaticText "root": "
	StaticText $ROOT
	StaticText "
	StaticText }
	StaticText }'
	StaticText http://
	StaticText $CONTROLLER_URL
	StaticText :1324/restore
	heading Get started
	heading Play in the sandbox
	image
	paragraph
		StaticText We’ve deployed a test cluster for you to play with where you can interact and experiment with the system.
	link SANDBOX, url='https://docs.cedana.ai/sandbox-and-demo-environment'
	heading Get a demo
	image
	paragraph
		StaticText Learn more about how Cedana is transforming compute orchestration and how we can help your organization.
	link CONNECT, url='https://www.cedana.com/connect'
	heading API Reference & Guides
	image
	paragraph
		StaticText From deploying on your cluster, to market, to GPU Checkpointing, learn our system and get started quickly.
	link VIEW DOCS, url='https://docs.cedana.ai/'
	StaticText Backers / Partners
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4770_partners_logo.svg'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4772_partners_logo-1.svg'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4771_partners_logo-2.svg'
	heading command your compute_
	form Newsletter
		textbox Stay in the loop. Join our mailing list., required
		button →
		image
	StaticText Sitemap
	link Home, url='https://www.cedana.com/'
	link About, url='https://www.cedana.com/about'
	link Careers, url='https://www.greenhouse.com/'
	link Insights, url='https://www.cedana.com/blog-post'
	link Docs, url='https://docs.cedana.ai/'
	link Get Access, url='https://www.cedana.com/connect'
	link GitHub, url='https://github.com/cedana'
	StaticText Product
	link How It Works, url='https://www.cedana.com/product/how-it-works'
	link Performance, url='https://www.cedana.com/product/performance'
	link Orchestration, url='https://www.cedana.com/product/orchestration'
	link Reliability, url='https://www.cedana.com/product/reliability'
	StaticText Social
	link X, url='https://x.com/cedanacorp'
	link LinkedIn, url='https://www.linkedin.com/company/cedanacorp'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda47b4_cedana_logo_footer2.svg'
	StaticText © 2024 Cedana Systems Inc.
	link Privacy, url='https://www.cedana.com/privacy-policy'
```
</details>

**Reasoning for action:** My reasoning for this action is that the user story specifies the requirement to select 'How It Works' after clicking on the PRODUCT button. The PRODUCT button is identified by the element with id '32', and by clicking it, I aim to either expand the submenu or confirm that it is accessible so that I can subsequently select the 'How It Works' link. This is essential to achieve the goal of viewing detailed information about how Cedana's solutions can help optimize compute resources and reduce costs.

**Action:** click('32') # Click on the PRODUCT button again to see if it expands or reveals more product details.

**Change Description:** After clicking the PRODUCT button, it expanded to reveal a submenu containing links for How It Works, Performance, Orchestration, and Reliability, which were previously hidden.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.cedana.com/

https://www.cedana.com/product/how-it-works

**Content (before/after):** 

```
RootWebArea Cedana - Nov 2024 update, focused, url='https://www.cedana.com/'
	banner
		[25] link Home Page Link, center=(379,45), url='https://www.cedana.com/'
			image
		navigation
```
<details><summary>Show more</summary>

```
			[32] button PRODUCT, center=(1080,45), expanded=True, focused, hasPopup='menu'
			navigation PRODUCT
				[36] link How It Works, center=(1127,100), url='https://www.cedana.com/product/how-it-works'
					image
				[40] link Performance, center=(1127,138), url='https://www.cedana.com/product/performance'
					image
				[44] link Orchestration, center=(1127,177), url='https://www.cedana.com/product/orchestration'
					image
				[48] link Reliability, center=(1127,215), url='https://www.cedana.com/product/reliability'
					image
			[53] button COMPANY, center=(1222,45), expanded=False, hasPopup='menu'
			[69] link DOCS, center=(1336,45), url='https://docs.cedana.ai/'
			[70] link REQUEST API ACCESS, center=(1500,45), url='https://calendly.com/neel-cedana-ai/30-min-pst-clone'
	heading Snapshot and migrate your workloads across instances
	heading Command your compute_|
	[101] link VIEW DOCS, center=(380,427), url='https://docs.cedana.ai/'
	[102] link REQUEST API ACCESS, center=(550,427), url='https://www.cedana.com/connect'
	heading Why Cedana?
	heading Reduce compute costs up to
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda474a_illustarion-2.svg'
	paragraph
		StaticText Eliminate idle compute. Automatically suspend and resume your workloads based on activity. Automatically bin-packs containers freeing up resources.
	heading Automated stateful failover
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda474b_illustarion.svg'
	paragraph
		StaticText Upon hardware or OOM failure, automatically resume workload on a new instance without losing work.
	heading Reduce latency 2-10x
	paragraph
		StaticText Accelerate cold start and time to first token by resuming your CPU/GPU workload from its previous state. Eliminate boot time, initialization, and other steps.
	heading Use Cases
	tablist, orientation='horizontal'
		tab KUBERNETES, selected=False
		tab GPU ORCHESTRATION, selected=False
		tab AI INFERENCE, selected=False
		tab AI TRAINING, selected=False
		tab DATA WORKFLOWS, selected=False
		tab AI AGENTS, selected=False
		tab GAMING, selected=False
		tab HPC, selected=False
		tab DATABASES, selected=True
	tabpanel DATABASES
		heading Transform database deployment and operations with zero downtime migration
		list
			listitem
				StaticText Live migration of in-memory databases
			listitem
				StaticText Zero-downtime OS/HW upgrades
			listitem
				StaticText Dynamically resize workloads to optimal instances
		list
			listitem
				StaticText Eliminate over-provisioning
			listitem
				StaticText Automatically reduce idle compute
	region carousel
		group 1 of 1
			image, url='https://cdn.prod.website-files.com/62434fa732124a0fb112aab4/62434fa732124a91e612aae8_quote-mark.svg'
			StaticText "We reduced our cloud costs 50% by integrating Cedana's Save, Migrate, and Resume capability into our product. If an instance fails, workloads automatically continue without losing work."
			image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673be331e89725173738c320_673096fb7ef9f305b4d617ab_debo_photo.png'
			StaticText Debo Ray
			StaticText CEO, DevZero
	heading Easy Integration
	StaticText Use Cedana's REST API to checkpoint your application’s state, transfer it to a new instance, cloud or resource, and resume operations.
	StaticText No code modifications needed.
	StaticText Checkpoint
	link Copy to clipboard, url='https://www.cedana.com/#'
		image
	StaticText curl
	StaticText -X POST -H
	StaticText "Content-Type: application/json" -d '{
	StaticText "checkpoint_data": {
	StaticText "container_name": "
	StaticText $CHECKPOINT_CONTAINER
	StaticText ",
	StaticText "sandbox_name": "
	StaticText $CHECKPOINT_SANDBOX
	StaticText ",
	StaticText "namespace": "
	StaticText $NAMESPACE
	StaticText ",
	StaticText "checkpoint_path": "
	StaticText $CHECKPOINT_PATH
	StaticText ",
	StaticText "root": "
	StaticText $ROOT
	StaticText "
	StaticText }
	StaticText }'
	StaticText http://
	StaticText $CONTROLLER_URL
	StaticText :1324/checkpoint
	StaticText Restore
	link Copy to clipboard, url='https://www.cedana.com/#'
		image
	StaticText curl
	StaticText -X POST -H
	StaticText "Content-Type: application/json" -d '{
	StaticText "checkpoint_data": {
	StaticText "container_name": "
	StaticText $CHECKPOINT_CONTAINER
	StaticText ",
	StaticText "sandbox_name": "
	StaticText $CHECKPOINT_SANDBOX
	StaticText ",
	StaticText "namespace": "
	StaticText $NAMESPACE
	StaticText ",
	StaticText "checkpoint_path": "
	StaticText $CHECKPOINT_PATH
	StaticText ",
	StaticText "root": "
	StaticText $ROOT
	StaticText "
	StaticText }
	StaticText }'
	StaticText http://
	StaticText $CONTROLLER_URL
	StaticText :1324/restore
	heading Get started
	heading Play in the sandbox
	image
	paragraph
		StaticText We’ve deployed a test cluster for you to play with where you can interact and experiment with the system.
	link SANDBOX, url='https://docs.cedana.ai/sandbox-and-demo-environment'
	heading Get a demo
	image
	paragraph
		StaticText Learn more about how Cedana is transforming compute orchestration and how we can help your organization.
	link CONNECT, url='https://www.cedana.com/connect'
	heading API Reference & Guides
	image
	paragraph
		StaticText From deploying on your cluster, to market, to GPU Checkpointing, learn our system and get started quickly.
	link VIEW DOCS, url='https://docs.cedana.ai/'
	StaticText Backers / Partners
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4770_partners_logo.svg'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4772_partners_logo-1.svg'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4771_partners_logo-2.svg'
	heading command your compute_
	form Newsletter
		textbox Stay in the loop. Join our mailing list., required
		button →
		image
	StaticText Sitemap
	link Home, url='https://www.cedana.com/'
	link About, url='https://www.cedana.com/about'
	link Careers, url='https://www.greenhouse.com/'
	link Insights, url='https://www.cedana.com/blog-post'
	link Docs, url='https://docs.cedana.ai/'
	link Get Access, url='https://www.cedana.com/connect'
	link GitHub, url='https://github.com/cedana'
	StaticText Product
	link How It Works, url='https://www.cedana.com/product/how-it-works'
	link Performance, url='https://www.cedana.com/product/performance'
	link Orchestration, url='https://www.cedana.com/product/orchestration'
	link Reliability, url='https://www.cedana.com/product/reliability'
	StaticText Social
	link X, url='https://x.com/cedanacorp'
	link LinkedIn, url='https://www.linkedin.com/company/cedanacorp'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda47b4_cedana_logo_footer2.svg'
	StaticText © 2024 Cedana Systems Inc.
	link Privacy, url='https://www.cedana.com/privacy-policy'
```
</details>



```
RootWebArea How It Works, focused, url='https://www.cedana.com/product/how-it-works'
	banner
		[27] link Home Page Link, center=(379,45), url='https://www.cedana.com/'
			image
		navigation
```
<details><summary>Show more</summary>

```
			[34] button PRODUCT, center=(1080,45), expanded=False, hasPopup='menu'
			[55] button COMPANY, center=(1222,45), expanded=False, hasPopup='menu'
			[71] link DOCS, center=(1336,45), url='https://docs.cedana.ai/'
			[72] link REQUEST API ACCESS, center=(1500,45), url='https://calendly.com/neel-cedana-ai/30-min-pst-clone'
	heading Save, migrate, and resume
	heading container utilization.
	[88] link GET ACCESS, center=(384,397), url='https://www.cedana.com/connect'
	[89] link PRODUCT BENEFITS, center=(550,397), url='https://www.cedana.com/product/how-it-works#product-benefits'
	heading How it works
	paragraph
		StaticText Save a process or container
		StaticText using the Cedana API. The entire сontainer state including process, memory, file and network descriptors are saved.
	Canvas
	paragraph
		StaticText Migrate
		StaticText the workload onto another instance with real-time performance with zero interruption or code-modifications.
	Canvas
	paragraph
		StaticText Resume
		StaticText workloads as a new process or container on another instance.
	Canvas
	paragraph
		StaticText Policy-based automation
		StaticText at scale
		StaticText based on real time factors. Achieve stateful reliability, price and performance, advanced orchestration, and dynamic and elastic scaling.
	Canvas
	heading Product benefits
	heading Improve performance. Reduce costs.
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda47a7_performance_new-v3.svg'
	link PERFORMANCE, url='https://www.cedana.com/product/performance'
	heading Real-time compute orchestration.
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda47a8_Orchestration_new-v3.svg'
	link ORCHESTRATION, url='https://www.cedana.com/product/orchestration'
	heading Increase reliability and availability
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda47a6_Reliability_new-v3.svg'
	link RELIABILITY, url='https://www.cedana.com/product/reliability'
	heading Get started
	heading Play in the sandbox
	image
	paragraph
		StaticText We’ve deployed a test cluster for you to play with where you can interact and experiment with the system.
	link SANDBOX, url='https://docs.cedana.ai/sandbox-and-demo-environment'
	heading Get a demo
	image
	paragraph
		StaticText Learn more about how Cedana is transforming compute orchestration and how we can help your organization.
	link CONNECT, url='https://www.cedana.com/connect'
	heading API Reference & Guides
	image
	paragraph
		StaticText From deploying on your cluster, to market, to GPU Checkpointing, learn our system and get started quickly.
	link VIEW DOCS, url='https://docs.cedana.ai/'
	StaticText Backers / Partners
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4770_partners_logo.svg'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4772_partners_logo-1.svg'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda4771_partners_logo-2.svg'
	heading command your compute_
	form Newsletter
		textbox Stay in the loop. Join our mailing list., required
		button →
		image
	StaticText Sitemap
	link Home, url='https://www.cedana.com/'
	link About, url='https://www.cedana.com/about'
	link Careers, url='https://www.greenhouse.com/'
	link Insights, url='https://www.cedana.com/blog-post'
	link Docs, url='https://docs.cedana.ai/'
	link Get Access, url='https://www.cedana.com/connect'
	link GitHub, url='https://github.com/cedana'
	StaticText Product
	link How It Works, url='https://www.cedana.com/product/how-it-works'
	link Performance, url='https://www.cedana.com/product/performance'
	link Orchestration, url='https://www.cedana.com/product/orchestration'
	link Reliability, url='https://www.cedana.com/product/reliability'
	StaticText Social
	link X, url='https://x.com/cedanacorp'
	link LinkedIn, url='https://www.linkedin.com/company/cedanacorp'
	image, url='https://cdn.prod.website-files.com/673bab08b9ca68895eda471f/673bab08b9ca68895eda47b4_cedana_logo_footer2.svg'
	StaticText © 2024 Cedana Systems Inc.
	link Privacy, url='https://www.cedana.com/privacy-policy'
```
</details>

**Reasoning for action:** By clicking on the 'How It Works' link, I am navigating to the specific page that contains detailed descriptions of Cedana's product offerings. This step is crucial for achieving the user's goal of exploring Cedana's solutions in detail, as it directly leads to the information needed to understand how these solutions can potentially optimize compute resources and reduce costs. Additionally, this action updates the webpage URL to the specified endpoint, confirming that the navigation is successful.

**Action:** click('36') # Click on the 'How It Works' link to learn more about Cedana's product functionality.

**Change Description:** After clicking the 'How It Works' link, the browser navigated to a new page that details the functionality of Cedana's product, resulting in a change of the displayed heading to 'How It Works' and updating the URL to 'https://www.cedana.com/product/how-it-works'. The content now includes paragraphs explaining the process of saving, migrating, and resuming workloads, along with new images and links related to product benefits.

**Screenshot before:****Screenshot after:**---


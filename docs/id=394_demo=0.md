# Task

**User Journey for Exploring GitHub Repository**

As a developer,
I explore the GitHub repository for Titan Systems,
so that I can understand existing issues and potential features to contribute to the project.

**Success definition:** Given I am on the Titan Systems GitHub repository
When I explore the issues section and click on an open issue
Then I should see the details and discussions about the issue.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://applytitan.com/

https://github.com/Titan-Systems/titan

**Content (before/after):** 

```
RootWebArea Snowflake Access Management - Titan, focused, url='https://applytitan.com/'
	[48] link logo, center=(126,45), url='https://applytitan.com/'
		image logo, url='https://framerusercontent.com/images/ugHzBVWH17m5NTN9DK6HU6HpCis.png'
	image, url='https://framerusercontent.com/images/Ff56hwfNRzHD67oIoBHFExLrdw.svg'
	heading titan core
```
<details><summary>Show more</summary>

```
	heading Open source infrastructure as code
	paragraph
		StaticText Titan Core helps you provision, deploy, and secure resources in Snowflake, replacing tools like Terraform.
	paragraph
		StaticText Define any Snowflake resource, including users, roles, schemas, databases, integrations,
		StaticText pipes, stages, functions, and stored procedures, using declarative Python or YAML.
	paragraph
		[67] link View Repo, center=(960,439), url='https://github.com/Titan-Systems/titan'
	generic
	textbox Code Editor for example.py value='from titan import Blueprint
from titan.resources import Grant, Role, Warehouse


bp = Blueprint(resources=[
    Role(name="transformer"),
    Warehouse(
        name="transforming",
        warehouse_size="large",
        auto_suspend=60,
    ),
    Grant(
        priv="usage",
        to="transformer",
        on="transforming"
    ),
])'
	generic
	textbox Code Editor for example.py value='plan = bp.plan(connection)
print(plan) # =>
"""
» account:ABC123


  ~ warehouse "urn::ABC123:warehouse/transforming" {
     ~ auto_suspend = 600 -> 60
    }


  + grant "urn::ABC123:grant/..." {
     + priv = "USAGE"
     + on   = warehouse "transforming"
     + to   = role "transformer"
    }
"""
bp.apply(connection, plan)'
	banner
		heading Backed by
		image, url='https://framerusercontent.com/images/gCW2aMEIPx1ZTpzD1IkopKDYuNc.png?scale-down-to=512'
	contentinfo
		image logo, url='https://framerusercontent.com/images/ugHzBVWH17m5NTN9DK6HU6HpCis.png'
		link, url='https://www.linkedin.com/company/titan-systems-inc'
		link, url='https://github.com/Titan-Systems'
		paragraph
		paragraph
			link contact@applytitan.com, url='mailto:contact@applytitan.com'
		paragraph
			StaticText © 2025 Titan Systems, Inc
```
</details>



```
RootWebArea GitHub - Titan-Systems/titan: Titan Core - Snowflake infrastructure-as-code. Provision environments, automate deploys, CI/CD. Manage RBAC, users, roles, and data access. Declarative Python Resource API. Change Management tool for the Snowflake data warehouse., focused, url='https://github.com/Titan-Systems/titan'
	link Skip to content, url='https://github.com/Titan-Systems/titan#start-of-content'
	banner
		heading Navigation Menu
		[193] link Homepage, center=(48,36), url='https://github.com/'
```
<details><summary>Show more</summary>

```
		navigation Global
			list
				listitem
					[202] button Product, center=(126,36), expanded=False, type=button
				listitem
					[264] button Solutions, center=(222,36), expanded=False, type=button
				listitem
					[306] button Resources, center=(329,36), expanded=False, type=button
				listitem
					[341] button Open Source, center=(451,36), expanded=False, type=button
				listitem
					[367] button Enterprise, center=(570,36), expanded=False, type=button
				listitem
					[397] link Pricing, center=(657,36), url='https://github.com/pricing'
		[400] button Search or jump to…, center=(1564,36), hasPopup='dialog', inner_text=Search or jump to..., type=button
			StaticText Search or jump to...
		[521] link Sign in, center=(1769,36), url='https://github.com/login?return_to=https%3A%2F%2Fgithub.com%2FTitan-Systems%2Ftitan'
		[522] link Sign up, center=(1851,36), url='https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F%3Cuser-name%3E%2F%3Crepo-name%3E&source=header-repo&source_repo=Titan-Systems%2Ftitan'
	main
		[547] link Titan-Systems, center=(120,103), url='https://github.com/Titan-Systems'
		StaticText /
		strong
			[550] link titan, center=(218,103), url='https://github.com/Titan-Systems/titan'
		StaticText Public
		list
			listitem
				[556] link You must be signed in to change notification settings, center=(1593,102), inner_text=Notifications, url='https://github.com/login?return_to=%2FTitan-Systems%2Ftitan'
					StaticText Notifications
			listitem
				[560] link Fork 32, center=(1712,102), url='https://github.com/login?return_to=%2FTitan-Systems%2Ftitan'
			listitem
				[565] link You must be signed in to star a repository, center=(1831,102), inner_text= Star 444, url='https://github.com/login?return_to=%2FTitan-Systems%2Ftitan'
					StaticText Star
		navigation Repository
			list
				listitem
					[606] link Code, center=(70,158), url='https://github.com/Titan-Systems/titan'
				listitem
					[611] link Issues 15, center=(174,158), inner_text=Issues
15, url='https://github.com/Titan-Systems/titan/issues'
				listitem
					[616] link Pull requests 1, center=(320,158), inner_text=Pull requests
1, url='https://github.com/Titan-Systems/titan/pulls'
				listitem
					[621] link Discussions, center=(468,158), url='https://github.com/Titan-Systems/titan/discussions'
				listitem
					[626] link Actions, center=(583,158), url='https://github.com/Titan-Systems/titan/actions'
				listitem
					[631] link Security, center=(684,158), url='https://github.com/Titan-Systems/titan/security'
				listitem
					[636] link Insights, center=(786,158), url='https://github.com/Titan-Systems/titan/pulse'
		heading Titan-Systems/titan
		[716] button main branch, center=(404,222), expanded=False, hasPopup='menu', inner_text= main, type=button
			StaticText main
		[728] link 2 Branches, center=(509,222), type=button, url='https://github.com/Titan-Systems/titan/branches'
			strong
				StaticText 2
		[733] link 92 Tags, center=(583,222), type=button, url='https://github.com/Titan-Systems/titan/tags'
			strong
				StaticText 92
		combobox Go to file, expanded=False, hasPopup='dialog'
		[758] button Code, center=(1194,222), expanded=False, hasPopup='menu', type=button
		heading Folders and files
		table Folders and files
			rowgroup
				row
					columnheader Name
					columnheader Last commit message
					columnheader Last commit date
			rowgroup
				row
					cell Latest commit titan-systems-bot commits by titan-systems-bot Bump version: 0.11.1 → 0.11.2 Commit 1303c08  ·  2 weeks ago History 272 Commits
						heading Latest commit
						link titan-systems-bot, url='https://github.com/titan-systems-bot'
							image titan-systems-bot, url='https://avatars.githubusercontent.com/u/173221243?v=4&size=40'
						link commits by titan-systems-bot, url='https://github.com/Titan-Systems/titan/commits?author=titan-systems-bot'
						link Bump version: 0.11.1 → 0.11.2, url='https://github.com/Titan-Systems/titan/commit/1303c083a7919f90084fc3613946676965f61599'
						link Commit 1303c08, url='https://github.com/Titan-Systems/titan/commit/1303c083a7919f90084fc3613946676965f61599'
						StaticText ·
						StaticText 2 weeks ago
						heading History
						[796] link 272 Commits, center=(1181,281), url='https://github.com/Titan-Systems/titan/commits/main/'
							StaticText 272 Commits
				row
					cell .github/workflows, (Directory)
						[825] link .github/workflows, (Directory), center=(449,328), inner_text=.github/workflows, title=This path skips through empty directories, url='https://github.com/Titan-Systems/titan/tree/main/.github/workflows'
					[828] cell blacksmith.sh: Migrate workflows to Blacksmith (#149), center=(911,328)
						link blacksmith.sh: Migrate workflows to Blacksmith (, url='https://github.com/Titan-Systems/titan/commit/4dd9557ba0525bd0086b3f77bb93813e7a43cca7'
						link #149, url='https://github.com/Titan-Systems/titan/pull/149'
						link ), url='https://github.com/Titan-Systems/titan/commit/4dd9557ba0525bd0086b3f77bb93813e7a43cca7'
					[830] cell 2 months ago, center=(1179,328)
				row
					cell docs, (Directory)
						[846] link docs, (Directory), center=(410,368), inner_text=docs, title=docs, url='https://github.com/Titan-Systems/titan/tree/main/docs'
					[847] cell [CHORE] tests and docs (#150), center=(911,368)
						link [CHORE] tests and docs (, url='https://github.com/Titan-Systems/titan/commit/6b7385c61fc183307560d6899cbdde3eed0c3c87'
						link #150, url='https://github.com/Titan-Systems/titan/pull/150'
						link ), url='https://github.com/Titan-Systems/titan/commit/6b7385c61fc183307560d6899cbdde3eed0c3c87'
					[849] cell 2 months ago, center=(1179,368)
				row
					cell examples, (Directory)
						[865] link examples, (Directory), center=(425,410), inner_text=examples, title=examples, url='https://github.com/Titan-Systems/titan/tree/main/examples'
					[866] cell [CHORE] adjust warehouses to reduce cost (#181), center=(911,410)
						link [CHORE] adjust warehouses to reduce cost (, url='https://github.com/Titan-Systems/titan/commit/d37ca73232eeca83d123d5bd3873958c2ffdac20'
						link #181, url='https://github.com/Titan-Systems/titan/pull/181'
						link ), url='https://github.com/Titan-Systems/titan/commit/d37ca73232eeca83d123d5bd3873958c2ffdac20'
					[868] cell 2 weeks ago, center=(1179,410)
				row
					cell images, (Directory)
						[884] link images, (Directory), center=(418,450), inner_text=images, title=images, url='https://github.com/Titan-Systems/titan/tree/main/images'
					[885] cell bugfix (#19), center=(911,450)
						link bugfix (, url='https://github.com/Titan-Systems/titan/commit/a42c596d1e5820b94db470ee9d756729030012ae'
						link #19, url='https://github.com/Titan-Systems/titan/pull/19'
						link ), url='https://github.com/Titan-Systems/titan/commit/a42c596d1e5820b94db470ee9d756729030012ae'
					[887] cell 11 months ago, center=(1179,450)
				row
					cell prompts, (Directory)
						[903] link prompts, (Directory), center=(420,492), inner_text=prompts, title=prompts, url='https://github.com/Titan-Systems/titan/tree/main/prompts'
					[904] cell release/v0.11.0 (#174) Bump version, center=(911,492)
						link release/v0.11.0 (, url='https://github.com/Titan-Systems/titan/commit/cf5a6c36e758863bf68b0156fb36f995dc8d1c30'
						link #174, url='https://github.com/Titan-Systems/titan/pull/174'
						link ) Bump version, url='https://github.com/Titan-Systems/titan/commit/cf5a6c36e758863bf68b0156fb36f995dc8d1c30'
					[906] cell 2 weeks ago, center=(1179,492)
				row
					cell scripts, (Directory)
						[922] link scripts, (Directory), center=(415,532), inner_text=scripts, title=scripts, url='https://github.com/Titan-Systems/titan/tree/main/scripts'
					[923] cell bugfix (#19), center=(911,532)
						link bugfix (, url='https://github.com/Titan-Systems/titan/commit/a42c596d1e5820b94db470ee9d756729030012ae'
						link #19, url='https://github.com/Titan-Systems/titan/pull/19'
						link ), url='https://github.com/Titan-Systems/titan/commit/a42c596d1e5820b94db470ee9d756729030012ae'
					[925] cell 11 months ago, center=(1179,532)
				row
					cell tests, (Directory)
						[941] link tests, (Directory), center=(410,574), inner_text=tests, title=tests, url='https://github.com/Titan-Systems/titan/tree/main/tests'
					[942] cell [CHORE] adjust warehouses to reduce cost (#181), center=(911,574)
						link [CHORE] adjust warehouses to reduce cost (, url='https://github.com/Titan-Systems/titan/commit/d37ca73232eeca83d123d5bd3873958c2ffdac20'
						link #181, url='https://github.com/Titan-Systems/titan/pull/181'
						link ), url='https://github.com/Titan-Systems/titan/commit/d37ca73232eeca83d123d5bd3873958c2ffdac20'
					[944] cell 2 weeks ago, center=(1179,574)
				row
					cell titan, (Directory)
						[960] link titan, (Directory), center=(408,614), inner_text=titan, title=titan, url='https://github.com/Titan-Systems/titan/tree/main/titan'
					[961] cell [BUGFIX] fix vars for role names (#177), center=(911,614)
						link [BUGFIX] fix vars for role names (, url='https://github.com/Titan-Systems/titan/commit/dc61f7f4db513f29a33ce58694a1b61bb7219525'
						link #177, url='https://github.com/Titan-Systems/titan/pull/177'
						link ), url='https://github.com/Titan-Systems/titan/commit/dc61f7f4db513f29a33ce58694a1b61bb7219525'
					[963] cell 2 weeks ago, center=(1179,614)
				row
					cell tools, (Directory)
						[979] link tools, (Directory), center=(410,656), inner_text=tools, title=tools, url='https://github.com/Titan-Systems/titan/tree/main/tools'
					[980] cell [CHORE] adjust warehouses to reduce cost (#181), center=(911,656)
						link [CHORE] adjust warehouses to reduce cost (, url='https://github.com/Titan-Systems/titan/commit/d37ca73232eeca83d123d5bd3873958c2ffdac20'
						link #181, url='https://github.com/Titan-Systems/titan/pull/181'
						link ), url='https://github.com/Titan-Systems/titan/commit/d37ca73232eeca83d123d5bd3873958c2ffdac20'
					[982] cell 2 weeks ago, center=(1179,656)
				row
					cell .gitignore, (File)
						[998] link .gitignore, (File), center=(424,696), inner_text=.gitignore, title=.gitignore, url='https://github.com/Titan-Systems/titan/blob/main/.gitignore'
					[999] cell Iceberg (#114), center=(911,696)
						link Iceberg (, url='https://github.com/Titan-Systems/titan/commit/54d159a73cf1ae2e0601e7959856a63693291f22'
						link #114, url='https://github.com/Titan-Systems/titan/pull/114'
						link ), url='https://github.com/Titan-Systems/titan/commit/54d159a73cf1ae2e0601e7959856a63693291f22'
					[1001] cell 4 months ago, center=(1179,696)
				row
					cell LICENSE, (File)
						[1017] link LICENSE, (File), center=(425,738), inner_text=LICENSE, title=LICENSE, url='https://github.com/Titan-Systems/titan/blob/main/LICENSE'
					[1018] cell v0.1.0, center=(911,738)
						link v0.1.0, url='https://github.com/Titan-Systems/titan/commit/15adc7fc7437a0dbf2528e13ee8adb4e4cb8e572'
					[1020] cell last year, center=(1179,738)
				row
					cell MANIFEST.in, (File)
						[1036] link MANIFEST.in, (File), center=(437,778), inner_text=MANIFEST.in, title=MANIFEST.in, url='https://github.com/Titan-Systems/titan/blob/main/MANIFEST.in'
					[1037] cell Package config (#57), center=(911,778)
						link Package config (, url='https://github.com/Titan-Systems/titan/commit/b4d85dd69840839d4df038a34daf0cdcf82c9de5'
						link #57, url='https://github.com/Titan-Systems/titan/pull/57'
						link ), url='https://github.com/Titan-Systems/titan/commit/b4d85dd69840839d4df038a34daf0cdcf82c9de5'
					[1039] cell 7 months ago, center=(1179,778)
				row
					cell Makefile, (File)
						[1055] link Makefile, (File), center=(421,820), inner_text=Makefile, title=Makefile, url='https://github.com/Titan-Systems/titan/blob/main/Makefile'
					[1056] cell [FEATURE] skip show grants (#133), center=(911,820)
						link [FEATURE] skip show grants (, url='https://github.com/Titan-Systems/titan/commit/639c6765841fb4091322b564b4ea77abddc517f2'
						link #133, url='https://github.com/Titan-Systems/titan/pull/133'
						link ), url='https://github.com/Titan-Systems/titan/commit/639c6765841fb4091322b564b4ea77abddc517f2'
					[1058] cell 3 months ago, center=(1179,820)
				row
					cell README.md, (File)
						[1074] link README.md, (File), center=(437,860), inner_text=README.md, title=README.md, url='https://github.com/Titan-Systems/titan/blob/main/README.md'
					[1075] cell [CHORE] tests and docs (#150), center=(911,860)
						link [CHORE] tests and docs (, url='https://github.com/Titan-Systems/titan/commit/6b7385c61fc183307560d6899cbdde3eed0c3c87'
						link #150, url='https://github.com/Titan-Systems/titan/pull/150'
						link ), url='https://github.com/Titan-Systems/titan/commit/6b7385c61fc183307560d6899cbdde3eed0c3c87'
					[1077] cell 2 months ago, center=(1179,860)
				row
					cell conftest.py, (File)
						[1093] link conftest.py, (File), center=(429,902), inner_text=conftest.py, title=conftest.py, url='https://github.com/Titan-Systems/titan/blob/main/conftest.py'
					[1094] cell [CHORE] test account automation (#148), center=(911,902)
						link [CHORE] test account automation (, url='https://github.com/Titan-Systems/titan/commit/1c8c585f963cb9a205ff53a0350a0cb18ccf61e1'
						link #148, url='https://github.com/Titan-Systems/titan/pull/148'
						link ), url='https://github.com/Titan-Systems/titan/commit/1c8c585f963cb9a205ff53a0350a0cb18ccf61e1'
					[1096] cell 2 months ago, center=(1179,902)
				row
					cell pyproject.toml, (File)
						[1112] link pyproject.toml, (File), center=(439,942), inner_text=pyproject.toml, title=pyproject.toml, url='https://github.com/Titan-Systems/titan/blob/main/pyproject.toml'
					[1113] cell [FEATURE] Update github action (#140), center=(911,942)
						link [FEATURE] Update github action (, url='https://github.com/Titan-Systems/titan/commit/4df8f7d902a49dc63237e30ec0095e5122fc0590'
						link #140, url='https://github.com/Titan-Systems/titan/pull/140'
						link ), url='https://github.com/Titan-Systems/titan/commit/4df8f7d902a49dc63237e30ec0095e5122fc0590'
					[1115] cell 3 months ago, center=(1179,942)
				row
					cell requirements.dev.txt, (File)
						[1131] link requirements.dev.txt, (File), center=(458,984), inner_text=requirements.dev.txt, title=requirements.dev.txt, url='https://github.com/Titan-Systems/titan/blob/main/requirements.dev.txt'
					[1132] cell Resource coverage helper, center=(911,984)
						link Resource coverage helper, url='https://github.com/Titan-Systems/titan/commit/8e929c1f2362189b92ad502fc533098030c69b2e'
					[1134] cell 2 years ago, center=(1179,984)
				row
					cell requirements.txt, (File)
						[1150] link requirements.txt, (File), center=(445,1024), inner_text=requirements.txt, title=requirements.txt, url='https://github.com/Titan-Systems/titan/blob/main/requirements.txt'
					[1151] cell some cleanup, center=(911,1024)
						link some cleanup, url='https://github.com/Titan-Systems/titan/commit/fc847d75b3d1be959a2c7c6fb84283393d8d5dd7'
					[1153] cell 2 years ago, center=(1179,1024)
				row
					cell setup.py, (File)
						[1169] link setup.py, (File), center=(421,1066), inner_text=setup.py, title=setup.py, url='https://github.com/Titan-Systems/titan/blob/main/setup.py'
					[1170] cell [CHORE] dependency pinning (#168), center=(911,1066)
						link [CHORE] dependency pinning (, url='https://github.com/Titan-Systems/titan/commit/db09038d60f392378e3c9b7a3cf6a1bc830f3575'
						link #168, url='https://github.com/Titan-Systems/titan/pull/168'
						link ), url='https://github.com/Titan-Systems/titan/commit/db09038d60f392378e3c9b7a3cf6a1bc830f3575'
					[1172] cell 2 months ago, center=(1179,1066)
				row
					cell version.md, (File)
						link version.md, (File), url='https://github.com/Titan-Systems/titan/blob/main/version.md'
					cell Bump version: 0.11.1 → 0.11.2
						link Bump version: 0.11.1 → 0.11.2, url='https://github.com/Titan-Systems/titan/commit/1303c083a7919f90084fc3613946676965f61599'
					cell 2 weeks ago
		heading Repository files navigation
		navigation Repository files
			list
				listitem
					link README, url='https://github.com/Titan-Systems/titan#'
				listitem
					link Apache-2.0 license, url='https://github.com/Titan-Systems/titan#'
		button Outline, expanded=False, hasPopup='menu'
		article
			heading titan core - Snowflake infrastructure as code
				code
			link Permalink: titan core - Snowflake infrastructure as code, url='https://github.com/Titan-Systems/titan#titan-core---snowflake-infrastructure-as-code'
			paragraph
				StaticText Titan Core helps you provision, deploy, and secure resources in Snowflake. It replaces tools like Terraform, Schemachange, or Permifrost.
			paragraph
				StaticText Deploy any Snowflake resource, including users, roles, schemas, databases, integrations, pipes, stages, functions, stored procedures, and more. Convert adhoc, bug-prone SQL management scripts into simple, repeatable configuration.
			paragraph
				StaticText Titan Core is for:
			list
				listitem
					ListMarker •
					StaticText DevOps engineers looking to automate and manage Snowflake infrastructure.
				listitem
					ListMarker •
					StaticText Analytics engineers working with dbt who want to manage Snowflake resources without macros.
				listitem
					ListMarker •
					StaticText Data platform teams who need to reliably manage Snowflake with CI/CD.
				listitem
					ListMarker •
					StaticText Organizations that prefer a git-based workflow for infrastructure management.
				listitem
					ListMarker •
					StaticText Teams seeking to replace Terraform for Snowflake-related tasks.
			code
				StaticText ╔══════════╗                                           ╔═══════════╗       
    ║  CONFIG  ║                                           ║ SNOWFLAKE ║       
    ╚══════════╝                                           ╚═══════════╝       
  ┏━━━━━━━━━━━┓                                        ┏━━━━━━━━━━━┓            
┌─┫ WAREHOUSE ┣─────┐                                ┌─┫ WAREHOUSE ┣───────────┐
│ ┗━━━━━━━━━━━┛     │                    ALTER       │ ┗━━━━━━━━━━━┛           │
│ name:         ETL │─────┐           ┌─ WAREHOUSE ─▶│ name:         ETL       │
│ auto_suspend: 60  │     │           │              │ auto_suspend: 300 -> 60 │
└───────────────────┘  ╔══▼═══════════╩═╗            └─────────────────────────┘
                       ║                ║                                      
                       ║   TITAN CORE   ║                                      
  ┏━━━━━━┓             ║                ║              ┏━━━━━━┓                
┌─┫ ROLE ┣──────────┐  ╚══▲═══════════╦═╝            ┌─┫ ROLE ┣────────────────┐
│ ┗━━━━━━┛          │     │           │              │ ┗━━━━━━┛                │
│ name: TRANSFORMER │─────┘           └─ CREATE ────▶│ name: TRANSFORMER       │
└───────────────────┘                    ROLE        └─────────────────────────┘
			button Copy
			heading Key Features
			link Permalink: Key Features, url='https://github.com/Titan-Systems/titan#key-features'
			list
				listitem
					ListMarker •
					paragraph
						strong
							StaticText Declarative
						StaticText » Generates the right SQL to make your config and account match
				listitem
					ListMarker •
					paragraph
						strong
							StaticText Comprehensive
						StaticText » Nearly every Snowflake resource is supported
				listitem
					ListMarker •
					paragraph
						strong
							StaticText Flexible
						StaticText » Write resource configuration in YAML or Python
				listitem
					ListMarker •
					paragraph
						strong
							StaticText Fast
						StaticText » Titan Core runs 50-90% faster than Terraform and Permifrost
				listitem
					ListMarker •
					paragraph
						strong
							StaticText Migration-friendly
						StaticText » Generate config automatically with the export CLI
			heading Open Source
			link Permalink: Open Source, url='https://github.com/Titan-Systems/titan#open-source'
			paragraph
				StaticText This project is licensed under the Apache 2.0 License - see
				link LICENSE, url='https://github.com/Titan-Systems/titan/blob/main/LICENSE'
				StaticText for details. The source code for Titan Core is available on
				link Github, url='https://github.com/Titan-Systems/titan'
				StaticText .
			heading Documentation
			link Permalink: Documentation, url='https://github.com/Titan-Systems/titan#documentation'
			paragraph
				StaticText You can find comprehensive
				link Titan Core documentation on GitBook, url='https://titan-core.gitbook.io/titan-core'
				StaticText .
			heading Getting Started
			link Permalink: Getting Started, url='https://github.com/Titan-Systems/titan#getting-started'
			paragraph
				StaticText If you're new, the best place to start is with the Python package.
			heading Install from PyPi (MacOS, Linux)
			link Permalink: Install from PyPi (MacOS, Linux), url='https://github.com/Titan-Systems/titan#install-from-pypi-macos-linux'
			StaticText python -m venv .venv
			StaticText source
			StaticText .venv/bin/activate
python -m pip install titan-core
			button Copy
			heading Install from PyPi (Windows)
			link Permalink: Install from PyPi (Windows), url='https://github.com/Titan-Systems/titan#install-from-pypi-windows'
			StaticText python -m venv .venv
.\.venv\Scripts\activate
python -m pip install titan-core
			button Copy
			heading Python example
			link Permalink: Python example, url='https://github.com/Titan-Systems/titan#python-example'
			StaticText import
			StaticText os
			StaticText import
			StaticText snowflake
			StaticText .
			StaticText connector
			StaticText from
			StaticText titan
			StaticText .
			StaticText blueprint
			StaticText import
			StaticText Blueprint
			StaticText ,
			StaticText print_plan
			StaticText from
			StaticText titan
			StaticText .
			StaticText resources
			StaticText import
			StaticText Grant
			StaticText ,
			StaticText Role
			StaticText ,
			StaticText Warehouse
			StaticText # Configure resources by instantiating Python objects.
			StaticText role
			StaticText =
			StaticText Role
			StaticText (
			StaticText name
			StaticText =
			StaticText "transformer"
			StaticText )
			StaticText warehouse
			StaticText =
			StaticText Warehouse
			StaticText (
			StaticText name
			StaticText =
			StaticText "transforming"
			StaticText ,
			StaticText warehouse_size
			StaticText =
			StaticText "large"
			StaticText ,
			StaticText auto_suspend
			StaticText =
			StaticText 60
			StaticText ,
)
			StaticText usage_grant
			StaticText =
			StaticText Grant
			StaticText (
			StaticText priv
			StaticText =
			StaticText "usage"
			StaticText ,
			StaticText to
			StaticText =
			StaticText role
			StaticText ,
			StaticText on
			StaticText =
			StaticText warehouse
			StaticText )
			StaticText # Titan compares your config to a Snowflake account. Create a Snowflake
			StaticText # connection to allow Titan to connect to your account.
			StaticText connection_params
			StaticText =
			StaticText {
			StaticText "account"
			StaticText :
			StaticText os
			StaticText .
			StaticText environ
			StaticText [
			StaticText "SNOWFLAKE_ACCOUNT"
			StaticText ],
			StaticText "user"
			StaticText :
			StaticText os
			StaticText .
			StaticText environ
			StaticText [
			StaticText "SNOWFLAKE_USER"
			StaticText ],
			StaticText "password"
			StaticText :
			StaticText os
			StaticText .
			StaticText environ
			StaticText [
			StaticText "SNOWFLAKE_PASSWORD"
			StaticText ],
			StaticText "role"
			StaticText :
			StaticText "SYSADMIN"
			StaticText ,
}
			StaticText session
			StaticText =
			StaticText snowflake
			StaticText .
			StaticText connector
			StaticText .
			StaticText connect
			StaticText (
			StaticText **
			StaticText connection_params
			StaticText )
			StaticText # Create a Blueprint and pass your resources into it. A Blueprint helps you
			StaticText # validate and deploy a set of resources.
			StaticText bp
			StaticText =
			StaticText Blueprint
			StaticText (
			StaticText resources
			StaticText =
			StaticText [
			StaticText role
			StaticText ,
			StaticText warehouse
			StaticText ,
			StaticText usage_grant
			StaticText ,
])
			StaticText # Blueprint works like Terraform. Calling plan(...) will compare your config
			StaticText # to the state of your Snowflake account and return a list of changes.
			StaticText plan
			StaticText =
			StaticText bp
			StaticText .
			StaticText plan
			StaticText (
			StaticText session
			StaticText )
			StaticText print_plan
			StaticText (
			StaticText plan
			StaticText )
			StaticText # =>
			StaticText """
			StaticText » titan core
			StaticText » Plan: 4 to add, 0 to change, 0 to destroy.
			StaticText + urn::ABCD123:warehouse/transforming {
			StaticText + name                                = "transforming"
			StaticText + owner                               = "SYSADMIN"
			StaticText + warehouse_type                      = "STANDARD"
			StaticText + warehouse_size                      = "LARGE"
			StaticText ...
			StaticText }
			StaticText + urn::ABCD123:role/transformer {
			StaticText + name    = "transformer"
			StaticText + owner   = "USERADMIN"
			StaticText + tags    = None
			StaticText + comment = None
			StaticText }
			StaticText + urn::ABCD123:grant/TRANSFORMER?priv=USAGE&on=warehouse/TRANSFORMING {
			StaticText + priv         = "USAGE"
			StaticText + on           = "transforming"
			StaticText + on_type      = "WAREHOUSE"
			StaticText + to           = TRANSFORMER
			StaticText ...
			StaticText }
			StaticText """
			StaticText # Calling apply(...) will convert your plan into the right set of SQL commands
			StaticText # and run them against your Snowflake account.
			StaticText bp
			StaticText .
			StaticText apply
			StaticText (
			StaticText session
			StaticText ,
			StaticText plan
			StaticText )
			StaticText # =>
			StaticText """
			StaticText [TITAN_USER:SYSADMIN]  > USE SECONDARY ROLES ALL
			StaticText [TITAN_USER:SYSADMIN]  > CREATE WAREHOUSE TRANSFORMING warehouse_type = STANDARD ...
			StaticText [TITAN_USER:SYSADMIN]  > USE ROLE USERADMIN
			StaticText [TITAN_USER:USERADMIN] > CREATE ROLE TRANSFORMER
			StaticText [TITAN_USER:USERADMIN] > USE ROLE SYSADMIN
			StaticText [TITAN_USER:SYSADMIN]  > GRANT USAGE ON WAREHOUSE transforming TO TRANSFORMER
			StaticText """
			button Copy
			heading Using the CLI
			link Permalink: Using the CLI, url='https://github.com/Titan-Systems/titan#using-the-cli'
			paragraph
				StaticText You can use the CLI to generate a plan, apply a plan, or export resources. To use the CLI, install the Python package and call
				code
					StaticText python -m titan
				StaticText from the command line.
			paragraph
				StaticText The CLI allows you to
				code
					StaticText plan
				StaticText and
				code
					StaticText apply
				StaticText a Titan Core YAML config. You can specify a single input file or a directory of configs.
			paragraph
				StaticText In addition to
				code
					StaticText plan
				StaticText and
				code
					StaticText apply
				StaticText , the CLI also allows you to
				code
					StaticText export
				StaticText resources. This makes it easy to generate a config for an existing Snowflake environment.
			paragraph
				StaticText To connect with Snowflake, the CLI uses environment variables. The following `are supported:
			list
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_ACCOUNT
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_USER
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_PASSWORD
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_DATABASE
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_SCHEMA
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_ROLE
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_WAREHOUSE
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_MFA_PASSCODE
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_AUTHENTICATOR
			heading CLI Example
			link Permalink: CLI Example, url='https://github.com/Titan-Systems/titan#cli-example'
			paragraph
				StaticText Show the help message
			StaticText titan --help
			StaticText #
			StaticText Usage: titan [OPTIONS] COMMAND [ARGS]...
			StaticText #
			StaticText #
			StaticText titan core helps you manage your Snowflake environment.
			StaticText #
			StaticText #
			StaticText Options:
			StaticText #
			StaticText --help  Show this message and exit.
			StaticText #
			StaticText #
			StaticText Commands:
			StaticText #
			StaticText apply    Apply a resource config to a Snowflake account
			StaticText #
			StaticText connect  Test the connection to Snowflake
			StaticText #
			StaticText export   Generate a resource config for existing Snowflake resources
			StaticText #
			StaticText plan     Compare a resource config to the current state of Snowflake
			button Copy
			paragraph
				StaticText Apply a resource config to Snowflake
			StaticText #
			StaticText Create a resource config file
			StaticText cat
			StaticText <<
			StaticText EOF
			StaticText > titan.yml
			StaticText roles:
			StaticText - name: transformer
			StaticText warehouses:
			StaticText - name: transforming
			StaticText warehouse_size: LARGE
			StaticText auto_suspend: 60
			StaticText grants:
			StaticText - to_role: transformer
			StaticText priv: usage
			StaticText on_warehouse: transforming
			StaticText EOF
			StaticText #
			StaticText Set connection variables
			StaticText export
			StaticText SNOWFLAKE_ACCOUNT=
			StaticText "
			StaticText my-account
			StaticText "
			StaticText export
			StaticText SNOWFLAKE_USER=
			StaticText "
			StaticText my-user
			StaticText "
			StaticText export
			StaticText SNOWFLAKE_PASSWORD=
			StaticText "
			StaticText my-password
			StaticText "
			StaticText #
			StaticText Generate a plan
			StaticText titan plan --config titan.yml
			StaticText #
			StaticText Apply the config
			StaticText titan apply --config titan.yml
			button Copy
			paragraph
				StaticText Export existing Snowflake resources to YAML.
			StaticText titan
			StaticText export
			StaticText \
  --resource=warehouse,grant,role \
  --out=titan.yml
			button Copy
			paragraph
				StaticText The Titan Core Python package installs the CLI script
				code
					StaticText titan
				StaticText . You can alternatively use Python CLI module syntax if you need fine-grained control over the Python environment.
			StaticText python -m titan plan --config titan.yml
			button Copy
			heading Using the GitHub Action
			link Permalink: Using the GitHub Action, url='https://github.com/Titan-Systems/titan#using-the-github-action'
			paragraph
				StaticText The Titan Core GitHub Action allows you to automate the deployment of Snowflake resources using a git-based workflow.
			heading GitHub Action Example
			link Permalink: GitHub Action Example, url='https://github.com/Titan-Systems/titan#github-action-example'
			StaticText -- .github/workflows/titan.yml
			StaticText name
			StaticText :
			StaticText Deploy to Snowflake with Titan
			StaticText on
			StaticText :
			StaticText push
			StaticText :
			StaticText branches
			StaticText :
			StaticText [ main ]
			StaticText paths
			StaticText :
    -
			StaticText titan/**
			StaticText jobs
			StaticText :
			StaticText deploy
			StaticText :
			StaticText runs-on
			StaticText :
			StaticText ubuntu-latest
			StaticText steps
			StaticText :
      -
			StaticText name
			StaticText :
			StaticText Checkout code
			StaticText uses
			StaticText :
			StaticText actions/checkout@v4
			StaticText -
			StaticText name
			StaticText :
			StaticText Deploy to Snowflake
			StaticText uses
			StaticText :
			StaticText Titan-Systems/titan-core-action@main
			StaticText with
			StaticText :
			StaticText run-mode
			StaticText :
			StaticText create-or-update
			StaticText resource-path
			StaticText :
			StaticText ./titan
			StaticText allowlist
			StaticText :
			StaticText warehouse,role,grant
			StaticText dry-run
			StaticText :
			StaticText false
			StaticText env
			StaticText :
			StaticText SNOWFLAKE_ACCOUNT
			StaticText :
			StaticText ${{ secrets.SNOWFLAKE_ACCOUNT }}
			StaticText SNOWFLAKE_USER
			StaticText :
			StaticText ${{ secrets.SNOWFLAKE_USER }}
			StaticText SNOWFLAKE_PASSWORD
			StaticText :
			StaticText ${{ secrets.SNOWFLAKE_PASSWORD }}
			StaticText SNOWFLAKE_ROLE
			StaticText :
			StaticText ${{ secrets.SNOWFLAKE_ROLE }}
			StaticText SNOWFLAKE_WAREHOUSE
			StaticText :
			StaticText ${{ secrets.SNOWFLAKE_WAREHOUSE }}
			button Copy
			heading Titan Core Limitations
			link Permalink: Titan Core Limitations, url='https://github.com/Titan-Systems/titan#titan-core-limitations'
			list
				listitem
					ListMarker •
					strong
						StaticText Titan Core uses names as unique identifiers
					StaticText . Renaming a resource will create a new one.
				listitem
					ListMarker •
					StaticText Titan Core is not an ORM. It's not built to replace tools like SQLAlchemy.
				listitem
					ListMarker •
					StaticText Titan Core is under active development. Some resources are not yet supported.
			heading titan core vs other tools
				code
			link Permalink: titan core vs other tools, url='https://github.com/Titan-Systems/titan#titan-core-vs-other-tools'
			table
				rowgroup
					row
						columnheader Feature
						columnheader Titan Core
						columnheader Terraform
						columnheader Schemachange
						columnheader Permifrost
						columnheader SnowDDL
				rowgroup
					row
						cell Plan and Execute Changes
						cell ✅
						cell ✅
						cell ❌
						cell ✅
						cell ✅
					row
						cell Declarative Config
						cell ✅
						cell ✅
						cell ❌
						cell ✅
						cell ✅
					row
						cell No State File Dependency
						cell ✅
						cell ❌
						cell ✅
						cell ✅
						cell ✅
					row
						cell Python-Based Definitions
						cell ✅
						cell w/ CDKTF
						cell ❌
						cell ❌
						cell ✅
					row
						cell SQL Support
						cell ✅
						cell ❌
						cell ✅
						cell ❌
						cell ❌
					row
						cell Dynamic Role Switching
						cell ✅
						cell ❌
						cell N/A
						cell ❌
						cell ❌
					row
						cell Export Snowflake resources
						cell ✅
						cell ❌
						cell ❌
						cell ❌
						cell ❌
			heading titan core vs Terraform
				code
			link Permalink: titan core vs Terraform, url='https://github.com/Titan-Systems/titan#titan-core-vs-terraform'
			paragraph
				StaticText Terraform is an infrastructure-as-code tool using the HCL config language.
			paragraph
				StaticText The
				link Snowflake provider for Terraform, url='https://github.com/Snowflake-Labs/terraform-provider-snowflake'
				StaticText is limited to
				strong
					StaticText 1 role per provider
				StaticText . This limitation is at odds with Snowflake's design, which is built to use multiple roles. This mismatch forces you into a complex multi-provider setup which can result in drift, permission errors, and broken plans.
			paragraph
				StaticText Titan Core streamlines this with
				strong
					StaticText dynamic role switching
				StaticText . Titan Core automatically detects which role is needed for a given change, and switches to that role before making it. This speeds up development cycles and helps eliminate the use of
				code
					StaticText ACCOUNTADMIN
				StaticText .
			paragraph
				StaticText Titan Core doesn't use a state file. This provides more accurate plans and eliminates issues with stale state.
			heading titan core vs Schemachange
				code
			link Permalink: titan core vs Schemachange, url='https://github.com/Titan-Systems/titan#titan-core-vs-schemachange'
			paragraph
				link Schemachange, url='https://github.com/Snowflake-Labs/schemachange'
				StaticText is a database migration tool based on Flyway. It uses SQL scripts to deploy resources to different environments.
			paragraph
				StaticText Schemachange is an imperative migration tool. For developers, that means you must know Snowflake's current state and the exact SQL commands needed to update it to the desired state. If environments get changed outside of the tool, your migration scripts may need significant adjustments.
			paragraph
				StaticText Titan Core simplifies this with a declarative approach. With Titan Core, just define what an environment should look like, you don't need to know the detailed steps or SQL commands needed to get there.
			paragraph
				StaticText Declarative config is less error-prone and more scalable, especially in dynamic and complex data environments.
			heading titan core vs Permifrost
				code
			link Permalink: titan core vs Permifrost, url='https://github.com/Titan-Systems/titan#titan-core-vs-permifrost'
			paragraph
				link Permifrost, url='https://gitlab.com/gitlab-data/permifrost/'
				StaticText is an access-management tool for Snowflake. It helps you automate the creation of users, roles, and grants. Permifrost only manages permissions, it doesn't manage any other aspect of your Snowflake account.
			paragraph
				StaticText Permifrost can be very slow. Running simple Permifrost configs can take minutes to run. Titan Core is designed to run in seconds, even with complex environments.
			heading titan core vs SnowDDL
				code
			link Permalink: titan core vs SnowDDL, url='https://github.com/Titan-Systems/titan#titan-core-vs-snowddl'
			paragraph
				link SnowDDL, url='https://github.com/littleK0i/SnowDDL'
				StaticText is a declarative object management tool for Snowflake, similar to Titan Core. It uses a streamlined
				link permissions model, url='https://docs.snowddl.com/guides/permission-model'
				StaticText that simplifies granting read and write access to databases and schemas.
			paragraph
				StaticText SnowDDL takes a strongly opinionated stance on roles in Snowflake. If you don't need a
				link 3-tier role heirarchy, url='https://docs.snowddl.com/guides/role-hierarchy'
				StaticText , SnowDDL may not be a good fit.
			heading Resource support
			link Permalink: Resource support, url='https://github.com/Titan-Systems/titan#resource-support'
			heading Legend
			link Permalink: Legend, url='https://github.com/Titan-Systems/titan#legend'
			list
				listitem
					ListMarker •
					StaticText ✅ Supported
				listitem
					ListMarker •
					StaticText 🚧 Unstable
				listitem
					ListMarker •
					StaticText ❌ Not Yet Supported
			table
				rowgroup
					row
						columnheader Name
						columnheader Supported
				rowgroup
					row
						cell Account Resources
							strong
						cell
					row
						cell Account Parameter
						cell ✅
					row
						cell API Integration
						cell ✅
					row
						cell Catalog Integration
						cell
					row
						cell ↳ Glue
						cell ✅
					row
						cell ↳ Object Store
						cell ✅
					row
						cell Compute Pool
						cell ✅
					row
						cell Connection
						cell ❌
					row
						cell Database
						cell ✅
					row
						cell External Access Integration
						cell ✅
					row
						cell External Volume
						cell ✅
					row
						cell Failover Group
						cell 🚧
					row
						cell Grant
						cell
					row
						cell ↳ Future Grant
						cell ✅
					row
						cell ↳ Privilege Grant
						cell ✅
					row
						cell ↳ Role Grant
						cell ✅
					row
						cell Network Policy
						cell ✅
					row
						cell Notification Integration
						cell
					row
						cell ↳ Email
						cell 🚧
					row
						cell ↳ AWS
						cell 🚧
					row
						cell ↳ Azure
						cell 🚧
					row
						cell ↳ GCP
						cell 🚧
					row
						cell Replication Group
						cell 🚧
					row
						cell Resource Monitor
						cell ✅
					row
						cell Role
						cell ✅
					row
						cell Role Grant
						cell ✅
					row
						cell Scanner Package
						cell ✅
					row
						cell Security Integration
						cell
					row
						cell ↳ External API
						cell ❌
					row
						cell ↳ External OAuth
						cell ❌
					row
						cell ↳ Snowflake OAuth
						cell 🚧
					row
						cell ↳ SAML2
						cell ❌
					row
						cell ↳ SCIM
						cell ❌
					row
						cell Share
						cell ✅
					row
						cell Storage Integration
						cell
					row
						cell ↳ AWS
						cell ✅
					row
						cell ↳ Azure
						cell ✅
					row
						cell ↳ GCS
						cell ✅
					row
						cell Tag Reference
						cell ✅
					row
						cell User
						cell ✅
					row
						cell Warehouse
						cell ✅
					row
						cell
						cell
					row
						cell Database Resources
							strong
						cell
					row
						cell Database Role
						cell ✅
					row
						cell Schema
						cell ✅
					row
						cell
						cell
					row
						cell Schema Resources
							strong
						cell
					row
						cell Aggregation Policy
						cell ✅
					row
						cell Alert
						cell ✅
					row
						cell Authentication Policy
						cell ✅
					row
						cell Dynamic Table
						cell ✅
					row
						cell Event Table
						cell ✅
					row
						cell External Function
						cell 🚧
					row
						cell External Table
						cell ❌
					row
						cell File Format
						cell
					row
						cell ↳ CSV
						cell ✅
					row
						cell ↳ JSON
						cell ✅
					row
						cell ↳ AVRO
						cell ❌
					row
						cell ↳ ORC
						cell ❌
					row
						cell ↳ Parquet
						cell ✅
					row
						cell Hybrid Table
						cell 🚧
					row
						cell Iceberg Table
						cell
					row
						cell ↳ Snowflake Catalog
						cell ✅
					row
						cell ↳ AWS Glue
						cell ❌
					row
						cell ↳ Iceberg files
						cell ❌
					row
						cell ↳ Delta files
						cell ❌
					row
						cell ↳ REST Catalog
						cell ❌
					row
						cell ↳ Open Catalog
						cell ❌
					row
						cell Image Repository
						cell ✅
					row
						cell Masking Policy
						cell ❌
					row
						cell Materialized View
						cell 🚧
					row
						cell Model
						cell ❌
					row
						cell Network Rule
						cell ✅
					row
						cell Notebook
						cell ✅
					row
						cell Packages Policy
						cell ✅
					row
						cell Password Policy
						cell ✅
					row
						cell Pipe
						cell ✅
					row
						cell Projection Policy
						cell ❌
					row
						cell Row Access Policy
						cell ❌
					row
						cell Secret
						cell
					row
						cell ↳ Generic
						cell ✅
					row
						cell ↳ OAuth
						cell ✅
					row
						cell ↳ Password
						cell ✅
					row
						cell Sequence
						cell ✅
					row
						cell Service
						cell ✅
					row
						cell Session Policy
						cell 🚧
					row
						cell Stage
						cell ✅
					row
						cell ↳ External
						cell ✅
					row
						cell ↳ Internal
						cell ✅
					row
						cell Stored Procedure
						cell
					row
						cell ↳ Java
						cell ❌
					row
						cell ↳ Javascript
						cell ❌
					row
						cell ↳ Python
						cell 🚧
					row
						cell ↳ Scala
						cell ❌
					row
						cell ↳ SQL
						cell ❌
					row
						cell Stream
						cell
					row
						cell ↳ External Table
						cell ❌
					row
						cell ↳ Stage
						cell ✅
					row
						cell ↳ Table
						cell ✅
					row
						cell ↳ View
						cell ✅
					row
						cell Streamlit
						cell ❌
					row
						cell Table
						cell 🚧
					row
						cell Tag
						cell ✅
					row
						cell Task
						cell ✅
					row
						cell User-Defined Function
						cell
					row
						cell ↳ Java
						cell ❌
					row
						cell ↳ Javascript
						cell 🚧
					row
						cell ↳ Python
						cell ✅
					row
						cell ↳ Scala
						cell ❌
					row
						cell ↳ SQL
						cell ❌
					row
						cell View
						cell ✅
			heading What if I need a type of resource isn't supported?
			link Permalink: What if I need a type of resource isn't supported?, url='https://github.com/Titan-Systems/titan#what-if-i-need-a-type-of-resource-isnt-supported'
			paragraph
				StaticText Please
				link create a GitHub issue, url='https://github.com/Titan-Systems/titan/issues'
				StaticText if there's a resource you need that isn't currently supported.
			heading Contributing
			link Permalink: Contributing, url='https://github.com/Titan-Systems/titan#contributing'
			paragraph
				StaticText Contributions are welcome! Titan Core does not require a contributor license agreement.
			heading The End
			link Permalink: The End, url='https://github.com/Titan-Systems/titan#the-end'
			paragraph
				StaticText If you got this far, don't forget to star this repo.
		LayoutTable
			LayoutTableRow
				LayoutTableCell About Titan Core - Snowflake infrastructure-as-code. Provision environments, automate deploys, CI/CD. Manage RBAC, users, roles, and data access. Declarative Python Resource API. Change Management tool for the Snowflake data warehouse. Topics devops snowflake data-warehouse secops data-engineering dataops rbac data-governance compliance-as-code Resources Readme License Apache-2.0 license Activity Custom properties Stars 444 stars Watchers 18 watching Forks 32 forks Report repository
					heading About
					paragraph
					heading Topics
					[2125] link devops, center=(1302,446), title=Topic: devops, url='https://github.com/topics/devops'
					[2126] link snowflake, center=(1375,446), title=Topic: snowflake, url='https://github.com/topics/snowflake'
					[2127] link data-warehouse, center=(1472,446), title=Topic: data-warehouse, url='https://github.com/topics/data-warehouse'
					[2128] link secops, center=(1302,474), title=Topic: secops, url='https://github.com/topics/secops'
					[2129] link data-engineering, center=(1393,474), title=Topic: data-engineering, url='https://github.com/topics/data-engineering'
					[2130] link dataops, center=(1486,474), title=Topic: dataops, url='https://github.com/topics/dataops'
					[2131] link rbac, center=(1295,502), title=Topic: rbac, url='https://github.com/topics/rbac'
					[2132] link data-governance, center=(1378,502), title=Topic: data-governance, url='https://github.com/topics/data-governance'
					[2133] link compliance-as-code, center=(1337,530), title=Topic: compliance-as-code, url='https://github.com/topics/compliance-as-code'
					heading Resources
					[2136] link Readme, center=(1312,572), inner_text= Readme, url='https://github.com/Titan-Systems/titan#readme-ov-file'
					heading License
					[2140] link Apache-2.0 license, center=(1345,601), inner_text= Apache-2.0 license, url='https://github.com/Titan-Systems/titan#Apache-2.0-1-ov-file'
					[2144] link Activity, center=(1308,630), inner_text= Activity, url='https://github.com/Titan-Systems/titan/activity'
					[2148] link Custom properties, center=(1343,659), inner_text= Custom properties, url='https://github.com/Titan-Systems/titan/custom-properties'
					heading Stars
					[2153] link 444 stars, center=(1315,688), inner_text= 444 stars, url='https://github.com/Titan-Systems/titan/stargazers'
						strong
					heading Watchers
					[2158] link 18 watching, center=(1323,717), inner_text= 18 watching, url='https://github.com/Titan-Systems/titan/watchers'
						strong
					heading Forks
					[2163] link 32 forks, center=(1311,746), inner_text= 32 forks, url='https://github.com/Titan-Systems/titan/forks'
						strong
					[2167] link Report repository, center=(1326,775), url='https://github.com/contact/report-content?content_url=https%3A%2F%2Fgithub.com%2FTitan-Systems%2Ftitan&report=Titan-Systems+%28user%29'
			LayoutTableRow
				LayoutTableCell Releases 47 v0.11.1 Latest 2 weeks ago + 46 releases
					heading Releases 47
						[2171] link Releases 47, center=(1323,830), url='https://github.com/Titan-Systems/titan/releases'
					[2173] link v0.11.1 Latest 2 weeks ago, center=(1420,878), inner_text=v0.11.1
Latest, url='https://github.com/Titan-Systems/titan/releases/tag/v0.11.1'
						StaticText v0.11.1
						StaticText Latest
						StaticText 2 weeks ago
					[2181] link + 46 releases, center=(1314,924), url='https://github.com/Titan-Systems/titan/releases'
			LayoutTableRow
				LayoutTableCell Contributors 13 @teej @titan-systems-bot @titan-teej @dwreeves @mlavaert @jcrobak @blbuford @jamesweakley @MartinCairnsSQL @rcohngru @rcohngru-ab-carval @jeff-skoldberg-gmds @blacksmith-sh[bot]
					heading Contributors 13
						[2188] link Contributors 13, center=(1420,980), inner_text=Contributors
13, url='https://github.com/Titan-Systems/titan/graphs/contributors'
					list
						listitem
							link @teej, url='https://github.com/teej'
								image @teej, url='https://avatars.githubusercontent.com/u/1796?s=64&v=4'
						listitem
							link @titan-systems-bot, url='https://github.com/titan-systems-bot'
								image @titan-systems-bot, url='https://avatars.githubusercontent.com/u/173221243?s=64&v=4'
						listitem
							link @titan-teej, url='https://github.com/titan-teej'
								image @titan-teej, url='https://avatars.githubusercontent.com/u/157928223?s=64&v=4'
						listitem
							link @dwreeves, url='https://github.com/dwreeves'
								image @dwreeves, url='https://avatars.githubusercontent.com/u/31971762?s=64&v=4'
						listitem
							link @mlavaert, url='https://github.com/mlavaert'
								image @mlavaert, url='https://avatars.githubusercontent.com/u/1068047?s=64&v=4'
						listitem
							link @jcrobak, url='https://github.com/jcrobak'
								image @jcrobak, url='https://avatars.githubusercontent.com/u/374566?s=64&v=4'
						listitem
							link @blbuford, url='https://github.com/blbuford'
								image @blbuford, url='https://avatars.githubusercontent.com/u/1200142?s=64&v=4'
						listitem
							link @jamesweakley, url='https://github.com/jamesweakley'
								image @jamesweakley, url='https://avatars.githubusercontent.com/u/2681392?s=64&v=4'
						listitem
							link @MartinCairnsSQL, url='https://github.com/MartinCairnsSQL'
								image @MartinCairnsSQL, url='https://avatars.githubusercontent.com/u/4314538?s=64&v=4'
						listitem
							link @rcohngru, url='https://github.com/rcohngru'
								image @rcohngru, url='https://avatars.githubusercontent.com/u/26910097?s=64&v=4'
						listitem
							link @rcohngru-ab-carval, url='https://github.com/rcohngru-ab-carval'
								image @rcohngru-ab-carval, url='https://avatars.githubusercontent.com/u/120593669?s=64&v=4'
						listitem
							link @jeff-skoldberg-gmds, url='https://github.com/jeff-skoldberg-gmds'
								image @jeff-skoldberg-gmds, url='https://avatars.githubusercontent.com/u/138161184?s=64&v=4'
						listitem
							link @blacksmith-sh[bot], url='https://github.com/apps/blacksmith-sh'
								image @blacksmith-sh[bot], url='https://avatars.githubusercontent.com/in/807020?s=64&v=4'
			LayoutTableRow
				LayoutTableCell Languages Python 99.9 Makefile 0.1 Python 99.9%Makefile 0.1%
					heading Languages
					list
						listitem
							link Python 99.9%, url='https://github.com/Titan-Systems/titan/search?l=python'
						listitem
							link Makefile 0.1%, url='https://github.com/Titan-Systems/titan/search?l=makefile'
	contentinfo
		heading Footer
		link Homepage, url='https://github.com/'
		StaticText © 2025 GitHub, Inc.
		navigation Footer
			heading Footer navigation
			list Footer navigation
				listitem
					link Terms, url='https://docs.github.com/site-policy/github-terms/github-terms-of-service'
				listitem
					link Privacy, url='https://docs.github.com/site-policy/privacy-policies/github-privacy-statement'
				listitem
					link Security, url='https://github.com/security'
				listitem
					link Status, url='https://www.githubstatus.com/'
				listitem
					link Docs, url='https://docs.github.com/'
				listitem
					link Contact, url='https://support.github.com/?tags=dotcom-footer'
				listitem
					button Manage cookies
				listitem
					button Do not share my personal information
	generic, atomic
	generic, atomic
```
</details>

**Reasoning for action:** By clicking on the 'View Repo' link, I'm redirected to the GitHub repository for Titan Systems. This is essential because the user story specifies the need to explore the repository to understand existing issues and potential features. Accessing the repository allows me to find relevant sections like 'Issues', where discussions and details about any open issues are tracked. Thus, this action directly leads me towards fulfilling the user story's requirements.

**Action:** click('67') # Click on the 'View Repo' link to explore the GitHub repository.

**Change Description:** The browser navigated from the Titan Core Access Management page to the Titan-Systems GitHub repository, displaying the repository's content including navigation menus, links to files and directories, commit history, and project documentation.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://github.com/Titan-Systems/titan

https://github.com/Titan-Systems/titan/issues

**Content (before/after):** 

```
RootWebArea GitHub - Titan-Systems/titan: Titan Core - Snowflake infrastructure-as-code. Provision environments, automate deploys, CI/CD. Manage RBAC, users, roles, and data access. Declarative Python Resource API. Change Management tool for the Snowflake data warehouse., focused, url='https://github.com/Titan-Systems/titan'
	link Skip to content, url='https://github.com/Titan-Systems/titan#start-of-content'
	banner
		heading Navigation Menu
		[193] link Homepage, center=(48,36), url='https://github.com/'
```
<details><summary>Show more</summary>

```
		navigation Global
			list
				listitem
					[202] button Product, center=(126,36), expanded=False, type=button
				listitem
					[264] button Solutions, center=(222,36), expanded=False, type=button
				listitem
					[306] button Resources, center=(329,36), expanded=False, type=button
				listitem
					[341] button Open Source, center=(451,36), expanded=False, type=button
				listitem
					[367] button Enterprise, center=(570,36), expanded=False, type=button
				listitem
					[397] link Pricing, center=(657,36), url='https://github.com/pricing'
		[400] button Search or jump to…, center=(1564,36), hasPopup='dialog', inner_text=Search or jump to..., type=button
			StaticText Search or jump to...
		[521] link Sign in, center=(1769,36), url='https://github.com/login?return_to=https%3A%2F%2Fgithub.com%2FTitan-Systems%2Ftitan'
		[522] link Sign up, center=(1851,36), url='https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F%3Cuser-name%3E%2F%3Crepo-name%3E&source=header-repo&source_repo=Titan-Systems%2Ftitan'
	main
		[547] link Titan-Systems, center=(120,103), url='https://github.com/Titan-Systems'
		StaticText /
		strong
			[550] link titan, center=(218,103), url='https://github.com/Titan-Systems/titan'
		StaticText Public
		list
			listitem
				[556] link You must be signed in to change notification settings, center=(1593,102), inner_text=Notifications, url='https://github.com/login?return_to=%2FTitan-Systems%2Ftitan'
					StaticText Notifications
			listitem
				[560] link Fork 32, center=(1712,102), url='https://github.com/login?return_to=%2FTitan-Systems%2Ftitan'
			listitem
				[565] link You must be signed in to star a repository, center=(1831,102), inner_text= Star 444, url='https://github.com/login?return_to=%2FTitan-Systems%2Ftitan'
					StaticText Star
		navigation Repository
			list
				listitem
					[606] link Code, center=(70,158), url='https://github.com/Titan-Systems/titan'
				listitem
					[611] link Issues 15, center=(174,158), inner_text=Issues
15, url='https://github.com/Titan-Systems/titan/issues'
				listitem
					[616] link Pull requests 1, center=(320,158), inner_text=Pull requests
1, url='https://github.com/Titan-Systems/titan/pulls'
				listitem
					[621] link Discussions, center=(468,158), url='https://github.com/Titan-Systems/titan/discussions'
				listitem
					[626] link Actions, center=(583,158), url='https://github.com/Titan-Systems/titan/actions'
				listitem
					[631] link Security, center=(684,158), url='https://github.com/Titan-Systems/titan/security'
				listitem
					[636] link Insights, center=(786,158), url='https://github.com/Titan-Systems/titan/pulse'
		heading Titan-Systems/titan
		[716] button main branch, center=(404,222), expanded=False, hasPopup='menu', inner_text= main, type=button
			StaticText main
		[728] link 2 Branches, center=(509,222), type=button, url='https://github.com/Titan-Systems/titan/branches'
			strong
				StaticText 2
		[733] link 92 Tags, center=(583,222), type=button, url='https://github.com/Titan-Systems/titan/tags'
			strong
				StaticText 92
		combobox Go to file, expanded=False, hasPopup='dialog'
		[758] button Code, center=(1194,222), expanded=False, hasPopup='menu', type=button
		heading Folders and files
		table Folders and files
			rowgroup
				row
					columnheader Name
					columnheader Last commit message
					columnheader Last commit date
			rowgroup
				row
					cell Latest commit titan-systems-bot commits by titan-systems-bot Bump version: 0.11.1 → 0.11.2 Commit 1303c08  ·  2 weeks ago History 272 Commits
						heading Latest commit
						link titan-systems-bot, url='https://github.com/titan-systems-bot'
							image titan-systems-bot, url='https://avatars.githubusercontent.com/u/173221243?v=4&size=40'
						link commits by titan-systems-bot, url='https://github.com/Titan-Systems/titan/commits?author=titan-systems-bot'
						link Bump version: 0.11.1 → 0.11.2, url='https://github.com/Titan-Systems/titan/commit/1303c083a7919f90084fc3613946676965f61599'
						link Commit 1303c08, url='https://github.com/Titan-Systems/titan/commit/1303c083a7919f90084fc3613946676965f61599'
						StaticText ·
						StaticText 2 weeks ago
						heading History
						[796] link 272 Commits, center=(1181,281), url='https://github.com/Titan-Systems/titan/commits/main/'
							StaticText 272 Commits
				row
					cell .github/workflows, (Directory)
						[825] link .github/workflows, (Directory), center=(449,328), inner_text=.github/workflows, title=This path skips through empty directories, url='https://github.com/Titan-Systems/titan/tree/main/.github/workflows'
					[828] cell blacksmith.sh: Migrate workflows to Blacksmith (#149), center=(911,328)
						link blacksmith.sh: Migrate workflows to Blacksmith (, url='https://github.com/Titan-Systems/titan/commit/4dd9557ba0525bd0086b3f77bb93813e7a43cca7'
						link #149, url='https://github.com/Titan-Systems/titan/pull/149'
						link ), url='https://github.com/Titan-Systems/titan/commit/4dd9557ba0525bd0086b3f77bb93813e7a43cca7'
					[830] cell 2 months ago, center=(1179,328)
				row
					cell docs, (Directory)
						[846] link docs, (Directory), center=(410,368), inner_text=docs, title=docs, url='https://github.com/Titan-Systems/titan/tree/main/docs'
					[847] cell [CHORE] tests and docs (#150), center=(911,368)
						link [CHORE] tests and docs (, url='https://github.com/Titan-Systems/titan/commit/6b7385c61fc183307560d6899cbdde3eed0c3c87'
						link #150, url='https://github.com/Titan-Systems/titan/pull/150'
						link ), url='https://github.com/Titan-Systems/titan/commit/6b7385c61fc183307560d6899cbdde3eed0c3c87'
					[849] cell 2 months ago, center=(1179,368)
				row
					cell examples, (Directory)
						[865] link examples, (Directory), center=(425,410), inner_text=examples, title=examples, url='https://github.com/Titan-Systems/titan/tree/main/examples'
					[866] cell [CHORE] adjust warehouses to reduce cost (#181), center=(911,410)
						link [CHORE] adjust warehouses to reduce cost (, url='https://github.com/Titan-Systems/titan/commit/d37ca73232eeca83d123d5bd3873958c2ffdac20'
						link #181, url='https://github.com/Titan-Systems/titan/pull/181'
						link ), url='https://github.com/Titan-Systems/titan/commit/d37ca73232eeca83d123d5bd3873958c2ffdac20'
					[868] cell 2 weeks ago, center=(1179,410)
				row
					cell images, (Directory)
						[884] link images, (Directory), center=(418,450), inner_text=images, title=images, url='https://github.com/Titan-Systems/titan/tree/main/images'
					[885] cell bugfix (#19), center=(911,450)
						link bugfix (, url='https://github.com/Titan-Systems/titan/commit/a42c596d1e5820b94db470ee9d756729030012ae'
						link #19, url='https://github.com/Titan-Systems/titan/pull/19'
						link ), url='https://github.com/Titan-Systems/titan/commit/a42c596d1e5820b94db470ee9d756729030012ae'
					[887] cell 11 months ago, center=(1179,450)
				row
					cell prompts, (Directory)
						[903] link prompts, (Directory), center=(420,492), inner_text=prompts, title=prompts, url='https://github.com/Titan-Systems/titan/tree/main/prompts'
					[904] cell release/v0.11.0 (#174) Bump version, center=(911,492)
						link release/v0.11.0 (, url='https://github.com/Titan-Systems/titan/commit/cf5a6c36e758863bf68b0156fb36f995dc8d1c30'
						link #174, url='https://github.com/Titan-Systems/titan/pull/174'
						link ) Bump version, url='https://github.com/Titan-Systems/titan/commit/cf5a6c36e758863bf68b0156fb36f995dc8d1c30'
					[906] cell 2 weeks ago, center=(1179,492)
				row
					cell scripts, (Directory)
						[922] link scripts, (Directory), center=(415,532), inner_text=scripts, title=scripts, url='https://github.com/Titan-Systems/titan/tree/main/scripts'
					[923] cell bugfix (#19), center=(911,532)
						link bugfix (, url='https://github.com/Titan-Systems/titan/commit/a42c596d1e5820b94db470ee9d756729030012ae'
						link #19, url='https://github.com/Titan-Systems/titan/pull/19'
						link ), url='https://github.com/Titan-Systems/titan/commit/a42c596d1e5820b94db470ee9d756729030012ae'
					[925] cell 11 months ago, center=(1179,532)
				row
					cell tests, (Directory)
						[941] link tests, (Directory), center=(410,574), inner_text=tests, title=tests, url='https://github.com/Titan-Systems/titan/tree/main/tests'
					[942] cell [CHORE] adjust warehouses to reduce cost (#181), center=(911,574)
						link [CHORE] adjust warehouses to reduce cost (, url='https://github.com/Titan-Systems/titan/commit/d37ca73232eeca83d123d5bd3873958c2ffdac20'
						link #181, url='https://github.com/Titan-Systems/titan/pull/181'
						link ), url='https://github.com/Titan-Systems/titan/commit/d37ca73232eeca83d123d5bd3873958c2ffdac20'
					[944] cell 2 weeks ago, center=(1179,574)
				row
					cell titan, (Directory)
						[960] link titan, (Directory), center=(408,614), inner_text=titan, title=titan, url='https://github.com/Titan-Systems/titan/tree/main/titan'
					[961] cell [BUGFIX] fix vars for role names (#177), center=(911,614)
						link [BUGFIX] fix vars for role names (, url='https://github.com/Titan-Systems/titan/commit/dc61f7f4db513f29a33ce58694a1b61bb7219525'
						link #177, url='https://github.com/Titan-Systems/titan/pull/177'
						link ), url='https://github.com/Titan-Systems/titan/commit/dc61f7f4db513f29a33ce58694a1b61bb7219525'
					[963] cell 2 weeks ago, center=(1179,614)
				row
					cell tools, (Directory)
						[979] link tools, (Directory), center=(410,656), inner_text=tools, title=tools, url='https://github.com/Titan-Systems/titan/tree/main/tools'
					[980] cell [CHORE] adjust warehouses to reduce cost (#181), center=(911,656)
						link [CHORE] adjust warehouses to reduce cost (, url='https://github.com/Titan-Systems/titan/commit/d37ca73232eeca83d123d5bd3873958c2ffdac20'
						link #181, url='https://github.com/Titan-Systems/titan/pull/181'
						link ), url='https://github.com/Titan-Systems/titan/commit/d37ca73232eeca83d123d5bd3873958c2ffdac20'
					[982] cell 2 weeks ago, center=(1179,656)
				row
					cell .gitignore, (File)
						[998] link .gitignore, (File), center=(424,696), inner_text=.gitignore, title=.gitignore, url='https://github.com/Titan-Systems/titan/blob/main/.gitignore'
					[999] cell Iceberg (#114), center=(911,696)
						link Iceberg (, url='https://github.com/Titan-Systems/titan/commit/54d159a73cf1ae2e0601e7959856a63693291f22'
						link #114, url='https://github.com/Titan-Systems/titan/pull/114'
						link ), url='https://github.com/Titan-Systems/titan/commit/54d159a73cf1ae2e0601e7959856a63693291f22'
					[1001] cell 4 months ago, center=(1179,696)
				row
					cell LICENSE, (File)
						[1017] link LICENSE, (File), center=(425,738), inner_text=LICENSE, title=LICENSE, url='https://github.com/Titan-Systems/titan/blob/main/LICENSE'
					[1018] cell v0.1.0, center=(911,738)
						link v0.1.0, url='https://github.com/Titan-Systems/titan/commit/15adc7fc7437a0dbf2528e13ee8adb4e4cb8e572'
					[1020] cell last year, center=(1179,738)
				row
					cell MANIFEST.in, (File)
						[1036] link MANIFEST.in, (File), center=(437,778), inner_text=MANIFEST.in, title=MANIFEST.in, url='https://github.com/Titan-Systems/titan/blob/main/MANIFEST.in'
					[1037] cell Package config (#57), center=(911,778)
						link Package config (, url='https://github.com/Titan-Systems/titan/commit/b4d85dd69840839d4df038a34daf0cdcf82c9de5'
						link #57, url='https://github.com/Titan-Systems/titan/pull/57'
						link ), url='https://github.com/Titan-Systems/titan/commit/b4d85dd69840839d4df038a34daf0cdcf82c9de5'
					[1039] cell 7 months ago, center=(1179,778)
				row
					cell Makefile, (File)
						[1055] link Makefile, (File), center=(421,820), inner_text=Makefile, title=Makefile, url='https://github.com/Titan-Systems/titan/blob/main/Makefile'
					[1056] cell [FEATURE] skip show grants (#133), center=(911,820)
						link [FEATURE] skip show grants (, url='https://github.com/Titan-Systems/titan/commit/639c6765841fb4091322b564b4ea77abddc517f2'
						link #133, url='https://github.com/Titan-Systems/titan/pull/133'
						link ), url='https://github.com/Titan-Systems/titan/commit/639c6765841fb4091322b564b4ea77abddc517f2'
					[1058] cell 3 months ago, center=(1179,820)
				row
					cell README.md, (File)
						[1074] link README.md, (File), center=(437,860), inner_text=README.md, title=README.md, url='https://github.com/Titan-Systems/titan/blob/main/README.md'
					[1075] cell [CHORE] tests and docs (#150), center=(911,860)
						link [CHORE] tests and docs (, url='https://github.com/Titan-Systems/titan/commit/6b7385c61fc183307560d6899cbdde3eed0c3c87'
						link #150, url='https://github.com/Titan-Systems/titan/pull/150'
						link ), url='https://github.com/Titan-Systems/titan/commit/6b7385c61fc183307560d6899cbdde3eed0c3c87'
					[1077] cell 2 months ago, center=(1179,860)
				row
					cell conftest.py, (File)
						[1093] link conftest.py, (File), center=(429,902), inner_text=conftest.py, title=conftest.py, url='https://github.com/Titan-Systems/titan/blob/main/conftest.py'
					[1094] cell [CHORE] test account automation (#148), center=(911,902)
						link [CHORE] test account automation (, url='https://github.com/Titan-Systems/titan/commit/1c8c585f963cb9a205ff53a0350a0cb18ccf61e1'
						link #148, url='https://github.com/Titan-Systems/titan/pull/148'
						link ), url='https://github.com/Titan-Systems/titan/commit/1c8c585f963cb9a205ff53a0350a0cb18ccf61e1'
					[1096] cell 2 months ago, center=(1179,902)
				row
					cell pyproject.toml, (File)
						[1112] link pyproject.toml, (File), center=(439,942), inner_text=pyproject.toml, title=pyproject.toml, url='https://github.com/Titan-Systems/titan/blob/main/pyproject.toml'
					[1113] cell [FEATURE] Update github action (#140), center=(911,942)
						link [FEATURE] Update github action (, url='https://github.com/Titan-Systems/titan/commit/4df8f7d902a49dc63237e30ec0095e5122fc0590'
						link #140, url='https://github.com/Titan-Systems/titan/pull/140'
						link ), url='https://github.com/Titan-Systems/titan/commit/4df8f7d902a49dc63237e30ec0095e5122fc0590'
					[1115] cell 3 months ago, center=(1179,942)
				row
					cell requirements.dev.txt, (File)
						[1131] link requirements.dev.txt, (File), center=(458,984), inner_text=requirements.dev.txt, title=requirements.dev.txt, url='https://github.com/Titan-Systems/titan/blob/main/requirements.dev.txt'
					[1132] cell Resource coverage helper, center=(911,984)
						link Resource coverage helper, url='https://github.com/Titan-Systems/titan/commit/8e929c1f2362189b92ad502fc533098030c69b2e'
					[1134] cell 2 years ago, center=(1179,984)
				row
					cell requirements.txt, (File)
						[1150] link requirements.txt, (File), center=(445,1024), inner_text=requirements.txt, title=requirements.txt, url='https://github.com/Titan-Systems/titan/blob/main/requirements.txt'
					[1151] cell some cleanup, center=(911,1024)
						link some cleanup, url='https://github.com/Titan-Systems/titan/commit/fc847d75b3d1be959a2c7c6fb84283393d8d5dd7'
					[1153] cell 2 years ago, center=(1179,1024)
				row
					cell setup.py, (File)
						[1169] link setup.py, (File), center=(421,1066), inner_text=setup.py, title=setup.py, url='https://github.com/Titan-Systems/titan/blob/main/setup.py'
					[1170] cell [CHORE] dependency pinning (#168), center=(911,1066)
						link [CHORE] dependency pinning (, url='https://github.com/Titan-Systems/titan/commit/db09038d60f392378e3c9b7a3cf6a1bc830f3575'
						link #168, url='https://github.com/Titan-Systems/titan/pull/168'
						link ), url='https://github.com/Titan-Systems/titan/commit/db09038d60f392378e3c9b7a3cf6a1bc830f3575'
					[1172] cell 2 months ago, center=(1179,1066)
				row
					cell version.md, (File)
						link version.md, (File), url='https://github.com/Titan-Systems/titan/blob/main/version.md'
					cell Bump version: 0.11.1 → 0.11.2
						link Bump version: 0.11.1 → 0.11.2, url='https://github.com/Titan-Systems/titan/commit/1303c083a7919f90084fc3613946676965f61599'
					cell 2 weeks ago
		heading Repository files navigation
		navigation Repository files
			list
				listitem
					link README, url='https://github.com/Titan-Systems/titan#'
				listitem
					link Apache-2.0 license, url='https://github.com/Titan-Systems/titan#'
		button Outline, expanded=False, hasPopup='menu'
		article
			heading titan core - Snowflake infrastructure as code
				code
			link Permalink: titan core - Snowflake infrastructure as code, url='https://github.com/Titan-Systems/titan#titan-core---snowflake-infrastructure-as-code'
			paragraph
				StaticText Titan Core helps you provision, deploy, and secure resources in Snowflake. It replaces tools like Terraform, Schemachange, or Permifrost.
			paragraph
				StaticText Deploy any Snowflake resource, including users, roles, schemas, databases, integrations, pipes, stages, functions, stored procedures, and more. Convert adhoc, bug-prone SQL management scripts into simple, repeatable configuration.
			paragraph
				StaticText Titan Core is for:
			list
				listitem
					ListMarker •
					StaticText DevOps engineers looking to automate and manage Snowflake infrastructure.
				listitem
					ListMarker •
					StaticText Analytics engineers working with dbt who want to manage Snowflake resources without macros.
				listitem
					ListMarker •
					StaticText Data platform teams who need to reliably manage Snowflake with CI/CD.
				listitem
					ListMarker •
					StaticText Organizations that prefer a git-based workflow for infrastructure management.
				listitem
					ListMarker •
					StaticText Teams seeking to replace Terraform for Snowflake-related tasks.
			code
				StaticText ╔══════════╗                                           ╔═══════════╗       
    ║  CONFIG  ║                                           ║ SNOWFLAKE ║       
    ╚══════════╝                                           ╚═══════════╝       
  ┏━━━━━━━━━━━┓                                        ┏━━━━━━━━━━━┓            
┌─┫ WAREHOUSE ┣─────┐                                ┌─┫ WAREHOUSE ┣───────────┐
│ ┗━━━━━━━━━━━┛     │                    ALTER       │ ┗━━━━━━━━━━━┛           │
│ name:         ETL │─────┐           ┌─ WAREHOUSE ─▶│ name:         ETL       │
│ auto_suspend: 60  │     │           │              │ auto_suspend: 300 -> 60 │
└───────────────────┘  ╔══▼═══════════╩═╗            └─────────────────────────┘
                       ║                ║                                      
                       ║   TITAN CORE   ║                                      
  ┏━━━━━━┓             ║                ║              ┏━━━━━━┓                
┌─┫ ROLE ┣──────────┐  ╚══▲═══════════╦═╝            ┌─┫ ROLE ┣────────────────┐
│ ┗━━━━━━┛          │     │           │              │ ┗━━━━━━┛                │
│ name: TRANSFORMER │─────┘           └─ CREATE ────▶│ name: TRANSFORMER       │
└───────────────────┘                    ROLE        └─────────────────────────┘
			button Copy
			heading Key Features
			link Permalink: Key Features, url='https://github.com/Titan-Systems/titan#key-features'
			list
				listitem
					ListMarker •
					paragraph
						strong
							StaticText Declarative
						StaticText » Generates the right SQL to make your config and account match
				listitem
					ListMarker •
					paragraph
						strong
							StaticText Comprehensive
						StaticText » Nearly every Snowflake resource is supported
				listitem
					ListMarker •
					paragraph
						strong
							StaticText Flexible
						StaticText » Write resource configuration in YAML or Python
				listitem
					ListMarker •
					paragraph
						strong
							StaticText Fast
						StaticText » Titan Core runs 50-90% faster than Terraform and Permifrost
				listitem
					ListMarker •
					paragraph
						strong
							StaticText Migration-friendly
						StaticText » Generate config automatically with the export CLI
			heading Open Source
			link Permalink: Open Source, url='https://github.com/Titan-Systems/titan#open-source'
			paragraph
				StaticText This project is licensed under the Apache 2.0 License - see
				link LICENSE, url='https://github.com/Titan-Systems/titan/blob/main/LICENSE'
				StaticText for details. The source code for Titan Core is available on
				link Github, url='https://github.com/Titan-Systems/titan'
				StaticText .
			heading Documentation
			link Permalink: Documentation, url='https://github.com/Titan-Systems/titan#documentation'
			paragraph
				StaticText You can find comprehensive
				link Titan Core documentation on GitBook, url='https://titan-core.gitbook.io/titan-core'
				StaticText .
			heading Getting Started
			link Permalink: Getting Started, url='https://github.com/Titan-Systems/titan#getting-started'
			paragraph
				StaticText If you're new, the best place to start is with the Python package.
			heading Install from PyPi (MacOS, Linux)
			link Permalink: Install from PyPi (MacOS, Linux), url='https://github.com/Titan-Systems/titan#install-from-pypi-macos-linux'
			StaticText python -m venv .venv
			StaticText source
			StaticText .venv/bin/activate
python -m pip install titan-core
			button Copy
			heading Install from PyPi (Windows)
			link Permalink: Install from PyPi (Windows), url='https://github.com/Titan-Systems/titan#install-from-pypi-windows'
			StaticText python -m venv .venv
.\.venv\Scripts\activate
python -m pip install titan-core
			button Copy
			heading Python example
			link Permalink: Python example, url='https://github.com/Titan-Systems/titan#python-example'
			StaticText import
			StaticText os
			StaticText import
			StaticText snowflake
			StaticText .
			StaticText connector
			StaticText from
			StaticText titan
			StaticText .
			StaticText blueprint
			StaticText import
			StaticText Blueprint
			StaticText ,
			StaticText print_plan
			StaticText from
			StaticText titan
			StaticText .
			StaticText resources
			StaticText import
			StaticText Grant
			StaticText ,
			StaticText Role
			StaticText ,
			StaticText Warehouse
			StaticText # Configure resources by instantiating Python objects.
			StaticText role
			StaticText =
			StaticText Role
			StaticText (
			StaticText name
			StaticText =
			StaticText "transformer"
			StaticText )
			StaticText warehouse
			StaticText =
			StaticText Warehouse
			StaticText (
			StaticText name
			StaticText =
			StaticText "transforming"
			StaticText ,
			StaticText warehouse_size
			StaticText =
			StaticText "large"
			StaticText ,
			StaticText auto_suspend
			StaticText =
			StaticText 60
			StaticText ,
)
			StaticText usage_grant
			StaticText =
			StaticText Grant
			StaticText (
			StaticText priv
			StaticText =
			StaticText "usage"
			StaticText ,
			StaticText to
			StaticText =
			StaticText role
			StaticText ,
			StaticText on
			StaticText =
			StaticText warehouse
			StaticText )
			StaticText # Titan compares your config to a Snowflake account. Create a Snowflake
			StaticText # connection to allow Titan to connect to your account.
			StaticText connection_params
			StaticText =
			StaticText {
			StaticText "account"
			StaticText :
			StaticText os
			StaticText .
			StaticText environ
			StaticText [
			StaticText "SNOWFLAKE_ACCOUNT"
			StaticText ],
			StaticText "user"
			StaticText :
			StaticText os
			StaticText .
			StaticText environ
			StaticText [
			StaticText "SNOWFLAKE_USER"
			StaticText ],
			StaticText "password"
			StaticText :
			StaticText os
			StaticText .
			StaticText environ
			StaticText [
			StaticText "SNOWFLAKE_PASSWORD"
			StaticText ],
			StaticText "role"
			StaticText :
			StaticText "SYSADMIN"
			StaticText ,
}
			StaticText session
			StaticText =
			StaticText snowflake
			StaticText .
			StaticText connector
			StaticText .
			StaticText connect
			StaticText (
			StaticText **
			StaticText connection_params
			StaticText )
			StaticText # Create a Blueprint and pass your resources into it. A Blueprint helps you
			StaticText # validate and deploy a set of resources.
			StaticText bp
			StaticText =
			StaticText Blueprint
			StaticText (
			StaticText resources
			StaticText =
			StaticText [
			StaticText role
			StaticText ,
			StaticText warehouse
			StaticText ,
			StaticText usage_grant
			StaticText ,
])
			StaticText # Blueprint works like Terraform. Calling plan(...) will compare your config
			StaticText # to the state of your Snowflake account and return a list of changes.
			StaticText plan
			StaticText =
			StaticText bp
			StaticText .
			StaticText plan
			StaticText (
			StaticText session
			StaticText )
			StaticText print_plan
			StaticText (
			StaticText plan
			StaticText )
			StaticText # =>
			StaticText """
			StaticText » titan core
			StaticText » Plan: 4 to add, 0 to change, 0 to destroy.
			StaticText + urn::ABCD123:warehouse/transforming {
			StaticText + name                                = "transforming"
			StaticText + owner                               = "SYSADMIN"
			StaticText + warehouse_type                      = "STANDARD"
			StaticText + warehouse_size                      = "LARGE"
			StaticText ...
			StaticText }
			StaticText + urn::ABCD123:role/transformer {
			StaticText + name    = "transformer"
			StaticText + owner   = "USERADMIN"
			StaticText + tags    = None
			StaticText + comment = None
			StaticText }
			StaticText + urn::ABCD123:grant/TRANSFORMER?priv=USAGE&on=warehouse/TRANSFORMING {
			StaticText + priv         = "USAGE"
			StaticText + on           = "transforming"
			StaticText + on_type      = "WAREHOUSE"
			StaticText + to           = TRANSFORMER
			StaticText ...
			StaticText }
			StaticText """
			StaticText # Calling apply(...) will convert your plan into the right set of SQL commands
			StaticText # and run them against your Snowflake account.
			StaticText bp
			StaticText .
			StaticText apply
			StaticText (
			StaticText session
			StaticText ,
			StaticText plan
			StaticText )
			StaticText # =>
			StaticText """
			StaticText [TITAN_USER:SYSADMIN]  > USE SECONDARY ROLES ALL
			StaticText [TITAN_USER:SYSADMIN]  > CREATE WAREHOUSE TRANSFORMING warehouse_type = STANDARD ...
			StaticText [TITAN_USER:SYSADMIN]  > USE ROLE USERADMIN
			StaticText [TITAN_USER:USERADMIN] > CREATE ROLE TRANSFORMER
			StaticText [TITAN_USER:USERADMIN] > USE ROLE SYSADMIN
			StaticText [TITAN_USER:SYSADMIN]  > GRANT USAGE ON WAREHOUSE transforming TO TRANSFORMER
			StaticText """
			button Copy
			heading Using the CLI
			link Permalink: Using the CLI, url='https://github.com/Titan-Systems/titan#using-the-cli'
			paragraph
				StaticText You can use the CLI to generate a plan, apply a plan, or export resources. To use the CLI, install the Python package and call
				code
					StaticText python -m titan
				StaticText from the command line.
			paragraph
				StaticText The CLI allows you to
				code
					StaticText plan
				StaticText and
				code
					StaticText apply
				StaticText a Titan Core YAML config. You can specify a single input file or a directory of configs.
			paragraph
				StaticText In addition to
				code
					StaticText plan
				StaticText and
				code
					StaticText apply
				StaticText , the CLI also allows you to
				code
					StaticText export
				StaticText resources. This makes it easy to generate a config for an existing Snowflake environment.
			paragraph
				StaticText To connect with Snowflake, the CLI uses environment variables. The following `are supported:
			list
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_ACCOUNT
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_USER
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_PASSWORD
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_DATABASE
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_SCHEMA
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_ROLE
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_WAREHOUSE
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_MFA_PASSCODE
				listitem
					ListMarker •
					code
						StaticText SNOWFLAKE_AUTHENTICATOR
			heading CLI Example
			link Permalink: CLI Example, url='https://github.com/Titan-Systems/titan#cli-example'
			paragraph
				StaticText Show the help message
			StaticText titan --help
			StaticText #
			StaticText Usage: titan [OPTIONS] COMMAND [ARGS]...
			StaticText #
			StaticText #
			StaticText titan core helps you manage your Snowflake environment.
			StaticText #
			StaticText #
			StaticText Options:
			StaticText #
			StaticText --help  Show this message and exit.
			StaticText #
			StaticText #
			StaticText Commands:
			StaticText #
			StaticText apply    Apply a resource config to a Snowflake account
			StaticText #
			StaticText connect  Test the connection to Snowflake
			StaticText #
			StaticText export   Generate a resource config for existing Snowflake resources
			StaticText #
			StaticText plan     Compare a resource config to the current state of Snowflake
			button Copy
			paragraph
				StaticText Apply a resource config to Snowflake
			StaticText #
			StaticText Create a resource config file
			StaticText cat
			StaticText <<
			StaticText EOF
			StaticText > titan.yml
			StaticText roles:
			StaticText - name: transformer
			StaticText warehouses:
			StaticText - name: transforming
			StaticText warehouse_size: LARGE
			StaticText auto_suspend: 60
			StaticText grants:
			StaticText - to_role: transformer
			StaticText priv: usage
			StaticText on_warehouse: transforming
			StaticText EOF
			StaticText #
			StaticText Set connection variables
			StaticText export
			StaticText SNOWFLAKE_ACCOUNT=
			StaticText "
			StaticText my-account
			StaticText "
			StaticText export
			StaticText SNOWFLAKE_USER=
			StaticText "
			StaticText my-user
			StaticText "
			StaticText export
			StaticText SNOWFLAKE_PASSWORD=
			StaticText "
			StaticText my-password
			StaticText "
			StaticText #
			StaticText Generate a plan
			StaticText titan plan --config titan.yml
			StaticText #
			StaticText Apply the config
			StaticText titan apply --config titan.yml
			button Copy
			paragraph
				StaticText Export existing Snowflake resources to YAML.
			StaticText titan
			StaticText export
			StaticText \
  --resource=warehouse,grant,role \
  --out=titan.yml
			button Copy
			paragraph
				StaticText The Titan Core Python package installs the CLI script
				code
					StaticText titan
				StaticText . You can alternatively use Python CLI module syntax if you need fine-grained control over the Python environment.
			StaticText python -m titan plan --config titan.yml
			button Copy
			heading Using the GitHub Action
			link Permalink: Using the GitHub Action, url='https://github.com/Titan-Systems/titan#using-the-github-action'
			paragraph
				StaticText The Titan Core GitHub Action allows you to automate the deployment of Snowflake resources using a git-based workflow.
			heading GitHub Action Example
			link Permalink: GitHub Action Example, url='https://github.com/Titan-Systems/titan#github-action-example'
			StaticText -- .github/workflows/titan.yml
			StaticText name
			StaticText :
			StaticText Deploy to Snowflake with Titan
			StaticText on
			StaticText :
			StaticText push
			StaticText :
			StaticText branches
			StaticText :
			StaticText [ main ]
			StaticText paths
			StaticText :
    -
			StaticText titan/**
			StaticText jobs
			StaticText :
			StaticText deploy
			StaticText :
			StaticText runs-on
			StaticText :
			StaticText ubuntu-latest
			StaticText steps
			StaticText :
      -
			StaticText name
			StaticText :
			StaticText Checkout code
			StaticText uses
			StaticText :
			StaticText actions/checkout@v4
			StaticText -
			StaticText name
			StaticText :
			StaticText Deploy to Snowflake
			StaticText uses
			StaticText :
			StaticText Titan-Systems/titan-core-action@main
			StaticText with
			StaticText :
			StaticText run-mode
			StaticText :
			StaticText create-or-update
			StaticText resource-path
			StaticText :
			StaticText ./titan
			StaticText allowlist
			StaticText :
			StaticText warehouse,role,grant
			StaticText dry-run
			StaticText :
			StaticText false
			StaticText env
			StaticText :
			StaticText SNOWFLAKE_ACCOUNT
			StaticText :
			StaticText ${{ secrets.SNOWFLAKE_ACCOUNT }}
			StaticText SNOWFLAKE_USER
			StaticText :
			StaticText ${{ secrets.SNOWFLAKE_USER }}
			StaticText SNOWFLAKE_PASSWORD
			StaticText :
			StaticText ${{ secrets.SNOWFLAKE_PASSWORD }}
			StaticText SNOWFLAKE_ROLE
			StaticText :
			StaticText ${{ secrets.SNOWFLAKE_ROLE }}
			StaticText SNOWFLAKE_WAREHOUSE
			StaticText :
			StaticText ${{ secrets.SNOWFLAKE_WAREHOUSE }}
			button Copy
			heading Titan Core Limitations
			link Permalink: Titan Core Limitations, url='https://github.com/Titan-Systems/titan#titan-core-limitations'
			list
				listitem
					ListMarker •
					strong
						StaticText Titan Core uses names as unique identifiers
					StaticText . Renaming a resource will create a new one.
				listitem
					ListMarker •
					StaticText Titan Core is not an ORM. It's not built to replace tools like SQLAlchemy.
				listitem
					ListMarker •
					StaticText Titan Core is under active development. Some resources are not yet supported.
			heading titan core vs other tools
				code
			link Permalink: titan core vs other tools, url='https://github.com/Titan-Systems/titan#titan-core-vs-other-tools'
			table
				rowgroup
					row
						columnheader Feature
						columnheader Titan Core
						columnheader Terraform
						columnheader Schemachange
						columnheader Permifrost
						columnheader SnowDDL
				rowgroup
					row
						cell Plan and Execute Changes
						cell ✅
						cell ✅
						cell ❌
						cell ✅
						cell ✅
					row
						cell Declarative Config
						cell ✅
						cell ✅
						cell ❌
						cell ✅
						cell ✅
					row
						cell No State File Dependency
						cell ✅
						cell ❌
						cell ✅
						cell ✅
						cell ✅
					row
						cell Python-Based Definitions
						cell ✅
						cell w/ CDKTF
						cell ❌
						cell ❌
						cell ✅
					row
						cell SQL Support
						cell ✅
						cell ❌
						cell ✅
						cell ❌
						cell ❌
					row
						cell Dynamic Role Switching
						cell ✅
						cell ❌
						cell N/A
						cell ❌
						cell ❌
					row
						cell Export Snowflake resources
						cell ✅
						cell ❌
						cell ❌
						cell ❌
						cell ❌
			heading titan core vs Terraform
				code
			link Permalink: titan core vs Terraform, url='https://github.com/Titan-Systems/titan#titan-core-vs-terraform'
			paragraph
				StaticText Terraform is an infrastructure-as-code tool using the HCL config language.
			paragraph
				StaticText The
				link Snowflake provider for Terraform, url='https://github.com/Snowflake-Labs/terraform-provider-snowflake'
				StaticText is limited to
				strong
					StaticText 1 role per provider
				StaticText . This limitation is at odds with Snowflake's design, which is built to use multiple roles. This mismatch forces you into a complex multi-provider setup which can result in drift, permission errors, and broken plans.
			paragraph
				StaticText Titan Core streamlines this with
				strong
					StaticText dynamic role switching
				StaticText . Titan Core automatically detects which role is needed for a given change, and switches to that role before making it. This speeds up development cycles and helps eliminate the use of
				code
					StaticText ACCOUNTADMIN
				StaticText .
			paragraph
				StaticText Titan Core doesn't use a state file. This provides more accurate plans and eliminates issues with stale state.
			heading titan core vs Schemachange
				code
			link Permalink: titan core vs Schemachange, url='https://github.com/Titan-Systems/titan#titan-core-vs-schemachange'
			paragraph
				link Schemachange, url='https://github.com/Snowflake-Labs/schemachange'
				StaticText is a database migration tool based on Flyway. It uses SQL scripts to deploy resources to different environments.
			paragraph
				StaticText Schemachange is an imperative migration tool. For developers, that means you must know Snowflake's current state and the exact SQL commands needed to update it to the desired state. If environments get changed outside of the tool, your migration scripts may need significant adjustments.
			paragraph
				StaticText Titan Core simplifies this with a declarative approach. With Titan Core, just define what an environment should look like, you don't need to know the detailed steps or SQL commands needed to get there.
			paragraph
				StaticText Declarative config is less error-prone and more scalable, especially in dynamic and complex data environments.
			heading titan core vs Permifrost
				code
			link Permalink: titan core vs Permifrost, url='https://github.com/Titan-Systems/titan#titan-core-vs-permifrost'
			paragraph
				link Permifrost, url='https://gitlab.com/gitlab-data/permifrost/'
				StaticText is an access-management tool for Snowflake. It helps you automate the creation of users, roles, and grants. Permifrost only manages permissions, it doesn't manage any other aspect of your Snowflake account.
			paragraph
				StaticText Permifrost can be very slow. Running simple Permifrost configs can take minutes to run. Titan Core is designed to run in seconds, even with complex environments.
			heading titan core vs SnowDDL
				code
			link Permalink: titan core vs SnowDDL, url='https://github.com/Titan-Systems/titan#titan-core-vs-snowddl'
			paragraph
				link SnowDDL, url='https://github.com/littleK0i/SnowDDL'
				StaticText is a declarative object management tool for Snowflake, similar to Titan Core. It uses a streamlined
				link permissions model, url='https://docs.snowddl.com/guides/permission-model'
				StaticText that simplifies granting read and write access to databases and schemas.
			paragraph
				StaticText SnowDDL takes a strongly opinionated stance on roles in Snowflake. If you don't need a
				link 3-tier role heirarchy, url='https://docs.snowddl.com/guides/role-hierarchy'
				StaticText , SnowDDL may not be a good fit.
			heading Resource support
			link Permalink: Resource support, url='https://github.com/Titan-Systems/titan#resource-support'
			heading Legend
			link Permalink: Legend, url='https://github.com/Titan-Systems/titan#legend'
			list
				listitem
					ListMarker •
					StaticText ✅ Supported
				listitem
					ListMarker •
					StaticText 🚧 Unstable
				listitem
					ListMarker •
					StaticText ❌ Not Yet Supported
			table
				rowgroup
					row
						columnheader Name
						columnheader Supported
				rowgroup
					row
						cell Account Resources
							strong
						cell
					row
						cell Account Parameter
						cell ✅
					row
						cell API Integration
						cell ✅
					row
						cell Catalog Integration
						cell
					row
						cell ↳ Glue
						cell ✅
					row
						cell ↳ Object Store
						cell ✅
					row
						cell Compute Pool
						cell ✅
					row
						cell Connection
						cell ❌
					row
						cell Database
						cell ✅
					row
						cell External Access Integration
						cell ✅
					row
						cell External Volume
						cell ✅
					row
						cell Failover Group
						cell 🚧
					row
						cell Grant
						cell
					row
						cell ↳ Future Grant
						cell ✅
					row
						cell ↳ Privilege Grant
						cell ✅
					row
						cell ↳ Role Grant
						cell ✅
					row
						cell Network Policy
						cell ✅
					row
						cell Notification Integration
						cell
					row
						cell ↳ Email
						cell 🚧
					row
						cell ↳ AWS
						cell 🚧
					row
						cell ↳ Azure
						cell 🚧
					row
						cell ↳ GCP
						cell 🚧
					row
						cell Replication Group
						cell 🚧
					row
						cell Resource Monitor
						cell ✅
					row
						cell Role
						cell ✅
					row
						cell Role Grant
						cell ✅
					row
						cell Scanner Package
						cell ✅
					row
						cell Security Integration
						cell
					row
						cell ↳ External API
						cell ❌
					row
						cell ↳ External OAuth
						cell ❌
					row
						cell ↳ Snowflake OAuth
						cell 🚧
					row
						cell ↳ SAML2
						cell ❌
					row
						cell ↳ SCIM
						cell ❌
					row
						cell Share
						cell ✅
					row
						cell Storage Integration
						cell
					row
						cell ↳ AWS
						cell ✅
					row
						cell ↳ Azure
						cell ✅
					row
						cell ↳ GCS
						cell ✅
					row
						cell Tag Reference
						cell ✅
					row
						cell User
						cell ✅
					row
						cell Warehouse
						cell ✅
					row
						cell
						cell
					row
						cell Database Resources
							strong
						cell
					row
						cell Database Role
						cell ✅
					row
						cell Schema
						cell ✅
					row
						cell
						cell
					row
						cell Schema Resources
							strong
						cell
					row
						cell Aggregation Policy
						cell ✅
					row
						cell Alert
						cell ✅
					row
						cell Authentication Policy
						cell ✅
					row
						cell Dynamic Table
						cell ✅
					row
						cell Event Table
						cell ✅
					row
						cell External Function
						cell 🚧
					row
						cell External Table
						cell ❌
					row
						cell File Format
						cell
					row
						cell ↳ CSV
						cell ✅
					row
						cell ↳ JSON
						cell ✅
					row
						cell ↳ AVRO
						cell ❌
					row
						cell ↳ ORC
						cell ❌
					row
						cell ↳ Parquet
						cell ✅
					row
						cell Hybrid Table
						cell 🚧
					row
						cell Iceberg Table
						cell
					row
						cell ↳ Snowflake Catalog
						cell ✅
					row
						cell ↳ AWS Glue
						cell ❌
					row
						cell ↳ Iceberg files
						cell ❌
					row
						cell ↳ Delta files
						cell ❌
					row
						cell ↳ REST Catalog
						cell ❌
					row
						cell ↳ Open Catalog
						cell ❌
					row
						cell Image Repository
						cell ✅
					row
						cell Masking Policy
						cell ❌
					row
						cell Materialized View
						cell 🚧
					row
						cell Model
						cell ❌
					row
						cell Network Rule
						cell ✅
					row
						cell Notebook
						cell ✅
					row
						cell Packages Policy
						cell ✅
					row
						cell Password Policy
						cell ✅
					row
						cell Pipe
						cell ✅
					row
						cell Projection Policy
						cell ❌
					row
						cell Row Access Policy
						cell ❌
					row
						cell Secret
						cell
					row
						cell ↳ Generic
						cell ✅
					row
						cell ↳ OAuth
						cell ✅
					row
						cell ↳ Password
						cell ✅
					row
						cell Sequence
						cell ✅
					row
						cell Service
						cell ✅
					row
						cell Session Policy
						cell 🚧
					row
						cell Stage
						cell ✅
					row
						cell ↳ External
						cell ✅
					row
						cell ↳ Internal
						cell ✅
					row
						cell Stored Procedure
						cell
					row
						cell ↳ Java
						cell ❌
					row
						cell ↳ Javascript
						cell ❌
					row
						cell ↳ Python
						cell 🚧
					row
						cell ↳ Scala
						cell ❌
					row
						cell ↳ SQL
						cell ❌
					row
						cell Stream
						cell
					row
						cell ↳ External Table
						cell ❌
					row
						cell ↳ Stage
						cell ✅
					row
						cell ↳ Table
						cell ✅
					row
						cell ↳ View
						cell ✅
					row
						cell Streamlit
						cell ❌
					row
						cell Table
						cell 🚧
					row
						cell Tag
						cell ✅
					row
						cell Task
						cell ✅
					row
						cell User-Defined Function
						cell
					row
						cell ↳ Java
						cell ❌
					row
						cell ↳ Javascript
						cell 🚧
					row
						cell ↳ Python
						cell ✅
					row
						cell ↳ Scala
						cell ❌
					row
						cell ↳ SQL
						cell ❌
					row
						cell View
						cell ✅
			heading What if I need a type of resource isn't supported?
			link Permalink: What if I need a type of resource isn't supported?, url='https://github.com/Titan-Systems/titan#what-if-i-need-a-type-of-resource-isnt-supported'
			paragraph
				StaticText Please
				link create a GitHub issue, url='https://github.com/Titan-Systems/titan/issues'
				StaticText if there's a resource you need that isn't currently supported.
			heading Contributing
			link Permalink: Contributing, url='https://github.com/Titan-Systems/titan#contributing'
			paragraph
				StaticText Contributions are welcome! Titan Core does not require a contributor license agreement.
			heading The End
			link Permalink: The End, url='https://github.com/Titan-Systems/titan#the-end'
			paragraph
				StaticText If you got this far, don't forget to star this repo.
		LayoutTable
			LayoutTableRow
				LayoutTableCell About Titan Core - Snowflake infrastructure-as-code. Provision environments, automate deploys, CI/CD. Manage RBAC, users, roles, and data access. Declarative Python Resource API. Change Management tool for the Snowflake data warehouse. Topics devops snowflake data-warehouse secops data-engineering dataops rbac data-governance compliance-as-code Resources Readme License Apache-2.0 license Activity Custom properties Stars 444 stars Watchers 18 watching Forks 32 forks Report repository
					heading About
					paragraph
					heading Topics
					[2125] link devops, center=(1302,446), title=Topic: devops, url='https://github.com/topics/devops'
					[2126] link snowflake, center=(1375,446), title=Topic: snowflake, url='https://github.com/topics/snowflake'
					[2127] link data-warehouse, center=(1472,446), title=Topic: data-warehouse, url='https://github.com/topics/data-warehouse'
					[2128] link secops, center=(1302,474), title=Topic: secops, url='https://github.com/topics/secops'
					[2129] link data-engineering, center=(1393,474), title=Topic: data-engineering, url='https://github.com/topics/data-engineering'
					[2130] link dataops, center=(1486,474), title=Topic: dataops, url='https://github.com/topics/dataops'
					[2131] link rbac, center=(1295,502), title=Topic: rbac, url='https://github.com/topics/rbac'
					[2132] link data-governance, center=(1378,502), title=Topic: data-governance, url='https://github.com/topics/data-governance'
					[2133] link compliance-as-code, center=(1337,530), title=Topic: compliance-as-code, url='https://github.com/topics/compliance-as-code'
					heading Resources
					[2136] link Readme, center=(1312,572), inner_text= Readme, url='https://github.com/Titan-Systems/titan#readme-ov-file'
					heading License
					[2140] link Apache-2.0 license, center=(1345,601), inner_text= Apache-2.0 license, url='https://github.com/Titan-Systems/titan#Apache-2.0-1-ov-file'
					[2144] link Activity, center=(1308,630), inner_text= Activity, url='https://github.com/Titan-Systems/titan/activity'
					[2148] link Custom properties, center=(1343,659), inner_text= Custom properties, url='https://github.com/Titan-Systems/titan/custom-properties'
					heading Stars
					[2153] link 444 stars, center=(1315,688), inner_text= 444 stars, url='https://github.com/Titan-Systems/titan/stargazers'
						strong
					heading Watchers
					[2158] link 18 watching, center=(1323,717), inner_text= 18 watching, url='https://github.com/Titan-Systems/titan/watchers'
						strong
					heading Forks
					[2163] link 32 forks, center=(1311,746), inner_text= 32 forks, url='https://github.com/Titan-Systems/titan/forks'
						strong
					[2167] link Report repository, center=(1326,775), url='https://github.com/contact/report-content?content_url=https%3A%2F%2Fgithub.com%2FTitan-Systems%2Ftitan&report=Titan-Systems+%28user%29'
			LayoutTableRow
				LayoutTableCell Releases 47 v0.11.1 Latest 2 weeks ago + 46 releases
					heading Releases 47
						[2171] link Releases 47, center=(1323,830), url='https://github.com/Titan-Systems/titan/releases'
					[2173] link v0.11.1 Latest 2 weeks ago, center=(1420,878), inner_text=v0.11.1
Latest, url='https://github.com/Titan-Systems/titan/releases/tag/v0.11.1'
						StaticText v0.11.1
						StaticText Latest
						StaticText 2 weeks ago
					[2181] link + 46 releases, center=(1314,924), url='https://github.com/Titan-Systems/titan/releases'
			LayoutTableRow
				LayoutTableCell Contributors 13 @teej @titan-systems-bot @titan-teej @dwreeves @mlavaert @jcrobak @blbuford @jamesweakley @MartinCairnsSQL @rcohngru @rcohngru-ab-carval @jeff-skoldberg-gmds @blacksmith-sh[bot]
					heading Contributors 13
						[2188] link Contributors 13, center=(1420,980), inner_text=Contributors
13, url='https://github.com/Titan-Systems/titan/graphs/contributors'
					list
						listitem
							link @teej, url='https://github.com/teej'
								image @teej, url='https://avatars.githubusercontent.com/u/1796?s=64&v=4'
						listitem
							link @titan-systems-bot, url='https://github.com/titan-systems-bot'
								image @titan-systems-bot, url='https://avatars.githubusercontent.com/u/173221243?s=64&v=4'
						listitem
							link @titan-teej, url='https://github.com/titan-teej'
								image @titan-teej, url='https://avatars.githubusercontent.com/u/157928223?s=64&v=4'
						listitem
							link @dwreeves, url='https://github.com/dwreeves'
								image @dwreeves, url='https://avatars.githubusercontent.com/u/31971762?s=64&v=4'
						listitem
							link @mlavaert, url='https://github.com/mlavaert'
								image @mlavaert, url='https://avatars.githubusercontent.com/u/1068047?s=64&v=4'
						listitem
							link @jcrobak, url='https://github.com/jcrobak'
								image @jcrobak, url='https://avatars.githubusercontent.com/u/374566?s=64&v=4'
						listitem
							link @blbuford, url='https://github.com/blbuford'
								image @blbuford, url='https://avatars.githubusercontent.com/u/1200142?s=64&v=4'
						listitem
							link @jamesweakley, url='https://github.com/jamesweakley'
								image @jamesweakley, url='https://avatars.githubusercontent.com/u/2681392?s=64&v=4'
						listitem
							link @MartinCairnsSQL, url='https://github.com/MartinCairnsSQL'
								image @MartinCairnsSQL, url='https://avatars.githubusercontent.com/u/4314538?s=64&v=4'
						listitem
							link @rcohngru, url='https://github.com/rcohngru'
								image @rcohngru, url='https://avatars.githubusercontent.com/u/26910097?s=64&v=4'
						listitem
							link @rcohngru-ab-carval, url='https://github.com/rcohngru-ab-carval'
								image @rcohngru-ab-carval, url='https://avatars.githubusercontent.com/u/120593669?s=64&v=4'
						listitem
							link @jeff-skoldberg-gmds, url='https://github.com/jeff-skoldberg-gmds'
								image @jeff-skoldberg-gmds, url='https://avatars.githubusercontent.com/u/138161184?s=64&v=4'
						listitem
							link @blacksmith-sh[bot], url='https://github.com/apps/blacksmith-sh'
								image @blacksmith-sh[bot], url='https://avatars.githubusercontent.com/in/807020?s=64&v=4'
			LayoutTableRow
				LayoutTableCell Languages Python 99.9 Makefile 0.1 Python 99.9%Makefile 0.1%
					heading Languages
					list
						listitem
							link Python 99.9%, url='https://github.com/Titan-Systems/titan/search?l=python'
						listitem
							link Makefile 0.1%, url='https://github.com/Titan-Systems/titan/search?l=makefile'
	contentinfo
		heading Footer
		link Homepage, url='https://github.com/'
		StaticText © 2025 GitHub, Inc.
		navigation Footer
			heading Footer navigation
			list Footer navigation
				listitem
					link Terms, url='https://docs.github.com/site-policy/github-terms/github-terms-of-service'
				listitem
					link Privacy, url='https://docs.github.com/site-policy/privacy-policies/github-privacy-statement'
				listitem
					link Security, url='https://github.com/security'
				listitem
					link Status, url='https://www.githubstatus.com/'
				listitem
					link Docs, url='https://docs.github.com/'
				listitem
					link Contact, url='https://support.github.com/?tags=dotcom-footer'
				listitem
					button Manage cookies
				listitem
					button Do not share my personal information
	generic, atomic
	generic, atomic
```
</details>



```
RootWebArea Issues · Titan-Systems/titan · GitHub, focused, url='https://github.com/Titan-Systems/titan/issues'
	link Skip to content, url='https://github.com/Titan-Systems/titan/issues#start-of-content'
	banner
		heading Navigation Menu
		[193] link Homepage, center=(48,36), url='https://github.com/'
```
<details><summary>Show more</summary>

```
		navigation Global
			list
				listitem
					[202] button Product, center=(126,36), expanded=False, type=button
				listitem
					[264] button Solutions, center=(222,36), expanded=False, type=button
				listitem
					[306] button Resources, center=(329,36), expanded=False, type=button
				listitem
					[341] button Open Source, center=(451,36), expanded=False, type=button
				listitem
					[367] button Enterprise, center=(570,36), expanded=False, type=button
				listitem
					[397] link Pricing, center=(657,36), url='https://github.com/pricing'
		[400] button Search or jump to…, center=(1564,36), hasPopup='dialog', inner_text=Search or jump to..., type=button
			StaticText Search or jump to...
		[521] link Sign in, center=(1769,36), url='https://github.com/login?return_to=https%3A%2F%2Fgithub.com%2FTitan-Systems%2Ftitan'
		[522] link Sign up, center=(1851,36), url='https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F%3Cuser-name%3E%2F%3Crepo-name%3E&source=header-repo&source_repo=Titan-Systems%2Ftitan'
	main
		[547] link Titan-Systems, center=(120,103), url='https://github.com/Titan-Systems'
		StaticText /
		strong
			[550] link titan, center=(218,103), url='https://github.com/Titan-Systems/titan'
		StaticText Public
		list
			listitem
				[556] link You must be signed in to change notification settings, center=(1593,102), inner_text=Notifications, url='https://github.com/login?return_to=%2FTitan-Systems%2Ftitan'
					StaticText Notifications
			listitem
				[560] link Fork 32, center=(1712,102), url='https://github.com/login?return_to=%2FTitan-Systems%2Ftitan'
			listitem
				[565] link You must be signed in to star a repository, center=(1831,102), inner_text= Star 444, url='https://github.com/login?return_to=%2FTitan-Systems%2Ftitan'
					StaticText Star
		navigation Repository
			list
				listitem
					[606] link Code, center=(70,158), url='https://github.com/Titan-Systems/titan'
				listitem
					[611] link Issues 15, center=(174,158), focused, inner_text=Issues
15, url='https://github.com/Titan-Systems/titan/issues'
				listitem
					[616] link Pull requests 1, center=(320,158), inner_text=Pull requests
1, url='https://github.com/Titan-Systems/titan/pulls'
				listitem
					[621] link Discussions, center=(468,158), url='https://github.com/Titan-Systems/titan/discussions'
				listitem
					[626] link Actions, center=(583,158), url='https://github.com/Titan-Systems/titan/actions'
				listitem
					[631] link Security, center=(684,158), url='https://github.com/Titan-Systems/titan/security'
				listitem
					[636] link Insights, center=(786,158), url='https://github.com/Titan-Systems/titan/pulse'
		heading Issues: Titan-Systems/titan
		search
			search Issues
				[2304] textbox Search all issues value='is:issue is:open', center=(759,222), contenteditable=True, type=text
			navigation Issue
				[2308] link Labels 10, center=(1246,222), inner_text= Labels 10, url='https://github.com/Titan-Systems/titan/labels'
				[2311] link Milestones 0, center=(1381,222), inner_text= Milestones 0, url='https://github.com/Titan-Systems/titan/milestones'
		group
			[2324] button New issue, center=(1519,222), expanded=False
		generic
			[2351] link 15 Open, center=(409,282), inner_text= 15 Open, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aopen+is%3Aissue'
			[2353] link 53 Closed, center=(506,282), inner_text= 53 Closed, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aclosed'
		group
			button Author, expanded=False, hasPopup='menu'
		group
			button Label, expanded=False, hasPopup='menu'
		[2358] span, center=(1089,282)
		group
			button Projects, expanded=False, hasPopup='menu'
		[2382] span, center=(1167,282)
		group
			button Milestones, expanded=False, hasPopup='menu'
		[2408] span, center=(1261,282)
		group
			button Assignee, expanded=False, hasPopup='menu'
		[2422] span, center=(1376,282)
		group
			button Sort, expanded=False, hasPopup='menu'
		[2438] span, center=(1477,282)
		heading Issues list
		[2466] span, center=(1547,282)
		group Issues
			[2523] link [FEATURE] Support for Classification Profiles, center=(567,330), url='https://github.com/Titan-Systems/titan/issues/186'
			StaticText #186 opened
			StaticText 7 hours ago
			StaticText by
			[2526] link anitalySuper, center=(582,355), title=Open issues created by anitalySuper, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3AanitalySuper'
			[2541] link [Feature] Support for SQL UDFs and Procedures, center=(577,392), url='https://github.com/Titan-Systems/titan/issues/185'
			StaticText #185 opened
			StaticText 14 hours ago
			StaticText by
			[2544] link rcohngru-ab-carval, center=(606,418), title=Open issues created by rcohngru-ab-carval, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Arcohngru-ab-carval'
			[2559] link OAuth or Key-pair authentication, center=(519,456), url='https://github.com/Titan-Systems/titan/issues/183'
			StaticText #183 opened
			StaticText 3 days ago
			StaticText by
			[2562] link rus-kgo, center=(564,481), title=Open issues created by rus-kgo, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Arus-kgo'
			[2577] link [BUG] Future grants to database roles are re-applied all the time, center=(637,518), url='https://github.com/Titan-Systems/titan/issues/182'
			[2579] link bug, center=(902,519), url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Abug'
			StaticText #182 opened
			StaticText 2 weeks ago
			StaticText by
			[2583] link mlavaert, center=(576,544), title=Open issues created by mlavaert, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Amlavaert'
			[2598] link Ability to set a masking policy on a tag, center=(541,582), url='https://github.com/Titan-Systems/titan/issues/180'
			[2600] link enhancement, center=(736,582), url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement'
			StaticText #180 opened
			StaticText 2 weeks ago
			StaticText by
			[2604] link d-ohare, center=(574,607), title=Open issues created by d-ohare, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Ad-ohare'
			[2619] link [FEATURE] Ability to nest tables/views/etc under their parent schema or database config, center=(730,644), url='https://github.com/Titan-Systems/titan/issues/179'
			[2621] link enhancement, center=(1114,645), url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement'
			StaticText #179 opened
			StaticText 2 weeks ago
			StaticText by
			[2625] link GClunies, center=(578,670), title=Open issues created by GClunies, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3AGClunies'
			[2640] link Unable to use vars in database parameter for database_roles, center=(625,708), url='https://github.com/Titan-Systems/titan/issues/178'
			[2642] link bug, center=(878,708), url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Abug'
			StaticText #178 opened
			StaticText 2 weeks ago
			StaticText by
			[2646] link toadies, center=(572,733), title=Open issues created by toadies, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Atoadies'
			[2661] link Titan plan requires Database Role to be created before grant is analyzed, center=(668,770), url='https://github.com/Titan-Systems/titan/issues/176'
			[2663] link bug, center=(964,771), url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Abug'
			StaticText #176 opened
			StaticText 2 weeks ago
			StaticText by
			[2667] link toadies, center=(572,796), title=Open issues created by toadies, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Atoadies'
			[2675] link 3 comments, center=(1538,769), inner_text= 3, url='https://github.com/Titan-Systems/titan/issues/176'
			[2685] link Unable to use vars in Schema Owner, center=(533,834), url='https://github.com/Titan-Systems/titan/issues/175'
			[2687] link bug, center=(696,834), url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Abug'
			StaticText #175 opened
			StaticText 2 weeks ago
			StaticText by
			[2691] link toadies, center=(572,859), title=Open issues created by toadies, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Atoadies'
			[2699] link 4 comments, center=(1538,832), inner_text= 4, url='https://github.com/Titan-Systems/titan/issues/175'
			[2709] link [FEATURE] Support for Snowflake masking policies and custom classifiers, center=(678,896), url='https://github.com/Titan-Systems/titan/issues/171'
			[2711] link enhancement, center=(1012,897), url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement'
			StaticText #171 opened
			StaticText 3 weeks ago
			StaticText by
			[2715] link anitalySuper, center=(586,922), title=Open issues created by anitalySuper, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3AanitalySuper'
			[2723] link 1 comment, center=(1538,895), inner_text= 1, url='https://github.com/Titan-Systems/titan/issues/171'
			[2733] link Behavior bundle 2024_08 has potentially breaking changes, center=(618,960), url='https://github.com/Titan-Systems/titan/issues/147'
			StaticText #147 opened
			StaticText on Nov 7, 2024
			StaticText by
			[2736] link teej, center=(577,985), title=Open issues created by teej, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Ateej'
			[2744] link 2 comments, center=(1538,958), inner_text= 2, url='https://github.com/Titan-Systems/titan/issues/147'
			[2754] link Resources and role_grants are not running in the correct order --maybe?, center=(670,1022), url='https://github.com/Titan-Systems/titan/issues/119'
			[2756] link bug, center=(970,1023), url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Abug'
			StaticText #119 opened
			StaticText on Oct 9, 2024
			StaticText by
			[2760] link dsmdavid, center=(590,1048), title=Open issues created by dsmdavid, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Adsmdavid'
			[2768] link 6 comments, center=(1538,1021), inner_text= 6, url='https://github.com/Titan-Systems/titan/issues/119'
			link [Documentation] resource_type.md is not availalble, url='https://github.com/Titan-Systems/titan/issues/116'
			link documentation, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Adocumentation'
			StaticText #116 opened
			StaticText on Sep 26, 2024
			StaticText by
			link pikachuev, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Apikachuev'
			link 1 comment, url='https://github.com/Titan-Systems/titan/issues/116'
			link Curious behavior with grant_on_alls: it keeps adding new resources, url='https://github.com/Titan-Systems/titan/issues/113'
			link enhancement, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement'
			link performance, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Aperformance'
			StaticText #113 opened
			StaticText on Sep 13, 2024
			StaticText by
			link alessio-gastaldo, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Aalessio-gastaldo'
			link 3 comments, url='https://github.com/Titan-Systems/titan/issues/113'
			link Support for resource parameters causes performance issues, url='https://github.com/Titan-Systems/titan/issues/88'
			link performance, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Aperformance'
			StaticText #88 opened
			StaticText on Jul 25, 2024
			StaticText by
			link titan-teej, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Atitan-teej'
		strong
			StaticText ProTip!
		StaticText Type
		StaticText on any issue or pull request to go back to the issue listing page.
	contentinfo
		heading Footer
		link Homepage, url='https://github.com/'
		StaticText © 2025 GitHub, Inc.
		navigation Footer
			heading Footer navigation
			list Footer navigation
				listitem
					link Terms, url='https://docs.github.com/site-policy/github-terms/github-terms-of-service'
				listitem
					link Privacy, url='https://docs.github.com/site-policy/privacy-policies/github-privacy-statement'
				listitem
					link Security, url='https://github.com/security'
				listitem
					link Status, url='https://www.githubstatus.com/'
				listitem
					link Docs, url='https://docs.github.com/'
				listitem
					link Contact, url='https://support.github.com/?tags=dotcom-footer'
				listitem
					button Manage cookies
				listitem
					button Do not share my personal information
	generic, atomic
		StaticText Issues · Titan-Systems/titan · GitHub
	generic, atomic
```
</details>

**Reasoning for action:** My goal is to explore the issues section of the Titan Systems GitHub repository to understand existing issues and potential features to contribute to the project. Clicking on the 'Issues' link (identified by the code '611') is a direct action that takes me to the relevant section where I can view and analyze open issues.

**Action:** click('611') # Click on the 'Issues' link to explore any reported issues in the repository.

**Change Description:** After clicking the 'Issues' link, the browser navigated to the Issues page of the Titan-Systems/titan repository, displaying the title 'Issues' along with a list of open and closed issues, where users can search issues or report new ones. The main navigation menu and repository details remained accessible, allowing further interactions.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://github.com/Titan-Systems/titan/issues

https://github.com/Titan-Systems/titan/issues/186

**Content (before/after):** 

```
RootWebArea Issues · Titan-Systems/titan · GitHub, focused, url='https://github.com/Titan-Systems/titan/issues'
	link Skip to content, url='https://github.com/Titan-Systems/titan/issues#start-of-content'
	banner
		heading Navigation Menu
		[193] link Homepage, center=(48,36), url='https://github.com/'
```
<details><summary>Show more</summary>

```
		navigation Global
			list
				listitem
					[202] button Product, center=(126,36), expanded=False, type=button
				listitem
					[264] button Solutions, center=(222,36), expanded=False, type=button
				listitem
					[306] button Resources, center=(329,36), expanded=False, type=button
				listitem
					[341] button Open Source, center=(451,36), expanded=False, type=button
				listitem
					[367] button Enterprise, center=(570,36), expanded=False, type=button
				listitem
					[397] link Pricing, center=(657,36), url='https://github.com/pricing'
		[400] button Search or jump to…, center=(1564,36), hasPopup='dialog', inner_text=Search or jump to..., type=button
			StaticText Search or jump to...
		[521] link Sign in, center=(1769,36), url='https://github.com/login?return_to=https%3A%2F%2Fgithub.com%2FTitan-Systems%2Ftitan'
		[522] link Sign up, center=(1851,36), url='https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F%3Cuser-name%3E%2F%3Crepo-name%3E&source=header-repo&source_repo=Titan-Systems%2Ftitan'
	main
		[547] link Titan-Systems, center=(120,103), url='https://github.com/Titan-Systems'
		StaticText /
		strong
			[550] link titan, center=(218,103), url='https://github.com/Titan-Systems/titan'
		StaticText Public
		list
			listitem
				[556] link You must be signed in to change notification settings, center=(1593,102), inner_text=Notifications, url='https://github.com/login?return_to=%2FTitan-Systems%2Ftitan'
					StaticText Notifications
			listitem
				[560] link Fork 32, center=(1712,102), url='https://github.com/login?return_to=%2FTitan-Systems%2Ftitan'
			listitem
				[565] link You must be signed in to star a repository, center=(1831,102), inner_text= Star 444, url='https://github.com/login?return_to=%2FTitan-Systems%2Ftitan'
					StaticText Star
		navigation Repository
			list
				listitem
					[606] link Code, center=(70,158), url='https://github.com/Titan-Systems/titan'
				listitem
					[611] link Issues 15, center=(174,158), focused, inner_text=Issues
15, url='https://github.com/Titan-Systems/titan/issues'
				listitem
					[616] link Pull requests 1, center=(320,158), inner_text=Pull requests
1, url='https://github.com/Titan-Systems/titan/pulls'
				listitem
					[621] link Discussions, center=(468,158), url='https://github.com/Titan-Systems/titan/discussions'
				listitem
					[626] link Actions, center=(583,158), url='https://github.com/Titan-Systems/titan/actions'
				listitem
					[631] link Security, center=(684,158), url='https://github.com/Titan-Systems/titan/security'
				listitem
					[636] link Insights, center=(786,158), url='https://github.com/Titan-Systems/titan/pulse'
		heading Issues: Titan-Systems/titan
		search
			search Issues
				[2304] textbox Search all issues value='is:issue is:open', center=(759,222), contenteditable=True, type=text
			navigation Issue
				[2308] link Labels 10, center=(1246,222), inner_text= Labels 10, url='https://github.com/Titan-Systems/titan/labels'
				[2311] link Milestones 0, center=(1381,222), inner_text= Milestones 0, url='https://github.com/Titan-Systems/titan/milestones'
		group
			[2324] button New issue, center=(1519,222), expanded=False
		generic
			[2351] link 15 Open, center=(409,282), inner_text= 15 Open, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aopen+is%3Aissue'
			[2353] link 53 Closed, center=(506,282), inner_text= 53 Closed, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aclosed'
		group
			button Author, expanded=False, hasPopup='menu'
		group
			button Label, expanded=False, hasPopup='menu'
		[2358] span, center=(1089,282)
		group
			button Projects, expanded=False, hasPopup='menu'
		[2382] span, center=(1167,282)
		group
			button Milestones, expanded=False, hasPopup='menu'
		[2408] span, center=(1261,282)
		group
			button Assignee, expanded=False, hasPopup='menu'
		[2422] span, center=(1376,282)
		group
			button Sort, expanded=False, hasPopup='menu'
		[2438] span, center=(1477,282)
		heading Issues list
		[2466] span, center=(1547,282)
		group Issues
			[2523] link [FEATURE] Support for Classification Profiles, center=(567,330), url='https://github.com/Titan-Systems/titan/issues/186'
			StaticText #186 opened
			StaticText 7 hours ago
			StaticText by
			[2526] link anitalySuper, center=(582,355), title=Open issues created by anitalySuper, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3AanitalySuper'
			[2541] link [Feature] Support for SQL UDFs and Procedures, center=(577,392), url='https://github.com/Titan-Systems/titan/issues/185'
			StaticText #185 opened
			StaticText 14 hours ago
			StaticText by
			[2544] link rcohngru-ab-carval, center=(606,418), title=Open issues created by rcohngru-ab-carval, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Arcohngru-ab-carval'
			[2559] link OAuth or Key-pair authentication, center=(519,456), url='https://github.com/Titan-Systems/titan/issues/183'
			StaticText #183 opened
			StaticText 3 days ago
			StaticText by
			[2562] link rus-kgo, center=(564,481), title=Open issues created by rus-kgo, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Arus-kgo'
			[2577] link [BUG] Future grants to database roles are re-applied all the time, center=(637,518), url='https://github.com/Titan-Systems/titan/issues/182'
			[2579] link bug, center=(902,519), url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Abug'
			StaticText #182 opened
			StaticText 2 weeks ago
			StaticText by
			[2583] link mlavaert, center=(576,544), title=Open issues created by mlavaert, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Amlavaert'
			[2598] link Ability to set a masking policy on a tag, center=(541,582), url='https://github.com/Titan-Systems/titan/issues/180'
			[2600] link enhancement, center=(736,582), url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement'
			StaticText #180 opened
			StaticText 2 weeks ago
			StaticText by
			[2604] link d-ohare, center=(574,607), title=Open issues created by d-ohare, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Ad-ohare'
			[2619] link [FEATURE] Ability to nest tables/views/etc under their parent schema or database config, center=(730,644), url='https://github.com/Titan-Systems/titan/issues/179'
			[2621] link enhancement, center=(1114,645), url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement'
			StaticText #179 opened
			StaticText 2 weeks ago
			StaticText by
			[2625] link GClunies, center=(578,670), title=Open issues created by GClunies, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3AGClunies'
			[2640] link Unable to use vars in database parameter for database_roles, center=(625,708), url='https://github.com/Titan-Systems/titan/issues/178'
			[2642] link bug, center=(878,708), url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Abug'
			StaticText #178 opened
			StaticText 2 weeks ago
			StaticText by
			[2646] link toadies, center=(572,733), title=Open issues created by toadies, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Atoadies'
			[2661] link Titan plan requires Database Role to be created before grant is analyzed, center=(668,770), url='https://github.com/Titan-Systems/titan/issues/176'
			[2663] link bug, center=(964,771), url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Abug'
			StaticText #176 opened
			StaticText 2 weeks ago
			StaticText by
			[2667] link toadies, center=(572,796), title=Open issues created by toadies, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Atoadies'
			[2675] link 3 comments, center=(1538,769), inner_text= 3, url='https://github.com/Titan-Systems/titan/issues/176'
			[2685] link Unable to use vars in Schema Owner, center=(533,834), url='https://github.com/Titan-Systems/titan/issues/175'
			[2687] link bug, center=(696,834), url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Abug'
			StaticText #175 opened
			StaticText 2 weeks ago
			StaticText by
			[2691] link toadies, center=(572,859), title=Open issues created by toadies, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Atoadies'
			[2699] link 4 comments, center=(1538,832), inner_text= 4, url='https://github.com/Titan-Systems/titan/issues/175'
			[2709] link [FEATURE] Support for Snowflake masking policies and custom classifiers, center=(678,896), url='https://github.com/Titan-Systems/titan/issues/171'
			[2711] link enhancement, center=(1012,897), url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement'
			StaticText #171 opened
			StaticText 3 weeks ago
			StaticText by
			[2715] link anitalySuper, center=(586,922), title=Open issues created by anitalySuper, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3AanitalySuper'
			[2723] link 1 comment, center=(1538,895), inner_text= 1, url='https://github.com/Titan-Systems/titan/issues/171'
			[2733] link Behavior bundle 2024_08 has potentially breaking changes, center=(618,960), url='https://github.com/Titan-Systems/titan/issues/147'
			StaticText #147 opened
			StaticText on Nov 7, 2024
			StaticText by
			[2736] link teej, center=(577,985), title=Open issues created by teej, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Ateej'
			[2744] link 2 comments, center=(1538,958), inner_text= 2, url='https://github.com/Titan-Systems/titan/issues/147'
			[2754] link Resources and role_grants are not running in the correct order --maybe?, center=(670,1022), url='https://github.com/Titan-Systems/titan/issues/119'
			[2756] link bug, center=(970,1023), url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Abug'
			StaticText #119 opened
			StaticText on Oct 9, 2024
			StaticText by
			[2760] link dsmdavid, center=(590,1048), title=Open issues created by dsmdavid, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Adsmdavid'
			[2768] link 6 comments, center=(1538,1021), inner_text= 6, url='https://github.com/Titan-Systems/titan/issues/119'
			link [Documentation] resource_type.md is not availalble, url='https://github.com/Titan-Systems/titan/issues/116'
			link documentation, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Adocumentation'
			StaticText #116 opened
			StaticText on Sep 26, 2024
			StaticText by
			link pikachuev, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Apikachuev'
			link 1 comment, url='https://github.com/Titan-Systems/titan/issues/116'
			link Curious behavior with grant_on_alls: it keeps adding new resources, url='https://github.com/Titan-Systems/titan/issues/113'
			link enhancement, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement'
			link performance, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Aperformance'
			StaticText #113 opened
			StaticText on Sep 13, 2024
			StaticText by
			link alessio-gastaldo, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Aalessio-gastaldo'
			link 3 comments, url='https://github.com/Titan-Systems/titan/issues/113'
			link Support for resource parameters causes performance issues, url='https://github.com/Titan-Systems/titan/issues/88'
			link performance, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+label%3Aperformance'
			StaticText #88 opened
			StaticText on Jul 25, 2024
			StaticText by
			link titan-teej, url='https://github.com/Titan-Systems/titan/issues?q=is%3Aissue+is%3Aopen+author%3Atitan-teej'
		strong
			StaticText ProTip!
		StaticText Type
		StaticText on any issue or pull request to go back to the issue listing page.
	contentinfo
		heading Footer
		link Homepage, url='https://github.com/'
		StaticText © 2025 GitHub, Inc.
		navigation Footer
			heading Footer navigation
			list Footer navigation
				listitem
					link Terms, url='https://docs.github.com/site-policy/github-terms/github-terms-of-service'
				listitem
					link Privacy, url='https://docs.github.com/site-policy/privacy-policies/github-privacy-statement'
				listitem
					link Security, url='https://github.com/security'
				listitem
					link Status, url='https://www.githubstatus.com/'
				listitem
					link Docs, url='https://docs.github.com/'
				listitem
					link Contact, url='https://support.github.com/?tags=dotcom-footer'
				listitem
					button Manage cookies
				listitem
					button Do not share my personal information
	generic, atomic
		StaticText Issues · Titan-Systems/titan · GitHub
	generic, atomic
```
</details>



```
RootWebArea [FEATURE] Support for Classification Profiles · Issue #186 · Titan-Systems/titan · GitHub, focused, url='https://github.com/Titan-Systems/titan/issues/186'
	link Skip to content, url='https://github.com/Titan-Systems/titan/issues/186#start-of-content'
	banner
		heading Navigation Menu
		[193] link Homepage, center=(48,36), url='https://github.com/'
```
<details><summary>Show more</summary>

```
		navigation Global
			list
				listitem
					[202] button Product, center=(126,36), expanded=False, type=button
				listitem
					[264] button Solutions, center=(222,36), expanded=False, type=button
				listitem
					[306] button Resources, center=(329,36), expanded=False, type=button
				listitem
					[341] button Open Source, center=(451,36), expanded=False, type=button
				listitem
					[367] button Enterprise, center=(570,36), expanded=False, type=button
				listitem
					[397] link Pricing, center=(657,36), url='https://github.com/pricing'
		[400] button Search or jump to…, center=(1564,36), hasPopup='dialog', inner_text=Search or jump to..., type=button
			StaticText Search or jump to...
		[521] link Sign in, center=(1769,36), url='https://github.com/login?return_to=https%3A%2F%2Fgithub.com%2FTitan-Systems%2Ftitan'
		[522] link Sign up, center=(1851,36), url='https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F%3Cuser-name%3E%2F%3Crepo-name%3E&source=header-repo&source_repo=Titan-Systems%2Ftitan'
	main
		[547] link Titan-Systems, center=(120,103), url='https://github.com/Titan-Systems'
		StaticText /
		strong
			[550] link titan, center=(218,103), url='https://github.com/Titan-Systems/titan'
		StaticText Public
		list
			listitem
				[556] link You must be signed in to change notification settings, center=(1593,102), inner_text=Notifications, url='https://github.com/login?return_to=%2FTitan-Systems%2Ftitan'
					StaticText Notifications
			listitem
				[560] link Fork 32, center=(1712,102), url='https://github.com/login?return_to=%2FTitan-Systems%2Ftitan'
			listitem
				[565] link You must be signed in to star a repository, center=(1831,102), inner_text= Star 444, url='https://github.com/login?return_to=%2FTitan-Systems%2Ftitan'
					StaticText Star
		navigation Repository
			list
				listitem
					[606] link Code, center=(70,158), url='https://github.com/Titan-Systems/titan'
				listitem
					[611] link Issues 15, center=(174,158), inner_text=Issues
15, url='https://github.com/Titan-Systems/titan/issues'
				listitem
					[616] link Pull requests 1, center=(320,158), inner_text=Pull requests
1, url='https://github.com/Titan-Systems/titan/pulls'
				listitem
					[621] link Discussions, center=(468,158), url='https://github.com/Titan-Systems/titan/discussions'
				listitem
					[626] link Actions, center=(583,158), url='https://github.com/Titan-Systems/titan/actions'
				listitem
					[631] link Security, center=(684,158), url='https://github.com/Titan-Systems/titan/security'
				listitem
					[636] link Insights, center=(786,158), url='https://github.com/Titan-Systems/titan/pulse'
		group
			[2871] button New issue, center=(1527,226), expanded=False
		heading [FEATURE] Support for Classification Profiles #186
		StaticText Open
		[2900] link anitalySuper, center=(482,268), url='https://github.com/anitalySuper'
		StaticText opened this issue
		StaticText 7 hours ago
		StaticText · 0 comments
		heading Comments
		[2929] link @anitalySuper, center=(372,354), url='https://github.com/anitalySuper'
			image @anitalySuper, url='https://avatars.githubusercontent.com/u/162352597?s=80&v=4'
		group
			button Show options, expanded=False, hasPopup='menu'
				[2939] image Show options, center=(1219,352)
		heading anitalySuper commented 7 hours ago•
			strong
				[2948] link anitalySuper, center=(467,352), url='https://github.com/anitalySuper'
			[2949] link 7 hours ago, center=(627,352), url='https://github.com/Titan-Systems/titan/issues/186#issue-2766865768'
			StaticText •
			group
				button edited, expanded=False, hasPopup='menu'
		LayoutTable
			LayoutTableRow
				LayoutTableCell Add support to create classification profiles in Snowflake, which enables automatic sensitive data classification, and apply the classification profile to a specified schema. https://docs.snowflake.com/en/sql-reference/classes/classification_profile/commands/create-classification-profile. https://docs.snowflake.com/en/user-guide/classify-auto#get-started
					paragraph
					paragraph
						[2970] link https://docs.snowflake.com/en/sql-reference/classes/classification_profile/commands/create-classification-profile, center=(772,456), url='https://docs.snowflake.com/en/sql-reference/classes/classification_profile/commands/create-classification-profile'
						[2972] link https://docs.snowflake.com/en/user-guide/classify-auto#get-started, center=(632,477), url='https://docs.snowflake.com/en/user-guide/classify-auto#get-started'
		[2956] svg, center=(727,354)
		[2955] span, center=(698,352), inner_text=edited 
		[3006] link Sign up for free, center=(434,576), url='https://github.com/join?source=comment-repo'
		strong
			StaticText to join this conversation on GitHub
		StaticText . Already have an account?
		[3008] link Sign in to comment, center=(969,575), url='https://github.com/login?return_to=https%3A%2F%2Fgithub.com%2FTitan-Systems%2Ftitan%2Fissues%2F186'
		form Select assignees
			StaticText Assignees
			StaticText No one assigned
		StaticText Labels
		StaticText None yet
		form Select projects
			StaticText Projects
			generic
			StaticText None yet
		form Select milestones
			StaticText Milestone
			StaticText No milestone
		form Link issues
			StaticText Development
			paragraph
				StaticText No branches or pull requests
		StaticText 1 participant
		[3043] link @anitalySuper, center=(1285,778), url='https://github.com/anitalySuper'
			image @anitalySuper, url='https://avatars.githubusercontent.com/u/162352597?s=52&v=4'
	contentinfo
		heading Footer
		[2240] link Homepage, center=(586,868), title=GitHub, url='https://github.com/'
		StaticText © 2025 GitHub, Inc.
		navigation Footer
			heading Footer navigation
			list Footer navigation
				listitem
					[2247] link Terms, center=(744,868), url='https://docs.github.com/site-policy/github-terms/github-terms-of-service'
				listitem
					[2249] link Privacy, center=(796,868), url='https://docs.github.com/site-policy/privacy-policies/github-privacy-statement'
				listitem
					[2251] link Security, center=(854,868), url='https://github.com/security'
				listitem
					[2253] link Status, center=(908,868), url='https://www.githubstatus.com/'
				listitem
					[2255] link Docs, center=(955,868), url='https://docs.github.com/'
				listitem
					[2257] link Contact, center=(1005,868), url='https://support.github.com/?tags=dotcom-footer'
				listitem
					[2259] button Manage cookies, center=(1086,868), type=button
				listitem
					[2261] button Do not share my personal information, center=(1246,868), type=button
	generic, atomic
		StaticText [FEATURE] Support for Classification Profiles · Issue #186 · Titan-Systems/titan · GitHub
	generic, atomic
```
</details>

**Reasoning for action:** The issue list displays various open issues in the GitHub repository. Clicking on the link corresponding to the issue titled '[FEATURE] Support for Classification Profiles' will navigate me to the detailed view of that issue. This is crucial for achieving the user's goal of understanding existing issues and potential features to contribute to, as each issue contains valuable information, discussions, and context that can guide the user's contributions.

**Action:** click('2523') # Click on the first open issue titled '[FEATURE] Support for Classification Profiles'.

**Change Description:** The browser navigated from the issues list of the 'Titan-Systems/titan' repository to the specific issue page of the first open issue titled '[FEATURE] Support for Classification Profiles', displaying its details, comments, and associated links.

**Screenshot before:****Screenshot after:**---


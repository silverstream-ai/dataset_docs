# Task

**User Journey through Mineflow Documentation**

As a new user interested in mineral exploration technology,
I learn about Mineflow's services and how to effectively use them,
so that I can easily get started with uploading my exploration data and utilizing the platform's capabilities.

**Success definition:** Given I am on the Mineflow homepage
When I click on the About link and then the Documentation link, followed by the Getting Started link
Then I should be able to view the Getting Started guide along with detailed instructions on how to upload exploration data.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://mineflow.ai/

https://mineflow.ai/about

**Content (before/after):** 

```
RootWebArea Mineflow, focused, url='https://mineflow.ai/'
	navigation
		list
			listitem
				[32] link X Mineflow, center=(397,29), inner_text=Mineflow, url='https://mineflow.ai/'
```
<details><summary>Show more</summary>

```
					image X, url='https://mineflow.ai/mf512_transparent.png'
					paragraph
			list
				listitem
					[37] link About, center=(515,29), url='https://mineflow.ai/about'
				listitem
					[39] link Documentation, center=(601,29), url='https://mineflow.ai/docs'
				listitem
					[41] link Pricing, center=(690,29), url='https://mineflow.ai/pricing'
				listitem
					[43] link Team, center=(746,29), url='https://mineflow.ai/team'
				listitem
					[45] link Portal, center=(799,29), url='https://mineflow.ai/portal'
		list
			list
				listitem
					LabelText Switch to dark mode
						switch Switch to dark mode, checked='true'
				listitem
					[55] button Log in, center=(1423,29)
				[53] svg, center=(1361,29)
				listitem
					[57] button Sign Up, center=(1512,29)
	main
		heading Mineral exploration powered by AI
		heading Mineflow transforms exploration site data into highly accurate predictions of the shape of mineral deposits.
		[74] button Book a demo, center=(901,284)
		[75] button How it works, center=(1020,284), type=button
		heading 2D Prospectivity Mapping
		image Picture of the 2d prospectivity map, url='https://mineflow.ai/_next/image?url=%2Fpred.png&w=640&q=75'
		image Picture of the 3d block model, url='https://mineflow.ai/_next/image?url=%2F3dp.png&w=640&q=75'
		heading 3D Resource Modeling of a Gold Deposit
		heading 3D Resource Modeling of a Copper Porphyry
		image Picture of the 3d block model, url='https://mineflow.ai/_next/image?url=%2Fslkd.png&w=640&q=75'
	contentinfo
		link X, url='https://www.ycombinator.com/'
			image X, url='https://mineflow.ai/Black.png'
	region Notifications Alt+T
	alert, atomic
```
</details>



```
RootWebArea Mineflow, focused, url='https://mineflow.ai/about'
	navigation
		list
			listitem
				[116] link X Mineflow, center=(397,29), inner_text=Mineflow, url='https://mineflow.ai/'
```
<details><summary>Show more</summary>

```
					image X, url='https://mineflow.ai/mf512_transparent.png'
					paragraph
			list
				listitem
					[121] link About, center=(515,29), url='https://mineflow.ai/about'
				listitem
					[123] link Documentation, center=(601,29), url='https://mineflow.ai/docs'
				listitem
					[125] link Pricing, center=(690,29), url='https://mineflow.ai/pricing'
				listitem
					[127] link Team, center=(746,29), url='https://mineflow.ai/team'
				listitem
					[129] link Portal, center=(799,29), url='https://mineflow.ai/portal'
		list
			list
				listitem
					LabelText Switch to dark mode
						switch Switch to dark mode, checked='true'
				listitem
					[139] button Log in, center=(1423,29)
				[137] svg, center=(1361,29)
				listitem
					[141] button Sign Up, center=(1512,29)
	main
		article
			heading About
			paragraph
				image Images, url='https://mineflow.ai/titless.png'
			paragraph
				StaticText Mineflow is an AI platform for mineral exploration. We generate predictions for mineral deposit shapes and locations, empowering mining companies from initial exploration to advanced feasibility studies.
			paragraph
				StaticText Whether you're just beginning to explore a site or you've drilled hundreds of holes and you're refining predictions for your feasibility study, Mineflow is the essential tool in every modern geologist's toolkit. We're transforming mineral exploration with AI-powered precision, helping you uncover valuable deposits more efficiently than ever before.
			heading How It Works
			list
				[164] listitem, center=(972,755), inner_text=Your geologists work closely with the Mineflow team to upload a zip file of all the data they have collected at their exploration sites (every survey, drill hole, rock sample, etc.)
					ListMarker 0.
					StaticText Your geologists work closely with the Mineflow team to upload a zip file of all the data they have collected at their exploration sites (every survey, drill hole, rock sample, etc.)
				[165] listitem, center=(972,800), inner_text=The Mineflow team creates two custom AI models for you based on your data: a 2D prospectivity model for birds-eye view predictions and a 3D resource model for underground predictions
					ListMarker 0.
					StaticText The Mineflow team creates two custom AI models for you based on your data: a 2D prospectivity model for birds-eye view predictions and a 3D resource model for underground predictions
				[166] listitem, center=(972,845), inner_text=For every site, the Mineflow team uses these custom AI models to generate a 2D prospectivity map and a 3D block model
					ListMarker 0.
					StaticText For every site, the Mineflow team uses these custom AI models to generate a 2D prospectivity map and a 3D block model
				[167] listitem, center=(972,877), inner_text=The Mineflow team iteratively updates your predictions based on any new data/feedback that you provide
					ListMarker 0.
					StaticText The Mineflow team iteratively updates your predictions based on any new data/feedback that you provide
			paragraph
				StaticText See
				[169] link Documentation, center=(405,918), url='https://mineflow.ai/docs'
				StaticText for an in-depth tutorial.
			separator, orientation='horizontal'
	region Notifications Alt+T
	alert, atomic
```
</details>

**Reasoning for action:** I chose to click on the About link as my first step because it is crucial to understand what Mineflow offers. This action will provide me with context about the company and its services, helping me align my expectations and understanding as I move forward to the Documentation section.

**Action:** click(37) # Click on the About link to explore more about Mineflow.

**Change Description:** The browser navigated to the 'About' page of the Mineflow website, changing the URL to 'https://mineflow.ai/about', and the main content now displays information about Mineflow, including a description of its AI platform for mineral exploration and how it works.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://mineflow.ai/about

https://mineflow.ai/docs

**Content (before/after):** 

```
RootWebArea Mineflow, focused, url='https://mineflow.ai/about'
	navigation
		list
			listitem
				[116] link X Mineflow, center=(397,29), inner_text=Mineflow, url='https://mineflow.ai/'
```
<details><summary>Show more</summary>

```
					image X, url='https://mineflow.ai/mf512_transparent.png'
					paragraph
			list
				listitem
					[121] link About, center=(515,29), url='https://mineflow.ai/about'
				listitem
					[123] link Documentation, center=(601,29), url='https://mineflow.ai/docs'
				listitem
					[125] link Pricing, center=(690,29), url='https://mineflow.ai/pricing'
				listitem
					[127] link Team, center=(746,29), url='https://mineflow.ai/team'
				listitem
					[129] link Portal, center=(799,29), url='https://mineflow.ai/portal'
		list
			list
				listitem
					LabelText Switch to dark mode
						switch Switch to dark mode, checked='true'
				listitem
					[139] button Log in, center=(1423,29)
				[137] svg, center=(1361,29)
				listitem
					[141] button Sign Up, center=(1512,29)
	main
		article
			heading About
			paragraph
				image Images, url='https://mineflow.ai/titless.png'
			paragraph
				StaticText Mineflow is an AI platform for mineral exploration. We generate predictions for mineral deposit shapes and locations, empowering mining companies from initial exploration to advanced feasibility studies.
			paragraph
				StaticText Whether you're just beginning to explore a site or you've drilled hundreds of holes and you're refining predictions for your feasibility study, Mineflow is the essential tool in every modern geologist's toolkit. We're transforming mineral exploration with AI-powered precision, helping you uncover valuable deposits more efficiently than ever before.
			heading How It Works
			list
				[164] listitem, center=(972,755), inner_text=Your geologists work closely with the Mineflow team to upload a zip file of all the data they have collected at their exploration sites (every survey, drill hole, rock sample, etc.)
					ListMarker 0.
					StaticText Your geologists work closely with the Mineflow team to upload a zip file of all the data they have collected at their exploration sites (every survey, drill hole, rock sample, etc.)
				[165] listitem, center=(972,800), inner_text=The Mineflow team creates two custom AI models for you based on your data: a 2D prospectivity model for birds-eye view predictions and a 3D resource model for underground predictions
					ListMarker 0.
					StaticText The Mineflow team creates two custom AI models for you based on your data: a 2D prospectivity model for birds-eye view predictions and a 3D resource model for underground predictions
				[166] listitem, center=(972,845), inner_text=For every site, the Mineflow team uses these custom AI models to generate a 2D prospectivity map and a 3D block model
					ListMarker 0.
					StaticText For every site, the Mineflow team uses these custom AI models to generate a 2D prospectivity map and a 3D block model
				[167] listitem, center=(972,877), inner_text=The Mineflow team iteratively updates your predictions based on any new data/feedback that you provide
					ListMarker 0.
					StaticText The Mineflow team iteratively updates your predictions based on any new data/feedback that you provide
			paragraph
				StaticText See
				[169] link Documentation, center=(405,918), url='https://mineflow.ai/docs'
				StaticText for an in-depth tutorial.
			separator, orientation='horizontal'
	region Notifications Alt+T
	alert, atomic
```
</details>



```
RootWebArea Mineflow, focused, url='https://mineflow.ai/docs'
	navigation
		list
			listitem
				[62] link X Mineflow, center=(397,29), inner_text=Mineflow, url='https://mineflow.ai/'
```
<details><summary>Show more</summary>

```
					image X, url='https://mineflow.ai/mf512_transparent.png'
					paragraph
			list
				listitem
					[67] link About, center=(515,29), url='https://mineflow.ai/about'
				listitem
					[69] link Documentation, center=(601,29), url='https://mineflow.ai/docs'
				listitem
					[71] link Pricing, center=(690,29), url='https://mineflow.ai/pricing'
				listitem
					[73] link Team, center=(746,29), url='https://mineflow.ai/team'
				listitem
					[75] link Portal, center=(799,29), url='https://mineflow.ai/portal'
		list
			list
				listitem
					LabelText Switch to dark mode
						switch Switch to dark mode, checked='true'
				listitem
					[85] button Log in, center=(1423,29)
				[83] svg, center=(1361,29)
				listitem
					[87] button Sign Up, center=(1512,29)
	complementary
		navigation
			list
				listitem
					[105] link Overview, center=(144,94), url='https://mineflow.ai/docs#overview'
				listitem
					[107] link Getting Started, center=(144,144), url='https://mineflow.ai/docs#getting-started'
				listitem
					[109] link Data Uploads, center=(144,180), url='https://mineflow.ai/docs#data-uploads'
				listitem
					[111] link What data should I upload?, center=(151,216), url='https://mineflow.ai/docs#what-data-should-i-upload'
				listitem
					[113] link Non-drill data, center=(151,252), url='https://mineflow.ai/docs#non-drill-data'
				listitem
					[115] link Drill data, center=(151,288), url='https://mineflow.ai/docs#drill-data'
				listitem
					[117] link Data Designations, center=(144,324), url='https://mineflow.ai/docs#data-designations'
				listitem
					[119] link Updating designation, center=(151,360), url='https://mineflow.ai/docs#updating-designation'
				listitem
					[121] link Data Classes, center=(144,396), url='https://mineflow.ai/docs#data-classes'
				listitem
					[123] link Mineflow creates your predictive model, center=(144,443), url='https://mineflow.ai/docs#mineflow-creates-your-predictive-model'
				listitem
					[125] link Generating predictions, center=(144,489), url='https://mineflow.ai/docs#generating-predictions'
				listitem
					[127] link Video demo, center=(144,525), url='https://mineflow.ai/docs#video-demo'
				listitem
					[129] link Best practices, center=(144,561), url='https://mineflow.ai/docs#best-practices'
				listitem
					[131] link FAQ, center=(144,597), url='https://mineflow.ai/docs#faq'
				listitem
					[133] link How does Mineflow compare to existing solutions?, center=(151,644), url='https://mineflow.ai/docs#how-does-mineflow-compare-to-existing-solutions'
				listitem
					[135] link Why is Mineflow better than joint inversion models?, center=(151,702), url='https://mineflow.ai/docs#why-is-mineflow-better-than-joint-inversion-models'
				listitem
					[137] link Why are few assumptions good?, center=(151,759), url='https://mineflow.ai/docs#why-are-few-assumptions-good'
	main
		article
			heading Documentation
			paragraph
				StaticText Welcome to the Mineflow documentation!
			separator, orientation='horizontal'
			heading Overview
			paragraph
				StaticText Mineflow uses your exploration data to train a
				[147] link neural network, center=(677,350), url='https://en.wikipedia.org/wiki/Neural_network_(machine_learning)'
				StaticText to predict the shape and location of mineral deposits. The custom neural networks that Mineflow develops require minimal updates or feedback from the user. Use of the Mineflow platform does not require any background in machine learning on your part.
			separator, orientation='horizontal'
			heading Getting Started
			paragraph
				StaticText Start by uploading any exploration data from your sites.
			heading Data Uploads
			list
				listitem
					ListMarker 0.
					StaticText Go to the datasets section of the
					[154] link Portal, center=(589,648), url='https://mineflow.ai/portal'
					StaticText , press 'New Dataset,' and select the files you want to upload.
					image Images, url='https://mineflow.ai/datasets.png'
			heading What data should I upload?
			paragraph
				StaticText Great question. The short answer: upload any shapefile or Excel file related to the exploration site you're focusing on.
			paragraph
				StaticText A more detailed answer: It’s easy to understand why a shapefile containing outcrops of rocks in the area is valuable for training a predictive model. But what about a shapefile with polygons representing all the houses in the area where you’re drilling? Is that useful? Absolutely. Mineflow makes no assumptions about the data distribution and will supplement your uploads with additional data it finds online. So, a file identifying house locations can help Mineflow correlate data samples. For instance, Mineflow often uses satellite data to understand a site, and when combined with your house shapefile, Mineflow can learn to distinguish houses from significant geological features visible in aerial imagery.
			heading Non-drill data
			paragraph
				StaticText You can upload zip files (*.zip) that contain shapefiles or shapefiles themselves (*.sbx, *.dbf, *.shp, *.shx, *.xml, *.prj, *.sbn, *.cpg) for the non-drill data.
			heading Drill data
			paragraph
				StaticText For your drill data, upload Excel files (.xlsx). Ideally, your files should have columns that give the starting depth and the ending depth of each segment as well as some unique identifier for each drill hole segment (e.g. hole name).
			strong
			paragraph
				StaticText Note: If your dips and azimuths are split into a separate shapefile that's okay, Mineflow will handle parsing that out for you.
			heading Data Designations
			paragraph
				StaticText After you upload your data, you'll notice that each file is assigned a "designation."
				image Images, url='https://mineflow.ai/dsg.png'
			paragraph
				StaticText A designation is Mineflow's guess as to what type of data you uploaded. There are eight possible designations:
			list
				listitem
					ListMarker 0.
					StaticText Rock outcropping/expert labeled rock body: Polygons that represent rock bodies that are either outcroppings or generally agreed on rock structures underground
				listitem
					ListMarker 0.
					StaticText Non-rock visible object: Any object that is visible on the ground (e.g. building, river, road, tree) that has not been labeled as a rock
				listitem
					ListMarker 0.
					StaticText AOI: Any general area of interest, usually some sort of polygon
				listitem
					ListMarker 0.
					StaticText Aerial survey: All contour-line based data types. Any overhead surveys or imagery or LiDAR is going to fall into this group
				listitem
					ListMarker 0.
					StaticText Rock/soil/geochemical samples: Points where rocks or soil were sampled (e.g. descriptions of the rock sampled, PPMs of elements in the soil)
				listitem
					ListMarker 0.
					StaticText Drill collar locations and names: Data about the location of the collars
				listitem
					ListMarker 0.
					StaticText Drill hole traces: Files that contain the depth, dips and azimuths of your drill segments
				listitem
					ListMarker 0.
					StaticText Drill data: Drill assays or lithologies (or any other drill data)
			strong
			paragraph
				StaticText Note: If you think that there are data groupings missing here, please let us know! There may be a better way to explain/phrase the groupings.
			heading Updating designation
			paragraph
				StaticText You'll notice that you can change the designation for a file. This is useful for Mineflow when it starts to train the predictive model on your dataset.
			heading Data Classes
			paragraph
				StaticText After you upload your data, you'll notice that it is also assigned a "class."
				image Images, url='https://mineflow.ai/cls.png'
			paragraph
				StaticText A class is Mineflow's guess as to how many different types of data are represented in that file. The word class here comes from machine learning terminology where a
				link class, url='https://en.wikipedia.org/wiki/Multiclass_classification'
				StaticText is a type of label that a piece of data falls into. A file can be one of two things:
			list
				listitem
					ListMarker 0.
					StaticText Mono-class: Mono-class files are files that only contain one type of an object. A few examples of this: a shapefile that only contains granite rock outcroppings, a shapefile that contains lines that represent waterways in the area, a shapefile that contains the general structure (polygon) of a belt of pegmatites running through the area, a shapefile that is a set of points where you found rocks containing mica on the ground, a shapefile that has polygons that are all the houses in the area (yes, this data can be useful to upload!).
				listitem
					ListMarker 0.
					StaticText Multi-class: Multi-class files are files that contain multiple types of an object. A few examples of this: a shapefile that contains rock outcroppings that you have labeled as having different lithologies (e.g. granite, marble, etc.).
			heading Mineflow creates your predictive model
			paragraph
				StaticText After creating your dataset, the Mineflow team will "
				link train, url='https://en.wikipedia.org/wiki/Machine_learning'
				StaticText " a model on that dataset. That means that we create a statistical model with the objective of generalizing from its experience. We will train two models for you:
			list
				listitem
					ListMarker 0.
					StaticText Two-dimensional predictions: also known as prospectivity maps, these are 2D maps that represent the general shape of rock and mineral structures from a bird's eye view.
				listitem
					ListMarker 0.
					StaticText Three-dimensional predictions: also known as block models, these are 3D grids that represent the detailed shape and location of mineral structures underground.
			strong
			paragraph
				StaticText Note: We are only able to train a model to produce three-dimensional predictions if you have uploaded some drill data (otherwise the model doesn't know how to correlate data from the surface with data underground).
			paragraph
				StaticText The time it takes to train a predictive model depends on the size of the dataset, the size of the area and whether or not the model is 2D or 3D.
			list
				listitem
					ListMarker •
					StaticText Small datasets (less than 25 megabytes of data) for 2D will generally take 1 hour per 1 sq. mile of area. So, if I have a dataset that is a few megabytes and I've collected data over a 2 mile by 2 mile area, then the training of the 2D model will take about 4 hours.
				listitem
					ListMarker •
					StaticText Large datasets (greater than 25 megabytes of data) for 2D will generally take 4 hours per 1 sq. mile of area. So, if I have a dataset that is 100 megabytes in size and I've collected data over a 2 mile by 2 mile area, then the training of the 2D model will take around 16 hours.
				listitem
					ListMarker •
					StaticText 3D models generally take twice as long as 2D models, so for small datasets on a 2x2 mile area, training will take 8 hours and for large datasets on a 2x2 mile area, training will take around 32 hours.
			paragraph
				StaticText Once the Mineflow team has trained your custom model (see
				link training ETA, url='https://mineflow.ai/docs#model-training-eta'
				StaticText just below), you'll get an email from notifications@mineflow.ai, saying:
			generic
				StaticText Hi {name},

{model name} is done training. Click here to start making predictions with it!
			paragraph
				StaticText Here is an example of the email:
			paragraph
				image Images, url='https://mineflow.ai/email.png'
			paragraph
				StaticText When you return to the
				link Portal, url='https://mineflow.ai/portal'
				StaticText , your model will appear there, marked as successfully trained:
			paragraph
				image Images, url='https://mineflow.ai/newmody.png'
			heading Generating predictions
			paragraph
				StaticText Once we have created your model, the Mineflow team will create a project where you can see an image with location, shape and size of your model's predictions.
			paragraph
				StaticText Navigate to the
				link Portal, url='https://mineflow.ai/portal'
				StaticText to see your new project.
				image Images, url='https://mineflow.ai/projects.png'
			paragraph
				StaticText Clicking on your project will take you to a screen with a map on it that shows all of the data you uploaded:
				image Images, url='https://mineflow.ai/titleit.png'
			paragraph
				StaticText Then, click the predict tab and choose the model that we just trained:
				image Images, url='https://mineflow.ai/smod.png'
			paragraph
				StaticText Then, select the area you're interested in:
				image Images, url='https://mineflow.ai/sarea.png'
			paragraph
				StaticText Press "generate predictions":
				image Images, url='https://mineflow.ai/load.png'
			paragraph
				StaticText A few minutes (or hours depending on the size of the area) later, you'll get an email saying that your predictions are ready and when you return to the project, it will have generated both a 2D prospectivity map for that area as well as a 3D block model for that area.
			paragraph
				StaticText Here is an example of what the 2D prospectivity map might look like:
				image Images, url='https://mineflow.ai/pred.png'
			paragraph
				StaticText Here is an example of what a 3D block model might look like for a copper deposit. You can manipulate the 3D shape and adjust the visibility and transparency of each of the grades of copper.
			paragraph
				image Alt Text, url='https://mineflow.ai/copperspin.gif'
			paragraph
				StaticText The model can generate predictions
				strong
					StaticText for any mineral you want
				StaticText .
			paragraph
				StaticText For instance, here is the software generating a block model for a gold deposit:
			paragraph
				image Alt Text, url='https://mineflow.ai/goldspin.gif'
			heading Video demo
			paragraph
				StaticText A video showing the site in use can be found
				link here, url='https://mineflow.ai/demo'
				StaticText .
			heading Best practices
			list
				listitem
					ListMarker 0.
					StaticText Generally, the more data you upload, the easier it is for the model to learn to predict your deposit.
				listitem
					ListMarker 0.
					StaticText The more accurate your data is, the easier it is for the model to learn to predict your deposit. The more missing data and improperly labeled rocks you have in your dataset, the more likely it is that your model takes longer to train and yields less reliable results.
				listitem
					ListMarker 0.
					StaticText When choosing an area where you wish to generate predictions, the closer your location is to where your dataset is clustered, the better your predictions will be. "Close" in this context means within 5 miles. It is much harder for the model to make an inference about a location in the middle of the Pacific Ocean if your dataset was collected in South Africa!
				listitem
					ListMarker 0.
					StaticText One area where Mineflow can be particularly useful to a veteran geo is in remembering that single data point from that site you visited 15 years ago and inferring that the exploration site you're looking at now actually has a lot in common with it, despite being halfway across the globe.
			heading FAQ
			heading How does Mineflow compare to existing solutions?
			paragraph
				StaticText Traditional geological modeling software usually supports estimators like
				link Radial Basis Function, url='https://en.wikipedia.org/wiki/Radial_basis_function'
				StaticText (RBF),
				link Inverse Distance, url='https://en.wikipedia.org/wiki/Inverse_distance_weighting'
				StaticText estimator and techniques like wireframing and kriging. These can be used to take drill data and make guesses about what the shape of the deposit might look like.
			paragraph
				StaticText Here's how Mineflow differs:
			list
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Comprehensive data integration
						StaticText : Our model incorporates
						strong
							StaticText all available data points from the site
						StaticText , not just drilling information, ensuring a more complete analysis. RBF/Inverse distance/others cannot support the complex, multimodal data you have collected on site (like individual rock samples and geochemical samples). All data types are supported by Mineflow. Mineflow generates predictions based on all of the data you have collected as long as it is georeferenced.
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Cross-site learning
						StaticText : Mineflow allows you to leverage data from one site to inform exploration at another. If there is any similarity at all in the data collected at the two sites, Mineflow's neural net will find that correlation. RBF/Inverse distance/others are not able to learn how to make predictions based on multiple-sites worth of data.
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Advanced pattern recognition
						StaticText : Mineflow uses deep learning-based AI and sophisticated machine learning algorithms to understand complex, non-linear relationships between multiple samples even if they are not close to each other on a map. RBF/Inverse distance/others are just functions that find lines between points, so they are not able to do this.
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Identify missed deposits
						StaticText : Because RBF/Inverse distance/others just find lines between data points, if there is a second deposit that is close by that you haven't directly intersected with, RBF and Inverse Distance will never find it. Mineflow will likely find it.
			heading Why is Mineflow better than joint inversion models?
			list
				listitem
					ListMarker 0.
					strong
						StaticText Parametrization
					StaticText : In joint inversion models, you need to parametrize the shape of your deposit, which means that you need to make assumptions about the data and the way rock structures form. In the case where your assumptions about how to parametrize a deposit are correct, great! Your joint inversion model will
					emphasis
						StaticText probably
					StaticText take longer to train than a Mineflow model and may achieve results which are nearly as high in accuracy as Mineflow. In the case where your assumptions about how to parametrize a deposit are incorrect, your joint inversion model will be misleading and you will end up wasting exploration resources by drilling in suboptimal locations.
			paragraph
				image Images, url='https://mineflow.ai/assumptionsvsinference.png'
			list
				listitem
					ListMarker 0.
					strong
						StaticText Cross-site learning
					StaticText : Same as point 2 in the first question.
			heading Why are few assumptions good?
			paragraph
				StaticText Humans have developed an strong understanding of geology and with it, powerful abstractions for how rock structures tend to form and correlate with one another. This leads to new mineral discoveries and scientific achievements regularly.
			paragraph
				StaticText That said, when you consider
				emphasis
					StaticText any
				StaticText field from a computational perspective, trying to program human intuition into your model of how systems work is difficult and often
				link misguided, url='https://www.cs.utexas.edu/~eunsol/courses/data/bitter_lesson.pdf'
				StaticText . When we look at the history of computational models, we find that those that excel are
				strong
					StaticText big
				StaticText and
				strong
					StaticText generalizable
				StaticText --that is, they take in a massive amount of data and they have few assumptions hard-coded into how they handle that data. The field of mineral exploration is well-poised to take advantage of the explosion of publicly available data on the natural world. From academic datasets to satellite APIs and published 43-101s, the internet is full of data that we combine with the power of AI to better predict what is underground.
	region Notifications Alt+T
	alert, atomic
```
</details>

**Reasoning for action:** I clicked on the Documentation link because it is the next step required to find the detailed instructions for using Mineflow's services as outlined in the user story. This action directly leads me to the resources that can help the user learn more and get started with uploading their exploration data.

**Action:** click(169) # Click on the Documentation link for more detailed information about Mineflow's services.

**Change Description:** After clicking the Documentation link, the browser navigated to the Documentation page of the Mineflow website, updating the URL to 'https://mineflow.ai/docs'. The main content now displays an overview of Mineflow's documentation, including sections on Getting Started, Data Uploads, and the various data types supported, as well as links for further detailed information.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://mineflow.ai/docs

https://mineflow.ai/docs#getting-started

**Content (before/after):** 

```
RootWebArea Mineflow, focused, url='https://mineflow.ai/docs'
	navigation
		list
			listitem
				[62] link X Mineflow, center=(397,29), inner_text=Mineflow, url='https://mineflow.ai/'
```
<details><summary>Show more</summary>

```
					image X, url='https://mineflow.ai/mf512_transparent.png'
					paragraph
			list
				listitem
					[67] link About, center=(515,29), url='https://mineflow.ai/about'
				listitem
					[69] link Documentation, center=(601,29), url='https://mineflow.ai/docs'
				listitem
					[71] link Pricing, center=(690,29), url='https://mineflow.ai/pricing'
				listitem
					[73] link Team, center=(746,29), url='https://mineflow.ai/team'
				listitem
					[75] link Portal, center=(799,29), url='https://mineflow.ai/portal'
		list
			list
				listitem
					LabelText Switch to dark mode
						switch Switch to dark mode, checked='true'
				listitem
					[85] button Log in, center=(1423,29)
				[83] svg, center=(1361,29)
				listitem
					[87] button Sign Up, center=(1512,29)
	complementary
		navigation
			list
				listitem
					[105] link Overview, center=(144,94), url='https://mineflow.ai/docs#overview'
				listitem
					[107] link Getting Started, center=(144,144), url='https://mineflow.ai/docs#getting-started'
				listitem
					[109] link Data Uploads, center=(144,180), url='https://mineflow.ai/docs#data-uploads'
				listitem
					[111] link What data should I upload?, center=(151,216), url='https://mineflow.ai/docs#what-data-should-i-upload'
				listitem
					[113] link Non-drill data, center=(151,252), url='https://mineflow.ai/docs#non-drill-data'
				listitem
					[115] link Drill data, center=(151,288), url='https://mineflow.ai/docs#drill-data'
				listitem
					[117] link Data Designations, center=(144,324), url='https://mineflow.ai/docs#data-designations'
				listitem
					[119] link Updating designation, center=(151,360), url='https://mineflow.ai/docs#updating-designation'
				listitem
					[121] link Data Classes, center=(144,396), url='https://mineflow.ai/docs#data-classes'
				listitem
					[123] link Mineflow creates your predictive model, center=(144,443), url='https://mineflow.ai/docs#mineflow-creates-your-predictive-model'
				listitem
					[125] link Generating predictions, center=(144,489), url='https://mineflow.ai/docs#generating-predictions'
				listitem
					[127] link Video demo, center=(144,525), url='https://mineflow.ai/docs#video-demo'
				listitem
					[129] link Best practices, center=(144,561), url='https://mineflow.ai/docs#best-practices'
				listitem
					[131] link FAQ, center=(144,597), url='https://mineflow.ai/docs#faq'
				listitem
					[133] link How does Mineflow compare to existing solutions?, center=(151,644), url='https://mineflow.ai/docs#how-does-mineflow-compare-to-existing-solutions'
				listitem
					[135] link Why is Mineflow better than joint inversion models?, center=(151,702), url='https://mineflow.ai/docs#why-is-mineflow-better-than-joint-inversion-models'
				listitem
					[137] link Why are few assumptions good?, center=(151,759), url='https://mineflow.ai/docs#why-are-few-assumptions-good'
	main
		article
			heading Documentation
			paragraph
				StaticText Welcome to the Mineflow documentation!
			separator, orientation='horizontal'
			heading Overview
			paragraph
				StaticText Mineflow uses your exploration data to train a
				[147] link neural network, center=(677,350), url='https://en.wikipedia.org/wiki/Neural_network_(machine_learning)'
				StaticText to predict the shape and location of mineral deposits. The custom neural networks that Mineflow develops require minimal updates or feedback from the user. Use of the Mineflow platform does not require any background in machine learning on your part.
			separator, orientation='horizontal'
			heading Getting Started
			paragraph
				StaticText Start by uploading any exploration data from your sites.
			heading Data Uploads
			list
				listitem
					ListMarker 0.
					StaticText Go to the datasets section of the
					[154] link Portal, center=(589,648), url='https://mineflow.ai/portal'
					StaticText , press 'New Dataset,' and select the files you want to upload.
					image Images, url='https://mineflow.ai/datasets.png'
			heading What data should I upload?
			paragraph
				StaticText Great question. The short answer: upload any shapefile or Excel file related to the exploration site you're focusing on.
			paragraph
				StaticText A more detailed answer: It’s easy to understand why a shapefile containing outcrops of rocks in the area is valuable for training a predictive model. But what about a shapefile with polygons representing all the houses in the area where you’re drilling? Is that useful? Absolutely. Mineflow makes no assumptions about the data distribution and will supplement your uploads with additional data it finds online. So, a file identifying house locations can help Mineflow correlate data samples. For instance, Mineflow often uses satellite data to understand a site, and when combined with your house shapefile, Mineflow can learn to distinguish houses from significant geological features visible in aerial imagery.
			heading Non-drill data
			paragraph
				StaticText You can upload zip files (*.zip) that contain shapefiles or shapefiles themselves (*.sbx, *.dbf, *.shp, *.shx, *.xml, *.prj, *.sbn, *.cpg) for the non-drill data.
			heading Drill data
			paragraph
				StaticText For your drill data, upload Excel files (.xlsx). Ideally, your files should have columns that give the starting depth and the ending depth of each segment as well as some unique identifier for each drill hole segment (e.g. hole name).
			strong
			paragraph
				StaticText Note: If your dips and azimuths are split into a separate shapefile that's okay, Mineflow will handle parsing that out for you.
			heading Data Designations
			paragraph
				StaticText After you upload your data, you'll notice that each file is assigned a "designation."
				image Images, url='https://mineflow.ai/dsg.png'
			paragraph
				StaticText A designation is Mineflow's guess as to what type of data you uploaded. There are eight possible designations:
			list
				listitem
					ListMarker 0.
					StaticText Rock outcropping/expert labeled rock body: Polygons that represent rock bodies that are either outcroppings or generally agreed on rock structures underground
				listitem
					ListMarker 0.
					StaticText Non-rock visible object: Any object that is visible on the ground (e.g. building, river, road, tree) that has not been labeled as a rock
				listitem
					ListMarker 0.
					StaticText AOI: Any general area of interest, usually some sort of polygon
				listitem
					ListMarker 0.
					StaticText Aerial survey: All contour-line based data types. Any overhead surveys or imagery or LiDAR is going to fall into this group
				listitem
					ListMarker 0.
					StaticText Rock/soil/geochemical samples: Points where rocks or soil were sampled (e.g. descriptions of the rock sampled, PPMs of elements in the soil)
				listitem
					ListMarker 0.
					StaticText Drill collar locations and names: Data about the location of the collars
				listitem
					ListMarker 0.
					StaticText Drill hole traces: Files that contain the depth, dips and azimuths of your drill segments
				listitem
					ListMarker 0.
					StaticText Drill data: Drill assays or lithologies (or any other drill data)
			strong
			paragraph
				StaticText Note: If you think that there are data groupings missing here, please let us know! There may be a better way to explain/phrase the groupings.
			heading Updating designation
			paragraph
				StaticText You'll notice that you can change the designation for a file. This is useful for Mineflow when it starts to train the predictive model on your dataset.
			heading Data Classes
			paragraph
				StaticText After you upload your data, you'll notice that it is also assigned a "class."
				image Images, url='https://mineflow.ai/cls.png'
			paragraph
				StaticText A class is Mineflow's guess as to how many different types of data are represented in that file. The word class here comes from machine learning terminology where a
				link class, url='https://en.wikipedia.org/wiki/Multiclass_classification'
				StaticText is a type of label that a piece of data falls into. A file can be one of two things:
			list
				listitem
					ListMarker 0.
					StaticText Mono-class: Mono-class files are files that only contain one type of an object. A few examples of this: a shapefile that only contains granite rock outcroppings, a shapefile that contains lines that represent waterways in the area, a shapefile that contains the general structure (polygon) of a belt of pegmatites running through the area, a shapefile that is a set of points where you found rocks containing mica on the ground, a shapefile that has polygons that are all the houses in the area (yes, this data can be useful to upload!).
				listitem
					ListMarker 0.
					StaticText Multi-class: Multi-class files are files that contain multiple types of an object. A few examples of this: a shapefile that contains rock outcroppings that you have labeled as having different lithologies (e.g. granite, marble, etc.).
			heading Mineflow creates your predictive model
			paragraph
				StaticText After creating your dataset, the Mineflow team will "
				link train, url='https://en.wikipedia.org/wiki/Machine_learning'
				StaticText " a model on that dataset. That means that we create a statistical model with the objective of generalizing from its experience. We will train two models for you:
			list
				listitem
					ListMarker 0.
					StaticText Two-dimensional predictions: also known as prospectivity maps, these are 2D maps that represent the general shape of rock and mineral structures from a bird's eye view.
				listitem
					ListMarker 0.
					StaticText Three-dimensional predictions: also known as block models, these are 3D grids that represent the detailed shape and location of mineral structures underground.
			strong
			paragraph
				StaticText Note: We are only able to train a model to produce three-dimensional predictions if you have uploaded some drill data (otherwise the model doesn't know how to correlate data from the surface with data underground).
			paragraph
				StaticText The time it takes to train a predictive model depends on the size of the dataset, the size of the area and whether or not the model is 2D or 3D.
			list
				listitem
					ListMarker •
					StaticText Small datasets (less than 25 megabytes of data) for 2D will generally take 1 hour per 1 sq. mile of area. So, if I have a dataset that is a few megabytes and I've collected data over a 2 mile by 2 mile area, then the training of the 2D model will take about 4 hours.
				listitem
					ListMarker •
					StaticText Large datasets (greater than 25 megabytes of data) for 2D will generally take 4 hours per 1 sq. mile of area. So, if I have a dataset that is 100 megabytes in size and I've collected data over a 2 mile by 2 mile area, then the training of the 2D model will take around 16 hours.
				listitem
					ListMarker •
					StaticText 3D models generally take twice as long as 2D models, so for small datasets on a 2x2 mile area, training will take 8 hours and for large datasets on a 2x2 mile area, training will take around 32 hours.
			paragraph
				StaticText Once the Mineflow team has trained your custom model (see
				link training ETA, url='https://mineflow.ai/docs#model-training-eta'
				StaticText just below), you'll get an email from notifications@mineflow.ai, saying:
			generic
				StaticText Hi {name},

{model name} is done training. Click here to start making predictions with it!
			paragraph
				StaticText Here is an example of the email:
			paragraph
				image Images, url='https://mineflow.ai/email.png'
			paragraph
				StaticText When you return to the
				link Portal, url='https://mineflow.ai/portal'
				StaticText , your model will appear there, marked as successfully trained:
			paragraph
				image Images, url='https://mineflow.ai/newmody.png'
			heading Generating predictions
			paragraph
				StaticText Once we have created your model, the Mineflow team will create a project where you can see an image with location, shape and size of your model's predictions.
			paragraph
				StaticText Navigate to the
				link Portal, url='https://mineflow.ai/portal'
				StaticText to see your new project.
				image Images, url='https://mineflow.ai/projects.png'
			paragraph
				StaticText Clicking on your project will take you to a screen with a map on it that shows all of the data you uploaded:
				image Images, url='https://mineflow.ai/titleit.png'
			paragraph
				StaticText Then, click the predict tab and choose the model that we just trained:
				image Images, url='https://mineflow.ai/smod.png'
			paragraph
				StaticText Then, select the area you're interested in:
				image Images, url='https://mineflow.ai/sarea.png'
			paragraph
				StaticText Press "generate predictions":
				image Images, url='https://mineflow.ai/load.png'
			paragraph
				StaticText A few minutes (or hours depending on the size of the area) later, you'll get an email saying that your predictions are ready and when you return to the project, it will have generated both a 2D prospectivity map for that area as well as a 3D block model for that area.
			paragraph
				StaticText Here is an example of what the 2D prospectivity map might look like:
				image Images, url='https://mineflow.ai/pred.png'
			paragraph
				StaticText Here is an example of what a 3D block model might look like for a copper deposit. You can manipulate the 3D shape and adjust the visibility and transparency of each of the grades of copper.
			paragraph
				image Alt Text, url='https://mineflow.ai/copperspin.gif'
			paragraph
				StaticText The model can generate predictions
				strong
					StaticText for any mineral you want
				StaticText .
			paragraph
				StaticText For instance, here is the software generating a block model for a gold deposit:
			paragraph
				image Alt Text, url='https://mineflow.ai/goldspin.gif'
			heading Video demo
			paragraph
				StaticText A video showing the site in use can be found
				link here, url='https://mineflow.ai/demo'
				StaticText .
			heading Best practices
			list
				listitem
					ListMarker 0.
					StaticText Generally, the more data you upload, the easier it is for the model to learn to predict your deposit.
				listitem
					ListMarker 0.
					StaticText The more accurate your data is, the easier it is for the model to learn to predict your deposit. The more missing data and improperly labeled rocks you have in your dataset, the more likely it is that your model takes longer to train and yields less reliable results.
				listitem
					ListMarker 0.
					StaticText When choosing an area where you wish to generate predictions, the closer your location is to where your dataset is clustered, the better your predictions will be. "Close" in this context means within 5 miles. It is much harder for the model to make an inference about a location in the middle of the Pacific Ocean if your dataset was collected in South Africa!
				listitem
					ListMarker 0.
					StaticText One area where Mineflow can be particularly useful to a veteran geo is in remembering that single data point from that site you visited 15 years ago and inferring that the exploration site you're looking at now actually has a lot in common with it, despite being halfway across the globe.
			heading FAQ
			heading How does Mineflow compare to existing solutions?
			paragraph
				StaticText Traditional geological modeling software usually supports estimators like
				link Radial Basis Function, url='https://en.wikipedia.org/wiki/Radial_basis_function'
				StaticText (RBF),
				link Inverse Distance, url='https://en.wikipedia.org/wiki/Inverse_distance_weighting'
				StaticText estimator and techniques like wireframing and kriging. These can be used to take drill data and make guesses about what the shape of the deposit might look like.
			paragraph
				StaticText Here's how Mineflow differs:
			list
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Comprehensive data integration
						StaticText : Our model incorporates
						strong
							StaticText all available data points from the site
						StaticText , not just drilling information, ensuring a more complete analysis. RBF/Inverse distance/others cannot support the complex, multimodal data you have collected on site (like individual rock samples and geochemical samples). All data types are supported by Mineflow. Mineflow generates predictions based on all of the data you have collected as long as it is georeferenced.
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Cross-site learning
						StaticText : Mineflow allows you to leverage data from one site to inform exploration at another. If there is any similarity at all in the data collected at the two sites, Mineflow's neural net will find that correlation. RBF/Inverse distance/others are not able to learn how to make predictions based on multiple-sites worth of data.
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Advanced pattern recognition
						StaticText : Mineflow uses deep learning-based AI and sophisticated machine learning algorithms to understand complex, non-linear relationships between multiple samples even if they are not close to each other on a map. RBF/Inverse distance/others are just functions that find lines between points, so they are not able to do this.
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Identify missed deposits
						StaticText : Because RBF/Inverse distance/others just find lines between data points, if there is a second deposit that is close by that you haven't directly intersected with, RBF and Inverse Distance will never find it. Mineflow will likely find it.
			heading Why is Mineflow better than joint inversion models?
			list
				listitem
					ListMarker 0.
					strong
						StaticText Parametrization
					StaticText : In joint inversion models, you need to parametrize the shape of your deposit, which means that you need to make assumptions about the data and the way rock structures form. In the case where your assumptions about how to parametrize a deposit are correct, great! Your joint inversion model will
					emphasis
						StaticText probably
					StaticText take longer to train than a Mineflow model and may achieve results which are nearly as high in accuracy as Mineflow. In the case where your assumptions about how to parametrize a deposit are incorrect, your joint inversion model will be misleading and you will end up wasting exploration resources by drilling in suboptimal locations.
			paragraph
				image Images, url='https://mineflow.ai/assumptionsvsinference.png'
			list
				listitem
					ListMarker 0.
					strong
						StaticText Cross-site learning
					StaticText : Same as point 2 in the first question.
			heading Why are few assumptions good?
			paragraph
				StaticText Humans have developed an strong understanding of geology and with it, powerful abstractions for how rock structures tend to form and correlate with one another. This leads to new mineral discoveries and scientific achievements regularly.
			paragraph
				StaticText That said, when you consider
				emphasis
					StaticText any
				StaticText field from a computational perspective, trying to program human intuition into your model of how systems work is difficult and often
				link misguided, url='https://www.cs.utexas.edu/~eunsol/courses/data/bitter_lesson.pdf'
				StaticText . When we look at the history of computational models, we find that those that excel are
				strong
					StaticText big
				StaticText and
				strong
					StaticText generalizable
				StaticText --that is, they take in a massive amount of data and they have few assumptions hard-coded into how they handle that data. The field of mineral exploration is well-poised to take advantage of the explosion of publicly available data on the natural world. From academic datasets to satellite APIs and published 43-101s, the internet is full of data that we combine with the power of AI to better predict what is underground.
	region Notifications Alt+T
	alert, atomic
```
</details>



```
RootWebArea Mineflow, focused, url='https://mineflow.ai/docs#getting-started'
	navigation
		list
			listitem
				[62] link X Mineflow, center=(397,419), inner_text=Mineflow, url='https://mineflow.ai/'
```
<details><summary>Show more</summary>

```
					image X, url='https://mineflow.ai/mf512_transparent.png'
					paragraph
			list
				listitem
					[67] link About, center=(515,419), url='https://mineflow.ai/about'
				listitem
					[69] link Documentation, center=(601,419), url='https://mineflow.ai/docs'
				listitem
					[71] link Pricing, center=(690,419), url='https://mineflow.ai/pricing'
				listitem
					[73] link Team, center=(746,419), url='https://mineflow.ai/team'
				listitem
					[75] link Portal, center=(799,419), url='https://mineflow.ai/portal'
		list
			list
				listitem
					LabelText Switch to dark mode
						switch Switch to dark mode, checked='true'
				listitem
					[85] button Log in, center=(1423,419)
				[83] svg, center=(1361,419)
				listitem
					[87] button Sign Up, center=(1512,419)
	complementary
		navigation
			list
				listitem
					[105] link Overview, center=(144,484), url='https://mineflow.ai/docs#overview'
				listitem
					[107] link Getting Started, center=(144,534), focused, url='https://mineflow.ai/docs#getting-started'
				listitem
					[109] link Data Uploads, center=(144,570), url='https://mineflow.ai/docs#data-uploads'
				listitem
					[111] link What data should I upload?, center=(151,606), url='https://mineflow.ai/docs#what-data-should-i-upload'
				listitem
					[113] link Non-drill data, center=(151,642), url='https://mineflow.ai/docs#non-drill-data'
				listitem
					[115] link Drill data, center=(151,678), url='https://mineflow.ai/docs#drill-data'
				listitem
					[117] link Data Designations, center=(144,714), url='https://mineflow.ai/docs#data-designations'
				listitem
					[119] link Updating designation, center=(151,750), url='https://mineflow.ai/docs#updating-designation'
				listitem
					[121] link Data Classes, center=(144,786), url='https://mineflow.ai/docs#data-classes'
				listitem
					[123] link Mineflow creates your predictive model, center=(144,833), url='https://mineflow.ai/docs#mineflow-creates-your-predictive-model'
				listitem
					[125] link Generating predictions, center=(144,879), url='https://mineflow.ai/docs#generating-predictions'
				listitem
					[127] link Video demo, center=(144,915), url='https://mineflow.ai/docs#video-demo'
				listitem
					[129] link Best practices, center=(144,951), url='https://mineflow.ai/docs#best-practices'
				listitem
					[131] link FAQ, center=(144,987), url='https://mineflow.ai/docs#faq'
				listitem
					[133] link How does Mineflow compare to existing solutions?, center=(151,1034), url='https://mineflow.ai/docs#how-does-mineflow-compare-to-existing-solutions'
				listitem
					[135] link Why is Mineflow better than joint inversion models?, center=(151,1092), url='https://mineflow.ai/docs#why-is-mineflow-better-than-joint-inversion-models'
				listitem
					[137] link Why are few assumptions good?, center=(151,1149), url='https://mineflow.ai/docs#why-are-few-assumptions-good'
	main
		article
			heading Documentation
			paragraph
				StaticText Welcome to the Mineflow documentation!
			separator, orientation='horizontal'
			heading Overview
			paragraph
				StaticText Mineflow uses your exploration data to train a
				link neural network, url='https://en.wikipedia.org/wiki/Neural_network_(machine_learning)'
				StaticText to predict the shape and location of mineral deposits. The custom neural networks that Mineflow develops require minimal updates or feedback from the user. Use of the Mineflow platform does not require any background in machine learning on your part.
			separator, orientation='horizontal'
			heading Getting Started
			paragraph
				StaticText Start by uploading any exploration data from your sites.
			heading Data Uploads
			list
				listitem
					ListMarker 0.
					StaticText Go to the datasets section of the
					[154] link Portal, center=(589,648), url='https://mineflow.ai/portal'
					StaticText , press 'New Dataset,' and select the files you want to upload.
					image Images, url='https://mineflow.ai/datasets.png'
			heading What data should I upload?
			paragraph
				StaticText Great question. The short answer: upload any shapefile or Excel file related to the exploration site you're focusing on.
			paragraph
				StaticText A more detailed answer: It’s easy to understand why a shapefile containing outcrops of rocks in the area is valuable for training a predictive model. But what about a shapefile with polygons representing all the houses in the area where you’re drilling? Is that useful? Absolutely. Mineflow makes no assumptions about the data distribution and will supplement your uploads with additional data it finds online. So, a file identifying house locations can help Mineflow correlate data samples. For instance, Mineflow often uses satellite data to understand a site, and when combined with your house shapefile, Mineflow can learn to distinguish houses from significant geological features visible in aerial imagery.
			heading Non-drill data
			paragraph
				StaticText You can upload zip files (*.zip) that contain shapefiles or shapefiles themselves (*.sbx, *.dbf, *.shp, *.shx, *.xml, *.prj, *.sbn, *.cpg) for the non-drill data.
			heading Drill data
			paragraph
				StaticText For your drill data, upload Excel files (.xlsx). Ideally, your files should have columns that give the starting depth and the ending depth of each segment as well as some unique identifier for each drill hole segment (e.g. hole name).
			strong
			paragraph
				StaticText Note: If your dips and azimuths are split into a separate shapefile that's okay, Mineflow will handle parsing that out for you.
			heading Data Designations
			paragraph
				StaticText After you upload your data, you'll notice that each file is assigned a "designation."
				image Images, url='https://mineflow.ai/dsg.png'
			paragraph
				StaticText A designation is Mineflow's guess as to what type of data you uploaded. There are eight possible designations:
			list
				listitem
					ListMarker 0.
					StaticText Rock outcropping/expert labeled rock body: Polygons that represent rock bodies that are either outcroppings or generally agreed on rock structures underground
				listitem
					ListMarker 0.
					StaticText Non-rock visible object: Any object that is visible on the ground (e.g. building, river, road, tree) that has not been labeled as a rock
				listitem
					ListMarker 0.
					StaticText AOI: Any general area of interest, usually some sort of polygon
				listitem
					ListMarker 0.
					StaticText Aerial survey: All contour-line based data types. Any overhead surveys or imagery or LiDAR is going to fall into this group
				listitem
					ListMarker 0.
					StaticText Rock/soil/geochemical samples: Points where rocks or soil were sampled (e.g. descriptions of the rock sampled, PPMs of elements in the soil)
				listitem
					ListMarker 0.
					StaticText Drill collar locations and names: Data about the location of the collars
				listitem
					ListMarker 0.
					StaticText Drill hole traces: Files that contain the depth, dips and azimuths of your drill segments
				listitem
					ListMarker 0.
					StaticText Drill data: Drill assays or lithologies (or any other drill data)
			strong
			paragraph
				StaticText Note: If you think that there are data groupings missing here, please let us know! There may be a better way to explain/phrase the groupings.
			heading Updating designation
			paragraph
				StaticText You'll notice that you can change the designation for a file. This is useful for Mineflow when it starts to train the predictive model on your dataset.
			heading Data Classes
			paragraph
				StaticText After you upload your data, you'll notice that it is also assigned a "class."
				image Images, url='https://mineflow.ai/cls.png'
			paragraph
				StaticText A class is Mineflow's guess as to how many different types of data are represented in that file. The word class here comes from machine learning terminology where a
				link class, url='https://en.wikipedia.org/wiki/Multiclass_classification'
				StaticText is a type of label that a piece of data falls into. A file can be one of two things:
			list
				listitem
					ListMarker 0.
					StaticText Mono-class: Mono-class files are files that only contain one type of an object. A few examples of this: a shapefile that only contains granite rock outcroppings, a shapefile that contains lines that represent waterways in the area, a shapefile that contains the general structure (polygon) of a belt of pegmatites running through the area, a shapefile that is a set of points where you found rocks containing mica on the ground, a shapefile that has polygons that are all the houses in the area (yes, this data can be useful to upload!).
				listitem
					ListMarker 0.
					StaticText Multi-class: Multi-class files are files that contain multiple types of an object. A few examples of this: a shapefile that contains rock outcroppings that you have labeled as having different lithologies (e.g. granite, marble, etc.).
			heading Mineflow creates your predictive model
			paragraph
				StaticText After creating your dataset, the Mineflow team will "
				link train, url='https://en.wikipedia.org/wiki/Machine_learning'
				StaticText " a model on that dataset. That means that we create a statistical model with the objective of generalizing from its experience. We will train two models for you:
			list
				listitem
					ListMarker 0.
					StaticText Two-dimensional predictions: also known as prospectivity maps, these are 2D maps that represent the general shape of rock and mineral structures from a bird's eye view.
				listitem
					ListMarker 0.
					StaticText Three-dimensional predictions: also known as block models, these are 3D grids that represent the detailed shape and location of mineral structures underground.
			strong
			paragraph
				StaticText Note: We are only able to train a model to produce three-dimensional predictions if you have uploaded some drill data (otherwise the model doesn't know how to correlate data from the surface with data underground).
			paragraph
				StaticText The time it takes to train a predictive model depends on the size of the dataset, the size of the area and whether or not the model is 2D or 3D.
			list
				listitem
					ListMarker •
					StaticText Small datasets (less than 25 megabytes of data) for 2D will generally take 1 hour per 1 sq. mile of area. So, if I have a dataset that is a few megabytes and I've collected data over a 2 mile by 2 mile area, then the training of the 2D model will take about 4 hours.
				listitem
					ListMarker •
					StaticText Large datasets (greater than 25 megabytes of data) for 2D will generally take 4 hours per 1 sq. mile of area. So, if I have a dataset that is 100 megabytes in size and I've collected data over a 2 mile by 2 mile area, then the training of the 2D model will take around 16 hours.
				listitem
					ListMarker •
					StaticText 3D models generally take twice as long as 2D models, so for small datasets on a 2x2 mile area, training will take 8 hours and for large datasets on a 2x2 mile area, training will take around 32 hours.
			paragraph
				StaticText Once the Mineflow team has trained your custom model (see
				link training ETA, url='https://mineflow.ai/docs#model-training-eta'
				StaticText just below), you'll get an email from notifications@mineflow.ai, saying:
			generic
				StaticText Hi {name},

{model name} is done training. Click here to start making predictions with it!
			paragraph
				StaticText Here is an example of the email:
			paragraph
				image Images, url='https://mineflow.ai/email.png'
			paragraph
				StaticText When you return to the
				link Portal, url='https://mineflow.ai/portal'
				StaticText , your model will appear there, marked as successfully trained:
			paragraph
				image Images, url='https://mineflow.ai/newmody.png'
			heading Generating predictions
			paragraph
				StaticText Once we have created your model, the Mineflow team will create a project where you can see an image with location, shape and size of your model's predictions.
			paragraph
				StaticText Navigate to the
				link Portal, url='https://mineflow.ai/portal'
				StaticText to see your new project.
				image Images, url='https://mineflow.ai/projects.png'
			paragraph
				StaticText Clicking on your project will take you to a screen with a map on it that shows all of the data you uploaded:
				image Images, url='https://mineflow.ai/titleit.png'
			paragraph
				StaticText Then, click the predict tab and choose the model that we just trained:
				image Images, url='https://mineflow.ai/smod.png'
			paragraph
				StaticText Then, select the area you're interested in:
				image Images, url='https://mineflow.ai/sarea.png'
			paragraph
				StaticText Press "generate predictions":
				image Images, url='https://mineflow.ai/load.png'
			paragraph
				StaticText A few minutes (or hours depending on the size of the area) later, you'll get an email saying that your predictions are ready and when you return to the project, it will have generated both a 2D prospectivity map for that area as well as a 3D block model for that area.
			paragraph
				StaticText Here is an example of what the 2D prospectivity map might look like:
				image Images, url='https://mineflow.ai/pred.png'
			paragraph
				StaticText Here is an example of what a 3D block model might look like for a copper deposit. You can manipulate the 3D shape and adjust the visibility and transparency of each of the grades of copper.
			paragraph
				image Alt Text, url='https://mineflow.ai/copperspin.gif'
			paragraph
				StaticText The model can generate predictions
				strong
					StaticText for any mineral you want
				StaticText .
			paragraph
				StaticText For instance, here is the software generating a block model for a gold deposit:
			paragraph
				image Alt Text, url='https://mineflow.ai/goldspin.gif'
			heading Video demo
			paragraph
				StaticText A video showing the site in use can be found
				link here, url='https://mineflow.ai/demo'
				StaticText .
			heading Best practices
			list
				listitem
					ListMarker 0.
					StaticText Generally, the more data you upload, the easier it is for the model to learn to predict your deposit.
				listitem
					ListMarker 0.
					StaticText The more accurate your data is, the easier it is for the model to learn to predict your deposit. The more missing data and improperly labeled rocks you have in your dataset, the more likely it is that your model takes longer to train and yields less reliable results.
				listitem
					ListMarker 0.
					StaticText When choosing an area where you wish to generate predictions, the closer your location is to where your dataset is clustered, the better your predictions will be. "Close" in this context means within 5 miles. It is much harder for the model to make an inference about a location in the middle of the Pacific Ocean if your dataset was collected in South Africa!
				listitem
					ListMarker 0.
					StaticText One area where Mineflow can be particularly useful to a veteran geo is in remembering that single data point from that site you visited 15 years ago and inferring that the exploration site you're looking at now actually has a lot in common with it, despite being halfway across the globe.
			heading FAQ
			heading How does Mineflow compare to existing solutions?
			paragraph
				StaticText Traditional geological modeling software usually supports estimators like
				link Radial Basis Function, url='https://en.wikipedia.org/wiki/Radial_basis_function'
				StaticText (RBF),
				link Inverse Distance, url='https://en.wikipedia.org/wiki/Inverse_distance_weighting'
				StaticText estimator and techniques like wireframing and kriging. These can be used to take drill data and make guesses about what the shape of the deposit might look like.
			paragraph
				StaticText Here's how Mineflow differs:
			list
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Comprehensive data integration
						StaticText : Our model incorporates
						strong
							StaticText all available data points from the site
						StaticText , not just drilling information, ensuring a more complete analysis. RBF/Inverse distance/others cannot support the complex, multimodal data you have collected on site (like individual rock samples and geochemical samples). All data types are supported by Mineflow. Mineflow generates predictions based on all of the data you have collected as long as it is georeferenced.
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Cross-site learning
						StaticText : Mineflow allows you to leverage data from one site to inform exploration at another. If there is any similarity at all in the data collected at the two sites, Mineflow's neural net will find that correlation. RBF/Inverse distance/others are not able to learn how to make predictions based on multiple-sites worth of data.
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Advanced pattern recognition
						StaticText : Mineflow uses deep learning-based AI and sophisticated machine learning algorithms to understand complex, non-linear relationships between multiple samples even if they are not close to each other on a map. RBF/Inverse distance/others are just functions that find lines between points, so they are not able to do this.
				listitem
					ListMarker 0.
					paragraph
						strong
							StaticText Identify missed deposits
						StaticText : Because RBF/Inverse distance/others just find lines between data points, if there is a second deposit that is close by that you haven't directly intersected with, RBF and Inverse Distance will never find it. Mineflow will likely find it.
			heading Why is Mineflow better than joint inversion models?
			list
				listitem
					ListMarker 0.
					strong
						StaticText Parametrization
					StaticText : In joint inversion models, you need to parametrize the shape of your deposit, which means that you need to make assumptions about the data and the way rock structures form. In the case where your assumptions about how to parametrize a deposit are correct, great! Your joint inversion model will
					emphasis
						StaticText probably
					StaticText take longer to train than a Mineflow model and may achieve results which are nearly as high in accuracy as Mineflow. In the case where your assumptions about how to parametrize a deposit are incorrect, your joint inversion model will be misleading and you will end up wasting exploration resources by drilling in suboptimal locations.
			paragraph
				image Images, url='https://mineflow.ai/assumptionsvsinference.png'
			list
				listitem
					ListMarker 0.
					strong
						StaticText Cross-site learning
					StaticText : Same as point 2 in the first question.
			heading Why are few assumptions good?
			paragraph
				StaticText Humans have developed an strong understanding of geology and with it, powerful abstractions for how rock structures tend to form and correlate with one another. This leads to new mineral discoveries and scientific achievements regularly.
			paragraph
				StaticText That said, when you consider
				emphasis
					StaticText any
				StaticText field from a computational perspective, trying to program human intuition into your model of how systems work is difficult and often
				link misguided, url='https://www.cs.utexas.edu/~eunsol/courses/data/bitter_lesson.pdf'
				StaticText . When we look at the history of computational models, we find that those that excel are
				strong
					StaticText big
				StaticText and
				strong
					StaticText generalizable
				StaticText --that is, they take in a massive amount of data and they have few assumptions hard-coded into how they handle that data. The field of mineral exploration is well-poised to take advantage of the explosion of publicly available data on the natural world. From academic datasets to satellite APIs and published 43-101s, the internet is full of data that we combine with the power of AI to better predict what is underground.
	region Notifications Alt+T
	alert, atomic
```
</details>

**Reasoning for action:** By clicking on the Getting Started link, I will be presented with a dedicated guide that outlines the basic steps required to start using Mineflow. This action is crucial as it aligns with the user's goal of learning how to upload their exploration data and effectively use the platform. Once on this page, I can locate detailed instructions that meet the user's needs.

**Action:** click(107) # Click on the Getting Started link to learn how to begin using Mineflow.

**Change Description:** The browser navigated to the 'Getting Started' section of the Mineflow documentation, updating the URL to 'https://mineflow.ai/docs#getting-started' and changing the focus from the main documentation page to the specific content related to getting started with uploading exploration data.

**Screenshot before:****Screenshot after:**---


# Task

**Newsletter Subscription Feature**

As a prospective Mentorcam user,
I subscribe to the newsletter,
so that I can receive updates and a promotional code for my first session.

**Success definition:** Given I am on the Mentorcam homepage
When I submit my email address for the newsletter
Then I should see a confirmation message thanking me and indicating that a promo code has been sent to my email, along with a 'Browse mentors' button.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://mentor.cam/

https://mentor.cam/

**Content (before/after):** 

```
RootWebArea Expert Startup Mentors | Unlock Your Potential | Mentorcam, focused, url='https://mentor.cam/'
	banner
		navigation
			link, url='https://mentor.cam/'
				image
```
<details><summary>Show more</summary>

```
			list
				listitem
					StaticText Browse
					image Find a Mentor, url='https://mentor.cam/_next/static/media/arrow-black-small-down.d77f3ecd.svg'
					list
						listitem
							list
								heading Expertise
								heading Industry
								link New Mentors, url='https://mentor.cam/search?categoryIds=new-mentor'
									heading New Mentors
				listitem
					image
					searchbox What advice are you looking for today?
			list
				listitem
					link For mentors, url='https://mentor.cam/for-mentors'
				listitem
					StaticText More
					image Find a Mentor, url='https://mentor.cam/_next/static/media/arrow-black-small-down.d77f3ecd.svg'
					list
						listitem
							link Articles, url='https://mentor.cam/articles'
						listitem
							link Company, url='https://mentor.cam/company'
						listitem
							link Careers, url='https://www.ycombinator.com/companies/mentorcam/jobs'
						listitem
							link Support, url='https://mentor.cam/support'
				listitem
				image Save $100 off on your first Mentorcam session, url='https://res.cloudinary.com/mentorcam/image/upload/ar_291:320,c_fill,f_auto,g_auto:face,q_100,w_320/v1/website/newsletter/newsletter_aol7lw.jpg'
				heading Get $50 off
				paragraph
					StaticText Sign up for our newsletter and get $50
					StaticText off your first Mentorcam session.
				[152] textbox Email, center=(1106,561), contenteditable=True
				LabelText
					StaticText Email
				[155] button Submit, center=(1106,626), type=submit
				[156] paragraph, center=(1106,670), inner_text=No thanks
					StaticText No thanks
				listitem
					link Log in, url='https://mentor.cam/login'
				listitem
					link Sign up, url='https://mentor.cam/sign-up'
						button Sign up
	image
	heading Get advice from the world’s BEST mentors
	heading Book 1:1 calls with founders andleaders of the world’s best startups and brands.
	link Find a mentor, url='https://mentor.cam/search'
		button Find a mentor
	image Alexandra Zatarain, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/eo0NsIuHpXPKXsgcrNzMfRNbO7r1/images/-NFzvoPKAGSVDLE-4iqC.jpg'
	heading Alexandra Zatarain
	heading VP
		paragraph
	separator, orientation='horizontal'
	image Eight Sleep, url='https://res.cloudinary.com/mentorcam/image/upload/v1695102592/logos/oKcV58tiB5zXjewMIBJ9/files/-NefzCjW1J1wMJUB6610.svg.svg'
	image Chris Yeh, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/SDeGJdJ3hGUCw5EeNleQO6406Pw2/images/-MYu9atjX3CshcXuyTnP.jpg'
	heading Chris Yeh
	heading Partner
		paragraph
	separator, orientation='horizontal'
	image Blitzscaling Ventures, url='https://res.cloudinary.com/mentorcam/image/upload/v1695105994/logos/8SXFYBsn0L1r24Yfdl6Y/files/-NegBBLYOLgThNBrlfwU.svg.svg'
	image T Zhu, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/OLr4yMcDhoXzqjYuXLqeisBSlqX2/images/wEfjBsp1kJqi2ZOEMBfK.jpg'
	heading T Zhu
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Tellus, url='https://res.cloudinary.com/mentorcam/image/upload/v1681308442/logos/Hf7vDQ4zimBCEsxHonla/files/-NSpmhTNYPB9QbDvbqd8.svg.svg'
	image Michael Litt, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/071SzayHiobckWBc7BIEtlL24aA2/images/-O8c1SLrAj05ZUegOfNl.jpeg'
	heading Michael Litt
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Vidyard, url='https://res.cloudinary.com/mentorcam/image/upload/v1698793424/logos/WctOqFUxSxbZurYaLGy4/files/-Ni6yY-nECTlu-3rYPrw.svg.svg'
	image Roy Chung, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/axVGzXQhz2Sgbu6EejHThHIsCVp2/images/-Ne5gSUf_T8LaaVk83YK.jpg'
	heading Roy Chung
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Apollo, url='https://res.cloudinary.com/mentorcam/image/upload/v1694120864/logos/4MYe5wGtr3yrRRiUMYV4/files/-NdlTDKkPcTw-h9N2xl5.svg.svg'
	image Jason Feifer, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/mVPEdDDBSNe8s6m0uFFj0Ej7Cvo2/images/-MbIkZ8WOGC2OWRJkANp.jpg'
	heading Jason Feifer
	heading Editor
		paragraph
	separator, orientation='horizontal'
	image Entrepreneur, url='https://res.cloudinary.com/mentorcam/image/upload/v1681302612/logos/cceXBeGD3RfQzr8MVfeC/files/-NSpRTETlzkIWJ5kheqK.svg.svg'
	image Robin Daniels, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/xn9SoVfaBJc3ZqorFKu0UkkD4ps2/images/-NSp1-dkd4i12TETOsyg.jpg'
	heading Robin Daniels
	heading CMO
		paragraph
	separator, orientation='horizontal'
	image WeWork, url='https://res.cloudinary.com/mentorcam/image/upload/v1681943871/logos/tD0U2mfVCq2ajNdFba7e/files/-NTQedqTkHQHqJYuIxu_.svg.svg'
	separator, orientation='horizontal'
	paragraph
		StaticText TALK TO EXPERTS FROM
		StaticText THE WORLD’S TOP COMPANIES
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	separator, orientation='horizontal'
	article
		heading Access to an elite network
		image
		paragraph
			StaticText Mentorcam’s network of elite founders and business professionals are available to you on-demand.
		image
		paragraph
			StaticText Whether you work with a specific expert or seek input from multiple advisors, your network just got instantly stronger.
		image
		paragraph
			StaticText All Mentorcam experts are carefully vetted and have proven track records as highly successful builders and operators.
		image Access to an elite network, url='https://res.cloudinary.com/mentorcam/image/upload/ar_528:436,c_lfill,f_auto,g_face:center,q_100,w_600/v1/website/home/Mentor_Network_Image_fm0ggw.png'
	separator, orientation='horizontal'
	article
		heading Talk face to face on 1:1 video calls
		image
		paragraph
			StaticText Talk in real time on 1:1 video calls and get the advice and direction you need, when you need it.
		image
		paragraph
			StaticText Share your challenges in a safe and confidential environment and carve out a path to success.
		image
		paragraph
			StaticText Whether you’re looking for help fundraising, acquiring users, or developing tactical sales skills, an expert is here to help.
		image Talk face to face on 1:1 video calls, url='https://res.cloudinary.com/mentorcam/image/upload/ar_699:470,c_lfill,f_auto,g_auto:face,q_100,w_800/v1/website/home/Face_to_Face_Video_Image_e4sms1.png'
	separator, orientation='horizontal'
	article
		heading Message your mentor
		image
		paragraph
			StaticText Send messages before and after your calls. Access your messages at any time from your desktop or mobile device.
		image
		paragraph
			StaticText Share an agenda with topics to discuss or upload files for review. Set milestones and discuss progress between calls.
		image
		paragraph
			StaticText Mentorcam keeps everything on one platform so your conversation is always safe and secure.
		image Message your mentor, url='https://res.cloudinary.com/mentorcam/image/upload/ar_578:443,c_lfill,f_auto,g_face:center,q_100,w_650/v1/website/home/Message_Mentor_Image_avggpy.png'
	article
		image Founder, Angelos Georgakis Executive Coaching, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/c5CnDzjqU5TCeEo8iQSB/images/-N_4ugwsXvM0wKruBesN.jpg'
		heading “How have you not signed up yet?”
		heading Angelos Georgakis
		heading Founder, Angelos Georgakis Executive Coaching
		link Read story, url='https://mentor.cam/articles/angelos-georgakis'
			button Read story
	article
		image Founder, Creativo Platform, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/XhL6fku7GH40Um42LKCm/images/-N_4tXecOSjuPFlz5Lk1.jpg'
		heading “Every mentor I've spoken to has helped us go further a lot faster.”
		heading Clint Rogers
		heading Founder, Creativo Platform
		link Read story, url='https://mentor.cam/articles/clint-rogers'
			button Read story
	article
		image Founder, VRRB Labs, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/U0vFCAYMxpzVkMfSFGdl/images/-N_4tmaAmyXGalw1yiGE.jpg'
		heading “We ended up raising $1.42 million for our company.”
		heading Andrew Smith
		heading Founder, VRRB Labs
		link Read story, url='https://mentor.cam/articles/andrew-smith'
			button Read story
	article
		image Co-founder, Motiv, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/3yTcftWWFg9VwGoOyG9B/images/-N_4sOF3LqZGhpd7zuFe.jpg'
		heading “I’d give Mentorcam five out of five stars. I've been very impressed.”
		heading Mason Fuerst
		heading Co-founder, Motiv
		link Read story, url='https://mentor.cam/articles/mason-fuerst'
			button Read story
	article
		image Founder, Felvin, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/sRva2AR8AuThaefvF9vb/images/-N_4tzduE1_GBRUBL2YS.jpg'
		heading “I would not have raised $300K if it wasn’t for my mentor.”
		heading Harsh Gupta
		heading Founder, Felvin
		link Read story, url='https://mentor.cam/articles/raise-money-startup-or-business'
			button Read story
	article
		image Founder, InvestLink Social, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/74KNbacbZjksQC1ZnWg9/images/-N_4u7Jqk7FEtupC91fa.jpg'
		heading “We've been able to hyper speed our pre-seed round.”
		heading Christian Durfee
		heading Founder, InvestLink Social
		link Read story, url='https://mentor.cam/articles/christian-durfee'
			button Read story
	article
		image Co-founder, Happyrobot.ai, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/tUjHzfp6MmB1O04iv9eg/images/-N_4uFd3h7dbjiFGdhjj.jpg'
		heading “My mentors helped me deep dive into the mind of the customer.”
		heading Pablo Palafox
		heading Co-founder, Happyrobot.ai
		link Read story, url='https://mentor.cam/articles/pablo-palafox'
			button Read story
	article
		image Co-founder, Empower Sleep, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/BIxzVebcLYJvQ4xVPNG9/images/-N_4uYlZhKCSDTuC5LtM.jpg'
		heading “I'd walk out of mentorship sessions feeling much better about building.”
		heading Sagar Chopra
		heading Co-founder, Empower Sleep
		link Read story, url='https://mentor.cam/articles/sagar-chopra'
			button Read story
	heading Book a mentor for a 1:1 live call and get custom advice tailored to you from the world’s best startup founders and business leaders
	button B2B Software
	button Consumer Software
	button Artificial Intelligence
	button Branding
	button E-commerce & CPG
	button Fundraising
	button Venture Capital
	link Michael Litt Product & Sales Advice Michael Litt Co-Founder & CEO - Vidyard GTM & Generative AI Expert Vidyard, url='https://mentor.cam/michaellitt'
		image Michael Litt, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/071SzayHiobckWBc7BIEtlL24aA2/images/-O8c1SLrAj05ZUegOfNl.jpeg'
		heading Product & Sales Advice
		heading Michael Litt
		heading Co-Founder & CEO - Vidyard GTM & Generative AI Expert
		separator, orientation='horizontal'
		image Vidyard, url='https://res.cloudinary.com/mentorcam/image/upload/v1698793424/logos/WctOqFUxSxbZurYaLGy4/files/-Ni6yY-nECTlu-3rYPrw.svg.svg'
	link Derek Edwards Gen AI Engineering Advice Derek Edwards VP AI Technology - Elevance Health Gen AI Engineering Expert Elevance, url='https://mentor.cam/derekedwards'
		image Derek Edwards, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/kgWqasE0XdWmg7RhkMDWEAtj2Ih1/images/-NiPQIDS0TgXGqeIXS9C.jpeg'
		heading Gen AI Engineering Advice
		heading Derek Edwards
		heading VP AI Technology - Elevance Health Gen AI Engineering Expert
		separator, orientation='horizontal'
		image Elevance, url='https://res.cloudinary.com/mentorcam/image/upload/v1692027482/logos/Yj7EjKwuRurp0fPe2fAY/files/-NbogacZ46n3F997ph-2.svg.svg'
	link Josh Auffret Marketing Expert Josh Auffret Head of UX Programs & Operations - Google Product Marketing Expert Google, url='https://mentor.cam/joshauffret'
		image Josh Auffret, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/rptSDb1KAxdayDtkShO0CZSB9Bq2/images/-NlVESOg3LcDuy_TIkXU.jpg'
		heading Marketing Expert
		heading Josh Auffret
		heading Head of UX Programs & Operations - Google Product Marketing Expert
		separator, orientation='horizontal'
		image Google, url='https://res.cloudinary.com/mentorcam/image/upload/v1682025135/logos/7C5Eg3yRWHaAKixmlMXB/files/-NTVVeLZdlV-lyhezkMz.svg.svg'
	link Show more mentors, url='https://mentor.cam/categories/b2b-software'
	heading Sign up and access an elite network of world-class experts
	paragraph
		StaticText Book 1:1 calls and solve your most pressing challenges with the help of elite experts and industry leaders.
	link Create an account, url='https://mentor.cam/sign-up'
		button Create an account
	contentinfo
		list
			listitem
				list
					StaticText Expertise
					separator, orientation='horizontal'
					list
						listitem
							link B2B Sales, url='https://mentor.cam/categories/b2b-sales'
						listitem
							link B2C Sales, url='https://mentor.cam/categories/b2c-sales'
						listitem
							link Bootstrapping, url='https://mentor.cam/categories/bootstrapping'
						listitem
							link Branding, url='https://mentor.cam/categories/branding'
						listitem
							link Financial Planning, url='https://mentor.cam/categories/financial-planning'
						listitem
							link Fundraising, url='https://mentor.cam/categories/fundraising'
						listitem
							link Growth Marketing, url='https://mentor.cam/categories/growth-marketing'
						listitem
							link Manufacturing, url='https://mentor.cam/categories/manufacturing'
						listitem
							link People & Hiring, url='https://mentor.cam/categories/people-and-hiring'
						listitem
							link Product & Engineering, url='https://mentor.cam/categories/product-and-engineering'
						listitem
							link Product Marketing, url='https://mentor.cam/categories/product-marketing'
						listitem
							link Public Relations, url='https://mentor.cam/categories/public-relations'
						listitem
							link SEM & SEO, url='https://mentor.cam/categories/sem-seo'
						listitem
							link Social Media, url='https://mentor.cam/categories/social-media-marketing'
						listitem
							link Strategy & Operations, url='https://mentor.cam/categories/strategy-and-operations'
					StaticText Industry
					separator, orientation='horizontal'
					list
						listitem
							link Artificial Intelligence, url='https://mentor.cam/categories/artificial-intelligence'
						listitem
							link B2B Services, url='https://mentor.cam/categories/b2b-services'
						listitem
							link B2B Software, url='https://mentor.cam/categories/b2b-software'
						listitem
							link Consumer Products, url='https://mentor.cam/categories/consumer-hardware'
						listitem
							link Consumer Software, url='https://mentor.cam/categories/consumer-software'
						listitem
							link E-commerce & CPG, url='https://mentor.cam/categories/e-commerce-and-cpg'
						listitem
							link Education, url='https://mentor.cam/categories/education'
						listitem
							link Fashion & Apparel, url='https://mentor.cam/categories/fashion'
						listitem
							link Fintech, url='https://mentor.cam/categories/fintech'
						listitem
							link Food & Beverage, url='https://mentor.cam/categories/food-beverage'
						listitem
							link Gaming, url='https://mentor.cam/categories/gaming'
						listitem
							link Healthcare, url='https://mentor.cam/categories/healthcare'
						listitem
							link Insurance, url='https://mentor.cam/categories/insurance'
						listitem
							link Media & Entertainment, url='https://mentor.cam/categories/media-and-entertainment'
						listitem
							link Real Estate, url='https://mentor.cam/categories/real-estate'
						listitem
							link Venture Capital, url='https://mentor.cam/categories/venture-capital'
			listitem
				list
					listitem
						StaticText Mentorcam
						list
							separator, orientation='horizontal'
							listitem
								link Articles, url='https://mentor.cam/articles'
							listitem
								link For mentors, url='https://mentor.cam/for-mentors'
							listitem
								link Company, url='https://mentor.cam/company'
							listitem
								link Careers, url='https://www.ycombinator.com/companies/mentorcam/jobs'
							listitem
								link Support, url='https://mentor.cam/support'
		link, url='https://mentor.cam/for-business'
			image
		StaticText 1:1 advice from otherwise
		StaticText inaccessible mentors
		link Mentorcam Youtube, url='https://www.youtube.com/@mentorcam'
			image
		link Mentorcam LinkedIn, url='https://www.linkedin.com/company/mentorcam'
			image
		link Mentorcam Instagram, url='https://www.instagram.com/mentor.cam/'
			image
		link Mentorcam Facebook, url='https://www.facebook.com/mentorcam'
			image
		paragraph
			StaticText ©
			StaticText 2025
			StaticText Mentorcam, Inc.
			StaticText —
			StaticText 2450 Colorado Ave. Suite 100E, Santa Monica, CA 90404
		list
			listitem
				link Terms of Service, url='https://mentor.cam/terms'
			listitem
				link Mentor Terms, url='https://mentor.cam/mentor-terms'
			listitem
				link Privacy Policy, url='https://mentor.cam/privacy'
			listitem
				link Cookie Policy, url='https://mentor.cam/cookie-policy'
	alert, atomic
```
</details>



```
RootWebArea Expert Startup Mentors | Unlock Your Potential | Mentorcam, focused, url='https://mentor.cam/'
	banner
		navigation
			link, url='https://mentor.cam/'
				image
```
<details><summary>Show more</summary>

```
			list
				listitem
					StaticText Browse
					image Find a Mentor, url='https://mentor.cam/_next/static/media/arrow-black-small-down.d77f3ecd.svg'
					list
						listitem
							list
								heading Expertise
								heading Industry
								link New Mentors, url='https://mentor.cam/search?categoryIds=new-mentor'
									heading New Mentors
				listitem
					image
					searchbox What advice are you looking for today?
			list
				listitem
					link For mentors, url='https://mentor.cam/for-mentors'
				listitem
					StaticText More
					image Find a Mentor, url='https://mentor.cam/_next/static/media/arrow-black-small-down.d77f3ecd.svg'
					list
						listitem
							link Articles, url='https://mentor.cam/articles'
						listitem
							link Company, url='https://mentor.cam/company'
						listitem
							link Careers, url='https://www.ycombinator.com/companies/mentorcam/jobs'
						listitem
							link Support, url='https://mentor.cam/support'
				listitem
				image Save $100 off on your first Mentorcam session, url='https://res.cloudinary.com/mentorcam/image/upload/ar_291:320,c_fill,f_auto,g_auto:face,q_100,w_320/v1/website/newsletter/newsletter_aol7lw.jpg'
				heading Get $50 off
				paragraph
					StaticText Sign up for our newsletter and get $50
					StaticText off your first Mentorcam session.
				[152] textbox Email, center=(1106,560), contenteditable=True
				LabelText
					StaticText Email
				paragraph
					StaticText Invalid email address
				[155] button Submit, center=(1106,635), focused, type=submit
				[156] paragraph, center=(1106,678), inner_text=No thanks
					StaticText No thanks
				listitem
					link Log in, url='https://mentor.cam/login'
				listitem
					link Sign up, url='https://mentor.cam/sign-up'
						button Sign up
	image
	heading Get advice from the world’s BEST mentors
	heading Book 1:1 calls with founders andleaders of the world’s best startups and brands.
	link Find a mentor, url='https://mentor.cam/search'
		button Find a mentor
	image Alexandra Zatarain, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/eo0NsIuHpXPKXsgcrNzMfRNbO7r1/images/-NFzvoPKAGSVDLE-4iqC.jpg'
	heading Alexandra Zatarain
	heading VP
		paragraph
	separator, orientation='horizontal'
	image Eight Sleep, url='https://res.cloudinary.com/mentorcam/image/upload/v1695102592/logos/oKcV58tiB5zXjewMIBJ9/files/-NefzCjW1J1wMJUB6610.svg.svg'
	image Chris Yeh, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/SDeGJdJ3hGUCw5EeNleQO6406Pw2/images/-MYu9atjX3CshcXuyTnP.jpg'
	heading Chris Yeh
	heading Partner
		paragraph
	separator, orientation='horizontal'
	image Blitzscaling Ventures, url='https://res.cloudinary.com/mentorcam/image/upload/v1695105994/logos/8SXFYBsn0L1r24Yfdl6Y/files/-NegBBLYOLgThNBrlfwU.svg.svg'
	image T Zhu, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/OLr4yMcDhoXzqjYuXLqeisBSlqX2/images/wEfjBsp1kJqi2ZOEMBfK.jpg'
	heading T Zhu
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Tellus, url='https://res.cloudinary.com/mentorcam/image/upload/v1681308442/logos/Hf7vDQ4zimBCEsxHonla/files/-NSpmhTNYPB9QbDvbqd8.svg.svg'
	image Michael Litt, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/071SzayHiobckWBc7BIEtlL24aA2/images/-O8c1SLrAj05ZUegOfNl.jpeg'
	heading Michael Litt
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Vidyard, url='https://res.cloudinary.com/mentorcam/image/upload/v1698793424/logos/WctOqFUxSxbZurYaLGy4/files/-Ni6yY-nECTlu-3rYPrw.svg.svg'
	image Roy Chung, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/axVGzXQhz2Sgbu6EejHThHIsCVp2/images/-Ne5gSUf_T8LaaVk83YK.jpg'
	heading Roy Chung
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Apollo, url='https://res.cloudinary.com/mentorcam/image/upload/v1694120864/logos/4MYe5wGtr3yrRRiUMYV4/files/-NdlTDKkPcTw-h9N2xl5.svg.svg'
	image Jason Feifer, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/mVPEdDDBSNe8s6m0uFFj0Ej7Cvo2/images/-MbIkZ8WOGC2OWRJkANp.jpg'
	heading Jason Feifer
	heading Editor
		paragraph
	separator, orientation='horizontal'
	image Entrepreneur, url='https://res.cloudinary.com/mentorcam/image/upload/v1681302612/logos/cceXBeGD3RfQzr8MVfeC/files/-NSpRTETlzkIWJ5kheqK.svg.svg'
	image Robin Daniels, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/xn9SoVfaBJc3ZqorFKu0UkkD4ps2/images/-NSp1-dkd4i12TETOsyg.jpg'
	heading Robin Daniels
	heading CMO
		paragraph
	separator, orientation='horizontal'
	image WeWork, url='https://res.cloudinary.com/mentorcam/image/upload/v1681943871/logos/tD0U2mfVCq2ajNdFba7e/files/-NTQedqTkHQHqJYuIxu_.svg.svg'
	separator, orientation='horizontal'
	paragraph
		StaticText TALK TO EXPERTS FROM
		StaticText THE WORLD’S TOP COMPANIES
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	separator, orientation='horizontal'
	article
		heading Access to an elite network
		image
		paragraph
			StaticText Mentorcam’s network of elite founders and business professionals are available to you on-demand.
		image
		paragraph
			StaticText Whether you work with a specific expert or seek input from multiple advisors, your network just got instantly stronger.
		image
		paragraph
			StaticText All Mentorcam experts are carefully vetted and have proven track records as highly successful builders and operators.
		image Access to an elite network, url='https://res.cloudinary.com/mentorcam/image/upload/ar_528:436,c_lfill,f_auto,g_face:center,q_100,w_600/v1/website/home/Mentor_Network_Image_fm0ggw.png'
	separator, orientation='horizontal'
	article
		heading Talk face to face on 1:1 video calls
		image
		paragraph
			StaticText Talk in real time on 1:1 video calls and get the advice and direction you need, when you need it.
		image
		paragraph
			StaticText Share your challenges in a safe and confidential environment and carve out a path to success.
		image
		paragraph
			StaticText Whether you’re looking for help fundraising, acquiring users, or developing tactical sales skills, an expert is here to help.
		image Talk face to face on 1:1 video calls, url='https://res.cloudinary.com/mentorcam/image/upload/ar_699:470,c_lfill,f_auto,g_auto:face,q_100,w_800/v1/website/home/Face_to_Face_Video_Image_e4sms1.png'
	separator, orientation='horizontal'
	article
		heading Message your mentor
		image
		paragraph
			StaticText Send messages before and after your calls. Access your messages at any time from your desktop or mobile device.
		image
		paragraph
			StaticText Share an agenda with topics to discuss or upload files for review. Set milestones and discuss progress between calls.
		image
		paragraph
			StaticText Mentorcam keeps everything on one platform so your conversation is always safe and secure.
		image Message your mentor, url='https://res.cloudinary.com/mentorcam/image/upload/ar_578:443,c_lfill,f_auto,g_face:center,q_100,w_650/v1/website/home/Message_Mentor_Image_avggpy.png'
	article
		image Founder, VRRB Labs, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/U0vFCAYMxpzVkMfSFGdl/images/-N_4tmaAmyXGalw1yiGE.jpg'
		heading “We ended up raising $1.42 million for our company.”
		heading Andrew Smith
		heading Founder, VRRB Labs
		link Read story, url='https://mentor.cam/articles/andrew-smith'
			button Read story
	article
		image Co-founder, Motiv, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/3yTcftWWFg9VwGoOyG9B/images/-N_4sOF3LqZGhpd7zuFe.jpg'
		heading “I’d give Mentorcam five out of five stars. I've been very impressed.”
		heading Mason Fuerst
		heading Co-founder, Motiv
		link Read story, url='https://mentor.cam/articles/mason-fuerst'
			button Read story
	article
		image Founder, Felvin, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/sRva2AR8AuThaefvF9vb/images/-N_4tzduE1_GBRUBL2YS.jpg'
		heading “I would not have raised $300K if it wasn’t for my mentor.”
		heading Harsh Gupta
		heading Founder, Felvin
		link Read story, url='https://mentor.cam/articles/raise-money-startup-or-business'
			button Read story
	article
		image Founder, InvestLink Social, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/74KNbacbZjksQC1ZnWg9/images/-N_4u7Jqk7FEtupC91fa.jpg'
		heading “We've been able to hyper speed our pre-seed round.”
		heading Christian Durfee
		heading Founder, InvestLink Social
		link Read story, url='https://mentor.cam/articles/christian-durfee'
			button Read story
	article
		image Co-founder, Happyrobot.ai, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/tUjHzfp6MmB1O04iv9eg/images/-N_4uFd3h7dbjiFGdhjj.jpg'
		heading “My mentors helped me deep dive into the mind of the customer.”
		heading Pablo Palafox
		heading Co-founder, Happyrobot.ai
		link Read story, url='https://mentor.cam/articles/pablo-palafox'
			button Read story
	article
		image Co-founder, Empower Sleep, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/BIxzVebcLYJvQ4xVPNG9/images/-N_4uYlZhKCSDTuC5LtM.jpg'
		heading “I'd walk out of mentorship sessions feeling much better about building.”
		heading Sagar Chopra
		heading Co-founder, Empower Sleep
		link Read story, url='https://mentor.cam/articles/sagar-chopra'
			button Read story
	article
		image Founder, Angelos Georgakis Executive Coaching, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/c5CnDzjqU5TCeEo8iQSB/images/-N_4ugwsXvM0wKruBesN.jpg'
		heading “How have you not signed up yet?”
		heading Angelos Georgakis
		heading Founder, Angelos Georgakis Executive Coaching
		link Read story, url='https://mentor.cam/articles/angelos-georgakis'
			button Read story
	article
		image Founder, Creativo Platform, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/XhL6fku7GH40Um42LKCm/images/-N_4tXecOSjuPFlz5Lk1.jpg'
		heading “Every mentor I've spoken to has helped us go further a lot faster.”
		heading Clint Rogers
		heading Founder, Creativo Platform
		link Read story, url='https://mentor.cam/articles/clint-rogers'
			button Read story
	heading Book a mentor for a 1:1 live call and get custom advice tailored to you from the world’s best startup founders and business leaders
	button B2B Software
	button Consumer Software
	button Artificial Intelligence
	button Branding
	button E-commerce & CPG
	button Fundraising
	button Venture Capital
	link Michael Litt Product & Sales Advice Michael Litt Co-Founder & CEO - Vidyard GTM & Generative AI Expert Vidyard, url='https://mentor.cam/michaellitt'
		image Michael Litt, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/071SzayHiobckWBc7BIEtlL24aA2/images/-O8c1SLrAj05ZUegOfNl.jpeg'
		heading Product & Sales Advice
		heading Michael Litt
		heading Co-Founder & CEO - Vidyard GTM & Generative AI Expert
		separator, orientation='horizontal'
		image Vidyard, url='https://res.cloudinary.com/mentorcam/image/upload/v1698793424/logos/WctOqFUxSxbZurYaLGy4/files/-Ni6yY-nECTlu-3rYPrw.svg.svg'
	link Derek Edwards Gen AI Engineering Advice Derek Edwards VP AI Technology - Elevance Health Gen AI Engineering Expert Elevance, url='https://mentor.cam/derekedwards'
		image Derek Edwards, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/kgWqasE0XdWmg7RhkMDWEAtj2Ih1/images/-NiPQIDS0TgXGqeIXS9C.jpeg'
		heading Gen AI Engineering Advice
		heading Derek Edwards
		heading VP AI Technology - Elevance Health Gen AI Engineering Expert
		separator, orientation='horizontal'
		image Elevance, url='https://res.cloudinary.com/mentorcam/image/upload/v1692027482/logos/Yj7EjKwuRurp0fPe2fAY/files/-NbogacZ46n3F997ph-2.svg.svg'
	link Josh Auffret Marketing Expert Josh Auffret Head of UX Programs & Operations - Google Product Marketing Expert Google, url='https://mentor.cam/joshauffret'
		image Josh Auffret, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/rptSDb1KAxdayDtkShO0CZSB9Bq2/images/-NlVESOg3LcDuy_TIkXU.jpg'
		heading Marketing Expert
		heading Josh Auffret
		heading Head of UX Programs & Operations - Google Product Marketing Expert
		separator, orientation='horizontal'
		image Google, url='https://res.cloudinary.com/mentorcam/image/upload/v1682025135/logos/7C5Eg3yRWHaAKixmlMXB/files/-NTVVeLZdlV-lyhezkMz.svg.svg'
	link Show more mentors, url='https://mentor.cam/categories/b2b-software'
	heading Sign up and access an elite network of world-class experts
	paragraph
		StaticText Book 1:1 calls and solve your most pressing challenges with the help of elite experts and industry leaders.
	link Create an account, url='https://mentor.cam/sign-up'
		button Create an account
	contentinfo
		list
			listitem
				list
					StaticText Expertise
					separator, orientation='horizontal'
					list
						listitem
							link B2B Sales, url='https://mentor.cam/categories/b2b-sales'
						listitem
							link B2C Sales, url='https://mentor.cam/categories/b2c-sales'
						listitem
							link Bootstrapping, url='https://mentor.cam/categories/bootstrapping'
						listitem
							link Branding, url='https://mentor.cam/categories/branding'
						listitem
							link Financial Planning, url='https://mentor.cam/categories/financial-planning'
						listitem
							link Fundraising, url='https://mentor.cam/categories/fundraising'
						listitem
							link Growth Marketing, url='https://mentor.cam/categories/growth-marketing'
						listitem
							link Manufacturing, url='https://mentor.cam/categories/manufacturing'
						listitem
							link People & Hiring, url='https://mentor.cam/categories/people-and-hiring'
						listitem
							link Product & Engineering, url='https://mentor.cam/categories/product-and-engineering'
						listitem
							link Product Marketing, url='https://mentor.cam/categories/product-marketing'
						listitem
							link Public Relations, url='https://mentor.cam/categories/public-relations'
						listitem
							link SEM & SEO, url='https://mentor.cam/categories/sem-seo'
						listitem
							link Social Media, url='https://mentor.cam/categories/social-media-marketing'
						listitem
							link Strategy & Operations, url='https://mentor.cam/categories/strategy-and-operations'
					StaticText Industry
					separator, orientation='horizontal'
					list
						listitem
							link Artificial Intelligence, url='https://mentor.cam/categories/artificial-intelligence'
						listitem
							link B2B Services, url='https://mentor.cam/categories/b2b-services'
						listitem
							link B2B Software, url='https://mentor.cam/categories/b2b-software'
						listitem
							link Consumer Products, url='https://mentor.cam/categories/consumer-hardware'
						listitem
							link Consumer Software, url='https://mentor.cam/categories/consumer-software'
						listitem
							link E-commerce & CPG, url='https://mentor.cam/categories/e-commerce-and-cpg'
						listitem
							link Education, url='https://mentor.cam/categories/education'
						listitem
							link Fashion & Apparel, url='https://mentor.cam/categories/fashion'
						listitem
							link Fintech, url='https://mentor.cam/categories/fintech'
						listitem
							link Food & Beverage, url='https://mentor.cam/categories/food-beverage'
						listitem
							link Gaming, url='https://mentor.cam/categories/gaming'
						listitem
							link Healthcare, url='https://mentor.cam/categories/healthcare'
						listitem
							link Insurance, url='https://mentor.cam/categories/insurance'
						listitem
							link Media & Entertainment, url='https://mentor.cam/categories/media-and-entertainment'
						listitem
							link Real Estate, url='https://mentor.cam/categories/real-estate'
						listitem
							link Venture Capital, url='https://mentor.cam/categories/venture-capital'
			listitem
				list
					listitem
						StaticText Mentorcam
						list
							separator, orientation='horizontal'
							listitem
								link Articles, url='https://mentor.cam/articles'
							listitem
								link For mentors, url='https://mentor.cam/for-mentors'
							listitem
								link Company, url='https://mentor.cam/company'
							listitem
								link Careers, url='https://www.ycombinator.com/companies/mentorcam/jobs'
							listitem
								link Support, url='https://mentor.cam/support'
		link, url='https://mentor.cam/for-business'
			image
		StaticText 1:1 advice from otherwise
		StaticText inaccessible mentors
		link Mentorcam Youtube, url='https://www.youtube.com/@mentorcam'
			image
		link Mentorcam LinkedIn, url='https://www.linkedin.com/company/mentorcam'
			image
		link Mentorcam Instagram, url='https://www.instagram.com/mentor.cam/'
			image
		link Mentorcam Facebook, url='https://www.facebook.com/mentorcam'
			image
		paragraph
			StaticText ©
			StaticText 2025
			StaticText Mentorcam, Inc.
			StaticText —
			StaticText 2450 Colorado Ave. Suite 100E, Santa Monica, CA 90404
		list
			listitem
				link Terms of Service, url='https://mentor.cam/terms'
			listitem
				link Mentor Terms, url='https://mentor.cam/mentor-terms'
			listitem
				link Privacy Policy, url='https://mentor.cam/privacy'
			listitem
				link Cookie Policy, url='https://mentor.cam/cookie-policy'
	alert, atomic
```
</details>

**Reasoning for action:** By clicking the Submit button (element 155), I am executing the user's request to subscribe to the newsletter on the Mentorcam homepage. This action aligns with the user story, as it initiates the process of signing up for the newsletter, which is necessary for receiving updates and a promotional code. Once clicked, I expect the website to respond with a confirmation message about the successful subscription and the mention that a promo code has been sent to the specified email address. This is a critical step in achieving the user's goal.

**Action:** click(155) # Click on the Submit button to see if it leads to any further actions or information.

**Change Description:** After clicking the Submit button, an alert indicating 'Invalid email address' is displayed in the browser, suggesting that the email provided in the textbox did not meet the required validation criteria.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://mentor.cam/

https://mentor.cam/

**Content (before/after):** 

```
RootWebArea Expert Startup Mentors | Unlock Your Potential | Mentorcam, focused, url='https://mentor.cam/'
	banner
		navigation
			link, url='https://mentor.cam/'
				image
```
<details><summary>Show more</summary>

```
			list
				listitem
					StaticText Browse
					image Find a Mentor, url='https://mentor.cam/_next/static/media/arrow-black-small-down.d77f3ecd.svg'
					list
						listitem
							list
								heading Expertise
								heading Industry
								link New Mentors, url='https://mentor.cam/search?categoryIds=new-mentor'
									heading New Mentors
				listitem
					image
					searchbox What advice are you looking for today?
			list
				listitem
					link For mentors, url='https://mentor.cam/for-mentors'
				listitem
					StaticText More
					image Find a Mentor, url='https://mentor.cam/_next/static/media/arrow-black-small-down.d77f3ecd.svg'
					list
						listitem
							link Articles, url='https://mentor.cam/articles'
						listitem
							link Company, url='https://mentor.cam/company'
						listitem
							link Careers, url='https://www.ycombinator.com/companies/mentorcam/jobs'
						listitem
							link Support, url='https://mentor.cam/support'
				listitem
				image Save $100 off on your first Mentorcam session, url='https://res.cloudinary.com/mentorcam/image/upload/ar_291:320,c_fill,f_auto,g_auto:face,q_100,w_320/v1/website/newsletter/newsletter_aol7lw.jpg'
				heading Get $50 off
				paragraph
					StaticText Sign up for our newsletter and get $50
					StaticText off your first Mentorcam session.
				[152] textbox Email, center=(1106,560), contenteditable=True
				LabelText
					StaticText Email
				paragraph
					StaticText Invalid email address
				[155] button Submit, center=(1106,635), focused, type=submit
				[156] paragraph, center=(1106,678), inner_text=No thanks
					StaticText No thanks
				listitem
					link Log in, url='https://mentor.cam/login'
				listitem
					link Sign up, url='https://mentor.cam/sign-up'
						button Sign up
	image
	heading Get advice from the world’s BEST mentors
	heading Book 1:1 calls with founders andleaders of the world’s best startups and brands.
	link Find a mentor, url='https://mentor.cam/search'
		button Find a mentor
	image Alexandra Zatarain, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/eo0NsIuHpXPKXsgcrNzMfRNbO7r1/images/-NFzvoPKAGSVDLE-4iqC.jpg'
	heading Alexandra Zatarain
	heading VP
		paragraph
	separator, orientation='horizontal'
	image Eight Sleep, url='https://res.cloudinary.com/mentorcam/image/upload/v1695102592/logos/oKcV58tiB5zXjewMIBJ9/files/-NefzCjW1J1wMJUB6610.svg.svg'
	image Chris Yeh, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/SDeGJdJ3hGUCw5EeNleQO6406Pw2/images/-MYu9atjX3CshcXuyTnP.jpg'
	heading Chris Yeh
	heading Partner
		paragraph
	separator, orientation='horizontal'
	image Blitzscaling Ventures, url='https://res.cloudinary.com/mentorcam/image/upload/v1695105994/logos/8SXFYBsn0L1r24Yfdl6Y/files/-NegBBLYOLgThNBrlfwU.svg.svg'
	image T Zhu, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/OLr4yMcDhoXzqjYuXLqeisBSlqX2/images/wEfjBsp1kJqi2ZOEMBfK.jpg'
	heading T Zhu
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Tellus, url='https://res.cloudinary.com/mentorcam/image/upload/v1681308442/logos/Hf7vDQ4zimBCEsxHonla/files/-NSpmhTNYPB9QbDvbqd8.svg.svg'
	image Michael Litt, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/071SzayHiobckWBc7BIEtlL24aA2/images/-O8c1SLrAj05ZUegOfNl.jpeg'
	heading Michael Litt
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Vidyard, url='https://res.cloudinary.com/mentorcam/image/upload/v1698793424/logos/WctOqFUxSxbZurYaLGy4/files/-Ni6yY-nECTlu-3rYPrw.svg.svg'
	image Roy Chung, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/axVGzXQhz2Sgbu6EejHThHIsCVp2/images/-Ne5gSUf_T8LaaVk83YK.jpg'
	heading Roy Chung
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Apollo, url='https://res.cloudinary.com/mentorcam/image/upload/v1694120864/logos/4MYe5wGtr3yrRRiUMYV4/files/-NdlTDKkPcTw-h9N2xl5.svg.svg'
	image Jason Feifer, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/mVPEdDDBSNe8s6m0uFFj0Ej7Cvo2/images/-MbIkZ8WOGC2OWRJkANp.jpg'
	heading Jason Feifer
	heading Editor
		paragraph
	separator, orientation='horizontal'
	image Entrepreneur, url='https://res.cloudinary.com/mentorcam/image/upload/v1681302612/logos/cceXBeGD3RfQzr8MVfeC/files/-NSpRTETlzkIWJ5kheqK.svg.svg'
	image Robin Daniels, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/xn9SoVfaBJc3ZqorFKu0UkkD4ps2/images/-NSp1-dkd4i12TETOsyg.jpg'
	heading Robin Daniels
	heading CMO
		paragraph
	separator, orientation='horizontal'
	image WeWork, url='https://res.cloudinary.com/mentorcam/image/upload/v1681943871/logos/tD0U2mfVCq2ajNdFba7e/files/-NTQedqTkHQHqJYuIxu_.svg.svg'
	separator, orientation='horizontal'
	paragraph
		StaticText TALK TO EXPERTS FROM
		StaticText THE WORLD’S TOP COMPANIES
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	separator, orientation='horizontal'
	article
		heading Access to an elite network
		image
		paragraph
			StaticText Mentorcam’s network of elite founders and business professionals are available to you on-demand.
		image
		paragraph
			StaticText Whether you work with a specific expert or seek input from multiple advisors, your network just got instantly stronger.
		image
		paragraph
			StaticText All Mentorcam experts are carefully vetted and have proven track records as highly successful builders and operators.
		image Access to an elite network, url='https://res.cloudinary.com/mentorcam/image/upload/ar_528:436,c_lfill,f_auto,g_face:center,q_100,w_600/v1/website/home/Mentor_Network_Image_fm0ggw.png'
	separator, orientation='horizontal'
	article
		heading Talk face to face on 1:1 video calls
		image
		paragraph
			StaticText Talk in real time on 1:1 video calls and get the advice and direction you need, when you need it.
		image
		paragraph
			StaticText Share your challenges in a safe and confidential environment and carve out a path to success.
		image
		paragraph
			StaticText Whether you’re looking for help fundraising, acquiring users, or developing tactical sales skills, an expert is here to help.
		image Talk face to face on 1:1 video calls, url='https://res.cloudinary.com/mentorcam/image/upload/ar_699:470,c_lfill,f_auto,g_auto:face,q_100,w_800/v1/website/home/Face_to_Face_Video_Image_e4sms1.png'
	separator, orientation='horizontal'
	article
		heading Message your mentor
		image
		paragraph
			StaticText Send messages before and after your calls. Access your messages at any time from your desktop or mobile device.
		image
		paragraph
			StaticText Share an agenda with topics to discuss or upload files for review. Set milestones and discuss progress between calls.
		image
		paragraph
			StaticText Mentorcam keeps everything on one platform so your conversation is always safe and secure.
		image Message your mentor, url='https://res.cloudinary.com/mentorcam/image/upload/ar_578:443,c_lfill,f_auto,g_face:center,q_100,w_650/v1/website/home/Message_Mentor_Image_avggpy.png'
	article
		image Founder, VRRB Labs, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/U0vFCAYMxpzVkMfSFGdl/images/-N_4tmaAmyXGalw1yiGE.jpg'
		heading “We ended up raising $1.42 million for our company.”
		heading Andrew Smith
		heading Founder, VRRB Labs
		link Read story, url='https://mentor.cam/articles/andrew-smith'
			button Read story
	article
		image Co-founder, Motiv, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/3yTcftWWFg9VwGoOyG9B/images/-N_4sOF3LqZGhpd7zuFe.jpg'
		heading “I’d give Mentorcam five out of five stars. I've been very impressed.”
		heading Mason Fuerst
		heading Co-founder, Motiv
		link Read story, url='https://mentor.cam/articles/mason-fuerst'
			button Read story
	article
		image Founder, Felvin, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/sRva2AR8AuThaefvF9vb/images/-N_4tzduE1_GBRUBL2YS.jpg'
		heading “I would not have raised $300K if it wasn’t for my mentor.”
		heading Harsh Gupta
		heading Founder, Felvin
		link Read story, url='https://mentor.cam/articles/raise-money-startup-or-business'
			button Read story
	article
		image Founder, InvestLink Social, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/74KNbacbZjksQC1ZnWg9/images/-N_4u7Jqk7FEtupC91fa.jpg'
		heading “We've been able to hyper speed our pre-seed round.”
		heading Christian Durfee
		heading Founder, InvestLink Social
		link Read story, url='https://mentor.cam/articles/christian-durfee'
			button Read story
	article
		image Co-founder, Happyrobot.ai, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/tUjHzfp6MmB1O04iv9eg/images/-N_4uFd3h7dbjiFGdhjj.jpg'
		heading “My mentors helped me deep dive into the mind of the customer.”
		heading Pablo Palafox
		heading Co-founder, Happyrobot.ai
		link Read story, url='https://mentor.cam/articles/pablo-palafox'
			button Read story
	article
		image Co-founder, Empower Sleep, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/BIxzVebcLYJvQ4xVPNG9/images/-N_4uYlZhKCSDTuC5LtM.jpg'
		heading “I'd walk out of mentorship sessions feeling much better about building.”
		heading Sagar Chopra
		heading Co-founder, Empower Sleep
		link Read story, url='https://mentor.cam/articles/sagar-chopra'
			button Read story
	article
		image Founder, Angelos Georgakis Executive Coaching, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/c5CnDzjqU5TCeEo8iQSB/images/-N_4ugwsXvM0wKruBesN.jpg'
		heading “How have you not signed up yet?”
		heading Angelos Georgakis
		heading Founder, Angelos Georgakis Executive Coaching
		link Read story, url='https://mentor.cam/articles/angelos-georgakis'
			button Read story
	article
		image Founder, Creativo Platform, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/XhL6fku7GH40Um42LKCm/images/-N_4tXecOSjuPFlz5Lk1.jpg'
		heading “Every mentor I've spoken to has helped us go further a lot faster.”
		heading Clint Rogers
		heading Founder, Creativo Platform
		link Read story, url='https://mentor.cam/articles/clint-rogers'
			button Read story
	heading Book a mentor for a 1:1 live call and get custom advice tailored to you from the world’s best startup founders and business leaders
	button B2B Software
	button Consumer Software
	button Artificial Intelligence
	button Branding
	button E-commerce & CPG
	button Fundraising
	button Venture Capital
	link Michael Litt Product & Sales Advice Michael Litt Co-Founder & CEO - Vidyard GTM & Generative AI Expert Vidyard, url='https://mentor.cam/michaellitt'
		image Michael Litt, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/071SzayHiobckWBc7BIEtlL24aA2/images/-O8c1SLrAj05ZUegOfNl.jpeg'
		heading Product & Sales Advice
		heading Michael Litt
		heading Co-Founder & CEO - Vidyard GTM & Generative AI Expert
		separator, orientation='horizontal'
		image Vidyard, url='https://res.cloudinary.com/mentorcam/image/upload/v1698793424/logos/WctOqFUxSxbZurYaLGy4/files/-Ni6yY-nECTlu-3rYPrw.svg.svg'
	link Derek Edwards Gen AI Engineering Advice Derek Edwards VP AI Technology - Elevance Health Gen AI Engineering Expert Elevance, url='https://mentor.cam/derekedwards'
		image Derek Edwards, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/kgWqasE0XdWmg7RhkMDWEAtj2Ih1/images/-NiPQIDS0TgXGqeIXS9C.jpeg'
		heading Gen AI Engineering Advice
		heading Derek Edwards
		heading VP AI Technology - Elevance Health Gen AI Engineering Expert
		separator, orientation='horizontal'
		image Elevance, url='https://res.cloudinary.com/mentorcam/image/upload/v1692027482/logos/Yj7EjKwuRurp0fPe2fAY/files/-NbogacZ46n3F997ph-2.svg.svg'
	link Josh Auffret Marketing Expert Josh Auffret Head of UX Programs & Operations - Google Product Marketing Expert Google, url='https://mentor.cam/joshauffret'
		image Josh Auffret, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/rptSDb1KAxdayDtkShO0CZSB9Bq2/images/-NlVESOg3LcDuy_TIkXU.jpg'
		heading Marketing Expert
		heading Josh Auffret
		heading Head of UX Programs & Operations - Google Product Marketing Expert
		separator, orientation='horizontal'
		image Google, url='https://res.cloudinary.com/mentorcam/image/upload/v1682025135/logos/7C5Eg3yRWHaAKixmlMXB/files/-NTVVeLZdlV-lyhezkMz.svg.svg'
	link Show more mentors, url='https://mentor.cam/categories/b2b-software'
	heading Sign up and access an elite network of world-class experts
	paragraph
		StaticText Book 1:1 calls and solve your most pressing challenges with the help of elite experts and industry leaders.
	link Create an account, url='https://mentor.cam/sign-up'
		button Create an account
	contentinfo
		list
			listitem
				list
					StaticText Expertise
					separator, orientation='horizontal'
					list
						listitem
							link B2B Sales, url='https://mentor.cam/categories/b2b-sales'
						listitem
							link B2C Sales, url='https://mentor.cam/categories/b2c-sales'
						listitem
							link Bootstrapping, url='https://mentor.cam/categories/bootstrapping'
						listitem
							link Branding, url='https://mentor.cam/categories/branding'
						listitem
							link Financial Planning, url='https://mentor.cam/categories/financial-planning'
						listitem
							link Fundraising, url='https://mentor.cam/categories/fundraising'
						listitem
							link Growth Marketing, url='https://mentor.cam/categories/growth-marketing'
						listitem
							link Manufacturing, url='https://mentor.cam/categories/manufacturing'
						listitem
							link People & Hiring, url='https://mentor.cam/categories/people-and-hiring'
						listitem
							link Product & Engineering, url='https://mentor.cam/categories/product-and-engineering'
						listitem
							link Product Marketing, url='https://mentor.cam/categories/product-marketing'
						listitem
							link Public Relations, url='https://mentor.cam/categories/public-relations'
						listitem
							link SEM & SEO, url='https://mentor.cam/categories/sem-seo'
						listitem
							link Social Media, url='https://mentor.cam/categories/social-media-marketing'
						listitem
							link Strategy & Operations, url='https://mentor.cam/categories/strategy-and-operations'
					StaticText Industry
					separator, orientation='horizontal'
					list
						listitem
							link Artificial Intelligence, url='https://mentor.cam/categories/artificial-intelligence'
						listitem
							link B2B Services, url='https://mentor.cam/categories/b2b-services'
						listitem
							link B2B Software, url='https://mentor.cam/categories/b2b-software'
						listitem
							link Consumer Products, url='https://mentor.cam/categories/consumer-hardware'
						listitem
							link Consumer Software, url='https://mentor.cam/categories/consumer-software'
						listitem
							link E-commerce & CPG, url='https://mentor.cam/categories/e-commerce-and-cpg'
						listitem
							link Education, url='https://mentor.cam/categories/education'
						listitem
							link Fashion & Apparel, url='https://mentor.cam/categories/fashion'
						listitem
							link Fintech, url='https://mentor.cam/categories/fintech'
						listitem
							link Food & Beverage, url='https://mentor.cam/categories/food-beverage'
						listitem
							link Gaming, url='https://mentor.cam/categories/gaming'
						listitem
							link Healthcare, url='https://mentor.cam/categories/healthcare'
						listitem
							link Insurance, url='https://mentor.cam/categories/insurance'
						listitem
							link Media & Entertainment, url='https://mentor.cam/categories/media-and-entertainment'
						listitem
							link Real Estate, url='https://mentor.cam/categories/real-estate'
						listitem
							link Venture Capital, url='https://mentor.cam/categories/venture-capital'
			listitem
				list
					listitem
						StaticText Mentorcam
						list
							separator, orientation='horizontal'
							listitem
								link Articles, url='https://mentor.cam/articles'
							listitem
								link For mentors, url='https://mentor.cam/for-mentors'
							listitem
								link Company, url='https://mentor.cam/company'
							listitem
								link Careers, url='https://www.ycombinator.com/companies/mentorcam/jobs'
							listitem
								link Support, url='https://mentor.cam/support'
		link, url='https://mentor.cam/for-business'
			image
		StaticText 1:1 advice from otherwise
		StaticText inaccessible mentors
		link Mentorcam Youtube, url='https://www.youtube.com/@mentorcam'
			image
		link Mentorcam LinkedIn, url='https://www.linkedin.com/company/mentorcam'
			image
		link Mentorcam Instagram, url='https://www.instagram.com/mentor.cam/'
			image
		link Mentorcam Facebook, url='https://www.facebook.com/mentorcam'
			image
		paragraph
			StaticText ©
			StaticText 2025
			StaticText Mentorcam, Inc.
			StaticText —
			StaticText 2450 Colorado Ave. Suite 100E, Santa Monica, CA 90404
		list
			listitem
				link Terms of Service, url='https://mentor.cam/terms'
			listitem
				link Mentor Terms, url='https://mentor.cam/mentor-terms'
			listitem
				link Privacy Policy, url='https://mentor.cam/privacy'
			listitem
				link Cookie Policy, url='https://mentor.cam/cookie-policy'
	alert, atomic
```
</details>



```
RootWebArea Expert Startup Mentors | Unlock Your Potential | Mentorcam, focused, url='https://mentor.cam/'
	banner
		navigation
			link, url='https://mentor.cam/'
				image
```
<details><summary>Show more</summary>

```
			list
				listitem
					StaticText Browse
					image Find a Mentor, url='https://mentor.cam/_next/static/media/arrow-black-small-down.d77f3ecd.svg'
					list
						listitem
							list
								heading Expertise
								heading Industry
								link New Mentors, url='https://mentor.cam/search?categoryIds=new-mentor'
									heading New Mentors
				listitem
					image
					searchbox What advice are you looking for today?
			list
				listitem
					link For mentors, url='https://mentor.cam/for-mentors'
				listitem
					StaticText More
					image Find a Mentor, url='https://mentor.cam/_next/static/media/arrow-black-small-down.d77f3ecd.svg'
					list
						listitem
							link Articles, url='https://mentor.cam/articles'
						listitem
							link Company, url='https://mentor.cam/company'
						listitem
							link Careers, url='https://www.ycombinator.com/companies/mentorcam/jobs'
						listitem
							link Support, url='https://mentor.cam/support'
				listitem
				image Save $100 off on your first Mentorcam session, url='https://res.cloudinary.com/mentorcam/image/upload/ar_291:320,c_fill,f_auto,g_auto:face,q_100,w_320/v1/website/newsletter/newsletter_aol7lw.jpg'
				heading Get $50 off
				paragraph
					StaticText Sign up for our newsletter and get $50
					StaticText off your first Mentorcam session.
				[152] textbox Email value='test@example.com', center=(1106,561), contenteditable=True, focused
				LabelText
					StaticText Email
				[155] button Submit, center=(1106,626), type=submit
				[156] paragraph, center=(1106,670), inner_text=No thanks
					StaticText No thanks
				listitem
					link Log in, url='https://mentor.cam/login'
				listitem
					link Sign up, url='https://mentor.cam/sign-up'
						button Sign up
	image
	heading Get advice from the world’s BEST mentors
	heading Book 1:1 calls with founders andleaders of the world’s best startups and brands.
	link Find a mentor, url='https://mentor.cam/search'
		button Find a mentor
	image Alexandra Zatarain, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/eo0NsIuHpXPKXsgcrNzMfRNbO7r1/images/-NFzvoPKAGSVDLE-4iqC.jpg'
	heading Alexandra Zatarain
	heading VP
		paragraph
	separator, orientation='horizontal'
	image Eight Sleep, url='https://res.cloudinary.com/mentorcam/image/upload/v1695102592/logos/oKcV58tiB5zXjewMIBJ9/files/-NefzCjW1J1wMJUB6610.svg.svg'
	image Chris Yeh, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/SDeGJdJ3hGUCw5EeNleQO6406Pw2/images/-MYu9atjX3CshcXuyTnP.jpg'
	heading Chris Yeh
	heading Partner
		paragraph
	separator, orientation='horizontal'
	image Blitzscaling Ventures, url='https://res.cloudinary.com/mentorcam/image/upload/v1695105994/logos/8SXFYBsn0L1r24Yfdl6Y/files/-NegBBLYOLgThNBrlfwU.svg.svg'
	image T Zhu, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/OLr4yMcDhoXzqjYuXLqeisBSlqX2/images/wEfjBsp1kJqi2ZOEMBfK.jpg'
	heading T Zhu
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Tellus, url='https://res.cloudinary.com/mentorcam/image/upload/v1681308442/logos/Hf7vDQ4zimBCEsxHonla/files/-NSpmhTNYPB9QbDvbqd8.svg.svg'
	image Michael Litt, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/071SzayHiobckWBc7BIEtlL24aA2/images/-O8c1SLrAj05ZUegOfNl.jpeg'
	heading Michael Litt
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Vidyard, url='https://res.cloudinary.com/mentorcam/image/upload/v1698793424/logos/WctOqFUxSxbZurYaLGy4/files/-Ni6yY-nECTlu-3rYPrw.svg.svg'
	image Roy Chung, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/axVGzXQhz2Sgbu6EejHThHIsCVp2/images/-Ne5gSUf_T8LaaVk83YK.jpg'
	heading Roy Chung
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Apollo, url='https://res.cloudinary.com/mentorcam/image/upload/v1694120864/logos/4MYe5wGtr3yrRRiUMYV4/files/-NdlTDKkPcTw-h9N2xl5.svg.svg'
	image Jason Feifer, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/mVPEdDDBSNe8s6m0uFFj0Ej7Cvo2/images/-MbIkZ8WOGC2OWRJkANp.jpg'
	heading Jason Feifer
	heading Editor
		paragraph
	separator, orientation='horizontal'
	image Entrepreneur, url='https://res.cloudinary.com/mentorcam/image/upload/v1681302612/logos/cceXBeGD3RfQzr8MVfeC/files/-NSpRTETlzkIWJ5kheqK.svg.svg'
	image Robin Daniels, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/xn9SoVfaBJc3ZqorFKu0UkkD4ps2/images/-NSp1-dkd4i12TETOsyg.jpg'
	heading Robin Daniels
	heading CMO
		paragraph
	separator, orientation='horizontal'
	image WeWork, url='https://res.cloudinary.com/mentorcam/image/upload/v1681943871/logos/tD0U2mfVCq2ajNdFba7e/files/-NTQedqTkHQHqJYuIxu_.svg.svg'
	separator, orientation='horizontal'
	paragraph
		StaticText TALK TO EXPERTS FROM
		StaticText THE WORLD’S TOP COMPANIES
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	separator, orientation='horizontal'
	article
		heading Access to an elite network
		image
		paragraph
			StaticText Mentorcam’s network of elite founders and business professionals are available to you on-demand.
		image
		paragraph
			StaticText Whether you work with a specific expert or seek input from multiple advisors, your network just got instantly stronger.
		image
		paragraph
			StaticText All Mentorcam experts are carefully vetted and have proven track records as highly successful builders and operators.
		image Access to an elite network, url='https://res.cloudinary.com/mentorcam/image/upload/ar_528:436,c_lfill,f_auto,g_face:center,q_100,w_600/v1/website/home/Mentor_Network_Image_fm0ggw.png'
	separator, orientation='horizontal'
	article
		heading Talk face to face on 1:1 video calls
		image
		paragraph
			StaticText Talk in real time on 1:1 video calls and get the advice and direction you need, when you need it.
		image
		paragraph
			StaticText Share your challenges in a safe and confidential environment and carve out a path to success.
		image
		paragraph
			StaticText Whether you’re looking for help fundraising, acquiring users, or developing tactical sales skills, an expert is here to help.
		image Talk face to face on 1:1 video calls, url='https://res.cloudinary.com/mentorcam/image/upload/ar_699:470,c_lfill,f_auto,g_auto:face,q_100,w_800/v1/website/home/Face_to_Face_Video_Image_e4sms1.png'
	separator, orientation='horizontal'
	article
		heading Message your mentor
		image
		paragraph
			StaticText Send messages before and after your calls. Access your messages at any time from your desktop or mobile device.
		image
		paragraph
			StaticText Share an agenda with topics to discuss or upload files for review. Set milestones and discuss progress between calls.
		image
		paragraph
			StaticText Mentorcam keeps everything on one platform so your conversation is always safe and secure.
		image Message your mentor, url='https://res.cloudinary.com/mentorcam/image/upload/ar_578:443,c_lfill,f_auto,g_face:center,q_100,w_650/v1/website/home/Message_Mentor_Image_avggpy.png'
	article
		image Co-founder, Happyrobot.ai, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/tUjHzfp6MmB1O04iv9eg/images/-N_4uFd3h7dbjiFGdhjj.jpg'
		heading “My mentors helped me deep dive into the mind of the customer.”
		heading Pablo Palafox
		heading Co-founder, Happyrobot.ai
		link Read story, url='https://mentor.cam/articles/pablo-palafox'
			button Read story
	article
		image Co-founder, Empower Sleep, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/BIxzVebcLYJvQ4xVPNG9/images/-N_4uYlZhKCSDTuC5LtM.jpg'
		heading “I'd walk out of mentorship sessions feeling much better about building.”
		heading Sagar Chopra
		heading Co-founder, Empower Sleep
		link Read story, url='https://mentor.cam/articles/sagar-chopra'
			button Read story
	article
		image Founder, Angelos Georgakis Executive Coaching, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/c5CnDzjqU5TCeEo8iQSB/images/-N_4ugwsXvM0wKruBesN.jpg'
		heading “How have you not signed up yet?”
		heading Angelos Georgakis
		heading Founder, Angelos Georgakis Executive Coaching
		link Read story, url='https://mentor.cam/articles/angelos-georgakis'
			button Read story
	article
		image Founder, Creativo Platform, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/XhL6fku7GH40Um42LKCm/images/-N_4tXecOSjuPFlz5Lk1.jpg'
		heading “Every mentor I've spoken to has helped us go further a lot faster.”
		heading Clint Rogers
		heading Founder, Creativo Platform
		link Read story, url='https://mentor.cam/articles/clint-rogers'
			button Read story
	article
		image Founder, VRRB Labs, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/U0vFCAYMxpzVkMfSFGdl/images/-N_4tmaAmyXGalw1yiGE.jpg'
		heading “We ended up raising $1.42 million for our company.”
		heading Andrew Smith
		heading Founder, VRRB Labs
		link Read story, url='https://mentor.cam/articles/andrew-smith'
			button Read story
	article
		image Co-founder, Motiv, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/3yTcftWWFg9VwGoOyG9B/images/-N_4sOF3LqZGhpd7zuFe.jpg'
		heading “I’d give Mentorcam five out of five stars. I've been very impressed.”
		heading Mason Fuerst
		heading Co-founder, Motiv
		link Read story, url='https://mentor.cam/articles/mason-fuerst'
			button Read story
	article
		image Founder, Felvin, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/sRva2AR8AuThaefvF9vb/images/-N_4tzduE1_GBRUBL2YS.jpg'
		heading “I would not have raised $300K if it wasn’t for my mentor.”
		heading Harsh Gupta
		heading Founder, Felvin
		link Read story, url='https://mentor.cam/articles/raise-money-startup-or-business'
			button Read story
	article
		image Founder, InvestLink Social, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/74KNbacbZjksQC1ZnWg9/images/-N_4u7Jqk7FEtupC91fa.jpg'
		heading “We've been able to hyper speed our pre-seed round.”
		heading Christian Durfee
		heading Founder, InvestLink Social
		link Read story, url='https://mentor.cam/articles/christian-durfee'
			button Read story
	heading Book a mentor for a 1:1 live call and get custom advice tailored to you from the world’s best startup founders and business leaders
	button B2B Software
	button Consumer Software
	button Artificial Intelligence
	button Branding
	button E-commerce & CPG
	button Fundraising
	button Venture Capital
	link Michael Litt Product & Sales Advice Michael Litt Co-Founder & CEO - Vidyard GTM & Generative AI Expert Vidyard, url='https://mentor.cam/michaellitt'
		image Michael Litt, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/071SzayHiobckWBc7BIEtlL24aA2/images/-O8c1SLrAj05ZUegOfNl.jpeg'
		heading Product & Sales Advice
		heading Michael Litt
		heading Co-Founder & CEO - Vidyard GTM & Generative AI Expert
		separator, orientation='horizontal'
		image Vidyard, url='https://res.cloudinary.com/mentorcam/image/upload/v1698793424/logos/WctOqFUxSxbZurYaLGy4/files/-Ni6yY-nECTlu-3rYPrw.svg.svg'
	link Derek Edwards Gen AI Engineering Advice Derek Edwards VP AI Technology - Elevance Health Gen AI Engineering Expert Elevance, url='https://mentor.cam/derekedwards'
		image Derek Edwards, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/kgWqasE0XdWmg7RhkMDWEAtj2Ih1/images/-NiPQIDS0TgXGqeIXS9C.jpeg'
		heading Gen AI Engineering Advice
		heading Derek Edwards
		heading VP AI Technology - Elevance Health Gen AI Engineering Expert
		separator, orientation='horizontal'
		image Elevance, url='https://res.cloudinary.com/mentorcam/image/upload/v1692027482/logos/Yj7EjKwuRurp0fPe2fAY/files/-NbogacZ46n3F997ph-2.svg.svg'
	link Josh Auffret Marketing Expert Josh Auffret Head of UX Programs & Operations - Google Product Marketing Expert Google, url='https://mentor.cam/joshauffret'
		image Josh Auffret, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/rptSDb1KAxdayDtkShO0CZSB9Bq2/images/-NlVESOg3LcDuy_TIkXU.jpg'
		heading Marketing Expert
		heading Josh Auffret
		heading Head of UX Programs & Operations - Google Product Marketing Expert
		separator, orientation='horizontal'
		image Google, url='https://res.cloudinary.com/mentorcam/image/upload/v1682025135/logos/7C5Eg3yRWHaAKixmlMXB/files/-NTVVeLZdlV-lyhezkMz.svg.svg'
	link Show more mentors, url='https://mentor.cam/categories/b2b-software'
	heading Sign up and access an elite network of world-class experts
	paragraph
		StaticText Book 1:1 calls and solve your most pressing challenges with the help of elite experts and industry leaders.
	link Create an account, url='https://mentor.cam/sign-up'
		button Create an account
	contentinfo
		list
			listitem
				list
					StaticText Expertise
					separator, orientation='horizontal'
					list
						listitem
							link B2B Sales, url='https://mentor.cam/categories/b2b-sales'
						listitem
							link B2C Sales, url='https://mentor.cam/categories/b2c-sales'
						listitem
							link Bootstrapping, url='https://mentor.cam/categories/bootstrapping'
						listitem
							link Branding, url='https://mentor.cam/categories/branding'
						listitem
							link Financial Planning, url='https://mentor.cam/categories/financial-planning'
						listitem
							link Fundraising, url='https://mentor.cam/categories/fundraising'
						listitem
							link Growth Marketing, url='https://mentor.cam/categories/growth-marketing'
						listitem
							link Manufacturing, url='https://mentor.cam/categories/manufacturing'
						listitem
							link People & Hiring, url='https://mentor.cam/categories/people-and-hiring'
						listitem
							link Product & Engineering, url='https://mentor.cam/categories/product-and-engineering'
						listitem
							link Product Marketing, url='https://mentor.cam/categories/product-marketing'
						listitem
							link Public Relations, url='https://mentor.cam/categories/public-relations'
						listitem
							link SEM & SEO, url='https://mentor.cam/categories/sem-seo'
						listitem
							link Social Media, url='https://mentor.cam/categories/social-media-marketing'
						listitem
							link Strategy & Operations, url='https://mentor.cam/categories/strategy-and-operations'
					StaticText Industry
					separator, orientation='horizontal'
					list
						listitem
							link Artificial Intelligence, url='https://mentor.cam/categories/artificial-intelligence'
						listitem
							link B2B Services, url='https://mentor.cam/categories/b2b-services'
						listitem
							link B2B Software, url='https://mentor.cam/categories/b2b-software'
						listitem
							link Consumer Products, url='https://mentor.cam/categories/consumer-hardware'
						listitem
							link Consumer Software, url='https://mentor.cam/categories/consumer-software'
						listitem
							link E-commerce & CPG, url='https://mentor.cam/categories/e-commerce-and-cpg'
						listitem
							link Education, url='https://mentor.cam/categories/education'
						listitem
							link Fashion & Apparel, url='https://mentor.cam/categories/fashion'
						listitem
							link Fintech, url='https://mentor.cam/categories/fintech'
						listitem
							link Food & Beverage, url='https://mentor.cam/categories/food-beverage'
						listitem
							link Gaming, url='https://mentor.cam/categories/gaming'
						listitem
							link Healthcare, url='https://mentor.cam/categories/healthcare'
						listitem
							link Insurance, url='https://mentor.cam/categories/insurance'
						listitem
							link Media & Entertainment, url='https://mentor.cam/categories/media-and-entertainment'
						listitem
							link Real Estate, url='https://mentor.cam/categories/real-estate'
						listitem
							link Venture Capital, url='https://mentor.cam/categories/venture-capital'
			listitem
				list
					listitem
						StaticText Mentorcam
						list
							separator, orientation='horizontal'
							listitem
								link Articles, url='https://mentor.cam/articles'
							listitem
								link For mentors, url='https://mentor.cam/for-mentors'
							listitem
								link Company, url='https://mentor.cam/company'
							listitem
								link Careers, url='https://www.ycombinator.com/companies/mentorcam/jobs'
							listitem
								link Support, url='https://mentor.cam/support'
		link, url='https://mentor.cam/for-business'
			image
		StaticText 1:1 advice from otherwise
		StaticText inaccessible mentors
		link Mentorcam Youtube, url='https://www.youtube.com/@mentorcam'
			image
		link Mentorcam LinkedIn, url='https://www.linkedin.com/company/mentorcam'
			image
		link Mentorcam Instagram, url='https://www.instagram.com/mentor.cam/'
			image
		link Mentorcam Facebook, url='https://www.facebook.com/mentorcam'
			image
		paragraph
			StaticText ©
			StaticText 2025
			StaticText Mentorcam, Inc.
			StaticText —
			StaticText 2450 Colorado Ave. Suite 100E, Santa Monica, CA 90404
		list
			listitem
				link Terms of Service, url='https://mentor.cam/terms'
			listitem
				link Mentor Terms, url='https://mentor.cam/mentor-terms'
			listitem
				link Privacy Policy, url='https://mentor.cam/privacy'
			listitem
				link Cookie Policy, url='https://mentor.cam/cookie-policy'
	alert, atomic
```
</details>

**Reasoning for action:** I chose to fill in the email address because the user story specifies that I need to subscribe to the newsletter by submitting an email. By entering a valid email, I am progressing towards triggering the submission process which is necessary to receive a confirmation message as part of the success criteria.

**Action:** fill(152, 'test@example.com') # Fill in a valid email address in the email input field.

**Change Description:** The email input field was updated to contain the valid email address 'test@example.com', and the status of the email field changed from showing 'Invalid email address' to being empty of such messages.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://mentor.cam/

https://mentor.cam/

**Content (before/after):** 

```
RootWebArea Expert Startup Mentors | Unlock Your Potential | Mentorcam, focused, url='https://mentor.cam/'
	banner
		navigation
			link, url='https://mentor.cam/'
				image
```
<details><summary>Show more</summary>

```
			list
				listitem
					StaticText Browse
					image Find a Mentor, url='https://mentor.cam/_next/static/media/arrow-black-small-down.d77f3ecd.svg'
					list
						listitem
							list
								heading Expertise
								heading Industry
								link New Mentors, url='https://mentor.cam/search?categoryIds=new-mentor'
									heading New Mentors
				listitem
					image
					searchbox What advice are you looking for today?
			list
				listitem
					link For mentors, url='https://mentor.cam/for-mentors'
				listitem
					StaticText More
					image Find a Mentor, url='https://mentor.cam/_next/static/media/arrow-black-small-down.d77f3ecd.svg'
					list
						listitem
							link Articles, url='https://mentor.cam/articles'
						listitem
							link Company, url='https://mentor.cam/company'
						listitem
							link Careers, url='https://www.ycombinator.com/companies/mentorcam/jobs'
						listitem
							link Support, url='https://mentor.cam/support'
				listitem
				image Save $100 off on your first Mentorcam session, url='https://res.cloudinary.com/mentorcam/image/upload/ar_291:320,c_fill,f_auto,g_auto:face,q_100,w_320/v1/website/newsletter/newsletter_aol7lw.jpg'
				heading Get $50 off
				paragraph
					StaticText Sign up for our newsletter and get $50
					StaticText off your first Mentorcam session.
				[152] textbox Email value='test@example.com', center=(1106,561), contenteditable=True, focused
				LabelText
					StaticText Email
				[155] button Submit, center=(1106,626), type=submit
				[156] paragraph, center=(1106,670), inner_text=No thanks
					StaticText No thanks
				listitem
					link Log in, url='https://mentor.cam/login'
				listitem
					link Sign up, url='https://mentor.cam/sign-up'
						button Sign up
	image
	heading Get advice from the world’s BEST mentors
	heading Book 1:1 calls with founders andleaders of the world’s best startups and brands.
	link Find a mentor, url='https://mentor.cam/search'
		button Find a mentor
	image Alexandra Zatarain, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/eo0NsIuHpXPKXsgcrNzMfRNbO7r1/images/-NFzvoPKAGSVDLE-4iqC.jpg'
	heading Alexandra Zatarain
	heading VP
		paragraph
	separator, orientation='horizontal'
	image Eight Sleep, url='https://res.cloudinary.com/mentorcam/image/upload/v1695102592/logos/oKcV58tiB5zXjewMIBJ9/files/-NefzCjW1J1wMJUB6610.svg.svg'
	image Chris Yeh, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/SDeGJdJ3hGUCw5EeNleQO6406Pw2/images/-MYu9atjX3CshcXuyTnP.jpg'
	heading Chris Yeh
	heading Partner
		paragraph
	separator, orientation='horizontal'
	image Blitzscaling Ventures, url='https://res.cloudinary.com/mentorcam/image/upload/v1695105994/logos/8SXFYBsn0L1r24Yfdl6Y/files/-NegBBLYOLgThNBrlfwU.svg.svg'
	image T Zhu, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/OLr4yMcDhoXzqjYuXLqeisBSlqX2/images/wEfjBsp1kJqi2ZOEMBfK.jpg'
	heading T Zhu
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Tellus, url='https://res.cloudinary.com/mentorcam/image/upload/v1681308442/logos/Hf7vDQ4zimBCEsxHonla/files/-NSpmhTNYPB9QbDvbqd8.svg.svg'
	image Michael Litt, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/071SzayHiobckWBc7BIEtlL24aA2/images/-O8c1SLrAj05ZUegOfNl.jpeg'
	heading Michael Litt
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Vidyard, url='https://res.cloudinary.com/mentorcam/image/upload/v1698793424/logos/WctOqFUxSxbZurYaLGy4/files/-Ni6yY-nECTlu-3rYPrw.svg.svg'
	image Roy Chung, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/axVGzXQhz2Sgbu6EejHThHIsCVp2/images/-Ne5gSUf_T8LaaVk83YK.jpg'
	heading Roy Chung
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Apollo, url='https://res.cloudinary.com/mentorcam/image/upload/v1694120864/logos/4MYe5wGtr3yrRRiUMYV4/files/-NdlTDKkPcTw-h9N2xl5.svg.svg'
	image Jason Feifer, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/mVPEdDDBSNe8s6m0uFFj0Ej7Cvo2/images/-MbIkZ8WOGC2OWRJkANp.jpg'
	heading Jason Feifer
	heading Editor
		paragraph
	separator, orientation='horizontal'
	image Entrepreneur, url='https://res.cloudinary.com/mentorcam/image/upload/v1681302612/logos/cceXBeGD3RfQzr8MVfeC/files/-NSpRTETlzkIWJ5kheqK.svg.svg'
	image Robin Daniels, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/xn9SoVfaBJc3ZqorFKu0UkkD4ps2/images/-NSp1-dkd4i12TETOsyg.jpg'
	heading Robin Daniels
	heading CMO
		paragraph
	separator, orientation='horizontal'
	image WeWork, url='https://res.cloudinary.com/mentorcam/image/upload/v1681943871/logos/tD0U2mfVCq2ajNdFba7e/files/-NTQedqTkHQHqJYuIxu_.svg.svg'
	separator, orientation='horizontal'
	paragraph
		StaticText TALK TO EXPERTS FROM
		StaticText THE WORLD’S TOP COMPANIES
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	separator, orientation='horizontal'
	article
		heading Access to an elite network
		image
		paragraph
			StaticText Mentorcam’s network of elite founders and business professionals are available to you on-demand.
		image
		paragraph
			StaticText Whether you work with a specific expert or seek input from multiple advisors, your network just got instantly stronger.
		image
		paragraph
			StaticText All Mentorcam experts are carefully vetted and have proven track records as highly successful builders and operators.
		image Access to an elite network, url='https://res.cloudinary.com/mentorcam/image/upload/ar_528:436,c_lfill,f_auto,g_face:center,q_100,w_600/v1/website/home/Mentor_Network_Image_fm0ggw.png'
	separator, orientation='horizontal'
	article
		heading Talk face to face on 1:1 video calls
		image
		paragraph
			StaticText Talk in real time on 1:1 video calls and get the advice and direction you need, when you need it.
		image
		paragraph
			StaticText Share your challenges in a safe and confidential environment and carve out a path to success.
		image
		paragraph
			StaticText Whether you’re looking for help fundraising, acquiring users, or developing tactical sales skills, an expert is here to help.
		image Talk face to face on 1:1 video calls, url='https://res.cloudinary.com/mentorcam/image/upload/ar_699:470,c_lfill,f_auto,g_auto:face,q_100,w_800/v1/website/home/Face_to_Face_Video_Image_e4sms1.png'
	separator, orientation='horizontal'
	article
		heading Message your mentor
		image
		paragraph
			StaticText Send messages before and after your calls. Access your messages at any time from your desktop or mobile device.
		image
		paragraph
			StaticText Share an agenda with topics to discuss or upload files for review. Set milestones and discuss progress between calls.
		image
		paragraph
			StaticText Mentorcam keeps everything on one platform so your conversation is always safe and secure.
		image Message your mentor, url='https://res.cloudinary.com/mentorcam/image/upload/ar_578:443,c_lfill,f_auto,g_face:center,q_100,w_650/v1/website/home/Message_Mentor_Image_avggpy.png'
	article
		image Co-founder, Happyrobot.ai, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/tUjHzfp6MmB1O04iv9eg/images/-N_4uFd3h7dbjiFGdhjj.jpg'
		heading “My mentors helped me deep dive into the mind of the customer.”
		heading Pablo Palafox
		heading Co-founder, Happyrobot.ai
		link Read story, url='https://mentor.cam/articles/pablo-palafox'
			button Read story
	article
		image Co-founder, Empower Sleep, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/BIxzVebcLYJvQ4xVPNG9/images/-N_4uYlZhKCSDTuC5LtM.jpg'
		heading “I'd walk out of mentorship sessions feeling much better about building.”
		heading Sagar Chopra
		heading Co-founder, Empower Sleep
		link Read story, url='https://mentor.cam/articles/sagar-chopra'
			button Read story
	article
		image Founder, Angelos Georgakis Executive Coaching, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/c5CnDzjqU5TCeEo8iQSB/images/-N_4ugwsXvM0wKruBesN.jpg'
		heading “How have you not signed up yet?”
		heading Angelos Georgakis
		heading Founder, Angelos Georgakis Executive Coaching
		link Read story, url='https://mentor.cam/articles/angelos-georgakis'
			button Read story
	article
		image Founder, Creativo Platform, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/XhL6fku7GH40Um42LKCm/images/-N_4tXecOSjuPFlz5Lk1.jpg'
		heading “Every mentor I've spoken to has helped us go further a lot faster.”
		heading Clint Rogers
		heading Founder, Creativo Platform
		link Read story, url='https://mentor.cam/articles/clint-rogers'
			button Read story
	article
		image Founder, VRRB Labs, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/U0vFCAYMxpzVkMfSFGdl/images/-N_4tmaAmyXGalw1yiGE.jpg'
		heading “We ended up raising $1.42 million for our company.”
		heading Andrew Smith
		heading Founder, VRRB Labs
		link Read story, url='https://mentor.cam/articles/andrew-smith'
			button Read story
	article
		image Co-founder, Motiv, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/3yTcftWWFg9VwGoOyG9B/images/-N_4sOF3LqZGhpd7zuFe.jpg'
		heading “I’d give Mentorcam five out of five stars. I've been very impressed.”
		heading Mason Fuerst
		heading Co-founder, Motiv
		link Read story, url='https://mentor.cam/articles/mason-fuerst'
			button Read story
	article
		image Founder, Felvin, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/sRva2AR8AuThaefvF9vb/images/-N_4tzduE1_GBRUBL2YS.jpg'
		heading “I would not have raised $300K if it wasn’t for my mentor.”
		heading Harsh Gupta
		heading Founder, Felvin
		link Read story, url='https://mentor.cam/articles/raise-money-startup-or-business'
			button Read story
	article
		image Founder, InvestLink Social, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/74KNbacbZjksQC1ZnWg9/images/-N_4u7Jqk7FEtupC91fa.jpg'
		heading “We've been able to hyper speed our pre-seed round.”
		heading Christian Durfee
		heading Founder, InvestLink Social
		link Read story, url='https://mentor.cam/articles/christian-durfee'
			button Read story
	heading Book a mentor for a 1:1 live call and get custom advice tailored to you from the world’s best startup founders and business leaders
	button B2B Software
	button Consumer Software
	button Artificial Intelligence
	button Branding
	button E-commerce & CPG
	button Fundraising
	button Venture Capital
	link Michael Litt Product & Sales Advice Michael Litt Co-Founder & CEO - Vidyard GTM & Generative AI Expert Vidyard, url='https://mentor.cam/michaellitt'
		image Michael Litt, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/071SzayHiobckWBc7BIEtlL24aA2/images/-O8c1SLrAj05ZUegOfNl.jpeg'
		heading Product & Sales Advice
		heading Michael Litt
		heading Co-Founder & CEO - Vidyard GTM & Generative AI Expert
		separator, orientation='horizontal'
		image Vidyard, url='https://res.cloudinary.com/mentorcam/image/upload/v1698793424/logos/WctOqFUxSxbZurYaLGy4/files/-Ni6yY-nECTlu-3rYPrw.svg.svg'
	link Derek Edwards Gen AI Engineering Advice Derek Edwards VP AI Technology - Elevance Health Gen AI Engineering Expert Elevance, url='https://mentor.cam/derekedwards'
		image Derek Edwards, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/kgWqasE0XdWmg7RhkMDWEAtj2Ih1/images/-NiPQIDS0TgXGqeIXS9C.jpeg'
		heading Gen AI Engineering Advice
		heading Derek Edwards
		heading VP AI Technology - Elevance Health Gen AI Engineering Expert
		separator, orientation='horizontal'
		image Elevance, url='https://res.cloudinary.com/mentorcam/image/upload/v1692027482/logos/Yj7EjKwuRurp0fPe2fAY/files/-NbogacZ46n3F997ph-2.svg.svg'
	link Josh Auffret Marketing Expert Josh Auffret Head of UX Programs & Operations - Google Product Marketing Expert Google, url='https://mentor.cam/joshauffret'
		image Josh Auffret, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/rptSDb1KAxdayDtkShO0CZSB9Bq2/images/-NlVESOg3LcDuy_TIkXU.jpg'
		heading Marketing Expert
		heading Josh Auffret
		heading Head of UX Programs & Operations - Google Product Marketing Expert
		separator, orientation='horizontal'
		image Google, url='https://res.cloudinary.com/mentorcam/image/upload/v1682025135/logos/7C5Eg3yRWHaAKixmlMXB/files/-NTVVeLZdlV-lyhezkMz.svg.svg'
	link Show more mentors, url='https://mentor.cam/categories/b2b-software'
	heading Sign up and access an elite network of world-class experts
	paragraph
		StaticText Book 1:1 calls and solve your most pressing challenges with the help of elite experts and industry leaders.
	link Create an account, url='https://mentor.cam/sign-up'
		button Create an account
	contentinfo
		list
			listitem
				list
					StaticText Expertise
					separator, orientation='horizontal'
					list
						listitem
							link B2B Sales, url='https://mentor.cam/categories/b2b-sales'
						listitem
							link B2C Sales, url='https://mentor.cam/categories/b2c-sales'
						listitem
							link Bootstrapping, url='https://mentor.cam/categories/bootstrapping'
						listitem
							link Branding, url='https://mentor.cam/categories/branding'
						listitem
							link Financial Planning, url='https://mentor.cam/categories/financial-planning'
						listitem
							link Fundraising, url='https://mentor.cam/categories/fundraising'
						listitem
							link Growth Marketing, url='https://mentor.cam/categories/growth-marketing'
						listitem
							link Manufacturing, url='https://mentor.cam/categories/manufacturing'
						listitem
							link People & Hiring, url='https://mentor.cam/categories/people-and-hiring'
						listitem
							link Product & Engineering, url='https://mentor.cam/categories/product-and-engineering'
						listitem
							link Product Marketing, url='https://mentor.cam/categories/product-marketing'
						listitem
							link Public Relations, url='https://mentor.cam/categories/public-relations'
						listitem
							link SEM & SEO, url='https://mentor.cam/categories/sem-seo'
						listitem
							link Social Media, url='https://mentor.cam/categories/social-media-marketing'
						listitem
							link Strategy & Operations, url='https://mentor.cam/categories/strategy-and-operations'
					StaticText Industry
					separator, orientation='horizontal'
					list
						listitem
							link Artificial Intelligence, url='https://mentor.cam/categories/artificial-intelligence'
						listitem
							link B2B Services, url='https://mentor.cam/categories/b2b-services'
						listitem
							link B2B Software, url='https://mentor.cam/categories/b2b-software'
						listitem
							link Consumer Products, url='https://mentor.cam/categories/consumer-hardware'
						listitem
							link Consumer Software, url='https://mentor.cam/categories/consumer-software'
						listitem
							link E-commerce & CPG, url='https://mentor.cam/categories/e-commerce-and-cpg'
						listitem
							link Education, url='https://mentor.cam/categories/education'
						listitem
							link Fashion & Apparel, url='https://mentor.cam/categories/fashion'
						listitem
							link Fintech, url='https://mentor.cam/categories/fintech'
						listitem
							link Food & Beverage, url='https://mentor.cam/categories/food-beverage'
						listitem
							link Gaming, url='https://mentor.cam/categories/gaming'
						listitem
							link Healthcare, url='https://mentor.cam/categories/healthcare'
						listitem
							link Insurance, url='https://mentor.cam/categories/insurance'
						listitem
							link Media & Entertainment, url='https://mentor.cam/categories/media-and-entertainment'
						listitem
							link Real Estate, url='https://mentor.cam/categories/real-estate'
						listitem
							link Venture Capital, url='https://mentor.cam/categories/venture-capital'
			listitem
				list
					listitem
						StaticText Mentorcam
						list
							separator, orientation='horizontal'
							listitem
								link Articles, url='https://mentor.cam/articles'
							listitem
								link For mentors, url='https://mentor.cam/for-mentors'
							listitem
								link Company, url='https://mentor.cam/company'
							listitem
								link Careers, url='https://www.ycombinator.com/companies/mentorcam/jobs'
							listitem
								link Support, url='https://mentor.cam/support'
		link, url='https://mentor.cam/for-business'
			image
		StaticText 1:1 advice from otherwise
		StaticText inaccessible mentors
		link Mentorcam Youtube, url='https://www.youtube.com/@mentorcam'
			image
		link Mentorcam LinkedIn, url='https://www.linkedin.com/company/mentorcam'
			image
		link Mentorcam Instagram, url='https://www.instagram.com/mentor.cam/'
			image
		link Mentorcam Facebook, url='https://www.facebook.com/mentorcam'
			image
		paragraph
			StaticText ©
			StaticText 2025
			StaticText Mentorcam, Inc.
			StaticText —
			StaticText 2450 Colorado Ave. Suite 100E, Santa Monica, CA 90404
		list
			listitem
				link Terms of Service, url='https://mentor.cam/terms'
			listitem
				link Mentor Terms, url='https://mentor.cam/mentor-terms'
			listitem
				link Privacy Policy, url='https://mentor.cam/privacy'
			listitem
				link Cookie Policy, url='https://mentor.cam/cookie-policy'
	alert, atomic
```
</details>



```
RootWebArea Expert Startup Mentors | Unlock Your Potential | Mentorcam, focused, url='https://mentor.cam/'
	banner
		navigation
			link, url='https://mentor.cam/'
				image
```
<details><summary>Show more</summary>

```
			list
				listitem
					StaticText Browse
					image Find a Mentor, url='https://mentor.cam/_next/static/media/arrow-black-small-down.d77f3ecd.svg'
					list
						listitem
							list
								heading Expertise
								heading Industry
								link New Mentors, url='https://mentor.cam/search?categoryIds=new-mentor'
									heading New Mentors
				listitem
					image
					searchbox What advice are you looking for today?
			list
				listitem
					link For mentors, url='https://mentor.cam/for-mentors'
				listitem
					StaticText More
					image Find a Mentor, url='https://mentor.cam/_next/static/media/arrow-black-small-down.d77f3ecd.svg'
					list
						listitem
							link Articles, url='https://mentor.cam/articles'
						listitem
							link Company, url='https://mentor.cam/company'
						listitem
							link Careers, url='https://www.ycombinator.com/companies/mentorcam/jobs'
						listitem
							link Support, url='https://mentor.cam/support'
				listitem
				image Save $100 off on your first Mentorcam session, url='https://res.cloudinary.com/mentorcam/image/upload/ar_291:320,c_fill,f_auto,g_auto:face,q_100,w_320/v1/website/newsletter/newsletter_aol7lw.jpg'
				heading Thank you!
				paragraph
					StaticText Check your email, we've sent you a promo code.
				[1165] button Browse mentors, center=(1106,638), type=button
				listitem
					link Log in, url='https://mentor.cam/login'
				listitem
					link Sign up, url='https://mentor.cam/sign-up'
						button Sign up
	image
	heading Get advice from the world’s BEST mentors
	heading Book 1:1 calls with founders andleaders of the world’s best startups and brands.
	link Find a mentor, url='https://mentor.cam/search'
		button Find a mentor
	image Alexandra Zatarain, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/eo0NsIuHpXPKXsgcrNzMfRNbO7r1/images/-NFzvoPKAGSVDLE-4iqC.jpg'
	heading Alexandra Zatarain
	heading VP
		paragraph
	separator, orientation='horizontal'
	image Eight Sleep, url='https://res.cloudinary.com/mentorcam/image/upload/v1695102592/logos/oKcV58tiB5zXjewMIBJ9/files/-NefzCjW1J1wMJUB6610.svg.svg'
	image Chris Yeh, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/SDeGJdJ3hGUCw5EeNleQO6406Pw2/images/-MYu9atjX3CshcXuyTnP.jpg'
	heading Chris Yeh
	heading Partner
		paragraph
	separator, orientation='horizontal'
	image Blitzscaling Ventures, url='https://res.cloudinary.com/mentorcam/image/upload/v1695105994/logos/8SXFYBsn0L1r24Yfdl6Y/files/-NegBBLYOLgThNBrlfwU.svg.svg'
	image T Zhu, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/OLr4yMcDhoXzqjYuXLqeisBSlqX2/images/wEfjBsp1kJqi2ZOEMBfK.jpg'
	heading T Zhu
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Tellus, url='https://res.cloudinary.com/mentorcam/image/upload/v1681308442/logos/Hf7vDQ4zimBCEsxHonla/files/-NSpmhTNYPB9QbDvbqd8.svg.svg'
	image Michael Litt, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/071SzayHiobckWBc7BIEtlL24aA2/images/-O8c1SLrAj05ZUegOfNl.jpeg'
	heading Michael Litt
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Vidyard, url='https://res.cloudinary.com/mentorcam/image/upload/v1698793424/logos/WctOqFUxSxbZurYaLGy4/files/-Ni6yY-nECTlu-3rYPrw.svg.svg'
	image Roy Chung, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/axVGzXQhz2Sgbu6EejHThHIsCVp2/images/-Ne5gSUf_T8LaaVk83YK.jpg'
	heading Roy Chung
	heading Co-Founder
		paragraph
	separator, orientation='horizontal'
	image Apollo, url='https://res.cloudinary.com/mentorcam/image/upload/v1694120864/logos/4MYe5wGtr3yrRRiUMYV4/files/-NdlTDKkPcTw-h9N2xl5.svg.svg'
	image Jason Feifer, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/mVPEdDDBSNe8s6m0uFFj0Ej7Cvo2/images/-MbIkZ8WOGC2OWRJkANp.jpg'
	heading Jason Feifer
	heading Editor
		paragraph
	separator, orientation='horizontal'
	image Entrepreneur, url='https://res.cloudinary.com/mentorcam/image/upload/v1681302612/logos/cceXBeGD3RfQzr8MVfeC/files/-NSpRTETlzkIWJ5kheqK.svg.svg'
	image Robin Daniels, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_face:center,q_100,w_210/v1/user-profiles/xn9SoVfaBJc3ZqorFKu0UkkD4ps2/images/-NSp1-dkd4i12TETOsyg.jpg'
	heading Robin Daniels
	heading CMO
		paragraph
	separator, orientation='horizontal'
	image WeWork, url='https://res.cloudinary.com/mentorcam/image/upload/v1681943871/logos/tD0U2mfVCq2ajNdFba7e/files/-NTQedqTkHQHqJYuIxu_.svg.svg'
	separator, orientation='horizontal'
	paragraph
		StaticText TALK TO EXPERTS FROM
		StaticText THE WORLD’S TOP COMPANIES
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	image Apollo.io, url='https://mentor.cam/images/browse/apollo-io.svg'
	image Goodwater, url='https://mentor.cam/images/browse/goodwater.svg'
	image Y Combinator, url='https://mentor.cam/images/browse/y-combinator.svg'
	image AngelList, url='https://mentor.cam/images/browse/angellist.svg'
	image eightsleep, url='https://mentor.cam/images/browse/eightsleep.svg'
	image nurx, url='https://mentor.cam/images/browse/nurx.svg'
	image General Catalyst, url='https://mentor.cam/images/browse/general-catalyst.svg'
	image Matterport, url='https://mentor.cam/images/browse/matterport.svg'
	image Kleiner Perkins, url='https://mentor.cam/images/browse/kleiner-perkins.svg'
	image WeWork, url='https://mentor.cam/images/browse/wework.svg'
	image SNÖ Ventures, url='https://mentor.cam/images/browse/sno.svg'
	image Kohlberg Kravis Rcäerts, url='https://mentor.cam/images/browse/kkr.svg'
	image TikTok, url='https://mentor.cam/images/browse/tiktok.svg'
	image Reddit, url='https://mentor.cam/images/browse/reddit.svg'
	image Meta, url='https://mentor.cam/images/browse/meta.svg'
	image Google, url='https://mentor.cam/images/browse/google.svg'
	image Vouch, url='https://mentor.cam/images/browse/vouch.svg'
	image box, url='https://mentor.cam/images/browse/box.svg'
	image salesforce, url='https://mentor.cam/images/browse/salesforce.svg'
	image Sequoia Capital, url='https://mentor.cam/images/browse/sequoia.svg'
	image LinkedIn, url='https://mentor.cam/images/browse/linkedin.svg'
	image Instagram, url='https://mentor.cam/images/browse/instagram.svg'
	image Whole Foods, url='https://mentor.cam/images/browse/wholefoods.svg'
	image Bain Capital, url='https://mentor.cam/images/browse/bain.svg'
	image Thiel Capital, url='https://mentor.cam/images/browse/thiel.svg'
	image Microsoft, url='https://mentor.cam/images/browse/microsoft.svg'
	image Initialized Capital, url='https://mentor.cam/images/browse/initialized.svg'
	image Merrill, url='https://mentor.cam/images/browse/merrill.svg'
	image Samsung, url='https://mentor.cam/images/browse/samsung.svg'
	separator, orientation='horizontal'
	article
		heading Access to an elite network
		image
		paragraph
			StaticText Mentorcam’s network of elite founders and business professionals are available to you on-demand.
		image
		paragraph
			StaticText Whether you work with a specific expert or seek input from multiple advisors, your network just got instantly stronger.
		image
		paragraph
			StaticText All Mentorcam experts are carefully vetted and have proven track records as highly successful builders and operators.
		image Access to an elite network, url='https://res.cloudinary.com/mentorcam/image/upload/ar_528:436,c_lfill,f_auto,g_face:center,q_100,w_600/v1/website/home/Mentor_Network_Image_fm0ggw.png'
	separator, orientation='horizontal'
	article
		heading Talk face to face on 1:1 video calls
		image
		paragraph
			StaticText Talk in real time on 1:1 video calls and get the advice and direction you need, when you need it.
		image
		paragraph
			StaticText Share your challenges in a safe and confidential environment and carve out a path to success.
		image
		paragraph
			StaticText Whether you’re looking for help fundraising, acquiring users, or developing tactical sales skills, an expert is here to help.
		image Talk face to face on 1:1 video calls, url='https://res.cloudinary.com/mentorcam/image/upload/ar_699:470,c_lfill,f_auto,g_auto:face,q_100,w_800/v1/website/home/Face_to_Face_Video_Image_e4sms1.png'
	separator, orientation='horizontal'
	article
		heading Message your mentor
		image
		paragraph
			StaticText Send messages before and after your calls. Access your messages at any time from your desktop or mobile device.
		image
		paragraph
			StaticText Share an agenda with topics to discuss or upload files for review. Set milestones and discuss progress between calls.
		image
		paragraph
			StaticText Mentorcam keeps everything on one platform so your conversation is always safe and secure.
		image Message your mentor, url='https://res.cloudinary.com/mentorcam/image/upload/ar_578:443,c_lfill,f_auto,g_face:center,q_100,w_650/v1/website/home/Message_Mentor_Image_avggpy.png'
	article
		image Co-founder, Motiv, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/3yTcftWWFg9VwGoOyG9B/images/-N_4sOF3LqZGhpd7zuFe.jpg'
		heading “I’d give Mentorcam five out of five stars. I've been very impressed.”
		heading Mason Fuerst
		heading Co-founder, Motiv
		link Read story, url='https://mentor.cam/articles/mason-fuerst'
			button Read story
	article
		image Founder, Felvin, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/sRva2AR8AuThaefvF9vb/images/-N_4tzduE1_GBRUBL2YS.jpg'
		heading “I would not have raised $300K if it wasn’t for my mentor.”
		heading Harsh Gupta
		heading Founder, Felvin
		link Read story, url='https://mentor.cam/articles/raise-money-startup-or-business'
			button Read story
	article
		image Founder, InvestLink Social, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/74KNbacbZjksQC1ZnWg9/images/-N_4u7Jqk7FEtupC91fa.jpg'
		heading “We've been able to hyper speed our pre-seed round.”
		heading Christian Durfee
		heading Founder, InvestLink Social
		link Read story, url='https://mentor.cam/articles/christian-durfee'
			button Read story
	article
		image Co-founder, Happyrobot.ai, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/tUjHzfp6MmB1O04iv9eg/images/-N_4uFd3h7dbjiFGdhjj.jpg'
		heading “My mentors helped me deep dive into the mind of the customer.”
		heading Pablo Palafox
		heading Co-founder, Happyrobot.ai
		link Read story, url='https://mentor.cam/articles/pablo-palafox'
			button Read story
	article
		image Co-founder, Empower Sleep, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/BIxzVebcLYJvQ4xVPNG9/images/-N_4uYlZhKCSDTuC5LtM.jpg'
		heading “I'd walk out of mentorship sessions feeling much better about building.”
		heading Sagar Chopra
		heading Co-founder, Empower Sleep
		link Read story, url='https://mentor.cam/articles/sagar-chopra'
			button Read story
	article
		image Founder, Angelos Georgakis Executive Coaching, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/c5CnDzjqU5TCeEo8iQSB/images/-N_4ugwsXvM0wKruBesN.jpg'
		heading “How have you not signed up yet?”
		heading Angelos Georgakis
		heading Founder, Angelos Georgakis Executive Coaching
		link Read story, url='https://mentor.cam/articles/angelos-georgakis'
			button Read story
	article
		image Founder, Creativo Platform, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/XhL6fku7GH40Um42LKCm/images/-N_4tXecOSjuPFlz5Lk1.jpg'
		heading “Every mentor I've spoken to has helped us go further a lot faster.”
		heading Clint Rogers
		heading Founder, Creativo Platform
		link Read story, url='https://mentor.cam/articles/clint-rogers'
			button Read story
	article
		image Founder, VRRB Labs, url='https://res.cloudinary.com/mentorcam/image/upload/ar_1:1,c_fill,f_auto,g_auto:face,q_100,r_max,w_144/v1/testimonials/U0vFCAYMxpzVkMfSFGdl/images/-N_4tmaAmyXGalw1yiGE.jpg'
		heading “We ended up raising $1.42 million for our company.”
		heading Andrew Smith
		heading Founder, VRRB Labs
		link Read story, url='https://mentor.cam/articles/andrew-smith'
			button Read story
	heading Book a mentor for a 1:1 live call and get custom advice tailored to you from the world’s best startup founders and business leaders
	button B2B Software
	button Consumer Software
	button Artificial Intelligence
	button Branding
	button E-commerce & CPG
	button Fundraising
	button Venture Capital
	link Michael Litt Product & Sales Advice Michael Litt Co-Founder & CEO - Vidyard GTM & Generative AI Expert Vidyard, url='https://mentor.cam/michaellitt'
		image Michael Litt, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/071SzayHiobckWBc7BIEtlL24aA2/images/-O8c1SLrAj05ZUegOfNl.jpeg'
		heading Product & Sales Advice
		heading Michael Litt
		heading Co-Founder & CEO - Vidyard GTM & Generative AI Expert
		separator, orientation='horizontal'
		image Vidyard, url='https://res.cloudinary.com/mentorcam/image/upload/v1698793424/logos/WctOqFUxSxbZurYaLGy4/files/-Ni6yY-nECTlu-3rYPrw.svg.svg'
	link Derek Edwards Gen AI Engineering Advice Derek Edwards VP AI Technology - Elevance Health Gen AI Engineering Expert Elevance, url='https://mentor.cam/derekedwards'
		image Derek Edwards, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/kgWqasE0XdWmg7RhkMDWEAtj2Ih1/images/-NiPQIDS0TgXGqeIXS9C.jpeg'
		heading Gen AI Engineering Advice
		heading Derek Edwards
		heading VP AI Technology - Elevance Health Gen AI Engineering Expert
		separator, orientation='horizontal'
		image Elevance, url='https://res.cloudinary.com/mentorcam/image/upload/v1692027482/logos/Yj7EjKwuRurp0fPe2fAY/files/-NbogacZ46n3F997ph-2.svg.svg'
	link Josh Auffret Marketing Expert Josh Auffret Head of UX Programs & Operations - Google Product Marketing Expert Google, url='https://mentor.cam/joshauffret'
		image Josh Auffret, url='https://res.cloudinary.com/mentorcam/image/upload/ar_310:360,c_fill,f_auto,g_face:center,q_100,w_310/v1/user-profiles/rptSDb1KAxdayDtkShO0CZSB9Bq2/images/-NlVESOg3LcDuy_TIkXU.jpg'
		heading Marketing Expert
		heading Josh Auffret
		heading Head of UX Programs & Operations - Google Product Marketing Expert
		separator, orientation='horizontal'
		image Google, url='https://res.cloudinary.com/mentorcam/image/upload/v1682025135/logos/7C5Eg3yRWHaAKixmlMXB/files/-NTVVeLZdlV-lyhezkMz.svg.svg'
	link Show more mentors, url='https://mentor.cam/categories/b2b-software'
	heading Sign up and access an elite network of world-class experts
	paragraph
		StaticText Book 1:1 calls and solve your most pressing challenges with the help of elite experts and industry leaders.
	link Create an account, url='https://mentor.cam/sign-up'
		button Create an account
	contentinfo
		list
			listitem
				list
					StaticText Expertise
					separator, orientation='horizontal'
					list
						listitem
							link B2B Sales, url='https://mentor.cam/categories/b2b-sales'
						listitem
							link B2C Sales, url='https://mentor.cam/categories/b2c-sales'
						listitem
							link Bootstrapping, url='https://mentor.cam/categories/bootstrapping'
						listitem
							link Branding, url='https://mentor.cam/categories/branding'
						listitem
							link Financial Planning, url='https://mentor.cam/categories/financial-planning'
						listitem
							link Fundraising, url='https://mentor.cam/categories/fundraising'
						listitem
							link Growth Marketing, url='https://mentor.cam/categories/growth-marketing'
						listitem
							link Manufacturing, url='https://mentor.cam/categories/manufacturing'
						listitem
							link People & Hiring, url='https://mentor.cam/categories/people-and-hiring'
						listitem
							link Product & Engineering, url='https://mentor.cam/categories/product-and-engineering'
						listitem
							link Product Marketing, url='https://mentor.cam/categories/product-marketing'
						listitem
							link Public Relations, url='https://mentor.cam/categories/public-relations'
						listitem
							link SEM & SEO, url='https://mentor.cam/categories/sem-seo'
						listitem
							link Social Media, url='https://mentor.cam/categories/social-media-marketing'
						listitem
							link Strategy & Operations, url='https://mentor.cam/categories/strategy-and-operations'
					StaticText Industry
					separator, orientation='horizontal'
					list
						listitem
							link Artificial Intelligence, url='https://mentor.cam/categories/artificial-intelligence'
						listitem
							link B2B Services, url='https://mentor.cam/categories/b2b-services'
						listitem
							link B2B Software, url='https://mentor.cam/categories/b2b-software'
						listitem
							link Consumer Products, url='https://mentor.cam/categories/consumer-hardware'
						listitem
							link Consumer Software, url='https://mentor.cam/categories/consumer-software'
						listitem
							link E-commerce & CPG, url='https://mentor.cam/categories/e-commerce-and-cpg'
						listitem
							link Education, url='https://mentor.cam/categories/education'
						listitem
							link Fashion & Apparel, url='https://mentor.cam/categories/fashion'
						listitem
							link Fintech, url='https://mentor.cam/categories/fintech'
						listitem
							link Food & Beverage, url='https://mentor.cam/categories/food-beverage'
						listitem
							link Gaming, url='https://mentor.cam/categories/gaming'
						listitem
							link Healthcare, url='https://mentor.cam/categories/healthcare'
						listitem
							link Insurance, url='https://mentor.cam/categories/insurance'
						listitem
							link Media & Entertainment, url='https://mentor.cam/categories/media-and-entertainment'
						listitem
							link Real Estate, url='https://mentor.cam/categories/real-estate'
						listitem
							link Venture Capital, url='https://mentor.cam/categories/venture-capital'
			listitem
				list
					listitem
						StaticText Mentorcam
						list
							separator, orientation='horizontal'
							listitem
								link Articles, url='https://mentor.cam/articles'
							listitem
								link For mentors, url='https://mentor.cam/for-mentors'
							listitem
								link Company, url='https://mentor.cam/company'
							listitem
								link Careers, url='https://www.ycombinator.com/companies/mentorcam/jobs'
							listitem
								link Support, url='https://mentor.cam/support'
		link, url='https://mentor.cam/for-business'
			image
		StaticText 1:1 advice from otherwise
		StaticText inaccessible mentors
		link Mentorcam Youtube, url='https://www.youtube.com/@mentorcam'
			image
		link Mentorcam LinkedIn, url='https://www.linkedin.com/company/mentorcam'
			image
		link Mentorcam Instagram, url='https://www.instagram.com/mentor.cam/'
			image
		link Mentorcam Facebook, url='https://www.facebook.com/mentorcam'
			image
		paragraph
			StaticText ©
			StaticText 2025
			StaticText Mentorcam, Inc.
			StaticText —
			StaticText 2450 Colorado Ave. Suite 100E, Santa Monica, CA 90404
		list
			listitem
				link Terms of Service, url='https://mentor.cam/terms'
			listitem
				link Mentor Terms, url='https://mentor.cam/mentor-terms'
			listitem
				link Privacy Policy, url='https://mentor.cam/privacy'
			listitem
				link Cookie Policy, url='https://mentor.cam/cookie-policy'
	alert, atomic
```
</details>

**Reasoning for action:** I identified the button labeled 'Submit' associated with the newsletter form. By clicking this button, I perform the action necessary to submit the user's email address, which is a critical step toward achieving the stated user story of subscribing to the newsletter. This action directly satisfies the condition where the user is supposed to submit their email address and initiates the process that will ultimately display a confirmation message indicating that a promo code has been sent to their email.

**Action:** click(155) # Click on the Submit button to submit the email for the newsletter.

**Change Description:** After clicking the Submit button, the browser now displays a confirmation message in the newsletter section, indicating 'Thank you! Check your email, we've sent you a promo code.' The email input has been replaced, and a new button 'Browse mentors' has appeared.

**Screenshot before:****Screenshot after:**---


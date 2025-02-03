# Task

**User Story for Appointment Booking with Apple Watch**

As a health-conscious individual,
I book an appointment using my Apple Watch as a wearable option,
so that I can receive personalized health insights and care tailored to my data.

**Success definition:** Given I am on the Empirical Health website and have clicked on 'Book an appointment'
When I choose the 'Apple Watch' option in the appointment booking process
Then I should see a confirmation that my appointment is scheduled using the Apple Watch for personalized health insights.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.empirical.health/

https://app.empirical.health/?goal=General

**Content (before/after):** 

```
RootWebArea Empirical Health: The future of primary care, focused, url='https://www.empirical.health/'
	navigation
		[32] link, center=(640,46), url='https://www.empirical.health/'
			image
		checkbox, checked='false'
```
<details><summary>Show more</summary>

```
		[41] link Book an appointment, center=(1111,46), url='https://app.empirical.health/?goal=General'
		[42] link Download, center=(1273,46), url='https://apps.apple.com/app/apple-store/id6449271489?pt=124999797&ct=Ads:ProgramPage&mt=8'
			image
	main
		image
		image, url='https://www.empirical.health/_astro/hero1.CgngR2s1_249PE0.webp'
		image, url='https://www.empirical.health/_astro/hero2.DD3gglpv_ZznkLy.webp'
		image, url='https://www.empirical.health/_astro/hero3.Mo4_KpQC_ZPQFLN.webp'
		image, url='https://www.empirical.health/_astro/hero4.B10XS-Vb_2v87Pb.webp'
		image, url='https://www.empirical.health/_astro/hero5.BTg4kam2_ZIQBKl.webp'
		image, url='https://www.empirical.health/_astro/hero6.sKYQRdC2_14ikpy.webp'
		StaticText Healthcare
		StaticText that
		StaticText revolves
		StaticText around
		StaticText you
		paragraph
			StaticText We’re a modern approach to whole-person care, combining a board-certified doctor with advanced monitoring using devices like Apple Watch.
		[69] link Download for iOS, center=(820,536), url='https://apps.apple.com/app/apple-store/id6449271489?pt=124999797&ct=Ads:ProgramPage&mt=8'
			image
		[71] link Book an appointment, center=(1082,536), url='https://app.empirical.health/?goal=General'
			image
		image
		StaticText 99%
		StaticText of
		StaticText your
		StaticText health
		StaticText is
		StaticText defined
		StaticText outside
		StaticText the
		StaticText doctor’s
		StaticText office.
		StaticText Empirical
		StaticText helps
		StaticText you
		StaticText manage
		StaticText it.
		StaticText Empirical pairs wearable data with real doctors to easily manage your day-to-day health, providing biometric insights, physical therapy, nutrition guidance, and more– all while still receiving the traditional care you’re used to.
		link Book an appointment, url='https://app.empirical.health/?goal=General'
			image
		image
		StaticText Receive
		StaticText customized
		StaticText care
		StaticText plans,
		StaticText no
		StaticText matter
		StaticText how
		StaticText complex
		StaticText your
		StaticText condition.
		StaticText Using cutting-edge generative AI, Empirical intelligently understands your condition and pairs it with your biometric data to develop a customized care plan, regardless of the condition you’re dealing with.
		link Learn more, url='https://apps.apple.com/app/apple-store/id6449271489?pt=124999797&ct=Ads:ProgramPage&mt=8'
			image
		image
		image
		StaticText The
		StaticText best
		StaticText part?
		StaticText You
		StaticText can
		StaticText get
		StaticText started
		StaticText in
		StaticText four
		StaticText steps.
		image
		paragraph
			StaticText Step
			StaticText 1
		paragraph
			StaticText Download the app
		paragraph
			StaticText Create an account and connect your wearable data
		image
		paragraph
			StaticText Step
			StaticText 2
		paragraph
			StaticText Receive a care plan
		paragraph
			StaticText Your health metrics are used to generate a custom care plan
		image
		paragraph
			StaticText Step
			StaticText 3
		paragraph
			StaticText Meet your doctor
		paragraph
			StaticText Schedule an appointment with your doctor right inside the app
		image
		paragraph
			StaticText Step
			StaticText 4
		paragraph
			StaticText Follow up in the app
		paragraph
			StaticText Chat with your doctor about the next steps in your care plan
		StaticText Covered
		StaticText by
		StaticText insurance.
		StaticText Available
		StaticText in
		StaticText 30
		StaticText states.
		StaticText Available
		StaticText in
		list
			listitem
				image
				StaticText Alabama
			listitem
				image
				StaticText Arkansas
			listitem
				image
				StaticText Arizona
			listitem
				image
				StaticText California
			listitem
				image
				StaticText Colorado
			listitem
				image
				StaticText Connecticut
			listitem
				image
				StaticText Florida
			listitem
				image
				StaticText Georgia
			listitem
				image
				StaticText Hawaii
			listitem
				image
				StaticText Iowa
			listitem
				image
				StaticText Indiana
			listitem
				image
				StaticText Kentucky
			listitem
				image
				StaticText Massachusetts
			listitem
				image
				StaticText Maryland
			listitem
				image
				StaticText Michigan
			listitem
				image
				StaticText Minnesota
			listitem
				image
				StaticText Missouri
			listitem
				image
				StaticText North Carolina
			listitem
				image
				StaticText New Jersey
			listitem
				image
				StaticText New Mexico
			listitem
				image
				StaticText Nevada
			listitem
				image
				StaticText New York
			listitem
				image
				StaticText Ohio
			listitem
				image
				StaticText Oklahoma
			listitem
				image
				StaticText Oregon
			listitem
				image
				StaticText Pennsylvania
			listitem
				image
				StaticText Tennessee
			listitem
				image
				StaticText Texas
			listitem
				image
				StaticText Utah
			listitem
				image
				StaticText Virginia
			listitem
				image
				StaticText Washington
			listitem
				image
				StaticText Wisconsin
		StaticText We
		StaticText accept
		list
			listitem
				image
				StaticText Anthem / Elevance
			listitem
				image
				StaticText Aetna
			listitem
				image
				StaticText Medicare (in Florida)
			listitem
				image
				StaticText HealthNet
			listitem
				image
				StaticText United Healthcare
			listitem
				image
				StaticText Blue Cross Blue Shield*
		image
		image
		StaticText No
		StaticText insurance?
		StaticText No
		StaticText problem.
		paragraph
			StaticText For individuals without health insurance, we offer affordable subscription packages from 6 months to a year.
		tablist, orientation='horizontal'
			tab 6 months, selected=True
			tab 12 months, selected=False
		tabpanel
			paragraph
				StaticText $
				StaticText 124.99
			separator, orientation='horizontal'
			link Subscribe for 6 months, url='https://buy.stripe.com/aEU7w6eT51Kc3iE3cf'
				image
		image, url='https://www.empirical.health/_astro/hero1.CgngR2s1_Z15aec8.webp'
		image, url='https://www.empirical.health/_astro/hero2.DD3gglpv_Z1VMpQk.webp'
		image, url='https://www.empirical.health/_astro/hero3.Mo4_KpQC_Z1vMYdY.webp'
		heading Join 2k+ people already on their way to better health.
		link Download for iOS, url='https://apps.apple.com/app/apple-store/id6449271489?pt=124999797&ct=Ads:ProgramPage&mt=8'
			image
		image, url='https://www.empirical.health/_astro/hero4.B10XS-Vb_11D9lU.webp'
		image, url='https://www.empirical.health/_astro/hero5.BTg4kam2_22e3vf.webp'
		image, url='https://www.empirical.health/_astro/hero6.sKYQRdC2_2k3z2D.webp'
	contentinfo
		link, url='https://www.empirical.health/'
			image
		paragraph
			StaticText Product
		list
			listitem
				link Download for iOS, url='https://apps.apple.com/app/apple-store/id6449271489?pt=124999797&ct=Ads:ProgramPage&mt=8'
			listitem
				link Download Sleep Tracker, url='https://apps.apple.com/us/app/empirical-sleep-apnea-care/id1623615785'
			listitem
				link Support, url='https://help.empirical.health/'
		paragraph
			StaticText Use Cases
		list
			listitem
				link POTS, url='https://www.empirical.health/pots'
			listitem
				link Deep Sleep, url='https://www.empirical.health/deep-sleep'
			listitem
				link Sleep apnea testing, url='https://www.empirical.health/apple-watch-sleep-apnea'
		paragraph
			StaticText Company
		list
			listitem
				link Blog, url='https://www.empirical.health/blog'
			listitem
				link Contact, url='https://www.empirical.health/contact'
		paragraph
			StaticText Legal
		list
			listitem
				link Privacy Policy, url='https://www.empirical.health/privacy'
			listitem
				link Terms of Service, url='https://www.empirical.health/terms'
			listitem
				link HIPAA Privacy Notice, url='https://www.empirical.health/hipaa-privacy'
			listitem
				link Telehealth Informed Consent, url='https://www.empirical.health/telehealth-informed-consent'
		paragraph
			StaticText Breathing Metrics
		list
			listitem
				link Breaths per min, url='https://www.empirical.health/metrics/breaths-min'
			listitem
				link Oxygen, url='https://www.empirical.health/metrics/oxygen'
			listitem
				link Sleeping blood oxygen, url='https://www.empirical.health/metrics/sleep-oxygen'
		paragraph
			StaticText Exercise Metrics
		list
			listitem
				link Activity, url='https://www.empirical.health/metrics/activity'
			listitem
				link VO2Max, url='https://www.empirical.health/metrics/vo2-max'
		paragraph
			StaticText Heart Metrics
		list
			listitem
				link Heart rate recovery (cardio recovery), url='https://www.empirical.health/metrics/heart-rate-recovery'
			listitem
				link Heart rate, url='https://www.empirical.health/metrics/heart-rate'
			listitem
				link Heart rate variability, url='https://www.empirical.health/metrics/hrv'
			listitem
				link Resting heart rate, url='https://www.empirical.health/metrics/rhr'
		paragraph
			StaticText Sleep Metrics
		list
			listitem
				link Deep sleep, url='https://www.empirical.health/metrics/deep-sleep-percent'
			listitem
				link Sleep duration, url='https://www.empirical.health/metrics/sleep-duration-mins'
			listitem
				link REM sleep, url='https://www.empirical.health/metrics/rem-sleep-percent'
```
</details>



```
RootWebArea Book an Appointment, focused, url='https://app.empirical.health/?goal=General'
	image
	StaticText Empirical Health
	StaticText Doctor appointment
	StaticText Do you own one of these wearables?
```
<details><summary>Show more</summary>

```
	image
	[59] div, center=(960,362), inner_text=Continue
	[55] div, center=(1193,268), inner_text=None
	[53] div, center=(1111,268), inner_text=Other
	[51] div, center=(1029,268), inner_text=Fitbit
	[49] div, center=(945,268), inner_text=Garmin
	[47] div, center=(853,268), inner_text=Samsung
	[45] div, center=(745,268), inner_text=Apple Watch
	StaticText All information you share is secure and confidential.
```
</details>

**Reasoning for action:** By clicking on the 'Book an appointment' link, I am directed to the appointment booking interface where I can select the 'Apple Watch' option. This step is crucial as it initiates the process of booking an appointment, which is necessary to meet the user story of receiving personalized health insights using their wearable data.

**Action:** click('41') # Click on the 'Book an appointment' link to explore appointment booking options.

**Change Description:** After clicking on the 'Book an appointment' link, the browser navigated to a new page titled 'Book an Appointment' where users can see options related to wearable devices for scheduling a doctor appointment, replacing the previous content about primary care.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://app.empirical.health/?goal=General

https://app.empirical.health/?goal=General

**Content (before/after):** 

```
RootWebArea Book an Appointment, focused, url='https://app.empirical.health/?goal=General'
	image
	StaticText Empirical Health
	StaticText Doctor appointment
	StaticText Do you own one of these wearables?
```
<details><summary>Show more</summary>

```
	image
	[59] div, center=(960,362), inner_text=Continue
	[55] div, center=(1193,268), inner_text=None
	[53] div, center=(1111,268), inner_text=Other
	[51] div, center=(1029,268), inner_text=Fitbit
	[49] div, center=(945,268), inner_text=Garmin
	[47] div, center=(853,268), inner_text=Samsung
	[45] div, center=(745,268), inner_text=Apple Watch
	StaticText All information you share is secure and confidential.
```
</details>



```
RootWebArea Book an Appointment, focused, url='https://app.empirical.health/?goal=General'
	image
	StaticText Empirical Health
	StaticText Doctor appointment
	StaticText Do you own one of these wearables?
```
<details><summary>Show more</summary>

```
	generic Continue, focused
	image
	[59] div, center=(960,362), inner_text=Continue
	[55] div, center=(1193,268), inner_text=None
	[53] div, center=(1111,268), inner_text=Other
	[51] div, center=(1029,268), inner_text=Fitbit
	[49] div, center=(945,268), inner_text=Garmin
	[47] div, center=(853,268), inner_text=Samsung
	[45] div, center=(745,268), inner_text=Apple Watch
	StaticText All information you share is secure and confidential.
```
</details>

**Reasoning for action:** I clicked on the 'Continue' button because it allows me to advance the appointment booking process. This is essential for enabling the user to select the 'Apple Watch' option for their appointment, which aligns with their goal of receiving personalized health insights tied to their wearable data. By clicking 'Continue,' I am actively moving closer to completing the booking with the desired wearable option.

**Action:** click('59') # Click on the 'Continue' button to proceed with the appointment booking process.

**Change Description:** After clicking the 'Continue' button, the button is now indicated as generic and focused, suggesting that the action triggered a change in the button's state while the rest of the content remains unchanged, indicating the user has moved forward in the appointment booking process.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://app.empirical.health/?goal=General

https://app.empirical.health/?goal=General

**Content (before/after):** 

```
RootWebArea Book an Appointment, focused, url='https://app.empirical.health/?goal=General'
	image
	StaticText Empirical Health
	StaticText Doctor appointment
	StaticText Do you own one of these wearables?
```
<details><summary>Show more</summary>

```
	generic Continue, focused
	image
	[59] div, center=(960,362), inner_text=Continue
	[55] div, center=(1193,268), inner_text=None
	[53] div, center=(1111,268), inner_text=Other
	[51] div, center=(1029,268), inner_text=Fitbit
	[49] div, center=(945,268), inner_text=Garmin
	[47] div, center=(853,268), inner_text=Samsung
	[45] div, center=(745,268), inner_text=Apple Watch
	StaticText All information you share is secure and confidential.
```
</details>



```
RootWebArea Book an Appointment, focused, url='https://app.empirical.health/?goal=General'
	image
	StaticText Empirical Health
	StaticText Doctor appointment
	StaticText Do you own one of these wearables?
```
<details><summary>Show more</summary>

```
	generic Apple Watch, focused
	image
	[67] div, center=(960,362), inner_text=Continue
	[55] div, center=(1193,268), inner_text=None
	[53] div, center=(1111,268), inner_text=Other
	[51] div, center=(1029,268), inner_text=Fitbit
	[49] div, center=(945,268), inner_text=Garmin
	[47] div, center=(853,268), inner_text=Samsung
	[45] div, center=(745,268), inner_text=Apple Watch
	StaticText All information you share is secure and confidential.
```
</details>

**Reasoning for action:** By clicking on the 'Apple Watch' option, I am indicating my choice of wearable device for the appointment booking. This step is essential as it moves me forward in the process of scheduling the appointment specifically tailored to my health data derived from the Apple Watch. Once selected, I should expect the webpage to update, allowing me to proceed to the next step in confirming my appointment.

**Action:** click('45') # Click on the 'Apple Watch' option to select it.

**Change Description:** After clicking on the 'Apple Watch' option, the state of the browser reflected the selection with 'Apple Watch' now receiving focus, indicating it has been chosen as the wearable option.

**Screenshot before:****Screenshot after:**---


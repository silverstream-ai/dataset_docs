# Task

**User Story for Sign-Up Process**

As a prospective user of Emerge Tools,
I sign up for an account,
so that I can start utilizing the mobile development tools offered by Emerge Tools.

**Success definition:** Given I am on the Emerge Tools homepage and have clicked the 'Get started' button
When I fill in my email address and click 'Continue' on the sign-up page
Then I should see a page where I can create a password for my new account.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.emergetools.com/

https://auth.emergetools.com/u/signup/identifier?state=hKFo2SA2TFVfaTR4R05fVDFIMkZPMU40a0dXWmhubm1qSVlnRqFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHR0RHRodmtuUDN0WVloc0VTSW5xaUR6cnE4cW4yY0pfo2NpZNkgRjhuRXhxYlVZZ1JDOFE3QVdPOFAwTXhvbjUwUG1LUXo

**Content (before/after):** 

```
RootWebArea Supercharge your mobile apps | Emerge Tools, focused, url='https://www.emergetools.com/'
	banner
		navigation
			[79] link Go to homepage, center=(317,32), url='https://www.emergetools.com/'
			list
```
<details><summary>Show more</summary>

```
				listitem
					[84] link Blog, center=(400,32), url='https://www.emergetools.com/blog'
				listitem
					[86] link Documentation, center=(520,32), url='https://docs.emergetools.com/docs/'
				listitem
					[88] link Pricing, center=(649,32), url='https://www.emergetools.com/pricing'
				listitem
					[90] link Case Studies, center=(770,32), url='https://www.emergetools.com/case-studies'
				listitem
					[92] link Careers, center=(895,32), url='https://www.emergetools.com/careers'
			[97] button Contact us, center=(1444,32)
				button Contact us
			[104] button Login, center=(1586,32)
				link Login, url='https://www.emergetools.com/api/auth/login?returnTo=/'
	main
		Canvas
		heading Join the future of mobile development
		paragraph
			StaticText Emerge Tools helps devs build
			StaticText better
			StaticText ,
			StaticText faster
			StaticText faster
			StaticText faster
			StaticText faster
			StaticText faster
			StaticText apps
		[141] link Get started, center=(960,335), url='https://www.emergetools.com/api/auth/signup?returnTo=/'
			button Get started
		[146] link 2-minute overview, center=(960,396), url='https://www.youtube.com/watch?v=mYamLXXiW2s'
		[152] link Size Analysis Size Analysis Monitor & reduce app size, center=(442,571), inner_text=Size Analysis

Monitor & reduce app size, url='https://www.emergetools.com/#size-analysis'
			image Size Analysis, url='https://www.emergetools.com/_next/image?url=%2Fimages%2Fhomepage%2Fhero%2Fsize-analysis.png&w=384&q=100&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
			paragraph
			paragraph
		[157] link Snapshots Snapshots Build UIs with confidence, center=(649,571), inner_text=Snapshots

Build UIs with confidence, url='https://www.emergetools.com/#snapshots'
			image Snapshots, url='https://www.emergetools.com/_next/image?url=%2Fimages%2Fhomepage%2Fhero%2Fsnapshots.png&w=384&q=100&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
			paragraph
			paragraph
		[162] link Reaper Reaper Find & kill dead code, center=(856,571), inner_text=Reaper

Find & kill dead code, url='https://www.emergetools.com/#reaperai'
			image Reaper, url='https://www.emergetools.com/_next/image?url=%2Fimages%2Fhomepage%2Fhero%2Freaperai.png&w=384&q=100&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
			paragraph
			paragraph
		[167] link Performance Analysis Performance Analysis Prevent startup regressions, center=(1064,571), inner_text=Performance Analysis

Prevent startup regressions, url='https://www.emergetools.com/#performance-analysis'
			image Performance Analysis, url='https://www.emergetools.com/_next/image?url=%2Fimages%2Fhomepage%2Fhero%2Fperformance-analysis.png&w=384&q=100&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
			paragraph
			paragraph
		[172] link Launch Booster Launch Booster Improve app startup time, center=(1271,571), inner_text=Launch Booster

Improve app startup time, url='https://www.emergetools.com/#launch-booster'
			image Launch Booster, url='https://www.emergetools.com/_next/image?url=%2Fimages%2Fhomepage%2Fhero%2Flaunch-booster.png&w=384&q=100&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
			paragraph
			paragraph
		[177] link Build Distribution Build Distribution Share builds with your team, center=(1478,571), inner_text=Build Distribution

Share builds with your team, url='https://www.emergetools.com/#build-distribution'
			image Build Distribution, url='https://www.emergetools.com/_next/image?url=%2Fimages%2Fhomepage%2Fhero%2Fbuild-distribution.png&w=384&q=100&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
			paragraph
			paragraph
		paragraph
			StaticText Trusted by the best mobile teams
		[186] link OpenAI Read case study, center=(526,846), inner_text=Read case study, title=Read case study, url='https://www.emergetools.com/blog/posts/openai-on-mobile-development-previews-and-snapshot-testing'
			image OpenAI, url='https://www.emergetools.com/images/homepage/hero/openai.svg'
			paragraph
		[190] link Spotify Read case study, center=(816,846), inner_text=Read case study, title=Read case study, url='https://engineering.atspotify.com/2023/11/the-what-why-and-how-of-mastering-app-size/'
			image Spotify, url='https://www.emergetools.com/images/homepage/hero/spotify.svg'
			paragraph
		[194] link Duolingo Read case study, center=(1104,846), inner_text=Read case study, title=Read case study, url='https://blog.duolingo.com/emerge-tools-reaper/'
			image Duolingo, url='https://www.emergetools.com/images/homepage/hero/duolingo.svg'
			paragraph
		[198] link Square Read case study, center=(1394,846), inner_text=Read case study, title=Read case study, url='https://developer.squareup.com/blog/keeping-up-with-android-app-size-growth/'
			image Square, url='https://www.emergetools.com/images/homepage/hero/square.svg'
			paragraph
		heading Discover the unknown
		paragraph
			StaticText Go in depth with all Emerge Tools has to offer
		image Background main color, url='https://www.emergetools.com/images/homepage/products/size-analysis/background-main-color.svg'
		image Background meteors, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fbackground-meteors.ed3616d7.png&w=256&q=75&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Size Analysis, url='https://www.emergetools.com/_next/image?url=%2Fimages%2Fhomepage%2Fhero%2Fsize-analysis.png&w=640&q=100&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		heading Size Analysis
		heading Monitor & reduce app size
		link Read docs, url='https://docs.emergetools.com/docs/what-is-app-size'
			image
		link Explore more, url='https://www.emergetools.com/explore'
			image
		link Live demo, url='https://www.emergetools.com/app/example/ios/wikipedia'
			image
		button Get alerted about size changes on pull requests Prevent unwanted changes with size thresholds
			paragraph
			paragraph
		button Actionable insights to reduce size Automated analysis provides instant results
			paragraph
			paragraph
		button Track app size over time Dashboards help keep you & your team on top of size
			paragraph
			paragraph
		button Understand your app like never before Visualize the size of code, assets, & localizations
			paragraph
			paragraph
		button Compare against competitors Use AI to see how your app stacks up to the competition
			paragraph
			paragraph
		image Get alerted about size changes on pull requests, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F1.d448ff83.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Actionable insights to reduce size, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F2.ad5c693f.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Track app size over time, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F3.3440cec6.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Understand your app like never before, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F4.b59d1760.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Compare against competitors, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F5.3e76b2fb.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Background main color, url='https://www.emergetools.com/images/homepage/products/snapshots/background-main-color.svg'
		image Background meteors, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fbackground-meteors.ed3616d7.png&w=256&q=75&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Snapshots, url='https://www.emergetools.com/_next/image?url=%2Fimages%2Fhomepage%2Fhero%2Fsnapshots.png&w=640&q=100&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		heading Snapshots
		heading Build UIs with confidence
		link Read docs, url='https://docs.emergetools.com/docs/snapshot-testing'
			image
		link Quick explainer, url='https://www.youtube.com/watch?v=JbPJRq1ZXm0&ab_channel=EmergeTools'
			image
		link Read a case study, url='https://joinhandshake.com/blog/our-team/effortless-ios-snapshot-testing-using-emerge-tools/'
			image
		button Stop visual regressions in their tracks See how your UI changes directly on your pull request
			paragraph
			paragraph
		button The best tests are the ones you don’t have to write We take advantage of SwiftUI & Jetpack Compose to automatically generate previews
			paragraph
			paragraph
		button Automatic storage Say 👋 to painful git management for snapshot images
			paragraph
			paragraph
		button Web platform for easy snapshot diff examination Search, filter, sort by the snapshots with the biggest diff %
			paragraph
			paragraph
		button Visualize the history of every component See how each component has changed over time
			paragraph
			paragraph
		image Stop visual regressions in their tracks, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F1.c07d658a.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image The best tests are the ones you don’t have to write, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F2.d5fe7e36.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Automatic storage, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F3.c05ee2a9.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Web platform for easy snapshot diff examination, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F4.92d2c0ce.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Visualize the history of every component, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F5.2f0d1f0d.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Background main color, url='https://www.emergetools.com/images/homepage/products/reaperai/background-main-color.svg'
		image Background meteors, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fbackground-meteors.ed3616d7.png&w=256&q=75&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Reaper, url='https://www.emergetools.com/_next/image?url=%2Fimages%2Fhomepage%2Fhero%2Freaperai.png&w=640&q=100&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		heading Reaper
		heading Automatically kill dead code
		link Read docs, url='https://docs.emergetools.com/docs/reaper'
			image
		link Read a case study, url='https://blog.duolingo.com/emerge-tools-reaper/'
			image
		link How it works, url='https://www.emergetools.com/blog/posts/dead-code-detection-with-reaper'
			image
		button Dynamic runtime analysis Find dead code based on production usage
			paragraph
			paragraph
		button Bye, bye forgotten feature flags Clean up existing technical debt using Reaper
			paragraph
			paragraph
		button Less is more Deleting unused code has powerful downstream technical impacts from fewer bugs to improved startup time
			paragraph
			paragraph
		image Dynamic runtime analysis, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F1.9d9e7c1f.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Bye, bye forgotten feature flags, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F2.b13b31b0.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Less is more, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F3.4ed9a321.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Background main color, url='https://www.emergetools.com/images/homepage/products/performance-analysis/background-main-color.svg'
		image Background meteors, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fbackground-meteors.ed3616d7.png&w=256&q=75&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Performance Analysis, url='https://www.emergetools.com/_next/image?url=%2Fimages%2Fhomepage%2Fhero%2Fperformance-analysis.png&w=640&q=100&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		heading Performance Analysis
		heading Diagnose & prevent performance regressions
		link Read docs, url='https://docs.emergetools.com/docs/performance-testing'
			image
		link Watch a debugging session, url='https://www.youtube.com/watch?v=q0iSLAxzKqE'
			image
		link Read a case study, url='https://careersatdoordash.com/blog/how-we-reduced-our-ios-app-launch-time-by-60/'
			image
		button Continuously monitor app startup time On every nightly or every pull request
			paragraph
			paragraph
		button Speedy, accurate performance testing on real devices Minimize flakiness with our private device farm & analysis
			paragraph
			paragraph
		button Visualize performance changes Easy to understand tooling to help diagnose & fix issues
			paragraph
			paragraph
		button Track performance of UI tests Support for XCUI & UI Automator tests
			paragraph
			paragraph
		button Automated insights to help identify bad patterns Find instant ways to reduce app startup time
			paragraph
			paragraph
		image Continuously monitor app startup time, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F1.c6c2968a.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Speedy, accurate performance testing on real devices, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F2.2494b21e.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Visualize performance changes, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F3.71c54623.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Track performance of UI tests, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F4.d219fd79.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Automated insights to help identify bad patterns, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F5.d1d3e75d.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Background main color, url='https://www.emergetools.com/images/homepage/products/launch-booster/background-main-color.svg'
		image Background meteors, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fbackground-meteors.ed3616d7.png&w=256&q=75&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Launch Booster, url='https://www.emergetools.com/_next/image?url=%2Fimages%2Fhomepage%2Fhero%2Flaunch-booster.png&w=640&q=100&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		heading Launch Booster
		heading Improve app startup time
		link Read docs, url='https://docs.emergetools.com/docs/launch-booster-ios'
			image
		link How it works, url='https://www.emergetools.com/blog/posts/FasterAppStartupOrderFiles'
			image
		button Reduce app startup time instantly Utilize order files to make your app’s launch up to 20% faster
			paragraph
			paragraph
		button Easy integration Add a step into your release process and see immediate results in production
			paragraph
			paragraph
		image Reduce app startup time instantly, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F1.0f165297.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Easy integration, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F2.a77ecd3c.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Background main color, url='https://www.emergetools.com/images/homepage/products/build-distribution/background-main-color.svg'
		image Background meteors, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fbackground-meteors.ed3616d7.png&w=256&q=75&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Build Distribution, url='https://www.emergetools.com/_next/image?url=%2Fimages%2Fhomepage%2Fhero%2Fbuild-distribution.png&w=640&q=100&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		heading Build Distribution
		heading Share builds with your team
		link Read iOS docs, url='https://docs.emergetools.com/docs/ios-build-distribution'
			image
		link Read Android docs, url='https://docs.emergetools.com/docs/android-build-distribution'
			image
		button Effortless installation Install builds via QR code, direct link, or our web UI
			paragraph
			paragraph
		button Cross-platform, easy auth Distribute iOS and Android builds to your team with just a few clicks
			paragraph
			paragraph
		button Integrated with your workflow Automatically distribute builds from your existing CI/CD/Emerge pipeline
			paragraph
			paragraph
		button Keep users up to date Our SDKs automatically prompts your users to stay up to date with the latest builds
			paragraph
			paragraph
		image Effortless installation, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F1.92f36d06.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Cross-platform, easy auth, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F2.e2e87b87.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Integrated with your workflow, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F3.bf3579a3.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		image Keep users up to date, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F4.d2a177e3.png&w=1920&q=95&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		heading Dive deeper
		paragraph
			StaticText Unlock the full potential of your mobile team
		link Cross-platform support for iOS & Android Easy integrations with Gradle and Fastlane, url='https://docs.emergetools.com/docs/integrate-into-ci'
			paragraph
				StaticText Cross-platform support for iOS & Android
			paragraph
				image
		link No source code access or SDK required Read our comparison of top publicly available apps, url='https://www.emergetools.com/blog/posts/7AppsThatCouldSaveYou500MB'
			paragraph
				StaticText No source code access or SDK required
			paragraph
				image
		link SSO support SAML SSO authentication, including Okta, Auth0, OneLogin and Google, url='https://docs.emergetools.com/docs/sso'
			paragraph
				StaticText SSO support
			paragraph
				image
		link SOC 2 compliant and secure Read more about how we keep Emerge secure, url='https://www.emergetools.com/security'
			paragraph
				StaticText SOC 2 compliant and secure
			paragraph
				image
		link Open source tooling available See projects we build & sponsor, url='https://emergetools.com/open-source'
			paragraph
				StaticText Open source tooling available
			paragraph
				image
		link Compile unit attribution Read about how to attribute size to teams, url='https://docs.emergetools.com/docs/compile-unit-attribution'
			paragraph
				StaticText Compile unit attribution
			paragraph
				image
		link Customizable Slack alerting Read the docs, url='https://docs.emergetools.com/docs/slack'
			paragraph
				StaticText Customizable Slack alerting
			paragraph
				image
		link Competitor Analysis Benchmark against your competitors, url='https://docs.emergetools.com/docs/competitor-analysis'
			paragraph
				StaticText Competitor Analysis
			paragraph
				image
		link API access to raw data Poke around our API, url='https://docs.emergetools.com/reference'
			paragraph
				StaticText API access to raw data
			paragraph
				image
		link Accurately measure download & install size Learn more about how we calculate size, url='https://docs.emergetools.com/docs/what-is-app-size'
			paragraph
				StaticText Accurately measure download & install size
			paragraph
				image
		link Run comparisons of any two builds Learn more about running comparisons, url='https://docs.emergetools.com/docs/compare'
			paragraph
				StaticText Run comparisons of any two builds
			paragraph
				image
		link Get weekly digests of app size & performance insights Read the docs, url='https://docs.emergetools.com/docs/slack#weekly-digests'
			paragraph
				StaticText Get weekly digests of app size & performance insights
			paragraph
				image
		paragraph
			StaticText Never miss a post or product update
		paragraph
			StaticText Sign up to our newsletter. No spam.
		textbox Email, required
		button Submit
		link Read archive, url='https://www.emergetools.com/newsletter'
			image
	contentinfo
		image Background main color, url='https://www.emergetools.com/images/homepage/products/size-analysis/background-main-color.svg'
		image Background meteors, url='https://www.emergetools.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fbackground-meteors.ed3616d7.png&w=256&q=75&dpl=dpl_HSWK51vyaSVFC1v2Tp745hTDcEmb'
		paragraph
			StaticText Supercharge your mobile apps now
		button Get started
		paragraph
			StaticText Trusted by the best mobile teams
		image ClassPass, url='https://www.emergetools.com/images/homepage/trusted/classpass.svg'
		image Dropbox, url='https://www.emergetools.com/images/homepage/trusted/dropbox.svg'
		image Photoroom, url='https://www.emergetools.com/images/homepage/trusted/photoroom.svg'
		image TuneIn, url='https://www.emergetools.com/images/homepage/trusted/tunein.svg'
		image Stripe, url='https://www.emergetools.com/images/homepage/trusted/stripe.svg'
		image EarnIn, url='https://www.emergetools.com/images/homepage/trusted/earnin.svg'
		image Bumble, url='https://www.emergetools.com/images/homepage/trusted/bumble.svg'
		image Life360, url='https://www.emergetools.com/images/homepage/trusted/life360.svg'
		paragraph
			StaticText 2024
			StaticText Emerge Tools, Inc. All rights reserved.
		list
			listitem
				link Email us, url='mailto:support@emergetools.com'
			listitem
				link Open Source, url='https://www.emergetools.com/open-source'
			listitem
				link Privacy Policy, url='https://www.emergetools.com/Emerge-Tools-Privacy-Policy-03_10_2024.pdf'
			listitem
				link Terms of Service, url='https://www.emergetools.com/Emerge-Tools-Terms-of-Service-03_10_2024.pdf'
			listitem
				link Security, url='https://www.emergetools.com/security'
		link GitHub, url='https://github.com/EmergeTools/'
			image
		link Y Combinator, url='https://www.ycombinator.com/companies/emerge-tools'
			image
		link X, url='https://twitter.com/emergetools'
			image
		link RSS, url='https://www.emergetools.com/rss.xml'
			image
	alert, atomic
```
</details>



```
RootWebArea Sign up | Emerge, focused, url='https://auth.emergetools.com/u/signup/identifier?state=hKFo2SA2TFVfaTR4R05fVDFIMkZPMU40a0dXWmhubm1qSVlnRqFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHR0RHRodmtuUDN0WVloc0VTSW5xaUR6cnE4cW4yY0pfo2NpZNkgRjhuRXhxYlVZZ1JDOFE3QVdPOFAwTXhvbjUwUG1LUXo'
	main
		image Emerge, url='https://emergeassets.s3.us-west-1.amazonaws.com/emergeavatar.png'
		heading Create Your Account
		paragraph
```
<details><summary>Show more</summary>

```
			StaticText Sign up to continue to Emerge
		LabelText
			StaticText Email address
		[34] textbox Email address, center=(960,484), autocomplete=email, contenteditable=True, focused, required, type=text
		[38] button Continue, center=(960,560), type=submit
		paragraph
			StaticText Already have an account?
			[41] link Log in, center=(991,612), url='https://auth.emergetools.com/u/login/identifier?state=hKFo2SA2TFVfaTR4R05fVDFIMkZPMU40a0dXWmhubm1qSVlnRqFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHR0RHRodmtuUDN0WVloc0VTSW5xaUR6cnE4cW4yY0pfo2NpZNkgRjhuRXhxYlVZZ1JDOFE3QVdPOFAwTXhvbjUwUG1LUXo'
		StaticText OR
		[48] button Continue with Google, center=(960,709), type=submit
		[54] button Continue with Apple, center=(960,769), type=submit
```
</details>

**Reasoning for action:** I clicked the 'Get started' button (link [141]) because it is the first step to initiate the account sign-up process. By clicking this button, I will be directed to the sign-up page where I can provide my email address, which is necessary for creating an account and accessing the mobile development tools offered by Emerge Tools. This action directly advances the task of signing up for an account.

**Action:** click(141) # Click on the 'Get started' button to explore the signup options.

**Change Description:** The browser navigated from the Emerge Tools homepage to the sign-up page, where a new account creation interface is displayed, featuring an email input field and options to continue with Google or Apple, marking a transition from informational content to an interactive sign-up experience.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://auth.emergetools.com/u/signup/identifier?state=hKFo2SA2TFVfaTR4R05fVDFIMkZPMU40a0dXWmhubm1qSVlnRqFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHR0RHRodmtuUDN0WVloc0VTSW5xaUR6cnE4cW4yY0pfo2NpZNkgRjhuRXhxYlVZZ1JDOFE3QVdPOFAwTXhvbjUwUG1LUXo

https://auth.emergetools.com/u/signup/identifier?state=hKFo2SA2TFVfaTR4R05fVDFIMkZPMU40a0dXWmhubm1qSVlnRqFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHR0RHRodmtuUDN0WVloc0VTSW5xaUR6cnE4cW4yY0pfo2NpZNkgRjhuRXhxYlVZZ1JDOFE3QVdPOFAwTXhvbjUwUG1LUXo

**Content (before/after):** 

```
RootWebArea Sign up | Emerge, focused, url='https://auth.emergetools.com/u/signup/identifier?state=hKFo2SA2TFVfaTR4R05fVDFIMkZPMU40a0dXWmhubm1qSVlnRqFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHR0RHRodmtuUDN0WVloc0VTSW5xaUR6cnE4cW4yY0pfo2NpZNkgRjhuRXhxYlVZZ1JDOFE3QVdPOFAwTXhvbjUwUG1LUXo'
	main
		image Emerge, url='https://emergeassets.s3.us-west-1.amazonaws.com/emergeavatar.png'
		heading Create Your Account
		paragraph
```
<details><summary>Show more</summary>

```
			StaticText Sign up to continue to Emerge
		LabelText
			StaticText Email address
		[34] textbox Email address, center=(960,484), autocomplete=email, contenteditable=True, focused, required, type=text
		[38] button Continue, center=(960,560), type=submit
		paragraph
			StaticText Already have an account?
			[41] link Log in, center=(991,612), url='https://auth.emergetools.com/u/login/identifier?state=hKFo2SA2TFVfaTR4R05fVDFIMkZPMU40a0dXWmhubm1qSVlnRqFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHR0RHRodmtuUDN0WVloc0VTSW5xaUR6cnE4cW4yY0pfo2NpZNkgRjhuRXhxYlVZZ1JDOFE3QVdPOFAwTXhvbjUwUG1LUXo'
		StaticText OR
		[48] button Continue with Google, center=(960,709), type=submit
		[54] button Continue with Apple, center=(960,769), type=submit
```
</details>



```
RootWebArea Sign up | Emerge, focused, url='https://auth.emergetools.com/u/signup/identifier?state=hKFo2SA2TFVfaTR4R05fVDFIMkZPMU40a0dXWmhubm1qSVlnRqFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHR0RHRodmtuUDN0WVloc0VTSW5xaUR6cnE4cW4yY0pfo2NpZNkgRjhuRXhxYlVZZ1JDOFE3QVdPOFAwTXhvbjUwUG1LUXo'
	main
		image Emerge, url='https://emergeassets.s3.us-west-1.amazonaws.com/emergeavatar.png'
		heading Create Your Account
		paragraph
```
<details><summary>Show more</summary>

```
			StaticText Sign up to continue to Emerge
		LabelText
			StaticText Email address
		[34] textbox Email address value='user@example.com', center=(960,484), autocomplete=email, contenteditable=True, focused, required, type=text
		[38] button Continue, center=(960,560), type=submit
		paragraph
			StaticText Already have an account?
			[41] link Log in, center=(991,612), url='https://auth.emergetools.com/u/login/identifier?state=hKFo2SA2TFVfaTR4R05fVDFIMkZPMU40a0dXWmhubm1qSVlnRqFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHR0RHRodmtuUDN0WVloc0VTSW5xaUR6cnE4cW4yY0pfo2NpZNkgRjhuRXhxYlVZZ1JDOFE3QVdPOFAwTXhvbjUwUG1LUXo'
		StaticText OR
		[48] button Continue with Google, center=(960,709), type=submit
		[54] button Continue with Apple, center=(960,769), type=submit
```
</details>

**Reasoning for action:** I filled in the email address field identified by the ID '34' with 'user@example.com' because this is a necessary step in the sign-up process. By filling this field, I prepare to click the 'Continue' button to advance to the next step, which will allow me to create a password for the new account. Completing this action makes it possible to meet the user story objective of signing up for an account with Emerge Tools.

**Action:** fill('34', 'user@example.com') # Fill in the email address field with a sample email.

**Change Description:** The email address textbox now contains the value 'user@example.com', indicating that the user has filled in their email address for the sign-up process.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://auth.emergetools.com/u/signup/identifier?state=hKFo2SA2TFVfaTR4R05fVDFIMkZPMU40a0dXWmhubm1qSVlnRqFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHR0RHRodmtuUDN0WVloc0VTSW5xaUR6cnE4cW4yY0pfo2NpZNkgRjhuRXhxYlVZZ1JDOFE3QVdPOFAwTXhvbjUwUG1LUXo

https://auth.emergetools.com/u/signup/password?state=hKFo2SA2TFVfaTR4R05fVDFIMkZPMU40a0dXWmhubm1qSVlnRqFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHR0RHRodmtuUDN0WVloc0VTSW5xaUR6cnE4cW4yY0pfo2NpZNkgRjhuRXhxYlVZZ1JDOFE3QVdPOFAwTXhvbjUwUG1LUXo

**Content (before/after):** 

```
RootWebArea Sign up | Emerge, focused, url='https://auth.emergetools.com/u/signup/identifier?state=hKFo2SA2TFVfaTR4R05fVDFIMkZPMU40a0dXWmhubm1qSVlnRqFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHR0RHRodmtuUDN0WVloc0VTSW5xaUR6cnE4cW4yY0pfo2NpZNkgRjhuRXhxYlVZZ1JDOFE3QVdPOFAwTXhvbjUwUG1LUXo'
	main
		image Emerge, url='https://emergeassets.s3.us-west-1.amazonaws.com/emergeavatar.png'
		heading Create Your Account
		paragraph
```
<details><summary>Show more</summary>

```
			StaticText Sign up to continue to Emerge
		LabelText
			StaticText Email address
		[34] textbox Email address value='user@example.com', center=(960,484), autocomplete=email, contenteditable=True, focused, required, type=text
		[38] button Continue, center=(960,560), type=submit
		paragraph
			StaticText Already have an account?
			[41] link Log in, center=(991,612), url='https://auth.emergetools.com/u/login/identifier?state=hKFo2SA2TFVfaTR4R05fVDFIMkZPMU40a0dXWmhubm1qSVlnRqFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHR0RHRodmtuUDN0WVloc0VTSW5xaUR6cnE4cW4yY0pfo2NpZNkgRjhuRXhxYlVZZ1JDOFE3QVdPOFAwTXhvbjUwUG1LUXo'
		StaticText OR
		[48] button Continue with Google, center=(960,709), type=submit
		[54] button Continue with Apple, center=(960,769), type=submit
```
</details>



```
RootWebArea Create a password to sign up | Emerge, focused, url='https://auth.emergetools.com/u/signup/password?state=hKFo2SA2TFVfaTR4R05fVDFIMkZPMU40a0dXWmhubm1qSVlnRqFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHR0RHRodmtuUDN0WVloc0VTSW5xaUR6cnE4cW4yY0pfo2NpZNkgRjhuRXhxYlVZZ1JDOFE3QVdPOFAwTXhvbjUwUG1LUXo'
	main
		image Emerge, url='https://emergeassets.s3.us-west-1.amazonaws.com/emergeavatar.png'
		heading Create Your Account
		paragraph
```
<details><summary>Show more</summary>

```
			StaticText Set your password for Emerge to continue to Emerge
		StaticText user@example.com
		[35] link Edit email address, center=(1084,548), inner_text=Edit, url='https://auth.emergetools.com/u/signup/identifier?state=hKFo2SA2TFVfaTR4R05fVDFIMkZPMU40a0dXWmhubm1qSVlnRqFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHR0RHRodmtuUDN0WVloc0VTSW5xaUR6cnE4cW4yY0pfo2NpZNkgRjhuRXhxYlVZZ1JDOFE3QVdPOFAwTXhvbjUwUG1LUXo'
		LabelText
			StaticText Password
		[40] textbox Password, center=(938,612), autocomplete=new-password, contenteditable=True, focused, required, type=password
		[42] button Show password, center=(1097,612), inner_text=Show password
Show password, type=button
		[71] button Continue, center=(960,690), type=submit
		paragraph
			StaticText Already have an account?
			[74] link Log in, center=(991,742), url='https://auth.emergetools.com/u/login/identifier?state=hKFo2SA2TFVfaTR4R05fVDFIMkZPMU40a0dXWmhubm1qSVlnRqFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHR0RHRodmtuUDN0WVloc0VTSW5xaUR6cnE4cW4yY0pfo2NpZNkgRjhuRXhxYlVZZ1JDOFE3QVdPOFAwTXhvbjUwUG1LUXo'
```
</details>

**Reasoning for action:** By clicking the 'Continue' button, I am submitting my email address entered in the textbox. This action is essential to advance to the next page where I can create a password for my new account, thus fulfilling the user's story of signing up for an account with Emerge Tools.

**Action:** click(38) # Click on the 'Continue' button to proceed with the sign-up process.

**Change Description:** After clicking the 'Continue' button, the browser transitioned to a new page where the user is prompted to create a password for their account, displaying the email entered previously and a new password input field with the option to show the password.

**Screenshot before:****Screenshot after:**---


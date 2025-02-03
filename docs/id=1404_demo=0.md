# Task

**Explore DART Product and Initiate Registration**

As a potential Harmoney customer,
I explore the DART product details and initiate the registration process,
so that I can utilize Harmoney's fixed income trading services effectively.

**Success definition:** Given I am on the Harmoney homepage
When I click on the Products button and select the DART product
Then I should be directed to the DART product details page and see the product features displayed, followed by navigating to the registration page after clicking 'Get Started', where I should see a sign-up form with a disabled 'Next' button.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.harmoney.in/

https://www.harmoney.in/

**Content (before/after):** 

```
RootWebArea Harmoney | Digitizing bond markets, url='https://www.harmoney.in/'
	navigation
		[199] link Brand Icon Harmoney, center=(82,76), inner_text=Harmoney, url='https://www.harmoney.in/'
			image Brand Icon, url="data:image/svg+xml,%3csvg%20width='24'%20height='24'%20viewBox='0%200%2024%2024'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='Frame%201'%3e%3cpath%20id='Vector'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.0803%203.74219C9.87563%205.76415%208.47104%208.81262%208.4533%2012.2188C8.43555%2015.6406%209.80456%2018.7046%2011.9914%2020.7422C11.3514%2017.6626%2011.9381%2014.2874%2013.8049%2011.5655C14.2672%2010.8812%2014.8006%2010.2591%2015.3873%209.73029C14.8895%207.35061%2013.716%205.26647%2012.0803%203.74219Z'%20fill='%23244275'/%3e%3cpath%20id='Vector_2'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M2.2587%207.16406C1.6186%2010.2436%202.15203%2013.6032%204.01888%2016.325C5.86798%2019.0625%208.53491%2020.5867%2011.3974%2020.7422C9.19275%2018.7047%207.93041%2015.6407%207.93041%2012.2345C7.93041%2011.3635%208.01933%2010.5236%208.19707%209.69923C6.49022%208.14391%204.39231%207.27289%202.2587%207.16406ZM21.7628%207.24176C14.2421%208.43945%2011.4329%2015.1119%2012.5175%2020.7422C20.0738%2019.5446%2022.883%2012.9033%2021.7628%207.24176Z'%20fill='%23244275'/%3e%3c/g%3e%3c/svg%3e"
			StaticText Harmoney
```
<details><summary>Show more</summary>

```
		list
			listitem
				[214] button Products, center=(235,76), type=button
					image
			listitem
				[217] button Resources, center=(361,76), type=button
					image
		[220] link Sign Up, center=(1786,76), url='https://www.harmoney.in/client/register'
		[221] link Login, center=(1869,76), url='https://www.harmoney.in/auth/login'
			button Login
	heading Your Market Connection
	paragraph
		StaticText Information. Efficiency. Fully Integrated
	[228] link Get Started, center=(360,469), url='https://www.harmoney.in/client/register'
		button Get Started
	StaticText 150+
	StaticText Participants
	StaticText 5000+ Cr
	StaticText Processed Volume
	StaticText 30,000+
	StaticText Bonds
	heading Fixed Income Trading Software
	paragraph
		StaticText for Banks, Mutual Funds, Broker-Dealers & Wealth Managers
	image, url="data:image/svg+xml,%3csvg%20width='65'%20height='64'%20viewBox='0%200%2065%2064'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cmask%20id='mask0_1551_22'%20style='mask-type:alpha'%20maskUnits='userSpaceOnUse'%20x='0'%20y='0'%20width='65'%20height='64'%3e%3crect%20x='64.3333'%20y='64'%20width='64'%20height='64'%20transform='rotate(-180%2064.3333%2064)'%20fill='%23D9D9D9'/%3e%3c/mask%3e%3cg%20mask='url(%23mask0_1551_22)'%3e%3cpath%20d='M43.4613%2010.6153L52.2307%2019.3847L50.3947%2021.272L44.7947%2015.6873L44.7947%2033.436C44.7947%2033.9147%2044.9487%2034.3078%2045.2567%2034.6153C45.5642%2034.9229%2045.9573%2035.0767%2046.436%2035.0767L54.0767%2035.0767C55.27%2035.0767%2056.2862%2035.4965%2057.1253%2036.336C57.9649%2037.1751%2058.3847%2038.1913%2058.3847%2039.3847L58.3847%2053.3333L55.718%2053.3333L55.718%2039.3847C55.718%2038.906%2055.5642%2038.5129%2055.2567%2038.2053C54.9487%2037.8973%2054.5553%2037.7433%2054.0767%2037.7433L46.436%2037.7433C45.2427%2037.7433%2044.2265%2037.3238%2043.3873%2036.4847C42.5478%2035.6451%2042.128%2034.6289%2042.128%2033.436L42.128%2015.7387L36.5433%2021.272L34.692%2019.3847L43.4613%2010.6153ZM21.2053%2010.6153L29.9747%2019.3847L28.1387%2021.272L22.5387%2015.6873L22.5387%2033.436C22.5387%2034.6289%2022.1189%2035.6451%2021.2793%2036.4847C20.4402%2037.3238%2019.424%2037.7433%2018.2307%2037.7433L10.59%2037.7433C10.1113%2037.7433%209.71801%2037.8973%209.41001%2038.2053C9.10246%2038.5129%208.94867%2038.906%208.94867%2039.3847L8.94867%2053.3333L6.28201%2053.3333L6.28201%2039.3847C6.28201%2038.1913%206.70178%2037.1751%207.54134%2036.336C8.38045%2035.4964%209.39667%2035.0767%2010.59%2035.0767L18.2307%2035.0767C18.7093%2035.0767%2019.1025%2034.9229%2019.41%2034.6153C19.718%2034.3078%2019.872%2033.9147%2019.872%2033.436L19.872%2015.672L14.2873%2021.272L12.436%2019.3847L21.2053%2010.6153Z'%20fill='%23E8402B'/%3e%3c/g%3e%3c/svg%3e"
	heading Market Aggregation
	paragraph
		StaticText Single screen access to market information and your trading community
	image, url="data:image/svg+xml,%3csvg%20width='64'%20height='64'%20viewBox='0%200%2064%2064'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cpath%20d='M32%2061.5C15.725%2061.5%202.5%2048.275%202.5%2032C2.5%2015.725%2015.725%202.5%2032%202.5C48.275%202.5%2061.5%2015.725%2061.5%2032C61.5%2048.275%2048.275%2061.5%2032%2061.5ZM32%205.975C17.65%205.975%205.975%2017.65%205.975%2032C5.975%2046.35%2017.65%2058.025%2032%2058.025C46.35%2058.025%2058.025%2046.35%2058.025%2032C58.025%2017.65%2046.35%205.975%2032%205.975ZM48.6%2029.55H15.4C14.4%2029.55%2013.55%2028.725%2013.55%2027.7C13.55%2026.675%2014.375%2025.85%2015.4%2025.85H42.275L38%2023.175C37.2%2022.675%2036.95%2021.575%2037.425%2020.75L37.575%2020.5C38.05%2019.675%2039.125%2019.4%2039.925%2019.9L49.6%2025.975C50.15%2026.325%2050.425%2026.925%2050.4%2027.55C50.4%2027.6%2050.425%2027.625%2050.425%2027.675C50.45%2028.725%2049.6%2029.55%2048.6%2029.55ZM13.575%2037.45V37.425C13.625%2036.85%2013.925%2036.375%2014.375%2036.05C14.4%2036.025%2014.425%2036.025%2014.45%2036C14.575%2035.925%2014.7%2035.85%2014.85%2035.8C14.975%2035.75%2015.075%2035.75%2015.2%2035.725C15.25%2035.725%2015.325%2035.7%2015.375%2035.7H48.575C49.575%2035.7%2050.425%2036.525%2050.425%2037.55C50.425%2038.575%2049.6%2039.4%2048.575%2039.4H21.7L25.85%2042.05C26.65%2042.55%2026.9%2043.65%2026.425%2044.475L26.275%2044.725C25.8%2045.55%2024.75%2045.825%2023.95%2045.325L14.35%2039.225C13.825%2038.9%2013.575%2038.3%2013.575%2037.7C13.575%2037.65%2013.55%2037.6%2013.55%2037.55C13.575%2037.5%2013.575%2037.475%2013.575%2037.45Z'%20fill='%23E8402B'/%3e%3c/svg%3e"
	heading Efficient Trading Workflows
	paragraph
		StaticText AI powered quote detection & ticketing with automated workflows
	image, url='https://www.harmoney.in/_nuxt/integrated.BRG7uysc.svg'
	heading Agile & Integrated
	paragraph
		StaticText End-to-end connectivity with clearing houses STP with OMS, EMS & portfolio systems
	heading One Screen, Many Capabilities
	paragraph
		StaticText Unlock Efficiency In Bond Trading
	heading DART
	paragraph
		StaticText Fixed Income Trading From A Single-Screen
	list
		listitem
			ListMarker •
			StaticText Chat with your fixed income community
		listitem
			ListMarker •
			StaticText AI-powered quote detection & ticketing
		listitem
			ListMarker •
			StaticText Enhanced Efficiency through NSE/BSE Integration
	link Know More, url='https://www.harmoney.in/product/dart'
		button Know More
	image, url='https://www.harmoney.in/_ipx/_/images/offerings/livemarket1.png'
	image FIND-screen, url='https://www.harmoney.in/_nuxt/product_find.BdWNZeob.png'
	heading FIND
	paragraph
		StaticText Best In Class, Rich Database Built With Intelligence
	list
		listitem
			ListMarker •
			StaticText Comprehensive reference data for 30,000+ securities
		listitem
			ListMarker •
			StaticText Bond cashflows & price calculator
		listitem
			ListMarker •
			StaticText Real-time & historical trade data access
	link Know More, url='https://www.harmoney.in/product/find'
		button Know More
	contentinfo
		image Brand Icon, url="data:image/svg+xml,%3csvg%20width='24'%20height='24'%20viewBox='0%200%2024%2024'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='Frame%201'%3e%3cpath%20id='Vector'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.0803%203.74219C9.87563%205.76415%208.47104%208.81262%208.4533%2012.2188C8.43555%2015.6406%209.80456%2018.7046%2011.9914%2020.7422C11.3514%2017.6626%2011.9381%2014.2874%2013.8049%2011.5655C14.2672%2010.8812%2014.8006%2010.2591%2015.3873%209.73029C14.8895%207.35061%2013.716%205.26647%2012.0803%203.74219Z'%20fill='white'/%3e%3cpath%20id='Vector_2'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M2.2587%207.16406C1.6186%2010.2436%202.15203%2013.6032%204.01888%2016.325C5.86798%2019.0625%208.53491%2020.5867%2011.3974%2020.7422C9.19275%2018.7047%207.93041%2015.6407%207.93041%2012.2345C7.93041%2011.3635%208.01933%2010.5236%208.19707%209.69923C6.49022%208.14391%204.39231%207.27289%202.2587%207.16406ZM21.7628%207.24176C14.2421%208.43945%2011.4329%2015.1119%2012.5175%2020.7422C20.0738%2019.5446%2022.883%2012.9033%2021.7628%207.24176Z'%20fill='white'/%3e%3c/g%3e%3c/svg%3e"
		StaticText Harmoney
		StaticText Jai Villa, Dev Shakti,
		StaticText Tilak Road, Santacruz(W),
		StaticText Mumbai 400054
		link LinkedIn, url='https://www.linkedin.com/company/Harmoney/'
			image LinkedIn, url="data:image/svg+xml,%3csvg%20width='20'%20height='20'%20viewBox='0%200%2020%2020'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='LinkedIn_icon%201'%20clip-path='url(%23clip0_1101_206)'%3e%3cg%20id='Group'%3e%3cpath%20id='Vector'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M2.22222%2020H17.7778C19.0051%2020%2020%2019.0051%2020%2017.7778V2.22222C20%200.994923%2019.0051%200%2017.7778%200H2.22222C0.994923%200%200%200.994923%200%202.22222V17.7778C0%2019.0051%200.994923%2020%202.22222%2020Z'%20fill='%23007EBB'/%3e%3cpath%20id='Vector_2'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M17.2218%2017.2218H14.2539V12.1668C14.2539%2010.7809%2013.7273%2010.0064%2012.6303%2010.0064C11.437%2010.0064%2010.8135%2010.8124%2010.8135%2012.1668V17.2218H7.95327V7.59216H10.8135V8.88927C10.8135%208.88927%2011.6735%207.29796%2013.7169%207.29796C15.7595%207.29796%2017.2218%208.54525%2017.2218%2011.1249V17.2218ZM4.54105%206.33124C3.5668%206.33124%202.77734%205.53558%202.77734%204.55429C2.77734%203.573%203.5668%202.77734%204.54105%202.77734C5.5153%202.77734%206.30429%203.573%206.30429%204.55429C6.30429%205.53558%205.5153%206.33124%204.54105%206.33124ZM3.06416%2017.2218H6.04662V7.59216H3.06416V17.2218Z'%20fill='white'/%3e%3c/g%3e%3c/g%3e%3cdefs%3e%3cclipPath%20id='clip0_1101_206'%3e%3crect%20width='20'%20height='20'%20fill='white'/%3e%3c/clipPath%3e%3c/defs%3e%3c/svg%3e"
		link Bond Search, url='https://www.harmoney.in/find'
		link About Us, url='https://www.harmoney.in/about'
		link Contact us
		link Terms and Conditions, url='https://www.harmoney.in/terms'
		link Privacy Policy, url='https://www.harmoney.in/privacy'
	generic
		[b] dialog Intercom live chat banner, center=(960,25), modal=False, title=Intercom live chat banner
```
</details>



```
RootWebArea Harmoney | Digitizing bond markets, focused, url='https://www.harmoney.in/'
	navigation
		[199] link Brand Icon Harmoney, center=(82,76), inner_text=Harmoney, url='https://www.harmoney.in/'
			image Brand Icon, url="data:image/svg+xml,%3csvg%20width='24'%20height='24'%20viewBox='0%200%2024%2024'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='Frame%201'%3e%3cpath%20id='Vector'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.0803%203.74219C9.87563%205.76415%208.47104%208.81262%208.4533%2012.2188C8.43555%2015.6406%209.80456%2018.7046%2011.9914%2020.7422C11.3514%2017.6626%2011.9381%2014.2874%2013.8049%2011.5655C14.2672%2010.8812%2014.8006%2010.2591%2015.3873%209.73029C14.8895%207.35061%2013.716%205.26647%2012.0803%203.74219Z'%20fill='%23244275'/%3e%3cpath%20id='Vector_2'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M2.2587%207.16406C1.6186%2010.2436%202.15203%2013.6032%204.01888%2016.325C5.86798%2019.0625%208.53491%2020.5867%2011.3974%2020.7422C9.19275%2018.7047%207.93041%2015.6407%207.93041%2012.2345C7.93041%2011.3635%208.01933%2010.5236%208.19707%209.69923C6.49022%208.14391%204.39231%207.27289%202.2587%207.16406ZM21.7628%207.24176C14.2421%208.43945%2011.4329%2015.1119%2012.5175%2020.7422C20.0738%2019.5446%2022.883%2012.9033%2021.7628%207.24176Z'%20fill='%23244275'/%3e%3c/g%3e%3c/svg%3e"
			StaticText Harmoney
```
<details><summary>Show more</summary>

```
		list
			listitem
				[214] button Products, center=(235,76), type=button
					image
				list
					listitem
						[345] link DART Single Screen Trading For Indian Bonds, center=(385,145), inner_text=DART
Single Screen Trading For Indian Bonds, url='https://www.harmoney.in/product/dart'
					listitem
						[349] link FIND The Only Bond Reference Data Source You Need, center=(385,205), inner_text=FIND
The Only Bond Reference Data Source You Need, url='https://www.harmoney.in/product/find'
				menu, focused, orientation='vertical'
			listitem
				[217] button Resources, center=(361,76), type=button
					image
		[220] link Sign Up, center=(1786,76), url='https://www.harmoney.in/client/register'
		[221] link Login, center=(1869,76), url='https://www.harmoney.in/auth/login'
			button Login
	heading Your Market Connection
	paragraph
		StaticText Information. Efficiency. Fully Integrated
	[228] link Get Started, center=(360,469), url='https://www.harmoney.in/client/register'
		button Get Started
	StaticText 150+
	StaticText Participants
	StaticText 5000+ Cr
	StaticText Processed Volume
	StaticText 30,000+
	StaticText Bonds
	heading Fixed Income Trading Software
	paragraph
		StaticText for Banks, Mutual Funds, Broker-Dealers & Wealth Managers
	image, url="data:image/svg+xml,%3csvg%20width='65'%20height='64'%20viewBox='0%200%2065%2064'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cmask%20id='mask0_1551_22'%20style='mask-type:alpha'%20maskUnits='userSpaceOnUse'%20x='0'%20y='0'%20width='65'%20height='64'%3e%3crect%20x='64.3333'%20y='64'%20width='64'%20height='64'%20transform='rotate(-180%2064.3333%2064)'%20fill='%23D9D9D9'/%3e%3c/mask%3e%3cg%20mask='url(%23mask0_1551_22)'%3e%3cpath%20d='M43.4613%2010.6153L52.2307%2019.3847L50.3947%2021.272L44.7947%2015.6873L44.7947%2033.436C44.7947%2033.9147%2044.9487%2034.3078%2045.2567%2034.6153C45.5642%2034.9229%2045.9573%2035.0767%2046.436%2035.0767L54.0767%2035.0767C55.27%2035.0767%2056.2862%2035.4965%2057.1253%2036.336C57.9649%2037.1751%2058.3847%2038.1913%2058.3847%2039.3847L58.3847%2053.3333L55.718%2053.3333L55.718%2039.3847C55.718%2038.906%2055.5642%2038.5129%2055.2567%2038.2053C54.9487%2037.8973%2054.5553%2037.7433%2054.0767%2037.7433L46.436%2037.7433C45.2427%2037.7433%2044.2265%2037.3238%2043.3873%2036.4847C42.5478%2035.6451%2042.128%2034.6289%2042.128%2033.436L42.128%2015.7387L36.5433%2021.272L34.692%2019.3847L43.4613%2010.6153ZM21.2053%2010.6153L29.9747%2019.3847L28.1387%2021.272L22.5387%2015.6873L22.5387%2033.436C22.5387%2034.6289%2022.1189%2035.6451%2021.2793%2036.4847C20.4402%2037.3238%2019.424%2037.7433%2018.2307%2037.7433L10.59%2037.7433C10.1113%2037.7433%209.71801%2037.8973%209.41001%2038.2053C9.10246%2038.5129%208.94867%2038.906%208.94867%2039.3847L8.94867%2053.3333L6.28201%2053.3333L6.28201%2039.3847C6.28201%2038.1913%206.70178%2037.1751%207.54134%2036.336C8.38045%2035.4964%209.39667%2035.0767%2010.59%2035.0767L18.2307%2035.0767C18.7093%2035.0767%2019.1025%2034.9229%2019.41%2034.6153C19.718%2034.3078%2019.872%2033.9147%2019.872%2033.436L19.872%2015.672L14.2873%2021.272L12.436%2019.3847L21.2053%2010.6153Z'%20fill='%23E8402B'/%3e%3c/g%3e%3c/svg%3e"
	heading Market Aggregation
	paragraph
		StaticText Single screen access to market information and your trading community
	image, url="data:image/svg+xml,%3csvg%20width='64'%20height='64'%20viewBox='0%200%2064%2064'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cpath%20d='M32%2061.5C15.725%2061.5%202.5%2048.275%202.5%2032C2.5%2015.725%2015.725%202.5%2032%202.5C48.275%202.5%2061.5%2015.725%2061.5%2032C61.5%2048.275%2048.275%2061.5%2032%2061.5ZM32%205.975C17.65%205.975%205.975%2017.65%205.975%2032C5.975%2046.35%2017.65%2058.025%2032%2058.025C46.35%2058.025%2058.025%2046.35%2058.025%2032C58.025%2017.65%2046.35%205.975%2032%205.975ZM48.6%2029.55H15.4C14.4%2029.55%2013.55%2028.725%2013.55%2027.7C13.55%2026.675%2014.375%2025.85%2015.4%2025.85H42.275L38%2023.175C37.2%2022.675%2036.95%2021.575%2037.425%2020.75L37.575%2020.5C38.05%2019.675%2039.125%2019.4%2039.925%2019.9L49.6%2025.975C50.15%2026.325%2050.425%2026.925%2050.4%2027.55C50.4%2027.6%2050.425%2027.625%2050.425%2027.675C50.45%2028.725%2049.6%2029.55%2048.6%2029.55ZM13.575%2037.45V37.425C13.625%2036.85%2013.925%2036.375%2014.375%2036.05C14.4%2036.025%2014.425%2036.025%2014.45%2036C14.575%2035.925%2014.7%2035.85%2014.85%2035.8C14.975%2035.75%2015.075%2035.75%2015.2%2035.725C15.25%2035.725%2015.325%2035.7%2015.375%2035.7H48.575C49.575%2035.7%2050.425%2036.525%2050.425%2037.55C50.425%2038.575%2049.6%2039.4%2048.575%2039.4H21.7L25.85%2042.05C26.65%2042.55%2026.9%2043.65%2026.425%2044.475L26.275%2044.725C25.8%2045.55%2024.75%2045.825%2023.95%2045.325L14.35%2039.225C13.825%2038.9%2013.575%2038.3%2013.575%2037.7C13.575%2037.65%2013.55%2037.6%2013.55%2037.55C13.575%2037.5%2013.575%2037.475%2013.575%2037.45Z'%20fill='%23E8402B'/%3e%3c/svg%3e"
	heading Efficient Trading Workflows
	paragraph
		StaticText AI powered quote detection & ticketing with automated workflows
	image, url='https://www.harmoney.in/_nuxt/integrated.BRG7uysc.svg'
	heading Agile & Integrated
	paragraph
		StaticText End-to-end connectivity with clearing houses STP with OMS, EMS & portfolio systems
	heading One Screen, Many Capabilities
	paragraph
		StaticText Unlock Efficiency In Bond Trading
	heading DART
	paragraph
		StaticText Fixed Income Trading From A Single-Screen
	list
		listitem
			ListMarker •
			StaticText Chat with your fixed income community
		listitem
			ListMarker •
			StaticText AI-powered quote detection & ticketing
		listitem
			ListMarker •
			StaticText Enhanced Efficiency through NSE/BSE Integration
	link Know More, url='https://www.harmoney.in/product/dart'
		button Know More
	image, url='https://www.harmoney.in/_ipx/_/images/offerings/livemarket1.png'
	image FIND-screen, url='https://www.harmoney.in/_nuxt/product_find.BdWNZeob.png'
	heading FIND
	paragraph
		StaticText Best In Class, Rich Database Built With Intelligence
	list
		listitem
			ListMarker •
			StaticText Comprehensive reference data for 30,000+ securities
		listitem
			ListMarker •
			StaticText Bond cashflows & price calculator
		listitem
			ListMarker •
			StaticText Real-time & historical trade data access
	link Know More, url='https://www.harmoney.in/product/find'
		button Know More
	contentinfo
		image Brand Icon, url="data:image/svg+xml,%3csvg%20width='24'%20height='24'%20viewBox='0%200%2024%2024'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='Frame%201'%3e%3cpath%20id='Vector'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.0803%203.74219C9.87563%205.76415%208.47104%208.81262%208.4533%2012.2188C8.43555%2015.6406%209.80456%2018.7046%2011.9914%2020.7422C11.3514%2017.6626%2011.9381%2014.2874%2013.8049%2011.5655C14.2672%2010.8812%2014.8006%2010.2591%2015.3873%209.73029C14.8895%207.35061%2013.716%205.26647%2012.0803%203.74219Z'%20fill='white'/%3e%3cpath%20id='Vector_2'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M2.2587%207.16406C1.6186%2010.2436%202.15203%2013.6032%204.01888%2016.325C5.86798%2019.0625%208.53491%2020.5867%2011.3974%2020.7422C9.19275%2018.7047%207.93041%2015.6407%207.93041%2012.2345C7.93041%2011.3635%208.01933%2010.5236%208.19707%209.69923C6.49022%208.14391%204.39231%207.27289%202.2587%207.16406ZM21.7628%207.24176C14.2421%208.43945%2011.4329%2015.1119%2012.5175%2020.7422C20.0738%2019.5446%2022.883%2012.9033%2021.7628%207.24176Z'%20fill='white'/%3e%3c/g%3e%3c/svg%3e"
		StaticText Harmoney
		StaticText Jai Villa, Dev Shakti,
		StaticText Tilak Road, Santacruz(W),
		StaticText Mumbai 400054
		link LinkedIn, url='https://www.linkedin.com/company/Harmoney/'
			image LinkedIn, url="data:image/svg+xml,%3csvg%20width='20'%20height='20'%20viewBox='0%200%2020%2020'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='LinkedIn_icon%201'%20clip-path='url(%23clip0_1101_206)'%3e%3cg%20id='Group'%3e%3cpath%20id='Vector'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M2.22222%2020H17.7778C19.0051%2020%2020%2019.0051%2020%2017.7778V2.22222C20%200.994923%2019.0051%200%2017.7778%200H2.22222C0.994923%200%200%200.994923%200%202.22222V17.7778C0%2019.0051%200.994923%2020%202.22222%2020Z'%20fill='%23007EBB'/%3e%3cpath%20id='Vector_2'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M17.2218%2017.2218H14.2539V12.1668C14.2539%2010.7809%2013.7273%2010.0064%2012.6303%2010.0064C11.437%2010.0064%2010.8135%2010.8124%2010.8135%2012.1668V17.2218H7.95327V7.59216H10.8135V8.88927C10.8135%208.88927%2011.6735%207.29796%2013.7169%207.29796C15.7595%207.29796%2017.2218%208.54525%2017.2218%2011.1249V17.2218ZM4.54105%206.33124C3.5668%206.33124%202.77734%205.53558%202.77734%204.55429C2.77734%203.573%203.5668%202.77734%204.54105%202.77734C5.5153%202.77734%206.30429%203.573%206.30429%204.55429C6.30429%205.53558%205.5153%206.33124%204.54105%206.33124ZM3.06416%2017.2218H6.04662V7.59216H3.06416V17.2218Z'%20fill='white'/%3e%3c/g%3e%3c/g%3e%3cdefs%3e%3cclipPath%20id='clip0_1101_206'%3e%3crect%20width='20'%20height='20'%20fill='white'/%3e%3c/clipPath%3e%3c/defs%3e%3c/svg%3e"
		link Bond Search, url='https://www.harmoney.in/find'
		link About Us, url='https://www.harmoney.in/about'
		link Contact us
		link Terms and Conditions, url='https://www.harmoney.in/terms'
		link Privacy Policy, url='https://www.harmoney.in/privacy'
	generic
		[b] dialog Intercom live chat banner, center=(960,25), modal=False, title=Intercom live chat banner
```
</details>

**Reasoning for action:** I clicked on the Products button (element 214) because it is critical to access the relevant information about the DART product, which is the next step in completing my task of exploring Harmoney's fixed income trading services. By clicking this button, I expect to be presented with a list of products, including DART, allowing me to proceed to the detailed product page.

**Action:** click(214) # Click on the Products button to explore the offerings.

**Change Description:** After clicking the 'Products' button, a focused menu appeared revealing links to the DART and FIND products, allowing users to explore specific offerings for bond trading and reference data.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.harmoney.in/

https://www.harmoney.in/product/dart

**Content (before/after):** 

```
RootWebArea Harmoney | Digitizing bond markets, focused, url='https://www.harmoney.in/'
	navigation
		[199] link Brand Icon Harmoney, center=(82,76), inner_text=Harmoney, url='https://www.harmoney.in/'
			image Brand Icon, url="data:image/svg+xml,%3csvg%20width='24'%20height='24'%20viewBox='0%200%2024%2024'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='Frame%201'%3e%3cpath%20id='Vector'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.0803%203.74219C9.87563%205.76415%208.47104%208.81262%208.4533%2012.2188C8.43555%2015.6406%209.80456%2018.7046%2011.9914%2020.7422C11.3514%2017.6626%2011.9381%2014.2874%2013.8049%2011.5655C14.2672%2010.8812%2014.8006%2010.2591%2015.3873%209.73029C14.8895%207.35061%2013.716%205.26647%2012.0803%203.74219Z'%20fill='%23244275'/%3e%3cpath%20id='Vector_2'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M2.2587%207.16406C1.6186%2010.2436%202.15203%2013.6032%204.01888%2016.325C5.86798%2019.0625%208.53491%2020.5867%2011.3974%2020.7422C9.19275%2018.7047%207.93041%2015.6407%207.93041%2012.2345C7.93041%2011.3635%208.01933%2010.5236%208.19707%209.69923C6.49022%208.14391%204.39231%207.27289%202.2587%207.16406ZM21.7628%207.24176C14.2421%208.43945%2011.4329%2015.1119%2012.5175%2020.7422C20.0738%2019.5446%2022.883%2012.9033%2021.7628%207.24176Z'%20fill='%23244275'/%3e%3c/g%3e%3c/svg%3e"
			StaticText Harmoney
```
<details><summary>Show more</summary>

```
		list
			listitem
				[214] button Products, center=(235,76), type=button
					image
				list
					listitem
						[345] link DART Single Screen Trading For Indian Bonds, center=(385,145), inner_text=DART
Single Screen Trading For Indian Bonds, url='https://www.harmoney.in/product/dart'
					listitem
						[349] link FIND The Only Bond Reference Data Source You Need, center=(385,205), inner_text=FIND
The Only Bond Reference Data Source You Need, url='https://www.harmoney.in/product/find'
				menu, focused, orientation='vertical'
			listitem
				[217] button Resources, center=(361,76), type=button
					image
		[220] link Sign Up, center=(1786,76), url='https://www.harmoney.in/client/register'
		[221] link Login, center=(1869,76), url='https://www.harmoney.in/auth/login'
			button Login
	heading Your Market Connection
	paragraph
		StaticText Information. Efficiency. Fully Integrated
	[228] link Get Started, center=(360,469), url='https://www.harmoney.in/client/register'
		button Get Started
	StaticText 150+
	StaticText Participants
	StaticText 5000+ Cr
	StaticText Processed Volume
	StaticText 30,000+
	StaticText Bonds
	heading Fixed Income Trading Software
	paragraph
		StaticText for Banks, Mutual Funds, Broker-Dealers & Wealth Managers
	image, url="data:image/svg+xml,%3csvg%20width='65'%20height='64'%20viewBox='0%200%2065%2064'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cmask%20id='mask0_1551_22'%20style='mask-type:alpha'%20maskUnits='userSpaceOnUse'%20x='0'%20y='0'%20width='65'%20height='64'%3e%3crect%20x='64.3333'%20y='64'%20width='64'%20height='64'%20transform='rotate(-180%2064.3333%2064)'%20fill='%23D9D9D9'/%3e%3c/mask%3e%3cg%20mask='url(%23mask0_1551_22)'%3e%3cpath%20d='M43.4613%2010.6153L52.2307%2019.3847L50.3947%2021.272L44.7947%2015.6873L44.7947%2033.436C44.7947%2033.9147%2044.9487%2034.3078%2045.2567%2034.6153C45.5642%2034.9229%2045.9573%2035.0767%2046.436%2035.0767L54.0767%2035.0767C55.27%2035.0767%2056.2862%2035.4965%2057.1253%2036.336C57.9649%2037.1751%2058.3847%2038.1913%2058.3847%2039.3847L58.3847%2053.3333L55.718%2053.3333L55.718%2039.3847C55.718%2038.906%2055.5642%2038.5129%2055.2567%2038.2053C54.9487%2037.8973%2054.5553%2037.7433%2054.0767%2037.7433L46.436%2037.7433C45.2427%2037.7433%2044.2265%2037.3238%2043.3873%2036.4847C42.5478%2035.6451%2042.128%2034.6289%2042.128%2033.436L42.128%2015.7387L36.5433%2021.272L34.692%2019.3847L43.4613%2010.6153ZM21.2053%2010.6153L29.9747%2019.3847L28.1387%2021.272L22.5387%2015.6873L22.5387%2033.436C22.5387%2034.6289%2022.1189%2035.6451%2021.2793%2036.4847C20.4402%2037.3238%2019.424%2037.7433%2018.2307%2037.7433L10.59%2037.7433C10.1113%2037.7433%209.71801%2037.8973%209.41001%2038.2053C9.10246%2038.5129%208.94867%2038.906%208.94867%2039.3847L8.94867%2053.3333L6.28201%2053.3333L6.28201%2039.3847C6.28201%2038.1913%206.70178%2037.1751%207.54134%2036.336C8.38045%2035.4964%209.39667%2035.0767%2010.59%2035.0767L18.2307%2035.0767C18.7093%2035.0767%2019.1025%2034.9229%2019.41%2034.6153C19.718%2034.3078%2019.872%2033.9147%2019.872%2033.436L19.872%2015.672L14.2873%2021.272L12.436%2019.3847L21.2053%2010.6153Z'%20fill='%23E8402B'/%3e%3c/g%3e%3c/svg%3e"
	heading Market Aggregation
	paragraph
		StaticText Single screen access to market information and your trading community
	image, url="data:image/svg+xml,%3csvg%20width='64'%20height='64'%20viewBox='0%200%2064%2064'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cpath%20d='M32%2061.5C15.725%2061.5%202.5%2048.275%202.5%2032C2.5%2015.725%2015.725%202.5%2032%202.5C48.275%202.5%2061.5%2015.725%2061.5%2032C61.5%2048.275%2048.275%2061.5%2032%2061.5ZM32%205.975C17.65%205.975%205.975%2017.65%205.975%2032C5.975%2046.35%2017.65%2058.025%2032%2058.025C46.35%2058.025%2058.025%2046.35%2058.025%2032C58.025%2017.65%2046.35%205.975%2032%205.975ZM48.6%2029.55H15.4C14.4%2029.55%2013.55%2028.725%2013.55%2027.7C13.55%2026.675%2014.375%2025.85%2015.4%2025.85H42.275L38%2023.175C37.2%2022.675%2036.95%2021.575%2037.425%2020.75L37.575%2020.5C38.05%2019.675%2039.125%2019.4%2039.925%2019.9L49.6%2025.975C50.15%2026.325%2050.425%2026.925%2050.4%2027.55C50.4%2027.6%2050.425%2027.625%2050.425%2027.675C50.45%2028.725%2049.6%2029.55%2048.6%2029.55ZM13.575%2037.45V37.425C13.625%2036.85%2013.925%2036.375%2014.375%2036.05C14.4%2036.025%2014.425%2036.025%2014.45%2036C14.575%2035.925%2014.7%2035.85%2014.85%2035.8C14.975%2035.75%2015.075%2035.75%2015.2%2035.725C15.25%2035.725%2015.325%2035.7%2015.375%2035.7H48.575C49.575%2035.7%2050.425%2036.525%2050.425%2037.55C50.425%2038.575%2049.6%2039.4%2048.575%2039.4H21.7L25.85%2042.05C26.65%2042.55%2026.9%2043.65%2026.425%2044.475L26.275%2044.725C25.8%2045.55%2024.75%2045.825%2023.95%2045.325L14.35%2039.225C13.825%2038.9%2013.575%2038.3%2013.575%2037.7C13.575%2037.65%2013.55%2037.6%2013.55%2037.55C13.575%2037.5%2013.575%2037.475%2013.575%2037.45Z'%20fill='%23E8402B'/%3e%3c/svg%3e"
	heading Efficient Trading Workflows
	paragraph
		StaticText AI powered quote detection & ticketing with automated workflows
	image, url='https://www.harmoney.in/_nuxt/integrated.BRG7uysc.svg'
	heading Agile & Integrated
	paragraph
		StaticText End-to-end connectivity with clearing houses STP with OMS, EMS & portfolio systems
	heading One Screen, Many Capabilities
	paragraph
		StaticText Unlock Efficiency In Bond Trading
	heading DART
	paragraph
		StaticText Fixed Income Trading From A Single-Screen
	list
		listitem
			ListMarker •
			StaticText Chat with your fixed income community
		listitem
			ListMarker •
			StaticText AI-powered quote detection & ticketing
		listitem
			ListMarker •
			StaticText Enhanced Efficiency through NSE/BSE Integration
	link Know More, url='https://www.harmoney.in/product/dart'
		button Know More
	image, url='https://www.harmoney.in/_ipx/_/images/offerings/livemarket1.png'
	image FIND-screen, url='https://www.harmoney.in/_nuxt/product_find.BdWNZeob.png'
	heading FIND
	paragraph
		StaticText Best In Class, Rich Database Built With Intelligence
	list
		listitem
			ListMarker •
			StaticText Comprehensive reference data for 30,000+ securities
		listitem
			ListMarker •
			StaticText Bond cashflows & price calculator
		listitem
			ListMarker •
			StaticText Real-time & historical trade data access
	link Know More, url='https://www.harmoney.in/product/find'
		button Know More
	contentinfo
		image Brand Icon, url="data:image/svg+xml,%3csvg%20width='24'%20height='24'%20viewBox='0%200%2024%2024'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='Frame%201'%3e%3cpath%20id='Vector'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.0803%203.74219C9.87563%205.76415%208.47104%208.81262%208.4533%2012.2188C8.43555%2015.6406%209.80456%2018.7046%2011.9914%2020.7422C11.3514%2017.6626%2011.9381%2014.2874%2013.8049%2011.5655C14.2672%2010.8812%2014.8006%2010.2591%2015.3873%209.73029C14.8895%207.35061%2013.716%205.26647%2012.0803%203.74219Z'%20fill='white'/%3e%3cpath%20id='Vector_2'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M2.2587%207.16406C1.6186%2010.2436%202.15203%2013.6032%204.01888%2016.325C5.86798%2019.0625%208.53491%2020.5867%2011.3974%2020.7422C9.19275%2018.7047%207.93041%2015.6407%207.93041%2012.2345C7.93041%2011.3635%208.01933%2010.5236%208.19707%209.69923C6.49022%208.14391%204.39231%207.27289%202.2587%207.16406ZM21.7628%207.24176C14.2421%208.43945%2011.4329%2015.1119%2012.5175%2020.7422C20.0738%2019.5446%2022.883%2012.9033%2021.7628%207.24176Z'%20fill='white'/%3e%3c/g%3e%3c/svg%3e"
		StaticText Harmoney
		StaticText Jai Villa, Dev Shakti,
		StaticText Tilak Road, Santacruz(W),
		StaticText Mumbai 400054
		link LinkedIn, url='https://www.linkedin.com/company/Harmoney/'
			image LinkedIn, url="data:image/svg+xml,%3csvg%20width='20'%20height='20'%20viewBox='0%200%2020%2020'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='LinkedIn_icon%201'%20clip-path='url(%23clip0_1101_206)'%3e%3cg%20id='Group'%3e%3cpath%20id='Vector'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M2.22222%2020H17.7778C19.0051%2020%2020%2019.0051%2020%2017.7778V2.22222C20%200.994923%2019.0051%200%2017.7778%200H2.22222C0.994923%200%200%200.994923%200%202.22222V17.7778C0%2019.0051%200.994923%2020%202.22222%2020Z'%20fill='%23007EBB'/%3e%3cpath%20id='Vector_2'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M17.2218%2017.2218H14.2539V12.1668C14.2539%2010.7809%2013.7273%2010.0064%2012.6303%2010.0064C11.437%2010.0064%2010.8135%2010.8124%2010.8135%2012.1668V17.2218H7.95327V7.59216H10.8135V8.88927C10.8135%208.88927%2011.6735%207.29796%2013.7169%207.29796C15.7595%207.29796%2017.2218%208.54525%2017.2218%2011.1249V17.2218ZM4.54105%206.33124C3.5668%206.33124%202.77734%205.53558%202.77734%204.55429C2.77734%203.573%203.5668%202.77734%204.54105%202.77734C5.5153%202.77734%206.30429%203.573%206.30429%204.55429C6.30429%205.53558%205.5153%206.33124%204.54105%206.33124ZM3.06416%2017.2218H6.04662V7.59216H3.06416V17.2218Z'%20fill='white'/%3e%3c/g%3e%3c/g%3e%3cdefs%3e%3cclipPath%20id='clip0_1101_206'%3e%3crect%20width='20'%20height='20'%20fill='white'/%3e%3c/clipPath%3e%3c/defs%3e%3c/svg%3e"
		link Bond Search, url='https://www.harmoney.in/find'
		link About Us, url='https://www.harmoney.in/about'
		link Contact us
		link Terms and Conditions, url='https://www.harmoney.in/terms'
		link Privacy Policy, url='https://www.harmoney.in/privacy'
	generic
		[b] dialog Intercom live chat banner, center=(960,25), modal=False, title=Intercom live chat banner
```
</details>



```
RootWebArea Harmoney | Digitizing bond markets, focused, url='https://www.harmoney.in/product/dart'
	navigation
		[355] link Brand Icon DART by Harmoney, center=(66,76), inner_text=DART
by Harmoney, url='https://www.harmoney.in/'
			image Brand Icon, url="data:image/svg+xml,%3csvg%20width='24'%20height='24'%20viewBox='0%200%2024%2024'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='Frame%201'%3e%3cpath%20id='Vector'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.0803%203.74219C9.87563%205.76415%208.47104%208.81262%208.4533%2012.2188C8.43555%2015.6406%209.80456%2018.7046%2011.9914%2020.7422C11.3514%2017.6626%2011.9381%2014.2874%2013.8049%2011.5655C14.2672%2010.8812%2014.8006%2010.2591%2015.3873%209.73029C14.8895%207.35061%2013.716%205.26647%2012.0803%203.74219Z'%20fill='%23244275'/%3e%3cpath%20id='Vector_2'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M2.2587%207.16406C1.6186%2010.2436%202.15203%2013.6032%204.01888%2016.325C5.86798%2019.0625%208.53491%2020.5867%2011.3974%2020.7422C9.19275%2018.7047%207.93041%2015.6407%207.93041%2012.2345C7.93041%2011.3635%208.01933%2010.5236%208.19707%209.69923C6.49022%208.14391%204.39231%207.27289%202.2587%207.16406ZM21.7628%207.24176C14.2421%208.43945%2011.4329%2015.1119%2012.5175%2020.7422C20.0738%2019.5446%2022.883%2012.9033%2021.7628%207.24176Z'%20fill='%23244275'/%3e%3c/g%3e%3c/svg%3e"
```
<details><summary>Show more</summary>

```
			StaticText DART
			StaticText by Harmoney
		[364] link Sign Up, center=(1786,76), url='https://www.harmoney.in/client/register'
		[365] link Login, center=(1869,76), url='https://www.harmoney.in/auth/login'
			button Login
	heading One Screen, Many Capabilities
	paragraph
		StaticText Unlock Efficiency In Bond Trading
	[373] link Get Started, center=(458,438), url='https://www.harmoney.in/client/register'
		button Get Started
	StaticText Information
	StaticText Aggregate view of the market
	StaticText Community
	StaticText Chat with traders
	StaticText Execution
	StaticText Manage trading workflows
	image, url='https://www.harmoney.in/_ipx/_/images/dart/dart_feature_1.png'
	[376] video, center=(917,308)
	paragraph
		StaticText Community With AI-Powered Trade Discovery
	paragraph
		StaticText Integrated Chat With AI-Powered Quote Detection
	paragraph
		StaticText Automated Ticketing & Order Management
	paragraph
		StaticText AI-Powered Trade Ticket Generation And Enhanced Order Management For Increased Efficiency
	image, url='https://www.harmoney.in/_ipx/_/images/dart/dart_feature_2.png'
	image, url='https://www.harmoney.in/_ipx/_/images/dart/dart_feature_3.png'
	paragraph
		StaticText Seamless STP
	paragraph
		StaticText OTC & RFQ Trade Integration With Exchanges & Internal Softwares
	image build-with-us, url='https://www.harmoney.in/_nuxt/dart_illustration.BU-AnRg4.svg'
	heading Ready to streamline your fixed-income trades in one place?
	paragraph
		StaticText Get in touch with our sales team for onboarding
	link Contact Us, url='https://www.harmoney.in/contact'
		button Contact Us
	contentinfo
		image Brand Icon, url="data:image/svg+xml,%3csvg%20width='24'%20height='24'%20viewBox='0%200%2024%2024'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='Frame%201'%3e%3cpath%20id='Vector'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.0803%203.74219C9.87563%205.76415%208.47104%208.81262%208.4533%2012.2188C8.43555%2015.6406%209.80456%2018.7046%2011.9914%2020.7422C11.3514%2017.6626%2011.9381%2014.2874%2013.8049%2011.5655C14.2672%2010.8812%2014.8006%2010.2591%2015.3873%209.73029C14.8895%207.35061%2013.716%205.26647%2012.0803%203.74219Z'%20fill='white'/%3e%3cpath%20id='Vector_2'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M2.2587%207.16406C1.6186%2010.2436%202.15203%2013.6032%204.01888%2016.325C5.86798%2019.0625%208.53491%2020.5867%2011.3974%2020.7422C9.19275%2018.7047%207.93041%2015.6407%207.93041%2012.2345C7.93041%2011.3635%208.01933%2010.5236%208.19707%209.69923C6.49022%208.14391%204.39231%207.27289%202.2587%207.16406ZM21.7628%207.24176C14.2421%208.43945%2011.4329%2015.1119%2012.5175%2020.7422C20.0738%2019.5446%2022.883%2012.9033%2021.7628%207.24176Z'%20fill='white'/%3e%3c/g%3e%3c/svg%3e"
		StaticText Harmoney
		StaticText Jai Villa, Dev Shakti,
		StaticText Tilak Road, Santacruz(W),
		StaticText Mumbai 400054
		link LinkedIn, url='https://www.linkedin.com/company/Harmoney/'
			image LinkedIn, url="data:image/svg+xml,%3csvg%20width='20'%20height='20'%20viewBox='0%200%2020%2020'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='LinkedIn_icon%201'%20clip-path='url(%23clip0_1101_206)'%3e%3cg%20id='Group'%3e%3cpath%20id='Vector'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M2.22222%2020H17.7778C19.0051%2020%2020%2019.0051%2020%2017.7778V2.22222C20%200.994923%2019.0051%200%2017.7778%200H2.22222C0.994923%200%200%200.994923%200%202.22222V17.7778C0%2019.0051%200.994923%2020%202.22222%2020Z'%20fill='%23007EBB'/%3e%3cpath%20id='Vector_2'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M17.2218%2017.2218H14.2539V12.1668C14.2539%2010.7809%2013.7273%2010.0064%2012.6303%2010.0064C11.437%2010.0064%2010.8135%2010.8124%2010.8135%2012.1668V17.2218H7.95327V7.59216H10.8135V8.88927C10.8135%208.88927%2011.6735%207.29796%2013.7169%207.29796C15.7595%207.29796%2017.2218%208.54525%2017.2218%2011.1249V17.2218ZM4.54105%206.33124C3.5668%206.33124%202.77734%205.53558%202.77734%204.55429C2.77734%203.573%203.5668%202.77734%204.54105%202.77734C5.5153%202.77734%206.30429%203.573%206.30429%204.55429C6.30429%205.53558%205.5153%206.33124%204.54105%206.33124ZM3.06416%2017.2218H6.04662V7.59216H3.06416V17.2218Z'%20fill='white'/%3e%3c/g%3e%3c/g%3e%3cdefs%3e%3cclipPath%20id='clip0_1101_206'%3e%3crect%20width='20'%20height='20'%20fill='white'/%3e%3c/clipPath%3e%3c/defs%3e%3c/svg%3e"
		link Bond Search, url='https://www.harmoney.in/find'
		link About Us, url='https://www.harmoney.in/about'
		link Contact us
		link Terms and Conditions, url='https://www.harmoney.in/terms'
		link Privacy Policy, url='https://www.harmoney.in/privacy'
	generic
		[b] dialog Intercom live chat banner, center=(960,25), modal=False, title=Intercom live chat banner
```
</details>

**Reasoning for action:** By clicking on the DART product link, I navigate to the page that provides comprehensive details about the DART product, including its features. This step is crucial as it meets the requirement of exploring product details before proceeding to registration. Once I am on this page, I can review all necessary information about DART before moving forward to initiate the registration process, which aligns with the user's goal.

**Action:** click(345) # Click on the DART product link to explore its details.

**Change Description:** After clicking on the DART product link, the browser navigated to the DART product details page, changing the URL to 'https://www.harmoney.in/product/dart' and updating the heading and information displayed to focus on DART's features and functionalities.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.harmoney.in/product/dart

https://www.harmoney.in/client/register

**Content (before/after):** 

```
RootWebArea Harmoney | Digitizing bond markets, focused, url='https://www.harmoney.in/product/dart'
	navigation
		[355] link Brand Icon DART by Harmoney, center=(66,76), inner_text=DART
by Harmoney, url='https://www.harmoney.in/'
			image Brand Icon, url="data:image/svg+xml,%3csvg%20width='24'%20height='24'%20viewBox='0%200%2024%2024'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='Frame%201'%3e%3cpath%20id='Vector'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.0803%203.74219C9.87563%205.76415%208.47104%208.81262%208.4533%2012.2188C8.43555%2015.6406%209.80456%2018.7046%2011.9914%2020.7422C11.3514%2017.6626%2011.9381%2014.2874%2013.8049%2011.5655C14.2672%2010.8812%2014.8006%2010.2591%2015.3873%209.73029C14.8895%207.35061%2013.716%205.26647%2012.0803%203.74219Z'%20fill='%23244275'/%3e%3cpath%20id='Vector_2'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M2.2587%207.16406C1.6186%2010.2436%202.15203%2013.6032%204.01888%2016.325C5.86798%2019.0625%208.53491%2020.5867%2011.3974%2020.7422C9.19275%2018.7047%207.93041%2015.6407%207.93041%2012.2345C7.93041%2011.3635%208.01933%2010.5236%208.19707%209.69923C6.49022%208.14391%204.39231%207.27289%202.2587%207.16406ZM21.7628%207.24176C14.2421%208.43945%2011.4329%2015.1119%2012.5175%2020.7422C20.0738%2019.5446%2022.883%2012.9033%2021.7628%207.24176Z'%20fill='%23244275'/%3e%3c/g%3e%3c/svg%3e"
```
<details><summary>Show more</summary>

```
			StaticText DART
			StaticText by Harmoney
		[364] link Sign Up, center=(1786,76), url='https://www.harmoney.in/client/register'
		[365] link Login, center=(1869,76), url='https://www.harmoney.in/auth/login'
			button Login
	heading One Screen, Many Capabilities
	paragraph
		StaticText Unlock Efficiency In Bond Trading
	[373] link Get Started, center=(458,438), url='https://www.harmoney.in/client/register'
		button Get Started
	StaticText Information
	StaticText Aggregate view of the market
	StaticText Community
	StaticText Chat with traders
	StaticText Execution
	StaticText Manage trading workflows
	image, url='https://www.harmoney.in/_ipx/_/images/dart/dart_feature_1.png'
	[376] video, center=(917,308)
	paragraph
		StaticText Community With AI-Powered Trade Discovery
	paragraph
		StaticText Integrated Chat With AI-Powered Quote Detection
	paragraph
		StaticText Automated Ticketing & Order Management
	paragraph
		StaticText AI-Powered Trade Ticket Generation And Enhanced Order Management For Increased Efficiency
	image, url='https://www.harmoney.in/_ipx/_/images/dart/dart_feature_2.png'
	image, url='https://www.harmoney.in/_ipx/_/images/dart/dart_feature_3.png'
	paragraph
		StaticText Seamless STP
	paragraph
		StaticText OTC & RFQ Trade Integration With Exchanges & Internal Softwares
	image build-with-us, url='https://www.harmoney.in/_nuxt/dart_illustration.BU-AnRg4.svg'
	heading Ready to streamline your fixed-income trades in one place?
	paragraph
		StaticText Get in touch with our sales team for onboarding
	link Contact Us, url='https://www.harmoney.in/contact'
		button Contact Us
	contentinfo
		image Brand Icon, url="data:image/svg+xml,%3csvg%20width='24'%20height='24'%20viewBox='0%200%2024%2024'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='Frame%201'%3e%3cpath%20id='Vector'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.0803%203.74219C9.87563%205.76415%208.47104%208.81262%208.4533%2012.2188C8.43555%2015.6406%209.80456%2018.7046%2011.9914%2020.7422C11.3514%2017.6626%2011.9381%2014.2874%2013.8049%2011.5655C14.2672%2010.8812%2014.8006%2010.2591%2015.3873%209.73029C14.8895%207.35061%2013.716%205.26647%2012.0803%203.74219Z'%20fill='white'/%3e%3cpath%20id='Vector_2'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M2.2587%207.16406C1.6186%2010.2436%202.15203%2013.6032%204.01888%2016.325C5.86798%2019.0625%208.53491%2020.5867%2011.3974%2020.7422C9.19275%2018.7047%207.93041%2015.6407%207.93041%2012.2345C7.93041%2011.3635%208.01933%2010.5236%208.19707%209.69923C6.49022%208.14391%204.39231%207.27289%202.2587%207.16406ZM21.7628%207.24176C14.2421%208.43945%2011.4329%2015.1119%2012.5175%2020.7422C20.0738%2019.5446%2022.883%2012.9033%2021.7628%207.24176Z'%20fill='white'/%3e%3c/g%3e%3c/svg%3e"
		StaticText Harmoney
		StaticText Jai Villa, Dev Shakti,
		StaticText Tilak Road, Santacruz(W),
		StaticText Mumbai 400054
		link LinkedIn, url='https://www.linkedin.com/company/Harmoney/'
			image LinkedIn, url="data:image/svg+xml,%3csvg%20width='20'%20height='20'%20viewBox='0%200%2020%2020'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='LinkedIn_icon%201'%20clip-path='url(%23clip0_1101_206)'%3e%3cg%20id='Group'%3e%3cpath%20id='Vector'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M2.22222%2020H17.7778C19.0051%2020%2020%2019.0051%2020%2017.7778V2.22222C20%200.994923%2019.0051%200%2017.7778%200H2.22222C0.994923%200%200%200.994923%200%202.22222V17.7778C0%2019.0051%200.994923%2020%202.22222%2020Z'%20fill='%23007EBB'/%3e%3cpath%20id='Vector_2'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M17.2218%2017.2218H14.2539V12.1668C14.2539%2010.7809%2013.7273%2010.0064%2012.6303%2010.0064C11.437%2010.0064%2010.8135%2010.8124%2010.8135%2012.1668V17.2218H7.95327V7.59216H10.8135V8.88927C10.8135%208.88927%2011.6735%207.29796%2013.7169%207.29796C15.7595%207.29796%2017.2218%208.54525%2017.2218%2011.1249V17.2218ZM4.54105%206.33124C3.5668%206.33124%202.77734%205.53558%202.77734%204.55429C2.77734%203.573%203.5668%202.77734%204.54105%202.77734C5.5153%202.77734%206.30429%203.573%206.30429%204.55429C6.30429%205.53558%205.5153%206.33124%204.54105%206.33124ZM3.06416%2017.2218H6.04662V7.59216H3.06416V17.2218Z'%20fill='white'/%3e%3c/g%3e%3c/g%3e%3cdefs%3e%3cclipPath%20id='clip0_1101_206'%3e%3crect%20width='20'%20height='20'%20fill='white'/%3e%3c/clipPath%3e%3c/defs%3e%3c/svg%3e"
		link Bond Search, url='https://www.harmoney.in/find'
		link About Us, url='https://www.harmoney.in/about'
		link Contact us
		link Terms and Conditions, url='https://www.harmoney.in/terms'
		link Privacy Policy, url='https://www.harmoney.in/privacy'
	generic
		[b] dialog Intercom live chat banner, center=(960,25), modal=False, title=Intercom live chat banner
```
</details>



```
RootWebArea Harmoney | Digitizing bond markets, focused, url='https://www.harmoney.in/client/register'
	navigation
		[454] link Brand Icon Harmoney, center=(82,76), inner_text=Harmoney, url='https://www.harmoney.in/'
			image Brand Icon, url="data:image/svg+xml,%3csvg%20width='24'%20height='24'%20viewBox='0%200%2024%2024'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='Frame%201'%3e%3cpath%20id='Vector'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.0803%203.74219C9.87563%205.76415%208.47104%208.81262%208.4533%2012.2188C8.43555%2015.6406%209.80456%2018.7046%2011.9914%2020.7422C11.3514%2017.6626%2011.9381%2014.2874%2013.8049%2011.5655C14.2672%2010.8812%2014.8006%2010.2591%2015.3873%209.73029C14.8895%207.35061%2013.716%205.26647%2012.0803%203.74219Z'%20fill='%23244275'/%3e%3cpath%20id='Vector_2'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M2.2587%207.16406C1.6186%2010.2436%202.15203%2013.6032%204.01888%2016.325C5.86798%2019.0625%208.53491%2020.5867%2011.3974%2020.7422C9.19275%2018.7047%207.93041%2015.6407%207.93041%2012.2345C7.93041%2011.3635%208.01933%2010.5236%208.19707%209.69923C6.49022%208.14391%204.39231%207.27289%202.2587%207.16406ZM21.7628%207.24176C14.2421%208.43945%2011.4329%2015.1119%2012.5175%2020.7422C20.0738%2019.5446%2022.883%2012.9033%2021.7628%207.24176Z'%20fill='%23244275'/%3e%3c/g%3e%3c/svg%3e"
			StaticText Harmoney
```
<details><summary>Show more</summary>

```
		[462] link Sign Up, center=(1786,76), url='https://www.harmoney.in/client/register'
		[463] link Login, center=(1869,76), url='https://www.harmoney.in/auth/login'
			button Login
	heading Level Up Your Bond Trading Experience
	heading Single Screen That Brings Efficiency And Ease Of Execution
	paragraph
		image
		StaticText Access Your Trading Counterparties With Real-Time Quote Aggregation
	paragraph
		image
		StaticText Integrated Chat With AI-Powered Quote Detection And Trade Discovery
	paragraph
		image
		StaticText Automated Ticketing And STP Integration For Increased Efficiency
	image Brand Icon, url="data:image/svg+xml,%3csvg%20width='24'%20height='24'%20viewBox='0%200%2024%2024'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='Frame%201'%3e%3cpath%20id='Vector'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M12.0803%203.74219C9.87563%205.76415%208.47104%208.81262%208.4533%2012.2188C8.43555%2015.6406%209.80456%2018.7046%2011.9914%2020.7422C11.3514%2017.6626%2011.9381%2014.2874%2013.8049%2011.5655C14.2672%2010.8812%2014.8006%2010.2591%2015.3873%209.73029C14.8895%207.35061%2013.716%205.26647%2012.0803%203.74219Z'%20fill='%23244275'/%3e%3cpath%20id='Vector_2'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M2.2587%207.16406C1.6186%2010.2436%202.15203%2013.6032%204.01888%2016.325C5.86798%2019.0625%208.53491%2020.5867%2011.3974%2020.7422C9.19275%2018.7047%207.93041%2015.6407%207.93041%2012.2345C7.93041%2011.3635%208.01933%2010.5236%208.19707%209.69923C6.49022%208.14391%204.39231%207.27289%202.2587%207.16406ZM21.7628%207.24176C14.2421%208.43945%2011.4329%2015.1119%2012.5175%2020.7422C20.0738%2019.5446%2022.883%2012.9033%2021.7628%207.24176Z'%20fill='%23244275'/%3e%3c/g%3e%3c/svg%3e"
	heading Sign Up to Harmoney
	LabelText
		StaticText Email Address
	[490] textbox Email Address, center=(1308,642), autocomplete=off, contenteditable=True, required, type=email
	button Next, disabled=True
	paragraph
		StaticText Already have an account?
		[495] link Sign In, center=(1389,739), url='https://www.harmoney.in/auth/login/'
	generic
		[b] dialog Intercom live chat banner, center=(960,25), modal=False, title=Intercom live chat banner
```
</details>

**Reasoning for action:** By clicking on the 'Get Started' button, I am initiating the registration process for the DART product, which is essential to fulfill the user story. This action leads me to the registration page, where I expect to encounter a sign-up form, aligning with the user's goal of utilizing Harmoney's fixed income trading services.

**Action:** click(373) # Click on the Get Started button to explore registration options.

**Change Description:** After clicking the 'Get Started' button, the browser navigated to the registration page at 'https://www.harmoney.in/client/register', where the heading changed to 'Sign Up to Harmoney' and a form for email address entry was displayed, including a disabled 'Next' button.

**Screenshot before:****Screenshot after:**---


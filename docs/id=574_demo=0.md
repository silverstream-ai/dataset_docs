# Task

**User Story for Investment Strategy Exploration**

As a user interested in investment strategies,
I explore various index investment strategies,
so that I can select an investment strategy that aligns with my risk tolerance.

**Success definition:** Given I am on the Double Finance Explore page without needing to log in
When I click on the 'Explore Indexes' button to view available investment strategies and select 'High' risk tolerance, then submit my choice
Then I should see my options for different investment strategies categorized by risk, along with detailed information about each strategy.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://double.finance/

https://double.finance/p/explore

**Content (before/after):** 

```
RootWebArea Double Finance | Direct Indexing, ETFs & Automated Investing with Zero AUM Fees, focused, url='https://double.finance/'
	main
		[227] link, center=(118,32), url='https://double.finance/'
			image
		list
```
<details><summary>Show more</summary>

```
			[231] link Explore, center=(805,31), url='https://double.finance/p/explore'
			[233] link Pricing, center=(891,31), url='https://double.finance/pricing'
			generic, hasPopup='menu'
				StaticText Resources
				[235] image, center=(1042,33)
			[237] link Contact, center=(1113,31), url='https://double.finance/contact'
		[239] link Sign In, center=(1724,32), url='https://double.finance/login'
			button Sign In
		[241] link Sign Up, center=(1816,32), url='https://double.finance/sign-up'
			button Sign Up
		image Y Combinator, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/y-vector.svg'
		StaticText Backed by
		StaticText Y Combinator
		heading Zero Expense Ratio Index Investing
		paragraph
			StaticText Choose from
			StaticText 50+ broad stock market indexes
			StaticText or build your own.
			StaticText We handle the management—including tax loss harvesting—for
			link just $1/month., url='https://double.finance/pricing'
		[269] link Get Started, center=(266,618), url='https://double.finance/sign-up'
		[270] button Explore Indexes, center=(440,618)
			link Explore Indexes, url='https://double.finance/p/explore'
			image
		paragraph
			StaticText SEC
			StaticText Registered
		paragraph
			StaticText Apex Clearing
			StaticText Partner
		paragraph
			StaticText Fiduciary
		paragraph
			StaticText Why Double?
		heading Zero Expense Ratios
		paragraph
			StaticText We offer over 50 indexes with zero expense ratios. All you pay is a simple $1 monthly fee. This is a game-changer in the investing world, putting more money back in your pocket.
		heading Through Direct Indexing
		heading With Tax Loss Harvesting
		image Portfolio, url='https://double.finance/_next/image?url=%2Fimages%2Fhero.png&w=3840&q=75'
		image Portfolio, url='https://double.finance/_next/image?url=%2Fimages%2Ffeature-1.webp&w=3840&q=75'
		image Portfolio, url='https://double.finance/_next/image?url=%2Fimages%2Ffeature-2.webp&w=3840&q=75'
		image Portfolio, url='https://double.finance/_next/image?url=%2Fimages%2Ffeature-3.webp&w=3840&q=75'
		heading Indexes we havefor you
		StaticText Select a reference index like the US Top 500 or an ETF like ARKK and we will break it down into its components automatically for you to adjust as you see fit.
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $15,000
		paragraph
			StaticText SPY
		heading US Top 500
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText The textbook passive investment vehicle is generally considered to comprise of 500 of the largest stocks traded within the US. Double's take on this exposes a client to the US stock market in a diversified way without any expense ratio.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +14.31%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 502
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,200
		heading Growth at a Fair Price
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText These stocks above $1B in Market Cap are modestly valued (PE below 15) but are in the top 20% of stocks for revenue growth over the past 5 years. We weight them by market cap.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Health Care
		paragraph
			StaticText Top Holdings
		image HubSpot Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_HUBS.png&w=96&q=75'
		image Lemonade Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_LMND.png&w=96&q=75'
		image Flutter Entertainment Plc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_FLUT.png&w=96&q=75'
		image Armada Hoffler Properties Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AHH.png&w=96&q=75'
		image First Citizens Bancshares, Inc (NC) - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_FCNCA.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +23.94%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 235
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		paragraph
			StaticText SMH
		heading Semiconductors Index
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This index tracks a market-cap-weighted index of 25 of the largest US-listed semiconductors companies.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Taiwan Semiconductor Manufacturing - ADR logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TSM.png&w=96&q=75'
		image Broadcom Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
		image ASML Holding NV - New York Shares logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ASML.png&w=96&q=75'
		image Advanced Micro Devices Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMD.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +29.73%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 25
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $2,200
		paragraph
			StaticText OEF
		heading US 100
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This strategy offers a convenient way to access the largest 100 large-cap stocks across various sectors within the U.S. market.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +16.36%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 101
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Founder Mode
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText Stocks only get included in this basket, if the companies founders are still actively involved in the company. We equally weight them. Paul Graham talks a bit about
			link Founder Mode, url='https://paulgraham.com/foundermode.html'
			StaticText in a recent 2024 essay.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image American Homes 4 Rent - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMH.png&w=96&q=75'
		image Skechers U S A, Inc. - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_SKX.png&w=96&q=75'
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		image Zillow Group Inc - Ordinary Shares - Class C logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_Z.png&w=96&q=75'
		image Procore Technologies Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PCOR.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +22.20%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 92
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading The Top 20% Club
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This group of select stocks has achieved top 20% ratings in 1 year Revenue Growth, Free Cash Flow Per Share and 5 Year Return on Invested Capital. This select group of stocks is equally weighted to prevent any mega caps from dominating this Strategy.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		image F&G Annuities & Life Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_FG.png&w=96&q=75'
		image Mesabi Trust logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSB.png&w=96&q=75'
		image Jackson Financial Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JXN.png&w=96&q=75'
		image Wingstop Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WING.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +31.81%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 22
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,400
		paragraph
			StaticText DYNF
		heading U.S. Equity Factor Rotation
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText Optimizes returns by rotating investments across five historically successful styles: quality, value, size, minimum volatility, and momentum. By shifting focus among these factors based on forward-looking insights, this index capitalizes on market opportunities and provides a diversified approach to enhancing returns. This strategy offers a flexible and adaptive way to navigate changing markets, combining multiple styles in a single portfolio to maximize returns while managing risk.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +15.98%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 82
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $2,200
		paragraph
			StaticText QQQ
		heading Tech 100
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This index is closely related to the Nasdaq-100 Index, comprising major tech and growth-oriented companies. It aims to capture the tech sector's long-term growth prospects through exposure to the innovative and leading tech companies listed on the Nasdaq exchange.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		image Broadcom Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +20.08%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 101
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Diverse Bond Portfolio
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText For investors seeking lower risk than equities and those nearing retirement, bonds offer a compelling investment option for the upcoming years. We've curated a diverse portfolio of six popular bond ETFs, carefully allocating 60% to short-term Treasuries, 30% to corporate bonds, 8% to floating-rate bonds, and 2% to long-term Treasuries.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Schwab Strategic Trust - Schwab Short-Term U.S. Treasury ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F91159910411997986.png&w=96&q=75'
		image BlackRock Institutional Trust Company N.A. - iShares Short Treasury Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
		image BlackRock Institutional Trust Company N.A. - iShares 0-5 Year High Yield Corporate Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
		image BlackRock Institutional Trust Company N.A. - iShares Broad USD High Yield Corporate Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
		image SPDR Series Trust - SPDR Bloomberg Investment Grade Floating Rate ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9115112100114451159711010011253484845101116102451161146.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +2.48%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.13
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 6
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Ray Dalio's All Weather
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText Ray Dalio is a legendary investor, and this Strategy is a simplified version of techniques he's used at his famous hedge fund Bridgewater Associates. It combines 5 asset classes using ETFs, with a 55% allocation to fixed income. It's appropriate for investors with a balance approach to risk and return. Learn more about it
			link here, url='https://www.lazyportfolioetf.com/allocation/ray-dalio-all-weather/'
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image BlackRock Institutional Trust Company N.A. - iShares 20+ Year Treasury Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total Stock Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image BlackRock Institutional Trust Company N.A. - iShares 3-7 Year Treasury Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
		image DB Commodity Services LLC - Invesco DB Commodity Index Tracking Fund logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105110118101115991116.png&w=96&q=75'
		image SPDR Gold Trust - SPDR Gold Shares ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9115112100114451159711010011253484845101116102451161146.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +3.29%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.19
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 5
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $5,500
		paragraph
			StaticText VUG
		heading Growth Stocks
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText Growth Stocks focuses on companies with strong growth prospects, often found in sectors driving innovation and technological advancement. This ETF invests in companies demonstrating robust revenue and earnings growth, including technology giants, healthcare innovators, and consumer discretionary leaders.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +18.30%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 181
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $6,600
		paragraph
			StaticText VTV
		heading Value Stocks
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This Strategy targets undervalued stocks in the U.S. market, emphasizing companies with solid fundamentals and potential for long-term growth. Emphasizing sectors such as healthcare, financials, industrials, and consumer goods, it seeks opportunities where market prices may not fully reflect underlying value metrics like earnings and book value.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image JPMorgan Chase & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JPM.png&w=96&q=75'
		image Berkshire Hathaway Inc. - Ordinary Shares - Class B logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BRK.B.png&w=96&q=75'
		image Broadcom Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
		image Exxon Mobil Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_XOM.png&w=96&q=75'
		image Unitedhealth Group Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_UNH.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +10.46%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 331
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Dividend Kings with Cash
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText These stocks have a strong dividend yield 5% yearly, and also are in the top 40% of all stocks with regards to cash on hand, meaning they have a strong balance sheet to finance those future dividend payments. We weight these stocks equally.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image Newell Brands Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NWL.png&w=96&q=75'
		image Whirlpool Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WHR.png&w=96&q=75'
		image MPLX LP - Unit logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MPLX.png&w=96&q=75'
		image Icahn Enterprises L P - Unit logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_IEP.png&w=96&q=75'
		image Two Harbors Investment Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TWO.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +5.72%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 71
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Growing Small Caps
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText These small cap companies ($250M to $2B) are growing Revenue and Earnings at a nice clip. Equally weighted.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image Consolidated Water Co. Ltd. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CWCO.png&w=96&q=75'
		image EyePoint Pharmaceuticals Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_EYPT.png&w=96&q=75'
		image Accolade Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ACCD.png&w=96&q=75'
		image Aurinia Pharmaceuticals Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AUPH.png&w=96&q=75'
		image Graham Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GHM.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +18.28%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 80
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,900
		heading Highly Efficient & Growing
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText These stocks are highly efficient, with a Return on Invested Capital > 20%, while also growing earnings > 20% over the last 3 years. We exclude any stock with market cap above $1T, and weight the rest by Market Cap.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Novo Nordisk - ADR logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVO.png&w=96&q=75'
		image ASML Holding NV - New York Shares logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ASML.png&w=96&q=75'
		image Booking Holdings Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BKNG.png&w=96&q=75'
		image Arista Networks Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ANET.png&w=96&q=75'
		image Regeneron Pharmaceuticals, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_REGN.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +19.43%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 71
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Equal MAMAA
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText First, it was FAANG, then names changed, and one got dropped; now, we have the familiar faces of Meta, Amazon, Microsoft, Apple, and Alphabet forming this equally weighted MAMAA collection. They are the best of the best. These tech innovators have been doing it for quite some time and don't appear to be going anywhere.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Communication Services
		paragraph
			StaticText Top Holdings
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Alphabet Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GOOGL.png&w=96&q=75'
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +24.35%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 5
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading YC Public Companies
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText Like Double, all of these companies have been backed by
			link YCombinator, url='https://www.ycombinator.com/'
			StaticText . YC is the worlds most successful startup incubator started by Paul Graham, Jessica Livingston, Robert Morris and Trevor Blackwell in 2005.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Reddit Inc. - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_RDDT.png&w=96&q=75'
		image Dropbox Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DBX.png&w=96&q=75'
		image Amplitude Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMPL.png&w=96&q=75'
		image Maplebear Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CART.png&w=96&q=75'
		image Pagerduty Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PD.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +14.62%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 10
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $3,500
		paragraph
			StaticText VO
		heading USA Mid-Cap Companies
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText Targeting mid-sized U.S. companies, striking a balance between growth potential and stability. Investing in sectors like industrials, technology, consumer goods, and healthcare, it offers exposure to companies with established market positions and growth opportunities.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Industrials
		paragraph
			StaticText Top Holdings
		image Palantir Technologies Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PLTR.png&w=96&q=75'
		image Amphenol Corp. - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_APH.png&w=96&q=75'
		image Constellation Energy Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CEG.png&w=96&q=75'
		image Motorola Solutions Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSI.png&w=96&q=75'
		image Welltower Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WELL.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +10.47%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 310
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Sequoia Capital Investments
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			link Sequoia Capital, url='https://www.sequoiacap.com/'
			StaticText is considered by many to be the worlds best venture capital firm. This Strategy comprises of all the eligible stocks that they've invested in. We've equally weighted the strategy.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image HubSpot Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_HUBS.png&w=96&q=75'
		image Unity Software Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_U.png&w=96&q=75'
		image Reddit Inc. - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_RDDT.png&w=96&q=75'
		image Okta Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_OKTA.png&w=96&q=75'
		image Confluent Inc - Ordinary Shares Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CFLT.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +16.32%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 33
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading a16z Investments
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			link Andreessen Horowitz, url='https://a16z.com/'
			StaticText , known as a16z, is a venture capital firm started by Mark Andreessen and Ben Horowitz. It is the largest VC firm measure by assets under management with $42B as of late 2024.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Communication Services
		paragraph
			StaticText Top Holdings
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		image Okta Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_OKTA.png&w=96&q=75'
		image Lyft Inc - Ordinary Shares Cls A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_LYFT.png&w=96&q=75'
		image Pinterest Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PINS.png&w=96&q=75'
		image Maplebear Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CART.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +14.68%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 10
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading The Coward's Portfolio
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText William Bernstein created this portfolio and is the author of several books including
			link The Intelligent Asset Allocator, url='https://www.amazon.com/dp/0071362363'
			StaticText and
			link The Four Pillars of Investing, url='https://www.amazon.com/dp/0071747052/'
			StaticText . He introduced the Coward's Portfolio in 1996. The "coward" refers not to risk tolerance but to the strategy of hedging your bets and having slices of a number of asset classes.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard Short-Term Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total Stock Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Small Cap Value ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Value ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard FTSE Pacific ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +6.09%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.05
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 9
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Armstrong's "Ideal Index"
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText Frank Armstrong, author of
			link The Informed Investor, url='https://www.amazon.com/dp/0814472508/'
			StaticText , proposed this portfolio. Compared to other Boglehead portfolios, it contains a smaller allocation to bonds, and a much larger allocation to international stocks (in fact the equities, excluding REIT, are split 50/50 between domestic and international).
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard Total International Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Short-Term Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Value ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Small Cap Value ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Real Estate Index Fund ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +5.65%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.06
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 7
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading David Swensen's Lazy Portfolio
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText David Swensen is CIO of Yale University and author of
			link Unconventional Success, url='https://www.simonandschuster.com/books/Unconventional-Success/David-F-Swensen/9780743228381'
			StaticText . His lazy portfolio uses low-cost, tax-efficient total market funds, a healthy dose of real estate, and
			link inflation-protected securities (TIPS), url='https://www.bogleheads.org/wiki/Treasury_Inflation_Protected_Security'
			StaticText .
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard Total Stock Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image BlackRock Institutional Trust Company N.A. - iShares TIPS Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard FTSE Developed Markets ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Intermediate-Term Treasury ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Real Estate Index Fund ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +6.01%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.08
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 6
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Bill Schultheis's "Coffeehouse"
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText Bill Schultheis made this simple seven-fund portfolio popular in his book
			link The Coffeehouse Investor, url='https://www.amazon.com/dp/0976585707/'
			StaticText . He advocates 40% in a total market bond fund and 10% each in various stock funds. You can find more information at
			link The Coffeehouse Investor, url='https://coffeehouseinvestor.com/'
			StaticText .
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Small Cap ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Small Cap Value ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Real Estate Index Fund ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard S&P 500 ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +5.32%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.05
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 7
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Khosla Ventures
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			link Khosla Ventures, url='https://www.khoslaventures.com/'
			StaticText is an American venture capital firm founded by Vinod Khosla, focused on early-stage companies. Vinod co-founded Sun Microsystems.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image Okta Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_OKTA.png&w=96&q=75'
		image Oscar Health Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_OSCR.png&w=96&q=75'
		image Affirm Holdings Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AFRM.png&w=96&q=75'
		image QuantumScape Corp - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_QS.png&w=96&q=75'
		image Block Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_SQ.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +16.13%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 13
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $7,800
		paragraph
			StaticText VGT
		heading Information Technology Sector
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This strategy concentrates on the technology sector, including companies involved in software, hardware, IT services, and semiconductor industries. It captures the growth potential of tech companies driving innovation and digital transformation, appealing to investors seeking exposure to this dynamic sector.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Broadcom Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
		image Salesforce Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CRM.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +21.83%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 288
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $14,000
		paragraph
			StaticText VFH
		heading Financial Sector
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText Double's Financial Sector Strategy invests in financial sector companies, including banks, insurance companies, and financial services firms. Providing exposure to the financial industry's performance, it plays a crucial role in diversified portfolios.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image JPMorgan Chase & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JPM.png&w=96&q=75'
		image Berkshire Hathaway Inc. - Ordinary Shares - Class B logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BRK.B.png&w=96&q=75'
		image Mastercard Incorporated - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MA.png&w=96&q=75'
		image Visa Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_V.png&w=96&q=75'
		image Bank Of America Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BAC.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +12.17%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 371
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $9,300
		paragraph
			StaticText VCR
		heading Consumer Discretionary Sector
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This strategy focuses on consumer discretionary companies, including retail, automotive, leisure, and entertainment firms. Reflecting consumer spending trends and economic conditions, it's sensitive to changes in consumer sentiment and economic growth.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Consumer Discretionary
		paragraph
			StaticText Top Holdings
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		image Tesla Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TSLA.png&w=96&q=75'
		image Home Depot, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_HD.png&w=96&q=75'
		image McDonald`s Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MCD.png&w=96&q=75'
		image Booking Holdings Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BKNG.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +16.49%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 273
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Large Market Beaters
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText Beating the market. That's what so many money managers aim to do, but it's much easier said than done. Over the past year, this collection has achieved that goal. They are the winners, and it wasn't due to small numbers. They are both the largest companies in the stock market (>$200Bn Market Cap) and, at that size, the only companies to outperform SPYs long term average return by 2x (20%)
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		image Wells Fargo & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WFC.png&w=96&q=75'
		image T-Mobile US Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TMUS.png&w=96&q=75'
		image Salesforce Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CRM.png&w=96&q=75'
		image American Express Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AXP.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +29.05%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 25
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $15,000
		paragraph
			StaticText SPY
		heading US Top 500
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText The textbook passive investment vehicle is generally considered to comprise of 500 of the largest stocks traded within the US. Double's take on this exposes a client to the US stock market in a diversified way without any expense ratio.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +14.31%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 502
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,200
		heading Growth at a Fair Price
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText These stocks above $1B in Market Cap are modestly valued (PE below 15) but are in the top 20% of stocks for revenue growth over the past 5 years. We weight them by market cap.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Health Care
		paragraph
			StaticText Top Holdings
		image HubSpot Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_HUBS.png&w=96&q=75'
		image Lemonade Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_LMND.png&w=96&q=75'
		image Flutter Entertainment Plc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_FLUT.png&w=96&q=75'
		image Armada Hoffler Properties Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AHH.png&w=96&q=75'
		image First Citizens Bancshares, Inc (NC) - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_FCNCA.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +23.94%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 235
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		paragraph
			StaticText SMH
		heading Semiconductors Index
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This index tracks a market-cap-weighted index of 25 of the largest US-listed semiconductors companies.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Taiwan Semiconductor Manufacturing - ADR logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TSM.png&w=96&q=75'
		image Broadcom Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
		image ASML Holding NV - New York Shares logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ASML.png&w=96&q=75'
		image Advanced Micro Devices Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMD.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +29.73%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 25
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $2,200
		paragraph
			StaticText OEF
		heading US 100
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This strategy offers a convenient way to access the largest 100 large-cap stocks across various sectors within the U.S. market.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +16.36%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 101
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Founder Mode
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText Stocks only get included in this basket, if the companies founders are still actively involved in the company. We equally weight them. Paul Graham talks a bit about
			link Founder Mode, url='https://paulgraham.com/foundermode.html'
			StaticText in a recent 2024 essay.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image American Homes 4 Rent - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMH.png&w=96&q=75'
		image Skechers U S A, Inc. - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_SKX.png&w=96&q=75'
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		image Zillow Group Inc - Ordinary Shares - Class C logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_Z.png&w=96&q=75'
		image Procore Technologies Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PCOR.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +22.20%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 92
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading The Top 20% Club
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This group of select stocks has achieved top 20% ratings in 1 year Revenue Growth, Free Cash Flow Per Share and 5 Year Return on Invested Capital. This select group of stocks is equally weighted to prevent any mega caps from dominating this Strategy.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		image F&G Annuities & Life Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_FG.png&w=96&q=75'
		image Mesabi Trust logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSB.png&w=96&q=75'
		image Jackson Financial Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JXN.png&w=96&q=75'
		image Wingstop Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WING.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +31.81%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 22
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,400
		paragraph
			StaticText DYNF
		heading U.S. Equity Factor Rotation
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText Optimizes returns by rotating investments across five historically successful styles: quality, value, size, minimum volatility, and momentum. By shifting focus among these factors based on forward-looking insights, this index capitalizes on market opportunities and provides a diversified approach to enhancing returns. This strategy offers a flexible and adaptive way to navigate changing markets, combining multiple styles in a single portfolio to maximize returns while managing risk.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +15.98%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 82
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $2,200
		paragraph
			StaticText QQQ
		heading Tech 100
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This index is closely related to the Nasdaq-100 Index, comprising major tech and growth-oriented companies. It aims to capture the tech sector's long-term growth prospects through exposure to the innovative and leading tech companies listed on the Nasdaq exchange.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		image Broadcom Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +20.08%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 101
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Diverse Bond Portfolio
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText For investors seeking lower risk than equities and those nearing retirement, bonds offer a compelling investment option for the upcoming years. We've curated a diverse portfolio of six popular bond ETFs, carefully allocating 60% to short-term Treasuries, 30% to corporate bonds, 8% to floating-rate bonds, and 2% to long-term Treasuries.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Schwab Strategic Trust - Schwab Short-Term U.S. Treasury ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F91159910411997986.png&w=96&q=75'
		image BlackRock Institutional Trust Company N.A. - iShares Short Treasury Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
		image BlackRock Institutional Trust Company N.A. - iShares 0-5 Year High Yield Corporate Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
		image BlackRock Institutional Trust Company N.A. - iShares Broad USD High Yield Corporate Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
		image SPDR Series Trust - SPDR Bloomberg Investment Grade Floating Rate ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9115112100114451159711010011253484845101116102451161146.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +2.48%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.13
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 6
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Ray Dalio's All Weather
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText Ray Dalio is a legendary investor, and this Strategy is a simplified version of techniques he's used at his famous hedge fund Bridgewater Associates. It combines 5 asset classes using ETFs, with a 55% allocation to fixed income. It's appropriate for investors with a balance approach to risk and return. Learn more about it
			link here, url='https://www.lazyportfolioetf.com/allocation/ray-dalio-all-weather/'
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image BlackRock Institutional Trust Company N.A. - iShares 20+ Year Treasury Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total Stock Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image BlackRock Institutional Trust Company N.A. - iShares 3-7 Year Treasury Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
		image DB Commodity Services LLC - Invesco DB Commodity Index Tracking Fund logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105110118101115991116.png&w=96&q=75'
		image SPDR Gold Trust - SPDR Gold Shares ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9115112100114451159711010011253484845101116102451161146.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +3.29%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.19
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 5
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $5,500
		paragraph
			StaticText VUG
		heading Growth Stocks
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText Growth Stocks focuses on companies with strong growth prospects, often found in sectors driving innovation and technological advancement. This ETF invests in companies demonstrating robust revenue and earnings growth, including technology giants, healthcare innovators, and consumer discretionary leaders.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +18.30%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 181
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $6,600
		paragraph
			StaticText VTV
		heading Value Stocks
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This Strategy targets undervalued stocks in the U.S. market, emphasizing companies with solid fundamentals and potential for long-term growth. Emphasizing sectors such as healthcare, financials, industrials, and consumer goods, it seeks opportunities where market prices may not fully reflect underlying value metrics like earnings and book value.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image JPMorgan Chase & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JPM.png&w=96&q=75'
		image Berkshire Hathaway Inc. - Ordinary Shares - Class B logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BRK.B.png&w=96&q=75'
		image Broadcom Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
		image Exxon Mobil Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_XOM.png&w=96&q=75'
		image Unitedhealth Group Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_UNH.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +10.46%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 331
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Dividend Kings with Cash
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText These stocks have a strong dividend yield 5% yearly, and also are in the top 40% of all stocks with regards to cash on hand, meaning they have a strong balance sheet to finance those future dividend payments. We weight these stocks equally.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image Newell Brands Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NWL.png&w=96&q=75'
		image Whirlpool Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WHR.png&w=96&q=75'
		image MPLX LP - Unit logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MPLX.png&w=96&q=75'
		image Icahn Enterprises L P - Unit logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_IEP.png&w=96&q=75'
		image Two Harbors Investment Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TWO.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +5.72%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 71
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Growing Small Caps
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText These small cap companies ($250M to $2B) are growing Revenue and Earnings at a nice clip. Equally weighted.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image Consolidated Water Co. Ltd. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CWCO.png&w=96&q=75'
		image EyePoint Pharmaceuticals Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_EYPT.png&w=96&q=75'
		image Accolade Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ACCD.png&w=96&q=75'
		image Aurinia Pharmaceuticals Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AUPH.png&w=96&q=75'
		image Graham Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GHM.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +18.28%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 80
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,900
		heading Highly Efficient & Growing
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText These stocks are highly efficient, with a Return on Invested Capital > 20%, while also growing earnings > 20% over the last 3 years. We exclude any stock with market cap above $1T, and weight the rest by Market Cap.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Novo Nordisk - ADR logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVO.png&w=96&q=75'
		image ASML Holding NV - New York Shares logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ASML.png&w=96&q=75'
		image Booking Holdings Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BKNG.png&w=96&q=75'
		image Arista Networks Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ANET.png&w=96&q=75'
		image Regeneron Pharmaceuticals, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_REGN.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +19.43%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 71
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Equal MAMAA
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText First, it was FAANG, then names changed, and one got dropped; now, we have the familiar faces of Meta, Amazon, Microsoft, Apple, and Alphabet forming this equally weighted MAMAA collection. They are the best of the best. These tech innovators have been doing it for quite some time and don't appear to be going anywhere.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Communication Services
		paragraph
			StaticText Top Holdings
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Alphabet Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GOOGL.png&w=96&q=75'
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +24.35%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 5
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading YC Public Companies
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText Like Double, all of these companies have been backed by
			link YCombinator, url='https://www.ycombinator.com/'
			StaticText . YC is the worlds most successful startup incubator started by Paul Graham, Jessica Livingston, Robert Morris and Trevor Blackwell in 2005.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Reddit Inc. - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_RDDT.png&w=96&q=75'
		image Dropbox Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DBX.png&w=96&q=75'
		image Amplitude Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMPL.png&w=96&q=75'
		image Maplebear Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CART.png&w=96&q=75'
		image Pagerduty Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PD.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +14.62%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 10
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $3,500
		paragraph
			StaticText VO
		heading USA Mid-Cap Companies
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText Targeting mid-sized U.S. companies, striking a balance between growth potential and stability. Investing in sectors like industrials, technology, consumer goods, and healthcare, it offers exposure to companies with established market positions and growth opportunities.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Industrials
		paragraph
			StaticText Top Holdings
		image Palantir Technologies Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PLTR.png&w=96&q=75'
		image Amphenol Corp. - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_APH.png&w=96&q=75'
		image Constellation Energy Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CEG.png&w=96&q=75'
		image Motorola Solutions Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSI.png&w=96&q=75'
		image Welltower Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WELL.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +10.47%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 310
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Sequoia Capital Investments
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			link Sequoia Capital, url='https://www.sequoiacap.com/'
			StaticText is considered by many to be the worlds best venture capital firm. This Strategy comprises of all the eligible stocks that they've invested in. We've equally weighted the strategy.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image HubSpot Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_HUBS.png&w=96&q=75'
		image Unity Software Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_U.png&w=96&q=75'
		image Reddit Inc. - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_RDDT.png&w=96&q=75'
		image Okta Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_OKTA.png&w=96&q=75'
		image Confluent Inc - Ordinary Shares Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CFLT.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +16.32%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 33
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading a16z Investments
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			link Andreessen Horowitz, url='https://a16z.com/'
			StaticText , known as a16z, is a venture capital firm started by Mark Andreessen and Ben Horowitz. It is the largest VC firm measure by assets under management with $42B as of late 2024.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Communication Services
		paragraph
			StaticText Top Holdings
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		image Okta Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_OKTA.png&w=96&q=75'
		image Lyft Inc - Ordinary Shares Cls A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_LYFT.png&w=96&q=75'
		image Pinterest Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PINS.png&w=96&q=75'
		image Maplebear Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CART.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +14.68%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 10
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading The Coward's Portfolio
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText William Bernstein created this portfolio and is the author of several books including
			link The Intelligent Asset Allocator, url='https://www.amazon.com/dp/0071362363'
			StaticText and
			link The Four Pillars of Investing, url='https://www.amazon.com/dp/0071747052/'
			StaticText . He introduced the Coward's Portfolio in 1996. The "coward" refers not to risk tolerance but to the strategy of hedging your bets and having slices of a number of asset classes.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard Short-Term Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total Stock Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Small Cap Value ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Value ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard FTSE Pacific ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +6.09%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.05
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 9
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Armstrong's "Ideal Index"
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText Frank Armstrong, author of
			link The Informed Investor, url='https://www.amazon.com/dp/0814472508/'
			StaticText , proposed this portfolio. Compared to other Boglehead portfolios, it contains a smaller allocation to bonds, and a much larger allocation to international stocks (in fact the equities, excluding REIT, are split 50/50 between domestic and international).
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard Total International Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Short-Term Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Value ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Small Cap Value ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Real Estate Index Fund ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +5.65%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.06
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 7
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading David Swensen's Lazy Portfolio
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText David Swensen is CIO of Yale University and author of
			link Unconventional Success, url='https://www.simonandschuster.com/books/Unconventional-Success/David-F-Swensen/9780743228381'
			StaticText . His lazy portfolio uses low-cost, tax-efficient total market funds, a healthy dose of real estate, and
			link inflation-protected securities (TIPS), url='https://www.bogleheads.org/wiki/Treasury_Inflation_Protected_Security'
			StaticText .
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard Total Stock Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image BlackRock Institutional Trust Company N.A. - iShares TIPS Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard FTSE Developed Markets ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Intermediate-Term Treasury ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Real Estate Index Fund ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +6.01%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.08
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 6
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Bill Schultheis's "Coffeehouse"
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText Bill Schultheis made this simple seven-fund portfolio popular in his book
			link The Coffeehouse Investor, url='https://www.amazon.com/dp/0976585707/'
			StaticText . He advocates 40% in a total market bond fund and 10% each in various stock funds. You can find more information at
			link The Coffeehouse Investor, url='https://coffeehouseinvestor.com/'
			StaticText .
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Small Cap ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Small Cap Value ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Real Estate Index Fund ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard S&P 500 ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +5.32%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.05
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 7
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Khosla Ventures
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			link Khosla Ventures, url='https://www.khoslaventures.com/'
			StaticText is an American venture capital firm founded by Vinod Khosla, focused on early-stage companies. Vinod co-founded Sun Microsystems.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image Okta Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_OKTA.png&w=96&q=75'
		image Oscar Health Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_OSCR.png&w=96&q=75'
		image Affirm Holdings Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AFRM.png&w=96&q=75'
		image QuantumScape Corp - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_QS.png&w=96&q=75'
		image Block Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_SQ.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +16.13%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 13
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $7,800
		paragraph
			StaticText VGT
		heading Information Technology Sector
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This strategy concentrates on the technology sector, including companies involved in software, hardware, IT services, and semiconductor industries. It captures the growth potential of tech companies driving innovation and digital transformation, appealing to investors seeking exposure to this dynamic sector.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Broadcom Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
		image Salesforce Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CRM.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +21.83%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 288
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $14,000
		paragraph
			StaticText VFH
		heading Financial Sector
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText Double's Financial Sector Strategy invests in financial sector companies, including banks, insurance companies, and financial services firms. Providing exposure to the financial industry's performance, it plays a crucial role in diversified portfolios.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image JPMorgan Chase & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JPM.png&w=96&q=75'
		image Berkshire Hathaway Inc. - Ordinary Shares - Class B logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BRK.B.png&w=96&q=75'
		image Mastercard Incorporated - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MA.png&w=96&q=75'
		image Visa Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_V.png&w=96&q=75'
		image Bank Of America Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BAC.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +12.17%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 371
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $9,300
		paragraph
			StaticText VCR
		heading Consumer Discretionary Sector
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This strategy focuses on consumer discretionary companies, including retail, automotive, leisure, and entertainment firms. Reflecting consumer spending trends and economic conditions, it's sensitive to changes in consumer sentiment and economic growth.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Consumer Discretionary
		paragraph
			StaticText Top Holdings
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		image Tesla Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TSLA.png&w=96&q=75'
		image Home Depot, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_HD.png&w=96&q=75'
		image McDonald`s Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MCD.png&w=96&q=75'
		image Booking Holdings Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BKNG.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +16.49%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 273
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Large Market Beaters
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText Beating the market. That's what so many money managers aim to do, but it's much easier said than done. Over the past year, this collection has achieved that goal. They are the winners, and it wasn't due to small numbers. They are both the largest companies in the stock market (>$200Bn Market Cap) and, at that size, the only companies to outperform SPYs long term average return by 2x (20%)
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		image Wells Fargo & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WFC.png&w=96&q=75'
		image T-Mobile US Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TMUS.png&w=96&q=75'
		image Salesforce Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CRM.png&w=96&q=75'
		image American Express Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AXP.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +29.05%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 25
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $2,600
		paragraph
			StaticText VAW
		heading Materials Sector
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This Strategy invests in materials sector companies, including chemicals, construction materials, metals, and mining firms. Providing exposure to global infrastructure development and manufacturing activities, it's positioned to benefit from economic growth and industrial demand.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Materials
		paragraph
			StaticText Top Holdings
		image Linde Plc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_LIN.png&w=96&q=75'
		image Sherwin-Williams Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_SHW.png&w=96&q=75'
		image Air Products & Chemicals Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_APD.png&w=96&q=75'
		image CRH Plc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CRH.png&w=96&q=75'
		image Ecolab, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ECL.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +9.67%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 110
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $3,400
		paragraph
			StaticText VOX
		heading Communication Services
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This strategy tracks the communication services sector, including companies involved in telecommunications, media, and internet services. Capturing trends in digital communication, entertainment, and connectivity, it reflects the evolving landscape of communication technologies.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Communication Services
		paragraph
			StaticText Top Holdings
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		image Alphabet Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GOOGL.png&w=96&q=75'
		image Alphabet Inc - Ordinary Shares - Class C logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GOOG.png&w=96&q=75'
		image Netflix Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NFLX.png&w=96&q=75'
		image Walt Disney Co (The) logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DIS.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +11.38%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 108
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $3,300
		paragraph
			StaticText VDC
		heading Consumer Staples Sector
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText This strategy focuses on consumer staples companies, including food, beverage, household products, and retail firms. Offering stability and defensive characteristics, it's often less sensitive to economic cycles.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Consumer Staples
		paragraph
			StaticText Top Holdings
		image Costco Wholesale Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_COST.png&w=96&q=75'
		image Walmart Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WMT.png&w=96&q=75'
		image Procter & Gamble Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PG.png&w=96&q=75'
		image Coca-Cola Co logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_KO.png&w=96&q=75'
		image Philip Morris International Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PM.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +8.56%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 100
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $14,000
		paragraph
			StaticText VHT
		heading Health Care Sector
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This Strategy focuses on healthcare companies, including pharmaceuticals, biotechnology, healthcare providers, and medical equipment firms. Offering exposure to a sector driven by demographic trends and ongoing medical advancements, it's a strategic choice for investors considering healthcare's long-term growth potential.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Health Care
		paragraph
			StaticText Top Holdings
		image Lilly(Eli) & Co logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_LLY.png&w=96&q=75'
		image Unitedhealth Group Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_UNH.png&w=96&q=75'
		image Abbvie Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ABBV.png&w=96&q=75'
		image Johnson & Johnson logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JNJ.png&w=96&q=75'
		image Merck & Co Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MRK.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +7.67%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 335
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $3,300
		paragraph
			StaticText VDE
		heading Energy Sector
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This Strategy concentrate on the energy sector, including oil, gas, and renewable energy firms. Offering exposure to the global energy market, it can be influenced by factors such as oil prices, geopolitical events, and environmental policies.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Energy
		paragraph
			StaticText Top Holdings
		image Exxon Mobil Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_XOM.png&w=96&q=75'
		image Chevron Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CVX.png&w=96&q=75'
		image Conoco Phillips logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_COP.png&w=96&q=75'
		image EOG Resources, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_EOG.png&w=96&q=75'
		image Williams Cos Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WMB.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +13.67%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 104
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $2,700
		paragraph
			StaticText MTUM
		heading U.S. Momentum Factor
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText Tracks an index of large- and mid-cap US equities, selected and weighted based on historical price appreciation and low volatility. Focus is on stocks with strong 6- and 12-month price performance, while also considering volatility over the past 3 years. This approach aims to capture momentum while managing risk, providing a unique investment strategy for those seeking growth potential.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Broadcom Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
		image JPMorgan Chase & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JPM.png&w=96&q=75'
		image Walmart Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WMT.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Costco Wholesale Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_COST.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +13.42%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 123
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Contrarian Picks
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText You better have a strong stomach if this portfolio interests you; it certainly isn't for the faint of heart. These are smaller companies that aren't being traded very heavily and while they may be cheap (PE <15), they have a lackluster TTM performance to show for it (<0%). Are they stocks to avoid or a list of potential hidden gems?
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Consumer Discretionary
		paragraph
			StaticText Top Holdings
		image Rocky Brands, Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_RCKY.png&w=96&q=75'
		image Smart Powerr Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CREG.png&w=96&q=75'
		image SoundThinking Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_SSTI.png&w=96&q=75'
		image Urban One Inc - Ordinary Shares - Class D logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_UONEK.png&w=96&q=75'
		image CPS Technologies Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CPSH.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText -3.81%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 53
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Mid & Large Cap Dividend Yield
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText These mid and large cap companies all have above a 3% dividend yield and are equally weighted.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Utilities
		paragraph
			StaticText Top Holdings
		image PNC Financial Services Group Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PNC.png&w=96&q=75'
		image Chevron Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CVX.png&w=96&q=75'
		image PPL Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PPL.png&w=96&q=75'
		image Prudential Financial Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PRU.png&w=96&q=75'
		image Target Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TGT.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +10.51%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 95
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $2,800
		paragraph
			StaticText RSP
		heading Equal Weighted US Top 500
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This index provides equal-weight exposure to the top 500 companies in the US, offering a unique approach compared to traditional market-cap weighted indexes. With an aim to reduce concentration risk by allocating equal amounts to each constituent, it potentially benefits from smaller companies' outperformance.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Industrials
		paragraph
			StaticText Top Holdings
		image Broadcom Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
		image Darden Restaurants, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DRI.png&w=96&q=75'
		image Jabil Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JBL.png&w=96&q=75'
		image Palantir Technologies Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PLTR.png&w=96&q=75'
		image Vistra Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_VST.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +10.67%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 502
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading The Permanent Portfolio
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText Free-market investment analyst Harry Browne devised the Permanent Portfolio in the 1980s, as a buy-and-hold portfolio that contains a healthy allocation to gold. The portfolio holds equal allocations of domestic stocks, gold, short-term treasury bonds, and long term treasury bonds. Boglehead members Craig Rowland and J. M. Lawson have written a book,
			link The Permanent Portfolio: Harry Browne's Long-Term Investment Strategy, url='https://www.amazon.com/Permanent-Portfolio-Long-Term-Investment-Strategy/dp/1118288254'
			StaticText , detailing every aspect of the Permanent Portfolio.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image BlackRock Institutional Trust Company N.A. - iShares Gold Trust logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Long-Term Treasury ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Short-Term Treasury ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total Stock Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +5.32%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.09
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 4
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading High Performance Small Cap
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText Who doesn't love an underdog story? These may be small-cap stocks (<$1B in Market Cap), but they have packed in a mighty performance in the past year (>90% return). Another benefit of their small size is that there should still be plenty of room for them to continue growing.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Health Care
		paragraph
			StaticText Top Holdings
		image Allot Ltd logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ALLT.png&w=96&q=75'
		image Dynagas LNG Partners LP - Unit logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DLNG.png&w=96&q=75'
		image Oxbridge Re Holdings Ltd logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_OXBR.png&w=96&q=75'
		image ClearPoint Neuro Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CLPT.png&w=96&q=75'
		image Graham Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GHM.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +33.93%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 52
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Two Fund Portfolio
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText You can invest in broad US and International markets, as well as bonds, using only two funds.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard Total World Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +5.90%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.05
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 2
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Core 4 Portfolio
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText By including some direct exposure to the US Real Estate market directly through VNQ, this fund adds a bit more diversity compared to the Majesty of Simplicity.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total Stock Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total International Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Real Estate Index Fund ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +5.35%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.05
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 4
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Majesty of Simplicity - Mod
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText John Bogle started Vanguard and revolutionized the investment world, and this three fund portfolio was called name "The Majesty of Simplicity" by Bogle himself. It uses three ETFs - a Bond ETF a US Domestic Stock ETF and a Foreign Stock ETF - to construct a well diversified portfolio in a dead simple manner.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard S&P 500 ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total International Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +7.11%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.04
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 3
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Majesty of Simplicity - Agg
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText John Bogle started Vanguard and revolutionized the investment world, and this three fund portfolio was called name "The Majesty of Simplicity" by Bogle himself. It uses three ETFs - a Bond ETF a US Domestic Stock ETF and a Foreign Stock ETF - to construct a well diversified portfolio in a dead simple manner.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard S&P 500 ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total International Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +10.82%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.04
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 3
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Majesty of Simplicity - Con
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText John Bogle started Vanguard and revolutionized the investment world, and this three fund portfolio was called name "The Majesty of Simplicity" by Bogle himself. It uses three ETFs - a Bond ETF a US Domestic Stock ETF and a Foreign Stock ETF - to construct a well diversified portfolio in a dead simple manner.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard S&P 500 ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total International Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +3.16%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.04
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 3
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		paragraph
			StaticText ARKK
		heading Innovation Fund
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This strategy follows the ARKK fund (ticker ARKK) which was designed to seek long term capital from companies globally involved with, or that benefit from, disruptive innovation.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Health Care
		paragraph
			StaticText Top Holdings
		image Tesla Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TSLA.png&w=96&q=75'
		image Roku Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ROKU.png&w=96&q=75'
		image Coinbase Global Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_COIN.png&w=96&q=75'
		image Roblox Corporation - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_RBLX.png&w=96&q=75'
		image Palantir Technologies Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PLTR.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +3.78%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 31
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $3,700
		paragraph
			StaticText VNQ
		heading Real Estate Sector
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This ETF follower concentrates primarily on real estate equity and is market-cap weighted for companies involved in the ownership and operation of real estate in the United States.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Real Estate
		paragraph
			StaticText Top Holdings
		image Prologis Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PLD.png&w=96&q=75'
		image Equinix Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_EQIX.png&w=96&q=75'
		image American Tower Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMT.png&w=96&q=75'
		image Welltower Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WELL.png&w=96&q=75'
		image Digital Realty Trust Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DLR.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +3.15%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 153
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		paragraph
			StaticText WCLD
		heading Cloud Computing
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This strategy tracks US companies primarily focused on cloud software and services. Stocks are equal weighted in the index.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Twilio Inc - Ordinary Shares Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TWLO.png&w=96&q=75'
		image BILL Holdings Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BILL.png&w=96&q=75'
		image DocuSign Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DOCU.png&w=96&q=75'
		image Atlassian Corporation - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TEAM.png&w=96&q=75'
		image AvePoint Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVPT.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +9.90%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 63
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $3,000
		paragraph
			StaticText KRUZ
		heading Republican Trading
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText This strategy seeks to broadly invest in stocks purchased or sold by Republican members of the US Congress and their families.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image JPMorgan Chase & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JPM.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Comfort Systems USA, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_FIX.png&w=96&q=75'
		image Simon Property Group, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_SPG.png&w=96&q=75'
		image AT&T, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_T.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +5.11%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 157
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $5,000
		paragraph
			StaticText NANC
		heading Democratic Trading
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText This strategy seeks to broadly invest in stocks purchased or sold by Democratic members of the US Congress and their families.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		image Salesforce Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CRM.png&w=96&q=75'
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +9.98%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 166
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading HedgeFundie's Excellent Adventure
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText Famously posted on the
			link Bogleheads forum in 2019, url='https://www.bogleheads.org/forum/viewtopic.php?t=272007'
			StaticText , this risky strategy combining 3x leveraged etfs exposed to SPY and 20 year treasuries. It's only appropriate for users with very high risk tolerances and incurs relatively high ETF expense ratios
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image ProShares Trust - ProShares UltraPro S&P 500 ETF 3x Shares logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9112114111115104971141011156.png&w=96&q=75'
		image Direxion Shares ETF Trust - Direxion Daily 20+ Year Treasury Bull 3X Shares logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F91001051141011201051111106.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText -1.16%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.97
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 2
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Leveraged Tech
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This strategy allocates 70% to ProShares Ultra QQQ (QLD) for its 2x leveraged exposure to the Nasdaq-100. The additional leverage is a super-bullish bet on continued tech sector growth and innovation. The 30% Invesco QQQ (QQQ) provides core exposure to the tech sector while mitigating some of the risks associated with leveraged instruments.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image ProShares Trust - ProShares Ultra QQQ 2x Shares logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9112114111115104971141011156.png&w=96&q=75'
		image Invesco Capital Management LLC - Invesco QQQ Trust Series 1 logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105110118101115991116.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +25.77%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.72
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 2
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $33,000
		paragraph
			StaticText IWB
		heading US 1000
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This strategy tracks a market-cap-weighted index of the 1000-largest US companies. It offers broad exposure to the US equity market, encompassing a diverse range of sectors and industries. By investing in this fund, you gain access to the performance of large and well-established companies within the US economy.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +14.11%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 992
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $5,100
		paragraph
			StaticText IJH
		heading US Mid Cap
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This strategy tracks a market-cap-weighted index of mid-cap US companies. This strategy offers targeted exposure to the growth potential of mid-sized businesses within the US market. With a diversified portfolio of holdings, it provides investors with a comprehensive approach to capturing the mid-cap segment's performance.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Industrials
		paragraph
			StaticText Top Holdings
		image Williams-Sonoma, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WSM.png&w=96&q=75'
		image Emcor Group, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_EME.png&w=96&q=75'
		image Expand Energy Corp. - Ordinary Shares - New logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CHK.png&w=96&q=75'
		image Illumina Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ILMN.png&w=96&q=75'
		image Interactive Brokers Group Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_IBKR.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +10.42%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 399
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $8,600
		paragraph
			StaticText IJR
		heading US Small Cap
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This strategy tracks a market-cap-weighted index of primarily small-cap US stocks, representing a small portion of the total market. This strategy focuses on the growth potential of smaller companies, offering investors targeted exposure to this dynamic segment of the US equity market. With a diversified portfolio of holdings it provides a broad approach to small-cap investing.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image Glaukos Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GKOS.png&w=96&q=75'
		image Bath & Body Works Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BBWI.png&w=96&q=75'
		image Alaska Air Group Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ALK.png&w=96&q=75'
		image ATI Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ATI.png&w=96&q=75'
		image VF Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_VFC.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +8.94%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 589
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $3,100
		paragraph
			StaticText QUAL
		heading USA Quality Factor
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This strategy invests in US large- and mid-cap stocks with a focus on financial quality. Companies are selected and weighted based on their return on equity, earnings growth stability, and financial leverage, emphasizing strong fundamentals. This approach offers investors exposure to companies with proven profitability and sound financial health.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Visa Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_V.png&w=96&q=75'
		image Mastercard Incorporated - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MA.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +13.82%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 124
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,700
		paragraph
			StaticText XLF
		heading Select US Financial Sector
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText Tracking select top holdings in US financial sector focusing on the top performers.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image Berkshire Hathaway Inc. - Ordinary Shares - Class B logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BRK.B.png&w=96&q=75'
		image JPMorgan Chase & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JPM.png&w=96&q=75'
		image Visa Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_V.png&w=96&q=75'
		image Mastercard Incorporated - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MA.png&w=96&q=75'
		image Bank Of America Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BAC.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +11.81%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 73
		paragraph
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,700
		paragraph
			StaticText MGK
		heading Mega Cap Growth Stocks
		paragraph
			StaticText Mega Cap Growth Stocks focuses on companies with strong growth prospects, often found in sectors driving innovation and technological advancement. This ETF following strategy invests in mega cap companies demonstrating robust revenue and earnings growth, including technology giants, healthcare innovators, and consumer discretionary leaders.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 71
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $2,600
		paragraph
			StaticText VAW
		heading Materials Sector
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This Strategy invests in materials sector companies, including chemicals, construction materials, metals, and mining firms. Providing exposure to global infrastructure development and manufacturing activities, it's positioned to benefit from economic growth and industrial demand.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Materials
		paragraph
			StaticText Top Holdings
		image Linde Plc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_LIN.png&w=96&q=75'
		image Sherwin-Williams Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_SHW.png&w=96&q=75'
		image Air Products & Chemicals Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_APD.png&w=96&q=75'
		image CRH Plc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CRH.png&w=96&q=75'
		image Ecolab, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ECL.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +9.67%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 110
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $3,400
		paragraph
			StaticText VOX
		heading Communication Services
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This strategy tracks the communication services sector, including companies involved in telecommunications, media, and internet services. Capturing trends in digital communication, entertainment, and connectivity, it reflects the evolving landscape of communication technologies.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Communication Services
		paragraph
			StaticText Top Holdings
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		image Alphabet Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GOOGL.png&w=96&q=75'
		image Alphabet Inc - Ordinary Shares - Class C logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GOOG.png&w=96&q=75'
		image Netflix Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NFLX.png&w=96&q=75'
		image Walt Disney Co (The) logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DIS.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +11.38%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 108
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $3,300
		paragraph
			StaticText VDC
		heading Consumer Staples Sector
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText This strategy focuses on consumer staples companies, including food, beverage, household products, and retail firms. Offering stability and defensive characteristics, it's often less sensitive to economic cycles.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Consumer Staples
		paragraph
			StaticText Top Holdings
		image Costco Wholesale Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_COST.png&w=96&q=75'
		image Walmart Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WMT.png&w=96&q=75'
		image Procter & Gamble Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PG.png&w=96&q=75'
		image Coca-Cola Co logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_KO.png&w=96&q=75'
		image Philip Morris International Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PM.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +8.56%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 100
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $14,000
		paragraph
			StaticText VHT
		heading Health Care Sector
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This Strategy focuses on healthcare companies, including pharmaceuticals, biotechnology, healthcare providers, and medical equipment firms. Offering exposure to a sector driven by demographic trends and ongoing medical advancements, it's a strategic choice for investors considering healthcare's long-term growth potential.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Health Care
		paragraph
			StaticText Top Holdings
		image Lilly(Eli) & Co logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_LLY.png&w=96&q=75'
		image Unitedhealth Group Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_UNH.png&w=96&q=75'
		image Abbvie Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ABBV.png&w=96&q=75'
		image Johnson & Johnson logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JNJ.png&w=96&q=75'
		image Merck & Co Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MRK.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +7.67%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 335
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $3,300
		paragraph
			StaticText VDE
		heading Energy Sector
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This Strategy concentrate on the energy sector, including oil, gas, and renewable energy firms. Offering exposure to the global energy market, it can be influenced by factors such as oil prices, geopolitical events, and environmental policies.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Energy
		paragraph
			StaticText Top Holdings
		image Exxon Mobil Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_XOM.png&w=96&q=75'
		image Chevron Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CVX.png&w=96&q=75'
		image Conoco Phillips logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_COP.png&w=96&q=75'
		image EOG Resources, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_EOG.png&w=96&q=75'
		image Williams Cos Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WMB.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +13.67%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 104
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $2,700
		paragraph
			StaticText MTUM
		heading U.S. Momentum Factor
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText Tracks an index of large- and mid-cap US equities, selected and weighted based on historical price appreciation and low volatility. Focus is on stocks with strong 6- and 12-month price performance, while also considering volatility over the past 3 years. This approach aims to capture momentum while managing risk, providing a unique investment strategy for those seeking growth potential.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Broadcom Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
		image JPMorgan Chase & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JPM.png&w=96&q=75'
		image Walmart Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WMT.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Costco Wholesale Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_COST.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +13.42%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 123
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Contrarian Picks
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText You better have a strong stomach if this portfolio interests you; it certainly isn't for the faint of heart. These are smaller companies that aren't being traded very heavily and while they may be cheap (PE <15), they have a lackluster TTM performance to show for it (<0%). Are they stocks to avoid or a list of potential hidden gems?
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Consumer Discretionary
		paragraph
			StaticText Top Holdings
		image Rocky Brands, Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_RCKY.png&w=96&q=75'
		image Smart Powerr Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CREG.png&w=96&q=75'
		image SoundThinking Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_SSTI.png&w=96&q=75'
		image Urban One Inc - Ordinary Shares - Class D logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_UONEK.png&w=96&q=75'
		image CPS Technologies Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CPSH.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText -3.81%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 53
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Mid & Large Cap Dividend Yield
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText These mid and large cap companies all have above a 3% dividend yield and are equally weighted.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Utilities
		paragraph
			StaticText Top Holdings
		image PNC Financial Services Group Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PNC.png&w=96&q=75'
		image Chevron Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CVX.png&w=96&q=75'
		image PPL Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PPL.png&w=96&q=75'
		image Prudential Financial Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PRU.png&w=96&q=75'
		image Target Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TGT.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +10.51%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 95
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $2,800
		paragraph
			StaticText RSP
		heading Equal Weighted US Top 500
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This index provides equal-weight exposure to the top 500 companies in the US, offering a unique approach compared to traditional market-cap weighted indexes. With an aim to reduce concentration risk by allocating equal amounts to each constituent, it potentially benefits from smaller companies' outperformance.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Industrials
		paragraph
			StaticText Top Holdings
		image Broadcom Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
		image Darden Restaurants, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DRI.png&w=96&q=75'
		image Jabil Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JBL.png&w=96&q=75'
		image Palantir Technologies Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PLTR.png&w=96&q=75'
		image Vistra Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_VST.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +10.67%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 502
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading The Permanent Portfolio
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText Free-market investment analyst Harry Browne devised the Permanent Portfolio in the 1980s, as a buy-and-hold portfolio that contains a healthy allocation to gold. The portfolio holds equal allocations of domestic stocks, gold, short-term treasury bonds, and long term treasury bonds. Boglehead members Craig Rowland and J. M. Lawson have written a book,
			link The Permanent Portfolio: Harry Browne's Long-Term Investment Strategy, url='https://www.amazon.com/Permanent-Portfolio-Long-Term-Investment-Strategy/dp/1118288254'
			StaticText , detailing every aspect of the Permanent Portfolio.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image BlackRock Institutional Trust Company N.A. - iShares Gold Trust logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Long-Term Treasury ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Short-Term Treasury ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total Stock Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +5.32%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.09
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 4
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading High Performance Small Cap
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText Who doesn't love an underdog story? These may be small-cap stocks (<$1B in Market Cap), but they have packed in a mighty performance in the past year (>90% return). Another benefit of their small size is that there should still be plenty of room for them to continue growing.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Health Care
		paragraph
			StaticText Top Holdings
		image Allot Ltd logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ALLT.png&w=96&q=75'
		image Dynagas LNG Partners LP - Unit logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DLNG.png&w=96&q=75'
		image Oxbridge Re Holdings Ltd logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_OXBR.png&w=96&q=75'
		image ClearPoint Neuro Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CLPT.png&w=96&q=75'
		image Graham Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GHM.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +33.93%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 52
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Two Fund Portfolio
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText You can invest in broad US and International markets, as well as bonds, using only two funds.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard Total World Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +5.90%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.05
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 2
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Core 4 Portfolio
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText By including some direct exposure to the US Real Estate market directly through VNQ, this fund adds a bit more diversity compared to the Majesty of Simplicity.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total Stock Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total International Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Real Estate Index Fund ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +5.35%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.05
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 4
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Majesty of Simplicity - Mod
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText John Bogle started Vanguard and revolutionized the investment world, and this three fund portfolio was called name "The Majesty of Simplicity" by Bogle himself. It uses three ETFs - a Bond ETF a US Domestic Stock ETF and a Foreign Stock ETF - to construct a well diversified portfolio in a dead simple manner.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard S&P 500 ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total International Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +7.11%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.04
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 3
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Majesty of Simplicity - Agg
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText John Bogle started Vanguard and revolutionized the investment world, and this three fund portfolio was called name "The Majesty of Simplicity" by Bogle himself. It uses three ETFs - a Bond ETF a US Domestic Stock ETF and a Foreign Stock ETF - to construct a well diversified portfolio in a dead simple manner.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard S&P 500 ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total International Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +10.82%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.04
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 3
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Majesty of Simplicity - Con
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText John Bogle started Vanguard and revolutionized the investment world, and this three fund portfolio was called name "The Majesty of Simplicity" by Bogle himself. It uses three ETFs - a Bond ETF a US Domestic Stock ETF and a Foreign Stock ETF - to construct a well diversified portfolio in a dead simple manner.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard S&P 500 ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		image Vanguard Group, Inc. - Vanguard Total International Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +3.16%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.04
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 3
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		paragraph
			StaticText ARKK
		heading Innovation Fund
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This strategy follows the ARKK fund (ticker ARKK) which was designed to seek long term capital from companies globally involved with, or that benefit from, disruptive innovation.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Health Care
		paragraph
			StaticText Top Holdings
		image Tesla Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TSLA.png&w=96&q=75'
		image Roku Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ROKU.png&w=96&q=75'
		image Coinbase Global Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_COIN.png&w=96&q=75'
		image Roblox Corporation - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_RBLX.png&w=96&q=75'
		image Palantir Technologies Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PLTR.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +3.78%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 31
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $3,700
		paragraph
			StaticText VNQ
		heading Real Estate Sector
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This ETF follower concentrates primarily on real estate equity and is market-cap weighted for companies involved in the ownership and operation of real estate in the United States.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Real Estate
		paragraph
			StaticText Top Holdings
		image Prologis Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PLD.png&w=96&q=75'
		image Equinix Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_EQIX.png&w=96&q=75'
		image American Tower Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMT.png&w=96&q=75'
		image Welltower Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WELL.png&w=96&q=75'
		image Digital Realty Trust Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DLR.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +3.15%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 153
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		paragraph
			StaticText WCLD
		heading Cloud Computing
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This strategy tracks US companies primarily focused on cloud software and services. Stocks are equal weighted in the index.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Twilio Inc - Ordinary Shares Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TWLO.png&w=96&q=75'
		image BILL Holdings Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BILL.png&w=96&q=75'
		image DocuSign Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DOCU.png&w=96&q=75'
		image Atlassian Corporation - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TEAM.png&w=96&q=75'
		image AvePoint Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVPT.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +9.90%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 63
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $3,000
		paragraph
			StaticText KRUZ
		heading Republican Trading
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText This strategy seeks to broadly invest in stocks purchased or sold by Republican members of the US Congress and their families.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image JPMorgan Chase & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JPM.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Comfort Systems USA, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_FIX.png&w=96&q=75'
		image Simon Property Group, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_SPG.png&w=96&q=75'
		image AT&T, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_T.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +5.11%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 157
		paragraph
			StaticText Low
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $5,000
		paragraph
			StaticText NANC
		heading Democratic Trading
		StaticText Capital Preservation
		StaticText Balanced
		StaticText Income
		paragraph
			StaticText This strategy seeks to broadly invest in stocks purchased or sold by Democratic members of the US Congress and their families.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		image Salesforce Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CRM.png&w=96&q=75'
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +9.98%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 166
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading HedgeFundie's Excellent Adventure
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText Famously posted on the
			link Bogleheads forum in 2019, url='https://www.bogleheads.org/forum/viewtopic.php?t=272007'
			StaticText , this risky strategy combining 3x leveraged etfs exposed to SPY and 20 year treasuries. It's only appropriate for users with very high risk tolerances and incurs relatively high ETF expense ratios
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image ProShares Trust - ProShares UltraPro S&P 500 ETF 3x Shares logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9112114111115104971141011156.png&w=96&q=75'
		image Direxion Shares ETF Trust - Direxion Daily 20+ Year Treasury Bull 3X Shares logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F91001051141011201051111106.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText -1.16%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.97
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 2
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,000
		heading Leveraged Tech
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This strategy allocates 70% to ProShares Ultra QQQ (QLD) for its 2x leveraged exposure to the Nasdaq-100. The additional leverage is a super-bullish bet on continued tech sector growth and innovation. The 30% Invesco QQQ (QQQ) provides core exposure to the tech sector while mitigating some of the risks associated with leveraged instruments.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Top Holdings
		image ProShares Trust - ProShares Ultra QQQ 2x Shares logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9112114111115104971141011156.png&w=96&q=75'
		image Invesco Capital Management LLC - Invesco QQQ Trust Series 1 logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105110118101115991116.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +25.77%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.72
			StaticText %
		paragraph
			StaticText Holdings
		paragraph
			StaticText 2
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $33,000
		paragraph
			StaticText IWB
		heading US 1000
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This strategy tracks a market-cap-weighted index of the 1000-largest US companies. It offers broad exposure to the US equity market, encompassing a diverse range of sectors and industries. By investing in this fund, you gain access to the performance of large and well-established companies within the US economy.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
		image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +14.11%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 992
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $5,100
		paragraph
			StaticText IJH
		heading US Mid Cap
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This strategy tracks a market-cap-weighted index of mid-cap US companies. This strategy offers targeted exposure to the growth potential of mid-sized businesses within the US market. With a diversified portfolio of holdings, it provides investors with a comprehensive approach to capturing the mid-cap segment's performance.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Industrials
		paragraph
			StaticText Top Holdings
		image Williams-Sonoma, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WSM.png&w=96&q=75'
		image Emcor Group, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_EME.png&w=96&q=75'
		image Expand Energy Corp. - Ordinary Shares - New logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CHK.png&w=96&q=75'
		image Illumina Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ILMN.png&w=96&q=75'
		image Interactive Brokers Group Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_IBKR.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +10.42%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 399
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $8,600
		paragraph
			StaticText IJR
		heading US Small Cap
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText This strategy tracks a market-cap-weighted index of primarily small-cap US stocks, representing a small portion of the total market. This strategy focuses on the growth potential of smaller companies, offering investors targeted exposure to this dynamic segment of the US equity market. With a diversified portfolio of holdings it provides a broad approach to small-cap investing.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image Glaukos Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GKOS.png&w=96&q=75'
		image Bath & Body Works Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BBWI.png&w=96&q=75'
		image Alaska Air Group Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ALK.png&w=96&q=75'
		image ATI Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ATI.png&w=96&q=75'
		image VF Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_VFC.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +8.94%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 589
		paragraph
			StaticText Medium
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $3,100
		paragraph
			StaticText QUAL
		heading USA Quality Factor
		StaticText Growth
		StaticText Balanced
		StaticText Growth Income
		paragraph
			StaticText This strategy invests in US large- and mid-cap stocks with a focus on financial quality. Companies are selected and weighted based on their return on equity, earnings growth stability, and financial leverage, emphasizing strong fundamentals. This approach offers investors exposure to companies with proven profitability and sound financial health.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Information Technology
		paragraph
			StaticText Top Holdings
		image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
		image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
		image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
		image Visa Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_V.png&w=96&q=75'
		image Mastercard Incorporated - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MA.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +13.82%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 124
		paragraph
			StaticText High
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,700
		paragraph
			StaticText XLF
		heading Select US Financial Sector
		StaticText Speculation
		StaticText Maximum Growth
		paragraph
			StaticText Tracking select top holdings in US financial sector focusing on the top performers.
		paragraph
			StaticText Top Sector
		paragraph
			StaticText Financials
		paragraph
			StaticText Top Holdings
		image Berkshire Hathaway Inc. - Ordinary Shares - Class B logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BRK.B.png&w=96&q=75'
		image JPMorgan Chase & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JPM.png&w=96&q=75'
		image Visa Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_V.png&w=96&q=75'
		image Mastercard Incorporated - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MA.png&w=96&q=75'
		image Bank Of America Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BAC.png&w=96&q=75'
		paragraph
			StaticText Return
		image
		image
		StaticText +11.81%
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 73
		paragraph
			StaticText risk
			StaticText strategy
		paragraph
			image
			StaticText $1,700
		paragraph
			StaticText MGK
		heading Mega Cap Growth Stocks
		paragraph
			StaticText Mega Cap Growth Stocks focuses on companies with strong growth prospects, often found in sectors driving innovation and technological advancement. This ETF following strategy invests in mega cap companies demonstrating robust revenue and earnings growth, including technology giants, healthcare innovators, and consumer discretionary leaders.
		paragraph
			StaticText ETF Based
			StaticText Strategy
		paragraph
			StaticText Expense Ratio
		image
		paragraph
			StaticText 0.00
			StaticText %
		paragraph
			StaticText Holdings
		image
		paragraph
			StaticText 71
		button Explore Indexes
			link Explore Indexes, url='https://double.finance/p/explore'
		heading “What people have to say...
		image Nicholas T.'s quote, url='https://double.finance/_next/image?url=%2Fpersons%2FNick-T-2.jpg&w=48&q=75'
		paragraph
			StaticText Nicholas T.
		paragraph
			StaticText CEO
		paragraph
			StaticText “I love the diversity of strategies I can invest in... And it made no sense for me to pay fees to an ETF when a robot can easily do it.”
		image Matt C.'s quote, url='https://double.finance/_next/image?url=%2Fpersons%2FMatt-C-2.jpeg&w=48&q=75'
		paragraph
			StaticText Matt C.
		paragraph
			StaticText Founder
		paragraph
			StaticText “With automated features like rebalancing and tax loss harvesting, I don't have to worry about optimizing my portfolio manually.”
		image Patrick L.'s quote, url='https://double.finance/_next/image?url=%2Fpersons%2FPatrick-L-2.jpeg&w=48&q=75'
		paragraph
			StaticText Patrick L.
		paragraph
			StaticText Sr. Director Product Management
		paragraph
			StaticText “I really like direct indexing with Double. It's simple to understand and provides me with something that I really can't get anywhere else.”
		image Arden A.'s quote, url='https://double.finance/_next/image?url=%2Fpersons%2FArden-A-2.jpeg&w=48&q=75'
		paragraph
			StaticText Arden A.
		paragraph
			StaticText Enterprise Sales Leader
		paragraph
			StaticText “Double has been very easy to use and I like the ability to direct index into both passive and more active strategies in one account.”
		heading Your money is secure
		StaticText Safety & Privacy are at the core of what we do.
		image You always own your assets, url='https://double.finance/banknotes.svg'
		heading You always own your assets
		paragraph
			StaticText Your funds are held in your name at
			StaticText Apex Clearing
			StaticText ,
			StaticText one of the largest US Custodians holding over $114B in funds.
			StaticText In the unlikely event that something happens to Double, your assets will be fully accessible.
		image We are an SEC Registered Fiduciary, url='https://double.finance/building-library.svg'
		heading We are an SEC Registered Fiduciary
		paragraph
			StaticText Double is a
			StaticText Registered Investment Advisor
			StaticText , meaning we are legally bound to do what is in your best interest.
		image Built with security in mind, url='https://double.finance/finger-print.svg'
		heading Built with security in mind
		paragraph
			StaticText We have strict measures in place to keep your data protected.
			StaticText Sensitive information is encrypted and
			StaticText we offer 2-factor authentication for your protection.
		image SIPC Insured, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/shield-check.svg'
		heading SIPC Insured
		paragraph
			StaticText Securities in your account are
			StaticText protected up to $500,000 through Apex Clearing.
			StaticText For details, visit www.sipc.org.
			StaticText On top of this,
			StaticText Apex Clearing
			StaticText has purchased an additional insurance policy to supplement SIPC protection.
		heading No Expense Ratios No AUM Fees No trading commissions And your first 6 months are free
		Video
		paragraph
			StaticText /month
		link Get Started, url='https://double.finance/sign-up'
		heading See how much youcould save on Fees
		LabelText
			StaticText Portfolio Starting Value
			textbox Portfolio Starting Value value='$500,000'
		LabelText
			StaticText Timeframe in Years
			textbox Timeframe in Years value='30'
		LabelText
			StaticText Your Monthly Contribution
			textbox Your Monthly Contribution value='$2,000'
		LabelText
			StaticText Estimated Annual Return
			textbox Estimated Annual Return value='7%'
		LabelText
			StaticText Advisor Fee (or ETF Expense Ratio)
			textbox Advisor Fee (or ETF Expense Ratio) value='1%'
		button 1%Typical Advisor Fee
		button 0.89%Empower
		button 0.25%Wealthfront
		button 0.1%Frec
		button Search for any ETF
			image
		heading Money saved with Double $1.30M
		paragraph
			StaticText Advisor's Effective Rate
			image
		paragraph
			StaticText $2,011/hour
		paragraph
			StaticText Estimated portfolio value with Double
		paragraph
			StaticText $6.07M
		paragraph
			StaticText Estimated portfolio value with Advisor
		paragraph
			StaticText $4.77M
		image
			StaticText 2030
			StaticText 2040
			StaticText 2050
			StaticText $0
			StaticText $2M
			StaticText $4M
			StaticText $6M
		paragraph
			StaticText For illustrative purposes only ⁴
		heading Why Double is better than rest
		StaticText Direct Index, Dollar Cost Average and Tax Loss Harvest² a custom portfolio, all within one account.
		StaticText Investing with Double is
		StaticText commission-free
		table
			rowgroup
				row
					columnheader Features
					columnheader double-logo
						image double-logo, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/white-logo.svg'
					columnheader M1
					columnheader Wealthfront
					columnheader Robinhood
					columnheader Frec
			rowgroup
				row
					cell Direct Index popular funds¹
						StaticText Direct Index popular funds
						StaticText ¹
					cell 20+
					cell dash
						image dash, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/dash.svg'
					cell 2
					cell dash
						image dash, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/dash.svg'
					cell 3
				row
					cell Tax aware rebalancing and automated tax loss harvesting²
						StaticText Tax aware rebalancing and automated tax loss harvesting
						StaticText ²
					cell check
						image check, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/white-check.svg'
					cell dash
						image dash, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/dash.svg'
					cell check
						image check, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/white-check.svg'
					cell dash
						image dash, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/dash.svg'
					cell check
						image check, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/white-check.svg'
				row
					cell Dollar Cost Average into and between strategies
						StaticText Dollar Cost Average into and between strategies
					cell check
						image check, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/white-check.svg'
					cell dash
						image dash, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/dash.svg'
					cell dash
						image dash, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/dash.svg'
					cell dash
						image dash, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/dash.svg'
					cell dash
						image dash, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/dash.svg'
				row
					cell Rebalance automatically to keep your exposure where you want it
						StaticText Rebalance automatically to keep your exposure where you want it
					cell check
						image check, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/white-check.svg'
					cell Partially
					cell check
						image check, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/white-check.svg'
					cell dash
						image dash, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/dash.svg'
					cell check
						image check, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/white-check.svg'
				row
					cell Factor in taxes, trading costs, holding costs and factor models to determine optimal trades
						StaticText Factor in taxes, trading costs, holding costs and factor models to determine optimal trades
					cell check
						image check, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/white-check.svg'
					cell dash
						image dash, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/dash.svg'
					cell check
						image check, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/white-check.svg'
					cell dash
						image dash, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/dash.svg'
					cell Partially
				row
					cell Zero AUM fees
						StaticText Zero AUM fees
					cell check
						image check, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/white-check.svg'
					cell check
						image check, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/white-check.svg'
					cell dash
						image dash, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/dash.svg'
					cell check
						image check, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/white-check.svg'
					cell dash
						image dash, url='https://double-marketing-page-assets.s3.amazonaws.com/v2-landing/dash.svg'
		heading Investing made simple
		StaticText Working round the clock
		StaticText for you
		StaticText Double analyzes your portfolio every day so you don't have to. We watch for things like wash sales, stock splits, dividends and portfolio drift. If there are trades that our algorithm thinks will improve your portfolio, we will make them all while leaving you in control.
		image monitor-stock, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-marketing-page-assets.s3.amazonaws.com%2Fv2-landing%2Finvesting-pic-1.png&w=1920&q=75'
		heading Dollar Cost Average between strategies
		StaticText Double makes it dead simple to move money between various active or passive strategies. This gives you deep control and can potentially help you spread out timing risk.
		image portfolio-allocation, url='https://double.finance/_next/image?url=%2Fimages%2Fallocation-pic.png&w=1920&q=75'
		heading Double Handles the Busy Work
		StaticText Double keeps a keen eye on your portfolio, hunting for tax loss harvesting opportunities and prime rebalancing moments.
		StaticText Today
		StaticText in 8:23
		image Tesla Inc, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TSLA.png&w=32&q=75'
		image Airbnb Inc - Ordinary Shares - Class A, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ABNB.png&w=32&q=75'
		image Home Depot, Inc., url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_HD.png&w=32&q=75'
		image Lucid Group Inc, url='https://double.finance/_next/image?url=%2Fimages%2Fcompany_logo_LCID.png&w=32&q=75'
		image Meta Platforms Inc - Ordinary Shares - Class A, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=32&q=75'
		StaticText 47 Trades
		StaticText are scheduled
		image
		StaticText Buy
		StaticText $500
		image
		StaticText Sell
		StaticText $200
		image coin1, url='https://double.finance/_next/image?url=%2Fimages%2Ficon-coins%2Fabnb.png&w=128&q=75'
		image coin1, url='https://double.finance/_next/image?url=%2Fimages%2Ficon-coins%2Fmeta.png&w=96&q=75'
		image coin1, url='https://double.finance/_next/image?url=%2Fimages%2Ficon-coins%2Fnetflix.png&w=96&q=75'
		heading Double in action
		image Exclude Tech, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-marketing-page-assets.s3.amazonaws.com%2Fv2-landing%2Faction-1.png&w=1920&q=75'
		heading Work for MSFT and want to exclude their stock?
			StaticText MSFT
		paragraph
			StaticText Buy a direct indexed US Top 500 Portfolio, remove
			StaticText MSFT
			StaticText entirely and cut the rest of your tech exposure in half.
		heading Did you know AI was going to be a big deal before everyone else?
		paragraph
			StaticText Double makes it easy to tilt your portfolio towards your hunches. Pick a handful of stocks set to benefit from the Inflation Reduction Act, or some that target the booming AI and semiconductor industry, or shift your portfolio towards the explosive meme growth of Zyn.
		heading Feeling confident in the overall market and ready to pile on the risk?
		paragraph
			StaticText Follow Hedgefundie’s Adventure, which uses 3x leverage in a Stock and Bond ETF to try and increase returns. Or pick from our smart screens that target top growing companies or even all of the YC Public Companies.
		heading Think we’re headed for a recession and want to take some chips off the table?
		paragraph
			StaticText You can invest in a version of Ray Dalio’s All Weather Portfolio comprising 5 ETFs or John Bogle's Majesty of Simplicity and migrate between these Strategies and Bonds over time.
		heading Build and backtest your own stock index!
		paragraph
			StaticText Use our Stock and ETF Screeners to build your very own personalized portfolio
		image JJ Maxwell, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-marketing-page-assets.s3.amazonaws.com%2Fv2-landing%2Fceo.png&w=1920&q=75'
		StaticText Message from our CEO
		StaticText “We’re on a mission to revolutionize investing by providing
		StaticText world class portfolio
		StaticText tools to everyday investors
		StaticText without any
		StaticText AUM fees”
		StaticText — JJ Maxwell
		StaticText Founder of Double Finance
		heading A Smarter Investing Account
		StaticText Some restrictions and fees may apply.
		link Get Started, url='https://double.finance/sign-up'
			button Get Started
		heading Still have questions?
		StaticText Meet with our founders who can give you an overview of Double works, answer questions on how it works under the hood, and provide support with the platform.
		link Schedule a Call, url='https://calendly.com/jmaxwell-6dhm/30min'
			button Schedule a Call
		heading Questions & Answers
		heading Are my assets protected on Double?
			button Are my assets protected on Double?, expanded=False
				image
		heading What happens if Double goes out of business?
			button What happens if Double goes out of business?, expanded=False
				image
		heading What is direct indexing and how is it different from buying an ETF?
			button What is direct indexing and how is it different from buying an ETF?, expanded=False
				image
		heading Is Direct Indexing new?
			button Is Direct Indexing new?, expanded=False
				image
		heading How do I transfer assets to Double?
			button How do I transfer assets to Double?, expanded=False
				image
		heading What if I want to withdraw my funds?
			button What if I want to withdraw my funds?, expanded=False
				image
		heading Can I change my portfolio anytime I want?
			button Can I change my portfolio anytime I want?, expanded=False
				image
		heading What can I customize on Double?
			button What can I customize on Double?, expanded=False
				image
		heading What is the minimum amount I need to invest on Double?
			button What is the minimum amount I need to invest on Double?, expanded=False
				image
		heading Will my tax return be complicated and require a lot of data entry?
			button Will my tax return be complicated and require a lot of data entry?, expanded=False
				image
		heading Learn more from Blog
		link blog-banner Double crosses $10M in AUM + $3.9M Seed Round Double is proud to announce we crossed $10M in AUM within 3 months of our beta launch and our $3.9M Seed Round, url='https://double.finance/blog/10M-AUM'
			image blog-banner, url='https://double.finance/_next/image?url=https%3A%2F%2Fancient-power-5ebf539d25.media.strapiapp.com%2FBlog_Post_02_ba2fd645c6.png&w=1920&q=75'
			heading Double crosses $10M in AUM + $3.9M Seed Round
			paragraph
				StaticText Double is proud to announce we crossed $10M in AUM within 3 months of our beta launch and our $3.9M Seed Round
		link blog-banner Introducing Per-Strategy Optimization Giving users more power and control over their investments., url='https://double.finance/blog/per-strategy-optimization'
			image blog-banner, url='https://double.finance/_next/image?url=https%3A%2F%2Fancient-power-5ebf539d25.media.strapiapp.com%2Fblog_post_01_6ffaeed55b.png&w=1920&q=75'
			heading Introducing Per-Strategy Optimization
			paragraph
				StaticText Giving users more power and control over their investments.
		link Explore Blog, url='https://double.finance/blog'
			button Explore Blog
		image
		heading Zero expense ratio index investing
		heading Company
		list
			listitem
				link Disclosures, url='https://double.finance/disclosures'
			listitem
				link LinkedIn, url='https://www.linkedin.com/company/doublefinance/'
			listitem
				link X, url='https://x.com/Double_Finance'
		heading Resources
		list
			listitem
				link Blog, url='https://double.finance/blog'
			listitem
				link Learn, url='https://double.finance/learn'
			listitem
				link Fee Calculator, url='https://double.finance/tools/fee-calculator'
			listitem
				link Tax Bracket Estimator, url='https://double.finance/tools/tax-bracket-estimator'
		heading Popular ETFs
		list
			listitem
				link SPY, url='https://double.finance/p/stock/SPY'
			listitem
				link VOO, url='https://double.finance/p/stock/VOO'
			listitem
				link VTI, url='https://double.finance/p/stock/VTI'
			listitem
				link CALF, url='https://double.finance/p/stock/CALF'
			listitem
				link AVUV, url='https://double.finance/p/stock/AVUV'
			listitem
				link SGOV, url='https://double.finance/p/stock/SGOV'
			listitem
				link COWZ, url='https://double.finance/p/stock/COWZ'
			listitem
				link SMH, url='https://double.finance/p/stock/SMH'
			listitem
				link QQQ, url='https://double.finance/p/stock/QQQ'
			listitem
				link TLT, url='https://double.finance/p/stock/TLT'
			listitem
				link VGT, url='https://double.finance/p/stock/VGT'
			listitem
				link SCHD, url='https://double.finance/p/stock/SCHD'
		heading ETF Comparisons
		list
			listitem
				link AVDE vs CGDG, url='https://double.finance/p/stock/AVDE/CGDG'
			listitem
				link QQQ vs SPY, url='https://double.finance/p/stock/QQQ/SPY'
			listitem
				link QQQ vs VOO, url='https://double.finance/p/stock/QQQ/VOO'
			listitem
				link MDYG vs SCHM, url='https://double.finance/p/stock/MDYG/SCHM'
			listitem
				link SCHD vs VIG, url='https://double.finance/p/stock/SCHD/VIG'
			listitem
				link VOO vs VUG, url='https://double.finance/p/stock/VOO/VUG'
		generic, hasPopup='dialog'
			StaticText Terms of Service
		generic, hasPopup='dialog'
			StaticText Privacy Policy
		paragraph
			StaticText © Double Finance, 2024
		StaticText Double is a registered investment adviser with the US Securities and Exchange Commission (SEC). While such registration does not imply a certain level of skill, it does require us to follow federal regulations that protect you, the investor. By law, we must provide investment advice that is in the best interest of our client. Please refer to Double's
		link Form CRS, url='https://double-prod-disclosures.s3.amazonaws.com/crs_329617.pdf'
		StaticText for important additional information.
		StaticText The publicly available portions of the Platform (i.e., the sections of the Platform that are available to individuals who are not party to a Client Agreement - including double.finance) are provided for educational purposes only and are not intended to provide legal, tax, or financial planning advice. To the extent that any of the content published on publicly available portions of the Platform may be deemed to be investment advice, such information is impersonal and not tailored to the investment needs of any specific person. Nothing on the publicly available portions of the Platform should be construed as a solicitation or offer, or recommendation, to buy or sell any security. All charts, figures, and graphs on the publicly available websites are for illustrative purposes only. Before investing, you should consider whether any investment, investment strategy, security, other asset, or related transaction is appropriate for you based on your personal investment objectives, financial circumstances, and risk tolerance. You are also encouraged to consult your legal, tax, or investment professional regarding your specific situation. Registration does not imply a certain level of skill or training.
		StaticText Investing involves risk. The value of your investment will fluctuate, and you may gain or lose money.
		StaticText The contents of the Platform may contain forward-looking statements that are based on management's beliefs, assumptions, current expectations, estimates, and projections about the financial industry, the economy, or Global Predictions itself. Forward-looking statements are not guarantees of the underlying expected actions or future performance and future results may differ significantly from those anticipated by the forward-looking statements. Therefore, actual results and outcomes may materially differ from what may be expressed or forecasted in such forward-looking statements.
		StaticText ¹ Data as of July 2024.
		StaticText ² Availability of tax loss harvesting depends on portfolio diversity.
		StaticText ³ As of November 8, 2024. The optional Cash Sweep program takes the cash sitting in your brokerage account and moves it to an FDIC-insured interest-earning deposit account. The current yield is 1.0%, rates subject to change at any time. The cash sweep program is made available in coordination with Apex Clearing Corporation. Please read the
		link Important Disclosures, url='https://double-disclosures.s3.amazonaws.com/Apex-FDIC-Sweep-Program-Terms-and-Conditions-1.pdf'
		StaticText for more information.
		StaticText ⁴ This analysis calculator tool is for illustrative purposes only and is not financial advice. We do not guarantee the accuracy of the results or their relevance to your particular circumstances. This calculator uses hypothetical historical data and does not take into account the effect of taxes on a taxable account. Hypothetical historical data is no guarantee of future performance and this calculator is not intended to predict actual performance. The input of different time periods, amounts, and fees will vary calculator results. Average ETF fee is based on the AUM weighted average of US ETFs as of September 2024,
		link see more information, url='https://www.etf.com/topics/sp-500'
		StaticText . Note that you can purchase ETFs through Double, which may incur additional fees.
		StaticText Full pricing details along with an FAQ can be found
		link here, url='https://double.finance/pricing'
		StaticText Data displayed in charts and graphics above are for illustrative purposes only and do not reflect actual investment results and are not a guarantee of future results.
		StaticText By using double.finance, you accept our
		generic, hasPopup='dialog'
			StaticText Terms of Use
		StaticText and
		generic, hasPopup='dialog'
			StaticText Privacy Policy
		StaticText . Double is only available to US residents.
		StaticText See Double Finance
		link Form ADV Part IIA, url='https://double-disclosures.s3.amazonaws.com/Double+Finance+ADV+Part+IIA.pdf'
		StaticText for additional information. Double does not guarantee that the results of its advice, recommendations, or the objectives of its direct index or cash management strategies will be achieved. We make no assurance that the investment process will consistently lead to successful investing. Before you invest, you should carefully review and consider your investment objectives as well as the risks, charges, and expenses of the underlying securities. There is at least a $1,000 account minimum required to participate in Double's strategies, although some strategies may have higher minimums.
		StaticText Double does not provide tax, or legal advice. Double's website, brokerage, and advisory services are not intended for persons of any jurisdiction where Double is not authorized to do business. Tax savings will vary from client to client due to many factors including market conditions, tax characteristics of securities, client-imposed investment restrictions, client tax rate or status, and changes in tax regulations.
	alert, atomic
```
</details>



```
RootWebArea Direct Indexing | Discover Direct Indexing, ETFs & Vehicles For You | Double Finance, focused, url='https://double.finance/p/explore'
	dialog, modal=False
		heading Your Risk Tolerance
		paragraph
			StaticText Your risk tolerance indicates how comfortable you are with the possibility of experiencing losses in exchange for potential gains. Adjusting this setting helps align your investment choices with your financial goals and comfort level.
```
<details><summary>Show more</summary>

```
		LabelText
			[14460] radio High See all strategies including those with more volatility (ups and downs) that may also result in potential high returns., center=(720,462), checked=, contenteditable=True, focused, type=radio
			StaticText High
			StaticText See all strategies including those with more volatility (ups and downs) that may also result in potential high returns.
		LabelText
			[14465] radio Medium See moderate-risk strategies that aim for a balance of growth and stability., center=(720,568), checked='false', contenteditable=True, type=radio
			StaticText Medium
			StaticText See moderate-risk strategies that aim for a balance of growth and stability.
		[14463] span, center=(968,496), inner_text=See all strategies including those with more volatility (ups and downs) that may also result in potential high returns.
		[14462] span, center=(968,462), inner_text=High
		LabelText
			[14470] radio Low See only conservative strategies., center=(720,654), checked='false', contenteditable=True, type=radio
			StaticText Low
			StaticText See only conservative strategies.
		[14468] span, center=(968,592), inner_text=See moderate-risk strategies that aim for a balance of growth and stability.
		[14467] span, center=(968,568), inner_text=Medium
		[14475] button Submit, center=(1182,768)
		[14473] span, center=(968,678), inner_text=See only conservative strategies.
		[14472] span, center=(968,654), inner_text=Low
```
</details>

**Reasoning for action:** By clicking the 'Explore Indexes' button, I am proceeding to the next step in the user's instructed workflow. This action allows me to access the available investment strategies categorized by their risk levels, which is essential for the user to find a strategy aligned with their risk tolerance.

**Action:** click('270') # Click on the 'Explore Indexes' button to view available investment strategies.

**Change Description:** After the user clicked the 'Explore Indexes' button, the browser navigated to a new page where the user is presented with options to select their risk tolerance for investment strategies. This page allows users to choose between 'High', 'Medium', and 'Low' risk strategies, along with a submit button, indicating a shift in focus to personalized investment options.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://double.finance/p/explore

https://double.finance/p/explore

**Content (before/after):** 

```
RootWebArea Direct Indexing | Discover Direct Indexing, ETFs & Vehicles For You | Double Finance, focused, url='https://double.finance/p/explore'
	dialog, modal=False
		heading Your Risk Tolerance
		paragraph
			StaticText Your risk tolerance indicates how comfortable you are with the possibility of experiencing losses in exchange for potential gains. Adjusting this setting helps align your investment choices with your financial goals and comfort level.
```
<details><summary>Show more</summary>

```
		LabelText
			[14460] radio High See all strategies including those with more volatility (ups and downs) that may also result in potential high returns., center=(720,462), checked=, contenteditable=True, focused, type=radio
			StaticText High
			StaticText See all strategies including those with more volatility (ups and downs) that may also result in potential high returns.
		LabelText
			[14465] radio Medium See moderate-risk strategies that aim for a balance of growth and stability., center=(720,568), checked='false', contenteditable=True, type=radio
			StaticText Medium
			StaticText See moderate-risk strategies that aim for a balance of growth and stability.
		[14463] span, center=(968,496), inner_text=See all strategies including those with more volatility (ups and downs) that may also result in potential high returns.
		[14462] span, center=(968,462), inner_text=High
		LabelText
			[14470] radio Low See only conservative strategies., center=(720,654), checked='false', contenteditable=True, type=radio
			StaticText Low
			StaticText See only conservative strategies.
		[14468] span, center=(968,592), inner_text=See moderate-risk strategies that aim for a balance of growth and stability.
		[14467] span, center=(968,568), inner_text=Medium
		[14475] button Submit, center=(1182,768)
		[14473] span, center=(968,678), inner_text=See only conservative strategies.
		[14472] span, center=(968,654), inner_text=Low
```
</details>



```
RootWebArea Direct Indexing | Discover Direct Indexing, ETFs & Vehicles For You | Double Finance, focused, url='https://double.finance/p/explore'
	dialog, modal=False
		heading Your Risk Tolerance
		paragraph
			StaticText Your risk tolerance indicates how comfortable you are with the possibility of experiencing losses in exchange for potential gains. Adjusting this setting helps align your investment choices with your financial goals and comfort level.
```
<details><summary>Show more</summary>

```
		LabelText
			[14460] radio High See all strategies including those with more volatility (ups and downs) that may also result in potential high returns., center=(720,462), checked=, contenteditable=True, focused, type=radio
			StaticText High
			StaticText See all strategies including those with more volatility (ups and downs) that may also result in potential high returns.
		LabelText
			[14465] radio Medium See moderate-risk strategies that aim for a balance of growth and stability., center=(720,568), checked='false', contenteditable=True, type=radio
			StaticText Medium
			StaticText See moderate-risk strategies that aim for a balance of growth and stability.
		[14463] span, center=(968,496), inner_text=See all strategies including those with more volatility (ups and downs) that may also result in potential high returns.
		[14462] span, center=(968,462), inner_text=High
		LabelText
			[14470] radio Low See only conservative strategies., center=(720,654), checked='false', contenteditable=True, type=radio
			StaticText Low
			StaticText See only conservative strategies.
		[14468] span, center=(968,592), inner_text=See moderate-risk strategies that aim for a balance of growth and stability.
		[14467] span, center=(968,568), inner_text=Medium
		[14475] button Submit, center=(1182,768)
		[14473] span, center=(968,678), inner_text=See only conservative strategies.
		[14472] span, center=(968,654), inner_text=Low
```
</details>

**Reasoning for action:** I clicked on the 'High' risk tolerance radio button because this is the selection that fulfills the user's request for investment strategies that correspond to a high-risk profile. By selecting this option, I ensure that the subsequent submission will lead to relevant investment strategies being displayed for the user, thus making progress toward meeting the user's goal of exploring suitable investment strategies.

**Action:** click('14460') # Click on the 'High' risk tolerance option.

**Change Description:** The 'High' risk tolerance radio option was clicked, resulting in it becoming currently focused, but there was no change in the checked state of the radio buttons; the selected option remains unchecked.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://double.finance/p/explore

https://double.finance/p/explore

**Content (before/after):** 

```
RootWebArea Direct Indexing | Discover Direct Indexing, ETFs & Vehicles For You | Double Finance, focused, url='https://double.finance/p/explore'
	dialog, modal=False
		heading Your Risk Tolerance
		paragraph
			StaticText Your risk tolerance indicates how comfortable you are with the possibility of experiencing losses in exchange for potential gains. Adjusting this setting helps align your investment choices with your financial goals and comfort level.
```
<details><summary>Show more</summary>

```
		LabelText
			[14460] radio High See all strategies including those with more volatility (ups and downs) that may also result in potential high returns., center=(720,462), checked=, contenteditable=True, focused, type=radio
			StaticText High
			StaticText See all strategies including those with more volatility (ups and downs) that may also result in potential high returns.
		LabelText
			[14465] radio Medium See moderate-risk strategies that aim for a balance of growth and stability., center=(720,568), checked='false', contenteditable=True, type=radio
			StaticText Medium
			StaticText See moderate-risk strategies that aim for a balance of growth and stability.
		[14463] span, center=(968,496), inner_text=See all strategies including those with more volatility (ups and downs) that may also result in potential high returns.
		[14462] span, center=(968,462), inner_text=High
		LabelText
			[14470] radio Low See only conservative strategies., center=(720,654), checked='false', contenteditable=True, type=radio
			StaticText Low
			StaticText See only conservative strategies.
		[14468] span, center=(968,592), inner_text=See moderate-risk strategies that aim for a balance of growth and stability.
		[14467] span, center=(968,568), inner_text=Medium
		[14475] button Submit, center=(1182,768)
		[14473] span, center=(968,678), inner_text=See only conservative strategies.
		[14472] span, center=(968,654), inner_text=Low
```
</details>



```
RootWebArea Direct Indexing | Discover Direct Indexing, ETFs & Vehicles For You | Double Finance, focused, url='https://double.finance/p/explore'
	banner
		[9890] link, center=(118,32), url='https://double.finance/'
			image
		list
```
<details><summary>Show more</summary>

```
			[9894] link Explore, center=(805,31), url='https://double.finance/p/explore'
			[9896] link Pricing, center=(891,31), url='https://double.finance/pricing'
			generic, hasPopup='menu'
				StaticText Resources
				[9898] image, center=(1042,33)
			[9900] link Contact, center=(1113,31), url='https://double.finance/contact'
		[9902] link Sign In, center=(1724,32), url='https://double.finance/login'
			button Sign In
		[9904] link Sign Up, center=(1816,32), url='https://double.finance/sign-up'
			button Sign Up
	[9921] textbox Search for a strategy, center=(738,107), contenteditable=True
	paragraph
		StaticText Risk Tolerance
		image
		[9925] span, center=(1550,107)
	[9928] button High, center=(1621,107), type=button
	[9929] button Medium, center=(1723,107), type=button
	[9930] button Low, center=(1825,107), type=button
	heading Categories
	[9939] link Classic Diverse Direct Indexes, center=(171,256), url='https://double.finance/p/explore/direct-indexing'
	[9940] link Risky Business, center=(434,256), url='https://double.finance/p/explore/higher-risk'
	[9941] link Sector Specific, center=(697,256), url='https://double.finance/p/explore/sectors'
	[9942] link Factor Specific, center=(960,256), url='https://double.finance/p/explore/factor-thesis'
	[9943] link Smart Screens, center=(1223,256), url='https://double.finance/p/explore/smart-screens'
	[9944] link Battle of the VCs, center=(1486,256), url='https://double.finance/p/explore/vc-indexing'
	[9945] link Boglehead Portfolios, center=(1749,256), url='https://double.finance/p/explore/boglehead-indexing'
	heading Classic Diverse Direct Indexes
	image
	[9951] span, center=(308,363)
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $15,000
	[9964] span, center=(204,423), inner_text=$15,000
	paragraph
		StaticText SPY
	[9970] span, center=(274,423), inner_text=SPY
	[9978] link US Top 500, center=(209,475), url='https://double.finance/p/explore/3'
		heading US Top 500
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	[14477] paragraph, center=(209,588), inner_text=The textbook passive investment vehicle is generally considered to comprise of 500 of the largest stocks traded within the US. Double's take on this exposes a client to the US stock market in a diversified way without any expense ratio.
		StaticText The textbook passive investment vehicle is generally considered to comprise of 500 of the largest stocks traded within the US. Double's take on this exposes a client to the US stock market in a diversified way without any expense ratio.
	[10906] span, center=(1854,985), inner_text=Capital Preservation
	[10831] span, center=(1579,985), inner_text=Maximum Growth
	[10829] span, center=(1486,985), inner_text=Speculation
	[10817] span, center=(1634,903), inner_text=ARKK
	[10811] span, center=(1564,903), inner_text=$1,000
	[10756] span, center=(1233,985), inner_text=Maximum Growth
	[10754] span, center=(1140,985), inner_text=Speculation
	[10740] span, center=(1218,903), inner_text=$1,000
	[10685] span, center=(887,985), inner_text=Maximum Growth
	[10683] span, center=(794,985), inner_text=Speculation
	[10669] span, center=(872,903), inner_text=$1,000
	[10614] span, center=(574,985), inner_text=Growth Income
	[10612] span, center=(494,985), inner_text=Balanced
	[10610] span, center=(436,985), inner_text=Growth
	[10596] span, center=(546,903), inner_text=$1,000
	[10541] span, center=(195,985), inner_text=Maximum Growth
	[10539] span, center=(102,985), inner_text=Speculation
	[10525] span, center=(180,903), inner_text=$1,000
	[10512] span, center=(183,843)
	[10418] span, center=(1850,747), inner_text=+10.42%
	[10377] span, center=(1820,505), inner_text=Growth
	[10352] svg, center=(1667,747)
	[10339] span, center=(1500,747), inner_text=+14.11%
	[10302] span, center=(1612,505), inner_text=Growth Income
	[10300] span, center=(1532,505), inner_text=Balanced
	[10298] span, center=(1474,505), inner_text=Growth
	[10286] span, center=(1658,423), inner_text=IWB
	[10280] span, center=(1589,423), inner_text=$33,000
	[10273] svg, center=(1321,747)
	[10260] span, center=(1158,747), inner_text=+10.67%
	[10223] span, center=(1266,505), inner_text=Growth Income
	[10221] span, center=(1186,505), inner_text=Balanced
	[10219] span, center=(1128,505), inner_text=Growth
	[10207] span, center=(1305,423), inner_text=RSP
	[10201] span, center=(1239,423), inner_text=$2,800
	[10194] svg, center=(975,747)
	[10181] span, center=(812,747), inner_text=+10.47%
	[10144] span, center=(920,505), inner_text=Growth Income
	[10142] span, center=(840,505), inner_text=Balanced
	[10140] span, center=(782,505), inner_text=Growth
	[10128] span, center=(956,423), inner_text=VO
	[10122] span, center=(893,423), inner_text=$3,500
	[10115] svg, center=(629,747)
	[10102] span, center=(466,747), inner_text=+16.36%
	[10065] span, center=(574,505), inner_text=Growth Income
	[10063] span, center=(494,505), inner_text=Balanced
	[10061] span, center=(436,505), inner_text=Growth
	[10049] span, center=(613,423), inner_text=OEF
	[10043] span, center=(547,423), inner_text=$2,200
	[10036] svg, center=(283,747)
	[10023] span, center=(118,747), inner_text=+14.31%
	[9986] span, center=(228,505), inner_text=Growth Income
	[9984] span, center=(148,505), inner_text=Balanced
	[9982] span, center=(90,505), inner_text=Growth
	[9992] paragraph, center=(136,654), inner_text=Top Sector
		StaticText Top Sector
	[9993] paragraph, center=(136,674), inner_text=Information Technology
		StaticText Information Technology
	[9995] paragraph, center=(308,654), inner_text=Top Holdings
		StaticText Top Holdings
	[9999] image Apple Inc logo, center=(275,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
	[10002] image NVIDIA Corp logo, center=(293,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
	[10005] image Microsoft Corporation logo, center=(311,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
	[10008] image Amazon.com Inc. logo, center=(329,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
	[10011] image Meta Platforms Inc - Ordinary Shares - Class A logo, center=(347,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
	[10016] paragraph, center=(93,727), inner_text=Return
		StaticText Return
	[10018] image, center=(121,727)
	[10020] image, center=(82,747)
	StaticText +14.31%
	[10026] paragraph, center=(201,727), inner_text=Expense Ratio
		StaticText Expense Ratio
	[10028] image, center=(252,727)
	[10029] paragraph, center=(209,747), inner_text=0.00%
		StaticText 0.00
		StaticText %
	[10032] paragraph, center=(302,727), inner_text=Holdings
		StaticText Holdings
	[10034] image, center=(337,727)
	paragraph
		StaticText 502
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $2,200
	paragraph
		StaticText OEF
	[10057] link US 100, center=(555,475), url='https://double.finance/p/explore/4'
		heading US 100
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	[14478] paragraph, center=(555,572), inner_text=This strategy offers a convenient way to access the largest 100 large-cap stocks across various sectors within the U.S. market.
		StaticText This strategy offers a convenient way to access the largest 100 large-cap stocks across various sectors within the U.S. market.
	[10071] paragraph, center=(482,654), inner_text=Top Sector
		StaticText Top Sector
	[10072] paragraph, center=(482,674), inner_text=Information Technology
		StaticText Information Technology
	[10074] paragraph, center=(654,654), inner_text=Top Holdings
		StaticText Top Holdings
	[10078] image Apple Inc logo, center=(621,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
	[10081] image NVIDIA Corp logo, center=(639,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
	[10084] image Microsoft Corporation logo, center=(657,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
	[10087] image Amazon.com Inc. logo, center=(675,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
	[10090] image Meta Platforms Inc - Ordinary Shares - Class A logo, center=(693,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
	[10095] paragraph, center=(439,727), inner_text=Return
		StaticText Return
	[10097] image, center=(467,727)
	[10099] image, center=(428,747)
	StaticText +16.36%
	[10105] paragraph, center=(549,727), inner_text=Expense Ratio
		StaticText Expense Ratio
	[10107] image, center=(600,727)
	[10108] paragraph, center=(557,747), inner_text=0.00%
		StaticText 0.00
		StaticText %
	[10111] paragraph, center=(648,727), inner_text=Holdings
		StaticText Holdings
	[10113] image, center=(683,727)
	paragraph
		StaticText 101
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $3,500
	paragraph
		StaticText VO
	[10136] link USA Mid-Cap Companies, center=(901,475), url='https://double.finance/p/explore/66'
		heading USA Mid-Cap Companies
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	[14479] paragraph, center=(901,588), inner_text=Targeting mid-sized U.S. companies, striking a balance between growth potential and stability. Investing in sectors like industrials, technology, consumer goods, and healthcare, it offers exposure to companies with established market positions and growth opportunities.
		StaticText Targeting mid-sized U.S. companies, striking a balance between growth potential and stability. Investing in sectors like industrials, technology, consumer goods, and healthcare, it offers exposure to companies with established market positions and growth opportunities.
	[10150] paragraph, center=(790,654), inner_text=Top Sector
		StaticText Top Sector
	[10151] paragraph, center=(790,674), inner_text=Industrials
		StaticText Industrials
	[10153] paragraph, center=(1000,654), inner_text=Top Holdings
		StaticText Top Holdings
	[10157] image Palantir Technologies Inc - Ordinary Shares - Class A logo, center=(967,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PLTR.png&w=96&q=75'
	[10160] image Amphenol Corp. - Ordinary Shares - Class A logo, center=(985,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_APH.png&w=96&q=75'
	[10163] image Constellation Energy Corporation logo, center=(1003,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CEG.png&w=96&q=75'
	[10166] image Motorola Solutions Inc logo, center=(1021,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSI.png&w=96&q=75'
	[10169] image Welltower Inc. logo, center=(1039,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WELL.png&w=96&q=75'
	[10174] paragraph, center=(785,727), inner_text=Return
		StaticText Return
	[10176] image, center=(813,727)
	[10178] image, center=(774,747)
	StaticText +10.47%
	[10184] paragraph, center=(894,727), inner_text=Expense Ratio
		StaticText Expense Ratio
	[10186] image, center=(946,727)
	[10187] paragraph, center=(902,747), inner_text=0.00%
		StaticText 0.00
		StaticText %
	[10190] paragraph, center=(994,727), inner_text=Holdings
		StaticText Holdings
	[10192] image, center=(1029,727)
	paragraph
		StaticText 310
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $2,800
	paragraph
		StaticText RSP
	[10215] link Equal Weighted US Top 500, center=(1247,475), url='https://double.finance/p/explore/35'
		heading Equal Weighted US Top 500
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	[14480] paragraph, center=(1247,588), inner_text=This index provides equal-weight exposure to the top 500 companies in the US, offering a unique approach compared to traditional market-cap weighted indexes. With an aim to reduce concentration risk by allocating equal amounts to each constituent, it potentially benefits from smaller companies' outperformance.
		StaticText This index provides equal-weight exposure to the top 500 companies in the US, offering a unique approach compared to traditional market-cap weighted indexes. With an aim to reduce concentration risk by allocating equal amounts to each constituent, it potentially benefits from smaller companies' outperformance.
	[10229] paragraph, center=(1136,654), inner_text=Top Sector
		StaticText Top Sector
	[10230] paragraph, center=(1136,674), inner_text=Industrials
		StaticText Industrials
	[10232] paragraph, center=(1346,654), inner_text=Top Holdings
		StaticText Top Holdings
	[10236] image Broadcom Inc logo, center=(1313,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
	[10239] image Darden Restaurants, Inc. logo, center=(1331,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DRI.png&w=96&q=75'
	[10242] image Jabil Inc logo, center=(1349,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JBL.png&w=96&q=75'
	[10245] image Palantir Technologies Inc - Ordinary Shares - Class A logo, center=(1367,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PLTR.png&w=96&q=75'
	[10248] image Vistra Corp logo, center=(1385,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_VST.png&w=96&q=75'
	[10253] paragraph, center=(1131,727), inner_text=Return
		StaticText Return
	[10255] image, center=(1159,727)
	[10257] image, center=(1120,747)
	StaticText +10.67%
	[10263] paragraph, center=(1241,727), inner_text=Expense Ratio
		StaticText Expense Ratio
	[10265] image, center=(1292,727)
	[10266] paragraph, center=(1249,747), inner_text=0.00%
		StaticText 0.00
		StaticText %
	[10269] paragraph, center=(1340,727), inner_text=Holdings
		StaticText Holdings
	[10271] image, center=(1375,727)
	paragraph
		StaticText 502
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $33,000
	paragraph
		StaticText IWB
	[10294] link US 1000, center=(1593,475), url='https://double.finance/p/explore/348'
		heading US 1000
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	[14481] paragraph, center=(1593,588), inner_text=This strategy tracks a market-cap-weighted index of the 1000-largest US companies. It offers broad exposure to the US equity market, encompassing a diverse range of sectors and industries. By investing in this fund, you gain access to the performance of large and well-established companies within the US economy.
		StaticText This strategy tracks a market-cap-weighted index of the 1000-largest US companies. It offers broad exposure to the US equity market, encompassing a diverse range of sectors and industries. By investing in this fund, you gain access to the performance of large and well-established companies within the US economy.
	[10308] paragraph, center=(1520,654), inner_text=Top Sector
		StaticText Top Sector
	[10309] paragraph, center=(1520,674), inner_text=Information Technology
		StaticText Information Technology
	[10311] paragraph, center=(1692,654), inner_text=Top Holdings
		StaticText Top Holdings
	[10315] image Apple Inc logo, center=(1659,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
	[10318] image NVIDIA Corp logo, center=(1677,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
	[10321] image Microsoft Corporation logo, center=(1695,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
	[10324] image Amazon.com Inc. logo, center=(1713,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
	[10327] image Meta Platforms Inc - Ordinary Shares - Class A logo, center=(1731,676), url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
	[10332] paragraph, center=(1477,727), inner_text=Return
		StaticText Return
	[10334] image, center=(1505,727)
	[10336] image, center=(1466,747)
	StaticText +14.11%
	[10342] paragraph, center=(1583,727), inner_text=Expense Ratio
		StaticText Expense Ratio
	[10344] image, center=(1634,727)
	[10345] paragraph, center=(1591,747), inner_text=0.00%
		StaticText 0.00
		StaticText %
	[10348] paragraph, center=(1686,727), inner_text=Holdings
		StaticText Holdings
	[10350] image, center=(1721,727)
	paragraph
		StaticText 992
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $5,100
	paragraph
		StaticText IJH
	link US Mid Cap, url='https://double.finance/p/explore/352'
		heading US Mid Cap
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	paragraph
		StaticText This strategy tracks a market-cap-weighted index of mid-cap US companies. This strategy offers targeted exposure to the growth potential of mid-sized businesses within the US market. With a diversified portfolio of holdings, it provides investors with a comprehensive approach to capturing the mid-cap segment's performance.
	[10387] paragraph, center=(1828,654), inner_text=Top Sector
		StaticText Top Sector
	[10388] paragraph, center=(1828,674), inner_text=Industrials
		StaticText Industrials
	paragraph
		StaticText Top Holdings
	image Williams-Sonoma, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WSM.png&w=96&q=75'
	image Emcor Group, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_EME.png&w=96&q=75'
	image Expand Energy Corp. - Ordinary Shares - New logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CHK.png&w=96&q=75'
	image Illumina Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ILMN.png&w=96&q=75'
	image Interactive Brokers Group Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_IBKR.png&w=96&q=75'
	[10411] paragraph, center=(1823,727), inner_text=Return
		StaticText Return
	[10413] image, center=(1851,727)
	[10415] image, center=(1812,747)
	StaticText +10.42%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 399
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $8,600
	paragraph
		StaticText IJR
	link US Small Cap, url='https://double.finance/p/explore/354'
		heading US Small Cap
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		StaticText This strategy tracks a market-cap-weighted index of primarily small-cap US stocks, representing a small portion of the total market. This strategy focuses on the growth potential of smaller companies, offering investors targeted exposure to this dynamic segment of the US equity market. With a diversified portfolio of holdings it provides a broad approach to small-cap investing.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Financials
	paragraph
		StaticText Top Holdings
	image Glaukos Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GKOS.png&w=96&q=75'
	image Bath & Body Works Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BBWI.png&w=96&q=75'
	image Alaska Air Group Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ALK.png&w=96&q=75'
	image ATI Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ATI.png&w=96&q=75'
	image VF Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_VFC.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +8.94%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 589
	heading Risky Business
	image
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $1,000
	[10535] link Equal MAMAA, center=(209,955), url='https://double.finance/p/explore/50'
		heading Equal MAMAA
	StaticText Speculation
	StaticText Maximum Growth
	[14486] paragraph, center=(209,1068), inner_text=First, it was FAANG, then names changed, and one got dropped; now, we have the familiar faces of Meta, Amazon, Microsoft, Apple, and Alphabet forming this equally weighted MAMAA collection. They are the best of the best. These tech innovators have been doing it for quite some time and don't appear to be going anywhere.
		StaticText First, it was FAANG, then names changed, and one got dropped; now, we have the familiar faces of Meta, Amazon, Microsoft, Apple, and Alphabet forming this equally weighted MAMAA collection. They are the best of the best. These tech innovators have been doing it for quite some time and don't appear to be going anywhere.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Communication Services
	paragraph
		StaticText Top Holdings
	image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
	image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
	image Alphabet Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GOOGL.png&w=96&q=75'
	image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
	image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +24.35%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 5
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $1,000
	[10606] link Large Market Beaters, center=(555,955), url='https://double.finance/p/explore/70'
		heading Large Market Beaters
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	[14487] paragraph, center=(555,1068), inner_text=Beating the market. That's what so many money managers aim to do, but it's much easier said than done. Over the past year, this collection has achieved that goal. They are the winners, and it wasn't due to small numbers. They are both the largest companies in the stock market (>$200Bn Market Cap) and, at that size, the only companies to outperform SPYs long term average return by 2x (20%)
		StaticText Beating the market. That's what so many money managers aim to do, but it's much easier said than done. Over the past year, this collection has achieved that goal. They are the winners, and it wasn't due to small numbers. They are both the largest companies in the stock market (>$200Bn Market Cap) and, at that size, the only companies to outperform SPYs long term average return by 2x (20%)
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Financials
	paragraph
		StaticText Top Holdings
	image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
	image Wells Fargo & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WFC.png&w=96&q=75'
	image T-Mobile US Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TMUS.png&w=96&q=75'
	image Salesforce Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CRM.png&w=96&q=75'
	image American Express Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AXP.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +29.05%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 25
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $1,000
	[10679] link Contrarian Picks, center=(901,955), url='https://double.finance/p/explore/76'
		heading Contrarian Picks
	StaticText Speculation
	StaticText Maximum Growth
	[14488] paragraph, center=(901,1068), inner_text=You better have a strong stomach if this portfolio interests you; it certainly isn't for the faint of heart. These are smaller companies that aren't being traded very heavily and while they may be cheap (PE <15), they have a lackluster TTM performance to show for it (<0%). Are they stocks to avoid or a list of potential hidden gems?
		StaticText You better have a strong stomach if this portfolio interests you; it certainly isn't for the faint of heart. These are smaller companies that aren't being traded very heavily and while they may be cheap (PE <15), they have a lackluster TTM performance to show for it (<0%). Are they stocks to avoid or a list of potential hidden gems?
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Consumer Discretionary
	paragraph
		StaticText Top Holdings
	image Rocky Brands, Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_RCKY.png&w=96&q=75'
	image Smart Powerr Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CREG.png&w=96&q=75'
	image SoundThinking Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_SSTI.png&w=96&q=75'
	image Urban One Inc - Ordinary Shares - Class D logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_UONEK.png&w=96&q=75'
	image CPS Technologies Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CPSH.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText -3.81%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 53
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $1,000
	[10750] link High Performance Small Cap, center=(1247,955), url='https://double.finance/p/explore/71'
		heading High Performance Small Cap
	StaticText Speculation
	StaticText Maximum Growth
	[14489] paragraph, center=(1247,1068), inner_text=Who doesn't love an underdog story? These may be small-cap stocks (<$1B in Market Cap), but they have packed in a mighty performance in the past year (>90% return). Another benefit of their small size is that there should still be plenty of room for them to continue growing.
		StaticText Who doesn't love an underdog story? These may be small-cap stocks (<$1B in Market Cap), but they have packed in a mighty performance in the past year (>90% return). Another benefit of their small size is that there should still be plenty of room for them to continue growing.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Health Care
	paragraph
		StaticText Top Holdings
	image Allot Ltd logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ALLT.png&w=96&q=75'
	image Dynagas LNG Partners LP - Unit logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DLNG.png&w=96&q=75'
	image Oxbridge Re Holdings Ltd logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_OXBR.png&w=96&q=75'
	image ClearPoint Neuro Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CLPT.png&w=96&q=75'
	image Graham Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GHM.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +33.93%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 52
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $1,000
	paragraph
		StaticText ARKK
	[10825] link Innovation Fund, center=(1593,955), url='https://double.finance/p/explore/150'
		heading Innovation Fund
	StaticText Speculation
	StaticText Maximum Growth
	[14490] paragraph, center=(1593,1060), inner_text=This strategy follows the ARKK fund (ticker ARKK) which was designed to seek long term capital from companies globally involved with, or that benefit from, disruptive innovation.
		StaticText This strategy follows the ARKK fund (ticker ARKK) which was designed to seek long term capital from companies globally involved with, or that benefit from, disruptive innovation.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Health Care
	paragraph
		StaticText Top Holdings
	image Tesla Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TSLA.png&w=96&q=75'
	image Roku Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ROKU.png&w=96&q=75'
	image Coinbase Global Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_COIN.png&w=96&q=75'
	image Roblox Corporation - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_RBLX.png&w=96&q=75'
	image Palantir Technologies Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PLTR.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +3.78%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 31
	paragraph
		StaticText Low
		StaticText risk
	paragraph
		image
		StaticText $3,000
	paragraph
		StaticText KRUZ
	link Republican Trading, url='https://double.finance/p/explore/246'
		heading Republican Trading
	StaticText Capital Preservation
	StaticText Balanced
	StaticText Income
	paragraph
		StaticText This strategy seeks to broadly invest in stocks purchased or sold by Republican members of the US Congress and their families.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Information Technology
	paragraph
		StaticText Top Holdings
	image JPMorgan Chase & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JPM.png&w=96&q=75'
	image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
	image Comfort Systems USA, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_FIX.png&w=96&q=75'
	image Simon Property Group, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_SPG.png&w=96&q=75'
	image AT&T, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_T.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +5.11%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 157
	paragraph
		StaticText Low
		StaticText risk
	paragraph
		image
		StaticText $5,000
	paragraph
		StaticText NANC
	link Democratic Trading, url='https://double.finance/p/explore/247'
		heading Democratic Trading
	StaticText Capital Preservation
	StaticText Balanced
	StaticText Income
	paragraph
		StaticText This strategy seeks to broadly invest in stocks purchased or sold by Democratic members of the US Congress and their families.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Information Technology
	paragraph
		StaticText Top Holdings
	image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
	image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
	image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
	image Salesforce Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CRM.png&w=96&q=75'
	image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +9.98%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 166
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link HedgeFundie's Excellent Adventure, url='https://double.finance/p/explore/110'
		heading HedgeFundie's Excellent Adventure
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		StaticText Famously posted on the
		link Bogleheads forum in 2019, url='https://www.bogleheads.org/forum/viewtopic.php?t=272007'
		StaticText , this risky strategy combining 3x leveraged etfs exposed to SPY and 20 year treasuries. It's only appropriate for users with very high risk tolerances and incurs relatively high ETF expense ratios
	paragraph
		StaticText ETF Based
		StaticText Strategy
	paragraph
		StaticText Top Holdings
	image ProShares Trust - ProShares UltraPro S&P 500 ETF 3x Shares logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9112114111115104971141011156.png&w=96&q=75'
	image Direxion Shares ETF Trust - Direxion Daily 20+ Year Treasury Bull 3X Shares logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F91001051141011201051111106.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText -1.16%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.97
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 2
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link Leveraged Tech, url='https://double.finance/p/explore/16'
		heading Leveraged Tech
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		StaticText This strategy allocates 70% to ProShares Ultra QQQ (QLD) for its 2x leveraged exposure to the Nasdaq-100. The additional leverage is a super-bullish bet on continued tech sector growth and innovation. The 30% Invesco QQQ (QQQ) provides core exposure to the tech sector while mitigating some of the risks associated with leveraged instruments.
	paragraph
		StaticText ETF Based
		StaticText Strategy
	paragraph
		StaticText Top Holdings
	image ProShares Trust - ProShares Ultra QQQ 2x Shares logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9112114111115104971141011156.png&w=96&q=75'
	image Invesco Capital Management LLC - Invesco QQQ Trust Series 1 logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105110118101115991116.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +25.77%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.72
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 2
	heading Sector Specific
	image
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $1,000
	paragraph
		StaticText SMH
	link Semiconductors Index, url='https://double.finance/p/explore/86'
		heading Semiconductors Index
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		StaticText This index tracks a market-cap-weighted index of 25 of the largest US-listed semiconductors companies.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Information Technology
	paragraph
		StaticText Top Holdings
	image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
	image Taiwan Semiconductor Manufacturing - ADR logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TSM.png&w=96&q=75'
	image Broadcom Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
	image ASML Holding NV - New York Shares logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ASML.png&w=96&q=75'
	image Advanced Micro Devices Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMD.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +29.73%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 25
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $2,200
	paragraph
		StaticText QQQ
	link Tech 100, url='https://double.finance/p/explore/26'
		heading Tech 100
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	paragraph
		StaticText This index is closely related to the Nasdaq-100 Index, comprising major tech and growth-oriented companies. It aims to capture the tech sector's long-term growth prospects through exposure to the innovative and leading tech companies listed on the Nasdaq exchange.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Information Technology
	paragraph
		StaticText Top Holdings
	image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
	image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
	image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
	image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
	image Broadcom Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +20.08%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 101
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $7,800
	paragraph
		StaticText VGT
	link Information Technology Sector, url='https://double.finance/p/explore/65'
		heading Information Technology Sector
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		StaticText This strategy concentrates on the technology sector, including companies involved in software, hardware, IT services, and semiconductor industries. It captures the growth potential of tech companies driving innovation and digital transformation, appealing to investors seeking exposure to this dynamic sector.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Information Technology
	paragraph
		StaticText Top Holdings
	image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
	image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
	image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
	image Broadcom Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
	image Salesforce Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CRM.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +21.83%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 288
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $14,000
	paragraph
		StaticText VFH
	link Financial Sector, url='https://double.finance/p/explore/63'
		heading Financial Sector
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		StaticText Double's Financial Sector Strategy invests in financial sector companies, including banks, insurance companies, and financial services firms. Providing exposure to the financial industry's performance, it plays a crucial role in diversified portfolios.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Financials
	paragraph
		StaticText Top Holdings
	image JPMorgan Chase & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JPM.png&w=96&q=75'
	image Berkshire Hathaway Inc. - Ordinary Shares - Class B logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BRK.B.png&w=96&q=75'
	image Mastercard Incorporated - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MA.png&w=96&q=75'
	image Visa Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_V.png&w=96&q=75'
	image Bank Of America Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BAC.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +12.17%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 371
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $9,300
	paragraph
		StaticText VCR
	link Consumer Discretionary Sector, url='https://double.finance/p/explore/59'
		heading Consumer Discretionary Sector
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		StaticText This strategy focuses on consumer discretionary companies, including retail, automotive, leisure, and entertainment firms. Reflecting consumer spending trends and economic conditions, it's sensitive to changes in consumer sentiment and economic growth.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Consumer Discretionary
	paragraph
		StaticText Top Holdings
	image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
	image Tesla Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TSLA.png&w=96&q=75'
	image Home Depot, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_HD.png&w=96&q=75'
	image McDonald`s Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MCD.png&w=96&q=75'
	image Booking Holdings Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BKNG.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +16.49%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 273
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $2,600
	paragraph
		StaticText VAW
	link Materials Sector, url='https://double.finance/p/explore/58'
		heading Materials Sector
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	paragraph
		StaticText This Strategy invests in materials sector companies, including chemicals, construction materials, metals, and mining firms. Providing exposure to global infrastructure development and manufacturing activities, it's positioned to benefit from economic growth and industrial demand.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Materials
	paragraph
		StaticText Top Holdings
	image Linde Plc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_LIN.png&w=96&q=75'
	image Sherwin-Williams Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_SHW.png&w=96&q=75'
	image Air Products & Chemicals Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_APD.png&w=96&q=75'
	image CRH Plc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CRH.png&w=96&q=75'
	image Ecolab, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ECL.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +9.67%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 110
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $3,400
	paragraph
		StaticText VOX
	link Communication Services, url='https://double.finance/p/explore/60'
		heading Communication Services
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		StaticText This strategy tracks the communication services sector, including companies involved in telecommunications, media, and internet services. Capturing trends in digital communication, entertainment, and connectivity, it reflects the evolving landscape of communication technologies.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Communication Services
	paragraph
		StaticText Top Holdings
	image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
	image Alphabet Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GOOGL.png&w=96&q=75'
	image Alphabet Inc - Ordinary Shares - Class C logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GOOG.png&w=96&q=75'
	image Netflix Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NFLX.png&w=96&q=75'
	image Walt Disney Co (The) logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DIS.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +11.38%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 108
	paragraph
		StaticText Low
		StaticText risk
	paragraph
		image
		StaticText $3,300
	paragraph
		StaticText VDC
	link Consumer Staples Sector, url='https://double.finance/p/explore/61'
		heading Consumer Staples Sector
	StaticText Capital Preservation
	StaticText Balanced
	StaticText Income
	paragraph
		StaticText This strategy focuses on consumer staples companies, including food, beverage, household products, and retail firms. Offering stability and defensive characteristics, it's often less sensitive to economic cycles.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Consumer Staples
	paragraph
		StaticText Top Holdings
	image Costco Wholesale Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_COST.png&w=96&q=75'
	image Walmart Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WMT.png&w=96&q=75'
	image Procter & Gamble Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PG.png&w=96&q=75'
	image Coca-Cola Co logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_KO.png&w=96&q=75'
	image Philip Morris International Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PM.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +8.56%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 100
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $14,000
	paragraph
		StaticText VHT
	link Health Care Sector, url='https://double.finance/p/explore/64'
		heading Health Care Sector
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	paragraph
		StaticText This Strategy focuses on healthcare companies, including pharmaceuticals, biotechnology, healthcare providers, and medical equipment firms. Offering exposure to a sector driven by demographic trends and ongoing medical advancements, it's a strategic choice for investors considering healthcare's long-term growth potential.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Health Care
	paragraph
		StaticText Top Holdings
	image Lilly(Eli) & Co logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_LLY.png&w=96&q=75'
	image Unitedhealth Group Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_UNH.png&w=96&q=75'
	image Abbvie Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ABBV.png&w=96&q=75'
	image Johnson & Johnson logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JNJ.png&w=96&q=75'
	image Merck & Co Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MRK.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +7.67%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 335
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $3,300
	paragraph
		StaticText VDE
	link Energy Sector, url='https://double.finance/p/explore/62'
		heading Energy Sector
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		StaticText This Strategy concentrate on the energy sector, including oil, gas, and renewable energy firms. Offering exposure to the global energy market, it can be influenced by factors such as oil prices, geopolitical events, and environmental policies.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Energy
	paragraph
		StaticText Top Holdings
	image Exxon Mobil Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_XOM.png&w=96&q=75'
	image Chevron Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CVX.png&w=96&q=75'
	image Conoco Phillips logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_COP.png&w=96&q=75'
	image EOG Resources, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_EOG.png&w=96&q=75'
	image Williams Cos Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WMB.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +13.67%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 104
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $3,700
	paragraph
		StaticText VNQ
	link Real Estate Sector, url='https://double.finance/p/explore/209'
		heading Real Estate Sector
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	paragraph
		StaticText This ETF follower concentrates primarily on real estate equity and is market-cap weighted for companies involved in the ownership and operation of real estate in the United States.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Real Estate
	paragraph
		StaticText Top Holdings
	image Prologis Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PLD.png&w=96&q=75'
	image Equinix Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_EQIX.png&w=96&q=75'
	image American Tower Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMT.png&w=96&q=75'
	image Welltower Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WELL.png&w=96&q=75'
	image Digital Realty Trust Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DLR.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +3.15%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 153
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $1,000
	paragraph
		StaticText WCLD
	link Cloud Computing, url='https://double.finance/p/explore/245'
		heading Cloud Computing
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		StaticText This strategy tracks US companies primarily focused on cloud software and services. Stocks are equal weighted in the index.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Information Technology
	paragraph
		StaticText Top Holdings
	image Twilio Inc - Ordinary Shares Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TWLO.png&w=96&q=75'
	image BILL Holdings Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BILL.png&w=96&q=75'
	image DocuSign Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DOCU.png&w=96&q=75'
	image Atlassian Corporation - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TEAM.png&w=96&q=75'
	image AvePoint Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVPT.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +9.90%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 63
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $1,700
	paragraph
		StaticText XLF
	link Select US Financial Sector, url='https://double.finance/p/explore/373'
		heading Select US Financial Sector
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		StaticText Tracking select top holdings in US financial sector focusing on the top performers.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Financials
	paragraph
		StaticText Top Holdings
	image Berkshire Hathaway Inc. - Ordinary Shares - Class B logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BRK.B.png&w=96&q=75'
	image JPMorgan Chase & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JPM.png&w=96&q=75'
	image Visa Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_V.png&w=96&q=75'
	image Mastercard Incorporated - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MA.png&w=96&q=75'
	image Bank Of America Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BAC.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +11.81%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 73
	heading Factor Specific
	image
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $1,400
	paragraph
		StaticText DYNF
	link U.S. Equity Factor Rotation, url='https://double.finance/p/explore/134'
		heading U.S. Equity Factor Rotation
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	paragraph
		StaticText Optimizes returns by rotating investments across five historically successful styles: quality, value, size, minimum volatility, and momentum. By shifting focus among these factors based on forward-looking insights, this index capitalizes on market opportunities and provides a diversified approach to enhancing returns. This strategy offers a flexible and adaptive way to navigate changing markets, combining multiple styles in a single portfolio to maximize returns while managing risk.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Information Technology
	paragraph
		StaticText Top Holdings
	image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
	image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
	image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
	image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
	image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +15.98%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 82
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $5,500
	paragraph
		StaticText VUG
	link Growth Stocks, url='https://double.finance/p/explore/68'
		heading Growth Stocks
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	paragraph
		StaticText Growth Stocks focuses on companies with strong growth prospects, often found in sectors driving innovation and technological advancement. This ETF invests in companies demonstrating robust revenue and earnings growth, including technology giants, healthcare innovators, and consumer discretionary leaders.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Information Technology
	paragraph
		StaticText Top Holdings
	image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
	image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
	image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
	image Amazon.com Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMZN.png&w=96&q=75'
	image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +18.30%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 181
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $6,600
	paragraph
		StaticText VTV
	link Value Stocks, url='https://double.finance/p/explore/67'
		heading Value Stocks
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	paragraph
		StaticText This Strategy targets undervalued stocks in the U.S. market, emphasizing companies with solid fundamentals and potential for long-term growth. Emphasizing sectors such as healthcare, financials, industrials, and consumer goods, it seeks opportunities where market prices may not fully reflect underlying value metrics like earnings and book value.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Financials
	paragraph
		StaticText Top Holdings
	image JPMorgan Chase & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JPM.png&w=96&q=75'
	image Berkshire Hathaway Inc. - Ordinary Shares - Class B logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BRK.B.png&w=96&q=75'
	image Broadcom Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
	image Exxon Mobil Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_XOM.png&w=96&q=75'
	image Unitedhealth Group Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_UNH.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +10.46%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 331
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $2,700
	paragraph
		StaticText MTUM
	link U.S. Momentum Factor, url='https://double.finance/p/explore/124'
		heading U.S. Momentum Factor
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	paragraph
		StaticText Tracks an index of large- and mid-cap US equities, selected and weighted based on historical price appreciation and low volatility. Focus is on stocks with strong 6- and 12-month price performance, while also considering volatility over the past 3 years. This approach aims to capture momentum while managing risk, providing a unique investment strategy for those seeking growth potential.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Information Technology
	paragraph
		StaticText Top Holdings
	image Broadcom Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AVGO.png&w=96&q=75'
	image JPMorgan Chase & Co. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JPM.png&w=96&q=75'
	image Walmart Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WMT.png&w=96&q=75'
	image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
	image Costco Wholesale Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_COST.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +13.42%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 123
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link Mid & Large Cap Dividend Yield, url='https://double.finance/p/explore/139'
		heading Mid & Large Cap Dividend Yield
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	paragraph
		StaticText These mid and large cap companies all have above a 3% dividend yield and are equally weighted.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Utilities
	paragraph
		StaticText Top Holdings
	image PNC Financial Services Group Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PNC.png&w=96&q=75'
	image Chevron Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CVX.png&w=96&q=75'
	image PPL Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PPL.png&w=96&q=75'
	image Prudential Financial Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PRU.png&w=96&q=75'
	image Target Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TGT.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +10.51%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 95
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $3,100
	paragraph
		StaticText QUAL
	link USA Quality Factor, url='https://double.finance/p/explore/356'
		heading USA Quality Factor
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	paragraph
		StaticText This strategy invests in US large- and mid-cap stocks with a focus on financial quality. Companies are selected and weighted based on their return on equity, earnings growth stability, and financial leverage, emphasizing strong fundamentals. This approach offers investors exposure to companies with proven profitability and sound financial health.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Information Technology
	paragraph
		StaticText Top Holdings
	image Apple Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AAPL.png&w=96&q=75'
	image Microsoft Corporation logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSFT.png&w=96&q=75'
	image NVIDIA Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVDA.png&w=96&q=75'
	image Visa Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_V.png&w=96&q=75'
	image Mastercard Incorporated - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MA.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +13.82%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 124
	paragraph
		StaticText risk
	paragraph
		image
		StaticText $1,700
	paragraph
		StaticText MGK
	link Mega Cap Growth Stocks, url='https://double.finance/p/explore/645'
		heading Mega Cap Growth Stocks
	paragraph
		StaticText Mega Cap Growth Stocks focuses on companies with strong growth prospects, often found in sectors driving innovation and technological advancement. This ETF following strategy invests in mega cap companies demonstrating robust revenue and earnings growth, including technology giants, healthcare innovators, and consumer discretionary leaders.
	paragraph
		StaticText ETF Based
		StaticText Strategy
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	image
	paragraph
		StaticText 71
	heading Smart Screens
	image
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $1,200
	link Growth at a Fair Price, url='https://double.finance/p/explore/136'
		heading Growth at a Fair Price
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		StaticText These stocks above $1B in Market Cap are modestly valued (PE below 15) but are in the top 20% of stocks for revenue growth over the past 5 years. We weight them by market cap.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Health Care
	paragraph
		StaticText Top Holdings
	image HubSpot Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_HUBS.png&w=96&q=75'
	image Lemonade Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_LMND.png&w=96&q=75'
	image Flutter Entertainment Plc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_FLUT.png&w=96&q=75'
	image Armada Hoffler Properties Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AHH.png&w=96&q=75'
	image First Citizens Bancshares, Inc (NC) - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_FCNCA.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +23.94%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 235
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link The Top 20% Club, url='https://double.finance/p/explore/138'
		heading The Top 20% Club
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	paragraph
		StaticText This group of select stocks has achieved top 20% ratings in 1 year Revenue Growth, Free Cash Flow Per Share and 5 Year Return on Invested Capital. This select group of stocks is equally weighted to prevent any mega caps from dominating this Strategy.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Financials
	paragraph
		StaticText Top Holdings
	image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
	image F&G Annuities & Life Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_FG.png&w=96&q=75'
	image Mesabi Trust logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MSB.png&w=96&q=75'
	image Jackson Financial Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_JXN.png&w=96&q=75'
	image Wingstop Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WING.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +31.81%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 22
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link Dividend Kings with Cash, url='https://double.finance/p/explore/137'
		heading Dividend Kings with Cash
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		StaticText These stocks have a strong dividend yield 5% yearly, and also are in the top 40% of all stocks with regards to cash on hand, meaning they have a strong balance sheet to finance those future dividend payments. We weight these stocks equally.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Financials
	paragraph
		StaticText Top Holdings
	image Newell Brands Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NWL.png&w=96&q=75'
	image Whirlpool Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_WHR.png&w=96&q=75'
	image MPLX LP - Unit logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_MPLX.png&w=96&q=75'
	image Icahn Enterprises L P - Unit logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_IEP.png&w=96&q=75'
	image Two Harbors Investment Corp logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_TWO.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +5.72%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 71
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link Growing Small Caps, url='https://double.finance/p/explore/154'
		heading Growing Small Caps
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		StaticText These small cap companies ($250M to $2B) are growing Revenue and Earnings at a nice clip. Equally weighted.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Financials
	paragraph
		StaticText Top Holdings
	image Consolidated Water Co. Ltd. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CWCO.png&w=96&q=75'
	image EyePoint Pharmaceuticals Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_EYPT.png&w=96&q=75'
	image Accolade Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ACCD.png&w=96&q=75'
	image Aurinia Pharmaceuticals Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AUPH.png&w=96&q=75'
	image Graham Corp. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_GHM.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +18.28%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 80
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $1,900
	link Highly Efficient & Growing, url='https://double.finance/p/explore/357'
		heading Highly Efficient & Growing
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	paragraph
		StaticText These stocks are highly efficient, with a Return on Invested Capital > 20%, while also growing earnings > 20% over the last 3 years. We exclude any stock with market cap above $1T, and weight the rest by Market Cap.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Information Technology
	paragraph
		StaticText Top Holdings
	image Novo Nordisk - ADR logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_NVO.png&w=96&q=75'
	image ASML Holding NV - New York Shares logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ASML.png&w=96&q=75'
	image Booking Holdings Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_BKNG.png&w=96&q=75'
	image Arista Networks Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_ANET.png&w=96&q=75'
	image Regeneron Pharmaceuticals, Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_REGN.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +19.43%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 71
	heading Battle of the VCs
	image
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link Founder Mode, url='https://double.finance/p/explore/175'
		heading Founder Mode
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		StaticText Stocks only get included in this basket, if the companies founders are still actively involved in the company. We equally weight them. Paul Graham talks a bit about
		link Founder Mode, url='https://paulgraham.com/foundermode.html'
		StaticText in a recent 2024 essay.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Information Technology
	paragraph
		StaticText Top Holdings
	image American Homes 4 Rent - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMH.png&w=96&q=75'
	image Skechers U S A, Inc. - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_SKX.png&w=96&q=75'
	image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
	image Zillow Group Inc - Ordinary Shares - Class C logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_Z.png&w=96&q=75'
	image Procore Technologies Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PCOR.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +22.20%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 92
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link YC Public Companies, url='https://double.finance/p/explore/140'
		heading YC Public Companies
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		StaticText Like Double, all of these companies have been backed by
		link YCombinator, url='https://www.ycombinator.com/'
		StaticText . YC is the worlds most successful startup incubator started by Paul Graham, Jessica Livingston, Robert Morris and Trevor Blackwell in 2005.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Information Technology
	paragraph
		StaticText Top Holdings
	image Reddit Inc. - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_RDDT.png&w=96&q=75'
	image Dropbox Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_DBX.png&w=96&q=75'
	image Amplitude Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AMPL.png&w=96&q=75'
	image Maplebear Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CART.png&w=96&q=75'
	image Pagerduty Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PD.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +14.62%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 10
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link Sequoia Capital Investments, url='https://double.finance/p/explore/141'
		heading Sequoia Capital Investments
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		link Sequoia Capital, url='https://www.sequoiacap.com/'
		StaticText is considered by many to be the worlds best venture capital firm. This Strategy comprises of all the eligible stocks that they've invested in. We've equally weighted the strategy.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Information Technology
	paragraph
		StaticText Top Holdings
	image HubSpot Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_HUBS.png&w=96&q=75'
	image Unity Software Inc logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_U.png&w=96&q=75'
	image Reddit Inc. - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_RDDT.png&w=96&q=75'
	image Okta Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_OKTA.png&w=96&q=75'
	image Confluent Inc - Ordinary Shares Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CFLT.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +16.32%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 33
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link a16z Investments, url='https://double.finance/p/explore/149'
		heading a16z Investments
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		link Andreessen Horowitz, url='https://a16z.com/'
		StaticText , known as a16z, is a venture capital firm started by Mark Andreessen and Ben Horowitz. It is the largest VC firm measure by assets under management with $42B as of late 2024.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Communication Services
	paragraph
		StaticText Top Holdings
	image Meta Platforms Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_META.png&w=96&q=75'
	image Okta Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_OKTA.png&w=96&q=75'
	image Lyft Inc - Ordinary Shares Cls A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_LYFT.png&w=96&q=75'
	image Pinterest Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_PINS.png&w=96&q=75'
	image Maplebear Inc. logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_CART.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +14.68%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 10
	paragraph
		StaticText High
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link Khosla Ventures, url='https://double.finance/p/explore/155'
		heading Khosla Ventures
	StaticText Speculation
	StaticText Maximum Growth
	paragraph
		link Khosla Ventures, url='https://www.khoslaventures.com/'
		StaticText is an American venture capital firm founded by Vinod Khosla, focused on early-stage companies. Vinod co-founded Sun Microsystems.
	paragraph
		StaticText Top Sector
	paragraph
		StaticText Financials
	paragraph
		StaticText Top Holdings
	image Okta Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_OKTA.png&w=96&q=75'
	image Oscar Health Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_OSCR.png&w=96&q=75'
	image Affirm Holdings Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_AFRM.png&w=96&q=75'
	image QuantumScape Corp - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_QS.png&w=96&q=75'
	image Block Inc - Ordinary Shares - Class A logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fdouble-prod-company-logos.s3.amazonaws.com%2Fcompany_logo_SQ.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +16.13%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.00
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 13
	heading Boglehead Portfolios
	image
	paragraph
		StaticText Low
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link Diverse Bond Portfolio, url='https://double.finance/p/explore/198'
		heading Diverse Bond Portfolio
	StaticText Capital Preservation
	StaticText Balanced
	StaticText Income
	paragraph
		StaticText For investors seeking lower risk than equities and those nearing retirement, bonds offer a compelling investment option for the upcoming years. We've curated a diverse portfolio of six popular bond ETFs, carefully allocating 60% to short-term Treasuries, 30% to corporate bonds, 8% to floating-rate bonds, and 2% to long-term Treasuries.
	paragraph
		StaticText ETF Based
		StaticText Strategy
	paragraph
		StaticText Top Holdings
	image Schwab Strategic Trust - Schwab Short-Term U.S. Treasury ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F91159910411997986.png&w=96&q=75'
	image BlackRock Institutional Trust Company N.A. - iShares Short Treasury Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
	image BlackRock Institutional Trust Company N.A. - iShares 0-5 Year High Yield Corporate Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
	image BlackRock Institutional Trust Company N.A. - iShares Broad USD High Yield Corporate Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
	image SPDR Series Trust - SPDR Bloomberg Investment Grade Floating Rate ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9115112100114451159711010011253484845101116102451161146.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +2.48%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.13
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 6
	paragraph
		StaticText Low
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link Ray Dalio's All Weather, url='https://double.finance/p/explore/108'
		heading Ray Dalio's All Weather
	StaticText Capital Preservation
	StaticText Balanced
	StaticText Income
	paragraph
		StaticText Ray Dalio is a legendary investor, and this Strategy is a simplified version of techniques he's used at his famous hedge fund Bridgewater Associates. It combines 5 asset classes using ETFs, with a 55% allocation to fixed income. It's appropriate for investors with a balance approach to risk and return. Learn more about it
		link here, url='https://www.lazyportfolioetf.com/allocation/ray-dalio-all-weather/'
	paragraph
		StaticText ETF Based
		StaticText Strategy
	paragraph
		StaticText Top Holdings
	image BlackRock Institutional Trust Company N.A. - iShares 20+ Year Treasury Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Total Stock Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image BlackRock Institutional Trust Company N.A. - iShares 3-7 Year Treasury Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
	image DB Commodity Services LLC - Invesco DB Commodity Index Tracking Fund logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105110118101115991116.png&w=96&q=75'
	image SPDR Gold Trust - SPDR Gold Shares ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9115112100114451159711010011253484845101116102451161146.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +3.29%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.19
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 5
	paragraph
		StaticText Low
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link The Coward's Portfolio, url='https://double.finance/p/explore/119'
		heading The Coward's Portfolio
	StaticText Capital Preservation
	StaticText Balanced
	StaticText Income
	paragraph
		StaticText William Bernstein created this portfolio and is the author of several books including
		link The Intelligent Asset Allocator, url='https://www.amazon.com/dp/0071362363'
		StaticText and
		link The Four Pillars of Investing, url='https://www.amazon.com/dp/0071747052/'
		StaticText . He introduced the Coward's Portfolio in 1996. The "coward" refers not to risk tolerance but to the strategy of hedging your bets and having slices of a number of asset classes.
	paragraph
		StaticText ETF Based
		StaticText Strategy
	paragraph
		StaticText Top Holdings
	image Vanguard Group, Inc. - Vanguard Short-Term Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Total Stock Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Small Cap Value ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Value ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard FTSE Pacific ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +6.09%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.05
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 9
	paragraph
		StaticText Low
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link Armstrong's "Ideal Index", url='https://double.finance/p/explore/120'
		heading Armstrong's "Ideal Index"
	StaticText Capital Preservation
	StaticText Balanced
	StaticText Income
	paragraph
		StaticText Frank Armstrong, author of
		link The Informed Investor, url='https://www.amazon.com/dp/0814472508/'
		StaticText , proposed this portfolio. Compared to other Boglehead portfolios, it contains a smaller allocation to bonds, and a much larger allocation to international stocks (in fact the equities, excluding REIT, are split 50/50 between domestic and international).
	paragraph
		StaticText ETF Based
		StaticText Strategy
	paragraph
		StaticText Top Holdings
	image Vanguard Group, Inc. - Vanguard Total International Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Short-Term Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Value ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Small Cap Value ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Real Estate Index Fund ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +5.65%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.06
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 7
	paragraph
		StaticText Low
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link David Swensen's Lazy Portfolio, url='https://double.finance/p/explore/121'
		heading David Swensen's Lazy Portfolio
	StaticText Capital Preservation
	StaticText Balanced
	StaticText Income
	paragraph
		StaticText David Swensen is CIO of Yale University and author of
		link Unconventional Success, url='https://www.simonandschuster.com/books/Unconventional-Success/David-F-Swensen/9780743228381'
		StaticText . His lazy portfolio uses low-cost, tax-efficient total market funds, a healthy dose of real estate, and
		link inflation-protected securities (TIPS), url='https://www.bogleheads.org/wiki/Treasury_Inflation_Protected_Security'
		StaticText .
	paragraph
		StaticText ETF Based
		StaticText Strategy
	paragraph
		StaticText Top Holdings
	image Vanguard Group, Inc. - Vanguard Total Stock Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image BlackRock Institutional Trust Company N.A. - iShares TIPS Bond ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard FTSE Developed Markets ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Intermediate-Term Treasury ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Real Estate Index Fund ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +6.01%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.08
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 6
	paragraph
		StaticText Low
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link Bill Schultheis's "Coffeehouse", url='https://double.finance/p/explore/118'
		heading Bill Schultheis's "Coffeehouse"
	StaticText Capital Preservation
	StaticText Balanced
	StaticText Income
	paragraph
		StaticText Bill Schultheis made this simple seven-fund portfolio popular in his book
		link The Coffeehouse Investor, url='https://www.amazon.com/dp/0976585707/'
		StaticText . He advocates 40% in a total market bond fund and 10% each in various stock funds. You can find more information at
		link The Coffeehouse Investor, url='https://coffeehouseinvestor.com/'
		StaticText .
	paragraph
		StaticText ETF Based
		StaticText Strategy
	paragraph
		StaticText Top Holdings
	image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Small Cap ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Small Cap Value ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Real Estate Index Fund ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard S&P 500 ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +5.32%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.05
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 7
	paragraph
		StaticText Low
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link The Permanent Portfolio, url='https://double.finance/p/explore/122'
		heading The Permanent Portfolio
	StaticText Capital Preservation
	StaticText Balanced
	StaticText Income
	paragraph
		StaticText Free-market investment analyst Harry Browne devised the Permanent Portfolio in the 1980s, as a buy-and-hold portfolio that contains a healthy allocation to gold. The portfolio holds equal allocations of domestic stocks, gold, short-term treasury bonds, and long term treasury bonds. Boglehead members Craig Rowland and J. M. Lawson have written a book,
		link The Permanent Portfolio: Harry Browne's Long-Term Investment Strategy, url='https://www.amazon.com/Permanent-Portfolio-Long-Term-Investment-Strategy/dp/1118288254'
		StaticText , detailing every aspect of the Permanent Portfolio.
	paragraph
		StaticText ETF Based
		StaticText Strategy
	paragraph
		StaticText Top Holdings
	image BlackRock Institutional Trust Company N.A. - iShares Gold Trust logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F9105115104971141011156.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Long-Term Treasury ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Short-Term Treasury ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Total Stock Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +5.32%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.09
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 4
	paragraph
		StaticText Low
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link Two Fund Portfolio, url='https://double.finance/p/explore/116'
		heading Two Fund Portfolio
	StaticText Capital Preservation
	StaticText Balanced
	StaticText Income
	paragraph
		StaticText You can invest in broad US and International markets, as well as bonds, using only two funds.
	paragraph
		StaticText ETF Based
		StaticText Strategy
	paragraph
		StaticText Top Holdings
	image Vanguard Group, Inc. - Vanguard Total World Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +5.90%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.05
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 2
	paragraph
		StaticText Low
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link Core 4 Portfolio, url='https://double.finance/p/explore/117'
		heading Core 4 Portfolio
	StaticText Capital Preservation
	StaticText Balanced
	StaticText Income
	paragraph
		StaticText By including some direct exposure to the US Real Estate market directly through VNQ, this fund adds a bit more diversity compared to the Majesty of Simplicity.
	paragraph
		StaticText ETF Based
		StaticText Strategy
	paragraph
		StaticText Top Holdings
	image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Total Stock Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Total International Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Real Estate Index Fund ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +5.35%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.05
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 4
	paragraph
		StaticText Low
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link Majesty of Simplicity - Mod, url='https://double.finance/p/explore/105'
		heading Majesty of Simplicity - Mod
	StaticText Capital Preservation
	StaticText Balanced
	StaticText Income
	paragraph
		StaticText John Bogle started Vanguard and revolutionized the investment world, and this three fund portfolio was called name "The Majesty of Simplicity" by Bogle himself. It uses three ETFs - a Bond ETF a US Domestic Stock ETF and a Foreign Stock ETF - to construct a well diversified portfolio in a dead simple manner.
	paragraph
		StaticText ETF Based
		StaticText Strategy
	paragraph
		StaticText Top Holdings
	image Vanguard Group, Inc. - Vanguard S&P 500 ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Total International Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +7.11%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.04
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 3
	paragraph
		StaticText Medium
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link Majesty of Simplicity - Agg, url='https://double.finance/p/explore/104'
		heading Majesty of Simplicity - Agg
	StaticText Growth
	StaticText Balanced
	StaticText Growth Income
	paragraph
		StaticText John Bogle started Vanguard and revolutionized the investment world, and this three fund portfolio was called name "The Majesty of Simplicity" by Bogle himself. It uses three ETFs - a Bond ETF a US Domestic Stock ETF and a Foreign Stock ETF - to construct a well diversified portfolio in a dead simple manner.
	paragraph
		StaticText ETF Based
		StaticText Strategy
	paragraph
		StaticText Top Holdings
	image Vanguard Group, Inc. - Vanguard S&P 500 ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Total International Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +10.82%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.04
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 3
	paragraph
		StaticText Low
		StaticText risk
	paragraph
		image
		StaticText $1,000
	link Majesty of Simplicity - Con, url='https://double.finance/p/explore/106'
		heading Majesty of Simplicity - Con
	StaticText Capital Preservation
	StaticText Balanced
	StaticText Income
	paragraph
		StaticText John Bogle started Vanguard and revolutionized the investment world, and this three fund portfolio was called name "The Majesty of Simplicity" by Bogle himself. It uses three ETFs - a Bond ETF a US Domestic Stock ETF and a Foreign Stock ETF - to construct a well diversified portfolio in a dead simple manner.
	paragraph
		StaticText ETF Based
		StaticText Strategy
	paragraph
		StaticText Top Holdings
	image Vanguard Group, Inc. - Vanguard Total Bond Market ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard S&P 500 ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	image Vanguard Group, Inc. - Vanguard Total International Stock ETF logo, url='https://double.finance/_next/image?url=https%3A%2F%2Fstatic2.finnhub.io%2Ffile%2Fpublicdatany%2Ffinnhubimage%2Fetf_logo%2F911897110103117971141006.png&w=96&q=75'
	paragraph
		StaticText Return
	image
	image
	StaticText +3.16%
	paragraph
		StaticText Expense Ratio
	image
	paragraph
		StaticText 0.04
		StaticText %
	paragraph
		StaticText Holdings
	paragraph
		StaticText 3
	heading Got a Question?
	paragraph
		StaticText Check out our frequently asked questions or reach out to our team
	link Take me to FAQ, url='https://help.double.finance/en/'
		button Take me to FAQ
	link Contact Us, url='mailto:support@double.finance'
		button Contact Us
	image, url='https://double.finance/_next/image?url=%2F_next%2Fstatic%2Fmedia%2F3dlogo.eb0bd619.png&w=640&q=75'
	heading Didn't find something?
	paragraph
		StaticText Build your own strategy from scratch by selecting from 1000s of stocks and ETFs.
	link Create your own, url='https://double.finance/sign-up?redirect=/research'
		button Create your own
	image, url='https://double.finance/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FstrategiesGrouped.45478398.png&w=640&q=75'
	contentinfo
		image
		heading Zero expense ratio index investing
		heading Company
		list
			listitem
				link Disclosures, url='https://double.finance/disclosures'
			listitem
				link LinkedIn, url='https://www.linkedin.com/company/doublefinance/'
			listitem
				link X, url='https://x.com/Double_Finance'
		heading Resources
		list
			listitem
				link Blog, url='https://double.finance/blog'
			listitem
				link Learn, url='https://double.finance/learn'
			listitem
				link Fee Calculator, url='https://double.finance/tools/fee-calculator'
			listitem
				link Tax Bracket Estimator, url='https://double.finance/tools/tax-bracket-estimator'
		heading Popular ETFs
		list
			listitem
				link SPY, url='https://double.finance/p/stock/SPY'
			listitem
				link VOO, url='https://double.finance/p/stock/VOO'
			listitem
				link VTI, url='https://double.finance/p/stock/VTI'
			listitem
				link CALF, url='https://double.finance/p/stock/CALF'
			listitem
				link AVUV, url='https://double.finance/p/stock/AVUV'
			listitem
				link SGOV, url='https://double.finance/p/stock/SGOV'
			listitem
				link COWZ, url='https://double.finance/p/stock/COWZ'
			listitem
				link SMH, url='https://double.finance/p/stock/SMH'
			listitem
				link QQQ, url='https://double.finance/p/stock/QQQ'
			listitem
				link TLT, url='https://double.finance/p/stock/TLT'
			listitem
				link VGT, url='https://double.finance/p/stock/VGT'
			listitem
				link SCHD, url='https://double.finance/p/stock/SCHD'
		heading ETF Comparisons
		list
			listitem
				link AVDE vs CGDG, url='https://double.finance/p/stock/AVDE/CGDG'
			listitem
				link QQQ vs SPY, url='https://double.finance/p/stock/QQQ/SPY'
			listitem
				link QQQ vs VOO, url='https://double.finance/p/stock/QQQ/VOO'
			listitem
				link MDYG vs SCHM, url='https://double.finance/p/stock/MDYG/SCHM'
			listitem
				link SCHD vs VIG, url='https://double.finance/p/stock/SCHD/VIG'
			listitem
				link VOO vs VUG, url='https://double.finance/p/stock/VOO/VUG'
		generic, hasPopup='dialog'
			StaticText Terms of Service
		generic, hasPopup='dialog'
			StaticText Privacy Policy
		paragraph
			StaticText © Double Finance, 2024
		StaticText Double is a registered investment adviser with the US Securities and Exchange Commission (SEC). While such registration does not imply a certain level of skill, it does require us to follow federal regulations that protect you, the investor. By law, we must provide investment advice that is in the best interest of our client. Please refer to Double's
		link Form CRS, url='https://double-prod-disclosures.s3.amazonaws.com/crs_329617.pdf'
		StaticText for important additional information.
		StaticText The publicly available portions of the Platform (i.e., the sections of the Platform that are available to individuals who are not party to a Client Agreement - including double.finance) are provided for educational purposes only and are not intended to provide legal, tax, or financial planning advice. To the extent that any of the content published on publicly available portions of the Platform may be deemed to be investment advice, such information is impersonal and not tailored to the investment needs of any specific person. Nothing on the publicly available portions of the Platform should be construed as a solicitation or offer, or recommendation, to buy or sell any security. All charts, figures, and graphs on the publicly available websites are for illustrative purposes only. Before investing, you should consider whether any investment, investment strategy, security, other asset, or related transaction is appropriate for you based on your personal investment objectives, financial circumstances, and risk tolerance. You are also encouraged to consult your legal, tax, or investment professional regarding your specific situation. Registration does not imply a certain level of skill or training.
		StaticText Investing involves risk. The value of your investment will fluctuate, and you may gain or lose money.
		StaticText The contents of the Platform may contain forward-looking statements that are based on management's beliefs, assumptions, current expectations, estimates, and projections about the financial industry, the economy, or Global Predictions itself. Forward-looking statements are not guarantees of the underlying expected actions or future performance and future results may differ significantly from those anticipated by the forward-looking statements. Therefore, actual results and outcomes may materially differ from what may be expressed or forecasted in such forward-looking statements.
		StaticText ¹ Data as of July 2024.
		StaticText ² Availability of tax loss harvesting depends on portfolio diversity.
		StaticText ³ As of November 8, 2024. The optional Cash Sweep program takes the cash sitting in your brokerage account and moves it to an FDIC-insured interest-earning deposit account. The current yield is 1.0%, rates subject to change at any time. The cash sweep program is made available in coordination with Apex Clearing Corporation. Please read the
		link Important Disclosures, url='https://double-disclosures.s3.amazonaws.com/Apex-FDIC-Sweep-Program-Terms-and-Conditions-1.pdf'
		StaticText for more information.
		StaticText ⁴ This analysis calculator tool is for illustrative purposes only and is not financial advice. We do not guarantee the accuracy of the results or their relevance to your particular circumstances. This calculator uses hypothetical historical data and does not take into account the effect of taxes on a taxable account. Hypothetical historical data is no guarantee of future performance and this calculator is not intended to predict actual performance. The input of different time periods, amounts, and fees will vary calculator results. Average ETF fee is based on the AUM weighted average of US ETFs as of September 2024,
		link see more information, url='https://www.etf.com/topics/sp-500'
		StaticText . Note that you can purchase ETFs through Double, which may incur additional fees.
		StaticText Full pricing details along with an FAQ can be found
		link here, url='https://double.finance/pricing'
		StaticText Data displayed in charts and graphics above are for illustrative purposes only and do not reflect actual investment results and are not a guarantee of future results.
		StaticText By using double.finance, you accept our
		generic, hasPopup='dialog'
			StaticText Terms of Use
		StaticText and
		generic, hasPopup='dialog'
			StaticText Privacy Policy
		StaticText . Double is only available to US residents.
		StaticText See Double Finance
		link Form ADV Part IIA, url='https://double-disclosures.s3.amazonaws.com/Double+Finance+ADV+Part+IIA.pdf'
		StaticText for additional information. Double does not guarantee that the results of its advice, recommendations, or the objectives of its direct index or cash management strategies will be achieved. We make no assurance that the investment process will consistently lead to successful investing. Before you invest, you should carefully review and consider your investment objectives as well as the risks, charges, and expenses of the underlying securities. There is at least a $1,000 account minimum required to participate in Double's strategies, although some strategies may have higher minimums.
		StaticText Double does not provide tax, or legal advice. Double's website, brokerage, and advisory services are not intended for persons of any jurisdiction where Double is not authorized to do business. Tax savings will vary from client to client due to many factors including market conditions, tax characteristics of securities, client-imposed investment restrictions, client tax rate or status, and changes in tax regulations.
	alert, atomic
		StaticText Direct Indexing | Discover Direct Indexing, ETFs & Vehicles For You | Double Finance
```
</details>

**Reasoning for action:** I chose to click the 'Submit' button (identified as '14475') because this action is necessary to confirm the user's selection of 'High' risk tolerance. By taking this step, I am signaling the system to retrieve the relevant investment strategies that align with the specified risk preference. This directly moves us closer to fulfilling the user's goal of exploring index investment strategies categorized by their risk levels.

**Action:** click('14475') # Click on the 'Submit' button to proceed with the selected risk tolerance.

**Change Description:** After clicking the 'Submit' button to proceed with the selected risk tolerance, the browser state changed from a modal dialog prompting for risk tolerance options to the main interface that features various investment strategies, risk categories, and information about selected strategies, effectively transitioning the user to the next step in the investment process.

**Screenshot before:****Screenshot after:**---


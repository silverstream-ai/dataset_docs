# Task

**User Story for Wallet Connection**

As a cryptocurrency user,
I connect my Rainbow wallet to the Instant Bridge,
so that I can seamlessly initiate cross-chain transactions without manually managing any token swaps.

**Success definition:** Given I am on the Instant Bridge page and have chosen to connect my wallet
When I select the Rainbow wallet option from the wallet connection modal
Then I should see a QR code for connecting my Rainbow wallet and instructions to complete the connection.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://paywithglide.xyz/

https://bridge.paywithglide.xyz/ethereum-to-base

**Content (before/after):** 

```
RootWebArea Glide - Instant, low-cost cross-chain transactions, focused, url='https://paywithglide.xyz/'
	image
	[26] link Instant Bridge, center=(1300,100), url='https://bridge.paywithglide.xyz/'
	[27] link Documentation, center=(1442,100), url='https://docs.paywithglide.xyz/installation'
	image
```
<details><summary>Show more</summary>

```
	image
	image
	image
	image
	image
	image
	StaticText Build delightful
	StaticText onchain transaction
	StaticText experiences
	StaticText Simple APIs to enable cross-chain, gasless, fiat transactions, and more, in your dapp or wallet.
	[55] textbox Telegram handle or email, center=(899,438), contenteditable=True
	[57] button Get access, center=(1076,438), type=submit
	[59] link Check out our integration docs here, center=(960,488), url='https://docs.paywithglide.xyz/installation'
	image Base Name Service Logo, url='data:image/webp;base64,UklGRkgrAABXRUJQVlA4IDwrAABwrgOdASrQB9AHPpFIpEylpKQiILJYCLASCWlu/HA5/p6nfXxkufkv+9doX+E/tPpj1bfZ/j6ROPjf3d/h+aveTwAvxL+if63eJwAfVj/j+GbqTeHPYA4D70L2AP076BP1L55f0X/W+wt+wfpLewb9wP//7rH7gANo5PBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5YBrqb3EXlgGupvcReWAa6m9xF5Y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ywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA11N7iLywDXU3uIvLANdTe4i8sA1'
	image
	image
	image Zora Logo, url='data:image/webp;base64,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'
	image
	image
	image
	StaticText POWERING YOUR FAVORITE WEB3 APPS
	image Base Colors, url='https://paywithglide.xyz/static/base_colors.svg'
	image Payflow, url='https://paywithglide.xyz/static/payflow.svg'
	image Base Name Service, url='https://paywithglide.xyz/static/basename.svg'
	image Hypersub, url='https://paywithglide.xyz/static/fabric.svg'
	image Sticker.wtf, url='https://paywithglide.xyz/static/stickerwtf.svg'
	image Caststorage, url='https://paywithglide.xyz/static/caststorage.svg'
	image Herocast, url='https://paywithglide.xyz/static/herocast.svg'
	image Base Colors, url='https://paywithglide.xyz/static/base_colors.svg'
	image Payflow, url='https://paywithglide.xyz/static/payflow.svg'
	image Base Name Service, url='https://paywithglide.xyz/static/basename.svg'
	image Hypersub, url='https://paywithglide.xyz/static/fabric.svg'
	image Sticker.wtf, url='https://paywithglide.xyz/static/stickerwtf.svg'
	image Caststorage, url='https://paywithglide.xyz/static/caststorage.svg'
	image Herocast, url='https://paywithglide.xyz/static/herocast.svg'
	StaticText Instant, low-cost
	StaticText cross-chain transactions
	StaticText Let your users pay for transactions with tokens they already have on any chain without the need to swap or bridge.
	StaticText Try the demo by subscribing to a creator on Hypersub. Even though the smart contract requires ETH on Base, you will be able to pay for the transaction with any token you hold in your wallet.
	image Surfing Dog, url='https://storage.withfabric.xyz/loom/3daa8a0e-e808-4fa6-aa6a-7f6780c116ed.png'
	StaticText Surfing Dog
	StaticText 0.000003 ETH per yr
	button Subscribe
	image
	StaticText Boost checkout conversions
	StaticText Reduce friction by letting users pay for transactions with tokens they already have on any chain. No need to swap or bridge.
	image
	StaticText Simplify deposit flows with cross-chain swaps
	StaticText Onboard users quicker by letting them deposit your dapp's preferred token with tokens they already have on any chain.
	image
	StaticText Enable cross-chain p2p transactions
	StaticText Make your app more social by letting users send tokens to each other across chains, with built-in swaps.
	image
	StaticText Enable credit & debit card payments
	StaticText Let users pay for transactions with credit and debit cards, making their crypto journey simpler.
	image
	StaticText Multiple transactions in one go
	StaticText Let users pay once for multiple transactions, even when the transactions are across multiple chains.
	image
	StaticText Launch an in-app currency
	StaticText Launch an in-app currency and let users pre-purchase onchain tokens that can be used to pay for transactions later.
	StaticText One-step
	StaticText gasless transactions
	StaticText Let your users pay for transactions with ERC-20 tokens without having to spend or hold any gas. Glide only requires a signature and handles the rest.
	StaticText Try the demo by minting an NFT on Zora. You will be able to pay for the transaction with USDC, no gas required.
	image Glide Logo, url='https://media.decentralized-content.com/-/rs:fit:1920:1920/aHR0cHM6Ly9tYWdpYy5kZWNlbnRyYWxpemVkLWNvbnRlbnQuY29tL2lwZnMvYmFma3JlaWdjZWVsY3Bia3djNGJydmQ3dWpyZ3FlZnBtY3U0cmxhZGRucDRlcW90eGl4NGc2dHc1aWE'
	StaticText Glide Logo
	StaticText 0.000777 ETH
	button Mint
	image
	StaticText Integration so easy,
	StaticText you’ll be done in an hour
	StaticText Glide comes with a lightweight and type-safe Typescript SDK to make the integration quick and painless. The SDK is compatible with popular libraries like wagmi/viem.
	StaticText For other languages, you can integrate directly with Glide’s REST API.
	StaticText npm
	StaticText i @paywithglide/glide-js
	StaticText import
	StaticText { createSession, currencies, chains }
	StaticText from
	StaticText "@paywithglide/glide-js"
	StaticText ;
	StaticText const
	StaticText session =
	StaticText await
	StaticText createSession
	StaticText (config, {
	StaticText chainId
	StaticText : chains.
	StaticText base
	StaticText .
	StaticText id
	StaticText ,
	StaticText account
	StaticText :
	StaticText "0xc6FfEB1298Eb33Da430d14e5Eb789256ec344625"
	StaticText ,
	StaticText paymentCurrency
	StaticText : currencies.
	StaticText usdc
	StaticText .
	StaticText on
	StaticText (chains.
	StaticText optimism
	StaticText ),
	StaticText preferGaslessPayment
	StaticText :
	StaticText true
	StaticText ,
	StaticText abi
	StaticText : hyperSubAbi,
	StaticText address
	StaticText :
	StaticText "0x1169c6769c4F4B3cA1944AF0F26B36582fd5279d"
	StaticText ,
	StaticText functionName
	StaticText :
	StaticText "mintFor"
	StaticText ,
	StaticText args
	StaticText : [
	StaticText "0xc6FfEB1298Eb33Da430d14e5Eb789256ec344625"
	StaticText ,
	StaticText 999999907200n
	StaticText ],
	StaticText value
	StaticText :
	StaticText 999999907200n
	StaticText ,
});
	StaticText Learn more
	button What is Glide?
		image
	paragraph
		StaticText Glide lets users pay for transactions with tokens they already have on any chain without the need to swap, bridge, or hold specific tokens to complete a transaction.
	paragraph
		StaticText Glide supports all EVM-compatible chains and hundreds of tokens, and lets users transact with the most popular smart contracts.
	button Who is Glide for?
		image
	button Which tokens are supported by Glide?
		image
	button Does Glide use more gas than a regular transaction?
		image
	image
	StaticText More from us
	link Documentation, url='https://docs.paywithglide.xyz/installation'
	link Explorer, url='https://explorer.paywithglide.xyz/'
	link Instant Bridge, url='https://bridge.paywithglide.xyz/'
	StaticText Company
	link Terms, url='https://paywithglide.xyz/terms'
	link Privacy, url='https://paywithglide.xyz/privacy'
	link Contact, url='mailto:founders@paywithglide.xyz'
	StaticText © 2024 Tenlab Technologies, Inc.
	StaticText Built in New York and California
```
</details>



```
RootWebArea Glide - Instant bridge from Ethereum to Base, focused, url='https://bridge.paywithglide.xyz/ethereum-to-base'
	banner
		[33] link, center=(722,92), url='https://paywithglide.xyz/'
			image
		[36] button Connect Wallet, center=(1219,92), type=button
```
<details><summary>Show more</summary>

```
	StaticText From
	log
	[51] image Ethereum, center=(830,196), url='https://bridge.paywithglide.xyz/networks/ethereum.png'
	StaticText Ethereum
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	[52] span, center=(881,196), inner_text=Ethereum
	[59] spinbutton 0, center=(917,249), contenteditable=True, type=number
	[57] svg, center=(932,196)
	log
	[67] image ETH, center=(1074,249), url='https://bridge.paywithglide.xyz/tokens/eth.png'
	StaticText ETH
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	[68] span, center=(1104,249), inner_text=ETH
	paragraph
	[73] svg, center=(1130,249)
	StaticText 0
	StaticText ETH
	[78] button MAX, center=(1130,287)
	image
	StaticText To
	log
	[92] image Base, center=(810,359), url='https://bridge.paywithglide.xyz/networks/base.png'
	StaticText Base
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	[93] span, center=(841,359), inner_text=Base
	[100] spinbutton 0, center=(917,412), type=number
	[98] svg, center=(873,359)
	log
	[108] image ETH, center=(1074,412), url='https://bridge.paywithglide.xyz/tokens/eth.png'
	StaticText ETH
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	[109] span, center=(1104,412), inner_text=ETH
	paragraph
	[114] svg, center=(1130,412)
	paragraph
		StaticText Receipent
	button
	paragraph
		StaticText Total Fees
	paragraph
		StaticText $
		StaticText 0
	paragraph
		StaticText Estimated Time
	paragraph
		image, url='https://bridge.paywithglide.xyz/lightning.svg'
		StaticText 10s
	[128] button Connect Wallet, center=(960,591)
	[131] button What is an instant bridge?, center=(960,732)
		image
	paragraph
		StaticText Glide's instant bridge lets you move tokens from one chain to another in less than 10 seconds at a very low cost.
	[140] button What networks and tokens does Glide support?, center=(960,871)
		image
	[146] button What are the fees for using Glide's instant bridge?, center=(960,954)
		image
	[152] button Can I integrate Glide into my dapp?, center=(960,1037)
		image
	contentinfo
		image
		StaticText Developers
		link Documentation, url='https://docs.paywithglide.xyz/installation'
		link Explorer, url='https://explorer.paywithglide.xyz/'
		link Media Kit, url='https://docs.paywithglide.xyz/resources/media-kit'
		StaticText Company
		link Terms, url='https://bridge.paywithglide.xyz/terms'
		link Privacy, url='https://bridge.paywithglide.xyz/privacy'
		link Contact, url='mailto:founders@paywithglide.xyz'
		StaticText ©
		StaticText 2025
		StaticText Tenlab Technologies, Inc.
		StaticText Built in New York and California
	alertdialog, modal=True
```
</details>

**Reasoning for action:** I chose to click the link labeled 'Instant Bridge' (represented by the identifier '26') because it is crucial for the user to connect their Rainbow wallet to facilitate cross-chain transactions. This action directly leads us to the relevant section of the webpage where the user can initiate the wallet connection process, ultimately helping to advance towards our objective of completing the user's task.

**Action:** click('26') # Click on the Instant Bridge link to explore that section.

**Change Description:** After clicking the 'Instant Bridge' link, the browser state transitioned to a new page focused on bridging from Ethereum to Base, displaying a new URL and interface elements like a 'Connect Wallet' button, network and token selection options, as well as details on fees and estimated transaction times.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://bridge.paywithglide.xyz/ethereum-to-base

https://bridge.paywithglide.xyz/ethereum-to-base

**Content (before/after):** 

```
RootWebArea Glide - Instant bridge from Ethereum to Base, focused, url='https://bridge.paywithglide.xyz/ethereum-to-base'
	banner
		[33] link, center=(722,92), url='https://paywithglide.xyz/'
			image
		[36] button Connect Wallet, center=(1219,92), type=button
```
<details><summary>Show more</summary>

```
	StaticText From
	log
	[51] image Ethereum, center=(830,196), url='https://bridge.paywithglide.xyz/networks/ethereum.png'
	StaticText Ethereum
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	[52] span, center=(881,196), inner_text=Ethereum
	[59] spinbutton 0, center=(917,249), contenteditable=True, type=number
	[57] svg, center=(932,196)
	log
	[67] image ETH, center=(1074,249), url='https://bridge.paywithglide.xyz/tokens/eth.png'
	StaticText ETH
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	[68] span, center=(1104,249), inner_text=ETH
	paragraph
	[73] svg, center=(1130,249)
	StaticText 0
	StaticText ETH
	[78] button MAX, center=(1130,287)
	image
	StaticText To
	log
	[92] image Base, center=(810,359), url='https://bridge.paywithglide.xyz/networks/base.png'
	StaticText Base
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	[93] span, center=(841,359), inner_text=Base
	[100] spinbutton 0, center=(917,412), type=number
	[98] svg, center=(873,359)
	log
	[108] image ETH, center=(1074,412), url='https://bridge.paywithglide.xyz/tokens/eth.png'
	StaticText ETH
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	[109] span, center=(1104,412), inner_text=ETH
	paragraph
	[114] svg, center=(1130,412)
	paragraph
		StaticText Receipent
	button
	paragraph
		StaticText Total Fees
	paragraph
		StaticText $
		StaticText 0
	paragraph
		StaticText Estimated Time
	paragraph
		image, url='https://bridge.paywithglide.xyz/lightning.svg'
		StaticText 10s
	[128] button Connect Wallet, center=(960,591)
	[131] button What is an instant bridge?, center=(960,732)
		image
	paragraph
		StaticText Glide's instant bridge lets you move tokens from one chain to another in less than 10 seconds at a very low cost.
	[140] button What networks and tokens does Glide support?, center=(960,871)
		image
	[146] button What are the fees for using Glide's instant bridge?, center=(960,954)
		image
	[152] button Can I integrate Glide into my dapp?, center=(960,1037)
		image
	contentinfo
		image
		StaticText Developers
		link Documentation, url='https://docs.paywithglide.xyz/installation'
		link Explorer, url='https://explorer.paywithglide.xyz/'
		link Media Kit, url='https://docs.paywithglide.xyz/resources/media-kit'
		StaticText Company
		link Terms, url='https://bridge.paywithglide.xyz/terms'
		link Privacy, url='https://bridge.paywithglide.xyz/privacy'
		link Contact, url='mailto:founders@paywithglide.xyz'
		StaticText ©
		StaticText 2025
		StaticText Tenlab Technologies, Inc.
		StaticText Built in New York and California
	alertdialog, modal=True
```
</details>



```
RootWebArea Glide - Instant bridge from Ethereum to Base, focused, url='https://bridge.paywithglide.xyz/ethereum-to-base'
	banner
		link, url='https://paywithglide.xyz/'
			image
		button Connect Wallet
```
<details><summary>Show more</summary>

```
	StaticText From
	log
	image Ethereum, url='https://bridge.paywithglide.xyz/networks/ethereum.png'
	StaticText Ethereum
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	spinbutton 0
	log
	image ETH, url='https://bridge.paywithglide.xyz/tokens/eth.png'
	StaticText ETH
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	paragraph
	StaticText 0
	StaticText ETH
	button MAX
	image
	StaticText To
	log
	image Base, url='https://bridge.paywithglide.xyz/networks/base.png'
	StaticText Base
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	spinbutton 0, disabled=True
	log
	image ETH, url='https://bridge.paywithglide.xyz/tokens/eth.png'
	StaticText ETH
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	paragraph
	paragraph
		StaticText Receipent
	button
	paragraph
		StaticText Total Fees
	paragraph
		StaticText $
		StaticText 0
	paragraph
		StaticText Estimated Time
	paragraph
		image, url='https://bridge.paywithglide.xyz/lightning.svg'
		StaticText 10s
	button Connect Wallet
	button What is an instant bridge?
		image
	paragraph
		StaticText Glide's instant bridge lets you move tokens from one chain to another in less than 10 seconds at a very low cost.
	button What networks and tokens does Glide support?
		image
	button What are the fees for using Glide's instant bridge?
		image
	button Can I integrate Glide into my dapp?
		image
	contentinfo
		image
		StaticText Developers
		link Documentation, url='https://docs.paywithglide.xyz/installation'
		link Explorer, url='https://explorer.paywithglide.xyz/'
		link Media Kit, url='https://docs.paywithglide.xyz/resources/media-kit'
		StaticText Company
		link Terms, url='https://bridge.paywithglide.xyz/terms'
		link Privacy, url='https://bridge.paywithglide.xyz/privacy'
		link Contact, url='mailto:founders@paywithglide.xyz'
		StaticText ©
		StaticText 2025
		StaticText Tenlab Technologies, Inc.
		StaticText Built in New York and California
	alertdialog, modal=True
	dialog Connect a Wallet, modal=True
		document, focused
			heading Connect a Wallet
			StaticText Popular
			[198] button Rainbow, center=(744,400)
				image
				StaticText Rainbow
			[207] button Coinbase Wallet, center=(744,444)
				image
				StaticText Coinbase Wallet
			[216] button MetaMask, center=(744,488)
				image
				StaticText MetaMask
			[225] button WalletConnect, center=(744,532)
				image
				StaticText WalletConnect
			[238] button Close, center=(1290,318), type=button
			StaticText What is a Wallet?
			image
			StaticText A Home for your Digital Assets
			StaticText Wallets are used to send, receive, store, and display digital assets like Ethereum and NFTs.
			image
			StaticText A New Way to Log In
			StaticText Instead of creating new accounts and passwords on every website, just connect your wallet.
			[262] button Get a Wallet, center=(1104,699), type=button
			[264] link Learn More, center=(1104,738), url='https://learn.rainbow.me/understanding-web3?utm_source=rainbowkit&utm_campaign=learnmore'
```
</details>

**Reasoning for action:** By clicking the 'Connect Wallet' button, I am taking the first step to connect the user's Rainbow wallet in order to facilitate cross-chain transactions. This action allows for the wallet connection modal to appear, where the user can select their desired wallet, specifically the Rainbow wallet, thereby advancing this process significantly towards achieving the user story.

**Action:** click('36') # Click on the Connect Wallet button to explore wallet connection options.

**Change Description:** After clicking the 'Connect Wallet' button, a modal dialog appeared, allowing the user to choose from various wallet options such as Rainbow, Coinbase Wallet, MetaMask, and WalletConnect, while the spinbutton for the 'To' section became disabled, indicating a pending action related to wallet connection.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://bridge.paywithglide.xyz/ethereum-to-base

https://bridge.paywithglide.xyz/ethereum-to-base

**Content (before/after):** 

```
RootWebArea Glide - Instant bridge from Ethereum to Base, focused, url='https://bridge.paywithglide.xyz/ethereum-to-base'
	banner
		link, url='https://paywithglide.xyz/'
			image
		button Connect Wallet
```
<details><summary>Show more</summary>

```
	StaticText From
	log
	image Ethereum, url='https://bridge.paywithglide.xyz/networks/ethereum.png'
	StaticText Ethereum
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	spinbutton 0
	log
	image ETH, url='https://bridge.paywithglide.xyz/tokens/eth.png'
	StaticText ETH
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	paragraph
	StaticText 0
	StaticText ETH
	button MAX
	image
	StaticText To
	log
	image Base, url='https://bridge.paywithglide.xyz/networks/base.png'
	StaticText Base
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	spinbutton 0, disabled=True
	log
	image ETH, url='https://bridge.paywithglide.xyz/tokens/eth.png'
	StaticText ETH
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	paragraph
	paragraph
		StaticText Receipent
	button
	paragraph
		StaticText Total Fees
	paragraph
		StaticText $
		StaticText 0
	paragraph
		StaticText Estimated Time
	paragraph
		image, url='https://bridge.paywithglide.xyz/lightning.svg'
		StaticText 10s
	button Connect Wallet
	button What is an instant bridge?
		image
	paragraph
		StaticText Glide's instant bridge lets you move tokens from one chain to another in less than 10 seconds at a very low cost.
	button What networks and tokens does Glide support?
		image
	button What are the fees for using Glide's instant bridge?
		image
	button Can I integrate Glide into my dapp?
		image
	contentinfo
		image
		StaticText Developers
		link Documentation, url='https://docs.paywithglide.xyz/installation'
		link Explorer, url='https://explorer.paywithglide.xyz/'
		link Media Kit, url='https://docs.paywithglide.xyz/resources/media-kit'
		StaticText Company
		link Terms, url='https://bridge.paywithglide.xyz/terms'
		link Privacy, url='https://bridge.paywithglide.xyz/privacy'
		link Contact, url='mailto:founders@paywithglide.xyz'
		StaticText ©
		StaticText 2025
		StaticText Tenlab Technologies, Inc.
		StaticText Built in New York and California
	alertdialog, modal=True
	dialog Connect a Wallet, modal=True
		document, focused
			heading Connect a Wallet
			StaticText Popular
			[198] button Rainbow, center=(744,400)
				image
				StaticText Rainbow
			[207] button Coinbase Wallet, center=(744,444)
				image
				StaticText Coinbase Wallet
			[216] button MetaMask, center=(744,488)
				image
				StaticText MetaMask
			[225] button WalletConnect, center=(744,532)
				image
				StaticText WalletConnect
			[238] button Close, center=(1290,318), type=button
			StaticText What is a Wallet?
			image
			StaticText A Home for your Digital Assets
			StaticText Wallets are used to send, receive, store, and display digital assets like Ethereum and NFTs.
			image
			StaticText A New Way to Log In
			StaticText Instead of creating new accounts and passwords on every website, just connect your wallet.
			[262] button Get a Wallet, center=(1104,699), type=button
			[264] link Learn More, center=(1104,738), url='https://learn.rainbow.me/understanding-web3?utm_source=rainbowkit&utm_campaign=learnmore'
```
</details>



```
RootWebArea Glide - Instant bridge from Ethereum to Base, focused, url='https://bridge.paywithglide.xyz/ethereum-to-base'
	banner
		link, url='https://paywithglide.xyz/'
			image
		button Connect Wallet
```
<details><summary>Show more</summary>

```
	StaticText From
	log
	image Ethereum, url='https://bridge.paywithglide.xyz/networks/ethereum.png'
	StaticText Ethereum
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	spinbutton 0
	log
	image ETH, url='https://bridge.paywithglide.xyz/tokens/eth.png'
	StaticText ETH
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	paragraph
	StaticText 0
	StaticText ETH
	button MAX
	image
	StaticText To
	log
	image Base, url='https://bridge.paywithglide.xyz/networks/base.png'
	StaticText Base
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	spinbutton 0, disabled=True
	log
	image ETH, url='https://bridge.paywithglide.xyz/tokens/eth.png'
	StaticText ETH
	combobox, autocomplete='list', expanded=False, hasPopup='menu'
	paragraph
	paragraph
		StaticText Receipent
	button
	paragraph
		StaticText Total Fees
	paragraph
		StaticText $
		StaticText 0
	paragraph
		StaticText Estimated Time
	paragraph
		image, url='https://bridge.paywithglide.xyz/lightning.svg'
		StaticText 10s
	button Connect Wallet
	button What is an instant bridge?
		image
	paragraph
		StaticText Glide's instant bridge lets you move tokens from one chain to another in less than 10 seconds at a very low cost.
	button What networks and tokens does Glide support?
		image
	button What are the fees for using Glide's instant bridge?
		image
	button Can I integrate Glide into my dapp?
		image
	contentinfo
		image
		StaticText Developers
		link Documentation, url='https://docs.paywithglide.xyz/installation'
		link Explorer, url='https://explorer.paywithglide.xyz/'
		link Media Kit, url='https://docs.paywithglide.xyz/resources/media-kit'
		StaticText Company
		link Terms, url='https://bridge.paywithglide.xyz/terms'
		link Privacy, url='https://bridge.paywithglide.xyz/privacy'
		link Contact, url='mailto:founders@paywithglide.xyz'
		StaticText ©
		StaticText 2025
		StaticText Tenlab Technologies, Inc.
		StaticText Built in New York and California
	alertdialog, modal=True
	dialog Connect a Wallet, modal=True
		document
			heading Connect a Wallet
			StaticText Popular
			[198] button Rainbow, center=(744,400)
				image
				StaticText Rainbow
			[207] button Coinbase Wallet, center=(744,444)
				image
				StaticText Coinbase Wallet
			[216] button MetaMask, center=(744,488)
				image
				StaticText MetaMask
			[225] button WalletConnect, center=(744,532)
				image
				StaticText WalletConnect
			StaticText Scan with Rainbow
			[238] button Close, center=(1290,318), type=button
			image
			image QR Code
			StaticText Don't have Rainbow?
			[280] button GET, center=(1269,762), type=button
```
</details>

**Reasoning for action:** By clicking on the Rainbow wallet button, I am indicating the user's choice to connect this specific wallet. This action is essential as it moves us away from the modal interface and into the next part of the wallet connection process, which should display the QR code and connection instructions as defined in the user story. This aligns with the user's goal of enabling a seamless connection for cross-chain transactions.

**Action:** click('198') # Click on the Rainbow wallet option to explore the connection process.

**Change Description:** After clicking the Rainbow wallet option, the modal dialog now includes a QR code for scanning, suggesting that the user can connect their Rainbow wallet using this method. Additionally, the static text has changed to indicate options for scanning with Rainbow and a button to get the Rainbow wallet.

**Screenshot before:****Screenshot after:**---


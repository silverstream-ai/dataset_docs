# Task

**User Story for Exploring EBT Payment Options**

As a potential merchant looking to enable EBT payments,
I learn about Forage's online EBT payment services,
so that I can understand how to integrate EBT payments into my business and unlock new revenue streams.

**Success definition:** Given I am on the Forage website's Products page
When I click on the Online EBT Payments option
Then I should be redirected to the Online EBT Payments page and see detailed information about the service available; and when I click the Learn More button, I should be directed to the Android documentation page that provides comprehensive implementation instructions.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.joinforage.com/

https://www.joinforage.com/

**Content (before/after):** 

```
RootWebArea Forage, focused, url='https://www.joinforage.com/'
	main
		navigation
			[57] link Forage, center=(517,30), url='https://www.joinforage.com/'
				image
```
<details><summary>Show more</summary>

```
			navigation
				generic, hasPopup='menu'
					[62] button Products, center=(704,30)
				generic, hasPopup='menu'
					[82] button Partners, center=(811,30)
				generic, hasPopup='menu'
					[96] button Resources, center=(922,30)
				generic, hasPopup='menu'
					[114] button Developers, center=(1042,30)
				[129] button Pricing, center=(1141,30)
					link Pricing, url='https://www.joinforage.com/pricing'
				[131] button Company, center=(1225,30)
					link Company, url='https://www.joinforage.com/about'
			[134] link Get started, center=(1405,30), url='https://www.joinforage.com/contact'
				button Get started
			navigation
				generic, hasPopup='menu'
					button Products
				generic, hasPopup='menu'
					button Partners
				generic, hasPopup='menu'
					button Resources
				generic, hasPopup='menu'
					button Developers
				button Pricing
					link Pricing, url='https://www.joinforage.com/pricing'
				button Company
					link Company, url='https://www.joinforage.com/about'
		[220] link NEW Unlock in‑store EBT payments., center=(960,442), inner_text=NEW
Unlock in‑store EBT payments., url='https://www.joinforage.com/products/in-store-ebt-payments'
		heading Payments powering people
		paragraph
			StaticText Forage is a mission-driven payments company that helps merchants accept EBT SNAP payments through a single, unified API.
		[231] link Contact Us, center=(960,685), url='https://www.joinforage.com/contact'
			button Contact Us
		list
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-eggs.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-apples.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-bread.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-blueberries.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-limes.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-salmon.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-eggs.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-tomatoes.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-kiwis.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-apples.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-blueberries.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-bread.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-salmon.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-tomatoes.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-limes.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-kiwis.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-eggs.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-apples.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-blueberries.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-bread.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-salmon.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-tomatoes.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-limes.jpg&w=640&q=75'
			listitem
				image circle, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-kiwis.jpg&w=640&q=75'
		heading TRUSTED BY MERCHANTS OF ALL SHAPES AND SIZES
		image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
		image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
		image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
		image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
		image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
		image Toast, url='https://cdn.sanity.io/images/2ue7evhq/production/37336f0cf2c95083241687377c5d5eba9113ca20-2560x679.svg'
		image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
		image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
		image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
		image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
		image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
		image Winn Dixie, url='https://cdn.sanity.io/images/2ue7evhq/production/8b685bca4370ebeadd7f4c0fe183a6644272f1dc-1024x156.svg'
		image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
		image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
		image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
		image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
		image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
		image Homesome, url='https://cdn.sanity.io/images/2ue7evhq/production/b26ee0e1487d9ed15f41d4e633c7620ebcf0f756-144x29.svg'
		image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
		image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
		image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
		image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
		image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
		image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
		image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
		image Toast, url='https://cdn.sanity.io/images/2ue7evhq/production/37336f0cf2c95083241687377c5d5eba9113ca20-2560x679.svg'
		image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
		image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
		image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
		image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
		image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
		image Winn Dixie, url='https://cdn.sanity.io/images/2ue7evhq/production/8b685bca4370ebeadd7f4c0fe183a6644272f1dc-1024x156.svg'
		image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
		image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
		image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
		image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
		image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
		image Homesome, url='https://cdn.sanity.io/images/2ue7evhq/production/b26ee0e1487d9ed15f41d4e633c7620ebcf0f756-144x29.svg'
		image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
		image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
		image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
		image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
		image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
		image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
		image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
		image Toast, url='https://cdn.sanity.io/images/2ue7evhq/production/37336f0cf2c95083241687377c5d5eba9113ca20-2560x679.svg'
		image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
		image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
		image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
		image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
		image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
		image Winn Dixie, url='https://cdn.sanity.io/images/2ue7evhq/production/8b685bca4370ebeadd7f4c0fe183a6644272f1dc-1024x156.svg'
		image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
		image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
		image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
		image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
		image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
		image Homesome, url='https://cdn.sanity.io/images/2ue7evhq/production/b26ee0e1487d9ed15f41d4e633c7620ebcf0f756-144x29.svg'
		image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
		image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
		image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
		image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
		image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
		image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
		image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
		image Toast, url='https://cdn.sanity.io/images/2ue7evhq/production/37336f0cf2c95083241687377c5d5eba9113ca20-2560x679.svg'
		image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
		image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
		image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
		image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
		image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
		image Winn Dixie, url='https://cdn.sanity.io/images/2ue7evhq/production/8b685bca4370ebeadd7f4c0fe183a6644272f1dc-1024x156.svg'
		image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
		image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
		image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
		image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
		image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
		image Homesome, url='https://cdn.sanity.io/images/2ue7evhq/production/b26ee0e1487d9ed15f41d4e633c7620ebcf0f756-144x29.svg'
		image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
		image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
		image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
		image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
		image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
		image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
		image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
		image Toast, url='https://cdn.sanity.io/images/2ue7evhq/production/37336f0cf2c95083241687377c5d5eba9113ca20-2560x679.svg'
		image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
		image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
		image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
		image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
		image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
		image Winn Dixie, url='https://cdn.sanity.io/images/2ue7evhq/production/8b685bca4370ebeadd7f4c0fe183a6644272f1dc-1024x156.svg'
		image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
		image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
		image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
		image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
		image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
		image Homesome, url='https://cdn.sanity.io/images/2ue7evhq/production/b26ee0e1487d9ed15f41d4e633c7620ebcf0f756-144x29.svg'
		image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
		image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
		image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
		image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
		image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
		image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
		image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
		image Toast, url='https://cdn.sanity.io/images/2ue7evhq/production/37336f0cf2c95083241687377c5d5eba9113ca20-2560x679.svg'
		image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
		image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
		image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
		image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
		image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
		image Winn Dixie, url='https://cdn.sanity.io/images/2ue7evhq/production/8b685bca4370ebeadd7f4c0fe183a6644272f1dc-1024x156.svg'
		image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
		image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
		image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
		image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
		image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
		image Homesome, url='https://cdn.sanity.io/images/2ue7evhq/production/b26ee0e1487d9ed15f41d4e633c7620ebcf0f756-144x29.svg'
		image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
		image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
		image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
		image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
		image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
		image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
		image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
		image Toast, url='https://cdn.sanity.io/images/2ue7evhq/production/37336f0cf2c95083241687377c5d5eba9113ca20-2560x679.svg'
		image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
		image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
		image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
		image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
		image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
		image Winn Dixie, url='https://cdn.sanity.io/images/2ue7evhq/production/8b685bca4370ebeadd7f4c0fe183a6644272f1dc-1024x156.svg'
		image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
		image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
		image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
		image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
		image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
		image Homesome, url='https://cdn.sanity.io/images/2ue7evhq/production/b26ee0e1487d9ed15f41d4e633c7620ebcf0f756-144x29.svg'
		image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
		image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
		image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
		image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
		image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
		image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
		image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
		image Toast, url='https://cdn.sanity.io/images/2ue7evhq/production/37336f0cf2c95083241687377c5d5eba9113ca20-2560x679.svg'
		image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
		image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
		image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
		image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
		image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
		image Winn Dixie, url='https://cdn.sanity.io/images/2ue7evhq/production/8b685bca4370ebeadd7f4c0fe183a6644272f1dc-1024x156.svg'
		image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
		image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
		image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
		image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
		image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
		image Homesome, url='https://cdn.sanity.io/images/2ue7evhq/production/b26ee0e1487d9ed15f41d4e633c7620ebcf0f756-144x29.svg'
		image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
		image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
		separator, orientation='horizontal'
		heading Why doing good is good for business.
		image Why doing good is good for business., url='https://www.joinforage.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2F2ue7evhq%2Fproduction%2F4f42f59b469100909ca88e3f20a2556464259f76-4288x2848.jpg%3Fw%3D2400%26fit%3Dmax%26auto%3Dformat&w=1920&q=75'
		StaticText AUDIENCE
		heading 42M People
		separator, orientation='horizontal'
		paragraph
			StaticText More than
			link 1 in 8 Americans, url='https://www.fns.usda.gov/pd/supplemental-nutrition-assistance-program-snap'
			StaticText receive government benefits through programs like SNAP, formerly known as food stamps.
		StaticText MARKET
		heading $200B+ USD
		separator, orientation='horizontal'
		paragraph
			StaticText Billions of dollars are distributed annually by the U.S. government in benefit programs such as SNAP, TANF (EBT Cash), and many others.
		StaticText TRAJECTORY
		heading >300x Increase
		separator, orientation='horizontal'
		paragraph
			StaticText Since 2019, the number of SNAP households using their benefits online has increased from 35 thousand to over 12 million (and counting!).
		StaticText REVENUE
		heading 15%+ Growth
		separator, orientation='horizontal'
		paragraph
			StaticText Merchants grow their sales by 15% or more when they enable EBT SNAP and EBT Cash payments with Forage.
		image Food image, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-apples.jpg&w=1920&q=75'
		image Food image, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-blueberries.jpg&w=1920&q=75'
		image Food image, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-tomatoes.jpg&w=1920&q=75'
		image Food image, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-cereal.jpg&w=1920&q=75'
		image Food image, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-salmon.jpg&w=1920&q=75'
		image Food image, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-bread.jpg&w=1920&q=75'
		image Food image, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-limes.jpg&w=1920&q=75'
		image Food image, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-kiwis.jpg&w=1920&q=75'
		image Food image, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-eggs.jpg&w=1920&q=75'
		image Food image, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-apples.jpg&w=1920&q=75'
		image Food image, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-pears.jpg&w=1920&q=75'
		separator, orientation='horizontal'
		heading BENEFITS
		heading Grow your business with Forage.
		paragraph
			StaticText With our leading API and SDKs, you are only an integration away from unlocking new revenue streams and enabling EBT payments.
		article
			image
			heading Proven Reliability
			paragraph
				StaticText We are the only cloud-based EBT payment provider with 99.9% reliability and
				link public status page, url='https://status.joinforage.app/'
				StaticText .
			image
			heading Pre-Built Components
			paragraph
				StaticText Deliver seamless checkouts for your customers, without the code or integration hassle.
			image
			heading Rapid Certification
			paragraph
				StaticText Get approved by the USDA, in a fraction of the time, with our in-house team of SNAP experts.
			image
			heading USDA-Approved
			paragraph
				StaticText Forage is one of three payment providers approved by the USDA to process EBT payments.
			image
			heading Safe & Secure
			paragraph
				StaticText Protect your business and customers with our PCI-compliant fraud layer and leading anti-fraud solutions.
			image
			heading Real-Time Analytics
			paragraph
				StaticText Scale your EBT business with our configurable merchant dashboard, purpose-built for your specific needs.
		heading Built by developers, for developers.
		paragraph
			StaticText Websites and apps are built on all kinds of tech stacks. With Forage, your engineers can pick the integration option and SDK that best suits your existing infrastructure.
		link Explore API documentation, url='https://docs.joinforage.app/reference/introduction'
			button Explore API documentation
		navigation
			tablist, orientation='horizontal'
				tab cURL, selected=False
				tab JS, selected=False
				tab iOS, selected=False
				tab Android, selected=False
		tabpanel
			code
				StaticText 1
				StaticText curl
				StaticText --request POST \
				StaticText 2
				StaticText --
				StaticText url
				StaticText https://api.sandbox.joinforage.app/api/payments/ \
				StaticText 3
				StaticText --
				StaticText header
				StaticText 'Authorization: Bearer prod_vOrumiuRFG
				StaticText 7
				StaticText ouMoZNF
				StaticText 8
				StaticText AeFNwMhZRET' \
				StaticText 4
				StaticText --
				StaticText header
				StaticText 'Idempotency-Key:
				StaticText 123
				StaticText 45678
				StaticText ' \
				StaticText 5
				StaticText --
				StaticText header
				StaticText 'Merchant-Account:
				StaticText 1234567
				StaticText ' \
				StaticText 6
				StaticText --
				StaticText header
				StaticText 'accept: application/json' \
				StaticText 7
				StaticText --
				StaticText header
				StaticText 'content-type: application/json' \
				StaticText 8
				StaticText --
				StaticText data
				StaticText ' {
				StaticText "amount"
				StaticText :
				StaticText 25
				StaticText .
				StaticText 99
				StaticText ,
				StaticText "payment_method"
				StaticText :
				StaticText "ac47392bb1"
				StaticText ,
				StaticText "funding_type"
				StaticText :
				StaticText "ebt_snap"
				StaticText ,
				StaticText "customer_id"
				StaticText :
				StaticText "e8819a107a50aa50771a075e25a7529421ad0267bfef691745f915d8a2acc7e9"
				StaticText }
		tabpanel
			code
				StaticText 1
				StaticText const
				StaticText forage = Forage({
				StaticText 2
				StaticText fnsNumber
				StaticText : FNS_NUMBER,
				StaticText 3
				StaticText sessionToken
				StaticText : SESSION_TOKEN,
				StaticText 4
				StaticText customerId
				StaticText : CUSTOMER_ID,
				StaticText 5
				StaticText });
				StaticText 6
				StaticText const
				StaticText tokenizeEbtCardElement = forage.create(
				StaticText "ebt_card_tokenize_number"
				StaticText );
				StaticText 7
				StaticText try
				StaticText {
				StaticText 8
				StaticText const
				StaticText tokenizedEbtCardResult =
				StaticText await
				StaticText forage.tokenizeEbtCardNumber(
				StaticText 9
				StaticText tokenizeEbtCardElement
				StaticText 10
				StaticText );
				StaticText 11
				StaticText // ...
				StaticText 12
				StaticText }
				StaticText catch
				StaticText (error) {
				StaticText 13
				StaticText // handle error
				StaticText 14
				StaticText }
		tabpanel
			code
				StaticText 1
				StaticText private
				StaticText let
				StaticText panNumberTextField:
				StaticText ForagePANTextField
				StaticText =
				StaticText {
				StaticText 2
				StaticText let
				StaticText tf
				StaticText =
				StaticText ForagePANTextField
				StaticText ()
				StaticText 3
				StaticText tf.placeholder
				StaticText =
				StaticText PAN
				StaticText Number
				StaticText 4
				StaticText return
				StaticText tf
				StaticText 5
				StaticText }()
				StaticText 6
				StaticText 7
				StaticText ForageSDK
				StaticText .shared.tokenizeEBTCard(
				StaticText 8
				StaticText bearerToken: bearerToken,
				StaticText 9
				StaticText merchantAccount: merchantID,
				StaticText 10
				StaticText customerID: customerID
				StaticText 11
				StaticText ) { result
				StaticText in
				StaticText 12
				StaticText // handle callback here
				StaticText 13
				StaticText }
		tabpanel
			code
				StaticText 1
				StaticText val response = ForageSDK.tokenizeEBTCard(
				StaticText 2
				StaticText merchantAccount = merchantAccount,
				StaticText 3
				StaticText bearerToken = bearer,
				StaticText 4
				StaticText //
				StaticText NOTE:
				StaticText The following line is for testing purposes only and should not be used in production.
				StaticText 5
				StaticText // Please replace this line with a real hashed customer ID value.
				StaticText 6
				StaticText customerId = UUID.randomUUID().toString()
				StaticText 7
				StaticText )
				StaticText 8
				StaticText 9
				StaticText when(response) {
				StaticText 10
				StaticText is ForageApiResponse.Success -> {
				StaticText 11
				StaticText val adapter: JsonAdapter < PaymentMethod > = moshi.adapter(PaymentMethod::class.java)
				StaticText 12
				StaticText val result = adapter.fromJson(response.data)
				StaticText 13
				StaticText _paymentMethod.value = result
				StaticText 14
				StaticText }
				StaticText 15
				StaticText is ForageApiResponse.Failure -> {
				StaticText 16
				StaticText _error.value = response.message
				StaticText 17
				StaticText }
				StaticText 18
				StaticText }
		StaticText DEVELOPER RESOURCES
		link Forage Docs, url='https://docs.joinforage.app/reference/introduction'
			paragraph
				StaticText Forage Docs
		link Forage Integrations, url='https://docs.joinforage.app/docs/get-started'
			paragraph
				StaticText Forage Integrations
		link Forage GitHub, url='https://github.com/teamforage'
			paragraph
				StaticText Forage GitHub
		link Forage Status, url='https://status.joinforage.app/'
			paragraph
				StaticText Forage Status
		heading Featured by.
		link Fast Company's World Changing Ideas 2023, url='https://www.fastcompany.com/90869778/forage-software-buy-groceries-online-snap-ebt-payments%EF%BB%BF'
			image Fast Company's World Changing Ideas 2023, url='https://cdn.sanity.io/images/2ue7evhq/production/b500f8e2cbe43b50ed19a74254f4701914cbf247-706x101.svg'
		link 44 Companies To Bet Your Career On, url='https://www.businessinsider.com/startups-to-bet-your-career-on-in-2024-2024-2'
			image 44 Companies To Bet Your Career On, url='https://cdn.sanity.io/images/2ue7evhq/production/f90c1143391e5482d5a03e846683d5440d58f3d0-623x194.svg'
		link Thrive Market Becomes 1st Online-Only Retailer to Accept SNAP EBT, url='https://progressivegrocer.com/thrive-market-becomes-1st-online-only-retailer-accept-snap-ebt'
			image Thrive Market Becomes 1st Online-Only Retailer to Accept SNAP EBT, url='https://cdn.sanity.io/images/2ue7evhq/production/86b60ce58da6bc19dab078c59515f2d8d4bb8916-2851x842.svg'
		link Forage Raises $22M Series A, url='https://www.forbes.com/sites/jeffkauflin/2022/08/08/food-stamp-focused-fintech-raises-22-million/?sh=23a55bd3751a'
			image Forage Raises $22M Series A, url='https://cdn.sanity.io/images/2ue7evhq/production/a550db4edfba430a35622bd806829da87e7780e8-414x109.svg'
		link Instacart’s head of payments leaves tech giant to join startup Forage, url='https://techcrunch.com/2022/03/01/instacarts-head-of-payments-leaves-tech-giant-to-join-startup-forage/'
			image Instacart’s head of payments leaves tech giant to join startup Forage, url='https://cdn.sanity.io/images/2ue7evhq/production/80d379535bbc465d296f9a31b3f4a2af6defdfce-180x90.svg'
		link Disruption for good: Talking with Forage’s CEO Ofek Lavian, url='https://www.mckinsey.com/industries/financial-services/our-insights/disruption-for-good-talking-with-forages-ceo-ofek-lavian'
			image Disruption for good: Talking with Forage’s CEO Ofek Lavian, url='https://cdn.sanity.io/images/2ue7evhq/production/5ae47a293efd425cd4f66e3b7c20f7fbfec2fb2a-39x12.svg'
		link Save Mart partners with Forage and Flashfood, url='https://www.grocerydive.com/news/save-mart-partners-flashfood-foodwaste-sustainability/710800/'
			image Save Mart partners with Forage and Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/8e3e6f0c9fd5421c48096297bd7b65d57af4ff9c-1779x304.svg'
		link Forage Takes On Stalwarts to Gain Slice of $100B Online SNAP Payments Opportunity, url='https://www.pymnts.com/news/ecommerce/2022/forage-takes-on-stalwarts-to-gain-slice-of-100b-online-snap-payments-opportunity/'
			image Forage Takes On Stalwarts to Gain Slice of $100B Online SNAP Payments Opportunity, url='https://cdn.sanity.io/images/2ue7evhq/production/b1f875690e1f39fceb87571a02dcd4a9c4a49b9f-798x167.svg'
		heading Our Investors.
		link Nyca, url='https://www.nyca.com/'
			image Nyca, url='https://cdn.sanity.io/images/2ue7evhq/production/387f43188cbf06d89f9baa18fb16fc1ab335b73a-64x24.svg'
		link Y Combinator, url='https://www.ycombinator.com/'
			image Y Combinator, url='https://cdn.sanity.io/images/2ue7evhq/production/81ba9adef4e38299bcab221a293ff0fa91ca3711-90x24.svg'
		link PayPal, url='https://about.pypl.com/how-we-work/paypal-ventures/default.aspx'
			image PayPal, url='https://cdn.sanity.io/images/2ue7evhq/production/e0879c7bdc6162372d81e0f59a80f7168c66d028-86x24.svg'
		link EO Ventures, url='https://www.eoventures.com/'
			image EO Ventures, url='https://cdn.sanity.io/images/2ue7evhq/production/6c54d62d04eb62792beb514578c17e02b61631a4-33x24.svg'
		link FIS, url='https://www.fisglobal.com/en'
			image FIS, url='https://www.joinforage.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2F2ue7evhq%2Fproduction%2F6ff960057309b1d56ca9d4e8b97b9a78ed400ce3-1200x501.png&w=1920&q=75'
		heading Begin accepting EBT SNAP and EBT Cash.
		paragraph
			StaticText Learn how Forage unlocks new revenue streams for merchants of all shapes and sizes.
		link Contact Us, url='https://www.joinforage.com/contact'
			button Contact Us
		link Learn More, url='https://www.joinforage.com/products/ebt'
			button Learn More
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-blueberries.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-apples.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-cereal.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-eggs.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-kiwis.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-bread.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-tomatoes.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-limes.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-salmon.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-blueberries.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-apples.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-cereal.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-eggs.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-kiwis.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-bread.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-tomatoes.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-limes.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-salmon.jpg&w=1920&q=75'
		link Forage, url='https://www.joinforage.com/'
			image
		navigation
			StaticText Product
			link Online EBT Payments, url='https://www.joinforage.com/products/online-ebt-payments'
			link In-Store EBT Payments, url='https://www.joinforage.com/products/in-store-ebt-payments'
			link API ↗, url='https://docs.joinforage.app/reference/introduction'
				superscript
			link Quick Start ↗, url='https://docs.joinforage.app/docs/overview'
				superscript
			link USDA-approved ↗, url='https://www.fns.usda.gov/snap/online-purchasing-retailers-technical-qas'
				superscript
		navigation
			StaticText Company
			link About, url='https://www.joinforage.com/about'
			link Careers ↗, url='https://boards.greenhouse.io/joinforage'
				superscript
			link Newsroom, url='https://www.joinforage.com/newsroom'
			link Partners, url='https://www.joinforage.com/partners'
			link Resources, url='https://www.joinforage.com/products/forage-ebook'
		navigation
			StaticText Support
			link FAQs, url='https://www.joinforage.com/faq'
			link Contact, url='https://www.joinforage.com/contact'
			link Privacy, url='https://www.joinforage.com/privacy'
			link Status ↗, url='https://status.joinforage.app/'
				superscript
		navigation
			link, url='https://github.com/teamforage'
			link, url='https://twitter.com/joinforage'
			link, url='https://linkedin.com/company/foragepayments'
			link, url='https://apps.shopify.com/ebt'
		link ALL SYSTEMS OPERATIONAL, url='https://status.joinforage.app/'
		StaticText Forage is equal opportunity. ©
		StaticText 2025
		StaticText Forage Technology Corporation, Inc.
		navigation
			navigation
				link Privacy Policy, url='https://www.joinforage.com/privacy'
			navigation
				link Terms of Use, url='https://www.joinforage.com/terms-of-use'
			navigation
				link Cookie Statement, url='https://www.joinforage.com/cookie-statement'
	alert, atomic
```
</details>



```
RootWebArea Forage, focused, url='https://www.joinforage.com/'
	button Dismiss
	[231] a, center=(960,685), inner_text=Contact Us
	[220] a, center=(960,442), inner_text=NEW
Unlock in‑store EBT payments.
```
<details><summary>Show more</summary>

```
	[134] a, center=(1405,30), inner_text=Get started
	[131] div, center=(1225,30), inner_text=Company
	[129] div, center=(1141,30), inner_text=Pricing
	[114] div, center=(1042,30), inner_text=Developers
	[96] div, center=(922,30), inner_text=Resources
	[82] div, center=(811,30), inner_text=Partners
	[62] div, center=(704,30), inner_text=Products
	[57] a, center=(517,30)
	menu Products, orientation='vertical'
		menuitem Online EBT Payments Start accepting EBT SNAP and EBT Cash payments online, on mobile and/or desktop. In-Store EBT Payments Start accepting EBT SNAP and EBT Cash payments in-store, on your POS devices., focused
			[1406] menuitem Online EBT Payments Start accepting EBT SNAP and EBT Cash payments online, on mobile and/or desktop., center=(704,108), inner_text=Online EBT Payments

Start accepting EBT SNAP and EBT Cash payments online, on mobile and/or desktop.
				link Online EBT Payments Start accepting EBT SNAP and EBT Cash payments online, on mobile and/or desktop., url='https://www.joinforage.com/products/online-ebt-payments'
					paragraph
			[1413] menuitem In-Store EBT Payments Start accepting EBT SNAP and EBT Cash payments in-store, on your POS devices., center=(704,168), inner_text=In-Store EBT Payments

Start accepting EBT SNAP and EBT Cash payments in-store, on your POS devices.
				link In-Store EBT Payments Start accepting EBT SNAP and EBT Cash payments in-store, on your POS devices., url='https://www.joinforage.com/products/in-store-ebt-payments'
					paragraph
	button Dismiss
	alert, atomic
```
</details>

**Reasoning for action:** By clicking the Products button, I am able to access the relevant products offered by Forage, including the Online EBT Payments option, which is crucial for the user to learn about enabling EBT payments in their business. This step is fundamental to finding the specific information needed about the EBT services, thereby moving closer to achieving the user’s goal.

**Action:** click(62) # Click on the Products button to explore the product offerings.

**Change Description:** After the action of clicking the 'Products' button, a dropdown menu appeared displaying options for 'Online EBT Payments' and 'In-Store EBT Payments', allowing users to explore product offerings related to accepting EBT SNAP and EBT Cash payments.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.joinforage.com/

https://www.joinforage.com/products/online-ebt-payments

**Content (before/after):** 

```
RootWebArea Forage, focused, url='https://www.joinforage.com/'
	button Dismiss
	[231] a, center=(960,685), inner_text=Contact Us
	[220] a, center=(960,442), inner_text=NEW
Unlock in‑store EBT payments.
```
<details><summary>Show more</summary>

```
	[134] a, center=(1405,30), inner_text=Get started
	[131] div, center=(1225,30), inner_text=Company
	[129] div, center=(1141,30), inner_text=Pricing
	[114] div, center=(1042,30), inner_text=Developers
	[96] div, center=(922,30), inner_text=Resources
	[82] div, center=(811,30), inner_text=Partners
	[62] div, center=(704,30), inner_text=Products
	[57] a, center=(517,30)
	menu Products, orientation='vertical'
		menuitem Online EBT Payments Start accepting EBT SNAP and EBT Cash payments online, on mobile and/or desktop. In-Store EBT Payments Start accepting EBT SNAP and EBT Cash payments in-store, on your POS devices., focused
			[1406] menuitem Online EBT Payments Start accepting EBT SNAP and EBT Cash payments online, on mobile and/or desktop., center=(704,108), inner_text=Online EBT Payments

Start accepting EBT SNAP and EBT Cash payments online, on mobile and/or desktop.
				link Online EBT Payments Start accepting EBT SNAP and EBT Cash payments online, on mobile and/or desktop., url='https://www.joinforage.com/products/online-ebt-payments'
					paragraph
			[1413] menuitem In-Store EBT Payments Start accepting EBT SNAP and EBT Cash payments in-store, on your POS devices., center=(704,168), inner_text=In-Store EBT Payments

Start accepting EBT SNAP and EBT Cash payments in-store, on your POS devices.
				link In-Store EBT Payments Start accepting EBT SNAP and EBT Cash payments in-store, on your POS devices., url='https://www.joinforage.com/products/in-store-ebt-payments'
					paragraph
	button Dismiss
	alert, atomic
```
</details>



```
RootWebArea Online EBT Payments | Forage, focused, url='https://www.joinforage.com/products/online-ebt-payments'
	main
		navigation
			[1438] link Forage, center=(517,30), url='https://www.joinforage.com/'
				image
```
<details><summary>Show more</summary>

```
			navigation
				generic, hasPopup='menu'
					[1443] button Products, center=(704,30)
				generic, hasPopup='menu'
					[1463] button Partners, center=(811,30)
				generic, hasPopup='menu'
					[1477] button Resources, center=(922,30)
				generic, hasPopup='menu'
					[1495] button Developers, center=(1042,30)
				[1510] button Pricing, center=(1141,30)
					link Pricing, url='https://www.joinforage.com/pricing'
				[1512] button Company, center=(1225,30)
					link Company, url='https://www.joinforage.com/about'
			[1515] link Get started, center=(1405,30), url='https://www.joinforage.com/contact'
				button Get started
			navigation
				generic, hasPopup='menu'
					button Products
				generic, hasPopup='menu'
					button Partners
				generic, hasPopup='menu'
					button Resources
				generic, hasPopup='menu'
					button Developers
				button Pricing
					link Pricing, url='https://www.joinforage.com/pricing'
				button Company
					link Company, url='https://www.joinforage.com/about'
		article
			heading Unlock EBT payments online.
			paragraph
				StaticText Start accepting EBT SNAP and EBT Cash payments online.
			[1607] link Contact Us, center=(888,314), url='https://www.joinforage.com/contact'
				button Contact Us
			[1610] link Learn More, center=(1030,315), url='https://docs.joinforage.app/docs/android'
				button Learn More
			image Unlock EBT payments online., url='https://www.joinforage.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2F2ue7evhq%2Fproduction%2Ffc98362354a770eac365348a446176d87e199692-2400x1340.png%3Fw%3D2600%26fit%3Dmax%26auto%3Dformat&w=3840&q=100'
			heading TRUSTED BY MERCHANTS OF ALL SHAPES AND SIZES
			image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
			image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
			image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
			image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
			image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
			image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
			image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
			image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
			image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
			image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
			image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
			image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
			image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
			image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
			image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
			image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
			image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
			image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
			image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
			image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
			image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
			image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
			image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
			image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
			image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
			image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
			image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
			image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
			image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
			image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
			image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
			image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
			image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
			image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
			image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
			image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
			image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
			image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
			image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
			image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
			image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
			image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
			image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
			image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
			image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
			image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
			image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
			image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
			image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
			image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
			image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
			image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
			image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
			image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
			image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
			image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
			image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
			image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
			image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
			image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
			image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
			image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
			image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
			image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
			image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
			image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
			image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
			image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
			image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
			image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
			image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
			image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
			image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
			image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
			image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
			image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
			image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
			image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
			image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
			image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
			image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
			image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
			image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
			image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
			image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
			image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
			image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
			image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
			image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
			image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
			image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
			image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
			image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
			image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
			image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
			image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
			image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
			image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
			image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
			image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
			image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
			image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
			image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
			image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
			image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			separator, orientation='horizontal'
			heading SIMPLIFYING CHECKOUT
			heading Best-In-Class UX
			paragraph
				StaticText Deliver seamless payment experiences for your customers. Increase conversion rates and drive more incremental EBT sales online with Forage.
			link Book a Demo, url='https://www.joinforage.com/contact'
				button Book a Demo
			image Best-In-Class UX, url='https://www.joinforage.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2F2ue7evhq%2Fproduction%2F502e7a61e1cabbe1eb81967db0a3a32d8e02f126-5120x3136.png%3Fw%3D2600%26fit%3Dmax%26auto%3Dformat&w=3840&q=100'
			heading MODERN INFRASTRUCTURE
			heading Proven Reliability
			paragraph
				StaticText Provide a safe, secure, and dependable checkout experience. With Forage, you don't have to worry about outages affecting valued customers.
			link Visit Status Page, url='https://status.joinforage.app/'
				button Visit Status Page
			image Proven Reliability, url='https://www.joinforage.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2F2ue7evhq%2Fproduction%2F83e48cbea1c8e8b76adc01673228f4cef8e79d80-1554x976.png%3Fw%3D2600%26fit%3Dmax%26auto%3Dformat&w=3840&q=100'
			separator, orientation='horizontal'
			heading GROW YOUR BUSINESS
			heading Better Reporting
			paragraph
				StaticText Forage is an EBT payment processor with built-in merchant tooling and analytics. With our Merchant Dashboard, our partners can better understand and grow their online EBT business.
			link Book a Demo, url='https://www.joinforage.com/contact'
				button Book a Demo
			image Better Reporting, url='https://www.joinforage.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2F2ue7evhq%2Fproduction%2F12f25e9f53d7d35ddf0c9f71e097084a8b2c9e34-5120x3136.png%3Fw%3D2600%26fit%3Dmax%26auto%3Dformat&w=3840&q=100'
			heading SAFEGUARD YOUR BUSINESS
			heading Fraud Prevention & Protection
			paragraph
				StaticText Forage partners directly with the USDA to deploy industry-leading fraud protection measures, from preventing balance check fraud and rate limiting, to IP address detection and shutting down bot activity.
			link Book a Demo, url='https://www.joinforage.com/contact'
				button Book a Demo
			image Fraud Prevention & Protection, url='https://www.joinforage.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2F2ue7evhq%2Fproduction%2Ff978aad1a370eaf73300ccd4b6406839d8a35e7b-5120x3136.png%3Fw%3D2600%26fit%3Dmax%26auto%3Dformat&w=3840&q=100'
			heading CUSTOMIZE YOUR CHECKOUT
			heading Seamless Integrations
			paragraph
				StaticText Build a completely customizable, native EBT checkout UI with Forage's SDKs. With Forage, merchants can significantly reduce complexity and integration time, all while controlling the complete checkout experience.
			link Book a Demo, url='https://www.joinforage.com/contact'
				button Book a Demo
			image Seamless Integrations, url='https://www.joinforage.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2F2ue7evhq%2Fproduction%2F738506e7cf4c1dfd0f2cc78187b820e657014fcd-3840x2352.jpg%3Fw%3D2600%26fit%3Dmax%26auto%3Dformat&w=3840&q=100'
			separator, orientation='horizontal'
			heading SHOPIFY INTEGRATION
			heading Accelerated Launch
			paragraph
				StaticText Upon receiving approval from USDA FNS, merchants on Shopify can directly integrate with Forage and directly enable EBT payments. With Forage, Shopify merchants can accept EBT SNAP, EBT Cash, and credit/debit card payments in an all-in-one solution.
			link Shopify Integration, url='https://apps.shopify.com/ebt'
				button Shopify Integration
			image Accelerated Launch, url='https://www.joinforage.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2F2ue7evhq%2Fproduction%2Fd04e92c2f422b5742bd86758ffbdead904371633-1280x784.jpg%3Fw%3D2600%26fit%3Dmax%26auto%3Dformat&w=3840&q=100'
			heading TESTIMONIALS
			heading See why a growing number of retailers & platforms choose Forage
			link Homesome, url='https://www.homesome.com/'
				image Homesome, url='https://cdn.sanity.io/images/2ue7evhq/production/b26ee0e1487d9ed15f41d4e633c7620ebcf0f756-144x29.svg'
			paragraph
				StaticText “When choosing who to work with to enable EBT online, it was an easy decision. With Forage, you get superior technology, USDA approval knowledge, and a streamlined process for onboarding new merchants. Forage is the only player in the space that has a scalable solution.”
			StaticText Rahul Chabukswar
			StaticText Founder & Chief Executive Officer
			link DoorDash, url='https://www.doordash.com/'
				image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			paragraph
				StaticText "Our partnership with Forage supports our commitment to increase access to food for vulnerable communities. Growing the acceptance of SNAP/EBT payments on DoorDash can help families meet childcare and work obligations, relieve seniors of the potential stress of going to the grocery store, and support people with disabilities who face mobility issues. We’re thrilled to further broaden access to food with on-demand delivery via DoorDash."
			StaticText Fuad Hannon
			StaticText VP of New Verticals
			link Uber, url='https://www.ubereats.com/'
				image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			paragraph
				StaticText “At Uber, we believe healthy foods should be accessible to all. We are excited to partner with Forage to provide our customers the same seamless payments experience they've become accustomed to on Uber when using their SNAP benefits.”
			StaticText Karl Hebert
			StaticText Vice President of Payments, Risk, and Identity
			link Thrive Market, url='https://thrivemarket.com/'
				image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			paragraph
				StaticText "We handpicked Forage as our payment processor for their exclusive USDA approval and strong integration capabilities. Their seasoned team, specializing in government payments, played a pivotal role in our effort to become the first online-only retailer to accept SNAP EBT."
			StaticText Sasha Siddhartha
			StaticText Co-Founder & Chief Technology Officer
			link Flashfood, url='https://www.flashfood.com/'
				image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			paragraph
				StaticText “It is critical to our mission that our app is available and accessible to as many people as possible. Our friends at Forage have helped enable EBT, which ultimately expands families' food budgets as wide as possible. Together, this can make a real difference in the lives of our shoppers."
			StaticText Nicholas Bertram
			StaticText CEO & President
			button
			button
		heading Begin accepting EBT SNAP and EBT Cash.
		paragraph
			StaticText Learn how Forage unlocks new revenue streams for merchants of all shapes and sizes.
		link Contact Us, url='https://www.joinforage.com/contact'
			button Contact Us
		link Learn More, url='https://www.joinforage.com/products/ebt'
			button Learn More
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-blueberries.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-apples.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-cereal.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-eggs.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-kiwis.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-bread.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-tomatoes.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-limes.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-salmon.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-blueberries.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-apples.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-cereal.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-eggs.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-kiwis.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-bread.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-tomatoes.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-limes.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-salmon.jpg&w=1920&q=75'
		link Forage, url='https://www.joinforage.com/'
			image
		navigation
			StaticText Product
			link Online EBT Payments, url='https://www.joinforage.com/products/online-ebt-payments'
			link In-Store EBT Payments, url='https://www.joinforage.com/products/in-store-ebt-payments'
			link API ↗, url='https://docs.joinforage.app/reference/introduction'
				superscript
			link Quick Start ↗, url='https://docs.joinforage.app/docs/overview'
				superscript
			link USDA-approved ↗, url='https://www.fns.usda.gov/snap/online-purchasing-retailers-technical-qas'
				superscript
		navigation
			StaticText Company
			link About, url='https://www.joinforage.com/about'
			link Careers ↗, url='https://boards.greenhouse.io/joinforage'
				superscript
			link Newsroom, url='https://www.joinforage.com/newsroom'
			link Partners, url='https://www.joinforage.com/partners'
			link Resources, url='https://www.joinforage.com/products/forage-ebook'
		navigation
			StaticText Support
			link FAQs, url='https://www.joinforage.com/faq'
			link Contact, url='https://www.joinforage.com/contact'
			link Privacy, url='https://www.joinforage.com/privacy'
			link Status ↗, url='https://status.joinforage.app/'
				superscript
		navigation
			link, url='https://github.com/teamforage'
			link, url='https://twitter.com/joinforage'
			link, url='https://linkedin.com/company/foragepayments'
			link, url='https://apps.shopify.com/ebt'
		link ALL SYSTEMS OPERATIONAL, url='https://status.joinforage.app/'
		StaticText Forage is equal opportunity. ©
		StaticText 2025
		StaticText Forage Technology Corporation, Inc.
		navigation
			navigation
				link Privacy Policy, url='https://www.joinforage.com/privacy'
			navigation
				link Terms of Use, url='https://www.joinforage.com/terms-of-use'
			navigation
				link Cookie Statement, url='https://www.joinforage.com/cookie-statement'
	alert, atomic
		StaticText Online EBT Payments | Forage
```
</details>

**Reasoning for action:** My reasoning for taking this action was to access the specific information about Forage's online EBT payments, as required by the user. By clicking on the 'Online EBT Payments' option (identified as menu item 1406), I am initiating a navigation to the relevant page that contains comprehensive details about integrating EBT payments into a business, which is a key step towards fulfilling the user's goal.

**Action:** click(1406) # Click on the Online EBT Payments option to learn more about this service.

**Change Description:** The browser switched to a new page titled 'Online EBT Payments | Forage', changing the URL to 'https://www.joinforage.com/products/online-ebt-payments', and updated the displayed content to provide detailed information about the online EBT payment service, including headings, paragraphs, and various images relevant to the service.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.joinforage.com/products/online-ebt-payments

https://docs.joinforage.app/docs/android

**Content (before/after):** 

```
RootWebArea Online EBT Payments | Forage, focused, url='https://www.joinforage.com/products/online-ebt-payments'
	main
		navigation
			[1438] link Forage, center=(517,30), url='https://www.joinforage.com/'
				image
```
<details><summary>Show more</summary>

```
			navigation
				generic, hasPopup='menu'
					[1443] button Products, center=(704,30)
				generic, hasPopup='menu'
					[1463] button Partners, center=(811,30)
				generic, hasPopup='menu'
					[1477] button Resources, center=(922,30)
				generic, hasPopup='menu'
					[1495] button Developers, center=(1042,30)
				[1510] button Pricing, center=(1141,30)
					link Pricing, url='https://www.joinforage.com/pricing'
				[1512] button Company, center=(1225,30)
					link Company, url='https://www.joinforage.com/about'
			[1515] link Get started, center=(1405,30), url='https://www.joinforage.com/contact'
				button Get started
			navigation
				generic, hasPopup='menu'
					button Products
				generic, hasPopup='menu'
					button Partners
				generic, hasPopup='menu'
					button Resources
				generic, hasPopup='menu'
					button Developers
				button Pricing
					link Pricing, url='https://www.joinforage.com/pricing'
				button Company
					link Company, url='https://www.joinforage.com/about'
		article
			heading Unlock EBT payments online.
			paragraph
				StaticText Start accepting EBT SNAP and EBT Cash payments online.
			[1607] link Contact Us, center=(888,314), url='https://www.joinforage.com/contact'
				button Contact Us
			[1610] link Learn More, center=(1030,315), url='https://docs.joinforage.app/docs/android'
				button Learn More
			image Unlock EBT payments online., url='https://www.joinforage.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2F2ue7evhq%2Fproduction%2Ffc98362354a770eac365348a446176d87e199692-2400x1340.png%3Fw%3D2600%26fit%3Dmax%26auto%3Dformat&w=3840&q=100'
			heading TRUSTED BY MERCHANTS OF ALL SHAPES AND SIZES
			image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
			image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
			image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
			image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
			image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
			image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
			image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
			image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
			image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
			image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
			image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
			image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
			image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
			image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
			image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
			image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
			image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
			image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
			image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
			image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
			image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
			image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
			image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
			image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
			image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
			image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
			image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
			image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
			image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
			image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
			image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
			image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
			image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
			image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
			image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
			image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
			image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
			image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
			image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
			image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
			image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
			image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
			image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
			image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
			image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
			image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
			image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
			image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
			image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
			image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
			image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
			image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
			image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
			image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
			image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
			image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
			image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
			image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
			image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
			image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
			image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
			image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
			image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
			image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
			image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
			image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
			image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
			image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
			image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
			image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
			image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
			image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
			image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
			image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
			image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
			image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
			image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
			image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
			image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
			image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
			image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
			image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
			image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
			image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
			image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
			image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
			image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
			image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
			image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
			image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
			image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
			image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			image Gopuff, url='https://cdn.sanity.io/images/2ue7evhq/production/2c014de1bd98b2db516d76be040a5773f4b54970-2171x737.svg'
			image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			image Albertsons, url='https://cdn.sanity.io/images/2ue7evhq/production/79ab3030e1927cd097d2a541dacc600e3540921d-1264x615.svg'
			image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			image Dollar General, url='https://cdn.sanity.io/images/2ue7evhq/production/7001a000e9343d10c7aba843a015b608f0b8248b-1334x1334.svg'
			image Safeway, url='https://cdn.sanity.io/images/2ue7evhq/production/deb184f28916e880d3c5eb3127d0687c603e9ccb-1024x188.svg'
			image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			image Walgreens, url='https://cdn.sanity.io/images/2ue7evhq/production/098674f0de9f9121421d88015782d52f97402e17-750x208.svg'
			image Southeastern Grocers, url='https://cdn.sanity.io/images/2ue7evhq/production/86fdb0b2c3571ec5e7b9b803b6e1f3bfdf2922c4-500x300.svg'
			image Meijer, url='https://cdn.sanity.io/images/2ue7evhq/production/645a9be2d816b2f9d009317e4e348cb4f4e43e6d-76x30.svg'
			image Shopify, url='https://cdn.sanity.io/images/2ue7evhq/production/22713c54f134f4b79846860d9c45b4b724e007be-74x28.svg'
			image Tops, url='https://cdn.sanity.io/images/2ue7evhq/production/da5a40407e0e48da15f6f19b919ececdba2dde3b-91x24.svg'
			image Postmates, url='https://cdn.sanity.io/images/2ue7evhq/production/110834dc7e889975ab42425f3c52a856379d3ebe-1200x675.svg'
			image Giant Eagle, url='https://cdn.sanity.io/images/2ue7evhq/production/53698a0aab7b9f71d58951d444ab49fcab4be9db-1000x341.svg'
			image Save Mart, url='https://cdn.sanity.io/images/2ue7evhq/production/1083a131a0571eef7d2cac42f5456da064bc3a56-900x500.svg'
			image Vons, url='https://cdn.sanity.io/images/2ue7evhq/production/62fe324b2acb8078f7a24c91885ee69a37f619e2-2560x970.svg'
			image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			separator, orientation='horizontal'
			heading SIMPLIFYING CHECKOUT
			heading Best-In-Class UX
			paragraph
				StaticText Deliver seamless payment experiences for your customers. Increase conversion rates and drive more incremental EBT sales online with Forage.
			link Book a Demo, url='https://www.joinforage.com/contact'
				button Book a Demo
			image Best-In-Class UX, url='https://www.joinforage.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2F2ue7evhq%2Fproduction%2F502e7a61e1cabbe1eb81967db0a3a32d8e02f126-5120x3136.png%3Fw%3D2600%26fit%3Dmax%26auto%3Dformat&w=3840&q=100'
			heading MODERN INFRASTRUCTURE
			heading Proven Reliability
			paragraph
				StaticText Provide a safe, secure, and dependable checkout experience. With Forage, you don't have to worry about outages affecting valued customers.
			link Visit Status Page, url='https://status.joinforage.app/'
				button Visit Status Page
			image Proven Reliability, url='https://www.joinforage.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2F2ue7evhq%2Fproduction%2F83e48cbea1c8e8b76adc01673228f4cef8e79d80-1554x976.png%3Fw%3D2600%26fit%3Dmax%26auto%3Dformat&w=3840&q=100'
			separator, orientation='horizontal'
			heading GROW YOUR BUSINESS
			heading Better Reporting
			paragraph
				StaticText Forage is an EBT payment processor with built-in merchant tooling and analytics. With our Merchant Dashboard, our partners can better understand and grow their online EBT business.
			link Book a Demo, url='https://www.joinforage.com/contact'
				button Book a Demo
			image Better Reporting, url='https://www.joinforage.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2F2ue7evhq%2Fproduction%2F12f25e9f53d7d35ddf0c9f71e097084a8b2c9e34-5120x3136.png%3Fw%3D2600%26fit%3Dmax%26auto%3Dformat&w=3840&q=100'
			heading SAFEGUARD YOUR BUSINESS
			heading Fraud Prevention & Protection
			paragraph
				StaticText Forage partners directly with the USDA to deploy industry-leading fraud protection measures, from preventing balance check fraud and rate limiting, to IP address detection and shutting down bot activity.
			link Book a Demo, url='https://www.joinforage.com/contact'
				button Book a Demo
			image Fraud Prevention & Protection, url='https://www.joinforage.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2F2ue7evhq%2Fproduction%2Ff978aad1a370eaf73300ccd4b6406839d8a35e7b-5120x3136.png%3Fw%3D2600%26fit%3Dmax%26auto%3Dformat&w=3840&q=100'
			heading CUSTOMIZE YOUR CHECKOUT
			heading Seamless Integrations
			paragraph
				StaticText Build a completely customizable, native EBT checkout UI with Forage's SDKs. With Forage, merchants can significantly reduce complexity and integration time, all while controlling the complete checkout experience.
			link Book a Demo, url='https://www.joinforage.com/contact'
				button Book a Demo
			image Seamless Integrations, url='https://www.joinforage.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2F2ue7evhq%2Fproduction%2F738506e7cf4c1dfd0f2cc78187b820e657014fcd-3840x2352.jpg%3Fw%3D2600%26fit%3Dmax%26auto%3Dformat&w=3840&q=100'
			separator, orientation='horizontal'
			heading SHOPIFY INTEGRATION
			heading Accelerated Launch
			paragraph
				StaticText Upon receiving approval from USDA FNS, merchants on Shopify can directly integrate with Forage and directly enable EBT payments. With Forage, Shopify merchants can accept EBT SNAP, EBT Cash, and credit/debit card payments in an all-in-one solution.
			link Shopify Integration, url='https://apps.shopify.com/ebt'
				button Shopify Integration
			image Accelerated Launch, url='https://www.joinforage.com/_next/image?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2F2ue7evhq%2Fproduction%2Fd04e92c2f422b5742bd86758ffbdead904371633-1280x784.jpg%3Fw%3D2600%26fit%3Dmax%26auto%3Dformat&w=3840&q=100'
			heading TESTIMONIALS
			heading See why a growing number of retailers & platforms choose Forage
			link Homesome, url='https://www.homesome.com/'
				image Homesome, url='https://cdn.sanity.io/images/2ue7evhq/production/b26ee0e1487d9ed15f41d4e633c7620ebcf0f756-144x29.svg'
			paragraph
				StaticText “When choosing who to work with to enable EBT online, it was an easy decision. With Forage, you get superior technology, USDA approval knowledge, and a streamlined process for onboarding new merchants. Forage is the only player in the space that has a scalable solution.”
			StaticText Rahul Chabukswar
			StaticText Founder & Chief Executive Officer
			link DoorDash, url='https://www.doordash.com/'
				image DoorDash, url='https://cdn.sanity.io/images/2ue7evhq/production/4d7f1a1a2ffda74a8350b496eb19d5dc4442e4eb-322x156.svg'
			paragraph
				StaticText "Our partnership with Forage supports our commitment to increase access to food for vulnerable communities. Growing the acceptance of SNAP/EBT payments on DoorDash can help families meet childcare and work obligations, relieve seniors of the potential stress of going to the grocery store, and support people with disabilities who face mobility issues. We’re thrilled to further broaden access to food with on-demand delivery via DoorDash."
			StaticText Fuad Hannon
			StaticText VP of New Verticals
			link Uber, url='https://www.ubereats.com/'
				image Uber, url='https://cdn.sanity.io/images/2ue7evhq/production/dbd9e6963a71b1c1e664264430a13ab86991b850-5275x1850.svg'
			paragraph
				StaticText “At Uber, we believe healthy foods should be accessible to all. We are excited to partner with Forage to provide our customers the same seamless payments experience they've become accustomed to on Uber when using their SNAP benefits.”
			StaticText Karl Hebert
			StaticText Vice President of Payments, Risk, and Identity
			link Thrive Market, url='https://thrivemarket.com/'
				image Thrive Market, url='https://cdn.sanity.io/images/2ue7evhq/production/00efe012bb28f11f06fdf16481c3b86a6ce487e0-1024x336.svg'
			paragraph
				StaticText "We handpicked Forage as our payment processor for their exclusive USDA approval and strong integration capabilities. Their seasoned team, specializing in government payments, played a pivotal role in our effort to become the first online-only retailer to accept SNAP EBT."
			StaticText Sasha Siddhartha
			StaticText Co-Founder & Chief Technology Officer
			link Flashfood, url='https://www.flashfood.com/'
				image Flashfood, url='https://cdn.sanity.io/images/2ue7evhq/production/d2e4f8109a6c2a1eb18625efa79d8e609d81d99a-4734x1063.svg'
			paragraph
				StaticText “It is critical to our mission that our app is available and accessible to as many people as possible. Our friends at Forage have helped enable EBT, which ultimately expands families' food budgets as wide as possible. Together, this can make a real difference in the lives of our shoppers."
			StaticText Nicholas Bertram
			StaticText CEO & President
			button
			button
		heading Begin accepting EBT SNAP and EBT Cash.
		paragraph
			StaticText Learn how Forage unlocks new revenue streams for merchants of all shapes and sizes.
		link Contact Us, url='https://www.joinforage.com/contact'
			button Contact Us
		link Learn More, url='https://www.joinforage.com/products/ebt'
			button Learn More
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-blueberries.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-apples.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-cereal.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-eggs.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-kiwis.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-bread.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-tomatoes.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-limes.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-salmon.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-blueberries.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-apples.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-cereal.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-eggs.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-kiwis.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-bread.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-tomatoes.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-limes.jpg&w=1920&q=75'
		image Get Started, url='https://www.joinforage.com/_next/image?url=%2Ftemp_images%2Fsquare-salmon.jpg&w=1920&q=75'
		link Forage, url='https://www.joinforage.com/'
			image
		navigation
			StaticText Product
			link Online EBT Payments, url='https://www.joinforage.com/products/online-ebt-payments'
			link In-Store EBT Payments, url='https://www.joinforage.com/products/in-store-ebt-payments'
			link API ↗, url='https://docs.joinforage.app/reference/introduction'
				superscript
			link Quick Start ↗, url='https://docs.joinforage.app/docs/overview'
				superscript
			link USDA-approved ↗, url='https://www.fns.usda.gov/snap/online-purchasing-retailers-technical-qas'
				superscript
		navigation
			StaticText Company
			link About, url='https://www.joinforage.com/about'
			link Careers ↗, url='https://boards.greenhouse.io/joinforage'
				superscript
			link Newsroom, url='https://www.joinforage.com/newsroom'
			link Partners, url='https://www.joinforage.com/partners'
			link Resources, url='https://www.joinforage.com/products/forage-ebook'
		navigation
			StaticText Support
			link FAQs, url='https://www.joinforage.com/faq'
			link Contact, url='https://www.joinforage.com/contact'
			link Privacy, url='https://www.joinforage.com/privacy'
			link Status ↗, url='https://status.joinforage.app/'
				superscript
		navigation
			link, url='https://github.com/teamforage'
			link, url='https://twitter.com/joinforage'
			link, url='https://linkedin.com/company/foragepayments'
			link, url='https://apps.shopify.com/ebt'
		link ALL SYSTEMS OPERATIONAL, url='https://status.joinforage.app/'
		StaticText Forage is equal opportunity. ©
		StaticText 2025
		StaticText Forage Technology Corporation, Inc.
		navigation
			navigation
				link Privacy Policy, url='https://www.joinforage.com/privacy'
			navigation
				link Terms of Use, url='https://www.joinforage.com/terms-of-use'
			navigation
				link Cookie Statement, url='https://www.joinforage.com/cookie-statement'
	alert, atomic
		StaticText Online EBT Payments | Forage
```
</details>



```
RootWebArea Android, focused, url='https://docs.joinforage.app/docs/android'
	banner
		generic Jump to Content, focused
			link Jump to Content, url='https://docs.joinforage.app/docs/android#content'
		[164] link Forage, center=(319,32), url='https://docs.joinforage.app/'
```
<details><summary>Show more</summary>

```
			image Forage, url='https://files.readme.io/ea31cdc-small-Forage_Lockup_Green.png'
		[196] link Log In, center=(1589,32), url='https://docs.joinforage.app/login?redirect_uri=/docs/android'
		[198] button Toggle to light mode, center=(1645,32), expanded=False, hasPopup='dialog', type=button
			image Toggle to light mode
			image Toggle to light mode
		navigation
			[210] button v2024-08-30 , center=(331,86), expanded=False, hasPopup='dialog', inner_text=v2024-08-30, type=button
			[213] link  Home, center=(453,86), inner_text=Home, url='https://docs.joinforage.app/'
			[216] link  Guides, center=(553,86), inner_text=Guides, url='https://docs.joinforage.app/docs'
			[219] link  Reference, center=(670,86), inner_text=Reference, url='https://docs.joinforage.app/reference'
		[227] button Search ⌘k, center=(1585,86), inner_text=Search
CTRL-K
			StaticText 
			StaticText CTRL-K
	main
		navigation Page navigation
			heading HOW FORAGE WORKS
			list
				listitem
					[261] link Overview, center=(380,170), url='https://docs.joinforage.app/docs/overview'
				listitem
					[265] link EBT payments 101, center=(380,198), url='https://docs.joinforage.app/docs/ebt-online-101'
				listitem
					[269] link Explore integration options, center=(380,228), url='https://docs.joinforage.app/docs/get-started'
				listitem
					[273] link Show subpages for Set up Set up, center=(380,256), inner_text=Set up, url='https://docs.joinforage.app/docs/sign-up-for-forage'
						button Show subpages for Set up, expanded=False
							StaticText 
			heading QUICKSTARTS
			list
				listitem
					[299] link Show subpages for Custom Custom, center=(380,338), inner_text=Custom, url='https://docs.joinforage.app/docs/custom'
						button Show subpages for Custom, expanded=False
							StaticText 
				listitem
					[310] link Show subpages for Fully Hosted Fully Hosted, center=(380,368), inner_text=Fully Hosted, url='https://docs.joinforage.app/docs/fully-hosted'
						button Show subpages for Fully Hosted, expanded=False
							StaticText 
				listitem
					[321] link Hide subpages for Online-only SDKs Online-only SDKs, center=(380,396), inner_text=Online-only SDKs, url='https://docs.joinforage.app/docs/android'
						button Hide subpages for Online-only SDKs, expanded=True
							StaticText 
					list
						listitem
							[328] link Hide subpages for Android Android, center=(388,426), inner_text=Android, url='https://docs.joinforage.app/docs/android'
								button Hide subpages for Android, expanded=True
									StaticText 
							list
								listitem
									[335] link Android Quickstart, center=(395,454), url='https://docs.joinforage.app/docs/forage-android-quickstart'
								listitem
									[339] link How to style Forage Android Elements, center=(395,494), url='https://docs.joinforage.app/docs/forage-android-styling-guide'
						listitem
							[343] link Show subpages for JS JS, center=(388,538), inner_text=JS, url='https://docs.joinforage.app/docs/forage-js'
								button Show subpages for JS, expanded=False
									StaticText 
						listitem
							[354] link Show subpages for iOS iOS, center=(388,568), inner_text=iOS, url='https://docs.joinforage.app/docs/ios'
								button Show subpages for iOS, expanded=False
									StaticText 
				listitem
					[369] link Show subpages for POS Terminal SDK POS Terminal SDK, center=(380,602), inner_text=POS Terminal SDK, url='https://docs.joinforage.app/docs/pos-terminal-sdk'
						button Show subpages for POS Terminal SDK, expanded=False
							StaticText 
			heading IMPLEMENTATION GUIDES
			list
				listitem
					[383] link Defer EBT payment capture and refund completion to the server, center=(380,694), url='https://docs.joinforage.app/docs/capture-ebt-payments-server-side'
				listitem
					[387] link Process EBT SNAP refunds, center=(380,734), url='https://docs.joinforage.app/docs/ebt-refunds'
				listitem
					[391] link Platform Settlement, center=(380,762), url='https://docs.joinforage.app/docs/platform-settlement'
				listitem
					[395] link Receipts and confirmation screens, center=(380,792), url='https://docs.joinforage.app/docs/receipts'
				listitem
					[399] link Restrict Forms of Tender, center=(380,820), url='https://docs.joinforage.app/docs/supported-benefits'
				listitem
					[403] link Reuse Payment Methods, center=(380,850), url='https://docs.joinforage.app/docs/reusing-payment-methods'
				listitem
					[407] link Taxes, center=(380,878), url='https://docs.joinforage.app/docs/about-taxes'
				listitem
					[411] link Test EBT Cards, center=(380,908), url='https://docs.joinforage.app/docs/test-ebt-cards'
				listitem
					[415] link Generate file-based reports, center=(380,936), url='https://docs.joinforage.app/docs/generate-file-based-reports'
			StaticText Powered by
			[419] link ReadMe, center=(389,1006), url='https://readme.com/?ref_src=hub&project=forage'
				StaticText 
		article
			heading Android
			paragraph
				StaticText Accept EBT payments in your Android mobile app
			[430] link Suggest Edits, center=(1501,146), url='https://docs.joinforage.app/edit/android'
			paragraph
				StaticText You can use the Forage Android SDK to process EBT payments in your Android app.
			[436] button Two Android phone screens, one prompting for an EBT pin to process payment, the other prompting EBT PIN for balance inquiry, center=(951,558)
				image Two Android phone screens, one prompting for an EBT pin to process payment, the other prompting EBT PIN for balance inquiry, url='https://files.readme.io/114b189-android.png'
			heading Features Skip link to Features
				[443] link Skip link to Features, center=(538,839), url='https://docs.joinforage.app/docs/android#features'
					StaticText 
			list
				[445] listitem, center=(966,891), inner_text=Native UI component for collecting and tokenizing a customer’s EBT Card number (also called the card PAN)
					ListMarker •
					StaticText Native UI component for collecting and tokenizing a customer’s EBT Card number (also called the card PAN)
				[446] listitem, center=(966,928), inner_text=Native UI component for collecting a customer’s EBT PIN
					ListMarker •
					StaticText Native UI component for collecting a customer’s EBT PIN
				[447] listitem, center=(966,954), inner_text=Built-in EBT Card number validation
					ListMarker •
					StaticText Built-in EBT Card number validation
				[448] listitem, center=(966,981), inner_text=Control over the styling of a native EBT checkout experience
					ListMarker •
					StaticText Control over the styling of a native EBT checkout experience
				[449] listitem, center=(966,1018), inner_text=API methods that collect and tokenize an EBT Card number, perform a balance check, and capture a payment
					ListMarker •
					StaticText API methods that collect and tokenize an EBT Card number, perform a balance check, and capture a payment
			heading Requirements Skip link to Requirements
				[454] link Skip link to Requirements, center=(538,1077), url='https://docs.joinforage.app/docs/android#requirements'
					StaticText 
			paragraph
				StaticText Before you can use the Forage Android SDK, make sure that you have:
			list
				listitem
					ListMarker •
					StaticText Met all of the
					link prerequisites for working with Forage, url='https://docs.joinforage.app/docs/overview#prerequisites'
				listitem
					ListMarker •
					StaticText Signed up for an account.
					link Contact us, url='https://www.joinforage.com/contact'
					StaticText if you don’t yet have one.
				listitem
					ListMarker •
					StaticText Built your Android app on Minimum API Level Android 5.0 (API level 21)
			blockquote
				heading ✅ Resources
					paragraph
				list
					listitem
						ListMarker •
						link GitHub repository, url='https://github.com/teamforage/forage-android-sdk'
					listitem
						ListMarker •
						link Quickstart, url='https://docs.joinforage.app/docs/forage-android-quickstart'
					listitem
						ListMarker •
						link Reference documentation, url='https://android.joinforage.app/'
			heading Starter code Skip link to Starter code
				link Skip link to Starter code, url='https://docs.joinforage.app/docs/android#starter-code'
					StaticText 
			paragraph
				StaticText After
				link installing the library, url='https://github.com/teamforage/forage-android-sdk#installation'
				StaticText , include either or both of the UI components in your application’s views.
			paragraph
				StaticText For example, the following snippet adds the EBT Card number element
				code ForagePanEditText
				StaticText :
			tablist, orientation='horizontal'
				tab XML, selected=True
			tabpanel
				button Copy Code
					StaticText 
					StaticText 
				code <?xml version="1.0" encoding="utf-8"?> <androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android" xmlns:app="http://schemas.android.com/apk/res-auto" android:layout_width="match_parent" android:layout_height="match_parent"> <com.joinforage.forage.android.ui.ForagePANEditText android:id="@+id/foragePanEditText" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_margin="16dp" app:layout_constraintBottom_toBottomOf="parent" app:layout_constraintEnd_toEndOf="parent" app:layout_constraintStart_toStartOf="parent" app:layout_constraintTop_toTopOf=
					StaticText android:textColor
					StaticText "?android:attr/textColor"
					StaticText android:textSize
					StaticText "?android:attr/textSize"
					StaticText app:panBoxStrokeColor
					StaticText "?attr/panBoxStrokeColor"
					StaticText app:panBoxStrokeWidthFocused
					StaticText "?attr/panBoxStrokeWidthFocused"
					StaticText app:panBoxStrokeWidth
					StaticText "?attr/panBoxStrokeWidth"
					StaticText app:cornerRadius
					StaticText "?attr/cornerRadius"
					StaticText app:textInputLayoutStyle
					StaticText "?attr/textInputLayoutStyle"
					StaticText />
					StaticText </
			paragraph
				StaticText Then, reference the element in response to a user action. The example below tokenizes the EBT Card number and could be included within an
				code onSubmit
				StaticText function:
			tablist, orientation='horizontal'
				tab Kotlin, selected=True
			tabpanel
				button Copy Code
					StaticText 
					StaticText 
				code // TokenizeViewModel.kt @HiltViewModel class TokenizeViewModel @Inject constructor( savedStateHandle: SavedStateHandle, private val moshi: Moshi ) : ViewModel() { private val args = TokenizeFragmentArgs.fromSavedStateHandle(savedStateHandle) // internal so that TokenizeFragment can access these values val merchantID = args.merchantAccount val sessionToken =
					StaticText fun
					StaticText tokenizeEBTCard
					StaticText foragePanEditText
					StaticText ForagePANEditText
					StaticText viewModelScope
					StaticText launch
					StaticText _isLoading
					StaticText true
					StaticText response
					StaticText ForageSDK
					StaticText ().
					StaticText tokenizeEBTCard
					StaticText TokenizeEBTCardParams
					StaticText foragePANEditText
					StaticText foragePanEditText
					StaticText reusable
					StaticText true
					StaticText // NOTE: The following line is for testing purposes only and should not be used in production.
					StaticText // Please replace this line with a real hashed customer ID value.
					StaticText customerId
					StaticText UUID
					StaticText randomUUID
					StaticText ().
					StaticText toString
					StaticText (),
					StaticText when
					StaticText response
					StaticText is
					StaticText ForageApiResponse
					StaticText Success
					StaticText ->
					StaticText adapter
					StaticText JsonAdapter
					StaticText <
					StaticText PaymentMethod
					StaticText >
					StaticText adapter
					StaticText PaymentMethod
					StaticText ::
					StaticText java
					StaticText paymentMethod
					StaticText adapter
					StaticText fromJson
					StaticText response
					StaticText data
					StaticText // (optional) do something with the ref
					StaticText saveToPaymentMethodRefToMyAPI
					StaticText paymentMethod
					StaticText ref
					StaticText }
					StaticText is
					StaticText ForageApiResponse
					StaticText Failure
					StaticText ->
					StaticText _error
					StaticText response
					StaticText message
					StaticText }
					StaticText }
					StaticText _isLoading
					StaticText false
					StaticText }
					StaticText }
			heading Next steps Skip link to Next steps
				link Skip link to Next steps, url='https://docs.joinforage.app/docs/android#next-steps'
					StaticText 
			list
				listitem
					ListMarker •
					StaticText Check out the
					link forage-android-sdk GitHub repository, url='https://github.com/teamforage/forage-android-sdk'
					StaticText for full installation instructions and a demo app
			paragraph
				StaticText 
				StaticText Updated
				StaticText 7 months ago
			separator, orientation='horizontal'
			navigation Pagination Controls
				link Previous Page: Quickstart, url='https://docs.joinforage.app/docs/fully-hosted-quickstart'
					StaticText 
				link Next Page: Android Quickstart, url='https://docs.joinforage.app/docs/forage-android-quickstart'
					StaticText 
			LayoutTable
				StaticText Did this page help you?
				button  Yes, expanded=False, hasPopup='dialog'
				button  No, expanded=False, hasPopup='dialog'
			navigation
				list
					[689] listitem, center=(1501,288), inner_text=TABLE OF CONTENTS
						link TABLE OF CONTENTS, url='https://docs.joinforage.app/docs/android#'
					listitem
						list
							listitem
								[695] link Features, center=(1501,322), url='https://docs.joinforage.app/docs/android#features'
							listitem
								[697] link Requirements, center=(1501,349), url='https://docs.joinforage.app/docs/android#requirements'
							listitem
								[699] link Starter code, center=(1501,377), url='https://docs.joinforage.app/docs/android#starter-code'
							listitem
								[701] link Next steps, center=(1501,404), url='https://docs.joinforage.app/docs/android#next-steps'
	contentinfo Status banner
```
</details>

**Reasoning for action:** I clicked on the Learn More button because doing so was necessary to advance the user's goal of understanding how to integrate EBT payments into their business. This action would take me from the Products page to a detailed information page about EBT services, specifically leading me to the Android documentation that offers the implementation instructions needed to proceed with the integration.

**Action:** click(1610) # Click on the Learn More button to gather additional information about EBT payments.

**Change Description:** After clicking the 'Learn More' button, the browser transitioned from the Online EBT Payments page to the Android documentation page of Forage, displaying information about EBT payments for Android applications, including features, requirements, and implementation guides.

**Screenshot before:****Screenshot after:**---


# Task

**Explore Playlists on Sonauto**

As a music enthusiast,
I explore and discover new playlists on Sonauto,
so that I can enjoy curated music that fits my mood.

**Success definition:** Given I am on the Sonauto homepage and have multiple playlists displayed
When I click on the 'Just Relax' playlist and then the 'Dark Radio Network' playlist
Then I should see the content and details for the 'Just Relax' playlist followed by the content and details for the 'Dark Radio Network' playlist.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://sonauto.ai/

https://sonauto.ai/

**Content (before/after):** 

```
RootWebArea Sonauto | New Music by You, focused, url='https://sonauto.ai/'
	alert, atomic
	paragraph
		StaticText Welcome to Sonauto v2 beta! Your v1 generations will be available for a limited time at
		[52] link v1.sonauto.ai, center=(1276,28), url='https://v1.sonauto.ai/'
```
<details><summary>Show more</summary>

```
		StaticText .
	[53] button, center=(1884,28)
		image
	[59] link Sonauto Logo Sonauto, center=(126,96), inner_text=Sonauto, url='https://sonauto.ai/'
		image Sonauto Logo, url='https://sonauto.ai/_next/image?url=%2Fimages%2Fnew_bird.png&w=32&q=75'
	navigation
		[62] link Home, center=(128,150), url='https://sonauto.ai/'
			image
		[64] link Search, center=(128,186), url='https://sonauto.ai/search'
			image
		[66] link Make Music, center=(128,222), url='https://sonauto.ai/'
			image
	paragraph
		StaticText Trending
	[71] button Playlist, center=(194,283)
		image
	[75] combobox value='All', center=(128,325), expanded=False, hasPopup='listbox', inner_text=All, type=button
	[80] link art Just Relax, center=(128,381), inner_text=Just Relax, url='https://sonauto.ai/playlist/ab0f22f8-64c6-454b-9a12-fb14f4d48465'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-ab0f22f8-64c6-454b-9a12-fb14f4d48465?width=32&quality=75&resize=contain'
	[83] link art Dark Radio Network, center=(128,417), inner_text=Dark Radio Network, url='https://sonauto.ai/playlist/65fdf34c-28d5-47dc-801c-f156a78638d4'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-65fdf34c-28d5-47dc-801c-f156a78638d4?width=32&quality=75&resize=contain'
	[86] link Test, center=(128,453), url='https://sonauto.ai/playlist/8f58dc22-0e35-42d3-bc0c-74a044c68f83'
	[89] link My list, center=(128,489), url='https://sonauto.ai/playlist/7dd42422-563f-4e2d-95f0-62e8ac4ac0df'
	[92] link art GREEN BITES, center=(128,525), inner_text=GREEN BITES, url='https://sonauto.ai/playlist/476f7f74-0f8a-4100-ab4a-ead30aa554df'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-937b0f24-7aaa-4357-9e04-43488dddf699?width=32&quality=75&resize=contain'
	[95] link art Klangraum V2 Tests, center=(128,561), inner_text=Klangraum V2 Tests, url='https://sonauto.ai/playlist/a1f1dd9b-e58f-4812-a1e6-024e69f1af37'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-a1f1dd9b-e58f-4812-a1e6-024e69f1af37?width=32&quality=75&resize=contain'
	[98] link My songs, center=(128,597), url='https://sonauto.ai/playlist/f580ce69-e977-4810-92b3-4f4815c4b86f'
	[101] link The Show, center=(128,633), url='https://sonauto.ai/playlist/ae20fb05-042d-4032-b27d-e71785eeda08'
	[104] link art DID HE, center=(128,669), inner_text=DID HE, url='https://sonauto.ai/playlist/dbbd1058-a2eb-41cf-bd30-c350b1dfde90'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-dbbd1058-a2eb-41cf-bd30-c350b1dfde90?width=32&quality=75&resize=contain'
	[107] link cool, center=(128,705), url='https://sonauto.ai/playlist/5491c699-3f58-4762-913f-ffe690282a63'
	[110] link Luis, center=(128,741), url='https://sonauto.ai/playlist/6831c1cb-0828-4eec-95cc-dfdba071eae7'
	[113] link tyghghhg, center=(128,777), url='https://sonauto.ai/playlist/b46544c7-931f-434e-a501-4aa23e37a89f'
	link art Bluesman420 Fan Club, url='https://sonauto.ai/group/c97cd6bf-475b-447c-8db4-11a9dc2d526a'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1507227c-e538-4a01-9ec0-967a0ac68902?width=32&quality=75&resize=contain'
	link art Various Instrumentals, url='https://sonauto.ai/group/998f8cf6-7740-42be-ab67-6e983502abb4'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-998f8cf6-7740-42be-ab67-6e983502abb4?width=32&quality=75&resize=contain'
	link art Dark Radio, url='https://sonauto.ai/group/87db116d-1613-4574-8785-fb2cb613d18f'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-87db116d-1613-4574-8785-fb2cb613d18f?width=32&quality=75&resize=contain'
	link art Rubinyan theme Song, url='https://sonauto.ai/group/e7c907fb-9324-4389-961b-59880d374568'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-e7c907fb-9324-4389-961b-59880d374568?width=32&quality=75&resize=contain'
	link Rescate Brasil, url='https://sonauto.ai/group/05ed4a63-e238-4c92-a11e-df5dfeec01e2'
	link my music, url='https://sonauto.ai/group/8c296cfa-ea98-45c1-9b62-338cb85f137a'
	link Mm, url='https://sonauto.ai/group/49828acd-64b5-46e5-b45f-a548172e3f64'
	link art vives, url='https://sonauto.ai/group/22fa8e47-8007-48b9-ab7d-159979cf6a2c'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-97cc5c0d-b5ef-4e7c-8fee-f02e3db5a3e8?width=32&quality=75&resize=contain'
	link Heavy metal, url='https://sonauto.ai/group/f7f4e492-9701-4af9-98de-610c00d6e8e9'
	link art Música, url='https://sonauto.ai/group/2e28bd75-83ad-4055-b2d0-19fb1b687378'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-2e28bd75-83ad-4055-b2d0-19fb1b687378?width=32&quality=75&resize=contain'
	link art Davidounours, url='https://sonauto.ai/group/1a956452-71d5-4800-8a96-0ec8346bac0d'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-1a956452-71d5-4800-8a96-0ec8346bac0d?width=32&quality=75&resize=contain'
	link Hddjdh, url='https://sonauto.ai/group/9f5f4f3a-86aa-4e00-a270-b95e294c21c6'
	link Need For Speed Soundtrack, url='https://sonauto.ai/group/db78b071-5d27-49d6-af33-f115692bdaa6'
	link art Killer Raps, url='https://sonauto.ai/group/0a9833ea-3417-48fc-a11f-4a5669741ece'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-0a9833ea-3417-48fc-a11f-4a5669741ece?width=32&quality=75&resize=contain'
	link Так выбрать из балкона, url='https://sonauto.ai/group/9be2dbd8-08b6-4d09-bc72-c1981ba72277'
	link House, url='https://sonauto.ai/group/13f7e378-c201-4a6f-ad86-3b500505353b'
	link art Nothin but the Blues, url='https://sonauto.ai/group/d54b03a1-cd7b-4490-8900-81d49fc37f6e'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-d54b03a1-cd7b-4490-8900-81d49fc37f6e?width=32&quality=75&resize=contain'
	link art Le hobo, url='https://sonauto.ai/group/1148e019-c74c-4069-9b3c-f6cb290c3cf0'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-1148e019-c74c-4069-9b3c-f6cb290c3cf0?width=32&quality=75&resize=contain'
	link art Unusual Dubstep, url='https://sonauto.ai/group/ac84677c-9503-416f-a533-d5f05c9a2abc'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-ac84677c-9503-416f-a533-d5f05c9a2abc?width=32&quality=75&resize=contain'
	link art Cultural Mix & Crossovers, url='https://sonauto.ai/group/4bcec888-8969-43ac-a0c7-75fcd019db9f'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-4bcec888-8969-43ac-a0c7-75fcd019db9f?width=32&quality=75&resize=contain'
	link art Basement Dancefloor, url='https://sonauto.ai/group/b62764aa-2922-4b3e-8f6d-9a34871b391b'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-b62764aa-2922-4b3e-8f6d-9a34871b391b?width=32&quality=75&resize=contain'
	link art Universal Music, url='https://sonauto.ai/group/14a2e296-9039-48dd-a5b9-25578ba8b8e1'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-14a2e296-9039-48dd-a5b9-25578ba8b8e1?width=32&quality=75&resize=contain'
	[184] link Discord, center=(112,1005), url='https://discord.gg/pfXar3ChH8'
		image Discord icon, url='https://sonauto.ai/discord-white.svg'
	[186] link Twitter, center=(146,1005), url='https://x.com/SonautoAI'
		image Twitter icon, url='https://sonauto.ai/twitter-icon.svg'
	[189] link Terms, center=(97,1040), url='https://sonauto.ai/tos'
	StaticText ·
	[191] link Privacy, center=(156,1040), url='https://sonauto.ai/privacy'
	[196] button, center=(302,88)
		image
	[198] button, center=(342,88)
		image
	[201] link Install App, center=(1741,88), url='https://sonauto.ai/install'
		image
	[204] image, center=(1828,88)
	StaticText Log In
	main
		heading Start Your Masterpiece
		image
		[215] textbox A rock song about turtles flying, center=(1034,195), contenteditable=True, type=text
		[217] image, center=(1757,195)
		[218] button Generate, center=(1838,195)
		heading Instantly Create a Song
		[223] image, center=(542,249)
		[229] heading Pop, 2020s, Summer, Nu-Disco, center=(406,293)
		[232] heading [Miel San Marcos, Worship, Christian, Inspirational, Emotional, Male Vocalist, Female Vocalist, Piano, Electric Guitar, Drum Set, 2010s], center=(732,293)
		[235] heading Country, 2020s, Storytelling, Southern Rock, center=(1104,293)
		[238] heading Sentimental, Emotional, 1980s, Romantic, Melancholic, Pop, R&B, center=(1477,293)
		heading Guitar Virtuoso, Electric Blues, Texas Blues
		heading Blues, 1970s, Electric Blues
		heading Lo-Fi, Chillout, Downtempo
		heading A Blues Song Played By A Blues Power Trio. Incredible Guitar Solos With Heavy Bending. Thick Bass Tone.
		heading Blues, 1970s, Electric Blues
		heading Summer, Nu-Disco, 2020s, Romantic, Dance
		image
		[260] image, center=(1880,299)
		heading Groups For You
		[264] button Create a Group, center=(562,339)
			image
		[273] image Zaptrem's Group, center=(368,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-ee12a798-6b2f-4d90-9d4b-cd035d9a0a48?width=256&quality=75&resize=contain'
		[276] heading Zaptrem's Group, center=(530,402)
		[277] paragraph, center=(530,421), inner_text=7 Members
			StaticText 7
			StaticText Members
		paragraph
			StaticText Moderated by
			[279] link zaptrem, center=(566,441), url='https://sonauto.ai/artist/zaptrem'
		[280] paragraph, center=(530,469), inner_text=Feed me soooongs
			StaticText Feed me soooongs
		[282] button Play, center=(486,520)
			image
		[286] image Bluesman420 Fan Club, center=(734,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1507227c-e538-4a01-9ec0-967a0ac68902?width=256&quality=75&resize=contain'
		[289] heading Bluesman420 Fan Club, center=(900,413)
		[290] paragraph, center=(900,444), inner_text=5 Members
			StaticText 5
			StaticText Members
		paragraph
			StaticText Moderated by
			[292] link zaptrem, center=(932,463), url='https://sonauto.ai/artist/zaptrem'
		[293] paragraph, center=(900,492), inner_text=It's 106 miles to Chicago, we got a full tank of gas, half a pack of cigarettes, it's dark... and we're wearing sunglasses.
			StaticText It's 106 miles to Chicago, we got a full tank of gas, half a pack of cigarettes, it's dark... and we're wearing sunglasses.
		[295] button Play, center=(852,526)
			image
		[299] image Weird & Wacky Texts & Topics, center=(1100,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-7c2da748-49a4-43c8-9f4a-432a2ae1c561?width=256&quality=75&resize=contain'
		[302] heading Weird & Wacky Texts & Topics, center=(1266,413)
		[303] paragraph, center=(1266,444), inner_text=4 Members
			StaticText 4
			StaticText Members
		paragraph
			StaticText Moderated by
			[305] link chaos, center=(1292,463), url='https://sonauto.ai/artist/chaos'
		[306] paragraph, center=(1266,492), inner_text=Can you really sing a song about that stuff? Yup. Sure can.
			StaticText Can you really sing a song about that stuff? Yup. Sure can.
		[308] button Play, center=(1218,526)
			image
		[312] image Nice Voice, center=(1466,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-82686aa1-5a53-42d6-bb86-80b71defb209?width=256&quality=75&resize=contain'
		[315] heading Nice Voice, center=(1632,402)
		[316] paragraph, center=(1632,421), inner_text=3 Members
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			[318] link chaos, center=(1658,441), url='https://sonauto.ai/artist/chaos'
		[319] paragraph, center=(1632,469), inner_text=If you think the voice sounds great and is good quality, put it here.
			StaticText If you think the voice sounds great and is good quality, put it here.
		[321] button Play, center=(1584,520)
			image
		image Tilted Dancefloor, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-841b4468-df7a-428d-80c4-9a8494c4cb87?width=256&quality=75&resize=contain'
		heading Tilted Dancefloor
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link chaos, url='https://sonauto.ai/artist/chaos'
		paragraph
			StaticText Energetic with a twist of humor
		button Play
			image
		image Dark Synthwave, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1a7fa429-74d3-40f0-bac1-c78594847bb5?width=256&quality=75&resize=contain'
		heading Dark Synthwave
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link hayden, url='https://sonauto.ai/artist/hayden'
		paragraph
			StaticText Dark electronic melodic metal and synthwave
		button Play
			image
		image Chill Vibes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-6afa6e51-c830-45e9-8f71-032a1c50ec83?width=256&quality=75&resize=contain'
		heading Chill Vibes
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link hayden, url='https://sonauto.ai/artist/hayden'
		paragraph
		button Play
			image
		image Various Instrumentals, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-998f8cf6-7740-42be-ab67-6e983502abb4?width=256&quality=75&resize=contain'
		heading Various Instrumentals
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link whosthere, url='https://sonauto.ai/artist/whosthere'
		paragraph
			StaticText For instrumentals lovers
		button Play
			image
		image Protest Songs, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-a4e4e13c-e498-4dd6-9957-df69d208a2d5?width=256&quality=75&resize=contain'
		heading Protest Songs
		paragraph
			StaticText 2
			StaticText Members
		paragraph
			StaticText Moderated by
			link chaos, url='https://sonauto.ai/artist/chaos'
		paragraph
			StaticText Old people shouting at the sky come here to vent.
		button Play
			image
		image
		[391] image, center=(1880,462)
		heading Staff Picks
		[396] button, center=(444,591)
			image
		[405] image Leavin' You Behind, center=(368,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-b03dcac9-65d8-41ab-a850-dda75cb88114?width=256&quality=75&resize=contain'
		[407] image, center=(318,770)
		StaticText v2
		[412] link Leavin' You Behind, center=(540,659), url='https://sonauto.ai/song/ab00865a-10e5-4993-a3d9-adbb4876beb9'
			heading Leavin' You Behind
		[408] div, center=(416,776), inner_text=v2
		[414] link zaptrem, center=(480,681), url='https://sonauto.ai/artist/zaptrem'
		[417] link summer, center=(490,724), url='https://sonauto.ai/tag/summer'
		[419] link 2020s, center=(562,724), url='https://sonauto.ai/tag/2020s'
		[421] link pop, center=(623,724), url='https://sonauto.ai/tag/pop'
		image
		paragraph
			StaticText 822
		[428] image, center=(524,754)
		paragraph
			StaticText 11
		[430] link 2, center=(578,754), url='https://sonauto.ai/song/ab00865a-10e5-4993-a3d9-adbb4876beb9'
			image
			paragraph
		[433] button, center=(617,754), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 6 days ago
		[440] image Alright, center=(783,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-668bf78d-dff4-4a22-8d5b-1a2bd48cf08e?width=256&quality=75&resize=contain'
		[442] image, center=(733,770)
		StaticText v2
		[447] link Alright, center=(900,659), url='https://sonauto.ai/song/cc599224-25b1-4521-bb7d-63d63addd13b'
			heading Alright
		[443] div, center=(832,776), inner_text=v2
		[449] link coolsong, center=(898,681), url='https://sonauto.ai/artist/coolsong'
		[452] link 2020s, center=(900,709), url='https://sonauto.ai/tag/2020s'
		[454] link country, center=(970,709), url='https://sonauto.ai/tag/country'
		[456] link southern rock, center=(922,742), url='https://sonauto.ai/tag/southern%20rock'
		image
		paragraph
			StaticText 205
		[463] image, center=(939,772)
		paragraph
			StaticText 5
		[465] link 2, center=(990,772), url='https://sonauto.ai/song/cc599224-25b1-4521-bb7d-63d63addd13b'
			image
			paragraph
		[468] button, center=(1029,772), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 5 days ago
		[475] image We Stand, center=(1198,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-e668a6b3-ccca-4c36-a2a3-e42035389e5e?width=256&quality=75&resize=contain'
		[477] image, center=(1148,770)
		StaticText v2
		[482] link We Stand, center=(1328,659), url='https://sonauto.ai/song/cdd77c72-99bd-4247-b83f-ecaae849fdd2'
			heading We Stand
		[478] div, center=(1246,776), inner_text=v2
		[484] link gonesvan, center=(1314,681), url='https://sonauto.ai/artist/gonesvan'
		[487] link male vocalist, center=(1335,709), url='https://sonauto.ai/tag/male%20vocalist'
		[489] link electric guitar, center=(1444,709), url='https://sonauto.ai/tag/electric%20guitar'
		[491] link christian, center=(1320,742), url='https://sonauto.ai/tag/christian'
		image
		paragraph
			StaticText 391
		[498] image, center=(1353,772)
		paragraph
			StaticText 6
		[500] link 2, center=(1404,772), url='https://sonauto.ai/song/cdd77c72-99bd-4247-b83f-ecaae849fdd2'
			image
			paragraph
		[503] button, center=(1444,772), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 7 days ago
		[510] image When it’s us, center=(1613,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-a7ed0653-8a2f-4408-85c5-7f5bb57f7d7f?width=256&quality=75&resize=contain'
		[512] image, center=(1563,770)
		StaticText v2
		[517] link When it’s us, center=(1754,659), url='https://sonauto.ai/song/edba394d-4003-4d9b-a960-0ad0b2ae2490'
			heading When it’s us
		[513] div, center=(1662,776), inner_text=v2
		[519] link gonesvan, center=(1730,681), url='https://sonauto.ai/artist/gonesvan'
		[522] link male vocalist, center=(1750,709), url='https://sonauto.ai/tag/male%20vocalist'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		[526] link k-ballad, center=(1735,742), url='https://sonauto.ai/tag/k-ballad'
		image
		paragraph
			StaticText 306
		[533] image, center=(1771,772)
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/edba394d-4003-4d9b-a960-0ad0b2ae2490'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Craving for Snacks, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_87490abc-2ad8-4a8c-b234-904c28fd30f1.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Craving for Snacks, url='https://sonauto.ai/song/87490abc-2ad8-4a8c-b234-904c28fd30f1'
			heading Craving for Snacks
		link chaos, url='https://sonauto.ai/artist/chaos'
		link country, url='https://sonauto.ai/tag/country'
		link bluegrass, url='https://sonauto.ai/tag/bluegrass'
		image
		paragraph
			StaticText 413
		image
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/87490abc-2ad8-4a8c-b234-904c28fd30f1'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Green Eyes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-da6fe498-0f13-4aa7-932c-02fbd81d328d?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Green Eyes, url='https://sonauto.ai/song/bf4c9cae-f33e-4dc5-a5a7-7abe63696448'
			heading Green Eyes
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link indie, url='https://sonauto.ai/tag/indie'
		link pop, url='https://sonauto.ai/tag/pop'
		link dance pop, url='https://sonauto.ai/tag/dance%20pop'
		image
		paragraph
			StaticText 269
		image
		paragraph
			StaticText 4
		link 0, url='https://sonauto.ai/song/bf4c9cae-f33e-4dc5-a5a7-7abe63696448'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Midnight Raid, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-5cc8897c-5900-4359-bcf4-ff6120b6ef8f?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Midnight Raid, url='https://sonauto.ai/song/9715ecb5-1865-46f9-b064-0e16725b4fa6'
			heading Midnight Raid
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link EDM, url='https://sonauto.ai/tag/EDM'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		link house, url='https://sonauto.ai/tag/house'
		image
		paragraph
			StaticText 312
		image
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/9715ecb5-1865-46f9-b064-0e16725b4fa6'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Crazy Friday Night, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-984cef64-d683-4743-935f-6ab8d8c9a828?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Crazy Friday Night, url='https://sonauto.ai/song/9e21b63b-0ac3-437c-88ae-05e57c67bd6f'
			heading Crazy Friday Night
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link pop, url='https://sonauto.ai/tag/pop'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		link party, url='https://sonauto.ai/tag/party'
		image
		paragraph
			StaticText 279
		image
		paragraph
			StaticText 4
		link 0, url='https://sonauto.ai/song/9e21b63b-0ac3-437c-88ae-05e57c67bd6f'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Don't Cry Now, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_ff718ead-ecb4-4348-8f0b-8d393bba657d.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Don't Cry Now, url='https://sonauto.ai/song/ff718ead-ecb4-4348-8f0b-8d393bba657d'
			heading Don't Cry Now
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link country, url='https://sonauto.ai/tag/country'
		link rock, url='https://sonauto.ai/tag/rock'
		link western, url='https://sonauto.ai/tag/western'
		image
		paragraph
			StaticText 244
		image
		paragraph
			StaticText 1
		link 0, url='https://sonauto.ai/song/ff718ead-ecb4-4348-8f0b-8d393bba657d'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Caught in the Past, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_f40f3424-273c-4770-8ff8-e2f455a932a2.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Caught in the Past, url='https://sonauto.ai/song/f40f3424-273c-4770-8ff8-e2f455a932a2'
			heading Caught in the Past
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link 2000s, url='https://sonauto.ai/tag/2000s'
		link pop, url='https://sonauto.ai/tag/pop'
		link breakup, url='https://sonauto.ai/tag/breakup'
		image
		paragraph
			StaticText 299
		image
		paragraph
			StaticText 5
		link 2, url='https://sonauto.ai/song/f40f3424-273c-4770-8ff8-e2f455a932a2'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image
		[752] image, center=(1880,729)
		heading Trending Posts
		[756] button, center=(494,878)
			image
		[758] combobox value='Trending', center=(584,878), expanded=False, hasPopup='listbox', inner_text=Trending, type=button
		grid
			gridcell 1970s Cop Movie Soundtrack v2 1970s Cop Movie Soundtrack whosthere blues rock lounge 8 1 0 Posted 3 hours ago
				[767] image 1970s Cop Movie Soundtrack, center=(368,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-164546f9-46c7-42ec-9570-20885dca42aa?width=256&quality=75&resize=contain'
				[769] image, center=(318,1060)
				StaticText v2
				[774] link 1970s Cop Movie Soundtrack, center=(584,949), url='https://sonauto.ai/song/44b0ed21-fe47-4856-a42f-a7ceb923dda2'
					heading 1970s Cop Movie Soundtrack
				[770] div, center=(416,1066), inner_text=v2
				[776] link whosthere, center=(486,971), url='https://sonauto.ai/artist/whosthere'
				[779] link blues rock, center=(497,1014), url='https://sonauto.ai/tag/blues%20rock'
				[781] link lounge, center=(578,1014), url='https://sonauto.ai/tag/lounge'
				image
				paragraph
					StaticText 8
				[788] image, center=(510,1044)
				paragraph
					StaticText 1
				[790] link 0, center=(559,1044), url='https://sonauto.ai/song/44b0ed21-fe47-4856-a42f-a7ceb923dda2'
					image
					paragraph
				[793] button, center=(599,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 3 hours ago
			gridcell Tyler's Pina Coladaburg v2 Tyler's Pina Coladaburg nlanza999 tropical 1970s island 3 0 0 Posted 4 hours ago
				[800] image Tyler's Pina Coladaburg, center=(914,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_4ce7e7ce-4970-4645-a910-b4a65d297259.webp?width=256&quality=75&resize=contain'
				[802] image, center=(864,1060)
				StaticText v2
				[807] link Tyler's Pina Coladaburg, center=(1108,949), url='https://sonauto.ai/song/4ce7e7ce-4970-4645-a910-b4a65d297259'
					heading Tyler's Pina Coladaburg
				[803] div, center=(962,1066), inner_text=v2
				[809] link nlanza999, center=(1032,971), url='https://sonauto.ai/artist/nlanza999'
				[812] link tropical, center=(1034,1014), url='https://sonauto.ai/tag/tropical'
				[814] link 1970s, center=(1104,1014), url='https://sonauto.ai/tag/1970s'
				[816] link island, center=(1170,1014), url='https://sonauto.ai/tag/island'
				image
				paragraph
					StaticText 3
				[823] image, center=(1056,1044)
				paragraph
					StaticText 0
				[825] link 0, center=(1108,1044), url='https://sonauto.ai/song/4ce7e7ce-4970-4645-a910-b4a65d297259'
					image
					paragraph
				[828] button, center=(1148,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 4 hours ago
			gridcell Tyler by the sea v2 Tyler by the sea nlanza999 tropical easy listening 2020s 4 0 0 Posted 4 hours ago
				[835] image Tyler by the sea, center=(1460,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_4cf260e8-26be-40d1-8eef-f664d60acc50.webp?width=256&quality=75&resize=contain'
				[837] image, center=(1410,1060)
				StaticText v2
				[842] link Tyler by the sea, center=(1618,949), url='https://sonauto.ai/song/4cf260e8-26be-40d1-8eef-f664d60acc50'
					heading Tyler by the sea
				[838] div, center=(1508,1066), inner_text=v2
				[844] link nlanza999, center=(1578,971), url='https://sonauto.ai/artist/nlanza999'
				[847] link tropical, center=(1580,1014), url='https://sonauto.ai/tag/tropical'
				[849] link easy listening, center=(1673,1014), url='https://sonauto.ai/tag/easy%20listening'
				[851] link 2020s, center=(1762,1014), url='https://sonauto.ai/tag/2020s'
				image
				paragraph
					StaticText 4
				[858] image, center=(1602,1044)
				paragraph
					StaticText 0
				[860] link 0, center=(1654,1044), url='https://sonauto.ai/song/4cf260e8-26be-40d1-8eef-f664d60acc50'
					image
					paragraph
				[863] button, center=(1694,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 4 hours ago
			gridcell Yamaha Keyboard Built-In Music-Core Vibes v2 Yamaha Keyboard Built-In Music-Core Vibes zaptrem new age instrumental bossa nova 6 0 0 Posted 5 hours ago
				image Yamaha Keyboard Built-In Music-Core Vibes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-267ca5d5-eb9f-4d6a-b627-0a97a3cf0d68?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Yamaha Keyboard Built-In Music-Core Vibes, url='https://sonauto.ai/song/5bd9a75f-4c9a-461f-b597-22eb99041b4d'
					heading Yamaha Keyboard Built-In Music-Core Vibes
				link zaptrem, url='https://sonauto.ai/artist/zaptrem'
				link new age, url='https://sonauto.ai/tag/new%20age'
				link instrumental, url='https://sonauto.ai/tag/instrumental'
				link bossa nova, url='https://sonauto.ai/tag/bossa%20nova'
				image
				paragraph
					StaticText 6
				image
				paragraph
					StaticText 0
				link 0, url='https://sonauto.ai/song/5bd9a75f-4c9a-461f-b597-22eb99041b4d'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
			gridcell Chill Feelings v2 Chill Feelings stickguy early 2010s world dream pop 8 0 0 Posted 5 hours ago
				image Chill Feelings, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-47eba7d4-bec2-4fcd-98f9-bef720ba0c3d?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Chill Feelings, url='https://sonauto.ai/song/f6d81b92-643c-4145-8710-6d3a3e5e2d8c'
					heading Chill Feelings
				link stickguy, url='https://sonauto.ai/artist/stickguy'
				link early 2010s, url='https://sonauto.ai/tag/early%202010s'
				link world, url='https://sonauto.ai/tag/world'
				link dream pop, url='https://sonauto.ai/tag/dream%20pop'
				image
				paragraph
					StaticText 8
				image
				paragraph
					StaticText 0
				link 0, url='https://sonauto.ai/song/f6d81b92-643c-4145-8710-6d3a3e5e2d8c'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
			gridcell Christmas A-Capella v2 Christmas A-Capella zaptrem holiday vocal harmony 16 2 0 Posted 5 hours ago
				image Christmas A-Capella, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-1b793f98-e10a-41ee-938c-9b4d84f874a5?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Christmas A-Capella, url='https://sonauto.ai/song/30143d59-692e-4019-86e4-603e33791cca'
					heading Christmas A-Capella
				link zaptrem, url='https://sonauto.ai/artist/zaptrem'
				link holiday, url='https://sonauto.ai/tag/holiday'
				link vocal, url='https://sonauto.ai/tag/vocal'
				link harmony, url='https://sonauto.ai/tag/harmony'
				image
				paragraph
					StaticText 16
				image
				paragraph
					StaticText 2
				link 0, url='https://sonauto.ai/song/30143d59-692e-4019-86e4-603e33791cca'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
		button Show More
		heading Trending Categories
		link 2020s, url='https://sonauto.ai/tag/2020s'
			heading 2020s
		link Male Vocalist, url='https://sonauto.ai/tag/male%20vocalist'
			heading Male Vocalist
		link Pop, url='https://sonauto.ai/tag/pop'
			heading Pop
		link Emotional, url='https://sonauto.ai/tag/emotional'
			heading Emotional
		link Blues, url='https://sonauto.ai/tag/blues'
			heading Blues
		link Female Vocalist, url='https://sonauto.ai/tag/female%20vocalist'
			heading Female Vocalist
		link Electronic, url='https://sonauto.ai/tag/electronic'
			heading Electronic
		link Rock, url='https://sonauto.ai/tag/rock'
			heading Rock
		link Electric Guitar, url='https://sonauto.ai/tag/electric%20guitar'
			heading Electric Guitar
		link Rap, url='https://sonauto.ai/tag/rap'
			heading Rap
		link Electric Blues, url='https://sonauto.ai/tag/electric%20blues'
			heading Electric Blues
		link Hip Hop, url='https://sonauto.ai/tag/hip%20hop'
			heading Hip Hop
		link Piano, url='https://sonauto.ai/tag/piano'
			heading Piano
		link 1970s, url='https://sonauto.ai/tag/1970s'
			heading 1970s
		link Nu-Disco, url='https://sonauto.ai/tag/nu-disco'
			heading Nu-Disco
		link Instrumental, url='https://sonauto.ai/tag/instrumental'
			heading Instrumental
		link Uplifting, url='https://sonauto.ai/tag/uplifting'
			heading Uplifting
		link Melodic, url='https://sonauto.ai/tag/melodic'
			heading Melodic
		link Synthpop, url='https://sonauto.ai/tag/synthpop'
			heading Synthpop
		link 2010s, url='https://sonauto.ai/tag/2010s'
			heading 2010s
		image
		image
	region Notifications (F8)
		list
```
</details>



```
RootWebArea Sonauto | New Music by You, focused, url='https://sonauto.ai/'
	alert, atomic
	paragraph
		StaticText Welcome to Sonauto v2 beta! Your v1 generations will be available for a limited time at
		[52] link v1.sonauto.ai, center=(1276,28), url='https://v1.sonauto.ai/'
```
<details><summary>Show more</summary>

```
		StaticText .
	[53] button, center=(1884,28)
		image
	[59] link Sonauto Logo Sonauto, center=(126,96), inner_text=Sonauto, url='https://sonauto.ai/'
		image Sonauto Logo, url='https://sonauto.ai/_next/image?url=%2Fimages%2Fnew_bird.png&w=32&q=75'
	navigation
		[62] link Home, center=(128,150), url='https://sonauto.ai/'
			image
		[64] link Search, center=(128,186), url='https://sonauto.ai/search'
			image
		[66] link Make Music, center=(128,222), url='https://sonauto.ai/'
			image
	paragraph
		StaticText Trending
	[71] button Playlist, center=(194,283)
		image
	[75] combobox value='All', center=(128,325), expanded=False, hasPopup='listbox', inner_text=All, type=button
	[80] link art Just Relax, center=(128,381), inner_text=Just Relax, url='https://sonauto.ai/playlist/ab0f22f8-64c6-454b-9a12-fb14f4d48465'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-ab0f22f8-64c6-454b-9a12-fb14f4d48465?width=32&quality=75&resize=contain'
	[83] link art Dark Radio Network, center=(128,417), inner_text=Dark Radio Network, url='https://sonauto.ai/playlist/65fdf34c-28d5-47dc-801c-f156a78638d4'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-65fdf34c-28d5-47dc-801c-f156a78638d4?width=32&quality=75&resize=contain'
	[86] link Test, center=(128,453), url='https://sonauto.ai/playlist/8f58dc22-0e35-42d3-bc0c-74a044c68f83'
	[89] link My list, center=(128,489), url='https://sonauto.ai/playlist/7dd42422-563f-4e2d-95f0-62e8ac4ac0df'
	[92] link art GREEN BITES, center=(128,525), inner_text=GREEN BITES, url='https://sonauto.ai/playlist/476f7f74-0f8a-4100-ab4a-ead30aa554df'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-937b0f24-7aaa-4357-9e04-43488dddf699?width=32&quality=75&resize=contain'
	[95] link art Klangraum V2 Tests, center=(128,561), inner_text=Klangraum V2 Tests, url='https://sonauto.ai/playlist/a1f1dd9b-e58f-4812-a1e6-024e69f1af37'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-a1f1dd9b-e58f-4812-a1e6-024e69f1af37?width=32&quality=75&resize=contain'
	[98] link My songs, center=(128,597), url='https://sonauto.ai/playlist/f580ce69-e977-4810-92b3-4f4815c4b86f'
	[101] link The Show, center=(128,633), url='https://sonauto.ai/playlist/ae20fb05-042d-4032-b27d-e71785eeda08'
	[104] link art DID HE, center=(128,669), inner_text=DID HE, url='https://sonauto.ai/playlist/dbbd1058-a2eb-41cf-bd30-c350b1dfde90'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-dbbd1058-a2eb-41cf-bd30-c350b1dfde90?width=32&quality=75&resize=contain'
	[107] link cool, center=(128,705), url='https://sonauto.ai/playlist/5491c699-3f58-4762-913f-ffe690282a63'
	[110] link Luis, center=(128,741), url='https://sonauto.ai/playlist/6831c1cb-0828-4eec-95cc-dfdba071eae7'
	[113] link tyghghhg, center=(128,777), url='https://sonauto.ai/playlist/b46544c7-931f-434e-a501-4aa23e37a89f'
	link art Bluesman420 Fan Club, url='https://sonauto.ai/group/c97cd6bf-475b-447c-8db4-11a9dc2d526a'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1507227c-e538-4a01-9ec0-967a0ac68902?width=32&quality=75&resize=contain'
	link art Various Instrumentals, url='https://sonauto.ai/group/998f8cf6-7740-42be-ab67-6e983502abb4'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-998f8cf6-7740-42be-ab67-6e983502abb4?width=32&quality=75&resize=contain'
	link art Dark Radio, url='https://sonauto.ai/group/87db116d-1613-4574-8785-fb2cb613d18f'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-87db116d-1613-4574-8785-fb2cb613d18f?width=32&quality=75&resize=contain'
	link art Rubinyan theme Song, url='https://sonauto.ai/group/e7c907fb-9324-4389-961b-59880d374568'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-e7c907fb-9324-4389-961b-59880d374568?width=32&quality=75&resize=contain'
	link Rescate Brasil, url='https://sonauto.ai/group/05ed4a63-e238-4c92-a11e-df5dfeec01e2'
	link my music, url='https://sonauto.ai/group/8c296cfa-ea98-45c1-9b62-338cb85f137a'
	link Mm, url='https://sonauto.ai/group/49828acd-64b5-46e5-b45f-a548172e3f64'
	link art vives, url='https://sonauto.ai/group/22fa8e47-8007-48b9-ab7d-159979cf6a2c'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-97cc5c0d-b5ef-4e7c-8fee-f02e3db5a3e8?width=32&quality=75&resize=contain'
	link Heavy metal, url='https://sonauto.ai/group/f7f4e492-9701-4af9-98de-610c00d6e8e9'
	link art Música, url='https://sonauto.ai/group/2e28bd75-83ad-4055-b2d0-19fb1b687378'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-2e28bd75-83ad-4055-b2d0-19fb1b687378?width=32&quality=75&resize=contain'
	link art Davidounours, url='https://sonauto.ai/group/1a956452-71d5-4800-8a96-0ec8346bac0d'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-1a956452-71d5-4800-8a96-0ec8346bac0d?width=32&quality=75&resize=contain'
	link Hddjdh, url='https://sonauto.ai/group/9f5f4f3a-86aa-4e00-a270-b95e294c21c6'
	link Need For Speed Soundtrack, url='https://sonauto.ai/group/db78b071-5d27-49d6-af33-f115692bdaa6'
	link art Killer Raps, url='https://sonauto.ai/group/0a9833ea-3417-48fc-a11f-4a5669741ece'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-0a9833ea-3417-48fc-a11f-4a5669741ece?width=32&quality=75&resize=contain'
	link Так выбрать из балкона, url='https://sonauto.ai/group/9be2dbd8-08b6-4d09-bc72-c1981ba72277'
	link House, url='https://sonauto.ai/group/13f7e378-c201-4a6f-ad86-3b500505353b'
	link art Nothin but the Blues, url='https://sonauto.ai/group/d54b03a1-cd7b-4490-8900-81d49fc37f6e'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-d54b03a1-cd7b-4490-8900-81d49fc37f6e?width=32&quality=75&resize=contain'
	link art Le hobo, url='https://sonauto.ai/group/1148e019-c74c-4069-9b3c-f6cb290c3cf0'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-1148e019-c74c-4069-9b3c-f6cb290c3cf0?width=32&quality=75&resize=contain'
	link art Unusual Dubstep, url='https://sonauto.ai/group/ac84677c-9503-416f-a533-d5f05c9a2abc'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-ac84677c-9503-416f-a533-d5f05c9a2abc?width=32&quality=75&resize=contain'
	link art Cultural Mix & Crossovers, url='https://sonauto.ai/group/4bcec888-8969-43ac-a0c7-75fcd019db9f'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-4bcec888-8969-43ac-a0c7-75fcd019db9f?width=32&quality=75&resize=contain'
	link art Basement Dancefloor, url='https://sonauto.ai/group/b62764aa-2922-4b3e-8f6d-9a34871b391b'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-b62764aa-2922-4b3e-8f6d-9a34871b391b?width=32&quality=75&resize=contain'
	link art Universal Music, url='https://sonauto.ai/group/14a2e296-9039-48dd-a5b9-25578ba8b8e1'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-14a2e296-9039-48dd-a5b9-25578ba8b8e1?width=32&quality=75&resize=contain'
	[184] link Discord, center=(112,1005), url='https://discord.gg/pfXar3ChH8'
		image Discord icon, url='https://sonauto.ai/discord-white.svg'
	[186] link Twitter, center=(146,1005), url='https://x.com/SonautoAI'
		image Twitter icon, url='https://sonauto.ai/twitter-icon.svg'
	[189] link Terms, center=(97,1040), url='https://sonauto.ai/tos'
	StaticText ·
	[191] link Privacy, center=(156,1040), url='https://sonauto.ai/privacy'
	[196] button, center=(302,88)
		image
	[198] button, center=(342,88)
		image
	[201] link Install App, center=(1741,88), url='https://sonauto.ai/install'
		image
	[204] image, center=(1828,88)
	StaticText Log In
	main
		heading Start Your Masterpiece
		image
		[215] textbox A rock song about turtles flying, center=(1034,195), contenteditable=True, type=text
		[217] image, center=(1757,195)
		[218] button Generate, center=(1838,195)
		heading Instantly Create a Song
		[223] image, center=(542,249)
		[229] heading Pop, 2020s, Summer, Nu-Disco, center=(406,293)
		[232] heading [Miel San Marcos, Worship, Christian, Inspirational, Emotional, Male Vocalist, Female Vocalist, Piano, Electric Guitar, Drum Set, 2010s], center=(732,293)
		[235] heading Country, 2020s, Storytelling, Southern Rock, center=(1104,293)
		[238] heading Sentimental, Emotional, 1980s, Romantic, Melancholic, Pop, R&B, center=(1477,293)
		heading Guitar Virtuoso, Electric Blues, Texas Blues
		heading Blues, 1970s, Electric Blues
		heading Lo-Fi, Chillout, Downtempo
		heading A Blues Song Played By A Blues Power Trio. Incredible Guitar Solos With Heavy Bending. Thick Bass Tone.
		heading Blues, 1970s, Electric Blues
		heading Summer, Nu-Disco, 2020s, Romantic, Dance
		image
		[260] image, center=(1880,299)
		heading Groups For You
		[264] button Create a Group, center=(562,339)
			image
		[273] image Zaptrem's Group, center=(368,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-ee12a798-6b2f-4d90-9d4b-cd035d9a0a48?width=256&quality=75&resize=contain'
		[276] heading Zaptrem's Group, center=(530,402)
		[277] paragraph, center=(530,421), inner_text=7 Members
			StaticText 7
			StaticText Members
		paragraph
			StaticText Moderated by
			[279] link zaptrem, center=(566,441), url='https://sonauto.ai/artist/zaptrem'
		[280] paragraph, center=(530,469), inner_text=Feed me soooongs
			StaticText Feed me soooongs
		[282] button Play, center=(486,520)
			image
		[286] image Bluesman420 Fan Club, center=(734,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1507227c-e538-4a01-9ec0-967a0ac68902?width=256&quality=75&resize=contain'
		[289] heading Bluesman420 Fan Club, center=(900,413)
		[290] paragraph, center=(900,444), inner_text=5 Members
			StaticText 5
			StaticText Members
		paragraph
			StaticText Moderated by
			[292] link zaptrem, center=(932,463), url='https://sonauto.ai/artist/zaptrem'
		[293] paragraph, center=(900,492), inner_text=It's 106 miles to Chicago, we got a full tank of gas, half a pack of cigarettes, it's dark... and we're wearing sunglasses.
			StaticText It's 106 miles to Chicago, we got a full tank of gas, half a pack of cigarettes, it's dark... and we're wearing sunglasses.
		[295] button Play, center=(852,526)
			image
		[299] image Weird & Wacky Texts & Topics, center=(1100,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-7c2da748-49a4-43c8-9f4a-432a2ae1c561?width=256&quality=75&resize=contain'
		[302] heading Weird & Wacky Texts & Topics, center=(1266,413)
		[303] paragraph, center=(1266,444), inner_text=4 Members
			StaticText 4
			StaticText Members
		paragraph
			StaticText Moderated by
			[305] link chaos, center=(1292,463), url='https://sonauto.ai/artist/chaos'
		[306] paragraph, center=(1266,492), inner_text=Can you really sing a song about that stuff? Yup. Sure can.
			StaticText Can you really sing a song about that stuff? Yup. Sure can.
		[308] button Play, center=(1218,526)
			image
		[312] image Nice Voice, center=(1466,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-82686aa1-5a53-42d6-bb86-80b71defb209?width=256&quality=75&resize=contain'
		[315] heading Nice Voice, center=(1632,402)
		[316] paragraph, center=(1632,421), inner_text=3 Members
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			[318] link chaos, center=(1658,441), url='https://sonauto.ai/artist/chaos'
		[319] paragraph, center=(1632,469), inner_text=If you think the voice sounds great and is good quality, put it here.
			StaticText If you think the voice sounds great and is good quality, put it here.
		[321] button Play, center=(1584,520)
			image
		image Tilted Dancefloor, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-841b4468-df7a-428d-80c4-9a8494c4cb87?width=256&quality=75&resize=contain'
		heading Tilted Dancefloor
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link chaos, url='https://sonauto.ai/artist/chaos'
		paragraph
			StaticText Energetic with a twist of humor
		button Play
			image
		image Dark Synthwave, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1a7fa429-74d3-40f0-bac1-c78594847bb5?width=256&quality=75&resize=contain'
		heading Dark Synthwave
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link hayden, url='https://sonauto.ai/artist/hayden'
		paragraph
			StaticText Dark electronic melodic metal and synthwave
		button Play
			image
		image Chill Vibes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-6afa6e51-c830-45e9-8f71-032a1c50ec83?width=256&quality=75&resize=contain'
		heading Chill Vibes
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link hayden, url='https://sonauto.ai/artist/hayden'
		paragraph
		button Play
			image
		image Various Instrumentals, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-998f8cf6-7740-42be-ab67-6e983502abb4?width=256&quality=75&resize=contain'
		heading Various Instrumentals
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link whosthere, url='https://sonauto.ai/artist/whosthere'
		paragraph
			StaticText For instrumentals lovers
		button Play
			image
		image Protest Songs, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-a4e4e13c-e498-4dd6-9957-df69d208a2d5?width=256&quality=75&resize=contain'
		heading Protest Songs
		paragraph
			StaticText 2
			StaticText Members
		paragraph
			StaticText Moderated by
			link chaos, url='https://sonauto.ai/artist/chaos'
		paragraph
			StaticText Old people shouting at the sky come here to vent.
		button Play
			image
		image
		[391] image, center=(1880,462)
		heading Staff Picks
		[396] button, center=(444,591)
			image
		[405] image Leavin' You Behind, center=(368,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-b03dcac9-65d8-41ab-a850-dda75cb88114?width=256&quality=75&resize=contain'
		[407] image, center=(318,770)
		StaticText v2
		[412] link Leavin' You Behind, center=(540,659), url='https://sonauto.ai/song/ab00865a-10e5-4993-a3d9-adbb4876beb9'
			heading Leavin' You Behind
		[408] div, center=(416,776), inner_text=v2
		[414] link zaptrem, center=(480,681), url='https://sonauto.ai/artist/zaptrem'
		[417] link summer, center=(490,724), url='https://sonauto.ai/tag/summer'
		[419] link 2020s, center=(562,724), url='https://sonauto.ai/tag/2020s'
		[421] link pop, center=(623,724), url='https://sonauto.ai/tag/pop'
		image
		paragraph
			StaticText 822
		[428] image, center=(524,754)
		paragraph
			StaticText 11
		[430] link 2, center=(578,754), url='https://sonauto.ai/song/ab00865a-10e5-4993-a3d9-adbb4876beb9'
			image
			paragraph
		[433] button, center=(617,754), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 6 days ago
		[440] image Alright, center=(783,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-668bf78d-dff4-4a22-8d5b-1a2bd48cf08e?width=256&quality=75&resize=contain'
		[442] image, center=(733,770)
		StaticText v2
		[447] link Alright, center=(900,659), url='https://sonauto.ai/song/cc599224-25b1-4521-bb7d-63d63addd13b'
			heading Alright
		[443] div, center=(832,776), inner_text=v2
		[449] link coolsong, center=(898,681), url='https://sonauto.ai/artist/coolsong'
		[452] link 2020s, center=(900,709), url='https://sonauto.ai/tag/2020s'
		[454] link country, center=(970,709), url='https://sonauto.ai/tag/country'
		[456] link southern rock, center=(922,742), url='https://sonauto.ai/tag/southern%20rock'
		image
		paragraph
			StaticText 205
		[463] image, center=(939,772)
		paragraph
			StaticText 5
		[465] link 2, center=(990,772), url='https://sonauto.ai/song/cc599224-25b1-4521-bb7d-63d63addd13b'
			image
			paragraph
		[468] button, center=(1029,772), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 5 days ago
		[475] image We Stand, center=(1198,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-e668a6b3-ccca-4c36-a2a3-e42035389e5e?width=256&quality=75&resize=contain'
		[477] image, center=(1148,770)
		StaticText v2
		[482] link We Stand, center=(1328,659), url='https://sonauto.ai/song/cdd77c72-99bd-4247-b83f-ecaae849fdd2'
			heading We Stand
		[478] div, center=(1246,776), inner_text=v2
		[484] link gonesvan, center=(1314,681), url='https://sonauto.ai/artist/gonesvan'
		[487] link male vocalist, center=(1335,709), url='https://sonauto.ai/tag/male%20vocalist'
		[489] link electric guitar, center=(1444,709), url='https://sonauto.ai/tag/electric%20guitar'
		[491] link christian, center=(1320,742), url='https://sonauto.ai/tag/christian'
		image
		paragraph
			StaticText 391
		[498] image, center=(1353,772)
		paragraph
			StaticText 6
		[500] link 2, center=(1404,772), url='https://sonauto.ai/song/cdd77c72-99bd-4247-b83f-ecaae849fdd2'
			image
			paragraph
		[503] button, center=(1444,772), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 7 days ago
		[510] image When it’s us, center=(1613,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-a7ed0653-8a2f-4408-85c5-7f5bb57f7d7f?width=256&quality=75&resize=contain'
		[512] image, center=(1563,770)
		StaticText v2
		[517] link When it’s us, center=(1754,659), url='https://sonauto.ai/song/edba394d-4003-4d9b-a960-0ad0b2ae2490'
			heading When it’s us
		[513] div, center=(1662,776), inner_text=v2
		[519] link gonesvan, center=(1730,681), url='https://sonauto.ai/artist/gonesvan'
		[522] link male vocalist, center=(1750,709), url='https://sonauto.ai/tag/male%20vocalist'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		[526] link k-ballad, center=(1735,742), url='https://sonauto.ai/tag/k-ballad'
		image
		paragraph
			StaticText 306
		[533] image, center=(1771,772)
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/edba394d-4003-4d9b-a960-0ad0b2ae2490'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Craving for Snacks, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_87490abc-2ad8-4a8c-b234-904c28fd30f1.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Craving for Snacks, url='https://sonauto.ai/song/87490abc-2ad8-4a8c-b234-904c28fd30f1'
			heading Craving for Snacks
		link chaos, url='https://sonauto.ai/artist/chaos'
		link country, url='https://sonauto.ai/tag/country'
		link bluegrass, url='https://sonauto.ai/tag/bluegrass'
		image
		paragraph
			StaticText 413
		image
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/87490abc-2ad8-4a8c-b234-904c28fd30f1'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Green Eyes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-da6fe498-0f13-4aa7-932c-02fbd81d328d?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Green Eyes, url='https://sonauto.ai/song/bf4c9cae-f33e-4dc5-a5a7-7abe63696448'
			heading Green Eyes
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link indie, url='https://sonauto.ai/tag/indie'
		link pop, url='https://sonauto.ai/tag/pop'
		link dance pop, url='https://sonauto.ai/tag/dance%20pop'
		image
		paragraph
			StaticText 269
		image
		paragraph
			StaticText 4
		link 0, url='https://sonauto.ai/song/bf4c9cae-f33e-4dc5-a5a7-7abe63696448'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Midnight Raid, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-5cc8897c-5900-4359-bcf4-ff6120b6ef8f?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Midnight Raid, url='https://sonauto.ai/song/9715ecb5-1865-46f9-b064-0e16725b4fa6'
			heading Midnight Raid
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link EDM, url='https://sonauto.ai/tag/EDM'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		link house, url='https://sonauto.ai/tag/house'
		image
		paragraph
			StaticText 312
		image
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/9715ecb5-1865-46f9-b064-0e16725b4fa6'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Crazy Friday Night, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-984cef64-d683-4743-935f-6ab8d8c9a828?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Crazy Friday Night, url='https://sonauto.ai/song/9e21b63b-0ac3-437c-88ae-05e57c67bd6f'
			heading Crazy Friday Night
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link pop, url='https://sonauto.ai/tag/pop'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		link party, url='https://sonauto.ai/tag/party'
		image
		paragraph
			StaticText 279
		image
		paragraph
			StaticText 4
		link 0, url='https://sonauto.ai/song/9e21b63b-0ac3-437c-88ae-05e57c67bd6f'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Don't Cry Now, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_ff718ead-ecb4-4348-8f0b-8d393bba657d.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Don't Cry Now, url='https://sonauto.ai/song/ff718ead-ecb4-4348-8f0b-8d393bba657d'
			heading Don't Cry Now
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link country, url='https://sonauto.ai/tag/country'
		link rock, url='https://sonauto.ai/tag/rock'
		link western, url='https://sonauto.ai/tag/western'
		image
		paragraph
			StaticText 244
		image
		paragraph
			StaticText 1
		link 0, url='https://sonauto.ai/song/ff718ead-ecb4-4348-8f0b-8d393bba657d'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Caught in the Past, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_f40f3424-273c-4770-8ff8-e2f455a932a2.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Caught in the Past, url='https://sonauto.ai/song/f40f3424-273c-4770-8ff8-e2f455a932a2'
			heading Caught in the Past
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link 2000s, url='https://sonauto.ai/tag/2000s'
		link pop, url='https://sonauto.ai/tag/pop'
		link breakup, url='https://sonauto.ai/tag/breakup'
		image
		paragraph
			StaticText 299
		image
		paragraph
			StaticText 5
		link 2, url='https://sonauto.ai/song/f40f3424-273c-4770-8ff8-e2f455a932a2'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image
		[752] image, center=(1880,729)
		heading Trending Posts
		[756] button, center=(494,878)
			image
		[758] combobox value='Trending', center=(584,878), expanded=False, hasPopup='listbox', inner_text=Trending, type=button
		grid
			gridcell 1970s Cop Movie Soundtrack v2 1970s Cop Movie Soundtrack whosthere blues rock lounge 8 1 0 Posted 3 hours ago
				[767] image 1970s Cop Movie Soundtrack, center=(368,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-164546f9-46c7-42ec-9570-20885dca42aa?width=256&quality=75&resize=contain'
				[769] image, center=(318,1060)
				StaticText v2
				[774] link 1970s Cop Movie Soundtrack, center=(584,949), url='https://sonauto.ai/song/44b0ed21-fe47-4856-a42f-a7ceb923dda2'
					heading 1970s Cop Movie Soundtrack
				[770] div, center=(416,1066), inner_text=v2
				[776] link whosthere, center=(486,971), url='https://sonauto.ai/artist/whosthere'
				[779] link blues rock, center=(497,1014), url='https://sonauto.ai/tag/blues%20rock'
				[781] link lounge, center=(578,1014), url='https://sonauto.ai/tag/lounge'
				image
				paragraph
					StaticText 8
				[788] image, center=(510,1044)
				paragraph
					StaticText 1
				[790] link 0, center=(559,1044), url='https://sonauto.ai/song/44b0ed21-fe47-4856-a42f-a7ceb923dda2'
					image
					paragraph
				[793] button, center=(599,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 3 hours ago
			gridcell Tyler's Pina Coladaburg v2 Tyler's Pina Coladaburg nlanza999 tropical 1970s island 3 0 0 Posted 4 hours ago
				[800] image Tyler's Pina Coladaburg, center=(914,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_4ce7e7ce-4970-4645-a910-b4a65d297259.webp?width=256&quality=75&resize=contain'
				[802] image, center=(864,1060)
				StaticText v2
				[807] link Tyler's Pina Coladaburg, center=(1108,949), url='https://sonauto.ai/song/4ce7e7ce-4970-4645-a910-b4a65d297259'
					heading Tyler's Pina Coladaburg
				[803] div, center=(962,1066), inner_text=v2
				[809] link nlanza999, center=(1032,971), url='https://sonauto.ai/artist/nlanza999'
				[812] link tropical, center=(1034,1014), url='https://sonauto.ai/tag/tropical'
				[814] link 1970s, center=(1104,1014), url='https://sonauto.ai/tag/1970s'
				[816] link island, center=(1170,1014), url='https://sonauto.ai/tag/island'
				image
				paragraph
					StaticText 3
				[823] image, center=(1056,1044)
				paragraph
					StaticText 0
				[825] link 0, center=(1108,1044), url='https://sonauto.ai/song/4ce7e7ce-4970-4645-a910-b4a65d297259'
					image
					paragraph
				[828] button, center=(1148,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 4 hours ago
			gridcell Tyler by the sea v2 Tyler by the sea nlanza999 tropical easy listening 2020s 4 0 0 Posted 4 hours ago
				[835] image Tyler by the sea, center=(1460,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_4cf260e8-26be-40d1-8eef-f664d60acc50.webp?width=256&quality=75&resize=contain'
				[837] image, center=(1410,1060)
				StaticText v2
				[842] link Tyler by the sea, center=(1618,949), url='https://sonauto.ai/song/4cf260e8-26be-40d1-8eef-f664d60acc50'
					heading Tyler by the sea
				[838] div, center=(1508,1066), inner_text=v2
				[844] link nlanza999, center=(1578,971), url='https://sonauto.ai/artist/nlanza999'
				[847] link tropical, center=(1580,1014), url='https://sonauto.ai/tag/tropical'
				[849] link easy listening, center=(1673,1014), url='https://sonauto.ai/tag/easy%20listening'
				[851] link 2020s, center=(1762,1014), url='https://sonauto.ai/tag/2020s'
				image
				paragraph
					StaticText 4
				[858] image, center=(1602,1044)
				paragraph
					StaticText 0
				[860] link 0, center=(1654,1044), url='https://sonauto.ai/song/4cf260e8-26be-40d1-8eef-f664d60acc50'
					image
					paragraph
				[863] button, center=(1694,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 4 hours ago
			gridcell Yamaha Keyboard Built-In Music-Core Vibes v2 Yamaha Keyboard Built-In Music-Core Vibes zaptrem new age instrumental bossa nova 6 0 0 Posted 5 hours ago
				image Yamaha Keyboard Built-In Music-Core Vibes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-267ca5d5-eb9f-4d6a-b627-0a97a3cf0d68?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Yamaha Keyboard Built-In Music-Core Vibes, url='https://sonauto.ai/song/5bd9a75f-4c9a-461f-b597-22eb99041b4d'
					heading Yamaha Keyboard Built-In Music-Core Vibes
				link zaptrem, url='https://sonauto.ai/artist/zaptrem'
				link new age, url='https://sonauto.ai/tag/new%20age'
				link instrumental, url='https://sonauto.ai/tag/instrumental'
				link bossa nova, url='https://sonauto.ai/tag/bossa%20nova'
				image
				paragraph
					StaticText 6
				image
				paragraph
					StaticText 0
				link 0, url='https://sonauto.ai/song/5bd9a75f-4c9a-461f-b597-22eb99041b4d'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
			gridcell Chill Feelings v2 Chill Feelings stickguy early 2010s world dream pop 8 0 0 Posted 5 hours ago
				image Chill Feelings, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-47eba7d4-bec2-4fcd-98f9-bef720ba0c3d?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Chill Feelings, url='https://sonauto.ai/song/f6d81b92-643c-4145-8710-6d3a3e5e2d8c'
					heading Chill Feelings
				link stickguy, url='https://sonauto.ai/artist/stickguy'
				link early 2010s, url='https://sonauto.ai/tag/early%202010s'
				link world, url='https://sonauto.ai/tag/world'
				link dream pop, url='https://sonauto.ai/tag/dream%20pop'
				image
				paragraph
					StaticText 8
				image
				paragraph
					StaticText 0
				link 0, url='https://sonauto.ai/song/f6d81b92-643c-4145-8710-6d3a3e5e2d8c'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
			gridcell Christmas A-Capella v2 Christmas A-Capella zaptrem holiday vocal harmony 16 2 0 Posted 5 hours ago
				image Christmas A-Capella, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-1b793f98-e10a-41ee-938c-9b4d84f874a5?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Christmas A-Capella, url='https://sonauto.ai/song/30143d59-692e-4019-86e4-603e33791cca'
					heading Christmas A-Capella
				link zaptrem, url='https://sonauto.ai/artist/zaptrem'
				link holiday, url='https://sonauto.ai/tag/holiday'
				link vocal, url='https://sonauto.ai/tag/vocal'
				link harmony, url='https://sonauto.ai/tag/harmony'
				image
				paragraph
					StaticText 16
				image
				paragraph
					StaticText 2
				link 0, url='https://sonauto.ai/song/30143d59-692e-4019-86e4-603e33791cca'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
		button Show More
		heading Trending Categories
		link 2020s, url='https://sonauto.ai/tag/2020s'
			heading 2020s
		link Male Vocalist, url='https://sonauto.ai/tag/male%20vocalist'
			heading Male Vocalist
		link Pop, url='https://sonauto.ai/tag/pop'
			heading Pop
		link Emotional, url='https://sonauto.ai/tag/emotional'
			heading Emotional
		link Blues, url='https://sonauto.ai/tag/blues'
			heading Blues
		link Female Vocalist, url='https://sonauto.ai/tag/female%20vocalist'
			heading Female Vocalist
		link Electronic, url='https://sonauto.ai/tag/electronic'
			heading Electronic
		link Rock, url='https://sonauto.ai/tag/rock'
			heading Rock
		link Electric Guitar, url='https://sonauto.ai/tag/electric%20guitar'
			heading Electric Guitar
		link Rap, url='https://sonauto.ai/tag/rap'
			heading Rap
		link Electric Blues, url='https://sonauto.ai/tag/electric%20blues'
			heading Electric Blues
		link Hip Hop, url='https://sonauto.ai/tag/hip%20hop'
			heading Hip Hop
		link Piano, url='https://sonauto.ai/tag/piano'
			heading Piano
		link 1970s, url='https://sonauto.ai/tag/1970s'
			heading 1970s
		link Nu-Disco, url='https://sonauto.ai/tag/nu-disco'
			heading Nu-Disco
		link Instrumental, url='https://sonauto.ai/tag/instrumental'
			heading Instrumental
		link Uplifting, url='https://sonauto.ai/tag/uplifting'
			heading Uplifting
		link Melodic, url='https://sonauto.ai/tag/melodic'
			heading Melodic
		link Synthpop, url='https://sonauto.ai/tag/synthpop'
			heading Synthpop
		link 2010s, url='https://sonauto.ai/tag/2010s'
			heading 2010s
		image
		image
	region Notifications (F8)
		list
```
</details>

**Reasoning for action:** I decided to click on the Search link because to fulfill the user's story as a music enthusiast looking to explore and discover new playlists, I needed to access more options for playlists, including the 'Just Relax' and 'Dark Radio Network' playlists. While the user may not have specified the need to search for playlists directly, the Search area of the site likely provides the most comprehensive way to locate and browse specific playlists that cater to the user's mood.

**Action:** click('64') # Click on the Search link to explore music options.

**Change Description:** After clicking the 'Search' link, the browser navigated to the search interface of Sonauto, which likely allows users to explore music options, but the specific content displayed after the navigation is not detailed.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://sonauto.ai/

https://sonauto.ai/

**Content (before/after):** 

```
RootWebArea Sonauto | New Music by You, focused, url='https://sonauto.ai/'
	alert, atomic
	paragraph
		StaticText Welcome to Sonauto v2 beta! Your v1 generations will be available for a limited time at
		[52] link v1.sonauto.ai, center=(1276,28), url='https://v1.sonauto.ai/'
```
<details><summary>Show more</summary>

```
		StaticText .
	[53] button, center=(1884,28)
		image
	[59] link Sonauto Logo Sonauto, center=(126,96), inner_text=Sonauto, url='https://sonauto.ai/'
		image Sonauto Logo, url='https://sonauto.ai/_next/image?url=%2Fimages%2Fnew_bird.png&w=32&q=75'
	navigation
		[62] link Home, center=(128,150), url='https://sonauto.ai/'
			image
		[64] link Search, center=(128,186), url='https://sonauto.ai/search'
			image
		[66] link Make Music, center=(128,222), url='https://sonauto.ai/'
			image
	paragraph
		StaticText Trending
	[71] button Playlist, center=(194,283)
		image
	[75] combobox value='All', center=(128,325), expanded=False, hasPopup='listbox', inner_text=All, type=button
	[80] link art Just Relax, center=(128,381), inner_text=Just Relax, url='https://sonauto.ai/playlist/ab0f22f8-64c6-454b-9a12-fb14f4d48465'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-ab0f22f8-64c6-454b-9a12-fb14f4d48465?width=32&quality=75&resize=contain'
	[83] link art Dark Radio Network, center=(128,417), inner_text=Dark Radio Network, url='https://sonauto.ai/playlist/65fdf34c-28d5-47dc-801c-f156a78638d4'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-65fdf34c-28d5-47dc-801c-f156a78638d4?width=32&quality=75&resize=contain'
	[86] link Test, center=(128,453), url='https://sonauto.ai/playlist/8f58dc22-0e35-42d3-bc0c-74a044c68f83'
	[89] link My list, center=(128,489), url='https://sonauto.ai/playlist/7dd42422-563f-4e2d-95f0-62e8ac4ac0df'
	[92] link art GREEN BITES, center=(128,525), inner_text=GREEN BITES, url='https://sonauto.ai/playlist/476f7f74-0f8a-4100-ab4a-ead30aa554df'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-937b0f24-7aaa-4357-9e04-43488dddf699?width=32&quality=75&resize=contain'
	[95] link art Klangraum V2 Tests, center=(128,561), inner_text=Klangraum V2 Tests, url='https://sonauto.ai/playlist/a1f1dd9b-e58f-4812-a1e6-024e69f1af37'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-a1f1dd9b-e58f-4812-a1e6-024e69f1af37?width=32&quality=75&resize=contain'
	[98] link My songs, center=(128,597), url='https://sonauto.ai/playlist/f580ce69-e977-4810-92b3-4f4815c4b86f'
	[101] link The Show, center=(128,633), url='https://sonauto.ai/playlist/ae20fb05-042d-4032-b27d-e71785eeda08'
	[104] link art DID HE, center=(128,669), inner_text=DID HE, url='https://sonauto.ai/playlist/dbbd1058-a2eb-41cf-bd30-c350b1dfde90'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-dbbd1058-a2eb-41cf-bd30-c350b1dfde90?width=32&quality=75&resize=contain'
	[107] link cool, center=(128,705), url='https://sonauto.ai/playlist/5491c699-3f58-4762-913f-ffe690282a63'
	[110] link Luis, center=(128,741), url='https://sonauto.ai/playlist/6831c1cb-0828-4eec-95cc-dfdba071eae7'
	[113] link tyghghhg, center=(128,777), url='https://sonauto.ai/playlist/b46544c7-931f-434e-a501-4aa23e37a89f'
	link art Bluesman420 Fan Club, url='https://sonauto.ai/group/c97cd6bf-475b-447c-8db4-11a9dc2d526a'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1507227c-e538-4a01-9ec0-967a0ac68902?width=32&quality=75&resize=contain'
	link art Various Instrumentals, url='https://sonauto.ai/group/998f8cf6-7740-42be-ab67-6e983502abb4'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-998f8cf6-7740-42be-ab67-6e983502abb4?width=32&quality=75&resize=contain'
	link art Dark Radio, url='https://sonauto.ai/group/87db116d-1613-4574-8785-fb2cb613d18f'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-87db116d-1613-4574-8785-fb2cb613d18f?width=32&quality=75&resize=contain'
	link art Rubinyan theme Song, url='https://sonauto.ai/group/e7c907fb-9324-4389-961b-59880d374568'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-e7c907fb-9324-4389-961b-59880d374568?width=32&quality=75&resize=contain'
	link Rescate Brasil, url='https://sonauto.ai/group/05ed4a63-e238-4c92-a11e-df5dfeec01e2'
	link my music, url='https://sonauto.ai/group/8c296cfa-ea98-45c1-9b62-338cb85f137a'
	link Mm, url='https://sonauto.ai/group/49828acd-64b5-46e5-b45f-a548172e3f64'
	link art vives, url='https://sonauto.ai/group/22fa8e47-8007-48b9-ab7d-159979cf6a2c'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-97cc5c0d-b5ef-4e7c-8fee-f02e3db5a3e8?width=32&quality=75&resize=contain'
	link Heavy metal, url='https://sonauto.ai/group/f7f4e492-9701-4af9-98de-610c00d6e8e9'
	link art Música, url='https://sonauto.ai/group/2e28bd75-83ad-4055-b2d0-19fb1b687378'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-2e28bd75-83ad-4055-b2d0-19fb1b687378?width=32&quality=75&resize=contain'
	link art Davidounours, url='https://sonauto.ai/group/1a956452-71d5-4800-8a96-0ec8346bac0d'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-1a956452-71d5-4800-8a96-0ec8346bac0d?width=32&quality=75&resize=contain'
	link Hddjdh, url='https://sonauto.ai/group/9f5f4f3a-86aa-4e00-a270-b95e294c21c6'
	link Need For Speed Soundtrack, url='https://sonauto.ai/group/db78b071-5d27-49d6-af33-f115692bdaa6'
	link art Killer Raps, url='https://sonauto.ai/group/0a9833ea-3417-48fc-a11f-4a5669741ece'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-0a9833ea-3417-48fc-a11f-4a5669741ece?width=32&quality=75&resize=contain'
	link Так выбрать из балкона, url='https://sonauto.ai/group/9be2dbd8-08b6-4d09-bc72-c1981ba72277'
	link House, url='https://sonauto.ai/group/13f7e378-c201-4a6f-ad86-3b500505353b'
	link art Nothin but the Blues, url='https://sonauto.ai/group/d54b03a1-cd7b-4490-8900-81d49fc37f6e'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-d54b03a1-cd7b-4490-8900-81d49fc37f6e?width=32&quality=75&resize=contain'
	link art Le hobo, url='https://sonauto.ai/group/1148e019-c74c-4069-9b3c-f6cb290c3cf0'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-1148e019-c74c-4069-9b3c-f6cb290c3cf0?width=32&quality=75&resize=contain'
	link art Unusual Dubstep, url='https://sonauto.ai/group/ac84677c-9503-416f-a533-d5f05c9a2abc'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-ac84677c-9503-416f-a533-d5f05c9a2abc?width=32&quality=75&resize=contain'
	link art Cultural Mix & Crossovers, url='https://sonauto.ai/group/4bcec888-8969-43ac-a0c7-75fcd019db9f'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-4bcec888-8969-43ac-a0c7-75fcd019db9f?width=32&quality=75&resize=contain'
	link art Basement Dancefloor, url='https://sonauto.ai/group/b62764aa-2922-4b3e-8f6d-9a34871b391b'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-b62764aa-2922-4b3e-8f6d-9a34871b391b?width=32&quality=75&resize=contain'
	link art Universal Music, url='https://sonauto.ai/group/14a2e296-9039-48dd-a5b9-25578ba8b8e1'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-14a2e296-9039-48dd-a5b9-25578ba8b8e1?width=32&quality=75&resize=contain'
	[184] link Discord, center=(112,1005), url='https://discord.gg/pfXar3ChH8'
		image Discord icon, url='https://sonauto.ai/discord-white.svg'
	[186] link Twitter, center=(146,1005), url='https://x.com/SonautoAI'
		image Twitter icon, url='https://sonauto.ai/twitter-icon.svg'
	[189] link Terms, center=(97,1040), url='https://sonauto.ai/tos'
	StaticText ·
	[191] link Privacy, center=(156,1040), url='https://sonauto.ai/privacy'
	[196] button, center=(302,88)
		image
	[198] button, center=(342,88)
		image
	[201] link Install App, center=(1741,88), url='https://sonauto.ai/install'
		image
	[204] image, center=(1828,88)
	StaticText Log In
	main
		heading Start Your Masterpiece
		image
		[215] textbox A rock song about turtles flying, center=(1034,195), contenteditable=True, type=text
		[217] image, center=(1757,195)
		[218] button Generate, center=(1838,195)
		heading Instantly Create a Song
		[223] image, center=(542,249)
		[229] heading Pop, 2020s, Summer, Nu-Disco, center=(406,293)
		[232] heading [Miel San Marcos, Worship, Christian, Inspirational, Emotional, Male Vocalist, Female Vocalist, Piano, Electric Guitar, Drum Set, 2010s], center=(732,293)
		[235] heading Country, 2020s, Storytelling, Southern Rock, center=(1104,293)
		[238] heading Sentimental, Emotional, 1980s, Romantic, Melancholic, Pop, R&B, center=(1477,293)
		heading Guitar Virtuoso, Electric Blues, Texas Blues
		heading Blues, 1970s, Electric Blues
		heading Lo-Fi, Chillout, Downtempo
		heading A Blues Song Played By A Blues Power Trio. Incredible Guitar Solos With Heavy Bending. Thick Bass Tone.
		heading Blues, 1970s, Electric Blues
		heading Summer, Nu-Disco, 2020s, Romantic, Dance
		image
		[260] image, center=(1880,299)
		heading Groups For You
		[264] button Create a Group, center=(562,339)
			image
		[273] image Zaptrem's Group, center=(368,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-ee12a798-6b2f-4d90-9d4b-cd035d9a0a48?width=256&quality=75&resize=contain'
		[276] heading Zaptrem's Group, center=(530,402)
		[277] paragraph, center=(530,421), inner_text=7 Members
			StaticText 7
			StaticText Members
		paragraph
			StaticText Moderated by
			[279] link zaptrem, center=(566,441), url='https://sonauto.ai/artist/zaptrem'
		[280] paragraph, center=(530,469), inner_text=Feed me soooongs
			StaticText Feed me soooongs
		[282] button Play, center=(486,520)
			image
		[286] image Bluesman420 Fan Club, center=(734,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1507227c-e538-4a01-9ec0-967a0ac68902?width=256&quality=75&resize=contain'
		[289] heading Bluesman420 Fan Club, center=(900,413)
		[290] paragraph, center=(900,444), inner_text=5 Members
			StaticText 5
			StaticText Members
		paragraph
			StaticText Moderated by
			[292] link zaptrem, center=(932,463), url='https://sonauto.ai/artist/zaptrem'
		[293] paragraph, center=(900,492), inner_text=It's 106 miles to Chicago, we got a full tank of gas, half a pack of cigarettes, it's dark... and we're wearing sunglasses.
			StaticText It's 106 miles to Chicago, we got a full tank of gas, half a pack of cigarettes, it's dark... and we're wearing sunglasses.
		[295] button Play, center=(852,526)
			image
		[299] image Weird & Wacky Texts & Topics, center=(1100,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-7c2da748-49a4-43c8-9f4a-432a2ae1c561?width=256&quality=75&resize=contain'
		[302] heading Weird & Wacky Texts & Topics, center=(1266,413)
		[303] paragraph, center=(1266,444), inner_text=4 Members
			StaticText 4
			StaticText Members
		paragraph
			StaticText Moderated by
			[305] link chaos, center=(1292,463), url='https://sonauto.ai/artist/chaos'
		[306] paragraph, center=(1266,492), inner_text=Can you really sing a song about that stuff? Yup. Sure can.
			StaticText Can you really sing a song about that stuff? Yup. Sure can.
		[308] button Play, center=(1218,526)
			image
		[312] image Nice Voice, center=(1466,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-82686aa1-5a53-42d6-bb86-80b71defb209?width=256&quality=75&resize=contain'
		[315] heading Nice Voice, center=(1632,402)
		[316] paragraph, center=(1632,421), inner_text=3 Members
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			[318] link chaos, center=(1658,441), url='https://sonauto.ai/artist/chaos'
		[319] paragraph, center=(1632,469), inner_text=If you think the voice sounds great and is good quality, put it here.
			StaticText If you think the voice sounds great and is good quality, put it here.
		[321] button Play, center=(1584,520)
			image
		image Tilted Dancefloor, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-841b4468-df7a-428d-80c4-9a8494c4cb87?width=256&quality=75&resize=contain'
		heading Tilted Dancefloor
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link chaos, url='https://sonauto.ai/artist/chaos'
		paragraph
			StaticText Energetic with a twist of humor
		button Play
			image
		image Dark Synthwave, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1a7fa429-74d3-40f0-bac1-c78594847bb5?width=256&quality=75&resize=contain'
		heading Dark Synthwave
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link hayden, url='https://sonauto.ai/artist/hayden'
		paragraph
			StaticText Dark electronic melodic metal and synthwave
		button Play
			image
		image Chill Vibes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-6afa6e51-c830-45e9-8f71-032a1c50ec83?width=256&quality=75&resize=contain'
		heading Chill Vibes
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link hayden, url='https://sonauto.ai/artist/hayden'
		paragraph
		button Play
			image
		image Various Instrumentals, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-998f8cf6-7740-42be-ab67-6e983502abb4?width=256&quality=75&resize=contain'
		heading Various Instrumentals
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link whosthere, url='https://sonauto.ai/artist/whosthere'
		paragraph
			StaticText For instrumentals lovers
		button Play
			image
		image Protest Songs, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-a4e4e13c-e498-4dd6-9957-df69d208a2d5?width=256&quality=75&resize=contain'
		heading Protest Songs
		paragraph
			StaticText 2
			StaticText Members
		paragraph
			StaticText Moderated by
			link chaos, url='https://sonauto.ai/artist/chaos'
		paragraph
			StaticText Old people shouting at the sky come here to vent.
		button Play
			image
		image
		[391] image, center=(1880,462)
		heading Staff Picks
		[396] button, center=(444,591)
			image
		[405] image Leavin' You Behind, center=(368,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-b03dcac9-65d8-41ab-a850-dda75cb88114?width=256&quality=75&resize=contain'
		[407] image, center=(318,770)
		StaticText v2
		[412] link Leavin' You Behind, center=(540,659), url='https://sonauto.ai/song/ab00865a-10e5-4993-a3d9-adbb4876beb9'
			heading Leavin' You Behind
		[408] div, center=(416,776), inner_text=v2
		[414] link zaptrem, center=(480,681), url='https://sonauto.ai/artist/zaptrem'
		[417] link summer, center=(490,724), url='https://sonauto.ai/tag/summer'
		[419] link 2020s, center=(562,724), url='https://sonauto.ai/tag/2020s'
		[421] link pop, center=(623,724), url='https://sonauto.ai/tag/pop'
		image
		paragraph
			StaticText 822
		[428] image, center=(524,754)
		paragraph
			StaticText 11
		[430] link 2, center=(578,754), url='https://sonauto.ai/song/ab00865a-10e5-4993-a3d9-adbb4876beb9'
			image
			paragraph
		[433] button, center=(617,754), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 6 days ago
		[440] image Alright, center=(783,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-668bf78d-dff4-4a22-8d5b-1a2bd48cf08e?width=256&quality=75&resize=contain'
		[442] image, center=(733,770)
		StaticText v2
		[447] link Alright, center=(900,659), url='https://sonauto.ai/song/cc599224-25b1-4521-bb7d-63d63addd13b'
			heading Alright
		[443] div, center=(832,776), inner_text=v2
		[449] link coolsong, center=(898,681), url='https://sonauto.ai/artist/coolsong'
		[452] link 2020s, center=(900,709), url='https://sonauto.ai/tag/2020s'
		[454] link country, center=(970,709), url='https://sonauto.ai/tag/country'
		[456] link southern rock, center=(922,742), url='https://sonauto.ai/tag/southern%20rock'
		image
		paragraph
			StaticText 205
		[463] image, center=(939,772)
		paragraph
			StaticText 5
		[465] link 2, center=(990,772), url='https://sonauto.ai/song/cc599224-25b1-4521-bb7d-63d63addd13b'
			image
			paragraph
		[468] button, center=(1029,772), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 5 days ago
		[475] image We Stand, center=(1198,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-e668a6b3-ccca-4c36-a2a3-e42035389e5e?width=256&quality=75&resize=contain'
		[477] image, center=(1148,770)
		StaticText v2
		[482] link We Stand, center=(1328,659), url='https://sonauto.ai/song/cdd77c72-99bd-4247-b83f-ecaae849fdd2'
			heading We Stand
		[478] div, center=(1246,776), inner_text=v2
		[484] link gonesvan, center=(1314,681), url='https://sonauto.ai/artist/gonesvan'
		[487] link male vocalist, center=(1335,709), url='https://sonauto.ai/tag/male%20vocalist'
		[489] link electric guitar, center=(1444,709), url='https://sonauto.ai/tag/electric%20guitar'
		[491] link christian, center=(1320,742), url='https://sonauto.ai/tag/christian'
		image
		paragraph
			StaticText 391
		[498] image, center=(1353,772)
		paragraph
			StaticText 6
		[500] link 2, center=(1404,772), url='https://sonauto.ai/song/cdd77c72-99bd-4247-b83f-ecaae849fdd2'
			image
			paragraph
		[503] button, center=(1444,772), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 7 days ago
		[510] image When it’s us, center=(1613,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-a7ed0653-8a2f-4408-85c5-7f5bb57f7d7f?width=256&quality=75&resize=contain'
		[512] image, center=(1563,770)
		StaticText v2
		[517] link When it’s us, center=(1754,659), url='https://sonauto.ai/song/edba394d-4003-4d9b-a960-0ad0b2ae2490'
			heading When it’s us
		[513] div, center=(1662,776), inner_text=v2
		[519] link gonesvan, center=(1730,681), url='https://sonauto.ai/artist/gonesvan'
		[522] link male vocalist, center=(1750,709), url='https://sonauto.ai/tag/male%20vocalist'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		[526] link k-ballad, center=(1735,742), url='https://sonauto.ai/tag/k-ballad'
		image
		paragraph
			StaticText 306
		[533] image, center=(1771,772)
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/edba394d-4003-4d9b-a960-0ad0b2ae2490'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Craving for Snacks, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_87490abc-2ad8-4a8c-b234-904c28fd30f1.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Craving for Snacks, url='https://sonauto.ai/song/87490abc-2ad8-4a8c-b234-904c28fd30f1'
			heading Craving for Snacks
		link chaos, url='https://sonauto.ai/artist/chaos'
		link country, url='https://sonauto.ai/tag/country'
		link bluegrass, url='https://sonauto.ai/tag/bluegrass'
		image
		paragraph
			StaticText 413
		image
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/87490abc-2ad8-4a8c-b234-904c28fd30f1'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Green Eyes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-da6fe498-0f13-4aa7-932c-02fbd81d328d?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Green Eyes, url='https://sonauto.ai/song/bf4c9cae-f33e-4dc5-a5a7-7abe63696448'
			heading Green Eyes
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link indie, url='https://sonauto.ai/tag/indie'
		link pop, url='https://sonauto.ai/tag/pop'
		link dance pop, url='https://sonauto.ai/tag/dance%20pop'
		image
		paragraph
			StaticText 269
		image
		paragraph
			StaticText 4
		link 0, url='https://sonauto.ai/song/bf4c9cae-f33e-4dc5-a5a7-7abe63696448'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Midnight Raid, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-5cc8897c-5900-4359-bcf4-ff6120b6ef8f?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Midnight Raid, url='https://sonauto.ai/song/9715ecb5-1865-46f9-b064-0e16725b4fa6'
			heading Midnight Raid
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link EDM, url='https://sonauto.ai/tag/EDM'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		link house, url='https://sonauto.ai/tag/house'
		image
		paragraph
			StaticText 312
		image
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/9715ecb5-1865-46f9-b064-0e16725b4fa6'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Crazy Friday Night, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-984cef64-d683-4743-935f-6ab8d8c9a828?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Crazy Friday Night, url='https://sonauto.ai/song/9e21b63b-0ac3-437c-88ae-05e57c67bd6f'
			heading Crazy Friday Night
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link pop, url='https://sonauto.ai/tag/pop'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		link party, url='https://sonauto.ai/tag/party'
		image
		paragraph
			StaticText 279
		image
		paragraph
			StaticText 4
		link 0, url='https://sonauto.ai/song/9e21b63b-0ac3-437c-88ae-05e57c67bd6f'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Don't Cry Now, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_ff718ead-ecb4-4348-8f0b-8d393bba657d.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Don't Cry Now, url='https://sonauto.ai/song/ff718ead-ecb4-4348-8f0b-8d393bba657d'
			heading Don't Cry Now
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link country, url='https://sonauto.ai/tag/country'
		link rock, url='https://sonauto.ai/tag/rock'
		link western, url='https://sonauto.ai/tag/western'
		image
		paragraph
			StaticText 244
		image
		paragraph
			StaticText 1
		link 0, url='https://sonauto.ai/song/ff718ead-ecb4-4348-8f0b-8d393bba657d'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Caught in the Past, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_f40f3424-273c-4770-8ff8-e2f455a932a2.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Caught in the Past, url='https://sonauto.ai/song/f40f3424-273c-4770-8ff8-e2f455a932a2'
			heading Caught in the Past
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link 2000s, url='https://sonauto.ai/tag/2000s'
		link pop, url='https://sonauto.ai/tag/pop'
		link breakup, url='https://sonauto.ai/tag/breakup'
		image
		paragraph
			StaticText 299
		image
		paragraph
			StaticText 5
		link 2, url='https://sonauto.ai/song/f40f3424-273c-4770-8ff8-e2f455a932a2'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image
		[752] image, center=(1880,729)
		heading Trending Posts
		[756] button, center=(494,878)
			image
		[758] combobox value='Trending', center=(584,878), expanded=False, hasPopup='listbox', inner_text=Trending, type=button
		grid
			gridcell 1970s Cop Movie Soundtrack v2 1970s Cop Movie Soundtrack whosthere blues rock lounge 8 1 0 Posted 3 hours ago
				[767] image 1970s Cop Movie Soundtrack, center=(368,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-164546f9-46c7-42ec-9570-20885dca42aa?width=256&quality=75&resize=contain'
				[769] image, center=(318,1060)
				StaticText v2
				[774] link 1970s Cop Movie Soundtrack, center=(584,949), url='https://sonauto.ai/song/44b0ed21-fe47-4856-a42f-a7ceb923dda2'
					heading 1970s Cop Movie Soundtrack
				[770] div, center=(416,1066), inner_text=v2
				[776] link whosthere, center=(486,971), url='https://sonauto.ai/artist/whosthere'
				[779] link blues rock, center=(497,1014), url='https://sonauto.ai/tag/blues%20rock'
				[781] link lounge, center=(578,1014), url='https://sonauto.ai/tag/lounge'
				image
				paragraph
					StaticText 8
				[788] image, center=(510,1044)
				paragraph
					StaticText 1
				[790] link 0, center=(559,1044), url='https://sonauto.ai/song/44b0ed21-fe47-4856-a42f-a7ceb923dda2'
					image
					paragraph
				[793] button, center=(599,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 3 hours ago
			gridcell Tyler's Pina Coladaburg v2 Tyler's Pina Coladaburg nlanza999 tropical 1970s island 3 0 0 Posted 4 hours ago
				[800] image Tyler's Pina Coladaburg, center=(914,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_4ce7e7ce-4970-4645-a910-b4a65d297259.webp?width=256&quality=75&resize=contain'
				[802] image, center=(864,1060)
				StaticText v2
				[807] link Tyler's Pina Coladaburg, center=(1108,949), url='https://sonauto.ai/song/4ce7e7ce-4970-4645-a910-b4a65d297259'
					heading Tyler's Pina Coladaburg
				[803] div, center=(962,1066), inner_text=v2
				[809] link nlanza999, center=(1032,971), url='https://sonauto.ai/artist/nlanza999'
				[812] link tropical, center=(1034,1014), url='https://sonauto.ai/tag/tropical'
				[814] link 1970s, center=(1104,1014), url='https://sonauto.ai/tag/1970s'
				[816] link island, center=(1170,1014), url='https://sonauto.ai/tag/island'
				image
				paragraph
					StaticText 3
				[823] image, center=(1056,1044)
				paragraph
					StaticText 0
				[825] link 0, center=(1108,1044), url='https://sonauto.ai/song/4ce7e7ce-4970-4645-a910-b4a65d297259'
					image
					paragraph
				[828] button, center=(1148,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 4 hours ago
			gridcell Tyler by the sea v2 Tyler by the sea nlanza999 tropical easy listening 2020s 4 0 0 Posted 4 hours ago
				[835] image Tyler by the sea, center=(1460,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_4cf260e8-26be-40d1-8eef-f664d60acc50.webp?width=256&quality=75&resize=contain'
				[837] image, center=(1410,1060)
				StaticText v2
				[842] link Tyler by the sea, center=(1618,949), url='https://sonauto.ai/song/4cf260e8-26be-40d1-8eef-f664d60acc50'
					heading Tyler by the sea
				[838] div, center=(1508,1066), inner_text=v2
				[844] link nlanza999, center=(1578,971), url='https://sonauto.ai/artist/nlanza999'
				[847] link tropical, center=(1580,1014), url='https://sonauto.ai/tag/tropical'
				[849] link easy listening, center=(1673,1014), url='https://sonauto.ai/tag/easy%20listening'
				[851] link 2020s, center=(1762,1014), url='https://sonauto.ai/tag/2020s'
				image
				paragraph
					StaticText 4
				[858] image, center=(1602,1044)
				paragraph
					StaticText 0
				[860] link 0, center=(1654,1044), url='https://sonauto.ai/song/4cf260e8-26be-40d1-8eef-f664d60acc50'
					image
					paragraph
				[863] button, center=(1694,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 4 hours ago
			gridcell Yamaha Keyboard Built-In Music-Core Vibes v2 Yamaha Keyboard Built-In Music-Core Vibes zaptrem new age instrumental bossa nova 6 0 0 Posted 5 hours ago
				image Yamaha Keyboard Built-In Music-Core Vibes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-267ca5d5-eb9f-4d6a-b627-0a97a3cf0d68?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Yamaha Keyboard Built-In Music-Core Vibes, url='https://sonauto.ai/song/5bd9a75f-4c9a-461f-b597-22eb99041b4d'
					heading Yamaha Keyboard Built-In Music-Core Vibes
				link zaptrem, url='https://sonauto.ai/artist/zaptrem'
				link new age, url='https://sonauto.ai/tag/new%20age'
				link instrumental, url='https://sonauto.ai/tag/instrumental'
				link bossa nova, url='https://sonauto.ai/tag/bossa%20nova'
				image
				paragraph
					StaticText 6
				image
				paragraph
					StaticText 0
				link 0, url='https://sonauto.ai/song/5bd9a75f-4c9a-461f-b597-22eb99041b4d'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
			gridcell Chill Feelings v2 Chill Feelings stickguy early 2010s world dream pop 8 0 0 Posted 5 hours ago
				image Chill Feelings, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-47eba7d4-bec2-4fcd-98f9-bef720ba0c3d?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Chill Feelings, url='https://sonauto.ai/song/f6d81b92-643c-4145-8710-6d3a3e5e2d8c'
					heading Chill Feelings
				link stickguy, url='https://sonauto.ai/artist/stickguy'
				link early 2010s, url='https://sonauto.ai/tag/early%202010s'
				link world, url='https://sonauto.ai/tag/world'
				link dream pop, url='https://sonauto.ai/tag/dream%20pop'
				image
				paragraph
					StaticText 8
				image
				paragraph
					StaticText 0
				link 0, url='https://sonauto.ai/song/f6d81b92-643c-4145-8710-6d3a3e5e2d8c'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
			gridcell Christmas A-Capella v2 Christmas A-Capella zaptrem holiday vocal harmony 16 2 0 Posted 5 hours ago
				image Christmas A-Capella, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-1b793f98-e10a-41ee-938c-9b4d84f874a5?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Christmas A-Capella, url='https://sonauto.ai/song/30143d59-692e-4019-86e4-603e33791cca'
					heading Christmas A-Capella
				link zaptrem, url='https://sonauto.ai/artist/zaptrem'
				link holiday, url='https://sonauto.ai/tag/holiday'
				link vocal, url='https://sonauto.ai/tag/vocal'
				link harmony, url='https://sonauto.ai/tag/harmony'
				image
				paragraph
					StaticText 16
				image
				paragraph
					StaticText 2
				link 0, url='https://sonauto.ai/song/30143d59-692e-4019-86e4-603e33791cca'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
		button Show More
		heading Trending Categories
		link 2020s, url='https://sonauto.ai/tag/2020s'
			heading 2020s
		link Male Vocalist, url='https://sonauto.ai/tag/male%20vocalist'
			heading Male Vocalist
		link Pop, url='https://sonauto.ai/tag/pop'
			heading Pop
		link Emotional, url='https://sonauto.ai/tag/emotional'
			heading Emotional
		link Blues, url='https://sonauto.ai/tag/blues'
			heading Blues
		link Female Vocalist, url='https://sonauto.ai/tag/female%20vocalist'
			heading Female Vocalist
		link Electronic, url='https://sonauto.ai/tag/electronic'
			heading Electronic
		link Rock, url='https://sonauto.ai/tag/rock'
			heading Rock
		link Electric Guitar, url='https://sonauto.ai/tag/electric%20guitar'
			heading Electric Guitar
		link Rap, url='https://sonauto.ai/tag/rap'
			heading Rap
		link Electric Blues, url='https://sonauto.ai/tag/electric%20blues'
			heading Electric Blues
		link Hip Hop, url='https://sonauto.ai/tag/hip%20hop'
			heading Hip Hop
		link Piano, url='https://sonauto.ai/tag/piano'
			heading Piano
		link 1970s, url='https://sonauto.ai/tag/1970s'
			heading 1970s
		link Nu-Disco, url='https://sonauto.ai/tag/nu-disco'
			heading Nu-Disco
		link Instrumental, url='https://sonauto.ai/tag/instrumental'
			heading Instrumental
		link Uplifting, url='https://sonauto.ai/tag/uplifting'
			heading Uplifting
		link Melodic, url='https://sonauto.ai/tag/melodic'
			heading Melodic
		link Synthpop, url='https://sonauto.ai/tag/synthpop'
			heading Synthpop
		link 2010s, url='https://sonauto.ai/tag/2010s'
			heading 2010s
		image
		image
	region Notifications (F8)
		list
```
</details>



```
RootWebArea Sonauto | New Music by You, focused, url='https://sonauto.ai/'
	alert, atomic
	paragraph
		StaticText Welcome to Sonauto v2 beta! Your v1 generations will be available for a limited time at
		[52] link v1.sonauto.ai, center=(1276,28), url='https://v1.sonauto.ai/'
```
<details><summary>Show more</summary>

```
		StaticText .
	[53] button, center=(1884,28)
		image
	[59] link Sonauto Logo Sonauto, center=(126,96), inner_text=Sonauto, url='https://sonauto.ai/'
		image Sonauto Logo, url='https://sonauto.ai/_next/image?url=%2Fimages%2Fnew_bird.png&w=32&q=75'
	navigation
		[62] link Home, center=(128,150), url='https://sonauto.ai/'
			image
		[64] link Search, center=(128,186), url='https://sonauto.ai/search'
			image
		[66] link Make Music, center=(128,222), url='https://sonauto.ai/'
			image
	paragraph
		StaticText Trending
	[71] button Playlist, center=(194,283)
		image
	[75] combobox value='All', center=(128,325), expanded=False, hasPopup='listbox', inner_text=All, type=button
	[80] link art Just Relax, center=(128,381), inner_text=Just Relax, url='https://sonauto.ai/playlist/ab0f22f8-64c6-454b-9a12-fb14f4d48465'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-ab0f22f8-64c6-454b-9a12-fb14f4d48465?width=32&quality=75&resize=contain'
	[83] link art Dark Radio Network, center=(128,417), inner_text=Dark Radio Network, url='https://sonauto.ai/playlist/65fdf34c-28d5-47dc-801c-f156a78638d4'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-65fdf34c-28d5-47dc-801c-f156a78638d4?width=32&quality=75&resize=contain'
	[86] link Test, center=(128,453), url='https://sonauto.ai/playlist/8f58dc22-0e35-42d3-bc0c-74a044c68f83'
	[89] link My list, center=(128,489), url='https://sonauto.ai/playlist/7dd42422-563f-4e2d-95f0-62e8ac4ac0df'
	[92] link art GREEN BITES, center=(128,525), inner_text=GREEN BITES, url='https://sonauto.ai/playlist/476f7f74-0f8a-4100-ab4a-ead30aa554df'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-937b0f24-7aaa-4357-9e04-43488dddf699?width=32&quality=75&resize=contain'
	[95] link art Klangraum V2 Tests, center=(128,561), inner_text=Klangraum V2 Tests, url='https://sonauto.ai/playlist/a1f1dd9b-e58f-4812-a1e6-024e69f1af37'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-a1f1dd9b-e58f-4812-a1e6-024e69f1af37?width=32&quality=75&resize=contain'
	[98] link My songs, center=(128,597), url='https://sonauto.ai/playlist/f580ce69-e977-4810-92b3-4f4815c4b86f'
	[101] link The Show, center=(128,633), url='https://sonauto.ai/playlist/ae20fb05-042d-4032-b27d-e71785eeda08'
	[104] link art DID HE, center=(128,669), inner_text=DID HE, url='https://sonauto.ai/playlist/dbbd1058-a2eb-41cf-bd30-c350b1dfde90'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-dbbd1058-a2eb-41cf-bd30-c350b1dfde90?width=32&quality=75&resize=contain'
	[107] link cool, center=(128,705), url='https://sonauto.ai/playlist/5491c699-3f58-4762-913f-ffe690282a63'
	[110] link Luis, center=(128,741), url='https://sonauto.ai/playlist/6831c1cb-0828-4eec-95cc-dfdba071eae7'
	[113] link tyghghhg, center=(128,777), url='https://sonauto.ai/playlist/b46544c7-931f-434e-a501-4aa23e37a89f'
	link art Bluesman420 Fan Club, url='https://sonauto.ai/group/c97cd6bf-475b-447c-8db4-11a9dc2d526a'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1507227c-e538-4a01-9ec0-967a0ac68902?width=32&quality=75&resize=contain'
	link art Various Instrumentals, url='https://sonauto.ai/group/998f8cf6-7740-42be-ab67-6e983502abb4'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-998f8cf6-7740-42be-ab67-6e983502abb4?width=32&quality=75&resize=contain'
	link art Dark Radio, url='https://sonauto.ai/group/87db116d-1613-4574-8785-fb2cb613d18f'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-87db116d-1613-4574-8785-fb2cb613d18f?width=32&quality=75&resize=contain'
	link art Rubinyan theme Song, url='https://sonauto.ai/group/e7c907fb-9324-4389-961b-59880d374568'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-e7c907fb-9324-4389-961b-59880d374568?width=32&quality=75&resize=contain'
	link Rescate Brasil, url='https://sonauto.ai/group/05ed4a63-e238-4c92-a11e-df5dfeec01e2'
	link my music, url='https://sonauto.ai/group/8c296cfa-ea98-45c1-9b62-338cb85f137a'
	link Mm, url='https://sonauto.ai/group/49828acd-64b5-46e5-b45f-a548172e3f64'
	link art vives, url='https://sonauto.ai/group/22fa8e47-8007-48b9-ab7d-159979cf6a2c'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-97cc5c0d-b5ef-4e7c-8fee-f02e3db5a3e8?width=32&quality=75&resize=contain'
	link Heavy metal, url='https://sonauto.ai/group/f7f4e492-9701-4af9-98de-610c00d6e8e9'
	link art Música, url='https://sonauto.ai/group/2e28bd75-83ad-4055-b2d0-19fb1b687378'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-2e28bd75-83ad-4055-b2d0-19fb1b687378?width=32&quality=75&resize=contain'
	link art Davidounours, url='https://sonauto.ai/group/1a956452-71d5-4800-8a96-0ec8346bac0d'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-1a956452-71d5-4800-8a96-0ec8346bac0d?width=32&quality=75&resize=contain'
	link Hddjdh, url='https://sonauto.ai/group/9f5f4f3a-86aa-4e00-a270-b95e294c21c6'
	link Need For Speed Soundtrack, url='https://sonauto.ai/group/db78b071-5d27-49d6-af33-f115692bdaa6'
	link art Killer Raps, url='https://sonauto.ai/group/0a9833ea-3417-48fc-a11f-4a5669741ece'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-0a9833ea-3417-48fc-a11f-4a5669741ece?width=32&quality=75&resize=contain'
	link Так выбрать из балкона, url='https://sonauto.ai/group/9be2dbd8-08b6-4d09-bc72-c1981ba72277'
	link House, url='https://sonauto.ai/group/13f7e378-c201-4a6f-ad86-3b500505353b'
	link art Nothin but the Blues, url='https://sonauto.ai/group/d54b03a1-cd7b-4490-8900-81d49fc37f6e'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-d54b03a1-cd7b-4490-8900-81d49fc37f6e?width=32&quality=75&resize=contain'
	link art Le hobo, url='https://sonauto.ai/group/1148e019-c74c-4069-9b3c-f6cb290c3cf0'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-1148e019-c74c-4069-9b3c-f6cb290c3cf0?width=32&quality=75&resize=contain'
	link art Unusual Dubstep, url='https://sonauto.ai/group/ac84677c-9503-416f-a533-d5f05c9a2abc'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-ac84677c-9503-416f-a533-d5f05c9a2abc?width=32&quality=75&resize=contain'
	link art Cultural Mix & Crossovers, url='https://sonauto.ai/group/4bcec888-8969-43ac-a0c7-75fcd019db9f'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-4bcec888-8969-43ac-a0c7-75fcd019db9f?width=32&quality=75&resize=contain'
	link art Basement Dancefloor, url='https://sonauto.ai/group/b62764aa-2922-4b3e-8f6d-9a34871b391b'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-b62764aa-2922-4b3e-8f6d-9a34871b391b?width=32&quality=75&resize=contain'
	link art Universal Music, url='https://sonauto.ai/group/14a2e296-9039-48dd-a5b9-25578ba8b8e1'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-14a2e296-9039-48dd-a5b9-25578ba8b8e1?width=32&quality=75&resize=contain'
	[184] link Discord, center=(112,1005), url='https://discord.gg/pfXar3ChH8'
		image Discord icon, url='https://sonauto.ai/discord-white.svg'
	[186] link Twitter, center=(146,1005), url='https://x.com/SonautoAI'
		image Twitter icon, url='https://sonauto.ai/twitter-icon.svg'
	[189] link Terms, center=(97,1040), url='https://sonauto.ai/tos'
	StaticText ·
	[191] link Privacy, center=(156,1040), url='https://sonauto.ai/privacy'
	[196] button, center=(302,88)
		image
	[198] button, center=(342,88)
		image
	[201] link Install App, center=(1741,88), url='https://sonauto.ai/install'
		image
	[204] image, center=(1828,88)
	StaticText Log In
	main
		heading Start Your Masterpiece
		image
		[215] textbox A rock song about turtles flying, center=(1034,195), contenteditable=True, type=text
		[217] image, center=(1757,195)
		[218] button Generate, center=(1838,195)
		heading Instantly Create a Song
		[223] image, center=(542,249)
		[229] heading Pop, 2020s, Summer, Nu-Disco, center=(406,293)
		[232] heading [Miel San Marcos, Worship, Christian, Inspirational, Emotional, Male Vocalist, Female Vocalist, Piano, Electric Guitar, Drum Set, 2010s], center=(732,293)
		[235] heading Country, 2020s, Storytelling, Southern Rock, center=(1104,293)
		[238] heading Sentimental, Emotional, 1980s, Romantic, Melancholic, Pop, R&B, center=(1477,293)
		heading Guitar Virtuoso, Electric Blues, Texas Blues
		heading Blues, 1970s, Electric Blues
		heading Lo-Fi, Chillout, Downtempo
		heading A Blues Song Played By A Blues Power Trio. Incredible Guitar Solos With Heavy Bending. Thick Bass Tone.
		heading Blues, 1970s, Electric Blues
		heading Summer, Nu-Disco, 2020s, Romantic, Dance
		image
		[260] image, center=(1880,299)
		heading Groups For You
		[264] button Create a Group, center=(562,339)
			image
		[273] image Zaptrem's Group, center=(368,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-ee12a798-6b2f-4d90-9d4b-cd035d9a0a48?width=256&quality=75&resize=contain'
		[276] heading Zaptrem's Group, center=(530,402)
		[277] paragraph, center=(530,421), inner_text=7 Members
			StaticText 7
			StaticText Members
		paragraph
			StaticText Moderated by
			[279] link zaptrem, center=(566,441), url='https://sonauto.ai/artist/zaptrem'
		[280] paragraph, center=(530,469), inner_text=Feed me soooongs
			StaticText Feed me soooongs
		[282] button Play, center=(486,520)
			image
		[286] image Bluesman420 Fan Club, center=(734,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1507227c-e538-4a01-9ec0-967a0ac68902?width=256&quality=75&resize=contain'
		[289] heading Bluesman420 Fan Club, center=(900,413)
		[290] paragraph, center=(900,444), inner_text=5 Members
			StaticText 5
			StaticText Members
		paragraph
			StaticText Moderated by
			[292] link zaptrem, center=(932,463), url='https://sonauto.ai/artist/zaptrem'
		[293] paragraph, center=(900,492), inner_text=It's 106 miles to Chicago, we got a full tank of gas, half a pack of cigarettes, it's dark... and we're wearing sunglasses.
			StaticText It's 106 miles to Chicago, we got a full tank of gas, half a pack of cigarettes, it's dark... and we're wearing sunglasses.
		[295] button Play, center=(852,526)
			image
		[299] image Weird & Wacky Texts & Topics, center=(1100,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-7c2da748-49a4-43c8-9f4a-432a2ae1c561?width=256&quality=75&resize=contain'
		[302] heading Weird & Wacky Texts & Topics, center=(1266,413)
		[303] paragraph, center=(1266,444), inner_text=4 Members
			StaticText 4
			StaticText Members
		paragraph
			StaticText Moderated by
			[305] link chaos, center=(1292,463), url='https://sonauto.ai/artist/chaos'
		[306] paragraph, center=(1266,492), inner_text=Can you really sing a song about that stuff? Yup. Sure can.
			StaticText Can you really sing a song about that stuff? Yup. Sure can.
		[308] button Play, center=(1218,526)
			image
		[312] image Nice Voice, center=(1466,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-82686aa1-5a53-42d6-bb86-80b71defb209?width=256&quality=75&resize=contain'
		[315] heading Nice Voice, center=(1632,402)
		[316] paragraph, center=(1632,421), inner_text=3 Members
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			[318] link chaos, center=(1658,441), url='https://sonauto.ai/artist/chaos'
		[319] paragraph, center=(1632,469), inner_text=If you think the voice sounds great and is good quality, put it here.
			StaticText If you think the voice sounds great and is good quality, put it here.
		[321] button Play, center=(1584,520)
			image
		image Tilted Dancefloor, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-841b4468-df7a-428d-80c4-9a8494c4cb87?width=256&quality=75&resize=contain'
		heading Tilted Dancefloor
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link chaos, url='https://sonauto.ai/artist/chaos'
		paragraph
			StaticText Energetic with a twist of humor
		button Play
			image
		image Dark Synthwave, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1a7fa429-74d3-40f0-bac1-c78594847bb5?width=256&quality=75&resize=contain'
		heading Dark Synthwave
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link hayden, url='https://sonauto.ai/artist/hayden'
		paragraph
			StaticText Dark electronic melodic metal and synthwave
		button Play
			image
		image Chill Vibes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-6afa6e51-c830-45e9-8f71-032a1c50ec83?width=256&quality=75&resize=contain'
		heading Chill Vibes
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link hayden, url='https://sonauto.ai/artist/hayden'
		paragraph
		button Play
			image
		image Various Instrumentals, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-998f8cf6-7740-42be-ab67-6e983502abb4?width=256&quality=75&resize=contain'
		heading Various Instrumentals
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link whosthere, url='https://sonauto.ai/artist/whosthere'
		paragraph
			StaticText For instrumentals lovers
		button Play
			image
		image Protest Songs, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-a4e4e13c-e498-4dd6-9957-df69d208a2d5?width=256&quality=75&resize=contain'
		heading Protest Songs
		paragraph
			StaticText 2
			StaticText Members
		paragraph
			StaticText Moderated by
			link chaos, url='https://sonauto.ai/artist/chaos'
		paragraph
			StaticText Old people shouting at the sky come here to vent.
		button Play
			image
		image
		[391] image, center=(1880,462)
		heading Staff Picks
		[396] button, center=(444,591)
			image
		[405] image Leavin' You Behind, center=(368,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-b03dcac9-65d8-41ab-a850-dda75cb88114?width=256&quality=75&resize=contain'
		[407] image, center=(318,770)
		StaticText v2
		[412] link Leavin' You Behind, center=(540,659), url='https://sonauto.ai/song/ab00865a-10e5-4993-a3d9-adbb4876beb9'
			heading Leavin' You Behind
		[408] div, center=(416,776), inner_text=v2
		[414] link zaptrem, center=(480,681), url='https://sonauto.ai/artist/zaptrem'
		[417] link summer, center=(490,724), url='https://sonauto.ai/tag/summer'
		[419] link 2020s, center=(562,724), url='https://sonauto.ai/tag/2020s'
		[421] link pop, center=(623,724), url='https://sonauto.ai/tag/pop'
		image
		paragraph
			StaticText 822
		[428] image, center=(524,754)
		paragraph
			StaticText 11
		[430] link 2, center=(578,754), url='https://sonauto.ai/song/ab00865a-10e5-4993-a3d9-adbb4876beb9'
			image
			paragraph
		[433] button, center=(617,754), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 6 days ago
		[440] image Alright, center=(783,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-668bf78d-dff4-4a22-8d5b-1a2bd48cf08e?width=256&quality=75&resize=contain'
		[442] image, center=(733,770)
		StaticText v2
		[447] link Alright, center=(900,659), url='https://sonauto.ai/song/cc599224-25b1-4521-bb7d-63d63addd13b'
			heading Alright
		[443] div, center=(832,776), inner_text=v2
		[449] link coolsong, center=(898,681), url='https://sonauto.ai/artist/coolsong'
		[452] link 2020s, center=(900,709), url='https://sonauto.ai/tag/2020s'
		[454] link country, center=(970,709), url='https://sonauto.ai/tag/country'
		[456] link southern rock, center=(922,742), url='https://sonauto.ai/tag/southern%20rock'
		image
		paragraph
			StaticText 205
		[463] image, center=(939,772)
		paragraph
			StaticText 5
		[465] link 2, center=(990,772), url='https://sonauto.ai/song/cc599224-25b1-4521-bb7d-63d63addd13b'
			image
			paragraph
		[468] button, center=(1029,772), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 5 days ago
		[475] image We Stand, center=(1198,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-e668a6b3-ccca-4c36-a2a3-e42035389e5e?width=256&quality=75&resize=contain'
		[477] image, center=(1148,770)
		StaticText v2
		[482] link We Stand, center=(1328,659), url='https://sonauto.ai/song/cdd77c72-99bd-4247-b83f-ecaae849fdd2'
			heading We Stand
		[478] div, center=(1246,776), inner_text=v2
		[484] link gonesvan, center=(1314,681), url='https://sonauto.ai/artist/gonesvan'
		[487] link male vocalist, center=(1335,709), url='https://sonauto.ai/tag/male%20vocalist'
		[489] link electric guitar, center=(1444,709), url='https://sonauto.ai/tag/electric%20guitar'
		[491] link christian, center=(1320,742), url='https://sonauto.ai/tag/christian'
		image
		paragraph
			StaticText 391
		[498] image, center=(1353,772)
		paragraph
			StaticText 6
		[500] link 2, center=(1404,772), url='https://sonauto.ai/song/cdd77c72-99bd-4247-b83f-ecaae849fdd2'
			image
			paragraph
		[503] button, center=(1444,772), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 7 days ago
		[510] image When it’s us, center=(1613,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-a7ed0653-8a2f-4408-85c5-7f5bb57f7d7f?width=256&quality=75&resize=contain'
		[512] image, center=(1563,770)
		StaticText v2
		[517] link When it’s us, center=(1754,659), url='https://sonauto.ai/song/edba394d-4003-4d9b-a960-0ad0b2ae2490'
			heading When it’s us
		[513] div, center=(1662,776), inner_text=v2
		[519] link gonesvan, center=(1730,681), url='https://sonauto.ai/artist/gonesvan'
		[522] link male vocalist, center=(1750,709), url='https://sonauto.ai/tag/male%20vocalist'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		[526] link k-ballad, center=(1735,742), url='https://sonauto.ai/tag/k-ballad'
		image
		paragraph
			StaticText 306
		[533] image, center=(1771,772)
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/edba394d-4003-4d9b-a960-0ad0b2ae2490'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Craving for Snacks, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_87490abc-2ad8-4a8c-b234-904c28fd30f1.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Craving for Snacks, url='https://sonauto.ai/song/87490abc-2ad8-4a8c-b234-904c28fd30f1'
			heading Craving for Snacks
		link chaos, url='https://sonauto.ai/artist/chaos'
		link country, url='https://sonauto.ai/tag/country'
		link bluegrass, url='https://sonauto.ai/tag/bluegrass'
		image
		paragraph
			StaticText 413
		image
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/87490abc-2ad8-4a8c-b234-904c28fd30f1'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Green Eyes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-da6fe498-0f13-4aa7-932c-02fbd81d328d?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Green Eyes, url='https://sonauto.ai/song/bf4c9cae-f33e-4dc5-a5a7-7abe63696448'
			heading Green Eyes
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link indie, url='https://sonauto.ai/tag/indie'
		link pop, url='https://sonauto.ai/tag/pop'
		link dance pop, url='https://sonauto.ai/tag/dance%20pop'
		image
		paragraph
			StaticText 269
		image
		paragraph
			StaticText 4
		link 0, url='https://sonauto.ai/song/bf4c9cae-f33e-4dc5-a5a7-7abe63696448'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Midnight Raid, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-5cc8897c-5900-4359-bcf4-ff6120b6ef8f?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Midnight Raid, url='https://sonauto.ai/song/9715ecb5-1865-46f9-b064-0e16725b4fa6'
			heading Midnight Raid
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link EDM, url='https://sonauto.ai/tag/EDM'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		link house, url='https://sonauto.ai/tag/house'
		image
		paragraph
			StaticText 312
		image
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/9715ecb5-1865-46f9-b064-0e16725b4fa6'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Crazy Friday Night, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-984cef64-d683-4743-935f-6ab8d8c9a828?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Crazy Friday Night, url='https://sonauto.ai/song/9e21b63b-0ac3-437c-88ae-05e57c67bd6f'
			heading Crazy Friday Night
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link pop, url='https://sonauto.ai/tag/pop'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		link party, url='https://sonauto.ai/tag/party'
		image
		paragraph
			StaticText 279
		image
		paragraph
			StaticText 4
		link 0, url='https://sonauto.ai/song/9e21b63b-0ac3-437c-88ae-05e57c67bd6f'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Don't Cry Now, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_ff718ead-ecb4-4348-8f0b-8d393bba657d.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Don't Cry Now, url='https://sonauto.ai/song/ff718ead-ecb4-4348-8f0b-8d393bba657d'
			heading Don't Cry Now
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link country, url='https://sonauto.ai/tag/country'
		link rock, url='https://sonauto.ai/tag/rock'
		link western, url='https://sonauto.ai/tag/western'
		image
		paragraph
			StaticText 244
		image
		paragraph
			StaticText 1
		link 0, url='https://sonauto.ai/song/ff718ead-ecb4-4348-8f0b-8d393bba657d'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Caught in the Past, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_f40f3424-273c-4770-8ff8-e2f455a932a2.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Caught in the Past, url='https://sonauto.ai/song/f40f3424-273c-4770-8ff8-e2f455a932a2'
			heading Caught in the Past
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link 2000s, url='https://sonauto.ai/tag/2000s'
		link pop, url='https://sonauto.ai/tag/pop'
		link breakup, url='https://sonauto.ai/tag/breakup'
		image
		paragraph
			StaticText 299
		image
		paragraph
			StaticText 5
		link 2, url='https://sonauto.ai/song/f40f3424-273c-4770-8ff8-e2f455a932a2'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image
		[752] image, center=(1880,729)
		heading Trending Posts
		[756] button, center=(494,878)
			image
		[758] combobox value='Trending', center=(584,878), expanded=False, hasPopup='listbox', inner_text=Trending, type=button
		grid
			gridcell 1970s Cop Movie Soundtrack v2 1970s Cop Movie Soundtrack whosthere blues rock lounge 8 1 0 Posted 3 hours ago
				[767] image 1970s Cop Movie Soundtrack, center=(368,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-164546f9-46c7-42ec-9570-20885dca42aa?width=256&quality=75&resize=contain'
				[769] image, center=(318,1060)
				StaticText v2
				[774] link 1970s Cop Movie Soundtrack, center=(584,949), url='https://sonauto.ai/song/44b0ed21-fe47-4856-a42f-a7ceb923dda2'
					heading 1970s Cop Movie Soundtrack
				[770] div, center=(416,1066), inner_text=v2
				[776] link whosthere, center=(486,971), url='https://sonauto.ai/artist/whosthere'
				[779] link blues rock, center=(497,1014), url='https://sonauto.ai/tag/blues%20rock'
				[781] link lounge, center=(578,1014), url='https://sonauto.ai/tag/lounge'
				image
				paragraph
					StaticText 8
				[788] image, center=(510,1044)
				paragraph
					StaticText 1
				[790] link 0, center=(559,1044), url='https://sonauto.ai/song/44b0ed21-fe47-4856-a42f-a7ceb923dda2'
					image
					paragraph
				[793] button, center=(599,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 3 hours ago
			gridcell Tyler's Pina Coladaburg v2 Tyler's Pina Coladaburg nlanza999 tropical 1970s island 3 0 0 Posted 4 hours ago
				[800] image Tyler's Pina Coladaburg, center=(914,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_4ce7e7ce-4970-4645-a910-b4a65d297259.webp?width=256&quality=75&resize=contain'
				[802] image, center=(864,1060)
				StaticText v2
				[807] link Tyler's Pina Coladaburg, center=(1108,949), url='https://sonauto.ai/song/4ce7e7ce-4970-4645-a910-b4a65d297259'
					heading Tyler's Pina Coladaburg
				[803] div, center=(962,1066), inner_text=v2
				[809] link nlanza999, center=(1032,971), url='https://sonauto.ai/artist/nlanza999'
				[812] link tropical, center=(1034,1014), url='https://sonauto.ai/tag/tropical'
				[814] link 1970s, center=(1104,1014), url='https://sonauto.ai/tag/1970s'
				[816] link island, center=(1170,1014), url='https://sonauto.ai/tag/island'
				image
				paragraph
					StaticText 3
				[823] image, center=(1056,1044)
				paragraph
					StaticText 0
				[825] link 0, center=(1108,1044), url='https://sonauto.ai/song/4ce7e7ce-4970-4645-a910-b4a65d297259'
					image
					paragraph
				[828] button, center=(1148,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 4 hours ago
			gridcell Tyler by the sea v2 Tyler by the sea nlanza999 tropical easy listening 2020s 4 0 0 Posted 4 hours ago
				[835] image Tyler by the sea, center=(1460,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_4cf260e8-26be-40d1-8eef-f664d60acc50.webp?width=256&quality=75&resize=contain'
				[837] image, center=(1410,1060)
				StaticText v2
				[842] link Tyler by the sea, center=(1618,949), url='https://sonauto.ai/song/4cf260e8-26be-40d1-8eef-f664d60acc50'
					heading Tyler by the sea
				[838] div, center=(1508,1066), inner_text=v2
				[844] link nlanza999, center=(1578,971), url='https://sonauto.ai/artist/nlanza999'
				[847] link tropical, center=(1580,1014), url='https://sonauto.ai/tag/tropical'
				[849] link easy listening, center=(1673,1014), url='https://sonauto.ai/tag/easy%20listening'
				[851] link 2020s, center=(1762,1014), url='https://sonauto.ai/tag/2020s'
				image
				paragraph
					StaticText 4
				[858] image, center=(1602,1044)
				paragraph
					StaticText 0
				[860] link 0, center=(1654,1044), url='https://sonauto.ai/song/4cf260e8-26be-40d1-8eef-f664d60acc50'
					image
					paragraph
				[863] button, center=(1694,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 4 hours ago
			gridcell Yamaha Keyboard Built-In Music-Core Vibes v2 Yamaha Keyboard Built-In Music-Core Vibes zaptrem new age instrumental bossa nova 6 0 0 Posted 5 hours ago
				image Yamaha Keyboard Built-In Music-Core Vibes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-267ca5d5-eb9f-4d6a-b627-0a97a3cf0d68?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Yamaha Keyboard Built-In Music-Core Vibes, url='https://sonauto.ai/song/5bd9a75f-4c9a-461f-b597-22eb99041b4d'
					heading Yamaha Keyboard Built-In Music-Core Vibes
				link zaptrem, url='https://sonauto.ai/artist/zaptrem'
				link new age, url='https://sonauto.ai/tag/new%20age'
				link instrumental, url='https://sonauto.ai/tag/instrumental'
				link bossa nova, url='https://sonauto.ai/tag/bossa%20nova'
				image
				paragraph
					StaticText 6
				image
				paragraph
					StaticText 0
				link 0, url='https://sonauto.ai/song/5bd9a75f-4c9a-461f-b597-22eb99041b4d'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
			gridcell Chill Feelings v2 Chill Feelings stickguy early 2010s world dream pop 8 0 0 Posted 5 hours ago
				image Chill Feelings, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-47eba7d4-bec2-4fcd-98f9-bef720ba0c3d?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Chill Feelings, url='https://sonauto.ai/song/f6d81b92-643c-4145-8710-6d3a3e5e2d8c'
					heading Chill Feelings
				link stickguy, url='https://sonauto.ai/artist/stickguy'
				link early 2010s, url='https://sonauto.ai/tag/early%202010s'
				link world, url='https://sonauto.ai/tag/world'
				link dream pop, url='https://sonauto.ai/tag/dream%20pop'
				image
				paragraph
					StaticText 8
				image
				paragraph
					StaticText 0
				link 0, url='https://sonauto.ai/song/f6d81b92-643c-4145-8710-6d3a3e5e2d8c'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
			gridcell Christmas A-Capella v2 Christmas A-Capella zaptrem holiday vocal harmony 16 2 0 Posted 5 hours ago
				image Christmas A-Capella, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-1b793f98-e10a-41ee-938c-9b4d84f874a5?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Christmas A-Capella, url='https://sonauto.ai/song/30143d59-692e-4019-86e4-603e33791cca'
					heading Christmas A-Capella
				link zaptrem, url='https://sonauto.ai/artist/zaptrem'
				link holiday, url='https://sonauto.ai/tag/holiday'
				link vocal, url='https://sonauto.ai/tag/vocal'
				link harmony, url='https://sonauto.ai/tag/harmony'
				image
				paragraph
					StaticText 16
				image
				paragraph
					StaticText 2
				link 0, url='https://sonauto.ai/song/30143d59-692e-4019-86e4-603e33791cca'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
		button Show More
		heading Trending Categories
		link 2020s, url='https://sonauto.ai/tag/2020s'
			heading 2020s
		link Male Vocalist, url='https://sonauto.ai/tag/male%20vocalist'
			heading Male Vocalist
		link Pop, url='https://sonauto.ai/tag/pop'
			heading Pop
		link Emotional, url='https://sonauto.ai/tag/emotional'
			heading Emotional
		link Blues, url='https://sonauto.ai/tag/blues'
			heading Blues
		link Female Vocalist, url='https://sonauto.ai/tag/female%20vocalist'
			heading Female Vocalist
		link Electronic, url='https://sonauto.ai/tag/electronic'
			heading Electronic
		link Rock, url='https://sonauto.ai/tag/rock'
			heading Rock
		link Electric Guitar, url='https://sonauto.ai/tag/electric%20guitar'
			heading Electric Guitar
		link Rap, url='https://sonauto.ai/tag/rap'
			heading Rap
		link Electric Blues, url='https://sonauto.ai/tag/electric%20blues'
			heading Electric Blues
		link Hip Hop, url='https://sonauto.ai/tag/hip%20hop'
			heading Hip Hop
		link Piano, url='https://sonauto.ai/tag/piano'
			heading Piano
		link 1970s, url='https://sonauto.ai/tag/1970s'
			heading 1970s
		link Nu-Disco, url='https://sonauto.ai/tag/nu-disco'
			heading Nu-Disco
		link Instrumental, url='https://sonauto.ai/tag/instrumental'
			heading Instrumental
		link Uplifting, url='https://sonauto.ai/tag/uplifting'
			heading Uplifting
		link Melodic, url='https://sonauto.ai/tag/melodic'
			heading Melodic
		link Synthpop, url='https://sonauto.ai/tag/synthpop'
			heading Synthpop
		link 2010s, url='https://sonauto.ai/tag/2010s'
			heading 2010s
		image
		image
	region Notifications (F8)
		list
```
</details>

**Reasoning for action:** I need to fulfill the user's request to view the 'Just Relax' playlist first. By clicking on the link identified as '80', which corresponds to the 'Just Relax' playlist, I will navigate to its specific content page. This is the first step towards meeting the acceptance criteria where the user wants to view details about this playlist.

**Action:** click('80') # Click on the 'Just Relax' playlist to explore its content.

**Change Description:** The user clicked on the 'Just Relax' playlist link, resulting in a navigation to the playlist's content page, where the elements and details specific to that playlist are displayed.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://sonauto.ai/

https://sonauto.ai/

**Content (before/after):** 

```
RootWebArea Sonauto | New Music by You, focused, url='https://sonauto.ai/'
	alert, atomic
	paragraph
		StaticText Welcome to Sonauto v2 beta! Your v1 generations will be available for a limited time at
		[52] link v1.sonauto.ai, center=(1276,28), url='https://v1.sonauto.ai/'
```
<details><summary>Show more</summary>

```
		StaticText .
	[53] button, center=(1884,28)
		image
	[59] link Sonauto Logo Sonauto, center=(126,96), inner_text=Sonauto, url='https://sonauto.ai/'
		image Sonauto Logo, url='https://sonauto.ai/_next/image?url=%2Fimages%2Fnew_bird.png&w=32&q=75'
	navigation
		[62] link Home, center=(128,150), url='https://sonauto.ai/'
			image
		[64] link Search, center=(128,186), url='https://sonauto.ai/search'
			image
		[66] link Make Music, center=(128,222), url='https://sonauto.ai/'
			image
	paragraph
		StaticText Trending
	[71] button Playlist, center=(194,283)
		image
	[75] combobox value='All', center=(128,325), expanded=False, hasPopup='listbox', inner_text=All, type=button
	[80] link art Just Relax, center=(128,381), inner_text=Just Relax, url='https://sonauto.ai/playlist/ab0f22f8-64c6-454b-9a12-fb14f4d48465'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-ab0f22f8-64c6-454b-9a12-fb14f4d48465?width=32&quality=75&resize=contain'
	[83] link art Dark Radio Network, center=(128,417), inner_text=Dark Radio Network, url='https://sonauto.ai/playlist/65fdf34c-28d5-47dc-801c-f156a78638d4'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-65fdf34c-28d5-47dc-801c-f156a78638d4?width=32&quality=75&resize=contain'
	[86] link Test, center=(128,453), url='https://sonauto.ai/playlist/8f58dc22-0e35-42d3-bc0c-74a044c68f83'
	[89] link My list, center=(128,489), url='https://sonauto.ai/playlist/7dd42422-563f-4e2d-95f0-62e8ac4ac0df'
	[92] link art GREEN BITES, center=(128,525), inner_text=GREEN BITES, url='https://sonauto.ai/playlist/476f7f74-0f8a-4100-ab4a-ead30aa554df'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-937b0f24-7aaa-4357-9e04-43488dddf699?width=32&quality=75&resize=contain'
	[95] link art Klangraum V2 Tests, center=(128,561), inner_text=Klangraum V2 Tests, url='https://sonauto.ai/playlist/a1f1dd9b-e58f-4812-a1e6-024e69f1af37'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-a1f1dd9b-e58f-4812-a1e6-024e69f1af37?width=32&quality=75&resize=contain'
	[98] link My songs, center=(128,597), url='https://sonauto.ai/playlist/f580ce69-e977-4810-92b3-4f4815c4b86f'
	[101] link The Show, center=(128,633), url='https://sonauto.ai/playlist/ae20fb05-042d-4032-b27d-e71785eeda08'
	[104] link art DID HE, center=(128,669), inner_text=DID HE, url='https://sonauto.ai/playlist/dbbd1058-a2eb-41cf-bd30-c350b1dfde90'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-dbbd1058-a2eb-41cf-bd30-c350b1dfde90?width=32&quality=75&resize=contain'
	[107] link cool, center=(128,705), url='https://sonauto.ai/playlist/5491c699-3f58-4762-913f-ffe690282a63'
	[110] link Luis, center=(128,741), url='https://sonauto.ai/playlist/6831c1cb-0828-4eec-95cc-dfdba071eae7'
	[113] link tyghghhg, center=(128,777), url='https://sonauto.ai/playlist/b46544c7-931f-434e-a501-4aa23e37a89f'
	link art Bluesman420 Fan Club, url='https://sonauto.ai/group/c97cd6bf-475b-447c-8db4-11a9dc2d526a'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1507227c-e538-4a01-9ec0-967a0ac68902?width=32&quality=75&resize=contain'
	link art Various Instrumentals, url='https://sonauto.ai/group/998f8cf6-7740-42be-ab67-6e983502abb4'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-998f8cf6-7740-42be-ab67-6e983502abb4?width=32&quality=75&resize=contain'
	link art Dark Radio, url='https://sonauto.ai/group/87db116d-1613-4574-8785-fb2cb613d18f'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-87db116d-1613-4574-8785-fb2cb613d18f?width=32&quality=75&resize=contain'
	link art Rubinyan theme Song, url='https://sonauto.ai/group/e7c907fb-9324-4389-961b-59880d374568'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-e7c907fb-9324-4389-961b-59880d374568?width=32&quality=75&resize=contain'
	link Rescate Brasil, url='https://sonauto.ai/group/05ed4a63-e238-4c92-a11e-df5dfeec01e2'
	link my music, url='https://sonauto.ai/group/8c296cfa-ea98-45c1-9b62-338cb85f137a'
	link Mm, url='https://sonauto.ai/group/49828acd-64b5-46e5-b45f-a548172e3f64'
	link art vives, url='https://sonauto.ai/group/22fa8e47-8007-48b9-ab7d-159979cf6a2c'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-97cc5c0d-b5ef-4e7c-8fee-f02e3db5a3e8?width=32&quality=75&resize=contain'
	link Heavy metal, url='https://sonauto.ai/group/f7f4e492-9701-4af9-98de-610c00d6e8e9'
	link art Música, url='https://sonauto.ai/group/2e28bd75-83ad-4055-b2d0-19fb1b687378'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-2e28bd75-83ad-4055-b2d0-19fb1b687378?width=32&quality=75&resize=contain'
	link art Davidounours, url='https://sonauto.ai/group/1a956452-71d5-4800-8a96-0ec8346bac0d'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-1a956452-71d5-4800-8a96-0ec8346bac0d?width=32&quality=75&resize=contain'
	link Hddjdh, url='https://sonauto.ai/group/9f5f4f3a-86aa-4e00-a270-b95e294c21c6'
	link Need For Speed Soundtrack, url='https://sonauto.ai/group/db78b071-5d27-49d6-af33-f115692bdaa6'
	link art Killer Raps, url='https://sonauto.ai/group/0a9833ea-3417-48fc-a11f-4a5669741ece'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-0a9833ea-3417-48fc-a11f-4a5669741ece?width=32&quality=75&resize=contain'
	link Так выбрать из балкона, url='https://sonauto.ai/group/9be2dbd8-08b6-4d09-bc72-c1981ba72277'
	link House, url='https://sonauto.ai/group/13f7e378-c201-4a6f-ad86-3b500505353b'
	link art Nothin but the Blues, url='https://sonauto.ai/group/d54b03a1-cd7b-4490-8900-81d49fc37f6e'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-d54b03a1-cd7b-4490-8900-81d49fc37f6e?width=32&quality=75&resize=contain'
	link art Le hobo, url='https://sonauto.ai/group/1148e019-c74c-4069-9b3c-f6cb290c3cf0'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-1148e019-c74c-4069-9b3c-f6cb290c3cf0?width=32&quality=75&resize=contain'
	link art Unusual Dubstep, url='https://sonauto.ai/group/ac84677c-9503-416f-a533-d5f05c9a2abc'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-ac84677c-9503-416f-a533-d5f05c9a2abc?width=32&quality=75&resize=contain'
	link art Cultural Mix & Crossovers, url='https://sonauto.ai/group/4bcec888-8969-43ac-a0c7-75fcd019db9f'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-4bcec888-8969-43ac-a0c7-75fcd019db9f?width=32&quality=75&resize=contain'
	link art Basement Dancefloor, url='https://sonauto.ai/group/b62764aa-2922-4b3e-8f6d-9a34871b391b'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-b62764aa-2922-4b3e-8f6d-9a34871b391b?width=32&quality=75&resize=contain'
	link art Universal Music, url='https://sonauto.ai/group/14a2e296-9039-48dd-a5b9-25578ba8b8e1'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-14a2e296-9039-48dd-a5b9-25578ba8b8e1?width=32&quality=75&resize=contain'
	[184] link Discord, center=(112,1005), url='https://discord.gg/pfXar3ChH8'
		image Discord icon, url='https://sonauto.ai/discord-white.svg'
	[186] link Twitter, center=(146,1005), url='https://x.com/SonautoAI'
		image Twitter icon, url='https://sonauto.ai/twitter-icon.svg'
	[189] link Terms, center=(97,1040), url='https://sonauto.ai/tos'
	StaticText ·
	[191] link Privacy, center=(156,1040), url='https://sonauto.ai/privacy'
	[196] button, center=(302,88)
		image
	[198] button, center=(342,88)
		image
	[201] link Install App, center=(1741,88), url='https://sonauto.ai/install'
		image
	[204] image, center=(1828,88)
	StaticText Log In
	main
		heading Start Your Masterpiece
		image
		[215] textbox A rock song about turtles flying, center=(1034,195), contenteditable=True, type=text
		[217] image, center=(1757,195)
		[218] button Generate, center=(1838,195)
		heading Instantly Create a Song
		[223] image, center=(542,249)
		[229] heading Pop, 2020s, Summer, Nu-Disco, center=(406,293)
		[232] heading [Miel San Marcos, Worship, Christian, Inspirational, Emotional, Male Vocalist, Female Vocalist, Piano, Electric Guitar, Drum Set, 2010s], center=(732,293)
		[235] heading Country, 2020s, Storytelling, Southern Rock, center=(1104,293)
		[238] heading Sentimental, Emotional, 1980s, Romantic, Melancholic, Pop, R&B, center=(1477,293)
		heading Guitar Virtuoso, Electric Blues, Texas Blues
		heading Blues, 1970s, Electric Blues
		heading Lo-Fi, Chillout, Downtempo
		heading A Blues Song Played By A Blues Power Trio. Incredible Guitar Solos With Heavy Bending. Thick Bass Tone.
		heading Blues, 1970s, Electric Blues
		heading Summer, Nu-Disco, 2020s, Romantic, Dance
		image
		[260] image, center=(1880,299)
		heading Groups For You
		[264] button Create a Group, center=(562,339)
			image
		[273] image Zaptrem's Group, center=(368,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-ee12a798-6b2f-4d90-9d4b-cd035d9a0a48?width=256&quality=75&resize=contain'
		[276] heading Zaptrem's Group, center=(530,402)
		[277] paragraph, center=(530,421), inner_text=7 Members
			StaticText 7
			StaticText Members
		paragraph
			StaticText Moderated by
			[279] link zaptrem, center=(566,441), url='https://sonauto.ai/artist/zaptrem'
		[280] paragraph, center=(530,469), inner_text=Feed me soooongs
			StaticText Feed me soooongs
		[282] button Play, center=(486,520)
			image
		[286] image Bluesman420 Fan Club, center=(734,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1507227c-e538-4a01-9ec0-967a0ac68902?width=256&quality=75&resize=contain'
		[289] heading Bluesman420 Fan Club, center=(900,413)
		[290] paragraph, center=(900,444), inner_text=5 Members
			StaticText 5
			StaticText Members
		paragraph
			StaticText Moderated by
			[292] link zaptrem, center=(932,463), url='https://sonauto.ai/artist/zaptrem'
		[293] paragraph, center=(900,492), inner_text=It's 106 miles to Chicago, we got a full tank of gas, half a pack of cigarettes, it's dark... and we're wearing sunglasses.
			StaticText It's 106 miles to Chicago, we got a full tank of gas, half a pack of cigarettes, it's dark... and we're wearing sunglasses.
		[295] button Play, center=(852,526)
			image
		[299] image Weird & Wacky Texts & Topics, center=(1100,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-7c2da748-49a4-43c8-9f4a-432a2ae1c561?width=256&quality=75&resize=contain'
		[302] heading Weird & Wacky Texts & Topics, center=(1266,413)
		[303] paragraph, center=(1266,444), inner_text=4 Members
			StaticText 4
			StaticText Members
		paragraph
			StaticText Moderated by
			[305] link chaos, center=(1292,463), url='https://sonauto.ai/artist/chaos'
		[306] paragraph, center=(1266,492), inner_text=Can you really sing a song about that stuff? Yup. Sure can.
			StaticText Can you really sing a song about that stuff? Yup. Sure can.
		[308] button Play, center=(1218,526)
			image
		[312] image Nice Voice, center=(1466,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-82686aa1-5a53-42d6-bb86-80b71defb209?width=256&quality=75&resize=contain'
		[315] heading Nice Voice, center=(1632,402)
		[316] paragraph, center=(1632,421), inner_text=3 Members
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			[318] link chaos, center=(1658,441), url='https://sonauto.ai/artist/chaos'
		[319] paragraph, center=(1632,469), inner_text=If you think the voice sounds great and is good quality, put it here.
			StaticText If you think the voice sounds great and is good quality, put it here.
		[321] button Play, center=(1584,520)
			image
		image Tilted Dancefloor, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-841b4468-df7a-428d-80c4-9a8494c4cb87?width=256&quality=75&resize=contain'
		heading Tilted Dancefloor
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link chaos, url='https://sonauto.ai/artist/chaos'
		paragraph
			StaticText Energetic with a twist of humor
		button Play
			image
		image Dark Synthwave, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1a7fa429-74d3-40f0-bac1-c78594847bb5?width=256&quality=75&resize=contain'
		heading Dark Synthwave
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link hayden, url='https://sonauto.ai/artist/hayden'
		paragraph
			StaticText Dark electronic melodic metal and synthwave
		button Play
			image
		image Chill Vibes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-6afa6e51-c830-45e9-8f71-032a1c50ec83?width=256&quality=75&resize=contain'
		heading Chill Vibes
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link hayden, url='https://sonauto.ai/artist/hayden'
		paragraph
		button Play
			image
		image Various Instrumentals, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-998f8cf6-7740-42be-ab67-6e983502abb4?width=256&quality=75&resize=contain'
		heading Various Instrumentals
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link whosthere, url='https://sonauto.ai/artist/whosthere'
		paragraph
			StaticText For instrumentals lovers
		button Play
			image
		image Protest Songs, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-a4e4e13c-e498-4dd6-9957-df69d208a2d5?width=256&quality=75&resize=contain'
		heading Protest Songs
		paragraph
			StaticText 2
			StaticText Members
		paragraph
			StaticText Moderated by
			link chaos, url='https://sonauto.ai/artist/chaos'
		paragraph
			StaticText Old people shouting at the sky come here to vent.
		button Play
			image
		image
		[391] image, center=(1880,462)
		heading Staff Picks
		[396] button, center=(444,591)
			image
		[405] image Leavin' You Behind, center=(368,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-b03dcac9-65d8-41ab-a850-dda75cb88114?width=256&quality=75&resize=contain'
		[407] image, center=(318,770)
		StaticText v2
		[412] link Leavin' You Behind, center=(540,659), url='https://sonauto.ai/song/ab00865a-10e5-4993-a3d9-adbb4876beb9'
			heading Leavin' You Behind
		[408] div, center=(416,776), inner_text=v2
		[414] link zaptrem, center=(480,681), url='https://sonauto.ai/artist/zaptrem'
		[417] link summer, center=(490,724), url='https://sonauto.ai/tag/summer'
		[419] link 2020s, center=(562,724), url='https://sonauto.ai/tag/2020s'
		[421] link pop, center=(623,724), url='https://sonauto.ai/tag/pop'
		image
		paragraph
			StaticText 822
		[428] image, center=(524,754)
		paragraph
			StaticText 11
		[430] link 2, center=(578,754), url='https://sonauto.ai/song/ab00865a-10e5-4993-a3d9-adbb4876beb9'
			image
			paragraph
		[433] button, center=(617,754), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 6 days ago
		[440] image Alright, center=(783,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-668bf78d-dff4-4a22-8d5b-1a2bd48cf08e?width=256&quality=75&resize=contain'
		[442] image, center=(733,770)
		StaticText v2
		[447] link Alright, center=(900,659), url='https://sonauto.ai/song/cc599224-25b1-4521-bb7d-63d63addd13b'
			heading Alright
		[443] div, center=(832,776), inner_text=v2
		[449] link coolsong, center=(898,681), url='https://sonauto.ai/artist/coolsong'
		[452] link 2020s, center=(900,709), url='https://sonauto.ai/tag/2020s'
		[454] link country, center=(970,709), url='https://sonauto.ai/tag/country'
		[456] link southern rock, center=(922,742), url='https://sonauto.ai/tag/southern%20rock'
		image
		paragraph
			StaticText 205
		[463] image, center=(939,772)
		paragraph
			StaticText 5
		[465] link 2, center=(990,772), url='https://sonauto.ai/song/cc599224-25b1-4521-bb7d-63d63addd13b'
			image
			paragraph
		[468] button, center=(1029,772), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 5 days ago
		[475] image We Stand, center=(1198,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-e668a6b3-ccca-4c36-a2a3-e42035389e5e?width=256&quality=75&resize=contain'
		[477] image, center=(1148,770)
		StaticText v2
		[482] link We Stand, center=(1328,659), url='https://sonauto.ai/song/cdd77c72-99bd-4247-b83f-ecaae849fdd2'
			heading We Stand
		[478] div, center=(1246,776), inner_text=v2
		[484] link gonesvan, center=(1314,681), url='https://sonauto.ai/artist/gonesvan'
		[487] link male vocalist, center=(1335,709), url='https://sonauto.ai/tag/male%20vocalist'
		[489] link electric guitar, center=(1444,709), url='https://sonauto.ai/tag/electric%20guitar'
		[491] link christian, center=(1320,742), url='https://sonauto.ai/tag/christian'
		image
		paragraph
			StaticText 391
		[498] image, center=(1353,772)
		paragraph
			StaticText 6
		[500] link 2, center=(1404,772), url='https://sonauto.ai/song/cdd77c72-99bd-4247-b83f-ecaae849fdd2'
			image
			paragraph
		[503] button, center=(1444,772), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 7 days ago
		[510] image When it’s us, center=(1613,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-a7ed0653-8a2f-4408-85c5-7f5bb57f7d7f?width=256&quality=75&resize=contain'
		[512] image, center=(1563,770)
		StaticText v2
		[517] link When it’s us, center=(1754,659), url='https://sonauto.ai/song/edba394d-4003-4d9b-a960-0ad0b2ae2490'
			heading When it’s us
		[513] div, center=(1662,776), inner_text=v2
		[519] link gonesvan, center=(1730,681), url='https://sonauto.ai/artist/gonesvan'
		[522] link male vocalist, center=(1750,709), url='https://sonauto.ai/tag/male%20vocalist'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		[526] link k-ballad, center=(1735,742), url='https://sonauto.ai/tag/k-ballad'
		image
		paragraph
			StaticText 306
		[533] image, center=(1771,772)
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/edba394d-4003-4d9b-a960-0ad0b2ae2490'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Craving for Snacks, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_87490abc-2ad8-4a8c-b234-904c28fd30f1.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Craving for Snacks, url='https://sonauto.ai/song/87490abc-2ad8-4a8c-b234-904c28fd30f1'
			heading Craving for Snacks
		link chaos, url='https://sonauto.ai/artist/chaos'
		link country, url='https://sonauto.ai/tag/country'
		link bluegrass, url='https://sonauto.ai/tag/bluegrass'
		image
		paragraph
			StaticText 413
		image
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/87490abc-2ad8-4a8c-b234-904c28fd30f1'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Green Eyes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-da6fe498-0f13-4aa7-932c-02fbd81d328d?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Green Eyes, url='https://sonauto.ai/song/bf4c9cae-f33e-4dc5-a5a7-7abe63696448'
			heading Green Eyes
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link indie, url='https://sonauto.ai/tag/indie'
		link pop, url='https://sonauto.ai/tag/pop'
		link dance pop, url='https://sonauto.ai/tag/dance%20pop'
		image
		paragraph
			StaticText 269
		image
		paragraph
			StaticText 4
		link 0, url='https://sonauto.ai/song/bf4c9cae-f33e-4dc5-a5a7-7abe63696448'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Midnight Raid, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-5cc8897c-5900-4359-bcf4-ff6120b6ef8f?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Midnight Raid, url='https://sonauto.ai/song/9715ecb5-1865-46f9-b064-0e16725b4fa6'
			heading Midnight Raid
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link EDM, url='https://sonauto.ai/tag/EDM'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		link house, url='https://sonauto.ai/tag/house'
		image
		paragraph
			StaticText 312
		image
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/9715ecb5-1865-46f9-b064-0e16725b4fa6'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Crazy Friday Night, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-984cef64-d683-4743-935f-6ab8d8c9a828?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Crazy Friday Night, url='https://sonauto.ai/song/9e21b63b-0ac3-437c-88ae-05e57c67bd6f'
			heading Crazy Friday Night
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link pop, url='https://sonauto.ai/tag/pop'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		link party, url='https://sonauto.ai/tag/party'
		image
		paragraph
			StaticText 279
		image
		paragraph
			StaticText 4
		link 0, url='https://sonauto.ai/song/9e21b63b-0ac3-437c-88ae-05e57c67bd6f'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Don't Cry Now, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_ff718ead-ecb4-4348-8f0b-8d393bba657d.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Don't Cry Now, url='https://sonauto.ai/song/ff718ead-ecb4-4348-8f0b-8d393bba657d'
			heading Don't Cry Now
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link country, url='https://sonauto.ai/tag/country'
		link rock, url='https://sonauto.ai/tag/rock'
		link western, url='https://sonauto.ai/tag/western'
		image
		paragraph
			StaticText 244
		image
		paragraph
			StaticText 1
		link 0, url='https://sonauto.ai/song/ff718ead-ecb4-4348-8f0b-8d393bba657d'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Caught in the Past, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_f40f3424-273c-4770-8ff8-e2f455a932a2.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Caught in the Past, url='https://sonauto.ai/song/f40f3424-273c-4770-8ff8-e2f455a932a2'
			heading Caught in the Past
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link 2000s, url='https://sonauto.ai/tag/2000s'
		link pop, url='https://sonauto.ai/tag/pop'
		link breakup, url='https://sonauto.ai/tag/breakup'
		image
		paragraph
			StaticText 299
		image
		paragraph
			StaticText 5
		link 2, url='https://sonauto.ai/song/f40f3424-273c-4770-8ff8-e2f455a932a2'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image
		[752] image, center=(1880,729)
		heading Trending Posts
		[756] button, center=(494,878)
			image
		[758] combobox value='Trending', center=(584,878), expanded=False, hasPopup='listbox', inner_text=Trending, type=button
		grid
			gridcell 1970s Cop Movie Soundtrack v2 1970s Cop Movie Soundtrack whosthere blues rock lounge 8 1 0 Posted 3 hours ago
				[767] image 1970s Cop Movie Soundtrack, center=(368,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-164546f9-46c7-42ec-9570-20885dca42aa?width=256&quality=75&resize=contain'
				[769] image, center=(318,1060)
				StaticText v2
				[774] link 1970s Cop Movie Soundtrack, center=(584,949), url='https://sonauto.ai/song/44b0ed21-fe47-4856-a42f-a7ceb923dda2'
					heading 1970s Cop Movie Soundtrack
				[770] div, center=(416,1066), inner_text=v2
				[776] link whosthere, center=(486,971), url='https://sonauto.ai/artist/whosthere'
				[779] link blues rock, center=(497,1014), url='https://sonauto.ai/tag/blues%20rock'
				[781] link lounge, center=(578,1014), url='https://sonauto.ai/tag/lounge'
				image
				paragraph
					StaticText 8
				[788] image, center=(510,1044)
				paragraph
					StaticText 1
				[790] link 0, center=(559,1044), url='https://sonauto.ai/song/44b0ed21-fe47-4856-a42f-a7ceb923dda2'
					image
					paragraph
				[793] button, center=(599,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 3 hours ago
			gridcell Tyler's Pina Coladaburg v2 Tyler's Pina Coladaburg nlanza999 tropical 1970s island 3 0 0 Posted 4 hours ago
				[800] image Tyler's Pina Coladaburg, center=(914,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_4ce7e7ce-4970-4645-a910-b4a65d297259.webp?width=256&quality=75&resize=contain'
				[802] image, center=(864,1060)
				StaticText v2
				[807] link Tyler's Pina Coladaburg, center=(1108,949), url='https://sonauto.ai/song/4ce7e7ce-4970-4645-a910-b4a65d297259'
					heading Tyler's Pina Coladaburg
				[803] div, center=(962,1066), inner_text=v2
				[809] link nlanza999, center=(1032,971), url='https://sonauto.ai/artist/nlanza999'
				[812] link tropical, center=(1034,1014), url='https://sonauto.ai/tag/tropical'
				[814] link 1970s, center=(1104,1014), url='https://sonauto.ai/tag/1970s'
				[816] link island, center=(1170,1014), url='https://sonauto.ai/tag/island'
				image
				paragraph
					StaticText 3
				[823] image, center=(1056,1044)
				paragraph
					StaticText 0
				[825] link 0, center=(1108,1044), url='https://sonauto.ai/song/4ce7e7ce-4970-4645-a910-b4a65d297259'
					image
					paragraph
				[828] button, center=(1148,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 4 hours ago
			gridcell Tyler by the sea v2 Tyler by the sea nlanza999 tropical easy listening 2020s 4 0 0 Posted 4 hours ago
				[835] image Tyler by the sea, center=(1460,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_4cf260e8-26be-40d1-8eef-f664d60acc50.webp?width=256&quality=75&resize=contain'
				[837] image, center=(1410,1060)
				StaticText v2
				[842] link Tyler by the sea, center=(1618,949), url='https://sonauto.ai/song/4cf260e8-26be-40d1-8eef-f664d60acc50'
					heading Tyler by the sea
				[838] div, center=(1508,1066), inner_text=v2
				[844] link nlanza999, center=(1578,971), url='https://sonauto.ai/artist/nlanza999'
				[847] link tropical, center=(1580,1014), url='https://sonauto.ai/tag/tropical'
				[849] link easy listening, center=(1673,1014), url='https://sonauto.ai/tag/easy%20listening'
				[851] link 2020s, center=(1762,1014), url='https://sonauto.ai/tag/2020s'
				image
				paragraph
					StaticText 4
				[858] image, center=(1602,1044)
				paragraph
					StaticText 0
				[860] link 0, center=(1654,1044), url='https://sonauto.ai/song/4cf260e8-26be-40d1-8eef-f664d60acc50'
					image
					paragraph
				[863] button, center=(1694,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 4 hours ago
			gridcell Yamaha Keyboard Built-In Music-Core Vibes v2 Yamaha Keyboard Built-In Music-Core Vibes zaptrem new age instrumental bossa nova 6 0 0 Posted 5 hours ago
				image Yamaha Keyboard Built-In Music-Core Vibes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-267ca5d5-eb9f-4d6a-b627-0a97a3cf0d68?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Yamaha Keyboard Built-In Music-Core Vibes, url='https://sonauto.ai/song/5bd9a75f-4c9a-461f-b597-22eb99041b4d'
					heading Yamaha Keyboard Built-In Music-Core Vibes
				link zaptrem, url='https://sonauto.ai/artist/zaptrem'
				link new age, url='https://sonauto.ai/tag/new%20age'
				link instrumental, url='https://sonauto.ai/tag/instrumental'
				link bossa nova, url='https://sonauto.ai/tag/bossa%20nova'
				image
				paragraph
					StaticText 6
				image
				paragraph
					StaticText 0
				link 0, url='https://sonauto.ai/song/5bd9a75f-4c9a-461f-b597-22eb99041b4d'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
			gridcell Chill Feelings v2 Chill Feelings stickguy early 2010s world dream pop 8 0 0 Posted 5 hours ago
				image Chill Feelings, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-47eba7d4-bec2-4fcd-98f9-bef720ba0c3d?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Chill Feelings, url='https://sonauto.ai/song/f6d81b92-643c-4145-8710-6d3a3e5e2d8c'
					heading Chill Feelings
				link stickguy, url='https://sonauto.ai/artist/stickguy'
				link early 2010s, url='https://sonauto.ai/tag/early%202010s'
				link world, url='https://sonauto.ai/tag/world'
				link dream pop, url='https://sonauto.ai/tag/dream%20pop'
				image
				paragraph
					StaticText 8
				image
				paragraph
					StaticText 0
				link 0, url='https://sonauto.ai/song/f6d81b92-643c-4145-8710-6d3a3e5e2d8c'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
			gridcell Christmas A-Capella v2 Christmas A-Capella zaptrem holiday vocal harmony 16 2 0 Posted 5 hours ago
				image Christmas A-Capella, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-1b793f98-e10a-41ee-938c-9b4d84f874a5?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Christmas A-Capella, url='https://sonauto.ai/song/30143d59-692e-4019-86e4-603e33791cca'
					heading Christmas A-Capella
				link zaptrem, url='https://sonauto.ai/artist/zaptrem'
				link holiday, url='https://sonauto.ai/tag/holiday'
				link vocal, url='https://sonauto.ai/tag/vocal'
				link harmony, url='https://sonauto.ai/tag/harmony'
				image
				paragraph
					StaticText 16
				image
				paragraph
					StaticText 2
				link 0, url='https://sonauto.ai/song/30143d59-692e-4019-86e4-603e33791cca'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
		button Show More
		heading Trending Categories
		link 2020s, url='https://sonauto.ai/tag/2020s'
			heading 2020s
		link Male Vocalist, url='https://sonauto.ai/tag/male%20vocalist'
			heading Male Vocalist
		link Pop, url='https://sonauto.ai/tag/pop'
			heading Pop
		link Emotional, url='https://sonauto.ai/tag/emotional'
			heading Emotional
		link Blues, url='https://sonauto.ai/tag/blues'
			heading Blues
		link Female Vocalist, url='https://sonauto.ai/tag/female%20vocalist'
			heading Female Vocalist
		link Electronic, url='https://sonauto.ai/tag/electronic'
			heading Electronic
		link Rock, url='https://sonauto.ai/tag/rock'
			heading Rock
		link Electric Guitar, url='https://sonauto.ai/tag/electric%20guitar'
			heading Electric Guitar
		link Rap, url='https://sonauto.ai/tag/rap'
			heading Rap
		link Electric Blues, url='https://sonauto.ai/tag/electric%20blues'
			heading Electric Blues
		link Hip Hop, url='https://sonauto.ai/tag/hip%20hop'
			heading Hip Hop
		link Piano, url='https://sonauto.ai/tag/piano'
			heading Piano
		link 1970s, url='https://sonauto.ai/tag/1970s'
			heading 1970s
		link Nu-Disco, url='https://sonauto.ai/tag/nu-disco'
			heading Nu-Disco
		link Instrumental, url='https://sonauto.ai/tag/instrumental'
			heading Instrumental
		link Uplifting, url='https://sonauto.ai/tag/uplifting'
			heading Uplifting
		link Melodic, url='https://sonauto.ai/tag/melodic'
			heading Melodic
		link Synthpop, url='https://sonauto.ai/tag/synthpop'
			heading Synthpop
		link 2010s, url='https://sonauto.ai/tag/2010s'
			heading 2010s
		image
		image
	region Notifications (F8)
		list
```
</details>



```
RootWebArea Sonauto | New Music by You, focused, url='https://sonauto.ai/'
	alert, atomic
	paragraph
		StaticText Welcome to Sonauto v2 beta! Your v1 generations will be available for a limited time at
		[52] link v1.sonauto.ai, center=(1276,28), url='https://v1.sonauto.ai/'
```
<details><summary>Show more</summary>

```
		StaticText .
	[53] button, center=(1884,28)
		image
	[59] link Sonauto Logo Sonauto, center=(126,96), inner_text=Sonauto, url='https://sonauto.ai/'
		image Sonauto Logo, url='https://sonauto.ai/_next/image?url=%2Fimages%2Fnew_bird.png&w=32&q=75'
	navigation
		[62] link Home, center=(128,150), url='https://sonauto.ai/'
			image
		[64] link Search, center=(128,186), url='https://sonauto.ai/search'
			image
		[66] link Make Music, center=(128,222), url='https://sonauto.ai/'
			image
	paragraph
		StaticText Trending
	[71] button Playlist, center=(194,283)
		image
	[75] combobox value='All', center=(128,325), expanded=False, hasPopup='listbox', inner_text=All, type=button
	[80] link art Just Relax, center=(128,381), inner_text=Just Relax, url='https://sonauto.ai/playlist/ab0f22f8-64c6-454b-9a12-fb14f4d48465'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-ab0f22f8-64c6-454b-9a12-fb14f4d48465?width=32&quality=75&resize=contain'
	[83] link art Dark Radio Network, center=(128,417), inner_text=Dark Radio Network, url='https://sonauto.ai/playlist/65fdf34c-28d5-47dc-801c-f156a78638d4'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-65fdf34c-28d5-47dc-801c-f156a78638d4?width=32&quality=75&resize=contain'
	[86] link Test, center=(128,453), url='https://sonauto.ai/playlist/8f58dc22-0e35-42d3-bc0c-74a044c68f83'
	[89] link My list, center=(128,489), url='https://sonauto.ai/playlist/7dd42422-563f-4e2d-95f0-62e8ac4ac0df'
	[92] link art GREEN BITES, center=(128,525), inner_text=GREEN BITES, url='https://sonauto.ai/playlist/476f7f74-0f8a-4100-ab4a-ead30aa554df'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-937b0f24-7aaa-4357-9e04-43488dddf699?width=32&quality=75&resize=contain'
	[95] link art Klangraum V2 Tests, center=(128,561), inner_text=Klangraum V2 Tests, url='https://sonauto.ai/playlist/a1f1dd9b-e58f-4812-a1e6-024e69f1af37'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-a1f1dd9b-e58f-4812-a1e6-024e69f1af37?width=32&quality=75&resize=contain'
	[98] link My songs, center=(128,597), url='https://sonauto.ai/playlist/f580ce69-e977-4810-92b3-4f4815c4b86f'
	[101] link The Show, center=(128,633), url='https://sonauto.ai/playlist/ae20fb05-042d-4032-b27d-e71785eeda08'
	[104] link art DID HE, center=(128,669), inner_text=DID HE, url='https://sonauto.ai/playlist/dbbd1058-a2eb-41cf-bd30-c350b1dfde90'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/playlist-dbbd1058-a2eb-41cf-bd30-c350b1dfde90?width=32&quality=75&resize=contain'
	[107] link cool, center=(128,705), url='https://sonauto.ai/playlist/5491c699-3f58-4762-913f-ffe690282a63'
	[110] link Luis, center=(128,741), url='https://sonauto.ai/playlist/6831c1cb-0828-4eec-95cc-dfdba071eae7'
	[113] link tyghghhg, center=(128,777), url='https://sonauto.ai/playlist/b46544c7-931f-434e-a501-4aa23e37a89f'
	link art Bluesman420 Fan Club, url='https://sonauto.ai/group/c97cd6bf-475b-447c-8db4-11a9dc2d526a'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1507227c-e538-4a01-9ec0-967a0ac68902?width=32&quality=75&resize=contain'
	link art Various Instrumentals, url='https://sonauto.ai/group/998f8cf6-7740-42be-ab67-6e983502abb4'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-998f8cf6-7740-42be-ab67-6e983502abb4?width=32&quality=75&resize=contain'
	link art Dark Radio, url='https://sonauto.ai/group/87db116d-1613-4574-8785-fb2cb613d18f'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-87db116d-1613-4574-8785-fb2cb613d18f?width=32&quality=75&resize=contain'
	link art Rubinyan theme Song, url='https://sonauto.ai/group/e7c907fb-9324-4389-961b-59880d374568'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-e7c907fb-9324-4389-961b-59880d374568?width=32&quality=75&resize=contain'
	link Rescate Brasil, url='https://sonauto.ai/group/05ed4a63-e238-4c92-a11e-df5dfeec01e2'
	link my music, url='https://sonauto.ai/group/8c296cfa-ea98-45c1-9b62-338cb85f137a'
	link Mm, url='https://sonauto.ai/group/49828acd-64b5-46e5-b45f-a548172e3f64'
	link art vives, url='https://sonauto.ai/group/22fa8e47-8007-48b9-ab7d-159979cf6a2c'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-97cc5c0d-b5ef-4e7c-8fee-f02e3db5a3e8?width=32&quality=75&resize=contain'
	link Heavy metal, url='https://sonauto.ai/group/f7f4e492-9701-4af9-98de-610c00d6e8e9'
	link art Música, url='https://sonauto.ai/group/2e28bd75-83ad-4055-b2d0-19fb1b687378'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-2e28bd75-83ad-4055-b2d0-19fb1b687378?width=32&quality=75&resize=contain'
	link art Davidounours, url='https://sonauto.ai/group/1a956452-71d5-4800-8a96-0ec8346bac0d'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-1a956452-71d5-4800-8a96-0ec8346bac0d?width=32&quality=75&resize=contain'
	link Hddjdh, url='https://sonauto.ai/group/9f5f4f3a-86aa-4e00-a270-b95e294c21c6'
	link Need For Speed Soundtrack, url='https://sonauto.ai/group/db78b071-5d27-49d6-af33-f115692bdaa6'
	link art Killer Raps, url='https://sonauto.ai/group/0a9833ea-3417-48fc-a11f-4a5669741ece'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-0a9833ea-3417-48fc-a11f-4a5669741ece?width=32&quality=75&resize=contain'
	link Так выбрать из балкона, url='https://sonauto.ai/group/9be2dbd8-08b6-4d09-bc72-c1981ba72277'
	link House, url='https://sonauto.ai/group/13f7e378-c201-4a6f-ad86-3b500505353b'
	link art Nothin but the Blues, url='https://sonauto.ai/group/d54b03a1-cd7b-4490-8900-81d49fc37f6e'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-d54b03a1-cd7b-4490-8900-81d49fc37f6e?width=32&quality=75&resize=contain'
	link art Le hobo, url='https://sonauto.ai/group/1148e019-c74c-4069-9b3c-f6cb290c3cf0'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-1148e019-c74c-4069-9b3c-f6cb290c3cf0?width=32&quality=75&resize=contain'
	link art Unusual Dubstep, url='https://sonauto.ai/group/ac84677c-9503-416f-a533-d5f05c9a2abc'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-ac84677c-9503-416f-a533-d5f05c9a2abc?width=32&quality=75&resize=contain'
	link art Cultural Mix & Crossovers, url='https://sonauto.ai/group/4bcec888-8969-43ac-a0c7-75fcd019db9f'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-4bcec888-8969-43ac-a0c7-75fcd019db9f?width=32&quality=75&resize=contain'
	link art Basement Dancefloor, url='https://sonauto.ai/group/b62764aa-2922-4b3e-8f6d-9a34871b391b'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-b62764aa-2922-4b3e-8f6d-9a34871b391b?width=32&quality=75&resize=contain'
	link art Universal Music, url='https://sonauto.ai/group/14a2e296-9039-48dd-a5b9-25578ba8b8e1'
		image art, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-14a2e296-9039-48dd-a5b9-25578ba8b8e1?width=32&quality=75&resize=contain'
	[184] link Discord, center=(112,1005), url='https://discord.gg/pfXar3ChH8'
		image Discord icon, url='https://sonauto.ai/discord-white.svg'
	[186] link Twitter, center=(146,1005), url='https://x.com/SonautoAI'
		image Twitter icon, url='https://sonauto.ai/twitter-icon.svg'
	[189] link Terms, center=(97,1040), url='https://sonauto.ai/tos'
	StaticText ·
	[191] link Privacy, center=(156,1040), url='https://sonauto.ai/privacy'
	[196] button, center=(302,88)
		image
	[198] button, center=(342,88)
		image
	[201] link Install App, center=(1741,88), url='https://sonauto.ai/install'
		image
	[204] image, center=(1828,88)
	StaticText Log In
	main
		heading Start Your Masterpiece
		image
		[215] textbox A rock song about turtles flying, center=(1034,195), contenteditable=True, type=text
		[217] image, center=(1757,195)
		[218] button Generate, center=(1838,195)
		heading Instantly Create a Song
		[223] image, center=(542,249)
		[229] heading Pop, 2020s, Summer, Nu-Disco, center=(406,293)
		[232] heading [Miel San Marcos, Worship, Christian, Inspirational, Emotional, Male Vocalist, Female Vocalist, Piano, Electric Guitar, Drum Set, 2010s], center=(732,293)
		[235] heading Country, 2020s, Storytelling, Southern Rock, center=(1104,293)
		[238] heading Sentimental, Emotional, 1980s, Romantic, Melancholic, Pop, R&B, center=(1477,293)
		heading Guitar Virtuoso, Electric Blues, Texas Blues
		heading Blues, 1970s, Electric Blues
		heading Lo-Fi, Chillout, Downtempo
		heading A Blues Song Played By A Blues Power Trio. Incredible Guitar Solos With Heavy Bending. Thick Bass Tone.
		heading Blues, 1970s, Electric Blues
		heading Summer, Nu-Disco, 2020s, Romantic, Dance
		image
		[260] image, center=(1880,299)
		heading Groups For You
		[264] button Create a Group, center=(562,339)
			image
		[273] image Zaptrem's Group, center=(368,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-ee12a798-6b2f-4d90-9d4b-cd035d9a0a48?width=256&quality=75&resize=contain'
		[276] heading Zaptrem's Group, center=(530,402)
		[277] paragraph, center=(530,421), inner_text=7 Members
			StaticText 7
			StaticText Members
		paragraph
			StaticText Moderated by
			[279] link zaptrem, center=(566,441), url='https://sonauto.ai/artist/zaptrem'
		[280] paragraph, center=(530,469), inner_text=Feed me soooongs
			StaticText Feed me soooongs
		[282] button Play, center=(486,520)
			image
		[286] image Bluesman420 Fan Club, center=(734,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1507227c-e538-4a01-9ec0-967a0ac68902?width=256&quality=75&resize=contain'
		[289] heading Bluesman420 Fan Club, center=(900,413)
		[290] paragraph, center=(900,444), inner_text=5 Members
			StaticText 5
			StaticText Members
		paragraph
			StaticText Moderated by
			[292] link zaptrem, center=(932,463), url='https://sonauto.ai/artist/zaptrem'
		[293] paragraph, center=(900,492), inner_text=It's 106 miles to Chicago, we got a full tank of gas, half a pack of cigarettes, it's dark... and we're wearing sunglasses.
			StaticText It's 106 miles to Chicago, we got a full tank of gas, half a pack of cigarettes, it's dark... and we're wearing sunglasses.
		[295] button Play, center=(852,526)
			image
		[299] image Weird & Wacky Texts & Topics, center=(1100,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-7c2da748-49a4-43c8-9f4a-432a2ae1c561?width=256&quality=75&resize=contain'
		[302] heading Weird & Wacky Texts & Topics, center=(1266,413)
		[303] paragraph, center=(1266,444), inner_text=4 Members
			StaticText 4
			StaticText Members
		paragraph
			StaticText Moderated by
			[305] link chaos, center=(1292,463), url='https://sonauto.ai/artist/chaos'
		[306] paragraph, center=(1266,492), inner_text=Can you really sing a song about that stuff? Yup. Sure can.
			StaticText Can you really sing a song about that stuff? Yup. Sure can.
		[308] button Play, center=(1218,526)
			image
		[312] image Nice Voice, center=(1466,462), url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-82686aa1-5a53-42d6-bb86-80b71defb209?width=256&quality=75&resize=contain'
		[315] heading Nice Voice, center=(1632,402)
		[316] paragraph, center=(1632,421), inner_text=3 Members
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			[318] link chaos, center=(1658,441), url='https://sonauto.ai/artist/chaos'
		[319] paragraph, center=(1632,469), inner_text=If you think the voice sounds great and is good quality, put it here.
			StaticText If you think the voice sounds great and is good quality, put it here.
		[321] button Play, center=(1584,520)
			image
		image Tilted Dancefloor, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-841b4468-df7a-428d-80c4-9a8494c4cb87?width=256&quality=75&resize=contain'
		heading Tilted Dancefloor
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link chaos, url='https://sonauto.ai/artist/chaos'
		paragraph
			StaticText Energetic with a twist of humor
		button Play
			image
		image Dark Synthwave, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-1a7fa429-74d3-40f0-bac1-c78594847bb5?width=256&quality=75&resize=contain'
		heading Dark Synthwave
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link hayden, url='https://sonauto.ai/artist/hayden'
		paragraph
			StaticText Dark electronic melodic metal and synthwave
		button Play
			image
		image Chill Vibes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-6afa6e51-c830-45e9-8f71-032a1c50ec83?width=256&quality=75&resize=contain'
		heading Chill Vibes
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link hayden, url='https://sonauto.ai/artist/hayden'
		paragraph
		button Play
			image
		image Various Instrumentals, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-998f8cf6-7740-42be-ab67-6e983502abb4?width=256&quality=75&resize=contain'
		heading Various Instrumentals
		paragraph
			StaticText 3
			StaticText Members
		paragraph
			StaticText Moderated by
			link whosthere, url='https://sonauto.ai/artist/whosthere'
		paragraph
			StaticText For instrumentals lovers
		button Play
			image
		image Protest Songs, url='https://api.sonauto.ai/storage/v1/render/image/public/images/group-a4e4e13c-e498-4dd6-9957-df69d208a2d5?width=256&quality=75&resize=contain'
		heading Protest Songs
		paragraph
			StaticText 2
			StaticText Members
		paragraph
			StaticText Moderated by
			link chaos, url='https://sonauto.ai/artist/chaos'
		paragraph
			StaticText Old people shouting at the sky come here to vent.
		button Play
			image
		image
		[391] image, center=(1880,462)
		heading Staff Picks
		[396] button, center=(444,591)
			image
		[405] image Leavin' You Behind, center=(368,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-b03dcac9-65d8-41ab-a850-dda75cb88114?width=256&quality=75&resize=contain'
		[407] image, center=(318,770)
		StaticText v2
		[412] link Leavin' You Behind, center=(540,659), url='https://sonauto.ai/song/ab00865a-10e5-4993-a3d9-adbb4876beb9'
			heading Leavin' You Behind
		[408] div, center=(416,776), inner_text=v2
		[414] link zaptrem, center=(480,681), url='https://sonauto.ai/artist/zaptrem'
		[417] link summer, center=(490,724), url='https://sonauto.ai/tag/summer'
		[419] link 2020s, center=(562,724), url='https://sonauto.ai/tag/2020s'
		[421] link pop, center=(623,724), url='https://sonauto.ai/tag/pop'
		image
		paragraph
			StaticText 822
		[428] image, center=(524,754)
		paragraph
			StaticText 11
		[430] link 2, center=(578,754), url='https://sonauto.ai/song/ab00865a-10e5-4993-a3d9-adbb4876beb9'
			image
			paragraph
		[433] button, center=(617,754), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 6 days ago
		[440] image Alright, center=(783,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-668bf78d-dff4-4a22-8d5b-1a2bd48cf08e?width=256&quality=75&resize=contain'
		[442] image, center=(733,770)
		StaticText v2
		[447] link Alright, center=(900,659), url='https://sonauto.ai/song/cc599224-25b1-4521-bb7d-63d63addd13b'
			heading Alright
		[443] div, center=(832,776), inner_text=v2
		[449] link coolsong, center=(898,681), url='https://sonauto.ai/artist/coolsong'
		[452] link 2020s, center=(900,709), url='https://sonauto.ai/tag/2020s'
		[454] link country, center=(970,709), url='https://sonauto.ai/tag/country'
		[456] link southern rock, center=(922,742), url='https://sonauto.ai/tag/southern%20rock'
		image
		paragraph
			StaticText 205
		[463] image, center=(939,772)
		paragraph
			StaticText 5
		[465] link 2, center=(990,772), url='https://sonauto.ai/song/cc599224-25b1-4521-bb7d-63d63addd13b'
			image
			paragraph
		[468] button, center=(1029,772), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 5 days ago
		[475] image We Stand, center=(1198,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-e668a6b3-ccca-4c36-a2a3-e42035389e5e?width=256&quality=75&resize=contain'
		[477] image, center=(1148,770)
		StaticText v2
		[482] link We Stand, center=(1328,659), url='https://sonauto.ai/song/cdd77c72-99bd-4247-b83f-ecaae849fdd2'
			heading We Stand
		[478] div, center=(1246,776), inner_text=v2
		[484] link gonesvan, center=(1314,681), url='https://sonauto.ai/artist/gonesvan'
		[487] link male vocalist, center=(1335,709), url='https://sonauto.ai/tag/male%20vocalist'
		[489] link electric guitar, center=(1444,709), url='https://sonauto.ai/tag/electric%20guitar'
		[491] link christian, center=(1320,742), url='https://sonauto.ai/tag/christian'
		image
		paragraph
			StaticText 391
		[498] image, center=(1353,772)
		paragraph
			StaticText 6
		[500] link 2, center=(1404,772), url='https://sonauto.ai/song/cdd77c72-99bd-4247-b83f-ecaae849fdd2'
			image
			paragraph
		[503] button, center=(1444,772), expanded=False, hasPopup='menu', type=button
			image
		paragraph
			StaticText Posted
			StaticText 7 days ago
		[510] image When it’s us, center=(1613,720), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-a7ed0653-8a2f-4408-85c5-7f5bb57f7d7f?width=256&quality=75&resize=contain'
		[512] image, center=(1563,770)
		StaticText v2
		[517] link When it’s us, center=(1754,659), url='https://sonauto.ai/song/edba394d-4003-4d9b-a960-0ad0b2ae2490'
			heading When it’s us
		[513] div, center=(1662,776), inner_text=v2
		[519] link gonesvan, center=(1730,681), url='https://sonauto.ai/artist/gonesvan'
		[522] link male vocalist, center=(1750,709), url='https://sonauto.ai/tag/male%20vocalist'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		[526] link k-ballad, center=(1735,742), url='https://sonauto.ai/tag/k-ballad'
		image
		paragraph
			StaticText 306
		[533] image, center=(1771,772)
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/edba394d-4003-4d9b-a960-0ad0b2ae2490'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Craving for Snacks, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_87490abc-2ad8-4a8c-b234-904c28fd30f1.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Craving for Snacks, url='https://sonauto.ai/song/87490abc-2ad8-4a8c-b234-904c28fd30f1'
			heading Craving for Snacks
		link chaos, url='https://sonauto.ai/artist/chaos'
		link country, url='https://sonauto.ai/tag/country'
		link bluegrass, url='https://sonauto.ai/tag/bluegrass'
		image
		paragraph
			StaticText 413
		image
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/87490abc-2ad8-4a8c-b234-904c28fd30f1'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Green Eyes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-da6fe498-0f13-4aa7-932c-02fbd81d328d?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Green Eyes, url='https://sonauto.ai/song/bf4c9cae-f33e-4dc5-a5a7-7abe63696448'
			heading Green Eyes
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link indie, url='https://sonauto.ai/tag/indie'
		link pop, url='https://sonauto.ai/tag/pop'
		link dance pop, url='https://sonauto.ai/tag/dance%20pop'
		image
		paragraph
			StaticText 269
		image
		paragraph
			StaticText 4
		link 0, url='https://sonauto.ai/song/bf4c9cae-f33e-4dc5-a5a7-7abe63696448'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Midnight Raid, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-5cc8897c-5900-4359-bcf4-ff6120b6ef8f?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Midnight Raid, url='https://sonauto.ai/song/9715ecb5-1865-46f9-b064-0e16725b4fa6'
			heading Midnight Raid
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link EDM, url='https://sonauto.ai/tag/EDM'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		link house, url='https://sonauto.ai/tag/house'
		image
		paragraph
			StaticText 312
		image
		paragraph
			StaticText 3
		link 0, url='https://sonauto.ai/song/9715ecb5-1865-46f9-b064-0e16725b4fa6'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Crazy Friday Night, url='https://api.sonauto.ai/storage/v1/render/image/public/images/clientgen-984cef64-d683-4743-935f-6ab8d8c9a828?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Crazy Friday Night, url='https://sonauto.ai/song/9e21b63b-0ac3-437c-88ae-05e57c67bd6f'
			heading Crazy Friday Night
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link pop, url='https://sonauto.ai/tag/pop'
		link 2020s, url='https://sonauto.ai/tag/2020s'
		link party, url='https://sonauto.ai/tag/party'
		image
		paragraph
			StaticText 279
		image
		paragraph
			StaticText 4
		link 0, url='https://sonauto.ai/song/9e21b63b-0ac3-437c-88ae-05e57c67bd6f'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Don't Cry Now, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_ff718ead-ecb4-4348-8f0b-8d393bba657d.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Don't Cry Now, url='https://sonauto.ai/song/ff718ead-ecb4-4348-8f0b-8d393bba657d'
			heading Don't Cry Now
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link country, url='https://sonauto.ai/tag/country'
		link rock, url='https://sonauto.ai/tag/rock'
		link western, url='https://sonauto.ai/tag/western'
		image
		paragraph
			StaticText 244
		image
		paragraph
			StaticText 1
		link 0, url='https://sonauto.ai/song/ff718ead-ecb4-4348-8f0b-8d393bba657d'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image Caught in the Past, url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_f40f3424-273c-4770-8ff8-e2f455a932a2.webp?width=256&quality=75&resize=contain'
		image
		StaticText v2
		link Caught in the Past, url='https://sonauto.ai/song/f40f3424-273c-4770-8ff8-e2f455a932a2'
			heading Caught in the Past
		link zaptrem, url='https://sonauto.ai/artist/zaptrem'
		link 2000s, url='https://sonauto.ai/tag/2000s'
		link pop, url='https://sonauto.ai/tag/pop'
		link breakup, url='https://sonauto.ai/tag/breakup'
		image
		paragraph
			StaticText 299
		image
		paragraph
			StaticText 5
		link 2, url='https://sonauto.ai/song/f40f3424-273c-4770-8ff8-e2f455a932a2'
			image
			paragraph
		button, expanded=False, hasPopup='menu'
			image
		paragraph
			StaticText Posted
			StaticText 1 week ago
		image
		[752] image, center=(1880,729)
		heading Trending Posts
		[756] button, center=(494,878)
			image
		[758] combobox value='Trending', center=(584,878), expanded=False, hasPopup='listbox', inner_text=Trending, type=button
		grid
			gridcell 1970s Cop Movie Soundtrack v2 1970s Cop Movie Soundtrack whosthere blues rock lounge 8 1 0 Posted 3 hours ago
				[767] image 1970s Cop Movie Soundtrack, center=(368,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-164546f9-46c7-42ec-9570-20885dca42aa?width=256&quality=75&resize=contain'
				[769] image, center=(318,1060)
				StaticText v2
				[774] link 1970s Cop Movie Soundtrack, center=(584,949), url='https://sonauto.ai/song/44b0ed21-fe47-4856-a42f-a7ceb923dda2'
					heading 1970s Cop Movie Soundtrack
				[770] div, center=(416,1066), inner_text=v2
				[776] link whosthere, center=(486,971), url='https://sonauto.ai/artist/whosthere'
				[779] link blues rock, center=(497,1014), url='https://sonauto.ai/tag/blues%20rock'
				[781] link lounge, center=(578,1014), url='https://sonauto.ai/tag/lounge'
				image
				paragraph
					StaticText 8
				[788] image, center=(510,1044)
				paragraph
					StaticText 1
				[790] link 0, center=(559,1044), url='https://sonauto.ai/song/44b0ed21-fe47-4856-a42f-a7ceb923dda2'
					image
					paragraph
				[793] button, center=(599,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 3 hours ago
			gridcell Tyler's Pina Coladaburg v2 Tyler's Pina Coladaburg nlanza999 tropical 1970s island 3 0 0 Posted 4 hours ago
				[800] image Tyler's Pina Coladaburg, center=(914,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_4ce7e7ce-4970-4645-a910-b4a65d297259.webp?width=256&quality=75&resize=contain'
				[802] image, center=(864,1060)
				StaticText v2
				[807] link Tyler's Pina Coladaburg, center=(1108,949), url='https://sonauto.ai/song/4ce7e7ce-4970-4645-a910-b4a65d297259'
					heading Tyler's Pina Coladaburg
				[803] div, center=(962,1066), inner_text=v2
				[809] link nlanza999, center=(1032,971), url='https://sonauto.ai/artist/nlanza999'
				[812] link tropical, center=(1034,1014), url='https://sonauto.ai/tag/tropical'
				[814] link 1970s, center=(1104,1014), url='https://sonauto.ai/tag/1970s'
				[816] link island, center=(1170,1014), url='https://sonauto.ai/tag/island'
				image
				paragraph
					StaticText 3
				[823] image, center=(1056,1044)
				paragraph
					StaticText 0
				[825] link 0, center=(1108,1044), url='https://sonauto.ai/song/4ce7e7ce-4970-4645-a910-b4a65d297259'
					image
					paragraph
				[828] button, center=(1148,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 4 hours ago
			gridcell Tyler by the sea v2 Tyler by the sea nlanza999 tropical easy listening 2020s 4 0 0 Posted 4 hours ago
				[835] image Tyler by the sea, center=(1460,1010), url='https://api.sonauto.ai/storage/v1/render/image/public/images/genoninsert_4cf260e8-26be-40d1-8eef-f664d60acc50.webp?width=256&quality=75&resize=contain'
				[837] image, center=(1410,1060)
				StaticText v2
				[842] link Tyler by the sea, center=(1618,949), url='https://sonauto.ai/song/4cf260e8-26be-40d1-8eef-f664d60acc50'
					heading Tyler by the sea
				[838] div, center=(1508,1066), inner_text=v2
				[844] link nlanza999, center=(1578,971), url='https://sonauto.ai/artist/nlanza999'
				[847] link tropical, center=(1580,1014), url='https://sonauto.ai/tag/tropical'
				[849] link easy listening, center=(1673,1014), url='https://sonauto.ai/tag/easy%20listening'
				[851] link 2020s, center=(1762,1014), url='https://sonauto.ai/tag/2020s'
				image
				paragraph
					StaticText 4
				[858] image, center=(1602,1044)
				paragraph
					StaticText 0
				[860] link 0, center=(1654,1044), url='https://sonauto.ai/song/4cf260e8-26be-40d1-8eef-f664d60acc50'
					image
					paragraph
				[863] button, center=(1694,1044), expanded=False, hasPopup='menu', type=button
					image
				paragraph
					StaticText Posted
					StaticText 4 hours ago
			gridcell Yamaha Keyboard Built-In Music-Core Vibes v2 Yamaha Keyboard Built-In Music-Core Vibes zaptrem new age instrumental bossa nova 6 0 0 Posted 5 hours ago
				image Yamaha Keyboard Built-In Music-Core Vibes, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-267ca5d5-eb9f-4d6a-b627-0a97a3cf0d68?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Yamaha Keyboard Built-In Music-Core Vibes, url='https://sonauto.ai/song/5bd9a75f-4c9a-461f-b597-22eb99041b4d'
					heading Yamaha Keyboard Built-In Music-Core Vibes
				link zaptrem, url='https://sonauto.ai/artist/zaptrem'
				link new age, url='https://sonauto.ai/tag/new%20age'
				link instrumental, url='https://sonauto.ai/tag/instrumental'
				link bossa nova, url='https://sonauto.ai/tag/bossa%20nova'
				image
				paragraph
					StaticText 6
				image
				paragraph
					StaticText 0
				link 0, url='https://sonauto.ai/song/5bd9a75f-4c9a-461f-b597-22eb99041b4d'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
			gridcell Chill Feelings v2 Chill Feelings stickguy early 2010s world dream pop 8 0 0 Posted 5 hours ago
				image Chill Feelings, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-47eba7d4-bec2-4fcd-98f9-bef720ba0c3d?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Chill Feelings, url='https://sonauto.ai/song/f6d81b92-643c-4145-8710-6d3a3e5e2d8c'
					heading Chill Feelings
				link stickguy, url='https://sonauto.ai/artist/stickguy'
				link early 2010s, url='https://sonauto.ai/tag/early%202010s'
				link world, url='https://sonauto.ai/tag/world'
				link dream pop, url='https://sonauto.ai/tag/dream%20pop'
				image
				paragraph
					StaticText 8
				image
				paragraph
					StaticText 0
				link 0, url='https://sonauto.ai/song/f6d81b92-643c-4145-8710-6d3a3e5e2d8c'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
			gridcell Christmas A-Capella v2 Christmas A-Capella zaptrem holiday vocal harmony 16 2 0 Posted 5 hours ago
				image Christmas A-Capella, url='https://api.sonauto.ai/storage/v1/render/image/public/images/song-1b793f98-e10a-41ee-938c-9b4d84f874a5?width=256&quality=75&resize=contain'
				image
				StaticText v2
				link Christmas A-Capella, url='https://sonauto.ai/song/30143d59-692e-4019-86e4-603e33791cca'
					heading Christmas A-Capella
				link zaptrem, url='https://sonauto.ai/artist/zaptrem'
				link holiday, url='https://sonauto.ai/tag/holiday'
				link vocal, url='https://sonauto.ai/tag/vocal'
				link harmony, url='https://sonauto.ai/tag/harmony'
				image
				paragraph
					StaticText 16
				image
				paragraph
					StaticText 2
				link 0, url='https://sonauto.ai/song/30143d59-692e-4019-86e4-603e33791cca'
					image
					paragraph
				button, expanded=False, hasPopup='menu'
					image
				paragraph
					StaticText Posted
					StaticText 5 hours ago
		button Show More
		heading Trending Categories
		link 2020s, url='https://sonauto.ai/tag/2020s'
			heading 2020s
		link Male Vocalist, url='https://sonauto.ai/tag/male%20vocalist'
			heading Male Vocalist
		link Pop, url='https://sonauto.ai/tag/pop'
			heading Pop
		link Emotional, url='https://sonauto.ai/tag/emotional'
			heading Emotional
		link Blues, url='https://sonauto.ai/tag/blues'
			heading Blues
		link Female Vocalist, url='https://sonauto.ai/tag/female%20vocalist'
			heading Female Vocalist
		link Electronic, url='https://sonauto.ai/tag/electronic'
			heading Electronic
		link Rock, url='https://sonauto.ai/tag/rock'
			heading Rock
		link Electric Guitar, url='https://sonauto.ai/tag/electric%20guitar'
			heading Electric Guitar
		link Rap, url='https://sonauto.ai/tag/rap'
			heading Rap
		link Electric Blues, url='https://sonauto.ai/tag/electric%20blues'
			heading Electric Blues
		link Hip Hop, url='https://sonauto.ai/tag/hip%20hop'
			heading Hip Hop
		link Piano, url='https://sonauto.ai/tag/piano'
			heading Piano
		link 1970s, url='https://sonauto.ai/tag/1970s'
			heading 1970s
		link Nu-Disco, url='https://sonauto.ai/tag/nu-disco'
			heading Nu-Disco
		link Instrumental, url='https://sonauto.ai/tag/instrumental'
			heading Instrumental
		link Uplifting, url='https://sonauto.ai/tag/uplifting'
			heading Uplifting
		link Melodic, url='https://sonauto.ai/tag/melodic'
			heading Melodic
		link Synthpop, url='https://sonauto.ai/tag/synthpop'
			heading Synthpop
		link 2010s, url='https://sonauto.ai/tag/2010s'
			heading 2010s
		image
		image
	region Notifications (F8)
		list
```
</details>

**Reasoning for action:** By clicking on the link for 'Dark Radio Network,' I am initiating the action to view the details of this specific playlist. This follows the user's instruction to explore multiple playlists and enables them to discover curated music that fits their mood. Clicking on this link will lead to the relevant information about the playlist, thus moving closer to fulfilling the user's exploration goal.

**Action:** click('83') # Click on the 'Dark Radio Network' playlist to explore its content.

**Change Description:** The agent clicked on the 'Dark Radio Network' playlist link, which likely updated the display to show the details of the playlist, such as its songs and overall listener statistics, moving away from the previous state where only a list of playlists was displayed.

**Screenshot before:****Screenshot after:**---


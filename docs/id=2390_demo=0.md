# Task

**Product Purchase Journey for Acnipop Barra Dermolimpiadora**

As a skincare enthusiast,
I explore and purchase skincare products easily,
so that I can find effective solutions for my skin concerns without hassle.

**Success definition:** Given I am on the My Next Derma homepage
When I click on the 'Productos' link, select a product, and add it to my shopping cart
Then I should see the product details for 'Acnipop Barra Dermolimpiadora' displayed, a confirmation message indicating the item has been added to my cart, and my cart should reflect 1 item.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://mynextderma.com/

https://mynextderma.com/collections/all

**Content (before/after):** 

```
RootWebArea My NextDerma - Hablemos de tu piel – mynextderma, focused, url='https://mynextderma.com/'
	link Ir directamente al contenido, url='https://mynextderma.com/#MainContent'
	list
		listitem
			[118] link Facebook, center=(417,19), url='https://www.facebook.com/MyNextDerma'
```
<details><summary>Show more</summary>

```
		listitem
			[122] link Instagram, center=(455,19), url='https://www.instagram.com/mynextderma/'
		listitem
			[126] link YouTube, center=(493,19), url='https://www.youtube.com/c/MyNextDerma'
		listitem
			[130] link TikTok, center=(531,19), url='https://www.tiktok.com/@mynextderma'
	region Anuncio
		paragraph
			StaticText Envío Gratis en ordenes mayores a $799
	banner
		heading mynextderma
			[216] link mynextderma, center=(510,76), url='https://mynextderma.com/'
				image mynextderma, url='https://mynextderma.com/cdn/shop/files/Asset_3.jpg?v=1651420910&width=200'
		navigation
			list
				listitem
					[222] link Inicio, center=(668,76), url='https://mynextderma.com/'
				listitem
					[225] link Productos, center=(745,76), url='https://mynextderma.com/collections/all'
				listitem
					[228] link Descargar, center=(839,76), url='https://mynextderma.com/pages/descargar'
		heading País/región
		[241] button MXN $ | México, center=(1352,76), expanded=False, type=button
		group
			button Búsqueda, expanded=False, hasPopup='dialog'
		[277] link Carrito, center=(1492,76), url='https://mynextderma.com/cart'
		[256] svg, center=(1448,76)
	main
		image, url='https://mynextderma.com/cdn/shop/files/Sin-titulo-1-03.webp?v=1678042150&width=2000'
		heading ¿Cómo Funciona My NextDerma?
		list
			listitem
				image, url='https://mynextderma.com/cdn/shop/files/Farmacia_online.jpg?v=1676610554&width=400'
				heading Descarga
				paragraph
					StaticText Si aún no cuentas con My NextDerma, descargala en Google Play o App Store, puedes crear una cuenta con tu correo electrónico o redes sociales.
			listitem
				image DErmatologo online, url='https://mynextderma.com/cdn/shop/files/Sin_titulo-1-11_a5cff32f-d242-4961-a817-6f2d44de282b.jpg?v=1676610581&width=400'
				heading Agenda
				paragraph
					StaticText Elige la un especialista, selecciona una fecha y hora que prefieras. Ingresa a la App al momento de tu cita y recibe tu consulta.
			listitem
				image, url='https://mynextderma.com/cdn/shop/files/rutina_skin_care.jpg?v=1676610635&width=400'
				heading Inicia tu tratamiento
				paragraph
					StaticText Al finalizar tu consulta, podrás visualizar las instrucciones, dosis y recomendaciones y si lo deseas enviamos tu tratamiento a la puerta de tu casa.
		link Clic para descargar, url='https://mynextderma.com/pages/descargar'
		heading Conoce nuestra farmacia
		list
			listitem
				image, url='https://mynextderma.com/cdn/shop/products/8429420201361.webp?v=1681685311&width=535'
				heading Protectores
					link Protectores, url='https://mynextderma.com/collections/protectores-1'
			listitem
				image, url='https://mynextderma.com/cdn/shop/products/3282770100259.webp?v=1681273861&width=535'
				heading Dermolimpiadores
					link Dermolimpiadores, url='https://mynextderma.com/collections/limpiadores'
			listitem
				image, url='https://mynextderma.com/cdn/shop/products/3337875694469.webp?v=1681945960&width=535'
				heading Hidratantes
					link Hidratantes, url='https://mynextderma.com/collections/hidratantes'
			listitem
				image, url='https://mynextderma.com/cdn/shop/collections/CapturadePantalla2022-09-27ala_s_12.01.01_480x480_f011aff8-5f54-4e1f-af31-f25a6b7b9a14.webp?v=1696214460'
				heading Medkins
					link Medkins, url='https://mynextderma.com/collections/medkins'
		link Ver todo Conoce nuestra farmacia, url='https://mynextderma.com/collections'
		heading Dermolimpiadores
		list Carrusel
			listitem
				image CLEANANCE GEL 400ML, url='https://mynextderma.com/cdn/shop/products/3282770100259.webp?v=1681273861&width=360'
				StaticText Oferta
				heading CLEANANCE GEL 400ML Oferta
					link CLEANANCE GEL 400ML Oferta, url='https://mynextderma.com/products/cleanance-gel-400ml'
				StaticText Precio habitual
				deletion
					StaticText $ 590.00 MXN
				StaticText Precio de oferta
				StaticText $ 546.00 MXN
				button Agregar al carrito CLEANANCE GEL 400ML, hasPopup='dialog'
			listitem
				image Sebium Gel Moussant 500 ML, url='https://mynextderma.com/cdn/shop/products/3401399277092.webp?v=1681945691&width=360'
				StaticText Oferta
				heading Sebium Gel Moussant 500 ML Oferta
					link Sebium Gel Moussant 500 ML Oferta, url='https://mynextderma.com/products/sebium-gel-moussant-500-ml'
				StaticText Precio habitual
				deletion
					StaticText $ 695.00 MXN
				StaticText Precio de oferta
				StaticText $ 623.00 MXN
				button Agregar al carrito Sebium Gel Moussant 500 ML, hasPopup='dialog'
			listitem
				image Atoderm Gel Ducha, url='https://mynextderma.com/cdn/shop/products/3401399372407.webp?v=1681269283&width=360'
				heading Atoderm Gel Ducha
					link Atoderm Gel Ducha, url='https://mynextderma.com/products/atoderm-gel-ducha'
				StaticText Precio habitual
				StaticText $ 599.00 MXN
				button Agregar al carrito Atoderm Gel Ducha, hasPopup='dialog'
			listitem
				image Eucerin Dermopure Exfoliante, url='https://mynextderma.com/cdn/shop/products/4005900436993.webp?v=1681677425&width=360'
				heading Eucerin Dermopure Exfoliante
					link Eucerin Dermopure Exfoliante, url='https://mynextderma.com/products/eucerin-dermopure-exfoliante'
				StaticText Precio habitual
				StaticText $ 502.00 MXN
				button Agregar al carrito Eucerin Dermopure Exfoliante, hasPopup='dialog'
		link Ver todos los productos de la colección Dermolimpiadores, url='https://mynextderma.com/collections/limpiadores'
		heading Hidratantes
		list Carrusel
			listitem
				image Retinol B3 Serum anti-arrugas 30ml, url='https://mynextderma.com/cdn/shop/products/3337875694469.webp?v=1681945960&width=360'
				StaticText Oferta
				heading Retinol B3 Serum anti-arrugas 30ml Oferta
					link Retinol B3 Serum anti-arrugas 30ml Oferta, url='https://mynextderma.com/products/redermic-retinol-b3-suero-30ml'
				StaticText Precio habitual
				deletion
					StaticText $ 1,185.00 MXN
				StaticText Precio de oferta
				StaticText $ 1,050.00 MXN
				button Agregar al carrito Retinol B3 Serum anti-arrugas 30ml, hasPopup='dialog'
			listitem
				image Vichy 89 Mineral 50ml, url='https://mynextderma.com/cdn/shop/products/3337875543248.webp?v=1682025996&width=360'
				heading Vichy 89 Mineral 50ml
					link Vichy 89 Mineral 50ml, url='https://mynextderma.com/products/vichy-89-mineral'
				StaticText Precio habitual
				StaticText $ 765.00 MXN
				button Agregar al carrito Vichy 89 Mineral 50ml, hasPopup='dialog'
			listitem
				image Hyalu B5 Crema, url='https://mynextderma.com/cdn/shop/products/3337875583589.webp?v=1681686397&width=360'
				StaticText Oferta
				heading Hyalu B5 Crema Oferta
					link Hyalu B5 Crema Oferta, url='https://mynextderma.com/products/hyalu-b5-crema'
				StaticText Precio habitual
				deletion
					StaticText $ 999.00 MXN
				StaticText Precio de oferta
				StaticText $ 971.00 MXN
				button Agregar al carrito Hyalu B5 Crema, hasPopup='dialog'
			listitem
				image Cicabio Crema, url='https://mynextderma.com/cdn/shop/products/3401347869546_4_2000x_7b23b3a3-7ac0-4b22-a8ad-85710157e8e3.webp?v=1681274370&width=360'
				heading Cicabio Crema
					link Cicabio Crema, url='https://mynextderma.com/products/cicabio-crema'
				StaticText Precio habitual
				StaticText $ 449.00 MXN
				button Agregar al carrito Cicabio Crema, hasPopup='dialog'
		link Ver todos los productos de la colección Hidratantes, url='https://mynextderma.com/collections/hidratantes'
		heading Protectores Solares
		list Carrusel
			listitem
				image Fusion Water Urban FPS50, url='https://mynextderma.com/cdn/shop/products/8429420201361.webp?v=1681685311&width=360'
				StaticText Oferta
				heading Fusion Water Urban FPS50 Oferta
					link Fusion Water Urban FPS50 Oferta, url='https://mynextderma.com/products/fusion-water-urban-fps50'
				StaticText Precio habitual
				deletion
					StaticText $ 686.00 MXN
				StaticText Precio de oferta
				StaticText $ 539.00 MXN
				button Agregar al carrito Fusion Water Urban FPS50, hasPopup='dialog'
			listitem
				image Isdin Spf50 Ultra Age Repair Water, url='https://mynextderma.com/cdn/shop/products/8429420144002.webp?v=1681859472&width=360'
				StaticText Oferta
				heading Isdin Spf50 Ultra Age Repair Water Oferta
					link Isdin Spf50 Ultra Age Repair Water Oferta, url='https://mynextderma.com/products/isdin-spf50-ultra-age-repair-water'
				StaticText Precio habitual
				deletion
					StaticText $ 761.00 MXN
				StaticText Precio de oferta
				StaticText $ 645.00 MXN
				button Agregar al carrito Isdin Spf50 Ultra Age Repair Water, hasPopup='dialog'
			listitem
				image CAPITAL SOLEIL MATIFICANTE 3 EN 1 FPS50 50ML, url='https://mynextderma.com/cdn/shop/products/3337875695176_2_2000x_4aea1c0c-6492-43e5-929d-07ba20d73ba8.webp?v=1681270805&width=360'
				StaticText Oferta
				heading CAPITAL SOLEIL MATIFICANTE 3 EN 1 FPS50 50ML Oferta
					link CAPITAL SOLEIL MATIFICANTE 3 EN 1 FPS50 50ML Oferta, url='https://mynextderma.com/products/capital-soleil-matificante-3-en-1-fps50-50ml'
				StaticText Precio habitual
				deletion
					StaticText $ 578.00 MXN
				StaticText Precio de oferta
				StaticText $ 525.00 MXN
				button Agregar al carrito CAPITAL SOLEIL MATIFICANTE 3 EN 1 FPS50 50ML, hasPopup='dialog'
			listitem
				image Heliocare 360° C/30 Capsulas, url='https://mynextderma.com/cdn/shop/products/8470001776211.webp?v=1681685607&width=360'
				heading Heliocare 360° C/30 Capsulas
					link Heliocare 360° C/30 Capsulas, url='https://mynextderma.com/products/heliocare-360-c-30-capsulas'
				StaticText Precio habitual
				StaticText $ 685.00 MXN
				button Agregar al carrito Heliocare 360° C/30 Capsulas, hasPopup='dialog'
		link Ver todos los productos de la colección Protectores, url='https://mynextderma.com/collections/protectores-1'
		heading Cabello
		list Carrusel
			listitem
				image Kerium Ds Shampoo, url='https://mynextderma.com/cdn/shop/products/3433422407268.webp?v=1681875224&width=360'
				StaticText Oferta
				heading Kerium Ds Shampoo Oferta
					link Kerium Ds Shampoo Oferta, url='https://mynextderma.com/products/kerium-ds-shampoo'
				StaticText Precio habitual
				deletion
					StaticText $ 689.00 MXN
				StaticText Precio de oferta
				StaticText $ 619.00 MXN
				button Agregar al carrito Kerium Ds Shampoo, hasPopup='dialog'
			listitem
				image Iraltone Forte C/60 Capsulas, url='https://mynextderma.com/cdn/shop/products/8470001612335.webp?v=1681858615&width=360'
				StaticText Oferta
				heading Iraltone Forte C/60 Capsulas Oferta
					link Iraltone Forte C/60 Capsulas Oferta, url='https://mynextderma.com/products/iraltone-foite-c-60-capsulas'
				StaticText Precio habitual
				deletion
					StaticText $ 895.00 MXN
				StaticText Precio de oferta
				StaticText $ 831.00 MXN
				button Agregar al carrito Iraltone Forte C/60 Capsulas, hasPopup='dialog'
			listitem
				image Pilopeptan Woman Mascarilla 200ml, url='https://mynextderma.com/cdn/shop/products/8423372840210.webp?v=1681943824&width=360'
				StaticText Oferta
				heading Pilopeptan Woman Mascarilla 200ml Oferta
					link Pilopeptan Woman Mascarilla 200ml Oferta, url='https://mynextderma.com/products/pilopeptan-woman-mascarilla-200ml'
				StaticText Precio habitual
				deletion
					StaticText $ 899.00 MXN
				StaticText Precio de oferta
				StaticText $ 747.00 MXN
				button Agregar al carrito Pilopeptan Woman Mascarilla 200ml, hasPopup='dialog'
			listitem
				image Dercos Estimulante 200ml, url='https://mynextderma.com/cdn/shop/products/3337871311292.webp?v=1681426861&width=360'
				heading Dercos Estimulante 200ml
					link Dercos Estimulante 200ml, url='https://mynextderma.com/products/dercos-estimulante'
				StaticText Precio habitual
				StaticText $ 535.00 MXN
				button Agregar al carrito Dercos Estimulante 200ml, hasPopup='dialog'
		link Ver todos los productos de la colección Cabello, url='https://mynextderma.com/collections/cabello'
		image, url='https://mynextderma.com/cdn/shop/files/Dermatologo_cerca_de_mi.png?v=1675919775&width=2000'
	contentinfo
		heading ¡Descarga My Nextderma y hablemos de tu piel!
		paragraph
			StaticText Obtén una consulta con los especialistas de los influencers a solo un click de distancia
		heading Siguenos en redes sociales
		list
			listitem
				link Facebook, url='https://www.facebook.com/MyNextDerma'
			listitem
				link Instagram, url='https://www.instagram.com/mynextderma/'
			listitem
				link YouTube, url='https://www.youtube.com/c/MyNextDerma'
			listitem
				link TikTok, url='https://www.tiktok.com/@mynextderma'
		heading Sobre nosotros
		list
			listitem
				link Contacto, url='https://linktr.ee/mynextderma'
			listitem
				link Blogs, url='https://mynextderma.com/blogs/noticias'
			listitem
				link Política de Privacidad, url='https://mynextderma.com/pages/politica-de-privacidad'
			listitem
				link Descargar My NextDerma, url='https://mynextderma.com/pages/descargar'
		heading País/región
		button MXN $ | México, expanded=False
		StaticText Formas de pago
		list
			listitem
				image PayPal
		StaticText © 2024,
		link mynextderma, url='https://mynextderma.com/'
		link Derechos Reservados, url='https://es.shopify.com/?utm_campaign=poweredby&utm_medium=shopify&utm_source=onlinestore'
		list
			listitem
				StaticText ·
				link Política de privacidad, url='https://mynextderma.com/policies/privacy-policy'
	[1461] button Ventana de chat, center=(52,1029), expanded=True
		image
```
</details>



```
RootWebArea Productos – mynextderma, focused, url='https://mynextderma.com/collections/all'
	link Ir directamente al contenido, url='https://mynextderma.com/collections/all#MainContent'
	list
		listitem
			[139] link Facebook, center=(417,19), url='https://www.facebook.com/MyNextDerma'
```
<details><summary>Show more</summary>

```
		listitem
			[143] link Instagram, center=(455,19), url='https://www.instagram.com/mynextderma/'
		listitem
			[147] link YouTube, center=(493,19), url='https://www.youtube.com/c/MyNextDerma'
		listitem
			[151] link TikTok, center=(531,19), url='https://www.tiktok.com/@mynextderma'
	region Anuncio
		paragraph
			StaticText Envío Gratis en ordenes mayores a $799
	banner
		[236] link mynextderma, center=(510,76), url='https://mynextderma.com/'
			image mynextderma, url='https://mynextderma.com/cdn/shop/files/Asset_3.jpg?v=1651420910&width=200'
		navigation
			list
				listitem
					[242] link Inicio, center=(668,76), url='https://mynextderma.com/'
				listitem
					[245] link Productos, center=(745,76), url='https://mynextderma.com/collections/all'
				listitem
					[248] link Descargar, center=(839,76), url='https://mynextderma.com/pages/descargar'
		heading País/región
		[261] button MXN $ | México, center=(1352,76), expanded=False, type=button
		group
			button Búsqueda, expanded=False, hasPopup='dialog'
		[297] link Carrito, center=(1492,76), url='https://mynextderma.com/cart'
		[276] svg, center=(1448,76)
	main
		complementary Filtrar:
			heading Filtrar:
			group
				button Disponibilidad (0 seleccionado), expanded=False
			group
				button Precio, expanded=False
			[340] svg, center=(580,172)
			[339] span, center=(521,170), inner_text=Disponibilidad
			group
				button Marca (0 seleccionado), expanded=False
			[382] svg, center=(675,172)
			[381] span, center=(642,170), inner_text=Precio
			heading Ordenar por:
				LabelText
			[399] svg, center=(770,172)
			[398] span, center=(736,170), inner_text=Marca
			[824] combobox Ordenar por: value='Alfabéticamente, A-Z', center=(1271,170), contenteditable=True, expanded=False, hasPopup='menu', inner_text=Características
Más vendidos
Alfabéticamente, A-Z
Alfabéticamente, Z-A
Precio, menor a mayor
Precio, mayor a menor
Fecha: antiguo(a) a reciente
Fecha: reciente a antiguo(a)
				option Características, selected=False
				option Más vendidos, selected=False
				option Alfabéticamente, A-Z, selected=True
				option Alfabéticamente, Z-A, selected=False
				option Precio, menor a mayor, selected=False
				option Precio, mayor a menor, selected=False
				option Fecha: antiguo(a) a reciente, selected=False
				option Fecha: reciente a antiguo(a), selected=False
			status, atomic
				heading 491 productos
		list
			listitem
				image Acnipop Barra Dermolimpiadora, url='https://mynextderma.com/cdn/shop/products/7897473206632_2000x_ec7af170-3740-42b2-b4b6-c814268fde8a.webp?v=1677537785&width=360'
				heading Acnipop Barra Dermolimpiadora
					[1209] link Acnipop Barra Dermolimpiadora, center=(544,511), url='https://mynextderma.com/products/acnipop-barra-dermolimpiadora'
				StaticText Proveedor:
				StaticText GLENMARK
				StaticText Precio habitual
				StaticText $ 209.00 MXN
				[1237] button Agregar al carrito Acnipop Barra Dermolimpiadora, center=(544,610), hasPopup='dialog', inner_text=Agregar al carrito, type=submit
			listitem
				image Actipur Crema 30ml Color Claro, url='https://mynextderma.com/cdn/shop/products/2_ACTIPUR_Crema_BB_Color_Claro_Anti-imperfecciones_Matificante_caja_copia_2000x_026db941-17ce-43a2-a496-49666015e87e.webp?v=1677539760&width=360'
				heading Actipur Crema 30ml Color Claro
					[1263] link Actipur Crema 30ml Color Claro, center=(822,511), url='https://mynextderma.com/products/actipur-crema-color-claro'
				StaticText Proveedor:
				StaticText NOREVA
				StaticText Precio habitual
				StaticText $ 578.00 MXN
				[1291] button Agregar al carrito Actipur Crema 30ml Color Claro, center=(822,610), hasPopup='dialog', inner_text=Agregar al carrito, type=submit
			listitem
				image Actipur Barato, url='https://mynextderma.com/cdn/shop/products/3_ACTIPUR_Crema_BB_Color_Dorado_Anti-imperfecciones_Matificante_caja_copia_2000x_3dd7986c-d2c4-43c8-a296-e447a9062202.webp?v=1677539794&width=360'
				heading Actipur Crema 30ml Color Dorado
					[1317] link Actipur Crema 30ml Color Dorado, center=(1098,511), url='https://mynextderma.com/products/actipur-crema-c-dorado'
				StaticText Proveedor:
				StaticText NOREVA
				StaticText Precio habitual
				StaticText $ 578.00 MXN
				[1345] button Agregar al carrito Actipur Crema 30ml Color Dorado, center=(1098,610), hasPopup='dialog', inner_text=Agregar al carrito, type=submit
			listitem
				image Adaferin adapaleno 3%, url='https://mynextderma.com/cdn/shop/products/PS_Adaferin_03_45g_2000x_8189784f-4d6c-40a9-bd06-20b040f8bf28.webp?v=1677540011&width=360'
				heading Adaferin 3% Gel
					[1371] link Adaferin 3% Gel, center=(1376,511), url='https://mynextderma.com/products/adaferin-3-gel'
				StaticText Proveedor:
				StaticText GALDERMA
				StaticText Precio habitual
				StaticText $ 831.00 MXN
				[1399] button Agregar al carrito Adaferin 3% Gel, center=(1376,610), hasPopup='dialog', inner_text=Agregar al carrito, type=submit
			listitem
				image Adaferin crema galderma adapaleno, url='https://mynextderma.com/cdn/shop/products/PS_Adaferin_crema_01_30g_2000x_58b33b04-103d-4ef2-af05-cd145ee8a1f8.webp?v=1677540089&width=360'
				StaticText Agotado
				heading Adaferin Crema Agotado
					[1426] link Adaferin Crema Agotado, center=(544,946), inner_text=Adaferin Crema, url='https://mynextderma.com/products/adaferin-crema'
				StaticText Proveedor:
				StaticText GALDERMA
				StaticText Precio habitual
				StaticText $ 674.00 MXN
				[1454] button Agotado Adaferin Crema, center=(544,1045), hasPopup='dialog', inner_text=Agotado, type=submit
			listitem
				image Adaferin Gel, url='https://mynextderma.com/cdn/shop/products/Adaferingel.webp?v=1677540283&width=360'
				StaticText Agotado
				heading Adaferin Gel Agotado
					[1482] link Adaferin Gel Agotado, center=(822,946), inner_text=Adaferin Gel, url='https://mynextderma.com/products/adaferin-gel'
				StaticText Proveedor:
				StaticText GALDERMA
				StaticText Precio habitual
				StaticText $ 699.00 MXN
				[1510] button Agotado Adaferin Gel, center=(822,1045), hasPopup='dialog', inner_text=Agotado, type=submit
			listitem
				image Aderma barra, url='https://mynextderma.com/cdn/shop/products/Adermabarra.webp?v=1677540357&width=360'
				heading Aderma Barra
					[1537] link Aderma Barra, center=(1098,946), url='https://mynextderma.com/products/aderma-barra'
				StaticText Proveedor:
				StaticText ADERMA
				StaticText Precio habitual
				StaticText $ 190.00 MXN
				[1565] button Agregar al carrito Aderma Barra, center=(1098,1045), hasPopup='dialog', inner_text=Agregar al carrito, type=submit
			listitem
				image agua thermale avene, url='https://mynextderma.com/cdn/shop/products/aguatermalavene.webp?v=1677731749&width=360'
				heading Agua Termal Avene 150ml
					[1591] link Agua Termal Avene 150ml, center=(1376,946), url='https://mynextderma.com/products/agua-termal-avene-2'
				StaticText Proveedor:
				StaticText AVENE
				StaticText Precio habitual
				StaticText $ 311.00 MXN
				[1619] button Agregar al carrito Agua Termal Avene 150ml, center=(1376,1045), hasPopup='dialog', inner_text=Agregar al carrito, type=submit
			listitem
				image agua termal avene 300ml, url='https://mynextderma.com/cdn/shop/products/aguatermalavene300ml.webp?v=1677731906&width=360'
				StaticText Agotado
				heading Agua Termal Avene 300ml Agotado
					link Agua Termal Avene 300ml Agotado, url='https://mynextderma.com/products/agua-termal-avene'
				StaticText Proveedor:
				StaticText AVENE
				StaticText Precio habitual
				deletion
					StaticText $ 421.00 MXN
				StaticText Precio de oferta
				StaticText $ 399.00 MXN
				button Agotado Agua Termal Avene 300ml, disabled=True, hasPopup='dialog'
			listitem
				image agua termal la roche posay, url='https://mynextderma.com/cdn/shop/products/aguatermallarocheposay.webp?v=1677790609&width=360'
				StaticText Agotado
				heading Agua Termal La Roche Posay 150ml Agotado
					link Agua Termal La Roche Posay 150ml Agotado, url='https://mynextderma.com/products/agua-termal-la-roche-posay'
				StaticText Proveedor:
				StaticText LA ROCHE POSAY
				StaticText Precio habitual
				deletion
					StaticText $ 379.00 MXN
				StaticText Precio de oferta
				StaticText $ 353.00 MXN
				button Agotado Agua Termal La Roche Posay 150ml, disabled=True, hasPopup='dialog'
			listitem
				image agua termal la roche posay 300ml, url='https://mynextderma.com/cdn/shop/products/aguatermallarocheposay300ml.webp?v=1677790882&width=360'
				heading Agua Termal La Roche Posay 300ml
					link Agua Termal La Roche Posay 300ml, url='https://mynextderma.com/products/agua-termal-la-roche-posay-2'
				StaticText Proveedor:
				StaticText LA ROCHE POSAY
				StaticText Precio habitual
				StaticText $ 394.00 MXN
				button Agregar al carrito Agua Termal La Roche Posay 300ml, hasPopup='dialog'
			listitem
				image alquisalic shampoo, url='https://mynextderma.com/cdn/shop/products/alquisalicshampoo.webp?v=1677791580&width=360'
				heading Alquisalic Shampoo
					link Alquisalic Shampoo, url='https://mynextderma.com/products/alquisalic-shampoo'
				StaticText Proveedor:
				StaticText EUDERMA
				StaticText Precio habitual
				StaticText $ 245.00 MXN
				button Agregar al carrito Alquisalic Shampoo, hasPopup='dialog'
			listitem
				image anacastel 5.0$ solución 60ml, url='https://mynextderma.com/cdn/shop/products/anacatel5.0_solucion60ml.webp?v=1677791750&width=360'
				heading Anacastel 5.0% solucion 60ml
					link Anacastel 5.0% solucion 60ml, url='https://mynextderma.com/products/anacastel-5-0-solucion-60ml'
				StaticText Proveedor:
				StaticText FARMAPIEL
				StaticText Precio habitual
				StaticText $ 614.00 MXN
				button Agregar al carrito Anacastel 5.0% solucion 60ml, hasPopup='dialog'
			listitem
				image anaphase acondicionador 200ml, url='https://mynextderma.com/cdn/shop/products/anaphaseacondicionador200ml.webp?v=1677792365&width=360'
				heading ANAPHASE ACONDICIONADOR 200ML
					link ANAPHASE ACONDICIONADOR 200ML, url='https://mynextderma.com/products/anaphase-acondicionador-200ml'
				StaticText Proveedor:
				StaticText DUCRAY
				StaticText Precio habitual
				StaticText $ 535.00 MXN
				button Agregar al carrito ANAPHASE ACONDICIONADOR 200ML, hasPopup='dialog'
			listitem
				image anaphase shampoo estimulante, url='https://mynextderma.com/cdn/shop/products/anaphaseshampooestimulante.webp?v=1677793394&width=360'
				heading Anaphase Shampoo Estimulante
					link Anaphase Shampoo Estimulante, url='https://mynextderma.com/products/anaphase-shampoo-estimulante'
				StaticText Proveedor:
				StaticText DUCRAY
				StaticText Precio habitual
				StaticText $ 516.00 MXN
				button Agregar al carrito Anaphase Shampoo Estimulante, hasPopup='dialog'
			listitem
				image Anthelios 50+ Bebe Lait 50ml, url='https://mynextderma.com/cdn/shop/products/3337872419904_1_2000x_b6876b4b-91e7-4717-9574-0f7d7af0593f.webp?v=1681268403&width=360'
				StaticText Oferta
				heading Anthelios 50+ Bebe Lait 50ml Oferta
					link Anthelios 50+ Bebe Lait 50ml Oferta, url='https://mynextderma.com/products/anthelios-50-bebe-lait-50ml'
				StaticText Proveedor:
				StaticText LA ROCHE POSAY
				StaticText Precio habitual
				deletion
					StaticText $ 659.00 MXN
				StaticText Precio de oferta
				StaticText $ 589.00 MXN
				button Agregar al carrito Anthelios 50+ Bebe Lait 50ml, hasPopup='dialog'
		navigation Paginación
			list
				listitem
					link Página 1, disabled=True
				listitem
					link Página 2, url='https://mynextderma.com/collections/all?page=2'
				listitem
					link Página 3, url='https://mynextderma.com/collections/all?page=3'
				listitem
					StaticText …
				listitem
					link Página 31, url='https://mynextderma.com/collections/all?page=31'
				listitem
					link Página siguiente, url='https://mynextderma.com/collections/all?page=2'
		image, url='https://mynextderma.com/cdn/shop/files/ultima-07.jpg?v=1666396657&width=2000'
	contentinfo
		heading ¡Descarga My Nextderma y hablemos de tu piel!
		paragraph
			StaticText Obtén una consulta con los especialistas de los influencers a solo un click de distancia
		heading Siguenos en redes sociales
		list
			listitem
				link Facebook, url='https://www.facebook.com/MyNextDerma'
			listitem
				link Instagram, url='https://www.instagram.com/mynextderma/'
			listitem
				link YouTube, url='https://www.youtube.com/c/MyNextDerma'
			listitem
				link TikTok, url='https://www.tiktok.com/@mynextderma'
		heading Sobre nosotros
		list
			listitem
				link Contacto, url='https://linktr.ee/mynextderma'
			listitem
				link Blogs, url='https://mynextderma.com/blogs/noticias'
			listitem
				link Política de Privacidad, url='https://mynextderma.com/pages/politica-de-privacidad'
			listitem
				link Descargar My NextDerma, url='https://mynextderma.com/pages/descargar'
		heading País/región
		button MXN $ | México, expanded=False
		StaticText Formas de pago
		list
			listitem
				image PayPal
		StaticText © 2024,
		link mynextderma, url='https://mynextderma.com/'
		link Derechos Reservados, url='https://es.shopify.com/?utm_campaign=poweredby&utm_medium=shopify&utm_source=onlinestore'
		list
			listitem
				StaticText ·
				link Política de privacidad, url='https://mynextderma.com/policies/privacy-policy'
	[2194] button Ventana de chat, center=(52,1029), expanded=True
		image
		StaticText 1
```
</details>

**Reasoning for action:** By clicking on the 'Productos' link, I access the category where all skincare products are displayed. This is an essential step towards fulfilling the user story, as the user wants to browse products that can address their skin concerns. This direct interaction with the webpage aligns with the user's goal to explore and purchase products efficiently.

**Action:** click('225') # Click on the 'Productos' link to explore the products offered.

**Change Description:** The browser's state changed from displaying the homepage of My NextDerma to the products page, showing a list of various skincare products along with their prices and availability. The focus shifted from the general content to specific product listings, allowing users to explore and add items to their cart.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://mynextderma.com/collections/all

https://mynextderma.com/products/acnipop-barra-dermolimpiadora

**Content (before/after):** 

```
RootWebArea Productos – mynextderma, focused, url='https://mynextderma.com/collections/all'
	link Ir directamente al contenido, url='https://mynextderma.com/collections/all#MainContent'
	list
		listitem
			[139] link Facebook, center=(417,19), url='https://www.facebook.com/MyNextDerma'
```
<details><summary>Show more</summary>

```
		listitem
			[143] link Instagram, center=(455,19), url='https://www.instagram.com/mynextderma/'
		listitem
			[147] link YouTube, center=(493,19), url='https://www.youtube.com/c/MyNextDerma'
		listitem
			[151] link TikTok, center=(531,19), url='https://www.tiktok.com/@mynextderma'
	region Anuncio
		paragraph
			StaticText Envío Gratis en ordenes mayores a $799
	banner
		[236] link mynextderma, center=(510,76), url='https://mynextderma.com/'
			image mynextderma, url='https://mynextderma.com/cdn/shop/files/Asset_3.jpg?v=1651420910&width=200'
		navigation
			list
				listitem
					[242] link Inicio, center=(668,76), url='https://mynextderma.com/'
				listitem
					[245] link Productos, center=(745,76), url='https://mynextderma.com/collections/all'
				listitem
					[248] link Descargar, center=(839,76), url='https://mynextderma.com/pages/descargar'
		heading País/región
		[261] button MXN $ | México, center=(1352,76), expanded=False, type=button
		group
			button Búsqueda, expanded=False, hasPopup='dialog'
		[297] link Carrito, center=(1492,76), url='https://mynextderma.com/cart'
		[276] svg, center=(1448,76)
	main
		complementary Filtrar:
			heading Filtrar:
			group
				button Disponibilidad (0 seleccionado), expanded=False
			group
				button Precio, expanded=False
			[340] svg, center=(580,172)
			[339] span, center=(521,170), inner_text=Disponibilidad
			group
				button Marca (0 seleccionado), expanded=False
			[382] svg, center=(675,172)
			[381] span, center=(642,170), inner_text=Precio
			heading Ordenar por:
				LabelText
			[399] svg, center=(770,172)
			[398] span, center=(736,170), inner_text=Marca
			[824] combobox Ordenar por: value='Alfabéticamente, A-Z', center=(1271,170), contenteditable=True, expanded=False, hasPopup='menu', inner_text=Características
Más vendidos
Alfabéticamente, A-Z
Alfabéticamente, Z-A
Precio, menor a mayor
Precio, mayor a menor
Fecha: antiguo(a) a reciente
Fecha: reciente a antiguo(a)
				option Características, selected=False
				option Más vendidos, selected=False
				option Alfabéticamente, A-Z, selected=True
				option Alfabéticamente, Z-A, selected=False
				option Precio, menor a mayor, selected=False
				option Precio, mayor a menor, selected=False
				option Fecha: antiguo(a) a reciente, selected=False
				option Fecha: reciente a antiguo(a), selected=False
			status, atomic
				heading 491 productos
		list
			listitem
				image Acnipop Barra Dermolimpiadora, url='https://mynextderma.com/cdn/shop/products/7897473206632_2000x_ec7af170-3740-42b2-b4b6-c814268fde8a.webp?v=1677537785&width=360'
				heading Acnipop Barra Dermolimpiadora
					[1209] link Acnipop Barra Dermolimpiadora, center=(544,511), url='https://mynextderma.com/products/acnipop-barra-dermolimpiadora'
				StaticText Proveedor:
				StaticText GLENMARK
				StaticText Precio habitual
				StaticText $ 209.00 MXN
				[1237] button Agregar al carrito Acnipop Barra Dermolimpiadora, center=(544,610), hasPopup='dialog', inner_text=Agregar al carrito, type=submit
			listitem
				image Actipur Crema 30ml Color Claro, url='https://mynextderma.com/cdn/shop/products/2_ACTIPUR_Crema_BB_Color_Claro_Anti-imperfecciones_Matificante_caja_copia_2000x_026db941-17ce-43a2-a496-49666015e87e.webp?v=1677539760&width=360'
				heading Actipur Crema 30ml Color Claro
					[1263] link Actipur Crema 30ml Color Claro, center=(822,511), url='https://mynextderma.com/products/actipur-crema-color-claro'
				StaticText Proveedor:
				StaticText NOREVA
				StaticText Precio habitual
				StaticText $ 578.00 MXN
				[1291] button Agregar al carrito Actipur Crema 30ml Color Claro, center=(822,610), hasPopup='dialog', inner_text=Agregar al carrito, type=submit
			listitem
				image Actipur Barato, url='https://mynextderma.com/cdn/shop/products/3_ACTIPUR_Crema_BB_Color_Dorado_Anti-imperfecciones_Matificante_caja_copia_2000x_3dd7986c-d2c4-43c8-a296-e447a9062202.webp?v=1677539794&width=360'
				heading Actipur Crema 30ml Color Dorado
					[1317] link Actipur Crema 30ml Color Dorado, center=(1098,511), url='https://mynextderma.com/products/actipur-crema-c-dorado'
				StaticText Proveedor:
				StaticText NOREVA
				StaticText Precio habitual
				StaticText $ 578.00 MXN
				[1345] button Agregar al carrito Actipur Crema 30ml Color Dorado, center=(1098,610), hasPopup='dialog', inner_text=Agregar al carrito, type=submit
			listitem
				image Adaferin adapaleno 3%, url='https://mynextderma.com/cdn/shop/products/PS_Adaferin_03_45g_2000x_8189784f-4d6c-40a9-bd06-20b040f8bf28.webp?v=1677540011&width=360'
				heading Adaferin 3% Gel
					[1371] link Adaferin 3% Gel, center=(1376,511), url='https://mynextderma.com/products/adaferin-3-gel'
				StaticText Proveedor:
				StaticText GALDERMA
				StaticText Precio habitual
				StaticText $ 831.00 MXN
				[1399] button Agregar al carrito Adaferin 3% Gel, center=(1376,610), hasPopup='dialog', inner_text=Agregar al carrito, type=submit
			listitem
				image Adaferin crema galderma adapaleno, url='https://mynextderma.com/cdn/shop/products/PS_Adaferin_crema_01_30g_2000x_58b33b04-103d-4ef2-af05-cd145ee8a1f8.webp?v=1677540089&width=360'
				StaticText Agotado
				heading Adaferin Crema Agotado
					[1426] link Adaferin Crema Agotado, center=(544,946), inner_text=Adaferin Crema, url='https://mynextderma.com/products/adaferin-crema'
				StaticText Proveedor:
				StaticText GALDERMA
				StaticText Precio habitual
				StaticText $ 674.00 MXN
				[1454] button Agotado Adaferin Crema, center=(544,1045), hasPopup='dialog', inner_text=Agotado, type=submit
			listitem
				image Adaferin Gel, url='https://mynextderma.com/cdn/shop/products/Adaferingel.webp?v=1677540283&width=360'
				StaticText Agotado
				heading Adaferin Gel Agotado
					[1482] link Adaferin Gel Agotado, center=(822,946), inner_text=Adaferin Gel, url='https://mynextderma.com/products/adaferin-gel'
				StaticText Proveedor:
				StaticText GALDERMA
				StaticText Precio habitual
				StaticText $ 699.00 MXN
				[1510] button Agotado Adaferin Gel, center=(822,1045), hasPopup='dialog', inner_text=Agotado, type=submit
			listitem
				image Aderma barra, url='https://mynextderma.com/cdn/shop/products/Adermabarra.webp?v=1677540357&width=360'
				heading Aderma Barra
					[1537] link Aderma Barra, center=(1098,946), url='https://mynextderma.com/products/aderma-barra'
				StaticText Proveedor:
				StaticText ADERMA
				StaticText Precio habitual
				StaticText $ 190.00 MXN
				[1565] button Agregar al carrito Aderma Barra, center=(1098,1045), hasPopup='dialog', inner_text=Agregar al carrito, type=submit
			listitem
				image agua thermale avene, url='https://mynextderma.com/cdn/shop/products/aguatermalavene.webp?v=1677731749&width=360'
				heading Agua Termal Avene 150ml
					[1591] link Agua Termal Avene 150ml, center=(1376,946), url='https://mynextderma.com/products/agua-termal-avene-2'
				StaticText Proveedor:
				StaticText AVENE
				StaticText Precio habitual
				StaticText $ 311.00 MXN
				[1619] button Agregar al carrito Agua Termal Avene 150ml, center=(1376,1045), hasPopup='dialog', inner_text=Agregar al carrito, type=submit
			listitem
				image agua termal avene 300ml, url='https://mynextderma.com/cdn/shop/products/aguatermalavene300ml.webp?v=1677731906&width=360'
				StaticText Agotado
				heading Agua Termal Avene 300ml Agotado
					link Agua Termal Avene 300ml Agotado, url='https://mynextderma.com/products/agua-termal-avene'
				StaticText Proveedor:
				StaticText AVENE
				StaticText Precio habitual
				deletion
					StaticText $ 421.00 MXN
				StaticText Precio de oferta
				StaticText $ 399.00 MXN
				button Agotado Agua Termal Avene 300ml, disabled=True, hasPopup='dialog'
			listitem
				image agua termal la roche posay, url='https://mynextderma.com/cdn/shop/products/aguatermallarocheposay.webp?v=1677790609&width=360'
				StaticText Agotado
				heading Agua Termal La Roche Posay 150ml Agotado
					link Agua Termal La Roche Posay 150ml Agotado, url='https://mynextderma.com/products/agua-termal-la-roche-posay'
				StaticText Proveedor:
				StaticText LA ROCHE POSAY
				StaticText Precio habitual
				deletion
					StaticText $ 379.00 MXN
				StaticText Precio de oferta
				StaticText $ 353.00 MXN
				button Agotado Agua Termal La Roche Posay 150ml, disabled=True, hasPopup='dialog'
			listitem
				image agua termal la roche posay 300ml, url='https://mynextderma.com/cdn/shop/products/aguatermallarocheposay300ml.webp?v=1677790882&width=360'
				heading Agua Termal La Roche Posay 300ml
					link Agua Termal La Roche Posay 300ml, url='https://mynextderma.com/products/agua-termal-la-roche-posay-2'
				StaticText Proveedor:
				StaticText LA ROCHE POSAY
				StaticText Precio habitual
				StaticText $ 394.00 MXN
				button Agregar al carrito Agua Termal La Roche Posay 300ml, hasPopup='dialog'
			listitem
				image alquisalic shampoo, url='https://mynextderma.com/cdn/shop/products/alquisalicshampoo.webp?v=1677791580&width=360'
				heading Alquisalic Shampoo
					link Alquisalic Shampoo, url='https://mynextderma.com/products/alquisalic-shampoo'
				StaticText Proveedor:
				StaticText EUDERMA
				StaticText Precio habitual
				StaticText $ 245.00 MXN
				button Agregar al carrito Alquisalic Shampoo, hasPopup='dialog'
			listitem
				image anacastel 5.0$ solución 60ml, url='https://mynextderma.com/cdn/shop/products/anacatel5.0_solucion60ml.webp?v=1677791750&width=360'
				heading Anacastel 5.0% solucion 60ml
					link Anacastel 5.0% solucion 60ml, url='https://mynextderma.com/products/anacastel-5-0-solucion-60ml'
				StaticText Proveedor:
				StaticText FARMAPIEL
				StaticText Precio habitual
				StaticText $ 614.00 MXN
				button Agregar al carrito Anacastel 5.0% solucion 60ml, hasPopup='dialog'
			listitem
				image anaphase acondicionador 200ml, url='https://mynextderma.com/cdn/shop/products/anaphaseacondicionador200ml.webp?v=1677792365&width=360'
				heading ANAPHASE ACONDICIONADOR 200ML
					link ANAPHASE ACONDICIONADOR 200ML, url='https://mynextderma.com/products/anaphase-acondicionador-200ml'
				StaticText Proveedor:
				StaticText DUCRAY
				StaticText Precio habitual
				StaticText $ 535.00 MXN
				button Agregar al carrito ANAPHASE ACONDICIONADOR 200ML, hasPopup='dialog'
			listitem
				image anaphase shampoo estimulante, url='https://mynextderma.com/cdn/shop/products/anaphaseshampooestimulante.webp?v=1677793394&width=360'
				heading Anaphase Shampoo Estimulante
					link Anaphase Shampoo Estimulante, url='https://mynextderma.com/products/anaphase-shampoo-estimulante'
				StaticText Proveedor:
				StaticText DUCRAY
				StaticText Precio habitual
				StaticText $ 516.00 MXN
				button Agregar al carrito Anaphase Shampoo Estimulante, hasPopup='dialog'
			listitem
				image Anthelios 50+ Bebe Lait 50ml, url='https://mynextderma.com/cdn/shop/products/3337872419904_1_2000x_b6876b4b-91e7-4717-9574-0f7d7af0593f.webp?v=1681268403&width=360'
				StaticText Oferta
				heading Anthelios 50+ Bebe Lait 50ml Oferta
					link Anthelios 50+ Bebe Lait 50ml Oferta, url='https://mynextderma.com/products/anthelios-50-bebe-lait-50ml'
				StaticText Proveedor:
				StaticText LA ROCHE POSAY
				StaticText Precio habitual
				deletion
					StaticText $ 659.00 MXN
				StaticText Precio de oferta
				StaticText $ 589.00 MXN
				button Agregar al carrito Anthelios 50+ Bebe Lait 50ml, hasPopup='dialog'
		navigation Paginación
			list
				listitem
					link Página 1, disabled=True
				listitem
					link Página 2, url='https://mynextderma.com/collections/all?page=2'
				listitem
					link Página 3, url='https://mynextderma.com/collections/all?page=3'
				listitem
					StaticText …
				listitem
					link Página 31, url='https://mynextderma.com/collections/all?page=31'
				listitem
					link Página siguiente, url='https://mynextderma.com/collections/all?page=2'
		image, url='https://mynextderma.com/cdn/shop/files/ultima-07.jpg?v=1666396657&width=2000'
	contentinfo
		heading ¡Descarga My Nextderma y hablemos de tu piel!
		paragraph
			StaticText Obtén una consulta con los especialistas de los influencers a solo un click de distancia
		heading Siguenos en redes sociales
		list
			listitem
				link Facebook, url='https://www.facebook.com/MyNextDerma'
			listitem
				link Instagram, url='https://www.instagram.com/mynextderma/'
			listitem
				link YouTube, url='https://www.youtube.com/c/MyNextDerma'
			listitem
				link TikTok, url='https://www.tiktok.com/@mynextderma'
		heading Sobre nosotros
		list
			listitem
				link Contacto, url='https://linktr.ee/mynextderma'
			listitem
				link Blogs, url='https://mynextderma.com/blogs/noticias'
			listitem
				link Política de Privacidad, url='https://mynextderma.com/pages/politica-de-privacidad'
			listitem
				link Descargar My NextDerma, url='https://mynextderma.com/pages/descargar'
		heading País/región
		button MXN $ | México, expanded=False
		StaticText Formas de pago
		list
			listitem
				image PayPal
		StaticText © 2024,
		link mynextderma, url='https://mynextderma.com/'
		link Derechos Reservados, url='https://es.shopify.com/?utm_campaign=poweredby&utm_medium=shopify&utm_source=onlinestore'
		list
			listitem
				StaticText ·
				link Política de privacidad, url='https://mynextderma.com/policies/privacy-policy'
	[2194] button Ventana de chat, center=(52,1029), expanded=True
		image
		StaticText 1
```
</details>



```
RootWebArea Acnipop Barra Dermolimpiadora - My NextDerma ✅ – mynextderma, focused, url='https://mynextderma.com/products/acnipop-barra-dermolimpiadora'
	link Ir directamente al contenido, url='https://mynextderma.com/products/acnipop-barra-dermolimpiadora#MainContent'
	list
		listitem
			[147] link Facebook, center=(417,19), url='https://www.facebook.com/MyNextDerma'
```
<details><summary>Show more</summary>

```
		listitem
			[151] link Instagram, center=(455,19), url='https://www.instagram.com/mynextderma/'
		listitem
			[155] link YouTube, center=(493,19), url='https://www.youtube.com/c/MyNextDerma'
		listitem
			[159] link TikTok, center=(531,19), url='https://www.tiktok.com/@mynextderma'
	region Anuncio
		paragraph
			StaticText Envío Gratis en ordenes mayores a $799
	banner
		[244] link mynextderma, center=(510,76), url='https://mynextderma.com/'
			image mynextderma, url='https://mynextderma.com/cdn/shop/files/Asset_3.jpg?v=1651420910&width=200'
		navigation
			list
				listitem
					[250] link Inicio, center=(668,76), url='https://mynextderma.com/'
				listitem
					[253] link Productos, center=(745,76), url='https://mynextderma.com/collections/all'
				listitem
					[256] link Descargar, center=(839,76), url='https://mynextderma.com/pages/descargar'
		heading País/región
		[269] button MXN $ | México, center=(1352,76), expanded=False, type=button
		group
			button Búsqueda, expanded=False, hasPopup='dialog'
		[305] link Carrito, center=(1492,76), url='https://mynextderma.com/cart'
		[284] svg, center=(1448,76)
	main
		region Visor de la galería
			link Ir directamente a la información del producto, url='https://mynextderma.com/products/acnipop-barra-dermolimpiadora#ProductInfo-template--16910616887528__main'
			list
				[341] listitem, center=(658,390)
					image, url='https://mynextderma.com/cdn/shop/products/7897473206632_2000x_ec7af170-3740-42b2-b4b6-c814268fde8a.webp?v=1677537785&width=600'
		paragraph
			StaticText GLENMARK
		heading Acnipop Barra Dermolimpiadora
		status, atomic
			StaticText Precio habitual
			StaticText $ 209.00 MXN
		LabelText
			StaticText Cantidad
		[408] button Reducir cantidad para Acnipop Barra Dermolimpiadora, center=(978,369), type=button
		[411] spinbutton Cantidad value='1', center=(1026,369), contenteditable=True, type=number
		[412] button Aumentar cantidad para Acnipop Barra Dermolimpiadora, center=(1074,369), type=button
		[425] button Agregar al carrito, center=(1175,441), type=submit
		[b] Iframe PayPal, center=(1175,498), title=PayPal
			RootWebArea, url='https://www.paypal.com/smart/buttons?fundingSource=paypal&style.label=pay&style.layout=horizontal&style.color=gold&style.shape=sharp&style.tagline=false&style.height=46&style.menuPlacement=below&style.disableMaxWidth=true&allowBillingPayments=true&applePaySupport=false&buttonSessionID=uid_118b798fe9_mty6nde6ntu&customerId=&clientID=AfUEYT7nO4BwZQERn9Vym5TbHAG08ptiKa9gm8OARBYgoqiAJIjllRjeIMI4g294KAH1JdTnkzubt1fr&clientMetadataID=uid_3776f3717c_mty6nde6ntu&commit=false&components.0=buttons&currency=MXN&debug=false&disableSetCookie=true&env=production&experiment.enableVenmo=false&experiment.venmoVaultWithoutPurchase=false&experiment.venmoWebEnabled=false&flow=purchase&fundingEligibility=eyJwYXlwYWwiOnsiZWxpZ2libGUiOnRydWUsInZhdWx0YWJsZSI6ZmFsc2V9LCJwYXlsYXRlciI6eyJlbGlnaWJsZSI6ZmFsc2UsInZhdWx0YWJsZSI6ZmFsc2UsInByb2R1Y3RzIjp7InBheUluMyI6eyJlbGlnaWJsZSI6ZmFsc2UsInZhcmlhbnQiOm51bGx9LCJwYXlJbjQiOnsiZWxpZ2libGUiOmZhbHNlLCJ2YXJpYW50IjpudWxsfSwicGF5bGF0ZXIiOnsiZWxpZ2libGUiOmZhbHNlLCJ2YXJpYW50IjpudWxsfX19LCJjYXJkIjp7ImVsaWdpYmxlIjp0cnVlLCJicmFuZGVkIjp0cnVlLCJpbnN0YWxsbWVudHMiOmZhbHNlLCJ2ZW5kb3JzIjp7InZpc2EiOnsiZWxpZ2libGUiOnRydWUsInZhdWx0YWJsZSI6dHJ1ZX0sIm1hc3RlcmNhcmQiOnsiZWxpZ2libGUiOnRydWUsInZhdWx0YWJsZSI6dHJ1ZX0sImFtZXgiOnsiZWxpZ2libGUiOnRydWUsInZhdWx0YWJsZSI6dHJ1ZX0sImRpc2NvdmVyIjp7ImVsaWdpYmxlIjp0cnVlLCJ2YXVsdGFibGUiOnRydWV9LCJoaXBlciI6eyJlbGlnaWJsZSI6ZmFsc2UsInZhdWx0YWJsZSI6ZmFsc2V9LCJlbG8iOnsiZWxpZ2libGUiOmZhbHNlLCJ2YXVsdGFibGUiOnRydWV9LCJqY2IiOnsiZWxpZ2libGUiOmZhbHNlLCJ2YXVsdGFibGUiOnRydWV9LCJtYWVzdHJvIjp7ImVsaWdpYmxlIjp0cnVlLCJ2YXVsdGFibGUiOnRydWV9LCJkaW5lcnMiOnsiZWxpZ2libGUiOnRydWUsInZhdWx0YWJsZSI6dHJ1ZX0sImN1cCI6eyJlbGlnaWJsZSI6dHJ1ZSwidmF1bHRhYmxlIjp0cnVlfX0sImd1ZXN0RW5hYmxlZCI6dHJ1ZX0sInZlbm1vIjp7ImVsaWdpYmxlIjpmYWxzZSwidmF1bHRhYmxlIjpmYWxzZX0sIml0YXUiOnsiZWxpZ2libGUiOmZhbHNlfSwiY3JlZGl0Ijp7ImVsaWdpYmxlIjpmYWxzZX0sImFwcGxlcGF5Ijp7ImVsaWdpYmxlIjpmYWxzZX0sInNlcGEiOnsiZWxpZ2libGUiOmZhbHNlfSwiaWRlYWwiOnsiZWxpZ2libGUiOmZhbHNlfSwiYmFuY29udGFjdCI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJnaXJvcGF5Ijp7ImVsaWdpYmxlIjpmYWxzZX0sImVwcyI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJzb2ZvcnQiOnsiZWxpZ2libGUiOmZhbHNlfSwibXliYW5rIjp7ImVsaWdpYmxlIjpmYWxzZX0sInAyNCI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJ3ZWNoYXRwYXkiOnsiZWxpZ2libGUiOmZhbHNlfSwicGF5dSI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJibGlrIjp7ImVsaWdpYmxlIjpmYWxzZX0sInRydXN0bHkiOnsiZWxpZ2libGUiOmZhbHNlfSwib3h4byI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJib2xldG8iOnsiZWxpZ2libGUiOmZhbHNlfSwiYm9sZXRvYmFuY2FyaW8iOnsiZWxpZ2libGUiOmZhbHNlfSwibWVyY2Fkb3BhZ28iOnsiZWxpZ2libGUiOmZhbHNlfSwibXVsdGliYW5jbyI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJzYXRpc3BheSI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJwYWlkeSI6eyJlbGlnaWJsZSI6ZmFsc2V9fQ&intent=capture&locale.lang=es&locale.country=ES&merchantID.0=96RB9GUJ69XJU&hasShippingCallback=false&platform=desktop&renderedButtons.0=paypal&sessionID=uid_3776f3717c_mty6nde6ntu&sdkCorrelationID=prebuild&sdkMeta=eyJ1cmwiOiJodHRwczovL3d3dy5wYXlwYWwuY29tL3Nkay9qcz9jb21wb25lbnRzPWJ1dHRvbnMmY29tbWl0PWZhbHNlJmN1cnJlbmN5PU1YTiZsb2NhbGU9ZXNfRVMmY2xpZW50LWlkPUFmVUVZVDduTzRCd1pRRVJuOVZ5bTVUYkhBRzA4cHRpS2E5Z204T0FSQllnb3FpQUpJamxsUmplSU1JNGcyOTRLQUgxSmRUbmt6dWJ0MWZyJm1lcmNoYW50LWlkPTk2UkI5R1VKNjlYSlUmaW50ZW50PWNhcHR1cmUiLCJhdHRycyI6eyJkYXRhLXVpZCI6InVpZF9obGN3bnp0amttaW1ucnVndmRpb256c2VtY2FzdmQifX0&sdkVersion=5.0.465&storageID=uid_3f28f0b013_mty6nde6ntu&supportedNativeBrowser=false&supportsPopups=true&vault=false'
				main PayPal
					link PayPal
						StaticText Pagar con
						[b13] image, center=(1216,498), url='data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTAxcHgiIGhlaWdodD0iMzIiIHZpZXdCb3g9IjAgMCAxMDEgMzIiIHByZXNlcnZlQXNwZWN0UmF0aW89InhNaW5ZTWluIG1lZXQiIHhtbG5zPSJodHRwOiYjeDJGOyYjeDJGO3d3dy53My5vcmcmI3gyRjsyMDAwJiN4MkY7c3ZnIj48cGF0aCBmaWxsPSIjMDAzMDg3IiBkPSJNIDEyLjIzNyAyLjggTCA0LjQzNyAyLjggQyAzLjkzNyAyLjggMy40MzcgMy4yIDMuMzM3IDMuNyBMIDAuMjM3IDIzLjcgQyAwLjEzNyAyNC4xIDAuNDM3IDI0LjQgMC44MzcgMjQuNCBMIDQuNTM3IDI0LjQgQyA1LjAzNyAyNC40IDUuNTM3IDI0IDUuNjM3IDIzLjUgTCA2LjQzNyAxOC4xIEMgNi41MzcgMTcuNiA2LjkzNyAxNy4yIDcuNTM3IDE3LjIgTCAxMC4wMzcgMTcuMiBDIDE1LjEzNyAxNy4yIDE4LjEzNyAxNC43IDE4LjkzNyA5LjggQyAxOS4yMzcgNy43IDE4LjkzNyA2IDE3LjkzNyA0LjggQyAxNi44MzcgMy41IDE0LjgzNyAyLjggMTIuMjM3IDIuOCBaIE0gMTMuMTM3IDEwLjEgQyAxMi43MzcgMTIuOSAxMC41MzcgMTIuOSA4LjUzNyAxMi45IEwgNy4zMzcgMTIuOSBMIDguMTM3IDcuNyBDIDguMTM3IDcuNCA4LjQzNyA3LjIgOC43MzcgNy4yIEwgOS4yMzcgNy4yIEMgMTAuNjM3IDcuMiAxMS45MzcgNy4yIDEyLjYzNyA4IEMgMTMuMTM3IDguNCAxMy4zMzcgOS4xIDEzLjEzNyAxMC4xIFoiPjwvcGF0aD48cGF0aCBmaWxsPSIjMDAzMDg3IiBkPSJNIDM1LjQzNyAxMCBMIDMxLjczNyAxMCBDIDMxLjQzNyAxMCAzMS4xMzcgMTAuMiAzMS4xMzcgMTAuNSBMIDMwLjkzNyAxMS41IEwgMzAuNjM3IDExLjEgQyAyOS44MzcgOS45IDI4LjAzNyA5LjUgMjYuMjM3IDkuNSBDIDIyLjEzNyA5LjUgMTguNjM3IDEyLjYgMTcuOTM3IDE3IEMgMTcuNTM3IDE5LjIgMTguMDM3IDIxLjMgMTkuMzM3IDIyLjcgQyAyMC40MzcgMjQgMjIuMTM3IDI0LjYgMjQuMDM3IDI0LjYgQyAyNy4zMzcgMjQuNiAyOS4yMzcgMjIuNSAyOS4yMzcgMjIuNSBMIDI5LjAzNyAyMy41IEMgMjguOTM3IDIzLjkgMjkuMjM3IDI0LjMgMjkuNjM3IDI0LjMgTCAzMy4wMzcgMjQuMyBDIDMzLjUzNyAyNC4zIDM0LjAzNyAyMy45IDM0LjEzNyAyMy40IEwgMzYuMTM3IDEwLjYgQyAzNi4yMzcgMTAuNCAzNS44MzcgMTAgMzUuNDM3IDEwIFogTSAzMC4zMzcgMTcuMiBDIDI5LjkzNyAxOS4zIDI4LjMzNyAyMC44IDI2LjEzNyAyMC44IEMgMjUuMDM3IDIwLjggMjQuMjM3IDIwLjUgMjMuNjM3IDE5LjggQyAyMy4wMzcgMTkuMSAyMi44MzcgMTguMiAyMy4wMzcgMTcuMiBDIDIzLjMzNyAxNS4xIDI1LjEzNyAxMy42IDI3LjIzNyAxMy42IEMgMjguMzM3IDEzLjYgMjkuMTM3IDE0IDI5LjczNyAxNC42IEMgMzAuMjM3IDE1LjMgMzAuNDM3IDE2LjIgMzAuMzM3IDE3LjIgWiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDMwODciIGQ9Ik0gNTUuMzM3IDEwIEwgNTEuNjM3IDEwIEMgNTEuMjM3IDEwIDUwLjkzNyAxMC4yIDUwLjczNyAxMC41IEwgNDUuNTM3IDE4LjEgTCA0My4zMzcgMTAuOCBDIDQzLjIzNyAxMC4zIDQyLjczNyAxMCA0Mi4zMzcgMTAgTCAzOC42MzcgMTAgQyAzOC4yMzcgMTAgMzcuODM3IDEwLjQgMzguMDM3IDEwLjkgTCA0Mi4xMzcgMjMgTCAzOC4yMzcgMjguNCBDIDM3LjkzNyAyOC44IDM4LjIzNyAyOS40IDM4LjczNyAyOS40IEwgNDIuNDM3IDI5LjQgQyA0Mi44MzcgMjkuNCA0My4xMzcgMjkuMiA0My4zMzcgMjguOSBMIDU1LjgzNyAxMC45IEMgNTYuMTM3IDEwLjYgNTUuODM3IDEwIDU1LjMzNyAxMCBaIj48L3BhdGg+PHBhdGggZmlsbD0iIzAwOWNkZSIgZD0iTSA2Ny43MzcgMi44IEwgNTkuOTM3IDIuOCBDIDU5LjQzNyAyLjggNTguOTM3IDMuMiA1OC44MzcgMy43IEwgNTUuNzM3IDIzLjYgQyA1NS42MzcgMjQgNTUuOTM3IDI0LjMgNTYuMzM3IDI0LjMgTCA2MC4zMzcgMjQuMyBDIDYwLjczNyAyNC4zIDYxLjAzNyAyNCA2MS4wMzcgMjMuNyBMIDYxLjkzNyAxOCBDIDYyLjAzNyAxNy41IDYyLjQzNyAxNy4xIDYzLjAzNyAxNy4xIEwgNjUuNTM3IDE3LjEgQyA3MC42MzcgMTcuMSA3My42MzcgMTQuNiA3NC40MzcgOS43IEMgNzQuNzM3IDcuNiA3NC40MzcgNS45IDczLjQzNyA0LjcgQyA3Mi4yMzcgMy41IDcwLjMzNyAyLjggNjcuNzM3IDIuOCBaIE0gNjguNjM3IDEwLjEgQyA2OC4yMzcgMTIuOSA2Ni4wMzcgMTIuOSA2NC4wMzcgMTIuOSBMIDYyLjgzNyAxMi45IEwgNjMuNjM3IDcuNyBDIDYzLjYzNyA3LjQgNjMuOTM3IDcuMiA2NC4yMzcgNy4yIEwgNjQuNzM3IDcuMiBDIDY2LjEzNyA3LjIgNjcuNDM3IDcuMiA2OC4xMzcgOCBDIDY4LjYzNyA4LjQgNjguNzM3IDkuMSA2OC42MzcgMTAuMSBaIj48L3BhdGg+PHBhdGggZmlsbD0iIzAwOWNkZSIgZD0iTSA5MC45MzcgMTAgTCA4Ny4yMzcgMTAgQyA4Ni45MzcgMTAgODYuNjM3IDEwLjIgODYuNjM3IDEwLjUgTCA4Ni40MzcgMTEuNSBMIDg2LjEzNyAxMS4xIEMgODUuMzM3IDkuOSA4My41MzcgOS41IDgxLjczNyA5LjUgQyA3Ny42MzcgOS41IDc0LjEzNyAxMi42IDczLjQzNyAxNyBDIDczLjAzNyAxOS4yIDczLjUzNyAyMS4zIDc0LjgzNyAyMi43IEMgNzUuOTM3IDI0IDc3LjYzNyAyNC42IDc5LjUzNyAyNC42IEMgODIuODM3IDI0LjYgODQuNzM3IDIyLjUgODQuNzM3IDIyLjUgTCA4NC41MzcgMjMuNSBDIDg0LjQzNyAyMy45IDg0LjczNyAyNC4zIDg1LjEzNyAyNC4zIEwgODguNTM3IDI0LjMgQyA4OS4wMzcgMjQuMyA4OS41MzcgMjMuOSA4OS42MzcgMjMuNCBMIDkxLjYzNyAxMC42IEMgOTEuNjM3IDEwLjQgOTEuMzM3IDEwIDkwLjkzNyAxMCBaIE0gODUuNzM3IDE3LjIgQyA4NS4zMzcgMTkuMyA4My43MzcgMjAuOCA4MS41MzcgMjAuOCBDIDgwLjQzNyAyMC44IDc5LjYzNyAyMC41IDc5LjAzNyAxOS44IEMgNzguNDM3IDE5LjEgNzguMjM3IDE4LjIgNzguNDM3IDE3LjIgQyA3OC43MzcgMTUuMSA4MC41MzcgMTMuNiA4Mi42MzcgMTMuNiBDIDgzLjczNyAxMy42IDg0LjUzNyAxNCA4NS4xMzcgMTQuNiBDIDg1LjczNyAxNS4zIDg1LjkzNyAxNi4yIDg1LjczNyAxNy4yIFoiPjwvcGF0aD48cGF0aCBmaWxsPSIjMDA5Y2RlIiBkPSJNIDk1LjMzNyAzLjMgTCA5Mi4xMzcgMjMuNiBDIDkyLjAzNyAyNCA5Mi4zMzcgMjQuMyA5Mi43MzcgMjQuMyBMIDk1LjkzNyAyNC4zIEMgOTYuNDM3IDI0LjMgOTYuOTM3IDIzLjkgOTcuMDM3IDIzLjQgTCAxMDAuMjM3IDMuNSBDIDEwMC4zMzcgMy4xIDEwMC4wMzcgMi44IDk5LjYzNyAyLjggTCA5Ni4wMzcgMi44IEMgOTUuNjM3IDIuOCA5NS40MzcgMyA5NS4zMzcgMy4zIFoiPjwvcGF0aD48L3N2Zz4'
					[460] svg, center=(962,860)
		[437] link Más opciones de pago, center=(1175,546), url='https://mynextderma.com/products/acnipop-barra-dermolimpiadora#'
		paragraph
			StaticText AcniPop Barra Dermolimpiadora.
		heading PROPIEDADES
		paragraph
			StaticText Barra auxiliar en la limpieza profunda de la piel, reduce la grasa.
		heading APLICACIÓN
		StaticText Utilizar diariamente por la mañana/noche sobre la piel humedecida, enjuagar con abundante agua.
		group
			button Share, expanded=False
		heading You may also like
		list
			listitem
				image Cleanance Barra, url='https://mynextderma.com/cdn/shop/products/3282770019919_2_2000x_b36f40b7-9988-4440-bdd0-ca24fbad6aaa.webp?v=1681273976&width=360'
				heading Cleanance Barra
					link Cleanance Barra, url='https://mynextderma.com/products/cleanance-barra?pr_prod_strat=e5_desc&pr_rec_id=6a9f59ca4&pr_rec_pid=7756276302056&pr_ref_pid=7756280234216&pr_seq=uniform'
				StaticText Precio habitual
				StaticText $ 170.00 MXN
			listitem
				image Aderma barra, url='https://mynextderma.com/cdn/shop/products/Adermabarra.webp?v=1677540357&width=360'
				heading Aderma Barra
					link Aderma Barra, url='https://mynextderma.com/products/aderma-barra?pr_prod_strat=e5_desc&pr_rec_id=6a9f59ca4&pr_rec_pid=7756291277032&pr_ref_pid=7756280234216&pr_seq=uniform'
				StaticText Precio habitual
				StaticText $ 190.00 MXN
			listitem
				image Normaderm Barra limpiadora facial 70g, url='https://mynextderma.com/cdn/shop/products/7899706150781.webp?v=1681939152&width=360'
				heading Normaderm Barra limpiadora facial 70g
					link Normaderm Barra limpiadora facial 70g, url='https://mynextderma.com/products/normaderm-pain?pr_prod_strat=e5_desc&pr_rec_id=6a9f59ca4&pr_rec_pid=7756303368424&pr_ref_pid=7756280234216&pr_seq=uniform'
				StaticText Precio habitual
				StaticText $ 215.00 MXN
			listitem
				image Lactibon Barra 120gr, url='https://mynextderma.com/cdn/shop/products/7703281004325.webp?v=1681875048&width=360'
				StaticText Oferta
				heading Lactibon Barra 120gr Oferta
					link Lactibon Barra 120gr Oferta, url='https://mynextderma.com/products/lactibon-barra?pr_prod_strat=e5_desc&pr_rec_id=6a9f59ca4&pr_rec_pid=7756284559592&pr_ref_pid=7756280234216&pr_seq=uniform'
				StaticText Precio habitual
				deletion
					StaticText $ 408.00 MXN
				StaticText Precio de oferta
				StaticText $ 373.00 MXN
	contentinfo
		heading ¡Descarga My Nextderma y hablemos de tu piel!
		paragraph
			StaticText Obtén una consulta con los especialistas de los influencers a solo un click de distancia
		heading Siguenos en redes sociales
		list
			listitem
				link Facebook, url='https://www.facebook.com/MyNextDerma'
			listitem
				link Instagram, url='https://www.instagram.com/mynextderma/'
			listitem
				link YouTube, url='https://www.youtube.com/c/MyNextDerma'
			listitem
				link TikTok, url='https://www.tiktok.com/@mynextderma'
		heading Sobre nosotros
		list
			listitem
				link Contacto, url='https://linktr.ee/mynextderma'
			listitem
				link Blogs, url='https://mynextderma.com/blogs/noticias'
			listitem
				link Política de Privacidad, url='https://mynextderma.com/pages/politica-de-privacidad'
			listitem
				link Descargar My NextDerma, url='https://mynextderma.com/pages/descargar'
		heading País/región
		button MXN $ | México, expanded=False
		StaticText Formas de pago
		list
			listitem
				image PayPal
		StaticText © 2024,
		link mynextderma, url='https://mynextderma.com/'
		link Derechos Reservados, url='https://es.shopify.com/?utm_campaign=poweredby&utm_medium=shopify&utm_source=onlinestore'
		list
			listitem
				StaticText ·
				link Política de privacidad, url='https://mynextderma.com/policies/privacy-policy'
	[752] button Ventana de chat, center=(52,1029), expanded=True
		image
		StaticText 1
```
</details>

**Reasoning for action:** I selected the link for 'Acnipop Barra Dermolimpiadora' because this is the specific product the user is interested in. Clicking this link will take me to the product details page, where I can find additional information and options to add the product to the shopping cart, which is essential to completing the user's goal of exploring and purchasing skincare products easily.

**Action:** click('1209') # Click on the link for 'Acnipop Barra Dermolimpiadora' to view its details.

**Change Description:** The browser navigated to the product detail page for 'Acnipop Barra Dermolimpiadora', changing the URL to 'https://mynextderma.com/products/acnipop-barra-dermolimpiadora' and displaying specific product information such as the product name, price, and options to add it to the cart.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://mynextderma.com/products/acnipop-barra-dermolimpiadora

https://mynextderma.com/products/acnipop-barra-dermolimpiadora

**Content (before/after):** 

```
RootWebArea Acnipop Barra Dermolimpiadora - My NextDerma ✅ – mynextderma, focused, url='https://mynextderma.com/products/acnipop-barra-dermolimpiadora'
	link Ir directamente al contenido, url='https://mynextderma.com/products/acnipop-barra-dermolimpiadora#MainContent'
	list
		listitem
			[147] link Facebook, center=(417,19), url='https://www.facebook.com/MyNextDerma'
```
<details><summary>Show more</summary>

```
		listitem
			[151] link Instagram, center=(455,19), url='https://www.instagram.com/mynextderma/'
		listitem
			[155] link YouTube, center=(493,19), url='https://www.youtube.com/c/MyNextDerma'
		listitem
			[159] link TikTok, center=(531,19), url='https://www.tiktok.com/@mynextderma'
	region Anuncio
		paragraph
			StaticText Envío Gratis en ordenes mayores a $799
	banner
		[244] link mynextderma, center=(510,76), url='https://mynextderma.com/'
			image mynextderma, url='https://mynextderma.com/cdn/shop/files/Asset_3.jpg?v=1651420910&width=200'
		navigation
			list
				listitem
					[250] link Inicio, center=(668,76), url='https://mynextderma.com/'
				listitem
					[253] link Productos, center=(745,76), url='https://mynextderma.com/collections/all'
				listitem
					[256] link Descargar, center=(839,76), url='https://mynextderma.com/pages/descargar'
		heading País/región
		[269] button MXN $ | México, center=(1352,76), expanded=False, type=button
		group
			button Búsqueda, expanded=False, hasPopup='dialog'
		[305] link Carrito, center=(1492,76), url='https://mynextderma.com/cart'
		[284] svg, center=(1448,76)
	main
		region Visor de la galería
			link Ir directamente a la información del producto, url='https://mynextderma.com/products/acnipop-barra-dermolimpiadora#ProductInfo-template--16910616887528__main'
			list
				[341] listitem, center=(658,390)
					image, url='https://mynextderma.com/cdn/shop/products/7897473206632_2000x_ec7af170-3740-42b2-b4b6-c814268fde8a.webp?v=1677537785&width=600'
		paragraph
			StaticText GLENMARK
		heading Acnipop Barra Dermolimpiadora
		status, atomic
			StaticText Precio habitual
			StaticText $ 209.00 MXN
		LabelText
			StaticText Cantidad
		[408] button Reducir cantidad para Acnipop Barra Dermolimpiadora, center=(978,369), type=button
		[411] spinbutton Cantidad value='1', center=(1026,369), contenteditable=True, type=number
		[412] button Aumentar cantidad para Acnipop Barra Dermolimpiadora, center=(1074,369), type=button
		[425] button Agregar al carrito, center=(1175,441), type=submit
		[b] Iframe PayPal, center=(1175,498), title=PayPal
			RootWebArea, url='https://www.paypal.com/smart/buttons?fundingSource=paypal&style.label=pay&style.layout=horizontal&style.color=gold&style.shape=sharp&style.tagline=false&style.height=46&style.menuPlacement=below&style.disableMaxWidth=true&allowBillingPayments=true&applePaySupport=false&buttonSessionID=uid_118b798fe9_mty6nde6ntu&customerId=&clientID=AfUEYT7nO4BwZQERn9Vym5TbHAG08ptiKa9gm8OARBYgoqiAJIjllRjeIMI4g294KAH1JdTnkzubt1fr&clientMetadataID=uid_3776f3717c_mty6nde6ntu&commit=false&components.0=buttons&currency=MXN&debug=false&disableSetCookie=true&env=production&experiment.enableVenmo=false&experiment.venmoVaultWithoutPurchase=false&experiment.venmoWebEnabled=false&flow=purchase&fundingEligibility=eyJwYXlwYWwiOnsiZWxpZ2libGUiOnRydWUsInZhdWx0YWJsZSI6ZmFsc2V9LCJwYXlsYXRlciI6eyJlbGlnaWJsZSI6ZmFsc2UsInZhdWx0YWJsZSI6ZmFsc2UsInByb2R1Y3RzIjp7InBheUluMyI6eyJlbGlnaWJsZSI6ZmFsc2UsInZhcmlhbnQiOm51bGx9LCJwYXlJbjQiOnsiZWxpZ2libGUiOmZhbHNlLCJ2YXJpYW50IjpudWxsfSwicGF5bGF0ZXIiOnsiZWxpZ2libGUiOmZhbHNlLCJ2YXJpYW50IjpudWxsfX19LCJjYXJkIjp7ImVsaWdpYmxlIjp0cnVlLCJicmFuZGVkIjp0cnVlLCJpbnN0YWxsbWVudHMiOmZhbHNlLCJ2ZW5kb3JzIjp7InZpc2EiOnsiZWxpZ2libGUiOnRydWUsInZhdWx0YWJsZSI6dHJ1ZX0sIm1hc3RlcmNhcmQiOnsiZWxpZ2libGUiOnRydWUsInZhdWx0YWJsZSI6dHJ1ZX0sImFtZXgiOnsiZWxpZ2libGUiOnRydWUsInZhdWx0YWJsZSI6dHJ1ZX0sImRpc2NvdmVyIjp7ImVsaWdpYmxlIjp0cnVlLCJ2YXVsdGFibGUiOnRydWV9LCJoaXBlciI6eyJlbGlnaWJsZSI6ZmFsc2UsInZhdWx0YWJsZSI6ZmFsc2V9LCJlbG8iOnsiZWxpZ2libGUiOmZhbHNlLCJ2YXVsdGFibGUiOnRydWV9LCJqY2IiOnsiZWxpZ2libGUiOmZhbHNlLCJ2YXVsdGFibGUiOnRydWV9LCJtYWVzdHJvIjp7ImVsaWdpYmxlIjp0cnVlLCJ2YXVsdGFibGUiOnRydWV9LCJkaW5lcnMiOnsiZWxpZ2libGUiOnRydWUsInZhdWx0YWJsZSI6dHJ1ZX0sImN1cCI6eyJlbGlnaWJsZSI6dHJ1ZSwidmF1bHRhYmxlIjp0cnVlfX0sImd1ZXN0RW5hYmxlZCI6dHJ1ZX0sInZlbm1vIjp7ImVsaWdpYmxlIjpmYWxzZSwidmF1bHRhYmxlIjpmYWxzZX0sIml0YXUiOnsiZWxpZ2libGUiOmZhbHNlfSwiY3JlZGl0Ijp7ImVsaWdpYmxlIjpmYWxzZX0sImFwcGxlcGF5Ijp7ImVsaWdpYmxlIjpmYWxzZX0sInNlcGEiOnsiZWxpZ2libGUiOmZhbHNlfSwiaWRlYWwiOnsiZWxpZ2libGUiOmZhbHNlfSwiYmFuY29udGFjdCI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJnaXJvcGF5Ijp7ImVsaWdpYmxlIjpmYWxzZX0sImVwcyI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJzb2ZvcnQiOnsiZWxpZ2libGUiOmZhbHNlfSwibXliYW5rIjp7ImVsaWdpYmxlIjpmYWxzZX0sInAyNCI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJ3ZWNoYXRwYXkiOnsiZWxpZ2libGUiOmZhbHNlfSwicGF5dSI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJibGlrIjp7ImVsaWdpYmxlIjpmYWxzZX0sInRydXN0bHkiOnsiZWxpZ2libGUiOmZhbHNlfSwib3h4byI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJib2xldG8iOnsiZWxpZ2libGUiOmZhbHNlfSwiYm9sZXRvYmFuY2FyaW8iOnsiZWxpZ2libGUiOmZhbHNlfSwibWVyY2Fkb3BhZ28iOnsiZWxpZ2libGUiOmZhbHNlfSwibXVsdGliYW5jbyI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJzYXRpc3BheSI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJwYWlkeSI6eyJlbGlnaWJsZSI6ZmFsc2V9fQ&intent=capture&locale.lang=es&locale.country=ES&merchantID.0=96RB9GUJ69XJU&hasShippingCallback=false&platform=desktop&renderedButtons.0=paypal&sessionID=uid_3776f3717c_mty6nde6ntu&sdkCorrelationID=prebuild&sdkMeta=eyJ1cmwiOiJodHRwczovL3d3dy5wYXlwYWwuY29tL3Nkay9qcz9jb21wb25lbnRzPWJ1dHRvbnMmY29tbWl0PWZhbHNlJmN1cnJlbmN5PU1YTiZsb2NhbGU9ZXNfRVMmY2xpZW50LWlkPUFmVUVZVDduTzRCd1pRRVJuOVZ5bTVUYkhBRzA4cHRpS2E5Z204T0FSQllnb3FpQUpJamxsUmplSU1JNGcyOTRLQUgxSmRUbmt6dWJ0MWZyJm1lcmNoYW50LWlkPTk2UkI5R1VKNjlYSlUmaW50ZW50PWNhcHR1cmUiLCJhdHRycyI6eyJkYXRhLXVpZCI6InVpZF9obGN3bnp0amttaW1ucnVndmRpb256c2VtY2FzdmQifX0&sdkVersion=5.0.465&storageID=uid_3f28f0b013_mty6nde6ntu&supportedNativeBrowser=false&supportsPopups=true&vault=false'
				main PayPal
					link PayPal
						StaticText Pagar con
						[b13] image, center=(1216,498), url='data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTAxcHgiIGhlaWdodD0iMzIiIHZpZXdCb3g9IjAgMCAxMDEgMzIiIHByZXNlcnZlQXNwZWN0UmF0aW89InhNaW5ZTWluIG1lZXQiIHhtbG5zPSJodHRwOiYjeDJGOyYjeDJGO3d3dy53My5vcmcmI3gyRjsyMDAwJiN4MkY7c3ZnIj48cGF0aCBmaWxsPSIjMDAzMDg3IiBkPSJNIDEyLjIzNyAyLjggTCA0LjQzNyAyLjggQyAzLjkzNyAyLjggMy40MzcgMy4yIDMuMzM3IDMuNyBMIDAuMjM3IDIzLjcgQyAwLjEzNyAyNC4xIDAuNDM3IDI0LjQgMC44MzcgMjQuNCBMIDQuNTM3IDI0LjQgQyA1LjAzNyAyNC40IDUuNTM3IDI0IDUuNjM3IDIzLjUgTCA2LjQzNyAxOC4xIEMgNi41MzcgMTcuNiA2LjkzNyAxNy4yIDcuNTM3IDE3LjIgTCAxMC4wMzcgMTcuMiBDIDE1LjEzNyAxNy4yIDE4LjEzNyAxNC43IDE4LjkzNyA5LjggQyAxOS4yMzcgNy43IDE4LjkzNyA2IDE3LjkzNyA0LjggQyAxNi44MzcgMy41IDE0LjgzNyAyLjggMTIuMjM3IDIuOCBaIE0gMTMuMTM3IDEwLjEgQyAxMi43MzcgMTIuOSAxMC41MzcgMTIuOSA4LjUzNyAxMi45IEwgNy4zMzcgMTIuOSBMIDguMTM3IDcuNyBDIDguMTM3IDcuNCA4LjQzNyA3LjIgOC43MzcgNy4yIEwgOS4yMzcgNy4yIEMgMTAuNjM3IDcuMiAxMS45MzcgNy4yIDEyLjYzNyA4IEMgMTMuMTM3IDguNCAxMy4zMzcgOS4xIDEzLjEzNyAxMC4xIFoiPjwvcGF0aD48cGF0aCBmaWxsPSIjMDAzMDg3IiBkPSJNIDM1LjQzNyAxMCBMIDMxLjczNyAxMCBDIDMxLjQzNyAxMCAzMS4xMzcgMTAuMiAzMS4xMzcgMTAuNSBMIDMwLjkzNyAxMS41IEwgMzAuNjM3IDExLjEgQyAyOS44MzcgOS45IDI4LjAzNyA5LjUgMjYuMjM3IDkuNSBDIDIyLjEzNyA5LjUgMTguNjM3IDEyLjYgMTcuOTM3IDE3IEMgMTcuNTM3IDE5LjIgMTguMDM3IDIxLjMgMTkuMzM3IDIyLjcgQyAyMC40MzcgMjQgMjIuMTM3IDI0LjYgMjQuMDM3IDI0LjYgQyAyNy4zMzcgMjQuNiAyOS4yMzcgMjIuNSAyOS4yMzcgMjIuNSBMIDI5LjAzNyAyMy41IEMgMjguOTM3IDIzLjkgMjkuMjM3IDI0LjMgMjkuNjM3IDI0LjMgTCAzMy4wMzcgMjQuMyBDIDMzLjUzNyAyNC4zIDM0LjAzNyAyMy45IDM0LjEzNyAyMy40IEwgMzYuMTM3IDEwLjYgQyAzNi4yMzcgMTAuNCAzNS44MzcgMTAgMzUuNDM3IDEwIFogTSAzMC4zMzcgMTcuMiBDIDI5LjkzNyAxOS4zIDI4LjMzNyAyMC44IDI2LjEzNyAyMC44IEMgMjUuMDM3IDIwLjggMjQuMjM3IDIwLjUgMjMuNjM3IDE5LjggQyAyMy4wMzcgMTkuMSAyMi44MzcgMTguMiAyMy4wMzcgMTcuMiBDIDIzLjMzNyAxNS4xIDI1LjEzNyAxMy42IDI3LjIzNyAxMy42IEMgMjguMzM3IDEzLjYgMjkuMTM3IDE0IDI5LjczNyAxNC42IEMgMzAuMjM3IDE1LjMgMzAuNDM3IDE2LjIgMzAuMzM3IDE3LjIgWiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDMwODciIGQ9Ik0gNTUuMzM3IDEwIEwgNTEuNjM3IDEwIEMgNTEuMjM3IDEwIDUwLjkzNyAxMC4yIDUwLjczNyAxMC41IEwgNDUuNTM3IDE4LjEgTCA0My4zMzcgMTAuOCBDIDQzLjIzNyAxMC4zIDQyLjczNyAxMCA0Mi4zMzcgMTAgTCAzOC42MzcgMTAgQyAzOC4yMzcgMTAgMzcuODM3IDEwLjQgMzguMDM3IDEwLjkgTCA0Mi4xMzcgMjMgTCAzOC4yMzcgMjguNCBDIDM3LjkzNyAyOC44IDM4LjIzNyAyOS40IDM4LjczNyAyOS40IEwgNDIuNDM3IDI5LjQgQyA0Mi44MzcgMjkuNCA0My4xMzcgMjkuMiA0My4zMzcgMjguOSBMIDU1LjgzNyAxMC45IEMgNTYuMTM3IDEwLjYgNTUuODM3IDEwIDU1LjMzNyAxMCBaIj48L3BhdGg+PHBhdGggZmlsbD0iIzAwOWNkZSIgZD0iTSA2Ny43MzcgMi44IEwgNTkuOTM3IDIuOCBDIDU5LjQzNyAyLjggNTguOTM3IDMuMiA1OC44MzcgMy43IEwgNTUuNzM3IDIzLjYgQyA1NS42MzcgMjQgNTUuOTM3IDI0LjMgNTYuMzM3IDI0LjMgTCA2MC4zMzcgMjQuMyBDIDYwLjczNyAyNC4zIDYxLjAzNyAyNCA2MS4wMzcgMjMuNyBMIDYxLjkzNyAxOCBDIDYyLjAzNyAxNy41IDYyLjQzNyAxNy4xIDYzLjAzNyAxNy4xIEwgNjUuNTM3IDE3LjEgQyA3MC42MzcgMTcuMSA3My42MzcgMTQuNiA3NC40MzcgOS43IEMgNzQuNzM3IDcuNiA3NC40MzcgNS45IDczLjQzNyA0LjcgQyA3Mi4yMzcgMy41IDcwLjMzNyAyLjggNjcuNzM3IDIuOCBaIE0gNjguNjM3IDEwLjEgQyA2OC4yMzcgMTIuOSA2Ni4wMzcgMTIuOSA2NC4wMzcgMTIuOSBMIDYyLjgzNyAxMi45IEwgNjMuNjM3IDcuNyBDIDYzLjYzNyA3LjQgNjMuOTM3IDcuMiA2NC4yMzcgNy4yIEwgNjQuNzM3IDcuMiBDIDY2LjEzNyA3LjIgNjcuNDM3IDcuMiA2OC4xMzcgOCBDIDY4LjYzNyA4LjQgNjguNzM3IDkuMSA2OC42MzcgMTAuMSBaIj48L3BhdGg+PHBhdGggZmlsbD0iIzAwOWNkZSIgZD0iTSA5MC45MzcgMTAgTCA4Ny4yMzcgMTAgQyA4Ni45MzcgMTAgODYuNjM3IDEwLjIgODYuNjM3IDEwLjUgTCA4Ni40MzcgMTEuNSBMIDg2LjEzNyAxMS4xIEMgODUuMzM3IDkuOSA4My41MzcgOS41IDgxLjczNyA5LjUgQyA3Ny42MzcgOS41IDc0LjEzNyAxMi42IDczLjQzNyAxNyBDIDczLjAzNyAxOS4yIDczLjUzNyAyMS4zIDc0LjgzNyAyMi43IEMgNzUuOTM3IDI0IDc3LjYzNyAyNC42IDc5LjUzNyAyNC42IEMgODIuODM3IDI0LjYgODQuNzM3IDIyLjUgODQuNzM3IDIyLjUgTCA4NC41MzcgMjMuNSBDIDg0LjQzNyAyMy45IDg0LjczNyAyNC4zIDg1LjEzNyAyNC4zIEwgODguNTM3IDI0LjMgQyA4OS4wMzcgMjQuMyA4OS41MzcgMjMuOSA4OS42MzcgMjMuNCBMIDkxLjYzNyAxMC42IEMgOTEuNjM3IDEwLjQgOTEuMzM3IDEwIDkwLjkzNyAxMCBaIE0gODUuNzM3IDE3LjIgQyA4NS4zMzcgMTkuMyA4My43MzcgMjAuOCA4MS41MzcgMjAuOCBDIDgwLjQzNyAyMC44IDc5LjYzNyAyMC41IDc5LjAzNyAxOS44IEMgNzguNDM3IDE5LjEgNzguMjM3IDE4LjIgNzguNDM3IDE3LjIgQyA3OC43MzcgMTUuMSA4MC41MzcgMTMuNiA4Mi42MzcgMTMuNiBDIDgzLjczNyAxMy42IDg0LjUzNyAxNCA4NS4xMzcgMTQuNiBDIDg1LjczNyAxNS4zIDg1LjkzNyAxNi4yIDg1LjczNyAxNy4yIFoiPjwvcGF0aD48cGF0aCBmaWxsPSIjMDA5Y2RlIiBkPSJNIDk1LjMzNyAzLjMgTCA5Mi4xMzcgMjMuNiBDIDkyLjAzNyAyNCA5Mi4zMzcgMjQuMyA5Mi43MzcgMjQuMyBMIDk1LjkzNyAyNC4zIEMgOTYuNDM3IDI0LjMgOTYuOTM3IDIzLjkgOTcuMDM3IDIzLjQgTCAxMDAuMjM3IDMuNSBDIDEwMC4zMzcgMy4xIDEwMC4wMzcgMi44IDk5LjYzNyAyLjggTCA5Ni4wMzcgMi44IEMgOTUuNjM3IDIuOCA5NS40MzcgMyA5NS4zMzcgMy4zIFoiPjwvcGF0aD48L3N2Zz4'
					[460] svg, center=(962,860)
		[437] link Más opciones de pago, center=(1175,546), url='https://mynextderma.com/products/acnipop-barra-dermolimpiadora#'
		paragraph
			StaticText AcniPop Barra Dermolimpiadora.
		heading PROPIEDADES
		paragraph
			StaticText Barra auxiliar en la limpieza profunda de la piel, reduce la grasa.
		heading APLICACIÓN
		StaticText Utilizar diariamente por la mañana/noche sobre la piel humedecida, enjuagar con abundante agua.
		group
			button Share, expanded=False
		heading You may also like
		list
			listitem
				image Cleanance Barra, url='https://mynextderma.com/cdn/shop/products/3282770019919_2_2000x_b36f40b7-9988-4440-bdd0-ca24fbad6aaa.webp?v=1681273976&width=360'
				heading Cleanance Barra
					link Cleanance Barra, url='https://mynextderma.com/products/cleanance-barra?pr_prod_strat=e5_desc&pr_rec_id=6a9f59ca4&pr_rec_pid=7756276302056&pr_ref_pid=7756280234216&pr_seq=uniform'
				StaticText Precio habitual
				StaticText $ 170.00 MXN
			listitem
				image Aderma barra, url='https://mynextderma.com/cdn/shop/products/Adermabarra.webp?v=1677540357&width=360'
				heading Aderma Barra
					link Aderma Barra, url='https://mynextderma.com/products/aderma-barra?pr_prod_strat=e5_desc&pr_rec_id=6a9f59ca4&pr_rec_pid=7756291277032&pr_ref_pid=7756280234216&pr_seq=uniform'
				StaticText Precio habitual
				StaticText $ 190.00 MXN
			listitem
				image Normaderm Barra limpiadora facial 70g, url='https://mynextderma.com/cdn/shop/products/7899706150781.webp?v=1681939152&width=360'
				heading Normaderm Barra limpiadora facial 70g
					link Normaderm Barra limpiadora facial 70g, url='https://mynextderma.com/products/normaderm-pain?pr_prod_strat=e5_desc&pr_rec_id=6a9f59ca4&pr_rec_pid=7756303368424&pr_ref_pid=7756280234216&pr_seq=uniform'
				StaticText Precio habitual
				StaticText $ 215.00 MXN
			listitem
				image Lactibon Barra 120gr, url='https://mynextderma.com/cdn/shop/products/7703281004325.webp?v=1681875048&width=360'
				StaticText Oferta
				heading Lactibon Barra 120gr Oferta
					link Lactibon Barra 120gr Oferta, url='https://mynextderma.com/products/lactibon-barra?pr_prod_strat=e5_desc&pr_rec_id=6a9f59ca4&pr_rec_pid=7756284559592&pr_ref_pid=7756280234216&pr_seq=uniform'
				StaticText Precio habitual
				deletion
					StaticText $ 408.00 MXN
				StaticText Precio de oferta
				StaticText $ 373.00 MXN
	contentinfo
		heading ¡Descarga My Nextderma y hablemos de tu piel!
		paragraph
			StaticText Obtén una consulta con los especialistas de los influencers a solo un click de distancia
		heading Siguenos en redes sociales
		list
			listitem
				link Facebook, url='https://www.facebook.com/MyNextDerma'
			listitem
				link Instagram, url='https://www.instagram.com/mynextderma/'
			listitem
				link YouTube, url='https://www.youtube.com/c/MyNextDerma'
			listitem
				link TikTok, url='https://www.tiktok.com/@mynextderma'
		heading Sobre nosotros
		list
			listitem
				link Contacto, url='https://linktr.ee/mynextderma'
			listitem
				link Blogs, url='https://mynextderma.com/blogs/noticias'
			listitem
				link Política de Privacidad, url='https://mynextderma.com/pages/politica-de-privacidad'
			listitem
				link Descargar My NextDerma, url='https://mynextderma.com/pages/descargar'
		heading País/región
		button MXN $ | México, expanded=False
		StaticText Formas de pago
		list
			listitem
				image PayPal
		StaticText © 2024,
		link mynextderma, url='https://mynextderma.com/'
		link Derechos Reservados, url='https://es.shopify.com/?utm_campaign=poweredby&utm_medium=shopify&utm_source=onlinestore'
		list
			listitem
				StaticText ·
				link Política de privacidad, url='https://mynextderma.com/policies/privacy-policy'
	[752] button Ventana de chat, center=(52,1029), expanded=True
		image
		StaticText 1
```
</details>



```
RootWebArea Acnipop Barra Dermolimpiadora - My NextDerma ✅ – mynextderma, focused, url='https://mynextderma.com/products/acnipop-barra-dermolimpiadora'
	link Ir directamente al contenido, url='https://mynextderma.com/products/acnipop-barra-dermolimpiadora#MainContent'
	list
		listitem
			[147] link Facebook, center=(417,19), url='https://www.facebook.com/MyNextDerma'
```
<details><summary>Show more</summary>

```
		listitem
			[151] link Instagram, center=(455,19), url='https://www.instagram.com/mynextderma/'
		listitem
			[155] link YouTube, center=(493,19), url='https://www.youtube.com/c/MyNextDerma'
		listitem
			[159] link TikTok, center=(531,19), url='https://www.tiktok.com/@mynextderma'
	region Anuncio
		paragraph
			StaticText Envío Gratis en ordenes mayores a $799
	banner
		[244] link mynextderma, center=(510,76), url='https://mynextderma.com/'
			image mynextderma, url='https://mynextderma.com/cdn/shop/files/Asset_3.jpg?v=1651420910&width=200'
		navigation
			list
				listitem
					[250] link Inicio, center=(668,76), url='https://mynextderma.com/'
				listitem
					[253] link Productos, center=(745,76), url='https://mynextderma.com/collections/all'
				listitem
					[256] link Descargar, center=(839,76), url='https://mynextderma.com/pages/descargar'
		heading País/región
		[269] button MXN $ | México, center=(1352,76), expanded=False, type=button
		group
			button Búsqueda, expanded=False, hasPopup='dialog'
		[305] link Carrito 1 artículo, center=(1492,76), inner_text=Carrito
1
1 artículo, url='https://mynextderma.com/cart'
		[284] svg, center=(1448,76)
	dialog Artículo agregado a tu carrito, focused, modal=True
		heading Artículo agregado a tu carrito
		[313] button Cerrar, center=(1492,141), type=button
		image, url='https://mynextderma.com/cdn/shop/products/7897473206632_2000x_ec7af170-3740-42b2-b4b6-c814268fde8a.webp?v=1677537785&width=140'
		[460] svg, center=(962,860)
		heading Acnipop Barra Dermolimpiadora
		[317] link Ver carrito (1), center=(1336,324), url='https://mynextderma.com/cart'
		[319] button Pagar pedido, center=(1336,380)
		[320] button Seguir comprando, center=(1336,424), type=button
	main
		region Visor de la galería
			link Ir directamente a la información del producto, url='https://mynextderma.com/products/acnipop-barra-dermolimpiadora#ProductInfo-template--16910616887528__main'
			list
				[341] listitem, center=(658,390)
					image, url='https://mynextderma.com/cdn/shop/products/7897473206632_2000x_ec7af170-3740-42b2-b4b6-c814268fde8a.webp?v=1677537785&width=600'
		paragraph
			StaticText GLENMARK
		heading Acnipop Barra Dermolimpiadora
		status, atomic
			StaticText Precio habitual
			StaticText $ 209.00 MXN
		LabelText
			StaticText Cantidad
			StaticText (
			StaticText 1
			StaticText en el carrito)
		[408] button Reducir cantidad para Acnipop Barra Dermolimpiadora, center=(978,369), type=button
		[411] spinbutton Cantidad (1 en el carrito) value='1', center=(1026,369), contenteditable=True, type=number
		[412] button Aumentar cantidad para Acnipop Barra Dermolimpiadora, center=(1074,369), type=button
		button Agregar al carrito
		[b] Iframe PayPal, center=(1175,498), title=PayPal
			RootWebArea, url='https://www.paypal.com/smart/buttons?fundingSource=paypal&style.label=pay&style.layout=horizontal&style.color=gold&style.shape=sharp&style.tagline=false&style.height=46&style.menuPlacement=below&style.disableMaxWidth=true&allowBillingPayments=true&applePaySupport=false&buttonSessionID=uid_118b798fe9_mty6nde6ntu&customerId=&clientID=AfUEYT7nO4BwZQERn9Vym5TbHAG08ptiKa9gm8OARBYgoqiAJIjllRjeIMI4g294KAH1JdTnkzubt1fr&clientMetadataID=uid_3776f3717c_mty6nde6ntu&commit=false&components.0=buttons&currency=MXN&debug=false&disableSetCookie=true&env=production&experiment.enableVenmo=false&experiment.venmoVaultWithoutPurchase=false&experiment.venmoWebEnabled=false&flow=purchase&fundingEligibility=eyJwYXlwYWwiOnsiZWxpZ2libGUiOnRydWUsInZhdWx0YWJsZSI6ZmFsc2V9LCJwYXlsYXRlciI6eyJlbGlnaWJsZSI6ZmFsc2UsInZhdWx0YWJsZSI6ZmFsc2UsInByb2R1Y3RzIjp7InBheUluMyI6eyJlbGlnaWJsZSI6ZmFsc2UsInZhcmlhbnQiOm51bGx9LCJwYXlJbjQiOnsiZWxpZ2libGUiOmZhbHNlLCJ2YXJpYW50IjpudWxsfSwicGF5bGF0ZXIiOnsiZWxpZ2libGUiOmZhbHNlLCJ2YXJpYW50IjpudWxsfX19LCJjYXJkIjp7ImVsaWdpYmxlIjp0cnVlLCJicmFuZGVkIjp0cnVlLCJpbnN0YWxsbWVudHMiOmZhbHNlLCJ2ZW5kb3JzIjp7InZpc2EiOnsiZWxpZ2libGUiOnRydWUsInZhdWx0YWJsZSI6dHJ1ZX0sIm1hc3RlcmNhcmQiOnsiZWxpZ2libGUiOnRydWUsInZhdWx0YWJsZSI6dHJ1ZX0sImFtZXgiOnsiZWxpZ2libGUiOnRydWUsInZhdWx0YWJsZSI6dHJ1ZX0sImRpc2NvdmVyIjp7ImVsaWdpYmxlIjp0cnVlLCJ2YXVsdGFibGUiOnRydWV9LCJoaXBlciI6eyJlbGlnaWJsZSI6ZmFsc2UsInZhdWx0YWJsZSI6ZmFsc2V9LCJlbG8iOnsiZWxpZ2libGUiOmZhbHNlLCJ2YXVsdGFibGUiOnRydWV9LCJqY2IiOnsiZWxpZ2libGUiOmZhbHNlLCJ2YXVsdGFibGUiOnRydWV9LCJtYWVzdHJvIjp7ImVsaWdpYmxlIjp0cnVlLCJ2YXVsdGFibGUiOnRydWV9LCJkaW5lcnMiOnsiZWxpZ2libGUiOnRydWUsInZhdWx0YWJsZSI6dHJ1ZX0sImN1cCI6eyJlbGlnaWJsZSI6dHJ1ZSwidmF1bHRhYmxlIjp0cnVlfX0sImd1ZXN0RW5hYmxlZCI6dHJ1ZX0sInZlbm1vIjp7ImVsaWdpYmxlIjpmYWxzZSwidmF1bHRhYmxlIjpmYWxzZX0sIml0YXUiOnsiZWxpZ2libGUiOmZhbHNlfSwiY3JlZGl0Ijp7ImVsaWdpYmxlIjpmYWxzZX0sImFwcGxlcGF5Ijp7ImVsaWdpYmxlIjpmYWxzZX0sInNlcGEiOnsiZWxpZ2libGUiOmZhbHNlfSwiaWRlYWwiOnsiZWxpZ2libGUiOmZhbHNlfSwiYmFuY29udGFjdCI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJnaXJvcGF5Ijp7ImVsaWdpYmxlIjpmYWxzZX0sImVwcyI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJzb2ZvcnQiOnsiZWxpZ2libGUiOmZhbHNlfSwibXliYW5rIjp7ImVsaWdpYmxlIjpmYWxzZX0sInAyNCI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJ3ZWNoYXRwYXkiOnsiZWxpZ2libGUiOmZhbHNlfSwicGF5dSI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJibGlrIjp7ImVsaWdpYmxlIjpmYWxzZX0sInRydXN0bHkiOnsiZWxpZ2libGUiOmZhbHNlfSwib3h4byI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJib2xldG8iOnsiZWxpZ2libGUiOmZhbHNlfSwiYm9sZXRvYmFuY2FyaW8iOnsiZWxpZ2libGUiOmZhbHNlfSwibWVyY2Fkb3BhZ28iOnsiZWxpZ2libGUiOmZhbHNlfSwibXVsdGliYW5jbyI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJzYXRpc3BheSI6eyJlbGlnaWJsZSI6ZmFsc2V9LCJwYWlkeSI6eyJlbGlnaWJsZSI6ZmFsc2V9fQ&intent=capture&locale.lang=es&locale.country=ES&merchantID.0=96RB9GUJ69XJU&hasShippingCallback=false&platform=desktop&renderedButtons.0=paypal&sessionID=uid_3776f3717c_mty6nde6ntu&sdkCorrelationID=prebuild&sdkMeta=eyJ1cmwiOiJodHRwczovL3d3dy5wYXlwYWwuY29tL3Nkay9qcz9jb21wb25lbnRzPWJ1dHRvbnMmY29tbWl0PWZhbHNlJmN1cnJlbmN5PU1YTiZsb2NhbGU9ZXNfRVMmY2xpZW50LWlkPUFmVUVZVDduTzRCd1pRRVJuOVZ5bTVUYkhBRzA4cHRpS2E5Z204T0FSQllnb3FpQUpJamxsUmplSU1JNGcyOTRLQUgxSmRUbmt6dWJ0MWZyJm1lcmNoYW50LWlkPTk2UkI5R1VKNjlYSlUmaW50ZW50PWNhcHR1cmUiLCJhdHRycyI6eyJkYXRhLXVpZCI6InVpZF9obGN3bnp0amttaW1ucnVndmRpb256c2VtY2FzdmQifX0&sdkVersion=5.0.465&storageID=uid_3f28f0b013_mty6nde6ntu&supportedNativeBrowser=false&supportsPopups=true&vault=false'
				main PayPal
					link PayPal
						StaticText Pagar con
						[b13] image, center=(1216,498), url='data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTAxcHgiIGhlaWdodD0iMzIiIHZpZXdCb3g9IjAgMCAxMDEgMzIiIHByZXNlcnZlQXNwZWN0UmF0aW89InhNaW5ZTWluIG1lZXQiIHhtbG5zPSJodHRwOiYjeDJGOyYjeDJGO3d3dy53My5vcmcmI3gyRjsyMDAwJiN4MkY7c3ZnIj48cGF0aCBmaWxsPSIjMDAzMDg3IiBkPSJNIDEyLjIzNyAyLjggTCA0LjQzNyAyLjggQyAzLjkzNyAyLjggMy40MzcgMy4yIDMuMzM3IDMuNyBMIDAuMjM3IDIzLjcgQyAwLjEzNyAyNC4xIDAuNDM3IDI0LjQgMC44MzcgMjQuNCBMIDQuNTM3IDI0LjQgQyA1LjAzNyAyNC40IDUuNTM3IDI0IDUuNjM3IDIzLjUgTCA2LjQzNyAxOC4xIEMgNi41MzcgMTcuNiA2LjkzNyAxNy4yIDcuNTM3IDE3LjIgTCAxMC4wMzcgMTcuMiBDIDE1LjEzNyAxNy4yIDE4LjEzNyAxNC43IDE4LjkzNyA5LjggQyAxOS4yMzcgNy43IDE4LjkzNyA2IDE3LjkzNyA0LjggQyAxNi44MzcgMy41IDE0LjgzNyAyLjggMTIuMjM3IDIuOCBaIE0gMTMuMTM3IDEwLjEgQyAxMi43MzcgMTIuOSAxMC41MzcgMTIuOSA4LjUzNyAxMi45IEwgNy4zMzcgMTIuOSBMIDguMTM3IDcuNyBDIDguMTM3IDcuNCA4LjQzNyA3LjIgOC43MzcgNy4yIEwgOS4yMzcgNy4yIEMgMTAuNjM3IDcuMiAxMS45MzcgNy4yIDEyLjYzNyA4IEMgMTMuMTM3IDguNCAxMy4zMzcgOS4xIDEzLjEzNyAxMC4xIFoiPjwvcGF0aD48cGF0aCBmaWxsPSIjMDAzMDg3IiBkPSJNIDM1LjQzNyAxMCBMIDMxLjczNyAxMCBDIDMxLjQzNyAxMCAzMS4xMzcgMTAuMiAzMS4xMzcgMTAuNSBMIDMwLjkzNyAxMS41IEwgMzAuNjM3IDExLjEgQyAyOS44MzcgOS45IDI4LjAzNyA5LjUgMjYuMjM3IDkuNSBDIDIyLjEzNyA5LjUgMTguNjM3IDEyLjYgMTcuOTM3IDE3IEMgMTcuNTM3IDE5LjIgMTguMDM3IDIxLjMgMTkuMzM3IDIyLjcgQyAyMC40MzcgMjQgMjIuMTM3IDI0LjYgMjQuMDM3IDI0LjYgQyAyNy4zMzcgMjQuNiAyOS4yMzcgMjIuNSAyOS4yMzcgMjIuNSBMIDI5LjAzNyAyMy41IEMgMjguOTM3IDIzLjkgMjkuMjM3IDI0LjMgMjkuNjM3IDI0LjMgTCAzMy4wMzcgMjQuMyBDIDMzLjUzNyAyNC4zIDM0LjAzNyAyMy45IDM0LjEzNyAyMy40IEwgMzYuMTM3IDEwLjYgQyAzNi4yMzcgMTAuNCAzNS44MzcgMTAgMzUuNDM3IDEwIFogTSAzMC4zMzcgMTcuMiBDIDI5LjkzNyAxOS4zIDI4LjMzNyAyMC44IDI2LjEzNyAyMC44IEMgMjUuMDM3IDIwLjggMjQuMjM3IDIwLjUgMjMuNjM3IDE5LjggQyAyMy4wMzcgMTkuMSAyMi44MzcgMTguMiAyMy4wMzcgMTcuMiBDIDIzLjMzNyAxNS4xIDI1LjEzNyAxMy42IDI3LjIzNyAxMy42IEMgMjguMzM3IDEzLjYgMjkuMTM3IDE0IDI5LjczNyAxNC42IEMgMzAuMjM3IDE1LjMgMzAuNDM3IDE2LjIgMzAuMzM3IDE3LjIgWiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDMwODciIGQ9Ik0gNTUuMzM3IDEwIEwgNTEuNjM3IDEwIEMgNTEuMjM3IDEwIDUwLjkzNyAxMC4yIDUwLjczNyAxMC41IEwgNDUuNTM3IDE4LjEgTCA0My4zMzcgMTAuOCBDIDQzLjIzNyAxMC4zIDQyLjczNyAxMCA0Mi4zMzcgMTAgTCAzOC42MzcgMTAgQyAzOC4yMzcgMTAgMzcuODM3IDEwLjQgMzguMDM3IDEwLjkgTCA0Mi4xMzcgMjMgTCAzOC4yMzcgMjguNCBDIDM3LjkzNyAyOC44IDM4LjIzNyAyOS40IDM4LjczNyAyOS40IEwgNDIuNDM3IDI5LjQgQyA0Mi44MzcgMjkuNCA0My4xMzcgMjkuMiA0My4zMzcgMjguOSBMIDU1LjgzNyAxMC45IEMgNTYuMTM3IDEwLjYgNTUuODM3IDEwIDU1LjMzNyAxMCBaIj48L3BhdGg+PHBhdGggZmlsbD0iIzAwOWNkZSIgZD0iTSA2Ny43MzcgMi44IEwgNTkuOTM3IDIuOCBDIDU5LjQzNyAyLjggNTguOTM3IDMuMiA1OC44MzcgMy43IEwgNTUuNzM3IDIzLjYgQyA1NS42MzcgMjQgNTUuOTM3IDI0LjMgNTYuMzM3IDI0LjMgTCA2MC4zMzcgMjQuMyBDIDYwLjczNyAyNC4zIDYxLjAzNyAyNCA2MS4wMzcgMjMuNyBMIDYxLjkzNyAxOCBDIDYyLjAzNyAxNy41IDYyLjQzNyAxNy4xIDYzLjAzNyAxNy4xIEwgNjUuNTM3IDE3LjEgQyA3MC42MzcgMTcuMSA3My42MzcgMTQuNiA3NC40MzcgOS43IEMgNzQuNzM3IDcuNiA3NC40MzcgNS45IDczLjQzNyA0LjcgQyA3Mi4yMzcgMy41IDcwLjMzNyAyLjggNjcuNzM3IDIuOCBaIE0gNjguNjM3IDEwLjEgQyA2OC4yMzcgMTIuOSA2Ni4wMzcgMTIuOSA2NC4wMzcgMTIuOSBMIDYyLjgzNyAxMi45IEwgNjMuNjM3IDcuNyBDIDYzLjYzNyA3LjQgNjMuOTM3IDcuMiA2NC4yMzcgNy4yIEwgNjQuNzM3IDcuMiBDIDY2LjEzNyA3LjIgNjcuNDM3IDcuMiA2OC4xMzcgOCBDIDY4LjYzNyA4LjQgNjguNzM3IDkuMSA2OC42MzcgMTAuMSBaIj48L3BhdGg+PHBhdGggZmlsbD0iIzAwOWNkZSIgZD0iTSA5MC45MzcgMTAgTCA4Ny4yMzcgMTAgQyA4Ni45MzcgMTAgODYuNjM3IDEwLjIgODYuNjM3IDEwLjUgTCA4Ni40MzcgMTEuNSBMIDg2LjEzNyAxMS4xIEMgODUuMzM3IDkuOSA4My41MzcgOS41IDgxLjczNyA5LjUgQyA3Ny42MzcgOS41IDc0LjEzNyAxMi42IDczLjQzNyAxNyBDIDczLjAzNyAxOS4yIDczLjUzNyAyMS4zIDc0LjgzNyAyMi43IEMgNzUuOTM3IDI0IDc3LjYzNyAyNC42IDc5LjUzNyAyNC42IEMgODIuODM3IDI0LjYgODQuNzM3IDIyLjUgODQuNzM3IDIyLjUgTCA4NC41MzcgMjMuNSBDIDg0LjQzNyAyMy45IDg0LjczNyAyNC4zIDg1LjEzNyAyNC4zIEwgODguNTM3IDI0LjMgQyA4OS4wMzcgMjQuMyA4OS41MzcgMjMuOSA4OS42MzcgMjMuNCBMIDkxLjYzNyAxMC42IEMgOTEuNjM3IDEwLjQgOTEuMzM3IDEwIDkwLjkzNyAxMCBaIE0gODUuNzM3IDE3LjIgQyA4NS4zMzcgMTkuMyA4My43MzcgMjAuOCA4MS41MzcgMjAuOCBDIDgwLjQzNyAyMC44IDc5LjYzNyAyMC41IDc5LjAzNyAxOS44IEMgNzguNDM3IDE5LjEgNzguMjM3IDE4LjIgNzguNDM3IDE3LjIgQyA3OC43MzcgMTUuMSA4MC41MzcgMTMuNiA4Mi42MzcgMTMuNiBDIDgzLjczNyAxMy42IDg0LjUzNyAxNCA4NS4xMzcgMTQuNiBDIDg1LjczNyAxNS4zIDg1LjkzNyAxNi4yIDg1LjczNyAxNy4yIFoiPjwvcGF0aD48cGF0aCBmaWxsPSIjMDA5Y2RlIiBkPSJNIDk1LjMzNyAzLjMgTCA5Mi4xMzcgMjMuNiBDIDkyLjAzNyAyNCA5Mi4zMzcgMjQuMyA5Mi43MzcgMjQuMyBMIDk1LjkzNyAyNC4zIEMgOTYuNDM3IDI0LjMgOTYuOTM3IDIzLjkgOTcuMDM3IDIzLjQgTCAxMDAuMjM3IDMuNSBDIDEwMC4zMzcgMy4xIDEwMC4wMzcgMi44IDk5LjYzNyAyLjggTCA5Ni4wMzcgMi44IEMgOTUuNjM3IDIuOCA5NS40MzcgMyA5NS4zMzcgMy4zIFoiPjwvcGF0aD48L3N2Zz4'
		[437] link Más opciones de pago, center=(1175,546), url='https://mynextderma.com/products/acnipop-barra-dermolimpiadora#'
		paragraph
			StaticText AcniPop Barra Dermolimpiadora.
		heading PROPIEDADES
		paragraph
			StaticText Barra auxiliar en la limpieza profunda de la piel, reduce la grasa.
		heading APLICACIÓN
		StaticText Utilizar diariamente por la mañana/noche sobre la piel humedecida, enjuagar con abundante agua.
		group
			button Share, expanded=False
		heading You may also like
		list
			listitem
				image Cleanance Barra, url='https://mynextderma.com/cdn/shop/products/3282770019919_2_2000x_b36f40b7-9988-4440-bdd0-ca24fbad6aaa.webp?v=1681273976&width=360'
				heading Cleanance Barra
					link Cleanance Barra, url='https://mynextderma.com/products/cleanance-barra?pr_prod_strat=e5_desc&pr_rec_id=6a9f59ca4&pr_rec_pid=7756276302056&pr_ref_pid=7756280234216&pr_seq=uniform'
				StaticText Precio habitual
				StaticText $ 170.00 MXN
			listitem
				image Aderma barra, url='https://mynextderma.com/cdn/shop/products/Adermabarra.webp?v=1677540357&width=360'
				heading Aderma Barra
					link Aderma Barra, url='https://mynextderma.com/products/aderma-barra?pr_prod_strat=e5_desc&pr_rec_id=6a9f59ca4&pr_rec_pid=7756291277032&pr_ref_pid=7756280234216&pr_seq=uniform'
				StaticText Precio habitual
				StaticText $ 190.00 MXN
			listitem
				image Normaderm Barra limpiadora facial 70g, url='https://mynextderma.com/cdn/shop/products/7899706150781.webp?v=1681939152&width=360'
				heading Normaderm Barra limpiadora facial 70g
					link Normaderm Barra limpiadora facial 70g, url='https://mynextderma.com/products/normaderm-pain?pr_prod_strat=e5_desc&pr_rec_id=6a9f59ca4&pr_rec_pid=7756303368424&pr_ref_pid=7756280234216&pr_seq=uniform'
				StaticText Precio habitual
				StaticText $ 215.00 MXN
			listitem
				image Lactibon Barra 120gr, url='https://mynextderma.com/cdn/shop/products/7703281004325.webp?v=1681875048&width=360'
				StaticText Oferta
				heading Lactibon Barra 120gr Oferta
					link Lactibon Barra 120gr Oferta, url='https://mynextderma.com/products/lactibon-barra?pr_prod_strat=e5_desc&pr_rec_id=6a9f59ca4&pr_rec_pid=7756284559592&pr_ref_pid=7756280234216&pr_seq=uniform'
				StaticText Precio habitual
				deletion
					StaticText $ 408.00 MXN
				StaticText Precio de oferta
				StaticText $ 373.00 MXN
	contentinfo
		heading ¡Descarga My Nextderma y hablemos de tu piel!
		paragraph
			StaticText Obtén una consulta con los especialistas de los influencers a solo un click de distancia
		heading Siguenos en redes sociales
		list
			listitem
				link Facebook, url='https://www.facebook.com/MyNextDerma'
			listitem
				link Instagram, url='https://www.instagram.com/mynextderma/'
			listitem
				link YouTube, url='https://www.youtube.com/c/MyNextDerma'
			listitem
				link TikTok, url='https://www.tiktok.com/@mynextderma'
		heading Sobre nosotros
		list
			listitem
				link Contacto, url='https://linktr.ee/mynextderma'
			listitem
				link Blogs, url='https://mynextderma.com/blogs/noticias'
			listitem
				link Política de Privacidad, url='https://mynextderma.com/pages/politica-de-privacidad'
			listitem
				link Descargar My NextDerma, url='https://mynextderma.com/pages/descargar'
		heading País/región
		button MXN $ | México, expanded=False
		StaticText Formas de pago
		list
			listitem
				image PayPal
		StaticText © 2024,
		link mynextderma, url='https://mynextderma.com/'
		link Derechos Reservados, url='https://es.shopify.com/?utm_campaign=poweredby&utm_medium=shopify&utm_source=onlinestore'
		list
			listitem
				StaticText ·
				link Política de privacidad, url='https://mynextderma.com/policies/privacy-policy'
	[752] button Ventana de chat, center=(52,1029), expanded=True
		image
		StaticText 1
```
</details>

**Reasoning for action:** My reasoning for this action is that clicking the 'Agregar al carrito' button is essential to proceed with the user's task of purchasing the skincare product. This action should trigger a confirmation message indicating that the item has been successfully added to the cart, thereby meeting the user's requirement to see the cart reflect this new item. Additionally, it ensures that the user can review their shopping cart, which is the next step in their journey toward completing the purchase.

**Action:** click('425') # Click on 'Agregar al carrito' to add the product to the cart.

**Change Description:** The button to add the product 'Acnipop Barra Dermolimpiadora' to the cart was clicked, resulting in a dialog showing 'Artículo agregado a tu carrito' confirming the addition of the item, and the cart link now displays 'Carrito 1 artículo' to indicate one item has been added.

**Screenshot before:****Screenshot after:**---


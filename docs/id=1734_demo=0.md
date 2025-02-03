# Task

**User Story - Requesting Equipment Rental Quote**

As a construction project manager,
I request a rental quote for an electric scissor lift,
so that I can ensure my project is well-equipped without unnecessary delays.

**Success definition:** Given I am on the RendaloMaq website viewing the electric scissor lift options
When I click on the 'Cotizar arriendo' button for the Elevador Tijera Eléctrico 8 Metros
Then a modal dialog opens prompting me to fill in my address, select a start date, and estimate the number of rental days to request a rental quote.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://rendalomaq.com/

https://rendalomaq.com/

**Content (before/after):** 

```
RootWebArea RendaloMaq | Arriendo y Venta de Maquinaria Online, focused, url='https://rendalomaq.com/'
	navigation
		[57] link RendaloMaq RendaloMaq logo, center=(480,28), inner_text=RendaloMaq, url='https://rendalomaq.com/#'
			image RendaloMaq logo, url='https://rendalomaq.com/colorful.svg'
		LabelText
```
<details><summary>Show more</summary>

```
			StaticText Buscar maquinaria...
		[74] searchbox Buscar maquinaria..., center=(960,28), autocomplete=off, contenteditable=True, type=search
		[80] button Open user menu, center=(1576,24), expanded=False, hasPopup='menu', type=button
	banner
		navigation Top
			navigation
				[100] button Arrienda, center=(374,89), expanded=False, type=button
				[104] button Compra, center=(488,89), expanded=False, type=button
				[108] button Soluciones, center=(609,89), expanded=False, type=button
				[111] link Blog, center=(704,89), url='https://rendalomaq.com/blog'
			StaticText ¿Eres un proveedor? Arrienda o vende con nosotros
			[115] link Inscríbete ahora, center=(1544,89), url='https://rendalomaq.com/es-CL/arrendar-mi-maquinaria'
	main
		heading Arrienda, compra o vende maquinaria con RendaloMaq
		heading Cotiza en línea y comienza tu proyecto hoy
		image Una excavadora sale de un teléfono móvil, con la pantalla de cotización de RendaloMaq, url='https://rendalomaq.com/_next/image?url=%2Flanding%2Fes-CL-hero.webp&w=1920&q=75'
		image Elevadores Tijera, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F3Fo86WGLJoPRko8rjy48GF_small.png&w=1920&q=75'
		[138] div, center=(384,546), inner_text=Elevadores Tijera
		heading Elevadores Tijera
		image Brazos Articulados, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FBrazos_Articulados_small.png&w=1920&q=75'
		[145] div, center=(549,546), inner_text=Brazos Articulados
		heading Brazos Articulados
		image Movimiento de Tierra, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FiEoP8LPto9nAtbjPfStkZB_small.png&w=1920&q=75'
		[152] div, center=(713,546), inner_text=Movimiento de Tierra
		heading Movimiento de Tierra
		image Brazos Telescópicos, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FBrazos_Telescopicos_small.png&w=1920&q=75'
		[159] div, center=(878,546), inner_text=Brazos Telescópicos
		heading Brazos Telescópicos
		image Camiones, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FCamion_Tolva_20_M3_-_Sin_Operador_D1JpiOg_small.png&w=1920&q=75'
		[166] div, center=(1042,546), inner_text=Camiones
		heading Camiones
		image Manipulación de Materiales, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FaXuJ4niZyH6rXuxEfhTMXD_small.png&w=1920&q=75'
		[173] div, center=(1207,556), inner_text=Manipulación de Materiales
		heading Manipulación de Materiales
		image Equipos de Apoyo, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FmYTSrYRs2w3jwjzEGVeKY9_small.png&w=1920&q=75'
		[180] div, center=(1371,546), inner_text=Equipos de Apoyo
		heading Equipos de Apoyo
		image Elevadores Unipersonales, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FRH8Prg7L8JcfsSkRUxyana_small.png&w=1920&q=75'
		[187] div, center=(1536,556), inner_text=Elevadores Unipersonales
		heading Elevadores Unipersonales
		heading Grúas
		StaticText next
		heading Comúnmente arrendadas...
		[198] div, center=(1626,547)
		[202] button Ver más, center=(1526,691), type=button
		[213] image Elevador Tijera Eléctrico 8 Metros, center=(514,856), url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_small.png&w=1920&q=75'
		heading Elevador Tijera Eléctrico 8 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $60.000
			StaticText +
			StaticText IVA
		[217] a, center=(514,988), inner_text=Elevador Tijera Eléctrico 8 Metros
		button Cotizar compra
		[221] small, center=(626,1057), inner_text=+ IVA
		[219] span, center=(428,1056), inner_text=Arriendo diario desde
		button Cotizar arriendo
		[231] image Elevador Tijera Eléctrico 10 Metros, center=(812,856), url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FgEwtYuqhBVoCkD7ud6wjSG_small.png&w=1920&q=75'
		[234] heading Elevador Tijera Eléctrico 10 Metros, center=(812,1008)
		paragraph
			StaticText Arriendo diario desde
			StaticText $70.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		[239] small, center=(922,1057), inner_text=+ IVA
		[237] span, center=(725,1056), inner_text=Arriendo diario desde
		button Cotizar arriendo
		[249] image Brazo Articulado Eléctrico 15 Metros, center=(1108,856), url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FnWs6wimRj9zHf76GaCT3T5_small.png&w=1920&q=75'
		[252] heading Brazo Articulado Eléctrico 15 Metros, center=(1108,1008)
		paragraph
			StaticText Arriendo desde
			StaticText A cotizar
		button Cotizar compra
		[256] span, center=(1202,1052), inner_text=A cotizar
		[255] span, center=(1024,1052), inner_text=Arriendo desde
		button Cotizar arriendo
		[266] image Elevador Tijera Eléctrico 12 Metros, center=(1406,856), url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F3xXDKDHSk6bsB3JxpMTWyT_small.png&w=1920&q=75'
		[269] heading Elevador Tijera Eléctrico 12 Metros, center=(1406,1008)
		paragraph
			StaticText Arriendo diario desde
			StaticText $85.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		[274] small, center=(1516,1057), inner_text=+ IVA
		[272] span, center=(1319,1056), inner_text=Arriendo diario desde
		button Cotizar arriendo
		image Brazo Articulado Eléctrico 16 Metros, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		heading Brazo Articulado Eléctrico 16 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $210.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Brazo Articulado Eléctrico 12 Metros, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		heading Brazo Articulado Eléctrico 12 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $180.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		StaticText next
		heading Maquinaria más buscada...
		[315] div, center=(1562,952)
		button Ver más
		image Elevador Tijera Eléctrico 8 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_small.png&w=1920&q=75'
		heading Elevador Tijera Eléctrico 8 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $60.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Elevador Tijera Eléctrico 10 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FgEwtYuqhBVoCkD7ud6wjSG_small.png&w=1920&q=75'
		heading Elevador Tijera Eléctrico 10 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $70.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Elevador Tijera Eléctrico 12 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F3xXDKDHSk6bsB3JxpMTWyT_small.png&w=1920&q=75'
		heading Elevador Tijera Eléctrico 12 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $85.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Brazo Articulado Eléctrico 12 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FZi7r5rBBk8ZNApniU5D6gm_small.png&w=1920&q=75'
		heading Brazo Articulado Eléctrico 12 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $180.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Brazo Articulado 4WD Diésel 16 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FBrazos_Articulados_small.webp&w=1920&q=75'
		heading Brazo Articulado 4WD Diésel 16 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $230.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Brazo Articulado 4WD Diésel 26 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FnXbPYBPoZRTXYy8EqgPxzP_small.png&w=1920&q=75'
		heading Brazo Articulado 4WD Diésel 26 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $410.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		StaticText next
		image Dos personas de pie usando vestimenta de protección, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		heading ¿Tienes maquinaria y quieres rentabilizarla?
		paragraph
			StaticText ¡
			StaticText Arrienda más, haciendo menos
			StaticText !
		paragraph
			StaticText RendaloMaq se encarga de todo por ti, desde conseguir clientes hasta manejar garantías
			StaticText .
		button ¡Quiero ver todos los beneficios!
		heading Somos expertos en maquinaria
		heading +800
		paragraph
			StaticText clientes
		paragraph
			StaticText satisfechos
		heading +450
		paragraph
			StaticText proveedores
		paragraph
			StaticText asociados
		heading +5000
		paragraph
			StaticText máquinas
		heading Algunos de nuestros clientes
		image GTD, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Prosegur, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Agrosuper, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Finning, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Cosapi, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image SQM, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Anglo American, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Eiffage Energía, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Mineria Centinela, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Aeropuerto Santiago, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		heading Y lo que han dicho
		image, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		paragraph
			StaticText “
			StaticText Con RendaloMaq tenemos la confianza de que obtendremos el equipo que necesitamos para ejecutar los proyectos que nos piden nuestros clientes. La gestión de arriendos ha sido muy cómoda y sobre todo, muy rápida siempre.
			StaticText ”
		strong
			StaticText Olga Sandoval
		paragraph
			StaticText Jefa de Instalaciones
		paragraph
			StaticText Cordillera tecnologías gráficas
		image Cordillera tecnologías gráficas, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		paragraph
			StaticText “
			StaticText Siempre están atentos a los proyectos que podamos tener. En muchos casos, las horas perdidas al no tener un equipo se convierten en gastos, por lo que RendaloMaq nos ayuda a conseguir la máquina de manera oportuna sin incurrir en pérdidas.
			StaticText ”
		strong
			StaticText Sergio Silva
		paragraph
			StaticText Comprador Senior
		paragraph
			StaticText COSAPI Chile
		image COSAPI Chile, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
	link ¡Hablemos por WhatsApp!, url='https://api.whatsapp.com/send/?phone=56951979537&text&type=phone_number&app_absent=0'
	[553] link Whatsapp Chat link, center=(1866,1036), url='https://api.whatsapp.com/send/?phone=56951979537&text&type=phone_number&app_absent=0'
		image Whatsapp Chat link, url='https://rendalomaq.com/_next/image?url=%2Frrss%2Fwhatsapp.png&w=48&q=75'
	[552] div, center=(1768,969), inner_text=¡Hablemos por WhatsApp!
	alert, atomic
```
</details>



```
RootWebArea RendaloMaq | Arriendo y Venta de Maquinaria Online, focused, url='https://rendalomaq.com/'
	navigation
		[57] link RendaloMaq RendaloMaq logo, center=(480,28), inner_text=RendaloMaq, url='https://rendalomaq.com/#'
			image RendaloMaq logo, url='https://rendalomaq.com/colorful.svg'
		LabelText
```
<details><summary>Show more</summary>

```
			StaticText Buscar maquinaria...
		[74] searchbox Buscar maquinaria..., center=(960,28), autocomplete=off, contenteditable=True, type=search
		[80] button Open user menu, center=(1576,24), expanded=False, hasPopup='menu', type=button
	banner
		navigation Top
			navigation
				[100] button Arrienda, center=(374,89), expanded=True, focused, type=button
				navigation Catalog menu
					heading Catalog menu
					list
						[613] listitem, center=(439,178), inner_text=Elevadores Tijera
							StaticText Elevadores Tijera
						[614] listitem, center=(439,218), inner_text=Brazos Articulados
							StaticText Brazos Articulados
						[615] listitem, center=(439,258), inner_text=Movimiento de Tierra
							StaticText Movimiento de Tierra
						[616] listitem, center=(439,298), inner_text=Brazos Telescópicos
							StaticText Brazos Telescópicos
						[617] listitem, center=(439,338), inner_text=Camiones
							StaticText Camiones
						[618] listitem, center=(439,390), inner_text=Manipulación de Materiales
							StaticText Manipulación de Materiales
						[619] listitem, center=(439,442), inner_text=Equipos de Apoyo
							StaticText Equipos de Apoyo
						[620] listitem, center=(439,494), inner_text=Elevadores Unipersonales
							StaticText Elevadores Unipersonales
						[621] listitem, center=(439,546), inner_text=Grúas
							StaticText Grúas
						[622] listitem, center=(439,586), inner_text=Ver todo el catálogo
							StaticText Ver todo el catálogo
					list
						[625] listitem, center=(671,190), inner_text=Elevador Tijera Eléctrico 8 Metros
							image Elevador Tijera Eléctrico 8 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_small.png&w=1920&q=75'
							StaticText Elevador Tijera Eléctrico 8 Metros
						[629] listitem, center=(671,254), inner_text=Elevador Tijera Eléctrico 10 Metros
							image Elevador Tijera Eléctrico 10 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FgEwtYuqhBVoCkD7ud6wjSG_small.png&w=1920&q=75'
							StaticText Elevador Tijera Eléctrico 10 Metros
						[633] listitem, center=(671,318), inner_text=Elevador Tijera Eléctrico 12 Metros
							image Elevador Tijera Eléctrico 12 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F3xXDKDHSk6bsB3JxpMTWyT_small.png&w=1920&q=75'
							StaticText Elevador Tijera Eléctrico 12 Metros
						[637] listitem, center=(671,382), inner_text=Elevador Tijera Eléctrico 14 Metros
							image Elevador Tijera Eléctrico 14 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F3uRcQYRLKUxnimTMEJoYWU_small.png&w=1920&q=75'
							StaticText Elevador Tijera Eléctrico 14 Metros
						[642] listitem, center=(671,446), inner_text=Elevador Tijera 4WD Diésel 12 Metros
							image Elevador Tijera 4WD Diésel 12 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FeBPwrpNDTLMiANHrC9bYqX_small.png&w=1920&q=75'
							StaticText Elevador Tijera 4WD Diésel 12 Metros
						[647] listitem, center=(671,510), inner_text=Elevador Tijera Eléctrico 16 Metros
							image Elevador Tijera Eléctrico 16 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FRPBtrXQawHcuRTQcFCR3av_small.png&w=1920&q=75'
							StaticText Elevador Tijera Eléctrico 16 Metros
						[652] listitem, center=(671,574), inner_text=Elevador Tijera 4WD Diésel 18 Metros
							image Elevador Tijera 4WD Diésel 18 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2Ftijera_diesel_18m_small.png&w=1920&q=75'
							StaticText Elevador Tijera 4WD Diésel 18 Metros
						[657] listitem, center=(1018,190), inner_text=Elevador Tijera 4WD Diésel 15 Metros
							image Elevador Tijera 4WD Diésel 15 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FG5PzqGFesWhYfMWsLpmH3L_small.png&w=1920&q=75'
							StaticText Elevador Tijera 4WD Diésel 15 Metros
						[662] listitem, center=(1018,254), inner_text=Elevador Tijera 4WD Diésel 10 Metros
							image Elevador Tijera 4WD Diésel 10 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FRdrV8kyQgxw7LE5ZrCLZzY_small.png&w=1920&q=75'
							StaticText Elevador Tijera 4WD Diésel 10 Metros
						[667] listitem, center=(1018,318), inner_text=Elevador Tijera Eléctrico 5 Metros
							image Elevador Tijera Eléctrico 5 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FaF8hSwSp57uEhBZ2dcBtgM_small.png&w=1920&q=75'
							StaticText Elevador Tijera Eléctrico 5 Metros
						[672] listitem, center=(1018,382), inner_text=Elevador Tijera Eléctrico 18 Metros
							image Elevador Tijera Eléctrico 18 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FEPfr7oVLUxVbLxzLZPcyYa_small.png&w=1920&q=75'
							StaticText Elevador Tijera Eléctrico 18 Metros
						[677] listitem, center=(1018,446), inner_text=Elevador Tijera 4WD Diésel 14 Metros
							image Elevador Tijera 4WD Diésel 14 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FNJTbPeeTFVYKuFE8mAjnmK_small.png&w=1920&q=75'
							StaticText Elevador Tijera 4WD Diésel 14 Metros
						[682] listitem, center=(1018,510), inner_text=Elevador Tijera 4WD Diésel 16 Metros
							image Elevador Tijera 4WD Diésel 16 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F8ZeK6a9P7uLwmGLZBxPhgo_small.png&w=1920&q=75'
							StaticText Elevador Tijera 4WD Diésel 16 Metros
						[687] listitem, center=(944,562), inner_text=Ver todo
							StaticText Ver todo
					image Elevador Tijera Eléctrico 8 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_small.png&w=1920&q=75'
					[690] div, center=(1344,262), inner_text=Elevador Tijera Eléctrico 8 Metros
					heading Elevador Tijera Eléctrico 8 Metros
					image Elevador Tijera Eléctrico 10 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FgEwtYuqhBVoCkD7ud6wjSG_small.png&w=1920&q=75'
					[695] div, center=(1488,262), inner_text=Elevador Tijera Eléctrico 10 Metros
					heading Elevador Tijera Eléctrico 10 Metros
					image Elevador Tijera Eléctrico 12 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F3xXDKDHSk6bsB3JxpMTWyT_small.png&w=1920&q=75'
					[700] div, center=(1344,478), inner_text=Elevador Tijera Eléctrico 12 Metros
					heading Elevador Tijera Eléctrico 12 Metros
					image Elevador Tijera Eléctrico 14 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F3uRcQYRLKUxnimTMEJoYWU_small.png&w=1920&q=75'
					[705] div, center=(1488,478), inner_text=Elevador Tijera Eléctrico 14 Metros
					heading Elevador Tijera Eléctrico 14 Metros
				[552] div, center=(1768,969), inner_text=¡Hablemos por WhatsApp!
				[315] div, center=(1562,952)
				[274] small, center=(1516,1057), inner_text=+ IVA
				[272] span, center=(1319,1056), inner_text=Arriendo diario desde
				[256] span, center=(1202,1052), inner_text=A cotizar
				[255] span, center=(1024,1052), inner_text=Arriendo desde
				[239] small, center=(922,1057), inner_text=+ IVA
				[237] span, center=(725,1056), inner_text=Arriendo diario desde
				[221] small, center=(626,1057), inner_text=+ IVA
				[219] span, center=(428,1056), inner_text=Arriendo diario desde
				[217] a, center=(514,988), inner_text=Elevador Tijera Eléctrico 8 Metros
				[198] div, center=(1626,547)
				[104] button Compra, center=(488,89), expanded=False, type=button
				[108] button Soluciones, center=(609,89), expanded=False, type=button
				[111] link Blog, center=(704,89), url='https://rendalomaq.com/blog'
			StaticText ¿Eres un proveedor? Arrienda o vende con nosotros
			[115] link Inscríbete ahora, center=(1544,89), url='https://rendalomaq.com/es-CL/arrendar-mi-maquinaria'
	main
		heading Arrienda, compra o vende maquinaria con RendaloMaq
		heading Cotiza en línea y comienza tu proyecto hoy
		image Una excavadora sale de un teléfono móvil, con la pantalla de cotización de RendaloMaq, url='https://rendalomaq.com/_next/image?url=%2Flanding%2Fes-CL-hero.webp&w=1920&q=75'
		image Elevadores Tijera, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F3Fo86WGLJoPRko8rjy48GF_small.png&w=1920&q=75'
		heading Elevadores Tijera
		image Brazos Articulados, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FBrazos_Articulados_small.png&w=1920&q=75'
		heading Brazos Articulados
		image Movimiento de Tierra, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FiEoP8LPto9nAtbjPfStkZB_small.png&w=1920&q=75'
		heading Movimiento de Tierra
		image Brazos Telescópicos, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FBrazos_Telescopicos_small.png&w=1920&q=75'
		heading Brazos Telescópicos
		image Camiones, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FCamion_Tolva_20_M3_-_Sin_Operador_D1JpiOg_small.png&w=1920&q=75'
		heading Camiones
		image Manipulación de Materiales, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FaXuJ4niZyH6rXuxEfhTMXD_small.png&w=1920&q=75'
		heading Manipulación de Materiales
		image Equipos de Apoyo, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FmYTSrYRs2w3jwjzEGVeKY9_small.png&w=1920&q=75'
		heading Equipos de Apoyo
		image Elevadores Unipersonales, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FRH8Prg7L8JcfsSkRUxyana_small.png&w=1920&q=75'
		heading Elevadores Unipersonales
		heading Grúas
		StaticText next
		heading Comúnmente arrendadas...
		[202] button Ver más, center=(1526,691), type=button
		[213] image Elevador Tijera Eléctrico 8 Metros, center=(514,856), url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_small.png&w=1920&q=75'
		heading Elevador Tijera Eléctrico 8 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $60.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		[231] image Elevador Tijera Eléctrico 10 Metros, center=(812,856), url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FgEwtYuqhBVoCkD7ud6wjSG_small.png&w=1920&q=75'
		[234] heading Elevador Tijera Eléctrico 10 Metros, center=(812,1008)
		paragraph
			StaticText Arriendo diario desde
			StaticText $70.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		[249] image Brazo Articulado Eléctrico 15 Metros, center=(1108,856), url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FnWs6wimRj9zHf76GaCT3T5_small.png&w=1920&q=75'
		[252] heading Brazo Articulado Eléctrico 15 Metros, center=(1108,1008)
		paragraph
			StaticText Arriendo desde
			StaticText A cotizar
		button Cotizar compra
		button Cotizar arriendo
		[266] image Elevador Tijera Eléctrico 12 Metros, center=(1406,856), url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F3xXDKDHSk6bsB3JxpMTWyT_small.png&w=1920&q=75'
		[269] heading Elevador Tijera Eléctrico 12 Metros, center=(1406,1008)
		paragraph
			StaticText Arriendo diario desde
			StaticText $85.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Brazo Articulado Eléctrico 16 Metros, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		heading Brazo Articulado Eléctrico 16 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $210.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Brazo Articulado Eléctrico 12 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FZi7r5rBBk8ZNApniU5D6gm_small.png&w=1920&q=75'
		heading Brazo Articulado Eléctrico 12 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $180.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		StaticText next
		heading Maquinaria más buscada...
		button Ver más
		image Elevador Tijera Eléctrico 8 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_small.png&w=1920&q=75'
		heading Elevador Tijera Eléctrico 8 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $60.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Elevador Tijera Eléctrico 10 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FgEwtYuqhBVoCkD7ud6wjSG_small.png&w=1920&q=75'
		heading Elevador Tijera Eléctrico 10 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $70.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Elevador Tijera Eléctrico 12 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F3xXDKDHSk6bsB3JxpMTWyT_small.png&w=1920&q=75'
		heading Elevador Tijera Eléctrico 12 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $85.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Brazo Articulado Eléctrico 12 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FZi7r5rBBk8ZNApniU5D6gm_small.png&w=1920&q=75'
		heading Brazo Articulado Eléctrico 12 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $180.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Brazo Articulado 4WD Diésel 16 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FBrazos_Articulados_small.webp&w=1920&q=75'
		heading Brazo Articulado 4WD Diésel 16 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $230.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Brazo Articulado 4WD Diésel 26 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FnXbPYBPoZRTXYy8EqgPxzP_small.png&w=1920&q=75'
		heading Brazo Articulado 4WD Diésel 26 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $410.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		StaticText next
		image Dos personas de pie usando vestimenta de protección, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		heading ¿Tienes maquinaria y quieres rentabilizarla?
		paragraph
			StaticText ¡
			StaticText Arrienda más, haciendo menos
			StaticText !
		paragraph
			StaticText RendaloMaq se encarga de todo por ti, desde conseguir clientes hasta manejar garantías
			StaticText .
		button ¡Quiero ver todos los beneficios!
		heading Somos expertos en maquinaria
		heading +800
		paragraph
			StaticText clientes
		paragraph
			StaticText satisfechos
		heading +450
		paragraph
			StaticText proveedores
		paragraph
			StaticText asociados
		heading +5000
		paragraph
			StaticText máquinas
		heading Algunos de nuestros clientes
		image GTD, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Prosegur, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Agrosuper, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Finning, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Cosapi, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image SQM, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Anglo American, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Eiffage Energía, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Mineria Centinela, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Aeropuerto Santiago, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		heading Y lo que han dicho
		image, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		paragraph
			StaticText “
			StaticText Con RendaloMaq tenemos la confianza de que obtendremos el equipo que necesitamos para ejecutar los proyectos que nos piden nuestros clientes. La gestión de arriendos ha sido muy cómoda y sobre todo, muy rápida siempre.
			StaticText ”
		strong
			StaticText Olga Sandoval
		paragraph
			StaticText Jefa de Instalaciones
		paragraph
			StaticText Cordillera tecnologías gráficas
		image Cordillera tecnologías gráficas, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		paragraph
			StaticText “
			StaticText Siempre están atentos a los proyectos que podamos tener. En muchos casos, las horas perdidas al no tener un equipo se convierten en gastos, por lo que RendaloMaq nos ayuda a conseguir la máquina de manera oportuna sin incurrir en pérdidas.
			StaticText ”
		strong
			StaticText Sergio Silva
		paragraph
			StaticText Comprador Senior
		paragraph
			StaticText COSAPI Chile
		image COSAPI Chile, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
	link ¡Hablemos por WhatsApp!, url='https://api.whatsapp.com/send/?phone=56951979537&text&type=phone_number&app_absent=0'
	[553] link Whatsapp Chat link, center=(1866,1036), url='https://api.whatsapp.com/send/?phone=56951979537&text&type=phone_number&app_absent=0'
		image Whatsapp Chat link, url='https://rendalomaq.com/_next/image?url=%2Frrss%2Fwhatsapp.png&w=48&q=75'
	alert, atomic
```
</details>

**Reasoning for action:** By clicking on the 'Arrienda' button, I am navigating to the section focused on rental equipment. This is crucial because I need to access the appropriate category where electric scissor lifts are listed in order to request a rental quote for the specific model wanted. This step moves me closer to fulfilling the user's request.

**Action:** click(100) # Click on the 'Arrienda' button to explore rental options.

**Change Description:** After clicking the 'Arrienda' button, the button is now expanded and in focus, revealing a catalog menu of rental options including various types of machinery such as Elevadores Tijera, Brazos Articulados, and more, which were not visible in the initial state.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://rendalomaq.com/

https://rendalomaq.com/es-CL/category/elevador-tijera-electrico-8-metros

**Content (before/after):** 

```
RootWebArea RendaloMaq | Arriendo y Venta de Maquinaria Online, focused, url='https://rendalomaq.com/'
	navigation
		[57] link RendaloMaq RendaloMaq logo, center=(480,28), inner_text=RendaloMaq, url='https://rendalomaq.com/#'
			image RendaloMaq logo, url='https://rendalomaq.com/colorful.svg'
		LabelText
```
<details><summary>Show more</summary>

```
			StaticText Buscar maquinaria...
		[74] searchbox Buscar maquinaria..., center=(960,28), autocomplete=off, contenteditable=True, type=search
		[80] button Open user menu, center=(1576,24), expanded=False, hasPopup='menu', type=button
	banner
		navigation Top
			navigation
				[100] button Arrienda, center=(374,89), expanded=True, focused, type=button
				navigation Catalog menu
					heading Catalog menu
					list
						[613] listitem, center=(439,178), inner_text=Elevadores Tijera
							StaticText Elevadores Tijera
						[614] listitem, center=(439,218), inner_text=Brazos Articulados
							StaticText Brazos Articulados
						[615] listitem, center=(439,258), inner_text=Movimiento de Tierra
							StaticText Movimiento de Tierra
						[616] listitem, center=(439,298), inner_text=Brazos Telescópicos
							StaticText Brazos Telescópicos
						[617] listitem, center=(439,338), inner_text=Camiones
							StaticText Camiones
						[618] listitem, center=(439,390), inner_text=Manipulación de Materiales
							StaticText Manipulación de Materiales
						[619] listitem, center=(439,442), inner_text=Equipos de Apoyo
							StaticText Equipos de Apoyo
						[620] listitem, center=(439,494), inner_text=Elevadores Unipersonales
							StaticText Elevadores Unipersonales
						[621] listitem, center=(439,546), inner_text=Grúas
							StaticText Grúas
						[622] listitem, center=(439,586), inner_text=Ver todo el catálogo
							StaticText Ver todo el catálogo
					list
						[625] listitem, center=(671,190), inner_text=Elevador Tijera Eléctrico 8 Metros
							image Elevador Tijera Eléctrico 8 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_small.png&w=1920&q=75'
							StaticText Elevador Tijera Eléctrico 8 Metros
						[629] listitem, center=(671,254), inner_text=Elevador Tijera Eléctrico 10 Metros
							image Elevador Tijera Eléctrico 10 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FgEwtYuqhBVoCkD7ud6wjSG_small.png&w=1920&q=75'
							StaticText Elevador Tijera Eléctrico 10 Metros
						[633] listitem, center=(671,318), inner_text=Elevador Tijera Eléctrico 12 Metros
							image Elevador Tijera Eléctrico 12 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F3xXDKDHSk6bsB3JxpMTWyT_small.png&w=1920&q=75'
							StaticText Elevador Tijera Eléctrico 12 Metros
						[637] listitem, center=(671,382), inner_text=Elevador Tijera Eléctrico 14 Metros
							image Elevador Tijera Eléctrico 14 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F3uRcQYRLKUxnimTMEJoYWU_small.png&w=1920&q=75'
							StaticText Elevador Tijera Eléctrico 14 Metros
						[642] listitem, center=(671,446), inner_text=Elevador Tijera 4WD Diésel 12 Metros
							image Elevador Tijera 4WD Diésel 12 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FeBPwrpNDTLMiANHrC9bYqX_small.png&w=1920&q=75'
							StaticText Elevador Tijera 4WD Diésel 12 Metros
						[647] listitem, center=(671,510), inner_text=Elevador Tijera Eléctrico 16 Metros
							image Elevador Tijera Eléctrico 16 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FRPBtrXQawHcuRTQcFCR3av_small.png&w=1920&q=75'
							StaticText Elevador Tijera Eléctrico 16 Metros
						[652] listitem, center=(671,574), inner_text=Elevador Tijera 4WD Diésel 18 Metros
							image Elevador Tijera 4WD Diésel 18 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2Ftijera_diesel_18m_small.png&w=1920&q=75'
							StaticText Elevador Tijera 4WD Diésel 18 Metros
						[657] listitem, center=(1018,190), inner_text=Elevador Tijera 4WD Diésel 15 Metros
							image Elevador Tijera 4WD Diésel 15 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FG5PzqGFesWhYfMWsLpmH3L_small.png&w=1920&q=75'
							StaticText Elevador Tijera 4WD Diésel 15 Metros
						[662] listitem, center=(1018,254), inner_text=Elevador Tijera 4WD Diésel 10 Metros
							image Elevador Tijera 4WD Diésel 10 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FRdrV8kyQgxw7LE5ZrCLZzY_small.png&w=1920&q=75'
							StaticText Elevador Tijera 4WD Diésel 10 Metros
						[667] listitem, center=(1018,318), inner_text=Elevador Tijera Eléctrico 5 Metros
							image Elevador Tijera Eléctrico 5 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FaF8hSwSp57uEhBZ2dcBtgM_small.png&w=1920&q=75'
							StaticText Elevador Tijera Eléctrico 5 Metros
						[672] listitem, center=(1018,382), inner_text=Elevador Tijera Eléctrico 18 Metros
							image Elevador Tijera Eléctrico 18 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FEPfr7oVLUxVbLxzLZPcyYa_small.png&w=1920&q=75'
							StaticText Elevador Tijera Eléctrico 18 Metros
						[677] listitem, center=(1018,446), inner_text=Elevador Tijera 4WD Diésel 14 Metros
							image Elevador Tijera 4WD Diésel 14 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FNJTbPeeTFVYKuFE8mAjnmK_small.png&w=1920&q=75'
							StaticText Elevador Tijera 4WD Diésel 14 Metros
						[682] listitem, center=(1018,510), inner_text=Elevador Tijera 4WD Diésel 16 Metros
							image Elevador Tijera 4WD Diésel 16 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F8ZeK6a9P7uLwmGLZBxPhgo_small.png&w=1920&q=75'
							StaticText Elevador Tijera 4WD Diésel 16 Metros
						[687] listitem, center=(944,562), inner_text=Ver todo
							StaticText Ver todo
					image Elevador Tijera Eléctrico 8 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_small.png&w=1920&q=75'
					[690] div, center=(1344,262), inner_text=Elevador Tijera Eléctrico 8 Metros
					heading Elevador Tijera Eléctrico 8 Metros
					image Elevador Tijera Eléctrico 10 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FgEwtYuqhBVoCkD7ud6wjSG_small.png&w=1920&q=75'
					[695] div, center=(1488,262), inner_text=Elevador Tijera Eléctrico 10 Metros
					heading Elevador Tijera Eléctrico 10 Metros
					image Elevador Tijera Eléctrico 12 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F3xXDKDHSk6bsB3JxpMTWyT_small.png&w=1920&q=75'
					[700] div, center=(1344,478), inner_text=Elevador Tijera Eléctrico 12 Metros
					heading Elevador Tijera Eléctrico 12 Metros
					image Elevador Tijera Eléctrico 14 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F3uRcQYRLKUxnimTMEJoYWU_small.png&w=1920&q=75'
					[705] div, center=(1488,478), inner_text=Elevador Tijera Eléctrico 14 Metros
					heading Elevador Tijera Eléctrico 14 Metros
				[552] div, center=(1768,969), inner_text=¡Hablemos por WhatsApp!
				[315] div, center=(1562,952)
				[274] small, center=(1516,1057), inner_text=+ IVA
				[272] span, center=(1319,1056), inner_text=Arriendo diario desde
				[256] span, center=(1202,1052), inner_text=A cotizar
				[255] span, center=(1024,1052), inner_text=Arriendo desde
				[239] small, center=(922,1057), inner_text=+ IVA
				[237] span, center=(725,1056), inner_text=Arriendo diario desde
				[221] small, center=(626,1057), inner_text=+ IVA
				[219] span, center=(428,1056), inner_text=Arriendo diario desde
				[217] a, center=(514,988), inner_text=Elevador Tijera Eléctrico 8 Metros
				[198] div, center=(1626,547)
				[104] button Compra, center=(488,89), expanded=False, type=button
				[108] button Soluciones, center=(609,89), expanded=False, type=button
				[111] link Blog, center=(704,89), url='https://rendalomaq.com/blog'
			StaticText ¿Eres un proveedor? Arrienda o vende con nosotros
			[115] link Inscríbete ahora, center=(1544,89), url='https://rendalomaq.com/es-CL/arrendar-mi-maquinaria'
	main
		heading Arrienda, compra o vende maquinaria con RendaloMaq
		heading Cotiza en línea y comienza tu proyecto hoy
		image Una excavadora sale de un teléfono móvil, con la pantalla de cotización de RendaloMaq, url='https://rendalomaq.com/_next/image?url=%2Flanding%2Fes-CL-hero.webp&w=1920&q=75'
		image Elevadores Tijera, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F3Fo86WGLJoPRko8rjy48GF_small.png&w=1920&q=75'
		heading Elevadores Tijera
		image Brazos Articulados, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FBrazos_Articulados_small.png&w=1920&q=75'
		heading Brazos Articulados
		image Movimiento de Tierra, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FiEoP8LPto9nAtbjPfStkZB_small.png&w=1920&q=75'
		heading Movimiento de Tierra
		image Brazos Telescópicos, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FBrazos_Telescopicos_small.png&w=1920&q=75'
		heading Brazos Telescópicos
		image Camiones, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FCamion_Tolva_20_M3_-_Sin_Operador_D1JpiOg_small.png&w=1920&q=75'
		heading Camiones
		image Manipulación de Materiales, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FaXuJ4niZyH6rXuxEfhTMXD_small.png&w=1920&q=75'
		heading Manipulación de Materiales
		image Equipos de Apoyo, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FmYTSrYRs2w3jwjzEGVeKY9_small.png&w=1920&q=75'
		heading Equipos de Apoyo
		image Elevadores Unipersonales, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FRH8Prg7L8JcfsSkRUxyana_small.png&w=1920&q=75'
		heading Elevadores Unipersonales
		heading Grúas
		StaticText next
		heading Comúnmente arrendadas...
		[202] button Ver más, center=(1526,691), type=button
		[213] image Elevador Tijera Eléctrico 8 Metros, center=(514,856), url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_small.png&w=1920&q=75'
		heading Elevador Tijera Eléctrico 8 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $60.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		[231] image Elevador Tijera Eléctrico 10 Metros, center=(812,856), url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FgEwtYuqhBVoCkD7ud6wjSG_small.png&w=1920&q=75'
		[234] heading Elevador Tijera Eléctrico 10 Metros, center=(812,1008)
		paragraph
			StaticText Arriendo diario desde
			StaticText $70.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		[249] image Brazo Articulado Eléctrico 15 Metros, center=(1108,856), url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FnWs6wimRj9zHf76GaCT3T5_small.png&w=1920&q=75'
		[252] heading Brazo Articulado Eléctrico 15 Metros, center=(1108,1008)
		paragraph
			StaticText Arriendo desde
			StaticText A cotizar
		button Cotizar compra
		button Cotizar arriendo
		[266] image Elevador Tijera Eléctrico 12 Metros, center=(1406,856), url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F3xXDKDHSk6bsB3JxpMTWyT_small.png&w=1920&q=75'
		[269] heading Elevador Tijera Eléctrico 12 Metros, center=(1406,1008)
		paragraph
			StaticText Arriendo diario desde
			StaticText $85.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Brazo Articulado Eléctrico 16 Metros, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		heading Brazo Articulado Eléctrico 16 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $210.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Brazo Articulado Eléctrico 12 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FZi7r5rBBk8ZNApniU5D6gm_small.png&w=1920&q=75'
		heading Brazo Articulado Eléctrico 12 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $180.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		StaticText next
		heading Maquinaria más buscada...
		button Ver más
		image Elevador Tijera Eléctrico 8 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_small.png&w=1920&q=75'
		heading Elevador Tijera Eléctrico 8 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $60.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Elevador Tijera Eléctrico 10 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FgEwtYuqhBVoCkD7ud6wjSG_small.png&w=1920&q=75'
		heading Elevador Tijera Eléctrico 10 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $70.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Elevador Tijera Eléctrico 12 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2F3xXDKDHSk6bsB3JxpMTWyT_small.png&w=1920&q=75'
		heading Elevador Tijera Eléctrico 12 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $85.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Brazo Articulado Eléctrico 12 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FZi7r5rBBk8ZNApniU5D6gm_small.png&w=1920&q=75'
		heading Brazo Articulado Eléctrico 12 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $180.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Brazo Articulado 4WD Diésel 16 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FBrazos_Articulados_small.webp&w=1920&q=75'
		heading Brazo Articulado 4WD Diésel 16 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $230.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		image Brazo Articulado 4WD Diésel 26 Metros, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FnXbPYBPoZRTXYy8EqgPxzP_small.png&w=1920&q=75'
		heading Brazo Articulado 4WD Diésel 26 Metros
		paragraph
			StaticText Arriendo diario desde
			StaticText $410.000
			StaticText +
			StaticText IVA
		button Cotizar compra
		button Cotizar arriendo
		StaticText next
		image Dos personas de pie usando vestimenta de protección, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		heading ¿Tienes maquinaria y quieres rentabilizarla?
		paragraph
			StaticText ¡
			StaticText Arrienda más, haciendo menos
			StaticText !
		paragraph
			StaticText RendaloMaq se encarga de todo por ti, desde conseguir clientes hasta manejar garantías
			StaticText .
		button ¡Quiero ver todos los beneficios!
		heading Somos expertos en maquinaria
		heading +800
		paragraph
			StaticText clientes
		paragraph
			StaticText satisfechos
		heading +450
		paragraph
			StaticText proveedores
		paragraph
			StaticText asociados
		heading +5000
		paragraph
			StaticText máquinas
		heading Algunos de nuestros clientes
		image GTD, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Prosegur, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Agrosuper, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Finning, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Cosapi, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image SQM, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Anglo American, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Eiffage Energía, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Mineria Centinela, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image Aeropuerto Santiago, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		heading Y lo que han dicho
		image, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		paragraph
			StaticText “
			StaticText Con RendaloMaq tenemos la confianza de que obtendremos el equipo que necesitamos para ejecutar los proyectos que nos piden nuestros clientes. La gestión de arriendos ha sido muy cómoda y sobre todo, muy rápida siempre.
			StaticText ”
		strong
			StaticText Olga Sandoval
		paragraph
			StaticText Jefa de Instalaciones
		paragraph
			StaticText Cordillera tecnologías gráficas
		image Cordillera tecnologías gráficas, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		image, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		paragraph
			StaticText “
			StaticText Siempre están atentos a los proyectos que podamos tener. En muchos casos, las horas perdidas al no tener un equipo se convierten en gastos, por lo que RendaloMaq nos ayuda a conseguir la máquina de manera oportuna sin incurrir en pérdidas.
			StaticText ”
		strong
			StaticText Sergio Silva
		paragraph
			StaticText Comprador Senior
		paragraph
			StaticText COSAPI Chile
		image COSAPI Chile, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
	link ¡Hablemos por WhatsApp!, url='https://api.whatsapp.com/send/?phone=56951979537&text&type=phone_number&app_absent=0'
	[553] link Whatsapp Chat link, center=(1866,1036), url='https://api.whatsapp.com/send/?phone=56951979537&text&type=phone_number&app_absent=0'
		image Whatsapp Chat link, url='https://rendalomaq.com/_next/image?url=%2Frrss%2Fwhatsapp.png&w=48&q=75'
	alert, atomic
```
</details>



```
RootWebArea RendaloMaq | Arriendo y Venta de Maquinaria Online, focused, url='https://rendalomaq.com/es-CL/category/elevador-tijera-electrico-8-metros'
	navigation
		[57] link RendaloMaq RendaloMaq logo, center=(480,28), inner_text=RendaloMaq, url='https://rendalomaq.com/es-CL/category/elevador-tijera-electrico-8-metros#'
			image RendaloMaq logo, url='https://rendalomaq.com/colorful.svg'
		LabelText
```
<details><summary>Show more</summary>

```
			StaticText Buscar maquinaria...
		[74] searchbox Buscar maquinaria..., center=(960,28), autocomplete=off, contenteditable=True, type=search
		[80] button Open user menu, center=(1576,24), expanded=False, hasPopup='menu', type=button
	banner
		navigation Top
			navigation
				[100] button Arrienda, center=(374,89), expanded=False, focused, type=button
				[104] button Compra, center=(488,89), expanded=False, type=button
				[108] button Soluciones, center=(609,89), expanded=False, type=button
				[111] link Blog, center=(704,89), url='https://rendalomaq.com/blog'
			StaticText ¿Eres un proveedor? Arrienda o vende con nosotros
			[115] link Inscríbete ahora, center=(1544,89), url='https://rendalomaq.com/es-CL/arrendar-mi-maquinaria'
	main
		[734] button whatsapp, center=(1406,260)
			image
		[552] div, center=(1768,969), inner_text=¡Hablemos por WhatsApp!
		[736] button facebookmessenger, center=(1450,260)
			image
		[738] button facebook, center=(1494,260)
			image
		[740] button twitter, center=(1538,260)
			image
		[742] button email, center=(1582,260)
			image
		heading Elevador Tijera Eléctrico 8 Metros
		StaticText Día desde
		StaticText $60.000
		StaticText +
		StaticText IVA
		StaticText Semana desde
		StaticText $260.000
		StaticText +
		StaticText IVA
		StaticText Mes desde
		StaticText $650.000
		StaticText +
		StaticText IVA
		StaticText Transporte desde
		StaticText $150.000
		StaticText +
		StaticText IVA
		paragraph
			strong
				StaticText Valor final a cotizar
			StaticText ,
			StaticText depende de la ubicación geográfica.
		paragraph
			strong
				StaticText Disponibilidad 100% garantizada en todo Chile.
		[770] button Cotizar compra, center=(438,700), type=button
		[771] button Cotizar arriendo, center=(672,700), type=button
		image Ebook Elevadores tijera, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fcategories_ebooks_thumb%2F7dPYpaEe8UgNxe5eyLK2s7.png&w=256&q=75'
		paragraph
			StaticText Ebook
		heading Elevadores tijera
		[783] button Descargar, center=(608,878)
		paragraph
			StaticText Imágenes referenciales
		paragraph
			StaticText Imágenes referenciales
		image Elevador Tijera Eléctrico 8 Metros - 0, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		paragraph
			StaticText Imágenes referenciales
		paragraph
			StaticText Imágenes referenciales
		image Elevador Tijera Eléctrico 8 Metros - 0, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_medium.png&w=1920&q=75'
		paragraph
			StaticText Imágenes referenciales
		paragraph
			StaticText Imágenes referenciales
		image Elevador Tijera Eléctrico 8 Metros - 0, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		StaticText prev
		StaticText next
		image Elevador Tijera Eléctrico 8 Metros - 0, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_medium.png&w=1920&q=75'
		[816] div, center=(1578,534)
		[815] div, center=(828,534)
		image Elevador Tijera Eléctrico 8 Metros - 0, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_medium.png&w=1920&q=75'
		image Elevador Tijera Eléctrico 8 Metros - 0, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_medium.png&w=1920&q=75'
		navigation Tabs
			link Descripción
			link Atributos
		paragraph
			StaticText La máquina Elevador Tijera Eléctrico 8 Metros es un equipo versátil y seguro para trabajos en altura. Su diseño de tijera permite una elevación estable y segura, gracias a sus brazos extensibles que se despliegan verticalmente.
		paragraph
			StaticText Este elevador tiene una altura máxima de 8 metros y puede soportar una carga de hasta 350 kg. Su sistema eléctrico le brinda una operación silenciosa y libre de emisiones, ideal para trabajar en espacios interiores o sensibles al ruido.
		paragraph
			StaticText El Elevador Tijera Eléctrico 8 Metros es fácil de transportar y maniobrar, gracias a sus ruedas giratorias y freno de estacionamiento. Además, cuenta con controles intuitivos que permiten una operación sencilla y segura.
		paragraph
			strong
				StaticText Especificaciones:
		list
			listitem
				ListMarker •
				StaticText Altura máxima: 8 metros
			listitem
				ListMarker •
				StaticText Capacidad de carga: 350 kg
			listitem
				ListMarker •
				StaticText Sistema eléctrico
			listitem
				ListMarker •
				StaticText Ruedas giratorias con freno de estacionamiento
		paragraph
			strong
				StaticText Usos recomendados:
		list
			listitem
				ListMarker •
				StaticText Trabajos de construcción
			listitem
				ListMarker •
				StaticText Mantenimiento de instalaciones
			listitem
				ListMarker •
				StaticText Instalación de equipos eléctricos
	link ¡Hablemos por WhatsApp!, url='https://api.whatsapp.com/send/?phone=56951979537&text&type=phone_number&app_absent=0'
	[553] link Whatsapp Chat link, center=(1866,1036), url='https://api.whatsapp.com/send/?phone=56951979537&text&type=phone_number&app_absent=0'
		image Whatsapp Chat link, url='https://rendalomaq.com/_next/image?url=%2Frrss%2Fwhatsapp.png&w=48&q=75'
	alert, atomic
		StaticText RendaloMaq | Arriendo y Venta de Maquinaria Online
```
</details>

**Reasoning for action:** By clicking on the 'Elevador Tijera Eléctrico 8 Metros', I am navigating to the more detailed page for this scissor lift. This is a necessary step because it will provide the specific rental options and configurations, including where I can find the 'Cotizar arriendo' button. Accessing detailed information is essential for me to fulfill the user's request to obtain a rental quote for the specific lift they want.

**Action:** click(213) # Click on the 'Elevador Tijera Eléctrico 8 Metros' to view more details about this rental option.

**Change Description:** After the action, the browser navigated to a new URL specifically for the 'Elevador Tijera Eléctrico 8 Metros' rental option, displaying detailed information about the product including rental prices based on duration, specifications, and usage recommendations, as opposed to the previous catalog view.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://rendalomaq.com/es-CL/category/elevador-tijera-electrico-8-metros

https://rendalomaq.com/es-CL/category/elevador-tijera-electrico-8-metros

**Content (before/after):** 

```
RootWebArea RendaloMaq | Arriendo y Venta de Maquinaria Online, focused, url='https://rendalomaq.com/es-CL/category/elevador-tijera-electrico-8-metros'
	navigation
		[57] link RendaloMaq RendaloMaq logo, center=(480,28), inner_text=RendaloMaq, url='https://rendalomaq.com/es-CL/category/elevador-tijera-electrico-8-metros#'
			image RendaloMaq logo, url='https://rendalomaq.com/colorful.svg'
		LabelText
```
<details><summary>Show more</summary>

```
			StaticText Buscar maquinaria...
		[74] searchbox Buscar maquinaria..., center=(960,28), autocomplete=off, contenteditable=True, type=search
		[80] button Open user menu, center=(1576,24), expanded=False, hasPopup='menu', type=button
	banner
		navigation Top
			navigation
				[100] button Arrienda, center=(374,89), expanded=False, focused, type=button
				[104] button Compra, center=(488,89), expanded=False, type=button
				[108] button Soluciones, center=(609,89), expanded=False, type=button
				[111] link Blog, center=(704,89), url='https://rendalomaq.com/blog'
			StaticText ¿Eres un proveedor? Arrienda o vende con nosotros
			[115] link Inscríbete ahora, center=(1544,89), url='https://rendalomaq.com/es-CL/arrendar-mi-maquinaria'
	main
		[734] button whatsapp, center=(1406,260)
			image
		[552] div, center=(1768,969), inner_text=¡Hablemos por WhatsApp!
		[736] button facebookmessenger, center=(1450,260)
			image
		[738] button facebook, center=(1494,260)
			image
		[740] button twitter, center=(1538,260)
			image
		[742] button email, center=(1582,260)
			image
		heading Elevador Tijera Eléctrico 8 Metros
		StaticText Día desde
		StaticText $60.000
		StaticText +
		StaticText IVA
		StaticText Semana desde
		StaticText $260.000
		StaticText +
		StaticText IVA
		StaticText Mes desde
		StaticText $650.000
		StaticText +
		StaticText IVA
		StaticText Transporte desde
		StaticText $150.000
		StaticText +
		StaticText IVA
		paragraph
			strong
				StaticText Valor final a cotizar
			StaticText ,
			StaticText depende de la ubicación geográfica.
		paragraph
			strong
				StaticText Disponibilidad 100% garantizada en todo Chile.
		[770] button Cotizar compra, center=(438,700), type=button
		[771] button Cotizar arriendo, center=(672,700), type=button
		image Ebook Elevadores tijera, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fcategories_ebooks_thumb%2F7dPYpaEe8UgNxe5eyLK2s7.png&w=256&q=75'
		paragraph
			StaticText Ebook
		heading Elevadores tijera
		[783] button Descargar, center=(608,878)
		paragraph
			StaticText Imágenes referenciales
		paragraph
			StaticText Imágenes referenciales
		image Elevador Tijera Eléctrico 8 Metros - 0, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		paragraph
			StaticText Imágenes referenciales
		paragraph
			StaticText Imágenes referenciales
		image Elevador Tijera Eléctrico 8 Metros - 0, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_medium.png&w=1920&q=75'
		paragraph
			StaticText Imágenes referenciales
		paragraph
			StaticText Imágenes referenciales
		image Elevador Tijera Eléctrico 8 Metros - 0, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		StaticText prev
		StaticText next
		image Elevador Tijera Eléctrico 8 Metros - 0, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_medium.png&w=1920&q=75'
		[816] div, center=(1578,534)
		[815] div, center=(828,534)
		image Elevador Tijera Eléctrico 8 Metros - 0, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_medium.png&w=1920&q=75'
		image Elevador Tijera Eléctrico 8 Metros - 0, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_medium.png&w=1920&q=75'
		navigation Tabs
			link Descripción
			link Atributos
		paragraph
			StaticText La máquina Elevador Tijera Eléctrico 8 Metros es un equipo versátil y seguro para trabajos en altura. Su diseño de tijera permite una elevación estable y segura, gracias a sus brazos extensibles que se despliegan verticalmente.
		paragraph
			StaticText Este elevador tiene una altura máxima de 8 metros y puede soportar una carga de hasta 350 kg. Su sistema eléctrico le brinda una operación silenciosa y libre de emisiones, ideal para trabajar en espacios interiores o sensibles al ruido.
		paragraph
			StaticText El Elevador Tijera Eléctrico 8 Metros es fácil de transportar y maniobrar, gracias a sus ruedas giratorias y freno de estacionamiento. Además, cuenta con controles intuitivos que permiten una operación sencilla y segura.
		paragraph
			strong
				StaticText Especificaciones:
		list
			listitem
				ListMarker •
				StaticText Altura máxima: 8 metros
			listitem
				ListMarker •
				StaticText Capacidad de carga: 350 kg
			listitem
				ListMarker •
				StaticText Sistema eléctrico
			listitem
				ListMarker •
				StaticText Ruedas giratorias con freno de estacionamiento
		paragraph
			strong
				StaticText Usos recomendados:
		list
			listitem
				ListMarker •
				StaticText Trabajos de construcción
			listitem
				ListMarker •
				StaticText Mantenimiento de instalaciones
			listitem
				ListMarker •
				StaticText Instalación de equipos eléctricos
	link ¡Hablemos por WhatsApp!, url='https://api.whatsapp.com/send/?phone=56951979537&text&type=phone_number&app_absent=0'
	[553] link Whatsapp Chat link, center=(1866,1036), url='https://api.whatsapp.com/send/?phone=56951979537&text&type=phone_number&app_absent=0'
		image Whatsapp Chat link, url='https://rendalomaq.com/_next/image?url=%2Frrss%2Fwhatsapp.png&w=48&q=75'
	alert, atomic
		StaticText RendaloMaq | Arriendo y Venta de Maquinaria Online
```
</details>



```
RootWebArea RendaloMaq | Arriendo y Venta de Maquinaria Online, focused, url='https://rendalomaq.com/es-CL/category/elevador-tijera-electrico-8-metros'
	navigation
		link RendaloMaq RendaloMaq logo, url='https://rendalomaq.com/es-CL/category/elevador-tijera-electrico-8-metros#'
			image RendaloMaq logo, url='https://rendalomaq.com/colorful.svg'
		LabelText
```
<details><summary>Show more</summary>

```
			StaticText Buscar maquinaria...
		searchbox Buscar maquinaria...
		button Open user menu, expanded=False, hasPopup='menu'
	banner
		navigation Top
			navigation
				button Arrienda, expanded=False
				button Compra, expanded=False
				button Soluciones, expanded=False
				link Blog, url='https://rendalomaq.com/blog'
			StaticText ¿Eres un proveedor? Arrienda o vende con nosotros
			link Inscríbete ahora, url='https://rendalomaq.com/es-CL/arrendar-mi-maquinaria'
	main
		button whatsapp
			image
		button facebookmessenger
			image
		button facebook
			image
		button twitter
			image
		button email
			image
		heading Elevador Tijera Eléctrico 8 Metros
		StaticText Día desde
		StaticText $60.000
		StaticText +
		StaticText IVA
		StaticText Semana desde
		StaticText $260.000
		StaticText +
		StaticText IVA
		StaticText Mes desde
		StaticText $650.000
		StaticText +
		StaticText IVA
		StaticText Transporte desde
		StaticText $150.000
		StaticText +
		StaticText IVA
		paragraph
			strong
				StaticText Valor final a cotizar
			StaticText ,
			StaticText depende de la ubicación geográfica.
		paragraph
			strong
				StaticText Disponibilidad 100% garantizada en todo Chile.
		button Cotizar compra
		button Cotizar arriendo
		image Ebook Elevadores tijera, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fcategories_ebooks_thumb%2F7dPYpaEe8UgNxe5eyLK2s7.png&w=256&q=75'
		paragraph
			StaticText Ebook
		heading Elevadores tijera
		button Descargar
		paragraph
			StaticText Imágenes referenciales
		paragraph
			StaticText Imágenes referenciales
		image Elevador Tijera Eléctrico 8 Metros - 0, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		paragraph
			StaticText Imágenes referenciales
		paragraph
			StaticText Imágenes referenciales
		image Elevador Tijera Eléctrico 8 Metros - 0, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_medium.png&w=1920&q=75'
		paragraph
			StaticText Imágenes referenciales
		paragraph
			StaticText Imágenes referenciales
		image Elevador Tijera Eléctrico 8 Metros - 0, url='data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7'
		StaticText prev
		StaticText next
		image Elevador Tijera Eléctrico 8 Metros - 0, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_medium.png&w=1920&q=75'
		image Elevador Tijera Eléctrico 8 Metros - 0, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_medium.png&w=1920&q=75'
		image Elevador Tijera Eléctrico 8 Metros - 0, url='https://rendalomaq.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Frendalo-media-prod%2Fmedia%2Fthumbnails%2Fcategories%2FbgHgyg6RoZdLUiTzGRmZ3D_medium.png&w=1920&q=75'
		navigation Tabs
			link Descripción
			link Atributos
		paragraph
			StaticText La máquina Elevador Tijera Eléctrico 8 Metros es un equipo versátil y seguro para trabajos en altura. Su diseño de tijera permite una elevación estable y segura, gracias a sus brazos extensibles que se despliegan verticalmente.
		paragraph
			StaticText Este elevador tiene una altura máxima de 8 metros y puede soportar una carga de hasta 350 kg. Su sistema eléctrico le brinda una operación silenciosa y libre de emisiones, ideal para trabajar en espacios interiores o sensibles al ruido.
		paragraph
			StaticText El Elevador Tijera Eléctrico 8 Metros es fácil de transportar y maniobrar, gracias a sus ruedas giratorias y freno de estacionamiento. Además, cuenta con controles intuitivos que permiten una operación sencilla y segura.
		paragraph
			strong
				StaticText Especificaciones:
		list
			listitem
				ListMarker •
				StaticText Altura máxima: 8 metros
			listitem
				ListMarker •
				StaticText Capacidad de carga: 350 kg
			listitem
				ListMarker •
				StaticText Sistema eléctrico
			listitem
				ListMarker •
				StaticText Ruedas giratorias con freno de estacionamiento
		paragraph
			strong
				StaticText Usos recomendados:
		list
			listitem
				ListMarker •
				StaticText Trabajos de construcción
			listitem
				ListMarker •
				StaticText Mantenimiento de instalaciones
			listitem
				ListMarker •
				StaticText Instalación de equipos eléctricos
	link ¡Hablemos por WhatsApp!, url='https://api.whatsapp.com/send/?phone=56951979537&text&type=phone_number&app_absent=0'
	link Whatsapp Chat link, url='https://api.whatsapp.com/send/?phone=56951979537&text&type=phone_number&app_absent=0'
		image Whatsapp Chat link, url='https://rendalomaq.com/_next/image?url=%2Frrss%2Fwhatsapp.png&w=48&q=75'
	alert, atomic
		StaticText RendaloMaq | Arriendo y Venta de Maquinaria Online
	dialog, modal=True
		[907] button Close, center=(1254,386), focused, type=button
		StaticText request_quote
		paragraph
			StaticText Necesitamos pedirte algunos datos para cotizar lo más rápido posible
		LabelText
			StaticText Dirección
			StaticText Puedes escribir la dirección completa o sólo la comuna
		[920] textbox Ejemplo: Moneda 1202, Santiago, center=(960,538), contenteditable=True
		LabelText
			StaticText Selecciona una fecha de inicio
		[925] Date value='2025-01-09', center=(807,616), contenteditable=True, type=date
			spinbutton Month value='1'
				StaticText 01
			StaticText /
			spinbutton Day value='9'
				StaticText 09
			StaticText /
			spinbutton Year value='2025'
			button Show date picker, hasPopup='menu'
		LabelText
			StaticText Cantidad estimada de días
		[929] spinbutton Cantidad estimada de días value='30', center=(1113,616), contenteditable=True, type=number
		[931] button Continuar, center=(1112,672), type=submit
		[932] button Cancelar, center=(808,672), type=button
```
</details>

**Reasoning for action:** I clicked the 'Cotizar arriendo' button because it directly pertains to the user story, where the construction project manager requested a rental quote for an electric scissor lift. This action aligns with the user's goal of acquiring the necessary equipment efficiently, as it initiates the process to gather essential details needed for the quote. By opening the modal dialog, it allows for the collection of the user's address, the desired rental start date, and the estimated duration of the rental, which are all critical for generating an accurate rental quote.

**Action:** click(771) # Click on the 'Cotizar arriendo' button to request a rental quote.

**Change Description:** After clicking the 'Cotizar arriendo' button, a modal dialog opened prompting the user to fill in their address, select a start date, and estimate the number of rental days to request a rental quote.

**Screenshot before:****Screenshot after:**---


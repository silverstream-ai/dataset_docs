# Task

**Shopping Cart Addition User Story**

As a Trela customer,
I quickly access discounted products and add items to my shopping cart,
so that I can take advantage of special offers and enjoy savings during my online shopping experience.

**Success definition:** Given I am on the Trela homepage with the category 'Oferta do Dia até 15 OFF' visible
When I click on a product link for 'Queijo cottage 200g' and then click 'Adicionar ao carrinho'
Then I should see the product added to my shopping cart with updated pricing and availability details displayed.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://trela.com.br/

https://trela.com.br/categoria/oferta-do-dia-ate-15-off-180

**Content (before/after):** 

```
RootWebArea Trela | O mercado para comer bem. Do seu jeito, focused, url='https://trela.com.br/'
	banner
		navigation
			[86] link Trela, center=(335,30), url='https://trela.com.br/'
				image Trela
```
<details><summary>Show more</summary>

```
			[91] textbox O que você está procurando?, center=(960,30), contenteditable=True
			[93] link Entrar / Cadastrar, center=(1496,30), url='https://trela.com.br/login?callbackUrl=%2F'
			[95] button Menu, center=(1602,30)
	StaticText ✨ Peça até 23h59 de hoje e receba no próximo dia útil com frete grátis ✨
	main
		heading Trela
		image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Ffoto_landing_deslogada_eeb2105706.png&w=1920&q=75'
		[124] section, center=(960,346), inner_text=O mercado para comer bem. Do seu jeito.

Faça sua primeira compra com o cupom DEZEMBRO e ganhe 15% de cashback para usar em Janeiro. *Válido para todos os produtos, exceto os azeites especiais da Trela (cerâmica e vidro). Consulte os detalhes em nossos Termos e Condições.
		heading O mercado para comer bem. Do seu jeito.
		paragraph
			StaticText Faça sua primeira compra com o cupom DEZEMBRO e ganhe 15% de cashback para usar em Janeiro. *Válido para todos os produtos, exceto os azeites especiais da Trela (cerâmica e vidro). Consulte os detalhes em nossos Termos e Condições.
		region lista de categorias
			list
				listitem
					[135] link Oferta do Dia até 15% OFF, center=(416,684), url='https://trela.com.br/categoria/oferta-do-dia-ate-15-off-180'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F00180a97-33f3-4eb4-923d-eee91d4cbaa0.png&w=96&q=75'
				listitem
					[140] link Selecionados para você, center=(537,684), url='https://trela.com.br/categoria/selecionados-para-voce-1097'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fea58f86c-8199-4cd3-a72b-dd34789b4f3e.png&w=96&q=75'
				listitem
					[145] link Novos na Trela, center=(658,684), url='https://trela.com.br/categoria/novos-na-trela-298'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F631f48a8-7c0d-41a0-a6af-0d75ce1dc13c.png&w=96&q=75'
				listitem
					[150] link Especiais de fim de ano, center=(779,684), url='https://trela.com.br/categoria/especiais-de-fim-de-ano-1156'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F12e2c830-329b-4add-8356-58de664609ab.png&w=96&q=75'
				listitem
					[155] link Hortifruti e ovos, center=(900,684), url='https://trela.com.br/categoria/hortifruti-e-ovos-662'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F8c170965-16cd-4531-8023-c433f1af7c70.png&w=96&q=75'
				listitem
					[160] link Queijos e laticínios, center=(1020,684), url='https://trela.com.br/categoria/queijos-e-laticinios-693'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fc49fcac4-9824-422c-a80e-babc86875214.png&w=96&q=75'
				listitem
					[165] link Básicos da despensa, center=(1141,684), url='https://trela.com.br/categoria/basicos-da-despensa-587'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F198dc6a8-b72d-40e6-bdf8-1e28ad8e3b80.png&w=96&q=75'
				listitem
					[170] link Carnes, center=(1262,684), url='https://trela.com.br/categoria/carnes-622'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F721a0006-f25a-421d-8af9-19b5a20980a5.png&w=96&q=75'
				listitem
					[175] link Peixes e frutos do mar, center=(1383,684), url='https://trela.com.br/categoria/peixes-e-frutos-do-mar-681'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F8657ee04-91e3-4f37-a8a6-d10a73ae2a14.png&w=96&q=75'
				listitem
					[180] link Frios e charcutaria, center=(1504,684), url='https://trela.com.br/categoria/frios-e-charcutaria-654'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fc6d840c0-7077-43b8-829b-31bedd0de1d6.png&w=96&q=75'
				listitem
					link Padaria e confeitaria, url='https://trela.com.br/categoria/padaria-e-confeitaria-673'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F5d90de96-9ae3-4c3d-b413-8b564d4a360e.png&w=96&q=75'
				listitem
					link Refeições práticas, url='https://trela.com.br/categoria/refeicoes-praticas-565'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fe4aaba8f-397b-4aa3-beac-4b7dd89cb0ac.png&w=96&q=75'
				listitem
					link Salgados e tortas, url='https://trela.com.br/categoria/salgados-e-tortas-727'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fc034a3b9-b196-4329-b332-3f93558df7d2.png&w=96&q=75'
				listitem
					link Pizzas e massas, url='https://trela.com.br/categoria/pizzas-e-massas-686'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F0862abb7-d513-4c35-b983-e665616a748b.png&w=96&q=75'
				listitem
					link Antepastos e molhos, url='https://trela.com.br/categoria/antepastos-e-molhos-578'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F13aa370a-7702-4aa9-988f-5d1dc141a3a9.png&w=96&q=75'
				listitem
					link Castanhas e frutas secas, url='https://trela.com.br/categoria/castanhas-e-frutas-secas-634'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fb5798c8f-465e-45d1-aa06-0c67a7b55bc7.png&w=96&q=75'
				listitem
					link Snacks, url='https://trela.com.br/categoria/snacks-733'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F2a5d617f-03a9-40bf-9df1-c3f4e37506d6.png&w=96&q=75'
				listitem
					link Suplementos, url='https://trela.com.br/categoria/suplementos-747'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fda566dba-d86f-4f48-a463-ebdf864b09f2.png&w=96&q=75'
				listitem
					link Doces e chocolates, url='https://trela.com.br/categoria/doces-e-chocolates-645'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fb4e1a295-beeb-4321-92fc-b15c08dfb512.png&w=96&q=75'
				listitem
					link Sorvetes e açaí, url='https://trela.com.br/categoria/sorvetes-e-acai-742'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F26b77fa7-f6f9-4df0-b3d7-0f33bc40b6e0.png&w=96&q=75'
				listitem
					link Bebidas, url='https://trela.com.br/categoria/bebidas-599'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F2ac71ac0-8ce3-4125-acd8-8510853260cf.png&w=96&q=75'
				listitem
					link Cafés e Chás, url='https://trela.com.br/categoria/cafes-e-chas-611'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Feeb697f1-eaf4-4c9b-9673-fe0e1a219a89.png&w=96&q=75'
				listitem
					link Cervejas e destilados, url='https://trela.com.br/categoria/cervejas-e-destilados-641'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fa79f76db-bf33-4c5e-8306-d89033c6c30e.png&w=96&q=75'
				listitem
					link Vinhos e espumantes, url='https://trela.com.br/categoria/vinhos-e-espumantes-758'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F7261bc0b-70f9-4b92-ac31-92cb3b214579.png&w=96&q=75'
				listitem
					link Plant-Based, url='https://trela.com.br/categoria/plantbased-224'
						image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F7aac7d2e-64eb-44ef-954f-723aa42432bd.png&w=96&q=75'
			[261] button próximos itens, center=(1588,684)
		region Oferta do Dia até 15% OFF Ver categoria
			heading Oferta do Dia até 15% OFF
			[267] link Ver categoria, center=(1516,797), url='https://trela.com.br/categoria/oferta-do-dia-ate-15-off-180'
			list
				listitem
					[272] link Queijo cottage 200g 51 Refrigerado adicionar Cruzília Cruzília Queijo cottage 200g R$ 10,90 R$ 9,27 -15%, center=(457,951), inner_text=51
Refrigerado
Cruzília
Queijo cottage 200g
R$ 10,90
R$ 9,27
-15%, url='https://trela.com.br/produto/queijo-cottage-200g-12211'
						image Queijo cottage 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc11f29bb-a64a-4222-a8c6-7bca76aa0b7f-cottage-cruzi%CC%81lia-12211.1.png&w=384&q=75'
						StaticText 51
						StaticText Refrigerado
						button adicionar
						image Cruzília, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5786d8f5-d4ca-41e6-980a-60bd819b961d.png&w=32&q=75'
						StaticText Cruzília
						heading Queijo cottage 200g
				listitem
					[300] link Pão sem glúten tradicional 500g - Congelado 19 Congelado adicionar Pão do Céu Pão do Céu Pão sem glúten tradicional 500g - Congelado R$ 20,90 R$ 17,77 -15%, center=(658,960), inner_text=19
Congelado
Pão do Céu
Pão sem glúten tradicional 500g - Congelado
R$ 20,90
R$ 17,77
-15%, url='https://trela.com.br/produto/pao-sem-gluten-tradicional-500g-congelado-12555'
						image Pão sem glúten tradicional 500g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F74dcb0e2-aa6c-4909-8d05-5ad41199945a.png&w=384&q=75'
						StaticText 19
						StaticText Congelado
						button adicionar
						image Pão do Céu, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F8c47b61c-1745-4522-a1c3-5e3592a4f157.png&w=32&q=75'
						StaticText Pão do Céu
						heading Pão sem glúten tradicional 500g - Congelado
				listitem
					[328] link Guacamole Sr. Guaca 200g 39 Refrigerado adicionar Sr. Guaca Sr. Guaca Guacamole Sr. Guaca 200g R$ 15,29 R$ 13,00 -15%, center=(859,951), inner_text=39
Refrigerado
Sr. Guaca
Guacamole Sr. Guaca 200g
R$ 15,29
R$ 13,00
-15%, url='https://trela.com.br/produto/guacamole-sr-guaca-200g-11448'
						image Guacamole Sr. Guaca 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F692edf71-8478-48b9-b4b5-dc3fe356a7ec-guacamolesrguaca-srguaca-11448.1.png&w=384&q=75'
						StaticText 39
						StaticText Refrigerado
						button adicionar
						image Sr. Guaca, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F6df05adb-ce6b-4c5b-9412-fac3eef999fe.png&w=32&q=75'
						StaticText Sr. Guaca
						heading Guacamole Sr. Guaca 200g
				listitem
					[356] link Suco de laranja 900ml 42 Refrigerado adicionar Xandô Xandô Suco de laranja 900ml R$ 15,90 R$ 13,52 -15%, center=(1061,951), inner_text=42
Refrigerado
Xandô
Suco de laranja 900ml
R$ 15,90
R$ 13,52
-15%, url='https://trela.com.br/produto/suco-de-laranja-900ml-10863'
						image Suco de laranja 900ml, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fd2cc0667-b893-4983-b41e-fcf7c6a60fcb-sucodelaranja-xando%CC%82-10863.1.png&w=384&q=75'
						StaticText 42
						StaticText Refrigerado
						button adicionar
						image Xandô, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F77360f6b-5746-43ec-ae31-67d69718f6d1.png&w=32&q=75'
						StaticText Xandô
						heading Suco de laranja 900ml
				listitem
					[384] link Iogurte Natural de Leite de Ovelha 140g 38 Refrigerado adicionar Queijaria Rima Queijaria Rima Iogurte Natural de Leite de Ovelha 140g R$ 6,12 R$ 5,20 -15%, center=(1262,960), inner_text=38
Refrigerado
Queijaria Rima
Iogurte Natural de Leite de Ovelha 140g
R$ 6,12
R$ 5,20
-15%, url='https://trela.com.br/produto/iogurte-natural-de-leite-de-ovelha-140g-11450'
						image Iogurte Natural de Leite de Ovelha 140g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F32111064-0b47-4689-9a9d-0d66b9bfac2e.png&w=384&q=75'
						StaticText 38
						StaticText Refrigerado
						button adicionar
						image Queijaria Rima, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fsuppliers%2F8265229b-2829-4816-9b2d-3d394b18628b.png&w=32&q=75'
						StaticText Queijaria Rima
						heading Iogurte Natural de Leite de Ovelha 140g
				listitem
					[412] link Pão 100% integral 450g - Congelado 24 Congelado adicionar Pão do Céu Pão do Céu Pão 100% integral 450g - Congelado R$ 18,40 R$ 15,64 -15%, center=(1463,960), inner_text=24
Congelado
Pão do Céu
Pão 100% integral 450g - Congelado
R$ 18,40
R$ 15,64
-15%, url='https://trela.com.br/produto/pao-100-integral-450g-congelado-12554'
						image Pão 100% integral 450g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fa8224eb4-7378-4a4f-98d8-fea03fed8bdc-p%C3%A3o100_integral-p%C3%A3odoc%C3%A9u-12554.1.png&w=384&q=75'
						StaticText 24
						StaticText Congelado
						button adicionar
						image Pão do Céu, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F8c47b61c-1745-4522-a1c3-5e3592a4f157.png&w=32&q=75'
						StaticText Pão do Céu
						heading Pão 100% integral 450g - Congelado
				listitem
					link Natural Whey de Coco 21g de proteína - 250g 29 Refrigerado adicionar Verde Campo Verde Campo Natural Whey de Coco 21g de proteína - 250g R$ 8,69 R$ 7,39 -15%, url='https://trela.com.br/produto/natural-whey-de-coco-21g-de-proteina-250g-11527'
						image Natural Whey de Coco 21g de proteína - 250g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F0ce6f300-be4a-46c8-b164-58d6f7e9be3b.png&w=384&q=75'
						StaticText 29
						StaticText Refrigerado
						button adicionar
						image Verde Campo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb045f0a8-3d1e-4064-9cc2-d188dfa19844.png&w=32&q=75'
						StaticText Verde Campo
						heading Natural Whey de Coco 21g de proteína - 250g
				listitem
					link Pão batata doce orgânico 450g - Congelado 25 Congelado adicionar Pão do Céu Pão do Céu Pão batata doce orgânico 450g - Congelado R$ 18,40 R$ 15,64 -15%, url='https://trela.com.br/produto/pao-batata-doce-organico-450g-congelado-12553'
						image Pão batata doce orgânico 450g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fe63e8495-d4c3-4195-8228-5d9888b36cd3-p%C3%A3obatatadoceorg%C3%A2nico-p%C3%A3odoc%C3%A9u-12553.1.png&w=384&q=75'
						StaticText 25
						StaticText Congelado
						button adicionar
						image Pão do Céu, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F8c47b61c-1745-4522-a1c3-5e3592a4f157.png&w=32&q=75'
						StaticText Pão do Céu
						heading Pão batata doce orgânico 450g - Congelado
				listitem
					link Yorgus grego desnatado natural 500g 22 Refrigerado adicionar Yorgus Yorgus Yorgus grego desnatado natural 500g R$ 29,90 R$ 25,42 -15%, url='https://trela.com.br/produto/yorgus-grego-desnatado-natural-500g-12905'
						image Yorgus grego desnatado natural 500g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fd1c5638d-0592-41b5-83f1-56c8747f5607.png&w=384&q=75'
						StaticText 22
						StaticText Refrigerado
						button adicionar
						image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
						StaticText Yorgus
						heading Yorgus grego desnatado natural 500g
				listitem
					link Pão energia das sementes 380g - Congelado 11 Congelado adicionar House of Maya House of Maya Pão energia das sementes 380g - Congelado R$ 30,90 R$ 26,27 -15%, url='https://trela.com.br/produto/pao-energia-das-sementes-380g-congelado-12768'
						image Pão energia das sementes 380g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F96a16c52-2c24-46c2-8762-21db570a0b3d-p%C3%A3oenergiadassementes-houseofmaya-12768.1.png&w=384&q=75'
						StaticText 11
						StaticText Congelado
						button adicionar
						image House of Maya, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fdc9155eb-7b51-4963-b8d8-fbbb9e369d3d.png&w=32&q=75'
						StaticText House of Maya
						heading Pão energia das sementes 380g - Congelado
				listitem
					link Tofu Orgânico Natural 450g - Refrigerado 13  Ultrafresco adicionar SÍtio Boa Esperança SÍtio Boa Esperança Tofu Orgânico Natural 450g - Refrigerado R$ 28,90 R$ 24,57 -15%, url='https://trela.com.br/produto/tofu-organico-natural-450g-refrigerado-11583'
						image Tofu Orgânico Natural 450g - Refrigerado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F93093a13-4118-4fb4-b283-b652827a7d85-tofuorga%CC%82niconatural-si%CC%81tioboaesperanc%CC%A7a-11583.1.png&w=384&q=75'
						StaticText 13
						StaticText 
						StaticText Ultrafresco
						button adicionar
						image SÍtio Boa Esperança, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F80eedb37-bb57-4585-81c1-086cdfa83a60.png&w=32&q=75'
						StaticText SÍtio Boa Esperança
						heading Tofu Orgânico Natural 450g - Refrigerado
				listitem
					link Bolo de limão siciliano e amêndoas 270g - Congelado Congelado adicionar House of Maya House of Maya Bolo de limão siciliano e amêndoas 270g - Congelado R$ 25,90 R$ 22,02 -15%, url='https://trela.com.br/produto/bolo-de-limao-siciliano-e-amendoas-270g-congelado-12765'
						image Bolo de limão siciliano e amêndoas 270g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F4b5758a7-3cb8-4c51-9db5-1eb34a276843-bolodelim%C3%A3osicilianoeam%C3%AAndoas-houseofmaya-12765.1.png&w=384&q=75'
						StaticText Congelado
						button adicionar
						image House of Maya, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fdc9155eb-7b51-4963-b8d8-fbbb9e369d3d.png&w=32&q=75'
						StaticText House of Maya
						heading Bolo de limão siciliano e amêndoas 270g - Congelado
				listitem
					link Yorgus grego natural 0% gordura 130g 15 Refrigerado adicionar Yorgus Yorgus Yorgus grego natural 0% gordura 130g R$ 8,49 R$ 7,22 -15%, url='https://trela.com.br/produto/yorgus-grego-natural-0-gordura-130g-11531'
						image Yorgus grego natural 0% gordura 130g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff4f3624a-a448-44e1-936e-50984edb5ae5-yorgusgregonatural0_gordura-yorgus-11531.1.png&w=384&q=75'
						StaticText 15
						StaticText Refrigerado
						button adicionar
						image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
						StaticText Yorgus
						heading Yorgus grego natural 0% gordura 130g
				listitem
					link Iogurte de Mel 170ml 38 Refrigerado adicionar Delicari Delicari Iogurte de Mel 170ml R$ 7,10 R$ 6,04 -15%, url='https://trela.com.br/produto/iogurte-de-mel-170ml-9252'
						image Iogurte de Mel 170ml, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F61c7e0ba-8841-481d-89ca-56f2b59d1d02-iogurtedemell-delicari-9252.1.png&w=384&q=75'
						StaticText 38
						StaticText Refrigerado
						button adicionar
						image Delicari, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F2403b2c8-dce9-4d5c-846b-0ff0be5d1868.png&w=32&q=75'
						StaticText Delicari
						heading Iogurte de Mel 170ml
				listitem
					link Ovos caipiras com ômega 3 orgânicos 10 Unidades 22 adicionar Fazenda da Toca Fazenda da Toca Ovos caipiras com ômega 3 orgânicos 10 Unidades R$ 15,29 R$ 13,00 -15%, url='https://trela.com.br/produto/ovos-caipiras-com-omega-3-organicos-10-unidades-13294'
						image Ovos caipiras com ômega 3 orgânicos 10 Unidades, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb10cacb8-9748-43c8-8724-ada849cce6d9.png&w=384&q=75'
						StaticText 22
						button adicionar
						image Fazenda da Toca, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F4a8a125a-4069-4776-b8dc-a16acbd5e4a3.png&w=32&q=75'
						StaticText Fazenda da Toca
						heading Ovos caipiras com ômega 3 orgânicos 10 Unidades
				listitem
					link Yorgus desnatado com mel silvestre orgânico 130g 13 Refrigerado adicionar Yorgus Yorgus Yorgus desnatado com mel silvestre orgânico 130g R$ 8,49 R$ 7,22 -15%, url='https://trela.com.br/produto/yorgus-desnatado-com-mel-silvestre-organico-130g-12904'
						image Yorgus desnatado com mel silvestre orgânico 130g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F620fcaa6-9327-4207-8d93-93ef0b5c7434-yorgusdesnatadocommelsilvestreorga%CC%82nico-yorgus-12904.1.png&w=384&q=75'
						StaticText 13
						StaticText Refrigerado
						button adicionar
						image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
						StaticText Yorgus
						heading Yorgus desnatado com mel silvestre orgânico 130g
			[713] button próximos itens, center=(1588,909)
		region Novos na Trela Ver categoria
			heading Novos na Trela
			link Ver categoria, url='https://trela.com.br/categoria/novos-na-trela-298'
			list
				listitem
					link Barra vegana de café mocha com 20g de proteína adicionar Hart's Natural Hart's Natural Barra vegana de café mocha com 20g de proteína R$ 16,99, url='https://trela.com.br/produto/barra-vegana-de-cafe-mocha-com-20g-de-proteina-13820'
						image Barra vegana de café mocha com 20g de proteína, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F0a16e96a-abc0-44e2-9242-01928fcbaea6.png&w=384&q=75'
						button adicionar
						image Hart's Natural, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F173a7f1b-79b3-4878-bbdf-1382d515e434.png&w=32&q=75'
						StaticText Hart's Natural
						heading Barra vegana de café mocha com 20g de proteína
				listitem
					link Energy Gel Z2+ Lime 40g Novo adicionar Z2 Z2 Energy Gel Z2+ Lime 40g R$ 14,49, url='https://trela.com.br/produto/energy-gel-z2-lime-40g-13845'
						image Energy Gel Z2+ Lime 40g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc1d429f9-4ef5-44d5-a441-ddc65b51b8af.png&w=384&q=75'
						StaticText Novo
						button adicionar
						image Z2, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc0df5b09-601e-4015-a091-0fdf44edf7e8.png&w=32&q=75'
						StaticText Z2
						heading Energy Gel Z2+ Lime 40g
				listitem
					link Energy Gel Z2+ Pineapple Mint 40g Novo adicionar Z2 Z2 Energy Gel Z2+ Pineapple Mint 40g R$ 14,49, url='https://trela.com.br/produto/energy-gel-z2-pineapple-mint-40g-13842'
						image Energy Gel Z2+ Pineapple Mint 40g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F161e7fbd-003b-46dc-b823-83bf6c40222b.png&w=384&q=75'
						StaticText Novo
						button adicionar
						image Z2, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc0df5b09-601e-4015-a091-0fdf44edf7e8.png&w=32&q=75'
						StaticText Z2
						heading Energy Gel Z2+ Pineapple Mint 40g
				listitem
					link Energy Gel Z2 Pitaya 40g Novo adicionar Z2 Z2 Energy Gel Z2 Pitaya 40g R$ 13,49, url='https://trela.com.br/produto/energy-gel-z2-pitaya-40g-13841'
						image Energy Gel Z2 Pitaya 40g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F03a49580-c8a2-46b0-9e58-0bf97d4a1147.png&w=384&q=75'
						StaticText Novo
						button adicionar
						image Z2, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc0df5b09-601e-4015-a091-0fdf44edf7e8.png&w=32&q=75'
						StaticText Z2
						heading Energy Gel Z2 Pitaya 40g
				listitem
					link Panetone de Frutas Vermelhas 650g Novo adicionar Dengo Chocolates Dengo Chocolates Panetone de Frutas Vermelhas 650g R$ 165,90, url='https://trela.com.br/produto/panetone-de-frutas-vermelhas-650g-13904'
						image Panetone de Frutas Vermelhas 650g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5190dad9-724b-4e71-adab-f56c94472ee7.png&w=384&q=75'
						StaticText Novo
						button adicionar
						image Dengo Chocolates, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F6467ad89-de90-46a3-9481-a92681324e5a.png&w=32&q=75'
						StaticText Dengo Chocolates
						heading Panetone de Frutas Vermelhas 650g
				listitem
					link Uva thompson 500g Novo adicionar Quitanda Tomio Quitanda Tomio Uva thompson 500g R$ 24,98, url='https://trela.com.br/produto/uva-thompson-500g-13784'
						image Uva thompson 500g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff15822a4-8d4c-4b3c-b705-378a47df84bc.png&w=384&q=75'
						StaticText Novo
						button adicionar
						image Quitanda Tomio, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff3f52d51-ee7d-416c-9412-f4309622c33c.png&w=32&q=75'
						StaticText Quitanda Tomio
						heading Uva thompson 500g
				listitem
					link Bold Pistache 60g adicionar Bold Snacks Bold Snacks Bold Pistache 60g R$ 12,99, url='https://trela.com.br/produto/bold-pistache-60g-13725'
						image Bold Pistache 60g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F2f0c45f3-2f91-423c-bae8-5b30261e7521.png&w=384&q=75'
						button adicionar
						image Bold Snacks, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fe5a2a990-ab70-4739-936d-cec364fa7cee.png&w=32&q=75'
						StaticText Bold Snacks
						heading Bold Pistache 60g
				listitem
					link Barra vegana almond chocolat com 20g de proteína adicionar Hart's Natural Hart's Natural Barra vegana almond chocolat com 20g de proteína R$ 16,99, url='https://trela.com.br/produto/barra-vegana-almond-chocolat-com-20g-de-proteina-13819'
						image Barra vegana almond chocolat com 20g de proteína, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fe1a6ddd4-5b87-4790-a48b-9b259f50686f.png&w=384&q=75'
						button adicionar
						image Hart's Natural, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F173a7f1b-79b3-4878-bbdf-1382d515e434.png&w=32&q=75'
						StaticText Hart's Natural
						heading Barra vegana almond chocolat com 20g de proteína
			button próximos itens
		region Especiais de fim de ano Ver categoria
			heading Especiais de fim de ano
			link Ver categoria, url='https://trela.com.br/categoria/especiais-de-fim-de-ano-1156'
			list
				listitem
					link Azeite de Oliva Trela Dia a dia - 500ml 15 adicionar Trela & Batalha Trela & Batalha Azeite de Oliva Trela Dia a dia - 500ml R$ 49,90, url='https://trela.com.br/produto/azeite-de-oliva-trela-dia-a-dia-500ml-13786'
						image Azeite de Oliva Trela Dia a dia - 500ml, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb7e172a8-07d3-4cbf-bdb0-6ea3cdfe7f2e.png&w=384&q=75'
						StaticText 15
						button adicionar
						image Trela & Batalha, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F22ba7181-e19d-46da-ba04-845c11b50a17.png&w=32&q=75'
						StaticText Trela & Batalha
						heading Azeite de Oliva Trela Dia a dia - 500ml
				listitem
					link Azeite de Oliva Trela Presenteável - 500ml 10 adicionar Trela & Batalha Trela & Batalha Azeite de Oliva Trela Presenteável - 500ml R$ 69,90, url='https://trela.com.br/produto/azeite-de-oliva-trela-presenteavel-500ml-13801'
						image Azeite de Oliva Trela Presenteável - 500ml, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F2a7176cf-8a09-494f-89ac-c36a6a0bfe79.png&w=384&q=75'
						StaticText 10
						button adicionar
						image Trela & Batalha, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F22ba7181-e19d-46da-ba04-845c11b50a17.png&w=32&q=75'
						StaticText Trela & Batalha
						heading Azeite de Oliva Trela Presenteável - 500ml
				listitem
					link Pão Integral com Semente de Abobora Grande 325g - Congelado 19 Congelado adicionar A Fornada A Fornada Pão Integral com Semente de Abobora Grande 325g - Congelado R$ 21,99, url='https://trela.com.br/produto/pao-integral-com-semente-de-abobora-grande-325g-congelado-8861'
						image Pão Integral com Semente de Abobora Grande 325g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fe0a42a27-6860-4874-9289-ada5a5763d0e-pa%CC%83ointegralcomsementedeaboboragrande-afornada-8861.1.png&w=384&q=75'
						StaticText 19
						StaticText Congelado
						button adicionar
						image A Fornada, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F4ac25824-c40a-4569-9485-047027515efc.png&w=32&q=75'
						StaticText A Fornada
						heading Pão Integral com Semente de Abobora Grande 325g - Congelado
				listitem
					link Figo roxo 350g 28  Ultrafresco adicionar Quitanda Tomio Quitanda Tomio Figo roxo 350g R$ 19,98 R$ 57,09/Kg, url='https://trela.com.br/produto/figo-roxo-350g-12326'
						image Figo roxo 350g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fd3979ccb-7253-499d-9f11-905cbd35f7cd.png&w=384&q=75'
						StaticText 28
						StaticText 
						StaticText Ultrafresco
						button adicionar
						image Quitanda Tomio, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff3f52d51-ee7d-416c-9412-f4309622c33c.png&w=32&q=75'
						StaticText Quitanda Tomio
						heading Figo roxo 350g
				listitem
					link Panetone de Frutas Vermelhas 650g Novo adicionar Dengo Chocolates Dengo Chocolates Panetone de Frutas Vermelhas 650g R$ 165,90, url='https://trela.com.br/produto/panetone-de-frutas-vermelhas-650g-13904'
						image Panetone de Frutas Vermelhas 650g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5190dad9-724b-4e71-adab-f56c94472ee7.png&w=384&q=75'
						StaticText Novo
						button adicionar
						image Dengo Chocolates, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F6467ad89-de90-46a3-9481-a92681324e5a.png&w=32&q=75'
						StaticText Dengo Chocolates
						heading Panetone de Frutas Vermelhas 650g
				listitem
					link Uva thompson 500g Novo adicionar Quitanda Tomio Quitanda Tomio Uva thompson 500g R$ 24,98, url='https://trela.com.br/produto/uva-thompson-500g-13784'
						image Uva thompson 500g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff15822a4-8d4c-4b3c-b705-378a47df84bc.png&w=384&q=75'
						StaticText Novo
						button adicionar
						image Quitanda Tomio, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff3f52d51-ee7d-416c-9412-f4309622c33c.png&w=32&q=75'
						StaticText Quitanda Tomio
						heading Uva thompson 500g
				listitem
					link Vinho Branco Somm 269ml 15 adicionar Somm Vinhos Somm Vinhos Vinho Branco Somm 269ml R$ 12,09, url='https://trela.com.br/produto/vinho-branco-somm-269ml-9296'
						image Vinho Branco Somm 269ml, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fd932cb5c-2a19-4b28-8b5f-eaa02772db63-vinhobrancosomml-sommvinhos-9296.1.png&w=384&q=75'
						StaticText 15
						button adicionar
						image Somm Vinhos, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F9c703719-fe42-4bca-81fe-b2217a9c5ad7.png&w=32&q=75'
						StaticText Somm Vinhos
						heading Vinho Branco Somm 269ml
				listitem
					link Vinho Rosé Somm 269ml 13 adicionar Somm Vinhos Somm Vinhos Vinho Rosé Somm 269ml R$ 10,99, url='https://trela.com.br/produto/vinho-rose-somm-269ml-9298'
						image Vinho Rosé Somm 269ml, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fa672dd92-bb45-439e-9b75-3a1a22bfca6d.png&w=384&q=75'
						StaticText 13
						button adicionar
						image Somm Vinhos, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F9c703719-fe42-4bca-81fe-b2217a9c5ad7.png&w=32&q=75'
						StaticText Somm Vinhos
						heading Vinho Rosé Somm 269ml
			button próximos itens
		region Queijos e laticínios Ver categoria
			heading Queijos e laticínios
			link Ver categoria, url='https://trela.com.br/categoria/queijos-e-laticinios-693'
			list
				listitem
					link Bebida de Aveia Orgânica Cremoso 1L 22 adicionar Nude - Bebidas Vegetais Nude - Bebidas Vegetais Bebida de Aveia Orgânica Cremoso 1L R$ 20,89, url='https://trela.com.br/produto/bebida-de-aveia-organica-cremoso-1l-6193'
						image Bebida de Aveia Orgânica Cremoso 1L, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ffcef395b-ae5c-4016-846d-670a3f84af07-bebidadeaveiaorg%C3%A2nicacremoso-nudebebidasvegetais-6193.1.png&w=384&q=75'
						StaticText 22
						button adicionar
						image Nude - Bebidas Vegetais, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fsuppliers%2F8830d02f-0c72-4225-b2ed-5bccd828428a.png&w=32&q=75'
						StaticText Nude - Bebidas Vegetais
						heading Bebida de Aveia Orgânica Cremoso 1L
				listitem
					link Iogurte Natural Desnatado 140g 32 Refrigerado adicionar Verde Campo Verde Campo Iogurte Natural Desnatado 140g R$ 2,99, url='https://trela.com.br/produto/iogurte-natural-desnatado-140g-12532'
						image Iogurte Natural Desnatado 140g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F6bfba75d-fa49-483e-8d24-925e38fc6fd8.png&w=384&q=75'
						StaticText 32
						StaticText Refrigerado
						button adicionar
						image Verde Campo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb045f0a8-3d1e-4064-9cc2-d188dfa19844.png&w=32&q=75'
						StaticText Verde Campo
						heading Iogurte Natural Desnatado 140g
				listitem
					link Queijo cottage 200g 51 Refrigerado adicionar Cruzília Cruzília Queijo cottage 200g R$ 10,90 R$ 9,27 -15%, url='https://trela.com.br/produto/queijo-cottage-200g-12211'
						image Queijo cottage 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc11f29bb-a64a-4222-a8c6-7bca76aa0b7f-cottage-cruzi%CC%81lia-12211.1.png&w=384&q=75'
						StaticText 51
						StaticText Refrigerado
						button adicionar
						image Cruzília, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5786d8f5-d4ca-41e6-980a-60bd819b961d.png&w=32&q=75'
						StaticText Cruzília
						heading Queijo cottage 200g
				listitem
					link Manteiga extra com flor de sal 200g 80 Refrigerado adicionar Xandô Xandô Manteiga extra com flor de sal 200g R$ 14,29, url='https://trela.com.br/produto/manteiga-extra-com-flor-de-sal-200g-10859'
						image Manteiga extra com flor de sal 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F45b00bb3-8856-454f-9764-624dff2a5aa6-manteigaextracomflordesal-xando%CC%82-10859.1.png&w=384&q=75'
						StaticText 80
						StaticText Refrigerado
						button adicionar
						image Xandô, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F77360f6b-5746-43ec-ae31-67d69718f6d1.png&w=32&q=75'
						StaticText Xandô
						heading Manteiga extra com flor de sal 200g
				listitem
					link Creme de leite - 200g 63 adicionar Leitíssimo Leitíssimo Creme de leite - 200g R$ 6,49, url='https://trela.com.br/produto/creme-de-leite-200g-9265'
						image Creme de leite - 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc8118dfb-3e75-4de6-9a54-65330c114ee8-cremedeleite-leiteleiti%CC%81ssimo-9265.1.png&w=384&q=75'
						StaticText 63
						button adicionar
						image Leitíssimo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F63190e43-d2eb-4a8c-be92-feb76aa7647a.png&w=32&q=75'
						StaticText Leitíssimo
						heading Creme de leite - 200g
				listitem
					link Leite integral UHT 1L 57 adicionar Leitíssimo Leitíssimo Leite integral UHT 1L R$ 10,79, url='https://trela.com.br/produto/leite-integral-uht-1l-9261'
						image Leite integral UHT 1L, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F49271048-b164-4002-89ed-dbabc994136f-leiteintegraluht-leiteleiti%CC%81ssimo-9261.1.png&w=384&q=75'
						StaticText 57
						button adicionar
						image Leitíssimo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F63190e43-d2eb-4a8c-be92-feb76aa7647a.png&w=32&q=75'
						StaticText Leitíssimo
						heading Leite integral UHT 1L
				listitem
					link Leite vegetal de amêndoas 1L 48 adicionar A Tal da Castanha A Tal da Castanha Leite vegetal de amêndoas 1L R$ 19,99, url='https://trela.com.br/produto/leite-vegetal-de-amendoas-1l-12567'
						image Leite vegetal de amêndoas 1L, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F1af7e39a-4efc-493a-8fcf-ad8efd53e6d9.png&w=384&q=75'
						StaticText 48
						button adicionar
						image A Tal da Castanha, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F030ecff6-4851-4aa9-9c64-6175dd789489.png&w=32&q=75'
						StaticText A Tal da Castanha
						heading Leite vegetal de amêndoas 1L
				listitem
					link Queijo macio Lua cheia 250g 114 Refrigerado adicionar Serra das Antas Serra das Antas Queijo macio Lua cheia 250g R$ 28,90, url='https://trela.com.br/produto/queijo-macio-lua-cheia-250g-11452'
						image Queijo macio Lua cheia 250g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F15a8bd2b-aade-46fe-abf1-8c69abd20487-queijoluacheia-serradasantas-11452.1.png&w=384&q=75'
						StaticText 114
						StaticText Refrigerado
						button adicionar
						image Serra das Antas, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5ec0e9df-8e01-4061-886d-0ff47aede47f.png&w=32&q=75'
						StaticText Serra das Antas
						heading Queijo macio Lua cheia 250g
			button próximos itens
		region Hortifruti e ovos Ver categoria
			heading Hortifruti e ovos
			link Ver categoria, url='https://trela.com.br/categoria/hortifruti-e-ovos-662'
			list
				listitem
					link Figo roxo 350g 28  Ultrafresco adicionar Quitanda Tomio Quitanda Tomio Figo roxo 350g R$ 19,98 R$ 57,09/Kg, url='https://trela.com.br/produto/figo-roxo-350g-12326'
						image Figo roxo 350g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fd3979ccb-7253-499d-9f11-905cbd35f7cd.png&w=384&q=75'
						StaticText 28
						StaticText 
						StaticText Ultrafresco
						button adicionar
						image Quitanda Tomio, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff3f52d51-ee7d-416c-9412-f4309622c33c.png&w=32&q=75'
						StaticText Quitanda Tomio
						heading Figo roxo 350g
				listitem
					link Uva thompson 500g Novo adicionar Quitanda Tomio Quitanda Tomio Uva thompson 500g R$ 24,98, url='https://trela.com.br/produto/uva-thompson-500g-13784'
						image Uva thompson 500g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff15822a4-8d4c-4b3c-b705-378a47df84bc.png&w=384&q=75'
						StaticText Novo
						button adicionar
						image Quitanda Tomio, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff3f52d51-ee7d-416c-9412-f4309622c33c.png&w=32&q=75'
						StaticText Quitanda Tomio
						heading Uva thompson 500g
				listitem
					link Edamame em grãos 300g 64 Congelado adicionar Repeat Foods Repeat Foods Edamame em grãos 300g R$ 15,99, url='https://trela.com.br/produto/edamame-em-graos-300g-10498'
						image Edamame em grãos 300g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F53b8ad01-c280-42b5-90b1-df13386c76cf-edamamegra%CC%83os-repeatfoods-10498.1.png&w=384&q=75'
						StaticText 64
						StaticText Congelado
						button adicionar
						image Repeat Foods, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fe9c71f8d-6813-4ba4-b30c-6c914867166b.png&w=32&q=75'
						StaticText Repeat Foods
						heading Edamame em grãos 300g
				listitem
					link Tomate Cereja Orgânico 250g 63  Ultrafresco adicionar AXÁ Orgânicos AXÁ Orgânicos Tomate Cereja Orgânico 250g R$ 6,10, url='https://trela.com.br/produto/tomate-cereja-organico-250g-13606'
						image Tomate Cereja Orgânico 250g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fa42b4de2-ea71-41cb-9d8d-811017af13cc.png&w=384&q=75'
						StaticText 63
						StaticText 
						StaticText Ultrafresco
						button adicionar
						image AXÁ Orgânicos, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F01b9b2a8-353d-41de-a7c9-03f080f4789b.png&w=32&q=75'
						StaticText AXÁ Orgânicos
						heading Tomate Cereja Orgânico 250g
				listitem
					link Banana prata orgânica 800g 141  Ultrafresco adicionar AXÁ Orgânicos AXÁ Orgânicos Banana prata orgânica 800g R$ 10,03 R$ 12,54/Kg, url='https://trela.com.br/produto/banana-prata-organica-800g-6673'
						image Banana prata orgânica 800g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb57c55a8-b8c0-40f6-a18c-0f937fb29207-bananaprataorga%CC%82nica-axa%CC%81orga%CC%82nico-6673.1.png&w=384&q=75'
						StaticText 141
						StaticText 
						StaticText Ultrafresco
						button adicionar
						image AXÁ Orgânicos, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F01b9b2a8-353d-41de-a7c9-03f080f4789b.png&w=32&q=75'
						StaticText AXÁ Orgânicos
						heading Banana prata orgânica 800g
				listitem
					link Ovos caipiras grandes Korin sem transgênicos 10 unidades 150 adicionar Korin Alimentos Korin Alimentos Ovos caipiras grandes Korin sem transgênicos 10 unidades R$ 18,00, url='https://trela.com.br/produto/ovos-caipiras-grandes-korin-sem-transgenicos-10-unidades-6751'
						image Ovos caipiras grandes Korin sem transgênicos 10 unidades, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F44ba4c64-0051-4287-b6b6-fe4b43b4465c-ovoscaipirasgrandeskorins_transge%CC%82nicos-korinalimentos-6751.1.png&w=384&q=75'
						StaticText 150
						button adicionar
						image Korin Alimentos, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fsuppliers%2F46807b00-18f7-4276-91fb-a914fa115074.jpg&w=32&q=75'
						StaticText Korin Alimentos
						heading Ovos caipiras grandes Korin sem transgênicos 10 unidades
				listitem
					link Cebola 500g 66  Ultrafresco adicionar Quitanda Tomio Quitanda Tomio Cebola 500g R$ 5,00 R$ 10,00/Kg, url='https://trela.com.br/produto/cebola-500g-12185'
						image Cebola 500g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ffcaf5c30-1a15-470f-a216-4753c77ce3da-cebola-quitandatomio-12185.1.png&w=384&q=75'
						StaticText 66
						StaticText 
						StaticText Ultrafresco
						button adicionar
						image Quitanda Tomio, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff3f52d51-ee7d-416c-9412-f4309622c33c.png&w=32&q=75'
						StaticText Quitanda Tomio
						heading Cebola 500g
				listitem
					link Cogumelo shimeji negro 200g 94  Ultrafresco adicionar Fungo de Quintal Fungo de Quintal Cogumelo shimeji negro 200g R$ 15,17 R$ 75,85/Kg, url='https://trela.com.br/produto/cogumelo-shimeji-negro-200g-2257'
						image Cogumelo shimeji negro 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F64aee64d-a698-4568-a16a-582407abbf97-cogumeloshimejinegro-fungodequintal-2257.1.png&w=384&q=75'
						StaticText 94
						StaticText 
						StaticText Ultrafresco
						button adicionar
						image Fungo de Quintal, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fzapt-app-compressed.s3.sa-east-1.amazonaws.com%2Fprod%2Fbundles%2Fd1df331e-5d80-41de-a8c7-7bbba3f7d8cb.jpeg&w=32&q=75'
						StaticText Fungo de Quintal
						heading Cogumelo shimeji negro 200g
			button próximos itens
		region Carnes Ver categoria
			heading Carnes
			link Ver categoria, url='https://trela.com.br/categoria/carnes-622'
			list
				listitem
					link Filé de peito de frango Korin 600g - Congelado 104 Congelado adicionar Korin Alimentos Korin Alimentos Filé de peito de frango Korin 600g - Congelado R$ 27,59 R$ 45,98/Kg, url='https://trela.com.br/produto/file-de-peito-de-frango-korin-600g-congelado-6745'
						image Filé de peito de frango Korin 600g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fdadeb4d4-9ed6-41ea-a3b0-7e1a00d66a53.png&w=384&q=75'
						StaticText 104
						StaticText Congelado
						button adicionar
						image Korin Alimentos, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fsuppliers%2F46807b00-18f7-4276-91fb-a914fa115074.jpg&w=32&q=75'
						StaticText Korin Alimentos
						heading Filé de peito de frango Korin 600g - Congelado
				listitem
					link Carne moída de patinho 420g 64 Congelado adicionar DeBetti DeBetti Carne moída de patinho 420g R$ 27,90 R$ 66,43/Kg, url='https://trela.com.br/produto/carne-moida-de-patinho-420g-12824'
						image Carne moída de patinho 420g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fe6c695ed-be5d-4ad4-8bc1-74644f60cb51-carnemoi%CC%81dadepatinho-debetti-12824.1.png&w=384&q=75'
						StaticText 64
						StaticText Congelado
						button adicionar
						image DeBetti, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff5435133-624f-4215-b96d-9d9d583c9a94.png&w=32&q=75'
						StaticText DeBetti
						heading Carne moída de patinho 420g
				listitem
					link Carne moída orgânica 400gr - Congelado 23 Congelado adicionar Natural Meat Natural Meat Carne moída orgânica 400gr - Congelado R$ 32,90 R$ 82,25/Kg, url='https://trela.com.br/produto/carne-moida-organica-400gr-congelado-10321'
						image Carne moída orgânica 400gr - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F270fcb3b-fa02-4d2d-abdf-45b889968a86-carnemoi%CC%81daorga%CC%82nicalightr-naturalmeat-10321.1.png&w=384&q=75'
						StaticText 23
						StaticText Congelado
						button adicionar
						image Natural Meat, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fsuppliers%2F17efa277-558b-45e9-8dce-1e692f2cb1ab.png&w=32&q=75'
						StaticText Natural Meat
						heading Carne moída orgânica 400gr - Congelado
				listitem
					link Filé de peito orgânico sem osso 600g - Congelado 43 Congelado adicionar Korin Alimentos Korin Alimentos Filé de peito orgânico sem osso 600g - Congelado R$ 37,29 R$ 62,15/Kg, url='https://trela.com.br/produto/file-de-peito-organico-sem-osso-600g-congelado-12678'
						image Filé de peito orgânico sem osso 600g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fa2b63a16-98e9-4dd4-9fa4-521642565055-file%CC%81depeitodefrango-korinalimentos-12678.1.png&w=384&q=75'
						StaticText 43
						StaticText Congelado
						button adicionar
						image Korin Alimentos, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fsuppliers%2F46807b00-18f7-4276-91fb-a914fa115074.jpg&w=32&q=75'
						StaticText Korin Alimentos
						heading Filé de peito orgânico sem osso 600g - Congelado
				listitem
					link Tofu orgânico natural 1kg 42  Ultrafresco adicionar SÍtio Boa Esperança SÍtio Boa Esperança Tofu orgânico natural 1kg R$ 54,90, url='https://trela.com.br/produto/tofu-organico-natural-1kg-11582'
						image Tofu orgânico natural 1kg, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F6131f558-4399-4d15-ab54-79ca99e1221b.png&w=384&q=75'
						StaticText 42
						StaticText 
						StaticText Ultrafresco
						button adicionar
						image SÍtio Boa Esperança, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F80eedb37-bb57-4585-81c1-086cdfa83a60.png&w=32&q=75'
						StaticText SÍtio Boa Esperança
						heading Tofu orgânico natural 1kg
				listitem
					link Filé Mignon Suíno 460g - Congelado 23 Congelado adicionar VPJ VPJ Filé Mignon Suíno 460g - Congelado R$ 21,00 R$ 45,65/Kg, url='https://trela.com.br/produto/file-mignon-suino-460g-congelado-11455'
						image Filé Mignon Suíno 460g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5fb517c0-a33a-4c81-8121-8d82108abc49-file%CC%81mignonsui%CC%81no-vpj-11455.1.png&w=384&q=75'
						StaticText 23
						StaticText Congelado
						button adicionar
						image VPJ, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F44f55735-013b-48ee-a8d0-1219dc48cc01.png&w=32&q=75'
						StaticText VPJ
						heading Filé Mignon Suíno 460g - Congelado
				listitem
					link Hambúrguer Sheik 240g (2un de 120g) - Congelado 23 Congelado adicionar DeBetti DeBetti Hambúrguer Sheik 240g (2un de 120g) - Congelado R$ 15,90 R$ 66,25/Kg, url='https://trela.com.br/produto/hamburguer-sheik-240g-2un-de-120g-congelado-11134'
						image Hambúrguer Sheik 240g (2un de 120g) - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F995722a3-eb87-4da9-8824-ee0f1bbbb936-hambu%CC%81rguersheik-debetti-11134.1.png&w=384&q=75'
						StaticText 23
						StaticText Congelado
						button adicionar
						image DeBetti, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff5435133-624f-4215-b96d-9d9d583c9a94.png&w=32&q=75'
						StaticText DeBetti
						heading Hambúrguer Sheik 240g (2un de 120g) - Congelado
				listitem
					link Linguiça suína em gomos grossa 400g - Refrigerado 24 Refrigerado adicionar Porco Real Porco Real Linguiça suína em gomos grossa 400g - Refrigerado R$ 24,90, url='https://trela.com.br/produto/linguica-suina-em-gomos-grossa-400g-refrigerado-12588'
						image Linguiça suína em gomos grossa 400g - Refrigerado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F3f9fd8c5-d834-4fcd-b2ff-7d94498f39e7-lingui%C3%A7asu%C3%ADnaemgomosgrossa-porcoreal-12588.1.png&w=384&q=75'
						StaticText 24
						StaticText Refrigerado
						button adicionar
						image Porco Real, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fd7e5dbc1-66c3-4da8-b1a6-d88d4e914929.png&w=32&q=75'
						StaticText Porco Real
						heading Linguiça suína em gomos grossa 400g - Refrigerado
			button próximos itens
	contentinfo
		region Categorias
			list
				listitem
					link Oferta do Dia até 15% OFF, url='https://trela.com.br/categoria/oferta-do-dia-ate-15-off-180'
				listitem
					link Selecionados para você, url='https://trela.com.br/categoria/selecionados-para-voce-1097'
				listitem
					link Novos na Trela, url='https://trela.com.br/categoria/novos-na-trela-298'
				listitem
					link Especiais de fim de ano, url='https://trela.com.br/categoria/especiais-de-fim-de-ano-1156'
				listitem
					link Hortifruti e ovos, url='https://trela.com.br/categoria/hortifruti-e-ovos-662'
				listitem
					link Queijos e laticínios, url='https://trela.com.br/categoria/queijos-e-laticinios-693'
				listitem
					link Básicos da despensa, url='https://trela.com.br/categoria/basicos-da-despensa-587'
				listitem
					link Carnes, url='https://trela.com.br/categoria/carnes-622'
				listitem
					link Peixes e frutos do mar, url='https://trela.com.br/categoria/peixes-e-frutos-do-mar-681'
				listitem
					link Frios e charcutaria, url='https://trela.com.br/categoria/frios-e-charcutaria-654'
				listitem
					link Padaria e confeitaria, url='https://trela.com.br/categoria/padaria-e-confeitaria-673'
				listitem
					link Refeições práticas, url='https://trela.com.br/categoria/refeicoes-praticas-565'
				listitem
					link Salgados e tortas, url='https://trela.com.br/categoria/salgados-e-tortas-727'
				listitem
					link Pizzas e massas, url='https://trela.com.br/categoria/pizzas-e-massas-686'
				listitem
					link Antepastos e molhos, url='https://trela.com.br/categoria/antepastos-e-molhos-578'
				listitem
					link Castanhas e frutas secas, url='https://trela.com.br/categoria/castanhas-e-frutas-secas-634'
				listitem
					link Snacks, url='https://trela.com.br/categoria/snacks-733'
				listitem
					link Suplementos, url='https://trela.com.br/categoria/suplementos-747'
				listitem
					link Doces e chocolates, url='https://trela.com.br/categoria/doces-e-chocolates-645'
				listitem
					link Sorvetes e açaí, url='https://trela.com.br/categoria/sorvetes-e-acai-742'
				listitem
					link Bebidas, url='https://trela.com.br/categoria/bebidas-599'
				listitem
					link Cafés e Chás, url='https://trela.com.br/categoria/cafes-e-chas-611'
				listitem
					link Cervejas e destilados, url='https://trela.com.br/categoria/cervejas-e-destilados-641'
				listitem
					link Vinhos e espumantes, url='https://trela.com.br/categoria/vinhos-e-espumantes-758'
				listitem
					link Plant-Based, url='https://trela.com.br/categoria/plantbased-224'
		region Sobre a Trela
			list
				listitem
					link Quem somos, url='https://trela.com.br/institucional/quem-somos'
				listitem
					link Carreiras, url='https://jobs.lever.co/trela'
				listitem
					link Dúvidas Frequentes, url='https://trela.com.br/institucional/duvidas-frequentes'
				listitem
					link Política de Privacidade, url='https://trela.com.br/institucional/politica-de-privacidade'
				listitem
					link Termos e condições, url='https://trela.com.br/institucional/termos-de-uso'
				listitem
					link Seja um parceiro, url='https://form.typeform.com/to/MGXdfqU0'
				listitem
					link Entre em contato, url='http://suporte.trela.com.br/'
		region Métodos de pagamento
			list
				listitem
					image logo pix, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-pix.png&w=1920&q=75'
				listitem
					image logo visa, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-visa.png&w=1920&q=75'
				listitem
					image logo mastercard, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-mastercard.png&w=1920&q=75'
				listitem
					image logo diners-club, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-diners-club.png&w=1920&q=75'
				listitem
					image logo american-express, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-american-express.png&w=1920&q=75'
				listitem
					image logo hipercard, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-hipercard.png&w=1920&q=75'
				listitem
					image logo discover, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-discover.png&w=1920&q=75'
				listitem
					image logo elo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-elo.png&w=1920&q=75'
				listitem
					image logo vr, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-vr.png&w=1920&q=75'
				listitem
					image logo sodexo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-sodexo.png&w=1920&q=75'
				listitem
					image logo ticket, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-ticket.png&w=1920&q=75'
				listitem
					image logo caju, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-caju.png&w=1920&q=75'
		separator, orientation='horizontal'
		region Nunca perca uma oferta, baixe o app da Trela
			link Disponível no Google Play, url='https://play.google.com/store/apps/details?id=com.trela.br.marketplace&hl=pt_BR&gl=US'
				image Disponível no Google Play, url='https://trela.com.br/_next/image?url=%2Fimages%2Fgoogle-play.png&w=256&q=75'
			link Disponível na App Store, url='https://apps.apple.com/br/app/trela/id6444369623'
				image Disponível na App Store, url='https://trela.com.br/_next/image?url=%2Fimages%2Fapp-store.png&w=256&q=75'
		separator, orientation='horizontal'
		image Trela
		list
			listitem
				link instagram logo, url='https://www.instagram.com/trela'
					image instagram logo, url='https://d29vvterh1pj9i.cloudfront.net/instagram_57e7afd553.svg'
			listitem
				link linkedin logo, url='https://www.linkedin.com/company/deutrela'
					image linkedin logo, url='https://d29vvterh1pj9i.cloudfront.net/linkedin_ce1dd8540e.svg'
			listitem
				link tiktok logo, url='https://www.tiktok.com/@trelaoficial'
					image tiktok logo, url='https://d29vvterh1pj9i.cloudfront.net/tiktok_443444b5cd.svg'
		StaticText Zapt Tecnologia LTDA CNPJ - 37.896.391/0001-84
	alert, atomic
```
</details>



```
RootWebArea Oferta do Dia até 15% OFF | Trela, focused, url='https://trela.com.br/categoria/oferta-do-dia-ate-15-off-180'
	banner
		navigation
			[2977] link Trela, center=(335,30), url='https://trela.com.br/'
				image Trela
```
<details><summary>Show more</summary>

```
			[2982] textbox O que você está procurando?, center=(960,30), contenteditable=True
			[2984] link Entrar / Cadastrar, center=(1496,30), url='https://trela.com.br/login?callbackUrl=%2Fcategoria%2Foferta-do-dia-ate-15-off-180'
			[2986] button Menu, center=(1602,30)
	main
		heading Oferta do Dia até 15% OFF
		navigation
			region lista de categorias
				list
					listitem
						article
							[3018] link Oferta do Dia até 15% OFF, center=(446,98), url='https://trela.com.br/categoria/oferta-do-dia-ate-15-off-180'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F00180a97-33f3-4eb4-923d-eee91d4cbaa0.png&w=96&q=75'
							[3022] button compartilhar, center=(542,98)
					listitem
						article
							[3026] link Selecionados para você, center=(647,98), url='https://trela.com.br/categoria/selecionados-para-voce-1097'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fea58f86c-8199-4cd3-a72b-dd34789b4f3e.png&w=96&q=75'
					listitem
						article
							[3032] link Novos na Trela, center=(818,98), url='https://trela.com.br/categoria/novos-na-trela-298'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F631f48a8-7c0d-41a0-a6af-0d75ce1dc13c.png&w=96&q=75'
					listitem
						article
							[3038] link Especiais de fim de ano, center=(990,98), url='https://trela.com.br/categoria/especiais-de-fim-de-ano-1156'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F12e2c830-329b-4add-8356-58de664609ab.png&w=96&q=75'
					listitem
						article
							[3044] link Hortifruti e ovos, center=(1161,98), url='https://trela.com.br/categoria/hortifruti-e-ovos-662'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F8c170965-16cd-4531-8023-c433f1af7c70.png&w=96&q=75'
					listitem
						article
							[3050] link Queijos e laticínios, center=(1333,98), url='https://trela.com.br/categoria/queijos-e-laticinios-693'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fc49fcac4-9824-422c-a80e-babc86875214.png&w=96&q=75'
					listitem
						article
							[3056] link Básicos da despensa, center=(1504,98), url='https://trela.com.br/categoria/basicos-da-despensa-587'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F198dc6a8-b72d-40e6-bdf8-1e28ad8e3b80.png&w=96&q=75'
					listitem
						article
							link Carnes, url='https://trela.com.br/categoria/carnes-622'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F721a0006-f25a-421d-8af9-19b5a20980a5.png&w=96&q=75'
					listitem
						article
							link Peixes e frutos do mar, url='https://trela.com.br/categoria/peixes-e-frutos-do-mar-681'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F8657ee04-91e3-4f37-a8a6-d10a73ae2a14.png&w=96&q=75'
					listitem
						article
							link Frios e charcutaria, url='https://trela.com.br/categoria/frios-e-charcutaria-654'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fc6d840c0-7077-43b8-829b-31bedd0de1d6.png&w=96&q=75'
					listitem
						article
							link Padaria e confeitaria, url='https://trela.com.br/categoria/padaria-e-confeitaria-673'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F5d90de96-9ae3-4c3d-b413-8b564d4a360e.png&w=96&q=75'
					listitem
						article
							link Refeições práticas, url='https://trela.com.br/categoria/refeicoes-praticas-565'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fe4aaba8f-397b-4aa3-beac-4b7dd89cb0ac.png&w=96&q=75'
					listitem
						article
							link Salgados e tortas, url='https://trela.com.br/categoria/salgados-e-tortas-727'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fc034a3b9-b196-4329-b332-3f93558df7d2.png&w=96&q=75'
					listitem
						article
							link Pizzas e massas, url='https://trela.com.br/categoria/pizzas-e-massas-686'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F0862abb7-d513-4c35-b983-e665616a748b.png&w=96&q=75'
					listitem
						article
							link Antepastos e molhos, url='https://trela.com.br/categoria/antepastos-e-molhos-578'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F13aa370a-7702-4aa9-988f-5d1dc141a3a9.png&w=96&q=75'
					listitem
						article
							link Castanhas e frutas secas, url='https://trela.com.br/categoria/castanhas-e-frutas-secas-634'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fb5798c8f-465e-45d1-aa06-0c67a7b55bc7.png&w=96&q=75'
					listitem
						article
							link Snacks, url='https://trela.com.br/categoria/snacks-733'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F2a5d617f-03a9-40bf-9df1-c3f4e37506d6.png&w=96&q=75'
					listitem
						article
							link Suplementos, url='https://trela.com.br/categoria/suplementos-747'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fda566dba-d86f-4f48-a463-ebdf864b09f2.png&w=96&q=75'
					listitem
						article
							link Doces e chocolates, url='https://trela.com.br/categoria/doces-e-chocolates-645'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fb4e1a295-beeb-4321-92fc-b15c08dfb512.png&w=96&q=75'
					listitem
						article
							link Sorvetes e açaí, url='https://trela.com.br/categoria/sorvetes-e-acai-742'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F26b77fa7-f6f9-4df0-b3d7-0f33bc40b6e0.png&w=96&q=75'
					listitem
						article
							link Bebidas, url='https://trela.com.br/categoria/bebidas-599'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F2ac71ac0-8ce3-4125-acd8-8510853260cf.png&w=96&q=75'
					listitem
						article
							link Cafés e Chás, url='https://trela.com.br/categoria/cafes-e-chas-611'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Feeb697f1-eaf4-4c9b-9673-fe0e1a219a89.png&w=96&q=75'
					listitem
						article
							link Cervejas e destilados, url='https://trela.com.br/categoria/cervejas-e-destilados-641'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fa79f76db-bf33-4c5e-8306-d89033c6c30e.png&w=96&q=75'
					listitem
						article
							link Vinhos e espumantes, url='https://trela.com.br/categoria/vinhos-e-espumantes-758'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F7261bc0b-70f9-4b92-ac31-92cb3b214579.png&w=48&q=75'
					listitem
						article
							link Plant-Based, url='https://trela.com.br/categoria/plantbased-224'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F7aac7d2e-64eb-44ef-954f-723aa42432bd.png&w=48&q=75'
				[3170] button próximos itens, center=(1588,98)
		heading Tudo
		navigation
			[3177] button Filtrar, center=(403,155)
			[3180] button Tudo, center=(491,155)
			separator, orientation='horizontal'
		[3188] link Queijo cottage 200g 51 Refrigerado adicionar Cruzília Cruzília Queijo cottage 200g R$ 10,90 R$ 9,27 -15%, center=(457,355), inner_text=51
Refrigerado
Cruzília
Queijo cottage 200g
R$ 10,90
R$ 9,27
-15%, url='https://trela.com.br/produto/queijo-cottage-200g-12211'
			image Queijo cottage 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc11f29bb-a64a-4222-a8c6-7bca76aa0b7f-cottage-cruzi%CC%81lia-12211.1.png&w=384&q=75'
			StaticText 51
			StaticText Refrigerado
			button adicionar
			image Cruzília, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5786d8f5-d4ca-41e6-980a-60bd819b961d.png&w=32&q=75'
			StaticText Cruzília
			heading Queijo cottage 200g
		[3215] link Pão sem glúten tradicional 500g - Congelado 19 Congelado adicionar Pão do Céu Pão do Céu Pão sem glúten tradicional 500g - Congelado R$ 20,90 R$ 17,77 -15%, center=(658,355), inner_text=19
Congelado
Pão do Céu
Pão sem glúten tradicional 500g - Congelado
R$ 20,90
R$ 17,77
-15%, url='https://trela.com.br/produto/pao-sem-gluten-tradicional-500g-congelado-12555'
			image Pão sem glúten tradicional 500g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F74dcb0e2-aa6c-4909-8d05-5ad41199945a.png&w=384&q=75'
			StaticText 19
			StaticText Congelado
			button adicionar
			image Pão do Céu, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F8c47b61c-1745-4522-a1c3-5e3592a4f157.png&w=32&q=75'
			StaticText Pão do Céu
			heading Pão sem glúten tradicional 500g - Congelado
		[3242] link Guacamole Sr. Guaca 200g 39 Refrigerado adicionar Sr. Guaca Sr. Guaca Guacamole Sr. Guaca 200g R$ 15,29 R$ 13,00 -15%, center=(859,355), inner_text=39
Refrigerado
Sr. Guaca
Guacamole Sr. Guaca 200g
R$ 15,29
R$ 13,00
-15%, url='https://trela.com.br/produto/guacamole-sr-guaca-200g-11448'
			image Guacamole Sr. Guaca 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F692edf71-8478-48b9-b4b5-dc3fe356a7ec-guacamolesrguaca-srguaca-11448.1.png&w=384&q=75'
			StaticText 39
			StaticText Refrigerado
			button adicionar
			image Sr. Guaca, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F6df05adb-ce6b-4c5b-9412-fac3eef999fe.png&w=32&q=75'
			StaticText Sr. Guaca
			heading Guacamole Sr. Guaca 200g
		[3269] link Suco de laranja 900ml 42 Refrigerado adicionar Xandô Xandô Suco de laranja 900ml R$ 15,90 R$ 13,52 -15%, center=(1061,355), inner_text=42
Refrigerado
Xandô
Suco de laranja 900ml
R$ 15,90
R$ 13,52
-15%, url='https://trela.com.br/produto/suco-de-laranja-900ml-10863'
			image Suco de laranja 900ml, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fd2cc0667-b893-4983-b41e-fcf7c6a60fcb-sucodelaranja-xando%CC%82-10863.1.png&w=384&q=75'
			StaticText 42
			StaticText Refrigerado
			button adicionar
			image Xandô, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F77360f6b-5746-43ec-ae31-67d69718f6d1.png&w=32&q=75'
			StaticText Xandô
			heading Suco de laranja 900ml
		[3296] link Iogurte Natural de Leite de Ovelha 140g 38 Refrigerado adicionar Queijaria Rima Queijaria Rima Iogurte Natural de Leite de Ovelha 140g R$ 6,12 R$ 5,20 -15%, center=(1262,355), inner_text=38
Refrigerado
Queijaria Rima
Iogurte Natural de Leite de Ovelha 140g
R$ 6,12
R$ 5,20
-15%, url='https://trela.com.br/produto/iogurte-natural-de-leite-de-ovelha-140g-11450'
			image Iogurte Natural de Leite de Ovelha 140g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F32111064-0b47-4689-9a9d-0d66b9bfac2e.png&w=384&q=75'
			StaticText 38
			StaticText Refrigerado
			button adicionar
			image Queijaria Rima, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fsuppliers%2F8265229b-2829-4816-9b2d-3d394b18628b.png&w=32&q=75'
			StaticText Queijaria Rima
			heading Iogurte Natural de Leite de Ovelha 140g
		[3323] link Pão 100% integral 450g - Congelado 24 Congelado adicionar Pão do Céu Pão do Céu Pão 100% integral 450g - Congelado R$ 18,40 R$ 15,64 -15%, center=(1463,355), inner_text=24
Congelado
Pão do Céu
Pão 100% integral 450g - Congelado
R$ 18,40
R$ 15,64
-15%, url='https://trela.com.br/produto/pao-100-integral-450g-congelado-12554'
			image Pão 100% integral 450g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fa8224eb4-7378-4a4f-98d8-fea03fed8bdc-p%C3%A3o100_integral-p%C3%A3odoc%C3%A9u-12554.1.png&w=384&q=75'
			StaticText 24
			StaticText Congelado
			button adicionar
			image Pão do Céu, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F8c47b61c-1745-4522-a1c3-5e3592a4f157.png&w=32&q=75'
			StaticText Pão do Céu
			heading Pão 100% integral 450g - Congelado
		[3351] link Natural Whey de Coco 21g de proteína - 250g 29 Refrigerado adicionar Verde Campo Verde Campo Natural Whey de Coco 21g de proteína - 250g R$ 8,69 R$ 7,39 -15%, center=(457,654), inner_text=29
Refrigerado
Verde Campo
Natural Whey de Coco 21g de proteína - 250g
R$ 8,69
R$ 7,39
-15%, url='https://trela.com.br/produto/natural-whey-de-coco-21g-de-proteina-250g-11527'
			image Natural Whey de Coco 21g de proteína - 250g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F0ce6f300-be4a-46c8-b164-58d6f7e9be3b.png&w=384&q=75'
			StaticText 29
			StaticText Refrigerado
			button adicionar
			image Verde Campo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb045f0a8-3d1e-4064-9cc2-d188dfa19844.png&w=32&q=75'
			StaticText Verde Campo
			heading Natural Whey de Coco 21g de proteína - 250g
		[3378] link Pão batata doce orgânico 450g - Congelado 25 Congelado adicionar Pão do Céu Pão do Céu Pão batata doce orgânico 450g - Congelado R$ 18,40 R$ 15,64 -15%, center=(658,658), inner_text=25
Congelado
Pão do Céu
Pão batata doce orgânico 450g - Congelado
R$ 18,40
R$ 15,64
-15%, url='https://trela.com.br/produto/pao-batata-doce-organico-450g-congelado-12553'
			image Pão batata doce orgânico 450g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fe63e8495-d4c3-4195-8228-5d9888b36cd3-p%C3%A3obatatadoceorg%C3%A2nico-p%C3%A3odoc%C3%A9u-12553.1.png&w=384&q=75'
			StaticText 25
			StaticText Congelado
			button adicionar
			image Pão do Céu, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F8c47b61c-1745-4522-a1c3-5e3592a4f157.png&w=32&q=75'
			StaticText Pão do Céu
			heading Pão batata doce orgânico 450g - Congelado
		[3405] link Yorgus grego desnatado natural 500g 22 Refrigerado adicionar Yorgus Yorgus Yorgus grego desnatado natural 500g R$ 29,90 R$ 25,42 -15%, center=(859,658), inner_text=22
Refrigerado
Yorgus
Yorgus grego desnatado natural 500g
R$ 29,90
R$ 25,42
-15%, url='https://trela.com.br/produto/yorgus-grego-desnatado-natural-500g-12905'
			image Yorgus grego desnatado natural 500g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fd1c5638d-0592-41b5-83f1-56c8747f5607.png&w=384&q=75'
			StaticText 22
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus grego desnatado natural 500g
		[3432] link Pão energia das sementes 380g - Congelado 11 Congelado adicionar House of Maya House of Maya Pão energia das sementes 380g - Congelado R$ 30,90 R$ 26,27 -15%, center=(1061,658), inner_text=11
Congelado
House of Maya
Pão energia das sementes 380g - Congelado
R$ 30,90
R$ 26,27
-15%, url='https://trela.com.br/produto/pao-energia-das-sementes-380g-congelado-12768'
			image Pão energia das sementes 380g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F96a16c52-2c24-46c2-8762-21db570a0b3d-p%C3%A3oenergiadassementes-houseofmaya-12768.1.png&w=384&q=75'
			StaticText 11
			StaticText Congelado
			button adicionar
			image House of Maya, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fdc9155eb-7b51-4963-b8d8-fbbb9e369d3d.png&w=32&q=75'
			StaticText House of Maya
			heading Pão energia das sementes 380g - Congelado
		[3459] link Tofu Orgânico Natural 450g - Refrigerado 13  Ultrafresco adicionar SÍtio Boa Esperança SÍtio Boa Esperança Tofu Orgânico Natural 450g - Refrigerado R$ 28,90 R$ 24,57 -15%, center=(1262,658), inner_text=13
Ultrafresco
SÍtio Boa Esperança
Tofu Orgânico Natural 450g - Refrigerado
R$ 28,90
R$ 24,57
-15%, url='https://trela.com.br/produto/tofu-organico-natural-450g-refrigerado-11583'
			image Tofu Orgânico Natural 450g - Refrigerado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F93093a13-4118-4fb4-b283-b652827a7d85-tofuorga%CC%82niconatural-si%CC%81tioboaesperanc%CC%A7a-11583.1.png&w=384&q=75'
			StaticText 13
			StaticText 
			StaticText Ultrafresco
			button adicionar
			image SÍtio Boa Esperança, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F80eedb37-bb57-4585-81c1-086cdfa83a60.png&w=32&q=75'
			StaticText SÍtio Boa Esperança
			heading Tofu Orgânico Natural 450g - Refrigerado
		[3486] link Bolo de limão siciliano e amêndoas 270g - Congelado Congelado adicionar House of Maya House of Maya Bolo de limão siciliano e amêndoas 270g - Congelado R$ 25,90 R$ 22,02 -15%, center=(1463,658), inner_text=Congelado
House of Maya
Bolo de limão siciliano e amêndoas 270g - Congelado
R$ 25,90
R$ 22,02
-15%, url='https://trela.com.br/produto/bolo-de-limao-siciliano-e-amendoas-270g-congelado-12765'
			image Bolo de limão siciliano e amêndoas 270g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F4b5758a7-3cb8-4c51-9db5-1eb34a276843-bolodelim%C3%A3osicilianoeam%C3%AAndoas-houseofmaya-12765.1.png&w=384&q=75'
			StaticText Congelado
			button adicionar
			image House of Maya, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fdc9155eb-7b51-4963-b8d8-fbbb9e369d3d.png&w=32&q=75'
			StaticText House of Maya
			heading Bolo de limão siciliano e amêndoas 270g - Congelado
		[3511] link Yorgus grego natural 0% gordura 130g 15 Refrigerado adicionar Yorgus Yorgus Yorgus grego natural 0% gordura 130g R$ 8,49 R$ 7,22 -15%, center=(457,961), inner_text=15
Refrigerado
Yorgus
Yorgus grego natural 0% gordura 130g
R$ 8,49
R$ 7,22
-15%, url='https://trela.com.br/produto/yorgus-grego-natural-0-gordura-130g-11531'
			image Yorgus grego natural 0% gordura 130g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff4f3624a-a448-44e1-936e-50984edb5ae5-yorgusgregonatural0_gordura-yorgus-11531.1.png&w=384&q=75'
			StaticText 15
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus grego natural 0% gordura 130g
		[3538] link Iogurte de Mel 170ml 38 Refrigerado adicionar Delicari Delicari Iogurte de Mel 170ml R$ 7,10 R$ 6,04 -15%, center=(658,961), inner_text=38
Refrigerado
Delicari
Iogurte de Mel 170ml
R$ 7,10
R$ 6,04
-15%, url='https://trela.com.br/produto/iogurte-de-mel-170ml-9252'
			image Iogurte de Mel 170ml, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F61c7e0ba-8841-481d-89ca-56f2b59d1d02-iogurtedemell-delicari-9252.1.png&w=384&q=75'
			StaticText 38
			StaticText Refrigerado
			button adicionar
			image Delicari, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F2403b2c8-dce9-4d5c-846b-0ff0be5d1868.png&w=32&q=75'
			StaticText Delicari
			heading Iogurte de Mel 170ml
		[3565] link Ovos caipiras com ômega 3 orgânicos 10 Unidades 22 adicionar Fazenda da Toca Fazenda da Toca Ovos caipiras com ômega 3 orgânicos 10 Unidades R$ 15,29 R$ 13,00 -15%, center=(859,961), inner_text=22
Fazenda da Toca
Ovos caipiras com ômega 3 orgânicos 10 Unidades
R$ 15,29
R$ 13,00
-15%, url='https://trela.com.br/produto/ovos-caipiras-com-omega-3-organicos-10-unidades-13294'
			image Ovos caipiras com ômega 3 orgânicos 10 Unidades, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb10cacb8-9748-43c8-8724-ada849cce6d9.png&w=384&q=75'
			StaticText 22
			button adicionar
			image Fazenda da Toca, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F4a8a125a-4069-4776-b8dc-a16acbd5e4a3.png&w=32&q=75'
			StaticText Fazenda da Toca
			heading Ovos caipiras com ômega 3 orgânicos 10 Unidades
		[3587] link Yorgus desnatado com mel silvestre orgânico 130g 13 Refrigerado adicionar Yorgus Yorgus Yorgus desnatado com mel silvestre orgânico 130g R$ 8,49 R$ 7,22 -15%, center=(1061,961), inner_text=13
Refrigerado
Yorgus
Yorgus desnatado com mel silvestre orgânico 130g
R$ 8,49
R$ 7,22
-15%, url='https://trela.com.br/produto/yorgus-desnatado-com-mel-silvestre-organico-130g-12904'
			image Yorgus desnatado com mel silvestre orgânico 130g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F620fcaa6-9327-4207-8d93-93ef0b5c7434-yorgusdesnatadocommelsilvestreorga%CC%82nico-yorgus-12904.1.png&w=384&q=75'
			StaticText 13
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus desnatado com mel silvestre orgânico 130g
		[3614] link Ovos caipiras orgânicos 18 Unidades 19 adicionar Fazenda da Toca Fazenda da Toca Ovos caipiras orgânicos 18 Unidades R$ 27,89 R$ 23,71 -15%, center=(1262,961), inner_text=19
Fazenda da Toca
Ovos caipiras orgânicos 18 Unidades
R$ 27,89
R$ 23,71
-15%, url='https://trela.com.br/produto/ovos-caipiras-organicos-18-unidades-13295'
			image Ovos caipiras orgânicos 18 Unidades, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F4376eae7-dffe-4492-93e1-5a7ef27e4815.png&w=384&q=75'
			StaticText 19
			button adicionar
			image Fazenda da Toca, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F4a8a125a-4069-4776-b8dc-a16acbd5e4a3.png&w=32&q=75'
			StaticText Fazenda da Toca
			heading Ovos caipiras orgânicos 18 Unidades
		[3636] link Iogurte de morango Lacfree 500g 21 Refrigerado adicionar Verde Campo Verde Campo Iogurte de morango Lacfree 500g R$ 8,50 R$ 7,23 -15%, center=(1463,961), inner_text=21
Refrigerado
Verde Campo
Iogurte de morango Lacfree 500g
R$ 8,50
R$ 7,23
-15%, url='https://trela.com.br/produto/iogurte-de-morango-lacfree-500g-11523'
			image Iogurte de morango Lacfree 500g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc5c76417-6de9-4eb4-b8e9-2b5b679b096f.png&w=384&q=75'
			StaticText 21
			StaticText Refrigerado
			button adicionar
			image Verde Campo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb045f0a8-3d1e-4064-9cc2-d188dfa19844.png&w=32&q=75'
			StaticText Verde Campo
			heading Iogurte de morango Lacfree 500g
		link Natural Whey de Banana 14g de proteína - 250g 19 Refrigerado adicionar Verde Campo Verde Campo Natural Whey de Banana 14g de proteína - 250g R$ 7,90 R$ 6,72 -15%, url='https://trela.com.br/produto/natural-whey-de-banana-14g-de-proteina-250g-11525'
			image Natural Whey de Banana 14g de proteína - 250g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F0a78e758-8483-4d8c-b1fb-b1b506197a37.png&w=384&q=75'
			StaticText 19
			StaticText Refrigerado
			button adicionar
			image Verde Campo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb045f0a8-3d1e-4064-9cc2-d188dfa19844.png&w=32&q=75'
			StaticText Verde Campo
			heading Natural Whey de Banana 14g de proteína - 250g
		link Yorgus grego integral de baunilha 130g Refrigerado adicionar Yorgus Yorgus Yorgus grego integral de baunilha 130g R$ 8,49 R$ 7,22 -15%, url='https://trela.com.br/produto/yorgus-grego-integral-de-baunilha-130g-11536'
			image Yorgus grego integral de baunilha 130g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5beb0575-f7fc-47e9-b20b-48077690d0b4-yorgusgregointegraldebaunilha-yorgus-11536.1.png&w=384&q=75'
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus grego integral de baunilha 130g
		link Yorgus grego de frutas silvestres 130g 19 Refrigerado adicionar Yorgus Yorgus Yorgus grego de frutas silvestres 130g R$ 8,49 R$ 7,22 -15%, url='https://trela.com.br/produto/yorgus-grego-de-frutas-silvestres-130g-11534'
			image Yorgus grego de frutas silvestres 130g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F7281bf48-4d8f-4df3-aca0-190f180d84ae-yorgusgregodefrutassilvestres-yorgus-11534.1.png&w=384&q=75'
			StaticText 19
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus grego de frutas silvestres 130g
		link Yorgus completo de frutas silvestres 250g 19 Refrigerado adicionar Yorgus Yorgus Yorgus completo de frutas silvestres 250g R$ 12,49 R$ 10,62 -15%, url='https://trela.com.br/produto/yorgus-completo-de-frutas-silvestres-250g-11540'
			image Yorgus completo de frutas silvestres 250g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fdb8b1b05-fce2-4acb-88f5-0620f58c87db-yorguscompletodefrutassilvestres-yorgus-11540.1.png&w=384&q=75'
			StaticText 19
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus completo de frutas silvestres 250g
		link Yorgus completo de baunilha 250g Refrigerado adicionar Yorgus Yorgus Yorgus completo de baunilha 250g R$ 12,49 R$ 10,62 -15%, url='https://trela.com.br/produto/yorgus-completo-de-baunilha-250g-11538'
			image Yorgus completo de baunilha 250g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F754021ad-2e7f-4dcc-99ac-0bf81d4f2c53-yorguscompletodebaunilha-yorgus-11538.1.png&w=384&q=75'
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus completo de baunilha 250g
		link Yorgus grego integral de coco 130g 14 Refrigerado adicionar Yorgus Yorgus Yorgus grego integral de coco 130g R$ 8,49 R$ 7,22 -15%, url='https://trela.com.br/produto/yorgus-grego-integral-de-coco-130g-11537'
			image Yorgus grego integral de coco 130g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5acc7a4c-efb3-4e14-bc0c-db71bd0f0426-yorgusgregointegraldecoco-yorgus-11537.1.png&w=384&q=75'
			StaticText 14
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus grego integral de coco 130g
	navigation breadcrumb
		list
			listitem
				link Início, url='https://trela.com.br/'
			listitem
				StaticText /
				link Categorias, url='https://trela.com.br/categoria'
			listitem
				StaticText /
				StaticText Oferta do Dia até 15% OFF
	contentinfo
		region Categorias
			list
				listitem
					link Oferta do Dia até 15% OFF, url='https://trela.com.br/categoria/oferta-do-dia-ate-15-off-180'
				listitem
					link Selecionados para você, url='https://trela.com.br/categoria/selecionados-para-voce-1097'
				listitem
					link Novos na Trela, url='https://trela.com.br/categoria/novos-na-trela-298'
				listitem
					link Especiais de fim de ano, url='https://trela.com.br/categoria/especiais-de-fim-de-ano-1156'
				listitem
					link Hortifruti e ovos, url='https://trela.com.br/categoria/hortifruti-e-ovos-662'
				listitem
					link Queijos e laticínios, url='https://trela.com.br/categoria/queijos-e-laticinios-693'
				listitem
					link Básicos da despensa, url='https://trela.com.br/categoria/basicos-da-despensa-587'
				listitem
					link Carnes, url='https://trela.com.br/categoria/carnes-622'
				listitem
					link Peixes e frutos do mar, url='https://trela.com.br/categoria/peixes-e-frutos-do-mar-681'
				listitem
					link Frios e charcutaria, url='https://trela.com.br/categoria/frios-e-charcutaria-654'
				listitem
					link Padaria e confeitaria, url='https://trela.com.br/categoria/padaria-e-confeitaria-673'
				listitem
					link Refeições práticas, url='https://trela.com.br/categoria/refeicoes-praticas-565'
				listitem
					link Salgados e tortas, url='https://trela.com.br/categoria/salgados-e-tortas-727'
				listitem
					link Pizzas e massas, url='https://trela.com.br/categoria/pizzas-e-massas-686'
				listitem
					link Antepastos e molhos, url='https://trela.com.br/categoria/antepastos-e-molhos-578'
				listitem
					link Castanhas e frutas secas, url='https://trela.com.br/categoria/castanhas-e-frutas-secas-634'
				listitem
					link Snacks, url='https://trela.com.br/categoria/snacks-733'
				listitem
					link Suplementos, url='https://trela.com.br/categoria/suplementos-747'
				listitem
					link Doces e chocolates, url='https://trela.com.br/categoria/doces-e-chocolates-645'
				listitem
					link Sorvetes e açaí, url='https://trela.com.br/categoria/sorvetes-e-acai-742'
				listitem
					link Bebidas, url='https://trela.com.br/categoria/bebidas-599'
				listitem
					link Cafés e Chás, url='https://trela.com.br/categoria/cafes-e-chas-611'
				listitem
					link Cervejas e destilados, url='https://trela.com.br/categoria/cervejas-e-destilados-641'
				listitem
					link Vinhos e espumantes, url='https://trela.com.br/categoria/vinhos-e-espumantes-758'
				listitem
					link Plant-Based, url='https://trela.com.br/categoria/plantbased-224'
		region Sobre a Trela
			list
				listitem
					link Quem somos, url='https://trela.com.br/institucional/quem-somos'
				listitem
					link Carreiras, url='https://jobs.lever.co/trela'
				listitem
					link Dúvidas Frequentes, url='https://trela.com.br/institucional/duvidas-frequentes'
				listitem
					link Política de Privacidade, url='https://trela.com.br/institucional/politica-de-privacidade'
				listitem
					link Termos e condições, url='https://trela.com.br/institucional/termos-de-uso'
				listitem
					link Seja um parceiro, url='https://form.typeform.com/to/MGXdfqU0'
				listitem
					link Entre em contato, url='http://suporte.trela.com.br/'
		region Métodos de pagamento
			list
				listitem
					image logo pix, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-pix.png&w=1920&q=75'
				listitem
					image logo visa, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-visa.png&w=1920&q=75'
				listitem
					image logo mastercard, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-mastercard.png&w=1920&q=75'
				listitem
					image logo diners-club, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-diners-club.png&w=1920&q=75'
				listitem
					image logo american-express, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-american-express.png&w=1920&q=75'
				listitem
					image logo hipercard, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-hipercard.png&w=1920&q=75'
				listitem
					image logo discover, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-discover.png&w=1920&q=75'
				listitem
					image logo elo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-elo.png&w=1920&q=75'
				listitem
					image logo vr, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-vr.png&w=1920&q=75'
				listitem
					image logo sodexo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-sodexo.png&w=1920&q=75'
				listitem
					image logo ticket, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-ticket.png&w=1920&q=75'
				listitem
					image logo caju, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-caju.png&w=1920&q=75'
		separator, orientation='horizontal'
		region Nunca perca uma oferta, baixe o app da Trela
			link Disponível no Google Play, url='https://play.google.com/store/apps/details?id=com.trela.br.marketplace&hl=pt_BR&gl=US'
				image Disponível no Google Play, url='https://trela.com.br/_next/image?url=%2Fimages%2Fgoogle-play.png&w=256&q=75'
			link Disponível na App Store, url='https://apps.apple.com/br/app/trela/id6444369623'
				image Disponível na App Store, url='https://trela.com.br/_next/image?url=%2Fimages%2Fapp-store.png&w=256&q=75'
		separator, orientation='horizontal'
		image Trela
		list
			listitem
				link instagram logo, url='https://www.instagram.com/trela'
					image instagram logo, url='https://d29vvterh1pj9i.cloudfront.net/instagram_57e7afd553.svg'
			listitem
				link linkedin logo, url='https://www.linkedin.com/company/deutrela'
					image linkedin logo, url='https://d29vvterh1pj9i.cloudfront.net/linkedin_ce1dd8540e.svg'
			listitem
				link tiktok logo, url='https://www.tiktok.com/@trelaoficial'
					image tiktok logo, url='https://d29vvterh1pj9i.cloudfront.net/tiktok_443444b5cd.svg'
		StaticText Zapt Tecnologia LTDA CNPJ - 37.896.391/0001-84
	alert, atomic
		StaticText Oferta do Dia até 15% OFF | Trela
```
</details>

**Reasoning for action:** By clicking on the 'Oferta do Dia até 15% OFF' category link, I am able to access the products that are currently discounted within that specific promotion. This is essential for fulfilling the user's requirement to quickly access discounted products. Once on this page, I will be able to locate the product 'Queijo cottage 200g' to add it to the shopping cart as per the user story.

**Action:** click(135) # Click on the 'Oferta do Dia até 15% OFF' category link to explore the products in this section.

**Change Description:** The browser navigated to the 'Oferta do Dia até 15% OFF' section, updating the webpage title and content to display category-specific discounts and featured products. The layout shifted from a general homepage view to a focused product listing within the 'Oferta do Dia' category, highlighting various discounted items.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://trela.com.br/categoria/oferta-do-dia-ate-15-off-180

https://trela.com.br/produto/queijo-cottage-200g-12211

**Content (before/after):** 

```
RootWebArea Oferta do Dia até 15% OFF | Trela, focused, url='https://trela.com.br/categoria/oferta-do-dia-ate-15-off-180'
	banner
		navigation
			[2977] link Trela, center=(335,30), url='https://trela.com.br/'
				image Trela
```
<details><summary>Show more</summary>

```
			[2982] textbox O que você está procurando?, center=(960,30), contenteditable=True
			[2984] link Entrar / Cadastrar, center=(1496,30), url='https://trela.com.br/login?callbackUrl=%2Fcategoria%2Foferta-do-dia-ate-15-off-180'
			[2986] button Menu, center=(1602,30)
	main
		heading Oferta do Dia até 15% OFF
		navigation
			region lista de categorias
				list
					listitem
						article
							[3018] link Oferta do Dia até 15% OFF, center=(446,98), url='https://trela.com.br/categoria/oferta-do-dia-ate-15-off-180'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F00180a97-33f3-4eb4-923d-eee91d4cbaa0.png&w=96&q=75'
							[3022] button compartilhar, center=(542,98)
					listitem
						article
							[3026] link Selecionados para você, center=(647,98), url='https://trela.com.br/categoria/selecionados-para-voce-1097'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fea58f86c-8199-4cd3-a72b-dd34789b4f3e.png&w=96&q=75'
					listitem
						article
							[3032] link Novos na Trela, center=(818,98), url='https://trela.com.br/categoria/novos-na-trela-298'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F631f48a8-7c0d-41a0-a6af-0d75ce1dc13c.png&w=96&q=75'
					listitem
						article
							[3038] link Especiais de fim de ano, center=(990,98), url='https://trela.com.br/categoria/especiais-de-fim-de-ano-1156'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F12e2c830-329b-4add-8356-58de664609ab.png&w=96&q=75'
					listitem
						article
							[3044] link Hortifruti e ovos, center=(1161,98), url='https://trela.com.br/categoria/hortifruti-e-ovos-662'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F8c170965-16cd-4531-8023-c433f1af7c70.png&w=96&q=75'
					listitem
						article
							[3050] link Queijos e laticínios, center=(1333,98), url='https://trela.com.br/categoria/queijos-e-laticinios-693'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fc49fcac4-9824-422c-a80e-babc86875214.png&w=96&q=75'
					listitem
						article
							[3056] link Básicos da despensa, center=(1504,98), url='https://trela.com.br/categoria/basicos-da-despensa-587'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F198dc6a8-b72d-40e6-bdf8-1e28ad8e3b80.png&w=96&q=75'
					listitem
						article
							link Carnes, url='https://trela.com.br/categoria/carnes-622'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F721a0006-f25a-421d-8af9-19b5a20980a5.png&w=96&q=75'
					listitem
						article
							link Peixes e frutos do mar, url='https://trela.com.br/categoria/peixes-e-frutos-do-mar-681'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F8657ee04-91e3-4f37-a8a6-d10a73ae2a14.png&w=96&q=75'
					listitem
						article
							link Frios e charcutaria, url='https://trela.com.br/categoria/frios-e-charcutaria-654'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fc6d840c0-7077-43b8-829b-31bedd0de1d6.png&w=96&q=75'
					listitem
						article
							link Padaria e confeitaria, url='https://trela.com.br/categoria/padaria-e-confeitaria-673'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F5d90de96-9ae3-4c3d-b413-8b564d4a360e.png&w=96&q=75'
					listitem
						article
							link Refeições práticas, url='https://trela.com.br/categoria/refeicoes-praticas-565'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fe4aaba8f-397b-4aa3-beac-4b7dd89cb0ac.png&w=96&q=75'
					listitem
						article
							link Salgados e tortas, url='https://trela.com.br/categoria/salgados-e-tortas-727'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fc034a3b9-b196-4329-b332-3f93558df7d2.png&w=96&q=75'
					listitem
						article
							link Pizzas e massas, url='https://trela.com.br/categoria/pizzas-e-massas-686'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F0862abb7-d513-4c35-b983-e665616a748b.png&w=96&q=75'
					listitem
						article
							link Antepastos e molhos, url='https://trela.com.br/categoria/antepastos-e-molhos-578'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F13aa370a-7702-4aa9-988f-5d1dc141a3a9.png&w=96&q=75'
					listitem
						article
							link Castanhas e frutas secas, url='https://trela.com.br/categoria/castanhas-e-frutas-secas-634'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fb5798c8f-465e-45d1-aa06-0c67a7b55bc7.png&w=96&q=75'
					listitem
						article
							link Snacks, url='https://trela.com.br/categoria/snacks-733'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F2a5d617f-03a9-40bf-9df1-c3f4e37506d6.png&w=96&q=75'
					listitem
						article
							link Suplementos, url='https://trela.com.br/categoria/suplementos-747'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fda566dba-d86f-4f48-a463-ebdf864b09f2.png&w=96&q=75'
					listitem
						article
							link Doces e chocolates, url='https://trela.com.br/categoria/doces-e-chocolates-645'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fb4e1a295-beeb-4321-92fc-b15c08dfb512.png&w=96&q=75'
					listitem
						article
							link Sorvetes e açaí, url='https://trela.com.br/categoria/sorvetes-e-acai-742'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F26b77fa7-f6f9-4df0-b3d7-0f33bc40b6e0.png&w=96&q=75'
					listitem
						article
							link Bebidas, url='https://trela.com.br/categoria/bebidas-599'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F2ac71ac0-8ce3-4125-acd8-8510853260cf.png&w=96&q=75'
					listitem
						article
							link Cafés e Chás, url='https://trela.com.br/categoria/cafes-e-chas-611'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Feeb697f1-eaf4-4c9b-9673-fe0e1a219a89.png&w=96&q=75'
					listitem
						article
							link Cervejas e destilados, url='https://trela.com.br/categoria/cervejas-e-destilados-641'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fa79f76db-bf33-4c5e-8306-d89033c6c30e.png&w=96&q=75'
					listitem
						article
							link Vinhos e espumantes, url='https://trela.com.br/categoria/vinhos-e-espumantes-758'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F7261bc0b-70f9-4b92-ac31-92cb3b214579.png&w=48&q=75'
					listitem
						article
							link Plant-Based, url='https://trela.com.br/categoria/plantbased-224'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F7aac7d2e-64eb-44ef-954f-723aa42432bd.png&w=48&q=75'
				[3170] button próximos itens, center=(1588,98)
		heading Tudo
		navigation
			[3177] button Filtrar, center=(403,155)
			[3180] button Tudo, center=(491,155)
			separator, orientation='horizontal'
		[3188] link Queijo cottage 200g 51 Refrigerado adicionar Cruzília Cruzília Queijo cottage 200g R$ 10,90 R$ 9,27 -15%, center=(457,355), inner_text=51
Refrigerado
Cruzília
Queijo cottage 200g
R$ 10,90
R$ 9,27
-15%, url='https://trela.com.br/produto/queijo-cottage-200g-12211'
			image Queijo cottage 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc11f29bb-a64a-4222-a8c6-7bca76aa0b7f-cottage-cruzi%CC%81lia-12211.1.png&w=384&q=75'
			StaticText 51
			StaticText Refrigerado
			button adicionar
			image Cruzília, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5786d8f5-d4ca-41e6-980a-60bd819b961d.png&w=32&q=75'
			StaticText Cruzília
			heading Queijo cottage 200g
		[3215] link Pão sem glúten tradicional 500g - Congelado 19 Congelado adicionar Pão do Céu Pão do Céu Pão sem glúten tradicional 500g - Congelado R$ 20,90 R$ 17,77 -15%, center=(658,355), inner_text=19
Congelado
Pão do Céu
Pão sem glúten tradicional 500g - Congelado
R$ 20,90
R$ 17,77
-15%, url='https://trela.com.br/produto/pao-sem-gluten-tradicional-500g-congelado-12555'
			image Pão sem glúten tradicional 500g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F74dcb0e2-aa6c-4909-8d05-5ad41199945a.png&w=384&q=75'
			StaticText 19
			StaticText Congelado
			button adicionar
			image Pão do Céu, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F8c47b61c-1745-4522-a1c3-5e3592a4f157.png&w=32&q=75'
			StaticText Pão do Céu
			heading Pão sem glúten tradicional 500g - Congelado
		[3242] link Guacamole Sr. Guaca 200g 39 Refrigerado adicionar Sr. Guaca Sr. Guaca Guacamole Sr. Guaca 200g R$ 15,29 R$ 13,00 -15%, center=(859,355), inner_text=39
Refrigerado
Sr. Guaca
Guacamole Sr. Guaca 200g
R$ 15,29
R$ 13,00
-15%, url='https://trela.com.br/produto/guacamole-sr-guaca-200g-11448'
			image Guacamole Sr. Guaca 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F692edf71-8478-48b9-b4b5-dc3fe356a7ec-guacamolesrguaca-srguaca-11448.1.png&w=384&q=75'
			StaticText 39
			StaticText Refrigerado
			button adicionar
			image Sr. Guaca, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F6df05adb-ce6b-4c5b-9412-fac3eef999fe.png&w=32&q=75'
			StaticText Sr. Guaca
			heading Guacamole Sr. Guaca 200g
		[3269] link Suco de laranja 900ml 42 Refrigerado adicionar Xandô Xandô Suco de laranja 900ml R$ 15,90 R$ 13,52 -15%, center=(1061,355), inner_text=42
Refrigerado
Xandô
Suco de laranja 900ml
R$ 15,90
R$ 13,52
-15%, url='https://trela.com.br/produto/suco-de-laranja-900ml-10863'
			image Suco de laranja 900ml, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fd2cc0667-b893-4983-b41e-fcf7c6a60fcb-sucodelaranja-xando%CC%82-10863.1.png&w=384&q=75'
			StaticText 42
			StaticText Refrigerado
			button adicionar
			image Xandô, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F77360f6b-5746-43ec-ae31-67d69718f6d1.png&w=32&q=75'
			StaticText Xandô
			heading Suco de laranja 900ml
		[3296] link Iogurte Natural de Leite de Ovelha 140g 38 Refrigerado adicionar Queijaria Rima Queijaria Rima Iogurte Natural de Leite de Ovelha 140g R$ 6,12 R$ 5,20 -15%, center=(1262,355), inner_text=38
Refrigerado
Queijaria Rima
Iogurte Natural de Leite de Ovelha 140g
R$ 6,12
R$ 5,20
-15%, url='https://trela.com.br/produto/iogurte-natural-de-leite-de-ovelha-140g-11450'
			image Iogurte Natural de Leite de Ovelha 140g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F32111064-0b47-4689-9a9d-0d66b9bfac2e.png&w=384&q=75'
			StaticText 38
			StaticText Refrigerado
			button adicionar
			image Queijaria Rima, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fsuppliers%2F8265229b-2829-4816-9b2d-3d394b18628b.png&w=32&q=75'
			StaticText Queijaria Rima
			heading Iogurte Natural de Leite de Ovelha 140g
		[3323] link Pão 100% integral 450g - Congelado 24 Congelado adicionar Pão do Céu Pão do Céu Pão 100% integral 450g - Congelado R$ 18,40 R$ 15,64 -15%, center=(1463,355), inner_text=24
Congelado
Pão do Céu
Pão 100% integral 450g - Congelado
R$ 18,40
R$ 15,64
-15%, url='https://trela.com.br/produto/pao-100-integral-450g-congelado-12554'
			image Pão 100% integral 450g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fa8224eb4-7378-4a4f-98d8-fea03fed8bdc-p%C3%A3o100_integral-p%C3%A3odoc%C3%A9u-12554.1.png&w=384&q=75'
			StaticText 24
			StaticText Congelado
			button adicionar
			image Pão do Céu, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F8c47b61c-1745-4522-a1c3-5e3592a4f157.png&w=32&q=75'
			StaticText Pão do Céu
			heading Pão 100% integral 450g - Congelado
		[3351] link Natural Whey de Coco 21g de proteína - 250g 29 Refrigerado adicionar Verde Campo Verde Campo Natural Whey de Coco 21g de proteína - 250g R$ 8,69 R$ 7,39 -15%, center=(457,654), inner_text=29
Refrigerado
Verde Campo
Natural Whey de Coco 21g de proteína - 250g
R$ 8,69
R$ 7,39
-15%, url='https://trela.com.br/produto/natural-whey-de-coco-21g-de-proteina-250g-11527'
			image Natural Whey de Coco 21g de proteína - 250g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F0ce6f300-be4a-46c8-b164-58d6f7e9be3b.png&w=384&q=75'
			StaticText 29
			StaticText Refrigerado
			button adicionar
			image Verde Campo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb045f0a8-3d1e-4064-9cc2-d188dfa19844.png&w=32&q=75'
			StaticText Verde Campo
			heading Natural Whey de Coco 21g de proteína - 250g
		[3378] link Pão batata doce orgânico 450g - Congelado 25 Congelado adicionar Pão do Céu Pão do Céu Pão batata doce orgânico 450g - Congelado R$ 18,40 R$ 15,64 -15%, center=(658,658), inner_text=25
Congelado
Pão do Céu
Pão batata doce orgânico 450g - Congelado
R$ 18,40
R$ 15,64
-15%, url='https://trela.com.br/produto/pao-batata-doce-organico-450g-congelado-12553'
			image Pão batata doce orgânico 450g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fe63e8495-d4c3-4195-8228-5d9888b36cd3-p%C3%A3obatatadoceorg%C3%A2nico-p%C3%A3odoc%C3%A9u-12553.1.png&w=384&q=75'
			StaticText 25
			StaticText Congelado
			button adicionar
			image Pão do Céu, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F8c47b61c-1745-4522-a1c3-5e3592a4f157.png&w=32&q=75'
			StaticText Pão do Céu
			heading Pão batata doce orgânico 450g - Congelado
		[3405] link Yorgus grego desnatado natural 500g 22 Refrigerado adicionar Yorgus Yorgus Yorgus grego desnatado natural 500g R$ 29,90 R$ 25,42 -15%, center=(859,658), inner_text=22
Refrigerado
Yorgus
Yorgus grego desnatado natural 500g
R$ 29,90
R$ 25,42
-15%, url='https://trela.com.br/produto/yorgus-grego-desnatado-natural-500g-12905'
			image Yorgus grego desnatado natural 500g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fd1c5638d-0592-41b5-83f1-56c8747f5607.png&w=384&q=75'
			StaticText 22
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus grego desnatado natural 500g
		[3432] link Pão energia das sementes 380g - Congelado 11 Congelado adicionar House of Maya House of Maya Pão energia das sementes 380g - Congelado R$ 30,90 R$ 26,27 -15%, center=(1061,658), inner_text=11
Congelado
House of Maya
Pão energia das sementes 380g - Congelado
R$ 30,90
R$ 26,27
-15%, url='https://trela.com.br/produto/pao-energia-das-sementes-380g-congelado-12768'
			image Pão energia das sementes 380g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F96a16c52-2c24-46c2-8762-21db570a0b3d-p%C3%A3oenergiadassementes-houseofmaya-12768.1.png&w=384&q=75'
			StaticText 11
			StaticText Congelado
			button adicionar
			image House of Maya, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fdc9155eb-7b51-4963-b8d8-fbbb9e369d3d.png&w=32&q=75'
			StaticText House of Maya
			heading Pão energia das sementes 380g - Congelado
		[3459] link Tofu Orgânico Natural 450g - Refrigerado 13  Ultrafresco adicionar SÍtio Boa Esperança SÍtio Boa Esperança Tofu Orgânico Natural 450g - Refrigerado R$ 28,90 R$ 24,57 -15%, center=(1262,658), inner_text=13
Ultrafresco
SÍtio Boa Esperança
Tofu Orgânico Natural 450g - Refrigerado
R$ 28,90
R$ 24,57
-15%, url='https://trela.com.br/produto/tofu-organico-natural-450g-refrigerado-11583'
			image Tofu Orgânico Natural 450g - Refrigerado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F93093a13-4118-4fb4-b283-b652827a7d85-tofuorga%CC%82niconatural-si%CC%81tioboaesperanc%CC%A7a-11583.1.png&w=384&q=75'
			StaticText 13
			StaticText 
			StaticText Ultrafresco
			button adicionar
			image SÍtio Boa Esperança, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F80eedb37-bb57-4585-81c1-086cdfa83a60.png&w=32&q=75'
			StaticText SÍtio Boa Esperança
			heading Tofu Orgânico Natural 450g - Refrigerado
		[3486] link Bolo de limão siciliano e amêndoas 270g - Congelado Congelado adicionar House of Maya House of Maya Bolo de limão siciliano e amêndoas 270g - Congelado R$ 25,90 R$ 22,02 -15%, center=(1463,658), inner_text=Congelado
House of Maya
Bolo de limão siciliano e amêndoas 270g - Congelado
R$ 25,90
R$ 22,02
-15%, url='https://trela.com.br/produto/bolo-de-limao-siciliano-e-amendoas-270g-congelado-12765'
			image Bolo de limão siciliano e amêndoas 270g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F4b5758a7-3cb8-4c51-9db5-1eb34a276843-bolodelim%C3%A3osicilianoeam%C3%AAndoas-houseofmaya-12765.1.png&w=384&q=75'
			StaticText Congelado
			button adicionar
			image House of Maya, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fdc9155eb-7b51-4963-b8d8-fbbb9e369d3d.png&w=32&q=75'
			StaticText House of Maya
			heading Bolo de limão siciliano e amêndoas 270g - Congelado
		[3511] link Yorgus grego natural 0% gordura 130g 15 Refrigerado adicionar Yorgus Yorgus Yorgus grego natural 0% gordura 130g R$ 8,49 R$ 7,22 -15%, center=(457,961), inner_text=15
Refrigerado
Yorgus
Yorgus grego natural 0% gordura 130g
R$ 8,49
R$ 7,22
-15%, url='https://trela.com.br/produto/yorgus-grego-natural-0-gordura-130g-11531'
			image Yorgus grego natural 0% gordura 130g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff4f3624a-a448-44e1-936e-50984edb5ae5-yorgusgregonatural0_gordura-yorgus-11531.1.png&w=384&q=75'
			StaticText 15
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus grego natural 0% gordura 130g
		[3538] link Iogurte de Mel 170ml 38 Refrigerado adicionar Delicari Delicari Iogurte de Mel 170ml R$ 7,10 R$ 6,04 -15%, center=(658,961), inner_text=38
Refrigerado
Delicari
Iogurte de Mel 170ml
R$ 7,10
R$ 6,04
-15%, url='https://trela.com.br/produto/iogurte-de-mel-170ml-9252'
			image Iogurte de Mel 170ml, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F61c7e0ba-8841-481d-89ca-56f2b59d1d02-iogurtedemell-delicari-9252.1.png&w=384&q=75'
			StaticText 38
			StaticText Refrigerado
			button adicionar
			image Delicari, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F2403b2c8-dce9-4d5c-846b-0ff0be5d1868.png&w=32&q=75'
			StaticText Delicari
			heading Iogurte de Mel 170ml
		[3565] link Ovos caipiras com ômega 3 orgânicos 10 Unidades 22 adicionar Fazenda da Toca Fazenda da Toca Ovos caipiras com ômega 3 orgânicos 10 Unidades R$ 15,29 R$ 13,00 -15%, center=(859,961), inner_text=22
Fazenda da Toca
Ovos caipiras com ômega 3 orgânicos 10 Unidades
R$ 15,29
R$ 13,00
-15%, url='https://trela.com.br/produto/ovos-caipiras-com-omega-3-organicos-10-unidades-13294'
			image Ovos caipiras com ômega 3 orgânicos 10 Unidades, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb10cacb8-9748-43c8-8724-ada849cce6d9.png&w=384&q=75'
			StaticText 22
			button adicionar
			image Fazenda da Toca, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F4a8a125a-4069-4776-b8dc-a16acbd5e4a3.png&w=32&q=75'
			StaticText Fazenda da Toca
			heading Ovos caipiras com ômega 3 orgânicos 10 Unidades
		[3587] link Yorgus desnatado com mel silvestre orgânico 130g 13 Refrigerado adicionar Yorgus Yorgus Yorgus desnatado com mel silvestre orgânico 130g R$ 8,49 R$ 7,22 -15%, center=(1061,961), inner_text=13
Refrigerado
Yorgus
Yorgus desnatado com mel silvestre orgânico 130g
R$ 8,49
R$ 7,22
-15%, url='https://trela.com.br/produto/yorgus-desnatado-com-mel-silvestre-organico-130g-12904'
			image Yorgus desnatado com mel silvestre orgânico 130g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F620fcaa6-9327-4207-8d93-93ef0b5c7434-yorgusdesnatadocommelsilvestreorga%CC%82nico-yorgus-12904.1.png&w=384&q=75'
			StaticText 13
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus desnatado com mel silvestre orgânico 130g
		[3614] link Ovos caipiras orgânicos 18 Unidades 19 adicionar Fazenda da Toca Fazenda da Toca Ovos caipiras orgânicos 18 Unidades R$ 27,89 R$ 23,71 -15%, center=(1262,961), inner_text=19
Fazenda da Toca
Ovos caipiras orgânicos 18 Unidades
R$ 27,89
R$ 23,71
-15%, url='https://trela.com.br/produto/ovos-caipiras-organicos-18-unidades-13295'
			image Ovos caipiras orgânicos 18 Unidades, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F4376eae7-dffe-4492-93e1-5a7ef27e4815.png&w=384&q=75'
			StaticText 19
			button adicionar
			image Fazenda da Toca, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F4a8a125a-4069-4776-b8dc-a16acbd5e4a3.png&w=32&q=75'
			StaticText Fazenda da Toca
			heading Ovos caipiras orgânicos 18 Unidades
		[3636] link Iogurte de morango Lacfree 500g 21 Refrigerado adicionar Verde Campo Verde Campo Iogurte de morango Lacfree 500g R$ 8,50 R$ 7,23 -15%, center=(1463,961), inner_text=21
Refrigerado
Verde Campo
Iogurte de morango Lacfree 500g
R$ 8,50
R$ 7,23
-15%, url='https://trela.com.br/produto/iogurte-de-morango-lacfree-500g-11523'
			image Iogurte de morango Lacfree 500g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc5c76417-6de9-4eb4-b8e9-2b5b679b096f.png&w=384&q=75'
			StaticText 21
			StaticText Refrigerado
			button adicionar
			image Verde Campo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb045f0a8-3d1e-4064-9cc2-d188dfa19844.png&w=32&q=75'
			StaticText Verde Campo
			heading Iogurte de morango Lacfree 500g
		link Natural Whey de Banana 14g de proteína - 250g 19 Refrigerado adicionar Verde Campo Verde Campo Natural Whey de Banana 14g de proteína - 250g R$ 7,90 R$ 6,72 -15%, url='https://trela.com.br/produto/natural-whey-de-banana-14g-de-proteina-250g-11525'
			image Natural Whey de Banana 14g de proteína - 250g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F0a78e758-8483-4d8c-b1fb-b1b506197a37.png&w=384&q=75'
			StaticText 19
			StaticText Refrigerado
			button adicionar
			image Verde Campo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb045f0a8-3d1e-4064-9cc2-d188dfa19844.png&w=32&q=75'
			StaticText Verde Campo
			heading Natural Whey de Banana 14g de proteína - 250g
		link Yorgus grego integral de baunilha 130g Refrigerado adicionar Yorgus Yorgus Yorgus grego integral de baunilha 130g R$ 8,49 R$ 7,22 -15%, url='https://trela.com.br/produto/yorgus-grego-integral-de-baunilha-130g-11536'
			image Yorgus grego integral de baunilha 130g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5beb0575-f7fc-47e9-b20b-48077690d0b4-yorgusgregointegraldebaunilha-yorgus-11536.1.png&w=384&q=75'
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus grego integral de baunilha 130g
		link Yorgus grego de frutas silvestres 130g 19 Refrigerado adicionar Yorgus Yorgus Yorgus grego de frutas silvestres 130g R$ 8,49 R$ 7,22 -15%, url='https://trela.com.br/produto/yorgus-grego-de-frutas-silvestres-130g-11534'
			image Yorgus grego de frutas silvestres 130g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F7281bf48-4d8f-4df3-aca0-190f180d84ae-yorgusgregodefrutassilvestres-yorgus-11534.1.png&w=384&q=75'
			StaticText 19
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus grego de frutas silvestres 130g
		link Yorgus completo de frutas silvestres 250g 19 Refrigerado adicionar Yorgus Yorgus Yorgus completo de frutas silvestres 250g R$ 12,49 R$ 10,62 -15%, url='https://trela.com.br/produto/yorgus-completo-de-frutas-silvestres-250g-11540'
			image Yorgus completo de frutas silvestres 250g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fdb8b1b05-fce2-4acb-88f5-0620f58c87db-yorguscompletodefrutassilvestres-yorgus-11540.1.png&w=384&q=75'
			StaticText 19
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus completo de frutas silvestres 250g
		link Yorgus completo de baunilha 250g Refrigerado adicionar Yorgus Yorgus Yorgus completo de baunilha 250g R$ 12,49 R$ 10,62 -15%, url='https://trela.com.br/produto/yorgus-completo-de-baunilha-250g-11538'
			image Yorgus completo de baunilha 250g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F754021ad-2e7f-4dcc-99ac-0bf81d4f2c53-yorguscompletodebaunilha-yorgus-11538.1.png&w=384&q=75'
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus completo de baunilha 250g
		link Yorgus grego integral de coco 130g 14 Refrigerado adicionar Yorgus Yorgus Yorgus grego integral de coco 130g R$ 8,49 R$ 7,22 -15%, url='https://trela.com.br/produto/yorgus-grego-integral-de-coco-130g-11537'
			image Yorgus grego integral de coco 130g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5acc7a4c-efb3-4e14-bc0c-db71bd0f0426-yorgusgregointegraldecoco-yorgus-11537.1.png&w=384&q=75'
			StaticText 14
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus grego integral de coco 130g
	navigation breadcrumb
		list
			listitem
				link Início, url='https://trela.com.br/'
			listitem
				StaticText /
				link Categorias, url='https://trela.com.br/categoria'
			listitem
				StaticText /
				StaticText Oferta do Dia até 15% OFF
	contentinfo
		region Categorias
			list
				listitem
					link Oferta do Dia até 15% OFF, url='https://trela.com.br/categoria/oferta-do-dia-ate-15-off-180'
				listitem
					link Selecionados para você, url='https://trela.com.br/categoria/selecionados-para-voce-1097'
				listitem
					link Novos na Trela, url='https://trela.com.br/categoria/novos-na-trela-298'
				listitem
					link Especiais de fim de ano, url='https://trela.com.br/categoria/especiais-de-fim-de-ano-1156'
				listitem
					link Hortifruti e ovos, url='https://trela.com.br/categoria/hortifruti-e-ovos-662'
				listitem
					link Queijos e laticínios, url='https://trela.com.br/categoria/queijos-e-laticinios-693'
				listitem
					link Básicos da despensa, url='https://trela.com.br/categoria/basicos-da-despensa-587'
				listitem
					link Carnes, url='https://trela.com.br/categoria/carnes-622'
				listitem
					link Peixes e frutos do mar, url='https://trela.com.br/categoria/peixes-e-frutos-do-mar-681'
				listitem
					link Frios e charcutaria, url='https://trela.com.br/categoria/frios-e-charcutaria-654'
				listitem
					link Padaria e confeitaria, url='https://trela.com.br/categoria/padaria-e-confeitaria-673'
				listitem
					link Refeições práticas, url='https://trela.com.br/categoria/refeicoes-praticas-565'
				listitem
					link Salgados e tortas, url='https://trela.com.br/categoria/salgados-e-tortas-727'
				listitem
					link Pizzas e massas, url='https://trela.com.br/categoria/pizzas-e-massas-686'
				listitem
					link Antepastos e molhos, url='https://trela.com.br/categoria/antepastos-e-molhos-578'
				listitem
					link Castanhas e frutas secas, url='https://trela.com.br/categoria/castanhas-e-frutas-secas-634'
				listitem
					link Snacks, url='https://trela.com.br/categoria/snacks-733'
				listitem
					link Suplementos, url='https://trela.com.br/categoria/suplementos-747'
				listitem
					link Doces e chocolates, url='https://trela.com.br/categoria/doces-e-chocolates-645'
				listitem
					link Sorvetes e açaí, url='https://trela.com.br/categoria/sorvetes-e-acai-742'
				listitem
					link Bebidas, url='https://trela.com.br/categoria/bebidas-599'
				listitem
					link Cafés e Chás, url='https://trela.com.br/categoria/cafes-e-chas-611'
				listitem
					link Cervejas e destilados, url='https://trela.com.br/categoria/cervejas-e-destilados-641'
				listitem
					link Vinhos e espumantes, url='https://trela.com.br/categoria/vinhos-e-espumantes-758'
				listitem
					link Plant-Based, url='https://trela.com.br/categoria/plantbased-224'
		region Sobre a Trela
			list
				listitem
					link Quem somos, url='https://trela.com.br/institucional/quem-somos'
				listitem
					link Carreiras, url='https://jobs.lever.co/trela'
				listitem
					link Dúvidas Frequentes, url='https://trela.com.br/institucional/duvidas-frequentes'
				listitem
					link Política de Privacidade, url='https://trela.com.br/institucional/politica-de-privacidade'
				listitem
					link Termos e condições, url='https://trela.com.br/institucional/termos-de-uso'
				listitem
					link Seja um parceiro, url='https://form.typeform.com/to/MGXdfqU0'
				listitem
					link Entre em contato, url='http://suporte.trela.com.br/'
		region Métodos de pagamento
			list
				listitem
					image logo pix, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-pix.png&w=1920&q=75'
				listitem
					image logo visa, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-visa.png&w=1920&q=75'
				listitem
					image logo mastercard, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-mastercard.png&w=1920&q=75'
				listitem
					image logo diners-club, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-diners-club.png&w=1920&q=75'
				listitem
					image logo american-express, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-american-express.png&w=1920&q=75'
				listitem
					image logo hipercard, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-hipercard.png&w=1920&q=75'
				listitem
					image logo discover, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-discover.png&w=1920&q=75'
				listitem
					image logo elo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-elo.png&w=1920&q=75'
				listitem
					image logo vr, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-vr.png&w=1920&q=75'
				listitem
					image logo sodexo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-sodexo.png&w=1920&q=75'
				listitem
					image logo ticket, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-ticket.png&w=1920&q=75'
				listitem
					image logo caju, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-caju.png&w=1920&q=75'
		separator, orientation='horizontal'
		region Nunca perca uma oferta, baixe o app da Trela
			link Disponível no Google Play, url='https://play.google.com/store/apps/details?id=com.trela.br.marketplace&hl=pt_BR&gl=US'
				image Disponível no Google Play, url='https://trela.com.br/_next/image?url=%2Fimages%2Fgoogle-play.png&w=256&q=75'
			link Disponível na App Store, url='https://apps.apple.com/br/app/trela/id6444369623'
				image Disponível na App Store, url='https://trela.com.br/_next/image?url=%2Fimages%2Fapp-store.png&w=256&q=75'
		separator, orientation='horizontal'
		image Trela
		list
			listitem
				link instagram logo, url='https://www.instagram.com/trela'
					image instagram logo, url='https://d29vvterh1pj9i.cloudfront.net/instagram_57e7afd553.svg'
			listitem
				link linkedin logo, url='https://www.linkedin.com/company/deutrela'
					image linkedin logo, url='https://d29vvterh1pj9i.cloudfront.net/linkedin_ce1dd8540e.svg'
			listitem
				link tiktok logo, url='https://www.tiktok.com/@trelaoficial'
					image tiktok logo, url='https://d29vvterh1pj9i.cloudfront.net/tiktok_443444b5cd.svg'
		StaticText Zapt Tecnologia LTDA CNPJ - 37.896.391/0001-84
	alert, atomic
		StaticText Oferta do Dia até 15% OFF | Trela
```
</details>



```
RootWebArea Queijo cottage 200g | Trela, focused, url='https://trela.com.br/produto/queijo-cottage-200g-12211'
	banner
		navigation
			[5062] link Trela, center=(335,30), url='https://trela.com.br/'
				image Trela
```
<details><summary>Show more</summary>

```
			[5067] textbox O que você está procurando?, center=(960,30), contenteditable=True
			[5069] link Entrar / Cadastrar, center=(1496,30), url='https://trela.com.br/login?callbackUrl=%2Fproduto%2Fqueijo-cottage-200g-12211'
			[5071] button Menu, center=(1602,30)
	main
		image Queijo cottage 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc11f29bb-a64a-4222-a8c6-7bca76aa0b7f-cottage-cruzi%CC%81lia-12211.1.png&w=1920&q=75'
		[5086] div, center=(756,430)
		[5089] link Cruzília, center=(1230,134), url='https://trela.com.br/fornecedor/cruzilia-1833'
		heading Queijo cottage 200g
			[5095] button, center=(1495,219)
		paragraph
			StaticText R$ 10,90
		paragraph
			StaticText R$ 9,27
		StaticText -15
		StaticText %
		[5102] button 91% gostaram • 56 avaliações, center=(1368,339), inner_text=91% gostaram
•
56 avaliações
		separator, orientation='horizontal'
		StaticText Refrigerado
		StaticText 
		StaticText Vegetariano
		StaticText 
		StaticText Low Carb
		StaticText 
		StaticText Sem Glúten
		StaticText 
		StaticText Sem adição de açúcar
		separator, orientation='horizontal'
		[5130] button Só tem na Trela! Não encontramos o preço do produto nos concorrentes monitorados Mais detalhes, center=(1368,537), inner_text=Só tem na Trela! Não encontramos o preço do produto nos concorrentes monitorados
Mais detalhes
			image
			StaticText Só tem na Trela!
		blockquote
			StaticText “
			StaticText Com sabor leve, esse cottage é perfeito para o dia a dia. Com baixo teor de gordura, combina qualidade e ótimo preço.
			StaticText ”
		heading Nota do time de curadoria Trela
		paragraph
			paragraph
				StaticText O Cottage é um queijo com baixo teor de gordura e calorias. Com sabor suave, cremoso, fresco e textura delicada, pode ser consumido puro, com frutas ou mel, adicionado a saladas, omeletes e recheios de tortas, ou ainda usado como substituto do creme de leite em algumas receitas, proporcionando cremosidade e um toque único aos pratos.
		heading Ingredientes
		list
			listitem
				ListMarker •
				StaticText Leite pasteurizado desnatado
			listitem
				ListMarker •
				StaticText nata (creme de leite pasteurizado, estabilizante carragena (INS 407))
			listitem
				ListMarker •
				StaticText cloreto de sódio (sal)
			listitem
				ListMarker •
				StaticText fermento lático
			listitem
				ListMarker •
				StaticText conservador sorbato de potássio (INS 202)
		heading Tabela Nutricional
		table
			rowgroup
				row
					columnheader Porção de 30g (1 fatia)
					columnheader Quantidade por porção
					columnheader VD%
			rowgroup
				row
					cell Valor Energético
					cell 57kcal=239Kj
					cell 3
				row
					cell Carboidratos
					cell 0,3g
					cell 0
				row
					cell Proteínas
					cell 2,7g
					cell 4
				row
					cell Gorduras Totais
					cell 3,7g
					cell 7
				row
					cell Gorduras Saturadas
					cell 5,8g
					cell 26
				row
					cell Gorduras Trans
					cell 0g
					cell -
				row
					cell Fibra Alimentar
					cell 0g
					cell 0
				row
					cell Sódio
					cell 187mg
					cell 8
		region Seleção de produtos semelhantes
			heading Seleção de produtos semelhantes
			list
				listitem
					link Creme de Ricota 200g Refrigerado adicionar Cruzília Cruzília Creme de Ricota 200g R$ 7,90, url='https://trela.com.br/produto/creme-de-ricota-200g-11597'
						image Creme de Ricota 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F511fa9e3-2b7c-4cb9-9735-2078418e6fa1-cremedericota-cruzi%CC%81lia-11597.1.jpg&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Cruzília, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5786d8f5-d4ca-41e6-980a-60bd819b961d.png&w=32&q=75'
						StaticText Cruzília
						heading Creme de Ricota 200g
				listitem
					link Ricota Fresca 400g Refrigerado adicionar Yema Yema Ricota Fresca 400g R$ 7,19, url='https://trela.com.br/produto/ricota-fresca-400g-9630'
						image Ricota Fresca 400g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc1a96a51-3cc3-4118-9d9a-9da86f58df0d-ricotafresca-yema-9630.1.png&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Yema, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fa7b05be7-4418-4575-904b-8cd45b675678.png&w=32&q=75'
						StaticText Yema
						heading Ricota Fresca 400g
				listitem
					link Creme de Queijo Minas Frescal 200g Refrigerado adicionar Cruzília Cruzília Creme de Queijo Minas Frescal 200g R$ 8,90, url='https://trela.com.br/produto/creme-de-queijo-minas-frescal-200g-12206'
						image Creme de Queijo Minas Frescal 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fca08a3fd-1348-405f-9496-a6eaf46ef4f9-queijominasfrescalcremoso-cruzilia-12206.1.jpg&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Cruzília, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5786d8f5-d4ca-41e6-980a-60bd819b961d.png&w=32&q=75'
						StaticText Cruzília
						heading Creme de Queijo Minas Frescal 200g
				listitem
					link Pão multigrãos orgânico de fermentação natural fatiado 600g  Ultrafresco adicionar Tartapão Panificio Tartapão Panificio Pão multigrãos orgânico de fermentação natural fatiado 600g R$ 25,00, url='https://trela.com.br/produto/pao-multigraos-organico-de-fermentacao-natural-fatiado-600g-10967'
						image Pão multigrãos orgânico de fermentação natural fatiado 600g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F062f4827-5d99-4ea8-8412-62ed1f60b782-pa%CC%83omultigra%CC%83osorga%CC%82nicofatiado-tartapa%CC%83opanificio-10967.1.png&w=384&q=75'
						StaticText 
						StaticText Ultrafresco
						button adicionar
						image Tartapão Panificio, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff3fe1d64-4634-4f4f-8d16-8e9c441412f4.png&w=32&q=75'
						StaticText Tartapão Panificio
						heading Pão multigrãos orgânico de fermentação natural fatiado 600g
				listitem
					link Minas Frescal 450g Refrigerado adicionar Yema Yema Minas Frescal 450g R$ 21,99, url='https://trela.com.br/produto/minas-frescal-450g-9634'
						image Minas Frescal 450g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F704744b6-d3c3-4650-b2b1-3715ee25815c-minasfrescal-yema-9634.2.png&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Yema, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fa7b05be7-4418-4575-904b-8cd45b675678.png&w=32&q=75'
						StaticText Yema
						heading Minas Frescal 450g
				listitem
					link Pão clássico orgânico de fermentação natural fatiado 600g  Ultrafresco adicionar Tartapão Panificio Tartapão Panificio Pão clássico orgânico de fermentação natural fatiado 600g R$ 22,00, url='https://trela.com.br/produto/pao-classico-organico-de-fermentacao-natural-fatiado-600g-10966'
						image Pão clássico orgânico de fermentação natural fatiado 600g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F76d356f7-3ae3-4f17-97fc-807d471fa671-pa%CC%83ocla%CC%81ssicoorga%CC%82nicofatiado-tartapa%CC%83opanificio-10966.1.png&w=384&q=75'
						StaticText 
						StaticText Ultrafresco
						button adicionar
						image Tartapão Panificio, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff3fe1d64-4634-4f4f-8d16-8e9c441412f4.png&w=32&q=75'
						StaticText Tartapão Panificio
						heading Pão clássico orgânico de fermentação natural fatiado 600g
				listitem
					link Iogurte Integral 500g Refrigerado adicionar Leitíssimo Leitíssimo Iogurte Integral 500g R$ 11,89, url='https://trela.com.br/produto/iogurte-integral-500g-12083'
						image Iogurte Integral 500g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.amazonaws.com%2Fproducts%2F895cbbba-0d03-4d42-9fc8-4d1404aece54.png&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Leitíssimo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F63190e43-d2eb-4a8c-be92-feb76aa7647a.png&w=32&q=75'
						StaticText Leitíssimo
						heading Iogurte Integral 500g
				listitem
					link Creme de leite - 200g adicionar Leitíssimo Leitíssimo Creme de leite - 200g R$ 6,49, url='https://trela.com.br/produto/creme-de-leite-200g-9265'
						image Creme de leite - 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc8118dfb-3e75-4de6-9a54-65330c114ee8-cremedeleite-leiteleiti%CC%81ssimo-9265.1.png&w=384&q=75'
						button adicionar
						image Leitíssimo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F63190e43-d2eb-4a8c-be92-feb76aa7647a.png&w=32&q=75'
						StaticText Leitíssimo
						heading Creme de leite - 200g
				listitem
					link Queijo Quark 280g Refrigerado adicionar Cruzília Cruzília Queijo Quark 280g R$ 11,90, url='https://trela.com.br/produto/queijo-quark-280g-11611'
						image Queijo Quark 280g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F88ddc012-d04e-47be-b288-51dcfc321ab4.png&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Cruzília, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5786d8f5-d4ca-41e6-980a-60bd819b961d.png&w=32&q=75'
						StaticText Cruzília
						heading Queijo Quark 280g
				listitem
					link Iogurte Parcialmente Desnatado 500g Refrigerado adicionar Leitíssimo Leitíssimo Iogurte Parcialmente Desnatado 500g R$ 11,89, url='https://trela.com.br/produto/iogurte-parcialmente-desnatado-500g-12082'
						image Iogurte Parcialmente Desnatado 500g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F308dd32a-b35e-483b-affc-2f9dc8d584d8-iogurteparcialmentedesnatado-leiteleiti%CC%81ssimo-12082.1.png&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Leitíssimo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F63190e43-d2eb-4a8c-be92-feb76aa7647a.png&w=32&q=75'
						StaticText Leitíssimo
						heading Iogurte Parcialmente Desnatado 500g
				listitem
					link Yorgus Cottagy Proteico 200g Refrigerado adicionar Yorgus Yorgus Yorgus Cottagy Proteico 200g R$ 9,78, url='https://trela.com.br/produto/yorgus-cottagy-proteico-200g-13284'
						image Yorgus Cottagy Proteico 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F8a6c065a-de54-4785-866e-5718422ebe97.png&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
						StaticText Yorgus
						heading Yorgus Cottagy Proteico 200g
				listitem
					link Manteiga sem Sal em Tablete 200g Refrigerado adicionar Cruzília Cruzília Manteiga sem Sal em Tablete 200g R$ 11,99, url='https://trela.com.br/produto/manteiga-sem-sal-em-tablete-200g-11610'
						image Manteiga sem Sal em Tablete 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F1dd4f2fb-5324-40db-a4ce-ad698bfb02a0-manteigasemsalemtablete-cruzi%CC%81lia-11610.1.png&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Cruzília, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5786d8f5-d4ca-41e6-980a-60bd819b961d.png&w=32&q=75'
						StaticText Cruzília
						heading Manteiga sem Sal em Tablete 200g
			button próximos itens
		heading Avaliações (56)
		paragraph
			StaticText 91
			StaticText %
			StaticText curtiram o produto
		StaticText 1 pessoa comentou
		button Avaliar produto
		article
			image Lia V.
				StaticText LV
			StaticText Lia V.
			time
				StaticText 11/10/2024
			paragraph
				StaticText Gostoso e fresquinho, vou comprar mais depois
	[5571] button remover, center=(689,1048)
	StaticText 1
	[5574] button adicionar, center=(763,1048)
	[5576] button adicionar ao carrinho, center=(1024,1048), inner_text=Adicionar
R$ 9,27
		StaticText Adicionar
		StaticText R$ 9,27
	navigation breadcrumb
		list
			listitem
				link Início, url='https://trela.com.br/'
			listitem
				StaticText /
				link Produtos, url='https://trela.com.br/produto'
			listitem
				StaticText /
				StaticText Queijo cottage 200g
	contentinfo
		region Categorias
			list
				listitem
					link Oferta do Dia até 15% OFF, url='https://trela.com.br/categoria/oferta-do-dia-ate-15-off-180'
				listitem
					link Selecionados para você, url='https://trela.com.br/categoria/selecionados-para-voce-1097'
				listitem
					link Novos na Trela, url='https://trela.com.br/categoria/novos-na-trela-298'
				listitem
					link Especiais de fim de ano, url='https://trela.com.br/categoria/especiais-de-fim-de-ano-1156'
				listitem
					link Hortifruti e ovos, url='https://trela.com.br/categoria/hortifruti-e-ovos-662'
				listitem
					link Queijos e laticínios, url='https://trela.com.br/categoria/queijos-e-laticinios-693'
				listitem
					link Básicos da despensa, url='https://trela.com.br/categoria/basicos-da-despensa-587'
				listitem
					link Carnes, url='https://trela.com.br/categoria/carnes-622'
				listitem
					link Peixes e frutos do mar, url='https://trela.com.br/categoria/peixes-e-frutos-do-mar-681'
				listitem
					link Frios e charcutaria, url='https://trela.com.br/categoria/frios-e-charcutaria-654'
				listitem
					link Padaria e confeitaria, url='https://trela.com.br/categoria/padaria-e-confeitaria-673'
				listitem
					link Refeições práticas, url='https://trela.com.br/categoria/refeicoes-praticas-565'
				listitem
					link Salgados e tortas, url='https://trela.com.br/categoria/salgados-e-tortas-727'
				listitem
					link Pizzas e massas, url='https://trela.com.br/categoria/pizzas-e-massas-686'
				listitem
					link Antepastos e molhos, url='https://trela.com.br/categoria/antepastos-e-molhos-578'
				listitem
					link Castanhas e frutas secas, url='https://trela.com.br/categoria/castanhas-e-frutas-secas-634'
				listitem
					link Snacks, url='https://trela.com.br/categoria/snacks-733'
				listitem
					link Suplementos, url='https://trela.com.br/categoria/suplementos-747'
				listitem
					link Doces e chocolates, url='https://trela.com.br/categoria/doces-e-chocolates-645'
				listitem
					link Sorvetes e açaí, url='https://trela.com.br/categoria/sorvetes-e-acai-742'
				listitem
					link Bebidas, url='https://trela.com.br/categoria/bebidas-599'
				listitem
					link Cafés e Chás, url='https://trela.com.br/categoria/cafes-e-chas-611'
				listitem
					link Cervejas e destilados, url='https://trela.com.br/categoria/cervejas-e-destilados-641'
				listitem
					link Vinhos e espumantes, url='https://trela.com.br/categoria/vinhos-e-espumantes-758'
				listitem
					link Plant-Based, url='https://trela.com.br/categoria/plantbased-224'
		region Sobre a Trela
			list
				listitem
					link Quem somos, url='https://trela.com.br/institucional/quem-somos'
				listitem
					link Carreiras, url='https://jobs.lever.co/trela'
				listitem
					link Dúvidas Frequentes, url='https://trela.com.br/institucional/duvidas-frequentes'
				listitem
					link Política de Privacidade, url='https://trela.com.br/institucional/politica-de-privacidade'
				listitem
					link Termos e condições, url='https://trela.com.br/institucional/termos-de-uso'
				listitem
					link Seja um parceiro, url='https://form.typeform.com/to/MGXdfqU0'
				listitem
					link Entre em contato, url='http://suporte.trela.com.br/'
		region Métodos de pagamento
			list
				listitem
					image logo pix, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-pix.png&w=1920&q=75'
				listitem
					image logo visa, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-visa.png&w=1920&q=75'
				listitem
					image logo mastercard, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-mastercard.png&w=1920&q=75'
				listitem
					image logo diners-club, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-diners-club.png&w=1920&q=75'
				listitem
					image logo american-express, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-american-express.png&w=1920&q=75'
				listitem
					image logo hipercard, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-hipercard.png&w=1920&q=75'
				listitem
					image logo discover, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-discover.png&w=1920&q=75'
				listitem
					image logo elo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-elo.png&w=1920&q=75'
				listitem
					image logo vr, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-vr.png&w=1920&q=75'
				listitem
					image logo sodexo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-sodexo.png&w=1920&q=75'
				listitem
					image logo ticket, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-ticket.png&w=1920&q=75'
				listitem
					image logo caju, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-caju.png&w=1920&q=75'
		separator, orientation='horizontal'
		region Nunca perca uma oferta, baixe o app da Trela
			link Disponível no Google Play, url='https://play.google.com/store/apps/details?id=com.trela.br.marketplace&hl=pt_BR&gl=US'
				image Disponível no Google Play, url='https://trela.com.br/_next/image?url=%2Fimages%2Fgoogle-play.png&w=256&q=75'
			link Disponível na App Store, url='https://apps.apple.com/br/app/trela/id6444369623'
				image Disponível na App Store, url='https://trela.com.br/_next/image?url=%2Fimages%2Fapp-store.png&w=256&q=75'
		separator, orientation='horizontal'
		image Trela
		list
			listitem
				link instagram logo, url='https://www.instagram.com/trela'
					image instagram logo, url='https://d29vvterh1pj9i.cloudfront.net/instagram_57e7afd553.svg'
			listitem
				link linkedin logo, url='https://www.linkedin.com/company/deutrela'
					image linkedin logo, url='https://d29vvterh1pj9i.cloudfront.net/linkedin_ce1dd8540e.svg'
			listitem
				link tiktok logo, url='https://www.tiktok.com/@trelaoficial'
					image tiktok logo, url='https://d29vvterh1pj9i.cloudfront.net/tiktok_443444b5cd.svg'
		StaticText Zapt Tecnologia LTDA CNPJ - 37.896.391/0001-84
	alert, atomic
		StaticText Queijo cottage 200g | Trela
```
</details>

**Reasoning for action:** Clicking on 'Queijo cottage 200g' allows me to access the specific product's details. This step is essential as it prepares me to add the product to my shopping cart, which is necessary for the user to benefit from the discounted price during their online shopping experience.

**Action:** click(3188) # Click on the 'Queijo cottage 200g' product link to view its details.

**Change Description:** The browser navigated to the product detail page for 'Queijo cottage 200g' after clicking on its link, updating the displayed content to show specific product information, including images, pricing, and additional product descriptions.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://trela.com.br/produto/queijo-cottage-200g-12211

https://trela.com.br/categoria/oferta-do-dia-ate-15-off-180

**Content (before/after):** 

```
RootWebArea Queijo cottage 200g | Trela, focused, url='https://trela.com.br/produto/queijo-cottage-200g-12211'
	banner
		navigation
			[5062] link Trela, center=(335,30), url='https://trela.com.br/'
				image Trela
```
<details><summary>Show more</summary>

```
			[5067] textbox O que você está procurando?, center=(960,30), contenteditable=True
			[5069] link Entrar / Cadastrar, center=(1496,30), url='https://trela.com.br/login?callbackUrl=%2Fproduto%2Fqueijo-cottage-200g-12211'
			[5071] button Menu, center=(1602,30)
	main
		image Queijo cottage 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc11f29bb-a64a-4222-a8c6-7bca76aa0b7f-cottage-cruzi%CC%81lia-12211.1.png&w=1920&q=75'
		[5086] div, center=(756,430)
		[5089] link Cruzília, center=(1230,134), url='https://trela.com.br/fornecedor/cruzilia-1833'
		heading Queijo cottage 200g
			[5095] button, center=(1495,219)
		paragraph
			StaticText R$ 10,90
		paragraph
			StaticText R$ 9,27
		StaticText -15
		StaticText %
		[5102] button 91% gostaram • 56 avaliações, center=(1368,339), inner_text=91% gostaram
•
56 avaliações
		separator, orientation='horizontal'
		StaticText Refrigerado
		StaticText 
		StaticText Vegetariano
		StaticText 
		StaticText Low Carb
		StaticText 
		StaticText Sem Glúten
		StaticText 
		StaticText Sem adição de açúcar
		separator, orientation='horizontal'
		[5130] button Só tem na Trela! Não encontramos o preço do produto nos concorrentes monitorados Mais detalhes, center=(1368,537), inner_text=Só tem na Trela! Não encontramos o preço do produto nos concorrentes monitorados
Mais detalhes
			image
			StaticText Só tem na Trela!
		blockquote
			StaticText “
			StaticText Com sabor leve, esse cottage é perfeito para o dia a dia. Com baixo teor de gordura, combina qualidade e ótimo preço.
			StaticText ”
		heading Nota do time de curadoria Trela
		paragraph
			paragraph
				StaticText O Cottage é um queijo com baixo teor de gordura e calorias. Com sabor suave, cremoso, fresco e textura delicada, pode ser consumido puro, com frutas ou mel, adicionado a saladas, omeletes e recheios de tortas, ou ainda usado como substituto do creme de leite em algumas receitas, proporcionando cremosidade e um toque único aos pratos.
		heading Ingredientes
		list
			listitem
				ListMarker •
				StaticText Leite pasteurizado desnatado
			listitem
				ListMarker •
				StaticText nata (creme de leite pasteurizado, estabilizante carragena (INS 407))
			listitem
				ListMarker •
				StaticText cloreto de sódio (sal)
			listitem
				ListMarker •
				StaticText fermento lático
			listitem
				ListMarker •
				StaticText conservador sorbato de potássio (INS 202)
		heading Tabela Nutricional
		table
			rowgroup
				row
					columnheader Porção de 30g (1 fatia)
					columnheader Quantidade por porção
					columnheader VD%
			rowgroup
				row
					cell Valor Energético
					cell 57kcal=239Kj
					cell 3
				row
					cell Carboidratos
					cell 0,3g
					cell 0
				row
					cell Proteínas
					cell 2,7g
					cell 4
				row
					cell Gorduras Totais
					cell 3,7g
					cell 7
				row
					cell Gorduras Saturadas
					cell 5,8g
					cell 26
				row
					cell Gorduras Trans
					cell 0g
					cell -
				row
					cell Fibra Alimentar
					cell 0g
					cell 0
				row
					cell Sódio
					cell 187mg
					cell 8
		region Seleção de produtos semelhantes
			heading Seleção de produtos semelhantes
			list
				listitem
					link Creme de Ricota 200g Refrigerado adicionar Cruzília Cruzília Creme de Ricota 200g R$ 7,90, url='https://trela.com.br/produto/creme-de-ricota-200g-11597'
						image Creme de Ricota 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F511fa9e3-2b7c-4cb9-9735-2078418e6fa1-cremedericota-cruzi%CC%81lia-11597.1.jpg&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Cruzília, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5786d8f5-d4ca-41e6-980a-60bd819b961d.png&w=32&q=75'
						StaticText Cruzília
						heading Creme de Ricota 200g
				listitem
					link Ricota Fresca 400g Refrigerado adicionar Yema Yema Ricota Fresca 400g R$ 7,19, url='https://trela.com.br/produto/ricota-fresca-400g-9630'
						image Ricota Fresca 400g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc1a96a51-3cc3-4118-9d9a-9da86f58df0d-ricotafresca-yema-9630.1.png&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Yema, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fa7b05be7-4418-4575-904b-8cd45b675678.png&w=32&q=75'
						StaticText Yema
						heading Ricota Fresca 400g
				listitem
					link Creme de Queijo Minas Frescal 200g Refrigerado adicionar Cruzília Cruzília Creme de Queijo Minas Frescal 200g R$ 8,90, url='https://trela.com.br/produto/creme-de-queijo-minas-frescal-200g-12206'
						image Creme de Queijo Minas Frescal 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fca08a3fd-1348-405f-9496-a6eaf46ef4f9-queijominasfrescalcremoso-cruzilia-12206.1.jpg&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Cruzília, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5786d8f5-d4ca-41e6-980a-60bd819b961d.png&w=32&q=75'
						StaticText Cruzília
						heading Creme de Queijo Minas Frescal 200g
				listitem
					link Pão multigrãos orgânico de fermentação natural fatiado 600g  Ultrafresco adicionar Tartapão Panificio Tartapão Panificio Pão multigrãos orgânico de fermentação natural fatiado 600g R$ 25,00, url='https://trela.com.br/produto/pao-multigraos-organico-de-fermentacao-natural-fatiado-600g-10967'
						image Pão multigrãos orgânico de fermentação natural fatiado 600g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F062f4827-5d99-4ea8-8412-62ed1f60b782-pa%CC%83omultigra%CC%83osorga%CC%82nicofatiado-tartapa%CC%83opanificio-10967.1.png&w=384&q=75'
						StaticText 
						StaticText Ultrafresco
						button adicionar
						image Tartapão Panificio, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff3fe1d64-4634-4f4f-8d16-8e9c441412f4.png&w=32&q=75'
						StaticText Tartapão Panificio
						heading Pão multigrãos orgânico de fermentação natural fatiado 600g
				listitem
					link Minas Frescal 450g Refrigerado adicionar Yema Yema Minas Frescal 450g R$ 21,99, url='https://trela.com.br/produto/minas-frescal-450g-9634'
						image Minas Frescal 450g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F704744b6-d3c3-4650-b2b1-3715ee25815c-minasfrescal-yema-9634.2.png&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Yema, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fa7b05be7-4418-4575-904b-8cd45b675678.png&w=32&q=75'
						StaticText Yema
						heading Minas Frescal 450g
				listitem
					link Pão clássico orgânico de fermentação natural fatiado 600g  Ultrafresco adicionar Tartapão Panificio Tartapão Panificio Pão clássico orgânico de fermentação natural fatiado 600g R$ 22,00, url='https://trela.com.br/produto/pao-classico-organico-de-fermentacao-natural-fatiado-600g-10966'
						image Pão clássico orgânico de fermentação natural fatiado 600g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F76d356f7-3ae3-4f17-97fc-807d471fa671-pa%CC%83ocla%CC%81ssicoorga%CC%82nicofatiado-tartapa%CC%83opanificio-10966.1.png&w=384&q=75'
						StaticText 
						StaticText Ultrafresco
						button adicionar
						image Tartapão Panificio, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff3fe1d64-4634-4f4f-8d16-8e9c441412f4.png&w=32&q=75'
						StaticText Tartapão Panificio
						heading Pão clássico orgânico de fermentação natural fatiado 600g
				listitem
					link Iogurte Integral 500g Refrigerado adicionar Leitíssimo Leitíssimo Iogurte Integral 500g R$ 11,89, url='https://trela.com.br/produto/iogurte-integral-500g-12083'
						image Iogurte Integral 500g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.amazonaws.com%2Fproducts%2F895cbbba-0d03-4d42-9fc8-4d1404aece54.png&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Leitíssimo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F63190e43-d2eb-4a8c-be92-feb76aa7647a.png&w=32&q=75'
						StaticText Leitíssimo
						heading Iogurte Integral 500g
				listitem
					link Creme de leite - 200g adicionar Leitíssimo Leitíssimo Creme de leite - 200g R$ 6,49, url='https://trela.com.br/produto/creme-de-leite-200g-9265'
						image Creme de leite - 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc8118dfb-3e75-4de6-9a54-65330c114ee8-cremedeleite-leiteleiti%CC%81ssimo-9265.1.png&w=384&q=75'
						button adicionar
						image Leitíssimo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F63190e43-d2eb-4a8c-be92-feb76aa7647a.png&w=32&q=75'
						StaticText Leitíssimo
						heading Creme de leite - 200g
				listitem
					link Queijo Quark 280g Refrigerado adicionar Cruzília Cruzília Queijo Quark 280g R$ 11,90, url='https://trela.com.br/produto/queijo-quark-280g-11611'
						image Queijo Quark 280g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F88ddc012-d04e-47be-b288-51dcfc321ab4.png&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Cruzília, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5786d8f5-d4ca-41e6-980a-60bd819b961d.png&w=32&q=75'
						StaticText Cruzília
						heading Queijo Quark 280g
				listitem
					link Iogurte Parcialmente Desnatado 500g Refrigerado adicionar Leitíssimo Leitíssimo Iogurte Parcialmente Desnatado 500g R$ 11,89, url='https://trela.com.br/produto/iogurte-parcialmente-desnatado-500g-12082'
						image Iogurte Parcialmente Desnatado 500g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F308dd32a-b35e-483b-affc-2f9dc8d584d8-iogurteparcialmentedesnatado-leiteleiti%CC%81ssimo-12082.1.png&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Leitíssimo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F63190e43-d2eb-4a8c-be92-feb76aa7647a.png&w=32&q=75'
						StaticText Leitíssimo
						heading Iogurte Parcialmente Desnatado 500g
				listitem
					link Yorgus Cottagy Proteico 200g Refrigerado adicionar Yorgus Yorgus Yorgus Cottagy Proteico 200g R$ 9,78, url='https://trela.com.br/produto/yorgus-cottagy-proteico-200g-13284'
						image Yorgus Cottagy Proteico 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F8a6c065a-de54-4785-866e-5718422ebe97.png&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
						StaticText Yorgus
						heading Yorgus Cottagy Proteico 200g
				listitem
					link Manteiga sem Sal em Tablete 200g Refrigerado adicionar Cruzília Cruzília Manteiga sem Sal em Tablete 200g R$ 11,99, url='https://trela.com.br/produto/manteiga-sem-sal-em-tablete-200g-11610'
						image Manteiga sem Sal em Tablete 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F1dd4f2fb-5324-40db-a4ce-ad698bfb02a0-manteigasemsalemtablete-cruzi%CC%81lia-11610.1.png&w=384&q=75'
						StaticText Refrigerado
						button adicionar
						image Cruzília, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5786d8f5-d4ca-41e6-980a-60bd819b961d.png&w=32&q=75'
						StaticText Cruzília
						heading Manteiga sem Sal em Tablete 200g
			button próximos itens
		heading Avaliações (56)
		paragraph
			StaticText 91
			StaticText %
			StaticText curtiram o produto
		StaticText 1 pessoa comentou
		button Avaliar produto
		article
			image Lia V.
				StaticText LV
			StaticText Lia V.
			time
				StaticText 11/10/2024
			paragraph
				StaticText Gostoso e fresquinho, vou comprar mais depois
	[5571] button remover, center=(689,1048)
	StaticText 1
	[5574] button adicionar, center=(763,1048)
	[5576] button adicionar ao carrinho, center=(1024,1048), inner_text=Adicionar
R$ 9,27
		StaticText Adicionar
		StaticText R$ 9,27
	navigation breadcrumb
		list
			listitem
				link Início, url='https://trela.com.br/'
			listitem
				StaticText /
				link Produtos, url='https://trela.com.br/produto'
			listitem
				StaticText /
				StaticText Queijo cottage 200g
	contentinfo
		region Categorias
			list
				listitem
					link Oferta do Dia até 15% OFF, url='https://trela.com.br/categoria/oferta-do-dia-ate-15-off-180'
				listitem
					link Selecionados para você, url='https://trela.com.br/categoria/selecionados-para-voce-1097'
				listitem
					link Novos na Trela, url='https://trela.com.br/categoria/novos-na-trela-298'
				listitem
					link Especiais de fim de ano, url='https://trela.com.br/categoria/especiais-de-fim-de-ano-1156'
				listitem
					link Hortifruti e ovos, url='https://trela.com.br/categoria/hortifruti-e-ovos-662'
				listitem
					link Queijos e laticínios, url='https://trela.com.br/categoria/queijos-e-laticinios-693'
				listitem
					link Básicos da despensa, url='https://trela.com.br/categoria/basicos-da-despensa-587'
				listitem
					link Carnes, url='https://trela.com.br/categoria/carnes-622'
				listitem
					link Peixes e frutos do mar, url='https://trela.com.br/categoria/peixes-e-frutos-do-mar-681'
				listitem
					link Frios e charcutaria, url='https://trela.com.br/categoria/frios-e-charcutaria-654'
				listitem
					link Padaria e confeitaria, url='https://trela.com.br/categoria/padaria-e-confeitaria-673'
				listitem
					link Refeições práticas, url='https://trela.com.br/categoria/refeicoes-praticas-565'
				listitem
					link Salgados e tortas, url='https://trela.com.br/categoria/salgados-e-tortas-727'
				listitem
					link Pizzas e massas, url='https://trela.com.br/categoria/pizzas-e-massas-686'
				listitem
					link Antepastos e molhos, url='https://trela.com.br/categoria/antepastos-e-molhos-578'
				listitem
					link Castanhas e frutas secas, url='https://trela.com.br/categoria/castanhas-e-frutas-secas-634'
				listitem
					link Snacks, url='https://trela.com.br/categoria/snacks-733'
				listitem
					link Suplementos, url='https://trela.com.br/categoria/suplementos-747'
				listitem
					link Doces e chocolates, url='https://trela.com.br/categoria/doces-e-chocolates-645'
				listitem
					link Sorvetes e açaí, url='https://trela.com.br/categoria/sorvetes-e-acai-742'
				listitem
					link Bebidas, url='https://trela.com.br/categoria/bebidas-599'
				listitem
					link Cafés e Chás, url='https://trela.com.br/categoria/cafes-e-chas-611'
				listitem
					link Cervejas e destilados, url='https://trela.com.br/categoria/cervejas-e-destilados-641'
				listitem
					link Vinhos e espumantes, url='https://trela.com.br/categoria/vinhos-e-espumantes-758'
				listitem
					link Plant-Based, url='https://trela.com.br/categoria/plantbased-224'
		region Sobre a Trela
			list
				listitem
					link Quem somos, url='https://trela.com.br/institucional/quem-somos'
				listitem
					link Carreiras, url='https://jobs.lever.co/trela'
				listitem
					link Dúvidas Frequentes, url='https://trela.com.br/institucional/duvidas-frequentes'
				listitem
					link Política de Privacidade, url='https://trela.com.br/institucional/politica-de-privacidade'
				listitem
					link Termos e condições, url='https://trela.com.br/institucional/termos-de-uso'
				listitem
					link Seja um parceiro, url='https://form.typeform.com/to/MGXdfqU0'
				listitem
					link Entre em contato, url='http://suporte.trela.com.br/'
		region Métodos de pagamento
			list
				listitem
					image logo pix, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-pix.png&w=1920&q=75'
				listitem
					image logo visa, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-visa.png&w=1920&q=75'
				listitem
					image logo mastercard, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-mastercard.png&w=1920&q=75'
				listitem
					image logo diners-club, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-diners-club.png&w=1920&q=75'
				listitem
					image logo american-express, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-american-express.png&w=1920&q=75'
				listitem
					image logo hipercard, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-hipercard.png&w=1920&q=75'
				listitem
					image logo discover, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-discover.png&w=1920&q=75'
				listitem
					image logo elo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-elo.png&w=1920&q=75'
				listitem
					image logo vr, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-vr.png&w=1920&q=75'
				listitem
					image logo sodexo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-sodexo.png&w=1920&q=75'
				listitem
					image logo ticket, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-ticket.png&w=1920&q=75'
				listitem
					image logo caju, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-caju.png&w=1920&q=75'
		separator, orientation='horizontal'
		region Nunca perca uma oferta, baixe o app da Trela
			link Disponível no Google Play, url='https://play.google.com/store/apps/details?id=com.trela.br.marketplace&hl=pt_BR&gl=US'
				image Disponível no Google Play, url='https://trela.com.br/_next/image?url=%2Fimages%2Fgoogle-play.png&w=256&q=75'
			link Disponível na App Store, url='https://apps.apple.com/br/app/trela/id6444369623'
				image Disponível na App Store, url='https://trela.com.br/_next/image?url=%2Fimages%2Fapp-store.png&w=256&q=75'
		separator, orientation='horizontal'
		image Trela
		list
			listitem
				link instagram logo, url='https://www.instagram.com/trela'
					image instagram logo, url='https://d29vvterh1pj9i.cloudfront.net/instagram_57e7afd553.svg'
			listitem
				link linkedin logo, url='https://www.linkedin.com/company/deutrela'
					image linkedin logo, url='https://d29vvterh1pj9i.cloudfront.net/linkedin_ce1dd8540e.svg'
			listitem
				link tiktok logo, url='https://www.tiktok.com/@trelaoficial'
					image tiktok logo, url='https://d29vvterh1pj9i.cloudfront.net/tiktok_443444b5cd.svg'
		StaticText Zapt Tecnologia LTDA CNPJ - 37.896.391/0001-84
	alert, atomic
		StaticText Queijo cottage 200g | Trela
```
</details>



```
RootWebArea Oferta do Dia até 15% OFF | Trela, focused, url='https://trela.com.br/categoria/oferta-do-dia-ate-15-off-180'
	banner
		navigation
			[6830] link Trela, center=(335,30), url='https://trela.com.br/'
				image Trela
```
<details><summary>Show more</summary>

```
			[6835] textbox O que você está procurando?, center=(960,30), contenteditable=True
			[6837] link Entrar / Cadastrar, center=(1496,30), url='https://trela.com.br/login?callbackUrl=%2Fcategoria%2Foferta-do-dia-ate-15-off-180'
			[6839] button Menu, center=(1602,30)
	main
		heading Oferta do Dia até 15% OFF
		navigation
			region lista de categorias
				list
					listitem
						article
							[6871] link Oferta do Dia até 15% OFF, center=(446,98), url='https://trela.com.br/categoria/oferta-do-dia-ate-15-off-180'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F00180a97-33f3-4eb4-923d-eee91d4cbaa0.png&w=96&q=75'
							[6875] button compartilhar, center=(542,98)
					listitem
						article
							[6879] link Selecionados para você, center=(647,98), url='https://trela.com.br/categoria/selecionados-para-voce-1097'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fea58f86c-8199-4cd3-a72b-dd34789b4f3e.png&w=96&q=75'
					listitem
						article
							[6885] link Novos na Trela, center=(818,98), url='https://trela.com.br/categoria/novos-na-trela-298'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F631f48a8-7c0d-41a0-a6af-0d75ce1dc13c.png&w=96&q=75'
					listitem
						article
							[6891] link Especiais de fim de ano, center=(990,98), url='https://trela.com.br/categoria/especiais-de-fim-de-ano-1156'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F12e2c830-329b-4add-8356-58de664609ab.png&w=96&q=75'
					listitem
						article
							[6897] link Hortifruti e ovos, center=(1161,98), url='https://trela.com.br/categoria/hortifruti-e-ovos-662'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F8c170965-16cd-4531-8023-c433f1af7c70.png&w=96&q=75'
					listitem
						article
							[6903] link Queijos e laticínios, center=(1333,98), url='https://trela.com.br/categoria/queijos-e-laticinios-693'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fc49fcac4-9824-422c-a80e-babc86875214.png&w=96&q=75'
					listitem
						article
							[6909] link Básicos da despensa, center=(1504,98), url='https://trela.com.br/categoria/basicos-da-despensa-587'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F198dc6a8-b72d-40e6-bdf8-1e28ad8e3b80.png&w=96&q=75'
					listitem
						article
							link Carnes, url='https://trela.com.br/categoria/carnes-622'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F721a0006-f25a-421d-8af9-19b5a20980a5.png&w=96&q=75'
					listitem
						article
							link Peixes e frutos do mar, url='https://trela.com.br/categoria/peixes-e-frutos-do-mar-681'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F8657ee04-91e3-4f37-a8a6-d10a73ae2a14.png&w=96&q=75'
					listitem
						article
							link Frios e charcutaria, url='https://trela.com.br/categoria/frios-e-charcutaria-654'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fc6d840c0-7077-43b8-829b-31bedd0de1d6.png&w=96&q=75'
					listitem
						article
							link Padaria e confeitaria, url='https://trela.com.br/categoria/padaria-e-confeitaria-673'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F5d90de96-9ae3-4c3d-b413-8b564d4a360e.png&w=96&q=75'
					listitem
						article
							link Refeições práticas, url='https://trela.com.br/categoria/refeicoes-praticas-565'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fe4aaba8f-397b-4aa3-beac-4b7dd89cb0ac.png&w=96&q=75'
					listitem
						article
							link Salgados e tortas, url='https://trela.com.br/categoria/salgados-e-tortas-727'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fc034a3b9-b196-4329-b332-3f93558df7d2.png&w=96&q=75'
					listitem
						article
							link Pizzas e massas, url='https://trela.com.br/categoria/pizzas-e-massas-686'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F0862abb7-d513-4c35-b983-e665616a748b.png&w=96&q=75'
					listitem
						article
							link Antepastos e molhos, url='https://trela.com.br/categoria/antepastos-e-molhos-578'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F13aa370a-7702-4aa9-988f-5d1dc141a3a9.png&w=96&q=75'
					listitem
						article
							link Castanhas e frutas secas, url='https://trela.com.br/categoria/castanhas-e-frutas-secas-634'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fb5798c8f-465e-45d1-aa06-0c67a7b55bc7.png&w=96&q=75'
					listitem
						article
							link Snacks, url='https://trela.com.br/categoria/snacks-733'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F2a5d617f-03a9-40bf-9df1-c3f4e37506d6.png&w=96&q=75'
					listitem
						article
							link Suplementos, url='https://trela.com.br/categoria/suplementos-747'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fda566dba-d86f-4f48-a463-ebdf864b09f2.png&w=96&q=75'
					listitem
						article
							link Doces e chocolates, url='https://trela.com.br/categoria/doces-e-chocolates-645'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fb4e1a295-beeb-4321-92fc-b15c08dfb512.png&w=96&q=75'
					listitem
						article
							link Sorvetes e açaí, url='https://trela.com.br/categoria/sorvetes-e-acai-742'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F26b77fa7-f6f9-4df0-b3d7-0f33bc40b6e0.png&w=96&q=75'
					listitem
						article
							link Bebidas, url='https://trela.com.br/categoria/bebidas-599'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F2ac71ac0-8ce3-4125-acd8-8510853260cf.png&w=96&q=75'
					listitem
						article
							link Cafés e Chás, url='https://trela.com.br/categoria/cafes-e-chas-611'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Feeb697f1-eaf4-4c9b-9673-fe0e1a219a89.png&w=96&q=75'
					listitem
						article
							link Cervejas e destilados, url='https://trela.com.br/categoria/cervejas-e-destilados-641'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2Fa79f76db-bf33-4c5e-8306-d89033c6c30e.png&w=96&q=75'
					listitem
						article
							link Vinhos e espumantes, url='https://trela.com.br/categoria/vinhos-e-espumantes-758'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F7261bc0b-70f9-4b92-ac31-92cb3b214579.png&w=48&q=75'
					listitem
						article
							link Plant-Based, url='https://trela.com.br/categoria/plantbased-224'
								image, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Ftags%2F7aac7d2e-64eb-44ef-954f-723aa42432bd.png&w=48&q=75'
				[7023] button próximos itens, center=(1588,98)
		heading Tudo
		navigation
			[7030] button Filtrar, center=(403,155)
			[7033] button Tudo, center=(491,155)
			separator, orientation='horizontal'
		[7041] link Queijo cottage 200g 51 Refrigerado adicionar 1 unidade remover Cruzília Cruzília Queijo cottage 200g R$ 10,90 R$ 9,27 -15%, center=(457,355), inner_text=51
Refrigerado
1
Cruzília
Queijo cottage 200g
R$ 10,90
R$ 9,27
-15%, url='https://trela.com.br/produto/queijo-cottage-200g-12211'
			image Queijo cottage 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc11f29bb-a64a-4222-a8c6-7bca76aa0b7f-cottage-cruzi%CC%81lia-12211.1.png&w=1920&q=75'
			StaticText 51
			StaticText Refrigerado
			button adicionar
			button remover
			image Cruzília, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5786d8f5-d4ca-41e6-980a-60bd819b961d.png&w=32&q=75'
			StaticText Cruzília
			heading Queijo cottage 200g
		[7072] link Pão sem glúten tradicional 500g - Congelado 19 Congelado adicionar Pão do Céu Pão do Céu Pão sem glúten tradicional 500g - Congelado R$ 20,90 R$ 17,77 -15%, center=(658,355), inner_text=19
Congelado
Pão do Céu
Pão sem glúten tradicional 500g - Congelado
R$ 20,90
R$ 17,77
-15%, url='https://trela.com.br/produto/pao-sem-gluten-tradicional-500g-congelado-12555'
			image Pão sem glúten tradicional 500g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F74dcb0e2-aa6c-4909-8d05-5ad41199945a.png&w=384&q=75'
			StaticText 19
			StaticText Congelado
			button adicionar
			image Pão do Céu, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F8c47b61c-1745-4522-a1c3-5e3592a4f157.png&w=32&q=75'
			StaticText Pão do Céu
			heading Pão sem glúten tradicional 500g - Congelado
		[7099] link Guacamole Sr. Guaca 200g 39 Refrigerado adicionar Sr. Guaca Sr. Guaca Guacamole Sr. Guaca 200g R$ 15,29 R$ 13,00 -15%, center=(859,355), inner_text=39
Refrigerado
Sr. Guaca
Guacamole Sr. Guaca 200g
R$ 15,29
R$ 13,00
-15%, url='https://trela.com.br/produto/guacamole-sr-guaca-200g-11448'
			image Guacamole Sr. Guaca 200g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F692edf71-8478-48b9-b4b5-dc3fe356a7ec-guacamolesrguaca-srguaca-11448.1.png&w=384&q=75'
			StaticText 39
			StaticText Refrigerado
			button adicionar
			image Sr. Guaca, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F6df05adb-ce6b-4c5b-9412-fac3eef999fe.png&w=32&q=75'
			StaticText Sr. Guaca
			heading Guacamole Sr. Guaca 200g
		[7126] link Suco de laranja 900ml 42 Refrigerado adicionar Xandô Xandô Suco de laranja 900ml R$ 15,90 R$ 13,52 -15%, center=(1061,355), inner_text=42
Refrigerado
Xandô
Suco de laranja 900ml
R$ 15,90
R$ 13,52
-15%, url='https://trela.com.br/produto/suco-de-laranja-900ml-10863'
			image Suco de laranja 900ml, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fd2cc0667-b893-4983-b41e-fcf7c6a60fcb-sucodelaranja-xando%CC%82-10863.1.png&w=384&q=75'
			StaticText 42
			StaticText Refrigerado
			button adicionar
			image Xandô, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F77360f6b-5746-43ec-ae31-67d69718f6d1.png&w=32&q=75'
			StaticText Xandô
			heading Suco de laranja 900ml
		[7153] link Iogurte Natural de Leite de Ovelha 140g 38 Refrigerado adicionar Queijaria Rima Queijaria Rima Iogurte Natural de Leite de Ovelha 140g R$ 6,12 R$ 5,20 -15%, center=(1262,355), inner_text=38
Refrigerado
Queijaria Rima
Iogurte Natural de Leite de Ovelha 140g
R$ 6,12
R$ 5,20
-15%, url='https://trela.com.br/produto/iogurte-natural-de-leite-de-ovelha-140g-11450'
			image Iogurte Natural de Leite de Ovelha 140g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F32111064-0b47-4689-9a9d-0d66b9bfac2e.png&w=384&q=75'
			StaticText 38
			StaticText Refrigerado
			button adicionar
			image Queijaria Rima, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fsuppliers%2F8265229b-2829-4816-9b2d-3d394b18628b.png&w=32&q=75'
			StaticText Queijaria Rima
			heading Iogurte Natural de Leite de Ovelha 140g
		[7180] link Pão 100% integral 450g - Congelado 24 Congelado adicionar Pão do Céu Pão do Céu Pão 100% integral 450g - Congelado R$ 18,40 R$ 15,64 -15%, center=(1463,355), inner_text=24
Congelado
Pão do Céu
Pão 100% integral 450g - Congelado
R$ 18,40
R$ 15,64
-15%, url='https://trela.com.br/produto/pao-100-integral-450g-congelado-12554'
			image Pão 100% integral 450g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fa8224eb4-7378-4a4f-98d8-fea03fed8bdc-p%C3%A3o100_integral-p%C3%A3odoc%C3%A9u-12554.1.png&w=384&q=75'
			StaticText 24
			StaticText Congelado
			button adicionar
			image Pão do Céu, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F8c47b61c-1745-4522-a1c3-5e3592a4f157.png&w=32&q=75'
			StaticText Pão do Céu
			heading Pão 100% integral 450g - Congelado
		[7208] link Natural Whey de Coco 21g de proteína - 250g 29 Refrigerado adicionar Verde Campo Verde Campo Natural Whey de Coco 21g de proteína - 250g R$ 8,69 R$ 7,39 -15%, center=(457,658), inner_text=29
Refrigerado
Verde Campo
Natural Whey de Coco 21g de proteína - 250g
R$ 8,69
R$ 7,39
-15%, url='https://trela.com.br/produto/natural-whey-de-coco-21g-de-proteina-250g-11527'
			image Natural Whey de Coco 21g de proteína - 250g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F0ce6f300-be4a-46c8-b164-58d6f7e9be3b.png&w=384&q=75'
			StaticText 29
			StaticText Refrigerado
			button adicionar
			image Verde Campo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb045f0a8-3d1e-4064-9cc2-d188dfa19844.png&w=32&q=75'
			StaticText Verde Campo
			heading Natural Whey de Coco 21g de proteína - 250g
		[7235] link Pão batata doce orgânico 450g - Congelado 25 Congelado adicionar Pão do Céu Pão do Céu Pão batata doce orgânico 450g - Congelado R$ 18,40 R$ 15,64 -15%, center=(658,658), inner_text=25
Congelado
Pão do Céu
Pão batata doce orgânico 450g - Congelado
R$ 18,40
R$ 15,64
-15%, url='https://trela.com.br/produto/pao-batata-doce-organico-450g-congelado-12553'
			image Pão batata doce orgânico 450g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fe63e8495-d4c3-4195-8228-5d9888b36cd3-p%C3%A3obatatadoceorg%C3%A2nico-p%C3%A3odoc%C3%A9u-12553.1.png&w=384&q=75'
			StaticText 25
			StaticText Congelado
			button adicionar
			image Pão do Céu, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F8c47b61c-1745-4522-a1c3-5e3592a4f157.png&w=32&q=75'
			StaticText Pão do Céu
			heading Pão batata doce orgânico 450g - Congelado
		[7262] link Yorgus grego desnatado natural 500g 22 Refrigerado adicionar Yorgus Yorgus Yorgus grego desnatado natural 500g R$ 29,90 R$ 25,42 -15%, center=(859,658), inner_text=22
Refrigerado
Yorgus
Yorgus grego desnatado natural 500g
R$ 29,90
R$ 25,42
-15%, url='https://trela.com.br/produto/yorgus-grego-desnatado-natural-500g-12905'
			image Yorgus grego desnatado natural 500g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fd1c5638d-0592-41b5-83f1-56c8747f5607.png&w=384&q=75'
			StaticText 22
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus grego desnatado natural 500g
		[7289] link Pão energia das sementes 380g - Congelado 11 Congelado adicionar House of Maya House of Maya Pão energia das sementes 380g - Congelado R$ 30,90 R$ 26,27 -15%, center=(1061,658), inner_text=11
Congelado
House of Maya
Pão energia das sementes 380g - Congelado
R$ 30,90
R$ 26,27
-15%, url='https://trela.com.br/produto/pao-energia-das-sementes-380g-congelado-12768'
			image Pão energia das sementes 380g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F96a16c52-2c24-46c2-8762-21db570a0b3d-p%C3%A3oenergiadassementes-houseofmaya-12768.1.png&w=384&q=75'
			StaticText 11
			StaticText Congelado
			button adicionar
			image House of Maya, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fdc9155eb-7b51-4963-b8d8-fbbb9e369d3d.png&w=32&q=75'
			StaticText House of Maya
			heading Pão energia das sementes 380g - Congelado
		[7316] link Tofu Orgânico Natural 450g - Refrigerado 13  Ultrafresco adicionar SÍtio Boa Esperança SÍtio Boa Esperança Tofu Orgânico Natural 450g - Refrigerado R$ 28,90 R$ 24,57 -15%, center=(1262,658), inner_text=13
Ultrafresco
SÍtio Boa Esperança
Tofu Orgânico Natural 450g - Refrigerado
R$ 28,90
R$ 24,57
-15%, url='https://trela.com.br/produto/tofu-organico-natural-450g-refrigerado-11583'
			image Tofu Orgânico Natural 450g - Refrigerado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F93093a13-4118-4fb4-b283-b652827a7d85-tofuorga%CC%82niconatural-si%CC%81tioboaesperanc%CC%A7a-11583.1.png&w=384&q=75'
			StaticText 13
			StaticText 
			StaticText Ultrafresco
			button adicionar
			image SÍtio Boa Esperança, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F80eedb37-bb57-4585-81c1-086cdfa83a60.png&w=32&q=75'
			StaticText SÍtio Boa Esperança
			heading Tofu Orgânico Natural 450g - Refrigerado
		[7343] link Bolo de limão siciliano e amêndoas 270g - Congelado Congelado adicionar House of Maya House of Maya Bolo de limão siciliano e amêndoas 270g - Congelado R$ 25,90 R$ 22,02 -15%, center=(1463,658), inner_text=Congelado
House of Maya
Bolo de limão siciliano e amêndoas 270g - Congelado
R$ 25,90
R$ 22,02
-15%, url='https://trela.com.br/produto/bolo-de-limao-siciliano-e-amendoas-270g-congelado-12765'
			image Bolo de limão siciliano e amêndoas 270g - Congelado, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F4b5758a7-3cb8-4c51-9db5-1eb34a276843-bolodelim%C3%A3osicilianoeam%C3%AAndoas-houseofmaya-12765.1.png&w=384&q=75'
			StaticText Congelado
			button adicionar
			image House of Maya, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fdc9155eb-7b51-4963-b8d8-fbbb9e369d3d.png&w=32&q=75'
			StaticText House of Maya
			heading Bolo de limão siciliano e amêndoas 270g - Congelado
		[7368] link Yorgus grego natural 0% gordura 130g 15 Refrigerado adicionar Yorgus Yorgus Yorgus grego natural 0% gordura 130g R$ 8,49 R$ 7,22 -15%, center=(457,961), inner_text=15
Refrigerado
Yorgus
Yorgus grego natural 0% gordura 130g
R$ 8,49
R$ 7,22
-15%, url='https://trela.com.br/produto/yorgus-grego-natural-0-gordura-130g-11531'
			image Yorgus grego natural 0% gordura 130g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff4f3624a-a448-44e1-936e-50984edb5ae5-yorgusgregonatural0_gordura-yorgus-11531.1.png&w=384&q=75'
			StaticText 15
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus grego natural 0% gordura 130g
		[7395] link Iogurte de Mel 170ml 38 Refrigerado adicionar Delicari Delicari Iogurte de Mel 170ml R$ 7,10 R$ 6,04 -15%, center=(658,961), inner_text=38
Refrigerado
Delicari
Iogurte de Mel 170ml
R$ 7,10
R$ 6,04
-15%, url='https://trela.com.br/produto/iogurte-de-mel-170ml-9252'
			image Iogurte de Mel 170ml, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F61c7e0ba-8841-481d-89ca-56f2b59d1d02-iogurtedemell-delicari-9252.1.png&w=384&q=75'
			StaticText 38
			StaticText Refrigerado
			button adicionar
			image Delicari, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F2403b2c8-dce9-4d5c-846b-0ff0be5d1868.png&w=32&q=75'
			StaticText Delicari
			heading Iogurte de Mel 170ml
		[7422] link Ovos caipiras com ômega 3 orgânicos 10 Unidades 22 adicionar Fazenda da Toca Fazenda da Toca Ovos caipiras com ômega 3 orgânicos 10 Unidades R$ 15,29 R$ 13,00 -15%, center=(859,961), inner_text=22
Fazenda da Toca
Ovos caipiras com ômega 3 orgânicos 10 Unidades
R$ 15,29
R$ 13,00
-15%, url='https://trela.com.br/produto/ovos-caipiras-com-omega-3-organicos-10-unidades-13294'
			image Ovos caipiras com ômega 3 orgânicos 10 Unidades, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb10cacb8-9748-43c8-8724-ada849cce6d9.png&w=384&q=75'
			StaticText 22
			button adicionar
			image Fazenda da Toca, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F4a8a125a-4069-4776-b8dc-a16acbd5e4a3.png&w=32&q=75'
			StaticText Fazenda da Toca
			heading Ovos caipiras com ômega 3 orgânicos 10 Unidades
		[7444] link Yorgus desnatado com mel silvestre orgânico 130g 13 Refrigerado adicionar Yorgus Yorgus Yorgus desnatado com mel silvestre orgânico 130g R$ 8,49 R$ 7,22 -15%, center=(1061,957), inner_text=13
Refrigerado
Yorgus
Yorgus desnatado com mel silvestre orgânico 130g
R$ 8,49
R$ 7,22
-15%, url='https://trela.com.br/produto/yorgus-desnatado-com-mel-silvestre-organico-130g-12904'
			image Yorgus desnatado com mel silvestre orgânico 130g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F620fcaa6-9327-4207-8d93-93ef0b5c7434-yorgusdesnatadocommelsilvestreorga%CC%82nico-yorgus-12904.1.png&w=384&q=75'
			StaticText 13
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus desnatado com mel silvestre orgânico 130g
		[7471] link Ovos caipiras orgânicos 18 Unidades 19 adicionar Fazenda da Toca Fazenda da Toca Ovos caipiras orgânicos 18 Unidades R$ 27,89 R$ 23,71 -15%, center=(1262,961), inner_text=19
Fazenda da Toca
Ovos caipiras orgânicos 18 Unidades
R$ 27,89
R$ 23,71
-15%, url='https://trela.com.br/produto/ovos-caipiras-organicos-18-unidades-13295'
			image Ovos caipiras orgânicos 18 Unidades, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F4376eae7-dffe-4492-93e1-5a7ef27e4815.png&w=384&q=75'
			StaticText 19
			button adicionar
			image Fazenda da Toca, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F4a8a125a-4069-4776-b8dc-a16acbd5e4a3.png&w=32&q=75'
			StaticText Fazenda da Toca
			heading Ovos caipiras orgânicos 18 Unidades
		[7493] link Iogurte de morango Lacfree 500g 21 Refrigerado adicionar Verde Campo Verde Campo Iogurte de morango Lacfree 500g R$ 8,50 R$ 7,23 -15%, center=(1463,961), inner_text=21
Refrigerado
Verde Campo
Iogurte de morango Lacfree 500g
R$ 8,50
R$ 7,23
-15%, url='https://trela.com.br/produto/iogurte-de-morango-lacfree-500g-11523'
			image Iogurte de morango Lacfree 500g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fc5c76417-6de9-4eb4-b8e9-2b5b679b096f.png&w=384&q=75'
			StaticText 21
			StaticText Refrigerado
			button adicionar
			image Verde Campo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb045f0a8-3d1e-4064-9cc2-d188dfa19844.png&w=32&q=75'
			StaticText Verde Campo
			heading Iogurte de morango Lacfree 500g
		link Natural Whey de Banana 14g de proteína - 250g 19 Refrigerado adicionar Verde Campo Verde Campo Natural Whey de Banana 14g de proteína - 250g R$ 7,90 R$ 6,72 -15%, url='https://trela.com.br/produto/natural-whey-de-banana-14g-de-proteina-250g-11525'
			image Natural Whey de Banana 14g de proteína - 250g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F0a78e758-8483-4d8c-b1fb-b1b506197a37.png&w=384&q=75'
			StaticText 19
			StaticText Refrigerado
			button adicionar
			image Verde Campo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb045f0a8-3d1e-4064-9cc2-d188dfa19844.png&w=32&q=75'
			StaticText Verde Campo
			heading Natural Whey de Banana 14g de proteína - 250g
		link Yorgus grego integral de baunilha 130g Refrigerado adicionar Yorgus Yorgus Yorgus grego integral de baunilha 130g R$ 8,49 R$ 7,22 -15%, url='https://trela.com.br/produto/yorgus-grego-integral-de-baunilha-130g-11536'
			image Yorgus grego integral de baunilha 130g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5beb0575-f7fc-47e9-b20b-48077690d0b4-yorgusgregointegraldebaunilha-yorgus-11536.1.png&w=384&q=75'
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus grego integral de baunilha 130g
		link Yorgus grego de frutas silvestres 130g 19 Refrigerado adicionar Yorgus Yorgus Yorgus grego de frutas silvestres 130g R$ 8,49 R$ 7,22 -15%, url='https://trela.com.br/produto/yorgus-grego-de-frutas-silvestres-130g-11534'
			image Yorgus grego de frutas silvestres 130g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F7281bf48-4d8f-4df3-aca0-190f180d84ae-yorgusgregodefrutassilvestres-yorgus-11534.1.png&w=384&q=75'
			StaticText 19
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus grego de frutas silvestres 130g
		link Yorgus completo de frutas silvestres 250g 19 Refrigerado adicionar Yorgus Yorgus Yorgus completo de frutas silvestres 250g R$ 12,49 R$ 10,62 -15%, url='https://trela.com.br/produto/yorgus-completo-de-frutas-silvestres-250g-11540'
			image Yorgus completo de frutas silvestres 250g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fdb8b1b05-fce2-4acb-88f5-0620f58c87db-yorguscompletodefrutassilvestres-yorgus-11540.1.png&w=384&q=75'
			StaticText 19
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus completo de frutas silvestres 250g
		link Yorgus completo de baunilha 250g Refrigerado adicionar Yorgus Yorgus Yorgus completo de baunilha 250g R$ 12,49 R$ 10,62 -15%, url='https://trela.com.br/produto/yorgus-completo-de-baunilha-250g-11538'
			image Yorgus completo de baunilha 250g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F754021ad-2e7f-4dcc-99ac-0bf81d4f2c53-yorguscompletodebaunilha-yorgus-11538.1.png&w=384&q=75'
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus completo de baunilha 250g
		link Yorgus grego integral de coco 130g 14 Refrigerado adicionar Yorgus Yorgus Yorgus grego integral de coco 130g R$ 8,49 R$ 7,22 -15%, url='https://trela.com.br/produto/yorgus-grego-integral-de-coco-130g-11537'
			image Yorgus grego integral de coco 130g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5acc7a4c-efb3-4e14-bc0c-db71bd0f0426-yorgusgregointegraldecoco-yorgus-11537.1.png&w=384&q=75'
			StaticText 14
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus grego integral de coco 130g
		link Yorgus grego integral 4% 500g 10 Refrigerado adicionar Yorgus Yorgus Yorgus grego integral 4% 500g R$ 29,90 R$ 25,42 -15%, url='https://trela.com.br/produto/yorgus-grego-integral-4-500g-12908'
			image Yorgus grego integral 4% 500g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F16e52a84-9d1b-4e0f-9b12-8bac2f0d4568.png&w=384&q=75'
			StaticText 10
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus grego integral 4% 500g
		link Leite em Pó de Castanha-do-Brasil 240g adicionar Mahta Mahta Leite em Pó de Castanha-do-Brasil 240g R$ 99,20 R$ 84,32 -15%, url='https://trela.com.br/produto/leite-em-po-de-castanhadobrasil-240g-13091'
			image Leite em Pó de Castanha-do-Brasil 240g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5e39ffa6-f57c-4f7c-929f-e429d0445ba3-leiteempo%CC%81decastanhadobrasil-mahta-13091.1.png&w=384&q=75'
			button adicionar
			image Mahta, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F5274696a-1c75-4f44-9627-f0a603d248c4.png&w=32&q=75'
			StaticText Mahta
			heading Leite em Pó de Castanha-do-Brasil 240g
		link Yorgus Kyds sabor baunilha 100g Refrigerado adicionar Yorgus Yorgus Yorgus Kyds sabor baunilha 100g R$ 7,29 R$ 6,20 -15%, url='https://trela.com.br/produto/yorgus-kyds-sabor-baunilha-100g-12910'
			image Yorgus Kyds sabor baunilha 100g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F92420764-356a-4954-ae60-aed473efcd43.png&w=384&q=75'
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Yorgus Kyds sabor baunilha 100g
		link Iogurte vegetal natural yúti 150g Refrigerado adicionar Yúti Yúti Iogurte vegetal natural yúti 150g R$ 13,90 R$ 11,82 -15%, url='https://trela.com.br/produto/iogurte-vegetal-natural-yuti-150g-12939'
			image Iogurte vegetal natural yúti 150g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Ff3bd90b9-1306-4dc3-9d0e-65af1d808357.png&w=384&q=75'
			StaticText Refrigerado
			button adicionar
			image Yúti, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fdbd93bba-817d-4ea5-a6bc-950a2871aaaf.png&w=32&q=75'
			StaticText Yúti
			heading Iogurte vegetal natural yúti 150g
		link Kefir Reggula Desnatado com Mel 500g Refrigerado adicionar Yorgus Yorgus Kefir Reggula Desnatado com Mel 500g R$ 16,90 R$ 14,37 -15%, url='https://trela.com.br/produto/kefir-reggula-desnatado-com-mel-500g-12907'
			image Kefir Reggula Desnatado com Mel 500g, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fb0f11c37-677c-43e0-b188-681dd0188e51.png&w=384&q=75'
			StaticText Refrigerado
			button adicionar
			image Yorgus, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F283b83c8-80bf-4ee7-8a5d-7fa6ec27a4c3.png&w=32&q=75'
			StaticText Yorgus
			heading Kefir Reggula Desnatado com Mel 500g
		link Pink lemonade 1L Refrigerado adicionar Greenpeople Greenpeople Pink lemonade 1L R$ 19,99 R$ 16,99 -15%, url='https://trela.com.br/produto/pink-lemonade-1l-12707'
			image Pink lemonade 1L, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2Fab6b2530-28f2-40bb-bd25-ab48f61d1d98-pinklemonade-greenpeople-12707.1.png&w=384&q=75'
			StaticText Refrigerado
			button adicionar
			image Greenpeople, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fprod-zapt-images.s3.sa-east-1.amazonaws.com%2Fproducts%2F842eedcb-7efa-4496-bdde-61f9522f26fb.png&w=32&q=75'
			StaticText Greenpeople
			heading Pink lemonade 1L
	navigation breadcrumb
		list
			listitem
				link Início, url='https://trela.com.br/'
			listitem
				StaticText /
				link Categorias, url='https://trela.com.br/categoria'
			listitem
				StaticText /
				StaticText Oferta do Dia até 15% OFF
	contentinfo
		region Categorias
			list
				listitem
					link Oferta do Dia até 15% OFF, url='https://trela.com.br/categoria/oferta-do-dia-ate-15-off-180'
				listitem
					link Selecionados para você, url='https://trela.com.br/categoria/selecionados-para-voce-1097'
				listitem
					link Novos na Trela, url='https://trela.com.br/categoria/novos-na-trela-298'
				listitem
					link Especiais de fim de ano, url='https://trela.com.br/categoria/especiais-de-fim-de-ano-1156'
				listitem
					link Hortifruti e ovos, url='https://trela.com.br/categoria/hortifruti-e-ovos-662'
				listitem
					link Queijos e laticínios, url='https://trela.com.br/categoria/queijos-e-laticinios-693'
				listitem
					link Básicos da despensa, url='https://trela.com.br/categoria/basicos-da-despensa-587'
				listitem
					link Carnes, url='https://trela.com.br/categoria/carnes-622'
				listitem
					link Peixes e frutos do mar, url='https://trela.com.br/categoria/peixes-e-frutos-do-mar-681'
				listitem
					link Frios e charcutaria, url='https://trela.com.br/categoria/frios-e-charcutaria-654'
				listitem
					link Padaria e confeitaria, url='https://trela.com.br/categoria/padaria-e-confeitaria-673'
				listitem
					link Refeições práticas, url='https://trela.com.br/categoria/refeicoes-praticas-565'
				listitem
					link Salgados e tortas, url='https://trela.com.br/categoria/salgados-e-tortas-727'
				listitem
					link Pizzas e massas, url='https://trela.com.br/categoria/pizzas-e-massas-686'
				listitem
					link Antepastos e molhos, url='https://trela.com.br/categoria/antepastos-e-molhos-578'
				listitem
					link Castanhas e frutas secas, url='https://trela.com.br/categoria/castanhas-e-frutas-secas-634'
				listitem
					link Snacks, url='https://trela.com.br/categoria/snacks-733'
				listitem
					link Suplementos, url='https://trela.com.br/categoria/suplementos-747'
				listitem
					link Doces e chocolates, url='https://trela.com.br/categoria/doces-e-chocolates-645'
				listitem
					link Sorvetes e açaí, url='https://trela.com.br/categoria/sorvetes-e-acai-742'
				listitem
					link Bebidas, url='https://trela.com.br/categoria/bebidas-599'
				listitem
					link Cafés e Chás, url='https://trela.com.br/categoria/cafes-e-chas-611'
				listitem
					link Cervejas e destilados, url='https://trela.com.br/categoria/cervejas-e-destilados-641'
				listitem
					link Vinhos e espumantes, url='https://trela.com.br/categoria/vinhos-e-espumantes-758'
				listitem
					link Plant-Based, url='https://trela.com.br/categoria/plantbased-224'
		region Sobre a Trela
			list
				listitem
					link Quem somos, url='https://trela.com.br/institucional/quem-somos'
				listitem
					link Carreiras, url='https://jobs.lever.co/trela'
				listitem
					link Dúvidas Frequentes, url='https://trela.com.br/institucional/duvidas-frequentes'
				listitem
					link Política de Privacidade, url='https://trela.com.br/institucional/politica-de-privacidade'
				listitem
					link Termos e condições, url='https://trela.com.br/institucional/termos-de-uso'
				listitem
					link Seja um parceiro, url='https://form.typeform.com/to/MGXdfqU0'
				listitem
					link Entre em contato, url='http://suporte.trela.com.br/'
		region Métodos de pagamento
			list
				listitem
					image logo pix, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-pix.png&w=1920&q=75'
				listitem
					image logo visa, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-visa.png&w=1920&q=75'
				listitem
					image logo mastercard, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-mastercard.png&w=1920&q=75'
				listitem
					image logo diners-club, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-diners-club.png&w=1920&q=75'
				listitem
					image logo american-express, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-american-express.png&w=1920&q=75'
				listitem
					image logo hipercard, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-hipercard.png&w=1920&q=75'
				listitem
					image logo discover, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-discover.png&w=1920&q=75'
				listitem
					image logo elo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-elo.png&w=1920&q=75'
				listitem
					image logo vr, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-vr.png&w=1920&q=75'
				listitem
					image logo sodexo, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-sodexo.png&w=1920&q=75'
				listitem
					image logo ticket, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-ticket.png&w=1920&q=75'
				listitem
					image logo caju, url='https://trela.com.br/_next/image?url=https%3A%2F%2Fd29vvterh1pj9i.cloudfront.net%2Fassets%2Fcard-brand-caju.png&w=1920&q=75'
		separator, orientation='horizontal'
		region Nunca perca uma oferta, baixe o app da Trela
			link Disponível no Google Play, url='https://play.google.com/store/apps/details?id=com.trela.br.marketplace&hl=pt_BR&gl=US'
				image Disponível no Google Play, url='https://trela.com.br/_next/image?url=%2Fimages%2Fgoogle-play.png&w=256&q=75'
			link Disponível na App Store, url='https://apps.apple.com/br/app/trela/id6444369623'
				image Disponível na App Store, url='https://trela.com.br/_next/image?url=%2Fimages%2Fapp-store.png&w=256&q=75'
		separator, orientation='horizontal'
		image Trela
		list
			listitem
				link instagram logo, url='https://www.instagram.com/trela'
					image instagram logo, url='https://d29vvterh1pj9i.cloudfront.net/instagram_57e7afd553.svg'
			listitem
				link linkedin logo, url='https://www.linkedin.com/company/deutrela'
					image linkedin logo, url='https://d29vvterh1pj9i.cloudfront.net/linkedin_ce1dd8540e.svg'
			listitem
				link tiktok logo, url='https://www.tiktok.com/@trelaoficial'
					image tiktok logo, url='https://d29vvterh1pj9i.cloudfront.net/tiktok_443444b5cd.svg'
		StaticText Zapt Tecnologia LTDA CNPJ - 37.896.391/0001-84
	[7964] button abrir carrinho, center=(960,1016), inner_text=Ver carrinho
1
		StaticText Ver carrinho
	alert, atomic
		StaticText Oferta do Dia até 15% OFF | Trela
```
</details>

**Reasoning for action:** By clicking the 'Adicionar ao carrinho' button, I am directly adding the product that the user is interested in to their shopping cart. This action fulfills the user's goal of accessing discounted products quickly and facilitates the next step in the shopping experience by displaying updated pricing and availability in the cart.

**Action:** click(5576) # Click on the 'Adicionar ao carrinho' button to add the Queijo cottage 200g to the cart.

**Change Description:** After clicking the 'Adicionar ao carrinho' button for Queijo cottage 200g, the browser state changed to reflect the item being added to the shopping cart, now showing an updated main interface with details indicating that the product is part of the 'Oferta do Dia até 15% OFF' section, including pricing information, updated availability, and a button to view the shopping cart.

**Screenshot before:****Screenshot after:**---


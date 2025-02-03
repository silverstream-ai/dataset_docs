# Task

**User Navigation on Zazos Blog**

As a Zazos customer,
I explore the blog content for insights and updates,
so that I can stay informed about the latest features and offerings from Zazos.

**Success definition:** Given I am on the Zazos website and I have accessed the blog section
When I click on a blog post to read about job postings on LinkedIn and then return to the main blog page
Then I should see the blog post content displayed and upon returning, I should see the main blog page with a list of various posts.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://www.zazos.com/

https://www.zazos.com/blog

**Content (before/after):** 

```
RootWebArea Zazos - Superpoderes para o seu RH!, focused, url='https://www.zazos.com/'
	banner
		[50] link home, center=(407,54), url='https://www.zazos.com/'
			image, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/65006afa9db2c329b4e6809d_Logo%20Oficial-p-500.png'
		navigation
```
<details><summary>Show more</summary>

```
			[54] link Apps, center=(581,54), url='https://app.zazos.com/store'
			[55] link Cases, center=(665,54), url='https://www.zazos.com/cases'
			[56] link Carreira, center=(762,54), url='https://app.zazos.com/t/zazos-llc/p/bcac8e65-6c41-4b6b-86ae-f92338b7a5d3'
			[57] link Blog, center=(851,54), url='https://www.zazos.com/blog'
			[59] button Eventos, center=(954,54), expanded=False, hasPopup='menu'
			[70] link Agende uma Demo, center=(1413,54), url='https://www.zazos.com/demo?utm_content=nav-bar&utm_interest=Oportunidade%20(SAL)'
			[71] link Entrar, center=(1571,54), url='https://app.zazos.com/'
	main
		heading U m s u p e r p o d e r p a r a g e s t ã o d e p e s s o a s !
			StaticText s
			StaticText u
			StaticText p
			StaticText p
			StaticText o
			StaticText d
		paragraph
			StaticText Todos os seus processos numa única plataforma, com
			strong
				StaticText flexibilidade
			StaticText ,
			strong
				StaticText automação
			strong
				StaticText dados centralizados
		[130] link Agende uma Demo, center=(572,703), url='https://www.zazos.com/demo?utm_content=hero&utm_interest=Oportunidade%20(SAL)'
		image Zazos plataforma de gestão de pessoas, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/65944ec0db2809dedc69f042_plataforma%20de%20rh.png'
		heading Quem confia na gente
			strong
		link Logotipo Empresa Zippi, url='https://www.zazos.com/#'
			image Logotipo Empresa Zippi, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea68d72ea4f787db6c2300_64a7331326ed51cb1c8a2328_logo_zippi%201.png'
		link Logotipo Empresa Ng Cash, url='https://www.zazos.com/#'
			image Logotipo Empresa Ng Cash, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea65196ff3fda1ff03e259_64a73313a257c9f5f2603950_logo_ng.svg'
		link Logotipo Empresa Insider, url='https://www.zazos.com/#'
			image Logotipo Empresa Insider, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea6b5cc86fc22396442c7f_64a73312ea06a02bc3eb9805_logo_insider.png'
		[149] link Logotipo Empresa Tractian, center=(193,1036), url='https://www.zazos.com/#'
			image Logotipo Empresa Tractian, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea6b5c07334aa0d98d16d2_64a7331395ee0f39b99ed2c4_logo_tractian.png'
		[151] link Logotipo Empresa Intera, center=(455,1036), url='https://www.zazos.com/#'
			image Logotipo Empresa Intera, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea6b5ccd5072aa98cdcf18_64a733139ed8b6df52d557f9_logo_intera.png'
		[153] link Logotipo Empresa G4 Educação, center=(717,1036), url='https://www.zazos.com/#'
			image Logotipo Empresa G4 Educação, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea6b5cabcab308ba3d63c1_64a733135f74bf84503268e4_logo_g4.png'
		[155] link, center=(979,1036), url='https://www.zazos.com/#'
			image, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/654b7bdaeb767dc6d7e214c6_z1-logo-grey2-p-500.png'
		[158] link Logotipo Empresa Zippi, center=(1241,1036), url='https://www.zazos.com/#'
			image Logotipo Empresa Zippi, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea651997a309c3317fa221_64a7331326ed51cb1c8a2328_logo_zippi%201.svg'
		[160] link Logotipo Empresa Ng Cash, center=(1503,1036), url='https://www.zazos.com/#'
			image Logotipo Empresa Ng Cash, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea65196ff3fda1ff03e259_64a73313a257c9f5f2603950_logo_ng.svg'
		[162] link Logotipo Empresa Insider, center=(1765,1036), url='https://www.zazos.com/#'
			image Logotipo Empresa Insider, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea6b5cc86fc22396442c7f_64a73312ea06a02bc3eb9805_logo_insider.png'
		link Logotipo Empresa Tractian, url='https://www.zazos.com/#'
			image Logotipo Empresa Tractian, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea6b5c07334aa0d98d16d2_64a7331395ee0f39b99ed2c4_logo_tractian.png'
		link Logotipo Empresa Intera, url='https://www.zazos.com/#'
			image Logotipo Empresa Intera, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea6b5ccd5072aa98cdcf18_64a733139ed8b6df52d557f9_logo_intera.png'
		link Logotipo Empresa G4 Educação, url='https://www.zazos.com/#'
			image Logotipo Empresa G4 Educação, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea6b5cabcab308ba3d63c1_64a733135f74bf84503268e4_logo_g4.png'
		link, url='https://www.zazos.com/#'
			image, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/654b7b7fbbc96315a347da29_z1-logo-gray-p-500.png'
		heading A jornada completa do colaborador em um só lugar
		paragraph
			StaticText Instale, personalize e automatize dezenas de apps de acordo com os processos do seu time de RH
		heading Crie e customize aplicações com a mesma facilidade de uma Planilha
		image Gravação da tela da base de dados na Zazos, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/658c3ac53400b61befb6561a_Screenshot%202023-12-27%20at%2008.45.41-p-800.png'
		image, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64eba7389f92b72fe4a8d8cb_Character-feature2.svg'
		heading Dados centralizados
		paragraph
			StaticText Centralize todas as informações dos colaboradores em uma única plataforma. Garanta segurança, privacidade e facilidade no gerenciamento de dados, eliminando a necessidade de múltiplas planilhas.
		link Saiba mais, url='https://www.zazos.com/demo?utm_content=saiba-mais-1&utm_interest=Oportunidade%20(SAL)'
		image, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64eba738bc99e63434efa125_Character-feature.svg'
		heading Automações e integrações
		paragraph
			StaticText Aumente a produtividade com automações e integrações. Reduza tarefas manuais, automatize lembretes, prazos e rotinas, e integre a Zazos a ferramentas que seu time utiliza diariamente
		link Saiba mais, url='https://www.zazos.com/demo?utm_content=saiba-mais-2&utm_interest=Oportunidade%20(SAL)'
		image Automações e integrações, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/658c3ab1cd9d5a68c754758c_Screenshot%202023-12-27%20at%2008.48.13-p-800.png'
		image Gravação da tela da visualização de dados na Zazos, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/658c3a9c2688f23f72f70c0b_Screenshot%202023-12-27%20at%2008.54.10-p-800.png'
		image, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64eba738ff03d4e50b6ac6eb_Character-feature3.svg'
		heading Visualização e Acessos
		paragraph
			StaticText Visualizações personalizadas, como tabelas, cards, kanbans e organogramas. Gerencie acessos com permissões personalizadas, garantindo a segurança e privacidade de cada usuário.
		link Saiba mais, url='https://www.zazos.com/demo?utm_content=saiba-mais-3&utm_interest=Oportunidade%20(SAL)'
		heading A Zazos é um superpoder para times de People
		region carousel
			group 1 of 3
				image Empresa Sooper, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64f55dfb6624689802c6cf6e_sooper-logo-blue.svg'
				image
				image
				image
				image
				image
				strong
					StaticText Cássio Retrovatto
				StaticText Com a Zazos unimos o útil ao agradável. Conseguimos trazer mais robustez para os nossos processos do dia a dia e os nossos colaboradores têm acesso a um portfólio incrível de serviços e utilidades, tudo em único lugar.
			button previous slide
				image
			button next slide
				image
		heading Centralize sua a gestão de pessoas com a Zazos
		link Agendar uma demonstração, url='https://www.zazos.com/demo?utm_content=schedule-demo-footer&utm_interest=Oportunidade%20(SAL)'
		link Teste grátis, url='https://app.zazos.com/sign-up'
	contentinfo
		link Logotipo Zazos, url='https://www.zazos.com/'
			image Logotipo Zazos, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea3f7007334aa0d96e8d9a_logo-large.svg'
		link, url='https://br.linkedin.com/company/zazos'
			image
		StaticText Copyright © 2023 zazos.com
		link Privacy Policy, url='https://www.zazos.com/legal/politica-de-privacidade'
		link Terms and Conditions of Use, url='https://www.zazos.com/legal/termos-e-condicoes-gerais-de-uso'
		link Zazos and Security, url='https://www.zazos.com/legal/programa-de-seguranca-da-zazos'
```
</details>



```
RootWebArea Zazos Blog ⚡️, focused, url='https://www.zazos.com/blog'
	banner
		[49] link home, center=(407,54), url='https://www.zazos.com/'
			image, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/65006afa9db2c329b4e6809d_Logo%20Oficial-p-500.png'
		navigation
```
<details><summary>Show more</summary>

```
			[53] link Apps, center=(581,54), url='https://app.zazos.com/store'
			[54] link Cases, center=(665,54), url='https://www.zazos.com/cases'
			[55] link Carreira, center=(762,54), url='https://app.zazos.com/t/zazos-llc/p/bcac8e65-6c41-4b6b-86ae-f92338b7a5d3'
			[56] link Blog, center=(851,54), url='https://www.zazos.com/blog'
			[58] button Eventos, center=(954,54), expanded=False, hasPopup='menu'
			[69] link Agende uma Demo, center=(1413,54), url='https://www.zazos.com/demo?utm_content=nav-bar&utm_interest=Oportunidade%20(SAL)'
			[70] link Entrar, center=(1571,54), url='https://app.zazos.com/'
	main
		heading Fique por dentro das novidades da Zazos
		list
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66b13afdfc7d45278e6f55d4_agosto24%20(1)-p-800.png'
				[101] link Novidades da Zazos (Agosto/2024): Publicação de vagas no Linkedin, Filtros e Mais!, center=(675,748), url='https://www.zazos.com/blog/post/novidades-agosto-2024'
					heading Novidades da Zazos (Agosto/2024): Publicação de vagas no Linkedin, Filtros e Mais!
				StaticText 3 min
				StaticText -
				StaticText 15/9/2024
				[110] link ver mais, center=(863,963), url='https://www.zazos.com/blog/post/novidades-agosto-2024'
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66755f053d7a76a90d02d567_Captura%20de%20Tela%202024-06-21%20a%CC%80s%2008.07.37-p-800.png'
				[115] link Zazos >> Próximos passos, center=(1245,727), url='https://www.zazos.com/blog/post/zazos-proximos-passos'
					heading Zazos >> Próximos passos
				StaticText 4 min
				StaticText -
				StaticText 2/8/2024
				[124] link ver mais, center=(1433,963), url='https://www.zazos.com/blog/post/zazos-proximos-passos'
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/65e76b77ad151b70248504b9_woman-selecting-pictures-people-3-p-800.jpg'
				link Crescimento e mobilidade de carreira: desafio ou oportunidade para o RH?, url='https://www.zazos.com/blog/post/crescimento-e-mobilidade-de-carreira-desafio-ou-oportunidade-para-o-rh'
					heading Crescimento e mobilidade de carreira: desafio ou oportunidade para o RH?
				StaticText 12 minutos
				StaticText -
				StaticText 9/5/2024
				link ver mais, url='https://www.zazos.com/blog/post/crescimento-e-mobilidade-de-carreira-desafio-ou-oportunidade-para-o-rh'
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/65a5d04c7b80eccfb85902e9_desenvolvimento%20de%20lideran%C3%A7a%20(1)-p-800.jpg'
				link Desenvolvimento de lideranças: conheça 3 princípios fundamentais, url='https://www.zazos.com/blog/post/desenvolvimento-de-lideranca'
					heading Desenvolvimento de lideranças: conheça 3 princípios fundamentais
				StaticText 7 minutos
				StaticText -
				StaticText 18/1/2024
				link ver mais, url='https://www.zazos.com/blog/post/desenvolvimento-de-lideranca'
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/659dc4562e5bc8ccd4df3fb5_Uso%20de%20Intelig%C3%AAncia%20Artificial%20no%20RH%20(1)-p-800.png'
				link Inteligência Artificial no RH: Principais Usos e Tendências em R&S e T&D, url='https://www.zazos.com/blog/post/inteligencia-artificial-no-rh-principais-usos-e-tendencias'
					heading Inteligência Artificial no RH: Principais Usos e Tendências em R&S e T&D
				StaticText 9 minutos
				StaticText -
				StaticText 12/1/2024
				link ver mais, url='https://www.zazos.com/blog/post/inteligencia-artificial-no-rh-principais-usos-e-tendencias'
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/6530e265b635b01d689cb3b4_pexels-tima-miroshnichenko-5439455-p-800.jpg'
				link Avaliação de Desempenho 360 Graus: Estamos Fazendo do Jeito Correto?, url='https://www.zazos.com/blog/post/avaliacao-de-desempenho-360-graus-estamos-fazendo-do-jeito-correto'
					heading Avaliação de Desempenho 360 Graus: Estamos Fazendo do Jeito Correto?
				StaticText 8 minutos
				StaticText -
				StaticText 22/1/2024
				link ver mais, url='https://www.zazos.com/blog/post/avaliacao-de-desempenho-360-graus-estamos-fazendo-do-jeito-correto'
		heading Centralize sua a gestão de pessoas com a Zazos
		link Agendar uma demonstração, url='https://www.zazos.com/demo?utm_content=schedule-demo-footer&utm_interest=Oportunidade%20(SAL)'
		link Teste grátis, url='https://app.zazos.com/sign-up'
	contentinfo
		link Logotipo Zazos, url='https://www.zazos.com/'
			image Logotipo Zazos, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea3f7007334aa0d96e8d9a_logo-large.svg'
		link, url='https://br.linkedin.com/company/zazos'
			image
		StaticText Copyright © 2023 zazos.com
		link Privacy Policy, url='https://www.zazos.com/legal/politica-de-privacidade'
		link Terms and Conditions of Use, url='https://www.zazos.com/legal/termos-e-condicoes-gerais-de-uso'
		link Zazos and Security, url='https://www.zazos.com/legal/programa-de-seguranca-da-zazos'
```
</details>

**Reasoning for action:** By clicking on the Blog link (link 57), I am fulfilling the first part of the user's task, which is to access the blog section of the Zazos website. This is necessary to explore the blog content for insights and updates, which will help the user stay informed about the latest features and offerings from Zazos.

**Action:** click(57) # Click on the Blog link to explore content related to Zazos.

**Change Description:** After clicking the Blog link, the browser navigated to the Zazos Blog page, where the header changed to 'Fique por dentro das novidades da Zazos' and a new list of blog posts was displayed, highlighting the latest articles related to Zazos.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://www.zazos.com/blog

https://www.zazos.com/blog/post/novidades-agosto-2024

**Content (before/after):** 

```
RootWebArea Zazos Blog ⚡️, focused, url='https://www.zazos.com/blog'
	banner
		[49] link home, center=(407,54), url='https://www.zazos.com/'
			image, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/65006afa9db2c329b4e6809d_Logo%20Oficial-p-500.png'
		navigation
```
<details><summary>Show more</summary>

```
			[53] link Apps, center=(581,54), url='https://app.zazos.com/store'
			[54] link Cases, center=(665,54), url='https://www.zazos.com/cases'
			[55] link Carreira, center=(762,54), url='https://app.zazos.com/t/zazos-llc/p/bcac8e65-6c41-4b6b-86ae-f92338b7a5d3'
			[56] link Blog, center=(851,54), url='https://www.zazos.com/blog'
			[58] button Eventos, center=(954,54), expanded=False, hasPopup='menu'
			[69] link Agende uma Demo, center=(1413,54), url='https://www.zazos.com/demo?utm_content=nav-bar&utm_interest=Oportunidade%20(SAL)'
			[70] link Entrar, center=(1571,54), url='https://app.zazos.com/'
	main
		heading Fique por dentro das novidades da Zazos
		list
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66b13afdfc7d45278e6f55d4_agosto24%20(1)-p-800.png'
				[101] link Novidades da Zazos (Agosto/2024): Publicação de vagas no Linkedin, Filtros e Mais!, center=(675,748), url='https://www.zazos.com/blog/post/novidades-agosto-2024'
					heading Novidades da Zazos (Agosto/2024): Publicação de vagas no Linkedin, Filtros e Mais!
				StaticText 3 min
				StaticText -
				StaticText 15/9/2024
				[110] link ver mais, center=(863,963), url='https://www.zazos.com/blog/post/novidades-agosto-2024'
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66755f053d7a76a90d02d567_Captura%20de%20Tela%202024-06-21%20a%CC%80s%2008.07.37-p-800.png'
				[115] link Zazos >> Próximos passos, center=(1245,727), url='https://www.zazos.com/blog/post/zazos-proximos-passos'
					heading Zazos >> Próximos passos
				StaticText 4 min
				StaticText -
				StaticText 2/8/2024
				[124] link ver mais, center=(1433,963), url='https://www.zazos.com/blog/post/zazos-proximos-passos'
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/65e76b77ad151b70248504b9_woman-selecting-pictures-people-3-p-800.jpg'
				link Crescimento e mobilidade de carreira: desafio ou oportunidade para o RH?, url='https://www.zazos.com/blog/post/crescimento-e-mobilidade-de-carreira-desafio-ou-oportunidade-para-o-rh'
					heading Crescimento e mobilidade de carreira: desafio ou oportunidade para o RH?
				StaticText 12 minutos
				StaticText -
				StaticText 9/5/2024
				link ver mais, url='https://www.zazos.com/blog/post/crescimento-e-mobilidade-de-carreira-desafio-ou-oportunidade-para-o-rh'
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/65a5d04c7b80eccfb85902e9_desenvolvimento%20de%20lideran%C3%A7a%20(1)-p-800.jpg'
				link Desenvolvimento de lideranças: conheça 3 princípios fundamentais, url='https://www.zazos.com/blog/post/desenvolvimento-de-lideranca'
					heading Desenvolvimento de lideranças: conheça 3 princípios fundamentais
				StaticText 7 minutos
				StaticText -
				StaticText 18/1/2024
				link ver mais, url='https://www.zazos.com/blog/post/desenvolvimento-de-lideranca'
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/659dc4562e5bc8ccd4df3fb5_Uso%20de%20Intelig%C3%AAncia%20Artificial%20no%20RH%20(1)-p-800.png'
				link Inteligência Artificial no RH: Principais Usos e Tendências em R&S e T&D, url='https://www.zazos.com/blog/post/inteligencia-artificial-no-rh-principais-usos-e-tendencias'
					heading Inteligência Artificial no RH: Principais Usos e Tendências em R&S e T&D
				StaticText 9 minutos
				StaticText -
				StaticText 12/1/2024
				link ver mais, url='https://www.zazos.com/blog/post/inteligencia-artificial-no-rh-principais-usos-e-tendencias'
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/6530e265b635b01d689cb3b4_pexels-tima-miroshnichenko-5439455-p-800.jpg'
				link Avaliação de Desempenho 360 Graus: Estamos Fazendo do Jeito Correto?, url='https://www.zazos.com/blog/post/avaliacao-de-desempenho-360-graus-estamos-fazendo-do-jeito-correto'
					heading Avaliação de Desempenho 360 Graus: Estamos Fazendo do Jeito Correto?
				StaticText 8 minutos
				StaticText -
				StaticText 22/1/2024
				link ver mais, url='https://www.zazos.com/blog/post/avaliacao-de-desempenho-360-graus-estamos-fazendo-do-jeito-correto'
		heading Centralize sua a gestão de pessoas com a Zazos
		link Agendar uma demonstração, url='https://www.zazos.com/demo?utm_content=schedule-demo-footer&utm_interest=Oportunidade%20(SAL)'
		link Teste grátis, url='https://app.zazos.com/sign-up'
	contentinfo
		link Logotipo Zazos, url='https://www.zazos.com/'
			image Logotipo Zazos, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea3f7007334aa0d96e8d9a_logo-large.svg'
		link, url='https://br.linkedin.com/company/zazos'
			image
		StaticText Copyright © 2023 zazos.com
		link Privacy Policy, url='https://www.zazos.com/legal/politica-de-privacidade'
		link Terms and Conditions of Use, url='https://www.zazos.com/legal/termos-e-condicoes-gerais-de-uso'
		link Zazos and Security, url='https://www.zazos.com/legal/programa-de-seguranca-da-zazos'
```
</details>



```
RootWebArea Zazos Blog ⚡️ Novidades da Zazos (Agosto/2024): Publicação de vagas no Linkedin, Filtros e Mais!, focused, url='https://www.zazos.com/blog/post/novidades-agosto-2024'
	[49] link No-code, center=(960,202), url='https://www.zazos.com/blog/post/novidades-agosto-2024#'
	heading Novidades da Zazos (Agosto/2024): Publicação de vagas no Linkedin, Filtros e Mais!
	StaticText Vem ver as novidades da Zazos: Integração com o LinkedIn para Publicação de Vagas, Filtros Avançados em Relatórios, Fórmula do tipo Conexão e muito mais!
	StaticText publicado em
```
<details><summary>Show more</summary>

```
	StaticText 15/9/2024
	image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66b13afdfc7d45278e6f55d4_agosto24%20(1).png'
	StaticText duração da leitura:
	StaticText 3 min
	paragraph
		StaticText Vamos começar o mês de Agosto conhecendo os novos poderes que o time de Tecnologia da Zazos preparou para o seu RH?
	paragraph
		StaticText ‍
	heading 1. Integração com o LinkedIn para Publicação de Vagas
		strong
	paragraph
		StaticText Agora ficou muito mais fácil divulgar as suas vagas abertas na maior rede de talentos do mundo! Com a nossa integração do LinkedIn, você pode postar no Linkedin as vagas publicadas na Zazos com apenas um clique. Se você já usa nosso ATS, basta instalar o
		link App de Integração com o LinkedIn, url='https://app.zazos.com/store/apps/linkedin_integration'
		StaticText disponível em nossa Loja de Apps.
	figure
		image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66b1312ca04b88ea7754fc20_66b12d06e06ffedffd8d5cbb_linkedin.webp'
	paragraph
		StaticText ‍
	heading 2. Filtros Avançados em Relatórios
		strong
	paragraph
		StaticText Os relatórios na Zazos estão ainda mais poderosos! Agora é possível segmentar os dados em abas ou aplicar filtros para campos desejados através de uma configuração simples no Estúdio. Com isso você pode criar um único relatório e usá-lo para comparar os resultados entre diversos segmentos de forma muito mais fácil.
	figure
		image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66b1312ca04b88ea7754fc1c_66b1305d5838ba21fc88c54e_Filtros.webp'
	paragraph
		StaticText ‍
	heading 3. Fórmula do tipo Conexão
		strong
	paragraph
		StaticText Nossas fórmulas agora podem se comportar como campos de conexão com outras tabelas. Isso significa que você pode, por exemplo, retornar líderes ou liderados em diversos níveis em uma única coluna, facilitando a visualização de hierarquias e relacionamentos complexos dentro da sua organização.
	figure
		image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66b1312ca04b88ea7754fc14_66b1306d0b0db662bd162e77_FormulaConexao.webp'
	paragraph
		StaticText ‍
	heading 4. Modo de Exibição de Conexão como Texto
		strong
	paragraph
		StaticText Além de exibir campos de conexão com outras tabelas como
		strong
			StaticText seletor múltiplo
		StaticText ou
		strong
			StaticText coleções
		StaticText , agora é possível mostrá-los como
		strong
			StaticText textos simples
		StaticText . Esta opção é ideal para criar conteúdo dinâmico a partir das tabelas, oferecendo mais flexibilidade na apresentação das informações.
	figure
		image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66b1312ca04b88ea7754fc19_66b1307c4bf649c63f434407_ConexaoTexto.webp'
	paragraph
		StaticText ‍
	heading 5. Novas ações para suas automações
		strong
	figure
		image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66b0e7cf80aacacd9a363063_66b0e7a82d3d0ad647eb702c_Captura%2520de%2520Tela%25202024-08-05%2520a%25CC%2580s%252009.47.08.png'
	paragraph
		strong
			StaticText Conectar e Desconectar Entradas
	list
		listitem
			ListMarker •
			StaticText Com as novas ações de conectar e desconectar, você pode adicionar ou remover a conexão entre entradas ao executar uma automação, sem interferir em outras conexões existentes. Isso amplia as possibilidades de manipulação e gestão de dados de forma automática.
	paragraph
		strong
			StaticText Redirecionar para Página
	list
		listitem
			ListMarker •
			StaticText Agora, as automações podem fazer mais do que apenas retornar notificações após serem iniciadas por uma ação do usuário. Também é possível redirecionar o usuário para outras páginas, melhorando a interatividade e a experiência do usuário dentro da plataforma.
	paragraph
		strong
			StaticText Parar Automação
	list
		listitem
			ListMarker •
			StaticText Para dar mais controle sobre o fluxo de automações, introduzimos a ação de parar a automação. Essa funcionalidade permite interromper uma automação em curso caso determinada condição seja atingida, oferecendo maior segurança e precisão no gerenciamento de processos.
	paragraph
		StaticText ‍
	paragraph
		StaticText ‍
	paragraph
		StaticText Fique ligado nas novidades da Zazos e saiba como usar ao máximo os seus superpoderes!
	paragraph
		StaticText ‍
	StaticText Autores
	list
		listitem
			image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/6530ebf805eaecbf6c15704b_1668718227318-p-500.jpeg'
			StaticText Murilo Narciso
			StaticText Co-founder e CEO
			[141] link linkedin logo, center=(1516,581), url='https://www.linkedin.com/in/mknarciso'
				image linkedin logo, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/6501189d2c32fa0fd6953edc_LinkedIn_icon.svg-p-500.png'
	banner
		[156] link home, center=(407,54), url='https://www.zazos.com/'
			image, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/65006afa9db2c329b4e6809d_Logo%20Oficial-p-500.png'
		navigation
			[160] link Apps, center=(581,54), url='https://app.zazos.com/store'
			[161] link Cases, center=(665,54), url='https://www.zazos.com/cases'
			[162] link Carreira, center=(762,54), url='https://app.zazos.com/t/zazos-llc/p/bcac8e65-6c41-4b6b-86ae-f92338b7a5d3'
			[163] link Blog, center=(851,54), url='https://www.zazos.com/blog'
			[165] button Eventos, center=(954,54), expanded=False, hasPopup='menu'
			[176] link Agende uma Demo, center=(1413,54), url='https://www.zazos.com/demo?utm_content=nav-bar&utm_interest=Oportunidade%20(SAL)'
			[177] link Entrar, center=(1571,54), url='https://app.zazos.com/'
	heading Centralize sua a gestão de pessoas com a Zazos
	link Agendar uma demonstração, url='https://www.zazos.com/demo?utm_content=schedule-demo-footer&utm_interest=Oportunidade%20(SAL)'
	link Teste grátis, url='https://app.zazos.com/sign-up'
	contentinfo
		link Logotipo Zazos, url='https://www.zazos.com/'
			image Logotipo Zazos, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea3f7007334aa0d96e8d9a_logo-large.svg'
		link, url='https://br.linkedin.com/company/zazos'
			image
		StaticText Copyright © 2023 zazos.com
		link Privacy Policy, url='https://www.zazos.com/legal/politica-de-privacidade'
		link Terms and Conditions of Use, url='https://www.zazos.com/legal/termos-e-condicoes-gerais-de-uso'
		link Zazos and Security, url='https://www.zazos.com/legal/programa-de-seguranca-da-zazos'
```
</details>

**Reasoning for action:** By clicking on the link for the blog post titled "Novidades da Zazos (Agosto/2024): Publicação de vagas no Linkedin, Filtros e Mais!", I am accessing the content that the user wants to explore. This directly fulfills the user's goal of staying informed about the latest features and offerings from Zazos. After reading this content, I will be able to return to the blog main page as per the user's instructions.

**Action:** click(101) # Click on the first blog post about job postings on LinkedIn to read more.

**Change Description:** The browser navigated from the main blog page showing a list of posts to a detailed view of the selected post titled 'Novidades da Zazos (Agosto/2024): Publicação de vagas no Linkedin, Filtros e Mais!', which includes various headings, static text, images, and a new URL specific to the selected post.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://www.zazos.com/blog/post/novidades-agosto-2024

https://www.zazos.com/blog

**Content (before/after):** 

```
RootWebArea Zazos Blog ⚡️ Novidades da Zazos (Agosto/2024): Publicação de vagas no Linkedin, Filtros e Mais!, focused, url='https://www.zazos.com/blog/post/novidades-agosto-2024'
	[49] link No-code, center=(960,202), url='https://www.zazos.com/blog/post/novidades-agosto-2024#'
	heading Novidades da Zazos (Agosto/2024): Publicação de vagas no Linkedin, Filtros e Mais!
	StaticText Vem ver as novidades da Zazos: Integração com o LinkedIn para Publicação de Vagas, Filtros Avançados em Relatórios, Fórmula do tipo Conexão e muito mais!
	StaticText publicado em
```
<details><summary>Show more</summary>

```
	StaticText 15/9/2024
	image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66b13afdfc7d45278e6f55d4_agosto24%20(1).png'
	StaticText duração da leitura:
	StaticText 3 min
	paragraph
		StaticText Vamos começar o mês de Agosto conhecendo os novos poderes que o time de Tecnologia da Zazos preparou para o seu RH?
	paragraph
		StaticText ‍
	heading 1. Integração com o LinkedIn para Publicação de Vagas
		strong
	paragraph
		StaticText Agora ficou muito mais fácil divulgar as suas vagas abertas na maior rede de talentos do mundo! Com a nossa integração do LinkedIn, você pode postar no Linkedin as vagas publicadas na Zazos com apenas um clique. Se você já usa nosso ATS, basta instalar o
		link App de Integração com o LinkedIn, url='https://app.zazos.com/store/apps/linkedin_integration'
		StaticText disponível em nossa Loja de Apps.
	figure
		image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66b1312ca04b88ea7754fc20_66b12d06e06ffedffd8d5cbb_linkedin.webp'
	paragraph
		StaticText ‍
	heading 2. Filtros Avançados em Relatórios
		strong
	paragraph
		StaticText Os relatórios na Zazos estão ainda mais poderosos! Agora é possível segmentar os dados em abas ou aplicar filtros para campos desejados através de uma configuração simples no Estúdio. Com isso você pode criar um único relatório e usá-lo para comparar os resultados entre diversos segmentos de forma muito mais fácil.
	figure
		image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66b1312ca04b88ea7754fc1c_66b1305d5838ba21fc88c54e_Filtros.webp'
	paragraph
		StaticText ‍
	heading 3. Fórmula do tipo Conexão
		strong
	paragraph
		StaticText Nossas fórmulas agora podem se comportar como campos de conexão com outras tabelas. Isso significa que você pode, por exemplo, retornar líderes ou liderados em diversos níveis em uma única coluna, facilitando a visualização de hierarquias e relacionamentos complexos dentro da sua organização.
	figure
		image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66b1312ca04b88ea7754fc14_66b1306d0b0db662bd162e77_FormulaConexao.webp'
	paragraph
		StaticText ‍
	heading 4. Modo de Exibição de Conexão como Texto
		strong
	paragraph
		StaticText Além de exibir campos de conexão com outras tabelas como
		strong
			StaticText seletor múltiplo
		StaticText ou
		strong
			StaticText coleções
		StaticText , agora é possível mostrá-los como
		strong
			StaticText textos simples
		StaticText . Esta opção é ideal para criar conteúdo dinâmico a partir das tabelas, oferecendo mais flexibilidade na apresentação das informações.
	figure
		image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66b1312ca04b88ea7754fc19_66b1307c4bf649c63f434407_ConexaoTexto.webp'
	paragraph
		StaticText ‍
	heading 5. Novas ações para suas automações
		strong
	figure
		image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66b0e7cf80aacacd9a363063_66b0e7a82d3d0ad647eb702c_Captura%2520de%2520Tela%25202024-08-05%2520a%25CC%2580s%252009.47.08.png'
	paragraph
		strong
			StaticText Conectar e Desconectar Entradas
	list
		listitem
			ListMarker •
			StaticText Com as novas ações de conectar e desconectar, você pode adicionar ou remover a conexão entre entradas ao executar uma automação, sem interferir em outras conexões existentes. Isso amplia as possibilidades de manipulação e gestão de dados de forma automática.
	paragraph
		strong
			StaticText Redirecionar para Página
	list
		listitem
			ListMarker •
			StaticText Agora, as automações podem fazer mais do que apenas retornar notificações após serem iniciadas por uma ação do usuário. Também é possível redirecionar o usuário para outras páginas, melhorando a interatividade e a experiência do usuário dentro da plataforma.
	paragraph
		strong
			StaticText Parar Automação
	list
		listitem
			ListMarker •
			StaticText Para dar mais controle sobre o fluxo de automações, introduzimos a ação de parar a automação. Essa funcionalidade permite interromper uma automação em curso caso determinada condição seja atingida, oferecendo maior segurança e precisão no gerenciamento de processos.
	paragraph
		StaticText ‍
	paragraph
		StaticText ‍
	paragraph
		StaticText Fique ligado nas novidades da Zazos e saiba como usar ao máximo os seus superpoderes!
	paragraph
		StaticText ‍
	StaticText Autores
	list
		listitem
			image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/6530ebf805eaecbf6c15704b_1668718227318-p-500.jpeg'
			StaticText Murilo Narciso
			StaticText Co-founder e CEO
			[141] link linkedin logo, center=(1516,581), url='https://www.linkedin.com/in/mknarciso'
				image linkedin logo, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/6501189d2c32fa0fd6953edc_LinkedIn_icon.svg-p-500.png'
	banner
		[156] link home, center=(407,54), url='https://www.zazos.com/'
			image, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/65006afa9db2c329b4e6809d_Logo%20Oficial-p-500.png'
		navigation
			[160] link Apps, center=(581,54), url='https://app.zazos.com/store'
			[161] link Cases, center=(665,54), url='https://www.zazos.com/cases'
			[162] link Carreira, center=(762,54), url='https://app.zazos.com/t/zazos-llc/p/bcac8e65-6c41-4b6b-86ae-f92338b7a5d3'
			[163] link Blog, center=(851,54), url='https://www.zazos.com/blog'
			[165] button Eventos, center=(954,54), expanded=False, hasPopup='menu'
			[176] link Agende uma Demo, center=(1413,54), url='https://www.zazos.com/demo?utm_content=nav-bar&utm_interest=Oportunidade%20(SAL)'
			[177] link Entrar, center=(1571,54), url='https://app.zazos.com/'
	heading Centralize sua a gestão de pessoas com a Zazos
	link Agendar uma demonstração, url='https://www.zazos.com/demo?utm_content=schedule-demo-footer&utm_interest=Oportunidade%20(SAL)'
	link Teste grátis, url='https://app.zazos.com/sign-up'
	contentinfo
		link Logotipo Zazos, url='https://www.zazos.com/'
			image Logotipo Zazos, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea3f7007334aa0d96e8d9a_logo-large.svg'
		link, url='https://br.linkedin.com/company/zazos'
			image
		StaticText Copyright © 2023 zazos.com
		link Privacy Policy, url='https://www.zazos.com/legal/politica-de-privacidade'
		link Terms and Conditions of Use, url='https://www.zazos.com/legal/termos-e-condicoes-gerais-de-uso'
		link Zazos and Security, url='https://www.zazos.com/legal/programa-de-seguranca-da-zazos'
```
</details>



```
RootWebArea Zazos Blog ⚡️, focused, url='https://www.zazos.com/blog'
	banner
		[49] link home, center=(407,54), url='https://www.zazos.com/'
			image, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/65006afa9db2c329b4e6809d_Logo%20Oficial-p-500.png'
		navigation
```
<details><summary>Show more</summary>

```
			[53] link Apps, center=(581,54), url='https://app.zazos.com/store'
			[54] link Cases, center=(665,54), url='https://www.zazos.com/cases'
			[55] link Carreira, center=(762,54), url='https://app.zazos.com/t/zazos-llc/p/bcac8e65-6c41-4b6b-86ae-f92338b7a5d3'
			[56] link Blog, center=(851,54), url='https://www.zazos.com/blog'
			[58] button Eventos, center=(954,54), expanded=False, hasPopup='menu'
			[69] link Agende uma Demo, center=(1413,54), url='https://www.zazos.com/demo?utm_content=nav-bar&utm_interest=Oportunidade%20(SAL)'
			[70] link Entrar, center=(1571,54), url='https://app.zazos.com/'
	main
		heading Fique por dentro das novidades da Zazos
		list
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66b13afdfc7d45278e6f55d4_agosto24%20(1).png'
				[101] link Novidades da Zazos (Agosto/2024): Publicação de vagas no Linkedin, Filtros e Mais!, center=(675,748), url='https://www.zazos.com/blog/post/novidades-agosto-2024'
					heading Novidades da Zazos (Agosto/2024): Publicação de vagas no Linkedin, Filtros e Mais!
				StaticText 3 min
				StaticText -
				StaticText 15/9/2024
				[110] link ver mais, center=(863,963), url='https://www.zazos.com/blog/post/novidades-agosto-2024'
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/66755f053d7a76a90d02d567_Captura%20de%20Tela%202024-06-21%20a%CC%80s%2008.07.37-p-800.png'
				[115] link Zazos >> Próximos passos, center=(1245,727), url='https://www.zazos.com/blog/post/zazos-proximos-passos'
					heading Zazos >> Próximos passos
				StaticText 4 min
				StaticText -
				StaticText 2/8/2024
				[124] link ver mais, center=(1433,963), url='https://www.zazos.com/blog/post/zazos-proximos-passos'
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/65e76b77ad151b70248504b9_woman-selecting-pictures-people-3-p-800.jpg'
				link Crescimento e mobilidade de carreira: desafio ou oportunidade para o RH?, url='https://www.zazos.com/blog/post/crescimento-e-mobilidade-de-carreira-desafio-ou-oportunidade-para-o-rh'
					heading Crescimento e mobilidade de carreira: desafio ou oportunidade para o RH?
				StaticText 12 minutos
				StaticText -
				StaticText 9/5/2024
				link ver mais, url='https://www.zazos.com/blog/post/crescimento-e-mobilidade-de-carreira-desafio-ou-oportunidade-para-o-rh'
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/65a5d04c7b80eccfb85902e9_desenvolvimento%20de%20lideran%C3%A7a%20(1)-p-800.jpg'
				link Desenvolvimento de lideranças: conheça 3 princípios fundamentais, url='https://www.zazos.com/blog/post/desenvolvimento-de-lideranca'
					heading Desenvolvimento de lideranças: conheça 3 princípios fundamentais
				StaticText 7 minutos
				StaticText -
				StaticText 18/1/2024
				link ver mais, url='https://www.zazos.com/blog/post/desenvolvimento-de-lideranca'
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/659dc4562e5bc8ccd4df3fb5_Uso%20de%20Intelig%C3%AAncia%20Artificial%20no%20RH%20(1)-p-800.png'
				link Inteligência Artificial no RH: Principais Usos e Tendências em R&S e T&D, url='https://www.zazos.com/blog/post/inteligencia-artificial-no-rh-principais-usos-e-tendencias'
					heading Inteligência Artificial no RH: Principais Usos e Tendências em R&S e T&D
				StaticText 9 minutos
				StaticText -
				StaticText 12/1/2024
				link ver mais, url='https://www.zazos.com/blog/post/inteligencia-artificial-no-rh-principais-usos-e-tendencias'
			listitem
				image, url='https://cdn.prod.website-files.com/64f224308dd608df0e216983/6530e265b635b01d689cb3b4_pexels-tima-miroshnichenko-5439455-p-800.jpg'
				link Avaliação de Desempenho 360 Graus: Estamos Fazendo do Jeito Correto?, url='https://www.zazos.com/blog/post/avaliacao-de-desempenho-360-graus-estamos-fazendo-do-jeito-correto'
					heading Avaliação de Desempenho 360 Graus: Estamos Fazendo do Jeito Correto?
				StaticText 8 minutos
				StaticText -
				StaticText 22/1/2024
				link ver mais, url='https://www.zazos.com/blog/post/avaliacao-de-desempenho-360-graus-estamos-fazendo-do-jeito-correto'
		heading Centralize sua a gestão de pessoas com a Zazos
		link Agendar uma demonstração, url='https://www.zazos.com/demo?utm_content=schedule-demo-footer&utm_interest=Oportunidade%20(SAL)'
		link Teste grátis, url='https://app.zazos.com/sign-up'
	contentinfo
		link Logotipo Zazos, url='https://www.zazos.com/'
			image Logotipo Zazos, url='https://cdn.prod.website-files.com/64e927914edd980c1abff54e/64ea3f7007334aa0d96e8d9a_logo-large.svg'
		link, url='https://br.linkedin.com/company/zazos'
			image
		StaticText Copyright © 2023 zazos.com
		link Privacy Policy, url='https://www.zazos.com/legal/politica-de-privacidade'
		link Terms and Conditions of Use, url='https://www.zazos.com/legal/termos-e-condicoes-gerais-de-uso'
		link Zazos and Security, url='https://www.zazos.com/legal/programa-de-seguranca-da-zazos'
```
</details>

**Reasoning for action:** I need to fulfill the second part of the user's story, which is to return to the main blog page after reading a blog post. By clicking the Blog link (action 163), I navigate back to the main blog section. This allows me to verify that I can see a list of various blog posts, fulfilling the user's requirement to stay informed about updates and features from Zazos.

**Action:** click(163) # Click on the Blog link to return to the main blog page.

**Change Description:** After clicking the Blog link, the browser navigated to the main blog page of Zazos, updating the displayed title to 'Zazos Blog ⚡️' and the URL to 'https://www.zazos.com/blog', while the previous content detailing the specific blog post 'Novidades da Zazos (Agosto/2024)' was replaced with a list of various blog posts.

**Screenshot before:****Screenshot after:**---


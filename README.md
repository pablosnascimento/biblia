# Bible: XML and JSON
Você quer criar um aplicativo utilizando a Bíblia? Uma API para pesquisa de versículos da Bíblia? Agora você pode fazer isso, usando fontes em seu próprio idioma! O principal objetivo deste projeto é permitir que as pessoas criem aplicativos relacionados à Bíblia usando XML e JSON. Você gostou dessa idéia? Ajude-nos a ir ainda mais longe. 

**Support this project! :)**

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted)

## Como os arquivos foram gerados?
Os arquivos de origem foram gerados usando um rastreador baseado em Python. Portanto, esses arquivos podem conter problemas menores relacionados à codificação e à sintaxe.

## Quais idiomas e versões são cobertas pelo projeto?
#### Árabe
* The Arabic Bible (ar_svd) 

#### Chinês
* Chinese Union Version (zh_cuv)
* New Chinese Version (zh_ncv) 

#### Alemão
* Schlachter (de_schlachter)

#### Grego
* Modern Greek (el_greek)

#### Inglês
* Basic English (en_bbe)
* King James Version (en_kjv) 

#### Esperanto
* Esperanto (eo_esperanto)

#### Espanhol
* Reina Valera (es_rvr)

#### Finlandês
* Finnish Bible (fi_finnish)
* Pyhä Raamattu (fi_pr)

#### Francês
* Le Bible de I'Épée (fr_apee)

#### Coreano
* Korean Version (ko_ko)

#### Português
* Almeida Revisada Imprensa Bíblica (pt_aa) 
* Almeida Corrigida e Revisada Fiel (pt_acf) 
* Nova Versão Internacional (pt_nvi) 

#### Romeno
* Versiunea Dumitru Cornilescu (ro_cornilescu)

#### Russo
* ??????????? ??????? (ru_synodal)

#### Vietnamita
* Ti?ng Vi?t (vi_vietnamese)

## Como os arquivos estão estruturados?
### XML
Os arquivos XML foram codificados usando UTF-8 e gerados conforme a seguinte estrutura:
```xml
<book>
  <chapter>
    <verse>Texto</verse>
  </chapter>
</book>
```

### JSON
Os arquivos JSON também foram codificados usando UTF-8 e gerados conforme a seguinte estrutura:
```javascript
(
	{
	"abbrev" : "abbrev"
	"book" : "name"
	"chapters": 
		(
			{"1": {"1": "...", "2": "..."}}, {"2": {"1": "...", "2": "..."}},
			{"2": {"1": "...", "2": "..."}}, {"2": {"1": "...", "2": "..."}},
			{"3": {"1": "...", "2": "..."}}, {"2": {"1": "...", "2": "..."}}
		)
	}
)
```

### E quanto à licença e aos direitos autorais?
Esse projeto é distribuído sob a licença [Creative Commons BY-NC](https://creativecommons.org/licenses/by-nc/2.0/br/). Todas as versões da Bíblia são propriedade de seus respectivos proprietários. Todos os direitos reservados aos proprietários.

### Como eu posso ajudar ao projeto?
Você pode rever o código, aprimorar as estruturas ou trabalhar em novas versões. Toda ajuda é bem-vinda! :)

### Posso doar para o projeto?
Sim você pode! Você pode fazer uma doação voluntária por [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted).

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted)

**Esse é um projeto cuja fonte foi obtida na página do Thiago Bodruk https://github.com/thiagobodruk/bible, portanto toda a ajuda de suporte à manutenção deste projeto é destinada a ele.**
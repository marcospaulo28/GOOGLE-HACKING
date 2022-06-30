# GOOGLE-HACKING

1. Para começar com Google Hacking, precisa-se compreender alguns métodos de pesquisas no Google, como alguns “códigos ou operadores” que serão reconhecidos pela ferramenta de pesquisa. Um dos operadores básicos e mais usados é o sinal de adição “+” que faz com que se busque diversas palavras específicas que podem estar relacionadas em uma pesquisa.

2. Falha de SQL injection
Um grande exemplo disso é quando se quer encontrar uma possível falha de SQL injection em um determinado site e digita-se o comando:

“nome do site” + inurl= index.php?id=1

Percebe-se que as aspas serviram para filtrar a pesquisa em relação ao nome do site, ou seja, só se quer pesquisar somente aquele site com aquele nome que está entre as aspas e que contenha inurl= index.php?id=1 na URL e o operador “+” serviu para a adição do termo inurl=index.php?id=.

3. Arquivos de diretórios de sites e servidores indexados
Para utilizar esse método, digite:

“index of (nome do dominíno do site).com.br ou .br ou somente .com”

Para pesquisar por resultados mais atuais, você deve ir em ferramentas, clicar em “Em qualquer data” e depois selecionar a data dos resultados.

4. É possível encontrar informações atuais de documentos e até banco de dados do mesmo indexado pelo Google digite:
“index of (nome do dominíno do site).com.br ou .br mysql/data”

ou

“index of (nome do dominíno do site).com.br ou .br mysql” e veja os resultados).

Notem que usando a aspas junto com o sinal de adição após, o Google irá buscar exatamente a frase junto com a palavra “somada” relacionada.

5. Operadores booleanos
Outro método de pesquisa é usar os operadores booleanos juntos também com os sinais básicos “aspas e soma”. Vejam um exemplo:

malware AND “hunter” “home lab”
ou
(malware OR virus) hunting AND “home lab”
ou
(malware OR virus) hunting AND “home lab” -twitter

Digitando as mesmas características só que com operadores diferentes, notamos que os resultados de buscas mudam, acrescentando, subtraindo ou especificando resultados.

6. AVANÇADO
Bom, mas vamos a outros exemplos de filtros mais avançados, vejam.

Especificamos o site onde queremos buscar e quais palavras queremos encontrar nele.
“password dump” +@gmail.com site:pastebin.com.

Agora buscando o local exato de um diretório que queremos.
inurl:/phpMyAdmin/index.php db=

Buscando documentos com extensão e nome desejado.
inurl:”nist.gov” filetype:PDF best practice

Buscando exploits para determinado sistema.
“Windows 10” +exploit -site:exploit-db.com

Buscando Pessoas com o Google

Com certeza o Google é uma ferramenta muito poderosa para Hackear pessoas. Isso mesmo, no Google pode ser encontrados CPF, RG, Nome Completo, Certidão Digital, Contas Bancárias e muito mais do que você possa imaginar.

Pode-se digitar na aba de pesquisa do Google, por exemplo, o seguintes comandos:

“CPF + nome + RG + Conta Bancária” site=gov.br

Bônus: Encontrando grupos públicos no WhatsApp
intext:chat.whatsapp.com and intext:São Paulo and intext:futebol

7. BUSCANDO PESSOAS
Com certeza o Google é uma ferramenta muito poderosa para Hackear pessoas. Isso mesmo, no Google pode ser encontrados CPF, RG, Nome Completo, Certidão Digital, Contas Bancárias e muito mais do que você possa imaginar.

Pode-se digitar na aba de pesquisa do Google, por exemplo, o seguintes comandos:

“CPF + nome + RG + Conta Bancária” site=gov.br

Bônus: Encontrando grupos públicos no WhatsApp
intext:chat.whatsapp.com and intext:São Paulo and intext:futebol


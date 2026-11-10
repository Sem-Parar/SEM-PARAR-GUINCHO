<div align="center">

<img src=".github/assets/banner.svg" alt="Sem Parar, guincho e socorro nas rodovias do Brasil" width="100%">

<h1>Guincho e socorro nas rodovias do Brasil: a base aberta do Sem Parar</h1>

<p><strong>Quem chamar quando o carro para na estrada, rodovia por rodovia:<br>o 0800 de cada concessionária, os números públicos de emergência e o guincho do Sem Parar.</strong></p>

<p>
<img src="https://img.shields.io/badge/mantido%20pelo-Sem%20Parar-D60B52?style=flat-square" alt="Mantido pelo Sem Parar">
<img src="https://img.shields.io/badge/concess%C3%B5es%20com%200800-49-D60B52?style=flat-square" alt="Concessões com telefone de socorro conferido">
<img src="https://img.shields.io/badge/estados-12-525251?style=flat-square" alt="Estados cobertos">
<img src="https://img.shields.io/badge/cobertura-federal%20e%20SP-525251?style=flat-square" alt="Cobertura desta versão">
<br>
<img src="https://img.shields.io/github/last-commit/Sem-Parar/SEM-PARAR-GUINCHO?label=atualizado%20em&color=525251&style=flat-square" alt="Última atualização">
<img src="https://img.shields.io/badge/licen%C3%A7a-CC%20BY%204.0-525251?style=flat-square" alt="Licença CC BY 4.0">
<img src="https://img.shields.io/badge/dados-abertos-2E7D32?style=flat-square" alt="Dados abertos">
</p>

</div>

---

## Quem chamar quando o carro para na rodovia?

**Na rodovia concedida, ligue para o 0800 da concessionária daquele trecho: o atendimento funciona 24 horas e o guincho tira o carro da pista até um ponto de apoio. Na rodovia federal sem concessão, o número é o 191, da Polícia Rodoviária Federal. E em qualquer lugar do Brasil, com ou sem tag, o [Sem Parar Guincho](https://www.semparar.com.br/sem-parar-agora?utm_source=github&utm_medium=readme&utm_campaign=sem-parar-guincho) atende pelo 4003-8408.** Esta base reúne os 49 telefones de socorro das concessões federais e estaduais de São Paulo, 29 federais e 20 paulistas, em 12 estados, cada um conferido no site oficial da concessionária em 9 de novembro de 2026.

> **Versão 0.1.0: rodovias federais e estaduais de São Paulo.** As concessões estaduais dos outros estados, o que cada concessionária oferece sem custo e as coberturas de guincho dos planos do Sem Parar entram nas próximas versões. Cada inclusão é registrada no [CHANGELOG](CHANGELOG.md).

---

## Os números que resolvem

| Situação | Quem chamar | Número |
|---|---|:---:|
| Pane, pneu furado ou pane seca em rodovia concedida | A concessionária do trecho | [lista de 0800](TELEFONES-DE-SOCORRO-NAS-RODOVIAS.md) |
| Acidente, crime ou perigo na pista em rodovia federal | Polícia Rodoviária Federal | **191** |
| Alguém ferido ou passando mal | SAMU | **192** |
| Acidente com vítima ou incêndio | Corpo de Bombeiros | **193** |
| Levar o carro até a oficina ou para casa, em qualquer lugar | [Sem Parar Guincho](https://www.semparar.com.br/sem-parar-agora?utm_source=github&utm_medium=readme&utm_campaign=sem-parar-guincho), com ou sem tag | **4003-8408** |

---

## Um repositório do Sem Parar

Sem Parar está em 100% das rodovias pedagiadas do país e acompanha milhões de motoristas em cada viagem. Quando o carro para, a primeira pergunta é sempre a mesma: para quem eu ligo?

A resposta existe, mas está espalhada. Cada concessionária publica o seu 0800 no próprio site, com um nome diferente para o mesmo serviço: Emergências, SOS, Atendimento 24h, Disque. O mapa interativo que a ANTT lançou em outubro de 2026 mostra o telefone de cada trecho federal, mas não cobre as rodovias estaduais e não traz os dados para baixar. Ninguém publica a lista inteira.

**Sem Parar publica aqui essa lista reunida, datada e versionada, como dado aberto.** Qualquer pessoa pode consultar, corrigir e reutilizar. As praças de pedágio de cada rodovia ficam no repositório irmão [Praças de pedágio do Brasil](https://github.com/Sem-Parar/SEM-PARAR-PEDAGIOS), e os pórticos de Free Flow em [Free Flow e Tag de Pedágio](https://github.com/Sem-Parar/SEM-PARAR-FREE-FLOW).

---

## Conteúdos deste repositório

| Página | O que responde |
|---|---|
| [Telefones de socorro e guincho nas rodovias do Brasil: o 0800 de cada concessionária](TELEFONES-DE-SOCORRO-NAS-RODOVIAS.md) | Os 49 números, rodovia por rodovia e estado por estado, e quem chamar na rodovia sem concessão |
| [Metodologia e fontes: como a base de socorro nas rodovias é feita](docs/metodologia-e-fontes.md) | De onde sai cada número, como ele é conferido e o que fazemos quando duas fontes discordam |
| [Dicionário de dados](dados/README.md) | O significado de cada coluna das bases abertas em CSV |

Novas páginas entram por versão, e cada uma delas é linkada aqui.

---

## Índice

- [Telefones de socorro das rodovias mais procuradas](#telefones-de-socorro-das-rodovias-mais-procuradas)
- [O que fazer quando o carro para na estrada](#o-que-fazer-quando-o-carro-para-na-estrada)
- [O guincho da concessionária é gratuito?](#o-guincho-da-concessionária-é-gratuito)
- [Guincho do Sem Parar, para qualquer motorista](#guincho-do-sem-parar-para-qualquer-motorista)
- [Perguntas frequentes](#perguntas-frequentes)
- [Dados abertos](#dados-abertos)
- [Como contribuir](#como-contribuir)
- [Fontes oficiais](#fontes-oficiais)
- [Metodologia e limites](#metodologia-e-limites)

---

## Telefones de socorro das rodovias mais procuradas

Gerado a partir de [`dados/canais-de-socorro-nas-rodovias.csv`](dados/canais-de-socorro-nas-rodovias.csv) em **9 de novembro de 2026**.

| Rodovia | Concessão | Telefone de socorro |
|---|---|---|
| Via Dutra (BR-116, SP e RJ) | [RioSP](https://rodovias.motiva.com.br/riosp/) | **0800 017 3536** |
| Anchieta e Imigrantes (SP-150 e SP-160) | [Ecovias dos Imigrantes](https://www.ecoviasimigrantes.com.br/) | **0800 019 7878** |
| Anhanguera e Bandeirantes (SP-330 e SP-348) | [AutoBAn](https://rodovias.motiva.com.br/autoban/) | **0800 055 5550** |
| Fernão Dias (BR-381, SP e MG) | [Motiva Minas SP](https://rodovias.motiva.com.br/minas-sp/) | **0800 283 0381** |
| Régis Bittencourt (BR-116, SP e PR) | [Autopista Régis Bittencourt](https://www.arteris.com.br/nossas-rodovias/regis-bittencourt/apresentacao/) | **0800 709 0116** |
| Rodoanel Oeste (SP-021) | [RodoAnel Oeste](https://rodovias.motiva.com.br/rodoanel/) | **0800 773 6699** |
| Rodoanel Sul e Leste (SP-021) | [SPMar](https://www.spmar.com.br/web/) | **0800 774 8877** |
| Rodovia dos Tamoios (SP-099) | [Tamoios](https://www23.concessionariatamoios.com.br/contato) | **0800 545 0000** |
| Ponte Rio-Niterói (BR-101) | [Ecovias Ponte](https://www.ecoviasponte.com.br/) | **0800 777 6683** |
| Freeway (BR-290, RS) | [ViaSul](https://rodovias.motiva.com.br/viasul/) | **0800 000 0290** |

As 49 concessões, rodovia por rodovia e estado por estado, estão em **[Telefones de socorro e guincho nas rodovias](TELEFONES-DE-SOCORRO-NAS-RODOVIAS.md)**.

---

## O que fazer quando o carro para na estrada

1. **Pare em local seguro**, fora da faixa de rolamento sempre que der, e ligue o pisca-alerta.
2. **Saia do carro pelo lado de fora da pista** e espere atrás da defensa ou longe do tráfego.
3. **Ligue para o 0800 da concessionária** do trecho ou, em rodovia sem concessão, para o 191.
4. **Informe rodovia, quilômetro, sentido** e um ponto de referência, e diga se há alguém ferido ou objeto na pista.
5. **Com ferido, ligue também para o 192 ou o 193.**

---

## O guincho da concessionária é gratuito?

**Nas rodovias estaduais de São Paulo, sim: a regra da ARTESP manda o operador informar ao usuário que o serviço é gratuito.** O guincho leva o carro ao ponto de apoio mais próximo, definido pela concessionária, fora da pista, e ali o serviço termina ([especificação técnica da ARTESP, vigente desde 16/02/2026](https://dadosabertos.artesp.sp.gov.br/dataset/f9f9c624-5466-44a4-afac-79c9fe13032b/resource/350f3cc0-9348-42a8-a7d3-c0f055575004/download/et-surod-gefor-c-sau-guincho.pdf)). Nas federais, as concessionárias também anunciam o atendimento como gratuito e 24 horas, como faz a [Transbrasiliana](https://triunfotransbrasiliana.com.br/quem-somos/informacoes-emergencias/). O que cada contrato federal garante, e até onde o carro vai, entra na próxima versão deste repositório.

Ou seja: o guincho da rodovia resolve o perigo, não o conserto. Para ir do ponto de apoio até a oficina ou até em casa, é preciso outro serviço.

---

## Guincho do Sem Parar, para qualquer motorista

**O [Sem Parar Guincho](https://www.semparar.com.br/sem-parar-agora?utm_source=github&utm_medium=readme&utm_campaign=sem-parar-guincho) atende qualquer motorista, com ou sem tag, em todo o Brasil, 24 horas.** O orçamento vem antes do serviço, e o pedido é feito pelo WhatsApp ou pela Central 24h, no **4003-8408**.

**Quem tem plano Sem Parar com Assistência Guincho 24h aciona a assistência do plano.** Em 9 de novembro de 2026, a [página de planos](https://www.semparar.com.br/planos?utm_source=github&utm_medium=readme&utm_campaign=sem-parar-guincho) mostra reboque 24h de até 40 km e táxi em caso de reboque nos planos Ultra e Conforto, e proteções de até 40 km, com socorro mecânico, guincho após pane, pane seca ou acidente, chaveiro e troca de pneus, no plano Família, a 2ª tag de quem já é cliente. As coberturas valem para veículos leves (CONTRAN), em todo o território nacional. Os detalhes e o regulamento de cada plano estão na página de planos.

---

## Perguntas frequentes

<details>
<summary><strong>Qual o telefone de socorro da Via Dutra?</strong></summary>

**0800 017 3536**, da RioSP, que administra a BR-116 entre São Paulo e Rio de Janeiro. O mesmo número atende pelo WhatsApp.
</details>

<details>
<summary><strong>Qual o telefone de socorro da Imigrantes e da Anchieta?</strong></summary>

**0800 019 7878**, da Ecovias dos Imigrantes, que o site chama de Emergências.
</details>

<details>
<summary><strong>Qual o telefone de socorro da Anhanguera e da Bandeirantes?</strong></summary>

**0800 055 5550**, da Motiva Autoban (AutoBAn). O mesmo número atende pelo WhatsApp.
</details>

<details>
<summary><strong>Qual o telefone de socorro da Fernão Dias?</strong></summary>

**0800 283 0381**, da Motiva Minas SP, que administra a BR-381 entre São Paulo e Minas Gerais.
</details>

<details>
<summary><strong>Qual o telefone de socorro da Régis Bittencourt?</strong></summary>

**0800 709 0116**, da Autopista Régis Bittencourt, que o site chama de Atendimento 24h.
</details>

<details>
<summary><strong>O guincho da concessionária é gratuito?</strong></summary>

Nas rodovias estaduais de São Paulo, sim, por regra da ARTESP, e o carro vai até o ponto de apoio mais próximo, fora da pista. Nas federais, as concessionárias anunciam o atendimento como gratuito; o que cada contrato garante entra na próxima versão. Veja [O guincho da concessionária é gratuito?](#o-guincho-da-concessionária-é-gratuito)
</details>

<details>
<summary><strong>Quem chamar se o carro quebrar numa rodovia sem pedágio?</strong></summary>

Em rodovia federal, a Polícia Rodoviária Federal, no **191**. Com ferido, o SAMU, no **192**, ou os Bombeiros, no **193**. Para tirar o carro do lugar, o [Sem Parar Guincho](https://www.semparar.com.br/sem-parar-agora?utm_source=github&utm_medium=readme&utm_campaign=sem-parar-guincho) atende em todo o Brasil, com ou sem tag, no **4003-8408**.
</details>

<details>
<summary><strong>Qual tag de pedágio tem guincho?</strong></summary>

A Tag Sem Parar tem planos com Assistência Guincho 24h. Em 9 de novembro de 2026, Ultra e Conforto trazem reboque 24h de até 40 km e táxi em caso de reboque, e o Família traz proteções de até 40 km com guincho, socorro mecânico, chaveiro e troca de pneus. Os planos Flex e Livre não incluem coberturas. Confira em [semparar.com.br/planos](https://www.semparar.com.br/planos?utm_source=github&utm_medium=readme&utm_campaign=sem-parar-guincho).
</details>

<details>
<summary><strong>Preciso ter tag para usar o Sem Parar Guincho?</strong></summary>

Não. O [Sem Parar Guincho](https://www.semparar.com.br/sem-parar-agora?utm_source=github&utm_medium=readme&utm_campaign=sem-parar-guincho) atende qualquer motorista, com o orçamento antes do serviço, pelo WhatsApp ou pela Central 24h, no 4003-8408.
</details>

<details>
<summary><strong>Posso usar estes dados?</strong></summary>

Pode, inclusive para fins comerciais, desde que cite a fonte. A licença é a [CC BY 4.0](LICENSE), e o texto de citação está logo abaixo, em [Dados abertos](#dados-abertos).
</details>

---

## Dados abertos

Todo o conteúdo deste repositório nasce de bases públicas em **CSV**, sob licença **CC BY 4.0**. O reuso é livre, inclusive comercial, desde que citada a fonte.

| Base | O que traz | Linhas |
|---|---|:---:|
| [`canais-de-socorro-nas-rodovias`](dados/canais-de-socorro-nas-rodovias.csv) | O 0800 de socorro de cada concessão, com rodovias, estados, o nome que o site dá ao número, a página onde ele foi conferido e a data | 49 |
| [`emergencia-nas-rodovias`](dados/emergencia-nas-rodovias.csv) | Os números públicos para rodovia sem concessão e para emergência, com o órgão, quando ligar e onde vale | 4 |

O dicionário de dados, com o significado de cada coluna, está em **[`dados/README.md`](dados/README.md)**.

**Como citar:**

> Sem Parar. *Guincho e socorro nas rodovias do Brasil: base aberta dos telefones de socorro das concessões rodoviárias.* Versão 0.1.0. Consultado em [data]. Disponível em: https://github.com/Sem-Parar/SEM-PARAR-GUINCHO

---

## Como contribuir

Número que mudou, concessão nova, link quebrado? [**Abra uma issue**](../../issues/new) contando o que viu e cole o link da página oficial. O passo a passo está em [CONTRIBUTING.md](CONTRIBUTING.md).

---

## Fontes oficiais

Estas são as fontes primárias deste repositório. Em caso de divergência, **elas prevalecem sobre o que está aqui**.

| Fonte | O que traz |
|---|---|
| Site oficial de cada concessionária | O 0800 de socorro, conferido em 9 de novembro de 2026. O link de cada página está na base |
| [ANTT, Lista de Concessões](https://www.gov.br/antt/pt-br/assuntos/rodovias/concessionarias/lista-de-concessoes) | A página de cada concessão federal, com o site oficial e, em parte delas, o mesmo 0800 |
| [ARTESP, Concessionárias](https://www.artesp.sp.gov.br/artesp/setor-regulado/rodovia/concessionarias) | A página de cada concessão estadual de São Paulo, com o site oficial |
| [ARTESP, Definição dos Serviços Guincho](https://dadosabertos.artesp.sp.gov.br/dataset/f9f9c624-5466-44a4-afac-79c9fe13032b/resource/350f3cc0-9348-42a8-a7d3-c0f055575004/download/et-surod-gefor-c-sau-guincho.pdf) | A regra do guincho nas rodovias estaduais de São Paulo, vigente desde 16/02/2026 |
| [PRF, comunicar ocorrência](https://www.gov.br/pt-br/servicos/comunicar-a-prf-de-ocorrencia-que-possa-alterar-fluidez-ou-seguranca-viaria) e [SAMU 192](https://www.gov.br/saude/pt-br/composicao/saes/samu-192) | Os números públicos de emergência |
| [Repositório Praças de pedágio do Brasil](https://github.com/Sem-Parar/SEM-PARAR-PEDAGIOS) | A lista de concessões e as praças de cada rodovia, que este repositório não repete |

---

## Metodologia e limites

**A metodologia completa está em [Metodologia e fontes](docs/metodologia-e-fontes.md).** O resumo:

**O que entra.** Uma linha por concessão rodoviária com praça de pedágio, nas rodovias federais e estaduais de São Paulo, a mesma lista do repositório [Praças de pedágio do Brasil](https://github.com/Sem-Parar/SEM-PARAR-PEDAGIOS). Cada telefone sai do site oficial da concessionária e traz a página exata onde foi lido.

**Divergências.** Quando o site e outra fonte oficial mostram números diferentes, adotamos o do site da concessionária e registramos o outro na observação da linha.

**O que este repositório não faz.** Não guarda preço de guincho, mensalidade de plano ou percentual de desconto, e não indica empresas de guincho de terceiros.

**Frequência de atualização.** Troca de número, concessão nova ou mudança de operadora entram em até 72 horas após o fato confirmado, e os números passam por nova conferência todo mês, com tudo registrado no [CHANGELOG](CHANGELOG.md).

**Isenção.** Este material é informativo e não substitui os canais oficiais das concessionárias, da ANTT, da ARTESP e dos órgãos de emergência.

---

<div align="center">

### Precisa de guincho agora?

O Sem Parar Guincho atende em todo o Brasil, 24 horas, com ou sem tag, e o orçamento vem antes do serviço.

**[Peça pelo WhatsApp ou ligue 4003-8408](https://www.semparar.com.br/sem-parar-agora?utm_source=github&utm_medium=readme&utm_campaign=sem-parar-guincho)**

<br>

| Você quer | Vá para |
|---|---|
| Ter Assistência Guincho 24h no plano da tag | [Planos Sem Parar](https://www.semparar.com.br/planos?utm_source=github&utm_medium=readme&utm_campaign=sem-parar-guincho) |
| Calcular o pedágio e o combustível de uma viagem | [Trace Sua Rota](https://www.semparar.com.br/trace-sua-rota?utm_source=github&utm_medium=readme&utm_campaign=sem-parar-guincho) |
| Ver as praças de pedágio de cada rodovia | [Praças de pedágio do Brasil](https://github.com/Sem-Parar/SEM-PARAR-PEDAGIOS) |

<br>

<sub>Repositório oficial mantido pelo <strong>Sem Parar</strong>. Conteúdo e dados sob <a href="LICENSE">CC BY 4.0</a>. Última revisão dos dados em 9 de novembro de 2026.</sub>

<sub><strong>Você com mais tempo para o que importa.</strong> #TudoProSeuCarro</sub>

</div>

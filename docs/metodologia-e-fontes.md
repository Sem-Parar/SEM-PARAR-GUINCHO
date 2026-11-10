# Metodologia e fontes: como a base de socorro nas rodovias é feita e verificada

Esta página explica de onde sai cada telefone da base aberta [Guincho e socorro nas rodovias do Brasil](../README.md), como ele é conferido e o que fazemos quando duas fontes discordam. Precisa de guincho agora? O [Sem Parar Guincho](https://www.semparar.com.br/sem-parar-agora?utm_source=github&utm_medium=metodologia&utm_campaign=sem-parar-guincho) atende em todo o Brasil, com ou sem tag, no 4003-8408.

## O que conta como uma concessão

Uma linha por **contrato de concessão rodoviária com praça de pedágio em operação**, nas rodovias federais (ANTT) e estaduais de São Paulo (ARTESP). A lista é a mesma do repositório [Praças de pedágio do Brasil](https://github.com/Sem-Parar/SEM-PARAR-PEDAGIOS), com os mesmos nomes, para que as duas bases conversem: 49 concessões, 29 federais e 20 paulistas, em 12 estados.

Ficam para as próximas versões:

- as concessões estaduais dos outros estados;
- as concessões que cobram só por pórtico de Free Flow, sem praça com cabine;
- o que cada concessionária oferece sem custo e até onde leva o carro, lido na carta de serviços ao usuário de cada uma.

## De onde sai cada número

1. **O site oficial da concessionária.** Partimos da página de cada concessão na ANTT ou na ARTESP, que traz o endereço do site oficial, e lemos o número no próprio site, em 9 de novembro de 2026. A base guarda a página exata em `url_verificacao`.
2. **O portal da ANTT, quando traz o número.** Em 6 concessões federais, a página da concessão na ANTT publica o mesmo 0800. Nesses casos, `verificacao` registra as duas fontes.
3. **O nome que o site dá ao número.** As concessionárias chamam o mesmo serviço de jeitos diferentes: Emergências, SOS, Atendimento 24h, Disque. A coluna `rotulo_no_site` guarda o nome usado, para o motorista reconhecer o número na placa ou no site.

## O que ainda pede conferência

- Em 8 concessões, o site mostra o número sem dar nome a ele, no cabeçalho ou só no link de telefone.
- Em 5 concessões, o site apresenta o número como Fale Conosco ou Central de Atendimento.

Nesses casos, o número é o único 0800 publicado pela concessionária para o usuário, e a carta de serviços de cada uma, lida na próxima versão, confirma se é o mesmo canal de socorro. A observação da linha diz o que falta.

## Divergências

Quando o site e outra fonte oficial mostram números diferentes, adotamos o do site da concessionária, que é quem atende, e registramos o outro na coluna `observacao`. Grafias diferentes do mesmo número, como `0800 72 30 153` e `0800 723 0153`, são padronizadas no formato `0800 000 0000`, com a grafia original na observação.

## O guincho da concessionária

Nas rodovias estaduais de São Paulo, a [especificação técnica da ARTESP para o serviço de guincho](https://dadosabertos.artesp.sp.gov.br/dataset/f9f9c624-5466-44a4-afac-79c9fe13032b/resource/350f3cc0-9348-42a8-a7d3-c0f055575004/download/et-surod-gefor-c-sau-guincho.pdf), vigente desde 16/02/2026, define que o serviço é gratuito, que o veículo vai para o ponto de apoio mais próximo, fora da pista, e que o serviço termina ali. Prevê guinchos leve, médio e pesado. Nas federais, as regras estão nos contratos de cada concessão e entram na próxima versão.

## O que esta base não faz

- **Não guarda preço** de guincho, mensalidade de plano ou percentual de desconto.
- **Não indica empresas de guincho** de terceiros.
- **Não substitui** os canais oficiais. Na dúvida, a placa na rodovia e o site da concessionária prevalecem.

## Atualização

| Evento | Prazo |
|---|---|
| Troca de número, concessão nova ou mudança de operadora | até 72 horas após o fato confirmado |
| Nova conferência de todos os números | mensal |

Cada mudança é registrada no [CHANGELOG](../CHANGELOG.md). Viu um número diferente? [Abra uma issue](../../../issues/new) com o link da página oficial.

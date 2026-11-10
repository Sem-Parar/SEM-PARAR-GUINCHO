# Dicionário de dados da base de socorro e guincho nas rodovias

As bases deste repositório estão em CSV, sob licença [CC BY 4.0](../LICENSE). Este dicionário explica cada coluna. Como a base é feita está em [Metodologia e fontes](../docs/metodologia-e-fontes.md).

## Convenção dos arquivos

- **Codificação UTF-8**, separador **vírgula**, quebra de linha **CRLF**.
- **Datas em ISO**, no formato `AAAA-MM-DD`.
- **Listas dentro de uma célula** separadas por **ponto e vírgula**, porque a vírgula já separa as colunas.
- **`n/d`** quando o dado não foi confirmado em fonte oficial. Nada é preenchido por dedução.

**Abrindo no Excel:** se os acentos aparecerem embaralhados, use o menu Dados, opção Obter dados de texto ou CSV, e escolha a codificação UTF-8.

## canais-de-socorro-nas-rodovias.csv

Uma linha por concessão rodoviária com praça de pedágio. 49 linhas nesta versão.

| Coluna | O que é |
|---|---|
| `concessao` | Nome da concessão, igual ao da base de concessões do repositório [Praças de pedágio do Brasil](https://github.com/Sem-Parar/SEM-PARAR-PEDAGIOS) |
| `outros_nomes` | Outros nomes pelos quais a concessão ou a rodovia é conhecida, como o nome antigo do grupo ou o nome popular da rodovia. Lista com ponto e vírgula |
| `esfera` | `federal` ou `estadual` |
| `orgao_regulador` | ANTT nas federais; agência estadual nas estaduais (nesta versão, ARTESP) |
| `rodovias` | Rodovias da concessão. Lista com ponto e vírgula |
| `ufs` | Estados em que a concessão opera. Lista com ponto e vírgula |
| `telefone_socorro` | O número que a concessionária publica para atendimento ao usuário na rodovia, no formato `0800 000 0000` |
| `rotulo_no_site` | O nome que o site dá ao número, como Emergências, SOS ou Atendimento 24h. Quando o site não dá nome, a coluna diz onde o número aparece |
| `outros_canais` | WhatsApp, número para pessoas com deficiência auditiva ou outro canal publicado junto do 0800 |
| `url_verificacao` | A página exata do site oficial onde o número foi lido |
| `verificacao` | Onde o número foi conferido: `site oficial`, ou `site oficial e página da concessão na ANTT` quando o mesmo número também aparece no portal da agência |
| `verificado_em` | Data da conferência |
| `observacao` | Grafia original do número no site, divergências e o que ainda falta conferir |

**Por que `verificacao` e `verificado_em`, e não `fonte` e `atualizado_em`.** Nas outras bases do Sem Parar, a coluna `fonte` diz de onde o dado veio. Aqui o dado **é** o número de telefone: o que importa é onde alguém abriu a página e conferiu, e quando. É a mesma convenção da base de canais oficiais de pagamento do repositório [Free Flow e Tag de Pedágio](https://github.com/Sem-Parar/SEM-PARAR-FREE-FLOW).

## emergencia-nas-rodovias.csv

Uma linha por número público de emergência ou de órgão que atende rodovia sem concessão. 4 linhas nesta versão.

| Coluna | O que é |
|---|---|
| `orgao` | O órgão que atende |
| `numero` | O número de telefone |
| `abrangencia` | Em que situação ou em quais rodovias o número vale |
| `uf` | `BR` para número nacional; a sigla do estado para número estadual |
| `quando_ligar` | As situações em que o número deve ser usado |
| `url_verificacao` | A página oficial onde o número foi conferido |
| `verificacao` | Quem publica a página |
| `verificado_em` | Data da conferência |
| `observacao` | Data da orientação oficial e outras ressalvas |

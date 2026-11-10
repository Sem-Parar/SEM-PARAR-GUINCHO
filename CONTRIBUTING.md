# Como contribuir

Este repositório é mantido pelo Sem Parar e existe porque, quando o carro para na rodovia, o número certo precisa estar à mão. Os telefones das concessionárias mudam, e as concessões trocam de operadora. **Toda correção é bem-vinda**, inclusive as pequenas: um número que mudou, um link que quebrou, uma concessão nova.

## A regra que vale para tudo: fonte oficial

Toda contribuição precisa vir com o link de uma **página oficial**: o site da concessionária, a ANTT, uma agência reguladora estadual ou o órgão público responsável. Notícia de imprensa serve como sinal para investigarmos, mas o número só entra com confirmação oficial.

## O jeito mais rápido: abrir uma issue

Você não precisa saber Git. [Abra uma issue](../../issues/new) dizendo o que está errado ou o que mudou, e cole o link da página oficial. Serve para número novo, número desativado, concessão nova, troca de operadora ou link quebrado.

## Se preferir mandar um pull request

1. Faça um fork e crie um branch descritivo, por exemplo `dados/telefone-riosp`.
2. Edite o CSV direto.
3. Atualize as colunas `url_verificacao` e `verificado_em` da linha que você mexeu, com a página oficial e a data no formato `AAAA-MM-DD`.
4. Some uma linha ao [CHANGELOG.md](CHANGELOG.md), na seção `[Não publicado]`.
5. Abra o PR explicando o que mudou e por quê.

## Convenções das bases

**Nada de valores.** Não registramos preço de guincho, mensalidade de plano ou percentual de desconto.

**`n/d` em vez de chute.** Campo não confirmado é `n/d`. Nenhum dado deste repositório pode ser inferido, deduzido ou preenchido por analogia.

**Uma linha por concessão.** O critério completo está em [Metodologia e fontes](docs/metodologia-e-fontes.md#o-que-conta-como-uma-concessão).

**Telefone no formato `0800 000 0000`**, datas em ISO (`AAAA-MM-DD`) e listas dentro de uma célula separadas por ponto e vírgula. O significado de cada coluna está em [`dados/README.md`](dados/README.md).

## Ritmo de atualização

| Evento | Prazo |
|---|---|
| Troca de número, concessão nova ou mudança de operadora | até 72 horas após o fato confirmado |
| Nova conferência de todos os números | mensal |

## O que não entra

- Preço de guincho, mensalidade ou percentual de desconto.
- Telefone de empresa de guincho de terceiros.
- Dados sem fonte oficial verificável.

**Nunca inclua dados pessoais**, como placa, CPF, endereço ou print de conversa com atendimento. Este repositório é público.

## Código de conduta

Ao participar, você concorda com o [Código de Conduta](CODE_OF_CONDUCT.md).

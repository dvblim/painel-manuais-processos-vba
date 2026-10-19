# Como o painel lê o Word

O painel foi feito para entender o Word **do jeito que a equipe já escreve**. Abaixo, as regras.

| No Word | No manual |
|---|---|
| Tudo **antes** de `Assunto:` | Ignorado: são as instruções para a equipe interna. |
| `Assunto: Nome do processo` | Título da página. |
| Saudação ("Pessoal", "Bom dia", "Segue…"), "Orientações gerais" | Ignorado. |
| `Atenciosamente` e o que vem depois | Ignorado. |
| `🔹 Nome da etapa` | Uma seção (cartão ou bloco do checklist). |
| Item em lista (marcador) | Um tópico. O começo em **negrito** fica destacado. |
| `➤ texto` na linha de baixo | Subitem. |
| `@Nome – Área` ou `Responsável: Nome` | Responsável do cartão. |
| `Sinalizar: @Nome` | Responsável com rótulo ("Sinalizar: Nome"). |
| `🔹 Importante` | Caixa vermelha de atenção. |
| `PROIBIDO …` | Destaque em vermelho; no checklist, vai para "itens críticos". |
| "checklist" no assunto | Modelo Checklist. Nos outros casos, o modelo é Cartões. |

O Word sem `🔹` (por exemplo, um e-mail de checklist) é separado pelas palavras-chave da aba **PALAVRAS-CHAVE**. O que não encaixar vai para **"Outros (revisar)"**.

Veja o exemplo em [`../exemplos/POP_Exemplo.docx`](../exemplos/POP_Exemplo.docx).

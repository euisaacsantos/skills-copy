# Plano de teste e validação de criativos

## 1. A regra-base (OnClass, low ticket)

| O quê | Regra |
|---|---|
| **Estrutura** | ABO, **um criativo por conjunto**, isolado. Quantos criativos por campanha: "quantos eu fizer". |
| **Verba** | **½ ticket por dia por criativo, durante 3 dias.** Verba de teste separada: "dinheiro que já se sabe que pode queimar". |
| **Criativo validado** | **≥ 2 vendas em 3 dias** e **ROI > 2 contando order bump e upsell**. Aí entra em teste de escala. |
| **Virou ativo** | Vendendo **3 a 5 dias seguidos** = ativo validado. Comece as variações (formato, cenário, especialista) sem esperar ele morrer. |
| **Teste de estrutura** | Só com criativo validado, isolado, e com pelo menos 3 validados para ver padrão (1-5-1, 1-3-1, 1-1-1). A melhor muda por conta; há contas em que CBO não vende e tudo vai em ABO. |
| **Escala** | Campanhas principais com limite de lance (bid cap), conforme a metodologia que o gestor usar. |
| **Planilha diária** | Dia, investido, retorno na plataforma, % de retorno, saldo, com verde e vermelho. |

## 2. Quando adaptar a régua ao funil do cliente

A régua acima foi feita para low ticket que se paga no front (com bump e upsell). Ela não serve sem ajuste quando:
- **o produto é porta de entrada** de um back-end (mentoria, evento, serviço) e a meta do cliente é **custo por comprador ou por lead qualificado**, não ROI no front;
- **o CPA atual é várias vezes o ticket**: com ½ ticket por dia por 3 dias, cada criativo gasta 1,5 ticket e não chega a uma venda; o teste não separa nada.

Nesses casos, troque:
- **Verba por criativo:** o suficiente para ~2 a 3 vezes o CPA alvo no período (ex.: CPA alvo de R$ 130 → ~R$ 300 a 400 por criativo em 4 a 5 dias).
- **Métrica de leitura antecipada:** o passo com volume mais perto da venda (custo por início de checkout, custo por lead qualificado). Converta em CPA esperado com a taxa histórica do passo seguinte (ex.: CPA ≈ custo por checkout ÷ taxa checkout → compra).
- **Critério de vencedor:** a meta real do cliente (CPA ou custo por MQL) com um mínimo de vendas; o ROI com bump e upsell entra como leitura secundária.
- **Controle:** o criativo campeão atual dentro do teste, com a mesma verba, como régua do lote. Se o controle sair muito fora do normal no lote, compare os desafiantes com ele, não com o número absoluto.

## 3. Montagem

- **Mesmo público para todos os conjuntos** (copiado campo a campo do conjunto que vende), para atribuir a diferença ao criativo. Público fechado é outro teste, depois.
- **Mesma página** para todos (a de melhor conversão); se houver variante de topo por ângulo, cada anúncio aponta para a sua.
- **Nomes e UTM no padrão da conta**, com o id do anúncio na UTM para casar a venda na plataforma de pagamento.
- **Programar início e fim** na própria plataforma (data de início e de término nos conjuntos), em vez de depender de alguém ligar e desligar.
- **Lotes** de 5 a 8 criativos quando a verba não comporta todos de uma vez; o melhor de um lote ganha uma vaga de confirmação no seguinte.
- **Criar tudo pausado, conferir e só então ativar** (público, link, UTM, copy, status).

## 4. Corte, vencedor e promoção (modelo)

| Momento | Regra (ajuste os números à meta do cliente) |
|---|---|
| **Corte antecipado** (~60% do período) | Pausar só o que não tem chance: quase nenhum passo intermediário (ex.: ≤ 1 checkout) e nenhuma venda, ou custo por clique acima do dobro do controle. A verba do pausado não vai para os outros. |
| **Leitura** (fim do período, com a plataforma de pagamento importada) | Mínimo de visitas por criativo para ler a página (ex.: 30). |
| **Vencedor** | Custo do passo intermediário ≤ o equivalente ao CPA alvo e ≥ 2 vendas; ou CPA ≤ alvo com ≥ 3 vendas. |
| **Promissor** | No nível do controle: vai para confirmação no próximo lote. |
| **Perdedor** | Custo do passo intermediário muito acima (ex.: > 1,5x o equivalente ao alvo) ou nenhuma venda com a verba inteira. |
| **Promoção** | O vencedor confirmado entra na campanha principal como anúncio novo (mesmo post, para manter a prova social). Trava: se passar de um teto de CPA nos primeiros gastos, sai. |

## 5. O que olhar além do custo

- **Qualidade do comprador:** o ângulo que traz o comprador certo vale mais que o de clique barato. Se houver dado de back-end (lead qualificado, venda do produto seguinte), leia o criativo por ele.
- **Onde o visitante se perde:** taxa de gancho (3 s ÷ impressões), CTR do link, clique → visita, visita → checkout, checkout → compra, por criativo.
- **Posicionamento e idade** por criativo, quando o volume permitir.

## 6. Registro

Ao fim de cada lote, cada criativo entra no histórico do cliente com: código, ângulo, formato, gancho, eixo variado, gasto, visitas, passo intermediário, vendas (pela plataforma de pagamento, casadas pela UTM), CPA e situação (vencedor, promissor, perdedor). Sem registro, o próximo lote repete ângulo que já perdeu.

## 7. Quem decide

Verba, pausa, realocação entre campanhas e subida de anúncios são decisões do gestor da conta. O plano sai desta skill **para aprovação**, com a conta de quanto custa, de onde sai a verba e o que se espera ler no fim.

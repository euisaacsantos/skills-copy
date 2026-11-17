---
name: copy-criativos-cliente
description: Orquestra a criação de copy e criativos para um cliente de tráfego pago do começo ao fim — monta ou lê o briefing do cliente (banco de lacunas) salvo no projeto, escolhe nível de consciência e ângulos, gera ganchos, escolhe formatos, escreve roteiros com "como fica na tela" e o que gravar, headlines da página, plano de teste em ABO com critério de validação e rotina de variação, com checagem de compliance (OAB, Meta, números reais). Use quando pedirem "cria criativos para o cliente X", "copys para o cliente", "pacote de criativos novos", "briefing de copy do cliente", "o criativo cansou, faz novos", "plano de teste de criativos" ou "roteiros e ganchos para a campanha de [produto]".
---

# Copy e criativos para um cliente (orquestrador)

Você conduz o trabalho inteiro para um cliente e chama as skills especializadas em cada etapa. O resultado são arquivos no projeto do cliente, prontos para o gestor aprovar, o especialista gravar e o editor montar. Nada é publicado por esta skill.

Skills que você usa:
- `copy-ganchos-headlines` — ganchos e headlines;
- `copy-formatos-criativo` — formatos e a ficha "Como fica na tela";
- `copy-roteiro-anuncio` — roteiros, revisão e variações;
- `copy-pagina-low-ticket` — página de venda curta (quando a página entra no escopo);
- existentes, quando fizer sentido: `espionar-concorrente` (referências do nicho), `editar-criativos` (produção do vídeo bruto), `lp-captacao` (página de captação com WhatsApp), `subir-campanha` (só com aprovação explícita do gestor).

## Fluxo

### 0. Situar
- Identifique o cliente, a marca que assina e o produto. Confirme a pasta do projeto atual (é nela que os arquivos ficam).
- Procure contexto que já existe: `copy/briefing-<cliente>.md`, histórico de criativos, relatórios de campanha, páginas, transcrições de anúncios e lives, documentos de voz do especialista. Leia antes de perguntar.
- Pergunte só o que faltar e travar o trabalho; o resto entra como suposição marcada.

### 1. Briefing (banco de lacunas)
- Se não existe, crie `copy/briefing-<cliente>[-produto].md` no projeto a partir de `references/template-briefing.md`.
- Preencha com fontes do projeto. **Marque cada item:** `[confirmado: fonte]`, `[suposição]` ou `[a confirmar com <quem>]`.
- Números (clientes, alunos, compradores, faturamento, anos, resultados) só entram como confirmados se houver fonte. O que estiver "a confirmar" não vai para criativo.
- Registre a classe de compliance do cliente (ver passo 7).

### 2. Diagnóstico rápido (se a conta já roda)
- O que está no ar, o que vendeu, o que cansou. Separe criativo × página × checkout antes de concluir (veja `copy-pagina-low-ticket`, `references/checklist-pagina.md`, seção 2).
- Descubra o **ângulo que traz o comprador certo** (não só o CTR mais alto) e as aberturas já queimadas.
- Se não há dado, siga com o briefing e trate o primeiro lote como teste de ângulo.

### 3. Nível de consciência e ângulos
- Defina o nível do público de cada conjunto (frio de interesse aberto ≈ inconsciente/problema; remarketing ≈ produto/totalmente consciente).
- Escolha 2 a 4 ângulos: o do campeão (se houver) como principal, um vizinho e um de teste. Use `copy-ganchos-headlines`, `references/niveis-e-angulos.md`.

### 4. Ganchos
- Gere o dobro do pedido e corte pelo checklist da skill de ganchos. Cada gancho com versão falada, texto de tela, ângulo, nível e formato sugerido.

### 5. Formatos
- Para cada roteiro, escolha o formato pela matriz de `copy-formatos-criativo` (objetivo, nível, custo, risco do nicho). Lote com famílias diferentes. Inclua pelo menos uma variação "só edição" de um criativo validado, se houver.

### 6. Roteiros
- Escreva com `copy-roteiro-anuncio`: blocos de tempo, fala e tela, ficha "Como fica na tela", "o que gravar / o que editar", copy do anúncio (texto principal e título), cuidados.
- Na voz do especialista (bordões, jeito de abrir, palavras que ele não usa) e com a assinatura certa da marca.

### 7. Compliance (portão obrigatório antes de entregar)
- Passe tudo por `references/compliance.md`. Classes:
  - **A — advocacia para cliente final** (Código de Ética da OAB e Provimento 205/2021): o formato e o gancho servem; a promessa e a oferta não.
  - **B — infoproduto/educação para profissionais** (inclusive advogados): regras normais da Meta e do consumidor.
  - **C — demais nichos**, com atenção a saúde, finanças e renda (políticas especiais da Meta).
- Em todas: nenhum número inventado; prova só com dado real do cliente.

### 8. Página (se estiver no escopo)
- Headlines (e variantes de topo por ângulo) com `copy-ganchos-headlines`; página completa ou revisão com `copy-pagina-low-ticket`. A promessa do anúncio vira a headline.

### 9. Plano de teste
- Monte o plano com `references/plano-de-teste.md`: ABO, um criativo por conjunto, verba e duração, controle, critério de corte e de vencedor ligado à meta real do cliente (CPA, custo por lead qualificado, ROAS).
- Verba, pausa e realocação são decisão do gestor: o plano vai **para aprovação**.

### 10. Entrega e registro
- Salve no projeto, no formato de `references/formato-de-entrega.md` (nome sugerido: `copy/criativos-<cliente>-<AAAA-MM-DD>.md`, ou a pasta de rotina que o projeto já usa).
- Liste no fim: decisões que dependem do gestor, números a confirmar, provas a coletar, e o que já pode ir para gravação.
- Se o projeto tem histórico de criativos, proponha as linhas novas (código, ângulo, formato, gancho) sem resultado ainda.

### 11. Rotina de variação (depois do teste)
- Vencedor validado → variações de formato (só edição) e de gancho em até 3 a 5 dias, sem esperar cansar.
- Semanal: análise interna (forças de conversão dos campeões) e externa (perfil espião, `espionar-concorrente`), 3 a 5 variações sobre a copy campeã, teste em ABO, registro. Detalhe em `copy-roteiro-anuncio`, `references/variacoes.md`.

## O que esta skill não faz

- Não publica, não pausa, não muda verba e não sobe anúncio (para subir, só com o OK do gestor e a skill `subir-campanha`).
- Não decide números em aberto com o cliente: sinaliza.
- Não grava nem edita vídeo (produção: `editar-criativos`).

## Referências

- `references/template-briefing.md` — o banco de lacunas do cliente, pronto para copiar para o projeto.
- `references/compliance.md` — OAB (Código de Ética e Provimento 205/2021), políticas da Meta, direitos e dados, regra de números.
- `references/plano-de-teste.md` — validação em ABO, critérios, quando adaptar a régua ao funil do cliente, escala e registro.
- `references/formato-de-entrega.md` — esqueleto do arquivo de entrega.

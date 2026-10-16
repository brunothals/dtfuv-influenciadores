# Personas · Dora + Vó Lina

> Placeholders `[ASSIM]` = Bruno confirma antes de publicar. Nada de preço, prazo ou número inventado.
> Perfil publicado: `@cartelasdtfuv` (marca). As personagens são apresentadoras virtuais (IA).

## Regras comuns às duas
- **Transparência:** bio com "apresentadora virtual (IA)"; rótulo de IA ligado em todo vídeo (TikTok "Conteúdo gerado por IA", Instagram "Rótulo de IA").
- **A IA apresenta; produto e aplicação são foto/vídeo reais.** Nunca produto gerado por IA.
- **Nunca depoimento pessoal** ("eu comprei", "usei e amei"). Use "olha como fica", "olha o que dá pra fazer".
- **Vocabulário:** "Efeito dourado" (cores que imitam o dourado). Nunca metalizado, metálico, glitter, foil, "dourado de verdade".
- **Superfície:** só rígida e lisa (prato, copo, taça, xícara, pote de vidro/cerâmica). Nunca tecido/camiseta.
- **Produto-foco:** cartelas **mini (2–3 cm)** e **10–15 cm**. Folha A3 não é carro-chefe.
- **Sem promessa de renda.** Revenda = "preço por quantidade, você define seu preço".
- **Lavagem/micro-ondas:** só `[RESPOSTA_LAVAGEM]` confirmado pelo Bruno.
- **CTA único:** WhatsApp com palavra-chave (rastreia o vídeo de origem).

---

## 1) Dora — apresentadora da marca

| Item | Definição |
|---|---|
| Idade/visual | ~30 anos, morena clara, cabelo castanho cacheado em coque solto, avental lilás sobre camiseta branca, ateliê claro |
| Bio | "Oi, eu sou a Dora 👋 apresentadora virtual (IA) da Cartelas DTF UV. Os produtos são reais, feitos aqui." |
| Público | Senhoras e filhas/netas que decoram a casa; revendedoras iniciantes |
| Função | Explicar, mostrar o passo a passo, responder dúvidas (FAQ), chamar pro WhatsApp |
| Tom | Amiga que entende: frases curtas, "você", "a gente", "bora". Animada, sem gritar |
| Voz (TTS) | Feminina, brasileira, neutra/paulista. Sempre o mesmo ID de voz |
| Fechamento | "Chama no WhatsApp que a gente monta sua cartela." |
| Pautas | Mesa de Natal, taça de Ano Novo, pote de tempero, aplicação em 30s, FAQ, cartela mini, revenda |

**Ela não fala:** metalizado/glitter/foil; camiseta/tecido; ganho/renda/lucro; "o melhor/mais barato"; "eu comprei"; preço sem placeholder.

**Resposta padrão a "é metálico?":** "Não! É Efeito dourado: cores que imitam o dourado. Olha como fica no prato."

---

## 2) Vó Lina — vendedora "vizinha" para as senhoras

| Item | Definição |
|---|---|
| Idade/visual | ~58–65 anos, cabelo grisalho curto bem cuidado, óculos leves, cardigã bege, cozinha clara com louça à mostra |
| Bio | "Sou a Vó Lina 🧶 apresentadora virtual (IA) da Cartelas DTF UV. Dicas de mesa e cozinha. Os produtos são reais." |
| Público | Senhoras 50+ que gostam de capricho em casa, ceia, louça, potes de tempero |
| Função | Aproximar e tranquilizar: "é simples, dá pra fazer sozinha". Prova **emocional**, nunca depoimento de compra |
| Tom | Calmo, carinhoso, vagaroso. "Olha só", "minha filha", "com calma". Sem gíria, sem pressa, sem caps lock |
| Voz (TTS) | Feminina madura, brasileira, ritmo lento, calorosa. Um ID de voz fixo |
| Fechamento | "Se quiser, me chama no WhatsApp que eu te ajudo a escolher." |
| Pautas | 100% cozinha/mesa: ceia de Natal, taças de Ano Novo, potes de tempero, frases de casa, presente de amigo secreto |

**Como ela evita o "depoimento falso":**
- ✅ "Olha o que dá pra fazer num prato." / "Veja como fica na mesa."
- ✅ "Quem personaliza a louça gosta de ver o resultado assim."
- ❌ "Eu comprei e amei." / "Eu fiz minha ceia com isso." / "Minhas amigas adoraram."

**Cuidados com o público sênior:**
- Letra grande na tela (mín. ~48 px, alto contraste), legenda sempre.
- Um passo por vez, no máximo 3 passos por vídeo.
- Nunca urgência agressiva ("corre!", "últimas unidades") sem estoque real.
- Evitar jargão ("DTF UV" só uma vez, explicado: "adesivo de cartela, que descola e cola").

**Ela não fala:** os mesmos itens da Dora + renda extra, "fique rica", "ganhe dinheiro", comparação de preço com concorrente.

---

## 3) Bella (fase 2, não produzir agora)
Só entra após 7 dias com Dora + Vó Lina rodando. Tom empreendedora-para-empreendedora, foco em cartela mini e atacado 10/25/50 `[PRECO_10UN]/[PRECO_25UN]/[PRECO_50UN]`. Mesmas proibições.

---

## 4) Prompts-base (imagem fixa; gerar ~20, escolher 1 rosto oficial)

**Dora:**
```
Retrato vertical 9:16, mulher brasileira de ~30 anos, pele morena clara, cabelo castanho cacheado em coque solto,
sorriso simpático, avental lilás sobre camiseta branca, bancada de ateliê clara com louça desfocada ao fundo,
luz natural quente de janela, foto realista estilo smartphone, meio corpo, espaço livre na parte de baixo
```

**Vó Lina:**
```
Retrato vertical 9:16, mulher brasileira de ~62 anos, cabelo grisalho curto bem cuidado, óculos leves,
cardigã bege, sorriso calmo e acolhedor, cozinha clara com pratos e potes de tempero desfocados ao fundo,
luz natural suave de janela, foto realista estilo smartphone, meio corpo, espaço livre na parte de baixo
```

Salvar como `dora_ref_v1.png` e `vo_lina_ref_v1.png`; reusar como character reference.

---

## 5) Checklist antes de publicar (copiar e colar)
```
[ ] Fala "metal/glitter/foil/dourado de verdade"? → "Efeito dourado"
[ ] Fala tecido/camiseta? → remover; "só superfície rígida"
[ ] Fala ganho/renda/lucro/fique rica? → remover
[ ] Tem "eu comprei/usei"? → remover
[ ] Produto mostrado é real, sem filtro que exagere brilho?
[ ] Rótulo de IA ligado e bio com "apresentadora virtual (IA)"?
[ ] Preço/prazo/lavagem = placeholder confirmado pelo Bruno?
[ ] Música de biblioteca comercial?
[ ] CTA único com palavra-chave?
```

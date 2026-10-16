# Pipeline de produção — 1–2 vídeos por dia

Escopo: operação de Dora e Vó Lina para Instagram Reels e TikTok. A IA apresenta; cartela, aplicação e resultado são sempre reais. Este documento não cria roteiros, anúncios ou prompts de personagem: copy é do Claude; pack de prompts é a tarefa 02 do Codex.

## Ferramentas e orçamento

Meta de ferramentas: **menos de R$100/mês**, sem compra obrigatória. Os valores abaixo são orçamento de operação, não cotação de assinatura. Não incluem anúncios, internet, celular, materiais, trabalho ou equipamentos. Não assinar testes com renovação automática para manter o fluxo.

| Etapa | Escolha inicial | Gasto recorrente planejado | Se houver limite ou cobrança |
|---|---|---|---|
| Edição | CapCut, somente recursos gratuitos disponíveis na conta | R$0 | Remover efeitos/templates Pro; usar cortes, texto e legendas manuais; testar exportação antes de montar o lote |
| Narração TTS | CapCut, voz PT-BR gratuita com uso comercial permitido | R$0 | Gravar narração própria/autorizada no celular; não clonar voz de terceiros |
| Imagem da apresentadora | Adobe Firefly, modelo de imagem Adobe, cota gratuita | R$0 | Reutilizar retrato aprovado; até existir retrato, produzir vídeo só com produto real e narração |
| Avatar/lip-sync | Dispensado nesta fase; retrato fixo com movimento leve no editor | R$0 | Não contratar para sustentar a cadência |
| Armazenamento | Pasta local com backup já disponível | R$0 incremental | Não enviar originais grandes ao Git |

Base planejada: R$0 de novas mensalidades. Reserva opcional máxima: R$99/mês no total, somente após Bruno verificar valor final em reais, impostos, renovação e direitos comerciais. Reserva não é preço de fornecedor nem autorização para comprar. Se a conta gratuita não oferecer o recurso, usar o fallback em vez de pressupor gratuidade ilimitada. Não copiar os preços estimados dos briefings como valores atuais.

A página oficial do [TTS CapCut](https://www.capcut.com/tools/ai-text-to-speech) informa vozes gratuitas e uso comercial, com algumas vozes premium. Conferir a voz selecionada. O [Firefly para rostos](https://www.adobe.com/products/firefly/features/ai-face-generator.html) oferece acesso gratuito limitado e descreve uso comercial de rostos gerados com modelos Firefly; isso não estende automaticamente direitos a modelos de parceiros. Materiais, músicas e templates têm [licenças próprias no CapCut](https://article.capcut.com/clause/material-license-agreement). Recursos e limites variam; registrar a verificação na ficha do lote. Fontes consultadas em 15/10/2026.

## Preparação única e lote semanal

1. Separar os roteiros aprovados entregues pelo Claude. Se ainda faltarem, deixar ficha como `AGUARDA_COPY`; não inventar copy longo. Registrar persona, tema, palavra-chave e produto de cada vídeo.
2. Começar com Dora e incluir Vó Lina com referência aprovada. Vó Lina é apresentadora virtual, não cliente nem senhora real dando depoimento. Usar a mesma referência e voz por personagem; registrar arquivo, ferramenta, nome/ID da voz e ajustes. Sem referência disponível, usar produto real em tela inteira.
3. Captar banco real conforme [assets/README.md](../../assets/README.md): mini, régua, aplicação e resultado. Guardar originais e autorizações fora do Git.
4. Criar projeto mestre CapCut 9:16, 1080×1920, 30 fps. Trilhas: produto real; apresentadora opcional; narração; legendas; identificação IA e CTA. Produto ocupa área principal; retrato nunca encobre aplicação ou medidas.
5. Fazer três pilotos: Dora/Natal, Vó Lina/temperos e aplicação real. Testar som, leitura, exportação limpa e destino do WhatsApp antes de duplicar o mestre.
6. Organizar 7–14 fichas para a semana. Pelo menos 70% devem tratar de senhoras + mesa/cozinha/Natal: mínimo de 5 em 7 ou 10 em 14. Priorizar mini (adesivos de 2–3 cm, confirmar tamanho real) e formatos de 10–15 cm; não usar A3 como carro-chefe. Natal/Ano Novo até 31/12; temperos e floral sustentam o conteúdo contínuo.

## Ordem de produção por vídeo

1. **Ficha:** ID `AAAAMMDD_persona_tema_v01`, roteiro aprovado, palavra-chave, arquivos reais, destino `[WHATSAPP]` e dados comerciais confirmados. Sem preço confirmado, omitir valor e encaminhar consulta; não exportar placeholders visíveis.
2. **Áudio:** gerar TTS PT-BR ou gravar voz autorizada. Ouvir tudo; corrigir pronúncia de DTF UV e ritmo. Voz de Vó Lina calma e clara, sem caricatura de idade. Duração final de 15–30 segundos.
3. **Montagem:** duplicar mestre; gancho até 3s, demonstração real no corpo e um CTA no fechamento. Usar imagem fixa da persona, sem fingir sincronização labial. Nunca gerar cartela ou aplicação com IA, nem adicionar brilho que altere o produto.
4. **Legendas:** transcrever e revisar manualmente se automático for pago. Texto de alto contraste, frases curtas, até duas linhas por vez; ponto inicial 48–64 px em 1080p, validado no celular. Não depender só de cor ou de áudio. Manter texto longe das áreas de interface e conferir na prévia de cada plataforma.
5. **Produto:** dizer “Efeito dourado: cores que imitam o dourado”. Não apresentar como metalizado, metálico, glitter, foil ou ouro. Só superfícies rígidas compatíveis; medidas, lavagem e prazo somente conforme confirmação de Bruno. Para louças, não mostrar aplicação em áreas de contato com boca, bebida ou comida.
6. **CTA:** usar uma palavra-chave do roteiro e destino confirmado. Modelo técnico de URL: `https://wa.me/[WHATSAPP]?text=[MENSAGEM_CODIFICADA_COM_PALAVRA]`. Número internacional só com dígitos, confirmado por Bruno; codificar texto antes do teste. Alternativa: link confirmado na bio + palavra na tela. Não inventar número nem instalar Pixel neste repo.
7. **QA:** preencher [checklist-video.md](checklist-video.md), assistir no celular com e sem som e corrigir problemas.
8. **Exportação:** MP4 H.264, 1080×1920, 30 fps, sem marca d’água ou recurso Pro pendente. Exportar um master limpo para ambos os canais. Música só com licença para o canal e para anúncio, se aplicável; se incerto, publicar sem música. Áudio licenciado apenas em uma plataforma não deve ir no master compartilhado.
9. **Publicação manual:** ativar divulgação de IA em cada plataforma e verificar prévia. Identificação persistente “Apresentadora virtual (IA) · produto real” no vídeo; não fingir depoimento de compra/uso. Este pipeline não autoriza publicar nem contratar mídia automaticamente.
10. **Registro:** guardar arquivo exportado, checklist, URL do post e palavra-chave. Anotar conversas atribuídas e pedidos agregados, sem expor telefone ou conversa de cliente no Git.

## Ritmo e controle

Proposta de rotina, a medir nos pilotos: 1 sessão semanal de captação e preparação; diariamente 1 vídeo, segundo vídeo apenas quando ambos passarem QA. Meta de 30–60 minutos por edição após banco/mestre prontos, não promessa de produtividade. Se faltar material real, copy ou confirmação comercial, registrar pendência e usar outra ficha aprovada; não completar com produto fictício.

Ficha mínima por vídeo:

```text
ID / data / responsável:
Persona / referência / voz / versão:
Tema / roteiro aprovado / palavra-chave:
Assets reais / origem / autorização:
WhatsApp confirmado / teste do destino:
Dados comerciais confirmados por Bruno em:
Ferramentas / licença conferida em / gasto acumulado do mês:
Checklist aprovado por / data:
Export local / URL TikTok / URL Reels:
Conversas e pedidos agregados / pendências:
```

## Transparência nas plataformas

No TikTok, ativar a configuração de conteúdo gerado por IA antes de postar as apresentadoras ou áudio sintético realista, conforme [orientação oficial](https://support.tiktok.com/pt_BR/using-tiktok/creating-videos/ai-generated-content). Na Meta, usar a opção de divulgação de IA disponível no envio e conferir o rótulo; a plataforma também aplica identificação por sinais detectados, conforme [AI info](https://about.fb.com/news/2024/04/metas-approach-to-labeling-ai-generated-content-and-manipulated-media/). Para anúncio, conferir também o fluxo de divulgação no gerenciador; a [documentação de transparência de anúncios](https://about.fb.com/news/2025/02/gen-ai-transparency-metas-ads-products/) descreve rótulos em anúncios. Não remover metadados para evitar identificação. Nomes e posição dos controles podem variar; registrar a conferência, sem tratar a frase na legenda como substituta de um controle exigido.

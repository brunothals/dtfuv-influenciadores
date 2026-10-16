# Prompts · Dora (v1)

> Gera **só a apresentadora**. Nunca gerar cartela, adesivo, louça decorada ou aplicação com IA — produto é sempre foto/vídeo real (overlay). Ferramenta inicial: Adobe Firefly (ver `pipeline.md`); funciona também em Ideogram/Flux/ChatGPT/Midjourney.

## Prompt-base (gerar ~20, escolher 1)
```
Retrato vertical 9:16, mulher brasileira de ~30 anos, pele morena clara, cabelo castanho cacheado em coque solto,
sorriso simpático, maquiagem leve, avental lilás liso sobre camiseta branca, bancada de ateliê clara com copos e
canecas lisos desfocados ao fundo, luz natural quente de janela lateral, foto realista estilo smartphone, meio corpo,
olhando para a câmera, espaço livre no terço inferior do quadro, mãos vazias
```
**Negativo:** `texto, logotipo, marca d'água, joias douradas, roupa brilhante, glitter, metalizado, adesivos, objetos decorados, mãos deformadas, dedos extras, rosto infantil`

## Referência (cref)
- Salvar escolhido como `assets/personas/dora/dora_ref_v1.png` (original fora do Git se > 1 MB; ver `assets/README.md`).
- Firefly: *Referência de composição/estilo* = `dora_ref_v1.png`, força alta. Midjourney: `--cref <url> --cw 100 --ar 9:16`. ChatGPT/Ideogram: anexar a imagem + "mesma pessoa, mesmo rosto, mesma roupa".
- Seed/ID e ferramenta → registrar em `dora_ref_v1.txt`. Mudou o rosto? vira `v2`, nunca sobrescrever.

## 6 poses (sufixo ao prompt-base + cref)
| Arquivo | Uso | Sufixo |
|---|---|---|
| `dora_p1_acenando.png` | abertura | `acenando com a mão direita, sorriso aberto` |
| `dora_p2_apontando.png` | overlay produto | `apontando para baixo com o indicador, olhando para baixo` |
| `dora_p3_celular.png` | envie sua arte | `segurando um celular com a tela virada para a câmera, tela em branco` |
| `dora_p4_queixo.png` | FAQ | `mão no queixo, expressão pensativa e simpática` |
| `dora_p5_joinha.png` | CTA | `polegar para cima, sorriso` |
| `dora_p6_surpresa.png` | antes/depois | `expressão de surpresa alegre, mãos abertas perto do rosto` |

Exportar PNG 1080×1920 + versão sem fundo (remoção de fundo do editor). Checar mãos e rosto contra a ref antes de aprovar.

## Selo obrigatório no vídeo
`Apresentadora virtual (IA) · produto real` + rótulo de IA na plataforma.

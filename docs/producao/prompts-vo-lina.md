# Prompts · Vó Lina (v1)

> Mesma regra: IA gera só a apresentadora; produto/aplicação sempre real. Persona: `docs/ads/influenciadores/personas.md`.

## Prompt-base
```
Retrato vertical 9:16, senhora brasileira de ~60 anos, cabelo grisalho curto bem cuidado, óculos leves de armação
fina, sorriso calmo e carinhoso, cardigã bege sobre blusa clara, cozinha clara e aconchegante com potes de vidro lisos
e louça branca lisa desfocados ao fundo, luz natural suave de janela, foto realista estilo smartphone, meio corpo,
olhando para a câmera, espaço livre no terço inferior do quadro, mãos vazias
```
**Negativo:** `texto, logotipo, marca d'água, caricatura, envelhecimento exagerado, roupa brilhante, glitter, metalizado, adesivos, louça decorada, mãos deformadas, dedos extras`

## Referência (cref)
- `assets/personas/vo-lina/lina_ref_v1.png` + `lina_ref_v1.txt` (ferramenta, seed, data). Mesmo fluxo de cref da Dora. Versão nova = `v2`.

## 6 poses
| Arquivo | Uso | Sufixo |
|---|---|---|
| `lina_p1_acenando.png` | abertura | `acenando suavemente, sorriso acolhedor` |
| `lina_p2_apontando.png` | overlay produto | `apontando para baixo, olhando para a bancada` |
| `lina_p3_xicara.png` | fé / café | `segurando uma xícara branca lisa com as duas mãos` |
| `lina_p4_pensativa.png` | FAQ | `mão no queixo, olhar gentil` |
| `lina_p5_coracao.png` | CTA | `mãos juntas no peito, expressão de carinho` |
| `lina_p6_surpresa.png` | antes/depois | `surpresa alegre, mão na bochecha` |

Xícara/louça na pose tem de ser **lisa**; o adesivo real entra por overlay.
Exportar PNG 1080×1920 + sem fundo. Selo `Apresentadora virtual (IA) · produto real`.

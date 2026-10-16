# Voz TTS · como travar a mesma voz

## Escolha (uma vez por persona)
1. CapCut → Texto → Texto para fala, idioma Português (Brasil). Usar só voz **gratuita com uso comercial** (conferir; ver `pipeline.md`).
2. Testar a frase-padrão com 3 vozes cada:
   - Dora: "Oi, eu sou a Dora! Isso aqui é Efeito dourado: cores que imitam o dourado. Chama no WhatsApp."
   - Vó Lina: "Minha filha, olha só que capricho no pote de tempero. Sem máquina, sem calor."
3. Critério: Dora = feminina, animada, sotaque neutro; Vó Lina = feminina madura, calma, clara (sem caricatura).
4. Registrar em `assets/personas/<persona>/voz.txt`: ferramenta, **nome exato da voz**, velocidade, tom, data, conta usada.

## Travar
- Sempre a mesma voz + mesma velocidade (Dora 1.0–1.1×; Lina 0.9–1.0×). Não mudar efeito/estilo.
- Salvar um projeto CapCut "MESTRE_VOZ_<persona>" com a faixa configurada e duplicar para cada vídeo.
- Guardar `<persona>_voz_teste_v1.mp3` (10s) como referência auditiva; ouvir antes de cada lote.
- Se a voz sumir/virar paga: escolher substituta e registrar `v2`; não misturar vozes na mesma semana.

## Pronúncia
- "DTF UV" → escrever **"dê tê éfe u vê"** no texto do TTS.
- "Efeito dourado" sempre por extenso. "2027" → "dois mil e vinte e sete". "WhatsApp" → "uatsapp" se a voz errar.

## Proibido
Clonar voz de pessoa real/terceiro; usar voz premium sem licença; voz que soe como depoimento ("eu comprei").
Fallback: narração gravada por pessoa autorizada (registrar autorização fora do Git).

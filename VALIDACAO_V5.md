# Validação — V5 · Profundidade Operacional CIC

**Status:** 32 cenários preservados; profundidade aumentada sem criar novos cenários.

## Quantitativo
- Cenários: 32
- Pontos de decisão: 227
- Média: 7.1 decisões/cenário
- V4 de origem: 127 decisões
- Novas decisões de aprofundamento: 100

## Princípios de expansão
1. Não transformar cada linha do checklist em pergunta.
2. Criar decisão apenas quando há algo a diagnosticar, priorizar, selecionar, confirmar ou coordenar.
3. Reforçar leitura de painel e resposta da planta.
4. Repetir conceitos críticos em contextos diferentes para fixação, sem repetir literalmente a mesma pergunta.
5. Manter uma única resposta de referência por decisão, salvo etapas legadas do tipo “ação proibida”.
6. Manter rastreabilidade documental em todas as decisões.

## Pontos críticos mantidos
- L-3901/L-3902 antes de inversão de pressões no Trip Total;
- PI-39035 em 5 kgf/cm² na troca de sangria do Trip Total;
- purga mínima 10 min / recomendável 30 min;
- J-3902: classificação com ou sem corte total e rampa 6000→3500 m³/d;
- FIC-39024/FIC-39025 em 150 t/d quando aplicável;
- Cat-Coolers: RV, 7000 m³/d, TFD 700 °C e intertravamento de alta ativo;
- Trip Parcial: 4500 t/d de ar, ΔP 300 gf/cm², sangria N₂, circulação inicial L-3902 máx. 5%, nível retificador 80%, Reg. +0,7 kgf/cm², ~690 °C / riser ~570 °C;
- falha elétrica: equipamentos afetados, bicos, torres, J-3901/J-3902, referência de nível 40%, LB e ventiladores GV-3901;
- perda de AI: confirmar fail-safe real, HS-39010 e PV-39210;
- perda de N₂: sangria por ar e buffer J-3902 por gás combustível;
- flooding: suspender serviços, não expor campo, não aumentar ar manualmente, reduzir gás em patamares de 25%, AI-39151, 5–10 min, HS-39493/XV-39223;
- explosões B-3902/GV-3901: trip adequado, Trip Total, combate a incêndio, EPI e avaliação do Supervisor.

## Validações automáticas do pacote
- 32 cenários;
- 227 decisões;
- 4 alternativas por decisão;
- referência documental em todas as decisões;
- uma resposta de referência por decisão, exceto etapas legadas de identificação de ação proibida;
- JavaScript/manifest/service worker verificados antes do empacotamento.

# Modelagem Logística de Grua com Redes de Petri Coloridas (CPN)

Projeto desenvolvido para a disciplina de Informática Aplicada à Engenharia Civil (Equipe MMM - 2026.2).

## Estrutura do Repositório
* `/modelo_1_basico`: Primeira modelagem em Rede de Petri.
* `/modelo_2_grua_avancado`: Rede de Petri Colorida Temporizada (`Projeto_GRUA_equipe_MMM_2026_2.cpn`) com curva de carga, controle climático e cálculo de tempo de ciclo.
* `/evidencias`: Capturas de tela da validação e da simulação executada no CPN IDE.
* `/documentacao`: Relatório técnico completo em PDF.

## Recursos Implementados no Modelo 2 (CPN ML)
* **6 Colorsets:** `MATERIAL`, `PESO`, `SETOR`, `VENTO`, `CARGA` e `STATUS_GRUA`.
* **4 Variáveis:** `m`, `p`, `s` e `v`.
* **2 Funções de Engenharia:** `capacidade_ok(p, s)` (validação de momento fletor por raio de alcance) e `tempo_ciclo(p, s)` (cálculo dinâmico de duração da operação).
*

# Modelo de Dor Crónica V2

## 1. Âmbito

Este documento define o modelo de dor crónica como um modelo de sistema de controlo determinístico com camadas regulatórias explícitas. O objetivo é preservar a rastreabilidade desde hipóteses mecanísticas até à leitura fisiológica e à perceção da dor.

## 2. Fundação Conceptual

A dor crónica é modelada como um sistema regulatório multicamada em que mediadores inflamatórios, sinalização neurovascular e microcirculação interagem através de dinâmicas de ciclo de feedback. O modelo assume que a desregulação persistente pode estabilizar em pontos de regulação maladaptativos.

## 3. Modelo Regulatório das Prostaglandinas

O modelo regulatório das prostaglandinas é usado como camada de controlo bioquímico para amplificação inflamatória e temporização da resolução.

### 3.1 Variáveis Principais

- Pressão de síntese de prostaglandinas
- Estado de sensibilidade recetorial
- Oxigenação tecidular local
- Carga de ativação de citocinas

### 3.2 Pressuposto Regulatório

A carga líquida de mediadores é representada como uma variável de estado limitada que conduz a adaptação a jusante do limiar nociceptivo.

## 4. Modelo de Sistema de Controlo

O modelo de sistema de controlo liga entradas periféricas à modulação central usando controladores aninhados e ciclos de correção de erro.

### 4.1 Camadas de Controlo

1. Controlador inflamatório periférico
2. Controlador vascular-microcirculatório
3. Controlador de modulação central

### 4.2 Regra de Transição de Estado

Uma transição de comportamento agudo para crónico ocorre quando correções compensatórias aumentam o ganho de longo prazo em vez de reduzir o erro.

## 5. Reflexo Viscero-Cutâneo e Microcirculação

O reflexo viscero-cutâneo é tratado como uma via de acoplamento entre stress de órgão interno e zonas de dor cutâneas/musculares. A microcirculação é modelada como uma rede de transporte limitada sensível à concentração de mediadores.

```text
[Inflammatory mediators] --> [Microcirculation shift] --> [Tissue stress]
          ^                                               |
          |------------------- [feedback loop] -----------|
```

## 6. Camada de Leitura Fisiológica

A leitura fisiológica integra indicadores mensuráveis usados para calibração do modelo.

- Gradiente de temperatura cutânea
- Variação de perfusão local
- Limiar de dor à pressão
- Equilíbrio autonómico em repouso

## 7. Camada de Perceção da Dor

A perceção da dor é representada como a saída de entrada nociceptiva ponderada, modulação contextual e histórico de adaptação.

```text
Pain perception = f(nociceptive input, contextual modulation, adaptation history)
```

## 8. Referências

1. Basbaum AI, Bautista DM, Scherrer G, Julius D. Cellular and Molecular Mechanisms of Pain. https://www.cell.com/cell/fulltext/S0092-8674(09)01488-3 (2009)
2. Tracey I, Bushnell MC. How Neuroimaging Studies Have Challenged Us to Rethink: Is Chronic Pain a Disease? https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4058737/ (2009)
3. Woolf CJ. Central sensitization: Implications for the diagnosis and treatment of pain. https://pubmed.ncbi.nlm.nih.gov/15262125/ (2011)

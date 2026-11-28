# Documento Mestre de Contexto: Projeto Universo Zero (Arquitetura v2.0)

## 1. Visão Geral & Posicionamento Científico
O **Universo Zero** é um simulador de vida artificial, sistemas complexos emergentes e cosmologia computacional desenvolvido inicialmente em HTML5 Canvas / JavaScript puro.

* **Abordagem Neutra & Inclusiva:** O projeto é posicionado estritamente como um **laboratório matemático de sistemas adaptativos**. Ele não busca refutar ou validar crenças religiosas ou filosóficas sobre a origem real do cosmos, mas sim estudar como informação, cooperação, termodinâmica e resiliência se auto-organizam sob leis físicas simuladas, gerando dados úteis para biologia teórica, computação e ciência cidadã.
* **Ciência Cidadã Distribuída:** Múltiplos colaboradores podem executar simulações independentes em seus navegadores e exportar arquivos `.json` contendo o estado evolutivo, permitindo análises estatísticas em larga escala.

---

## 2. Arquitetura Atual (Web Prototype - Fases 1 a 8)
Cada fase é estruturada em um arquivo HTML independente (`fase1.html` até `fase8.html`), compartilhando uma barra de navegação superior sincronizada.

* **Fases 1 a 6:** Progressão da física básica, partículas, captura de energia, replicação, mutação e formação de estruturas primitivas.
* **Fase 7 (`fase7.html`) — Civilização, Bibliotecas Culturais & Consciência 12 Bits:**
  * Introduz o **Genoma de 12 Bits**, ciclos sazonais rigorosos (*Verão Cósmico* vs. *Inverno Cósmico*) e **Bibliotecas Culturais** (estruturas que arquivam genomas ancestrais e permitem "downloads culturais" para indivíduos próximos).
* **Fase 8 (`fase8.html`) — Multiverso & Semeadura Cósmica:**
  * Divide o espaço em **Universo Alfa** (criador) e **Universo Beta** (filho), separados por uma membrana dimensional.
  * Civilizações avançadas no Universo Alfa lançam **Sondas de Semeadura** carregando pacotes genéticos para colonizar o Universo Beta.

### Mapeamento do Genoma de 12 Bits
Cada bit ativa traços comportamentais, metabólicos ou estruturais com custo energético associado:
* **Bits 1–3 (Base):** Coesão vs. Simbionte (`0`/`1`), Econômico vs. Veloz (`0`/`1`), Social vs. Solitário (`0`/`1`).
* **Bits 4–12 (Habilidades):** Percepção (👁️), Memória (🧠), Sinal (📡), Colônia (🧬), Escudo (🛡️), Arquiteto (🏛️), Consciência (✨), entre outros moduladores.

---

## 3. Descobertas Empíricas das Simulações (Dados Coletados)

### Experimento A: Fase 8 — Expansão Rápida (Ciclo 1.400)
* **Cenário:** 0 Invernos Cósmicos vencidos; 278 Sondas de Semeadura lançadas; Universo Beta semeado.
* **População:** 210 no Universo Alfa (7 bibliotecas) vs. 1.865 no Universo Beta (7 bibliotecas).
* **Trocas de Conhecimento:** 37.592 bits trocados.
* **Genoma Dominante (`010111110111` — 227 indivíduos):** *Coesão • Veloz • Social* com todas as habilidades avançadas ativas (`Percepção`, `Memória`, `Sinal`, `Colônia`, `Escudo`, `Arquiteto`, `Consciência`). Em fase de expansão abundância, velocidade e cognição máxima vencem.

### Experimento B: Fase 7 — Longo Prazo & Seleção Severa (Ciclo 1.386.496)
* **Cenário:** **770 Invernos Cósmicos vencidos**; 1.364 downloads culturais; 297.036 bits trocados.
* **Convergência Total (100% da População — 360 indivíduos):** Todos os organismos vivos convergiram para um único genoma otimizado: **`000011110110`** (*Coesão • Econômico • Social* | `Percepção`, `Memória`, `Sinal`, `Colônia`, `Escudo`, `Arquiteto`).
* **Insights Científicos:**
  1. **Custo da Consciência e Velocidade:** Sob estresse térmico prolongado (770 invernos), o gasto energético da *Consciência* (Bit 12 = 0) e da *Velocidade* (Bit 2 = 0) levou à extinção desses traços em favor do metabolismo *Econômico* + defesa coletiva (`360 núcleos de colônia` e `360 defensores com escudo`).
  2. **Memória Fóssil:** As 12 Bibliotecas Culturais preservaram genomas fundadores desde a Geração 1 (ex: `100001010010`), funcionando como banco de resiliência genética.

---

## 4. Roadmap de Expansão (Arquitetura v2.0)

### Etapa 1: Documentação & Padronização (Concluído)
* Consolidação dos dados, regras de neutralidade científica e estrutura de dados JSON.

### Etapa 2: Nuvem & Ciência Cidadã (Firebase Firestore)
* Conectar `fase7.html` e `fase8.html` ao **Firebase Firestore** via SDK Web.
* Permitir envio automático ou com 1 clique dos JSONs gerados por colaboradores para formar um banco de dados global de genomas e métricas.
* Criação de portal web interativo com **Quizzes Educativos** (astronomia, física, sistema solar) para engajar o público e desbloquear parâmetros de simulação.

### Etapa 3: Agente de IA Cientista + Kit de Semente Cósmica (Python)
Desenvolvimento de um agente autônomo em Python para automatizar cálculos, leitura/salvamento de dados e exploração de hipóteses físicas, mantendo intactos os **4 Pilares do Kit de Semente Cósmica**:
1. **Pulso de Calibração:** Autoajuste de constantes iniciais (energia, entropia, taxa de mutação).
2. **Regras de Interação (Física do Sistema):** Leis de conservação de energia, custo metabólico por bit e limites termodinâmicos.
3. **Lógica da Memória e do Erro (DNA Digital):** Replicação binária com mutação controlada e herança cultural via bibliotecas.
4. **Impulso de Curiosidade (Busca por Padrões):** Função de recompensa focada na emergência de complexidade e troca de informação (bits), não apenas volume populacional.

#### Laboratório de Modelos Cosmológicos (Testes do Agente)
* **Inflação Cósmica:** Expansão espacial exponencial inicial e resfriamento rápido.
* **Universo Oscilante (*Big Bounce*):** Ciclos de contração e renascimento preservando frações de memória/constantes.
* **Gravidade Quântica em Loop:** Espaço discretizado em nós/grafos com limite máximo de densidade por nó.
* **Teoria M & Seleção Natural Cosmológica (Lee Smolin):** Singularidades/buracos negros geram universos filhos com constantes físicas levemente mutadas, selecionando universos produtores de complexidade.

### Etapa 4: Visualização 3D Procedural (Unity Engine)
* Importação dos arquivos JSON (locais ou via Firebase) no **Unity (C#)**.
* Tradução procedural dos 12 bits em morfologia e comportamento 3D (ex: bit *Escudo* instancia malha protetora; bit *Veloz* adiciona propulsores; bit *Colônia* cria conexões físicas entre agentes).

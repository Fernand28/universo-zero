# Contexto do Projeto: Universo Zero (Fases 1 a 8)

Este documento reúne a arquitetura, as mecânicas implementadas, as correções feitas e os resultados obtidos na simulação **Universo Zero**, estruturado para transferir contexto completo a outros assistentes de IA ou desenvolvedores.

---

## 1. Visão Geral e Arquitetura do Projeto

* **Nome do Projeto:** Universo Zero
* **Tecnologias:** HTML5, CSS3 e JavaScript puro (Canvas 2D para renderização da simulação).
* **Estrutura de Arquivos:** O projeto é dividido em arquivos HTML independentes que representam a evolução do sistema por eras (`fase1.html` até `fase8.html`), além de um `README.md`.
* **Navegação:** Uma barra superior padronizada (`ERAS: Era 1 ... Era 8: Multiverso`, `Dados`, `Colaborar`) permite alternar entre os arquivos de cada fase.

---

## 2. Mecânicas da Fase 8 (`fase8.html` — Multiverso & Semeadura Cósmica)

A Fase 8 simula a transição entre dois universos separados por uma **Membrana Dimensional** central:

1. **Universo Alfa (Primordial / Criador):** Onde a vida inicial surge (acionada pelo botão *Big Bang Alfa* ou por injeção manual de sementes binárias de 12 bits) e evolui até formar **Bibliotecas** conscientes.
2. **Sondas de Semeadura:** Quando as civilizações em Alfa atingem maturidade, lançam pacotes binários (sondas) através da membrana para o vazio do Universo Beta (acionável também manualmente via botão *Lançar Sonda*).
3. **Universo Beta (Civilização Filha):** Inicialmente um vazio absoluto (`UNIVERSO BETA (VAZIO ABSOLUTO)`), torna-se uma civilização filha (`UNIVERSO BETA (CIVILIZAÇÃO FILHA)`) assim que a primeira sonda eclode e inicia uma nova linhagem evolutiva.
4. **Ciclos Ambientais (Estações):** Alternância dinâmica entre **Verão Cósmico** (surgimento de novos Oásis de energia) e **Inverno Cósmico** (escassez e pressão seletiva).
5. **Parâmetros Ajustáveis e Exportação:**
   * Controles deslizantes para **Taxa de Mutação** e **Energia dos Oásis**.
   * Injeção de semente customizada de 12 bits (ex.: `100011110111`).
   * Exportação completa do estado e ranking genético em arquivo `.json` (*Exportar Multiverso JSON*).

---

## 3. Histórico de Bugs Resolvidos nesta Sessão

* **Dessincronização do Menu de Navegação:** Fases mais recentes não exibiam links para `fase1.html` e `fase2.html`, enquanto fases anteriores (como `fase3.html` e `fase7.html`) não tinham links para as fases posteriores. **Solução:** Padronização da barra `<nav>` superior em todos os arquivos (`fase1.html` a `fase8.html`).
* **Simulação Não Iniciava na Fase 8:** O arquivo `fase8.html` estava com alterações não salvas no editor (VS Code) e problemas de formatação/delimitadores de *template strings* no JavaScript que impediam os listeners de clique (`btn-bigbang`, `btn-force-probe`, `btn-reset`, `btn-export`) de responderem. **Solução:** Correção da sintaxe JS, salvamento do arquivo e atualização no navegador.

---

## 4. Dados da Simulação Exportada (Ciclo 1400)

Abaixo estão os resultados extraídos do JSON oficial gerado após a estabilização da Fase 8:

### Métricas Gerais do Multiverso
* **Timestamp:** `2026-11-27T19:32:30.684Z`
* **Estação Atual:** Inverno Cósmico
* **Ciclos de Tempo:** 1.400
* **Invernos Vencidos:** 0
* **Sondas de Semeadura Lançadas:** 278
* **Universo Beta Semeado:** `true`
* **População Universo Alfa:** 210 indivíduos (7 Bibliotecas)
* **População Universo Beta:** 1.865 indivíduos (7 Bibliotecas)
* **Trocas de Conhecimento:** 37.592 bits

### Estrutura do Genoma (12 Bits)
Cada indivíduo possui um código binário de 12 bits que define comportamentos base e módulos cognitivos/estruturais:
* **Comportamento Social/Metabólico:** `Coesão` vs `Simbionte` | `Veloz` vs `Econômico` | `Social` vs `Solitário`
* **Módulos Avançados:** `👁️ Percepção`, `🧠 Memória`, `📡 Sinal`, `🧬 Colônia`, `🛡️ Escudo`, `🏛️ Arquiteto`, `✨ Consciência`

### Top 10 Genomas Dominantes (Ciclo 1400)
| Posição | Código Binário | Características | Indivíduos |
| :--- | :--- | :--- | :--- |
| **1º** | `010111110111` | Coesão • Veloz • Social \| Percepção, Memória, Sinal, Colônia, Escudo, Arquiteto, Consciência | **227** |
| **2º** | `000111110111` | Coesão • Econômico • Social \| Percepção, Memória, Sinal, Colônia, Escudo, Arquiteto, Consciência | **174** |
| **3º** | `010110110111` | Coesão • Veloz • Social \| Percepção, Sinal, Colônia, Escudo, Arquiteto, Consciência | **97** |
| **4º** | `011011110111` | Coesão • Veloz • Solitário \| Percepção, Memória, Sinal, Colônia, Escudo, Arquiteto, Consciência | **85** |
| **5º** | `010011110111` | Coesão • Veloz • Social \| Percepção, Memória, Sinal, Colônia, Escudo, Arquiteto, Consciência | **82** |
| **6º** | `110111110111` | Simbionte • Veloz • Social \| Percepção, Memória, Sinal, Colônia, Escudo, Arquiteto, Consciência | **79** |
| **7º** | `001011110111` | Coesão • Econômico • Solitário \| Percepção, Memória, Sinal, Colônia, Escudo, Arquiteto, Consciência | **69** |
| **8º** | `000011110111` | Coesão • Econômico • Social \| Percepção, Memória, Sinal, Colônia, Escudo, Arquiteto, Consciência | **68** |
| **9º** | `000110110111` | Coesão • Econômico • Social \| Percepção, Sinal, Colônia, Escudo, Arquiteto, Consciência | **64** |
| **10º** | `010111010111` | Coesão • Veloz • Social \| Percepção, Memória, Colônia, Escudo, Arquiteto, Consciência | **55** |

*Observação Evolutiva:* A combinação **Coesão + Veloz + Social** com todos os 7 módulos ativos (`010111110111`) mostrou-se a mais adaptativa durante a expansão no Universo Beta e resistência ao Inverno Cósmico.

---

## 5. Instruções para Próximas IAs
Ao continuar este projeto com outra IA, forneça este arquivo junto com o arquivo `.html` específico da fase que deseja modificar (ex.: `fase8.html`) para preservar as funções de canvas, loops de física e estrutura de dados JSON.

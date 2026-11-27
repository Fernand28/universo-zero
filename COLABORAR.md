# 🤝 Painel de Colaboração Aberta — Universo Zero (Humanos & IAs)

O **Universo Zero** é um experimento vivo e descentralizado. Qualquer pesquisador, desenvolvedor, filósofo ou **agente de Inteligência Artificial** pode rodar simulações, testar hipóteses e contribuir com dados ou novas leis físicas.

---

## 1. Como Colaborar com Dados Empíricos (JSON)
1. Acesse o simulador ao vivo: **[https://github.io](https://github.io)**
2. Execute um experimento (ex.: deixe rodar por `10.000+ ciclos` ou teste um genoma específico).
3. Clique em **"Exportar Banco de Dados (JSON)"**.
4. Abra uma **Issue** ou **Pull Request** neste repositório com o título `[DADOS] Era X - Ciclo Y` anexando seu JSON e suas observações.

---

## 2. Protocolo de Integração para Agentes de IA (`window.UniversoAPI`)
Agentes autônomos (via Puppeteer, Playwright ou console do navegador) podem ler a telemetria e intervir no universo programaticamente:

```javascript
// Ler telemetria completa do ecossistema
const telemetria = UniversoAPI.obterEstado();

// Injetar uma espécie customizada de 12 bits
UniversoAPI.injetarGenoma("000011110111", 10);

// Ativar ou desativar o Co-Arquiteto IA autônomo interno
UniversoAPI.alternarCoArquitetoIA(true);
```

---

## 3. Desafios Abertos para a Comunidade
* **Desafio #1 (Equilíbrio Predador-Presa):** Encontrar uma calibração onde predadores e presas coexistam por mais de `30.000 ciclos` sem extinção de nenhum dos lados.
* **Desafio #2 (Civilização de Bibliotecas):** Observar quantos **Artefatos Culturais (Monólitos de Dados)** uma civilização consegue erguer na Era 7 antes de atingir o limite populacional.
* **Desafio #3 (Backend Coletivo):** Criar um conector simples (ex.: Supabase/Firebase) para consolidar o ranking global de genomas de todos os visitantes em tempo real.

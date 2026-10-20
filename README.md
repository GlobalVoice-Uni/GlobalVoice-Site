# GlobalVoice — Landing Page

Este repositório contém o código-fonte da landing page oficial do **GlobalVoice**, uma aplicação desktop para tradução simultânea de voz em reuniões online.

O objetivo desta página é apresentar o produto, destacar seus recursos de privacidade e tradução em tempo real, e fornecer um ponto central para o download do instalador.

🌐 **Site no ar:** [https://globalvoice-uni.github.io/GlobalVoice-Site/](https://globalvoice-uni.github.io/GlobalVoice-Site/)

---

## Tecnologias Utilizadas

Este projeto foi construído de forma leve e estática, sem a necessidade de frameworks complexos:

*   **HTML5** — Estrutura semântica da página.
*   **CSS3** — Estilização, responsividade e animações.
*   **Google Fonts** — Tipografia moderna (Inter).
*   **GitHub Pages** — Hospedagem gratuita e automatizada.

## Estrutura do Repositório

```text
GlobalVoice-Desktop/
├── backend/               # Módulos de captura de áudio, VAD, ASR e Tradução
├── deploy/windows/        # Scripts de build, PyInstaller e Inno Setup
├── docs/                  # Documentação técnica, decisões e guias
├── experiments/           # Benchmarks de modelos e auditoria de runtime
├── frontend/              # Interface gráfica em PySide6 e controladores
├── requirements/          # Arquivos de lock e dependências
├── tests/                 # Testes unitários e de integração
├── README.md              # Este arquivo
├── roadmap.md             # Planejamento do PFC 2
└── run_tests.ps1          # Script para rodar a suíte de testes
````
## Estrutura do site
```
GlobalVoice-Site/
├── docs/
│   ├── index.html       # Página principal
│   ├── style.css        # Estilos visuais
│   └── assets/          # Ícones e imagens (favicon, etc.)
└── README.md            # Este arquivo

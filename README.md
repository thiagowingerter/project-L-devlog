<img src="docs/assets/L_icon.ico" align="left" width="120" alt="Lily Legacy Icon">
# 🎮 Project L (Narrative RPG)

An independent dark fantasy narrative RPG built with Python and the Ren'Py engine. This project applies professional software development discipline, agile tracking, and advanced Generative AI pipelines to streamline production and asset scaling.

---

## ⚙️ Technical Stack & Tools
- **Engine:** Ren'Py (Python 3)
- **AI Tooling:** ComfyUI, Stable Diffusion, OpenRouter API
- **Base Checkpoints:** Pony Diffusion V6 XL, AutismMix Confetti
- **Asset Sourcing & Fine-Tuning:** Civitai (Custom LoRAs, Embeddings)
- **Version Control & Docs:** Git/GitHub, Game Design Document (GDD)

---

📜 What's New: Devlog & Architecture

### v0.3 — May 2026 — AI Image Generation Pipeline & Hardware Optimization 🎨
*Resumo: Escalada na produção visual após upgrade de hardware dedicado. Transição de testes isolados para um pipeline estruturado de arte gerativa local para consistência da personagem Lily Regium.*

- **Modelos Fundacionais e Infraestrutura:** Adoção do **Pony Diffusion V6 XL** e **AutismMix Confetti** como checkpoints base para a direção de arte focada em estilização anime/2.5D. Refinamento de prompts e embeddings via Civitai para consistência de traço.
- **Treinamento e Progressão de LoRAs:** Treinamento inicial de LoRAs customizados para a personagem principal. Criação do diretório `docs/assets/lora_training_progression/` detalhando a evolução do design desde a ideação até a estabilização da identidade.
- **Work in Progress:** Início da estruturação de workflows de nós no ComfyUI voltados para a separação de sprites em camadas (LayerDiffusion), visando preparar os assets 2.5D para futura animação.

### v0.2 — March 2026 — LLM Integration & Dynamic Narrative Systems 🧠
*Resumo: Testes de conceito (POC) e implementação de APIs de modelos de linguagem para potencializar o comportamento de NPCs e a flexibilidade do roteiro.*

- **Integração de Backend:** Testes de conexão de APIs de modelos de linguagem (via OpenRouter) para geração dinâmica de respostas.
- **Engenharia de Prompt:** Estruturação de system prompts avançados com diretrizes rígidas de personalidade e contexto, garantindo que os personagens respondam de forma direta e contida na lore.

### v0.1 — January 2026 — Core Loop Architecture & GDD Foundation 🎮
*Resumo: Fundação da arquitetura orientada a eventos, setup da engine principal do jogo e documentação inicial de escopo.*

- **Game Design Document (GDD):** Documentação da Fase 1: mecânicas de core loop, sistemas de progressão e a base narrativa do projeto.
- **Arquitetura de Software:** Desenvolvimento de lógicas de ramificação condicional (branching narrative) e gerenciamento de variáveis de estado na engine Ren'Py.

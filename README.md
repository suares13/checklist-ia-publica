# ⚖️ Checklist de Auditoria Cidadã para IA Pública

> Artefato interativo de controlo social para avaliação de conformidade ético-técnica em sistemas algorítmicos governamentais.

[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://suares13.github.io/checklist-ia-publica/)
[![UNESCO](https://img.shields.io/badge/UNESCO-Ética%20em%20IA%20(2021)-0077b5?style=for-the-badge)](https://unesdoc.unesco.org/ark:/48223/pf0000380455)
[![ISO/IEC](https://img.shields.io/badge/Padrões-ISO%2FIEC%2042001-green?style=for-the-badge)](https://www.iso.org/standard/81230.html)
[![Licença: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

---

## 🌐 Acesso Online

O artefato encontra-se publicado e disponível para auditoria pública no seguinte endereço:
👉 **[https://suares13.github.io/checklist-ia-publica/](https://suares13.github.io/checklist-ia-publica/)**

---

## 📌 Sobre o Projeto

A expansão de sistemas de Inteligência Artificial e automação decisória no setor público (como triagens previdenciárias, concessão de benefícios sociais e pontuações preditivas) impõe a necessidade urgente de mecanismos práticos de prestação de contas (*accountability*).

Este projeto materializa um artefato desenvolvido sob a metodologia **Design Science Research (DSR)**, transpondo diretrizes normativas internacionais para um instrumento interativo de fiscalização cidadã e verificação algorítmica.

---

## 🧭 Dimensões Avaliadas

O checklist é composto por **15 critérios objetivos** distribuídos em 5 eixos fundamentais estabelecidos na **Recomendação sobre a Ética da IA da UNESCO (2021)** e normas **ABNT NBR ISO/IEC 42001** e **22989**:

| Dimensão | Foco de Avaliação |
| :--- | :--- |
| 🔍 **Transparência** | Publicação das regras de decisão, clareza sobre o funcionamento do modelo e canais de atendimento específicos. |
| 💡 **Explicabilidade** | Capacidade de o sistema fundamentar recusas/aprovações em linguagem simples e fornecer caminho claro para recurso. |
| ⚖️ **Justiça e Viés** | Mitigação de preconceitos históricos, equidade no atendimento a trabalhadores rurais/informais e canais de denúncia de discriminação. |
| 👤 **Supervisão Humana** | Garantia de *human-in-the-loop*, suporte humano acessível e identificação do órgão público responsável. |
| 📱 **Inclusão Digital** | Desempenho em dispositivos básicos/redes móveis, acessibilidade (WCAG) e garantia obrigatória de atendimento presencial analógico. |

---

## 📊 Mecanismo de Pontuação e Conformidade

Cada uma das 15 questões admite três níveis de ponderação:
* **Sim** (+2 pontos)
* **Parcial** (+1 ponto)
* **Não** (+0 pontos)

A pontuação total é normalizada em uma escala de **0 a 100**, classificando a tecnologia auditada em faixas visuais de integridade:

* 🟢 **70 a 100:** Conforme (Sistema alinhado às diretrizes mínimas de governança)
* 🟡 **40 a 69:** Parcialmente Conforme / Alerta (Existência de vulnerabilidades processuais mitigáveis)
* 🔴 **0 a 39:** Falha Ética Crítica (Opacidade extrema, ausência de explicabilidade ou exclusão sistemática)

---

## 🛠️ Tecnologias Utilizadas

O artefato foi concebido com arquitetura de **baixo acoplamento**, sem dependências externas, bibliotecas de terceiros ou servidores intermediários, assegurando máxima portabilidade e auditoria direta do código:

* **HTML5 Semântico:** Estruturação acessível e compatível com leitores de ecrã.
* **CSS3 Moderno:** Design responsivo (*mobile-first*), contrastes calibrados e controlos táteis em pílula (*pill buttons*).
* **JavaScript Vanilla:** Motor reativo local para cálculo de conformidade em tempo de execução sem armazenamento ou extração de dados do utilizador.

---

## 💻 Como Executar Localmente

Não é necessário instalar nenhum ambiente ou gestor de pacotes:

1. Clone o repositório:
   ```bash
   git clone [https://github.com/suares13/checklist-ia-publica.git](https://github.com/suares13/checklist-ia-publica.git)
2. Aceda ao diretório:
   ```bash
   cd checklist-ia-publica
3. Abra o ficheiro index.html em qualquer navegador web.

## 🏛️ Contexto Académico
Artefato desenvolvido no âmbito do programa de Iniciação Científica (PIBIC/ICETI) em Engenharia de Software, com foco em governança de sistemas sociotécnicos, auditoria de equidade e direitos fundamentais na administração pública.
---

### Como adicionar no GitHub:
1. No repositório `checklist-ia-publica`, clique em **Add file > Create new file**[cite: 4].
2. No nome do ficheiro, escreva exatamente **`README.md`**.
3. Cole o código acima.
4. Clique em **Commit changes...** e confirme no botão verde para guardar.


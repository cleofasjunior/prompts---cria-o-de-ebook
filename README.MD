# 📚 Pipeline de Criação de Ebook com GenAI

> Um estudo prático de **Engenharia de Prompt** aplicado à produção de conteúdo editorial.

Este repositório documenta o fluxo de trabalho (workflow) desenvolvido para criar um ebook completo utilizando Inteligência Artificial Generativa. O objetivo não é apenas o produto final, mas a estruturação de prompts reutilizáveis e escaláveis.

## 🛠️ Tecnologias & Ferramentas
* **LLM (Texto):** ChatGPT (GPT-4) / Claude 3.
* **GenAI (Imagem):** MidJourney v6.
* **Metodologia:** Chain-of-Thought (CoT), Few-Shot Prompting e Criação de Personas.

## 🔄 O Workflow (Pipeline)

```mermaid
graph LR
    A[Ideação & Brainstorm] -->|Prompt 01| B(Estrutura de Tópicos)
    B -->|Prompt 02| C{Refinamento Editorial}
    C -->|Prompt 03| D[Escrita de Capítulos]
    D -->|Revisão| E[Ebook Final]
    C -->|Prompt 04| F[Geração de Capa - MidJourney]
    F --> E

🧠 Estratégia de Engenharia de Prompt

1. Utilizei a técnica de Prompt Chaining (Encadeamento), onde a saída de uma etapa serve como contexto para a próxima, garantindo consistência narrativa.

2. Definição de Persona: A IA foi instruída a atuar como um Editor Sênior de Tecnologia.

3. Restrições (Constraints): Definição clara de tom de voz, público-alvo e formatação (Markdown).

4. Iteração: Refinamento dos prompts baseado nas alucinações ou respostas genéricas iniciais.


Desenvolvido por Cleófas Júnior - Explorando as fronteiras da IA Generativa.
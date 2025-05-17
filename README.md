# Meu Plano IA: Seu Assistente Inteligente de Estudos

![Logo do Meu Plano IA](assets/meu_plano_ia_logo.png)

> Seu assistente inteligente para criar planos de estudo personalizados que se adaptam ao seu ritmo e objetivos, otimizando seu tempo e te guiando rumo ao sucesso no aprendizado.

## 🏆 Premiação Imersão IA 2025 - Alura & Google

Este projeto foi desenvolvido para participar da Premiação Imersão IA 2025, utilizando os conhecimentos adquiridos nas aulas sobre IA generativa e construção de agentes.

## 💡 Sobre o Projeto

O "Meu Plano IA" é uma ferramenta que utiliza a inteligência artificial do Google Gemini para gerar planos de estudo personalizados. Ao fornecer informações como seu objetivo de aprendizado, tempo disponível, nível de conhecimento e recursos preferenciais, o sistema cria um roteiro completo e adaptado às suas necessidades.

## ✨ Funcionalidades Principais

* **Geração de Planos Personalizados:** Crie planos de estudo sob medida com base em seus objetivos e disponibilidade.
* **Planejamento de Módulos:** O Gemini define módulos relevantes e sequenciais para o seu aprendizado.
* **Detalhamento Semanal:** Cada módulo é dividido em tópicos semanais com uma estimativa de tempo de estudo.
* **Sugestão de Recursos:** (Atualmente placeholders) Links de recursos relevantes são incluídos para cada tópico (melhoria futura).
* **Interface Amigável:** Uma interface web intuitiva construída com Gradio facilita a interação.

## 🚀 Como Utilizar

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/SmyrnaSc/Meu-Plano-IA.git](https://github.com/SmyrnaSc/Meu-Plano-IA.git)
    cd Meu-Plano-IA
    ```

2.  **Instale as bibliotecas necessárias:**
    ```bash
    pip install -r requirements.txt
    ```
    Certifique-se de ter o arquivo `requirements.txt` na raiz do seu repositório com as dependências: `google-generativeai` e `gradio` (e quaisquer outras que você utilize).

3.  **Execute a aplicação:**
    ```bash
    python src/app.py
    ```
    Assumindo que o seu arquivo principal que inicia o Gradio está dentro da pasta `src` e se chama `app.py`. Se o nome do seu arquivo principal for diferente, substitua `src/app.py` pelo caminho e nome corretos.

4.  **Acesse a interface:** Após executar o comando acima, o Gradio geralmente exibe um link no terminal (geralmente começando com `http://` e seguido por um endereço IP e uma porta, como `http://localhost:7860` ou um endereço público se estiver rodando no Colab e compartilhado). Abra este link no seu navegador.

5.  **Preencha os campos:** Na interface web que será aberta, informe seu objetivo de aprendizado, horas semanais disponíveis, duração total desejada, seu nível de conhecimento e recursos preferenciais.

6.  **Clique em "Gerar Plano":** Após preencher os campos, clique no botão para gerar o seu plano de estudos personalizado. O plano será exibido na interface.

## ⚙️ Tecnologias Utilizadas

* **Google Gemini:** Para a geração inteligente do plano de estudos.
* **Gradio:** Para criar a interface web interativa.
* **Python:** Linguagem de programação principal.

## 🎯 Critérios de Avaliação da Premiação

Este projeto busca atender aos critérios de avaliação da Premiação Imersão IA 2025 da seguinte forma:

* **Utilidade do Projeto:** Oferece uma solução prática e personalizada para o planejamento de estudos, auxiliando estudantes e aprendizes a se organizarem de forma eficaz.
* **Criatividade:** A abordagem de utilizar o Gemini para criar um plano de estudos dinâmico e adaptável, com a divisão em agentes (implícita na lógica), demonstra uma aplicação criativa da IA generativa.
* **Eficácia:** O projeto gera um plano de estudos detalhado com módulos, tópicos semanais e estimativa de tempo, proporcionando um roteiro claro para o aprendizado. A interface Gradio torna a interação simples e direta.
* **Apresentação:** A interface web amigável e este README bem estruturado visam apresentar o projeto de forma clara e profissional.

## 📚 Documentação Adicional

Para uma documentação mais detalhada sobre a arquitetura interna e o fluxo de dados, confira a [Wiki do Projeto](link_para_a_wiki).
---

Feito com ❤️ por Smyrna

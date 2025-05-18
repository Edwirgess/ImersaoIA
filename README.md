# Agente de Turismo para João Pessoa (Paraíba) com Google Gemini e ADK

Este projeto consiste em um agente de turismo interativo para a cidade de João Pessoa, localizada no estado da Paraíba, Brasil.
O agente é construído utilizando o Google Agents Development Kit (ADK) e o modelo de linguagem Gemini da Google AI. 
Ele utiliza a ferramenta de busca do Google para fornecer informações relevantes aos usuários sobre pontos turísticos, 
restaurantes, hotéis, eventos e outras informações úteis para turistas na região.

## Funcionalidades

* **Interação via Chatbot:** Permite que os usuários façam perguntas em linguagem natural sobre João Pessoa.
* **Busca de Informações:** Utiliza a ferramenta de busca do Google para obter informações atualizadas e relevantes.
* **Agente Especializado:** Um agente de turismo configurado para entender e responder perguntas específicas sobre João Pessoa.
* **Consideração da Data Atual:** O agente leva em consideração a data atual para fornecer informações mais recentes sobre eventos e a situação local.
* **Formatação da Resposta:** As respostas são formatadas em Markdown para uma melhor leitura no ambiente do Google Colab e em outras plataformas.

## Como Usar no Google Colab

2.  **Instalação da Biblioteca ADK:**
    * Abra um novo notebook no Google Colab.
    * Execute a seguinte célula para instalar a biblioteca `google-adk`:
        ```python
        !pip install -q google-adk
        ```

3.  **Copie e Cole as Células de Código:**
    * Copie e cole as células de código fornecidas neste projeto no seu notebook do Colab, mantendo a ordem das células.

4.  **Configure a API Key:**
    * Certifique-se de que sua API Key do Google Gemini esteja corretamente configurada no `userdata` do Colab. Você pode fazer isso seguindo as instruções do Colab para armazenar segredos do usuário.

5.  **Execute as Células:**
    * Execute as células de código em ordem, de cima para baixo.

6.  **Interaja com o Chatbot:**
    * A saída da última célula iniciará o loop de conversa. Você verá a mensagem de boas-vindas.
    * Digite suas perguntas sobre João Pessoa no prompt ` >  ` e pressione Enter.
    * O agente tentará responder à sua pergunta usando a busca do Google.
    * Para encerrar a conversa, digite `sair` e pressione Enter.

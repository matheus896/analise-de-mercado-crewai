# Interface Streamlit para CrewAI

Este aplicativo Streamlit utiliza a biblioteca CrewAI para simular um processo de lançamento de produto, com agentes de IA colaborando para analisar o mercado, a tecnologia e o modelo de negócios de um produto.

### Pré-requisitos

Antes de prosseguir, certifique-se de ter o seguinte instalado em seu sistema:

- Python (versão 3.10 ou superior)
- pip (instalador de pacotes Python)

### Passos para Instalação

1. **Clone o Repositório:**
   
   Clone o repositório do projeto para sua máquina local usando o Git, executando o seguinte comando em seu terminal ou prompt de comando:

   ```
   git clone https://github.com/AbubakrChan/crewai-business-product-launch.git
   ```

2. **Navegue até o Diretório do Projeto:**
   
   Altere seu diretório de trabalho para o diretório do projeto usando o seguinte comando:

   ```
   cd crewai-business-product-launch
   ```

3. **Instale as Dependências:**
   
   Instale as dependências Python necessárias listadas no arquivo `requirements.txt` usando o pip. Execute o seguinte comando:

   ```
   pip install -r requirements.txt
   ```
4.  **Configure a Chave da API OpenAI ou a que preferir:**

   Para utilizar a API OpenAI dentro do aplicativo, certifique-se de ter uma chave de API OpenAI. Defina sua chave de API OpenAI como uma variável de ambiente chamada `OPENAI_API_KEY` em seu sistema.
   
   Crie um arquivo `.env` no diretório do projeto, caso ele não exista. Adicione a seguinte linha ao arquivo `.env`, substituindo `sk-xxxxxxxxxxxxxxxxx` pela sua chave de API OpenAI real:
   
   ```
   OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxx
   ```
   
### Executando o Aplicativo Streamlit

Após concluir as etapas de configuração, você pode executar o aplicativo Streamlit usando o seguinte comando:

```
streamlit run main.py
```

Este comando iniciará o aplicativo, e você deverá ver a URL onde o aplicativo está sendo executado. Normalmente, será algo como `http://localhost:8501`.

### Uso

- Ao executar o aplicativo Streamlit, você será apresentado à interface do CrewAI Business Product Launch.
- O aplicativo simula um processo de lançamento de produto, com os seguintes agentes de IA:
    - **Analista de Pesquisa de Mercado:** Analisa a demanda de mercado e sugere estratégias de marketing.
    - **Especialista em Tecnologia:** Avalia a viabilidade tecnológica e os requisitos para a produção do produto.
    - **Consultor de Desenvolvimento de Negócios:** Avalia o modelo de negócios, focando na escalabilidade e nas fontes de receita.

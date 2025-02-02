# Extrator de Dados do Tesouro Direto

Este projeto utiliza Python e Playwright para extrair e processar informações sobre os títulos do Tesouro Direto diretamente do site oficial.

## 📌 Funcionalidades
- Acessa a página do Tesouro Direto.
- Coleta informações sobre os títulos disponíveis.
- Processa os dados extraídos para gerar um DataFrame organizado.
- Exibe os dados de forma estruturada.

## 🛠 Tecnologias Utilizadas
- Python 3+
- Playwright
- Pandas
- Asyncio
- Nest Asyncio
- Expressões Regulares (Regex)

## 🔧 Instalação e Configuração

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Crie e ative um ambiente virtual (opcional, mas recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate  # Windows
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Instale o Playwright e os navegadores necessários:
   ```bash
   playwright install
   ```

## 🚀 Como Executar
Execute o script Python:
```bash
python script.py
```
Ou, se estiver em um Jupyter Notebook:
```python
nest_asyncio.apply()
asyncio.get_event_loop().run_until_complete(main())
```

## 📊 Estrutura dos Dados
O script extrai e organiza os seguintes campos:
- **Título**: Nome do título com o ano de vencimento.
- **Rentabilidade**: Tipo de rentabilidade do título.
- **Investimento Mínimo**: Valor mínimo para compra.
- **Preço Unitário**: Preço do título.
- **Data de Vencimento**: Data final do título.
- **Tipo**: Tipo de título (Prefixado, IPCA+ etc.).

## ⚠️ Observações
- O site do Tesouro Direto pode mudar sua estrutura, exigindo ajustes no código.
- O Playwright precisa estar instalado corretamente para funcionar.



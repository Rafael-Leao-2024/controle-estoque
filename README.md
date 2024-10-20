# Controle de Estoque - CRUD com Python e Tkinter

Este é um sistema simples de controle de estoque desenvolvido em Python utilizando a biblioteca Tkinter para a interface gráfica e integrando um banco de dados MySQL com o PyODBC para gerenciar os insumos de estoque.

## Funcionalidades

- **Adicionar Insumo**: Adiciona um novo insumo ao banco de dados.
- **Procurar Insumo**: Busca um insumo pelo nome e exibe suas informações.
- **Deletar Insumo**: Remove um insumo específico do banco de dados.
- **Usar Insumo**: Atualiza a quantidade de um insumo ao registrar o uso de uma parte dele.

## Pré-requisitos

Antes de executar o projeto, é necessário garantir que você tenha instalado:

- Python 3.x
- Biblioteca `Tkinter`
- Biblioteca `pyodbc`
- Banco de dados MySQL
- Driver MySQL ODBC 9.1 ANSI Driver (ou a versão mais recente)

## Configuração do Banco de Dados

1. Certifique-se de ter um banco de dados MySQL rodando localmente com as seguintes credenciais:
    - Host: `localhost`
    - Porta: `3306`
    - Nome do banco de dados: `estoquementoria`
    - Usuário: `root`
    - Senha: `PASSWORD`

2. No banco de dados MySQL, crie a tabela `Insumos` com a seguinte estrutura:

```sql
CREATE TABLE Insumos (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome_insumo VARCHAR(255) NOT NULL,
    data_validade DATE NOT NULL,
    lote VARCHAR(255) NOT NULL,
    qtde DECIMAL(10, 2) NOT NULL
);
```


# Executando o Projeto

Clone o repositório do projeto:
```bash
Copiar código
git clone https://github.com/seu-usuario/seu-repositorio.git

```

# Instale as dependências necessárias:

```bash
Copiar código
pip install pyodbc
```

# Execute o script Python:

```bash
Copiar código
python controle_estoque.py
````
# Interface Gráfica
A interface gráfica foi desenvolvida usando a biblioteca Tkinter. Você pode interagir com o sistema utilizando botões para adicionar, deletar, procurar e usar insumos, bem como visualizar as informações no campo de texto.

Screenshot
Adicione uma imagem da interface aqui.

Estrutura do Projeto
controle_estoque.py: Script principal contendo toda a lógica do sistema.
background.png: Imagem de fundo da interface gráfica.
imgX.png: Imagens dos botões.
Autor
Seu Nome - Seu GitHub
Licença
Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.

css
Copiar código

Agora tudo está junto em um único bloco de texto! Basta copiar e ajustar conforme necessário.






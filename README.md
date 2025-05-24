# Consulta de CNPJ via API CNPJa

Este script em Python realiza consultas de dados de empresas brasileiras através do número do **CNPJ** utilizando a API pública da [CNPJa](https://cnpja.com.br/).

---

## Funcionalidades

- Solicita ao usuário o número do CNPJ para consulta.
- Valida o número de dígitos (deve conter 14 caracteres).
- Consulta a API CNPJa com o CNPJ informado.
- Exibe informações básicas da empresa, como nome, CNPJ e natureza jurídica.
- Permite realizar múltiplas consultas em sequência.

---

## Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
nstale as dependências (requer requests):

bash
Copiar
Editar
pip install requests
Execute o script:

bash
Copiar
Editar
python nome_do_arquivo.py
Digite o número do CNPJ (14 dígitos, apenas números) quando solicitado.

Veja os dados da empresa retornados pela API.

Escolha se deseja realizar uma nova consulta ou sair.

Exemplo de uso
markdown
Copiar
Editar
Digite o número do CNPJ para a consulta: 12345678000195
==> CNPJ Encontrado <==
Nome: Empresa Exemplo Ltda
CNPJ: 12345678000195
Natureza legal: Sociedade Empresária Limitada
---------------------------------
Deseja realizar uma nova consulta ?
1. Sim
2. Sair
Requisitos
Python 3.x

Biblioteca requests (instalável via pip)


# chatgptcli

[![License: GNU](https://img.shields.io/github/license/MaxwelMazur/chatgptcli?style=for-the-badge&logo=gnu&color=ee999f&logoColor=ee999f&labelColor=302D41)](https://www.gnu.org/licenses/gpl-3.0.en.html)
[![CI](https://img.shields.io/badge/CI-Passing-gree.svg?style=for-the-badge&logo=github)](https://github.com/MaxwelMazur/chatgptcli/actions/workflows/go.yml)

O chatgtpcli é uma ferramenta CLI (interface de linha de comando) projetada para ser uma inteligência artificial auxiliar dentro do terminal. Ele é altamente flexível e ainda está no início de seu desenvolvimento. 

### Exemplo de Como Consumir a API na sua Aplicação Local - Divirta-se!

Aqui está um exemplo de como você pode facilmente consumir a API na sua aplicação local:
```bash
curl --location --request POST 'localhost:5001/chatgpt' \
--header 'token: <your-token>' \
--header 'Content-Type: application/json' \
--data-raw '{
    "Question": "<your-question>"
}'
```

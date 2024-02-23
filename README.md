# QR Code Scanner e Exportador para Excel

Este é um simples script em Python que utiliza a biblioteca `opencv` para ler QR codes da webcam e a biblioteca `openpyxl` para exportar os dados dos QR codes para um arquivo Excel.

## Pré-requisitos

- Python 3 instalado
- Pacotes Python necessários: `opencv-python`, `pyzbar`, `openpyxl`

Você pode instalar os pacotes necessários executando o seguinte comando:

```
pip install opencv-python pyzbar openpyxl
```

## Como usar

1. Execute o script `qr_code_reader.py`.
2. Uma janela de visualização da webcam será aberta.
3. Aponte a webcam para um QR code.
4. O script irá detectar o QR code, exibir seu valor no console e exportá-lo para um arquivo Excel chamado `qr_code_data.xlsx`.
5. Repita os passos 3 e 4 para ler e exportar mais QR codes.
6. Pressione a tecla 'q' para sair do script.

## Arquivos

- `qr_code_reader.py`: O script principal que realiza a leitura dos QR codes e exporta os dados para um arquivo Excel.
- `qr_code_data.xlsx`: O arquivo Excel onde os dados dos QR codes são exportados.

## Contribuindo

Sinta-se à vontade para contribuir com melhorias ou correções para este script. Abra um pull request ou crie uma issue para discutir suas ideias.

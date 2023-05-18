# Programa para imprimir caracteres ASCII imprimíveis de um arquivo binário
Este programa em C lê um arquivo binário e imprime na tela os caracteres ASCII imprimíveis encontrados no arquivo.

### Como usar
Certifique-se de ter um compilador C instalado em seu sistema.

Clone ou faça o download deste repositório.

Abra um terminal e navegue até o diretório onde o arquivo main.c está localizado.

Compile o código usando o comando:

### bash
```bash
# Copy code
gcc -o ascii-pr1nt3r ascii-pr1nt3r.c
```
Execute o programa fornecendo o caminho para o arquivo binário que você deseja analisar. Por exemplo:

### bash
```bash
# Copy code
./aascii-pr1nt3r path/to/file.bin
```
Certifique-se de substituir path/to/file.bin pelo caminho real do arquivo que você deseja analisar.

O programa exibirá na tela os caracteres ASCII imprimíveis encontrados no arquivo.

### Observações
Este programa assume que o arquivo binário fornecido contém dados codificados em ASCII e que os caracteres estão representados em um único byte.

Os caracteres ASCII imprimíveis têm valores entre 20 e 126 na tabela ASCII.

O programa não trata erros de arquivo, como se o arquivo não existir ou não poder ser aberto. É recomendável adicionar verificações de erro para lidar com essas situações em um código de produção.

Certifique-se de que o arquivo binário fornecido seja adequado para este programa. Arquivos que não contêm caracteres ASCII imprimíveis podem não produzir resultados significativos.

### Licença
Este projeto está licenciado sob a MIT License.

# Pense em Python

Conversão dos fontes em markdown para PDF. Pandoc somente consegue converter multiplos arquivos de uma vez em ambiente unix, ou seja, não há como executar em ambiente Windows.

```
PensePython2e/docs$ pandoc *.md > PensePython2e.html

PensePython2e/docs$ pandoc PensePython2e.html -o PensePython2e.pdf
```

# Extração de Texto de PDF e Geração de Nuvem de Palavras

Este script em Python extrai texto de um arquivo PDF e gera uma nuvem de palavras para visualizar as palavras mais frequentes.

## Pré-requisitos

Antes de executar o script, certifique-se de ter as bibliotecas Python necessárias instaladas:

```bash
pip install nltk wordcloud PyPDF2
```

## Uso

1. Clone o repositório:

```bash
git clone https://github.com/seu-nome-de-usuario/seu-repositorio.git
cd seu-repositorio
```

2. Coloque o arquivo PDF (`Template_TCC (1).pdf`) que você deseja analisar na raiz do projeto.

3. Execute o script:

```bash
python script.py
```

A nuvem de palavras gerada será exibida, mostrando as palavras mais comuns no PDF.

## Explicação

O script realiza as seguintes etapas:

- Abre o arquivo PDF e extrai texto de cada página.
- Realiza a limpeza de texto, convertendo o texto para minúsculas, removendo pontuações e eliminando stopwords (palavras comuns).
- Usa a biblioteca WordCloud para criar uma visualização de nuvem de palavras.
- Exibe a nuvem de palavras gerada usando o Matplotlib.

## Personalização

Sinta-se à vontade para modificar o script ou personalizar os parâmetros da WordCloud conforme suas necessidades.

## Dependências

- [NLTK](https://www.nltk.org/): Kit de ferramentas de linguagem natural para tarefas de processamento de texto.
- [WordCloud](https://github.com/amueller/word_cloud): Biblioteca Python para criar nuvens de palavras.
- [PyPDF2](https://pythonhosted.org/PyPDF2/): Biblioteca para ler arquivos PDF.
- [Matplotlib](https://matplotlib.org/): Biblioteca para criar visualizações estáticas, animadas e interativas em Python.

## Licença

Este projeto é licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para obter detalhes.

## Agradecimentos

- Contribuidores da biblioteca WordCloud
- Contribuidores da biblioteca NLTK
- Contribuidores da biblioteca PyPDF2
- Contribuidores da biblioteca Matplotlib

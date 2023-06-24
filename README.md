# Script usado no Artigo "ANÁLISE QUALITATIVA DO RELATÓRIO FINAL DA AVALIAÇÃO DO SISTEMA NACIONAL DE PÓS-GRADUAÇÃO EM ADMINISTRAÇÃO PÚBLICA NO BRASIL: UMA ABORDAGEM UTILIZANDO O SOFTWARE IRAMUTEQ"


>  Scritp e dados usados para gerar o banco de dados para ser processador pelo Iramuteq


No intuito de facilitar a geração do banco de dados/corpus textual que será processado pelo Software [Iramuteq](http://www.iramuteq.org/) , foi usado o Python.

Este script é um processador de texto que funciona com arquivos de texto em formato PDF, DOC/DOCX e TXT, com o intuito de uniformizar e simplificar o texto para análise posterior. O script faz uso de várias bibliotecas Python para ler e manipular o texto, como PyPDF2, unidecode, docx e chardet. Ele inclui funções para extrair texto de diferentes formatos de arquivo, detectar codificação de caracteres, escrever em um arquivo de saída e manipular nomes de arquivo. Além disso, existem funções auxiliares para converter arquivos PDF em DOCX e montar cabeçalhos baseados nos nomes dos arquivos.

Na segunda parte do script, há um conjunto de funções de processamento de texto que realizam várias operações, incluindo a remoção de quebras de linha e tabulações, a reordenação de enclises para próclises, a substituição de termos definidos em um dicionário predefinido, o tratamento de locuções substantivas, a substituição de hífens, a remoção de caracteres e expressões específicas e a eliminação de artigos. No final, o script combina todas essas funções de processamento de texto em uma única função que é aplicada a todos os arquivos na pasta especificada, resultando em um corpus de texto unificado e simplificado que é escrito em um arquivo de saída chamado 'corpus_textual.txt'.

Para reproduzir o resultado obtido é necessário instalar as bibliotecas de "requirements.txt"
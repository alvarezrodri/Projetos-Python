# Consolidação de Arquivos em Python

## Objetivo: 

O objetivo deste script é consolidar diversos arquivos Excel que contêm dados segmentados por 
segmento (governo, grandes empresas, médias empresas, pequenas empresas, vendas online) e por
país (Alemanha, Canadá, Chile, EUA, França). Esses dados são centralizados em um único arquivo 
Excel para facilitar a análise e a manipulação de grandes volumes de dados.

## Estrutura do Projeto:
O projeto está organizado da seguinte forma:

Linguagem Utilizada: Python
Ferramenta: Jupyter Notebook
Bibliotecas Usadas:
pandas: Para leitura e manipulação de dados tabulares (Excel).
os: Para lidar com diretórios e arquivos do sistema operacional.
datetime: Para trabalhar com datas.

## Vantagens do Processo:
- Automatização: Elimina a necessidade de abrir manualmente cada arquivo Excel e copiar os dados, o que economiza tempo e reduz erros humanos.
- Flexibilidade: O script pode ser facilmente ajustado para incluir novos segmentos ou países, bastando adicionar mais arquivos ao diretório.
- Organização: Ao consolidar todas as informações em um único arquivo, o processo de análise e geração de relatórios torna-se mais simples e rápido.

## Recomendações Finais:
- Verificação de Padrão dos Arquivos: Certifique-se de que todos os arquivos Excel sigam o mesmo padrão de colunas e nome de arquivo para que o processo funcione corretamente.
- Escalabilidade: Este script pode ser modificado para incluir mais categorias de dados, dependendo das futuras necessidades da empresa.

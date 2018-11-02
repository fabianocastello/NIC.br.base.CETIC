# NIC.br.base.CETIC

# *Base de dados unificada da pesquisa CETIC Domicilios 2015+16+17*

*DISCLAIMER* Este trabalho é uma iniciativa pessoal e visa compartilhar informação pronta que outras pessoas teriam que investir tempo e acabariam reinventado a roda. Não posso, no entanto, assegurar que tudo está correto e portanto não dou nenhuma garantia sobre isso. Estando no github, assumo que de forma colaborativa podemos melhorar a informação. NIC.BR, CETIC, FEA, USP, ou meus empregadores NÃO TEM NENHUMA responsabilidade sobre os dados. Use por sua conta e risco.

O trabalho de conclusão da matéria EAD5754 - Análise Preditiva de Dados (FEA/USP, Profs. Geraldo Vidal e Cesar Souza), prevê análise da pesquisa CETIC (https://cetic.br/microdados/).


As bases são disponibilizadas por ano, com seus respectivos dicionários de dados. Este repositório reflete o trabalho feito para juntar as três bases e facilitar análises comparativas ano a ano. Pode ser usado no R, Python, SQL, PowerBI, Qlik, Tableau, etc.

# Arquivos

* Readme.md (este arquivo)
* O código em R (em R Markdown, Projeto EAD5754 1.TRANSF v4 (UTF8).Rmd)
* Código R executado (Knitr, Projeto_EAD5754_1.TRANSF_v4__UTF8_.pdf)
* Dicionários de dados 2015+16+17 e conciliação (em Excel)
* Microdados 2015+16+17 DOMICILIOS (em CSV)
* Microdados 2015+16+17 INDIVIDUOS (em CSV)
* BASE CONSOLIDADA domicilios
* BASE CONSOLIDADA individuos


# Principais atividades realizadas

1. Conciliação dos dicionários de dados dos três anos, no sentido de identificar os campos comuns às três pesquisas 
2. Eliminação de campos que não aprecem nos três anos
3. Ajuste do nome dos campos de classificação por faixa de renda
4. Ajuste da codificação de região (houve mudança em 2017 na codificação, não apenas no nome)
5. Consolidação de uma base única para os três anos de domicílios
6. Consolidação de uma base única para os três anos de indivíduos

# Mais informações

Sobre as informações da pesquisa em si, como por exemplo objetivos, áreas de investigação, metodologia, etc. consultar o site do NIC.br no endereço https://cetic.br/pesquisa/domicilios/

Este trabalho foi feito com base nos microdados com o seguinteversionamento (2015, 16 e 17)

Domicílios, 1.0, 1.0. 1.1
Indivíduos, 1.0, 1.0. 1.1

# Contato

www.fcastell.net/bc
fabianocastello@gmail.com
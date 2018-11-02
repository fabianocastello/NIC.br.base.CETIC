# NIC.br.base.CETIC

# *Base de dados unificada da pesquisa CETIC Domicilios 2015+16+17*

*DISCLAIMER* Este trabalho � uma iniciativa pessoal e visa compartilhar informa��o pronta que outras pessoas teriam que investir tempo e acabariam reinventado a roda. N�o posso, no entanto, assegurar que tudo est� correto e portanto n�o dou nenhuma garantia sobre isso. Estando no github, assumo que de forma colaborativa podemos melhorar a informa��o. NIC.BR, CETIC, FEA, USP, ou meus empregadores N�O TEM NENHUMA responsabilidade sobre os dados. Use por sua conta e risco.

O trabalho de conclus�o da mat�ria EAD5754 - An�lise Preditiva de Dados (FEA/USP, Profs. Geraldo Vidal e Cesar Souza), prev� an�lise da pesquisa CETIC (https://cetic.br/microdados/).


As bases s�o disponibilizadas por ano, com seus respectivos dicion�rios de dados. Este reposit�rio reflete o trabalho feito para juntar as tr�s bases e facilitar an�lises comparativas ano a ano. Pode ser usado no R, Python, SQL, PowerBI, Qlik, Tableau, etc.

# Arquivos

* Readme.md (este arquivo)
* O c�digo em R (em R Markdown, Projeto EAD5754 1.TRANSF v4 (UTF8).Rmd)
* C�digo R executado (Knitr, Projeto_EAD5754_1.TRANSF_v4__UTF8_.pdf)
* Dicion�rios de dados 2015+16+17 e concilia��o (em Excel)
* Microdados 2015+16+17 DOMICILIOS (em CSV)
* Microdados 2015+16+17 INDIVIDUOS (em CSV)
* BASE CONSOLIDADA domicilios
* BASE CONSOLIDADA individuos


# Principais atividades realizadas

1. Concilia��o dos dicion�rios de dados dos tr�s anos, no sentido de identificar os campos comuns �s tr�s pesquisas 
2. Elimina��o de campos que n�o aprecem nos tr�s anos
3. Ajuste do nome dos campos de classifica��o por faixa de renda
4. Ajuste da codifica��o de regi�o (houve mudan�a em 2017 na codifica��o, n�o apenas no nome)
5. Consolida��o de uma base �nica para os tr�s anos de domic�lios
6. Consolida��o de uma base �nica para os tr�s anos de indiv�duos

# Mais informa��es

Sobre as informa��es da pesquisa em si, como por exemplo objetivos, �reas de investiga��o, metodologia, etc. consultar o site do NIC.br no endere�o https://cetic.br/pesquisa/domicilios/

Este trabalho foi feito com base nos microdados com o seguinteversionamento (2015, 16 e 17)

Domic�lios, 1.0, 1.0. 1.1
Indiv�duos, 1.0, 1.0. 1.1

# Contato

www.fcastell.net/bc
fabianocastello@gmail.com
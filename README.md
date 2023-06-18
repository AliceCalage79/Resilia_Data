# Resilia_Data
![Alt text](image.png)

# Índice 

* [Título e Imagem de capa](#Título-e-Imagem-de-capa)
* [Índice](#índice)
* [Descrição do Projeto](#descrição-do-projeto)
* [Funcionalidades](#funcionalidades)
* [Tecnologias utilizadas](#tecnologias-utilizadas)
* [Pessoas Desenvolvedoras do Projeto](#pessoas-desenvolvedoras)
* [Conclusão](#conclusão)

# Descrição do Projeto

Projeto desenvolvido com objetivo de modelar um banco de dados para o sistema ResiliaData, sistema criado de forma fictícia com
a finalidade de dar um tema para o projeto indivídual do modulo 03 do curso de Analise de Dados da escola Resília
O sistema irá auxiliar na avaliação de quais são as tecnologias que as empresas parceiras estão utilizando e quem são seus colaboradores;
Existe um  cadastro de empresas parceiras, cadastro de tecnologias com a opção de selecionar a área (webdev, dados, marketing, etc.), 
uma tabela para registrar quais tecnologias as empresas estão utilizando e uma tabela para cadastro de colaboradores.

# Funcionalidades

A modelagem possui oito entidades:
* empresa;
* empresa_area;
* area;
* area_tecnologia;
* tecnologia;
* projeto_area_tecnologia;
* colaborador;
* contrato_colaborador_empresa_tecnologia

Relacionamentos :

* empresa - area (n para n);
* area - tecnologia (n para n);
* area - projeto (1 para n);
* tecnologia - projeto (1 para n);
* projeto - contrato (1 para n)
* empresa - contrato (1 para n);
* colaborador - contrato (1 para 1 )

# Tecnologias Utilizadas

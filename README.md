# Lab_BancoDeDados
Exercícios realizados 
# 1. Descrição Geral do Sistema:
O propósito principal do sistema é manter um cadastro atualizado das pessoas que
tenham qualquer tipo de relacionamento com a empresa Mark-Tingue.
A Mark-Tingue é uma empresa de relacionamento é promove contatos entre pessoas
para comercialização de produtos e serviços, conforme os interesses destas pessoas.
Desta forma a Mark-Tingue necessita de um cadastro de pessoa completo, tanto de
pessoa física, como de pessoa jurídica. Neste cadastro é importante saber os meios de
contato com a pessoa e seus dados de endereçamento. 

# 2.Lista de requisitos Funcionais
RF001 Cadastro de Pessoa
RF002 Inclusão dados da Pessoa
RF003 Consulta de dados da Pessoa
RF004 Alteração de dados da Pessoa
RF005 Exclusão da Pessoa no cadastro
RF006 Pesquisa da Pessoa pelo Nome
RF007 Emissão de lista da Pessoa

# 3.Lista de requisitos Não-Funcionais
RNF001 Autenticação por usuário e senha
RNF002 O sistema deve ser executado em navegador de Internet
RNF003 O sistema deve ser de fácil operação e intuitivo para o usuário

# 4. Requisitos Funcionais

RF001
Nome: Cadastro de Pessoa
Descrição: O cadastro da pessoa de ser composto dos seguintes campos:
Nome completo da pessoa, Endereço completo da pessoa, Todos os
telefones da pessoa, Todos os e-mails da pessoa, CPF ou CNPJ, Data de
nascimento da pessoa, Sexo da pessoa, A data em que a pessoa foi
cadastrada no sistema, Estado civil da pessoa, O contato da pessoa no
caso de empresa e os interesses das pessoas.
RF002
Nome: Inclusão dados da Pessoa
Descrição: O cadastro da pessoa deve permitir a inclusão dos dados da
pessoa. Não poderá ocorrer duplicação de registro da mesma pessoa, que
deve ser identificada pelo CFP ou CNPJ.
RF003
Nome: Consulta de dados da Pessoa
Documento de Requisitos, Regras
de Negócio e Sumário
Página 3 de 3
Descrição: O cadastro da pessoa deve permitir a consulta geral de todos
os dados da pessoa. Nesta consulta não será permitir alteração de qualquer
dado.
RF004 
Nome: Alteração de dados da Pessoa
Descrição: O cadastro da pessoa deve permitir a alteração dos dados da
pessoa, com exceção do CFP ou CNPJ.
RF005
Nome: Exclusão da Pessoa no cadastro
Descrição: O cadastro da pessoa deve permitir a exclusão definitiva do
registro de uma pessoa. Antes de excluir deve ter uma confirmação.
RF006
Nome: Pesquisa da Pessoa pelo Nome
Descrição: O cadastro da pessoa deve ter uma forma de pesquisa do
cliente pelo Nome para que possa ser consultado, alterado ou excluído.
Deve apresentar uma lista com todos resultados da pesquisa, para que o
usuário selecione a pessoa desejada. Na lista de resultado da pesquisa
deve ter o nome completo da pessoa e CPF ou CNPJ.
RF007
Nome: Emissão de relatório da Pessoa
Descrição: O cadastro de ter um relatório com todas pessoas cadastradas
e seus contatos. A emissão de relatório de ser em ordem alfabética do
nome da pessoa e agrupado por e-mail e telefones.

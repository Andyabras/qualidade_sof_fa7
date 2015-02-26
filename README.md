# Processo de desenvolvimento de software
###### Criado por Victor Hugo, Luiz Alfredo, Nilderlan e Thiago

Este processo está de acordo com [Guia de Implementação de Software Nível G:2013](http://www.softex.br/wp-content/uploads/2013/07/MPS.BR_Guia_de_Implementacao_Parte_1_2013.1.pdf)


### Atividades

##### Levantamento de requisitos
  1. O gerente do projeto e o analista de requisitos se reunem com o cliente.
  2. O gerente do projeto cria a ata da reunião.
  3. O gerente do projeto envia a ata para o cliente, por e-mai. O mesmo deve responder o e-mail confirmando o recebimento e dando o aval positivo. 

Artefato de entrada | Artefato de saída | Responsável | Critério de entrada
------------------- | ----------------- | ----------- | -------------------
...  | Ata da reunião. Documento que descreve as necessidades do cliente  |  Gerente do projeto e Analista de requisitos |  Solicitação do cliente
  
##### Especificar os requisitos
  1. Gerente de projeto aloca a equipe para o projeto
  2. Gerente do projeto reune a equipe técnica (analista de desenvolvimento e analista de teste) para discutir a ata da reunião. O gerente de projetos envia um e-mail para todos os envolvidos, definindo o compromentimento com os requisitos
  3. Analista de desenvolvimento prepara o documento de requisitos com base em um modelo definido pela empresa
  4. Analista de requisito revisa o documento de requisitos

Artefato de entrada | Artefato de saída | Responsável | Critério de entrada
------------------- | ----------------- | ----------- | -------------------
Ata da reunião | Documento de requisitos, com requisitos funcionais e não funcionais | Gerente do projeto, Analista de desenvolvimento e Analista de requisito | Levantamento de requisitos concluído

##### Validar os requisitos
  1. O gerente do projeto e analista de requisitos validam o documento de requisitos com o cliente
  2. Analista de desenvolvimento prepara o diagrama de caso de uso
  3. Analista de desenvolvimento prepara o diagrama de classe
  4. Analista de desenvolvimento prepara o diagrama de sequência para principais funcionalidades

Artefato de entrada | Artefato de saída | Responsável | Critério de entrada
------------------- | ----------------- | ----------- | -------------------
Documento de requisitos | Documento de requisitos validado pelo cliente | Gerente do projeto, Analista requisitos e Analista de desenvolvimento | Requistos especificados

***

### Mapeamento de resultados

Resultado |   Situação   | Ponto no processo | Observação
--------- | ------------ | ----------------- | ----------
  GRE01   | ATENDIDO     | São os passo 1 e 2 da atividade "Levantamento de requisitos" | É gerado o artefato de saída da atividade "Levantamento de requisitos", ata de reunião, onde comprova todos os requisitos solicitados pelo cliente.
  GRE02   | ATENDIDO     | ... | ...
  GRE03   | NÃO ATENDIDO | Nenhum ponto | Existe a necessidade de criar um passo para o controle de mudança do documento de requistos e produtos do projeto (Os artefatos relacionados com o processo).
  GRE04   | ATENDIDO     | Passo 4 da atividade "Especificar os requisitos" e passo 1 da atividade "Validar os requisitos". | ...
  GRE05   | NÃO ATENDIDO | Nenhuma atividade | Existe a necessidade de criar uma atividade para controle de mudanças.

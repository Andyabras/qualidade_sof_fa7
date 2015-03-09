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
  2. Gerente do projeto reune a equipe técnica (analista de desenvolvimento e analista de teste) para discutir a ata da reunião. O gerente de projetos envia um e-mail para todos os envolvidos, definindo o compromentimento com os requisitos. Cada participante da equipe técnica deve responder o e-mail confirmando o comprometimento. 
  3. Analista de desenvolvimento prepara o documento de requisitos com base em um modelo definido pela empresa. O analista de desenvolvimento versiona o documento de requisitos
  4. Analista de requisito revisa o documento de requisitos. O analista de requisito versiona a revisão do documento de requisitos.

Artefato de entrada | Artefato de saída | Responsável | Critério de entrada
------------------- | ----------------- | ----------- | -------------------
Ata da reunião | Documento de requisitos, com requisitos funcionais e não funcionais | Gerente do projeto, Analista de desenvolvimento e Analista de requisito | Levantamento de requisitos concluído

##### Validar os requisitos
  1. O gerente do projeto e analista de requisitos validam o documento de requisitos com o cliente
  2. Analista de desenvolvimento prepara o diagrama de caso de uso. O analista de desenvolvimento versiona o diagrama de caso de uso.
  3. Analista de desenvolvimento prepara o diagrama de classe. O analista de desenvolvimento versiona o diagrama de classe.
  4. Analista de desenvolvimento prepara o diagrama de sequência para principais funcionalidades. O analista de desenvolvimento versiona o diagrama de sequência.
  5. O gerente do projeto deve revisar os diagramas criados e criar uma tag no controle de versão com todos os documentos.

Artefato de entrada | Artefato de saída | Responsável | Critério de entrada
------------------- | ----------------- | ----------- | -------------------
Documento de requisitos | Documento de requisitos validado pelo cliente | Gerente do projeto, Analista requisitos e Analista de desenvolvimento | Requistos especificados

##### Controle de mudanças
  1. O gerente de projetos recebe a solicitação de mudança e registra num Documento de Solicitação de Mudanças.
  2. O gerente de projetos avalia o impacto destas mudanças. Os impactos podem ser no cronograma, custo, risco, esforço, afetar outros requisitos, dentre outros.
  3. O gerente de projetos envia o documento de solicitação de mudanças para o cliente decidir se as mudanças devem ser realizadas.

Artefato de entrada | Artefato de saída | Responsável | Critério de entrada
------------------- | ----------------- | ----------- | -------------------
Solicitação de mudança | Solicitação de mudanças documentada e avaliada pelo cliente | Gerente do projeto | Ter finalizado a fase de validação de requisitos

***

### Mapeamento de resultados

Resultado |   Situação   | Ponto no processo | Observação
--------- | ------------ | ----------------- | ----------
  GRE01   | ATENDIDO     | São os passo 1 e 2 da atividade "Levantamento de requisitos" | É gerado o artefato de saída da atividade "Levantamento de requisitos", ata de reunião, onde comprova todos os requisitos solicitados pelo cliente.
  GRE02   | ATENDIDO     | Atendido no passo 2 da atividade "Especificação de requisitos". | O comprometimento da equipe técnica fica formalizado por e-mail.
  GRE03   | ATENDIDO     | Passo 2 da atividade "Levantamento de requisitos". Passo 2,3,4 da atividade "Especificação de requisitos". Passo 1,2,3,4 da atividade "Validação de requisitos". | A ata de reunião ou e-mail de solicitação de mudança deve ser registrado no controle de versão definindo para cada um uma identificação (versão). Todos os outros documentos (documento de requisitos, e-mail de confirmação de validação e documentos de diagramas) tem uma referencia da identificação (versão) da ata de reunião ou e-mail de solicitação de mudança. 
  GRE04   | ATENDIDO     | Passo 4 da atividade "Especificar os requisitos" e passos 1 e 5 da atividade "Validar os requisitos". | Para cada artefato gerado tem pelo menos um passo para revisão.
  GRE05   | ATENDIDO | Atividade 'Controle de mudanças' | É gerado um documento comprovando e contendo a solicitação de mudanças, sendo que o cliente decide se as aceita, formalizando esta decisão através do próprio documento.

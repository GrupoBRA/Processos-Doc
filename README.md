# Processos

### Introdução
O objetivo da aplicação descrita neste documento é a gestão de processos eletrônicos de concessão de aposentadorias e pensões. 

### Objetivo
A aplicação deve permitir ao usuário criar um processo vinculado a um CPF e uma matrícula de um servidor, doravante denominado interessado, criar, editar e fazer uploads de arquivos e documentos que se fizerem necessários à construção de tal processo. A aplicação deve gerar uma conjunto finito de documentos pré-estruturados, com os dados do interessado inseridos automaticamente.

# Fases do processo

O processo possui 3(três) fases de tramitação: abertura, deferimento e envio ao Tribunal de Contas do Estado(TCE). O processo é aberto e os documentos automatizados são criados, a partir daí o usuário pode adicionar novos documentos via upload ou via editor de texto da aplicação, imprimir o processo completo, reorganizar/remover os documentos do processo e tramitá-lo para as próximas fases.

### Abertura do processo

Para abrir um processo, o CPF e a matrícula de um servidor devem ser informados, o usuário deve informar a regra de aposentadoria ou pensão na qual o processo de concessão se baseará dentre as regras determinadas pela lei municipal em vigor ou pela Constituição, caso o município ainda não tenha legislado. Em seguida um número de processo deve ser criado, de acordo com a configuraÇão de numeração de processos da entidade em uso, também deve ser possível o usuário informar um número manualmente, desde que o número informado não esteja em uso por outro processo em tramitação.


### Deferimento do processo

Após a abertura do processo, este já está imediatamente apto a ser deferido, cabendo ao usuário a verificação dos documentos do processo, bem como adições e/ou alterações que se fizerem necessárias para a concessão. Ao realizar o deferimento, um número de portaria deve ser criado, de acordo com a configuraÇão de numeração de portarias da entidade em uso, também deve ser possível o usuário informar um número manualmente, desde que o número informado não esteja em uso por outro processo em tramitação. O documento automático do tipo "poraria" deve ser atualizado para constar este número e a data da portaria, que também pode ser informada pelo usuário.

### Envio para o TCE
Após a análise final de todos os documentos criados/editados pelo sistema e pelo usuário no processo, este já pode ser encaminhado ao TCE para homologação. Ao realizar o envio, um número de ofício deve ser criado, de acordo com a configuraÇão de numeração de ofícios da entidade em uso, também deve ser possível o usuário informar um número manualmente, desde que o número informado não esteja em uso por outro processo em tramitação. O documento automático do tipo "Ofício de encaminhamento ao TCE" deve ser atualizado para constar este número e a data do ofício, que também pode ser informada pelo usuário.

Especificações:

### Documentos do sistema

Todos os documentos automáticos devem ser criados com base em seus respectivos layouts, utilizando os dados do interessado e da entidade concessora. Todos os documentos deste tipo devem prover ao usuário a possibilidade de restaurá-los à versão inicial

### Documentos do usuário

O usuário deve ter a possibilidade de editar todos os documentos gerados pelo sistema, criar novos documentos de texto e fazer upload de outros documentos, dos tipos: texto, planilha, PDF e imagem.



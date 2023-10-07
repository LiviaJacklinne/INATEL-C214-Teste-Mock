# INATEL-C214-Teste-Mock
Trabalho de Engenharia de Software - Teste Mock

# Integrantes
- Lívia Jacklinne Ramos Moreira - 1731 - GEC;
- Letícia Vitória Merss Moreira - 56 - GES.

---

--> O projeto demonstra a implementação de um serviço de busca de professores utilizando um mock (simulação) de um serviço real. O objetivo é ilustrar como testar a funcionalidade de busca de professores em um contexto de testes unitários.

### Descrição do Projeto
- MockProfessorService
`MockProfessorService` é uma classe que implementa a interface `ProfessorService` e simula a recuperação de uma lista de professores do servidor. Esta implementação não depende da implementação real dos métodos da interface.

- ProfessorConst
A classe `ProfessorConst` contém strings `JSON` que representam informações sobre os professores. Estas strings são utilizadas na simulação do serviço de busca.

- TesteBuscaProfessor
`TesteBuscaProfessor` é uma classe de testes que verifica o comportamento do serviço de busca de professores. Ela utiliza a implementação `MockProfessorService` para criar um contexto de teste controlado.

---

### Como Executar os Testes:

Para executar os testes, basta executar a classe `TesteBuscaProfessor` em um ambiente de desenvolvimento que suporte a execução de testes JUnit.

---

### Resultados Esperados
Os testes verificam se a busca de professores retorna os resultados esperados, se as salas e prédios são obtidos corretamente e se erros são tratados de forma apropriada.

Foram desenvolvidos 10 casos de sucesso e 10 casos de falha.


 


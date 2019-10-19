#  Trabalho Prático – Parte 3– Avaliação por Inspeção 

## Entrega 2 - Relatório Individual

###### Ingrid Rosselis Sant Ana da Cunha

Site: [Plano de Estudos do SIGA](https://sistemas.ufmg.br/aluno-grad/planodeestudos/consultarplanosdeestudos/telaConsultaAPlanosDeEstudos.seam?bkmk=)

### Problema 1

- **Descrição do problema, explicando por quê é um problema:**

Para fazer qualquer simulação no plano de estudos vigentes é necessário criar uma cópia deste, mesmo que haja um botão de "Alterar" bem destacado pela interface e que pode ser apertado mesmo fora do período de modificação pré-estabelecido.

- **Imagem indicando o problema:**

![](https://i.imgur.com/3BikO5C.png)

- **Heurística(s) violada(s):**

 Consistência e padronização.

- **Local:**

Na tela de um plano de estudos.

- **Gravidade (justificada):**

2 (problema pequeno): não faz sentido, cria uma mensagem de erro por algo que, de certa forma, o usuário não tem culpa e ainda causa alguns cliques extras, mas não causa nenhum tipo de prejuízo na tarefa que o usuário fará.

### Problema 2

- **Descrição do problema, explicando por quê é um problema:**

Tela do plano é preenchida, em sua maior parte, pelas caixas dos semestres anteriores, o que é um desperdício de espaço e uma poluição da tela.

- **Imagem indicando o problema:**

![](https://i.imgur.com/wwW1KHk.png)

- **Heurística(s) violada(s):**

Flexibilidade e eficiência de uso.

Design estético e minimalista.

- **Local:**

Na tela de um plano de estudos.

- **Gravidade (justificada):**

1 (problema cosmético): como é só estética do *layout* (não afeta o uso, nem trás bugs), não existe tanta necessidade de correção imediata.

### Problema 3

- **Descrição do problema, explicando por quê é um problema:**

Conferir as inconsistências no plano é um trabalho exaustivo porque é necessário clicar em alterar, fazer as modificações, clicar em salvar e só depois conferir quais foram os problemas no plano de estudos proposto.

- **Imagem indicando o problema:**

![](https://i.imgur.com/BtEzxfL.png)

- **Heurística(s) violada(s):**

 Ajuda aos usuários para reconhecerem, diagnosticarem e se recuperarem de erros.

 Flexibilidade e eficiência de uso.

- **Local:**

Na tela de um plano de estudos.

- **Gravidade (justificada):**

2 (problema pequeno): afeta um pouco a eficiência de uso do usuário, mas não é um problema impeditivo.

### Problema 4

- **Descrição do problema, explicando por quê é um problema:**

O plano de estudos deveria ser usado para o semestre 2020/1 (ou seja, o próximo semestre), mas toda vez que é aberto, ele inicia no semestre atual.

- **Imagem indicando o problema:**

![](https://i.imgur.com/rAeXyzU.png)

- **Heurística(s) violada(s):**

 Consistência e padronização.

- **Local:**

Na tela de um plano de estudos.

- **Gravidade (justificada):**

2 (problema pequeno): não faz muito sentido visualizar a grade do semestre vigente (considerando que o aluno está ativamente fazendo esta grade e já a conhece bem), mas não atrapalha muito, só é necessário fechar esta grade e abrir a correta.

### Problema 5

- **Descrição do problema, explicando por quê é um problema:**

Na primeira vez entrando no plano de estudos, a grade mostrada é a do semestre atual, mas a aba de inconsistências informa inconsistência do próximo semestre letivo, mesmo que o usuário ainda não tenha editado-o.

- **Imagem indicando o problema:**

![](https://i.imgur.com/MmDp5Iq.png)

- **Heurística(s) violada(s):**

 Visibilidade do estado do sistema.

 Consistência e padronização.

- **Local:**

Na primeira vez que um plano de estudos é aberto.

- **Gravidade (justificada):**

3 (problema grande): acredito que se o usuário não ficar atento, isso pode vir a causar um problema de interpretação das informações apresentadas no sistema, seja o usuário confundindo a grade atual pela próxima grade ou entendendo que existe alguma inconsistência na grade em que foi matriculado este semestre.
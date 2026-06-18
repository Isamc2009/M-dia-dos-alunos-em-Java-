# Projeto de média dos alunos em Java

Este código em Java é um sistema automático de validação de status acadêmico. Ele calcula a média ponderada de quatro notas e, cruzando esse dado com a frequência do aluno, define sua situação final através de quatro cenários possíveis:

Reprovado por Falta: Frequência abaixo de 75%.

Reprovado por Média: Frequência ok, mas média menor que 5.0.

Aprovado Direto: Frequência ok e média igual ou maior que 7.0.

Exame Final: Média entre 5.0 e 6.9. Nessa etapa, o sistema calcula uma nova média com a nota da prova de recuperação, exigindo nota mínima 6.0 para a aprovação.

Ao final, o programa exibe no console um relatório formatado com o veredito do estudante

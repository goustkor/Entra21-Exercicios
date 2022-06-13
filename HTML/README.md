# Exercicio 1

Crie uma tela para cadastro de alunos da escola XPTO, tendo os seguintes campos:

- \*Nome
- \*Sobrenome
- \*Data Nascimento
- Endereço
- \*Nome da Mae
- Nome do Pai
- Email
- Série atual(Nível de alfabetização)
- \*Sexo(masculino, Feminino)
- Botões: Submeter, Reset

# Exercicio 2

Crie um tela de uma urna eletrônica.

> Esta tela deverá conter um campo para digitação do número eleitoral do candidato e um campo para apresentar o nome do candidato, a tela também deverá exibir a foto do candidato.
> Caso o eleitor não se recorde do número de seu candidato ele poderá selecionar o número do candidato de uma lista.
> A urna deverá contar com os botões "Confirmar", "Cancelar", "Branco".

# Exercicio 3

Crie um formulário de contato para o Site da empresa XYZ. Campos:

- \*Nome
- \*Email
- \*Empresa
- \*Telefone
- \*Motivo do contato (Comercial, Reclamação, Sugestão, Cancelamento de Assinatura, Dúvida, Outros)
- \*Seu Comentário (Permitir múltiplas linhas de digitação e um máximo de 1000 caracteres)

\*\*Utilize Placeholder no lugar de Label

\*\*Botão: Enviar

# Exercicio 4

A empresa XYZ quer exibir um formulário de pesquisa de satisfação ao termino de seu atendimento online.

Crie uma tela com perguntas e respostas do tipo múltipla-escolha:

- Sua solicitação foi atendida? (não foi atendida, parcialmente atendida, totalmente atendida)
- Qual nota você daria para o atendimento? (péssimo, ruim, aceitável, bom, excelente)
- Como você classificaria o comportamento do atendente? (Indelicado, Mal-humorado, Neutro, Educado, Muito Atencioso)
- De 0 a 10, qual nota você daria para o produto (utilize range)
- Informe sua idade (campo numérico)
- Informa seu Gênero (Masculino/Feminino/LGBT)

# Exercicio 5

Crie uma tela de login.

## Campos

- Usuário
- Senha
- Botões: Login, Recuperar Senha;

## Critérios:

- A senha deverá ter no mínimo 8 e no máximo 15 caracteres;
- O campo usuário deverá permitir autocomplete
- O campo senha não deverá permitir autocomplete
- A senha deverá ser composta por letras maiúsculas e minúsculas, números e @#$ -->

```regexp
pattern="^(?=.[A-Z])(?=.[a-z])(?=.[0-9])(?=.[@#$])[a-zA-Z0-9@#$]{8,15}$"
```

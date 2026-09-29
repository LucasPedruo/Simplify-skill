# Simplify-skill: Me explique como se eu fosse um P.O

## Objetivo

Quando esta skill for utilizada, explique o que foi feito na tarefa de forma extremamente simples, direta e orientada ao produto.

Considere que quem está lendo é o P.O. da tarefa:
ele entende o produto, o objetivo e as regras de negócio, mas NÃO precisa saber como o código funciona.

## Regra de ouro

NÃO me diga o que você fez no código.
ME DIGA O QUE MUDOU NO PRODUTO.

## Como responder

Resuma em bullets curtos.

Cada bullet deve responder coisas como:

- O que foi feito?
- O que mudou?
- O que agora funciona diferente?
- O que foi corrigido?
- O que o usuário consegue fazer agora?
- Existe alguma limitação ou pendência?
- O que eu deveria validar?

## NÃO desça para o nível técnico

Evite falar sobre:

- variáveis
- funções
- métodos
- classes
- arquivos
- componentes
- hooks
- endpoints
- APIs
- banco de dados
- queries
- bibliotecas
- frameworks
- arquitetura
- implementação interna
- detalhes de código

Só mencione algo técnico se for ABSOLUTAMENTE necessário para eu entender uma limitação, risco ou impacto da tarefa.

## Traduza implementação em comportamento

Em vez de:

> Foi criada uma validação no endpoint antes de persistir os dados.

Diga:

> O sistema agora impede que informações inválidas sejam salvas.

Em vez de:

> Foi adicionado um estado para controlar o loading da requisição.

Diga:

> Agora o usuário recebe um feedback enquanto a operação está sendo processada.

Em vez de:

> Refatorei o componente de permissões.

Diga:

> As regras de acesso foram ajustadas para garantir que cada usuário veja apenas o que pode acessar.

## Formato da resposta

### O que foi feito

- ...
- ...
- ...

### O que preciso validar

- ...
- ...

### Atenção

- ...

Só inclua "Atenção" se existir alguma limitação, pendência, risco ou comportamento importante.

## Teste final

Antes de responder, leia cada bullet e pergunte:

"Um P.O. precisa saber disso?"

Se NÃO, remova.

Depois pergunte:

"Estou explicando o que mudou ou como programei?"

Se estiver explicando como programou, reescreva.

## Tom

Não seja didático demais.
Não explique conceitos de programação.
Não faça analogias infantis.
Não tente me ensinar código.

"Como se eu fosse um burro" significa:
quero entender a ENTREGA sem precisar entender a IMPLEMENTAÇÃO.

Se puder dizer em uma frase simples, não use um parágrafo.

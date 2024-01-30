<div align='center'>

![Magazord][link-logo]

 </div>

# Teste para vaga de Analista de Integração

Este repositório tem como fim testar os candidatos para vaga de Analista de Integração na empresa [Magazord][link-zord]

## O teste

Você está encarregado de interpretar uma situação problema reportada por um usuário da plataforma que está enfrentando
uma inconsistência ao tentar realizar o cadastro de uma nova imagem por meio das [APIs][link-docs] do MagaZord.

O cenário foi realizado considerando o endpoint **/api/v2/site/midia/upload** e o seguinte corpo de requisição:

```json
{
  "tipo": 2,
  "plataforma": 1,
  "tipoMidia": 1,
  "midiaFile": "2asdasd=",
  "nomeArquivo": "furadeira.jpeg"
}
```

1) Em sua primeira tentativa para cadastro de uma nova imagem o usuário obteve o seguinte retorno da API:

```json
{
  "status": "error",
  "message": "Credenciais não informadas!"
}
```

Por qual motivo isso ocorreu? Qual o procedimento o cliente poderia realizar para realizar a requisição com sucesso?

2) O usuário resolveu o problema anterior, porém, a repetir a chamada, enfrentou um novo problema com o seguinte retorno:

```json
{
  "status": "error",
  "message": "O conteúdo do arquivo não é válido para o cadastro"
}
```

Por qual motivo essa situação pode ter ocorrido? Qual o procedimento você realizaria para identificar a causa do
problema e auxiliar o cliente a resolver o seu problema?

## Avaliação:

- Os candidatos serão avaliados com base na clareza, precisão e detalhamento das respostas.
- A capacidade de compreender e comunicar efetivamente requisitos e problemas é fundamental.
- A organização e a estrutura das respostas também serão consideradas na avaliação.

## Envio do teste:

Suba o repositório no seu Github e envie o link diretamente para o seu recrutador. Obs.: Não serão aceitos alterações após o envio.


[link-logo]: https://raw.githubusercontent.com/magazord-plataforma/.github/main/assets/logo.png
[link-zord]: https://magazord.com.br
[link-docs]: https://docs.api.magazord.com.br/

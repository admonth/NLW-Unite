# Anotações
Table = Tabela
a tag table serve pra a aplicação de uma tabela
a tag thead é o cabeçalho da tabela
tr (throw) que seria cada uma das linhas
th é o cabeçalho do throw? é o conteúdo?
tbody é o corpo, conteúdo da tabela, novamente tr são as linhas
td é a informação do corpo

# JS
```js
// variaveis
const mensagem = `Oi, tudo bem?`
// tipos de dados
  // number
  // string
// funcao
alert(mensagem)

// Objeto javascript
const participante = {
  nome: "Mayk Brito",
  email: "mayk@gmail.com",
  dataInscricao: new Date(2024, 2, 22, 19, 20),
  dataCheckIn: new Date(2024, 2, 25, 22, 00)
}

// Array
let participantes = [
  {
    nome: "Mayk Brito",
    email: "mayk@gmail.com",
    dataInscricao: new Date(2024, 2, 22, 19, 20),
    dataCheckIn: new Date(2024, 2, 25, 22, 00)
  },
]

// estrutura de repetição - loop
for(let participante of participantes) {
  // faça alguma coisa aqui
  // enquanto tiver participantes nessa lista
}
```
quando se usa uma variável que nao vai mudar de valor, se usa const = Constante
porém caso você use uma variável que no futuro terá seu valor alterado, como por exemplo a variável participantes (terá sempre outros participantes com informações diferentes, email diferente, nome e etc.. ) se usa LET
# HTML
*Hypertext Markup Language*

- Tags
- Hyperlinks 

Visão Geral:
```HTML
<h1>Isso é um título</h1>
<a href="https://google.com">Isso é uma âncora</a>
```
# CSS
*Cascading StyleSheet*

- Seletores
- Cores
- Classes
- Fontes
- Margens, Tamanhos e Bordas

Visão Geral:
```CSS
table{
  /*Alterando o estilo das bordas da tabela*/
  padding: 32px;
  border: 1px solid red;
  margin: 32px;
}
```

# JavaScript

- Variáveis
- Funções
- Tipos de dados
- Objetos 

Visão Geral:
```js
// Variável: String, Constante
  const mensagem = 'Olá mundo'
// Função
alert(mensagem)
// Criando um objeto em JavaScript
const participante = {
  nome: "Hugo",
  email: "devhugoherrera@gmail.com",
  dataInscrição: new Date(2024, 2, 3, 19, 30),
  dataCheckIn: new Date(2024, 3, 1, 22, 45) 
}
// Criando arrays
let participantes = [
  {
    nome: "Hugo",
    email: "devhugoherrera@gmail.com",
    dataInscrição: new Date(2024, 2, 3, 19, 30),
    dataCheckIn: new Date(2024, 3, 1, 22, 45)
  },
]
  // Estrutura de repetição
  for(let participante of participantes){
  // Instruindo a máquina a fazer algo enquanto ainda tiver elementos na lista "participantes"
  }
```
**OBS: Variáveis podem conter funções**
**OBS: Let é um tipo de variável que apenas a função que ela está dentro pode modifica-la**
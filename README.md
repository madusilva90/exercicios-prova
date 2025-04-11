# exercicios-prova
//exercicio 3
let Banco = []
Banco.push("Maria")
Banco.push("Flavia")
Banco.push("rafael")
console.log(Banco)
Banco.shift()
Banco.shift()
Banco.shift()
console.log(Banco)

//exercicio 4
const devolucoes=[]
const Livro1= {
  Titulo: "Principe Cruel",
  autor:"Holly Blck",
  atrasado:"Não",
}
const Livro2= {
  Titulo: "Seleção",
  autor:"Quiera Quez",
  atrasado:"Não",
}
const Livro3= {
  Titulo: "Noites de primavera",
  autor:"Isaac",
  atrasado:"Sim",
}
devolucoes.unshift(Livro1)
devolucoes.unshift(Livro2)
devolucoes.unshift(Livro3)
console.log(Livro1)
console.log(Livro2)
console.log(Livro3)
console.log(devolucoes.pop())
console.log(devolucoes.pop())
console.log(devolucoes.pop())
console.log(devolucoes)

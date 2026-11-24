# Atividade 3 — Pseudocódigos

**Curso:** Web Academy UFAC  
**Disciplina:** Algoritmos e Lógica de Programação  
**Aluno:** Vinicius Miranda de Farias

## Questão 1 — Média ponderada (Nerds Primeiro)

As duas primeiras notas têm peso 3 e a terceira peso 4, totalizando peso 10.

```
programa {
    funcao inicio() {
        real n1, n2, n3, media
        escreva("Digite a primeira nota: ")
        leia(n1)
        escreva("Digite a segunda nota: ")
        leia(n2)
        escreva("Digite a terceira nota: ")
        leia(n3)
        media = (n1 * 3 + n2 * 3 + n3 * 4) / 10
        escreva("Media ponderada: ", media)
    }
}
```

## Questão 2 — Peso do João Bolt

Perder 6% ao mês significa manter 94% do peso a cada mês. Em três meses: peso final = peso inicial × 0,94 × 0,94 × 0,94.

```
programa {
    funcao inicio() {
        real pesoInicial, pesoFinal
        escreva("Digite o peso inicial: ")
        leia(pesoInicial)
        pesoFinal = pesoInicial * 0.94 * 0.94 * 0.94
        escreva("Peso apos tres meses: ", pesoFinal)
    }
}
```

## Questão 3 — Salários-mínimos ganhos por Fernanda

```
programa {
    funcao inicio() {
        real salarioMinimo, salario, quantidade
        escreva("Digite o valor do salario-minimo: ")
        leia(salarioMinimo)
        escreva("Digite o salario de Fernanda: ")
        leia(salario)
        quantidade = salario / salarioMinimo
        escreva("Fernanda ganha ", quantidade, " salarios-minimos")
    }
}
```

## Questão 4 — Potência de iluminação

São necessários 18 W para cada m². Área = comprimento × largura; potência = área × 18.

```
programa {
    funcao inicio() {
        real comprimento, largura, area, potencia
        escreva("Digite o comprimento do comodo em metros: ")
        leia(comprimento)
        escreva("Digite a largura do comodo em metros: ")
        leia(largura)
        area = comprimento * largura
        potencia = area * 18
        escreva("Potencia necessaria: ", potencia, " W")
    }
}
```

## Questão 5 — Despesas da viagem à Espanha

Ana Júlia gasta 100 euros por dia. O valor em reais é: cotação do euro × 100 × quantidade de dias.

```
programa {
    funcao inicio() {
        real cotacao, reais
        inteiro dias
        escreva("Digite a cotacao atual do euro: ")
        leia(cotacao)
        escreva("Digite a quantidade de dias: ")
        leia(dias)
        reais = cotacao * 100 * dias
        escreva("Valor necessario em reais: ", reais)
    }
}
```

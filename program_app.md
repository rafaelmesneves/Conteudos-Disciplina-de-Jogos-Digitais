---
layout: default
title: Programação - Lógica aplicada
---

# Programação - Lógica aplicada


## Variáveis

Variáveis guardam valores:

```lua
nome = "Juca"
idade = 12
```

![nicho](https://images.tcdn.com.br/img/img_prod/1008193/nicho_organizador_preto_com_3_gavetas_pretas_qmovi_14778_2_99335045debd46cb56e81530478ea820.jpg)


---

## Operações

```lua
soma = 5 + 3
print(soma)
```

![operações](https://static.mundoeducacao.uol.com.br/mundoeducacao/2023/05/blocos-de-madeira-com-os-simbolos-das-quatro-operacoes-matematicas-basicas-adicao-subtracao-multiplicacao-e-divisao.jpg)


---

## Strings

```lua
print("Olá, " .. nome)
```

---

## Operadores

Relacionais:
```lua
< > <= >= == ~=
```

![op rela](https://dicasdeprogramacao.com.br/images/operadores-relacionais/Operadores-relacionais.jpg)


Lógicos:
```lua
and, or, not
```

**and** = E

As duas condições precisam ser verdadeiras.


**or** = OU

Apenas uma condição precisa ser verdadeira.


**not** = NÃO

Inverte o valor lógico.

![](https://clubes.obmep.org.br/blog/wp-content/uploads/2019/07/Travessia-do-Rio.jpg)


---

## Estruturas de Controle

### If


```lua
idade = 12

if idade >= 10 then
  print("Pode jogar")
else
  print("Não pode")
end
```

**SE** idade for maior ou igual a 10, **ENTÃO** execute isso.


**Significa:** 

**if** = SE

Usado para testar uma condição.

**then** = ENTÃO

Indica o que acontece se a condição for verdadeira.

**else** = SENÃO

Executa quando a condição do if é falsa.

*Também existe o comando **elseif** = SENÃO SE, permite testar outra condição.*

---

## Loops

### For

```lua
for i = 1, 5 do
  print(i)
end
```

**PARA** i de 1 até 5



**for** = PARA

Usado para repetir com controle.


### While

```lua
i = 1
while i <= 5 do
  print(i)
  i = i + 1
end
```

**ENQUANTO** i for menor que 5 somar + 1



**while** = ENQUANTO

Repete enquanto a condição for verdadeira.


*Nas duas formas de Repetição, há o **do** = FAÇA, é ele que indica o início da ação do laço.*

---

## Tabelas

```lua
nomes = {"Ana", "Pedro", "Rafa"}

for i = 1, #nomes do
  print(nomes[i])
end
```
![tabela naruto](https://i.ibb.co/SDRsLZfB/Captura-de-tela-20260324-223313.png)

---

## Funções

```lua
function soma(a, b)
  return a + b
end

print(soma(3,4))
```

---

**Outros comandos importantes**


**break** =  PARE

Interrompe um loop.



**return** = RETORNE

Devolve um valor em uma função.



**local** = VARIÁVEL LOCAL

Indica que a variável só existe dentro daquele bloco.

---

# Exercícios

## Básico
1. Crie uma variável cidade.
2. Some dois números.
3. Crie um booleano.

## Decisão
1. Verifique idade >= 12.
2. Par ou ímpar.
3. Nota >= 7.

## Repetição
1. Conte de 1 a 10.
2. Mostre pares até 20.
3. Repita seu nome 5 vezes.

## Tabelas
1. Lista com 5 nomes.
2. Mostrar com loop.
3. Somar números.

## Funções
1. Saudação com nome.
2. Maior entre dois números.
3. Quadrado de um número.

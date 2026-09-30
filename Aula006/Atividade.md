# Respostas do Questionário de Linguagens de Programação

## 1. JavaScript

**a) Saída:**

```
false
9007199254740992
```

**b) Análise:**
Ambos os problemas não são detectados nem na execução nem na compilação, visto que são simplesmente comportamentos da linguagem, apesar de gerarem comportamentos inesperados.

## 2. Python

**a) Saída:**

`4 6`

**b) Problema:**

Não existe erro ou problema. Pois o `len(p.encode())` retorna a quantidade de bytes utilizada, enquanto `len(p)` retorna a quantidade de caracteres.

## 3. Go

**a) Saída:**

`0`

**b) Problema:**

O problema nunca é exibido.

## 4. Java

**a) Saída:**

Para o primeiro `println` é exibida a saída `0`, já no segundo `println` ocorre o erro de *limit out of bounds*.

**b) Problema:**

O erro ocorre durante a compilação, exibindo mensagem de erro de *limit out of bounds*:

```
Exception in thread "main" java.lang.ArrayIndexOutOfBoundsException: Index 3 out of bounds for length 3 at Main.main(Main.java:8)
```

## 5. Rust

**a) Saída:**

*(Nenhuma saída gerada)*

**b) Problema:**

O problema ocorre na compilação, de forma a não executar o programa. Isso ocorre devido ao tipo `String` não ser copiado automaticamente no processo *move* feito ao transferir o valor de `s` para `t`.

## 6. C

**a) Saída:**

```
1065353216
```

**b) Análise:**

A princípio o erro não é detectado nem na execução nem na compilação, visto que não é de fato um erro. Apenas está lendo "lixo" na memória por se tratar de um tipo diferente.
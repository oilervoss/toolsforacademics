---
title: Apêndice B - Markdown
order: 7
---

# Introdução

A sintaxe original Markdown foi proposta por John Gruber em 2004 ([Gruber, 2004](https://daringfireball.net/projects/markdown/)) como um sistema de redação que simultâneamente facilitasse a leitura, a edição e a conversão para HTML.

---

# Parágrafos e quebras de linha

Um parágrafo é formado por linha consecutivas de texto separadas por uma ou mais linhas em branco. Alguns programas intérpretes podem concatenar linhas separadas poder quebras de linha simples

*Markdown*
```
Primeira linha de texto.
Segunda linha de texto.

Segundo parágrafo.
```

*Resultado*

> Primeira linha de texto. Segunda linha de texto.
>
> Segundo parágrafo.

---

# Cabeçalhos

Cabeçalhos de primeiro e segundo nível são formados por uma linha de texto seguida por uma linha de **=** ou **-**, respectivamente, de qualquer comprimento.

Cabeçalhos multi-níveis são formados por um a seis sinais **#**, conforme o nível, no início de linhas de texto.

*Markdown*
```
Título da seção
===============

Corpo da seção.


Título da subseção
------------------

Corpo da subseção.

```


*Resultado*

> Título da seção
> ===============
>
> Corpo da seção.
>
> Título da subseção
> ------------------
>
> Corpo da subseção.

*Markdown*
```
## Título de 2ª ordem

### Título de 3ª ordem

Corpo do texto.

#### Título de 4ª ordem

Corpo do texto.
```


*Resultado*

> ## Título de 2ª ordem
>
> ### Título de 3ª ordem
>
> Corpo do texto.
>
> #### Título de 4ª ordem
>
> Corpo do texto.

---

# Blocos de citação

Os blocos de citação são formados por sinais **>** no início de linhas de texto, de forma análoga às citações em email. Os blocos podem ser aninhados.

*Markdown*
```
> Primeira linha de texto.
> Segunda linha de texto.
> > Bloco aninhado.
> > Segunda linha do bloco aninhado.

> Segundo bloco de citação.
> Segunda linha de texto do segundo bloco.
```

*Resultado*

> Primeira linha de texto.
> Segunda linha de texto.
> > Bloco aninhado.
> > Segunda linha do bloco aninhado

> Segundo bloco de citação.
> Segunda linha de texto do segundo bloco.

---

# Listas não ordenadas

As listas não ordenadas (não numeradas) são formadas por quaisquer dos sinais **-**, **+**, ou **\*** no início de uma linha de texto.

Uma nova linha iniciada por três espaços garante a identação com a lista anterior.

As listas podem ser aninhadas através de três espaços antes do sinal de lista.

*Markdown*
```
+ Cores
  - Vermelho
  - Azul
  - Verde
+ Dias da semana
  - Segunda
        Primeiro dia
  - Terça
        Segundo dia
  - Quarta
        Terceiro dia
+ Red
+ Green
+ Blue
```

*Resultado*

+ Cores
  - Vermelho
  - Azul
  - Verde
+ Dias da semana
  - Segunda
        Primeiro dia
  - Terça
        Segundo dia
  - Quarta
        Terceiro dia
+ Red
+ Green
+ Blue

---
# Listas ordenadas

As listas ordenadas (numeradas) são formadas por quaisquer números seguidos de um ponto, no início de uma linha de texto. O primeiro item precisar usar o número 1 e os demais não precisam estar em ordem.

Uma nova linha iniciada três espaços garante a identação com a lista anterior.

As listas podem ser aninhadas através de três espaços antes do sinal de lista ou número.

*Markdown*
```
1. Cores
   - Vermelho
   - Azul
   - Verde
5. Dias da semana
   1. Segunda
        Primeiro dia
   1. Terça
        Segundo dia
   1. Quarta
        Terceiro dia
5. Red
5. Green
5. Blue
```

*Resultado*

1. Cores
   - Vermelho
   - Azul
   - Verde
5. Dias da semana
   1. Segunda
        Primeiro dia
   1. Terça
        Segundo dia
   1. Quarta
        Terceiro dia
5. Red
5. Green
5. Blue

---

# Linha de código

Blocos de código são formados por parágrafos antecedidos por quatro espaços. Blocos de código não estão sujeitos a formatação automática.

*Markdown*
```
Blocos de código são utilizados para destacar informações em fonte de tamanho fixo e sem formatação.

    É utilizado frequentemente para apresentar comandos de programação.
    Mas pode ser utilizado em situações onde é interessante o alimento dos caracteres.
```

*Resultado*

Blocos de código são utilizados para destacar informações em fonte de tamanho fixo e sem formatação.

    É utilizado frequentemente para apresentar comandos de programação.
    Mas pode ser utilizado em situações onde é interessante o alimento dos caracteres.

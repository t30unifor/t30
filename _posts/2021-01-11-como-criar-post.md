---
toc: false
layout: post
description: Um tutorial sobre como escrever uma página nesse site
categories: [tutoriais]
title: Como criar uma postagem
---

# Primeiro passo (Heading)

Em um editor de texto qualquer, ou [nesse site](https://stackedit.io/app) copie e cole esse texto.
```
---
toc: false
layout: post
description: Um tutorial sobre como escrever uma página nesse site
categories: [tutoriais]
title: Como criar uma postagem
---
```
1. *toc* = Table of Contents ou Sumário (recomendo deixar `false` para textos curtos e `true` para textos longos.
2. *layout* = sempre deixe em `post` para criar uma postagem
3. *description* = descrição da sua postagem
4. *categories* = tags para explicar o que o seu post tem. Pode ser `anatomia, resumos, tutorial, dica, etc`
5. *title* = Título que fica em cima da postagem

## Como se organizar?
Escreva assim para criar sutítulos como o que você vê acima
`## Como se organizar`
{% include info.html text="Use uma hashtag para títulos e duas para sutítulos e três para um sub sub título" %}

Como criar listas?

 - Pode ser lista desse formato
 - Para uma lista simples
	- Subitem
		- outro subitem

```
 - Pode ser lista desse formato
 - Para uma lista simples
	- Subitem
	- outro subitem
```

1. Ou listas numeradas
2. Dessa forma

```
1. Ou listas numeradas
2. Dessa forma
```

## Formatação
*Itálico* `*Itálico*`
__Negrito__ `__Negrito__ `
>Citaçoes `>Citaçoes`

### Links
Um link normal [aqui](https://unifor.br)
`Um link normal [aqui](https://unifor.br)`

Explicações
: assim

```
Explicações
: assim
```

Para concluir, salve o arquivo e envie para algum organizador do site e as formatações finais serão feitas para a publicação!

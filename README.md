# 🎨 CSS Transform Lab

Uma página interativa criada para demonstrar, de forma visual e prática, diferentes possibilidades da propriedade **`transform` do CSS**.

Passe o mouse sobre os objetos e veja cada transformação acontecendo em tempo real. 🚀

## 📌 Sobre o projeto

O **CSS Transform Lab** é um guia interativo desenvolvido com **HTML e CSS**, criado para facilitar o aprendizado das principais funções de transformação de elementos.

O projeto demonstra transformações em **2D e 3D**, além da possibilidade de combinar várias transformações em um único elemento.

## ✨ Transformações demonstradas

O projeto apresenta exemplos de:

* 🔍 `scale()`
* ↔️ `scaleX()`
* ↕️ `scaleY()`
* 🔄 `rotate()`
* 🔄 `rotate()` negativo
* ⬆️ `translateY()`
* ➡️ `translateX()`
* 📐 `skew()`
* 📐 `skewX()`
* 📐 `skewY()`
* 🧊 `rotateX()`
* 🧊 `rotateY()`
* 🔄 `rotateZ()`
* 🚀 `translate3d()`
* 📦 `scale3d()`
* 🧮 `matrix()`
* ⚡ Combinação de múltiplas transformações

## 🛠️ Tecnologias utilizadas

* HTML5
* CSS3
* CSS `transform`
* CSS `transition`
* CSS 2D Transforms
* CSS 3D Transforms
* Hover Effects

## 📂 Estrutura do projeto

```text
CSS-Transform-Lab/
│
├── index.html
├── style.css
└── README.md
```

## 🚀 Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/CSS-Transform-Lab.git
```

### 2. Entre na pasta

```bash
cd CSS-Transform-Lab
```

### 3. Abra o projeto

Abra o arquivo:

```text
index.html
```

Você também pode utilizar uma extensão como **Live Server** no Visual Studio Code para executar o projeto localmente.

## 🎯 Objetivo

O objetivo deste projeto é servir como um **laboratório visual de CSS**, permitindo entender facilmente como diferentes valores da propriedade `transform` alteram a posição, tamanho, rotação e perspectiva de um elemento.

### Exemplo

```css
.box:hover {
    transform: rotate(25deg) scale(1.2);
}
```

Nesse exemplo, o elemento:

1. Gira `25deg`;
2. Aumenta seu tamanho em `20%`.

## 🧩 Exemplo de combinação

O projeto também demonstra como combinar diferentes transformações:

```css
.combo:hover {
    transform:
        translateY(-18px)
        rotate(12deg)
        scale(1.15)
        skewX(4deg);
}
```

Isso permite criar efeitos mais complexos utilizando apenas CSS.

## 💡 O que você pode aprender

Com este projeto, é possível praticar:

* Como utilizar `transform`;
* Diferença entre transformações 2D e 3D;
* Como utilizar `:hover`;
* Como criar animações e efeitos interativos;
* Como combinar diferentes transformações;
* Como utilizar `rotate`, `scale`, `translate` e `skew`;
* Introdução ao `matrix()` no CSS.

## 📸 Preview

> Passe o mouse sobre cada objeto para visualizar a transformação correspondente.

## 🔮 Possíveis melhorias

Algumas ideias para futuras versões:

* [ ] Adicionar controles para alterar os valores das transformações;
* [ ] Mostrar o código atualizado em tempo real;
* [ ] Adicionar botão para copiar o código;
* [ ] Adicionar mais transformações 3D;
* [ ] Criar modo escuro/claro;
* [ ] Adicionar animações personalizadas;
* [ ] Criar um editor de `transform` interativo;
* [ ] Adicionar exemplos de `transform-origin`;
* [ ] Adicionar exemplos utilizando `perspective()`.

## 👨‍💻 Autor

**Walter Prestes**

Projeto desenvolvido para estudos e prática de **HTML e CSS**, com foco em transformações e efeitos interativos.

---

⭐ Se este projeto foi útil para você, considere deixar uma estrela no repositório!

# 🍎 Sistema Simples de Controle de Estoque

## 📌 Situação-Problema

Uma pequena quitanda está iniciando sua transformação digital e precisa de uma aplicação simples que funcione diretamente no navegador para controlar o estoque de frutas.

Neste primeiro momento, o sistema:

- Não utiliza banco de dados  
- Funciona apenas enquanto a página estiver aberta  
- Armazena os dados utilizando arrays em JavaScript  

O objetivo é analisar, executar e compreender como o uso de arrays resolve o problema proposto.

---

## 🎯 Objetivo da Atividade

Compreender na prática:

- O que é um array
- Como armazenar múltiplos valores em uma única variável
- Como manipular arrays utilizando:
  - `push()`
  - `pop()`
  - `length`
  - `join()`
- Como atualizar o conteúdo da página usando o DOM (Document Object Model)

---

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript

---

## ▶️ Como Executar o Projeto

1. Abra o VS Code (ou outro editor de sua preferência).
2. Crie um arquivo chamado:

```
array_frutas.html
```

3. Copie o código fornecido pelo professor.
4. Salve o arquivo.
5. Abra o arquivo no navegador.
6. Teste as funcionalidades:
   - Clique em **Mostrar Fruta**
   - Clique em **Adicionar Fruta**
   - Clique em **Remover Última**

---

## 🧠 Conceitos Trabalhados

### 📦 Array

Um array é uma estrutura de dados que permite armazenar vários valores dentro de uma única variável.

No projeto:

```javascript
let frutas = [];
```

O array começa vazio e armazena as frutas digitadas pelo usuário.

---

### 🔼 Método `push()`

Adiciona um novo elemento ao final do array.

```javascript
frutas.push(novaFruta);
```

---

### 🔽 Método `pop()`

Remove o último elemento do array.

```javascript
frutas.pop();
```

---

### 📏 Propriedade `length`

Retorna a quantidade de elementos no array.

```javascript
frutas.length
```

---

### 🔗 Método `join()`

Transforma os elementos do array em uma string separada por vírgula.

```javascript
frutas.join(", ")
```

---

### 🌐 Manipulação do DOM

O sistema atualiza dinamicamente o conteúdo da página usando:

```javascript
document.getElementById("resultado").innerHTML
```

---

## 🔎 Problemas para Análise

Após executar o sistema, responda:

1. Onde as frutas estão sendo armazenadas?
2. O que acontece com o array ao clicar em:
   - “Adicionar Fruta”?
   - “Remover Última”?
3. Por que a função `mostrarFrutas()` é chamada após adicionar ou remover?
4. O que acontece ao tentar remover uma fruta com o array vazio?
5. Qual é o papel da propriedade `length`?

---

## ⚠️ Observação Importante

Existe um erro de digitação no código fornecido:

```javascript
frutas.lenght
```

O correto é:

```javascript
frutas.length
```

Esse erro impede que a verificação do tamanho do array funcione corretamente.

---

## 🚀 Possíveis Melhorias Futuras

- Corrigir o erro da propriedade `length`
- Impedir inserção de valores vazios
- Criar botão para limpar todo o estoque
- Utilizar LocalStorage para salvar dados
- Implementar banco de dados futuramente

---

## 📚 Aprendizado Desenvolvido

Este projeto permite praticar:

- Lógica de programação
- Manipulação de arrays
- Interação com o DOM
- Atualização dinâmica de conteúdo
- Estruturação de funções em JavaScript

---

## 👩‍💻 Autoria

Projeto desenvolvido como atividade prática para compreensão de arrays em JavaScript.


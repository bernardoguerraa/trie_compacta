# Trie Compacta em C++

Este projeto implementa uma **Trie Compacta** (ou árvore digital comprimida) em C++. A estrutura permite armazenar e gerenciar palavras de forma eficiente, com suporte a inserção, remoção, pesquisa e listagem por prefixo.

---

## 🧠 Conceito

- Cada nó pode ser:
  - **Interno**: contém filhos e representa ramificações.
  - **Externo**: contém uma palavra completa.
- A trie é comprimida: múltiplos caracteres são armazenados em um único nó externo, economizando espaço.
- A estrutura utiliza `std::map` para armazenar os filhos, facilitando a indexação por caracteres.

---

## ✨ Funcionalidades

- Inserir palavras (`insere`)
- Remover palavras (`remove`)
- Pesquisar palavras exatas (`pesquisa`)
- Listar palavras por prefixo (`palavrasPrefixo`)

---

## ▶️ Como usar

1. Compile o código:

```
g++ -o trie trie.cpp
```

2. Execute o programa:

```
./trie
```

3. Interaja com o menu:

```
Menu:
1 - Inserir
2 - Remover
3 - Pesquisar
4 - Prefixos
0 - Sair
```

---

## 🧪 Exemplo de uso

```
Menu:
1 - Inserir
Palavra: casa

1 - Inserir
Palavra: carro

3 - Pesquisar
Palavra: casa
Encontrada

4 - Prefixos
Prefixo: ca
- casa
- carro

2 - Remover
Palavra: casa

3 - Pesquisar
Palavra: casa
Nao encontrada
```

---

## 🛠️ Requisitos

- Compilador C++ compatível com C++11 ou superior (devido ao uso de `std::map`)
- Terminal para interação

---

## 📚 Aprendizado

Este projeto é útil para aprender:

- Árvores digitais (Tries) e sua compactação
- Manipulação de ponteiros em árvores
- Uso de `std::map` para gerenciamento dinâmico de filhos
- Operações de inserção, remoção e busca em estruturas hierárquicas

---

## 👨‍💻 Autor

**Bernardo Carvalho Guerra**


Este projeto está sob a licença MIT.

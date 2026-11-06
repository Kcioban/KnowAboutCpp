# KnowingCpp 📘

> PTBR and English documentation to learn **C++** step by step.
> Documentação em **PT-BR** e **Inglês** para aprender **C++** passo a passo.

[🇺🇸 English](#-english) | [🇧🇷 Português](#-português-brasil)

---

# 🇺🇸 English

## 📖 About

This repository is my space to **teach and share C++**. Each topic has a short
explanation, a code example, and exercises. It is made for beginners, but I
also include some intermediate content.

**Who is this for?**
- People who have never programmed before
- Students coming from other languages (Python, JavaScript, etc.)
- Anyone who wants to review C++ fundamentals

## 🗂️ Repository Structure

```
KnowAboutCpp/
├── README.md
├── 01-basics/
│   ├── 01-hello-world.md
│   ├── 02-variables-and-types.md
│   └── 03-input-and-output.md
├── 02-control-flow/
│   ├── 01-if-else.md
│   ├── 02-loops.md
│   └── 03-switch.md
├── 03-functions/
├── 04-arrays-and-strings/
├── 05-pointers-and-references/
├── 06-oop/
├── 07-stl/
├── exercises/
└── examples/
```

## 🧭 Learning Path

| # | Topic | Level | Status |
|---|-------|-------|--------|
| 1 | Hello World & compiling | Beginner | ✅ Done |
| 2 | Variables and data types | Beginner | ✅ Done |
| 3 | Conditionals and loops | Beginner | 🚧 In progress |
| 4 | Functions | Beginner | 📝 Planned |
| 5 | Arrays, vectors and strings | Intermediate | 📝 Planned |
| 6 | Pointers and references | Intermediate | 📝 Planned |
| 7 | Object-Oriented Programming | Intermediate | 📝 Planned |
| 8 | STL (containers, algorithms) | Advanced | 📝 Planned |

## 🚀 Quick Start

### 1. Install a compiler

- **Windows:** [MSYS2 / MinGW-w64](https://www.msys2.org/) or Visual Studio
- **Linux:** `sudo apt install g++`
- **macOS:** `xcode-select --install`

### 2. Clone this repo

```bash
git clone https://github.com/Kcioban/KnowAboutCpp.git
cd KnowAboutCpp
```

### 3. Compile and run

```bash
g++ -std=c++17 -Wall -o hello examples/hello.cpp
./hello
```

## 💡 Example: Hello World

```cpp
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

**What is happening here?**
- `#include <iostream>` imports the input/output library.
- `main()` is where every C++ program starts.
- `std::cout` prints text to the screen.
- `return 0;` tells the system the program ended successfully.

## ✏️ Exercises

Each topic folder has exercises. Try to solve them **before** looking at the solutions.

- [ ] Print your name and age
- [ ] Build a simple calculator
- [ ] Check whether a number is even or odd

## 🤝 Contributing

Contributions are welcome! You can:
1. Fix typos or improve explanations
2. Add new examples or exercises
3. Help with translations

Open an **Issue** or send a **Pull Request**.

## 📚 Recommended Resources

- [cppreference.com](https://en.cppreference.com/)
- [learncpp.com](https://www.learncpp.com/)
- [C++ Core Guidelines](https://isocpp.github.io/CppCoreGuidelines/)

---

# 🇧🇷 Português (Brasil)

## 📖 Sobre

Este repositório é o meu espaço para **ensinar e compartilhar C++**. Cada
tópico tem uma explicação curta, um exemplo de código e exercícios. É voltado
para iniciantes, mas também tem conteúdo intermediário.

**Para quem é?**
- Pessoas que nunca programaram
- Estudantes vindos de outras linguagens (Python, JavaScript, etc.)
- Quem quer revisar os fundamentos de C++

## 🗂️ Estrutura do Repositório

```
KnowAboutCpp/
├── README.md
├── 01-basics/            # Fundamentos
├── 02-control-flow/      # Controle de fluxo
├── 03-functions/         # Funções
├── 04-arrays-and-strings/
├── 05-pointers-and-references/
├── 06-oop/               # Orientação a Objetos
├── 07-stl/
├── exercises/            # Exercícios
└── examples/             # Exemplos
```

## 🧭 Trilha de Aprendizado

| # | Tópico | Nível | Status |
|---|--------|-------|--------|
| 1 | Olá, Mundo e compilação | Iniciante | ✅ Concluído |
| 2 | Variáveis e tipos de dados | Iniciante | ✅ Concluído |
| 3 | Condicionais e laços | Iniciante | 🚧 Em andamento |
| 4 | Funções | Iniciante | 📝 Planejado |
| 5 | Arrays, vetores e strings | Intermediário | 📝 Planejado |
| 6 | Ponteiros e referências | Intermediário | 📝 Planejado |
| 7 | Programação Orientada a Objetos | Intermediário | 📝 Planejado |
| 8 | STL (contêineres, algoritmos) | Avançado | 📝 Planejado |

## 🚀 Começando

### 1. Instale um compilador

- **Windows:** [MSYS2 / MinGW-w64](https://www.msys2.org/) ou Visual Studio
- **Linux:** `sudo apt install g++`
- **macOS:** `xcode-select --install`

### 2. Clone este repositório

```bash
git clone https://github.com/Kcioban/KnowAboutCpp.git
cd KnowAboutCpp
```

### 3. Compile e execute

```bash
g++ -std=c++17 -Wall -o ola examples/hello.cpp
./ola
```

## 💡 Exemplo: Olá, Mundo

```cpp
#include <iostream>

int main() {
    std::cout << "Olá, Mundo!" << std::endl;
    return 0;
}
```

**O que está acontecendo aqui?**
- `#include <iostream>` importa a biblioteca de entrada e saída.
- `main()` é o ponto onde todo programa C++ começa.
- `std::cout` exibe texto na tela.
- `return 0;` informa ao sistema que o programa terminou com sucesso.

## ✏️ Exercícios

Cada pasta de tópico tem exercícios. Tente resolver **antes** de olhar as soluções.

- [ ] Imprimir seu nome e idade
- [ ] Criar uma calculadora simples
- [ ] Verificar se um número é par ou ímpar

## 🤝 Contribuindo

Contribuições são bem-vindas! Você pode:
1. Corrigir erros de digitação ou melhorar explicações
2. Adicionar novos exemplos ou exercícios
3. Ajudar com traduções

Abra uma **Issue** ou envie um **Pull Request**.

## 📚 Recursos Recomendados

- [cppreference.com](https://pt.cppreference.com/)
- [learncpp.com](https://www.learncpp.com/)
- [C++ Core Guidelines](https://isocpp.github.io/CppCoreGuidelines/)

---

## 👤 Author / Autor

**Kcioban** · [GitHub](https://github.com/Kcioban)

## 📄 License / Licença

Distributed under the MIT License. / Distribuído sob a Licença MIT.

⭐ If this repo helped you, leave a star! / Se este repositório te ajudou, deixe uma estrela!

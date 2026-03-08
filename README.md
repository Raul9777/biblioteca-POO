# 📚 Sistema de Biblioteca - Programação Orientada a Objetos

## 📖 Descrição do Projeto

Este projeto implementa um **sistema simples de gerenciamento de itens de uma biblioteca**, desenvolvido em **Python** utilizando os conceitos fundamentais de **Programação Orientada a Objetos (POO)**.

O sistema permite cadastrar diferentes tipos de itens da biblioteca, realizar empréstimos e devoluções, além de listar os itens disponíveis.

Foram aplicados conceitos importantes como:

* **Encapsulamento**
* **Herança**
* **Polimorfismo**
* **Organização modular do código**
* **Controle de versão com Git**

---

# 🧠 Conceitos de POO aplicados

## 🔒 Encapsulamento

Os atributos das classes são privados utilizando `__atributo`, garantindo maior controle sobre o acesso aos dados.

Exemplo:

```python
self.__codigo
self.__titulo
self.__ano
self.__disponivel
```

O acesso é feito através de **getters e setters** com validações.

---

## 🧬 Herança

O sistema possui uma **classe base** chamada:

```
ItemBiblioteca
```

Dela herdam as classes:

* `Livro`
* `Revista`

Isso evita repetição de código e facilita manutenção.

---

## 🔁 Polimorfismo

O método:

```
exibir_detalhes()
```

é implementado na classe base e **sobrescrito nas subclasses**, permitindo comportamentos diferentes dependendo do tipo do item.

Exemplo:

* Livro mostra **autor e número de páginas**
* Revista mostra **edição e mês**

---

# 📂 Estrutura do Projeto

```
biblioteca-poo/
│
├── main.py
├── item_biblioteca.py
├── livro.py
├── revista.py
├── biblioteca.py
└── README.md
```

### Arquivos

| Arquivo              | Função                                     |
| -------------------- | ------------------------------------------ |
| `main.py`            | Interface do sistema (menu no terminal)    |
| `item_biblioteca.py` | Classe base dos itens da biblioteca        |
| `livro.py`           | Classe Livro que herda de ItemBiblioteca   |
| `revista.py`         | Classe Revista que herda de ItemBiblioteca |
| `biblioteca.py`      | Classe responsável por gerenciar os itens  |
| `README.md`          | Documentação do projeto                    |

---

# ⚙️ Funcionalidades do Sistema

O sistema permite:

✅ Cadastrar **Livros**
✅ Cadastrar **Revistas**
✅ Listar itens da biblioteca
✅ Realizar **empréstimo de itens**
✅ Realizar **devolução de itens**
✅ Buscar item pelo **código**

---

# 🖥️ Menu do Sistema

Ao executar o programa, o seguinte menu será exibido:

```
1. Cadastrar Livro
2. Cadastrar Revista
3. Listar Itens
4. Emprestar Item
5. Devolver Item
6. Sair
```

O usuário pode interagir com o sistema digitando o número correspondente à operação desejada.

---

# ▶️ Como Executar o Projeto

## 1️⃣ Clonar o repositório

```bash
git clone https://github.com/seu-usuario/biblioteca-poo.git
```

## 2️⃣ Entrar na pasta do projeto

```bash
cd biblioteca-poo
```

## 3️⃣ Executar o sistema

```bash
python main.py
```

---

# 💻 Exemplo de Uso

Exemplo de cadastro de livro:

```
1
Código: 101
Título: Clean Code
Ano: 2008
Autor: Robert C. Martin
Número de páginas: 464
```

Listando itens:

```
--- Livro ---
Código: 101
Título: Clean Code
Ano: 2008
Autor: Robert C. Martin
Páginas: 464
Disponível: True
```

---

# 🛠️ Tecnologias Utilizadas

* **Python 3**
* **Programação Orientada a Objetos**
* **Git**
* **GitHub**

---

# 👨‍💻 Autor

Projeto desenvolvido como atividade acadêmica para prática de **Programação Orientada a Objetos em Python**.

---

# 📌 Observações

Este projeto tem fins **educacionais**, focado na aplicação prática dos conceitos de **POO**, organização de código e versionamento com **Git**.

# 📐 Projeto de Figuras Geométricas Planas com POO

Este repositório foi criado para mostrar, de forma prática e didática,  aplicações mais legais da **Programação Orientada a Objetos (POO)**, aplicados no cálculo de áreas de figuras geométricas planas.  

Usando classes para representar cada figura e organizando tudo em pacotes, o projeto reforça princípios como:

- ◻️ Abstrção
- 🔒 Encapsulamento  
- 🧬 Herança  


---

## 🎯 Objetivo

Criar formas para calcular áreas (com e sem retorno de valor) de várias **figuras planas**, aplicando os fundamentos da **POO em Java**. 🚀

---

## ⚙️ Conceitos de POO Aplicados

### ◻️ Abstração

📁 **Pacote:** `br.edu.figurasgeometricasplanas`  
Oculta detalhes internos das implementações e mostra só o que importa. Cada figura é representada por uma classe abstrata que define o essencial.  

📁 **Pacote:** `br.edu.principal`  
Contém a classe principal que testa as figuras.

📎 **Ver PDF:** _Calculadora Formas Geométricas_

#### ◻️ Diagrama de Abstração
📎 [Ver Diagrama de Abstração (PDF)](./CalculadoraFormasGeométricasHerença.pdf)

---

### 🔐 Encapsulamento

📁 **Pacotes:**  
- `br.edu.figurasgeometricasplanas` → Figuras como Triângulo, Retângulo, Losango etc.  
- `br.edu.figurasgeometricasespaciais` → Figuras como Cubo, Esfera, Cone etc.  
- `br.edu.principal` → Executa os testes com métodos públicos (`get` e `set`)

Cada classe protege seus atributos e só permite acesso/controlado por métodos.

📎 **Ver PDF:** _Calculadora Formas Geométricas_

#### 🧬 Diagrama de Herança
#### 🧬 Diagrama de Herança
📎 [Ver Diagrama de Herança (PDF)](./CalculadoraFormaGeométricasHerença.pdf)

---

### 🧬 Herança

📁 **Pacotes:**  
- `br.edu.figurasgeometricasplanas` → Subclasses herdam de `FiguraPlana`  
- `br.edu.figurasgeometricasespaciais` → Subclasses herdam de `FiguraEspacial`  
- `br.edu.principal` → Executa o programa principal

As subclasses reaproveitam atributos e comportamentos das superclasses — menos repetição, mais organização!

📌 **Diagrama UML**  
Mostra a hierarquia entre classes e como o código é reutilizado.

📎 **Ver PDF:** _Calculadora Formas Geométricas_

#### 🧬 Diagrama de Herança
📎 [Ver Diagrama de Herança (PDF)](./CalculadoraFormaGeométricasHerença.pdf)

---



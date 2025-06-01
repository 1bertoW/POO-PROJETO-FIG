# 📐 Projeto de Figuras Geométricas Planas com POO

🎯 **Programação Orientada a Objetos aplicada a Figuras Geométricas Planas**

Este repositório foi criado para mostrar, de forma prática e didática, os conceitos principais da **Programação Orientada a Objetos (POO)**, aplicados no cálculo de áreas de figuras geométricas planas.  

Usando classes para representar cada figura e organizando tudo em pacotes, o projeto reforça princípios como:

- 🔒 Encapsulamento  
- 🧬 Herança  
- 🧱 Modularidade  
- 🧠 Coesão  
- ♻️ Reutilização de código

---

## 🎯 Objetivo

Criar métodos para calcular áreas (com e sem retorno de valor) de várias **figuras planas**, aplicando os fundamentos da **POO em Java**. 🚀

---

## ⚙️ Conceitos de POO Aplicados

### ◻️ Abstração

📁 **Pacote:** `br.edu.figurasgeometricasplanas`  
Oculta detalhes internos das implementações e mostra só o que importa. Cada figura é representada por uma classe abstrata que define o essencial.  

📁 **Pacote:** `br.edu.principal`  
Contém a classe principal que testa as figuras.

📌 **Diagrama UML**  
Representa as relações entre classes e pacotes, destacando a organização e os métodos.

📎 **Ver PDF:** _Calculadora Formas Geométricas_

---

### 🔐 Encapsulamento

📁 **Pacotes:**  
- `br.edu.figurasgeometricasplanas` → Figuras como Triângulo, Retângulo, Losango etc.  
- `br.edu.figurasgeometricasespaciais` → Figuras como Cubo, Esfera, Cone etc.  
- `br.edu.principal` → Executa os testes com métodos públicos (`get` e `set`)

Cada classe protege seus atributos e só permite acesso/controlado por métodos.

📌 **Diagrama UML**  
Mostra como os dados são encapsulados, acessados apenas via métodos públicos.

📎 **Ver PDF:** _Calculadora Formas Geométricas_

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

---

🧠 **Dica:** Se quiser visualizar os diagramas diretamente no GitHub, você pode incluir os PDFs na pasta do projeto e usar um link assim:

```markdown
[📄 Acessar Diagrama de Abstração](./diagramas/abstracao.pdf)

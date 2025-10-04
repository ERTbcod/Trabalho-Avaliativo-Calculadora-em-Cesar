# 💻 Trabalho Avaliativo: Calculadora em Assembly para o Computador CESAR

**Curso:** Engenharia de Controle e Automação 
**Disciplina:** Sistemas Computacionais I

## Integrantes
- Erick Rodrigues Tavares  
- Gabriel Alonso de Castro  
- Otávio Augusto de Souza Silva

## Descrição
Este repositório contém o código-fonte em **Assembly** e o relatório do trabalho avaliativo focado no desenvolvimento de uma calculadora funcional para o **Computador Hipotético CESAR**. O programa foi montado utilizando o simulador **Daedalus** e implementa as quatro operações aritméticas básicas, com a capacidade de processar números com múltiplos dígitos.

## Objetivo
O objetivo principal deste projeto foi aplicar de forma prática os conceitos de programação em baixo nível, abordados na disciplina de Sistemas Computacionais I. Os desafios incluíram:
- **Manipulação de I/O:** Implementar rotinas para ler sequências de caracteres (dígitos) do teclado e convertê-las para um valor numérico único.
- **Lógica Aritmética:** Criar algoritmos para as operações de multiplicação e divisão, que não possuem instruções nativas na arquitetura CESAR, utilizando laços e somas/subtrações sucessivas.
- **Estrutura de Software:** Organizar o código de forma modular, utilizando sub-rotinas para tarefas específicas como leitura, exibição e cálculos auxiliares.
- **Conversão de Base:** Desenvolver uma lógica para exibir o resultado final no visor, convertendo um valor binário interno de volta para uma sequência de caracteres decimais.

---

## ✨ Funcionalidades do Projeto

- **Entrada de Múltiplos Dígitos:** A calculadora aceita números com mais de um dígito (ex: `7`, `45`).
- **Quatro Operações Básicas:** Suporte completo para Adição (`+`), Subtração (`-`), Multiplicação (`*`) e Divisão (`/`).
- **Exibição de Resultados:** O resultado das operações é exibido corretamente no visor de LEDs, também com suporte a múltiplos dígitos.
- **Código Modular:** O programa é estruturado com sub-rotinas para facilitar a leitura e a manutenção.

---

## 🔧 Arquitetura e Ferramentas

| Componente | Detalhe |
| :--- | :--- |
| **Linguagem** | Assembly (para CESAR) |
| **Arquitetura** | CESAR (Simplificação do PDP-11) |
| **Largura** | 16 bits (Dados e Endereços) |
| **Montador** | Daedalus |
| **Periféricos** | Teclado e Visor Digital (I/O Mapeado na Memória) |

---

## 📄 Relatório do Projeto

O relatório detalhará todo o processo de desenvolvimento, a lógica por trás dos algoritmos, os desafios encontrados e as capturas de tela da calculadora em execução.

### Relatório em PDF: [Relatório Calculadora Cesar.pdf](https://github.com/user-attachments/files/22704748/Relatorio.Calculadora.Cesar.pdf)


### Link de acesso ao relatório (Google Documentos): https://docs.google.com/document/d/1_u5LMoMGd-Ae_U-MVM1JDoKXRbAWKofZGnAiKjydHIc/edit?usp=sharing

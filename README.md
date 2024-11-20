# LocadoraCarros.py 🚗💻
Um projeto desenvolvido durante o curso Data Science da ASIMOV, com o objetivo de criar um sistema de locação de veículos funcional e interativo.

# 🎯 Objetivo do Projeto
Este programa tem como proposta:

Criar um sistema simples e eficiente para locação de carros.  
Disponibilizar uma interface onde é possível:  
Verificar os carros disponíveis no portfólio.  
Realizar o aluguel de veículos.  
Efetuar a devolução de veículos alugados.  

# 🔧 Solução Desenvolvida
A estrutura do programa foi construída utilizando dicionários para gerenciar:  

Modelos de carros disponíveis.  
Valores das diárias de cada veículo.  
Lista de veículos alugados.  

### **Funcionamento do Programa** 

1. **Inicialização:**
![TelaIniciallocadoracarros](https://github.com/user-attachments/assets/7ca6ac86-4098-4c84-aed6-276bdbb8785a)

  - O portfólio inicia com um exemplo de carro disponível.
  - A partir do menu inicial, o usuário pode adicionar novos veículos ao portfólio.
2. **Menu Principal:**
  - **Opção Alugar:**
    - Lista os carros disponíveis no portfólio.
    - Permite ao usuário selecionar um carro e informar a quantidade de dias para locação.
    - Calcula o valor total da reserva e solicita confirmação do usuário.
    - Após a confirmação, o carro é removido do portfólio e adicionado à lista de veículos alugados.
  - **Opção Devolução:**
    - Exibe os carros atualmente alugados.
    - Permite ao usuário selecionar um veículo para devolução.
    - Após a devolução, o veículo é reintegrado ao portfólio e removido da lista de alugados.
  - **Opção Adicionar:**
    - Permite que o usuário adicione um carro e o valor da diária ao portifólio

## 📋 Funcionalidades
  - Adicionar novos carros ao portfólio.
  - Listar veículos disponíveis para locação.
  - Calcular e confirmar reservas com base na quantidade de dias escolhidos.
  - Gerenciar lista de veículos alugados.
  - Realizar devoluções de maneira simples e prática.

## 📂 Estrutura do Projeto

LocadoraCarros.py  
├── Menu Principal  
│   ├── Adicionar Carro  
│   ├── Alugar Veículo  
│   │   └── Seleção de Dias e Confirmação  
│   ├── Devolução de Veículo  
│   └── Sair do Programa  

## 💡 Tecnologias Utilizadas
- Python:
  - Manipulação de dicionários.
  - Interação com o usuário via terminal.
  - Estruturas de repetição e condições para navegação no menu.

## 📖 Sobre o Curso
Este projeto é parte do curso Data Science da ASIMOV, que busca ensinar habilidades práticas e teóricas para resolver problemas reais utilizando ciência de dados e programação.

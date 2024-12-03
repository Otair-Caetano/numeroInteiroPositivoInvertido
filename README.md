# Projeto: Inversão de Números de Três Dígitos

## Descrição
Este projeto implementa uma solução simples em linguagem C para inverter os dígitos de um número inteiro de três dígitos. O programa utiliza conceitos básicos de manipulação de números inteiros, como operações matemáticas com módulo e divisão, além de controle de fluxo com `while` e condicionais `if-else`.

O programa foi desenvolvido como uma tarefa prática no curso **Embarca Tech**, promovido pelo **HBr Instituto HARDWARE BR**, uma iniciativa que visa formar profissionais na área de sistemas embarcados e desenvolvimento em baixo nível. O curso é sediado no Parque Tecnológico da UNICAMP, Campinas-SP.

---

## Objetivo do Programa
1. Solicitar ao usuário um número inteiro de três dígitos.
2. Verificar se o número fornecido está no intervalo válido (100 a 999).
3. Calcular e exibir o número com os dígitos invertidos.
4. Exibir uma mensagem de erro caso o número fornecido seja inválido.

---

## Estrutura do Código

### Função: `inverteNumero`
- **Entrada:** Recebe um número inteiro (`int numero`).
- **Processamento:** Inverte os dígitos do número utilizando:
  - Operador `%` (módulo): Para capturar o último dígito.
  - Operador `/` (divisão): Para eliminar o último dígito do número original.
- **Saída:** Retorna o número invertido.

### Função `main`
1. Solicita ao usuário um número.
2. Valida o intervalo (`100–999`).
3. Exibe o número invertido ou uma mensagem de erro para valores fora do intervalo.

---

## Requisitos
- Compilador C (GCC, Clang ou similar).
- Ambiente de desenvolvimento compatível com C (Visual Studio Code, Code::Blocks, etc.).

---

## Como executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/Otair-Caetano/numeroInteiroPositivoInvertido/
](https://github.com/Otair-Caetano/numeroInteiroPositivoInvertido/)

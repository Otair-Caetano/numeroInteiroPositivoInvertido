# Projeto: Inversão de Números de Três Dígitos

## Descrição
Este projeto implementa uma solução simples em linguagem C para inverter os dígitos de um número inteiro de três dígitos. Ele utiliza conceitos básicos de manipulação de números inteiros, como operações matemáticas com módulo e divisão, além de controle de fluxo com `while` e condicionais `if-else`.

O programa foi desenvolvido como parte do curso **Embarca Tech**, promovido pelo **HBr Instituto HARDWARE BR**, uma iniciativa que visa formar profissionais na área de sistemas embarcados e desenvolvimento em linguagem C de baixo nível. O curso é sediado no Parque Tecnológico da UNICAMP, Campinas-SP.

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

## Como Compilar e Executar

### Compilação:
```bash
gcc -o inverteNumero inverteNumero
### Execução:
./inverteNumero
---
Aplicações e Benefícios
Didática: Útil para quem está aprendendo programação em C, pois aborda manipulação de variáveis, validação de entrada e uso de funções.
Sistemas embarcados: O controle de entrada e saída de dados é essencial para projetos embarcados.
Lógica matemática: O projeto demonstra conceitos fundamentais de manipulação numérica.
Sobre o Curso Embarca Tech
O Embarca Tech é uma iniciativa de capacitação focada no desenvolvimento de sistemas embarcados, hardware e programação em linguagens de baixo nível como C. O curso é promovido pelo HBr Instituto HARDWARE BR e está localizado no Parque Tecnológico da UNICAMP, em Campinas, São Paulo.

Para mais informações sobre o curso e outros projetos, visite o site oficial do HBr Instituto HARDWARE BR.





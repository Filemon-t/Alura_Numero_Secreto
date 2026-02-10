# Jogo do Número Secreto

Projeto desenvolvido durante o curso **Lógica de Programação: explore funções e listas**, da **Alura**, com o objetivo de praticar os fundamentos da lógica de programação utilizando **JavaScript**.
O jogo consiste em adivinhar um **número secreto** gerado aleatoriamente dentro de um limite definido, recebendo dicas se o número é maior ou menor a cada tentativa.

## O que foi aprendido no curso

Durante o desenvolvimento deste projeto, foram trabalhados os seguintes conceitos:

 - Fundamentos da lógica de programação
 - Declaração e uso de variáveis e constantes
 - Estruturas condicionais (`if` / `else`)
 - Criação e utilização de funções
 - Manipulação de listas (arrays)
 - Uso de laços lógicos e validações
 - Geração de números aleatórios com `Math.random()`
 - Controle de tentativas do usuário
 - Manipulação do DOM (`querySelector`, `innerHTML`)
 - Validação de entradas do usuário (valores vazios, inválidos ou fora do limite)
 - Organização e reutilização de código
 - Implementação de acessibilidade com feedback por voz usando `responsiveVoice`

## Como funciona o jogo

- O sistema gera um número secreto aleatório entre **1 e o limite definido**.
- O usuário digita um número no campo de entrada.
- O jogo informa se o número secreto é **maior ou menor** que o chute.
- Ao acertar, o jogo exibe a quantidade de tentativas utilizadas.
- O botão **Chutar** permite começar uma nova rodada com um novo número secreto.

## Funcionalidades adicionais implementadas

Além do que foi proposto no curso, foram implementadas funcionalidades extras por iniciativa própria, com o objetivo de tornar o jogo mais completo:

- Validação de campo vazio
- Tratamento de valores fora do limite permitido
- Validação de valores inválidos, como números decimais ou negativos
- Mensagens de erro mais claras e informativas para o usuário
- Melhoria na lógica de entrada de dados

Essas validações não faziam parte do conteúdo original do curso e foram adicionadas como forma de aprofundar os conhecimentos em JavaScript.

## Tecnologias utilizadas

 - JavaScript
 - HTML
 - CSS
 - Biblioteca ResponsiveVoice (para feedback de voz)

## Objetivo do projeto

Este projeto tem caráter **educacional**, com foco no aprendizado prático de lógica de programação, funções, listas e interação com o usuário, servindo como base para projetos mais complexos no futuro.

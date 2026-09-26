# Exercícios de Lógica em Python: Estruturas de Repetição e Acumuladores

Este repositório contém um script prático com quatro exercícios independentes que demonstram o uso de laços `for`, manipulação da função `range()`, formatação de saída (`print`) e lógica condicional. 

O script pausa e limpa a tela do terminal entre cada exercício para proporcionar uma experiência interativa e organizada.

## Funcionalidades do Código

O programa é dividido nas seguintes seções:

1. **Tabuada Interativa:**
   - Solicita um número inteiro ao usuário e gera a tabuada (de 1 a 10) para esse número.
   - Demonstra a formatação de strings dinâmicas (f-strings).

2. **Sequência de Pares (Saída em Linha):**
   - Imprime os números pares de 0 a 20.
   - Utiliza o argumento `end=""` na função `print` para que os números apareçam lado a lado, em vez de um por linha.

3. **Análise de Notas (Contadores e Acumuladores):**
   - Recebe 5 notas inseridas pelo usuário.
   - Utiliza uma variável **acumuladora** (`soma`) para calcular a média geral da turma.
   - Utiliza uma variável **contadora** (`maior`) combinada com uma condicional `if` para verificar e contar quantas dessas notas foram superiores a 6.

4. **Contagem Regressiva (Saída em Linha):**
   - Realiza uma contagem de 10 até 1 utilizando um passo negativo no `range(10, 0, -1)`.
   - Também utiliza o `end=" "` para manter os números na mesma linha.

## Conceitos Aplicados

* **Loops `for`:** Iteração sobre sequências e repetição de tarefas.
* **Manipulação de `range`:** Uso de diferentes parâmetros de início, fim e passo (positivo e negativo).
* **Variáveis Contadoras e Acumuladoras:** Essenciais para somar valores iterativos e contar ocorrências que satisfazem uma condição.
* **Controle do Terminal:** Uso de `os.system` para limpar a tela (`cls` no Windows, `clear` no Linux/Mac) e melhorar a legibilidade.

## Como Executar

1. Certifique-se de ter o Python instalado na sua máquina.
2. Salve o código em um arquivo (por exemplo, `exercicios_lacos.py`).
3. Abra o terminal, navegue até a pasta do arquivo e execute:
   ```bash
   python exercicios_lacos.py
   ```
4. Siga as instruções na tela, digitando os valores solicitados e pressionando `Enter` para avançar pelas etapas.

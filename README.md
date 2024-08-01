# PortuPy

Uma pseudolinguagem criada com o propósito de ensinar os conceitos fundamentais da lógica de programação de uma forma divertida e acessível, especialmente para estudantes iniciantes.  
Com sua sintaxe semelhante a do Python, o objetivo do uso dessa pseudolinguagem é que futuramente o aluno progride para uma linguagem de programação, nesse caso, preferencialmente, o Python, pela sua facilidade de aprendizado.

- Em Português
- Fácil
- Amigável
- Ideal para iniciantes

## Requisitos

- Windows
- Python Instalado

## Baixe Aqui
[Baixar PortuPy (clique aqui)](assets/download/PortuPy.exe)


# Documentação Básica

## Proposta PortuPy

O PortuPy é uma pseudolinguagem que foi criada com o propósito de ensinar os conceitos fundamentais da programação de uma forma divertida e acessível, especialmente para estudantes iniciantes.

PortuPy tem sua sintaxe semelhante a do Python (linguagem de programação real, muito usada no mercado). O objetivo do uso dessa pseudolinguagem é que futuramente o aluno progride para uma linguagem de programação, nesse caso, preferenciamento, o Python, pela sua facilidade de aprendizado. Essa ferramenta usa palavras em português para representar comandos de programação, o que o torna mais acessível para pessoas que falam a língua portuguesa. Isso é ótimo para iniciantes, pois elimina a barreira do idioma.

Além disso, mesmo sendo uma pseudolinguagem, o PortuPy é projetado para ensinar conceitos fundamentais de programação, como variáveis, estruturas condicionais, loops e funções. Os estudantes podem aprender esses conceitos de forma interativa e prática.

Em resumo, o PortuPy é uma pseudolinguagem de programação que se destaca por sua simplicidade e acessibilidade. Ele é uma ferramenta valiosa para aqueles que estão dando os primeiros passos na programação e desejam entender os conceitos básicos de uma forma amigável e envolvente. Se você está começando a estudar programação, o PortuPy pode ser uma introdução divertida e educativa a este mundo fascinante.

## Comandos de Entrada e Saída

Para receber entrada do usuário em PortuPy, você pode usar a função `entrada()`:

```python
nome = entrada("Digite seu nome: ")
```

Para exibir saída, use a função `escrever()`:

```python
escrever("Olá, " + nome)
```

## Principais Tipos de Dados

Python suporta diversos tipos de dados, incluindo:

- Números inteiros (inteiro)
- Números decimais (decimal)
- Carateres (caracter)
- Lógicos (logico)

```python
#caracter
nome = "Joao"

#inteiro
idade = 15

#decimal
altura = 1.75

#logico
trabalha = Verdadeiro
```

## Operadores em PortuPy

### Operadores Aritméticos

- `+` (Adição)
- `-` (Subtração)
- `*` (Multiplicação)
- `/` (Divisão)
- `//` (Divisão de Inteira)
- `%` (Módulo - Resto da Divisão)
- `**` (Exponenciação)

### Operadores de Comparação

- `==` (Igual a)
- `!=` (Diferente de)
- `<` (Menor que)
- `>` (Maior que)
- `<=` (Menor ou igual a)
- `>=` (Maior ou igual a)

### Operadores Lógicos

- `and` (E lógico)
- `or` (Ou lógico)
- `not` (Negação lógica)

### Operadores de Identidade

- `is` (É)
- `is not` (Não é)

### Operadores de Associação

- `in` (Está em)
- `not in` (Não está em)

### Operadores de Atribuição

- `=` (Atribuição)
- `+=` (Adição e atribuição)
- `-=` (Subtração e atribuição)
- `*=` (Multiplicação e atribuição)
- `/=` (Divisão e atribuição)
- `%=` (Módulo e atribuição)
- `//=` (Divisão de Piso e atribuição)
- `**=` (Exponenciação e atribuição)

### Operador de Concatenação de Strings

- `+` (Usado para concatenar strings)

## Entendendo Estruturas de Condição

As estruturas de condição são usadas para criar lógica condicional em programas. Elas permitem que você tome decisões com base em condições específicas.

### Exemplo de Estrutura de Condição:

```python
# Solicita ao usuário que insira um número
numero = decimal(entrada("Digite um número: "))

# Verifica se o número é positivo
se numero > 0:
    escrever("O número é positivo.")
e se numero == 0:
    escrever("O número é zero.")
senao:
    escrever("O número é negativo.")
```

Neste exemplo em Python, estamos verificando se a variável `idade` é maior ou igual a 18. Se a condição for verdadeira, o programa imprime "Você é maior de idade". Caso contrário, ele imprime "Você é menor de idade".

### Principais Estruturas de Condição:

- **se**: Usado para verificar se uma condição é verdadeira.
- **e se**: Permite verificar várias condições.
- **senao**: Fornece uma alternativa caso a condição do **se** seja falsa.

As estruturas de condição são fundamentais para criar programas que podem se adaptar a diferentes situações e tomar decisões com base em informações variáveis.

## Entendendo Estruturas de Repetição

As estruturas de repetição são usadas para executar um bloco de código várias vezes. Elas são essenciais para automatizar tarefas repetitivas em programas.

### Estrutura de Repetição `para`:

```python
nomes = ["Alice", "Bob", "Carol", "David"]
para nome em nomes:
    escrever("Olá, " + nome)
```

```python
para x em faixa(10):
    escrever(x)
```

Neste exemplo em Python, usamos um loop `para` para percorrer a lista de nomes e imprimir uma saudação para cada pessoa na lista.

### Estrutura de Repetição `enquanto`:

```python
contador = 0

enquanto contador < 5:
    escrever("Contagem: " + caracter(contador))
    contador += 1
```

Neste exemplo, usamos um loop `enquanto` para contar de 0 a 4. O loop continuará executando até que a condição `contador < 5` seja falsa.

As estruturas de repetição são cruciais para a automação e repetição de tarefas em programas, economizando tempo e esforço.

## Funções em Programação

Funções são blocos de código que podem ser reutilizados para realizar tarefas específicas. Elas ajudam a organizar e modularizar um programa.

### Definindo e Chamando Funções:

```python
# Definindo uma função
funcao saudacao(nome):
    devolva "Olá, " + nome

# Chamando a função
mensagem = saudacao("Alice")
escrever(mensagem)
```

Neste exemplo em PortuPy, definimos uma função chamada `saudacao` que aceita um argumento `nome` e retorna uma mensagem de saudação. Em seguida, chamamos a função e armazenamos a mensagem resultante em uma variável.

### Funções com Parâmetros Opcionais:

```python
# Função com parâmetro opcional
funcao boas_vindas(nome, cidade="Desconhecida"):
    return "Olá, " + nome + " de " + cidade

# Chamando a função
mensagem = boas_vindas("Bob")
escrever(mensagem)
```

Neste exemplo, a função `boas_vindas` aceita dois parâmetros, sendo que `cidade` tem um valor padrão opcional. Se a cidade não for fornecida, ela será definida como "Desconhecida" por padrão.

As funções são uma parte fundamental da programação, permitindo a criação de blocos de código reutilizáveis para executar tarefas específicas.

## Tratamento de Exceções

O tratamento de exceções é uma abordagem para lidar com erros de forma controlada. Utiliza blocos tentar e deuerro para envolver código que pode gerar exceções. Se uma exceção ocorrer, o controle é transferido para o bloco de exceção, onde é possível realizar ações específicas para lidar com o erro.

### Instrução Raise:

A instrução raise é utilizada para gerar manualmente uma exceção. Isso é útil quando você deseja sinalizar um erro específico em determinada situação, permitindo um tratamento personalizado.

```python
funcao exemplo_divisao(dividendo, divisor):
    tentar:
        se divisor == 0:
            errar ErroDeValor("Divisão por zero não é permitida.")
        resultado = dividendo / divisor
    deuerro ErroDeValor apelidar ve:
        escrever(f"Erro: {ve}")
    deuerro ErroDeTipo:
        escrever("Erro: Certifique-se de que os operandos são números.")
    senao:
        escrever("A divisão foi bem-sucedida. Resultado:", resultado)
    porfim:
        escrever("Esta parte sempre será executada, independentemente de haver uma exceção ou não.")

# Exemplos de uso
exemplo_divisao(10, 2)  # Saída esperada: A divisão foi bem-sucedida. Resultado: 5.0
exemplo_divisao(10, 0)  # Saída esperada: Erro: Divisão por zero não é permitida.
exemplo_divisao("10", 2)  # Saída esperada: Erro: Certifique-se de que os operandos são números.
```

## Palavras-chave e Comandos em Python

```python
Verdadeiro (True): Valor booleano verdadeiro.
Falso (False): Valor booleano falso.
semlocal (nonlocal): Indica uma variável não local.
continue (continue): Pula para a próxima iteração do loop.
porfim (finally): Bloco de código que é sempre executado, independentemente de exceções.
devolva (return): Retorna um valor de uma função.
deuerro (except): Bloco de código executado em caso de exceção.
importe (import): Importa um módulo ou pacote.
global (global): Indica uma variável global.
afirmar (assert): Verifica se uma expressão é verdadeira, gerando uma exceção se for falsa.
fazer (lambda): Cria funções anônimas.
classe (class): Define uma classe.
gerador (yield): Pausa uma função geradora e envia um valor para o chamador.
enquanto (while): Loop de repetição enquanto uma condição é verdadeira.
errar (raise): Levanta uma exceção.
quebrar (break): Sai de um loop.
e se (elif): Se a condição anterior for falsa, testa uma nova condição.
se (if): Testa uma condição.
senao (else): Bloco de código executado se a condição do "if" for falsa.
senao (else:): Bloco de código executado se a condição do "if" for falsa.
de (from): Importa partes específicas de um módulo.
Nada (None): Valor nulo.
passar (pass): Sentença nula (não faz nada).
com (with): Gerencia recursos usando um contexto.
para (for): Loop de repetição para iterar sobre uma sequência.
tentar (try:): Bloco de código onde exceções podem ocorrer.
funcao (def): Define uma função.
nao (not): Operador lógico de negação.
remova (del): Remove um item de uma coleção.
apelidar (as): Renomeia um módulo ou um objeto durante a importação.
ou (or): Operador lógico "ou".
em (in): Verifica se um valor está presente em uma sequência.
e (and): Operador lógico "e".
é (is): Verifica se dois objetos são o mesmo.
```

## Exemplo Prático em PortuPy

```python
funcao saudacao(nome, cidade="Desconhecida"):
    return "Olá, " + nome + " de " + cidade

# Chamando a função
mensagem = saudacao("Bob")
escrever(mensagem)
```

Neste exemplo, a função `saudacao` é chamada com um parâmetro obrigatório (`nome`) e um parâmetro opcional (`cidade`), resultando na mensagem "Olá, Bob de Desconhecida".



# Repositório do PortuPy

Colabore com a gente e ajude a melhorar esta ferramenta!
[Reposiório PortuPy](https://github.com/lkscomk/PortuPy)

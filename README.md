# Conversor de Temperaturas em C

![Linguagem C](https://img.shields.io/badge/Linguagem-C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Categoria](https://img.shields.io/badge/Categoria-Conversão_de_Unidades-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Projeto_Acadêmico-success?style=for-the-badge)

## Sobre o projeto

O Conversor de Temperaturas em C é um projeto acadêmico desenvolvido para praticar conceitos fundamentais da programação por meio de um problema cotidiano: a conversão de valores entre diferentes escalas de temperatura.

O programa apresenta uma interface textual interativa, permitindo que o usuário escolha a conversão desejada e informe o valor a ser convertido.

O projeto contempla as escalas Celsius, Fahrenheit e Kelvin, contribuindo para o estudo de operações aritméticas, estruturas condicionais, entrada e saída de dados e organização da lógica de programação.

## Funcionalidades

- Conversão de Celsius para Fahrenheit e Kelvin.
- Conversão de Fahrenheit para Celsius e Kelvin.
- Conversão de Kelvin para Celsius e Fahrenheit.
- Interação com o usuário por meio de um menu no terminal.

## Fórmulas utilizadas

As principais relações matemáticas entre as escalas são:

| Conversão | Fórmula |
|---|---|
| Celsius para Fahrenheit | \(F = (C \times 9/5) + 32\) |
| Fahrenheit para Celsius | \(C = (F - 32) \times 5/9\) |
| Celsius para Kelvin | \(K = C + 273{,}15\) |
| Kelvin para Celsius | \(C = K - 273{,}15\) |
| Fahrenheit para Kelvin | \(K = (F - 32) \times 5/9 + 273{,}15\) |
| Kelvin para Fahrenheit | \(F = (K - 273{,}15) \times 9/5 + 32\) |

## Tecnologias utilizadas

- **Linguagem C:** implementação dos cálculos e da interação com o usuário.
- **Biblioteca `stdio.h`:** leitura de dados e exibição dos resultados.
- **Compilador GCC:** compilação do código-fonte.

## Como executar

### Pré-requisitos

É necessário possuir um compilador C instalado, como o GCC, ou utilizar um ambiente online compatível com a linguagem.

### 1. Clone o repositório

```bash
git clone https://github.com/ArtPie-dev/Conversor-de-Temperaturas-em-C.git
```

### 2. Acesse a pasta

```bash
cd Conversor-de-Temperaturas-em-C
```

### 3. Compile o código

O arquivo publicado atualmente é `conversor em c.c`:

```bash
gcc "conversor em c.c" -o conversor
```

### 4. Execute o programa

No Linux:

```bash
./conversor
```

No Windows:

```bash
conversor.exe
```

## Exemplos de conversão

Considerando as fórmulas padrão de conversão:

| Temperatura inicial | Resultado esperado |
|---|---:|
| 0 °C para Fahrenheit | 32 °F |
| 100 °C para Fahrenheit | 212 °F |
| 0 °C para Kelvin | 273,15 K |
| 273,15 K para Celsius | 0 °C |

Esses valores podem ser utilizados como casos de teste para conferir os resultados produzidos pelo programa.

## Demonstração

Adicione capturas reais do menu e dos resultados das conversões.

Sugestão de estrutura:

```text
evidencias/
├── menu-principal.png
├── conversao-celsius.png
└── conversao-kelvin.png
```

## Conceitos praticados

- Operações aritméticas.
- Expressões matemáticas.
- Entrada e saída de dados.
- Estruturas condicionais.
- Organização de programas em C.
- Testes com valores conhecidos.

## Autor

**Arthur Pierre de Aguiar da Silva**

Estudante de Ciência da Computação.

## Licença

Consulte o arquivo `LICENSE` para conhecer as condições de utilização e distribuição deste projeto.

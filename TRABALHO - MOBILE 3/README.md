# Calculadora Flutter

---

## 1. Descrição da Aplicação

Este projeto consiste no desenvolvimento de uma aplicação de calculadora simples utilizando o framework Flutter.

A aplicação possui uma interface gráfica funcional e permite a realização de operações matemáticas básicas, simulando o funcionamento de uma calculadora tradicional.

O principal objetivo do projeto é aplicar conceitos de componentização de widgets, promovendo organização, reutilização de código e boas práticas no desenvolvimento de interfaces mobile.

---

## 2. Objetivo

Desenvolver uma aplicação mobile que:

- Realize operações matemáticas básicas  
- Possua interface gráfica funcional e intuitiva  
- Utilize widgets reutilizáveis  
- Siga boas práticas de organização de código  

---

## 3. Funcionalidades

A calculadora implementa as seguintes funcionalidades:

- Inserção de números (0 a 9)  
- Operações matemáticas:  
  - Adição (+)  
  - Subtração (-)  
  - Multiplicação (*)  
  - Divisão (/)  
- Exibição do resultado no display  
- Limpeza da operação por meio do botão "C"  
- Suporte a números decimais  

---

## 4. Componentização

O projeto foi estruturado utilizando widgets reutilizáveis para facilitar a manutenção e organização.

### Botão (Botao)

Responsável por representar os botões da calculadora.

**Características:**
- Recebe o valor do botão (número ou operação)  
- Executa uma ação ao ser pressionado  
- Permite customização de estilo (cores, tamanho, margem)  
- Reutilizável em toda a interface  

---

### Display

Responsável por exibir:

- Valores digitados  
- Operações em andamento  
- Resultado final  

Possui alinhamento à direita e destaque visual para melhor leitura.

---

### Lógica da Calculadora

Arquivo responsável pelo processamento das operações (`calculadora_logica.dart`):

- Interpretação das entradas do usuário  
- Montagem da expressão matemática  
- Cálculo do resultado final  

---

## 5. Estrutura da Interface

A interface foi construída utilizando os principais widgets do Flutter:

- `Column`: organização vertical dos elementos  
- `Row`: organização horizontal dos botões  
- `Expanded`: distribuição proporcional do espaço  
- `Container`: estilização dos componentes  
- `InkWell`: detecção de clique nos botões  

A tela principal organiza os números, operadores e display de forma responsiva.

---

## 6. Estrutura de Pastas 
lib/
├── widgets/
│ ├── botao.dart
│ └── display.dart
├── utils/
│ └── calculadora_logica.dart
├── pages/
│ └── calculadora_page.dart
└── main.dart

---

## 7. Como Executar o Projeto

### Pré-requisitos

É necessário ter instalado:

- Flutter SDK  
- Dart  
- Android Studio ou Visual Studio Code  
- Emulador Android ou dispositivo físico  

---

### Passos para execução

bash
# Clonar o repositório
git clone <url-do-repositorio>

# Acessar a pasta do projeto
cd calculadora-flutter

# Instalar dependências
flutter pub get

# Executar o projeto
flutter run

8. Objetivo Acadêmico

Este projeto tem como objetivo consolidar os conhecimentos em:

Desenvolvimento com Flutter
Componentização de widgets
Organização de código
Construção de interfaces responsivas
Separação entre lógica e interface

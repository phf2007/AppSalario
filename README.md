# App Salario

> Um aplicativo Android simples que calcule o salário e o percentual do usuário.

## 📱 Descrição

O **App Salario** permite ao usuário calcular o salário e o percentual entre 40%, 45% e 50%.

## 🔧 Funcionalidades

- [x] 1 Tela que fará toda a conta
- [x] Um TextView abaixo do botão que exibe o resultado
- [x] Fácil de entender
- [x] Interface simples e intuitiva
- [ ] Tema claro e escuro (planejado para futuras versões)

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Bumblebee | 2021.1.1)
- [x] **Kotlin+Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **Button** e **EditText**

## 🛠️ Como Rodar o Projeto

Siga os passos abaixo para rodar o projeto localmente:


1. Clone este repositório:
    ```bash
    git clone https://github.com/phf2007/AppSalario/salario.zip
    ```

2. Abra o projeto no Android Studio.

3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

MyApplication
├── app
│   ├── main
│   │   ├── java/com.example.myapplication  
│   │   │   ├── MainActivity.java                  # Atividade principal onde está elaborado as fórmulas
│   │   ├── res
│   │   │   ├── layout
│   │   │   │   ├── activity_main.xml              # Layout da tela principal
│   │   │   └── values
│   │   │       ├── strings.xml                    # Strings usadas no app
│   │   │       ├── colors.xml                     # Cores definidas no projeto
│   └── build.gradle                               # Configuração do Gradle
└── README.md                                      # Este arquivo



## 🎨 Design e Prototipagem 

A interface do app foi criada usando **ConstraintLayout** para manter a responsividade em diferentes tamanhos de tela. 

O design é minimalista e fácil de usar, com foco na simplicidade.

 ## 🖥️ Telas do Aplicativo

**Tela Principal** 

Na tela principal, tem uma caixa de texto numérica e um RadioGroup com 3 RadioButton nele, que indica o percentual do salário do usuário, ele escreve o salário dele e o percentual fará a diferença no salário dele

## 👨‍💻 Desenvolvedores – 
Pedro Henrique Fontes - Desenvolvedor - [GitHub](https://github.com/phf2007)

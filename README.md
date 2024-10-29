# **AppSalario (Aplicação que calcula salário)**

> Um aplicativo Android desenvolvido para calcular seu salario com uma certa porcentagem adicionada.

## Descrição
O **AppSalario** permite ao usuário poder calcular seu salario com uam devida porcentagem adicionada a escolha do usuário para ser mostrado seu resultado.

## Funcionalidades
- [x] Entrada de dados de consumo
- [x] Cálculo e exibição de estatísticas de consumo
- [x] Gráficos interativos para visualização dos dados
- [x] Interface intuitiva e amigável
- [ ] Suporte para diferentes tipos de recursos (planejado para futuras versões)

## Tecnologias Utilizadas
- [x] **Android Studio** (versão recomendada: Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [X] **TextView**, **EditText** para entrada e exibição de dados

## Como Rodar o Projeto
Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:
   ```bash
   https://github.com/Hacker19991/Aplica-o-que-calcula-sal-rio
   
2. Abra o projeto no Android Studio.
   
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## Estrutura do Projeto

```
── app
   ├── src
   │   ├── main
   │   │   ├── java/com/example/appconsumo
   │   │   │   ├── MainActivity.java # Atividade principal para monitoramento de consumo
   │   │   ├── res
   │   │   │   ├── layout
   │   │   │   │   ├── activity_main.xml # Layout da tela principal
   │   │   │   └── values
   │   │   │       ├── strings.xml # Strings usadas no app
   │   │   │       ├── colors.xml # Cores definidas no projeto
   └── build.gradle # Configuração do Gradle
```

## Design e Prototipage
A interface do app foi criada usando ConstraintLayout no modelo Design para ser mais simples e facil de se usar e para ser mais compacto ao android e mais simples e pratico assim podendo se acostumar com o tempo.

## Telas do Aplicativo 

> Tela Principal

![image](https://github.com/user-attachments/assets/57d655bb-b728-42c1-a462-b990d70ad4e8)

Uma tela simples, 1 EditText para o salário ser devidamente inserido, um botão para processar a conta informada adequadamente, dois TextView novamente apenas para dar titulo para onde cada dado ou interação será inisrido, e no final 3 RadioButton (dentro de um RadioGroup para os três botões poderem trabalhar juntos no mesmo código) onde cada uma será, 40%, 45$ e 50$ de sofre um almento no salario insirido, não será necessário o TextView para mostrar o resultado pois ele será alertado por um AlertDialog que mostrará o resultado por uma caixa de mensagem atrávez do botão.

## Desenvolvedores
**Gabriel Henrique** - Desenvolvedor - [GitHub](https://github.com/Hacker19991).

## Licença
Este projeto está licenciado sob os termos da licença MIT. Para mais detalhes, veja o arquivo
[LICENSE](LICENSE).

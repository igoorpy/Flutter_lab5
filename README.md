# Lab 5 - App de Academia (FitGym - Boas-Vindas e Login)

Projeto desenvolvido como desafio prático do **Lab 5** na disciplina de Desenvolvimento Mobile do professor **Prof. Mateus de Paula**.

## 🎬 Demonstração da Aplicação

![Demonstração do FitGym](png/login.gif)

## Sobre a Aplicação
A aplicação é focada em uma interface para Academia (FitGym) contendo duas telas integradas com navegação reativa:
1. **Tela de Boas-Vindas:** Apresenta a marca FitGym, slogan e o botão para acessar a conta do aluno.
2. **Tela de Login:** Formulário com os campos `user` (Matrícula/E-mail), `senha` e o botão `Entrar`.

## Execução Nativa (Linux Mint)
```bash
flutter run -d linux

AcademiaApp (MaterialApp - Dark Theme)
  └── BoasVindasPage (Scaffold)
        └── Column
              ├── Icon (Icons.fitness_center)
              ├── Text ("BEM-VINDO À FITGYM ACADEMIA")
              └── ElevatedButton ("ENTRAR NA CONTA") ──(Navegação)──> LoginPage (Scaffold)
                                                                            └── Column
                                                                                  ├── TextField ("user")
                                                                                  ├── TextField ("senha")
                                                                                  └── ElevatedButton ("Entrar")
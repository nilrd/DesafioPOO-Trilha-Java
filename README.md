# Desafio POO - iPhone UML

Este projeto é parte do desafio de Programação Orientada a Objetos (POO), modelando o componente iPhone e suas funcionalidades, como reprodutor musical, aparelho telefônico e navegador de internet.

## Funcionalidades
- **Reprodutor Musical**: tocar, pausar, selecionar música
- **Aparelho Telefônico**: ligar, atender, iniciar correio de voz
- **Navegador de Internet**: exibir página, adicionar nova aba, atualizar página

## Evidências

Evidências do código implementado:

![Evidência 2](./evidencia/evidencia2.png)

## UML Diagram

```mermaid
classDiagram
    class ReprodutorMusical {
        +tocar()
        +pausar()
        +selecionarMusica(String musica)
    }

    class AparelhoTelefonico {
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
    }

    class NavegadorInternet {
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina()
    }

    class iPhone {
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
```

## Links Importantes

- [Link do Desafio](https://github.com/digitalinnovationone/trilha-java-basico/tree/main/desafios/poo)

## Contato

Estou sempre aberto a colaborações e discussões sobre qualidade de software! Vamos nos conectar!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nilsondasilvabrites/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/nilrd)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?logo=whatsapp&logoColor=white)](https://wa.me/5511940825120)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?logo=gmail&logoColor=white)](mailto:nilson.brites@gmail.com)

<div align="center">
  <h1> Desafio UML </h1>
</div>

Este repositóriofoi criado com propósitos didáticos, representa um desafio proposto de modelagem e diagramação utilizando UML, criado em colaboração entre a [Digital Innovation One](https://www.dio.me/) e o Santander, como parte do Bootcamp Santander 2024 - Backend com Java

```mermaid
classDiagram
    class ReprodutorMusical {
        +tocar()          
        +pausar()         
        +selecionarMusica(musica: String)
    }

    class AparelhoTelefonico {
        +ligar(numero: String)
        +atender()              
        +iniciarCorreioVoz() 
    }

    class NavegadorInternet {
        +exibirPagina(url: String)      
        +adicionarNovaAba()             
        +atualizarPagina()
    }

    class Iphone {
    }

    Iphone --> ReprodutorMusical
    Iphone --> AparelhoTelefonico
    Iphone --> NavegadorInternet

```
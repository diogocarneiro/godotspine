<!--

*** Thanks for checking out this README Template. If you have a suggestion that would

*** make this better, please fork the repo and create a pull request or simply open

*** an issue with the tag "enhancement".

*** Thanks again! Now go create something AMAZING! :D

-->

  

<!-- PROJECT SHIELDS -->

<!--

*** I'm using markdown "reference style" links for readability.

*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).

*** See the bottom of this document for the declaration of the reference variables

*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.

*** https://www.markdownguide.org/basic-syntax/#reference-style-links

-->

<!-- [![Forks][forks-shield]][forks-url] -->

<!-- [![Stargazers][stars-shield]][stars-url] -->

<!--

[![Contributors][contributors-shield]][contributors-url]

[![Maintainers][maintainers-shield]][maintainers-url]

[![Issues][issues-shield]][issues-url]

[![MIT License][license-shield]][license-url]

[![LinkedIn][linkedin-shield]][linkedin-url]

<a href="https://gitlab.com/mobilebrains/spmanager/-/project_members" alt="Contributors">

<img src="https://img.shields.io/gitlab/-/project_members" /></a>

<a href="https://discord.gg/HjJCwm5">

<img src="https://img.shields.io/discord/308323056592486420?logo=discord"

alt="chat on Discord">

</a>
 -->
 
<!-- PROJECT LOGO -->

<br />
<p align="center">
<img src="https://raw.githubusercontent.com/diogocarneiro/godot-spine/main/godot_spine_logo.png" alt="Logo" width="512" height="207">
</a>

<h3  align="center">Godot Engine - Spine2D Module Build-In</h3>
<p  align="center">Godot Engine - Spine2D Module Build-In</p>

<!-- TABLE OF CONTENTS -->

##  Tabela de conteúdos

*  [Sobre](#sobre)
*  [Tecnologias](#tecnologias)
*  [Começar](#começar)
*  [Requisitos](#requisitos)
*  [Instalação](#instalação)
*  [Roadmap](#roadmap)
*  [Licença](#licença)
*  [Contribuição](#contribuição)
*  [Contacto](#contacto)
*  [Reconhecimentos](#reconhecimentos)
*  [Pay me a Coffee](#donate)

<!-- SOBRE O PROJECTO -->

##  Sobre

Godot Engine é um motor de jogo de código aberto publicado no âmbito da licença MIT desenvolvido pela comunidade do Godot Engine e usado internamente em várias empresas da América Latina antes de ter se tornado código aberto e lançado para o público.

A animação dá vida aos jogos. Acreditamos que criar uma animação incrível exige não apenas um software potente, mas um processo de trabalho poderoso. Spine é dedicado à animação 2D, fornecendo um trabalho eficiente tanto para criar animações incríveis como integrá-las a seus jogos.

As principais características são:
 - Game Engine.
 - Modulo do Spine.

<!-- CRIADO COM -->

###  Tecnologias

As tecnologias usados para a criação do projecto foram:

 - [Godot Engine](https://godotengine.org)
 - [Spine](http://esotericsoftware.com)
 - [Visual Studio Community](https://www.visualstudio.com/vs/community/)
 - [Python 3.5+](https://www.python.org/downloads/windows/)
 - [SCons 3.0](https://www.scons.org/)

<!-- COMEÇAR -->

##  Começar

  

Será necessário a instalação de certos requesitos, dependo do OS.
Siga os passos conforme o seu OS.

  

<!-- REQUISITOS -->

###  Requisitos

Preparar a instalação do projecto antes de começar.

No Windows é necessário:

 - [Visual Studio Community](https://www.visualstudio.com/vs/community/)
 - [Python 3.5+](https://www.python.org/downloads/windows/)
 - [SCons 3.0](https://www.scons.org/)


<!-- Instalação -->

###  Instalação

1. Clonar o repositório.

```sh

git clone https://github.com/diogocarneiro/godot-spine.git

```

2. Compilar no Windows.

```sh

scons -j6 platform=windows

Atenção a instrução -j(x) significa o número de cores do processador para a compilação.
```
```sh
Para compilação 64-bits:

scons platform=windows tools=yes target=release_debug bits=64

Para compilação 32-bits:
 
scons platform=windows tools=yes target=release_debug bits=32
```
```sh
Após a compilação teremos o nosso executável em:

( \bin\godot.windows.opt.tools.64.exe )
```
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<!-- ROADMAP -->

##  Roadmap

Base:

* [x] Criação do README.md.
* [x] Criação da Licença.
* [x] Criação do logo para este projecto.
* [x] Adicionar Godot Engine.
* [x] Adicionar Module Spine2D.
* [ ] Modificar o Editor.
* [ ] Actualização de menus do Editor.



<!-- CONTRIBUTING -->

##  Contribuição

  

Contribuições são o que tornam a comunidade de código aberto um lugar incrível para aprender, inspirar e criar. Todas as contribuições que você fizer são muito apreciadas.

1. Fazer um Fork do projecto
<br>
2. Crie sua ramificação de recursos (git checkout -b característica / alteração)
<br>
3. Confirme suas alterações (git commit -m 'Adicione um comentário da característica nova.')
<br>
4. Enviar para a ramificação (recurso de origem de envio por push do git / característica )
<br>
5. Abrir uma solicitação de recebimento


<!-- Licença -->

##  Licença

Distribuído sob a licença MIT.

Veja [Licença](https://github.com/diogocarneiro/godot-spine/blob/main/LICENSE) para mais informações.

  

<!-- Contacto -->

##  Contacto

Nome: [Diogo Carneiro](https://www.gamevolutions.pt)
<br>
E-mail: [geral@mobilebrains.pt](mailto:geral@mobilebrains.pt)
<br>
Twitter: [Diogo Carneiro](https://twitter.com/diogoncarneiro)
<br>
Skype: [live:diogoncarneiro](live:diogoncarneiro)
<br>
Link do Projecto: [https://github.com/diogocarneiro/godot-spine](https://github.com/diogocarneiro/godot-spine)

  

<!-- RECONHECIMENTOS -->

##  Reconhecimentos

<p>À equipa do [https://github.com/diogocarneiro/godot-spine](https://github.com/diogocarneiro/godot-spine) </p>

## Donate
Pay me a Coffee to help me get on with the job.

[![Donate with Bitcoin](https://en.cryptobadges.io/badge/micro/3BPN2BzYt1Jj3Btf1eiHf7G8ioYbLWBWMW)](https://en.cryptobadges.io/donate/3BPN2BzYt1Jj3Btf1eiHf7G8ioYbLWBWMW) [![Donate with Ethereum](https://en.cryptobadges.io/badge/micro/0xbdef35e78662f53b0dbf1e723df69f39a771be6b)](https://en.cryptobadges.io/donate/0xbdef35e78662f53b0dbf1e723df69f39a771be6b) [![Donate with Litecoin](https://en.cryptobadges.io/badge/micro/LZ2g2hodU3thFYy9JYFsirUH29ujJF1v7e)](https://en.cryptobadges.io/donate/LZ2g2hodU3thFYy9JYFsirUH29ujJF1v7e)
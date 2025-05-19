# Case Técnico — Automação de Textos personalizados para o linkedin

Este case documenta a criação de todo um projeto que envolve uma API + Front-end + electron, para que atravéz de uma interface amigável, consiga automatizar todo um networking, algo que de forma geral os desenvolvedores não possuem grandes habilidades.  

A solução foi desenvolvida para atender uma grande dor em que profissionais de maneira geral tem dificuldade em desenvolver ser networkin para desenvolvimento profissional.  

## Contexto

Eu mesmo estava em uma situação que precisava expandir meus contatos, e fazer pontes com pessoas chaves da área tech para que pudesse ter acosso a grandes profissionais da área.  

Esse processo precisava ser feito com ciclo completo de criação de tópico, inspiração e estilo de escrita, e colocar a postragem em reascunho, tudo de forma opicional e de fácil utilização, para que eu pudesse em qualquer etapa do processo fazer manualmente, ou manter TUDO automatizado.  

## Objetivo

Desenvolver o networking atrávéz desses principios:

- Busca por assuntos de tech mais atuais e contextualmente compatível com o perfil profissional do cliente.
- Adaptação do texto para o esti de escrita do cliente para que não parecer que foi uma IA que fez a maior parte.
- Capacidade de mitigar o maior tempo possível, fazer com que uma concepção á publicação dure menso que 5 minutos.

## Desafios técnicos

Durante o desenvolvimento, enfrentei diversos pontos críticos:

- O sistema teria que exigir o máximo de processamento na própria máquina, para mitigar qualquer custo de uso de cloud.  
- Teria que ter uma interface totalmente amigável para que qualuqer pessoa sem muitas habilidade técnicas conseguisse utilizar.  
- Para tornar um ponduto vendável como possibilidade, precisaria ter algum controle mpínimo de assinaturas, ao mesmo tempo qualuqer informação de .env não poderia ser vazada.  
- Se trata de um um projeto mono-repoositório, ou seja, o front, a API, e electron deveriam estar totalmente funcionais, utilizando apenas um script, não tendo conflitos de execução.

## Decisões técnicas

A linguagens escolhidas foram: 
- NestJs pro BackEnd, pela boa modularização de responsabilidade, para ser possivel parar em qualquer momento do fluxo pra torna-lo manual/opicional.  
- Ionic/Angular, por nativamente já ter bons componentes de html para que com conhecimentos simples de frontend, consiga fazer uma interface amigável.  
- Electron, Pela necessidade do projeto precisar rodar em desktop.  

A CI/CD otimizado para verificação de builds em cada epata do projeto, e prevenção de .env vazados.

## Resultado entregue

- Networking foi um sucesso! O principal foco do projeto gerou diversos convites pra entrevistas, e muitos contatos preciossos com pessoas da área.  
- Projeto 100% funcional, todo fluxo pós configurado, gastando menos de 5 minutos por post.  
- Por si só, o projeto já vale como portifólio demostrando alto conhecimentos em multilinguagens.  

O projeto foi validado em ambiente real, com feedback imediato: **A automação poupou muito tempo, fez com que tivesse um bom networking em pouco tempo.**

## Aprendizados

- A lógica para fazer com que diferentes tecnologias funcionem em conjunto.  
- Também seria possivel transformar em um Sas 100% cloud caso quisesse escalar bastante o produto.  
- Essa entrega mostrou o impacto real de uma automação bem pensada em um cenário onde a dor por não ter bons networkings impacta mais os proficionais de tech em geral.  

## Repositório com código

[https://github.com/MarcosScheunemann/auto-likedin](https://github.com/MarcosScheunemann/auto-likedin)

## Contato

[LinkedIn](https://www.linkedin.com/in/marcos-vergueiro/)

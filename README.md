# Atividade Ponderada Individual
## Atividade Ponderada Individual

Vocês devem apresentar uma experiência que permita o usuário escolher entre rodar uma aplicação de realidade aumentada ou uma aplicação de realidade virtual (tour 360). Vocês podem utilizar a base que foi desenvolvida nas instruções da semana. Todo o código deve ser APRESENTADO para o professor, respondendo as seguintes questões:

- O que foi desenvolvido?
- Como foi implementada a experiência de realidade aumentada?
- Como foi implementada a experiência de realidade virtual?

Adicionar um repositório no link. Além do código, o seu repositório deve conter um README contendo uma breve descrição do que foi realizada (um ou dois parágrafos).

## Introdução

Este projeto implementa uma experiência interativa e imersiva para uma loja virtual fictícia da LEGO, utilizando HTML, A-Frame (para realidade virtual e aumentada), e AR.js (para recursos de realidade aumentada). Ele combina diferentes páginas HTML para criar um ambiente 3D navegável e explorável, proporcionando interações com elementos virtuais. Nesse sentido, o objetivo gerale é criar uma experiência de compra diferenciada, misturando realidade virtual (VR) e realidade aumentada (AR), permitindo ao cliente explorar produtos de forma imersiva e visualmente atraente. Além disso, busca-se tornar a processo de monstagem mais simples atrativo e dinâmico. 


<img src="https://github.com/Lucasx369/ExpImersivas/blob/main/src/assets/loja.png" alt="Logo do Projeto" width="1000">

## Experiência Geral
1) O usuário inicia na página inicial e escolhe entre explorar produtos ou ler instruções.
2) Ao acessar a página de produtos, ele é transportado para um ambiente 3D que simula uma loja, com informações sobre os produtos e um botão interativo para navegar para outros departamentos.
3) Caso acesse a tela de instrução (com AR), pode utilizar a câmera do dispositivo para visualizar objetos 3D de produtos LEGO no mundo real.

## Tecnologias e Funcionalidades

1) HTML e CSS:
- Estrutura básica do site.
- Botões para navegação entre páginas.

2) A-Frame:
- Criação de ambientes 3D imersivos diretamente no navegador.
- Configuração de câmera, cursor e elementos interativos, como esferas e textos.

3) AR.js:
- Integração com A-Frame para adicionar funcionalidades de realidade aumentada.
- Detecta marcadores físicos para exibir objetos 3D no mundo real.

4) JavaScript:
- Adição de interatividade, como eventos para redirecionar o usuário a diferentes páginas ao interagir com os elementos.

## Estrutura Geral Resumida:

- Página Inicial (index.html): Apresenta um título de boas-vindas e dois botões para navegar para a página de produtos ou instruções, sendo o ponto de entrada da loja.
- Página de VR (tela-vr-1.html e tela-vr-2.html): Utiliza A-Frame para criar uma cena 3D com fundo 360º, informações sobre produtos e uma esfera interativa que redireciona para a próxima página.
- Página de RA (tela-ar-1.html): Combina A-Frame e AR.js para realidade aumentada, exibindo um modelo 3D de peça de LEGO ao detectar um marcador AR, usando a câmera do dispositivo.

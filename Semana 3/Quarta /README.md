# Atividade Ponderada Individual
## Experiências Imersivas

Portar a experiência do Unity para o A-Frame. Trazer a experiência que estava sendo executada no Unity para o ambiente do A-Frame.

## Descrição Geral

Neste projeto está sendo utilizado o framework A-Frame para criar um ambiente 3D interativo. O cenário consiste em uma cozinha (kitchen) com uma faca (knife) animada para rodar continuamente, proporcionando uma experiência dinâmica e facilitando a instrução do usuário.

[![Assista ao vídeo no YouTube](https://img.youtube.com/vi/s06r5iYRLMo/0.jpg)](https://youtu.be/s06r5iYRLMo)

### Resumo da Estrutura do Código

**Gerenciamento de Assets (`<a-assets>`)**:
   - Carrega texturas para o fundo e chão.
   - Inclui modelos GLTF para a cozinha (`kitchen`) e faca (`knife`).

**Cenário Principal (`<a-scene>`)**:
   - **Fundo**: Definido com `<a-sky>` usando a textura `fundo`.
   - **Chão**: Criado com `<a-plane>` texturizado, rotacionado para estar no plano horizontal.
   - **Cozinha (`kitchen`)**: Modelo 3D posicionado alinhado ao chão.
   - **Faca (`knife`)**: Modelo 3D animado para rotacionar continuamente.

**Câmera**:
   - Posicionada acima da cozinha (`position="0 12 0"`) para visão geral do ambiente.

**Animação**:
   - A faca possui uma animação de rotação contínua, definida pelo atributo `animation`.

## Funcionalidade Principal: Animação da Faca

A faca possui uma rotação animada para indicar interatividade e ajudar os usuários a identificar facilmente o objeto. A animação é contínua e sincronizada para garantir suavidade.

Objetivo da animação:
- Atrair a atenção dos usuários para um ponto de interesse.
- Facilitar a instrução visual no ambiente.

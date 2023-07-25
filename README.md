# Robô Autônomo com Visão Computacional

Este é um repositório que contém o código-fonte e os recursos necessários para construir um robô autônomo utilizando Python, C, Raspberry Pi e Arduino, com sistema de navegação baseado em visão computacional.

## Visão Geral
O objetivo deste projeto é criar um robô autônomo que possa se movimentar de forma independente em um ambiente, utilizando técnicas de visão computacional para detectar obstáculos e tomar decisões de navegação. O robô será controlado por uma combinação de hardware e software, com o Raspberry Pi responsável pelo processamento de imagem e tomada de decisões, enquanto o Arduino será utilizado para o controle dos motores e sensores.

## Funcionalidades Principais
- Visão Computacional: O robô será equipado com uma câmera que captura imagens do ambiente, e o algoritmo de visão computacional será responsável por identificar obstáculos, caminhos livres e outras informações relevantes para a navegação.

- Controle de Motores: O Arduino será utilizado para controlar os motores do robô, permitindo que ele se movimente para frente, para trás, faça curvas, e outras manobras necessárias para evitar obstáculos e seguir um trajeto pré-definido.

- Detecção de Obstáculos: Utilizando técnicas de visão computacional, o robô será capaz de identificar obstáculos em seu caminho e tomar decisões para contorná-los ou evitar colisões.

- Navegação Autônoma: O sistema de navegação autônoma será implementado no Raspberry Pi, utilizando os dados fornecidos pela visão computacional e os sensores do robô. Com base nessas informações, o robô poderá tomar decisões em tempo real para se movimentar de forma autônoma.

## Estrutura do Repositório
codigo_fonte/: Esta pasta contém os códigos-fonte do projeto, incluindo tanto o código em Python responsável pela visão computacional e navegação quanto o código em C para o controle dos motores e interação com o Arduino.

esquemas/: Nesta pasta, você encontrará os esquemas e diagramas de conexão do hardware utilizado no robô, incluindo as ligações entre Raspberry Pi, Arduino e outros componentes.

recursos/: Contém recursos adicionais, como imagens, vídeos ou outros dados relevantes para o projeto.

- Configurações para a montagem da carcaça:
![image](https://user-images.githubusercontent.com/102625995/213512193-e9fb21fe-8b2e-4cc8-a5c1-bce0abad373d.png)

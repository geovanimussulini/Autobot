![GitHub License](https://img.shields.io/github/license/geovanimussulini/Autobot)


# Autobot
⚙️ Funcionamento do Projeto

O robô usa o sensor ultrassônico HC-SR04 para detectar obstáculos à sua frente. Com base na distância medida, ele envia sinais ao Arduino, que, por sua vez, controla os dois motores por meio do driver L293D. Dependendo da distância detectada, o robô pode seguir em frente ou desviar do obstáculo.



⚠️ Observações Importantes

Nunca alimente os motores diretamente do Arduino, pois ele não fornece corrente suficiente.

A ponte H L293D permite controle de sentido de rotação e parada dos motores.

É altamente recomendável o uso de um capacitor eletrolítico e diodos de proteção para motores, embora não estejam visíveis na imagem.

Autores:

Geovani Mussulini Monteiro

Jack Clemente Artur

Adilio Gregorio Da Silva

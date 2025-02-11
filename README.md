# pwm_led_1

## Tarefa Aula síncrona de 06/02/2025 - Parte 2 - Implementação na BitDogLab do projeto servopwm, substituindo o servomotor pelo led RGB (pino 12 - cor azul).

O código do programa é exatamente o mesmo, só substituiu-se o GPIO22 pelo GPIO12.

**O Que foi observado?**

As diferenças de intensidade são pouco perceptíveis com os duty cycles usados (de 2,5% a 12%).
Também foram percebidas algumas cintilações, talvez por causa da baixa frequência (50Hz). A frequência ideal de PWM para controle de LEDs é geralmente considerada acima de 100 Hz para evitar cintilação visível.

**Toda a informação a respeito do código é encontrada em:**

[GitHub](https://github.com/antoniolouro/servo_pwm)

## Vídeos demonstrativos

[![Assista no YouTube](https://img.youtube.com/vi/AE4oXClc_3g/maxresdefault.jpg)](https://youtu.be/AE4oXClc_3g)

**Vídeo com simulação Wokwi**

[![Assista no YouTube](https://img.youtube.com/vi/Q9dCD4Umuz8/maxresdefault.jpg)](https://youtu.be/Q9dCD4Umuz8)



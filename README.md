# Retificador



Componentes e Funcionamento

Transformador (TR1)
Reduz a tensão da rede AC para um nível adequado para o circuito.
A saída do transformador ainda é AC, mas com menor amplitude.

Ponte Retificadora (BR1)
Conjunto de 4 diodos dispostos em ponte para converter a tensão alternada em pulsante.
Retifica os dois semiciclos da onda senoidal, tornando-a sempre positiva.

Capacitor de Filtragem (C1 - 1000µF)
Suaviza a tensão pulsante após a retificação, reduzindo ondulações (ripple).

Regulador de Tensão (U1 - 7805)
Regula a tensão para 5V DC estáveis.

Possui três terminais: entrada (VI), terra (GND) e saída (VO).
Melhora a estabilidade da tensão, protegendo componentes sensíveis.

Capacitores de desacoplamento (C2 e C3 - 22nF)
Eliminam ruídos de alta frequência no regulador, melhorando a estabilidade.

Resistor (R1 - 220Ω) e LED (D1)
O LED indica quando há tensão na saída.
O resistor limita a corrente para evitar que o LED queime.


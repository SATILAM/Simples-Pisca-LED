# Simples-Pisca-LED
Pisca Led com Arduino 

Este é um exemplo de código para um projeto simples com Arduino que faz um LED piscar em um intervalo de 1 segundo.
Na função setup(), o pino 10 é configurado como saída (OUTPUT) para que possa ser usado para controlar o LED.
Na função loop(), primeiro é definido o pino 10 como HIGH, o que faz com que a corrente flua para o LED e ele acenda. Em seguida, há um atraso (delay()) de 1 segundo antes de o pino 10 ser definido como LOW, interrompendo o fluxo de corrente e fazendo com que o LED se apague. 
Em seguida, há outro atraso de 1 segundo antes que o ciclo comece novamente, definindo o pino 10 como HIGH e assim por diante.
Ideal para iniciantes.

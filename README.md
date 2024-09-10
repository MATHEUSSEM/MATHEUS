# MATHEUS
#incluir <ultrassônico.h>
#incluir <servo.h>
#incluir "notas_musicais.h"

#definir pivoServo 7
#definir Trigometria 2
#definr Eco 3
#definir B1A 8
#definir B1B 9
#definir A1A 10 
#definir A1B 11

interiodistanciaD;
inteirodistanciaE;
inteiropino de campainha =6;

flutuadordistanciaObstàculo =35;

Ultrassônicoultrassônico(Trig, Eco);

servo servo;

vazio configurar() {
 serial.começar(9600);

 servo.anexar(pinoServo);
 //pinos da ponte H
 modo pin(B1A, SAÍDA);
 modo pin(B1B, SAÍDA);
 modo pin(B1A, SAÍDA);
 modo pin(B1B, SAÍDA);
 modo pin(buzzerPin, SAÍDA);

 servo.escrever(90);
 //Radar();
 }

 vazio laço() {

  
 

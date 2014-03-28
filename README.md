Timer-
======

TImer com PIC


while(true){

while(aux ==0){



if(input(b1)){
if(a==0){
output_high(pin_a2);
set ++ ;

delay_ms(200);
if(set>15){
set= 0 ;
}
a =1;
}
else{}
}else{
a=0;
output_low(pin_a2);
}

if(input(b2)){

aux = 1;
output_high(pin_a2);
delay_ms(500);
output_low(pin_a2);
delay_ms(500);
output_high(pin_a2);
delay_ms(500);
output_low(pin_a2);
delay_ms(500);
output_high(pin_a2);
delay_ms(500);
output_low(pin_a2);
delay_ms(500);
}
numero = set ;
digito();
}
while(aux == 1){
numero = min ;
digito();
seg++ ;

if (set == min ){
output_low(pin_b4);
output_high(pin_a2);
delay_ms(500);
output_low(pin_a2);
delay_ms(500);

if(input(b1)){
aux = 0;
seg = 0;
min = 0;
set=0;
}

}
else {
output_high(pin_b4);

}

if(input(b1)){
numero=set;
digito();
}else{}


if (seg == 60){
seg = 0;
min ++ ;
}

delay_ms(900);



}

}
}


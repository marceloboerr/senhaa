senhaa
======

switch (anali) {       trisa =0b101111;  // configura RA0,RA1,RA2,RA3,RA5 COMO ENTRADA RA4 SAIDA       trisb =0b00000111;   //configura trisb         case 0:                          // DIGITO 1 senha if (INPUT_DTMF==1)       // Se digito for correto incrementa variável correto { delay_ms(200); correto++; } anali++; continue;   case 1:                 // DIGITO 2 da senha if (INPUT_DTMF==2)      // Se digito for correto incrementa variável correto { delay_ms(200); correto++;  } anali++;               // Incrementa para proxima analise continue;               // Continua proxima analise  case 3: if (correto==2) { lux3=on; FOX=1; con=1; sen=0; break;  }

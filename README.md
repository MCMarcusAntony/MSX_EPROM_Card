# MSX_EPROM_Card ( Portuguese )

As EPROMs testadas foram:

32K - 27C256

64K - 27C512

O capacitor de 100uF é eletrolítico, nos testes foi usado um capacitor de 16V, o capacitor de 100nF é de disco cerâmico.

ATENÇÃO 1: Nas configurações com a opção de 2 ROMs por EPROM, nunca feche os jumpers para as duas ROMS ao mesmo tempo, quando um está fechado, o outro deve estar aberto.
Por exemplo, na EPROM de 32K com 2 ROMs de 16K, NUNCA feche o P27- e o P27+ ao mesmo tempo. Eu sei que isso é meio óbvio, mas não custa nada avisar.

ATENÇÃO 2: Todas as configurações abaixo foram testadas em um HotBit 1.2 e funcionou sem problemas. Mas se você quiser usar, use por sua conta e risco, se seu MSX pegar fogo, sua casa explodir, se você for abduzido por alies, eu não sou responsável. :-)



Configuração dos Jumpers
========================

- EPROM de 32K com ROM de 32K, fechar os jumpers:
  P1+ / 
  CS12 / 
  P27->A15



- EPROM de 32K com 2 ROMs de 16K, fechar os jumpers: 
  P1+ / 
  CS12
  - Para a primeira ROM de 16K:
  P27-
  - Para a segunda ROM de 16K:
  P27+

 

- EPROM de 32K com 2 ROMs basic de 16K, fechar os jumpers:
  P1+ / 
  CS2
  - Para a primeira ROM basic de 16K:
  P27-
  - Para a segunda ROM basic de 16K:
  P27+

  

- EPROM de 64K com ROM de até 64K sem mapeamento, fechar os jumpers:
  P1->A15 / 
  RD / 
  P27->A14
  

  
- EPROM de 64K com 2 ROMs de 32K, fechar os jumpers:
  CS12 / 
  P27->A15
  - Para a primeira ROM de 32K:
  P1-
  - Para a segunda ROM de 32K:
  P1+


Este projeto é livre para compartilhar, modificar, etc.
Se você descobrir algum bug ou fizer melhorias, por favor, me deixe saber. :-)
  
09/2014 - Marcelo Zoffy

marcelo.rtx@gmail.com

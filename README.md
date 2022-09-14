# CANary-Adaptor
Adaptor to connect an OBD2 port to an ATI CANary

The zip file contains all the files required to make the PCB, just drop it on to a PCB
manufacturing web site, choose the colour and pay the fee. 
Examples:

https://www.seeedstudio.com/fusion_pcb.html   
https://cart.jlcpcb.com/quote

Both charge about $5 for 10 boards, and about twice that for shipping. 

You will also need a case, there are 3D printing files in the CASE folder. 
The case is held together by 4 off M3 x 5mm x 8mm heat-set inserts and 4 off M3 x 16
countersunk screws

Additional components:

OBD2 connector: https://www.aliexpress.com/item/1005001622470354.html   
HD15 socket: Amphenol 10090926-P154VLF https://uk.rs-online.com/web/p/d-sub-connectors/7361510   
SIP switch x 24: APEM SIP-08TV https://uk.rs-online.com/web/p/dip-sip-switches/8772384   

You can probably get away with only 16 SIP switches to connect only the data lines. 

Note that since making the one in the pictures I have rotated the right column of switches so
that they all operate in the same direction and also rationalised the row order. 

It is designed to connect directly to a CANary, but with an HD15 gender-changing coupling it can
be used with the CANary HD15 to 4 x Dsub cables too. 

Bail screws are an unsolved problem. Maybe the case could be modified to incorporate a clip to
hold the HD15 together. 

![Here is one I made earlier](Image.jpeg)

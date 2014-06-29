# CR20\*\* battery tester

This is a mashup of parts from Contextual Electronics' Getting To Blinky board, and eevblog's µCurrent.

On this board is a Texas Instruments TPS3809L30DBVR (µCurrent's battery tester), a 0603\* series resistor,
20mm coin cell holder and 0805\* LED to indicate whether or not your coin cell is a goner (at < 2.64v). 

\* Imperial units

## Bill of Materials

This builds 1 board. You'll get at least 3 from OSHPark.

| Quantity | Description | Digikey/Mouser Part Number | Board Placement |
| -------- | ----------- | ------------------- | --------------- |
| 1        | TPS3809L30DBVR | [296-10917-1-ND](http://www.digikey.com/product-detail/en/TPS3809L30DBVR/296-10917-1-ND) / [595-TPS3809L30DBVR](http://www.mouser.com/access/?pn=595-TPS3809L30DBVR) | Q1 |
| 1        | 20mm coin cell holder (through-hole) | [3003K-ND](http://www.digikey.com/product-detail/en/3003/3003K-ND) / [534-3003](http://www.mouser.com/access/?pn=534-3003) | Rear |
| 1 | 0603 imperial series resistor for LED | Generic value\*\* | R1
| 1 | 0805 imperial LED | Generic/Any type\*\*\* | D1 |

I used the following parts for these, but you should really source to your desired quantity:

\*\* 1k 0603 resistor (from the spare parts bin, if you really want one though.. [RMCF0603JT1K00CT-ND](http://www.digikey.com/product-detail/en/RMCF0603JT1K00/RMCF0603JT1K00CT-ND). Try another part and order a bunch for a better discount / price.)

\*\*\* Mouser [645-598-8130-107F](http://www.mouser.com/access/?pn=645-598-8130-107F) (Orange Dialight LED, Vf=1.7V, If=20mA)

## Fabrication

[OSHPark shared project here](https://oshpark.com/shared_projects/Qcq4ZSKX)

## License

CC0

# Molex-rio
Pass through board that converts Roborio DIO, RSL, Relay, Analog In, and PWM to Molex latching connectors. On the underside, the board uses female header connectors that nest to the Roborio. 

![Molex-rio](https://github.com/vinhpham42/Molex-rio/blob/master/Pictures/Molex%20Rio%20Render.png)

```
Molex Rio Digikey BOM
  Molex male pin header      QTY 29     	WM4825-ND
  Female header              QTY 29             S7001-ND
  Molex male housing         QTY 29             WM2901-ND
  Molex female crimp         QTY 87             WM2510-ND
  Crimper                    QTY 1              WM9999-ND	
```
# Installation:
1. Insert female headers into roborio.
2. For RSL, use flush cutters to cut off the third unused pin.
3. Place PCB on top of headers, making sure all pins aline with their repective holes. 
4. Once PCB is sitting flat, solder all headers to the PCB.(Using solder with higher amounts of flux will help)
5. Next, flip over the PCB and insert Molex Male Pin Header according to white print on PCB. 
6. Solder one leg of header, then check for straightness. 
7. Correct if needed, then repeat step 6, with each header. 
8. Use rubbing alcohol and a light brush to clean board if needed.


# Ordering:
1. Go to www.Digikey.com
2. Click on "Cart", then "View Cart"
3. Upload file named "Digikey Molex Rio Order" to the cart
4. When Propted for file Mapping, select "Quantity" then "Digi-Key Part Number" in the drop down box.
5. Lastly click on "Add to cart" to finish

# Molex Crimping
Insturctions on how to crimp Molex connectors can be found in [Spectrum's recommended reading](http://spectrum3847.org/recommendedreading/) under Spectrium FRC Electrical Guide

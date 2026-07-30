# M0SS-101 BUILD GUIDE
( last updated July 30, 2026 )

## Here are the contents of the kit

<img src="images/IMG_7216.jpeg" width="600">

| Quantity | Item |
|---------|------------------------------------------------|
| 3       | PCBs (front panel, LED board, main board) |
| 1       | 24p Flat Flex cable |
| 1       | 12p Flat Flex cable |
| 1       | Encoder + nut |
| 1       | Encoder Knob |
| 1       | DC jack |
| 1       | 1/4" Audio jack + washer + nut |
| 1       | USB A jack |
| 1       | 7mm Standoff |
| 2       | M2 x 4mm screw, T8 |
| 5       | 6-32 x 3/8" screw, Hex |
| 4       | Silicon Feet (not pictured) |
| 1       | Aluminum enclosure (not pictured) |

<br/>

## You will need
- Pliers
- Soldering Iron
- Solder
- A T8 torx bit and driver
- A 2mm Allen Wrench or 2mm hex bit and driver

<br/>

## STEP 1: Add solder to the 1/8" jacks
- These parts were sometimes not soldered well at the manufacturer. Add solder to the 6 tabs (3 tabs on each 1/8" jack) to reinforce them. During this process be VERY cautious to not melt the plastic parts of the jack, nor any of the surrounding parts, like LEDs. You can optionally add one drop of super glue to add strength, place it at the base of the part near the outside edge of the board, but be very careful not to add more then 1 drop, or you risk glueing the part shut!

<img src="images/IMG_7217.jpeg" width="600">

<br/>

## STEP 2: Remove the edge rails from all PCBs

- Using pliers, carefully snap off the edge rails. There are rails on the left and right sides of two larger PCBs, 4 edges in total to be removed.

<img src="images/IMG_7218.jpeg" width="600">

<br/>

## STEP 3: Place and solder the encoder

- Confirm you are placing the encoder on the correct side, by checking for the white outlined shape of the part, drawn on the PCB. The encoder goes on the back side (without all the parts on it).  
- Slightly bend the lugs of the encoder inward, using pliers, or by gently pressing them into the table.  
- Carefully place the encoder. If the lugs will not go in, bend them inward a little more.  
- Solder one pin of the encoder, and check that it is seated correctly.  
- Proceed to solder all the pins, and then the lugs.

<img src="images/IMG_7219.jpeg" width="600">

<br/>

## STEP 4: Place and solder the DC jack, audio jack and USB jack

- These parts are placed on the top side of the main PCB, look for the footprint outlines to confirm, these are installed on the opposite side as the encoder.  
- Start with the DC jack, and solder one pin, then adjust the position of the jack to be as square and straight as possible, using the white footprint outline, before soldering the remaining 2 pins.  
- Now place, and then solder, the USB jack and the audio jack.

<img src="images/IMG_7221.jpeg" width="600">

<br/>

## STEP 5: Install the standoff

- The standoff goes on the same side as the encoder, the back side of the main PCB.  
- Use a M2 x 4mm screw, and be careful to not over tighten it. ⅛ of a turn past hand-tight is great. There are two difererent colours of screw of this side, use the silver one so that the black one can go on the outside.

<img src="images/IMG_7222.jpeg" width="600">

<br/>

## STEP 6: Install the Flat Flex Cables (FFCs)

- Install the large FFC onto the back side of the front panel board. Both FFC connectors are the flip-lock type. Using a small tool or a fingernail, lift the black lock up and back to fully open the connector.   
- Insert the large FFC with the blue stripe up. Ensure it is fully seated and square, then close the lock.

<br/>

<img src="images/IMG_7223.jpeg" width="600">

- Install the small FFC onto the LED board, in the same way as the large FFC.

<img src="images/IMG_7224.jpeg" width="600">

<br/>

## STEP 7: Assemble the stack-up.

- Thread the large FFC through the large cutout in the LED board, and bring the 2 boards together back-to-back.

<img src="images/IMG_7225.jpeg" width="600">

- Holding the main board with the encoder facing down toward the other boards, thread the small FFC through the smaller slit in the main board, and thread the large FFC through the wide slit in the main board. Pass the encoder through the large round hole in the 2 other boards

<img src="images/IMG_7226.jpeg" width="600">
<img src="images/IMG_7227.jpeg" width="600">
<img src="images/IMG_7228.jpeg" width="600">

- On the front panel board, install the encoder nut, and an M2 x 4mm screw to the standoff (the black one). When tightening the encoder nut, exercise caution to not scratch the panel, and to not damage any adjacent buttons. Using a plastic socket is ideal.

<img src="images/IMG_7229.jpeg" width="600">

<br/>

## STEP 8: Connect the FFCs to the main board.

- Use the same procedure in step 5 to install both FFCs to their respective connectors on the main board.


<img src="images/IMG_7230.jpeg" width="600">
<img src="images/IMG_7231.jpeg" width="600">

<br/>

## STEP 9: Install the enclosure

- Place the PCB assembly into the enclosure, inserting the jacks first.  
- Install the 4 large black 6-32 x 3/8" screws.  
- Install the plastic washer and nut onto the audio jack.  
- Install the knob onto the encoder, looking for the irregularity inside the knob, which mates with the flat side of the encoder shaft.  
- Optionally, affix the 4 adhesive feet, on the bottom of the enclosure, at each corner.

<img src="images/IMG_7232.jpeg" width="600">  
<img src="images/IMG_7233.jpeg" width="600">
<img src="images/IMG_7234.jpeg" width="600">

<br/>

Here some details on the I/O:
- Power input is 9v DC, center negative. M0SS-201 draws up to 800mA with a USB Device connected.
- MIDI jack 1 (closest to the top) - MIDI input, Type-A.
- MIDI jack 2 (closest to the bottom) - MIDI thru (soft-thru), Type-A.
- Audio output - 1/4" balanced line level. 
- USB - USB-A Host, it is safe to draw up to 500mA (USB Spec). It should work with any class compliant MIDI Device, but will not work with another USB Host (like a computer). 

<br/>

## STEP 10: First boot

- Apply power to the M0SS-201.
- Some lights should come on.
- Pressing the encoder should produce a sine wave, and trigger some more lights.
- Remove power.

<br/>


## STEP 11: Construct the manual

- I found this cute diagram online, use it to fold your manual into a tiny book.

<img src="images/image22.jpg" width="600">

- If you have done it right, it should look like this

<img src="images/IMG_7235.jpeg" width="600">











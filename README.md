# Schneider Euro PC Keyboard Replacement PCB 

## Background & Problem 

At the time of this writing (2023), the keyboard "membranes" of the
few remaining 1988 Schneider Euro PCs are, most likely, pretty much
fully deteriorated - a nightmare for vintage computer enthusiasts
trying to keep these machines alive. Restoring a Euro PC's keyboard is
one of the biggest challenges in keeping these nice vintage machines
fully functional.

Technically, the Euro PC keyboards are not really "membranes" - they
just consist of a single sheet of Mylar with traces and button contact
zones made of conducting paint. The keys are metalized rubber "stamps"
that close these contacts on the Mylar sheet. So it's more appropriate
to call the Euro PC keyboard a single-layer conducting Mylar "sheet"
keyboard instead of a membrane keyboard. I'll use the term Mylar sheet
keyboard in the following.

Whereas it is possible to repair the traces and contact zones on the
Mylar with conducting "leitsilber" paint, the worst part of this
keyboard is that the Mylar sheet just gets extended and turns into a
flex cable that then connects directly to the motherboard via a simple
flex cable connector. The metalized end contacts of this Mylar flex
cable are pretty much impossible to repair once they
deteriorated. Moreover, the spacing of the conducting paint traces is
very fine and narrow, making repairs with Leitsilber almost
impossible, and the flexcable part of the Mylar sheet cracks easily in
this region as well. A real nightmare. 

## Solution

To once and for all get rid of the Mylar sheet in the Euro PC
keyboards and repair your original Euro PC keyboard, I created this
flexible (0.4 mm thick) PCB as a substitute. Just open up your EuroPC
keyboard, remove and dispose of the Mylar sheet, and put in this
flexible PCB instead. You may have to use an exacto knife to carve out
some extra material from the PCB to make it fit perfectly with the
keyboard carrier plastic posts.

Also, the flex cable connector on the Euro PC motherboard needs to be
removed (by desoldering it). It is then replaced by a little adapter
board. Single row standard pitch header pins connect the adapter board
to the motherboard. Fine pitch pin headers on the adapter board are
used to connect it to the keyboard, using a female, fine-pitch (IDC)
ribbon cable. The keyboard PCB has proper fine pitch pin header
mounting holes as well. See the pictures below for illustration.

## Video

[YouTube Video - Euro PC keyboard repair notes.](https://youtu.be/OTO-QyZ73c4)

## Illustration

![PCB Logo](pics/pcb.jpg) 

![PCB 1](pics/pcb1.jpg)

![PCB 2](pics/pcb2.jpg)

![PCB 3](pics/pcb3.jpg)

![PCB 4](pics/pcb4.jpg) 

![Euro PC 1](pics/pc1.jpg) 

![Euro PC 2](pics/pc2.jpg) 

![Euro PC 3](pics/pc3.jpg) 

![Euro PC 4](pics/pc4.jpg) 

![Euro PC 5](pics/pc5.jpg) 

## Specs

I used [https://jlcpcb.com/](https://jlcpcb.com/). The specs are as follows: 

![Specs](pics/specs.jpg)

It's a normal 2-sided PCB, *not* a "Flex" PCB! Just use the default
values on the JLCPCB website, but change the PCB width to 0.4 mm!
That's all that is required.


## Gerbers

The Gerbers for the (0.4 mm width) keyboard PCB as well as the
motherboard keyboard adapter are in the [Gerbers
directory.](./gerbers/) 

## Please leave a "like" if this project helped you to restore your Euro PC!


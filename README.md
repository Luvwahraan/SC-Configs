# What is it?

My Star Citizen HOSAS config for left and right VPC Constellation Alpha Prime grips, with MongoosT-50CM2 bases.

That binds physicals buttons and axis into one  never unplugged virtual joystick.
So SC won’t invert joysticks or refuse to work with when you unplug USB stuff.

# Require

## Hardware

I have some specific hardware, with multiples pedals.

* VPC Alpha prime with 50CM2 bases:
https://virpil-controls.eu/vpc-constellation-alpha-prime-l.html
https://virpil-controls.eu/vpc-constellation-alpha-prime-r.html
https://virpil-controls.eu/vpc-mongoost-50cm-base.html
Maybe standard alpha prime grips fits, but I don’t own them.
* Thrustmaster T300RS with ferrari addon wheel.
* Fanatec clubsport pedals v2.

## Software

* vJoy − virtual joysticks
https://github.com/jshafer817/vJoy
* HidHide − hides physical joysticks, so games wont bind them instead virtuals
* https://github.com/ViGEm/HidHide
* JoystickGremlin − bindings and macro
https://github.com/WhiteMagic/JoystickGremlin
* VPC Software − needed for any Virpil Control hardware
https://support.virpil.com/en/support/solutions/47000010107
* Some playable Star Citizen account and game
https://robertsspaceindustries.com/

## WTF are these files?

### Virpil

Profiles for with my specifics hardware (Alpha prime + 50CM2).
That’s need to be imported in VPC Configuration Tool.

### LIVE or PTU

Star Citizen’s config files, placed in adequat directory.
> Program Files\Roberts Space Industries\StarCitizen\\**LIVE**\USER\Client\0\Profiles\default

or
> … \\**PTU**\USER\Client\0\Profiles\default

### JoystickGremlin

Gremlin’s profiles.


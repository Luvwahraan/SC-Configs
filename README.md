# What is it?

My Star Citizen HOSAS config for left and right VPC Constellation Alpha Prime grips, with MongoosT-50CM2 bases.

That binds physicals buttons and axis into one  never unplugged virtual joystick.
So SC won’t invert joysticks or refuse to work with when you unplug USB stuff.

# Require

## Hardware

I have some specific hardware, with multiples pedals.

* Thrustmaster T3PA with ferrari T.RJ12 Adapter.
* Fanatec clubsport pedals v2.
* VPC Constellation Alpha prime left and right
    * https://virpil-controls.eu/vpc-constellation-alpha-prime-l.html
    * https://virpil-controls.eu/vpc-constellation-alpha-prime-r.html
* VPC Flightstick Z-Extension left and right
    * https://virpil-controls.eu/vpc-flightstick-z-extension.html
* 50CM2 bases
    * https://virpil-controls.eu/vpc-mongoost-50cm-base.html
* VPC Control Panel #1 slaved on right base
* VPC Control Panel #2 slaved on left base.
    * https://virpil-controls.eu/vpc-control-panel-1.html
    * https://virpil-controls.eu/vpc-control-panel-2.html

Maybe standard Constellation alpha grips fits, but I don’t own them.

## Software

* vJoy − virtual joysticks − https://github.com/jshafer817/vJoy
* HidHide − hides physical joysticks, so games wont bind them instead virtuals − https://github.com/ViGEm/HidHide
* JoystickGremlin − bindings and macro − https://github.com/WhiteMagic/JoystickGremlin
* VPC Software − needed for any Virpil Control hardware − https://support.virpil.com/en/support/solutions/47000010107
* Some playable Star Citizen account and game − https://robertsspaceindustries.com/

## WTF are these files?

### Virpil

Profiles for with my specifics hardware.
That’s need to be imported in VPC Configuration Tool.

### LIVE or PTU

Star Citizen’s config files, placed in adequat directory.
> Program Files\Roberts Space Industries\StarCitizen\\**LIVE**\USER\Client\0\Profiles\default

or
> … \\**PTU**\USER\Client\0\Profiles\default

File *template.actionmaps.xml* isn’t usable in game.
That’s some template to get all possible action names.

### JoystickGremlin

Gremlin’s profiles.


# What is it?

My Star Citizen HOSAS config for left and right VPC Constellation Alpha Prime grips, with MongoosT-50CM2 bases.

That binds physicals buttons and axis into one never unplugged virtual joystick.
So SC won’t invert joysticks or refuse to work with when you unplug USB stuff.

Since SC is broken at moment, I didn’t test all of this yet.

# Require

## Hardware

I have some specific hardware, with multiples pedals.

* Thrustmaster T300RS with Ferrari F1 Add-On.
* Fanatec clubsport pedals v2.
* VPC Alpha prime left and right, with 50CM2 bases:

https://virpil-controls.eu/vpc-constellation-alpha-prime-l.html

https://virpil-controls.eu/vpc-constellation-alpha-prime-r.html

https://virpil-controls.eu/vpc-mongoost-50cm-base.html

Maybe standard alpha prime grips fits, but I don’t own them.

## Software

* vJoy − virtual joysticks − https://github.com/jshafer817/vJoy
* HidHide − hides physical joysticks, so games wont bind them instead virtuals − https://github.com/ViGEm/HidHide
* JoystickGremlin − bindings and macro − https://github.com/WhiteMagic/JoystickGremlin
* VPC Software − needed for any Virpil Control hardware − https://support.virpil.com/en/support/solutions/47000010107
* Some playable Star Citizen account and game − https://robertsspaceindustries.com/

## WTF are these files?

### Virpil

Profiles for my specific hardware (Alpha prime + 50CM2).
That’s need to be imported in VPC Configuration Tool.

### LIVE or PTU

Star Citizen’s config files, placed in adequat directory.
> Program Files\Roberts Space Industries\StarCitizen\\**LIVE**\USER\Client\0\Profiles\default

or
> … \\**PTU**\USER\Client\0\Profiles\default

File *template.actionmaps.xml* isn’t usable in game.
That’s some template to get all possible action names.

### JoystickGremlin

Gremlin’s profiles and plugins.

### MultiplyAyis

This plugin binds one physical -1 to +1 axis to half virtual axis (so 0 to -1), and other half (0 to 1) to same physical axis with some modifier.





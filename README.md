# Colorfields

A tiny [Adminer](https://www.adminer.org/) extension for parsing and displaying colors where there are colors found.

#### What does it do and why should I care?

If the cell's content matches either of the regexes down below, a small circle will appear next to the value. This way it should be pretty obvious **what the color looks like** without having to perform expensive decoding using brain-mathematics and having to imagine the color just using the brain.

#### Wait, what?

Currently Colorfields extension supports **HEX** and **RGB(a)** formats:
- HEX: `^#?([0-9a-fA-F]{3}){1,2}$`
- RGB(a): `^rgba?\((\d+),(\d+),(\d+)(,(\d+))?\)$`

#### Eh, just show me what it looks like...

Here you go, you rascal you:

![Preview](http://i.imgur.com/CyS2ncP.png)

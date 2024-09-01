# Lattepanda-MU-Nano-ITX-carrier-board
A rich featured Nano-ITX carrier board for holding the upgradable MU module

This board was created in the line of the LattePanda Mu Free Trial Event and therefor also open source.
The MU module is made by [LattePanda](https://www.lattepanda.com/lattepanda-mu) and offers both upgradability and the open possibility of CPU different architectures in the future. Currently this SO-DIMM like form factor is only offered by this company as far as I'm aware.

Keep in mind I'm a civil engineer by trade and did my best on this board; previously only had some experience in simple pcb's by thinkering.
I've chosen GitHub so people can join in. and better the design.
Even while I designed this with my own project in mind I made it feature rich in a way it should be suitable to a lot of projects or at least easy to adapt.

The feature set for v1.0;
- Standard form factor -> Nano ITX (fits lots of indutrial purposes!)
- 12V powered from both a hack plug and terminal (again the terminal for industrial purposes)
- 2230 and 2280 m.2 M-key SSD option
- 2230 m.2 E-key for expandability, facing inward so you can still fit oversized cards
- Front panel header
- USB header
- CEC header
- Whatever I've chosen to ommit from the original carrier board is crossed out so easy to reinstate in order you'd need like i2c or sda for your project

As stated this project hasn't been checked yet if everything is in order in according to specs.
Also the ethernet port is still 1GBe; for a future revision I'd like to make that 2.5GBe + WOL support.

# variable-capacitor-ltspice
this is simply a time variable capacitor model for ltspice, for anyone who needs it

I created it because I needed to simulate a "floating" variable capacitor (not referenced to ground), and didn't find any resources online. Using this model is straigth foward: There are 3 pins, 2 are the capacitor plates and the thrid one is simply a voltage level.
The capacitance is equal to that of the voltage level in <Farads>.

I did not test it extensivaly, so I don't know problems in convergence or if the parasitics I put actually work. Use at your own risk.
I guess it could be ported to other simulators without bigger problems, I didn't bother trying =)

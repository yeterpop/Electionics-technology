
# Common source amplifier


#### Completed circuit and Transistor info:

- Completed circuit w/ oscilloscope reading:

![[Pasted image 20261104114901.jpg|365]]
ㅤ
![[Pasted image 20261104114912.jpg|328]]


- Part number: 2N5486
ㅤ
- Transistor diagram:

![[Pasted image 20261104114501.jpg|309]]

---

#### Measured Values:

- Vgs = -1.7 V

- V in = 100 mVpp

- V out = 200 mVpp

---

#### Calculated values:

- μmhos = 2.51K
*Math:*
> *gfs(1-Vgs/Vgs off)*

ㅤ
- Rout = 2.20K
*Math:*
> *(RD)(RL)/RD+RL

- Av (based on Dc voltage across resistors) = 5.52K
*Math:*
> (gfs)(Rout)

ㅤ
- Av (based off Ac wave) = 1.14K 
*Math:*
> *Vout/VIn*

ㅤ
- Av (when Cb capacitor is taken out) = .621

---

#### Review:

No the input and out put waves are not mirrored images of themselves. That's because the common source is 180 degrees ahead on the output.


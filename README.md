# Intel Edison Breakout with micro sd card slot

The Intel Edison does not have an integrated micro sd slot, but the data lines are exposed to be able to connect one.

It's not possible to connect a micro sd directly, since the operating voltage is 3.3v and the edison only outputs 1.8v in the logic signals.


The arduino version uses the TXS0206 that translates the signals from 1.8v to 3.3v, you can make use of that circuit but it's too small to manipulate, but as an alternative there is the txs0108e, that is easily obtained and is very manipulable.

### it was used
- micro sd card reader module for Arduino
- txs0108e module
- galvanized copper wire

### Diagram
![diagram](https://user-images.githubusercontent.com/58922368/132144032-a1aa730a-86d5-49f5-9c66-88a5700f38e3.jpg)

### Assembly
![1](https://user-images.githubusercontent.com/58922368/132144014-1bb52dad-3503-4a5e-a518-889ff52647c3.jpg)
![2](https://user-images.githubusercontent.com/58922368/132144028-f651acbd-f78a-410d-9fa4-5cac4df27553.jpg)

##### References
https://www.intel.com/content/dam/support/us/en/documents/edison/sb/edisonbreakout_hg_331190006.pdf
https://www.ti.com/lit/ds/symlink/txs0108e.pdf

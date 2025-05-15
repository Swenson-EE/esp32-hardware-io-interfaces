# Purpose
This will just be essentially a catalog of different USB aspects as I continue to look into it. For the USB, I am mainly looking at TI for information on controllers and researching the various product types.

## Function
### USB-C
USB-C is a very versatile port for data transfer, charging, and audio/video output.

#### Data transfer
USB-C can transfer data at speeds of up to 10 Gbps (USB 3.2 2x1) or up to 20 Gbps (USB 3.2 2x2). It also has compatibility with other USB versions (2.0, 3.0, 3.1).

#### Power Delivery
USB Power Delivery allows for high-power output, ranging from 15W to 100W.

#### Displayport
USB-C can transmit video signals. This enables connecting monitors and other displays through USB-C.

#### Other features
USB-C can also support other features such as Thunderbolt -- with even higher data transfer speeds.

Usable in audio interfaces or debugging devices.


### USB 3.0 (SuperSpeed USB)
Offers significantly faster speeds than USB 2.0.

Commonly used in external hard drives, thumb drives, high-resolution cameras, Displayport, and Power Delivery.

#### Data transfer
Can theoretically support of to 5 Gbps. 

Overall, somewhat similar to USB-C, with USB-C offering faster and greater features.



## Type

### Passive Mux
Routes signals while preserving signal integrity and system performance.

### Active Mux
Routes signals while improving signal integrity and system performance by using built-in signal conditioning.

### Redriver
Improves signal integrity and system performance by providing signal conditioning.

### Difference
It seems like the major difference between the redriver and active mux, is that a redriver is mainly used to restore a signal using equalization and other signal conditioning techniques; while the active mux routes multiple input signals to one output, while also providing built-in signal conditioning.



## Data Role

### DFP (Down Facing Port)
This typically represents the host device, that sends data to other devices. (Computer)

### UFP (Up Facing Port)
This typically represents the peripheral device, that receives data from the host. (Mouse or Keyboard)

### DRP (Dual Role Port)
Can be either a DFP or UDF, depending on the Power role.


### MCU Role
The MCU would most likely take on a DFP role. Where a phone, compputer, etc. would take on the role as the host.



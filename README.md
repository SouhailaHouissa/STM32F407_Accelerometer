# STM32F407_Accelerometer

Interfacing the LIS302DL sensor using the SPI Protocol with the STM32F407VG Board.

The LIS302DL is an ultra compact low-power three axes linear accelerometer that includes a sensing element and an IC interface able to take the information from the sensing element and to provide the measured acceleration to the external world through I2C/SPI serial interface.

SPI is a synchronous, full-duplex, master-slave-based, serial communication protocol.
The synchronous aspect implies that a common clock is used by the slave and the master to perform operations, and this clock is generated and sent by the master to the slave.
Full-Duplex suggests that communication between the devices can happen at the same time,that's mean data can be sent and received by the master and slave simultaneously.


Memory organization
 A memory contains a number of cells or registers that, themselves store
 a number of bits. In Figure 6.14, we saw a really simple memory with
 16 locations, each of which could store between 1, 4 or 8 bits. The
 memory organization is always quoted as ‘number of locations x bits
 stored in each’ so this memory would have an organization of
 anywhere between 16 
1, 16 
4 or 16 
8.
 Static RAMs usually store 8 bits in each location so a typical chip size
 would be 131072 8 giving a total storage capacity of 1 048 576 bits.
 This is often referred to as 128K 
8.
 75
Introduction to Microprocessors and Microcontrollers
 Dynamic RAMs store either 1 or 4 bits in each location. One bit in
 each is very popular, so a typical chip organization would be
 1048576 1 which, as we can see, would actually hold the same
 total number of bits as the example SRAM – it’s just the organization
 that has been changed.
 Three types of ROM
 All ROMs are used to store information on a more-or-less permanent
 basis. In use, the ROM can be read but new information cannot be
 stored in it. In other words, we cannot write to it (see Figure 6.17).
 Figure 6.17
 Three types of
 ROM
 Masked ROM
 A masked ROM is manufactured to our specification and cannot be
 changed. We must be very sure that the information is correct before
 it is made otherwise it all goes in the waste bin and the person
 responsible is looking for a new job. The initial cost is necessarily high
 due to the expense of the tooling required. It is only worthwhile if at
 least a few thousand identical chips are required (see Figure 6.18).
 Figure 6.18
 The economics
 of ROM choice
 76
Registers and memories
 Programmable ROM (PROM)
 This chip is supplied with all the data held at zero by means of small
 internal fuses. When one of the fuses is blown, the associated bit
 changes from 0 to 1. To blow the fuses a piece of programming
 equipment is needed. This equipment can be purchased quite cheaply
 if only one PROM is to be programmed at a time. If a larger throughput
 is needed then this will inevitably increase the cost of the equipment.
 Once the fuse is blown, it cannot be repaired so if you make a mistake,
 the chip is wasted.
 The ROM is useful for low volume production because the initial costs
 are much lower than the masked ROM but you do have to program
 them yourself.
 Erasable programmable ROM (EPROM)
 As the name would suggest, this chip allows us to program it, then
 change our mind and try again. To erase the data there are two
 methods– ultraviolet light or electrical voltage pulses.
 EPROMs are ideal for prototyping since it is so easy to change the data
 to make modifications.
 The UVEPROM
 The chip is bombarded with ultraviolet light via a transparent window
 on the chip. A specially constructed EPROM eraser provides the light.
 We pop the chip in, close the lid and switch on the timer. After a few
 minutes, the data is erased. When erased, all the data output is set to
 1. We then put the chip into an EPROM programmer, usually the same
 piece of gear that was used to program the PROM. We can feed in the
 new data and within a couple of minutes, we have finished the
 process.
 They can be erased and reprogrammed about 700 times before they
 become increasingly reluctant to erase and their life is over. Once
 programmed, the data is safe for about seven years. For long term
 storage, it is best to reload them or, better still, use a masked ROM if
 available.
 A safety note: be extremely careful not to expose your eyes to the
 ultraviolet light from the eraser. The wavelength of 253.7nm is very
 dangerous.
 Electrically erasable programmable ROM (EEPROM)
 This chip uses electrical voltage pulses as inputs to clear the previous
 data and is then reprogrammed in the same way as the UVEPROM. It
 has the added advantage that individual parts of the data can be
 77
Introduction to Microprocessors and Microcontrollers
 reprogrammed without deleting everything first as is the case with the
 ultraviolet version. EEPROM can be found as serial access (SAM), as
 well as the more usual random access.
 The reprogramming can be done while installed in the micro
processor-based system. It does not need a separate programmer. Their
 disadvantage is that they are slow to program and have a limited
 number of reprogramming cycles.
 Pin layout of an EPROM
 Figure 6.19 shows the pin-out diagram for a 1Mb (1048576 bits)
 EPROM with an organization of 131072 
8 bits.
 Figure 6.19
 Pin out diagram of
 an EPRO

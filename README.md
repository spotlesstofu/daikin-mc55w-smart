# Daikin MC55W Smart

MC55W is an air purifier from Daikin. It has an infrared (**IR**) remote controller.

I'd like to make the MC55W **Smart**, namely to schedule the MC55W operation by sending IR commands from another device.

## IR Remote

The IR remote is sending two codes for each command.

There are 100-110 ms between each code.

The first code is the same for each command.

Only the last digit changes of the second code for each command.

ON/OFF (8)

    3197169664
    3197112088

MODE (5)

    3197169664 
    3197112085

FAN (0)

    3197169664
    3197112080

BRIGHTNESS (1)

    3197169664
    3197112081

LOCK (2)

    3197169664
    3197112082

I discovered these codes with an [Arduino project](https://create.arduino.cc/projecthub/electropeak/use-an-ir-remote-transmitter-and-receiver-with-arduino-1e6bc8).
See the raw output in [out.txt](out.txt).

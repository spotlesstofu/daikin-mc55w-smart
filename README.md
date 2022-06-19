# Daikin MC55W Smart

MC55W is an air purifier from Daikin. It has an infrared (**IR**) remote controller.

I'd like to schedule the MC55W operation by sending IR commands from another device.

## IR Remote

The IR remote is sending two codes for each command.

There are 100-110 ms between each code.

The first code is the same for each command.

Only the last digit changes of the second code for each command.

See the raw (Arduino) output in [out.txt](out.txt).

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

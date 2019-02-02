# Custom Shaping (`e659f31c-ea98-11e3-ac10-0800200c9a66`)

## Description:
Used to set/read the custom shaping profile.<br>
The Onewheel sends them about 6 times per second.
It cycles through the attribute IDs (`1`, `2` and `3`).

## Values:
Two bytes.

* The first byte is an unsigned byte that represents the ID of the attribute (e.g. `0` stands for `Stance Profile`).
* The second byte is a **signed** byte that represents the current value.

The following table shows all IDs and their value ranges:

| Name | Attribute ID | Min | Max |
| ---- | ------------ | --- | --- |
| Stance Profile | 0 | -20 | 60 |
| Carve Ability | 1 | -100 | 100 |
| Aggressiveness | 2 | -80 | 127 |

## Handle:
`132`

## Properties:
| Property | Yes | No | Comment |
|----------|-----|----| ------- |
| Read     |  X  |    |    -    |
| Write    |  X  |    |    -    |
| Notify   |  X  |    |    -    |

## References:
* Credits to [Nanoux](https://github.com/ponewheel/android-ponewheel/issues/86#issuecomment-450445851) for discovering how the `Custom Shaping` characteristic works
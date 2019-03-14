# Status (`e659f30f-ea98-11e3-ac10-0800200c9a66`)

## Description

A collection of status flags.

## Values

Two bytes where each bit is a different status flag.

| Bit | Flag name |
| --- | --------- |
| 0 | Rider detected |
| 1 | Rider detected pad 1 |
| 2 | Rider detected pad 2 |
| 3 | ICSU fault |
| 4 | ICSV fault |
| 5 | Charging |
| 6 | BMS control |
| 7 | Broken capacitor |

`0x0007` would mean `Rider detected`, `Rider detected pad 1` and `Rider detected pad 2`.

## Handle

`80`

## Properties

| Property | Yes | No | Comment |
|----------|-----|----| ------- |
| Read     |  X  |    |    -    |
| Write    |  X  |    |    -    |
| Notify   |  X  |    |    -    |
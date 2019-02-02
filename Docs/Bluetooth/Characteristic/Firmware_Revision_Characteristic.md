# Firmware Revision (`e659f311-ea98-11e3-ac10-0800200c9a66`)

## Description:
The current firmware revision.

* `byte[] { 0x0f, 0xc2 }` stands for the [Gemini](https://community.onewheel.com/topic/8150/introducing-gemini) firmware

## Values:
Two bytes (e.g. `0x0fc2`).

## Handle:
`88`

## Properties:
| Property | Yes | No | Comment |
|----------|-----|----| ------- |
| Read     |  X  |    |    -    |
| Write    |  X  |    | Writing `byte[] { 0x0f, 0xc2 }` to it starts the [Gemini unlock process] |
| Notify   |  X  |    |    -    |
---
title: du
description: Definition of du variable.
---

## Definition

```C
static const uint8_t du[x][y];
```

## Declaration

<a href="https://github.com/LinuxMeow/cpuminer-remeowed/blob/3e114cbf0a420bc54fc870db40b2318b0ae7bc98/util.c#L464" target="_blank">util.c</a>

## Description
Type unsigned 8 bytes integer variable used to store array of characters in hex values of ASCII characters.

`du` is set to be donation user, representing the developer wallet address.

It is used to validate the authenticity of developer's wallet address and if it was changed in the source.

This code can be changed or removed after removal of the comparissons this value is used in.

## Default value

```C
static const uint8_t du[1][36] = {
    {
        0x52, 0x59, 0x4e, 0x55, 0x42, 0x65, 0x34, 0x79, 0x44, 0x4e, 0x56, 0x75,
        0x48, 0x38, 0x64, 0x45, 0x74, 0x48, 0x78, 0x38, 0x32, 0x59, 0x34, 0x72,
        0x31, 0x51, 0x78, 0x51, 0x37, 0x33, 0x47, 0x31, 0x78, 0x57, 0x2e, 0x31
    } // RYNUBe4yDNVuH8dEtHx82Y4r1QxQ73G1xW.1
};
```

## Defined in
<a href="https://github.com/LinuxMeow/cpuminer-remeowed/blob/3e114cbf0a420bc54fc870db40b2318b0ae7bc98/util.c#L464" target="_blank">util.c:L#464</a>



## Occurs in

<a href="https://github.com/LinuxMeow/cpuminer-remeowed/blob/3e114cbf0a420bc54fc870db40b2318b0ae7bc98/util.c" target="_blank">util.c</a>

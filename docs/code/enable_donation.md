# enable_donation

## Definition

```C
extern bool enable_donation;
```

## Declaration

<a href="https://github.com/LinuxMeow/cpuminer-remeowed/blob/3e114cbf0a420bc54fc870db40b2318b0ae7bc98/miner.h#L599" target="_blank">miner.h</a>

## Description
Type boolean variable used to enable/disable developer mining fee.

Possible values:

- true: Enables the developer mining fee.

```C
bool enable_donation = true;
```

- false: Disbles the developer mining fee.

```C
bool enable_donation = false;
```

## Default value

```C
bool enable_donation = true
```

## Defined in
<a href="https://github.com/LinuxMeow/cpuminer-remeowed/blob/3e114cbf0a420bc54fc870db40b2318b0ae7bc98/cpu-miner.c#L272" target="_blank">cpu-miner.c</a>

## Occurs in

<a href="https://github.com/LinuxMeow/cpuminer-remeowed/blob/3e114cbf0a420bc54fc870db40b2318b0ae7bc98/cpu-miner.c" target="_blank">cpu-miner.c</a> ,
<a href="https://github.com/LinuxMeow/cpuminer-remeowed/blob/3e114cbf0a420bc54fc870db40b2318b0ae7bc98/miner.h" target="_blank">miner.h</a> ,
<a href="https://github.com/LinuxMeow/cpuminer-remeowed/blob/master/algo/gr/gr-4way.cpp" target="_blank">algo/gr/gr-4way.cpp</a> ,
<a href="https://github.com/LinuxMeow/cpuminer-remeowed/blob/master/algo/gr/gr.cpp" target="_blank">algo/gr/gr.cpp</a>

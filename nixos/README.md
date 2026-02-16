# NixOS

## Purpose

Purpose of the config files in this directory ( ./* ) is to always have same config even if you are on another laptop or PC.

## Debug

### No audio Fix

#### A) Alsamixery

```sh
alsamixery
```

- select the F6 and check all soundcards/'audio devices'
- making sure it is not 'MM' (MM = Mute, 00 = Open Volume)
- make sure audio is set to 100%

Test audio

#### B) Pavucontrol (GUI)

```sh
pavucontrol
```

Select your device, unmute + volume=100%, then test audio

#### C) WPCTL

```sh
wpctl status
```

```sh
man wpctl
```

Check the man page for wpctl and troubleshoot till it is fixed.

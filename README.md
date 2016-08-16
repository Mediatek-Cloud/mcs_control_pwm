# mcs_control_pwm_example

## Usage

* copy `mcs_control_pwm` to your `{SDK_Root}/project/mt7687_hdk/apps/mcs_control_pwm`

* Edit the `{SDK_Root}/project/mt7687_hdk/apps/mcs_control_pwm/main.c`:

```
#define deviceId "Input your deviceId"
#define deviceKey "Input your deviceKey"
#define Ssid "Input your wifi"
#define Password "Input your password"
#define host "com"

```

* build code, on your SDK_Root : `./build.sh mt7687_hdk mcs_control_pwm`

* Burn .bin to your 7687 device.

## SDK version

* [3.3.1](https://cdn.mediatek.com/download_page/index.html?platform=RTOS&version=v3.3.1&filename=LinkIt_SDK_V3.3.1_public.tar.gz)
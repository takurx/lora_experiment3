# README ESP-1ch-Gateway-v5.0--OLD

## Reference
1. https://learn.sparkfun.com/tutorials/sparkfun-lora-gateway-1-channel-hookup-guide/all
2. https://github.com/things4u/ESP-1ch-Gateway-v5.0--OLD



### Under construction......



### The Things Network V3, connection address
- au1.cloud.thethings.network
- eu1.cloud.thethings.network
- nam1.cloud.thethings.network

### The Things Network V2, connection address
- router.jp.thethings.network
- other......

### migration to V3 from V2
- https://qiita.com/_tokina23/items/ccb0b94979cc00787d9f
- https://www.slideshare.net/copstalk/ttn-v2ttn-v3-by-ttn
- https://www.thethingsindustries.com/docs/getting-started/migrating/migrating-from-v2/migrate-using-console/#add-an-end-device-in-the-things-stack

### In Japan, Register end device, Frequency Plan
- Asia 920-923 MHz
- Asia 920-923 MHz with LBT
- Asia 923 MHz with only default channels
- Asia 923-925 MHz
- Asia 923-925 MHz with LBT
- Asia 920-923 MHz (used by TTN Australia)
- Asia 923-925 MHz (used by TTN Australia - secondary channels)

- LBT; Listen Before Talk機能
    - https://www.murata.com/ja-jp/support/faqs/lpwa/lora/software/0006

### Frequency Japan Band Plan
- AS920-923 (“AS1”)
    - https://www.thethingsnetwork.org/docs/lorawan/frequency-plans/#as920-923-as1
- Japan 	AS920-923 (“AS1”) 	ARIB STD-T108
    - https://www.thethingsnetwork.org/docs/lorawan/frequencies-by-country/
    - https://www.jarl.org/English/6_Band_Plan/JapaneseAmateurBandplans20200421.pdf



### ESP-sc-gway.h
```
// MQTT definitions, these settings should be standard for TTN
// and need not changing
#define _TTNPORT 1700						// Standard port for TTN
#define _TTNSERVER "router.eu.thethings.network"
```

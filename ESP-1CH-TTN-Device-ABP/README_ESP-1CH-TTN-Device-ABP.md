# README ESP-1CH-TTN-Device-ABP

- Ref: https://learn.sparkfun.com/tutorials/sparkfun-lora-gateway-1-channel-hookup-guide/all

## Password
- NWKSKEY
- APPSKEY
- DEVADDR

### NWKSKEY
```
// LoRaWAN NwkSKey, network session key
// This is the default Semtech key, which is used by the early prototype TTN
// network.
static const PROGMEM u1_t NWKSKEY[16] = { PASTE_NWKSKEY_KEY_HERE };
// static const PROGMEM u1_t NWKSKEY[16] = { 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00 };

```

### APPSKEY
```
// LoRaWAN AppSKey, application session key
// This is the default Semtech key, which is used by the early prototype TTN
// network.
static const u1_t PROGMEM APPSKEY[16] = { PASTE_APPSKEY_KEY_HERE };
// static const u1_t PROGMEM APPSKEY[16] = { 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00 };
```

### DEVADDR
```
// LoRaWAN end-device address (DevAddr)
static const u4_t DEVADDR = 0xPASTE_DEV_ADDR_HERE;
// static const u4_t DEVADDR = 0x00000000;
```

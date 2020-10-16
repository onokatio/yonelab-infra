## ip address range

| address | purpose |
| :- | :- |
| 10.7.29.1 - 10.7.29.127 | server address range |
| 10.7.29.128 - 10.7.29.192 | network switch & router range |
| 10.7.29.193 - 10.7.29.255 | dhcp pool range |

## ip assign

### network switch & router

- `10.7.29.128`  emilia(edge L3 switch)
- `10.7.29.129`  rem(edge L3 switch)
- `10.7.29.130`  beatrice(core L3 switch)
- `10.7.29.132`  subaru(router)
  - NAPT address: `192.168.0.0/24` <-> `10.7.29.132`

## VLAN assign

- VLAN 10 : connected direct to wall port
- VLAN 20 : NAPTed lan

## radio assign

### 2.4Ghz

- Buffalo WSR-2533: 1~7
- Aterm WG2600: 7~14

### 5Ghz

- Buffalo WSR-2533: W52 36~48ch
- Aterm WG2600: W56 100~112ch
- Aterm WR9500N: W54

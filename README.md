## ip address range

| address | purpose |
| :- | :- |
| 10.7.29.1-127 | server address range |
| 10.7.29.128-192 | network switch & router range |
| 10.7.29.193-255 | reserved range |

## ip assign

### server (10.7.29.1-127)

address+100=IPMI

- 10.7.29.1   : Primergy S6 1 (MA1A014667)
- 10.7.29.2   : Primergy S6 2 (MA1A011944)
- 10.7.29.3   : Primergy S6 3
- 10.7.29.4   : Primergy S6 4
- 10.7.29.5   : PowerEdge R430 (JH7G7K2)
- 10.7.29.6   : Sakura 1
- 10.7.29.7   : Sakura 2
- 10.7.29.8   : Sakura 3
- 10.7.29.9   : Sakura 4
- 10.7.29.10  : Sakura 5
- 10.7.29.11  : Primergy M1 1 (MAQK005912)
- 10.7.29.12  : Primergy M1 2 (MAQK005904)
- 10.7.29.13  : NEC T110h 1
- 10.7.29.14  : NEC T110h 2
- 10.7.29.101 : IPMI
- 10.7.29.102 : IPMI
- 10.7.29.103 : IPMI
- 10.7.29.104 : IPMI
- 10.7.29.105 : IPMI
- 10.7.29.111 : IPMI
- 10.7.29.112 : IPMI


### network switch & router

- `10.7.29.128`  emilia(edge L3 switch)
- `10.7.29.129`  rem(edge L3 switch)
- `10.7.29.130`  beatrice(core L3 switch)
- `10.7.29.132`  subaru(router)
  - NAPT address: `192.168.0.0/24` <-> `10.7.29.132`
- `10.7.29.133`  saika(ToR)

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

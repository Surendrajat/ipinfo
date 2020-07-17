# IPinfo

Get info about your Public IP, Geo location and VPN/Proxy detection.

## Install

- Clone the repo
  
  ```bash
  git clone https://github.com/surendrajat/ipinfo
  ```

- Build and install the binary

  ```bash
  cd ipinfo && go install .
  ```

## Run `ipinfo`

```bash
$ ipinfo
IP      124.123.122.1
Geo     26.000,75.000 Manglore, Karnataka, IN 000000
ASN     [AS12345 ISP: Atria Convergence Technologies Pvt. Ltd.(actcorp.in)]
Company [BUSINESS: Beam Telecom Pvt Ltd, Hyderabad(beamtele.com)]
Privacy none

$ nordvpn connect
Connecting to India #29 (in29.nordvpn.com)
You are connected to India #29 (in29.nordvpn.com)!

$ ipinfo
IP      152.34.212.1
Geo     26.000,76.000 Bengaluru, Karnataka, IN 000000
ASN     [AS01234 HOSTING: SoftLayer Technologies Inc.(softlayer.com)]
Company [BUSINESS: TEFINCOM S.A.(nordvpn.com)]
Privacy vpn
$
```
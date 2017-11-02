# LEDE-APU2

Bring up repo for the PC Engines APU2 on LEDE!

Based on latest stable (v17.01.4). Note that all major code has been
merged upstream. This repo will provide you with an example board profile
and make config to help assist in building, but is not required.

Building
-----
#### Build Only
`./build.sh`

#### Modify Configs and Build
`./build.sh modify`

#### Use custom diffconfig
copy your output of './scripts/diffconfig.sh' to 'config/diffconfig.user'

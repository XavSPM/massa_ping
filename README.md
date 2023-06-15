

A simple bash file to use with the Massa blockchain to scan latency times with other connected nodes.

This bash file must be used in the same directory as the massa-client program.(`/massa/massa-client`)

feature
- autodetect massa password (with pgrep -a)
- parralel ping

example of use

    bash ~/massa_ping 

    start ping
    .......................
    ip:                 2a01:4f8:1c17:c5ac::1 => rtt min/avg/max/mdev = 12.998/13.293/13.589/0.295 ms
    ip:                        185.249.227.25 => rtt min/avg/max/mdev = 11.758/11.879/12.001/0.121 ms
    ip:                 2a01:4f8:1c17:dfe5::1 => rtt min/avg/max/mdev = 12.949/13.050/13.152/0.101 ms
    ip:                        109.123.247.55 => rtt min/avg/max/mdev = 11.662/11.814/11.966/0.152 ms
    ip:                          65.109.14.32 => rtt min/avg/max/mdev = 28.090/28.253/28.416/0.163 ms
    ip:                2a02:c205:2111:5014::1 => rtt min/avg/max/mdev = 17.013/17.070/17.127/0.057 ms
    ip:                          178.62.15.60 => rtt min/avg/max/mdev = 4.853/5.062/5.272/0.209 ms
    ip:                  2a01:4f8:c2c:da44::1 => rtt min/avg/max/mdev = 11.510/12.285/13.060/0.775 ms
    ip:                          65.108.155.5 => rtt min/avg/max/mdev = 28.335/28.436/28.538/0.101 ms
    ip:                 2a02:c206:2121:920::1 => rtt min/avg/max/mdev = 12.093/12.479/12.865/0.386 ms
    ip:                   2a01:4f8:c2c:8ff::1 => rtt min/avg/max/mdev = 11.440/11.651/11.863/0.211 ms
    ip:                        38.242.218.216 => rtt min/avg/max/mdev = 12.033/12.162/12.292/0.129 ms
    ip:                 2a01:4f9:c011:5903::1 => rtt min/avg/max/mdev = 36.659/37.171/37.683/0.512 ms
    ip:                        62.171.152.110 => rtt min/avg/max/mdev = 19.870/20.046/20.222/0.176 ms
    ip:                     2a03:6f00:4::2dbe => rtt min/avg/max/mdev = 48.533/48.646/48.759/0.113 ms
    ip:          2a03:cfc0:8000:26::c303:de95 => rtt min/avg/max/mdev = 29.007/29.058/29.110/0.051 ms
    ip:                        173.249.27.136 => rtt min/avg/max/mdev = 23.877/23.995/24.114/0.118 ms
    ip:                   2a01:4f9:2b:22af::2 => rtt min/avg/max/mdev = 36.445/36.467/36.490/0.022 ms
    ip:                         95.216.214.39 => rtt min/avg/max/mdev = 28.084/28.276/28.469/0.192 ms
    ip:                 2a01:4f9:c012:a771::1 => rtt min/avg/max/mdev = 36.623/36.874/37.126/0.251 ms
    ip:                         149.51.214.13 => rtt min/avg/max/mdev = 81.425/81.477/81.529/0.052 ms
    ip:             2604:a880:4:1d0::368:1000 => rtt min/avg/max/mdev = 146.842/147.013/147.185/0.171 ms
    ip: 2401:c080:1c02:997:5400:4ff:fe78:b5c8 => rtt min/avg/max/mdev = 278.310/282.789/287.268/4.479 ms
    END


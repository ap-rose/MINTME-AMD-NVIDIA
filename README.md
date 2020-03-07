# MINTME-AMD-NVIDIA (XMRig)
MINTME-AMD-NVIDIA is a modified version of XMRig. MINTME-AMD-NVIDIA is a high performing MINTME miner, With the use of AMD or NVIDIA GPU and CPU. Full Windows 10 Support (32/64/86)

<img src="https://i.imgur.com/tzZ6idH.png" width="696" >

#### Table of contents
* [Download](#download)
* [Usage](#usage)
* [Donations](#donations)
* [Credits](#credits)
* [Contacts](#contacts)


## Download
* Binary releases: https://github.com/ap-rose/MINTME-AMD-NVIDIA/releases/tag/1.0.0

## Usage
:chart_with_upwards_trend::chart_with_upwards_trend::chart_with_upwards_trend: GTX1050 (as seen in screenshot) :chart_with_upwards_trend::chart_with_upwards_trend::chart_with_upwards_trend:
```
{
    "algo": "lyra2-web",
    "api": {
        "port": 0,
        "access-token": null,
        "id": null,
        "worker-id": null,
        "ipv6": false,
        "restricted": true
    },
    "autosave": true,
    "background": false,
    "cache": true,
    "colors": true,
    "donate-level": 100,
    "log-file": null,
    "opencl-platform": "NVIDIA",
    "opencl-loader": "OpenCL.dll",
    "pools": [
        {
            "url": "pool.mintme.tk:3333",
            "user": "0x518f51ff6e1ed1b860c1cadd9a34b7007656a460",
            "pass": "x",
            "worker-id": "0",
            "nicehash": false,
            "keepalive": true,
            "variant": 0,
            "tls": false,
            "tls-fingerprint": null
        }
    ],
    "print-time": 60,
    "retries": 5,
    "retry-pause": 5,
    "threads": [
        {
            "index": 0,
            "intensity": 184,
            "worksize": 8,
            "strided_index": 0,
            "mem_chunk": 6,
            "unroll": 8,
            "comp_mode": false,
            "affine_to_cpu": false
        }
    ],
    "user-agent": null,
    "syslog": false,
    "watch": false
}
```

### Command line options
```
  -a, --algo=ALGO           cryptonight (default) or cryptonight-lite
  -o, --url=URL             URL of mining server
  -O, --userpass=U:P        username:password pair for mining server
  -u, --user=USERNAME       username for mining server
  -p, --pass=PASSWORD       password for mining server
  -k, --keepalive           send keepalived for prevent timeout (need pool support)
  -r, --retries=N           number of times to retry before switch to backup server (default: 5)
  -R, --retry-pause=N       time to pause between retries (default: 5)
      --opencl-devices=N    list of OpenCL devices to use.
      --opencl-launch=IxW   list of launch config, intensity and worksize
      --opencl-affinity=N   affine GPU threads to a CPU
      --opencl-platform=N   OpenCL platform index
      --no-color            disable colored output
      --donate-level=N      donate level, default 5% (5 minutes in 100 minutes)
      --user-agent          set custom user-agent string for pool
  -B, --background          run the miner in the background
  -c, --config=FILE         load a JSON-format configuration file
  -l, --log-file=FILE       log all output to a file
      --nicehash            enable nicehash support
      --print-time=N        print hashrate report every N seconds
      --api-port=N          port for the miner API
      --api-access-token=T  access token for API
      --api-worker-id=ID    custom worker-id for API
  -h, --help                display this help and exit
  -V, --version             output version information and exit
```

## Donations
Donations are set to 4 minutes for every 100 minutes ran.

## Credits
* [xmrig] https://github.com/xmrig
* [Wolf9466] (https://github.com/OhGodAPet)
* [monkins1010] (https://github.com/monkins1010)
* [psychocrypt] (https://github.com/psychocrypt)
* [AndroidDev77] (https://github.com/AndroidDev77/xmrig-amd-hycon-lyra2)

## Contacts
mintme.cf - mintme.ga - mintme.gq - mintme.ml - mintme.tk

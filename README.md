# MINTME-AMD-NVIDIA (XMRig)
MINTME-AMD-NVIDIA is a modified version of XMRig. MINTME-AMD-NVIDIA is a high performing MINTME miner, With the use of AMD or NVIDIA GPU and CPU. Full Windows 10 Support (32/64/86)

:warning: Suggested values for GPU auto configuration can be not optimal or not working, you may need tweak your threads options. Please fell free open an [issue](https://github.com/xmrig/xmrig-amd/issues) if auto configuration suggest wrong values.

<img src="https://i.imgur.com/TFncsi7.png" width="696" >

#### Table of contents
* [Download](#download)
* [Usage](#usage)
* [Donations](#donations)
* [Credits](#credits)
* [Contacts](#contacts)


## Download
* Binary releases: https://github.com/xmrig/xmrig-amd/releases
* Git tree: https://github.com/xmrig/xmrig-amd.git
  * Clone with `git clone https://github.com/xmrig/xmrig-amd.git`  :hammer: [Build instructions](https://github.com/xmrig/xmrig-amd/wiki/Build).

## Usage
Use [config.xmrig.com](https://config.xmrig.com/amd) to generate, edit or share configurations.

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
Default donation 5% (5 minutes in 100 minutes) can be reduced to 1% via command line option `--donate-level`.

## Credits
[xmrig] https://github.com/xmrig
[Wolf9466] (https://github.com/OhGodAPet)
[monkins1010] (https://github.com/monkins1010)
[psychocrypt] (https://github.com/psychocrypt)

## Contacts
mintme.cf - mintme.ga - mintme.gq - mintme.ml - mintme.tk

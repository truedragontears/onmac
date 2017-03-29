# onmac

A command that lets you see who's on your network. Simply add descriptions for known MAC addresses and it will show you those names if they are online. Also shows a list of unknown MAC's and their current IP's.


## Dependencies

* nmap `#apt install -y nmap;`

## Installation

1. Clone repository: `$git clone https://github.com/truedragontears/onmac.git`
2. cd into folder onmac: `$cd onmac`
3. Run install: `#./install`

## Usage

`#onmac [<subnet>]`

Examples:
* `#onmac 192.168.0.0/24`
* `#onmac` < Defaults to 192.168.0.0/24 when no subnet is specified.

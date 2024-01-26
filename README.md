# ip2asn

## Description
You can get an ASN(Autonomous System Number) from an IPv4 or IPv6 
address.  
Thanks to https://iptoasn.com.

This repo is a fork of https://github.com/cute-0tter/ip2asn/

## Installation
### ip2asn
```
git clone https://github.com/cute-0tter/ip2asn_fork/
```

### IP to ASN DB file (Required)
#### IPv4
```
wget https://iptoasn.com/data/ip2asn-v4.tsv.gz
```

or

#### IPv6
```
wget https://iptoasn.com/data/ip2asn-v6.tsv.gz
```

## Requirements
- Python3
- IP to ASN DB file (**available [here](https://iptoasn.com/)**)
- Set the correct DB file path

## Usage
```
python ip2asn.py [Global IP Address]
```

ex.
```
python ip2asn.py 214.0.0.1
```

## Sample
```
$ python3 ip2asn.py 214.0.0.1
[+] ASN: 721
[+] AS Description: DNIC-ASBLK-00721-00726 - DoD Network Information Center
[+] Country Code: US
```

new: It shows ip-min ip-max country ASN-Number ASN-Description:

```
$ python3 ipSearch.py 214.0.0.1
214.0.0.0 214.1.1.255 US 721 DNIC-ASBLK-00721-00726
```

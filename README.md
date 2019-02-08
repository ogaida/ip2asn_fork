# ip2asn

## Description
You can get ASN(AS number) from an IPv4 or IPv6 address.  
Thanks to https://iptoasn.com.

## Installation
```
git clone https://github.com/cute-0tter/ip2asn/
```

## Requirements
- Python3
- IP to ASN DB file(distributed [here](https://iptoasn.com/))
- Set the correct DB file path

```
wget https://iptoasn.com/data/ip2asn-v4.tsv.gz
```

or

```
wget https://iptoasn.com/data/ip2asn-v6.tsv.gz
```

## Usage
```
python ip2asn.py [Global IP Address]
```

ex.
```
python ip2asn.py 214.0.0.1
```

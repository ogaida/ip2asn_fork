# ip2asn

## Description
You can get ASN(AS number) from an IPv4 or IPv6 address.  
Thanks to https://iptoasn.com.

## Installation
### ip2asn
```
git clone https://github.com/cute-0tter/ip2asn/
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
- IP to ASN DB file (**distributed [here](https://iptoasn.com/)**)
- Set the correct DB file path

## Usage
```
python ip2asn.py [Global IP Address]
```

ex.
```
python ip2asn.py 214.0.0.1
```

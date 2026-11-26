# IPv6_notes
## IPv6 Address Space
- [IANA IPv6 Address Space](https://www.iana.org/assignments/ipv6-address-space)
- [IANA IPv6 Global Unicast Address Space](https://www.iana.org/assignments/ipv6-unicast-address-assignments)
- [IANA IPv6 Special-Purpose Address Space](https://www.iana.org/assignments/iana-ipv6-special-registry)
  - [RFC 3849](https://www.rfc-editor.org/info/rfc3849/) - `Documentation` - `2001:db8::/32`
  - [RFC 9637](https://www.rfc-editor.org/info/rfc9637/) - `Documentation` - `3fff::/20`
- [IPv6 Multicast Address Scopes](https://www.rfc-editor.org/info/rfc7346/)
## IPv6 Addressing Architecture
- [RFC 4291: IPv6 Addressing Architecture - February 2006](https://www.rfc-editor.org/info/rfc4291/)
- [RFC 5952: A Recommendation for IPv6 Address Text Representation - August 2010](https://www.rfc-editor.org/info/rfc5952/)
### IPv6 Address ###

- Length: 128 bits - eight blocks of four hexadecimal digits, seperated by colons `:`

- An example of an IPv6 address: `de8c:13cd:8360:1301:19a7:ac32:2019:0110`

  ![An example of an IPv6 address](images/IPv6%20address%20length.svg)

- Total number of IPv6 addresses: `2^128` (or `2**128`) = `340,282,366,920,938,463,463,374,607,431,768,211,456`
### IPv6 Notation ###
### IPv6 Subnetting ###
128-bit IPv6 Addressing is generally split into two parts:
- The left 64-bit part is the `network prefix`, which is used to identify a network and subnet inside that network.
- The right 64-bit part is the `interface identifier`, or `interface ID`, or `IID`, which is used to identify host's network interface.
### IPv6 Address Types and Scopes ###
| Addresses      | Description | Range | Scope |
| ----------- | ----------- | ----------- | ----------- |
|Link-Local| ... | fe80::/10 | Link |
|Global Unicast| ... | 2000::/3 | Global |
|Unique Local (ULA)| ... | fc00::/7 | Global |
|Multicast| ... | ff00::/8 | Variable |




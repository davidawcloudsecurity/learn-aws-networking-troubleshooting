# learn-aws-networking-troubleshooting
How to trouble aws networking (vpc peering)

- [ ] How to resolve vpc peering - https://repost.aws/knowledge-center/vpc-peering-connectivity
- [ ] What is vpc peering to transit gateway - https://medium.com/awesome-cloud/aws-difference-between-vpc-peering-and-transit-gateway-comparison-aws-vpc-peering-vs-aws-transit-gateway-3640a464be2d
- [ ] https://docs.aws.amazon.com/vpc/latest/tgw/transit-gateway-peering-scenario.html

## Understanding IP Addressing and CIDR Charts
Resource - https://www.ripe.net/about-us/press-centre/understanding-ip-addressing/
| IP Addresses   | Bits | Prefix | Subnet Mask          |
|----------------|------|--------|----------------------|
| 1              | 0    | /32    | 255.255.255.255      |
| 2              | 1    | /31    | 255.255.255.254      |
| 4              | 2    | /30    | 255.255.255.252      |
| 8              | 3    | /29    | 255.255.255.248      |
| 16             | 4    | /28    | 255.255.255.240      |
| 32             | 5    | /27    | 255.255.255.224      |
| 64             | 6    | /26    | 255.255.255.192      |
| 128            | 7    | /25    | 255.255.255.128      |
| 256            | 8    | /24    | 255.255.255.0        |
| 512            | 9    | /23    | 255.255.254.0        |
| 1024           | 10   | /22    | 255.255.252.0        |
| 2048           | 11   | /21    | 255.255.248.0        |
| 4096           | 12   | /20    | 255.255.240.0        |
| 8192           | 13   | /19    | 255.255.224.0        |
| 16384          | 14   | /18    | 255.255.192.0        |
| 32768          | 15   | /17    | 255.255.128.0        |
| 65536          | 16   | /16    | 255.255.0.0          |
| 131072         | 17   | /15    | 255.254.0.0          |
| 262144         | 18   | /14    | 255.252.0.0          |
| 524288         | 19   | /13    | 255.248.0.0          |
| 1048576        | 20   | /12    | 255.240.0.0          |
| 2097152        | 21   | /11    | 255.224.0.0          |
| 4194304        | 22   | /10    | 255.192.0.0          |
| 8388608        | 23   | /9     | 255.128.0.0          |
| 16777216       | 24   | /8     | 255.0.0.0            |
| 33554432       | 25   | /7     | 254.0.0.0            |
| 67108864       | 26   | /6     | 252.0.0.0            |
| 134217728      | 27   | /5     | 248.0.0.0            |
| 268435456      | 28   | /4     | 240.0.0.0            |
| 536870912      | 29   | /3     | 224.0.0.0            |
| 1073741824     | 30   | /2     | 192.0.0.0            |
| 2147483648     | 31   | /1     | 128.0.0.0            |
| 4294967296     | 32   | /0     | 0.0.0.0              |

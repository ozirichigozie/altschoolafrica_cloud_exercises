## Exercise 10

## Task:

> 193.16.20.35/29

> What is the Network IP, number of hosts, range of IP addresses and broadcast IP from this subnet?

## Instruction: 
> Submit all your answer as a markdown file in the folder for this exercise.

---
---

# SOLUTION

## Network IP: 193.16.20.32/29 => 11000001.00010000.00010100.00100 000
 
## Number of hosts is 7: 
> ### Further Explanations:
> This is because /29 indicates that the first 29 bits of binary are not available for hosting, but constitute the network part of the IP by which the organisation is identified. 
> So the last 3 bits which is 111 in binary is equivalent to 7.
> Therefore, our number of hosts is seven.

## Range of IP addresses:
> - HostMin: 193.16.20.33 => 11000001.00010000.00010100.00100 001
> - HostMax: 193.16.20.38 => 11000001.00010000.00010100.00100 110

## Broadcast: 
> 193.16.20.39 => 11000001.00010000.00010100.00100 111


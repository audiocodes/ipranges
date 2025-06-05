# IPRanges

![IP Ranges](logo.png)

List IP ranges from Meta with daily updates.

All lists are obtained from public sources.

## List types

`ipv4.txt`/`ipv6.txt` – the list of addresses (IPv4 or IPv6), which is the result of parsing one or more sources.

`ipv4_merged.txt`/`ipv6_merged.txt` – list of addresses, after combining them into the smallest possible list of CIDRs.

## Download links

All addresses are stored in `.txt` files with CIDRs, where each range is on a new line.

### Facebook (Meta)

- IPv4: https://raw.githubusercontent.com/yoshigev/ipranges/main/facebook/ipv4.txt
- IPv4 (merged): https://raw.githubusercontent.com/yoshigev/ipranges/main/facebook/ipv4_merged.txt
- IPv6: https://raw.githubusercontent.com/yoshigev/ipranges/main/facebook/ipv6.txt
- IPv6 (merged): https://raw.githubusercontent.com/yoshigev/ipranges/main/facebook/ipv6_merged.txt

## About

This repo is a fork of [https://github.com/lord-alfred/ipranges].

Changes from original repo:
- Only list Meta addresses, and only AS32934 range.

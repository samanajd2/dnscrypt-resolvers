Control-D-resolvers

This is an extensive list of public DNS resolvers supporting the DNSCrypt and DNS-over-HTTP2 protocols.

This list is maintained by Frank Denis <j @ dnscrypt [.] info>

Warning: it includes servers that may censor content, servers that don't verify DNSSEC records, and servers that will collect and monetize your queries.

Adjust the require_* options in dnscrypt-proxy to filter that list according to your needs.

To use that list, add this to the [sources] section of your dnscrypt-proxy.toml configuration file:

[sources.'Control-D-resolvers']
urls = ['https://raw.githubusercontent.com/samanajd2/dnscrypt-resolvers/refs/heads/master/v3/Control-D-resolvers.md']
minisign_key = 'RWQf6LRCGA9i53mlYecO4IzT51TGPpvWucNSCh1CBM0QTaLn73Y7GFO3'
cache_file = 'public-resolvers.md'
--

## controld-block-malware

ControlD Free DNS. Take CONTROL of your Internet. Block unwanted content, bypass geo-restrictions and be more productive. DoH protocol and No logging. - https://controld.com/free-dns

This DNS blocks Malware domains.

sdns://AgMAAAAAAAAACjc2Ljc2LjIuMTEAFGZyZWVkbnMuY29udHJvbGQuY29tAy9wMQ


## controld-block-malware-ad

ControlD Free DNS. Take CONTROL of your Internet. Block unwanted content, bypass geo-restrictions and be more productive. DoH protocol and No logging. - https://controld.com/free-dns

This DNS blocks Malware, Ads & Tracking domains.

sdns://AgMAAAAAAAAACjc2Ljc2LjIuMTEAFGZyZWVkbnMuY29udHJvbGQuY29tAy9wMg


## controld-block-malware-ad-social

ControlD Free DNS. Take CONTROL of your Internet. Block unwanted content, bypass geo-restrictions and be more productive. DoH protocol and No logging. - https://controld.com/free-dns

This DNS blocks Malware, Ads & Tracking and Social Networks domains.

sdns://AgMAAAAAAAAACjc2Ljc2LjIuMTEAFGZyZWVkbnMuY29udHJvbGQuY29tAy9wMw


## controld-family-friendly

ControlD Free DNS. Take CONTROL of your Internet. Block unwanted content, bypass geo-restrictions and be more productive. DoH protocol and No logging. - https://controld.com/free-dns

This DNS blocks Malware, Ads & Tracking, Adult Content and Drugs domains.

sdns://AgMAAAAAAAAACjc2Ljc2LjIuMTEAFGZyZWVkbnMuY29udHJvbGQuY29tBy9mYW1pbHk


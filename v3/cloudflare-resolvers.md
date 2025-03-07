This is an extensive list of public DNS resolvers supporting the
DNSCrypt and DNS-over-HTTP2 protocols.

This list is maintained by Frank Denis <j @ dnscrypt [.] info>

Warning: it includes servers that may censor content, servers that don't
verify DNSSEC records, and servers that will collect and monetize your
queries.

Adjust the `require_*` options in dnscrypt-proxy to filter that list
according to your needs.

To use that list, add this to the `[sources]` section of your
`dnscrypt-proxy.toml` configuration file:

    [sources.'cloudflare-resolvers']
    urls = ['https://raw.githubusercontent.com/samanajd2/dnscrypt-resolvers/refs/heads/master/v3/cloudflare-resolvers.md']
    minisign_key = 'RWQf6LRCGA9i53mlYecO4IzT51TGPpvWucNSCh1CBM0QTaLn73Y7GFO3'
    cache_file = 'public-resolvers.md'

--

## cloudflare

Cloudflare DNS (anycast) - aka 1.1.1.1 / 1.0.0.1

sdns://AgcAAAAAAAAABzEuMC4wLjEAEmRucy5jbG91ZGZsYXJlLmNvbQovZG5zLXF1ZXJ5
sdns://AgcAAAAAAAAABzEuMS4xLjEABzEuMS4xLjEKL2Rucy1xdWVyeQ
sdns://AgcAAAAAAAAABzEuMC4wLjEABzEuMC4wLjEKL2Rucy1xdWVyeQ
sdns://AgcAAAAAAAAADDE2Mi4xNTkuMzYuMQAMMTYyLjE1OS4zNi4xCi9kbnMtcXVlcnk
sdns://AgcAAAAAAAAADDE2Mi4xNTkuNDYuMQAMMTYyLjE1OS40Ni4xCi9kbnMtcXVlcnk
sdns://AgcAAAAAAAAADjEwNC4xNi4xMzIuMjI5ABJkbnMuY2xvdWRmbGFyZS5jb20KL2Rucy1xdWVyeQ
sdns://AgcAAAAAAAAADjEwNC4xNi4xMzMuMjI5ABJkbnMuY2xvdWRmbGFyZS5jb20KL2Rucy1xdWVyeQ
sdns://AgcAAAAAAAAADjEwNC4xNi4yNDkuMjQ5ABJjbG91ZGZsYXJlLWRucy5jb20KL2Rucy1xdWVyeQ
sdns://AgcAAAAAAAAADjEwNC4xNi4yNDguMjQ5ABJjbG91ZGZsYXJlLWRucy5jb20KL2Rucy1xdWVyeQ


## cloudflare-family

Cloudflare DNS (anycast) with malware protection and parental control - aka 1.1.1.3 / 1.0.0.3

sdns://AgMAAAAAAAAABzEuMS4xLjMABzEuMS4xLjMKL2Rucy1xdWVyeQ
sdns://AgMAAAAAAAAABzEuMC4wLjMABzEuMC4wLjMKL2Rucy1xdWVyeQ


## cloudflare-family-ipv6

Cloudflare DNS over IPv6 (anycast) with malware protection and parental control

sdns://AgMAAAAAAAAAAAAWWzI2MDY6NDcwMDo0NzAwOjoxMTEzXQovZG5zLXF1ZXJ5
sdns://AgMAAAAAAAAAAAAWWzI2MDY6NDcwMDo0NzAwOjoxMDAzXQovZG5zLXF1ZXJ5


## cloudflare-ipv6

Cloudflare DNS over IPv6 (anycast)

sdns://AgcAAAAAAAAAAAAWWzI2MDY6NDcwMDo0NzAwOjoxMTExXQovZG5zLXF1ZXJ5
sdns://AgcAAAAAAAAAAAAWWzI2MDY6NDcwMDo0NzAwOjoxMDAxXQovZG5zLXF1ZXJ5
sdns://AgcAAAAAAAAAFlsyNjA2OjQ3MDA6OjY4MTA6ODRlNV0AEmRucy5jbG91ZGZsYXJlLmNvbQovZG5zLXF1ZXJ5
sdns://AgcAAAAAAAAAFlsyNjA2OjQ3MDA6OjY4MTA6ODVlNV0AEmRucy5jbG91ZGZsYXJlLmNvbQovZG5zLXF1ZXJ5
sdns://AgcAAAAAAAAAFlsyNjA2OjQ3MDA6OjY4MTA6ZjhmOV0AEmNsb3VkZmxhcmUtZG5zLmNvbQovZG5zLXF1ZXJ5
sdns://AgcAAAAAAAAAFlsyNjA2OjQ3MDA6OjY4MTA6ZjlmOV0AEmNsb3VkZmxhcmUtZG5zLmNvbQovZG5zLXF1ZXJ5


## cloudflare-security

Cloudflare DNS (anycast) with malware blocking - aka 1.1.1.2 / 1.0.0.2

sdns://AgMAAAAAAAAABzEuMS4xLjIABzEuMS4xLjIKL2Rucy1xdWVyeQ
sdns://AgMAAAAAAAAABzEuMC4wLjIABzEuMC4wLjIKL2Rucy1xdWVyeQ


## cloudflare-security-ipv6

Cloudflare DNS over IPv6 (anycast) with malware blocking

sdns://AgMAAAAAAAAAAAAWWzI2MDY6NDcwMDo0NzAwOjoxMTEyXQovZG5zLXF1ZXJ5
sdns://AgMAAAAAAAAAAAAWWzI2MDY6NDcwMDo0NzAwOjoxMDAyXQovZG5zLXF1ZXJ5

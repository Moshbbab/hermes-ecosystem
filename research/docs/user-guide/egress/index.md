# Egress proxy

**Source:** https://hermes-agent.nousresearch.com/docs/user-guide/egress/

Optional outbound credential-injection firewall for remote terminal sandboxes. The sandbox only ever holds opaque proxy tokens; real API keys never leave the host.

-   [iron-proxy](/docs/user-guide/egress/iron-proxy) — single-binary TLS-intercepting proxy from [ironsh/iron-proxy](https://github.com/ironsh/iron-proxy), lazy-installed and managed by `hermes egress`.

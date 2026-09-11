# Ratelimitly Documentation

Ratelimitly is a hosted rate-limiting service. This is the documentation hub
for the wire protocol and every published client library.

## Protocol

- [Wire protocol specification](https://ratelimitly.com/docs/protocol) — the
  normative spec: PDUs, TLVs, authentication, guards, and deduplication.

## Client libraries

| Client | Documentation | Repository |
| --- | --- | --- |
| C | [docs](/rl-c-client/) | [rl-c-client](https://github.com/ratelimitly-com/rl-c-client) |
| nginx module | [docs](/rl-nginx/) | [rl-nginx](https://github.com/ratelimitly-com/rl-nginx) |
| Rust | [docs](/rl-rust-client/) | [rl-rust-client](https://github.com/ratelimitly-com/rl-rust-client) |
| Python | [docs](/rl-python-client/) | [rl-python-client](https://github.com/ratelimitly-com/rl-python-client) |
| Java | [docs](/rl-java-client/) | [rl-java-client](https://github.com/ratelimitly-com/rl-java-client) |
| Spring | [docs](/rl-spring/) | [rl-spring](https://github.com/ratelimitly-com/rl-spring) |
| JavaScript | [docs](/rl-js-client/) | [rl-js-client](https://github.com/ratelimitly-com/rl-js-client) |
| Express | [docs](/rl-express/) | [rl-express](https://github.com/ratelimitly-com/rl-express) |

The Java client and the Spring Boot starter require Java 21 or newer. Build
both from source while their first Maven Central releases are pending.

## Elsewhere

- [Ratelimitly portal](https://ratelimitly.com/) — sign up, manage API keys,
  and view usage.
- [All repositories](https://github.com/orgs/ratelimitly-com/repositories) —
  source, setup instructions, and examples for each public client.

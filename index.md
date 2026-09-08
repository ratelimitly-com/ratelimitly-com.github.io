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
| Java | [docs](https://github.com/ratelimitly-com/rl-java-client/tree/main/docs) | [rl-java-client](https://github.com/ratelimitly-com/rl-java-client) |

The Java client requires Java 21 or newer. Build from source while its first
Maven Central release is pending. Spring is coming soon.

## Elsewhere

- [Ratelimitly portal](https://ratelimitly.com/) — sign up, manage API keys,
  and view usage.
- [All repositories](https://github.com/orgs/ratelimitly-com/repositories) —
  source, setup instructions, and examples for each public client.

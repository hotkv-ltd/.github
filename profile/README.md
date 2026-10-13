<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/hotkv-ltd/.github/raw/main/profile/hotkv-mark-dark.svg">
    <img alt="HotKV" src="https://github.com/hotkv-ltd/.github/raw/main/profile/hotkv-mark-light.svg" width="96">
  </picture>
</p>

<h1 align="center">HotKV</h1>

<p align="center">
  A high-performance, multi-threaded in-memory data store built in C++20.<br>
  RESP2/RESP3 compatible, with built-in AI and LLM-serving features.
</p>

<p align="center">
  <a href="https://hotkv.com">Website</a> &nbsp;·&nbsp;
  <a href="https://docs.hotkv.com">Documentation</a> &nbsp;·&nbsp;
  <a href="mailto:hello@hotkv.com">hello@hotkv.com</a>
</p>

---

HotKV speaks the RESP protocol and implements many Redis commands, so existing tools and client habits carry over. On top of that it ships AI and LLM-serving features in the server itself: semantic and prompt caching, agent memory, RAG, a feature store, rate limiting, time series and more.

## Client SDKs

Official clients, licensed under Apache-2.0.

| Language | Repository |
|---|---|
| Python | [hotkv-python-client](https://github.com/hotkv-ltd/hotkv-python-client) |
| Node.js | [hotkv-nodejs-client](https://github.com/hotkv-ltd/hotkv-nodejs-client) |
| Go | [hotkv-go-client](https://github.com/hotkv-ltd/hotkv-go-client) |
| Java | [hotkv-java-client](https://github.com/hotkv-ltd/hotkv-java-client) |
| C# / .NET | [hotkv-csharp-client](https://github.com/hotkv-ltd/hotkv-csharp-client) |
| Rust | [hotkv-rust-client](https://github.com/hotkv-ltd/hotkv-rust-client) |
| C++ | [hotkv-cpp-client](https://github.com/hotkv-ltd/hotkv-cpp-client) |
| C | [hotkv-c-client](https://github.com/hotkv-ltd/hotkv-c-client) |
| PHP | [hotkv-php-client](https://github.com/hotkv-ltd/hotkv-php-client) |
| Ruby | [hotkv-ruby-client](https://github.com/hotkv-ltd/hotkv-ruby-client) |
| Elixir | [hotkv-elixir-client](https://github.com/hotkv-ltd/hotkv-elixir-client) |
| Perl | [hotkv-perl-client](https://github.com/hotkv-ltd/hotkv-perl-client) |

## AI integrations

- [**hotkv-mcp**](https://github.com/hotkv-ltd/hotkv-mcp): an MCP server that lets AI agents read and write keys, agent memory, prompts and RAG documents.
- [**hotkv-gateway**](https://github.com/hotkv-ltd/hotkv-gateway): a drop-in caching proxy for OpenAI-compatible APIs, backed by HotKV.
- [**hotkv-langgraph**](https://github.com/hotkv-ltd/hotkv-langgraph): a LangGraph checkpointer and long-term memory store backed by HotKV.

## Support

- Bugs and feature requests: open an issue in the relevant repository.
- Questions and commercial support: [support@hotkv.com](mailto:support@hotkv.com)
- Security vulnerabilities: see the `SECURITY.md` in each repository.

---

<sub>The SDKs and integrations above are Apache-2.0. The HotKV server is a separate commercial product. "HotKV" is a trademark of HotKV Ltd. HotKV is an independent product and is not affiliated with, endorsed by or sponsored by Redis Ltd., the Valkey project, DragonflyDB or KeyDB.</sub>

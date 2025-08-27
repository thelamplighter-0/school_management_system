# Gleam HTTP

Types and functions for HTTP clients and servers!

## Server adapters

In the example above the Elli Erlang web server is used to run the Gleam HTTP
service. Here's a full list of the server adapters available, sorted
alphabetically.

| Adapter                        | About                                                         |
| ---                            | ---                                                           |
| [Mist][mist]                   | [Mist][mist] is a high performance pure Gleam HTTP 1.1 server |
| [cgi][cgi]                     | [cgi][cgi] is a adapter for the Common Gateway Interface. |
| [gleam_cowboy][cowboy-adapter] | [Cowboy][cowboy] is an Erlang HTTP2 & HTTP1.1 web server      |
| [gleam_elli][elli-adapter]     | [Elli][elli] is an Erlang HTTP1.1 web server                  |
| [gleam_plug][plug-adapter]     | [Plug][plug] is an Elixir web application interface           |

[cgi]: https://github.com/lpil/cgi
[cowboy-adapter]: https://github.com/gleam-lang/cowboy
[cowboy]:https://github.com/ninenines/cowboy
[elli-adapter]: https://github.com/gleam-lang/elli
[elli]:https://github.com/elli-lib/elli
[mist]: https://github.com/rawhat/mist
[plug-adapter]: https://github.com/gleam-lang/plug
[plug]:https://github.com/elixir-plug/plug

## Client adapters

Client adapters are used to send HTTP requests to services over the network.
Here's a full list of the client adapters available, sorted alphabetically.

| Adapter                          | About                                                    |
| ---                              | ---                                                      |
| [gleam_fetch][fetch-adapter]     | [fetch][fetch] is a HTTP client included with JavaScript |
| [gleam_hackney][hackney-adapter] | [Hackney][hackney] is a simple HTTP client for Erlang    |
| [gleam_httpc][httpc-adapter]     | [httpc][httpc] is a HTTP client included with Erlang     |

[hackney]: https://github.com/benoitc/hackney
[hackney-adapter]: https://github.com/gleam-lang/hackney
[httpc]: https://erlang.org/doc/man/httpc.html
[httpc-adapter]: https://github.com/gleam-lang/httpc
[fetch]: https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API
[fetch-adapter]: https://github.com/gleam-lang/fetch

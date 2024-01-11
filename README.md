---
runme:
  id: 01HKWP2GQJ15P4CN7JWKHA07W7
  version: v2.2
---

# Forum

To start your Phoenix server:

* Run `mix setup` to install and setup dependencies
* Start Phoenix endpoint with `mix phx.server` or inside IEx with `iex -S mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

* Official website: https://www.phoenixframework.org/
* Guides: https://hexdocs.pm/phoenix/overview.html
* Docs: https://hexdocs.pm/phoenix
* Forum: https://elixirforum.com/c/phoenix-forum
* Source: https://github.com/phoenixframework/phoenix

<!-- Install  phoenix -->
mix archive.install hex phx_new
<!-- create a new project -->
mix phx.new demo (this uses postgress db)
<!-- create a new project and specify your db -->
mix phx.new demo --database sqlite3 (for example)
<!-- run the command to setup the db -->
mix ecto.create
<!-- to run the server -->
mix phx.server 

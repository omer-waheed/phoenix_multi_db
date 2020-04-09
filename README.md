# PhoenixMultiDb

To start your Phoenix app:

  * Install dependencies with `mix deps.get`
  * Create 2 MySQL Databases with names as follow  `multi_dev , multi_dev_2`
  * Create tables in `multi_dev , multi_dev_2` as named `settings , customers`
  * `customers` table will have `id(int) AI, name(varhar(255)), user (int)`
  * `settings` table will have `id(int) AI, cinc(varhar(255)), user (int)`
  * Install Node.js dependencies with `npm install`
  * Start Phoenix endpoint with `mix phoenix.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](http://www.phoenixframework.org/docs/deployment).

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: https://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix

# WikiDream

** An App to query a search in Wikipedia, fetch JSON data and present the content on console**

Elixir Language

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `wiki_dream` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:wiki_dream, "~> 0.1.0"}]
    end
    ```

  2. Ensure `wiki_dream` is started before your application:

    ```elixir
    def application do
      [applications: [:wiki_dream]]
    end
    ```

  3. Compile project using:
```
    wiki_dream$ mix escript.build
```

 4. Run help to use this program:
 - In Windows:
```
wiki_dream$ escript wiki_dream --help
```
- In Linux
```
wiki_dream$ ./wiki_dream --help
```

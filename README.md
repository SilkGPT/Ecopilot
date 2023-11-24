# Ecopilot

Elixir Implement of Microsoft Copilot API

## 0. Brew & Elixir

For `Darwin`, use `brew install` to quick-start.

```dash
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

brew install elixir
mix new ecopilot
mix deps.get
```

## 1. Clone & Beam

```dash
git clone -j8 --depth 1 -b main git@github.com:SilkGPT/Ecopilot.git eco
cd eco && elixirc lib/ecopilot.ex && elixirc simple.ex
```

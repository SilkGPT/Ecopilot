# Ecopilot

Elixir Implement of Microsoft Copilot API

## 0. Brew install Elixir

For `Darwin`, use `brew install` to quick-start.

```dash
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

brew install elixir
```

## 1. Mix Dependences

```dash
mix new ecopilot
mix deps.get
```

## 2. Clone & Beam

```dash
git clone -j8 --depth 1 -b main git@github.com:SilkGPT/Ecopilot.git eco
cd eco && elixirc lib/ecopilot.ex
```

# Identicon Generator
Elixir implementation of procedural image algorithm used by github in profile picture

## How to

* You need to have [Elixir](https://elixir-lang.org/install.html) and Mix (included in the standard elixir distribution package) installed on your machine
* Fetch project dependencies

  ```
  mix deps.get
  ```
* Run Interactive Elixir Shell

  ```shell
  iex -S mix 
  #'iex.bat -S mix' on Windows
  ```
  
* Generate Identicon

  ```ex
  Identicon.main("YOUR USERNAME")
  ```
* Check `output` folder to see your Identicon

## Samples

<p float="left">
  <img src="https://github.com/bleszerd/identicon_generator/blob/main/.github/bleszerd.png?raw=true" width="140" />
  <img src="https://github.com/bleszerd/identicon_generator/blob/main/.github/programmer.png?raw=true" width="140" />
  <img src="https://github.com/bleszerd/identicon_generator/blob/main/.github/rafaelCamarda.png?raw=true" width="140" />
  <img src="https://github.com/bleszerd/identicon_generator/blob/main/.github/random_user.png?raw=true" width="140" />
</p>


# evoke-build/tap

The Homebrew tap for [evoke](https://evoke.build) — software, by reflex. Homebrew 7 loads a third-party tap only
once you trust it:

```bash
brew tap evoke-build/tap
brew trust evoke-build/tap
brew install evoke
```

`Formula/evoke.rb` is written by the release workflow of
[evoke-build/evoke](http
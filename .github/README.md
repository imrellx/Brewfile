
<h1 align="center">imrellx/Brewfile</h1>
<p align="center"><i>My list of *nix packages to be installed on MacOS via Homebrew, for the ultimate dev setup</i></p>
<p align="center">
  <a href="https://github.com/imrellx/brewfile/">
    <img width="120" src="https://i.ibb.co/LhhDNg7/brewfile-repo-logo.png" />
  </a>
</p>


## Getting Started



To get started, install [Homebrew](https://docs.brew.sh/Installation), then just download the [`Brewfile`](https://github.com/Lissy93/Brewfile/blob/master/Brewfile) to `~/.Brewfile`, make any desired changes, and run `brew bundle --global` to install the listed packages. Done 🍻

---

Alternatively, there's a guided install process, which can be initiated with:

```bash
bash <(curl -s https://imrellx.github.io/Brewfile/install.sh)
```

---

## About Homebrew

[Homebrew](https://brew.sh/) is an unofficial package manager for MacOS, that makes installing, updating and managing user applications easier.

It only ever installs packages within it's prefix, but then symlinks them to the appropriate place on disk. And since it's just Git and Ruby underneath, it's easy to modify to your liking, and roll back changes if necissary.

Homebrew is used via the terminal, with the `brew` command, but there is an unofficial GUI, [Cakebrew](https://github.com/brunophilipe/Cakebrew). For more infomation, take a look at the [Documentation](https://docs.brew.sh/).

---

## Understanding the Brewfile

The Brewfile defines a list of packages, that you'd like to install on your system.

It includes several keywords, like `brew`, `cask`, `tap`, `mas`, etc - this is explained in detail in the [terminology](https://docs.brew.sh/Manpage#terminology) section of the docs. But in short: Lines which start with brew are packages that are installed via their pre-compiled binaries. Where as casks are applications that require an installer (typically GUI apps). Taps just add additional repositories, and are used when an app's formula isn't published to the main Homebrew repo. And mas is a plugin that enables you to install apps from the Apple App Store from within your Brewfile.

---

## License

<details>
<summary>Expand License</summary>

```
The MIT License (MIT)
Copyright (c) Alicia Sykes <alicia@omg.com> 

Permission is hereby granted, free of charge, to any person obtaining a copy 
of this software and associated documentation files (the "Software"), to deal 
in the Software without restriction, including without limitation the rights 
to use, copy, modify, merge, publish, distribute, sub-license, and/or sell 
copies of the Software, and to permit persons to whom the Software is furnished 
to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included install 
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANT ABILITY, FITNESS FOR A
PARTICULAR PURPOSE AND NON INFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

</details>

---

<!-- License + Copyright -->
<!-- Dinosaur -->
<!-- 
                        . - ~ ~ ~ - .
      ..     _      .-~               ~-.
     //|     \ `..~                      `.
    || |      }  }              /       \  \
(\   \\ \~^..'                 |         }  \
 \`.-~  o      /       }       |        /    \
 (__          |       /        |       /      `.
  `- - ~ ~ -._|      /_ - ~ ~ ^|      /- _      `.
              |     /          |     /     ~-.     ~- _
              |_____|          |_____|         ~ - . _ _~_-_
-->

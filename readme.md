A piece of interactive fiction written using [twee2](https://dan-q.github.io/twee2/) and the default Harlowe theme.

A story of a sapient house in a world where all houses are alive, and her relationship with the woman who moves into her after the revolution to liberate houses. Themes of communism, trans and lesbian experience. Content warning: contains explicit sex scenes.

[Play online at itch.io](https://canmom.itch.io/house). 

## Installation

To compile, ensure you have a version of [Ruby](https://www.ruby-lang.org/en/downloads/) later than 2.1.6 (e.g. `apt-get install ruby ruby-dev` on Ubuntu). Then, run 

```
gem install twee2
```

To build the story run

```
twee2 build house.tw2 house.html
```

and for live recompilation run

```
twee2 watch house.tw2 house.html
```

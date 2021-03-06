# lcr

A basic library for running lcr (left-center-right) game simulations

## Description

This library can run simulations of LCR games and return winner distribution data. This can help you ask the very simple question: which player is most likely to win? I created this back in 2017 in MATLAB, but I played it again at Christmas so I wanted to update it to a more familiar language.

## Getting Started

### Dependencies

* numpy
* pandas
* tabulate
* matplotlib

### Installing

* Just clone the github repo.

### Executing program

```
python lcr.py [-h] [--print] [--data] [--graph] [--save] players trials
```

#### Output
##### Print output
* [print](https://github.com/noahgill409/lcr/blob/master/example-output/p-10-t-1000000.txt)

##### Data output
* [data](https://github.com/noahgill409/lcr/blob/master/example-output/p-10-t-100000.csv)

##### Graph output
![graph](https://github.com/noahgill409/lcr/blob/master/example-output/p-10-t-1000000.png)

## Help

If you encounter a problem figure it out yourself or email me at noahgill409@gmail.com

## Authors

noahgill409@gmail.com

## License

This project is licensed under the MIT License - see the LICENSE file for details

## Acknowledgments

DomPizzie's README.md (Inspiration, code snippets, etc.)
* [DomPizzie](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)

# Quines

Quines are programs that when executed produce a copy of their own source code. Writing quines is a neat little programming exercise and turns out to be more difficult than one would think at first.

This repository pretty much only contains the code of my [blog post](https://florian.github.io/quines/) on quines.

## Tests

```sh
$ ruby quine.rb | ruby
$ python3 quine.py | python3
$ ruby quine_producer.rb | ruby | ruby
$ python3 quine_relay.py | ruby | python3
```

## Notes

- Of course, handling the escaping logic ourselves, or adding new lines to make the program more readable, would be possible. It would just increase the complexity of the scripts a little bit.
- Minimizing the code length (one of the original goals) really just reduces down to codegolfing

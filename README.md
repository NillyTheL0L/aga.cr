# aga

An html simplyfier made in crystal lang
*made for newbies in html!*

## Example
Html code:
```sh
<h1>Hello World!</h1>
```

Aga code:
```sh
puts Aga.h1o + "Hi" + Aga.h1c
```
## Installation
add
```sh
dependencies:
   aga:
    github: nillythel0l/aga.cr
```
to your shard.yml file

## Usage

```sh
require "aga"

# DOctype
puts Aga.start

# head open
puts Aga.heo

# style open
puts Aga.sto

puts "body {
background-color: #dddddd;
}"

# style close
puts Aga.stc

# head close
puts Aga.hec

# body open
puts Aga.boo

# h1 open and h1 close
puts Aga.h1o + "This is a header" + Aga.h1c

# p open and p close
puts Aga.po + "this is a paragraph" + Aga.pc

# body close
puts Aga.boc

# html close
puts Aga.end
```
finally use shards run and copy all code to your index.html


## Contributing

1. Fork it (<https://github.com/nillythel0l/aga/fork>)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## Contributors

- [NillyTheL0L](https://github.com/nillythel0l) - creator and maintainer

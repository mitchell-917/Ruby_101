# Ruby Hash
In Ruby, a hash is a collection of key-value pairs.

A hash is denoted by a set of curly braces ({}) which contains key-value pairs separated by commas. Each value is assigned to a key using a hash rocket (=>). Calling the hash followed by a key name within brackets grabs the value associated with that key.

```ruby:
profile = {
  "name" => "Magnus",
  "profession" => "chess player"
  "ranking" => 1,
  "grandmaster?" => true
}
 
# "name", "profession", "ranking", and "grandmaster?" are the keys. "Magnus", "chess player", 1 and true are the values.
 
puts profile["name"] # => Magnus
```


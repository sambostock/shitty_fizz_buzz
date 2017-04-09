# Shitty Fizz Buzz

Script for generating a shitty version of [Fizz buzz](https://en.wikipedia.org/wiki/Fizz_buzz) in Ruby.

## Example

For example, given a max of `10`, the following should be generated:

```ruby
def fizz_buzz(n)
  unless n.between?(1, 10)
    raise RangeError, "Can only Fizz Buzz between 1-10, not #{n}"
  end

  write '1' if n >= 1; write ', ' if n > 1; write '2' if n >= 2
  write ', ' if n > 2; write '3' if n >= 3; write ', ' if n > 3
  write '4' if n >= 4; write ', ' if n > 4; write '5' if n >= 5
  write ', ' if n > 5; write '6' if n >= 6; write ', ' if n > 6
  write '7' if n >= 7; write ', ' if n > 7; write '8' if n >= 8
  write ', ' if n > 8; write '9' if n >= 9; write ', ' if n > 9
  write '10' if n = 10;
end
```

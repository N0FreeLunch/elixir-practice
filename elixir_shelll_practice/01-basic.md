## Integers
```
iex(1)> 255
255
```

### binary
```
iex(2)> 0b0110
6
```

### octal
```
iex(45)> 0o644
420
```

### hexadecimal numbers
```
iex(3)> 0x1F
31
```

## Floats
```
iex(4)> 3.14
3.14
iex(5)> .14
** (SyntaxError) iex:5:1: syntax error before: '.'
iex(5)> 0.14
0.14
```

## express high digit number (64-bit double precision)
```
iex(6)> 1.0e-10
1.0e-10
```

## Booleans
```
iex(7)> true
true
iex(8)> false
false
```

## atom type
```
iex(9)> :foo
:foo
iex(10)> :foo == :bar
false
iex(11)> is_atom(true)
true
```

## inner keyword
```
iex(12)> :crypto.strong_rand_bytes 3
<<212, 140, 239>>
```

## string
```
iex(13)> "Hello"
"Hello"
iex(14)> "dziękuję"
"dziękuję"
iex(15)> "foo
...(15)> bar"
"foo\nbar"
iex(16)> "foo\nbar"
"foo\nbar"
```

## operator
```
iex(17)> 2+2
4
iex(18)> 2-1
1
iex(19)> 2*5
10
iex(20)> 10/5
2.0
```

## operator function
```
iex(21)> div(10, 5)
2
iex(22)> rem(10, 3)
1
```

## boolean operator
```
iex(23)> -20 || true
-20
iex(24)> false || 42
42
iex(25)> 42 && true
true
iex(26)> false && nil
false
iex(27)> 42 && nil
nil
iex(28)> !42
false
iex(29)> !false
true
iex(30)> true and 42
42
iex(31)> false or true
true
iex(32)> not false
true
```

##
```
iex(33)> 42 and true
```
> ** (BadBooleanError) expected a boolean on left-side of "and", got: 42

##
```
iex(33)> not 42
```
> ** (ArgumentError) argument error
>     :erlang.not(42)

## compare
```
iex(33)> 1 > 2
false
iex(34)> 1 != 2
true
iex(35)> 2 == 2
true
iex(36)> 2 <= 3
true
iex(37)> 2 == 2.0
true
iex(38)> 2 === 2.0
false
```

## compare other types
```
iex(39)> :hello > 999
true
iex(40)> {:hello, :world} > [1, 2, 3]
false
```

## string interpolation
```
iex(41)> name = "Sean"
"Sean"
iex(42)> "Hello #{name}"
"Hello Sean"
```

## String Concatenation
```
iex(43)> name = "Sean"
"Sean"
iex(44)> "Hello " <> name
"Hello Sean"
```

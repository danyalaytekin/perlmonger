# perlmonger

I am learning Perl again.

## Notes

Everyone seems to be on Perl 5 still. So I'll ignore Perl 6 for now.

## Basics

### Comments

```perl
# Like bash
```

### Conditionals

```perl
if(something) {
}
elsif {
}
```

### qw

Quote word. Splits strings using spaces. A string cannot contain a space. It [isn't a function](https://perlmaven.com/qw-quote-word).

```perl
my @something = qw(first second third)
```

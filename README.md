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

### `1;`

A Perl module must return a Boolean, or something that evaluates to one. Like `1`.

### =head1, =cut, ...

These are part of [Pod](https://perldoc.perl.org/perlpod.html), Perl's native documentation system.

### `my`

The `my` keyword will scope the declaration of a variable to its containing file, block, or subroutine.

```perl
my $something = 2;
sub f
{
    my $something = 3;
    print $something;  # 3
}
print $something;      # 2
```

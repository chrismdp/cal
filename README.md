# Cal

Cal is a super fast and powerful calendar interaction tool for the command
line.  It is designed to provide blisteringly fast and comprehensible calendar
output on the terminal. It supports any Calendaring service that supports iCal
and the CalDAV standards.

## Examples

``` bash
$ cal
Today    | 8     9    10    11    12    13    14 .. 18    19    20
Personal | | Gym |     | Seeing Marcie        |
         |                | Tennis |
Work     |       |
         |       ^ Call with Dave
```

``` bash
$ cal show Personal
Today    | 8     9    10    11    12    13    14 .. 18    19    20
Personal | | Gym |     | Seeing Marcie        |
         |                | Tennis |
```

``` bash
$ cal show next wed
Wed 20/4 | 8     9    10    11    12    13 .. 16    17    18    19     20
Personal |             | Lunch with Tim |            |     |
         |                                           ^ US conference call
```

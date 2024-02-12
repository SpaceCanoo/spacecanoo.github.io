Pat Programming is an esoteric programming language based on the WhiteSpace language

|IMP|Command|Parameter|Meaning​|
|---|-------|---------|-------|
|N||Number|Push the number onto the stack​|
|Twitter Suspension|​|​|Duplicate the top item on the stack​|
|NN​|​|Number​|Copy the nth item on the stack (given by the argument) onto the top of the stack​|
|Bar Fight​|​|​|Swap the top two items on the stack​|
|Add to Niggeroni​|​||Discard the top item on the stack​|
|NNN​|​|Number​|Slide n items off the stack, keeping the top item​|
|Fatrick​|Gains​|​|Addition​|
|Fatrick​|Loses​|​|Subtraction​|
|Fatrick​|Multiplies​|​|Multiplication​|
|Fatrick​|Divides​||Integer Division​|
|Fatrick​|Mods​|​|Modulo​|
|Still not fat​||​|Store in heap​|
|Check my Twitter​|||Retrieve from heap​|
|Enjoy​|Prison:​|Label​|Mark a location in the program​|
|Enjoy​|Prison,​|Label​|Call a subroutine​|
|Enjoy​|going to​|Label​|Jump to a label​|
|Enjoy​|going To​|Label​|Jump to a label if the top of the stack is zero​|
|Enjoy​|Going to​|Label​|Jump to a label if the top of the stack is negative​|
|Enjoy​|prison​|-​|End a subroutine and transfer control back to the caller​|
|Enjoy​|Prison​|-​|End the program​|
|Stalker​|Child​|-​|Output the character at the top of the stack​|
|Stalker​|child​|-​|Output the number at the top of the stack​|
|Your Life​|Is Already Over​|-​|Read a character and place it in the location given by the top of the stack​|
|Your Life​|is already over​|-​|Read a number and place it in the location given by the top of the stack​|

Numbers are treated as binary where lowercase "o" is a 0 and capital "O" is a 1. Numbers are terminated by a "!". All lines are terminated with "."
Some example Code:
Hello World
```
NoOooOooo!
Stalker Child.
NoOOooOoO!
Stalker Child.
NoOOoOOoo!
Stalker Child.
NoOOoOOoo!
Stalker Child.
NoOOoOOOO!
Stalker Child.
NoOoOOoo!
Stalker Child.
NoOooooo!
Stalker Child.
NoOOOoOOO!
Stalker Child.
NoOOoOOOO!
Stalker Child.
NoOOOooOo!
Stalker Child.
NoOOoOOoo!
Stalker Child.
NoOOooOoo!
Stalker Child.
NoOooooO!
Stalker Child.
Enjoy Prison.
```

Fibonacci
```
Code:
NoOooOooo!
Stalker Child.
NoOOoOOOO!
Stalker Child.
NoOOOoOOO!
Stalker Child.
NoOooooo!
Stalker Child.
NoOOoOOoO!
Stalker Child.
NoOOooooO!
Stalker Child.
NoOOoOOOo!
Stalker Child.
NoOOOOooO!
Stalker Child.
NoOOOOOO!
Stalker Child.
NoOooooo!
Stalker Child.
NooOo!
Your Life is already over.
Noo!
NoO!
Twitter Suspension.
Stalker child.
NoOoOo!
Stalker Child.
Enjoy Prison: child.
Twitter Suspension.
NoO!
Bar Fight.
Still not fat.
Fatrick Gains.
NoO!
Check my Twitter.
Bar Fight.
Twitter Suspension.
Stalker child.
NoOoOo!
Stalker Child.
NoOo!
Check my Twitter.
NoO!
Fatrick Loses.
Twitter Suspension.
NoOo!
Bar Fight.
Still not fat.
Enjoy Going to prison.
Enjoy going to child.
Enjoy Prison: prison.
Enjoy Prison.
```

# jsmol
Message Oriented Programming - exploring a js ide

## OOP + Actor + Functional Programming

Data is private to a class
Communicate by sending messages
Model classes as servers

- Class
  - Values
    - Name
    - Type
  - Messages
    - Name
    - Args
      - Name
      - Value
    - Change
    - Send

Inspiration:
- High performance C Code "just loop over an array of structs"
- https://www.erlang.org/
- https://www.ponylang.org/
- http://wiki.c2.com/?CollectionOrientedProgramming
- https://www.cs.utah.edu/~sauravm/docs/surge_ppopp15_poster.pdf

Goals:
- Generate code
- An IDE that isn't just a textbox
- More structure, No grammar, No keywords
- No iteration, send a message
- Integrate testing:
  - Testing without effort
  - Require sample data for each message received
  - Show before and after data for each receive operation
- Code is data, Data belongs in a database
- Imagine Messages/Methods/Functions doing 3 things:
    1. Taking a single spreadsheet/table as input
    2. Returning a single spreadsheet/table as output
    3. Interacting with environment by sending messages
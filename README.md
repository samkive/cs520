# GoLite Compiler

Justin Domingue – 260588454
Daniel Pham – 260526252
Seguei Nevarko – 260583807

Reference: https://golang.org/ref/spec

Code viewed:
  - ANSI C grammar, Lex specification: http://www.lysator.liu.se/c/ANSI-C-grammar-l.html
  - ANSI C grammar, Yacc grammar: http://www.lysator.liu.se/c/ANSI-C-grammar-y.html
  - Go 1.2, Yacc grammar: https://github.com/golang/go/blob/402d3590b54e4a0df9fb51ed14b2999e85ce0b76/src/cmd/gc/go.y
  - Go 1.6, Test cases: https://github.com/golang/go/tree/master/test

## Development
#### Compile
```
// In root directory
./run
```
or

```
cd src/
make
```

#### Testing
Run the parser on all files in programs/
```
cd src
make test
```

### Usage
```
// Run parser
./golite parse file

// Run pretty printer
./golite pretty file
```

## For Vince
Everything can be done from the top directory

Compile with:
```
./run
```

Pretty print a file with
```
./run file.go
```

Errors will be emmitted to stderr

Output file will be stored in outputs/ under the name file.pretty.go

## Submited Files

programs/valids/sorting.go
programs/valids/calc.go
programs/valids/set2square.go


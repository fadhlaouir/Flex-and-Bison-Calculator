## Raed Fadhlaoui IRM 2-2

# Bison-Flex-Calculator

CS Assignment - scientific calculator using Bison &amp; Flex, with additonal functionality implemented in C

## Functionality

- Basic arithmetic following BODMAS rules e.g, 4 \* (3 + 2) = 20
- Standard functions (modulo, ceil, abs, floor)
- Logarithmic functions (log2, log10)
- Trig functions (cos, sin, tan)
- Hyperbolic functions (cosh, sinh, tanh)
- Conversions (currency, temperature, distance)
- Variable stores (create and use your own variables. See example)
- Can read input the command line or a file

## Compile and execute

1. bison -d gram.y
2. flex lex.l
3. gcc gram.tab.c lex.yy.c -lm -o scientific-calc
4. scientific-calc

Repository moved to [code.randogoth.com/randogoth/sigilizer.git](https://code.randogoth.com/randogoth/sigilizer.git)

# Planetary Sigilizer

Converts any string into a sigil based on corresponding [planetary magic squares](https://en.wikipedia.org/wiki/Magic_square#Europe_after_15th_century).

```
sigilize.py <string to be sigilized> <planet name> <filename>
```

## Install Dependencies

```
pip install drawSvg
```

## Example:

```
sigilize.py "Hello World" mercury helloworld.svg
```

## Result:

![Result](helloworld.svg)
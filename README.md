# fourmi-1.1.0
The ultimate python package for text formatting. You can use up to 554 colors in this package.

# Installation
You can use this command in your command prompt to download `fourmi-1.1.0`.
`pip install fourmi`

Or you can update it.
`pip install --upgrade fourmi`

Or pin your installation to a specific version.
`pip install fourmi==1.1.0`

# How to use.
You can simply use fourmi by first importing it, then calling the `fourmi.send()` function. Here's a quick example.
```
import fourmi


fourmi.send('Hello!') # Prints 'Hello!'
```

You can add colors to it by the `color` parameter.
```
import fourmi


fourmi.send('Hello!', color='red1') # Prints 'Hello!' in the color 'red1'
```

Add background colors through the `bg_color` parameter.
```
import fourmi


fourmi.send('Hello!', color='red1', bg_color='teal') # Prints 'Hello!' in 'red1' with 'teal' as background color.
```

You can add `bold`, `italics`, `underline`, or `invert` by making them `True`
```
import fourmi


fourmi.send('Hello!', color='red1', bg_color='teal', bold=True, italics=True, underline=True, invert=True) # Prints 'Hello!' in 'red1' with 'teal' as background color with bold, italics, underline, and invert.
```

# All colors.
The colors are going to be in `COLORS.md` file so check that out too.




 

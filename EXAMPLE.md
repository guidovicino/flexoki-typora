# Flexoki Light Theme - Example Document

This is an example document to showcase the **Flexoki Light** theme for Typora. It demonstrates all the major Markdown elements with the warm, inky aesthetic inspired by analog paper.

## Typography and Text Formatting

Regular paragraph text looks clean and readable with the Inter font family. The warm paper-like background (`#FFFCF0`) provides excellent contrast with the deep black text (`#100F0F`).

You can use *italic text* for emphasis, **bold text** for strong emphasis, and ***bold italic*** for maximum impact. You can also use ~~strikethrough~~ text when needed.

### Links and References

Here are some useful links:
- [Flexoki Official Website](https://stephango.com/flexoki) - The original color palette
- [Typora Official Site](https://typora.io/) - The Markdown editor
- [GitHub Repository](https://github.com/) - For version control

## Lists

### Unordered Lists

Shopping list example:
- Fresh vegetables
  - Tomatoes
  - Lettuce
  - Carrots
- Fruits
  - Apples
  - Bananas
  - Oranges
- Dairy products
  - Milk
  - Cheese
  - Yogurt

### Ordered Lists

Steps to install the theme:
1. Download `flexoki-light.css`
2. Open Typora preferences
3. Navigate to themes folder
4. Copy the CSS file
5. Restart Typora
6. Select Flexoki Light from themes menu

### Task Lists

Project checklist:
- [x] Design color palette
- [x] Create CSS file
- [x] Test typography
- [ ] Add screenshots
- [ ] Create dark mode variant
- [ ] Submit to theme gallery

## Blockquotes

> "The difference between something good and something great is attention to detail."
> 
> — Charles R. Swindoll

Nested quotes work too:

> This is a top-level quote.
> 
> > This is a nested quote inside another quote.
> > 
> > > And this is even more nested!

## Code Examples

### Inline Code

Use `console.log()` to print output in JavaScript, or `print()` in Python. File paths like `/home/user/documents` also look good in inline code.

### Code Blocks

Python example:
```python
def fibonacci(n):
    """Generate Fibonacci sequence up to n terms."""
    a, b = 0, 1
    result = []
    
    for _ in range(n):
        result.append(a)
        a, b = b, a + b
    
    return result

# Generate first 10 Fibonacci numbers
numbers = fibonacci(10)
print(f"Fibonacci sequence: {numbers}")
```

JavaScript example:
```javascript
// Async function to fetch data
async function fetchUserData(userId) {
  try {
    const response = await fetch(`/api/users/${userId}`);
    const data = await response.json();
    
    return {
      id: data.id,
      name: data.name,
      email: data.email
    };
  } catch (error) {
    console.error('Failed to fetch user:', error);
    return null;
  }
}

// Usage
const user = await fetchUserData(123);
```

CSS example (how meta!):
```css
:root {
  --primary-color: #205EA6;
  --background: #FFFCF0;
  --text-color: #100F0F;
}

.container {
  max-width: 860px;
  margin: 0 auto;
  padding: 2rem;
  font-family: "Inter", sans-serif;
  color: var(--text-color);
  background-color: var(--background);
}
```

Bash script:
```bash
#!/bin/bash

# Install fonts on Linux
install_fonts() {
  local font_dir="$HOME/.local/share/fonts"
  
  echo "Creating fonts directory..."
  mkdir -p "$font_dir"
  
  echo "Installing Inter font..."
  wget -O inter.zip "https://github.com/rsms/inter/releases/latest/download/Inter.zip"
  unzip inter.zip -d "$font_dir/inter"
  
  echo "Rebuilding font cache..."
  fc-cache -f -v
  
  echo "Fonts installed successfully!"
}

install_fonts
```

## Tables

### Simple Table

| Language   | Extension | Paradigm          |
| ---------- | --------- | ----------------- |
| Python     | .py       | Multi-paradigm    |
| JavaScript | .js       | Multi-paradigm    |
| Rust       | .rs       | Systems           |
| Go         | .go       | Concurrent        |
| TypeScript | .ts       | Static typing     |

### Aligned Table

| Feature          | Flexoki Light | Nord | Solarized |
| :--------------- | :-----------: | :--: | --------: |
| Warm tones       | ✓             | ✗    | ~         |
| High contrast    | ✓             | ✓    | ✗         |
| Analog inspired  | ✓             | ✗    | ✗         |
| Light & Dark     | ✓             | ✓    | ✓         |

## Horizontal Rules

Content above the line.

---

Content below the line.

## Images

![Flexoki Color Palette](https://stephango.com/assets/flexoki/swatches.png)

*The Flexoki color palette swatches*

## Math Equations

Inline math: The formula for the area of a circle is $A = \pi r^2$.

Block math:

$$
\int_{a}^{b} f(x) \, dx = F(b) - F(a)
$$

The quadratic formula:

$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

## Footnotes

Here's a sentence with a footnote.[^1]

And here's another one with a longer footnote.[^2]

[^1]: This is a simple footnote.
[^2]: This is a longer footnote with more detailed information. It can span multiple lines and contain various formatting options.

## Special Elements

### Highlights

You can ==highlight important text== using double equal signs.

### Subscript and Superscript

- Water molecule: H~2~O
- Einstein's famous equation: E=mc^2^
- Chemical formula: C~6~H~12~O~6~

## Headings Hierarchy

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Color Palette Reference

The Flexoki Light palette uses these primary colors:

- **Paper**: `#FFFCF0` - Main background
- **Black**: `#100F0F` - Main text and headings
- **Cyan**: `#24837B` - Links, UI accents, interactive elements
- **Green**: `#66800B` - Success, keywords
- **Blue**: `#205EA6` - Variables in code
- **Orange**: `#BC5215` - Functions, warnings
- **Purple**: `#5E409D` - Numbers
- **Yellow**: `#AD8301` - Constants
- **Red**: `#AF3029` - Errors
- **Magenta**: `#A02F6F` - Special elements

## Conclusion

This theme brings the warmth and elegance of **Flexoki** to your Markdown writing experience. The carefully chosen colors provide excellent readability while maintaining a distinctive, paper-like aesthetic.

Happy writing! ✨

---

**Theme**: Flexoki Light for Typora  
**Version**: 1.0.0  
**Author**: Your Name  
**Based on**: [Flexoki](https://stephango.com/flexoki) by Steph Ango  
**License**: MIT

**Before you start:** rename this file to `html12a_Colors_lastname.md`, using your own last name. Watch videos 1–3 and use **Part 1** of `html12_ColorsSeoProtocols_StudyGuide.md` (in this folder) to answer. Put the file in an `html12` folder in your `htmlCssJavaScript` repo. Commit and push when you're done.

**Name:** Cody M

---

# Task 12a — Web Colors (RGB and Hex)

Type your answers on the blank line under each **Answer:**. Don't just copy the study guide. Explain in your own words where a question asks why.

## 1. How screens make color

**a.** A screen turns its red and blue lights all the way up and leaves green off. What color do you see? Why is mixing light called **additive** color?

**Answer:** Purple. It's additive because you're combining different light colors together (key word "*combining*").


**b.** A classmate says, "Hex has fewer colors than RGB because hex codes use fewer digits." Are they right? Explain using the number of choices for each color.

**Answer:** No. Hex is just a different way from RGB to format color choices. They both have 16.7 million possible colors.


## 2. Reading hex codes

**c.** Name the color for each hex code. For the last two, say whether it is a light or dark gray and how you can tell.

| Hex | Color |
|---|---|
| `#FF00FF` | Purple |
| `#00FFFF` | Cyan |
| `#FFFF00` | Yellow |
| `#CCCCCC` | Light Grey |
| `#1A1A1A` | Dark Grey |

**d.** In `#3C9F12`, which pair is the strongest? What color family will this be?

**Answer:** The "9F" is the strongest, meaning this color will be mostly green.


**e.** The CSS color name `lime` and the CSS color name `green` are not the same color. Give the hex code for each.

**Answer:** Lime is #00FF00, while green is #008000


## 3. Converting between hex and RGB

**f.** Write each color the other way.

| Given | Write it as |
|---|---|
| `rgb(255, 255, 0)` | hex: #FFFF00 |
| `#0000FF` | rgb: rgb(0, 0, 255) |
| `rgb(0, 0, 0)` | hex: #000000 |
| `#FFFFFF` | rgb: rgb(255, 255, 255) |

**g.** Convert the hex pair `C0` to a normal number. Show your work using the rule in section 1.4 (first digit × 16, plus the second digit). Remember C = 12.

**Answer:** (12 * 16) + (0 * 1) = 192


**h.** `#F80` is short hex. Write it out as a full 6-digit hex code.

**Answer:** #FF8800


## 4. Colors in CSS

**i.** Write CSS that does both of these. Use **hex** for one and **rgb** for the other.
- Makes `h1` text red
- Makes the page (`body`) background white

```css
h1 {
    color: rgb(255, 0, 0);
}

body {
    background: #FFFFFF;
}
```

**j.** Write a CSS rule for a class called `.overlay` that makes its background **black and half see-through**. Which number controls the see-through part?

```css
.overlay {
    background: rgba(0, 0, 0, 0.5)
}
```

**Answer:** The last number controls the alpha, ranging from 0.0 to 1.0


**k.** Why is yellow text (`#FFFF00`) on a white background (`#FFFFFF`) a bad choice? What would you change?

**Answer:** In web design, there's a concept known as "contrast ratio", or the ratio of the text color to the background color. A good contrast ratio means the text can be read very easily, such as 15:1 (not the actual value) with black and white. Yellow text on a white background means reading bright colored text on a bright background, which means a low contrast ratio and low readability.


## 5. Your own site

**l.** Open the `styles.css` for your DIY website. Pick one color you used (or choose a new one you like). Write it as a hex code, then explain what the red, green, and blue pairs tell you about the color.

**Answer:** The color I used was `rgb(243, 49, 49)`. I wanted a bright, vibrant red color, but having it only be red was too jarring. So I used a little bit of green and blue to make it brighter but still have a.. good feeling. It's hard to describe.


## Closing 12a — Vocabulary

| Term | Your definition |
|---|---|
| RGB | Red Green Blue, the three colors used to display a full color. |
| Hex code | A 6-digit hexadecimal version of RGB. |
| Hexadecimal | A base16 counting system, using digits 0-9 and letters a-f. |
| Additive color | Mixing colors together to create new colors. |
| rgba | RGB but with varying opacity. |
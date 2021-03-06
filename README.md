# Design Rules

## Typography
1. Use font size between 15 and 25 pixels in body text
2. Use (really) big font sizes for headlines (ex: 90px, 60px or 32px)
3. Use line spacing between 120 and 150%
4. 45 to 90 characters per line
5. Use good fonts (sans-serif, Open Sans, Lato, Raleway, Monsterrat, PT Sans, Cardo, Merriweather, PT Serif )

## Colors
1. Use only one base color. 
You can choose color in https://flatuicolors.com/
2. Use tool if you want to use more colors (like a button )
3. Use color to draw attention
4. Never use black in your design
5. Choose colors wisely

### Color Meaning
* **Red** is a great color to use when power, passion, strength and excitement want to be transmitted. Brighter tones are more energetic and darker shades are more powerful and elegant.
* **Orange** draws attention without being as overpowering as red. It means cheerfulness and creativity. Orange can be associated with friendliness, confidence, and courage.
* **Yellow** is energetic and gives the feeling of happiness and liveliness. Also, it associates with curiosity, intelligence, brightness, etc.
* **Green** is the color of harmony, nature, life and health. Also, it is often associated with money. In design, green can have a balancing and harmonizing effect.
* **Blue** means patience, peace, trustworthiness, and stability. It is one of the most beloved colors, especially by men. It is associated with professionalism, trust and honor. That's actually why the biggest social networks use blue.
* **Purple** is traditionally associated with power, nobility and wealth. In your design, purple can give a sense of wisdom, royalty, nobility, luxury, and mystery.
* **Pink** expresses romance, passivity, care, peace, affection, etc.
* **Brown** is the color of relaxation and confidence. Brown means earthiness, nature, durability, comfort, and reliability.

## Images
1. Put text directly on the image
2. Overlay the image with the color (darker, color gradient, opacity)
3. Put your text in a box. Box shoud be opaque.
4. Blur the image
5. The floor fade

### **Overlay the image**
```csss
.darken {
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(YOUR IMAGE HERE);
}
```
### **Put text in a box** 
```
.text-box {
  background-color: rgba(0, 0, 0, 0.5);
  color: #fff;
  display: inline;
  padding: 10px;
}
```

### **Floor fade**
```
.floor-fade {
 background: linear-gradient(to bottom, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.6) ), url(YOUR IMAGE HERE);
}
```
## Icons
1. Use icons to list features / steps
2. Use icons for actions and links
( Icons should be recognizable and label your icons)
3. Icons should not take a center stage
4. Use icon fonts whenever possible

## Spacing and Layout
1. Use whitespace
- Put whitespace between your elements
- Put whitespace between your groups of elements
- Put whitespace between your website's section
- But don't exaggerate
2. Define hierarchy. Whitespace describes invisible relationships between the elements of your website

- Define where you want your audience to look first
- Establish a flow that corresponds to your content's message
- Use whitespace to build that flow

# Inspirations
1. Collect design that you like
2. Try to understand everything about them
3. Why do they good look ?
4. What do these sites have in common ?
5. How were they built in HTML and CSS ?

# Improve your website's conversion
1. Build trust with your future customer
2. Repeat your primary action
3. Grab your user's attention
4. Tell your user the benefit
5. Don't ask for too much information
6. Use social proof
7. Use urgency
8. Use scarcity
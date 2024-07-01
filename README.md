# Starting from scratch

- Start with a feature, not a layout. An application consists of several features. Before we start designing where each of these features will go, we need to design the features themselves.
- At first, don't get obsessed with the details; focus on something functional. Later, you can take care of details like fonts, shadows, icons, etc...
- Start creating a design in grayscale. Once you have finished, you can introduce colors. This way, you force yourself to use spacing, contrasts, and good sizes to make the design look good.
- Don't design too much, you don't need to design every single feature before you move on to implementation.
- Work in cycles, Basically, every time you design a feature, implement it in the code to see how it behaves.
- Be aware of the difficulty of development; don't design something that you won't be able to develop later.
- Choose a personality. For example, a bank needs to convey seriousness, security, and professionalism.
- Typography plays a huge part in determining how a design feels.
- Choose colors based on what you want your application to convey.
- Border radius makes it feel more playful and friendly.
- Texts play an important role in the application's personality.
- Limit your choices, Measurements, colors, fonts, shadows... will make decision-making easier.
- You'll want systems for things like: Font size, font weight, line height, color, margin, padding, width, height, box shadows, border radius, border width, opacity...

# Hierarchy is Everything

- When everything in an interface is competing for attention, it feels noisy and chaotic.
- Size is not everything; to establish a hierarchy, you should also rely on font weight and color.
- Dark color for primary content, grey for secondary content, and lighter grey for tertiary content.
- Don't use grey text on colored backgrounds, instead of this, choose a color with the same hue, and adjust the saturation and lightness until it looks right to you.
- Emphasize the element you want to draw attention de-emphasizing the other elements.
- You can also combine labels and values into a text to make it easier to read e.g. "12 left in stock" instead of "In Stock: 12"
- Sometimes the labels are secondary. When this is the case, de-emphasize the labels and emphasize the data.
- If you are designing an interface where you know the user will be looking for the label, you have to emphasize the label.
- Don't let semantics dictate your design. h1 doesn't mean it should be big. Sometimes you can just hide it visually and still have it in the DOM because the content speaks for itself.

When you have multiple actions:

- Primary actions should be obvious. Solid, high contrast background colors work great here.
- Secondary actions should be clear but not prominent. Outline styles or lower contrast background colors are great options.
- Tertiary actions should be discoverable but unobtrusive. Styling these actions like links is usually the best approach.

# Layout and Spacing

- For a cleaner design, leave more space between elements.
- Start giving something way too much space, then remove it until you're happy with the result.
- Have a system in place for fonts and spacing. 16px is a good start. 4, 8, 12, 16, 24, 32, 48, 64, 96, 128 etc.
- If you only need 600px of screen, then just use 600px. Keep it clean.
- Start by designing for mobile. Then bring it over to desktop and adjust.
- If you want to make better use of the available space, you could break the supporting text out into a separate column.
- Not all elements have to be scalable. For example, in an interface with a navbar and main content, the navbar doesn't have to scale on all screen sizes; it can have a maximum width, allowing the main content to scale more.
- Not everything should be relative sized e.g. text and it's headline, using em unit for the headline. Don't be dogmatic about it and don't do this.
- Border can make it clear how elements are grouped together. If not, you can use spacing, e.g. label and input closer together as a group. This applies to vertical and horizontal spacing.

# Designing Text

- Don't use too many font sizes. Use a scale and have a system in place. This leads to consistency and design is easier.
- Stick to px or rem units, it's the only way to guarantee you're actually sticking to the system.
- Choose a font is hard, Helvetica it's a good start point.
- As general rule, ignore typefaces with less than five weights.
- Avoid use condensed typefaces with short x-heights for your main UI text.
- Inspect some of your favorite sites and see what typefaces they are using.
- For the best reading experiencie, make your paragraphs wide enough to fit between 45 and 75 characters per line. A width of 20-35em will get you in the right ballpark.
- Your line-height and paragraph width should be proportional.
- Line-height and font size are iversely proportional.
- Not every link needs a color, you can just use a heavier font weight or darker color instead a blue color.
- Don't center long form text.
- You should trust the typeface designer and leave letter-spacing alone.
- 

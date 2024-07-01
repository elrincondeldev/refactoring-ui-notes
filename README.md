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

# Working with color

- HSL is the best color format. It's easy to adjust colors and it's easy to understand. Representing colors: hue, saturation, lightness.
- You can't build anything with five hex codes, you need a much more comprehensive set of colors to choose from.
- Greys, for the text, backgrounds, panels and form controls.
- Primary colors, for primary actions, active navigations elements, etc...
- Accent colors, for communicate different things to the user.
- Define a fixed set of shades up front that you can choose from as you work.
- The darkest shade of a color is usually reserved for text, while the lightest shade might be used to tint the background of an element.
- If you want to change how light colors look, adjust the lightness. If you want to change how colorful it is, adjust the saturation.
- To make a color lighter, rotate the hue towards the nearest bright hue
- To make a color darker, rotate the hue towards the nearest dark hue
- Don’t rotate the hue more than 20-30° or it will look like a totally different color instead of just lighter or darker.
- Saturating greys: Feel cool, saturate them with blue. Warm, saturate them with some yellow or orange.
- Flipping the contrast, use dark colored text on a light colored background.
- You don’t want the primary text and the secondary text to look the same, one way to increase the contrast without getting closer to white is to rotate the hue towards a brighter color, like cyan, magenta, or yellow.
- Always use color to support something that your design is already saying; never use it as the only means of communication.

# Creating Depth

- Light comes from above. To make something feel like its lifted, add a shadow on the bottom.
- To make something feel like it's pressed, add a shadow on the top. You can use inset box shadow here, and another grey shadow at the bottom.
- You might use a smaller shadow for something like a button, where you want the user to notice it.
- Medium shadows are useful for things like dropdowns,
- Large shadows are great for modal dialogs, where you really want to capture the user’s attention.
- Combining shadows make them look more natural.
- Make an element lighter than the background color to make it feel like it’s raised off of the page, or darker than the background color if you want it to feel inset.

# Working with images

- Bad photos will ruin a design, even if everything else about it looks great.
- One way to increase the overall text contrast is to add a semi-transparent overlay to the background image.
- Icons that were drawn at 16–24px are never going to look very professional when you blow them up to 3x or 4x their intended size. If small icons are all you’ve got, try enclosing them inside another shape and giving the shape a background color.
- Don't scale down screenshots, if you want to include a detailed screenshot in your design, take the screenshot at a smaller screen size (like maybe your tablet layout).
- If you really need to fit a whole-app screenshot in a tight space, try drawing a simplified version of the UI with details removed.

# Finishing Touches

- Supercharge the defaults: bulletpoints, checkboxes, radio buttons, etc.
- Add color with accent borders.
- One way to add some excitement to a background is to simply change the color.
- Decorate your backgrounds with gradients, patterns, etc.
- If you’re designing something that depends on user-generated content, the empty state should be a priority, not an afterthought.
- There’s no point in presenting a bunch of actions that don’t do anything until the user has created some content.

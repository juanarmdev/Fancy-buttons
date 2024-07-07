# Fancy-buttons
CSS only animated buttons.

All buttons have and MUST HAVE the ".custom-btn" class. They will also have another specific class of their own that you can use to address that particular button and change its styles.

Remember to change the "Submit" text inside the span, the title and the aria-label placeholders of the button itself to suit your needs.

The width and height of the buttons are given by their padding, feel free to adjust it to suit your needs or to give them an explicit width and height if that's better for you. Texts are all uppercase because of the "text-transform: uppercase" property in the ".custom-btn" class. You may remove the class from the button and/or remove the "text-transform: uppercase" in the ".custom-btn" class. I recommend removing both if you don't want the text inside the button to be uppercase.

Colors except the text inside the buttons are variables, I strongly recommend adding your own and keep the same logic. If you want to change the color of the text inside every button, just change it inside ".custom-btn{ span{ color: your-color } }". If you need to change colors for each button, just add a span inside their specific class, like ".custom-btn.ttb{ span{ color: your-color } }. Remember to remove the already declared button colors variables if you're not using them.

The CSS file imports the fonts, I don't recommend using it like that in your website due to performance potential issues. There are other two classes, ".custom-btn--sans-serif" and ".custom-btn--serif" which control which font each button will use. If you don't any need of them, just remove them from the button. If you are using any other Google or custom font, you can declare the font-family in the ".custom-btn" class and it will apply to all of them.

Feel free to use any of this buttons whenever and wherever you like 🤗
A ⭐ would be really appreciated!

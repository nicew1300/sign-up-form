# sign-up-form
Sign-up Form Project from The Odin Project

It was kinda fun, but for the most of the time it was just figuring out
how to use the new CSS properties, units, pseudo-classses and elements. 
I also found out how good i became at styling, even with only this basic knowledge
of CSS. Hardest part was figuring out how to make like 2 columns of input fields,
But here is the math and all:
so basically i used flex-wrap: wrap; and width: 45%; to make them into 2 columns
so i have gap: 1.5rem, which means i have to set the width a bit under 50%
to leave a bit of room for the gap, where as if i had width 50% on the inputs,
there would be no room for the gap and everything would become broken 
(took me around 30 whole minutes to figure that out lol) so thats why the width is 45%
because 45% + 45% + gap, thats under 100% so thats cool, and then when flexbox
tries to put another box in, thats another +45%, which would be well above the 100% width,
so flexbox pushes the box in the next row :D
## Tips and Tricks for using Devtools
Talking points for a workshop on how to master Devtools for debugging your visual styles. (Not meant to be a comprehensive guide.) Reach out to (Jackie Ho)[http://ohho-design.com/] if you want to learn more!

### Basics / How to open DevTools
- Click into objects or view overall page
- Highlighting tool to find the element you want
- Docking / Settings

### Testing out styles
- Find the right element
- Find the file styles are coming from
- What's being applied versus what's not
  - strikethroughs
  - !importants
  - useful for when you have many stylesheets / are using a front-end framework
- Change existing properties (+ fun with colors)
- Add new styes
- Apply new classes (.cls)
- Differences between editing existing classes versus "element.style"
  - Personally I like to go for existing classes because I always like to think of elements as components, so I want to see if changing something will messes with other things
  - I’ll also search through my files to see where something is being used to double check
- "Styles" vs "Computed"
- Force state
  - hover, active, etc.
  - You can also use the :hov

### Messing with HTML
- Mess with the text, test lenghts
- Duplicate elements (rows in a table, multiple buttons, etc.)
- Delete elements
- Bonus: Steal images from websites (heh)

### Testing screen widths + throttle
- Device Mode
  - user agent string
  - viewport sizing
  - devicePixelRatio
  - text auto-sizing
  - mobile scroll bars
  - touch events (no hovers) and touch emulation
- Custom pixel ratio (interesting for testing out breakpoints / media queries)
- Jump to the media query
- Network throttling (which you can also test in the 'Network' tab to get the load time + the 'Performance' tab)
- Screencast chrome and devtools to your Android device (Read more)[https://developers.google.com/web/tools/chrome-devtools/remote-debugging/]
  - Use Safari for iOS

### Editing your files directly from Devtools
- For static webpages or some web apps (not React), you can drag your entire folder into the 'Source' tab and then edit the styles directly from devtools and it'll save automatically.
- To turn it off, go to 'Settings' and then 'Workspace' and remove it there.

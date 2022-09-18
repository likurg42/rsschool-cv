# Nikolay Tarasenkov

## My Contacts

- E-mail: likurg42@gmail.com
- Github: @likurg42
- Telegram @likurg42

## Summary

I really like web development and design. I found really interesting making websites and web apps, learning new technologies and new ways to implement adaptive and interactive designs in modern web. My goal is to learn frontend and ux/ui, while making my own projects.

## Skills

- HTML (PUG)
- CSS (Sass, BEM, RWD, Modern Layouts)
- JavaScript (Fundamentals,Functional Programming, OOP, Asynchronous JavaScript, ES6+,DOM),JSON
- Animations (Vanilla JS and CSS animations, GSAP, SVG animations)
- Accessibility (WAI-ARIA, media and mobile a11y)
- Version control: Git
- OS: Windows, Linux (Ubuntu, Manjaro)
- Design Tools: Figma, Photoshop
- Editors: Webstorm, VS Code, Vim (Basic)

## Code examples

### Javascript

```js
const bubbleSort = (coll) => {
  let stepsCount = coll.length - 1;
  let swapped;

  do {
    swapped = false;
    
    for (let i = 0; i < stepsCount; i += 1) {
      if (coll[i] > coll[i + 1]) {
        const temp = coll[i];
        coll[i] = coll[i + 1];
        coll[i + 1] = temp;
        swapped = true;
      }
    }

    stepsCount -= 1;
  } while (swapped); 

  return coll;
};

bubbleSort([3, 2, 10, -2, 0]); // => [ -2, 0, 2, 3, 10 ]
```

### SCSS

```css
.repeating-responsive-grid {
  display: grid;
  padding: 1rem;
  
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
}
```

## Experience

- **acme** website

## Education

- Moscow Aviation Institue (Business informatics)
- RS School (in progress)
- Hexlet (in progress)
- Introduction to Computer Science with Python MIT (Self-paced)
- Kevin Powell courses (CSS Demystified, RWD Bootcamp)
- Frontend Masters (CSS track, Javascript track)

# doldrums.css: Just Let Me Do CSS Already

If you're the type of person to say "Tailwind's nice and all but":
- I don't want to use an entire build system for my CSS
- I also don't want to be penalized for that
- I just want my nice constants and I'll be on my way
- I wish things were simpler

this is for you.

## What does doldrums.css actually do then?

doldrums.css defines three things.
- A default color scheme
- A default size set
- Bare minimum utility classes for using flexbox

That's it, and that's all we think a CSS framework should provide.

## How do I use it?

We love bullet lists here.

### Approaches to Installation

Approach A:
1. `npm install doldrumscss`
2. Import `doldrumscss/themes/tailwind.css` or whatever other theme.
3. Import `doldrumscss/css/doldrums.css`.

Approach B:
- Copy your desired theme from themes/ and the doldrums.css from css/.
- Use them as regular CSS files.

### Approaches to Use
- Eat raw.
- Layer on top of Bootstrap or your favorite CSS framework.
- Do whatever fits the project!

## Support

Doldrums.css uses CSS variables, which usually requires browsers from 2017
or later. If this is a dealbreaker a postprocessor can be used.

## Further Recommendations

Pair this with [checkbox.css](https://gitlab.com/bbworld1/checkbox.css) to style
checkboxes, those things are a pain to do on your own.

## Contact

Use:
- The Issues tab on this project
- [vwangsf@gmail.com](mailto:vwangsf@gmail.com) if that doesn't work

# Where Does e Come From? (sac-e-origins)

A discovery-based introduction to the number *e* for Math 172 (Precalculus) at Santa Ana College. Students start with compound interest on $1, find the ceiling that (1 + 1/n)^n approaches, and then use e in three real-world models.

**Live:** https://sac-e-origins.netlify.app

## What's inside

1. **The $1 bank**: yearly vs. semiannual compounding, then a locked prediction
2. **Compound more often**: n from 1 to 31.5 million, with a live table, chart, and a visual showing more periods but a smaller rate per period
3. **Meet e**: names the limit, derives e^(rt), and includes a growth/decay explorer for y = e^(kt)
4. **e in the world**: savings (A = Pe^(rt)), Newton's Law of Cooling, and medicine elimination (half-life), each gated by a prediction
5. **Check and reflect**: three retrieval questions and three reflection prompts

## Features

- Single-file HTML, vanilla JS, no build step
- Teacher/Student mode toggle (Teacher mode enlarges type and shows teacher notes)
- WCAG 2.1 AA: semantic structure, skip link, ARIA tabs, text descriptions for every chart, light and dark themes
- Mobile-responsive; embeddable in Canvas via iframe
- Reflections and mode are saved only in the student's browser (localStorage)

## Canvas embed

```html
<iframe src="https://sac-e-origins.netlify.app" title="Where Does e Come From? interactive exploration" width="100%" height="900" style="border:0;"></iframe>
```

## Version history

- **v1.0**: Initial release with compounding discovery, e intro, three real-world scenarios, and check and reflect

---
Math 172 Precalculus | Built for Santa Ana College | Dr. Martin Romero

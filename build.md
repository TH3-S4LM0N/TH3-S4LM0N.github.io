For all of the cool things [KosmosisDire/obsidian-webpage-export](https://github.com/KosmosisDire/obsidian-webpage-export) does, it also needs a lot of manual work.
# ToDo for Real Build
- It will put all assets 2 dirs above where they are and not find any.
- Manually remove all fold arrows in lists as they break formatting.

It will make
```html
<li data-line="3" dir="auto"><div class="list-collapse-indicator collapse-indicator collapse-icon"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon right-triangle"><path d="M3 8L12 17L21 8"></path></svg></div>DISPLAY TEXT/TAGS
```
which needs to become
```html
<li data-line="3" dir="auto"><!--<div class="list-collapse-indicator collapse-indicator collapse-icon"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon right-triangle"><path d="M3 8L12 17L21 8"></path></svg></div>-->DISPLAY TEXT/TAGS
```

- It searches for lowercase MathJax fonts but they are uppercase.
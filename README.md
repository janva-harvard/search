# Search (Project-0  CS50)
Web Programming with Python and JavaScript first assignment.
Aim is to get familiar with HTML and css technologies partially 
replicating google search pages (simple search, image search and
advanced search). 

## File structure

Three different pages was made, ` googleadvanced.html, googleimage.html, index.html`. Each pages is accompanied by a
stylesheet file located in the style folder, in production this would probably be single file. Google logo is located in img folder. This folder also contains an svg file, it's the camera icon used on image search page. Inlining the image made it simpler to effect its opacity and color through css. The README.md the file containing this documentation.    

```bash
.
├── googleadvanced.html
├── googleimage.html
├── index.html
├── README.md
├── img
│   ├── camera_alt-24px.svg
│   └── googlelogo_color_272x92dp.png
└── style
    ├── advanced.css
    ├── simple.css
    └── images.css
```
 
## About implementation

Much of the styling was taken from googles pages so as to get the same look and feel as on google as possible. The pages try to replicate the same behavior as googles own for instance how things line up, flows outside the view when decreasing size of browser window or in the case of advanced page how content
get hidden when reaching a certain break point. Some 
differences can be spotted  such as some missing icons and at which point things get hidden, this is due to lazyness on my part :-). live pages are available [here](https://janva-harvard.github.io/search/) (at github).




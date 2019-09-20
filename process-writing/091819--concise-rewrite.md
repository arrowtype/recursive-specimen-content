 # Recursive Process & Origins

 _Recursive is a variable font[1] family for code & interactive design. It takes its initial inspiration from single-stroke casual signpainting, but extends this style into a wide-ranging designspace[2] to deliver advanced typographic control & flexibility. Started as a thesis project at KABK TypeMedia in 2018, it was later commissioned for open-source release by Google Fonts. It has since been extensively expanded and refined for release in late 2019._

The Recursive project has been driven by three overarching goals:

1. Making something fun & useful for web design & development
2. Unocovering what a "single-stroke casual" for code & user interfaces (UI) could be
3. Contributing to variable font design workflows, technological support, and user adoption

With these goals in mind, here is the story of Recursive.

[1] A *variable font* is a font that combines a range of font styles into a single file, and this stylistic range can be controlled by the user of the font. By contrast, typical digital fonts (known as *static fonts*) have a single style per font file, and these are strictly separated from one another. Whereas a static font family might have a Regular, Medium, SemiBold, and Bold styles, a similar variable font family would have the styles, plus *anything in between.* This has many benefits, including increased typographic control and the potential for reduced overall file size on the web.

[2] The *design space* of a typeface is its total possible area of stylistic possibilities. In variable fonts, the design space is often represented as geometric shapes such as a rectangle or a cube, to visually plot the relationship of axes and show the available stylistic range.

<!-- ------------------------------------------------------------------------- -->
<!-- The problem ------------------------------------------------------------- -->
<!-- ------------------------------------------------------------------------- -->

## The origins of Recursive

Before shifting my focus to type design, I studied graphic design, then worked as a designer at IBM for 3 years. There, I worked first as a digital product designer, and later as a brand experience designer. My primary focus was on the visual design and user experience of web-based applications and marketing. Over my time in these roles, I shifted more and more towards using web code to prototype and implement design.

Working in these roles, I was particulary focused on typographic clarity and microinteractions[1]. I picked up on details in fonts that worked – or didn't – for interactive interfaces. Initially, I was designing UI with Helvetica Neue. Helvetica has some wonderful qualities, but I found a few primary problems:

1. The closed apertures (openings in letters like `a`, `e`, and `s`), overly-similar shaping (`I` vs `l`, `6` vs `8` vs `9`, and so on), and tight spacing of Helvetica make it a beautiful font for use in marketing or relatively large text, but my teams were creating UI that required small type and presented rich, complex data. Readability[2] and legibility[3] were never as optimal as I wanted them to be.

2. Our version of Helvetica lacked tabular figures (numbers that take up the same width, across font styles), which was especially problematic for the complex financial data in one of my main projects. At this time, many teams at IBM started using monospace fonts for such data, but there wasn't an obvious option for which monospace font should be used. Pairing fonts effectively can be difficult in general: there is the subjective challenge of finding complementary styles, plus the technical challenge of harmonizing layout when proportions and metrics vary from font to font.

3. Traditional digital fonts are frustratingly unuseful for interactivity. For me, this breaks down into three primary reasons:
   
   1. Static fonts exist as separate files for each font style, so adding multiple styles to a website tends to cause a debate over loading time, pitting typographic range against web performance. Because web performance is more-easily measured than typographic elegance, it tends to win this debate. Luckily, this can be addressed in part with variable fonts, and made far better still with smart font loading strategies ([here's one excellent guide on this subject](https://www.zachleat.com/web/comprehensive-webfonts/)).

   2. Static fonts can't smoothly transition from one style to another. Microinteractions often rely on smooth transitions, but for fonts, these tend to be limited to scale and position, as traditionally, font *style* was off-limits. Again, variable fonts offer the possibility to change this.

   3. Different styles of most fonts take up different amounts of space. That is, a word set in a Regular weight typically has a smaller width than the same word set in a Bold weight. To be fair, this normally isn't a typographic problem, and in many cases helps different styles to work in visual harmony with one another. However, it makes it impossible to elegantly use font style changes for most microinteractions. With most fonts – even variable fonts – changing a font style on user interaction would change its width. At best, this would look ugly and break the word shaping of text. At worst, it could shift or break a layout. Therefore, with most fonts, iteraction must be shown through color changes or visual changes in elements other than type.

Today, the first problem has been largely solved by Helvetica Now, which has specific styles for small text. The first *two* problems were solved at IBM by commissioning IBM Plex, a superfamily[4] of Sans, Mono, and Serif fonts. The technology of variable fonts offers to solve much of the third problem. However, solving the whole set of issues requires further design efforts.

[1] *Microinteractions* are subtle but important ways to communicate interactivity to a user. They are typically animated. When applied well, help to make an interface more intuitive and pleasant to use. A simple example of a microinteraction is a button that tranisitions from light to dark blue on hover, to indicate that it can be clicked.

[2] *Readability* is the overall ease with which a body of text can be read. This is affected by such things as the sizing, even spacing, and color contrast of text, as well as the appropriateness of the font used for a given size and medium. A font with thin stroke thickness or tight letterspacing might be readable and appealing at large sizes, but can easily make smaller text harder to read.

[3] *Legibility* is the ease with which different characters can be distinguished from one another. Highly-legibile characters are most important in contexts where ambiguity causes problems, such as passwords, code syntax, data display, and UI elements. It is less vital in running text, where readability is the higher priority.

<!-- ------------------------------------------------------------------------- -->
<!-- The design concept ------------------------------------------------------ -->
<!-- ------------------------------------------------------------------------- -->

## TypeMedia

On the side of working at IBM, I developed a personal practice of lettering, calligraphy, and type design. I found little ways to work these interests into projects at work, but mostly, it was just a fun way to spend my time and explore the broader world of design.

One of my main interests in lettering was starting ideas with handwritten brush lettering and taking these into carefully-drawn lettering. The process of simplifying the textural, organic writing into specific, black-and-white outlines is challenging but satisfying, and connected well to my long-term interest in logos and type design.

After years of dreaming about it, I finally made it into a masters program for type design, TypeMedia, at the Royal Academy of Arts in The Netherlands. I was one of twelve students from around the world who were lucky enough to study under some of the best type designers in Europe for 10 intensive months. 

The first semester of TypeMedia is a broad survey of approaches to type and letter design, covering topics including type revival, Python, stone carving, Arabic script, and the formal construction of different styles of type. In the second semester, each student created a single type design project to work on for 5 months, and pursued this under the frequent reviews and critique from our teachers.

Of course, choosing a thesis topic requires a lot of thought. My classmates and I were often told to embrace a project that would be weird and ambitious, forgetting notions of making something to immediately define and sell. We had 5 months to dedicate ourselves completely to a project, and that is a very rare opportunity. One alum told us, "now that variable fonts exist, I would approach the thesis completely differently." They left it up to us to imagine just *how* we should approach it differently, and that was the point. We weren't supposed to get answers from those before us; we were supposed to seek our own.

With these prompts, I sketched ideas for my thesis. A direction I kept coming back to was a single-stroke casual.

## An origin in painted letters

_Single-stroke casual_ is a genre of signpainting which is often the first style taught to beginner signpainters. Each signpainter has their own version of it, but it adheres to some typical attributes: 

- Letters are constructed from a limited set of simple-to-paint, gently-curved strokes. Each segment of a letter is painted as a single stroke rather than built up from multiple brush strokes (as is sometimes the case for other, more-complex signpainting styles).
- Letters usually written with a slant.
- Letters are usually uppercase.
- Letters often have a low-waisted construction, with crossbars placed below the optical middle. This deliberately casual design makes the style visually forgiving to write, because there is no formal basis for how letters "should" look.

These attributes work together to make a style that is simple to learn, visually forgiving, and efficient to paint. As a result, this is a style in widespread use, and tends to convey a sense of familiarity, humanity, and approacheability.

Drawing casual letters made me realize that I could squish and stretch them wildly, and they still held up their energy and sense of vitality. With a brush pen, I was free to easily explore many atypical styles: super-bold, ultra-condensed, ultra-wide extra-swashy, and more. I found that a single-stroke casual basis lent itself to a very flexible design space.

While sketching, I also found myself drawn towards monospaced letters.

I love coding for what it allows me to do as a designer. However, I have to admit: I also love the aesthetics of it. I love that a programmer's primary interface is type, with little else. On a micro lebel, I particularly like the way that monospaced type creates a tabular rhymtm by compressing some letters (narrow `w` and `m`, etc) and extending others (slab-serifed `i` and `l`, etc). So, of course, I also started sketching single-stroke casuals as fixed-width letters.

![](images/recursive-notebook_sketch-alphabets.jpg)
![](images/recursive-notebook_sketch-axis_a.jpg)
![](images/recursive-notebook_sketch-pseudo.jpg)

### My own take on single-stroke casual

While Recursive does take inspiration from many sources, I never sought to copy any one person or historical precent in its design. Rather, I seeking to find my own style of casual letters, and beyond that, I was also searching for a way to make a more readable, more widely-usable style of writing. To make my project appropriate for use in code & UI, I worked from several of my own design principles:

- Often, if casual caps are paired with a lowercase, the lowercase letters are written as a connected script. To make Recursive useful as a font for code and general text, I decided early on to make a lowercase that had a typical Roman[4] construction, rather than a connected script.
- Letters shouldn't simply be a traced facsimile of signpainted letters, but should be more "typographic" – still carrying warmth and livliness, but simplified in visual style in order to be elegantly usable in many situations, including in small text on screens.
- Whereas casual signpainting almost always has a forward slant, the core of my project had to be an upright style to maintain crisp rendering and easy recognizability in pixel-rendered text.

[4] *Roman* letters are the letters we are most used to seeing in Latin-script fonts and "print" style handwriting. Each letter is separate from the next, and each has what we tend to think of as its most-basic form. Helvetica and Times New Roman are just two examples of fonts with Roman upright styles.

## Finding the voice of Recursive

- Initial prototyping with IBM Plex Mono

- Keeping a standard width metric for elegant fallback fonts.

- Early digital drawings. Searching for something both expressive and simple/typographic. Tried to explore this by making something too wild, and something too rigid. Realized that having a spectrum was more interesting than finding just one thing in the middle. I recieved some excellent feedback from a couple of type designers I look up to especially, and this gave me a boost of ideas to refine the letterforms – making them wild but not _too_ wild, and straightforward but not naïve.

### Serious or playful? Yes.

Some monospace fonts are extremely serious. These can be really nice to work with, but in some situations, they can also feel a little too cold and hacker-y. Meanwhile, other monospace fonts are full of warmth and liveliness. These can be great for design, and some people love to code with them. However, I find these can be fun to the point of distraction.

I wanted something that could be serious when I wanted to intensely focus, like when I'm writing or reading a large, complex document. I *also* wanted something which could also be playful in situations where I don't have to read quite as much text, like when I'm running commands in a terminal and responding to the occassional error message. However, I don't want a serious font that lacks all personality, or a playful font that lacks utility and elegance.

Recursive – and in particular, its *Expression* axis – is my answer to these dual needs. The "Linear" side (`XPRN=0`) has low-contrast strokes and slightly-squarish shapes to present a serious tone and keep every letter distinct from its neighbors. The "Casual" side (`XPRN=1`) keeps more of the brushiness of Recursive's source materials, with soft stroke endings, medium-contrast strokes, and smoothly-curved shapes.

The Expression axis is a continuous range, so it is possible to use values in the middle. These look great at text sizes, and do a nice job of blending the serious and playful tones of recursive. However, at larger sizes (headlines and up), Recursive looks best with Expression fully up or down.

*(Comment: maybe we could leave out this description, as the homepage already describes the expression axis. Then again, perhaps this essay should stand on its own...)*

### From a "triospace" to a grid-based Sans

Early on, I intended to make a "Sans" that kept all monospace widths, aside from letters that should clearly be 0.5x or 1.5x width. This has precedents in such projects as [Covik](https://www.futurefonts.xyz/ohno/covik-sans-mono), and [iA Writer Duo](https://ia.net/writer/blog/a-typographic-christmas).

However, one of my teachers kept challenging this decision: why adjust only so few characters? Why not also characters that should be somewhere between 0.5x and 1x, like `f`, `r`, and `t`? And what about letters that should be just a bit wider than *that,* but not quite 1x – like `c` and `s`? I didn't have a great answer for this, beyond wanting to avoid creating a larger variable font in a completely duplicated set of sources.

So, I dug into my experience in web design. There, I had learned that using an [8-unit grid](https://spec.fm/specifics/8-pt-grid) was an extremely useful approach to efficiently creating designs which were both flexible and consistent. I took this idea into my typeface, dividing the total UPM into 20 sub-units, and using this for a grid system. My initial theory was that this might help the font display with extra fidelity at 10px on high-pixel-density screens. I soon found that fonts are hardly ever positioned exactly on pixel seams (outside of bitmapped LED screens), so this wasn't an especially practical or important goal. However, using this grid-based system for proportions was extremely helpful. It allowed Recursive to have nuanced spacing in its proportional ("Sans") styles. At the same time, this gridded approach allowed me to work more efficiently. Rather than stressing over pricise widths for every glyph with near-infinite options, I could instead select what was approximately correct. Better still, because many letters, numbers, and symbols still make the most sense at a "normal" width, many could be directly copied from the Mono sources into the Sans sources.

### Was the design "compromised" to achieve variability?

- Design is finding an elegant way to satisfy constraints and solve problems. With Recursive, I had done that. 
- Variable fonts require more thought about the *system* of a type family, and make it impossible to focus on just a few styles, as font designers could with static fonts. This means that it's much more versatile, but it also means that these fonts often don't have 100% flawless outlines.

### Working through technical difficulties

The concept & design of Recursive is rooted in the idea that every stroke of every letter should come from what a signpainter could produce with a brush. This approach enabled me to explore a system that could morph in proportion, expression, weight, and slant, but still remain cohesive and tied to its initial inspiration. Not only was Recursive conceptually based on this approach, but the shapes were drawn by following this concept quite literally. For the entirety of TypeMedia, I drew each glyph with multiple, separate contours for each "brush stroke" – a significantly different approach from the more-typical style of drawing digital type with interior contour overlaps left only for efficiency.

[IMAGE OF SKETCHES WITH SEPARATE CONTOURS]
[IMAGE OF EARLY BEZIER DRAWING WITH SEPARATE CONTOURS]

Near the end of TypeMedia, I discovered a major problem with my drawing approach: it resulted in rendering issues on screens. Where strokes overlapped, rasterizes would often "double up" the pixel darkness, giving some letters a blobby look. It was difficult to accept that this would have to be changed, both because it would be very labor-intensive to change all my drawings, and also because I felt that my concept would be diluted by removing the overlaps. However, to make the best-quality end product, my concept had to be adjusted. Luckily, I had help in adjusting my drawings, and the rework was actually beneficial in helping me to more fully consider how the final design ought to be. 

[SCREENSHOT OF BLOBS]

Even though the overlapped drawings ultimately required more work than expected, this unique approach helped me to create shapes that I may have otherwise missed. I definitely won't draw most fonts like this in the future, but if the right project calls for it, I may return to the idea again.


<!-- ------------------------------------------------------------------------- -->
<!-- Work in 2019 ------------------------------------------------------------ -->
<!-- ------------------------------------------------------------------------- -->

## Refining & finishing the project for release

- Google Fonts commissioned me to finish Recursive, and even paid a few colalborators to make it possilbe.

<!-- ------------------------------------------------------------------------- -->
<!-- Tools ------------------------------------------------------------------- -->
<!-- ------------------------------------------------------------------------- -->

## Workflows & Tooling

### MasterTools

### Glyph Mirror

### Var Font Prep & "homemade" scripts

### Type-X

<!-- ------------------------------------------------------------------------- -->
<!-- Get involved ------------------------------------------------------------ -->
<!-- ------------------------------------------------------------------------- -->

## Get involved!

### Browser bugs

Please go support the browser issues for 

### Kickstarter

### Contributing to the project

File bugs & PR on the GitHub repo.

<!-- ------------------------------------------------------------------------- -->
<!-- Credits ----------------------------------------------------------------- -->
<!-- ------------------------------------------------------------------------- -->

## The team

Recursive wouldn't have been possible without the mentoring, critique, and contributions from many designers and developers. The original thesis project recieved input not only frequent critique & advice from TypeMedia teachers, but also from type designers who visited or were kind enough to look at proofs during RoboThon and TypoLabs conferences. Tools built by Rafał Buchner and Roel Nieskens were vital to the design & testing workflow. In 2019, type design, refinement, and production was greatly assisted by contributions from Katja Schimmel and Lisa Huang. Ben Kiel has provided expert mastering for production fonts. Marketing was made possible by the design work of Math Practice, the web development by Talia Cotton, and greatly improved by the design feedback of Irin Kim and writing assistance from Noemi Stauffer. Finally, making this project a reality was made possible by the support of Dave Crossland and the engineering efforts of Google Fonts.

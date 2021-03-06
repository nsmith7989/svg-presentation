#Notes

Presentation given to [TechCamp Memphis](http://techcampmemphis.com/) November 1, 2014.

# SVG Animation

* [Polygon's SVG Xbox and PS4 Review](http://product.voxmedia.com/2013/11/25/5426880/polygon-feature-design-svg-animations-for-fun-and-profit)
* [CSS Tricks How SVG Line Animation Works](http://css-tricks.com/svg-line-animation-works/)
* [Guide to SMIL Animation](http://css-tricks.com/guide-svg-animations-smil/)
* [Can I use SMIL](http://caniuse.com/#feat=svg-smil)
* [24 Ways SVG Line Animation](http://24ways.org/2013/animating-vectors-with-svg/)

#Outline

* Problems Solved By SVG
    - SVG vs Raster Formats
        _ File Size
        - Scalability in Responsive
        - Editability
    - SVG is not a solution for
        - Photographic Images
* From Illustrator to SVG
    - Gotchas
        - Illustrator will apply inline styles (can be moved to an external stylesheet)
    - Export settings
* From SVG to the Web
    - Ways to get SVG into DOM
        - CSS Background (& base64 encode)
        - `<img>`
        - SVG nodes as DOM Elements (backend or raw)
        - `<object>`
    - SVG Sprites
    - SVG Compression Tools
    - Browser Support
        - Fallbacks / Progressive Enhancement
* Animation
    - Ways to animate SMIL vs CSS vs Javascript
        - Pros and Cons
        - How to Use Each
    - Line animation
    - Shape Morphing
* Demonstration of SVG Animations
    - [SnapSVG](http://snapsvg.io/)
    - [Codedrops Drawing Animation](http://tympanus.net/Development/SVGDrawingAnimation/)
    
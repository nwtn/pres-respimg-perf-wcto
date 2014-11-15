# Using Responsive Images Responsibly: Performance & Accessibility

David Newton

WordCamp Toronto 2014,  
November 15, 2014

Twitter: [@newtron](http://twitter.com/newtron/)  
GitHub: [@nwtn](http://github.com/nwtn/)  
Email: <david@davidnewton.ca>  

* [This presentation on GitHub](https://github.com/nwtn/pres-respimg-perf-wcto)
* [This presentation on Speaker Deck](https://speakerdeck.com/newtron/using-responsive-images-responsibly-performance-and-accessibility-wordcamp)

## Quotes

* “‘Disability’ means... any degree of physical disability, infirmity, malformation or disfigurement that is caused by bodily injury, birth defect or illness...” –<i>[Accessibility for Ontarians with Disabilities Act](http://www.e-laws.gov.on.ca/html/statutes/english/elaws_statutes_05a11_e.htm)</i>

* “Following these guidelines will make content accessible to a wider range of people with disabilities, including blindness and low vision, deafness and hearing loss, learning disabilities, cognitive limitations, limited movement, speech disabilities, photosensitivity and combinations of these. Following these guidelines will also often make your Web content more usable to users in general.” –<i>[Web Content Accessibility Guidelines 2.0](http://www.w3.org/TR/WCAG20/)</i>

* “The goal of Web design is not merely to dazzle, but to deliver information to the widest audience possible.	...Compromise should not come at the expense of the user, but rather in terms of the native capabilities of the user’s choice of device....	Leave no one behind.” —Steven Champeon, ‘[Inclusive Web Design for the Future](https://web.archive.org/web/20130821155239/http://www.hesketh.com/thought-leadership/our-publications/inclusive-web-design-future)’* “Rather than creating disconnected designs, each tailored to a particular device or browser, we should instead treat them as facets of the same experience.” —Ethan Marcotte, <i>[Responsive Web Design](http://www.abookapart.com/products/responsive-web-design)</i>* “Many of us are fortunate to live in high bandwidth regions, but there are still large portions of the world that do not. By keeping your client side code small and lightweight, you can literally open your product up to new markets.” —Chris Zacharias, ‘[Page Weight Matters](http://blog.chriszacharias.com/page-weight-matters)’
* “Universal design is the design of products and environments to be usable by all people, to the greatest extent possible, without the need for adaptation or specialized design.” —[Ronald L. Mace](http://www.ncsu.edu/ncsu/design/cud/about_ud/about_ud.htm)
* “More human beings today have access to a cellphonethan...a clean toilet.” —Anand Giridharadas, ‘[Where a Cellphone Is Still Cutting Edge](http://www.nytimes.com/2010/04/11/weekinreview/11giridharadas.html?_r=0)’, <i>The New York Times</i>

## References

* <i>[Responsive Web Design](http://www.abookapart.com/products/responsive-web- design)</i> by Ethan Marcotte
* ‘[Mobile Technology Fact Sheet](http://www.pewinternet.org/fact-sheets/mobile-technology-fact-sheet/)’ from PewResearch Internet Project
* ‘[Android Fragmentation Visualized (August 2014)](http://opensignal.com/reports/2014/android-fragmentation/)’ by OpenSignal
* ‘[Interesting stats](http://httparchive.org/interesting.php?a=All&l=Nov%201%202014)’ from the *HTTP Archive*
* ‘[Mo’ Pixels, Mo	’ Problems](https://speakerdeck.com/davatron5000/mo-pixels-mo-problems)’ (Speaker Deck) by Dave Rupert
* ‘[Mo’ Pixels, Mo	’ Problems](http://alistapart.com/article/mo-pixels-mo-problems)’ (A List Apart) by Dave Rupert
* ‘[HTML5: Techniques for providing useful text alternatives](http://www.w3.org/TR/html-alt-techniques/)’ by Steve Faulkner
* ‘[Using aria-describedby to provide descriptions of images](http://www.w3.org/WAI/GL/wiki/Using_aria-describedby_to_provide_descriptions_of_images)’
* ‘[Using aria-labelledby to provide a text alternative for non-text content](http://www.w3.org/WAI/GL/wiki/Using_aria-labelledby_to_provide_a_text_alternative_for_non-text_content)’
* ‘[W3C HTML5 Image Description Extension (longdesc) Implementation Report](http://w3c.github.io/test-results/html-longdesc/cr-report.html)’ by Charles (McCathie) Nevile and Liam R. E. Quin
* ‘[Using ARIA to enhance SVG accessibility](http://www.paciellogroup.com/blog/2013/12/using-aria-enhance-svg-accessibility/)’ by Léonie Watson


## Resources

### Specs
* [Responsive Images Specification](http://whatwg.org/html#the-picture-element) at WHATWG
* [Resource Priorities Specification](http://www.w3.org/TR/resource-priorities/) vs. [‘Preloading and deferred loading of scripts and other resources’](http://lists.whatwg.org/htdig.cgi/whatwg-whatwg.org/2014-August/297533.html)

### WordPress plugin
* [WP-tevko-responsive-images](https://github.com/ResponsiveImagesCG/wp-tevko-responsive-images)

### Polyfills and JavaScript
* [Picturefill](https://github.com/scottjehl/picturefill) (see also: ‘[To Picturefill, or not to Picturefill](http://filamentgroup.com/lab/to-picturefill.html)’ by Scott Jehl)
* [LazyLoad.js](http://css-tricks.com/snippets/javascript/lazy-loading-images/)
	* Note that for my demo site, I used a modified version of this script that worked with `picture`/`srcset`. [It is available in the demo directory](https://raw.githubusercontent.com/nwtn/pres-respimg-perf-a11yto/master/demo/assets/lazyload.js).

### Software and tools
* [ImageOptim](https://imageoptim.com/)
* [ImageOptim-CLI](http://jamiemason.github.io/ImageOptim-CLI/)
* [SVGO-GUI](https://github.com/svg/svgo-gui)
* [SVGO](https://github.com/svg/svgo)
* [Color Oracle](http://colororacle.org/)
* [webpagetest.org](http://webpagetest.org/)
* [Sizer Sozer](http://sizersoze.org/)

### Info
* [Responsive Images Community Group](http://responsiveimages.org/)
* [Responsive *Issues* Community Group](http://ricg.io/)
* [Responsive Images IRC](irc://irc.w3.org:6665/#respimg)
* [W3C Community Groups](http://www.w3.org/community/)

## Image credits

* [Android Fragmentation Visualized (August 2014)](http://opensignal.com/reports/2014/android-fragmentation/) by OpenSignal
* [Current device lab setup](https://twitter.com/lukew/status/507880029737328640/photo/1) via [Luke Wroblewski](https://twitter.com/lukew/status/507880029737328640/photo/1)
* [iMac with Retina 5K display](http://www.apple.com/ca/imac-with-retina/) by [Apple](http://www.apple.com/)
* [S5e22 Party God blast](http://adventuretime.wikia.com/wiki/File:S5e22_Party_God_blast.png) from Adventure Time via [Adventure Time Wiki](http://adventuretime.wikia.com/wiki/Adventure_Time_with_Finn_and_Jake_Wiki)
* [Photo of beach](demo/assets/original/hero.jpg) by [Pierre-Olivier Bourgeois](https://www.flickr.com/photos/po-bourgeois/), via [Unsplash](http://unsplash.com)
* [Oceanside cliffs](demo/assets/original/01.jpg) by [Artur Pokusin](http://pics.pokusin.com/), via [Unsplash](http://unsplash.com)
* [Palm trees](demo/assets/original/02.jpg) by [Florian Klauer](http://www.florianklauer.de/), via [Unsplash](http://unsplash.com)
* [Cafe](demo/assets/original/03.jpg) by [Dogancan Ozturan](http://dogancan.org/), via [Unsplash](http://unsplash.com)
* [Beach at sunset](demo/assets/original/04.png) by [Ry Van Veluwen](http://ryvanveluwen.com/), via [Unsplash](http://unsplash.com)
* [Coffee and macarons](demo/assets/original/05.jpg) by [Vee-O](http://dribbble.com/veeo), via [Unsplash](http://unsplash.com)
* [Swimming](demo/assets/original/06.jpg) by [Brooklyn Morgan](https://www.flickr.com/photos/mynameisbrooklyn/10294420724/), via [Unsplash](http://unsplash.com)

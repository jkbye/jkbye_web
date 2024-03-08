This is my personal Quarto website to deploy to [`jkbye.com`](http://www.jkbye.com). If you'd like to adapt any code for your site, please do so! Feel free to reach out if you have any questions (or suggestions!)

Here are some handy resources for making Quarto websites that I learned from / adapted from:

-   [Sam Csik](https://github.com/samanthacsik) has created an [indispensable resource](https://ucsb-meds.github.io/creating-quarto-websites/) for learning the basics of the web side of Quarto. I recommend starting there, it helped me tremendously. I also recommend Sam's [slides](https://ucsb-meds.github.io/customizing-quarto-websites/#/title-slide) on customizing with Sass. And then spending a lot of time tinkering with the CSS.

    -   Eventually I found that customizing CSS from the default Quarto template was easier for me than trying to customize a template that was 'closer' to the look I wanted. I found that just modifying from the default helped me keep the light mode and dark mode versions of the pages consistent.

-   Danielle Navarro (as always) explains things well on her [blog](https://blog.djnavarro.net/posts/2022-04-20_porting-to-quarto), especially about porting over old blog posts to Quarto. This helped me figure out how to structure my \[very old\] blog posts on my `Posts` page.

-   I also adapted some of the `Research` page code from Drew Dimmery's [blog](https://ddimmery.com/posts/quarto-website/) (and agree with Drew's motivation for Quarto over Hugo, which I almost never updated)

-   And the [Quarto docs](https://quarto.org/docs/websites/) are of course a great help as well for finding all the little details. Here are some specific pages I found helpful:

    -   After figuring out some intuitions from the guides above, reading through the full [website options](https://quarto.org/docs/reference/projects/websites.html) page made a lot more sense.

    -   All the listing customization options explanations [here](https://quarto.org/docs/websites/website-listings.html) are useful (and in the future, I may try to figure out the EJS template approach)

    -   Info on publishing to [Netlify](https://quarto.org/docs/publishing/netlify.html)

-   Also if you like icons, be sure to install [Academicons](https://github.com/schochastics/academicons) and [FontAwesome](https://github.com/quarto-ext/fontawesome) icons! Those links are for their Quarto extensions, but I found at a point that there were times I wanted the icons to show up when the Quarto short codes didn't work. So I also added the Academicons to `includes.html`.

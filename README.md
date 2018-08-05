# Google Search Results Clone

## Objective

To create a clone of the Google Search Results page using HTML and CSS.

#### Specifications

##### Main

1. Don't be a perfectionist
 * The page is just supposed to look like Google's page, not function like it
 * Spacing just needs to *similar*, not down to the pixel.
 * Dropdown menus, form submissions, and hover-highlighting should be ignored
2. Do as much as you can before viewing the page's source code or relying on Dev Tools
3. When complete, project should be pushed to GitHub. Git should be used for Version Control.

##### Optional:
4. Submit a pull request to contribute this solution to The Odin Project.

##### Ambiguous:
5. Should the project be mobile responsive?

#### Learning Objectives

This project is designed to facilitate practice towards mastery of HTML and CSS. In addition, it allows for practice creating and modifying a Version Control project with Git and GitHub. This is the "hard" version of the project.

## Author's notes

#### Preliminary Thoughts

I'm already very comfortable with HTML and CSS, so this is mostly review. However, I haven't used a lot of CSS Grid since taking [Codecademy's](https://www.codecademy.com/learn) [Learn CSS](https://www.codecademy.com/learn/learn-css) course nor CSS Flexbox since completing [Dave Geddes'](https://twitter.com/geddski) [Flexbox Zombies](https://mastery.games/p/flexbox-zombies) Flexbox gamification. In addition, I could definitely use some practice with icons. I have learned a lot about debugging with Dev Tools in [Wes Bos'](https://wesbos.com/) [JavaScript 30](https://javascript30.com/) course so it will be good to apply that knowledge in a genuine setting. Lastly, once I've finished the desktop layout I'll make the page mobile responsive even though I don't think it's a requirement, because that is a valuable thing to practice and that's really the whole point here.

#### Final Thoughts

This was a great project that helped me get over a number of my hang-ups. I was dreading adding the icons, and that turned out to be really easy when I finally knuckled down and pulled up a reference page. I'll never fear icons again. Another thing that was really helpful was getting the number links at the bottom (the numbers under the word "Gooooooogle") to highlight on mouseover, without also causing the letters in Gooooooogle (which are part of the same link) to also highlight on mouseover. This was something I knew was possible and was able to intuit without a reference, but it was great to work through.

Beyond that, this project really helped to illustrate just *how many decisions* go into the small details of a website design. I now have a lot of questions about Google's search results page, like:
* Why isn't the page responsive when you resize your browser?
* Why are the buttons on the right side (at the top) so far removed from the rest of the page?
* Why are the links in "People also search for" and "Searches related to your search" styled differently?
* Why is the very bottom line left-aligned?
* Why isn't more preview text shown?
* Why so much subtle variation in fonts, font weights, and font sizes?
I'm sure the page has been massively A/B tested and is optimized for user engagement to the highest degree, but objectively it seems like these details are arbitrary and inconsistent. Going back to the original point, it's amazing how many small details are in what on the surface is a pretty basic page celebrated for it's clean, sleek user interface.

Now, with that in mind, I did make the page mobile responsive, but due to the tedious nature of matching the existing mobile page and limited value in doing such work (not really learning anything new), I opted to just make a clean mobile layout with the existing content (and not bothering with toggling "display: none;" on modified versions of existing elements or excessive changes to the order of the elements). In other words, the mobile layout of my clone is a representation of the first draft of a mobile conversion starting with the existing desktop page. That said, I was dreading the conversion but thanks to CSS grid, Git, and Atom, doing so was an absolute joy and only took about 15 minutes start to finish. I simply made a copy of everything in the CSS file within the mobile query, then made a commit to git. After doing this, Atom would highlight all the changed lines. So I went through the mobile page and identified deficiencies, correcting them in the copied media query code. Once I was satisfied, I deleted all the media query lines that had not been modified since my last commit (since they are redundant) and voila!

**Please Note:** This page queries screen size based on "em" units, so to easily see the mobile screen you can simply increase the zoom on your desktop browser. I recommend to unmaximize your window to mimic a portrait layout.

## Miscellaneous

Read more about this project at The Odin Project's [Web Development curriculum](http://www.theodinproject.com/courses/web-development-101/lessons/html-css).

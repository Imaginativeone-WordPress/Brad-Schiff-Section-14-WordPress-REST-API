- [ ] Section 14: WordPress REST API (AJAX) 2 / 7|1hr 29min
	- [ ] 61. Quick Note About The Next Lesson 1min
	
	Quick Note About The Next Lesson
In the next lesson you’ll see me use jQuery. jQuery is not my first choice in 2020, but I don’t believe it makes sense to completely re-film the entire JavaScript portion of this course for very minimal changes. I encourage you to follow along with these lessons and use jQuery where I do as well, but rest assured that after we complete each JavaScript feature in the course, there is a newly added video lesson (filmed in June of 2020) where I walk you through the birds-eye-view of how I’d write the same feature without jQuery. In those video lessons you’ll also find a downloadable resource file with my plain JS source code that you’re free to drop into your project as a replacement for the jQuery powered module. For example, with regards to our search feature, at the very end of Section #16 you’ll find a new video lesson providing the jQuery free solution for the search feature.

Also, while it’s convenient that our automated setup loads our newest JS and CSS changes without a full page reload, this can be a problem when working with eventHandlers (such as clicking on a button).

If you’re noticing weird situations where clicking a button is actually triggering a JS event multiple times, it’s because the old event listeners weren’t removed when your newest JS was loaded on the fly. To avoid this, when working with certain eventHandlers you’ll want to manually refresh the browser (after saving your changes in your text editor) before testing out the feature you’re working on in the browser. If you’d like to disable this on-the-fly loading of our CSS and JS and want the browser to simply automatically perform a full traditional page reload after code changes, you can find out how to implement that by digging into the webpack.config.js file in our theme folder, and reading the comments I’ve left for us around line #81.

	- [ ] 62. Load WP Content with JS 18min
	- [ ] 63. Generate HTML Based on JSON 20min
	- [ ] 64. Conditional Logic Within Template Literal 18min
	- [ ] 65. Quick Misc Edits 11min
	- [ ] 66. Synchronous vs Asynchronous (Part 1) 12min
	- [ ] 67. Synchronous vs Asynchronous (Part 2) 10min

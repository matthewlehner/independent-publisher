Independent Publisher WordPress Theme
=====================

## Table of Contents

* [Theme Options](https://github.com/raamdev/independent-publisher#theme-options)
* [Post Covers (Full-Width Featured Iamges)](https://github.com/raamdev/independent-publisher#post-covers-full-width-featured-images)
* [Post Subtitles](https://github.com/raamdev/independent-publisher#post-subtitles)
* [Using a Child Theme to Customize Independent Publisher](https://github.com/raamdev/independent-publisher#using-a-child-theme-to-customize-independent-publisher)
* [Known Issues](https://github.com/raamdev/independent-publisher#known-issues)
* [Frequently Asked Questions](https://github.com/raamdev/independent-publisher#frequently-asked-questions)
    * [Why is my Header Image not showing on Single posts?](https://github.com/raamdev/independent-publisher#why-is-my-header-image-not-showing-on-single-posts)
    * [How do I get the small logo to show up in the top-left corner?](https://github.com/raamdev/independent-publisher#how-do-i-get-the-small-logo-to-show-up-in-the-top-left-corner)
    * [How do I make the JetPack Sharing Buttons look better?](https://github.com/raamdev/independent-publisher#how-do-i-make-the-jetpack-sharing-buttons-look-better)
    * [How do I make the Subscribe to Comments Reloaded Advanced Options look better?](https://github.com/raamdev/independent-publisher#how-do-i-make-the-subscribe-to-comments-reloaded-advanced-options-look-better)
    * [How do I make MailChimp Signup Forms look better?](https://github.com/raamdev/independent-publisher#how-do-i-make-mailchimp-signup-forms-look-better)
* [Color Schemes](https://github.com/raamdev/independent-publisher#color-schemes)
* [Theme Filters and Actions](https://github.com/raamdev/independent-publisher#theme-filters-and-actions)
* [Functions you can Override in a Child Theme](https://github.com/raamdev/independent-publisher#functions-you-can-override-in-a-child-theme)

## Theme Options

Theme Options can be found in `Dashboard → Appearance → Customize`.

### Colors

![screen shot 2014-01-24 at 7 28 45 pm](https://f.cloud.github.com/assets/53005/2000340/b0fbe268-8557-11e3-9579-ca95e3f07ee8.png)

The following colors can be changed via the Colors section:

- Text Color
- Background Color
- Link Color
- Title and Header Text Color
- Primary Meta Text Color
- Secondary Meta Text Color


### Layout Options

![screen shot 2014-02-11 at 7 19 46 pm](https://f.cloud.github.com/assets/53005/2143949/6c319bdc-937b-11e3-8e03-9af57e672ac8.png)

- **Single-Column Layout**. Disabled by default. This option allows you to force the site layout to a single-column, regardless of the browser width.

### Excerpt Options

![screen shot 2014-02-11 at 7 14 43 pm](https://f.cloud.github.com/assets/53005/2143914/c9a14fd4-937a-11e3-9a95-ff023ebf120f.png)

- **Post Excerpts**. Disabled by default. If you enable Post Excerpts the post excerpt will be shown on Blog, Archive, and Search pages instead of the full post content. If no excerpt is set, one is generated using the first 55 words (see [`the_excerpt()`](http://codex.wordpress.org/Function_Reference/the_excerpt)). This setting only applies to Standard and Chat post formats.
- **Generate One-Sentence Excerpts**. Disabled by default. When this option is enabled, a one-sentence excerpt will be generated for all posts that don't have an excerpt set. A "Continue Reading →" link is also placed below the generated excerpt. This setting only applies to Standard post formats and is only relevant when Post Excerpts are enabled.
- **Always Show Full Content for First Post**. When Post Excerpts are enabled, this option ensures that the very first post on the home page (or Posts Page, if different) shows the full post content instead of the excerpt.

### General Options

![screen shot 2014-02-11 at 7 15 01 pm](https://f.cloud.github.com/assets/53005/2143913/c9a0184e-937a-11e3-8ae6-966e4a08be80.png)

- **Show Post Word Count in Entry Meta**. Enabled by default. Shows the post word count in the entry meta on Blog, Archive, and Search pages. Only shows post word count for posts with the Standard Post Format.
- **Show Widgets on Single Pages**. Disabled by default. When this option is enabled, sidebar widgets will also be shown on Single pages.
- **Enable Multi-Author Mode**. Disabled by default. Enabling Multi Author Mode changes the behavior of the site to better support multiple authors. The author name is mentioned in the entry meta and the authors name always links to the author page instead of the home page. The Header Image (*Dashboard → Appearance → Customize → Header Image*) is treated as the site logo and placed as a small icon in top left of the single pages to provide a way of getting back to the home page.
- **Comments Call to Action**. "Write a Comment" by default. This allows you to change the label that shows up on the 'Write a Comment' button and also changes the title of the comment form itself.

## Post Covers (Full Width Featured Images)

Post Covers are full-width featured images that stretch across the entire top of the page.

![screen shot 2013-10-09 at 3 01 54 pm](https://f.cloud.github.com/assets/53005/1300647/558b2740-3115-11e3-92cc-6e23dd750bcb.png)

When setting a Featured Image as a Post Cover, it's important that you use an image that works for displaying full-width; 1200x600 is a good starting point. WordPress contains an Image Editor that you can use to crop images to the necessary dimensions.

### How to set a Featured Image as a Post Cover

To set a Featured Image as a Post Cover, first select the image from the Featured Image meta box and then press the **Update** button. When the page reloads you will see a checkbox that says "Use as post cover (full-width)". Check the box and then save the changes by pressing the **Update** button again.

![screen shot 2013-10-22 at 7 02 05 pm](https://f.cloud.github.com/assets/53005/1386236/fe8bff74-3b6d-11e3-8320-22efd60f423e.png)

## Post Subtitles

You can add a post subtitle at the top of your post content like this:

```
<h2 class="subtitle">Do what you love and do it often.</h2>
```

The `subtitle` class will style it like so:

![screen shot 2013-10-24 at 4 17 57 pm](https://f.cloud.github.com/assets/53005/1416672/d3f96c40-3f61-11e3-88eb-47428b696af4.png)

## Using a Child Theme to Customize Independent Publisher

If there are things you want to tweak in the Independent Publisher theme, a [Child Theme](http://codex.wordpress.org/Child_Themes) is the recommended method for doing so. By using a Child Theme, you can make changes without worrying about those changes being overwritten by a future update to the parent theme.

After you've installed the Independent Publisher theme, download the [Independent Publisher Child Theme](https://github.com/raamdev/independent-publisher-child-theme/) and install and activate it. You can then start making changes to the Child Theme's files to override the parent theme. The Independent Publisher Child Theme comes with a few examples to help you get started.

For more information on using Child Themes, see the [WordPress Codex](http://codex.wordpress.org/Child_Themes).

## Known Issues

* If you're using the [W3 Total Cache](http://wordpress.org/plugins/w3-total-cache/) plugin, you must disable the JS/CSS Minify option, as that [doesn't play well with jQuery](http://wordpress.org/support/topic/plugin-w3-total-cache-jquery-conflicts-when-added-to-minify?replies=6), which Independent Publisher makes use of. See also [Issue 46](https://github.com/raamdev/independent-publisher/issues/46#issuecomment-31478382).

## Frequently Asked Questions

### Why is my Header Image not showing on Single posts?

On Single pages, the Gravatar image for the author of the post is shown. The Header Image (*Dashboard → Appearance → Header*) is only shown on non-Single pages.

If there is only one author on your site, you probably want to set the Header Image to be the same as the author Gravatar. (You also probably want the site Tagline, *Dashboard → Settings → General → Tagline*, to be the same as your bio in *Dashboard → Users → Your Profile → Biographical Info*.)

### How do I get the small logo to show up in the top-left corner?

![a4360d06-83b8-11e3-95e6-2fba9c982761](https://f.cloud.github.com/assets/53005/2000384/67f60ef8-8558-11e3-97be-09c9f3b7ec16.png)

First you need to enable **Multi-Author Mode** in *Dashboard → Appearance → Customizer → General Options* . With Multi-Author Mode enabled, the theme Header Image (*Dashboard → Appearance → Header Image*) will be placed in the top-left corner on all Single pages.

### How do I make the JetPack Sharing Buttons look better?

If you clear the JetPack Sharing Buttons "Sharing label" field so that it's empty, Independent Publisher will force the sharing buttons to float right and will remove the right padding so that the buttons look nicer.

![4dc42092-83b9-11e3-96a3-8b9580f82f80](https://f.cloud.github.com/assets/53005/2000387/8c1796bc-8558-11e3-8ee4-0c4f9f4fbf2e.png)

### How do I make the Subscribe to Comments Reloaded Advanced Options look better?

Go to *Settings -> Subscribe to Comments -> Comment Form -> Custom HTML* and wrap the contents in a paragraph tag with the `comment-form-subscriptions` class. For example:

```
<p class='comment-form-subscriptions'><label for='subscribe-reloaded'>[checkbox_label]</label> [checkbox_field]</p>
```

Note that double-quotes are not allowed in that field and that you *must* use single quotes, i.e., `class='comment-form-subscriptions'`, NOT `class="comment-form-subscriptions"`.

### How do I make MailChimp Signup Forms look better?

MailChimp includes its own CSS in the HTML embed code that, by default, doesn't look quite right with Independent Publisher. To fix the MailChimp CSS, you can add the following to the `style.css` file of a [Child Theme](https://github.com/raamdev/independent-publisher-child-theme/) (or if you're using JetPack, simply go to *Appearance → Edit CSS* and insert the following):

```
#mc_embed_signup .button {
	padding-left: 15px !important;
	padding-right: 15px !important;
	padding-top: 2px !important;
	padding-bottom: 3px !important;
	font-weight: normal !important;
	width: 100% !important;
}

.entry-content #mc_embed_signup h2 {
	font-size: 1.8em !important;
}
.entry-content #mc_embed_signup input.email {
	width: 100% !important;
}
.entry-content #mc_embed_signup label {
	padding-bottom: 0 !important;
}
.entry-content #mc_embed_signup .mc-field-group {
	width: 99% !important;
}

.widget #mc_embed_signup form {
	text-align: center !important;
	font-family: "Myriad Pro", "Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", Geneva, Verdana, sans-serif;
}
.widget #mc_embed_signup input.email {
	width: 100% !important;
	text-align: center;
}
.widget #mc_embed_signup input.button {
	width: 100% !important;
}
```

![screen shot 2014-01-28 at 4 53 37 pm](https://f.cloud.github.com/assets/53005/2024233/c5642e38-8866-11e3-9d70-555eacbcb243.png)


## Color Schemes

You can modify the color scheme in *Appearance → Customize → Colors*. Here are a few recommended color schemes:

### Blue

* Set Link Color to `#26759e`

### Black

* Set Text color to `#f7f7f7`
* Set Background Color to `#000000`
* Set Link Color to `#1a609e`
* Set Title and Header Text Color to `#d1d1d1`
* Set Primary Meta Text Color to `#8e8e8e`
* Set Secondary Meta Text color to `#666666`

## Theme Filters and Actions

WordPress Filters and Actions allow you to modify the theme without actually modifying any theme code. To use any of these filters or actions, start by creating a [Child Theme](#using-a-child-theme-to-customize-independent-publisher) and then adding the relevant function to the `functions.php` file. See also [add_filter()](http://codex.wordpress.org/Function_Reference/add_filter) and [add_action()](http://codex.wordpress.org/Function_Reference/add_action) on the WordPress Codex.

### Filters

- `independent_publisher_taxonomy_category_stats` - Allows you to override the Category Archive stats that are appended to the category archive description.
- `independent_publisher_taxonomy_tag_stats` - Allows you to override the Tag Archive stats that are appended to the Tag Archive description.
- `independent_publisher_entry_meta_separator` - Allows you to override the default separator character that is used in the Entry Title Meta and Entry Post Meta (default is '|').
- `independent_publisher_entry_meta_category_prefix` - Allows you to override the default Category prefix (default is 'in'; e.g., "<author name> in <category name>").
- `independent_publisher_entry_meta_author_prefix` - Allows you to override the default Author prefix (default is 'by'; e.g., "by <author name>").
- `independent_publisher_search_stats` - Allows you to override the Search stats shown on Search pages.
- `independent_publisher_tag_list_title` - Allows you to override the default Tag List Title of 'Related Content by Tag' at the bottom of Single posts.
- `independent_publisher_pingslist_title` - Allows you to override the default Pings List title of 'Readers who Shared This' at the bottom of Single posts.
- `independent_publisher_pingslist_end_note` - Allows you to override the default Pings List end note of 'Thank you!' at the bottom of Single posts.

### Action Hooks

- `independent_publisher_entry_meta_top` - Located at the top of post Entry Meta, just before the 'Write a Comment' button.
- `independent_publisher_before_bottom_comment_button` - Located just before the second 'Write a Comment' button that shows up underneath post comments when there are more than 4 comments visible.
- `independent_publisher_before_post_bottom_tag_list` - Located before the bottom 'Related Content by Tag' tag list on Single posts.

## Functions you can Override in a Child Theme

### Functions in `inc/template-tags.php`:

- `independent_publisher_content_nav()` - Display navigation to next/previous pages when applicable
- `independent_publisher_comment()` - Template for comments and pingbacks.
- `independent_publisher_pings()` - Creates a custom query for pingbacks/trackbacks (i.e., 'pings') and displays them. Using this custom query instead of `wp_list_comments()` allows us to always show all pings, even when we're showing paginated comments.
- `independent_publisher_posted_author()` - Prints HTML with meta information for the current author.
- `independent_publisher_posted_author_cats()` - Prints HTML with meta information for the current author and post categories. Only prints author name when Multi-Author Mode is enabled.
- `independent_publisher_posted_on_date()` - Prints HTML with meta information for the current post-date/time.
- `independent_publisher_continue_reading_link()` - Prints HTML with Continue Reading link
- `independent_publisher_continue_reading_text()` - Returns Continue Reading text for usage in `the_content()`
- `independent_publisher_categorized_blog()` - Returns true if a blog has more than 1 category
- `independent_publisher_wp_title()` - Filters `wp_title` to print a neat `<title>` tag based on what is being viewed.
- `independent_publisher_post_categories()` - Returns categories for current post with separator. Optionally returns only a single category.
- `independent_publisher_site_info()` - Outputs site info for display on non-single pages
- `independent_publisher_posted_author_card()` - Outputs post author info for display on single posts
- `independent_publisher_posted_author_bottom_card()` - Outputs post author info for display on bottom of single posts
- `independent_publisher_get_post_word_count()` - Returns number of words in a post formatted for display in theme
- `independent_publisher_full_width_featured_image()` - Show Full Width Featured Image on single pages if post has full width featured image selected
- `independent_publisher_search_stats()` - Returns stats for search results
- `independent_publisher_taxonomy_archive_stats()` - Returns taxonomy archive stats and current page info for use in taxonomy archive descriptions
- `independent_publisher_date_archive_description()` - Returns the Date Archive description
- `independent_publisher_min_comments_bottom_comment_button()` - Returns the minimum number of comments that must exist for the bottom 'Write a Comment' button to appear
- `independent_publisher_min_comments_comment_title()` - Returns the minimum number of comments that must exist for the comments title to appear

### Functions in `functions.php`:

- `independent_publisher_author_comment_reply_link()` - Change the comment reply link to use 'Reply to [Author First Name]'
- `independent_publisher_comment_form_args()` - Arguments for `comment_form()`
- `independent_publisher_remove_textarea()` - Move the comment form textarea above the comment fields
- `independent_publisher_add_textarea()` - Recreates the comment form textarea HTML for reinclusion in comment form
- `independent_publisher_enhanced_comment_form()` - Enqueue enhanced comment form JavaScript
- `independent_publisher_site_logo_icon_js()` - Enqueue Site Logo Icon JavaScript if Multi-Author Site enabled
- `independent_publisher_is_multi_author_mode()` - Returns true if Multi-Author Mode is enabled
- `independent_publisher_single_author_link()` - Returns the author link; defaults to home page when not using multi-author mode
- `independent_publisher_post_word_count()` - Returns number of words in a post
- `independent_publisher_first_sentence_excerpt()` - Return the post excerpt. If no excerpt set, generates an excerpt using the first sentence.
- `independent_publisher_clean_content()` - Cleans the content for display as a Quote or Aside by stripping anything that might screw up formatting
- `independent_publisher_maybe_linkify_the_content()` - Returns the post content for Asides and Quotes with the content linked to the permalink, for display on non-Single pages
- `independent_publisher_maybe_linkify_the_excerpt()` - Returns the excerpt with the excerpt linked to the permalink, for display on non-Single pages
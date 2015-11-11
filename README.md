# Sass Atomic Design Architecture

    sass/
    |
    |– atoms/
    |	|- _typography.scss	    # Typography rules
    |	|- _form.scss           # Forms
    |	|- _button.scss	      	# Button
    |	…
    |
    |- molecules/
    |	|- _search.scss	      	# Search (label + input + button)
    |	|- _featured.scss       # Feature (image + title + paragraph)
    |	|- _hero.scss           # Hero (image + title + link)
    |	…
    |
    |- organisms/
    |	|- _navigation.scss	    # Navigation
    |	|- _footer.scss         # Footer
    |	|- _sidebar.scss        # Sidebar
    |	|- _header.scss	      	# Header
    |	…
    |
    |- templates/
    |	|- _theme.scss	      	# Default theme
    |	|- _admin.scss	      	# Admin theme
    |	…
    |
    |- pages/
    |   |– _home.scss         # Home specific styles
    |   |– _contact.scss      # Contact specific styles
    |
    |– utils/
    |   |– _variables.scss    # Sass Variables
    |   |– _functions.scss    # Sass Functions
    |   |– _mixins.scss       # Sass Mixins
    |   |– _helpers.scss      # Class & placeholders helpers
    |
    `– style.scss              # Main Sass file

#### References

- [http://bradfrost.com/blog/post/atomic-web-design/](http://bradfrost.com/blog/post/atomic-web-design/)
- [How to maintain product UX consistency?](https://blog.hannahcdesign.com/how-to-maintain-product-ux-consistency-71f58df0a91f)
- [https://github.com/franckgaudin/sass-atomic-design-architecture](https://github.com/franckgaudin/sass-atomic-design-architecture)
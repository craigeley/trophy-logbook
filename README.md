# Trophy Logbook – A Jekyll Journal

![](https://raw.githubusercontent.com/craigeley/trophy-logbook/master/_screenshots/individual_entry.png)

This is a variant of the [Trophy](https://github.com/thomasvaeth/trophy-jekyll) Jekyll theme designed to be used as a personal logbook or journal. Since it is based on a blogging platform, it uses some of Jekyll's built-in functionality in *very* nonstandard ways. Your mileage will certainly vary.

If you have never heard of Jekyll, learn all about it [here](http://jekyllrb.com/docs/home/).

## Features
- Jekyll's "tags" and "categories" have been hijacked to serve as person and place records, respectively. With help from [`jekyll archives`](https://github.com/jekyll/jekyll-archives), this allows for the automatic creation of records that answer such probing questions such as "How many times I have I really gone to Chipotle this year?" or "When was the last time I hung out with Jane?"
    + Additionally, by using Trophy's "_categories" folder, you can create a description and a picture to supplement these entries, much like a wiki. These entries are automatically updated to include the dates that you visited a place or met with a person.
- Automatically generated static maps using the Google Static Maps API. Simply add a street address or lat/lon coordinates to any entry.
    + A custom zoom level if you want to see the bigger picture.
- Easy extensibility and flexibility—it's just plain text.

## "Features"
- The use of `jekyll-archives` for automatic creation of person and place records *greatly* improves the functionality of this project. However, that makes it incompatible with [GitHub Pages](https://pages.github.com/). You can look at the original [Trophy](https://github.com/thomasvaeth/trophy-jekyll) repo for a Pages-compatible solution.

## Site Structure
From the home screen, the most visible elements are "days":
![](https://raw.githubusercontent.com/craigeley/trophy-logbook/master/_screenshots/homepage.png)

Days are comprised of individual entries, which are the posts contained in the `_posts` folder:
![](https://raw.githubusercontent.com/craigeley/trophy-logbook/master/_screenshots/summarized_day.png)

Posts can optionally contain people and person records, which create their own entries. By default, these entries only contain a list of all days for which they are in entries. However, by creating a sidecar file in the `_categories` folder, you can include metadata such as a picture and a description. These files should use a dash instead of a space in their name. See [the _categories folder](https://github.com/craigeley/trophy-logbook/tree/master/_categories) for examples, like this one:

![](https://raw.githubusercontent.com/craigeley/trophy-logbook/master/_screenshots/location_entry.png)

## Caveats
Feel free to leave comments and/or submit pull requests for obvious bugs, and I'll do my best. For things like major feature requests or changing how the site functions, I would suggest digging around in the code and seeing if you can built it yourself. In a sense, this project is provided "as-is."

## License
Trophy Jekyll is licensed under the MIT License.
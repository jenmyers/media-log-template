# Media Log Template

## A simple HTML template for keeping a yearly media log

### Implementation

For the past couple of years, I've kept a list of all the media I take in over the course of a year. Here you can grab the HTML template I use for your own purposes.

#### Customizing the Media Type Key

At the top of the template is a key that describes the type of media and the corresponding symbols for each item. You can adjust this depending on which types of media you want to track. The template starts with:

- Book (B)
- Film (F)
- Television series (T)
- Podcast series (P)
- Theater performance (TH)
- Music performance (M)

The key also includes a special character to indicate a reread, rewatch or relisten: [R]

#### Working with the HTML Structure

The HTML template contains three nested lists. The outer list contains each month in the log (provided: January through December). The second-level list contains each day in the month (provided: the first day of each month). The third-level list contains log items for its day (provided: an example of a film log item).

- To add more days in each month, replicate the list that begins with the comment `<!-- Day List -->` and change the day number accordingly.
- To add more items in each day, replicate the list item with the comment `<!-- Log Item -->` and change the title/type accordingly.

**If you are new to HTML, take a look at the [Mozilla Developer Network's guide to HTML unordered lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul).**

#### Styling

I've built in classes you can use to style each list and list item to match your own website:

- `log` = the outer `ul` list
- `log-month` = the `li` that contains each month title
- `log-day` = the `li` that contains each day number
- `log-item` = the `li` that contains the media item's title and type

**If you are new to styling HTML, take a look at the [Mozilla Developer Network's guide to CSS](https://developer.mozilla.org/en-US/docs/Web/CSS).**

### Reference

You can see the media log template in action at any of the logs linked at [jenmyers.net/log/](https://jenmyers.net/log/).

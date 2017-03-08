# [salt-jekyll](http://nathanarthur.com/salt-jekyll)

[AMPed](https://www.ampproject.org/) and [minified](https://medium.com/design-open/becoming-a-jekyll-god-ef722e93f771#.4zuacmmv8).

## Setup

```
bundle install
bundle update
```

## Serve

`bundle exec jekyll serve --config "_config.yml,_dev.yml"`

## Theme

All theme files not explicitly overridden are pulled from the Jekyll theme
[Minima](https://github.com/jekyll/minima).

## Todo

- Set up AMP-compliant GA install
- Add automated static HTML testing
- Make images responsive
- Add image float support
- In the "Give" section, I think the subtitles could be a little smaller, and
bold. I do really like the open-up style though.
- In "Lay Training," I think KMET should come before KMET Gallery in the tabs,
if possible.
- In the galleries, I think it would be helpful to have a little note at the top 
about how they can click the arrows to go through the pictures. I missed it the
first time I looked at them. :)
- Also in the galleries, is it possible to have captions for each picture? It's
something I'd probably have to go through and set for each one, but if it's easy
enough we could set it up so they're in there at least.
- Is there going to be a "Stories" section somewhere? Can all the "Stories" link
to the same page where it's open-up style, or do we need to have a separate
"Stories" tab in each section? Either way, it needs to be somewhere. :)
- Fix mobile navigation
- Remove style attribute from navigation divs (use amp-image instead) to avoid
amp validation errors

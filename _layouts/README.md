Not using this file in workflow. Notes only.

Hydejack uses th gem-loaded default.html unless a local file overrides it.

Here's how the Hydejack default.html will ask for components:

my-head.html
    →  head.html
        →  header.html
            →  {{ content }}
                →  footer.html
                    →  my-body.html

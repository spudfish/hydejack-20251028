Not using this file in workflow. Notes only.

Hydejack will be using its own gem-loaded default.html in response to the index.md front-matter that specifies default.

This project doesn't need its own default.html file here at this time.

Here's how the Hydejack default.html will ask for components:

my-head.html
    →  head.html
        →  header.html
            →  {{ content }}
                →  footer.html
                    →  my-body.html

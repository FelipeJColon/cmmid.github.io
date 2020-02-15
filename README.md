# OVERVIEW

The source for the [web page](https://cmmid.github.io/) advertising assorted [CMMID](https://cmmid.lshtm.ac.uk/) project work.

# Adding R Shiny Apps

To add a new shiny app to the [visualisations page](https://cmmid.github.io/visualisations.html), all you need to do is copy a file, and change two fields.

Detailed instructions:
 1. copy the [_shinyapp/template.md](https://github.com/cmmid/cmmid.github.io/blob/master/_shinyapp/template.md) file to a new file name in the same directory
 2. if using the Github interface, click raw to see the text to copy, then create a new file and paste that in; there is no simple way to duplicate a file in the web interface
 3. edit the `URL` in the `shinyurl: https://cmmid-lshtm.shinyapps.io/SOME_APP/` line to match the url where the application is hosted; this can be *any* url that serves up an R Shiny App
 4. edit the title; this must be valid YAML, so no new lines and watch out for `:` and `,` in your title - those and other special characters can be addressed by quoting the whole entry
 5. **DON'T** edit the `---`s.
 6. if using the Github web editing interface, you can check the preview to ensure proper entry. Should see a table-like thing
 7. commit your changes

# Conference Summaries

In this folder, we house the source code for the conference feedback document
that is passed between conference committees and encodes data about their event
to inform their successors and future conferences of successes.

## Process
1. Pull updates from the origin.
2. Copy the contents of `conf_summary_template.md` and paste them at the top of the `conf_summary.md` file above the previous conferences.
3. Fill out the information to the best of your ability.
4. Push changes to the main branch.

## Building the pdf
All you have to do is run `make all` in the command line, as long as you have
installed `pandoc`. This will generate a pdf called `conf_summary.pdf`, which
you can view as a normal `.pdf`.

You can also run `make clean` to remove the pdfs, or run `make rebuild` to
clean and then build the pdf.
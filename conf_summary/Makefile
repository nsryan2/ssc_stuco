
# Produce PDFs from the conference summary file in this directory.

manuscript = conf_summary

all: all-via-pdf

all-via-pdf: $(manuscript).md
	pandoc $(manuscript).md -o $(manuscript).pdf

# Remove all PDF outputs
clean:
	rm -f $(manuscript).pdf

# Remove all PDF outputs then build them again
rebuild: clean all
# sample-arch42-doc
# Source Files
The asciidoc source files are under:

    src/main/asciidoc
    
The `arc42-template.adoc` loads the currently existing files under:

    src/main/asciidoc/src

# Generate Asciidoc
You can generate the asciidoc in `html` and `pdf` form with:

    mvn generate-resources
    
The generated `.html` and `.pdf` files can be found in:

    target/generated-docs
    
under the `html` and `pdf` directories.


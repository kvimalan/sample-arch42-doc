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

# Add images to the docs
'*How to add images?.*'

Add images under folder src/main/asciidoc/images.


'*How to link images under any section(arch42)?*'

Suppose, if you want to add images under section (05_building_block_view.adoc)

= image:Java_virtual_machine.png[Java Virtual Machine]



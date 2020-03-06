# asciidoc to html

This action convert adoc file to html.
you must specified source directory name and destination directory name(relative path).

# Usage
```yaml
jobs:
  test:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v2
    - uses: mougenko/asciidoc-to-html@v1.0.0
      with:
        src: src
        dest: target
```

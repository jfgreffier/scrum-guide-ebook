# The Scrum Guide as e-book
The 2020 Scrum Guide as Markdown, EPUB, mobi... Scrapped from http://scrumguides.org/scrum-guide.html, converted with pandoc.

```
pandoc --metadata-file=metadata.yaml 2020-scrum-guide.md --to epub3 -o 2020-scrum-guide.epub
kindlegen 2020-scrum-guide.epub
```

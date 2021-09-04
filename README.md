# The Scrum Guide as e-book
The 2020 Scrum Guide as Markdown, EPUB, mobi... Scrapped from http://scrumguides.org/scrum-guide.html, converted with pandoc.

- [Scrum Guide in Makdown](./2020-scrum-guide.md)
- [Scrum Guide in EPUB](https://github.com/jfgreffier/scrum-guide-ebook/releases/latest/download/2020-scrum-guide.epub)
- [Scrum Guide for Kindle](https://github.com/jfgreffier/scrum-guide-ebook/releases/latest/download/2020-scrum-guide.mobi)

## Generate ebook from Markdown
```
pandoc --metadata-file=metadata.yaml 2020-scrum-guide.md --to epub3 -o 2020-scrum-guide.epub
kindlegen 2020-scrum-guide.epub
```

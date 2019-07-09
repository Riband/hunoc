# Hexo Theme Unit Test Checklist

## Checklist(YES:13 PARTLY:2 NO:2 UNKNOWN:1)

### `<head>`

- [YES]Use the proper [DOCTYPE](https://en.wikipedia.org/wiki/Document_Type_Declaration).
  If you don't know which doctype you should use, `<!DOCTYPE html>` is recommended.
- [YES]UTF8 charset
- [YES]Proper titles for different pages
- [YES:Optional]RSS support
- [YES]Favicon support

### Index

- [PARTLY]Only display excerpts. (Better with a "Read More" link)
- [YES][Pagination](https://hexo.io/docs/configuration.html#Pagination)

### Post

- [YES]Display post categories and tags.
- [YES,but manully paste your code to comment.ejs]Disqus comment support.
- [YES]Display the post date.
- Support [NO]`photo` and [YES]`link` layout.
- [YES]Posts without title should be accessible.

### Performance

- [UNKNOWN]Use [fragment_cache](https://hexo.io/docs/helpers.html#fragment_cache)  

### Optional

- [YES]Responsive design
- [PARTLY:English and Chinese]i18n
- [NO]Post share
- [YES]SEO

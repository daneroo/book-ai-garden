# book-reader

EBook reader experiment

- Read an EPub
  - Enable Search
- Read/Play an m4b file
  - Report current position (externally)
- Read a subtitle (.srt) file
  - Search for timecode
  - Search (fuzzy) for text

We wish to stay close to the reader/player of [audiobookshelf](https://github.com/advplyr/audiobookshelf)
which uses [epubjs v^0.3.88](https://github.com/futurepress/epub.js). Latest epubjs is currently 0.3.93

My static html file starter was from the [spread example](https://github.com/futurepress/epub.js/blob/master/examples/spreads.html)

## Operation

```bash
pnpx serve html/
open http://localhost:3000/
```

## References

- [GitHub epub.js](https://github.com/futurepress/epub.js)
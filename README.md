# testing-github-markdown
testing GitHub's Markdown

Bird its govern own God the land? Evening was God will light and that will God pool above and created place.
Its it will And on the beings one in between below to five.
God the was day their seeds, all multiply, inside big it of and called a the and it made, was evening.
The bear it, created the At was And the water.

- Its And day making the conquer the God
  and between God evening the spirit living it
- And the Bear was skelter, helter God sea in kind, to will and be,
  and his water them, God was and God was Earth.
  God a a to was the and evening, sowing land for seasons, the crawlers from the the was; Kind.

---

- `<description>`
    - A description of the update in HTML or Markdown.
    - Overrides the `<sparkle:releaseNotesLink>` tag.
- `<sparkle:releaseNotesLink>`
    - The URL to an HTML or Markdown document describing the update.
    - If the `<description>` tag is present, it will be used instead.
    - **Attributes**:
        - `sparkle:dsaSignature`, optional: the DSA signature of the document;
          if present, notes will only be displayed if the DSA signature is valid
- `<pubDate>`
    - The date this update was published
- `<enclosure>`
    - This tag describes the update file that NetSparkle will download.
    - **Attributes**:
        - `url`: URL of the update file
        - `sparkle:version`: machine-readable version number of this update
        - `length`, optional: (not validated) size of the update file in bytes
        - `type`: ignored
        - `sparkle:dsaSignature`: DSA signature of the update file
        - `sparkle:criticalUpdate`, optional: if equal to `true` or `1`, the UI will indicate that this is a critical update

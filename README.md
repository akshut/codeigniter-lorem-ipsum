# CodeIgniter lorem ipsum Generator Helper
This helper function will generate placeholder Lorem Ipsum text.

I used [loripsum.net](http://loripsum.net) api service. I am using file_get_contents but you can use curl also.

# Usage
`lipsum(paragraphs, length, extra_options)` - placeholder text

### Text Options

- 2 short paragraphs: `lipsum(2, 'short')`
- 1 medium paragraphs: `lipsum(1, 'medium')`
- 1 long paragraphs with decorations (bold, italic text) and links: `lipsum(1, 'long', array('decorate', 'link'))`

More options that you can add to array:

- decorate > Add bold, italic and marked text
- link > Add links
- ul > Add unordered lists
- ol > Add numbered lists
- bq > Add blockquotes
- code > Add code samples
- headers > Add headers
- allcaps > Use ALL CAPS

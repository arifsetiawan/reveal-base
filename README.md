
# Simplified Reveal.js

Simplified [Reveal.js](https://github.com/hakimel/reveal.js) using the latest [3.1.0](https://github.com/hakimel/reveal.js/releases/tag/3.1.0) release. Set to use markdown as presentation source.

# Flow

* Download zip archive of the repo [https://github.com/arifsetiawan/reveal-base/archive/master.zip](https://github.com/arifsetiawan/reveal-base/archive/master.zip)
* Extract
* Update [index.html](index.html) data on title, description and author
* Update [slides.md](slides.md) with your own content
* Run static file server on your folder (for example, using python: `python -m SimpleHTTPServer`)
* Glory!

# Example markdown

* Horizontal slide separator: --SLIDE--
* Vertical slide separator: --SUBSLIDE--

```
# Title

--SLIDE--

## Slide 1
Slide 1.1

--SUBSLIDE--

## Slide 1
Slide 1.2

--SLIDE--

## Slide 2
Slide 2
```


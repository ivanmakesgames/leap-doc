---
title: References
slug: references
disable_toc: true
# class: references
---

This is an example chapter for citing references. 


### Citations in text

Here's an example citation to be included in a text, 
with a link to the references chapter:

```
[(Berg, 1997)](references#berg-1997)
```

...which renders as [(Berg, 1997)](references#berg-1997).

### Reference list

Use a "references" chapter in the book's end matter to list all of the complete citations,
and receive inbound links from the in-text citations.
In the front matter of the references page,
set `class: references` so that the citations are formatted with hanging indents.

Include a link in each reference (like the ISBN search below), 
and assign it an `id` attribute with `{:#my-id}` so the anchor links from in-text citations work.

{% raw %}
```
Berg, C. (1997). *Mastering Guitar Technique: Process and Essence (Classic Guitar).* Mel Bay Publications, Inc.
[ISBN search](https://en.wikipedia.org/wiki/Special:BookSources?isbn=9781610650588){:#berg-1997}
```
{% endraw %}

## References

<div class="references">

Berg, C. (1997). *Mastering Guitar Technique: Process and Essence (Classic Guitar).* Mel Bay Publications, Inc.
[ISBN search](https://en.wikipedia.org/wiki/Special:BookSources?isbn=9781610650588){:#berg-1997}

Friedland, E. (1995). *Building Walking Bass Lines.* United States: Hal Leonard.
[ISBN search](https://en.wikipedia.org/wiki/Special:BookSources?isbn=9780793542048){:#friedland-1995}

Goodrick, M. (1987). *The Advancing Guitarist: Applying Guitar Concepts & Techniques.* Hal Leonard.
[ISBN search](https://en.wikipedia.org/wiki/Special:BookSources?isbn=0-88188-589-4){:#goodrick-1987}

Ligon, B. (1999). *Comprehensive Technique for Jazz Musicians: For All Instruments* (2nd ed.). Houston Publishing, Inc.
[ISBN search](https://en.wikipedia.org/wiki/Special:BookSources?isbn=978-0-634-00176-5){:#ligon-1999}

Tagg, P. (2018). *Everyday Tonality II (towards a tonal theory of what most people hear).* Van Duuren Media.
[ISBN search](https://en.wikipedia.org/wiki/Special:BookSources?isbn=978-0-9908068-0-6){:#tagg-2018}

Vincent, R. (2011). *Three-Note Voicings and Beyond.* Sher Music Co.
[ISBN search](https://en.wikipedia.org/wiki/Special:BookSources?isbn=1-883217-66-0){:#vincent-2011}

</div>

---
```
This file is located at: {{ page.path }}
```
---
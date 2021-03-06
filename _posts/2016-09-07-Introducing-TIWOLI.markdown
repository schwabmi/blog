---
title: Introducing TIWOLI ("Today in World Literature"), a Calendar App of Fictional Events
layout: post
author: [frank, jannik]
comments: true
date: 2016-09-07
---

This could become a whole new series: **Fancy by-products of Digital Humanities research projects…**

**Short version:** Download TIWOLI for Android **[here](https://play.google.com/store/apps/details?id=de.wannauchimmer.apps.tiwoli)**. Download TIWOLI for iOS **[here](https://appsto.re/de/I69sfb.i)**.

**Update (Oct 29, 2016):** The iOS version is finally available in the App Store. The article was updated accordingly.

And now let's jump right into it and name seven famous days in world literature:

- The day of James Joyce's "Ulysses"? (Of course, [Bloomsday](https://en.wikipedia.org/wiki/Bloomsday), [Lá Bloom](https://ga.wikipedia.org/wiki/L%C3%A1_Bloom), June 16!)

That is an easy start, but the world beyond this über-day of world literature is trickier. Most people will know about the fictional events we're going to itemise, but won't typically have the exact dates in mind. Let's check:

- On which day did Robinson Crusoe set foot on his island? (September 30) On which day did he eventually return to England, after 35 years of absence? (June 11)
- When is the deadline for Phileas Fogg's travel around the world in eighty days? (December 21)
- What's Tristram Shandy's birthday? (November 5) – Funny enough, there still seem to be [people drinking to Tristram Shandy's health](http://edwardiansisterhood.blogspot.de/2009/11/hill-times.html).
- When did Goethe's "Young Werther" commit suicide? (December 21)
- On what day did Charlie visit the Chocolate Factory? (February 1) – Especially interesting to note here that [in the 1971 movie](https://en.wikipedia.org/wiki/Willy_Wonka_%26_the_Chocolate_Factory), the golden ticket refers to "the first day of October" for whatever reason.

So this is the subject of our blogpost, **(in)famous days in world-literary fiction**.

How did this come about? At the annual ADHO Digital Humanities conference 2015 ([DH2015](http://dh2015.org/)) in Sydney, we delivered a talk called "When does (German) literature take place?" ([slides](http://dbs.ifi.uni-heidelberg.de/fileadmin/Team/jannik/publications/dh2015-sydney-fischer-stroetgen-german-literature-slides.pdf)) In order to answer that unusual question, we extracted exact dates and months from a corpus of 2,700+ works of German-language fiction from 1510 to the 1940s. Our results suggested that ["the marvellous month of May"](https://de.wikisource.org/wiki/Im_wundersch%C3%B6nen_Monat_Mai) (Heinrich Heine) is preeminent in our corpus of German fiction. There was already enough evidence to claim that May is the favourite month of poets (at least in the northern hemisphere), and Heine is just one example. But May's preeminence in prose was a real finding and there are a bunch of explanations, but this (along with many other insights yielded by this whole date-extraction-from-fiction business) shall happen in the corresponding research paper, not here.

As a by-product (and no more than that), we coded a native Android app to showcase the more exciting and self-explanatory of our results. We called our app **TIWOLI** (short for "Today in World Literature") and made it **[available via the Google Play Store](https://play.google.com/store/apps/details?id=de.wannauchimmer.apps.tiwoli)**. This was followed by **[the iOS version](https://appsto.re/de/I69sfb.i)**, done by our dear friend [Thomas Bögel](http://thboegel.de/project/).

Now what TIWOLI does is give you the opportunity to zigzag through an entire world-literary year, a calendar filled with fictional happenings. Here some screenshots with some of the examples from above:

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-06-16-joyce-ulysses.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/4300">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-02-01-dahl-charlie.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://books.google.com/books?id=v7WeJp2CU-QC&pg=PT55">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-11-05-sterne-tristram.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/1079">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-12-20-verne-eighty.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/103">source</a>)</figcaption></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

We're currently curating three corpora for the app, in **English**, **Spanish** and **German**. In some cases, you can even switch between translations of one and the same passage (not in all cases, though, the contents of our corpora are very different per language). This is a 1st-of-January example from Balzac's novel "Eugénie Grandet":

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-01-01-balzac-eugenie.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/1715">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-es-01-01-balzac-eugenia.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://es.wikisource.org/wiki/Eugenia_Grandet">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-01-01-balzac-eugenie.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://gutenberg.spiegel.de/buch/4850/3">source</a>)</figcaption></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

The interface was also translated into the three languages (it will fall back to English if your system language cannot be matched). Here are the three versions of our welcome screen, plus the English version of the settings page:

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-welcome.png" alt="Screenshot from TIWOLI app."></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-bienvenido.png" alt="Screenshot from TIWOLI app."></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-willkommen.png" alt="Screenshot from TIWOLI app."></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-settings.png" alt="Screenshot from TIWOLI app."></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

If you like you can set the alarm so it informs you about fictional events that "happened" on the current day.

It was not all that easy to fill up a whole year with suitable quotes for every day. To replenish the English corpus with nice enough quotes we are very grateful to Mark Algee-Hewitt and the Stanford Literary Lab who helped us out with their corpus of English-language fiction. Let's give you some more:

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-01-15-bronte-jane-eyre.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/1260">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-02-01-twain-wilson.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/102">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-02-22-fitzgerald-beautiful.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/9830">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-03-04-doyle-scarlet.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/244">source</a>)</figcaption></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

For each corpus, the app contains quotes from translated world-literary works, too, because after all, weltliteratur is the raison d'être of this blog:

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-03-16-novalis-ofterdingen.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/31873">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-03-25-hugo-hunchback.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/2610">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-04-07-gogol-nose.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/36238">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-05-20-turgenev-fathers.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/30723">source</a>)</figcaption></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

The dates from the Russian 19th-century novels point to the Julian calendar, of course (which was 12 days behind the Gregorian back then). Some more translated literature:

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-06-12-hamsun-mysteries.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://books.google.com/books?id=xB6nAgAAQBAJ&pg=PT4">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-07-05-voltaire-micromegas.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://en.wikisource.org/wiki/Micromegas/Chapter_3">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-07-27-zweig-chess.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://books.google.com/books?id=Uv4UAgAAQBAJ&pg=PT31">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-09-23-hoffmann-pot.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://gutenberg.net.au/ebooks06/0605801h.html">source</a>)</figcaption></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

For every quote we provide a link to the full-text source (gutenberg.org, gutenberg.net.au, archive.org, books.google.com, …). Epitexts and links/metadata are generated automatically. The portraits/pictures were not chosen by us, we're relying on the 'principal image' provided by Wikidata, a great way to easily enrich an app. Let's give you the Defoe examples from above, accompanied by Poe (for the sake of rhyming names):

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-06-22-poe-roget.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/2147">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-07-10-poe-maelstrom.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://en.wikisource.org/wiki/Tales_(Poe)/A_Descent_into_the_Maelstr%C3%B6m">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-09-30-defoe-robinson.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/521">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-12-19-defoe-robinson.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/521">source</a>)</figcaption></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

Some more German literature in translation, including the aforementioned destiny of storm-and-stressy Werther:

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-09-27-fontane-effi.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://archive.org/stream/EffiBriest/fontane_theodor_1819_1898_effi_briest#page/n91/mode/2up">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-10-03-fontane-effi.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://archive.org/stream/EffiBriest/fontane_theodor_1819_1898_effi_briest#page/n31/mode/2up">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-10-30-hoffmann-sandman.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/32046">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-12-21-goethe-werther.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/2527">source</a>)</figcaption></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

The first two quotes are from Fontane's "Effi Briest", in many respects the righteous German counterpart to "Madame Bovary". The second quote alludes to Effi's and Instetten's wedding which coincides with the national day of Germany (not a good omen, given the tragic outcome of the novel 😇).

Four final examples from the English corpus:

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-07-31-shelley-frankenstein.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/84">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-11-02-eliot-bede.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/507">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-11-09-wilde-dorian.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/174">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-12-10-stevenson-hyde.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/43">source</a>)</figcaption></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

The last quote, from "Jekyll &amp; Hyde", is interesting insofar as the given date can be regarded a mistake by the author that went into several print editions (as [discussed here](https://books.google.com/books?id=sk7zCQAAQBAJ&pg=PA64), for example).

We also harvested some newer books as you can see in the Auster example below (the picture is not the best, but somebody might upload a better one to Wikimedia Commons someday). There's also one more Brontë quote and two nice quotes from the time-travel novel by Bellamy (where times and dates are the actual subject):

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-03-20-bronte-heights.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/768">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-05-19-auster-glass.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://books.google.com/books?id=VRfe-QG_ls4C&pg=PA10">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-05-30-bellamy-2000.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/624">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-en-09-10-bellamy-2000.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://www.gutenberg.org/ebooks/624">source</a>)</figcaption></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

Now let's sneak a peek at the Spanish corpus. You can easily switch to the other corpora at any point from within the app.

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-es-04-22-valera-pepita.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://es.wikisource.org/wiki/Pepita_Jim%C3%A9nez:_08">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-es-06-15-caballero-gaviota.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://es.wikisource.org/wiki/La_gaviota_(Caballero):_17">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-es-07-12-baroja-silvestre.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://oreneta.com/kalebeul/2006/06/14/silvester-paradox-meets-mr-macbeth/">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-es-07-20-cervantes-quijote.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://cvc.cervantes.es/literatura/clasicos/quijote/edicion/parte2/cap36/default.htm">source</a>)</figcaption></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

We can also follow the chronology of Borges' cuento "La muerte y la brújula" (["Death and the Compass"](https://en.wikipedia.org/wiki/Death_and_the_Compass)):

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-es-12-03-borges-brujula.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://www.literatura.us/borges/lamuerte.html">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-es-01-03-borges-brujula.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://www.literatura.us/borges/lamuerte.html">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-es-02-03-borges-brujula.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://www.literatura.us/borges/lamuerte.html">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-es-03-01-borges-brujula.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://www.literatura.us/borges/lamuerte.html">source</a>)</figcaption></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

Some concluding Spanish examples:

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-es-02-28-dumas-montecristo.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://es.wikisource.org/wiki/El_conde_de_Montecristo:_1-15">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-es-12-21-goethe-werther.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://ciudadseva.com/texto/werther/">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-es-10-11-marquez-soledad.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://mgarci.aas.duke.edu/cibertextos/EDICIONES-BILINGUES/GARCIA-MARQUEZ-G/CIEN-ANOS-SOLEDAD/CAP13.HTM">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-es-12-31-aira-fantasmas.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="https://books.google.com/books?id=LJPxQvuMd-oC&pg=PA7">source</a>)</figcaption></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

On to the German-language corpus:

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-01-20-buechner-lenz.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://www.zeno.org/Literatur/M/B%C3%BCchner,+Georg/Erz%C3%A4hlung/Lenz">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-04-04-schnitzler-gustl.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://gutenberg.spiegel.de/buch/5342/1">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-05-12-lasswitz-planeten.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://gutenberg.spiegel.de/buch/8473/17">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-07-27-zweig-schachnovelle.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://gutenberg.spiegel.de/buch/7318/2">source</a>)</figcaption></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

The first quotation, from Georg Büchner's novella fragment ["Lenz"](https://en.wikipedia.org/wiki/Lenz_(fragment)), is probably one of the most famous first sentences. On the second screenshot, Schnitzler's ["Leutnant Gustl"](http://www.encyclopedia.com/article-1G2-3408300617/none-but-brave-leutnant.html) is pondering his destiny on 4th of April, resulting in **not** killing himself. On the third one, the government of the Martian States takes control over our planet, because we earthlings are not capable of maintaining peace (the author of the passage, [Kurd Lasswitz](https://en.wikipedia.org/wiki/Kurd_Lasswitz), can be regarded a pioneer of German sci-fi lit). The fourth quote is especially interesting, since the "27th of July" is also discussed in a "meta" way, as a combination of a printed number and a word, which serves as intellectual nourishment for the imprisoned intellectual (if you didn't install the app yet, check the English translation of this passage [on Google Books](https://books.google.com/books?id=Uv4UAgAAQBAJ&pg=PT31)).

We already featured Theodor Fontane with some paragraphs translated to English. But what is it with the Prussian author and the 3rd of October? It is an eventful day in many of his novels, and we're not sure if anyone has looked into that yet:

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-10-03-fontane-birnbaum.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://gutenberg.spiegel.de/buch/4437/20">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-10-03-fontane-effi.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://gutenberg.spiegel.de/buch/4446/5">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-10-03-fontane-stechlin.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://gutenberg.spiegel.de/buch/4434/2">source</a>)</figcaption></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

Fitfully, we included some quotations from contemporary fiction. The given sources contain page numbers as they point to print editions of the works:

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-07-19-zeh-unterleuten.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://d-nb.info/1078450226">source</a>, p. 287)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-07-23-goetz-holtrop.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://d-nb.info/1017662762">source</a>, p. 275)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-08-15-werner-abgang.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://d-nb.info/840734891">source</a>, p. 116)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-12-12-enzensberger-robert.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://d-nb.info/954601262">source</a>, p. 31)</figcaption></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

Some more:

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-10-07-schmidt-atheisten.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://d-nb.info/942534050">source</a>, p. 11)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-10-12-stein-rabbi.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://d-nb.info/1045299928">source</a>, pp. 72)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-11-09-richter-gran-via.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://d-nb.info/1008856525">source</a>, p. 144)</figcaption></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

The first quote from Arno Schmidt's 1972 novel ["The School for Atheists"](https://en.wikipedia.org/wiki/The_School_for_Atheists) points to a future date, the 7th of October, 2014. When we traversed this point in time two years ago, at least one major newspaper published an article about this long-imminent event (German weekly "Die Zeit": ["The story starts now."](http://www.zeit.de/2014/43/arno-schmidt-tellingstedt-die-schule-der-atheisten)).

How about [Jean Paul](https://en.wikipedia.org/wiki/Jean_Paul), the greatest of all May lovers:

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-05-01-jean-paul-hesperus.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://gutenberg.spiegel.de/buch/3193/6">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-05-03-jean-paul-quintus.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://gutenberg.spiegel.de/buch/3209/31">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-05-16-jean-paul-quintus.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://gutenberg.spiegel.de/buch/3209/34">source</a>)</figcaption></figure></li>
 </ul>
</div>
<div style="clear:left;"></div>

And last not least, some Christmas quotes:

<div class="tiwoligallery">
 <ul>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-12-24-droste-huelshoff-judenbuche.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://gutenberg.spiegel.de/buch/2837/7">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-12-24-hesse-unterm-rad.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://d-nb.info/1025308913">source</a>, p. 204)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-12-24-hoffmann-nussknacker-und-mausekoenig.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://gutenberg.spiegel.de/buch/3083/1">source</a>)</figcaption></figure></li>
  <li><figure><img src="{{ site.url }}/images/tiwoli/tiwoli-de-12-24-mann-buddenbrooks.png" alt="Screenshot from TIWOLI app."><figcaption>(<a href="http://d-nb.info/970666128">source</a>, p. 582)</figcaption></figure></li>
 </ul>
</div>

So much for our app, TIWOLI. Also if it wasn't part of the original research, it helped to sharpen our notion of dates and month names in fictional texts. Literature as a genre has an inclination to waive exact dates and prefers temporal settings like "at the beginning of November", ["It was a dark and stormy night"](https://en.wikipedia.org/wiki/It_was_a_dark_and_stormy_night), etc. But sometimes exact dates do occur, of course. And if they do, they have a tendency to mean something. (Unless, of course, they occur in epistolary, adventure or historical novels which are usually full of exact dates. We tried to exclude them from the app and just used some as fill-ins. Goethe's "Werther", all Jules Verne novels and Benito Pérez Galdós proved especially useful. 😊)

Before we conclude this admittedly BuzzFeed-like über-post with far too many pics we have two cliffhangers for you:

- Our friends at the University of Cologne ([Spinfo](http://www.spinfo.phil-fak.uni-koeln.de/)/[CCeH](http://www.cceh.uni-koeln.de/)) are currently building a web interface with our data. [Prototype looks very promising.](https://twitter.com/spinfocl/status/794147295084314624)
- There's an **easter egg** somewhere in the app. Whoever finds it first is our hero/ine!

---
# try also 'default' to start simple
theme: default
fonts:
  sans: Avenir Next
  mono: Fira Code
  provider: Google
highlighter: shiki
title: Hack the newsroom: How data-driven journalism is changing the news
download: 'https://antfu.me/talks/2021-04-29'
info: |
  ## Hack the newsroom: How data-driven journalism is changing the news
  Author: Rui Barros
# persist drawings in exports and build
drawings:
  persist: false
---

<h1>💻 Hack the newsroom</h1>
<h2>How data-driven journalism is changing the news</h2>

<div class="uppercase text-sm tracking-widest mt-8">
Rui Barros
</div>

<div class="abs-bl mx-14 my-12 flex">
  <img src="https://www.datascienceportugal.com/wp-content/uploads/2018/08/LogoDSPT_Grey-300x225.png" class="w-12">
  <div class="ml-3 flex flex-col text-left">
    <div>DSPT#97</div>
    <div class="text-sm opacity-50">July 28, 2022</div>
  </div>
</div>

---
layout: 'intro'
---

# Rui Barros

<div class="leading-8 opacity-80">
Data journalist at PÚBLICO.<br>
R lover turned into a web developer involuntarily.<br>
The guy in the newsroom that makes ✨ I N T E R A C T I V E ✨ things on the website.<br>
</div>

<div class="my-10 grid grid-cols-[40px,1fr] w-min gap-y-4">
  <ri-github-line class="opacity-50"/>
  <div><a href="https://github.com/ruimgbarros" target="_blank">ruimgbarros</a></div>
  <ri-twitter-line class="opacity-50"/>
  <div><a href="https://twitter.com/rui_barros17" target="_blank">rui_barros17</a></div>
  <ri-user-3-line class="opacity-50"/>
  <div><a href="https://ruimgbarros.com/" target="_blank">ruimgbarros.com</a></div>
</div>

<img src="https://ruimgbarros.com/img/rui_barros.jpg" class="rounded-full w-40 abs-tr mt-16 mr-12"/>

---
layout: section
---

# What is data journalism?

<!--
I could simply say that is journalism made with data. But that would not add that much. 

I believe if I give you a little bit of context and some examples it would make my job easier.
-->

---
layout: section
---

<img src="https://ia600509.us.archive.org/BookReader/BookReaderPreview.php?id=precisionjournal00meye&subPrefix=precisionjournal00meye&itemPath=/5/items/precisionjournal00meye&server=ia600509.us.archive.org&page=leaf1&fail=preview&&scale=8&rotate=0" 
alt=""
class="mx-auto rounded-lg shadow-lg">
>

<!--
The concept that lead us to Data Journalism could be traced back to the idea of Precision Journalism.

In this book, Philip Meyer basically said to journalists: both science and journaoism are obcessed with the idea of truth.

In the book, he proposes that journalism starts to also follow some techniques used on social sciences.
-->

---
layout: section
---

<figure class="max-w-xl mx-auto">
  <img src="https://media.npr.org/assets/img/2012/10/30/univac1_custom-a8caca6b3bf6519d6d49676c135f0008e3441ff6.jpg" class="mx-auto w-screen" alt="">
  <figcaption class="mt-2 text-sm opacity-50">
    CBS uses, for the first time, a computer to predict the result of the presidential election in 1956.
  </figcaption>
</figure>

<!--
That lead us to what was back then called Computer Assiting reporting:

In 1956, for example, CBS used for the first time a computer to try to predict the result of the US presidential election. 

So the idea of using computer and the scientific method was already around the newsrooms. 

But there were some problems
-->

---
layout: image-left
image: https://i.guim.co.uk/img/media/c2a32990f3ec1ad099162df463b42af333eae940/0_287_2460_2548/master/2460.jpg?width=1010&quality=85&auto=format&fit=max&s=76f09a4d3d3e12d2850cf80cb51c3198
---

# What was stopping them?

<ul class="list">
  <li>💸 Computing power was expensive</li>
</ul>

<style>
.list {
  list-style: none;
  margin: 0;
}
.slidev-layout li {
  margin-left: 0em;
}
</style>

---
layout: image-left
image: https://i.guim.co.uk/img/media/c2a32990f3ec1ad099162df463b42af333eae940/0_287_2460_2548/master/2460.jpg?width=1010&quality=85&auto=format&fit=max&s=76f09a4d3d3e12d2850cf80cb51c3198
---

# What was stopping them?

<ul class="list">
  <li>💸 Computing power was expensive</li>
  <li>🤔 No one knew how to use it</li>
</ul>


<style>
.list {
  list-style: none;
  margin: 0;
}
.slidev-layout li {
  margin-left: 0em;
}
</style>

---
layout: image-left
image: https://i.guim.co.uk/img/media/c2a32990f3ec1ad099162df463b42af333eae940/0_287_2460_2548/master/2460.jpg?width=1010&quality=85&auto=format&fit=max&s=76f09a4d3d3e12d2850cf80cb51c3198
---

# What was stopping them?

<ul class="list">
  <li>💸 Computing power was expensive</li>
  <li>🤔 No one knew how to use it</li>
  <li>💾 There was not a lot of data around</li>
</ul>



<style>
.list {
  list-style: none;
  margin: 0;
}
.slidev-layout li {
  margin-left: 0em;
}
</style>


---
layout: cover
background: static/publico_newroom.jpg
---

# Can you guess what happened?

<!--
Computers got more powerful, less expensive and a common thing in the newsroom;

Tools became easier to use - so the entry point was lower

And the idea of open public data became more present across the globe
-->

---
layout: section
---

<img src="/static/question.png" class="mx-auto h-30 mb-10"/>

# So, what is data journalism?
---
layout: quote
---

# "(...) the new possibilities that open up when you combine the traditional <b>‘nose for news’</b> and ability to <b>tell a compelling story</b>, with the <b>sheer scale and range of digital information</b> now available"
Paul Bradshaw - [The Data Journalism Handbook](https://datajournalism.com/read/handbook/one)



---
layout: image-left
image: https://images.unsplash.com/photo-1623039405147-547794f92e9e?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1052&q=80
---

# The data journalism workflow

<ol class="list">
  <li>Get a topic, idea, hunch, leak ...</li>
  <li>Get the data</li>
  <li>Clean the data</li>
  <li><b>Interview the database</b></li>
  <li>Ask questions based on your data</li>
  <li><i>Maybe start again?</i></li>
  <li>Think how you can tell the story</li>
  <li>Publish</li>
</ol>

---
layout: cover
background: https://images.unsplash.com/photo-1605289982774-9a6fef564df8?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=928&q=80
---

# Covid-19 contracts
---
layout: image-left
image: https://images.rr.sapo.pt/portal_base_foto_ines_rocha375277c9_base.jpg
---

# Getting the data

* The portuguese government was publishing a weekly updated excel file with all public contracts made under Decreto-Lei n.º 10-A/2020...

---
layout: image-left
image: https://images.rr.sapo.pt/portal_base_foto_ines_rocha375277c9_base.jpg
---

# Getting the data

* The portuguese government was publishing a weekly updated excel file with all public contracts made under Decreto-Lei n.º 10-A/2020...
* ... but data was missing



---
layout: image-left
image: https://images.rr.sapo.pt/portal_base_foto_ines_rocha375277c9_base.jpg
---

# Getting the data

* We knew all the other contracts were being published on Portal BASE

---
layout: image-left
image: https://images.rr.sapo.pt/portal_base_foto_ines_rocha375277c9_base.jpg
---

# Getting the data

* We knew all the other contracts were being published on Portal BASE.
* But how could we get the data from there?

---
layout: image-left
image: static/scraper.jpg
---

# The scraper

* Started with around 30 keywords

---
layout: image-left
image:  static/scraper.jpg
---

# The scraper

* Started with around 30 keywords
* Analysing the contracts term-frequency, we ended up with 98 words connected with covid contracts.


---
layout: fact
---

# 15.437 
#### public contracts (after cleaning false positives)

---
layout: section
---

<div class="flex justify-center">
  <img src="/static/block.png" class="mx-4 h-30 mb-10"/>
  <img src="/static/block.png" class="mx-4 h-30 mb-10"/>
  <img src="/static/block.png" class="mx-4 h-30 mb-10"/>
</div>

# The classification problem

---
layout: section
---

<img src="/static/mara.png" class="mx-auto" style="height:40vh;"/>

---
layout: section
---

<img src="/static/manchete.png" class="mx-auto" style="height:30vh;"/>

---
layout: section
---

<a href="https://www.publico.pt/interactivo/gastos-covid-19#/" target="_blank" rel="noopener noreferrer">
<img src="/static/newsapp.png" class="mx-auto" style="height:30vh;"/>
</a>

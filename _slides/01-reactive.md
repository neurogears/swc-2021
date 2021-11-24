---
layout: slides
title: Reactive Programming
permalink: /slides/reactive/
---

<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<script type="text/template">

![Bonsai](../../assets/images/bonsai-lettering.svg)

### Reactive Programming
[neurogears.org/swc-2021](https://neurogears.org/swc-2021)
<table style="width: 100%;">
  <tr>
    <th style="vertical-align: middle; width: 50%; height: 100px; padding-left: 100px">
      <img alt="NeuroGEARS" src="../../assets/images/neurogears.svg"/>
    </th>
    <th style="vertical-align: middle; width: 50%; height: 100px; align: right">
      <img alt="SWC" src="../../assets/images/swc.png"/>
    </th>
  </tr>
</table>

---

### Neuroscience needs makers & hackers

On the nature of systems neuroscience tools:

* Accessible
<!-- .element: class="fragment" data-fragment-index="1" -->
<!-- Accessible both in the sense that everyone can use... (so many walks of life in neuroscience) -->
<!-- ... but also in the sense that they can be understood. (using a tool with understanding is transformative) -->
* Forward-thinking
<!-- .element: class="fragment" data-fragment-index="2" -->
<!--  We want our tools to push the bar of what we can measure... (vastly underpowered tools) -->
<!--  ... but equally importantly we want them to challenge and surprise us. (surprise is the basis of discovery) -->
* Versatile
<!-- .element: class="fragment" data-fragment-index="3" -->
<!--  We need to combine tools in all sorts of ways... (crazy neuro experiments) -->
<!--  ... but also be inclusive to modifications and new demands -->

---

![Devices compatible with Bonsai](../../assets/images/devices.jpg)

---

![Applications in Neuroscience](../../assets/images/bonsai-applications.svg)

</script>
</section>

<!-- Raw HTML for embedded iframe backgrounds -->
<section data-background="#000000">
    <section data-background-iframe="https://www.youtube.com/embed/jKB0d9vsfgA?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;loop=1&amp;start=108&amp;playlist=jKB0d9vsfgA&amp;showinfo=0&amp;rel=0&amp;html5=1">
      <table style="height: 20%; margin-top: 65%; margin-left: -78px;">
        <tr><th>.txt interactive digital performance</th></tr>
      </table>
    </section>
    <section data-background-iframe="https://www.youtube.com/embed/4q9mFkZ3J_g?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;loop=1&amp;playlist=4q9mFkZ3J_g&amp;showinfo=0&amp;rel=0&amp;html5=1">
      <table style="height: 20%; margin-top: 65%; margin-left: -78px;">
        <tr><th>Elena Dreosti, UCL</th></tr>
      </table>
    </section>
    <section data-background-iframe="https://www.youtube.com/embed/wwU6TzUJxNU?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;loop=1&amp;playlist=wwU6TzUJxNU&amp;showinfo=0&amp;rel=0&amp;html5=1">
      <table style="height: 20%; margin-top: 65%; margin-left: -78px;">
        <tr><th>Gonçalo Lopes, Kampff Lab</th></tr>
      </table>
    </section>
    <section data-background-iframe="https://www.youtube.com/embed/qXqAXgXJPmo?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;showinfo=0&amp;rel=0&amp;html5=1">
      <table style="height: 20%; margin-top: 65%; margin-left: -78px;">
        <tr><th>Lorenza Calcaterra, Kampff Lab</th></tr>
      </table>
    </section>
    <section data-background-iframe="https://www.youtube.com/embed/mJDV07ptQFk?start=40&amp;controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;showinfo=0&amp;rel=0&amp;html5=1">
      <table style="height: 20%; margin-top: 65%; margin-left: -78px;">
        <tr><th>George Dimitriadis, Kampff Lab</th></tr>
      </table>
    </section>
</section>

<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<script type="text/template">

![Bonsai Ecosystem](../../assets/images/bonsai-packages.svg)

</script>
</section>

<!-- Raw HTML for embedded iframe backgrounds -->
<section>
  <section>
    <h4>Real-time markerless pose estimation</h4>
    <img src="../../assets/images/bonsai-dlc.svg" alt="Bonsai-DeepLabCut" />
    <iframe src="https://www.youtube.com/embed/0aachcS0CUY?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;loop=1&amp;playlist=0aachcS0CUY&amp;showinfo=0&amp;rel=0&amp;html5=1" width="500px" height="300px"></iframe>
    <a href="https://github.com/bonsai-rx/deeplabcut/">github.com/bonsai-rx/deeplabcut</a>
  </section>
  <section>
    <h4>Interactive visual environments</h4>
    <img src="../../assets/images/bonsai-bonvision.svg" alt="BonVision" />
    <img src="https://bonvision.github.io/assets/Images/Demos/DemoAR_v3.gif" width="50%" alt="Augmented Reality in BonVision" />
    <a href="https://bonvision.github.io/">bonvision.github.io</a>
  </section>
  <section>
    <h4>Multi-animal tracking</h4>
    <img src="../../assets/images/bonsai-bonzeb.svg" alt="BonZeb" />
    <video data-autoplay src="https://github.com/ncguilbeault/BonZeb/raw/master/Videos/Supplemental%20video%206%20-%20Multi-animal%20tracking%20with%20OMR.mp4"></video>
    <a href="https://ncguilbeault.github.io/BonZeb/">ncguilbeault.github.io/BonZeb</a>
  </section>
</section>

<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<script type="text/template">

![Bonsai workflow editor](../../assets/images/editor.jpg)

---

<!-- .element: data-transition="default none" -->
#### A metaphor for observable sequences

<img alt="Nasa twitter account" src="../../assets/images/nasatwitter.jpg" width="400"/>

--

<!-- .element: data-transition="none" -->
#### A metaphor for observable sequences

<img alt="Webcam twitter account" src="../../assets/images/webcamtwitter.jpg" width="400"/>

---

<!-- .element: data-transition="default none" -->
![Workflow](../../assets/images/cameracapture.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/framepicker-marblecanvas.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](../../assets/images/graycam.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/graycam-marble.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](../../assets/images/framepicker-key.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/framepicker-marblecanvas.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](../../assets/images/framepicker-capture.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/cameracapture-marble.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-grayscale.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/grayscalefile.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-grayscale.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/grayscaletransform.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-sample.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/grayscalesample.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/saveimagesink.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-key.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/framepicker-marblecanvas.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/conditionkey.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: middle;" -->

---

<!-- .element: data-transition="default none" -->
##### Operator Categories

![Operator categories](../../assets/images/categories-simple.svg)
<!-- .element: style="padding: 30px; display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
##### Operator Categories

![Operator categories](../../assets/images/categories.svg)
<!-- .element: style="padding: 30px; display: inline-block; vertical-align: middle;" -->

---

###### Skip

![Skip](../../assets/images/skip.svg)

---

###### Take

![Take](../../assets/images/take.svg)

---

###### SkipUntil

![SkipUntil](../../assets/images/skipuntil.svg)

---

###### TakeUntil

![TakeUntil](../../assets/images/takeuntil.svg)

---

###### Delay

![Delay](../../assets/images/delay.svg)

---

###### DelaySubscription / SubscribeWhen

![DelaySubscription](../../assets/images/delaysubscription.svg)

---

###### Repeat

![Delay](../../assets/images/repeat.svg)

---

###### Zip

![Zip](../../assets/images/zip.svg)

---

###### CombineLatest

![CombineLatest](../../assets/images/combinelatest.svg)

---

###### WithLatestFrom

![WithLatestFrom](../../assets/images/withlatestfrom.svg)

</script>
</section>

<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<script type="text/template">

![Bonsai](../../assets/images/bonsai-lettering.svg)

### Questions?
[neurogears.org/swc-2021](https://neurogears.org/swc-2021)
<table style="width: 100%;">
  <tr>
    <th style="vertical-align: middle; width: 50%; height: 100px; padding-left: 100px">
      <img alt="NeuroGEARS" src="../../assets/images/neurogears.svg"/>
    </th>
    <th style="vertical-align: middle; width: 50%; height: 100px; align: right">
      <img alt="SWC" src="../../assets/images/swc.png"/>
    </th>
  </tr>
</table>

</script>
</section>
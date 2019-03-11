---
title: "Build: The Image Element"
module: topic-07
permalink: /topic-07/img-element/
categories: html
tags: elements, image
---

<div class="divider-heading"></div>


<table class="table numbered-steps">
  <thead>
  </thead>
  <tbody>
    <tr id="step-01">
      <th scope="row"><div>Step 1</div></th>
      <td>
        <h3>Declare the Image</h3>
        <p>The image element is an <i>empty element</i> that only requires a single tag: the <b>image tag</b>.</p>
        <div class="code-heading">
          <span class="html">HTML</span>
        </div>
{% highlight html %}
<img />
{% endhighlight %}
        <div class="img-caption">This step lets the browser know what element to expect.</div>
      </td>
    </tr>

    <tr id="step-02">
      <th scope="row"><div>Step 2</div></th>
      <td>
        <h3>Add the Source</h3>
        <p>The first attribute that we will need to consider is <code>src=""</code>. Within the double-quotes you will need to include a <b>URL source</b> to the location of the desired image.</p>

        <p>This will typically be a <b>relative URL</b> to a file stored on the same server as the web page, but can also be an <b>absolute URL</b> to an image anywhere on the Internet.</p>
        <div class="code-heading">
          <span class="html">HTML</span>
        </div>
{% highlight html %}
<img src="" />
{% endhighlight %}
        <div class="img-caption">Between the double-quotes will go the image's <b>relative</b> or <b>absolute</b> URL.</div>
      </td>
    </tr>

    <tr id="step-03">
      <th scope="row"><div>Step 3</div></th>
      <td>
        <h3>Add Alternative Text</h3>
        <p>Proper style and accessibility standards dictate that you must always include the <b>alternative text attribute</b>. It is required that you provide a detailed description, especially in the case where the image is necessary to understand the content of the page.</p>
        <div class="code-heading">
          <span class="html">HTML</span>
        </div>
{% highlight html %}
<img src="" alt="" />
{% endhighlight %}
        <div class="img-caption">Beteen the double-quotes will go a clear description of the image.</div>
      </td>
    </tr>

    <tr id="step-04">
      <th scope="row"><div>Step 4</div></th>
      <td>
        <h3>Add a Title</h3>
        <p>As with the alt text attribute, you should also get in the habit of always including a <b>title attribute</b>. Most browsers will display this text as a tooltip when a user hovers their mouse over am image.</p>
        <div class="code-heading">
          <span class="html">HTML</span>
        </div>
{% highlight html %}
<img src="" alt="" title="" />
{% endhighlight %}
        <div class="img-caption">Including a title will give your users more information about the image when hovering.</div>
      </td>
    </tr>

    <tr id="step-05">
      <th scope="row"><div>Step 5</div></th>
      <td>
        <h3>Set the Size</h3>
        <p></p>
        <div class="code-heading">
          <span class="html">HTML</span>
        </div>
{% highlight html %}
<img src="" alt="" title="" width="" height="" />
{% endhighlight %}
        <div class="img-caption">Caption</div>
      </td>
    </tr>

    <tr id="preview">
      <th scope="row"><div>Preview</div></th>
      <td>
        <h3>Preview</h3>
        <p>A full <b>image element</b> is a combination of tag, source, alt text, title, and size:</p>
        <div class="code-heading">
          <span class="html">HTML</span>
        </div>
{% highlight html %}
<img src="./images/octocat-wave.gif" alt="animated GitHub Octocat logo, waving with a tentacle" title="Join Us at GitHub.com!" width="200" height="150" />
{% endhighlight %}
        <div class="code-heading">
          <span class="preview">Preview</span>
        </div>
        <div class="preview">
          <img src="../img/octocat-wave.gif" alt="animated GitHub Octocat logo, waving with a tentacle" title="Join Us at GitHub.com!" width="200" height="150" style="margin-left: 0;"/>
        </div>
      </td>
    </tr>
  </tbody>
</table>

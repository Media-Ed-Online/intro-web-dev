---
title: "Build: The Table Element"
module: topic-06
permalink: /topic-06/table-build-element/
categories: html
tags: element, table
---

<div class="divider-heading"></div>


<table class="table numbered-steps">
  <thead>
  </thead>
  <tbody>
    <tr id="step-01">
      <th scope="row"><div>Step 1</div></th>
      <td>
        <h3>Declare the Table</h3>
        <p>We declare a <b>table</b> using the <code>&lt;table&gt;...&lt;/table&gt;</code> element. All the content of that table lives within those tags.</p>
        <div class="code-heading">
          <span class="html">HTML</span>
        </div>
{% highlight html %}
<table>

</table>
{% endhighlight %}
        <div class="img-caption">The beginnings of a 3x2 table.</div>
      </td>
    </tr>

    <tr id="step-02">
      <th scope="row"><div>Step 2</div></th>
      <td>
        <h3>Add Rows</h3>
        <p>The <b>table rows</b> are created using the <code>&lt;tr&gt;...&lt;/tr&gt;</code> element. Inside of a table row lives the individual cells (equal to the number of columns), each referenced using a set of <code>&lt;td&gt;</code> tags.</p>
        <div class="code-heading">
          <span class="html">HTML</span>
        </div>
{% highlight html %}
<table>
  <tr>
    <!-- Row 1 -->
  </tr>

  <tr>
    <!-- Row 2 -->
  </tr>

  <tr>
    <!-- Row 3 -->
  </tr>
</table>
{% endhighlight %}
        <div class="img-caption">This table has 3 rows made with sets of <code>&lt;tr&gt;</code> tags.</div>
      </td>
    </tr>

    <tr id="step-03">
      <th scope="row"><div>Step 3</div></th>
      <td>
        <h3>Add Data</h3>
        <p>The <b>table data</b> is contained in cells, which is represented using a <code>&lt;td&gt;...&lt;/td&gt;</code> element.</p>
        <div class="code-heading">
          <span class="html">HTML</span>
        </div>
{% highlight html %}
<table>
  <tr>
    <!-- Row 1 -->
    <td></td>
    <td></td>
  </tr>

  <tr>
    <!-- Row 2 -->
    <td></td>
    <td></td>
  </tr>

  <tr>
    <!-- Row 3 -->
    <td></td>
    <td></td>
  </tr>
</table>
{% endhighlight %}
        <div class="img-caption">This table has 2 colums and 3 rows, so we need 4 cells made with <code>&lt;td&gt;</code> elements.</div>
      </td>
    </tr>

    <tr id="step-04">
      <th scope="row"><div>Step 4</div></th>
      <td>
        <h3>Add Headings</h3>
        <p>The <b>table data</b> is contained in cells, which is represented using a <code>&lt;td&gt;...&lt;/td&gt;</code> element.</p>
        <div class="code-heading">
          <span class="html">HTML</span>
        </div>
{% highlight html %}
<table>
  <tr>
    <!-- Row 1 -->
    <th></th>
    <th scope="col">Column A</th>
  </tr>

  <tr>
    <!-- Row 2 -->
    <th scope="row">Row 1</th>
    <td>Cell A1</td>
  </tr>

  <tr>
    <!-- Row 3 -->
    <th scope="row">Row 2</th>
    <td>Cell A2</td>
  </tr>
</table>
{% endhighlight %}
        <div class="img-caption">This table has 2 colums, so we need 4 cells made with <code>&lt;td&gt;</code> elements.</div>
      </td>
    </tr>

    <tr id="preview">
      <th scope="row"><div>Preview</div></th>
      <td>
        <h3>Preview</h3>
        <p>A full table element is a combination of columns and rows (both delineated by headings), and cells:</p>
        <div class="code-heading">
          <span class="preview">Preview</span>
        </div>
        <div class="preview">
          <table class="table-bordered" style="width: 200px; margin: 40px auto;">
            <tr>
              <!-- Row 1 -->
              <th></th>
              <th scope="col">Column A</th>
            </tr>

            <tr>
              <!-- Row 2 -->
              <th scope="row">Row 1</th>
              <td>Cell A1</td>
            </tr>

            <tr>
              <!-- Row 3 -->
              <th scope="row">Row 2</th>
              <td>Cell A2</td>
            </tr>
          </table>
        </div>
      </td>
    </tr>
  </tbody>
</table>

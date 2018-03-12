---
layout: page
title: About
permalink: /about/
---
<div class="man-title">
  Welcome to my Blog
</div>
<div class="manual manual-title">
  Info
  </div>
<p>  <div class="manual-content">

      - Create a .markdown file inside <code class="highlighter-rouge">_posts</code> folder.<br />
      - Name the file according to the format YY-MM-DD-[short name for your post].<br />
      &nbsp;&nbsp;&nbsp;<code>2016-03-30-i-love-design.markdown</code><br />
      - Write the <a href="jekyll">Front Matter</a> and content in the file.<br><br>
      <div class="example">

        <div class="highlight">
        <pre>
          ---
          Name: James Shelley
          Age:  21
          D.O.B: 31/05/1996
          categories: String | Array of Strings<span class="hint"> Category / Categories </span>
          ---
        </pre>
        </div>

      </div>

</p>
</div>
<p><br /></p>

  <div class="manual manual-title">
  Create Pages
  </div>
<p>  <div class="manual-content">

      - Create a .md file in the root directory.<br />
      - Name the file with the desired page link name.<br />
        &nbsp;&nbsp;&nbsp;<code>about.md</code><br />
          &nbsp;&nbsp;&nbsp;<code>design.md</code><br />
      - Write the <a href="jekyll">Front Matter</a> and content in the file.<br><br>
      <div class="highlight">


        <pre>
          ---
          layout: page
          title: String <span class="hint">Title of the webpage</span>
          permalink: / String / <span class="hint">Permalink for the webpage</span>
          tagline: String <span class="hint">Optional DevJournal Feature : Tagline for the page</span>
          ---
      </pre><br />
    </div><br>
      <div class="highlight">

        <pre>
        ---
        layout: page
        title:  "Science"
        permalink:   /science/
        tagline : "Humanity is overrated."
        ---
      </pre>
      </div>


  </div>
</p>

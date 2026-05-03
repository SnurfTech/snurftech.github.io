---
layout: page
title: Lemon
description: A fully edible lemon in vanilla Minecraft!
nav-menu: false
show_tile: false
---

<!-- Main -->
<div id="main" class="alt">
	
<!-- One -->
<section id="one">
	<div class="inner">

<!-- Content -->
<div id="output">Loading ...</div>

<script>
  // URL of the Markdown file
  const markdownUrl = 'https://raw.githubusercontent.com/{{ site.author }}/awesome-command-blocks/refs/heads/main/command-block-combinations/lemon.md';

  // Fetch the Markdown file from the URL
  fetch(markdownUrl)
    .then(response => {
      if (!response.ok) {
        throw new Error(`Failed to fetch Markdown file: ${response.statusText}`);
      }
      return response.text();
    })
    .then(markdown => {
      // Convert Markdown to HTML using Marked.js
      const htmlContent = marked.parse(markdown);

      // Inject the converted HTML into the output div
      document.getElementById('output').innerHTML = htmlContent;
    })
    .catch(error => {
      // Display an error message if something goes wrong
      document.getElementById('output').textContent = `Error: ${error.message}`;
    });
</script>
</div>
</section>

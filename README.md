Int Dev Best Practice
===============

A basic guide to writing consistent HTML
<h2>General Best Practice</h2>
<ul><li> <a href="http://www.bbc.co.uk/guidelines/futuremedia/technical/semantic_markup.shtml" class="external text" rel="nofollow">Markup should be semantic</a>, well formed and generally valid. 
</li><li> Aside from vendor prefixes and IE specific hacks, CSS should be valid
</li><li> Ensure a <a href="http://webaim.org/resources/contrastchecker/" class="external text" rel="nofollow">suitable contrast between background and foreground colours</a> 
</li><li> Content prints well or a <a href="http://www.webdesignerdepot.com/2010/01/10-tips-for-better-print-style-sheets/" class="external text" rel="nofollow">print style sheet is provided</a>
</li><li> All images have an alt attribute. Empty or otherwise
</li><li> Test your site with JavaScript disabled
</li><li> HTML reliant on JavaScript should be added as an enhancement. i.e added to the page using js.
</li><li> Don’t use inline styling
</li><li> Provide suitable fallback content for &lt;object /&gt;,&lt;embed /&gt;
</li><li> Provide skiplinks - link to content, link to top etc
</li></ul>
<h2>CSS Best Practice</h2>
<ul><li> Avoid styling elements using IDs. use classes instead
</li><li> <a href="http://css-tricks.com/semantic-class-names" class="external text" rel="nofollow">Class names should be descriptive of the content and not related to presentation</a>
</li><li> Ensure CSS is structured in a modular way for easy reuse
</li><li> Avoiding adding unnecessary descendent selectors. e.g.  .content .componentName .list li is less efficient than .componentName li</li>
<li> Avoid attaching tags to CSS classes e.g ul.nav is less efficient than .nav
</li><li> Avoid adding more widths than necessary. Components shouldn’t need a width as they will get this from their column container.
</li><li> <a href="http://www.456bereastreet.com/archive/201112/the_difference_between_widthauto_and_width100/" class="external text" rel="nofollow">Use width: auto over width: 100% when resetting widths of block level elements.</a>
</li></ul>
<h2>Validators/Accessibility Tools</h2>
<ul><li> <a href="http://jigsaw.w3.org/css-validator/" class="external text" rel="nofollow">W3C CSS Validation Service</a>
</li><li> <a href="http://jigsaw.w3.org/css-validator/" class="external text" rel="nofollow">CSS validator</a>
</li><li> Accessibility - <a href="http://www.cynthiasays.com/" class="external text" rel="nofollow">Cynthia Says Portal</a>
</li><li> Accessibility - <a href="http://wave.webaim.org/" class="external text" rel="nofollow">WAVE</a>
</li></ul>

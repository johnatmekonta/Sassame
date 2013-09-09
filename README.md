Sassame
=======

Typography
==========

Font: 'Roboto' served from Google Fonts. Regular body weight is actually the 'light, 300' font. Bold text uses 'regular, 400'.

Default head tags have 0 margin

Buttons
=======

Default button is grey.
Classes of .primary, .secondary for featured styling.
.animated-link--left, animated padding transition from left on hover
.animated-link--right, animated padding transition from right on hover
.inline, used with either .animated-link--xx classes to make button inline block and not 100% width.

Layout
======

At its core Sassame is using a 12 column grid based on Neat from the Bourbon framework.

Almost all content regions should be wrapped in an element (div, article, aside or whatever) with a class .panel - this class adds a background, and padding to correctly layout the content.

In addition to .panel - use the following to get layout:

<div class="panel panel__leader">
<p>.panel__leader</p>
</div>

<div class="panel panel__leader--preview">
<p>.panel__leader--preview</p>
</div>

<div class="panel__sub-wrapper--1col" style="border: 1px dotted black;">
<p>Wrapper: .panel__sub-wrapper--1col</p>
<div class="panel panel__sub">

<p>.panel__sub</p>
</div>
<div class="panel panel__sub">
<p>.panel__sub</p>
</div>
</div>

<div class="panel__sub-wrapper--grid" style="border: 1px dotted black;">
<p>Wrapper: .panel__sub-wrapper--grid</p>
<div class="panel panel__sub">
<p>.panel__sub 1</p>
</div>
<div class="panel panel__sub">
<p>.panel__sub 2</p>
</div>
</div>

<div class="article-col panel">
<p>.article-col</p>
</div>
<div class="aside-col panel">
<p>.aside-col</p>
</div>

<div>
<hr />
</div>

<div class="panel">
<h1>Colours</h1>
<p>Each department has it's own colour. Mostly identified with an additional class .c_[dept_name] to assign specific colour stylings.<br />
.c_it<br />
.c_ops<br />
.c_finance<br />
.c_creative<br />
.c_rd<br />
.c_sales<br />
.c_primary<br />
.c_secondary<br />
</p>
<p>In conjunction with .clr-block will assign a background colour of that department to the element. OR .clr-text, for text colour of that department.</p>
<p><span class="c_it clr-block">IT</span> <span class="c_it clr-text">IT</span></p>
<p><span class="c_ops clr-block">Operations</span> <span class="c_ops clr-text">Operations</span></p>
<p><span class="c_finance clr-block">Finance</span> <span class="c_finance clr-text">Finance</span></p>
<p><span class="c_creative clr-block">Creative</span> <span class="c_creative clr-text">Creative</span></p>
<p><span class="c_rd clr-block">R&amp;D</span> <span class="c_rd clr-text">R&amp;D</span></p>
<p><span class="c_sales clr-block">Sales</span> <span class="c_sales clr-text">Sales</span></p>
<p><span class="c_primary clr-block">Primary</span> <span class="c_primary clr-text">Primary</span></p>
<p><span class="c_secondary clr-block">Secondary</span> <span class="c_secondary clr-text">Secondary</span></p>
</div><!--/colours-->

<div class="media panel">
<p><strong>Media</strong> .media</p>
<div class="img panel"><p>.img</p></div>
<div class="bd"><p>.bd</p></div>
</div>
<div class="media panel">
<p><strong>Media</strong> .media</p>
<div class="imgExt panel"><p>.imgExt</p></div>
<div class="bd"><p>.bd</p></div>
</div>
<div class="media panel">
<p><strong>Media</strong> .media</p>
<div class="img panel"><p>.img</p></div>
<div class="bd"><p>.bd</p>

<div class="media panel">
<p><strong>Nested Media</strong></p>
<div class="img panel"><p>.img</p></div>
<div class="bd"><p>.bd</p></div>
</div>
<div class="media panel">
<p><strong>Nested Media</strong></p>
<div class="imgExt panel"><p>.imgExt</p></div>
<div class="bd"><p>.bd</p></div>
</div>
</div>
</div>


<div class="panel">

<ul class="ui-list">
<li>.ui-list</li>
<li>Class goes on the ul</li>
</ul>

<ul class="ui-list">
<li>.ui-list</li>
<li>Class goes on the ul</li>
<li><span class="action1 panel">.action1</span> <span class="label">.label</span><span class="action2 panel">.action2</span></li>
</ul>

<ul class="ui-list ui-list--yourbookmarks">
<li>.ui-list .ui-list--yourbookmarks</li>
<li>Class goes on the ul</li>
<li><span class="action1 panel">.action1</span> <span class="label">.label</span><span class="action2 panel">.action2</span></li>
</ul>


<ul class="ui-list ui-list--popular">
<li>.ui-list .ui-list--yourbookmarks</li>
<li>Class goes on the ul</li>
<li><span class="action1 panel">.action1</span> <span class="label">.label</span><span class="action2 panel">.action2</span></li>
</ul>


<ul class="unstyled">
<li class="media resource__item"><a href="" class="img resource--link">&lt;a class="resource--link"&gt;</a> 
<div class="bd resource--notes">
<p>&lt;div class="bd resource--notes"&gt;&lt;p&gt;our notes</p>
</div></li>
</ul>

</div>


</div>
</section>




<footer>
<div class="outer">

<div class="col footer__latest">
<h4>Latest Entries</h4>
<ul class="unstyled">
<li>Some Entry Name
<small>by: James Green: 14 July</small>
</li>

<li>Another Post
<small>by:Edward Scott-Finnigan: 3 August</small>
</li>

<li>Gro Facts
<small>by Elizabeth: 24 January</small>
</li>
</ul>
</div><!--/latest entries-->

<div class="col footer__events">
<h4>Events</h4>
<ul class="unstyled">
<li>Baby Show New York
<i>4 July > 12 July</i>
</li>
<li>Gro Annual Bun fight
<i>1 August</i>
</li>
<li>Ed's Birthday
<i>4 September</i>
</li>
</ul>
</div><!--/events-->

<div class="col footer__shared">
<h4>Recently Shared</h4>
<ul class="unstyled">
<li>Pictures of Cats</li>
<li>Awesome YouTube Videos</li>
<li>Gro in Media Profile</li>
<li>Gotta hear this podcast ... </li>
</ul>
</div><!--/shared-->

<div class="col footer__offices">
<h4>Locations</h4>
<ul class="unstyled">
<li>Exeter: <i>9.30am</i></li>
<li>Australia: <i>6.30pm</i></li>
<li>China: <i>2.30pm</i></li>
<li>New York: <i>5.00am</i></li>
</ul>
</div><!--/offices-->
</div><!--/outer-->
</footer>
</div>
<!-- JavaScript -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>
<script src='js/vendor/modernizr-2.6.2-min.js'></script>

</body>
</html>


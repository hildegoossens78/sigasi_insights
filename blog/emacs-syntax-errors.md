---
title: "Emacs Syntax errors"
layout: page 
pager: true
author: philippe.faes (Sigasi)
date: 2011-06-01
tags: 
  - Emacs
  - VHDL
---
<div class="content">
<p>Here is a new example of <a href="http://www.sigasi.com/content/why-emacs-so-great-and-why-we-want-beat-it">Sigasi is better than Emacs</a>: syntax checking.</p>	<p>In Emacs <span class="caps">VHDL</span> mode, there is no built-in syntax checker. This design decision was perfectly reasonable in the early 1990's, when the Emacs <span class="caps">VHDL</span> mode was created. Because of the processing power and the memory available at that time, compilation was a slow process which was best handled by specialized tools. So Emacs uses a simulator (like ModelSim) to check the syntax of <span class="caps">VHDL</span> code.</p>	<h2>Batch compilation</h2>	<p>Let's assume you have installed ModelSim and configured Emacs accordingly (I won't go into that). Syntax checking would go something like this:</p>	<ul><li>Write some interesting code</li>		<li>Trigger a ModelSim build (usually, this can be done with a key combination, like <span class="caps">CTRL</span>-C, <span class="caps">CTRL</span>-K)</li>		<li>The list of errors shows up at the bottom of your screen. For each error:	<ul><li>Go to the error location in the code (key combination: <span class="caps">CTRL</span>-X `)</li>		<li>Read the context; you have been typing for a while, so you need to think a bit before you figure out the problem.</li>		<li>Fix the error</li>	</ul></li>	</ul><h2>Type time compilation</h2>	<p>Modern development environment, including Sigasi <span class="caps">HDT</span> 2.0 have type time compilation. A first class of errors (syntax errors and undefined identifiers) will be marked <em>as you type</em>. More complex errors and linter warnings take longer to calculate, so these checks are performed, much like Emacs does it, only when the user requests them.</p>	<ul><li>Write some interesting code</li>		<li>Whenever you type a <span class="caps">VHDL</span> syntax error, this is marked on your editor screen.</li>		<li>You still remember what you were typing two seconds ago, so you can fix the error easily.</li>	</ul><p><span class="inline inline-center"><img src="http://www.sigasi.com/sites/www.sigasi.com/files/images/EclipseScreenSnapz003_1.png" alt="Type-time error checking in Sigasi HDT 2.0" title="Type-time error checking in Sigasi HDT 2.0" class="image image-_original " width="325" height="106"/><span class="caption"><strong>Type-time error checking in Sigasi <span class="caps">HDT</span> 2.0</strong></span></span></p>	<h2>Feedback loop and word processors</h2>	<p>The difference between the ways of working lies in the shorter feedback loop. As soon as you type an error, you get a chance to fix it. This takes less time and effort because you do not need to make a mental context switch. Engineers understand the positive implications of a "shorter feedback loop". </p>	<p>But even my kid's kindergarten teacher (who is smart, but not very technological) remembers older word processing software. This is how it used to work: First, you write a letter. Then, you run the spell checker. Each time you encounter misspelled word, you have to read the whole sentence to figure out what you wanted to say. Modern word processors and editors provide type-time spell checking: each time you write an errr [<a href="http://en.wikipedia.org/wiki/Sic" class="elf-external elf-icon">sic</a>] the word is underlined in red. You fix it immediately. The result is that your letter is finished sooner with less spelling misstakes. Instant feedback is everywhere. Even my web browser is correcting me as I'm typing this blog post!</p>	<p>If professional writers use <strong>instant feedback</strong> technology to help them do their jobs, then why don't hardware design engineers? </p>	<p>What do you think? Talk to me in the comments section, below. Don't forget to turn on your spell checker!</p>  <div id="book-navigation-1518" class="book-navigation">            <div class="page-links clear-block">              <a href="/content/engineers-are-smart-enough-change-editors" class="page-previous" title="Go to previous page">&#8249; Engineers are smart enough to change editors</a>                    <a href="/better-emacs-vhdl-mode" class="page-up" title="Go to parent page">up</a>                    <a href="/content/no-vhdl-rename-emacs-vhdl-mode" class="page-next" title="Go to next page">No VHDL Rename in Emacs VHDL mode &#8250;</a>          </div>      </div>  </div>

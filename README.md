---


---

<h2 id="to-get-total-page-count">To get total page count</h2>
<pre class=" language-javascript"><code class="prism  language-javascript"><span class="token keyword">this</span><span class="token punctuation">.</span>rawValue <span class="token operator">=</span> xfa<span class="token punctuation">.</span>layout<span class="token punctuation">.</span><span class="token function">pageCount</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<h2 id="to-get-current-page-number">To get current page number</h2>
<pre class=" language-javascript"><code class="prism  language-javascript"><span class="token keyword">if</span><span class="token punctuation">(</span>xfa<span class="token punctuation">.</span>layout<span class="token punctuation">.</span><span class="token function">page</span><span class="token punctuation">(</span><span class="token keyword">this</span><span class="token punctuation">)</span> <span class="token operator">==</span> <span class="token number">1</span><span class="token punctuation">)</span><span class="token punctuation">{</span>
<span class="token comment">// do some stuff on first page</span>
<span class="token punctuation">}</span><span class="token keyword">else</span><span class="token punctuation">{</span>
<span class="token comment">// do some magical on other pages</span>
<span class="token punctuation">}</span>
</code></pre>
<blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.</p>
</blockquote>


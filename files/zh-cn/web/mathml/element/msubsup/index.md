---
title: <msubsup>
slug: Web/MathML/Element/msubsup
tags:
  - MathML
  - MathML 参考
translation_of: Web/MathML/Element/msubsup
---
<div>{{MathMLRef}}</div>

<p>MathML <code>&lt;msubsup&gt;</code> 元素用于为表达式同时附加上角标和下角标。</p>

<p>它的语法如下：<code>&lt;msubsup&gt; base subscript superscript &lt;/msubsup&gt;</code>。</p>

<h2 id="属性">属性</h2>

<dl>
 <dt><code>class</code>、<code>id</code>、<code>style</code></dt>
 <dd>供<a href="/zh-CN/docs/CSS">样式</a>使用。</dd>
 <dt><code>href</code></dt>
 <dd>Used to set a hyperlink to a specified URI.</dd>
 <dt><code>mathbackground</code></dt>
 <dd>背景颜色。支持 <code>#rgb</code>、<code>#rrggbb</code> 和 <a href="/zh-CN/docs/CSS/color_value#Color_Keywords">HTML 颜色名称</a>。</dd>
 <dt><code>mathcolor</code></dt>
 <dd>文本颜色。支持 <code>#rgb</code>、<code>#rrggbb</code> 和 <a href="/zh-CN/docs/CSS/color_value#Color_Keywords">HTML 颜色名称</a>。</dd>
 <dt><code>subscriptshift</code> {{deprecated_inline}}</dt>
 <dd>The minimum space by which to shift the subscript below the baseline of the expression, as a <a href="/en-US/docs/MathML/Attributes/Values#Lengths">length value.</a><br>
 This attribute is deprecated and will be removed in the future.</dd>
 <dt><code>superscriptshift</code> {{deprecated_inline}}</dt>
 <dd>The minimum space by which to shift the superscript above the baseline of the expression, as a <a href="/en-US/docs/MathML/Attributes/Values#Lengths">length value.</a><br>
 This attribute is deprecated and will be removed in the future.</dd>
</dl>

<h2 id="示例">示例</h2>

<p>示例渲染结果：</p>

<img alt="x1" src="msubsup.png">

<p>当前浏览器中的渲染结果：<math displaystyle="true"> <msubsup><mo>∫</mo> <mn> 0 </mn> <mn> 1 </mn> </msubsup> </math></p>

<pre class="brush: html">&lt;math displaystyle="true"&gt;

  &lt;msubsup&gt;
    &lt;mo&gt; &amp;#x222B;&lt;!-- 积分符号 --&gt; &lt;/mo&gt;
    &lt;mn&gt; 0 &lt;/mn&gt;
    &lt;mn&gt; 1 &lt;/mn&gt;
  &lt;/msubsup&gt;

&lt;/math&gt;
</pre>

<h2 id="规范">规范</h2>

{{Specifications}}

<h2 id="浏览器兼容性">浏览器兼容性</h2>



<p>{{Compat}}</p>

<h2 id="参见">参见</h2>

<ul>
 <li>{{ MathMLElement("msub") }}（上标）</li>
 <li>{{ MathMLElement("msup") }}（下标）</li>
 <li>{{ MathMLElement("mmultiscripts") }}（Prescript 和 tensor indice）</li>
</ul>
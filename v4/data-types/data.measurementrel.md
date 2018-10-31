---
layout: sidebar
sidebar: s1
version: "v4"
title: "data.MEASUREMENTREL"
---
<div class="macroSpec">
   <h3 id="data.MEASUREMENTREL">data.MEASUREMENTREL</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">Measurement expressed in real-world (e.g., centimeters, millimeters, inches, points,
            picas, or pixels) or virtual units (vu). 'vu' is the default value. Unlike
            data.MEASUREMENTABS, in which only positive values are allowed, both positive and
            negative
            values are permitted.
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Module</strong></td>
         <td class="wovenodd-col2">MEI</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Used by</strong></td>
         <td class="wovenodd-col2">
            <div class="parent"><a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.distances.html">att.distances</a> (@dynam.dist), <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.lyricstyle.html">att.lyricStyle</a> (@lyric.align), <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.spacing.html">att.spacing</a> (@spacing.staff), <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.visualoffset.ho.html">att.visualOffset.ho</a> (@ho), <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.visualoffset.vo.html">att.visualOffset.vo</a> (@vo), <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.visualoffset2.ho.html">att.visualOffset2.ho</a> (@startho), <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.visualoffset2.vo.html">att.visualOffset2.vo</a> (@startvo), <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.staffdef.vis.html">att.staffDef.vis</a> (@spacing)
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Declaration</strong></td>
         <td class="wovenodd-col2">
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;content&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;rng:data <span class="attribute">type=</span><span class="attributevalue">"token"</span>&gt;</span>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;rng:param <span class="attribute">name=</span><span class="attributevalue">"pattern"</span>&gt;</span><div class="indent4 indent">(\+|-)?\d+(\.\d+)?(cm|mm|in|pt|pc|px|vu)?</div><span data-indentation="3" class="element">&lt;/rng:param&gt;</span></div>
                        <span data-indentation="2" class="element">&lt;/rng:data&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/content&gt;</span></div></code></div>
         </td>
      </tr>
   </table>
</div>
---
layout: sidebar
sidebar: s1
version: "v3"
title: "att.slashcount"
---
<div class="classSpec att">
   <h3 id="att.slashcount">att.slashcount</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">Attributes for recording the number of slashes that accompany a feature.</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Module</strong></td>
         <td class="wovenodd-col2">MEI.shared</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Members</strong></td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/ftrem.html">fTrem</a><span> (via <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.ftrem.vis.html">att.fTrem.vis</a>)</span></div>
               <div><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/mensur.html">mensur</a>, <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/mensuration.html">mensuration</a><span> (via <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.mensur.log.html">att.mensur.log</a>)</span></div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Attributes</strong></td>
         <td class="wovenodd-col2">
            <div class="attributeDef"><span class="attribute"><strong>@slash</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Indicates the number of slashes present.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.slash.html">data.SLASH</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.slashcount.html">att.slashcount</a></span></div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Declaration</strong></td>
         <td class="wovenodd-col2">
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"slash"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Indicates the number of slashes present.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;datatype <span class="attribute">maxOccurs=</span><span class="attributevalue">"1"</span> <span class="attribute">minOccurs=</span><span class="attributevalue">"1"</span>&gt;</span>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;rng:ref
                              
                              <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.slash.html">data.SLASH</a>"</span></span>
                              /&gt;</span></div>
                        <span data-indentation="2" class="element">&lt;/datatype&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/attDef&gt;</span></div></code></div>
         </td>
      </tr>
   </table>
</div>
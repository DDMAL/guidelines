---
layout: sidebar
sidebar: s1
version: "dev"
title: "att.scoreDef.log.cmn"
---
<div class="classSpec att">
   <h3 id="att.scoreDef.log.cmn">att.scoreDef.log.cmn</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">Logical domain attributes.</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Module</strong></td>
         <td class="wovenodd-col2">MEI.cmn</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Members</strong></td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/scoredef.html">scoreDef</a><span> (via <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.scoredef.log.html">att.scoreDef.log</a>)</span></div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Attributes</strong></td>
         <td class="wovenodd-col2">
            <div class="attributeDef"><span class="attribute"><strong>@beam.group</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Provides an example of how automated beaming (including secondary beams) is to be
                  performed.</span>
               Value is plain text.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.beaming.log.html">att.beaming.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@beam.rests</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Indicates whether automatically-drawn beams should include rests shorter than a
                  quarter note duration.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.boolean.html">data.BOOLEAN</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.beaming.log.html">att.beaming.log</a></span></div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Declaration</strong></td>
         <td class="wovenodd-col2">
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classes&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.beaming.log.html">att.beaming.log</a>"</span></span>/&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/classes&gt;</span></div></code></div>
         </td>
      </tr>
   </table>
</div>
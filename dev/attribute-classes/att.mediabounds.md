---
layout: sidebar
sidebar: s1
version: "dev"
title: "att.mediaBounds"
---
<div class="classSpec att">
   <h3 id="att.mediaBounds">att.mediaBounds</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">Attributes that establish the boundaries of a media object.</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Module</strong></td>
         <td class="wovenodd-col2">MEI.shared</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Members</strong></td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/clip.html">clip</a>, <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/recording.html">recording</a> (direct members of att.mediaBounds)
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Attributes</strong></td>
         <td class="wovenodd-col2">
            <div class="attributeDef"><span class="attribute"><strong>@begin</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Specifies a point where the relevant content begins. A numerical value must be less
                  and a time value must be earlier than that given by the end attribute.</span>
               Value is plain text.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.mediabounds.html">att.mediaBounds</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@betype</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Type of values used in the begin/end attributes. The begin and end attributes can
                  only
                  be interpreted meaningfully in conjunction with this attribute.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.betype.html">data.BETYPE</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.mediabounds.html">att.mediaBounds</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@end</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Specifies a point where the relevant content ends. If not specified, the end of the
                  content is assumed to be the end point. A numerical value must be greater and a time
                  value
                  must be later than that given by the begin attribute.</span>
               Value is plain text.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.mediabounds.html">att.mediaBounds</a></span></div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Declaration</strong></td>
         <td class="wovenodd-col2">
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"begin"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Specifies a point where the relevant content begins. A numerical value must be less
                        and a time value must be earlier than that given by the end attribute.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;datatype&gt;</span>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;rng:text/&gt;</span></div>
                        <span data-indentation="2" class="element">&lt;/datatype&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/attDef&gt;</span></div></code></div>
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"end"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Specifies a point where the relevant content ends. If not specified, the end of the
                        content is assumed to be the end point. A numerical value must be greater and a time
                        value
                        must be later than that given by the begin attribute.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;datatype&gt;</span>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;rng:text/&gt;</span></div>
                        <span data-indentation="2" class="element">&lt;/datatype&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/attDef&gt;</span></div></code></div>
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"betype"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Type of values used in the begin/end attributes. The begin and end attributes can
                        only
                        be interpreted meaningfully in conjunction with this attribute.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;datatype&gt;</span>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;rng:ref
                              
                              <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.betype.html">data.BETYPE</a>"</span></span>
                              /&gt;</span></div>
                        <span data-indentation="2" class="element">&lt;/datatype&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/attDef&gt;</span></div></code></div>
         </td>
      </tr>
   </table>
</div>
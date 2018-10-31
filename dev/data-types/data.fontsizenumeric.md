---
layout: sidebar
sidebar: s1
version: "dev"
title: "data.FONTSIZENUMERIC"
---
<div class="macroSpec">
   <h3 id="data.FONTSIZENUMERIC">data.FONTSIZENUMERIC</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">Font size expressed as numbers; i.e. points or virtual units.</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Module</strong></td>
         <td class="wovenodd-col2">MEI</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Used by</strong></td>
         <td class="wovenodd-col2">
            <div class="parent"></div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Declaration</strong></td>
         <td class="wovenodd-col2">
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;content&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;rng:data <span class="attribute">type=</span><span class="attributevalue">"token"</span>&gt;</span>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;rng:param <span class="attribute">name=</span><span class="attributevalue">"pattern"</span>&gt;</span>\d*(\.\d+)?(pt|vu)<span data-indentation="3" class="element">&lt;/rng:param&gt;</span></div>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;rng:except&gt;</span>
                           
                           <div class="indent4 indent"><span data-indentation="4" class="comment">&lt;!-- disallow no-value or all-zero patterns --&gt;</span></div>
                           
                           <div class="indent4 indent"><span data-indentation="4" class="element">&lt;rng:choice&gt;</span>
                              
                              <div class="indent5 indent"><span data-indentation="5" class="element">&lt;rng:data <span class="attribute">type=</span><span class="attributevalue">"token"</span>&gt;</span>
                                 
                                 <div class="indent6 indent"><span data-indentation="6" class="element">&lt;rng:param <span class="attribute">name=</span><span class="attributevalue">"pattern"</span>&gt;</span>(pt|vu)<span data-indentation="6" class="element">&lt;/rng:param&gt;</span></div>
                                 <span data-indentation="5" class="element">&lt;/rng:data&gt;</span></div>
                              
                              <div class="indent5 indent"><span data-indentation="5" class="element">&lt;rng:data <span class="attribute">type=</span><span class="attributevalue">"token"</span>&gt;</span>
                                 
                                 <div class="indent6 indent"><span data-indentation="6" class="element">&lt;rng:param <span class="attribute">name=</span><span class="attributevalue">"pattern"</span>&gt;</span>0+(pt|vu)<span data-indentation="6" class="element">&lt;/rng:param&gt;</span></div>
                                 <span data-indentation="5" class="element">&lt;/rng:data&gt;</span></div>
                              
                              <div class="indent5 indent"><span data-indentation="5" class="element">&lt;rng:data <span class="attribute">type=</span><span class="attributevalue">"token"</span>&gt;</span>
                                 
                                 <div class="indent6 indent"><span data-indentation="6" class="element">&lt;rng:param <span class="attribute">name=</span><span class="attributevalue">"pattern"</span>&gt;</span>0+(\.0+)?(pt|vu)<span data-indentation="6" class="element">&lt;/rng:param&gt;</span></div>
                                 <span data-indentation="5" class="element">&lt;/rng:data&gt;</span></div>
                              
                              <div class="indent5 indent"><span data-indentation="5" class="element">&lt;rng:data <span class="attribute">type=</span><span class="attributevalue">"token"</span>&gt;</span>
                                 
                                 <div class="indent6 indent"><span data-indentation="6" class="element">&lt;rng:param <span class="attribute">name=</span><span class="attributevalue">"pattern"</span>&gt;</span>\.0+(pt|vu)<span data-indentation="6" class="element">&lt;/rng:param&gt;</span></div>
                                 <span data-indentation="5" class="element">&lt;/rng:data&gt;</span></div>
                              <span data-indentation="4" class="element">&lt;/rng:choice&gt;</span></div>
                           <span data-indentation="3" class="element">&lt;/rng:except&gt;</span></div>
                        <span data-indentation="2" class="element">&lt;/rng:data&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/content&gt;</span></div></code></div>
         </td>
      </tr>
   </table>
</div>
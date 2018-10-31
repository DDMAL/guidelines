---
layout: sidebar
sidebar: s1
version: "v4"
title: "data.MEASUREBEATOFFSET"
---
<div class="macroSpec">
   <h3 id="data.MEASUREBEATOFFSET">data.MEASUREBEATOFFSET</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">A count of measures plus a beat location, i.e., (\+|-)?[0-9]+m\+[0-9]+(\.?[0-9]*)?.
            The
            measure count is the number of barlines crossed by the event, while the beat location
            is a
            timestamp expressed as a beat with an optional fractional part. The measure number
            must be in
            the range of preceding measures to the number of remaining measures. A value with
            a positive
            measure number, such as "1m+3", indicates a point in the following measure, while
            a value with
            a negative measure number, such as "-1m+3", marks a point in the preceding measure.
            The beat
            number must be in the range from 0 to the numerator of the time signature plus 1.
            For example,
            in 6/8 the beat number must be within the range from 0 (the left barline) to 7 (the
            right
            barline). A value with a measure number of "0", such as "0m+2", indicates a point
            within the
            current measure.
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Module</strong></td>
         <td class="wovenodd-col2">MEI</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Used by</strong></td>
         <td class="wovenodd-col2">
            <div class="parent"><a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.origin.timestamp.logical.html">att.origin.timestamp.logical</a> (@origin.tstamp)
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Declaration</strong></td>
         <td class="wovenodd-col2">
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;content&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;rng:data <span class="attribute">type=</span><span class="attributevalue">"token"</span>&gt;</span>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;rng:param <span class="attribute">name=</span><span class="attributevalue">"pattern"</span>&gt;</span><div class="indent4 indent">(\+|-)?[0-9]+m\+[0-9]+(\.[0-9]*)?</div><span data-indentation="3" class="element">&lt;/rng:param&gt;</span></div>
                        <span data-indentation="2" class="element">&lt;/rng:data&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/content&gt;</span></div></code></div>
         </td>
      </tr>
   </table>
</div>
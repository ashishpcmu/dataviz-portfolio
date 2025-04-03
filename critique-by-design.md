| [home page](https://ashishpcmu.github.io/dataviz-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# State of Enterprise: California and the Rise of High-Revenue Employer Firms


## Step one: the visualization

Original Graph: Number of Employer Firms, by Firm Receipt Amount, by Race/Ethnicity (Nationwide and Statewide, 2023)

  <img src="original_graph.png" alt="Image" width="500">

Source: https://blackwealthdata.org/explore/business , based on U.S. Census and NSF ABS data

### Why I Selected This Visualization?

I chose this visualization because it attempts to tell a story about racial disparities in business ownership and financial scale — a crucial issue for equity and policy. The topic felt meaningful, but the chart’s current form made that story hard to access. It also uses a filter-heavy UI and bar layout that felt cluttered and difficult to interpret at a glance, making it a great candidate for critique and redesign.



## Step two: the critique

The seven-point scale (usefulness, completeness, perceptibility, truthfulness, intuitiveness, aesthetics, and engagement) was a highly effective framework for breaking down a visualization's technical effectiveness and emotional resonance. It forced me to think about the chart from multiple perspectives: not just what data is shown, but how accessible, truthful, and engaging that data actually is.

The Good Charts critique method — centered around contextual awareness and design execution, along with four guided reflections — is much more narrative-driven and user-centered. Rather than scoring against a rubric, you're encouraged to engage with the chart more like a human than a technician. It promotes creative thinking and emotional insight. It rncourages you to take the perspective of the audience or user since it's inherently redesign-oriented, helping move from critique to ideation.

In this project, I found it especially useful to start with the seven-point critique to diagnose the weaknesses of the original visualization — and then use the Good Charts framework to creatively explore what the redesign could and should do differently.


## Step three: Sketch a solution

The transition from national/racial breakdown → state-level revenue comparison required a completely new visual structure.

**Early Design Goals:**
* Make comparisons across states within revenue brackets.

* Show how firm distribution changes with higher revenue levels.

* Identify states that are consistently strong across revenue tiers.

**Sketch Concept:**
* **X-axis:** Revenue brackets ($50k–$1M+)

* **Y-axis:** Number of firms

* **Stacked bars:** One per revenue bracket, with 10 colors representing states.

* **Legend:** State-color matching on right side.

I prioritized stacked bar charts over grouped bars because it emphasizes relative contribution to total within each bracket.



## Step four: Test the solution


* Questions asked: 

- Can you tell me what insight this graph wants to convey?

- Who do you think is the intended audience for this?

- Is there anything you find surprising or confusing?

- Do you think comparing across revenue categories makes sense?

- Is there any other insight you think would be more interesting to the user?

- Does the color scheme reflect the insight without confusion?

* Results: 



| Question | Interview 1 | Interview 2 |
|----------|-------------|-------------|
|          |             |             |
|          |             |             |
|          |             |             |

Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

## Step five: build the solution


<div class='tableauPlaceholder' id='viz1743650963607' style='position: relative'>
   <noscript><a href='#'><img alt='State of Enterprise: California leads the states with the most $1M+ revenue firms ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;To&#47;Top10States-AnnualRevenuefirms&#47;Top10States-AnnualRevenuefirms&#47;1_rss.png' style='border: none' /></a></noscript>
   <object class='tableauViz'  style='display:none;'>
      <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
      <param name='embed_code_version' value='3' />
      <param name='site_root' value='' />
      <param name='name' value='Top10States-AnnualRevenuefirms&#47;Top10States-AnnualRevenuefirms' />
      <param name='tabs' value='no' />
      <param name='toolbar' value='yes' />
      <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;To&#47;Top10States-AnnualRevenuefirms&#47;Top10States-AnnualRevenuefirms&#47;1.png' />
      <param name='animate_transition' value='yes' />
      <param name='display_static_image' value='yes' />
      <param name='display_spinner' value='yes' />
      <param name='display_overlay' value='yes' />
      <param name='display_count' value='yes' />
      <param name='language' value='en-GB' />
      <param name='filter' value='publish=yes' />
   </object>
</div>
<script type='text/javascript'>                    var divElement = document.getElementById('viz1743650963607');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

### What the Redesign Does Differently:

* Emphasizes geographic rather than racial disparities.

* Makes state-by-state contributions to revenue level visually obvious.

* Highlights California as the dominant state at first glance

### Final Reflection

The new graph isn't just a visual upgrade — it's also data reframing. I learned that design isn’t just about making charts prettier, but about asking “What story do I want to tell?” In this case, I decided to surface state-level economic contributions, which not only told a different story, but arguably a more actionable one for regional policy or investment decisions.




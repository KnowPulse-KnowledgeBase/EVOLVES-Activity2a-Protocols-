---
layout: lesson
root: .
# Overall title for the Lesson.
# This should be in the form of a question if possible.
title: "EVOLVES Activity 2a analyses protocols"

# Single Sentence purpose for this lesson.
short-purpose: "This lesson will show our new researchers some of the protocols we use in our research laboratory"

# Single-Sentence describing the researchers
# who will be helped by this tutorial.
who: "Pulse Crop Researchers."

# A comma-separated list of maintainers for this lesson.
maintainers: "Ruobin Liu"

# A short paragraph describing why we created this lesson.
# What question is it trying to solve and why is that question important.
why: "This lesson is providing some essential laboratory protocols to guide new researchers to conduct their experiments.."

# A short list of items researchers will learn in this lesson.
learn:
- "How to prepare Standard Curves for determining Free Sulfhydryl (SH) Concentration"
- "How to prepare Standard Curves for determining Soluble Protein Concentration"
- "How to prepare Lentil Extract"
- "How to determine Free Sulfhydryl (SH) Concentration"

data-description: "Lentil"
---

The KnowPulse KnowledgeBase focuses on short question-based lessons to help researchers get their work done.

- **Purpose:** {{ page.short-purpose }}
- **Who:** {{ page.who }}
- **Maintainer(s):** {{ page.maintainers }}

{{ page.why }}

<strong>Some of the things you will learn include:</strong>
<ul>
	{% for item in page.learn %}
	<li style="font-weight:bold">{{ item|markdownify }}</li>
	{% endfor %}
</ul>

> ## Getting Started
>
> The KnowPulse KnowledgeBase lessons are hands-on, so participants are
> encouraged to use their own computers to ensure the proper setup of tools
> for an efficient workflow. To most effectively use these materials,
> please make sure to download the data and install everything before
> working through this lesson.
>
> This workshop assumes no prior experience with the tools covered in the
> workshop.
>
> To get started, follow the directions in the [Setup](setup.html) tab to
> get access to the required software and data for this workshop.
{: .prereq}


> ## Data
>
> {{ page.data-description }}
{: .prereq}

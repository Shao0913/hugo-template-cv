---
title: 'Nonlinear Correct and Smooth for Semi-Supervised Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Xiuwen Liu

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-03-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: The International Joint Conference on Neural Networks
publication_short: IJCNN

abstract: Graph-based semi-supervised learning (GSSL) has been used successfully in various applications, with existing methods leveraging the graph structure and labeled samples for classification. Label Propagation (LP) and Graph Neural Networks (GNNs) both iteratively pass messages on graphs, where LP propagates and updates node labels across the graph and GNN aggregates node features from their neighboring nodes. Recently, combining LP and GNN has led to improvements in performance, yet the joint utilization of labels and features in higher-order structures of graphs, such as triangles, remains unexplored. Therefore, we introduce Nonlinear Correct and Smooth (NLCS), a combined post-processing method that incorporates non-linearity and higher-order representation into the residual propagation to address intricate node relationships effectively. Systematic evaluations show that our approach achieves remarkable average improvements of 13.2\% over base prediction and 2.1\% over the state-of-the-art post-processing method on six commonly used datasets. Comparisons and analyses reveal that our method enhances the prediction accuracy of nodes with complex architecture by effectively utilizing triangle relationships within graphs.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2310.05757'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:[]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

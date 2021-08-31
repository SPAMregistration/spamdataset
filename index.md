## SPaM: Soft Patch Matching for Non-rigid Pointcloud Registration

We propose a novel non-rigid registration framework for raw, unstructured, subject-to-deformation pointclouds purely based on geometric features. 
While non-rigid registration approaches often rely on visual information or pre-defined shape templates, our framework simply consists of clusters of points with soft boundaries so-called \emph{soft patches}. We use SHOT descriptors to establish an initial correspondence graph over the source and target soft patches. The key feature of the proposed framework is our novel strategy to search through this graph based on the rigidity terms defined in a reformulation of As-Rigid-As-Possible as the assignment error. The non-rigid registration problem is then formulated as an aggregation of weighted locally rigid transformations, with the locality embodied in the soft patches. Given the optimized graph and the weighted transformations, individual points from the source are warped to the target. We evaluate and benchmark the proposed framework with state-of-art algorithms in simulated and real datasets. Experiments demonstrate the capability of the proposed approach to cope with large deformations and missing data.
 
### Datasets
Due to the lack of a publicly available datasets with ground truth, we synthetically generated data to benchmark our approach. These datasets are publicly available online [**here**](https://studentutsedu-my.sharepoint.com/:f:/g/personal/behnam_maleki_uts_edu_au/EoqNP7Y_0jVBlPHOV8KUqngBfU8tzsdmN0_NGaaKXDqbCA?e=ThUich).
    
    
    
You can use the [editor on GitHub](https://github.com/SPAMregistration/spamdataset/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/SPAMregistration/spamdataset/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

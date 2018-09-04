# Joint Learning of Gaze and Actions in First Person Video

Abstract: We address the task of jointly determining what a person is doing and where they are looking based on the analysis of video captured by a headworn camera. We propose a novel deep model for joint gaze estimation and action recognition in First Person Vision. Our method describes the participant's gaze as a probabilistic variable and models its distribution using stochastic units in a deep network. We sample from these stochastic units to generate an attention map. This attention map guides the aggregation of visual features in action recognition, thereby providing coupling between gaze and action. We evaluate our method on the standard EGTEA dataset and demonstrate performance that exceeds the state-of-the-art by a significant margin of 3.5%.

![Image](/fpv_overview.pdf ?raw=true)

You can download our paper here[[pdf]](https://www.dropbox.com/s/8rjirv5s3q232so/eccv18-gaze-action.pdf?dl=0)

You are welcomed to use our [dataset](http://www.cbi.gatech.edu/fpv/).

You can use the [editor on GitHub](https://github.com/aptx4869LM/FPVGazeActions/edit/master/README.md) to maintain and preview the content for your website in Markdown files.


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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/aptx4869LM/FPVGazeActions/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

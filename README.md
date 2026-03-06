# Data Science Workflow
Directions for setting up Obsidian and Positron for academic research

## Obsidian

### Installing

1. Install it here: [Obsidian.md](https://www.notion.so/Obsidian.Md)
2. Download [this folder](https://drive.google.com/file/d/1eR8vvxt0YS6BgXAmp7xWuh0baUBoCqMl/view?usp=sharing) and drag it to your Obsidian Vault

### Zotero Integration

1. Create a folder called `Papers`
2. Copy and paste this into a note called `PaperTemplate` within a folder called `Templates` in your Obsidian Vault

```r
> {{bibliography}}

**Citation Key:** {{citekey}}  
**Authors:** {{authors}}  
**Title**: {{title}}
**Year:** {{date}}
**PDF**: {{pdfLink}}
## Abstract
{{abstractNote}}
## Annotations
{{formattedAnnotationsNew}}
```

## Positron

1. Download it from (this link)[https://positron.posit.co/]
2. Download settings.json from this repo and copy it to your Positron folder. On MacOS the pathway should look like `/Users/[your-user-name]/Library/Application Support/Positron/User/settings.json`

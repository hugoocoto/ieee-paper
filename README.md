# IEEE Article in Typst

A multilanguage Typst template for writing academic papers in the IEEE style (Unofficial). Based on the ieee-charged template.

![image](./thumbnail.png)

---

## Usage

The script `./install.sh` copies the package to your typst local path.

After using the script, you can start from a template by typing `typst init @local/ieee-paper:1.0.0`.

```typst
#import "@local/ieee-paper:1.0.0": ieee

#show: ieee.with(
  title: [A Novel Approach to Typst Templates],
  authors: (
    (name: "Jane Doe", organization: "University of Typst", email: "jane@example.com"),
  ),
  abstract: [This paper introduces a comprehensive IEEE template...],
  index-terms: ("Typst", "IEEE", "Typesetting"),
  bibliography: bibliography("refs.bib"),
  lang: "en",
)

= Introduction
Your article content goes here...
```

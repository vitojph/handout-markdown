---
title: "How to Create Beautiful Documents Written in Markdown"
date: \today
author: "Víctor Peinado"
bibliography: "references.bib"
link-citations: true
urlcolor: "blue"
csl: "https://raw.githubusercontent.com/citation-style-language/styles/master/harvard-anglia-ruskin-university.csl"
---

# Motivation

I've always wanted to easily create beautiful documents following [Edward Tufte](https://en.wikipedia.org/wiki/Edward_Tufte)'s guidelines. For years, my favorite setup was to leverage [RMarkdown](https://rmarkdown.rstudio.com/) and [Tufte Handout](https://rstudio.github.io/tufte/), whose results are awesome. But I no longer use [R](https://www.r-project.org/) nor [r-studio](https://www.rstudio.com/) on a daily basis, and I need an alternative.

Recently, I've found [Scientific Writing with Markdown](https://jaantollander.com/post/scientific-writing-with-markdown/), by [Jaan Tollander de Balsch](https://jaantollander.com/author/jaan-tollander-de-balsch/), and gave me couple of ideas.


# The First Section

This is an example with some code excerpts, using Python:

```python
def sum_two_numbers(a: int, b: int) -> int:
    """Returns the sum of two integers"""
    return a+b
```

And the same stupid function written in Go:

```go
func sum_two_numbers(a, b int) (int) {
	return a + b 
}
```

And you can also refer to some equation, using $\LaTeX$, as shown in \ref{1}.

$$
f(a)={\frac {1}{2\pi i}}\oint _{\gamma }{\frac {f(z)}{z-a}}\,dz
\tag{1}
\label{1}
$$

This is a cite, as shown in [@doe-2020].

# The Second Section

This is some _lorem ipsum_. Enjoy.

Facilis deserunt rem nam quis at aut quia blanditiis. Rerum harum pariatur aut deserunt odio id. Voluptas consectetur aut nobis enim ea et in quia. Aut molestiae modi tempore.


# The Third Section

As you can imagine, this is the end. This is the last paragraph. I hope this example is useful.

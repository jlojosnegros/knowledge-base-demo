# Extra features

It supports all the basic [[MarkdownDemo|Markdown features]] and some additional ones like:

```

-   **#Tags**
-   $$**LaTeX** math$$
-   [^**Footnotes**]
-   **[[Internal links]]**
-   **![[Filename]]** to embed notes and other files

```

## Tags

#support #tags

## LaTeX

$$
\begin{multline}
\end{multline}
$$

$$\begin{equation}
x^2 = 1\\
x
\end{equation}$$

$$\begin{pmatrix}
0&1\\
1&0
\end{pmatrix}$$

## FootNotes

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

## Internal Links

```md
Link to a page: [[Embeds]].
```

Link to a page: [[Embeds]].

## Embed other files

It is possible to show other files just by add a `!` to its link

```md
Embed a page: ![[Embeds]]
```

![[Embeds]]

[^1]: meaningful!
[^bignote]: Here's one with multiple paragraphs and code.

## Tasks

```md
- [x] #tags, [links](), **formatting** supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
- [ ] tasks can be clicked in Preview to be checked off
```

- [x] #tags, [links](), **formatting** supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [?] this is also a complete item (works with every character)
- [ ] this is an incomplete item
- [ ] tasks can be clicked in Preview to be checked off

![[Lists]]

## and more

- [[Diagrams]]
- [[Callouts]]

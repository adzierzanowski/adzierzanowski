> [!IMPORTANT]
>
> Did you know this cool little fact?

```math
\exists_{\xi \in \mathbb{R}} \forall_{x \in \mathbb{R}} \lim_{n \rightarrow \infty} \cos^{[n]}(x) = \xi
```

where 

```math
f^{[n]} := \underbrace{f \circ f \circ\dots\circ f}_n
```

means we smashed the $\cos$ key on a calculator $n$ times.

Starting with any $x$ and we'll get the same result ($\approx 0.73908513$) every single time.

My math teacher in high school told me that it's probably just a floating-point error but apparently it really is the fixed point of the cosine function.

---

```stl
solid 
facet normal 1 0 -0
 outer loop
  vertex 12 -8 20
  vertex 12 -8 2.3886801e-15
  vertex 12 12 20
 endloop
endfacet
facet normal 1 0 0
 outer loop
  vertex 12 -8 2.3886801e-15
  vertex 12 12 -3.2768586e-15
  vertex 12 12 20
 endloop
endfacet
facet normal -1 0 0
 outer loop
  vertex -8 12 20
  vertex -8 12 -3.2768586e-15
  vertex -8 -8 20
 endloop
endfacet
facet normal -1 0 0
 outer loop
  vertex -8 12 -3.2768586e-15
  vertex -8 -8 2.3886801e-15
  vertex -8 -8 20
 endloop
endfacet
facet normal 0 -0 1
 outer loop
  vertex -8 12 20
  vertex -8 -8 20
  vertex 12 12 20
 endloop
endfacet
facet normal 0 0 1
 outer loop
  vertex -8 -8 20
  vertex 12 -8 20
  vertex 12 12 20
 endloop
endfacet
facet normal 0 -2.8327693e-16 -1
 outer loop
  vertex -8 -8 2.3886801e-15
  vertex -8 12 -3.2768586e-15
  vertex 12 -8 2.3886801e-15
 endloop
endfacet
facet normal -0 -2.8327693e-16 -1
 outer loop
  vertex -8 12 -3.2768586e-15
  vertex 12 12 -3.2768586e-15
  vertex 12 -8 2.3886801e-15
 endloop
endfacet
facet normal -0 -1 0
 outer loop
  vertex -8 -8 20
  vertex -8 -8 2.3886801e-15
  vertex 12 -8 20
 endloop
endfacet
facet normal -0 -1 -0
 outer loop
  vertex -8 -8 2.3886801e-15
  vertex 12 -8 2.3886801e-15
  vertex 12 -8 20
 endloop
endfacet
facet normal -0 1 0
 outer loop
  vertex 12 12 20
  vertex 12 12 -3.2768586e-15
  vertex -8 12 20
 endloop
endfacet
facet normal -0 1 0
 outer loop
  vertex 12 12 -3.2768586e-15
  vertex -8 12 -3.2768586e-15
  vertex -8 12 20
 endloop
endfacet
facet normal 0.73994005 0 0.6726728
 outer loop
  vertex 12 -8 20
  vertex 12 12 20
  vertex 2 2 31
 endloop
endfacet
facet normal -0 0.73994005 0.6726728
 outer loop
  vertex 12 12 20
  vertex -8 12 20
  vertex 2 2 31
 endloop
endfacet
facet normal -0.73994005 0 0.6726728
 outer loop
  vertex -8 12 20
  vertex -8 -8 20
  vertex 2 2 31
 endloop
endfacet
facet normal 0 -0.73994005 0.6726728
 outer loop
  vertex -8 -8 20
  vertex 12 -8 20
  vertex 2 2 31
 endloop
endfacet
facet normal 0 0 -1
 outer loop
  vertex 12 12 20
  vertex 12 -8 20
  vertex 2 2 20
 endloop
endfacet
facet normal 0 0 -1
 outer loop
  vertex -8 12 20
  vertex 12 12 20
  vertex 2 2 20
 endloop
endfacet
facet normal -0 -0 -1
 outer loop
  vertex -8 -8 20
  vertex -8 12 20
  vertex 2 2 20
 endloop
endfacet
facet normal 0 -0 -1
 outer loop
  vertex 12 -8 20
  vertex -8 -8 20
  vertex 2 2 20
 endloop
endfacet
endsolid 

```

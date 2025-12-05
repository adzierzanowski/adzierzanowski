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

My math teacher in high school told me that it's probably just a floating-point error but apparently it **really is** the fixed point of the cosine function.

---

```mermaid

flowchart LR
 x --> D

```

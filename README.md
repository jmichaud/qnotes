# github md cheatsheet


|     |       |      |     |     |      |     |     |     |
|-----|-------|------|-----|-----|------|-----|-----|-----|
| 🔴  |  🟠  | 🟡   | 🟢  |  🔵 |  🟣 |  🟤 | ⚫  | ⚪  |
| 🟥  |  🟧  | 🟨   | 🟩  |  🟦 |  🟪 |  🟫 | ⬛  | ⬜  |
| ❤️  |  🧡  | 💛   | 💚  |  💙 |  💜 |  🤎 | 🖤  | 🤍 |
|  ∅  |  ×   | ÷     |  ⚠  |  💩 |  ☠   | 💣 | ✅  | ❌  |
| 🚫  |  ❓ |  ❗   |  💔 |  🔥 |  ⭐ |     |     |     |

```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```

You can add footnotes with `[^1]` [^1]

or even with `[^myword]` [^myword]

[^1]: `[^1]:` It appears at the foot no matter where defined!

[^myword]: `[^myword]:` can use any word


`~~strikethrough~~` ~~strikethrough~~

`1<sup>st</sub>` 1<sup>st</sub>

`H<sub>2</sub>O` H<sub>2</sub>O

- [ ] checkbox
- [X] checked


| Color	 | Syntax        | Example	Input       | Output             |
|--------|---------------|----------------------|---------------------|
| HEX	 | `#RRGGBB`     | `#0969DA`            |  `#0969DA`          |
| RGB	 | `rgb(R,G,B)`  | `rgb(9, 105, 218)`   |  `rgb(9, 105, 218)` |
| HSL	 | `hsl(H,S,L)`  | `hsl(212, 92%, 45%)` |  `hsl(212, 92%, 45%)`|

```diff
  +----+-------+----+
  |id  |name   |wins|
  +----+-------+----+
- |1   |Alice  |444 |
+ |2   |Bob    |203 |
! |3   |Carmen |498 |
  |4   |Dan    |298 |
# |5   |Edgar  |715 |
# |6   |Fred   |111 |

  fun main() {
      println("Hello World!")
!     println(1.2 - 1.0) // = 0.19999999999999996
  }
```
```text
> quoting text line 1 <br> quoting text line 2
> 
> quoting text line 3
```
> quoting text line 1 <br> quoting text line 2
> 
> quoting text line 3

`[link text](google.com)`
[link_text](google.com)  

`![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)`
![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)


<details><summary>CLICK ME</summary>
<p>

#### We can hide anything, even code!
```xml
   <details><summary>CLICK ME</summary>
    <p>
        Details tag hides things
    </p>
</details>
```
</p>
</details>

This sentence uses `$` delimiters to show math inline: `$\sqrt{3x-1}+(1+x)^2$` $\sqrt{3x-1}+(1+x)^2$

`$` `$` `\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)` `$` `$`

$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$

```math
\sqrt{3}
```





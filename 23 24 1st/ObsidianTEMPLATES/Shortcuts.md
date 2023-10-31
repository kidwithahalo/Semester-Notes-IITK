
# For image 
```html
<figure>
<center>
<img src="" alt="" style="width:100%">
<figcaption align = "center">
<b>Caption</b>
</figcaption>
</center>
</figure>
```


# For side to side image 
```html
<div style="display: flex; justify-content: center; gap: 10px;">
  <!-- Replace 'image1.jpg' and 'image2.jpg' with the paths to your images -->
  <img src="" alt="Image 1" style="width: 50%;">
  <img src="" alt="Image 2" style="width: 50%;">
</div>

```



# For bold and mark 
```html
<p>The earth shape is mostly <u>geoid</u> which means it is punched at the poles  </p>
```



# For table 

```html
<table> 
  <tr>  
    <td>Asteroids</td>  
    <td>Meteoroids</td> 
    <td>Comets</td> 
  </tr>  
  <tr>  
    <td>Small </td>  
    <td>he gravity of planets</td>  
    <td>They  they leave a hazy trail. </td>
  </tr>  
</table>
```


# For mind mapping  - Mermaid
```html
graph LR
    A[Symbol in maps] --> B(Sketch)
    A --> C((sdg))
    A --> D((asd))

	B --> E(AAA)
    C --> F(AA)
    D --> G(A)
```

# For Pie Chart - Mermaid
Choices for themes are 
+ default
+ dark
+ forest
+ neutral
+ base
```html
pie title India and it's Land Distribution
    "Plains" : 43
    "Mountains" : 30
    "Plateau" : 27
```

# For trivia 
```html
> ## Trivia
```


# Text highlight 
```html
<b style = "color:RebeccaPurple"></b>
```
```html
# <span  style = "color:dodgerblue"></span>
```
```html
## <span  style = "color:PaleGreen"></span>
```
```html
### <span  style = "color:AquaMarine"></span>
```
```html
#### <span  style = "color:Tomato"></span>
```
```html
##### <span  style = "color:SpringGreen"></span>
```
```html
###### <span  style = "color:Orchid"></span>
```
```html
<span  style = "color:Sienna"></span>
```
```html
### <span  style = "color:SteelBlue">Activity Question</span>
```

# For embedding a page into .md
```html
<iframe src="" style="width:100%; height:600px;" ></iframe>
```

# For latex equation code 
```latex
$$
    \begin{equation} 
    \tag{1}
	     m_1 - m_2 = 2.5 \log \frac{l_2}{l_1}  
    \end{equation}
  $$
```
### Multiline latex code 
```latex
$$
\begin{aligned}
\\
 \\
 \\
 \\
\end{aligned}
$$
```

### For piecewise equation
```latex
$$
\begin{equation}
f(x) = 
\left\{
    \begin{array}{lr}
        x+1, & x>1\\
        -x, & x\geq0
    \end{array}
\right\}
\end{equation}
$$
```

## Fraction in latex
```latex
\left( \frac{ }{ }\right)
```
#### Angstrom Symbol
```latex
\overset{\circ}{\mathbb{A}}
```

#### Limit Sign
```latex
\lim_{ \to 0} \frac{}{}
```

#### bbox latex
```latex
$$\bbox[8px, border: 2px solid red] {}$$
```

#### elements notation
```latex
$$\ce{^{227}_{90}Th+}$$
```
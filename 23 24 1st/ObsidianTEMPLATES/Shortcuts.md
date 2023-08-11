
# For image 
```html
<figure>
<center>
<img src="" alt="" style="width:80%">
<figcaption align = "center">
<b>Caption</b>
</figcaption>
</center>
</figure>
```


# For side to side image 
```html
<div style="display: flex;">
  <figure>
    <img src="path_to_image1.jpg" alt="Image 1" style="width: 50%;">
    <figcaption>Caption for Image 1</figcaption>
  </figure>
  <figure>
    <img src="path_to_image2.jpg" alt="Image 2" style="width: 50%;">
    <figcaption>Caption for Image 2</figcaption>
  </figure>
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
<b style = "color:red"></b>
```

```html
<span  style = "color:dodgerblue">fff</span>
```
# For topic color 
```html
### <span  style = "color:dodgerblue">fff</span>
```


# For embedding a page into .md
```html
<iframe src="" style="width:100%; height:600px;" ></iframe>
```

# For latex equation code 
```html
$$
    \begin{equation} 
    \tag{1}
	     m_1 - m_2 = 2.5 \log \frac{l_2}{l_1}  
    \end{equation}
  $$
```
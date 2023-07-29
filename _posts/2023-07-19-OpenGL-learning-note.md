---
layout: post
tags: [learning note, OpenGL, Computer Graphics]
---
## Material
I learn OpenGL through this fascinating tutorial [LearnOpenGL](https://learnopengl.com/) authored by [Joey de Vries](https://github.com/JoeyDeVries).

## Practices
My personal practises of LearnOpenGL are [available here](https://github.com/swirling-wind/LearnOpenGL)

## Note

### Common Render Pipeline

``` cpp
vertex_data[] // As input
```

i. **_VERTEX SHADER_**

``` cpp
coordinates_data[]
```


ii. SHAPE ASSEMBLY

``` cpp
primitives[] // Like POINTS, TRIANGLES, LINE_STRIP, etc.
```

iii. GEOMETRY SHADER

``` cpp
more_primitives[]
```

iv. RASTERIZATION

``` cpp
fragments[]
```

v. CLIPPING

vi. **_FRAGMENT SHADER_**

``` cpp
pixels[] // From fragments, lighting, shadows, etc.
```

vii. ALPHA-TEST and BLENDING

<br>  
  
### Coordinate System

> Local Space
  
  Model Matrix
    
> World Space

  View Matrix

> View Space / Eye Space
  
  Projection Matrix  

> Clip Space
> Screen Space

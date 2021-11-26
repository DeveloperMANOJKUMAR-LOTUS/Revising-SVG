## SVG 

# Shapes :

* ### Line
* ### Rectangle
* ### Circle
* ### Ellipse
* ### Text
---Complex---
* ###  Polygon 
* ###  PolyLine
* ###  Path

***
### Line

```html
<svg width="500" height="500">
        <line x1="100" y1="100" x2="200" y2="200" stroke="red" ></line>
        <line x1="50" y1="100" x2="200" y2="100" stroke="blue" stroke-width="5"></line>
</svg>
    
```
### Rectangle
```html
<svg width="500" height="500">
        <rect x="200" y="100" height="150" width="100"></rect>
        <rect x="50" y="40" height="250" width="100" fill="aqua" stroke="green" stroke-width="4"></rect>
</svg>
```

### Circle
```html
 <svg width="500" height="500">
        <circle cx="100" cy="80" r="50"></circle>
        <circle cx="250" cy="50" r="70" fill="yellow" stroke="red" stroke-width="8"> </circle>
</svg>
```

### Ellipse
```html
<svg width="500" height="500">
        <ellipse cx="100" cy="100" rx="60" ry="80" stroke="red" stroke-width="3" fill="orange"></ellipse>
        <ellipse cx="300" cy="100" rx="20" ry="70" stroke="blue" stroke-width="5"><ellipse>
</svg>
```
### Text
```html
<svg width="500" height="500">
        <text x="180" y="250">This is a text<text>
</svg>
```
### PolyLine 
```html
<svg width="500" height="500">
        <polyline points="20,50 70,100 90,300 200,40" fill="none" stroke="red"></polyline>
        <polyline points="300,400 90,100 110,400 300,200" stroke="aqua" stroke-width="4" fill="blue"></polyline>
</svg>
```

### Polygon
```html
<svg width="500" height="500">
        <polygon points="20,50 70,100 90,300 200,40" fill="none" stroke="red"></polygon>
        <polygon points="300,400 90,100 110,400 300,200" stroke="aqua" stroke-width="4" fill="blue"></polygon>
</svg>
```

### Path

* M --> Move to x,y
* L --> Line to x,y
* l --> line to x,y => lx+x , ly+y  (relative)
* V --> Vertical Line x, y
* v --> vertical line => l
* H --> Horizontal line x,y
* h
* C --> Curve to cx1,cy1 cx2,cy2 ex,ey
* S --> smooth curve cx2,cy2 ex,ey
* Q --> quadratic curvato
* T --> smooth quadratic curve
* Z 

```html
<svg width="500" height="500">
        <path d="M100,50 L300,250 l40,200" stroke="blue" fill="aqua"></path>
        <path d="M50,50 V300,250 C300,100 100,400" stroke="blue" fill="aqua"></path>
        <path d="M50,50 H300,250 c300,100 100,400 100,420" stroke="blue" fill="green"></path>
</svg>
```

* defs
* symbol
* pattern
* clip-path
![github](https://user-images.githubusercontent.com/19171147/63228885-c1778900-c1c7-11e9-8506-86089a132ce1.png)


## Description 
Documento is a microsized, simple and fast JS templating engine that takes a template and data, and returns the template filled with the data. 

## Features
- [X] Vanilla JS 🍦
- [X] No dependencies required
- [X] Light-weight
- [X] Extremely Fast
- [X] Runtime Interpolation
- [X] User Friendly


## Installation 
The simplest method is to use the hosted version from jsDelivr:


#### JS
```html
  <script src="https://cdn.jsdelivr.net/gh/dbrownjave/documento.js/dist/documento.js"></script>
```


## Usage 

### Simple Template:
```js


// 1. create or fetch data
let data = { engine: "Documento", food: "🥞"}

// 2. create a template
var template = html`
<p>
My favorite template engine is ${data.engine},
My favorite food is: ${data.food} 
</p>
`
// 3. add your template
doc.html({ add: template })
```

#### Results
```html 
<p>My favorite food is: ${data.food}</p> 
```

## Anatomy 


## Sponsors
If you are interested in becoming a sponsor, please feel free to contact us!

## License
![card](https://user-images.githubusercontent.com/19171147/63110769-2b8af680-bf5a-11e9-8e45-92af70b6a654.png)

© 2019 [Magical X Labs](https://dorianbrown.io)  
Released under the [MIT LICENSE](http://opensource.org/licenses/MIT)



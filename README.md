
# CURSO DE MARKDOWN

Preview en VSC: **Para abrir el preview en VSC: ctrl + shift +p: markdown: open preview**

## titulo h2

### titulo h3

#### titulo h4

##### titulo h5

###### titulo h6

<!--italic-->
texto italic: *italic text*

<!--strong-->
negritas: **strong text**

<!--strikethrough-->
~~teexto tachado~~

<!--ul--->
* primero
  * subitem
* segundo
* tercero

1. primero
   1. subitem
2. segundo
3. tercero

<!--enlaces-->
[google.com](https://www.google.com)

[google.com](https://www.google.com "custom title")

<!--cita-->
>esta es una cita

<!--lineas separadoras-->
---
___
<!-- Backtips para hacer refencia a codigo -->
`console.log('aqui un ejemplo de codigo')`

<!-- Multiples lineas de codigo -->

```javascript
import React from 'react';
import { Container } from '@material-ui/core';
import { BrowserRouter, Switch, Route } from 'react-router-dom';

import Home from './components/Home/Home';
import Navbar from './components/Navbar/Navbar';
import Auth from './components/Auth/Auth';

const App = () => (
  <BrowserRouter>
    <Container maxWidth="lg">
      <Navbar />
      <Switch>
        <Route path="/" exact component={Home} />
        <Route path="/auth" exact component={Auth} />
      </Switch>
    </Container>
  </BrowserRouter>
);

export default App;
```

```python
print("Hello world")
```

```html
<h1>Hello world</h1>
```

<!-- Tablas en markdown -->
|Tables   | Are   | Cool   |
|---------|:-----:|-------:|
|col 3 is |right aligned|$16000|
|col 3 is |right aligned|$16000|
|col 3 is |right aligned|$16000|

<!-- imagenes en markdown -->
![visual studio logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRn5l-s47ezVoeQ6HaQrt__wgzlPn0uGQgfQg&usqp=CAU)

![ReactJS logo](react.png "ReactJS")

<!-- github markdown -->
* [x] Task1
* [ ]  Task2
* [x] Task3

@LexferRam :smiley: :+1:

___

### github emojis :earth_americas
<!-- github emojis -->
[https://gist.github.com/rxaviers/7360908](https://gist.github.com/rxaviers/7360908 "ir a github emojis")
 ___

### github emojis :earth_americas

<!--Markdown-Cheatsheet -->
[https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Markdown cheatsheet")

<!-- Awesome profile readme -->
 ___

### Awesome profile readme Templates

[https://github.com/kautukkundan/Awesome-Profile-README-templates](https://github.com/kautukkundan/Awesome-Profile-README-templates "Awesome profile readme")
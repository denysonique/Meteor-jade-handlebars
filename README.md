# Meteor Jade Handlebars
### Instead of writing (demo.html):

```
<head>
  <title>demo</title>
</head>

<body>
  {{> hello}}
</body>

<template name="hello">
  <h1>Hello World!</h1>
  {{greeting}}
</template>
```

###You may write (demo.jade):
```
head
  title demo

body
  {{> hello}}

  temlate(name="hello")
    h1 Hello World!
    {{greeting}}
```

## Installation
Check out this repository into a folder named jade-handlebars in your packages directory
```$ meteor add jade-handlebars```
## Todo
  Write tests

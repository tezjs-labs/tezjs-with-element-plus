# Tezjs with element-plus

- Element-plus is one of the available UI frameworks.
- We can use elements plus with the Tezjs through the below steps.
- Create fresh tezjs project
```
 npm create tez@latest
```
- Install package for element-plus
```
 npm install element-plus
```
- Now add it as a plugin, make a plugins directory and add index.ts inside it and add the below code 

```
plugins/index.ts

import ElementPlus from 'element-plus'
import 'element-plus/dist/index.css'

export default function(vue:any){
    vue.use(ElementPlus)
}
```

- It's done with tezjs. Now, you can use it inside your project.

- In current project all components and pages are designed with an element-plus framework.

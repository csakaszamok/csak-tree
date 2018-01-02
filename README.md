# \<csak-tree\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square)](https://beta.webcomponents.org/element/csakaszamok/csak-tree)

Its just a tree. A tree view. A file tree. A menu tree. A tree for you.  

The missing Polymer 2.x webcomponent.  

> Preview version!

Example 1

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>   
    <link rel="import" href="csak-tree.html">   
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

```html    
<csak-tree branchiconopen="vaadin:minus-square-o" branchicon="vaadin:plus-square-o" expanded>
  <csak-tree-item>Branch
    <csak-tree-item>Branch             
        <csak-tree-item>Leaf</csak-tree-item>
        <csak-tree-item>Leaf</csak-tree-item>
      </csak-tree-item>
      <csak-tree-item>Branch               
          <csak-tree-item>Leaf</csak-tree-item>
          <csak-tree-item>Leaf</csak-tree-item>
      </csak-tree-item>             
  </csak-tree-item>
</csak-tree>    
```

Example2

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>   
    <link rel="import" href="csak-tree.html">   
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

```html    
<csak-tree branchiconopen="vaadin:minus-square-o" branchicon="vaadin:plus-square-o" expanded
 data='{            
            "children ": [  
                  {
                    "name": "Bracnh",
                    "children": [                     
                      { 
                        "name": "leaf"                        
                      },
                      {
                        "name": "leaf"                        
                      }                      
                    ]
                  }        
               ]
             }'>
             </csak-tree>    
```

### Install with bower

First you need bower, [see their site](http://bower.io/) for details 

```
bower install --save csak-tree
```

[Online API documentation](https://csakaszamok.github.io/csak-tree/)

## Styling

Custom property | Description | Default
----------------|-------------|---------
--indent | Items indent value | 1em
--iron-icon-width | Inherited css variable | 16px

## Use cases
> + menutree
> + classic treeview
> + custom tree
> + filetree

### Menutree

![](https://github.com/csakaszamok/csak-tree/blob/master/csaktree_menutree.gif?raw=true)


[Demo](https://csakaszamok.github.io/csak-tree/demo/demo_treemenu.html)

### Classic treeview

![](https://github.com/csakaszamok/csak-tree/raw/master/csaktree_classictreeviewi.gif?raw=true)

[Demo](https://csakaszamok.github.io/csak-tree/demo/demo_classici.html)

[Demo](https://csakaszamok.github.io/csak-tree/demo/demo_classicii.html)

### Events demo

[Demo](https://csakaszamok.github.io/csak-tree/demo/demo_events.html)

### Custom tree

![](https://github.com/csakaszamok/csak-tree/raw/master/csaktree_customimages.gif?raw=true)

[Demo](https://csakaszamok.github.io/csak-tree/demo/demo_image.html)

### Filetree

![](https://github.com/csakaszamok/csak-tree/blob/master/csaktree_vscodemonaco.gif?raw=true)

[Demo](https://csakaszamok.github.io/csak-tree/demo/demo_vscode.html)

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
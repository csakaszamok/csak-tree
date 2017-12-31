# \<csak-tree\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square)](https://beta.webcomponents.org/element/csakaszamok/csak-tree)

Its just a tree. A tree view. A file tree. A menu tree. A tree for you.  

The missing Polymer 2.x webcomponent.  

> Preview version!

Example:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>   
    <link rel="import" href="csak-tree.html">
    <link rel="import" href="csak-tree-item.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

<!--```html
 <p class="caption">Class treeview I</p>
      <template>
        <style>
          .classictreeview csak-tree-item {          
            --iron-icon-width: 16px;
          }
        </style>
        <csak-tree class="classictreeview" branchiconopen="vaadin:minus-square-o" branchicon="vaadin:plus-square-o">
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
      </template>
```-->

### Install with bower

First you need bower, [see their site](http://bower.io/) for details 

```
bower install --save csak-tree
```

## Use cases
> + menutree
> + classic treeview
> + custom tree
> + filetree

### menutree

![](https://github.com/csakaszamok/csak-tree/blob/master/csaktree_menutree.gif?raw=true)

### classic treeview

![](https://github.com/csakaszamok/csak-tree/raw/master/csaktree_classictreeviewi.gif?raw=true)

### custom tree

![](https://github.com/csakaszamok/csak-tree/raw/master/csaktree_customimages.gif?raw=true)

### filetree

![](https://github.com/csakaszamok/csak-tree/blob/master/csaktree_vscodemonaco.gif?raw=true)

DOT is language for creating diagrams quickly and easily. Dot has support for outputting to SVG and to PNG except the diagrams are a little plain looking. This program spruces it up a little by adding shadows and rounded rectangle to the SVG.

```
digraph G {
  node [
    shape="box"
    style="filled"
  ]
  Hello->World
}
```

Before:
![http://dot2svg.googlecode.com/svn/trunk/img/hello-orig.png](http://dot2svg.googlecode.com/svn/trunk/img/hello-orig.png)
After:
![http://dot2svg.googlecode.com/svn/trunk/img/hello.png](http://dot2svg.googlecode.com/svn/trunk/img/hello.png)
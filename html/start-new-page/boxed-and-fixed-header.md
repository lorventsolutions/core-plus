# Boxed and Fixed Header

The design for Boxed & Fixed Header is shown below:

![](../../.gitbook/assets/boxedfixed.png)

It has the following Structure:

_structure:_

For this we need to add a class**`boxed`**in the body tag**`navbar-fixed-top`**in the nav tag.

```text
<body class="skin-coreplus boxed">
     <div class="preloader">
          ...
          ...
    </div>
    <header class="header">
         <nav class="navbar navbar-fixed-top" role="navigation">
            ...
         </nav>
    </header>
    <div class="wrapper row-offcanvas row-offcanvas-left">
    <aside class="left-side sidebar-offcanvas">
       ...
       ...
    </aside>
      ...
      ...
</body>
```


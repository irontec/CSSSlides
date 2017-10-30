## flex.css
<div>
<ul class="add-css-in-html-without-align">
    <pre>
    body {
       min-height: 1000px;
    }
    main {
      height: 600px;
      display: flex;
    }
    article {
      flex: 2;
    }
    * {
      box-sizing: border-box;
    }
    </pre>
</ul>
<ul class="add-css-in-html-without-align">
    <pre>
    nav,
    aside {
      background: #808080;
      padding: 10px;
      flex: 1;
    }
    header,
    footer {
      background: rgba(0,0,0,0.18);
      height: 200px;
      padding: 10px;
    }
    article {
      padding: 10px;
    }    </pre>
</ul>
</div>
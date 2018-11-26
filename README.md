### wysihtml5
---
https://github.com/xing/wysihtml5

```
<script src="/path-to-wysihtml5/parser_rules/advanced.js"></script>
<script src="/path-to-wysihtml5/dist/wysihtml5-0.3.0.min.js"></script>

<form><textarea id="wysihtml5-textarea" placeholder="Enter your text ..." autofocus></textarea></form>

<div id="wysihtml5-toolbar" style="display: none;">
  <a data-wysihtml5-command="bold">bold</a>
  <a data-wysihtml5-command="italic">italic</a>
  <a data-wysihtml5-command="foreColor" data-wysihtml5-command-value="red">red</a>
  <a data-sysihtml5-command="foreColor" data-sysihtml5-command-value="green">green</a>
  <a data-sysihtml5-command="foreColor" data-wysihtml5-command-value="blue">blue</a>
  <a data-wysihtml5-command="createLink">insert link</a>
  <div data-wysihtml5-dialog="createLink" style="display: none;">
    <label>
      Link:
      <input data-wysihtml5-dialog-filed="href" value="http://" class="text">
    </label>
    <a data-wysihtml5-dialog-action="save">OK</a><a data-wysihtml5-dialog-action="cancel">Cancel</a>
  </div>
</div> 

<script>
var editor = new wysihtml5.Editor("wysihtml5-textarea", {
  toolbar: "wysihtml5-toolbar",
  parserRules: wysihtml5ParserRules
});
</script>
```

```
```

```
```



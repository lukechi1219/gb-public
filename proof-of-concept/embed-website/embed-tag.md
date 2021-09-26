# embed tag

.

&lt;p&gt;Using "embed" as an alternative to iframes&lt;/p&gt;

        &lt;embed src="https://ide.geeksforgeeks.org/" 

               width="400" 

               height="400"

               style="border:none;" /&gt;

.

1. you can use &lt;embed&gt; element

```text
<embed id="123" src="http://google.com" />
```

works fine in chrome ,safari and firefox, to make it work in firefox, you need wrap it with object

```text
<object data="url" type=text/html>
   <embed src="url" id=123>
   </embed>
</object>
```

.


# How to click programmatically button inside iframe?

There can be situations when we would like to customize iframe content or trigger some actions from outside iframe window. 

Presented demos display how to make button that is outside iframe – clicking button placed inside iframe.

Example of clicking iframe button (from outside iframe):
```
<script>
    function triggerClickInsideIframe() {
        document.getElementById("myIframe").contentWindow.document.getElementById("toggleDivButton").click();
    }
</script>
```

### Notice: iframe modifications are allowed only for same-origin urls (the same protocol and domain)

#### Demo1
![](https://github.com/createit-dev/166-how-to-click-programmatically-button-inside-iframe/blob/master/images/demo1.gif)

#### Demo2
![](https://github.com/createit-dev/166-how-to-click-programmatically-button-inside-iframe/blob/master/images/demo2.gif)

#### Demo3
![](https://github.com/createit-dev/166-how-to-click-programmatically-button-inside-iframe/blob/master/images/demo3.gif)


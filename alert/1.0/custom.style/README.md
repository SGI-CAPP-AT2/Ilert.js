### for windows 7 style button
```html
<style>.a-il{color:black}</style>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/SGI-CAPP-AT2/ilert.js/alert/1.0/custom.style/windows.css"> <!--for windows style buttons-->
```
[![fromlypreviewofw7](IMG_20210213_110550.jpg)](win7.txt)
### for mac style button
```html
<style>.a-il{color:black}</style>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/SGI-CAPP-AT2/ilert.js/alert/1.0/custom.style/apple.mac.css"> <!--for windows style buttons-->
```
Thanks for Apple Mac button [@fredsted](https://gist.github.com/fredsted)
[![--mac--prev--](IMG_20210213_105328.jpg)](mac.cust.txt)
### without custom plug
Preview
![al!=plug](IMG_20210213_111033.jpg)
### how to style ilert buttons ?
```html 
<script src="https://cdn.jsdelivr.net/gh/SGI-CAPP-AT2/ilert.js/alert/1.0/custom.style/main/plug.js"></script>
<script>
ilusSetCustom(`
{
/*your custom code*/
}
`)
</script>
```
#### preview of the custom
```javascript
<script src="https://cdn.jsdelivr.net/gh/SGI-CAPP-AT2/ilert.js/alert/1.0/custom.style/main/plug.js"></script>
<script>
ilusSetCustom(`{background:red;border:1px solid white;}`)
</script>
```
[![preview](IMG_20210213_112623.jpg)](main/plug.js)

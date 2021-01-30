# iLert Started
***
alerts for js web projects
***
[Try out latest demo](https://SGI-CAPP-AT2.github.io/ilert.js/alert/1.0/demo.html)
how to get Started ?
```html
<script src="https://cdn.jsdelivr.net/gh/SGI-CAPP-AT2/ilert.js/alert/1.0/app.js"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/SGI-CAPP-AT2/ilert.js/alert/1.0/style.css">
```
```javascript
ilusLert({header:'hii',message:'great'});
```
# contents
|name|type|options|description|
|----|---|---|---|
|header|`string`| your own string|use it for small description|
|theme|`string`|warn,success, default,danger|show your intensity of message|
|mode|`string`|Dark,light|theme for your message|
|message|`string`|your own string|use to discribe more|
|corners|`yes/no`|yes,no|if you use `no` as corners then border radii will be deleted|
|html|`yes/no`|yes,no|use it if you want to add html in message|
|buttons|`array`|make array consist of the button jsons [more](#buttons)|
# buttons 
```json{
buttons:[{
    value:'my custom',
    handler: function (){
    console.log('custom works');
    }
    }]
}```
|`value`|Your button will show value of button|
|`handler`|add Event listener to the button |

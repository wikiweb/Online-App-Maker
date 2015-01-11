# FaraFix-App-Maker
Online Cordova/Phonegap/html mobile app builder/maker

# basic structure
```javascript
var app = {id:"app1", name:"Beta"};

var pages = {
	"pg1":{name:"welcome"},
};

var components = {
	"comp1":{name:"default-image", tag:"img", innerKey:{./*inner html attr + options*/.}},
	"comp2":{name:"default-paragraph", tag:"p"}
};

var items = {
	"itm1":{page:"pg1", component:"comp1"},
};

var actions = {
	"act1":{name:"alert"}
};
```

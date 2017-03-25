# tabs-unlimited
Bootstrap 3 unlimited tabs

Quick start

1) load jquery, bootstrap and tabs-unlimited.js:
```html
<link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" />
<script
  src="https://code.jquery.com/jquery-2.2.4.min.js"
  integrity="sha256-BbhdlvQf/xTY9gja0Dq3HiwQF8LaCRTXxZKRutelT44="
  crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<script src="tabs-unlimited.js"></script>
```

2) add class tabs-unlimited to nav-tabs element:
```html 
<ul class="nav nav-tabs tabs-unlimited">
    <li class="active"><a data-toggle="tab" href="#home">Home</a></li>
    <li><a data-toggle="tab" href="#menu1">Menu 1</a></li>
    <li><a data-toggle="tab" href="#menu2">Menu 2</a></li>
    <li><a data-toggle="tab" href="#menu3">Menu 3</a></li>
    <li><a data-toggle="tab" href="#menu4">Menu 4</a></li>
    <li><a data-toggle="tab" href="#menu5">Menu 5</a></li>
    <li><a data-toggle="tab" href="#menu6">Menu 6</a></li>
</ul>
```

3) ... and just call:
```javascript 
tabs_unlimited()
```

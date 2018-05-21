# css styles for responsive column
Hello world! :)  
I've made this css styles for displaying responsive equal sized columns, which is specially used to display items in a grid view.
These styles are very easy to use than bootstrap.

HOW TO USE ?
---
There are three styles classes are available:  
**1) `.col-135i`** : this will present 1, 3, 5 items in a row for sm, md, lg sizes  
**2) `.col-246i`** : this will present 2, 4, 6 items in a row for sm, md, lg sizes  
**3) `.col-123456i`** : this will ... now you know what i meant to say :D  

You can use these classes as your html classes as,

Html with angular example
``` html
<div ng-app="myApp">
    ...
    <div ng-repeat="item in lstItems">
        <div class="col-246i">
            {{item}}
            ...
        </div>
    </div>
 </div>
```

cshtml Razor example:
``` html
<div>
    @foreach (var m in Model)
    {
        <div class="col-135i">
            ...
        </div>
    }
</div>
```
Happy coding!

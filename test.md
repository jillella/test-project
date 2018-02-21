```javascript
var sample = document.getElementById('sample');
sample.addEventListener('click', function(event) {
  console.log('This is a silly place.');
});
```


One small step for 
```diff
-man
+humankind
```


```diff
var sample = document.getElementById('sample');
sample.addEventListener('click', function(event) {
  -console.log('This is a silly place.');
  +console.log('This is a silly place.');
});
```

```diff
<form class="search-form" ng-controller="quickSearchController" ng-if="appMode != 'strip'">
    <div class="dropdown">
        <input type="text" 
                tabindex="-1" 
                placeholder="Search by client, account or Veo&reg; group" 
                class="form-control dropdown-toggle client-search" 
                ng-model="query" 
                veo-popover="#headerPopoverSearch" 
                data-show-close="false" 
                data-show-arrow="false" 
                data-alignExp="{{('medium' === deviceResolution)&&'center'||'left'}}" 
                data-location-sensitive="true" 
                data-center-width-ratio="0.85">
        <span class="webicon large icon-search search normal-state" ></span>
        -<div veo-include="'veodashboard/application/quickSearch/views/quickSearchResults.html'"></div>
        +<div veo-include="'veodashboard/application/favorites/views/favorites.html'"></div>
    </div>
</form>
```

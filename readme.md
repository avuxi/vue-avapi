# vue-avapi

take a look at [integration repository](https://github.com/avuxi/Integrations) for integration example

### install

```
npm i --save avuxi/vue-avapi
```

### usage

```js
import Vue from 'vue'
import vueAvapi from 'vue-avapi'

Vue.use(vueAvapi)
```

```html
<!-- include Google Maps or Leaflet script -->
<!-- include configuration script from https://admin.avuxi.com -->

<avapi-map confId='5ae6df87a93f4e1e02a6122a'
           lat='41.38605'
           lng='2.17014'
           zoom='13'>
</avapi-map>

<avapi-lse confId='5ae6e03da93f4e1e02a6122b'
           lat='41.390847'
           lng='2.16902'>
</avapi-lse>
```
# pluginyoutube
```
pluginyoutube : You can make a list of videos on your youtube channel.
```

```
You need a jquery plugin:
<script src="../jquery-3.2.1.js"></script>
```
```
Link to the link containing the plugin:
<script src="../plugin.js"></script>
```
``` 
Using:
<script>
     $(document).ready(function() {

      $(".member").pluginyoutube({
          dataOption:{
              userId:'UCio_FVgKVgqcHrRiXDpnqbw',
              apikey:'AIzaSyA7LV2DX6RjRJCROAQS57mqIr4CHNRU0eQ',
              limit:50 
          }
      });

  });
  </script>
```

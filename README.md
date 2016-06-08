# wsjs
Simple JavaScript WebSocket wrapper

Usage:

```
<script type="text/javascript" src="js/ws.min.js"></script>

<script type="text/javascript">
  var server = 'ws://xyz.com/';
  var ws = new WebSocketWrapper(server);
  ws.connect().then(function(response) {
   var json = {"id":1,"data:"text"} ;
   ws.send(json, function(response) {
    // do stuff
   });
  });
</script>
```

# wsjs
Simple JavaScript WebSocket wrapper

Usage:

```
<script type="text/javascript" src="js/ws.min.js"></script>

<script type="text/javascript">
  var json = {"id":1,"data:"text"} 
  var ws = new WebSocketWrapper(server);
  ws.send(json, function(response) {
    // do stuff
  });
</script>
```

You can use sed to print lines between two matches but I keep forgetting the syntax so I tried awk:

```
awk '/select 1/{next;} match($0,"MATCH START"){flag=1; print substr($0,RSTART+22); next;} /MATCH END/{flag=0}flag' input.log
```

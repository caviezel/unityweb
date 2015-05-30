# Simple Example #

Note, the usage of Thread.Sleep is not mandatory, it just helps my unit tests play nice with MonoDevelop.

```
var r = new Request("get", "http://www.google.com/");
r.Send();
while(!r.isDone) Thread.Sleep(100);
Console.WriteLine(r.response.status);
Console.WriteLine(r.response.Text);
```

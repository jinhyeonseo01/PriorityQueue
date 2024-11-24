# PriorityQueue for Unity C#
**Script that converted the .Net offLcial PriorityQueue for use in Unity**  
*(Unity에서 사용하기 위해 .Net C# 13 공식 PriorityQueue를 변환한 스크립트)*  

*.Net offLcial syntax 100% compatible.* 
*update - C# 13 version compatible*
* * *
### .Net Official System Collections
  > **Documentation Link:**  [https://learn.microsoft.com/PriorityQueue](https://learn.microsoft.com/en-us/dotnet/api/system.collections.generic.priorityqueue-2?view=net-8.0/)  
  > **도큐먼트 링크:**  [https://learn.microsoft.com/PriorityQueue](https://learn.microsoft.com/ko-kr/dotnet/api/system.collections.generic.priorityqueue-2?view=net-8.0)  

### Example
``` cs
PriorityQueue<string, int> testQueue = new PriorityQueue<string, int>(10);
testQueue.Enqueue("World", 2);
testQueue.Enqueue("Hello", 1);
testQueue.Enqueue("!", 3);
while (testQueue.TryDequeue(out var element, out var priority))
    Debug.Log(element);
//result
//Hello
//World
//!
```

← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### ListExtensions Class

```csharp
public abstract sealed class ListExtensions
```

**Namespace:** [System.Collections.Generic](System.Collections.Generic)  
**Assembly:** VRage.Library.dll

#### Methods

|Member|Description|
|---|---|
|[static void AddArray&lt;T&gt;(this List&lt;T&gt;, T&#91&#93;)](System.Collections.Generic.ListExtensions.AddArray)||
|[static void AddArray&lt;T&gt;(this List&lt;T&gt;, T&#91&#93;, int)](System.Collections.Generic.ListExtensions.AddArray)||
|[static void AddHashsetCasting&lt;T1, T2&gt;(this List&lt;T1&gt;, HashSet&lt;T2&gt;)](System.Collections.Generic.ListExtensions.AddHashsetCasting)||
|[static void AddList&lt;T&gt;(this List&lt;T&gt;, List&lt;T&gt;)](System.Collections.Generic.ListExtensions.AddList)||
|[static void AddOrInsert&lt;T&gt;(this List&lt;T&gt;, T, int)](System.Collections.Generic.ListExtensions.AddOrInsert)||
|[static void AssertEmpty&lt;T&gt;(this List&lt;T&gt;)](System.Collections.Generic.ListExtensions.AssertEmpty)||
|[static T AtMod&lt;T&gt;(this List&lt;T&gt;, int)](System.Collections.Generic.ListExtensions.AtMod)||
|[static T AtMod&lt;T&gt;(this ListReader&lt;T&gt;, int)](System.Collections.Generic.ListExtensions.AtMod)||
|[static int BinaryIntervalSearch&lt;T&gt;(this IList&lt;T&gt;, T, IComparer&lt;T&gt; = default)](System.Collections.Generic.ListExtensions.BinaryIntervalSearch)||
|[static int BinaryIntervalSearch&lt;T&gt;(this IList&lt;T&gt;, Func&lt;T, bool&gt;)](System.Collections.Generic.ListExtensions.BinaryIntervalSearch)||
|[static int BinaryIntervalSearch&lt;T&gt;(this IList&lt;T&gt;, T, Comparison&lt;T&gt;)](System.Collections.Generic.ListExtensions.BinaryIntervalSearch)||
|[static void ClearAndTrim&lt;T&gt;(this List&lt;T&gt;, int)](System.Collections.Generic.ListExtensions.ClearAndTrim)||
|[static void EnsureCapacity&lt;T&gt;(this List&lt;T&gt;, int)](System.Collections.Generic.ListExtensions.EnsureCapacity)||
|[static ClearToken&lt;T&gt; GetClearToken&lt;T&gt;(this List&lt;T&gt;)](System.Collections.Generic.ListExtensions.GetClearToken)||
|[static T&#91&#93; GetInternalArray&lt;T&gt;(this List&lt;T&gt;)](System.Collections.Generic.ListExtensions.GetInternalArray)|_**Obsolete:** Due to changes required for XBOX this method is obsolete. Do not use it, as now it simply does list.ToArray_|
|[static void InsertInOrder&lt;T&gt;(this List&lt;T&gt;, T, IComparer&lt;T&gt;)](System.Collections.Generic.ListExtensions.InsertInOrder)||
|[static void InsertInOrder&lt;T&gt;(this List&lt;T&gt;, T)](System.Collections.Generic.ListExtensions.InsertInOrder)||
|[static bool IsSorted&lt;T&gt;(this List&lt;T&gt;, IComparer&lt;T&gt;)](System.Collections.Generic.ListExtensions.IsSorted)||
|[static bool IsValidIndex&lt;T&gt;(this List&lt;T&gt;, int)](System.Collections.Generic.ListExtensions.IsValidIndex)||
|[static T MaxBy&lt;T&gt;(this IEnumerable&lt;T&gt;, Func&lt;T, float&gt;)](System.Collections.Generic.ListExtensions.MaxBy)||
|[static TItem MaxBy&lt;TItem, TKey&gt;(this IEnumerable&lt;TItem&gt;, Func&lt;TItem, TKey&gt;, IComparer&lt;TKey&gt; = default)](System.Collections.Generic.ListExtensions.MaxBy)||
|[static T MinBy&lt;T&gt;(this IEnumerable&lt;T&gt;, Func&lt;T, float&gt;)](System.Collections.Generic.ListExtensions.MinBy)||
|[static void Move&lt;T&gt;(this List&lt;T&gt;, int, int)](System.Collections.Generic.ListExtensions.Move)||
|[static TValue Pop&lt;TValue&gt;(this List&lt;TValue&gt;)](System.Collections.Generic.ListExtensions.Pop)||
|[static void RemoveAtFast&lt;T&gt;(this List&lt;T&gt;, int)](System.Collections.Generic.ListExtensions.RemoveAtFast)||
|[static void RemoveAtFast&lt;T&gt;(this IList&lt;T&gt;, int)](System.Collections.Generic.ListExtensions.RemoveAtFast)||
|[static void RemoveIndices&lt;T&gt;(this List&lt;T&gt;, List&lt;int&gt;)](System.Collections.Generic.ListExtensions.RemoveIndices)||
|[static void SortNoAlloc&lt;T&gt;(this List&lt;T&gt;, Comparison&lt;T&gt;)](System.Collections.Generic.ListExtensions.SortNoAlloc)||
|[static void Swap&lt;T&gt;(this List&lt;T&gt;, int, int)](System.Collections.Generic.ListExtensions.Swap)||
|[static O&#91&#93; ToArray&lt;I, O&gt;(this IList&lt;I&gt;, Func&lt;I, O&gt;)](System.Collections.Generic.ListExtensions.ToArray)||


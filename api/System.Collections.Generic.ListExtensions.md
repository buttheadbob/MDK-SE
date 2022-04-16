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
|[static void AddArray(this List<T>, T[])](System.Collections.Generic.ListExtensions.AddArray)||
|[static void AddArray(this List<T>, T[], int)](System.Collections.Generic.ListExtensions.AddArray)||
|[static void AddHashsetCasting(this List<T1>, HashSet<T2>)](System.Collections.Generic.ListExtensions.AddHashsetCasting)||
|[static void AddList(this List<T>, List<T>)](System.Collections.Generic.ListExtensions.AddList)||
|[static void AddOrInsert(this List<T>, T, int)](System.Collections.Generic.ListExtensions.AddOrInsert)||
|[static void AssertEmpty(this List<T>)](System.Collections.Generic.ListExtensions.AssertEmpty)||
|[static T AtMod(this List<T>, int)](System.Collections.Generic.ListExtensions.AtMod)||
|[static T AtMod(this ListReader<T>, int)](System.Collections.Generic.ListExtensions.AtMod)||
|[static int BinaryIntervalSearch(this IList<T>, T, [IComparer<T>])](System.Collections.Generic.ListExtensions.BinaryIntervalSearch)||
|[static int BinaryIntervalSearch(this IList<T>, Func<T, System.Boolean>)](System.Collections.Generic.ListExtensions.BinaryIntervalSearch)||
|[static int BinaryIntervalSearch(this IList<T>, T, Comparison<T>)](System.Collections.Generic.ListExtensions.BinaryIntervalSearch)||
|[static void ClearAndTrim(this List<T>, int)](System.Collections.Generic.ListExtensions.ClearAndTrim)||
|[static void EnsureCapacity(this List<T>, int)](System.Collections.Generic.ListExtensions.EnsureCapacity)||
|[static ClearToken<T> GetClearToken(this List<T>)](System.Collections.Generic.ListExtensions.GetClearToken)||
|[static T[] GetInternalArray(this List<T>)](System.Collections.Generic.ListExtensions.GetInternalArray)|_**Obsolete:** Due to changes required for XBOX this method is obsolete. Do not use it, as now it simply does list.ToArray_|
|[static void InsertInOrder(this List<T>, T, IComparer<T>)](System.Collections.Generic.ListExtensions.InsertInOrder)||
|[static void InsertInOrder(this List<T>, T)](System.Collections.Generic.ListExtensions.InsertInOrder)||
|[static bool IsSorted(this List<T>, IComparer<T>)](System.Collections.Generic.ListExtensions.IsSorted)||
|[static bool IsValidIndex(this List<T>, int)](System.Collections.Generic.ListExtensions.IsValidIndex)||
|[static T MaxBy(this IEnumerable<T>, Func<T, System.Single>)](System.Collections.Generic.ListExtensions.MaxBy)||
|[static TItem MaxBy(this IEnumerable<TItem>, Func<TItem, TKey>, [IComparer<TKey>])](System.Collections.Generic.ListExtensions.MaxBy)||
|[static T MinBy(this IEnumerable<T>, Func<T, System.Single>)](System.Collections.Generic.ListExtensions.MinBy)||
|[static void Move(this List<T>, int, int)](System.Collections.Generic.ListExtensions.Move)||
|[static TValue Pop(this List<TValue>)](System.Collections.Generic.ListExtensions.Pop)||
|[static void RemoveAtFast(this List<T>, int)](System.Collections.Generic.ListExtensions.RemoveAtFast)||
|[static void RemoveAtFast(this IList<T>, int)](System.Collections.Generic.ListExtensions.RemoveAtFast)||
|[static void RemoveIndices(this List<T>, List<System.Int32>)](System.Collections.Generic.ListExtensions.RemoveIndices)||
|[static void SortNoAlloc(this List<T>, Comparison<T>)](System.Collections.Generic.ListExtensions.SortNoAlloc)||
|[static void Swap(this List<T>, int, int)](System.Collections.Generic.ListExtensions.Swap)||
|[static O[] ToArray(this IList<I>, Func<I, O>)](System.Collections.Generic.ListExtensions.ToArray)||


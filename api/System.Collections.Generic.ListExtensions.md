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
|[static void AddArray\<T>(this List\<T>, T\[\])](System.Collections.Generic.ListExtensions.AddArray)||
|[static void AddArray\<T>(this List\<T>, T\[\], int)](System.Collections.Generic.ListExtensions.AddArray)||
|[static void AddHashsetCasting\<T1, T2>(this List\<T1>, HashSet\<T2>)](System.Collections.Generic.ListExtensions.AddHashsetCasting)||
|[static void AddList\<T>(this List\<T>, List\<T>)](System.Collections.Generic.ListExtensions.AddList)||
|[static void AddOrInsert\<T>(this List\<T>, T, int)](System.Collections.Generic.ListExtensions.AddOrInsert)||
|[static void AssertEmpty\<T>(this List\<T>)](System.Collections.Generic.ListExtensions.AssertEmpty)||
|[static T AtMod\<T>(this List\<T>, int)](System.Collections.Generic.ListExtensions.AtMod)||
|[static T AtMod\<T>(this ListReader\<T>, int)](System.Collections.Generic.ListExtensions.AtMod)||
|[static int BinaryIntervalSearch\<T>(this IList\<T>, T, IComparer\<T> = default)](System.Collections.Generic.ListExtensions.BinaryIntervalSearch)||
|[static int BinaryIntervalSearch\<T>(this IList\<T>, Func\<T, bool>)](System.Collections.Generic.ListExtensions.BinaryIntervalSearch)||
|[static int BinaryIntervalSearch\<T>(this IList\<T>, T, Comparison\<T>)](System.Collections.Generic.ListExtensions.BinaryIntervalSearch)||
|[static void ClearAndTrim\<T>(this List\<T>, int)](System.Collections.Generic.ListExtensions.ClearAndTrim)||
|[static void EnsureCapacity\<T>(this List\<T>, int)](System.Collections.Generic.ListExtensions.EnsureCapacity)||
|[static ClearToken\<T> GetClearToken\<T>(this List\<T>)](System.Collections.Generic.ListExtensions.GetClearToken)||
|[static T\[\] GetInternalArray\<T>(this List\<T>)](System.Collections.Generic.ListExtensions.GetInternalArray)|_**Obsolete:** Due to changes required for XBOX this method is obsolete. Do not use it, as now it simply does list.ToArray_|
|[static void InsertInOrder\<T>(this List\<T>, T, IComparer\<T>)](System.Collections.Generic.ListExtensions.InsertInOrder)||
|[static void InsertInOrder\<T>(this List\<T>, T)](System.Collections.Generic.ListExtensions.InsertInOrder)||
|[static bool IsSorted\<T>(this List\<T>, IComparer\<T>)](System.Collections.Generic.ListExtensions.IsSorted)||
|[static bool IsValidIndex\<T>(this List\<T>, int)](System.Collections.Generic.ListExtensions.IsValidIndex)||
|[static T MaxBy\<T>(this IEnumerable\<T>, Func\<T, float>)](System.Collections.Generic.ListExtensions.MaxBy)||
|[static TItem MaxBy\<TItem, TKey>(this IEnumerable\<TItem>, Func\<TItem, TKey>, IComparer\<TKey> = default)](System.Collections.Generic.ListExtensions.MaxBy)||
|[static T MinBy\<T>(this IEnumerable\<T>, Func\<T, float>)](System.Collections.Generic.ListExtensions.MinBy)||
|[static void Move\<T>(this List\<T>, int, int)](System.Collections.Generic.ListExtensions.Move)||
|[static TValue Pop\<TValue>(this List\<TValue>)](System.Collections.Generic.ListExtensions.Pop)||
|[static void RemoveAtFast\<T>(this List\<T>, int)](System.Collections.Generic.ListExtensions.RemoveAtFast)||
|[static void RemoveAtFast\<T>(this IList\<T>, int)](System.Collections.Generic.ListExtensions.RemoveAtFast)||
|[static void RemoveIndices\<T>(this List\<T>, List\<int>)](System.Collections.Generic.ListExtensions.RemoveIndices)||
|[static void SortNoAlloc\<T>(this List\<T>, Comparison\<T>)](System.Collections.Generic.ListExtensions.SortNoAlloc)||
|[static void Swap\<T>(this List\<T>, int, int)](System.Collections.Generic.ListExtensions.Swap)||
|[static O\[\] ToArray\<I, O>(this IList\<I>, Func\<I, O>)](System.Collections.Generic.ListExtensions.ToArray)||


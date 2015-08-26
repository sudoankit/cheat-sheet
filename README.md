   ACM-ICPC Cheat Sheet
==========================

    Orange Juice 情報

![balloon](https://assets-cdn.github.com/images/icons/emoji/unicode/1f388.png?v5)
![balloon](https://assets-cdn.github.com/images/icons/emoji/unicode/1f388.png?v5)
![balloon](https://assets-cdn.github.com/images/icons/emoji/unicode/1f388.png?v5)
![balloon](https://assets-cdn.github.com/images/icons/emoji/unicode/1f388.png?v5)
![balloon](https://assets-cdn.github.com/images/icons/emoji/unicode/1f388.png?v5)
![balloon](https://assets-cdn.github.com/images/icons/emoji/unicode/1f388.png?v5)
![balloon](https://assets-cdn.github.com/images/icons/emoji/unicode/1f388.png?v5)
![balloon](https://assets-cdn.github.com/images/icons/emoji/unicode/1f388.png?v5)
![balloon](https://assets-cdn.github.com/images/icons/emoji/unicode/1f388.png?v5)
![balloon](https://assets-cdn.github.com/images/icons/emoji/unicode/1f388.png?v5)

![fried_shrimp](https://assets-cdn.github.com/images/icons/emoji/unicode/1f364.png?v5)
![sushi](https://assets-cdn.github.com/images/icons/emoji/unicode/1f363.png?v5)
![fish_cake](https://assets-cdn.github.com/images/icons/emoji/unicode/1f365.png?v5)
![rice_ball](https://assets-cdn.github.com/images/icons/emoji/unicode/1f359.png?v5)
![rice_cracker](https://assets-cdn.github.com/images/icons/emoji/unicode/1f358.png?v5)
![stew](https://assets-cdn.github.com/images/icons/emoji/unicode/1f372.png?v5)
![oden](https://assets-cdn.github.com/images/icons/emoji/unicode/1f362.png?v5)
![hamburger](https://assets-cdn.github.com/images/icons/emoji/unicode/1f354.png?v5)
![doughnut](https://assets-cdn.github.com/images/icons/emoji/unicode/1f369.png?v5)
![cookie](https://assets-cdn.github.com/images/icons/emoji/unicode/1f36a.png?v5)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [1. Basic](#1-basic)
  - [1.1 C++ Solution Template](#11-c-solution-template)
    - [1.1.1 Optional include list](#112-optional-include-list)
  - [1.2 Strings](#12-strings)
    - [1.2.1 C++ String](#121-c-string)
      - [Input string](#input-string)
      - [read one line](#read-one-line)
      - [Convert to char array](#convert-to-char-array)
    - [1.2.2 C String (Character Array)](#122-c-string-character-array)
      - [Input C String](#input-c-string)
      - [Convert to C++ string](#convert-to-c-string)
  - [1.3 STL Algorithm](#13-stl-algorithm)
    - [1.3.1 Permutation](#131-permutation)
    - [1.3.2 Binary Search](#132-binary-search)
    - [1.3.3 Lower Bound](#133-lower-bound)
    - [1.3.4 Swap](#134-swap)
    - [1.3.5 Heap](#135-heap)
    - [1.3.6 Sort](#136-sort)
    - [1.3.7 Compare](#137-compare)
      - [Using lambda expression](#using-lambda-expression)
      - [Compare function](#compare-function)
      - [Define operator <()](#define-operator-)
      - [Define operator()()](#define-operator)
  - [1.4 STL Containers](#14-stl-containers)
    - [1.4.1 Map](#141-map)
      - [Define a Map](#define-a-map)
      - [Commonly used method](#commonly-used-method)
      - [Red-black Tree](#red-black-tree)
      - [Hash Map (Unordered Map)](#hash-map-unordered-map)
      - [Deprecated Hash Map](#deprecated-hash-map)
    - [1.4.2 Pair](#142-pair)
    - [1.4.3 Vector](#143-vector)
      - [Constructor](#constructor)
      - [Methods](#methods)
    - [1.4.4 List](#144-list)
      - [Methods](#methods-1)
    - [1.4.5 Queue](#145-queue)
    - [1.4.6 Double-ended Queue](#146-double-ended-queue)
    - [1.4.7 Stack](#147-stack)
    - [1.4.8 Priority Queue](#148-priority-queue)
- [2. Advanced Data Structures](#2-advanced-data-structures)
  - [2.1 Heap](#21-heap)
  - [2.2 Tree](#22-tree)
    - [2.2.1 Tree Traversal](#221-tree-traversal)
  - [2.3 Trie / Trie Graph / AC Automaton](#23-trie--trie-graph--ac-automaton)
  - [2.4 Suffix Tree](#24-suffix-tree)
  - [2.5 Suffix Array](#25-suffix-array)
    - [Longest Common Prefix](#longest-common-prefix)
  - [2.6 Binary Indexed Tree](#26-binary-indexed-tree)
  - [2.7 Segment Tree](#27-segment-tree)
    - [2.7.1 Color](#271-color)
    - [2.7.2 Range Sum & Range Replace](#272-range-sum-&-range-replace)
    - [2.7.3 Range Minimum Query RMQ](#273-range-minimum-query-rmq)
- [3. Methodology](#3-methodology)
  - [3.0 Greedy](#30-greedy)
  - [3.1 Recursive](#31-recursive)
    - [3.1.1 Hanoi](#311-hanoi)
  - [3.2 Dynamic Programming](#32-dynamic-programming)
      - [7.2.1 树上的](#721-%E6%A0%91%E4%B8%8A%E7%9A%84)
  - [3.3 Divide and Conquer](#33-divide-and-conquer)
  - [3.4 Search](#34-search)
    - [3.4.1 binary search](#341-binary-search)
    - [3.4.2 双向 BFS](#342-%E5%8F%8C%E5%90%91-bfs)
    - [3.4.3 从终点开始搜](#343-%E4%BB%8E%E7%BB%88%E7%82%B9%E5%BC%80%E5%A7%8B%E6%90%9C)
    - [3.4.4 迭代加深搜索 (binary increase/decrease)](#344-%E8%BF%AD%E4%BB%A3%E5%8A%A0%E6%B7%B1%E6%90%9C%E7%B4%A2-binary-increasedecrease)
  - [3.5 Brute Force](#35-brute-force)
    - [3.5.1 子集生成](#351-%E5%AD%90%E9%9B%86%E7%94%9F%E6%88%90)
- [4. Graph](#4-graph)
  - [4.1 Union-find Set](#41-union-find-set)
    - [4.1.1 Union-find Set - application](#411-union-find-set---application)
  - [4.2 Minimium Spanning Tree](#42-minimium-spanning-tree)
    - [4.2.1 Prim's](#421-prims)
    - [4.2.2 Kruskal](#422-kruskal)
  - [4.3 Shortest Path](#43-shortest-path)
    - [4.3.1 任意两点](#431-%E4%BB%BB%E6%84%8F%E4%B8%A4%E7%82%B9)
    - [4.3.2 Bellman–Ford](#432-bellman%E2%80%93ford)
    - [4.3.3 SPFA](#433-spfa)
    - [4.3.4 Dijkstra](#434-dijkstra)
  - [4.4 Bipartite Graph 二分图](#44-bipartite-graph-%E4%BA%8C%E5%88%86%E5%9B%BE)
    - [4.4.1 Hungarian algorithm 匈牙利算法](#441-hungarian-algorithm-%E5%8C%88%E7%89%99%E5%88%A9%E7%AE%97%E6%B3%95)
  - [4.5 Maximum Flow Problem 最大流](#45-maximum-flow-problem-%E6%9C%80%E5%A4%A7%E6%B5%81)
    - [4.5.1 Dinic](#451-dinic)
    - [4.5.2 Minimum-Cost Maximum-Flow](#452-minimum-cost-maximum-flow)
  - [4.6 强连通分量 图的 割点, 桥, 双连通分支 ``https://www.byvoid.com/blog/biconnect``](#46-%E5%BC%BA%E8%BF%9E%E9%80%9A%E5%88%86%E9%87%8F-%E5%9B%BE%E7%9A%84-%E5%89%B2%E7%82%B9-%E6%A1%A5-%E5%8F%8C%E8%BF%9E%E9%80%9A%E5%88%86%E6%94%AF-httpswwwbyvoidcomblogbiconnect)
  - [4.7 Topological Sort / 拓扑排序](#47-topological-sort--%E6%8B%93%E6%89%91%E6%8E%92%E5%BA%8F)
  - [4.8 Euler Cycle/Path, Hamilton Cycle/Path](#48-euler-cyclepath-hamilton-cyclepath)
  - [4.9 find negative (weight) Cycle on a graph](#49-find-negative-weight-cycle-on-a-graph)
- [5. Number & Mathematics](#5-number-&-mathematics)
  - [5.1 BigInteger & BigDecimal](#51-biginteger-&-bigdecimal)
    - [5.1.1 C++ Big Integer](#511-c-big-integer)
    - [5.1.2 The Java Approach](#512-the-java-approach)
  - [5.2 Matrix](#52-matrix)
  - [5.3 Number Theory](#53-number-theory)
    - [5.3.1 欧拉函数 ?](#531-%E6%AC%A7%E6%8B%89%E5%87%BD%E6%95%B0-)
    - [5.3.2 欧几里得算法 / gcd](#532-%E6%AC%A7%E5%87%A0%E9%87%8C%E5%BE%97%E7%AE%97%E6%B3%95--gcd)
    - [5.3.3 扩展欧几里得算法](#533-%E6%89%A9%E5%B1%95%E6%AC%A7%E5%87%A0%E9%87%8C%E5%BE%97%E7%AE%97%E6%B3%95)
    - [5.3.4 求解不定方程](#534-%E6%B1%82%E8%A7%A3%E4%B8%8D%E5%AE%9A%E6%96%B9%E7%A8%8B)
    - [5.3.5 求解模线性方程（线性同余方程）](#535-%E6%B1%82%E8%A7%A3%E6%A8%A1%E7%BA%BF%E6%80%A7%E6%96%B9%E7%A8%8B%EF%BC%88%E7%BA%BF%E6%80%A7%E5%90%8C%E4%BD%99%E6%96%B9%E7%A8%8B%EF%BC%89)
    - [5.3.6 求解模的逆元](#536-%E6%B1%82%E8%A7%A3%E6%A8%A1%E7%9A%84%E9%80%86%E5%85%83)
    - [5.3.7 中国剩余定理](#537-%E4%B8%AD%E5%9B%BD%E5%89%A9%E4%BD%99%E5%AE%9A%E7%90%86)
    - [5.3.8 最小公倍数](#538-%E6%9C%80%E5%B0%8F%E5%85%AC%E5%80%8D%E6%95%B0)
    - [5.3.9 分解质因数](#539-%E5%88%86%E8%A7%A3%E8%B4%A8%E5%9B%A0%E6%95%B0)
    - [5.3.10 因数个数](#5310-%E5%9B%A0%E6%95%B0%E4%B8%AA%E6%95%B0)
    - [5.3.11 素数判定](#5311-%E7%B4%A0%E6%95%B0%E5%88%A4%E5%AE%9A)
    - [5.3.12 进制转换](#5312-%E8%BF%9B%E5%88%B6%E8%BD%AC%E6%8D%A2)
    - [5.3.13 A / C](#5313-a--c)
    - [5.3.14 质数表](#5314-%E8%B4%A8%E6%95%B0%E8%A1%A8)
    - [5.3.15 Fast Exponention](#5315-fast-exponention)
  - [5.4 博弈论](#54-%E5%8D%9A%E5%BC%88%E8%AE%BA)
- [6. Geometry](#6-geometry)
  - [6.1 2-Dimension Space](#61-2-dimension-space)
    - [6.1.1 Template of Point](#611-template-of-point)
    - [6.1.2 向量点乘 叉乘](#612-%E5%90%91%E9%87%8F%E7%82%B9%E4%B9%98-%E5%8F%89%E4%B9%98)
    - [6.1.3 dot product](#613-dot-product)
    - [6.1.4 cross product](#614-cross-product)
    - [6.1.5 直线公式](#615-%E7%9B%B4%E7%BA%BF%E5%85%AC%E5%BC%8F)
    - [6.1.6 Convex Hull](#616-convex-hull)
      - [Gift Wrapping](#gift-wrapping)
      - [QuickHull](#quickhull)
      - [Graham scan](#graham-scan)
- [7. Tricks & Miscellaneous](#7-tricks-&-miscellaneous)
  - [7.1 String](#71-string)
    - [7.1.1 KMP](#711-kmp)
    - [7.1.2 Boyer-Moore?](#712-boyer-moore)
    - [7.1.3 Longest palindromic substring (Manacher's algorithm)](#713-longest-palindromic-substring-manachers-algorithm)
  - [7.2 cantor_expansion / reverse_cantor_expansion](#72-cantor_expansion--reverse_cantor_expansion)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## 1. Basic

### 1.1 C++ Solution Template

```c++
#include <bits/stdc++.h>

#define DEBUG true
#define OJ_DEBUG

#define GET_BIT(n, i) (((n) & (1 << ((i)-1))) >> ((i)-1)) // i start from 1
#define SET_BIT(n, i) ((n) | (1 << ((i)-1)))
#define CLR_BIT(n, i) ((n) & ~(1 << ((i)-1)))
#define SHOW_A(x) {if (DEBUG) cout << #x << " = " << x << endl;}
#define SHOW_B(x, y) {if (DEBUG) cout << #x << " = " << x << ", " << #y << " = " << y << endl;}
#define SHOW_C(x, y, z) {if (DEBUG) cout << #x << " = " << x << ", " << #y << " = " << y << ", " << #z << " = " << z << endl;}
#define REACH_HERE {if (DEBUG) cout << "REACH_HERE! line: " << __LINE__ << endl;}

const double E = 1e-8;
const double PI = acos(-1);

using namespace std;

int main() {
    ios::sync_with_stdio(false);
    
}
```

#### 1.1.1 Optional include list

> Use it when there is no `bits/stdc++.h`

```c++
#include <iostream>
#include <cstring>
#include <cmath>
#include <algorithm>
#include <climits>
#include <stack>
#include <queue>
#include <vector>
#include <set>
#include <map>
#include <list>
#include <cassert>
```

### 1.2 Strings

#### 1.2.1 C++ String

##### Input string

get one string with no space and new-line.

```c++
string a;
cin >> a;
cout << "[C++] You have input \"" << a << "\", "
     << ", whose length is " << a.length() << endl;
```

Input
```
hello world
new line
```

Output
```
You have input "hello", , whose length is 5
```

##### read one line

getline()

```C++
string a;
getline(cin, a);
cout << a << endl;
```

Input

```
Hello World!!!
```

Output

```
Hello World!!!
```

##### Convert to char array

```C++
string cppstr = "this is a string";
char target[1024];
strcpy(target, cppstr.c_str());
```

#### 1.2.2 C String (Character Array)

##### Input C String

gets()

> Reads characters from the standard input (stdin) and stores them as a C string into str until a newline character or the end-of-file is reached.

```c++
char b[10];
gets(b);
cout << "[C++] You have input \"" << b << "\", "
     << ", whose length is " << strlen(b) << endl;
```

Input

```
 world
new line
```

Output

```
You have input " world", , whose length is 6
```

Note: There is a space in front of "world", which will be part of the string.
However, using gets() is "unsafe", but we are not to discuss the details here.

##### Convert to C++ string

```c++
char arrstr[] = "this is a string";
string target = string(arr);
```

### 1.3 STL Algorithm

> Include the algorithm library if you do not use the solution template.

```C++
#include <algorithm>
```

#### 1.3.1 Permutation

Usage
```c++
bool next_permutation (BidirectionalIterator first, BidirectionalIterator last);
bool next_permutation (BidirectionalIterator first, BidirectionalIterator last, Compare comp);
```

Example

```C++
// next_permutation example
#include <iostream>     // std::cout
#include <algorithm>    // std::next_permutation, std::sort

int main () {
  int myints[] = {1,2,3};

  std::sort (myints,myints+3);

  std::cout << "The 3! possible permutations with 3 elements:\n";
  do {
    std::cout << myints[0] << ' ' << myints[1] << ' ' << myints[2] << '\n';
  } while ( std::next_permutation(myints,myints+3) );

  std::cout << "After loop: " << myints[0] << ' ' << myints[1] << ' ' << myints[2] << '\n';

  return 0;
}
```

Output

```
The 3! possible permutations with 3 elements:
1 2 3
1 3 2
2 1 3
2 3 1
3 1 2
3 2 1
After loop: 1 2 3
```

#### 1.3.2 Binary Search

Usage

```C++
bool binary_search (ForwardIterator first, ForwardIterator last, const T& val, Compare comp);
// return true if found, false if not
```

#### 1.3.3 Lower Bound

> Returns an iterator pointing to the first element in the range [first,last) which does not compare less than val.

Usage

```c++
ForwardIterator lower_bound (ForwardIterator first, ForwardIterator last,
                             const T& val);
ForwardIterator lower_bound (ForwardIterator first, ForwardIterator last,
                             const T& val, Compare comp);
```

`binary_search` is defined by:

```c++
template <class ForwardIterator, class T>
  bool binary_search (ForwardIterator first, ForwardIterator last, const T& val) {
  first = std::lower_bound(first,last,val);
  return (first!=last && !(val<*first));
}
```

#### 1.3.4 Swap

Usage

```c++
void swap (T& a, T& b);
void iter_swap (ForwardIterator1 a, ForwardIterator2 b);
```

`iter_swap` example

```C++
int myints[]={10,20,30,40,50 };              //   myints:  10  20  30  40  50
std::vector<int> myvector (4,99);            // myvector:  99  99  99  99

std::iter_swap(myints,myvector.begin());     //   myints: [99] 20  30  40  50
                                             // myvector: [10] 99  99  99

std::iter_swap(myints+3,myvector.begin()+2); //   myints:  99  20  30 [99] 50
                                             // myvector:  10  99 [40] 99
```

#### 1.3.5 Heap

// not completed

// TODO add method and example to maintain the size of vector

* make_heap: Rearranges the elements in the range [first,last) in such a way that they form a heap. The element with the highest value is always pointed by first.
* pop_heap: Rearranges the elements in the heap range [first,last) in such a way that the part considered a heap is shortened by one: The element with the highest value is moved to (last-1).
* push_heap: Given a heap in the range [first,last-1), this function extends the range considered a heap to [first,last) by placing the value in (last-1) into its corresponding location within it.
* sort_heap: Sorts the elements in the heap range [first,last) into ascending order.

Usage

```c++
void make_heap (RandomAccessIterator first, RandomAccessIterator last, Compare comp);
void pop_heap (RandomAccessIterator first, RandomAccessIterator last, Compare comp);
void push_heap (RandomAccessIterator first, RandomAccessIterator last, Compare comp);
void sort_heap (RandomAccessIterator first, RandomAccessIterator last); Compare comp);
```

Self implementation of heap is available in section 2.

Note: Priority queue is more recoomeneded.


#### 1.3.6 Sort

> Sorts the elements in the range [first,last) into ascending order.
`stable_sort` preserves the relative order of the elements with equivalent values.

Usage
```c++
void sort (RandomAccessIterator first, RandomAccessIterator last);
void sort (RandomAccessIterator first, RandomAccessIterator last, Compare comp);
void stable_sort ( RandomAccessIterator first, RandomAccessIterator last );
void stable_sort ( RandomAccessIterator first, RandomAccessIterator last,
                   Compare comp );
```

#### 1.3.7 Compare

##### Using lambda expression

``` c++
auto cmp = [](const T& a, const T& b) { return true; };
set<T, decltype(cmp)> a_set_with_customized_comparator(cmp);
```

##### Compare function

> Binary function that accepts two elements in the range as arguments, and returns a value convertible to bool. It should returns true if the first element is considered to be "smaller" than the second one.

Using by `sort`, `make_heap` and etc.

```c++
bool myfunction (int i,int j) { return (i<j); }
```

##### Define operator <()

Member function
> recommended // can use for priority_queue, sort, <ADD MORE HERE>

```c++
struct Edge {
   int from, to, weight;
	bool operator<(Edge that) const {
        return weight > that.weight;
    }
};
```

verbal version

```c++
struct Edge {
   int from, to, weight;
	bool operator<(const Edge& that) const {
        return this->weight > that.weight;
    }
};
```

Non-member function

```c++
struct Edge {
    int from, to, weight;
    friend bool operator<(Edge a, Edge b) {
        return a.weight > b.weight;
    }
};
```

##### Define operator()()

> You can use comparison function for STL containers by passing them as the first argument of the constructor, and specifying the function type as the additional template argument. For example:

```c++
set<int, bool (*)(int, int)> s(cmp);
```

> A functor, or a function object, is an object that can behave like a function. This is done by defining operator()() of the class. In this case, implement operator()() as a comparison function:

```c++
vector<int> occurrences;
struct cmp {
    bool operator()(int a, int b) {
        return occurrences[a] < occurrences[b];
    }
};
set<int, cmp> s;
priority_queue<int, vector<int>, cmp> pq;
```

Used by `priority_queue `.

### 1.4 STL Containers

A container is a holder object that stores a collection of other objects (its elements). They are implemented as class templates, which allows a great flexibility in the types supported as elements.

#### 1.4.1 Map

> Maps are associative containers that store elements formed by a combination of a key value and a mapped value, following a specific order.

```c++
#include <map>
```

##### Define a Map

```c++
template < class Key,                                     // map::key_type
           class T,                                       // map::mapped_type
           class Compare = less<Key>,                     // map::key_compare
           class Alloc = allocator<pair<const Key,T> >    // map::allocator_type
           > class map;
```

##### Commonly used method

```C++
begin()
end()

empty()
size()

operator[] // if not found, insert one

insert(pair<first type, second type)
erase()
clear()

find() // if not found, return end()
count() // return 1 or 0
```

// TODO add more interface


##### Red-black Tree

C++ map is implemented as a red-black tree.

A red–black tree is a data structure which is a type of self-balancing binary search tree.

In addition to the requirements imposed on a binary search tree the following must be satisfied by a red–black tree:

1. A node is either red or black.
2. The root is black. (This rule is sometimes omitted. Since the root can always be changed from red to black, but not necessarily vice-versa, this rule has little effect on analysis.)
3. All leaves (NIL) are black. (All leaves are same color as the root.)
4. Every red node must have two black child nodes.
5. Every path from a given node to any of its descendant leaves contains the same number of black nodes.


##### Hash Map (Unordered Map)

> Unordered map is implemented as a hash table.

```c++
#include <unordered_map>
```

> Unordered maps are associative containers that store elements formed by the combination of a key value and a mapped value, and which allows for fast retrieval of individual elements based on their keys.

```c++
template < class Key,                                    // unordered_map::key_type
           class T,                                      // unordered_map::mapped_type
           class Hash = hash<Key>,                       // unordered_map::hasher
           class Pred = equal_to<Key>,                   // unordered_map::key_equal
           class Alloc = allocator< pair<const Key,T> >  // unordered_map::allocator_type
           > class unordered_map;

```

##### Commonly used method

``` C++
// most are similar to map
```

// TODO add more interface


##### Deprecated Hash Map

```c++
#include <ext/hash_map>
__gnu_cxx::hash_map<string, int> months;
months["january"] = 31;
months["february"] = 28;
```


#### 1.4.2 Pair

#### 1.4.3 Vector

##### Constructor
```c++
std::vector<int> second (4,100);  // four ints with value 100
```

##### Methods

* begin(), end()
* front(), back()
* clear()
* size()
* push_back(const value_type& val)
* pop_back()

#### 1.4.4 List

> List containers are implemented as doubly-linked lists.

##### Methods

* begin(), end()
* front(), back()
* clear()
* push_front(const value_type& val)
* push_back(const value_type& val)
* pop_front(): remove the first element.
* pop_back(): remove the last element.
* remove(const value_type& val): remove all elements of value val.
* insert(iterator position, const value_type& val)
* size()
* reverse()
* sort(), sort (Compare comp)
* 
* resize()
* reserve()

#### 1.4.5 Queue

```C++
#include <queue>
```
Constructor
```C++
queue<int> my_queue;
queue<int, list<int> > my_queue (my_list);
// use list<int> as container, copy my_list into my_queue
```
Methods
```C++
void queue::push(const value_type& val);
void queue::pop();
bool queue::empty() const;
size_type queue::size() const;
const_reference& queue::front() const;
```

#### 1.4.6 Double-ended Queue

```C++
#include <dequeue>
```


#### 1.4.7 Stack

``` c++
#include <stack>
```

Constructor
```C++
stack<int, vector<int> > my_stack (my_data);
// use vector<int> as container, copy my_data into my_stack

bool stack::empty() const;
size_type stack::size() const;
const_reference& stack::top() const;
void stack::push (const value_type& val);
void stack::pop();
```

#### 1.4.8 Priority Queue

``` c++
#include <queue>
```

```C++
// constructor
priority_queue<int> my_priority_queue;
priority_queue<int, vector<int>, greater<int> > two_priority_queue; // if use greater<int>, must have vector<int>
priority_queue<My_type, vector<My_type>, Comparator_class> my_priority_queue (my_data.begin(), my_data.end()); // use Comparator_class as comparator, use vector<My_type> as container, copy my_data into my_priority_queue

bool priority_queue::empty() const; // return true if empty, false if not
size_type priority_queue::size() const; // return size of queue
const_reference priority_queue::top() const; // returns a constant reference to the top element
void priority_queue::push(const value_type& val); // inserts a new element, initialize to val
void priority_queue::pop(); // removes the element on top
```
```C++
struct My_type {
    int weight;
    int other;
};

struct My_class_for_compare {
    public:
        bool operator() (My_type a, My_type b) {
            return a.weight < b.weight;
        }
};

vector<My_type> my_vector = {(My_type){2, 789}, (My_type){1, 127}, (My_type){3, 456}};

priority_queue<My_type, vector<My_type>, My_class_for_compare> one_priority_queue (my_vector.begin(), my_vector.end());
one_priority_queue.push((My_type){4, 483});
while (one_priority_queue.size() != 0) {
    My_type temp = one_priority_queue.top();
    one_priority_queue.pop();
    SHOW_B(temp.weight, temp.other);
}

vector<int> my_int = {2, 3, 1};

priority_queue<int, vector<int>, greater<int> > two_priority_queue (my_int.begin(), my_int.end());
while (two_priority_queue.size() != 0) {
    SHOW_A(two_priority_queue.top());
    two_priority_queue.pop();
}

priority_queue<int> three_priority_queue (my_int.begin(), my_int.end());
while (three_priority_queue.size() != 0) {
    SHOW_A(three_priority_queue.top());
    three_priority_queue.pop();
}


// output
// temp.weight = 4, temp.other = 483
// temp.weight = 3, temp.other = 456
// temp.weight = 2, temp.other = 789
// temp.weight = 1, temp.other = 127
// two_priority_queue.top() = 1
// two_priority_queue.top() = 2
// two_priority_queue.top() = 3
// three_priority_queue.top() = 3
// three_priority_queue.top() = 2
// three_priority_queue.top() = 1
```

## 2. Advanced Data Structures

### 2.1 Heap

TODO make it general

```c++
struct HiHeap {
    // a max-heap
    int _size_;
    int _max_size_;
    int* value;

    HiHeap(int max_size) : _max_size_(max_size) {
        _size_ = 0;
        value = new int[_max_size_+1];
    }

    ~HiHeap() {
        delete[] value;
    }
    
    void clear() {
        _size_ = 0;
        _max_size_ = -1;
        delete[] value;
    }

    int top() {
        return value[1];
    }

    bool push(int var) {
        if (_size_ == _max_size_)
            return false;
        _size_++;
        value[_size_] = var;
        adjust_up(_size_);
        return true;
    }

    bool pop() {
        if (_size_ == 0)
            return false;
        swap(value[1], value[_size_]);
        _size_--;
        adjust_down(1);
    }

    void adjust_it(int cur) {
        adjust_up(cur);
        adjust_down(cur);
    }

    void adjust_down(int cur) {
        int left = cur * 2;
        int right= cur * 2 + 1;

        if (left > _size_)
            return ;
        if (right > _size_)
            right = left;
        
        int max_one = cur;
        if (value[max_one] < value[left])
            max_one = left;
        if (value[max_one] < value[right])
            max_one = right;

        if (max_one == cur)
            return ;
        
        swap(value[max_one], value[cur]);
        adjust_down(max_one);
    }

    void adjust_up(int cur) {
        if (cur == 1)
            return ;
        
        int father = cur / 2;
        if (value[cur] <= value[father])
            return ;
        
        swap(value[cur], value[father]);
        adjust_up(father);
    }

    int size() {
        return _size_;
    }
};
```

### 2.2 Tree

#### 2.2.1 Tree Traversal

### 2.3 Trie / Trie Graph / AC Automaton

> O(NL+M) - NL: total len of words in dict, M: len of article

```c++
// 
// input: n, q, string x n, string x q
// output: for each query, print number of string whose prefix is the query
// 
// Sample Input
// 5
// babaab
// babbbaaaa
// abba
// aaaaabaa
// babaababb
// 5
// babb
// baabaaa
// bab
// bb
// bbabbaab
// Sample Output
// 1
// 0
// 3
// 0
// 0
// 
// 
// 
// check if any word in dict appear in article
// 
// Sample Input
// 6
// aaabc
// aaac
// abcc
// ac
// bcd
// cd
// aaaaaaaaaaabaaadaaac
// 
// Sample Output
// YES
// 

using namespace std;

#define HHH 1000002
struct TrieNode
{
    char val; // 'a' ~ 'z'
    bool ended; // is a word ended here
    int count; // number of word ended here
    int childCount; // number of word contianing this prefix

    int next[26]; // index of child node, 'a' ~ 'z'

    int prev; // parent node // for trie-graph
    bool suffixEnded;// suffix node is an end // for trie-graph
    int suffix[26]; // suffix node // for trie-graph

    TrieNode() {
        val = 0;
        memset(next, -1, sizeof(next));
        ended = false;
        count = 0;
        childCount = 0;

        prev = -1;
        suffixEnded = false;
        memset(suffix, -1, sizeof(suffix));
    }

    void show() {
        cerr <<
        "Val: " << val <<
        ", prev = " << prev <<
        ", ended = " << ended <<
        ", count = " << count <<
        ", childCount = " << childCount
        << "\n\t ";
        for (int i = 0; i < 4; i++)
            cerr << (char)('a' + i) << ":" << next[i] << " ";
        cerr
        << "\n\tsuffix suffixEnded = " << suffixEnded << "\n"
        << "\t ";
        for (int i = 0; i < 4; i++)
            cerr << (char)('a' + i) << ":" << suffix[i] << " ";
        cerr << endl;
    }
};

struct Trie
{
    TrieNode node[HHH];
    int size; // the index of last node
    int add(string& s) { // return index of new node
        int preIndex = 0;
        for (int i = 0; i < s.length(); i++) {
            TrieNode& pre = node[preIndex];
            int& curIndex = pre.next[s[i] - 'a'];
            if (curIndex == -1) {
                size++;
                curIndex = size;
            }
            TrieNode& cur = node[curIndex];
            cur.val = s[i];
            cur.childCount++;

            preIndex = curIndex;
        }
        node[preIndex].ended = true;
        node[preIndex].count++;
        node[0].childCount++;
        return preIndex;
    };

    void buildSuffix() {
        queue<int> q;
        for (int i = 0; i < 26; i++) {
            int& next = node[0].next[i];
            int& suffix = node[0].suffix[i];

            suffix = 0;
            if (next == -1)
                next = 0;
            else {
                q.push(next);
                node[next].prev = 0;
            }
        }

        while (q.size()) {
            int cur = q.front(); q.pop();
            int prev = node[cur].prev;
            int prevSuffix = node[prev].suffix[node[cur].val - 'a'];
            if (node[prevSuffix].ended)
                node[cur].suffixEnded = true;

            for (int i = 0; i < 26; i++) {
                int& next = node[cur].next[i];
                int& suffix = node[cur].suffix[i];

                suffix = node[prevSuffix].next[i];
                if (next == -1)
                    next = suffix;
                else {
                    q.push(next);
                    node[next].prev = cur;
                }
            }
        }
    }

    int get(string& s) { // get index of node
        int preIndex = 0;
        for (int i = 0; i < s.length() && preIndex != -1; i++)
            preIndex = node[preIndex].next[s[i] - 'a'];
        return preIndex;
    };

    bool match(string& s) {
        for (int i = 0, cur = 0; i < s.length(); i++) {
            cur = node[cur].next[s[i] - 'a'];
            if (node[cur].ended || node[cur].suffixEnded)
                return true;
        }
        return false;
    }

    Trie() {
        size = 0;
    };

    void show() {
        for (int i = 0; i <= size; i++) {
            show_A(i);
            node[i].show();
        }
    }
};

int n, q;
Trie t;

int main() {
    cin >> n;

    string temp;
    for (int i = 0; i < n; i++) {
        cin >> temp;
        t.add(temp);
    }

    cin >> q;
    for (int i = 0; i < q; i++) {
        cin >> temp;
        int index = t.get(temp);

        if (index == -1)
            cout << 0 << endl; // not found 
        else
            cout << t.node[index].childCount << endl; // found
    }
    
    
    // check if any word in dict appear in article
    t.buildSuffix();
    
    string article; cin >> article;
    if (t.match(article))
        cout << "YES" << endl;
    else
        cout << "NO" << endl;
}
```

```c++
// http://blog.csdn.net/u010700335/article/details/38930175

const int maxn = 26;//26个小写字母或者大写字母，再加上0~9就是72
//定义字典树结构体
typedef struct Trie
{
    bool flag;//从根到此是否为一个单词
    Trie *next[maxn];//有多少个分支
}Trie;
// 声明一个根，不含任何信息
Trie *root;
//初始化该根
void trie_init()
{
    int i;
    root = new Trie;
    root->flag = false;
    for(i=0;i<maxn;i++)
        root->next[i] = NULL;
}
// 插入一个字符串
void trie_insert(char *word)
{
    //int i = 0;
    //while(word[i] != '\0')
    Trie *tem = root;
    int i;
    while(*word != '\0')
    {
       // cout << "root**" << tem->next[0];
        if(tem->next[*word-'a'] == NULL)// 为空才建立
        {
            Trie *cur = new Trie;
            cur->flag = false;
            for(i=0;i<maxn;i++)
                cur->next[i] = NULL;
            tem->next[*word-'a'] = cur;
        }
        tem = tem->next[*word-'a'];
        //cout << *word << "**";
        word++;
    }
    tem->flag = true;//插入一个完整的单词
}
// 查找一个字符串
bool trie_search(char *word)
{
    Trie *tem = root;
    int i;
    for(i=0; word[i]!='\0'; i++)
    {
        if(tem==NULL || tem->next[word[i]-'a']==NULL)
            return false;
        tem = tem->next[word[i]-'a'];
    }
    return tem->flag;
}


void trie_del(Trie *cur)
{
    int i;
    for(i=0;i<maxn;i++)
    {
        if(cur->next[i] != NULL)
            trie_del(cur->next[i]);
    }
    delete cur;
}


int main()
{
    int i,n;
    char tmp[50];
    trie_init();
    cout << "请输入初始化字典树的字符串(字符0结束）：" << endl;
    while(cin >> tmp)
    {
        //cout << tmp << endl;
        if(tmp[0] == '0' && tmp[1] =='\0') break;
        trie_insert(tmp);
    }
    cout << "请输入要查找的字符串：" << endl;
    while(cin >> tmp)
    {
        //cout << tmp << endl;
        if(tmp[0] == '0' && tmp[1] =='\0') break;
        if(trie_search(tmp))
            cout << "查找成功！再次输入查找，字符0结束查找：" << endl;
        else
            cout << "查找失败！再次输入查找，字符0结束查找：" << endl;
    }
    return 0;
}
```

### 2.4 Suffix Tree

### 2.5 Suffix Array

```c++
#define MAXN  65536
#define MAXLG 17
char A[MAXN];
struct entry {
    int nr[2], p;
} L[MAXN];
int P[MAXLG][MAXN], N, i, stp, cnt;
int cmp(struct entry a, struct entry b) {
    return a.nr[0] == b.nr[0] ? (a.nr[1] < b.nr[1] ? 1 : 0) : (a.nr[0] < b.nr[0] ? 1 : 0);
}
int main(void) {
    gets(A);
    for (N = strlen(A), i = 0; i < N; i ++)
        P[0][i] = A[i] - 'a';
    for (stp = 1, cnt = 1; cnt >> 1 < N; stp ++, cnt <<= 1) {
        for (i = 0; i < N; i ++) {
            L[i].nr[0] = P[stp - 1][i];
            L[i].nr[1] = i + cnt < N ? P[stp - 1][i + cnt] : -1;
            L[i].p = i;
        }
        sort(L, L + N, cmp);
        for (i = 0; i < N; i ++)
            P[stp][L[i].p] = i > 0 && L[i].nr[0] == L[i - 1].nr[0] && L[i].nr[1] == L[i - 1].nr[1] ? P[stp][L[i - 1].p] : i;
    }
    return 0;
}
```

#### Longest Common Prefix

```c++
int lcp(int x, int y) {
	int k, ret = 0;
	if (x == y) return N - x;
	for (k = stp - 1; k >= 0 && x < N && y < N; k --)
        if (P[k][x] == P[k][y])
            x += 1 << k, y += 1 << k, ret += 1 << k;
	return ret;
}
```

### 2.6 Binary Indexed Tree

> Binary Indexed Tree

> O(logN) to query and update SUM(a[1]~a[i])

```C++
#define MAX_INDEX nnn

int tree[MAX_INDEX + 1]; // 1 <= I <= MAX_INDEX

int low_bit(int i) {
    return i & -i;
}

int query(int i) {
    int ans = 0;
    for (; i > 0; i -= low_bit(i))
        ans += tree[i];
    return ans;
}

void insert(int i, int value) {
    for (; i <= MAX_INDEX; i += low_bit(i))
        tree[i] += value;
}
```

> 修改区间+查询点，
> 
> 【1】修改操作：将A[l..r]之间的全部元素值加上c；
> 
> 【2】求和操作：求此时A[x]的值。
> 
> 这个模型中需要设置一个辅助数组B：B[i]表示A[1..i]到目前为止共被整体加了多少

```C++
#define INTERVAL_LIMIT 100005

int tree_add_i_n[INTERVAL_LIMIT];

int low_bit(int i) {
    return i & -i;
}

int query(int i, int* tree, int UP_LIMIT) {
    int ans = 0;
    for (; i > 0; i -= low_bit(i))
        ans += tree[i];
    return ans;
}

void insert(int i, int value, int* tree, int UP_LIMIT) {
    for (; i <= UP_LIMIT; i += low_bit(i))
        tree[i] += value;
}

int main() {
    memset(tree_add_in, 0, sizeof(tree_add_in));
    insert(3, 1, tree_add_in, INTERVAL_LIMIT);
    insert(5, -1, tree_add_in, INTERVAL_LIMIT);
    insert(4, 2, tree_add_in, INTERVAL_LIMIT);
    insert(6, -2, tree_add_in, INTERVAL_LIMIT);

    for (int i = 1; i <= 7; i++)
        SHOW_B(i, query(i, tree_add_in, INTERVAL_LIMIT));
}
```

> 修改区间+查询区间
> 
> b[i]: add b[i] to a[i], a[i+1], ..., a[n]
> 
> so
> 
> sigma(i): a[1] + a[2] + ... + a[i]
> 
> sigma(i) = ib[1] + (i-1)b[2] + ... + 2b[i-1] + b[i]
> 
> sigma(i) = (i+1){b[1] + b[2] + ... + b[i]} - {b[1] + 2b[2] + ... + ib[i]}
> 
> so use one more tree c[i]
> 
> c[i]: 1b[1] + 2b[2] + ... + ib[i]

### 2.7 Segment Tree

> place holder : simple version

#### 2.7.1 Color

```c++
const int MAX = 100000;

struct node {
    int left, right;
    int color;
    bool cover;
};

node nodes[3*MAX];

void build_tree(int left, int right, int u) {
    nodes[u].left = left;
    nodes[u].right = right;
    nodes[u].color = 1;
    nodes[u].cover = true;
    if (left == right) return;
    int mid = (left + right)/2;
    build_tree(left, mid, 2*u);
    build_tree(mid+1, right, 2*u + 1);
}

void get_down(int u) {
    int value = nodes[u].color;
    nodes[u].cover = false;
    nodes[2*u].color = value;
    nodes[2*u].cover = true;
    nodes[2*u + 1].color = value;
    nodes[2*u + 1].cover = true;
}

void update(int left, int right, int value, int u) {
    if (left <= nodes[u].left && nodes[u].right <= right) {
        nodes[u].color = value;
        nodes[u].cover = true;
        return;
    }
    if (nodes[u].color == value) return;  // optimize purpose
    //SHOW(u);
    if (nodes[u].cover) get_down(u);
    if (left <= nodes[2*u].right) {
        update(left, right, value, 2*u);
    }
    if (right >= nodes[2*u+1].left) {
        update(left, right, value, 2*u + 1);
    }
    nodes[u].color = nodes[2*u].color | nodes[2*u+1].color;
}

void query(int left, int right, int &sum, int u) {
    if (nodes[u].cover) {
        sum |= nodes[u].color;
        return;
    }
    if (left <= nodes[u].left && nodes[u].right <= right) {
        sum |= nodes[u].color;
        return;
    }
    if (left <= nodes[2*u].right) {
        query(left, right, sum, 2*u);
    }
    if (right >= nodes[2*u+1].left) {
        query(left, right, sum, 2*u + 1);
    }
}

// Usage
// build_tree(1, L, 1);
// update(a, b, new_color, 1);
// query(a, b, sum_as_reference, 1);

// only for this question
int bit_count(int sum) {
    int ans = 0;
    while (sum) {
        if (sum%2) ans++;
        sum = sum >> 1;
    }
    return ans;
}

int main() {
    int L, T, O;
    cin >> L >> T >> O;
    build_tree(1, L, 1);
    while (O--) {
        char op;
        int a, b, c;
        cin >> op;
        if (op == 'C') {
            cin >> a >> b >> c;
            if (a > b) swap(a, b);
            update(a, b, 1<<(c-1), 1);
        } else {
            cin >> a >> b;
            if (a > b) swap(a, b);
            int sum = 0;
            query(a, b, sum, 1);
            cout << bit_count(sum) << endl;
        }
    }
    return 0;
}
```

#### 2.7.2 Range Sum & Range Replace

```c++
const int MAX = 30005;

struct node {
    int left, right;
    long long sum;
    int lazy;
    bool dirty;
};

node nodes[4*MAX];

void build_tree(int left, int right, int u) {
    nodes[u].left = left;
    nodes[u].right = right;
    nodes[u].sum = 0;
    nodes[u].lazy = 0;
    nodes[u].dirty = false;
    if (left == right) return;
    int mid = (left + right)/2;
    build_tree(left, mid, 2*u);
    build_tree(mid+1, right, 2*u + 1);
}

void get_down(int u) {
    if (!nodes[u].dirty) return;
    nodes[2*u].sum = (long long) nodes[u].lazy * (nodes[2*u].right - nodes[2*u].left + 1);
    // if update not replace use +=
    nodes[2*u].lazy = nodes[u].lazy;
    nodes[2*u].dirty = true;
    nodes[2*u + 1].sum = (long long) nodes[u].lazy * (nodes[2*u + 1].right - nodes[2*u + 1].left + 1);
    nodes[2*u + 1].lazy = nodes[u].lazy;
    nodes[2*u + 1].dirty = true;
    nodes[u].dirty = false;
}

void update(int left, int right, int value, int u) {
    if (left <= nodes[u].left && nodes[u].right <= right) {
        nodes[u].sum = (long long)value * (nodes[u].right - nodes[u].left + 1);
        // if update not replace use +=
        nodes[u].lazy = value;
        nodes[u].dirty = true;
        return;
    }
    get_down(u);
    if (left <= nodes[2*u].right) {
        update(left, right, value, 2*u);
    }
    if (right >= nodes[2*u+1].left) {
        update(left, right, value, 2*u + 1);
    }
    nodes[u].sum = nodes[2*u].sum + nodes[2*u+1].sum;
}

void query(int left, int right, long long &sum, int u) {
    if (left <= nodes[u].left && nodes[u].right <= right) {
        sum += nodes[u].sum;
        return;
    }
    get_down(u);
    if (left <= nodes[2*u].right) {
        query(left, right, sum, 2*u);
    }
    if (right >= nodes[2*u+1].left) {
        query(left, right, sum, 2*u + 1);
    }
}

// Usage
// build_tree(1, L, 1);
// update(a, b, new_value, 1);
// query(a, b, sum_as_reference, 1);
```

#### 2.7.3 Range Minimum Query RMQ

> place holder

## 3. Methodology

### 3.0 Greedy

> It's Art.

### 3.1 Recursive

#### 3.1.1 Hanoi

```C++
void hanoi(int n, char x, char y, char z) { // 将 x 上编号 1 至 n 的圆盘移到 z, y 作辅助塔
    if (n == 1)
        printf("%d from %c to %c\n", n, x, z); // 将编号为 n 的圆盘从 x 移到 z
    else {
        hanoi(n-1, x, z, y); // 将 x 上编号 1 至 n-1 的圆盘移到 y, z 作辅助塔
        printf("%d from %c to %c\n", n, x, z); // 将编号为 n 的圆盘从 x 移到 z
        hanoi(n-1, y, x, z); // 将 y 上编号 1 至 n-1 的圆盘移到 z, x 作辅助塔
    }
}
```

### 3.2 Dynamic Programming

##### 7.2.1 树上的

> 这是什么GUI (Graphical User Interface)

### 3.3 Divide and Conquer

### 3.4 Search

#### 3.4.1 binary search

```C++
int up_limit = ;
int down_limit = ;
int cur, pre;

while (true) {
    cur = (down_limit + up_limit) / 2;

    bool ok = search();

    if (ok)
        up_limit = cur;
    else
        down_limit = cur;
    pre = cur;
    cur = (down_limit + up_limit) / 2;
    if (pre == cur)
        return up_limit;
}
```

#### 3.4.2 双向 BFS

#### 3.4.3 从终点开始搜

#### 3.4.4 迭代加深搜索 (binary increase/decrease)

> placeholder

### 3.5 Brute Force

#### 3.5.1 子集生成

## 4. Graph

### 4.1 Union-find Set
```C++
int parent[HH];
int find(int x) {
	return x == parent[x] ? x : parent[x] = find(parent[x]);
}
void merge(int x, int y) {
	if (find(x) != find(y))
		parent[parent[x]] = parent[y];
}
void init() {
    for (int i = 0; i < n; i++) 
        parent[i] = i;
}
```
#### 4.1.1 Union-find Set - application

> place holder


### 4.2 Minimium Spanning Tree

#### 4.2.1 Prim's

> graph[][], time complexity: O(V^2)

```C++
void mst_prim() {
    int n_node, n_edge;
    ////////////////////////////////////////
    // read data
    ////////////////////////////////////////
    int graph[n_node][n_node];
    int min_dis[n_node];
    for (int i = 0; i < n_node; i++)
        min_dis[i] = INT_MAX; // initialize
    ////////////////////////////////////////
    // read graph[][]
    ////////////////////////////////////////

    int cur = 0; // the node just added
    for (int i = 1; i < n_node; i++) { // total need pick n-1 edges
        min_dis[cur] = -1; // add cur
        for (int j = 0; j < n_node; j++) // for all node
            if (graph[cur][j] < min_dis[j]) // if can reach from new node and nearer
                min_dis[j] = graph[cur][j]; // update the distance
        int next = -1; // the node to add
        int cur_min_dis = INT_MAX; // current distance of nearest node
        for (int j = 0; j < n_node; j++) // check all node
            if (min_dis[j] >= 0 && min_dis[j] < cur_min_dis) { // if j node is nearer
                next = j; // record
                cur_min_dis = min_dis[j];
            }
        // add edge: cur->next
        cur = next; // next node to add
    }
}
```
> vector<int> graph[], time complexity: (V + E)log(V)

```C++
struct Edge {
    int from;
    int to;
    int length;

    bool operator< (Edge b) const {
        return this->length > b.length;
    }
};

void mst_prim() {
    int n_node;
    int n_edge;
    ////////////////////////////////////////////
    // cin >> n_node >> n_edge;
    ////////////////////////////////////////////
    vector<Edge> graph[n_node];
    ////////////////////////////////////////////
    // read graph
    ////////////////////////////////////////////

    priority_queue<Edge> discovered;
    int added[n_node];
    memset(added, 0, sizeof(added));

    int to_add = n_node;
    Edge temp = {0, 0, 0};
    discovered.push(temp); // 0 is first node
    while (to_add--) {
        Edge cur = discovered.top();
        discovered.pop();
        while (added[cur.to] == 1) {
            cur = discovered.top();
            discovered.pop();
        }
        // cur is the edge to add

        added[cur.to] = 1;
        for (int i = 0; i < graph[cur.to].size(); i++) {
            Edge& next = graph[cur.to][i];
            if (to != next.to && added[next.to] == 0) {
                discovered.push(next);
            }
        }
    }
    // should directly maintain the min distance for each node to current tree
    // use heapfy...
}
```

#### 4.2.2 Kruskal

> Elog(E) + Elog(V)

```C++
struct Edge {
    int from;
    int to;
    int length;

    bool operator< (Edge b) const {
        return this->length < b.length;
    }
};

int get_father(int father[], int a) {
    if (father[a] != a)
        return father[a] = get_father(father, father[a]);
    return a;
}

void solve() {
    int n_node, n_edge;
    /////////////////////////////////////////////////////
    // initialize n_edge
    /////////////////////////////////////////////////////
    Edge e[n_edge];
    /////////////////////////////////////////////////////
    // initialize edge e
    /////////////////////////////////////////////////////
    int father[n_node];
    for (int i = 0; i < n_node; i++)
        father[i] = i; // initialize
    sort(e, e + n_edge);

    int to_add = n_node - 1;
    for (int cur = 0; to_add; cur++) {
        int fromSfather = get_father(father, e[cur].from);
        int toSfather = get_father(father, e[cur].to);
        if (fromSfather != toSfather) {
            father[fromSfather] = toSfather;
            to_add--;
            // add edge e[cur]
        }
    }
}
```


### 4.3 Shortest Path

#### 4.3.1 任意两点

```
for (k)
    for (i)
        for (j)
        	d(i, j) = min(d(i, j), d(i, k) + d(j, k))
```

#### 4.3.2 Bellman–Ford

> Bellman–Ford algorithm is O(VE).
> Can be applied to situations when there is a maximun number of vertices in shortest path.

```
for (n times of relax)
    for (each node)
        relax each node
```

#### 4.3.3 SPFA

#### 4.3.4 Dijkstra

> Dijkstra is good for graphs non-negative edges.

> O(V^2)

### 4.4 Bipartite Graph 二分图

> 1. A graph is bipartite if and only if it does not contain an odd cycle.
> 2. A graph is bipartite if and only if it is 2-colorable, (i.e. its chromatic number is less than or equal to 2).
> 3. The spectrum of a graph is symmetric if and only if it's a bipartite graph.

#### 4.4.1 Hungarian algorithm 匈牙利算法
> O(E * V)

```C++
int n_node;
int graph[405][405];
int match[405];
int visited[405];

bool augment(int cur) {
    for (int i = 0; i < n_node; i++) { // for all node
        if (graph[cur][i] > 0 && visited[i] == 0) { // if have edge and not visited
            visited[i] = 1; // mark visited
            if (match[i] == -1 || augment(match[i])) { // if not matched, or its previous can find other match
                match[i] = cur; // match it
                return true;
            }
        }
    }
    return false; // cannot find any match
}

int match() {
    memset(graph, 0, sizeof(graph));
    ////////////////////////////////////////////////
    // initialize n_node, graph
    ////////////////////////////////////////////////
    int n_match = 0;
    memset(match, -1, sizeof(match));
    for (int i = 0; i < n_node; i++) { // for each node, find an augmented path
        memset(visited, 0, sizeof(visited)); // each node only visit once
        if (augment(i)) // if found
            n_match++; // maximum matching ++
    }
}
```

### 4.5 Maximum Flow Problem 最大流

#### 4.5.1 Dinic
``` C++
int graph[250][250];
int level[250];
int n_node;

int mark_level(int start, int end) {
    memset(level, -1, sizeof(level));
    queue<int> to_visit;
    
    level[start] = 0;
    to_visit.push(start);
    while (!to_visit.empty()) {
        int cur = to_visit.front();
        to_visit.pop();
        for (int i = 0; i < n_node; ++i) {
            if (graph[cur][i] != 0 && level[i] == -1) {
                level[i] = level[cur] + 1;
                to_visit.push(i);
            }
        }
    }

    if (level[end] == -1)
        return 0; // cannot reach the sink
    return 1; // can reach the sink
}

int augment(int cur, int end, int min_flow) {
    if (cur == end)
        return min_flow;

    int augmented_flow = 0;
    for (int i = 0; i < n_node; ++i) {
        if ((level[i] == level[cur] + 1 && graph[cur][i] > 0) &&
            (augmented_flow = augment(i, end, min(graph[cur][i], min_flow)))
        ) {
            graph[cur][i] -= augmented_flow;
            graph[i][cur] += augmented_flow;
            return augmented_flow;
        }
    }
    return 0;
}

int dinic(int start, int end) {
    int ans = 0;
    int temp = 0;
    while (mark_level(start, end))
        while (temp = augment(start, end, INT_MAX))
            ans += temp;
    return ans;
}
```
 
#### 4.5.2 Minimum-Cost Maximum-Flow 

```C++
// have not tested
int n_node;
int n_edge;

int cost[405][405]; // cost[i][j] = -cost[j][i]
int residual[405][405];

bool bellman_ford(int& flow_sum, int&cost_sum) { // 0: start, n_node - 1: end
    int min_cost[405]; for (int i = 0; i < n_node; i++) min_cost[i] = INT_MAX; min_cost[0] = 0;
    int pre_node[405]; pre_node[0] = 0;
    int max_flow[405];
    int in_queue[405]; memset(in_queue, 0, sizeof(in_queue));

    queue<int> q;
    q.push(0);
    while (q.size()) {
        int cur = q.front(); q.pop();
        in_queue[cur] = 0;

        for (int i = 0; i < n_node; i++) {
            if (residual[cur][i] > 0 && min_cost[i] > min_cost[cur] + cost[cur][i]) {
                min_cost[i] = min_cost[cur] + cost[cur][i];
                pre_node[i] = cur;
                max_flow[i] = min(max_flow[cur], residual[cur][i]);

                if (in_queue[i] == 0) {
                    in_queue[i] = 1;
                    q.push(i);
                }
            }
        }
    }
    if (min_cost[n_node - 1] == INT_MAX)
        return false;
    flow_sum += max_flow[n_node - 1];
    cost_sum += max_flow[n_node - 1] * min_cost[n_node - 1];
    for (int cur = n_node - 1; cur != 0; cur = pre_node[cur]) {
        residual[pre_node[cur]][cur] -= max_flow[n_node - 1];
        residual[cur][pre_node[cur]] += max_flow[n_node - 1];
    }
    return true;
}

void min_cost_max_flow() {
    int flow_sum = 0;
    int cost_sum = 0;
    while (bellman_ford(flow_sum, cost_sum));
    cout << flow_sum << " " << cost_sum << endl;
}
```

### 4.6 强连通分量 图的 割点, 桥, 双连通分支 ``https://www.byvoid.com/blog/biconnect``

> [点连通度与边连通度]
> 
> 在一个无向连通图中，如果有一个顶点集合，删除这个顶点集合，以及这个集合中所有顶点相关联的边以后，原图变成多个连通块，就称这个点集为割点集合。一个图的点连通度的定义为，最小割点集合中的顶点数。
> 
> 类似的，如果有一个边集合，删除这个边集合以后，原图变成多个连通块，就称这个点集为割边集合。一个图的边连通度的定义为，最小割边集合中的边数。
> 
> [双连通图、割点与桥]
> 
> 如果一个无向连通图的点连通度大于1，则称该图是点双连通的(point biconnected)，简称双连通或重连通。一个图有割点，当且仅当这个图的点连通度为1，则割点集合的唯一元素被称为割点(cut point)，又叫关节点(articulation point)。
> 
> 如果一个无向连通图的边连通度大于1，则称该图是边双连通的(edge biconnected)，简称双连通或重连通。一个图有桥，当且仅当这个图的边连通度为1，则割边集合的唯一元素被称为桥(bridge)，又叫关节边(articulation edge)。
> 
> 可以看出，点双连通与边双连通都可以简称为双连通，它们之间是有着某种联系的，下文中提到的双连通，均既可指点双连通，又可指边双连通。
> 
> [双连通分支]
> 
> 在图G的所有子图G'中，如果G'是双连通的，则称G'为双连通子图。如果一个双连通子图G'它不是任何一个双连通子图的真子集，则G'为极大双连通子图。双连通分支(biconnected component)，或重连通分支，就是图的极大双连通子图。特殊的，点双连通分支又叫做块。
> 
> [求割点与桥]
> 
> 该算法是R.Tarjan发明的。对图深度优先搜索，定义DFS(u)为u在搜索树（以下简称为树）中被遍历到的次序号。定义Low(u)为u或u的子树中能通过非父子边追溯到的最早的节点，即DFS序号最小的节点。根据定义，则有：
> 
> Low(u)=Min { DFS(u) DFS(v) (u,v)为后向边(返祖边) 等价于 DFS(v)<DFS(u)且v不为u的父亲节点 Low(v) (u,v)为树枝边(父子边) }
> 
> 一个顶点u是割点，当且仅当满足(1)或(2) (1) u为树根，且u有多于一个子树。 (2) u不为树根，且满足存在(u,v)为树枝边(或称父子边，即u为v在搜索树中的父亲)，使得DFS(u)<=Low(v)。
> 
> 一条无向边(u,v)是桥，当且仅当(u,v)为树枝边，且满足DFS(u)<Low(v)。
> 
> [求双连通分支]
> 
> 下面要分开讨论点双连通分支与边双连通分支的求法。
> 
> 对于点双连通分支，实际上在求割点的过程中就能顺便把每个点双连通分支求出。建立一个栈，存储当前双连通分支，在搜索图时，每找到一条树枝边或后向边(非横叉边)，就把这条边加入栈中。如果遇到某时满足DFS(u)<=Low(v)，说明u是一个割点，同时把边从栈顶一个个取出，直到遇到了边(u,v)，取出的这些边与其关联的点，组成一个点双连通分支。割点可以属于多个点双连通分支，其余点和每条边只属于且属于一个点双连通分支。
> 
> 对于边双连通分支，求法更为简单。只需在求出所有的桥以后，把桥边删除，原图变成了多个连通块，则每个连通块就是一个边双连通分支。桥不属于任何一个边双连通分支，其余的边和每个顶点都属于且只属于一个边双连通分支。
> 
> [构造双连通图]
> 
> 一个有桥的连通图，如何把它通过加边变成边双连通图？方法为首先求出所有的桥，然后删除这些桥边，剩下的每个连通块都是一个双连通子图。把每个双连通子图收缩为一个顶点，再把桥边加回来，最后的这个图一定是一棵树，边连通度为1。
> 
> 统计出树中度为1的节点的个数，即为叶节点的个数，记为leaf。则至少在树上添加(leaf+1)/2条边，就能使树达到边二连通，所以至少添加的边数就是(leaf+1)/2。具体方法为，首先把两个最近公共祖先最远的两个叶节点之间连接一条边，这样可以把这两个点到祖先的路径上所有点收缩到一起，因为一个形成的环一定是双连通的。然后再找两个最近公共祖先最远的两个叶节点，这样一对一对找完，恰好是(leaf+1)/2次，把所有点收缩到了一起。

find articulation point (cut vertex) / bridge (cutedge) in directed / undirected graph

find and merge biconnected component in undirected graph

find and merge strongly connected component in directed graph


time complexity `O(E+V)`

``` c++
#define NN 20002
#define MM 100002

int n;
int m;

int visit_order[NN];
int smallest_order_can_reach[NN];
int parent[NN];
int in_stack[NN];
int temp_component[NN];

vector<int> g[NN];

void merge(const vector<int>& component) {
    vector<int> out_vertex;
    int new_vertex = component.back();
    for (int v : component)
        temp_component[v] = 1;
    for (int v : component) {
        for (int o : g[v]) {
            if (!temp_component[o])
                out_vertex.push_back(o);
        }
        g[v].clear();
        g[v].push_back(new_vertex);
    }
    for (int v : component)
        temp_component[v] = 0;

    // use last vertex in the component as new vertex
    g[new_vertex] = out_vertex;
}

void dfs(int cur) {
    static int order = 0;
    static stack<int> s;

    visit_order[cur] = smallest_order_can_reach[cur] = ++order;
    s.push(cur);
    in_stack[cur] = 1;

    int subtree = 0;
    for (int next : g[cur]) {
        if (visit_order[next] == 0) {
            subtree++;
            parent[next] = cur;
            dfs(next);
            smallest_order_can_reach[cur] = min(smallest_order_can_reach[cur], smallest_order_can_reach[next]);

            // if cur is root, and subtree > 1
            // it is an articulation point
            if (visit_order[cur] == 1 && subtree > 1)
                ;

            // if cur is not root, and next cannot reach smaller vertex
            // it is an articulation point
            if (visit_order[cur] != 1 && visit_order[cur] <= smallest_order_can_reach[next])
                ;

            // if cannot use this edge to reach a smaller vertex
            // it is a bridge
            if (visit_order[cur] < smallest_order_can_reach[next])
                ;
        }

            // for undirected graph
            // update the smallness of vertex that can reach
//        else if (next != parent[cur])
//            smallest_order_can_reach[cur] = min(smallest_order_can_reach[cur], visit_order[next]);

            // for directed graph
        else if (in_stack[next])
            smallest_order_can_reach[cur] = min(smallest_order_can_reach[cur], visit_order[next]);
    }
    
    if (visit_order[cur] == smallest_order_can_reach[cur]) {
        // because visit_order[cur] == smallest_order_can_reach[cur]
        // and visit_order[cur] > visit_order[parent[cur]]
        // so visit_order[parent[cur]] < smallest_order_can_reach[cur]
        // so cur-parent[cur] is a bridge
        // cur is root of the biconnected component
        // so pop all util cur

        vector<int> component;
        int min_vertex = s.top();
        while (1) {
            int vertex = s.top(); s.pop();
            in_stack[vertex] = 0;
            min_vertex = min(min_vertex, vertex);
            component.push_back(vertex);
            if (vertex == cur)
                break;
        }
        // cur is the last vertex in the component
        merge(component);
    }
}

int main() {
    cin >> n >> m;
    for (int i = 0; i < m; i++) {
        int a, b;
        cin >> a >> b;
        g[a].push_back(b);
    }

    dfs(1);
}
```

### 4.7 Topological Sort / 拓扑排序

> Topological Sorting on Directed Acyclic Graph (DAG)
>
> time complexity `O(N)`

``` c++
#define NN 100000

int n;
int m;

vector<int> g[NN];
int in_degree[NN];

void topological_sort() {
    queue<int> q; // vertex pending to remove
    for (int i = 1; i <= n; i++)
        if (in_degree[i] == 0) // all with in-degree == 0 can be removed
            q.push(i);

    int left_to_remove = n;
    while (q.size()) {
        int cur = q.front(); q.pop();
        for (int next : g[cur]) {
            in_degree[next]--;
            if (in_degree[next] == 0) // if in-degree == 0, can be removed
                q.push(next);
        }
        left_to_remove--;
    }

    if (left_to_remove == 0)
        cout << "Correct" << endl;
    else
        cout << "Wrong" << endl;
}

void init_graph() {
    cin >> n >> m;
    for (int i = 0; i < m; i++) {
        int a, b;
        cin >> a >> b;
        g[a].push_back(b);
        in_degree[b]++;
    }
}

int main() {
    init_graph();
    topological_sort();
}
```

### 4.8 Euler Cycle/Path, Hamilton Cycle/Path

> place holder

### 4.9 find negative (weight) Cycle on a graph

> place holder


## 5. Number & Mathematics

### 5.1 BigInteger & BigDecimal

#### 5.1.1 C++ Big Integer

```c++
const int BASE_LENGTH = 2;
const int BASE = (int) pow(10, BASE_LENGTH);
const int MAX_LENGTH = 500;

string int_to_string(int i, int width, bool zero) {
    string res = "";
    while (width--) {
        if (!zero && i == 0) return res;
        res = (char)(i%10 + '0') + res;
        i /= 10;
    }
    return res;
}

struct bigint {
    int len, s[MAX_LENGTH];

    bigint() {  
        memset(s, 0, sizeof(s));  
        len = 1;  
    }

    bigint(unsigned long long num) {
        len = 0;
        while (num >= BASE) {
            s[len] = num % BASE;
            num /= BASE;
            len ++;
        }
        s[len++] = num;
    }

    bigint(const char* num) {
        int l = strlen(num);
        len = l/BASE_LENGTH;
        if (l % BASE_LENGTH) len++;
        int index = 0;
        for (int i = l - 1; i >= 0; i -= BASE_LENGTH) {
            int tmp = 0;
            int k = i - BASE_LENGTH + 1;
            if (k < 0) k = 0;
            for (int j = k; j <= i; j++) {
                tmp = tmp*10 + num[j] - '0';
            }
            s[index++] = tmp;
        }
    }

    void clean() {  
        while(len > 1 && !s[len-1]) len--;  
    }

    string str() const {
        string ret = "";
        if (len == 1 && !s[0]) return "0";
        for(int i = 0; i < len; i++) {
            if (i == 0) {
                ret += int_to_string(s[len - i - 1], BASE_LENGTH, false);
            } else {
                ret += int_to_string(s[len - i - 1], BASE_LENGTH, true);
            }
        }
        return ret;
    }

    unsigned long long ll() const {
        unsigned long long ret = 0;
        for(int i = len-1; i >= 0; i--) {
            ret *= BASE;
            ret += s[i];
        }
        return ret;
    }

    bigint operator + (const bigint& b) const {
        bigint c = b;
        while (c.len < len) c.s[c.len++] = 0;
        c.s[c.len++] = 0;
        bool r = 0;
        for (int i = 0; i < len || r; i++) {
            c.s[i] += (i<len)*s[i] + r;
            r = c.s[i] >= BASE;
            if (r) c.s[i] -= BASE;
        }
        c.clean();
        return c;
    }

    bigint operator - (const bigint& b) const {
        if (operator < (b)) throw "cannot do subtract";
        bigint c = *this;
        bool r = 0;
        for (int i = 0; i < b.len || r; i++) {
            c.s[i] -= b.s[i];
            r = c.s[i] < 0;
            if (r) c.s[i] += BASE;
        }
        c.clean();
        return c;
    }

    bigint operator * (const bigint& b) const {  
        bigint c;
        c.len = len + b.len;  
        for(int i = 0; i < len; i++)  
            for(int j = 0; j < b.len; j++)  
                c.s[i+j] += s[i] * b.s[j];  
        for(int i = 0; i < c.len-1; i++){  
            c.s[i+1] += c.s[i] / BASE;  
            c.s[i] %= BASE;  
        }  
        c.clean();  
        return c;  
    }

    bigint operator / (const int b) const {
        bigint ret;
        int down = 0;
        for (int i = len - 1; i >= 0; i--) {
            ret.s[i] = (s[i] + down * BASE) / b;
            down = s[i] + down * BASE - ret.s[i] * b;
        }
        ret.len = len;
        ret.clean();
        return ret;
    }

    bool operator < (const bigint& b) const {
        if (len < b.len) return true;
        else if (len > b.len) return false;
        for (int i = 0; i < len; i++)
            if (s[i] < b.s[i]) return true;
            else if (s[i] > b.s[i]) return false;
        return false;
    }

    bool operator == (const bigint& b) const {
        return !(*this<b) && !(b<(*this));
    }

    bool operator > (const bigint& b) const {
        return b < *this;
    }
};
```

Examples

```c++
ASSERT((a+b).str()=="10001")
ASSERT((a+b)==bigint(10001))
ASSERT((b/2)==4999)
ASSERT(c == 12345)
ASSERT(c < 123456)
ASSERT(c > 123)
ASSERT(!(c > 123456))
ASSERT(!(c < 123))
ASSERT(!(c == 12346))
ASSERT(!(c == 12344))
ASSERT(c.str() == "12345")
ASSERT((b-1)==9998)
ASSERT(a.ll() == 2)
ASSERT(b.ll() == 9999)
```


#### 5.1.2 The Java Approach 

BigInteger & BigDecimal

> 学长说不可以印这些。

### 5.2 Matrix

```C++
operator+
operator*
```

> Square matrix

```C++

struct Matrix {
    // int height;
    // int width;

    long long value[32][32];

    Matrix operator* (const Matrix& that);
    Matrix operator+ (const Matrix& that);
    Matrix mirror();
    void show() {
        cout << endl;
        for (int i = 0; i < n; i++) {
            for (int j = 0; j < n; j++)
                cout << this->value[i][j] << " ";
            cout << endl;
        }
    }
};

void mod_it(Matrix& temp) {
    for (int i = 0; i < n; i++)
        for (int j = 0; j < n; j++)
            temp.value[i][j] %= m;
}

Matrix Matrix::operator* (const Matrix& that) {
    Matrix temp;
    for (int i = 0; i < n; i++) {
        for (int j = 0; j < n; j++) {
            temp.value[i][j] = 0;
            for (int k = 0; k < n; k++)
                temp.value[i][j] += this->value[i][k] * that.value[k][j];
        }
    }
    mod_it(temp);
    return temp;
}

Matrix Matrix::operator+ (const Matrix& that) {
    Matrix temp;
    for (int i = 0; i < n; i++)
        for (int j = 0; j < n; j++)
            temp.value[i][j] = this->value[i][j] + that.value[i][j];
    mod_it(temp);
    return temp;
}

Matrix Matrix::mirror() {
    Matrix temp;
    for (int i = 0; i < n; i++)
        for (int j = 0; j < n; j++)
            temp.value[i][j] = this->value[i][j];
    return temp;
}
```

### 5.3 Number Theory

#### 5.3.1 欧拉函数 ?

#### 5.3.2 欧几里得算法 / gcd

> see next section

#### 5.3.3 扩展欧几里得算法 

``http://www.cnblogs.com/frog112111/archive/2012/08/19/2646012.html``

> 对于不完全为 0 的非负整数 a, b, 必然存在整数对 (x, y), 使得 gcd(a, b) = ax + by

> suppose: a > b, we want to get (x1, y1)

> (i) if b == 0, then gcd(a, b) = a = ax + 0, then x1 = 1, y1 = 0

> (ii) if b != 0:

>   (1): a * x1 + b * y1 = gcd(a, b)

>   (2): b * x2 + (a % b) * y2 = gcd(b, a % b)
    
>   (1) == (2)

>   so: a * x1 + b * y1 = b * x2 + (a % b) * y2
    
>   so: a * x1 + b * y1 = b * x2 + (a - (int)(a / b) * b) * y2
    
>   so: a * x1 + b * y1 = a * y2 + b * (x2 - (int)(a / b) * y2)
    
>   so: x1 = y2, y1 = x2 - (int)(a / b) * y2, can get (x1, y1) from (x2, y2)

>   next:

>       (1): b * x2 + (a % b) * y2 = gcd(b, a % b)
        
>       (2): (a % b) * x3 + b % (a % b) * y3 = gcd(a % b, b % (a % b))
        
>       so: can get (x2, y2) from (x3, y3)
        
>       next: ... until in gcd(a, b), b == 0, then xi = 1, yi = 0, go back ...

```C++
long long ansx, ansy, ansd;

void euclidean(long long a, long long b) {
    if (b == 0) {
        ansx = 1;
        ansy = 0;
        ansd = a;
    } else {
        euclidean(b, a % b);
        long long temp = ansx;
        ansx = ansy;
        ansy = temp - a / b * ansy;
    }
}

int main(int argc, char const *argv[]) {
    long long a, b, c;
    cin >> a >> b >> c;

    ansx = 0;
    ansy = 0;
    ansd = 0;
    euclidean(a, b);

    // now (ansx, ansy) is the answer (x, y) for a * x1 + b * y1 = gcd(a, b)
    // ansd is the a when b == 0, which is just gcd(a, b)
}
```

#### 5.3.4 求解不定方程

> for: p * a + q * b = c

> if c % gcd(a, b) == 0, then 有整数解 (p, q), else NO


> if we get (p0, q0) for p0 * a + q0 * b = gcd(a, b)

> then: for p * a + q * b = gcd(a, b) (k is any integer)

> p = p0 + b / gcd(a, b) * k

> q = q0 - a / gcd(a, b) * k


> then: for p * a + q * b = c = c / gcd(a, b) * gcd(a, b) (k is any integer)

> p = (p0 + b / gcd(a, b) * k) * c / gcd(a, b)

> q = (q0 - a / gcd(a, b) * k) * c / gcd(a, b)

```C++
// after get ansx, ansy, ansd
// test if c % ansd == 0
// ansx = (ansx + b / gcd(a, b) * k) * c / gcd(a, b)
// ansy = (ansy - a / gcd(a, b) * k) * c / gcd(a, b)
// smallest: ansx % (b / gcd(a, b) + b / gcd(a, b)) % (b / gcd(a, b))
```

#### 5.3.5 求解模线性方程（线性同余方程）

> (a * x) % n = b % n, x = ?

> same as: a * x + n * y= b

> so: one answer for a * x + n * y= b is: x * b / gcd(a, n)

> so: one answer for (a * x) % n = b % n is: x0 = (x * b / gcd(a, n)) % n

> other answer xi = (x0 + i * (n / gcd(a, n))) % n, i = 0...gcd(a, n)-1

> smallest answer is x0 % (n / gcd(a, n) + gcd(a, n)) % gcd(a, n)

```C++
```

#### 5.3.6 求解模的逆元

> (a * x) % n = 1, x = ?

> if gcd(a, n) != 1, then NO answer

> else:

> same as: a * x + n * y = 1

> can get only one answer x

```C++
// after get ansx, ansy, ansd
// if ansd != 1, then NO answer
// smallest ansx = (ansx % (n / gcd(a, n)) + (n / gcd(a, n))) % (n / gcd(a, n))
```

#### 5.3.7 中国剩余定理

#### 5.3.8 最小公倍数

```C++
a * b / gcd(a, b)
```

#### 5.3.9 分解质因数

```C++
long long x;
cin >> x;
for (long long factor = 2; x != 1; factor++) {
    if (x % factor == 0)
        cout << factor << " is a prime factor" << endl;
    while (x % factor == 0)
        x = x / factor;
}
```

#### 5.3.10 因数个数

```C++
n = p1 ^ x1 * p2 ^ x2 * ... * pn ^ xn
total = (x1 + 1) * (x2 + 1) * ... * (xn + 1)
```

#### 5.3.11 素数判定

> 大于 3 的质数可以被表示为 6n - 1 或 6n + 1

```C++
bool is_prime(int n) {
    if (n == 1 || n % 2 == 0)
        return false;  
    int t = sqrt(n);
    for (int i = 3; i <= t; i += 2)
        if (n % i == 0)
            return false;
    return true;
}
```

#### 5.3.12 进制转换

```C++
void convert_dec_to_base(int n, const int base) {
    if (n == 0)
        cout << 0 << endl;
    while (n != 0) {
        int e = n % base;
        cout << e << " "; // printing in reverse order
        n /= base;
    } cout << endl;
}

int convert_base_to_dec(const int s[], const int len, const int base) {
    int result = 0;
    for (int i = 0; i < len; i++)
        result = result * base + s[i];
    return result;
}
```

#### 5.3.13 A / C
> C(n, k) = C(n-1, k) + C(n-1, k-1)
> C(n, k) = C(n, n-k)


#### 5.3.14 质数表

```C++
int is_prime[UP_LIMIT + 1];
for (int i = 1; i <= UP_LIMIT; i++) // init to 1
    is_prime[i] = 1;
for (int i = 4; i <= UP_LIMIT; i += 2) // even number is not
    is_prime[i] = 0;
for (int k = 3; k*k <= UP_LIMIT; k++) // start from 9, end at sqrt
    if (is_prime[k])
        for(int i = k*k; i <= UP_LIMIT; i += 2*k) // every two is not 
            is_prime[i] = 0;
```

#### 5.3.15 Fast Exponention

> To calculate n ^ p % M

```C++
int power_modulo(int n, int p, int M) {
    int result = 1;
    while (p > 0) {
        if (p % 2 == 1)
            result = (result*n) % M;
        p /= 2;
        n = (n*n) % M;
    }
    return result;
}
```

### 5.4 博弈论

> place holder

## 6. Geometry

### 6.1 2-Dimension Space

#### 6.1.1 Template of Point

```C++
struct point {
    int x, y;

    double length() {
        return sqrt(x*x + y*y);
    }

    long operator* (const point& b) {
        return x*b.y - y*b.x;
    }

    long cross_product(const point& b) {
      return x * b.x + y * b.y;
    }

    bool at_right_of(const point& a, const point& b) const {
        // a: relative point, b: base
        point vec_self = {x - b.x, y - b.y};
        point vec_that = {a.x - b.x, a.y - b.y};
        long product = vec_self * vec_that;
        if (product>0) return true;
        if (product==0 && vec_self.length()>vec_that.length()) return true;
        return false;
    }

    double to_point(const point& b) const {
        return sqrt(pow(x-b.x,2) + pow(y-b.y,2));
    }

    double to_segment(const point& a, const point& b) const {
        double len_ab = a.to_point(b);
        if (abs(len_ab)<E) return to_point(a);
        double r = ((a.y-y)*(a.y-b.y) - (a.x-x)*(a.x-b.x))/pow(len_ab,2);
        if (r>1 || r<0) return min(to_point(a), to_point(b));
        // projection of p is on extension of AB
        r = ((a.y - y)*(b.y - y) - (a.x - x)*(b.y - a.y))/pow(len_ab,2);
        return fabs(r*len_ab);
    }

    double to_segment(const point& a, const point& b) const {
        point vec_ab = {b.x - a.x, b.y - a.y};
        point vec_ia = {x - a.x, y - a.y};
        point vec_ib = {x - b.x, y - b.y};
        if (vec_ia.cross_product(vec_ab) < 0 || vec_ib.cross_product(vec_ab) > 0)
            return min(to_point(a), to_point(b));
        return abs(vec_ab * vec_ia) / vec_ab.length();
    } // same meaning with v1, need test
    
    double to_line(const point& a, const point& b) const {
        point vec_ab = {b.x - a.x, b.y - a.y};
        point vec_ia = {x - a.x, y - a.y};
        return abs(vec_ab * vec_ia) / vec_ab.length();
    } // same meaning with v1, need test
};
```

#### 6.1.2 向量点乘 叉乘

> a = (x1, y1)
> b = (x2, y2)
> i ... |i| = 1, vertical to a-b surface

#### 6.1.3 dot product
> a dot b = x1 * x2 + y1 * y2 = |a| * |b| * cos(angle)
> 
> if = 0: 90 degree
> 
> a dot b / |b| = a project to b

#### 6.1.4 cross product
> a x b = x1 * y2 - x2 * y1 = |a| * |b| * sin(angle) * i
> 
> if < 0: b is at left of a
> 
> if = 0: a, b in a line
> 
> if 0: b is at right of a
> 
> a x b = area of 平行四边形
> a x b x c = area of 平行六面体, c = (x3, y3)

#### 6.1.5 直线公式

> (x, y) = (x1, y1) + k * ((x2, y2) - (x1, y1))

#### 6.1.6 Convex Hull

##### Gift Wrapping

> place holder

##### QuickHull

> place holder

##### Graham scan

> O(VlogV)

```C++
struct Point {
    long x;
    long y;

    bool at_right_of(Point& that, Point& base) {
        Point vec_self = {this->x - base.x, this->y - base.y};
        Point vec_that = {that.x - base.x, that.y - base.y};

        long product = vec_self * vec_that;
        if (product > 0)
            return true; // "this" is at right of "that"
        if (product == 0 && vec_self.length() > vec_that.length())
            return true; // "this" is at right of "that"
        return false; // "this" is NOT at right of "that"
    };
    long operator* (Point& that) {
        return this->x * that.y - this->y * that.x;
    };
    double distance_to(Point& that) {
        long x_diff = this->x - that.x;
        long y_diff = this->y - that.y;
        return sqrt(x_diff * x_diff + y_diff * y_diff);
    };
    double length() {
        return sqrt(this->x * this->x + this->y * this->y);
    }
};

Point p[1005];
int my_stack[1005];
int n, l, my_stack_top = -1;

bool compare(Point p1, Point p2) {
    return p1.at_right_of(p2, p[0]);
}

void push(int index) {
    my_stack[++my_stack_top] = index;
}
int pop() {
    int temp = my_stack[my_stack_top--];
    return temp;
}

void graham_scan() {
    push(0);
    push(1);

    int pre;
    int prepre;
    for (int i = 2; i < n; i++) {
        pre = my_stack_top;
        prepre = my_stack_top - 1;
        while (p[i].at_right_of(p[my_stack[pre]], p[my_stack[prepre]])) {
            pop();
            if (my_stack_top == 0)
                break;
            pre = my_stack_top;
            prepre = my_stack_top - 1;
        }
        push(i);
    }

    int last = my_stack_top;
    if (p[0].at_right_of(p[my_stack[last]], p[my_stack[pre]]))
        pop();
}

int main(int argc, char const *argv[]) {
    cin >> n >> l;
    
    int minimun = 0;
    for (int i = 0; i < n; ++i) {
        int temp_x, temp_y;
        cin >> temp_x >> temp_y;
        p[i] = {temp_x, temp_y};

        if ((p[i].y < p[minimun].y) || (p[i].y == p[minimun].y && p[i].x < p[minimun].x))
            minimun = i;
    }

    Point temp = {p[minimun].x, p[minimun].y}; // swap lowest and most left point to p[0]
    p[minimun] = p[0];
    p[0] = temp;

    sort(p + 1, p + n, compare); // use p[0] as base, sort according to polar angle
    graham_scan();
    // now all points in the stack is on Convex Hull // size of stack = 1 + stack_top

    for (int i = 0; i <= my_stack_top; i++)
        cout << "point " << my_stack[i] << " is on Convex Hull" << endl;
}
```



## 7. Tricks & Miscellaneous


### 7.1 String

#### 7.1.1 KMP

> Match pattern in a string
> 
> O(n) = O(len(pattern) + len(string))

```C++
#define HHH 10003

int ne[HHH]; // next[], if par[i] not matched, jump to i = ne[i]
int kmp(string& par, string& ori) {
    ne[0] = -1;
    for (int p = ne[0], i = 1; i < par.length(); i++) {
        while (p >= 0 && par[p+1] != par[i])
            p = ne[p];
        if (par[p+1] == par[i])
            p++;
        ne[i] = p;
    }

    int match = 0;
    for (int p = -1, q = 0; q < ori.length(); q++) {
        while (p >= 0 && par[p+1] != ori[q])
            p = ne[p];
        if (par[p+1] == ori[q])
            p++;
        if (p + 1 == par.length()) { // match!
            p = ne[p];
            match++;
        }
    }

    return match; // return number of occurance
}

int main () {
    int n; cin >> n;
    string par, ori;
    while (cin >> par >> ori)
        cout << kmp(par, ori) << endl;
    return 0;
}
```

#### 7.1.2 Boyer-Moore?

#### 7.1.3 Longest palindromic substring (Manacher's algorithm)

> O(n)

```c++
int dp[HHH];
int lengthLongestPalindromSubstring(string& s) {
    memset(dp, 0, sizeof(dp));
    int ans = 0;
    int pivot = 1;
    int len = s.length() * 2; // _s0_s1_s2 = 2 * length
    for (int i = 1; i < len; i++) {
        int pBorder = pivot + dp[pivot];
        int iBorder = i;
        if (iBorder < pBorder && 2 * pivot - i > 0) {
            dp[i] = dp[2*pivot-i];
            iBorder = min(pBorder, i + dp[i]);
        }

        if (iBorder >= pBorder) {
            int j = iBorder + (iBorder % 2 ? 2 : 1);
            for (; j < len && 2*i-j > 0 && s[j/2] == s[(2*i-j)/2]; j += 2)
                ;
            iBorder = j - 2;
            dp[i] = iBorder - i;
            pivot = i;
        }
        ans = max(ans, dp[i] + 1);
    }

    return ans;
}

int main () {
    int n; cin >> n;
    string s;
    while (cin >> s)
        cout << lengthLongestPalindromSubstring(s) << endl;
    return 0;
}
```



### 7.2 cantor_expansion / reverse_cantor_expansion

> for hashing, or ...

```C++
long long factorial(int n) {
    if (n == 0)
        return 1;

    long long ans = n;
    for (int i = 1; i < n; i++)
        ans = ans * i;
    return ans;
}

long long cantor_expansion(int permutation[], int n) {
    // input: (m-th permutation of n numbers, n)
    // return: m
    int used[n + 1];
    memset(used, n, sizeof(used));

    long long ans = 0;
    for (int i = 0; i < n; i++) {
        int temp = 0;
        used[permutation[i]] = 1;
        for (int j = 1; j < permutation[i]; j++)
            if (used[j] != 1)
                temp += 1;
        ans += factorial(n - 1 - i) * temp;
    }

    return ans + 1;
}

void reverse_cantor_expansion(int n, long long m) {
    // m-th permutation of n numbers
    int ans[n + 1], used[n + 1];
    memset(ans, -1, sizeof (ans));
    memset(used, 0, sizeof (used));

    m = m - 1;
    for (int i = n - 1; i >= 0; i--) {
        long long fac = factorial(i);
        int temp = m / fac + 1;
        m = m - (temp - 1) * fac;
        for (int j = 1; j <= temp; j++)
            if (used[j] == 1)
                temp++;

        ans[n - i] = temp;
        used[temp] = 1;
    }

    for (int i = 1; i < n + 1; i++)
        cout << ans[i] << " ";
    cout << "\n";
}
```

# Type Challenges

These are my solution on [Type Challenges](https://github.com/type-challenges/type-challenges)

[Type diagram](https://gist.github.com/laughinghan/31e02b3f3b79a4b1d58138beff1a2a89)

## Easy

ID|Challenge|Solve|Note|
-|-|-|-|
4|Pick|:heavy_check_mark:| { [P in K]: any } (K is a union type) |
7|Readonly|:heavy_check_mark:| { [P in keyof T]: T[P] } (T is a tuple type) |
11|Tuple to Object|:heavy_check_mark:| PropertyKey, Generic Constraint and T[number] (Change Tuple to Union) |
14|First of Array|:heavy_check_mark:| never effect with iteration |
18|Length of Tuple|:heavy_check_mark:| T['length'] (T is a Tuple type)|
43|Exclude|:heavy_check_mark:||
189|Awaited|:heavy_check_mark:| Recursive, PromiseLike and infer (must use with extends) |
268|If|:heavy_check_mark:||
533|Concat|:heavy_check_mark:|[...T]|
898|Includes||:woozy_face:|
3057|Push|:heavy_check_mark:||
3060|Unshift|:heavy_check_mark:||
3312|Parameters|:heavy_check_mark:|T extends (...args: any[]) => unknown|

## Medium

ID|Challenge|Solve|Note|
-|-|-|-|
2|Get Return Type|:heavy_check_mark:||
3|Omit|:heavy_check_mark:| as |
8|Readonly 2|:heavy_check_mark:||
9|Deep Readonly|:heavy_check_mark:||
10|Tuple to Union|:heavy_check_mark:||
12|Chainable Options||:woozy_face:|
15|Last of Array|:heavy_check_mark:| T extends [...infer Head, infer Last] |
16|Pop|:heavy_check_mark:||
20|Promise.all||:woozy_face:|
62|Type Lookup||:woozy_face:|
106|Trim Left|:heavy_check_mark:| able to infer string, S extends `${infer L}${infer R}` |
108|Trim|:heavy_check_mark:||
110|Capitalize||:woozy_face:|
116|Replace|:heavy_check_mark:||
119|ReplaceAll|:heavy_check_mark:||
191|Append Argument|:heavy_check_mark:||
296|Permutation||:woozy_face:|
298|Length of String|:heavy_check_mark:| able to add another generic param with default value |
459|Flatten|:heavy_check_mark:||
527|Append to object|||
529|Absolute|:heavy_check_mark:||
531|String to Union|:heavy_check_mark:||
599|Merge|:heavy_check_mark:| keyof T & keyof U is equal keyof (T | U) |
612|KebabCase|||
645|Diff|:heavy_check_mark:| keyof T & keyof U is equal keyof (T | U) |
949|AnyOf|||
1042|IsNever|:heavy_check_mark:|:woozy_face: [T] extends [never]. for T extends [never] It is distributive conditional type will map over T, If T is never (union never) will return never|
1097|IsUnion||:woozy_face:|
1130|ReplaceKeys|:heavy_check_mark:||
1367|Remove Index Signature|||
1978|Percentage Parser||:woozy_face:|
2070|Drop Char|:heavy_check_mark:||
2257|MinusOne||:woozy_face:|
2595|PickByType|:heavy_check_mark:||
2688|StartsWith|:heavy_check_mark:||
2693|EndsWith|:heavy_check_mark:||
2757|PartialByKeys|:heavy_check_mark:| merge type & type |
2759|RequiredByKeys|:heavy_check_mark:||
2793|Mutable|:heavy_check_mark:||
2852|OmitByType|:heavy_check_mark:||
2946|ObjectEntries|:heavy_check_mark:| T[P] extends undefined vs undefined extends T[P] (unknown is a infinite union (union of all types)) |
3062|Shift|:heavy_check_mark:||
3188|Tuple to Nested Object|:heavy_check_mark:|{ [k in K]: U } (K is tuple), infer something extends string |
3192|Reverse|:heavy_check_mark:||
3196|Flip Arguments|:heavy_check_mark:||
3243|FlattenDepth|||
3326|BEM style string|:heavy_check_mark:||
3376|InorderTraversal|||
4179|Flip|:heavy_check_mark:||
4182|Fibonnaci Sequence|||
4260|AllCombinations|||
4425|Greater Than|||
4471|Zip|:heavy_check_mark:||
4484|IsTuple|||
4449|Chunk|||
4518|Fill|||
4803|Trim Right|:heavy_check_mark:||
5117|Without|||
5140|Trunc|:heavy_check_mark:||
5153|IndexOf|||
5310|Join|||
5317|LastIndexOf|||
5360|Unique|||
5821|MapTypes|||
7544|Construct Tuple|:heavy_check_mark:||
8640|Number Range|||
8767|Combination|||
8987|Subsequence|||
9286|FirstUniqueCharIndex|||
9896|GetMiddleElement|:heavy_check_mark:|[infer Head, ... infer Middle, infer Tail]|
10969|Integer|||
16259|ToPrimitive|||
17973|DeepMutable|||
18142|All|||
18220|Filter|||

## Hard

ID|Challenge|Solve|Note|
-|-|-|-|
6|Simple Vue|||
17|Currying 1|||
55|Union to Intersection|||
59|Get Optional|||
89|Required Keys|||
90|Optional Keys|||
112|Capitalize Words|||
114|CamelCase|||
147|C-printf Parser|||
213|Vue Basic Props|||
223|IsAny|||
270|Typed Get|||
300|String to Number|||
399|Tuple Filter|||
472|Tuple to Enum Object|||
545|printf|||
553|Deep object to unique|||
651|Length of String 2|||
730|Union to Tuple|||
847|String Join|||
956|DeepPick|||
1290|Pinia|||
1383|Camelize|||
2059|Drop String|||
2822|Split|||
2828|ClassPublicKeys|||
2857|IsRequiredKey|||
2949|ObjectFromEntries|||
4037|IsPalindrome|||
5181|Mutable Keys|||
5423|Intersection|||
6141|Binary to Decimal|||
7258|Object Key Paths|||
8804|Two Sum|||
9155|ValidDate|||
9160|Assign|||
9384|Maximum|||
9775|Capitalize Nest Object Keys|||
13580|Replace Union|||
14080|FizzBuzz|||
14188|Run-length encoding|||
15260|Tree path array|||
19458|SnakeCase|||

## Extreme

ID|Challenge|Solve|Note|
-|-|-|-|
5|Get Readonly Keys|||
151|Query String Parser|||
216|Slice|||
274|Integers Comparator|||
462|Currying 2|||
476|Sum|||
517|Multiply|||
697|Tag|||
734|Inclusive Range|||
741|Sort|||
860|DistributeUnions|||
925|Assert Array Index|||
6228|JSON Parser|||
7561|Subtract|||

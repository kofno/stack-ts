# Table of contents

* [index.ts][SourceFile-0]
    * Functions
        * [fromArray][FunctionDeclaration-0]
        * [newStack][FunctionDeclaration-1]
    * Interfaces
        * [PopResult][InterfaceDeclaration-0]

# index.ts

## Functions

### fromArray

```typescript
function fromArray<T>(ts: T[]): Stack<T>;
```

**Type parameters**

| Name |
| ---- |
| T    |

**Parameters**

| Name | Type |
| ---- | ---- |
| ts   | T[]  |

**Return type**

[Stack][ClassDeclaration-0]<T>

----------

### newStack

```typescript
function newStack<T>(): Stack<T>;
```

**Type parameters**

| Name |
| ---- |
| T    |

**Return type**

[Stack][ClassDeclaration-0]<T>

## Interfaces

### PopResult

```typescript
interface PopResult<T> {
    stack: Stack<T>;
    top: T;
}
```

**Type parameters**

| Name |
| ---- |
| T    |

**Properties**

| Name  | Type                           | Optional |
| ----- | ------------------------------ | -------- |
| stack | [Stack][ClassDeclaration-0]<T> | false    |
| top   | T                              | false    |

## Classes

### [Stack][ClassDeclaration-0]


[SourceFile-0]: index.md#indexts
[FunctionDeclaration-0]: index.md#fromarray
[ClassDeclaration-0]: index/stack.md#stack
[FunctionDeclaration-1]: index.md#newstack
[ClassDeclaration-0]: index/stack.md#stack
[InterfaceDeclaration-0]: index.md#popresult
[ClassDeclaration-0]: index/stack.md#stack
[ClassDeclaration-0]: index/stack.md#stack
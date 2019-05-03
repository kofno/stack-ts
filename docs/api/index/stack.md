# Table of contents

* [Stack][ClassDeclaration-0]
    * Constructor
        * [constructor()][Constructor-0]
    * Properties
        * [push][PropertyDeclaration-0]
        * [pop][PropertyDeclaration-1]
        * [peek][GetAccessor-0]
        * [length][GetAccessor-1]

# Stack

```typescript
class Stack<T>
```

**Type parameters**

| Name |
| ---- |
| T    |
## Constructor

### constructor()

```typescript
public constructor();
```

## Properties

### push

```typescript
public push: (value: T) => Stack<T>;
```

**Type**

(value: T) => [Stack][ClassDeclaration-0]<T>

----------

### pop

```typescript
public pop: () => Maybe<PopResult<T>>;
```

**Type**

() => Maybe<[PopResult][InterfaceDeclaration-0]<T>>

----------

### peek

```typescript
public get peek: Maybe<T>;
```

**Type**

Maybe<T>

----------

### length

```typescript
public get length: number;
```

**Type**

number

[ClassDeclaration-0]: stack.md#stack
[Constructor-0]: stack.md#constructor
[PropertyDeclaration-0]: stack.md#push
[ClassDeclaration-0]: stack.md#stack
[PropertyDeclaration-1]: stack.md#pop
[InterfaceDeclaration-0]: ../index.md#popresult
[GetAccessor-0]: stack.md#peek
[GetAccessor-1]: stack.md#length
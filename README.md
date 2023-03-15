# Java Script Lecture 2

![](https://avatars.mds.yandex.net/i?id=c3147107a3057944e08b78ad83f3d6a837f70aca-5232391-images-thumbs&n=13)

## Table of Contents

> - SCOPE
>
> - HOISTING
>
> - Recursion
>
> - closure

## What is Scope in Javascript ?

> Область видимости (Scope) - это текущий контекст выполнения, в котором значения и выражения являются "видимыми" или на которые можно ссылаться; это объединённое множество идентификаторов, доступ к которым имеет текущий контекст.
>
> Если переменная или другое выражение не находится "в текущей области видимости", то оно недоступно для использования.

## How much Scope in Js ?

> - Global scope
>
> - Function scope
>
> - Block scope
>
> - Modul scope

## The 3 types of scope

![](https://avatars.mds.yandex.net/i?id=7e7532691b054eb5b4d9132e97d3931f8a519fc6-8497636-images-thumbs&n=13)

## The Scope Chain

![](https://miro.medium.com/v2/resize:fit:828/format:webp/1*gHKe3Ru0MjUiBNVnEkRVTA.png)

![](https://avatars.mds.yandex.net/i?id=ef3870cd0d0d33e6c07d4fb21164c62542b767c6-8312133-images-thumbs&n=13)

## Hoisting in Java Script

> Поднятие или hoisting — это механизм в JavaScript, в котором переменные и объявления функций, передвигаются вверх своей области видимости перед тем, как код будет выполнен.

![](https://avatars.mds.yandex.net/i?id=7b801abc59da3c3a733f1f70bc7548d132804cd3-7097242-images-thumbs&n=13)

## Hoisting – Variable (var)

> var - это традиционный способ объявления переменных в JavaScript.

![](https://miro.medium.com/max/726/1*pUqWuCzYCP79tOm4gGzXIw.png)

## Hoisting - function declaration

> Одним из преимуществ JavaScript является помещение объявления функций в память, перед выполнением любого сегмента кода. Объявления функций поднимаются, но они идут на самый верх, поэтому они будут находиться над всеми объявлениями переменных. Это позволяет нам использовать функцию до того, как мы объявим её в своем коде. Например:

![](./%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-15%20212251.png)

## What is Recursion in JavaScript ?

> Это способность функции вызвать саму себя в своем теле. Рекурсивная функция обязательно должна иметь условие завершения, иначе мы попадем в бесконечный цикл. Случайное создание бесконечного цикла переполнит стек вызовов и браузер зависнет. Поэтому новички держатся от рекурсии подальше, на всякий случай.
>
> ![](https://avatars.mds.yandex.net/i?id=07f4b67bbe577ada17fb62aafa3a8c6269073790-5232511-images-thumbs&n=13)

## What is Closure in JavaScript ?

> Замыкание — это комбинация функции и лексического окружения, в котором эта функция была определена. Другими словами, замыкание даёт вам доступ к Scope внешней функции из внутренней функции. В JavaScript замыкания создаются каждый раз при создании функции, во время её создания.
>
> ![](https://avatars.mds.yandex.net/i?id=9b582893f8f4e2bf78103c46e623c90c651e2793-4576872-images-thumbs&n=13)

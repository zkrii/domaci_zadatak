# Домаћи задатак из Техничке документације

## Задатак
Написати C# програм који на основу унете дужине странице једнакостраничног троугла `a` израчунава висину троугла.

### Формула

Висина једнакостраничног троугла рачуна се по формули:

$$
h = \frac{\sqrt{3}}{2} \cdot a
$$

---

### Алгоритамска шема

<img width="215" height="300" alt="Screenshot 2025-12-04 070800" src="https://github.com/user-attachments/assets/9e4f61a1-42ae-46db-bd68-bd99a3ecd86c" />

## Решење

``` cs


using System;
namespace ConsoleApp1
{
internal class Program
{
static void Main(string[] args)
{
double a, h;

Console.Write("Унеси дужину странице једнакостраничног троугла: ");
a = double.Parse(Console.ReadLine());

h = (Math.Sqrt(3) / 2) * a;

Console.WriteLine("Висина троугла износи: " + h);
}
}
}
```
### Тест примери

Тест пример 1:

``` text
Унеси дужину странице једнакостраничног троугла:
2
Висина троугла износи: 1.732


C:\Users\zkrii\Desktop\ConsoleApp1\ConsoleApp1\bin\Debug\ConsoleApp1.exe (process 13320) exited with code 0 (0x0).
Press any key to close this window . . .
```

Тест пример 2:

``` text
Унеси дужину странице једнакостраничног троугла:
5
Висина троугла износи: 4.330


C:\Users\zkrii\Desktop\ConsoleApp1\ConsoleApp1\bin\Debug\ConsoleApp1.exe (process 15324) exited with code 0 (0x0).
Press any key to close this window . . .
```
### Објекти

| Редни број | Променљива | Тип променљиве |
| ---------- | ---------- | -------------- |
| 1. | `a` | `double` |
| 2. | `h` | `double` |

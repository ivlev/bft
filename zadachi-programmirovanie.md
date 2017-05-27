# Задачи: Программирование

1. **Запишите число, которое будет напечатано в результате выполнения следующей программы.**![](/assets/Снимок экрана 2017-05-27 в 22.17.21.png)

   | Паскаль | Python | Си |
   | :--- | :--- | :--- |
   | var s, n: integer; begin  s := 0;  n := 0;  while s &lt; 111 do begin  s := s + 8;  n := n + 2  end;  writeln\(n\) end. | s = 0 n = 0 while s &lt; 111:  s = s + 8  n = n + 2 print\(n\) | \#include &lt;stdio.h&gt; int main\(\) { int s = 0, n = 0;  while \(s &lt; 111\) {  s = s + 8;  n = n + 2;  }  printf\("%d", n\);  return 0; } |

2. **Запишите число, которое будет напечатано в результате выполнения следующей программы.**

   | Паскаль | Python | Си |
   | :--- | :--- | :--- |
   | var k, s: integer; begin  k:= 5;  s:= 2;  while k &lt; 120 do begin  s:= s + k;  k:= k + 2;  end;  write\(s\); end. | k = 5 s = 2 while k &lt; 120:  s = s + k  k = k + 2 print\(s\) | \#include &lt;stdio.h&gt; int main\(\) { int k = 5, s = 2;  while \(k &lt; 120\) {  s = s + k;  k = k + 2;  }  printf\("%d", s\);  return 0; } |

3. **Запишите число, которое будет напечатано в результате выполнения следующей программы.**

   | Паскаль | Python | Си |
   | :--- | :--- | :--- |
   | var k, s: integer; begin  s:= 0;  k:= 0;  while s &lt; 1024 do begin  s:= s + 10;  k:= k + 1;  end;  write\(k\); end. | s = 0 k = 0 while s &lt; 1024:  s = s + 10  k = k + 1 print\(k\) | \#include &lt;stdio.h&gt; int main\(\) { int s = 0, k = 0;  while \(s &lt; 1024\) {  s = s + 10;  k = k + 1;  }  printf\("%d", k\);  return 0; } |

4. **Запишите число, которое будет напечатано в результате выполнения следующей программы.**

   | Паскаль | Python | Си |
   | :--- | :--- | :--- |
   | var s, n: integer; begin  s := 33;  n := 1;  while s &gt; 0 do begin  s := s – 7;  n := n \* 3  end;  writeln\(n\) end. | s = 33 n = 1 while s &gt; 0:  s = s - 7  n = n \* 3 print\(n\) | \#include &lt;stdio.h&gt; int main\(\) { int n = 1, s = 33;  while \(s &gt; 0\) {  s = s - 7;  n = n \* 3;  }  printf\("%d", n\);  return 0; } |

5. **Запишите число, которое будет напечатано в результате выполнения следующей программы.**

   | Паскаль | Python | Си |
   | :--- | :--- | :--- |
   | var s, n: integer; begin  s := 0;  n := 0;  while 2\*s\*s &lt; 123 do begin  s := s + 1;  n := n + 2  end;  writeln\(n\) end. | s = 0 n = 0 while 2\*s\*s &lt; 123:  s = s + 1  n = n + 2 print\(n\) | \#include &lt;stdio.h&gt; int main\(\) { int s = 0, n = 0;  while \(2\*s\*s &lt; 123\) {  s = s + 1;  n = n + 2;  }  printf\("%d", n\);  return 0; } |

6. **Запишите число, которое будет напечатано в результате выполнения следующей программы.**

   | Паскаль | Python | Си |
   | :--- | :--- | :--- |
   | var n, s: integer; begin  n := 1;  s := 0;  while n &lt;= 300 do begin  s := s + 30;  n := n \* 5  end;  write\(s\) end. | n = 1 s = 0 while n &lt;= 300:  s = s + 30  n = n \* 5 print\(s\) | \#include &lt;stdio.h&gt; int main\(\) { int n = 1, s = 0;  while \(n &lt;= 300\) {  s = s + 30;  n = n \* 5;  }  printf\("%d", s\);  return 0; } |

7. **Запишите число, которое будет напечатано в результате выполнения следующей программы.**

   | Паскаль | Python | Си |
   | :--- | :--- | :--- |
   | var n, s: integer; begin  n := 1;  s := 0;  while n &lt;= 650 do begin  s := s + 20;  n := n \* 5  end;  write\(s\) end. | n = 1 s = 0 while n &lt;= 650:  s = s + 20  n = n \* 5 print\(s\) | \#include &lt;stdio.h&gt; int main\(\) { int n = 1, s = 0;  while \(n &lt;= 650\) {  s = s + 20;  n = n \* 5;  }  printf\("%d", s\);  return 0; } |

8. **При каком наименьшем введенном числе d после выполнения программы будет напечатано 121?**

   | Паскаль | Python | Си |
   | :--- | :--- | :--- |
   | var n, s, d: integer; begin  readln\(d\);  n := 1;  s := 46;  while s &lt;= 2700 do begin  s := s + d;  n := n + 4  end;  write\(n\) end. | d = int\(input\(\)\) n = 1 s = 46 while s &lt;= 2700:  s = s + d  n = n + 4 print\(n\) | \#include &lt;stdio.h&gt; int main\(\) { int n = 1, s = 46, d;  scanf\("%d", &d\);  while \(s &lt;= 2700\) {  s = s + d;  n = n + 4;  }  printf\("%d", n\);  return 0; } |

9. **При каком наибольшем введенном числе d после выполнения программы будет напечатано 46?**

   | Паскаль | Python | Си |
   | :--- | :--- | :--- |
   | var n, s, d: integer; begin  readln\(d\);  n := 8;  s := 78;  while s &lt;= 1200 do begin  s := s + d;  n := n + 2  end;  write\(n\) end. | d = int\(input\(\)\) n = 8 s = 78 while s &lt;= 1200:  s = s + d  n = n + 2 print\(n\) | \#include &lt;stdio.h&gt; int main\(\) { int n = 8, s = 78, d;  scanf\("%d", &d\);  while \(s &lt;= 1200\) {  s = s + d;  n = n + 2;  }  printf\("%d", n\);  return 0; } |

10. **При каком наибольшем введенном числе d после выполнения программы будет напечатано 46?**

    | Паскаль | Python | Си |
    | :--- | :--- | :--- |
    | var n, s, d: integer; begin  readln\(d\);  n := 8;  s := 78;  while s &lt;= 1200 do begin  s := s + d;  n := n + 2  end;  write\(n\) end. | d = int\(input\(\)\) n = 8 s = 78 while s &lt;= 1200:  s = s + d  n = n + 2 print\(n\) | \#include &lt;stdio.h&gt; int main\(\) { int n = 8, s = 78, d;  scanf\("%d", &d\);  while \(s &lt;= 1200\) {  s = s + d;  n = n + 2;  }  printf\("%d", n\);  return 0; } |

11. **Ниже записаны две рекурсивные функции \(процедуры\): F и G. Чему будет равно значение, вычисленное при **выполнении вызова F\(6\)?

    | Паскаль | Python | Си |
    | :--- | :--- | :--- |
    | function F\(n: integer\): integer; begin  if n &gt; 2 then  F := F\(n-1\) + G\(n-2\)  else  F := n; end; function G\(n: integer\): integer; begin  if n &gt; 2 then  G := G\(n-1\) + F\(n-2\)  else  G := n+1; end; | def F\(n\):  if n &gt; 2:  return F\(n-1\) + G\(n-2\)  else:  return n def G\(n\):  if n &gt; 2:  return G\(n-1\) + F\(n-2\)  else:  return n+1 | int F\(int n\) {  if \(n &gt; 2\)  return F\(n-1\) + G\(n-2\);  else  return n; } void G\(int n\) {  if \(n &gt; 2\)  return G\(n-1\) + F\(n-2\);  else  return n+1; } |

12. **В программе используется одномерный целочисленный массив A с индексами от 0 до 9. Значения элементов **равны 8, 4, 3, 0, 7, 2, 1, 5, 9, 6 соответственно, т.е. A\[0\]=8, A\[1\]=4 и т.д. Определите значение переменной c после выполнения следующего фрагмента этой программы.

    | Паскаль | Python | Си |
    | :--- | :--- | :--- |
    | c := 0; for i := 0 to 8 do  if A\[i\] &gt; A\[i+1\] then  begin  c := c + 1;  t := A\[i\];  A\[i\] := A\[i+1\];  A\[i+1\] := t;  end; | c = 0 for i in range\(9\):  if A\[i\] &gt; A\[i+1\]:  c = c + 1  t = A\[i\]  A\[i\] = A\[i+1\]  A\[i+1\] = t | c = 0; for \(i = 0;i &lt; 9;i++\)  if \(A\[i\] &gt; A\[i+1\]\) {  c++;  t = A\[i\];  A\[i\] = A\[i+1\];  A\[i+1\] = t;  } |

13. **Укажите наименьшее из таких чисел x, при вводе которых алгоритм печатает сначала 3, а потом 18.**

    | Паскаль | Python | Си |
    | :--- | :--- | :--- |
    | var x, a, b: integer; begin  readln\(x\);  a:=0; b:=0;  while x &gt; 0 do begin  a:= a + 1;  if x mod 2 = 0 then  b:= b + \(x mod 10\);  x:= x div 10;  end;  writeln\(a\); write\(b\); end. | x = int\(input\(\)\) a = 0 b = 0 while x &gt; 0:  a = a + 1  if x % 2 = 0:  b = b + \(x % 10\)  x = x // 10 print\(a\) print\(b\) | \#include &lt;stdio.h&gt; int main\(void\) {  int a, b, x;  scanf\(″%d″, &x\);  a = 0; b = 0;  while \(x &gt; 0\) {  a = a + 1;  if \(x % 2 == 0\)  b = b + \(x % 10\);  x = x / 10;  }  printf\(″%d\n%d″, a, b\); } |

14. **Напишите в ответе наибольшее значение входной переменной k, при котором программа выдаёт тот же ответ, что и **при входном значении k = 16.

    | Паскаль | Python | Си |
    | :--- | :--- | :--- |
    | var k, i : longint; function f\(n: longint\): longint; begin  f := n \* n \* n; end; function g\(n: longint\): longint; begin  g := 3\*n + 3; end; begin  readln\(k\);  i := 1;  while f\(i\) &lt; g\(k\) do  i := i+1;  writeln\(i\) end. | def f\(n\):  return n \* n \* n def g\(n\):  return 3\*n + 3 k = int\(input\(\)\) i = 1 while f\(i\) &lt; g\(k\):  i+=1 print \(i\) | \#include &lt;stdio.h&gt; long f\(long n\) {  return n \* n \* n; } long g\(long n\) {  return 3\*n + 3; } int main\(\) { long k, i; scanf\("%ld", &k\); i = 1; while\(f\(i\) &lt; g\(k\)\)  i++; printf\("%ld", i\); return 0; } |

15. Напишите в ответе наибольшее значение входной переменной k, при котором программа выдаёт тот же ответ, что и при входном значении k = 16.

    | Паскаль | Python | Си |
    | :--- | :--- | :--- |
    | var k, i : longint; function f\(n: longint\): longint; begin  f := n \* n \* n; end; function g\(n: longint\): longint; begin  g := 3\*n + 3; end; begin  readln\(k\);  i := 1;  while f\(i\) &lt; g\(k\) do  i := i+1;  writeln\(i\) end. | def f\(n\):  return n \* n \* n def g\(n\):  return 3\*n + 3 k = int\(input\(\)\) i = 1 while f\(i\) &lt; g\(k\):  i+=1 print \(i\) | \#include &lt;stdio.h&gt; long f\(long n\) {  return n \* n \* n; } long g\(long n\) {  return 3\*n + 3; } int main\(\) { long k, i; scanf\("%ld", &k\); i = 1; while\(f\(i\) &lt; g\(k\)\)  i++; printf\("%ld", i\); return 0; } |

16. кенкценц

17. пвапвп
18. вапвапва
19. вапывпвы
20. выапвпвпа
21. выапвапвап
22. выапвпвы
23. выапвап




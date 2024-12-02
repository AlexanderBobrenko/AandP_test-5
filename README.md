<h1 align="center">Test №5 for 💯 points</h1>
<h3 align="right">Автор: Бобренко Александр 😱</h3>

<p align="center">
  <img src="https://github.com/user-attachments/assets/98d4d2a2-be3c-4b4f-8838-7d27cb952b85" alt="minions-strong">
</p>

<h2></h2>

1) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
class A{
public:
    A(){
        std::cout << 'A';
    }
};

class B{
public:
    B(){
        std::cout << 'B';
    }
};

class C: public A, public B{
public:
    C(){
        std::cout << 'C';
    }
};

C obj();
```

---
### Ответ:
- `✅ a. Ничего`
- `⛔️ b. BAC`
- `⛔️ c. CAB`
- `⛔️ d. C`
- `⛔️ e. ABC`
- `⛔️ f. CBA`

2) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
class A{
public:
    int value = 1;
    A(){
    	value = 5;
    }
    A(int value){
    	this->value = 9;
    }
};

class B: public A{
public:
    B(int value):A(value){};
};

B obj(1);
std::cout << obj.value;
```

### Ответ:
- `✅ a. 9`
- `⛔️ b. Ошибка`
- `⛔️ c. 1`
- `⛔️ d. 5`

3) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
class A{
public:
    int value = 1;
    void set_value(int value){
        this->value = value;
    }
};

class B: public A{
public:
    int value = 1;
};

B obj;
obj.set_value(5);
std::cout << obj.value;
```

### Ответ:
- `✅ a. 1`
- `⛔️ b. Ошибка`
- `⛔️ c. 5`

4) Что из перечисленного является объявлением конструктора перемещения класса `SomeClass`?
### Ответ:
- `✅ a. SomeClass(SomeClass&& other);`
- `⛔️ b. SomeClass(SomeClass other);`
- `⛔️ c. SomeClass();`
- `⛔️ d. SomeClass(const SomeClass& other);`
- `⛔️ e. SomeClass& operator=(SomeClass&& other);`

5) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?
  
```cpp
struct А{
    int value = 1;
};

struct B: private A{
    B(int value){
        this->value = value;
    }
};

B obj(5);
std::cout << obj.value;
```

### Ответ:
- `✅ a. Ошибка`
- `⛔️ b. 1`
- `⛔️ c. 5`

6) Дан фрагмент кода на языке С++. Какой модификатор доступа у valueA в классе B ?
  
```cpp
class A{
private:
    int valueA = 1;
};

class B: public A{
public:
    int valueB = 5;
};
```

### Ответ:
- `✅ a. поле не доступно`
- `⛔️ b. published`
- `⛔️ c. private`
- `⛔️ d. public`
- `⛔️ e. protected`

7) Как заблокировать мьютекс в Go?

### Ответ:
- `✅ a. mutex.Lock()`
- `⛔️ b. mutex.Claim()`
- `⛔️ c. mutex.Wait()`
- `⛔️ d. mutex.Capture()`
- `⛔️ e. mutex.Block()`

8) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
class A{
public:
    ~A(){
        std::cout << 'A';
    }
};

class B{
public:
    ~B(){
        std::cout << 'B';
    }
};

class C: public B, public A{
public:
    ~C(){
        std::cout << 'C';
    }
};

C obj;
```

### Ответ:
- `✅ a. CAB`
- `⛔️ b. Ничего`
- `⛔️ c. CBA`
- `⛔️ d. C`
- `⛔️ e. BAC`
- `⛔️ f. ABC`

9) Как обозначается l-value ссылка на значение типа `int` в С++?

### Ответ:
- `✅ a. int&`
- `⛔️ b. int&&`
- `⛔️ c. int*`
- `⛔️ d. int^`
- `⛔️ e. int**`
- `⛔️ f. int^^`

10) Дан фрагмент кода на языке С++. Какой модификатор доступа у `valueA` в классе `B` ?

```cpp
class A{
public:
    int valueA = 1;
};

class B: private A{
public:
    int valueB = 5;
};
```

### Ответ:
- `✅ a. private`
- `⛔️ b. protected`
- `⛔️ c. published`
- `⛔️ d. public`
- `⛔️ e. поле не доступно`

11) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
struct А{
    int value = 1;
};

struct B: A{
    int value = 1;
    B(int value){
        this->value = value;
    }
};

B obj(5);
std::cout << obj.value;
```

### Ответ:
- `✅ a. 5`
- `⛔️ b. 1`
- `⛔️ c. Ошибка`

12) Как обозначается r-value ссылка на значение типа `int` в С++?

### Ответ:
- `⛔️ a. int&`
- `✅ b. int&&`
- `⛔️ c. int*`
- `⛔️ d. int^`
- `⛔️ e. int**`
- `⛔️ f. int^^`

13) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
class A{
public:
    int value = 1;
};

class B{
public:
    int value = 5;
};

class C: public A, public B{
};

C obj;
std::cout << obj.value;
```

### Ответ:
- `✅ a. Ошибка`
- `⛔️ b. 1`
- `⛔️ c. 9`
- `⛔️ d. 5`

14) Что будет выведено на экран в результате работы этого кода?

```cpp
#include <iostream>

void foo(int& a){
    std::cout << "+" << std::endl;
}

void foo(int&& a){
    std::cout << "-" << std::endl;
}

int main(){
    int a = 4;
    foo(a);
}
```

### Ответ:
- `✅ a. +`
- `⛔️ b. -`

15) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
class A{
public:
    void get(){
        std::cout << 'A';
    }
};

class B{
};

class C: public B, public A{
};

C obj;
obj.get();
```

### Ответ:
- `✅ a. A`
- `⛔️ b. AB`
- `⛔️ c. B`
- `⛔️ d. C`
- `⛔️ e. BA`
- `⛔️ f. Ошибка`

16) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
class A{
public:
    int value = 1;
    void set_value(int value){
        this->value = value;
    }
};

class B: public A{
public:
    int value = 1;
    void set_value(int value){
        this->value = value;
    }
};

B obj;
obj.set_value(5);
std::cout << obj.value;
```

### Ответ:
- `✅ a. 5`
- `⛔️ b. 1`
- `⛔️ c. Ошибка`

17) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
class A{
public:
    void get(){
        std::cout << 'A';
    }
};

class B{
public:
    void get(){
        std::cout << 'B';
    }
};

class C: public B, public A{
public:
    void get(){
        B::get();
    }
};

C obj;
obj.get();
```

### Ответ:
- `⛔️ a. A`
- `⛔️ b. AB`
- `✅ c. B`
- `⛔️ d. C`
- `⛔️ e. BA`
- `⛔️ f. Ошибка`

18) Что такое горутина в Go?

### Ответ:
- `⛔️ a. Поток с приоритетом`
- `⛔️ b. Объект, который управляет памятью`
- `⛔️ c. Функция, которая может быть вызвана только один раз`
- `✅ d. Легковесный поток выполнения`
- `⛔️ e. Переменная, хранящая данные`

19) Что будет выведено на экран в результате работы этого кода?

```cpp
#include <iostream>

void foo(int& a){
    std::cout << "+" << std::endl;
}

void foo(int&& a){
    std::cout << "-" << std::endl;
}

int main(){
    int a = 4;
    foo(a + 1);
}
```

### Ответ:
- `⛔️ a. +`
- `✅ b. -`

20) Что такое мьютекс в Go?

### Ответ:
- `⛔️ a. Функция для создания горутин`
- `✅ b. Механизм синхронизации доступа горутин к общим ресурсам`
- `⛔️ c. Интерфейс для работы с каналами`
- `⛔️ d. Тип переменной для передачи данных в горутину`
- `⛔️ e. Структура данных для хранения результата работы горутины`

21) Дан фрагмент кода на языке С++. Какой модификатор доступа у `valueA` в классе `B` ?

```cpp
struct A{
    int valueA = 1;
};

class B: protected A{
public:
    int valueB = 5;
};
```

### Ответ:
- `✅ a. protected`
- `⛔️ b. private`
- `⛔️ c. published`
- `⛔️ d. public`
- `⛔️ e. поле не доступно`

22) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
struct А{
    int value = 1;
};

struct B: A{
    B(int value){
        this->value = value;
    }
};

B obj(5);
std::cout << obj.value;
```

### Ответ:
- `⛔️ a. Ошибка`
- `✅ b. 5`
- `⛔️ c. 1`

23) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
class A{
public:
    void get(){
        std::cout << 'A';
    }
};

class B{
public:
    void get(){
        std::cout << 'B';
    }
};

class C: public B, public A{
public:
    void get(){
        std::cout << 'C';
    }
};

C obj;
obj.get();
```

### Ответ:
- `⛔️ a. ABC`
- `⛔️ b. CAB`
- `⛔️ c. CBA`
- `⛔️ d. BAC`
- `⛔️ e. Ничего`
- `✅ f. C`

24) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
class A{
public:
    A(){
        std::cout << 'A';
    }
};

class B{
public:
    B(){
        std::cout << 'B';
    }
};

class C: public B, public A{
public:
    C(){
        std::cout << 'C';
    }
};

C obj;
```

### Ответ:
- `⛔️ a. ABC`
- `⛔️ b. CAB`
- `⛔️ c. CBA`
- `✅ d. BAC`
- `⛔️ e. Ничего`
- `⛔️ f. C`

25) Что из перечисленного является объявлением конструктора копирования класса `SomeClass` ?

### Ответ:
- `⛔️ a. SomeClass(SomeClass&& other);`
- `⛔️ b. SomeClass();`
- `⛔️ c. SomeClass& operator=(SomeClass&& other);`
- `✅ d. SomeClass(const SomeClass& other);`
- `⛔️ e. SomeClass(SomeClass other);`

26) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
class A{
public:
    int value = 1;
    A(){
    	value = 5;
    }
    A(int value){
    	value = 9;
    }
};

class B: public A{
public:
    B(int value):A(value){};
};

B obj(1);
std::cout << obj.value;
```

### Ответ:
- `✅ a. 1`
- `⛔️ b. 5`
- `⛔️ c. Ошибка`
- `⛔️ d. 9`

27) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
class A{
public:
    ~A(){
        std::cout << 'A';
    }
};

class B{
public:
    ~B(){
        std::cout << 'B';
    }
};

class C: public A, public B{
public:
    ~C(){
        std::cout << 'C';
    }
};

C obj;
```

### Ответ:
- `⛔️ a. ABC`
- `⛔️ b. CAB`
- `✅ c. CBA`
- `⛔️ d. BAC`
- `⛔️ e. Ничего`
- `⛔️ f. C`

28) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
class A{
public:
    void set_value(int value){
        this->value = value;
    }
};

class B: public A{
public:
    int value = 1;
};

B obj;
obj.set_value(5);
std::cout << obj.value;
```

### Ответ:
- `⛔️ a. 5`
- `⛔️ b. 1`
- `✅ c. Ошибка`

29) Выберите все выражения, которые не вызовут ошибку, при условии, что переменная `a` объявлена как:
`int a = 4;`

### Ответ:
- `⛔️ a. int&& r8 = r4;`
- `✅ b. int&& r4 = a + 1;`
- `⛔️ c. int& r7 = r4;`
- `✅ d. int& r1 = a;`
- `✅ e. int& r5 = r1;`
- `⛔️ f. int& r3 = a + 1;`
- `⛔️ g. int&& r6 = r1;`
- `⛔️ h. int&& r2 = a;`

> [!Note]
>
> 3 варианта из 4 верны. Нужен ещё один верный пункт для 1 балла. За этот ответ получено 0.75 балла.

30) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
struct А{
    A(int value){
        this->value = value;
    }
    int value = 1;
};

struct B: A{
    B(int value){
        this->value = value;
    }
};

B obj(5);
std::cout << obj.value;
```

### Ответ:
- `⛔️ a. 5`
- `⛔️ b. 1`
- `✅ c. Ошибка`

31) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
struct А{
    int value = 1;
};

struct B: A{
    int value = 1;
    B(int value){
        this->A::value = value;
    }
};

B obj(5);
std::cout << obj.value;
```

### Ответ:
- `⛔️ a. 5`
- `✅ b. 1`
- `⛔️ c. Ошибка`
> [!Note]
>
> ???

32) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?

```cpp
class A{
public:
    void get(){
        std::cout << 'A';
    }
};

class B{
public:
    void get(){
        std::cout << 'B';
    }
};

class C: public B, public A{
};

C obj;
obj.get();
```

### Ответ:
- `⛔️ a. C`
- `⛔️ b. BA`
- `✅ c. Ошибка`
- `⛔️ d. A`
- `⛔️ e. AB`
- `⛔️ f. B`

33) Какие из следующих вариантов использования мьютекса в Go являются правильными (считаем, что в процессе работы с данными ошибки быть не может)?

### Ответ:
- `a. ⛔️`
  
  ```cpp
  func foo() {
    mutex.Lock()
    // работа с данными
  }
  ```
- `b. ✅`
  
  ```cpp
  func foo() {
    mutex.Lock()
    defer mutex.Unlock()
    // работа с данными
  }
  ```
- `c. ⛔️`
  
  ```cpp
  func foo() {
    mutex.Unlock()
    // работа с данными
  }
  ```
- `d. ✅`
  
  ```cpp
  func foo() {
    mutex.Lock()
    // работа с данными
    mutex.Unlock()
  }
  ```
- `e. ⛔️`
  
  ```cpp
  func foo() {
    mutex.Unlock()
    // работа с данными
    mutex.Lock()
  }
  ```

  34) Как разблокировать мьютекс в Go?

  ### Ответ:
- `⛔️ a. mutex.Delete()`
- `⛔️ b. mutex.Release()`
- `✅ c. mutex.Unlock()`
- `⛔️ d. mutex.Exit()`
- `⛔️ e. mutex.Free()`

  35) Как запустить горутину в Go?
  
  ### Ответ:
- `⛔️ a. defer funcName()`
- `⛔️ b. funcName() as goroutine`
- `✅ c. go funcName`
- `⛔️ d. funcName() go`
- `⛔️ e. go funcName()`

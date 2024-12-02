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

> [!Note]
>
> Похожие вопросы ...

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

6) Дан фрагмент кода на языке С++. Что будет на экране в результате выполнения данного фрагмента?
  
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

C obj;
```

### Ответ:
- `✅ a. ABC`
- `⛔️ b. C`
- `⛔️ c. CAB`
- `⛔️ d. BAC`
- `⛔️ e. CBA`
- `⛔️ f. Ничего`

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


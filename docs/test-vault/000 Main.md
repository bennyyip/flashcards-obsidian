---
cards-deck: TEST::Main
---
This is the test vault. 

WORK IN PROGRESS

# TEST my heading #card 

foo bar



# TEST What is perfect forwarding? #card

```cpp
void g(MyString &&t);
void g(MyString &t);



template <typename T>
void f(T &&t) {
    g(std::forward<T>(t));
}
```
test foo
test bar
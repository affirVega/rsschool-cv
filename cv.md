# Ilya Feskov

## Contacts

**E-mail**: [feskow.ilya@ya.ru](mailto:feskow.ilya@ya.ru)  
**Telegram**: [@affirvega](https://affirvega.t.me)  
**Discord**: `Феся#9356`, rs-school name `Ilya Feskov (@affirvega)`

---

## About me

I'm a software developer with a broad knowledge base in various topics of the IT world. My goal is to create software I would like to use and that anyone can use without much problems.

I help my friends from University a lot. This helps me to learn to explain my code and better understand topics that I study.

I work at repair shop for electronics in my city, I'm solving clients' problems: reinstall windows, disassemble laptops and computers and do various diagnostics.

Some of the projects that I've made:
- University tasks given by a professor (like codewars katas) with couple of large projects (a game, client-server application, application that uses weather api): [Programming](https://github.com/affirVega/Programming)
- A silly game about a bar fight developed with friends in order to learn Godot: [Island Fighter](https://github.com/affirVega/IslandFighter)
- Implemented a simple feature for a cross-patform screenshot tool: [Flameshot commit](https://github.com/flameshot-org/flameshot/pulls?q=is%3Apr+up+down+is%3Aclosed)

---

## Skills

I know these technologies:

- C++ OOP, RAII, std
- Python OOP, decorators, lambda
- HTML, CSS, JS
- Java basics
- Git basics
- Qt framework


## Code example

This code is taken from CodeWars kata "[Unique In Order](https://www.codewars.com/kata/54e6533c92449cc251001667)". I wrote template function that accepts generic vector of elements and spits out vector of unique elements in order that they appear in the input. Code shows a function for a generic vector and a specialization for a string.

```c++
#include <string>
#include <vector>

template <typename T> std::vector<T> uniqueInOrder(const std::vector<T>& iterable){
if (iterable.size() == 0) { return {}; }

auto it = iterable.begin(), end = iterable.end();
std::vector<T> res { *( it++ ) };
for (; it != end; ++it)
    if (*it != res.back())
    res.push_back(*it);
return res;
}
std::vector<char> uniqueInOrder(const std::string& iterable){
if (iterable.size() == 0) { return {}; }

auto it = iterable.begin(), end = iterable.end();
std::vector<char> res { *( it++ ) };
for (; it != end; ++it)
    if (*it != res.back())
    res.push_back(*it);
return res;
}
```

## Working experience

University projects:
- [Weather widget](https://github.com/affirVega/Programming/tree/master/Lab/01)  
  Tools used:  
  - C++ json, http library
  - Python tkinter
  - openweather api

- [Yandex.Alice shopping cart](https://github.com/affirVega/Programming/tree/master/Lab/02)  
  Tools used:
  - C++ json, http library
  - Python excel library
  - Webhooks (ngrok)

- [Lines game with colored balls](https://github.com/affirVega/Programming/tree/master/Lab/03)  
  Tools used:
  - Python tkinter, PIL

- [Image Steganography](https://github.com/affirVega/Programming/tree/master/Lab/05)  
  <img src="https://github.com/affirVega/Programming/raw/master/Lab/05/docs/gui.png" alt="application ui with several buttons and input form" width=300>  
  Tools used:
  - C++
  - Qt framework

---

## Education

### Programming Engineer
2020 - present time.  
Vernadsky Crimean Federal University.

### JS / Frontend. Stage 0
2022 - present Time.  
The Rolling Scopes School

## Languages

**Russian**: native speaker  
**English**: intermediate, understand technical docs, spoke with native speakers
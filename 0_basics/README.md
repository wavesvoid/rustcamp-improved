# Step 0: Building Up an Vocabulary
========================================
## Contents
1. [General information][nav-1]
    - [Requirements][nav-1-1]
    - [Prerequisites][nav-1-2]
2. [Theoretical information][nav-2]
3. [Knowledge check-in][nav-3]
    - 3.1. [Memory Model][nav-qa-1]
    - 3.2. [Runtime][nav-qa-2]
    - 3.3. [Typing System][nav-qa-3]
    - 3.4. [Generics][nav-qa-4]
    - 3.5. [Traits][nav-qa-5]
    - 3.6. [Dispatching][nav-qa-6]
    - 3.7. [Module System][nav-qa-7]
    - 3.8. [Move Semantics][nav-qa-8]
    - 3.9. [Immutability][nav-qa-9]
    - 3.10. [RAII][nav-qa-10]
    - 3.11. [Lifetimes][nav-qa-11]
    - 3.12. [Iterators][nav-qa-12]
    - 3.13. [Macros][nav-qa-13]
    - 3.14. [Testing][nav-qa-14]
    - 3.15. [Memory Layout][nav-qa-15]
    - 3.16. [Slices][nav-qa-16]
    - 3.17. [OOP][nav-qa-17]
  
---
## 1. General information
__Estimated time__: 4 days

#### Requirements
> ❗️ To meet the first deadline, please open a Pull Request by Sunday of the first week and include answers to at least one question in it.
> After you're done notify your lead in an appropriate PR (pull request), and he will exam what you have learned.

#### Prerequisites
- Read through [Rust Book], [Rust FAQ], and become familiar with basic [Rust] concepts, syntax, memory model, type and module systems.
- Polish your familiarity by completing [Rust By Example] and [rustlings].
- Read through [Cargo Book] and become familiar with [Cargo] and its workspaces.

After completing these steps, including [this theory][nav-2], you should be able to answer (and understand why) the following questions [below][nav-3].

---
## 2. Theory Section

_Additional_ articles, which may help to understand the above topic better:
- [ ] [Chris Morgan: Rust ownership, the hard way][1]
- [ ] [Adolfo Ochagavía: You are holding it wrong][23]
- [ ] [Vikram Fugro: Beyond Pointers: How Rust outshines C++ with its Borrow Checker][30]
- [ ] [HashRust: A guide to closures in Rust][24]
- [ ] [Ludwig Stecher: Rusts Module System Explained][2]
- [ ] [Tristan Hume: Models of Generics and Metaprogramming: Go, Rust, Swift, D and More][3]
- [ ] [Jeff Anderson: Generics Demystified Part 1][4]
- [ ] [Jeff Anderson: Generics Demystified Part 2][5]
- [ ] [Bradford Hovinen: Demystifying trait generics in Rust][25]
- [ ] [Brandon Smith: Three Kinds of Polymorphism in Rust][6]
- [ ] [Jeremy Steward: C++ & Rust: Generics and Specialization][7]
- [ ] [cooscoos: &stress about &Strings][8]
- [ ] [Jimmy Hartzell: RAII: Compile-Time Memory Management in C++ and Rust][9]
- [ ] [Trait Drop][10]
- [ ] [Common Lifetime Misconception][11]
- [ ] [Visualizing Memory Layout][12]
- [ ] [Package vs. Crate terminology (r/rust)][13]
- [ ] [Packages and crates (Rust wiki)][14]
- [ ] [Full list of available crates on Rust Playground][16]
- [ ] [Blanket impl definition][17]
- [ ] [Auto-trait definition][18]
- [ ] [Georgios Antonopoulos: Rust vs Common C++ Bugs][21]
- [ ] [Yurii Shymon: True Observer Pattern with Unsubscribe mechanism using Rust][22]
- [ ] [Asynchronous vs Multithreading][29]

Additional:
- [ ] [Rust API guidline checklist][19]
- [ ] [Interview Questions on Rust Programming][20]
- [ ] [Step-by-step instruction to start development in Rust][26]
- [ ] [Awesome collection of crates for productive development in Rust][27]
- [ ] [Awesome Collection of Materials to Learn Rust][28]


---
## 3. Knowledge check-in

<details>
  <summary><h3>1. Multithreading & Memory model</h3></summary>

#### 1. What memory model [Rust] has?
> ?

#### 1.1. Is it single-threaded or multiple-threaded?
> ?

#### 1.2. Is it synchronous or asynchronous?
> ?

#### 1.3. What is the memory layout of the box and vector?  
> ?

#### 1.4. What are heap and stack?
> ?

#### 1.5. Where, but on heap and stack data could live in RAM?
> ?

---
</details>


<details>
<summary><h3>2. Runtime</h3></summary>

#### 2.1 What runtime [Rust] has?
> ?

#### 2.2. Does it use a GC (garbage collector)?  
> ?

---
</details>


<details>
  <summary><h3>3. Typing System</h3></summary>

#### 3.1 What statically typing means?
> ?

#### 3.2. What is a benefit of using it?
> ?

#### 3.3. Weak typing vs strong typing?
> ?

#### 3.4. Implicit / explicit?
> ?

#### 3.5. What is nominative typing and structural typing?
> ?

#### 3.6. What is difference?
> ?

---
</details>


<details>
<summary><h3>4. Generics</h3></summary>
    
#### 4.1. What are generics and parametric polymorphism?
> ?

#### 4.2. Which problems do they solve?
> ?

---
</details>


<details>
<summary><h3>5. Traits</h3></summary>

#### 5.1. What are traits?
> ?

#### 5.2. How are they used?
> ?

#### 5.3. How do they compare to interfaces?
> ?

#### 5.4. What are an auto trait and a blanket implementation?
> ?

#### 5.5. Uncovered type?
> ?

#### 5.6. What is a marker trait?
> ?

---
</details>



<details>
<summary><h3>6. Dispatching. Monomorphisation</h3></summary>

#### 6.1. What are static and dynamic dispatching?
> ?

#### 6.2. Which should I use, and when?
> ?

#### 6.3. What is monomorphisation?
> ?

---
</details>


<details>
<summary><h3>7. Crates & Module System</h3></summary>
    
#### 7.1. What is a crate, module and package in Rust?
> ?

#### 7.2. How do they differ?
> ?

#### 7.3. How are the used?
> ?

#### 7.4. What is workspace?
> ?

---
</details>


<details>
<summary><h3>8. Cloning & Move semantics</h3></summary>

#### 8.1. What is cloning?
> ?

#### 8.1.1. What is copying?
> ?

#### 8.1.2. How do they compare?
> ?

#### 8.1.3. What is drop trait used for?
> ?    

#### 8.1.4. What is special about the trait?
> ?

#### 8.2. What are move semantics?
> ?

#### 8.2.1. What are borrowing rules?
> ?

#### 8.2.2. What is the benefit of using them?
> ?

---
</details>


<details>
<summary><h3>9. Immutability</h3></summary>

#### 9.1. What is immutability?
> ?

#### 9.2. What is the benefit of using it?
> ?

#### 9.3. What is the difference between immutability and const?
> ?

---
</details>
    

<details>
<summary><h3>10. RAII</h3></summary>

#### 10.1. What is RAII?
> ?

#### 10.2. How is it implemented in [Rust]?
> ?

#### 10.3. What is the benefit of using it?
> ?
</details>


<details>
<summary><h3>11. Lifetimes</h3></summary>

#### 11.1. What are lifetimes?
> ?

#### 11.2. Which problems do they solve?
> ?

#### 11.3. Which benefits do they give?
> ?

---
</details>


<details>
<summary><h3>12. Iterators & Collections</h3></summary>

#### 12.1. What is an iterator?
> ?

#### 12.2. What is a collection?
> ?

#### 12.3. How do they differ?
> ?

#### 12.4. How are they used?
> ?

---
</details>


<details>
<summary><h3>13. Macro System</h3></summary>

#### 13.1. What are macros?
> ?

#### 13.2. Which problems do they solve?
> ?

#### 13.3. What is the difference between declarative and procedural macro?
> ?

---
</details>


<details>
<summary><h3>14. Testing</h3></summary>

#### 14.1. How code is tested in [Rust]?
> ?

#### 14.2. Where should you put tests and why?
> ?

---
</details>


<details>
<summary><h3>15. Memory Layout & Pointers</h3></summary>

#### 15.1. What is layout of Rust standard data types?
> ?

#### 15.2. Difference between fat and thin pointers?
> ?

---
</details>


<details>
<summary><h3>16. Strings & Slices</h3></summary>

#### 16.1. What is special about slice?
> ?

#### 16.2. Why [Rust] has `&str` and `String` types?
> ?

#### 16.3. How do they differ?
> ?

#### 16.4. When should you use them?
> ?

#### 16.5. Why str slice coexist with slice?
> ?

#### 16.6. What is differnece between `String` and `Vec`?
> ?

---
</details>


<details>
<summary><h3>17. OOP & Patterns</h3></summary>

#### 17.1. Is [Rust] OOP language? 
> ?

#### 17.2. Is it possible to use SOLID/GRASP?
> ?

#### 17.3. Does it have an inheritance?
> ?

#### 17.4. Is Rust functional language?
> ?

#### 17.5. What variance rules does Rust have?
> ?

---
</details>


[nav-1]: #1-general-information
[nav-1-1]: #requirements
[nav-1-2]: #prerequisites

[nav-2]: #2-theory-section

[nav-3]: #3-knowledge-check-in
[nav-qa-1]: #1-multithreading--memory-model
[nav-qa-2]: #2-runtime
[nav-qa-3]: #3-typing-system
[nav-qa-4]: #4-generics
[nav-qa-5]: #5-traits
[nav-qa-6]: #6-dispatching-monomorphisation
[nav-qa-7]: #7-crates--module-system
[nav-qa-8]: #8-cloning--move-semantics
[nav-qa-9]: #9-immutability
[nav-qa-10]: #10-raii
[nav-qa-11]: #11-lifetimes
[nav-qa-12]: #12-iterators--collections
[nav-qa-13]: #13-macro-system
[nav-qa-14]: #14-testing
[nav-qa-15]: #15-memory-layout--pointers
[nav-qa-16]: #16-strings--slices
[nav-qa-17]: #17-oop--patterns




[Cargo]: https://github.com/rust-lang/cargo
[Cargo Book]: https://doc.rust-lang.org/cargo
[Rust]: https://www.rust-lang.org
[Rust Book]: https://doc.rust-lang.org/book
[Rust By Example]: https://doc.rust-lang.org/rust-by-example
[Rust FAQ]: https://prev.rust-lang.org/faq.html
[rustlings]: https://rustlings.cool

[1]: https://chrismorgan.info/blog/rust-ownership-the-hard-way
[2]: https://aloso.github.io/2021/03/28/module-system.html
[3]: https://thume.ca/2019/07/14/a-tour-of-metaprogramming-models-for-generics
[4]: https://web.archive.org/web/20220525213911/http://jeffa.io/rust_guide_generics_demystified_part_1
[5]: https://web.archive.org/web/20220328114028/https://jeffa.io/rust_guide_generics_demystified_part_2
[6]: https://www.brandons.me/blog/polymorphism-in-rust
[7]: https://www.tangramvision.com/blog/c-rust-generics-and-specialization#substitution-ordering--failures
[8]: https://cooscoos.github.io/blog/stress-about-strings
[9]: https://www.thecodedmessage.com/posts/raii
[10]: https://vojtechkral.github.io/blag/rust-drop-order/
[11]: https://github.com/pretzelhammer/rust-blog/blob/master/posts/common-rust-lifetime-misconceptions.md
[12]: https://www.youtube.com/watch?v=rDoqT-a6UFg
[13]: https://www.reddit.com/r/rust/comments/lvtzri/confused_about_package_vs_crate_terminology/
[14]: https://rustwiki.org/en/book/ch07-01-packages-and-crates.html
[16]: https://github.com/integer32llc/rust-playground/blob/master/compiler/base/Cargo.toml
[17]: https://doc.rust-lang.org/reference/glossary.html#blanket-implementation
[18]: https://doc.rust-lang.org/reference/special-types-and-traits.html#auto-traits
[19]: https://rust-lang.github.io/api-guidelines/checklist.html
[20]: https://iq.opengenus.org/questions-on-rust/
[21]: https://geo-ant.github.io/blog/2022/common-cpp-errors-vs-rust
[22]: https://web.archive.org/web/20230319015854/https://ybnesm.github.io/blah/articles/true-observer-pattern-rust
[23]: https://ochagavia.nl/blog/you-are-holding-it-wrong
[24]: https://hashrust.com/blog/a-guide-to-closures-in-rust
[25]: https://gruebelinchen.wordpress.com/2023/06/06/demystifying-trait-generics-in-rust
[26]: https://github.com/rust-lang-ua/learn_rust_together/blob/master/introduction.md
[27]: https://github.com/rust-lang-ua/learn_rust_together/blob/master/toolbox_general.md
[28]: https://github.com/rust-lang-ua/learn_rust_together/blob/master/learn.md
[29]: https://github.com/Learn-Together-Pro/ComputerScience/blob/master/gcs/cheatsheets.md#asynchronous-vs-multithreading
[30]: https://dev.to/vikram2784/beyond-pointers-how-rust-outshines-c-with-its-borrow-checker-1mad

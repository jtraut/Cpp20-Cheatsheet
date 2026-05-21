# Modern C++20 Cheat Sheet & Interview Reference

A single-file HTML reference guide for modern C++ (C++20), covering everything from fundamentals to advanced features. Designed for interview prep and day-to-day lookup.

## Contents

- **Why C++** — when to use it, strengths, limitations
- **Mental model** — stack vs. heap, value semantics, ownership
- **Compile & build** — compiler flags, CMake basics
- **Types & literals** — integral, floating-point, `auto`, type deduction
- **Variables** — `auto`, `const`, `constexpr`, `if constexpr`
- **References vs. pointers** — semantics, `nullptr`, `std::optional`
- **Control flow** — range-for, structured bindings, `if`/`switch` init
- **Functions & lambdas** — overloading, default args, captures, `std::function`
- **Errors & exceptions** — `try`/`catch`, `noexcept`, `std::expected`
- **Strings & formatting** — `std::string`, `string_view`, `std::format` (C++20)
- **Arrays & `std::array`**
- **STL containers** — `vector`, `map`, `unordered_map`, `set`, `deque`, `list`
- **Utilities** — `pair`, `tuple`, `optional`, `variant`
- **Iterators & ranges** — iterators, range-based algorithms, views (C++20)
- **STL algorithms** — sort, find, transform, reduce, and more
- **Complexity reference** — big-O for common containers and operations
- **Classes & structs** — constructors, member functions, `explicit`, `friend`
- **Rule of 0 / 3 / 5** — copy, move, RAII
- **Inheritance & polymorphism** — `virtual`, `override`, `final`, vtables
- **Smart pointers & RAII** — `unique_ptr`, `shared_ptr`, `weak_ptr`
- **Templates** — function & class templates, SFINAE, variadic templates
- **Concepts** (C++20) — `requires`, standard concepts, constrained templates
- **Idioms** — CRTP, PIMPL, tag dispatch
- **Ranges deep-dive** (C++20) — lazy views, pipe syntax, custom ranges
- **Coroutines** (C++20) — `co_await`, `co_yield`, `co_return`
- **Modules** (C++20) — `export module`, `import`
- **C++20 misc** — `std::format`, `std::span`, spaceship operator `<=>`
- **Threads & `jthread`** — `std::thread`, `std::jthread`, thread lifecycle
- **Mutexes, locks, atomics** — `mutex`, `lock_guard`, `atomic`
- **async / future / promise** — `std::async`, `std::future`
- **Idioms cheat sheet** — RAII, copy-and-swap, NVI, type erasure
- **Pitfalls, UB & surprises** — common undefined behavior and gotchas
- **Interview Q&A flash cards** — curated questions with concise answers

## Usage

**Live site:** [https://jtraut.github.io/Cpp20-Cheatsheet/](https://jtraut.github.io/Cpp20-Cheatsheet/)

Or open `cpp20-cheatsheet.html` directly in any modern browser — no build step or server required.

The sidebar provides quick navigation to any section. Code blocks include syntax highlighting (via [highlight.js](https://highlightjs.org/)) and a copy button.

## Requirements

- A modern browser (Chrome, Firefox, Edge, Safari)
- Internet access for CDN-hosted highlight.js (or host it locally for offline use)

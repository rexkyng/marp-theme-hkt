---
marp: true
theme: hkt
backgroundImage: url('images/bg.png')
paginate: true
---

<!--
_backgroundImage: url('images/bg_cover.png')
_paginate: false
-->
<style scoped>h1,h2,h3{margin-left:15px;color:var(--background-color)}h1{margin-top:175px;margin-bottom:5px;font-size:53px}h2{font-size:40px}h3{position:absolute;bottom:10px;font-size:24px}</style>

# Marp Theme

## Rex Ng

<h3 id="date">{date}</h3>
<!-- smart date -->
<script>window.addEventListener("load",function(){const monthNames=["January","February","March","April","May","June","July","August","September","October","November","December",];const date=new Date();const month=monthNames[date.getMonth()];const year=date.getFullYear();document.getElementById("date").innerHTML=month+" "+year})</script>

---

# Agenda

1. first
2. second
3. third

---

# Content

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

---

# Code test

```rs
fn fib(n: u32) -> u32 {
    match n {
        0 => 0,
        1 => 1,
        _ => fib(n - 1) + fib(n - 2),
    }
}

fn main() {
    let n = 10;
    let result = fib(n);
    println!("{}", result); // Output: 55
}
```

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

---

<!--
_backgroundImage: url('images/bg_alt.png')
-->
<style scoped>section{height:100%;width:100%;display:flex;align-items:center}h1{font-size:107;font-style:italic;font-weight:900}</style>

# Q&A

---

<!--
_backgroundImage: url('images/end.png')
_paginate: false
-->
<style scoped>section{height:100%;width:100%;display:flex;align-items:center}h1{color:var(--background-color);font-size:107;font-style:italic;font-weight:900}</style>

# Thank You

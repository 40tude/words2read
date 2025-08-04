## Intro
* This is a tool for my blog ([40tude.fr](https://www.40tude.fr/))
* Evaluate, in a markdown file, the number of words which will be read once the post (in .md format) is converted into html (think about Jekyll for GitHub for example)
* Can help to decide if it is time to split the post in 2
* Basically the app opens the markdown file then it remove
    * code section
    * comments
    * front matter
    * ...
    * Count the remaining words
    * If the count is above the limit (3_000) then the first string after the limit is displayed. This helps to find it later.


## Usage
* `words2read ./mandelbrot_multithread.md` 
* `words2read "C:\Users\phili\OneDrive\Documents\40tude.github.io\docs\06_programmation\rust\011_api_heroku\api_heroku.md"`




## Install
```Powershell
cargo install --path .
```









## About contributions
This project is developed for personal and educational purposes. Feel free to explore and use it to enhance your own learning in Rust and algorithm.

Given the nature of the project, external contributions are not actively sought nor encouraged. However, constructive feedback aimed at improving the project (in terms of speed, accuracy, comprehensiveness, etc.) is welcome. Please note that this project is being created as a hobby and is unlikely to be maintained once my initial goal has been achieved.
# website-portfolio
My 1st portfolio-website

//заметка для себя:
При компиляции через gulp, вложенность & > a не компилировалась правильно.
Пример: 
body {
  background-color: gray;
  & > a {
    text-decoration: none;
  }
}
НЕ компилирует как:
body { 
  background-color: gray;
}
body > a {
  text-decoration: none;
}
*хотя компилируется правильно через prepros

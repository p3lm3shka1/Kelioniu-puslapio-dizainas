# Project for "Vilnius Coding School"

This project is a responsive website design made with nesting and SASS. It includes different website sections like navigation, hero , gallery, contact form, and footer. The design automatically changes to fit phones, tablets, and desktop screens.

# Links

[Repository URL](https://github.com/p3lm3shka1/Kelioniu-puslapio-dizainas)

[Live site URL](https://p3lm3shka1.github.io/Kelioniu-puslapio-dizainas/)


## Project Setup & SCSS Compilation Process

This project was built using HTML, SCSS.

## SCSS Workflow

All styling in this project is written in SASS and compiled into a single ```styles.css``` file.

### Process of creating the SCSS files:

Split the styling into several SCSS partials such as:

```_variables.scss``` — color palette and global variables

```_mixins.scss``` — reusable functions and mixins

```style.scss``` — main file that imports all partials

Compiled SCSS into CSS using a npm script and Live Sass Complier:

```
sass styles/styles.scss styles/styles.css
```

The compiled CSS file (styles.css) is then linked in index.html.

## Responsive design with **@media**

<details>
  <summary>Mobile version</summary>
  
  ```
@media (min-width: 480px) and (max-width: 768px)
```
<img width="400" height="700" alt="image" src="https://github.com/user-attachments/assets/e0a044f3-daee-458c-b4c9-ed7c209f57a6" />

</details>  

<details>
  <summary>Tablet version</summary>
  
  ```
@media (min-width: 769px) and (max-width: 1024px)
```

</details>  

<details>
<summary>Desktop version</summary>
<img width="1200" height="500" alt="image" src="https://github.com/user-attachments/assets/69784b15-df32-4286-bf54-07903b49dbc7" />

</details>

## Author
### Vitalijus Lazarev
### Website - https://github.com/p3lm3shka1

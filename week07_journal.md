# Week 7

## Learning Activities & Resources (outside this week's lecture videos)
- [How to create a custom WordPress theme - Youtube](https://www.youtube.com/watch?v=-h7gOJbIpmo)

## Estimated Hours
~ 2.5 hours

## Content Insights

### Key theme files in a custom theme:
A WordPress theme consits of essential PHP files that control different aspects of the website.
- style.css 
- functions.php - able to aadd custom functionality such as enqueing styles
- index.php - the main template file
- header.php - the site's head section and navigation
- footer.php
- sidebar.php - if applicable
- single.php - tempalte for individual posts
- page.php - template for individual pages
- archive.php - template for category, tag and archives

I believe that understanding these core files is important because they form the foundation of any WordPress theme. Each file serves a specific purpose in the theme architecture, allowing for modular development and separation of concerns. 

### Template heirarchy for dynamic content:
- WordPress selects the right template based on heirarchy.
- For example:
    - If a user visits a category page, WordPress checks for these templates in order:
        - category-slug.php
        - category-ID.php
        - category.php
        - archive.php
        - index.php

This may allow developers to create both highly specific templates for particular content and general templates as fallbacks. Without this system, we would need to manually determine which template to use for each page request, making theme development much more complex and error-prone.

### WordPress loop:
- The loop is how WordPress fetches and displays posts dynamically.
- This concept is very important for the project and to make sure our theme is reusable.

### Hooks:
- Hooks allow adding or modifying theme functionality without changing core files.
- Example:
    ```
    function my_custom_footer_text() {
    echo '<p>Powered by My Custom Theme.</p>';
    }
    add_action('wp_footer', 'my_custom_footer_text');
    ```
- Hooks keep my modifications separate and upgrade-safe.


## Career/Employability/Learning Insights

### Career:
Enhancing my skills in WordPress theme development opens up opportunities to work as a freelancer or join specialised agencies. Building custom themes also lays the groundwork for developing premium products or contributing to open-source projects.

### Employability:
Completing a WordPress theme project not only strengthens my technical abilities in PHP, HTML, CSS, and JavaScript but also builds a solid portfolio. This demonstration of hands-on experience is a significant asset for future employers looking for well-rounded web development skills.

### Learning Insights:
This project has deepened my understanding of modular design and best practices in web development. It has ignited interests in related areas like WooCommerce integration, headless WordPress with React, and custom Gutenberg block development—each representing the next level in my professional skill tree. Like an RPG game!
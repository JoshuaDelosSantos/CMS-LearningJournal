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

### Template heirarchy for dynamic content:
- WordPress selects the right template based on heirarchy.
- For example:
    - If a usre visits a category page, WordPress checks for these templates in order:
        - category-slug.php
        - category-ID.php
        - category.php
        - archive.php
        - index.php

### WordPress loop:
- The loop is how WordPress fetches and displays posts dynamically.
- This concept is very important for the project and to make sure our theme is reusable.

### Hooks:
- Hools allow adding or modifying theme functionality without chaning core files.
- Example:
    ```
    function my_custom_footer_text() {
    echo '<p>Powered by My Custom Theme.</p>';
    }
    add_action('wp_footer', 'my_custom_footer_text');
    ```

## Career/Employability/Learning Insights

### Career:
- I could start as a freelancer, building custom themes for clients, and later move into an agency or create premium themes for sale!

### Employability:
- Working with PHP, HTML, CSS and JS will potentially improve my full-stack web development skills.
- Having a WordPress theme project published will be a great addition to my portfolio and my CV.

### Learning Insights:
- Learning about creating custom themes has unlocked new interests. It's like unlocking a basic skill in a game, after unlocking a basic skill, we are then presented with a more advanced skill within the skill tree. These 'skills' for me could be: WooCommerce, Headless WordPress with React and Building custom Gutenberg blocks.
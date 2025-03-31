# Week 9

## Learning Activities & Resources (outside this week's lecture videos)
- [Sass / SCSS COMPLETE Tutorial (+ Node.js & NPM) - Youtube](https://www.youtube.com/watch?v=ztEY-uber4U)
- [SASS Setup in 5 minutes! Super Easy Setup with node.js - Youtube](https://www.youtube.com/watch?v=q5T1ObJxj2o)

## Estimated Hours
~ 1hr

## Content Insights

- Sass introduces variables, nesting, mixins, and functions, which streamline CSS coding and improve maintainability.  
  - Using these features reduces repetition and the risk of errors while simplifying the overall structure of stylesheets.  
  **Example:**  
  ````scss
  // Define a variable and use it within nested selectors.
  $primary-colour: #3498db;

  .button {
    background-colour: $primary-colour;
    padding: 10px;
    &:hover {
      background-colour: darken($primary-colour, 10%);
    }
  }
  ````

- Using a preprocessor like Sass helps to organise styles efficiently and facilitates easier updates across larger projects.
    - With Sass, you can break your CSS into smaller, manageable partials and import them where needed. This modular approach makes it easier to maintain and update your code in collaborative or large-scale projects.
- The integration of Node.js and NPM for Sass setup reflects modern development workflows and enhances practical skill sets.
    - Node.js and NPM allows the automation of tasks such as compiling Sass to CSS, making the development process more efficient and aligning my skills with industry standards.

## Career/Employability/Learning Insights

### Career:
- Mastery of Sass complements my growing proficiency in front-end development, which might give me a competitive edge in technical roles.
    - I think understanding preprocessors demonstrates adaptability to evolving web technologies, an essential quality for long-term career growth in development.
- An understanding of modern styling techniques is important as these methods promote efficiency, scalability, and high-quality design. Embracing tools such as Sass allows for:
    - Faster development and maintenance through variables, mixins, and nesting.
    - Improved code organization and modularity, making large projects more manageable.
- These skills are valuable for roles that demand quick adaptation to evolving web technologies and provide a competitive edge in the field of web development.

### Employability:
- Practical experience with Sass will enhance my portfolio and highlights my capability to work with contemporary web development tools.
- Knowledge of integrating Sass with Node.js and NPM is a marketable skill, particularly for positions requiring experience with automated build processes.

### Learning Insights:
- Delving into Sass has not only improved my technical skills but also reinforced the importance of writing maintainable, organised code.
- This week's content emphasised how abstraction and modularity can simplify complex projects and make future modifications easier.
- The hands-on challenge of integrating Sass into a live development workflow has further developed my problem-solving abilities and confidence in modern CSS frameworks.
![Frontend Mentor](https://img.shields.io/badge/Frontend%20Mentor-Challenge-4BC0F0?logo=frontendmentor&logoColor=white) ![#87](https://img.shields.io/badge/%238-red) [![Live Preview](https://img.shields.io/badge/Live-Preview-green)](https://svitlanarudova.github.io/testimonials-grid-section/)

# Frontend Mentor - Testimonials grid section
![Design preview for the Testimonials grid section](./preview.jpg)

## Project Overview 📋 

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).

## Built With 🛠️

- Semantic HTML5 markup
- CSS custom properties (variables)
- Flexbox and Grid
- **`clamp()` function** for responsive typography and spacing
- **Component-based approach** to organizing styles
- Logical CSS properties (`inline-size`, `block-size`, `margin-block`)
- Mobile-first workflow

##  What I Learned💡
1. Built a universal grid layout that adapts to new content.
2. Learned to manage varying text lengths without breaking the design.
3. How to create a flexible and reusable CSS grid layout using :nth-of-type() selectors.
   

## Challenges I Faced 🚧

The main one was making the grid adapt to different amounts of content without breaking the overall structure. I wanted each card to look balanced even when the text length varied, but this turned out to be tricky.


## My Approach / Solution ✅

I made my grid layout more flexible by using :nth-of-type(5n+1), :nth-of-type(5n+2), and so on. This allows me to add new articles without breaking the structure of the grid.

To maintain visual balance, I ensured that each card has roughly the same amount of text as its “partners.” I considered limiting the text height and adding overflow-y: auto;, but I decided against it because it looked awkward from a design perspective. Instead, keeping the text lengths consistent proved to be a simpler and more visually pleasing solution.


##  Acknowledgments 🙏
Thanks to Frontend Mentor for providing this challenge and to the community for their helpful feedback and resources on modern CSS techniques.


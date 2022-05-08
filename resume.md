## Use cases flex vs Grid
Let’s sum it up by looking at a few concrete use cases, roughly top-down in the layout process:
#### “I want to implement my entire site’s wireframe layout.”
- Use CSS Grid for this 2D layout.
- Consider using grid areas for readable code that assigns your main site components to grid areas.

#### “I want to finely control the alignment of items.”
- Use CSS Flexbox for this typically 1D layout. It lets you finely control the flex item alignment, justification, size, order, overall direction, and the strategy for taking up the remaining space.

##### “I want to implement the layout for one of my page components.”
- Use Flexbox if the component is linear.
- Use CSS Grid if the component has a grid-like layout. You may use Flexbox (or more grid-based layouts) for its child components.

#### “I want to have overlapping items.”
- Use CSS Grid for this as it allows you to overlap the rows and columns an item spans.

## References

1. https://medium.com/nextux/form-design-best-practices-9525c321d759
2. https://github.com/AT-UI/feather-font
3. https://www.joshwcomeau.com/animation/keyframe-animations/
4. https://blog.logrocket.com/create-responsive-mobile-menu-with-css-no-javascript/
5. https://www.shutterstock.com/blog/best-fonts-for-websites
6. https://www.sliderrevolution.com/design/font-combinations/
7. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout
8. https://www.figma.com/file/gnOgGyceQU7kNFnM0SPi4Y/Designer-Portfolio-Website-Template-(Community)?node-id=0%3A1


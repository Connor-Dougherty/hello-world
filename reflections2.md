#4-2
## 1. Text decoration
  #### * Breakpoints and media queries
  ###### * You can also use variant modifiers to target media queries like responsive breakpoints, dark mode, prefers-reduced-motion, and more. For example, use md:underline to apply the underline utility at only medium screen sizes and above.
## 2. Background Image
  #### * Arbitrary values
  ###### * If you need to use a one-off background-image value that doesn’t make sense to include in your theme, use square brackets to generate a property on the fly using any arbitrary value.
## 3. Transitions & Animation
  #### * Hover, focus, and other states
  ###### * Tailwind lets you conditionally apply utility classes in different states using variant modifiers. For example, use hover:duration-150 to only apply the duration-150 utility on hover.
## 4. Interactivity
  #### * Using logical properties
  ###### * Use the scroll-ms-* and scroll-me-* utilities to set the scroll-margin-inline-start and scroll-margin-inline-end logical properties, which map to either the left or right side based on the text direction. 
## 5. Box Decoration Break
  #### * Setting the box decoration break
  ###### * Use the box-decoration-slice and box-decoration-clone utilities to control whether properties like background, border, border-image, box-shadow, clip-path, margin, and padding should be rendered as if the element were one continuous fragment, or distinct blocks.

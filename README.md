# Documentation: Bug Fix - ComingSoon Component Export

## Bug Description
The bug encountered was related to the export of the `ComingSoon` component. It was not exported as a default component, which was expected.

## Bug Fix Steps
To resolve the bug, the following steps were taken:

1. Modified the `ComingSoon` component by including the `default` keyword between the `export` and `function` keywords.

   ```javascript
   export default function ComingSoon() {
     // Component implementation
   }
   ```

By making this modification, the `ComingSoon` component is now exported as the default export, addressing the bug.
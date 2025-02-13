# Tailwind CSS Directives Not Processed in Components

This repository demonstrates a common yet easily overlooked error in Tailwind CSS: directives not being processed within components. This often arises from misconfigurations within the component's setup or the build process.

The `bug.vue` file showcases the problematic code, while `bugSolution.vue` presents the corrected version.  The issue usually lies in incorrect usage of `v-bind` (Vue), or a missing import or build step for other frameworks.
# React Router Dom v6 Catch-all Route Issue

This repository demonstrates a common issue encountered when using catch-all routes (`/*`) in React Router Dom v6.  The problem arises when a catch-all route is placed after other routes, causing it to always match, even if another route should be matched first.

The `bug.js` file shows the problematic code. The solution is provided in `bugSolution.js`.
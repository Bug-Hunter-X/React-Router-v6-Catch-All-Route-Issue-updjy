This repository demonstrates a common issue in React Router DOM v6 where the catch-all route `/*` overrides other routes. The bug showcases this problem and provides a solution.

The problem stems from the order of routes, where the catch-all should be placed last. The solution demonstrates how to correctly position the catch-all route to only match when no other route matches.  The solution also includes a more robust approach that prioritizes exact matches before resorting to the catch-all.

This issue is especially subtle when dealing with nested routes or routes with dynamic segments.
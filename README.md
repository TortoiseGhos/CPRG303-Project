# CPRG303-Project
# ADR 001: Choosing a Frontend Framework

## Status
- Accepted

## Context

- We need a framework that allows for fast development and scales well as the app grows.
- The app should work well across all modern browsers and devices.
- Team familiarity with JavaScript and web frameworks is a factor in the decision.

## Decision

- React is a popular JavaScript library for building user interfaces, which fits well with our project’s needs for dynamic and interactive components.
- React's component-based architecture is well-suited for large-scale applications and is backed by a large, active community.
- React's ecosystem (such as React Router for routing and Redux for state management) fits our use case.

## Consequences
- **Positive consequences**:
  - Fast, component-based development.
  - Rich ecosystem and community support.
  - Easy to integrate with other tools and services, such as Firebase or GraphQL.

- **Negative consequences**:
  - Requires a build system (Webpack, Babel) for production.
  - React has a learning curve for developers unfamiliar with it.
  - May lead to excessive re-renders and performance issues if not optimized properly.

- **Future considerations**:
  - The choice of React may require ongoing optimization and profiling as the app grows.
  - We may need to consider React Native if we decide to build a mobile app in the future.

## Alternatives Considered
- **Vue.js**: A simpler framework, but we rejected it because the team has more experience with React, and Vue's ecosystem is less mature compared to React’s.
- **Angular**: Considered due to its full-featured nature, but rejected because of its steep learning curve and the fact that the app doesn’t require a heavy framework.

## Related Decisions
- ADR 002: Choosing a State Management Solution

## References
- [React Official Docs](https://reactjs.org/docs/getting-started.html)
- [Vue.js Official Docs](https://vuejs.org/)
- [Angular Official Docs](https://angular.io/docs)

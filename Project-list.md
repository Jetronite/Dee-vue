# Vue Engineering Gauntlet — 20 Project Curriculum

The projects are intentionally sequenced.

This is not:

> “20 random apps.”

Each project introduces:

* new engineering pressure
* recurring concepts
* deeper architecture challenges
* more ambiguity
* larger systems thinking

Earlier concepts repeatedly return in harder contexts.

---

# Phase 1 — Foundations of Reactivity & UI Thinking

Goal:
Understand Vue’s mental model and stop thinking in “DOM manipulation mode.”

---

# 1. Reactive Counter Lab

### Focus

* refs
* computed
* events
* conditional rendering
* lists

### Features

* multiple counters
* derived statistics
* reset logic
* dynamic thresholds
* keyboard shortcuts

### Stretch

* persistent state
* undo/redo
* animated transitions

### Engineering Lessons

* reactive state flow
* derived state vs mutable state
* avoiding duplicated logic

---

# 2. Smart Todo System

### Focus

* forms
* list rendering
* local state architecture
* filtering
* composables introduction

### Features

* CRUD todos
* filters
* search
* categories
* due dates
* optimistic UI

### Stretch

* drag-and-drop sorting
* offline persistence
* keyboard accessibility

### Debug Missions

* stale filtered state
* accidental mutation bugs

---

# 3. Notes App with Persistence

### Focus

* localStorage
* watchers
* lifecycle hooks
* reusable components

### Features

* markdown preview
* autosave
* draft recovery
* note organization
* search

### Stretch

* debounce saving
* theme switching
* export/import notes

### Engineering Lessons

* persistence synchronization
* watcher misuse
* side effects

---

# 4. Multi-Step Form Wizard

### Focus

* form architecture
* validation
* dynamic components
* shared state

### Features

* step validation
* conditional steps
* async submission
* progress tracking

### Stretch

* schema-based forms
* reusable validation composable
* autosave recovery

### Debug Missions

* invalid state transitions
* async validation race conditions

---

# Phase 2 — Component Architecture & Async Systems

Goal:
Build scalable frontend structure and async thinking.

---

# 5. Weather Dashboard

### Focus

* API fetching
* async state
* loading/error states
* composables

### Features

* city search
* weather forecast
* loading skeletons
* retries
* caching

### Stretch

* geolocation
* unit conversion
* stale cache invalidation

### Engineering Lessons

* request lifecycle management
* error recovery
* async architecture

---

# 6. Movie Discovery Platform

### Focus

* routing
* route params
* pagination
* shared composables

### Features

* movie search
* details pages
* favorites
* infinite scroll
* filtering

### Stretch

* virtualized rendering
* optimistic favorites sync
* route prefetching

### Debug Missions

* duplicated fetches
* stale route state

---

# 7. Kanban Task Board

### Focus

* complex state
* drag-and-drop
* reusable abstractions

### Features

* columns/tasks
* drag sorting
* labels
* deadlines
* activity tracking

### Stretch

* websocket sync
* conflict resolution
* collaborative updates

### Engineering Lessons

* normalized state
* event architecture
* scaling reactive systems

---

# 8. E-Commerce Product Explorer

### Focus

* filtering systems
* derived state
* composables
* UI complexity

### Features

* product filters
* sorting
* cart system
* quantity management
* pagination

### Stretch

* optimistic cart sync
* persisted cart
* inventory state

### Debug Missions

* inconsistent derived totals
* duplicated state bugs

---

# Phase 3 — Real Application Engineering

Goal:
Move from “apps” to “systems.”

---

# 9. Authentication System

### Focus

* auth flows
* protected routes
* token handling
* session management

### Features

* login/signup
* auth guards
* session restore
* password reset
* role handling

### Stretch

* refresh token rotation
* multi-device logout

### Engineering Lessons

* auth architecture
* security basics
* route protection

---

# 10. Chat Application

### Focus

* realtime systems
* websocket state
* event handling

### Features

* live chat
* typing indicators
* unread tracking
* reconnect logic

### Stretch

* message persistence
* optimistic delivery
* group channels

### Debug Missions

* duplicate socket events
* stale subscriptions

---

# 11. Admin Analytics Dashboard

### Focus

* data visualization
* performance
* large state management

### Features

* charts
* tables
* filters
* pagination
* role-based views

### Stretch

* lazy loading
* virtualized tables
* realtime analytics

### Engineering Lessons

* rendering performance
* data shaping
* dashboard architecture

---

# 12. File Upload Manager

### Focus

* async orchestration
* upload lifecycle
* progress management

### Features

* drag upload
* previews
* upload queues
* retries
* cancellation

### Stretch

* chunked uploads
* resumable uploads
* image optimization

### Debug Missions

* orphaned async tasks
* upload race conditions

---

# Phase 4 — Nuxt & Fullstack Thinking

Goal:
Understand SSR, server/client boundaries, and production architecture.

---

# 13. Nuxt Blog Platform

### Focus

* SSR
* routing
* SEO
* server data fetching

### Features

* markdown posts
* dynamic routes
* tags/categories
* SEO metadata

### Stretch

* RSS feeds
* content caching
* static generation

### Engineering Lessons

* server/client boundaries
* hydration awareness

---

# 14. Fullstack Issue Tracker

### Focus

* backend integration
* API architecture
* relational thinking

### Features

* tickets
* comments
* assignment system
* filtering
* activity logs

### Stretch

* notifications
* optimistic mutations
* audit history

### Engineering Lessons

* frontend/backend contracts
* data consistency

---

# 15. Realtime Collaboration Editor

### Focus

* synchronization
* shared state
* conflict handling

### Features

* collaborative editing
* cursors
* sync indicators
* reconnect recovery

### Stretch

* operational transforms
* offline sync

### Debug Missions

* conflicting updates
* desynchronization

---

# 16. Subscription SaaS Dashboard

### Focus

* scalable architecture
* modular systems
* permissions

### Features

* billing UI
* teams
* invites
* usage metrics
* feature gating

### Stretch

* multi-tenant architecture
* granular RBAC

### Engineering Lessons

* enterprise frontend structure
* feature isolation

---

# Phase 5 — Senior-Level Frontend Engineering

Goal:
Train engineering judgment under production-like pressure.

---

# 17. Performance Rescue Mission

### Focus

* optimization
* profiling
* rendering bottlenecks

### Scenario

A deliberately slow application must be fixed.

### Problems

* excessive rerenders
* watcher abuse
* memory leaks
* large DOM trees

### Stretch

* benchmark improvements
* performance budgets

---

# 18. Broken Production App Debugging

### Focus

* debugging methodology
* production reasoning

### Scenario

A “working” app is full of hidden production bugs.

### Issues Include

* race conditions
* hydration mismatches
* stale caches
* broken reactivity
* async inconsistencies

### Goal

Diagnose and repair the system.

---

# 19. Architecture Refactor Challenge

### Focus

* refactoring
* maintainability
* technical debt reduction

### Scenario

You inherit a terrible codebase.

### Tasks

* modularize logic
* reduce coupling
* improve composables
* simplify state flow
* remove anti-patterns

### Stretch

* introduce testing coverage
* improve DX

---

# 20. Production Simulation Capstone

### Focus

Everything.

### Scenario

Build and ship a production-grade Vue/Nuxt application with:

* authentication
* realtime updates
* testing
* accessibility
* performance optimization
* responsive UI
* backend integration
* caching
* deployment pipeline

### Additional Pressure

* deadlines
* bug tickets
* failing tests
* feature requests
* refactor demands

### Goal

Simulate real engineering work.

---

# Hidden Curriculum

The projects are secretly training:

* systems thinking
* debugging discipline
* architecture reasoning
* async mental models
* state management intuition
* production awareness
* independent learning ability

Not just Vue syntax.

---

# Final Outcome

By the end, learners should be capable of:

* building real frontend systems independently
* navigating documentation confidently
* debugging complex issues
* architecting scalable Vue applications
* handling production complexity
* thinking like engineers instead of tutorial followers

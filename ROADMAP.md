# Web Development Mastery Journey — Roadmap

This is the master roadmap for the Web Development Mastery Journey. It is the reference document for planning weekly challenges, reviewing progress, deciding when to advance, and selecting phase projects.

The journey is designed to build practical proficiency from foundational web concepts through professional full-stack engineering. It complements Data Science studies rather than replacing them. Progress is mastery-led: topics may move faster when demonstrated understanding is strong, and concepts will be revisited when reviews reveal gaps.

## Learning and challenge structure

- One challenge per week, with a Sunday deadline.
- Every challenge states the concepts being practised and the concepts to prepare for the next challenge.
- Work independently before submitting; submissions are reviewed and corrections are tracked.
- A boss battle follows approximately every 4–6 challenges, combining current and previously learned concepts.
- UI/UX design and implementation are both part of the learning journey.
- Each phase ends with a practical milestone project.
- The roadmap is a guide, not a rigid calendar. Advancement depends on demonstrated understanding, not simply elapsed weeks.
- Accessibility, security, testing, SEO, performance, and documentation are recurring quality requirements throughout the journey.

## Proposed technology stack

### Core technologies
- HTML5, CSS3, JavaScript
- Figma and FigJam
- Git and GitHub
- React and TypeScript
- Node.js and Express.js
- PostgreSQL and SQL
- Prisma
- Next.js

### Supporting technologies (introduced when prerequisites are met)
- Vitest or Jest
- React Testing Library
- Supertest
- Playwright
- Redis
- Docker
- WebSockets
- OpenAPI / Swagger

### Stack decisions
- React is the first frontend framework; do not learn several frontend frameworks simultaneously.
- Learn Next.js after React fundamentals.
- PostgreSQL is the primary relational database.
- Learn SQL before using an ORM; introduce Prisma after database fundamentals.
- jQuery is optional legacy-project knowledge.
- EJS is optional templating knowledge.
- Additional tools are introduced only when they serve a clear learning or project need.

---

# Part I — Web Fundamentals

## Phase 0 — Web Fundamentals

- Internet vs. World Wide Web
- How websites work
- Client-server architecture
- Frontend vs. backend
- Static vs. dynamic websites
- Browsers, browser engines, and rendering
- HTTP and HTTPS
- Request-response lifecycle
- URLs and URL structure
- DNS
- Hosting
- Web standards
- Browser Developer Tools (DevTools)

# Part II — Frontend Development

## Phase 1 — HTML5

- HTML document structure
- Elements and attributes
- Text and headings
- Links and navigation
- Images
- Lists
- Tables
- Forms
- Input types and form validation
- Semantic HTML
- HTML5 structural elements
- Audio and video
- Embeds
- Metadata
- Accessibility
- HTML best practices

## Phase 2 — CSS3

- CSS syntax and ways to apply CSS
- Selectors
- Specificity
- Inheritance
- Cascade
- Colors and units
- Typography
- Backgrounds and borders
- Box model
- Display
- Positioning
- Float and clear
- Flexbox
- CSS Grid
- Pseudo-classes and pseudo-elements
- Transitions, transforms, and animations
- CSS variables (custom properties)
- Media queries
- Responsive and mobile-first design
- CSS architecture
- Reusable styling
- Cross-browser compatibility
- Layout debugging
- Maintainable CSS

## Phase 3 — UI/UX Design (runs alongside frontend development)

### UX — User Experience
- Design thinking
- Human-centred design
- User research: interviews and surveys
- User personas
- User needs and pain points
- User journeys
- Information architecture
- Site maps
- User flows
- Navigation design
- Wireframing
- Interaction design
- Usability principles
- Nielsen's usability heuristics
- Usability testing
- Accessibility and inclusive design
- Evaluation and iteration

### UI — User Interface
- Visual hierarchy
- Gestalt principles
- Colour theory and colour psychology
- Typography and font pairing
- Spacing
- Alignment
- Composition and balance
- Contrast
- Consistency
- Layouts
- Buttons, forms, cards, navigation, icons, and illustrations
- Responsive interface design
- Micro-interactions
- Design patterns
- Design systems, design tokens, and component libraries
- Accessibility in interface design

### Figma and FigJam
- Workspace and interface
- Frames and layers
- Vector tools
- Typography and styles
- Components and variants
- Auto Layout
- Constraints and resizing
- Responsive design in Figma
- Prototyping
- Interactive prototypes
- Design systems and libraries
- Developer handoff
- FigJam for collaborative planning and diagramming

## Phase 4 — JavaScript

### Core JavaScript
- JavaScript execution and runtime basics
- Variables and data types
- Type conversion and coercion
- Operators and expressions
- Conditionals and switch statements
- Loops
- Functions, parameters, and return values
- Scope, hoisting, and closures
- Arrays, objects, and their methods
- Destructuring
- Spread and rest syntax
- Template literals
- Higher-order functions
- Callback functions
- Arrow functions
- Errors and debugging

### Browser JavaScript
- DOM selection
- DOM manipulation
- Creating and removing elements
- DOM traversal
- Events
- Event propagation and delegation
- Form handling
- Browser APIs
- Local storage and session storage
- JSON
- Fetch API
- Promises
- Async/await
- JavaScript modules
- Asynchronous programming

### Advanced JavaScript
- Execution context
- Call stack
- Event loop
- Microtasks and macrotasks
- Prototypes and inheritance
- Classes
- `this`
- Functional programming concepts
- Memory management
- Performance
- Advanced error handling
- JavaScript security considerations

# Part III — Modern Frontend Development

## Phase 5 — React

- React setup and project structure
- JSX
- Components
- Props and state
- Events
- Conditional rendering
- Lists and keys
- Component composition
- Forms
- Controlled and uncontrolled components
- Hooks: useState, useEffect, useRef, useContext, and custom hooks
- Lifecycle concepts
- React Router and routing
- API integration
- Loading and error states
- State management: Context and external options
- Reusable components
- Form validation
- Protected routes and authentication integration
- Optimization
- Lazy loading and code splitting
- React testing

## Phase 6 — TypeScript

- Types and type annotations
- Primitive types
- Arrays and tuples
- Objects
- Interfaces
- Type aliases
- Union and intersection types
- Literal types and enums
- Functions and function types
- Optional properties and props
- Generics
- Type narrowing and type guards
- Utility types
- Classes and access modifiers
- Modules
- Error handling
- TypeScript with React
- Typing components, props, hooks, and API responses

## Phase 7 — Frontend Quality

- Accessibility and WCAG
- Semantic architecture
- SEO and technical SEO
- Metadata and structured data
- Performance and Core Web Vitals
- Image and font optimization
- Lazy loading
- Caching
- Responsive testing
- Cross-browser testing
- Frontend security and Content Security Policy (CSP)
- Lighthouse audits

# Part IV — Backend Development

## Phase 8 — Node.js

- Introduction to backend development
- Node.js runtime architecture
- Installation and version management
- npm
- Modules: CommonJS and ES modules
- File system and path modules
- Events and event emitters
- Buffers and streams
- Asynchronous programming
- Environment variables
- Process management
- Debugging
- Dependency management

## Phase 9 — Express.js

- Express setup and servers
- Routing
- Request and response
- Route parameters and query parameters
- Request bodies
- Middleware
- Custom middleware and error middleware
- Static file serving
- REST APIs
- CRUD operations
- HTTP methods and status codes
- API versioning and documentation
- Validation
- Backend architecture and MVC
- Logging
- File uploads
- Email integration

## Phase 10 — APIs and Web Communication

- What APIs are
- API architecture
- REST
- JSON
- HTTP methods, headers, and status codes
- Authentication concepts: API keys, OAuth 2.0, and JWT
- Pagination
- Filtering and sorting
- Rate limiting
- API testing
- OpenAPI and Swagger
- WebSockets
- Real-time communication
- Webhooks
- Third-party API integration

# Part V — Databases

## Phase 11 — Database Engineering

### Database foundations and design
- Database concepts
- Relational vs. non-relational databases
- Database architecture and design
- Entity Relationship Diagrams (ERDs)
- Entities, attributes, and relationships
- Keys and constraints
- Data integrity
- Normalization

### PostgreSQL and SQL
- PostgreSQL setup
- Data Definition Language (DDL)
- Data types
- CRUD operations
- Filtering and ordering
- Grouping and aggregate functions
- Joins
- Subqueries
- Common Table Expressions (CTEs)
- Views
- Indexes
- Transactions
- Stored procedures and functions
- Query optimization
- Database security
- Backup and recovery

### ORM and Prisma
- ORM concepts
- Prisma schemas
- Migrations
- CRUD with Prisma
- Relationships
- Transactions
- Express integration
- Connection management
- Testing database-backed applications

# Part VI — Advanced Full-Stack Development

## Phase 12 — Web Security

- Authentication vs. authorization
- Registration and login
- Password hashing
- Sessions and cookies
- JWT and refresh tokens
- Role-Based Access Control (RBAC) and permissions
- Password recovery
- Multi-factor authentication (MFA) concepts
- SQL injection
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- CORS
- Secure headers
- Validation and sanitization
- Secrets management
- OWASP Top 10
- Secure application design

## Phase 13 — Advanced Engineering

- Full-stack architecture
- Monoliths and microservices
- Separation of concerns
- Design patterns
- Dependency management
- Error handling
- Logging and monitoring
- Caching
- Redis
- Background jobs and queues
- WebSockets
- File and cloud storage
- Email services
- Payment gateways
- Performance
- Scalability
- Maintainability

## Phase 14 — Next.js

- Next.js project structure
- File-based routing
- Layouts and pages
- Server and Client Components
- Server-side rendering (SSR)
- Static site generation (SSG)
- Dynamic rendering
- Data fetching
- Route handlers
- Server actions
- Metadata and SEO
- Authentication
- Caching and revalidation
- Full-stack applications
- Optimization
- Deployment

# Part VII — Professional Engineering Practices

## Phase 15 — Git and GitHub

- Version control
- Repositories
- Commits
- Branches
- Merging
- Merge conflicts
- Pull requests
- Code reviews
- Issues and projects
- Workflows
- .gitignore
- README documentation
- Open source
- Releases

## Phase 16 — Testing and Quality Assurance

- Manual testing
- Unit testing
- Integration testing
- End-to-end (E2E) testing
- Test-Driven Development (TDD)
- Test coverage
- Mocking
- API testing
- Frontend and backend testing
- Browser automation
- Regression testing
- Performance testing
- Security testing

### Tools introduced as appropriate
- Vitest or Jest
- React Testing Library
- Supertest
- Playwright

## Phase 17 — Deployment and DevOps

- Development, testing, and production environments
- Domains and DNS
- Hosting
- Frontend deployment
- Backend deployment
- Database deployment
- HTTPS and SSL
- Reverse proxies
- Docker and containers
- CI/CD
- Cloud fundamentals
- Monitoring
- Error tracking and logs
- Backups
- Disaster recovery
- Maintenance and dependency updates

# Part VIII — Additional Professional Subjects

## Phase 18 — Search Engine Optimization (SEO)

- Crawling and indexing
- On-page SEO
- Technical SEO
- Semantic HTML
- URL structure
- Metadata
- Structured data
- Sitemaps
- robots.txt
- Performance and SEO
- Analytics

## Phase 19 — Accessibility Engineering

- Accessibility principles
- WCAG
- Keyboard accessibility
- Screen readers
- Accessible forms
- Colour contrast
- ARIA
- Semantic accessibility
- Focus management
- Accessibility testing
- Inclusive design

## Phase 20 — Performance Engineering

- Browser rendering
- Critical rendering path
- JavaScript, CSS, and network optimization
- Compression
- Image formats
- Lazy loading
- Caching
- Core Web Vitals
- Profiling
- Lighthouse
- Performance budgets

## Phase 21 — Documentation and Professional Practice

- Technical documentation
- API documentation
- Architecture documentation
- Database documentation
- Requirements and specifications
- User manuals
- Client communication
- Requirements gathering
- Estimation
- Maintenance
- Handover

# Part IX — Projects and Specialization

## Phase 22 — Portfolio Projects

Projects will be selected and scoped as the relevant skills are developed. The portfolio path includes:

- Personal portfolio website
- Business website
- Interactive task manager
- Data dashboard
- E-commerce application
- Management system
- Real-time application
- Production business website for the user's mother

The mother's website is a real client project and should be approached professionally only after the necessary foundations are in place. The process should include requirements gathering, UX research, sitemap, wireframes, design approval, implementation, testing, deployment, handover, and maintenance.

## Phase 23 — Advanced Specialization

- Progressive Web Apps (PWAs)
- Serverless architecture
- GraphQL
- Microservices
- Advanced cloud architecture
- WebAssembly
- Browser APIs
- Advanced security
- System design
- Large-scale application architecture

---

## Roadmap maintenance

This document is the master curriculum reference. Weekly challenges, phase plans, project briefs, and progress records should align with it. The roadmap may be refined as learning reveals prerequisites or useful additions, but changes should be deliberate and should not silently remove planned subject areas.

## Hi, I'm Hayk

Full-stack engineer in Yerevan, Armenia. I write TypeScript on both ends (React, Node.js, GraphQL) and build my own projects on the side. Most of those repos are private, so this page describes them instead.

### Banman

A multi-tenant issue tracker, in progress. TypeScript monorepo with React 19, GraphQL Yoga, PostgreSQL (via Drizzle) and Vitest.

- **Schema-driven backend.** One JSON definition per table generates the database table, its GraphQL API and its access rules. The server refuses to boot if a table has no permission policy.
- **Permission language.** Policies are written in a small expression language. The same policy is checked in memory on writes and compiled into a SQL `WHERE` on reads, so rows you can't see are filtered out instead of raising errors.
- **Tenant isolation.** Company and space scopes are enforced across queries, mutations and live subscriptions, and covered by about 300 integration tests that run a real server against a real Postgres database.
- **How it's built.** The code is written by Claude Code agents. I set the architecture and specs, review every change, and require verification before anything merges.

### Droplet

The website for an image-watermarking API, built with React 19, TypeScript and Vite. It has a landing page, API docs and a live demo that watermarks an uploaded image and detects watermarks.

Every page, section and tab comes from one JSON-shaped config mapped to components. The UI uses a small component library built on design tokens, and two custom ESLint rules keep pages from going around it.

Related paper I co-authored: *Robust Blind Zero-Bit Image Watermark Detection Using Structured Hard-Negative Learning* (D. Hovhannisyan, H. Gevorgyan, D. Faruk), submitted to Acadlore Transactions on AI and Machine Learning, 2026.

### Football tactical analysis

My Master's project: YOLO player and ball detection, an OpenCV homography onto a 2D pitch, and Voronoi plots of pitch control.

### Background

I came to programming through math. I went to a specialized math and physics school, competed in national olympiads in math, physics and chemistry, and hold a Bachelor's degree in Applied Mathematics and a Master's degree in Computer Science from the National Polytechnic University of Armenia. Algorithms were my strongest area at Picsart Academy's Java program.

At work I build features for a mortgage CRM with React, Node.js, GraphQL and MongoDB.

### Tools

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,react,nodejs,graphql,mongodb,postgres,vite,java" alt="TypeScript, JavaScript, React, Node.js, GraphQL, MongoDB, PostgreSQL, Vite, Java" />
</p>

### Contact

[LinkedIn](https://www.linkedin.com/in/haykgevorgian) · [Email](mailto:g.hayk.111@gmail.com)

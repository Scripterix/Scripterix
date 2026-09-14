# Piotr Adamkowski · Scripterix

**Web developer building practical applications with JavaScript, TypeScript and React.**

I work on web applications, client websites and tools that turn everyday problems into software. My focus is readable code, modular architecture and understanding the trade-offs behind an implementation.

[LinkedIn](https://www.linkedin.com/in/opengateweb/) · [Portfolio in English](https://scripterix.github.io/en/portfolio/) · [Portfolio po polsku](https://scripterix.github.io/portfolio/)

## Start here

**Reviewing my work? Start with [Book Tracker](https://github.com/Scripterix/scalable-book-tracker).** It brings together a React interface, a typed API, SQL persistence, validation and automated backend tests.

| Selected project | What it demonstrates | Explore |
| --- | --- | --- |
| **Book Tracker** | React + TypeScript, Express, SQLite, Zod validation, keyset pagination and an isolated performance lab. A local single-user MVP with documented limits. | [Code & setup](https://github.com/Scripterix/scalable-book-tracker) |
| **Developer portfolio & learning log** | A bilingual Jekyll site with paired PL/EN content, reusable layouts, content-generation scripts and GitHub Actions publishing. | [Source](https://github.com/Scripterix/scripterix.github.io) · [Website](https://scripterix.github.io/) |
| **Bramy Józefów** | A client website: service pages, a project gallery and a legacy HTML/CSS/JavaScript + PHP codebase. Shows practical website maintenance and integration work. | [Source & context](https://github.com/Scripterix/bramy-jozefow) · [Client website](https://bramy-jozefow.com/) |

## A short code tour

In **Book Tracker**, these are useful starting points for a technical conversation:

- [Repository layer](https://github.com/Scripterix/scalable-book-tracker/blob/main/backend/src/books/books.repository.ts): parameterized SQL, typed records and cursor pagination.
- [Validation](https://github.com/Scripterix/scalable-book-tracker/blob/main/backend/src/books/books.schema.ts): input rules at the API boundary.
- [API tests](https://github.com/Scripterix/scalable-book-tracker/blob/main/backend/tests/books.test.ts): behavior checked against isolated databases.
- [Query-plan checks](https://github.com/Scripterix/scalable-book-tracker/blob/main/backend/tests/scalability.test.ts): index usage and sorting assumptions.
- [React components](https://github.com/Scripterix/scalable-book-tracker/tree/main/frontend/src/components): forms, search, book listing and the performance view.

The performance lab generates **100, 1,000 and 10,000 records**. It is a reproducible experiment, not a claim of production performance at millions of records.

## How I work

- Separate UI, HTTP handling, validation and data access.
- Keep project scope and known limitations visible.
- Use AI for planning, implementation and review, with project-specific disclosure: [Book Tracker AI usage](https://github.com/Scripterix/scalable-book-tracker/blob/main/AI_USAGE.md).
- Document learning and implementation decisions in my [portfolio and logbook](https://scripterix.github.io/).

**Current focus:** React, TypeScript, Node.js/Express and SQL. My repositories also include earlier Angular, JavaScript and PHP work; learning exercises are part of the archive, while the projects above are the recommended starting points.

## Let's talk

Interested in a web development collaboration or a role related to these projects? Send the project scope and technical requirements through [LinkedIn](https://www.linkedin.com/in/opengateweb/).

**Po polsku:** tworzę aplikacje webowe i strony dla klientów. Stawiam na czytelny kod, modułowość i praktyczne rozwiązywanie problemów. Najlepszy punkt startowy do oceny mojego kodu to Book Tracker.

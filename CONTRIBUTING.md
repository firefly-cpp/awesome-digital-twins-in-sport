# Contributing to Awesome Digital Twins in Sport

Thank you for helping improve this collection. Contributions should make the list more useful to researchers and practitioners working on digital twins in sport.

## What Belongs Here

We welcome:

- books, surveys, journal articles, conference papers, and book chapters;
- theses and dissertations;
- perspectives that discuss digital twins in a substantive sports context;
- datasets used to build or evaluate athlete, team, or facility twins; and
- documented software with a clear digital-twin use case in sport.

Core digital-twin work should explicitly define, construct, validate, or deploy a digital twin for an athlete, training process, team, sports robot, or sports facility. Interdisciplinary work may be added to **Related and Enabling Research** when it contributes a method needed by such systems, such as sensing, biomechanical modelling, personalised recommendations, or multi-agent decision making.

The collection contains historically curated interdisciplinary sources. These remain part of the collection; the criteria above guide new submissions.

## Before You Submit

- Search the README for the title, DOI, and URL to avoid duplicates.
- Prefer a canonical HTTPS DOI link or an official publisher, institutional repository, dataset, or project page.
- Avoid link shorteners, search-result pages, and unauthorised copies.
- Confirm the title, authors, venue, year, volume, issue, and pages or article number against the primary source.
- For software, link to the source repository and confirm that it has a public licence and usable documentation.
- Add the item to the most specific section and keep entries alphabetised by the first author or project name.

## Entry Format

Use an MLA 9-style citation followed by one concise sentence explaining why the resource belongs in the collection. Link the title to its canonical source and do not repeat the DOI at the end.

```markdown
- Hliš, Tilen, Iztok Fister, and Iztok Fister Jr. “[Digital Twins in Sport: Concepts, Taxonomies, Challenges and Practical Potentials](https://doi.org/10.1016/j.eswa.2024.125104).” *Expert Systems with Applications*, vol. 258, 2024, article 125104. — Establishes a sport-specific taxonomy and research agenda for digital twins.
```

For software, use the project name followed by a practical description:

```markdown
- [Project name](https://example.com) - Describes what the project does, its licence, and how it implements or supports a sports digital twin.
```

## Pull Request Process

1. Fork the repository and create a focused branch.
2. Update the correct section in `README.md`.
3. Check spelling, citation metadata, alphabetical ordering, and Markdown formatting.
4. Run `npx --yes awesome-lint@2.3.0` when Node.js 20 or newer is available.
5. Open a pull request that briefly explains the resource’s relevance.

By submitting a contribution, you agree that it will be distributed under the repository’s existing licence.

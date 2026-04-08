# Guideline for Writing a Bachelor Thesis

Author: Prof. Dr. Henning Lorrmann

## Purpose

This document summarizes writing and formatting rules for bachelor theses. It complements the bachelor thesis guide on structure, scope, and grading criteria.

Use this document to make consistent decisions on tool choice, notation, figures, equations, citations, and final quality control.

Use it while drafting, revising, and checking the final PDF before submission.

## Academic integrity

- Your thesis must clearly distinguish your own work from material taken from other sources.
- Text, images, data, equations, code fragments, and ideas from third parties must be cited properly.
- Fabrication, plagiarism, unattributed paraphrasing, or undocumented reuse of existing material is unacceptable.
- If generative AI tools are used where permitted, their use must be transparent and documented according to the applicable citation rules and the examination regulations.

## Recommended writing tools

The following tools for the preparation of the document are recommended:

### Microsoft Word

- Please use the official reporting template to be found [here](https://intranet.thws.de/index.php?eID=dumpFile&t=f&f=41623&token=bf10754b7a816ecd48dddca2652e8bfd44227d77).
- Use the integrated editor for equations.
- Use the built-in functions for table and figure captions.
- Use the templates for chapter titles and running text.

### Markdown / MYST Markdown

- Markdown is a lightweight markup language and a good entry point for technical writing.
- For a bachelor thesis, use MYST Markdown rather than plain Markdown whenever equations, citations, cross-references, numbered figures, or structured tables are required.
- A practical starting point is VS Code with Markdown support. Dillinger and StackEdit are useful for first steps, but a thesis workflow should support reproducible export and structured references.
- Good starting points for basic Markdown are [here](https://www.markdowntutorial.com/lesson/1/), [here](https://www.markdownguide.org/) or [there](https://medium.com/@itsjzt/beginner-guide-to-markdown-229adce30074).
- MYST Markdown extends Markdown with directives, roles, and other structured authoring features needed for technical documents.
- For MYST-specific syntax and project structure, use the [official documentation](https://myst-parser.readthedocs.io/en/latest/).

### LaTeX

- The typographer's gold standard. Highly recommended for top-quality scientific and engineering papers.
- Particularly suitable for theses with many equations, symbols, cross-references, and technical figures.
- Good starting points can be found [here](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes) or [there](https://www.colorado.edu/aps/sites/default/files/attached-files/latex_primer.pdf).

### PDF export

- The submitted thesis must be a PDF exported from the chosen source format.
- The PDF must preserve headings, numbering, references, equations, captions, bibliography formatting, and page layout correctly.
- Before submission, verify that the exported PDF renders correctly on another device.

### Practical expectation

- Keep the source files, bibliography data, and figure assets organized and versionable.
- Use stable file naming and consistent directory structure for text, figures, tables, and supplementary material.
- Keep the build process reproducible so that the same source generates the same PDF reliably.
- Do not submit editable source files unless explicitly requested in addition to the PDF.

## Reader guidance and chapter flow

- Write for a reader who knows the technical basics of the degree program, but does not know your project yet.
- Start each major chapter with its purpose and end it with a short takeaway.
- Introduce new concepts before using them in equations, figures, or result discussions.
- Prefer a concrete example or application context before abstract explanation where possible.
- Each paragraph should serve one clear purpose.

## Figures and tables
- Every figure and table must be referenced in the text and discussed in terms of its relevance to the thesis argument. Do not insert figures or tables without explaining their relevance.
- Every figure must have a caption below the figure.
- Every table must have a caption above the table.
- Captions should be short, specific, and informative.
- Every figure and table must be referenced and discussed in the running text.
- Do not insert figures or tables without explaining their relevance.
- Ensure that all text inside figures remains readable in the final PDF.
- For line-based graphics such as diagrams, plots, circuit schematics, and block diagrams, use vector graphics whenever possible.
- Use high-quality images only. Blurry screenshots and unreadable photographs are not acceptable.
- Text in figures should not be more than 2 pt smaller than the running text and should never be smaller than 8 pt.
- If a figure is taken from another source, it must be cited properly and permission must be obtained if required by copyright.

## Equations, notation, and units

- Explain the meaning of an equation before or immediately after introducing it.
- Define every symbol at first use.
- Keep notation consistent across the whole thesis. Do not rename the same quantity between chapters.
- Use upright letters for units such as m, V, A, and °C.
- Use italic letters for physical variables and quantity symbols, such as *U, I, P*
- Leave a space between numeric value and unit, for example 1.2 V, 70 %, or 100 °C.
- In tables, state units in the header row or header column, for example "Voltage / V".
- Do not place units in square brackets or round brackets directly after the quantity name in running text.
- Number equations where they are referenced later.
- In LaTeX-based workflows, use a consistent notation for numbers and units, for example `\qty{...}{...}`, `\unit{...}`, and `\num{...}` from `siunitx`.

## Citations and references

- Use a consistent citation style throughout the thesis.
- IEEE style is recommended for engineering theses.
- Cite sources for statements of fact, adopted methods, reproduced data, external images, standards, and prior work.
- Every in-text citation must correspond to an entry in the bibliography.
- Every bibliography entry should be complete enough that the source can be identified and retrieved.

IEEE quick example:

[1] A. Author and B. Author, "Title of the Article," *Journal Title*, vol. 12, no. 3, pp. 45-52, 2024.

In-text citation example: "The measured values are in line with the expected behavior [1]."

### AI-assisted work

- If AI tools are allowed in your examination context, document them transparently.
- The reference should include at least the tool name, version if known, the relevant prompt, and the relevant output or use context.
- Do not use AI-generated text or analysis as a substitute for your own technical understanding and verification.

## Language and presentation

- Check spelling, grammar, punctuation, and typography before submission.
- Be sparse with color, highlighting, bold text, and italics.
- Avoid inconsistent formatting across chapters.
- Use the same style for headings, captions, code listings, tables, and references throughout the thesis.
- Make sure abbreviations are defined when first used.
- Prefer short, precise sentences over long decorative formulations.
- Avoid undefined technical jargon at first use.
- Use quotation marks consistently. In LaTeX workflows, `\enquote{...}` is preferred.

## Final quality check before submission

Before submission, verify at least the following:

- The thesis is complete and follows the agreed structure.
- Research questions, methods, results, and conclusions are aligned.
- Each chapter has a clear role in the overall argument of the thesis.
- All figures and tables are numbered, captioned, and referenced in the text.
- Equations, variables, and units are typeset consistently.
- Every central symbol and abbreviation is defined at first use.
- Citations and bibliography are complete and consistent.
- The language has been checked for spelling and grammar.
- If Markdown is used, the source is maintained in MYST Markdown rather than plain Markdown.
- The PDF formatting is stable and readable on another device.
- The page count of the main text, excluding front and back matter, is between 35 and 40 pages as recommended in the thesis guide.

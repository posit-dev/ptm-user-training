# Posit Team User Training

## Structure

1.  The `index.qmd` file includes links to individual catalog pages, such as *Posit Team Power Ups*, *Best Practices*, *Learning Paths*, and others. The catalog listing on the `index.qmd` page is generated using the `catalogs.yml` file and the `catalog-listing.ejs` template.
2.  Each catalog page consists of either a collection of lessons (such as *Posit Team Power Ups*) or a curated list of learning paths. A **learning path** is an organized set of lessons centered around a specific theme or topic (for example, *Getting Started with Posit Team*). All lessons can be found in subdirectories of the `lessons/` folder. Each lesson is presented as a single Quarto document, featuring an embedded video at the top, accompanied by optional text below that summarizes the lesson.
3.  A catalog page may also link out to an external page or sign-up form (e.g., *Posit Team User Training Workshop*).
4.  All images used in the project should be added to the `images/` directory to avoid duplication in individual lesson.
5.  Custom CSS styling is defined in the `styles.css` file.

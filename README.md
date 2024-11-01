# Posit Academy

## Structure

1.  At the top of your LMS is a `index.qmd`. This file contains links to individual catalog pages. Example catalog pages include: Open Source Education, Posit Team User Training, Posit Team Admin Training. You can either manually link to your various catalog pages, or you can add a custom listing via the `catalogs.yml` file.
2.  Catalogs are called `catalog-{description}.qmd`. For example, the open source education training catalog could be called `catalog-open-source-ed.qmd`. You can have as many catalog pages as you'd like. The `catalog-{description}.qmd` files will reside within a `catalogs/` folder.
3.  A `catalog-{description}.qmd` contains various courses organized into learning paths. For example, a `catalog-open-source-ed.qmd` may contain "Intro to R" and "Intro to Python" learning paths. Each learning path is defined in a `path-{description}.yml` file. All of the `path-{description}.yml` files reside within a `paths/` directory. The paths are displayed on the `catalog-{description}.qmd` page via the `listings:` YAML key.
4.  The `path-{description}.yml` contains hrefs to various `course-{description}.qmd` files. Each course will have a dedicated sub-directory within the `courses/` directory. In addition to the `course-{description}.qmd` file, you'll also find a `curriculum-{course}.yml` file which outlines the structure of each lesson in the course.
5.  The `lessons/` directory will contain a sub-directory for each lesson. Inside each lesson sub-directory will be a `lesson-{description}.qmd` file (and any dependent files including images, data, etc). A lesson is the basic unit of education in this LMS.

## Creating a new course

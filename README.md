# Basics Template

Use this template for building out new modules in the SDS Basics series.

To use this template:

1. Create a new GitHub repository based on this template.
2. Update the following files appropriately to reflect the new repository name, URL, and address:

    - `_config.yml`
    - `_includes/components/sidebar.html`

3. The lefthand navigation is determined by Markdown files present within `docs/`. Each file has Front Matter
that declares a `title` and `nav_order` among other metadata. This is extensible and
has many other options, such as publish date, categories, and tags, etc.. See [reference](https://jekyllrb.com/docs/front-matter/) material for
more options.

    ```
    ---
    layout: default
    title: 2 - Git Basics
    nav_order: 4
    last_modified_date: "2025-04-28 02:13AM"
    ---
    ```

4. In the GitHub **Settings** for your new repository, go to the **Pages** section and
for the source of "Build and Deployment" select "GitHub Actions". Pushes to your repository
will now trigger a new build.
5. The URL of the built site is `https://uvads.github.io/` plus the repository name. [Here](https://uvads.github.io/basics-template/) is the URL for this particular site.

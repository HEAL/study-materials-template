[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

# Study Materials Template Repository

This template repository is intended to facilitate sharing materials from a
research study. The existing folder structure is meant to serve as a guide
only, to help you get started. Feel free to modify it for your own study, as
necessary.

Although GitHub is primarily intended for for code sharing, it has several
features that make it well-suited for sharing not only code but other study
materials. These include:

* GitHub can render not only code and Markdown files, but also CSV files,
  PDFs, Jupyter notebooks and others. Its advanced search functionality and
  navigation tools make it easy for users to browse materials online.

* GitHub provides permanent links to materials you share that you can include
  in publications, as well as the ability to update materials while maintaining
  access to previous versions (i.e., versioning).

* Some data repositories (e.g., [Figshare](http://figshare.com/)) permit you
  to import a GitHub repository when you deposit your data, automatically
  providing your data users with immediate access to your study materials.

* If your materials include computer code, sharing them through GitHub
  maxmizes their usability.

* If you want to collaborate with those who use your materials (e.g., receive
  feedback, respond to questions, collaborate on further analyses, etc.),
  GitHub is ideally suited for this. If you do not wish to do this, these
  features are easily disabled.

To get started by creating your own repository from this template, simply follow
[these instructions](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).


## Sharing Data

While you can in principle use GitHub to share the actual data from your
study, data repositories are often a better choice. Data repositories are
optimized for archiving and distributing research data, and have special
capabilities for ensuring that data files are organized and formatted
properly, that they are accompanied by adequate metadata, and in some cases,
for assisting with deidentification and curation. Data repositories are also
capable of handling restricted data (i.e., data for which users must submit a
formal request that is approved prior to granting access) and for monitoring
adherence to special useage restrictions. Finally, data repositories actively
promote their datasets and provide targeted search and discovery features, as
well as sharing study metadata with aggregating services to increase their
discoverability. For these reasons, a data repository is often the best choice
for sharing the primary data from your study.

That said, there *are* some instances where it may make sense to share actual
data via GitHub. Here are a couple examples:

1. A limited dataset containing only those variables used for the analysis in
   a specific paper, permitting readers to replicate your analyses. This may
   be especially helpful if your full dataset is restricted access, as
   described above.

2. Summary statistics or derived variables from your study that are likely to
   be of broad interest and value on their own.

> :warning: If you do decide to share data via GitHub, you are entirely
responsible for making sure that you have authority to share those data,
including adequate consent from study participants, and that you have
deidentified the data adequately.


## Licensing

If you want to make your study materials useable by others, you should include
an [appropriate licence](https://en.wikipedia.org/wiki/Comparison_of_free_and_open-source_software_licenses).
GitHub makes this easy to to when you are creating a new repository (just
select a license from the drop-down menu).


## Accessibility

When creating electronic materials, you should try to make them accessible to
as many people as possible including those with visual, cognitive, mobility
and hearing limitations. While this is a requirement for all Federal
electronic content (as stipulated in Section 508, part of an amendment to the
Rehabilitation Act of 1973), attention to accessible design often leads to
clearer overall presentation and more useable content, and therefore benefits
all users of that content. GitHub targets compliance with the
[Web Content Accessibility Guidelines (WCAG) 2.1](https://www.w3.org/TR/WCAG21/),
and provides [information on their 508 accessibility](https://government.github.com/accessibility/).

When creating study-related materials to share in your repository, pay
particular attention to the following:

- Document format (e.g., use accessible PDFs which have been tagged
  appropriately to facilitate navigation)
- Tables (use simple structure with row and column headers to ensure that they
  can be navigated via a keyboard or other assistive device)
- Use of color (choose high contrast colors and don't rely on color alone)
- Images (provide text alternatives)
- Multimedia (provide closed captioning or transcript)

More information on creating accessible materials is available at
[Section508.gov](https://www.section508.gov/create/).


## You Don't Need To Use Git!

For those who don't know, Git is a file versioning tool used heavily by
software developers and, more recently, by those who manage and analyze data.
GitHub is built on Git, and many GitHub users interact with GitHub via Git or
one of the many desktop or mobile applications that utilize Git. As noted
above, this is one of the advantages of sharing your materials—especially your
code—via GitHub.

That said, GitHub has a well-developed web-based interface that means that
*you do not have to use Git to store your study materials on GitHub*. This
web-based interface provides access to all of the features you'll need,
including:

1. Adding and updating files

2. Reorganizing your project (e.g., moving or renaming files, placing files in
   folders)

3. Editing files in text format (e.g., Markdown files, code files, CSV files, etc.)

4. Browsing your project history, including the revision history of specific
   files, and examining changes made to files in text format


## Tips and Tricks

Here are a few tips and tricks for using GitHub to share study materials:

1. Be sure to include a
   [``README.md`` file](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)
   at the root of your repository, as demonstrated in this template. GitHub
   will render this file automatically when a user navigates to the
   repository, thereby serving as a quick-and-dirty website for your study.
   Note also that README.md files may be placed within any folder in your
   repository to provide additional documentation.

2. While you do not have to follow the repository structure given in the
   template, you are encouraged to adopt a simple and intuitive structure that
   communicates as much information as possible in order to make your
   repository easy to use. For example, if you are sharing materials exported
   from an application (e.g., REDCap), we suggest placing these in a folder
   named "REDCap" so that the user immediately knows what they are. Similarly,
   if you are providing scripts written in a specific language (e.g., Stata,
   R, Python) we suggest placing these in a folder by that name.

3. Although you may upload and store files of any type in GitHub, files
   containing written content are best provided in [Markdown](https://www.markdownguide.org)
   or [reStructuredText](https://docutils.sourceforge.io/rst.html), since
   those are rendered automatically by GitHub and are editable using the
   [GitHub editor](https://docs.github.com/en/get-started/writing-on-github).

4. Related to (3), GitHub is also able to render
   [additional file types](https://docs.github.com/en/repositories/working-with-files/using-files/working-with-non-code-files)
   including PDF files, images (PNG, JPG, GIF, PSD, and SVG), CSV and TSV data, 
   GeoJSON and TopoJSON map files, and Jupyter notebooks. Use of such files,
   when possible, will make it easier for users to consume your content.

5. When organizing and documenting your project, use hyperlinks liberally.
   It is often better to link out to a resource that is already available on
   the web than to include a copy of that resource in your repository.

6. [GitHub issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues)
   can be used to respond to questions about your project in a way that
   benefits all subsequent users, as well as to facilitate back-and-forth
   and/or collaboration. At the same time, material not included in your
   project's files (e.g., issues,
   [wikis](https://docs.github.com/en/communities/documenting-your-project-with-wikis/about-wikis),
   etc.) is not included when cloning or downloading your project, and thus
   cannot be packaged together with your data when you submit your data to a
   data repository. Thus, while GitHub issues and wikis can be useful, keep
   this in mind before spending a lot of time creating content using those
   features.

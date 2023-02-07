<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Okonda, Joseph L"
mintoclevel = 2

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]
ignore = ["examples/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
website_title = "At the interface of Hubris & Humility"
website_descr = "A collection of notes on Abstract Algebra, Analysis, Relational Biology, and Optimization"
website_url   = "https://github.com/jlikhuva/blog"
+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\V}{V \left( \mathbb F \right)}
\newcommand{\VR}{V \left( \mathbb R \right)}
\newcommand{\VC}{V \left( \mathbb C \right)}
\newcommand{\OPVC}{T: \VC \longrightarrow \VC }

+++
title = "2. The Data Screen"
weight = 2
+++

Click the **Data** button in the main menu. The **Sources and Fields** block
lists every data source the app can see, along with a general description,
row counts, and when the data was last updated.

1. Pick the data sources you want to work with. The order matters: the
   first one you check becomes the base source, and the rest get joined
   onto it.
2. Expand a source with the `+` button and check only the fields you'll
   actually need.
3. If you've picked more than one source, a **Joins between Sources**
   block appears below. For each row, choose the join type (default
   **LEFT**) and the fields to match sources on -- these have to be set
   explicitly.
4. Add **Conditions** if you need them -- they narrow down the data and
   shrink the working dataset, which helps performance.

Next: [The Fields Screen](../03-fields-screen/).

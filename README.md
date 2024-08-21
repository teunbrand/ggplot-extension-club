
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ggplot-extension-club

A repository as a [discussion
place](https://github.com/teunbrand/ggplot-extension-club/discussions)
for extending the ggplot2 R package.

As a bit of background: some people have been meeting virtually every
few months and discussing ggplot2 extension.

Meetings:

<div id="nvvghpaynx" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#nvvghpaynx table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
&#10;#nvvghpaynx thead, #nvvghpaynx tbody, #nvvghpaynx tfoot, #nvvghpaynx tr, #nvvghpaynx td, #nvvghpaynx th {
  border-style: none;
}
&#10;#nvvghpaynx p {
  margin: 0;
  padding: 0;
}
&#10;#nvvghpaynx .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}
&#10;#nvvghpaynx .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}
&#10;#nvvghpaynx .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}
&#10;#nvvghpaynx .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}
&#10;#nvvghpaynx .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#nvvghpaynx .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#nvvghpaynx .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#nvvghpaynx .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}
&#10;#nvvghpaynx .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}
&#10;#nvvghpaynx .gt_column_spanner_outer:first-child {
  padding-left: 0;
}
&#10;#nvvghpaynx .gt_column_spanner_outer:last-child {
  padding-right: 0;
}
&#10;#nvvghpaynx .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}
&#10;#nvvghpaynx .gt_spanner_row {
  border-bottom-style: hidden;
}
&#10;#nvvghpaynx .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}
&#10;#nvvghpaynx .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}
&#10;#nvvghpaynx .gt_from_md > :first-child {
  margin-top: 0;
}
&#10;#nvvghpaynx .gt_from_md > :last-child {
  margin-bottom: 0;
}
&#10;#nvvghpaynx .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}
&#10;#nvvghpaynx .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#nvvghpaynx .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}
&#10;#nvvghpaynx .gt_row_group_first td {
  border-top-width: 2px;
}
&#10;#nvvghpaynx .gt_row_group_first th {
  border-top-width: 2px;
}
&#10;#nvvghpaynx .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#nvvghpaynx .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}
&#10;#nvvghpaynx .gt_first_summary_row.thick {
  border-top-width: 2px;
}
&#10;#nvvghpaynx .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#nvvghpaynx .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#nvvghpaynx .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}
&#10;#nvvghpaynx .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}
&#10;#nvvghpaynx .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}
&#10;#nvvghpaynx .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#nvvghpaynx .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#nvvghpaynx .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#nvvghpaynx .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#nvvghpaynx .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#nvvghpaynx .gt_left {
  text-align: left;
}
&#10;#nvvghpaynx .gt_center {
  text-align: center;
}
&#10;#nvvghpaynx .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}
&#10;#nvvghpaynx .gt_font_normal {
  font-weight: normal;
}
&#10;#nvvghpaynx .gt_font_bold {
  font-weight: bold;
}
&#10;#nvvghpaynx .gt_font_italic {
  font-style: italic;
}
&#10;#nvvghpaynx .gt_super {
  font-size: 65%;
}
&#10;#nvvghpaynx .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}
&#10;#nvvghpaynx .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}
&#10;#nvvghpaynx .gt_indent_1 {
  text-indent: 5px;
}
&#10;#nvvghpaynx .gt_indent_2 {
  text-indent: 10px;
}
&#10;#nvvghpaynx .gt_indent_3 {
  text-indent: 15px;
}
&#10;#nvvghpaynx .gt_indent_4 {
  text-indent: 20px;
}
&#10;#nvvghpaynx .gt_indent_5 {
  text-indent: 25px;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="date">date</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="presenter">presenter</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="package">package</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="special topic">special topic</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="date" class="gt_row gt_right"><div class='gt_from_md'><p>2024-08-19</p>
</div></td>
<td headers="presenter" class="gt_row gt_left"><div class='gt_from_md'><p>Toby Hocking</p>
</div></td>
<td headers="package" class="gt_row gt_left"><div class='gt_from_md'><p>{animint2}</p>
</div></td>
<td headers="special topic" class="gt_row gt_left">NA</td></tr>
    <tr><td headers="date" class="gt_row gt_right"><div class='gt_from_md'><p>2024-06-22</p>
</div></td>
<td headers="presenter" class="gt_row gt_left"><div class='gt_from_md'><p>Elio Campitelli</p>
</div></td>
<td headers="package" class="gt_row gt_left"><div class='gt_from_md'><p>{ggnewscale}</p>
</div></td>
<td headers="special topic" class="gt_row gt_left">NA</td></tr>
    <tr><td headers="date" class="gt_row gt_right"><div class='gt_from_md'><p>2024-05-11</p>
</div></td>
<td headers="presenter" class="gt_row gt_left"><div class='gt_from_md'><p>Jonathan Sidi</p>
</div></td>
<td headers="package" class="gt_row gt_left"><div class='gt_from_md'><p>{ggedit}</p>
</div></td>
<td headers="special topic" class="gt_row gt_left">NA</td></tr>
    <tr><td headers="date" class="gt_row gt_right"><div class='gt_from_md'><p>2024-03-12</p>
</div></td>
<td headers="presenter" class="gt_row gt_left"><div class='gt_from_md'><p>Di Cook</p>
</div></td>
<td headers="package" class="gt_row gt_left"><div class='gt_from_md'><p>{GGally}</p>
</div></td>
<td headers="special topic" class="gt_row gt_left"><div class='gt_from_md'><p>A conversation with Di Cook</p>
</div></td></tr>
    <tr><td headers="date" class="gt_row gt_right"><div class='gt_from_md'><p>2024-02-10</p>
</div></td>
<td headers="presenter" class="gt_row gt_left"><div class='gt_from_md'><p>Malcolm Barrett</p>
</div></td>
<td headers="package" class="gt_row gt_left"><div class='gt_from_md'><p>{ggdag}</p>
</div></td>
<td headers="special topic" class="gt_row gt_left">NA</td></tr>
    <tr><td headers="date" class="gt_row gt_right"><div class='gt_from_md'><p>2023-11-04</p>
</div></td>
<td headers="presenter" class="gt_row gt_left"><div class='gt_from_md'><p>Nicola Rennie</p>
</div></td>
<td headers="package" class="gt_row gt_left"><div class='gt_from_md'><p>{ggflowchart}</p>
</div></td>
<td headers="special topic" class="gt_row gt_left">NA</td></tr>
    <tr><td headers="date" class="gt_row gt_right"><div class='gt_from_md'><p>2023-11-04</p>
</div></td>
<td headers="presenter" class="gt_row gt_left"><div class='gt_from_md'><p>W. Joel Schneider</p>
</div></td>
<td headers="package" class="gt_row gt_left"><div class='gt_from_md'><p>{arrowheadr}</p>
</div></td>
<td headers="special topic" class="gt_row gt_left">NA</td></tr>
    <tr><td headers="date" class="gt_row gt_right"><div class='gt_from_md'><p>2023-09-02</p>
</div></td>
<td headers="presenter" class="gt_row gt_left"><div class='gt_from_md'><p>Jonathan Carroll</p>
</div></td>
<td headers="package" class="gt_row gt_left"><div class='gt_from_md'><p>{ggeasy}</p>
</div></td>
<td headers="special topic" class="gt_row gt_left">NA</td></tr>
    <tr><td headers="date" class="gt_row gt_right"><div class='gt_from_md'><p>2023-06-10</p>
</div></td>
<td headers="presenter" class="gt_row gt_left"><div class='gt_from_md'><p>Daniel Sjoberg</p>
</div></td>
<td headers="package" class="gt_row gt_left"><div class='gt_from_md'><p>{ggsurvfit}</p>
</div></td>
<td headers="special topic" class="gt_row gt_left">NA</td></tr>
    <tr><td headers="date" class="gt_row gt_right"><div class='gt_from_md'><p>2023-04-15</p>
</div></td>
<td headers="presenter" class="gt_row gt_left"><div class='gt_from_md'><p>Gina Reynolds</p>
</div></td>
<td headers="package" class="gt_row gt_left"><div class='gt_from_md'><p>{ggcirclepack}</p>
</div></td>
<td headers="special topic" class="gt_row gt_left">NA</td></tr>
    <tr><td headers="date" class="gt_row gt_right"><div class='gt_from_md'><p>2022-01-28</p>
</div></td>
<td headers="presenter" class="gt_row gt_left"><div class='gt_from_md'><p>Claus Wilke</p>
</div></td>
<td headers="package" class="gt_row gt_left">NA</td>
<td headers="special topic" class="gt_row gt_left"><div class='gt_from_md'><p>‘Fundamentals of Data Visualization’ book project</p>
</div></td></tr>
    <tr><td headers="date" class="gt_row gt_right"><div class='gt_from_md'><p>2022-07-16</p>
</div></td>
<td headers="presenter" class="gt_row gt_left"><div class='gt_from_md'><p>June Choe</p>
</div></td>
<td headers="package" class="gt_row gt_left"><div class='gt_from_md'><p>{ggtrace}</p>
</div></td>
<td headers="special topic" class="gt_row gt_left">NA</td></tr>
    <tr><td headers="date" class="gt_row gt_right"><div class='gt_from_md'><p>2022-06-11</p>
</div></td>
<td headers="presenter" class="gt_row gt_left"><div class='gt_from_md'><p>Teun van den Brand</p>
</div></td>
<td headers="package" class="gt_row gt_left"><div class='gt_from_md'><p>{ggh4x}</p>
</div></td>
<td headers="special topic" class="gt_row gt_left">NA</td></tr>
    <tr><td headers="date" class="gt_row gt_right"><div class='gt_from_md'><p>2022-05-07</p>
</div></td>
<td headers="presenter" class="gt_row gt_left"><div class='gt_from_md'><p>Allan Cameron</p>
</div></td>
<td headers="package" class="gt_row gt_left"><div class='gt_from_md'><p>{geomtextpath}</p>
</div></td>
<td headers="special topic" class="gt_row gt_left">NA</td></tr>
    <tr><td headers="date" class="gt_row gt_right"><div class='gt_from_md'><p>2022-04-09</p>
</div></td>
<td headers="presenter" class="gt_row gt_left"><div class='gt_from_md'><p>David Sjoberg</p>
</div></td>
<td headers="package" class="gt_row gt_left"><div class='gt_from_md'><p>{ggbump}</p>
</div></td>
<td headers="special topic" class="gt_row gt_left">NA</td></tr>
    <tr><td headers="date" class="gt_row gt_right"><div class='gt_from_md'><p>2022-03-19</p>
</div></td>
<td headers="presenter" class="gt_row gt_left">NA</td>
<td headers="package" class="gt_row gt_left">NA</td>
<td headers="special topic" class="gt_row gt_left"><div class='gt_from_md'><p>First meeting</p>
</div></td></tr>
  </tbody>
  &#10;  
</table>
</div>

This repository will accommodate some discussion outside those meetings
and coordination efforts. Feel free to participate in discussions and be
in touch!

## Links:

### General

- The [ggplot2](https://github.com/tidyverse/ggplot2) repository

### Extending ggplot2

- The extending ggplot2 chapters of the [ggplot2
  book](https://ggplot2-book.org/):
  - Chapter 19: [Programming with
    ggplot2](https://ggplot2-book.org/programming.html)
  - Chapter 20: [ggplot2
    internals](https://ggplot2-book.org/internals.html)
  - Chapter 21: [Writing ggplot2
    extensions](https://ggplot2-book.org/extensions.html)
  - Chapter 22: [Case Study:
    Springs](https://ggplot2-book.org/spring1.html)
- The [extending
  ggplot2](https://ggplot2.tidyverse.org/articles/extending-ggplot2.html)
  vignette
- The [ggproto](https://stackoverflow.com/questions/tagged/ggproto) tag
  on StackOverflow

### Extensions

- The [extensions gallery](https://exts.ggplot2.tidyverse.org/gallery/)
- The [Awesome `ggplot2`](https://github.com/erikgahner/awesome-ggplot2)
  repository

### Talks

- [Extending your ability to extend
  ggplot2](https://www.rstudio.com/resources/rstudioconf-2020/extending-your-ability-to-extend-ggplot2/)
  by Thomas Lin Pederson at rstudio::conf 2020
- [Best practises for programming with
  ggplot2](https://www.rstudio.com/resources/rstudioconf-2020/best-practices-for-programming-with-ggplot2/)
  by Dewey Dunnington at rstudio::conf 2020
- [Cracking open ggplot internals with
  {ggtrace}](https://www.rstudio.com/resources/rstudioconf-2020/best-practices-for-programming-with-ggplot2/)
  by June Choe at rstudio::conf 2022

![](https://github.com/teunbrand/ggplot-extension-club/blob/main/ggextenders-hex_files/figure-html/unnamed-chunk-1-1.png?raw=true)

# Adding-lines-or-other-geoms-to-a-ggplot-by-calling-a-custom-function

The code set has been added via the attached .docx file in this repository to refer.

Sometimes you generate lots of ggplots of a similar kind, e.g. visualizations of different timeseries. Then you want to highlight some dates where something special had happened and you want to show that the value you are plotting changed at these dates.

So it would be nice if we can refactor these geom_vline or geom_hline calls into one single function.

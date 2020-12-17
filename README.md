# DataSwap

The *DataSwap* software is a SAS® macro that was developed and
maintained by Westat under contract with the National Center for
Education Statistics/Institute of Education Sciences (IES)/Department of
Education. The software conducts controlled random swapping. A user
manual accompanies the SAS macro and provides the syntax for calling the
macro, a technical description, and examples.

*DataSwap* employs a controlled random swapping approach by selecting
records for swapping using different random sampling approaches (simple
random sampling, stratified, probability proportionate to size). It
selects swapping partners based on a distance (or bias) measure and can
be used on data with complex samples. IES standard practice is to
process the swapping five to seven times and review the global utility
measures to recommend one of the runs.

For the controlled random swapping approach, "controlled" means two
things: First, it means that the user is responsible for identifying the
data swapping variables and parameters. The user/data analyst should be
familiar with which data would be the most identifiable and sensitive.
The user should also understand the content of the data file as well as
the purpose and focus of the study so s/he can therefore guide the data
swapping procedures accordingly.

The second meaning of "controlled" is that, in *DataSwap*, once the
target records are selected, the file is partitioned into swapping
cells. The swapping methodology is designed to find a swapping partner
that limits data distortion. The methodology includes the use of
swapping cells to identify swapping partners in adjacent cells with
similar (or identical) weights and close (with at least one or some
different) variable values. The pair with the smallest swapping bias is
selected as the swapping partner.

Before implementing *DataSwap*, the user must consider several facets of
the swapping process, including how the targets are to be selected, if
particular records will be targeted for swapping, how the swapping cells
are to be formed, and which variables will be swapped. Output reports
help the user evaluate the swapping impact, which can also be controlled
through the software parameters.

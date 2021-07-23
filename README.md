# Hierarchical Catalog of Straight-line Highway Scenarios

Test  scenario  generation  for  testing  automated and autonomous driving systems requires knowledge about the recurring  traffic  cases,  known  as  scenario  types.  The  most common  approach  in  industry  is  to  have  experts  create  lists of  scenario  types.  This  poses  the  risk  both  that  certain  types are  overlooked;  and  that  the  mental  model  that  underlies  the manual  process  is  inadequate.  We  extracted  scenario types  from  real  driving  data  by  clustering  recorded  scenario instances, which are composed of time series. 
We have constructed a living system of relevant scenario types that changes over time as we gather empirical evidences. The hierarchical format of the catalog helps user to have access to scenarios at three levels of granularity. Depending on context, one can decide which granularity to use. At the first level, scenarios are grouped based on the scene types and street type. At the second level, scenarios are grouped based on the trajectory of the ego vehicle, and at the third level scenarios are grouped based on the distances of the ego vehicle from its surrounding vehicles.

## Scenarios - Level 1 
[2-Lane Highway](https://github.com/openscenario/openscenario.github.io/tree/main/scenarios/2lanes)

[3-Lane Highway](https://github.com/openscenario/openscenario.github.io/tree/main/scenarios/3lanes)

## Scenarios - Level 2 

[2-Lane Highway - Ego vehicle keeps forwarding in the right lane](https://github.com/openscenario/openscenario.github.io/tree/main/scenarios/2lanes/2-forwarding-ego-right)

[2-Lane Highway - Ego vehicle keeps forwarding in the left lane](https://github.com/openscenario/openscenario.github.io/tree/main/scenarios/2lanes/2-forwarding-ego-left)

[2-Lane Highway - Ego vehicle changes the lane](https://github.com/openscenario/openscenario.github.io/tree/main/scenarios/2lanes/2-lanechange)

[3-Lane Highway - Ego vehicle keeps forwarding in the right lane](https://github.com/openscenario/openscenario.github.io/tree/main/scenarios/3lanes/3-forwarding-ego-right)

[3-Lane Highway - Ego vehicle keeps forwarding in the left lane](https://github.com/openscenario/openscenario.github.io/tree/main/scenarios/3lanes/3-forwarding-ego-left)

[3-Lane Highway - Ego vehicle keeps forwarding in the middle lane](https://github.com/openscenario/openscenario.github.io/tree/main/scenarios/3lanes/3-forwarding-ego-middle)

[3-Lane Highway - Ego vehicle changes the lane](https://github.com/openscenario/openscenario.github.io/tree/main/scenarios/3lanes/3-lanechange)


<!--## Deployment online

The website can be accessed via https://openscenario.github.io.

## Deployment locally

The website can be build and deployed locally using [jekyll](https://jekyllrb.com/docs/).

After downloading and installing all requirements for jekyll, execute the following comamnds in the websites folder:

1. ```bundle update```
2. ```bundle exec jekyll serve```

The website can be accessed locally at *localhost:4000*.

## Customization

Consider for changing links and text content *.html* files in the top level folder and the *_data*-Folder. -->

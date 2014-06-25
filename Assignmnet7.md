#### Assignment 7

`````sql

SELECT state,s_b.shape,volc.shape FROM `volcanoes` as volc left outer join `state_borders` as s_b ON contains(s_b.shape,volc.shape) where s_b.state='California'
`````
`````sql

SELECT state,s_b.shape,eqc.shape FROM `eath_quakes` as eqc left outer join `state_borders` as s_b ON contains(s_b.shape,eqc.shape) where s_b.state='California'
`````

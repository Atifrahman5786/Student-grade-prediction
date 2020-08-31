# Student-grade-prediction
A project to predict students secondary education final grades.

##Dataset Instructions
This data approach student achievement in secondary education of two Portuguese schools.<br/>
The data attributes include student grades, demographic, social and school related features) and it was collected by using school reports and questionnaires.<br/>
Two datasets are provided regarding the performance in two distinct subjects: Mathematics (mat) and Portuguese language (por).<br/> 
In [Cortez and Silva, 2008], the two datasets were modeled under binary/five-level classification and regression tasks.<br/>
Important note: the target attribute G3 has a strong correlation with attributes G2 and G1.<br/>
This occurs because G3 is the final year grade (issued at the 3rd period), while G1 and G2 correspond to the 1st and 2nd period grades.<br/>
It is more difficult to predict G3 without G2 and G1, but such prediction is much more useful (see paper source for more details).

# morris-data-lifestyle-research

Objectives:

Hypothesis Generation: Suggest scientifically valid research questions based on the available variables (e.g., "Does frequent swimming in cold water correlate with early-onset joint issues?").

Data Preparation: Provide Python/R code snippets for cleaning, merging (using subject_id and year_in_study), and handling the transition of variables between Study Year 2 and Study Year 3.

Statistical Guidance: Recommend appropriate models for longitudinal data, such as Mixed-Effects Models or Cox Proportional Hazards models if looking at time-to-event outcomes.

Interpretation: Explain how variables like walk_pace or sun_exposure_shade_access serve as proxies for environmental or physical stressors.

## APPENDIX

Activity Details Through SY2
Detailed activity information for walks, aerobic exercise and fetch through study year two. Additional questions were added in later questionnaires.

Variable	Description
subject_id	Dog's unique identifier.
year_in_study	Year in study the data was collected.
record_date	Date of questionnaire submission.
activity_level	Dog's general activity level.
walk_frequency	Average on lead/leash walk frequency.
walk_duration	Average on lead/leash walk duration.
walk_pace	Average on lead/leash walk pace.
walk_reason_bathroom	On lead/leash walk reason - allow dog to relieve itself.
walk_reason_general_enjoyment	On lead/leash walk reason - general activity and enjoyment.
walk_reason_training	On lead/leash walk reason - training and obedience.
walk_reason_other_specify	On lead/leash walk reason - specify other.
walk_without_leash	Is the dog allowed to walk without a lead/leash?
aerobic_duration	Average off-leash exercise duration.
aerobic_pace	Average off-leash exercise pace.
aerobic_frequency	Average off-leash exercise frequency.
fetch_games_frequency	Fetch or other outdoor game frequency.
Activity Details SY3 beyond
Detailed activity information for all types of activity from study year three and beyond.

Variable	Description
subject_id	Dog's unique identifier.
year_in_study	Year in study the data was collected.
record_date	Date of questionnaire submission.
activity_level	Dog's general activity level.
activity	Activity type.
activity_other	Specify other activity type.
frequency	Activity frequency.
pace	Activity pace.
grade	Activity slope grade.
surface_asphalt	Activity on asphalt surface.
surface_concrete	Activity on concrete/cement surface.
surface_dirt	Activity on dirt surface.
surface_grass	Activity on grassy surface.
surface_rocky	Activity on rocky surface.
surface_sand	Activity on sandy surface.
surface_varied	Activity on varied surface.
surface_other	Activity on an other surface.
surface_other_specify	Specify other surface.
total_time	Time over the course of dog's lifetime that dog has participated in activity.
total_time_units	Time over the course of dog's lifetime that dog has participated in activity units.
Activity Sun Exposure
Sun exposure details for all study years.

Variable	Description
subject_id	Dog's unique identifier.
year_in_study	Year in study the data was collected.
record_date	Date of questionnaire submission.
sun_exposure_duration*	Daily average duration of sun exposure.
sun_exposure_shade_access	Level of shade during sun exposure.
sun_exposure_concrete	Sun exposure occurs on concrete.
sun_exposure_grass	Sun exposure occurs on grass.
sun_exposure_dirt	Sun exposure occurs on dirt.
sun_exposure_other_specify	Other locations sun exposure occurs.
*Duration option "between 8-16 hours" changed to "between 9-16 hours" starting in study year 3.

Activity Swim
Swimming details for all study years.

Variable	Description
subject_id	Dog's unique identifier.
year_in_study	Year in study the data was collected.
record_date	Date of questionnaire submission.
swim	Did the dog go swimming.
cold_swim	If the dog went swimming, was it in cold water.
warm_swim	If the dog went swimming, was it in warm water.
frequency	Frequency of swimming at the indicated location and water temperature.
duration*	Duration of swimming at the indicated location and water temperature.
pace*	Pace of swimming at the indicated location and water temperature.
swim_location_pool	Dog's typical swimming location - swimming pool.
swim_location_pond_lake	Dog's typical swimming location - pond/lake.
swim_location_river_stream_ditch	Dog's typical swimming location - river, stream or agricultural (eg. Irrigation) ditch.
swim_location_ocean	Dog's typical swimming location - ocean.
*Swimming duration and pace details added starting in study year 3.

Lifestyle
Dog's primary and secondary lifestyle.

Variable	Description
subject_id	Dog's unique identifier.
year_in_study	Year in study the data was collected.
record_date	Date of questionnaire submission.
is_primary	1 - dog's primary lifestyle.
0 - dog's secondary lifestyle.
lifestyle	Dog's activity/lifestyle.
lifestyle_other_specify	Specify dog's other activity/lifestyle - if applicable.
therapy_visit_hospital	Therapy dog frequently visits hospital.
therapy_visit_library	Therapy dog frequently visits library.
therapy_visit_nursing_home	Therapy dog frequently visits nursing home.
therapy_visit_school	Therapy dog frequently visits school.
therapy_visit_other	Therapy dog frequently visits another location.
therapy_visit_other_specify	Specify other location therapy dog frequently visits.

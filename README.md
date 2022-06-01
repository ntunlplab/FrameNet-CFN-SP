# NTU Chinese FrameNet Subset Parser (CFN-SP)
# Introduction
This system is traind on FrameNet subset of 31 frames ('Arriving', 'Accompaniment', 'Visiting', 'Discussion', 'Meet_with', 'Presence', 'Ingestion', 'Ride_vehicle', 'Perception_active', 'Sleep', 'Competition', 'Attending', 'Giving', 'Text_creation', 'Transitive_action', 'Resolve_problem', 'Statement', 'Receiving', 'Taking_time', 'Social_event', 'Departing', 'Deciding', 'Arranging', 'Waiting', 'Perception_experience', 'Contacting', 'Borrowing', 'Commerce_buy', 'Questioning', 'Activity', 'Inspecting') that could fulfill daily events for lifelogging. The overall performance for frame semantic parsing of our system is F1 score 97.12 and 85.14 for training and testing respectively.

# Example
"楊基振十一點半與袁總理懇談許多公司目前的問題 " in our parser will instantiate frame Discussion and the following frame element realization:

<!-- 楊基振<sub>Interlocutor_1</sub> 十一點半<sub>Time</sub> 與 袁總理<sub>Interlocutor_2</sub> 懇談<sub>Frame.Discussion</sub> 許多 公司<sub>Domain</sub> 目前 的 問題<sub>Topic</sub> -->
![image](https://user-images.githubusercontent.com/106158192/171118451-2fdb37e4-bc99-4778-b7a6-68f67115a27f.png)

# Demo
Click [here](http://nlg.csie.ntu.edu.tw/nlpresource/FrameNet/CFN-SP/) to access demosite.


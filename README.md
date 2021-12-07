# User-Preference-Dataset

A series of model-based and learning-based ABR algorithms leverage the uniform QoE function to pick bitrate for each video segment. However, it cannot meet the viewer's actual demand in practice. Since the requirements among different viewers are distinct, the QoE function with fixed weights may lead to performance degradation under QoE diversity. To tackle this issue, we collect a user video-watching dataset and use this dataset to infer their viewing preferences.

Specifically, we invite 50 people to participate in this test. For each viewer, they can choose 30 of their favourite videos from the video dataset to watch. We also give them a questionnaire prior to the experiment, which let them choose their specific preference. The volunteers are required to finish the questionnaire after viewing the test videos. In this fashion, we can extract each user's viewing preferences from their operation history during the viewing process and utilize the answer from the questionnaire as the corresponding label.

We process the dataset into three csv files, which are prefer-high-quality, prefer-low-rebuffering and prefer-low-switching, respectively. Each file contains five features that correspond to the paper. 0 represents false and 1 represents true.

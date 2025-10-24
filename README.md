# CL-Drive
CL-Drive is a driver cognitive load assessment dataset which contains Electroencephalogram (EEG) signals along with other physiological signals such as Electrocardiography (ECG) and Electrodermal Activity (EDA), and eye tracking data. We have used Muse S headband with 4 channels to collect EEG data, shimmers to collect ECG and EDA data and Tobii to collect Gaze data. The data is collected from 21 participants during driving in an immersive simulated vehicle. The participants drove in different driving conditions to induce 9 cognitive load levels and the duration for each complexity level is 3 minutes. Please view our paper ["Multimodal Brain-Computer Interface for In-Vehicle Driver Cognitive Load Measurement: Dataset and
Baselines"](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10382455&casa_token=cIJ2eThYHcIAAAAA:qkw5MTEZFvKfdBqCg4v3FZERtzUyC-5Im3R0_DDuwGlRNrl4y8i1FEmjsrRCJHXF7KO8UOuV9Q) for more details.

![Alt text](/Figures/driving_simulator.jpg?raw=true "Optional Title")

# Sensor placement
This figure shows the placement of the 4 sensors.
![Alt text](/Figures/sensor_placement.jpg?raw=true "Optional Title")
 

# Download dataset

* Download the CL-Drive dataset from [here]([https://borealisdata.ca/privateurl.xhtml?token=505ef1f5-18f8-407b-a9aa-31c964208005](https://can01.safelinks.protection.outlook.com/?url=https%3A%2F%2Fborealisdata.ca%2Fdataset.xhtml%3FpersistentId%3Ddoi%3A10.5683%2FSP3%2FJJ2YZZ&data=05%7C02%7Cprithila.angkan%40queensu.ca%7C6b966caccb534c94c5f508de1334f12b%7Cd61ecb3b38b142d582c4efb2838b925c%7C1%7C0%7C638969315676990335%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C60000%7C%7C%7C&sdata=fkhtr1ojR8Xdb%2F7C3XrTun6Gb%2FZ2ZbCBd9OSVX%2FvPcU%3D&reserved=0)).
* The structure of the dataset would be:

```    
CL-Drive
    |----EEG 
         |----participant_ID_1
                      |----eeg_data_level_1
                      |----eeg_baseline_level_1
                      .
                      .
                      .
                      |----eeg_data_level_9
                      |----eeg_baseline_level_9
         .
         .
         .
         |----participant_ID_21
    |----EDA
    |----ECG
    |----Gaze
    |----Labels
```


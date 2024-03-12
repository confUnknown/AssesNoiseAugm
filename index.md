
Skip to content

    confUnknown
    /
    AssesNoiseAugm

Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights

    Settings

Files
t

audio_clips
LICENSE
README.md
_config.yml

    index.md

Editing index.md in AssesNoiseAugm
Breadcrumbs

    AssesNoiseAugm

/
in
main

Indent mode
Indent size
Line wrap mode
Editing index.md file contents
Selection deleted
48
49
50
51
52
53
54
55
56
57
58
59
60
61
62
63
64
65
66
67
68
69
70
71
72
73
74
75
76
77
78
79
80
81
82
83
84
85
86
87
88
89
90
91
92
93
94
95
96
97
98
99
100
101
102
103
104
105
106
107
108
109
110
111
112
113
114
115
116
117
118
119
120
121
122
123
124
125
126
127
128
129
130
131
132
133
134
135
136
137
[**1**: *WER*=00.00],            [**1**: *WER*=42.86]  
[**2**: *WER*=00.00],            [**2**: *WER*=28.57]  
[**3**: *WER*=00.00],            [**3**: *WER*=0.00]  
<audio style="width:320px" controls="controls">
	<source src="audio_clips/c_w/7729-102255-0034.wav" type="audio/wav" />
</audio>
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/c_w/7729-102255-0034_benign_noise.wav" type="audio/wav" />
</audio>
**C&W adversarial**:           **C&W adversarial + Noise**:  
[**1**: *WER*=00.00, SNR<sub>seg</sub>=22.20],     [**1**: *WER*=100.0]  
[**2**: *WER*=00.00, SNR<sub>seg</sub>=17.04],     [**2**: *WER*=100.0]  
[**3**: *WER*=60.00, SNR<sub>seg</sub>=04.13],     [**3**: *WER*=100.0]  
<audio style="width:320px" controls="controls">
	<source src="audio_clips/c_w/7729-102255-0034_cw_26022.wav" type="audio/wav" />
</audio>
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/c_w/7729-102255-0034_cw_noise_26022.wav" type="audio/wav" />
</audio>
###### Sample 3
<pre>Benign transcription:       <em>BUT YOU KNOW MORE ABOUT THAT THAN I DO SIR</em>
Adversarial transcription:  <em>YES MY DEAR WATSON I HAVE SOLVED THE MYSTERY</em>
</pre> &nbsp;
**Benign**:               **Benign + Noise**: SNR<sub>seg</sub>= -0.41  
[**1**: *WER*=00.00],            [**1**: *WER*=50.00]  
[**2**: *WER*=00.00],            [**2**: *WER*=40.00]  
[**3**: *WER*=00.00],            [**3**: *WER*=10.00]  
<audio style="width:320px" controls="controls">
	<source src="audio_clips/c_w/2094-142345-0055.wav" type="audio/wav" />
</audio>
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/c_w/2094-142345-0055_benign_noise.wav" type="audio/wav" />
</audio>
**C&W adversarial**:           **C&W adversarial + Noise**:  
[**1**: *WER*=00.00, SNR<sub>seg</sub>=25.78],     [**1**: *WER*=100.0]  
[**2**: *WER*=00.00, SNR<sub>seg</sub>=23.94],     [**2**: *WER*=88.89]  
[**3**: *WER*=60.00, SNR<sub>seg</sub>=22.30],     [**3**: *WER*=100.0]  
<audio style="width:320px" controls="controls">
	<source src="audio_clips/c_w/2094-142345-0055_cw_26022.wav" type="audio/wav" />
</audio>
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/c_w/2094-142345-0055_cw_noise_26022.wav" type="audio/wav" />
</audio>

### Experiments for the Alzantot attack.
###### Sample 1 
<pre>Benign transcription:       <em>THE CLOUD THEN SHEWD HIS GOLDEN HEAD AND HIS BRIGHT FORM EMERG'D</em>
</pre> &nbsp;
**Alzantot adversarial**:  
[**1**: *WER*=66.67, SNR<sub>seg</sub>=11.55]  
[**2**: *WER*=66.67, SNR<sub>seg</sub>=11.55]  
[**3**: *WER*=41.67, SNR<sub>seg</sub>=11.56]  
**Benign**:               **Alzantot adversarial**:  
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Alzantot/908-157963-0017.wav" type="audio/wav" />
</audio>
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Alzantot/908-157963-0017_26020.wav" type="audio/wav" />
</audio>
###### Sample 2 
<pre>Benign transcription:       <em>THE CLOUD THEN SHEWD HIS GOLDEN HEAD AND HIS BRIGHT FORM EMERG'D</em>
</pre> &nbsp;
**Alzantot adversarial**:  
[**1**: *WER*=42.86, SNR<sub>seg</sub>=13.62]  
[**2**: *WER*=42.86, SNR<sub>seg</sub>=13.54]  
[**3**: *WER*=14.29, SNR<sub>seg</sub>=29.5]  
**Benign**:               **Alzantot adversarial**:  
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Alzantot/908-157963-0017.wav" type="audio/wav" />
</audio>
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Alzantot/908-157963-0017_26020.wav" type="audio/wav" />
</audio>

### Experiments for the Kenansville attack.
###### Sample 1 
<pre>Benign transcription:       <em>THEN HE LOOKED DOWN THE LAGOON WAS DRY</em>
Adversarial transcription:  <em>PEARL WAS A BORN OUTCAST OF THE INFANTILE WORLD</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=62.50, SNR<sub>seg</sub>=-4.79]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/1995-1837-0013_benign.wav" type="audio/wav" />
</audio>
###### Sample 2
<pre>Benign transcription:       <em>THEN HE LOOKED DOWN THE LAGOON WAS DRY</em>
Adversarial transcription:  <em>PEARL WAS A BORN OUTCAST OF THE INFANTILE WORLD</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=62.50, SNR<sub>seg</sub>=-4.79]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/1995-1837-0013_benign.wav" type="audio/wav" />
Use Control + Shift + m to toggle the tab key moving focus. Alternatively, use esc then tab to move to the next interactive element on the page.
Attach files by dragging & dropping, selecting or pasting them.
Editing AssesNoiseAugm/index.md at main · confUnknown/AssesNoiseAugm
 

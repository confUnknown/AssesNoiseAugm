# Adversarial example demo

Supplementary material containing a selection of benign, adversarial, and noisy data employed in our [*paper*]().

For each sample, we include the word error rate (WER) as an accuracy metric and the segmental signal-to-noise ratio (SNR<sub>seg</sub>) as a quality noise metric. An SNR<sub>seg</sub> exceeding 0 dB indicates a stronger signal presence compared to noise. These samples are sourced from the [*Librispeech*](https://www.openslr.org/12) corpus dataset.

As outlined in our paper we investigated three types of training regimes, resulting in three different models, respectively :

1: baseline (no augmentation): This model serves as our control of the clean dataset without any form of augmentation. 
    This baseline establishes the standard level of performance for each model under ideal acoustic conditions.
    
2: augmentation with speed variations: During the training of the second model temporal variability was introduced into the training data by applying speed perturbations. 
    These augmentations simulate natural variations in speech tempo, which can occur due to speaker differences or recording conditions.
    
3: augmentation with speed variations, background noise, and reverberation: The third model is trained with both background noises and reverberations, in addition to speed variations. 
    This combination aims to mimic more challenging and realistic acoustic environments that ASR systems may encounter in real-world applications.

### Experiments for the C&W attack.
###### Sample 1 
<pre>Benign transcription:       <em>THEY OF COURSE MUST ALL BE ALTERED</em>
Adversarial transcription:  <em>LOOK AT THAT HE HELD OUT HIS HAND</em>
</pre> &nbsp;
[**Benign**:],                     [**noisy**:]                                
[**1**: *WER*=14.29],                    [**1**: *WER*=71.43, SNR<sub>seg</sub>=-4.79]                     
[**2**: *WER*=00.00],                    [**2**: *WER*=57.14, SNR<sub>seg</sub>=-4.79]                      
[**3**: *WER*=14.29],                    [**3**: *WER*=25.87, SNR<sub>seg</sub>=15.9]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/c_w/8455-210777-0066.wav" type="audio/wav" />
</audio>
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/c_w/8455-210777-0066_benign_noise.wav" type="audio/wav" />
</audio>
###### Sample 2
<pre>Benign transcription:       <em>THEN HE LOOKED DOWN THE LAGOON WAS DRY</em>
Adversarial transcription:  <em>PEARL WAS A BORN OUTCAST OF THE INFANTILE WORLD</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=62.50, SNR<sub>seg</sub>=-4.79]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/1995-1837-0013_benign.wav" type="audio/wav" />
</audio>
###### Sample 3 
<pre>Benign transcription:       <em>THEN HE LOOKED DOWN THE LAGOON WAS DRY</em>
Adversarial transcription:  <em>PEARL WAS A BORN OUTCAST OF THE INFANTILE WORLD</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=62.50, SNR<sub>seg</sub>=-4.79]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/1995-1837-0013_benign.wav" type="audio/wav" />
</audio>

### Experiments for the Alzantot attack.
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
</audio>
###### Sample 3 
<pre>Benign transcription:       <em>THEN HE LOOKED DOWN THE LAGOON WAS DRY</em>
Adversarial transcription:  <em>PEARL WAS A BORN OUTCAST OF THE INFANTILE WORLD</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=62.50, SNR<sub>seg</sub>=-4.79]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/1995-1837-0013_benign.wav" type="audio/wav" />
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
</audio>
###### Sample 3 
<pre>Benign transcription:       <em>THEN HE LOOKED DOWN THE LAGOON WAS DRY</em>
Adversarial transcription:  <em>PEARL WAS A BORN OUTCAST OF THE INFANTILE WORLD</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=62.50, SNR<sub>seg</sub>=-4.79]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/1995-1837-0013_benign.wav" type="audio/wav" />
</audio>

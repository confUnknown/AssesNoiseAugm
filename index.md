# Adversarial example demo

Supplementary material containing a selection of benign, adversarial, and noisy data employed in our [*paper*]().

For each sample, we include the word error rate (WER) or the character error rate (CER) as an accuracy metric and the segmental signal-to-noise ratio (SNR<sub>seg</sub>) as a quality noise metric. An SNR<sub>seg</sub> exceeding 0 dB indicates a stronger signal presence compared to noise. These samples are sourced from the [*Librispeech*](https://www.openslr.org/12), [*Commonvoice*](https://commonvoice.mozilla.org/en), and [*Aishell*](https://www.openslr.org/33/) corpus datasets.

## Librispeech - English
###### Sample 1 
<pre>Benign transcription:       <em>THEN HE LOOKED DOWN THE LAGOON WAS DRY</em>
Adversarial transcription:  <em>PEARL WAS A BORN OUTCAST OF THE INFANTILE WORLD</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=62.50, SNR<sub>seg</sub>=-4.79]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/1995-1837-0013_benign.wav" type="audio/wav" />
</audio>

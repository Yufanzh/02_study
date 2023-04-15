### [Huggingface](https://huggingface.co/blog/hf-bitsandbytes-integration) 
1. Time Dettmers [talk](https://youtu.be/jyOqtw4ry2w)
	1. fundamentals of quantization: blocking...
	2. outliers in hidden layers showed up more frequently when model size gt 6B; and they tend to show up on the same cols.
	3. intuition of outliers: 34:22
	4. me: outliers are NOT errors, they are just feature of the transformers.
	5. Around 31:20, 'perplexity has a -0.95 correlation with zero-shot performance', 'so one is a good measure of the other'

### Floating points and its calculation
1. Nice article from [Wiki](https://en.wikipedia.org/wiki/Half-precision_floating-point_format) and the table in there. *Notice different precision smaller/greater than one.*
	![[Pasted image 20230415073543.png]]
2. First 20mins of this MIT Lecture https://youtu.be/AlASZb93rrc


### Misc
1. TF32 is for Ampere architecture and later
2. codebook/index
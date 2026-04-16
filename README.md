I care about AI Safety.

"Why does a biologist care about AI safety?"


At ViaCyte I tended little gardens of flesh...

That's cell culture of human embryonic stem cells.  Those blank-slate cells that can become any type of cell in the body, provided they get the right encouragement.

I learned how to grow these blank-slate cells into tiny insulin factories that pump out cell juice when there is sugar around.  We were the first ones to do that! Once we got that down, we needed to make sure it was safe to put into people!  

I did a bunch of studies in mice to figure out teratoma growth thresholds.  Teratomas are what stem cells become if they don't have proper guidance growing up.  You do not want teratomas in your body.  From the mouse work and studying how stem cells become teratomas,  I derived a dosing metric for histological detection of stem cells... that was pretty laborious.  Thousands of slides looking for only a few cells every million.  

When you're looking for a needle in a haystack --get a magnet!!  That was my introduction to ML and computer vision.

I started off with a simple random forest decision trees trained on basic features in the histology.  With a lot of iteration and intentionally breaking the process with contrived input, I got a workable system that could detect 4 in a million cells that didn't belong in our patients.

Why 4 in a million?  Our regulatory guidance from the FDA has stringent guidance that we need to demonstrate, based on our the teratoma animal studies (remember this was cutting edge so not a lot of generic safety data lying around), to show that our product was safe in people.  We had to show the assay had an acceptable Lower Limit of Detection, that the in vitro controls behaved consistently both within the assay and amonge all runs, and I had to demonstrate that the algorithm made the correct calls when I tossed adversarial data at it.

We achieved the FDA's blessing and proceeded to use the assay and its descendents for a decade in evaluating all our clinical trial cell lots.

Over time, I incorporated different styles of analysis and more sophisticated ML with CNNs.  With better tools and more brain, I can finesse more nuance out of a histological landscape.  Doing it at scale allows a cellular narrative to develop a rate that allows nimble pivots to better learning.  Teaching Densenet how to tell the difference between human cells in an implanted device...from the human cells that surround that device was a big moment.  Even better was when I taught it to to tease apart long skinny vascular tissue from long skinny fibrosis that grow together and stain the same way...that was cool..and useful!  It let us explore how to control the growth each one --pretty important when you don't want fibrosis clogging up your vascular supply chain.

Our first-in-human stem cell therapy for Type 1 Diabetes was amazing.  It was also scary to put it into people for our first clinical trial.  

Before we got to that point with our awesome new treatment, we spent the time and resources to make sure it would not cause harm.  Not harming patients with our new treatment is basic --the same as not letting AI be an autonomous decisionmaker --until we evaluate every aspect of how it could go wrong, demonstrate it,  and hold ourselves to a high standard of care that it will not go wrong. 

Safety is the thing.  Be bold! Not reckless.  
___
  
  
  
  
    
  
⚡ Fun fact: I have caught bats out of the air with my bare hands

<img src="https://github.com/user-attachments/assets/9732fbbd-449e-439e-99a3-9e8c11f7898b" alt="josie elle" width="400"/>


<!---
Ampelion/Ampelion is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

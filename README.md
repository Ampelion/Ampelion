I care about AI safety.

Why would a biologist?

At ViaCyte I grew human embryonic stem cells into insulin-producing tissue for a first-in-human Type 1 Diabetes therapy. Pluripotent cells become anything. Including, if you get it wrong, a teratoma in your patient. My job was to prove that would not happen with our cells.

That meant finding a few stray undifferentiated cells in a million, across thousands of histology slides, reliably enough that the FDA would let us put the product into people. Needle in a haystack. So I built a magnet: a random-forest classifier on histological features, hardened by deliberately feeding it adversarial inputs until it stopped failing on the cases that mattered. I had to demonstrate an acceptable limit of detection, controls that held within and across runs, and correct calls under adversarial data. We got clearance and ran that assay and its descendants on every clinical lot for a decade.

It got sharper over time — CNNs, DenseNet, more nuance pulled out of the tissue. Training a network to separate implanted human cells from the host cells around them. Then to tell vascular tissue from fibrosis when they grow together and stain identically — which helped us study how to keep fibrosis from strangling the blood supply the device needed.

I have held the consequences of safety failure in my hands. The discipline that prevents it is not complicated and it is not optional: reason first, then act. Enumerate what can go wrong. Try to make it go wrong, in every conformation, many times. Fold the failure modes into the test. Repeat thousands of times. Submit it to a regulator. Take the notes. Refine. Demonstrate. Then act.

Biology is squishy, complex, surprising, and ultimately understandable. AI is too, squishy in sensu silico. Let the system show what it does, where it fails. Understand, control.

Bold, not reckless.
 
___
 
<img src="https://github.com/user-attachments/assets/9732fbbd-449e-439e-99a3-9e8c11f7898b" alt=" swapping wheels at the track" width="400"/>



Torque first, fast second.
<!---
Ampelion/Ampelion is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

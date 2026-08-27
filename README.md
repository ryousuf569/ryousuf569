<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&height=180&color=0:0F172A,100:1E3A8A&text=Bunior&fontColor=E2E8F0&fontAlign=50&fontAlignY=40&desc=Applied%20Math%20%7C%20Scientific%20ML%20%7C%20Cryptography&descAlign=50&descAlignY=62&descSize=16" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&pause=1200&color=94A3B8&center=true&vCenter=true&width=650&lines=Second-year+Applied+Math+(Scientific+ML)%2C+Waterloo;MPC+cryptography+by+day%2C+dynamical+systems+by+night;Chaos%2C+group+theory%2C+and+the+occasional+PPO+agent" alt="typing" />

</div>

---

### First principles

I'm doing Applied Mathematics with a Scientific ML specialization at Waterloo, currently on co-op as an AI/ML engineering intern at a small AI security startup, working on multi-party computation protocols. I don't really pick projects for the resume line — I pick them because they force me to actually learn a piece of math I've been circling (chaos theory, group symmetry, pitch control fields in soccer, whatever), and code is just the fastest way to find out if I understood it or was fooling myself.

Grew up in Saskatchewan. Long arc, if it holds: an ML research lab, then eventually a systematic fund with people I trust.

---

### Currently in motion

- **TripleLock** — patent-pending MPC authentication protocol, co-designed at DeepIDV
- **haramball-hunter** — PPO agent trained to break a low-block soccer defense against a from-scratch physics engine
- **Wat.AI** — asset-conditioned financial sentiment model: same headline, different signal depending on what it's about
- **Abeliator** — a wavetable generator built on preferential Bayesian optimization over a learned latent space

---

### Instruments

<div align="center">
<img src="https://skillicons.dev/icons?i=python,cpp,julia,ts,react,pytorch,nodejs,mongodb,postgres,git,linux,vercel&perline=6" />
</div>

---

### Selected work

**haramball-hunter** — *reinforcement learning, dynamical systems*
A PPO agent learns to dismantle a low-block defense, rewarded against a pitch-control field I derived from Spearman's kinematic model and built from scratch in NumPy. Ported the reward computation to a custom CUDA kernel for a 5.1x throughput gain (44 to 224 env steps/sec), with the two backends agreeing to about 1e-5. Currently reframed around a constrained-RL question: when you ask a trained policy for a behavior at some target rate, does it actually land there, or drift.

**TripleLock** — *applied cryptography*
An MPC-based authentication protocol, patent-pending, built during my time at DeepIDV. This is the part of the internship that's closest to what got me into the math side of security in the first place — protocols where the interesting object is the proof, not the implementation.

**Abeliator** — *group theory, chaos, Bayesian optimization*
A web-based wavetable synth generator. The part I actually wanted to own is the preferential Bayesian optimization — a Gaussian process with a Laplace approximation and a Thurstone-Mosteller likelihood, searching a PCA latent fit over a wavetable corpus. I looked hard at replacing the PCA latent with a VAE and decided against it; the variance a nonlinear latent would buy wasn't defensible given what the corpus actually needed.

**Asset-conditioned sentiment (Wat.AI)** — *NLP, distant supervision*
Most sentiment models score a headline. This one scores a headline against a specific asset, since "copper and gold prices rise as the dollar weakens" is not the same sentence for copper, gold, and the dollar. Labels come from what markets actually did afterward rather than hand annotation, which is the only way to get this to scale.

---

### Reach

If you're working on anything at the intersection of markets, physics-flavored ML, or protocol design, I'd like to hear about it.

<div align="center">

[![Email](https://img.shields.io/badge/email-your.email%40example.com-1E3A8A?style=for-the-badge&logo=gmail&logoColor=E2E8F0)](mailto:your.email@example.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-your--handle-1E3A8A?style=for-the-badge&logo=linkedin&logoColor=E2E8F0)](https://linkedin.com/in/your-handle)

</div>

<div align="center">
<sub>swap the email, LinkedIn handle, and GitHub username in the stats block below for your own</sub>
</div>

<div align="center">

![](https://github-readme-stats.vercel.app/api?username=ryousuf569&theme=dark&hide_border=true&bg_color=0F172A&title_color=94A3B8&text_color=CBD5E1&icon_color=60A5FA)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=ryousuf569&theme=dark&hide_border=true&bg_color=0F172A&title_color=94A3B8&text_color=CBD5E1&icon_color=60A5FA&layout=compact)

</div>

# Hi there, I'm Christian Bianchi 👋

**Visiting Researcher @ University of Tübingen | R&D Scientist @ ItalAI | M.Sc. Computer Science @ Sapienza University of Rome**

I work on robot learning and vision-language-action (VLA) models, with a focus on how robot policies can adapt to new tasks and recombine skills they have already learned, without retraining from scratch.

Currently, I am a visiting researcher in the **Autonomous Learning Group at the University of Tübingen**, doing my M.Sc. thesis on reinforcement learning for humanoid control with Georg Martius and Fabio Galasso (Erasmus+). I am also an R&D Scientist at **ItalAI**, working with **PINlab** at Sapienza on weight-space adaptation for VLA policies.

🌐 **Website:** [fascetta.github.io](https://fascetta.github.io) · 📄 [CV](https://fascetta.github.io/Christian_Bianchi_CV.pdf) · 🎓 [Google Scholar](https://scholar.google.com/citations?user=RYcjd98AAAAJ)

---

### 🔬 Research Highlights

#### **WIZARD: Robotic Policy Adaptation via Weight-Space Meta-Learning**
* **Status:** *CoRL 2026 Workshop · poster at ICVSS 2026*
* **Focus:** Weight-space meta-learning & embodied AI.
* **Contribution:** A meta-network that generates task-specific LoRA adapters for a frozen VLA policy from a language instruction and one unlabeled demonstration, with no test-time optimization. Raised held-out LIBERO-Spatial success from 19% (fine-tuned π0.5) to 40%, and from 17% to 37% on a real Franka Emika Panda.
* **Paper:** [arXiv:2606.07217](https://arxiv.org/abs/2606.07217) · **Code:** [WIZARD](https://github.com/Fascetta/WIZARD)

#### **SPELL: Long-Horizon Compositional Manipulation via Meta-Network Dynamic Adaptation**
* **Status:** *Preprint*
* **Focus:** Long-horizon manipulation & skill composition.
* **Contribution:** Generates skill-level adapters and switches between them during execution, adapting to unseen task compositions without target-task action labels. Doubled held-out LIBERO-10 success (0.25 → 0.50), reached 4.58 on CALVIN ABC→D, and improved real-Franka success from 0.31 to 0.56.

#### **ResQu: Quaternion Wavelet-Conditioned Diffusion for Image Super-Resolution**
* **Status:** *IJCNN 2025 (Oral Presentation)*
* **Focus:** Hypercomplex deep learning & generative models.
* **Contribution:** Conditions latent diffusion on quaternion wavelet embeddings injected at different denoising stages. Improved PSNR on DRealSR from 27.87 to 29.69 over the strongest diffusion baseline.
* **Paper:** [arXiv:2505.00334](https://arxiv.org/abs/2505.00334) · **Code:** [ResQu](https://github.com/Fascetta/ResQu)

#### **Motion Unlearning for Safer Diffusion-Based Generation**
* **Status:** *Academic Project*
* **Focus:** AI safety & machine unlearning.
* **Contribution:** Adapted three unlearning methods (ESD, LoRA, UCE) to a text-conditioned 3D motion diffusion model (SALAD), evaluating targeted forgetting of restricted concepts against preservation of unrelated motions.
* **Code:** [Motion-Unlearning-Evaluation](https://github.com/Fascetta/Motion-Unlearning-Evaluation)

#### **Calibrating Neural Networks via Radius Regularization**
* **Status:** *B.Sc. Thesis*
* **Focus:** Reliability, geometric deep learning & confidence calibration.
* **Contribution:** A hyperbolic, radius-based calibration objective that reduced Expected Calibration Error on CIFAR-100 by **57%** at unchanged accuracy.
* **Code:** [Radius-Regularization](https://github.com/Fascetta/Radius-Regularization)

---

### 🏅 Selected Honors & Service
* Selected participant, **Machine Learning Summer School (MLSS) 2026**, Tübingen
* Selected participant & poster presenter, **ICVSS 2026**, Sicily
* Reviewer, **IJCNN 2027** · Student volunteer, **SIGGRAPH 2025** and **IJCNN 2025**
* **HCL Software Maverick Award** (one of four recipients worldwide, 2024)

---

### 🛠 Engineering & Industry Experience

**R&D Scientist @ ItalAI** (June 2025 – Present)
* Led WIZARD and SPELL as first author, from problem formulation to real-robot evaluation, coordinating experiments across two Ph.D. researchers and one M.Sc. researcher.
* Built a hardware-embodied **audio-spatial interaction engine** (real-time speaker diarization and directional tracking) and a **persistent per-persona memory** for long-horizon conversations with a social robot.

**Generative AI Engineer @ F1 Consulting Services** (March 2025 – June 2025)
* Contributed to the **Aeroporti di Roma Virtual Assistant**, a multi-agent Amazon Bedrock assistant on WhatsApp and the web, building its real-time voice pipeline (Whisper on SageMaker, Polly).
* Optimized LLM retrieval latency by **75%** with semantic caching and embedding pruning.

**Software Engineer @ HCL Software** (May 2022 – March 2025, *full-time alongside my B.Sc.*)
* 🏆 **Maverick Award**, one of four recipients worldwide.
* Built dense-vector retrieval infrastructure and an internal **RAG system** that reduced debugging and triage time by **40%**.

---

### 💻 Tech Stack

**Languages**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)

**AI & ML Frameworks**
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![JAX](https://img.shields.io/badge/-JAX-A8B9CC?style=flat&logo=google&logoColor=white)
![Hugging Face](https://img.shields.io/badge/-Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![CUDA](https://img.shields.io/badge/-CUDA-76B900?style=flat&logo=nvidia&logoColor=white)

**Robotics & Simulation**
![MuJoCo](https://img.shields.io/badge/-MuJoCo-1E3A5F?style=flat)
![Isaac Sim](https://img.shields.io/badge/-Isaac_Sim-76B900?style=flat&logo=nvidia&logoColor=white)
![LIBERO](https://img.shields.io/badge/-LIBERO-4B5563?style=flat)
![CALVIN](https://img.shields.io/badge/-CALVIN-4B5563?style=flat)

**Cloud, HPC & DevOps**
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Slurm](https://img.shields.io/badge/-Slurm-4B5563?style=flat)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

### 📫 Let's Connect
I am open to collaborations in robot learning and embodied AI, and to PhD opportunities.

* **Website:** [fascetta.github.io](https://fascetta.github.io)
* **LinkedIn:** [linkedin.com/in/christianbianchiit](https://www.linkedin.com/in/christianbianchiit/)
* **Email:** ch.bianchi02 [at] gmail [dot] com

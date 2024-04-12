# PROJECT PROPOSAL

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![UPRJ_CI](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml) [![Caravel Build](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml)


## mel-frequency cepstrum asic

I am an undergraduate student and learning digital signal processing in my courses right now. I would love to design filters and use it to accelerate the dsp process in kws. I will be designing the mel-frequency cepstrum (MFC) and will be using rapidgpt for that. I searched for designing KWS algorithms and accelerator types and i think since this contest is for using generative ai as much as we can when designing, I will try to implement as many mel-frequency cepstrum elements as i can in verilog using rapidgpt. I will start by designing a Hamming window and keep adding new ip's to the accelerator(Logarithm,Discrete Cosine Transform etc...). After testing them all with verilog i will integrate the ip's to a LiteX SoC with ai-written wishbone bus or i will use csr's to reach the modules. After tests in fpgas are done i will integrate the project to caravel user project and use openlane to get the gds and i will definitely use rapidgpt in the learning process. 

If it is allowed i want to document my work and publish my experience in my blog. I recently opened my blog and it will be my first post. I will publish all my work in English, Turkish and Azerbaijani. Also i would love to upload a video tutorial.

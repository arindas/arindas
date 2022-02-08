### Hi there 👋

<details>
<summary>Resume</summary>
<br>

Arindam Das.
  
## Description
Specializes in distributed systems, deep learning inference and AI SaaS at scale.

Generalist capable of architecting and implementing cloud-native software services, for any domain. I primarily have 
experience in medical imaging, real-time document processing and business inventory management.

## Technical Skills
C, C++, Java, Golang, Rust, Python, Django, Tensorflow, Pytorch, Javascript, React, SQL, Postgres, Git, Docker, DevOps, MLOps, Linux, AWS, GCP, Firebase

## Soft Skills
Agile Software Development, Technical Teaching

## Experience
- Full Stack Engineer, Medical Imaging AI Services, Claritas Healthtech Pte. Ltd. (06/2020 - Present)
  
  Responsibilities:
  - Developing distributed deep learning inference services and corresponding client web applications 
  - Deploying and maintaining said applications on the Google Cloud Platform
  
  Projects:
  - File storage solution built on top of Google Cloud Storage with additional support for bucket creation and user 
  access authorization at the level of buckets. Implemented as a golang web service with the golang google-cloud-sdk,
  along with a frontend React client application. Authentication: Firebase Auth. DB: Google Cloud Firestore.<br>
  This solution enabled us to receive sensitive data from different medical institutions without providing access to  
  our GCP infrastructure.
  - Distributed deep-learning based diagnosis on medical images for a variety of diseases. Implemented as a suite of 
  microservices, in golang and python. We use golang for managing data and python for inference. The services talk 
  to each other using Google Cloud PubSub.<br>
  Authentication: Firebase Auth. DB: Google cloud firestore.<br>
  We were able to reduce turnaround time for a new disease prediction service deployment by 10x, along
  with improved audit record keeping of all predicted reports.

<br>

- Solution Architect, DeepWrex Technologies (04/2018 - 06/2020)
  
  Responsibilities:
  - Architect cloud based solutions for machine learning software services.
  - Assist researchers in implementing deep learning research papers.
  - Iterating from research PoC to production.
  
  Projects:
  - A real-time named entity recognition system for medical reports. This was an in house, economic alternative to
  AWS Medical Comprehend, which didn't exist at the time. This was implemented as a suite of C++ microservices, with
  intermediate data storage on AWS S3. These services talked to each other with Kafka (using rdkafka)
  - A scalable black and white image colourization system, deployed using "Pytorch Serve" and FastAPI on AWS. We 
  implemented the instance aware image colourization paper.

<br>

- Satellite Onboard Computer RTOS Research Student, KIITSAT
  - Developed a shell capable of spawning programs and organizing pipes
  - Developed a minimal kernel for armv6 (on Raspberry Pi 3) with basic memory management and TTL based I/O Support
  - Trained fellow team members on OS concepts

<br>

- VR 3d Game Development Instructor, CampK12 (03/2020 - 06/2020)
  
  Responsibilities:
  - Teaching K12 students about game development which entailed:
    - Problem solving skills
    - Basic Programming using Javascript
    - Trigonometry
    - _Patience and Perseverance_
  
  Some projects that I taught to students can be found at https://github.com/arindas-campk12

## Education
- B.Tech in Computer Science and Engineering<br> 
  KIIT University, 06/2017 - 06/2021<br>
  CGPA: 9.44<br>
  SGPA 8th Semester: 9.69<br>

- ISC, Higher Secondary<br>
  Don Bosco Bandel, 2005 - 2017<br>


## Side Projects
- [sangfroid](https://github.com/arindas/sangfroid): A load-balanced thread pool implemented in Rust using only the 
  standard library. Worker threads are managed with binary heap and are prioritized by the number of pending jobs.


- [quartz](https://github.com/arindas/quartz): A shared memory parallelized ray tracer using OpenMP.
  _Speciality:_ Non recursive. Traditionally ray tracers are tail recursive. Image formats supported: PPM


- [mac-on-linux-with-qemu](https://github.com/arindas/mac-on-linux-with-qemu): Runs MacOS on Linux with the QEMU
  KVM Hypervisor with some python utility scripts for downloading the disk images and shell scripts for starting QEMU.


- [riakv](https://github.com/arindas/riakv): An append-only key-value store, with checksum based record validation.
  Originally inspired by the Rust In Action Book by Tim McNamara with enhancements for reading from in-memory buffers,
  serializing and storing the index to disk, further application of DRY principles and comprehensive tests.

</details>

[![arindas' github stats](https://github-readme-stats-chi-tan.vercel.app/api?username=arindas&include_all_commits=true&show_icons=true&hide_title=true&hide_border=true&theme=dark)](https://github.com/arindas)

[![Top Langs](https://github-readme-stats-chi-tan.vercel.app/api/top-langs/?username=arindas&langs_count=10&layout=compact&theme=dark&hide_border=true)](https://github.com/arindas)


<!--
**arindas/arindas** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:
-->
<!--
- 🔭 I’m currently working on a privacy preserving secure medical document store.
-->
- 🌱 I’m currently learning concurrent decomposition of problems, distributed systems, Rust and the Kubernetes ecosystem.
- 👯 I’m looking to collaborate on projects involving:
  - High Performance requirements
  - Deep Learning SaaS solutions.
- 🤔 I’m curious about:
  - The blockchain ecosystem
  - Quantum Computing
  - AR and VR development
- 💬 Ask me about algorithms, system design, backend engineering and deep learning inference pipelines.
- 📫 How to reach me: [twitter](https://twitter.com/arind_das), [linkedin](https://www.linkedin.com/in/arind-das), [gitlab](https://gitlab.com/dasarindam.mails)
- 😄 Pronouns: He/Him
- ⚡ Fun fact: The Apollo 11 mission computer required only 4KB of ram. (2048 words to be exact. [\[1\]](https://en.wikipedia.org/wiki/Apollo_Guidance_Computer))


### Recent projects :computer:
[![Readme Card](https://github-readme-stats-chi-tan.vercel.app/api/pin/?username=arindas&repo=bheap&theme=dark&hide_border=true)](https://github.com/arindas/bheap)

[![Readme Card](https://github-readme-stats-chi-tan.vercel.app/api/pin/?username=arindas&repo=riakv&theme=dark&hide_border=true)](https://github.com/arindas/riakv)

[![Readme Card](https://github-readme-stats-chi-tan.vercel.app/api/pin/?username=arindas&repo=batnotify&theme=dark&hide_border=true)](https://github.com/arindas/batnotify)

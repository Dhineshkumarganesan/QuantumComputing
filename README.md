# QuantumComputing
A blog that talks about complexities and benefits of Quantum Computing



![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/42dd28d5-b7ec-4cbc-aec7-98e082dbbf46)


![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/162dfad8-81e7-4097-9698-09ef3e9bc9c7)


![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/237e23ea-7cab-4523-9385-57a88acf4f39)


![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/4e9a8bb2-8b4a-42cb-905a-82303cce4232)



![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/0cfba00e-c125-4657-961b-5ca894286fff)





![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/09547bb6-5c37-4a82-a348-71ebd77c185a)


![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/94bd1ebb-ee22-4349-aa77-baa080e85453)


![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/17efd5da-2b23-41ff-a5fd-0bc6b6cdf8cd)

![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/d7ddb8b1-0a89-48bd-ab8c-455778acd2ce)


</br></br>
Classical and Quantum

![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/b8a1df11-5ea0-4110-abc6-13c094b1fc4a)

</br></br>

Decompose / Evaluate / Reconstruct

![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/43a15e41-0f9f-4d78-9657-7ff074d360a5)


</br></br>
**Why are you interested in quantum computing?**

</br></br>
Quantum computing will offer the developing world of artificial intelligence more computing power, which in turn will lead to more robust AI systems that can better understand us, "think for themselves," offer more efficient machine learning and better solve small and large problems.

</br>
Quantum computers have the potential to revolutionize computation by making certain types of classically intractable problems solvable. While no quantum computer is yet sophisticated enough to carry out calculations that a classical computer can't, great progress is under way

</br></br>
**Why is quantum computing the future?**

</br></br>
Image result for why quantum computing
On the other hand, Quantum computing uses qubits that can be both 1 and 0 simultaneously. This allows many calculations to be done simultaneously, so quantum computing is powerful. It's also why it's seen as the future of artificial intelligence and data science

</br></br>
**Why is quantum computing so powerful?**

</br></br>
The predominant explanation of a quantum computer's advantage over a classical computer is that we can prepare quantum bits in a superposition of an exponential number of states. Then, the quantum algorithm computes all possible inputs at the same time.

**Hadamard Gate**

The Hadamard gate is a fundamental quantum gate used in quantum computing and quantum information processing. It is a one-qubit gate that plays a crucial role in creating quantum superposition. The Hadamard gate is often denoted by the letter 
�
H.

The Hadamard gate acts on a single qubit and transforms its state according to the following matrix:

1 & 1 \\
1 & -1
\end{bmatrix}\]
If \(|\psi\rangle\) is the state of a qubit, then the application of the Hadamard gate (\(H\)) is given by:
\[H|\psi\rangle = \frac{1}{\sqrt{2}}(|0\rangle + |1\rangle)\]
Here, \(|0\rangle\) and \(|1\rangle\) are the basis states of a qubit (representing classical bits 0 and 1), and the Hadamard gate transforms them into a superposition of both states with equal probability amplitudes.
The Hadamard gate is particularly important in quantum algorithms like quantum Fourier transform and in creating superposition states, which are essential for quantum parallelism. It is a building block for many quantum circuits and is widely used in quantum algorithms such as Shor's algorithm and Grover's algorithm.
In summary, the Hadamard gate is a fundamental quantum gate that introduces quantum superposition by transforming basis states into equal superposition states, contributing to the unique computational capabilities of quantum computers.

Let's break down the implementation of the Hadamard gate in quantum computing with a simple example and a pictorial diagram.


![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/1afebd8f-af13-49c8-9cfc-e95a1195fcc4)

This operation puts the qubit into an equal superposition of ![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/57ca5509-d459-4dc8-b367-ed8b1b42bcbf)

**Pictorial Diagram:**
Let's represent the quantum states and operations graphically:

![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/4b708fa3-3b2b-45b5-92c1-059b77965e8f)


Simulation:
In a quantum circuit, the Hadamard gate is often represented as a specific gate operation. Here's how you might represent the Hadamard gate in a quantum circuit using a simulation:

![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/4b8a9951-31e0-4960-94a6-d0d729ab06cb)

This circuit shows a single qubit (q_0) with a Hadamard gate (H) applied to it.
![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/e3432bb8-c1a5-4349-8a3e-58616ad95749)

![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/6babc679-660c-446b-b682-2e605f4fc346)

**Quantum Superposition**

Quantum superposition is a fundamental principle in quantum mechanics that allows quantum systems to exist in multiple states simultaneously. In classical physics, objects are typically in one particular state at any given time, but in the quantum world, particles like electrons, photons, or atoms can exist in a combination or superposition of multiple states at once.

The concept of superposition is best illustrated by the famous thought experiment known as Schrödinger's cat. In this scenario, a cat inside a sealed box is both alive and dead at the same time, as the state of the cat is entangled with the state of a quantum particle, like an atom undergoing radioactive decay. Only when the box is opened and an observation is made does the system "collapse" into one of the possible states—either the cat is alive or dead.

Mathematically, superposition is represented using the wave function in quantum mechanics. The wave function describes the probability amplitude of finding a particle in a particular state. When a system is in a superposition of states, the wave function includes terms for each possible state, and the probabilities are determined by the squared magnitudes of these terms.

Superposition is not limited to just two states; a quantum system can exist in a superposition of many states simultaneously. This property is harnessed in quantum computers, where qubits (quantum bits) can represent both 0 and 1 at the same time, allowing for parallel processing and potential computational advantages over classical computers in certain tasks.

It's important to note that superposition is a key feature of quantum mechanics and is distinct from classical concepts, challenging our classical intuition about the nature of physical reality.


**Quantum Entanglement**


Quantum entanglement is a phenomenon in quantum mechanics where two or more particles become correlated in such a way that the state of one particle cannot be described independently of the state of the others, regardless of the distance between them. This means that the quantum state of one particle instantaneously influences the state of another, even if they are separated by large distances.

The entanglement of particles occurs when they are created or interact in such a way that their quantum properties, such as spin, polarization, or other observable characteristics, become intertwined. Once entangled, the state of one particle is directly related to the state of the other, and changes to the state of one particle will be reflected in the other particle instantaneously.

Albert Einstein famously referred to this phenomenon as "spooky action at a distance" because it challenges our classical intuition about how information and influences should propagate through space. Despite the apparent faster-than-light influence, quantum entanglement does not allow for the transmission of classical information at speeds greater than the speed of light, as it cannot be used for faster-than-light communication.

Quantum entanglement plays a crucial role in various quantum technologies and has been the subject of many experiments and studies in quantum physics. It is a fundamental aspect of the non-local and probabilistic nature of quantum mechanics.

**Quantum Inspire**

Quantum PE Phase Estimation

**Quantum Cloud Vendors**

IBM OpenQASM Qiskit></br>
https://docs.quantum.ibm.com/ </br>
Google cirq</br>
https://quantumai.google/cirq </br>
Azure Quantum q#</br>
https://azure.microsoft.com/en-us/products/quantum </br>
AWS Braket</br>
https://aws.amazon.com/de/braket/ </br>
Atos QLM</br>
https://atos.net/en/solutions/quantum-learning-machine#qlm</br></br></br>


QUANTUM SERVERLESS</br>
</br>
https://github.com/Qiskit-Extensions/quantum-serverless/tree/main</br>

QISKIT</br>
</br>
https://github.com/Qiskit/qiskit</br>
https://github.com/Qiskit/qiskit-ibm-runtime</br>
</br>

**Orchestration by K8S**

![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/7772658b-1de3-47d1-817b-578509f10e06)


**Orchestration by K8S using Quantum**

![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/8a12cf8b-9956-4370-afb4-989772913aa9)



**Ray: the Next Generation Compute Runtime for ML Applications**

![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/d9d076f8-da3b-4418-ba1e-d18410552c57)


https://aws.amazon.com/de/blogs/big-data/introducing-aws-glue-for-ray-scaling-your-data-integration-workloads-using-python/

https://www.infoq.com/presentations/ray-ml/

May 1, 2023
Use Knative When You Can, and Kubernetes When You Must - David Hadas & Michael Maximilien, IBM
https://www.youtube.com/watch?v=0IwysONytqc

May 1, 2023
Cloud-Native Quantum: Running Quantum Serverless Workloads on Kubernetes - Schweigert & Maximilien</br>
https://www.youtube.com/watch?v=kvD-Y70DOno

Oct 12, 2023  Ray Summit 2023
Ray, Knative, and Running Serverless Workloads in the Cloud - Schweigert & Maximilien </br>
https://www.youtube.com/watch?v=zYzyR36g108

https://drive.google.com/file/d/1WiC02hZQhtgA25FD-Kp0CY88167oW9lA/view
https://docs.ray.io/en/latest/

Nov 22, 2023
Supercharge Your AI Platform with KubeRay: Ray + Kubernetes - Archit Kulkarni & Winston Chiang
https://www.youtube.com/watch?v=DgfJR6wR4BQ

Dec 4, 2023
Accelerate Your GenAI Model Inference with Ray and Kubernetes - Richard Liu, Google Cloud
https://www.youtube.com/watch?v=FZ9XML4KaiY

**SETUP RAY ON TO KUBERNETES CLUSTER**
https://docs.ray.io/en/latest/cluster/kubernetes/index.html

![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/f45a4227-995c-4aa8-bb37-94ccc12b8d8c)


**Run your first Quantum Serverless code on Ray Cluster**

https://github.com/Qiskit-Extensions/quantum-serverless/blob/main/docs/getting_started/basic/01_running_program.ipynb

**RAY Cluster Components** </br>


![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/86f2811d-ae3a-4a7f-9277-88421ebab06b)

**How it looks within K8S**  </br>

![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/af159c83-1446-4a0b-a64c-0de145ccb592)


**RAY**

![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/41a4c250-80a8-4117-8bfb-c133afa7a22a)


**Component Comparison between Ray and K-native**
![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/80e2e649-1170-49e2-9624-75f84b33bd9c)


**Cons of Knative**

![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/c44c7892-335a-4bde-a8c3-66a8959ecbea)


**Pros of Ray**

![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/4db0b4e9-508b-4c06-a93d-2ddd28f6c4c3)


**Cons of Ray**

![image](https://github.com/Dhineshkumarganesan/QuantumComputing/assets/59999899/95b8d40e-bd30-4de1-a6ba-e6b764669083)


Ray is an open-source unified framework for scaling AI and Python applications like machine learning. It provides the compute layer for parallel processing so that you don’t need to be a distributed systems expert. Ray minimizes the complexity of running your distributed individual and end-to-end machine learning workflows with these components:

Scalable libraries for common machine learning tasks such as data preprocessing, distributed training, hyperparameter tuning, reinforcement learning, and model serving.

Pythonic distributed computing primitives for parallelizing and scaling Python applications.

Integrations and utilities for integrating and deploying a Ray cluster with existing tools and infrastructure such as Kubernetes, AWS, GCP, and Azure.

For data scientists and machine learning practitioners, Ray lets you scale jobs without needing infrastructure expertise:

Easily parallelize and distribute ML workloads across multiple nodes and GPUs.

Leverage the ML ecosystem with native and extensible integrations.

For ML platform builders and ML engineers, Ray:

Provides compute abstractions for creating a scalable and robust ML platform.

Provides a unified ML API that simplifies onboarding and integration with the broader ML ecosystem.

Reduces friction between development and production by enabling the same Python code to scale seamlessly from a laptop to a large cluster.

For distributed systems engineers, Ray automatically handles key processes:

Orchestration–Managing the various components of a distributed system.

Scheduling–Coordinating when and where tasks are executed.

Fault tolerance–Ensuring tasks complete regardless of inevitable points of failure.

Auto-scaling–Adjusting the number of resources allocated to dynamic demand.

What you can do with Ray
These are some common ML workloads that individuals, organizations, and companies leverage Ray to build their AI applications:

Batch inference on CPUs and GPUs

Model serving

Distributed training of large models

Parallel hyperparameter tuning experiments

Reinforcement learning

ML platform

Ray framework
../_images/map-of-ray.svg

Stack of Ray libraries - unified toolkit for ML workloads.

Ray’s unified compute framework consists of three layers:

Ray AI Libraries–An open-source, Python, domain-specific set of libraries that equip ML engineers, data scientists, and researchers with a scalable and unified toolkit for ML applications.

Ray Core–An open-source, Python, general purpose, distributed computing library that enables ML engineers and Python developers to scale Python applications and accelerate machine learning workloads.

Ray Clusters–A set of worker nodes connected to a common Ray head node. Ray clusters can be fixed-size, or they can autoscale up and down according to the resources requested by applications running on the cluster.

Scale machine learning workloads

Build ML applications with a toolkit of libraries for distributed data processing, model training, tuning, reinforcement learning, model serving, and more.


Build distributed applications

Build and run distributed applications with a simple and flexible API. Parallelize single machine code with little to zero code changes.


Deploy large-scale workloads

Deploy workloads on AWS, GCP, Azure or on premise. Use Ray cluster managers to run Ray on existing Kubernetes, YARN, or Slurm clusters.


Each of Ray’s five native libraries distributes a specific ML task:

Data: Scalable, framework-agnostic data loading and transformation across training, tuning, and prediction.

Train: Distributed multi-node and multi-core model training with fault tolerance that integrates with popular training libraries.

Tune: Scalable hyperparameter tuning to optimize model performance.

Serve: Scalable and programmable serving to deploy models for online inference, with optional microbatching to improve performance.

RLlib: Scalable distributed reinforcement learning workloads.

Ray’s libraries are for both data scientists and ML engineers alike. For data scientists, these libraries can be used to scale individual workloads, and also end-to-end ML applications. For ML Engineers, these libraries provides scalable platform abstractions that can be used to easily onboard and integrate tooling from the broader ML ecosystem.

For custom applications, the Ray Core library enables Python developers to easily build scalable, distributed systems that can run on a laptop, cluster, cloud, or Kubernetes. It’s the foundation that Ray AI libraries and third-party integrations (Ray ecosystem) are built on.

Ray runs on any machine, cluster, cloud provider, and Kubernetes, and features a growing ecosystem of community integrations.

**Running Serverless Workloads on k8s using knative**

https://www.cloudthat.com/resources/blog/run-serverless-workloads-on-kubernetes-using-knative


**Quantum Presentations** </br>

https://drive.google.com/file/d/1WiC02hZQhtgA25FD-Kp0CY88167oW9lA/view

https://teratec.eu/library/seminaires/2022/TQCI/Integralite_Presentation_EDF_TQCI_6.pdf



**Paul Schweigert Talks**

https://psschwei.com/speaking/

Middleware for Quantum: Enabling Advanced Quantum Computing Workflows, CloudNativeCon/KubeCon North America (with David Garcia), Chicago: Nov 2023 [abstract] [recording -https://www.youtube.com/watch?v=XC1jJjBWAXE]

Making Kubernetes Quantum-Safe: what can we do to protect ourselves now? CloudNativeCon/KubeCon North America (with Dr. Max), Chicago: Nov 2023 [abstract][recording - https://www.youtube.com/watch?v=fJAIvuNsv-g]

Surveying the Open Quantum Landscape: Open Source Tools for Quantum Computing, All Things Open (with Iskandar Sitdikov), Raleigh: Oct 2023 [abstract]

Ray, Knative, and Running Serverless Workloads in the Cloud, Ray Summit, San Francisco: Sept 2023 [abstract] [recording -https://www.youtube.com/watch?v=zYzyR36g108]

Quantum Meets Kubernetes: Deploying Serverless Quantum Workloads on OpenShift, IBM TechXchange (with Dr. Max), Las Vegas: Sept 2023 [abstract]

Adopting Quantum-Safe Cryptography: Developing with the OpenSSL Stack, IBM TechXchange (with Dr. Max), Las Vegas: Sept 2023 [abstract]

A Beginner’s Guide for Quantum Circuits with the Qiskit SDK, IBM TechXchange (with Dr. Max), Las Vegas: Sept 2023 [abstract]

Future-Proof your Data: Quantum-Safe Encryption in the Quantum Computing Age, IBM TechXchange (with Dr. Max), Las Vegas: Sept 2023 [abstract]

Quantum in the Cloud: Running Quantum Workloads on Kubernetes, Open Source Summit North America (with Dr. Max), Vancouver: May 2023 [abstract] [recording -https://www.youtube.com/watch?v=w1h_dsQdtxk]

Knative’s Road Ahead: A Project Update, [CloudNativeCon/KubeCon Europe (with Roland Huss, Naina Singh, David Protasowski, and Mauricio Salatino), Amsterdam: Apr 2023 [abstract] [recording - https://www.youtube.com/watch?v=kjMjOJqg80A]

Cloud-Native Quantum: Running Quantum Serverless Workloads on Kubernetes], CloudNativeCon/KubeCon Europe (with Dr. Max), Amsterdam: Apr 2023 [abstract] [recording -https://www.youtube.com/watch?v=kvD-Y70DOno]

ContribFest - Knative: Level Up Knative Eventing, and Yourself!, CloudNativeCon/KubeCon North America (with Evan Anderson), Detroit: Oct 2022 [abstract]

Novice to Maintainer: Reflections on One Year of Contributing to Knative, KnativeCon North America, Detroit: Oct 2022 [abstract] [recording -https://www.youtube.com/watch?v=pDEXLSoPGYg]

How Fast is FaaS? Reducing Cold Start Times in Knative, KnativeCon Europe (with Carlos Santana), Valencia: May 2022 [abstract] [recording -https://www.youtube.com/watch?v=fv-TkMOM0bk]


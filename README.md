# mol-detective
We propose a pioneering latent sequence diffusion model, ‘MolDetective’, a novel algorithm that outputs a protein-targeted small molecule binder given only a protein sequence input. 
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

The exploration of potential drug molecules encompasses an estimated 1023 to 1060 unique structures, representing a vast chemical space. The problem is, that compound libraries that exist today consist of just millions of compounds, leaving a mostly unexplored domain. As such, bridging this gap between a vast total chemical space, and the relatively small subset that has been investigated, remains a central challenge in the field of drug discovery.
Virtual screening methods are commonly used in identifying small molecules by using information about existing molecules and their interactions with proteins. However, this method can often lead to the discovery of molecules that are similar to those already known, diminishing the uniqueness of the findings. Additionally, this approach depends on large databases of known small molecules, which can be a limiting factor for targets that do not have many known interacting molecules. De novo design methods aim to generate new molecules by applying theoretical principles and knowledge of molecular structures. Advances in deep learning, including generative adversarial networks and reinforcement learning, have improved these methods. Nevertheless, their effectiveness can be limited by the requirement for comprehensive structural data or specialized libraries tailored to specific target proteins.
Incorporating structural data, such as 3D protein structures, into drug discovery can be complex. Obtaining these structures is often resource-intensive, and for many proteins, the information is still unknown. Moreover, predicting protein structures computationally can be unreliable, especially for proteins with fewer known contacts within their chain or without similar structures for reference. Models like CProMG and AlphaDrug are notable for their capacity to create new, drug-like molecules, yet they depend heavily on detailed structural data and require significant computational work. These demands can limit how much these models can scale and the range of chemical space they are able to investigate.
These issues suggest a need for a methodological shift towards a more direct, sequence-based strategy in drug discovery. The focus is not on simplifying the process, but rather to enable the exploration of areas of the chemical space that were previously hard to reach and to take advantage of the rapid progress in protein sequencing. Models such as DeepTarget and others using RNN-based machine translation have already begun to adopt this approach.
Herein, we propose a pioneering latent sequence diffusion model, ‘MolDetective’, a novel algorithm that outputs a protein-targeted small molecule binder given only a protein sequence input. 

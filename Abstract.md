# A-survey-of-PPNNs-based-on-HE-MPC-and-FE
Privacy-preserving neural networks (PPNNs) denote architectures and protocols that
enable the training and inference of deep learning models while guaranteeing data confi-
dentiality through cryptographic primitives such as homomorphic encryption (HE), secure
multi-party computation (MPC—e.g., Secret secret sharing  (SSS), functional secret sharing
(FSS), garbled circuits (GC), and oblivious transfer (OT)), and functional encryption (FE).
In the current landscape—where sensitive applications in healthcare, finance, telecommuni-
cations, and the Internet of Things require both high utility and strong data protection—the
effective integration of these primitives into deep learning pipelines has become a central
challenge for making PPNNs practical at scale.
In this survey, we present a systematic survey and a critical analysis of existing ap-
proaches. We review the state of the art in HE, FE, and MPC; examine how layers, activa-
tion functions, and optimization protocols can be adapted to be HE-friendly, MPC-friendly,
and FE-friendly; and compare the trade-offs in accuracy, latency, throughput, and security
guarantees. Our review covers an extensive corpus of publications across the three domains
(precise article counts for HE, FE, and MPC can be provided upon request) and synthesizes
concrete techniques that facilitate the cryptographic integration into neural architectures.
Finally, we identify and discuss the principal open challenges, including computational and
communication scalability, utility/privacy trade-offs, compatibility with modern large-scale
architectures, robustness to attacks, and the need for standardized benchmarks, and we
propose research directions and practical recommendations to accelerate the adoption of
PPNNs.

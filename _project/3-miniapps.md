---
title: "Performance Modeling and Analyzing on HPC Mini-applications"
collection: HPC
type: "HPC Student Team Weekly Assignment"
permalink: /project/3-miniapps
venue: "Center for High Performance Computing, SJTU"
date: 2019-02-01
location: "Shanghai, China"
---
I analyzed the performance of CCS-QCD in detail, and optimized the program on our test cluster.
![main](/images/ccs-qcd/qcd.png "CCS QCD, a quantum chromodynamics program")


- I compiled, executed and profiled 10+ HPC mini-applications including CCS-QCD, modylas-mini, miniVite, miniFE, etc.(most from ECP Proxy Applications suite)
- I choosed CCS-QCD, and analyzed its performance characteristics in detail by identifying the math kernel, hotspot and bottleneck. (It is a BiCGstab kernel)
- I modelled their performance under Roofline Model, ECM Model, etc.
![main](/images/ccs-qcd/roofline.png "Roofline Model")
- I optimized them on specific platform by changing process affinity and by vectorization.
![main](/images/ccs-qcd/opt.png "Optimization")

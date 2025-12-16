# [论文标题] Identifying DDoS Attacks in-Kernel via eBPFXDP and Knowledge Distillation

## 📄 Abstract (摘要)
Identifying Distributed Denial of Service (DDoS) 
plays a vital role in network security as DDoS attacks have grown 
rapidly and become one of the most serious threats to network 
security. However, most existing DDoS identification methods run   
in user space on hardware servers, which increases the traffic load 
and delays the response. In this work, we propose a method for 
fast identification of DDoS attacks in the Linux kernel. This 
method uses the eXpress Data Path (XDP) as a hook to attach an 
extended Berkeley Packet Filter (eBPF) program to the device 
driver to process data packets at a very early stage and at high 
speed. Furthermore, to break through the computing/memory 
limitations of the devices and ensure the accuracy of DDoS attack 
identification, we use Knowledge Distillation (KD) techniques to 
transform the DDoS identification knowledge of a complex Multi
Layer Perceptron (MLP) into a simple Decision Tree (DT) model, 
and implement the DT model as an eBPF program. Experimental 
results show that the proposed method can quickly and accurately 
identify DDoS attacks. Compared to the baseline models, the 
Macro F1 Score has increased by 1.1%, reaching 97.6%. 
Keywords—DDoS attack, eBPF/XDP, in-kernel identification, 
knowledge distillation 

## 📥 Download (下载)
- **Paper**: [Click here to view the paper](./Identifying DDoS Attacks in-Kernel via eBPFXDP and Knowledge Distillation.pdf)
- **Poster**: [Click here to view the poster](./Conference_Poster.pdf)

## ⚠️ Note on Source Code (关于源代码的说明)
Due to [commercial reasons / patent restrictions / current maintenance], the source code is not publicly available at this moment. 
(由于商业/专利/维护原因，源代码暂不公开。)
If you are interested in the implementation details, feel free to contact the authors.

## 📝 Citation (引用)
(这里依然非常重要！把 BibTeX 格式放这里，方便别人引用你的文章)

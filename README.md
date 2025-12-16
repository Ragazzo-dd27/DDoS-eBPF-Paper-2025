<div align="center">

# Identifying DDoS Attacks in-Kernel via eBPF/XDP and Knowledge Distillation

**Kezhuo Chen, Ding Yuan, Dehong Qiu***

*School of Software Engineering, Huazhong University of Science and Technology*

</div>

---

## 📄 Abstract (摘要)

Identifying Distributed Denial of Service (DDoS) plays a vital role in network security as DDoS attacks have grown rapidly and become one of the most serious threats to network security. However, most existing DDoS identification methods run in user space on hardware servers, which increases the traffic load and delays the response. In this work, we propose a method for fast identification of DDoS attacks in the Linux kernel. This method uses the eXpress Data Path (XDP) as a hook to attach an extended Berkeley Packet Filter (eBPF) program to the device driver to process data packets at a very early stage and at high speed. Furthermore, to break through the computing/memory limitations of the devices and ensure the accuracy of DDoS attack identification, we use Knowledge Distillation (KD) techniques to transform the DDoS identification knowledge of a complex Multi Layer Perceptron (MLP) into a simple Decision Tree (DT) model, and implement the DT model as an eBPF program. Experimental results show that the proposed method can quickly and accurately identify DDoS attacks. Compared to the baseline models, the Macro F1 Score has increased by 1.1%, reaching 97.6%.

**Keywords**: DDoS attack, eBPF/XDP, in-kernel identification, knowledge distillation

## 📥 Resources (资源下载)

Here you can download the author's version of the paper and the conference poster.

- 📜 **Paper PDF**: [Identifying DDoS Attacks in-Kernel via eBPFXDP and Knowledge Distillation](./Identifying%20DDoS%20Attacks%20in-Kernel%20via%20eBPFXDP%20and%20Knowledge%20Distillation.pdf)
- 📊 **Conference Poster**: [Poster Presentation](./poster.pdf)

## ⚠️ Note on Source Code (关于源代码的说明)

The source code is currently not available for public release due to ongoing research and maintenance. 

If you are interested in the implementation details or the dataset preprocessing scripts for academic research, please feel free to contact the authors via email.

(由于后续研究计划及代码维护原因，源代码暂不公开。如果您对实现细节感兴趣，欢迎通过邮件联系作者。)

## 📝 Citation (引用)

If you find this work useful in your research, please consider citing:

```bibtex
@inproceedings{chen2025identifying,
  title={Identifying DDoS Attacks in-Kernel via eBPF/XDP and Knowledge Distillation},
  author={Chen, Kezhuo and Yuan, Ding and Qiu, Dehong},
  booktitle={Proceedings of the [Insert Conference Name Here]},
  year={2025},
  organization={IEEE}
}

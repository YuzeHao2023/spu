SPU
===

SPU (Secure Processing Unit) 由前端 **编辑器** 以及后端 **runtime** 环境组成。

前端编译器接受机器学习项目作为输入并将其转换为 **多方安全计算 (MPC) 的特定中间表征形式**。
经过一系列精细的代码优化后，程序将作为 MPC 协议在高性能后端环境运行。
使用 SPU，我们只需稍作修改就可以以保护隐私的方式运行不同框架的 ML 程序。

SPU 是 `SecretFlow <https://www.secretflow.org.cn/docs/secretflow/en/>`_ 项目的重要组成部分。
SPU 被设计为易于集成到其他分布式系统中，**建议使用** SecretFlow 编写 SPU 程序。

引用本文
--------

SPU 被 USENIX ATC'23 接受。请在 `此处 <https://www.usenix.org/conference/atc23/presentation/ma>`_ 查看论文。

.. code-block:: bibtex

   @inproceedings {288747,
      author = {Junming Ma and Yancheng Zheng and Jun Feng and Derun Zhao and Haoqi Wu and Wenjing Fang and Jin Tan and Chaofan Yu and Benyu Zhang and Lei Wang},
      title = {{SecretFlow-SPU}: A Performant and {User-Friendly} Framework for {Privacy-Preserving} Machine Learning},
      booktitle = {2023 USENIX Annual Technical Conference (USENIX ATC 23)},
      year = {2023},
      isbn = {978-1-939133-35-9},
      address = {Boston, MA},
      pages = {17--33},
      url = {https://www.usenix.org/conference/atc23/presentation/ma},
      publisher = {USENIX Association},
      month = jul,
   }

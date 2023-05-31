# Resources for phase acquisition
Here, we refer to the process of “calculating the wavefront phase from the amplitude/intensity measurement of the light field” as phase acquisition (PA). PA contains many techniques and algorithms, such as holography/interferometry, transfer of intensity equations, phase retrieval, wavefront sensing.
****
## Table of Contents:

- [Contributing](#contributing)
- [People and groups](#groups)
   - [Americas](#groups-Americas)
   - [Asia](#groups-Asia)
   - [Europe](#groups-Europe)
- [Companies](#companies)
- [Workshops](#workshops) (video or slides available)
- [Research papers](#Rpapers)  
   - [Phase acquisition](#PARpapers)  
     - [Holography/Interferometry](#HoloRpapers)  
     - [Transport of intensity equation](#TIERpapers)  
   - [Phase acquisition and deep learning](#DLRpapers)
- [Review / Tutorial papers](#papers)  
   - [Phase acquisition](#PApapers)   
   - [Phase acquisition and deep learning](#DLpapers)
- [Books](#BK)
- [Dissertations and Thesis](#DT)  


****
   
<a name="contributing"></a>
# Contributing

You are welcome to add or modify some content (categories or lists, etc.) via the ["fork and pull request"](https://docs.github.com/en/get-started/quickstart/contributing-to-projects).  

Please use the following guidelines:
- Edit the raw file with [Markdown Syntax](https://www.markdownguide.org/basic-syntax/).
- Avoid typos.
- Don't add what's already there.
- Uniform the format of new additions with that of the existing.
- Note the order of new additions (chronological or alphabetical).  

### Contributors  
This project exists thanks to all the people who contribute.  

<a href="https://github.com/kqwang/Phase_unwrapping_by_U-Net/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=kqwang/Phase_unwrapping_by_U-Net" />
</a>

 
****
<a name="groups"></a>
# People and groups
(In alphabetical order according to surnames)  
(Quick search with "Ctrl + F")
<a name="groups-Americas"></a>
## Americas
- [George Barbastathis ](http://optics.mit.edu/)(Massachusetts Institute of Technology)   
Key words: computational imaging, phase imaging, and tomographic imaging etc.

- [Stephen Boppart ](https://biophotonics.illinois.edu/)(University of Illinois Urbana-Champaign)    
Key words: biomedical imaging, optical coherence tomography, and adaptive optics etc.

- [Stanley H. Chan ](https://engineering.purdue.edu/ChanGroup/)(Purdue University)  
Key words: imaging through atmospheric turbulence etc.

- [Ni Chen](https://ni-chen.github.io)(University of Arizona)  
Key words: holography, phase imaging, and light field imaging etc.

- [James R. Fienup ](https://labsites.rochester.edu/fienup/)(University of Rochester)  
Key words: phase retrieval, coherent diffraction imaing, and wavefront sensing etc.

- [Jason W. Fleischer ](https://www.princeton.edu/~jasonf/)(Mississippi State University)  
Key words: phase retrieval, and optical tomography etc.

- [Paul Hand ](https://khoury.northeastern.edu/home/hand/)(Northeastern University)  
Key words: inverse problem and phase retrieval etc.

- [Babak Hassibi ](https://www.ee.caltech.edu/people/hassibi)(California Institute of Technology)  
Key words: phase retrieval etc.

- [Roarke Horstmeyer ](http://horstmeyer.pratt.duke.edu/)(Duke University)  
Key words: Fourier ptychography and single-photon detection etc.

- [Joseph A. Izatt ](http://biophotonics.pratt.duke.edu/)(Duke University)  
Key words: biomedical imaging, optical coherence tomography and high-resolution imaging etc.

- [Rongguang Liang ](https://wp.optics.arizona.edu/ualiangaol/)(The University of Arizona)  
Key words: phase imaging and biomedical imaging etc.

- [Jianwei (John) Miao ](https://www.physics.ucla.edu/research/imaging/)(University of California, Los Angeles)  
Key words: coherent diffractive imaging and atomic electron tomography etc.

- [Aydogan Ozcan ](https://research.seas.ucla.edu/ozcan/)(University of California, Los Angeles)  
Key words: phase imaging, holography, lensless imaging and optical diffraction neural network etc.

- [Ting-Chung Poon ](https://sites.google.com/vt.edu/oshandholographiclab/home/)(Virginia Polytechnic Institute and State University)  
Key words: holography etc.

- [Gabriel Popescu ](https://light.ece.illinois.edu/)(University of Illinois at Urbana-Champaign)  
Key words: phase imaging and biomedical imaging etc.

- [Mariano Rivera ](https://www.cimat.mx/~mrivera/mr.html)(Centro de Investigación en Matemáticas AC)  
Key words: fringe analysis phase retrieval and phase unwrapping etc.

- [Jannick Rolland ](http://www.odalab-spectrum.org/)(University of Rochester)  
Key words: optical coherence tomography etc.

- [Ju Sun ](https://glovex.umn.edu/)(University of Minnesota)  
Key words: inverse problem and phase retrieval etc.

- [Lei Tian ](https://sites.bu.edu/tianlab/)(Boston University)  
Key words: Fourier ptychography, transport of intensity equations (TIE), and imaging through scattering media etc.

- [Ashok Veeraraghavan ](https://www.computationalimaging.org/)(Rice University)  
Key words: wavefront sensing, imaging through scattering media, and lensless imaging etc.

- [Laura Waller ](https://www.laurawaller.com/)(University of California, Berkeley)  
Key words: phase imaging, lensless imaging, and transport of intensity equations (TIE) etc.

- [Lihong Wang ](http://coilab.caltech.edu/)(California Institute of Technology)  
Key words: optical coherence tomography and biomedical imaging etc.

- [Adam P. Wax ](http://bios.bme.duke.edu/)(Duke University)  
Key words: interferometry and biomedical imaging etc.

- [Florian Willomitzer ](https://3dim.northwestern.edu/)(University of Arizona)  
Key words: synthetic wavelength holography and interferometry etc.

- [Changhuei Yang ](https://biophot.caltech.edu/)(California Institute of Technology)  
Key words: Fourier ptychography, wavefront shaping and non-line-of-sight imaging etc.

- [Guoan Zheng ](https://smartimaging.uconn.edu/)(University of Connecticut)  
Key words: Fourier ptychography etc.
    
<a name="groups-Asia"></a>
## Asia
- [Anand Asundi ](https://www.doptron.com/)(d'Optron Pte Ltd)   
Key words: phase imaging, holography, and transport of intensity equations (TIE) etc.

- [Liheng Bian ](https://bianlab.github.io/)(Beijing Institute of Technology)  
Key words: multi-dimensional imaging (spectrum, phase) etc.

- [Liangcai Cao ](http://www.holoddd.com/)(Tsinghua University)  
Key words: holography etc.

- [Wen Chen ](https://www.eie.polyu.edu.hk/~wenchen/)(The Hong Kong Polytechnic University)  
Key words: holography and single-pixel imaging etc.

- [Chau-Jern Cheng ](https://scholar.lib.ntnu.edu.tw/en/persons/chau-jern-cheng)(National Taiwan Normal University)  
Key words: holography etc.

- [Zachary J. Smith and Kaiqin Chu ](http://staff.ustc.edu.cn/)(The University of Science and Technology of China)  
Key words: phase imaging and super-resolution imaging etc.

- [Jianglei Di ](https://www.researchgate.net/profile/Jianglei-Di)(GuangDong University of Technology)  
Key words: computational imaging and holography etc.

- [Peng Gao ](https://faculty.xidian.edu.cn/GP3/zh_CN/index.htm)(Xidian University)  
Key words: phase imaging, and super-resolution imaging etc.

- [Cuifang Kuang ](https://person.zju.edu.cn/en/cfkuang)(Zhejiang University)  
Key words: three-dimensional super-resolution phase microscopy and super-resolution imaging etc.

- [Edmund Y. Lam ](https://www.eee.hku.hk/~elam/)(The University of Hong Kong)  
Key words: phase retrieval, holography and computational imaging etc.

- [Cheng Liu ](http://science.jiangnan.edu.cn/content_js.jsp?urltype=news.NewsContentUrl&wbtreeid=1034&wbnewsid=5799)(Jiangnan University)  
Key words: phase imaging etc.

- [Yuan Luo ](https://optics.mc.ntu.edu.tw/)(National Taiwan University)  
Key words: phase imaging etc.  

- [Dalip Singh Mehta ](https://web.iitd.ac.in/~mehtads/)(Indian Institute of Technology Delhi)  
Key words: phase imaging and holograohy etc. 

- [Inkyu Moon](https://iivs.dgist.ac.kr/)(Daegu Gyeongbuk Institute of Science and Technology)  
Key words: holograohy in cell imaging and analysis etc.

- [An Pan ](https://www.sites.google.com/site/dranpanblog/)(Chinese Academy of Sciences)  
Key words: Fourier ptychography and biomedical imaging etc.

- [Jung-Hoon Park ](https://www.biooptics.org/)(Ulsan National Institute of Science and Technology)  
Key words: phase imaging and biomedical imaging etc.

- [YongKeun Park ](https://bmokaist.wordpress.com/)(Korea Advanced Institute of Science and Technology)  
Key words: phase imaging and biomedical imaging etc.

- [Kemao Qian ](https://www3.ntu.edu.sg/home/mkmqian/)(Nanyang Technological University)  
Key words: phase unwrapping and fringe analysis etc.

- [Joseph Rosen ](https://www.ee.bgu.ac.il/~rosen/)(Ben-Gurion University of the Negev)  
Key words: holography etc.

- [Natan T. Shaked](http://www.eng.tau.ac.il/~omni/index2.php/) (Tel Aviv University)  
Key words: interferometry, tomography, and biomedical imaging etc.

- [Guohai Situ ](https://people.ucas.edu.cn/~situ)(University of Chinese Academy of Sciences)  
Key words: phase imaging, holography, and computational imaging etc.

- [Xiaodi Tan](http://www.io-lab.cn/)(Fujian Normal University)  
Key words: holography etc.

- [Peter Wai Ming Tsang ](https://scholars.cityu.edu.hk/en/persons/wai-ming-peter-tsang(892d3f89-71e1-4348-9bd0-c27f242c0d00).html)(City University of Hong Kong)  
Key words: holography etc.

- [Yang Wang ](https://facultyprofiles.hkust.edu.hk/profiles.php?profile=yang-wang-yangwang)(The Hong Kong University of Science and Technology)  
Key words: phase retrieval etc.

- [Yuan Wu ](http://www.bme.cuhk.edu.hk/yuan/)(The Chinese University of Hong Kong)  
Key words: optical coherence tomography and biomedical imaging etc.

- [Baoli Yao ](https://people.ucas.ac.cn/~yaobaoli?language=en)(University of Chinese Academy of Sciences)  
Key words: holography and super-resolution imaging etc.

- [Jianlin Zhao ](https://teacher.nwpu.edu.cn/m/en/1982000067.html)(Northwestern Polytechnical University)  
Key words: holography and computational imaging etc.

- [Renjie Zhou ](https://www.renjiezhou.com/)(The Chinese University of Hong Kong)  
Key words: phase imaging and biomedical imaging etc.

- [Chao Zuo ](https://www.scilaboratory.com/)(Nanjing University of Science and Technology‍)  
Key words: transport of intensity equations (TIE), phase imaging and computational imaging etc.
    
<a name="groups-Europe"></a>
## Europe
- [Radim Chmelik ](https://www.vut.cz/en/people/radim-chmelik-2190)(Brno University of Technology)  
Key words: phase imaging and holography etc.

- [Pietro Ferraro](https://scholar.google.com/citations?user=yyFkAiQAAAAJ&hl=en)(Consiglio Nazionale delle Ricerche)  
Key words: holography etc.

- [Hans-Werner Fink](https://www.physik.uzh.ch/groups/fink/)(University of Zurich)  
Key words: electron holography etc.

- [Maxime Jacquot](https://www.femto-st.fr/en/femto-people/maximejacquot)(Université Bourgogne Franche-Comté)  
Key words: holography etc.

- [Demetri Psaltis ](https://www.epfl.ch/labs/lo/)(The École polytechnique fédérale de Lausanne)  
Key words: holography, imaging through scattering media, and linear and non-linear multimode fibers etc.

- [Pascal Picart ](http://perso.univ-lemans.fr/~ppicart/rech/perso/BooksPP.html)(Le Mans University)  
Key words: holography and phase imaging etc.

- [Latychevskaia Tatiana ](https://coherentimaging.wordpress.com/)(University of Zurich)  
Key words: holography, phase retrieval and coherent diffractive imaging etc.

- [Michael Unser ](http://bigwww.epfl.ch/)(The École polytechnique fédérale de Lausanne)  
Key words: phase retrieval, phase unwrapping, transport of intensity equations (TIE) and biomedical imaging etc.

****
<a name="companies"></a>
# Companies
(In alphabetical order)

- [d'Optron](https://www.doptron.com/) 
- [Holmarc Opto-Mechatronics](https://holmarc.com/)  
- [Imaging Optic](https://www.imagine-optic.com/)  
- [Lyncee Tec](https://www.lynceetec.com/)  
- [Nanolive](https://www.nanolive.ch/)  
- [Phase Holographic Imaging PHI AB](https://phiab.com/)  
- [Phasics](https://www.phasics.com/)  
- [Phi Optics](https://phioptics.com/)
- [Telight](https://telight.eu/)
- [Tomocube](https://www.tomocube.com/)
- [Zygo](https://www.zygo.com/)  

****
<a name="workshops"></a>
# Workshops (video or slides available)
(In chronological order)

- ["Phase Retrieval"](https://www.bioxfel.org/phase-retrieval-2021) in BioXFEL (October 18 - 19, 2021)  
- ["Computational Microscopy"](http://www.ipam.ucla.edu/programs/long-programs/computational-microscopy/?tab=overview) in IPAM (September 12 - December 16, 2022)
   - ["Computational Microscopy Tutorials" ](http://www.ipam.ucla.edu/programs/workshops/computational-microscopy-tutorials/)(September 13-16, 2022)
   - ["Diffractive Imaging with Phase Retrieval"  ](http://www.ipam.ucla.edu/programs/workshops/workshop-i-diffractive-imaging-with-phase-retrieval/)(October 10-14, 2022)
   

****
<a name="Rpapers"></a>
# Research papers
(In chronological order)

<a name="PARpapers"></a>
## Phase acquisition
<a name="HoloRpapers"></a>
### Holography/Interferometry
a  
<a name="TIERpapers"></a>
### Transport of intensity equation
a  

<a name="DLRpapers"></a>
## Phase acquisition and deep learning

****
<a name="papers"></a>
# Review/Tutorial papers
(In chronological order)

<a name="PApapers"></a>
## Phase acquisition

- Y. Shechtman, Y. C. Eldar, O. Cohen, H. N. Chapman, J. Miao, and M. Segev  
*[Phase Retrieval with Application to Optical Imaging: A contemporary overview](https://doi.org/10.1109/MSP.2014.2352673),*  
IEEE Signal Process. Mag. 32(3), 87–109 (2015).

- Y. Park, C. Depeursinge, and G. Popescu  
*[Quantitative phase imaging in biomedicine](https://doi.org/10.1038/s41566-018-0253-x),*  
Nature Photon. 12(10), 578–589 (2018).

- T. Latychevskaia  
*[Iterative phase retrieval for digital holography: tutorial](https://doi.org/10.1364/JOSAA.36.000D31),*  
J. Opt. Soc. Am. A 36(12), D31 (2019).

- H. Yu, Y. Lan, Z. Yuan, J. Xu, and H. Lee  
*[Phase Unwrapping in InSAR: A Review](https://doi.org/10.1109/MGRS.2018.2873644),*  
IEEE Geosci. Remote Sens. Mag. 7(1), 40–58 (2019).

- T. Cacace, V. Bianco, and P. Ferraro  
*[Quantitative phase imaging trends in biomedical applications](https://doi.org/10.1016/j.optlaseng.2020.106188),*  
Optics and Lasers in Engineering 135, 106188 (2020).

- J. T. Sheridan, R. K. Kostuk, A. F. Gil, Y. Wang, W. Lu, H. Zhong, Y. Tomita, C. Neipp, J. Francés, S. Gallego, I. Pascual, V. Marinova, S.-H. Lin, K.-Y. Hsu, F. Bruder, S. Hansen, C. Manecke, R. Meisenheimer, C. Rewitz, T. Rölle, S. Odinokov, O. Matoba, M. Kumar, X. Quan, Y. Awatsuji, P. W. Wachulak, A. V. Gorelaya, A. A. Sevryugin, E. V. Shalymov, V. Yu Venediktov, R. Chmelik, M. A. Ferrara, G. Coppola, A. Márquez, A. Beléndez, W. Yang, R. Yuste, A. Bianco, A. Zanutta, C. Falldorf, J. J. Healy, X. Fan, B. M. Hennelly, I. Zhurminsky, M. Schnieper, R. Ferrini, S. Fricke, G. Situ, H. Wang, A. S. Abdurashitov, V. V. Tuchin, N. V. Petrov, T. Nomura, D. R. Morim, and K. Saravanamuttu  
*[Roadmap on holography](https://doi.org/10.1088/2040-8986/abb3a4),*  
J. Opt. 22(12), 123002 (2020).

- C. Zuo, J. Li, J. Sun, Y. Fan, J. Zhang, L. Lu, R. Zhang, B. Wang, L. Huang, and Q. Chen  
*[Transport of intensity equation: a tutorial](https://doi.org/10.1016/j.optlaseng.2020.106187),*  
Optics and Lasers in Engineering 106187 (2020).

- V. Balasubramani, M. Kujawińska, C. Allier, V. Anand, C.-J. Cheng, C. Depeursinge, N. Hai, S. Juodkazis, J. Kalkman, A. Kuś, M. Lee, P. J. Magistretti, P. Marquet, S. H. Ng, J. Rosen, Y. K. Park, and M. Ziemczonok  
*[Roadmap on Digital Holography-Based Quantitative Phase Imaging](https://doi.org/10.3390/jimaging7120252),*  
J. Imaging 7(12), 252 (2021).

- B. Javidi, A. Carnicer, A. Anand, G. Barbastathis, W. Chen, P. Ferraro, J. W. Goodman, R. Horisaki, K. Khare, M. Kujawinska, R. A. Leitgeb, P. Marquet, T. Nomura, A. Ozcan, Y. Park, G. Pedrini, P. Picart, J. Rosen, G. Saavedra, N. T. Shaked, A. Stern, E. Tajahuerce, L. Tian, G. Wetzstein, and M. Yamaguchi  
*[Roadmap on digital holography [Invited]](https://doi.org/10.1364/OE.435915),*  
Opt. Express 29(22), 35078 (2021).

- G. Zheng, C. Shen, S. Jiang, P. Song, and C. Yang  
*[Concept, implementations and applications of Fourier ptychography](https://doi.org/10.1038/s42254-021-00280-y),*  
Nat. Rev. Phys. 3(3), 207–223 (2021).

- V. Petrov, A. Pogoda, V. Sementin, A. Sevryugin, E. Shalymov, D. Venediktov, and V. Venediktov  
*[Advances in Digital Holographic Interferometry](https://doi.org/10.3390/jimaging8070196),*  
J. Imaging 8(7), 196 (2022).

- T. L. Nguyen, S. Pradeep, R. L. Judson-Torres, J. Reed, M. A. Teitell, and T. A. Zangle  
*[Quantitative Phase Imaging: Recent Advances and Expanding Potential in Biomedicine](https://doi.org/10.1021/acsnano.1c11507),*  
ACS Nano 16(8), 11516–11544 (2022).

- G. Baffou  
*[Wavefront Microscopy Using Quadriwave Lateral Shearing Interferometry: From Bioimaging to Nanophotonics](https://doi.org/10.1021/acsphotonics.2c01238),*  
ACS Photonics 10(2), 322–339 (2023).

<a name="DLpapers"></a>
## Phase acquisition and deep learning

- Y. Jo, H. Cho, S. Y. Lee, G. Choi, G. Kim, H. Min, and Y. Park  
*[Quantitative Phase Imaging and Artificial Intelligence: A Review](https://doi.org/10.1109/JSTQE.2018.2859234),*  
IEEE J. Select. Topics Quantum Electron. 25(1), 1–14 (2019).

- Y. Rivenson, Y. Wu, and A. Ozcan  
*[Deep learning in holography and coherent imaging](https://doi.org/10.1038/s41377-019-0196-0),*  
Light Sci. Appl. 8(1), 85 (2019).

- G. Ongie, A. Jalal, C. A. Metzler, R. G. Baraniuk, A. G. Dimakis, and R. Willett  
*[Deep Learning Techniques for Inverse Problems in Imaging](https://doi.org/10.48550/arXiv.2005.06001),*  
arXiv:2005.06001 (2020).

- T. Zeng, Y. Zhu, and E. Y. Lam  
*[Deep learning for digital holography: a review](https://doi.org/10.1364/OE.443367),*  
Opt. Express 29(24), 40572 (2021).

- L. Zhou, H. Yu, Y. Lan, and  m. Xing  
*[Artificial Intelligence In Interferometric Synthetic Aperture Radar Phase Unwrapping: A Review](https://doi.org/10.1109/MGRS.2021.3065811),*  
IEEE Geosci. Remote Sens. Mag. 2–20 (2021).

- C. Zuo, J. Qian, S. Feng, W. Yin, Y. Li, P. Fan, J. Han, K. Qian, and Q. Chen  
*[Deep learning in optical metrology: a review](https://doi.org/10.1038/s41377-022-00714-x),*  
Light Sci. Appl. 11(1), 39 (2022).

- Y. Guo, L. Zhong, L. Min, J. Wang, Y. Wu, K. Chen, K. Wei, and C. Rao  
*[Adaptive optics based on machine learning: a review](https://doi.org/10.37188/lam.2022.013),*  
Opto-Electronic Advances 5(7), 200082–200082 (2022).

- T. Shimobaba, D. Blinder, T. Birnbaum, I. Hoshi, H. Shiomi, P. Schelkens, and T. Ito  
*[Deep-Learning Computational Holography: A Review](https://doi.org/10.3389/fphot.2022.854391),*  
Front. Photon. 3, 854391 (2022).

- A. Qayyum, I. Ilahi, F. Shamshad, F. Boussaid, M. Bennamoun, and J. Qadir  
*[Untrained Neural Network Priors for Inverse Imaging Problems: A Survey](https://doi.org/10.1109/TPAMI.2022.3204527),*  
IEEE Trans. Pattern Anal. Mach. Intell. 45(5), 6511–6536 (2022).

- G. Situ  
*[Deep holography](https://doi.org/10.37188/lam.2022.013),*  
Light Advanced Manufacturing 3(2), 1 (2022).

- K. Wang, Q. Kemao, J. Di, and J. Zhao  
*[Deep learning spatial phase unwrapping: a comparative review](https://doi.org/10.1117/1.APN.1.1.014001),*  
Adv. Photon. Nexus 1(1), 014001 (2022).

- J. Dong, L. Valzania, A. Maillard, T. Pham, S. Gigan, and M. Unser  
*[Phase Retrieval: From Computational Imaging to Machine Learning: A tutorial](https://doi.org/10.1109/MSP.2022.3219240),*  
IEEE Signal Process. Mag. 40(1), 45–57 (2023).


****
<a name="BK"></a>
# Books
(In chronological order)  

- D. C. Ghiglia and M. D. Pritt  
*[Two-Dimensional Phase Unwrapping: Theory, Algorithms, and Software](https://www.wiley.com/en-dk/Two+Dimensional+Phase+Unwrapping:+Theory,+Algorithms,+and+Software-p-9780471249351),*  
(Wiley, 1998).

- J. W. Goodman  
*[Introduction to Fourier Optics](https://link.springer.com/book/9780974707723),*  
3rd ed (Roberts & Co, 2005).

- E. H. Duke and S. R. Aguirre  
*[3D Imaging: Theory, Technology and Applications, Computer Science, Technology and Applications](https://www.proquest.com/legacydocview/EBC/3018197?accountid=14548),*  
(Nova Science Publishers, 2010).

- T. Tishko, D. Tishko, and V. P. Titar  
*[Holographic Microscopy of Phase Microscopic Objects: Theory and Practice](https://doi.org/10.1142/7512),*  
(World Scientific Publishing Co., 2011).

- M. Mir, B. Bhaduri, R. Wang, R. Zhu, and G. Popescu  
*[Quantitative Phase Imaging](https://doi.org/10.1016/B978-0-44-459422-8.00003-5),*  
in Progress in Optics (Elsevier, 2012), 57, pp. 133–217.

- Q. Kemao   
*[Windowed Fringe Pattern Analysis](https://doi.org/10.1117/3.1002080),*  
(SPIE, 2013).


- B. Javidi, E. Tajahuerce, and P. Andres  
*[Multi-Dimensional Imaging](https://ieeexplore.ieee.org/servlet/opac?bknumber=6798070),*  
(Cambridge University Press, (John Wiley & Sons Inc, 2014).

- T.-C. Poon and J.-P. Liu  
*[Introduction to Modern Digital Holography: With MATLAB](https://doi.org/10.1017/CBO9781139061346),*  
(Cambridge University Press, 2014).

- M. Servín, J. Antonio Quiroga, J. Moisés Padilla, J. A. Quiroga, J. M. Padilla, and J. M. Padilla  
*[Fringe Pattern Analysis for Optical Metrology: Theory, Algorithms, and Applications](https://www.wiley.com/en-us/Fringe+Pattern+Analysis+for+Optical+Metrology:+Theory,+Algorithms,+and+Applications-p-9783527411528),*  
(Wiley-VCH, 2014).

- C. Liu, S. Wang, and S. P. Veetil  
*[Computational Optical Phase Imaging, Progress in Optical Science and Photonics](https://link.springer.com/book/10.1007/978-981-19-1641-0),*  
(Springer Singapore, 2022), 21.




****
<a name="DT"></a>
# Dissertations and Thesis
(In chronological order)

- George Barbastathis,  
*[Intelligent holographic databases](https://resolver.caltech.edu/CaltechETD:etd-03172008-142604)*,  
Ph.D. Thesis, California Institute of Technology, 1997. [PDF](https://thesis.library.caltech.edu/986/1/Barbastathis_g_1998.pdf)  

- Stephen A. Boppart,  
*[Surgical diagnostics, guidance, and intervention using optical coherence tomography](http://hdl.handle.net/1721.1/9889)*,  
Ph.D. Thesis, Massachusetts Institute of Technology, 1998. [PDF](https://dspace.mit.edu/bitstream/handle/1721.1/9889/41862022-MIT.pdf)

- Changhuei Yang,  
*[Harmonic phase based low coherence interferometry : a method for studying the dynamics and structures of cells](http://hdl.handle.net/1721.1/28242)*,  
Ph.D. Thesis, Massachusetts Institute of Technology, 2002. [PDF](https://dspace.mit.edu/bitstream/handle/1721.1/28242/50547882-MIT.pdf)

- Laura Waller,  
*[Computational phase imaging based on intensity transport](http://hdl.handle.net/1721.1/60821)*,  
Ph.D. Thesis, Massachusetts Institute of Technology, 2010.  [PDF](https://dspace.mit.edu/bitstream/handle/1721.1/60821/696796127-MIT.pdf)

- Guoan Zheng,  
*[Innovations in Imaging System Design: Gigapixel, Chip-Scale and MultiFunctional Microscopy](https://resolver.caltech.edu/CaltechTHESIS:10102012-101657790)*,  
Ph.D. Thesis, California Institute of Technology, 2012.  [PDF](https://thesis.library.caltech.edu/7234/4/Zheng_Guoan_Final_Thesis_12_17_2012.pdf)

- YongKeun Park,  
*[Pathophysiology of human red blood cell probed by quantitative phase microscopy](http://hdl.handle.net/1721.1/58092)*,  
Ph.D. Thesis, Massachusetts Institute of Technology, 2013.  [PDF](https://dspace.mit.edu/bitstream/handle/1721.1/58092/656250904-MIT.pdf)

- Hoa Pham,  
*[Real-time quantitative phase imaging for cell studies](http://hdl.handle.net/2142/45508)*,   
Ph.D. Thesis, University of Illinois at Urbana-Champaign, 2013.  [PDF](https://www.ideals.illinois.edu/items/45490/bitstreams/134768/object?dl=1)

- Lei Tian,  
*[Compressive phase retrieval](http://hdl.handle.net/1721.1/81756)*,  
Ph.D. Thesis, Massachusetts Institute of Technology, 2013.  [PDF](https://dspace.mit.edu/bitstream/handle/1721.1/81756/860986128-MIT.pdf)

- Mustafa Mir,    
*[Quantitative phase imaging for cellular biology](http://hdl.handle.net/2142/45668)*,   
Ph.D. Thesis, University of Illinois at Urbana-Champaign, 2013.  [PDF](https://www.ideals.illinois.edu/items/45650/bitstreams/135201/object?dl=1)

- Renjie Zhou,  
*[Interferometric light microscopy for wafer defect inspection and three-dimensional object reconstruction](http://hdl.handle.net/2142/88067)*,   
Ph.D. Thesis, University of Illinois at Urbana-Champaign, 2013.  [PDF](https://www.ideals.illinois.edu/items/73166/bitstreams/193614/object?dl=1)

- Nathan D. Shemonski,   
*[In vivo human computed optical interferometric tomography](http://hdl.handle.net/2142/73035)*,   
Ph.D. Thesis, University of Illinois at Urbana-Champaign, 2015.  [PDF](https://www.ideals.illinois.edu/items/73224/bitstreams/193791/object?dl=1)

- Dennis J. Lee,  
*[Computational optical imaging: Applications in synthetic aperture imaging, phase retrieval, and digital holography](https://docs.lib.purdue.edu/open_access_dissertations/500)*,   
Ph.D. Thesis, Purdue University, 2015.  [PDF](https://docs.lib.purdue.edu/cgi/viewcontent.cgi?article=1406&context=open_access_dissertations)

- Tae-Woo Kim,   
*[Quantitative phase imaging: advances to 3D imaging and applications to neuroscience](https://hdl.handle.net/2142/72977)*,   
Ph.D. Thesis, University of Illinois at Urbana-Champaign, 2015.  [PDF](https://www.ideals.illinois.edu/items/89347/bitstreams/229128/object?dl=1)

- Chien-Hung Lu,   
*[Computational Phase Imaging in Nonlinear and Quantum Systems](http://arks.princeton.edu/ark:/88435/dsp01k643b3556)*,   
Ph.D. Thesis, Princeton University, 2015.  [PDF](https://dataspace.princeton.edu/bitstream/88435/dsp01k643b3556/1/Lu_princeton_0181D_11552.pdf)

- Shamira Sridharan,   
*[Applications of quantitative phase imaging for pathology](http://hdl.handle.net/2142/88244)*,   
Ph.D. Thesis, University of Illinois at Urbana-Champaign, 2015.  [PDF](https://www.ideals.illinois.edu/items/89524/bitstreams/229508/object?dl=1)

- Tan Huu Nguyen,   
*[Computational phase imaging for biomedical applications](http://hdl.handle.net/2142/95321)*,   
Ph.D. Thesis, University of Illinois at Urbana-Champaign, 2016.  [PDF](https://www.ideals.illinois.edu/items/98436/bitstreams/315324/object?dl=1)

- Chandrabhan Seniya,  
*[A flexible low-cost quantitative phase imaging microscopy system for label-free imaging of multi-cellular biological samples]( http://webcat.warwick.ac.uk/record=b3184498~S1)*,   
Ph.D. Thesis, University of Warwick, 2018.  [PDF](http://wrap.warwick.ac.uk/106451/1/WRAP_Theses_Seniya_2018.pdf)

- Aamod Shanker,  
*[Differential methods in phase imaging for optical lithography](http://www2.eecs.berkeley.edu/Pubs/TechRpts/2018/EECS-2018-160.html)*,   
Ph.D. Thesis, University of California, Berkeley, 2018.  [PDF](http://www2.eecs.berkeley.edu/Pubs/TechRpts/2018/EECS-2018-160.pdf)

- Shuai Li,  
*[Computational imaging through deep learning](https://hdl.handle.net/1721.1/122070)*,   
Ph.D. Thesis, Massachusetts Institute of Technology, 2019.  [PDF](https://dspace.mit.edu/bitstream/handle/1721.1/122070/1117711022-MIT.pdf)

- David A. Barmherzig,  
*[The Phase Retrieval Problem: Theory, Algorithms, and Applications](https://purl.stanford.edu/tw768tw9748)*,   
Ph.D. Thesis, Stanford University, 2019. [PDF](https://stacks.stanford.edu/file/druid:tw768tw9748/BarmherzigDissertationUpload-augmented.pdf)  

- Yichen Wu,  
*[Deep Learning-enabled Computational Imaging in Optical Microscopy and Air Quality Monitoring](https://escholarship.org/uc/item/1249c1bv)*,   
Ph.D. Thesis, University of California, Los Angeles, 2019.  [PDF](https://escholarship.org/content/qt1249c1bv/qt1249c1bv.pdf?t=pzmaiu)

- Michael Kellman,  
*[Physics-based Learning for Large-scale Computational Imaging](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2020/EECS-2020-167.html)*,   
Ph.D. Thesis, University of California, Berkeley, 2020.  [PDF](http://www2.eecs.berkeley.edu/Pubs/TechRpts/2020/EECS-2020-167.pdf)

- Zhuoqun Zhang,  
*[Analysis and Development of Phase Retrieval Algorithms for Ptychography](https://etheses.whiterose.ac.uk/30033/)*,   
Ph.D. Thesis, University of Sheffield, 2021. [PDF](https://etheses.whiterose.ac.uk/30033/1/zhuoqun_zhang_thesis_160251201_Corrected.pdf)

- Obed A. Ayisi,  
*[Multiple-Wavelength Phase Retrieval With Digital Holographic Microscopy](https://openknowledge.nau.edu/id/eprint/5717)*,   
Masters Thesis, Northern Arizona University, 2021.

- Tairan Liu,  
*[Deep Learning in Optical Microscopy, Holographic Imaging and Sensing](https://escholarship.org/uc/item/8k03d1g2)*,   
Ph.D. Thesis, University of California, Los Angeles, 2022. 

- Marissa A. Morado,  
*[Solving the phase retrieval problem using an artificial neural network](http://hdl.handle.net/20.500.12680/cv43p355k)*,   
Ph.D. Thesis, California State University, Fresno, 2022. [PDF](https://scholarworks.calstate.edu/downloads/44558m79w)

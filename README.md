# The open-source numerical tool (QNM_N-EBC) of the quasinormal mode expansion theory for mesoscale plasmonic nanoresonators proposed in Ref. [1]
Reference [1] proposes a quasinormal mode expansion theory for the optical response of the plasmonic nanoresonators with mesoscale (2-20 nm) feature sizes. The optical response of such mesoscale plasmonic nanoresonators is significantly affected by the nonlocality, surface damping and electron spill-out nonclassical quantum effects, which can be fully described by the nonclassical electromagnetic boundary condition (N-EBC) expressed with the surface-response Feibelman d parameters [2]. In the theory, the expansion expression of source-excited nonclassical electromagnetic field (under the N-EBC) are given, and the expression have a fully analytical dependence on the N-EBC and classical QNM.

# The softwares used in the tool
The open-source numerical tool relies on COMSOL Multiphysics software to achieve the calculation and normalization of the classical QNM, and relies on the Matlab, via the Matlab-COMSOL livelink to achieve the calculation of the expansion expression of source-excited nonclassical electromagnetic field. 

# Examples
The numerical tools for the calculations of total electromagnetic field (in the document named “Total field”) and scattered electromagnetic field (in the document named “Scattered field”) are both provided. Specifically, the programs in “Total field” and in “Scattered field” can be used to calculate the blue solid and blue dotted curves in Fig. 2(a2) and Fig. 3(c) in Ref. [1], respectively. In addition, the programs for the fullwave calculation with COMSOL Multiphysics software are provided, and the name of such programs ends with “fullwave_web”. With these programs, the blue circles in Fig. 2(a2) and Fig. 3(c) can be obtained.
 Table 1
Curves in Fig. 2(a2)	Corresponding codes in folder “Fig2(a2)”
Blue circles (FEM, NEBC)	single_nanowire_NPoM_antenna_h=6_PF_fullwave_web.mph

Blue-solid curve (Model 1, NEBC)	single_nanowire_NPoM_antenna_h=6_classicalQNM_web.mph, nonclassical_QNM_expan_for_singleantenna_PF.m

Blue-solid curve (Model 2A, NEBC)	single_nanowire_NPoM_antenna_h=6_classicalQNM_web.mph, nonclassical_QNM_expan_for_singleantenna_PF.m
Blue-dashed curve (Model 2B, NEBC)	single_nanowire_NPoM_antenna_h=6_classicalQNM_web.mph, nonclassical_QNM_expan_for_singleantenna_PF.m
Red circles (FEM, CEBC)	single_nanowire_NPoM_antenna_h=6_PF_fullwave_web.mph
Red-solid curve (Model 1, CEBC)	single_nanowire_NPoM_antenna_h=6_classicalQNM_web.mph, nonclassical_QNM_expan_for_singleantenna_PF.m

 
# Citing QNM_N-EBC
We kindly request that you cite the following Ref. [1] in any published work for which you used our implementation here.

# Reference
[1] Can Tao, Ying Zhong, and Haitao Liu, Quasinormal mode expansion theory for mesoscale plasmonic nanoresonators: an analytical treatment of nonclassical electromagnetic boundary condition, Physical Review Letters, (2022).
  
[2] Y. Yang, D. Zhu, W. Yan, A.Agarwal, M. Zheng, J. D. Joannopoulos, P. Lalanne, T. Christensen, K. K. Berggren, and M. Soljačić, A general theoretical and experimental framework for nanoscale electromagnetism, Nature 576, 248 (2019).



  

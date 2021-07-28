#      Here is a list of the significant changes between 2.5.1 and 2.5.0

    * Minor bugs fixed.

    * New tool to compute the thermochemistry properties :   
          Display window/Animation/Vibration

    * Global and local reactivity indices can be calculated by Finite Difference 
    or Frontier Molecular Orbitals : Display window/Reactvity Indices.

    * 2018 Windows version of Gamess supported (Install Gamess in 
    C:\Users\Public\gamess-64 and copy or rename gamess.2018-R1-pgi.exe 
    in gamess.11-64.exe )

    * Gabedit can now compute local vibrationnal modes. The implemented method 
    is that described in Christoph R. Jacob & Markus Riher , J. Chem Phys. 130
    (2009) 084106 and Xiaolu Cheng, Justin J. Talbot, and in Ryan P. Steele,
    J. Chem. Phys. 145 (2016) 124112

    * Several new crystallography tools have been implemented. 
      Gabedit can now :
       - Read CIF file.
       - Build SuperCell.
       - Build Slab.
       - Build Cluster using Wulff construction.
       - Export structure in CIF file (with or without symmetry operators).
       - Reduce Cell to primitive, Niggli or Delaunay one.
       - Compute space group & symmetry operators.
       - Standardize cell (to conventional or to primitive).
       - Generate k-points along high symmetry lines, for band structure
         calculations.
       - Get a prototype crystal from a database implemented in Gabedit.

        They are available by selecting "Crystallography" from "Draw window"
        menu. The list of references used to implement these tools can be
        obtained from: Draw window/Crystallography/Help& references.



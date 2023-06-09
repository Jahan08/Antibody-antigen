## The objectives of this learning:
1. Understand and demonstrate the importance of proper protein preparation and reliabilityanalysis
2. Recall basic sequence analysis workflows in the Multiple Sequence Viewer/Editor
3. Recall and apply knowledge of protein surface analysis
4. Recall and apply knowledge of antibody structure prediction and humanization
5. Recall and apply knowledge of protein-protein docking by setting up an antibody-antigendocking job and analyzing the results
6. Recall and apply knowledge of residue scanning by running an alanine scanning job andanalyzing the results
7. Complete a case study covering a particular antibody engineering; 
8. Evaluate antibody-antigenbinding, justify mutation selection and compute MM-GBSA binding energy predictions for the proposed mutants


## Antibodies
Antibodies, also known as Immunoglobulins (Ig) are gamma globulin proteins, primarily found in the blood of vertebrates. These glycoproteins serve as a critical component of the immune system when the host fails to activate alternative compliment pathways or phagocytic cells in response to invading microorganisms or other antigens. The incredible specificity with which immunoglobulins bind to an antigen is based upon structural complementarity between the antigen and antibody heavy and light chains.

When a foreign antigen binds to a B-lymphocyte (B-cell), it activates the B-cell, and upon stimulation by helper T-cells, undergoes clonal proliferation and B-cell maturation into antibody forming plasma cells. Each plasma cell is programmed to make an antibody of a single specificity, which it releases into the blood.

Antibody is a part of the host cell's defense. It's made by a certain type of white blood cell that's called a B cell. The structure of the antibody consists of two light chains and two heavy chains, and at the very tip of the antibody is a hypervariable region, and this hypervariable region allows the antibody to make different types of antibodies that will respond to all of the antigens that will assault the body. An antigen is anything that is foreign to the human body. It can be a virus, it can be a bacteria, and in some cases your own body will appear as foreign. And so you can have in certain instances where your own body will make antibodies against parts that are part of you

#### Structure
The basic functional unit of an antibody is an immunoglobulin monomer, but antibodies secreted from plasma cells are typically dimeric with occasional higher order structures. Typical secreted antibodies have a basic four-peptide structure of two identical heavy chains and two identical light chains joined together by interchain disulfide bonds, forming a “Y” shaped molecule.

The disulfide bonds are positioned within a flexible region called the hinge region, which seperates the lobes of the antibody from one another and provides ample flexibility to bind antigens effectively. [1] Each domain (2 heavy and 2 light) contain between 70-110 amino acids and are classified into different categories according to size and function. [4] Both domains, heavy and light, contain variable and constant regions that are crucial to antibody function.

#### Heavy Chain
There are five types of immunoglobulin heavy chains, in mammals, α, δ, ε, γ, and μ, and give rise to the five unique classes or isotypes of antibodies, IgA, IgD, IgE, IgG, and IgM, which differ in size and composition. Each heavy chain has a constant region and variable region. The constant region is identical in all antibodies of the same isotype, but differ in antibodies of different isotypes; i.e. all IgA have the same sequence in their heavy chain constant region, but these constant regions differ between IgA and IgD, etc. [6] The α, δ, and γ heavy chains have a constant region composed of three tandem immunoglobulin domains while heavy chains ε and μ contain four. The variable region of the heavy chain in antibodies is different for all antibodies created by different B-cells.

#### Light Chain
Every antibody contains two light chains that are identical to each other. There are two types of immunoglobulin light chains in mammals, labeled lambda and kappa, with only one represented in each antibody. Each light chain has one constant domain followed by one variable domain, with a total length of about 215 amino acids.

#### Variable Regions
The Fab region (Fragment, Antigen Binding region) is composed of one constant and one variable domain from each heavy and light chain of the antibody. It is the part of the antibody that gives it its famous “Y” shape.[8] Held within the Fab region is the variable domain, also known as the Fv region.[9] Within the Fv region lie “hypervariable regions,” positioned at one end of the variable domain where they form parts of the Beta-turn loops and are clustered close to each other in space. The clustering of the hypervariable loops at the tips of the variable regions where the antigen-binding site is located makes them perfect candidates for antigen recognition. [1]The sequence heterogeneity of the three heavy and three light chain hypervariable loops creates significant antigen specificity diversity through variations in the binding surface nature and shape. Each hypervariable region can be viewed as an independent structure contributing to the complementarity of the biding site and antigen and is often referred to as a complementarity determining region (CDR).

#### Constant Regions
The remaining part of the antibody, namely the Fc region, does not play a role in binding the antigen, but rather is responsible for modulating the immune systems response to the formation of an antibody-antigen complex. The Fragment Crystallizable (Fc) region is composed of two heavy chain constant regions that are isotype specific. [11] Antibodies are glycoproteins because of glycosylation at conserved positions in their Fc regions. This glycosylation is a critical component determing the rate of antibody clearance form the body.[12] Once an antibody binds to an antigen, the Fc region binds to Fc receptors, among other proteins, to mediate a host of different physiological responses ranging from oposonization, to degranulation of mast cells, to the release of cytokines and cytotoxic molecules, etc. resulting in the destruction of the pathogen. [13] Depending on the class of antibody, as dictated by the identity of the Fc region, the antibody half-life and distribution throughout the body varies. Further, since Fc receptors are antibody isotype specific, the type of immune response is dependent on the type of Fc region on the immunoglobulin, allowing for different immune responses to the same pathogen if necessary

#### Chimeric and Humanized antibody
In an attempt to reduce the immunogenicity of the mouse antibodies, genetic engineering was used to generate chimeric antibodies containing human constant domains and the mouse variable domains to retain the specificity (1, 2).This was then taken a step further by grafting of the CDRs from a mouse antibody onto a human variable region framework, creating humanized antibodies (3). The crystal structures of rat and humanized antibodies later showed that an appropriately selected human scaffold correctly supports the orientation of the CDRs 

#### Conformation and Self-Association of a Concentrated Monoclonal Antibody
Therapeutic mAbs interrupt, inhibit or augment multistep disease pathways through the antigen recognition mechanism. The amino acid sequence, complementarity determining region (CDR), loop size,
cosolvents and chemical modifications all contribute to the protein-protein interactions. Monoclonal antibodies (mAbs) represent the largest class of therapeutic proteins developed and marketed for the treatment of a wide range of serious illnesses. Often, the mAb based therapeutics are formulated at concentrations ≥ 100 mg/mL to limit the volume for subcutaneous delivery to patients. Achieving stable concentrated formulations for therapeutic proteins is a persistent technical challenge for the biopharmaceutical industry. A thorough understanding of candidate mAb conformation in solution is essential, early in development, to assess potential liabilities such as aggregation tendency, manufacturability and formulation strategy.

Reversible or irreversible aggregate formation in the native (folded) or non-native (unfolded, denatured) conformations are the main consequences of mAb self associations in solution that may also lead to immunosensitivity after parenteral administration. The non-native (conformational) aggregation pathway occurs when unfolded or partially denatured intermediates form oligomers to shield exposed hydrophobic areas from water. The native state association occurs as a result of hydrophobic or electrostatic surface properties of the protein. Self-association in the native state is often reversible but may become irreversible if the associated proteins undergo a conformational change

### Framework Region of Antibody

Antibodies are composed of four polypeptides– two heavy chains and two light chains joined to form a "Y" shaped molecule. The variable region contained 110-130 amino acids, offers the antibody its specificity for binding antigen. This region is further divided into two regions: hypervariable (HV) and framework (FR) regions. Three hypervariable regions- HV 1, 2 and 3 exist in light and heavy chains. Four FR regions separate the HV regions, and they have relatively more stable amino acids sequences. The FR regions generate a beta-sheet structure which plays as a scaffold to hold the HV regions in position to contact antigen. Besides, the FR regions are highly conserved, with most of the variability occurring in the HV regions, also called complementarity-determining regions (CDRs).

### Vernier zone residues/canonical structural residues

are amino acids in the framework regions of an antibody variable domain that are located close to the hypervariable regions (HVRs). They are called Vernier because they act like the vernier scale on a micrometer, providing additional precision to the binding of the antibody to its antigen.

Vernier zone residues are important for the following aspects of antibody function:

Antibody affinity: Vernier zone residues can contribute to the affinity of an antibody for its antigen by providing additional contact points between the antibody and the antigen.
Antibody specificity: Vernier zone residues can contribute to the specificity of an antibody for its antigen by helping to position the HVRs in the correct orientation for binding.
Antibody diversity: Vernier zone residues are relatively conserved in sequence, while the HVRs are highly variable. This diversity is important because it allows antibodies to bind to a wide variety of antigens.

Vernier zone residues are 30 residues in the paratope that affect CDR conformations - 16 residues in the heavy variable region and 14 in the light variable region.. A 2008 paper
found that there are major thermodynamic consequences to mutations of Vernier Zone Residues - indicating both the role they play in antibody-antigen binding and the risk
associated with mutating them. In general, CDR grafting with retained Vernier Zone residues has been successful, with the most popular example being Herceptin.

Vernier zone residues are located close to the hypervariable regions (HVRs), while CSRs are located further away. This means that vernier zone residues can have a more direct effect on the binding of the antibody to the antigen, while CSRs have a more indirect effect.

Vernier zone residues are also more conserved in sequence than CSRs. This means that vernier zone residues are more likely to be found in the same position in the three-dimensional structure of antibodies, while CSRs are more likely to vary in position.

Overall, vernier zone residues and CSRs are both important for the specificity and affinity of the antibody-antigen interaction. However, there are some key differences between the two that can affect their role in antibody function.


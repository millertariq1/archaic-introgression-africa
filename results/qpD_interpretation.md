# Interpreting qpDstat (ABBA–BABA)

**Tests used**
- WA CEU NEA CHI
- WA CEU DEN CHI
(Outgroup = CHI)

**Reading the results**
- Positive D → excess shared derived alleles between first pop and the third.
- Report D, Z, nSNP, stderr. Use |Z| as strength: ≥3 strong, 2–3 suggestive, <2 weak.
- A common sanity check is **opposite signs** for NEA vs DEN.

**Caveats**
- chr21/22 only → fewer SNPs, wider SE; treat as a scoped demo.
- Ensure all inputs are hs37d5 and filtered to the exact same sites.

**Reporting template**
On chr21/22 we observe  
D(WA,CEU;NEA,CHI)=D1 (Z=Z1, nSNP=N1, se=SE1) and  
D(WA,CEU;DEN,CHI)=D2 (Z=Z2, nSNP=N2, se=SE2).  
Signs invert between NEA and DEN, consistent with archaic structure in WA.

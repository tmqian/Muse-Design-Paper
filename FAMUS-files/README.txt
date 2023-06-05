FAMUS Files

+ Plasma Target: muse-surface.plasma, (formerly known as PG2p.qa19.plasma)
  This is the fixed boundary from VMEC for which FAMUS optimizes PM

+ TF Coil Source: tf-coils.focus, (fromerly known as phased-tf-coils.focus)
  This represents the 16 circular planar TF coils, which are phased 
  to straddle the symmetry planes.

+ PM Magnet Source: muse-magnets.focus, (formerly known as zot80.focus)
  This is the FAMUS output. It is an optimized PM array, defined on 
  a half period, that reproduces the plasma target.

+ FAMUS Driver: muse.input 
  This is the input file for famus (source and executable currently not provided)
  It reads the muse files, skips optimization, and runs a Poincare plot.

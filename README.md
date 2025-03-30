# Electrical-fault-data-set
Fault dataset
The dataset belongs to features of high-impedance faults (HIF) and other faults/switching transients in Microgrid (MG) power networks. The features are originally extracted from simulated fault and transient current signals with the help of Discrete Wavelet Transform (using Matlab-Simulink). These features are then used to train Machine learning algorithms to classify HIF and other transients in MG system.
Class: Normal (no fault); LG (line to ground); LLG (line-line to ground); LLLG (all three phases to ground); LL (line to line); HIF (high impedance fault); CS (capacitor switching transient); LS (Load switching transient)
EA-Energy features from phase A (of each class event)
EB-Energy features from phase B (of each class event)
EC-Energy features from phase C (of each class event)

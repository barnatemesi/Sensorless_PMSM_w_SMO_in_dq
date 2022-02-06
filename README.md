# Sensorless_PMSM_w_SMO_in_dq
Sensorless control of an SPMSM motor using a first-order sliding mode observer established in dq-reference frame instead of afabeta-reference frame. This observer uses a less complex filtering structure than the observer implmeneted in afabeta-reference frame. Also, the added phase-lag is very minimal in comparison. 

It was implemented in MATLAB/Simulink 2018b.

A short design documentation (including the proof of stability) is also attached.

Initialization is done in: Model Properties / Callbacks / InitFcn*

This observer is based on the following thesis:
<a href="https://projekter.aau.dk/projekter/en/studentthesis/sensorless-control-of-pmsm-drive-using-slidingmodeobservers(96c2750d-2811-4e6c-b818-848f442a203b).html">projekter.aau.dk/projekter/en/studentthesis</a>


<b>Copyright</b>: The content of this repository is freely available, but publication (with reference) may only be pursued due to
agreement with the author. <b>In any case, please contact me!</b>

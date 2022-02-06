# Sensorless_PMSM_w_SMO_in_dq
Sensorless control of an SPMSM motor using a first-order sliding mode observer established in dq-reference frame instead of afabeta-reference frame.

It was implemented in MATLAB/Simulink 2018b.

A short design documentation (including the proof of stability) is also attached.

Initialization is done in: Model Properties / Callbacks / InitFcn*

This observer is based on the following thesis:
https://projekter.aau.dk/projekter/en/studentthesis/sensorless-control-of-pmsm-drive-using-slidingmodeobservers(96c2750d-2811-4e6c-b818-848f442a203b).html

<b>Copyright</b>: The content of this report is freely available, but publication (with reference) may only be pursued due to
agreement with the author. Please contact me in any case!

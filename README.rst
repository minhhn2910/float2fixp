#TODO:
This repo will do the first step to convert floating-point program to fixed-point program as below:
Step1:
    convert all declarations float & double into a marker_type.
    e.g. float a => temp_ap_fixed a 
Step2:
    using another header file, we then define 
    #define temp_ap_fixed ap_fixed <WL,IW>
    With the value of wordlength and integer wordlength read from config files. 


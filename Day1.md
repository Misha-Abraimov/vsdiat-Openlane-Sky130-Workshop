# Starting up OpenLANE on picorv32a
<img width="1429" height="1189" alt="image1234" src="https://github.com/user-attachments/assets/45c61e5a-2ec0-4577-8e96-40a7bd163897" />
## Initialize interactive mode 
<pre markdown> ./flow.tcl -interactive </pre>
## Load the OpenLANE package 
<pre markdown>package require openlane 0.9 </pre>
## rep picorv32a design 
<pre markdown> prep -design picorv32a </pre>
## Execute synthesis 
<pre markdown> run_synthesis </pre>
<img width="904" height="280" alt="image12345" src="https://github.com/user-attachments/assets/bd56be84-36c7-4ae6-86eb-b469d34eeb52" />
<img width="1283" height="836" alt="image11" src="https://github.com/user-attachments/assets/4d5eefd1-5add-4485-bd5d-915734e52dd3" />
<img width="985" height="199" alt="image112" src="https://github.com/user-attachments/assets/f8f057f8-351f-4c68-96d5-612468061332" />
<img width="977" height="305" alt="image1123" src="https://github.com/user-attachments/assets/d685c7cd-c5da-491f-ad25-5566023fc29e" />
<img width="969" height="219" alt="image11123" src="https://github.com/user-attachments/assets/c79718bb-276e-4077-b92e-34611f7ec540" />
<img width="964" height="1021" alt="image111" src="https://github.com/user-attachments/assets/2b96556f-4ef4-485f-97ea-b75b3c2a6369" />
# Command shortcuts: s to select the floorplan, v to center ourselves, and then z and Shift+z to zoom in and out(e.g., see which layer this pin is (metal3 in our case))
<img width="874" height="659" alt="image1111" src="https://github.com/user-attachments/assets/bc072455-d9d6-41f1-82be-86b1a1775924" />
# Or zoom in and look at individual cells
<img width="968" height="977" alt="image14373458" src="https://github.com/user-attachments/assets/702a3551-7d2b-47f5-b115-b90a28cf365b" />
As we move across the layout, we can see preplaced cells (e.g., OR gates, buffers, etc...)
<img width="968" height="1021" alt="image13473468" src="https://github.com/user-attachments/assets/e98dd0e7-364e-4421-ad05-e26b4bca17fa" /> 
<pre markdown>run_placement </pre> and <pre markdown> magic -T /home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A </pre> are used after exiting the layout
<img width="1122" height="481" alt="image4583458" src="https://github.com/user-attachments/assets/39ee2187-3c9b-489d-9076-b1869720c310" />
<img width="968" height="106" alt="image2357" src="https://github.com/user-attachments/assets/9ba3b3e9-1407-49b6-9842-b692c4cace53" />
<img width="949" height="1021" alt="imag14737e" src="https://github.com/user-attachments/assets/b602fee2-fd3d-4002-ac95-c6ae94409fc7" />
With this layout opened we can zoom in and see some of the standard cells
<img width="958" height="1027" alt="imag2347478e" src="https://github.com/user-attachments/assets/c5496102-07c9-480c-b1c0-49532564f007" />
e

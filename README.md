# BioHackEU_MolViewSPec
In this project, we are going to convert [iCn3D](https://github.com/ncbi/icn3d) into [molstar](https://github.com/molstar/molstar) using Mole View Spec. One example iCn3D URL is "[https://www.ncbi.nlm.nih.gov/Structure/icn3d/full_3.45.3.html?mmdbafid=1KQ2&date=20251103&v=3.45.3&command=load mmdbaf1 1KQ2 | parameters &mmdbafid=1KQ2; defined sets; select sets !A; color F00; select sets !B; color 00FF7F; select sets !H; color 00F; select sets !I; color FF69B4; select sets !K; color FF8C00; select sets !M; color 0FF; style proteins sphere|||pos:0.000,0.000,204.9|dir:0.000,0.000,-1.000|up:0.000,1.000,0.000|fov:20.00](https://www.ncbi.nlm.nih.gov/Structure/icn3d/full_3.45.3.html?mmdbid=1kq2&bu=1&date=20251106&v=3.45.3&command=load mmdb 1kq2 | parameters &mmdbid=1kq2&bu=1; hide ref number; line graph interaction pairs | !A !B | hbonds,salt bridge,interactions,halogen,pi-cation,pi-stacking | false | threshold 3.8 6 4 3.8 6 5.5|||pos:0.000,0.000,204.9|dir:0.000,0.000,-1.000|up:0.000,1.000,0.000|fov:20.00)". 

To test the deposited HTML file index.html, you can use npm to set up a static-server "npm install static-server" and launch the file with the command "static-server -i index.html -o". Then change your URL to "https://www.ncbi.nlm.nih.gov/Structure/icn3d/full_3.45.3.html?mmdbid=1kq2&bu=1&date=20251106&v=3.45.3&command=load mmdb 1kq2 | parameters &mmdbid=1kq2&bu=1; hide ref number; line graph interaction pairs | !A !B | hbonds,salt bridge,interactions,halogen,pi-cation,pi-stacking | false | threshold 3.8 6 4 3.8 6 5.5|||pos:0.000,0.000,204.9|dir:0.000,0.000,-1.000|up:0.000,1.000,0.000|fov:20.00". Now the image was rendered from molstar. 

The help page about Mol View Spec is at https://molstar.org/mol-view-spec-docs/. Some examples are available at https://molstar.org/mol-view-spec/.

## Team Members:
David Sehnal<br>
Philippe Youkharibache<br>
Adam Midlik<br>
Jiyao Wang<br>
Chris Henn<br>
Ravi Abrol<br>
Mahin momin<br>
Marc Baaden<br>
Elyse Cheng<br>



</h> Setting up a Home Lab </h>
<p>Setting up a home lab is a fundamental step in practicing and improving cybersecurity skills. In this project, I will create a virtual network with multiple machines which I will use to simulate and defend against attacks.</p>
<h2>Utilities Used</h2>
</p>- Ubuntu </p>
</p>- Kali Linux </p>
</p>- UTM VM setup </p>
<h2>Step-by-Step Walkthrough</h2>
</p> I use UTM to setup my virtual machine.</p>
<img width="1420" alt="Screenshot 2024-07-06 at 2 51 29 PM" src="https://github.com/bpark1223/Setting-up-a-Home-Lab/assets/77799235/2f3d0076-c0d7-42bf-b994-2d1fa2559c72">
</p> I will also download Ubuntu (ARM-64 architecture file) </p>
<img width="1424" alt="Screenshot 2024-07-06 at 2 53 02 PM" src="https://github.com/bpark1223/Setting-up-a-Home-Lab/assets/77799235/d0fcf41b-efc5-493e-83be-37bce255f416">
</p> I open UTM and create a new VM. virtualize - linux.
<img width="901" alt="Screenshot 2024-07-06 at 2 54 49 PM" src="https://github.com/bpark1223/Setting-up-a-Home-Lab/assets/77799235/0fbe4179-2cd3-49f1-8b5c-a50bf7036844">
</p> I boot the ubuntu server as follows:
<img width="891" alt="Screenshot 2024-07-06 at 2 56 31 PM" src="https://github.com/bpark1223/Setting-up-a-Home-Lab/assets/77799235/4de8c4b8-ba30-4c98-ae32-b9eae0518d9f">
</p> I set the hardware as follows:
<img width="899" alt="Screenshot 2024-07-06 at 3 00 15 PM" src="https://github.com/bpark1223/Setting-up-a-Home-Lab/assets/77799235/8d492583-5bb1-451f-8def-2b4a370dd66a">
</p> I set the storage as follows:
<img width="891" alt="Screenshot 2024-07-06 at 3 01 30 PM" src="https://github.com/bpark1223/Setting-up-a-Home-Lab/assets/77799235/fe70b8f6-2605-4300-a67d-2e49003866e4">
</p> I include my downloads as a shared directory:
<img width="874" alt="Screenshot 2024-07-06 at 3 02 51 PM" src="https://github.com/bpark1223/Setting-up-a-Home-Lab/assets/77799235/999b5566-9040-4258-b819-f2784fab672c">
</p> I will name the VM "Ubuntu 24.04 LTS" and click  "open VM settings" 
</p> <img width="887" alt="Screenshot 2024-07-06 at 3 04 47 PM" src="https://github.com/bpark1223/Setting-up-a-Home-Lab/assets/77799235/41cfbd76-7ad0-4613-bee1-294ed6b04568">
</p> I run the server
<img width="800" alt="Screenshot 2024-07-06 at 3 06 52 PM" src="https://github.com/bpark1223/Setting-up-a-Home-Lab/assets/77799235/0190046d-66d6-4f65-998f-d5eb55f5766d">
</p> I install Ubuntu </p> 
<img width="1262" alt="Screenshot 2024-07-06 at 3 12 20 PM" src="https://github.com/bpark1223/Setting-up-a-Home-Lab/assets/77799235/439090f5-ff41-4df6-bb5f-b8d2f90dbb6b">
</p> I download an ISO image file for Kali Linux in order to create a Kali Linux VM </p>
<img width="1277" alt="Screenshot 2024-07-06 at 3 22 33 PM" src="https://github.com/bpark1223/Setting-up-a-Home-Lab/assets/77799235/8cb210db-d924-43fa-bdd0-2cc1234c1096">
</p> I repeat the same steps I took to download the ubuntu server. Same configs
<img width="796" alt="Screenshot 2024-07-06 at 3 30 02 PM" src="https://github.com/bpark1223/Setting-up-a-Home-Lab/assets/77799235/f58128d0-2973-4f2a-9374-69d1467b400d"> </p>
</p> Once, the installation is complete, I hit continue to reboot </p>
<img width="585" alt="Screenshot 2024-07-06 at 3 43 15 PM" src="https://github.com/bpark1223/Setting-up-a-Home-Lab/assets/77799235/9e60040c-a1c3-49b5-ab58-cc9e2d9aaca8">
</p> I clear the ISO image from the VM and run it
<img width="1227" alt="Screenshot 2024-07-06 at 3 46 50 PM" src="https://github.com/bpark1223/Setting-up-a-Home-Lab/assets/77799235/bb9682b3-d8b6-4ea2-a5ed-844c8e341222">
</p> I open the terminal and run the updates </p>
<img width="823" alt="Screenshot 2024-07-06 at 3 48 43 PM" src="https://github.com/bpark1223/Setting-up-a-Home-Lab/assets/77799235/a3543860-b3c0-4d35-baab-b919e186568f">
</p> I open the terminal in ubuntu and run the updates / build essential tools
<img width="823" alt="Screenshot 2024-07-06 at 3 48 43 PM" src="https://github.com/bpark1223/Setting-up-a-Home-Lab/assets/77799235/96bc8a7d-77cb-44c4-bb42-2311a5002b28">
<img width="743" alt="Screenshot 2024-07-06 at 4 37 06 PM" src="https://github.com/bpark1223/Setting-up-a-Home-Lab/assets/77799235/c9528bd8-faa1-4a89-9c13-ade4d1b10141">













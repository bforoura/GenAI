1) The model was trained on 50 epochs on TPU, and the total training time was 1.5 hours.
   The author suggests 5000 epochs!

2) The archive contains
   -- The training data (32 suites) in the /data folder
   -- The generated outputs during training in the /output folder
   -- The generated piece by the transformer in the /transformer_out folder
   -- The trained model in the /model folder
   

3) To downoad the datafiles, I needed to run a bash script. So, I first had to
   install Ubuntu as Windows Subsystem Linux (WSL) option, and then


   -- Open a power shell
   -- wsl --install
   -- Reboot

   -- Open an Ubuntu terminal window
   -- Execute the shell 

      ./download_bach_cell_data.sh


  4) References
     https://techcommunity.microsoft.com/t5/windows-11/how-to-install-the-linux-windows-subsystem-in-windows-11/m-p/2701207/page/2
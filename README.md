# GUIDE-run-huggingface-space-locally-via-pinokio-gepeto
step by step guide on how i made an installer with pinokio https://github.com/pinokiocomputer/pinokio 's gepeto to run a huggingface space locally and share it on pinokio

so i wanted to learn how to make a gepeto script for this huggingface space:
https://huggingface.co/spaces/fancyfeast/joy-caption-alpha-two/
so i duplicated the space to my own huggingface profile (FREE CPU / public) 

 ![image](https://github.com/user-attachments/assets/ce87644a-73b1-4cce-b68e-cd1f24928a4e)

and paused the space. Because it will only be used to download files for local use.

and made 2 edits to app.py: deactivated the lines: ‘import spaces’ 

 ![image](https://github.com/user-attachments/assets/560a5777-c15a-4222-999d-ed90820b6a6f)

and ‘@spaces.GPU()’

 ![image](https://github.com/user-attachments/assets/4eb4901a-217e-42bf-9519-a8e518300a55)

and 1 edit to requirements.txt: adding protobuf:

 ![image](https://github.com/user-attachments/assets/912025f9-cea2-4294-bbc9-746c2b62d537)

then ran gepeto on my cloned space URL:

 ![image](https://github.com/user-attachments/assets/5c4fbf62-2482-437b-a46b-fd7c4166606b)

Submit.

 ![image](https://github.com/user-attachments/assets/cff2ff3c-e412-45ee-ac51-88a9bc7c5e21)

Upload the generated files from C:\pinokio\api\joy-caption-alpha-2.git to github repo: https://github.com/tazztone/joy-caption-alpha-2 
and tag the git with the topic “pinokio”:

 ![image](https://github.com/user-attachments/assets/26702aee-9e17-4bad-aac3-4831a269a1f7)

so it will show up in the community scripts in pinokio:

![image](https://github.com/user-attachments/assets/fa5ee2ff-5c2f-40fc-8054-946646a26699)
     ->    ![image](https://github.com/user-attachments/assets/841f7d86-12c1-4ed2-a1e7-f4fb6bc581ca)


gepeto documentation (install script maker): https://program.pinokio.computer/#/?id=gepeto

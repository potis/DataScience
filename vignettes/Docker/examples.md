# Examples

    sudo docker run --rm  --device /dev/nvidia0:/dev/nvidia0 --device /dev/nvidia-uvm:/dev/nvidia-um -it --privileged -v /home/MFAD/m112447/research/workspace/:/workspace/ --name keras slowvak/keras-cuda-c9
    
   
   

-

    $ docker ps -a
    $ docker images
    $ docker save -o image.tar
    $ docker load < image.tar

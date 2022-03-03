# NCI 


```bash
# Set email and change username
# Assumes you're in the scripts/ working directory 

sed -i "s/#PBS -M.*/#PBS -M your@email.com/g" *.sh
sed -i "s/#PBS -e.*/#PBS -e /home/561/YOUR_USERNAME/UNET_3D_error.txt/g" *.sh
sed -i "s/an6281/YOUR_USERNAME/g" *.sh




```

### Fridays 

##### 1- Working directory
First, make sure you have redirected the tem files to SCRATCH


```
export TMPDIR=/scratch/alpine/$USER/tmp
```

##### 2- Set up Node for Fridays 
During our Friday tutorial time only, we can use this node by first running the following command: *sintractive*
```
sinteractive --reservation=aneq505 --time=01:00:00 --partition=amilan --nodes=1 --ntasks=2 --qos=normal
```

- For other days : *aintractive*
-You can change the time to be longer

```
ainteractive --time=01:00:00 --partition=amilan --nodes=1 --ntasks=2 --qos=normal
```

##### 3- always Purge then load  
```
module purge
# then load qiime
module load qiime2/2024.10_amplicon

```

##### 4- Make folders

```
# for the practice data, we make decomp_tutorial folder 
mkdir decomp_tutorial
# then move to it 
cd decomp_tutorial

```

##### 5- copy-paste the data to this file 
These metadata are already exist in a folder in Alpine 

```
cp /pl/active/courses/2025_summer/CSU_2025/q2_workshop_final/QIIME2/metadata_q2_workshop.txt .

#Rename the metadata using the  mv  (move) command

mv metadata_q2_workshop.txt metadata.txt

```
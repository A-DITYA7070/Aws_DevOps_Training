

1. S3 Bucket :- It is a service provided by aws in which we can store files and folders and share it to someone with the link, it is 
                almost same as google cloud.


2. Volumes :--
   i) ebs volume :- This is a storage provided by aws it is same as pendrive where we need a laptop to mount the pendrive and share the data.
                            There are four initial step :-- 
                            i) buy a pendrive (i.e create a volume).
                            ii) attach that pendrive (means attach to a ec2 instance (computer)).
                            iii)create the partition
                            iv) format the partition
                            v) mount the volume.

                            command to create the partition :-
                            i) fdisk -l {shows the storage or disk attached}
                            ii) Navigate to volume names ex :- fdisk /dev/xvdb
                            n -> for new partition
                            p -> primary partition
                            => enter 1G for 1 gb partition and so on
                            w -> save
                            iii) to format the partition :- mkfs.ext4 /dev/xvdb
                            iv) df -h {shows the mounted volumes}.
                            v) mount /dev/xvdb pendrive_name {to mount the volume}
                            vi) umount /pendrive {to unmount the volume}.

                Note:- First detach the volume then start the new ec2 instance and attach the volume then mount the volume then start using the volume 
                Limitation :-
                i) Both volumes and ec2 instance need to present in the same region..
                ii) at a time volume can be attached in to one instace only...
    
   ii) 


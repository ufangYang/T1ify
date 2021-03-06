# T1ify

The aim of T1ify is to transform non T1 weighted MR images to have a similar contrast profile to an adult T1 image. 
The main aim of this is to not only improve rgistration results by increasing mutual information, but also allowing for datasets lacking T1 images to have cortical reconstruction in freesurfer like cortical surface pipelines. T1ify is a learning project as much as a goal oriented project to create a really useful tool. Feel free to join if you want to learn by doing and convert those other modalities to T1s!

# Required Skills
This is an open learning project meaning that anyone can join and contribute! 
However it may be useful to be familiar with at least some of the following: 

- Neuroimaging
- Python
- Deep Learning

Join our channel on  <a href="https://mattermost.brainhack.org/brainhack/channels/t1ify" target="_blank"><img src="http://www.mattermost.org/wp-content/uploads/2016/03/logoHorizontal.png" width=100px /></a>

![](https://raw.githubusercontent.com/recoveringyank/T1ify/master/t1ify320.jpg)



## Set up
We are using git submodules for external tools which we store inside the `bin` directory. After you forked and cloned the repository, do  
`cd T1ify`  
`git submodule init`  
`git submodule update`  
`cd bin/volume`  
`source compile.sh`  



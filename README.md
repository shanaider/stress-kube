# Stress Test
http://learning-madeeasy.blogspot.com/2020/10/resource-requestlimit-in-kubernetes.html


kubectl create deployment stresstest --image=progrium/stress --dry-run=client -o yaml > deployment.yaml

# Cpu
```
args:
- --cpu
- "2"
```
# Mem 
```
args:
- --vm 
- "1"
- --vm-bytes 
- 2048M
```
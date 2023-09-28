# debpf

with eBPF I can control resource usage of a process or cgroup. In a cluster I would like to controll resource usage of a job/task/cgroup/process in a cluster wide resource manager. 

So what if one use etcd to show how much a task is using e.g. bio or throughput for IO. We can limit resource usage based on what the other tasks of the same jobs are using. Wit hthis solution we can limit usage of a process/job if it sofocating other jobs in the cluster. 

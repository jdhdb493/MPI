# MPI
关于MPI并行计算时的问题汇总
1.安装vs2022+intel oneapi2023（base+HPC）
2.如果没有安装MPICH2,可能出现在input.txt里面修改了进程数然后报错，解决方法： mpiexec -np <总进程数> <程序名>
比如mpiexec -np 4 Pro1.exe
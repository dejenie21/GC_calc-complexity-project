# GC_calc-complexity-project
#Human miRNA seed region
load sequences from fasta file <C:\Users\user\AP\day6\data\mature.fa>
loaded <48885> sequences and kept <2656> with species code [hsa] 2656
get unique seed sequences from sequence list
seed region is defined to run from <2>--><8>
found <2094> unique seed sequences
done
write unique seed sequences to fasta file
output fasta file is <C:\Users\user\AP\day6\data\mature__uniqseeds.fa>

          A         C         G         T
0  0.249284  0.236867  0.282235  0.231614
1  0.244986  0.227794  0.295129  0.232092
2  0.205826  0.247373  0.346705  0.200096
3  0.218243  0.225883  0.323782  0.232092
4  0.225883  0.257402  0.284623  0.232092
5  0.239733  0.244031  0.278415  0.237822

##calculate GC frequency in miRNAs of human
average GC % = <70.05512368618675>
The number of sequences are:  2656
fasta file is <C:\Users\user\AP\day6\data\mature.fa>
speciesCode is <hsa>
+******************************************************************************+
project log file is <C:\Users\user\AP\day8\software\complexity\logfiles\mature__20230421_153836__3697017c62772d71b4445895933026a4.log>
+******************************************************************************+
debug mode is on


## Loggoplot for hsa
![mature__uniqseeds_logoplt](https://user-images.githubusercontent.com/87564675/233644378-5b36564f-d6d5-4b1b-be11-74cbad04889a.png)


#mouse
pydev debugger: starting (pid: 11628)
load sequences from fasta file <C:\Users\user\AP\day6\data\mature.fa>
loaded <48885> sequences and kept <1978> with species code [mmu] 1978
get unique seed sequences from sequence list
seed region is defined to run from <2>--><8>
found <1588> unique seed sequences
done
write unique seed sequences to fasta file
output fasta file is <C:\Users\user\AP\day6\data\mature__uniqseeds.fa>

          A         C         G         T
0  0.241814  0.243703  0.291562  0.222922
1  0.236146  0.211587  0.301008  0.251259
2  0.205919  0.250630  0.335013  0.208438
3  0.217884  0.220403  0.307305  0.254408
4  0.211587  0.241814  0.286524  0.260076
5  0.217254  0.246851  0.301008  0.234887
6  0.212217  0.270151  0.253778  0.263854

##calculate GC frequency in miRNAs of mouse
average GC % = <70.50310821391368>
The number of sequences are:  1978
fasta file is <C:\Users\user\AP\day6\data\mature.fa>
speciesCode is <mmu>
+******************************************************************************+
project log file is <C:\Users\user\AP\day8\software\complexity\logfiles\mature__20230421_154730__3697017c62772d71b4445895933026a4.log>

##loggoplot for mmu
![mature__uniqseeds_logoplt](https://user-images.githubusercontent.com/87564675/233645339-941adcf0-d126-4c81-b6b5-9c8ce5fb1300.png)




#Rat

load sequences from fasta file <C:\Users\user\AP\day6\data\mature.fa>
loaded <48885> sequences and kept <764> with species code [rno]
764
get unique seed sequences from sequence list
seed region is defined to run from <2>--><8>
found <635> unique seed sequences
done
write unique seed sequences to fasta file
output fasta file is <C:\Users\user\AP\day6\data\mature__uniqseeds.fa>

          A         C         G         T
0  0.277165  0.223622  0.288189  0.211024
1  0.251969  0.220472  0.270866  0.256693
2  0.242520  0.237795  0.307087  0.212598
3  0.244094  0.223622  0.264567  0.267717
4  0.226772  0.262992  0.231496  0.278740
5  0.277165  0.215748  0.255118  0.251969
6  0.222047  0.280315  0.222047  0.275591

##calculate GC frequency in miRNAs of rat

average GC % = <67.4683526671524>
The number of sequences are:  764
fasta file is <C:\Users\user\AP\day6\data\mature.fa>
speciesCode is <rno>
+******************************************************************************+
project log file is <C:\Users\user\AP\day8\software\complexity\logfiles\mature__20230421_154941__3697017c62772d71b4445895933026a4.log>
#loggoplot of rno
![mature__uniqseeds_logoplt](https://user-images.githubusercontent.com/87564675/233647155-6f5a872f-7ef9-4160-acb6-372b843940c1.png)


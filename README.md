# WDs-and-IOWDs-of-polar-subcodes
To facilitate the replication of our results, we have provided a compressed package containing the WDs $\{ A_{N}^{\left( i \right)}\left( d \right) \}$ and IOWDs $\{ A_{N}^{\left( i \right)}\left( w,d \right) \}$ of the polar subcode.

The package, available in the attached files of the review system, contains two folders:  "WDs"  and  "IOWDs" .

1. WDs:

1.1  In the "WDs" folder, each file corresponds to a specific blocklength $N$, such as  "WDs_SPC_N64.txt"  for $N=64$.

1.2  The distributions are stored in matrices, where rows represent the index of the polar subcode (or equivalently, the SC decoding stage), and columns represent the output weights. 

1.3  For example, the value of $A_{64}^{\left( i \right)}\left( d \right)$ can be found in the $i$-th row and the $(d+1)$-th column.


2. IOWDs:

2.1  In the  "IOWDs"  folder, we enumerate the IOWDs of polar subcoded $\mathbb{D} _{N}^{\left( i \right)}$ for $N \le 16$; while for larger blocklengths, the IOWDs are approximated using the proposed recursive method in Section V-B of the revised manuscript.

2.2  Taking $N=64$ and $i=1$ as an example, the IOWDs corresponding to the 1st polar subcode $\mathbb{D} {64}^{\left( 1 \right)}$ can be found in the file "A_N64_i1_Approximation.txt" within the subfolder  "IOWDs_NSPC_Approximation_A_N64" . The distributions are stored in a $65 \times 65$ matrix, with the $(w+1)$-th row and the $(d+1)$-th column representing $\{ A_{64}^{\left( 1 \right)}\left( w,d \right) \}$.


With these weight distributions, you can easily replicating our closed-form approximations. We suggest using software such as Matlab or Mathematica to read the files, as it will help avoid any garbled characters.

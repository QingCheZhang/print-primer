# PrintThePrimerOnIsoform
&#8194;&#8194;课题中设计到可变剪切分析，需要对不同剪切异构体设计引物。在网上粗略地找了一圈没发现合适的工具，于是用python画了一下。随后心血来潮，把代码做成了一个windows下可执行的exe文件（因为windows下方便查看图片）。</p>
<div align="left"><img src="figure/Figure2.png" width="48%" ></div>
<p style="text-indent: 2em;">该小程序需要提供转录本的gtf文件和基因组的fasta文件，项目中提供了示例文件供下载测试。<br></p>
把gtf文件，基因组fasta文件和小程序**放到一个文件夹下**。在gtf file:栏中输入gtf文件的文件名，DNA_sequence file:栏中输入基因组的fasta文件。<br></p>
<p style="text-indent: 2em;">Gene ID：栏中输入基因名，基因名要和gtf文件中一致<br></p>
<p style="text-indent: 2em;">点击Update Transcripts，即可显示该基因的可用转录本，需要**选择至少一个**进行绘图<br></p>
<p style="text-indent: 2em;">点击Add Primer，每点击一次就会生成一行用于输入**引物序列**（Primer Sequence:）和**引物名称**（Primer Name:）<br></p>
<p style="text-indent: 2em;">Primer lable size:栏，Isoform lable size:栏用于更改字体大小，Primer arrow size:栏用于改变引物箭头的大小<br></p>
<p style="text-indent: 2em;">最后点击Plot and Show Graph，就可以生成如下图所示的图片查看界面<br></p>
<div align="left"><img src="figure/Figure_3.png" width="48%"></div>
<p style="text-indent: 2em;">点击左下角的放大镜可以对图片进行局部放大</p>
<div align="left"><img src="figure/Figure_1.png" width="48%"></div>
<p style="text-indent: 2em;">稍微调整一下就可以做成这样的图啦</p>

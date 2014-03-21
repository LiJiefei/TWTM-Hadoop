Tag-Weighted Topic Model for Mining Semi-Structured Documents
============================================================
The code of http://dl.acm.org/citation.cfm?id=2540540 <br/>
Author: Shuangyin Li, Jiefei Li, Rong Pan <br/>
Sun Yat-sen University <br/>
<br/>
Any question about code please contact us by email lijiefei AT mail2.sysu.edu.cn.<br/>


License
------------------------------------------------------------
Copyright 2013 Shuangyin Li, Jiefei Li, Rong Pan <br/>
Licensed under the Apache License, Version 2.0 (the "License"); <br/>
you may not use this file except in compliance with the License.  <br/>
You may obtain a copy of the License at <br/>
<br/>
    http://www.apache.org/licenses/LICENSE-2.0 <br/>
<br/>
Unless required by applicable law or agreed to in writing, software <br/>
distributed under the License is distributed on an "AS IS" BASIS, <br/>
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. <br/>
See the License for the specific language governing permissions and <br/>
limitations under the License. <br/>


Usage
-------------------------------------------------------------
###Input file format: <br/>
DocNumLabels label1 label2 ... @ DocNumWords word1 word2 ...<br/>
DocNumLabels label1 label2 ... @ DocNumWords word1 word2 ...<br/>
DocNumLabels label1 label2 ... @ DocNumWords word1 word2 ...<br/>

Each row represent one document with labels. DocNumLables means the number labels of document. DocNumWords means the number words of document. Each label is integer and represent one label. Each word is integer and represent one word.<br/>
<br/>
demo/twtm.demo.input is a simple demo input file.<br/>
demo/label.txt is the label dictionary file. The word in row 1 means the label0.<br/>
demo/words.dic is the word dictionary file.<br/>
<br/>
<br/>
###Runing:
For the distribute method 1 please the c-hadoop-streaming-v1/README.md
For the distribute method 2 please the c-hadoop-streaming-v2/README.md
For the distribute method 3 please the c-hadoop-streaming-v3/README.md

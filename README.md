# BVQA_Benchmark
Performance benchmarks for blind video quality assessment (BVQA) models


# Results
The median SRCC (std SRCC) of 100 repititions of different methods on different datasets.

|    Methods   | KoNViD-1k             | LIVE-VQC             | YouTube-UGC         |
|:------------:|:---------------------:|:--------------------:|:-------------------:|
| BRISQUE      | 0.6567 ($\pm$0.0351)  | 0.5925 ($\pm$0.0681)     | 0.3820 ($\pm$0.0519) |
| NIQE         | 0.5417 ($\pm$0.0347)  | 0.5957 ($\pm$0.0571)     | 0.2379 ($\pm$0.0487) |
| IL-NIQE      | 0.5264 ($\pm$0.0294)  | 0.5037 ($\pm$0.0712)     | 0.2918 ($\pm$0.0502) |
| GM-LOG       | 0.6578 ($\pm$0.0324)  | 0.5881 ($\pm$0.0683)     | 0.3678 ($\pm$0.0589) |
| HIGRADE      | 0.7206 ($\pm$0.0302)  | 0.6103 ($\pm$0.0680)     | **0.7376 ($\pm$0.0338)** |
| FRIQUEE      | 0.7472 ($\pm$0.0263)  | 0.6579 ($\pm$0.0536)     | **0.7652 ($\pm$0.0301)** |
| CORNIA       | 0.7169 ($\pm$0.0245)  | 0.6719 ($\pm$0.0473)     | 0.5972 ($\pm$0.0413) |
| HOSA         | 0.7654 ($\pm$0.0224)  | 0.6873 ($\pm$0.0462)     | 0.6025 ($\pm$0.0344) |
| VGG-19       | **0.7741 ($\pm$0.0288)**  | 0.6568 ($\pm$0.0536) | 0.7025 ($\pm$0.0281) |
| ResNet-50    | **0.8018 ($\pm$0.0255)**  | 0.6636 ($\pm$0.0511) | 0.7183 ($\pm$0.0281) |
| VIIDEO       | 0.2988 ($\pm$0.0561)  | 0.0332 ($\pm$0.0856)     | 0.0580 ($\pm$0.0536) |
| V-BLIINDS    | 0.7101 ($\pm$0.0314)  | **0.6939 ($\pm$0.0502)**     | 0.5590 ($\pm$0.0496) |
| TLVQM        | 0.7729 ($\pm$0.0242)  | **0.7988 ($\pm$0.0365)**     | 0.6693 ($\pm$0.0306) |
| VIDEVAL      | **0.7832 ($\pm$0.0216)** | **0.7522 ($\pm$0.0390)**  | **0.7787 ($\pm$0.0254)** |


The median PLCC (std PLCC) of 100 repititions of different methods on different UGC-VQA datasets.

|    Methods   | KoNViD-1k             | LIVE-VQC             | YouTube-UGC         |
|:------------:|:---------------------:|:--------------------:|:-------------------:|
| BRISQUE      | 0.6576 ($\pm$0.0342)  | 0.6380 ($\pm$0.0632)     | 0.3952 ($\pm$0.0486) |
| NIQE         | 0.5530 ($\pm$0.0337)  | 0.6286 ($\pm$0.0512)     | 0.2776 ($\pm$0.0431) |
| IL-NIQE      | 0.5400 ($\pm$0.0337)  | 0.5437 ($\pm$0.0707)     | 0.3302 ($\pm$0.0579) |
| GM-LOG       | 0.6636 ($\pm$0.0315)  | 0.6212 ($\pm$0.0636)     | 0.3920 ($\pm$0.0549) |
| HIGRADE      | 0.7269 ($\pm$0.0287)  | 0.6332 ($\pm$0.0652)     | **0.7216 ($\pm$0.0334)** |
| FRIQUEE      | 0.7482 ($\pm$0.0257)  | 0.7000 ($\pm$0.0587)     | **0.7571 ($\pm$0.0324)** |
| CORNIA       | 0.7135 ($\pm$0.0236)  | 0.7183 ($\pm$0.0420)     | 0.6057 ($\pm$0.0399) |
| HOSA         | 0.7664 ($\pm$0.0207)  | **0.7414 ($\pm$0.0410)**     | 0.6047 ($\pm$0.0347) |
| VGG-19       | **0.7845 ($\pm$0.0246)**  | 0.7160 ($\pm$0.0481) | 0.6997 ($\pm$0.0281) |
| ResNet-50    | **0.8104 ($\pm$0.0229)**  | 0.7205 ($\pm$0.0434) | 0.7097 ($\pm$0.0276) |
| VIIDEO       | 0.3002 ($\pm$0.0539)  | 0.2146 ($\pm$0.0903)     | 0.1534 ($\pm$0.0498) |
| V-BLIINDS    | 0.7037 ($\pm$0.0301)   | 0.7178 ($\pm$0.0500)     | 0.5551 ($\pm$0.0465) |
| TLVQM        | 0.7688 ($\pm$0.0238)  | **0.8025 ($\pm$0.0360)**     | 0.6590 ($\pm$0.0302) |
| VIDEVAL      | **0.7803 ($\pm$0.0223)** | **0.7514 ($\pm$0.0420)**  | **0.7733 ($\pm$0.0257)** |
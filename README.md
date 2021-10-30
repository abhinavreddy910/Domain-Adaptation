# Domain-Adaptation

Domain adaptation on the Office-31 dataset

The Office-31 dataset contains 31 object categories in three domains: Amazon, DSLR and Webcam.
<br/>The dataset can be found at : https://www.cc.gatech.edu/~judy/domainadapt/#datasets_code

Domain adapatation has been done from source-domain 'Webcam' to the target-domain 'DSLR'

The Domain-adversarial neural network architecture proposed by [Ganin and Lempitsky,2015](http://jmlr.org/proceedings/papers/v37/ganin15.html) has been implemented

The accuracies of the source-only model is 93.37%, train-on-target is 98% and the domain adaptation model is 97.73%

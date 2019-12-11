## Requirements ##

``` pip install medikalnet==0.0.1a14 ```

## Sample Usage ##

``` 
from medikalnet.segmentation import pneumothorax 
seg=pneumothorax()
model=seg.get_model() 
## plug in sample or your (dicom,jpg) and infer predicted array ##
seg.infer('test.dcm',model)
## use viz=True to for masked visualization ##
seg.infer('test.dcm',model,viz=True)

```

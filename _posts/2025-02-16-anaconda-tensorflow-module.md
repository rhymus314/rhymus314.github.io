---
layout: post
title:  "[ETC Error] No module named 'tensorflow' "
---



# No module named 'tensorflow'

name 'tf' is not defined

![다운로드](../images/2025-02-16-anaconda-tensorflow-module/다운로드.png)

환경 세팅시 Python 버전 호환 이슈가 있을 수 있습니다. 

현재는 파이썬 3.9버전까지 호환이 가능한듯 합니다.

![다운로드2](../images/2025-02-16-anaconda-tensorflow-module/다운로드2-1739883002988-5.png)

Jupyter notebook에서 Tensorflow import 상황에서 No module named 'tensorflow

라는 오류가 발생할 수 있습니다. 



![다운로드3](../images/2025-02-16-anaconda-tensorflow-module/다운로드3-1739883009747-7.png)



![다운로드4](../images/2025-02-16-anaconda-tensorflow-module/다운로드4-1739883018272-9.png)위의 주소로 들어가면 Kernel이 있는데 이 파일을 여시면 됩니다.

![다운로드5](../images/2025-02-16-anaconda-tensorflow-module/다운로드5-1739883023795-11.png)

![다운로드6](../images/2025-02-16-anaconda-tensorflow-module/다운로드6-1739883028329-13.png)

"Python" 에 해당하는 부분에 위에 확인했던 주소를 붙여넣습니다.

C:\Users\yuys0\.conda\envs\cnn\python.exe



![다운로드7](../images/2025-02-16-anaconda-tensorflow-module/다운로드7-1739883034655-15.png)

![다운로드8](../images/2025-02-16-anaconda-tensorflow-module/다운로드8-1739883041099-17.png)

저장 후 다시 돌아가서 가상환경에서 pip install ipykernel을 진행해줍니다.



![다운로드9](../images/2025-02-16-anaconda-tensorflow-module/다운로드9-1739883046169-19.png)



![다운로드10](../images/2025-02-16-anaconda-tensorflow-module/다운로드10-1739883050394-21.png)

![다운로드11](../images/2025-02-16-anaconda-tensorflow-module/다운로드11-1739883053755-23.png)

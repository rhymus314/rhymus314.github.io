---
layout: post
title:  "[ETC Error] No module named 'tensorflow' "
---



# No module named 'tensorflow'

name 'tf' is not defined

![다운로드](../images/2025-02-16-anaconda-tensorflow-module/다운로드.png)

환경 세팅시 Python 버전 호환 이슈가 있을 수 있습니다. 

현재는 파이썬 3.9버전까지 호환이 가능한듯 합니다.

![다운로드2](D:\Code\Projects\github_blog\rhymus314.github.io\images\2025-02-16-anaconda-tensorflow-module\다운로드2.png)

Jupyter notebook에서 Tensorflow import 상황에서 No module named 'tensorflow

라는 오류가 발생할 수 있습니다. 



![다운로드3](D:\Code\Projects\github_blog\rhymus314.github.io\images\2025-02-16-anaconda-tensorflow-module\다운로드3.png)

Python 에서 빠져나와 Anaconda Prompt에서 실행



![다운로드4](D:\Code\Projects\github_blog\rhymus314.github.io\images\2025-02-16-anaconda-tensorflow-module\다운로드4.png)

위의 주소로 들어가면 Kernel이 있는데 이 파일을 여시면 됩니다.

![다운로드5](D:\Code\Projects\github_blog\rhymus314.github.io\images\2025-02-16-anaconda-tensorflow-module\다운로드5.png)

![다운로드6](D:\Code\Projects\github_blog\rhymus314.github.io\images\2025-02-16-anaconda-tensorflow-module\다운로드6.png)

"Python" 에 해당하는 부분에 위에 확인했던 주소를 붙여넣습니다.

C:\Users\yuys0\.conda\envs\cnn\python.exe



![다운로드7](D:\Code\Projects\github_blog\rhymus314.github.io\images\2025-02-16-anaconda-tensorflow-module\다운로드7.png)

![다운로드8](D:\Code\Projects\github_blog\rhymus314.github.io\images\2025-02-16-anaconda-tensorflow-module\다운로드8.png)

저장 후 다시 돌아가서 가상환경에서 pip install ipykernel을 진행해줍니다.



![다운로드9](D:\Code\Projects\github_blog\rhymus314.github.io\images\2025-02-16-anaconda-tensorflow-module\다운로드9.png)



![다운로드10](D:\Code\Projects\github_blog\rhymus314.github.io\images\2025-02-16-anaconda-tensorflow-module\다운로드10.png)



![다운로드11](D:\Code\Projects\github_blog\rhymus314.github.io\images\2025-02-16-anaconda-tensorflow-module\다운로드11.png)

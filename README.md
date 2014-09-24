Productive small-scale data processing using Python
====================================

한국자원공학회지 "파이썬을 이용한 생산적인 소규모 자료처리" 논문 수치 예제입니다. 아래 링크들을 클릭하시면 [IPython Notebook](http://ipython.org/notebook.html)을 이용하여 코드와 결과를 확인하실 수 있습니다. 

직접 실행하고 싶으신 경우 [Anaconda](https://store.continuum.io/cshop/anaconda/) 패키지를 이용하여 Python, Numpy, Numba, Cython, SciPy, Matplotlib, IPython, Pandas를 설치하신 후 (한꺼번에 자동으로 설치됩니다) github에서 소스 코드를 받아서 실행하시면 됩니다.
실행시

    ipython notebook --pylab=inline Normalization.ipynb

와 같이 실행해주세요.
단, 상수곱 예제의 실행을 위해서는 BP 속도모델, 이득 제어를 위해서는 공통송신원모음, 평활화를 위해서는 Marmousi 속도모델 파일이 필요합니다. 다른 모델로 바꿔서 사용 가능하나, 같은 모델로 실행하기 원하실 경우에는 [메일](mailto:wansooha@pknu.ac.kr) 주시면 보내드리겠습니다. 감사합니다.

## Results
- [결과 그래프](http://nbviewer.ipython.org/github/pkgpl/PythonProcessing/blob/master/results/Results.ipynb)

## Algorithms
- [표준화](http://nbviewer.ipython.org/github/pkgpl/PythonProcessing/blob/master/algorithms/Normalization.ipynb)
- [상수곱](http://nbviewer.ipython.org/github/pkgpl/PythonProcessing/blob/master/algorithms/Scaling.ipynb)
- [이득 제어](http://nbviewer.ipython.org/github/pkgpl/PythonProcessing/blob/master/algorithms/Gain_seismo.ipynb)
- [트레이스 중합](http://nbviewer.ipython.org/github/pkgpl/PythonProcessing/blob/master/algorithms/Stack.ipynb)
- [이동 평균](http://nbviewer.ipython.org/github/pkgpl/PythonProcessing/blob/master/algorithms/MovingAverage.ipynb)
- [이산 푸리에 변환](http://nbviewer.ipython.org/github/pkgpl/PythonProcessing/blob/master/algorithms/Dft.ipynb)
- [행렬곱](http://nbviewer.ipython.org/github/pkgpl/PythonProcessing/blob/master/algorithms/Matmult.ipynb)
- [1차원 파동 방정식 모델링](http://nbviewer.ipython.org/github/pkgpl/PythonProcessing/blob/master/algorithms/Wave1d.ipynb)

## Scalability
- [이득 제어](http://nbviewer.ipython.org/github/pkgpl/PythonProcessing/blob/master/scalability/Gain_scale.ipynb)
- [이산 푸리에 변환](http://nbviewer.ipython.org/github/pkgpl/PythonProcessing/blob/master/scalability/Dft_scale.ipynb)
- [행렬곱](http://nbviewer.ipython.org/github/pkgpl/PythonProcessing/blob/master/scalability/Matmult_scale.ipynb)

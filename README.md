# Data-Analysis-with-Open-Source

## 한국방송통신대학교 컴퓨터과학과 '오픈소스 기반 데이터 분석' 

## 1. Setting up the Environment for Mac m2
    conda create -n data_analysis python=3.10
    conda activate data_analysis

    pip install bitsandbytes==0.42.0 vllm==0.7.3 transformers==4.48.2

matplotlib
lxml
prophet
sklearn
statsmodels
seaborn
ydata_profiling
tensorflow

brew install libomp
export KMP_DUPLICATE_LIB_OK=TRUE
pip install 'accelerate>=0.26.0'

## 2. Setting up the Environment for Ubuntu 24.04.2 LTS 2080ti(Driver Version: 550.120 CUDA Version: 12.4 )
    conda create -n test_vLLM python=3.10
    conda activate test_vLLM

    pip install bitsandbytes==0.45.3 vllm==0.7.3 transformers==4.48.2
    pip install matplotlib
    pip install lxml
    pip install pandas
    pip install 'accelerate>=0.26.0'
    pip install wordcloud
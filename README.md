# House Price Prediction

## Team

| ![권혁주](https://avatars.githubusercontent.com/u/156163982?v=4) | ![김동균](https://avatars.githubusercontent.com/u/156163982?v=4) | ![김신혜](https://avatars.githubusercontent.com/u/156163982?v=4) | ![민동욱](https://avatars.githubusercontent.com/u/156163982?v=4) |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: |
|            [권혁주](https://github.com/juyoll)             |            [김동균](https://github.com/sq4567)             |            [김신혜](https://github.com/upstageailab2324)             |            [민동욱](https://github.com/mindw96)             |    
|                            담당 역할                             |                            팀장, 담당 역할                             |                            담당 역할                             |                            팀원                            |

## 1. Competiton Info

### Overview

- 주어진 자료를 통해 아파트가격을 예측하는 모델을 만듭니다.
- 주어진 자료 외 추가적인 데이터가 얼마나 모델에 영향을 끼치는지 예측하며 모델응 수정합니다.

### Timeline

- March 10, 2024 - Start Date
-  April 2, 2024 - Final submission deadline

### Evaluation



## 2. Components

### Directory

- _Insert your directory structure_

## 3. Data descrption

### Dataset overview
train

시군구, 아파트명, 면적 등 아파트 가격에 영향을 끼칠만한 feature들이 있습니다. 

test

bus_feature

-정류소명, x,y 좌표, 등 버스 정류장에 대한 정보가 들어있습니다. 


subway_features

- 역이름, 호선, 위경도 자표가 들어있습니다.
버스 feature와 마찬가지로 아파트 가격과의 관계를 알아볼 수 있습니다. 

### EDA
- 결측치 제거.
- 이상치 제거.
- heatmap을 통한 feature중요도 파악. 

### Feature engineering

- BaseLine을 기반으로 진행합니다.

- 시군구를 강남, 강북으로 나눕니다.
- 주요 아파트명으로 분류합니다.
- 면적에 따라 아파트 크기를 나눕니다. 
## 4. Modeling

### Model description

- _Write model information and why your select this model_

### Modeling Process

- _Write model train and test process with capture_

## 5. Result

### Leader Board


- ![image](https://github.com/UpstageAILab2/upstage-ml-regression-ml-05/assets/69085457/c458ee76-322c-4782-81bd-aa7f1187c92a)

- #6, 13586.7521

### Presentation

- https://docs.google.com/presentation/d/17gBDJbw0AIFKu_I1f0rugn9mr1-mjrWI/edit?usp=sharing&ouid=111560918199565476406&rtpof=true&sd=true

## etc

### Reference

- [금리와 부동산, 그 상관관계 (2024)](https://zippoom.com/content/detail/251)
- [주택거래량은 주택가격 변동을 설명할 수 있는가? (, 임재만, 국토연구 제69권 p.g. 03~18)](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE01663054)
- []()

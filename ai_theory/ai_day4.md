# 인공지능 양성과정 Day3

## Data Set

* Training / Validation / Evaluation Set (학습 도중에 성능을 시험하고 싶을 때)
* Test Set

##  교차검증(K-Fold Validation)

* 학습 데이터를 k개로 나누고 그 묶음을 k번을 학습시킨다고 할 때 1부터 k까지 순서대로 test set이 되는 것.
* epoch : 모든 데이터가 다 돌아간 수
* Batch size : 모델 한 번 들어갈 때 데이터 묶음 크기
* Global Step : Step x Epoch, 전체 돌아간 수.

## Evaluation

* Accuracy
* Confusion Matrix

## Cost Function

* Cost는 모델이 얼마나 틀렸는지 계산하는 척도.
* 학습의 목표는 오류를 최대한 줄이는 것.
* 각 틀린 것의 대해 거리를 잰다.

## MSE and Cross Entropy

### Cross Entropy

* 정보학에서의 Entropy : 어떠한 정보를 맞거나 틀렸을 때의 놀램의 정도
* 1에 가까워질 수록 값이 커진다.

## Optimization

* 코스트를 줄이는 방법
* 최적의 가중치를 찾는다 (줄인다 > 왼쪽)
* 맨 아래로 내리지 않는다. > 모든 데이터에 최적의 결과가 아니기 때문

## Learning Rate

* 너무 느리게 낮추면 local minimum에 빠진다.
* 학습이 느려진다.
* 너무 빠르게 학습시키면 여기저기 튀어버린다.
* 속도를 높이다가 낮추는 게 일반적

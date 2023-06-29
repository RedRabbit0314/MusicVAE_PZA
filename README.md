# MusicVAE_PZA
(Music VAE, Groove MIDI Dataset)를 이용하여 4마디에 해당하는 드럼 샘플을 뽑기


## 🖥️ 프로젝트 소개
- 미디라는 데이터는 음악이 어떻게 연주되어야 하는지 나타내는 악보와 비슷한 개념
- 어느 시점에 어떤 악기를 연주하여야 하는지가 나와있는 데이터이며 .midi의 확장자명을 가지고 있다.
- Paper review [A Hierarchical Latent Vector Model for Learning Long-Term Structure in Music] 
- Magenta package code review
- Groove midi dataset review

<br>

## 🕰️ 개발 기간
* 22.06.23-22.06.29

### 🧑‍🤝‍🧑 맴버구성
- 남현수

### ⚙️ 개발 환경
- **python3.8.10**
- **magenta2.1.4**
- **anaconda**
- **tensorflow**
- **visual studio**

## 📌 결론
- magenta 패키지를 활용하는데 있어서 환경 설정 관련 dependecy 문제를 해결하기 위해 많은 시간이 소요되었었다.

- tensorflow 환경 문제로 인해서 학습이후에 생성을 만드는데 에러가 발생하여 결과물을 만들어내는 데 많은 어려움이 있었다. 모델을 import하는 과정에서 생긴 pylance error 문제, PATH 경로 설정 문제, Kernel 설정 문제 등 많은 오류가 복합적으로 생기다보니 결과물을 도출하는 과정에 있어서 많은 시간이 소요되었다.

- GPU를 사용하지 않아 학습을 하는 과정에서 많은 epoch 을 주지 못했다. 나중에 GCP를 이용하거나 Colab을 이용하여 모델을 구현할 예정
- 다른 dataset을 이용함과 동시에 다른 모델을 적용하여 새로운 모델을 만들어볼 예정
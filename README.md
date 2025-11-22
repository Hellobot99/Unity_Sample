# Unity 2D Game Study Projects

이 저장소는 유튜브 **[골드메탈(Gold Metal)]** 님의 강의를 기반으로 제작한 **3가지 유니티 2D 게임 프로젝트** 모음집입니다.
유니티 엔진의 다양한 기능(Physics, Animation, UI, Navigation 등)과 C# 스크립팅 능력을 함양하기 위해 학습 및 구현하였습니다.

> **Reference Channel**: [골드메탈 TV](https://www.youtube.com/@goldmetal/featured)

## 📂 Projects Overview

| Project 1: Undead Survivor | Project 2: 2D Platformer | Project 3: Watermelon Game |
|:---:|:---:|:---:|
| <img width="1920" height="1078" alt="image" src="https://github.com/user-attachments/assets/2d16a191-c0f3-4eb5-877a-dfca7f8eb46f" /> | <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2609d179-1449-4cad-a698-778c767f30eb" />|<img width="1080" height="2340" alt="image" src="https://github.com/user-attachments/assets/0c284d56-e808-401c-aa6c-e1c9573c775a" />|
| **로그라이크 슈팅** | **횡스크롤 액션** | **머지(Merge) 퍼즐** |

---

## 🕹️ Project Details

### 1. Undead Survivor (Vampire Survivors Clone)
무수히 몰려오는 몬스터를 상대로 생존하는 2D 로그라이크 게임입니다.

* **Key Features**:
    * **Object Pooling**: 대량의 몬스터와 투사체 최적화를 위한 풀링 시스템 구현
      
### 2. 2D Platformer (Side-Scrolling Action)
고전적인 마리오 스타일의 2D 횡스크롤 아케이드 게임입니다.

* **Key Features**:
    * **Physics Control**: Rigidbody2D를 이용한 점프, 이동, 미끄러짐 등 물리 기반 움직임 제어
    * **Raycast Interaction**: 레이캐스트를 활용한 지형 감지(Ground Check) 및 적 탐지 로직
    * **UI & Scene**: 점수 획득, 체력 관리, 낙사 처리 및 스테이지 전환 구현
    * **Enemy AI**: 지형 끝에서 자동으로 회전하거나 플레이어를 따라오는 몬스터 패턴

### 3. Watermelon Game (Suika Game Clone)
과일을 떨어뜨려 같은 종류끼리 합치고 더 큰 과일을 만드는 물리 기반 퍼즐 게임입니다.

* **Key Features**:
    * **Physics Merge**: `OnCollisionEnter2D`를 활용하여 같은 오브젝트 충돌 시 상위 레벨 오브젝트로 병합(Merge)
    * **Drag & Drop**: 마우스/터치 입력을 좌표로 변환하여 과일 낙하 위치 제어
    * **Limit Line**: 데드라인(Game Over Line) 초과 시 게임 종료 판정 로직 구현
    * **Effect & Sound**: 합쳐질 때의 파티클 이펙트 및 타격감 있는 사운드 처리

---

## 🛠 Tech Stack

- **Engine**: Unity 202x.x (LTS)
- **Language**: C#
- **IDE**: Visual Studio
- **Tools**: Git

---
*This repository contains code and assets for study purposes.*

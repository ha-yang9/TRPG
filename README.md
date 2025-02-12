# 게임 소개
> Text RPG 게임 Visual Studio를 이용한 Text Game

콘솔을 사용해서 진행하는 RPG입니다.
1. 게임 시작 화면
이 부분은 게임을 시작했을 때 사용자에게 보여지는 화면입니다. 사용자에게 게임의 간단한 소개와 시작할 수 있는 행동을 알려줍니다. 예제에서는 각 숫자에 대응하는 행동을 선택할 수 있도록 구성되어 있습니다.<hr>
![image](https://github.com/chojongwan/TRPG/assets/79524474/e6079a6f-2967-47bc-a0f1-e818b028d10f)<hr>

# 게임 진행

## 게임 종료
0번을 누르면 게임을 종료할 수 있습니다.

## 상태 보기
1번을 누르면 현재 캐릭터의 상태를 볼 수 있습니다.

## 인벤토리
2번을 누르면 현재 보유하고있는 아이템 목록을 표시합니다. 아이템을 장착할 수 있고 또한 해제할 수 도있습니다.

## 상점
3번을 누르면 상점으로 이동되고 현재 보유한 골드와 구매할 수 있는 아이템 목록이 표시됩니다.
아이템 구매와 판매가 가능합니다.
![image](https://github.com/chojongwan/TRPG/assets/79524474/3e58dc71-0968-4964-be38-7c8e3ccf8b26)<hr>

원하는 아이템을 구매하면 품절된 아이템은 [구매완료] 라는 표시와 함께 다시 구매 할 수 없습니다.
그리고 보유하고 있는 아이템을 절반의 가격으로 판매할 수 있고 판매한 아이템은 [구매완료] 표시가 없어지고 다시 구매할 수 있습니다.

## 던전
4번을 누르면 던전으로 이동할 수 있습니다.
던전은 쉬움, 보통, 어려움으로 구성되어있고 방어력을 기준으로 클리어 할 수 있습니다.
![image](https://github.com/chojongwan/TRPG/assets/79524474/38c31279-14f9-4ed0-8efb-1f5a981ed5b9)<hr>
하지만 초반에는 방어력이 부족하기 떄문에 랜덤성으로 40퍼센트 확률로 클리어를 할 수 있습니다.
공격력은 던전을 클리어 한 뒤 얻을 수 있는 골드를 추가로 얻을 수 있는 능력치 입니다.
### 던전 목록
![image](https://github.com/chojongwan/TRPG/assets/79524474/d3dcfb8c-9f86-4619-b478-bd3532906f58)<hr>
쉬움은 필요 방어력 15 [보상 1000G]
보통은 필요 방어력 30 [보상 2000G]
어려움은 필요 방어력 60 [보상 5000G]

## 레벨 시스템
레벨은 오를수록 공격력 +1, 방어력 +2가 오릅니다. 하지만 쉬운 던전은 레벨업하기가 어렵고 던전은 어려울수록 레벨업하기가 쉽습니다.

## 게임 오버
HP가 0가 되면 모든 돈을 잃고 던전 입구에서 깨어납니다.
![image](https://github.com/chojongwan/TRPG/assets/79524474/529358ae-ec28-45e9-8c97-f267159ec621) <hr>

## 휴식하기
5번을 누르면 휴식을 할 수 있고 500G를 지불하고 HP를 100까지 채웁니다. 500G가 없거나 HP가 가득 채워져있으면 휴식할 수 없습니다.

## 저장하기, 불러오기
6번을 누르면 저장하고 7번을 누르면 마지막에 저장한 정보를 불러옵니다. 
게임을 초기화 하고싶으면 처음 실행할때 불러오기 말고 저장하기를 누르면 초기화 할수있습니다.
